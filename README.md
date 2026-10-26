# Lab notebook of Uladzimir Khadakouski

AI/QA engineer in Purmerend, NL. I build AI you can verify.

Trustworthy AI needs rulers that cannot quietly move: frozen evaluations, guarded memory, and rights earned through verified results.

**Current entries: 001 oathgate, 002 memgate, 003 Genkan (running).**

### [001 — oathgate](https://github.com/UladzKha/oathgate) · public · [PyPI](https://pypi.org/project/oathgate/)

Hypothesis: an evaluation is trustworthy only if its method is fixed before the run. `oathgate predict` freezes that method into a hash; `oathgate check` returns 0 if it holds, 1 if it moved, or 2 if it cannot tell. v0.1.0 has zero runtime dependencies and 55 tests on Python 3.11–3.13. Its CI checks the repo with its own lock.

### [002 — memgate](https://github.com/UladzKha/memgate) · public · [pilot](https://github.com/UladzKha/memory-gate-pilot) · [dataset](https://doi.org/10.5281/zenodo.23665517)

Hypothesis: untrusted text needs a gate before it becomes agent memory. A deterministic local gate uses provenance tags and an action-time guard. No LLM runs inside it. The pilot used three local ~24–31B models: Qwen, Gemma, and Mistral.

### 003 — Genkan · private · running

Hypothesis: agents should earn rights through verified results. Genkan is a continuity runtime for one personal agent whose identity, memory, and goals survive as cognition moves between devices. In progress.

**Current focus:** leading an AI-based testing initiative at EssilorLuxottica; moving toward Lead/Staff AI Engineer. I started as a frontend lead and have 9+ years in engineering.

[Open the notebook](https://uladzkha.github.io) · [GitHub](https://github.com/UladzKha) · [X](https://x.com/u_kouski) · [LinkedIn](https://www.linkedin.com/in/k-dalu/) · [Email](mailto:raer.camp@gmail.com)
