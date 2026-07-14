# Sharanya B — Portfolio

A single-page developer portfolio designed to look and read like **API documentation** — because that's literally what I build. Each section of the page (About, Experience, Projects, Skills, Education, Certifications, Contact) is presented as an endpoint, complete with method badges, status codes, and JSON-style response panels.

🔗 **Live demo:** _add your deployed link here_

---

## Why this theme

Most of my work involves designing and consuming REST APIs — Django REST Framework, Flask, and FastAPI. Instead of a generic template, I wanted the portfolio itself to reflect that: browsing it should feel like reading through a small API's docs.

- `GET /about` → bio and background
- `GET /experience` → work history
- `GET /projects` → project records
- `GET /skills` → tech stack schema
- `GET /education` → academic records
- `GET /certifications` → certification list
- `POST /contact` → ways to reach me

---

## Tech Stack

- **HTML5** — semantic single-page structure
- **CSS3** — custom properties (CSS variables) for full theme control, responsive grid/flexbox layout, no external CSS framework
- **Vanilla JavaScript** — minimal, used only for smooth-scroll navigation
- **Fonts** — [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) and [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) via Google Fonts

No build tools, no dependencies, no framework — it's a single `.html` file that runs anywhere.

---

## Features

- Sidebar navigation styled like an API endpoint list (collapses to a top bar on mobile)
- Fully responsive layout (desktop, tablet, mobile breakpoints)
- Theming via CSS custom properties — swap the color palette by editing a handful of variables in `:root`
- Project cards with tag chips for tech stack at a glance
- Contact panel with Email, Phone, GitHub, LinkedIn, Portfolio, and Resume links

---

## Project Structure

```
├── sharanya_portfolio.html   # the entire site — structure, styles, and script in one file
├── resume.pdf                # (add your own) resume file linked from the Contact section
└── README.md
```

---

## Running Locally

No setup required.

```bash
git clone https://github.com/YOUR-USERNAME/portfolio.git
cd portfolio
open sharanya_portfolio.html   # or just double-click the file
```

---

## Customizing

- **Colors:** edit the CSS custom properties inside `:root` at the top of the `<style>` block (`--bg`, `--text`, `--accent-get`, `--accent-warn`, `--accent-blue`, etc.)
- **Content:** update the `#about`, `#experience`, `#projects`, `#skills`, `#education`, `#certifications`, and `#contact` sections directly in the HTML
- **Links:** replace the placeholder `YOUR-USERNAME` values in the Contact section with your real GitHub and LinkedIn URLs, and add `resume.pdf` alongside the HTML file for the Resume download link to work

---

## Deploying

Since it's a static single HTML file, it can be hosted for free on:

- **GitHub Pages** — push to a repo, enable Pages in settings, point it at the HTML file
- **Netlify / Vercel** — drag and drop the file, done

---

## Contact

- **Email:** sharanyabaleguli@gmail.com
- **Phone:** +91 96064 98369
- **Location:** Bangalore, India
