# Strut — paper meets acid

## Overview

A tactile editorial style with the energy of a studio pinboard rather than a conventional software brochure. Warm cream and near-black carry most of the page, interrupted by acid yellow, violet and blocks of pastel color. Heavy, tightly packed geometric sans headlines mingle with elegant italic serif phrases, tiny mono annotations and paper collages; broad landing-page compositions give way to denser, book-like explanations. It suits creative tools and thoughtful productivity products that need both personality and a serious account of how they work.

### Essentials

- Headlines change voice mid-sentence: Manrope 700 at 92.2px/0.88 with -0.075em tracking pairs with Newsreader 500 italic at the same size and spacing; section pairs use 72px/0.95 and -0.06em.
- The opening feels like a split editorial cover: a 48% cream text column faces 52% edge-to-edge tactile collage, under a 72px navigation bar; the headline occupies roughly five compact lines rather than a centered slogan.
- Actions are sharp little printed rectangles: 41px high, 13px/1 Manrope 600, 13px 18px padding and a 1px border; acid yellow is the primary landing-page action, black the navigation action.
- Color arrives in decisive islands, not a continuous wash: cream dominates the reading sections, near-black stages the product and the ending, violet anchors a capability panel, and #dfff3f supplies a 422px conversion band and small signals.
- Imagery has physical edges: layered paper, graphite marks and muted purple geometric fragments fill the opening; cream note slips with 22px padding, slight rotation and an 8px 10px hard shadow sit above it. Every new landing page retains a tactile collage device; layered paper and a drawn directional line are the fallback when bespoke imagery is unavailable.
- Editorial navigation is part of the character: 10px DM Mono labels with 0.12em tracking, 1px rules and squared, contiguous panels temper the expressive headlines.
- The ending is a designed statement, not just links: a near-black 335px callout carries a two-line 65px/0.95, weight-800 closing phrase and a small yellow action, followed by a spacious directory footer with tiny mono headings.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#dfff3f` | `--color-acid` | accent, action, background, text | Primary compact actions, conversion bands, drawn loops, badges, highlights and selected emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Studio violet | `#7e57ff` | `--color-violet` | surface, background | Main capability panel and editorial-image backing; also fills resource-library openings. |
| Apricot paper | `#e6a868` | `--color-apricot` | surface | One panel in the stacked capability mosaic. |
| Blue paper | `#b8d8fe` | `--color-blue-paper` | surface | Another panel in the stacked capability mosaic. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer black | `#111111` | `--color-night` | background, text | Directory footer and text on yellow compact buttons. |
| Printed ink | `#151515` | `--color-ink` | text, border, action | Default headings, strong outlines and dark buttons. |
| Product charcoal | `#171717` | `--color-stage` | background | Product demonstration stage and narrow proof strips. |
| Dark seam | `#333333` | `--color-dark-rule` | border, text | Separators on black and ordinary comparison-table text. |
| Soft brown ink | `#3f3d38` | `--color-list-ink` | text | Explanatory lists in long-form editorial sections. |
| Olive ink | `#3f4033` | `--color-yellow-ink` | text | Large type and supporting copy on the yellow conversion band. |
| Warm gray | `#4f4d48` | `--color-body` | text, border | Opening support copy and secondary explanatory text. |
| Reading gray | `#555555` | `--color-prose` | text | Expanded FAQ answers. |
| Paper gray | `#6c6a64` | `--color-muted` | text | Section support and compact card descriptions. |
| Graphite gray | `#777777` | `--color-annotation` | text | Footer mono headings and bottom annotations. |
| Dim silver | `#999999` | `--color-footer-body` | text | Short brand description in the footer. |
| Stage gray | `#aaaaaa` | `--color-stage-body` | text | Supporting copy on the dark product stage. |
| Silver text | `#bbbbbb` | `--color-footer-link` | link, text | Directory links against black. |
| Paper seam | `#cbc7bd` | `--color-rule` | border | Hairlines between rows, across navigation and around light editorial regions. |
| Warm paper | `#f3f0e8` | `--color-canvas` | background, surface | Default page canvas and floating note slips; the header uses this hue at 0.94 alpha over the same paper. |
| Clean white | `#ffffff` | `--color-white` | text, surface | Light cards and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial image grids | Editorial orange | `#f47b31` | `--color-orange` | surface | Duotone article-art backing. |
| editorial image grids | Editorial blue | `#3478f6` | `--color-editorial-blue` | surface | Duotone article-art backing. |
| editorial image grids | Editorial green | `#a8c91a` | `--color-green` | surface | Duotone article-art backing. |
| editorial image grids | Editorial teal | `#0fb69b` | `--color-teal` | surface | Duotone article-art backing. |
| editorial image grids | Editorial pink | `#ed5b92` | `--color-pink` | surface | Duotone article-art backing. |
| comparison tables | Pale citron | `#fbffe0` | `--color-table-tint` | surface | Emphasized comparison-table column. |

## Typography

