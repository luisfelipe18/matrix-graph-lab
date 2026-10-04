# Matrix ↔ Graph Lab

A small, browser based linear algebra lab for exploring the relationship between a matrix and its directed graph. Edit matrix entries and compare the input matrix, inverse, adjugate, and Laplacian.

Everything runs locally in the browser. No build step, package manager, API key, or backend is required.

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server.

## Publish with GitHub Pages

Suggested repository name: **`matrix-graph-lab`**

Create an empty GitHub repository with that name, then run these commands from this project folder. Replace `YOUR-USERNAME` with your GitHub username:

```sh
git init -b main
git add index.html favicon.svg README.md
git commit -m "Build Matrix Graph Lab"
git remote add origin https://github.com/YOUR-USERNAME/matrix-graph-lab.git
git push -u origin main
```

Then open the repository on GitHub and select **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **`main`** and **`/(root)`**, then save. GitHub Pages will publish the static site at:

```text
https://YOUR-USERNAME.github.io/matrix-graph-lab/
```

The page and favicon use relative paths, so they also work at the repository subpath used by GitHub Pages.
