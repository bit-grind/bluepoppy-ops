# Blue Poppy Design Audit

This folder is an isolated design exploration. It does not change or import any
production application code.

## Start here

- `WORKFLOW.md`: reusable design-audit process.
- `AUDIT.md`: findings and the proposed design direction.
- `before.html`: source-faithful dashboard reconstruction.
- `after.html`: proposed dashboard direction.
- `visual-comparison.html`: labeled before/after presentation board.
- `PROMPTS.md`: image-generation prompt and usage notes.
- `visuals/`: captured desktop and mobile comparisons.

## Visual outputs

- `visuals/comparison-board.png`: the main before/after board.
- `visuals/before-desktop.png` and `visuals/after-desktop.png`.
- `visuals/before-mobile.png` and `visuals/after-mobile.png`.
- `visuals/generated-concept-board.png`: a looser, warmer alternate direction.

## Preview

Serve the repository root and open either prototype:

```bash
python3 -m http.server 4173
```

Then visit:

- `http://localhost:4173/design-audit/2026-06-10/before.html`
- `http://localhost:4173/design-audit/2026-06-10/after.html`

The prototypes use representative data and contain no live credentials or
production requests.
