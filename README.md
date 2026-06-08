# mockup-to-game-ui

Codex skill for turning UI mockups, GPT image references, and AI concept images into layered PNG game UI assets, asset manifests, and editable UI scenes.

## What It Does

- Uses the mockup as style and layout reference, not as a baked runtime background.
- Requires bitmap PNG asset generation through `gpt-image-2` / Responses `image_generation`.
- Splits UI frames, panels, cards, buttons, props, and decorations into separate runtime layers.
- Keeps text, icons, values, and dynamic content bound by the target game project.
- Supports integration into editable Godot, Unity, or HTML UI scenes.

## Files

- `SKILL.md`: main skill instructions.
- `references/prompt-patterns.md`: prompt templates for asset sheets.
- `agents/openai.yaml`: Codex skill interface metadata.

## Usage

Install or copy this folder into your Codex skills directory, then invoke:

```text
$mockup-to-game-ui
```

