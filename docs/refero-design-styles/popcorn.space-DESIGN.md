# Popcorn — airborne editorial optimism

## Overview

A light, optimistic style that makes practical software feel almost weightless. Bookish serif headlines meet compact, friendly sans-serif text, with chalky whites, pale sky blue and touches of peach and lilac. Floating product renders, soft clouds and rounded interface vignettes create an unusually spacious presentation suited to consumer services and approachable technology.

### Essentials

- Bookish promises, not tech shouting: serif headlines use untitledSerif 400 at 88px/1 with -0.025em tracking; section leads step down to 64px while retaining the same tight spacing.
- The opening is a centered promise above an airborne object: a 768px headline column, one small announcement pill, two lines of 20px support and a single 46px-high action; the product enters the lower third of the first screen and continues below it.
- Actions are small dark pebbles in a pale landscape: messinaSans 600 at 16px/24px, -0.025em tracking, 9999px radius and 32px horizontal padding; white buttons are reserved for dark panels.
- Color behaves like weather rather than branding paint: most content sits on #f7f7f7 or white; pale blue gradient cards, peach-to-blue conversion panels and fine pastel iridescent edges supply the color. Keep saturated hues inside realistic media or small interface details.
- Product proof floats rather than sitting in a browser wall: tilted light-screen devices, soft blue halos, white clouds and overlapping white UI fragments occupy more space than their short captions. Include an atmospheric product stage; without device artwork, use a clean layered interface panel over the same halo and cloud silhouette.
- The ending is a physical reveal: a light page sheet with 48px rounded bottom corners lifts visually over a #1e1e1e-to-#151515 footer; sparse link columns sit above a monumental white sans-serif wordmark at 350.8px/0.8 and -0.052em tracking. Use the new product's own name as this typographic artwork.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Iridescent butter | `#feebc6` | `--color-butter` | accent, border | Warm segment of the announcement edge. |
| Conversion peach | `#fce7cb` | `--color-peach` | accent, surface | Warm lower end of the onboarding panel. |
| Conversion mist | `#c7dbed` | `--color-mist` | accent, surface | Cool upper end of the onboarding panel. |
| Iridescent lilac | `#ead9fc` | `--color-lilac` | accent, border | Lilac segment of the announcement edge. |
| Iridescent aqua | `#d3f0f2` | `--color-aqua` | accent, border | Cool segment of the announcement edge. |
| Iridescent periwinkle | `#dbe5fa` | `--color-periwinkle` | accent, border | Blue segment of the announcement edge. |
| Iridescent pink | `#fadce6` | `--color-pink` | accent, border | Pink return segment of the announcement edge. |
| Iridescent rose | `#f4e4e9` | `--color-rose` | accent, border | Thin conic-gradient announcement edge. |
| Pearl lilac | `#ece6f5` | `--color-medallion-lilac` | accent | Pearlescent icon-disc underlayer. |
| Pearl rose | `#f3e9e9` | `--color-medallion-rose` | accent | Pearlescent icon-disc underlayer. |
| Pearl blue | `#e2edf5` | `--color-medallion-blue` | accent | Pearlescent icon-disc underlayer. |
| Feature blue wash | `#eaf0f5` | `--color-blue-wash` | surface | Visible upper feature-card wash: rgba(229,235,242,0.7) over the chalk canvas, fading toward rgba(241,244,248,0.7). |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#393737` | `--color-ink` | text, action | Primary headings and dark buttons. |
| Footer lower charcoal | `#151515` | `--color-footer-base` | background | Footer base and lower gradient stop. |
| Footer upper charcoal | `#1e1e1e` | `--color-footer-top` | background | Upper stop of the footer gradient. |
| Offer charcoal | `#222222` | `--color-panel-dark` | surface | Dark conversion offer panel. |
| Muted graphite | `#6d6c6c` | `--color-muted` | text, link | Supporting copy and navigation. |
| Silver footer text | `#969696` | `--color-footer-link` | text, link | Visible result of white at 55% opacity over the charcoal footer. |
| Pearl silver | `#d0d0d0` | `--color-medallion-silver` | accent | Pearlescent icon-disc underlayer. |
| Pearl gray | `#dadada` | `--color-medallion-gray` | accent | Pearlescent icon-disc underlayer. |
| Gradient silver | `#ededed` | `--color-middle` | surface | Neutral midpoint between blue and peach. |
| Warm hairline | `#f0efef` | `--color-edge` | border, surface | Fine card outlines, conversation bubbles and pale circular disclosure controls. |
| Chalk canvas | `#f7f7f7` | `--color-canvas` | background | Default page sheet and announcement interior. |
| Pure white | `#ffffff` | `--color-white` | surface, text, background | Inset UI panels, FAQ rows, testimonials, reverse text and occasional full-width chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| feature-detail pages | Morning sky | `#dde6ef` | `--color-sky` | background | Top of the atmospheric feature-detail opening. |
| partner-program pages | Program lavender | `#f1edf5` | `--color-program-lilac` | background | Earnings band fades from this lavender into chalk. |
| feature-detail pages | Pale blue panel | `#f1f4f8` | `--color-feature-pale` | surface | Flat demonstration panels. |
| feature-detail and partner-program pages | Soft gray text | `#888787` | `--color-secondary` | text | Secondary explanatory copy in capability and earnings cards. |

## Typography

