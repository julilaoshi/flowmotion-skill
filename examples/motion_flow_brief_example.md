# Motion Flow Brief Example

## Goal

Show how raw ideas become a presentation-ready flowchart.

## Motion Timeline

```json
{
  "canvas": "16:9",
  "sequence": [
    {"time": 0.3, "action": "show_node", "target": "raw_notes"},
    {"time": 1.0, "action": "show_node", "target": "flowmotion_skill"},
    {"time": 1.4, "action": "draw_edge", "target": "raw_notes_to_skill"},
    {"time": 2.4, "action": "show_internal_steps", "target": ["cluster", "compress", "find_path"]},
    {"time": 3.4, "action": "show_node", "target": "flow_spec"},
    {"time": 4.2, "action": "draw_edge", "target": "skill_to_flow_spec"},
    {"time": 5.4, "action": "show_outputs", "target": ["static", "motion", "3d"]}
  ]
}
```

## Visual Rule

The viewer should understand the transformation:

```text
messy input -> structure -> reusable visual flow
```

Do not reveal every node at once.

