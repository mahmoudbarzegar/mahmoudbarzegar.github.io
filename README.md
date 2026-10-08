# Mahmoud Barzegar — Personal Website

Professional portfolio for [mbarzegar.ir](https://mbarzegar.ir).

Built with [Astro](https://astro.build/) and designed for GitHub Pages.

## Local development

```bash
npm install
npm run dev
```

Then open the local URL shown by Astro.

## Build

```bash
npm run build
```

The generated static files are placed in `dist/`.

## GitHub Pages

This repository is intended to be used as a GitHub Pages repository.

1. Create the repository as `mahmoudbarzegar.github.io`.
2. Push this project to the `main` branch.
3. In GitHub, open **Settings → Pages**.
4. Set the source to **GitHub Actions**.
5. The included workflow deploys the Astro build automatically.
6. The `public/CNAME` file configures `mbarzegar.ir` as the custom domain.

## Customize

The main content is in:

`src/pages/index.astro`

Global styles are in:

`src/styles/global.css`
