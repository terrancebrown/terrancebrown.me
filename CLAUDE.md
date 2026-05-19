Repo: ~/Sites/terrancebrown (branch: main)
Theme: Congo
Hugo version: 0.161.1+extended+withdeploy
Deployment: Cloudflare Pages via GitHub push to main. Build command: hugo --minify. HUGO_VERSION env var is set to 0.161.1.
Editor: VSCodium (primary), micro in terminal.

Content structure:
- All posts are flat .md files in content/post/ (singular)
- Slugs are date-prefixed: YYYY-MM-DD-slug.md
- Front matter is YAML (--- delimiters)
- Archetype scaffolds: date, draft, title only — additional fields added manually
- New post command: hugo new content/post/YYYY-MM-DD-slug.md

Front matter convention (based on existing posts):
```yaml
date: YYYY-MM-DD
title: Post Title
tags: ["tag"]
draft: true
```

The site has a long archive of posts going back to 2014. The owner is South African, writes in South African English (en-GB spelling). Casual, personal writing style.
