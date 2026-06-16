# Portfolio Project

A clean, responsive developer portfolio built with **HTML**, **CSS**, and **vanilla JavaScript** (no frameworks). It features a modern dark theme, sticky navigation, and a scalable projects section using reusable card styles.

---

## Live Preview
Open `index.html` in your browser:

- **macOS / Windows:** double-click `portfolio_project/index.html`
- Or run a simple local server (optional):
  - `python3 -m http.server 5500`
  - then visit: `http://localhost:5500/portfolio_project/`

---

## Key Features
- **Dark, modern UI** with a teal/blue accent gradient background.
- **Sticky navigation** with smooth scrolling to sections.
- **Responsive layout** using CSS Grid and Flexbox.
- **Mobile-friendly menu** (toggle button with `aria-expanded` support).
- **Reusable Projects cards** (`.project-card`) designed to scale as you add more work.
- **Accessibility improvements**
  - “Skip to content” link
  - semantic sections (`header`, `main`, `section`, `footer`)
- **Lightweight JavaScript**
  - Updates footer year dynamically
  - Handles the mobile nav toggle

---

## Technologies Used
- **HTML** (semantic structure, navigation, content sections)
- **CSS** (themes, layout, responsive design, animations)
- **Vanilla JavaScript** (nav toggle + footer year)
- **Bootstrap Icons** (via CDN for footer/contact icons)

---

## Project Structure
```
portfolio_project/
├── index.html
├── README.md
├── css/
│   └── style.css
└── assets/
    └── images/
        └── IMG_0772.png
```

---

## Sections Overview
- **Home (Hero):** Profile image, name/title, short intro, CTA buttons (resume placeholder + LinkedIn).
- **About:** Background, technologies, and a tech badge list.
- **Skills:** Categorized skill groups shown as pill badges.
- **Projects (“My Works”):** A grid of reusable `.project-card` components (image, description, stack pills, and a “View Project” link).
- **Contact:** Email, phone, and social links (LinkedIn + GitHub).

---

## Customization Notes
- **Resume button:** in `index.html`, update the resume link (`href="#"`) to your real file URL if you add one.
- **Social links:** update LinkedIn/GitHub URLs (both in the header/contact and footer).
- **Contact info:** edit email/phone values in the Contact section.
- **Add projects:** copy an existing `<article class="project-card"> ... </article>` block inside the `#projects .projects-grid` container and replace the image/text/links.

---

## Credits
Icons are provided using the **Bootstrap Icons** CDN.


