# Niladri Dey — Developer Portfolio

A personal portfolio website of me, built to showcase development work, technical strengths, and project thinking in a polished, responsive front-end experience.

Live demo: https://techieniladri.github.io/niladridey_portfolio/

## Overview

This project is a static portfolio website designed for personal branding and job-focused outreach. It highlights:

- frontend and product-focused development work
- core technologies and project experience
- a practical development process and engineering mindset
- direct contact and social links for recruiters and collaborators

The site is intentionally lightweight and dependency-free, using HTML, CSS, and vanilla JavaScript to deliver a modern single-page portfolio without requiring a build toolchain.

## Why This Project Exists

The site serves as a digital resume and portfolio, helping visitors quickly understand:

- who am I
- what kind of work I build
- which technologies I have used
- what kinds of products and experiments I am exploring

It is especially useful for:

- recruiters evaluating frontend and full-stack potential
- collaborators exploring project fit
- employers evaluating design and engineering sensibility

## Featured Projects

### Productivity Garden
A task-to-plant productivity concept where user progress maps to a growing habit loop. It is currently a private development project and does not yet have a public live demo.

### Neural-Decider
An AI-assisted reflection experiment where users respond to scenarios and receive reflective output. This project is publicly available and includes a live experiment link.

- Live demo: https://decision-timer.vercel.app/
- GitHub: https://github.com/techieNiladri/Neural-Decider

### Iron-Forge
A workout-tracking prototype built around Node.js, Express, and PostgreSQL for recording exercises and workout data. It is still in early prototype stages.

- GitHub: https://github.com/techieNiladri/Iron-Forge

### Keeper App
A responsive notes application built with React and UI components for managing notes with add and delete interactions.

- GitHub: https://github.com/techieNiladri/KeeperApp
- Live demo: https://techieniladri.github.io/KeeperApp/

## Tech Stack

This project uses a simple static front-end stack:

- HTML5 for structure and semantics
- CSS3 for layout, responsiveness, design system, animation, and styling
- Vanilla JavaScript for interactions, scroll effects, navigation, and UI behavior
- Google Fonts for typography
- GitHub Pages for deployment

## Key Features

- Responsive layout optimized for desktop, tablet, and mobile
- Animated hero and reveal-based scroll interactions
- Project showcase cards with live/demo links
- Accessible UI patterns and semantic structure
- Smooth scrolling and mobile navigation drawer
- Clean, modern visual style with custom design tokens
- No framework dependency or build step required

## Project Structure

```text
niladridey_portfolio/
├── index.html
├── README.md
├── .gitignore
├── .gitattributes
├── assets/
│   ├── neural-decider-screenshot.png
│   ├── keeperapp-screenshot.png
│   └── niladri-dey-cv.pdf
└── .github/  (if present in future workflows or Pages config)
```

## Running Locally

Because this is a static site, there is no install or build step required.

### Option 1: Open directly
Open `index.html` in a browser.

### Option 2: Run a local static server

```bash
git clone https://github.com/techieNiladri/niladridey_portfolio.git
cd niladridey_portfolio
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploying with GitHub Pages

This repository is already configured to use GitHub Pages, and the site is accessible through the live link above.

If you need to redeploy:

1. Push the latest changes to the `main` branch.
2. Ensure GitHub Pages is enabled for the repository.
3. Confirm the project is published from the repository root or the expected branch.

## CV Download

The portfolio includes a downloadable CV button that links to the CV asset in the `assets/` folder.

## Design and Engineering Notes

The site is designed to balance professionalism with personality. It avoids heavy dependencies and instead focuses on:

- clean information hierarchy
- strong visual identity
- accessible interactions
- a clear, portfolio-oriented narrative

This makes the project easy to host, easy to understand, and easy to maintain.


- leave the project unlicensed, or
- add MIT if they want the code to be reusable by others.

## Contact

- GitHub: https://github.com/techieNiladri
- LinkedIn: https://www.linkedin.com/in/niladri-dey-280710d/
- Email: mailto:deyniladri937@gmail.com

## About the Author

I am a developer based in Kolkata, India, exploring frontend, backend, and product-oriented development work. The portfolio reflects my practical engineering mindset: clear interfaces, meaningful functionality, and learning through real projects.

---

Built with intent.
