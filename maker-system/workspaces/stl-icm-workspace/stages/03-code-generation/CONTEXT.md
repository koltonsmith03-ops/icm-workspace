# Stage 03 — OpenSCAD Code Generation

## Inputs
- `../02-geometry-description/output/geometry.md`
- `../01-intent-spec/output/spec.md` (for any remaining constraints)
- OpenSCAD conventions in `../../references/` (if present)

## Process
1. Write clean, well-commented OpenSCAD code that implements the geometry description.
2. Use modules for major features.
3. Prefer parametric style where it makes sense, but do not invent parameters the user did not request.
4. Keep the code readable and easy for a human to edit later.
5. Do not add decorative features or fillets unless they were specified.

## Outputs
Write to `output/`:

- `main.scad` — The complete OpenSCAD model.
- `notes.md` — Short explanation of structure, any assumptions that were forced by missing data, and how to adjust key values.

## Checkpoint
Stop after writing the files. Offer to explain any part of the code or make adjustments before validation.
