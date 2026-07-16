# Deploying this site to GitHub Pages

You have two files: `index.html` and `assets/Wasi_Omar_Syed_Academic_CV.pdf`.
Here's the fastest way to get this live at a public URL.

## Option A — Personal site at `wasiomar.github.io` (recommended)

1. Go to https://github.com/new
2. Repository name must be exactly: `WasiOmar.github.io` (your GitHub username + `.github.io`)
3. Make it **Public**, don't add a README, click **Create repository**
4. On the new repo page, click **"uploading an existing file"**
5. Drag in `index.html` and the `assets` folder (with the CV PDF inside), commit
6. Go to **Settings → Pages** (left sidebar)
7. Under "Build and deployment", Source = **Deploy from a branch**, Branch = **main**, folder = **/ (root)**, click **Save**
8. Wait 1–2 minutes, then your site is live at:
   **https://wasiomar.github.io**

## Option B — As a project page in any repo

1. Create (or use an existing) repository, e.g. `academic-site`
2. Upload `index.html` and the `assets` folder to it
3. Settings → Pages → Source = Deploy from a branch → Branch = `main` → folder = `/ (root)` → Save
4. Your site will be live at:
   **https://wasiomar.github.io/academic-site**

## Submitting the assignment

Once the site is live (check the URL loads in an incognito tab first), submit that URL as your live site link for Task 2.

## Updating later

To make edits, just edit `index.html` directly in the GitHub web editor (click the pencil icon on the file) or re-upload a changed copy — GitHub Pages rebuilds automatically within a minute or two of any commit to `main`.
