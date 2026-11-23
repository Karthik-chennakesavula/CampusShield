# CampusShield

A React + Vite front-end prototype for a college campus safety demonstration.

## Features
- Student dashboard and SOS demonstration
- Incident reporting
- Security dashboard with incident status updates
- Browser geolocation display
- Emergency contact links
- My Reports view
- Browser localStorage persistence

## Run locally
1. Install Node.js.
2. Open this folder in VS Code or a terminal.
3. Run `npm install`.
4. Run `npm run dev`.
5. Open the local URL printed by Vite.

## Important limitations
- SOS is a demonstration only; it does not send emergency notifications.
- Reports are stored in the current browser using localStorage.
- Data is not shared across devices or users.
- GPS requires browser permission and a secure context (HTTPS or localhost).
- Replace `YOUR_COLLEGE_NUMBER` in `src/App.jsx` with a verified campus security number before a demonstration.
- Check all emergency numbers and local procedures before relying on them. This prototype is not a production emergency response system.
