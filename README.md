# Adasa (عدسة) — Arabic Photography Blog

An Arabic-first, RTL photography blog with live search and category filtering.

**Live demo:** https://my-adasa.vercel.app/

## Features

- Fully Arabic interface, designed RTL-first (`dir="rtl"`, `lang="ar"`)
- Blog with 28 articles across 5 categories (lighting, portrait, landscape, techniques, gear)
- Live client-side search that filters articles as you type
- Category filters with article counts
- Article pages with author card, reading time, and share action
- Built to handle Arabic RTL correctly: mirrored layout, Arabic-Indic numerals, localized dates
- Responsive, dark-themed design

## Tech Stack

- React + Vite
- Client-side hash routing (deep-link friendly)
- Lucide icons
- Static content rendered client-side

## Run Locally

```bash
git clone <repo-url>
cd adasa
npm install
npm run dev
```
