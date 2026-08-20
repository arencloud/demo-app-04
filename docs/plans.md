# Demo App 04 plans

Connectivity Link enforces these limits at the Gateway API route:

| Tier | Requests/minute | Monthly hard quota | Commercial price |
|---|---:|---:|---|
| Free | 10 | 1000 | Governed by the central Billing catalog |
| Developer | 1000 | 1000000 | Governed by the central Billing catalog |
| Enterprise | Unlimited | Contract | Contract |

Change the limits in `gitops/plans.yaml` through a pull request. Pricing and
included billable units remain centrally controlled so API owners cannot bypass
commercial governance by changing an application repository.

