# Eindhoven Design District — type turned into architecture

## Overview

A bold, light editorial style where black grotesk lettering behaves like architecture and documentary photographs become exhibits. White space, bubblegum pink, signal red and electric blue create an optimistic civic-poster atmosphere rather than a polished software dashboard. It suits products with tangible stories, cultural ambition or visible real-world impact, combining sparse oversized compositions with compact, informative text.

### Essentials

- Words become a spatial object: a monumental black word sculpture turns one word through 90 degrees, linking horizontal words across an approximately 1190×566px stage; repeat the device in a horizontally travelling editorial ribbon. Use new product language and live SVG text when bespoke artwork is unavailable.
- The opening is an asymmetric exhibition, not a centered sales pitch: a white canvas, 125px inset stage, a 261×339px upper-right photograph and a 417×526px lower-left photograph surround the word sculpture. The explanatory paragraph and first major action sit below the first 900px.
- Headings are tightly packed but paragraphs remain purposeful: HelveticaNow at 50px/1, weight 600, -0.02em for section titles; 35px/1.2 for the introductory manifesto; 18px/1.473, weight 600 for colored feature narratives.
- Actions are little capsules against monumental content: 500px radii, 1px black outlines on white, 53px height; white filled variants are 55px high on colored bands. Header tools shrink the same silhouette to 30px.
- Color occupies entire chapters, not decorative sprinkles: white carries the opening and typographic ribbon, gray carries the editorial carousel, and pink, red and blue carry full-height feature panels. In a feature, color and photography each occupy half the width; blue reverses the type to white.
- Photography is square-edged and materially specific: daylight buildings, patterned facades, objects in use and people at work, with no mockup frames or shadows. A pink closing question leaves a long pause before its white capsule, followed by a white footer with large stacked navigation and a substantial lower-left wordmark.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0f26ed` | `--color-blue` | background, surface | High-impact feature chapters and resource endings with white lettering. |
| Bubblegum pink | `#ffc2eb` | `--color-pink` | background, surface | Full feature text planes and closing invitations; also the directory opening. Keep it a flat color, not a translucent veil over photography. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#ff0000` | `--color-red` | background, text, accent | A full feature text plane with black lettering, and small editorial category labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, action, link | All primary lettering, hairline capsule outlines and link underlines. |
| Exhibition gray | `#e8e8e8` | `--color-gray-band` | background, surface | Editorial carousel backing and alternating directory bands. |
| White paper | `#ffffff` | `--color-paper` | background, surface, text | Default opening, reading areas, typographic ribbon and footer; filled capsules and text on blue. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| directory and comparison sections | Information rule | `#c7c7c7` | `--color-rule` | border | Thin separators between practical facts. |

## Typography

- **HelveticaNow** — All live text and the construction language of the word sculptures. Compact neo-grotesk with a large x-height, blunt terminals and firmly packed semibold headlines. If unavailable, use **Inter**. Use weights 400 and 600, retaining the tight headline tracking and compact line heights. Font stack: "HelveticaNow", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | HelveticaNow | 600 | 50px | 1 | -0.02em | fixed | Section leads, feature titles, editorial ribbon headings and closing questions. |
| manifesto | HelveticaNow | 600 | 35px | 1.2 | -0.004em | fixed | Broad introductory statement beneath the opening stage. |
| footer-navigation | HelveticaNow | 600 | 35px | 1 | -0.03em | fixed | Large stacked footer destinations. |
| card-heading | HelveticaNow | 600 | 23px | 1 | -0.0165em | fixed | Single-line editorial card titles, truncated with an ellipsis. |
| ribbon-body | HelveticaNow | 400 | 19px | 1.4 | -0.017em | size min(1.31944vw, 19px) | Introductory text inside the horizontal editorial ribbon. |
| feature-body | HelveticaNow | 600 | 18px | 1.473 | 0.015em | fixed | Compact but emphatic paragraphs in colored feature panels and image-backed closing invitations. |
| button | HelveticaNow | 600 | 16px | 1 | -0.024em | fixed | Outlined and filled capsule actions. |
| label | HelveticaNow | 600 | 16px | 21px | normal | fixed | Editorial category labels, small section headings and square-prefixed reading links. |
| small-body | HelveticaNow | 400 | 16px | 1.4 | -0.017em | fixed | Editorial card summaries and compact ribbon descriptions. |
| navigation-tool | HelveticaNow | 600 | 16px | 1.15 | normal | fixed | Menu label and compact header tools; the language abbreviation is uppercase. |
| credit-link | HelveticaNow | 600 | 16px | 21px | -0.02em | fixed | Compact attribution links grouped at the upper left of the footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| directory and institutional pages | page-title | HelveticaNow | 600 | 100px | 0.83 | -0.0257em | fixed | Two- or three-line titles for directory and institutional reading openings. |
| directory and institutional pages | lead | HelveticaNow | 600 | 22px | 1.275 | 0.007em | fixed | Opening explanatory paragraph accompanying a page title. |
| directory and institutional pages | body | HelveticaNow | 400 | 19px | 1.473 | -0.02em | fixed | Long-form reading and directory descriptions. |
| institutional reading pages | reading-subheading | HelveticaNow | 600 | 19px | 1.473 | 0.005em | fixed | Compact question-like subheads within long reading columns. |
| directory sections | caption | HelveticaNow | 400 | 15px | 1.473 | -0.025em | fixed | Image attribution beneath galleries and practical fact rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The largest opening lettering is a word sculpture rather than an ordinary heading: its visible capital height is about 128px, larger than the live page-title scale. Preserve its joined geometry instead of replacing it with a conventional headline block.
- Semibold carries most of the voice, including feature paragraphs. Regular text is reserved for longer reading and small editorial summaries.
- Tight line heights apply to headings, not paragraphs. Sentence case dominates; uppercase is limited to compact language controls.