- **untitledSerif** — Promises, section headings, card titles, FAQ questions and editorial statements. A literary, relatively low-contrast serif with broad lowercase forms and gently irregular warmth. If unavailable, use **Libre Caslon Text**. Use 400; tune line breaks before changing tracking. Font stack: "untitledSerif", "Libre Caslon Text", Georgia, "Times New Roman", serif.
- **messinaSans** — Navigation, actions, supporting copy, metrics and monumental closing lettering. Friendly contemporary grotesk; compact, rounded forms and a substantial medium weight. If unavailable, use **Inter**. Use 500–600 for most marketing text and preserve negative tracking. Font stack: "messinaSans", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| footer-word | messinaSans | 600 | 350.8px | 0.8 | -0.052em | fixed | Oversized closing name; scale it to fit the content container. |
| display | untitledSerif | 400 | 88px | 1 | -0.025em | fixed | Centered two-line opening promise. |
| price | messinaSans | 500 | 80px | 1 | -0.025em | size clamp(2.75rem, 5.6vw, 5rem) | Single large price on the dark conversion panel. |
| heading | untitledSerif | 400 | 64px | 1 | -0.025em | fixed | Default section headline. |
| heading-roomy | untitledSerif | 400 | 64px | 1.05 | -0.025em | fixed | Longer two-line section promises and explanatory chapter leads. |
| heading-proof | untitledSerif | 400 | 64px | 1.08 | -0.025em | fixed | Human proof and FAQ section leads. |
| capability-title | untitledSerif | 400 | 48px | 1 | -0.025em | fixed | Large paired capability-card titles. |
| conversion-title | untitledSerif | 400 | 38px | 1.05 | -0.025em | size clamp(1.625rem, 2.8vw, 2.375rem) | Closing onboarding and offer headings. |
| card-title | untitledSerif | 400 | 32px | 1.333 | -0.025em | fixed | Three-column benefit card titles. |
| benefit-label | untitledSerif | 400 | 30px | 1 | -0.025em | fixed | Short two-line benefits under pearl medallions. |
| question | untitledSerif | 400 | 22px | 1.5 | -0.025em | fixed | Accordion question text. |
| hero-support | messinaSans | 500 | 20px | 1.375 | -0.035em | fixed | Two short centered support lines beneath the opening promise. |
| support | messinaSans | 500 | 20px | 1.375 | -0.025em | fixed | Default section support. |
| body | messinaSans | 500 | 20px | 1.5 | -0.025em | fixed | Benefit-card copy and testimonial quotations. |
| footer-link | messinaSans | 500 | 18px | 1.556 | -0.025em | fixed | Muted footer column links. |
| action | messinaSans | 600 | 16px | 1.5 | -0.025em | fixed | Buttons, navigation and text links. |
| eyebrow | messinaSans | 600 | 14px | 1.5 | -0.025em | fixed | Announcement and category pills; sentence case. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| partner-program pages | program-number | untitledSerif | 400 | 72px | 1 | -0.03em | fixed | Large centered earnings figures. |
| editorial pages | editorial-close | untitledSerif | 400 | 72px | 1 | -0.025em | fixed | Two-line invitation over a cloud horizon. |
| recruiting pages | culture-heading | untitledSerif | 400 | 48px | 1.1 | -0.025em | fixed | Culture chapter lead and team-grid heading. |
| editorial pages | editorial-statement | untitledSerif | 400 | 40px | 1.2 | -0.025em | fixed | Large inset statement between narrative paragraphs. |
| partner-program pages | process-title | untitledSerif | 400 | 36px | 1.111 | -0.025em | fixed | Left-aligned titles beside process illustrations. |
| feature-detail pages | detail-title | untitledSerif | 400 | 32px | 1.2 | -0.03em | fixed | Text in horizontal demonstration cards. |
| editorial pages | editorial-body | messinaSans | 500 | 20px | 1.4 | -0.025em | fixed | Long-form narrative paragraphs. |
| recruiting pages | person-name | untitledSerif | 400 | 20px | 1.25 | -0.025em | fixed | Names under square team portraits. |
| feature-detail and partner-program pages | detail-body | messinaSans | 500 | 18px | 1.4 | -0.03em | fixed | Explanatory demonstration text. |
| recruiting pages | person-bio | messinaSans | 500 | 14px | 1.375 | -0.025em | fixed | Compact background and personal-interest biographies. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The serif carries emotion and hierarchy; the sans carries instructions and facts. Do not replace serif headings with an all-sans hierarchy.
- Most tracking is -0.025em at every size. Opening support tightens to -0.035em; the enormous footer lettering tightens further to -0.052em.
- Default section headings are 64px/1. Use 1.05 for longer promises and 1.08 for proof and FAQ leads rather than averaging their line heights.
- Footer lettering is container-relative in construction: 28.474cqw within the 1232px inner container. Fit a different product name with similarly dense, nearly edge-to-edge lettering.

## Layout

**Density:** Airy: small text clusters are separated by broad unpainted intervals, while UI fragments inside media stay compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight label and metadata gaps. |
| 12px | Card title-to-copy gap and accordion row gap. |
| 16px | Text-to-secondary-link gap and portrait-to-name gap. |
| 20px | Announcement-to-heading gap and paired-card gutter. |
| 24px | Page side gutter, standard section headline-to-support gap and three-column gutters. |
| 30px | Opening headline-to-support gap. |
| 40px | Testimonial inner padding and team-grid column gap. |
| 48px | Large card top padding and proof-card separation. |
| 56px | FAQ heading-to-list separation. |
| 64px | Opening top padding below navigation and smaller chapter padding. |
| 80px | Major chapter padding and heading-to-benefit-grid separation. |
| 96px | Heading-to-paired-capability-grid gap. |
| 112px | Editorial chapter padding and closing bottom breathing room. |
| 128px | Expansive feature chapter padding and process-row separation. |
| 160px | Large product-stage-to-benefits interval and process illustration-to-copy gap. |

