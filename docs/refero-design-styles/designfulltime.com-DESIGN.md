# Design Full-time — after-hours workshop energy

## Overview

A dark, hands-on marketing style with the confidence of an experienced practitioner talking directly to a peer. Bold grotesk headlines, charcoal panels and bright gradient accents sit beside real working footage, annotated interfaces and informal photographic proof. It suits expert-led products and practical tools, balancing dense, useful information with cinematic opening scenes rather than glossy abstraction.

### Essentials

- The opening feels like stepping into someone's working room: a full-width photographic stage, dark left and bottom fades, 208px top padding and a left-aligned 60px/1 bold promise over the scene.
- Color behaves like a product identity, not a page fill: the default is green on #111111, concentrated in gradient labels, checks and purchase buttons; product bands use only 5% color washes. Keep most of the page charcoal.
- Actions are blunt illuminated rectangles: square corners, 20px/28px semibold white labels, a bright horizontal gradient and a hard 4px downward dark shadow; secondary actions are outlined dark rectangles.
- Proof is visibly made by humans: wide working footage and annotated interface images, 48px circular author portraits, and square documentary photographs. Every new page needs a working scene or an annotated real output rather than decorative stock art.
- Section introductions join the content grid: a 36px/40px colored statement occupies the first cell of a four-column grid, alongside 320px-wide image-and-caption items separated by 32px.
- The final invitation is understated and slightly asymmetric: a 238px-high faintly outlined charcoal panel holds a left-set 24px heading and a centered 320px dark action, followed by a minimal two-ended footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Process green | `#51d34e` | `--color-green` | accent, text, action | Default product accent, used in gradient labels and checks. |
| Gradient green | `#59d34e` | `--color-green-mid` | accent, action | Middle stop of the default green gradient. |
| Button lime | `#c1d34e` | `--color-lime` | action | Left stop of the default purchase-button gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Offer red | `#fa3a19` | `--color-red` | accent, action | Right end of bundle and warm-product gradients. |
| Offer gold | `#ffc84e` | `--color-gold` | accent, action, text | Warm bundle offers and warm-family product accents. |
| Red offer wash | `#281512` | `--color-offer-wash-end` | surface | Visible red at 10% over charcoal in the offer strip. |
| Gold offer wash | `#2e2718` | `--color-offer-wash-start` | surface | Visible gold at 12% over charcoal in the offer strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Video black | `#000000` | `--color-black` | background, text | Navigation backing after scrolling, video framing and black offer-button text. |
| Workshop charcoal | `#111111` | `--color-canvas` | background, surface | Default canvas and dark secondary actions. |
| Raised charcoal | `#1d1d1d` | `--color-raised` | surface | White at 5% over charcoal for the closing invitation. |
| Lesson band | `#252525` | `--color-band` | surface, border | Free-preview band and solid section dividers. |
| Faint edge | `#292929` | `--color-edge` | border | White at 10% over charcoal for panels and subtle outlines. |
| Action edge | `#414141` | `--color-action-edge` | border | White at 20% over charcoal for detail buttons. |
| Utility edge | `#4d4d4d` | `--color-login-edge` | border | White at 25% over charcoal for the utility action. |
| Muted gray | `#888888` | `--color-muted` | text | White at 50% over charcoal for subdued navigation and portal introduction copy. |
| Caption gray | `#8b8c8d` | `--color-caption` | text | Sample-video support and small footer metadata. |
| Supporting gray | `#a0a0a0` | `--color-body` | text | White at 60% over the charcoal canvas for ordinary support text. |
| Hero support gray | `#b8b8b8` | `--color-hero-support` | text | White at 70% over charcoal for opening support paragraphs. |
| Headline white | `#ffffff` | `--color-white` | text, accent | Headlines, action labels and monochrome partner marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| cool-themed product campaigns | Review mint | `#17ffba` | `--color-mint` | accent, action | Left stop of the cool product gradient. |
| cool-themed product campaigns | Review blue | `#2f57a7` | `--color-blue` | accent, action | Right stop of the cool product gradient. |
| cool-themed product campaigns | Review blue gray | `#76b4c8` | `--color-blue-mid` | accent, action | Middle stop of the cool product gradient. |

## Typography

