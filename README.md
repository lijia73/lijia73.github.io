# Jia Li Personal Homepage

This is a static academic homepage built for GitHub Pages.

## Files

- `index.html`: homepage content
- `styles.css`: responsive visual design
- `.github/workflows/pages.yml`: GitHub Pages deployment workflow
- `.nojekyll`: keeps GitHub Pages from running Jekyll processing

## Deploy on GitHub Pages

1. Create a GitHub repository. Use `<username>.github.io` for a root personal site, or any repository name for a project site.
2. Push these files to the repository's `main` or `master` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Set `Build and deployment` -> `Source` to `GitHub Actions`.
5. The workflow will publish the site after the next push.

Root personal site URL:

```text
https://<username>.github.io/
```

Project site URL:

```text
https://<username>.github.io/<repository>/
```
