# Peter Tarka — floating worlds, ruled ground

## Overview

A light, gallery-like style in which playful three-dimensional objects float over an austere ruled index. Black grotesk labels and pale gray surfaces leave the expressive work to candy-colored miniature worlds, tactile materials and polished sculptural forms. It suits visually led products, creative tools and collections whose proof is best experienced rather than explained; the text is sparse and the imagery expansive.

### Essentials

- A catalog is the hero: two edge-to-edge columns, each 720px wide at 1440px, with independently staggered 480px and 720px panels and no gutters.
- Objects escape their entries: a large isolated 3D scene crosses the central column rule and several panel boundaries, while corner labels remain legible above it. Every new page needs this floating sculptural device; use a small original geometric diorama if detailed media is unavailable.
- Titles act as gallery labels, not slogans: GT America 38px, weight 400, line-height 1.31, normal tracking; the active title is underlined rather than placed in a filled button.
- Color belongs to the object and its selected stage: most of the ground remains #f0f0f0, with a single panel-sized blue gradient from #77c1e5 to #8ed0ef in the opening. Keep vivid color out of navigation and ordinary labels.
- Each entry is bracketed by text: a title at the top and a 21px, weight 300, line-height 1.31 metadata row at the bottom, all inset 45px; description left, date or compact fact right.
- The interface is almost unframed: 1px #d8d8d8 right and bottom rules, square corners, no card shadows, and a fixed two-stroke menu icon measuring 32px by 10px instead of a navigation bar.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#77c1e5` | `--color-stage-top` | background | Top of the selected opening panel gradient, not a general action color. |
| Pool blue | `#8ed0ef` | `--color-stage-bottom` | background | Bottom of the selected opening panel gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery gray | `#f0f0f0` | `--color-canvas` | background, surface | Continuous page ground and ordinary index panels. |
| Index rule | `#d8d8d8` | `--color-rule` | border | Fine panel edges and the diagonal terminal mark. |
| Black | `#000000` | `--color-ink` | text, link, action | All text, active title underline and menu strokes. |

## Typography

- **GT America** — All visible titles and metadata. Matter-of-fact American grotesk, regular titles with lighter secondary text; open shapes and unembellished spacing. If unavailable, use **Public Sans**. Use 400 for titles and 300 for metadata; retain normal tracking. Font stack: "GT America", "Public Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| entry-title | GT America | 400 | 38px | 1.31 | normal | Primary panel headings and opening title; underline the active entry only. |
| metadata | GT America | 300 | 21px | 1.31 | normal | Short descriptions, status labels and right-aligned years or facts at the bottom of panels. |
| control | GT America | 400 | 16px | 1 | normal | Base text for utility controls when a visible label is needed; keep subordinate to the two-level entry hierarchy. |

**Notes:**

- The hierarchy has only two prominent text sizes. Scale and material complexity live in the artwork, not in enormous display lettering.
- Keep titles in natural title or sentence case and metadata lightweight. The title underline is a selection cue, not the default treatment for every heading.

## Layout

**Density:** Airy: sparse corner labels surround large object stages, with no gutters between the panels themselves.

### Spacing

| Value | Use |
| --- | --- |
| 45px | Uniform inset on all four sides of index panels. |
| 15px | Vertical padding of the menu button hit area. |
| 10px | Horizontal padding of the menu button hit area. |

### Containers and grids

- **Edge-to-edge index**: 2 columns · gap 0px · side padding 0px. Two equal independent vertical stacks fill the viewport width, without a centered max-width container. At 1440px each is 720px wide. Alternate 480px and 720px entries to stagger horizontal rules.
- **Panel content**: side padding 45px. Title and footer share the same left and right inset. Flex column space-between sends the footer to the bottom rather than immediately beneath the title.

## Corner radius

| Element | Radius |
| --- | --- |
| Index panels | 0px |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Continuous background beneath the index and floating objects.

**CSS:** `background: #f0f0f0`

**Observed:** Flat and matte; no texture, vignette or raised card effect.

**Transfer:** Let the object lighting provide depth rather than adding depth to the page shell.

#### Ruled panel · level 0

**Use:** Default entry surface.

**CSS:** `background: #f0f0f0; border-right: 1px solid #d8d8d8; border-bottom: 1px solid #d8d8d8; border-radius: 0px; box-shadow: none`

**Observed:** Panels touch on all sides. The rules form a continuous index rather than separate cards.

**Transfer:** Use as the neutral frame for product capabilities, examples or collection entries.

#### Selected blue stage · level 0

**Use:** Opening selected entry behind the floating diorama.

