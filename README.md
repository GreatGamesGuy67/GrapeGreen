# GrapeGreen

GrapeGreen is a colorful single-page web app and dashboard focused on community features like chat, profile settings, QR generation, meme browsing, and account management. The project is built as a front-end-only experience with Firebase-powered data for user accounts, chat, and other community features.

## Overview

This project includes:

- A login/sign-up flow with account creation and guest access
- A dashboard home screen with community messaging and status panels
- Global chat and moderation tools
- User profiles, avatars, and appearance customization
- QR code generation and simple utility pages
- A meme gallery / wall of memes
- Admin, legal, and support flows for community management



## Features

### Authentication and accounts

- Username-based sign up and login
- Guest mode
- User roles such as guest, member, mod, admin, legal, dev, and owner
- Password handling with salted hashing and account security checks
- Account deletion and retention workflow

### Community and chat

- Public/global chat feed
- Staff chat area for higher-role users
- DM-style interactions and moderation tools
- Notification and ticket/report flows

### Dashboard experience

- Searchable tab navigation
- Settings panel for profile, theme, brightness, and text size
- QR code page and simple science/coding subpages
- Update log and help screen
- Memes wall and support bot interface

## Running locally

Because this is a static front-end project, you can run it by serving the repo root with any local web server.

Example:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Notes

- The app is primarily a front-end prototype and uses Firebase-style APIs in the browser for persistence and realtime updates.
- Some functionality depends on external configuration and service access.
- This repository is intended as a demo/community app project rather than a formal production-ready service.

## License

This project does not currently include a license file. If you plan to distribute or reuse it publicly, consider adding an explicit open-source license.

## Contributing

Contributions are welcome if you want to improve the app's UX, add features, tighten security, or clean up the frontend structure.
