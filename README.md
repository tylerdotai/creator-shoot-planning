<!-- PROJECT INFO -->
<!-- Don't remove this block. Fill in below. Delete all comment lines when done. -->
<!--
*** START: PROJECT METADATA (required for automated badge generation) ***
owner: tylerdotai
repo: creator-shoot-planning
description: A repeatable guided workshop for planning any photography or videography shoot — from brief to shot list to execution. Built for content creators and videographers.
topics: [photography, videography, content-creation, shoot-planning, location-scout, creative]
status: active
*** END: PROJECT METADATA ***
-->
<!-- BADGES -->
<!-- Add shields.io badges below. See https://shields.io/badges for options. -->

[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)](https://github.com/tylerdotai/creator-shoot-planning)
[![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)
[![Last Updated](https://img.shields.io/badge/Last%20Updated-2026-blue?style=flat-square)](https://github.com/tylerdotai/creator-shoot-planning/commits/main)

---

# Creator Shoot Planning Workshop

> **Plan any photography or videography shoot — from brief to shot list to execution. In a repeatable, guided process.**

A step-by-step workshop for taking any content creator from "I want to shoot something" to a concrete plan they can execute on location — without freezing, without second-guessing angles, without wondering if the audio is working.

Every time a creator wants to shoot, they freeze. They get overwhelmed by the location, distracted by people watching, and lost mid-shoot not knowing what angle to try next. This workshop solves that. It gives you a repeatable planning process — and a ready-made template system — so you can go from idea to executed shoot in less time, with no mid-shoot panic.

Built for content creators and videographers who shoot their own content. Works for any camera, any location, any vibe.

---

## Table of Contents

- [What This Is](#what-this-is)
- [How It Works](#how-it-works)
- [The Workshop](#the-workshop)
- [The Shoot Template](#the-shoot-template)
- [Who This Is For](#who-this-is-for)
- [Quick Start](#quick-start)
- [File Map](#file-map)

---

## What This Is

A **guided, human-run planning workshop** — not an automated pipeline. You run the steps. You capture the brief. You build the plan. The output is a complete **shoot guide** you can take on location and execute without thinking.

Think of it as the difference between wingin' it and knowing exactly what you're doing when you step on set. This gives you the prep, the shot list, and the confidence to execute.

### What you get

- **A brief capture system** — structured questions to pin down the vibe, location, and must-have shots
- **A location research framework** — what to look for, what to avoid, when to shoot
- **A visual style guide** — how to articulate the aesthetic so it's actionable, not vague
- **A concrete shot list** — exact shots with framing instructions, not "get something wide"
- **An angle confidence system** — three fallback angles so you never freeze mid-shoot
- **An audio plan** — scenario-based mic decisions, not guesswork
- **An anxiety protocol** — what to do when people are staring, when you freeze, when you lose the shot

---

## How It Works

```
1. Brief        → Capture the shoot parameters (use RESEARCH.md)
2. Research    → Scout the location (light, crowds, access, parking)
3. Style       → Define the visual aesthetic with reference images
4. Shot List   → Build exact shots with framing + what to say
5. Angle System → Three fallback angles for on-location confidence
6. Audio Plan   → Mic decision tree for the scenario
7. Anxiety      → Pre-mortem protocols for known pain points
8. Execute      → Pre-shoot prep, on-location flow, post-shoot debrief
```

Each step has a dedicated guide in `/docs/`. Start at `docs/01-brief.md` and work your way through.

---

## The Workshop

| Step | Guide | What You Do |
|------|-------|-------------|
| 01 | [Brief](./docs/01-brief.md) | Capture vibe, location, duration, gear, must-haves, aesthetic refs |
| 02 | [Research](./docs/02-research.md) | Scout the location — light, crowds, access, parking, permits |
| 03 | [Style](./docs/03-style.md) | Define the visual aesthetic with concrete references |
| 04 | [Shot List](./docs/04-shot-list.md) | Build exact shots with framing + what to say to talent |
| 05 | [Angle System](./docs/05-angles.md) | Three fallback angles — never freeze mid-shoot |
| 06 | [Audio Plan](./docs/06-audio.md) | Mic decision tree for the scenario |
| 07 | [Anxiety](./docs/07-anxiety.md) | Pre-mortem for people staring, freezing, losing shots |
| 08 | [Execute](./docs/08-execute.md) | Pre-shoot prep, on-location flow, post-shoot debrief |

---

## The Shoot Template

The `shoot-template/` directory is your starting point for every new shoot. Copy it, fill it in, and it becomes your shoot guide for on-location use.

```
shoot-template/
├── BRIEF.md        ← Shoot parameters — vibe, location, duration, refs
├── SHOTS.md        ← Shot list with exact framing + what to say
├── ANGLES.md       ← Three fallback angles for this specific shoot
├── AUDIO.md        ← Mic decision tree for this location
└── GEAR.md         ← Gear checklist, settings to pre-lock, storage plan
```

See [WORKSHOP.md](./WORKSHOP.md) for the full walkthrough.

---

## Who This Is For

- **Content creators** who shoot their own video and photo
- **Videographers** who want a repeatable pre-shoot planning system
- **Creators who freeze** on location — who get overwhelmed, distracted, or lose the shot

You should know how to operate your camera. This workshop doesn't teach you camera basics — it teaches you how to plan so you can execute without thinking.

---

## Quick Start

```bash
# 1. Clone this repo as your starting point
git clone https://github.com/tylerdotai/creator-shoot-planning.git my-shoot-workspace
cd my-shoot-workspace

# 2. Read the workshop guide
cat WORKSHOP.md

# 3. Start at Step 01
cat docs/01-brief.md

# 4. Copy the shoot template
cp -r shoot-template/ /path/to/your/shoot-plan/
```

---

## File Map

```
creator-shoot-planning/
├── README.md              ← You are here
├── WORKSHOP.md            ← Full workshop walkthrough (start here)
├── RESEARCH.md            ← Shoot brief capture template
│
├── docs/
│   ├── 01-brief.md       ← Step 1: Capture the brief
│   ├── 02-research.md    ← Step 2: Scout the location
│   ├── 03-style.md       ← Step 3: Define visual aesthetic
│   ├── 04-shot-list.md  ← Step 4: Build the shot list
│   ├── 05-angles.md     ← Step 5: Angle confidence system
│   ├── 06-audio.md       ← Step 6: Audio decision tree
│   ├── 07-anxiety.md     ← Step 7: Anxiety management on location
│   └── 08-execute.md     ← Step 8: Pre-shoot, on-location, debrief
│
├── shoot-template/
│   ├── BRIEF.md          ← Shoot parameters template
│   ├── SHOTS.md          ← Shot list with framing template
│   ├── ANGLES.md         ← Fallback angles template
│   ├── AUDIO.md          ← Audio plan template
│   └── GEAR.md           ← Gear checklist template
│
├── skills/
│   └── SKILL_TEMPLATE.md ← How to write any shoot-planning skill
│
└── templates/
    ├── shoot-brief.md        ← Blank brief template
    ├── shot-list-blank.md    ← Blank shot list
    ├── gear-checklist.md     ← Gear checklist for any shoot
    └── location-research.md  ← Location scout worksheet
```

---

## FAQ

**Q: What cameras does this work with?**
A: Any camera. The shot framing, angle, and audio guidance is gear-agnostic. Gear-specific notes are in the templates.

**Q: What if I don't know what I want to shoot?**
A: Start with the brief. The questions guide you toward a direction even if you arrive with nothing.

**Q: Can I skip steps?**
A: You can, but you shouldn't. Each step feeds the next. Skipping style means your shot list is unfocused. Skipping angle planning means you're vulnerable to freezing mid-shoot.

**Q: Does this work for photo-only shoots?**
A: Yes. The shot list and angle system apply to photo. Audio steps can be skipped for stills.

**Q: Can I use this for a client shoot?**
A: Yes. Fill in the templates with the client's brief, their gear, their client's aesthetic.

---

## Contributing

Improvements welcome. If you run this workshop with a real shoot, come back and share what worked, what didn't, and what you'd add. Open an issue or a PR.

---

## Credits

Built by [Tyler Delano](https://tylerdotai).

Based on real shoot planning sessions across streetwear, urban exploration, events, and content creator workflows.

---

<!-- FOOTER -->
<!-- Don't modify. Auto-generated by badge script. -->
<!-- OPERATOR: tyler | TIMESTAMP: 2026-07-06T00:00:00Z | VERSION: 1.0.0 -->
