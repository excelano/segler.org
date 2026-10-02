# segler.org

The site for Segler, the DocLang viewer and editor, and for the ecosystem around it: Duckling, DocLang, Docling, docling.rs, the DocLang viewer and Label Studio.

Plain HTML on the vendored Axe stylesheet, no build step. `brand.css` carries the Segler palette over Axe and `site.css`, loaded after Axe, the site's own rules; `./update-axe.sh` refreshes the vendored copy. Screenshots are the light and dark captures from the product pages on excelano.com.

Deploy with `updatesite segler.org` once the site is added to that script.

Pull requests are welcome, and [CONTRIBUTING.md](CONTRIBUTING.md) says what belongs here. A merged change goes live when the maintainer deploys, which is a manual step.

## Licence

Everything here is dedicated to the public domain under [CC0 1.0](LICENSE).

Three exceptions, each carried here as a copy. `axe/` is from [excelano/axe](https://github.com/excelano/axe), MIT licensed. The Segler and Duckling icons and screenshots belong to [excelano/segler](https://github.com/excelano/segler) (Apache-2.0) and [excelano/duckling](https://github.com/excelano/duckling) (MIT). The Excelano logo is Excelano's mark. All © Excelano LLC.
