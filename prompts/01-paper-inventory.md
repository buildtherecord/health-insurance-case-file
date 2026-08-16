# Prompt 01 — Paper inventory

---

Inventory every document in my insurance dispute. Sources: my insurer portal
downloads (EOBs, letters), mail scans, my provider portal (claims, orders,
notes I already have), email, and my call notes.

For each item: date on the document, date received (if different — envelopes
matter for deadlines), type (EOB / denial letter / prior-auth determination /
appeal acknowledgment / plan document / SPD / physician letter / bill), the
claim number(s) and service dates it references, and one factual sentence on
what it says — with the decisive line quoted verbatim.

Also build the call log from whatever exists (notes, phone screenshots, portal
message threads): date, time, representative name, reference number, what was
said — only what my contemporaneous notes actually record. Flag calls I
mention from memory with no note as unverified.

Rules:
- Never rename originals. Output a manifest I can review.
- Flag every document whose received-date is unknown — those create deadline
  ambiguity we must resolve conservatively (prompt 02).
- Flag any EOB row where the denial code on the EOB differs from the reason in
  the letter — that mismatch is evidence.
- List what is MISSING: no SPD/plan document on file? No letter for a denial
  that appears on an EOB? Missing items become the first requests we send.

---

## Afterward

Get the plan document/SPD if you don't have it — request it in writing from the
plan administrator (ERISA plans owe it to you on request). Everything later
quotes it.
