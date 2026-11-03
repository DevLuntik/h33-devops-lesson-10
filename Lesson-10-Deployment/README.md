# H33 DevOps Lesson 10 — Deployment

Starter website recreated from the Lesson 10 lecture screenshots.

## Files
- `index.html` — Pentatonix fan page with a YouTube embed and Statistics link
- `statistics.html` — Statistics page and link back
- `style.css` — Original basic CSS from the lecture

## Open in VS Code
1. Extract the ZIP.
2. In VS Code choose **File > Open Folder** and select `Lesson-10-Deployment`.
3. Open `index.html` in a browser (or use the Live Server extension).

## Create a GitHub repository
1. Sign in at https://github.com/new and create an **empty** repository named `h33-devops-lesson-10`. Do **not** initialize it with a README, license, or `.gitignore`.
2. Open **Terminal > New Terminal** in VS Code, inside the `Lesson-10-Deployment` folder.
3. Run these commands (replace `YOUR_USERNAME` with your GitHub username):

```powershell
git init
git branch -M main
git add .
git commit -m "Add Lesson 10 starter website"
git remote add origin https://github.com/YOUR_USERNAME/h33-devops-lesson-10.git
git push -u origin main
```

If Git says `remote origin already exists`, check `git remote -v` before changing it.

**Note:** The lecture screenshots show the starter project only. Follow any additional homework/deployment requirements your instructor gives you.
