DiGe Budget - GitHub Pages install guide

1. Create a new GitHub repository (Public), e.g. "dige-budget".
2. Upload ALL files in this folder to the repo root (index.html, manifest.webmanifest, sw.js,
   icon-192.png, icon-512.png, .nojekyll). Use "Add file > Upload files" on github.com.
3. Repo Settings > Pages > Build and deployment: Source "Deploy from a branch",
   Branch "main", folder "/ (root)". Save.
4. After a minute your app is live at https://<your-username>.github.io/dige-budget/
5. Open that link on your phone in Chrome (online once), then menu > Add to Home screen / Install app.
   It then opens like a normal app and works offline.

Updating later: upload the new index.html (replace) to the repo. Open the app online once
and close it fully to get the new version.

Your data lives only on the phone (per browser/app). The installed app does NOT share data
with the standalone HTML file. To move your data: in the old copy open
Menu > Backup and data > Export backup, then in the installed app use Restore backup.
Profiles are included in each profile's own backup (export each profile separately).
Privacy: the repo only holds the app, never your data. Public repos show the code to anyone,
which is fine since there is no personal data in it.
