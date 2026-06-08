# raygarrison.us

Starter portfolio website for `raygarrison.us`, deployed with GitHub Pages.

## Quick start

Open `index.html` in your browser to preview.

## Customize

- Replace placeholder text in `index.html`
- Update styles in `styles.css`
- Replace contact links with your real profiles

## Deploy

This repo includes `.github/workflows/deploy.yml` for GitHub Pages.

After creating the GitHub repo:

1. Push `main` branch
2. In GitHub repo settings, set **Pages > Source** to **GitHub Actions**
3. Ensure DNS for `raygarrison.us` points to GitHub Pages

## DNS records (apex domain)

At your domain registrar, create `A` records for:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optionally add:

- `AAAA` records for GitHub Pages IPv6 targets
- `www` CNAME to `HyruleanHero1988.github.io`
