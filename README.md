# Millwright

Landing page for **Millwright** — custom apps, workflows, and AI agents built around your business.

**Live site:** https://melaniesigrid.github.io/millwright/

Millwright turns repetitive work into custom software systems that capture data, move tasks, draft responses, update records, and keep teams out of manual busywork.

---

## What's here

A single self-contained static page. No build step, no dependencies, no framework.

```
index.html    The entire site — markup, styles, and scripts inline
```

Fonts (Bricolage Grotesque, Instrument Sans, Spline Sans Mono) load from Google Fonts. Everything else — the logo, the workflow diagram, the icons — is inline SVG.

## Running it locally

Open the file directly:

```bash
open index.html
```

Or serve it over HTTP if you want the page to behave exactly as it does in production:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Editing

All the styling lives in one `<style>` block at the top of `index.html`, driven by CSS custom properties in `:root` — colors, radii, fonts, and the content max-width. Change a token there and it propagates through the page.

| Token | Purpose |
| --- | --- |
| `--ink` | Dark section background |
| `--paper` | Light section background |
| `--volt` | Primary accent (buttons, links, highlights) |
| `--jade` | Success / "running" state accent |
| `--wrap` | Max content width |

Sections are marked with comment banners (`<!-- ============ HERO ============ -->`) so they're easy to find and reorder.

### Contact links

Three places point at Northbound and should be kept in sync if either changes:

- Booking → `https://cal.com/northboundsoftwarestudio/scope-call`
- Email → `hello@northboundsoftwarestudio.com`
- Footer credit → `https://northboundsoftwarestudio.com`

## Accessibility & motion

- Scroll-reveal and entrance animations are fully disabled under `prefers-reduced-motion: reduce`.
- The hero workflow diagram carries a descriptive `aria-label`; its decorative SVG is hidden from assistive tech.
- Interactive elements have visible `:focus-visible` outlines.

## Deployment

The site deploys to GitHub Pages from the `main` branch, served from the repository root. Any push to `main` republishes it — GitHub Pages picks up `index.html` automatically.

To point a custom domain at it, add a `CNAME` file containing the domain and configure the DNS records with your registrar.

---

## Contact

- **Book a call:** [cal.com/northboundsoftwarestudio/scope-call](https://cal.com/northboundsoftwarestudio/scope-call)
- **Email:** [hello@northboundsoftwarestudio.com](mailto:hello@northboundsoftwarestudio.com)

Made by [Northbound Software Studio](https://northboundsoftwarestudio.com).
