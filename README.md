# Triple Spark

Video marketing and QR demo prototype for businesses in Mexico. The customer-facing interface supports Mexican Spanish, English, and Simplified Chinese. Demo-only features are labeled in the app; there is no configured production authentication, video storage, or analytics backend.

## Run locally

Requirements: Node.js 20+ and pnpm.

```sh
pnpm install
pnpm dev
```

## Build

```sh
pnpm build
pnpm preview
```

The current project build targets Cloudflare through Nitro. For a public long-term website, import this GitHub repository into Cloudflare Workers and configure the build command as `pnpm build`. Confirm the deployment URL and demo flows before sharing it.

## Demo limitations

Sign-in, merchant profile, upload, and analytics are prototype/demo flows. Do not enter real passwords or sensitive customer data. A public demo URL does not add real persistence or production security.