- **Manrope** — Headlines, navigation, actions and general marketing copy. Rounded geometric sans with emphatic heavy headlines and open, readable small text. Font stack: "Manrope", Arial, sans-serif.
- **Newsreader** — Italic phrases inside display headlines, paper-slip copy and prominent numerals. High-contrast editorial serif with fluid italic joins and expressive descenders. Font stack: "Newsreader", "Times New Roman", serif.
- **DM Mono** — Small topic labels, timestamps, category markings and footer headings. Light, widely tracked monospace, used as an annotation rather than a technical theme. Font stack: "DM Mono", "Courier New", monospace.
- **Georgia** — Long-form explanatory paragraphs and expanded answers. Familiar bookish serif that separates sustained reading from marketing copy. Font stack: "Georgia", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Manrope | 700 | 92.2px | 0.88 | -0.075em | size clamp(58px, 6.4vw, 104px) | Default landing-page headline. |
| display-italic | Newsreader | 500 italic | 92.2px | 0.88 | -0.075em | size clamp(58px, 6.4vw, 104px) | One meaningful phrase embedded in the default display. |
| stat | Newsreader | 500 | 80px | 0.8 | normal | fixed | Acid-yellow numeral in a narrow dark proof strip. |
| heading-lg | Manrope | 700 | 72px | 0.95 | -0.06em | size clamp(42px, 5vw, 76px) | Main marketing section leads. |
| heading-lg-italic | Newsreader | 500 italic | 72px | 0.95 | -0.06em | size clamp(42px, 5vw, 76px) | Phrase-level companion to the main section lead. |
| closing | Manrope | 800 | 65px | 0.95 | -0.05em | fixed | Two-line closing statement above the directory footer. |
| conversion | Manrope | 800 | 58px | 0.98 | -0.05em | size clamp(38px, 4.5vw, 58px) | Yellow-band conversion headline. |
| conversion-italic | Newsreader | 500 italic | 58px | 0.98 | -0.05em | size clamp(38px, 4.5vw, 58px) | Final phrase of the conversion headline. |
| feature-heading | Manrope | 700 | 48px | 1.05 | -0.045em | fixed | Large lead capability panel. |
| tile-heading | Manrope | 700 | 27px | 1.15 | normal | fixed | Stacked capability-tile titles. |
| card-heading | Manrope | 700 | 24px | 1.17 | normal | fixed | Editorial card links beneath imagery. |
| note-copy | Newsreader | 500 | 22px | 1.15 | normal | fixed | Short editorial message on a floating paper slip. |
| item-heading | Manrope | 700 | 21px | 1.65 | normal | fixed | Ruled process-list headings. |
| intro | Manrope | 400 | 18px | 1.7 | normal | fixed | Opening support copy, constrained to 530px. |
| body | Manrope | 400 | 16px | 1.65 | normal | fixed | General marketing paragraphs and section support. |
| button-lg | Manrope | 600 | 16px | 1 | normal | fixed | Conversion-band and pricing actions. |
| faq-question | Manrope | 700 | 16px | 1.65 | normal | fixed | Accordion question and plus indicator. |
| faq-answer | Georgia | 400 | 16px | 1.65 | normal | fixed | Expanded FAQ paragraphs. |
| small-body | Manrope | 400 | 14px | 1.65 | normal | fixed | Card descriptions and comparison data. |
| button | Manrope | 600 | 13px | 1 | normal | fixed | Compact primary and navigation actions. |
| text-link | Manrope | 600 | 13px | 18px | normal | fixed | Underlined section utility links. |
| nav | Manrope | 600 | 13px | 1.65 | normal | fixed | Centered navigation links. |
| footer-link | Manrope | 400 | 13px | 1.65 | normal | fixed | Directory navigation links. |
| label | DM Mono | 400 | 10px | 1.3 | 0.12em | fixed | Topic labels, short all-cap panel labels and reading-time metadata. |
| footer-label | DM Mono | 400 | 10px | 1.3 | 0.14em | fixed | Directory group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| resource-library pages | library-display | Manrope | 700 | 129.6px | 0.83 | -0.075em | size clamp(64px, 9vw, 130px) | Broad two-line title on a violet field. |
| resource-library pages | library-count | Newsreader | 400 | 70px | 75px | normal | fixed | Resource count inside a tilted outline oval. |
| resource-library pages | library-intro-heading | Manrope | 700 | 47px | 1 | normal | fixed | Narrow introductory headline beside a resource grid. |
| resource-library pages | library-intro-italic | Manrope | 700 italic | 47px | 1 | normal | fixed | Italic sans emphasis within the narrow library introduction, unlike the default serif emphasis. |
| pricing pages | plan-heading | Manrope | 700 | 44px | 1 | -0.045em | fixed | Plan names. |
| editorial and detailed feature pages | editorial-heading | Manrope | 700 | 43px | 1.08 | normal | fixed | Long-form explanatory chapter headings. |
| resource, pricing and detailed feature pages | utility-heading | Manrope | 700 | 42px | 1.05 | -0.04em | size clamp(30px, 3.4vw, 42px) | Reference sections, comparison tables and secondary FAQs. |
| pricing pages | price | Newsreader | 500 | 36px | 1 | -0.03em | fixed | Price numerals beside much smaller billing qualifiers. |
| editorial pages | pullquote | Newsreader | 500 | 34px | 1.35 | normal | fixed | Standalone principle inside an essay; give the phrase an editorial italic appearance. |
| editorial and detailed feature pages | reading | Georgia | 400 | 19px | 1.8 | normal | fixed | Sustained editorial explanation. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the serif emphasis inside the same line box as the sans headline; it is a semantic turn in the sentence, not a separate decorative subtitle.
- Tracking tightens from -0.04em at utility-heading size to -0.06em on section leads and -0.075em on the opening display. Small text generally returns to normal tracking; mono labels expand instead.
- The default reading mode is sans. Georgia belongs to expanded answers and sustained editorial prose, not buttons or navigation.
- The standalone editorial quote looks italic even though its text declaration uses the regular Newsreader recipe; preserve the visual inflection.

