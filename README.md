# Washington, D.C. — Capital City History

A family-friendly, single-page history tour of Washington, D.C. — how it became the capital, its government architecture, the founding documents, monuments, cherry blossoms, airports, and nearby towns for trip planning.

**Live site:** https://kensingtondc.netlify.app/

## Features

- Mobile-first responsive design with fluid typography and scroll-spy navigation
- Tables that collapse into stacked cards on small screens
- 360° Google Street View links for the White House, Treasury, and Capitol
- Document images sourced directly from the National Archives
- Respects `prefers-reduced-motion`; works without JavaScript

## Structure

| File | Purpose |
|---|---|
| `index.html` | The entire site — content, styles, and scripts in one file |
| `sitemap.xml` | Sitemap submitted to Google Search Console |
| `robots.txt` | Crawler rules + sitemap pointer |

## Deployment

Deployed on [Netlify](https://www.netlify.com/) from the `main` branch. No build step — it's plain HTML, published from the repo root. Pushing to `main` auto-deploys.

## Sources

Content was researched from official sources: the National Archives, Library of Congress, Architect of the Capitol, White House Historical Association, U.S. Treasury, National Park Service, U.S. Census Bureau, MWAA, and the Smithsonian. Images are from the National Archives and Wikimedia Commons. Full source list is in the [Sources section](https://kensingtondc.netlify.app/#sources) of the site.
