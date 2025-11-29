# N E B U L Δ ™ - Dashboard & Website

This is the official frontend codebase for N E B U L Δ ™.

## 🚀 Deployment to Vercel

This project is configured for easy deployment on Vercel.

### Steps to Deploy:

1.  **Upload to GitHub**:
    *   Push this entire repository to a new GitHub repository.

2.  **Import to Vercel**:
    *   Go to [Vercel.com](https://vercel.com) and sign in.
    *   Click **"Add New..."** -> **"Project"**.
    *   Import your GitHub repository.

3.  **Configuration (Should be automatic)**:
    *   Vercel should detect the `vercel.json` file included in this project.
    *   **Framework Preset**: Vite
    *   **Build Command**: `npx vite build` (handled by vercel.json)
    *   **Output Directory**: `dist/public` (handled by vercel.json)

4.  **Deploy**:
    *   Click **"Deploy"**.

## 🛠️ Local Development

To run this project locally:

1.  Install dependencies:
    ```bash
    npm install
    ```

2.  Start the development server:
    ```bash
    npm run dev:client
    ```

3.  Open `http://localhost:5000` in your browser.

## 📂 Project Structure

*   `client/` - Contains all frontend code (React, Pages, Components).
*   `client/src/components/` - Reusable UI components.
*   `client/src/pages/` - Route pages (Home, Dashboard).
*   `vercel.json` - Configuration for Vercel deployment.
