# Atelier UI

A collection of UI design skills for premium digital products.

## Available Skills

| Skill | Description |
|-------|-------------|
| `editorial-designer` | Editorial/fashion magazine aesthetic for lifestyle apps |
| `apple-ui-designer` | iOS Human Interface Guidelines, native Apple feel |

## Installation

**Via Marketplace:**
```bash
claude /plugin marketplace add heyman333/atelier-ui
claude /plugin install heyman333@atelier-ui
```

To update:
```bash
claude /plugin marketplace update atelier-ui
```

**Codex (project-scoped):**
1) Add `skills/<skill-name>/` to your repo
2) Register it in `README.md` or `AGENTS.md`:
   - editorial-designer: ... (file: skills/editorial-designer/SKILL.md)
   - apple-ui-designer: ... (file: skills/apple-ui-designer/SKILL.md)
3) Use: `$editorial-designer <request>` or `$apple-ui-designer <request>`

**Codex (global):**
1) Copy the folder to `$CODEX_HOME/skills/<skill-name>` (usually `~/.codex/skills/`)
2) Use: `$editorial-designer <request>` or `$apple-ui-designer <request>`

## Overview

Atelier UI provides multiple design skills for different aesthetics:

### editorial-designer
Brings the refined aesthetic of fashion editorials and magazine layouts to digital product design. Interfaces feel curated, confident, and intentional.

### apple-ui-designer
Applies iOS Human Interface Guidelines and modern Apple design language. Interfaces feel native, calm, and inevitable — like first-party Apple apps.

## Design Example

![Atelier UI Design Example](images/image.jpg)

This example showcases a fashion e-commerce app designed with Atelier UI principles:

- **Bold Typography** — "GET READY TO SLAY IN STYLE" demonstrates confident, editorial-style headlines
- **Dark & Light Contrast** — Strategic use of dark cards against light backgrounds creates visual depth
- **Accent Color Strategy** — Yellow serves as a cohesive accent throughout, from clothing imagery to UI elements
- **Minimal UI Chrome** — Clean buttons, subtle icons, and text-based navigation reduce visual noise
- **Card-Based Layout** — Rounded corners and generous padding create a premium, tactile feel
- **Whitespace as Design** — Intentional breathing room guides the eye and elevates content

## Design Principles

- **Typography-first** — Large, expressive headlines with strong visual hierarchy
- **Monochrome foundation** — White, off-white, black, charcoal, beige
- **Editorial tension** — Intentional asymmetry, broken grids, generous whitespace
- **Minimal affordances** — Flat buttons, text-based actions, trust user intuition
- **Subtle motion** — Opacity, translate, scale ≤ 1.05. No bounce or spring.

## When to Use Each Skill

### editorial-designer
- Fashion, lifestyle, and premium brand experiences
- Landing pages with bold typography
- 20s-30s urban audience targeting

### apple-ui-designer
- iOS-native mobile apps
- Apps following Human Interface Guidelines
- Native-feeling system UI components

## License

MIT
