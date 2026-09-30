# ForeverRoute — Public Issue Tracker

This repository is the public bug tracker for **ForeverRoute**, a leveling and quest-navigation addon for **World of Warcraft: Forever**.

## Download

Latest public beta:
https://www.curseforge.com/wow/addons/foreverroute

Current public coverage focuses on **levels 1-22**. Routes and Forever-specific navigation data are still being verified, so real gameplay reports are especially useful.

## Before reporting

Please update to the newest available ForeverRoute beta and reproduce the problem once if practical.

If ForeverRoute is still usable:

1. Leave the addon on the incorrect step.
2. Click **REPORT** or type `/fr report`.
3. Click **GENERATE REPORT**.
4. Click **COPY REPORT**.
5. Open a new issue here and paste the entire generated diagnostic report.
6. Add one or two sentences describing what you expected to happen.

Optional: `/fr why` explains why ForeverRoute selected or moved to the current step.

The report can include the active route, step, quest state, target, waypoint evidence, player position, recent transitions, and other diagnostic information. Please do not edit the diagnostic block unless it contains something you explicitly do not want to share.

## Choose the right report type

- **Wrong NPC / Waypoint** — wrong NPC/object, incorrect waypoint, bad map pin/arrow, or navigation target problem.
- **Quest / Route Problem** — skipped step, stuck progression, wrong quest order, missing pickup/turn-in/objective action, level-gate problem, or route-selection issue.
- **Lua Error** — Lua error, taint error, stack trace, or addon crash.

## Helpful information

The most useful reports include:

- ForeverRoute version
- character level
- faction, race, and class
- route name
- step number
- quest ID / quest name
- what you expected
- what actually happened
- screenshot when useful
- full `/fr report` diagnostic output

If a waypoint is wrong and you know the correct NPC/object location, include a screenshot or map position if practical. Do not guess coordinates.

## Privacy

Do not include account credentials, Battle.net information, email addresses, or other private information in reports.

## What happens to reports

Reports are triaged against ForeverRoute's route lifecycle, endpoint evidence, TravelGraph, and runtime state. Verified fixes are tested before they are included in a later beta build.

Thank you for helping improve ForeverRoute.
