# Symbol Audio — tactile modernist listening

## Overview

A furniture-showroom sensibility pairs buttery pale yellow with black, warm wood and crisply framed photography. Bold geometric sans headings have an unusually personable, angular rhythm, while small sans captions keep the presentation practical. The result suits design-led physical products: image-rich, materially convincing and spacious between chapters, yet densely informative around purchase decisions. Electric blue and brick red provide distinct editorial identities rather than scattered decoration.

### Essentials

- The object gets the room, not a slogan: a 900px desktop opening splits a 952px image stage from a 487px purchase rail, with a 52px/1 product title above and buying controls near the bottom.
- Headlines feel cut from geometry: bold SupremeLL at 52px/1 and 34px/43px, both tracked -0.02em; compact 15px captions deliberately contrast with these broad statements.
- Butter-yellow is the default architectural field: #fffcda carries most of a product page, #000000 creates a concentrated technical chapter, and saturated color remains in photography and small tinted badges. Blue and red full-page identities belong to separate editorial variants.
- Soft controls inside hard architecture: 40px-high, 40px-radius purchase buttons and 40px circular arrows sit among square images, square cards and 1px rules; there are no raised-card shadows.
- Proof is tactile and captioned: pair close-up material or hand-at-work photographs with a narrow 15px bold label and a wider 15px explanatory paragraph, separated by 20px; use authentic process imagery or a plainly lit material sample when finished lifestyle media is unavailable.
- Include a dark technical plate and a graphic newsletter close: cream linework and ruled specifications on black make practical information a visual event; the ending is a full-width 34px signup line above a 148px graphic identity mark and small link columns. Use a simplified product outline and a new geometric monogram when equivalent artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter paper | `#fffcda` | `--color-canvas` | background, text, border | Default product and catalog canvas; reversed type and rules in black chapters. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brick red | `#c72a00` | `--color-rust` | text, accent, background | Default small status text and 10% badge wash; also the full background of the company-story theme. |
| Warm status wash | `#f9e7c4` | `--color-status-wash` | surface | Brick red at 10% over butter paper behind status labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm studio white | `#fffffd` | `--color-card` | surface | Isolated product card backing, subtly distinct from the yellow page. |
| Card edge | `#e6e6e4` | `--color-fine-edge` | border | Visible result of black at 10% over warm studio white; the perimeter becomes black on hover. |
| Soft control rule | `#bfbda4` | `--color-control-rule` | border | Visible black at 25% over butter paper, separating gallery and option rows. |
| Muted olive gray | `#807e6d` | `--color-muted-label` | text | Newsletter prompt: black at 50% over butter paper. |
| Black | `#000000` | `--color-ink` | text, background, border, action | Default lettering, structural rules, purchase actions and technical bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| brand-editorial pages | Electric blue | `#447cf0` | `--color-blue` | background, text, link | Full editorial canvas and product-card lettering in the blue theme. |
| brand-editorial pages | Cool silver | `#dfe2e5` | `--color-silver` | text, border | Type, graphics and structural lines over electric blue. |
| company-story pages | Dusty rose | `#e5b0a3` | `--color-rose` | text, border | All typography, identity graphics and fine rules over the brick-red company-story canvas. |

## Typography

