# Ranz Cuarto | Portfolio

[![Live site](https://img.shields.io/badge/Live-rnzcrt.github.io-ff3b1d)](https://rnzcrt.github.io)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/Hosted_on-GitHub_Pages-222222?logo=github&logoColor=white)
[![Made with AI](https://img.shields.io/badge/Made_with-AI_assistance-blue)](#ai-credits)

Personal portfolio of **Ranz Emmanuel G. Cuarto**, a BS Computer Science student at Holy Angel University, Angeles City, Philippines. I'm looking for an **OJT in IT Support or QA Testing**.

🔗 **Live site:** [rnzcrt.github.io](https://rnzcrt.github.io)

## Screenshots

<table>
<tr>
<td align="center"><img src="docs/screenshots/hero-desktop.png" width="420" alt="Hero section on desktop"><br><sub>Hero (desktop)</sub></td>
<td align="center"><img src="docs/screenshots/projects-desktop.png" width="420" alt="Projects section on desktop"><br><sub>Projects (desktop)</sub></td>
</tr>
<tr>
<td align="center" colspan="2"><img src="docs/screenshots/mobile.png" width="200" alt="Site on a phone"><br><sub>Mobile</sub></td>
</tr>
</table>

## What's on the site

- **Approach:** how I work: reproduce before fixing, test against requirements, document honestly, review what AI produces
- **Projects:** PriceWatch PH, LaundryLog, BudgetBlud, and HAU Pokémon, each with the stack I used, my role, and links
- **At a glance:** a few facts about where I am now, plus my certifications
- **Contact:** email, GitHub, and LinkedIn

## Tech

A single static page with no build step and no framework.

| Area | Details |
| --- | --- |
| Markup and styles | HTML5 and hand-written CSS (rem-based layout that scales with screen width, light motion with `prefers-reduced-motion` support) |
| Behavior | Vanilla JavaScript: letter-by-letter hero reveal, scroll-triggered reveals (`IntersectionObserver`), looping marquee |
| Fonts | [Anton](https://fonts.google.com/specimen/Anton) and [Onest](https://fonts.google.com/specimen/Onest) from Google Fonts |
| Hosting | GitHub Pages, served from the `main` branch |

## Project structure

```
rnzcrt.github.io/
├── index.html          # the whole site: markup, CSS, and JavaScript
├── docs/screenshots/   # images used in this README
└── README.md
```

## Run locally

No installation needed. Clone the repo and open the file in a browser:

```bash
git clone https://github.com/rnzcrt/rnzcrt.github.io.git
cd rnzcrt.github.io
open index.html        # macOS; on Windows use: start index.html
```

The page loads its fonts from Google Fonts, so it needs an internet connection to look right.

## Deploy

1. Keep the repository public and named exactly `rnzcrt.github.io`.
2. Go to **Settings → Pages**, set **Source** to **Deploy from a branch**, then choose `main` and `/ (root)`.
3. The site goes live at `https://rnzcrt.github.io` about a minute after each push.

## Design credit

The visual style (dark background, large condensed red headline, scroll reveals) was inspired by a cinematic one-page portfolio design reference. All content, copy, and project details are my own.

## AI Credits

AI tools were used to help build this site and to draft this README. I reviewed the content, and the project descriptions match what is in each project's repository.

## Contact

- Email: [cuartoranz@gmail.com](mailto:cuartoranz@gmail.com)
- GitHub: [github.com/rnzcrt](https://github.com/rnzcrt)
- LinkedIn: [ranz-cuarto](https://www.linkedin.com/in/ranz-cuarto)
