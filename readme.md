# 📄 Website Maintenance & Development Guide

**Project:** buds — Future Hygienic Products
**Type:** Static Company Website
**Location:** Changanacherry, Kerala, India

---

# 🎯 Purpose of this Document

This file is the **single source of truth** for:

* How the website is built
* How to update it
* How to deploy it
* How to scale it later

---

# 🧱 Current Architecture (v1)

## Stack

* HTML (single page)
* Tailwind CSS (CDN)
* No JavaScript logic
* No backend

## Hosting

* Cloudflare Pages / Netlify

## Key Principle

> Keep it simple, fast, and maintainable

---

# 📂 Project Structure

```
project/
├── index.html
├── Meta_image.jpg
└── README.md (this file)
```

---

# 🌐 Deployment Guide

## Option A — Cloudflare Pages (Recommended)

1. Create GitHub repo
2. Push files
3. Connect repo to Cloudflare Pages
4. Deploy

## Option B — Netlify

1. Drag and drop folder
2. Site goes live instantly

---

# 🔄 How to Update the Website

## Content changes (text, phone, etc.)

* Open `index.html`
* Edit directly
* Save → redeploy

## Image update

* Replace `Meta_image.jpg`
* Keep same file name OR update path in HTML

---

# 📱 QA Checklist (Before Every Deploy)

## Layout

* [ ] No broken layout
* [ ] Proper spacing
* [ ] No overlapping text

## Mobile

* [ ] Works on small screens
* [ ] No horizontal scroll
* [ ] Text readable

## Content

* [ ] Phone numbers correct
* [ ] Email correct
* [ ] Location correct (Changanacherry, Kerala)

## Performance

* [ ] Loads fast
* [ ] Image not too large

---

# 🐞 Common Issues & Fixes

## Site not updating

* Clear cache
* Redeploy

## Image not showing

* Check file name
* Check path (`./Meta_image.jpg`)

## Broken layout on mobile

* Check font sizes
* Check grid settings

---

# 🔐 Security & Safety

* No sensitive data stored
* No backend → low risk
* Hosting provides HTTPS automatically

---

# 🎨 Design Rules (DO NOT BREAK)

* No emojis
* No gradients
* No dark mode
* No clutter
* Keep layout minimal

---

# 🧠 Content Rules

* Use simple language
* Avoid buzzwords
* Keep sections short
* Focus on clarity

---

# 📈 Future Upgrade Plan

## Phase 2 (Optional)

* Add contact form (Formspree / EmailJS)
* Add analytics (Google Analytics)

## Phase 3 (Advanced)

* Add authentication (Firebase / Supabase)
* Add admin dashboard
* Add backend (Flask or Node)

---

# 🧩 Scalability Strategy

Frontend stays:

* Static + fast

New features added separately:

* Auth → external service
* Backend → separate server

---

# ⚠️ Things to Avoid

* Don’t rebuild unnecessarily
* Don’t add heavy frameworks
* Don’t overdesign
* Don’t add features without need

---

# ✅ Definition of Done

The site is considered complete when:

* It is live on a public URL
* It works on mobile
* Contact works correctly
* Client can share it

---

# 📞 Contact Reference (for quick edits)

* Phone: +91 94475 59487
* Phone: +91 75588 96906
* Phone: +91 99463 44121
* Email: [futurehygienic@gmail.com](mailto:futurehygienic@gmail.com)
* Location: Changanacherry, Kerala

---

# 🧨 Final Rule

> If you are unsure — simplify, don’t complicate.

---
