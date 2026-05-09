# FlowMotion Skill

<p align="center">
  <strong>From messy voice notes to motion-ready flowcharts.</strong><br />
  FlowMotion Skill turns spoken ideas, SRT transcripts, and rough planning sessions into structured visual flows with clear reveal order, connection logic, and motion-diagram briefs.
</p>

<p align="center">
  <a href="https://github.com/julilaoshi/flowmotion-skill"><img alt="Star Repo" src="https://img.shields.io/badge/Star-Repo-f6c343?style=for-the-badge&logo=github&logoColor=111111" /></a>
  <a href="./skill/SKILL.md"><img alt="Read Skill" src="https://img.shields.io/badge/Read-Skill-1f6feb?style=for-the-badge" /></a>
  <a href="#how-to-install"><img alt="Install" src="https://img.shields.io/badge/Install-111111?style=for-the-badge" /></a>
  <a href="./examples/srt_to_flowchart_example.md"><img alt="Example" src="https://img.shields.io/badge/View-Example-2da44e?style=for-the-badge" /></a>
</p>

Public `v1.0`. This repository contains the public-safe version of FlowMotion Skill.

English | [简体中文](./README.zh-CN.md)

## Demo

<p align="center">
  <img src="./site/assets/flowmotion-skill-demo.gif" alt="FlowMotion Skill motion flow demo" width="76%" />
</p>

<p align="center">
  <strong>Video demo:</strong> publishing soon.
</p>

## Start Here

- [Star the repository](https://github.com/julilaoshi/flowmotion-skill)
- [Read the public skill file](./skill/SKILL.md)
- [Try the SRT-to-flowchart example](./examples/srt_to_flowchart_example.md)

## What This Unlocks

- turn loose brainstorming into a structured flow
- convert spoken scripts or SRT transcripts into diagram-ready briefs
- prepare flowcharts for presentation, teaching, video explainers, and product storytelling
- design motion flow specs where nodes appear step by step and paths reveal over time
- hand off diagram logic to PPT, HTML, video, or 3D follow-up work
- separate structure, layout, connection design, and motion timing before implementation

## Why This Repository Exists

Most idea capture stops at text.

FlowMotion Skill exists for the moment after capture: when the raw thoughts need to become a flow that someone else can understand in a meeting, a class, a video, or a product demo.

The public version focuses on the reusable method:

- gather scattered input
- compress it into a main path
- design connection logic
- prepare a motion-ready visual brief

## What This Repository Includes

- the public FlowMotion Skill file
- public-safe examples
- reusable templates for flow specs, connection specs, and motion timelines
- a privacy and release checklist
- no private local workflow files

## What This Repository Does Not Include

- private transcripts
- local absolute paths
- internal project reports
- internal score notes or user chat logs
- private Skill chains from my local workspace
- copyrighted third-party examples
- browser automation scripts or local rendering scripts
- the full internal production workflow shown on social media

## Why The Social Media Version Looks Stronger

The public repository focuses on FlowMotion Skill itself.

In my internal workflow, stronger demos may also use:

- design skills for final visual polish
- coding workflows for HTML or video implementation
- media tools for GIF or MP4 export
- accumulated private examples and intermediate assets

This public version opens the reusable method and templates. It does not ship the full private production system.

## How To Install

### Recommended: ask your coding agent to install it

Open Codex, Claude Code, or another coding agent and paste:

```text
Please help me install FlowMotion Skill.

Repository:
https://github.com/julilaoshi/flowmotion-skill

Please do the following:
1. Read README.md and skill/SKILL.md
2. Decide where this coding agent expects user skills to live
3. Copy or link the skill/ folder into the readable skills directory
4. Confirm that skill/SKILL.md is readable
5. Run a minimal test: turn a messy note into a flow_spec and connection_spec
6. Do not modify the core rules of the Skill
```

### Manual install fallback

```bash
git clone https://github.com/julilaoshi/flowmotion-skill.git
cd flowmotion-skill
```

Then copy `skill/SKILL.md` into your coding agent's skills directory, or ask your agent to do it.

Restart your coding agent after installation.

## Quick Test

Paste this into your coding agent:

```text
Use FlowMotion Skill.

Turn this messy idea into:
1. a core judgment
2. a flow_spec
3. a connection_spec
4. a motion_timeline

Messy idea:
I keep collecting random notes from meetings, voice memos, and article drafts.
I want a system that groups them, finds the main path, removes noise,
and turns the result into a clear flowchart I can use in a presentation.
```

## Core Workflow

FlowMotion Skill works in four steps:

1. Gather messy input.
2. Extract the core judgment, nodes, and relationships.
3. Design the layout and connection rules.
4. Hand off a static, motion, or 3D-ready brief.

The key rule:

```text
Structure first. Layout second. Connections third. Motion last.
```

## Example Outputs

- [SRT to flowchart example](./examples/srt_to_flowchart_example.md)
- [Motion flow brief example](./examples/motion_flow_brief_example.md)

## Templates

- [flow_spec_template.json](./templates/flow_spec_template.json)
- [layout_spec_template.json](./templates/layout_spec_template.json)
- [connection_spec_template.json](./templates/connection_spec_template.json)
- [motion_timeline_template.json](./templates/motion_timeline_template.json)

## Structure

- `skill/SKILL.md` - the public FlowMotion Skill file
- `agents/openai.yaml` - UI metadata for coding agents
- `examples/` - public-safe sample inputs and outputs
- `templates/` - reusable JSON scaffolds
- `references/` - privacy and release guidance
- `site/assets/` - README demo assets

## Default Repository Flow

1. Read `skill/SKILL.md`.
2. Use a public-safe note, SRT snippet, or messy idea.
3. Generate `flow_spec`, `layout_spec`, `connection_spec`, and `motion_timeline`.
4. Use the templates as a scaffold if you want a structured file.
5. Hand the brief to your preferred design, slide, video, or coding tool.

## Language Strategy

- `README.md` is English-first for GitHub discovery.
- `README.zh-CN.md` is the Chinese companion page.
- The Skill name stays `FlowMotion Skill` in both versions.

## License And Brand Boundary

The code, documentation, templates, and reusable framework are released under the MIT License.

Brand-facing identity and endorsement implication are reserved. See [BRAND_NOTICE.md](./BRAND_NOTICE.md).

## Internal vs Public Boundary

Public means:

- method
- templates
- synthetic examples
- reusable framework

Public does not mean:

- private transcripts
- internal project files
- local rendering scripts
- private workflow traces
- unpublished production assets

## Public Boundary

This public package only includes the reusable method.

Private transcripts, internal project files, local paths, unreleased examples, and personal workflow records are intentionally excluded.

See:

- [Privacy Checklist](./references/privacy_checklist.md)
- [Brand Notice](./BRAND_NOTICE.md)
- [Public Release Checklist](./PUBLIC_RELEASE_CHECKLIST.md)

## Find Juli Laoshi

FlowMotion Skill is part of Juli Laoshi's public AI workflow experiments.

<p align="center">
  <a href="https://github.com/julilaoshi"><img alt="Follow on GitHub" src="https://img.shields.io/badge/Follow-on%20GitHub-111111?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://github.com/julilaoshi/flowmotion-skill"><img alt="Star This Repo" src="https://img.shields.io/badge/Star-This%20Repo-f6c343?style=for-the-badge&logo=github&logoColor=111111" /></a>
</p>

If this Skill helps you, star the repository so you can find it again.

## License

MIT for reusable code, documentation, templates, and framework material.

Brand-facing identity is reserved. See [BRAND_NOTICE.md](./BRAND_NOTICE.md).
