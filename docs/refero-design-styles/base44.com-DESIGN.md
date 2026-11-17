# Base44 — builder paper and punch

## Overview

A light, hands-on software style with the confidence of a workshop poster rather than a polished corporate brochure. Warm gray paper, charcoal grotesk typography, electric blue and hot orange surround cut-out interfaces, candid people and tactile printed textures. Oversized promises and sparse editorial layouts alternate with dense, ruled explanations, making it well suited to creation tools and approachable technical products.

### Essentials

- Headlines behave like compressed poster statements: Dazzed 600 at 93.7px/1.05 with -0.04em tracking for the opening, and 57px/1.05 for ordinary section leads; sentence case rather than spaced capitals.
- The opening puts a usable object between promise and proof: a centered headline, a 727px-wide support line, a 555×150px white composer and a low horizontal collage all fit within a 900px first screen.
- Actions are small tools, not floating pills: charcoal buttons use 8px corners, 44px height and 22px side padding; the fixed navigation action is only 38px tall.
- Color arrives as printed sheets against mostly neutral paper: #eeeceb dominates, #3950e6 fills a major split panel and the closing band, and #ff6a00 marks selected cards and 10px card feet. Keep colored expanses episodic rather than tinting every section.
- Proof looks assembled on a workbench: square-edged UI cutouts, candid photos, blue/orange symbol tiles and tiny dark selection handles share top edges without device mockups. Recreate this collage with representative output cards and simple geometric tiles when rich media is unavailable.
- Ruled lists and a monumental sendoff carry the identity: 2px charcoal dividers organize capabilities and questions; a textured blue closing sheet pairs a compact collage with 93px cream type and an oversized link underlined by a 12px rule.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot orange | `#ff6a00` | `--color-orange` | surface, background, accent, border | Bright paid-plan block, symbol tiles and thick card feet. |
| Electric printed blue | `#3950e6` | `--color-blue` | background, surface, link, accent | Signature split panel, closing sheet and highlighted navigation link. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Control orange | `#ff773c` | `--color-control-orange` | action, surface | Composer send control and active billing selector. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button charcoal | `#312f2f` | `--color-button` | action, text, border | Default filled actions and outlined action edges. |
| Charcoal ink | `#1e1e24` | `--color-ink` | text, border, accent | Main headings, paragraphs, dividers and small selection handles. |
| Putty | `#e2ded7` | `--color-stone` | surface, background | Stepped proof blocks, product-media backing and deeper neutral section bands. |
| Warm gray paper | `#eeeceb` | `--color-canvas` | background, text | Default visible page canvas; also cream-colored type on blue. |
| Ivory sheet | `#f9f7f4` | `--color-card` | surface | Flat capability and utility cards above the slightly darker paper. |
| Clean white | `#ffffff` | `--color-white` | surface, background, text | Composer, free-plan cards, FAQ band, footer and reversed button labels; navigation uses this at 97% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and enterprise detail | Utility blue | `#3b51e5` | `--color-utility-blue` | background, surface | Enterprise ribbon and small tier badges. |
| pricing and trust pages | Pricing charcoal | `#232529` | `--color-pricing-ink` | action, text | Pricing-page full-width actions and secondary trust prose. |
| company storytelling | Printed gray | `#bdbdbd` | `--color-mission-gray` | surface | Textured company-statement panel beside orange. |
| extended product and trust chapters | Warm backing | `#f1ede7` | `--color-warm-band` | background, text | Warm backing behind atmospheric feature panels; alternate reversed text on product blue. |

## Typography

