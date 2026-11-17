# shadcn — components as the canvas

## Overview

A light, monochrome style that makes useful interfaces feel like the main attraction. Black and pale gray grotesk typography sits above a dense gallery of softly rounded product fragments, with very little decorative imagery. It suits developer tools, configurable software and product libraries whose strongest argument is the product itself.

### Essentials

- The promise is a compact typographic banner, not a billboard: centered Geist 48px/1.1, weight 600 and -0.05em tracking, with an 896px text limit.
- The first screen pairs a small announcement with immediate working proof: 80px of breathing room below a 64px navigation bar, 16px between text levels, then product fragments beginning around 415px down the page.
- Conversion controls look like compact interface controls: black primary and pale-gray secondary buttons, 26px corners, 35–36px heights and 14px/20px medium text.
- The marketing shell is entirely neutral: white canvas, #f5f5f5 staging and black actions; chromatic color stays inside product data or tiny functional indicators rather than filling marketing sections.
- The signature image is an interface quilt: four 330px columns with 24px gutters, white 24px-radius cards and restrained edge shadows. Every landing page needs tangible interface proof; when finished product media is unavailable, construct representative task panels instead.
- The gallery dissolves rather than stops abruptly: a 256px white-to-transparent closing veil merges the product field into a centered 96px attribution footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Hero text, navigation and primary marketing actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control charcoal | `#171717` | `--color-control-ink` | text | Secondary action and announcement text. |
| Muted gray | `#737373` | `--color-muted` | text | Secondary descriptions and attribution. |
| Hairline gray | `#e5e5e5` | `--color-edge` | border | Preview frames and fine separators. |
| Interface wash | `#f5f5f5` | `--color-wash` | surface, background | Gallery stage, secondary actions, search and tab tracks. |
| Inverse text | `#fafafa` | `--color-inverse` | text | Labels on black actions. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Page, header and card backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interactive example galleries | Resize grid gray | `#d4d4d4` | `--color-dot` | accent | Fine dot backing behind resizable preview frames. |
| product demonstrations | Product ink | `#0a0a0a` | `--color-product-ink` | text | Titles and content inside the interface quilt. |

## Typography

- **Geist** — All headings, descriptions, navigation and interface labels. Contemporary grotesk with compact proportions, open counters and a matter-of-fact software voice. Font stack: "Geist", "Geist Fallback", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 600 | 48px | 1.1 | -0.05em | Centered opening promise. |
| lead | Geist | 400 | 18px | 28px | normal | Balanced supporting paragraph beneath the promise. |
| item-heading | Geist | 500 | 16px | 24px | normal | Interface panel titles and gallery category links; use this restrained level rather than inventing oversized chapter headings. |
| action | Geist | 500 | 14px | 20px | normal | Navigation, buttons and short descriptive preview links. |
| body-small | Geist | 400 | 14px | 20px | normal | Descriptions inside product panels. |
| attribution | Geist | 400 | 14px | 2 | normal | Centered footer sentence. |
| attribution-link | Geist | 500 | 14px | 2 | normal | Underlined links embedded in the footer sentence. |
| small-label | Geist | 500 | 12px | 16px | normal | Announcement pill and compact utility actions. |

**Notes:**

- Only the display uses strongly negative tracking. All smaller levels retain normal tracking.
- Weight 500 carries interface hierarchy; reserve 600 for the main promise. Keep support copy black in the opening and muted gray inside demonstrations.
- No separate oversized section-heading ladder is needed: examples are introduced by compact labels and descriptive links.

## Layout

**Density:** Airy opening over a compact product field: text gets breathing room while panels pack several useful controls into a small area.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Icon-to-label gaps and compact panel title/support separation. |
| 8px | Action-pair gap and header utility spacing. |
| 16px | Announcement-to-headline and headline-to-support gaps; preview toolbar-to-frame gap. |
| 20px | Panel inner padding and vertical content spacing. |
| 24px | Interface-quilt gutters, outer inset and support-to-action separation. |
| 40px | Desktop example grid gaps. |
| 48px | Opening bottom space before the product quilt. |
| 80px | Opening top padding and catalog-opening bottom padding. |
| 96px | Long-form preview separation and footer height. |

