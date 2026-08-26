# Stage 05 — Export & Notes

## Inputs
- Validated (or accepted) OpenSCAD file from stage 03 or 04
- All previous stage outputs as needed
- User’s final decisions

## Process
1. Confirm the model is ready for export.
2. Produce practical notes for the user:
   - How to export STL / 3MF from OpenSCAD
   - Any suggested orientation or support considerations (general, not printer-specific)
   - Open questions that still remain
   - Where the key parametric values live if the user wants to tweak them later
3. Keep the printer profile blank. Do not invent slicer settings.

## Outputs
Write to `output/`:

- `export-notes.md` — Final practical guidance and remaining open items.
- Copy or link to the final `.scad` file if helpful.

## Checkpoint
This is the end of the normal pipeline. Summarize what was delivered and what (if anything) is still unresolved.
