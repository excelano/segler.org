# segler.org

The site for Segler, the DocLang viewer and editor, and for the ecosystem around it: Duckling, DocLang, Docling, docling.rs, the DocLang viewer and Label Studio.

Plain HTML on the vendored Axe stylesheet, no build step. `brand.css` carries the Segler palette over Axe and `site.css`, loaded after Axe, the site's own rules; `./update-axe.sh` refreshes the vendored copy. Screenshots are the light and dark captures from the product pages on excelano.com.

Deploy with `updatesite segler.org` once the site is added to that script.
