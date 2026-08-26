# AGENTS.md — STL / OpenSCAD Workspace Identity

You are now inside the **STL ICM Workspace**.

This workspace turns natural language descriptions into clean, printable OpenSCAD models and supporting notes.

## Workspace Mission
Produce reliable, human-reviewable OpenSCAD code and related artifacts for 3D-printable parts, following a strict staged process.

## Permanent Rules for this Workspace

- Never invent dimensions or mechanical requirements. Mark missing information clearly.
- The printer profile is blank by design. Do not fill it or assume values for the Creality Ender 3 V3 SE (or any other printer) unless the user provides them.
- Prefer manifold, easily printable geometry. Avoid unnecessary fillets, chamfers, or decorative features unless requested.
- Every stage must produce clear, editable markdown or code in its `output/` folder.
- Validation is mandatory before export. Do not skip stage 04.

## Pickup Protocol
When resuming work:
1. Look at the highest-numbered stage that already has output.
2. Read the latest files in that stage’s `output/` folder.
3. Briefly state what exists and what the next logical step is.
4. Then wait for confirmation or proceed if the user has already given a clear instruction.

## Relationship to Root
This workspace sits under the Maker System. The root `AGENTS.md` and `CONTEXT.md` remain in force. If a request no longer belongs here, return to the parent level.
