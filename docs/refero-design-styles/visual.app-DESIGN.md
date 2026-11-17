# Visual — editorial machine dreams

## Overview

A light, editorial technology style that pairs elegant, tightly set serif headlines with utilitarian monospaced copy. Warm white and deep olive canvases frame reflective chrome sculptures, transparency checkerboards, pixel graphics and small flashes of acid yellow. It suits creative tools and workflow products that want to feel both cultured and computational, with sparse copy and image-heavy demonstrations.

### Essentials

- Editorial promises meet machine labels: serif headlines use 96px/90px with -0.05em tracking, while actions and breadcrumbs use 12px/12px uppercase monospace.
- The opening is a centered sculpture stage, not a dashboard banner: an 800px warm-white panel holds a two-line headline, 14px support, paired 40px pills and a reflective object that spills below the panel.
- Color behaves like registration marks: white, #f6f6f4 and #2c2c26 dominate almost the entire page; #fff347 and #aaa674 appear in tiny 4–8px-high segmented bars rather than broad marketing fills.
- Digital transparency is a visible material: checkerboard islands sit behind chrome and pixel objects, while the surrounding white canvas carries 2px square dots on a 24px repeat. Recreate these devices even when the product has no visual asset library.
- Actions are small capsules inside a mostly square architecture: primary buttons are 40px high with 16px horizontal padding and 9999px radius; cards use flat fills, 24px padding, 8px gutters and no shadows.
- A typographic poster interrupts the product story: a dark square with 64px padding sits inside a checkerboard band, mixing a 64px light serif statement with a 48px mono word capsule. Carry the device to a new product with an original short thesis.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive charcoal | `#2c2c26` | `--color-olive` | background, surface, text, action, border | Dark capability bands, poster, footer, primary actions and segmented marks. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal yellow | `#fff347` | `--color-yellow` | accent | Short, hard-edged registration strips layered over art; not a default button fill. |
| Registration khaki | `#aaa674` | `--color-khaki` | accent, border | Segmented graphic bars and the navigation conversion pill outline. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Headlines and light-surface titles. |
| Raised olive | `#414238` | `--color-capsule` | surface | Inline mono capsule within the dark statement poster. |
| Dark rule | `#57584b` | `--color-dark-rule` | border | Accordion dividers on olive charcoal. |
| Muted olive text | `#6d6e5e` | `--color-body` | text, link | Supporting text on light surfaces. |
| Pale olive text | `#aaab9c` | `--color-inverse-muted` | text | Descriptions and subdued controls on dark surfaces. |
| Light rule | `#d0d0c8` | `--color-rule` | border, text | Card and navigation hairlines; eyebrows on dark panels. |
| Transparency grey | `#e3e3de` | `--color-checker` | background, accent | Checkerboard squares and subtle dot-grid markings. |
| Pale khaki | `#e8e7d9` | `--color-nav-tint` | action, surface | Small navigation conversion pill. |
| Warm paper | `#f6f6f4` | `--color-paper` | background, surface | Opening panel, feature cards and illustration backings. |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Dotted page canvas, white interface panels, reversed text and inverse actions. |

## Typography

- **fontSerif** — Hero, section headlines and editorial titles. High-contrast editorial serif with fine hairlines, compact joins and tightly fitted letterforms. If unavailable, use **Bodoni Moda**. Use 300–400 where available and retain compact line heights and negative tracking. Font stack: "fontSerif", "Bodoni Moda", Georgia, serif.
- **fontMono** — All supporting prose, labels, navigation, actions and utility headings. Readable typewriter-like monospace; medium-weight small text with a technical but conversational character. If unavailable, use **IBM Plex Mono**. Use 500 for marketing text and controls. Font stack: "fontMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | fontSerif | 400 | 96px | 0.9375 | -0.05em | Centered two-line opening promise. |
| heading-lg | fontSerif | 300 | 64px | 1 | -0.05em | Major centered section headings, dark capability headline and statement poster. |
| heading | fontSerif | 300 | 48px | 1 | -0.025em | Headlines within paired feature panels. |
| poster-word | fontMono | 300 | 48px | 1 | -0.0667em | The single highlighted word in the statement poster. |
| article-featured | fontSerif | 400 | 32px | 1.125 | -0.025em | Lead editorial card title. |
| utility-heading | fontMono | 500 | 28px | 1 | -0.025em | Audience or application column titles. |
| article-title | fontSerif | 400 | 24px | 1.125 | -0.025em | Secondary editorial card titles. |
| card-heading | fontMono | 500 | 20px | 1 | -0.025em | Short benefit card titles. |
| accordion-title | fontMono | 500 | 20px | 1.414 | normal | Capability accordion controls. |
| accordion-body | fontMono | 500 | 20px | 1.33333 | -0.025em | Expanded capability explanation on the dark band. |
| body | fontMono | 500 | 16px | 1.33333 | -0.025em | Centered section support and benefit card descriptions. |
| body-small | fontMono | 500 | 14px | 1.33333 | -0.025em | Feature-panel and audience-column descriptions. |
| hero-support | fontMono | 500 | 14px | 1.414 | normal | The compact centered opening support line. |
| label | fontMono | 500 | 12px | 1 | normal, uppercase | Actions, navigation, breadcrumbs, dates and small section labels. |

