# arte* — fieldwork meets pop

## Overview

An earthy, playful editorial style with oversized geometric lowercase lettering, an occasional literary serif, and typewriter-like labels. Warm oatmeal grounds forest green, mustard brown, olive, periwinkle and acidic yellow, while candid working-life photography gives the bright product theatre a human counterweight. It suits tangible consumer products and origin-led brands, with sparse text, expansive pauses and confident full-screen imagery.

### Essentials

- A film-poster opening rather than a sales dashboard: a 688px full-bleed documentary scene, a 683×292px upper-left wordmark and a centered 56px/0.9 serif promise in acid yellow.
- Lowercase geometry does the heavy lifting: Parafina at weight 500, normal tracking, 56px/0.9 for ordinary headings, 104px/0.9 for a manifesto and 172.8px/0.8 for product names, with the latter scaling at 12vw.
- Color arrives in chapters, not little UI accents: oatmeal #e5dccd carries editorial passages; product stages occupy whole 1440×900px panels in contrasting flat hues; the closing footer is periwinkle #7997ff with oatmeal lettering.
- Navigation is deliberately tiny against monumental branding: an 84px transparent sticky header, a 70×30px small logo after the opening, and a 93×44px Menu pill with 31px corners and 24px horizontal padding.
- Products interrupt their own names: a roughly 489×627px isolated pack sits in front of huge centered oatmeal text, with three loose 30px/1.4 descriptors orbiting it. Use a clean object cutout or simple product silhouette when no pack photography exists.
- The page ends like a signed poster: a flat location illustration with a 70px/0.9 invitation, a cream sheet with 64px bottom corners, then a newsletter/navigation row above a 1312×641px cream wordmark. Preserve both the monumental closing mark and scattered flat asterisk ornaments in new work.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mustard brown | `#ab5700` | `--color-ink` | text, border, background, action | Default editorial text, benefit rules, map silhouette and warm information panel; secondary-page menu fill. |
| Olive | `#9c9c38` | `--color-olive` | background, text, accent | Product-stage field and scattered accents; also the unified text and footer color of the origin-story variant. |
| Muted forest | `#214534` | `--color-hero-green` | background, text | Backing for the documentary opening and dark text on its yellow Menu pill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#e8e359` | `--color-yellow` | text, background, accent, action | Opening lettering and Menu pill; scattered star accents. Also highlights a comparison column and data segments. |
| Periwinkle | `#7997ff` | `--color-periwinkle` | text, background, action, link | Default footer field, emphasized clause, circular arrows and action hover. |
| Salmon | `#e99686` | `--color-salmon` | background, accent | Full product-stage field and occasional flat asterisk ornament; map silhouette in the forest-themed variant. |
| Workwear blue | `#3d549c` | `--color-blue` | text | Large centered editorial promise; a related deep blue field also appears in product theatre. |
| Leaf green | `#568037` | `--color-leaf` | text | Small product descriptors against salmon; not a general body-text replacement. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Oatmeal | `#e5dccd` | `--color-canvas` | background, text, border | Default editorial canvas; reversed type and fine lines on saturated fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| differentiation and partner pages | Deep forest | `#103d26` | `--color-forest` | text, background, border | Unified heading, paragraph, comparison, FAQ and footer color for the forest-themed variant. |

## Typography

