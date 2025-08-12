# Chore Joy Board

This repository hosts the landing page for the **Family Chore Bingo** (Chore Joy Board) app.

## About

Family Chore Bingo turns household chores into a fun game. The app creates bingo boards for each member of your household, awards points based on difficulty, tracks leaderboards and bingos, and makes weekly resets easy.

The landing page (`download.html`) promotes the app and provides links to download or open the app on the web. You can host this page on GitHub Pages or another static hosting service.

## Usage

1. Edit the `download.html` file to set your real application URLs:
   ```html
   const APP_URL = 'https://your-deployed-web-app.com';
   const IOS_URL = 'https://apps.apple.com/app/idXXXXXXXXXX';
   const ANDROID_URL = 'https://play.google.com/store/apps/details?id=com.example.chorejoy';
   ```
   Replace these with the URLs for your web app and store listings.

2. Commit and push the changes to GitHub. If using GitHub Pages, enable the site in the repository settings and choose the `main` branch as the source.

## Features

- **Multi-player boards**: Create boards for each family member with unique colors.
- **Scoring & bingos**: Points based on chore difficulty, plus bingos detection and confetti animations.
- **Leaderboard & week summary**: Track who's ahead and the percentage of chores completed each week.
- **Chore management**: Add, edit or remove chores and members on the fly.
- **Export/Import & QR codes**: Share your current game via QR or text payload.

## Hosting

You can host this page and your web app on any static site host such as:

- GitHub Pages (free)
- Netlify or Vercel (easy deployment from your repo)
- AWS S3 + CloudFront

## Contributing

Feel free to open issues or pull requests with improvements. This project is open source under the MIT license.
