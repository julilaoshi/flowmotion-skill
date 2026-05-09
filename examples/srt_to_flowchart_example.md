# SRT To Flowchart Example

## Input

```text
00:00:00,000 --> 00:00:02,000
I keep recording voice notes after meetings.

00:00:02,000 --> 00:00:05,000
The notes are messy, but they usually contain a few clear actions.

00:00:05,000 --> 00:00:08,000
I want a system that extracts the main path and turns it into a flowchart.
```

## Core Judgment

Messy spoken notes can become a clear action flow when the system separates fragments, finds the main path, and outputs a visual structure.

## flow_spec

```json
{
  "diagram_type": "motion_sequence",
  "nodes": [
    {"id": "voice_notes", "label": "Voice notes"},
    {"id": "fragments", "label": "Fragments"},
    {"id": "main_path", "label": "Main path"},
    {"id": "flowchart", "label": "Flowchart"}
  ],
  "edges": [
    {"source": "voice_notes", "target": "fragments", "type": "main_flow"},
    {"source": "fragments", "target": "main_path", "type": "main_flow"},
    {"source": "main_path", "target": "flowchart", "type": "main_flow"}
  ],
  "core_judgment": "Spoken fragments become usable when they are compressed into a main path."
}
```

## connection_spec

```json
{
  "strategy": "left_to_right",
  "edge_style": "gray_base_with_green_progress",
  "ports": "edge ports, hidden in final visual",
  "orb": true,
  "avoid_labels": true
}
```

## layout_spec

```json
{
  "canvas": {"ratio": "16:9", "width": 1280, "height": 720, "safe_margin": 64},
  "layout_type": "left_to_right_motion_sequence",
  "nodes": [
    {"id": "voice_notes", "x": 96, "y": 250, "width": 210, "height": 96},
    {"id": "fragments", "x": 390, "y": 250, "width": 210, "height": 96},
    {"id": "main_path", "x": 680, "y": 250, "width": 210, "height": 96},
    {"id": "flowchart", "x": 970, "y": 250, "width": 220, "height": 96}
  ],
  "safe_areas": ["top_title", "bottom_caption"],
  "label_rules": {
    "avoid_path_overlap": true,
    "hide_engineering_ports": true
  }
}
```

## motion_timeline

```json
{
  "duration_seconds": 7,
  "events": [
    {"time": 0.3, "action": "show_node", "target": "voice_notes"},
    {"time": 1.0, "action": "show_node", "target": "fragments"},
    {"time": 1.3, "action": "draw_edge", "target": "voice_notes_to_fragments"},
    {"time": 2.2, "action": "show_node", "target": "main_path"},
    {"time": 2.5, "action": "draw_edge", "target": "fragments_to_main_path"},
    {"time": 3.6, "action": "show_node", "target": "flowchart"},
    {"time": 3.9, "action": "draw_edge", "target": "main_path_to_flowchart"},
    {"time": 5.2, "action": "show_final_summary", "target": "Spoken notes become a clear action flow"}
  ],
  "motion_rules": {
    "path_base": "gray",
    "path_progress": "green",
    "orb": "bind_to_real_path",
    "reveal": "one_node_then_one_path"
  }
}
```
