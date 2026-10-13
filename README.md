# Prose Revision Skill for Claude

A Claude Skill for revising draft prose — essays, papers, memos, reports — by
designing the **reader's path** through the ideas the author already wants to
express. Its guiding principle is **idea flow before linguistic flow**.

## What It Does

This skill treats revision as designing the route a reader takes through an
argument, and treats awkward writing as a symptom of a broken route rather than
just bad phrasing. When active, Claude will:

* **Walk the reader's path** — read the draft sentence by sentence as a reader
  would, checking what the reader knows and expects at each step
* **Diagnose leaps, detours, and backtracking** — steps the reader can't make,
  material that pulls them off course, and places they must reread or reinterpret
* **Aim for the shortest reliable path, not the fewest words** — sometimes cutting
  a detour, sometimes adding a bridging sentence the author skipped
* **Work at every level** — sentence, paragraph, section, and whole — fixing the
  larger route (paragraph and section order) before rewriting inside paragraphs
* **Stay conservative on content** — preserve the author's voice, substantive
  claims, and *claim strength* (no turning "suggests" into "shows")
* **Offer revised versions** distinguished by how much they restructure (light,
  moderate, or full rebuild), with a note on the tradeoff
* **Leave well enough alone** — if a draft already reads well, say so rather than
  manufacture edits

This is not proofreading. This skill helps put the structure of a rough draft into
shape. Proofreading is a late pass for typos and final copy-editing.

## Installation

1. Download this repository as a zip file (click **Code → Download ZIP** above)
2. In [claude.ai](https://claude.ai), go to **Customize → Skills**
3. Upload the zip file
4. Confirm the skill appears in your skills list and is toggled on

> **Requirement:** Code execution and file creation must be enabled in
> **Settings → Capabilities**.

## Usage

Just ask naturally:

* *"Revise this paragraph for flow"*
* *"Help me tighten this section — the argument feels tangled"*
* *"This draft reads awkwardly; can you restructure it?"*

Claude will detect the prose-revision context, load this skill automatically, and
diagnose the reader's path before touching the wording. You do not need to give
any special instructions.

## File Structure

```
prose-revision-skill-ht-anthony-lee-zhang/
├── SKILL.md    # The skill: reader's path, stance, workflow, output style, example
├── README.md   # This file
└── LICENSE     # MIT
```

## Background

Builds on Anthony Lee Zhang's prose-revision skill ("ht" = hat tip), including
his later framing of revision as designing the **reader's path** through the
prose. This version adapts those ideas for Claude and adds extensions:
structure above the paragraph level, voice and claim-strength preservation, guidance
for leaving good drafts alone, and a worked example.

## License

MIT — see `LICENSE`.
