# health-insurance-case-file

**A method and a set of AI prompts for a patient (or their family) to fight a health
insurance denial with a professional-grade paper record** — the internal appeal, the
external review, and the regulator complaint — without hiring anyone.

The numbers say the quiet part: in 2024, ACA-marketplace insurers denied **19% of
in-network claims**. Consumers appealed **less than 1%** of those denials — and when
they did appeal, **34% of the appeals won** ([KFF](https://www.kff.org/patient-consumer-protections/claims-denials-and-appeals-in-aca-marketplace-plans-in-2024/)).
The appeal you never file is the denial that stands. Insurers know this; some have
built denial pipelines that depend on it (see [`EXEMPLARS.md`](EXEMPLARS.md)).

This is the health-insurance sibling of
[lemon-case-file](https://github.com/buildtherecord/lemon-case-file). Same doctrine —
one source of truth, every number verified, quote-them-verbatim, the record argues by
existing — adapted to a world of EOBs, denial codes, medical-necessity criteria, and
**deadlines that can kill a valid claim**.

**See what you end up with:** the [demo appeal file](https://buildtherecord.github.io/health-insurance-case-file/)
— a fully fictional exemplar (every name, plan, document, and number invented).

## What you end up with

- **A denial ledger** — every claim and prior-auth: what was denied, the insurer's
  stated reason quoted verbatim, the criteria they cited, and what happened on appeal.
- **A deadline board** — every appeal window computed from the denial dates, because
  the first thing a denial letter does is start a clock.
- **The claim-file request** — after an adverse determination you are generally
  entitled to the insurer's complete file on your claim, including the internal
  guidelines they relied on and the reviewer's specialty. Their own file is usually
  where the appeal is won.
- **An appeal packet** — the denial anatomy, the plan's own coverage language, your
  physician's necessity statement, and exhibits, assembled so a reviewer can say yes
  in one pass.
- **The escalation map** — internal appeal → external review (independent, usually
  binding) → state insurance regulator / federal DOL, with what each step needs.

## How to use it

1. **Triage deadlines first.** Open [`prompts/00-START-HERE.md`](prompts/00-START-HERE.md)
   with an AI assistant that can read your files. Prompt 02 computes every clock
   before anything else happens — a perfect record filed one day late is worth nothing.
2. Read [`METHOD.md`](METHOD.md) — ten minutes.
3. Work the prompts in order. Each produces a concrete artifact.
4. Run the adversarial pass ([`prompts/08`](prompts/08-adversarial-review.md)) before
   anything is sent.

You do not need to be technical, and your doctor does not need to do more than what
they already do — the method assembles what exists into a record that is hard to
say no to.

## What this is not

Not legal advice, not medical advice. It does not tell you what care you need — that
is between you and your clinicians. It organizes the fight over whether the plan pays
for it. ERISA employer plans, state-regulated plans, Medicare Advantage, and Medicaid
each have different appeal machinery; the prompts make the assistant identify which
one governs YOUR plan before drafting anything. Deadlines are jurisdiction- and
plan-specific. Cases involving ongoing urgent care have expedited paths — use them,
and get professional help when the stakes are high.

## Contributing back

Prompt fixes from real appeals, plan-type notes (ERISA vs. state vs. MA vs. Medicaid),
state external-review notes, and anonymized outcomes are welcome. Real medical records
or claim documents are not — this repo stays 100% synthetic. See
[`CONTRIBUTING.md`](CONTRIBUTING.md).

## License

Apache-2.0.