- **Inter** — All marketing headings, body text, actions and captions. Straightforward contemporary grotesk with a tall x-height; bold rather than ultra-heavy headlines and neutral regular text. Font stack: "Inter", -apple-system, system-ui, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 700 | 60px | 1 | normal | Left-aligned opening promise, broken into emphatic lines. |
| heading-lg | Inter | 700 | 40px | 1.04 | normal | Benefit headline in horizontal product cards. |
| grid-introduction | Inter | 600 | 36px | 40px | normal | Colored statement occupying a first grid cell and default authority introduction. |
| heading | Inter | 700 | 30px | 1.2 | normal | Gradient heading beside a demonstration or sample video. |
| section-title | Inter | 700 | 24px | 32px | normal | Opening product label, related-offer heading and preview-band heading. |
| product-label | Inter | 700 | 24px | 1 | normal | Gradient product name above a card headline and white closing-panel heading. |
| action | Inter | 600 | 20px | 28px | normal | Purchase and detail actions; also feature-grid item headings. |
| proof-title | Inter | 500 | 20px | 28px | normal | Short titles above documentary proof images. |
| body | Inter | 400 | 18px | 28px | normal | Opening support and substantial product descriptions. |
| action-small | Inter | 700 | 18px | 28px | normal | Preview action, notification button and author name in the opening. |
| offer-line | Inter | 800 | 18px | 28px | normal | Bold savings and bundle-value lines. |
| caption | Inter | 400 | 16px | 1.5 | normal | Grid descriptions and small outlined authority links. |
| nav | Inter | 700 | 16px | 1.5 | normal | Navigation links, utility action and compact card author names. |
| offer-action | Inter | 800 | 16px | 1.5 | normal | Compact bundle action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| brand portals | portal-introduction | Inter | 400 | 20px | 28px | normal | Single centered support sentence under the large identity graphic. |

**Notes:**

- Keep normal letter spacing throughout; the character comes from bold weight, tight line height and direct wording, not aggressive negative tracking.
- Headlines use sentence case. Gradient fill identifies the offer or explanatory statement; the main benefit remains white.
- The cool campaign uses 30px/36px introductory statements; use that scoped alternative rather than shrinking every heading.

## Layout

**Density:** Comfortable inside a dense practical page: broad 80px chapter padding surrounds compact image-led grids and tightly grouped headings.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Primary horizontal padding and column gaps; small 12px action insets are local exceptions.

| Value | Use |
| --- | --- |
| 8px | Label-to-headline spacing and compact portrait/text gaps. |
| 12px | Vertical padding of major purchase and notification actions. |
| 16px | Grid title-to-image and image-to-description rhythm; compact action gaps. |
| 24px | Product-card padding and opening stack gaps. |
| 32px | Desktop page gutters, grid columns and separation between horizontal product cards. |
| 48px | Authority-grid row spacing and demonstration split gap. |
| 56px | Capability-grid row spacing. |
| 80px | Top and bottom padding of product chapters. |
| 208px | Desktop opening top padding, leaving room for navigation and the working scene. |

### Containers and grids

- **page-container**: max width 1600px · side padding 32px. Centered, almost full-width desktop canvas; at 1440px the main content spans 1376px.
- **hero-copy**: max width 896px. Opening text stack occupies the left portion of the stage; support text is constrained further to 672px.
- **capability-grid**: 4 columns · gap 32px. Four equal columns; introduction is the first cell, with 320px-wide content cells at desktop.
- **demonstration-split**: 2 columns · gap 48px. Wide working image on the left and vertically centered explanation on the right; equal halves by default, with a three-quarter media variant for annotated reviews.
- **product-card-split**: 2 columns · gap 32px. Near-equal image and text halves within a 24px inset panel.

## Corner radius

| Element | Radius |
| --- | --- |
| cards-and-actions | 0px |
| author-portrait | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| hard-downward-shadow | `0px 4px 0px rgba(0, 0, 0, 0.35)` | Offer strip and solid actions; use the equivalent drop-shadow filter on composed cards. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page backing.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Subtle grain sits over the opening, content chapters and footer; it is not a bright noise pattern.

**Transfer:** Keep the backing continuous across chapters so images and colored labels carry the change in subject.

#### Ruled chapter · level 0

**Use:** Capability, demonstration, authority and sample chapters.

**CSS:** `border-top: 1px solid #252525; padding: 80px 0px`

**Observed:** The rule is inset with the page gutters, not stretched outside the content area.

**Transfer:** Use to separate substantial changes in the argument without adding another filled card.

#### Product panel · level 1

**Use:** Default green-family related-offer panel.