## Layout

**Density:** Airy at the section level, with compact ruled lists and directory links inside generous editorial fields.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 9px | Vertical directory-link gap and editorial list-item margins. | fixed |
| 12px | Headline-to-description rhythm in article cards and price qualifier gaps. | fixed |
| 18px | Tool-grid gaps and conversion-action stack gaps. | fixed |
| 24px | Process-row vertical padding and article-grid column gaps. | fixed |
| 28px | Standard marketing side gutter and tool-card padding. | fixed |
| 32px | Capability-tile and resource-card padding. | fixed |
| 34px | Navigation link and opening action gaps. | fixed |
| 40px | Opening support-to-action separation and heading-pair gap. | fixed |
| 48px | Footer side gutters and article-grid row gap. | fixed |
| 60px | Directory grid gaps and article-grid top separation. | fixed |
| 70px | Major split-grid gap and capability-grid top separation. | fixed |
| 85px | Conversion-band vertical padding. | fixed |
| 105px | Dark closing-call vertical padding. | fixed |
| 120px | Default section vertical padding. | fixed |
| 28px | Full-bleed product-stage and conversion-band side padding. | max(28px,calc((100vw - 1600px)/2 + 48px)) |

### Containers and grids

- **page-shell**: max width 1600px · side padding 28px. Centered wide marketing sections. Full-bleed color bands continue beyond the constrained content.
- **opening-split**: max width 1600px · 2 columns · gap 0px. 48% text and 52% imagery; text column has 60px side insets and 126px top inset.
- **navigation-shell**: max width 1600px · 3 columns · side padding 34px. Flexible brand zone, intrinsic centered link group, flexible right-aligned action zone.
- **tool-grid**: 3 columns · gap 18px. Equal outlined light cards.
- **article-grid**: 3 columns · gap 24px. Image-first editorial cards; 48px row gap.
- **joined-grid**: 4 columns · gap 1px. Contiguous audience or assurance cards divided by thin lines rather than floating in space.
- **feature-mosaic**: 2 columns · gap 0px. 1.15fr violet lead panel beside 1fr stacked feature panels.
- **faq-width**: max width 1340px. Broad left-aligned accordion under a section heading.
- **footer-grid**: max width 1600px · 4 columns · gap 60px · side padding 48px. 2fr brand column and three 1fr directory columns; remaining groups begin a second row.
- **prose-shell** (only for editorial and detailed feature pages): max width 1200px · 2 columns · side padding 28px. 170px side-label rail beside a 974px reading column at desktop.
- **library-split** (only for resource-library pages): 2 columns · gap 80px. 0.6fr introduction beside 1.4fr two-column resource index.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and panels | 0px |
|  | Graphic disk | 50% |
| resource-library openings | Resource-count oval | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Paper slip | `rgba(0, 0, 0, 0.22) 8px 10px 0px 0px` | Hard offset shadow on the collage's floating paper notes; not a general card elevation. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing and reading canvas.

**CSS:** `background: #f3f0e8; color: #151515`

#### Translucent navigation · level 1

**Use:** Top navigation band.

**CSS:** `background: rgba(243, 240, 232, 0.94); backdrop-filter: blur(12px); border-bottom: 1px solid #cbc7bd`

**Observed:** The translucency stays warm and almost opaque, rather than appearing as blue glass.

#### Product stage · level 0

**Use:** A contrasting field for the detailed product demonstration.

**CSS:** `background: #171717; padding: 120px 28px`

**Observed:** Light interface imagery sits within the dark field beneath a white headline.

#### White ruled panel · level 1

**Use:** Utility cards and comparison enclosures.

**CSS:** `background: #ffffff; border: 1px solid #151515; border-radius: 0px; box-shadow: none`

**Transfer:** Let the rule, not a shadow, separate the content from paper.

#### Violet panel · level 1

**Use:** Lead capability panel.

**CSS:** `background: #7e57ff; border-right: 1px solid #151515; padding: 42px; overflow: hidden`

**Observed:** A cropped yellow disk intrudes at the lower-right edge.

#### Conversion band · level 0

**Use:** High-energy conversion interruption.

**CSS:** `background: #dfff3f; color: #3f4033; border-top: 1px solid #151515; border-bottom: 1px solid #151515; padding: 85px 28px`

#### Directory night · level 0

**Use:** Closing call and directory footer.

**CSS:** `background: #111111; color: #bbbbbb`

#### Tinted data cell · level 1