- **SupremeLL** — Headlines, statement copy, feature labels, navigation and buttons. Bold geometric sans with angular joins, a low friendly roundness and emphatic single-storey forms. If unavailable, use **Jost**. Use 700; preserve the tight tracking and geometric character. Font stack: "SupremeLL", "Jost", sans-serif.
- **Chalet-LondonSixty** — Body copy, prices, specification values and badges. Light, compact geometric sans; small and functional rather than editorially oversized. If unavailable, use **Questrial**. Use 400 and retain compact line spacing. Font stack: "Chalet-LondonSixty", "Questrial", sans-serif.
- **Chalet-NewYorkSixty** — Product-card names, specification labels and selected option values. Heavier companion to the body sans, distinct from the sculptural heading family. If unavailable, use **DM Sans**. Use 600 for the heavier companion appearance. Font stack: "Chalet-NewYorkSixty", "DM Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | SupremeLL | 700 | 52px | 1 | -0.02em | size clamp(calc(48*1px),calc((52*1vw)/1440*100),calc(52*1px)) | Default product title and chapter heading. |
| statement | SupremeLL | 700 | 34px | 1.265 | -0.02em | size clamp(calc(18*1px),calc((34*1vw)/1440*100),calc(34*1px)) | Full-width product explanation, chapter support statement and offset editorial paragraphs. |
| newsletter | SupremeLL | 700 | 34px | 1.25 | normal | fixed | Oversized newsletter input prompt and unboxed Submit action. |
| body | Chalet-LondonSixty | 400 | 15px | 1.333 | normal | fixed | Product summary, feature explanations, prices and specification values. |
| feature-label | SupremeLL | 700 | 15px | 1.333 | normal | fixed | Narrow bold label beside explanatory captions. |
| product-link | Chalet-NewYorkSixty | 400 | 15px | 1.333 | normal | size clamp(calc(15*1px),calc((15*1vw)/1440*100),calc(15*1px)) | Small product-card title and technical subheading. |
| menu | SupremeLL | 700 | 14px | 1.333 | normal | fixed | Navigation, footer links and small utility text. |
| action | SupremeLL | 700 | 14px | 1.33333 | normal | fixed | Purchase and outline collection buttons. |
| option-value | Chalet-NewYorkSixty | 400 | 14px | 1.333 | normal | size clamp(calc(14*1px),calc((14*1vw)/1440*100),calc(14*1px)) | Selected product finish or configuration. |
| badge | Chalet-LondonSixty | 400 | 13px | 1.3 | normal | fixed | Small sentence-case status chips. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| catalog and brand-editorial pages | display | SupremeLL | 700 | 80px | 1.125 | -0.02em | size clamp(calc(60*1px),calc((80*1vw)/1440*100),calc(80*1px)) | Large editorial titles and collection introductions. |
| catalog pages | collection-title | SupremeLL | 700 | 20px | 1.333 | -0.02em | size clamp(calc(18*1px),calc((20*1vw)/1440*100),calc(20*1px)) | Collection-card headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- SupremeLL-Bold is a bold cut even where its declared CSS weight is 400. Preserve its visual mass rather than rendering a regular geometric face.
- Large headings use -0.02em tracking; small labels and buttons return to normal tracking. The newsletter has normal tracking despite sharing the 34px size of statement copy.
- Do not promote explanatory captions to standard 18px marketing body copy: the contrast between 15px detail and broad bold statements is characteristic.
- The monumental editorial identity is vector artwork rather than an additional text-font recipe.

## Layout

**Density:** Airy between chapters, compact within information blocks: small captions and ruled controls sit inside broad photographic compositions.

### Spacing

**Spacing system:**

- **site step** 10px — Base margin and gutter unit; desktop compositions most often use 2 steps.

| Value | Use |
| --- | --- |
| 5px | Adjacent status badges and title-to-price micro spacing. |
| 10px | Image-to-caption spacing and compact row padding. |
| 20px | Desktop page margins, grid gaps, section inner padding and card-detail padding. |
| 40px | Product-card image inset and larger internal gaps. |
| 80px | Vertical padding of a compact inverted collection callout. |
| 100px | Editorial collection bottom spacing. |
| 200px | Major chapter breathing room, equivalent to 20 site steps. |

### Containers and grids

