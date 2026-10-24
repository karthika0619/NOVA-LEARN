# NOVA Learn — Frontend starter

A responsive React + TypeScript frontend prototype for NOVA Learn. It includes:
- Student overview dashboard
- Course cards and course search
- AI Teacher class checklist and a demo quiz interaction
- Learning Twin mastery profile and recommendations
- Study analytics charts with Recharts
- Instructor and administrator dashboard mock-ups

## Requirements
- Node.js 18+ (Node.js 20+ recommended)
- npm

## Run locally
1. Extract the ZIP file.
2. Open a terminal in the `nova-learn-frontend` folder.
3. Install packages:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL shown by Vite (usually `http://localhost:5173`).

## Build
```bash
npm run build
```

## Important
This is frontend-only starter code. It uses local sample data and demo interactions. It does not yet connect to a Node.js/Express API or PostgreSQL database. Authentication, role-based access, persistent progress, secure server-side quiz evaluation, and real AI/LLM responses must be implemented and connected in the backend before production use. Charts and example student data are illustrative only.
