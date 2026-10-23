# Research problem — working brief

**Status:** Scoping (23 October 2026)  
**Competition track:** Micron MIMORY Awards — Advanced Process Technology  
**Available tools:** SEMulator3D and Synopsys Sentaurus TCAD

## Objective

Identify a fabrication-process variation in a memory-device structure, then test whether its effect on geometry and electrical performance can be quantified with reproducible simulations.

This is an initial research brief, **not** a claim of novelty or a finalized project proposal.

## First-principles model

1. **Process input:** A controllable fabrication variable (for example, etch or deposition conditions).
2. **Physical structure:** The resulting device dimensions, profiles, and material boundaries.
3. **Electrical behavior:** A measurable device response under stated simulation conditions.
4. **Comparison:** A baseline and controlled variations, with consistent assumptions.

SEMulator3D can support process-geometry modeling; Sentaurus can support electrical modeling. A direct transfer workflow between the tools has **not yet been established**.

## Decisions still open

- **Memory technology:** DRAM / 3D NAND / emerging memory — undecided
- **Device structure:** TBD
- **Process step and variable:** TBD
- **Baseline and reference literature:** TBD
- **Primary electrical metric:** TBD
- **Testable research hypothesis:** TBD

## Minimum validation standard

- Reproduce a clearly documented baseline.
- Change one process variable at a time initially.
- Use explicit units, ranges, and boundary conditions.
- Quantify sensitivity and compare results against credible published work where possible.
- Record tool versions, model assumptions, scripts, figures, and limitations.
- Distinguish simulation predictions from experimentally verified fabrication results.

## Research and repository hygiene

Do not commit proprietary process recipes, licensed PDK files, confidential model decks, credentials, or restricted software outputs. Keep competition-specific submissions separate until the current edition's rules are confirmed.

## Next decision

Select the memory structure to investigate before writing the first experiment.
