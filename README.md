# Junxian You Personal Homepage

This is a lightweight bilingual academic personal homepage built from the supplied resume and updated profile information.

## Files

- `index.html`: page structure
- `styles.css`: visual system and responsive layout
- `script.js`: English/Chinese content and language switching
- `assets/research-banner.png`: generated research-themed banner image

## Content Rules

- Keep only published or formally accepted publications on the homepage.
- Do not include unpublished, revise-and-resubmit, or arXiv-only papers unless the public profile strategy changes.
- Public contact information is limited to email and Google Scholar.
- Phone number, birth date, gender, and hometown are intentionally excluded.

## Recommended Deployment Options

1. GitHub Pages
   - Best first choice for an academic homepage.
   - Create a repository named `<your-github-username>.github.io`.
   - Upload these files to the repository root.
   - Enable Pages from repository settings if it is not already enabled.
   - Resulting URL: `https://<your-github-username>.github.io`.

2. GitHub Pages with a static site generator
   - Useful later if you add many pages, posts, talks, or publication pages.
   - Common choices: Jekyll, Hugo, Quarto, or Astro.
   - Keep the current static page as the first version, then migrate only when content volume grows.

3. Netlify
   - Good if you want drag-and-drop deployment, branch previews, password protection, or simple form handling.
   - You can deploy the folder directly or connect a GitHub repository.

4. Vercel
   - Good if you later turn the homepage into a React/Next.js site or want automatic preview deployments.
   - It also supports plain static HTML/CSS/JS projects.

## Privacy Notes

- The public webpage currently exposes only the email address from the resume.
- The phone number, birth date, gender, and hometown from the resume are intentionally not included.
- Before publishing a downloadable CV, consider preparing a public academic CV without phone number or private identifiers.

## Suggested Next Edits

- Add GitHub, ORCID, LinkedIn, and personal domain links when available.
- Add DOI or publisher links for published papers.
- Add a headshot only if a real professional photo is available.
- Add a short `News` section when there are accepted papers, thesis updates, talks, or job-market milestones.
