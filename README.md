# tankdiary.com — static site

Two files, zero build step, zero maintenance. Hosted on Cloudflare Pages, auto-deploys from this repo's `main` branch.

## Placeholders to swap before/at launch
| Where | What |
|---|---|
| `index.html` — both `badge-appstore` links + `apple-itunes-app` meta | Real App Store URL / app ID |
| `index.html` — `.proof` strip | Real App Store rating + 2 community quotes |
| `index.html` — hero `.screen` and each `.mini` card | Real app screenshots (`screens/*.webp`, ~540×1170); the CSS mock cards are stand-ins |
| `og-image.png` | 1200×630 social card |

## Editing
Change a file on GitHub → commit → Cloudflare Pages redeploys automatically in ~30s. That's the whole workflow.