- **editorial grid**: 12 columns · gap 20px · side padding 20px. Full-width desktop structure. At 1440px, the inner span is 1400px; use six columns for paired images, four for three-up proof, and deliberate rightward text offsets.
- **product stage**: 12 columns · gap 20px · side padding 0px. Eight-column gallery and four-column purchase rail. Gallery occupies about two thirds of the viewport; the rail has its own 20px inset.
- **three-up grid**: 3 columns · gap 20px · side padding 20px. 453px-wide desktop product cards and technical-detail photos.
- **editorial collection grid** (only for brand-editorial pages): 4 columns · gap 20px · side padding 20px. 335px cards; the first row begins one column inward, leaving an intentional opening under the heading.

## Corner radius

| Element | Radius |
| --- | --- |
| purchase button | 40px |
| gallery control | 9999px (pill) |
| status badge | 6px |
| media and cards | 0px |

## Surfaces and depth

### Surfaces

#### Butter canvas · level 0

**Use:** Default new product or marketing landing page.

**CSS:** `background: #fffcda; color: #000000`

**Transfer:** Keep the warmth continuous through image gutters and long-form content.

#### Studio card · level 1

**Use:** Product and collection browsing.

**CSS:** `background: #fffffd; border: 1px solid rgba(0,0,0,0.1); border-radius: 0px; box-shadow: none`

**Observed:** The fine perimeter is a separate overlay, so it does not change card geometry when strengthened.

**Transfer:** Keep imagery isolated and object-centered; hierarchy comes from scale and spacing rather than elevation.

#### Technical black · level 0

**Use:** Specification plate and collection callout.

**CSS:** `background: #000000; color: #fffcda; padding: 20px`

**Observed:** A flat full-width inversion, not a floating rounded panel.

**Transfer:** Use this visual interruption for concrete product facts.

#### Blue editorial canvas · level 0

**Only for:** brand-editorial pages

**Use:** Expressive collections and brand-led discovery.

**CSS:** `background: #447cf0; color: #dfe2e5`

**Observed:** The color continues into the header and footer; white cards carry blue lettering.

**Transfer:** Treat blue as a page identity, not as alternating decorative stripes.

#### Red story canvas · level 0

**Only for:** company-story pages

**Use:** People, studio and company narrative.

**CSS:** `background: #c72a00; color: #e5b0a3`

**Observed:** Dusty rose rules and type run through the complete page.

**Transfer:** Carry this pairing consistently through people rows, photographs and the newsletter ending.

## Components

### Fixed navigation

**Use:** Global persistent orientation.

**CSS:** `position: fixed; height: 64px; width: 100%; padding: 0px 20px; background: #fffcda; color: #000000; border-bottom: 1px solid #000000; z-index: 50`

**Text style:** `menu` — SupremeLL 700 · 14px/1.333

**Observed:** Small identity at left, main navigation begins around the second quarter, search and cart at right, compact monogram at the far edge. Editorial themes recolor the whole header to match their canvas.

**States:** Declared: hover opacity 1 on the targeted menu item; ancestor hover opacity 0.5 on its peers; focus-visible not specified.

### Primary button

**Use:** Purchase or principal product conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 40px; width: 100%; padding: 0px 13.3px; border: 2px solid #000000; border-radius: 40px; background: #000000; color: #fffcda`

**Text style:** `action` — SupremeLL 700 · 14px/1.33333

**Observed:** The price shares the same centered line after the action, separated by a small gap. The product rail's full width makes the button broad but slim.

**States:** Declared: hover background transparent, border-color #000000, color #000000; focus-visible not specified.

### Gallery arrow

**Use:** Previous and next image navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; width: 40px; border: 1px solid #000000; border-radius: 9999px; background: transparent; color: #000000`

**Observed:** Opposing arrow glyphs sit at the lower corners of the gallery. Small image thumbnails and thin progress lines occupy the middle and bottom edge.

**Transfer:** Keep the controls visually lightweight and outside the product silhouette.

### Status badge

**Use:** A short product status above the title or at a card's upper-left.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 3.9px 8.4px; border-radius: 6px; color: #c72a00; background: rgba(199,42,0,0.1)`

