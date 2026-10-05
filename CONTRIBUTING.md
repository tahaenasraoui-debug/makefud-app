# Contributing to MakeFud

Contributions of any size are welcome, including during Hacktoberfest.

## Ground rules

- Keep the zero-build constraint. No npm, bundlers or frameworks. Vanilla ES6+ and native CSS only.
- Never commit API keys, and never add a hardcoded key to any file.
- One concern per pull request. Small PRs get reviewed faster.
- Run the app with "Use demo / mock data" on and confirm sorting, tags and error states still work.
- Escape any API-derived string before inserting it into HTML.
- Keep it accessible: visible focus, labels on controls, usable on a 360px wide screen.
- Spam, trivial whitespace changes and PRs made only to collect a swag shirt will be closed.

## How to submit

1. Fork the repo and create a branch: `git checkout -b fix/short-description`.
2. Make your change and test it locally by opening `index.html` or running `python3 -m http.server`.
3. Open a PR describing what changed and why. Add a screenshot for UI changes.

## Good first issues

- Add a "max calories" and "max minutes" filter.
- Add a pantry-staples toggle (salt, oil, water) that ignores common items when counting missing ingredients.
- Add a web app manifest and a service worker for offline demo mode.
- Add diet filters (vegetarian, vegan, gluten free) that map to Spoonacular parameters.
- Improve ingredient matching (plurals, synonyms, accents).
- Add TheMealDB as an optional provider, following the notes in `DISCLAIMER.md`.
- Translate the UI strings.
- Add a light/dark theme toggle that overrides the system setting.

## Reporting bugs

Open an issue with your browser, steps to reproduce, and whether you were in demo or live mode. Never paste your API key.
