# HomeTest Future State & Commercial Workstream Tracker

Live status, milestones, dependencies and scope authorisation across the HomeTest Future State and Commercial workstreams.

Owned and maintained by Scott Eason and Rachel Flower.

## Purpose

This tracker exists to do three jobs at once:

1. **Operational picture.** Workstream-by-workstream status, next actions, dependencies and blockers.
2. **Audit trail.** Every line is traceable to a tasking event, written ask, SLT direction or artefact that authorises the work. So when anyone questions scope, the answer is in the document.
3. **Defensive posture.** Captures the political watching brief and the comms discipline needed when operating as a small commercial team inside a larger delivery contract.

## What's in it

- Context paragraph on where the programme sits today
- At-a-glance summary cards for each workstream
- Three workstream blocks:
  - **MoUs (Private Beta and Acute).** RDUH, Salford, East Sussex.
  - **IG Workstream.** DPIA, IAO, DCB0160, federated controller model, Legal Directions.
  - **Future State Next Stages.** Phase 2 plan, sourcing strategy, Programme Board paper, post-playback work.
- Each workstream carries scope authorisation (audit trail), next actions table, dependencies/blockers table, and critical path callout
- Cross-workstream defensive posture: discipline of the week, political watching brief
- Source list

## How to view

Open `index.html` in any modern browser. Self-contained: no dependencies, no build step, no JavaScript. Fonts fall back to Segoe UI / Arial if Abadi is not installed.

## How to maintain

Refresh at each stand-up. When anything material changes:

1. Add a line to the relevant workstream's next-actions table with owner, due, dependency and status pill.
2. If a new scope authorisation event occurs (task assignment, written ask, SLT direction), add it to that workstream's audit-trail list with the source.
3. Update the meta `Last updated` line in the banner.
4. Commit with a one-line message describing the change.

Status pill conventions:

- `In flight` / amber — actively progressing
- `Blocked` / `Overdue` / red — needs intervention or breached date
- `Closed` / green — completed
- `Watching brief` / grey — monitored, not actively progressing

## Sources

The tracker is built from primary sources:

- Meeting transcripts in `C:\Users\scott\Documents\Claude\NHS\NHS Transcripts`
- Outlook `.msg` emails in `C:\Users\scott\Documents\Claude\NHS\New emails`
- SharePoint archive at `E:\NHS\Digital Prevention Services Portfolio (DPSP) - DPSP Digital Diagnostics & Digital Therapeutics`
- Live briefing notes in `C:\Users\scott\Documents\Claude\NHS\NHS Commercial Model\Briefing Notes\Master Briefing Notes`

A full sources list with citations is at the bottom of `index.html`.

## Versioning

Working draft. Refresh as the programme moves. Material decisions and SLT moves should always trigger a refresh within 24 hours.

## Distribution

Internal working document. Not for distribution outside the working team without owner approval.