**CSS:** `background: linear-gradient(95.47deg, rgba(193, 211, 78, 0.05) 0%, rgba(89, 211, 78, 0.05) 42.71%, rgba(81, 211, 78, 0.05) 100%); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 0px; padding: 24px; filter: drop-shadow(rgba(0, 0, 0, 0.35) 0px 4px 0px)`

**Observed:** Warm, cool, gold-brown and slate offers each use their own extremely low-opacity gradient; the bright counterpart appears in the label and action.

**Transfer:** Assign a coherent accent family to each offer and apply it consistently, never mixing families within a single offer.

#### Closing panel · level 1

**Use:** Final follow-up invitation.

**CSS:** `background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.1); padding: 24px; border-radius: 0px`

**Observed:** A 238px-high wide panel with a further 48px inner inset, a left-set heading and centered dark action.

**Transfer:** Offer a lower-commitment next step after the main conversion opportunity.

#### Preview band · level 1

**Only for:** brand portals with multiple sample videos

**Use:** Group a small library of preview videos.

**CSS:** `background: #252525; padding: 40px 32px`

**Observed:** Four thumbnail columns sit beneath a left-aligned title.

**Transfer:** Keep the thumbnails visually dominant rather than enclosing every item in another panel.

## Components

### Navigation

**Use:** Persistent orientation above the working scene.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 80px; z-index: 50; padding: 16px 32px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `nav` — Inter 700 · 16px/1.5

**Observed:** Left links, a small centered white identity mark and a right utility action. The opening overlays media; the scrolling state is backed by black. A future destination is muted and struck through with a small outlined status beneath it.

**Transfer:** Keep the central identity compact; do not distribute navigation evenly across the whole bar.

### Primary button

**Use:** Main purchase or commitment action.

**CSS:** `background: linear-gradient(95.47deg, #c1d34e 0%, #59d34e 42.71%, #51d34e 100%); color: #ffffff; border-radius: 0px; padding: 12px 56px; min-height: 52px; display: inline-flex; align-items: center; justify-content: center; filter: drop-shadow(rgba(0, 0, 0, 0.35) 0px 4px 0px)`

**Text style:** `action` — Inter 600 · 20px/28px

**Observed:** The colored surface is built beneath a white base using a gradient pseudo-element. Price stays on the same line as the action. Horizontal offer cards use 288px-wide, 56px-high actions with 12px 8px padding; their gradient follows that offer's accent family.

**Transfer:** Render the visible gradient directly when the original layered implementation is unnecessary.

### Preview button

**Use:** Secondary action beside the main opening action.

**CSS:** `background: #111111; color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 0px; height: 58px; padding: 0px 32px; display: inline-flex; align-items: center; justify-content: center; gap: 16px`

**Text style:** `action-small` — Inter 700 · 18px/28px

**Observed:** A small accent-colored play triangle precedes the label. The cool campaign replaces the plain triangle-only lead with a small video thumbnail and triangle.

**Transfer:** Use for a real preview or demonstration rather than a second competing purchase.

### Details button

**Use:** Secondary exploration action in horizontal product cards.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 0px; padding: 12px 0px; width: 288px; height: 58px; text-align: center`

**Text style:** `action` — Inter 600 · 20px/28px

**Observed:** Placed beside the equally wide gradient purchase action with 16px between them.

### Utility button

**Use:** Returning-user action in navigation.

**CSS:** `background: #111111; color: #ffffff; border: 1px solid rgba(255, 255, 255, 0.25); border-radius: 0px; padding: 8px 16px; height: 42px; filter: drop-shadow(rgba(0, 0, 0, 0.35) 0px 4px 0px)`

**Text style:** `nav` — Inter 700 · 16px/1.5

**Observed:** Compact right-aligned outlined rectangle; less bright than the main purchase.

**States:** Declared: hover border-color rgba(255,255,255,0.25), background-color #000000, color #ffffff; focus-visible not specified.

### Offer strip

**Use:** Compact bundle-value reminder above a set of offers.

**CSS:** `background: linear-gradient(to right, rgba(255, 200, 78, 0.12) 9.64%, rgba(250, 58, 25, 0.1) 90.67%); border: 1px solid #000000; padding: 8px 8px 8px 24px; height: 58px; display: flex; align-items: center; justify-content: space-between; box-shadow: 0px 4px 0px rgba(0, 0, 0, 0.35)`

**Text style:** `offer-line` — Inter 800 · 18px/28px

