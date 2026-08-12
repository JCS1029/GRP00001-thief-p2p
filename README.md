# Thief Peer — Police-Thief P2P

Standalone `Thief` export of the canonical Police-Thief P2P workspace.

- This repository: [https://github.com/JCS1029/GRP00001-thief-p2p](https://github.com/JCS1029/GRP00001-thief-p2p)
- Sibling Police repository: [https://github.com/JCS1029/GRP00001-police-p2p](https://github.com/JCS1029/GRP00001-police-p2p)
- Annotated submission tag: `v1.0-submission`
- Frozen from canonical commit `bfa31f635425f0abeddfc08732dfca5c0c3ebd4c`

```text
uv python install 3.13
uv sync --frozen --all-groups
uv run police-thief-p2p readiness
```

Full operator guide: `README.canonical.md`. Academic model, protocol, strategy,
experiments, and operations live under `docs/`.

Result JSON examples: `results/benchmarks/m12_tuning.json`,
`results/benchmarks/m12_selection.json`, `results/benchmarks/m12_language.json`,
`results/benchmarks/m12_league_rehearsal.json`.
