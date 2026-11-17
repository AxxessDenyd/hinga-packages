# hinga-packages

Download host for the Hinga OS app store. This repo holds **only** published store package files and the store package list, attached to GitHub Releases. Hinga's source code is not here.

- The store reads the package list from: `https://github.com/AxxessDenyd/hinga-packages/releases/latest/download/index.json`
- Each package is a release asset, downloaded from `https://github.com/AxxessDenyd/hinga-packages/releases/download/<tag>/<file>`
- Hinga verifies every package's signature and hash before installing, so the download location is not trusted on its own.
- Free GitHub hosting only: no paid services.
