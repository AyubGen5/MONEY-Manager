# MONEY-Manager

Having a disadvantaged background financially leads a lot of us into borrowing hoping our lives would be better. This project aims to help you understand and manage money with tools for importing transactions, simple analysis, and advisor suggestions.

Owner: Ayub Ndede Hamisi

This repo is the starter workspace for the MONEY-Manager app. It contains:

- `backend/` — Node adapter, SQLite persistence, and JacLang placeholders (analysis helper included).
- `frontend/` — Vite + React (TypeScript) frontend with CSV import and advisor view.

Quick start (recommended - using npm workspaces):

PowerShell (Windows):

```powershell
# From repository root: install dependencies for workspace and packages
npm run bootstrap

# Start both services (backend on port 4000 and frontend dev on port 5173)
npm start
```

Or run individually:

```powershell
cd backend
npm install
npm start

# In another terminal
cd frontend
npm install
npm run dev
```

Notes:
- The repository uses npm workspaces. The root `package.json` defines `frontend` and `backend` as workspaces and includes convenience scripts.
- The backend provides a local analysis helper at `backend/jac/run_analysis.js` used by default; if you have a JacLang runtime you can implement `backend/jac/finance.jac` and the adapter will try to call your `jac` CLI. Set `JAC_CMD` environment variable if your jac binary differs from `jac`.

If you want, I can add Dockerfiles and a `docker-compose.yml` to run both services in containers.
# MONEY-Manager
Having a disadvantaged background financially leads a lot of us in to borrowing hoping our lives would be better. A number of instances never achieve this change thereby more and more challenges are invited into our lives as we borrow more to achieve this DREAM of changing our lives. True to my DREAM of CHANGE This will change your LIFE.
Owner: Ayub Ndede Hamisi
This is the default owner of everything in this repo
 unless a  later change of ownership occurs.
@AyubGen5 or/and Ayub Ndede Hamisi will  be requested for
review incase someone opens a pull request.
The owner acknowlenges that this repo is and remains 
open source
