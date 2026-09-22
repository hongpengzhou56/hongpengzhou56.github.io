# Hongpeng Zhou · Health AI Lab

Academic homepage for Hongpeng Zhou at The University of Manchester.

Public URL: https://hongpengzhou56.github.io/

## Pages

- `index.html`: biography, selected news and background
- `lab.html`: Health AI Lab overview and research directions
- `people.html`: group members and alumni
- `publications.html`: recent research, earlier publications and thesis
- `join.html`: enquiries, funding links and archived opportunities
- `news.html`: news archive
- `service.html`: talks, reviewing and academic service
- `awards.html`: honours, awards and funding
- `404.html`: missing-page fallback

## Edit or preview

These are ordinary static HTML files. No installation, JavaScript framework or build service is needed. You can edit HTML directly on GitHub. Shared appearance is in `style.css`; the original portrait is `portrait.jpg`.

For a local preview, open `index.html`, or run `python -m http.server 8000` in this folder and visit http://localhost:8000.

`content-data.json` preserves the extracted source content. `build.py` regenerates the pages with Python 3 (standard library only). When using this workflow, update content-data.json for extracted records and build.py for the curated biography, research descriptions and recent-publication list, then run `python build.py`. Regeneration overwrites HTML files, so do not mix direct HTML edits with regeneration without first updating the generator.

## GitHub Pages

Repository: `hongpengzhou56/hongpengzhou56.github.io`. In Settings → Pages, use “Deploy from a branch”, branch `main`, folder `/ (root)`.

## Content notes

Content was migrated from https://www.hongpengzhou.com/ and its linked pages on 21 September 2026. Layout inspiration: https://mingfeisun.github.io/ and https://agent-lab.github.io/. Their source code, photos and personal content were not copied.

Health AI Lab is the working lab name requested by Hongpeng. Change the name in build.py and regenerate if Health AI Insight Lab is preferred.

The news and publication pages retain the acceptance/preprint status stated by the original website. The complete current bibliography remains linked through Google Scholar. Historical funding calls are labelled as archived.

The source People page contains both “Man Hou Lee” and “ManHou Lee”, with different co-supervisor details. The site consolidates these into one entry using the latter listing (Magdalene Montgomery and Li Dong); the source records remain in content-data.json for review. Please confirm the correct co-supervisors.

The March 2026 news item refers to an award at BIOINFORMATICS 2025. This chronology is retained from the original site and should be confirmed by the owner.

No custom domain has been changed; the existing hongpengzhou.com website remains independently hosted.
