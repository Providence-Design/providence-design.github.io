# My Portfolio Site

Live at: [providencedesign.github.io](https://providencedesign.github.io)

---

## Why I built this

I needed a proper portfolio link for job and volunteer applications and all I had was an old PDF sitting in a GitHub repo. Not exactly the most impressive thing to share. So I decided to build something real — a site that actually represents who I am and what I do.

---

## How I approached it

I kept it simple and clean. No frameworks, no build tools, no unnecessary complexity. Just HTML, CSS, and a bit of thought about structure.

The first thing I did was separate concerns properly:

```
portfolio/
├── index.html        # structure and content
├── css/
│   └── styles.css    # all the styling lives here
└── assets/
    └── Providence_Annor_Asemah_CV.pdf   # downloadable CV
```

I could have thrown everything into one file and called it a day, but that felt sloppy. Keeping the HTML and CSS separate makes it easier to maintain, easier to read, and honestly just better practice.

---

## What I focused on

**Design** — I went with a dark theme, clean typography using DM Sans and DM Mono, and a green accent colour. I wanted it to feel like something a DevOps/cloud engineer would actually build — minimal, intentional, no fluff.

**Content** — The site covers my work experience, skills, projects, education, and contact details. Everything pulled directly from my CV and kept up to date.

**Usability** — Sticky navigation, smooth scroll, a download button for the CV, and responsive layout so it works on mobile too.

**Performance** — No JavaScript frameworks. No bloat. The whole site loads fast because there is nothing unnecessary in it.

---

## Tech used

- HTML5
- CSS3 (custom properties, grid, flexbox, animations)
- Google Fonts — DM Sans + DM Mono
- GitHub Pages for hosting

---

## How to run it locally

Clone the repo and open `index.html` in your browser. That is genuinely all there is to it.

```bash
git clone https://github.com/ProvidenceDesign/ProvidenceDesign.github.io.git
cd ProvidenceDesign.github.io
open index.html
```

---

## Deploying updates

Any push to the `main` branch automatically updates the live site via GitHub Pages. No CI/CD pipeline needed for something this straightforward though I did consider it out of habit.

---

## What I would add next

- A proper projects section with links to repos and live demos
- Maybe a blog for writing about things I learn on the job
- Dark/light mode toggle

---

Built by [Providence Annor Asemah](https://linkedin.com/in/providence-annor-asemah) · DevOps & Cloud Platform Engineer · Accra, Ghana