### Containers and grids

- **main-container**: max width 1280px · side padding 24px. Centered outer container; at 1440px the usable content is 1232px wide.
- **opening-copy**: max width 768px. Centered opening headline with a narrower 576px support measure.
- **section-copy**: max width 672px. Balanced centered section heads and support.
- **benefit-grid**: 3 columns · gap 24px. Equal pale cards or icon-and-label benefits; medallion row is constrained to 1024px.
- **capability-pair**: 2 columns · gap 20px. Two 606px-wide product cards inside the main container.
- **faq-column**: max width 608px · gap 12px. Single centered accordion column.
- **editorial-column** (only for editorial pages): max width 680px · side padding 32px. Left-aligned narrative, with body paragraphs limited to 632px.
- **team-grid** (only for recruiting pages): max width 1220px · 4 columns · gap 40px. Square portraits with 48px row gaps; names and biographies align left.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-labels | 9999px (pill) |
|  | faq-rows | 14px |
|  | benefit-cards | 18px |
|  | testimonial-and-offer | 22px |
|  | onboarding-panel | 32px |
|  | capability-cards | 52px |
|  | page-sheet-bottom | 48px |
| partner-program pages | earnings-cards | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | testimonial-lift | `0px 12px 30px -20px rgba(15,30,60,0.16)` | Barely raised proof card; other primary pale cards remain flat. |
| recruiting pages | culture-photo | `0px 0px 0px 1px rgba(0,0,0,0.05), 0px 22px 48px -16px rgba(15,15,15,0.28)` | White-mounted casual photo collage. |

### Surfaces

#### Light page sheet · level 0

**Use:** Continuous default marketing canvas.

**CSS:** `background: #f7f7f7; border-radius: 0px 0px 48px 48px; overflow-x: clip`

**Observed:** The sheet sits above the dark footer, ending in conspicuous rounded lower corners.

**Transfer:** Treat the entire content area as a single light sheet rather than rounding every section.

#### Blue feature wash · level 1

**Use:** Benefit and capability cards.

**CSS:** `background: linear-gradient(rgba(229,235,242,0.7), rgba(241,244,248,0.7)); border-radius: 52px`

**Observed:** A restrained cool tint, with no visible hard edge or heavy shadow; smaller benefit cards use 18px corners.

**Transfer:** Use the wash behind light product objects, not as a saturated brand block.

#### White inset · level 2

**Use:** FAQ rows, testimonial cards and supporting interface fragments.

**CSS:** `background: #ffffff; border-radius: 14px`

**Observed:** White appears as a material change against the slightly darker canvas.

**Transfer:** Let the tonal difference establish the edge; use hairlines only for the scoped outlined cards.

#### Onboarding sunset · level 1

**Use:** Warm instructional half of a conversion stage.

**CSS:** `background: linear-gradient(to top, #fce7cb 0%, #ededed 42%, #c7dbed 100%); border-radius: 32px`

**Observed:** Blue at the top, neutral through the middle, peach along the lower edge.

**Transfer:** Keep copy on the calm left side and allow a central object to overlap the panel.

#### Offer charcoal · level 1

**Use:** Offer half of the conversion stage.

**CSS:** `background: #222222; border-radius: 22px; overflow: hidden`

**Observed:** Subtle monochrome noise overlays the panel; white type remains sharp.

**Transfer:** Use a sparse SVG noise layer at low visual contrast; the panel should read as charcoal, not speckled paper.

#### Footer charcoal · level 0

**Use:** Closing reveal behind the page sheet.

**CSS:** `background: linear-gradient(#1e1e1e 0%, #151515 100%); overflow: hidden`

**Observed:** A fine noise texture has overlay blending at 0.55 opacity, with sparse links and enormous white lettering.

**Transfer:** Generate a monochrome SVG turbulence texture and reduce its contrast before overlay blending.

#### Detail demonstration panel · level 1

**Only for:** feature-detail pages

**Use:** Step-by-step feature explanations.

**CSS:** `background: #f1f4f8; border-radius: 32px`

**Observed:** Wide flat rounded panels pair left-aligned prose with cropped device or UI imagery.

**Transfer:** Show one mechanism per panel.

#### Lavender earnings band · level 0

**Only for:** partner-program pages

**Use:** Quantified opportunity chapter.

**CSS:** `background: linear-gradient(#f1edf5 0%, #f7f7f7 100%); border-radius: 50px 50px 0px 0px`

**Observed:** A softly colored full-width band with white outlined earnings cards and peripheral clouds.

**Transfer:** Reserve this variant for a program's financial opportunity, not ordinary benefits.

## Components

### Navigation

**Use:** Compact global navigation across a spacious page.

**CSS:** `max-width: 1280px; padding: 20px 24px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action` — messinaSans 600 · 16px/1.5 · tracking -0.025em

**Observed:** Small wordmark and three subdued category triggers cluster on the left; the Primary button stands alone on the right. The full strip is 86px tall; category triggers have 8px 16px padding.

**Transfer:** Use only a few plain-language categories; keep the action visually detached.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #393737; color: #ffffff; border: 1px solid transparent; border-radius: 9999px; padding: 14px 32px; height: 46px; display: inline-flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `action` — messinaSans 600 · 16px/1.5 · tracking -0.025em

