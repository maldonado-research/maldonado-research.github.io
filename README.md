# Maldonado Research public hub

A static research portfolio prepared for https://maldonado-research.github.io/.

## Contents

- `index.html`: central collection and author overview.
- `projects/{slug}/index.html`: six public research summaries.
- `styles.css`: responsive styles, with no external fonts or scripts.
- `sitemap.xml`: seven hub pages plus the existing English and Spanish HDBLAST pages.
- `sitemap.txt`: the same nine URLs, one absolute URL per line, as a supported text-format sitemap fallback.
- `robots.txt`: allows crawling and advertises both central sitemap formats.
- `.nojekyll`: publishes plain static files on GitHub Pages.

## Publish

Place the contents of this directory at the published root of the `maldonado-research.github.io` repository. Enable GitHub Pages for that repository using its chosen publishing branch/root, or an existing Pages deployment workflow. No build dependencies are needed.

The canonical and social URLs intentionally target the root domain. The existing HDBLAST project site remains at `/HDblast/`; its files are maintained in its own repository and are not included here. Preserve that project site when enabling the root hub.

The root `index.html` contains the actual Google Search Console verification token supplied by the account’s verification flow. Preserve it during future page edits. Publication and Search Console submission are separate steps; the static files alone do not confirm indexing.

## Sitemap recovery experiment

Search Console reported “Couldn't fetch” for the XML sitemap even though the XML validated and a Google live fetch of the central page succeeded. A plain-text sitemap is a supported alternative format. `sitemap.txt` supplies the same nine URLs, and `robots.txt` retains both `Sitemap:` directives. This fallback is a recovery experiment, not a confirmed fix or evidence that Google has fetched the sitemap or indexed the pages. Check Search Console's processing result after submission. Regeneration must preserve the text sitemap and both advertised formats.

## Content and version policy

The six project summaries are grounded in public repository README and CITATION.cff material captured on 30 September 2026. DMDE uses the refreshed public README fetched later that day, after its full v0.9.20 provider materials were published. TMD now summarizes the public methods package 0.5.0 and links https://zenodo.org/records/23075312. The expanded report remains 0.1.0 at https://zenodo.org/records/23068056; the older software v2.6.5 archive is https://zenodo.org/records/22398093. The UTOE DOI 10.5281/zenodo.22319172 identifies only its older baseline. HDBLAST record 22922928 remains labeled as a record listed by its README, with the README’s version/file-list qualification preserved.

Structured data describes the site, author, collection and research materials without peer-review, experimental-validation or institutional claims. Reproducibility and byte-integrity evidence are qualified separately from scientific validation.

## Maintenance

When a project changes, update its overview, version, limitations, links and structured data together. Change the affected sitemap date only after changing the public page. Confirm that the static navigation and published canonical URLs still match. Keep source repository files and archives authoritative for detailed claims and reuse licenses.