- **Dazzed** — Headlines, card titles, FAQ questions, section labels and navigation. A compact contemporary grotesk with open counters, assertive medium-heavy shapes and tightly joined headline spacing. If unavailable, use **Inter Tight**. Use 500 and 600; retain the negative tracking and compact line lengths. Font stack: "Dazzed", "Inter Tight", Arial, sans-serif.
- **Geist** — Supporting prose, captions, button labels, footer links and utility text. A crisp neutral sans that keeps practical explanations legible beneath the expressive display hierarchy. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Dazzed | 600 | 93.7px | 1.05 | -0.04em | fixed | Default centered opening promise. |
| panel-display | Dazzed | 600 | 93px | 0.92 | -0.04em | fixed | Short stacked statement on a blue split panel. |
| closing-display | Dazzed | 600 | 93px | 0.89 | -0.04em | fixed | Closing headline and equally monumental action link. |
| price-display | Dazzed | 600 | 84px | 1 | -0.03em | fixed | Large price numerals in the compact landing-page plan comparison. |
| heading | Dazzed | 600 | 57px | 1.05 | -0.04em | fixed | Default section headings. |
| faq-heading | Dazzed | 600 | 57px | 1.05 | -0.04em | fixed | Left-side FAQ title. |
| proof-value | Dazzed | 600 | 57px | 60px | -0.03em | size clamp(48px, 3.958vw, 76px), line height clamp(50px, 4.17vw, 80px) | Large values at the top of stepped proof cards. |
| quote | Dazzed | 600 | 57px | 60px | -0.03em | size clamp(43px, 3.958vw, 76px), line height clamp(46px, 4.17vw, 80px) | Customer quotation above the proof cards. |
| card-heading | Dazzed | 600 | 36px | 1.08 | -0.0208em | fixed | Main capability card titles and split-panel list titles. |
| feature-row | Dazzed | 600 | 36px | 1.46 | -0.0208em | fixed | Large single-line capability links. |
| editorial-lead | Dazzed | 600 | 36px | 1.083 | -0.0208em | fixed | A short display paragraph under a modest section label. |
| small-heading | Dazzed | 600 | 24px | 1.125 | -0.03em | fixed | Utility-card titles. |
| question | Dazzed | 600 | 24px | 1.25 | -0.03em | fixed | FAQ question text. |
| section-label | Dazzed | 500 | 24px | 1.125 | normal | fixed | Sentence-case introductory label above a larger paragraph; also compact pricing labels. |
| proof-label | Dazzed | 600 | 24px | 27px | -0.01em | size clamp(20px, 1.667vw, 32px), line height clamp(22px, 1.875vw, 36px) | Bottom-anchored context on proof cards. |
| attribution | Geist | 400 | 24px | 1.35 | -0.01em | size clamp(16px, 1.667vw, 32px) | Single-line name and role above the quotation. |
| hero-support | Geist | 400 | 21px | 1.39 | -0.01em | fixed | Centered opening support across two lines. |
| body | Geist | 400 | 18px | 1.25 | -0.01em | fixed | Default card descriptions and concise section support. |
| footer-link | Geist | 400 | 18px | 32px | normal | fixed | Footer navigation lists. |
| footer-title | Geist | 600 | 18px | 22px | normal | fixed | Footer column headings. |
| answer | Geist | 400 | 16px | 1.44 | normal | fixed | Expanded FAQ explanations. |
| small-body | Geist | 400 | 16px | 1.5 | normal | fixed | Footer product summary and compact explanations. |
| button | Geist | 500 | 16px | 1 | normal | fixed | Default 44px content action. |
| nav | Dazzed | 500 | 16px | 1.5 | normal | fixed | Navigation labels. |
| header-button | Geist | 600 | 16px | 1.3 | -0.0225em | fixed | Compact header action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling | company-display | Dazzed | 600 | 270px | 240px | -12px | fixed | Monumental two-line word sculpture with orange punctuation. |
| flagship product launches | campaign-display | Dazzed | 600 | 135px | 1 | -0.0433em | fixed | Two-line left-aligned headline with an inline symbol tile. |
| company storytelling | company-heading | Dazzed | 600 | 135px | 1 | -0.04em | fixed | Centered statement above a horizontal strip of symbols and portraits. |
| trust and security pages | trust-display | Dazzed | 600 | 95px | 0.96 | -0.04em | size clamp(40px, 6.6vw, 124px) | Two-line opening headline beside an editorial collage. |
| pricing pages | pricing-display | Dazzed | 600 | 87.9px | 1.06 | -0.033em | fixed | Centered pricing promise. |
| pricing pages | plan-price | Dazzed | 500 | 46px | 1 | normal | fixed | Numerals in full pricing cards. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use Dazzed for the confident voice and Geist for explanation; neither a serif nor a monospace is part of the marketing hierarchy.
- The 93.7px opening is less tightly led than the 93px closing. Preserve the closing's compressed 0.89 line height rather than normalizing all display text.
- Most major headlines use -0.04em tracking; smaller 36px titles relax to -0.0208em. Section labels remain sentence case and are unusually substantial at 24px.
- Keep intentional two-line or stacked headline shapes. Change wrapping with new copy rather than forcing a line break into a tiny last word.

## Layout

**Density:** Airy at section scale, compact within controls and explanatory lists; large flat panels provide the breathing room rather than ornamental gutters.

### Spacing

**Spacing system:**

- **control step** 8px — Declared control-spacing family of 8px, 16px, 24px, 32px, 48px and 64px; editorial layouts also use fluid values outside this family.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Tight control and icon gaps. | fixed |
| 12px | Small flex-group gaps. | fixed |
| 16px | Label-to-value spacing. | fixed |
| 24px | Control groups and gaps between stacked plan sheets. | fixed |
| 32px | Interior action and column spacing. | fixed |
| 48px | Larger introduction-to-control gaps. | fixed |
| 64px | Compact enterprise-ribbon vertical padding. | fixed |
| 22.5px | Capability-sheet padding and utility-card inset. | clamp(20px, 1.5625vw, 30px) |
| 30px | Default card inset. | clamp(30px, 2.083vw, 40px) |
| 33px | Ruled FAQ row vertical spacing. | clamp(28px, 2.29vw, 44px) |
| 67.5px | Main desktop editorial side margins. | min(4.6875vw, 90px) |
| 90px | Default major-section top and bottom breathing room. | fixed |
| 120px | White FAQ-band vertical breathing room. | fixed |

