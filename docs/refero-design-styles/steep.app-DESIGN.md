# Steep — editorial machinery and starlight

## Overview

Literary serif headlines give technical software an unexpectedly human, imaginative presence. Near-black stages, restrained gray text and fine white drawings are punctuated by violet light, while the lighter variants use milky whites and washed peach or blue. Large interface scenes carry the explanation; sparse copy and small rounded controls keep the surrounding page unhurried. It suits sophisticated tools that need to feel approachable without losing technical substance.

### Essentials

- Software speaks in a literary voice: Signifier at 88px/1.3, weight 400 and -0.025em tracking opens the default dark product landing; 64px/1.3 and -0.015em carries major chapters.
- The opening is a centered promise above a broad working object: a roughly 560px text group, 80px separation before a 1200px interface, and a fixed 64px navigation bar. The object continues below the first 900px instead of being miniaturized to fit.
- Controls are small capsules rather than hero-sized slabs: 44px height with 20px side padding and 18px/1 text; navigation actions shrink to 32px with 15px/1 text. White is the primary action on dark; ink is the light-page equivalent.
- Color behaves like light, not branding paint: most of the default page remains #121212 or #1a1a1a; violet and teal concentrate behind the opening object and within a few illustrations. Light overview variants reserve #d3e3fc for proof and #fbe1d1 for one emphasized concept card.
- Every landing needs an imaginative technical drawing as well as interface proof: thin outlined constructions, a small starburst, and a selectively grainy spectral fill. If there is no finished artwork, use an original SVG wireframe object with one illuminated plane rather than generic stock 3D.
- A welcoming threshold finishes the narrative: a 64px serif conversion line sits beside a roughly 360–400px open-door drawing, followed by a restrained five-column directory. Retain a line-drawn threshold metaphor even when the product has no natural physical object.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Aubergine atmosphere | `#15101e` | `--color-hero-top` | background | Opening gradient's subtle violet-black upper field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, surface, background | Primary dark-page controls and full-strength labels; canvas in light variants. |
| Black | `#000000` | `--color-black` | text | Text within white primary controls; light pricing and editorial text. |
| Charcoal canvas | `#121212` | `--color-canvas` | background | Default product landing background. |
| Raised charcoal | `#1a1a1a` | `--color-panel` | surface, background | Feature panels, secondary bands and dark footer. |
| Ghost capsule | `#1e1e1e` | `--color-dark-control` | surface, action | Visible white at 5% over charcoal for secondary actions. |
| Header charcoal | `#222222` | `--color-header-base` | surface | Header source color, used at 78% opacity over dark content. |
| Charcoal hairline | `#252525` | `--color-dark-edge` | border | Visible white at 5% over raised charcoal. |
| Recessive dark text | `#898989` | `--color-muted` | text | Visible white at 50% over charcoal; introductory descriptions. |
| Footer gray | `#9e9e9e` | `--color-footer-text` | text, link | Dark footer links. |
| Dark body gray | `#a0a0a0` | `--color-secondary` | text | Visible white at 60% over charcoal; feature descriptions. |
| Soft white heading | `#e7e7e7` | `--color-heading` | text | Visible result of white at 90% over the charcoal canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company editorial pages | Editorial violet | `#4d2f87` | `--color-editorial-purple` | text | Single short emphasis paragraph within a company narrative. |
| company editorial pages | Pale yellow quotation | `#fcf0b6` | `--color-quote-yellow` | text | Serif quotation on an ink card. |
| light overview concept cards | Warm brown | `#5d2a1a` | `--color-concept-ink` | text | Text and outline drawing on the peach card. |
| light overview concept cards | Peach concept | `#fbe1d1` | `--color-concept-peach` | surface | One enlarged illustrated concept card. |
| light social-proof sections | Powder-blue proof | `#d3e3fc` | `--color-proof-blue` | background | Full-width customer-story field. |
| company editorial pages | Cream quotation | `#f8f5e2` | `--color-quote-paper` | surface | Warm quotation card paired with almost-white prose. |
| light overview, company and pricing variants | Light-page ink | `#17191c` | `--color-ink` | text, action, surface | Light-page headlines and primary controls; dark editorial quotation card. |
| light variants | Slate text | `#777b86` | `--color-light-secondary` | text, link | Body copy and links on light pages. |
| company and pricing pages | Faint slate | `#a3a6af` | `--color-light-label` | text | Small prefaces, tier descriptions and uppercase closing eyebrow. |
| light variants | Cool hairline | `#e7e8ea` | `--color-light-rule` | border | Visible rgba(10,23,43,0.1) on white for comparison rows and footer rules. |
| light overview demonstrations | Deeper pale gray | `#f2f2f3` | `--color-ai-band` | background | Long conversational-product demonstration band. |
| light variants | Cool gray band | `#f7f7f8` | `--color-light-band` | surface, background | Pricing cards and light footer. |
| light variants | Almost-white panel | `#fafafb` | `--color-light-panel` | surface, background | Editorial cards, feature stages and question rows. |

