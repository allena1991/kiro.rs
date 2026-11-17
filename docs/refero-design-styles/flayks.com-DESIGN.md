# Flayks — elastic poster theatre

## Overview

A dark, exuberant visual language that pairs towering condensed grotesk lettering with tiny, widely tracked uppercase narration. Forest green, coral and lavender frame glossy mint sculpture, vivid digital art, photography and nested website presentations. It suits creative tools, ambitious digital products and image-led launches, alternating oversized editorial gestures with compact outlined information.

### Essentials

- Headlines behave like cut-up posters: 518.4px bold condensed capitals with 1 line height, overlapping rows and selected slanted letters, split across opposite edges.
- The opening is a full-bleed typographic landscape, not a centered pitch: green canvas, coral lettering, a floating glossy identity object and a tilted 360×486px media stack; the statement continues below the first screen.
- Color lives in letters and media rather than a rainbow of cards: forest green carries the main narrative, warm charcoal carries the long showcase, coral marks the opening and closing, lavender marks chapter titles and thin outlines.
- Actions are small rectangular stamps against monumental type: transparent coral 1px outlines, 6px corners, 48px height and 32px condensed uppercase lettering; supporting copy uses 14px sans capitals with 0.1em tracking.
- Proof is staged as an image within an image: a 763px-wide live-looking presentation floats inside a 1090×674px rounded photographic or illustrated scene, with a neighboring text slide peeking beyond the right edge.
- Include the sculptural counterpoint and the monumental closing invitation: a glossy inflated identity object overlaps flat type, while the ending pairs a lavender outlined contact plaque with a fine-line green-and-lavender graphic. Use an original inflated symbol and generated line network when bespoke artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Forest green | `#00381c` | `--color-canvas` | background, surface | Main canvas, transparent-looking cards and the contact plaque. |
| Poster coral | `#ff8370` | `--color-coral` | text, border, action, accent | Opening and closing statements, compact subheads, action outlines and keyboard focus. |
| Lilac ink | `#d1adff` | `--color-lavender` | text, border, accent | Chapter lettering, capability symbols, proof labels, contact lettering and hairline frames. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach cream | `#ffe0ce` | `--color-cream` | text | Paragraphs, captions, metrics and descriptive headings. |
| Muted cream edge | `#546f57` | `--color-soft-rule` | border | Visible cream at 33% opacity over forest green; use the same cream alpha for inset showcase edges, where the darker backing changes its visible tone. |
| Warm charcoal | `#272221` | `--color-showcase` | background, surface | The long media showcase and its neighboring descriptive panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| featured collaborations | Deep electric blue | `#1e1779` | `--color-feature-blue` | background, surface | An isolated immersive partner or featured-product panel. |

## Typography

- **Mango Grotesque** — All poster lettering, descriptive headlines, metrics and stamped actions. Extremely condensed, heavy grotesk with tall vertical strokes; occasional slanted letters disrupt otherwise upright words. If unavailable, use **Anton**. Use 400 as the heavy visual cut; tune width to preserve the narrow poster silhouette. Font stack: "Mango Grotesque", "Anton", Impact, Helvetica, Arial, sans-serif.
- **Nohemi** — Narration, captions, proof chips and information labels. Clean geometric sans, mostly regular, made technical by generous uppercase tracking. If unavailable, use **Outfit**. Use 400 and 600 with 0.1em tracking. Font stack: "Nohemi", "Outfit", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| poster | Mango Grotesque | 700 | 518.4px | 1 | normal, uppercase | Opening statement and enormous chapter markers. |
| closing | Mango Grotesque | 700 | 256px | 0.8 | normal, uppercase | Multiline closing invitation. |
| contact | Mango Grotesque | 700 | 97.2px | 1.2 | 0.02em | Lowercase salutation and email split across the contact plaque. |
| project-heading | Mango Grotesque | 700 | 93.6px | 0.85 | 0.015em, uppercase | Descriptive headline inside a showcase text slide. |
| metric | Mango Grotesque | 500 | 88px | 0.85 | normal, uppercase | Tall counts with a directly attached multiplier suffix. |
| subheading | Mango Grotesque | 700 | 48px | 1 | 0.02em, uppercase | Capability group headings and compact editorial interludes. |
| action | Mango Grotesque | 700 | 32px | 0.85 | 0.025em, uppercase | Outline action stamps. |
| body | Nohemi | 400 | 18px | 1.35 | 0.1em, uppercase | Introduction, concluding support and proof-chip labels. |
| tile-label | Nohemi | 400 | 18px | 1.1 | 0.1em, uppercase | Bottom-aligned names in capability tiles. |
| caption | Nohemi | 400 | 14px | 1.35 | 0.1em, uppercase | Descriptions, status rail, social links and metric captions. |
| project-label | Nohemi | 600 | 14px | 1.35 | 0.1em, uppercase | Lavender name below each media stage. |

