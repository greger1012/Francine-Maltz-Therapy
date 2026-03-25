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

## Deploy on GitHub Pages

Repository: [greger1012/Francine-Maltz-Therapy](https://github.com/greger1012/Francine-Maltz-Therapy)

1. On GitHub: **Settings** → **Pages** → **Build and deployment** → **Source**: **Deploy from a branch** → Branch **main**, folder **/ (root)** → Save.
2. The site will be at `https://greger1012.github.io/Francine-Maltz-Therapy/` (exact URL is shown on the Pages settings page).

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
