# Prompt: Create DEFORM / FEA Setup

Use this prompt to generate a DEFORM-ready or FEA-ready forming simulation plan.

```text
Act as a metal-forming simulation engineer. Create a DEFORM-ready setup for the 8 mm steel lockbolt collar tooling process.

Process:
- Machine: 14B nut former
- Analysis type: 2D axisymmetric cold forming
- Billet: Ø11.80 mm low-carbon steel, 0.15%C max, annealed/spheroidized
- Tools: rigid die inserts, punches, and KO pins
- Friction: shear friction m = 0.08–0.12
- Remeshing: enabled every operation

Final geometry:
- OD target = Ø10.25 mm
- OD J max = Ø10.31 mm
- Length target = 8.06 mm
- Length K max = 8.13 mm
- Functional bore = Ø8.50 mm
- Die IV = Ø10.25 × 8.06 final land
- Punch IV = Ø8.50 working land
- KO Pin IV = Ø8.40 face, eject only

Generate:
1. Operation chain for four stations.
2. Stage output table with length, OD, bore, and purpose.
3. DEFORM object definitions: billet, die, punch, KO pin.
4. Contact/friction settings.
5. Mesh/refinement/remesh settings.
6. Material model requirement and flow-stress note.
7. Post-processing outputs: effective strain, effective stress, damage, contact pressure, load-stroke.
8. Acceptance criteria for OD, length, bore, no fold/lap, and no excessive damage.
9. Explain clearly whether the output is a real native DEFORM solve or only a DEFORM-ready setup.
```
