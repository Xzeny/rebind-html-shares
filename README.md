# Rebind HTML shares

Public review copies of Rebind marketing HTML files.

**Draft for review, not a live campaign.** These pages are for sharing previews. They are not a live ad destination, and `robots.txt` plus a `noindex,nofollow` meta tag ask search engines not to index them.

## What's here

- [Advertorial LP set v2.1 gallery](advertorial-lps-v2-1-gallery.html) — latest 12 sponsored landing pages, desktop (1440) and mobile (390) side by side
- [Script LP set v1 gallery](script-lps-v1-gallery.html) — Break Buddy and Port Janitor landing pages (coming soon)
- [Competitor reference v1](competitor-reference-v1.html) — public-safe edition (internal-only rows removed)
- [Advertorial LP set v2 gallery](advertorial-lps-v2-gallery.html) — earlier set, kept for comparison
- [Advertorial LP set v1 gallery](advertorial-lps-v1-gallery.html) — first set, kept for comparison

The galleries are self-contained: one HTML file each, and they also work if you download the file and double-click it.

## Add another HTML file later

1. Add the self-contained `.html` file to the repository root (or a named folder).
2. Add a card and link for it in `index.html`.
3. Put `<meta name="robots" content="noindex,nofollow">` in the new page's `<head>`.
4. Commit to `main`. The public site updates after the host rebuilds, usually within a couple of minutes.

Source packs on BingBong1: `E:\Marketing Repo\advertorial-lps-v1\v2.1\`, `E:\Marketing Repo\script-lps-v1\`.
