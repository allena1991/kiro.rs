# Increase — folded spectrum infrastructure

## Overview

An engineering-led, predominantly white style with slate grotesk typography and sudden electric lime, mint and cyan. Oversized folded ribbons bring energy to otherwise restrained grids, while layered interfaces and schematic diagrams make complex products tangible. It suits technical platforms with substantial capabilities to explain: spacious at the section level, compact and factual inside the details.

### Essentials

- Headlines behave like a two-tone sentence, not a poster: the default opening uses 40px/1.2, weight 600, -0.02em tracking, followed inline by a weight-400 slate continuation; section leads repeat this at 32px/1.2 and -0.01em.
- The first screen combines upper-left editorial copy with an enormous ascending folded spectrum: lime through mint to cyan planes fill the lower and right portions, clipped by the stage, while text stays on white. Recreate the folded geometry even when there is no product artwork.
- A faint architectural frame holds the page together: a 1160px centered rail with 24px inner side padding and 1px #edf1f5 vertical edges, crossed by restrained horizontal rules.
- Conversion controls are small rounded rectangles, never pills: the default mint action is 46px tall with 12px 16px padding, 8px corners and 16px/20px medium text; pair it with an outlined white action.
- Color is concentrated rather than spread evenly: white and near-white carry most content, a sustained #151e29 technical chapter reverses the palette, and saturated mint/lime appear in actions, icon chips and the signature folded artwork.
- Proof feels like annotated machinery: include a softly glowing testimonial panel with 32px padding, 12px corners, 20px/30px quotation text, a 16px/24px mono attribution and a small right-aligned mono outcome note. Use a verified editorial observation in the same construction when no customer quotation exists.
- Product explanation is staged in miniature: clipped 16px-corner pale-gray mosaics combine white interface fragments with dark code panels; technical diagrams use fine connectors and a 16px-pitch dot field rather than decorative stock illustration.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ribbon lemon | `#deff34` | `--color-ribbon-lime` | accent | First folded plane's left edge. |
| Ribbon leaf | `#8cf97c` | `--color-ribbon-leaf` | accent | First folded plane's right edge. |
| Ribbon green fold | `#65f75f` | `--color-ribbon-green` | accent | Green connector's left edge. |
| Ribbon jade fold | `#12f0aa` | `--color-ribbon-jade` | accent | Green connector's right edge. |
| Ribbon mint plane | `#45f4bc` | `--color-ribbon-mint` | accent | Middle broad plane's left edge. |
| Ribbon teal plane | `#33dfdf` | `--color-ribbon-teal` | accent | Middle broad plane's right edge. |
| Ribbon aqua fold | `#01d3d8` | `--color-ribbon-aqua` | accent | Middle connector's left edge. |
| Ribbon cyan fold | `#02b7f1` | `--color-ribbon-cyan` | accent | Middle connector's right edge. |
| Ribbon sky plane | `#34c8f4` | `--color-ribbon-sky` | accent | Blue broad plane's left edge. |
| Electric sky | `#34bcff` | `--color-sky` | accent | Blue broad plane's right edge and blue diagram marker. |
| Ribbon blue fold | `#02a7ff` | `--color-ribbon-blue` | accent | Final blue connector. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric mint | `#31f2bf` | `--color-mint` | action, link, accent | Default primary action, dark-band links and selected technical markers. |
| Signal lime | `#e4ff33` | `--color-lime` | surface, accent | Announcement badge, compact icon backgrounds and status dots. |
| Lemon proof wash | `#fcffeb` | `--color-proof` | surface | Warm testimonial backing. |
| Lime glow appearance | `#fafcd3` | `--color-lime-glow` | accent | Visible yellow-green wash made with #e4f221 at 20% over white, heavily blurred. |
| Blue glow appearance | `#cce2ff` | `--color-blue-glow` | accent | Visible blue wash made with #0070ff at 20% over white, heavily blurred. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page and interface surfaces; reversed headlines on dark bands. |
| Near-white | `#fcfcfc` | `--color-offwhite` | background | Subtle gradient starts and utility footer canvas. |
| Pale panel | `#f5f6f7` | `--color-panel` | surface, background | Feature mosaics and restrained utility bands. |
| Architectural hairline | `#edf1f5` | `--color-rail` | border | Outer rails, feature outlines and interface edges. |
| Table rule | `#edf0f2` | `--color-rule` | border, surface | Table dividers and story-media backing. |
| Panel edge | `#e1e5e9` | `--color-edge` | border | Testimonial edge and catalog grid seams. |
| Action edge | `#d5dee5` | `--color-button-edge` | border | Outlined action border. |
| Reversed support | `#c0c9d1` | `--color-dark-copy` | text | Support sentences in dark chapters and announcements. |
| Dark footer links | `#a6b0ba` | `--color-footer-copy` | text | Links on the default dark footer. |
| Dark secondary | `#8995a1` | `--color-fine-copy` | text | Dark-footer fine print and inactive demo labels. |
| Utility muted | `#687887` | `--color-muted` | text | Navigation, catalog descriptions and light-footer secondary text. |
| Editorial slate | `#657482` | `--color-subtle` | text, border | Inline headline continuations, statistical captions and diagram outlines. |
| Quote slate | `#334352` | `--color-quote-ink` | text | Quotation and mono attribution text. |
| Body slate | `#314352` | `--color-body` | text, border | Paragraph text and dark-footer dividing rule. |
| Utility ink | `#1a2b3b` | `--color-utility-ink` | text, action | Compact navigation action fill; bold headings on product and utility variants. |
| Editorial ink | `#1d2a36` | `--color-ink` | text | Default marketing headlines and action labels. |
| Deep slate canvas | `#151e29` | `--color-dark` | background, surface | Technical chapter, announcement panels and default marketing footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interactive product demonstrations | Developer stage | `#0d1726` | `--color-demo-dark` | surface | Inset developer demonstration panel. |

