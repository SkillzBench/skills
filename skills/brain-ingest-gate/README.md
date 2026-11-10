# brain-ingest-gate

[![SkillzBench](https://skillzbench.com/api/badge/brain-ingest-gate)](https://skillzbench.com/skills/brain-ingest-gate)

Pre-write quality gate for content entering the brain. No raw copies: a bare cp/mv into the brain repo is a bug. Before any new page lands, resolve named entities registry-first (a vector score is a floor for prose, never a gate for named things), then run the read-the-top-hit dedup decision tree (clear-dup / plausible-dup / clear). Owns dedup; delegates enrichment to the shipped ingestion skills. Routing convention, not an operation-boundary enforcement.

Mirrored from [skillzbench.com/skills/brain-ingest-gate](https://skillzbench.com/skills/brain-ingest-gate) — Trust Score, benchmarks and install options live there.
