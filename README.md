# Ishika Tyagi — Portfolio Website

A modern, single-page portfolio for **Ishika Tyagi**, a CRC Certified Medical Coder specializing in HCC, RxHCC, and ICD-10-CM coding and Chart Auditing at CorroHealth.

Built as a single self-contained HTML file — no frameworks, no build step, no dependencies. Just open it in a browser.

---

## ✨ Features

- **Animated hero** — gradient name, typed/rotating role, count-up stats, floating credential badges, and a subtle 3D photo tilt.
- **"Areas of Focus" grid** — six service cards summarizing core competencies.
- **Scrolling marquee** of key skills.
- **Interactive cards** — spotlight-on-hover for skills, services, and certifications.
- **Polished motion** — scroll-progress bar, scroll-reveal animations, magnetic buttons, and a cursor spotlight glow (desktop only).
- **Downloadable résumé** — a one-page PDF generated from the same content (`Ishika-Tyagi-Resume.pdf`).
- **Fully responsive** — working mobile hamburger menu and stacked layouts.
- **Accessible** — respects `prefers-reduced-motion`; the native cursor is never hidden; all `mousemove` effects are rAF-throttled and desktop-gated.

---

## 📁 Structure

```
ishika-portfolio/
├── index.html               # The portfolio (self-contained: HTML + CSS + JS)
├── photo.png                # Profile photo used in the hero
├── resume.html              # Print-styled résumé (source for the PDF)
├── Ishika-Tyagi-Resume.pdf  # Downloadable résumé (linked from the site)
├── index.html.bak           # Backup of the original design (safe to delete)
└── README.md
```

> **Deploying?** Make sure `index.html`, `photo.png`, and `Ishika-Tyagi-Resume.pdf` are all uploaded together, or the photo and résumé-download links will break.

---

## 🛠 Tech Stack

- Pure **HTML + CSS + Vanilla JS** — no frameworks, no build tools, no dependencies.
- Fonts from Google Fonts: **Cormorant Garamond** (display), **Plus Jakarta Sans** (body), **JetBrains Mono** (mono).
- Works fully offline except for the web fonts.

---

## 🚀 Local Preview

Just open `index.html` in any modern browser — double-click it, or:

```powershell
# Windows
start index.html
```

To preview over a local server (optional, e.g. to test the résumé download link cleanly):

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

---

## 🌐 Deploy to GitHub Pages

