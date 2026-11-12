# Adones Neto — Portfolio

A small, responsive portfolio in English, built with HTML and CSS. No application dependencies, build step, tracking, or external font requests. Inter and JetBrains Mono are self-hosted with their OFL licenses.

## Preview

```bash
python3 -m http.server 8080 --directory dist
```

Open http://localhost:8080. Edit `dist/index.html` for content and `dist/style.css` for the design.

## Contents

- Introduction and technology focus
- Professional projects: RHCA and PROCON PMJP, with institutional context, role, contributions, and engineering challenges
- Personal and academic projects: ABZSS, Oracle PL/SQL Toolkit, BetterTeaching, and Theater Management System
- INOVATEC-JP professional experience (June 2026 – Present)
- About and contact links

The Black Reaper artwork is reused from the existing GitHub profile README. Terminal commands are illustrative examples, not live database results. Users who prefer reduced motion receive a static frame instead of the animated GIF. Contact links come from the existing GitHub profile README. ABZSS examples show commands available in the public repository; Oracle/APEX integrations are explicitly labeled as planned.

## Hosting

`dist/` is published at https://adyshavefear.github.io/ using GitHub Pages. The default branch is `main`, and Pages uses GitHub Actions rather than publishing the repository root.

## GitHub Pages

The repository includes `.github/workflows/pages.yml` to publish `dist/` after pushes to the default branch.

1. Review the feature branch and open a pull request against `main` in the existing `adyshavefear/adyshavefear.github.io` repository.
2. After approval, merge the pull request. The existing workflow publishes `dist/` only from the default branch.
3. Open the URL shown in the successful deployment. Pages should remain configured to use **GitHub Actions**.

For a repository named `adyshavefear.github.io`, the site will be served at `https://adyshavefear.github.io/`. For another repository name, GitHub Pages adds the repository name to the URL. All assets use relative paths to support both options.

Workflow setup follows the [GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/using-custom-workflows-with-github-pages).

## Visual direction

The design follows the profile README: near-black background, red highlights, cyan terminal accents, and an Oracle/APEX focus. Education, location, and contact details are taken from that README; the current role and professional experience use the portfolio owner's supplied information.

Image Gen concepts and implementation decisions are recorded in [docs/design/design-spec.md](docs/design/design-spec.md). The site remains native HTML/CSS; UI text is not embedded in screenshots.

## Content verification

Professional descriptions and the INOVATEC-JP title and dates come from the portfolio owner's supplied experience. Engineering challenges summarize those responsibilities; no measured outcomes or independent ownership are claimed. The institutional entries contain no source links, internal screenshots, schemas, endpoints, or government records.

Public project descriptions were checked against their GitHub content:

- [ABZSS](https://github.com/adyshavefear/abzss): commands, service/adapter separation, and Mocha/Chai tests.
- [Theater Management System](https://github.com/adyshavefear/gerenciamento-teatro): Java 21, Swing, Hibernate/H2 persistence, business services, and JUnit tests.
- [Oracle PL/SQL Toolkit](https://github.com/adyshavefear/oracle-plsql-toolkit): learning examples for business rules, auditing, analytical queries, and APEX REST integration.
- [BetterTeaching](https://github.com/adyshavefear/BetterTeaching): Gemini image processing and Playwright-assisted grade entry with human review.

There is no package manifest, build command, lint configuration, or automated test suite in this static site. Preview with the command above and check local assets, fragment links, project categories, and the Pages artifact path before publishing.