**Observed:** Text-only, compact and centered. The reversed variant on the dark offer uses white fill and charcoal text; the product-card action uses 30px horizontal padding.

**States:** Declared: hover mixes the charcoal with 15% white and keeps white text; focus-visible changes the border to a medium gray; active scale 0.97.

### Announcement pill

**Use:** Small status or category marker above a headline.

**CSS:** `background: linear-gradient(#f7f7f7, #f7f7f7) padding-box, conic-gradient(from 225deg, #f4e4e9 0deg, #ededed 36.3462deg, #feebc6 102.115deg, #d3f0f2 167.885deg, #ead9fc 221.538deg, #dbe5fa 278.654deg, #fadce6 330.577deg, #f4e4e9 360deg) border-box; border: 2px solid transparent; border-radius: 9999px; padding: 10px 20px; color: #393737`

**Text style:** `eyebrow` — messinaSans 600 · 14px/1.5 · tracking -0.025em

**Observed:** An almost invisible rainbow edge, not a colored interior. It sits 20px above the opening heading.

**States:** Declared: hover opacity 0.8.

### Pearl medallion

**Use:** Small icon backing in benefit rows and surrounding product diagrams.

**CSS:** `width: 64px; height: 64px; background: conic-gradient(#e2edf5 0%, #f3e9e9 30%, #d0d0d0 52%, #ece6f5 72%, #dadada 88%); border-radius: 9999px; display: flex; align-items: center; justify-content: center; overflow: hidden`

**Observed:** A white 45%-opacity overlay with 12px backdrop blur softens the conic underlayer. A dark line icon sits above it; related diagram discs are 56px.

**Transfer:** Keep the color barely perceptible. Use a simple category symbol rather than a multicolor illustration.

### Benefit card

**Use:** Three concise reasons to choose the product.

**CSS:** `background: linear-gradient(rgba(229,235,242,0.7), rgba(241,244,248,0.7)); border-radius: 18px; padding: 54px 24px 48px; display: flex; flex-direction: column; align-items: center; text-align: center`

**Text style:** `card-title` — untitledSerif 400 · 32px/1.333 · tracking -0.025em

**Observed:** A small white proof vignette sits above the serif title, followed by two or three short lines of Body text. Equal desktop cards measure 395px by 456px.

**Transfer:** Show a tangible micro-proof such as a price, short checklist or setup artifact rather than three generic icons.

### Capability card

**Use:** Paired large product chapters.

**CSS:** `background: linear-gradient(rgba(229,235,242,0.7), rgba(241,244,248,0.7)); border-radius: 52px; padding: 48px 32px 0px; height: 660px; overflow: hidden; text-align: center`

**Text style:** `capability-title` — untitledSerif 400 · 48px/1 · tracking -0.025em

**Observed:** Serif title, short muted summary and a Learn more link precede a large upright device. The device is clipped by the bottom edge; white UI fragments can float over it.

**Transfer:** Use two genuinely distinct product modes; keep their object scales aligned.

### FAQ row

**Use:** Practical objection handling.

**CSS:** `background: #ffffff; border-radius: 14px; padding: 22px 26px; display: grid; grid-template-columns: minmax(0px, 1fr) auto; column-gap: 16px; max-width: 608px`

**Text style:** `question` — untitledSerif 400 · 22px/1.5 · tracking -0.025em

**Observed:** Each collapsed row is 77px tall with a small pale circular plus on the right. Rows are separated by 12px, without dividers across the whole list.

**Transfer:** Use one-line customer questions where possible; let longer questions increase row height.

### Testimonial card

**Use:** Specific human proof inside an atmospheric chapter.

**CSS:** `background: #ffffff; border-radius: 22px; padding: 40px; display: flex; gap: 28px; box-shadow: 0px 12px 30px -20px rgba(15,30,60,0.16); max-width: 800px`

**Text style:** `body` — messinaSans 500 · 20px/1.5 · tracking -0.025em

**Observed:** A narrow portrait-format customer photo anchors the left; quote and small source attribution fill the right. Discrete 48px previous and next controls sit outside the card. Rating and stars are above, not embedded in the quote.

**Transfer:** Use a real situational story and a natural photo rather than a logo-only endorsement.

### Onboarding panel

**Use:** Instructional half of a closing conversion stage.

**CSS:** `background: linear-gradient(to top, #fce7cb 0%, #ededed 42%, #c7dbed 100%); border-radius: 32px; padding: 25.9px 48px; display: flex; flex-direction: column; justify-content: center; gap: 20px`

**Text style:** `conversion-title` — untitledSerif 400 · 38px/1.05 · tracking -0.025em

**Observed:** A left-aligned two-line heading precedes three numbered steps. A small tilted white confirmation badge hangs off the lower-left edge; a diagonal shine crosses that badge.

**Transfer:** Reduce setup to concrete steps and keep the playful aside short.

### Offer panel

**Use:** Decisive commercial close beside the Onboarding panel.

**CSS:** `background: #222222; color: #ffffff; border-radius: 22px; min-height: 424px; padding: 24px 36px; display: flex; flex-direction: column; align-items: flex-end; justify-content: center; gap: 24px`

**Text style:** `conversion-title` — untitledSerif 400 · 38px/1.05 · tracking -0.025em

**Observed:** Right-aligned serif promise, large sans price, small billing period and reversed Primary button. A foreground device overlaps its left edge; the price is the only dominant metric.

**Transfer:** For non-subscription products, replace the price with one equally clear commercial commitment.

### Footer link

**Use:** Sparse grouped navigation in the closing reveal.

