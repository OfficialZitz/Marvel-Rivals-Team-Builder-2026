# Contributing

Thanks for helping keep the Marvel Rivals Team Builder up to date!

## What needs updating regularly

- **New heroes** — Marvel Rivals adds a hero roughly every month. Add to the `HEROES` array in `index.html`.
- **New Team-Ups** — Add to the `TEAM_UPS` array.
- **Tier changes** — Update `tier` values (S/A/B/C) in the `HEROES` array after major patches.
- **Broken images** — Update the `HERO_IMG` map with a working URL.

## How to test locally

No build step needed — just open `index.html` in any browser.

```bash
# Optional: serve locally to avoid font CORS issues
npx serve .
```

## Pull request checklist

- [ ] Data accurate to current season
- [ ] Team-up data verified against official patch notes
- [ ] No breaking changes to existing UI

## Issues

Open a GitHub Issue for:
- Missing or incorrect hero data
- Broken image URLs
- UI bugs on specific browsers or screen sizes
