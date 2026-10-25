# Sunny Benrath — Shift Planner UI Prototype

## Files
- `index.html`: landing page, choose Manager or Employee, enter demo code
- `manager.html`: manager scheduling UI
- `member.html`: employee schedule and team monthly overview
- `assets/`: optional future images, logo, icons (not needed yet)

## Demo codes
- Manager: `2468`
- Employees: `1001`, `1002`, `1003`, `1004`

## Deploy
Upload the contents of this folder to the **root** of a GitHub repository. For Netlify, import the GitHub repository and use the repository root as publish directory (`.`); no build command is needed.

## Important
This is a **UI prototype**, not secure authentication. Demo codes and access checks run in browser JavaScript. The browser's `localStorage` holds schedule data and does not sync across devices. Do not use real employee data or rely on deactivation to protect access until a backend is connected.

EN/DE switching is currently implemented on the landing page. The manager and employee dashboards still need complete translation.