**Text style:** `badge` — Chalet-LondonSixty 400 · 13px/1.3

**Observed:** A 10% colored layer backs the text without reducing its opacity. Multiple statuses have a 5px gap; blue and green statuses are additional category variants.

**Transfer:** Use one factual status rather than a row of promotional badges.

### Option row

**Use:** Product finish or configuration selection.

**CSS:** `height: 42px; border-top: 1px solid rgba(0,0,0,0.25); color: #000000`

**Text style:** `option-value` — Chalet-NewYorkSixty 400 · 14px/1.333

**Observed:** A plain label occupies the first third, a heavier selected value fills the middle, and a tiny chevron aligns right; the hit region adds 10px padding.

### Product card

**Use:** Related products and collection browsing.

**CSS:** `display: flex; flex-direction: column; position: relative; overflow: hidden; background: #fffffd; border-radius: 0px`

**Text style:** `product-link` — Chalet-NewYorkSixty 400 · 15px/1.333

**Observed:** A square image stage above an 80px detail strip, containing a small title then a 'from' price. The 453px desktop card has a 373px contained product image with 40px side insets. A fine border overlay strengthens on hover.

**States:** Declared: hover border overlay opacity changes from 0.1 to 1; focus-visible not specified.

**Transfer:** Maintain consistent stage size even when objects vary in proportions.

### Feature caption

**Use:** Explain what a close-up proves.

**CSS:** `display: flex; align-items: baseline; gap: 20px; margin-top: 10px; color: #000000`

**Text style:** `body` — Chalet-LondonSixty 400 · 15px/1.333

**Observed:** The feature-label recipe occupies about one quarter of the caption width; a body paragraph occupies the wider neighboring area. Captions sit directly on the page, without boxes.

**Transfer:** Name one tangible attribute in the narrow label, then explain its practical consequence.

### Specification row

**Use:** Technical facts within the inverted plate.

**CSS:** `display: flex; justify-content: space-between; align-items: baseline; padding: 6px 0px; border-top: 1px solid #fffcda; color: #fffcda`

**Text style:** `body` — Chalet-LondonSixty 400 · 15px/1.333

**Observed:** Label and value each use half the row width. A final bottom rule closes the table; rows grow naturally for wrapped values.

### Newsletter line

**Use:** Shared closing conversion.

**CSS:** `display: flex; position: relative; padding-bottom: 10px; border-bottom: 1px solid #000000; color: #000000`

**Text style:** `newsletter` — SupremeLL 700 · 34px/1.25

**Observed:** A single long input and Submit share one underline. The input prompt is at 50% opacity; Submit is fully opaque, unboxed and right aligned. It inherits silver on blue and rose on red.

## Imagery and graphics

### Isolated product stage

**Use:** Opening gallery and product cards.

**Observed:** Front-facing or slight three-quarter views preserve the full object silhouette. Natural ash and walnut grain, leather pulls, metal tubing and chromed edges are sharply legible. The gallery uses the yellow canvas; cards use studio white. Objects are surrounded by substantial empty field rather than cropped tight.

**Transfer:** Photograph or render the complete product with soft even illumination and realistic materials. If no cutout is available, use a clean single-color studio background close to the page color.

### Hands and material proof

**Use:** Paired benefits, technical triptychs and sourcing chapters.

**Observed:** Close framing shows hands browsing, tools working timber, joinery, leather and brass, manufacturing equipment and forests. Photography is natural-color, warmly tactile and documentary rather than desaturated. Pairs can be 690px square or 690×493px; triptychs use 453px squares with split captions below.

**Transfer:** Show the equivalent texture, mechanism and process for the new product. Real material samples and one authentic operation are better than abstract stock imagery.

### Cream technical drawing

**Use:** Signature illustration in the black specification plate.

**Observed:** A cream orthographic front elevation floats centrally in a generous black field. Thin straight outlines trace construction, restrained flat fills distinguish solid parts, and dimension arrows sit outside the silhouette.

