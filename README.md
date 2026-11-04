# STREET

A mobile-first social news and media-sharing front-end prototype.

## Features
- Sign up and sign in with a username and password
- Home feed for image and video posts
- Create posts using the camera or device gallery
- Captions, comments, and post search
- Instagram-inspired bottom navigation
- Dark black and glass-style interface

## Run locally
Open `index.html` in a modern browser.

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/ (root)`, then save.

## Important limitations
This is a front-end prototype. Accounts are stored in browser local storage, while posts and comments are stored in IndexedDB on the current device/browser. They do not sync between different users or phones. The demo password storage is not secure and must not be used for real accounts. A production version needs a backend, secure authentication, cloud media storage, database rules, moderation, and reporting tools.
