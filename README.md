# Love Live Intro Page

A lit.link-style one-page intro site for Love Live! fans. Built with plain HTML and CSS — no build step or JavaScript required.

## Live site

After enabling GitHub Pages, your site will be available at:

`https://<username>.github.io/lovelive_intro/`

## Local preview

Open `index.html` directly in your browser, or use a local server:

```bash
npx serve .
```

## Edit content

All page content lives in [`index.html`](index.html). Update the profile, links, social URLs, and image grid there, then commit and push.

## GitHub Pages setup

1. Push all files to the `main` branch on GitHub.
2. Go to your repo **Settings → Pages**.
3. Under **Build and deployment**, set Source to **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then click **Save**.
5. Wait about a minute — your site will be live at the URL above.

## Project structure

```
lovelive_intro/
├── index.html          # Page content + structure
└── css/styles.css      # Love Live pastel theme
```

## Tech stack

- Plain HTML
- Plain CSS with CSS variables
- Google Fonts (M PLUS Rounded 1c)
- GitHub Pages for hosting
