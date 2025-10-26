# LawVriksh - Deployable version

This is a minimal Vite + React + Tailwind project prepared to be a drop-in replacement if your original repo had build errors.
It uses `index.html` with a relative import (`./src/main.jsx`) to avoid the Rollup unresolved import issue on Vercel.

## To use locally
1. Install dependencies:
   ```
   npm install
   ```
2. Run dev:
   ```
   npm run dev
   ```
3. Build:
   ```
   npm run build
   ```

## Deploying to Vercel
- In Vercel set the Root to the project root (default).
- Build Command: `npm run build` (or `vite build`)
- Output Directory: `dist`

Replace files in your repository with these files (or merge) and push to GitHub, then redeploy on Vercel.

