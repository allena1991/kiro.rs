# Wise — heavyweight everyday optimism

## Overview

An exuberant, practical style that makes complicated services feel ordinary and approachable. Acid green and deep forest green punctuate a mostly white and pale sage world, with chunky uppercase display lettering balanced by lucid grotesk text. Rounded product demonstrations, warmly lit everyday photography and tactile painted graphics make spacious marketing pages feel useful rather than abstract.

### Essentials

- Headlines feel like solid blocks of language: Wise Sans at weight 900, 89.1px/0.85 for the opening and 58.5px/0.85 for major chapters, visually uppercase with normal tracking.
- The promise sits above a working object, not beside decorative filler: a centered 604px support column and 200px × 48px action lead into a 515px white demonstration on an uninterrupted #9fe870 opening.
- Green has distinct jobs: #163300 anchors text and reversed cards, #9fe870 owns the opening and conversion accents, and #ecefeb washes support bands. White and pale sage dominate the long body; multicolor texture is concentrated around an inset callout rather than spread through every section.
- Actions are short capsules, never rectangular slabs: 9999px radius, 11px 24px padding, 16px/24px semibold text and 48px height; reverse forest and lime according to the background.
- Every page needs tangible proof: rounded photographs or a functional product panel, with white capsule readouts floating over the scene. When no product footage exists, use a real activity photograph plus one factual outcome readout rather than generic dashboard art.
- A bright, handmade counterpoint interrupts the clean interface language: place a monumental closing message inside a white 37.5px-radius panel over saturated painted tapestry. Recreate the textured surround with layered paint-like shapes when original artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Bright lime | `#9fe870` | `--color-lime` | background, action, accent, text | Opening field, primary actions on light surfaces, and highlighted text on forest. |
| Forest | `#163300` | `--color-forest` | text, background, action, link | Primary branded ink, dark capsules and reversed cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near black | `#0e0f0c` | `--color-ink` | text | Body-section display headings and strong labels on white. |
| Charcoal | `#454745` | `--color-body` | text | Paragraphs and secondary explanatory text. |
| Control grey | `#868685` | `--color-muted` | border, text | Inset field edges and inactive control labels. |
| Soft edge | `#e2e2e2` | `--color-rule` | border | Visible near-black at 12% over white; hairline dividers and QR panel outlines. |
| Pale sage wash | `#ecefeb` | `--color-wash` | background, surface | Visible forest at 8% over white; support bands, footer and tinted feature cards. Feature cards use the closely related 7.843% overlay. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default body canvas, demonstration panels and reversed enterprise text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| business-focused dark sections | Light mint | `#e2f6d5` | `--color-mint` | text, surface, action | Reversed headlines, light buttons and alternating testimonial cards. |
| enterprise integration stories | Deep green stage | `#111f06` | `--color-deep-stage` | background | Contained technical integration callout. |

## Typography

