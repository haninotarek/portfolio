<h1 align="center">Hanin Tarek — Personal Portfolio</h1>

<p align="center">
  A modern, fully responsive personal portfolio website built with vanilla
  <strong>HTML</strong>, <strong>CSS</strong>, and <strong>JavaScript</strong>.<br />
  Designed with a soft purple palette, glassmorphism, and smooth motion.
</p>

<p align="center">
  <a href="https://haninotarek.github.io/portfolio/">
    <img alt="Live Demo" src="https://img.shields.io/badge/Live%20Demo-7c3aed?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img alt="Responsive" src="https://img.shields.io/badge/Responsive-A78BFA?style=for-the-badge&logo=responsive&logoColor=white" />
  <img alt="License" src="https://img.shields.io/badge/License-MIT-6d28d9?style=for-the-badge" />
</p>

<hr />

## Overview

A clean, single-page portfolio designed for a Computer Science student and aspiring UI/UX Designer & Frontend Developer. The site showcases professional information, skills, projects, certifications, and a working contact form — all in a single static bundle that loads fast and deploys anywhere.

It is built with **zero dependencies** and **no build step**: just open `index.html` and you're live.

<hr />

## Features

### Design
- Soft purple + white color palette with full dark-mode support
- Glassmorphism cards with soft shadows and rounded corners
- Elegant typography using **Inter** and **Poppins** from Google Fonts
- Animated SVG-style background blobs and gradients
- Consistent design language across every section

### User Experience
- Fully responsive layout for desktop, tablet, and mobile
- Smooth scrolling with section-aware navigation
- Active navbar link highlighting while scrolling
- Hamburger menu with slide-in panel on mobile
- Scroll-to-top floating button
- Page loading animation
- Reduced-motion friendly for accessibility

### Interactivity
- **Typing animation** in the hero cycling through roles
- **Scroll reveal** animations for every section
- **Animated skill bars** that fill on viewport entry
- **Animated stat counters** that count up when visible
- **Dark / Light mode toggle** with preference saved to `localStorage`
- Smooth hover effects on cards, buttons, chips, and social icons
- Functional contact form with validation and mailto fallback

### Code Quality
- Semantic, accessible HTML5
- Organized CSS with custom properties (CSS variables)
- Mobile-first responsive design via clean media queries
- Vanilla JS — no frameworks, no bundlers, no dependencies
- Commented sections for easy customization
- SEO-friendly meta tags + Open Graph

<hr />

## Tech Stack

| Layer        | Technology |
|--------------|-------------|
| Markup       | HTML5 (semantic) |
| Styling      | CSS3 (variables, grid, flexbox, glassmorphism) |
| Scripting    | Vanilla JavaScript (ES6+) |
| Typography   | Google Fonts (Inter, Poppins) |
| Icons        | Font Awesome 6 |
| Deployment   | GitHub Pages |

<hr />

## Sections

1. **Hero** — Name, animated role titles, intro, CTAs, social links, profile photo
2. **About** — Education, development, design cards + bio with live stats
3. **Skills** — Frontend, Backend, Programming, UI/UX, Database, Data & Analytics, Tools, Other
4. **Projects** — Featured projects with technologies and GitHub links
5. **Certifications** — Earned certificates and program participations
6. **Activities** — Competitive programming and extracurriculars
7. **Contact** — Direct contact info, social links, working contact form
8. **Footer** — Branding, copyright, social icons

<hr />

## Project Structure

```
HaninPortfolio/
├── index.html              # Main page — every section is clearly commented
├── styles.css              # Design system + components + responsive rules
├── script.js               # Interactivity (typing, theme, reveal, form, etc.)
├── README.md               # You are here
├── .gitignore
└── assets/
    ├── CV-HaninTarek.pdf   # CV linked from the "Download CV" button
    ├── profile.png         # Profile photo (drop your image here)
    └── README.txt          # Notes on the assets folder
```

<hr />

## Getting Started

### Run locally

The simplest way:

```bash
# Just open the file in any browser
open index.html
```

For a development server with live-reload:

```bash
npx serve .
# or use the VS Code "Live Server" extension
```

### Add your profile photo

1. Save your photo as `profile.png` (a square image around 500×500 px works best).
2. Place it inside the `assets/` folder.

If the file is missing, a styled placeholder is shown automatically.

<hr />

## Customization

All content is in plain HTML — no templating engine required.

| What you want to change | Where to edit |
|--------------------------|---------------|
| Name, intro, role titles | `index.html` → Hero section |
| About text, stats | `index.html` → About section |
| Skills and levels | `index.html` → Skills section (edit `data-fill` for percentages) |
| Projects | `index.html` → Projects section |
| Certifications | `index.html` → Certifications section |
| Contact email / social links | `index.html` (search for `haninotarek`) |
| Colors / theme | `styles.css` → `:root` CSS variables at the top |
| Typing roles | `script.js` → `phrases` array |

<hr />

## Deployment to GitHub Pages

1. Create a new **public** repository on GitHub.
2. From inside the project folder, run:

   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. On GitHub: open **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main` / `(root)`
5. Wait ~1 minute. Your portfolio is live at:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

<hr />

## Accessibility

- Semantic HTML landmarks (`<header>`, `<main>`, `<section>`, `<footer>`)
- Sufficient color contrast in both light and dark themes
- Visible keyboard focus styles
- ARIA labels on icon-only buttons and navigation
- `prefers-reduced-motion` support to disable animations for users who request it

<hr />

## Browser Support

Works on all modern browsers:

- Chrome / Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile Safari & Chrome on Android

<hr />

## Contact

- **Email:** [haninotarek222@gmail.com](mailto:haninotarek222@gmail.com)
- **GitHub:** [@haninotarek](https://github.com/haninotarek)
- **LinkedIn:** [hanin-tarek](https://www.linkedin.com/in/hanin-tarek-04900230b)

<hr />

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT). Feel free to fork it as a starting point for your own portfolio.

<hr />

<p align="center">
  Built with care by <strong>Hanin Tarek</strong> &middot; 2026
</p>
