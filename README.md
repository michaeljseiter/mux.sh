# Mux Blog

A personal blog built with Eleventy, focused on sharing projects, tools, and tech experiments.

## Project Structure

- `content/`: All blog content, including posts and pages
- `content/blog/`: Blog posts (tagged with 'posts')
- `content/about.md`: About page
- `_includes/`: Template includes and layouts
- `public/`: Static assets (CSS, images, etc.)
- `src/`: Source files for development

## Development

To run the blog locally:

```bash
npm install
npm run serve
```

## Building

To build the site:

```bash
npm run build
```

The built site will be in the `_site` directory.

## Customization

The blog uses custom layouts and styling:

- `_includes/layouts/base.njk`: Base HTML structure
- `_includes/layouts/post.njk`: Blog post template
- `_includes/layouts/page.njk`: Page template
- `src/css/main.css`: Custom styling

## Content Security

The site enforces a strict Content Security Policy. All styles are bundled and served inline.

## Project Structure

- `content/`: All blog content, including posts and pages
- `content/blog/`: Blog posts (tagged with 'posts')
- `content/about.md`: About page
- `_includes/`: Template includes and layouts
- `public/`: Static assets (CSS, images, etc.)
- `src/`: Source files for development

## Development

To run the blog locally:

```bash
npm install
npm run serve
```

## Deployment

The blog is deployed to [mux.sh](https://mux.sh) using Cloudflare Pages.

## Building

To build the site:

```bash
npm run build
```

The built site will be in the `_site` directory.

## Customization

The blog uses custom layouts and styling:

- `_includes/layouts/base.njk`: Base HTML structure
- `_includes/layouts/post.njk`: Blog post template
- `_includes/layouts/page.njk`: Page template
- `src/css/main.css`: Custom styling

## Content Security

The site enforces a strict Content Security Policy. All styles are bundled and served inline.
