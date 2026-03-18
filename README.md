# Job Application Tracker

A lightweight, single-file web app for tracking job applications — from wishlist through offer or rejection. No sign-up, no server, no installation required. Available at: https://job-tracker-indol-five.vercel.app/

## Features

- **Add, edit, and remove** job applications
- **Status pipeline** covering the full journey: Wishlist → Applied → Phone Screen → Interviewing → Final Round → Offer / Rejected / Withdrawn
- **Filter by status** and search across title, company, and notes
- **Live stats** showing total applications, active interviews, offers, and rejections
- **Import from CSV** to bulk-load existing job data
- **Export to CSV** for local backups or transferring data to another computer or browser
- **Dark mode** support via system preference
- **No backend required** — all data is stored locally in your browser via `localStorage`

## Getting Started

1. Download `index.html`
2. Double-click it to open in your browser
3. Start tracking your job application process
   
### Or

1. Access the deployed web app by going to `https://job-tracker-indol-five.vercel.app/`
2. Start tracking your job application process

## Exporting Your Data

Click **↓ Export CSV** at any time to download a backup of all your jobs as a CSV file named `job-tracker-backup-YYYY-MM-DD.csv`. This file can be re-imported using the Import CSV button to restore your data.

**Recommended:** export a backup before clearing your browser cache or switching browsers, as `localStorage` data does not sync across devices.

## Data & Privacy

All data is stored entirely in your own browser's `localStorage`. Nothing is sent to any server. Clearing your browser data or using a different browser/device will result in an empty tracker — export a backup first if needed.

## License

MIT — free to use, modify, and distribute.