### Containers and grids

- **editorial container**: max width 1920px · side padding 67.5px. Default marketing container; at 1440px this leaves 1305px of working width. Full-bleed sheets may run outside it.
- **header container**: max width 1920px · gap 32px · side padding 40px. Fixed horizontal navigation, brand at left, language control and compact action at right.
- **capability grid**: 3 columns · gap 21px. Equal rectangular sheets across the page; titles sit at the top and descriptions/actions near the bottom.
- **editorial split**: 2 columns · gap 63px. A roughly two-fifths introduction faces a larger ruled list; blue chapters instead use nearly equal full-height halves.
- **utility grid**: 3 columns · gap 22px. Repeated integration, trust and workspace cards in even rows.
- **footer**: max width 1920px · 4 columns · gap 21.6px · side padding 90px. Four 210px navigation columns alongside a separate 317px summary column; copyright sits below the tallest list.
- **pricing grid** (only for pricing pages): 3 columns · gap 20px · side padding 70px. Five plan sheets form three in the first row and two in the second; do not stretch the last row to fill.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | content buttons and composer | 8px |
|  | sheets | 0px |
| product launch and trust pages | large product and trust buttons | 10px |
| pricing pages | pricing buttons | 11px |
| pricing pages | billing switch shell | 12px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing ground.

**CSS:** `background: #eeeceb; color: #1e1e24`

**Observed:** A very faint regular dot field overlays the warm gray; text and media remain unshadowed.

**Transfer:** Keep the dot field low contrast, present mainly in exposed space.

#### Ivory sheet · level 1

**Use:** Capability and utility cards.

**CSS:** `background: #f9f7f4; border-radius: 0px; box-shadow: none`

**Observed:** A flat rectangular sheet, not a floating card. Selected capability cards have a hot-orange bottom edge.

**Transfer:** Use color contrast and spacing rather than an outline or elevation to separate sheets.

#### White band · level 0

**Use:** FAQ and footer; white card variant for a free offering.

**CSS:** `background: #ffffff`

**Observed:** A clean, untextured reset after paper and saturated panels.

**Transfer:** Give explanatory and navigational endings this clean ground.

#### Putty block · level 1

**Use:** Quantified proof and product-media backing.

**CSS:** `background: #e2ded7; border-radius: 0px`

**Observed:** Slightly darker than the canvas, with no border or shadow.

**Transfer:** Use for structural blocks that need visible mass without bright color.

#### Printed blue · level 0

**Use:** Full-bleed sendoff and emphatic split-panel statement.

**CSS:** `background: #3950e6; color: #eeeceb; position: relative; overflow: hidden`

**Observed:** A dense, irregular woven/halftone texture overlays the blue at 0.55 opacity using overlay blending; it is tactile rather than glossy.

**Transfer:** Keep text crisp above the texture; recreate the ink grain with the printed-material recipe.

#### Orange sheet · level 1

**Use:** Paid-plan spotlight and compact symbol artwork.

**CSS:** `background: #ff6a00; color: #1e1e24; border-radius: 0px`

**Observed:** Black text remains on orange; orange is not reserved for buttons.

**Transfer:** Use one selected proof or commercial sheet to punctuate neutral runs.

#### Atmospheric backing · level 0

**Use:** Broad supporting band behind cards or an inset ruled feature sheet.

**CSS:** `background: #f1ede7; position: relative; overflow: hidden`

**Observed:** Out-of-focus organic color masses in olive, cream, rust and near-black are heavily grained, with the reading surface opaque above them.

**Transfer:** Make soft material-like color fields rather than a crisp multicolor UI gradient; exact stops are not essential.

#### Company gray sheet · level 1

**Only for:** company storytelling

**Use:** Second statement panel beside orange.

**CSS:** `background: #bdbdbd; color: #1e1e24; border-radius: 0px`

**Observed:** The gray sheet is shorter and bottom-aligned with the orange sheet, both with printed grain.

**Transfer:** Use unequal heights for two related statements rather than two identical corporate cards.

## Components

### Fixed navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 86px; z-index: 50; background: rgba(255, 255, 255, 0.97)`

**Text style:** `nav` — Dazzed 500 · 16px/1.5

**Observed:** Brand at left, sentence-case links with small down chevrons, a blue highlighted product link flanked by tiny square marks, then language and compact action at the right. Over the opening, the navigation visually blends into the paper; lower sections read as white.

**Transfer:** Keep labels short and navigation visually much smaller than the opening statement.

### Primary button

**Use:** Default content conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 22px; background: #312f2f; color: #ffffff; border: 1px solid transparent; border-radius: 8px; overflow: hidden`

**Text style:** `button` — Geist 500 · 16px/1

**Observed:** A compact content-width rectangle. Larger launch and trust actions use 50px height, 26px side padding and 10px corners; the reversed variant on blue is white with dark text.

**States:** Declared: hover not specified for the default content action; focus-visible outline 2px solid #1e1e24, outline-offset 4px, border-radius 6px.

### Header action

