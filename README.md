# Stilltable · Spider Solitaire

A mobile-first, one-suit Spider Solitaire PWA. Play offline after the first visit. Your game and undo history stay in this browser on this device.

## Play

Open `index.html` through any static web server. The game deals a standard 104-card, one-suit deck into ten columns. Move face-up descending runs onto a card one rank higher or into an empty column. Deal from stock only when every column has cards. Complete eight King-to-Ace runs to win.

Tap a run and a highlighted destination, or drag it. Undo reverses a move or stock deal. Hint highlights a legal move without revealing hidden cards. Appearance follows system settings by default.

## Deploy

The GitHub Actions workflow in `.github/workflows/deploy.yml` publishes the static PWA to GitHub Pages after pushes to `main`. In the repository's **Settings → Pages**, select **GitHub Actions** as the build and deployment source. The first workflow run publishes the site.
