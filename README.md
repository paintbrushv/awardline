# Awardline

Public road-bid results for North Texas, priced and sourced.

**Sample issue: https://paintbrushv.github.io/awardline/**

The sample covers TxDOT lettings in Cooke, Grayson, Denton and Collin counties: **67 contracts across
19 letting dates in the 24 weeks to 2026-11-12**, with a new result in 15 of those weeks. It is computed
from one dated pull of TxDOT Bid Tabulations (data.texas.gov, dataset `de7b-7dna`, pulled 2026-11-23).

## What is on the page

For each letting: the sealed engineer's estimate, the winning number, the winning bidder, and the gap
to the second-low bid. Dollars are printed exactly as the source publishes them, and every percentage
on the page is re-derived from the dollars printed beside it, so any row can be checked with a
calculator. A check re-runs that arithmetic before publication and fails on any gap past a tenth of a
point.

## Plans shown in the sample

| Plan | Price | Scope |
|---|---:|---|
| County Scout | $79 / month | One county, every letting in it, 12-month archive |
| District Desk | $149 / month | Cooke, Grayson, Denton, Collin; competitor win table; material price checks |
| Bid Room | $390 one time | One trade, one county, 12-month price study |

**Nothing here is for sale yet.** The page is the sample issue. There is no buy button and no charge.
Ordering opens when billing is live.

## What this repository holds

The published page and nothing else: `index.html`, `sitemap.xml`, an IndexNow key file, and `.nojekyll`.
The page is generated from the same dated pull file the prospect list is measured against, so the page
and the pool cannot disagree about the same letting.

## Limits

Not included: awards, line-item unit prices, addenda, change orders, rejected bids, and anything behind
a vendor registration wall. Agency records answer those. Nothing here is a survey, an appraisal, or
advice to bid a particular job.

Awardline is an independent data service. It is not affiliated with TxDOT, any county, or any contractor
named on the page. No customer names, testimonials or logos appear.