**Notes:**

- The extreme difference between poster lettering and 14–18px narration is the hierarchy; avoid filling the middle with conventional medium-sized headings.
- Keep wide tracking on the small sans but nearly none on the enormous display face. Tight 0.8–0.85 line heights belong to multiline closing and descriptive display roles.
- Selected individual letters lean independently. Preserve the word's readability rather than italicizing entire paragraphs.

## Layout

**Density:** Airy in the editorial chapters, dense inside proof and capability groups; oversized letterforms supply mass without increasing copy volume.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Separation between wrapped proof-chip rows. |
| 16px | Capability-grid gaps and tile side padding. |
| 20px | Main grid column gap and media-to-caption offset. |
| 48px | Distance between horizontally neighboring showcase slides. |
| 57.6px | Side inset of showcase text and action areas. |
| 64px | Main content side padding. |
| 72px | Gap between showcase articles and between metric rows. |
| 158.4px | Generous feature-panel breathing space. |
| 201.6px | Large editorial interlude and proof-cloud bottom spacing. |
| 244.8px | Breathing room surrounding the recognition chapter. |

### Containers and grids

- **main-grid**: max width 1800px · 12 columns · gap 20px · side padding 64px. Centered outer grid for most content; desktop inner width is 1312px.
- **poster-grid**: max width 1800px · 12 columns · gap 20px · side padding 14.4px. Near-edge-to-edge word compositions and the narrow persistent status rail.
- **showcase-stage**: max width 1090px · gap 48px. Main stage centered on the page, with the next equally sized descriptive slide visible beyond its right edge.
- **capability-grid**: 4 columns · gap 16px. Four by two tiles occupy roughly two thirds of the content width; an outlined narrative and list panel occupies the remaining third.
- **proof-grid**: 5 columns · gap 20px. Five columns of unboxed metrics with 72px between rows.
- **description**: max width 420px. Compact uppercase paragraphs within large image-adjacent panels.

## Corner radius

| Element | Radius |
| --- | --- |
| tiles-and-stamps | 6px |
| media-and-contact | 10px |
| social-links | 4px |
| indicator | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| nested-media | `0px 0px 112px 0px rgba(0, 0, 0, 0.2)` | Broad soft separation beneath the centered presentation inside each image stage. |
| media-stage | `0px 62px 25px 0px rgba(0,0,0,0.01), 0px 35px 21px 0px rgba(0,0,0,0.05), 0px 16px 16px 0px rgba(0,0,0,0.09), 0px 4px 9px 0px rgba(0,0,0,0.1)` | Subtle layered depth under large image frames. |

### Surfaces

#### Forest canvas · level 0

**Use:** Default editorial background.

**CSS:** `background: #00381c; color: #ffe0ce`

#### Charcoal showcase · level 0

**Use:** Continuous backing through the media-led proof region.

**CSS:** `background: #272221`

**Observed:** The entire visible environment shifts from green to warm charcoal, not merely the image cards.

**Transfer:** Use this darker chapter to hold diverse product media together.

#### Outlined panel · level 1

**Use:** Capabilities, social rail and proof chips.

**CSS:** `background: transparent; border: 1px solid #d1adff; border-radius: 6px`

**Observed:** Fine lilac outlines with no elevation or contrasting fill.

**Transfer:** Use empty green interiors to keep the outlined information light.

#### Showcase text panel · level 1

**Use:** The descriptive slide next to a media stage.

**CSS:** `background: #272221; border-radius: 10px; box-shadow: inset 0px 0px 0px 1px rgba(255,224,206,0.33); overflow: hidden`

#### Immersive feature · level 1

**Only for:** featured collaborations

**Use:** A single exceptional collaboration or secondary offer.

**CSS:** `background: #1e1779; border-radius: 10px; padding-bottom: 72px`