## Typography

- **Sohne** — Descriptions, navigation, actions and compact feature headings. Matter-of-fact neo-grotesk with a warm, open rhythm and modest weight contrast. If unavailable, use **Inter**. Use 400, 430 and 500; retain the restrained weights. Font stack: "Sohne", "Inter", ui-sans-serif, system-ui, Arial, sans-serif.
- **Signifier** — Promises, chapter headings, quotations and price numerals. Expressive editorial serif with sharp details and an irregular, literary silhouette. If unavailable, use **Newsreader**. Use regular 400, non-italic; tune wrapping before increasing weight. Font stack: "Signifier", "Newsreader", ui-serif, Georgia, Cambria, 'Times New Roman', serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | Signifier | 400 | 88px | 1.3 | -0.025em | Default product opening, centered over two deliberate lines. |
| chapter | Signifier | 400 | 64px | 1.3 | -0.015em | Major chapter headings and illustrated closing call. |
| split-heading | Signifier | 400 | 56px | 1.3 | -0.015em | Narrow heading beside a large interface. |
| detail-heading | Signifier | 400 | 46px | 1.3 | -0.015em | Compact technical explanation beside media and a short feature list. |
| panel-title | Sohne | 500 | 28px | 1.25 | normal | Large illustrated-panel labels; also comparison and question headings. |
| hero-support | Sohne | 400 | 24px | 1.5 | normal | Two-line explanation beneath the opening promise. |
| lead | Sohne | 400 | 22px | 29px | normal | Section descriptions, usually no wider than 580px. |
| feature-title | Sohne | 500 | 20px | 1.35 | normal | Feature-grid titles and question text. |
| closing-support | Sohne | 400 | 20px | 1.35 | normal | Closing description and customer-story support. |
| feature-body | Sohne | 400 | 18px | 25px | normal | Short explanatory paragraphs under feature images. |
| action | Sohne | 430 | 18px | 1 | normal | Full-size capsule actions. |
| body | Sohne | 400 | 16px | 1.5 | normal | Compact technical descriptions, footer links and editorial body. |
| navigation | Sohne | 430 | 16px | 21px | normal | Top navigation links. |
| footer-heading | Sohne | 480 | 16px | 21px | normal | Footer directory group names. |
| action-small | Sohne | 430 | 15px | 1 | normal | Header actions and pricing-card controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| light social-proof sections | proof-quote | Signifier | 400 | 44px | 1.3 | -0.015em | Main quotation on a blue proof band. |
| company and pricing pages | editorial-heading | Signifier | 400 | 40px | 1 | normal | Company narrative headings, compact closing calls and pricing numerals. |
| company editorial pages | editorial-quote | Signifier | 400 | 36px | 1.25 | normal | Long quotation in a half-width card. |
| company editorial pages | manifesto | Sohne | 400 | 36px | 1.25 | normal | Wide gray editorial statement between card groups. |
| light overview concept cards | concept-title | Sohne | 450 | 26px | 1.18 | -0.0092em | Title at the top of an illustrated concept card. |
| pricing pages | plan-name | Sohne | 430 | 22px | 1.25 | normal | Pricing tier names. |
| company and pricing pages | eyebrow | Sohne | 400 | 16px | 1.5 | 0.05em, uppercase | Small centered preface above the compact closing call. |

**Notes:**

- Serif hierarchy is achieved with scale and spacing, never heavy bold. Tracking tightens from -0.015em at chapter sizes to -0.025em at the opening.
- Display words have individual wrappers and slightly overlapping line boxes: the 88px treatment uses -13.2px bottom margins on line wrappers; the 64px treatment uses -9.6px. Preserve the resulting compact multiline silhouette without clipping descenders.
- Sans text remains normally tracked except the small uppercase editorial eyebrow and the concept-card title. Do not turn technical material into a separate marketing monospace system.

## Layout

**Density:** Airy framing around deliberately compact controls and richly detailed interface imagery.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and close text grouping. |
| 12px | Heading/support and compact control grouping. |
| 16px | Action-pair gap and question-row separation. |
| 20px | Editorial heading separation and pricing-card gutters. |
| 24px | Action separation below support; footer grid gutters. |
| 32px | Concept-card padding and question-row inner padding. |
| 40px | Feature-grid gutters. |
| 48px | Pricing and glass-panel inner padding. |
| 64px | Closing two-column gap. |
| 80px | Desktop container side padding and heading-to-media separation. |
| 96px | Footer vertical padding and chapter-to-feature separation. |
| 120px | Large feature chapter breathing space. |
| 128px | Closing section upper padding. |
| 160px | Opening space below the header and major chapter separation. |
| 180px | Editorial card vertical padding. |
| 200px | Closing section lower padding. |
| 240px | Deep separation after a major four-item capability chapter. |

