# Jaya Maurya — Portfolio Website

A responsive React + Vite personal portfolio starter for Jaya Maurya, combining web development and data analytics experience from the supplied resumes.

## Run locally

1. Install Node.js (LTS recommended).
2. Extract this ZIP and open a terminal in the `Jaya_Portfolio` folder.
3. Run:

   ```bash
   npm install
   npm run dev
   ```

4. Open the local URL printed by Vite (usually `http://localhost:5173`).

## Before publishing

- Put the resume PDF you want to share in `public/` and name it `resume.pdf`. The Download Resume button points to `/resume.pdf`.
- In `src/main.jsx`, replace `#` placeholders for project GitHub/live-demo links with verified URLs.
- Check your public email and social profile links before deployment.
- The GPA is intentionally omitted because the supplied resumes show different values.
- Project cards use CSS illustrations instead of invented screenshots.

## Build

```bash
npm run build
npm run preview
```

## Deploy to Vercel

Push this folder to a GitHub repository, import the repository in Vercel, and use the default Vite settings. Build command: `npm run build`; output directory: `dist`.
