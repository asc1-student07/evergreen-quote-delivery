# Go / No-Go — Merge Decision

There is an issue with renters calculations, with overly large quotes related to premium quoted.  Additionally, CI is failing specifically on a renters javascript file not being found - too much coincidence to be overlooked.  Development team will research the missing js, and once that is resolved, will install and retest the renters scenarios.  Management (Marc) will update stakeholders to set expectations.

**Date / time:** 7/15/26 10AM ET
**Decision:** ☐ GO   ☐ NO-GO   *☐*-> GO WITH CONDITIONS<-

## CI evidence

- Latest run on `delivery/lead`: red_ link: _paste URL_
- Workflow file: `.github/workflows/ci.yml`
- What the workflow actually checked: smoketest required fields

## What "GO" would mean

- Merge `delivery/lead` → `main`, squash, delete branch.
- Tag the merge commit `week-1`.

## What "NO-GO" would mean

- Hold the merge until: renters javascript file is installed
- Owner of that condition: Marc Gagne
- Re-evaluate at: 4pm Day 3

## My call

Go ahead with conditions.  CI run for syntax erros are not causing site usage issues, so they can be overlooked in the near term.  To allow us to continue, we can comment out the ability to do a renters quote, and once fixed, deploy that as a second iteration.
