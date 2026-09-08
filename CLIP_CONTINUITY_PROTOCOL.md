# CLIP_CONTINUITY_PROTOCOL.md

**Official Multi-Clip Continuity Workflow**

Status: AUTHORITATIVE

---

## Why This Exists

Most current AI video generators have length limits.  
A 30-second advertisement is therefore produced as multiple shorter clips that must feel like one continuous piece.

---

## Official Workflow

```
CLIP 1
  ↓
FINAL FRAME / STATE CAPTURE
  ↓
CLIP 2  (inherits final state of Clip 1)
  ↓
FINAL FRAME / STATE CAPTURE
  ↓
CLIP 3  (inherits final state of Clip 2)
  ↓
...
  ↓
FINAL EDIT (assembly + polish)
```

---

## What the Next Clip Must Inherit

From the final frame / state of the previous clip:

| Element | Must Carry Forward |
|---------|--------------------|
| Character identity | Exact same AVA |
| Character location | Same position in space |
| Character pose | Approximate posture and orientation |
| Character expression | Emotional continuity |
| Camera position | Same or continuously motivated move |
| Camera direction | Coherent |
| Lighting | Same key, fill, color temperature |
| Environment | Same architecture, furniture, set dressing |
| Props | Same objects in same places |
| Wardrobe | Identical clothing |
| Background people | Same individuals, clothing, positions |
| Emotional / story state | Unbroken narrative |

---

## Prompt Instruction Pattern

Every subsequent clip prompt must begin with language equivalent to:

> CONTINUE DIRECTLY FROM THE FINAL FRAME OF THE PREVIOUS CLIP.  
> Do NOT restart the scene.  
> Maintain exact character identity, environment, lighting, wardrobe, and camera geography.

---

## Ending State Requirement

Every clip document must define an explicit **ENDING STATE** that the next clip is required to begin from.

---

## Failure Modes to Avoid

- Treating each clip as an independent video
- Allowing the AI to redesign the office or characters
- Changing AVA’s appearance between clips
- Jumping camera position without motivation
- Resetting emotional energy without story reason
