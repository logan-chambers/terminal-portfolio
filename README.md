# Retro Terminal Portfolio

A portfolio site styled as an interactive retro terminal — boots with a
fake init sequence and ASCII logo, then drops you at a command prompt.
Visitors "explore" your portfolio by typing commands instead of
scrolling a page.

No build tools, no dependencies — it's a single HTML file with plain
JavaScript (no React, no CDN dependencies other than a Google Font).

## Run it

Double-click `index.html`, or open it in any browser.

## Host it live (GitHub Pages)

1. Create a repo (e.g. `terminal-portfolio`) and upload `index.html` to
   the root.
2. Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`.
3. Your live URL will be `https://<username>.github.io/terminal-portfolio/`.

## Commands

`help`, `about`, `skills`, `projects`, `contact`, `ls`, `cat <file>`,
`resume`, `whoami`, `clear`, arrow-key command history, plus a couple of
easter eggs (`sudo hire-me`, `matrix`).

## Make it yours

Open `index.html` and edit the `PROFILE` object near the top of the
`<script>` tag — name, bio, skills, project list + links, contact info,
and résumé URL. Everything else (the file listing, `cat` output, etc.)
is generated from that object automatically.

## Tech

Plain HTML/CSS/JS. No framework, no build step, no external services
besides a Google Fonts stylesheet.
