# Begin Prayer — Landing Page

A single-file, mobile-first landing page for the Begin Prayer app.

## Setup

### 1. App Icon

Replace `icon.png` in this directory with your 88×88px (or larger) app icon.

### 2. Screenshots

Replace these files in this directory with your actual app screenshots:

- `screen1.png` — Personalized daily journal
- `screen2.png` — One focus. Your pace. His presence.
- `screen3.png` — Scripture, prayer & reflection every day
- `screen4.png` — Track how prayer transforms you

Recommended size: 1080×2340px (9:19.5 aspect ratio).

### 3. Amplitude API Key

In `index.html`, find this line and replace with your real key:

```js
amp.init('YOUR_AMPLITUDE_API_KEY', { defaultTracking: false });
```

### 4. Store URLs

Find and replace these URLs in `index.html` (they appear twice each — hero and bottom CTA):

- **App Store:** `https://apps.apple.com/fr/app/begin-prayer-bible-journal/id6760112071`
- **Google Play:** `https://play.google.com/store/apps/details?id=com.mtstudio.holyfaith`

### 5. Deploy to Vercel

```bash
cd landing
vercel deploy
```

That's it. No build step required.