- **Wise Sans** — Monumental headings and selected oversized numbers. Very heavy, compact, irregularly lively sans with a tightly packed uppercase silhouette. OpenType features: "calt". If unavailable, use **Barlow Condensed**. Use weight 900; adjust line breaks to preserve the compact block silhouette. Font stack: "Wise Sans", "Barlow Condensed", Inter, sans-serif.
- **Inter** — Supporting headings, body copy, navigation, actions and captions. Direct, highly legible grotesk with a generous x-height; semibold headings have distinctly tighter tracking than body copy. OpenType features: "calt". Font stack: "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Wise Sans | 900 | 89.1px | 0.85 | normal | size clamp(5.375rem, 4.28571rem + 1.42857vw, 6rem) | Opening promise, major proof statements and closing line; render as uppercase lettering. |
| chapter | Wise Sans | 900 | 58.5px | 0.85 | normal | size clamp(3.5rem, 2.62857rem + 1.14286vw, 4rem) | Primary section headings, usually short uppercase blocks. |
| heading | Inter | 600 | 45.5px | 57px | -0.03em | size clamp(2.625rem, 1.42679rem + 1.57143vw, 3.3125rem) | Sentence-case explanatory chapters and directory headings. |
| card-heading | Inter | 600 | 24.6px | 32px | -0.015em | size clamp(1.5rem, 1.28214rem + 0.28571vw, 1.625rem) | Feature card titles. |
| lead-bold | Inter | 600 | 20px | 1.4 | 0.005em | size clamp(1.125rem, 0.58114rem + 0.87719vw, 1.25rem) | Opening supporting copy, benefit titles and testimonial quotations. |
| lead | Inter | 400 | 20px | 1.4 | 0.005em | size clamp(1.125rem, 0.58114rem + 0.87719vw, 1.25rem) | Section introductions. |
| body | Inter | 400 | 18px | 26px | 0.01em | size clamp(1rem, 0.45614rem + 0.87719vw, 1.125rem) | Paragraphs, feature details and footer links. |
| body-bold | Inter | 600 | 18px | 26px | 0.01em | size clamp(1rem, 0.45614rem + 0.87719vw, 1.125rem) | Footer group headings and short strong statements. |
| navigation | Inter | 600 | 18px | 26px | -0.006em | fixed | Top-level navigation controls; visible text can use the compact action recipe inside the control. |
| action | Inter | 600 | 16px | 1.5 | -0.011em | fixed | Button labels and compact navigation text. |
| caption | Inter | 400 | 16px | 1.5 | 0.005em | fixed | Supporting annotations and small explanatory paragraphs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| purpose-led editorial openings | manifesto | Wise Sans | 900 | 105.4px | 0.85 | normal | size clamp(6rem, 2.73214rem + 4.28571vw, 7.875rem) | Oversized uppercase declaration inside a contained forest panel. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Display lettering is chunky and close vertically without artificially negative letter spacing. Keep uppercase display blocks separate from sentence-case Inter explanations.
- Inter headings tighten to -0.03em at 45.5px and -0.015em at 24.6px; body instead opens to 0.01em. Do not apply a single tracking value throughout.
- Use a 604px centered supporting column beneath a wider display block. Most introductions need only two or three lines; preserve deliberate headline line breaks.

## Layout

**Density:** Airy at section scale and compact within controls; wide media and large words carry more weight than dense prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact control insets. |
| 9.4px | Small icon-to-label gaps and footer link padding. |
| 14.1px | Gap between neighboring actions. |
| 18.8px | Heading-to-paragraph gaps and benefit-row vertical padding. |
| 24px | Button horizontal padding. |
| 28.2px | Card grid gaps and medium card insets. |
| 37.5px | Card vertical padding and paragraph-to-action separation. |
| 56.3px | Standard section vertical padding and separation before large media. |
| 75.1px | Contained statement-panel padding. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 100px. Centered desktop content frame; at 1440px viewport its working width is 1240px. Footer and navigation use a closely related 1252px working width with 93.8px side margins.
- **intro-column**: max width 604px. Centered supporting text and compact final calls.
- **statement-column**: max width 840px. Broad editorial statements inside contained stages.
- **feature-grid**: 3 columns · gap 28.2px. Equal cards approximately 395px wide within the marketing container.
- **split-chapter**: 2 columns · gap 37.5px. Two approximately 555px columns separated by an additional narrow spacer; alternate photo and text sides. Portrait media is typically 555px × 739px.
- **footer-columns**: 3 columns · gap 56.3px. Three approximately 380px navigation columns with groups stacked vertically.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 9999px (pill) |
| cards-and-media | 28.2px |
| statement-panels | 37.5px |
| qr-panel | 18.8px |
| icon-discs | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| comparison-panel | `0px 6px 20px 0px rgba(0,0,0,0.08)` | One raised interactive comparison panel; ordinary content cards remain flat. |

### Surfaces

#### Canvas · level 0

**Use:** Default long-form body.

**CSS:** `background: #ffffff; color: #454745`

#### Lime field · level 0

**Use:** Default opening and occasional high-energy inset story.

**CSS:** `background: #9fe870; color: #163300`

**Transfer:** Use broad uninterrupted color rather than a gradient behind the opening.

#### Sage band · level 0

**Use:** Comparison, directory and footer backgrounds.