### Containers and grids

- **opening-copy**: max width 896px · side padding 24px. Centered, balanced headline and supporting paragraph.
- **interface-quilt**: max width 1600px · 4 columns · gap 24px · side padding 24px. Full-width proof stage with independently stacked columns; cards do not share a fixed row height.
- **content-container** (only for example galleries): max width 1400px · side padding 32px. Centered catalog body. At a 1440px viewport the inner examples span 1336px.
- **example-grid** (only for data example galleries): 3 columns · gap 40px. One full-width interactive lead example followed by smaller repeated examples.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | hero-actions | 26px |
|  | announcement | 9999px (pill) |
|  | quilt-panels | 24px |
|  | search-and-tab-track | 10px |
| interactive example galleries | preview-frame | 14px |
| interactive example galleries | utility-controls | 8px |
| interactive example galleries | selected-tab | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| panel-edge | `0px 0px 0px 1px rgba(23,23,23,0.05), 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Soft definition around white panels, not floating elevation. |

### Surfaces

#### Canvas · level 0

**Use:** Default background and header.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat opaque white, with no texture or atmospheric lighting.

**Transfer:** Use the canvas to let the product's small-scale structure supply detail.

#### Quilt stage · level 0

**Use:** Neutral backing for the interface gallery.

**CSS:** `background: #f5f5f5; position: relative; overflow: hidden; padding: 24px 24px 0px`

**Observed:** A 480px upper backing gradient moves from white through the stage gray to transparent, beneath the panels.

**Transfer:** Keep the background lighter than any strong interface marks.

#### Soft panel · level 1

**Use:** Individual product fragments.

**CSS:** `background: #ffffff; border-radius: 24px; box-shadow: 0px 0px 0px 1px rgba(23,23,23,0.05), 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1); overflow: hidden`

**Observed:** Panels have unequal heights and contain real task structure rather than feature illustrations.

**Transfer:** Treat every panel as a coherent small workflow.

#### Closing veil · level 2

**Use:** Dissolve the lower portion of the quilt into the footer.

**CSS:** `background: linear-gradient(to top, #ffffff 0%, rgba(245,245,245,0.8) 50%, rgba(0,0,0,0) 100%); height: 256px; position: absolute; bottom: 0px; left: 0px; right: 0px; pointer-events: none`

**Observed:** The veil overlays the bottom of the cards, progressively softening text, edges and controls.

**Transfer:** Apply to decorative proof only, not to content the reader must finish reading.

#### Preview frame · level 1

**Only for:** interactive example galleries

**Use:** Large live-demo window.

**CSS:** `background: #ffffff; border: 1px solid #e5e5e5; border-radius: 14px; overflow: hidden`

**Observed:** A broad, nearly full-container frame sits below a compact control toolbar.

**Transfer:** Keep surrounding chrome minimal so the demonstration remains the main object.

## Components

### Navigation link

**Use:** Compact desktop navigation in an opaque 64px sticky header.

**CSS:** `height: 32px; padding: 0px 10px; border-radius: 8px; color: #000000; display: inline-flex; align-items: center`

**Text style:** `action` — Geist 500 · 14px/20px

**Observed:** Links run closely together on the left; search and utility controls align on the right. Header side padding is 24px.

**States:** Declared: hover background #f5f5f5 and text #171717; focus-visible border uses a mid-gray ring color; active opacity 1.

### Primary button

**Use:** The main opening action.

**CSS:** `background: #000000; color: #fafafa; border: 1px solid transparent; border-radius: 26px; height: 35px; padding: 0px 12px; display: inline-flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `action` — Geist 500 · 14px/20px

**Observed:** Content-sized and paired with a neutral secondary action; not a wide promotional slab.

**States:** Declared: hover background becomes black at 80% opacity; focus-visible border uses a mid-gray ring color; active opacity 1 and translate 0 0.

### Secondary button

**Use:** Explore or learn-more companion to the main action.

**CSS:** `background: #f5f5f5; color: #171717; border: 1px solid transparent; border-radius: 26px; height: 36px; padding: 0px 12px`

**Text style:** `action` — Geist 500 · 14px/20px

