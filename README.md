# antcrew Status

This repository powers the [antcrew status page](https://status.antcrew.org) using [Upptime](https://upptime.js.org).

[![Uptime CI](https://github.com/iagop03/antcrew-upptime/workflows/Uptime%20CI/badge.svg)](https://github.com/iagop03/antcrew-upptime/actions?query=workflow%3A%22Uptime+CI%22)
[![Static Site CI](https://github.com/iagop03/antcrew-upptime/workflows/Static%20Site%20CI/badge.svg)](https://github.com/iagop03/antcrew-upptime/actions?query=workflow%3A%22Static+Site+CI%22)

## Setup

1. Add a `UPPTIME_GH_TOKEN` secret to this repo — a GitHub PAT with `repo` and `workflow` scopes.
2. Enable GitHub Pages (source: `gh-pages` branch) in repo settings.
3. Optional: add a CNAME record for `status.antcrew.org → iagop03.github.io`.

Monitored endpoints are defined in [`.upptimerc.yml`](./.upptimerc.yml).
