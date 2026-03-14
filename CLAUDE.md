# mywebsite

A static website project deployed via GitHub Pages.

## Project Overview

- **Homepage**: https://rtheman.github.io/mywebsite
- **Deployment**: Uses `gh-pages` to deploy the `dist/` directory to GitHub Pages
- **Build output**: `dist/` and `dist_neatCSS/` directories

## Common Commands

```bash
# Deploy to GitHub Pages
npm run deploy
```

## Project Structure

- `dist/` — Main build output for deployment
- `dist_neatCSS/` — Alternative CSS build output
- `package.json` — Project config and deploy script

## Notes for Claude Code on Android / Web Sessions

- Configuration changes made here in `CLAUDE.md` persist across sessions (committed to repo)
- Use `.claude/settings.json` for tool permissions and hooks
- Local-only settings go in `.claude/settings.local.json` (gitignored)