**CSS:** `background: linear-gradient(#77c1e5 0%, #8ed0ef 100%); border-right: 1px solid #d8d8d8; border-bottom: 1px solid #d8d8d8`

**Observed:** The rectangular color field stops exactly at its panel edges; the foreground artwork does not.

**Transfer:** Reserve a colored field for the selected story. Additional selected stories can use colors drawn from their artwork while leaving the surrounding index neutral.

#### Diagonal end mark · level 0

**Use:** Graphic closure at the end of the index.

**CSS:** `background-image: linear-gradient(to left top, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0) calc(50% - 0.8px), #d8d8d8 50%, rgba(0, 0, 0, 0) calc(50% + 0.8px), rgba(0, 0, 0, 0) 100%)`

**Observed:** A faint bottom-left to top-right diagonal spans a square beside the last entry.

**Transfer:** Use this deliberate ruled gesture as a restrained ending rather than treating the terminal area as another content card.

## Components

### Index entry

**Use:** Main repeatable content unit.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: space-between; padding: 45px; height: 480px; box-sizing: border-box; background: #f0f0f0; border-right: 1px solid #d8d8d8; border-bottom: 1px solid #d8d8d8; overflow: hidden`

**Observed:** A heading begins the entry and a metadata footer ends it. The tall variant is 720px high. Imagery is presented in a separate cross-panel layer, not constrained inside this unit.

**Transfer:** Give each entry one product story and one concise supporting classification; choose height for rhythm rather than paragraph length.

### Entry title link

**Use:** Entry identification and direct exploration action.

**CSS:** `position: relative; color: #000000; font-family: "GT America", Arial, sans-serif; font-size: 38px; font-weight: 400; line-height: 1.31; letter-spacing: normal; z-index: 70`

**Text style:** `entry-title` — GT America 400 · 38px/1.31

**Observed:** Plain text at the upper-left corner. The active entry uses an underline and sits above the artwork with a higher layer priority.

**Transfer:** Use an informative product or capability name as the link, rather than adding a separate pill-shaped call to action.

### Metadata footer

**Use:** Classification and compact factual context for an entry.

**CSS:** `display: flex; position: relative; justify-content: space-between; z-index: 90`

**Text style:** `metadata` — GT America 300 · 21px/1.31

**Observed:** Two items align to opposite ends of the bottom edge; the title-to-footer void accommodates the visual story.

**Transfer:** Use a short category on the left and a year, release, count or status on the right. A single fact can stand alone when there is no useful category.

### Entry fact

**Use:** Small right-hand anchor in the metadata footer.

**CSS:** `color: #000000; font-size: 21px; font-weight: 300; line-height: 1.31; letter-spacing: normal`

**Text style:** `metadata` — GT America 300 · 21px/1.31

**Observed:** A compact fact shares the baseline and weight of the descriptive label rather than becoming a badge or oversized statistic.

**Transfer:** Keep factual proof understated and aligned to the panel's right inset.

### Fixed menu button

**Use:** Persistent navigation access without a header band.

**CSS:** `position: fixed; padding: 15px 10px; margin-top: -13px; margin-right: -10px; z-index: 1000; overflow-x: hidden`

**Observed:** Top-right control with a 52px by 46px hit area. Its visible mark is two black horizontal strokes, not three, and remains above the artwork during scrolling.

**Transfer:** Keep only this compact navigation trigger in the corner; supply an accessible name without adding a visible label.

### Floating media stage

**Use:** Large selected artwork spanning the ruled index.

**CSS:** `position: fixed; object-fit: contain; border: 90px solid transparent; box-sizing: border-box; z-index: 88; transition: opacity 0.25s ease-in`

**Observed:** A viewport-sized media layer allows isolated objects to bridge columns. Active title and footer layers sit above it; ordinary index labels can sit behind it.

**States:** Declared: hover and focus-visible styling are not specified; media opacity transition is 0.25s ease-in.

**Transfer:** Use transparent video, an alpha image or a matching-background render of an original product scene. Retain the cross-panel silhouette and generous perimeter.

### Terminal diagonal

**Use:** Index-ending graphic.

**CSS:** `background-image: linear-gradient(to left top, rgba(0, 0, 0, 0) 0%, rgba(0, 0, 0, 0) calc(50% - 0.8px), #d8d8d8 50%, rgba(0, 0, 0, 0) calc(50% + 0.8px), rgba(0, 0, 0, 0) 100%); width: 720px; height: 720px`

**Observed:** A single fine diagonal concludes the second column alongside the final labeled entry.

**Transfer:** Size the square to its column. Keep it purely graphic, without an icon, headline or explanatory caption.

