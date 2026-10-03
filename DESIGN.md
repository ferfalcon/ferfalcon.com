---
name: Fernando Falcon
description: A typographic portfolio connecting graphic sensibility and frontend craft.
colors:
  ink: "#182b3f"
  muted: "#526477"
  blue-soft: "#dbeafe"
  accent: "#0a66c2"
  accent-hover: "#084f97"
  paper: "#fafcff"
  soft: "#edf4fb"
  line: "#cbd9e6"
typography:
  display:
    fontFamily: "Archivo, sans-serif"
    fontSize: "clamp(3.3rem, 6.7vw, 6rem)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "-.04em"
  headline:
    fontFamily: "Archivo, sans-serif"
    fontSize: "clamp(2.4rem, 4.2vw, 4rem)"
    fontWeight: 600
    lineHeight: 1.08
    letterSpacing: "-.04em"
  title:
    fontFamily: "Archivo, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "-.025em"
  body:
    fontFamily: "Hanken Grotesk, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "Hanken Grotesk, sans-serif"
    fontSize: ".875rem"
    fontWeight: 600
    lineHeight: 1.5
rounded:
  sm: "4px"
  circle: "50%"
spacing:
  gutter: "clamp(1.25rem, 4.5vw, 5rem)"
  section: "clamp(4rem, 7vw, 7rem)"
  sm: "1rem"
  md: "1.5rem"
  lg: "2rem"
  xl: "2.5rem"
components:
  button-dark:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.paper}"
    rounded: "{rounded.sm}"
    padding: "1rem 1.4rem"
  button-dark-hover:
    backgroundColor: "{colors.accent-hover}"
  text-link:
    textColor: "inherit"
  navigation:
    textColor: "{colors.ink}"
  range:
    width: "100%"
  specimen:
    backgroundColor: "#c2ddf5"
    textColor: "{colors.ink}"
    rounded: "{rounded.sm}"
    padding: "1.25rem 1.6rem 1.4rem"
  project-visual:
    rounded: "{rounded.sm}"
  image-action:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    width: "42px"
    height: "42px"
---

# Design System: Fernando Falcon

## Opening blueprint detail — 2026-10-03

The homepage header and interactive type specimen use a restrained blueprint poster treatment: a 20px drafting grid tinted from the accent at 7% with 100px major divisions at 12%, crosshair registration marks at the header rule, and construction guides behind the lettering at 24%. The specimen uses a deliberately sharper 2px corner, an inset drawing frame, a crosshair swatch, uppercase sheet lettering, and a framed weight readout inspired by the supplied blueprint poster. These are intentional exceptions for the requested blueprint surface; the grid is confined to the opening header and specimen. Existing composition, palette, copy, and interaction stay intact. Desktop and 390px mobile previews were inspected; mobile has no horizontal overflow and the keyboard slider updates the displayed weight and lettering. Production build and diff check passed.

## Overview

**Creative North Star: "The Working Typographic Specimen"**

Graphic sensibility and frontend craft share one visual language: oversized lettering, pale blue fields, open composition, and direct manipulation. The atmosphere is confident and approachable, with compact controls and quiet supporting text giving the display type room to work.

Flat surfaces and carefully aligned rules organize the content. Actual portfolio imagery supplies the visual evidence; the interactive specimen makes the typography tangible without automatic movement. This system describes the implemented local redesign.

**Key Characteristics:**
- Large Archivo lettering paired with readable Hanken Grotesk.
- Blue and ink identity with soft white reading surfaces.
- Flat rectangular imagery and lightly rounded controls.
- User-driven interaction and visible keyboard focus.

## Colors

Pale blue is a substantial surface color, balanced by dark ink and nearly white content areas.

### Primary
- **Pale Blue** (`blue-soft`): opening field, inverse contact text, and selection text.
- **Primary Blue** (`accent`): the user-selected `#0a66c2`, used for primary actions, range controls, wordmark/specimen punctuation, and focus outlines on light surfaces.
- **Deep Blue** (`accent-hover`): primary action hover, preserving light-text contrast.

### Neutral
- **Slate Ink** (`ink`): primary text and inverse contact surface.
- **Muted Slate** (`muted`): supporting descriptions and secondary metadata.
- **Soft Paper** (`paper`): main reading surface and light text on filled actions.
- **Blue Mist** (`soft`): a tonal section background.
- **Quiet Rule** (`line`): dividers for repeated information and lists.

Portfolio image stages use colors drawn from their individual projects. These are contextual presentation choices, not additional global brand accents.

**The Surface Color Rule.** Use pale blue as a field and ink as a structural counterweight; preserve readable text contrast across both.

## Typography

**Display Font:** Archivo, with sans-serif fallback.
**Body Font:** Hanken Grotesk, with sans-serif fallback.