### Containers and grids

- **main-container**: max width 1360px · side padding 80px. Centered desktop wrapper giving 1200px usable content at the reference width.
- **product-stage**: max width 1200px. Main interface or illustrated panel; often much wider than the text group.
- **centered-lead**: max width 580px. Centered chapter heading and description; opening text group is about 560px.
- **split-feature**: 2 columns · gap 32px. Approximately one-third copy and two-thirds media, not equal cards.
- **feature-trio**: 3 columns · gap 40px. 373px square media atop titles and compact paragraphs.
- **feature-quartet**: 4 columns · gap 40px. 270px square demonstrations or illustrations with text below.
- **footer-directory**: max width 1200px · 5 columns · gap 24px. Small symbol column followed by four directory columns.
- **pricing-grid** (only for pricing pages): max width 1560px · 3 columns · gap 20px · side padding 80px. Equal pricing cards; actual usable width is 1280px at desktop.
- **comparison** (only for pricing pages): max width 900px. Narrow centered comparison and question blocks.
- **editorial-pair** (only for company editorial pages): max width 1200px · 2 columns · gap 20px. Equal prose and quotation cards; alternate their sides.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | capsules | 9999px (pill) |
|  | feature-panels | 24px |
|  | interface-and-small-panels | 16px |
| light conversational-product demonstrations | conversation-bubbles | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| large-interface | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Hero interface and large light interface scenes. |
| floating-layer | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Floating media and translucent callouts. |

### Surfaces

#### Dark canvas · level 0

**Use:** Default landing canvas.

**CSS:** `background: #121212; color: #e7e7e7`

**Observed:** Broad unboxed fields separate chapters.

**Transfer:** Let text and imagery create hierarchy before adding cards.

#### Opening atmosphere · level 0

**Use:** Back layer of the default first screen.

**CSS:** `background: linear-gradient(#15101e, #121212)`

**Observed:** Dim violet and teal light sits behind the interface; texture is fine rather than glossy.

**Transfer:** Use the Atmospheric light recipe over this base; keep the promise readable.

#### Charcoal panel · level 1

**Use:** Large illustrated feature panels and secondary bands.

**CSS:** `background: #1a1a1a; border: 1px solid rgba(255,255,255,0.05); border-radius: 24px`

**Observed:** Just one shade above the canvas, with a barely perceptible edge.

**Transfer:** Separate a substantial explanation without making every feature a boxed card.

#### Glass callout · level 2

**Use:** Copy that overlaps a broad product scene.

**CSS:** `background: rgba(26,26,26,0.667); border: 1px solid rgba(255,255,255,0.05); border-radius: 24px; backdrop-filter: blur(12px); box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Observed:** A 400px-wide translucent caption anchors one corner of a much larger image.

**Transfer:** Keep this as a single explanatory layer rather than a grid of glass cards.

#### Light canvas · level 0

**Only for:** light overview, company and pricing variants

**Use:** Alternative daytime editorial system.

**CSS:** `background: #ffffff; color: #17191c`

#### Pale panel · level 1

**Only for:** light variants

**Use:** Company prose cards and product feature bands.

**CSS:** `background: #fafafb; border-radius: 24px`

#### Pale gray band · level 0

**Only for:** light variants

**Use:** Footer and pricing-card backing.

**CSS:** `background: #f7f7f8`

#### Conversation stage · level 0

**Only for:** light conversational-product demonstrations

**Use:** Long interface scene with floating questions.

**CSS:** `background: #f2f2f3`

#### Blue proof band · level 0

**Only for:** light social-proof sections

**Use:** Full-width quotation and photographic proof.

**CSS:** `background: #d3e3fc; color: #17191c`

#### Cream quotation card · level 1

**Only for:** company editorial pages

**Use:** Long human quotation beside a prose card.

**CSS:** `background: #f8f5e2; color: #17191c; border-radius: 24px`

**Observed:** Companion variant uses ink backing and pale-yellow text.

**Transfer:** Keep warm quotation color local to company storytelling.

## Components

### Fixed navigation

