# Adones Neto — Portfolio

A small, responsive portfolio in Brazilian Portuguese, built with HTML and CSS. No dependencies, build step, tracking, or external fonts.

## Preview

```bash
python3 -m http.server 8080 --directory dist
```

Open http://localhost:8080. Edit `dist/index.html` for content and `dist/style.css` for the design.

## Contents

- Introduction and technology focus
- ABZSS, BetterTeaching, and Theater Management
- About and contact links

Project visuals are illustrations, not screenshots or live database results. Contact links come from the existing GitHub profile README. Database capabilities are labeled as in development and awaiting real Oracle validation.

## Hosting

`dist/` is published at https://adyshavefear.github.io/ using GitHub Pages. The default branch is `main`, and Pages uses GitHub Actions rather than publishing the repository root.

## GitHub Pages

The repository includes `.github/workflows/pages.yml` to publish `dist/` after pushes to the default branch.

1. Create a public GitHub repository and push this project.
2. In **Settings → Pages → Build and deployment**, select **GitHub Actions**.
3. Run **Actions → Deploy portfolio to GitHub Pages → Run workflow**, or push another commit to the default branch.
4. Open the URL shown in the successful deployment.

For a repository named `adyshavefear.github.io`, the site will be served at `https://adyshavefear.github.io/`. For another repository name, GitHub Pages adds the repository name to the URL. All assets use relative paths to support both options.

Workflow setup follows the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages).
