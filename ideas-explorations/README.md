# Ideas & Explorations

A responsive, editorial-style static site starter built using Tabler CSS and custom styling. Designed for Firebase Hosting.

## Deploy to Firebase

1. Install Node.js and Firebase CLI: `npm install -g firebase-tools`
2. Sign in: `firebase login`
3. From this folder, run `firebase init hosting`
4. Select your Firebase project, set public directory to `.`, configure as a single-page app **No**, and do not overwrite index.html.
5. Deploy: `firebase deploy --only hosting`

Alternatively, add the included firebase.json and use `firebase deploy --only hosting` after project selection.

The site is static HTML/CSS/JS. Collection content and dedicated detail-page templates can be added next without requiring a database.
