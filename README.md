# Blog — Hugo Static Site

A personal blog built with **Hugo** (static site generator) using the **hugo-theme-cactus-plus** theme. This is a fork of [mantoniou/Blog](https://github.com/mantoniou/Blog) customized for personal content.

## About

This repository contains the source for a Hugo-powered static blog with content, layouts, and static assets organized in the standard Hugo project structure.

## Tech Stack

| Technology | Purpose |
|---|---|
| Hugo | Static site generator |
| hugo-theme-cactus-plus | Blog theme |
| HTML/CSS | Content and styling |
| Netlify | Deployment (netlify.toml) |
| R Markdown (.Rproj) | R-based content authoring |

## Project Structure

```
Blog/
├── content/           # Blog posts and pages (Markdown)
├── layouts/           # Custom HTML templates
├── static/            # Static assets (images, CSS, JS)
├── public/            # Generated site output
├── themes/
│   └── hugo-theme-cactus-plus/   # Blog theme
├── config.toml        # Hugo site configuration
├── netlify.toml       # Netlify deployment config
├── index.Rmd          # R Markdown index
├── Blog.Rproj         # R project file
└── README.md
```

## Getting Started

1. Install [Hugo](https://gohugo.io/getting-started/installing/)
2. Clone the repository:
   ```bash
   git clone https://github.com/shreyawritescode/Blog.git
   cd Blog
   ```
3. Run the development server:
   ```bash
   hugo server -D
   ```
4. Open [http://localhost:1313](http://localhost:1313) in your browser.

## Building for Production

```bash
hugo
```

The generated static site will be output to the `public/` directory, ready for deployment.

## Deployment

Configured for **Netlify** deployment via `netlify.toml`.

## Forked From

This project is forked from [mantoniou/Blog](https://github.com/mantoniou/Blog).

---

*A personal Hugo blog — exploring static site generation and content publishing.*