**Observed:** Savings line on the left, total value near the middle and compact warm-gradient action on the right. A fine warm edge visually echoes the gradient.

### Bundle button

**Use:** Compact action within the Offer strip.

**CSS:** `background: linear-gradient(90deg, #ffc84e 0%, #fa3a19 100%); color: #000000; padding: 8px 16px; width: 192px; height: 40px; border-radius: 0px`

**Text style:** `offer-action` — Inter 800 · 16px/1.5

**Observed:** Uses heavier black text rather than the white semibold treatment of individual purchase buttons.

### Notification button

**Use:** Lower-commitment final action.

**CSS:** `background: #111111; color: #ffffff; padding: 12px 40px; width: 320px; height: 52px; border-radius: 0px; filter: drop-shadow(rgba(0, 0, 0, 0.35) 0px 4px 0px)`

**Text style:** `action-small` — Inter 700 · 18px/28px

**Observed:** Centered within the closing panel, below the left-aligned heading; not a gradient purchase button.

### Capability item

**Use:** Image-led explanation within the four-column grid.

**CSS:** `display: flex; flex-direction: column; gap: 16px`

**Text style:** `action` — Inter 600 · 20px/28px

**Observed:** A boxed accent check and white title lead, then a wide 320px image, then a 16px/24px gray description. No separate filled card surrounds each item.

**Transfer:** Show actual outputs or working steps; retain title-image-description order.

### Author line

**Use:** Human ownership beneath supporting copy.

**CSS:** `display: flex; align-items: center; gap: 8px; margin-top: 24px`

**Text style:** `body` — Inter 400 · 18px/28px

**Observed:** 48px circular portrait with a 4px dark rim, gray introductory words and a bold white linked name. Related-offer cards use a faint white rim and smaller 16px text.

### Footer

**Use:** Minimal end of the page.

**CSS:** `background: #111111; padding: 0px 32px 16px; display: flex; justify-content: space-between; align-items: center; min-height: 56px`

**Text style:** `caption` — Inter 400 · 16px/1.5

**Observed:** Copyright at the left and a linked maker credit at the right, with grain continuing behind them. There is no sitemap or large closing logo.

## Imagery and graphics

### Working-room stage

**Use:** Signature media in the opening and in supporting demonstrations.

**Observed:** Real footage or photography of a practitioner at a multi-monitor desk fills the background, with the subject concentrated to the right. The left side is heavily darkened, and the bottom dissolves into charcoal. The scene has practical lamps, monitors, studio clutter and subdued warm or blue light, with a fine grain layer.

**Transfer:** Photograph a real workflow or artifact in use. If no person or footage is available, stage a real output on a monitor or workbench at an oblique angle with practical side light; it must still read as work happening, not a floating software mockup.

**Build:** Use a full-bleed cover image positioned toward the right. Overlay a left-to-right gradient from rgba(17,17,17,1) to rgba(17,17,17,0) around the central portion, plus a vertical gradient from transparent to #111111 near the bottom. Add a tiled monochrome SVG turbulence texture on a pointer-events:none layer at low opacity; keep the grain barely visible and the headline above all overlays.

### Annotated working outputs

**Use:** Demonstration chapters, capability thumbnails and sample-video posters.

**Observed:** Real desktop interface views and website compositions remain rectangular and legible, often with red hand-drawn circles, arrows and underlines. Some views include a small presenter camera inset. They occupy one half to three quarters of a split section and are not wrapped in ornamental device frames.

**Transfer:** Show the new product's genuine result and annotate the specific decision being explained. A minimum version is a clear real output plus two or three purposeful drawn marks.

**Build:** Place the output image on a plain rectangular layer. Add an SVG overlay with irregular 2px to 4px red strokes, unfilled ellipses around key areas and loose arrow paths; use only a few marks, preserving the output's legibility. Keep annotation color inside the media, not as a new marketing accent.

### Offer posters

**Use:** Horizontal product cards and related-offer sections.

**Observed:** Approximately 647px by 360px media mixes a talking-head photograph, large condensed poster lettering or a tangible book cover against a dark studio. A cool-family poster instead uses an annotated web page and presenter inset. New or best-selling offers have a diagonal ribbon crossing the upper-left corner.

**Transfer:** Create an editorial poster for the offer with a genuine person, artifact or result. Use large expressive lettering within the artwork without introducing that font into the marketing type scale.

