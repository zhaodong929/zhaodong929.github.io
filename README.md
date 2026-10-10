# Zhaodong Guo — Academic Homepage

This site is a concise academic homepage built from the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll template. It is configured for `https://zhaodong929.github.io`.

## Edit the profile

- Update name, position, email, location, profile links, and avatar path in `_config.yml`.
- Replace `images/profile.jpg` with a square profile photo, keeping the same filename, or update `author.avatar` in `_config.yml`.

## Add a publication

Edit `_pages/about.md` and copy one of the existing `<article class="publication-card">` blocks. Update the title, author line, venue or status, summary, and links. Keep under-review work anonymized until it is safe to disclose authorship.

## Update the CV

Replace `files/Zhaodong_Guo_CV.pdf` with the latest PDF and keep the filename, or update the link in `_pages/about.md`.

## Build locally

Install Ruby, Bundler, and the GitHub Pages dependencies, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000` and check the homepage, navigation anchors, profile image, CV download, and publication links.

## Deploy with GitHub Pages

1. Create a public repository named `zhaodong929.github.io` under the GitHub account `zhaodong929`.
2. From this directory, set the remote and push the `main` branch:

   ```bash
   git remote set-url origin https://github.com/zhaodong929/zhaodong929.github.io.git
   git branch -M main
   git add .
   git commit -m "Build academic homepage"
   git push -u origin main
   ```

3. In the repository settings, open **Pages**, choose **GitHub Actions** as the source, and let the `Deploy to GitHub Pages` workflow publish the site.
4. After the workflow completes, visit `https://zhaodong929.github.io`.

The Google Scholar and LinkedIn links currently point to their service homepages because the source CV did not provide personal profile URLs. Replace them in `_config.yml` when available. The arXiv, PDF, and code buttons marked as placeholders should be replaced in `_pages/about.md` when public links are ready.
