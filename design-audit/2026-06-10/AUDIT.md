# Audit Findings

## Executive view

The current dashboard is functional and restrained, but almost every surface
has the same visual weight. The main opportunity is not a brighter theme. It is
to make today's answer, its freshness, and its trend visible before the user
starts reading.

## Scorecard

| Lens | Current | Proposed | Main change |
| --- | ---: | ---: | --- |
| Hierarchy | 2.5/5 | 4.5/5 | A clear page title and one dominant live-sales story |
| Density | 3/5 | 4/5 | Brief becomes scan-friendly insight rows |
| Navigation | 2.5/5 | 4/5 | Desktop sidebar and compact mobile destinations |
| Responsiveness | 3/5 | 4/5 | Mobile composition is redesigned, not only stacked |
| Accessibility | 3.5/5 | 4/5 | Larger targets, stronger state cues, less muted copy |

## Highest-value issues

### 1. Equal-weight panels slow scanning

The live card, morning brief, and historical metric cards all use similar dark
panels and borders. The amount is large, but the page still asks users to read
panel by panel.

Proposal: use one accented live-sales panel, introduce a page-level heading,
and demote supporting history into a clearly labeled performance section.

### 2. The morning brief is useful but text-heavy

The brief presents a narrative paragraph plus another hourly chart. Its key
signals are not visible until the paragraph is read.

Proposal: lead with three short insight rows, retain the full brief behind a
secondary action, and avoid repeating the same chart at equal prominence.

### 3. Navigation consumes attention

The brand header, account controls, and full tab row take a large portion of
the first viewport. On narrow screens the tab row becomes another horizontal
surface to manage.

Proposal: use a stable desktop sidebar. On mobile, show the highest-frequency
destinations directly and put the remainder behind a clear More action.

### 4. Metrics report values but do not explain shape

Week and month cards include comparison text, but the trend is easy to miss.

Proposal: pair each value with a compact trend badge and a small sparkline.
Use color as a redundant signal, never as the only signal.

### 5. Freshness is buried

The updated time shares a low-emphasis footer with orders and AOV.

Proposal: show freshness as a status chip next to the live label and keep the
refresh action adjacent to it.

## Design hypotheses

1. Users will identify today's takings and freshness in under three seconds.
2. Users will understand weekly direction without reading comparison prose.
3. The first mobile viewport will contain the live answer, status, and trend.
4. Navigation will feel calmer while preserving access to every current area.

## Boundaries

- No production behavior is changed.
- Representative numbers are illustrative.
- The concept preserves the current dark visual language.
- The audit does not propose changes to authorization, data flow, or refresh
  behavior.
