# Contributing

Thanks for helping strengthen **Memory Statue v2**. The goal here is not "more content," but **more truth per page**—tested claims, reproducible artifacts, and clear reasoning.

## Quick start
1. **Search existing issues** to avoid duplicates.
2. If you're reporting a problem or proposing a change, open an **Issue** first (recommended).
3. Fork the repo, make a branch, and open a **Pull Request**.

## What kinds of contributions are welcome?
- **Errata / corrections** (typos, unclear definitions, broken cross-references)
- **Reproducibility improvements** (build fixes, scripts, checks, packaging)
- **Implementation notes** (what you built, what failed, what worked)
- **Validation harness ideas** (benchmarks, drift tests, ablations, failure cases)
- **Figures / diagrams** improvements (clarity, correctness, alignment to text)
- **Use cases & results** (anonymized is fine)

## Preferred contribution style (how to be maximally helpful)
### If you're claiming something:
Provide at least one of:
- a minimal reproducible example,
- logs or traces (redact secrets),
- metrics and how you measured them,
- a clear "before vs after" explanation.

### If you're proposing changes to the manuscript:
- Keep edits **surgical**.
- Avoid stylistic rewrites unless necessary for clarity.
- Preserve terminology unless you also provide a reason + migration note.

## Pull request guidelines
Your PR description should include:
- **What changed** (1–5 bullets)
- **Why** (the reasoning)
- **Evidence** (repro steps, screenshots, metrics, or references inside the repo)
- **Scope** (what you intentionally did *not* change)

If your PR affects the paper source, please confirm:
- [ ] PDF builds successfully (or explain why it doesn't)
- [ ] Figures compile/render correctly (if applicable)
- [ ] No unrelated formatting churn

## Issue templates (use these headings)
### Bug / Errata
- **Location:** (file + section + line if possible)
- **Problem:** (what's wrong)
- **Proposed fix:** (what you think it should be)
- **Evidence:** (why)

### Experiment / Validation report
- **Goal:** (what you tested)
- **Setup:** (model/tooling/environment)
- **Procedure:** (steps)
- **Results:** (metrics/logs)
- **Notes:** (failures, surprises, next tests)

## Licensing note (important)
This repository is **source-available and non-commercial**.  
By contributing, you agree that your contributions may be distributed under the same terms described in `LICENSE`, and you affirm you have the right to submit the content you provide.

## Security & privacy
- Do not include API keys, secrets, private dataset material, or personal data.
- If you suspect a security issue, **do not** open a public issue—contact the maintainer privately.

## Thank you
Contributions that add clarity, testability, or real-world validation are pure gold. You're helping turn an idea into a system the world can trust.
