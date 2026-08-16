# Contributing

This repo exists so the next patient doesn't start from zero. The most valuable
contributions come from people who have actually run the method.

## What helps most

- **Prompt improvements from real use.** If a prompt produced something weak and you
  fixed it, PR the fix with one sentence on what went wrong. Keep the discipline
  rules intact — PRs that soften the evidence rules (source-or-it-doesn't-enter,
  verbatim quotes, no padded counts) will be declined.
- **Plan-type and state notes.** Files under `jurisdictions/` — copy `jurisdictions/TEMPLATE.md`, cite primary
  sources, run `python3 tools/validate_jurisdictions.py` before the PR: the appeal
  machinery for a plan type or state — windows, the external-review body, the
  regulator, quirks. Cite the rule; no legal advice, just signposts.
- **Insurer notes.** What worked in claim-file requests, portal quirks, where the
  criteria documents live, decision-deadline behavior.
- **Anonymized outcomes.** A short writeup of how the method held up — what the
  reviewer engaged with, what they ignored. Strip every identifying detail; see
  `prompts/09` for the scope-B checklist. Do not include settlement terms if you
  agreed to keep them confidential.
- **Accessibility and translation.** Plain-language rewrites and translations of
  the prompts.

## What we won't take

- Real medical or claim documents, even redacted, even yours — this repo stays
  100% synthetic. PHI never enters, period.
- Content attacking a specific insurer. The method's power is that it doesn't
  editorialize.
- Anything that turns prompts into legal argument templates. The record states
  facts; the cover email names the standard once. That's the design.

## If you practice law

The highest-leverage hour anyone can give this repo is a practitioner's review:
where could this method mislead a layperson in your jurisdiction? Which prompt
should say "stop — get counsel now"? What belongs in your state's
`jurisdictions/` signpost file? Open an issue or write to
**mailbox@buildtherecord.org**. Contributions are public under Apache-2.0;
nothing here creates an attorney-client relationship, and no contribution is
presented as an endorsement of any individual claim.

## Mechanics

Fork, branch, PR. Keep files in the existing voice: short, concrete, no hype.
For demo-site changes, include a screenshot. By contributing you license your
contribution under Apache-2.0.

Questions and anonymized outcomes: **mailbox@buildtherecord.org**.
