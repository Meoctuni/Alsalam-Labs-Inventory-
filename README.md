# Al Salam Lab Inventory - no login version

No accounts: anyone who opens the link can use the app. Each person enters their name once on their device (shown in the movement log).

## Setup (free)
1. console.firebase.google.com > your project > Build > Firestore Database > Create database.
2. Firestore > Rules > paste `firestore.rules` > Publish.
3. Project settings > Your apps > Web (</>) > copy the config values into `config.js` (replace every PASTE_HERE).
   (Authentication is NOT needed anymore.)
4. Upload all files to the GitHub repo (Add file > Upload files, replace old ones). Vercel redeploys by itself.
5. Open the link on each device, wait a minute after deploy, refresh.

If config.js still has PASTE_HERE, the app shows a setup box where you can paste the firebaseConfig on that device only.

## Install as app (same link)
Windows/Mac: Chrome/Edge install icon. Android: Chrome menu > Install app. iPhone: Safari > Share > Add to Home Screen.

## Notes
- Reports: Report tab > Movements / Current stock / Statistics > Print or Export CSV.
- Sound alerts: tap the bell once. Works while the app is open.
- Records older than 18 months are removed automatically when the app opens.
- Security: because there is no login, anyone with the link can read, edit and delete data. Do not share the link publicly.
