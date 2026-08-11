# IB Exam Timetable Planner

A personal day-by-day revision planner that I had built around my actual IB exam schedule (Computer Science HL, Math AA HL, Chemistry HL, English A Lang & Lit SL, Economics SL, Spanish ab Initio SL) right before my IB finals. Single HTML file, no backend, no build step.

## Features

- Every day from March 31 to May 20, 2026 laid out and expandable
- Add, edit, check off, and delete tasks per day, each with a priority (High/Med/Low) and optional duration
- Per-day progress bar and a notes field
- Exam days are highlighted, with a pill showing subject, paper, session, and duration
- Search across all tasks, filter by priority, hide completed, collapse all
- Top bar tracks total days, tasks added, completed, remaining, and overall % done
- "Download HTML" feature to export a self-contained copy of the planner with your current data baked in, so you can back it up or move it somewhere else
- Data automatically saved to the browser's local storage

## Note

The exam dates and subjects are hardcoded (`EXAMS` object and the `START`/`END` range in the script) to my own IB session, so this is really built for my own revision rather than general use. Feel free to fork it and swap in your own dates if it's useful as a starting point.

## Usage

Just open `index.html` in a browser. Nothing to install.
