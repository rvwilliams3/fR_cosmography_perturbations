# f(R) Gravity Honours Project

## Project overview
Dynamical systems and perturbation analysis in cosmographic f(R) gravity.
Using 4 models of j(z)=j(q(z)) to close the system.
Numerical and symbolic computation in Mathematica.

## Repo structure
- `Phase space analysis.nb` — Analysis of background dynamics: phase portraits, 3-variable dynamical system
- `Solving Background.nb` — Solving the backgrodun dynamical system (model-independent for general f(R) gravity). Initial conditions taken at z0=6, integrated forward to today at z=0 and backward to zintiial=2000 
- `Perturbations QS.nb` — Quasi-static perturbation analysis for model-independent f(R). Uses corresponding model's background evolution saved as .mx file. From the rate of growth function, determine the growth index approximation f=(Omega_matter)^\gamma. In f(R) Omega=Omega_matter/f_R, but the eneergy condition still holds for normal matter.

## Key functions
- `PhasePortrait[...]` — plots trajectories in the dynamical system phase space
- `SolveBackground[model, ...]` — modular solver, takes j[z] as input, supports bidirectional integration

## Dependencies
- Mathematica (xAct/xTensor for symbolic GR)

## Conventions
- Redshift z is the primary independent variable

## Notes for editing
- Prefer minimal, targeted changes — avoid large refactors
- Do not modify cell structure or output cells in notebooks unless asked
