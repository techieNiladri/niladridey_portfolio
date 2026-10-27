# Niladri Dey Portfolio

<div align="center">

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Interactive-8B5CF6?style=for-the-badge&logo=githubpages&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> I built this portfolio around clarity, thoughtful design, and the software I’m learning to ship.

</div>

I use this site to introduce my work, show how I approach building software, and make it easy to explore my projects or contact me.

**Live site:** https://techieniladri.github.io/niladridey_portfolio/

## What I share

- I show projects I’ve built and products I’m actively developing.
- I describe the tools I’ve used and the work they support.
- I share how I approach planning, implementation, and refinement.
- I provide direct links to my demos, source code, and contact details.

I built the site as a responsive single page using HTML, CSS, and vanilla JavaScript. I kept it dependency-free and deploy it with GitHub Pages.

## Featured work

### Productivity Garden

I’m developing Productivity Garden as a full-stack MVP that turns tasks into seeds. I can plant a seed with a task, let it grow through a five-stage, 20-minute cycle, then harvest it after completing the task. Completing tasks unlocks higher-tier plant rewards.

I’m building it with JavaScript, Vite, Supabase Auth, PostgreSQL, row-level security, and PostgreSQL RPCs. I added database integrity constraints and a transactional `plant_seed()` RPC, then integrated and tested it through the authenticated frontend. I’m hardening edge cases before deployment. The project is private and does not yet have a public demo.

### Neural-Decider

I built Neural-Decider as an AI-assisted reflection experiment. I use choice-based scenarios to generate reflective responses and visual summaries. I present it as an exploration, not a validated psychological assessment.

- **Live demo:** https://decision-timer.vercel.app/
- **Source code:** https://github.com/techieNiladri/Neural-Decider

### Iron-Forge

I started Iron-Forge as a workout tracker for recording exercises, weights, and reps. I’ve worked on its Node.js and Express API, PostgreSQL schema, and frontend entry flow. I’m still refining the integration and deployment, so I don’t list a live demo yet.

- **Source code:** https://github.com/techieNiladri/Iron-Forge

### Keeper App

I built Keeper App with React and Material UI so I can add and delete notes in a responsive interface. Notes currently stay in page state and do not persist after a refresh.

- **Live demo:** https://techieniladri.github.io/KeeperApp/
- **Source code:** https://github.com/techieNiladri/KeeperApp

## My services site

I also built Aetheris, my live multi-page services site, to present the websites I can build, my process, and ways to contact me.

- **Live site:** https://techieniladri.github.io/Aetheris/
- **Source code:** https://github.com/techieNiladri/Aetheris

## How I built this portfolio

- I use HTML5 for structure and semantics.
- I use CSS for layout, responsive styling, design tokens, and animation.
- I use vanilla JavaScript for interactions, navigation, and interface behavior.
- I use Google Fonts for typography.
- I host the site with GitHub Pages.

I focused on accessible interactions, a responsive layout, direct project links, and a mobile navigation drawer. I don’t need a framework, package installation, or build step to run this site.

## Project structure

```text
niladridey_portfolio/
├── index.html
├── README.md
├── .gitignore
├── .gitattributes
└── assets/
    ├── neural-decider-screenshot.png
    ├── keeperapp-screenshot.png
    └── niladri-dey-cv.pdf
```

## Run locally

I can open `index.html` directly, or start a local server:

```bash
git clone https://github.com/techieNiladri/niladridey_portfolio.git
cd niladridey_portfolio
python -m http.server 8000
```

Then I open http://localhost:8000 in a browser.

## Publish an update

I publish updates by pushing to the `main` branch and checking the live site.

## CV

I keep my downloadable CV in `assets/niladri-dey-cv.pdf` and link to it from the site.

## Contact

- **Portfolio:** https://techieniladri.github.io/niladridey_portfolio/
- **My services site:** https://techieniladri.github.io/Aetheris/
- **GitHub:** https://github.com/techieNiladri
- **LinkedIn:** https://www.linkedin.com/in/niladri-dey-280710d/
- **Email:** deyniladri937@gmail.com

## About me

I’m a developer based in Kolkata, India, exploring frontend, full-stack, backend, and product-oriented work. I care about clear interfaces, useful functionality, and learning by building real projects.

I built this portfolio with intent, and I’ll keep it aligned with the work I can show.