**Transfer:** Supply a simplified measured outline of the new product. For an intangible product, draw its actual system or workflow as a sparse technical diagram, not a decorative wireframe.

**Build:** Use an SVG viewBox with a centered front elevation, no perspective, approximately 1px cream strokes at desktop scale, sparse cream fills at reduced opacity, horizontal and vertical dimension lines with small arrowheads, and plain labels outside the object. Keep the drawing within a roughly 453px square stage; leave black breathing room around it.

### Photographic assurance tiles

**Use:** Product assurance, service and ownership support.

**Observed:** Three-up portrait tiles are 453×541px, with warm photography darkened for cream typography. Each has a large centered topic and a small paragraph near its bottom. Subjects connect directly to the promise: woodwork, delivery, landscape, room, care and fabric.

**Transfer:** Use one contextual photo per real service promise. If photography is limited, make fewer strong tiles rather than reusing unrelated stock scenes.

**Build:** Place a full-cover rectangular photograph under a uniform translucent black layer, then center a short cream heading and bottom-align a cream support paragraph with about 20px side clearance. Match readable contrast without crushing the material texture.

### Monumental editorial word sculpture

**Only for:** brand-editorial pages

**Use:** Immersive brand opening.

**Observed:** A 1400×400px silver vector wordmark spans almost the whole width and overlaps a centered 690×816px portrait interior photograph. The room is saturated amber, orange, black and magenta; the blue field remains visible on both sides.

**Transfer:** Create a new oversized typographic identity or very short product word. Pair it with a richly colored room or installation; a carefully staged portrait photograph is the minimum equivalent.

**Build:** Set or draw a very heavy geometric word in SVG, fit it across the inner width without stretching individual letters, and overlay it above the portrait photo with a higher stacking layer. Fill the word with #dfe2e5; use #447cf0 behind both. Keep the lower image visible through and below the lettering.

### Offset people and places

**Only for:** company-story pages

**Use:** Studio and people narrative.

**Observed:** Unretouched-looking portraits, listening rooms and a small architectural building are arranged at unequal sizes. Narrow 335px portraits sit beside 808px square interiors or 453px portraits, with broad red negative space and staggered baselines.

**Transfer:** Use real people in their working environment; preserve the asymmetric gallery rather than building identical headshot cards.

### Icons

**Observed:** Sparse monochrome utility marks: 14px search, roughly 24px header monogram, small chevrons and plus glyphs. Gallery navigation is a simple arrow inside a 40px circle. A much larger geometric identity graphic anchors the footer.

**Transfer:** Use solid monochrome utility icons and plain arrow glyphs. Build a new footer monogram from simple circles and right-angled shapes in the current theme text color, with no shadow or illustrative detail.

## Section recipes

How recurring sections are built.

### First screen: Object and purchase rail opening

**Observed:** Butter canvas behind a fixed 64px Fixed navigation. The remaining first-screen composition is a two-thirds image gallery beside a one-third product rail, separated by a faint vertical rule. The 952×836px gallery contains a complete front view, centered low enough to feel grounded, with generous air above; the object itself spans a little over half of the gallery width. Its lower edge leaves room for Gallery arrow controls, thumbnails and progress lines. In the 487px rail, 20px insets frame a Status badge followed by a 52px/1 black title at the top; a large intentional gap separates this from the short 15px summary, Option row and full-width Primary button near the bottom. Price is inside the button and a tiny financing utility line sits below it. Within 900px all product identity, principal object and buying controls are visible; the explanatory statement and proof imagery begin below the fold.

**Transfer:** For a new product, preserve the gallery-to-rail proportion and top-versus-bottom anchoring. Use a clean studio product image or one calm render, not a collage. Catalog and company-story pages instead use a five-column title/summary region and seven-column landscape photograph, reaching about 664px down the page; brand-editorial pages use the scoped word-sculpture opening.

