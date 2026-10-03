# Maldonado Research public hub

A static research portfolio prepared for https://maldonado-research.github.io/.

## Contents

- `index.html`: central collection and author overview.
- `projects/{slug}/index.html`: seven public research summaries.
- `styles.css`: responsive styles, with no external fonts or scripts.
- `sitemap.xml`: eight hub pages plus the existing English and Spanish HDBLAST pages.
- `sitemap.txt`: the same ten URLs, one absolute URL per line, as a supported text-format sitemap fallback.
- `robots.txt`: allows crawling and advertises both central sitemap formats.
- `.nojekyll`: publishes plain static files on GitHub Pages.

## Publish

Place the contents of this directory at the published root of the `maldonado-research.github.io` repository. Enable GitHub Pages for that repository using its chosen publishing branch/root, or an existing Pages deployment workflow. No build dependencies are needed.

The canonical and social URLs intentionally target the root domain. The existing HDBLAST project site remains at `/HDblast/`; its files are maintained in its own repository and are not included here. Preserve that project site when enabling the root hub.

The root `index.html` contains the actual Google Search Console verification token supplied by the account’s verification flow. Preserve it during future page edits. Publication and Search Console submission are separate steps; the static files alone do not confirm indexing.

## Sitemap recovery experiment

Search Console reported “Couldn't fetch” for the XML sitemap even though the XML validated and a Google live fetch of the central page succeeded. A plain-text sitemap is a supported alternative format. `sitemap.txt` supplies the same ten URLs, and `robots.txt` retains both `Sitemap:` directives. This fallback is a recovery experiment, not a confirmed fix or evidence that Google has fetched the sitemap or indexed the pages. Check Search Console's processing result after submission. Regeneration must preserve the text sitemap and both advertised formats.

## Content and version policy

The six original project summaries are grounded in public repository README and CITATION.cff material captured on 30 September 2026. DMDE uses the refreshed public README fetched later that day, after its full v0.9.20 provider materials were published. TMD's labelled methods release 0.5.0 is https://zenodo.org/records/23075312 in report/methods concept DOI family `10.5281/zenodo.23068055`. A later published family record, https://zenodo.org/records/23113326, has no version label; its six filenames, byte sizes and reported checksums match 0.5.0, and the prepared 0.6.0 package is absent. The expanded report 0.1.0 remains at https://zenodo.org/records/23068056; the older software v2.6.5 archive at https://zenodo.org/records/22398093 belongs to a separate publication family. The UTOE DOI 10.5281/zenodo.22319172 identifies only its older baseline. HDBLAST record 22922928 remains labeled as a record listed by its README, with the README’s version/file-list qualification preserved.

The DMDE overview was updated on 2 October 2026 from the reviewed public source-adapter preflight at commit `278de562075c0a37a3e36c6776053e3e3dd12330` of `maldonado-research/dmde-research`. It retains the 1 October numerical controls and adds twelve passing fixed-state adapter checks alongside the unresolved source-grid, production-operator and plasma-thermodynamics prerequisites. These diagnostics supply no evolved injected histories or new cosmological predictions. The existing v0.9.20 Zenodo archive and its five files were verified on 2 October; no new Zenodo release was created. The [public publication-status note](https://github.com/maldonado-research/dmde-research/blob/main/research/PUBLICATION_STATUS.md) records that distinction.

The Faster than Light overview was added on 2 October 2026 from the merged public `maldonado-research/faster-than-light` methods at commit `7ad6a32a2f413b8f13c329ae685478b19ea42dd2`. It links the finite-delay and unequal-speed calculations, the conditional preferred-frame scalar exercise and the live archive-verification note. The GitHub methods additions are separate from the cited v1.2.1 Zenodo package; no new Zenodo release or physical FTL result is claimed.

The TOE operator overview summarizes the October 1 checkpoint at immutable source commit `ca88aed6e69d3b6dbda02ebc78831dd925613fdb`, included in the public main branch through merged [research PR #1](https://github.com/maldonado-research/Unified-Theory-of-Everything/pull/1). Its source links remain pinned to that commit for reproducibility. Publication status was checked on 2 October 2026. The older Zenodo DOI identifies only the N00AK-r1 baseline; it does not archive the later GitHub edition. Private follow-up calculations are outside this overview. After directory changes are merged, verify the Pages deployment separately from the research-source merge.

The TMD overview was updated on 2 October 2026 from public numerical/source checkpoint `b3191b8b0ac952c6e35ad20b3e4175fdbca981bf` and the earlier pinned source-audit and prospective-design checkpoints. The certified-score implementation evaluates frozen forecasts of observed qualifying Wsp/Aws/Mws outcomes with certified rational confidence/logarithm/projection bounds. Its 20 synthetic tests and 30,887 independent exact review assertions do not establish biological validity or a new theorem. The targeted watch inspects three new primary full-text articles on transcription-dependent supply, population history and plasmid masking; their raw datasets remain unacquired, and no matched biological Wsp/Aws/Mws panel is admitted within the inspected scope. The design still has 26 unresolved required study inputs and is not registered. A 0.05-nat precision illustration needs 527 and 921 qualifying endpoints, beyond the bounded prototype's 500-unit limit; this is an interval-width bound, not power or a scientific sample-size recommendation. The reviewed 0.6.0 package remains absent from Zenodo; it freezes an earlier methods snapshot and excludes the later source-watch and certified-score work. The former draft 23113326 is now a published unversioned record containing the inherited 0.5.0 file inventory, so the prior draft editor fallback is obsolete. Current publication-state links identify that change without attributing its actor or claiming a verified active draft. No unattended research schedule is claimed to be active. Publication updates must preserve the existing report/methods DOI family; automatic GitHub-to-Zenodo archiving is disabled and must not be re-enabled to test publication.

Structured data describes the site, author, collection and research materials without peer-review, experimental-validation or institutional claims. Reproducibility and byte-integrity evidence are qualified separately from scientific validation.

## Maintenance

When a project changes, update its overview, version, limitations, links and structured data together. Change the affected sitemap date only after changing the public page. Confirm that the static navigation and published canonical URLs still match. Keep source repository files and archives authoritative for detailed claims and reuse licenses.
