# Codex Working Rules

This repository is the default shared workspace for the user.

## Default Behavior

- Treat `nistulgrow/thewall_skills` as the shared GitHub hub for future work in this workspace.
- When the user asks to start, build, draft, test, or continue a project without naming another location, create or update it under `projects/<project-name>/`.
- Do not create new standalone local-only project folders outside this repository unless the user explicitly asks.
- Keep cross-device continuity files updated:
  - `PROJECTS.md` for the project index.
  - `NOTES.md` for the latest handoff context.
  - `projects/<project-name>/notes.md` for project-specific context.
- At the end of meaningful work, prepare changes to be committed and pushed to GitHub when permissions allow.

## New Project Checklist

1. Create `projects/<project-name>/`.
2. Add `projects/<project-name>/README.md`.
3. Add `projects/<project-name>/notes.md`.
4. Add or update the matching row in `PROJECTS.md`.
5. Update `NOTES.md` with the latest status and next step.

## Naming

- Use lowercase kebab-case for project folders, such as `projects/customer-dashboard`.
- If the user gives a Korean project name, choose a short English kebab-case folder name and keep the Korean display name in README/PROJECTS.

## Safety

- Never commit secrets, API keys, private company documents, or customer data.
- Use `.env.example` for example environment variables and keep real `.env` files ignored.