**Build:** Use a 16:9 rectangle with a full-bleed documentary image. Layer an oversized short title behind or beside the subject where appropriate. For a status ribbon, clip a roughly 48px-high strip across the upper-left corner at about -35deg, fill it with the offer's warm gradient or pale neutral, and center a short dark label.

### Documentary proof wall

**Use:** Authority or trust chapters.

**Observed:** Square images show work environments, messages, publications, physical products and candid milestones. Each has a small white title above and muted explanatory text below. Images retain their varied natural colors, including one vivid pink-orange scene, rather than being uniformly tinted.

**Transfer:** Use genuine verifiable artifacts that substantiate different claims. Preserve the uneven, human documentary character instead of substituting a uniform stock-photo set.

### Identity flag

**Only for:** brand portals

**Use:** Centered brand introduction before the offer list.

**Observed:** A compact black-and-white, two-line wavy flag-like wordmark is enlarged to roughly 335px by 190px with a single centered muted sentence underneath; the navigation version is about 117px wide.

**Transfer:** Use the new brand's own bold two-line identity graphic. If it has only plain typography, create a monochrome stacked title inside a gently bowed banner rather than imitating an unrelated logo.

**Build:** Make two stacked SVG banner shapes with slightly curved top and bottom edges; place heavy uppercase lettering inside and use only white and charcoal. Keep the graphic compact, not viewport-sized.

### Icons

**Observed:** Small utilitarian checks and play triangles rather than a decorative icon family. Capability checks sit in approximately 28px square outlined boxes; opening play triangles are about 12px by 17px. White social marks accompany authority links; monochrome partner marks form a compact proof row.

**Transfer:** Use the active product accent for checks and play symbols, white for social or partner marks. Keep icons subordinate to real imagery.

## Section recipes

How recurring sections are built.

### First screen: Working-stage opening

**Observed:** A full-width photographic stage is 789px tall, with the navigation over it and a 32px inset content container. From back to front: working-room photograph concentrated on the right, dark left and bottom fades, fine grain, then the left text/action stack and a low-right partner strip. The copy starts after 208px top padding: green 24px/32px label, white 60px/1 bold benefit wrapping across roughly half the viewport into three lines, an 18px/28px support paragraph constrained to 672px, Author line, then Primary button and Preview button with 32px between them. A short warm-colored bundle line sits beneath the primary action. The partner strip is 576px wide and aligned near the action level. Within 900px the entire opening, the centered audience-proof line crossing a thin rule, and the first headings of the capability grid are visible; detailed grid media continues below.

**Transfer:** Keep this cinematic working-stage opening as the default for a new landing page. Replace the working room with a genuine workflow or lit artifact and give the left half enough darkness for a compact, outcome-led promise. Cool campaigns can use right-dominant presenter footage and mint-to-blue accents. Brand portals instead use the Identity flag plus one support sentence before offers; catalog pages begin with Offer strip and a first Product panel.

**Avoid:** Do not turn the opening into a centered text-only SaaS hero, place the main image in a small rounded card, or use a bright photograph behind the left-hand copy.

**Text style:** `display` — Inter 700 · 60px/1

### Grid-cell introduction

**Observed:** Ruled chapter contains a four-column capability grid after 80px top padding. The first cell is a green 36px/40px statement broken into short lines; the remaining cells are Capability items. Columns have 32px gaps and rows 56px gaps. An audience count is centered over the top rule on a charcoal backing, with the number in bold rather than giant numerals.

**Transfer:** Use the first cell to summarize the scope or promise of the set, and the other cells to prove it through outputs. A compact audience or usage count can interrupt the rule without becoming a separate stats section.

**Text style:** `grid-introduction` — Inter 600 · 36px/40px

### Demonstration with practical list

**Observed:** Ruled chapter uses Demonstration split: a wide rectangular working output at left, a 30px/36px gradient heading and 18px/28px explanation at right, then a short list with colored checks. The cool variant expands the annotated image to three quarters and narrows the explanation.

**Transfer:** Pair the product result with concrete reasons it works. Use the wider-media variant when annotations must remain readable.

**Text style:** `heading` — Inter 700 · 30px/1.2

### Authority in the first cell

**Observed:** A four-column documentary proof grid puts a colored introductory statement and two full-width outlined links in the first cell. Seven titled square artifacts fill the remaining cells across two rows; gray descriptions follow each image. Row gaps are 48px. The cool campaign adds a compact row of small partner marks beneath.

