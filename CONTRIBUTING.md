# Contributing

## Scope

This repository is a curated Seedance 2.0 prompt library. Contributions should improve prompt quality, source attribution, and repository consistency.

## What qualifies as a valid entry

Keep entries that are actually usable as prompts:

- direct video-generation prompts
- reusable prompt templates
- structured JSON prompts when the structure is part of the usable prompt format
- reference-driven prompts that rely on tokens such as `@image1`, `<<<Image1>>>`, or first/last-frame instructions

Do not add entries that are mostly:

- commentary about prompts
- repost captions or marketing copy
- discussion replies or opinions
- fragments too short to be actionable
- social chatter where the usable prompt is missing

## Cleaning rules

- Remove social-handle mentions like `@username` when they are not part of the prompt logic.
- Preserve prompt-internal reference syntax such as `@image1` when it is required by the prompt.
- Keep the source link in metadata, not inside the prompt body.
- Do not silently rewrite a prompt's meaning. Cleaning should remove noise, not alter intent.

## Attribution rules

Each entry should preserve:

- original source link
- original language
- original publication date when available

## README consistency rules

When the dataset changes, update the README in the same change set:

- regenerate prompt counts
- regenerate latest source date
- keep numbering aligned with the cleaned dataset order
- remove stale entries from `Featured Prompts` or `All Prompts`
- do not leave links to missing localized README files

## Pull request checklist

Before opening a PR, verify:

- the new or edited entry is a real prompt
- numbering is still correct
- statistics still match the cleaned dataset
- source links work
- formatting remains GitHub-readable
