# 🦘 Aussie Slang Password Generator

A fun, secure password generator that creates memorable passwords using Australian slang words.

## Features

- **300+ Aussie slang words** with definitions
- Configurable word count (2–6 words)
- Optional numbers, symbols, capitalization, and separators
- Password strength meter
- One-click copy to clipboard
- Slang breakdown with meanings
- Fully responsive design
- Uses `crypto.getRandomValues()` for secure randomness

## Deploy to Netlify

### Option A: Drag & Drop (Easiest)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Log in (or create a free account)
3. On your dashboard, look for **"Want to deploy a new site without connecting to Git?"**
4. Drag and drop **this entire folder** onto the deploy zone
5. Done! Netlify gives you a live URL instantly

### Option B: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to your account
netlify login

# Deploy (run from this folder)
netlify deploy --prod --dir=.
```

### Option C: Git-based Deploy

1. Push this folder to a GitHub/GitLab/Bitbucket repo
2. In Netlify, click **"Add new site" → "Import an existing project"**
3. Connect your repo
4. Set **publish directory** to `/` (root)
5. Click **Deploy site**

## Project Structure

```
aussie-slang-password-generator/
├── index.html    ← The entire app (single file)
├── netlify.toml  ← Netlify configuration
└── README.md     ← You are here
```

## License

MIT — Use it however you like, mate! 🤙
