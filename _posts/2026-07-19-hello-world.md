---
title: Hello, World
date: 2026-07-19 09:00:00 -0400
categories: [Blogging]
tags: [meta]
---

Welcome to my corner of the internet! This site is where I keep:

- **Posts** — longer-form writing on whatever I'm into
- **Books** — reviews and summaries of what I've been reading
- **Thoughts** — shorter, less polished musings
- **TIL** — small "today I learned" notes

Everything here is a plain Markdown file in a [GitHub repo](https://github.com/Boxis/boxis.github.io). When I push a new file, the site rebuilds itself automatically.

## How a post is born

Each post is a file in `_posts/` named `YYYY-MM-DD-title.md`, starting with a small header like this:

```yaml
---
title: My Post Title
date: 2026-07-19 09:00:00 -0400
categories: [Thoughts]
tags: [example]
---
```

That's it — the rest of the file is just Markdown. The theme (Chirpy) handles categories, tags, archives, search, and dark mode on its own.