- **Parafina** — Lowercase headings, product names, compact editorial statements and large numerals. Geometric sans with circular bowls and an easy, slightly eccentric silhouette. If unavailable, use **Outfit**. Use 500; retain circular construction and normal tracking. Font stack: "Parafina", "Outfit", sans-serif.
- **ExposureTrial** — The opening promise over documentary imagery. Expressive high-contrast serif, soft and literary rather than formal. If unavailable, use **Cormorant Garamond**. Use 500 and the tight 0.9 line height. Font stack: "ExposureTrial", "Cormorant Garamond", Georgia, serif.
- **Poppins** — Actions, navigation, small captions and supporting body copy. Round geometric sans, medium weight even at small sizes. Font stack: "Poppins", sans-serif.
- **Courier New** — Editorial labels, short introductions and contextual proof labels. Bold typewriter monospace, usually lowercase. Font stack: "Courier New", monospace.
- **ITC_Avant_Garde_Gothic_Medium** (only for origin stories and comparison tables) — Longer story paragraphs and comparison labels. Geometric sans with open circular forms. If unavailable, use **Questrial**. Match the medium visual weight without adding bold emphasis. Font stack: "ITC_Avant_Garde_Gothic_Medium", "Questrial", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-display | Parafina | 500 | 172.8px | 0.8 | normal, lowercase | size 12vw | Monumental names behind the product cutout; also short title-led openings. |
| manifesto | Parafina | 500 | 104px | 0.9 | normal, lowercase | fixed | Large centered statement on oatmeal. |
| closing-heading | Parafina | 500 | 70px | 0.9 | normal, lowercase | fixed | Compact three-line invitation beside the location graphic. |
| opening-promise | ExposureTrial | 500 | 56px | 0.9 | normal, lowercase | fixed | Centered three-line promise over the opening film. |
| heading | Parafina | 500 | 56px | 0.9 | normal, lowercase | fixed | Section statements, benefit titles, newsletter invitation and selected repeated slogans. |
| descriptor | Parafina | 500 | 30px | 1.4 | normal, lowercase | fixed | Floating words around a product. |
| editorial-label | Courier New | 700 | 24px | 1 | 0.0167em, lowercase | fixed | Short chapter labels above or beside editorial copy. |
| body | Poppins | 500 | 16px | 1.4 | normal, lowercase | fixed | Benefit support lines and FAQ answers. |
| action | Poppins | 500 | 16px | 1.4 | normal, uppercase | fixed | Menu, short text actions, eyebrows and footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| differentiation pages | word-cloud | Parafina | 500 | 172.8px | 1 | normal, lowercase | fixed | Centered multiline cluster of short attributes separated by colored asterisks. |
| impact and origin stories | stat | Parafina | 500 | 118px | 1 | normal, lowercase | fixed | Large freestanding numerical proof. |
| editorial data panels | data-question | Parafina | 500 | 56px | 1 | normal | fixed | Centered question above a two-column information display. |
| editorial data panels | data-tab | Parafina | 500 | 56px | 1.2 | normal, lowercase | fixed | Stacked category selectors beside a chart. |
| differentiation pages | editorial-statement | Parafina | 500 | 32px | 1 | normal, lowercase | fixed | Narrow indented paragraph beneath a monospace label. |
| title-led differentiation pages and proof labels | mono-introduction | Courier New | 700 | 24px | 1.4 | normal | fixed | Narrow opening explanation and multiline contextual labels. |
| question-and-answer sections | faq-title | Parafina | 500 | 24px | 1 | normal, lowercase | fixed | Question in a rounded outlined accordion. |
| comparison tables | comparison-label | ITC_Avant_Garde_Gothic_Medium | 500 | 20px | 1.4 | normal | fixed | Row labels in a dashed-rule comparison. |
| origin stories | story-body | ITC_Avant_Garde_Gothic_Medium | 500 | 18px | 1.4 | normal | fixed | Longer paragraphs beside documentary photographs. |
| impact and origin stories | stat-caption | Poppins | 500 | 12px | 1.6 | normal | fixed | Small explanation directly under a numerical proof. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep normal tracking throughout the large geometric scale; its character comes from rounded forms and compressed line height, not squeezed letters.
- The serif is an opening accent, not a second general-purpose heading family. Most ordinary headings use the 56px geometric recipe.
- The giant wordmarks are artwork, not a substitute font recipe. Use a vector version of the new identity and scale it to the composition.
- Use the tracked monospace label as the default chapter label; untracked 24px/1 labels belong to the origin-story variant.

## Layout

**Density:** Airy editorial spacing interrupted by immersive color panels; brief copy blocks have much more room around them than inside them.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Tight heading-to-support spacing and footer link rows. |
| 20px | Small editorial separation and header vertical inset. |
| 24px | Card gaps, Menu side padding, benefit-row vertical padding and newsletter heading gap. |
| 40px | Rich-text grid rhythm. |
| 60px | Short section padding. |
| 64px | Desktop page side padding and image/text column gaps. |
| 100px | Editorial section breathing room. |
| 114px | Footer top padding. |
| 140px | Benefit-list section vertical padding. |
| 340px | The large pause before and after a centered manifesto. |

### Containers and grids

