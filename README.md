# Alloc Technology Website

DevOps and Cloud Engineering services website built with [Astro](https://astro.build) and Tailwind CSS.

## Overview

Alloc Technology provides cloud infrastructure and DevOps services including:

- Infrastructure as Code (Terraform, CloudFormation, Ansible)
- Cloud-Native Architecture (AWS, Azure, GCP, Kubernetes)
- CI/CD Pipelines
- Security & Compliance (DevSecOps, SOC 2, HIPAA, GDPR)
- Site Reliability Engineering

## Tech Stack

- **Framework:** Astro 5.x
- **Styling:** Tailwind CSS 4.x
- **UI Components:** React 19
- **Content:** Markdown/MDX
- **Deployment:** Vercel

## Getting Started

### Prerequisites

- Node.js 18+ (LTS recommended)

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

### Production Build

```bash
npm run build
```

### Preview Build

```bash
npm run preview
```

## Project Structure

```
src/
├── components/     # React/Astro components
├── config/         # Site configuration (JSON)
├── content/        # Markdown content (homepage, blog, pages)
├── layouts/        # Page layouts
├── pages/          # Astro pages
├── styles/         # Global styles
└── utils/          # Helper functions
```

## Configuration

- `src/config/config.json` - Site settings, SEO metadata
- `src/config/menu.json` - Navigation menu
- `src/config/social.json` - Social links
- `src/config/theme.json` - Theme customization (colors, fonts)

## Content Management

Content is managed via Markdown files in `src/content/`:

- `homepage/-index.md` - Homepage content
- `blog/` - Blog posts
- `pages/` - Static pages (privacy policy, terms)
- `pricing/-index.md` - Pricing page
- `faq/-index.md` - FAQ page
- `contact/-index.md` - Contact page

## License

Copyright © 2026 Alloc Technology. All rights reserved.
