# Data

One folder per day (`YYYY-MM-DD/`, UTC), each containing two subdirectories:

- `raw/` — per-platform original data, untouched (nine files: registries, GitHub snapshot, social-buzz measurements, X post links)
- `rankings/` — the nine ranking lists computed from `raw/`

`latest/` always mirrors the most recent day; `index/first-seen.csv` is the cumulative first-seen date index that powers `rising-stars`.

See the [methodology](../docs/methodology.md) for column semantics and normalization rules.

Composite score columns (`*_score`, `wis`) are derived values; the raw per-platform numbers they were computed from are always included in the same file.