**CSS:** `background: rgba(22,51,0,0.08)`

**Observed:** A pale green-grey tint, not beige or blue.

#### Tinted feature card · level 1

**Use:** Equal-weight capability tiles on a white body.

**CSS:** `background: rgba(22,51,0,0.07843); border-radius: 28.2px; padding: 37.5px 28.2px; box-shadow: none`

**Observed:** The tint sits over a white base. Cards are flat and softly bounded without a visible outline.

#### Forest card · level 1

**Use:** Testimonial and reverse-content cards.

**CSS:** `background: #163300; color: #9fe870; border-radius: 28.2px; padding: 28.2px; box-shadow: none`

#### White statement panel · level 1

**Use:** Large inset closing call over a tapestry surround.

**CSS:** `background: #ffffff; border-radius: 37.5px; padding: 75.1px; overflow: hidden`

**Observed:** Broad opaque white center leaves the textured surround visible around all edges.

#### Technical stage · level 1

**Only for:** enterprise integration stories

**Use:** Monumental integration callout beneath an isolated graphic.

**CSS:** `background: #111f06; color: #ffffff; border-radius: 37.5px; padding: 75.1px 56.3px`

#### Dark business field · level 0

**Only for:** business-focused product narratives

**Use:** Opening, multi-feature chapter and later audience/pricing stories.

**CSS:** `background: #163300; color: #e2f6d5`

**Observed:** Use pale mint headlines and light capsule actions. The footer adds a 10% white wash over forest rather than becoming a black block.

## Components

### Primary button

**Use:** Primary action on white or pale sage.

**CSS:** `background: #9fe870; color: #163300; border: 1px solid #9fe870; border-radius: 9999px; padding: 11px 24px; height: 48px; min-width: 200px; box-sizing: border-box`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.011em

**Observed:** Centered label, generally no arrow. Paired actions use a plain text or outline alternative rather than two equal filled buttons.

**States:** Declared: hover background and border #65cf21 with forest text; focus-visible forest outline 2px with 2px offset; active matches hover.

### Reversed button

**Use:** Main action on the bright opening.

**CSS:** `background: #163300; color: #9fe870; border: 1px solid #163300; border-radius: 9999px; padding: 11px 24px; height: 48px; min-width: 200px; box-sizing: border-box`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.011em

**Observed:** The enterprise light-canvas variant uses white text on forest; dark business sections use mint-filled actions with forest text.

**States:** Declared: hover and active background and border #0e0f0c, lime text retained; focus-visible forest outline 2px with 2px offset.

### Outline button

**Use:** Secondary exploration beneath feature cards.

**CSS:** `background: transparent; color: #163300; border: 1px solid #163300; border-radius: 9999px; padding: 11px 24px; height: 48px; box-sizing: border-box`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.011em

**Observed:** Same capsule silhouette as the primary action; widths fit the label.

**States:** Declared: hover and active background and border #65cf21; focus-visible forest outline 2px with 2px offset.

### Navigation control

**Use:** Compact audience switching in a 76px header.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 8px 12px; border-radius: 9999px; color: #163300`

**Text style:** `navigation` — Inter 600 · 18px/26px · tracking -0.006em

**Observed:** Logo and three audience links cluster on the left; locale, help, login and a smaller filled signup capsule cluster on the right. Header inherits its opening color.

**States:** Declared: hover uses rgba(22,51,0,0.2) on the bright theme; focus-visible forest outline 2px with 2px offset.

### Feature card

**Use:** Three-way capability overview.

**CSS:** `display: flex; flex-direction: column; align-items: center; background: rgba(22,51,0,0.07843); border-radius: 28.2px; padding: 37.5px 28.2px; overflow: hidden; text-align: center`

**Text style:** `card-heading` — Inter 600 · 24.6px/32px · tracking -0.015em

**Observed:** Small isolated product cutout at top, title, supporting body, checked fact link, and Outline button aligned near the base. Cards are approximately 395px × 533px with a 288px inner content width.

**Transfer:** Use one concrete object or readout per tile, not a wall of miniature interfaces.

### Benefit row

**Use:** Trust and capability explanations alongside portrait media.