**Observed:** Sits 8px from the primary; remains low-contrast rather than outlined.

**States:** Declared: hover mixes the gray background with 5% black; focus-visible border uses a mid-gray ring color; active opacity 1 and translate 0 0.

### Announcement pill

**Use:** Short update before the opening headline.

**CSS:** `background: #f5f5f5; color: #171717; border: 1px solid transparent; border-radius: 9999px; padding: 2px 8px; height: 22px; display: inline-flex; align-items: center; gap: 4px`

**Text style:** `small-label` — Geist 500 · 12px/16px

**Observed:** A short phrase ends with a 12px right arrow. It acts as a miniature update link, not an uppercase eyebrow.

### Search trigger

**Use:** Header discovery action.

**CSS:** `background: #f5f5f5; border-radius: 10px; width: 256px; height: 32px; padding: 8px 16px 8px 12px; display: inline-flex; align-items: center; justify-content: flex-start`

**Text style:** `action` — Geist 500 · 14px/20px

**Observed:** A button styled as a subdued search field, aligned with adjacent repository and theme utilities.

### Product panel

**Use:** Working proof within the quilt.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 20px 0px; display: flex; flex-direction: column; gap: 20px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(23,23,23,0.05), 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Text style:** `item-heading` — Geist 500 · 16px/24px

**Observed:** Inner content is inset 20px horizontally. Titles lead muted support, then controls, numbers or charts; some panels have no title and directly display controls.

**Transfer:** Demonstrate a plausible task using the new product's own objects and data.

### Attribution link

**Use:** Embedded footer links.

**CSS:** `color: #737373; text-decoration: underline; text-underline-offset: 4px`

**Text style:** `attribution-link` — Geist 500 · 14px/2

**Observed:** Links belong to a single centered muted sentence rather than footer columns or a large closing campaign.

### Category link

**Only for:** example galleries

**Use:** Horizontal category navigation above examples.

**CSS:** `height: 28px; padding: 0px 16px; display: flex; align-items: center; justify-content: center; color: #000000`

**Text style:** `item-heading` — Geist 500 · 16px/24px

**Observed:** Active category is black; inactive categories are muted gray. No filled active pill or heavy underline. The row scrolls horizontally when constrained.

**States:** Declared: hover text becomes black; active opacity 1.

### Preview tabs

**Only for:** interactive example galleries

**Use:** Switch between a rendered example and its implementation.

**CSS:** `background: #f5f5f5; border-radius: 10px; height: 32px; padding: 4px; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr))`

**Text style:** `small-label` — Geist 500 · 12px/16px

**Observed:** The selected tab is a white 6px-radius chip with a tiny shadow; inactive text is subdued. A descriptive link follows, then viewport, refresh, installation and launch controls across the toolbar.

## Imagery and graphics

### Interface quilt

**Use:** Signature visual proof on a landing page.

**Observed:** A broad mosaic of white rounded cards shows controls, forms, navigation snippets, a bar chart, large numeric readouts, a chat composer and a connection code. Panels remain front-facing, at readable interface scale, with gray nested areas and black actions; the imagery takes most of the page after a short text opening.

**Transfer:** Build an equally tangible set of representative tasks. The minimum equivalent is a few convincing interface panels with real labels, meaningful values and working-looking controls, not stock photography.

**Build:** Use a four-column CSS grid with 24px gaps and separately stacked flex columns. Give the panels the Soft panel surface and 20px inner insets. Place a 480px white-to-gray-to-transparent gradient under the top and the Closing veil over the bottom. Avoid perspective, blur on the panels themselves or device mockups.

### Data demonstrations

**Only for:** data example galleries

**Use:** Visual comparison of related data-display variants.

**Observed:** A wide interactive area chart is followed by smaller white framed examples. Pale sky-blue and medium blue translucent areas, thin series outlines, faint horizontal rules and small legends stay inside the product UI; the surrounding page remains monochrome.

**Transfer:** Use data appropriate to the new product with the same light chart treatment; do not promote series colors into marketing accent bands.

### Full workflow demonstrations

**Only for:** interactive example galleries

**Use:** Show complete layouts rather than isolated controls.

