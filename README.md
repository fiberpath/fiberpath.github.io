# fiberpath.github.io

The FiberPath project's main site and documentation hub.

It is published to GitHub Pages by `.github/workflows/deploy.yml`, which:

1. serves a minimal landing page (`index.html`) at `/`, and
2. builds the MkDocs documentation from
   [`fiberpath/fiberpath`](https://github.com/fiberpath/fiberpath) and publishes
   it at `/fiberpath/`.

The software docs are authored in the `fiberpath/fiberpath` repo (next to the
code) and validated there on every PR; this repo owns assembly and publishing.
The build runs on push to `main`, on a daily schedule (to pick up doc changes in
`fiberpath/fiberpath`), and on manual dispatch.

Live at <https://fiberpath.org>.
