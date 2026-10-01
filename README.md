# experiments

A collection of research experiments, simulations, reports, and supporting figures/data.

## Canonical artifact layout

- `artifacts/zip-files/` — zipped experiment outputs and bundles
- `artifacts/conversations/` — conversation notes in Markdown (`.md`)
- `artifacts/sandboxes/` — sandbox projects, snippets, and throwaway prototypes
- `artifacts/graphs/` — charts, diagrams, and visual outputs
- `artifacts/open-questions/` — evolving questions and research TODOs

Each folder contains a `.gitkeep` so the structure is tracked even when empty.

## Current contents

### `Godel_Height_20260730/`
Gödel Height experiment stack — simulation code, forks, results, and figures.
- `Godel_Height_Report.md` — main report
- `model_note.md` — model notes
- `godel_stack_sim.py`, `checks.py` — core simulation and checks
- `fork1_earn_label.py`, `fork2_cost_sweep.py` — experiment forks
- `make_figures.py`, `make_fork_figures.py` — figure generation
- `figures/` — generated figures (fig1–fig8)
- `results/` — JSON result outputs
- `todo.md`, `todo_forks.md` — task tracking

### `Antifragile_Systems_Research_20260730/`
Antifragile Systems research — simulations, analysis reports, and figures.
- `Antifragile_Systems_Report.md` — main report
- `Simulation_Report.md`, `Critique_Report.md`, `Triangulation_Matrix.md` — supporting analysis
- `antifragile_sim.py`, `run_experiments.py` — simulation code
- `figures/` — generated figures (fig1–fig6)
- `results/` — CSV and JSON result outputs
- `todo.md`, `todo_simulation.md`, `todo_upgrade.md` — task tracking

### `deep-research_Godel_sandbox_convo_superninja.txt`
Deep-research conversation log related to the Gödel Height experiments.