## Layout

**Density:** Airy at the chapter level and compact inside content clusters: large vacant areas coexist with short headline-to-copy relationships.

### Spacing

**Spacing system:**

- **rhythm** 10px, vertical — Common vertical margins and chapter padding, with optical exceptions around type.
- **grid-gap** 20px, horizontal — Declared grid and container base; paired units create the main 40px desktop gutter.

| Value | Use |
| --- | --- |
| 10px | Icon-to-label gaps and separation between footer destinations. |
| 20px | Card image-to-text spacing, header tool separation and small content clusters. |
| 35px | Feature heading-to-paragraph gap and capsule horizontal padding. |
| 40px | Main column gutters and editorial heading-to-image gap. |
| 50px | Desktop outer margins, split-panel padding and common chapter gaps. |
| 80px | Directory band bottom padding. |
| 110px | Major editorial separation and long reading-section bottom clearance. |
| 187px | Breathing space after the introductory manifesto. |

### Containers and grids

- **main-container**: max width 1440px · 12 columns · gap 40px · side padding 50px. Desktop working width of 1340px inside the main canvas; align section headings, footer and text-led bands to this grid.
- **opening-stage**: max width 1190px · side padding 0px. An inset editorial composition, 125px from the desktop edges, narrower than the main container.
- **feature-halves**: max width 1440px · 2 columns · gap 0px · side padding 0px. Edge-to-edge color and photography, each 720px wide at desktop, typically filling a 900px chapter.
- **editorial-triptych**: 3 columns · gap 40px · side padding 50px. Three 420px image-led cards on the gray carousel band.
- **reading-pair** (only for directory and institutional pages): 2 columns · gap 40px · side padding 50px. Two 650px columns separated by a fine center axis; left text or title, right reading or gallery.
- **reading-width** (only for directory sections): max width 632px · side padding 0px. Directory paragraphs and fact tables remain slightly narrower than their column.

## Corner radius

| Element | Radius |
| --- | --- |
| capsules | 500px |
| gallery-controls | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default landing canvas, reading areas, ribbon and footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat uninterrupted paper; no visible elevation.

**Transfer:** Let composition, not card containers, divide the page.

#### Color plane · level 0

**Use:** Full-width chapter or one half of a split feature.

**CSS:** `background: #ffc2eb; color: #000000`

**Observed:** Pink is the default; red uses black type and electric blue uses white. The closing invitation returns to pink.

**Transfer:** Use one uninterrupted hue per chapter.

#### Editorial band · level 0

**Use:** Backing for image-led editorial cards.

**CSS:** `background: #e8e8e8; color: #000000; padding: 55px 0px 60px`

**Observed:** Cards sit directly on the band with no separate painted card shell.

**Transfer:** Reserve gray for grouped secondary content rather than tinting every section.

#### Information rules

**Only for:** directory and comparison sections

**Use:** Structured practical facts.

**CSS:** `border-bottom: 1px solid #c7c7c7`

**Observed:** Rows add a matching top border; the full list is closed by a bottom rule.

## Components

### Navigation bar

