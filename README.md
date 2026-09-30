# CampusSwap
A modern React student marketplace demo with purple styling, locally drawn product illustrations, mobile layouts, search, categories, campus filters, sorting, saved items, listing details, photo uploads, and a listing form.

## Run in VS Code
1. Extract the ZIP.
2. Open the `campusswap-react` folder (the folder containing `package.json`).
3. Open a terminal in that folder:

```bash
npm install
npm run dev
```

Open the local URL printed by Vite (usually http://localhost:5173).
Requires Node.js 20.19+ or 22.12+. Do not double-click index.html; React source requires Vite.
If npm reports ENOENT, run `pwd` and `ls`: package.json must be in your current folder. A ZIP extractor may create an extra enclosing directory.

## Build
```bash
npm run build
npm run preview
```
The production output is in `dist`. The ZIP includes a prebuilt dist folder.

## What works
- Search title/category, category filters, campus selection, and price/date sorting.
- Save/unsave finds and explore saved listings.
- Add listings with optional photo and seller email.
- Listing details; contact email opens your email app.
- Delete listings created in this browser, with confirmation.
- Listings and favorites persist with localStorage.
- Accessible native modal dialogs and labeled form controls.

## Scope
This is a frontend demo: the initial six listings are samples. Data stays in the current browser, not a shared marketplace. No login, messaging service, payments, or user verification is implemented. Uploaded pictures are stored locally; keep them small. A storage warning appears if the browser cannot persist changes. A production marketplace needs a backend, authentication, image storage, and listing ownership rules.

## Files
- src/main.jsx: React components, sample data, state, filtering, persistence.
- src/styles.css: responsive design and CSS product illustrations.
- index.html: HTML entry.
- package.json: scripts and dependencies.

Fonts load from Google Fonts when available; system fonts work offline. Product illustrations require no external images.
