# Release readiness checklist

Working checklist for this repo. Work the gates in order and record each outcome in `docs/audit-log.md`.

## Reference release

The reference example for this checklist is the newest tag published by the GitHub CLI project (`cli/cli`) in GitHub's own org:

- Tag: `v2.102.0`
- Commit SHA: `fc4b137cdef0a6bd28fd461b7cf9c84a5812a8cd`

Both values were taken from live GitHub lookups when this checklist was written. This is the shape we want for every release we cut: a tag name plus the exact commit it points to.

## Gates

1. Dependency review - confirm dependency alerts are triaged and nothing critical is open.
2. Secret hygiene - confirm secret scanning is enabled and all alerts are resolved.
3. Changelog verification - confirm the changelog covers every merged PR since the last release.

## Sign-off

A release is ready when all three gates are recorded as passing in the audit log and a tag has been cut from a green commit.