**Use:** Persistent brand and access controls above the opening.

**CSS:** `position: fixed; height: 100px; width: 100%; z-index: 4; background-color: #ffffff`

**Observed:** Small two-line wordmark at left; language, search and Menu capsules grouped at right with 20px gaps. The bar can withdraw on scroll; the pink directory opening visually carries its pink behind the controls.

**Transfer:** Keep the logo compact so the main word sculpture has its own scale.

### Outlined capsule

**Use:** Default action on paper and light content areas.

**CSS:** `color: #000000; border: 1px solid #000000; border-radius: 500px; padding: 16px 35px 19px; height: 53px; box-sizing: border-box; text-align: center`

**Text style:** `button` — HelveticaNow 600 · 16px/1 · tracking -0.024em

**Observed:** Text-only, horizontally centered, with generous lateral clearance and no arrow attachment.

**States:** Declared: hover background-color #000000 and color #ffffff; focus-visible unknown.

**Transfer:** Use descriptive action labels rather than a permanent dominant filled action.

### White capsule

**Use:** Actions on colored chapters and the gray editorial band.

**CSS:** `background-color: #ffffff; color: #000000; border-radius: 500px; padding: 18px 35px 21px; height: 55px; box-sizing: border-box; text-align: center`

**Text style:** `button` — HelveticaNow 600 · 16px/1 · tracking -0.024em

**Observed:** A quiet white island; the collection action stays near the lower-left edge of full-height feature chapters.

**States:** Declared: hover background-color #000000 and color #ffffff; focus-visible unknown.

### Menu capsule

**Use:** Compact utility navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; padding: 1px 12px 1px 15px; height: 30px; border: 1px solid #000000; border-radius: 500px; color: #000000`

**Text style:** `navigation-tool` — HelveticaNow 600 · 16px/1.15

**Observed:** Label followed by three short horizontal black lines. Search uses an icon-only capsule and language uses a short uppercase code with a downward chevron.

**States:** Declared: hover color white and background-color black; focus-visible unknown.

### Editorial card

**Use:** Secondary stories in the gray carousel.

**CSS:** `width: 420px; color: #000000`

**Text style:** `card-heading` — HelveticaNow 600 · 23px/1 · tracking -0.0165em

**Observed:** A 420×281px photograph comes first, then a red category label, a single-line ellipsized title and a regular summary limited to about four lines. Text occupies 90% of the card width; no visible outline, rounding or separate card fill.

**Transfer:** Keep the image substantial and the excerpt informative, not a collection of badges.

### Circular gallery control

**Use:** Carousel navigation beside a heading or over the gallery edge.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 55px; height: 55px; border-radius: 50%; background-color: #ffffff; color: #000000`

**Observed:** Small black chevron inside a generous circular hit area; paired controls sit 20px apart.

**States:** Declared: hover background-color #000000 and color #ffffff; focus-visible unknown.

### Footer destination

**Use:** Primary destination list in the footer's right column.

**CSS:** `color: #000000; background-image: linear-gradient(#000000, #000000); background-size: 0% 3.5px; background-position: 0px 43px; background-repeat: no-repeat`

**Text style:** `footer-navigation` — HelveticaNow 600 · 35px/1 · tracking -0.03em

**Observed:** A vertical stack with 10px gaps; underline is built as a background rather than a boxed button. The attribution groups occupy the opposite side.

**Transfer:** Use a few substantial destinations, not a dense sitemap.

### Practical fact row

**Only for:** directory and comparison sections

**Use:** Compact structured information below a directory description.

**CSS:** `display: flex; align-items: flex-start; gap: 10px; padding: 7px 0px; border-top: 1px solid #c7c7c7`

**Text style:** `caption` — HelveticaNow 400 · 15px/1.473 · tracking -0.025em

**Observed:** Small monochrome icon precedes one factual line; several rows form a ruled list. Gallery captions use the same type with 10px top separation.

**Transfer:** Adapt the rows to useful specifications, duration or availability, not decorative metrics.

## Imagery and graphics

### Typographic architecture

**Use:** Signature opening artwork and recurring editorial ribbon.

**Observed:** Heavy black neo-grotesk words join around right-angle turns. In the opening a long word spans the upper left, a second rises vertically near the center-right and a third extends to the right below it. A compact two-line invitation nests below the first word. The 1190×566px artwork shares the white stage with two photographs.

**Transfer:** Use the product's own short phrase as a spatial composition. A minimum version is three live-text words arranged horizontally, vertically and horizontally with their baselines meeting; preserve readability and large empty pockets.

