# myblog03.github.io

A personal Jekyll blog and portfolio site for DevOps, cloud computing, and networking topics.

This repository contains the source files for a static blog site powered by Jekyll, with custom styling and content focused on infrastructure, automation, and technical learning resources.

## 🚀 Project Overview

- Built with **Jekyll** and the **Minima** theme.
- Includes custom page and post content in Markdown.
- Serves blog posts, technical articles, and downloadable PDF resources.
- Configured for deployment using **Vercel**.

## 📁 Repository Structure

- `_config.yml` - Jekyll site configuration and metadata.
- `_includes/` - HTML snippets included across layouts.
- `_layouts/` - Layout templates used by pages and posts.
- `_posts/` - Blog posts written in Markdown.
- `_site/` - Generated static site output (build artifacts).
- `assets/` - Static assets such as CSS, images, and PDFs.
- `Gemfile` / `Gemfile.lock` - Ruby gem dependencies for Jekyll.
- `vercel.json` - Vercel deployment configuration.

## ✨ Key Features

- Responsive blog layout with navigation and content sections.
- Custom PDF document link cards styled for a polished presentation.
- Blog categories for DevOps and networking.
- SEO-friendly configuration with `jekyll-seo-tag`.
- RSS feed support with `jekyll-feed`.

## 🛠️ Local Setup

### Prerequisites

- Ruby
- Bundler
- Git

### Install dependencies

```bash
bundle install
```

### Build the site locally

```bash
bundle exec jekyll build
```

### Serve locally

```bash
bundle exec jekyll serve
```

Then open `http://127.0.0.1:4000` in your browser.

## 📦 Deployment

This site is configured to deploy from the repository root with Vercel.

- Build command: `bundle exec jekyll build`
- Output directory: `_site`

If you want to deploy elsewhere, make sure to build the site and publish the `_site` folder.

## 📝 Content Highlights

The site currently features articles such as:

- `2025-01-15-introduction-to-docker-containers.md`
- `2025-01-20-understanding-kubernetes-basics.md`
- `2025-01-25-cicd-pipelines-with-github-actions.md`
- `2025-02-01-networking-fundamentals-tcp-ip.md`
- `2025-02-10-understanding-subnetting-and-vlans.md`
- `2025-02-15-network-security-firewalls-and-vpns.md`

It also includes resource downloads like networking and Docker PDF guides.

## 💡 Notes

- Update `_config.yml` to change site title, author info, or social links.
- Add new posts under `_posts/` with the proper Jekyll front matter.
- Keep `assets/custom.css` updated for any custom styling changes.

## 📬 Contact

For questions or contributions, refer to the repository owner at the email listed in `_config.yml`.

---

Made for sharing technical knowledge through a clean, static Jekyll blog experience.