**Transfer:** Make trust an accumulation of real artifacts rather than a wall of anonymous testimonials. The first cell can introduce the maker, methodology or provenance of the product.

**Text style:** `grid-introduction` — Inter 600 · 36px/40px

### Sample before commitment

**Observed:** Within Ruled chapter, a large video poster occupies the left and a compact 30px/36px gradient invitation, gray 16px/24px explanation and Primary button sit at right. A black outlined clip-label overlay with a small accent play symbol anchors the bottom-left of the video.

**Transfer:** Offer a real useful preview with a descriptive label, then repeat the commitment action beside it.

**Text style:** `heading` — Inter 700 · 30px/1.2

### Horizontal offer showcase

**Observed:** Product panel pairs a 16:9 Offer poster with a Product label, 40px/1.04 white benefit heading, 18px/28px muted paragraph, compact Author line and side-by-side purchase/details actions. Cards are separated by 32px; labels, purchase gradients and faint backgrounds share one product accent family.

**Transfer:** Use for related products or editions, varying the accent family by offer while keeping the construction identical.

**Text style:** `heading-lg` — Inter 700 · 40px/1.04

### Low-key final invitation

**Observed:** Closing panel follows the last offer or sample group. Its 24px white heading is set toward the left with 48px inner padding; Notification button is centered on the next line. Footer follows with only copyright and maker credit. This ending is shared by catalog, portal and individual-product pages.

**Transfer:** Finish with a genuine follow-up action such as updates or availability, preserving the subdued panel rather than introducing an unrelated monumental closing statement.

**Text style:** `product-label` — Inter 700 · 24px/1

### Preview library band

**Only for:** brand portals with several samples

**Observed:** Preview band contains a 24px/32px left heading and four columns of 304px by 166px video posters, a black duration badge in each lower-right corner, bold 24px/32px titles and muted source labels.

**Transfer:** Present immediately usable examples, not abstract feature icons.

**Text style:** `section-title` — Inter 700 · 24px/32px

## Page flow

**Storyline:** Outcome promise → practical scope → visible work → human authority → useful sample → related choices → low-commitment follow-up.

### Expert-led product conversion

1. **Promise** — Working-stage opening with outcome, maker, purchase, free preview and partner proof.
2. **Capability chapters** — First-cell introduction and image-led capability grid.
3. **Product demonstration** — Real working output with a practical checklist.
4. **Authority** — Documentary proof wall, introduced by a colored statement and maker links.
5. **Try before buying** — Large free-sample video with adjacent purchase action.
6. **Related choices** — Offer strip and horizontal related-offer panels.
7. **Closing call** — Subdued notification panel and two-ended footer.

**Transfer:** Use when a real workflow and credible maker can carry the argument; adapt the relative depth of capabilities and trust to the product.

### Media-led product conversion with larger visual demonstrations

1. **Promise** — Presenter footage under mint-blue headline accents and purchase actions.
2. **Capability chapters** — Compact first-cell introduction beside annotated lesson thumbnails.
3. **Product demonstration** — Three-quarter-width annotated output and narrow supporting list.
4. **Authority** — Square proof artifacts with a compact partner-mark row.
5. **Try before buying** — Large annotated sample beside explanation and purchase.
6. **Related choices** — Offer strip and alternative offer panels.
7. **Closing call** — Notification panel followed by minimal footer.

**Transfer:** Use this cool variant when reviewing or showing outputs is more persuasive than describing a process.

### Brand portal introducing a family of practical offers

1. **Identity and promise** — Centered Identity flag and one muted audience-benefit sentence.
2. **Value** — Warm compact bundle strip.
3. **Product choices** — Repeated image-left product panels with separate accent families.
4. **Useful sample** — Four-column preview library on a lighter charcoal band.
5. **Closing call** — Subdued notification panel and minimal footer.

**Transfer:** Keep the identity introduction short so visitors reach concrete offers in the first screen.

### Catalog for visitors ready to compare offers

1. **Value** — Bundle offer strip directly under navigation.
2. **Product choices** — Consistent horizontal offer cards with benefit copy, authorship, price and details.
3. **Closing call** — Notification panel followed by copyright and creator credit.

**Transfer:** Remove the brand introduction and sample library when the visitor's primary task is choosing an offer.

## Writing

Confident practitioner-to-practitioner advice, warm and colloquial rather than institutional. Benefits are blunt and career-oriented, with personal experience offered as the reason to believe.

