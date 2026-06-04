# Spendlens — Personal Expense Tracker
A clean, dark-themed expense tracker web app built with vanilla HTML, CSS and JavaScript. Supports Google Sign-In, cloud sync across devices, budget tracking, and spending trends.
## Live demo: https://expensetracker-spendlenss.netlify.app/

## Features
- Google Sign-In — login with your Google account, no password needed
- Cloud sync — data stored in Supabase, syncs across all your devices
- Monthly tracking — navigate between months, every month stored separately
- Budget limits — set per-category limits with live progress bars
- Charts — donut chart, bar chart, 6-month trend line, payment mode split
- CSV export — download any month's data as a spreadsheet
- Full CRUD — add, edit, delete any expense
- Category management — create custom categories with a color picker
- Filters — filter entries by category or payment mode
## Tech Stack
- Frontend: HTML, CSS, JavaScript (no framework)
- Charts: Chart.js v4
- Auth: SupabaseAuth (Google OAuth)
- Database: Supabase (Postgres)
- Hosting: Netlify

## Local Setup
- This app uses Google OAuth which requires a live URL. 
- You cannot open it directly as a file:/// in the browser
— Google will block the login popup.
## Option 1 — Netlify Drop (easiest)
- Rename expense-tracker.html to index.html
- Go to app.netlify.com/drop
- Drag and drop the file
- Use the generated URL
## Option 2 — Local server
-bashnpx serve: .
- open http://localhost:3000
- Then add localhost:3000 to your Supabase redirect URLs.
