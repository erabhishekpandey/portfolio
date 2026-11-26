# Abhishek Pandey — research portfolio

## Run locally
Open index.html, or run `python3 -m http.server 8000` in this folder and open http://localhost:8000. No build or dependencies.

## Deploy using your existing GitHub Pages repository
1. Extract the ZIP. Upload the contents (not the outer folder or ZIP) to github.com/erabhishekpandey/portfolio. Replace index.html and README.md; upload css, js, images, assets, 404.html, sitemap.xml and robots.txt. Old root style.css and script.js are no longer used; delete them if desired. Remove superseded assets if not needed. Public repository history can retain old files.
2. Commit to main. Settings > Pages > Deploy from a branch > main > /(root) > Save. Check Actions for a successful deployment. Preview https://erabhishekpandey.github.io/portfolio/.
3. Once the .com.np registration is approved and Cloudflare DNS is active, configure the apex domain in Cloudflare DNS: A records for @ pointing individually to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME www to erabhishekpandey.github.io. Use DNS only (gray cloud), remove conflicting records for these names, do not alter unrelated records. Verify current instructions at https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site. Verify domain ownership via GitHub account Settings > Pages if possible before assigning the domain.
4. Repository Settings > Pages > Custom domain > erabhishekpandey.com.np > Save. GitHub creates a CNAME file; keep it in future updates. Once DNS checks and certificate provisioning succeed, enable Enforce HTTPS. Test apex and www. Do not create a separate Cloudflare Pages project.
5. SEO metadata and sitemap assume the final custom domain; if keeping the github.io address permanently, change all absolute URLs accordingly. Submit sitemap in Google Search Console after launch. Review public CV and page content before deploying.

## Remaining optional content (not displayed as placeholders on the website)
- Confirm target opportunities, current employment and research statement.
- Add verified Google Scholar and ResearchGate links if available.
- Add water savings, hydrological results, composite experimental results, and review findings/contribution when verified.
- Add hydrology and laboratory photographs, approved thesis PDF and conference abstract if cleared for public sharing. The supplied thesis document was used for methodology only; it does not contain a results chapter and is not included for public download.
- Confirm specific tool-to-project examples, optional analytics and domain activation.
- ORCID and LinkedIn are included as supplied; ownership has not been independently verified.

## Five improvements after launch
1. Replace illustrative diagrams with real, permission-cleared field photographs, maps and thesis figures.
2. Add validated numerical research outcomes and explain their measurement methods and limitations.
3. Finalize research statement and target opportunity; connect verified academic profiles.
4. Add downloadable approved thesis/abstracts and update publications regularly.
5. Run Lighthouse and manual keyboard/screen-reader checks on the deployed HTTPS URL, verify indexing, and optionally enable privacy-friendly analytics.

## Notes
CV content is the source; public CV is the previously redacted version (personal phone and reference contacts omitted). Portrait is compressed WebP; conceptual figures are lightweight SVG. No fabricated data or field photos. No backend or tracking; contact uses mailto. The Lighthouse 90+ target is not a measured guarantee. Update the footer date and sitemap lastmod after substantive revisions.
