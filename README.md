# Pratibha — GenAI Engineer Portfolio

A responsive, single-page portfolio built with plain HTML, CSS, and JavaScript. It has no build step, package manager, backend, or external JavaScript dependencies.

## Files

- `index.html` — page structure and portfolio content.
- `styles.css` — responsive layout, colors, and visual styling.
- `script.js` — mobile navigation behavior and dynamic footer year.
- `.gitignore` — excludes common local/editor files and environment secrets.

## Run locally in VS Code

1. Extract this folder if you downloaded the ZIP.
2. Open the folder in VS Code (`File → Open Folder`).
3. Open `index.html` in a browser.
4. Optional: install the **Live Server** extension, right-click `index.html`, and choose **Open with Live Server**.

## Publish using GitHub Pages

1. Create a **public** repository on GitHub named exactly `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
2. Open this project folder in VS Code.
3. Open VS Code's integrated terminal (`Terminal → New Terminal`) and run:

   ```bash
   git init
   git add .
   git commit -m "Add GenAI portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-USERNAME.github.io.git
   git push -u origin main
   ```

   Replace both occurrences of `YOUR-USERNAME` in the remote URL. If Git asks you to sign in, complete the browser authentication flow. If the repository already contains files or already has a Git remote, do not blindly repeat the initialization/remote commands; check `git status` and `git remote -v` first.

4. On GitHub, open your repository → **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, then click **Save**.
6. After deployment finishes, visit `https://YOUR-USERNAME.github.io/`.

Official instructions: https://docs.github.com/en/pages/quickstart

## Before publishing

- Check that the email and LinkedIn URLs are correct and that you want them publicly visible.
- Verify project metrics and make sure client/project descriptions are approved for public sharing.
- Do not commit API keys, `.env` files, customer documents, private screenshots, or confidential source code.
- This is a static website. It does not host or run a Python/FastAPI backend; link to separately hosted demos only when they are safe and approved to share.
