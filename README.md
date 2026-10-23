# Engineering portfolio HTML starter

Two editable HTML templates, one shared stylesheet, and a favicon. Everything works without JavaScript, a framework, remote fonts, or a build step.

## Open and edit

1. Extract the entire ZIP to a folder. Keep the files together.
2. Open that folder in VS Code.
3. Open `index.html` in Chrome or Edge. Save edits and refresh the browser.
4. Edit `blog.html` for the article page and `styles.css` for shared appearance.

`index.html` includes Home, About, Experience & Resume, Projects, Blog, and Contact sections. Each navigation link works. Project details use native `<details>` elements with keyboard support. `blog.html` is a reusable article template. Copy it to a descriptive filename for each additional article, update its unique metadata, and link to it from Home.

## Personalize before publishing

- Replace every `Your Name` and update the brand mark and favicon.
- Review the biographical text and all work descriptions. Add verified dates and results only. Keep company-confidential drawings and information out of a public portfolio.
- Replace the contact placeholder with real email, LinkedIn, and GitHub links. Commented examples are provided in the HTML. There is no fake form or mail delivery service.
- Add your real resume at `assets/resume.pdf`, then uncomment and update the sample resume link and its file size. The page already contains an accessible HTML experience summary.
- Review the sample blog in your own voice. Remove the sample-draft label only when it is ready. Add its real publication date using `<time datetime="YYYY-MM-DD">`.

## SEO implementation

- Both pages have a unique, descriptive title and meta description, readable visible content, and crawlable relative links.
- HTML is server-readable without running JavaScript. Each page has one primary h1 and logically nested headings.
- Open Graph title, description, and type plus a Twitter card type are included. These help sharing; they do not guarantee search ranking.
- After choosing your deployed HTTPS URL, uncomment each canonical link and `og:url`, replacing the placeholder with that page's real URL. Use the actual final public URL, including a repository subpath if applicable. Point each canonical at itself, not both at Home.
- If you create a real social preview image, add its absolute `og:image` URL and `og:image:alt`. No nonexistent image is referenced by this starter.
- Add structured data only when the underlying real name, URL, and content are finalized. Person/ProfilePage or BlogPosting data must match visible content. Structured data does not guarantee a rich result. No fabricated schema or placeholder domain is active here.
- Add `sitemap.xml` only after the production origin is known. Include the final absolute URLs of published pages. Only add lastmod dates that reflect actual substantive edits.
- A robots.txt file is optional; do not block these public pages if you want indexing. A `Disallow` rule is not a privacy control. If you use a temporary `noindex` directive for a public preview, remove it before launching.
- After deployment, confirm 200 responses, HTTPS, mobile layout, metadata, canonical URLs, and indexing access. Search engines cannot index a file opened only on your computer or an authenticated private preview.

## Accessibility implementation and checks

- English document language, semantic landmarks, a skip link, labeled navigation, and ordered heading levels.
- Native links and disclosures; no custom keyboard emulation, hover-only menu, or JavaScript dependency.
- A visible keyboard focus outline and 44px-minimum main navigation/disclosure controls. Inline text links remain inline.
- Responsive layout with wrapping navigation; no fixed header to obscure focus, no disabled zoom, and no fixed-height text blocks.
- High-contrast palette, persistent underline on content links, reduced-motion rules, forced-colors support, and print styles.
- Decorative marks are hidden from assistive technology. If adding meaningful images, supply appropriate alt text and intrinsic width/height. Use alt="" for purely decorative images.
- Any future form needs visible labels, appropriate input types, instructions, accessible errors, and a real submission destination. Do not use placeholders as labels.

Before launch, tab through both pages, use Enter/Space on the disclosures, check skip-link behavior, test a screen reader, and check at 200% and 400% zoom and a 320 CSS-pixel viewport. Run an automated accessibility audit and manually inspect it. Templates cannot by themselves guarantee WCAG compliance or SEO performance; later content changes also need review.

## References

- Google SEO Starter Guide: https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- W3C WAI Page Structure Tutorial: https://www.w3.org/WAI/tutorials/page-structure/
- W3C WAI Headings: https://www.w3.org/WAI/tutorials/page-structure/headings/