**Observed:** Deep blue-tinted photography fills a tall panel with a pale centered identity and a large inset presentation; the bottom fades into blue.

**Transfer:** Reserve the color change for a meaningful editorial detour, not every feature.

## Components

### Outline action

**Use:** Main action accompanying a showcased product or story.

**CSS:** `display: inline-flex; align-items: center; background: transparent; color: #ff8370; border: 1px solid #ff8370; border-radius: 6px; height: 48px; padding: 6px 16px 0px`

**Text style:** `action` — Mango Grotesque 700 · 32px/0.85 · tracking 0.025em · uppercase

**Observed:** A compact text-only stamp, placed low within the descriptive panel; an inset coral pseudo-layer supports its animated treatment.

**States:** Declared: hover behavior not specified; focus-visible outline 1px dashed #ff8370.

### Capability tile

**Use:** Small named capabilities with visual symbols.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; border: 1px solid #d1adff; border-radius: 6px; padding: 16px 16px 12px; height: 260px`

**Text style:** `tile-label` — Nohemi 400 · 18px/1.1 · tracking 0.1em · uppercase

**Observed:** A lavender 56px abstract symbol sits at the upper left, with a cream label anchored to the bottom. The panel remains green.

**Transfer:** Assign one simple geometric motif to each capability.

### Proof chip

**Use:** A centered wrapping cloud of customer or ecosystem names.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #00381c; border: 1px solid #d1adff; border-radius: 6px; height: 56px; padding: 2px 21.6px 0px`

**Text style:** `body` — Nohemi 400 · 18px/1.35 · tracking 0.1em · uppercase

**Observed:** Text names replace logos. Content-width rectangles wrap into centered rows with 8px spacing; alternate faces carry short organization descriptors.

### Showcase description

**Use:** Narrative counterpart to each image-led stage.

**CSS:** `display: flex; flex-direction: column; background: #272221; border-radius: 10px; box-shadow: inset 0px 0px 0px 1px rgba(255,224,206,0.33); width: 1090px; height: 674px; overflow: hidden`

**Text style:** `project-heading` — Mango Grotesque 700 · 93.6px/0.85 · tracking 0.015em · uppercase

**Observed:** Headline and compact uppercase description occupy the upper area, with an Outline action near the bottom. Text is inset 57.6px sideways and 79.2px vertically; a two-column text grid uses a 48px gap.

### Contact plaque

**Use:** The dominant final contact action.

**CSS:** `display: flex; background: #00381c; color: #d1adff; border-radius: 10px; box-shadow: inset 0px 0px 0px 1px #d1adff; padding: 29.2px 24.3px 19.4px; height: 165px; overflow: hidden`

**Text style:** `contact` — Mango Grotesque 700 · 97.2px/1.2 · tracking 0.02em

**Observed:** Lowercase salutation and address sit on opposite sides of a broad plaque; a second offset outline gives the object shallow depth.

**Transfer:** Use a short email or equivalent direct action that fits the condensed face.

### Social strip

**Use:** Compact closing destinations below the contact plaque.

**CSS:** `display: flex; justify-content: center; gap: 4px; border: 1px solid #d1adff; border-radius: 6px; padding: 4px`

**Text style:** `caption` — Nohemi 400 · 14px/1.35 · tracking 0.1em · uppercase

**Observed:** A single outlined horizontal group spans the plaque's width. Individual links have small corner rounding and expand evenly across the strip.

### Social link

**Use:** Individual destination within the Social strip.

**CSS:** `display: flex; align-items: center; justify-content: center; color: #ffe0ce; border-radius: 4px; height: 46px; padding: 6px 4px 4px`

**Text style:** `caption` — Nohemi 400 · 14px/1.35 · tracking 0.1em · uppercase

**Observed:** Text-only destination with a lavender pseudo-layer behind it.

**States:** Declared: hover color #00381c and box-shadow inset 0 0 0 1px #d1adff; focus-visible outline 1px dashed #ff8370.

### Metric item

**Use:** Unboxed quantified proof.

**CSS:** `color: #ffe0ce`

**Text style:** `metric` — Mango Grotesque 500 · 88px/0.85 · uppercase

**Observed:** A tall count with a joined X suffix sits above a small uppercase caption. The five-column grouping has no dividers, icons or panel fills.

### Section dot rail