**CSS:** `display: flex; border-top: 1px solid rgba(14,15,12,0.12); padding: 18.8px 0px`

**Text style:** `lead-bold` — Inter 600 · 20px/1.4 · tracking 0.005em

**Observed:** A 48px circular icon holder precedes a title and short body explanation; the title/body gap is about 4.7px. Several rows share a single text column.

**Transfer:** Keep each row to one distinct reassurance and give it a recognizable functional icon.

### Testimonial card

**Use:** Human proof in a horizontal carousel.

**CSS:** `display: flex; flex-direction: column; background: #163300; border-radius: 28.2px; padding: 28.2px; color: #9fe870`

**Text style:** `lead-bold` — Inter 600 · 20px/1.4 · tracking 0.005em

**Observed:** Quote above attribution and a capsule action, with small circular portrait or locale marker. Cards extend past the right content boundary. Business cards alternate forest and mint with staggered top edges; editorial quote-only cards use pale sage.

**Transfer:** Keep generous vertical breathing room instead of shrinking every card to fit a row.

### QR handoff panel

**Use:** Desktop-to-mobile conversion inside the closing statement panel.

**CSS:** `display: flex; align-items: center; border: 1px solid rgba(14,15,12,0.12); border-radius: 18.8px; padding: 9.4px`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.011em

**Observed:** Short label sits beside the QR square; store badges sit separately beneath. Overall panel is about 225px wide.

**Transfer:** For non-app products, use an equally compact useful handoff such as a signup capsule rather than an irrelevant QR code.

### Footer navigation

**Use:** Substantial practical ending after the final marketing call.

**CSS:** `background: rgba(22,51,0,0.08); color: #163300`

**Text style:** `body` — Inter 400 · 18px/26px · tracking 0.01em

**Observed:** Three columns of grouped links, semibold group labels, then a divider, brand mark on the left and social icons on the right. A lower three-column legal-link grid precedes copyright and compact regulatory text. Business uses pale mint text over a 10% white wash on forest.

**Transfer:** Preserve the deliberate two-stage ending: evocative final marketing call followed by a useful dense directory.

### Amount field

**Only for:** interactive calculators and comparisons

**Use:** Primary numeric entry in a functional product demonstration.

**CSS:** `height: 72px; padding: 0px 24px; border-radius: 9999px; box-shadow: 0px 0px 0px 1px #868685 inset`

**Observed:** A small label sits above a large rounded amount control; currency selectors are separate neighboring capsules.

**Transfer:** Use only when visitors can meaningfully enter a quantity; do not replicate a finance calculator as decoration.

## Imagery and graphics

### Everyday activity portraits

**Use:** Large proof scenes and alternating capability chapters.

**Observed:** Warm, natural-looking photos show people using a phone at home, collaborating at a table or working in a real shop. Portrait frames are roughly three-quarters as wide as tall, with 28.2px rounded corners. Clothing, plants, brick and wood add saturated local color without tinting the whole image green. White pill readouts float over the activity.

**Transfer:** Photograph a genuine moment of use in a lived-in environment. If footage is unavailable, a still photograph plus one clean factual readout is the minimum equivalent.

### Floating outcome capsules

**Use:** Signature proof device layered over photography and demonstration media.

**Observed:** Opaque white, fully rounded labels carry a compact symbol or circular avatar and a short outcome or amount. They appear as small useful receipts, not full windows; some stack with slight offsets.

**Transfer:** Reduce the product to one meaningful result and attach that result to the moment it enables.

**Build:** Use a white inline-flex capsule with 9999px radius, 12px 16px padding, forest text and a 32px circular symbol at its leading edge. Position it over the lower or middle part of a rounded photograph without covering the face; for a stack, offset two subdued white capsules behind the main one by 16px vertically and 12px horizontally.

### Painted tapestry surround

**Use:** Signature colorful surround for a large white conversion or update panel.

**Observed:** Dense painterly collage, with smeared brush texture, translucent layers, rough blocks and faint geometric or architectural traces. One treatment is cyan, lavender and hot pink; others favor leaf green, yellow, orange and red. The pattern frames the clean white center and never becomes a text background.

