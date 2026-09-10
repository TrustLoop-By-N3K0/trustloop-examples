# trustloop-examples

Example projects showing how to embed TrustLoop in popular frameworks and platforms.

## What this is

A monorepo of starter templates and example sites that demonstrate how to add the TrustLoop widget to Next.js, Astro, WordPress, Webflow, and more.

## Examples

| Directory | Framework / Platform |
| --- | --- |
| `nextjs` | Next.js App Router |
| `astro` | Astro |
| `wordpress` | WordPress plugin |
| `webflow` | Static HTML for Webflow |
| `shopify` | Shopify theme snippet |

## Getting started

Pick an example directory:

```bash
cd nextjs
npm install
npm run dev
```

## Using the widget

Most examples load the widget with a script tag:

```html
<script
  src="https://widget.trustloop.app/widget.js"
  data-slug="your-name"
  data-limit="3"
  defer
></script>
```

Replace `your-name` with your TrustLoop collection slug.

## Adding an example

1. Create a new directory under `examples/`.
2. Add a `README.md` inside it with setup steps.
3. Open a PR.

## License

MIT