**Avoid:** Do not center a giant slogan over a tiny object, fill the deliberate rail gap with feature bullets, or replace the contained gallery object with a full-bleed lifestyle crop.

**Text style:** `heading` — SupremeLL 700 · 52px/1 · tracking -0.02em

### Heading and broad statement

**Observed:** Heading at 52px, followed after roughly 13–20px by a 34px statement. Some introductions omit the heading and use the statement across the full 1400px inner width. Chapter transitions often have 200px of breathing room above.

**Transfer:** Introduce a practical capability with a short topic, then a declarative benefit. Use the broad statement as a change of reading pace rather than a testimonial.

### Captioned material pairs

**Observed:** Two six-column photographs with a 20px gutter; Feature caption underneath each. Shorter documentary pairs are landscape; material and sourcing pairs are square. The page canvas remains visible through all gutters.

**Transfer:** Pair use with making, or material with origin. Keep image dominance and the narrow-label/wide-explanation caption split.

**Text style:** `feature-label` — SupremeLL 700 · 15px/1.333

### Technical detail triptych

**Observed:** Three 453px square detail images across the inner grid, each with Feature caption; 200px bottom breathing room closes the chapter.

**Transfer:** Give each close-up a distinct mechanism, construction detail or usability consequence.

### Inverted technical plate

**Observed:** Technical black spans the width with 20px padding. A 52px cream title occupies the upper-left, Cream technical drawing sits in the open middle field, and compact facts anchor the lower edge in three-column groupings. Specification row and short feature lists handle detail without visual clutter.

**Transfer:** Preserve the strong light-to-dark change and the high empty-field-to-copy ratio while adapting the diagram and facts to the product.

### Offset editorial conviction

**Observed:** A 52px heading and broad 34px statement lead into another 34px paragraph offset to start around the fourth column, occupying roughly two thirds of the width.

**Transfer:** Use this asymmetry for one substantial point of view or long-term product principle, not a wall of centered text.

**Text style:** `statement` — SupremeLL 700 · 34px/1.265 · tracking -0.02em

### Assurance and collection close

**Observed:** Photographic assurance tiles form three-up rows. A later compact Technical black callout pairs a short statement, body copy and a cream outline pill with a landscape product image, using 80px vertical padding. Related Product cards return to the light canvas before the footer.

**Transfer:** Answer the real ownership questions for the new category, then offer a useful next destination. Keep the outline action at 40px high with 2px cream border and 40px radius.

### Graphic newsletter ending

**Observed:** A 257px desktop footer uses 20px padding and continues the page theme. Newsletter line spans the full inner width; below it, a 148×142px geometric mark anchors the left, utility links begin halfway across, and social/legal links occupy the right quarter. Copyright aligns beneath the middle links. There is no separate dark footer box.

**Transfer:** Close every page type with this shared graphic arrangement and a new identity mark. Keep the subscription prompt at 34px, visibly larger than the 14px links.

**Text style:** `newsletter` — SupremeLL 700 · 34px/1.25

### Ruled people index

**Only for:** company-story pages

**Observed:** A small section label introduces an offset 1045px-wide roster beginning one quarter of the way across. Each row has a rose top rule, 34px name and role at left, and a narrow 15px biography column to the right. Staggered portraits continue after the roster into the shared newsletter ending.

**Transfer:** Use this for experts, makers or contributors where short biographies genuinely help establish trust.

### Editorial collection launch

**Only for:** brand-editorial pages

**Observed:** A cool silver 80px title sits above a four-column Product card grid on Blue editorial canvas. The first card starts in the second column on the first row, while the next row uses the full width. Thin silver top rules separate collections.

**Transfer:** Keep the empty first cell as intentional typographic breathing space and the product photos as the denser counterweight.

**Text style:** `display` — SupremeLL 700 · 80px/1.125 · tracking -0.02em