**Transfer:** Make a new abstract collage in the same handmade spirit. A textured layered surround is required; a smooth rainbow gradient alone loses the material contrast.

**Build:** Create an SVG covering the whole band. Layer broad irregular polygons and dry-brush-like paths at opposing diagonals, using vivid cyan, violet and pink or green, yellow and orange. Add translucent overlapping copies at 0.2–0.5 opacity, then a fine fractal-noise texture using feTurbulence and a low-opacity multiply layer. Keep marks at several scales, with large color fields behind smaller scraped streaks. Overlay an opaque white panel with 37.5px corners and approximately 94px side gutters so texture remains at the perimeter.

### Tactile green symbols

**Only for:** trust, pricing and purpose-led editorial stories

**Use:** Large isolated illustrations that make abstract reassurance tangible.

**Observed:** Three-dimensional lock, headset, check mark, globe and card forms carry mottled painted green skins with yellow and turquoise variations. Strong directional light reveals rounded volume and surface grain. Objects float on white, warm pale neutral or forest backing, with little surrounding decoration.

**Transfer:** Choose a single object that explains the new benefit, not the original service. Minimum equivalent: a bold dimensional silhouette with painterly texture and clear light/shadow, rather than an untextured stock icon.

**Build:** Draw a simple solid symbol in SVG with a thick silhouette and one clear cutout. Duplicate the shape offset diagonally to imply depth, shade the side forest green, and fill the face lime. Clip overlapping semi-transparent green/yellow patches and fractal-noise texture to the silhouette; use a restrained directional highlight and soft contact shadow. For purpose-led openings, overlap a flat product card with a textured globe-like circle above the top edge of the dark statement panel.

### Desk-level product still life

**Only for:** business and enterprise product narratives

**Use:** Feature media that anchors software in the working world.

**Observed:** Phones and cards sit among keyboards, calculators, pens, headphones and craft tools on pale green desks. Oblique overhead framing and directional sunlight create believable soft shadows; green product objects connect the scene to the palette.

**Transfer:** Stage the new product or a device showing one key screen among tools belonging to its audience. Keep the scene focused on one central object.

### Icons

**Observed:** Small functional SVG symbols are primarily single-color forest or near-black, with common 24px and 16px sizes. Simple bank, shield, clock, globe and arrow silhouettes sit inside 48px or 56px circular holders. Social icons are solid brand-shaped marks.

**Transfer:** Use a consistent simple functional icon family with similar visual weight. Prefer a single dark symbol on a pale disc over multicolored pictograms; reserve dimensional painted art for larger editorial illustrations.

## Section recipes

How recurring sections are built.

### First screen: Bright working-object opening

**Observed:** A 76px header merges into a full-width Lime field. Centered ratings lead into a two-line uppercase display block at 89.1px/0.85; the visible lettering spans roughly 820px rather than filling the whole 1240px container. A 604px-wide semibold support paragraph follows after 18.8px, then a 200px Reversed button after 37.5px. A white, softly rounded 515px demonstration panel starts 56.3px below the action. Layers are flat lime, dark type, dark capsule, then the white functional object. Within the first 900px, the header, ratings, complete promise/support/action and the upper part of the demonstration are visible; its remaining details continue below the fold.

**Transfer:** Keep the centered promise-over-object structure for new landing pages. Replace the calculator with a useful compact representation of the new product, showing one real input/result. Enterprise openings use white with a wide rounded film below the action; business openings reverse to forest and mint with desk-level product imagery. Purpose-led editorial openings use a contained forest panel with a textured object overlapping its top edge.

**Avoid:** Do not turn the default into a left-aligned split hero, stretch the demonstration across the whole viewport, or compress the entire demonstration into the first screen.

**Text style:** `display` — Wise Sans 900 · 89.1px/0.85

### Centered heading pair

**Observed:** A chapter headline sits above a centered lead paragraph with an 18.8px gap. A Primary button follows after roughly 37.5px. The next major object or card row is separated by 37.5px–75.1px.

**Transfer:** Use short declarations for chapter-level promises and sentence-case heading text for detailed explanations.

