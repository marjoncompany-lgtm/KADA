# KADA-5mins

A responsive, dependency-free focus website with a five-minute timer, quick-task prompts, and a private intention form. Intentions stay in the browser page and are not sent to a server.

## Requirements
- Node.js 20 or newer
- npm

## Commands
```bash
npm install
npm run dev
npm run build
npm test
npm run preview
```

The build uses Node.js built-ins only, so there is no paid API, external runtime dependency, or Bun requirement. `npm run build` recreates `dist/` from source. `npm test` checks production output, core interactions, and deployment security headers.

## Cloudflare Pages
- Project: `kada-5mins`
- Production URL: `https://kada-5mins.pages.dev` (only live after a successful deployment)
- Root directory: `/`
- Build command: `npm run build`
- Build output directory: `dist`
- Package manager: npm; keep `package-lock.json` synchronized with `package.json`

## Deployment status
The Cloudflare Pages project is connected to `marjoncompany-lgtm/KADA` on `main`. Its build settings have been corrected to root `/` and output `dist/`. The repository's current branch did not contain the website source when this package was rebuilt, so this archive is verified locally but is not proof of a successful production deployment. Commit the source project to the connected repository and confirm the Cloudflare deployment reports success before treating the site as live.