**CSS:** `color: rgba(255,255,255,0.55); padding: 4px 0px; display: block`

**Text style:** `footer-link` — messinaSans 500 · 18px/1.556 · tracking -0.025em

**Observed:** Three columns have small brighter sans headings. A small brand symbol anchors the opposite side; three 40px dark square assistant links sit below the columns. Monumental lettering spans the bottom.

**States:** Declared: hover color becomes white.

### Earnings card

**Only for:** partner-program pages

**Use:** Compare concrete outcomes in a program.

**CSS:** `background: #ffffff; border: 1px solid #f0efef; border-radius: 16px; width: 380px; height: 360px; padding: 32px 24px 0px; display: flex; flex-direction: column; align-items: center; text-align: center`

**Text style:** `program-number` — untitledSerif 400 · 72px/1 · tracking -0.03em

**Observed:** Small pale emblem and label, oversized serif figure, tiny period suffix and muted expectation copy. The highest outcome has a fine iridescent border rather than a dark fill.

**Transfer:** Use substantiated outcomes and explain the conditions beneath each figure.

## Imagery and graphics

### Airborne product stage

**Use:** Signature opening and conversion artwork.

**Observed:** Light-screen phones have slim dark metallic frames, slight opposing tilts and soft grainy photographic edges. Two overlapping devices sit in a diffuse blue halo with small clouds drifting across them. In the opening, a roughly 771px-wide stage is larger than the support text and continues well below the fold; the closing uses one 391px by 660px tilted phone over both panels.

**Transfer:** Use your own device, packaging or cropped interface as the hero object. A minimum equivalent is two carefully masked light interface panels at opposing angles, with believable edge thickness and soft contact shadows; retain the halo and one foreground atmospheric shape.

**Build:** Create a centered 850px-wide relative stage. Put a broad ellipse behind the objects using rgba(163,198,230,0.28), blur it by 48px and fade to transparent at the edges. Place two light panels above it with opposite small rotations, thin charcoal edge layers and soft low-opacity shadows. Add white cloud groups partially in front; keep text outside the object stack.

### Cloud horizon

**Use:** Recurring atmospheric transitions, proof bands and expressive closing scenes.

**Observed:** Soft white sculpted clouds have cool cyan underside shading, occasional blush edges and very fine grain. Small clouds enter from the sides; a deep bank of overlapping clouds can fill the lower edge while the central product rises out of it.

**Transfer:** Preserve the light, tactile atmosphere without needing literal skies in the product story. The minimum is a layered soft scalloped silhouette with restrained cool underside shading, not flat cartoon cloud icons.

**Build:** In SVG, overlap five to nine ellipses with varied widths and heights into a wide cloud bank. Fill near-white, place a second offset layer behind in rgba(163,198,230,0.22), blur the rear layer by 12px and the white edges by 2px. Add a low-opacity turbulence mask for fine grain. Small side clouds use the same construction at roughly 400px by 160px; keep their centers outside the text measure.

### Dotted porcelain object

**Use:** Central explanatory illustration surrounded by small feature callouts.

**Observed:** A pale luminous globe, 664px square, carries muted blue-lilac dots describing continents. Its edge is soft, its light comes from the upper left, and four small icon/caption callouts flank it on white.

**Transfer:** Replace the globe with an object relevant to the product, but retain the pale spherical volume and orderly dot treatment. A minimum is a static SVG dotted silhouette on a softly shaded disc.

**Build:** Draw a 664px circular SVG with a near-white-to-pale-blue radial fill. Clip a regular dot pattern into the relevant silhouette, using rgba(165,187,219,0.55); shrink and soften dots toward the rim to imply curvature. Overlay a white upper-left radial highlight and keep dark strokes out of the object.

### Human conversation

**Use:** Service proof without a conventional corporate testimonial wall.

**Observed:** Three staggered message bubbles alternate pale gray and white, with circular headshots overlapping opposite edges. Small names and timestamps frame informal sans text; the whole conversation is narrow and isolated in generous whitespace.

**Transfer:** Write a brief plausible exchange demonstrating a human quality, and use real consenting people's portraits. Do not simulate a dense chat application.

### Natural photo and video fans

**Only for:** recruiting and partner-program pages

**Use:** Culture, creator proof and closing demonstration galleries.

**Observed:** Casual group photographs or vertical social videos fan out with slight rotations. Culture photos have white mounts and soft shadows; the central video is largest with smaller tilted videos behind it. Social proof uses overlapped portrait clips with fine white edges, keeping their original vivid colors.

**Transfer:** Use authentic work or customer media, not stock studio portraits. Limit the fan to a few clear items; use a circular white play control on videos.

### Team portrait wall

**Only for:** recruiting pages

**Use:** Large team roster.

**Observed:** Square 275px portraits sit against a pale blue-to-white backing with an 8px corner and a 4px white rim. Names are serif; role and short biography are subdued sans below. Four columns form a consistent grid.

**Transfer:** Use sharp, natural headshots with consistent framing and neutral light; personal biography details keep the roster human.

### Sculptural program close

**Only for:** partner-program pages

**Use:** Expressive invitation before the footer.

**Observed:** A centered 88px serif question and compact action float above a wide low mound of softly lit white popcorn-like objects at the bottom edge. A small participation count sits under the action.

**Transfer:** Use a low pile of your own simple product-related shapes; maintain near-white materials, soft overhead light and a low horizon so the invitation dominates.

**Build:** Use repeated simple SVG or 3D rounded forms, vary scale and rotation, overlap into a shallow mound across the bottom third, shade with white and low-opacity cool gray, and keep the upper half empty.