**Text style:** `chapter` — Wise Sans 900 · 58.5px/0.85

### Alternating tangible chapter

**Observed:** Portrait photo or product scene occupies one approximately 555px column; the other holds a chapter or sentence-case heading, lead paragraph, Benefit rows and a conversion capsule. Media and text are vertically balanced; successive chapters change sides.

**Transfer:** Explain one job per chapter. Preserve the visible connection between an outcome capsule and an actual activity rather than presenting interface internals alone.

**Text style:** `heading` — Inter 600 · 45.5px/57px · tracking -0.03em

### Three useful objects

**Observed:** Three equal Feature cards sit 28.2px apart. Small isolated objects at their tops are followed by card titles and concise copy; fact links and Outline buttons form a consistent lower edge.

**Transfer:** Group three independent capabilities or assurances. Give each a different useful object but maintain shared framing and image scale.

**Text style:** `card-heading` — Inter 600 · 24.6px/32px · tracking -0.015em

### Transparent comparison

**Observed:** Sage band supports a centered chapter heading and explanation, then a raised white comparison panel around 1092px wide. Rounded horizontal result bars use pale sage for alternatives and lime for the emphasized result; labels and quantities remain easy to compare.

**Transfer:** Use verifiable comparisons relevant to the new product. Preserve the relative-length bars and explicit values rather than turning this into a generic pricing-card grid.

### Human proof carousel

**Observed:** A display heading and short introduction sit beside or above Testimonial cards. Approximately 392px-wide cards continue beyond the right container edge; circular previous/next controls accompany the heading. Alternating and staggered cards make the business variant more conversational.

**Transfer:** Use real quotations with plain attribution and one clear action. Keep a visible next-card edge to communicate continuation.

**Text style:** `display` — Wise Sans 900 · 89.1px/0.85

### Painted closing call

**Observed:** A Painted tapestry surround frames the White statement panel. Centered ratings, monumental display text, QR handoff panel and store badges make a practical final conversion scene. Simpler editorial endings use just a monumental closing line and a lime capsule within the same white-over-paint construction.

**Transfer:** Make the closing line memorable and specific to the new product. Preserve the contrast between tactile saturated perimeter and uncluttered white center; use a direct action instead of app badges when appropriate.

**Text style:** `display` — Wise Sans 900 · 89.1px/0.85

### Practical directory ending

**Observed:** Footer navigation follows the last marketing call, sometimes after a white disclaimer card on sage. Three link columns lead to a separated logo/social row, legal-link grid, copyright and explanatory paragraphs. The default ending is pale sage even when its outer wrapper is white; the business variant is a lighter forest wash.

**Transfer:** Support exploration after conversion without inventing an additional hero. Keep the legal material visually subordinate and the links usable.

**Text style:** `body` — Inter 400 · 18px/26px · tracking 0.01em

### Monumental ruled statistics

**Only for:** purpose-led editorial narratives

**Observed:** Very large display statements occupy full-width white rows about 253px high. Each statistic has a small plain-language qualifier beneath and a thin near-black rule across the content width. The treatment is typographic, not boxed into metric tiles.

**Transfer:** Choose a few consequential measures of progress and let each read as a statement in its own right.

**Text style:** `display` — Wise Sans 900 · 89.1px/0.85

### Enterprise proof band

**Only for:** enterprise product narratives

**Observed:** Forest field divides into an introductory heading/paragraph/white action at left and a two-by-two grid of facts at right. Circular icon holders precede each fact; both labels and explanatory copy are white.

**Transfer:** Demonstrate scale, coverage, reliability or operational maturity using actual substantiated measures.

**Text style:** `heading` — Inter 600 · 45.5px/57px · tracking -0.03em

### Technical monument and resource mosaic

**Only for:** enterprise integration stories

**Observed:** A contained Technical stage pairs an isolated object with an uppercase display promise, centered support and a white capsule. Later, sage backing holds alternating two-thirds photo cards and one-third white text cards with 28.2px corners; photo cards use a dark overlay and bottom-aligned white copy.