**Only for:** comparison tables

**Use:** Recommended plan or key metric column.

**CSS:** `background: #fbffe0; border-left: 1px solid #cbc7bd; border-bottom: 1px solid #cbc7bd; padding: 13px 18px`

## Components

### Navigation

**Use:** Shared top-level wayfinding.

**CSS:** `height: 72px; background: rgba(243, 240, 232, 0.94); border-bottom: 1px solid #cbc7bd; backdrop-filter: blur(12px)`

**Text style:** `nav` — Manrope 600 · 13px/1.65

**Observed:** Small symbol and uppercase wordmark at left; five centered text links; Dark button at right. Internal shell uses three alignment zones rather than centering the whole collection.

**States:** Declared: hover opacity 0.55 on navigation text links.

### Primary button

**Use:** Default landing-page conversion and dark closing-call action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #dfff3f; color: #111111; border: 1px solid #dfff3f; border-radius: 0px; padding: 13px 18px; height: 41px; box-sizing: border-box; transition: 0.2s`

**Text style:** `button` — Manrope 600 · 13px/1

**Observed:** Text-only, intrinsic-width rectangular action; sits beside a quieter underlined alternative.

**States:** Declared: hover transform translateY(-2px).

### Dark button

**Use:** Navigation action and dark alternative to yellow.

**CSS:** `background: #151515; color: #ffffff; border: 1px solid #151515; border-radius: 0px; padding: 13px 18px; height: 41px; box-sizing: border-box; transition: 0.2s`

**Text style:** `button` — Manrope 600 · 13px/1

**Observed:** Same compact geometry as Primary button; white text replaces the acid treatment.

**States:** Declared: hover transform translateY(-2px).

### Large conversion button

**Use:** Primary action within the yellow band.

**CSS:** `background: #151515; color: #ffffff; border: 1px solid #151515; border-radius: 0px; padding: 20px 26px; height: 58px; box-sizing: border-box; transition: 0.2s`

**Text style:** `button-lg` — Manrope 600 · 16px/1

**Observed:** Stacks above a plain underlined demo link at the far right of the conversion band. Pricing uses full-width versions, outlined on the free tier and dark on the paid tier.

**States:** Declared: hover transform translateY(-2px).

### Utility link

**Use:** Secondary exploration and section-level navigation.

**CSS:** `display: flex; align-items: center; gap: 7.2px; padding-bottom: 6px; border-bottom: 1px solid #151515; color: #151515`

**Text style:** `text-link` — Manrope 600 · 13px/18px

**Observed:** Arrow remains on the text baseline; at section heads the link is right-aligned near the bottom of the heading group. Demo links use 4px bottom padding.

### Tool card

**Use:** Small, practical entry points.

**CSS:** `background: #ffffff; border: 1px solid #151515; padding: 28px; border-radius: 0px; position: relative`

**Text style:** `small-body` — Manrope 400 · 14px/1.65

**Observed:** Bold title first, compact gray explanation next, then a small underlined open-tool link. Three equal cards share a row.

**Transfer:** Make each card one concrete task, not an abstract benefit.

### Capability tile

**Use:** Secondary panels in a joined capability mosaic.

**CSS:** `background: #e6a868; border-bottom: 1px solid #151515; padding: 32px; border-radius: 0px`

**Text style:** `tile-heading` — Manrope 700 · 27px/1.15

**Observed:** Tiny mono category at top, compact two-line title below, short exploration label at the foot. The stack alternates white, apricot and pale blue.

### Paper slip

**Use:** Foreground editorial annotation in the hero art.

**CSS:** `background: #f3f0e8; padding: 22px; box-shadow: rgba(0, 0, 0, 0.22) 8px 10px 0px 0px; transform: rotate(-5deg); position: absolute; z-index: 2`

**Text style:** `note-copy` — Newsreader 500 · 22px/1.15

**Observed:** Small mono index above a brief serif thought; a second slip near the lower edge carries project-style metadata.

**Transfer:** Use product-relevant fragments or output names rather than decorative lorem ipsum.

### FAQ row

**Use:** Objection handling across page types.

**CSS:** `display: flex; justify-content: space-between; padding: 20px 0px`

**Text style:** `faq-question` — Manrope 700 · 16px/1.65

**Observed:** Native summary within a details row; parent has a 1px paper-seam top border and the last row also closes with a bottom rule. Question at left, plain plus at far right, no boxed icon. Expanded content uses faq-answer.

### Directory link

**Use:** Dense footer navigation.

**CSS:** `color: #bbbbbb`

**Text style:** `footer-link` — Manrope 400 · 13px/1.65

**Observed:** Links form left-aligned columns with 9px vertical gaps beneath widely spaced mono group headings.

**States:** Declared: hover color #dfff3f.

### Comparison table

**Only for:** pricing and resource-reference pages

**Use:** Detailed practical comparison.

**CSS:** `background: #ffffff; border: 1px solid #151515; margin-top: 30px`

**Text style:** `small-body` — Manrope 400 · 14px/1.65

**Observed:** Wide description column and narrow centered value columns; paper-colored header, mono column labels, thin internal seams, and Tinted data cell on the key column. Pricing inserts full-width category rows.

