# FitCoach (installable web app)

Static files only: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.

## Put it online (free, ~2 minutes)
- **Netlify:** go to app.netlify.com/drop and drag this whole folder in. You get an https link to share.
- **GitHub Pages:** create a repo, upload these files, then Settings > Pages > deploy from the main branch.
- Must be served over https for install and offline mode to work.

## Install on a phone
- iPhone (Safari): Share > Add to Home Screen.
- Android (Chrome): menu > Install app.

## Your users' data
Progress is stored in each person's own browser. Backup and restore codes in Profile move it between devices. Nothing is sent to a server.

## Optional next steps
- Real accounts and cross-device sync: add a backend such as Supabase or Firebase and replace the save()/load() functions in index.html.
- App stores: wrap this PWA with PWABuilder.com or Capacitor.
- Before wide release: add a privacy policy and keep the not-medical-advice notice.
