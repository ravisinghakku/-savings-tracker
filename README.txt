SAVINGS STUDIO - UPDATED TRACKER
Files: index.html, manifest.json, sw.js
Features: premium dashboard, six-month savings chart, goal calculator, edit/delete transactions, in-app daily reminder, JSON backup export.

PRESERVING EXISTING DATA
The updated app intentionally keeps the same localStorage key: mySavingsTrackerV1. If you publish these files to the same GitHub Pages URL, existing savings data stored in that browser should remain. Do not clear browser site data. Export a backup from the app before updating if possible.

REMINDER LIMITATION
The browser checks reminder time while the app is open. It cannot guarantee notifications when fully closed without a push-notification backend.

PUBLISH UPDATE
In the existing GitHub repository, upload/replace index.html, manifest.json, and sw.js at the repository root and commit changes. Wait for GitHub Pages to redeploy. If the installed app shows the old design, close/reopen it or refresh the site; the updated service worker cache version is v2.
