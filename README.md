# WP Exterior Inc — Website (Phase 3, v3 — FINALIZED)

Website for WP Exterior Inc, roofing contractor in Des Plaines, IL.
638 Birchwood Ave, Des Plaines, IL 60018 · (224) 802-4866 · https://www.wpexterior.com/

## Changes in v3 (Phase 3 own audit — finalized upload version)

- Independent re-verification of every Phase 1/2 check from scratch
  (titles, descriptions, H1s, canonicals/sitemap, JSON-LD, FAQ schema vs
  visible text, links, fragments, assets, redirects, images, reviews).
- The Filip Libera review excerpt is now ONE identical clearly-labelled
  verbatim excerpt (first two sentences + ellipsis, “Verbatim excerpt”
  label) on all 14 pages that carry it; the four pages that used a
  three-sentence version were aligned, in visible cards and schema alike.
- Second-pass content sweep: every code, permit, licence, price, warranty,
  availability, and review claim re-checked against the research report
  and the verified Google profile facts. No other content changes were
  needed; all claims were already correctly qualified or fenced.
- Visual check re-run in a real browser (9 pages × desktop + mobile):
  no horizontal overflow, no broken images.
- No design, layout, CSS, or script changes: stylesheet and scripts are
  byte-identical to the supplied template.

## Changes in v2 (Phase 2 audit fixes)

- Hiring-guide blog title shortened into the 50–60 character band.
- Twitter cards and `og:image` (existing generated hero photos, absolute
  URLs) added to all 41 indexed pages; blog `image` schema fields made
  absolute; unverifiable `datePublished` metadata removed.
- WebSite schema added to the homepage; hero-image preloads added to the
  7 pages that lacked them.
- Contact and services FAQ sets rewritten so each page answers its own
  questions (they previously duplicated the homepage set).
- Inspection service page now points to the blog inspection-cost guide
  with the same second-hand-figures warning used there.
- Halston Market townhome count now attributed to the builder’s listing.
- Footer: “Our story” renamed “About us”; sitemap link added.
- `/blog/index.html` redirect target corrected to `/blog` (no trailing
  slash) to match the canonical.

## Files included

- 42 HTML pages: homepage (`index.html`), `about.html`, `contact.html`,
  `services.html`, `locations.html`, `privacy-policy.html`,
  `terms-of-service.html`, `404.html`, 12 service pages
  (`roof-replacement`, `roof-repair`, `storm-damage-roof-repair`,
  `roof-inspection`, `emergency-roof-repair`, `flat-roof-repair`,
  `metal-roofing`, `wood-shake-roofing`, `skylight-installation`,
  `roof-ventilation-installation`, `gutter-installation`,
  `insurance-claim-help`), 7 location pages (`roofing-downtown-des-plaines`,
  `roofing-cumberland`, `roofing-big-bend`, `roofing-lake-opeka`,
  `roofing-orchard-place`, `roofing-riverview`, `roofing-oakton`), and
  `blog/` with an index + 14 posts.
- `assets/` — stylesheet, scripts, logo/favicon, and 96 generated JPG images
  (EXIF-tagged with the business address and map-pin coordinates).
- `.htaccess`, `_redirects`, `vercel.json`, `netlify.toml` — clean-URL rules
  plus 301 redirects for the 35 pruned URLs (each host reads its own file;
  safe to leave all four in place).
- `robots.txt`, `sitemap.xml` (41 URLs — every page except `404.html`).

## Setup

1. Upload the CONTENTS of this folder to your web host (not the folder itself).
2. Keep the files in the site's root directory, so `index.html` sits beside
   `assets/`.
3. **Shared/cPanel hosting:** make sure `.htaccess` uploaded too. It starts
   with a dot, so file managers hide it by default — turn on "show hidden
   files" and confirm it sits next to `index.html`. Without it every page
   except the homepage returns 404.
4. Open the site and check the pages, links and contact details. The Google
   Maps embed on the homepage needs a live connection to load tiles.

## Notes

- The logo is original placeholder branding created for this build (not the
  business's existing trademarked logo) — owner approval needed.
- No licence number, pricing, warranty, or 24/7 claim is published anywhere
  on the site: none was supplied. The owner must confirm the phone number —
  directories show a different number, (224) 817-4866, which is NOT used here.