## Typography

- **TT Interphases Pro-c98a05336328a01f** — All marketing headings, paragraphs and controls. Open, contemporary grotesk with compact proportions; medium and semibold feel functional rather than ornamental. If unavailable, use **Inter**. Use 400–700; preserve negative tracking and check line wraps. Font stack: "TT Interphases Pro-c98a05336328a01f", "Inter", Arial, sans-serif.
- **Input Mono-4c4a0ba0f7fa02b9** — Eyebrows, attributions, dates, outcome captions and code. Technical monospace, used in sentence case rather than widely tracked capitals. OpenType features: "ss01", "ss02", "ss12". If unavailable, use **IBM Plex Mono**. Use 400; keep labels compact. Font stack: "Input Mono-4c4a0ba0f7fa02b9", "IBM Plex Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening | TT Interphases Pro-c98a05336328a01f | 600 | 40px | 1.2 | -0.02em | Default first-screen promise. |
| opening-continuation | TT Interphases Pro-c98a05336328a01f | 400 | 40px | 1.2 | -0.02em | Muted continuation within the same opening sentence. |
| stat | TT Interphases Pro-c98a05336328a01f | 400 | 40px | 1.2 | -0.02em, features "lnum", "ss05", "ss16", "tnum" | Centered quantitative proof; no extra-heavy numeral treatment. |
| heading | TT Interphases Pro-c98a05336328a01f | 600 | 32px | 1.2 | -0.01em | Core section lead. |
| heading-continuation | TT Interphases Pro-c98a05336328a01f | 400 | 32px | 1.2 | -0.01em | Muted inline section explanation. |
| card-heading | TT Interphases Pro-c98a05336328a01f | 500 | 24px | 1.2 | -0.004em | Mosaic headings and audience subheadings. |
| dark-heading | TT Interphases Pro-c98a05336328a01f | 600 | 24px | 1.2 | normal | Technical chapter row lead. |
| dark-continuation | TT Interphases Pro-c98a05336328a01f | 400 | 24px | 1.2 | normal | Inline reversed support after the technical row lead. |
| announcement-heading | TT Interphases Pro-c98a05336328a01f | 600 | 24px | 1.2 | -0.004em | Headline inside a dark announcement panel. |
| quote | TT Interphases Pro-c98a05336328a01f | 500 | 20px | 1.5 | normal | Large proof-panel quotation. |
| lead | TT Interphases Pro-c98a05336328a01f | 400 | 20px | 1.4 | -0.01em | Announcement paragraph and standalone product-hero support. |
| body | TT Interphases Pro-c98a05336328a01f | 400 | 16px | 1.5 | normal | Explanatory paragraphs. |
| action | TT Interphases Pro-c98a05336328a01f | 500 | 16px | 20px | normal | Default main and outlined buttons. |
| emphasis | TT Interphases Pro-c98a05336328a01f | 600 | 16px | 24px | normal | Announcement badge and inline benefit labels. |
| attribution | Input Mono-4c4a0ba0f7fa02b9 | 400 | 16px | 1.5 | normal | Name and role beneath a quotation. |
| update-title | TT Interphases Pro-c98a05336328a01f | 500 | 16px | 1.5 | normal | Compact update headline. |
| small | TT Interphases Pro-c98a05336328a01f | 400 | 14px | 20px | normal | Footer links, catalog support and compact descriptive text. |
| label | TT Interphases Pro-c98a05336328a01f | 500 | 14px | 20px | normal | Navigation, compact actions and catalog titles. |
| eyebrow | Input Mono-4c4a0ba0f7fa02b9 | 400 | 14px | 20px | normal | Section markers and compact outcome notes. |
| date | Input Mono-4c4a0ba0f7fa02b9 | 400 | 12px | 16px | normal | Update dates and small technical annotations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product, solution and story-index openings | display-bold | TT Interphases Pro-c98a05336328a01f | 700 | 56px | 1.05 | -0.02em | Standalone, not inline, product or solution title. |
| product, solution and utility pages | heading-bold | TT Interphases Pro-c98a05336328a01f | 700 | 40px | 1.2 | -0.02em | Catalog closing headline, comparison lead and pricing title. |
| product and solution pages | feature-bold | TT Interphases Pro-c98a05336328a01f | 700 | 32px | 1.2 | -0.01em | Split feature-chapter headline. |
| story indexes | story-title | TT Interphases Pro-c98a05336328a01f | 500 | 20px | 1.4 | -0.01em | Sentence-length linked case-study title. |
| pricing tables | price | TT Interphases Pro-c98a05336328a01f | 500 | 20px | 1.2 | -0.01em | Right-aligned price and utility category title. |

**Notes:**

- Default marketing hierarchy uses weight 600, not the weight-700 standalone product variant. A muted continuation remains the same size as its lead and flows within the same text block.
- Negative tracking is strongest at 40px and 56px; 32px uses -0.01em and 24px card headings use -0.004em. Body, controls and mono captions use normal tracking.
- Keep mono as an annotation layer, not a replacement for paragraph text. The main sans has no single global feature-setting requirement.

## Layout

