# Live Typing Chat

## Publish with GitHub Pages
1. Create a new **Public** GitHub repository named `live-typing-chat`.
2. Upload `index.html` to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## Firebase setup required
This is a static website, but multi-device live synchronization requires Firebase Realtime Database.

1. Create a Firebase project at https://console.firebase.google.com/
2. Register a Web app and create a Realtime Database.
3. Copy the Firebase web app config into `index.html`, replacing the `PASTE_...` placeholders.
4. Set `databaseURL` to the exact URL shown by Firebase.
5. Do not leave the database in public Test mode for a public launch. Add authentication and restrictive Realtime Database Security Rules before sharing the site.

GitHub Pages hosts the website; Firebase provides the live shared data.
