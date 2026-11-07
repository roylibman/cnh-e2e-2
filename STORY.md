# Story: e2e5-232213

## Before

2026-11-06 23:26 PST. Radar Checks for namespace `team-e2e5-232213` (starter app, version c4bd37c): 0 critical, 0 high, 4 medium, 0 low.

Medium:
- `automountServiceAccountToken`: Deployment/app auto-mounts the service account token
- `readOnlyRootFs`: Deployment/app container `app` has a writable root filesystem
- `missingPDB`: Deployment/app has 2 replicas and no PodDisruptionBudget
- `missingTopologySpread`: Deployment/app has 2 replicas and no topology spread constraints
