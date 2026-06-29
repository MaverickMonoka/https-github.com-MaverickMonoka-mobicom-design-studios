# Mobicom Design Studios - Google Cloud Deploy

## App Engine
```bash
gcloud init
gcloud app create
gcloud app deploy
```

## Firebase Hosting
```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```
Choose the project, set public directory to this folder, do not overwrite index.html.

## Before going live
- Replace `your-domain.co.za` in sitemap.xml and robots.txt.
- Connect the domain in Google Cloud or Firebase.
- Add Google Analytics/Search Console tags if required.