### Icons

**Observed:** Predominantly simple dark outline symbols, often 28px or 32px, on 56px–64px Pearl medallions. Small inline directional marks use 14px–16px circles or arrows; FAQ disclosure glyphs are small white strokes on very pale circular discs. Many outlined SVGs use 2px strokes with round caps.

**Transfer:** Use a consistent simple line-icon set and retain the faint circular backing. Reserve solid marks for recognizable service or social logos.

## Section recipes

How recurring sections are built.

### First screen: Centered airborne opening

**Observed:** The first screen layers a chalk canvas, compact Navigation, centered Announcement pill, two-line Display promise, Hero-support and one Primary button, then an Airborne product stage with blue glow and white clouds. Navigation occupies the top 86px. The copy group begins after 64px of breathing room, with a 768px maximum headline width; the heading itself spans about two fifths of the viewport. There is 20px between pill and heading, 30px before support, and 38px before the action. The copy cluster ends around 560px. The product stage enters around 615px and spans roughly half the viewport width; within the first 900px the complete promise, support and action are visible, but only the upper portion of the phones. The rest of the object and the benefits sit below the fold.

**Transfer:** Keep the same centered promise-to-object relationship for a different product. Use two layered interface panels and the atmospheric halo when realistic product renders are unavailable. Partner-program openings substitute a fan of vertical customer media; feature-detail openings use a single upright object on a pale blue-to-peach atmosphere. Recruiting and editorial openings retain the serif promise and restrained category marker, with culture photography or atmospheric artwork below.

**Avoid:** Do not turn this into a left-copy/right-dashboard split, a full-bleed photograph with overlaid text, or a hero crowded with several competing actions.

**Text style:** `display` — untitledSerif 400 · 88px/1 · tracking -0.025em

### Pearl benefit row

**Observed:** Three evenly spaced Pearl medallions sit above centered Benefit-label text inside a 1024px row, with 24px icon-to-label gaps. A small centered policy or context note follows 48px below.

**Transfer:** Use three short concrete benefits; keep this light enough to read as captions to the main product stage rather than another card grid.

**Text style:** `benefit-label` — untitledSerif 400 · 30px/1 · tracking -0.025em

### Heading and proof grid

**Observed:** A centered Heading or Heading-roomy with Support 24px below precedes a three-column Benefit card grid by 80px. Alternative capability chapters use the Capability card pair 96px below the heading.

**Transfer:** Choose the grid according to the story: compact proof artifacts for practical benefits, tall device cards for major product modes.

**Text style:** `heading` — untitledSerif 400 · 64px/1 · tracking -0.025em

### Object with satellite callouts

**Observed:** A white chapter uses 128px top padding, a centered Heading-roomy and support, then the Dotted porcelain object between two vertical pairs of Pearl medallion callouts. The central object is much larger than the four captions.

**Transfer:** Explain reach, reliability or a connected system through one visual anchor instead of a dense architecture diagram.

**Text style:** `heading-roomy` — untitledSerif 400 · 64px/1.05 · tracking -0.025em

### Atmospheric social proof

**Observed:** Cloud horizon fragments enter from both sides over a subtle blue-to-transparent band. A centered serif heading, pale blue rating and compact review-count link lead to one Testimonial card, with navigation controls flanking it.

**Transfer:** Use one specific story at a time, keeping the photographic proof and quotation legible against a very soft atmosphere.

**Text style:** `heading-roomy` — untitledSerif 400 · 64px/1.05 · tracking -0.025em

### Human support vignette

**Observed:** A Heading-proof and Support introduce the narrow Human conversation. Three offset message bubbles and overlapping portraits occupy the center, with substantial unpainted space below.

**Transfer:** Prove a service behavior through a small conversational moment rather than adding another feature table.

**Text style:** `heading-proof` — untitledSerif 400 · 64px/1.08 · tracking -0.025em

### Question column

**Observed:** A centered two-line Heading-proof is followed after 56px by FAQ rows in a 608px column; the chapter uses 80px vertical padding.

**Transfer:** Answer the main buying uncertainties with plain one-sentence questions.

**Text style:** `heading-proof` — untitledSerif 400 · 64px/1.08 · tracking -0.025em

### Overlapping conversion stage

**Observed:** Inside the 1280px main container, an Onboarding panel occupies the left and an Offer panel the right. A tall tilted product object bridges both panels and extends above and below them. The instructional side is lower and lighter; the offer side has right-aligned white text and a reversed button. The section has 56px top and 112px bottom padding.

**Transfer:** Keep the compositional contrast of practical steps, one decisive offer and a shared product object. Without a device render, overlap a tall clean interface panel across the seam.

**Text style:** `conversion-title` — untitledSerif 400 · 38px/1.05 · tracking -0.025em

### Monumental footer reveal

**Observed:** The Light page sheet ends with 48px bottom corners over Footer charcoal. Three sparse navigation columns sit to the right of a small brand symbol, followed by small square assistant links. The bottom is dominated by Footer-word lettering that spans nearly the full inner width and is clipped low, creating a typographic landscape.

**Transfer:** Always include the oversized name artwork and light-over-dark edge. Adjust lettering to the length of the new name rather than shrinking it to an ordinary logo.

**Text style:** `footer-word` — messinaSans 600 · 350.8px/0.8 · tracking -0.052em

### Process beside artifact

**Only for:** partner-program pages

**Observed:** Three spacious process rows pair a 360px square pale lilac-backed UI artifact with a 432px text column, separated by 160px. A small timeline pill precedes Process-title, support and an occasional text link. Rows are separated by 128px.

