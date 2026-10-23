# Workers & Workers Suppliers Manager

A mobile-friendly, standalone web app for tracking boys' daily work and wages, worker-supplier entries, payments, expenses, reports, and daily work totals in the monthly calendar.

## Features

- Boys directory with a saved default daily salary
- Worker suppliers directory with a saved default per-worker rate
- Inline daily work-entry forms
- Date display in `DD/MM/YYYY` format and calendar pickers
- Reports filtered by date, place, person, and activity type
- Monthly calendar that shows daily recorded labour totals and lets you inspect work on a selected date
- Payment and expense records
- WhatsApp message preparation for review before opening WhatsApp
- CSV export and JSON backup/restore
- Local browser auto-save

## Publish with GitHub Pages

1. Create a new GitHub repository for this app.
2. Upload `index.html` and `README.md` to the repository's root folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/(root)`, then save.
6. Wait for GitHub Pages to publish the site and open the URL shown in Settings → Pages.

## Important data note

This version saves data in the browser's local storage on the device/browser where it is used. It does **not** have cloud database sync configured. Android, iPhone, and MacBook will not automatically share records just because they open the same GitHub Pages URL. Export regular JSON backups from the app's Backup & Sync section. Cloud sync should be configured and tested separately before relying on multi-device data sharing.

## Release/testing checklist

- [ ] Test adding and editing a boy and confirm the default salary fills in for new work entries.
- [ ] Test adding and editing a supplier and confirm the default rate fills in for new supplier entries.
- [ ] Test DD/MM/YYYY date fields and the calendar pickers.
- [ ] Test the Reports date/place/person filters and monthly calendar date selection.
- [ ] Export a JSON backup and restore it in a test browser/profile.
- [ ] Test the app on Android, iPhone Safari, and MacBook Safari.
- [ ] Confirm local data persists after refresh and keep a separate backup.
- [ ] Configure cloud sync separately if cross-device sharing is required.

## Privacy

Do not use a shared/public device for sensitive business records unless you understand that this version has no app PIN lock and stores records locally in that browser.
