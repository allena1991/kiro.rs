# IKEA — everyday life in colour

## Overview

An approachable, image-led style that makes useful products feel part of a lively everyday world. Warm white, black and emphatic blocks of yellow, blue and green support bold humanist sans-serif headlines and richly furnished photography. It suits consumer products, practical services and editorial discovery, with dense visual browsing balanced by spacious explanatory passages.

### Essentials

- A useful action becomes a whole architectural panel: the opening pairs a 921×784px photographic story with a 451×784px yellow action panel, separated by 20px inside 24px page gutters.
- Headlines are friendly, heavy and closely fitted rather than monumental by default: 45.7px/1.1 at weight 700 for leading stories, 36.6px/1.15 for image tiles, with negative tracking and sentence case.
- The page reads as a wall of lived-in pictures: near-square 686×684px tiles alternate with 1392×684px panoramas, all clipped to 8px corners with captions anchored at the bottom.
- Colour is furniture for content, not a page-wide wash: keep the canvas warm white and most of the browsing area photographic; use yellow for the conversion panel and occasional solid blue, green or peach editorial islands.
- Controls are simple discs, not miniature cards: 56px circular play, pause and arrow controls accompany imagery; text conversion buttons use a 56px height and 28px radius.
- End with a playful identity billboard, not just utility links: a 1211×492px illustrated identity panel sits on a full-width black closing band with 140px top padding. Use an original patterned word treatment when no equivalent artwork exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action yellow | `#ffdb00` | `--color-yellow` | surface, action, accent | Opening conversion panel and bright editorial collections; also the process chapter on service landing pages. |
| Story blue | `#0058a3` | `--color-blue` | surface | Solid editorial stage surrounding an inset photograph. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Story peach | `#ffae66` | `--color-peach` | surface | Warm background for a compact curated-story collection. |
| Story green | `#1a7e3b` | `--color-green` | surface | Alternative solid editorial stage, with white copy. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Closing black | `#000000` | `--color-black` | background | Full-width closing band; also the source of transparent photographic shading. |
| Near black | `#111111` | `--color-ink` | text, action | Primary lettering and dark controls. |
| Inactive grey | `#dadada` | `--color-disabled` | action | Inactive previous-slide disc. |
| Warm white | `#fffefb` | `--color-canvas` | background, border | Main page and navigation background; fine dividers within the yellow selector. |
| White | `#ffffff` | `--color-white` | text, surface | Text over dark photography and saturated panels, light media controls and story-card caption panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| destination-selection interfaces | Pale yellow | `#fff094` | `--color-search-wash` | surface | Nested search backing in the destination selector. |

## Typography

- **Noto IKEA** — All Latin headings, body text and controls. Sturdy humanist sans-serif with open counters, a practical rhythm and emphatic bold cuts. If unavailable, use **Noto Sans**. Use weights 300, 400, 700 and 800; retain each role's tracking. Font stack: "Noto IKEA", "Noto Sans", Roboto, "Open Sans", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| story-lead | Noto IKEA | 700 | 45.7px | 1.1 | -0.0348em | Opening image headline, colour-stage heading and curated collection heading. |
| tile-heading | Noto IKEA | 700 | 36.6px | 1.15 | -0.03em | Main headline on image-led story tiles. |
| action-panel-heading | Noto IKEA | 700 | 36.6px | 1.25 | -0.03em | Large conversion wording within the yellow opening panel. |
| link-row | Noto IKEA | 400 | 20px | 1.62 | normal | Primary closing navigation links; also explanatory service copy. |
| body | Noto IKEA | 400 | 16px | 1.5 | normal | Image overlines, short supporting copy and editorial descriptions. |
| card-title | Noto IKEA | 700 | 16px | 1.15 | normal | Compact story-card titles beneath square images. |
| card-caption | Noto IKEA | 400 | 13.7px | 1.8 | 0.0045em | Names and short context labels above compact card titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| explanatory service landing pages | service-display | Noto IKEA | 700 | 102px | 1.08 | -0.0412em | Two-line question establishing the reader's need. |
| major collection launches | campaign-display | Noto IKEA | 700 | 82.3px | 1.1 | -0.0432em | Short, oversized launch title on a solid-colour stage. |
| explanatory service landing pages | service-heading | Noto IKEA | 700 | 72px | 1.08 | -0.0256em | Large chapter headings for process, inspiration and project proof. |
| explanatory service landing pages | service-pair-heading | Noto IKEA | 700 | 51px | 1.08 | -0.029em | Short headings that contrast reader needs with provider capabilities. |
| explanatory service landing pages | service-label | Noto IKEA | 300 | 25px | 1.2 | -0.0216em | Light topic label immediately above the opening question. |
| explanatory service landing pages | service-statement | Noto IKEA | 400 | 25px | 1.4 | -0.0096em | Right-aligned introductory paragraph block. |
| explanatory service landing pages | service-list | Noto IKEA | 400 | 16px | 1.62 | normal | Reader and provider qualification lists. |
| explanatory service landing pages | button-label | Noto IKEA | 800 | 14px | 1.43 | normal | Text inside dark conversion pills. |