**Transfer:** Separate the technical integration promise from practical next steps such as documentation, events or reports. Use populated, useful resource cards rather than repeating identical sales CTAs.

**Text style:** `display` — Wise Sans 900 · 89.1px/0.85

## Page flow

**Storyline:** Clear promise → tangible demonstration → explicit value proof → useful capability chapters → human and operational reassurance → memorable conversion scene → practical directory.

### Consumer-facing product landing page

1. **Promise and demonstration** — Bright centered opening with ratings and a compact working calculator.
2. **Value proof** — Practical benefit strip and activity film lead into an explicit visual comparison.
3. **Capability chapters** — Three object-led feature cards, portrait trust chapter, testimonial carousel and an adjacent-audience product story.
4. **Closing conversion** — White monumental app-handoff panel over painted color.
5. **Coverage and ending** — Tabbed directory of destinations, disclaimer panel and pale-sage grouped footer through the final legal paragraphs.

**Transfer:** Use the same movement from promise to usable proof, then specific capabilities and a practical ending; choose the amount of detail the new product requires.

### Enterprise infrastructure marketing

1. **Promise** — White centered display opening and wide rounded film.
2. **Institutional proof** — Partner logo grid followed by a forest fact band.
3. **Solution explanation** — Alternating audience chapters and a tabbed product panel, followed by delivery-support cards.
4. **Assurance and integration** — Regulatory reassurance with a tactile symbol, then a contained technical monument.
5. **Next steps and ending** — Photo/text resource mosaic and a pale-sage grouped footer; a small centered contact capsule persists near the lower edge.

**Transfer:** Keep the brand's display and rounded media while giving sentence-case headings and proof more room. End with useful next-step resources rather than consumer app acquisition.

### Business account or multi-capability product landing page

1. **Promise** — Forest/mint opening, two action priorities and a wide desk-level product scene; optional announcement strip above navigation.
2. **Product demonstration** — Trust strip, functional amount panel and local-receiving activity scene.
3. **Capability chapters** — Long forest chapter with alternating portrait media, tangible objects and pale capsule actions.
4. **Reassurance and relevance** — Three protection cards, staggered customer quotes and photographic audience cards.
5. **Objection handling** — Isolated painted product object introduces pricing; ruled accordion rows answer practical questions.
6. **Closing and ending** — Painted app-handoff call, disclaimers, then mint-on-forest footer through social, legal and final explanatory text.

**Transfer:** Use the dark business theme for a broad professional product with several work modes, not as a random color switch within a consumer opening.

### Purpose-led company or progress narrative

1. **Declaration** — Textured object overlaps a contained forest manifesto panel.
2. **Quantified proof** — Large ruled statistical statements on white.
3. **Principles and progress** — Tabbed pillars, alternating detailed chapters and simple graphic measures.
4. **Activity and human proof** — Dark update carousel, editorial campaign cards, painted progress call and staggered pale quote cards.
5. **Origin and invitation** — Lime inset story with a portrait pair, then a concise white-on-tapestry closing invitation.
6. **Ending** — Pale-sage multi-column footer, social row, legal links and full final explanatory paragraphs.

**Transfer:** Use this mode to explain a product's ambition and tangible progress. Separate large declarations from smaller supporting mechanisms and show the people behind the work.

## Writing

Confident, helpful and a little defiant about unnecessary complexity. Friendly everyday language explains specific outcomes; measurable claims and practical caveats give the optimism substance.

**Do not copy:** Do not reuse Wise names, logos, proprietary artwork, customer quotations, partner marks, regulatory claims, product rates, audience counts, savings or speed figures. Replace all examples with truthful content belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the company when explaining commitments or mechanisms. Actions begin with straightforward verbs.
- **Rhythm:** Short, emphatic headline blocks contrast with explanatory sentences of ordinary conversational length. Brief fragments can form a punchy three-part declaration; paragraphs usually stay to two or three sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State the core job and its practical advantage, without abstract category jargon. | 6–10 words | “The fast way to send money abroad”<br>“The business account for going global” |
| Section headline | A direct reassurance or invitation, often an everyday phrase. | 3–7 words | “Safe at every step”<br>“Make your money do more” |
| Supporting line | Explain what visitors can do, then contrast the experience with a familiar baseline. | One or two short sentences | “Spend, receive and manage money internationally, as easily as you do at home.” |
| Primary action | Verb plus the thing or next step; be literal rather than clever. | 2–5 words | “Open an account”<br>“Get in touch”<br>“See our security” |
| Manifesto | Parallel fragments with a concrete benefit in each. | Three compact clauses | “MIN FEES. MAX EASE. FULL SPEED.” |
| Mechanism explanation | Name the action that makes the benefit possible; avoid unsupported reassurance. | One concise sentence | “Connect directly with banks, cutting out the middlemen so you pay less” |