**Build:** Create an SVG with viewBox 0 0 1190 566. Use black text, HelveticaNow or Inter semibold, starting around 180px font-size and tightly spaced, then tune widths to fit the phrase. Place the long first word across roughly two thirds of the top edge; rotate the connecting word -90deg, anchoring its end near the lower horizontal word. Put a 48px two-line supporting invitation in the open upper-left pocket. Render on white without bevels, texture or shadows.

### Documentary photographs

**Use:** Opening inserts, split features, editorial cards and gallery previews.

**Observed:** Architectural details, inhabited public spaces, material surfaces and people at work. Daylight stays natural, with occasional vivid light installations. Images have hard rectangular edges, no tint overlay and no floating-device frames. Feature images fill an entire 720×900px half; opening inserts retain distinct portrait proportions.

**Transfer:** Show an actual product outcome, a close material detail and a human setting with comparable specificity. For intangible products, photograph the working context or create a straightforward full-bleed interface detail rather than a glossy floating mockup.

### Travelling type ribbon

**Use:** Signature editorial discovery device within the landing narrative.

**Observed:** A 3856×482px horizontal word sculpture extends far outside the viewport. Content pockets contain 50px headings, short descriptions, square-prefixed underlined links and rectangular photographs. Scrolling reveals successive pockets while pieces of giant lettering remain cut by the viewport edges.

**Transfer:** Thread related use cases, demonstrations or stories through an oversized phrase; make text and images part of one typographic landscape rather than individual floating cards.

**Build:** Construct a clipped white viewport around a wide SVG or positioned text track approximately 3856px wide and 482px high at desktop. Alternate black horizontal word runs with 90-degree connectors. Reserve rectangular pockets between runs for text and roughly 390×260px landscape images. Translate the track horizontally as the reader progresses; the core composition must also work as an explicitly scrollable strip.

### Physical resource photograph

**Only for:** resource and directory endings

**Use:** Concrete final takeaway above the footer.

**Observed:** Printed pink and red folded matter photographed diagonally on a wooden bench; a 650×434px landscape image sits in the right half of an electric-blue band, with white explanatory text beneath it and a large title in the left half.

**Transfer:** Photograph a tangible guide, sample, report or package in natural surroundings, retaining visible material and shadow rather than isolating it on a studio gradient.

### Icons

**Observed:** Monochrome SVG symbols, generally 25×25px, with a 14×14px utility chevron. Gallery arrows are spare chevrons; fact rows use recognizable filled pictograms. Menu lines are 17×1px.

**Transfer:** Use simple black pictograms for facts and small chevrons for controls. Keep icons subordinate to the typography, with no colored icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Word sculpture opening

**Observed:** Paper canvas behind a compact Navigation bar. The main 1190px stage begins 125px below the top and is inset from the broader section grid. Back to front: white field, two rectangular documentary photographs, black Typographic architecture. The upper-right image is 261×339px; the lower-left image is 417×526px and continues below the 900px fold. A huge horizontal first word occupies roughly two thirds of the upper stage, the connector turns vertically near the right, and the last word anchors the lower-right edge. A short two-line invitation occupies the left pocket. Within the first 900px the word sculpture, invitation and both pictures are visible; no main conversion capsule is present. The manifesto and first major action begin below the 1198px opening.

**Transfer:** Give a different product an equally legible spatial phrase with two contrasting documentary views: a detail and a wider context. If no source photography is available, use a real working-context image and a tightly framed product detail. Directory pages instead use a pink 691px title band with a 100px heading at the upper left and 22px lead near the bottom; institutional reading pages use a white split opening with a sticky title on the left and text on the right.

**Avoid:** Do not replace this composition with a centered headline, two CTA buttons and a single wide hero image; do not put a pink wash behind the default opening.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Manifesto pause

**Observed:** A 1035px-wide introductory statement uses manifesto type, aligned with the inset opening stage. An Outlined capsule follows after 44px, then 187px of bottom space before the next editorial chapter.

**Transfer:** Explain the product's purpose in a substantive paragraph, allowing it to function as a typographic block rather than a slogan.

**Text style:** `manifesto` — HelveticaNow 600 · 35px/1.2 · tracking -0.004em

### Color and photograph feature

