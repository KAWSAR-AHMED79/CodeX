# CodeX

A responsive starter website using plain HTML and CSS. No dependencies or build step are required.

## Preview locally

Open `index.html` in your browser, or run this command from the repository directory:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Files

- `index.html`: page content.
- `style.css`: responsive styles.
- `.gitignore`: excludes common local files and environment secrets.
- `.github/workflows/pages.yml`: deploys the website to GitHub Pages.

## Publish with GitHub Pages

1. Commit and push these files to the `main` branch on GitHub.
2. In the repository's **Settings → Pages**, select **GitHub Actions** as the source.
3. Run **Deploy website to GitHub Pages** from the **Actions** tab, or push another change to `main`.

The workflow publishes only `index.html` and `style.css`. The deployment requires GitHub Pages to be available and enabled for the repository.
