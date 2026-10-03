---
version: 1
slug: "src-pages-work-figma-to-implementation-workflow-astro"
primary_target: "src/pages/work/figma-to-implementation-workflow.astro"
related_targets: ["src/components/Welcome.astro","src/components/WorkflowPath.astro","src/components/SiteHeader.astro","src/components/SiteFooter.astro","src/styles/styles.css","src/layouts/Layout.astro"]
---

# Figma to Implementation workflow

Mode: Read on the dedicated page; Persuade in the homepage feature. Audience: clients and recruiters. Scope: a distinct section below Del Campo and Elio and an editorial page from the Vault draft. Code-led ordinary extension; no new world, comp, or raster.

## Direction contract

THESIS: Connect design intent to reviewed code through inspectable evidence, including unresolved findings.

OWN-WORLD: Preserve blue/ink, Archivo/Hanken, flat fields, shared action arrows, and thin rules. Ink distinguishes the homepage feature; pale blue opens the editorial page.

STORY: Discover the process, understand Source → Plan → Code → Review, inspect three acceptance states, then explore GitHub or contact Fernando.

FIRST VIEWPORT: A large headline sits left of explanatory copy and GitHub/use-case actions, with the four-stage sequence beneath. Mobile stacks the opening and keeps two sequence columns. The homepage repeats this composition with an internal reading link.

FORM: Editorial process page with ruled evidence cases. No new-world selection or seed is required.

FINISH: Bounded finish review, verdict, and patterns recorded here. Preserve `DESIGN.md` and `.impeccable/design.json`; no system change or drift repair.

## Implemented surface patterns

`WorkflowPath.astro` supplies the static semantic ordered sequence, with labels, explanations, and top rules. Four columns become two at `700px`. Opening and evidence-case columns stack at that breakpoint; action groups wrap.

The page follows opening → principles → three ruled project records → evidence qualifications → inherited contact/resume closing. Each case pairs metadata and textual status with explanation and source links. Native anchors support reading and return navigation.

Evidence qualifications are part of the content contract:

- **myteam:** historical acceptance covers the reviewed output; later heading changes fall outside the evidence. No dedicated screen-reader/conformance claim; form sending was outside scope.
- **Tech Book Club:** blocked by the recorded hero-gradient contrast finding despite deployment and merge.
- **Insure:** proposed WordPress validation candidate; specific-workflow use and acceptance remain unestablished.
- Toolkit real-user acceptance remains pending, including its current online ChatGPT experience.
- Original design/assets credit belongs to the supplied Frontend Mentor challenges.

## Comparison with the incumbent system

Comparison used `PRODUCT.md`, `DESIGN.md`, final page/sequence/homepage source, and workflow CSS. The extension preserves incumbent tokens, Archivo/Hanken, centered container, fluid spacing, flat fields, rules, shared links, and visible focus. Scoped inverse text and page-specific type sizes remain surface treatments. The dedicated page adds no script or raster. Global design files remain unchanged. Supplied detector advisories concern color/type-ramp documentation, including incumbents; no mechanical errors were reported. Drift is preserved without repair.

## Bounded finish review

**Disposition: SHIP — no material fixes within the reviewed scope.** The reviewer checked `.impeccable/review/workflow/{desktop,mobile,home-desktop,home-mobile}.png` for composition, reading hierarchy, evidence qualifications, and responsive behavior.

Supplied execution results: build/diff/local links passed; no page overflow at `1440/390/320px` or homepage overflow at `390px`; visible skip focus moving to main; zero browser errors. These were not independently rerun by the documenter.

No new raster requires provenance. This local surface review is not full accessibility certification or a release. No publication occurred.
