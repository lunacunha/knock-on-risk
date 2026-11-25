# Decisions

Each entry records a decision, the alternatives considered and the reason.

## D001 · Repository visibility
- **Decision:** Public from the start.
- **Alternatives:** Private until the end of Phase 0, then public.
- **Reason:** The commit history shows the real process over time. Raw interview notes are never stored in the repository, only anonymised versions.

## D002 · Folder structure
- **Decision:** Create each folder only when a phase needs it.
- **Alternatives:** Create the full structure from the plan at the start.
- **Reason:** Git does not track empty folders, and the repository should reflect the actual state of the project.

## D003 · License
- **Decision:** Postponed to Phase 6.
- **Alternatives:** MIT now; no license.
- **Reason:** Not needed while the project is in early stages. Default copyright applies until a license is added.

## D004 · Main language
- **Decision:** Python and SQL for now. Revisit a TypeScript frontend in Phase 6 or 7.
- **Alternatives:** TypeScript frontend from Phase 6; no TypeScript at all.
- **Reason:** All planned libraries are Python. A single language keeps the scope small until the core product works. A custom frontend adds little for the target roles (AI, risk, BA), so it is only worth it if time allows.

## D005 · Naming
- **Decision:** Product name "Knock-on", repository name `knock-on-risk`.
- **Alternatives:** Same name for both (`knock-on`).
- **Reason:** The repository name shows the topic in the GitHub repository list. The README title uses the product name.