# Release Readiness Checklist

Use this checklist to confirm a release is ready to ship. Copy it into the release ticket and check items off as you go.

## Code & Testing
- [ ] All planned changes are merged; no blockers in the milestone
- [ ] CI is green on the release commit
- [ ] Unit, integration, and smoke tests pass
- [ ] Release notes / changelog is drafted and reviewed

## Review & Sign-off
- [ ] Pull request reviewed and approved by at least one maintainer
- [ ] No open review comments marked blocking
- [ ] Security and dependency alerts reviewed and triaged

## Deployment
- [ ] Rollout plan documented (and rollback plan too)
- [ ] Feature flags checked; deprecated paths cleaned up
- [ ] Release tagged, and the tag is announced in the team channel
