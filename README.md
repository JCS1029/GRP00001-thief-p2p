# Thief Peer — Police-Thief P2P

Standalone `Thief` export of the canonical Police-Thief P2P workspace.

- This repository: [https://github.com/JCS1029/GRP00001-thief-p2p](https://github.com/JCS1029/GRP00001-thief-p2p)
- Sibling Police repository: [https://github.com/JCS1029/GRP00001-police-p2p](https://github.com/JCS1029/GRP00001-police-p2p)
- Annotated submission tag: `v1.0-submission`
- Frozen from canonical commit `3d28b686a7aafca040b34aa922fe6ad4fe918397`

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