## Imagery and graphics

### Floating miniature worlds

**Use:** Signature visual proof in the opening and throughout the index.

**Observed:** Isometric cutaway environments float without a rectangular image frame. The opening shows a tiny domestic scene with garage, car, lounge and pool; other scenes combine miniature interiors, plants, furniture and musical objects. Soft studio illumination, ambient occlusion, rounded manufactured edges and saturated pastel accents make the forms tactile. The object crosses the middle rule and occupies roughly the central two-thirds of the opening width.

**Transfer:** Translate the product into a small physical world: a few modules, tools or objects on a cutaway platform. Keep an isolated silhouette, readable depth and abundant surrounding ground. A polished three-object diorama is the minimum acceptable version when a richly detailed environment is impractical.

**Build:** Render a shallow platform with rounded or stepped edges, two perpendicular cutaway walls and three to six product-related forms. Use an orthographic three-quarter camera, broad soft area lighting and subtle contact shadows within the object. Mix matte pale surfaces with pink, turquoise and yellow accents; export on alpha and place in Floating media stage so the silhouette crosses both columns. Do not add a rectangular photo backdrop.

### Material-rich object scenes

**Use:** Visual variety within the same floating stage.

**Observed:** Some worlds replace candy colors with navy upholstery, blush panels, marble, warm wood, brushed metal and cloth. Texture stays on the rendered objects; the surrounding page remains flat gray.

**Transfer:** Use a coherent material family for each story while retaining soft lighting, careful bevels and a clean cutout silhouette. Avoid introducing page-level texture to echo the material.

### Sculptural emblem

**Use:** A compact abstract counterpart to the miniature-world device.

**Observed:** The ending carries a diagonally rising segmented emblem with glossy cyan faces, deep blue shading and purple reflective edges, floating across the index. Another scene uses chunky pink, turquoise and electric-blue geometric volumes.

**Transfer:** Create an original product-related emblem or abstract assembly with the same dimensional polish. It should remain an object, not a flat brand stamp.

**Build:** Model a recognizable original silhouette from separated beveled wedges and rounded blocks. Arrange the pieces with narrow air gaps, orient the assembly diagonally upward and use a glossy iridescent material with cyan highlights, blue shadows and violet edge reflections. Render on alpha with a broad studio light; use a small collection of clean beveled solids if complex sculpting is unavailable.

### Icons

**Observed:** The navigation mark is a 32px by 10px SVG made of two black strokes with 3px width and butt caps. Iconography is otherwise sparse; restricted work uses a small lock beside its access label.

**Transfer:** Use simple black geometric marks only when function requires them. Preserve the distinctive two-line menu rather than using a three-line hamburger or a colored circular icon button.

## Section recipes

How recurring sections are built.

### First screen: Cross-panel gallery opening

**Observed:** The first screen starts directly in the Edge-to-edge index, with no introductory banner or navigation band. A 720px square Selected blue stage on the left sits beside a 720px by 480px Ruled panel on the right; the next right-hand entry begins sooner than the next left-hand entry. Titles occupy the upper-left corners with 45px insets and use Entry title link, not a monumental headline. From back to front: gray canvas, panel rules and blue gradient, a large isolated domestic diorama spanning the column division, active underlined title and bottom Metadata footer, then Fixed menu button. The diorama spans roughly 870px in width and about 510px in height within the opening, with its top below the title line and its base near the blue panel's bottom. Within the first 900px, both top titles, active entry description and year, the menu and the whole main scene are visible; the next entries begin at staggered heights and their lower metadata continues below the fold. There is no conventional filled primary button.

**Transfer:** Open a new marketing page with a selected product story and an original floating diorama as the promise and demonstration together. Use a meaningful product name in the active title and a short category at the bottom. Other collection or capability pages can open directly with their strongest entry using the same composition. If elaborate art is unavailable, construct a polished three-object stage rather than replacing it with a text-heavy hero.

**Avoid:** Do not turn this into a centered slogan above a boxed screenshot, or confine the main object to the blue rectangle.

**Text style:** `entry-title` — GT America 400 · 38px/1.31

### Staggered evidence index

**Observed:** Index entry units alternate 480px and 720px heights in two independent stacks. Entry title link stays at the top; Metadata footer stays at the bottom. Floating media stage bridges the resulting misaligned seams, and selected stories may use a colored stage matching the visual.

**Transfer:** Present capabilities, use cases or finished examples as a browseable body of evidence. Select enough entries to tell the product story without forcing a particular count or order.

### Restrained catalog ending

