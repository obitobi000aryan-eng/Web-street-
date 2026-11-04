# STREET

A mobile-first social media/news-feed front-end prototype with a premium black glass UI.

## Included pages
- **Home:** feed, stories-style user row, photo/video posts, likes and comments
- **Explore:** search usernames and captions, browse media grid
- **Create:** camera capture or gallery/file picker for photos and videos
- **Activity:** recent comments made by the signed-in user
- **Profile:** display name, bio, profile photo, own posts, saved posts and logout

## Run / publish
Open `index.html` in a modern browser. To publish:
1. Create a GitHub repository named `STREET`.
2. Upload `index.html` and `README.md` to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.

Camera access may require HTTPS, so use GitHub Pages for camera testing.

## Important limitation
This is a complete front-end prototype, not yet a production multi-user social network. Accounts are saved in browser localStorage and posts/media/comments in IndexedDB on the current browser/device. Other users and phones do not share data. Passwords are locally PBKDF2-hashed using Web Crypto, but browser storage is not secure server authentication. A public launch needs a backend, secure sessions, cloud database/media storage, access rules, moderation/reporting, privacy policy and account recovery. Do not reuse a personal password or upload private media.