**Observed:** Large front-facing preview windows contain dashboard/sidebar layouts or centered authentication forms on pale gray backings. A toolbar outside the frame gives the layout a short descriptive caption.

**Transfer:** Show a complete believable workflow in the frame. Use actual product media where available; keep any supporting photograph subordinate to the form rather than making it page-wide.

### Icons

**Observed:** Mostly 16px outline SVGs with 2px strokes and rounded caps, in black or muted gray. The announcement uses a 12px arrow; the header theme icon is 18px. Solid marks are limited to repository/provider utilities.

**Transfer:** Use a consistent rounded-stroke icon set for actions and compact navigation, keeping icons at text scale rather than turning them into feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Promise over working proof

**Observed:** An opaque 64px header sits above a white centered text opening. After 80px of top padding, the Announcement pill precedes a single-line 48px display promise by 16px; a balanced two-line 18px support paragraph follows after 16px within an 896px limit. Primary button and Secondary button sit 24px below the paragraph. The opening ends with 48px of space, and the interface quilt begins around 415px down the viewport. Within the first 900px the reader sees the complete promise, both actions and the upper portions of all four product columns; the remaining proof and the footer continue below. Layers are white canvas, soft gray stage gradient, then crisp front-facing panels.

**Transfer:** Keep the text compact enough that tangible proof appears in the first screen. For a product without ready media, construct representative task panels. Catalog variants retain the same opening typography and action pair but use 80px bottom spacing, then category navigation and either a wide leading example or full workflow previews.

**Avoid:** Do not replace the proof with a giant abstract hero illustration or enlarge the headline until it pushes all product detail below the first screen.

**Text style:** `display` — Geist 600 · 48px/1.1 · tracking -0.05em

### Task-panel proof field

**Observed:** The Interface quilt uses Product panel components with varying heights and 24px gaps. Panel labels, support and controls provide the hierarchy; there is no separate oversized section title. A lower Closing veil dissolves the field into Canvas.

**Transfer:** Let several distinct tasks substantiate the opening claim; keep each panel internally coherent rather than filling every card with a feature slogan.

### Understated ending

**Observed:** The product field gives way to a 96px footer containing a single centered Attribution sentence with Attribution link components. Long preview galleries add a centered 36px outline browse-more action before the footer, rather than a new headline or large signup band.

**Transfer:** End with one small continuation action when more examples exist, then a compact authorship or resource sentence.

### Categorized data examples

**Only for:** data example galleries

**Observed:** Category link navigation occupies a 60px band. A full-width interactive example leads a three-column Example-grid with 40px gaps. Small labels and code actions sit outside each rounded chart frame; internal titles and support remain compact.

**Transfer:** Show a leading general example, then named variations with consistent external chrome and relevant data.

### Full workflow preview chapter

**Only for:** interactive example galleries

**Observed:** Preview tabs and a descriptive link occupy a 32px toolbar, with utility controls aligned opposite. A Preview frame follows 16px below; substantial examples are separated by 96px. Captions explain what the layout does instead of acting as promotional section headings.

**Transfer:** Reuse the frame-and-toolbar construction for complete workflows or templates without inheriting the source's subject matter.

## Page flow

**Storyline:** Compact promise → tangible product proof → browsable variations or tasks → understated continuation and attribution.

### Introduce a configurable product through its working parts

1. **Promise** — Small update, centered headline, brief support and a black/gray action pair.
2. **Product demonstration** — A dense four-column quilt of task-focused interface fragments.
3. **Closing** — Proof fades into white and a one-line attribution footer.

**Transfer:** Make the product itself carry the proof rather than adding unrelated testimonials or generic feature art.

### Help visitors compare a family of data-display examples

1. **Promise** — Same centered opening system with a collection-focused description.
2. **Orientation** — A horizontal category row establishes the available families.
3. **Product demonstration** — A wide interactive lead followed by smaller named variants in a three-column grid.
4. **Closing** — A simple centered attribution sentence.

**Transfer:** Use this flow for comparable variants of a capability, keeping differences visible in the examples.

### Offer complete reusable workflows for browsing and adoption