**Density:** Airy section framing with compact internal controls and technical details.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-headline and number-to-caption gaps. |
| 12px | Story image-to-title gap and compact action separation. |
| 16px | Default paired-action gap. |
| 24px | Container inner sides, feature padding and mosaic gaps. |
| 32px | Proof panel padding, quote attribution separation and update-grid gap. |
| 40px | Pricing category separation and product-hero action offset. |
| 48px | Technical row padding and major heading-to-content separation. |
| 64px | Section lead-to-mosaic gap and story-grid horizontal gap. |
| 80px | Stat-band vertical padding and story-grid row gap. |
| 96px | Major section and footer vertical padding. |
| 112px | Opening padding of the sustained dark technical chapter. |

### Containers and grids

- **framed-container**: max width 1160px · side padding 24px. Centered desktop rail with faint vertical edges; yields about 1110px of usable inner width when borders are present.
- **editorial-measure**: max width 768px. Inline lead and continuation occupy roughly two thirds of the content rail.
- **feature-copy**: max width 460px. Paragraph-and-headline side of product and solution split sections.
- **mosaic**: 12 columns · gap 24px. One full-width tile followed by asymmetric pairs; common pair spans are seven/five, then five/seven.
- **technical-split**: 2 columns · gap 48px. Equal text and diagram columns inside the dark rail.
- **stats**: 3 columns · gap 24px. Equal centered metrics in a full-width horizontal band.
- **updates**: 4 columns · gap 32px. Text-led update entries on a shared horizontal timeline.
- **footer**: 4 columns · gap 0px. Equal navigation columns beneath a small wordmark; disclaimer runs across the full rail.
- **catalog** (only for product and solution closing sections): 4 columns · gap 1px. Two rows of white product cells sharing a single rounded shell.
- **story-index** (only for story indexes): 3 columns · gap 64px. 328px media cards at desktop, with 80px row gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 8px |
|  | panels | 12px |
|  | feature-mosaics | 16px |
|  | status-dot | 50% |
| pricing pages | utility-band | 4px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action | `0px 1px 2px 0px rgba(21,30,41,0.05)` | Subtle edge lift on default actions. |
| product and solution demonstrations | catalog-stage | `0px 6px 8px 0px rgba(12,25,39,0.05), 0px 16px 20px 0px rgba(12,25,39,0.06), 0px 50px 60px 0px rgba(12,25,39,0.1)` | Broad grounded shadow below a substantial catalog shell or developer stage. |
| story indexes | story-media | `0px 2px 4px 0px rgba(12,25,39,0.06), 0px 7px 12px 0px rgba(12,25,39,0.09)` | Modest lift of story thumbnails. |

### Surfaces

#### Framed canvas · level 0

**Use:** Default page foundation.

**CSS:** `background: #ffffff; color: #1d2a36; border-left: 1px solid #edf1f5; border-right: 1px solid #edf1f5`

**Observed:** The narrow centered frame continues through many sections while bands extend to the browser edges.

**Transfer:** Keep the rails aligned across varied content rather than turning each section into an isolated floating card.

#### Mosaic well · level 1

**Use:** Backdrop for layered product fragments.

**CSS:** `background: #f5f6f7; border: 1px solid #edf1f5; border-radius: 16px; overflow: hidden`

**Observed:** Large pale wells contain smaller white and dark surfaces; media is clipped at the lower or right edge.

**Transfer:** Show a few legible fragments of the new product rather than an entire dashboard shrunk to fit.

#### Dark technical band · level 0

**Use:** A sustained explanatory chapter and default footer.

**CSS:** `background: #151e29; color: #ffffff`

**Observed:** Full browser width with a continued inner frame; internal edges become low-alpha white and gray.

**Transfer:** Group closely related technical explanations into a coherent dark chapter rather than alternating every section.

#### Proof panel · level 1

**Use:** Quotation and annotated outcome.

**CSS:** `background: #fcffeb; border: 1px solid #e1e5e9; border-radius: 12px; padding: 32px; overflow: hidden; position: relative`

**Observed:** A warm proof wash with a brighter glow escaping behind the lower-right text. A second variant is white with a blue glow and pale rail border.

**Transfer:** Use one softly colored proof interruption among otherwise neutral content.

#### Proof glow · level 1

**Use:** Soft lower-right illumination inside Proof panel.

**CSS:** `background: rgba(228,242,33,0.2); width: 420px; height: 420px; border-radius: 50%; filter: blur(100px); position: absolute; right: -140px; bottom: -220px; pointer-events: none`

**Transfer:** For the cool variant replace the fill with rgba(0,112,255,0.2). Match the soft glow; exact gradient stops are not essential.

#### Dot-field diagram stage · level 1

**Use:** Backing for technical schematics.

**CSS:** `background-image: radial-gradient(circle, rgba(255,255,255,0.14) 1px, rgba(0,0,0,0) 1.5px); background-size: 16px 16px`

**Observed:** Subtle dots occupy the diagram half of a dark row, fading visually behind the nodes.

**Transfer:** Keep the field lower-contrast than connectors and labels.

#### Catalog shell · level 1

**Only for:** product and solution closing sections

**Use:** Unified grid surface above a cropped folded ribbon.

**CSS:** `background: #e1e5e9; border: 1px solid #e1e5e9; border-radius: 12px; overflow: hidden; display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 1px; box-shadow: 0px 6px 8px 0px rgba(12,25,39,0.05), 0px 16px 20px 0px rgba(12,25,39,0.06), 0px 50px 60px 0px rgba(12,25,39,0.1)`

