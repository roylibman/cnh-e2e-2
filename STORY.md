# Story

## Before

2026-11-06 23:48 PST · [Radar Checks for team-e2e6-234419](https://app.radarhq.io/checks?scope=43o-mt-ALYE&namespace=team-e2e6-234419)

0 critical, 0 high, 4 medium, 0 low (all on Deployment `app`):

- medium · Security · `automountServiceAccountToken`: service account token is auto-mounted
- medium · Security · `readOnlyRootFs`: container `app` does not use a read-only root filesystem
- medium · Reliability · `missingPDB`: 2 replicas, no PodDisruptionBudget
- medium · Reliability · `missingTopologySpread`: 2 replicas, no topology spread constraints
