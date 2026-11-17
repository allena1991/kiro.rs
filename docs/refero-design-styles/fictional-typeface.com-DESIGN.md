# Fictional — comic sticker playground

## Overview

An exuberant, light-backed style that feels like a cartoon poster turned into an interactive toy. Cream, violet, tomato, electric green and yellow surround a friendly, irregular sans serif, with huge black lettering and flat comic graphics instead of photography. It suits expressive creative products and playful consumer launches, balancing dense demonstrations with simple, oversized statements.

### Essentials

- The opening is a sticker-covered poster, not a conventional hero: a 1400×860px cream stage inside 20px white gutters, a centered 201.6px product name and rotated speech bubbles, circles and explosive stars.
- Letterforms carry the personality: Fictional at weight 400, normal tracking and 1.2 line height for the main display; rounded, uneven shapes replace a neutral grotesk.
- Color fills whole objects and whole proof panels: cream dominates the opening, while violet, yellow, tomato and green occupy most of the lower page; white is primarily the 20px separating gutter and speech-bubble fill.
- Actions are part of the collage: 144px round badges, 10px-radius tilted labels and a giant yellow starburst with a 72px blue two-line action replace a standard pill-button hierarchy.
- Product proof behaves like a toy: a saturated two-card comparison, a simple slider and a dense selection field paired with a monumental enlarged detail; use selectable symbols or product variants when literal glyphs are inappropriate.
- The ending remains loud before becoming tiny: a green two-thirds-width contact panel with 47.5px centered prose and underlined links meets an overlapping yellow purchase burst, followed by a 16px gray two-line credit footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#ffe9ce` | `--color-cream` | background | The broad opening poster backing. |
| Toy violet | `#8a53ff` | `--color-violet` | surface, accent | Proof card and round announcement or scroll stickers. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Comic tomato | `#fd4b38` | `--color-tomato` | surface, accent | Interactive proof field, comic burst and rectangular trial label. |
| Electric green | `#3ccb09` | `--color-green` | surface, accent | Closing contact panel, novelty badge and short fact label. |
| Burst yellow | `#ffd80c` | `--color-yellow` | surface, accent | Explanatory proof card and explosive comic action graphics. |
| Ultramarine lettering | `#0500a3` | `--color-blue` | text, action | Short shouts and purchase lettering on yellow bursts. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Outer gutters, speech bubbles and reversed text on saturated panels. |
| Credit underline | `#cccccc` | `--color-rule` | border | Thin borders beneath footer links. |
| Credit gray | `#666666` | `--color-muted` | text | Small footer credits and utility links. |
| Black ink | `#000000` | `--color-ink` | text | Primary lettering on cream, green and yellow. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| interactive selection demonstrations | Selected detail yellow | `#fbd70c` | `--color-selection` | border | Outline-like ring around the active demonstration cell. |

## Typography

- **Fictional** — All marketing lettering, from monumental name to footer credits. Friendly irregular sans serif with rounded bowls, open counters and cartoon-like terminals; apparent stroke weight can vary across live specimens. If unavailable, use **DynaPuff**. Use regular weight for copy; tune width before fitting the oversized name. Font stack: "Fictional", "DynaPuff", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Fictional | 400 | 201.6px | 1.2 | normal | fixed | Single centered product name in the opening poster. |
| burst-action | Fictional | 400 | 72px | 0.9 | normal | size 5vw | Compact two-line purchase action inside the closing starburst. |
| closing | Fictional | 400 | 47.5px | 1.1 | normal | size 3.3vw | Closing contact prose and inline destination links. |
| body-feature | Fictional | 400 | 37.4px | 1.3 | normal | size 2.6vw | Large centered explanatory paragraphs in the yellow proof card. |
| speech | Fictional | 400 | 36px | 1.2 | normal | fixed | Short supporting clauses in white speech bubbles. |
| badge | Fictional | 400 | 36px | 1 | normal | size 2.5vw | Two-line announcement in a circular sticker. |
| scroll | Fictional | 400 | 28.8px | 1 | normal | size 2vw | Lowercase scroll instruction with a simple down arrow. |
| label | Fictional | 400 | 21.6px | 1.2 | normal, uppercase | size 1.5vw | Compact facts and availability labels on tilted rectangles. |
| credit | Fictional | 400 | 16px | 1.4 | normal | fixed | Two lines of understated credits and utility links at the end. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| interactive selection demonstrations | detail | Fictional | 400 | 345.6px | 1.2 | normal | fixed | Single enlarged white character or symbol beside a selection field. |
| interactive product comparisons | specimen-row | Fictional | 400 | 50.4px | 1.714 | normal | size 3.5vw | Large selectable product specimen rows. |
| interactive selection demonstrations | cell | Fictional | 400 | 21.6px | 1.667 | normal | fixed | Dense selectable symbols on the tomato demonstration. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the main hierarchy in one expressive family rather than adding an editorial serif or mono accent.
- Normal tracking is the rule, including the giant name; personality comes from outlines, size and object rotation rather than letter spacing.
- There is no recurring eyebrow-and-heading hierarchy: the opening name, oversized explanatory paragraphs and enlarged product detail each lead their own block.
- The specimen rows visibly demonstrate progressively heavier appearances; this is product behavior, not a requirement to bold ordinary marketing copy.

