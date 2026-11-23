# Aperture — ChromeOS Edition

A static browser-style start page designed for ChromeOS and GitHub Pages.

## Publish with GitHub Pages

1. Create a new GitHub repository (for example, `aperture`).
2. Upload `index.html`, `style.css`, `app.js`, and this `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site.

## Features

- Internal Aperture tabs for Home, Bookmarks, and Developer Tools.
- Web search using Google, Bing, DuckDuckGo, Brave, or YouTube.
- External websites open in ordinary Chrome tabs. This avoids iframe restrictions.
- Gaming and programming quick links.
- Editable bookmarks.
- Local notes, dark/light theme, JSON formatter, Base64, URL encoder, colour picker, calculator, and Unix timestamp converter.

## Important browser limitation

This is a normal website, not a browser engine. A web page cannot take over Chrome's navigation controls, create unrestricted browser tabs inside itself, or embed websites that disallow framing. Aperture's internal tabs switch between its own pages; external links open in Chrome tabs.

## Privacy

Bookmarks, notes, and theme preference are stored in browser local storage. No backend or analytics are included.
