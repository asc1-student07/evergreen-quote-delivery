# Decision Memo — Evergreen Insurance Quote

**Date:** 7/14/26
**Author:** Marc Gagne
**Decision area:** Day 2 scope tradeoff

## Context

Legal was delayed in getting signoff for posting testimonials

## Options considered

1. **Option A — Hide testimonials with d-none.** quick / still viewable in source
2. **Option B — Remove testimonials from html source.** no way for users to view / slow to restore


## Recommendation

Since this is a legal issue, the best approach is to remove from the html source altogher to remove legal risk.  Savvy web users could simply use browsers built in view-source to see them if they wanted to.

## Why

Legal protection

## What would change my mind

If Legal got the ok to post before day 4, this would be moot.

