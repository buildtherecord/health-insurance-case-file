# Contributing

This repo exists so the next patient doesn't start from zero. The most valuable
contributions come from people who have actually run the method.

## What helps most

- **Prompt improvements from real use.** If a prompt produced something weak and you
  fixed it, PR the fix with one sentence on what went wrong. Keep the discipline
  rules intact — PRs that soften the evidence rules (source-or-it-doesn't-enter,
  verbatim quotes, no padded counts) will be declined.
- **Plan-type and state notes.** Short files under `jurisdictions/`: the appeal
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

## Mechanics

Fork, branch, PR. Keep files in the existing voice: short, concrete, no hype.
For demo-site changes, include a screenshot. By contributing you license your
contribution under Apache-2.0.
