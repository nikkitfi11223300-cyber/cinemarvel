# CINEMAMARVEL

A browser-based Marvel watch tracker for organizing movies, live-action and animated series, specials, and personal watch progress.

## Features in this build

- Marvel catalogue split into dedicated sections.
- Search, status filters, and sorting.
- Watch states: Plan to watch, Watching, and Watched.
- Dashboard progress, continue-watching list, and viewing statistics.
- Series season and episode progress management.
- Add and edit titles, including custom poster URLs and uploaded poster images.
- Watch planner, priority and essential/optional labels.
- Watch history, personal ratings/reviews, collections, and spoiler notes.
- Poster gallery and optional TMDB poster/series metadata lookup.
- JSON backup export/import and manual device transfer.
- Responsive layout and install prompt support where the browser supports it.

## Run locally

Open `index.html` in a modern browser. Some browser capabilities, such as installation and service-worker caching, require hosting over HTTPS (for example, GitHub Pages).

## Publish with GitHub Pages

1. Put `index.html` and this README in the repository root.
2. In **Settings → Pages**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Wait for the Pages deployment workflow to finish successfully.

## Data and backups

Tracker data is stored in the browser's local storage on the device where it is used. It does not automatically sync between devices. Use **Settings → Export backup** and **Import backup** to transfer your progress. Keep a separate copy of exported backups.

## TMDB integration

Poster and series metadata lookup can use a TMDB API key entered by the user in the app. The key is stored in that browser's local storage. Do not commit your personal API key to this public repository or include it in screenshots.

## Stable backup

`CINEMAMARVEL-stable-backup.html` is a copy of the release HTML. Keep it unchanged so you can restore this version if a later edit causes problems.

## Release note

This package uses the upgraded project HTML found in the project files. Character-specific wallpaper selection was not present in this HTML build and still needs a separate implementation; the theme toggle in this build is not the same as the requested 18 character wallpaper themes.