- **editorial container**: max width 1600px · side padding 64px. Default desktop content wrapper; leaves 1312px of content at a 1440px viewport.
- **paired content**: 2 columns · gap 64px. Equal 624px columns for photograph plus FAQ or proof; related story grids use a 2:1 image-to-copy ratio.
- **benefit column**: max width 800px. Centered ruled list with no boxed card backing.
- **manifesto container**: max width 1200px. Centered broad display statement with intentionally long pauses.
- **story rail**: 4 columns · gap 24px. 315px-wide portrait-media cards, horizontally clipped at the right edge; a 360px heading rail sits to their left.
- **narrow statement** (only for differentiation pages): max width 332px. Indented prose inside the smaller side of a 3:4 text/image composition.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | menu pill | 31px |
|  | editorial media | 20px |
|  | documentary media | 16px |
|  | closing sheet | 64px |
| question-and-answer sections | faq outline | 24px |
| editorial data panels | data capsule | 324px |

## Surfaces and depth

### Surfaces

#### Oatmeal canvas · level 0

**Use:** All editorial reading sections.

**CSS:** `background: #e5dccd; color: #ab5700`

**Observed:** A flat warm field, without paper grain or card shadows.

**Transfer:** Let image edges, rules and type define the layout rather than layering white cards.

#### Documentary stage · level 0

**Use:** Full-bleed opening film.

**CSS:** `background: #214534; position: relative`

**Observed:** Green-toned footage fills the entire stage beneath yellow typography.

**Transfer:** Use a dark-enough real-world scene with a coherent green cast; keep details visible.

#### Product color field · level 0

**Use:** Immersive product chapters.

**CSS:** `background: #e99686; color: #e5dccd; position: relative; overflow: hidden`

**Observed:** One uninterrupted flat hue per stage, changing with the product; olive and deep blue are companion treatments.

**Transfer:** Choose a field that relates to the new object's own color and lets the cream title remain legible.

#### Closing sheet · level 1

**Use:** The end of the oatmeal content above the colored footer.

**CSS:** `background: #e5dccd; border-radius: 0px 0px 64px 64px; padding-bottom: 64px; margin-bottom: -64px`

**Observed:** The rounded sheet overlaps the footer rather than ending in a straight horizontal cut.

**Transfer:** Keep the overlap as a material transition, even on a shorter page.

#### Signature footer field · level 0

**Use:** Newsletter, navigation and monumental identity.

**CSS:** `background: #7997ff; color: #e5dccd; padding-top: 114px`

**Observed:** A single flat inverted field, not separate newsletter and legal strips. Forest and olive variants align with their page's text theme.

**Transfer:** Default to periwinkle for a new marketing page; keep alternate themes internally consistent.

#### Data capsule · level 1

**Only for:** editorial data panels

**Use:** A substantial evidence or transparency chapter.

**CSS:** `background: #ab5700; color: #e5dccd; border-radius: 324px; padding: 40px; max-width: 1400px`

**Observed:** An oversized rounded rectangle nearly fills the width, with a question above two columns of selectors and chart data.

**Transfer:** Retain the single bold enclosure; make any internal chart appropriate to the new product.

## Components

### Sticky navigation

**Use:** Persistent access without a conventional full link bar.

**CSS:** `position: sticky; z-index: 3; height: 84px`

**Observed:** Transparent two-ended header: small wordmark at left, Menu pill at right; inner padding is 20px vertically and 24px horizontally. It overlays the opening media.

**Transfer:** Keep the identity compact after the oversized opening mark.

### Menu pill

**Use:** Primary navigation trigger.

**CSS:** `background: #e8e359; color: #214534; border-radius: 31px; padding: 0px 24px; height: 44px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Poppins 500 · 16px/1.4 · uppercase

**Observed:** A short label without a hamburger icon; secondary editorial themes reverse cream text onto brown.

**States:** Declared: hover background-color #7997ff; focus-visible outline 0px, outline-offset -2px, box-shadow 0 0 0 3px #214534, 0 0 0 5px rgba(232,227,89,0.5), 0 0 5px 4px rgba(232,227,89,0.3).

### Arrow text link

**Use:** Low-pressure transition from a statement to deeper information.

**CSS:** `display: inline-flex; align-items: center; height: 44px; color: #7997ff; border-radius: 31px; background: transparent`

**Text style:** `action` — Poppins 500 · 16px/1.4 · uppercase

**Observed:** A small filled circular arrow precedes the uppercase label; the whole item is not a filled pill.