**Do not copy:** Do not reuse the brand name, wordmark, instructor identity, course titles, client logos, earnings claims, student counts, prices, testimonials or distinctive source artwork as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use I for the expert's experience and we when inviting a shared action.
- **Rhythm:** Short benefit headlines, followed by two or three conversational explanatory sentences. Labels are direct names; actions are literal verbs, often with the price attached. Exclamation marks appear in promotional and friendly follow-up lines, not every headline.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Become or achieve a desirable outcome, expressed in everyday terms. | 5–12 words | “Become a faster, more efficient and hirable designer.” |
| Card benefit | A direct instruction or promise focused on getting better results. | 5–11 words | “Start getting the work you deserve.” |
| Support | Name the practical change, then the real-world priorities it serves. | 20–55 words | “This design process will change the way you approach your next project. It’s geared for speed, communication, and growing relationships.” |
| Capability title | A plain action and practical object, not a clever metaphor. | 2–5 words | “Communicate Effectively”<br>“Create Better Presentations” |
| Primary action | Verb plus offer, with a hyphen and price when useful. | 3–7 words | “Take the Course - $149” |
| Sample invitation | Make trying the product feel quick and low-risk. | 4–8 words | “Try a Free Lesson Real Quick” |
| Final follow-up | Plain future-facing status plus an explicit notification action. | 2–4 words each | “More Coming Soon.”<br>“Get Notified!” |

**Words and phrasing to use:** real; better; faster; stand out; learn; try; work; right now; simple and easy

**Avoid:** synergy; enterprise transformation; revolutionary ecosystem; unlock limitless possibilities; abstract luxury language

**Rules:**

- Lead with what the reader will be able to do, not the format or technology.
- Use concrete experience and inspectable work to support strong claims.
- Keep capability titles practical enough to read as a useful checklist.
- Make secondary actions describe what will actually happen, especially video previews.
- Let the maker sound human; do not polish every sentence into corporate symmetry.

## Do's and Don'ts

### Do

- Keep opening headlines at 60px/1 and 700 weight with normal tracking.
- Keep the default stage dark and reserve full-strength green for labels, checks and purchase actions.
- Align ordinary content to 32px desktop gutters within a 1600px maximum container.
- Use 80px chapter padding around unboxed image-led content.
- Maintain 32px columns and a first-cell statement in four-column grids.
- Keep purchase and detail actions square, with 20px/28px semibold labels.
- Use 16px/24px descriptions beneath square proof artifacts.
- End with the faint 238px invitation panel and restrained two-ended footer.

### Don't

- Do not apply pill corners to actions or product panels; circles belong to portraits.
- Do not replace normal tracking with tightly compressed headline tracking.
- Do not set body support in pure white everywhere; use the 60% or 70% white hierarchy.
- Do not turn the 5% product washes into saturated full-page green or blue backgrounds.
- Do not give every capability item its own raised, rounded card.
- Do not change the black 16px/24px extra-bold bundle action into the larger white purchase-label style.
- Do not substitute glossy 3D device mockups for the raw rectangular working outputs.
- Do not add a multi-column sitemap or enormous logo after the small final invitation.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed at desktop and becomes a black-backed bar while reading lower content.
- The utility action declares a black hover background with a 25% white border and white text. No matched action transitions or running animations establish timing.

**Transfer:**

- Keep the working scene readable as a still frame even when using video; text and purchase actions should remain independent of playback.
- Use a stable navigation identity during scrolling rather than a showy animated header.

**Unknown:**

- Video playback behavior, grain movement and transition durations are unspecified.

### Responsive

**Observed:**

- Width breakpoints include 640px, 768px, 1024px, 1200px, 1280px, 1536px and 1640px; product layouts also declare 1440px and 1840px.
- Container classes use 16px side padding before 640px and 32px afterwards. Product content declares stacked base layouts, two-column intermediate grids and four-column desktop grids.

**Transfer:**

- On narrow screens, retain a recognizable working-room image above or behind the stacked promise, with a dark backing for text rather than shrinking the desktop composition.
- Stack the purchase and preview actions, keep the author portrait visible, and allow product panels to become image-first vertical blocks.
- Move four-column capability and proof grids through two columns to a single column while keeping the introduction as a real first item.

**Unknown:**

- Exact narrow-screen appearance, headline substitutions and navigation interaction are not established; these stacking rules are implementation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
