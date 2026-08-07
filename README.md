# $3 Cover

Official website for **$3 Cover**, a two-guitar duo doing reinvented covers of popular music from the 70s to now.

> Three dollars of pure reinvention. We don't play songs. We re-open old wounds.

## About the site

A single-file static website (`index.html`) with an inline stylesheet and a small amount of vanilla JavaScript. No build step and no dependencies, so it can be hosted on any static web server.

### Structure

```
index.html      The entire site (HTML + CSS + JS in one file)
assets/         Images. Currently: brand.webp (nav wordmark),
                logo.webp (hero ticket art), mark.webp (unused)
README.txt      Plain-language editing guide for non-developers
```

### Editing

Open `index.html` in any text editor and search for `EDIT:` to find every spot meant to be personalized (streaming links, show dates, gallery photos, socials, city). See `README.txt` for a friendly walkthrough.

### Local preview

Just open `index.html` in a web browser.

## Deployment

Live at https://threedollarcover.com over HTTPS (Let's Encrypt, auto-renewing), with a
301 redirect from HTTP and HSTS enabled.

Since 2026-08-06 the site is served by nginx from a shared host that also serves several
other sites as separate virtual hosts, rather than from a dedicated instance. Deploying is
still just copying files: this repo is entirely self-contained (`index.html` plus `assets/`),
with no build step, so the document root is a copy of the repo contents.

`3dollarcover.com` (without the "three") redirects here via registrar-level domain
forwarding. That forwarding is HTTP-only, so `https://3dollarcover.com` does not resolve.

## Credits

- [Sky Sequoia](https://www.skysequoiamusic.com)
- [Cullen Damir](https://www.cullendamirmusic.com)
