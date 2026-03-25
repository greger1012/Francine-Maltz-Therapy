# Francine R. Maltz, LMFT, CCE — Child Custody Evaluator Website

A professional website for Francine R. Maltz, Child Custody Evaluator, serving Rancho Cucamonga and the Inland Empire.

## About the Site

This website presents Francine's child custody evaluation services, including:
- Child Custody Evaluations (California Family Code 3111)
- 730 Evaluations (California Evidence Code 730, Rules of Court 5.225/5.230)
- Experience in domestic violence, high-conflict custody, trauma, and forensic interviewing

## Getting Started

To view the website, open `index.html` in your web browser, or use a local server:

```bash
python -m http.server 8080
```

Then visit http://localhost:8080

## Deploy on GitHub (Pages)

1. Create a new empty repository on [GitHub](https://github.com/new) (for example `francine-maltz-therapy-website`). Do not add a README, `.gitignore`, or license (this project already has them).

2. In this folder, add the remote and push (replace `YOUR_USER` and `YOUR_REPO`):

```bash
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git branch -M main
git push -u origin main
```

3. Turn on **GitHub Pages**: open the repo on GitHub → **Settings** → **Pages** → **Build and deployment** → **Source**: **Deploy from a branch** → Branch **main**, folder **/ (root)** → Save.

Your site will be available at `https://YOUR_USER.github.io/YOUR_REPO/` (GitHub shows the exact URL on the Pages settings page).

## Files

- `index.html` — Home page
- `about.html` — About, credentials, and experience
- `services.html` — Evaluation services and process
- `contact.html` — Contact info and inquiry form
- `styles.css` — Styling and responsive design
- `script.js` — Mobile navigation and form handling

## Contact Form

The contact form shows an alert on submit. To enable actual email delivery, integrate with a form service such as Formspree, Netlify Forms, or a backend handler.

## Customization

- **Colors:** Edit CSS variables in `styles.css` (`:root`)
- **Content:** Update HTML files directly
- **Images:** Add an `images` folder and reference images in HTML
