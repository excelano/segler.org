# Contributing

The site is public and so is this repository. A correction, clearer wording, a broken link, a claim about another project that has gone out of date, a rendering bug in a browser we do not have: all of it is welcome as a pull request or an issue.

## Contributions are dedicated to the public domain

Everything here is dedicated to the public domain under [CC0 1.0](LICENSE). By contributing you dedicate your contribution on the same terms, waiving copyright and related rights in it to the extent possible under law.

## Claims about other projects

The ecosystem page describes Docling, docling.rs, the DocLang viewer, Label Studio and DocLang itself. Each statement should be something the project's own site or repository says. If one is wrong or has gone stale, a pull request that fixes it and links the source is the most useful thing you can send. Segler and Duckling are Excelano's applications, and what the pages say about them is the applications' own behaviour: a claim that does not match what the application does is a bug in the page.

## Two things that do not belong here

The DocLang format is defined in [doclang-project/doclang](https://github.com/doclang-project/doclang), and this site neither restates it nor amends it. A change to what DocLang is goes there. The applications are developed in [excelano/segler](https://github.com/excelano/segler) and [excelano/duckling](https://github.com/excelano/duckling), and a request for a feature or a report of a defect goes to those repositories, not to this one.

## House style

Prose, in paragraphs, in full sentences with a claim stated plainly rather than hedged. Plain HTML: no framework, no build step, no JavaScript beyond the theme toggle, and nothing loaded from a third party, so no fonts, analytics or CDN. A page must work with JavaScript off.

Styling comes from the vendored [Axe](https://github.com/excelano/axe) framework, which styles standard HTML elements without classes. `brand.css` holds only the variables. The site's own rules go in `site.css`, which loads after `axe.css`, and a class belongs there only when Axe has no opinion about what you are building.

Check both themes. The toggle in the navigation bar switches them, and a colour that only works in one is a bug. Check a narrow window as well.

## Before you open a pull request

Serve the site and look at what you changed:

```sh
python3 -m http.server 8000    # then http://localhost:8000/
```