**Notes:**

- Use the story-lead and tile-heading hierarchy for ordinary marketing pages; reserve the much larger service hierarchy for explanatory pages.
- The sans-serif remains consistent from headline to caption. Bold headlines use negative tracking; body and navigation retain normal spacing.
- Small overlines are visually above headlines, including on photography. They are sentence case rather than spaced uppercase labels.
- Keep type sizes as role-specific values. No viewport-relative type rule is defined here.

## Layout

**Density:** Visually full and tightly tiled in browsing sections; airy and offset in explanatory service sections.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap between paired carousel discs. |
| 16px | Compact card padding, card-to-card spacing and service heading-to-paragraph gap. |
| 20px | Default image-grid and section gaps. |
| 24px | Page side gutters, image-caption insets and service grids. |
| 30px | Service paragraph-to-action spacing. |
| 60px | Inset padding at the top and sides of curated collection bands. |
| 80px | Breathing space before the closing band and above its links. |
| 96px | Common service section top padding. |
| 140px | Closing billboard top padding. |
| 168px | Declared desktop long-form vertical-spacing token. |
| 192px | Expanded service process and video chapter spacing. |

### Containers and grids

- **page-container**: max width 1440px · side padding 24px. Centred outer layout; content spans 1392px at the desktop width.
- **story-grid**: 2 columns · gap 20px. Equal near-square story tiles; full-width stories span both columns.
- **opening-grid**: 3 columns · gap 20px. The photograph spans two columns and the yellow conversion panel spans one.
- **curated-strip**: gap 16px. A short left introduction faces a horizontal row of fixed 252px-wide cards; three cards are fully visible and further items continue horizontally.
- **closing-billboard**: max width 1211px. Centred identity artwork inside a full-width closing band.
- **service-content** (only for explanatory service landing pages): max width 1104px · gap 24px. Inset explanatory content; headings and body blocks are left aligned, with some statements shifted into the right-hand portion.
- **service-reading** (only for explanatory service landing pages): max width 682px. Chapter copy kept narrower than the surrounding media; opening statement can extend to 701px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-and-panels | 8px |
|  | media-controls | 50% |
| explanatory service landing pages | conversion-pill | 28px |

## Surfaces and depth

### Surfaces

#### Warm canvas · level 0

**Use:** The default foundation and navigation backing.

**CSS:** `background: #fffefb`

**Observed:** Almost-white rather than grey; the page is separated into content by gutters, not borders.

**Transfer:** Let photography and solid colour blocks provide the hierarchy.

#### Image caption shade · level 1

**Use:** Bottom-weighted contrast layer on busy photographs.

