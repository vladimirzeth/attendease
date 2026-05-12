# AttendEase 📋
> Smart Attendance Tracker for Teachers

A mobile-friendly, offline-capable attendance tracking app built as a single HTML file. No installation required — just open the link in any browser.

## Features
- ✅ Take attendance with a flashcard-style UI
- 🏫 Manage multiple sections and students
- 📊 Track absences with warning and critical alerts
- 📥 Import students from Excel (.xlsx)
- 📤 Export attendance records and absence summaries to Excel
- 🔒 Google Sign-In — each teacher's data is private and isolated
- ☁️ Google Sheets sync (coming soon)
- 📱 Works offline — install to home screen like an app

## How to Use
1. Open the app link in your browser
2. Sign in with your Google account
3. Add your sections and students (or import from Excel)
4. Tap "Take Attendance" to start a session
5. Mark each student Present, Absent, or Excused

## For Teachers
No account registration needed. Just sign in with your existing Google account. Your data is yours — no other teacher can see it.

## Tech Stack
- Vanilla HTML / CSS / JavaScript
- Google Identity Services (OAuth 2.0)
- SheetJS (Excel import/export)
- localStorage (offline storage)
- Google Sheets API (sync — coming in Stage 3)

## Roadmap
- [x] Stage 1 — Core app (flashcard UI, offline storage, Excel import/export)
- [x] Stage 2 — Google Login + data isolation
- [ ] Stage 3 — Google Sheets sync
- [ ] Stage 4 — n8n + Telegram alerts for high-absence students

## Developer
Built for Philippine school use. Absence thresholds follow standard policy (Warning: 3+, Critical: 9+, Dropped: 10+).
