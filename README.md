# 📘 PowerCoreSMP — Player Guide

The public player guide site for **PowerCoreSMP** — abilities, all 13 cores, fragments, rituals, trading, commands, and survival mechanics — served at **https://pcsmp.gcr4cked.dpdns.org/** via GitHub Pages. Part of the **OPs project family** — a solo project by **ITzGamerCracked_**.

This repository exists to keep the guide **public** while the [PowerCoreSMP](https://github.com/GamerCr4cked/PowerCoreSMP) product repository itself is **private**. The guide was extracted from that repo into its own on 2026-11-10.

## Structure

```
pcsmp-guide/
├── Guide/                                Jekyll site source — index.md, _config.yml, _layouts/, _includes/, assets/
└── .github/workflows/deploy-guide.yml    Pages deploy (Jekyll build from Guide/ → deploy-pages)
```

## Hosting

- Built by the **Deploy Guide (GitHub Pages)** workflow on every push to `main` (Ruby 3.3 → `gem install jekyll` → build from `Guide/` → artifact upload → `deploy-pages`)
- Pages is enabled with `build_type=workflow` — on first publish, select the workflow source; the custom domain lives in the repo's **Pages settings**, and deleting the Pages config wipes it, so always re-add the domain after any full reset
- `Guide/_config.yml` uses `url: https://pcsmp.gcr4cked.dpdns.org` with an empty `baseurl`, so asset, navigation, canonical, and social URLs resolve against the custom domain (custom domains serve at the root, NOT under `/<repo>`); `Guide/_layouts/default.html` emits the canonical/social tags from that URL
- Once the custom domain is bound, the old `*.github.io/<repo>/` URL stops serving — never leave it in live files

## Local build

Ruby 3.3 + `gem install jekyll --no-document`, then:

```bash
jekyll build --source ./Guide --destination ./_site
```

## Notes

- Author: **ITzGamerCracked_** (aka GC) — solo project
- License: **All Rights Reserved** — see [LICENSE](LICENSE); no redistribution or modification without written permission
- The PowerCoreSMP server itself (plugin source, bot, resource pack) is maintained in the separate **PowerCoreSMP** repository
