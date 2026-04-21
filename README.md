# UCLA Priority Matrix (Interactive)

Static single-page app: open `index.html` in a browser or serve this folder for deployment.

Aligned with the working group white paper draft (April 2026).

## Publish to GitHub

This folder is a git repository on branch `main` with `index.html` at the repo root (works with GitHub Pages).

**Option A (GitHub CLI):**

```bash
cd "/path/to/apr_21_data"
gh auth login
gh repo create YOUR-REPO-NAME --public --source=. --remote=origin --push
```

**Option B (manual):** Create an empty repository on GitHub, then:

```bash
cd "/path/to/apr_21_data"
git remote add origin https://github.com/YOURUSERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

Use a [personal access token](https://github.com/settings/tokens) as the password if prompted for HTTPS.
