# boxis.github.io

My personal blog, live at **<https://boxis.github.io>** — posts, book reviews/summaries, random thoughts, and TIL notes.

Built with [Jekyll](https://jekyllrb.com/) + the [Chirpy theme](https://github.com/cotes2020/jekyll-theme-chirpy) (via [chirpy-starter](https://github.com/cotes2020/chirpy-starter)), deployed automatically by GitHub Actions on every push to `master`.

## Writing a new post

1. Create a file in `_posts/` named `YYYY-MM-DD-short-title.md`
2. Start it with front matter:

   ```yaml
   ---
   title: My Post Title
   date: 2026-07-19 12:00:00 -0400
   categories: [Books]        # one of: Blogging, Books, Thoughts, TIL (or invent a new one)
   tags: [book-review]        # lowercase, freeform
   ---
   ```

3. Write Markdown below the front matter
4. Commit and push — the site rebuilds and deploys in ~2 minutes

Posts can also be created/edited directly on github.com from any device.

## Structure

- `_posts/` — all blog content
- `_tabs/about.md` — the About page
- `_config.yml` — site title, tagline, avatar, social links, analytics, comments
