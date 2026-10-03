# Bikeguy

My personal blog, built with [Jekyll](https://jekyllrb.com/) and the
[Minima](https://github.com/jekyll/minima) theme.

## Publish with GitHub Pages

1. In the repository on GitHub, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Pick the branch (e.g. `main`) and the `/ (root)` folder, then save.
4. The site will appear at `https://bikeguy59.github.io/Bikeguy/`. Set
   `baseurl: "/Bikeguy"` and `url: "https://bikeguy59.github.io"` in
   `_config.yml` so links and styles resolve correctly.

## Write a post

Create `_posts/YYYY-MM-DD-my-title.md`:

```markdown
---
layout: post
title: "My Title"
date: 2026-10-04 08:00:00 -0400
categories: rides
---

Post content in Markdown.
```

## Run locally

Requires Ruby and Bundler.

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.

## Customize

- `_config.yml` — site title, description, author, social links.
- `about.md` — the About page.
- `index.md` — the home page (lists posts automatically).
