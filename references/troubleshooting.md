# Troubleshooting

Use this reference for rotary cup and electrostatic powder coating defect diagnosis. Treat these as field-oriented starting points; confirm site conditions before giving final conclusions.

## Low Powder Deposition

Likely causes:

- Poor grounding of the workpiece, hanger, conveyor, or booth.
- Voltage too low or current limit too restrictive.
- Gun-to-part distance too far.
- Powder feed too low or unstable.
- Powder fluidization is poor.
- Workpiece geometry blocks the powder cloud.
- Powder is damp, aged, contaminated, or has poor chargeability.

Checks:

- Measure grounding resistance from workpiece to earth.
- Check hanger contact points for paint buildup.
- Confirm powder fluidization is even, not bubbling violently or channeling.
- Compare deposition on a simple test panel.
- Check whether the issue is all over the part or only in recessed/edge areas.

Adjustment logic:

- Restore grounding before increasing voltage.
- Reduce distance if the powder cloud is weak at the part.
- Increase powder feed gradually.
- Tune electrostatic settings only after mechanical powder delivery is stable.

## Uneven Film Thickness

Likely causes:

- Line speed and spray pattern do not match.
- Cup-to-part distance changes too much along the part.
- Cup speed or powder feed is unstable.
- Reciprocator/robot path is not covering the part evenly.
- Workpiece shape creates Faraday cage or shielding areas.

Checks:

- Measure film thickness at top, bottom, edge, flat face, recess, and backside.
- Check whether the pattern repeats with the conveyor pitch or hanger spacing.
- Confirm the rotary cup is clean and balanced.

Adjustment logic:

- Tune motion path before making large electrical changes.
- Adjust powder feed and cup speed in small steps.
- Use film thickness mapping to identify whether the problem is motion, distance, electrostatic effect, or powder delivery.

## Poor Edge Coverage

Likely causes:

- Powder cloud is not wrapping around the edge.
- Distance is too far or spray direction is poor.
- Electrostatic field is not strong enough at the edge.
- Grounding is weak.
- Line speed is too fast for edge build.

Checks:

- Compare inner corners, outer edges, and flat surfaces.
- Verify part grounding and hanger cleanliness.
- Check whether the same issue happens on different part shapes.

Adjustment logic:

- Improve grounding first.
- Adjust position and angle so the powder cloud reaches the edge.
- Reduce line speed or add pass time if production allows.
- Tune voltage/current and powder output after the mechanical coverage is correct.

## Orange Peel

Likely causes:

- Film is too thick or uneven.
- Powder flow and curing window do not match.
- Substrate temperature or oven profile is wrong.
- Powder quality or storage condition is poor.
- Surface pretreatment is inconsistent.

Checks:

- Measure film thickness before changing spraying equipment.
- Review oven temperature profile with the actual part temperature.
- Compare with a fresh powder batch.

Adjustment logic:

- Bring film thickness into the powder supplier's recommended range.
- Confirm curing before blaming the spray head.
- Reduce heavy build areas by adjusting powder feed, path, or line speed.

## Pinholes

Likely causes:

- Surface contamination, oil, moisture, or poor pretreatment.
- Outgassing from casting, galvanized part, or porous substrate.
- Powder or compressed air contains moisture.
- Film is too thick.
- Cure ramp is too aggressive for the substrate.

Checks:

- Inspect pretreatment and drying.
- Check compressed air drying and powder storage.
- Compare with test panels and known clean parts.

Adjustment logic:

- Fix contamination and moisture first.
- Reduce excessive film thickness.
- Consider preheating or adjusted curing for outgassing parts.

## Unstable Powder Output

Likely causes:

- Powder pump or injector is worn.
- Powder hose is blocked, kinked, too long, or poorly routed.
- Fluidizing air is unstable.
- Powder level in hopper changes too much.
- Rotary cup is contaminated or mechanically unstable.

Checks:

- Watch powder cloud stability with electrostatics off, then on.
- Inspect pump, venturi, hose, cup edge, and air supply.
- Confirm stable air pressure and dry compressed air.

Adjustment logic:

- Stabilize powder delivery before tuning electrostatic parameters.
- Clean or replace worn powder delivery parts.
- Keep powder hose routing smooth and consistent.
