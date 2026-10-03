---
version: 1
slug: "src-pages-work-del-campo-astro"
primary_target: "src/pages/work/del-campo.astro"
related_targets: ["src/components/Welcome.astro","src/styles/styles.css"]
---

# Del Campo case study

Mode: Read with storefront imagery. Clients and recruiters should understand Fernando’s website design and platform implementation contribution. Source: Vault/delcampo-case-study.md and its evidence note. English narrative, Spanish source UI. Extend the established Elio case-study composition; code-led, no new visual identity.

## Direction contract

THESIS: Explain the company’s first online storefront through an overview followed by catalog, product-detail, responsive-layout and implementation evidence.

OWN-WORLD: Retain the current blue and slate tokens, Archivo headings, Hanken Grotesk prose, flat surfaces and ruled information. Warm peach is confined to Del Campo image stages.

STORY: Establish role and scope, inspect the storefront’s recurring patterns, then explore Elio or contact Fernando. Avoid unconfirmed platform, launch, team and commercial-result claims.

FIRST VIEWPORT: Shared navigation above two columns: Del Campo title, first-storefront headline, role and overview anchor on the left; readable desktop-home crop on the right. Mobile stacks. Focused mobile crops accompany decisions; a full UI board anchors foundations. Full-reference links are the image exploration interaction; no automatic animation.

FORM: Precisely scoped extension of the existing overview-then-story case-study composition, using the vault’s visual story. No concept seed required for this inherited structure.

FINISH: unreviewed and undocumented is unfinished; this build ends with the finish review, the verdict, DESIGN.md, and every shipping raster carrying its provenance. Preserve the incumbent DESIGN.md and sidecar for this ordinary extension.

## Implemented patterns

Ordinary extension of the incumbent system, checked against `DESIGN.md`, `PRODUCT.md`, `src/styles/styles.css`, and the shared header/footer. Global blue/slate tokens, Archivo headings, Hanken Grotesk prose, flat depth, thin rules, fluid gutters, and visible focus remain authoritative. No durable system change: preserve `DESIGN.md` and `.impeccable/design.json`.

The shared Elio case-study structure supplies the hero, ruled facts, overview, tonal story sections, decision prose, contact invitation, and closing links. Del Campo adds a desktop-home crop, paired mobile browsing crops, a product-detail crop, and a full UI board, each with descriptive alt text and a complete-reference link. Peach (`#f2dfce`) remains a project image-stage color; the source UI's warm palette and Source Sans Pro are evidence inside images, not portfolio tokens.

At `700px` and below, the hero/catalog/product grids stack and product prose precedes its image. At `370px` and below, the paired browsing images become one column. These adaptations preserve the overview-to-catalog-to-product-to-foundations-to-implementation narrative and legible image inspection. No automatic motion or new interaction primitive is introduced.

## Bounded finish review

Disposition: **ship**. Independent reviewer reported persistence pass, with type, material, ground, first viewport, and narrative matching the inherited direction; mobile stacking and prose-before-product-image are appropriate adaptations. Material fixes: none. No separate quality-bar reference or composition image was supplied for this code-led extension; comparison authority was the incumbent `DESIGN.md` and the direction contract above.

Screenshot evidence: `.impeccable/review/del-campo/desktop.png`, `hero.png`, `mobile.png`, and `small-mobile.png`. Supplied execution checks: `npm run build` and `git diff --check` pass; 11 distinct internal href strings resolve in static output (fragment stripping collapses some URLs); 9 distinct local URLs return HTTP 200, covering the new route, images, Elio, home, and résumé. At 1440/390/320px, no horizontal overflow; all 5 displayed images load; anchors resolve; the skip link appears on focus and focuses main; the homepage text link navigates; no console errors. Provenance scan covers 11 rasters with zero missing records, including WebP derivative source provenance in sidecars.

No material system drift found in the sampled surface. Existing literal header divider color (`#8aaac8`) is outside the recorded global token inventory; it is preserved, not promoted into a new normative token. This bounded pass does not canonize incidental source values or repair unrelated incumbent documentation. Publication and commit remain outside scope.