## Layout

**Density:** Comfortable inside panels, dense inside the interactive selection field; narrow white gutters hold together a very colorful poster-like composition.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 20px | Page edge padding and gaps between major panels. | fixed |
| 11.5px | Vertical inset of small rectangular stickers. | 0.8vw |
| 28.8px | Sticker horizontal padding, speech vertical padding and selection-panel inset. | 2vw |
| 43.2px | Speech-bubble horizontal padding and closing bottom padding. | 3vw |
| 57.6px | Specimen-card padding and closing top padding. | 4vw |
| 60.5px | Yellow explanation card vertical padding. | 4.2vw |
| 31.7px | Yellow explanation card side padding. | 2.2vw |
| 108px | Closing green panel side padding. | 7.5vw |
| 22.4px | Additional separation before the credit footer. | fixed |

### Containers and grids

- **page-grid**: 12 columns · gap 20px · side padding 20px. Fluid full-width white frame. Full-width stages span all columns; proof cards each span six; closing information spans eight with a burst in the remaining four. No fixed maximum width.
- **proof-pair**: 2 columns · gap 20px. Equal 690px-wide, 559px-high cards at a 1440px viewport.
- **selection-split**: 12 columns · gap 0px. Tomato field divides eight columns of compact options from four columns of enlarged detail.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | major panels | 15px |
|  | rectangular stickers | 10px |
|  | speech bubbles | 144px |
|  | round stickers | 50% |
| interactive selection demonstrations | selection cells | 5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| interactive selection demonstrations | selection ring | `0px 0px 0px 2px #fbd70c` | Marks the active option without introducing panel depth. |

### Surfaces

#### White frame · level 0

**Use:** Unifying page canvas and gutters.

**CSS:** `background: #ffffff; padding: 20px; display: grid; grid-template-columns: repeat(12, 1fr); gap: 20px`

**Observed:** Colorful panels sit directly on the paper without shadows.

**Transfer:** Keep white visible as narrow seams rather than expanding it into large empty content sections.

#### Cream poster · level 1

**Use:** Opening collage stage.

**CSS:** `background: #ffe9ce; border-radius: 15px; position: relative`

**Observed:** A single warm backing carries black lettering and overlapping flat stickers.

**Transfer:** Use as a controlled theater for the main product identity.

#### Saturated panel · level 1

**Use:** Product proof and conversion blocks.

**CSS:** `background: #8a53ff; border-radius: 15px; box-shadow: none`

**Observed:** Violet supports white specimens; yellow supports black explanatory copy; tomato supports white selectable details; green supports black contact prose.

**Transfer:** Assign one flat color per major block, preserving the clear complementary pairings.

## Components

### Speech bubble

**Use:** Conversational product descriptor in the opening collage.

**CSS:** `background: #ffffff; color: #000000; border-radius: 144px; padding: 28.8px 43.2px`

**Text style:** `speech` — Fictional 400 · 36px/1.2

**Observed:** A wide rounded body has a small triangular speech tail; two bubbles tilt in opposite directions around the central name.

**Transfer:** Split a brief promise into two clauses and stage each as its own sticker.

### Round announcement

**Use:** Short launch message within the poster.

**CSS:** `background: #8a53ff; color: #ffffff; border-radius: 50%; width: 144px; height: 144px; padding-top: 36px; text-align: center`

**Text style:** `badge` — Fictional 400 · 36px/1

**Observed:** Lettering is tilted within a circle. The green novelty variant uses a single larger line; another violet circle contains a lowercase scroll cue.

**Transfer:** Use circles for a tiny number of high-energy annotations, not for every feature.

### Fact sticker

**Use:** Short factual or availability annotation.

**CSS:** `background: #3ccb09; color: #000000; border-radius: 10px; padding: 11.5px 28.8px; transform: rotate(10deg)`

