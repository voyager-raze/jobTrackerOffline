# JobLedger Offline Tracker

Simple offline job application tracker built as a single HTML app.

## What is in this folder

- `jobTracker-anima-backup.html` - Main app UI and logic.
- `logo.ico` - App icon.
- `script.py` - Generates sample export data (`job_tracker_export.json`).
- `joblledger-backup-2026-05-18.json` - Backup export file.

## How to use

1. Open `jobTracker-anima-backup.html` in a browser.
2. Add, edit, archive, and track applications.
3. Go to Settings and use Import/Export inside the app for backups.

## Notes

- Data is stored locally in your browser (IndexedDB).
- No server is required.
- If you clear browser site data, local records are removed.
