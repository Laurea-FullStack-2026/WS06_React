# WS06 - React (Built on REST API Week)

This repository continues from the previous REST API topic.  
Goal: keep the backend stable and teach React step-by-step on top of that API.

## Target Repository Structure

```text
WS06_React/
├─ README.md
├─ requirements.md
├─ docs/
│  ├─ week-overview.md
│  ├─ assignment.md
│  ├─ grading-rubric.md
│  └─ setup.md
├─ backend/
│  ├─ package.json
│  ├─ server.js
│  ├─ models/
│  ├─ routes/
│  └─ public/
├─ frontend/
│  ├─ starter/
│  │  ├─ package.json
│  │  ├─ src/
│  │  └─ public/
│  └─ solution/
│     ├─ package.json
│     ├─ src/
│     └─ public/
├─ exercises/
│  ├─ 01_components/
│  ├─ 02_props_state/
│  ├─ 03_effects_and_fetch/
│  ├─ 04_forms/
│  ├─ 05_routing/
│  └─ 06_api_integration/
├─ shared/
│  ├─ postman/
│  ├─ seed/
│  └─ examples/
└─ archive/
   └─ rest-api-week/
```

## Concrete Mapping from Current Folders

- `starter/` → `backend/`
  - Use as the baseline backend for React integration.
- `Solution/` → `archive/rest-api-week/solution-backend/`
  - Keep as teacher reference from REST week.
- `tuntiharjoitukset/` → `archive/rest-api-week/tuntiharjoitukset/`
  - Preserve exercise history, do not mix with new React flow.
- Current root docs:
  - `requirements.md` → keep at root for continuity OR copy to `docs/assignment.md`.

## Suggested Migration Order

1. Create new top-level folders (`docs`, `frontend`, `exercises`, `shared`, `archive`).
2. Move current `starter/` into `backend/`.
3. Move `Solution/` and `tuntiharjoitukset/` under `archive/rest-api-week/`.
4. Scaffold `frontend/starter` and `frontend/solution` React apps.
5. Add weekly React tasks under `exercises/`.
6. Update docs in `docs/` and keep this root README as navigation.

## Teaching Flow (WS06)

- Keep backend API contract unchanged (`/api/posts`).
- Teach React in increments:
  1. Components and JSX
  2. Props and state
  3. `useEffect` + fetching data
  4. Controlled forms
  5. Client routing
  6. Full CRUD integration with backend

## Minimal Run Conventions

- Backend: run inside `backend/`.
- Frontend starter: run inside `frontend/starter/`.
- Frontend solution: run inside `frontend/solution/`.

Keep student work in starter folders only; solution folders are teacher/reference material.