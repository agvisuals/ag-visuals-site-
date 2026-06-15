# AG Visuals — Photography & Videography Portfolio

Personal portfolio website for **Alexandr Golub** — professional photographer and videographer based in Ottawa, Canada.

🌐 **Live site:** [agvisuals.ca](https://agvisuals.ca)  
📧 **Email:** agvisuals.ca@gmail.com

---

## Tech Stack

- Pure HTML5 + CSS3 + Vanilla JS
- No frameworks, no build tools
- Hosted on **GitHub Pages** (free)
- Custom domain via **Namecheap**

## Project Structure

```
ag-visuals-site/
├── index.html       ← Main portfolio page (all-in-one)
└── README.md        ← This file
```

## How to Deploy

### GitHub Pages Setup
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Source: `Deploy from a branch` → `main` → `/ (root)`
4. Save — your site will be live at `https://yourusername.github.io/ag-visuals-site`

### Connect Custom Domain (agvisuals.ca)
1. In GitHub Pages settings → **Custom domain** → enter `agvisuals.ca` → Save
2. In **Namecheap DNS** (Advanced DNS tab), add these records:

| Type | Host | Value | TTL |
|------|------|-------|-----|
| A Record | @ | 185.199.108.153 | Automatic |
| A Record | @ | 185.199.109.153 | Automatic |
| A Record | @ | 185.199.110.153 | Automatic |
| A Record | @ | 185.199.111.153 | Automatic |
| CNAME Record | www | yourusername.github.io | Automatic |

3. Wait 15–30 min → DNS propagates → ✅ site live on agvisuals.ca
4. Enable **Enforce HTTPS** in GitHub Pages settings (free SSL)

## Local Development

Just open `index.html` in any browser — no server needed.

---

© 2026 AG Visuals · Alexandr Golub