**Use:** Persistent navigation between major narrative chapters.

**CSS:** `display: flex; flex-direction: column; gap: 12px`

**Observed:** Six tiny markers line the left edge around viewport midpoint. Lavender fills identify current or visited chapters; pale outlined circles indicate upcoming destinations. The links expose concise section names.

**States:** Declared: hover opacity 0.5 on the ancestor for inactive destinations; focus-visible outline 1px dashed #ff8370.

## Imagery and graphics

### Inflated identity sculpture

**Use:** Signature foreground counterpoint to the flat typographic landscape; repeats at the close.

**Observed:** A glossy mint bubble-letter identity, with rounded swollen contours, bright softbox highlights and deep dark edge shadows, floats over the poster text. It is large at the opening and smaller as a persistent upper-left identity.

**Transfer:** Create an original short word or product symbol as an inflated object. A single polished inflated glyph is the minimum acceptable alternative.

**Build:** Convert original lettering or a simple symbol to rounded SVG contours; extrude and bevel in 3D or layer offset SVG shapes. Use a pale mint body, turquoise shaded lower-left edges, dark green contact shadows and narrow off-white highlights toward the upper right. Render on transparency; keep the object separate from the flat coral text.

### Tilted media deck

**Use:** Floating editorial object in the opening.

**Observed:** Several portrait image cards overlap in a loose fan. The foremost vivid false-color forest image has blue-violet shadows, mint foliage and orange details. Cards are 360×486px before rotation, with 10px corners and directional shadows.

**Transfer:** Use product outputs, material studies or original photographic details as saturated portrait cards; do not turn the deck into feature tiles.

**Build:** Stack three or four rounded portrait images absolutely with slightly different rotations and small offsets. Let the leading card lean roughly 6 degrees, preserve visible edges of the rear cards and add a soft directional black alpha shadow. Layer the deck across the giant text.

### Nested presentation stage

**Use:** Repeated large proof stories.

**Observed:** A centered rectangular website presentation floats above a full-frame thematic image: clouds and a red perspective grid, golden cinematic imagery, purple forest, teal craft details, footwear photography or violet architecture. The outer stage dominates the viewport; the inset occupies about 70% of its width and retains its natural interface colors.

**Transfer:** Pair an authentic product view with a related original photo or illustrated environment. Keep the outer backing expressive and the inset legible; use a designed product-output composition if no interface exists.

### Fine-line closing terrain

**Use:** Signature graphic beside the contact plaque.

**Observed:** A lavender street-network-like drawing recedes in perspective over dark green terrain, clipped inside a wide 10px rounded outline. It balances the typographic contact object rather than functioning as an embedded map.

**Transfer:** Use an original route, connection or contour network relevant to the product; a generated branching line field provides the same visual density.

**Build:** Draw an SVG network of irregular angular polylines: many thin lavender strokes at low opacity, with a few 2px stronger arterial routes. Place over forest green with subtly darker land contours; skew and compress the upper part into a shallow perspective plane, then clip to a 10px rounded rectangle.

### Icons

**Observed:** Capability symbols are abstract lavender shapes in 56×56px boxes: folded wedges, layered ellipses, pinwheels and petal crosses. Most are solid; a layered-ring symbol uses a 3.5px butt-ended stroke. Small lavender circles and a compact star-like mark support status and contact links.

**Transfer:** Choose simple filled geometric emblems, not multicolor app icons or a generic thin-line pictogram set. Preserve the upper-left placement and common square footprint.

## Section recipes

How recurring sections are built.

### First screen: Split-poster opening

**Observed:** The forest canvas is covered by two huge coral rows within the first 900px. The first short word group is pushed to opposite edges; the next fragment is anchored to the right with a long hyphen reaching left. The 518.4px Poster type uses 1 line height and rows overlap by 103.7px. Selected letters lean. In front, the Inflated identity sculpture overlaps the upper-left lettering and the Tilted media deck occupies the lower-left area, crossing the second row. A narrow cream status line spans the bottom with location left, availability toward the right and contact at the far right. The long headline continues below the fold; explanatory prose appears later inside the word composition, not above it. No large conventional CTA button is present in this first screen.

**Transfer:** Express the new product's defining category or promise as short words broken into opposing groups. Recreate the inflated identity and a deck of outputs when original media is unavailable. For a detail-page opening, use a shorter version of the same word-and-object composition with a compact explanatory inset.