**Observed:** Feature-halves pairs a Color plane with a full-height Documentary photograph. The 900px chapter gives the left body 50px padding; heading width is about 496px and paragraph width about 422px. A 35px gap follows the heading, then a compact feature-body paragraph and a square-prefixed underlined reading link. A White capsule sits independently near the bottom. Pink and red use black type; blue uses white.

**Transfer:** Give each chapter one concrete use case or outcome, using the image as equal evidence rather than a thumbnail.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Editorial carousel band

**Observed:** Editorial band holds a left-aligned heading and Circular gallery controls at right; 40px later, three Editorial cards fill the width with 40px gutters. A White capsule sits below the cards. The band is separated from surrounding paper by substantial whitespace.

**Transfer:** Use this as supporting human proof, educational content or customer stories without turning it into a testimonial quotation grid.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Horizontal discovery landscape

**Observed:** Travelling type ribbon mixes oversized black word turns with small editorial pockets on paper. The visible stage is roughly 632px high, padded 50px; vertical progress reveals the wider track rather than more stacked cards.

**Transfer:** Carry a set of related next steps through one continuous typographic environment. The device can appear at any useful point in the narrative.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Closing question and signature footer

**Observed:** A 450px pink closing band contains a 50px question, constrained to 765px and usually two lines, with a White capsule near the bottom-left and a long unoccupied interval. The next 450px is a Paper canvas footer: small attribution groups at upper left, large Footer destinations at right, and a 495×140px two-line wordmark anchored low left. The same footer ends all page types.

**Transfer:** Ask a concrete reader-facing question, then give one low-pressure action. Finish with compact support credits, a short destination stack and a substantial typographic brand signature.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Directory comparison band

**Only for:** directory and resource pages

**Observed:** Alternating white and gray 780px bands, padded 50px above and 80px below. Reading-pair places a heading, 19px description, Practical fact rows and capsule on the left. The right column holds a small preview heading, a tall image gallery extending to the right edge, Circular gallery controls and a 15px caption. A fine vertical axis separates the columns. The ending changes to an electric-blue resource band, then the shared footer.

**Transfer:** Use for a product family or a set of service options, where descriptive facts and visual previews help the reader compare.

**Text style:** `heading` — HelveticaNow 600 · 50px/1 · tracking -0.02em

### Sticky institutional reading

**Only for:** institutional and explanatory pages

**Observed:** White Reading-pair begins around 140px down. A 100px/0.83 title remains at the left as the right column advances through a 22px lead, small semibold subheads, regular 19px paragraphs and a final image-led proof block. Subheads use about 57px top separation and 15px before paragraphs. The ending is a 900px pink-and-photograph invitation followed by the shared footer.

**Transfer:** Use for substantial background, method or company explanations, keeping the page identity visible beside the reading stream.

**Text style:** `page-title` — HelveticaNow 600 · 100px/0.83 · tracking -0.0257em

## Page flow

**Storyline:** spatial promise → purpose in prose → tangible demonstrations → editorial discovery → useful next step → invitation and brand signature

### Broad marketing landing page

1. **Promise** — Asymmetric word sculpture and two contrasting photographs.
2. **Purpose** — Large semibold manifesto with one outlined action.
3. **Demonstration** — Full-height color-and-photo chapters explain concrete outcomes.
4. **Editorial proof** — Gray three-card story carousel.
5. **Discovery** — A horizontally travelling typographic landscape reveals related stories.
6. **Closing call** — Pink question band and one white action.
7. **Orientation** — White footer with credits, stacked destinations and a large wordmark.

**Transfer:** Let tangible outcomes provide the argument. Preserve the spatial typography, color planes and substantial ending without requiring the same chapter order or count.

### Directory of experiences or offerings

1. **Orientation** — Pink title band and an emphatic lead set expectations.
2. **Comparison** — Alternating white and gray split bands combine descriptive text, practical rows and photographic previews.
3. **Takeaway** — Blue resource ending pairs a large heading with a physical resource image and inline download.
4. **Orientation** — Shared white signature footer.

**Transfer:** Adapt to product collections or service choices with genuinely useful facts and previews.

### Institutional explanation and purpose

1. **Identity** — Large sticky left title beside the opening lead.
2. **Explanation** — A right-hand reading stream organized by plain descriptive subheads.
3. **Proof** — An image-led example and a collection action continue the same reading column.
4. **Closing call** — Pink text half and full-height photographic half invite further discovery.
5. **Orientation** — Shared white signature footer.

**Transfer:** Use for a product philosophy, process or company story where the reading column needs depth rather than tiles.

## Writing

