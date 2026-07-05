# HomeTest Future State & Commercial Workstream Tracker

Live status, milestones, dependencies and scope authorisation across the HomeTest Future State and Commercial workstreams.

Owned and maintained by Scott Eason and Rachel Flower.

## Purpose

This tracker does three jobs at once:

1. **Operational picture.** Workstream-by-workstream status, open actions, dependencies and blockers.
2. **Audit trail.** Every line is traceable to a tasking event, written ask, SLT direction or artefact that authorises the work. So when anyone questions scope, the answer is in the document.
3. **Defensive posture.** Captures the watching brief and the comms discipline needed when operating as a small commercial team inside a larger delivery contract.

## Structure

Restructured 5 July 2026 into a function split: live position and historical record are separated on every page.

- `index.html` — tile-only front door. Tiles in three category groups (HIV Private Beta, PSA Acute Use Case, Future State & Commercial). No prose sections.
- `beta.html` — HIV Private Beta: position now, LA state of play, open actions (MoU / funding / technical, and IG / clinical safety), dependencies and blockers, critical path, then a dated History log.
- `acute.html` — PSA Acute Use Case: RDUH MoU and counter-signature, £198k transfer, mobilisation, the acute discovery pipeline, then History.
- `commercial.html` — Future State & Commercial: Phase 2 plan, sourcing strategy, Programme Board, supplier engagement, tariff and volumes work, then History.
- `sources.html` — defensive posture and the full source library.
- `detail.html` — stub only; the old single detail page moved into the pages above.

History logs are append-only, newest first, one collapsed `<details>` entry per event with its source. They are the audit record and are never trimmed.

## Maintenance rules

1. Live sections carry only open items. When an item closes, move it into that page's History with its date and source rather than striking it through in place.
2. A status change updates the index tile one-liner and the workstream page together; they must never contradict each other.
3. New scope authorisation events (task assignment, written ask, SLT direction) get a History entry on the relevant page with the source, the same day.
4. Update the banner `Last updated` line on every touched page.
5. Commit with a one-line message describing the change.

Status pill conventions:

- `In flight` / amber — actively progressing
- `Blocked` / `Overdue` / red — needs intervention or breached date
- `Closed` / green — completed
- `Watching brief` / grey — monitored, not actively progressing

## How to view

Open `index.html` in any modern browser. Self-contained: no dependencies, no build step, no JavaScript. Fonts fall back to Segoe UI / Arial if Abadi is not installed.

## Sources

Built from primary programme sources: emails and SharePoint primary documents. The full list with citations is on `sources.html`.

## Versioning

Working draft. Refresh as the programme moves. Material decisions and SLT moves should always trigger a refresh within 24 hours.

## Distribution

Internal working document. Not for distribution outside the working team without owner approval.
