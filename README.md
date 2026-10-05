# Mohamad Fazil J — Product Designer Portfolio

This folder contains the complete, self-contained source code for your portfolio website, ready to be hosted on **GitHub Pages** (or any static hosting service like Netlify, Vercel, or Cloudflare Pages).

---

## 📁 Project Structure

```text
├── index.html                 # Main Homepage / Portfolio
├── casestudyone.html          # Jupiter Money Case Study (Direct file URL)
├── casestudyone/
│   └── index.html             # Clean URL support (/casestudyone/)
├── walkthrough.html           # Walkthrough video page
├── walkthrough/
│   └── index.html             # Clean URL support (/walkthrough/)
├── 404.html                   # Fallback redirect for GitHub Pages
├── .nojekyll                  # Prevents Jekyll from ignoring files
└── images/                    # All 16 local images, mockups & icons
    ├── 3e9R5McH8is4nj6gYIcoKpcQBUI.png
    ├── D1RFLPOioXjXCySyzoabwJIJNgI.png
    ├── XpfHuYIrDSuQYC01YyKMX69w72M.png
    └── ... (all portfolio media)
```

---

## 🚀 How to Host on GitHub Pages (Step-by-Step)

### Option 1: Using the GitHub Web Interface (Easiest)

1. Go to [GitHub](https://github.com) and click **New repository** (or `+` in the top right).
2. Repository Name:
   - For a primary portfolio URL (`https://<username>.github.io`): name your repository `<your-github-username>.github.io`.
   - Or name it `portfolio` (the site will be at `https://<username>.github.io/portfolio/`).
3. Make sure the repository is **Public**.
4. Click **Create repository**.
5. Click **Upload an existing file** or drag and drop all the files and folders from `portfolio-github/` directly into the repository root.
6. Commit the changes.
7. Go to **Settings** → **Pages** (in the left sidebar).
8. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
9. Select Branch: `main` (or `master`) and Folder: `/ (root)`, then click **Save**.
10. In 1–2 minutes, your website will be live at:
    `https://<your-username>.github.io`!

---

### Option 2: Using Git in the Terminal

Open your terminal in this folder and run:

```bash
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

Then enable GitHub Pages under **Settings** → **Pages** → Branch: `main` → `/ (root)`.
