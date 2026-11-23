# Content Verse

Multi-author blogging platform (Node.js + Express + PostgreSQL).

- Public site with categories, search, author pages, sitemap.xml and robots.txt (indexable, no noindex)
- Anyone can register and write; optional admin approval
- Admin panel: published / draft / pending articles, categories, users, settings
- WordPress-style classic editor (TinyMCE) with Visual/Text tabs, Add Media, featured image, SEO box
- Google Search Console code: Admin → Settings & SEO → "Code for <head>"

## Environment variables
- `DATABASE_URL` – Postgres connection string (e.g. Neon)
- `SESSION_SECRET` – long random string
- `ADMIN_EMAIL` – the account registered with this email becomes admin
- `SITE_URL` – e.g. https://content-verse.onrender.com
- `NODE_ENV=production`

Start: `npm install && npm start`