**Avoid:** Do not shrink the whole promise into a tidy centered heading above a dashboard, or add a standard top navigation bar that displaces the poster.

**Text style:** `poster` — Mango Grotesque 700 · 518.4px/1 · uppercase

### Word landscape chapter

**Observed:** Huge lavender Poster lettering fills roughly two viewport-height rows, aligned alternately left and right with deliberate gaps inside words and selected slanted letters. The following information block returns to 64px side margins.

**Transfer:** Use brief chapter nouns or benefits that tolerate expressive line breaks. The typographic device can introduce whichever major content chapters the new page needs.

**Text style:** `poster` — Mango Grotesque 700 · 518.4px/1 · uppercase

### Image-led proof chapter

**Observed:** Charcoal showcase contains repeated centered 1090×674px Nested presentation stages with 10px corners. A Showcase description sits 48px to the right and intentionally peeks at the viewport edge. Below each stage, a lavender Project-label sits alongside 10px pagination dots; articles are separated by 72px.

**Transfer:** Use fewer, stronger stories if appropriate, while retaining the image-within-image construction and the adjacent descriptive-slide relationship.

### Capabilities and explanation

**Observed:** Coral Subheadings name two groups. Capability tiles form a four-column, two-row block on the left. An equally tall outlined panel on the right contains a short uppercase statement followed by five hairline-separated rows.

**Transfer:** Pair a visual capability taxonomy with a concise explanation or compatibility list. Keep symbols dominant at the top and labels at the foot of each tile.

### Immersive feature detour

**Observed:** A tall Immersive feature panel spans the inner content width, contrasting deep blue photographic atmosphere with a centered pale identity and a large inset presentation.

**Transfer:** Use as a scoped chapter for a distinct collaboration or featured offer rather than a default section background.

### Metrics and name cloud

**Observed:** An oversized lavender chapter marker precedes cream Metric items in a five-column, two-row unboxed grid. Another monumental title leads a centered support paragraph and a tightly wrapped cloud of Proof chips.

**Transfer:** Separate quantified evidence from named endorsements. Reuse either grouping only with authentic proof; retain the contrast between enormous chapter labels and compact information.

### Monumental contact ending

**Observed:** A three-line coral Closing statement stretches across the grid with selected slanted letters and an overlapping Inflated identity sculpture. A short cream Body paragraph is set to the left beneath the words. Fine-line closing terrain fills the lower-left panel; the Contact plaque sits to the right, with the Social strip aligned beneath it. A slim location, availability and scheduling rail ends the composition; there is no conventional multi-column footer.

**Transfer:** End with an expansive invitation and a tangible direct-contact object, balancing it with an original fine-line network. Use a product-relevant action and destinations, keeping the sculptural and typographic scale contrast.

**Text style:** `closing` — Mango Grotesque 700 · 256px/0.8 · uppercase

## Page flow

**Storyline:** Expressive identity and promise → immersive proof stories → capability explanation → quantified and named credibility → monumental invitation.

### An image-led marketing page that establishes a distinctive point of view before explaining the offer

1. **Promise** — A multi-screen word composition with a floating identity sculpture, output deck and compact introduction.
2. **Product demonstration** — Repeated nested media stages paired with adjacent descriptive slides.
3. **Editorial detour** — A compact discovery interlude leads into a contrasting immersive feature panel.
4. **Capability chapters** — Monumental chapter lettering gives way to outlined icon tiles and a technical explanation panel.
5. **Quantified proof** — Unboxed tall counts and tiny captions.
6. **Social proof** — An enormous title, centered support and a wrapping outlined name cloud.
7. **Closing call** — A coral invitation, inflated identity, fine-line terrain, oversized contact plaque and narrow social strip.

**Transfer:** Adapt the chapter order and story count to the product. Preserve the recurring shifts between huge type, expressive media and small outlined information rather than imitating a fixed section sequence.

## Writing

Confident, visually minded and personally engaged. Short editorial claims introduce concrete explanations; invitations are direct without sounding like aggressive sales copy.

