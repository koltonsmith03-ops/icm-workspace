# Stage 01 — Intent & Specification

## Inputs
- User’s natural language request (current conversation)
- Any previous notes the user provides
- Root and workspace AGENTS.md rules (already loaded)

## Process
1. Extract the core intent: what physical object is being requested and why.
2. List all explicitly stated requirements (dimensions, features, constraints).
3. List all missing but necessary information as open questions.
4. Produce a clean, structured specification that stage 02 can use without guessing.

## Outputs
Write these files into `output/`:

- `intent.md` — Short plain-language summary of what we are building and why.
- `spec.md` — Structured requirements + open questions. Use clear headings and bullet points. Never invent values.

## Checkpoint
Stop after writing the files. Present a brief summary and the open questions to the user before moving to stage 02.