**Text style:** `label` — Fictional 400 · 21.6px/1.2 · uppercase

**Observed:** A compact rectangle hangs near the main name; the longer tomato availability variant leans the other way.

**Transfer:** Choose a verifiable short fact and keep it to one line.

### Explanatory proof card

**Use:** Product personality and practical context in a bright block.

**CSS:** `background: #ffd80c; color: #000000; border-radius: 15px; padding: 60.5px 31.7px; text-align: center`

**Text style:** `body-feature` — Fictional 400 · 37.4px/1.3

**Observed:** Two centered paragraphs sit above a sparse black range control: a thin horizontal track and a large circular thumb.

**Transfer:** Keep the copy to two compact thought units; make the control change a meaningful product property.

### Conversational inline link

**Use:** Primary destination and contact action inside closing prose.

**CSS:** `color: #000000; text-decoration: underline`

**Text style:** `closing` — Fictional 400 · 47.5px/1.1

**Observed:** Link text remains part of a full centered sentence rather than a separate button row.

**States:** Declared: hover background #ffffff, border-radius 40px, text-decoration none.

**Transfer:** Let the surrounding sentence explain the next step.

### Purchase burst

**Use:** Monumental conversion action beside the closing panel.

**CSS:** `color: #0500a3; position: relative; transform: rotate(20deg)`

**Text style:** `burst-action` — Fictional 400 · 72px/0.9

**Observed:** A yellow irregular starburst backs two lines of centered blue lettering; the text counter-rotates relative to the burst. The object is oversized and overlaps the green panel and preceding block.

**Transfer:** Keep one short, direct action inside the star; recreate the backing with the Comic cutouts graphic recipe.

### Credit link

**Use:** Small attribution and utility navigation at the bottom.

**CSS:** `color: #666666; border-bottom: 1px solid #cccccc`

**Text style:** `credit` — Fictional 400 · 16px/1.4

**Observed:** Credits occupy one left-aligned line, followed by a second compact line of utility and social links; there are no footer columns.

**States:** Declared: hover text-decoration none, border-bottom-color currentcolor.

**Transfer:** Retain the abrupt scale change after the oversized closing action.

### Specimen option

**Only for:** interactive product comparisons

**Use:** Selectable product variants within the violet proof card.

**CSS:** `color: #ffffff; text-align: center; transform: rotate(4deg)`

**Text style:** `specimen-row` — Fictional 400 · 50.4px/1.714

**Observed:** Rows alternate gentle tilts and visibly vary their letterform weight; they are text-first controls without individual card backgrounds.

**States:** Declared: hover transform scale(1.35), outline none.

**Transfer:** Show the actual effect of choosing each option rather than building a conventional feature checklist.

### Selection cell

**Only for:** interactive selection demonstrations

**Use:** Compact selector in a dense product-detail field.

**CSS:** `width: 36px; height: 36px; border-radius: 5px; color: #ffffff; position: relative; box-shadow: 0px 0px 0px 2px #fbd70c`

**Text style:** `cell` — Fictional 400 · 21.6px/1.667

**Observed:** Only the active item has the yellow ring; the remaining options sit unboxed on tomato. A much larger version appears in the adjacent detail area.

**States:** Declared: hover transform scale(1.7), background #ffffff, color #000000, outline none; active ring remains.

**Transfer:** Use this for a real inventory of symbols or product variations, with a synchronized large preview.

## Imagery and graphics

### Comic cutouts

**Use:** Signature opening collage and oversized conversion artwork.

**Observed:** Flat vector comic explosions, circles, tilted labels and white speech balloons surround a huge black name. A red burst sits above the name, a larger yellow burst behind its lower-left edge, and a violet scroll circle overlaps the yellow. Edges are crisp, fills solid, with no texture, lighting, photography or dimensional shading.

**Transfer:** Make a new typographic poster from the product name and a few useful annotations. When no product imagery exists, these vector cutouts are the complete visual centerpiece, not a placeholder for photography.

**Build:** Use SVG polygons with roughly 12–16 unequal outer spikes alternating with shorter inner points; vary tip lengths and spacing to avoid a perfect gear. Fill one with tomato and another with yellow, with no stroke or shadow. Opening bursts occupy roughly 440–560px boxes; rotate them about -20deg and layer the black name in front. Make 144px violet/green circles, 10px-radius labels tilted 10deg or -20deg, and white capsule bubbles with small triangular tails. For conversion, enlarge a yellow polygon beyond its one-third-width column and rotate its container 20deg; center blue two-line lettering with a -10deg counter-rotation.

### Living product specimens

