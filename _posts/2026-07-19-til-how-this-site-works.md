---
title: "TIL: How GitHub Pages Turns Markdown Into This Site"
date: 2026-07-19 12:00:00 -0400
categories: [TIL]
tags: [github, jekyll]
---

Today I learned (by setting it up) how this site actually works:

- **GitHub Pages** serves any repo named `<username>.github.io` as a website — free, no server to manage.
- **Jekyll** is the static site generator: it takes Markdown files and templates and produces plain HTML.
- **Chirpy** is the Jekyll theme this site uses. It provides the layout, sidebar, categories/tags pages, search, and the dark/light mode toggle.
- On every push, a **GitHub Actions** workflow builds the site with Jekyll, runs an HTML validity check, and deploys the result to GitHub's CDN. It takes about two minutes.

The nice consequence: publishing a post is just `git push` — or even editing a file directly on github.com.