**Notes:**

- The largest serif sizes tighten to -0.05em; panel and editorial titles relax to -0.025em. Keep the serif light rather than substituting bold grotesk headings.
- Monospace is the ordinary prose voice, not just a code accent. Reserve serif for major promises and editorial titles.
- Support lines are visually small relative to headlines: 14px in the opening, 16px below major section headings, usually constrained to 480px.

## Layout

**Density:** Airy between chapters, compact within modules; large media areas sit inside narrow-gutter grids.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Page inset, grid gutters and spacing between paired actions. |
| 12px | Eyebrow-to-headline and footer-link spacing. |
| 16px | Headline-to-section support and media-to-editorial title spacing. |
| 24px | Panel and card padding; space above opening actions. |
| 32px | Footer vertical padding and heading offset below audience-column rules. |
| 64px | Section-header-to-media spacing and statement-poster padding. |
| 80px | Dark band vertical padding and several chapter separations. |
| 104px | Opening panel top padding. |
| 128px | Larger separations before paired panels, audience grid and footer. |

### Containers and grids

- **main-grid**: max width 1536px · 12 columns · gap 8px · side padding 24px. Centered desktop grid inside 8px page insets. Full content spans 1376px at a 1440px viewport; most product media uses the centered inner ten columns.
- **support-measure**: max width 480px. Centered section explanations.
- **hero-support-measure**: max width 640px. Opening explanation beneath the narrower two-line headline.
- **three-column-grid**: 3 columns · gap 8px. Benefit cards, audience columns and the lower gallery row.
- **paired-panels**: 2 columns · gap 8px. Equal square panels in a centered ten-column region, each about 569px wide on desktop.
- **editorial-grid**: 4 columns · gap 8px. A double-width lead article beside two single-width articles.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pills | 9999px (pill) |
| navigation-tray | 4px |
| editorial-media | 6px |
| small-icon-tiles | 8px |

## Surfaces and depth

### Surfaces

#### Dotted canvas · level 0

**Use:** Exposed page background between chapters.

**CSS:** `background-color: #ffffff; background-image: radial-gradient(circle, #e3e3de 1px, rgba(0,0,0,0) 1px); background-size: 24px 24px; background-position: 15px 15px`

**Observed:** Tiny square registration dots repeat across white; solid section panels cover the grid rather than tinting it.

**Transfer:** For exact square dots, replace the circular CSS dots with a 24px SVG tile containing a 2px square.

#### Paper panel · level 1

**Use:** Opening stage, benefit modules and illustration backings.

**CSS:** `background-color: #f6f6f4; box-shadow: none`

**Observed:** Flat, nearly white and warm, with mostly square edges.

**Transfer:** Separate sections by subtle material changes, not floating shadows.

#### Olive band · level 1

**Use:** Capability chapter, reversed feature panel, statement poster and footer.

**CSS:** `background-color: #2c2c26; color: #ffffff; box-shadow: none`

**Observed:** A solid dark olive, not neutral black; white headlines contrast with pale olive body copy.

**Transfer:** Use for a small number of decisive full-width or square interruptions among light chapters.

#### Transparency field · level 0

**Use:** Checkerboard backing for the statement poster and organic art islands.

**CSS:** `background-color: #ffffff; background-image: linear-gradient(45deg, #e3e3de 25%, rgba(0,0,0,0) 0px), linear-gradient(-45deg, #e3e3de 25%, rgba(0,0,0,0) 0px), linear-gradient(45deg, rgba(0,0,0,0) 75%, #e3e3de 0px), linear-gradient(-45deg, rgba(0,0,0,0) 75%, #e3e3de 0px); background-size: 21.6px 21.6px; background-position: 0px 0px, 0px 10.8px, 10.8px -10.8px, -10.8px 0px`

