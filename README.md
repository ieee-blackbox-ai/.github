# .github

Organisation profile for **BLACKBOX AI** — IEEE Student Branch, GCET.

`profile/README.md` is what renders on <https://github.com/ieee-blackbox-ai>.

> **This repository must be public** for the profile README to display, even though the
> organisation's other repositories are private. It contains nothing sensitive.

## Pushing

```bash
gh repo create ieee-blackbox-ai/.github --public --description "Organisation profile for BLACKBOX AI"
git remote add origin https://github.com/ieee-blackbox-ai/.github.git
git push -u origin main
```

The repo name must be exactly `.github` — an organisation profile does not come from a
repo named after the org. (That pattern is for personal accounts.)

## Updating between editions

The profile is written for the series, not a single event. When 1.0 finishes:

1. Move 1.0 to a past edition in the series table with its outcome.
2. Promote the next edition to **Current edition**.
3. Update the dates, track and prize pool block.

Everything else should keep working unchanged.