Both families are self-hosted variable fonts with swap loading. Archivo supplies dense, confident headings; Hanken Grotesk supplies clear paragraphs, navigation, and controls. The scale is fluid rather than a fixed mathematical ratio.

### Hierarchy
- **Display:** the large headline role in the frontmatter. At the tablet breakpoint it uses `clamp(3.3rem, 7vw, 4.8rem)`; on mobile, `clamp(2.75rem, 10.5vw, 4.5rem)`.
- **Headline:** section titles use the headline role with balanced wrapping. The contact invitation is larger (`clamp(2.1rem, 5.4vw, 5rem)`, line-height `1.15`).
- **Title:** project titles use the title role. Experience titles use a smaller size (`1.25rem`, then `1.125rem` on mobile).
- **Body:** ordinary copy uses the body role. Introductory copy is fluid (`clamp(1.125rem, 1.7vw, 1.375rem)`) and limited to `40ch`; longer prose is limited to `65ch`.
- **Label:** compact control labels use the label role. Dates and weight output use tabular numerals; supporting hints use a smaller size (`.8125rem`).

**The Two Voices Rule.** Use Archivo for expressive headings and specimens; use Hanken Grotesk for reading and operating the interface.

## Layout

Content sits in a centered container capped at `1320px`, with the fluid gutter in the frontmatter. Section spacing is fluid; internal gaps repeatedly use the recorded spacing steps. Desktop layouts pair unequal columns, allowing imagery and copy to have different visual weight. Repeated experience records use ruled rows rather than individual boxes.

At `1000px` and below, the hero proportions tighten and experience descriptions move to a second row. At `700px` and below, the hero, work, and about grids become single columns; staggered project positioning resets, headings and descriptions stack, and navigation stays visible. At `370px` and below, experience dates move into their own row. Flexible footer and action groups wrap as needed.

## Elevation & Depth

There are no shadows. Depth comes from tonal section changes, image composition, borders, and contrast. Hover changes color or adds underlining without lifting content or shifting its geometry. Color transitions use `180ms ease`; reduced-motion preference disables transitions and smooth scrolling.

**The Flat Surface Rule.** Keep surfaces flat; communicate hierarchy through color, type, spacing, and rules.

## Shapes

The base form is an open rectangle. Buttons, specimen panels, and image stages share the small corner radius in the frontmatter. Circles are reserved for compact swatches and image action affordances. Thin rules divide content and control areas. Directional arrows are stroked inline SVGs with rounded stroke ends, not text glyphs.

## Components

### Buttons and text links

Filled actions use paper text on primary blue, a small radius, semibold body text, and an inline arrow. Their minimum height is `54px`; hover changes the fill to deep blue. Text links keep an open background and underline on hover, with a minimum height of `44px`. The common keyboard focus treatment is a `3px` primary-blue outline offset by `6px`; on the ink contact section it switches to pale blue.

### Navigation

The Archivo wordmark pairs with a compact row of semibold anchor links. Anchors retain `44px` minimum height, underline on hover, and stay directly accessible at mobile widths. The contact link has a persistent bottom rule. Footer links repeat the arrow language at a smaller scale.

### Project presentations

Real project imagery occupies lightly rounded, flat color stages. Supporting titles and descriptions sit below the image without an enclosing card border. A circular arrow affordance reverses from paper to ink on image-link hover. Desktop image stages may have distinct aspect ratios; mobile brings them to a shared ratio (`1.25`). Image links have descriptive accessible names and informative primary-image alt text.

### Typographic specimen and range

The specimen uses a deeper pale-blue panel, a thin border, and oversized Archivo letters. Container-relative type sizing (`82cqi`) fits the desktop panel; mobile uses `clamp(9rem, 48vw, 17rem)`. A native range changes the weight from `100` to `900` in steps of `10`, starting at `700`. The output remains numeric and stable in width.

Controls are exposed only when the script is ready. The native range supports pointer and keyboard input, a visible label, a descriptive hint, and the shared focus outline. Without JavaScript, the specimen remains visible with static explanatory text. No motion runs automatically.

### Ruled information rows

Capabilities and experience use thin separators, open backgrounds, aligned labels, and muted descriptions. Their columns collapse responsively while preserving reading order; dates remain distinct through tabular numerals and compact typography.

## Do's and Don'ts

### Do:
- **Do** pair expressive Archivo headings with Hanken Grotesk reading and control text.
- **Do** use real portfolio imagery and preserve its proportions.
- **Do** maintain visible focus, native range interaction, and reduced-motion support.
- **Do** use tonal fields and thin rules to organize open layouts.

### Don't:
- **Don't** add shadows to this flat surface system.
- **Don't** turn project-specific image-stage colors into global brand accents.
- **Don't** animate the specimen automatically or hide essential content behind JavaScript.
- **Don't** replace the inline SVG arrow with a text glyph.