Public-facing, knowledgeable and inviting. The tone joins cultural confidence to practical explanation, treating the reader as curious rather than already expert.

**Do not copy:** Do not reuse the source brand name, wordmark artwork, partner identities, route names, project descriptions, local claims, quantities or quotations. Examples demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you in invitations and questions. Use we for the organization when explaining its purpose, and third-person names when describing concrete work.
- **Rhythm:** Short noun-based headings lead into substantive explanatory paragraphs. Invitations often take the form of a question; occasional exclamation marks add warmth, while descriptions use grounded specifics.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section heading | A plain noun or a concrete project name rather than an abstract benefit superlative. | 1–7 words | “Projects”<br>“Toolbox for freedom of movement” |
| Opening lead | A reader-facing question followed by reassurance and a specific account of what is available. | 2–3 sentences | “Want to truly experience design in Eindhoven? You’re in the right place!” |
| Editorial title | A concrete idea framed as an assertion or an explanatory tension. | 8–14 words | “Creating space for creativity: the importance of creative hubs in Eindhoven” |
| Closing question | Ask how the reader could apply the subject to their own situation. | 10–15 words | “Want to know how to use design power for your own project?” |
| Action | Descriptive destination or a warm invitation; never pressure language. | 2–7 words | “See all articles”<br>“Feel free to contact us!” |

**Words and phrasing to use:** discover; experience; explore; practical; projects; for yourself; want to; find out more

**Avoid:** revolutionary platform; unlock limitless potential; 10x everything; act now; world's best

**Rules:**

- Explain a real context before announcing a solution.
- Make project descriptions useful enough to stand alone, then offer a short reading link.
- Use questions to open a conversation, not to manufacture urgency.
- Keep category labels short and descriptive; let story headlines carry the argument.

## Do's and Don'ts

### Do

- Keep the default opening white and give its word sculpture an approximately 1190px stage.
- Join black horizontal and vertical words into a readable spatial object, with photographs occupying its open pockets.
- Use 50px/1 semibold section headings with -0.02em tracking.
- Preserve the 720px/720px color-and-photo balance in desktop feature chapters.
- Set feature paragraphs at 18px semibold and keep them narrower than their headings.
- Use 53px outlined capsules on paper and 55px white capsules on color.
- Keep the gray editorial band flat, with 420×281px images and 40px card gutters.
- Finish with a substantial wordmark, 35px stacked destinations and compact attribution groups on white.

### Don't

- Do not substitute a dark page shell for the white editorial canvas.
- Do not round photographs or add drop shadows to the flat exhibition layout.
- Do not turn the red and blue feature planes into tiny accent borders or pastel gradients.
- Do not make every action a black rectangle; the resting action language is outlined or white capsules.
- Do not apply the 100px page-title style to ordinary card titles; use the compact 23px recipe there.
- Do not set feature narratives in light 400-weight text; the semibold density is deliberate.
- Do not center-align the footer or convert it into several equally weighted sitemap columns.
- Do not use statistical counters, star ratings or logo clouds as substitutes for the documentary proof language.

## Motion and responsive

### Motion

**Observed:**

- Filled actions and gallery controls declare background-color 250ms and color 250ms transitions; compact header tools declare background-color 250ms.
- Underline backgrounds declare background-size 0.6s cubic-bezier(0.165, 0.84, 0.44, 1).
- The navigation bar declares transform 400ms, color 200ms 300ms and background-color 200ms 300ms.
- The editorial ribbon translates horizontally through vertical page progress; institutional titles remain visible while adjacent text scrolls.

**Transfer:**

- Use the horizontal type landscape as the characteristic scrolling scene, keeping small interactions to color inversion and underline travel.
- Keep the main composition readable at rest; do not turn each word into an unrelated entrance effect.

**Unknown:**

- Exact scroll mapping, pinning thresholds and arrow keyframe timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 370px, 599px, 600px, 900px, 992px, 1000px, 1023px, 1024px, 1120px, 1280px, 1900px and 2500px.
- The ribbon introduction uses min(1.31944vw, 19px) for font size.

**Transfer:**

- On narrow screens, preserve the joining logic of the word sculpture in a smaller SVG viewBox rather than shrinking the whole desktop page.
- Stack color and photographic halves with the text still anchored to an edge; retain hard image corners and capsule silhouettes.
- Turn the wide editorial landscape into an intentionally horizontally scrollable strip when pinning would compromise reading.

**Unknown:**

- Mobile compositions, exact collapse breakpoints and mobile headline sizes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