**States:** Declared: focus-visible outline 0px, outline-offset 3px, box-shadow 0 0 0 3px #e5dccd, 0 0 0 5px rgba(171,87,0,0.5), 0 0 5px 4px rgba(171,87,0,0.3).

### Benefit row

**Use:** A short set of product principles or distinguishing qualities.

**CSS:** `border-top: 1px solid #ab5700; padding: 24px 0px; text-align: center; color: #ab5700`

**Text style:** `heading` — Parafina 500 · 56px/0.9 · lowercase

**Observed:** Large title over one small body line, with a 4px local gap. Rows share an 800px centered column and the final row adds a bottom rule. Colored asterisk ornaments intrude at the edges.

**Transfer:** Use compact, distinct benefit words, not icon-card titles with paragraphs.

### Editorial media card

**Use:** Stories, collaborations or use cases in a horizontal rail.

**CSS:** `width: 315px; display: flex; flex-direction: column`

**Observed:** A 315×420px cover image with 20px corners precedes tiny uppercase dot-led tags and a short lowercase text link. No enclosing panel or shadow; photographic overlays can look hand-drawn.

**Transfer:** Use real people or outcomes, not generic stock-device mockups.

### Footer link

**Use:** Compact navigation and social links on the colored closing field.

**CSS:** `color: #e5dccd; text-decoration: none; transition: opacity 0.5s`

**Text style:** `action` — Poppins 500 · 16px/1.4 · uppercase

**Observed:** Navigation stacks in one column with 4px row gaps; social links run horizontally beside the address.

**States:** Declared: hover opacity 0.75; focus-visible outline 2px solid #e5dccd, outline-offset 3px.

### Newsletter field

**Use:** Single email entry within the footer.

**CSS:** `background: #7997ff; color: #e5dccd; height: 35px; padding: 8px 50px 8px 0px; border: 0px; border-bottom: 1px solid rgba(229,220,205,0.5); border-radius: 0px`

**Text style:** `body` — Poppins 500 · 16px/1.4 · lowercase

**Observed:** A roughly 320px-wide underlined field sits below the two-line newsletter heading. A 24px circular-arrow submit affordance is inset at the right; the enclosing field is 37px tall. Forest and olive footer variants carry their field background through.

**Transfer:** Keep the form visually part of the footer, not a white input box.

### Monumental footer mark

**Use:** The final visual signature.

**CSS:** `max-width: 100%; overflow: hidden`

**Observed:** A cream vector wordmark spans the 1312px content width and roughly 641px height, beneath the compact utility row. It nearly touches the bottom edge.

**Transfer:** Use the new identity as vector artwork, or a bold custom typeset brand signature fitted to the full width; preserve the huge scale.

### FAQ accordion

**Only for:** question-and-answer sections

**Use:** Detailed objections beside a large lifestyle image.

**CSS:** `border: 1px solid #103d26; border-radius: 24px; color: #103d26; background: transparent`

**Text style:** `faq-title` — Parafina 500 · 24px/1 · lowercase

**Observed:** Each closed row is 624×56px; its summary has 15px padding and a right-aligned 24px arrow. Expanded content uses the body recipe.

**States:** Declared: focus-visible outline 2px solid #103d26, outline-offset 3px.

### Comparison row

**Only for:** comparison tables

**Use:** Direct, scannable differentiation.

**CSS:** `display: grid; grid-template-columns: 3fr 2fr 2fr; align-items: center; border-bottom: 1px dashed #103d26; color: #103d26`

**Text style:** `comparison-label` — ITC_Avant_Garde_Gothic_Medium 500 · 20px/1.4

**Observed:** Rows are 49px tall across 1312px. The featured middle column has a continuous acid-yellow rounded backing; 16px mustard dots mark its attributes. The header rule is solid.

**Transfer:** Use supported comparisons, leaving genuinely inapplicable cells empty rather than decorating every cell.

### Impact numeral

**Only for:** impact and origin stories

**Use:** Quantified proof paired with hands-on photography.

**CSS:** `color: #9c9c38; text-align: center`

**Text style:** `stat` — Parafina 500 · 118px/1 · lowercase

**Observed:** Three large numerical statements alternate position within a right-hand 624px column; tiny captions sit directly underneath. A mono contextual label occupies upper negative space, and a blue hand-drawn object interrupts the middle row.

