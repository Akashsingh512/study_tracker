# NIMCET Study Tracker

A single-file progress tracker for NIMCET 2027 preparation. No build step, no dependencies — one HTML file.

**Live:** https://akashsingh512.github.io/study_tracker/

Works on phone and desktop. Progress is saved automatically in your browser (localStorage), so it survives refreshes and stays on your device.

## What it tracks

- **Syllabus** — every topic across Mathematics, Analytical Ability & Reasoning, Computer Awareness and General English, weighted by NIMCET's actual question split. Each topic has a mastery status, a confidence rating, a "weak area" flag, last-revised date, and notes.
- **Study Log** — daily study sessions by subject/topic with hours-by-subject breakdown.
- **Mock Tests** — subject-wise marks (auto-totals out of 480), with score trend and delta vs. the previous attempt.
- **Resources** — curated free study links (videos, PDFs, official sources) with a watch/read status, plus a form to add your own.
- **Dashboard** — countdown to exam day, weighted overall progress, subject breakdowns, and recent activity.

## Storage

Progress is stored in your browser's localStorage under `nimcet-tracker-v1` — it persists across refreshes but stays on that one device/browser. Clearing site data clears your progress.
