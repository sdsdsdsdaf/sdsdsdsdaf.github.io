# Dongchan Kim — Academic Homepage

Built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages.

## Deploy

1. Replace every `YOUR_GITHUB_ID` in `_config.yml` with your GitHub username.
2. Create an empty **public** repository named `<your-github-id>.github.io`.
3. Push:

   ```bash
   git remote add origin https://github.com/<your-github-id>/<your-github-id>.github.io.git
   git push -u origin main
   ```

4. Repository **Settings → Pages**: Source = "Deploy from a branch", Branch = `main` / `(root)`.
5. The site is live at `https://<your-github-id>.github.io` after a few minutes.

## Where to edit

| What | File |
|---|---|
| Name, sidebar bio, links (Scholar, GitHub, …) | `_config.yml` |
| Front page | `_pages/about.md` |
| CV page | `_pages/cv.md` |
| Top menu | `_data/navigation.yml` |
| Profile photo | `images/profile.png` (replace the file, keep the name) |
| Papers | one Markdown file per paper in `_publications/` |
| PDFs (CV, papers) | `files/` → served at `/files/<name>.pdf` |

### Adding a paper

Create `_publications/2027-06-01-paper-name.md`:

```markdown
---
title: "Paper Title"
collection: publications
category: conferences
permalink: /publication/2027-06-01-paper-name
date: 2027-06-01
venue: 'CVPR 2027'
paperurl: 'https://arxiv.org/abs/xxxx.xxxxx'
citation: 'Dongchan Kim, ... (2027). "Paper Title." <i>CVPR</i>.'
---
Short abstract.
```

## Local preview (optional)

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```