**Transfer:** Keep the scale contrast and staggered positions, using substantiated metrics.

## Imagery and graphics

### Working-life documentary

**Use:** Opening media and recurring editorial proof.

**Observed:** Wide greenhouse footage and close views of hands, produce and people at work; natural green light, real structural detail and candid gestures. Images dominate their paired text. Secondary imagery has restrained 16px corners and asymmetric proportions.

**Transfer:** Photograph the new product's making, setting or real use with the same tactile specificity. A strong full-bleed still of people doing the work is the minimum alternative to film.

### Floating product theatre

**Use:** Full-screen color chapters.

**Observed:** A clean isolated flexible pack floats at the center, slightly tilted, with realistic folds and highlights. Huge cream names pass behind it; the pack occupies about one third of the width and two thirds of the height. There is no horizon, pedestal or heavy drop shadow.

**Transfer:** Use a real isolated object with retained material detail; for an intangible product, create one crisp front-facing output or interface panel as the central object, not a collage of dashboards.

**Build:** Use a 1440×900px relative stage, a solid salmon, olive or blue background, centered 12vw geometric title at z-index 1, and a roughly 489×627px transparent object at z-index 2. Place three 30px labels above-left, above-right and below-left, with slight independent rotations. Keep the field flat and the object sharply resolved.

### Flat asterisk ornaments

**Use:** Scattered punctuation around benefit and editorial sections; a repeated identity device.

**Observed:** Bold flat five-armed asterisks in yellow, dark green or salmon overlap rules or sit in negative space. They feel like typographic cutouts, not shaded stickers.

**Transfer:** Create an original simple starburst or asterisk that belongs to the new identity, preserving flat color, playful rotation and occasional edge overlap.

**Build:** In SVG, union five thick rectangular arms around a common center at 72-degree intervals, retaining square ends. Render at roughly 90px, rotate instances independently, and fill with #e8e359, #214534 or #e99686. Use no stroke, bevel or shadow.

### Location silhouette

**Use:** Closing invitation before the footer.

**Observed:** A flat map of Canada occupies roughly 900×604px at left. Small cream-backed colored location pins dot the silhouette; a compact three-line heading and filled circular arrow sit at right. Default silhouette is mustard brown with periwinkle pins; forest and olive themes swap the accent relationship.

**Transfer:** Use a relevant service footprint, simplified place silhouette or network illustration. If geography is irrelevant, use a flat original diagram of access points with the same pin rhythm and scale.

**Build:** Draw a single solid-color SVG silhouette without internal borders. Add a dozen small cream circles with colored teardrop pins inside. Keep the graphic roughly twice the width of the adjoining text block and leave the canvas visible through cutouts.

### Community portrait rail

**Use:** Editorial cards following product claims.

**Observed:** Warm flash-like portraits, colorful dishes and casual gatherings, often with an imperfect handwritten rectangular frame or annotation baked into the picture. Portrait media has rounded corners and saturated real-world color.

**Transfer:** Show the new product in actual social or practical use, with one original hand-drawn annotation if appropriate; preserve the mix of human subjects and finished results.

### Blue margin sketches

**Only for:** origin and transparency stories

**Use:** Organic marginalia around documentary imagery and the data capsule.

**Observed:** Periwinkle single-color hand-drawn vegetables and a sketched pack sit in margins, crossing image or panel edges. Thin imperfect lines contrast with the solid geometry of type and surfaces.

**Transfer:** Draw tools, materials or objects specific to the new product; keep them small and recognizably hand-drawn.

**Build:** Use transparent SVGs with irregular 1px–2px periwinkle strokes, no fill, slightly doubled contour paths and a few interior gesture lines. Place at roughly 80px–180px with a slight tilt, partly straddling an image or capsule edge.

### Icons

**Observed:** Simple filled SVG circles containing fine directional arrows, 24px for inline actions and 60px for standalone closing or return-to-top controls. Location pins use a colored teardrop and cream center. The logo is artwork, not an icon font.

**Transfer:** Keep the icon vocabulary narrow: arrows for movement and simple pins for location. Match the current section's cream/accent reversal instead of introducing multicolor icon sets.

## Section recipes

How recurring sections are built.

### First screen: Documentary poster opening

