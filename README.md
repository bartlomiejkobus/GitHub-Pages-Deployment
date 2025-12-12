# GitHub-Pages-Deployment

Simple GitHub Actions workflow to deploy a **static website** to GitHub Pages.  
This project demonstrates **continuous deployment** of `index.html` whenever changes are pushed to the `main` branch.

This project is inspired by the [GitHub Actions Deployment Roadmap](https://roadmap.sh/projects/github-actions-deployment-workflow).

---

## Features

- Deploy **only when `docs/index.html` changes**
- Simple **static site** (HTML + CSS + JS)
- **Toggle light/dark theme**
- **Show greeting** with a click
- Automatic **date/time of deployment**
- No build step required — ideal for testing CI/CD flows

---

## Requirements

- GitHub repository
- GitHub Pages enabled
- Basic HTML/CSS/JS files in `docs/` folder
- GitHub Actions enabled

---

## Usage

1. Clone the repository:

```bash
git clone https://github.com/bartlomiejkobus/GitHub-Pages-Deployment.git
cd GitHub-Pages-Deployment
```

2. Make changes to `docs/index.html` or other files in `docs/`

3. Commit and push to `main` branch:
```bash
git add docs/index.html
git commit -m "feat: update content"
git push origin main
```

4. Workflow will **automatically deploy** changes to GitHub Pages

4. Or run manually via **Actions → Run workflow** in GitHub UI


## Example Output

Visit the live GitHub Pages site: [GitHub-Pages-Deployment](https://bartlomiejkobus.github.io/GitHub-Pages-Deployment/)

The page includes:

- Greeting section that toggles on button click  
- Light/Dark theme toggle  
- Deployment timestamp
