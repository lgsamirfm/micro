# Micro cheatsheets

Persian, right-to-left study notes for Micro 1, Micro 2, and Micro 3. This is a static HTML site with no build step or package installation.

## Pages

- [Micro 1](index.html) — the site homepage
- [Micro 2](micro2_cheatsheet_persian.html)
- [Micro 3](Micro3_cheatsheet_persian.html)

Every page includes navigation to the other two. Keep the HTML files and `navbar.css` together in the repository root. Relative links support both local previews and GitHub Pages project URLs such as `/micro/`.

## Preview locally

Run this command from the repository root:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`. The server automatically serves `index.html` as the homepage.

## Publish with GitHub Pages

1. Make sure these changes are on the repository's `main` branch.
2. Open the repository on GitHub and go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Source: Deploy from a branch**.
4. Select **main** and **/(root)**, then click **Save**.
5. Wait for GitHub to finish deploying. For this repository, the project-site URL is `https://lgsamirfm.github.io/micro/`.

The empty `.nojekyll` file tells GitHub Pages to serve the static files directly without a Jekyll build. Publishing is a repository setting; the files being ready does not enable Pages automatically.
