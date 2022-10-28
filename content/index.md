---
title: How to get started with Nuxt content
author: Peter Bessenyei
---
# How to get started with Nuxt content

Create app:
```bash
npx nuxi init nuxt-content-sample -t content
```

Or add content to existing Nuxt project:
```bash
npm install --save-dev @nuxt/content
```

Go to root directory, create a sub-dir called `content` and add your Markdown files

## Short video tutorial

[Youtube - Nuxt Content Simplified by LearnVue](https://www.youtube.com/watch?v=vgCPAtMwDxA)

## Markdown component
::example
_This_ is data from Markdown!
::

## Static generation
```bash
npm run generate
cd .output/public
php -S localhost:8000 # serve with simple webserver
```

---

[About](/about)
