# Dylan Stechmann

Computational regenerative medicine and geroscience tooling. The repositories are research artifacts. They are not clinical advice, dosing guidance, or a biological-age clock.

Student at Florida Atlantic University (MS, Artificial Intelligence). Experimental projects, often built with AI-assisted coding. Hobby use first; no lab-collaboration pitch.

## Start here

- [regen-workbench](https://github.com/dylanstechmann/regen-workbench) — local Docker lab and MCP sidecar
- [geroscience-compound-atlas](https://github.com/dylanstechmann/geroscience-compound-atlas) — public compounds, graded evidence, scaffold-split bake-off, play vs hypothesis generation — [live atlas](https://dylanstechmann.github.io/geroscience-compound-atlas/)

## The stack

| Piece | Role |
|---|---|
| [cell-protocol-compiler](https://github.com/dylanstechmann/cell-protocol-compiler) | Machine-readable checklists for published hiPSC workflows |
| [brightfield-colony-qc](https://github.com/dylanstechmann/brightfield-colony-qc) | Morphology QC. A flag is triage, not a diagnosis |
| [diffmedia-loop](https://github.com/dylanstechmann/diffmedia-loop) | In-vitro media search on a synthetic surface |
| [regen-benchmark-kit](https://github.com/dylanstechmann/regen-benchmark-kit) | Group-aware baselines and input hashes |
| [senescence-module-score](https://github.com/dylanstechmann/senescence-module-score) | SenMayo control-gene score |
| [organoid-oxygen-lab](https://github.com/dylanstechmann/organoid-oxygen-lab) | Conservative spherical oxygen transport |
| [cell-fate-transport](https://github.com/dylanstechmann/cell-fate-transport) | Balanced optimal transport for cell-state snapshots |
| [perfusion-calibration-lab](https://github.com/dylanstechmann/perfusion-calibration-lab) | Offline gravimetric flow checks |
| [open-perfusion-rig](https://github.com/dylanstechmann/open-perfusion-rig) | Host-side simulation of a research perfusion rig |
| [anagen](https://github.com/dylanstechmann/anagen) | Hair/tooth research map — [live](https://dylanstechmann.github.io/anagen/) |

## Generation

In the atlas: `make generate` is play mode. `make hypothesis` applies hard property gates and an anti-clone Tanimoto cap, then writes cards under `hypotheses/`. Cards are not a stack.

## Agent queue (one repo per session)

1. `geroscience-compound-atlas` — run `make hypothesis` locally and inspect reject counts.
2. `organoid-oxygen-lab` — keep units honest; do not fit fake biology.
3. `regen-benchmark-kit` + `brightfield-colony-qc` — do not invent a new imaging cohort.
4. `diffmedia-loop` + `cell-protocol-compiler` — planner stays inside encoded windows.
5. `cell-fate-transport` — stay balanced unless a growth model is implemented on purpose.
6. `open-perfusion-rig` + `perfusion-calibration-lab` — analysis only; no medical infusion claims.
7. `regen-workbench` — host `.env` and MCP; never paste keys into chat.

Out of this queue unless named: `AI_Companion`, `ReaperDelay`, `AvoidGrimReaper`, `diaper-changing-machines`, `Story`.
