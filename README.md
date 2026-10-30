# EEEE3134 Personal Portfolio — Version 1

A responsive, single-page English portfolio for Yueqi Zhao, an Electrical and Electronic Engineering student at the University of Nottingham Ningbo China. This AI-generated Version 1 portfolio is built with HTML, CSS, and vanilla JavaScript. No build step, backend, API keys, packages, or external assets are required.

## Files

- `index.html`: Home, About Me, Areas of Expertise & Interest, five Featured Projects, Technical Skills, and Contact.
- `style.css`: Responsive layouts, engineering-inspired illustrations, and reduced-motion support.
- `script.js`: Mobile navigation, active section indication, project filtering, and the footer year.

## Preview locally

Open `index.html` directly in a browser, or run the following from this folder:

```sh
python3 -m http.server 8000
```

Then visit **http://localhost:8000**. Stop the server with `Ctrl+C`.

## Portfolio content

The portfolio presents Yueqi Zhao's verified academic background, expected June 2027 graduation, engineering interests, technical skills, and five projects spanning autonomous robotics, Doppler radar signal processing, power electronics, research software, and IoT coursework. The Contact section includes the supplied email address and GitHub profile. Project descriptions are limited to the provided scope and outcomes; no publications, awards, unsupported metrics, or commercial claims are included.

## Deploy to GitHub Pages

1. Create a GitHub repository and upload these four files to its root.
2. Open **Settings → Pages** in the repository.
3. Choose **Deploy from a branch**, select your default branch (usually `main`) and **/(root)**, then save.
4. After deployment, open the URL shown by GitHub Pages, normally `https://USERNAME.github.io/REPOSITORY/`.

All asset links are relative, so the site supports GitHub Pages project subpaths. Publishing is a separate step; this workspace contains the source only.

## Accessibility and behaviour

- Semantic sections, a skip link, visible keyboard focus, and responsive typography.
- Mobile menu exposes its expanded state, closes after navigation, and supports Escape.
- Project filters expose selected states and announce the number of visible projects.
- Project scope expands using native keyboard-accessible disclosure controls.
- With JavaScript disabled, navigation and all project content remain accessible.
- No analytics, cookies, tracking, external fonts, or network requests are used.

## Suggested manual checks

Preview at mobile and desktop widths. Tab through navigation and project controls; test Escape on the mobile menu, each filter, project disclosures, and anchor destinations. Enable reduced motion in your system settings and confirm that scrolling is immediate.