**Observed:** White cells sit inside the seam-colored shell; the surrounding band fades from near-white to pale gray.

**Transfer:** Treat the whole grid as one raised object, not a set of separately rounded tiles.

#### Developer inset · level 1

**Only for:** interactive product demonstrations

**Use:** Wide developer-workbench scene.

**CSS:** `background: #0d1726; border-radius: 12px; padding: 96px 0px; overflow: hidden`

**Observed:** A 1280px inset stage with a faint square grid, selection list on one side and code/result panel on the other.

**Transfer:** Use for an actual interactive workflow, not as the page's overall dark theme.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; top: 0px; height: 65px; width: 100%; z-index: 50; background: rgba(255,255,255,0.95); backdrop-filter: blur(12px); border-bottom: 1px solid rgba(0,0,0,0.05)`

**Text style:** `label` — TT Interphases Pro-c98a05336328a01f 500 · 14px/20px

**Observed:** Small wordmark left, horizontal topic navigation in the middle, sign-in and compact dark signup right. The inner rail is 1160px. Menu triggers have 4px 8px padding and 8px corners.

**States:** Declared: hover menu triggers use #edf0f2 background and #1a2b3b text; focus-visible not specified.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `background: #31f2bf; color: #1d2a36; border-radius: 8px; padding: 12px 16px; height: 46px; display: inline-flex; align-items: center; gap: 8px; box-shadow: 0px 1px 2px 0px rgba(21,30,41,0.05)`

**Text style:** `action` — TT Interphases Pro-c98a05336328a01f 500 · 16px/20px

**Observed:** Content-width button paired with Secondary button. A documentation variant has the same construction at 44px height.

**States:** Declared: hover background #15cb9a; focus-visible not specified.

### Secondary button

**Use:** Alternative action beside the primary or below updates.

**CSS:** `background: #ffffff; color: #1d2a36; border: 1px solid #d5dee5; border-radius: 8px; padding: 12px 16px; height: 46px; display: inline-flex; align-items: center; gap: 8px; box-shadow: 0px 1px 2px 0px rgba(21,30,41,0.05)`

**Text style:** `action` — TT Interphases Pro-c98a05336328a01f 500 · 16px/20px

**Observed:** Content-width outline rather than a ghost link.

**States:** Declared: hover background #f5f8fa; focus-visible not specified.

### Compact dark button

**Use:** Small signup action in navigation; product and solution action variant.

**CSS:** `background: #1a2b3b; color: #ffffff; border-radius: 8px; padding: 5px 10px; height: 36px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `label` — TT Interphases Pro-c98a05336328a01f 500 · 14px/20px

**Observed:** Header version is compact and text-only. Product and solution versions are 42px tall with 10px 15px padding, a transparent border and a right chevron; pair those with a white compact action.

**States:** Declared: hover background #132030; focus-visible not specified.

### Announcement badge

**Use:** Short news hook above the opening promise.

**CSS:** `background: #e4ff33; color: #1d2a36; border-radius: 8px; padding: 6px 12px; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `emphasis` — TT Interphases Pro-c98a05336328a01f 600 · 16px/24px

**Observed:** Single-line sentence-case text ends with a northeast arrow, followed by 24px before the promise.

**States:** Declared: hover background #daf200; focus-visible not specified.

### Feature mosaic tile

**Use:** Compact visual explanation of a capability.

**CSS:** `background: #f5f6f7; border-radius: 16px; position: relative; overflow: hidden`

**Text style:** `card-heading` — TT Interphases Pro-c98a05336328a01f 500 · 24px/1.2 · tracking -0.004em

**Observed:** Title sits near the upper-left with 24px inset. A full-width tile combines a short two-column link list and overlapping code/result panels; asymmetric paired tiles below combine material objects, forms and ledgers. Thin outer edges remain nearly invisible.

**Transfer:** Give each tile one capability and one coherent scene, not a wall of unrelated widgets.

### Annotated testimonial

**Use:** A concrete statement of product value with an outcome note.

**CSS:** `background: #fcffeb; border: 1px solid #e1e5e9; border-radius: 12px; padding: 32px; position: relative; overflow: hidden`

**Text style:** `quote` — TT Interphases Pro-c98a05336328a01f 500 · 20px/1.5

**Observed:** Small identity mark above a left-aligned quote; mono attribution below. A separate compact mono outcome occupies the lower right, with the Proof glow behind it. Cool variant uses white and blue illumination.

**Transfer:** Keep the outcome separate from the quote and leave room around both.

### Technical text link

**Use:** Further explanation within a technical row.

**CSS:** `color: #31f2bf; display: inline-flex; align-items: center; gap: 6px`

**Text style:** `label` — TT Interphases Pro-c98a05336328a01f 500 · 14px/20px

**Observed:** A northeast arrow follows the label; no enclosing fill, border or oversized arrow box.

### Footer navigation

**Use:** Default marketing ending.

**CSS:** `background: #151e29; color: #a6b0ba; padding: 96px 0px`

**Text style:** `small` — TT Interphases Pro-c98a05336328a01f 400 · 14px/20px

**Observed:** Small white wordmark, then four equal navigation columns with brighter medium-weight group labels. Compact links use about 8px vertical gaps. A 2px #314352 rule separates navigation from full-width muted fine print with 24px top padding. Product, solution and story-index footers use white with dark links and a pale rule; pricing uses near-white and a longer disclosure area.

**Transfer:** Preserve the restrained directory ending; a huge closing slogan is not part of this footer.

### Catalog cell

**Only for:** product and solution closing sections

