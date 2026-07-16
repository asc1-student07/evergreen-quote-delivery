# Decision Memo — _short title here_

> Copy to `delivery-leadership-package/decision-memo.md`. Target length: ~250 words. Write for a non-technical reader. Name the options you **rejected**, not just the one you picked.

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

## Github Copilot change

Using the following prompt:

>in the testimonials section of this html file, can you auto generate two more entries that follow the tone and length of the three provided?  Also, make sure the additional entries retain the same responsive design as what is there now.  If you have any questions, ask me one at a time and don't build anything based on assumption.

Copilot, in one pass, created two more on-tone testimonial cards that matched the style of what was there and kept the responsivess of the site. In testing, no issue where found