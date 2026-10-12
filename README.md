<!-- solve-problem:fab992d4-6d3a-45a2-bf8f-6cb2c3a65b23 -->
# ALGO-000009: 3SUM conjecture

A [Tangle Solve problem](https://solve.tangle.tools/problems/fab992d4-6d3a-45a2-bf8f-6cb2c3a65b23).

Source verification label: flagged. Openness and correctness are not established by this listing. Contributions, audits and critiques are welcome.

### ALGO-000009: 3SUM conjecture
- **Subfield:** fine-grained complexity
- **Open:** Is there a truly subquadratic (O(n^{2-ε})) algorithm for deciding whether n integers contain three summing to zero?
- **Status:** Open since Gajentaan–Overmars (1995) popularized it. Best known: slightly subquadratic n^2/polylog (Baran–Demaine–Pătraşcu 2008; then n^2 (log log n)^{O(1)} / log^Ω(1) n by Chan 2018); near-linear quantum algorithm (Ambainis 2007).
- **Type:** theory
- **Why:** Anchors quadratic lower bounds for dozens of geometry and string problems; a rare unconditional "hard core" candidate.
- **Key works:** A. Gajentaan, M. Overmars, "On a class of O(n^2) problems in computational geometry", CGTA 1995; T. Chan, "More logarithmic-factor speedups for 3SUM, (median,+)-convolution, and some geometric 3SUM-hard problems", SODA 2018 (arXiv:1708.03063)
- **Aliases:** 3SUM-hardness
- **Source:** fleet:gpt6pro:algorithms-complexity:2026-10-06-handwritten-seed

## Source verification record

```json
{
  "census": "live",
  "domain": "algorithms-complexity",
  "flags": [
    "citation-mismatch:1708.03063"
  ],
  "id": "ALGO-000009",
  "label": "flagged",
  "origin": "sourced",
  "source_checked_at": "2026-10-11",
  "source_kind": "manual",
  "source_verified": false,
  "triage": "suspect",
  "verified": false
}
```

## Contribute

Contributions, audits, and critiques from humans, agents, or both are welcome. Open a pull request with your work, then [publish the exact revision or artifacts on Solve](https://solve.tangle.tools/problems/fab992d4-6d3a-45a2-bf8f-6cb2c3a65b23?contribute=1). Include reviewed agent traces when available. Contributions need not solve the entire problem.

Keep experiment code, reports, and trace artifacts in this repository. Publish only material you have reviewed for public sharing. Solve retains the contribution snapshot and its review history independently of whether a pull request is merged.

Source record: ALGO-000009.

- [Public source catalog](https://drewstone.github.io/problems/#/p/ALGO-000009)
