# Auspr7ng Portfolio

A simple Vue-powered static portfolio showcasing experience, projects, notes, and publications.

## Tech Stack
- Static HTML + CSS
- Vue 3 (CDN build)

## Project Structure
- index.html — main single-page app
- assets/ — images, icons, resume PDF
- notes/notes.json — note metadata loaded at runtime

## Running Locally
1. Clone or download the repo.
2. Open index.html directly in your browser, or serve the folder (e.g., `python -m http.server 8000`).
3. Ensure assets/ and notes/ stay alongside index.html.

## Customizing
- Content: edit the Vue data in index.html (skills, experiences, projects, notes, pubs).
- Notes list: update notes/notes.json entries.
- Styling: tweak CSS variables and styles in the <style> block of index.html.

## Deployment
Host the folder on any static host (GitHub Pages, Netlify, Vercel). Point the site root to index.html.
