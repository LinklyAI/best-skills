---
name: best-skills
description: Daily cross-platform rankings of AI agent skills (skills.sh, ClawHub, Tencent SkillHub, GitHub, X/HN/Bluesky). Use when the user asks which agent skill to install, what is trending, whether a skill is popular or trusted, or wants to compare skills. Read-only public CSV data; it recommends and links, it does not install anything.
---

# Best Agent Skills

Nine Top-100 lists, refreshed daily, with the raw per-platform numbers kept next to every score. Full guide and column dictionary: https://raw.githubusercontent.com/LinklyAI/best-skills/main/llms.txt

## When to use

- "Which skill should I install for browser automation / PDF / …" → `best-100.csv`, filter by `description` and `skill`
- "What is trending / new this week" → `trending-7d.csv`, `rising-stars.csv`
- "Is `<skill>` popular, maintained, official?" → `best-100.csv` (score and dimensions), `official-100.csv`, `most-active.csv`
- "Compare A and B" → look both up by `skill_key`, cite raw counts per platform

Not for: installing skills (hand the user the `install` command), full-text search of every skill in existence (only the Top 100 per list is published; the raw snapshots under `data/latest/raw/` go deeper), judging quality beyond the published counts.

## Workflow

1. Fetch `https://raw.githubusercontent.com/LinklyAI/best-skills/main/llms.txt` first. It is the current column dictionary and the rules; do not rely on a cached copy.
2. Pick the list, fetch `https://raw.githubusercontent.com/LinklyAI/best-skills/main/data/latest/rankings/<list>.csv` (4–90 KB, ≤100 rows). Parse by header name; an empty cell means "not measured", not zero.
3. Answer with rank, the raw numbers, `install` and `url`. Show `vendor` next to `skill`: same-name skills from different vendors are different skills.
4. For history, replace `latest` with `YYYY-MM-DD` (daily since 2026-08-16).

## Lists

`best-100` (overall score), `top-installs`, `trending-7d`, `social-buzz`, `most-active`, `official-100`, `official-vendors`, `top-repos`, `rising-stars`.

## Rules

- Never add install counts across platforms; present them side by side.
- Absent from a list ≠ zero; lists are truncated at 100.
- Attribute republished data: "Data from Best Skills (https://github.com/LinklyAI/best-skills) — CC BY 4.0".
