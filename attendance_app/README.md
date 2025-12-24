# Attendance App – Contribution Guide

This folder contains a simple attendance tracker with a vanilla HTML frontend (`index.html`) and an Express/MongoDB backend (`server.js`). Follow these steps to set up the project locally and contribute changes.

## Prerequisites
- Node.js and npm installed
- Local MongoDB instance running at `mongodb://localhost:27017/attendance`

## Run the app locally
1. Install backend dependencies (from this folder):
   ```bash
   npm install express cors mongoose
   ```
2. Start the backend API:
   ```bash
   node server.js
   ```
3. Open `index.html` in your browser (or via a simple static server/Live Server extension). The page expects the API at `http://localhost:3000`.

## How to contribute
1. Fork this repository and create a feature branch (e.g., `feat/fix-attendance`).
2. Make your changes to `attendance_app/` (frontend or backend).
3. Manually verify your change by:
   - Starting MongoDB and `node server.js`
   - Opening `index.html` and exercising the change end-to-end
4. Ensure any new endpoints or UI behavior are documented in this README.
5. Commit your changes and open a Pull Request describing:
   - What you changed
   - How you tested (steps in #3)

Thank you for improving the attendance app!
