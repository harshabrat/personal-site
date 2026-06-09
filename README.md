# Harshabrat Personal Site

A personal portfolio and blog built with [Zola](https://www.getzola.org/). The site includes project writeups, blog posts, and an about page.

## Development

Install Zola, then run:

```bash
zola serve
```

Build the static site with:

```bash
zola build
```

## Structure

- `content/` contains the site pages, blog posts, and project writeups.
- `templates/` contains the Zola templates.
- `sass/` contains the source styles.
- `static/` contains files copied directly into the final site.

Generated output in `public/`, processed images, and local `.DS_Store` files are ignored and should not be committed.