**CSS:** `background-image: linear-gradient(to top, rgba(0, 0, 0, 0.55) 80px, rgba(0, 0, 0, 0) 200px)`

**Observed:** Only the bottom of the image darkens; most of the photograph retains its natural colour.

**Transfer:** Layer this between the photograph and white caption; use dark lettering without it on a genuinely light studio background.

#### Colour stage · level 0

**Use:** A photographic chapter with a solid backing.

**CSS:** `background: #0058a3; color: #ffffff; border-radius: 8px; overflow: hidden`

**Observed:** Blue and green stages surround a large landscape image; the left copy column is much narrower than the media.

**Transfer:** Use a flat saturated colour, never a decorative gradient.

#### Curated colour band · level 0

**Use:** A brighter editorial collection interrupting the image wall.

**CSS:** `background: #ffdb00; color: #111111; border-radius: 8px; padding: 60px 60px 44px`

**Observed:** The peach variant has the same construction. White caption panels make the smaller cards distinct from the surrounding colour.

**Transfer:** Use this for a small collection of useful stories, examples or perspectives.

#### Closing black band · level 0

**Use:** Terminal identity and utility navigation.

**CSS:** `background: #000000; color: #ffffff; padding: 140px 24px 0; overflow: hidden`

**Observed:** The identity panel dominates; navigation is subordinate beneath it.

**Transfer:** Keep this strong contrast change even on a short page.

#### Process yellow band · level 0

**Only for:** explanatory service landing pages

**Use:** Process explanation and its accompanying video.

**CSS:** `background: #ffdb00; color: #111111`

**Observed:** A full-width yellow chapter contains the left-aligned heading, paragraph, dark pill and wide video.

**Transfer:** Use one decisive colour chapter to make a practical process approachable.

## Components

### Header navigation

**Use:** Global orientation above the visual opening.

**CSS:** `background: #fffefb; height: 96px; position: fixed; z-index: 11`

**Text style:** `body` — Noto IKEA 400 · 16px/1.5

**Observed:** A compact identity sits at the far left followed by four plain text links. Each link has 16px padding; this is not a centred, floating capsule. Service pages add a yellow shopping and destination control on the right.

**Transfer:** Use a small identity and a few short destinations; leave the opening imagery dominant.

### Conversion panel

**Use:** The primary next step beside the opening story.

**CSS:** `background: #ffdb00; color: #111111; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `action-panel-heading` — Noto IKEA 700 · 36.6px/1.25 · tracking -0.03em

**Observed:** The main action is vertically centred with a small dark arrow disc on the right. A separate bottom selector row has a warm-white hairline divider and a chevron; its height is 100px.

**Transfer:** Replace regional shopping selection with a relevant destination or configuration choice while retaining the decisive single action.

### Image story tile

**Use:** Primary editorial discovery unit.

**CSS:** `position: relative; border-radius: 8px; overflow: hidden`

**Text style:** `tile-heading` — Noto IKEA 700 · 36.6px/1.15 · tracking -0.03em

**Observed:** Image fills the tile. A body-sized overline and bold headline sit at bottom left with 24px insets. Image caption shade supports white text, while light studio stories use dark text. Reserve 120px on the right of the caption for a media control.

**Transfer:** Make the whole story a linked visual destination rather than placing a separate button underneath.

### Media control

**Use:** Play or pause inside image and video tiles.

**CSS:** `background: #ffffff; color: #111111; width: 56px; height: 56px; border-radius: 50%; position: absolute`

**Observed:** A small filled play or pause glyph is centred in the disc, placed at the bottom right of the media. A dark variant is used against light imagery.

**States:** Declared: hover background #f5f5f5; focus-visible appearance unspecified; active background #dfdfdf.

**Transfer:** Use a descriptive accessible label naming the media and playback action.

### Compact story card

**Use:** Items in coloured curated strips.

**CSS:** `width: 252px; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column; margin-right: 16px`

