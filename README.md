# FocusFlow

> Your space. Your pace. One step at a time.

FocusFlow is a calm, ADHD-friendly productivity space designed to make daily planning feel lighter. It helps turn overwhelming goals into small, visible next steps without guilt or pressure.

## Live app

- [FocusFlow on Vercel](https://focus-flow-pied-kappa.vercel.app/)
- [GitHub repository](https://github.com/honestlynahra/focus-flow)

## Features

- Personalized dashboard with daily progress and encouraging prompts
- Task manager with priorities, due dates, completion, filters, and subtasks
- Visual “Help me get started” flowchart for breaking stuck tasks into tiny steps
- Pomodoro Focus Room with customizable focus and break sessions
- Timeline-based daily schedule
- Mood and energy check-ins with gentle suggestions
- Habit tracker with flexible weekly progress
- Personalization settings for timer preferences, text size, and notifications
- Responsive layout for desktop, tablet, and mobile
- LocalStorage persistence so tasks and preferences remain after refresh

## Tech

This is a self-contained frontend prototype using:

- React 18
- Tailwind CSS via CDN
- Lucide icons
- Babel in the browser
- LocalStorage for persistence

## Run locally

Because the app is contained in `index.html`, no build step is required.

1. Download or clone the repository.
2. Open `index.html` in a browser.

For the smoothest local experience, serve the folder with any static file server.

## Product principles

FocusFlow is intentionally designed around:

- Smaller steps over overwhelming lists
- Encouragement over guilt
- Flexible routines over rigid schedules
- Clear, quiet interfaces over complicated dashboards

## Future direction

The frontend is structured so Supabase authentication, cloud persistence, and account-based synchronization can be added later without changing the core experience.
