# ⚡ PowerCoreSMP — Player Guide

The public player guide for **PowerCoreSMP**, served at **https://pcsmp.gcr4cked.dpdns.org/** through GitHub Pages. Part of the **OPs project family**, maintained by **ITzGamerCracked_ (GC)**.

This repository keeps the player documentation public while the [PowerCoreSMP](https://github.com/GamerCr4cked/PowerCoreSMP) project repository remains private.

## Site structure

```
pcsmp-guide/
├── Guide/
│   ├── _config.yml
│   ├── _layouts/default.html
│   ├── _includes/sidebar.html
│   ├── assets/
│   │   ├── css/style.css
│   │   └── images/favicon.svg
│   ├── getting-started/index.md
│   ├── cores/
│   │   ├── index.md
│   │   └── <core>.md             One page per core (13 total)
│   ├── systems/index.md
│   ├── reference/index.md
│   ├── index.md                  Landing page
│   └── CNAME
└── .github/workflows/
    └── deploy-guide.yml
```

## Hosting & deployment

- GitHub Pages builds the Jekyll source from `Guide/`.
- Pushes to `main` build and deploy the site.
- Pull requests targeting `main` run a build validation; deployment is skipped for pull requests.
- The custom domain is **pcsmp.gcr4cked.dpdns.org**. Keep `Guide/CNAME` and the repository Pages custom-domain setting intact.
- `Guide/_config.yml` uses the custom-domain root URL with an empty `baseurl`.

## Local build

Install Ruby 3.3 and Jekyll:

```bash
gem install jekyll --no-document
jekyll build --source ./Guide --destination ./_site
```

## Notes

- Author: **ITzGamerCracked_ (GC)** — solo project.
- License: **All Rights Reserved** — see [LICENSE](LICENSE).
- The PowerCoreSMP server/plugin source is maintained separately in the private **PowerCoreSMP** repository.
