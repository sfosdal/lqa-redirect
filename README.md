# lqa.here.events → lqa.seattle.here.events

The redirect stub for Lower Queen Anne Events' former host. GitHub Pages cannot
redirect a retired custom domain, so this repo holds `lqa.here.events` and:

- redirects every page (`index.html` and `404.html`, path + query + hash kept) to
  https://lqa.seattle.here.events/;
- mirrors the calendar feeds and the scripts the river site loads once a day
  (`feeds.txt`, `.github/workflows/mirror.yml`) so old subscriptions and embeds
  keep working.

Retire it when the old host has gone quiet (a few months after 2026-10-11).
