# Yashasree Kaasula — Interactive Portfolio

Responsive dark developer portfolio built using public information from [GitHub](https://github.com/yashasreekaasula) and a limited publicly indexed [LinkedIn profile](https://www.linkedin.com/in/yashasree-kaasula-b1a447312/).

## Features
- Animated hero, subtle particle background, mouse-tilt code card, scroll reveals
- Live project search, category filters and project detail dialogs
- Keyboard command palette (Ctrl+K / Cmd+K), light/dark theme memory, mobile menu
- Responsive accessible UI, reduced-motion support, copied link notification
- 8 real GitHub repository links
- No frontend dependencies or build process

## Run locally
1. Install Node.js 20 or later.
2. Open a terminal in this folder.
3. Run `npm start` and open http://localhost:3000.

## Deploy on Render (Web Service)
1. Extract the ZIP. Upload the **contents** of `yashasree-portfolio` to a new GitHub repository (or push with Git).
2. On render.com choose **New → Web Service → Connect repository**.
3. Environment: **Node**. Build command: `npm install`. Start command: `npm start`. Instance: **Free**, if available.
4. Deploy. Render supplies `PORT` and a `*.onrender.com` address.
5. Alternatively use **New → Blueprint** with `render.yaml`.

## Edit portfolio content
- `public/projects.json`: descriptions, repository links, project tags.
- `public/index.html`: hero bio, education, skills, contact links.
- `public/styles.css`: design.
- `public/app.js`: interactions.

## Verification notes
- All 8 project names and links came from publicly discoverable GitHub repositories. Several repositories are empty or have no accessible README; their summaries are conservative, based on the titles only. The descriptive exam evaluator README was accessible but its author line references another person, so this site does not claim sole authorship.
- LinkedIn's indexed public view confirms Amrita enrollment and Coimbatore. Employment and publications were **not publicly verifiable**, so no unsupported employers or publication claims were added.
- Programming skills and education details are editable and partly derived from previously supplied resume content. Review before publishing.
- No resume download button is included because no specific Yashasree resume file was supplied in this task.
- Project data is stored locally; the site does not automatically sync with GitHub.


## Retro theme update
The homepage includes the locally bundled portrait at `public/images/yashasree-portrait.webp`.
Palette and editorial styling are in `public/retro.css`. The original interactive projects,
search, dialogs, mobile navigation and theme switch remain available.
To run locally: `npm install && npm start`, then visit `http://localhost:3000`.