**Text style:** `card-title` — Noto IKEA 700 · 16px/1.15

**Observed:** A 252×252px image sits above a 100px white caption area with 16px padding. The card-caption label precedes the bold title; the title can wrap to two lines.

**Transfer:** Show a person, a useful scenario or an object detail rather than an icon.

### Carousel arrows

**Use:** Move the horizontal story strip.

**CSS:** `background: #111111; color: #ffffff; width: 56px; height: 56px; border-radius: 50%; display: flex; align-items: center; justify-content: center`

**Observed:** A right-aligned pair sits beneath the cards with 8px between discs. The inactive previous disc uses #dadada with a grey arrow.

**States:** Declared: hover background #333333; focus-visible appearance unspecified; active background #000000. Inactive disc retains #dadada.

**Transfer:** Keep the controls separate from the cards and below the image row.

### Closing link row

**Use:** Primary navigation below the identity billboard.

**CSS:** `color: #ffffff; display: flex; flex-wrap: wrap; justify-content: center`

**Text style:** `link-row` — Noto IKEA 400 · 20px/1.62

**Observed:** Plain text links form a centred horizontal sentence separated by bullets. Smaller utility links and a copyright line follow beneath.

**States:** Declared: hover text-decoration underline; focus-visible appearance unspecified.

**Transfer:** Keep the top row concise and clearly stronger than utility navigation.

### Destination search

**Only for:** destination-selection interfaces

**Use:** Search within the expanded destination selector.

**CSS:** `background: #ffffff; border-radius: 8px; height: 46px; padding: 12px 0 12px 42px`

**Observed:** The input sits within a pale-yellow panel padded by 10px. A 24px search icon sits on the left. The selector itself remains yellow.

**Transfer:** Use only when the page genuinely requires destination selection.

### Service conversion button

**Only for:** explanatory service landing pages

**Use:** A direct next step after an explanatory paragraph.

**CSS:** `background: #111111; color: #ffffff; height: 56px; padding: 0 32px; border-radius: 28px; display: flex; align-items: center; justify-content: center`

**Text style:** `button-label` — Noto IKEA 800 · 14px/1.43

**Observed:** One compact dark pill, aligned with the left edge of the chapter copy, follows the paragraph after 30px.

**States:** Declared: hover background #333333; focus-visible appearance unspecified; active background #000000.

**Transfer:** Use one explicit action, not a row of competing conversion buttons.

## Imagery and graphics

### Lived-in product photography

**Use:** The dominant content in the opening, story wall and wide editorial features.

**Observed:** Photographs show products in complete, believable scenes: sunlit rooms, textured wood, textiles, plants and people using things. Rich colour is balanced with natural light and real shadows. Square-ish tiles tightly frame details; panoramas establish a larger setting.

**Transfer:** Photograph the new product in use, keeping tactile surroundings, human scale and a clear visual focal point. For a digital product, use a person-and-device scene or an art-directed real-world use case rather than a wall of interface windows.

### Studio product character

**Use:** Light-background product stories contrasted with contextual photography.

**Observed:** A single playful object fills much of a near-square image on a soft white studio sweep, with a natural contact shadow. Black captions and a dark playback disc remain visible against the light backing.

**Transfer:** Use a real object or simple physical metaphor with soft directional light; preserve material texture instead of making a glossy floating 3D emblem.

### Inset colour-stage media

**Use:** A substantial feature inside a saturated editorial stage.

**Observed:** A landscape photograph or film is inset at roughly 894×547px inside a 1392×749px stage. White copy occupies a narrow column on the left; saturated backing remains visible on every side.

**Transfer:** Use a larger demonstration scene to the right of a brief benefit. The backing can echo a product colour while the media remains naturally lit.

### Identity billboard

**Use:** The signature graphic closing the page.

**Observed:** An enormous white identity overlays a wide oval of playful printed illustration inside a white rectangular field. Pink and grey diagonal swathes and bold green botanical drawings contrast with the black surrounding band. It behaves as artwork rather than normal display typography.