**Observed:** The transparency motif is a deliberate graphic material, both full-band and clipped into irregular islands.

**Transfer:** Use checkerboard as an editing metaphor behind real content, not as an empty media area.

## Components

### Navigation tray

**Use:** Persistent small navigation centered above the content.

**CSS:** `display: flex; align-items: center; height: 32px; padding: 0px 4px; background-color: #ffffff; border: 1px solid #d0d0c8; border-radius: 4px`

**Text style:** `label` — fontMono 500 · 12px/1 · uppercase

**Observed:** A compact link tray floats independently of the left brand chip and right conversion pill. The overall navigation is fixed with a 16px top offset and 32px desktop side padding; there is no full-width header fill.

**Transfer:** Keep the three separated navigation islands rather than building a large toolbar.

### Primary button

**Use:** Main conversion on light surfaces.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; background-color: #2c2c26; color: #ffffff; border-radius: 9999px`

**Text style:** `label` — fontMono 500 · 12px/1 · uppercase

**Observed:** Text-only capsule, paired with a secondary action in the opening. The dark-band variant inverts to white with olive text; the footer uses a smaller 32px inverse pill.

**States:** Declared: hover not specified; focus-visible solid 1px white outline with -1px offset.

**Transfer:** Use a short conversion verb without an oversized icon.

### Secondary button

**Use:** Low-emphasis explanation action beside the primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; background-color: #ffffff; color: #2c2c26; border: 1px solid #d0d0c8; border-radius: 9999px`

**Text style:** `label` — fontMono 500 · 12px/1 · uppercase

**Observed:** Same height and pill silhouette as the primary. A reversed outline version uses a white border and white text on the dark poster.

**States:** Declared: hover not specified; focus-visible solid 1px khaki outline with -1px offset.

### Navigation conversion

**Use:** Compact conversion action at the far right of navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 0px 12px; background-color: #e8e7d9; color: #2c2c26; border: 1px solid #aaa674; border-radius: 9999px`

**Text style:** `label` — fontMono 500 · 12px/1 · uppercase

**Observed:** A pale khaki capsule, quieter than the main conversion below the headline.

### Benefit card

**Use:** Compact outcome summary beneath large product proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; aspect-ratio: 8 / 5; padding: 24px; background-color: #f6f6f4; gap: 8px`

**Text style:** `card-heading` — fontMono 500 · 20px/1 · tracking -0.025em

**Observed:** A title sits at the upper left opposite a 48px white icon tile; the body sits near the lower edge. Tiny segmented yellow, khaki and dark bars pin the top-left edge.

**Transfer:** Pair one concrete task with one sentence of consequence using the body recipe.

### Capability accordion

**Use:** Selectable capability explanations in a dark chapter.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px 0px 16px 32px; color: #ffffff; text-align: left; border-top: 1px solid #57584b`

**Text style:** `accordion-title` — fontMono 500 · 20px/1.414

**Observed:** Small two-digit indices occupy the left indent; a 16px chevron sits on the right. One item expands to pale-olive explanation text, aligned with its title, while adjacent rows remain compact.

**Transfer:** Use three task-oriented claims connected to a single adjacent media composition.

### Audience column

**Use:** Parallel applications for distinct users or workflows.

**CSS:** `display: flex; flex-direction: column; aspect-ratio: 1 / 1; gap: 16px; border-top: 1px solid #d0d0c8`

**Text style:** `utility-heading` — fontMono 500 · 28px/1 · tracking -0.025em

**Observed:** Title and small icon share a row below a 32px top offset; a short paragraph leads to an 8:5 illustration with a paper backing. Three columns align edge to edge with narrow gutters.

### Statement poster

**Use:** Memorable thesis or closing argument.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: space-between; aspect-ratio: 1 / 1; padding: 64px; background-color: #2c2c26; color: #ffffff`

**Text style:** `heading-lg` — fontSerif 300 · 64px/1 · tracking -0.05em

**Observed:** Centered square spans half the outer grid, about 708px on desktop. A tiny breadcrumb sits above the central serif statement; one word becomes a raised olive mono capsule, and an outline pill anchors the bottom.

**Transfer:** Write a short original belief that can carry the same type-only drama.

### Footer columns

**Use:** Low-density ending with resource links and a final conversion.

**CSS:** `background-color: #2c2c26; color: #ffffff; padding: 32px 24px; min-height: 320px`

**Text style:** `label` — fontMono 500 · 12px/1 · uppercase