**Use:** A navigable capability inside Catalog shell.

**CSS:** `background: #ffffff; display: flex; flex-direction: column; padding: 24px 20px 30px 20px`

**Text style:** `label` — TT Interphases Pro-c98a05336328a01f 500 · 14px/20px

**Observed:** Lime 24px icon chip, short title, muted small-text description, then a bottom-aligned text link with chevron. Typical desktop cell is 277px by 250px.

**Transfer:** Keep descriptions concise enough that the bottom links align across a row.

### Pricing category

**Only for:** pricing pages

**Use:** Plain, comprehensive cost breakdown.

**CSS:** `background: #f5f6f7; border-radius: 4px; padding: 8px; display: flex; align-items: center; gap: 12px`

**Text style:** `price` — TT Interphases Pro-c98a05336328a01f 500 · 20px/1.2 · tracking -0.01em

**Observed:** Category strip starts with a 28px lime icon square. Rows below are unboxed flex lines separated by #edf0f2 rules with 10px vertical padding: description left, price right, small per-unit suffix on the price baseline. Categories are 40px apart. White compact Contact Sales actions replace rates where needed.

**Transfer:** Expose actual units and exceptions without inventing tier cards.

### Story media card

**Only for:** story indexes

**Use:** Browse linked proof stories.

**CSS:** `background: #edf0f2; border: 1px solid #edf0f2; border-radius: 12px; overflow: hidden; aspect-ratio: 3 / 2; box-shadow: 0px 2px 4px 0px rgba(12,25,39,0.06), 0px 7px 12px 0px rgba(12,25,39,0.09)`

**Text style:** `story-title` — TT Interphases Pro-c98a05336328a01f 500 · 20px/1.4 · tracking -0.01em

**Observed:** Only the image has a frame; the sentence-length title sits outside, 12px below, followed by a small inline arrow. Three columns have generous gutters rather than dense boxed cards.

**States:** Declared: hover image scale 1.01 with a 0.5s transition; focus-visible not specified.

## Imagery and graphics

### Ascending folded spectrum

**Use:** Signature first-screen artwork; repeated behind a catalog closing when that variant is used.

**Observed:** A crisp, large zigzag ribbon rises from lower left to upper right, changing from acid lime to green, mint, turquoise and sky blue. Broad slanted front planes alternate with darker diagonal return planes. It has no texture, outline or floating shadow, and is clipped at the right and bottom edges.

**Transfer:** Make an original ascending folded sculpture with the same clean color progression. This abstract device supplies the visual identity even if the new product has no photogenic object.

**Build:** Use an SVG with three broad parallelogram front faces and three connecting quadrilaterals. At desktop the broad planes occupy roughly 416px by 673px, stepping about 352px right and 193px up; skew the long sides about 20 degrees from vertical. Connect adjacent faces with polygons equivalent to polygon(0px 0px,100% 41%,100% 100%,0px 59%). Layer front planes above connectors. Apply horizontal gradients #deff34 → #8cf97c, #45f4bc → #33dfdf, #34c8f4 → #34bcff; connectors use #65f75f → #12f0aa, #01d3d8 → #02b7f1, then #02a7ff. Extend the last plane beyond the viewport. Scale the entire group together and clip it to the stage.

### Layered interface mosaic

**Use:** Main capability scenes.

**Observed:** White forms and ledger fragments overlap slate code panels, small bank-card objects, live markers and status timelines. They sit in pale-gray wells, cropped at their edges. Surfaces are legible and dimensional but restrained; mint and lime mark activity rather than coloring every field.

**Transfer:** Use two or three actual task fragments from the new product: one input or code fragment and one visible result. The minimum version is HTML cards with thin rules, concise sample data and a small status indicator.

### Technical schematics

**Use:** Explain architecture, flows and state changes.

**Observed:** Dark outlined nodes, compact labels and icon chips connect with thin gray arrows over Dot-field diagram stage. White-stage variants use dark terminal nodes and vivid lime/mint/cyan route labels; complex ideas remain diagrammatic rather than photorealistic.

**Transfer:** Diagram a real transformation in the new product. Keep a small number of nodes with one direction of reading, and use the same compact typographic annotation layer.

**Build:** Use SVG paths with 1px strokes and small arrowheads behind rounded 8px–12px HTML nodes. Dark nodes use #1d2a36 with #657482 edges, white labels, and 16px line icons. Place colored square chips inside nodes or small colored status dots beside mono labels; do not color the full diagram background.

### Proof illumination

**Use:** Distinctive light treatment inside Annotated testimonial.

**Observed:** A pale yellow panel brightens subtly at its lower right; a white variant has blue light in the same location. The glow is diffuse and stays behind the text, not a hard-edged gradient card.

**Transfer:** Retain the corner glow on proof content so the page has a warmer human interruption.

**Build:** Use Proof glow as a clipped pseudo-element behind the content, with a 420px circle, 100px blur and 20% hue opacity. Keep text in a higher stacking layer.

### Grounded product objects

**Only for:** product and solution showcases

**Use:** Hero and split-feature media.

**Observed:** A white phone stands in front of dark code, while thin physical cards float horizontally behind it. Other scenes fan white cards at shallow angles over a broad, soft gray shadow. Small colored details remain inside the objects; the stage is white with no enclosing dark rectangle.

**Transfer:** For software, layer an upright task panel with two shallow result panels and one code sheet. Use slight rotation, thin edges and a broad grounded shadow, not glossy abstract blobs.

