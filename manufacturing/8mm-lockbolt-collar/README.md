# 8 mm Lockbolt Collar — Engineering Prompt Pack

Prompt templates for designing, checking, and simulating an 8 mm steel lockbolt collar tooling stack for a 14B nut former.

## Corrected final geometry

- Collar OD target: Ø10.25 mm
- Collar OD limit: J max Ø10.31 mm
- Collar length target: 8.06 mm
- Collar length limit: K max 8.13 mm
- Functional bore: Ø8.50 mm
- Nominal pin: Ø8.00 mm
- Die Insert IV: Ø10.25 × 8.06 final land
- Punch IV: Ø8.50 working land
- Punch IV small nose: Ø7.80 / Ø7.75 lead-relief only
- KO Pin IV: Ø8.40 face, eject only

## Prompt files

- `01-tooling-review.md` — review hand sketches, collar geometry, and machine fit.
- `02-die-cavity-design.md` — generate die insert cavity sequence I–IV.
- `03-punch-ko-pin-design.md` — generate punch and kick-out pin geometry.
- `04-deform-fea-setup.md` — create a DEFORM-ready forming simulation plan.
- `05-output-checklist.md` — final part inspection and tooling acceptance checklist.

## Important modeling note

A visual or surrogate FEA is not a substitute for a native nonlinear elastoplastic contact solve in DEFORM, Forge, Simufact, or Abaqus/Explicit. Use these prompts to define the engineering problem, geometry, process chain, checks, and post-processing outputs before production tooling release.
