# Oak Plaza Tower

Luxury apartment rentals in Miami’s Health District. A static marketing site for [Melo Group](https://melogroup.com), redesigned from the live WordPress site at [oakplazatower.com](https://oakplazatower.com).

**1415 NW 15 AVE, Miami, Florida 33125** · 305.547.1616 · info@oakplazatower.com

## Preview locally

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Any static file server works — there is no build step, WordPress, or JavaScript framework. The page is a single `index.html` with Tailwind via CDN, the same pattern used by sibling Melo property sites (Art Plaza Tower, 25 Mirage, Square Station).

## Structure

| Path | Purpose |
| --- | --- |
| `index.html` | Full single-page site |
| `images/` | Logos, photography, and location maps from the live site |
| `floorplans/` | Unit layouts (downloaded from the live site) |
| `Oak-Plaza_brochure.pdf` | Property brochure |
| `CNAME` | `oakplazatower.com` for GitHub Pages |

The contact form opens a pre-filled `mailto:` to info@oakplazatower.com. No backend is required.
