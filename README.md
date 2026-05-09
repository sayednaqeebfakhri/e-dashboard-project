# e-dashboard-project

This repository contains a full-stack e-dashboard application with separate `backend` and `front-end` folders.

## Project structure

- `backend/`
  - Node.js backend server
  - `index.js` - main server entrypoint
  - `db/` - database models and configuration
  - `package.json` / `package-lock.json` - backend dependencies and scripts

- `front-end/`
  - React application
  - `public/` - static assets and HTML entrypoint
  - `src/` - React source files and components
  - `package.json` / `package-lock.json` - front-end dependencies and scripts

## Notes

- `backend/node_modules/` is excluded from the repository via `.gitignore`
- Run `npm install` separately in both `backend/` and `front-end/` before starting the app

## Usage

1. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```
2. Install frontend dependencies:
   ```bash
   cd ../front-end
   npm install
   ```
3. Start the backend server:
   ```bash
   cd ../backend
   npm start
   ```
4. Start the frontend app:
   ```bash
   cd ../front-end
   npm start
   ```

## Repository

Uploaded to: `https://github.com/sayednaqeebfakhri/e-dashboard-project.git`
