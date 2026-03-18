# AppsByAaron Dashboard

A single-file Bootstrap 5 dashboard for organizing website links into clean category containers with stacked buttons.

This dashboard is built for people who want a fast, simple launcher for websites without relying on browser bookmarks.

---

## Features

- Single HTML file
- Built with Bootstrap 5
- Categories displayed as container blocks
- Links displayed as stacked buttons inside each category
- Add, edit, and delete links
- Create, rename, and delete categories
- Assign links to categories
- Search links by title, tags, or URL
- Favorite toggle for links
- Copy URL button
- Import and export JSON data
- Local data persistence using `localStorage`
- Alphabetical sorting for categories
- Alphabetical sorting for links inside categories
- Responsive layout

---

## File Structure

This project uses a single file:

- `index.html` — main dashboard file

No build tools or installation are required.

---

## How It Works

The dashboard stores data in your browser using `localStorage`.

Saved data includes:

- Categories
- Links
- Sort preferences

This means your changes remain after refreshing the page, as long as you use the same browser and do not clear site storage.

---

## Link Data Format

Each link is stored like this:

```json
{
  "title": "ChatGPT",
  "url": "https://chat.openai.com/chat",
  "tags": ["ai"],
  "fav": false,
  "category": "AI"
}
