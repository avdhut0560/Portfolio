# Avdhut Gaikwad | Portfolio Website

A responsive personal portfolio and resume website for **Avdhut Yogesh Gaikwad (Av Gaikwad)**, B.Tech student at Sanjivani University, Kopargaon, Maharashtra.

## Features

- Modern dark UI with glass-card design (Tailwind CSS)
- Sections: Hero, About, Achievements, Skills (filterable), Education, Contact
- **Download Resume** button (navbar, hero section and mobile menu)
- One-click "Copy Email" with toast notification
- Fully responsive, with a mobile menu
- Pure static site: no build step, no dependencies to install

## Project Structure

```
.
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── profile.jpg
    ├── Avdhut_Gaikwad_Resume.pdf
    └── Avdhut_Gaikwad_Resume.jpg
```

## Run Locally

Open `index.html` in any browser, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on GitHub Pages

```bash
git init
git add .
git commit -m "Initial commit: portfolio website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo>.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save.**
Your site will be live at `https://<your-username>.github.io/<your-repo>/` in about a minute.

## Updating the Resume

Replace `assets/Avdhut_Gaikwad_Resume.pdf` with your new file (keep the same name) and push the change. The download buttons will serve the new file.

## Tech Stack

HTML5, Tailwind CSS (CDN), Lucide Icons, Google Fonts, vanilla JavaScript.

## Contact

- Email: avdhut0560@gmail.com
- Location: Kopargaon, Maharashtra, India

## License

© 2026 Avdhut Gaikwad. All rights reserved.