**Transfer:** Create an original oversized word or identity treatment with an expressive repeat pattern. The minimum equivalent is a bold white word over flat geometric shapes in a wide clipped field; preserve the art-to-navigation scale contrast.

**Build:** Use an SVG viewBox of 0 0 1211 492 on a white rectangle. Clip a broad ellipse inset about 20px from the edges; fill it with alternating blue and yellow diagonal bands and several original green organic silhouettes outlined in near black. Overlay the new identity in heavy white vector lettering across most of the width. Keep edges crisp, with no blur, bevel or shadow.

### Service scene ribbon

**Only for:** explanatory service landing pages

**Use:** Photo-first service introduction.

**Observed:** A horizontal row of 570×570px furnished scenes extends beyond both viewport edges with 24px gaps and softly faded outer edges. A dark pause disc sits near the lower right.

**Transfer:** Use a coherent set of environments or outcomes from the service, not unrelated stock portraits.

### Helpful line illustration

**Only for:** explanatory service landing pages

**Use:** A human bridge between reader needs and provider capabilities.

**Observed:** A 210×210px yellow circle backs a black line drawing of hands high-fiving, centred between two text columns.

**Transfer:** Choose a simple gesture of help or collaboration appropriate to the new offer.

**Build:** Draw two simplified hands in SVG using near-black round strokes over a yellow circle, with a few short radiating marks above the meeting point. Keep the illustration flat and diagrammatic rather than shaded.

### Icons

**Observed:** Small monochrome filled SVG symbols: arrows, chevrons, search, play and pause. Utility symbols commonly occupy 24×24px; playback glyphs are about 12×14px inside 56px discs. White and near-black reverse according to the background.

**Transfer:** Choose solid, uncomplicated glyphs with matching visual weight; do not introduce colourful icon badges or fine-line technical icon sets.

## Section recipes

How recurring sections are built.

### First screen: Story and action opening

**Observed:** A 96px warm-white Header navigation sits above a 784px-tall opening, leaving 20px below it within the first 900px. Inside 24px side gutters, a three-column grid puts the 921px-wide photographic Image story tile across two columns and the 451px Conversion panel in the third, separated by 20px. Layers are the edge-to-edge photo or film, bottom Image caption shade, white 16px overline, then a 45.7px bold headline at the lower left. A 56px Media control occupies the lower right. The yellow panel centres its 36.6px action and arrow, with its selector row at the bottom. The whole composition, including headline, action and media, is visible in the first screen; the next chapter starts below it.

**Transfer:** Use a strong in-use photograph or a short product film, and give one useful next step a whole yellow panel. If no campaign media exists, stage a real person using the product in a tactile setting. Explanatory service pages instead open with the Service scene ribbon, then a light topic label and oversized question below the image row.

**Avoid:** Do not replace this with a centred text-only hero, a floating product cutout and two pills; the opening's strength comes from its asymmetrical photo-to-action split.

**Text style:** `story-lead` — Noto IKEA 700 · 45.7px/1.1 · tracking -0.0348em

### Image wall

**Observed:** Image story tiles form two equal 686×684px columns with 20px gaps; occasional 1392×684px panoramas span both columns. Each caption combines a small overline and one short heavy headline.

**Transfer:** Group related use cases or editorial stories through imagery, and vary the width to make key ideas feel important without adding more words.

**Text style:** `tile-heading` — Noto IKEA 700 · 36.6px/1.15 · tracking -0.03em

### Saturated feature stage

**Observed:** Colour stage frames a narrow white text column and a much larger inset landscape image. The blue and green versions have the same 1392×749px outer size with about 101px above and below their media. Launch titles can use campaign-display instead of story-lead.

**Transfer:** Give a major capability or launch a physical colour backdrop and a single generous demonstration.

**Text style:** `story-lead` — Noto IKEA 700 · 45.7px/1.1 · tracking -0.0348em

