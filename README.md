# mykhailokar.github.io

Personal website, built with React + TypeScript (Vite) and hosted on GitHub Pages at
<https://mykhailokar.github.io/>.

## Development

```sh
npm install
npm run dev      # local dev server
npm run lint     # oxlint
npm run build    # type-check + production build into dist/
npm run preview  # serve the production build locally
```

## Deployment

Every push to `main` runs `.github/workflows/deploy.yml`, which builds the site and
publishes `dist/` to GitHub Pages.