**Words and phrasing to use:** easy; fast; clear; get; send; manage; no hidden; here’s how; at every step

**Avoid:** revolutionary synergy; unparalleled excellence; unlock your potential; best-in-class everything; excessive exclamation marks

**Rules:**

- Lead with a job or benefit, then explain the mechanism that makes it credible.
- Attach qualifications to the relevant claim and keep the main sentence readable.
- Use gentle oppositional phrasing to identify a real friction, not to belittle the reader.
- Reserve all-uppercase presentation for display statements; supporting paragraphs and action labels stay sentence case.

## Do's and Don'ts

### Do

- Keep the default opening one continuous lime field through the header and demonstration lead-in.
- Use 0.85 line height for heavy display type and 26px line height for 18px explanatory body text.
- Hold feature grids to three equal cards with 28.2px gaps at the desktop reference width.
- Keep ordinary cards flat; concentrate the soft 0px 6px 20px shadow on the interactive comparison panel.
- Pair portrait media with a short set of ruled benefit rows, each with a 48px icon holder.
- Use a real action label in a 48px capsule and allow a 37.5px pause after explanatory copy.
- Carry the final call into a substantial grouped footer, including the separated social and legal rows.

### Don't

- Do not make every headline an Inter semibold heading; the dense 900-weight display silhouette is essential.
- Do not turn 28.2px rounded cards into 8px dashboard tiles.
- Do not use the lime accent as ordinary paragraph text on white; forest and charcoal carry reading text.
- Do not add glows, glass cards or heavy shadows across the marketing body; its surfaces are mostly opaque and flat.
- Do not use a soft generic gradient as the entire painted surround; it needs visible layered texture.
- Do not cover the whole photograph with interface windows; use compact outcome capsules and keep people legible.
- Do not make the whole page forest by default; prolonged dark chapters belong to the professional and editorial variants.
- Do not replace the large ruled editorial statistics with a row of tiny colored KPI boxes.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color/background transitions of 0.15s ease-in-out. Header controls declare color/background/border transitions of 350ms cubic-bezier(0.8,0.05,0.2,0.95).
- Several scene elements declare transform/opacity reveals lasting 1000ms with ease. Flags declare a 0.6s cubic-bezier(.34,1,.64,1) reveal; an arrow has a declared 2s ease-in-out pulse after 0.6s.
- Large films have small circular play/pause controls; horizontal testimonial groups have previous/next controls.

**Transfer:**

- Use compact interaction feedback rather than moving the whole layout. Keep scene-level motion attached to a meaningful object or factual readout.
- Retain explicit play/pause controls for repeating narrative films and visible controls for card continuation.

**Unknown:**

- Exact reveal triggers, complete scene choreography and behavior under reduced-motion preferences are not established.

### Responsive

**Observed:**

- Declared width boundaries include 480px, 600px, 768px, 840px, 992px, 1160px, 1200px and 1440px.
- Display and body sizes use the clamp formulas listed in the type recipes.

**Transfer:**

- As design guidance, stack the alternating portrait/text chapters and feature cards when their columns no longer fit; preserve the promise-over-object opening and the capsule silhouettes.
- Keep the painted surround visible as a narrow perimeter around the closing panel. Replace desktop QR handoff with a direct relevant action on a device that cannot scan its own screen.

**Unknown:**

- Only desktop layouts are established; exact mobile column counts, navigation behavior, side gutters and line breaks are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
