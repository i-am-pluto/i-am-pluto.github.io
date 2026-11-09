# Still a Planet

Jekyll site, built by GitHub Pages on every push to `main`.

## Write a post
1. Create `_posts/YYYY-MM-DD-your-slug.md`:
   ```
   ---
   layout: post
   title: "Your title"
   ---
   Markdown here.
   ```
2. `git add . && git commit -m "post: your title" && git push`. It's live in about a minute.

## Linking to Medium
- Cross-post: on Medium use *Import a story* with the post's URL. Medium sets the canonical link back here.
- Written on Medium first: add `canonical: <medium url>` to the front matter, so search points there.
- To show a "also on Medium" link on a post, add `medium: <url>`.
- Medium can also follow `/feed.xml` (RSS).

Preview locally (optional): `bundle exec jekyll serve` with the `github-pages` gem.
