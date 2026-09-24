# Sanjay Shinde — Portfolio Website

A modern, single-page portfolio for **Sanjay Shinde**, Salesforce Success Architect.
Built as a single self-contained `index.html` (no build step, no dependencies) — just open it or host it anywhere.

## ✨ Features
- Animated aurora background + subtle grid
- Scroll-reveal animations and animated stat counters
- Responsive layout (mobile → desktop)
- Sections: Hero, Expertise, Experience timeline, Certifications, Contact
- Salesforce-inspired color system

## 🚀 Publish to GitHub Pages

1. **Create a repo** on GitHub. To get a URL like `https://<username>.github.io`,
   name it exactly `<username>.github.io`. Any other name works too — it will live at
   `https://<username>.github.io/<repo-name>/`.

2. **Push these files:**
   ```bash
   cd sanjay-portfolio
   git init
   git add .
   git commit -m "Add portfolio website"
   git branch -M main
   git remote add origin https://github.com/<username>/<repo-name>.git
   git push -u origin main
   ```

3. **Enable Pages:** In the repo, go to **Settings → Pages → Build and deployment**,
   set **Source = Deploy from a branch**, **Branch = `main`**, **Folder = `/ (root)`**, then **Save**.

4. Wait ~1 minute. Your site will be live at the URL shown on that Pages screen. 🎉

## ✏️ Editing
Everything lives in `index.html`. Update text, colors (see the `:root` CSS variables at the top),
and links directly in that file.
