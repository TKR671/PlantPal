# PlantPal

PlantPal is a home-screen installable Progressive Web App (PWA) for tracking plants, care schedules, and journal entries.

## Deployment

This repository deploys automatically to GitHub Pages through the workflow in `.github/workflows/deploy.yml`.

In GitHub, open **Settings → Pages** and choose **GitHub Actions** as the build and deployment source. The next push to `main` deploys the site.

Live URL: https://tkr671.github.io/PlantPal/

## Install on iPhone

1. Open the live URL in Safari.
2. Tap **Share → Add to Home Screen**.
3. Keep the name PlantPal and tap **Add**.

## Features

- Plant profiles, photos, species, location, light, and notes
- Watering, fertilizing, misting, and repotting schedules
- Due and overdue care tasks
- Plant journal with notes and photos
- Local data backup export and import
- Offline app-shell caching after the first successful visit

## Data and reminders

Plant profiles and journal data are stored in the browser on the current device. This build does not sync across devices or accounts. Background reminders are not guaranteed while the app is closed.
