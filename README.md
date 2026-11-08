# First Principle Lab

A static project and research directory for https://fpl.works/.

Edit `dist/index.html` for links and content, and `dist/style.css` for styling. No dependencies or build step are required. The page uses a consistent dark theme and supports keyboard navigation and reduced motion.

Deploy with `vercel --prod`. Vercel serves the `dist` directory using `vercel.json`.

Content sources: https://github.com/First-Principle-Lab and https://www.parththirwani.blog/.

## Production

- Public deployment: https://first-principle-lab.vercel.app
- Vercel project: https://vercel.com/parththirwanis-projects/first-principle-lab
- Custom domain: `fpl.works` is attached to this project.
- DNS is hosted externally (dns-parking.com). Vercel requires an apex (`@`) A record pointing to `76.76.21.21`. Keep the ChatterStack and Newshog subdomain records in place.

Verified the production HTML matches the source, all local assets return HTTP 200, security headers are present, and project destinations are correct. Browser visual QA was not run.
