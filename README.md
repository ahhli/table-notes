# 席间 · At the Counter

A bilingual field journal for food, cities, and the decisions made at the counter.

## Local development

```sh
npm install
npm run dev
```

## Content

- Chinese notes: `src/pages/notes/`
- English notes: `src/pages/en/notes/`
- Site styles: `src/styles/global.css`
- Original photography: `public/images/<story-slug>/`

Each story is a Markdown file with its own title, description, language switch target, and course progression.

## GitHub Pages

The included workflow builds and deploys the site whenever `main` is pushed. The Astro configuration automatically derives the correct repository base path during GitHub Actions builds.