**Transfer:** Keep the row labels descriptive; use the tint to identify one useful reading path.

### Plan panel

**Only for:** pricing pages

**Use:** Paired free and paid offers.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #dfff3f; border-left: 1px solid #151515; padding: 42px 40px 40px`

**Text style:** `plan-heading` — Manrope 700 · 44px/1 · tracking -0.045em

**Observed:** Small mono plan label, large plan name, short description, top-ruled serif price, check-mark feature list, bottom-aligned full-width action and fine billing detail. The white free tier is narrower; paid tier gets a dark upper-right allowance ribbon.

## Imagery and graphics

### Tactile editorial collage

**Use:** Signature opening image and visual language for the landing page.

**Observed:** A tall edge-to-edge assemblage of off-white fibrous sheets, torn edges, translucent rectangles, purple and charcoal folded geometry, graphite loops and a cropped pencil. Soft directional shadows make it physical. Small live paper slips and an acid-yellow hand-drawn loop sit in front. The image occupies slightly more than half the opening.

**Transfer:** Make a material metaphor for the new product: pieces of work, samples or outputs arranged like a studio experiment. Minimum acceptable treatment is a photographed paper texture, three layered cut shapes, a graphite path and two readable HTML note slips.

**Build:** Fill the art column with a warm paper photograph. Layer translucent cream rectangles at different scales, one tall violet polygon and one charcoal folded triangle using SVG polygons. Add thin irregular graphite paths in SVG, then a separate 3px acid-yellow looping path with a simple arrowhead across the middle-right. Place two cream Paper slip components with opposing slight tilts. Use hard slip shadows and softer shadows under the physical shapes; keep the photograph muted so the yellow annotation remains the brightest line.

### Duotone paper studies

**Use:** Editorial article thumbnails.

**Observed:** Landscape 445px by 260px compositions show torn notes, diagrams, strings and folded geometric objects. Each image is strongly unified under a single hue: violet, teal, orange, blue, pink or green. Images remain rectangular and meet the cream page directly, followed by mono metadata and a bold article title.

**Transfer:** Use the same family of physical objects across a content series, changing the arrangement and single-color treatment rather than introducing unrelated stock illustrations.

**Build:** Compose a grayscale photograph or SVG paper study with overlapping irregular rectangles, an occasional disk and thin pencil-like paths. Map dark values to a darkened version of one editorial hue and light values to its bright backing using an SVG component-transfer duotone or a multiply-blended grayscale image over a solid color. Keep paper grain and cast shadows visible; no rounded mask.

### Light interface on a dark stage

**Use:** Detailed product demonstration.

**Observed:** A 1280px-wide light workspace sits centered on charcoal with a thin dark frame and square corners. Sidebar, main document and assistant panel are visible at once; the surrounding heading stays outside the interface. This is a broad, legible product scene rather than a floating stack of tiny device mockups.

**Transfer:** Show one coherent workflow for the new product. Preserve the light-work-surface/dark-stage contrast, clear panel hierarchy and one acid-yellow active detail; substitute a faithful simplified interface if a real product view is unavailable.

### Disk and four-point spark

**Use:** Graphic punctuation in colored feature panels and dark feature openings.

**Observed:** A 250px acid-yellow disk is partially clipped by the lower-right of the violet panel and carries a small dark four-point spark. A larger standalone yellow spark balances the detailed-feature opening.

**Transfer:** Use this simple geometric punctuation as a counterweight to text, not as an icon for every feature.

**Build:** For the mosaic, position a 250px circle at the lower-right with overflow hidden on its parent, allowing part of the disk to fall outside the panel. Center a small four-point SVG whose sides curve inward toward the center. Use dark ink inside the disk; on charcoal use an acid-yellow spark alone and rotate it slightly.

### Monochrome working collage

**Only for:** company and editorial-introduction pages

**Use:** Human-scale visual beside the opening statement.

**Observed:** Black-and-white overhead photography of hands working among rough paper at a shared table. Rectangular translucent overlays, cropped duplicates and torn diagonal edges interrupt the photo; the piece is 541px by 500px, with no rounded frame.

**Transfer:** Photograph real work rather than posed portraits. Combine one candid activity image with a few cut-paper overlays, maintaining grayscale and ample cream around it.

**Build:** Start with a monochrome working photograph. Overlay two or three partially transparent rectangular excerpts of the same photograph, offset near the bottom and right edges. Mask a narrow diagonal torn strip along one side; retain a mostly square overall silhouette.

### Icons

**Observed:** The marketing vocabulary is sparse: literal right arrows on text links, plain plus signs in FAQs, check marks in plan lists and a curved four-point spark in feature art. Icons are dark on paper or yellow on dark; they do not sit inside soft rounded tiles.

**Transfer:** Use typographic arrows and plus signs for navigation and disclosure. Reserve custom SVG geometry for the editorial spark or a small product-specific mark; avoid a large multicolor icon library.

## Section recipes

How recurring sections are built.

### First screen: Split editorial opening

