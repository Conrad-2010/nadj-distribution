# Nadj Distribution

A responsive music-release planning dashboard for independent artists.

## Features
- Dashboard and release overview
- Create single, EP and album release drafts
- Artist, genre, language, release date and notes
- Intended streaming platform selection
- Cover artwork preview
- Audio file selection
- View and delete saved drafts
- Responsive phone and desktop layout

## Run locally
Open `index.html` in a modern browser. No build step is required.

## Publish with GitHub Pages
1. Open this repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/(root)`, then save.
5. Wait for GitHub Pages to publish the website.

## Important prototype limitations
This repository currently contains a front-end prototype:
- Release drafts are stored in the current browser's local storage.
- Artwork is stored as a browser-local preview; audio is selected locally and is not uploaded.
- No music is delivered to Spotify, Apple Music, YouTube Music or other services.
- Store selection records the artist's intended platforms only.
- Analytics, royalty reporting, payments, accounts and cloud backups are not connected.

## What production distribution requires
Real distribution requires a backend and an approved distribution partner or direct platform agreement with suitable delivery APIs and credentials. A production implementation should add:
- Secure user authentication and artist/team permissions
- Private cloud storage for audio and artwork
- Server-side validation for audio, artwork and metadata
- Secure partner API integration and delivery-status webhooks
- Release review, takedown and rights-management workflows
- Royalty statements, analytics and audit logs

Never put partner API secrets in browser JavaScript or commit them to this public repository. Only upload music and artwork that you have the right to distribute.

## License
Add a license before accepting external contributions or defining reuse terms.