**Observed:** A 688px-tall full-width film fills about three quarters of the first 900px screen. Behind everything is the muted forest backing, then edge-to-edge green documentary footage. A 683×292px acid-yellow wordmark fills the upper-left half; the Menu pill floats at upper right in the transparent Sticky navigation. A centered three-line serif promise sits in the lower-middle, roughly 560px wide, with a tiny bracketed scroll cue near the bottom. The first screen includes film, giant identity, promise and navigation, followed by about 212px of empty oatmeal transition. The large geometric manifesto is below the fold; there is no hero form or filled purchase button.

**Transfer:** Replace the footage with a rich image of the new product's world and fit its own wordmark to the same dominant upper-left role. Without motion, use one compelling documentary still. Differentiation pages instead open with a short monumental lowercase title and a narrow monospace explanation on oatmeal; origin stories open with a tall image at left and a smaller titled video at right.

**Avoid:** Do not replace this with a conventional left headline/right mockup split, center the giant logo like a small masthead, or add a row of competing hero CTAs.

**Text style:** `opening-promise` — ExposureTrial 500 · 56px/0.9 · lowercase

### Centered promise and broad statement

**Observed:** The manifesto container holds a centered 104px/0.9 blue promise, with 340px top and bottom padding. A large gathering photograph follows, aligned to the 64px gutter rather than stretched full width. A broad 56px lowercase statement then uses mustard text with one periwinkle clause and an Arrow text link.

**Transfer:** Use a compact category or benefit promise, then tangible use and one short explanation. Preserve the single colored clause rather than coloring every keyword.

**Text style:** `manifesto` — Parafina 500 · 104px/0.9 · lowercase

### Product color chapter

**Observed:** The Product color field fills a desktop viewport. Floating product theatre layers an isolated object over the product-display title and loose descriptors. Consecutive chapters move horizontally so adjacent hues can share the screen at transitions.

**Transfer:** Use one distinct object or outcome per field and let the title run behind it. The device can occur once or several times without dictating page length.

**Text style:** `product-display` — Parafina 500 · 172.8px/0.8 · lowercase

### Ruled principles

**Observed:** Benefit row components form an 800px centered list on Oatmeal canvas, within 140px vertical padding. Each title has a single support line; flat asterisk ornaments touch selected rules.

**Transfer:** Turn product strengths into a brief set of human-readable qualities. Keep the asterisk device, but adapt list length to the message.

**Text style:** `heading` — Parafina 500 · 56px/0.9 · lowercase

### Editorial story rail

**Observed:** A 360px left heading rail carries a small uppercase eyebrow above a stacked 56px title. Editorial media cards continue to the right with 24px gaps, showing a clipped next item instead of wrapping into a conventional centered grid.

**Transfer:** Use stories or real examples to shift the page from assertion to lived experience.

**Text style:** `heading` — Parafina 500 · 56px/0.9 · lowercase

### Editorial image and explanation

**Observed:** Large rounded documentary photographs alternate with short copy columns separated by 64px. Monospace labels introduce indented paragraphs; the differentiation variant uses a narrow 332px column of 32px/1 display text, while origin stories use smaller 18px/1.4 geometric prose next to a two-thirds-width image.

**Transfer:** Alternate evidence and explanation; vary which side owns the visual weight rather than repeating identical split sections.

**Text style:** `editorial-label` — Courier New 700 · 24px/1 · tracking 0.0167em · lowercase

### Location invitation and signed ending

**Observed:** Location silhouette and closing-heading form a broad left graphic/right invitation pair on oatmeal. The Closing sheet rounds off the content over the Signature footer field. The footer's utility row places a 320px newsletter block at left, narrow navigation in the middle, address/social information beside it and a 60px return-to-top circle at right. The Monumental footer mark fills the width below, making the ending primarily an identity poster. Periwinkle is the default; forest and olive are scoped page themes.

**Transfer:** Close with an access or availability invitation relevant to the product, then a simple contact or subscription path and the monumental new identity. Keep the signed-poster ending even if the preceding page is short.

**Text style:** `closing-heading` — Parafina 500 · 70px/0.9 · lowercase

### Attribute word poster

**Only for:** differentiation pages

**Observed:** A centered three-line word cluster uses 172.8px/1 lowercase green text over oatmeal, with salmon asterisks between the short words. The block spans the 1312px content width.

**Transfer:** Select a handful of distinct attributes and arrange by visual balance, without turning them into equal-sized cards.