**Observed:** A 72px warm translucent Navigation precedes a 913px two-column opening. The cream text side is 48% wide, the full-height Tactile editorial collage side 52%. Text has 60px side padding and 126px breathing room above the headline. The display forms about five compact lines across most of its column, with one near-final phrase in display-italic. Below it are a 530px support paragraph, then Primary button and Utility link separated by 34px, then a small availability explanation. Layers run from cream canvas to full-bleed physical collage to paper slips and yellow drawn loop. Within the first 900px the whole headline, support paragraph, both actions and most of the tall collage are visible; the final availability line and bottom of the collage continue below the fold. The next section starts below 985px.

**Transfer:** Write a specific transformation promise that can hold several short lines; emphasize its pivotal phrase in serif italic. Rebuild the physical metaphor using the collage fallback instead of replacing the right half with a generic dashboard. Resource-library openings use a full violet field with library-display and an outlined count oval; pricing opens with a broad cream mixed-type headline and no collage; company pages use a smaller monochrome work collage; detailed feature pages use charcoal, white display and yellow italic emphasis with a spark.

**Avoid:** Do not reduce the opening to a centered headline over a small rounded application card, or make the collage a narrow decorative thumbnail.

**Text style:** `display` — Manrope 700 · 92.2px/0.88 · tracking -0.075em

### Editorial heading and utility

**Observed:** A left-aligned heading-lg sentence combines heavy sans and heading-lg-italic emphasis. A Utility link sits at the far-right lower edge of the heading group, with a 40px flex gap. Major sections use 120px vertical and 28px horizontal padding; grids begin 50px to 70px below the heading.

**Transfer:** Use phrase-level contrast to identify the important idea. Keep a meaningful exploration link visually secondary, not another filled action.

**Text style:** `heading-lg` — Manrope 700 · 72px/0.95 · tracking -0.06em

### Process beside a statement

**Observed:** A narrow vertical mono label occupies a 60px rail; a large mixed-type statement and short paragraph occupy the next column; a top-ruled four-row process list occupies the right. The grid gap is 70px, and rows use 24px vertical padding, item-heading and small-body text separated by 6px.

**Transfer:** Use for a compact explanation of how any complex process grows or progresses. Adapt the number of rows to the process rather than copying the source topics.

### Dark demonstration chapter

**Observed:** Product stage holds a white mixed-type heading on the left and a muted 420px support paragraph aligned at its lower-right. The Light interface on a dark stage sits below with 64px separation. Content remains square and broad, with dark breathing room around the light frame.

**Transfer:** Demonstrate a coherent action and its surrounding context rather than a collection of unrelated UI fragments.

### Joined color mosaic

**Observed:** A heading pair leads to a single ink-outlined mosaic: 1.15fr Violet panel on the left, three stacked Capability tiles on the right. The left has a mono label high up, feature-heading below a long pause, a short paragraph and the clipped Disk and four-point spark. The right alternates white, apricot and pale blue with 32px insets.

**Transfer:** Give one core capability disproportionate space; use the stacked panels to express complementary tasks rather than an equal-card feature catalog.

### Narrow quantified strip

**Observed:** A 246px Product stage strip uses 75px vertical padding and an 80px grid gap. A bold white 48px heading sits left, an acid-yellow stat numeral with a small muted caption sits near the right, and an outlined browsing action closes the row.

**Transfer:** Use one verified count or short metric to connect the product to a useful body of proof or material. Keep the serif number prominent and its qualifier small.

### Editorial and utility grids

**Observed:** Tool cards appear in three columns with 18px gaps. Editorial image cards use three columns, 24px column gaps and 48px row gaps, with Duotone paper studies above label metadata, card-heading, small-body description and an underlined read link. Audience and assurance cards instead join in four columns with 1px seams.

**Transfer:** Choose the card construction by information type: practical action, reading material, or a compact assurance. Do not mix all three treatments into one row.

### Ruled objection handling

**Observed:** A broad heading sits over FAQ rows, usually constrained to 1340px. The default closed state is a calm sequence of 67px ruled rows, with plain plus signs at the right. Open answers switch to faq-answer; company-oriented prose can retain the larger reading recipe.

**Transfer:** Use actual practical questions and answer them directly. Keep the visual weight low so the final call remains the next strong beat.

### Bright conversion interruption

**Observed:** Conversion band is 422px tall with 85px vertical insets. A mixed conversion and conversion-italic statement wraps within 520px at left, followed by one body sentence. At right, Large conversion button sits above an underlined alternative with an 18px gap; the two columns have a 70px gap.

**Transfer:** Carry the page's central transformation into a short invitation. Preserve a bright conversion device somewhere in a new landing page, while allowing its placement to follow the narrative.

**Text style:** `conversion` — Manrope 800 · 58px/0.98 · tracking -0.05em

### Statement and directory ending

**Observed:** Directory night begins with a 335px closing-call region padded 105px 48px: a two-line closing phrase at left, Primary button aligned low at right, and a dark seam below. Beneath, a 2fr/1fr/1fr/1fr footer grid has 60px gaps, 70px vertical insets, a small brand description and grouped Directory links. Additional groups continue onto a second row; the bottom strip is separated by a dark rule and carries tiny mono copyright and a short closing thought.

**Transfer:** Retain the oversized closing phrase and substantial directory as a recognizable ending. Scale directory density to real navigation needs without simulating an empty tall footer.

