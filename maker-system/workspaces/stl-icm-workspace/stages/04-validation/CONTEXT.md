# Stage 04 — Validation

## Inputs
- `../03-code-generation/output/main.scad`
- `../03-code-generation/output/notes.md`
- `../02-geometry-description/output/geometry.md`
- `../01-intent-spec/output/spec.md`

## Process
1. Review the OpenSCAD code against the geometry description and original spec.
2. Check for:
   - Missing or invented dimensions
   - Non-manifold risks (if detectable from code)
   - Overly thin walls or features that will be hard to print (flag only, do not assume printer settings)
   - Code clarity and modularity issues
3. List concrete problems and suggested fixes.
4. Do **not** silently rewrite the model unless the user has already approved changes.

## Outputs
Write to `output/`:

- `validation-report.md` — Clear list of issues found, severity, and recommended actions.
- (Optional) `main-fixed.scad` only if the user has asked you to apply fixes in this stage.

## Checkpoint
Present the validation report. Wait for the user to decide whether to fix issues, accept as-is, or go back to an earlier stage.