1. **Promise** — A centered collection headline and compact action pair.
2. **Orientation** — Categories plus a small browse-all action.
3. **Product demonstration** — Repeated large framed workflows with descriptive toolbars and adoption controls.
4. **Continuation** — One centered outline browse-more button.
5. **Closing** — The shared attribution footer.

**Transfer:** Apply to a template, integration or workflow library; preserve the ability to inspect and act near each example.

## Writing

Confident, practical and developer-literate. Benefits are expressed through composability, ownership and clear actions rather than emotional superlatives.

**Do not copy:** Do not reuse the source brand names, product names, repository popularity, demo financial figures, user identities, specific ownership claims or licensing promises. Source examples illustrate syntax, not claims available to a new product.

- **Addressing the reader:** Direct you/your language in the promise and support; terse noun phrases for interface labels and imperative verbs for actions.
- **Rhythm:** Short title-case headlines, a one- or two-sentence supporting paragraph, and two-word action labels. Catalog support can use a run of short factual sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the useful foundation or category, with one restrained quality claim. | 4–8 words | “The Foundation for your Design System”<br>“Beautiful Charts & Graphs” |
| Supporting paragraph | Describe the object, then explain how the reader can use or adapt it. | 20–30 words | “Composable, accessible components with thoughtful defaults. Build your own component library with code you can customize, extend, and make your own.” |
| Primary action | A verb plus an immediate destination or next step. | 2 words | “Get Started”<br>“Browse Charts” |
| Preview caption | Plain descriptive noun phrase that identifies a concrete behavior or layout. | 6–10 words | “A sidebar that collapses to icons”<br>“A login page with a muted background color” |

**Words and phrasing to use:** build; your own; customize; extend; collection; browse; view; ready-to-use

**Avoid:** revolutionary; unleash; game-changing; magical; limitless possibilities

**Rules:**

- Make the supporting copy explain what the user can do, not merely restate the headline.
- Keep example captions descriptive and specific; use complete functionality as proof.
- State compatibility, access or pricing conditions only when true for the new product.

## Do's and Don'ts

### Do

- Keep the opening display at 48px, weight 600 and -0.05em tracking on desktop.
- Keep the action pair compact at 35–36px high with 8px separation.
- Use 24px gaps between quilt columns and vertically stacked panels.
- Use 20px panel insets and 16px/24px medium panel titles.
- Keep black primary actions distinct from #f5f5f5 secondary actions.
- Include the lower 256px dissolve on decorative interface proof.
- Keep footer attribution to one centered line in a 96px band.

### Don't

- Do not turn every control into a 48px-high marketing button; the action scale is deliberately compact.
- Do not recolor the neutral shell with chart blues or functional status colors.
- Do not apply 24px corners to every utility control; catalog tools use 6–10px corners.
- Do not add strong floating shadows or dark drop-shadow halos around panels.
- Do not introduce a serif or monospace headline; the visible type system is Geist throughout.
- Do not use a dark footer block or dense multi-column sitemap in place of the light attribution ending.
- Do not equalize all quilt card heights into a generic feature-card grid.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.15s all-property transitions with cubic-bezier(.4, 0, .2, 1).
- The announcement declares 0.15s color and box-shadow transitions; actions declare opacity 1 in active states.
- No matched page-level animation is established.

**Transfer:**

- Keep interaction feedback in the small neutral control surfaces; preserve the stable, readable product-stage composition.

**Unknown:**

- No observed entrance choreography or scroll-animation timing; broader stylesheet keyframes do not establish actual page motion.

### Responsive

**Observed:**

- Desktop navigation uses a hidden-by-default, large-screen flex treatment; search is hidden below the medium layout.
- The interface quilt has a medium-screen visibility gate.
- Data grids declare two columns at the medium layout and three at the large layout; category navigation uses horizontal overflow.
- The headline declares a smaller base text level and the 48px treatment at the extra-large layout.

**Transfer:**

- For a new narrow-screen landing page, retain a readable representative product proof rather than squeezing four columns into the viewport; select or stack a few panels as an adaptation.
- Keep the announcement, promise and actions as a centered compact stack; let catalog categories scroll instead of wrapping into a tall menu.

**Unknown:**

- Rendered mobile layouts and the intended small-screen replacement for the hidden quilt were not available.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
