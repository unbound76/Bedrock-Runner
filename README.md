# Bedrock Runner

A mobile-friendly Minecraft Bedrock FSG community seed library.

## Run locally
Open `index.html` in a browser, or enable GitHub Pages for this repository.

## GitHub Pages
This repository includes a GitHub Actions Pages workflow. In **Settings → Pages**, select **GitHub Actions** as the build and deployment source. Pushes to `main` will then deploy the site.

## Current capabilities
- Filter seed entries by Bedrock version (1.16 / 1.18+), run type, difficulty, verification status and features.
- Add community seeds, favorite them, copy seed numbers and view notes.
- Import/export the local seed library as JSON.
- Randomly pick from the filtered entries already in your library.

## Important verification note
This is a seed-library frontend, not a Bedrock world-generation engine. It does not currently discover or validate world seeds automatically. A seed is only marked verified when a contributor has tested it and explicitly marks it as such. Imported or user-added entries are not independently verified by this app. Structure coordinates are intentionally not exposed in the finder.

## Data storage
Seed entries and favorites are stored in the current browser's local storage. Export a JSON backup to move them between devices. Community submissions are not automatically sent to GitHub.
