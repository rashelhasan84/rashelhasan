# Md Rashel Hasan — personal website

A single-page site with articles, research, career, and contact. No build tools are needed.

## Publish on GitHub Pages (about 10 minutes)

1. Sign in at https://github.com (create a free account if needed).
2. Click **New repository**. Name it exactly `YOUR-USERNAME.github.io` (for example `rashelhasan.github.io`). Set it to **Public**. Click **Create repository**.
3. On the new repository page, click **uploading an existing file**. Drag in `index.html`, `profile.jpg`, and `README.md`. Click **Commit changes**.
4. Go to **Settings → Pages**. Under "Branch", choose `main` and `/ (root)`, then **Save**.
5. After one or two minutes, the site is live at `https://YOUR-USERNAME.github.io`.

## Add a new article

Open `index.html` on GitHub, click the pencil icon, and find `const ARTICLES = [`. Copy one block and edit it:

```js
{date:"2026-12-01", outlet:"The Daily Star", topic:"payments",
 title:"Your article title",
 authors:"With co-author name",
 summary:"Two or three sentences on the argument.",
 url:"https://link-to-the-article"},
```

- `topic` is `payments`, `monetary`, or `public`.
- Articles sort by date automatically. Commit the change and the site updates in a minute.

## Change the photo

Upload a new file named `profile.jpg` (portrait, roughly 4:5) to replace the old one.

## Custom domain (optional)

Buy a domain (for example `rashelhasan.com`). In **Settings → Pages → Custom domain**, enter it, then add the DNS records GitHub shows at your domain registrar.
