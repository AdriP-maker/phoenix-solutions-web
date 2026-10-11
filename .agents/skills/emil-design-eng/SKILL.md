---
name: emil-design-eng
description: "Encodes Emil Kowalski's philosophy on UI polish, component design, animation decisions, tactile micro-interactions, and invisible craft details."
metadata:
  homepage: https://emilkowal.ski/skill
---

# Emil Kowalski — Design Engineering & Motion

Build interfaces where every detail compounds into something that feels right. Taste is the differentiator.

## Core Rules & Micro-Interactions
- **Tactile feedback**: Buttons must have `:active` states (`transform: scale(0.975)` or `-translate-y-[1px]`).
- **Snappy transitions**: 150ms-220ms with custom easing `cubic-bezier(0.16, 1, 0.3, 1)` or `ease-out`. Never use sluggish linear or `ease-in` for entering elements.
- **Subtle borders**: 1px borders with translucency (`rgba(255, 255, 255, 0.08)` or theme tokens) rather than heavy outlines.
- **Elevation & Lighting**: Tint drop shadows to background hues. Radial glows should be subtle and ambient.
