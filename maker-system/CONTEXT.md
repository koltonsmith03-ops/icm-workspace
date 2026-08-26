# CONTEXT.md — Maker System Router

## Purpose
This file is the top-level map. It tells you which workspace to enter for a given request.

## Available Workspaces

| Request type | Go to this workspace | Notes |
|--------------|----------------------|-------|
| 3D printable parts, OpenSCAD, geometry, STL, mesh validation, phone stands, enclosures, brackets, etc. | `workspaces/stl-icm-workspace/` | Main and currently only workspace |
| Anything else | Stay here / refuse | Do not invent new workspaces or leave the Maker System |

## How to enter a workspace

1. Confirm the request belongs to the STL workspace using the table above.
2. Change into `workspaces/stl-icm-workspace/`.
3. Immediately read that workspace’s own `AGENTS.md` and then its `CONTEXT.md`.
4. Follow the stage contracts from there.

## If the request is unclear
Ask one clarifying question, or return to the root `AGENTS.md` and state that the request does not clearly map to the available workspace.
