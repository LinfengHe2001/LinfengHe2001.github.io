# Personal website

The homepage is `_pages/about.html`, styled by `assets/css/profile.css`.
GitHub Pages builds the existing Jekyll repository; no JavaScript, web fonts,
package installation, or additional hosting service is needed for the homepage.

## Content

Profile information was updated from the owner's OpenReview screenshots on
2026-10-11. Duke is described as master's studies rather than asserting a
completed degree. The preferred contact address is lh426@duke.edu.
Google Scholar and LinkedIn are linked without importing unverified content.
The supplied Wikipedia URL returned 404 and is omitted until available.
Birth date and other account-only details are not published.

The original Academic Pages sample collections and demo pages remain in Git
but are excluded in `_config.yml`. Add verified publications before restoring
a local publications collection. Do not publish the template's example papers.

## Design

Warm neutral background, forest-green accents, system sans-serif body text,
Georgia headings, shared column alignment, and restrained rules. Responsive
layouts at 900px and 640px; visible keyboard focus, a skip link, reduced-motion
support, and print styling are included. The former profile image was a generic
placeholder, so the site uses an LH monogram instead.

## Validation

Check local links, unique anchor IDs, mobile navigation, keyboard focus, and
desktop/mobile rendering when updating. A full Jekyll build is performed by
GitHub Pages. Local HTTP preview can strip YAML front matter and replace the
Liquid year, but is not a substitute for that build.
