## Integrate Steps

- run `pnpm init`
- add `pnpm-workspace.yaml` file
- creae `backend/` & `frontend/`
- shared common lib
  - add `shared-lib/` in `packages/`
  - excute `npm install --save ../../packages/shared-lib` in `backend` or `frontend` directory
- multiple projects share dependency packages