**Text style:** `word-cloud` — Parafina 500 · 172.8px/1 · lowercase

### Comparison and questions

**Only for:** differentiation and partner pages

**Observed:** A 56px introduction leads into Comparison rows with a yellow spotlight column. A later paired-content grid places a 624×776px lifestyle image beside a heading and FAQ accordion stack.

**Transfer:** Use a comparison only when its criteria are meaningful, then answer the practical objections in the rounded question rows.

**Text style:** `heading` — Parafina 500 · 56px/0.9 · lowercase

### Capsule transparency panel

**Only for:** editorial data panels

**Observed:** Data capsule sits inset about 72px from the viewport edges at desktop. A centered mono label and data-question heading introduce a lower 2:3 split: large stacked category tabs at left and a small ruled calendar chart at right. Blue margin sketches overlap its perimeter; yellow segments contrast with pale imported segments.

**Transfer:** Put meaningful provenance, process or performance evidence in the enclosure. Retain the unusually soft outer shape and fine internal data rhythm; do not copy the source's particular chart content.

**Text style:** `data-question` — Parafina 500 · 56px/1

### Staggered impact proof

**Only for:** impact and origin stories

**Observed:** A 624×832px close-up of hands at work anchors the left column. Three 118px numerals with 12px captions occupy staggered positions on the right, interrupted by a blue line drawing and a loose monospace contextual label.

**Transfer:** Use a small number of verified results and retain asymmetry rather than aligning all metrics into dashboard cards.

**Text style:** `stat` — Parafina 500 · 118px/1 · lowercase

## Page flow

**Storyline:** immersive promise → plain-language positioning → tangible product or process proof → distinctive qualities → practical reassurance → invitation and monumental signature

### A sensory marketing landing page that makes a product feel both useful and culturally alive

1. **promise** — Documentary poster opening with huge identity and a literary benefit line.
2. **positioning** — Spacious centered category promise, real-life photograph and a broad colored-clause statement.
3. **product demonstration** — Horizontal full-screen colored object stages.
4. **differentiation** — Ruled principles with oversized headings and scattered asterisks.
5. **social proof** — Portrait-media editorial rail showing people and uses.
6. **closing call** — Flat access graphic, rounded canvas edge and periwinkle newsletter footer with monumental identity.

**Transfer:** Use the contrast of real-world context and abstract object theatre as the narrative engine; adapt the amount of proof to the product.

### A focused differentiation page for readers weighing trust and partnership

1. **positioning** — Huge short title, narrow mono introduction and a single playful product-use image.
2. **differentiation** — A large asterisk-separated attribute word poster.
3. **capability explanation** — Monospace section labels and narrow display paragraphs beside a tall lifestyle photograph.
4. **comparative proof** — Dashed comparison rows with a yellow spotlight column.
5. **objection handling** — Outlined rounded FAQ beside an image.
6. **closing call** — Salmon access silhouette with green invitation, rounded sheet and forest signature footer.

**Transfer:** Keep the poster-like scale while letting more explanatory copy and practical answers support consideration.

### An origin and impact story driven by people, process and measurable care

1. **human context** — Asymmetric tall photograph and smaller film with a short 56px title.
2. **purpose** — Narrow statement beside a close-up working photograph.
3. **process proof** — Uneven documentary gallery, short producer explanation and wide hands-on image.
4. **conviction** — Monumental editorial statement with blue marginal sketches.
5. **transparency** — Mustard data capsule with category tabs and fine calendar marks.
6. **origin story** — Large people/process images alternate with small geometric prose.
7. **quantified proof** — Staggered oversized olive statistics beside hands at work, then a repeated periwinkle slogan ticker.
8. **closing call** — Periwinkle access silhouette, olive invitation and olive monumental footer.

**Transfer:** Use original people, process detail and verified data to earn emotional claims; preserve the more intimate photographic pacing and olive theme.

## Writing

Friendly, grounded and a little mischievous. Everyday benefits and specific sourcing language sit beside conversational wordplay; the confidence is warm rather than luxury-formal or technical.

**Do not copy:** Do not reuse arte* identity artwork, product names, founders, addresses, partner names, sourcing or safety certifications, metrics, product claims or quotations as claims for a new brand. Source examples illustrate voice only.