## Page flow

**Storyline:** object and proposition → tangible benefit proof → practical detail → ownership confidence → related discovery → graphic subscription close

### Design-led product landing with deep material and ownership proof

1. **Product demonstration** — A contained full-object gallery shares the first screen with an anchored purchase rail.
2. **Promise** — A broad bold statement explains the value, followed by two captioned use-and-making photographs.
3. **Capability chapters** — A technical-detail triptych leads to an inverted diagram and ruled specifications.
4. **Trust and objection handling** — Material/sourcing photographs, large conviction copy and photographic assurance tiles explain longevity and ownership.
5. **Related discovery** — An inverted collection callout and three related cards extend the decision.
6. **Closing call** — The graphic newsletter line and monogram footer complete the page.

**Transfer:** Default for a new physical product; scale the depth of proof to the actual buying questions.

### Shorter configurable product presentation

1. **Product demonstration** — The same gallery and purchase rail supports more configuration rows and thumbnails.
2. **Promise** — One bold sentence precedes an immersive full-width detail photograph.
3. **Practical proof** — A black specification chapter precedes an offset finish carousel and manufacturing photo.
4. **Related discovery** — Two three-card recommendation groups broaden the options.
5. **Closing call** — The light-canvas newsletter and monogram footer finish the page.

**Transfer:** Use when finish choice and engineering are more relevant than a long materials narrative.

### Brand-led discovery and collection merchandising

1. **Identity** — Monumental overlapping word artwork and a portrait interior photograph establish atmosphere.
2. **Discovery** — Ruled editorial collection introductions repeat with offset four-column product grids.
3. **Positioning** — A large heading and broad statement connect the range; a four-image category strip adds breadth.
4. **Trust** — A split company introduction pairs concise copy with architecture.
5. **Closing call** — The blue theme continues into the graphic newsletter close.

**Transfer:** Use the scoped blue identity for a multi-category editorial destination, not the ordinary product default.

### Catalog navigation through product families

1. **Orientation** — A split editorial title and bottom-anchored summary face a wide lifestyle image.
2. **Promise** — A broad 34px statement introduces the collection approach.
3. **Discovery** — 52px category headings introduce three-column white collection cards, each with name, concise description and starting price.
4. **Closing call** — The yellow canvas continues into the newsletter and monogram footer.

**Transfer:** Use clear category groupings and generous separation rather than adding ornamental filters.

### Company and people credibility

1. **Identity** — A red-and-rose split opening pairs a large title and concise summary with architecture.
2. **Positioning** — Broad bold philosophy copy leads to unequal-size room and people photographs.
3. **Human proof** — An offset ruled roster introduces contributors with compact biographies.
4. **Atmosphere** — Staggered portraits retain broad red negative space.
5. **Closing call** — The red theme continues uninterrupted into the shared newsletter footer.

**Transfer:** Use the red story theme and asymmetry to humanize the organization without turning people into product cards.

## Writing

Warm, matter-of-fact design confidence. The writing links beauty to everyday function, with technical specifics supporting the emotional promise rather than sales superlatives.

**Do not copy:** Do not reuse Symbol Audio names, logos, product names, biographies, artist or album artwork, proprietary photography, certification claims, capacities, prices, warranties or sourcing percentages. Examples demonstrate tone only; new claims must be true for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'we' for design intent and making, 'your' for practical ownership benefits, and the product's name for direct specification-led summaries.
- **Rhythm:** Headings are usually short noun phrases or concise declarative promises. Large statement paragraphs can be expansive; small captions remain concrete and explanatory. Sentence case dominates, with occasional casual lower-case collection headings and restrained ellipses.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product title | The actual product name without a promotional preamble. | 2–5 words | “Dovetail 3 × 2”<br>“USM DJ Booth” |
| Chapter heading | Name the topic or make one durable benefit explicit. | 2–7 words | “Technical Features”<br>“Designed to Last a Lifetime” |
| Supporting statement | A plain-language principle with tangible materials or functional consequences. | 6–14 words for a short line | “Every detail serves a purpose.”<br>“Premium hardwoods, responsibly sourced, built to last.” |
| Feature label | Name the construction detail, then explain what it does in nearby body copy. | 2–8 words | “Adjustable Leveling Feet”<br>“Soft close drawers with leather pulls” |
| Action | Direct verb plus object; avoid clever conversion language. | 1–4 words | “Add To Cart”<br>“Learn more →”<br>“Submit” |