**Do not copy:** Do not reuse Flayks' identity artwork, personal biography, client names, project names, email, award totals, proprietary imagery or claims as another product's assets or credentials. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First-person singular for the independent maker, impersonal descriptions for projects, and direct second-person language in the final invitation. A different company can use we without losing the conversational stance.
- **Rhythm:** Short noun-led chapter titles and roughly 4–8-word descriptive headlines alternate with compact explanatory paragraphs. Actions begin with a verb; emphatic fragments punctuate longer explanations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | A plainly named discipline or product category, expanded into monumental broken words. | 4–6 words | “Art Director & Digital Designer” |
| Story headline | An expressive adjective plus a concrete outcome or medium. | 4–7 words | “Fun and striking programmable data”<br>“An ode to nature and technology” |
| Support | Explain what changes and how, then close with a short confident fragment. | 20–50 words | “Irys breaks the rules by making data programmable instead of just stored. Smart contracts and AI manipulate data directly onchain. No compromises.” |
| Action | An active invitation tailored to what the destination contains. | 2–4 words | “Live the experience”<br>“Explore the houses”<br>“Schedule a call” |
| Closing invitation | An expansive destination followed by a personal request to start a conversation. | 6–10 words for headline | “Step into a bold new universe”<br>“Reach out and tell me what you’re building.” |

**Words and phrasing to use:** crafted; bold; experience; refined; explore; concept to production; what you’re building

**Avoid:** synergy; unlock unparalleled potential; best-in-class; hurry; guaranteed success

**Rules:**

- Use sentence-case language in the writing even when visual styling renders capitals.
- Ground expressive adjectives in a specific product behavior or outcome.
- Make the final invitation personal and actionable rather than repeating a slogan.

## Do's and Don'ts

### Do

- Keep the primary editorial canvas forest green and supporting text peach cream.
- Set monumental chapter type at 518.4px on a 1440px desktop composition.
- Keep body and caption tracking at 0.1em even inside compact proof groups.
- Use 1px lavender outlines and 6px corners for capability tiles and name chips.
- Stage media inside a 1090×674px outer frame with a smaller centered presentation.
- Reserve 48px for slide-to-slide separation and 72px for article-to-article separation.
- Make the closing contact object conspicuous with 97.2px condensed lavender lettering.
- Retain a glossy sculptural identity counterpoint and fine-line graphic in the overall design.

### Don't

- Do not replace the condensed display face with a wide geometric sans; the towering narrow silhouette carries the style.
- Do not make actions pill-shaped: the default uses 6px corners, not fully rounded ends.
- Do not introduce white page bands between green chapters; contrast comes from charcoal media regions.
- Do not turn the proof-name cloud into a grid of large filled logo cards; it uses 56px-high outlined text chips.
- Do not box each metric into a separate raised tile; the counts sit directly on green.
- Do not tint the inset product interface to match the outer image; its native colors keep it credible.
- Do not add gradients to flat coral and lavender headlines; volume belongs to the separate inflated artwork.
- Do not pad all content to the 14.4px poster edge; ordinary sections use the wider 64px inset.

## Motion and responsive

### Motion

**Observed:**

- Showcase text panels declare transform and opacity transitions of 1.6s cubic-bezier(.165, .84, .44, 1).
- Proof-name faces declare transform and opacity transitions of 0.5s cubic-bezier(.165, .84, .44, 1).
- Capability panels declare background-color and border-color transitions of 0.4s cubic-bezier(.165, .84, .44, 1).
- Social links declare color and box-shadow transitions of 0.5s cubic-bezier(.165, .84, .44, 1).
- The location indicator uses a 4s infinite pulse with cubic-bezier(.76, 0, .24, 1).

**Transfer:**

- Use the declared slow slide reveal for the large showcase relationship and shorter transitions for the compact outlined links.
- Keep the dot pulse a small peripheral cue rather than a large animated hero effect.

**Unknown:**

- Exact scroll-trigger choreography, opening artwork behavior and reduced-motion variants are not established.

### Responsive

**Observed:**

- Desktop composition uses a 12-column outer grid, a four-column tile grid and a centered wrapping name cloud.
- Metrics use repeat(auto-fit, minmax(200px, 1fr)).

**Transfer:**

- On narrow screens, reduce poster size in proportion to available width while retaining opposing alignments and a small number of deliberately leaning letters.
- Reflow the capability and explanation groups vertically; preserve symbol-to-label separation inside tiles.
- Keep media and its explanatory slide reachable without widening the document; let the proof-name cloud wrap naturally.

**Unknown:**

- Mobile breakpoints, exact fluid font formulas and touch navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
