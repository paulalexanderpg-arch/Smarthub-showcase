[README.md](https://github.com/user-attachments/files/24388045/README.md)
# Client Overview Site

This is a standalone, modern overview site (React via CDN) for client-facing sharing.
It is ready for GitHub Pages without a build step.

## Deploy to GitHub Pages

Option A: Use repository root
1) Create a new repo.
2) Copy the contents of `client_overview/` into the repo root.
3) Push to `main`.
4) In GitHub: Settings -> Pages -> Deploy from branch -> `main` / `/ (root)`.

Option B: Use a `/docs` folder in an existing repo
1) Copy the contents of `client_overview/` into `docs/`.
2) Commit and push.
3) In GitHub: Settings -> Pages -> Deploy from branch -> `main` / `/docs`.

## Customize

- Edit text and labels inside `client_overview/index.html`.
- Replace demo email addresses (`demo@company.com`, `info@company.com`) with your real contact.
- Update the title/brand as needed.
