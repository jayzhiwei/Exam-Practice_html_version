# Exam Practice HTML Versions

A public archive of standalone HTML exam-practice dumps.

## Latest

Use the current stable version here:

[Open latest dump in GitHub](latest/DUMP_current.html)

## Live Preview

Open the latest practice dump as a live page:

[Open Latest Practice Dump](https://jayzhiwei.github.io/Exam-Practice_html_version/latest/DUMP_current.html)

Current stable source: `2026-07-29_2907.html`

## Version Archive

Older snapshots are kept in `versions/` so the root of the repo stays clean while history is still easy to find.

| Date | Version file | Notes |
| --- | --- | --- |
| 2026-03-07 | [0307](versions/2026-03-07_0307.html) | Original March 7 version |
| 2026-03-07 | [0307 retake fixed](versions/2026-03-07_0307-retake-fixed.html) | Retake-fixed variant |
| 2026-06-07 | [0607](versions/2026-06-07_0607.html) | June 7 version |
| 2026-06-19 | [DUMP 1906](versions/2026-06-19_DUMP-1906.html) | June 19 dump |
| 2026-06-22 | [DUMP 2206 A3](versions/2026-06-22_DUMP-2206-A3.html) | June 22 A3 dump |
| 2026-06-23 | [DUMP 2306](versions/2026-06-23_DUMP-2306.html) | June 23 dump |
| 2026-06-23 | [DUMP 2306 ISTQB base64](versions/2026-06-23_DUMP-2306-ISTQBwBase64.html) | Base64 ISTQB variant |
| 2026-06-24 | [DUMP 2406](versions/2026-06-24_DUMP-2406.html) | June 24 dump |
| 2026-06-24 | [DUMP 2406 base64](versions/2026-06-24_DUMP-2406-base64.html) | Base64 variant |
| 2026-06-29 | [DUMP 2906](versions/2026-06-29_DUMP-2906.html) | June 29 dump |
| 2026-06-29 | [DUMP 2906 M](versions/2026-06-29_DUMP-2906-M.html) | M variant |
| 2026-06-30 | [3006 M](versions/2026-06-30_3006-M.html) | June 30 M version |
| 2026-06-30 | [3006 M fixed](versions/2026-06-30_3006-M-fixed.html) | Fixed M version |
| 2026-07-02 | [DUMP 0207 keyboard control](versions/2026-07-02_DUMP-0207-keyboard-control.html) | Keyboard-control version |
| 2026-07-07 | [0707](versions/2026-07-07_0707.html) | July 7 version |
| 2026-07-08 | [0807](versions/2026-07-08_0807.html) | July 8 version |
| 2026-07-09 | [0907](versions/2026-07-09_0907.html) | July 9 version |
| 2026-07-09 | [0907 bold VLAN](versions/2026-07-09_0907-bold-VLAN.html) | Bold VLAN variant |
| 2026-07-13 | [1307 New CI](versions/2026-07-13_1307-New-CI.html) | Previous stable source |
| 2026-07-13 | [1307 old CI](versions/2026-07-13_1307-old-CI.html) | Previous CI variant |
| 2026-07-28 | [1307 New CI with NS BC](versions/2026-07-28_1307-New-CI-with-NS-BC.html) | Stable source with NCP-NS and NCP-BC banks |
| 2026-07-29 | [2907](versions/2026-07-29_2907.html) | Current stable source |

## Upgrade Workflow

Use a branch for each upgrade, then merge it back to `main` when it is ready.

1. Create a branch named like `upgrade-YYYYMMDD-short-name`.
2. Put the new stable HTML at `latest/DUMP_current.html`.
3. Archive the previous stable file in `versions/` with a date prefix.
4. Update this README so the latest link and archive table stay accurate.
5. Merge the upgrade branch into `main`.

This keeps `main` clean, makes the latest file obvious, and still preserves every older HTML version.
