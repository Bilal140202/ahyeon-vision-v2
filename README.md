# THE ICON DOSSIER — Vol.2 preview build

Static, deploy-only mirror for the live preview of **"The Icon Dossier" Vol.2** — an unofficial,
fan-maintained archive of Jung Ahyeon of BABYMONSTER. The dossier itself is presented anonymously
by "the archive desk"; no personal names, handles or account references appear in the site or in
this repo.

- **Live preview:** https://bilal140202.github.io/ahyeon-vision-v2/
- **Identity:** "The Icon Dossier" v2.2 — bone paper, broadcast crimson + signal lime,
  Syne / Hanken Grotesk / Martian Mono.
- Unofficial fan project — not affiliated with YG Entertainment. All referenced media belongs to
  its respective owners.

## Fan Wire — contribute

Spotted a moment we missed, a detail to fix, or an idea for the site? Use the **FILE A FAN WIRE**
button on the site. Wires are typed (ADD A MOMENT / CHANGE A DETAIL / IMPROVE THE SITE), delivered
**privately to the archive desk's Telegram line**, reviewed wire by wire, and approved entries are
folded into the dossier with the submitter credited (optional — leave the credit line blank to
stay fully unsigned). Nothing auto-publishes; no GitHub account, email or sign-up is involved.

## For maintainers

This repo is deploy-only: the `main` branch holds the production build output of the
`icon-dossier-v2` branch (built with `vite build --base=/ahyeon-vision-v2/`). Do not edit
`index.html` or `assets/` by hand — they are overwritten on each deploy. Site source, docs and
history live in the private parent repo.
