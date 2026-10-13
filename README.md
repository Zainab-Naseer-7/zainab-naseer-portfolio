# ZAINAB NASEER — SIGNATURE DIGITAL UNIVERSE

A bespoke, production-ready, luxury personal portfolio and digital brand experience for **Zainab Naseer** (BSIT Student, Web Developer, and Graphic Designer based in Lahore, Pakistan).

Designed with the aesthetic precision of a luxury design studio, the technical discipline of a senior frontend engineer, and zero external build framework dependencies.

---

## ✦ Brand Identity & Creative Direction

| Attribute | Specification |
| :--- | :--- |
| **Full Name** | Zainab Naseer |
| **Professional Title** | BSIT Student \| Web Developer \| Graphic Designer |
| **Location** | Lahore, Pakistan |
| **WhatsApp Direct** | [+92 300 4462924](https://wa.me/923004462924) (`0300 4462924`) |
| **LinkedIn Profile** | [linkedin.com/in/zainab-naseer-12b29641b](https://www.linkedin.com/in/zainab-naseer-12b29641b) |
| **GitHub Profile** | [github.com/Zainab-Naseer-7](https://https://github.com/Zainab-Naseer-7) |
| **GitHub Username** | `Zainab-Naseer-7` |
| **Official Email** | [naturalstar848@gmail.com](mailto:naturalstar848@gmail.com) |

### Color Palette
- **Deep Obsidian:** `#080D18` (Primary background atmosphere)
- **Midnight Navy:** `#0B1220` (Surface foundation & cards)
- **Metallic Gold:** `#D6B36A` (Signature metallic accent, gradients & emblems)
- **Warm White:** `#FAFAF8` (High-contrast typography)
- **Soft Neutral:** `#E8EAF0` / `#C8CEDC` (Readable secondary prose)

---

## ✦ File Structure (Flat Root - Zero Subdirectories)

All files reside directly in the project root directory:

```text
├── index.html        # Complete semantic HTML5 structure, SEO metadata, JSON-LD Schema
├── style.css         # Master Vanilla CSS design system, dark/light themes, responsive layout
├── script.js         # Production Vanilla JS: GitHub REST API, theme engine, WhatsApp handler
├── logo.svg          # Primary horizontal luxury logo (monogram + wordmark)
├── monogram.svg      # Bespoke standalone geometric ZN monogram (512x512)
├── favicon.svg       # Crisp vector browser favicon
├── avatar.svg        # Square luxury social avatar (500x500)
├── README.md         # Complete documentation, setup, CV config, deployment guide
└── Zainab_Naseer_CV.pdf (Drop your authentic CV PDF here)
```

---

## ✦ Key Features & Systems

### 1. Original Luxury ZN Logo & Monogram
- Scalable vector graphics constructed from geometric intersecting lines combining **Z** and **N**.
- Includes primary horizontal mark (`logo.svg`), compact monogram (`monogram.svg`), browser favicon (`favicon.svg`), and square social avatar (`avatar.svg`).

### 2. Live GitHub Project Ecosystem & In-Page Website Previewer
- Direct integration with GitHub's REST API endpoint:
  ```
  https://api.github.com/users/Zainab-Naseer-7/repos?sort=updated&direction=desc&per_page=100
  ```
- **Real-time Synchronization & Resilient Showcase:** Public repositories created by `@Zainab-Naseer-7` appear automatically with offline/rate-limit fallback to curated projects.
- **Dynamic Language Filter Pills:** Automatically extracts programming languages from repositories and builds interactive filter buttons.
- **Live Search & Sorting:** Instant filtering across repository title, description, and topics. Sort by "Recently Updated", "Most Stars", or "Alphabetical".
- **Interactive In-Page "Live Demo" Modal:** Every project features a glowing "Live Demo" button. Clicking opens an embedded live website preview modal right on the portfolio without navigating away.
- **Multi-Device Viewport Tester:** Allows visitors to test responsiveness right inside the live demo modal with 1-click Desktop (100%), Tablet (768px), and Mobile (375px) frame simulations.
- **Quick Controls:** Top toolbar includes "Open in New Tab", "Refresh Preview", and Esc / Backdrop close support.
- **Local Caching:** Caches data in `localStorage` (15-minute TTL) for instantaneous subsequent visits.

### 3. WhatsApp-First Direct Contact System
- Direct WhatsApp action buttons with prefilled message:
  ```
  "Hello Zainab, I visited your portfolio and would like to discuss a project or professional opportunity."
  ```
- Form validation with real-time feedback and truthful submission routing (pre-fills default email client or allows instant WhatsApp dispatch).

### 4. Elite Dark / Light Mode
- One-click toggle with animated Sun & Moon icons.
- System color preference detection (`prefers-color-scheme`).
- Instant restoration on page refresh via `localStorage` and zero-flash inline script.

### 5. Academic & Experience Timelines (Authentic CV Data)
- **Education:**
  - BS Information Technology (BSIT) — Government MAO College (Present / Enrolled)
  - Intermediate — Ayesha Graduate College (2023–2025)
  - Matriculation — Government MCL School (2021–2023)
- **Professional Experience:**
  - Teaching Experience (2 Years) — The Great Vision School System
  - Highlighting instructional clarity, classroom organization, and leadership.
- **Skills Categorization:**
  - *Development:* Web Development, Responsive UI, Semantic HTML5, CSS3, JavaScript.
  - *Creative:* Graphic Designing, Visual Composition, Digital Typography, Color Theory.
  - *Productivity:* Microsoft Office Suite (Word, PowerPoint, Excel).
- **Languages & Strengths:**
  - Urdu (Native/Fluent), English (Good).
  - Good Communication, Classroom Management, Student Engagement, Patience, Teamwork, Quick Learner.
- **Achievements:**
  - Consistent Academic Performance.

---

## ✦ How to Configure Your Authentic CV (PDF)

To enable one-click CV downloads:
1. Save your official CV as:
   ```text
   Zainab_Naseer_CV.pdf
   ```
2. Place this file directly in the same folder as `index.html`.
3. Visitors clicking **"Download CV"** will immediately receive the file. If not yet placed, an informational modal guides the visitor.

---

## ✦ How to Configure Your Official Email

Open [script.js](file:///c:/Users/Naveedkhan/Desktop/new%20portfolio/script.js) and update the `CONFIG` object at line 14:

```javascript
const CONFIG = {
  // ...
  emailAddress: 'naturalstar848@gmail.com', // Active verified email
  // ...
};
```

---

## ✦ Deployment Instructions (Zero Build Tools Needed)

Because this website uses 100% Vanilla HTML5, CSS3, and JavaScript with flat root assets, it runs anywhere without needing `npm install` or compilation.

### Option A: GitHub Pages
1. Push all files to a repository on GitHub (e.g. `https://github.com/Zainab-Naseer-7/portfolio`).
2. Go to repository **Settings** → **Pages**.
3. Under **Branch**, select `main` (root) and click **Save**.
4. Your website is live in seconds at `https://zainab-naseer-7.github.io/portfolio/`.

### Option B: Netlify or Vercel
- Drag and drop this folder directly into the Netlify or Vercel dashboard.

---

## ✦ Standards & Accessibility
- **Semantic HTML5:** Correct document outline (`header`, `nav`, `main`, `section`, `article`, `footer`).
- **WCAG AA Contrast:** Accessible color contrast in both dark and light modes.
- **Keyboard Navigation:** Skip link (`#main-content`), focus outlines, ARIA labels on all icons.
- **Motion Accessibility:** Automatically respects `prefers-reduced-motion`.
- **Search Engine Optimization (SEO):** Open Graph, Twitter cards, meta tags, and schema.org `Person` JSON-LD.
