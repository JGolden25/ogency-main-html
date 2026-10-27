# Golden Age Films — goldenagefilms.com

Static HTML/CSS site (built on the Ogency template), hosted on Firebase Hosting.

- **Live:** https://goldenagefilms.com
- **Firebase project:** `goldenagefilms-ffe98` (set as default in `.firebaserc`)
- **DNS:** managed at Bluehost (A `@` → 199.36.158.100, TXT `hosting-site=goldenagefilms-ffe98`)

## Deploy

```bash
firebase deploy --only hosting
```

## Preview a change before it goes live

```bash
firebase hosting:channel:deploy preview
```