**Use:** Persistent compact conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 38px; padding: 0px 15px; background: #312f2f; color: #ffffff; border-radius: 8px; overflow: hidden`

**Text style:** `header-button` — Geist 600 · 16px/1.3 · tracking -0.0225em

**Observed:** Label sits inside an overflow-hidden slot with a second copy for vertical rollover.

**States:** Declared: hover background-color rgb(67 63 63 / 1); focus-visible outline 2px solid #1e1e24 with 4px offset and 6px radius.

### Opening composer

**Use:** Tangible main object and immediate product entry point.

**CSS:** `display: flex; flex-direction: column; width: 555px; height: 150px; background: #ffffff; border-radius: 8px`

**Text style:** `small-body` — Geist 400 · 16px/1.5

**Observed:** A text-entry area occupies the top; plus control anchors the lower left, mode selector, microphone and orange 40px send square sit along the lower right. No strong border or shadow.

**Transfer:** For a non-conversational product, use an equally simple live search, configurator or representative output card rather than a fake chat requirement.

### Capability sheet

**Use:** Compare possible outcomes or major capabilities.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #f9f7f4; border-bottom: 10px solid #ff6a00; border-radius: 0px; padding: 22.5px 22.5px 31.5px`

**Text style:** `card-heading` — Dazzed 600 · 36px/1.08 · tracking -0.0208em

**Observed:** Title occupies the top corner, practical explanation and Primary button form a lower group. Three equal sheets share a baseline.

**Transfer:** Retain the open vertical interval between title and explanation without adding decorative placeholder media.

### Ruled capability link

**Use:** A compact catalogue of concrete benefits.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; color: #1e1e24`

**Text style:** `feature-row` — Dazzed 600 · 36px/1.46 · tracking -0.0208em

**Observed:** Large text faces a circled right arrow at the far edge. Rows are separated by 2px charcoal rules, not enclosed in individual boxes.

**Transfer:** Use for five or six short, distinct benefits; add descriptions only in the expanded chapter variant.

### Utility sheet

**Use:** Linked supporting capabilities over atmospheric backing.

**CSS:** `display: flex; flex-direction: column; background: #f9f7f4; padding: 22.5px; border-radius: 0px`

**Text style:** `small-heading` — Dazzed 600 · 24px/1.125 · tracking -0.03em

**Observed:** Title at top, prose low in the sheet, small solid dark circle containing a diagonal arrow at bottom left. The linked sheet is about 435×461px in the three-column treatment.

**Transfer:** Use the low-anchored explanation as a deliberate typographic composition, not a space to fill with arbitrary icons.

### Stepped proof block

**Use:** A small set of verified outcomes.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #e2ded7; padding: 30px 30px 26.3px; border-radius: 0px`

**Text style:** `proof-value` — Dazzed 600 · 57px/60px · tracking -0.03em

**Observed:** Three equal-width blocks have descending heights and a shared lower baseline; value at top, proof-label at bottom. Quote and attribution sit above, portrait at the outer right.

**Transfer:** Use genuine outcomes; if numbers are unavailable, use concise milestones without inventing metrics.

### FAQ row

**Use:** Objection handling in a clean white band.

**CSS:** `border-top: 2px solid #1e1e24; padding-bottom: 33px; color: #1e1e24`

**Text style:** `question` — Dazzed 600 · 24px/1.25 · tracking -0.03em

**Observed:** Question button has 33px top padding and a far-right circled downward arrow; the first answer is expanded with the arrow pointing up. Answer uses the answer recipe, inset from the arrow column.

**States:** Declared: hover not specified; focus-visible outline 2px solid #1e1e24, 4px offset and 6px radius.

### Closing action

**Use:** Oversized final conversion beneath the collage.

**CSS:** `color: #eeeceb; border-bottom: 12px solid currentColor; padding-bottom: 6.2px; position: relative`

**Text style:** `closing-display` — Dazzed 600 · 93px/0.89 · tracking -0.04em

**Observed:** An outlined circular right arrow sits just left of the immense underlined phrase. This is a text link, not a filled button.

**Transfer:** Keep the action phrase brief enough to retain headline scale.

### Footer column

**Use:** Secondary navigation after the blue sendoff.

**CSS:** `color: #1e1e24; width: 210px`

**Text style:** `footer-link` — Geist 400 · 18px/32px

**Observed:** A footer-title sits above a list with 32px line rhythm. Four columns accompany a separate brand summary with social icons, and copyright sits low on the white band.

**Transfer:** Let the longest list set the column group's height instead of vertically centering shorter lists.

### Plan sheet

**Only for:** pricing pages

