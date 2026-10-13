# Zhaodong Guo — Academic Homepage

This site is a concise academic homepage built from the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) Jekyll template. It is configured for `https://zhaodong929.github.io`.

## Edit the profile

- Update name, position, email, location, profile links, CV path, arXiv link, and ORCID link in `_config.yml`.
- Replace `images/profile.jpg` with the full profile photo, keeping the same filename, or update `author.avatar` in `_config.yml`. The stylesheet displays the complete image at its natural proportions without cropping, a frame, or a shadow.

## Add a publication

Edit `_pages/about.md` and copy one of the existing `<article class="publication-card">` blocks. Update the title, author line, venue or status, summary, and links. Keep under-review work described as a manuscript under review until it is safe to disclose authorship.

## Add a research project

Edit `_pages/projects.md` and copy a `<article class="project-card">` block. Keep the problem, idea, and contribution concise and supported by the project materials.

## Update the CV

Replace `files/Zhaodong_Guo_CV.pdf` with the latest PDF and keep the filename, or update the link in `_pages/about.md`.

The first-page preview PDFs for the two manuscripts under review are stored as `files/KronHiPPO_STGP.pdf` and `files/HiPPO_Functional_Memory.pdf`; the accepted workshop paper remains at `files/Analytic_Interdomain_Memory_HiPPO_SVGP.pdf`. Keep the first two files limited to a single-page preview and update the corresponding links in `_pages/about.md` and `_pages/projects.md` when replacing them.

KronHiPPO-STGP and HiPPO Functional Memory display disabled "Code (private)" labels while their repositories are private. Analytic Interdomain Memory links to `Analytic-HippoSVGP`. Update these in the same two page files.

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

The Google Scholar, arXiv, and ORCID entries are placeholders because the source CV did not provide personal profile URLs or identifiers. Replace them in `_config.yml` when available.
