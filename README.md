# PetAgeCalc — Dog & Cat Age Calculator

PetAgeCalc is an ultra-fast, visually stunning web application built with **Astro 5** and **Tailwind CSS v4**. It features accurate calculators to convert your pet's age into human years, alongside a rich, Markdown-powered Pet Advice blog.

## 🚀 Features

- **Dog Age Calculator:** Accurately converts dog age to human years based on size (Small, Medium, Large, Giant) using up-to-date veterinary formulas.
- **Cat Age Calculator:** Converts cat age to human years, accounting for the rapid developmental stages in the first two years of a cat's life.
- **Markdown Blog (Content Collections):** A blazing-fast "Pet Advice" hub powered by Astro Content Collections, fully SEO optimized.
- **Premium Glassmorphic UI:** Designed with custom Tailwind v4 utilities, dark mode/light mode toggling, and fluid animations.
- **Technical SEO:** 100% SEO optimized with dynamic Open Graph images (`og-image.png`), `robots.txt`, dynamic `sitemap.xml`, and JSON-LD structured data (`WebApplication` and `FAQPage`).

## 🛠️ Tech Stack

- **Framework:** [Astro](https://astro.build)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
- **Deployment:** Cloudflare Pages (Optimized via `@astrojs/cloudflare` adapter)
- **Icons:** Custom SVG Assets

## 💻 Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:4321/`.

3. Build for production:
   ```bash
   npm run build
   ```

## 📝 Editing the Blog

The blog is fully dynamic and powered by Markdown. To add a new article, simply create a new `.md` file inside the `src/content/blog/` directory with the following frontmatter:

```markdown
---
title: "Your Post Title"
description: "A short description for SEO and the preview card."
pubDate: "2026-06-15"
author: "PetAgeCalc Team"
tags: ["dogs", "health"]
---

Your markdown content here...
```
Astro will automatically generate the page, add it to the `/pet-advice` grid, and inject it into the `sitemap.xml`.

## 🌐 Deployment

This project is configured to be deployed effortlessly on **Cloudflare Pages**. 
Simply connect this repository to Cloudflare Pages via your Cloudflare Dashboard, and the site will automatically build and deploy every time you push to the `main` branch.