**Transfer:** Explain an application or earning journey with one tangible artifact per stage rather than a generic numbered timeline.

**Text style:** `process-title` — untitledSerif 400 · 36px/1.111 · tracking -0.025em

### Outcome comparison band

**Only for:** partner-program pages

**Observed:** Lavender earnings band frames a centered Heading-roomy and three Earnings cards separated by 24px. The final card's iridescent edge is the only preference cue. Small clouds sit outside the content.

**Transfer:** Present realistic outcome ranges with concise conditions, preserving the airy financial-stat treatment.

**Text style:** `program-number` — untitledSerif 400 · 72px/1 · tracking -0.03em

### Culture and curiosity close

**Only for:** recruiting pages

**Observed:** A serif chapter title introduces a Team portrait wall. Later, a playful anonymous-backer conversation and small white cards lead to a closing three-video fan: one large landscape demo in front of two smaller tilted square clips, with white rims and play buttons. Short invitation paragraphs and an Apply button lead into the shared footer.

**Transfer:** Combine credible people information with informal proof of the work; close with something candidates can watch, not a generic benefits checklist.

**Text style:** `culture-heading` — untitledSerif 400 · 48px/1.1 · tracking -0.025em

### Editorial argument and cloud invitation

**Only for:** editorial pages

**Observed:** A narrow left-aligned narrative uses a 64px serif question over 20px paragraphs spaced 28px apart. An atmospheric oval image separates the argument from a 40px serif vision statement. The closing uses a 72px two-line invitation, one button and a low cloud horizon fading into blue before the shared footer.

**Transfer:** Make a sustained argument in readable paragraphs; use the larger serif statement to mark the change from problem to conviction.

**Text style:** `editorial-statement` — untitledSerif 400 · 40px/1.2 · tracking -0.025em

### Feature explanation and present-future pair

**Only for:** feature-detail pages

**Observed:** Two pale rounded benefit panels follow an atmospheric single-device opening. A later stack of 840px by 320px Detail demonstration panels pairs left-aligned Detail-title copy with right-side UI imagery. A rounded-top blue atmospheric band holds white capsule feature disclosures. A final isolated 64px serif pair contrasts a dark present-tense line with a very pale future-tense line, then support and a technology link.

**Transfer:** Move from immediate value to understandable mechanisms, then distinguish available capability from the roadmap. Keep future wording visually secondary.

**Text style:** `detail-title` — untitledSerif 400 · 32px/1.2 · tracking -0.03em

## Page flow

**Storyline:** Plain promise → tangible product scene → practical benefits → deeper capability proof → human credibility → buying uncertainties → expressive conversion → monumental footer reveal.

### Broad product marketing and conversion

1. **Promise** — Centered serif claim, small status pill and single action above overlapping product objects.
2. **Practical proof** — Pearl benefit captions and three pale cards make cost, activation and everyday usefulness tangible.
3. **Capability chapters** — Paired tall product cards and a large central explanatory object.
4. **Human credibility** — Atmospheric customer quote, then a compact support conversation.
5. **Point of view** — A rhetorical question and cloud-framed product scene.
6. **Objection handling** — Narrow white FAQ rows.
7. **Closing conversion** — Gradient setup steps and charcoal offer joined by a foreground device, then rounded sheet edge and monumental footer.

**Transfer:** Use the emotional promise and physical product proof as the spine; choose only chapters that advance the new product's buying story.

### Recruiting and culture

1. **Invitation** — Serif mission challenge above a casual team-photo collage and short recruiting introduction.
2. **Opportunity** — Left-aligned editorial challenge beside small white role rows.
3. **People proof** — Four-column portrait roster with serif names and personal biographies.
4. **Personality** — Playful backer conversation and anonymous proof cards.
5. **Closing invitation** — Layered video demonstrations, concise invitation and application action before the shared footer.

**Transfer:** Replace sales proof with people, problems and watchable work while keeping the same airy serif and pale-material grammar.

### Partner-program recruitment

1. **Promise** — Two short imperative clauses above a fan of vertical creator media.
2. **Friction reduction** — Three medallion captions state application and participation simplicity.
3. **Process** — Artifact-and-copy rows show the journey from application to first outcome.
4. **Quantified opportunity** — Lavender band with three giant serif financial figures.
5. **Participant proof** — Overlapping portrait videos above a compact white list of concrete advantages.
6. **Objection handling** — Program-specific FAQ column.
7. **Closing invitation** — Large serif question, colloquial action, small participation count and low sculptural mound before the shared footer.

**Transfer:** Pair realistic opportunity with clear effort requirements and one relatable participant example.

### Editorial conviction and brand point of view

1. **Mission** — Centered serif title and two-line mission above cloud-framed artwork.
2. **Problem framing** — Long rhetorical serif question and readable narrative paragraphs.
3. **Vision** — Atmospheric image, compact brand declaration and a large serif statement.
4. **Argument** — Short paragraphs explain the intended change.
5. **Closing invitation** — 72px invitation and button over a pale cloud horizon, then the shared footer.

**Transfer:** Keep the readable essay structure and atmospheric punctuation; do not turn every paragraph into a card.

### Focused product-feature explanation

1. **Outcome promise** — Blue-to-warm atmospheric hero with one upright product object.
2. **Immediate benefits** — Two pale benefit cards with white interface vignettes.
3. **Mechanism** — Stacked horizontal cards explain the behavior in three small chapters.
4. **Expansion** — Cloud-backed rounded band with white capsule feature disclosures.
5. **Roadmap clarity** — Paired present and future serif lines with one line visually muted.
6. **Objection handling** — Feature-specific FAQ.
7. **Closing conversion** — Shared overlapping setup-and-offer scene and monumental footer.

