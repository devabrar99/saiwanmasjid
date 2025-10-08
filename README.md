# Masjid Prayer Timetable

A modern, responsive prayer timetable web app for masjids, built with Vite, React, and TypeScript. It highlights the next prayer with a live countdown and allows authorized admins to edit daily timings directly in the browser.

## Features

- 🌙 Five daily prayers with Adhan and optional Iqamah times
- 🕰️ Live countdown to the next prayer with automatic rollover to the next day
- 💾 Persistent schedule using local storage so updates stick between refreshes
- 🔐 Admin mode protected by a PIN for quick timetable edits
- 📱 Responsive, display-ready layout suitable for lobby screens or kiosks

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) 18 or later
- npm (bundled with Node.js)

### Installation

```powershell
npm install
```

### Development server

```powershell
npm run dev
```

Open the printed local URL (defaults to `http://localhost:5173`) in your browser.

### Build for production

```powershell
npm run build
```

Preview the production build locally:

```powershell
npm run preview
```

### Run tests

```powershell
npm run test
```

## Admin Mode

- Click **Admin Login** and enter the default PIN `1357` (change this in `src/App.tsx`).
- Adjust Adhan/Iqamah times; changes save instantly to local storage.
- Use **Reset Defaults** to restore the original timetable.

## Customization Tips

- Update the masjid name and branding in `src/App.tsx` and `src/index.css`.
- Set your community's default timings in `src/data/defaultSchedule.ts`.
- Adjust styling to match existing signage or display requirements.

## License

This project is provided without an explicit license. Contact the author before redistribution.
