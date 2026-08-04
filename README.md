# Atharva Hatolkar — Personal Portfolio

Source for my personal portfolio site, live at **[hatolkarav.github.io](https://hatolkarav.github.io)**.

A single-page site covering my work in data science and machine learning — with a focus on time-series forecasting and foundation models — alongside my experience, skills, and a downloadable CV.

## Built With

- Static **HTML / CSS / JavaScript** (no framework, no build step)
- Custom dark editorial design with a signal-amber accent
- Hosted on **GitHub Pages**

## Repository Structure

```
hatolkarav.github.io/
├── index.html                 # The portfolio site (all markup, styles, and script inline)
├── Atharva-Hatolkar-CV.pdf    # CV, linked from the site's "View CV" button
└── README.md
```

> The "View CV" button links to `./Atharva-Hatolkar-CV.pdf`, so that file must sit in the repo root with that exact name (GitHub Pages is case-sensitive).

## Run Locally

No build tools required — just open the file, or serve it:

```bash
# Option 1: open directly
open index.html

# Option 2: serve locally (so relative links resolve exactly as they do live)
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

The site deploys automatically via GitHub Pages. Push to the default branch and the changes go live within about a minute:

```bash
git add index.html Atharva-Hatolkar-CV.pdf
git commit -m "Update portfolio"
git push
```

## Contact

- **Portfolio:** [hatolkarav.github.io](https://hatolkarav.github.io)
- **Email:** atharvahatolkar1@universityofgalway.ie
- **LinkedIn:** [atharva-hatolkar](https://www.linkedin.com/in/atharva-hatolkar-b235541a5/)
- **GitHub:** [HatolkarAV](https://github.com/HatolkarAV)

---

© Atharva Hatolkar · Built and hosted on GitHub Pages