**Observed:** Brand name sits far left; two small link columns and a white conversion pill align near the right. A wide empty center and muted copyright/privacy line along the bottom keep the ending spare.

**States:** Declared: hover underline on text links; focus-visible not specified.

## Imagery and graphics

### Reflective sculpture stage

**Use:** Primary opening image and recurring support for capability art.

**Observed:** A glossy black-and-silver organic sculpture with hollow folds, sharp white specular edges and deep olive reflections. It is centered below the opening copy, overlaps the action zone slightly and extends beyond the warm panel. An irregular checkerboard island and thin segmented bars sit behind and in front of it.

**Transfer:** Create an original chrome knot, folded ribbon or symbolic object linked to the new product. The minimum equivalent is one convincing reflective 3D form over an irregular checkerboard island with registration bars; do not substitute a generic gradient blob.

**Build:** Render a smooth twisted torus or folded ribbon with a dark metallic material, broad white studio reflections and olive environment light. Composite it over a roughly 780px-wide asymmetric SVG path filled with the Transparency field pattern. Overlay 4–8px-high hard rectangles in olive, khaki and signal yellow, with varied lengths of 8–80px; place some across the object to establish depth.

### Layered capability collage

**Use:** Large image beside a dark-band accordion and inside feature panels.

**Observed:** White rounded interface fragments float at several depths over chrome and checkerboard. A cutout business portrait, chat panel, status lozenges and softly dimensional chart share a mostly neutral palette. The collage occupies roughly the same area as the text column but is much taller than any individual card.

**Transfer:** Show a few legible fragments of the actual product rather than a complete browser window. Use only the new product's meaningful inputs, outputs and status cues.

**Build:** Compose one 569px-wide portrait-format stage: checkerboard island at back, chrome loop behind, then three or four white UI fragments with restrained pale borders and softly rounded edges. Offset their left edges and sizes; connect them visually with two short yellow/khaki bars. Use a portrait only when a human role is relevant.

### Pixel workflow emblems

**Use:** Illustration row beneath audience or application descriptions.

**Observed:** Oversized white lightning, pointer and conversation symbols with thick stair-stepped dark extrusions sit on pale paper. Checkerboard islands and thin olive paths, arrowheads and circular endpoints make them feel like components of an editing workspace.

**Transfer:** Choose equally simple symbols appropriate to the new use cases, keeping the pixel silhouette, white face and dark offset depth.

**Build:** Draw each symbol on a coarse SVG grid with stepped corners. Add a dark copy offset diagonally behind the white face, then a dark outline. Place on an 8:5 paper rectangle above a clipped checkerboard shape. Thread 1px olive paths around the symbol with small arrowheads or hollow circular endpoints.

### Output gallery

**Use:** Image-heavy proof of the range of finished work.

**Observed:** Two wide presentation images sit above three smaller images with 8px gutters. Finished designs use olive, paper, muted gold and occasional yellow light, contrasting editorial layouts and product UI without enclosing browser chrome.

**Transfer:** Show polished real outputs in an equivalent two-over-three arrangement; let their layouts vary while keeping the surrounding gallery neutral.

### Editorial composites

**Use:** Article thumbnails near the end of the page.

**Observed:** One wide and two square images combine portrait cutouts, retro hardware, large pixel pointers, diagram rings and acid-yellow accents. Images have 6px corners, serif titles below, and small monospaced date/byline metadata.

**Transfer:** Create subject-specific editorial collages with the same cutout, diagram and checkerboard vocabulary rather than unrelated stock photos.

### Icons

**Observed:** Small monochrome utility symbols accompany titles and controls: 24px black feature icons in 48px bordered white tiles, 16px muted chevrons in accordions and a 20px white brand symbol in the navigation chip. Large pixel emblems are a separate illustration language.

**Transfer:** Use simple monochrome utility glyphs at the same visual scale; reserve thick stair-stepped forms for the large editorial illustrations.

## Section recipes

How recurring sections are built.

### First screen: Sculpture stage opening

**Observed:** A warm Paper panel begins 8px inside the page and stands 800px tall. Above it, Navigation tray floats at top center with separated brand and conversion islands. A tiny uppercase label introduces a centered serif promise spanning about half the viewport, set in two closely fitted lines at 96px/90px. A 640px-wide 14px support line follows with 12px separation, then Primary button and Secondary button form an 8px-gap pair after 24px. Behind and below the action row, the Reflective sculpture stage occupies the lower half of the first screen: checkerboard island at back, chrome object in the middle, short registration bars across both. The object spills past the panel into the slim development notice. Within the first 900px, navigation, complete headline, support, both actions and most of the object are visible; the detailed product proof begins below.