**Use:** Persistent small-scale orientation and conversion.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 64px; padding: 0px 20px; background: rgba(34,34,34,0.78); backdrop-filter: blur(15.6px); z-index: 50`

**Text style:** `navigation` — Sohne 430 · 16px/21px

**Observed:** A 1200px inner row places the symbol and name at left, four links in the middle and demo plus primary action at right. The current section gets a faint capsule. Light variants use white at 78% with the same geometry.

**Transfer:** Keep the center links subdued and reserve the filled capsule for conversion.

### Primary button

**Use:** Main conversion in the default dark theme.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 0px 20px; border-radius: 9999px; background: #ffffff; color: #000000`

**Text style:** `action` — Sohne 430 · 18px/1

**Observed:** No icon is required; a plain secondary demo action sits beside it. Light variants invert to ink fill and white text.

**States:** Declared: hover opacity 0.9; focus-visible styling unspecified; active opacity 0.8.

### Compact action

**Use:** Conversion in the fixed header and pricing cards.

**CSS:** `height: 32px; padding: 0px 12px; border-radius: 9999px; background: #ffffff; color: #000000`

**Text style:** `action-small` — Sohne 430 · 15px/1

**Observed:** Uses the same inversion on light backgrounds as Primary button.

**States:** Declared: hover opacity 0.9; focus-visible styling unspecified; active opacity 0.8.

### Ghost button

**Use:** Secondary route to a deeper feature explanation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 44px; padding: 0px 20px; border-radius: 9999px; background: rgba(255,255,255,0.05); color: #ffffff`

**Text style:** `action` — Sohne 430 · 18px/1

**Observed:** A small right arrow follows the text. Light variant uses a 5% blue-black wash with ink text.