**Use:** The principal proof imagery below the poster.

**Observed:** The product itself is the image: white typographic rows on violet, black text and a slider on yellow, then a field of white characters and one giant white character on tomato. Color blocks replace device mockups or photographic framing.

**Transfer:** Use actual selectable states, swatches, symbols or compact outputs of the new product, with one enlarged detail. The minimum version is a working two-state selector with visibly different outputs, not a decorative fake interface.

### Icons

**Observed:** Symbols are typographic and direct: a down arrow accompanies the lowercase scroll cue, while the detail field includes punctuation and directional arrows. Comic silhouettes do more identity work than an icon library.

**Transfer:** Prefer simple arrows rendered in the text family; keep functional symbols subordinate to the sticker silhouettes.

## Section recipes

How recurring sections are built.

### First screen: Sticker poster opening

**Observed:** A 20px white frame surrounds a 1400×860px Cream poster. With no conventional navigation bar, the first 900px show the entire composition: a black 201.6px product name centered across roughly three-fifths of the width, white descriptor bubbles above-left and below-right, a red upper burst, a yellow lower-left burst, small tilted fact labels, and green/violet circles. Cream is the back layer; bursts and bubbles overlap in the middle; the name reads in front. A circular scroll prompt sits low in the collage and availability is carried by a rectangular sticker, not a standard CTA pair. The next proof cards begin below the first screen.

**Transfer:** Give a different product a short name or compact display phrase at the same visual dominance, then distribute its promise and useful facts among custom comic cutouts. Keep this typographic artwork even without product media. Secondary marketing pages can open with a shorter poster using the same name-and-sticker relationship.

**Avoid:** Do not turn this into a left-aligned headline with a screenshot on the right, or add a floating navigation bar that competes with the poster.

**Text style:** `display` — Fictional 400 · 201.6px/1.2

### Bright paired proof

**Observed:** Two Saturated panels share equal width and 559px height, separated by 20px: violet holds centered Specimen options, while yellow holds the Explanatory proof card and range control. The blocks start directly with specimens or prose instead of an eyebrow/heading pair.

**Transfer:** Pair tangible product variation with plain-language explanation; use contrasting violet and yellow rather than a monochrome card grid.

**Text style:** `body-feature` — Fictional 400 · 37.4px/1.3

### Inventory and giant detail

**Observed:** A full-width tomato Saturated panel is 598px high. Compact Selection cells fill its left two-thirds with 28.8px inset, and a 345.6px white selected symbol occupies the right third.

**Transfer:** Show breadth through a compact selection field and clarity through one huge synchronized preview; this composition can represent ingredients, outputs or customizable parts.

**Text style:** `detail` — Fictional 400 · 345.6px/1.2

### Contact panel and escaping burst

**Observed:** A 927px-wide green Saturated panel holds centered closing prose with Conversational inline links and 57.6px top, 108px side and 43.2px bottom padding. The Purchase burst occupies the adjoining one-third-width area, but is enlarged and shifted to overlap both the panel and preceding demonstration. Two thought groups make the destination and human contact route clear.

**Transfer:** Close with a practical route to obtain the product and a friendly question-handling sentence. Preserve a giant yellow burst action somewhere prominent even if the conversion content is placed elsewhere.

**Text style:** `closing` — Fictional 400 · 47.5px/1.1

### Small credit ending

**Observed:** The final block returns to the White frame: a left-aligned 16px gray attribution line and a second utility-link line, about 45px total height, with an additional 22.4px margin before it.

**Transfer:** End with a brief human-scale credit and only essential utility links; do not extend the saturated action into a large corporate footer.

**Text style:** `credit` — Fictional 400 · 16px/1.4

## Page flow

**Storyline:** expressive identity → hands-on variation and explanation → breadth with enlarged detail → friendly next step and comic conversion → tiny credits

### A compact expressive product launch that lets visitors experience the product before leaving to obtain it

1. **Promise** — A full-screen typographic poster communicates character through the product name, speech bubbles and launch stickers.
2. **Product demonstration** — Paired violet and yellow cards combine selectable variants, a short description and a range control.
3. **Capability proof** — A dense tomato inventory is paired with one monumental selected detail.
4. **Closing call** — A green conversational destination/contact panel meets a huge yellow purchase burst.
5. **Utility ending** — Two small gray lines supply attribution and utility links.

**Transfer:** Borrow the escalation from expressive identity to tangible interaction and practical conversion; adapt the amount and position of proof to the new product rather than copying a fixed section count.

## Writing

