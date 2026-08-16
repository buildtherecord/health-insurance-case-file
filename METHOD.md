# The method — health-insurance edition

The core doctrine is shared with [lemon-case-file](https://github.com/CaitlinEverett/lemon-case-file):
one source of truth, every number computed and asserted at build time, a screenshot
or letter proves only what is visible in it, quote them verbatim, curate ruthlessly,
never omit what would make you look dishonest, and **the record argues by existing**.
What follows is what changes when the counterparty is a health plan.

## 1. Deadlines are the spine

Every denial letter starts clocks: typically 180 days to file an internal appeal
under ERISA-governed employer plans, tighter windows in some state plans and
Medicare Advantage, and a window for external review after the final internal
denial. Urgent-care situations have expedited tracks measured in hours and days.

The FIRST artifact you build is the deadline board: for every adverse determination,
the date received, the governing appeal window, the computed due date, and the days
remaining — asserted in code from the letter dates. Everything else can be improved
later; a blown deadline cannot. When a deadline is near, file a timely short appeal
that preserves the right and supplement it afterward, rather than polishing past
the date.

## 2. Know which machinery governs your plan

Employer self-funded plan (ERISA, federal DOL oversight), fully-insured employer or
individual plan (state insurance department), Medicare Advantage (CMS machinery,
auto-forwarded second-level review), Medicaid managed care (state fair hearing).
The appeal rights, deadlines, external-review body, and regulator all differ. The
prompts force this determination first — your ID card, SPD, and the denial letter's
appeal-rights paragraph answer it.

## 3. The denial has anatomy — dissect it, verbatim

Every denial letter states (or is required to state) a reason, the plan provision or
criteria relied on, and your appeal rights. Extract each, quoted exactly. Denials
fall into families that are fought differently: not-medically-necessary (fight with
criteria + physician statement), experimental/investigational (fight with evidence
and plan definitions), out-of-network / no-prior-auth (fight with process facts and
network-adequacy rules), coding/administrative (often fixable by the provider's
biller — make them refile before you appeal), and eligibility. Misclassifying the
family wastes your one internal appeal.

## 4. Their own file is your best exhibit

After an adverse determination you are generally entitled — free, on written
request — to the insurer's complete claim file: everything they relied on, the
internal guidelines and criteria applied, and the identity/specialty of the
reviewing clinician. Request it immediately, before drafting the appeal. Appeals
are won on gaps between what the plan's own criteria say and what the reviewer did:
a cardiology denial reviewed by a non-specialist, criteria that don't match the
plan document, a "review" completed in less time than it takes to read the chart.
You cannot find those gaps without the file. (This is the exact analog of
requesting the manufacturer's diagnostic logs in the lemon-law method.)

## 5. The record is process facts; medicine belongs to your physician

Your ledger records what was submitted, when, by whom, what they said, and what
their own documents show. The medical-necessity argument is your treating
physician's, in their letter, in their words — the method's job is to make sure
that letter answers the plan's actual criteria point by point (give the physician
the criteria; don't make them guess) and lands attached to a complete, on-time
packet. Never paraphrase medicine in your own voice in the record.

## 6. Call discipline

Every phone call: date, time, representative's name, and the reference number —
ask for it every time, and log it the same hour. "A representative told us it was
covered" is worth little; "Reference #X, rep N., on <date>, stated prior
authorization was not required — call log attached, and the plan's own call
recording is requested in the claim file" is evidence.

## 7. Escalation is a ladder, and each rung is a record

Internal appeal (use every level offered) → external review by an independent
review organization (typically binding on the insurer) → state insurance
department complaint / DOL-EBSA for ERISA plans → counsel, who inherits a complete
record. Every rung's submission is generated from the same bundle; every rung's
outcome letter goes back into it. Regulator complaints in particular convert your
private paper into a docketed record — and pattern complaints are how algorithmic
mass-denial practices come to light (see EXEMPLARS.md).

## 8. The mitzvah stat

Fewer than 1 in 100 denials is appealed; a third of appeals win, and external
reviews win at meaningful rates too. The system's economics assume you will not
file. A complete, on-time, criteria-matched appeal packet is a statistical
outlier — which is exactly why it works.