**Text style:** `closing` — Manrope 800 · 65px/0.95 · tracking -0.05em

### Long-form explanatory chapter

**Only for:** company and detailed feature pages

**Observed:** A prose-shell places a small mono rail label beside a continuous reading column. editorial-heading introduces Georgia reading paragraphs; 16px sans lists and ink-underlined inline links make explanations navigable. A pullquote uses a 6px yellow left rule, 20px 35px padding and 50px surrounding margins. Simple two-column comparisons stay square and ruled.

**Transfer:** Use this mode for an argument, principle or implementation explanation. Keep the prose continuous instead of turning every paragraph into a card.

**Text style:** `editorial-heading` — Manrope 700 · 43px/1.08

### Resource-library index

**Only for:** resource-library pages

**Observed:** A violet opening carries a nearly full-width library-display and a 156px by 234px tilted outline oval containing a serif count. Below, a narrow library-intro-heading with italic sans emphasis sits beside a two-column ruled index with 32px card padding. Later sections use utility-heading above numbered reading paths, comparison tables, definitions and related links.

**Transfer:** Organize material around the decision the reader is making; let the count describe real available items rather than act as a decorative statistic.

**Text style:** `library-display` — Manrope 700 · 129.6px/0.83 · tracking -0.075em

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A wide cream display sentence with serif emphasis opens the page, followed by a small serif tagline and explanatory copy. A sharp monthly/annual segmented control precedes a joined 1fr/1.15fr plan grid. White free and acid-yellow paid panels are 660px high at desktop, with buttons aligned near the bottom. Detailed comparison and billing FAQ follow; the page proceeds directly into Directory night without a separate yellow conversion band.

**Transfer:** Distinguish plans through fill, width and clear limits, not a floating recommended-card shadow. Keep full terms near the relevant action.

**Text style:** `plan-heading` — Manrope 700 · 44px/1 · tracking -0.045em

## Page flow

**Storyline:** Concrete transformation promise → explanation of the working model → demonstration or useful detail → capability and audience evidence → practical objections → emphatic invitation and directory.

### Broad product landing page

1. **Promise** — Split editorial opening establishes the transformation and a tactile metaphor.
2. **Working model** — Large statement beside a ruled process list.
3. **Product demonstration** — Dark stage with a broad light interface.
4. **Capabilities** — Joined color mosaic and a narrow quantified strip.
5. **Useful proof** — Practical tool cards, editorial image cards and audience workflows.
6. **Trust and objections** — Joined assurance cards and ruled FAQ.
7. **Closing call** — Bright conversion interruption followed by statement and directory ending.

**Transfer:** Choose the proof forms that suit the new product; preserve the material collage, contrasting product stage and strong closing devices without copying the topic sequence.

### Educational resource collection

1. **Orientation** — Violet display opening with count oval.
2. **Selection** — Narrow introduction beside a two-column resource index.
3. **Guidance** — Ordered reading path, comparison matrix and definitions.
4. **Related action** — Related topic cards and practical next-step links.
5. **Objection handling** — Compact question list.
6. **Closing call** — Bright invitation and full dark directory ending.

**Transfer:** Use the library variant when helping a reader choose among resources, not as the default product opening.

### Commercial decision page

1. **Promise** — Broad mixed-type cream headline and explanation of what the free workspace includes.
2. **Pricing** — Billing-period selector and joined white/yellow plan pair.
3. **Comparison** — Short plain-language answer before the detailed ruled matrix.
4. **Objection handling** — Billing and cancellation questions.
5. **Closing call** — Direct transition into the black closing statement and directory.

**Transfer:** Use explicit plan limits and real terms; keep the paid offer visually stronger without inventing a third tier.

### Company position and principles

1. **Position** — Mixed-type opening beside a monochrome working collage.
2. **Problem explanation** — Long-form serif prose explains the gap between existing approaches.
3. **Principles** — Subheadings, a yellow-ruled pullquote and a simple is/is-not comparison.
4. **Fit and credibility** — Audience description, useful publishing approach and contact.
5. **Objection handling** — Common questions in the prose layout.
6. **Closing call** — Yellow conversion band and full black statement-directory ending.

**Transfer:** Write an argument for the product's approach rather than a timeline or a wall of team portraits.

### Detailed capability landing page

1. **Promise** — Charcoal opening with white display, yellow serif emphasis and spark.
2. **Capabilities** — Four joined cards describe practical operations.
3. **Working model** — Yellow process band with a violet middle step and connecting arrows.
4. **Mechanism and control** — Editorial chapters explain inputs, named operations, context and reversible changes.
5. **Objection handling** — Feature-specific FAQ.
6. **Closing call** — Yellow conversion band and dark statement-directory ending.

**Transfer:** Use the dark opening as a scoped feature-page variant and support it with inspectable details rather than repeating broad landing-page claims.

## Writing

Thoughtful, direct and craft-aware. It is confident about practical mechanisms but candid about boundaries, favoring useful explanations over breathless promises.

**Do not copy:** Do not reuse Strut's name, logo, artwork, quotations, proprietary feature names, pricing, token allowances, resource counts, privacy guarantees or other factual claims for another product. Source examples illustrate voice only; write new claims grounded in the new product.