**Build:** Create three rounded rectangular planes in perspective, with the foremost plane facing the viewer and the rear two rotated by about -10 and -20 degrees as design guidance. Back them with a large low-opacity slate ellipse blurred beneath the objects; avoid sharp drop-shadow silhouettes.

### Story collages

**Only for:** story indexes

**Use:** Case-study thumbnails.

**Observed:** Landscape compositions combine identity marks, white UI fragments, occasional tightly framed work photography and charts on muted gray, olive or very dark backings. They are not repeated headshot tiles. Contrast and intensity stay inside the image frame.

**Transfer:** Compose a subject-specific collage using a workflow image, a legible result panel and the story's identity; maintain the same 3:2 frame and restrained material depth.

### Announcement vignette

**Only for:** editorial announcements

**Use:** Human-scale art on the right of a compact dark announcement.

**Observed:** A small square landscape painting accompanies the dark copy panel, rather than a full-bleed photo hero.

**Transfer:** Use a warm, hand-made landscape or place-based illustration related to the announcement, keeping it subordinate to the text.

### Icons

**Observed:** Most icons are 16px SVG outlines with 1.5px rounded strokes. Arrows are small northeast pointers or right chevrons. Functional glyphs sit in lime or mint square chips, usually 24px or 32px, with 4px or 8px corners.

**Transfer:** Choose simple geometric line icons with rounded ends; use one accent chip per item rather than multicolor pictograms.

## Section recipes

How recurring sections are built.

### First screen: Folded spectrum opening

**Observed:** A 65px translucent Navigation floats above a white framed stage. The content starts with Announcement badge about 128px from the top, then a 24px gap to the left-aligned promise and muted continuation. The heading block uses opening plus opening-continuation and a 768px measure, taking roughly two thirds of the rail. Actions follow after 32px. Behind and below this upper-left copy, Ascending folded spectrum dominates the lower and right portions without covering the text. White canvas and faint rails are backmost, folds are the middle layer, and copy/actions sit above. The artwork is clipped at the stage bottom around 753px, followed by a roughly 93px monochrome logo strip. Within the first 900px the full headline, continuation, both actions, most of the ribbon and the proof strip are visible; only the top of the following announcement panel appears.

**Transfer:** Keep this as the default new marketing opening, using an original folded sculpture and a short new promise. Without product media the abstract folds still provide the main object. Product openings instead use a 56px bold standalone title, 20px support and a split object scene; solution openings center that bold title above a broad interface scene. Utility and story-index openings are compact and left aligned, without the giant hero scene.

**Avoid:** Do not substitute a centered oversized gradient-text headline, put a dashboard behind the copy, or turn the ribbon into a soft mesh-gradient wallpaper.

**Text style:** `opening` — TT Interphases Pro-c98a05336328a01f 600 · 40px/1.2 · tracking -0.02em

### Inline section heading pair

**Observed:** A heading and regular-weight slate continuation share one 32px text block at a 768px maximum measure. It begins a section with 80px–96px breathing room and is followed by a larger content gap, often 64px before a visual mosaic.

**Transfer:** Write the lead as the argument and the continuation as its explanation. Preserve the inline flow instead of creating a small detached subtitle.

**Text style:** `heading` — TT Interphases Pro-c98a05336328a01f 600 · 32px/1.2 · tracking -0.01em

### Capability mosaic

**Observed:** Feature mosaic tile fills a 12-column grid with 24px gutters. A full-width 420px-tall scene leads, then asymmetric pairs distribute code, physical objects, lists and forms. Titles occupy the same upper-left inset regardless of media arrangement.

**Transfer:** Vary tile width to match the complexity of the new capabilities while keeping a shared backing, corners and title position.

### Annotated proof interruption

**Observed:** Annotated testimonial spans the inner rail between explanatory sections. A compact identity mark anchors the upper left, the quote occupies most of the width, and the separate outcome note sits at the lower right. Proof illumination adds color without sacrificing calm.

**Transfer:** Use actual proof or a grounded editorial observation, with a short annotation explaining the outcome rather than another slogan.

**Text style:** `quote` — TT Interphases Pro-c98a05336328a01f 500 · 20px/1.5

### Measured proof band

**Observed:** Three equal centered metrics occupy a white band with 80px vertical padding. Each stat uses 40px regular numerals and a 16px support caption separated by 8px; captions have a 240px measure.

**Transfer:** Give each metric a distinct proof function. Maintain the restrained numerals and avoid turning the band into three promotional cards.

**Text style:** `stat` — TT Interphases Pro-c98a05336328a01f 400 · 40px/1.2 · tracking -0.02em

### Technical chapter rows

**Observed:** Dark technical band begins with a 32px inline heading pair, muted support and a mint documentation action. Subsequent rows use Technical text link beneath a 24px inline title/support pair on the left and Technical schematics on the right. A small quote and attribution ground the lower-left area. Rows have 48px padding and low-contrast bottom rules.

**Transfer:** Use the dark chapter to explain the mechanism behind the promise, pairing each diagram with a real operational benefit.

**Text style:** `dark-heading` — TT Interphases Pro-c98a05336328a01f 600 · 24px/1.2

### Update timeline ending

**Observed:** A 32px lead sits above four unboxed update entries with 32px gutters. Small square markers sit along a shared pale rule; entries contain a 16px medium title, short 14px support and a 12px mono date. Secondary button follows, then dark Footer navigation.

**Transfer:** Use for ongoing product or company progress, keeping the rule and markers as the organizing device rather than image thumbnails.

### Split feature chapter

**Only for:** product and solution pages