### Curated story strip

**Observed:** Curated colour band pairs a short left-aligned heading and paragraph with Compact story cards to its right. Cards are 252px wide, separated by 16px; Carousel arrows sit below the row when further content continues.

**Transfer:** Use for compact related ideas, practical examples or human perspectives without turning the whole page into small cards.

**Text style:** `story-lead` — Noto IKEA 700 · 45.7px/1.1 · tracking -0.0348em

### Illustrated closing

**Observed:** After 80px of light breathing room, Closing black band presents Identity billboard centred at 1211×492px with 140px top padding. Closing link row follows beneath the artwork; a smaller utility row and copyright finish the page. Both editorial and service pages share this strong ending.

**Transfer:** Make the closing an expressive identity moment that rewards scrolling, with only the most useful navigation beneath it.

### Offset service introduction

**Only for:** explanatory service landing pages

**Observed:** Below Service scene ribbon, a light 25px topic label leads into a 102px question within a 766px text width. A 701px paragraph is shifted right beneath it. Subsequent reader/provider columns use 51px headings and body lists separated by the Helpful line illustration.

**Transfer:** Start with a recognisable reader problem, then let an offset supporting statement and two-sided explanation establish fit.

**Text style:** `service-display` — Noto IKEA 700 · 102px/1.08 · tracking -0.0412em

### Service explanation and proof

**Only for:** explanatory service landing pages

**Observed:** A 72px chapter heading is followed after 16px by 20px/1.62 copy, with a Service conversion button 30px below. The process chapter sits on Process yellow band with a 1104×621px video. Later proof uses alternating 448px and 920px images with 24px gaps, followed by a 1392×696px project photograph.

**Transfer:** Explain the next step plainly, then show credible environments and outcomes at a larger scale than the text.

**Text style:** `service-heading` — Noto IKEA 700 · 72px/1.08 · tracking -0.0256em

## Page flow

**Storyline:** Visual invitation → useful next step → stories or explanation → larger demonstrations and human proof → expressive identity close.

### Visual discovery and product-led editorial browsing

1. **Invitation and conversion** — A large in-use story shares the opening with a yellow action panel.
2. **Focused feature** — A saturated inset-media stage gives one story special emphasis.
3. **Breadth of possibility** — Pairs of near-square images mix with panoramic stories and occasional curated strips.
4. **Human perspective** — A bright story collection gives people and their creative process a place beside product scenes.
5. **Identity close** — Illustrated billboard on black, primary links, then quieter utilities.

**Transfer:** Use this as the default marketing pattern; adapt the amount and order of stories to the new product without losing the opening split and expressive closing.

### Explain a practical service and establish reader fit

1. **Outcome preview** — A moving ribbon of real settings precedes a large reader-centred question.
2. **Reassurance and qualification** — An offset statement and two-sided list explain who the offer is for and how help works.
3. **Process and next step** — A yellow chapter combines a clear explanation, dark pill and wide film.
4. **Inspiration and proof** — Asymmetrical image pairs lead to a project introduction and a wide completed-outcome image.
5. **Identity close** — The same black illustrated ending replaces a separate generic sales banner.

**Transfer:** Use this variant when comprehension and eligibility matter more than browsing many products.

## Writing

Warm, useful and conversational, with a little everyday wit. Confidence comes from recognisable situations and specific help rather than abstract superlatives.

