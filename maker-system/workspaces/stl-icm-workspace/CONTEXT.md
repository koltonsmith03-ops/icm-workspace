# CONTEXT.md — STL Workspace Stage Router

## Stages (in order)

| Stage | Folder | Job |
|-------|--------|-----|
| 01 | `stages/01-intent-spec/` | Turn the user request into a clear, structured intent + specification |
| 02 | `stages/02-geometry-description/` | Describe the geometry in precise, unambiguous language (no code yet) |
| 03 | `stages/03-code-generation/` | Write clean, well-commented OpenSCAD code |
| 04 | `stages/04-validation/` | Check for common problems, manifold issues, missing dimensions, etc. |
| 05 | `stages/05-export-notes/` | Produce final notes, suggested export settings, and any open questions |

## How to run a stage

1. Enter the stage folder.
2. Read that stage’s `CONTEXT.md` (the contract).
3. Load only the inputs listed in the contract.
4. Do the work.
5. Write the required outputs into the stage’s `output/` folder.
6. Stop and wait for human review unless the user has explicitly said to continue.

## Starting point
- New part → begin at stage 01.
- User provides an existing OpenSCAD file or previous output → jump to the appropriate stage and note it.
- Always prefer going through the stages rather than doing everything in one shot.
