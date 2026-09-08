# CANONICAL_REFERENCE_POLICY.md

**How Canonical Reference Images Must Be Used**

Status: AUTHORITATIVE

---

## Core Principle

**CANONICAL REFERENCE > AI INVENTION**

The images stored in `references/canonical/` are the definitive visual definition of AVA.  
Any AI image or video generation must treat them as non-negotiable ground truth.

---

## Rules for Generators and Creators

1. **Always load or reference the canonical images** when generating new AVA content.
2. If a generated result conflicts with a canonical image in face, hair, freckles, proportions, or overall identity → **reject the generation**.
3. Do not “average” AVA with other faces or styles.
4. Do not allow the model to invent a new hairstyle, hair color, or facial structure.
5. When using image-to-video or reference-guided generation, the canonical images take priority over any text description that contradicts them.
6. Generated assets must be saved under `generated/` and never copied into `references/canonical/`.

---

## What Counts as Canonical

- All original reference images currently in the repository (the 10 .webp files that defined AVA at creation).
- Any future images explicitly approved and placed into `references/canonical/` via the process in `VERSIONING.md`.

---

## What Does Not Count as Canonical

- Any AI-generated still or frame, even if it looks good.
- Experimental outputs.
- Alternate costumes or looks that have not been formally promoted to canonical status.

---

## Recommended Folder Structure

```
references/
  canonical/
    portraits/          # Close-ups and headshots
    full-body/          # Full figure, multiple angles
    expressions/        # Key emotional / performance states
    environment/        # AVA in key environments (when applicable)
  supporting/           # Non-identity references (office, props, etc.)
```

---

## Enforcement

Every generation workflow must include a visual consistency check against the canonical set (see `QUALITY_CONTROL.md`).
