# Prompt 09 — The packet as PDF (and, rarely, a site)

---

Generate the master PDF from the bundle: cover chronology (one page), the
deadline board, the denial ledger, each appeal/response in order, the
claim-file gap list, exhibits with a numbered index. Every number asserted at
build; filename carries the month and year. This is the file a lawyer, a
regulator, or a state consumer-assistance program can pick up cold.

A password-gated evidence site (see `site/` — same kit as the sibling repos)
is worth building only for long multi-denial sagas with many documents and
parties: it gives reviewers one-click access to full documents and gives you
an access log. For a single denial, the PDF packet is the right tool — don't
build infrastructure the dispute doesn't need.

If a site is warranted: PHI discipline is stricter than PII. Nothing goes
online beyond what the dispute requires; strip EXIF; the reviewer credential
goes only to named case handlers; rotate credentials when the matter closes.
