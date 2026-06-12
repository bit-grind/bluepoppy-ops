# Design Audit Workflow

## Purpose

Run a repeatable visual audit without changing the product. The output should
make design decisions easy to compare before implementation begins.

## 1. Define the jobs

Pick three to five tasks the interface must make fast and obvious.

For Blue Poppy Ops:

1. Check today's takings and freshness.
2. Understand whether performance is up or down.
3. Read the morning brief.
4. Move to another operations area.
5. Find the next useful action.

## 2. Capture the baseline

Capture the same state at:

- Desktop: 1440 x 1000.
- Mobile: 390 x 844.
- Optional compact laptop: 1280 x 720.

Use stable representative data. Record loading, empty, error, and populated
states separately when those states materially change the layout.

## 3. Audit five lenses

Score each lens from 1 to 5 and attach one screenshot annotation per issue.

| Lens | Question |
| --- | --- |
| Hierarchy | Can the eye find the primary answer in under three seconds? |
| Density | Is related information grouped without making every panel equal? |
| Navigation | Can users move areas without scanning a long row? |
| Responsiveness | Does the mobile layout transform rather than only stack? |
| Accessibility | Are contrast, focus, targets, labels, and state cues clear? |

## 4. Prioritize

Use:

`priority = task frequency x user impact x confidence`

Keep the first concept to the top three structural issues. Defer decorative
polish until the information order is working.

## 5. Prototype one direction

Build a disposable prototype with:

- The same representative data as the baseline.
- The same desktop and mobile viewport sizes.
- No production API calls.
- No edits to product code.
- A short list of explicit hypotheses.

## 6. Compare visually

Create paired before/after assets with matching viewport, data, and scroll
position. Add a one-sentence caption describing the intended improvement.

## 7. Review with users

Ask users to complete the original tasks without coaching. Record:

- Time to first correct answer.
- Wrong turns.
- Unclear labels.
- Information they expected but could not find.
- Elements they ignored.

## 8. Implementation gate

Only move a concept into product work when:

- The primary tasks are faster or clearer.
- Mobile avoids accidental horizontal navigation patterns.
- Keyboard and contrast checks pass.
- Loading, empty, and error states have an agreed treatment.
- The team accepts the information hierarchy, not only the styling.
