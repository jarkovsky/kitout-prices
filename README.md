# kitout-prices

The API price table Kitout uses to estimate what Claude Code and Codex usage would cost at API rates. Kitout fetches `models.json` from this repo on its update-check schedule, caches it, and falls back to the copy built into the app.

- `as_of` is the day the vendors' pricing pages were read.
- Rates are US dollars per million tokens.
- Add a line to `CHANGELOG.md` with every change.
