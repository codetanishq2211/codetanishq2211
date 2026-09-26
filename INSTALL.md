# 🚀 Tanishq Cyber Lab — GitHub Pages Setup

## 1. Create the website repository

Create a **public** GitHub repository named exactly:

`codetanishq2211.github.io`

GitHub Pages user sites use the `<username>.github.io` repository naming pattern.

## 2. Upload this package

Upload these files/folders to the root of that repository:

- `index.html`
- `style.css`
- `script.js`
- `.nojekyll`
- `.github/workflows/deploy-pages.yml`

## 3. Enable Pages

Open:

**Repository → Settings → Pages**

Choose **GitHub Actions** as the publishing source if GitHub asks for a source.

The included workflow will deploy the site from the `main` branch.

## 4. Open your dashboard

After the workflow finishes, your site will be:

`https://codetanishq2211.github.io`

GitHub notes that publishing can take a few minutes after changes are pushed.

## 5. Make your GitHub profile open the dashboard

Your profile repository is:

`codetanishq2211/codetanishq2211`

Replace its `README.md` with the provided `README.md`.

That README contains the **ENTER CYBER LAB** button and project links.

### Important

The GitHub profile README itself cannot run arbitrary JavaScript/CSS like a normal website. GitHub renders it as GitHub-flavored Markdown with supported HTML. The interactive parts in this package therefore live on the GitHub Pages site, while the profile README is the gateway.

## Optional: direct Git push

From the website folder:

```bash
git init
git branch -M main
git remote add origin https://github.com/codetanishq2211/codetanishq2211.github.io.git
git add .
git commit -m "Create cyber lab portfolio"
git push -u origin main
```

