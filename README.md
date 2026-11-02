# ELITE — Student & Teacher Mobile Web App
### The Academy Of Elite Karachi
*Powered by The Code Legends*

---

## 🌟 Overview
ELITE is a mobile-first Progressive Web Application (PWA) designed for students and faculty of **The Academy Of Elite Karachi**. It connects to the academy's live Supabase backend and is optimized for hosting on **GitHub Pages**.

- **Student Portal:** Personalized Dashboard, Real-time Attendance, Upcoming Examinations & Live Countdowns, Published Results & Report Cards, Academic Progress Analytics, Homework Submissions, Academy Announcements.
- **Teacher Portal:** Faculty Dashboard, Assigned Class Cohorts & Rosters, Attendance Marking, Examination Marks Entry & Auto-Grading, Homework Creation & Reviews, Administrative Notices.

---

## 🚀 Quick Start (Local Development)

```bash
# 1. Navigate to the project directory
cd "D:\Elite\Elit App"

# 2. Start Vite local development server
npm run dev
```

Visit the displayed local server URL (e.g. `http://localhost:5173`) in your browser or mobile emulator.

---

## 📱 GitHub Pages Deployment

This project is configured out-of-the-box for GitHub Pages:
1. Initialize Git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of ELITE Student & Teacher App"
   ```
2. Create a repository on GitHub (e.g., `elite-app`) and push:
   ```bash
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git branch -M main
   git push -u origin main
   ```
3. In GitHub Repository Settings -> **Pages**:
   - Source: **GitHub Actions**
   - The `.github/workflows/deploy.yml` workflow will automatically build and publish your app.

---

## 🔑 Authentication Handles
- **Students:** Can log in using either their **Registration No** (e.g. `ELT-2026-0002`) or their email and password.
- **Teachers:** Can log in using their **Faculty ID** (e.g. `EMP-2026-01`) or their email and password.
- **One-Click Quick Login:** Preset quick-login buttons on the login screen for testing.

