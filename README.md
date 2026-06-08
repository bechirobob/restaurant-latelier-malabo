# Restaurant L'Atelier Malabo

Restaurant web presence for Restaurant L'Atelier in Malabo.

## Build

```bash
npm ci
npm run lint
npm run build
```

## Deployment

Static site deployment uses Render with:

- Build command: `npm ci && npm run build`
- Publish directory: `dist`
- Rewrite: `/*` to `/index.html`
