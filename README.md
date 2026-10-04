# Unified Knowledge Map

A lifetime map of what has been touched and what is actually competent. Single-file app: `index.html`.

- Works offline from browser storage. Sign in (tap the status text, top right) to sync across devices via Firebase.
- `firebase-config.js` holds your Firebase web config. `firestore.rules` is what to publish in the Firebase console.
- Back up from the app (Back up button). Backup files are git-ignored on purpose.
- Syllabus version is `SYL_V` in `index.html`. Bump it when the topic tree changes.