**Transfer:** Separate immediate benefits, mechanism and future availability rather than making one undifferentiated feature grid.

## Writing

Practical confidence with a mischievous human streak. It speaks about a technical service in everyday language, promising less hassle rather than abstract transformation.

**Do not copy:** Do not reuse the Popcorn name, logos, proprietary artwork, employee identities, customer quotes, prices, country counts, earnings claims, review counts or product-specific promises. Source examples illustrate cadence only; substantiate all replacement claims.

- **Addressing the reader:** Talk directly to you; use we for the people behind the service. Product explanations use plain present tense, and invitations sound like a person rather than a campaign slogan.
- **Rhythm:** Headlines tend to be two short clauses split over two lines. Support is usually one or two compact sentences. Longer editorial passages alternate clear factual sentences with a blunt rhetorical question; jokes remain brief.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two short statements pairing a practical benefit with relief from friction. | 5–9 words | “One global plan. No hassle.”<br>“Make content. Get paid.”<br>“A world with less noise.” |
| Support | Explain the concrete offer, then remove a familiar worry. | 10–18 words | “Enjoy unlimited global service for $69/mo. No roaming fees, or headaches.”<br>“Assistant screens spam and saves time. Finally, some peace.” |
| Section headline | A conversational question followed by a short answer, or repeated sentence structure. | 5–10 words | “The best feature? The humans.”<br>“Works in the US. Works everywhere.” |
| Primary action | Small direct verb phrase; occasional more colloquial enthusiasm in a program close. | 1–3 words | “Sign up”<br>“Apply”<br>“Hell yeah!” |
| Process | Describe one simple action at each stage. | 2–5 words | “Get setup and post”<br>“Get paid” |
| Personality aside | A tiny wink after a concrete assertion. | 3–7 words | “Yes, we timed it.”<br>“We’re backed by... Someone?” |

**Words and phrasing to use:** works; no hassle; get started; you; we; humans; peace; simple; anywhere; plain questions; short playful asides

**Avoid:** revolutionary ecosystem; enterprise-grade synergy; unlock your potential; disruptive platform; excessive AI jargon; formal application language

**Rules:**

- Lead with an everyday outcome before naming its technical mechanism.
- Use numbers to resolve practical uncertainty, not as decorative superlatives.
- Put conditions or expectations close to the claim they qualify.
- Use a joke as punctuation after useful information; do not make every heading a pun.
- Keep future capabilities explicitly future-tense and visually secondary.

## Do's and Don'ts

### Do

- Keep opening promises at 88px/1 and weight 400 with -0.025em tracking.
- Constrain section heading groups to 672px and separate support by 24px.
- Use 24px gutters for three-column proof grids and 20px for the paired capability stage.
- Preserve the small 46px action against the much larger product scene.
- Let white UI fragments sit on pale blue washes with flat, soft edges.
- Carry the light page sheet into a 48px rounded bottom edge above the dark footer.
- Make the closing name nearly fill the inner width at 0.8 line height.
- Keep the onboarding gradient cool at the top and peach at the bottom.

### Don't

- Do not use bold serif headlines: 400 is the default, even at 88px.
- Do not turn pastel iridescence into rainbow headline text or broad saturated fills.
- Do not apply the 52px capability radius to FAQ rows; those use 14px.
- Do not add heavy drop shadows to all pale cards; the main cards rely on tonal layering.
- Do not place every product demonstration in a black browser frame; screens are predominantly light and objects have slim edges.
- Do not shrink the footer name to a conventional small logo beneath a dense sitemap.
- Do not spread a paragraph across the full 1280px container; long-form narrative stays near 632px.
- Do not make the highest earnings card dark; its distinction is a fine pastel edge.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare scale, background-color, border-color, box-shadow and color transitions of 0.15s with cubic-bezier(.22, 1, .36, 1), and active scale 0.97.
- Announcement edges declare --rainbowz-angle transitions of 1.6s with cubic-bezier(.22, 1, .36, 1).
- Footer link colors declare .15s transitions with cubic-bezier(.4, 0, .2, 1).
- The small conversion badge declares cta-badge-shine 5.5s ease-in-out .3s infinite; star-bob uses variable duration and delay.

**Transfer:**

- Keep action feedback compact; a small press-scale belongs to the pebble-shaped buttons.
- Use motion to reinforce floating objects and glints, without making supporting copy difficult to read.
- Use a light-over-dark footer reveal so the oversized word feels uncovered by the page sheet.

**Unknown:**

- Scroll-reveal sequencing, exact product float trajectories and star-bob variable timings are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px, alongside several finer thresholds.
- Navigation categories are hidden below the medium layout; the large capability pair declares a single-column base and two columns at the small breakpoint.
- The conversion title and price use the clamp formulas specified in their typography recipes.

**Transfer:**

- On narrow screens, retain the centered serif promise and small action before the product object; reduce the stage scale rather than switching to a split layout.
- Stack capability and benefit cards, preserving the object clipping and pale backing.
- Stack the two conversion messages with the product image as the shared transition; keep the light sheet's rounded lower edge and scale footer lettering to its container.
- Use fewer visible items in photo fans rather than allowing tiny unreadable media.

**Unknown:**

- Exact mobile compositions, device artwork substitutions and menu behavior are not established; stacking guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
