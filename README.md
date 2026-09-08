# AVA Character System

**Official OPERAVA AI Character Bible + AI Video Generation System**

This repository is the **single source of truth** for AVA — OPERAVA’s official AI character used in advertising, video production, and brand storytelling.

---

## Who is AVA?

**AVA** is OPERAVA’s emergency operational backup.

She is not a literal superhero.  
The dramatic / superhero presentation is a recurring **advertising and comedic device**.

In reality, AVA is a calm, capable, professional operational specialist who can step into multiple roles when a business suddenly needs help:

- Call Center / Customer Support
- Web Development
- Automation
- Administrative Support
- Reporting & Data
- General Operational Backup

**Core identity:** Capable · Calm · Professional · Intelligent · Adaptable · Reliable · Helpful · Confident · Efficient · Slightly witty · Calm under pressure.

---

## What is OPERAVA?

OPERAVA is the brand behind AVA.  
AVA represents OPERAVA’s ability to provide flexible, high-quality operational capacity on demand.

---

## Repository Purpose

This repository enables any AI system, video creator, designer, or team member to:

- Understand exactly who AVA is
- Know precisely what AVA looks like
- Maintain perfect visual and behavioral continuity
- Generate multi-clip videos that feel like one continuous advertisement
- Create new campaigns without character drift
- Use any modern AI image/video generator (Gemini, Grok, Veo, Sora, Runway, Kling, etc.) while preserving identity

**One AVA. One canonical identity. Many stories. Zero drift.**

---

## Authority Hierarchy (Highest → Lowest)

1. **Canonical AVA reference images** (`references/canonical/`)
2. `CHARACTER_BIBLE.md`
3. `VISUAL_BIBLE.md`
4. `CONTINUITY.md`
5. `VIDEO_MASTER.md`
6. Campaign Bibles (`campaigns/`)
7. Individual campaign / video documents
8. Individual clip prompts
9. AI-generated output

Lower-level instructions **must never** override higher-level identity rules unless an explicit canonical update is approved and documented.

---

## Quick Start — Creating a New AVA Video

1. Read `CHARACTER_BIBLE.md` and `VISUAL_BIBLE.md`
2. Read `VIDEO_MASTER.md` and `CLIP_CONTINUITY_PROTOCOL.md`
3. Use `VIDEO_PROMPT_TEMPLATE.md` for every generation
4. For multi-clip videos, always pass the **final frame / state** of the previous clip into the next prompt
5. Run `QUALITY_CONTROL.md` checks before accepting any output
6. Store generated assets under `generated/` — never mix them with canonical references

---

## Core Documents

| Document | Purpose |
|----------|---------|
| `CHARACTER_BIBLE.md` | Who AVA is, personality, role, capabilities |
| `VISUAL_BIBLE.md` | Strict visual identity derived from reference images |
| `CANONICAL_REFERENCE_POLICY.md` | How to use reference images |
| `CONTINUITY.md` | What must never change |
| `VIDEO_MASTER.md` | Universal rules for all AI video generators |
| `CLIP_CONTINUITY_PROTOCOL.md` | Multi-clip workflow |
| `VIDEO_PROMPT_TEMPLATE.md` | Master prompt structure |
| `VOICE_AND_DIALOGUE.md` | How AVA speaks |
| `CAMPAIGN_TEMPLATE.md` | Template for future campaigns |
| `VERSIONING.md` | How identity changes are handled |
| `QUALITY_CONTROL.md` | Acceptance checklist |
| `AUTHORITY.md` | Full hierarchy |

---

## Campaigns

### Northstar Operations Inc. (Fictional)

Location: Austin, Texas, USA  
Purpose: Believable modern U.S. corporate environment for advertising.

- `campaigns/northstar/CAMPAIGN_BIBLE.md`
- `campaigns/northstar/emergency-backup/` — the flagship 30-second advertisement

---

## Asset Organization

```
references/
  canonical/          ← AUTHORITATIVE AVA images (never overwrite)
    portraits/
    full-body/
    expressions/
    environment/
generated/
  video/
  stills/
  experiments/
```

**Rule:** Canonical references define AVA. Generated assets are outputs only.

---

## Critical Rules (Never Violate)

- **DO NOT** change AVA’s face, facial proportions, hair, hair color, freckles, apparent age, or body proportions.
- **DO NOT** invent a different-looking “version” of AVA.
- **DO NOT** mix generated images into the canonical folder.
- **DO NOT** reset environment, lighting, wardrobe, or camera geography between clips when continuity is required.
- **DO NOT** turn AVA into a literal superhero. The costume is a storytelling device.

---

## License

MIT License — Copyright (c) 2026 Operava

---

**This repository is designed so that a completely new AI system, given only these files, can correctly answer every question about AVA’s identity, appearance, behavior, and production process.**