**Do not copy:** Do not reuse IKEA identities, product and collection names, proprietary illustrations, campaign anniversaries, experience totals, geographical service claims or source quotations as claims for a new product. Examples here demonstrate voice only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you and your situation. Use we for concrete help or responsibility, and let short headings speak in a shared conversational voice.
- **Rhythm:** Most editorial headlines are 3–8 words, with short overlines and one-sentence support. Questions, contractions, gentle puns and occasional exclamation marks add energy; service paragraphs can be longer when explaining a practical commitment.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Story headline | A familiar phrase with a useful twist; lead with a benefit or mood rather than a technical specification. | 3–8 words | “For life on the move”<br>“Bamboo, rebooted”<br>“More green? Yes, please!” |
| Context line | A small plain-language description immediately above the story title. | 3–9 words | “The role of home in a changing world”<br>“Indoor adventures for busy kids” |
| Reader question | Name a real obstacle in an uncomplicated question. | 5–9 words | “No [Brand] store in your country?” |
| Chapter heading | Friendly orientation or invitation, without corporate terminology. | 3–5 words | “Here’s how it works”<br>“Inspiration awaits!” |
| Action | Short verb-led instruction describing the destination. | 2–6 words | “Go shopping”<br>“Find out more” |

**Words and phrasing to use:** everyday; play; ideas; your; we; let’s; made for; here’s how; help

**Avoid:** disruptive; best-in-class; enterprise-grade; revolutionary ecosystem; unlock limitless potential

**Rules:**

- Let images carry atmosphere; captions should add a useful angle rather than narrating everything visible.
- Pair a playful headline with a concrete context line.
- Use direct questions for practical obstacles, and answer with a specific form of help.
- Keep interface actions literal even when editorial titles are playful.

## Do's and Don'ts

### Do

- Keep the 24px desktop page gutters and 20px gaps consistent across the image wall.
- Use 8px clipping on photographic tiles and coloured panels.
- Anchor story captions 24px inside the lower-left edge and reserve room for playback controls.
- Use 16px/1.5 text for overlines so small labels remain readable on rich photographs.
- Pair near-square tiles with occasional full-width panoramas for emphasis.
- Keep curated cards at 252px wide with square images and white caption areas.
- Give the black closing band an oversized original identity graphic before navigation.
- On service pages, keep 20px body copy within a roughly 682px reading measure.

### Don't

- Do not turn every section into a pale-grey bordered feature card; this style uses images and flat saturated fields.
- Do not replace the humanist sans with a geometric display face or monospace labels.
- Do not stretch the 8px media radius into heavily rounded 24px bubbles.
- Do not place a dark scrim over the whole photograph; keep the shade concentrated in its bottom 200px.
- Do not make yellow the colour of every CTA pill; large panels are yellow while text conversion pills are near black.
- Do not centre all service paragraphs under the heading; the offset introductory statement is part of that variant's rhythm.
- Do not add drop shadows to the flat story cards and colour stages.
- Do not substitute a multi-column corporate sitemap for the centred bullet-separated closing links.

## Motion and responsive

### Motion

**Observed:**

- Media tiles provide explicit play and pause controls, and the service photo ribbon provides a pause control.
- Declared header transform transition is 0.15s cubic-bezier(1, 0.26, 0.51, 0.72).
- The destination accordion declares a transform transition of 0.4s ease-in.
- A scrolling animation is declared at 10s linear infinite.

**Transfer:**

- Keep playback user-controllable through the visible corner discs.
- Use sliding or scrolling only for image stories and selectors where the interface makes that motion clear.

**Unknown:**

- Exact playback timing, autoplay conditions, reduced-motion behaviour and the assignment of every general transform transition are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 767px, 768px, 1024px, 1025px and 1440px.
- Declared side-spacing tokens use 16px for mobile and tablet, versus 24px desktop navigation spacing.
- Declared long-form vertical-spacing tokens are 64px mobile, 80px tablet and 168px desktop.

**Transfer:**

- For narrow screens, stack the opening story and action panel while retaining the action panel's clear colour identity.
- Collapse paired images into a readable single column; preserve caption-to-image attachment.
- Let curated cards remain a horizontal browse strip rather than shrinking their text to fit.
- Scale the closing artwork to the content width and wrap its link row.

**Unknown:**

- Mobile compositions and exact breakpoint-specific type sizes are not established; stacking rules are recommended adaptations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