**Observed:** A 460px text measure sits beside a similarly sized object scene or event panel. Mono eyebrow with an 8px lime dot precedes a 32px bold heading by 8px, then 24px to body paragraphs. Sections generally use 96px top and bottom padding; adjacent chapters can become equal two-column vertical stories.

**Transfer:** Choose one mechanism per chapter, moving from explanation to a visible result rather than enumerating every feature in the headline.

**Text style:** `feature-bold` — TT Interphases Pro-c98a05336328a01f 700 · 32px/1.2 · tracking -0.01em

### Catalog closing stage

**Only for:** product and solution pages

**Observed:** On a white-to-pale-gray band with 96px vertical padding, a left-aligned mono eyebrow introduces a 40px bold closing headline and a short 16px paragraph. Compact dark and white actions precede Catalog shell by about 48px. The shared four-column grid sits above a smaller Ascending folded spectrum that emerges from behind its lower-right corner. The next section is a light footer.

**Transfer:** Close a product or solution story by connecting the featured offer to a broader set of relevant capabilities, with the folded art retaining brand energy.

**Text style:** `heading-bold` — TT Interphases Pro-c98a05336328a01f 700 · 40px/1.2 · tracking -0.02em

### Technical pricing ledger

**Only for:** pricing pages

**Observed:** A compact 40px bold title opens at about 116px from the document top with a short 16px support paragraph. Pricing category strips and plain rows follow; the table fills the inner rail. The ending consists of dashed-underlined reference links, a save-page action, a footnote, then a near-white Footer navigation with extended disclosure text.

**Transfer:** Keep this a readable schedule of actual fees rather than a conversion-first plan comparison.

**Text style:** `heading-bold` — TT Interphases Pro-c98a05336328a01f 700 · 40px/1.2 · tracking -0.02em

### Story library and onward panel

**Only for:** story indexes

**Observed:** A mono eyebrow and 56px bold title introduce a three-column Story media card grid. After the last row, a 12px-corner pale-gray onward panel has 32px padding, a 24px title, a small support line and a simple arrow at the far right. A white Footer navigation follows.

**Transfer:** Use the onward panel to connect readers to related editorial material instead of forcing a sales CTA after every story.

**Text style:** `display-bold` — TT Interphases Pro-c98a05336328a01f 700 · 56px/1.05 · tracking -0.02em

### Compact announcement panel

**Only for:** editorial announcements

**Observed:** A dark 8px-corner panel uses 32px padding, a 24px semibold headline, 20px support, and a mint text action. A small square art vignette occupies the right end. The same construction can recur later in a long page.

**Transfer:** Reserve for a genuine update that deserves a distinct but compact editorial voice.

**Text style:** `announcement-heading` — TT Interphases Pro-c98a05336328a01f 600 · 24px/1.2 · tracking -0.004em

## Page flow

**Storyline:** Promise → tangible capability scenes → human and quantitative proof → mechanism-level explanation → broader relevance → onward action and directory.

### Broad platform marketing

1. **Promise** — Two-tone inline headline, paired actions, monumental folded artwork and monochrome proof strip.
2. **Capability demonstration** — Compact announcement and an asymmetric interface mosaic.
3. **Social and quantified proof** — Glowing quote panel, team expertise and a restrained three-metric band.
4. **Mechanism explanation** — Sustained dark chapter with technical schematics, links and small testimonials.
5. **Broader relevance** — Audience-specific benefits, more proof and a repeated announcement.
6. **Onward reading and ending** — Update timeline, outlined read-more action, dark four-column footer and disclosure rule.

**Transfer:** Alternate visual product specificity with human credibility, keeping the technical chapter a coherent change of tone.

### Audience-specific solution marketing

1. **Promise** — Centered bold title and contact action over a broad interface composition with floating objects.
2. **Workflow explanation** — Full-width flowchart, a split feature scene and paired capability chapters.
3. **Broader offering and conversion** — Catalog closing stage with actions and folded spectrum emerging below.
4. **Directory ending** — Light four-column footer and compact disclosures.

**Transfer:** Begin with the audience's workflow and show how the platform expands its options; retain the catalog closing as a scoped template.

### Single-product technical landing

1. **Promise** — Bold left title and concise support beside a grounded object scene.
2. **Capability overview** — Four-column text benefits followed by split feature chapters.
3. **Differentiation** — Detailed comparison rows with subtle rules and mint check markers.
4. **Hands-on explanation** — Dark inset developer workbench followed by a compact technical article panel.
5. **Broader offering and ending** — Catalog closing stage, folded spectrum and light footer.

**Transfer:** Move from tangible benefit to operational detail, using a real workflow demonstration where useful.

### Transparent pricing reference

1. **Orientation** — Compact title and a short custom-pricing qualification.
2. **Pricing** — Repeated gray category strips, lime icon chips and right-aligned rates in plain divided rows.
3. **Clarification** — Reference links, save action and a precise footnote.
4. **Directory ending** — Near-white footer with longer legal disclosure.

**Transfer:** Prioritize scanning, units and exceptions; do not import the theatrical landing hero into this page type.

### Proof-story index

1. **Orientation** — Mono category label and bold title.
2. **Social proof browsing** — Three-column image-and-title story grid with generous row gaps.
3. **Onward reading** — Pale linked panel with title, support line and far-right arrow.
4. **Directory ending** — White four-column footer and legal text.

**Transfer:** Let story imagery and specific outcome titles do the selling rather than adding promotional blocks between rows.

## Writing