**Observed:** The last labeled Index entry occupies the lower-left side while Terminal diagonal fills the final square on the right. A glossy sculptural emblem spans the two columns above the remaining metadata. The page ends with the same small labels and rules used throughout, not a separate footer or oversized closing call.

**Transfer:** End with a final meaningful example or action-bearing entry and the diagonal closure. If conversion is needed, make that final title a direct action while preserving the catalog framing; do not introduce a new promotional surface.

## Page flow

**Storyline:** Selected visual promise → browseable proof and capability stories → final example with graphic closure.

### A visually led portfolio or product collection that lets the work establish credibility

1. **Promise and demonstration** — One selected colored panel and an oversized floating scene establish the visual language immediately.
2. **Proof and exploration** — A staggered two-column index offers named entries with short classifications and factual anchors; changing sculptural scenes create variety without changing the typography.
3. **Closing proof** — A final named entry and a faint diagonal end mark conclude the browse without a separate sales footer.

**Transfer:** For another product, turn the entries into outcomes, capabilities or use cases, and use the floating object to make each idea tangible. Let the strongest evidence determine the sequence rather than imitating a fixed list.

## Writing

Confident, economical and curatorial. Names and classifications carry the message; there is little explanatory prose and no relentless sales patter.

**Do not copy:** Do not reuse the artist's name, client names, campaign titles, dates, confidential-project implications or proprietary artwork and logos as another product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal labels rather than direct address. Let the product or project name identify itself; reserve a direct verb for a genuine action.
- **Rhythm:** Titles are generally one to four words, classifications one short phrase and facts a single compact item. Fragments and natural capitalization dominate; punctuation is sparse, though a slash or occasional exclamation can appear in a project label.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Entry headline | A plain proper name or concise identifier, without a promotional preamble. | 1–4 words | “Green Mountain Energy”<br>“All Nippon Airways” |
| Classification | A short medium, discipline or product descriptor. | 2–5 words | “Television and Digital”<br>“Digital campaign”<br>“DevOps for Robots.” |
| Status | A compact literal qualification, visually treated as metadata rather than a badge. | 1–2 words | “/ Confidential” |
| Campaign phrase | An occasional compact expressive line among otherwise factual labels. | 3–4 words | “The smarter way”<br>“Build The Tension” |

**Words and phrasing to use:** Specific nouns; Medium and discipline labels; Short product descriptors; Literal statuses

**Avoid:** Revolutionary; Game-changing; Unlock endless possibilities; Long benefit lists; Repeated superlatives

**Rules:**

- Let visual proof carry most of the persuasion.
- Keep classifications distinct from names instead of appending long explanatory subtitles.
- Use dates and factual labels only when they help a reader browse.
- When an action is needed, prefer a short text link integrated into the entry over a separate button slogan.

## Do's and Don'ts

### Do

- Use 38px regular titles and 21px light metadata as the two main text levels.
- Keep all entry content aligned to a 45px inset on desktop.
- Let one polished object bridge the central rule and the staggered horizontal seams.
- Use 1px gray rules instead of gaps between entries.
- Keep the selected title underlined while ordinary titles remain plain.
- Keep the two-stroke 32px menu visible above the media layer.
- Preserve a flat gray page even when the object itself uses rich marble, chrome or fabric.
- Finish with catalog-scale text and a fine graphic closure.

### Don't

- Do not use weight 700 headlines to compete with the artwork.
- Do not turn the gray ground into pure white cards on a darker page.
- Do not round the panel corners or lift them with drop shadows.
- Do not apply the blue stage color to every panel or navigation control.
- Do not replace the 21px metadata with tiny uppercase monospace labels.
- Do not place a logo strip, full navigation bar and paired filled CTA buttons above the index.
- Do not flatten the sculptural media into a grid of framed thumbnails.
- Do not make dates into large numeric proof blocks; their role is a lightweight footer anchor.

## Motion and responsive

### Motion

**Observed:**

- The fixed media layer declares an opacity transition of 0.25s ease-in.
- The artwork changes across the scrolling experience while the top-right menu remains fixed.

**Transfer:**

- Use the declared opacity transition when changing the selected floating scene; keep the typography and panel rules stable.

**Unknown:**

- Exact selection triggers, media playback timing, menu animation, hover and focus-visible appearance are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 768px, 769px and 1280px.
- The desktop composition uses two equal columns and viewport-contained media.

**Transfer:**

- On narrow screens, preserve title and metadata corner anchoring and the isolated object silhouette. A single-column adaptation should keep an artwork layer that can cross entry seams, rather than shrinking the full desktop composition until labels become unreadable.

**Unknown:**

- Actual narrow-screen stacking, typography sizes, panel heights and navigation expansion are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