- **Addressing the reader:** Address the reader as you and your, especially when discussing control or next actions. Refer to the product by name when explaining mechanisms; use we sparingly for a stated position.
- **Rhythm:** Headline sentences often contain a turn from an unfinished state to a useful outcome. Short paired clauses punctuate longer, concrete explanatory paragraphs. Actions are brief imperatives; punctuation is restrained and exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category, then describe a transformation through a where or that clause; italicize the pivotal outcome phrase. | 9–16 words | “The AI writing workspace where rough notes become long-form work.” |
| Section headline | Two grounded ideas joined into a short statement, often with a serif turn in the second half. | 6–12 words | “From the first fragment to the finished draft.”<br>“You provide the judgment. AI helps move the material.” |
| Supporting line | Describe the actual materials, actions and scope rather than simply restating the headline. | 20–40 words | “Ideas rarely arrive in outline order. [Brand] keeps rough notes, developed passages, structure, and the full draft connected as the work grows.” |
| Primary action | Concrete verb plus the immediate next step, with a short availability qualifier when useful. | 2–6 words | “Start writing — it's free”<br>“Create your free account” |
| Secondary action | A low-pressure invitation to inspect the product or a specific body of information. | 3–7 words | “Look around the demo first →”<br>“Explore every feature →” |
| Boundary and reassurance | State what does not happen, then explain the mechanism that makes the boundary meaningful. | One short claim plus one explanatory sentence | “It never writes unasked”<br>“Nothing is written into your document until you accept it.” |
| Closing statement | Two compact imperative clauses with parallel rhythm. | 6–9 words total | “Catch the thought. Shape the work.” |

**Words and phrasing to use:** rough; shape; develop; connected; context; material; useful; your; one deliberate operation; before; beside; inspect; keep

**Avoid:** revolutionize; 10x; effortless magic; game-changing; unleash; autopilot everything; infinite possibilities

**Rules:**

- Describe inputs, operation and result before claiming an abstract benefit.
- Keep the reader's agency explicit when automation is involved.
- A contrast should name two concrete approaches, not belittle the reader.
- Put limitations and terms next to the relevant promise or action.
- Use editorial titles that explain what the reader will learn or decide, not vague inspiration.

## Do's and Don'ts

### Do

- Use one serif-italic phrase inside the 92.2px opening display and 72px section leads.
- Let the opening collage occupy 52% of the desktop split, with full-height texture rather than a small card.
- Keep compact actions at 41px high and conversion actions at 58px, both square.
- Use 1px ink outlines for structural panels and #cbc7bd seams for reading rows.
- Separate major content chapters with 120px vertical padding while retaining compact internal rows.
- Make violet, apricot and pale-blue panels touch inside one outlined capability mosaic.
- Include mono annotations at 10px with 0.12em tracking, especially around editorial media.
- Give the ending a 65px two-line statement before the small directory navigation.

### Don't

- Do not turn the whole site into a black interface; cream remains the default reading canvas.
- Do not apply Newsreader to navigation or ordinary card paragraphs; its main role is display emphasis and select numerals.
- Do not replace hard panel edges with 16px rounded cards and diffuse elevation.
- Do not apply the Paper slip shadow to utility or pricing cards; their separation is a 1px rule.
- Do not spread every accent hue across buttons; compact primary actions use acid yellow and navigation uses ink.
- Do not use full-color lifestyle photography in the editorial thumbnail series; keep each study unified by one duotone hue.
- Do not enlarge mono labels into a technical display style; they remain small annotations around the expressive type.
- Do not convert the paid plan into a detached floating card; it shares an outlined enclosure with the free plan.

## Motion and responsive

### Motion

**Observed:**

- Compact and large filled actions declare a 0.2s transition and hover translateY(-2px).
- Navigation links declare hover opacity 0.55; directory links declare hover color #dfff3f.
- The shared help control declares hover translateY(-3px), a black background, and focus-visible outline 3px solid #dfff3f with 3px offset.

**Transfer:**

- Keep interactive movement to the small lift on rectangular actions; the physical collage and bold typography already provide the energy.
- Use the acid outline treatment when adding a visible keyboard-focus style to similarly dark controls.

**Unknown:**

- No settled animation sequence or timing for the spark and circular graphics is established.
- No general focus-visible rule for the main actions is known.

### Responsive

**Observed:**

- Declared width breakpoints include 420px, 520px, 640px, 720px, 760px, 761px, 900px, 1050px and 1100px.
- The display, section lead, conversion title and utility title use the clamp formulas recorded in their typography recipes.

**Transfer:**

- As a recommended narrow-screen adaptation, stack the opening copy before a still-substantial collage, preserving readable note slips and the yellow directional mark.
- Collapse joined mosaics and pricing panels into a ruled vertical stack rather than turning them into rounded cards.
- Move the editorial side rail above the prose and let utility links wrap beneath headings; preserve the sans/italic phrase relationship.

**Unknown:**

- Exact mobile navigation construction and breakpoint-to-component mappings are not established.
- Narrow-screen collage framing and directory ordering are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