### 1 — Create a repository
1. [github.com](https://github.com) → **New repository**
2. Name it `portfolio` (or `<your-username>.github.io` for a root-domain site)
3. Set it to **Public**

### 2 — Upload the files
**Option A — GitHub website (easiest):**
1. Open the repo → **Add file → Upload files**
2. Drag in `index.html`, `photo.png`, and `Ishika-Tyagi-Resume.pdf`
3. **Commit changes**

**Option B — Git:**
```bash
git init
git add index.html photo.png Ishika-Tyagi-Resume.pdf resume.html
git commit -m "Initial portfolio"
git remote add origin https://github.com/<your-username>/portfolio.git
git branch -M main
git push -u origin main
```

### 3 — Enable Pages
1. Repo **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`, folder: `/ (root)` → **Save**
4. Live in ~2 minutes at `https://<your-username>.github.io/portfolio`

---

## ✏️ Editing Content

All text and styling live inside `index.html`. Key sections, in order:

| Section          | Anchor            | What's there                               |
|------------------|-------------------|--------------------------------------------|
| Hero             | `#hero`           | Name, role, stats, photo, CTA buttons      |
| About            | `#about`          | Bio + info grid                            |
| What I Do        | `#services`       | Six "Areas of Focus" cards                 |
| Skills           | `#skills`         | Skill categories and tags                  |
| Experience       | `#experience`     | Work history                               |
| Credentials      | `#certifications` | Certifications                             |
| Education # Ishika Tyagi — Portfolio Website

A modern, single-page portfolio for **Ishika Tyagi**, a CRC Certified Medical Coder specializing in HCC, RxHCC, and ICD-10-CM coding and Chart Auditing at CorroHealth.

Built as a single self-contained HTML file — no frameworks, no build step, no dependencies. Just open it in a browser.

---

## ✨ Features

- **Animated hero** — gradient name, typed/rotating role, count-up stats, floating credential badges, and a subtle 3D photo tilt.
- **"Areas of Focus" grid** — six service cards summarizing core competencies.
- **Scrolling marquee** of key skills.
- **Interactive cards** — spotlight-on-hover for skills, services, and certifications.
- **Polished motion** — scroll-progress bar, scroll-reveal animations, magnetic buttons, and a cursor spotlight glow (desktop only).
- **Downloadable résumé** — a one-page PDF generated from the same content (`Ishika-Tyagi-Resume.pdf`).
- **Fully responsive** — working mobile hamburger menu and stacked layouts.
- **Accessible** — respects `prefers-reduced-motion`; the native cursor is never hidden; all `mousemove` effects are rAF-throttled and desktop-gated.

---

## 📁 Structure

```
ishika-portfolio/
├── index.html               # The portfolio (self-contained: HTML + CSS + JS)
├── photo.png                # Profile photo used in the hero
├── resume.html              # Print-styled résumé (source for the PDF)
├── Ishika-Tyagi-Resume.pdf  # Downloadable résumé (linked from the site)
├── index.html.bak           # Backup of the original design (safe to delete)
└── README.md
```

> **Deploying?** Make sure `index.html`, `photo.png`, and `Ishika-Tyagi-Resume.pdf` are all uploaded together, or the photo and résumé-download links will break.

---

## 🛠 Tech Stack

- Pure **HTML + CSS + Vanilla JS** — no frameworks, no build tools, no dependencies.
- Fonts from Google Fonts: **Cormorant Garamond** (display), **Plus Jakarta Sans** (body), **JetBrains Mono** (mono).
- Works fully offline except for the web fonts.

---

## 🚀 Local Preview

Just open `index.html` in any modern browser — double-click it, or:

```powershell
# Windows
start index.html
```

To preview over a local server (optional, e.g. to test the résumé download link cleanly):

```bash
# Python 3
python -m http.server 8000
# then visit http://localhost:8000
```

---

## 🌐 Deploy to GitHub Pages

### 1 — Create a repository
1. [github.com](https://github.com) → **New repository**
2. Name it `portfolio` (or `<your-username>.github.io` for a root-domain site)
3. Set it to **Public**

### 2 — Upload the files
**Option A — GitHub website (easiest):**
1. Open the repo → **Add file → Upload files**
2. Drag in `index.html`, `photo.png`, and `Ishika-Tyagi-Resume.pdf`
3. **Commit changes**

**Option B — Git:**
```bash
git init
git add index.html photo.png Ishika-Tyagi-Resume.pdf resume.html
git commit -m "Initial portfolio"
git remote add origin https://github.com/<your-username>/portfolio.git
git branch -M main
git push -u origin main
```

### 3 — Enable Pages
1. Repo **Settings → Pages**
2. **Source:** Deploy from a branch
3. **Branch:** `main`, folder: `/ (root)` → **Save**
4. Live in ~2 minutes at `https://<your-username>.github.io/portfolio`

---

## ✏️ Editing Content

All text and styling live inside `index.html`. Key sections, in order:

| Section          | Anchor            | What's there                               |
|------------------|-------------------|--------------------------------------------|
| Hero             | `#hero`           | Name, role, stats, photo, CTA buttons      |
| About            | `#about`          | Bio + info grid                            |
| What I Do        | `#services`       | Six "Areas of Focus" cards                 |
| Skills           | `#skills`         | Skill categories and tags                  |
| Experience       | `#experience`     | Work history                               |
| Credentials      | `#certifications` | Certifications                             |
| Education        | `#education`      | Degree details                             |
| Contact          | `#contact`        | Email, LinkedIn, résumé download           |

To change colors, edit the CSS variables in the `:root` block near the top of `index.html` (e.g. `--cyan`, `--gold`, `--navy`).

---

## 📄 Updating the Résumé PDF

The PDF is generated from `resume.html` — **it does not update automatically** when you edit the site. After changing résumé content, edit `resume.html` to match, then regenerate the PDF with headless Chrome:

```powershell
& "C:\Program Files\Google\Chrome\Application\chrome.exe" `
  --headless=new --disable-gpu --no-pdf-header-footer `
  --print-to-pdf="Ishika-Tyagi-Resume.pdf" `
  "file:///C:/Users/Shagun/Downloads/ishika-portfolio-v2/ishika-portfolio/resume.html"
```

Or simply open `resume.html` in a browser and use **Print → Save as PDF** (A4, margins set to *None*).

---

## 📬 Contact

- **Email:** ishikatyagi801@gmail.com
- **LinkedIn:** [in/ishika-tyagimedicalcoder](https://www.linkedin.com/in/ishika-tyagimedicalcoder)
- **Location:** Noida, Uttar Pradesh, India

---

© 2025 Ishika Tyagi · All rights reserved
       | `#education`      | Degree details                             |
| Contact          | `#contact`        | Email, LinkedIn, résumé download           |

To change colors, edit the CSS variables in the `:root` block near the top of `index.html` (e.g. `--cyan`, `--gold`, `--navy`).

---

## 📄 Updating the Résumé PDF

The PDF is generated from `resume.html` — **it does not update automatically** when you edit the site. After changing résumé content, edit `resume.html` to match, then regenerate the PDF with headless Chrome:

```powershell
& "C:\Program Files\Google\Chrome\Application\chrome.exe" `
  --headless=new --disable-gpu --no-pdf-header-footer `
  --print-to-pdf="Ishika-Tyagi-Resume.pdf" `
  "file:///C:/Users/Shagun/Downloads/ishika-portfolio-v2/ishika-portfolio/resume.html"
```

Or simply open `resume.html` in a browser and use **Print → Save as PDF** (A4, margins set to *None*).

---

## 📬 Contact

- **Email:** ishikatyagi801@gmail.com
- **LinkedIn:** [in/ishika-tyagimedicalcoder](https://www.linkedin.com/in/ishika-tyagimedicalcoder)
- **Location:** Noida, Uttar Pradesh, India

---

© 2025 Ishika Tyagi · All rights reserved
