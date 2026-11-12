# WardTrack

Single-file prototype (HTML, CSS, vanilla JS) for a virus quarantine and treatment centre.
Roles: Nurse, Doctor, Admin staff. Runs on sample data for 74 beds. No build step, no dependencies.

## Run locally
Open `index.html` in a browser.

## Deploy to Vercel
1. Put this folder in a new Vercel project (drag and drop, or `vercel` from this folder).
2. Framework preset: Other. No build command. Output directory: `.`

## Demo path
1. Nurse: search B13, record 37.1.
2. Doctor: open B13, Save and recommend discharge.
3. Admin: Discharges, discharge B13, then Admit a patient.
4. Admin dashboard: Start next day to replay the cycle.

Demo state is stored in the browser's localStorage. Use "Reset sample data" on the admin dashboard to restore it.
