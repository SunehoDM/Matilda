# Matilda
*an organiser for the loml*

A warm, Ghibli-inspired planner for med school and life.

## Deploy
1. Create repo `matilda` on GitHub
2. Push this folder
3. Settings → Pages → Source: main branch
4. Live at `https://YOUR_USERNAME.github.io/matilda/`

## Google Calendar Sync
1. Google Cloud Console → New Project → enable Calendar API
2. Credentials → OAuth Client ID → Web App
   - JS Origin: `https://YOUR_USERNAME.github.io`
   - Redirect URI: `https://YOUR_USERNAME.github.io/matilda/`
3. Paste Client ID into `index.html` replacing `YOUR_GOOGLE_CLIENT_ID`
4. Push → sidebar → Connect Google Calendar

## Install as App
- **iPhone/iPad**: Safari → Share → Add to Home Screen
- **Android**: Chrome → menu → Add to Home Screen

## Features
- 26 categories: 20 medical subjects + 6 life categories
- PG prep highlight toggle on any entry
- Repeat daily / weekly / biweekly / monthly
- GCal sync with popup reminders
- Bidirectional sync — all devices see same data
