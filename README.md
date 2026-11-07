# Tanzstudio Bonita

A warm, responsive Astro landing page for the upcoming Tanzstudio Bonita in Wietzendorf.

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Before publishing

1. Replace the sample instructor introduction with your own approved text and photo.
2. Add real studio photos when the room is ready.
3. Confirm course names, age groups, dates and times after training.
4. Add a real contact email and social links.
5. Connect the interest form to a GDPR-appropriate form provider. The current form is a front-end placeholder and does not submit or store data.
6. Add legally reviewed Impressum and Datenschutzerklärung.
7. Buy a domain, update `site` in `astro.config.mjs`, and configure GitHub Pages custom-domain settings.
8. Review the GitHub Pages deployment workflow and repository Pages settings.

## GitHub Pages

The included workflow builds the site and deploys `dist/` to GitHub Pages. In the repository, choose **Settings → Pages → Build and deployment → GitHub Actions**.

For a project repository URL such as `https://USERNAME.github.io/tanzstudio-bonita/`, configure Astro's `site` and `base` accordingly before deploying. For a custom domain later, use `base: "/"` and set `site` to your real domain.