**Words and phrasing to use:** beautifully functional; thoughtfully designed; built to last; solid; crafted; natural beauty; everyday; designed for; explore

**Avoid:** revolutionary; game-changing; unlock; disrupt; ultimate luxury; hurry; don't miss out

**Rules:**

- Explain why a detail matters immediately after naming it.
- Support a large emotional promise with visible material or process proof.
- Use specific capacities and dimensions only when they are real and useful.
- Let merchandising headings be conversational; keep product facts literal.
- Prefer durability and enjoyment over status or exclusivity rhetoric.

## Do's and Don'ts

### Do

- Keep the default title at 52px/1 with -0.02em tracking and a genuinely bold geometric cut.
- Use 20px desktop gutters to connect gallery captions, card grids and footer alignment.
- Reserve 200px breathing room for meaningful chapter changes rather than widening every caption gap.
- Keep product imagery square-cornered and fully contained where silhouette matters.
- Pair 15px bold feature labels with 15px body explanations in a 20px-gap caption row.
- Use cream technical linework and 1px ruled facts to make the black chapter informative.
- Make the newsletter prompt and Submit both 34px/1.25, with only the prompt at half opacity.
- Keep purchase buttons slim at 40px high even when they span the full rail.

### Don't

- Do not turn every image into a rounded 16px card; the square photographic architecture is essential.
- Do not add drop shadows to studio cards; their edge is a 10% black hairline.
- Do not substitute pure white for the #fffcda default page field.
- Do not scatter red and blue through an ordinary product page as competing CTA colors.
- Do not apply the 80px editorial display size to the standard purchase-rail title.
- Do not inflate footer links to compete with the 34px newsletter line.
- Do not replace small 13px status chips with uppercase tracking-heavy ribbons.
- Do not use tiny generic feature icons instead of the material-detail photographs.

## Motion and responsive

### Motion

**Observed:**

- Declared purchase transition: background 0.3s, color 0.3s; hover reverses the filled black button to transparent.
- Declared navigation opacity transition: 0.3s cubic-bezier(0.4, 0, 0.2, 1); peers dim to 0.5 while the target stays at 1.
- Declared card-border opacity transition: 0.3s cubic-bezier(0.4, 0, 0.2, 1).

**Transfer:**

- Use the border-strengthening hover to give square cards feedback without introducing elevation.
- Keep color changes and peer dimming restrained; the photographs and object silhouette remain the visual focus.

**Unknown:**

- Gallery autoplay, drag inertia, scroll-linked identity behavior and ticker timing are not established.
- Focus-visible and active treatments are not specified.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 480px, 550px, 768px, 940px, 1200px, 1600px, 1800px and 2400px.
- Product structure includes a column-first small-screen layout and a 12-column desktop grid; content grids use 10px smaller-screen gaps and 20px desktop gaps.
- Newsletter typography has 24px smaller-screen and 34px desktop declarations.

**Transfer:**

- On narrow layouts, stack the contained product gallery and purchase content while preserving a clear object silhouette and reachable purchase controls.
- Collapse caption labels and explanations without separating a caption from its photograph.
- Reduce columns before shrinking the practical 15px reading text; retain the distinction between page field and studio card.

**Unknown:**

- Exact mobile compositions, crop choices, sticky purchase behavior and breakpoint-specific header menus are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
