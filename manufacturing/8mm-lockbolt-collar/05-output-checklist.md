# Prompt: Final Output Checklist

Use this prompt to inspect whether the produced collar and tooling stack are acceptable.

```text
Act as a tooling validation engineer. Create a final output checklist for the 8 mm steel lockbolt collar made on a 14B nut former.

Known limits:
- OD J max = Ø10.31 mm
- Length K max = 8.13 mm
- Target OD = Ø10.25 mm
- Target length = 8.06 mm
- Functional bore = Ø8.50 mm
- Nominal pin = Ø8.00 mm
- Material = low-carbon steel, 0.15%C max

Check the trial samples for:
1. Outside diameter.
2. Collar length.
3. Bore diameter and taper.
4. Wall thickness uniformity.
5. Concentricity/runout.
6. Front taper and back face quality.
7. Lap/fold at the nose and bore corner.
8. Surface galling or tool pickup.
9. Plating allowance if zinc plated.
10. Swage/lock test on actual 8 mm lockbolt pin.

Also create adjustment rules:
- If OD is oversize, adjust Die IV land.
- If bore is oversize/undersize, adjust Punch IV, not KO Pin IV.
- If bore is bell-mouthed, check KO Pin IV face and ejection stroke.
- If collar is short/long, adjust shut height/cut-off volume.
- If cracks/damage occur, check material anneal, lubrication, radius, and reduction schedule.

Return a pass/fail table and recommended next action.
```
