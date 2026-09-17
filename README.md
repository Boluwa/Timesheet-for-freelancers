# 🕐 Hours Ledger

A single-page freelance timesheet tracker. Type a task in plain language — "New lead gen set up for Green Pantry — 3h" — and it parses out the task and the hours automatically. Switch to the Month Report tab to see hours totaled by task for any month, with a one-click copy for sending on to a client. No build step, no backend — just an HTML file that saves your log to the browser.

🔗 [Live demo](https://boluwa.github.io/Timesheet-for-freelancers/) · 📁 [Source](./index.html)

<!-- Add a screenshot once you have one. Take one from the live URL, save as screenshot.png in this repo, then uncomment the line below.
![Screenshot of Hours Ledger](screenshot.png)
-->

## Features

- **Natural-language entry** — type the task and hours in one line, in whatever order feels natural (`— 3h`, `, 2.5 hours`, `- 4`)
- **Daily log view** — entries grouped by day, newest first
- **Month-end report** — hours totaled per task, with entry counts and a grand total
- **Copy report** — one click copies a plain-text summary to the clipboard
- **Month navigation** — flip back through past months
- **Light/dark aware** — matches your system theme

## Running it

No build step. Either:

- Open `index.html` directly in a browser, or
- Enable **GitHub Pages** for this repo (Settings → Pages → Deploy from branch → `main` / root) to get a shareable live link

Entries are saved in the browser's local storage, scoped to whichever URL you open it from — so the GitHub Pages link and a local file will keep separate histories.

## Stack

Plain HTML/CSS/JS. No dependencies beyond Google Fonts (Fraunces, Inter, IBM Plex Mono).

---

<sub>Built by [Boluwa Olojo](https://github.com/Boluwa) — a freelance-friendly tool for tracking billable hours without a subscription.</sub>