- **Addressing the reader:** Use we for the makers and you or your for the reader. Product references stay concrete; the reader is a person with everyday needs, not a business persona.
- **Rhythm:** Short lowercase headings, often three to seven words; compact single-sentence support lines and occasional longer editorial paragraphs. Asterisks, compounds and contractions add rhythm without exclamation-heavy selling.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A human journey from making to daily use, phrased as a reassuring relationship. | 8–14 words | “from our farms to your table, always close to home” |
| Positioning | Plain category description softened by an informal qualifier. | 5–10 words | “convenient and fresh, almost-ready-to-eat products.” |
| Benefit title | One familiar quality word with a small verbal twist. | 1–3 words | “Flavour-full”<br>“Familiar” |
| Editorial heading | A relationship metaphor that makes a practical principle memorable. | 6–12 words | “we don't believe in long distance relationships” |
| Action | Simple invitation or destination, with no urgency or inflated promise. | 2–6 words | “More on us”<br>“Sign up for our newsletter” |
| Objection handling | Ask the practical question in the reader's own words, then explain the mechanism plainly. | 6–12 words per question | “where are your ingredients sourced from?” |

**Words and phrasing to use:** close to home; thoughtfully; fresh take; feel-good; with a full plate; from our … to your …; chef-inspired; win-win

**Avoid:** disruptive ecosystem; unlock your potential; enterprise-grade excellence; exclusive luxury; hurry, limited time; world's best

**Rules:**

- Keep headlines predominantly lowercase; reserve uppercase for small navigation, tags and eyebrows.
- Pair an emotional phrase with a tangible explanation rather than stacking adjectives.
- Use gentle product-specific wordplay, not a stream of jokes.
- Keep supporting copy short enough that photography remains the dominant evidence.
- Make practical information candid and specific; qualify numerical statements where necessary.

## Do's and Don'ts

### Do

- Keep default editorial text mustard brown on oatmeal, with periwinkle used for a single emphasized clause or action.
- Use 56px/0.9 geometric headings at weight 500 and normal tracking.
- Let the 12vw product name pass behind the central object.
- Keep the Menu trigger 44px tall with 31px corners, rather than enlarging navigation to compete with the identity.
- Use 64px desktop content gutters and 24px gaps in the story rail.
- Preserve fine 1px rules and flat surfaces without elevation shadows.
- Make the closing identity fill the 1312px desktop content width.
- Use documentary images at materially larger scale than their adjoining copy.

### Don't

- Do not turn all headings into the serif; it is the distinctive 56px opening accent.
- Do not tighten display tracking into a compressed tech aesthetic; tracking stays normal.
- Do not use pure white reading panels in place of the #e5dccd canvas.
- Do not shrink the signature footer into a conventional small-logo legal strip.
- Do not add gradients, glass blur or drop-shadow stacks to the flat product fields.
- Do not box the benefit list into separate rounded cards; its shared 800px ruled column is essential.
- Do not use the forest differentiation theme and olive origin theme interchangeably within an ordinary landing page.
- Do not use multicolor outline-icon grids where simple circular arrows, flat pins and asterisks suffice.

## Motion and responsive

### Motion

**Observed:**

- Menu background-color transitions over .2s ease; footer links transition opacity over 0.5s and dim to 0.75 on hover.
- Product chapters translate horizontally through full-viewport flat-color stages; small descriptors change tilt and position.
- Declared animations include reveal at 1s ease with a 0.2s delay, float at 6s ease-in-out and repeating slogan tickers at 10s linear.

**Transfer:**

- Keep motion tied to the color-stage presentation and loose floating descriptors, rather than animating every UI element.
- Use a repeated horizontal sentence strip for the origin-story ticker variant; keep the flat oatmeal backing and periwinkle text.

**Unknown:**

- Exact scroll pinning distances and sequencing are not specified.
- Opening-film playback controls and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 749px/750px and 989px/990px, with additional component-specific desktop thresholds.
- The monumental product title uses 12vw.

**Transfer:**

- On narrow screens, preserve the opening's documentary backdrop and oversized identity, but fit the promise into readable lines.
- Stack image/text pairs while keeping images dominant; retain the horizontal editorial rail instead of compressing its portrait cards into tiny columns.
- Keep the footer mark full width and let utility columns stack above it; retain the rounded sheet transition.

**Unknown:**

- Exact mobile sizes, margins, ordering and menu-drawer layout are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