**States:** Declared: hover background-color color-mix(in oklab,#fff 10%,transparent); focus-visible styling unspecified; active background-color color-mix(in oklab,#fff 15%,transparent).

### Illustrated feature panel

**Use:** One substantial capability presented as a composed scene.

**CSS:** `background: #1a1a1a; border: 1px solid rgba(255,255,255,0.05); border-radius: 24px; padding: 80px 80px 16px 80px`

**Text style:** `panel-title` — Sohne 500 · 28px/1.25

**Observed:** Short title and support sit upper left; a large construction drawing occupies the right. A lower row of compact feature explanations is divided by faint vertical rules.

**Transfer:** Use an original structural metaphor related to the new capability.

### Footer link

**Use:** Directory destinations in either theme.

**CSS:** `color: #9e9e9e; text-decoration: none; text-underline-offset: 4px`

**Text style:** `body` — Sohne 400 · 16px/1.5

**Observed:** Stacked in 40px rows beneath brighter group titles; external destinations receive a small diagonal arrow. Light version uses slate text.

**States:** Declared: hover text-decoration-line underline; focus-visible styling unspecified.

### Plan card

**Only for:** pricing pages

**Use:** Three equal-weight purchasing options.

**CSS:** `display: flex; flex-direction: column; background: #f7f7f8; border-radius: 16px; padding: 48px; color: #000000`

**Text style:** `plan-name` — Sohne 430 · 22px/1.25

**Observed:** Tier name, muted one-sentence audience, serif price or custom-price text, Compact action in ink, then checkmarked inclusions. All plans have the same fill and dark action; no bright recommended-plan ribbon.

**Transfer:** Keep tiers calm and comparable; differentiate through content rather than decoration.

### Question row

**Only for:** pricing pages

**Use:** Objection handling below detailed comparison.

**CSS:** `background: #fafafb; border-radius: 16px; margin-bottom: 16px`

**Text style:** `feature-title` — Sohne 500 · 20px/1.35

**Observed:** A padded inner row uses 32px inset, question at left and a muted 24px disclosure icon at right; closed rows are 91px tall.

**Transfer:** Use a real disclosure control; keep answers outside the closed-row height.

### Comparison row

**Only for:** pricing pages

**Use:** Dense feature-by-plan comparison.

**CSS:** `display: flex; border-bottom: 1px solid rgba(10,23,43,0.1)`

**Text style:** `body` — Sohne 400 · 16px/1.5

**Observed:** 900px table with a 40% label column and three 20% plan columns. Typical rows are 45px tall, category rows 66px; plan cells use near-white backing and centered checks or short values. A sticky heading maintains context.

**Transfer:** Preserve label width and aligned tier columns instead of turning this into unrelated cards.

### Concept card

**Only for:** light overview concept sections

**Use:** A memorable compact explanation of a product principle.

**CSS:** `display: flex; flex-direction: column; padding: 32px; border-radius: 24px; background: #fbe1d1; color: #5d2a1a`

**Text style:** `concept-title` — Sohne 450 · 26px/1.18 · tracking -0.0092em

**Observed:** Title at top, fine outline object in the middle, short explanation at bottom. The peach card is enlarged relative to neighboring pale-gray cards.

**Transfer:** Use one emphasized card, not three saturated tiles.

### Editorial quote card

**Only for:** company editorial pages

**Use:** Human perspective paired with factual prose.

**CSS:** `padding: 180px 80px; background: #f8f5e2; border-radius: 24px; color: #17191c`

**Text style:** `editorial-quote` — Signifier 400 · 36px/1.25

**Observed:** Long serif quotation above a small sans attribution. Its paired variant is ink with pale-yellow quotation text; prose cards retain an almost-white backing.

**Transfer:** Use genuine attributed language and alternate quote/prose sides across the narrative.

## Imagery and graphics

### Working product scenes

**Use:** The primary evidence of what the software does.

**Observed:** Real desktop interfaces are framed at 1200px wide in the opening, or roughly 788px beside narrow prose. Dark scenes retain dark native chrome, faint 5–8% white edges and 16px corners; some small feature images fade gently into the page at the bottom. Light scenes use white chrome and soft elevation, with pastel chart colors confined to the interface.

**Transfer:** Show one meaningful task at readable scale. If no finished interface exists, construct a believable reduced workflow with a sidebar, one central task and one supporting panel; do not fill the stage with decorative dashboards.

### Atmospheric light

**Use:** Signature atmosphere behind the opening object and selected demonstrations.

**Observed:** Dim teal drifts from the left toward a violet glow under the centered promise; charcoal remains dominant. The light variant spreads low-saturation lavender, peach, coral and pale yellow across a milky field, behind floating interface fragments.

**Transfer:** Keep text and interface crisp above the light. Exact stops are not essential; match the soft, grainy spread rather than creating bright neon rims.

**Build:** Layer two or three oversized radial gradients behind content: teal at about 15% opacity toward the lower left, violet at about 22% toward the lower center, fading to transparent well before the edges. Blur the light layer by roughly 80px and add a very fine monochrome SVG turbulence layer at low opacity. On light stages use pastel versions with a white veil. These are construction recommendations, not fixed gradient stops.

### Spectral construction drawings

**Use:** Signature explanatory art paired with technical chapters.

**Observed:** White pencil-like isometric outlines depict modular blocks, arches and prism forms on charcoal. Only a few faces glow violet with gold or cyan transitions; fine visible grain and tiny cross-shaped stars keep the effect handmade rather than polished 3D. One expansive scene overlays a translucent code window on an outlined prism and a tapering spectral beam.

**Transfer:** Make an original physical analogy for the product's operation. Minimum acceptable version is a crisp wireframe object with one textured illuminated face and two small starbursts.

**Build:** Draw isometric polygon faces with SVG paths, roughly 1px off-white strokes, no solid fill on most faces. Fill one tall plane with a violet-to-warm-gold gradient and a fine turbulence opacity mask; put a faint blurred duplicate behind it. For a beam scene, connect a broad cyan polygon to a narrow violet tip at a diagonal and scatter only a few 8–20px four-ray stars. Keep these colors inside the artwork, not in page text.

### Threshold illustration

**Use:** Signature companion to the final conversion statement.

**Observed:** A thin white open door on dark, or black outline on white, stands on a single imperfect horizontal ground line. The gap reveals a few distant points of light; the object occupies about one-third of the closing composition.

**Transfer:** Retain the feeling of an invitation into a new space. An original doorway, opening panel or outlined portal is sufficient; keep the surrounding field empty.

**Build:** Use SVG straight paths for a frame and perspective quadrilateral leaf, a small rounded handle and a 1px ground line. Make the opening a narrow contrasting wedge with a few 2–4px pale dots and one small four-point star. Size the artwork around 360–400px wide; avoid a rendered room or elaborate scenery.

### Human photographic proof

**Only for:** light social-proof and company editorial pages

**Use:** Ground software claims in people and actual use.

**Observed:** Square monochrome photography, including outdoor everyday activity and founders in a street, uses soft contrast and rounded corners. The proof band pairs a substantial photo at right with a serif quotation at left; company openings place a portrait beside a compact statement inside a pale card.

**Transfer:** Use candid, context-rich people photography, desaturated and naturally lit; keep photographs subordinate to the editorial composition.

### Floating conversation

**Only for:** light conversational-product demonstrations

**Use:** Show participation around a large interface.

**Observed:** White 20px-radius question bubbles and pill-shaped person badges overlap opposite edges of a wide interface. Fine outlines, soft shadows and very pale lavender light separate the layers.

**Transfer:** Use two or three realistic user intentions tied to the central task; avoid a cloud of unrelated notifications.

### Icons

**Observed:** Small navigation and external-link symbols are restrained; utility outlines use about 1.4px round strokes at 12–23px, while technical feature symbols are 36px with about 1.5px strokes and less rounded ends. Arrows are small and follow labels; checks in pricing are muted rather than green.

**Transfer:** Choose a single sparse outline icon set and match stroke weight. Keep larger illustrated metaphors separate from the utility icons.

## Section recipes

How recurring sections are built.

### First screen: Dark promise over working object

**Observed:** Back to front: Dark canvas, Opening atmosphere with dim colored light, centered serif promise, muted support, then the large native-dark interface. Fixed navigation spans the top with a white Compact action at right. The opening text starts 160px below the 64px header, occupies about 560px in the center and uses hero across two lines; support is 24px/1.5 across about 488px. An 80px gap leads into the 1200px-wide interface beginning near 598px. Within the first 900px the entire promise and support plus the upper working portion of the interface are visible; the remaining interface and its overlapping detail continue below. The main call to action in this screen is in the navigation, not an extra oversized action row.

**Transfer:** Use this dark composition as the default marketing or product landing. Replace the interface with one large reduced working scene if necessary, keeping its upper portion visible above the fold. Pricing opens on white with a centered 64px serif proposition and controls over equal cards; company stories open in a pale portrait-and-statement card. A light overview can instead surround a centered explanation and action pair with floating interface fragments in pastel light.

**Avoid:** Do not squeeze the entire application into a tiny laptop mockup, replace the serif promise with bold sans, or brighten the background into a full-bleed neon gradient.

**Text style:** `hero` — Signifier 400 · 88px/1.3 · tracking -0.025em

### Centered chapter pair

**Observed:** A centered chapter heading and lead share a 580px measure, followed by about 80px before the main panel. Major chapters are separated by 160px. Headings are soft white, descriptions recede to white at 50%.

**Transfer:** Use for a new idea that needs a composed introduction, not for every small feature.

**Text style:** `chapter` — Signifier 400 · 64px/1.3 · tracking -0.015em

### Illustrated panel with foundations

**Observed:** Illustrated feature panel combines a short sans title at upper left and large Spectral construction drawings at right, then a lower four-column explanatory row with fine rules and compact labels.

**Transfer:** Explain a system through one physical metaphor plus a few concrete constituent capabilities.

**Text style:** `panel-title` — Sohne 500 · 28px/1.25

### Asymmetric interface chapter

**Observed:** A 56px split-heading or 46px detail-heading sits in a narrow left column with a lead and optional compact icon list. The right media occupies about two-thirds of the 1200px stage. Copy begins around 40px below the media top rather than being centered mechanically.

**Transfer:** Use for one important capability with direct visual proof.

**Text style:** `split-heading` — Signifier 400 · 56px/1.3 · tracking -0.015em

### Unboxed capability grid

**Observed:** Three 373px or four 270px square media objects sit over 20px feature titles and 18px explanatory text, with 40px gutters. Images may fade into the charcoal backing; the text is not wrapped in another card.

**Transfer:** Group parallel benefits while keeping their descriptions short and their media consistent.

**Text style:** `feature-title` — Sohne 500 · 20px/1.35

### Scene with glass caption

**Observed:** A broad roughly 1152px product illustration is partly overlapped at a lower corner by Glass callout, 400px wide with 48px top/side and 80px bottom padding. Its sans headline is larger than normal feature text.

**Transfer:** Use sparingly for a narrative turning point where a short explanation belongs inside the scene.

### Illustrated closing invitation

**Observed:** A 1200px two-column scene uses chapter and closing-support on the left and Threshold illustration on the right, with 64px between. Primary button and a plain demo route sit 24px below the support. Padding is 128px above and 200px below; dark uses a white button and light uses ink.

**Transfer:** End with a low-friction next step and the threshold metaphor, not another feature grid.

**Text style:** `chapter` — Signifier 400 · 64px/1.3 · tracking -0.015em

### Directory ending

**Observed:** After conversion, the footer moves one neutral shade away from the canvas. A 1200px five-column grid contains a small symbol, four link groups and a bottom metadata row. Vertical padding is 96px, gutters 24px and links occupy 40px rows. Light variants include a faint full-width divider; dark remains nearly tonal.

**Transfer:** Give the footer useful structure without a giant wordmark, gradient or additional sales pitch.

**Text style:** `body` — Sohne 400 · 16px/1.5

### Powder-blue human proof

**Only for:** light social-proof sections

**Observed:** Blue proof band places a 44px serif quotation and support in a wide left column opposite square monochrome photography. Read-story and all-stories actions sit below, followed by a four-logo selector with a thin active underline. The band is about 830px tall.

**Transfer:** Use a short authentic customer statement and contextual image; preserve the blue field and understated selector rather than replacing it with a star-rating widget.

**Text style:** `proof-quote` — Signifier 400 · 44px/1.3 · tracking -0.015em

### Editorial paired cards

**Only for:** company editorial pages

**Observed:** Two 590px cards share a 20px gutter within 1200px. Pale prose cards use 40px serif headings and 16px body; quotations use Editorial quote card. Alternate cream/ink quote cards with neutral prose cards. A separate 800px-wide gray manifesto uses 36px sans text.

**Transfer:** Balance first-person perspective with factual context rather than making a wall of testimonials.

**Text style:** `editorial-heading` — Signifier 400 · 40px/1

### Transparent pricing and objections

**Only for:** pricing pages

**Observed:** A centered 64px serif proposition and 22px lead precede small 32px outlined currency/billing selectors. Plan card appears in three equal columns; Comparison row follows in a 900px block. Question row then handles objections beneath a 28px sans heading.

**Transfer:** Keep commercial information visually neutral and dense only where comparison benefits from it.

**Text style:** `chapter` — Signifier 400 · 64px/1.3 · tracking -0.015em

### Compact editorial closing

**Only for:** company and pricing pages

**Observed:** A centered 460px group has a 16px uppercase eyebrow, 40px serif statement, 16px support and one ink capsule. Gaps are 8px, 20px and 32px; the enclosing section has 180px vertical padding.

**Transfer:** Use this quieter close where a long illustrated landing-page finale would distract from a practical decision.

**Text style:** `editorial-heading` — Signifier 400 · 40px/1

## Page flow

**Storyline:** Promise → working proof → explanatory chapters → confidence and breadth → low-friction invitation → directory; expand or compress according to the decision being made.

### Flagship product landing with technical depth

1. **Promise** — Centered serif claim in dim spectral atmosphere above a large dark interface.
2. **System explanation** — Centered chapter introduces an illustrated architecture panel and three supporting capabilities.
3. **Working proof** — Asymmetric interface chapter and parallel square media examples.
4. **User outcome** — Expansive scene with a glass caption bridges into controls and access capabilities.
5. **Technical confidence** — Wide integration artwork, compact capability row and a split performance explanation.
6. **Organizational confidence** — Four restrained enterprise capability items.
7. **Closing call** — Serif invitation beside a line-drawn threshold; white capsule on charcoal.
8. **Directory** — Five-column charcoal footer.

**Transfer:** Use the dark flagship treatment for new product landings; select only chapters needed to explain the product rather than reproducing the full sequence.

### Broad product overview combining approachability and proof

1. **Working atmosphere** — Light pastel field with floating interface details and centered explanation plus actions.
2. **Concept framing** — Centered serif proposition and three outline-illustrated cards, one emphasized in peach.
3. **Product demonstration** — Pale stage with narrow feature selector beside a large interface.
4. **Social proof** — Blue quotation band and monochrome contextual photograph.
5. **Technical foundation** — Dark chapter with diagram and compact icon-led supporting capabilities.
6. **Participation** — Pale gray conversation stage with floating user questions and a three-item benefit row.
7. **Closing call** — Light illustrated threshold invitation.
8. **Directory** — Five-column pale footer.

**Transfer:** Use the scoped light overview system when breadth and approachability matter more than technical immersion.

### Company narrative that makes expertise feel human

1. **Identity** — Pale card with monochrome portrait and compact serif statement.
2. **Point of view** — Wide gray sans manifesto.
3. **Perspective and credentials** — Alternating prose and cream/ink quotation cards.
4. **Organizational confidence** — Two factual prose columns in one pale panel.
5. **Closing call** — Compact centered eyebrow, serif statement and single capsule.
6. **Directory** — Pale five-column footer.

**Transfer:** Use the editorial cards for any organization's point of view and credibility, not as a requirement to recount founders or company history.

### Practical purchase decision and objection handling

1. **Commercial promise** — Centered serif proposition, short explanation and small billing controls.
2. **Choice** — Three equally styled pricing cards with serif numerals and dark actions.
3. **Detailed comparison** — Narrow hairline table with persistent tier context.
4. **Objection handling** — Stacked near-white question rows.
5. **Closing call** — Compact centered invitation.
6. **Directory** — Pale five-column footer.

**Transfer:** Replace tiers, features and commercial terms while retaining equal emphasis and the calm shift from cards to dense comparison.

## Writing

Assured, plainspoken and optimistic about making complex work accessible. Technical nouns are welcomed, but outcomes and everyday collaboration keep the language human.

**Do not copy:** Do not reuse Steep's name, wordmark, customer logos, proprietary illustrations, quotations, product claims, prices, user limits, setup-time promises or customer results. Examples below show cadence only.

- **Addressing the reader:** Use you and your for capabilities, we for a company perspective, and direct imperatives for major promises. Refer to the product by name only when it clarifies the sentence.
- **Rhythm:** Headlines are usually two to seven words with deliberate contrasts or an active verb. Supporting text is one or two plain sentences; card titles are short nouns or verb phrases. Avoid exclamation marks and ornamental punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Active verb plus a concrete object, often contrasted with the old way of working. | 3–7 words | “Ship metrics, not dashboards” |
| Chapter heading | Short action with a human or practical outcome. | 2–5 words | “Engage everyone”<br>“Unlock deep analysis” |
| Support | Explain the mechanism and benefit without repeating the headline. | 12–25 words | “All your governed metrics available in one place.”<br>“Give your end users the freedom to answer their own questions.” |
| Feature label | Concrete capability noun phrase. | 2–5 words | “Version-controlled code definitions”<br>“Fine-grained permissions” |
| Action | Direct familiar verb; primary action feels easy, secondary offers human help. | 2–4 words | “Get started”<br>“Book a demo”<br>“Read the story” |
| Reassurance | Plain practical reduction of risk or effort beneath the closing promise. | One or two short sentences | “No card details required. Get started in 10 minutes” |

**Words and phrasing to use:** ship; define; connect; explore; governed; building blocks; available in one place; your team; move faster

**Avoid:** game-changing; disruptive; unleash your potential; next-level; magical AI; !!!

**Rules:**

- Pair broad promises with specific mechanisms in the following sentence.
- Use contrast to clarify a change in working method, not to insult the reader.
- Name controls and capabilities plainly; let artwork supply the playfulness.
- Keep evidence and commercial terms factual; only publish reassurance that the new product can support.

## Do's and Don'ts

### Do

- Keep display serif at weight 400 and use 88px only for the principal opening promise.
- Use the 1200px media stage to make one working task legible rather than presenting many miniature screens.
- Separate dark surfaces by #121212 versus #1a1a1a and a 5% white hairline.
- Keep primary controls at 44px and navigation controls at 32px.
- Retain one original fine-line, selectively illuminated drawing and the threshold device on new landings.
- Use 40px gutters for parallel capability media and 24px for the footer grid.
- Keep scoped pricing cards neutral and give every plan the same ink action.
- Pair monochrome human photography with powder blue only in the light proof treatment.

### Don't

- Do not use bold geometric sans for the main promise; it loses the editorial character.
- Do not spread violet into navigation labels, body links and conversion buttons; light belongs behind objects.
- Do not apply heavy shadows to every charcoal panel; edges are mostly tonal and hairline.
- Do not substitute 8px-rounded rectangular buttons for full capsules.
- Do not surround every feature title and paragraph with an extra bordered card.
- Do not introduce green checks or a saturated recommended-plan fill into the neutral pricing system.
- Do not turn the footer into a monumental wordmark; the ending is a small symbol and five-column directory.
- Do not apply cream quotation cards and purple editorial emphasis to an ordinary technical landing.

## Motion and responsive

### Motion

**Observed:**

- Primary and ghost actions declare color/opacity transitions of 0.2s cubic-bezier(.4,0,.2,1). Navigation link color transitions use 0.15s with the same curve.
- The fixed navigation declares an all-property 0.5s cubic-bezier(.4,0,.2,1) transition.
- Declared keyframes include sweeping, progress filling, arrow frames, fades and a carousel; no matched active animations establish their timing.

**Transfer:**

- Keep interaction motion concentrated in capsules, navigation and selected scene layers; retain legible settled compositions.
- For a rotating proof selector, preserve the underline and active-logo distinction even when movement is reduced.

**Unknown:**

- Exact scene choreography, scroll triggers, playback timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 640px, 768px, 1024px, 1280px and 1536px.
- The opening headline declares 50px, 60px, 70px and 88px steps across increasing widths. Centered opening alignment begins above the narrowest layout.
- The main wrapper declares smaller 48px padding before the 80px desktop treatment. Navigation center links are hidden below the small breakpoint; footer grid changes from five to two columns. Several desktop feature rows are hidden below the medium breakpoint.

**Transfer:**

- As a design recommendation, stack asymmetric copy above its media and preserve a useful working area rather than shrinking a desktop interface to unreadable text.
- Keep the threshold artwork below the closing copy at narrow widths; reduce atmosphere intensity where text and objects converge.
- Use the declared stepped type approach instead of inventing a continuous viewport formula.

**Unknown:**

- Mobile replacement content for hidden rows, mobile menu behavior, exact narrow-screen media framing and all touch interaction states remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