Warm, cheerful and unabashedly playful. Personality is stated plainly, reinforced by comic exclamations, then grounded with useful descriptions and approachable contact language.

**Do not copy:** Do not reuse the Fictional name, Jonas Type or Jonas Pelzer identities, original product claims, weight count, use-case claims or exact branded artwork. Write equivalent facts and actions for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The product is described in the third person; closing copy addresses the reader as you and offers a direct human contact route.
- **Rhythm:** A one-word identity headline, short sticker fragments, one-sentence descriptive paragraphs and fuller conversational closing sentences. Exclamations belong to announcements and comic shouts rather than every line.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity headline | Use a short product name as the central poster object. | 1–2 words | “[Brand]” |
| Supporting clause | Split the personality statement into two friendly speech-bubble fragments. | 4–6 words per bubble | “A friendly & quirky typeface”<br>“with a cartoonesque character” |
| Description | Name the product's emotional character, then explain practical uses in a separate sentence. | 12–16 words per sentence | “[Brand] is a friendly, playful typeface, full of warmth and personality.” |
| Sticker annotation | Use blunt availability, novelty or useful facts; uppercase fits the compact rectangle or badge. | 1–4 words | “Free trial available”<br>“OUT NOW” |
| Primary action | A short verb-led action, stacked inside a comic burst. | 2 words | “BUY NOW” |
| Contact | Offer help in a normal sentence and underline the actionable phrase. | One short sentence | “If you have any questions, please send an email!” |

**Words and phrasing to use:** friendly; playful; warmth; personality; cheerful; head over to; questions; send an email

**Avoid:** enterprise-grade; seamless ecosystem; revolutionize; industry-leading; technical jargon in the poster

**Rules:**

- Let the art supply the exuberance while descriptions remain concrete.
- Keep labels readable in a single glance.
- Use a direct destination and a human contact path instead of vague conversion language.
- Reserve comic sound effects for graphic annotations.

## Do's and Don'ts

### Do

- Keep the page frame and panel gaps at 20px.
- Use 15px corners on major color panels and 10px on rectangular stickers.
- Keep the opening product name at 201.6px with normal tracking at desktop scale.
- Pair violet/white specimens with yellow/black explanation.
- Use 144px circles and opposite sticker tilts to create the comic-poster balance.
- Let the yellow conversion burst escape its column and overlap nearby panels.
- Maintain 47.5px centered conversational closing prose.
- Drop to 16px gray text for the final two-line footer.

### Don't

- Do not apply gradients, glossy lighting or drop shadows to the flat color panels.
- Do not replace the expressive family with a neutral geometric sans throughout.
- Do not make every annotation a perfect pill: retain circles, 10px rectangles, speech tails and irregular stars.
- Do not distribute every accent evenly inside each block; each proof panel has one dominant fill.
- Do not shrink the product demonstration into a device mockup surrounded by white space.
- Do not add a separate heading above every paragraph; oversized prose already leads the explanatory blocks.
- Do not use the 345.6px detail recipe for ordinary section headings.
- Do not replace the understated ending with dark multicolumn footer navigation.

## Motion and responsive

### Motion

**Observed:**

- Sticker entrances are staggered with declared 0.6–0.7s animations using cubic-bezier(0.34, 1.56, 0.64, 1); delays run from 0.8s through 3.8s.
- Selection cells declare transform 0.15s cubic-bezier(0.34, 1.56, 0.64, 1) and enlarge to scale(1.7) on hover.
- Specimen options declare 0.4s cubic-bezier(0.34, 1.56, 0.64, 1) and hover scale(1.35).
- The purchase-burst wrapper declares a 0.2s cubic-bezier(0.16, 1, 0.3, 1) transition.

**Transfer:**

- Use spring-like sticker entrances and local enlargement to make the poster feel touchable; keep normal reading and conversion available in the settled state.
- Limit hover enlargement to playful specimens and selectable details, leaving conversational links to their declared white-background treatment.

**Unknown:**

- Full game behavior, sound interactions and exact entrance transforms are not established.

### Responsive

**Observed:**

- A 700px width breakpoint is declared.
- Several text and inset recipes scale with viewport width, including the 5vw purchase lettering and 4vw proof-card padding.

**Transfer:**

- On narrow screens, recompose the poster around a readable name rather than uniformly shrinking every sticker.
- Stack paired proof cards and move the enlarged detail beneath its selection field when side-by-side reading fails; preserve the colored blocks and narrow white seams.
- Keep the purchase burst visibly overlapping the closing composition without obscuring contact links.

**Unknown:**

- Exact mobile column placement, sticker positions and breakpoint overrides are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