**Transfer:** Keep the centered editorial promise and tactile digital sculpture for a new landing page. If no product artwork exists, make an original chrome symbol and the checkerboard/bar layers instead of expanding a screenshot to fill the hero. Editorial or resource pages can open with a smaller serif title and the same floating navigation vocabulary.

**Avoid:** Do not turn the opening into a left-copy/right-dashboard split, place a full browser window behind the heading, or bury the sculpture entirely below the first screen.

**Text style:** `display` — fontSerif 400 · 96px/0.9375 · tracking -0.05em

### Bracketed heading and proof

**Observed:** Small 16px L-shaped corner marks bracket a broad centered chapter. A label precedes a 64px serif heading and a 480px support measure with 16px separation. After 64px, a centered product demonstration uses light and dark halves; Benefit cards continue beneath in three columns.

**Transfer:** Use corner marks to frame a major promise and accompany it with a visible input-to-output demonstration rather than adding decorative statistic claims.

**Text style:** `heading-lg` — fontSerif 300 · 64px/1 · tracking -0.05em

### Dark capability chapter

**Observed:** An Olive band uses 80px vertical and 24px side padding. The left five columns hold an eyebrow, a 64px two-line heading, a large pause and Capability accordion with a white inverse action below. A portrait-format Layered capability collage fills five columns toward the right, separated by open grid space.

**Transfer:** Group related capabilities around one rich product composition; do not add a separate illustration to every row.

**Text style:** `heading-lg` — fontSerif 300 · 64px/1 · tracking -0.05em

### Paired capability panels

**Observed:** Two approximately 569px square panels share a centered ten-column region with an 8px gutter. Paper panel and Olive band alternate; each uses 24px inset, an uppercase breadcrumb, 48px serif heading, large centered art and a compact description near the bottom.

**Transfer:** Contrast two complementary modes of the new product while preserving identical panel structure.

**Text style:** `heading` — fontSerif 300 · 48px/1 · tracking -0.025em

### Application columns

**Observed:** Three Audience columns span the full content width. Each starts with a hairline and 28px mono title, includes a short 14px description and finishes with a broad Pixel workflow emblem.

**Transfer:** Use for three applications, audiences or jobs; the parallel illustration language provides cohesion without enclosing every column in a card.

**Text style:** `utility-heading` — fontMono 500 · 28px/1 · tracking -0.025em

### Output showcase

**Observed:** A bracketed centered heading group leads into a ten-column gallery. Two 569px-wide images form the upper row and three 376px-wide images form the lower row, with 8px gaps.

**Transfer:** Present outputs at comparable scales, maintaining crisp edges and a neutral frame so the work itself supplies controlled variation.

**Text style:** `heading-lg` — fontSerif 300 · 64px/1 · tracking -0.05em

### Thesis interruption

**Observed:** A full-width Transparency field band with 80px vertical padding surrounds the Statement poster. Its 64px white serif message mixes in a single 48px monospaced word on a #414238 capsule with 2px vertical and 12px horizontal padding. A 40px white-outline pill sits at the foot.

**Transfer:** Preserve a typographic poster somewhere in the story, using a concise original belief and a visually distinct key word rather than imitating the source phrase.

**Text style:** `heading-lg` — fontSerif 300 · 64px/1 · tracking -0.05em

### Editorial tail and spare footer

**Observed:** A compact journal label precedes a four-column Editorial grid: double-width lead image/title, then two single-width cards. Images align at 296px high; titles use 32px and 24px serif, dates and bylines use 12px mono. A 128px chapter gap leads to Footer columns, a dark 320px ending with small links high on the right and legal text low on the left.

**Transfer:** Use the editorial tail when useful supporting material exists; finish with the same sparse dark footer rather than another oversized sales headline.

**Text style:** `article-featured` — fontSerif 400 · 32px/1.125 · tracking -0.025em

## Page flow

**Storyline:** Editorial promise → tangible product proof → capability chapters → applications and outputs → brand thesis → useful reading → sparse conversion ending.

### A product marketing landing page that makes an abstract creative tool feel tangible

