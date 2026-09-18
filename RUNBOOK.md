# Release Readiness Runbook

Use this checklist before cutting any release.

## Pre-release checklist

- [ ] All issues in the release milestone are closed or moved
- [ ] CI is green on the release commit
- [ ] Version bump and changelog entries are up to date
- [ ] Security and dependency alerts are reviewed (no unresolved criticals)
- [ ] Smoke tests pass in staging
- [ ] Release notes drafted and proofread

## Go / no-go

- [ ] Release owner signs off
- [ ] Rollback plan confirmed and communicated