Confident, technically literate and direct. Warmth comes from explaining how the product works and giving credit to real people, not from exuberance or jokes.

**Do not copy:** Do not reuse Increase's name, wordmark, proprietary artwork, customer identities, quotations, metrics, banking claims, regulatory status, product promises or fees. Source examples illustrate syntax only; all claims and proof must belong to the new product.

- **Addressing the reader:** Use you and your for builders and operators, we for the team and its deliberate engineering choices. Use plain product nouns when a neutral description is clearer.
- **Rhythm:** Short declarative leads alternate with longer explanatory sentences. Headlines commonly run 4–10 words; paragraphs use one to three sentences. Inline continuations extend the thought without a new rhetorical flourish.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category and who it serves, then explain the enabling mechanism. | 5–12 words for the lead | “Banking for ambitious technology companies.” |
| Inline continuation | A plain imperative or explanation continues the lead at the same visual scale. | 8–18 words | “Build great financial products with an API-first bank.” |
| Capability headline | Verb plus a specific capability or operational result. | 4–8 words | “Approve authorizations in real-time”<br>“Customize physical and virtual cards” |
| Supporting paragraph | State the mechanism and enumerate useful specifics, not abstract adjectives. | 15–50 words | “Programmatically approve or decline every card authorization for full control.” |
| Action | Short literal verb-object label, with a more descriptive read-about link for technical depth. | 2–8 words | “Contact sales”<br>“Read about our core technology” |
| Story title | Name the organization and concrete result rather than writing a vague endorsement. | 8–16 words | “How Ramp scaled a successful bill pay product with [Brand]” |
| Closing statement | Frame comprehensiveness as useful restraint. | 7–12 words | “Everything you need and nothing you don't” |

**Words and phrasing to use:** direct; build; real-time; flexibility; reliability; transparency; control; programmatic; unopinionated; primitives; from scratch

**Avoid:** revolutionary; game-changing; magical; seamless everything; unlock limitless potential; exclamation-heavy urgency

**Rules:**

- Explain what is exposed, connected or controllable before describing it as powerful.
- Pair a broad benefit with a tangible mechanism or example.
- Use precise technical terms when they reduce ambiguity; explain the reader's consequence immediately.
- Keep button labels literal and sentence-case; reserve longer labels for further-reading links.
- Quotes and statistics should substantiate a nearby argument, not repeat the hero as praise.

## Do's and Don'ts

### Do

- Use the 1160px framed rail and align section edges across light and dark treatments.
- Keep the default 40px promise and 32px section lead at weight 600 with regular-weight inline continuations.
- Place saturated color in the folded sculpture, small 24px–32px icon chips and compact actions.
- Use 24px gutters and 16px corners for the visual mosaic; clip media intentionally at its boundaries.
- Include a corner-glowing proof panel with mono attribution and a separate outcome note.
- Keep statistics regular at 40px rather than turning them into a second display headline.
- Use 48px internal technical-row padding and 96px major section spacing to separate diagram detail from page rhythm.
- Give the ending a real directory structure with four aligned columns and a disclosure rule.

### Don't

- Do not apply the 56px weight-700 product-title variant to every headline; it erases the editorial default.
- Do not turn 8px-corner action rectangles into pill buttons.
- Do not make every section dark; the sustained #151e29 chapter contrasts with a predominantly white page.
- Do not use wide uppercase tracking for mono eyebrows; they are 14px/20px with normal tracking.
- Do not round each catalog cell individually; the 12px outer shell owns the corners and 1px seams.
- Do not replace the restrained 40px regular stats with giant neon counters.
- Do not wrap update entries in heavily shadowed image cards; their shared rule and mono dates organize them.
- Do not make product imagery float with hard black shadows; keep broad grounded gray depth and thin edges.

## Motion and responsive

### Motion

**Observed:**

- Declared action and navigation transitions commonly use 0.15s cubic-bezier(.4, 0, .2, 1).
- Story-media transformations declare 0.5s cubic-bezier(.4, 0, .2, 1), including hover scale 1.01.
- The folded artwork has separate bar and diagonal animation names; the proof-logo strip declares a linear infinite marquee with a variable duration.
- A small product-status indicator declares a 1.6s ease-in-out infinite pulse; some technical media declares opacity/transform transitions at 1.2s cubic-bezier(.23, 1, .32, 1).

**Transfer:**

- Keep action feedback brief and color-led. Let small operational indicators carry ongoing motion rather than moving all text.
- If the folded sculpture animates, move connected planes as a coherent folded object; the settled geometry must remain the visual anchor.

**Unknown:**

- Exact timing and trajectories of the folded-art entrance and the logo-marquee duration are not established.
- No focus-visible treatment or reduced-motion behavior is established.

### Responsive

**Observed:**

- Desktop uses the framed rail, asymmetric mosaic, three-metric band and four-column catalog. Utility classes indicate single-column defaults, two-column intermediate story grids and larger-screen three-column story grids; numeric breakpoint values are not established.
- Some technical diagram media is hidden at narrow widths; default opening type has smaller size classes before its desktop size.

**Transfer:**

- On narrow screens keep the opening promise and actions above a contained lower ribbon, scaling the connected sculpture as one unit.
- Stack mosaic and split-feature scenes while preserving their internal visual hierarchy. Collapse catalog and footer columns into readable groups instead of shrinking 14px text.
- Keep price descriptions and rates associated; allow the per-unit suffix beneath the rate when needed.

**Unknown:**

- Exact mobile viewport layouts, breakpoint widths and mobile navigation interaction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
