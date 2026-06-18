# Raliew Church Website

This repository contains a static single-page site for Raliew Seventh-day Adventist Church.

How to publish to GitHub Pages

1. Create a new GitHub repository (public) and do NOT initialize with README or .gitignore.
2. In your local folder run:

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

3. After push the GitHub Actions workflow in `.github/workflows/pages.yml` will build and deploy the site to GitHub Pages. The published URL will be one of:

- `https://<your-username>.github.io/<your-repo>/` (for repo pages)
- `https://<your-username>.github.io/` (if repo named `<your-username>.github.io`)

If you want, I can create the repo and push these changes for you — provide GitHub access details or grant a repository invite.
