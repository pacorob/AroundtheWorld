# Around the World Deluxe

Retro-inspired geography trivia game built as a static site for GitHub Pages.

## Features

- Works as a static HTML site
- Designed for iPhone, iPad, and desktop browsers
- Three.js globe
- English and Dutch UI
- Multiplayer scoring
- Inline travel interludes
- No build step required

## Quick deploy to GitHub Pages

### Option 1: simplest

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. In **Settings > Pages**, set the source to **Deploy from a branch**.
4. Select the **main** branch and the **/(root)** folder.
5. Wait for GitHub Pages to publish the site.

### Option 2: GitHub Actions

A workflow is included in `.github/workflows/pages.yml`.

1. Push this folder to a repository.
2. In **Settings > Pages**, set the source to **GitHub Actions**.
3. Commit and push.
4. GitHub will deploy the static site automatically.

## Notes

- The file `.nojekyll` is included so GitHub Pages does not try to process the site with Jekyll.
- Keep links and asset references relative for project-page compatibility.
- Media is streamed from public demo URLs; you can replace them with your own licensed files later.

## Customization

- Edit questions directly in `index.html`.
- Replace interlude video URLs in the `INTERLUDES` array.
- Change colors, fonts, or labels in the same file.
