
# Academic Homepage Starter (GitHub Pages + Minimal Mistakes)

This repo is a ready-to-publish academic homepage for **GitHub Pages**.

## Quick start
1. Create a new repo named **`sultanahammad.github.io`** on your GitHub account.
2. Upload all files from this folder (or push with Git).
3. In the repo, go to **Settings → Pages** and ensure the site builds from the `main` branch `/ (root)`.
4. Replace placeholders in:
   - `_config.yml` (name, social links, menu)
   - `index.md` (bio + news)
   - `publications.md` (your papers)
   - `teaching.md`
   - `vacancies.md`
5. Put your **CV** at `files/CV.pdf` and (optionally) a headshot at `assets/img/profile.jpg`.

## Local preview (optional)
If you want to preview locally, install Ruby and Jekyll, then run:
```bash
bundle install
bundle exec jekyll serve
```
(You can also skip local preview and let GitHub Pages build automatically.)

## Notes
- This starter uses **Minimal Mistakes** via `remote_theme`, which GitHub Pages supports.
- Publication lists here are manual Markdown (simple and reliable on GitHub Pages). If you need automatic BibTeX rendering, consider the **academicpages** template with Actions.
