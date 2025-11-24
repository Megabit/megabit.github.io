# Company Website Template

This repository contains the source code for the **Megabit** company
website, built using **GitHub Pages**, **Jekyll**, and the **Agency
Jekyll Theme**.

The site is designed for easy maintenance, fast deployment, and clean
presentation of: 

- Company services
- Portfolio items
- About information
- Team members
- Timeline / history
- Contact information

## 🚀 Features

-   Responsive, modern one-page layout
-   Portfolio and services sections
-   Optimized for GitHub Pages
-   Easy customization via `_config.yml`
-   SEO-friendly structure
-   Supports custom domains
-   Custom CSS overrides
-   Markdown content support
-   Fast builds with Jekyll remote theme
-   Smooth scrolling and animated sections

## 🧩 Technology Stack

  Component                 Description
  ------------------------- --------------------------------------------
  **Jekyll**                Static site generator used by GitHub Pages
  **Agency Jekyll Theme**   Base template used for layout and styling
  **GitHub Pages**          Hosting and automatic build system
  **Liquid Templates**      For data-driven sections
  **SCSS & Custom CSS**     For styling and overrides

**Theme Source:**

This site is built using the excellent **Agency Jekyll Theme**: https://github.com/raviriley/agency-jekyll-theme

## 📁 Project Structure

    .
    ├── _config.yml
    ├── _data/
    ├── _includes/
    ├── _layouts/
    ├── assets/
    │   ├── css/custom.css
    │   └── img/
    └── index.md

## 🎨 Customizing the Design

### 1. Edit Company Info

Update data files in `_data/` and settings in `_config.yml`.

### 2. Override CSS

Add overrides in:

    assets/css/custom.css

And ensure it loads in `_includes/head.html`.

## 🌐 Using a Custom Domain

Add GitHub Pages custom domain, then configure GoDaddy DNS with GitHub's
A and CNAME records, and enable HTTPS.

## 🛠 Running Locally

    bundle install
    bundle exec jekyll serve

## 🚀 Deployment

Automatic on push to `main`.

## 🙏 Credits

Built using **Agency Jekyll Theme**: https://github.com/raviriley/agency-jekyll-theme

## 📄 License

Content © Megabit d.o.o.