**Use:** Detailed commercial comparison.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; padding: 30px 20px; border-radius: 0px; gap: 21px`

**Text style:** `plan-price` — Dazzed 500 · 46px/1

**Observed:** Title and short description precede price and billing note, two ruled credit rows, a full-width 50px charcoal action with 11px corners, then compact checkmarked features. One tier gets a small blue Popular badge; the card itself stays white.

**Transfer:** Use the same order and compact rows for real entitlements; keep the lower row left-aligned in the grid.

## Imagery and graphics

### Workbench collage

**Use:** Opening proof strip, editorial product scenes and closing collage.

**Observed:** Cropped interfaces, simple symbol tiles and warmly lit candid portraits are assembled as flat rectangular cutouts. Different aspect ratios share top edges; tiny charcoal squares evoke active design-selection handles. Opening output strip spans almost the page width; closing collage is only about 680px wide between large text lines.

**Transfer:** Combine your own output examples with people using the product. If full interfaces are unavailable, compose readable mini charts, a small results table and a geometric symbol, never a row of generic empty cards.

**Build:** Arrange 5–7 SVG or image rectangles in a horizontal flex strip with narrow gaps and unequal heights. Add 7–8px charcoal square handles at selected top corners. Include one orange chart, one blue symbol tile and one people photo; leave backgrounds flat and edges square. Clip the wide strip at page edges rather than shrinking every detail to fit.

### Printed material

**Use:** Blue/orange panels and symbol tiles.

**Observed:** Ink appears on coarse woven paper with dense irregular halftone, slight mottling and no glossy specular highlight. The blue remains saturated beneath the grain.

**Transfer:** Use a procedural grain overlay that suggests printed fabric or risograph paper while leaving text untouched.

**Build:** Place a monochrome SVG feTurbulence texture above the flat fill, combine fine fractal noise with a slightly rotated repeating 1px dot/line pattern, and set mix-blend-mode: overlay with opacity 0.55. Keep the overlay below text and imagery. On orange use the same print treatment; do not add a bevel.

### Organic blurred field

**Use:** Backing behind the utility-card row and inset feature chapters.

**Observed:** Cream, olive and rusty brown fields blend like an extremely defocused photograph, with a darker central or lower mass and conspicuous grain. Opaque paper cards cover most of the field.

**Transfer:** Create a warm, earthy field even for a technical product; the color is material scenery, not semantic chart color.

**Build:** On the warm backing, layer 3–4 oversized elliptical radial gradients using rgba(92,110,42,0.65), rgba(151,82,48,0.65), rgba(30,30,36,0.8) and transparent edges. Blur the field 60px and scale beyond its container to hide blur edges. Add an overlay noise texture at 0.6 opacity. Cover the central reading area with an opaque paper sheet or three ivory cards.

### People and product cutouts

**Use:** Trust chapters, customer proof and closing collage.

**Observed:** Natural-light studio, café and event photographs show people working or talking, not posed corporate headshots. Rectangular photos overlap or abut small vivid interfaces; portrait treatment stays natural in color.

**Transfer:** Use authentic contextual people photography with cream and plant-green surroundings; pair it with a real relevant product fragment, not a glowing device render.

### Inline launch symbol

**Only for:** flagship product launches

**Use:** An interruption inside the oversized opening headline and a small central product interlude.

**Observed:** An orange square with a simple light abstract mascot interrupts words, with dark corner handles. A later scene places a small monochrome animated symbol between short text fragments.

**Transfer:** Create an original compact silhouette or geometric monogram with the same blocky readability; keep the motif product-specific.

**Build:** Use a 110–125px square inline tile at desktop headline scale. Draw a single high-contrast SVG silhouette on orange; place charcoal handles just outside opposing corners. For the interlude remove the tile and show the dark silhouette alone.

### Company history cards

**Only for:** company storytelling

**Use:** Narrative pause between company statements and operating principles.

**Observed:** A narrow 336×446px printed blue or orange card sits between large parentheses, with a short topic label to the left and a compact conviction statement to the right. A small portrait precedes one card's prose.

**Transfer:** Treat a pivotal story as one physical card at a time, not a timeline of miniature logos.

**Build:** Center a square-edged portrait-format card on paper. Set two large charcoal parentheses outside it, keep side captions vertically near its midpoint, and switch between blue with cream text and orange with dark text.

### Icons

**Observed:** Circled arrows are the recurring navigation language: approximately 43px for major rows and 34px for FAQ controls; social/language symbols are 24px. Most icons are solid dark SVG silhouettes or an outlined circle containing a simple arrow. Trust cards also use 44px outline symbols with roughly 1.6–1.9px strokes.

**Transfer:** Use one consistent circled-arrow family for rightward movement, downward expansion and upward collapse. Keep brand/product logos confined to relevant integration or collage content.

## Section recipes

How recurring sections are built.

### First screen: Workbench opening

**Observed:** A paper-and-faint-dot canvas fills the first 900px. Fixed navigation occupies an 86px strip above a centered, nearly full-width single-line display headline beginning around 135px from the top. Its 93.7px type spans about four-fifths of the width; a 21px two-line support paragraph sits 30px below, constrained to 727px. The white Opening composer follows with another 30px gap. Category text sits below the composer, then a wide irregular strip of output cutouts with black corner handles fills the lower third. All of headline, support, composer controls, category labels and output strip are visible within the first screen; the first capability chapter starts below 900px. Back-to-front layers are paper, faint dots, text/composer, then cutout media and their tiny handles.

**Transfer:** Keep the centered promise → usable object → low collage composition for an ordinary marketing opening. Replace the composer with a real simple interaction or output preview when conversation is not the product. Launch variants use a left-aligned 135px two-line statement with inline symbol and a large demo to the lower right; trust variants put a 95px left headline beside a people-and-product collage. Pricing opens with centered 88px type and billing switch above the plan grid. Company storytelling uses a 270px word sculpture with orange punctuation and two separated supporting captions.

**Avoid:** Do not turn this into a standard left-copy/right-laptop hero, add a gradient headline, or place the product object so low that only its top edge appears in the first screen.

**Text style:** `display` — Dazzed 600 · 93.7px/1.05 · tracking -0.04em

### Heading and ruled list

**Observed:** Within the editorial container, a 57px heading and 18px explanation occupy the smaller left column. The larger right column holds Ruled capability links with circled arrows; a small blue symbol and candid-photo tile can anchor the space below the introduction. Default section top breathing room is 90px.

**Transfer:** Explain one promise at left, then expose the specific mechanisms at right. Use the ruled structure for dense practical content rather than expanding everything into cards.

**Text style:** `heading` — Dazzed 600 · 57px/1.05 · tracking -0.04em

### Outcome sheets

**Observed:** A left-aligned heading and one-line support precede three Capability sheets. Their 36px titles sit high, with a long vertical interval before compact prose and the action near the bottom. A 10px orange foot ties the three sheets together.

**Transfer:** Choose three distinct outcomes or audiences; preserve the equal sheet scale and strong colored baseline.

**Text style:** `card-heading` — Dazzed 600 · 36px/1.08 · tracking -0.0208em

### Printed split chapter

**Observed:** Printed blue fills roughly half the width with a 93px compressed, stacked cream statement and a smaller explanation. The paper half contains four large title/description pairs divided by charcoal rules and marked with circular arrows. Both halves share section height.

**Transfer:** Pair one emotional product promise with concrete capabilities. For an illustrated product chapter, the second half can become a putty-backed collage and the blue half can carry a white action.

**Text style:** `panel-display` — Dazzed 600 · 93px/0.92 · tracking -0.04em

### Label and atmospheric cards

**Observed:** A 24px sentence-case section-label introduces a 36px editorial-lead constrained to about 800px. A full-width organic blurred field follows, holding three Utility sheets with about 20px gaps and ample inset around the group.

**Transfer:** Use this lower-key heading relationship when the explanation itself carries the message; keep scenery behind opaque sheets, never under body text.

**Text style:** `editorial-lead` — Dazzed 600 · 36px/1.083 · tracking -0.0208em

### Customer proof staircase

**Observed:** Attribution comes before the 57px quote; a small rectangular portrait occupies the far right. Below, three Stepped proof blocks share a bottom edge but step down in height from left to right. Values sit at upper left and captions along the bottom; the story link occupies the open right-side space above shorter blocks.

**Transfer:** Use two or three genuinely different outcomes, preserving the stepped silhouette even if the new facts are milestones rather than numeric claims.

**Text style:** `quote` — Dazzed 600 · 57px/60px · tracking -0.03em

### Compact commercial fork

**Observed:** A 93px two-line section heading at left faces two horizontal offer sheets stacked at right: white first, hot orange second. Each pairs a large price/action group with a compact entitlement list. A short sales link sits below.

**Transfer:** Summarize entry and expansion paths without reproducing a full comparison table. Dedicated pricing uses Plan sheets, a blue enterprise ribbon, then a narrow ruled inclusion sheet over atmospheric backing.

**Text style:** `price-display` — Dazzed 600 · 84px/1 · tracking -0.03em

### Split FAQ band

**Observed:** White band with 120px vertical breathing room. The 57px heading occupies the left third and remains sticky on wide layouts; the right column is approximately 712px wide and contains FAQ rows. First answer is shown expanded, remaining questions are separated by clear rules.

**Transfer:** Put the reader's actual objections into short questions and useful prose answers; retain the asymmetry instead of centering a narrow accordion.

**Text style:** `faq-heading` — Dazzed 600 · 57px/1.05 · tracking -0.04em

### Printed sendoff and white footer

**Observed:** A 634px-tall Printed blue sheet centers a compressed two-line headline, a narrow Workbench collage and the Closing action. About 43px gaps separate these elements. The following white footer has 90px insets, product summary/social block at left, four top-aligned navigation columns at right and copyright below. All page types use this same strong ending with context-specific invitation text.

**Transfer:** Include this unmistakable closing device on a new page: a brief invitation, your own output-and-people collage and a monumental underlined action. If photography is unavailable, use original output fragments and textured symbol tiles, preserving the strip's varied heights.

**Text style:** `closing-display` — Dazzed 600 · 93px/0.89 · tracking -0.04em

### Inset practice sheet

**Only for:** extended product and trust chapters

**Observed:** An earthy blurred-and-grained full-width backing surrounds an opaque paper panel. A large heading leads a three-column grid of short chapters, each beginning with a 2px charcoal top rule. Launch versions use six compact items with tiny visual labels; trust versions use nine longer text items.

**Transfer:** Keep the outer material visible as a frame and let the inner opaque paper carry complex explanations.

### Trust and administration chapters

**Only for:** trust and security pages

**Observed:** Three ivory credential cards pair title and seal at top with description and dark action below. A putty band later holds a three-column workspace-card grid. The long governance chapter pairs a ruled left text stack and blue tier badges with a tall orange-backed product collage at right.

**Transfer:** Separate credentials, user-level controls and organizational controls into distinct compositions. Use seals only for real credentials and let detailed chapters become denser than the opening.

### Company editorial pauses

**Only for:** company storytelling

**Observed:** Unequal orange and gray statement sheets share a lower edge; history becomes a centered card inside parentheses rather than a conventional timeline. A later 135px centered headline sits above five widely separated tiny photo/symbol tiles, three compact prose columns and an oversized arrow link. A putty community chapter pairs a 93px invitation with a small collage and two large text links.

**Transfer:** Use these treatments for identity, origin and participation stories; their word-sculpture scale and staged pauses should not become the default feature-page layout.

## Page flow

**Storyline:** Promise → tangible product/output → concrete capability chapters → credible proof or commercial clarity → objections → printed invitation → practical navigation.

### Broad marketing landing page

1. **Promise and entry** — Centered statement, usable composer and wide cutout output strip.
2. **Capability chapters** — Ruled benefits, outcome sheets, a blue split statement and atmospheric utility cards.
3. **Quantified proof** — Customer quotation, portrait and stepped outcome blocks.
4. **Commercial clarity** — White/orange offer pair rather than a full table.
5. **Objection handling** — Split white FAQ.
6. **Closing call and navigation** — Textured blue invitation, collage, monumental underlined link, then white five-part footer.

**Transfer:** Move among benefits, output and proof with changes in composition; adapt the number of chapters to the product.

### Flagship product launch

1. **Product promise** — Huge left headline interrupted by a symbol, support/actions and an adjacent demo.
2. **Use cases** — Horizontal carousel of colored demo tiles with conversational task examples.
3. **Mechanisms** — Inset ruled feature grid over earthy texture, then a small symbol interlude.
4. **Ecosystem proof** — Three-column integration tiles with logos at the far edge.
5. **Product demonstration** — Blue split chapter beside a chat/output collage.
6. **Objections and closing** — White FAQ, printed blue invitation with product-specific action, shared white footer.

**Transfer:** Keep launch symbolism and demos grounded in real tasks, not abstract AI spectacle.

### Technical reassurance and enterprise evaluation

1. **Reassurance** — Left promise and two actions beside a people/product collage.
2. **Credential proof** — Three seal-bearing ivory cards.
3. **User agency** — Ruled data-control list.
4. **Process assurance** — Inset multi-column practice sheet over earthy texture, followed by partner-directory cards.
5. **Control detail** — Product-control accordion, putty workspace grid and long orange-backed governance split.
6. **Review objections** — Targeted security-review questions and a trust link.
7. **Closing call and navigation** — Context-specific blue invitation, shared collage, oversized action and white footer.

**Transfer:** Let practical controls and verifiable documentation provide reassurance; preserve compositional variety in a long technical page.

### Plan selection and purchase confidence

1. **Commercial promise** — Centered headline, low-friction support and orange-active billing switch.
2. **Plan comparison** — Three-column white sheet grid, with the remaining two tiers left-aligned below.
3. **Higher-touch path** — Short blue enterprise ribbon and reversed action.
4. **Shared value** — Narrow paper inclusion list on earthy full-bleed backing.
5. **Objections** — Split white FAQ on ownership, usage and billing.
6. **Closing call and navigation** — Printed blue invitation and monumental link, followed by white footer.

**Transfer:** Keep entry and expansion easy to understand, with real billing terms and a visible path for custom needs.

### Company identity and participation

1. **Identity** — Oversized word sculpture with orange punctuation and separated supporting captions.
2. **Definition and purpose** — Unequal orange and gray printed sheets.
3. **Origin story** — One narrative card at a time between parentheses with side captions.
4. **Operating character** — Huge centered heading, tiny media strip and short prose columns.
5. **Participation** — Putty invitation chapter, photo/symbol collage and large community links.
6. **Closing call and navigation** — Question-led blue invitation, collage, monumental action and shared white footer.

**Transfer:** Borrow the editorial staging for your own origin and participation story rather than importing the company-specific narrative.

## Writing

Confident, practical and encouraging, with a maker's impatience for unnecessary setup. Warmth comes from plain speech and useful detail, not exuberant hype.

**Do not copy:** Do not reuse Base44/Wix names, logos, proprietary artwork, customer identities or quotations, prices, growth numbers, certifications or product-performance claims. Replace all examples with substantiated facts and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. The product speaks by name or as we when describing commitments; headlines often invite action directly.
- **Rhythm:** Headlines are usually 4–9 words, often split into two clipped clauses. Support can be one practical sentence or a short two-sentence promise; longer paragraphs enumerate concrete mechanisms. Contractions, em dashes and blunt fragments are common; exclamation marks are not the source of energy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct, broadly human statement that makes the product feel like a foundation. | 5–9 words | “Every builder needs a base”<br>“Security you can build on” |
| Section heading | Outcome followed by friction removed, or a compact expression of reader control. | 4–9 words | “The whole stack. No setup slowdown.”<br>“Your data, your rules” |
| Support | Name the real task and the benefit; use concrete nouns before abstract claims. | 15–40 words | “Create a new Superagent, start a conversation and describe what you want it to do.”<br>“Start for free. Upgrade when you're ready.” |
| Feature explanation | Short actions describe what happens, then explain what work the reader no longer needs to do. | 20–45 words | “Ask for design options, pick the one you want. AI shows previews before it touches anything.” |
| Primary action | An active verb plus a small object, not a promotional slogan. | 2–4 words | “Start building”<br>“Visit Trust Center” |
| Closing invitation | A short permission-giving statement or direct question, followed by a brief action. | 4–7 words | “Go ahead. Build it yourself.”<br>“So, what are you building?” |

**Words and phrasing to use:** build; your own; already; built in; get things done; ready; real; no setup; start; keep going

**Avoid:** revolutionary synergy; unleash limitless potential; best-in-class ecosystem; effortless magic; future-proof everything

**Rules:**

- Lead with what the reader can make or accomplish, then explain the mechanism.
- List removed chores in short parallel fragments when this is factually justified.
- Use technical specifics in trust copy, but explain their practical consequence.
- Write labels and questions in sentence case; don't convert the voice to uppercase equipment labels.
- Keep pricing encouragement low pressure and reversible rather than urgent.
- Make the final invitation sound like permission to begin, not a scarcity pitch.

## Do's and Don'ts

### Do

- Use the 93.7px/1.05 opening recipe and keep its supporting line constrained to about 727px.
- Give ordinary section leads the 57px Dazzed 600 treatment, not the company-only 270px scale.
- Keep major reading margins near 67.5px at desktop, with 90px section breathing room.
- Construct rectangular sheets with square corners and no shadow; reserve 8px rounding for controls and composer.
- Use 2px charcoal rules and circled arrows to make long feature lists feel tangible.
- Anchor proof captions at the bottom of stepped putty blocks, leaving the values at the top.
- Carry grain into blue and orange artwork while keeping text on a crisp upper layer.
- Finish with the textured blue collage-and-link device and a clean white multi-column footer.

### Don't

- Don't make every button orange: the ordinary action is #312f2f with white text.
- Don't round large content sheets to 16px or 24px; that erases the cut-paper construction.
- Don't replace the negative headline tracking with loose geometric-sans spacing.
- Don't use glass cards, drop shadows or glowing borders to simulate depth; the depth comes from opaque overlap.
- Don't tint the entire page blue; neutral paper should dominate between emphatic printed sheets.
- Don't turn the 12px-underlined closing link into a conventional 44px CTA button.
- Don't apply the 135px launch headline or 270px company word sculpture to ordinary feature chapters.
- Don't put grain or earthy gradient color directly behind small explanatory text without an opaque reading sheet.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions include color, background-color, border-color and opacity at 0.16s.
- Header label rollover uses a vertical duplicate-label strip with a 0.2s ease-out transform on wide screens.
- FAQ uses a 400ms grid-row expansion and a separate 300ms ease-out answer-opacity transition; reduced-motion overrides are declared.
- Printed texture jitter is declared at 0.9s steps(1), and the closing cut-in uses 0.16s steps(1,end). A horizontal sub-strip loop is declared at 55s linear.

**Transfer:**

- Use the clipped label-roll treatment on compact header conversion rather than scaling the whole button.
- Keep texture movement discrete and subordinate to legible stationary text; retain reduced-motion alternatives.

**Unknown:**

- The full choreography, playback triggers and timing of product videos and staged company graphics are not established.

### Responsive

**Observed:**

- Wide editorial splits change at declared 1100px rules; intermediate styles use 768px rules. The full horizontal navigation is shown from 1431px.
- The trust opening size is clamp(40px, 6.6vw, 124px). Main editorial margins use min(4.6875vw, 90px).
- Classes declare single-column capability cards at narrow widths and three columns at wide widths; some intermediate utility cards use horizontal strips.

**Transfer:**

- As design guidance, stack introduction above ruled content on narrow screens; preserve the blue printed sendoff, square media cutouts and compact button geometry.
- Let the opening strip clip or scroll horizontally instead of reducing every output fragment to unreadable miniatures.
- Use the declared fluid recipes where provided; rewrap giant company or launch statements rather than copying desktop line breaks.

**Unknown:**

- Mobile viewport appearance, navigation menu behavior and exact stacked spacing were not visually verified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
