# Sorted

**Your first weeks on campus, sorted.** Sorted turns the flood of WhatsApp groups, emails and committee forms a fresher gets into one short list of what needs them this week.

**Open the app:** https://nilkanth01.github.io/sorted/

Built as a student prototype for a Design Thinking course (Empathize, Define, Ideate, Prototype, Test). All names, dates and messages in the app are sample data.

## Install it on your phone

**Android (Chrome):** open the link, then tap **Install** on the banner, or open the ⋮ menu and choose **Install app** / **Add to Home screen**.

**iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.

Once installed it opens full screen like a normal app and works offline.

## What it does

| Screen | What you get |
| --- | --- |
| Today | What needs you this week, deadlines with countdowns, clash alerts, tonight's digest |
| Updates | Every notice with a one-line summary first; the original message one tap away |
| Committees | Hours per week for each committee, a plan meter, clash detection, a drafted slot-change message |
| Guide | A first-30-days checklist: ID card, Wi-Fi, LMS, laundry, getting home |
| Post | A one-minute form for committees and offices, with quality checks and a WhatsApp-ready version |

Your ticks, shortlists and posts are saved only on your own device (browser storage). Nothing is sent to a server.

## Files

- `index.html`: the whole app (HTML, CSS and JavaScript in one file)
- `manifest.webmanifest`, `icons/`: what makes it installable
- `sw.js`: service worker that caches the app for offline use
