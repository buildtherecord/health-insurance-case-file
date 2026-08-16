# Exemplars worth reading

The demo in `docs/` is **fictional** — every name, plan, document, and number is
invented. We do not rebuild real patients' files. What follows is the real public
record showing how modern denial machinery works, and why a complete paper record
beats it.

## The numbers

- **KFF, Claims Denials and Appeals in ACA Marketplace Plans (2024 data):**
  19% of in-network claims denied; fewer than 1% of denials appealed; 34% of
  internal appeals overturned the denial.
  https://www.kff.org/patient-consumer-protections/claims-denials-and-appeals-in-aca-marketplace-plans-in-2024/
  The single most important fact in this repo: **the appeal you don't file is the
  denial that stands.**

## The denial machinery, documented

- **ProPublica — Cigna's PxDx system (2023– ).** Investigative reporting and
  subsequent litigation over a review system in which company doctors denied
  claims in bulk without opening patient files — spending, per internal records
  cited in the reporting, an average of ~1.2 seconds per case. Congressional and
  regulatory scrutiny followed; class actions were allowed to proceed.
  https://www.propublica.org/article/cigna-health-insurance-denials-pxdx-congress-investigation
  Lesson: *the "review" of your claim may never have read your chart — the claim
  file request (prompt 04) is how you find out.*

- **STAT News — UnitedHealth and the nH Predict algorithm (2023– ).** Reporting
  and a federal class action alleging an algorithm was used to cut off Medicare
  Advantage post-acute care against treating clinicians' judgment — with internal
  targets keyed to the algorithm's predictions, in a population where almost no
  one appeals. Courts have ordered broad discovery.
  https://www.statnews.com/2023/11/14/unitedhealth-class-action-lawsuit-algorithm-medicare-advantage/
  Lesson: *denial pipelines are calibrated to non-appeal rates. Appealing, on
  time, with the treating clinician's record, is the countermeasure the pipeline
  assumes you won't take.*

- **Wit v. United Behavioral Health (N.D. Cal. / 9th Cir., 2019–2023).** The
  landmark behavioral-health case: a district court found UBH's internal coverage
  guidelines were skewed against generally accepted standards of care; years of
  appellate back-and-forth followed, with the Ninth Circuit reversing in part and
  reissuing its opinion more than once. Read it for what discovery revealed about
  internally-authored "criteria" — and as a caution that big-system litigation is
  slow and uncertain, which is exactly why the individual appeal record matters.
  https://law.justia.com/cases/federal/appellate-courts/ca9/20-17363/20-17363-2023-01-26-0.html

## The demo case

`docs/index.html` shows the finished shape: the fictional owner of a fictional
"Acme Health Plan" policy fights a prior-auth denial for imaging
("not medically necessary" — overturned internally once the plan's own criteria
were quoted back with the physician's letter) and an algorithm-flavored cutoff of
post-surgical rehabilitation days (upheld internally, overturned on external
review). Any resemblance to real persons, plans, or insurers is unintended.