1. **Promise** — Centered headline, compact actions and a reflective digital sculpture.
2. **Expectation setting** — Thin understated product-status notice below the opening.
3. **Product demonstration** — Bracketed outcome heading, large split input/output visual and three benefit cards.
4. **Capability chapters** — Dark accordion/collage chapter followed by paired light and dark square panels.
5. **Applications** — Three hairline-separated columns with pixel illustrations.
6. **Output proof** — Two-over-three gallery of finished examples.
7. **Brand thesis** — Dark square typographic poster isolated on checkerboard.
8. **Useful reading** — Asymmetric editorial cards with serif titles and mono dates.
9. **Closing conversion** — Small inverse action embedded in a sparse dark footer.

**Transfer:** Adapt the sequence to the new product's argument; carry the sculpture, registration graphics and thesis poster without requiring the same section count or subject matter.

## Writing

Direct, practical and confident, with a light creative wit. Benefits are expressed as work removed or output made faster, while technical vocabulary appears only where it explains a real capability.

**Do not copy:** Do not reuse the Visual name, logo, proprietary artwork, article titles, team-specific claims, time-saving numbers or source slogans. Substitute original product facts and only supported performance claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader and their team as you/your. The product is usually described through active verbs; we appears in short company-purpose links.
- **Rhythm:** Headlines are short declarative phrases. Support is usually one compact sentence, sometimes a punchy stop/start pair followed by an explanation. Actions are two to four words and visually uppercase.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Product category followed by the audience it serves. | 5–8 words | “Design Agents for Revenue Teams” |
| Opening support | Name the frustrating task, contrast the better outcome, then explain who benefits. | 20–30 words | “Stop formatting slides. Start closing deals. [Brand] helps sales, marketing, and success teams build on-brand assets instantly with AI.” |
| Section headline | Lead with an outcome or a short actionable promise. | 5–9 words | “Save your team 1 day a week”<br>“Keep every slide on-brand” |
| Benefit description | Concrete task removal followed by a useful consequence. | 10–20 words | “Skip the copy-paste loop and generate client-ready reviews instantly.” |
| Action | Plain verb-led conversion or explanation. | 2–4 words | “Join waitlist”<br>“Learn more” |
| Brand thesis | A familiar expression given one technical twist. | 6–10 words | “A picture is worth a thousand tokens” |

**Words and phrasing to use:** build; generate; personalize; on-brand; workflow; your team; in clicks, not hours; bring your own

**Avoid:** revolutionary; game-changing; unlock limitless potential; seamless synergy; exclamation-heavy hype

**Rules:**

- Use capability labels that describe a job a person recognizes.
- Keep technical specifics in supporting text rather than stacking jargon in the opening.
- Pair speed claims with a tangible output; use quantified benefits only when substantiated.
- Keep labels and actions terse enough for 12px monospaced capitals.

## Do's and Don'ts

### Do

- Keep the opening headline at 96px/90px and regular weight on desktop.
- Use 64px light serif section headings against 14–16px mono support.
- Keep 8px gutters even when media panels grow large.
- Carry the 24px repeating dot grid through exposed white areas.
- Use yellow as 4–8px signal bars across checkerboard and chrome.
- Keep feature panels square with 24px padding and alternating paper/olive fills.
- Finish with small uppercase footer links and a compact inverse action, leaving substantial empty space.

### Don't

- Do not replace the mono prose with a neutral sans-serif; the contrast with serif is structural.
- Do not use vivid yellow as a full-section canvas or the default CTA color.
- Do not add elevation shadows to the flat marketing cards.
- Do not round every panel into a 24px-radius SaaS card; most architecture is square.
- Do not spread card grids with 24–32px gutters; use 8px to preserve the contact-sheet effect.
- Do not render large pixel illustrations as thin line icons; their white faces need dark stepped depth.
- Do not style the dark bands as pure black; their olive cast is essential.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 150ms cubic-bezier(0.4,0,0.2,1).
- Accordion controls declare all-property transitions at 150ms with the same easing; chevron transforms declare 200ms.
- The navigation remains fixed during scrolling.

**Transfer:**

- Keep conversion and link feedback short and restrained; preserve the accordion chevron rotation as the primary local state cue.

**Unknown:**

- The reflective canvas object's motion and scroll choreography are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 544px, 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Opening heading classes reduce to a 60px base size; paired panels and audience columns declare full-width bases before multi-column layouts.
- Navigation links and the right-hand conversion pill declare hidden base states before the small-screen breakpoint.

**Transfer:**

- On narrow screens, stack paired panels and audience columns while retaining the paper/olive alternation, checkerboard islands and 8px outer inset.
- Reduce the sculpture stage proportionally without covering the action pair; preserve a complete readable promise before the image.

**Unknown:**

- Exact narrow-screen line wrapping, navigation replacement and final media framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
