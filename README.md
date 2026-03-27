# THE BAD NEIGHBORHOOD

> Stories that live on the edge. Published raw, chapter by chapter.

A cinematic storytelling platform built as a single, self-contained HTML file — no build tools, no dependencies, no server required.

---

## 🚀 Deploy

### GitHub Pages (Recommended)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

Your site will be live at `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

### Any Static Host

Upload `index.html` to any static hosting service:
- Cloudflare Pages
- Netlify (drag & drop)
- Vercel
- Any web server

---

## 🎨 Design

| Token | Value |
|---|---|
| Asphalt (dark) | `#1A1A1B` |
| Rawbone (light) | `#E9E9E2` |
| Sulphur (accent) | `#CCFF00` |

**Fonts:** Space Grotesk (headings) · JetBrains Mono (labels) · Inter (body)

---

## 🔐 Admin Access

The Drafting Board is password protected. Click **Manifesto → Drafting Board** or the **Admin ✦** badge (visible after login).

**Default password:** `NeIgHbOrHoOd2025`

To change it, open `index.html` and find:
```js
var ADMIN_PASSWORD = 'NeIgHbOrHoOd2025';
```

---

## 📁 Structure

```
the-bad-neighborhood/
├── index.html      ← Entire app (HTML + CSS + JS)
├── README.md
├── .gitignore
└── LICENSE
```

---

## ✏️ Customise

All content lives inside `index.html`. Find the **DATA** section in the `<script>` tag:

```js
var stories = [ ... ];   // Add / edit your stories here
var chapters = { ... };  // Add / edit chapters per story
```

---

## 📄 License

MIT — do whatever you want with it.
