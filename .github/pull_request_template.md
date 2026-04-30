## Summary

<!-- What changed and why -->

## Release / release-please

This repo uses **release-please**. Merge commits titled `Merge pull request #…` are not valid [Conventional Commits](https://www.conventionalcommits.org/), so release-please ignores them.

**When you merge:** use **Squash and merge** (conventional squash title, e.g. `fix:`, `feat:`) or **Rebase and merge** if every commit is conventional.

**Commit types and semver:** `fix:` / `feat:` drive version bumps by default. `docs:` / `chore:` alone may not open a release PR.

## Checklist

- [ ] Merge strategy matches whether this PR should affect release-please / changelog
