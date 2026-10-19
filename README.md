# ASTRA v4 — Automatic rewards and daily rollover

## Changes
- Removed the manual Claim Reward button. Daily reward is awarded automatically when every activity is completed and meets its threshold.
- Removed the manual day-reset button. ASTRA archives the previous day automatically and prepares the next day.
- Running activities crossing midnight are split at midnight for reporting; the active activity continues in the new day with its timer restarted at midnight.
- Existing dark theme, seven distinct activity colors, mobile responsive layout, PWA files, local storage, and export remain.

## Publish update
Upload/replace all files in the root of your GitHub Pages repository: `index.html`, `manifest.json`, `sw.js`, `astra-icon.svg`. Then wait for Pages to deploy. If your phone keeps showing the old version, close/reopen the installed app or clear its site cache; the service worker cache version is updated.

## Important
Daily rewards are virtual and stored locally. Export backups regularly. Browser local storage does not sync across devices.
