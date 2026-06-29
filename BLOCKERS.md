# Blockers

## docs.tookyn.com DNS activation

Status: blocked by Cloudflare DNS permission.

What is ready:
- Cloudflare Pages project: `tookyn-docs`
- Direct Upload deployment: `https://tookyn-docs.pages.dev`
- Requested custom domain: `docs.tookyn.com`

What remains:
- Create DNS record `docs.tookyn.com` pointing to `tookyn-docs.pages.dev`, or grant the token DNS permission for the `tookyn.com` zone and rerun the DNS step.

Observed API result:
- Pages custom domain creation succeeded.
- DNS record read/create returned Cloudflare authentication error `10000`.

No secret values are stored here.
