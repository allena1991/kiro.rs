# Codex — charcoal and signal lime

## Overview

A dark, technical marketing style with a low-lit data atmosphere and sharply legible grotesk typography. Charcoal panels, gray secondary lines and small electric-lime signals give it the feel of a working infrastructure console rather than a futuristic spectacle. Interface illustrations, monochrome customer marks and restrained portraits supply proof, with dense ruled grids separated by unusually spacious chapter introductions.

### Essentials

- Headlines speak in bright and dim halves: Geist 500 at 56px/0.92 with -0.04em tracking, first line near-white and second line white at 50% over charcoal.
- The opening is a promise inside a data atmosphere: a centered 61.9px/0.92 headline over a faint oversized halftone globe, within a 738px stage below a 64px navigation bar. Recreate the low-lit point field with a product-relevant silhouette when no globe equivalent exists.
- The page behaves like one continuous instrument panel: a 1280px centered frame with 1px #3d4045 side rails and flush, square section grids divided by 1px rules; chapter introductions commonly begin after 192px of breathing room.
- Lime is a signal, not a canvas: #e5ff5d appears in compact 48px-high primary actions, 32px square controls, progress lines and selected phrases. Almost all page area remains #181818 or #1f1f1f; multicolor is concentrated inside product illustrations and ecosystem marks.
- Actions are tiny typographic commands inside blunt rectangles: 12px uppercase Geist 500, -0.02em tracking, 4px corners, with a small dark icon tile leading the lime primary action.
- Demonstrations sit inside ruled stages rather than floating glossy windows: dark rounded interface fragments fade back into the canvas, with compact controls and small lime activation marks. A product workflow panel is the fallback when live data is unavailable.
- A moving assurance ribbon and centered closing question are signature devices: a 100px ruled ticker with 14px copy precedes a 487px call-to-action stage, repeating the bright/dim headline and paired lime/dark actions.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal lime | `#e5ff5d` | `--color-signal` | accent, action, text | Primary actions, active indicators, small icons and highlighted proof. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White proof | `#ffffff` | `--color-white` | surface, text | Recommended plan surface, strong labels and hover links. |
| Soft white | `#e8e8e8` | `--color-headline` | text | Primary headings; also the visible result of white at 90% on charcoal. |
| Reading gray | `#d1d1d1` | `--color-body` | text, link | Body text and links; white at 80% on charcoal. |
| Caption gray | `#a7a7a7` | `--color-caption` | text | Customer-use captions; white at 62% on charcoal. |
| Dim gray | `#8c8c8c` | `--color-muted` | text | Second headline lines, captions and footer labels; white at 50% on charcoal. |
| Structural gray | `#3d4045` | `--color-rule` | border | One-pixel page rails and grid separators. |
| Action hover | `#3a3a3a` | `--color-hover` | action | Declared hover fill for secondary and dark plan actions. |
| Action gray | `#292929` | `--color-button` | action, surface | Secondary action background and FAQ hover fill. |
| Inner panel edge | `#282828` | `--color-subtle-edge` | border | Visible white-at-7% separators on charcoal within interface panels. |
| Raised charcoal | `#1f1f1f` | `--color-panel` | surface | Interface stages and dark pricing cards. |
| Charcoal canvas | `#181818` | `--color-canvas` | background, text | Dominant page background and ink on light panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Code string green | `#97e6b4` | `--color-code-green` | text | Strings in code demonstrations. |

## Typography

- **Geist** — Marketing headings, paragraphs, controls and navigation. Compact contemporary grotesk, regular body and medium headings with pronounced negative tracking. Font stack: "Geist", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Arial, sans-serif.
- **Manrope** (only for customer-use grids) — Customer-use descriptions beneath monochrome logos. Rounded geometric sans that softens the small proof captions. Font stack: "Manrope", Geist, sans-serif.
- **JetBrains Mono** (only for product demonstrations) — Readable code demonstrations. Technical monospaced text with generous line spacing. Font stack: "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | Geist | 500 | 61.9px | 0.92 | -0.04em | Centered two-line opening promise. |
| display | Geist | 500 | 56px | 0.92 | -0.04em | Chapter headings, secondary openings and closing question. |
| feature-heading | Geist | 500 | 32px | 1 | -0.04em | Large illustrated feature titles. |
| card-heading | Geist | 500 | 20px | 1.4 | -0.02em | Benefit titles and accordion labels. |
| quote | Geist | 500 | 20px | 1.2 | -0.04em | Centered testimonial with selected lime phrases. |
| body | Geist | 400 | 16px | 1.4 | -0.02em | Supporting paragraphs beside chapter headings. |
| small-body | Geist | 400 | 14px | 1.4 | -0.02em | Feature descriptions, ticker and footer descriptor. |
| link | Geist | 400 | 14px | 1 | -0.02em | Footer text links. |
| action | Geist | 500 | 12px | 16px | -0.02em, uppercase | Navigation and paired conversion actions. |
| compact-label | Geist | 500 | 12px | 1 | -0.02em, uppercase | Story actions and footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing sections | price | Geist | 500 | 48px | 1 | -0.04em | Plan prices and custom-price label. |
| company narratives | mission | Geist | 500 | 32px | 1.2 | -0.04em | Long editorial belief statement. |
| product demonstrations | code | JetBrains Mono | 400 | 21px | 1.6 | normal | Large query/response illustration text. |
| careers pages | editorial-body | Geist | 400 | 20px | 1.4 | -0.02em | Two-column culture prose. |
| careers pages | role-title | Geist | 500 | 20px | 1.2 | -0.02em | Open-role title. |
| customer-use grids | customer-caption | Manrope | 400 | 14px | 18px | normal | Descriptions under customer logos. |
| careers pages | role-meta | Geist | 500 | 11px | 1 | 0.04em, uppercase | Lime location and compensation metadata. |

**Notes:**

- Headlines are medium, not bold. Their -0.04em tracking and sub-unit display leading create a compact two-line block.
- Keep the same size and weight across bright and dim headline lines; color creates the hierarchy.
- Body and control text use -0.02em tracking. Do not spread uppercase navigation letters apart; the wider tracking belongs only to role metadata.
- Use the main grotesk for marketing; code and customer captions are narrowly scoped exceptions.

## Layout

**Density:** Airy chapter introductions contrast with tightly packed ruled grids and controls.

### Spacing

| Value | Use |
| --- | --- |
| 1px | Grid seams and stacked row separators. |
| 12px | Small control gaps, footer item spacing and accordion interior gaps. |
| 16px | Icon-to-title gap and secondary action side padding. |
| 20px | Standard tile padding and section side inset. |
| 24px | Large feature title-to-copy gap. |
| 32px | Logo-to-caption gap in customer tiles. |
| 40px | Common heading-to-grid offset and ticker interior vertical padding. |
| 46px | Chapter heading-to-demonstration or benefit-grid offset. |
| 64px | Footer column gaps and spacious card interior separation. |
| 112px | First capability introduction top space. |
| 192px | Desktop major chapter top padding. |

### Containers and grids

- **Rail frame**: max width 1280px · side padding 12px. Centered page frame; at 1440px the outer rails sit 80px from either edge. Retain 12px minimum viewport gutters.
- **Heading pair**: max width 1280px · 2 columns · gap 32px · side padding 20px. Broad two-line title at left, support paragraph up to 363px at right, bottom-aligned.
- **Benefit grid**: 3 columns · gap 1px. Equal square-edged columns share ruled boundaries rather than detached cards.
- **Customer grid**: 4 columns · gap 1px. Monochrome logos with optional captions in flush tiles.
- **Demonstration split**: 2 columns · gap 1px. 367px selector column and remaining 910px media stage within the rails.
- **Footer links**: 4 columns · gap 64px · side padding 20px. Four narrow link columns at right of a separate brand descriptor.
- **Plan group** (only for pricing sections): 3 columns · gap 42px. Centered 298px flanking plans around a 360px featured plan, vertically offset by 31px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions | 4px |
|  | Icon controls | 3.2px |
| pricing sections | Plan cards | 16px |
| product demonstrations | Interface fragments | 20px |
| product demonstrations | Large code illustration | 44.7px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing sections | Featured plan | `0px 24px 60px 0px rgba(0,0,0,0.45)` | The white recommended card is lifted against charcoal. |

### Surfaces

#### Rail canvas · level 0

**Use:** Continuous page ground.

**CSS:** `background: #181818; border-left: 1px solid #3d4045; border-right: 1px solid #3d4045`

**Observed:** The same ground continues through opening, chapter gaps, tiles and footer.

**Transfer:** Keep the page visually continuous even when the narrative changes.

#### Ruled grid · level 0

**Use:** Dense feature, proof and resource groups.

**CSS:** `background: #3d4045; display: grid; gap: 1px; border-top: 1px solid #3d4045; border-bottom: 1px solid #3d4045`

**Observed:** Canvas-colored children reveal the background only as hairline seams.

**Transfer:** Use adjoining cells rather than individual bordered floating cards.

#### Dash field · level 0

**Use:** Subtle backing for demonstrations, proof and the closing action.

**CSS:** `background-color: #181818; background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='15' height='15'%3E%3Crect width='7' height='7' rx='1' fill='rgba(255,255,255,0.006)'/%3E%3C/svg%3E")`

**Observed:** A near-invisible repeating square texture provides depth without a colorful gradient.

**Transfer:** Keep it subordinate to every text line.

#### Dark interface panel · level 1

**Only for:** product demonstrations

**Use:** UI fragments within an illustration stage.

**CSS:** `background: #1f1f1f; border-radius: 20px; overflow: hidden`

**Observed:** Rounded panels are partially masked into the surrounding canvas, not used as page-wide containers.

**Transfer:** Use an authentic interface fragment with enough readable detail to demonstrate an outcome.

#### Dark plan · level 1

**Only for:** pricing sections

**Use:** Non-featured pricing options.

**CSS:** `background: #1f1f1f; border: 1px solid rgba(119,128,144,0.3); border-radius: 16px; padding: 20px 12px`

**Observed:** Restrained cool gray edges distinguish these cards from square feature grids.

**Transfer:** Keep these subordinate to the white recommendation.

#### White recommendation · level 2

**Only for:** pricing sections

**Use:** One recommended offering.

**CSS:** `background: #ffffff; color: #181818; border: 2px solid rgba(255,255,255,0.07); border-radius: 16px; padding: 20px 12px 12px; box-shadow: 0px 24px 60px 0px rgba(0,0,0,0.45)`

**Observed:** The bright central card is wider and taller than its flanking cards; its action reverses to dark with lime text.

**Transfer:** Reserve this major light-surface exception for a meaningful commercial recommendation.

## Components

### Navigation

**Use:** Persistent top-level wayfinding.

**CSS:** `position: fixed; top: 0px; height: 64px; z-index: 50; display: flex; align-items: center; justify-content: space-between`

**Text style:** `action` — Geist 500 · 12px/16px · tracking -0.02em · uppercase

**Observed:** Wordmark aligned to the left page rail; compact navigation, a lime signup rectangle and a small theme control at right. The bar is visually integrated with the dark stage.

### Primary button

**Use:** Main conversion in the opening and closing stages.

**CSS:** `background: #e5ff5d; color: #181818; height: 48px; border-radius: 4px; display: inline-flex; align-items: center; gap: 12px`

**Text style:** `action` — Geist 500 · 12px/16px · tracking -0.02em · uppercase

**Observed:** A dark square leading tile contains a lime pixel-like arrow mark; text follows in one line. It is paired with Secondary button.

**Transfer:** Use a simple modular arrow or product-independent pixel mark with a short verb-led label.

### Secondary button

**Use:** Documentation or a supporting proof action.

**CSS:** `background: #292929; color: #ffffff; height: 48px; padding: 0px 16px; border-radius: 4px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `compact-label` — Geist 500 · 12px/1 · tracking -0.02em · uppercase

**Observed:** Plain text rectangle without the primary action's leading tile; used beside primary actions and below testimonial attribution.

**States:** Declared: hover background-color #3a3a3a.

### Square signal control

**Use:** Previous/next story or feature documentation affordance.

**CSS:** `background: #e5ff5d; width: 32px; height: 32px; border-radius: 3.2px; display: flex; align-items: center; justify-content: center`

**Observed:** Dark pixel-like directional glyph centered inside the lime tile; placed at panel edges or bottom-right of features. Some documentation controls grow to 40px.

**States:** Declared: hover scale 1.06; active scale 0.94.

### Benefit cell

**Use:** Concise outcome proof in a ruled row.

**CSS:** `background: #181818; padding: 17px 15px; display: flex; flex-direction: column; justify-content: space-between; gap: 64px; min-height: 366px`

**Text style:** `card-heading` — Geist 500 · 20px/1.4 · tracking -0.02em

**Observed:** Small lime icon and title sit together at the top; 14px explanatory text is anchored near the bottom, leaving a purposeful open center.

### Customer tile

**Use:** Proof of real adoption and use cases.

**CSS:** `background: #181818; padding: 20px; display: flex; flex-direction: column; gap: 32px`

**Text style:** `customer-caption` — Manrope 400 · 14px/18px

**Observed:** A monochrome customer logo occupies a 32px-high top row; a muted description follows. Tiles share grid seams. Logo-only proof uses shallower 96px cells.

### Footer link

**Use:** Secondary navigation within the closing grid.

**CSS:** `color: #d1d1d1; line-height: 1; letter-spacing: -0.02em`

**Text style:** `link` — Geist 400 · 14px/1 · tracking -0.02em

**Observed:** Links sit below muted uppercase column headings, with 12px list spacing.

**States:** Declared: hover color #ffffff.

### Assurance ticker

**Use:** Repeat a small set of conversion reassurances near the close.

**CSS:** `height: 100px; border-bottom: 1px solid #3d4045; display: flex; align-items: center; gap: 64px; overflow: hidden`

**Text style:** `small-body` — Geist 400 · 14px/1.4 · tracking -0.02em

**Observed:** Repeated groups flow beyond the rails. Each short statement has a small gray rounded check tile; no large promotional badges.

### Testimonial

**Use:** A focused customer proof moment.

**CSS:** `max-width: 563px; color: #e8e8e8; text-align: center; margin-top: 29px`

**Text style:** `quote` — Geist 500 · 20px/1.2 · tracking -0.04em

**Observed:** Monochrome customer mark above the quote; selected factual phrases in lime. A small grayscale portrait, name and dim role follow, then Secondary button. Square signal controls flank the full stage and a lime progress line tracks along the bottom.

### Plan card

**Only for:** pricing sections

**Use:** Compare commercial options.

**CSS:** `background: #1f1f1f; border: 1px solid rgba(119,128,144,0.3); border-radius: 16px; padding: 20px 12px; width: 298px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `price` — Geist 500 · 48px/1 · tracking -0.04em

**Observed:** Plan name, audience, price, divider, checked benefits and a full-width action. Recommended option uses White recommendation and adds a compact popularity tag and usage slider.

### Plan action

**Only for:** pricing sections

**Use:** Conversion inside the recommended plan.

**CSS:** `background: #181818; color: #e5ff5d; height: 48px; border-radius: 4px; display: flex; align-items: center; justify-content: center; width: 100%`

**Text style:** `compact-label` — Geist 500 · 12px/1 · tracking -0.02em · uppercase

**Observed:** This inversion belongs on the light recommended plan, not as the default opening action.

**States:** Declared: hover background-color #3a3a3a.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling in a commercial page.

**CSS:** `background: #181818; padding: 20px; display: flex; align-items: flex-start; gap: 12px; text-align: left`

**Text style:** `card-heading` — Geist 500 · 20px/1.4 · tracking -0.02em

**Observed:** Question on the left, expanded 14px answer in a right-hand column, lime modular plus/minus at the far edge. Collapsed rows are 68px high with 1px separators.

**States:** Declared: hover background-color #292929.

## Imagery and graphics

### Halftone data atmosphere

**Use:** A signature low-lit graphic behind the opening promise and as an editorial motif.

**Observed:** An oversized globe made of tiny points rises behind the centered opening copy, tinted a very dim olive-lime. Faint columns of numerals float above it. Company-oriented openings replace the globe with sparse waves of gray digits; the art spans almost the full frame but never competes with text.

**Transfer:** Represent the new product's world as a sphere, network or recognizable silhouette made of points and digits. The minimum equivalent is a broad curved dot field with a few vertically staggered numeral columns, not a stock technology photo.

**Build:** Draw a broad SVG ellipse extending beyond the lower stage, fill a relevant silhouette with a 2px repeating point pattern in rgba(229,255,93,0.10), and overlay digit columns at rgba(229,255,93,0.05). Use a darker center mask behind the text. Fade the bottom with a gradient from transparent to #181818, with the darkest portion concentrated near the bottom. Keep all of this behind the content.

### Illustrated product fragments

**Use:** Capability explanations and interactive demonstrations.

**Observed:** Dark interface slices show lists, line charts, a gauge, wallet balances or code in rounded charcoal frames. Charts use restrained pink or green, code uses pastel syntax colors, and edge gradients conceal panel ends. UI is much larger than supporting copy but sits within a hard-edged ruled stage.

**Transfer:** Show the new product's actual output in one coherent interface fragment. Use a simplified but plausible static workflow if live functionality is unavailable; preserve charcoal backing, legible details and edge fades.

**Build:** Place an interface panel on Dash field, add a 20px radius, and mask its far and bottom edges with transparent-to-#181818 gradients. Use thin SVG chart strokes or a short monospace query/response instead of decorative 3D objects.

### Ecosystem constellation

**Use:** Breadth or coverage demonstration.

**Observed:** A compact globe-like cluster of multicolor circular ecosystem marks floats in a wide dark stage. The color occupies only the central cluster; the adjacent quantified selector remains monochrome with lime signals.

**Transfer:** Use relevant integrations or supported categories as a compact clustered diagram, not an edge-to-edge logo collage.

**Build:** Arrange circular marks in concentric, irregular rings, with larger discs toward the front and small discs around the perimeter. Keep the cluster roughly 380px across inside a 910px stage; use 20px–40px discs and a Dash field backing. If partner marks are unavailable, use simple category glyphs with restrained colors.

### Monochrome proof marks

**Use:** Customer, partner and investor recognition.

**Observed:** White or gray logo artwork remains flat on charcoal without individual colored backplates. Customer-use logos are small and left-aligned; investor marks are centered in larger cells. Testimonial portraits are small, square, grayscale and lightly rounded.

**Transfer:** Normalize genuine proof assets by luminance and optical scale; keep personal portraits secondary to the quote.

### Icons

**Observed:** Small modular, pixel-like directional and plus symbols in lime recur at panel edges. Supporting category icons are thin and geometric, commonly 20px; checks are white inside small gray squares, with 12px-wide filled check glyphs.

**Transfer:** Choose simple geometric symbols with a shared box size; use pixel-step arrows for action emphasis rather than a large conventional chevron or ornamental icon set.

## Section recipes

How recurring sections are built.

### First screen: Data atmosphere opening

**Observed:** A 64px fixed Navigation sits above a 738px full-width stage inside Rail canvas. Back to front: charcoal ground, dim halftone globe and numeral atmosphere, bottom fade, centered text and actions, then a bracketed strip of monochrome proof marks. The 61.9px headline forms two compact lines in a block about 520px wide; the first screen centers the promise rather than splitting text from media. A narrow two-line support statement sits below it, followed by Primary button and Secondary button, and a spaced proof strip. The globe spans most of the frame behind all of them. Within the first 900px the complete stage, actions and proof marks are visible; the next chapter title remains below the fold.

**Transfer:** Use the same centered promise and low-lit point silhouette for a different product. If no literal object is useful, create an abstract curved data field. Commercial pages instead open with a left-aligned display pair and immediate plan group after generous top space; company and careers pages use left-aligned display pairs over digit fields, with supporting copy low on the right.

**Avoid:** Do not turn the opening into a bright dashboard screenshot beside a left-aligned oversized headline, or make the globe a saturated neon centerpiece.

**Text style:** `hero` — Geist 500 · 61.9px/0.92 · tracking -0.04em

### Chapter heading pair

**Observed:** Display headline on the left, first line bright and continuation dim, support copy at right up to 363px wide and aligned to the bottom of the title. Most chapters use 192px top padding and 40px–46px before the next ruled stage.

**Transfer:** Split one grammatical promise across two lines; use the support paragraph for concrete detail rather than another slogan.

**Text style:** `display` — Geist 500 · 56px/0.92 · tracking -0.04em

### Capability bento

**Observed:** A wide feature and narrower feature share an upper ruled row, followed by three equal cells. Large feature titles use feature-heading; supporting text is small-body. Interface fragments occupy the centers and Square signal controls sit near the lower-right corners.

**Transfer:** Group complementary outcomes, giving the most visual capability more width without introducing detached card spacing.

### Selector and demonstration

**Observed:** A 367px vertical selector sits beside a 910px Dash field stage. Collapsed selectors are 56px rows; the active one expands to reveal supporting text, a lime progress rule and a matching product illustration. A related tabbed variant uses five equal 69px-high tabs over a chart and query/response split.

**Transfer:** Use this for mutually exclusive product workflows, keeping one story expanded at a time.

### Ruled proof grid

**Observed:** Customer tile repeats in four columns with shared 1px seams; logo-only proof uses 96px-high cells and use-case captions use 140px-high cells.

**Transfer:** Choose logo-only for recognition and captioned tiles when the diversity of actual use is important.

### Centered proof stage

**Observed:** Testimonial is centered in a 531px-high ruled stage backed by Dash field. Logo, quote, portrait, attribution and story action create a vertical stack. Lime highlights and a thin bottom progress line supply almost all color.

**Transfer:** Use one substantive customer outcome at a time, with a credible person and a short factual emphasis.

### Sparse benefit row

**Observed:** Three Benefit cells sit flush in Ruled grid. Icon/title groups remain at the top while detailed copy sits low, producing a tall intentional pause within each cell.

**Transfer:** Use for a small set of infrastructure or reliability benefits, keeping the explanatory copy concise.

### Commercial recommendation

**Observed:** A 700px ruled stage holds two dark Plan cards and a wider, taller White recommendation in the center. The white card contains a compact popularity tag, benefits, usage slider, cost summary and Plan action. Beneath the cards, small quantitative proof cells continue the ruled system.

**Transfer:** Give the strongest contrast to one useful recommendation. On a dedicated commercial page, follow with a four-column feature matrix using 32px rows and 56px group headings.

**Text style:** `price` — Geist 500 · 48px/1 · tracking -0.04em

### Question list

**Observed:** FAQ row repeats with 1px seams; one answer opens in the right column while other rows stay compact. The heading pair retains the same bright/dim treatment as other chapters.

**Transfer:** Answer purchase and integration objections with specific plain language rather than adding another promotional card grid.

### Ribbon close and utility footer

**Observed:** Assurance ticker leads into a 487px Dash field stage. A centered two-line 56px bright/dim question, narrow support paragraph and repeated Primary button/Secondary button pair form the close. Footer remains within the same rails: brand descriptor left, four link columns right, 56px vertical padding, then a separate 61px legal strip with 24px vertical padding.

**Transfer:** Keep the ribbon and centered closing question as recognizable devices even on shorter editorial or recruiting pages. Adapt the reassurances and action to the new product; keep utility navigation below the conversion moment.

**Text style:** `display` — Geist 500 · 56px/0.92 · tracking -0.04em

### Company narrative checkerboard

**Only for:** company narratives

**Observed:** Two columns alternate text-bearing cells across four 312px-high rows with 1px seams. Short 20px titles sit high and 16px story paragraphs sit low. Small lime markers punctuate the central seam. A 518px digit-field band follows with a muted label and a broad 32px statement.

**Transfer:** Use alternating positions to tell a real origin or process narrative. Preserve deliberate empty counter-cells as editorial pacing, not as missing illustration slots.

**Text style:** `mission` — Geist 500 · 32px/1.2 · tracking -0.04em

### Culture and role listing

**Only for:** careers pages

**Observed:** Two equal prose columns use editorial-body within a ruled band. Roles appear in three 220px-high linked cells, with lime role-meta, title, small description and a View role action with square arrow.

**Transfer:** State working conditions plainly beside the roles heading and keep compensation metadata easy to scan.

**Text style:** `editorial-body` — Geist 400 · 20px/1.4 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible capability → adoption and operational proof → commercial or editorial detail → reduced-friction closing action → utility navigation.

### Product marketing landing page

1. **Promise** — Centered benefit statement, low-lit data object, paired actions and bracketed proof marks.
2. **Capability demonstration** — Illustrated bento and interactive tabbed output stage.
3. **Adoption proof** — Captioned customer grid and an integration selector with code output.
4. **Operational proof** — Centered testimonial and sparse three-column benefits.
5. **Commercial detail** — Contrasting recommended plan, quantitative proof and coverage constellation.
6. **Related exploration** — Ruled resource tiles point to adjacent capabilities.
7. **Closing action** — Assurance ribbon, centered closing question and multi-column footer.

**Transfer:** Use the demonstration-rich default for a new product; vary the number and ordering of proof chapters to fit the actual story.

### Commercial comparison and objection handling

1. **Pricing** — Left-aligned display pair and three-plan recommendation stage.
2. **Comparison** — Four-column matrix with a persistent header and expandable feature groups.
3. **Capability reassurance** — Integration selector and concise feature-benefit row.
4. **Social proof** — Centered testimonial stage.
5. **Objection handling** — Ruled FAQ with right-column answers.
6. **Closing action** — The same assurance ribbon, centered conversion stage and utility footer.

**Transfer:** Prioritize real plan differences and readable comparison; retain product proof without repeating a full landing page.

### Recruiting and working-culture introduction

1. **Team promise** — Left-aligned bright/dim headline over a digit atmosphere, support low on the right.
2. **Culture context** — Two equal columns of larger body prose.
3. **Opportunity** — Three role cells with geographic and compensation metadata.
4. **Closing action** — Product assurance ribbon and conversion stage followed by the shared footer.

**Transfer:** Keep the short editorial path focused on working conditions and real openings, while preserving the shared visual ending.

### Company origin, mission and institutional proof

1. **Positioning** — Wide digit atmosphere with left-aligned promise and lower-right factual support.
2. **Origin narrative** — Alternating text cells with lime seam markers.
3. **Long-term belief** — A broad 32px statement over the low-lit digit field.
4. **Adoption proof** — Four-column monochrome customer matrix.
5. **Institutional proof** — Three-column investor mark matrix.
6. **Closing action** — Assurance ribbon, centered conversion question and shared utility footer.

**Transfer:** Tell the new organization's own origin and belief; use actual external proof without expanding into a generic team-photo collage.

## Writing

Confident, builder-facing and practical. Technical specificity is balanced with conversational descriptions of the work and frustration the product removes.

**Do not copy:** Do not reuse Codex names, logos, customer or investor assets, testimonials, compensation, network counts, performance claims, prices or other proprietary facts. Replace all of them with verified material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use 'you' for the builder's goal and 'we' for the operational burden the product takes away; name the product directly in factual support.
- **Rhythm:** Short, two-part headlines of roughly 3–8 words; one or two compact support sentences. Longer narrative prose stays confined to company and culture content.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An imperative tied to an immediate product benefit. | 6–9 words | “Build with real-time crypto market data.” |
| Chapter heading | Contrast the user's desired work with the burden removed. | 4–7 words | “Ship products not infrastructure”<br>“Built to plug into anything” |
| Supporting paragraph | Concrete operational pain followed by the user's outcome. | 15–30 words | “We handle the indexing headaches and the breaking changes at 2AM. You focus on building products your users love.” |
| Primary action | Plain verb, quick start and reduced friction. | 2–5 words | “Start building for free”<br>“Get started” |
| Narrative title | First-person admission or a matter-of-fact realization. | 4–6 words | “We were frustrated builders”<br>“No one was doing it right” |
| Closing question | Ask whether the reader is ready for the core benefit. | 8–12 words | “Ready to have the fastest onchain data?” |

**Words and phrasing to use:** build; ship; real-time; reliable; plug into; source of truth; maintenance; worked examples; in minutes

**Avoid:** revolutionary; magical; game-changing; unleash; limitless possibilities; excessive exclamation marks

**Rules:**

- Pair a technical capability with a recognizable user benefit.
- Use numbers only when they substantiate an outcome or clarify a commercial limit.
- Prefer literal action labels over clever campaign slogans.
- Use contractions and occasional concrete operational details to keep infrastructure language human.

## Do's and Don'ts

### Do

- Keep desktop chapter titles at 56px/0.92 and -0.04em tracking.
- Carry the 1px side rails through the close and footer.
- Use 192px chapter top spacing to contrast with 1px grid seams.
- Keep conversion controls 48px high with 4px corners.
- Anchor benefit text low in the 366px ruled cells.
- Normalize proof logos to monochrome and keep caption text at 14px/18px.
- Limit lime to commands, small controls, progress and brief factual emphasis.
- Use the 100px assurance ribbon and centered closing question to give even short pages a complete ending.

### Don't

- Do not replace the charcoal ground with pure black; the intended base is #181818.
- Do not turn ordinary feature cells into 16px-radius floating cards; that radius belongs to plans.
- Do not make display headlines 700 weight or loosen their tracking.
- Do not apply the 11px metadata's positive tracking to the 12px navigation.
- Do not use white cards across every proof or benefit section; the bright card is a commercial exception.
- Do not fill large marketing bands with lime or add rainbow gradients behind headings.
- Do not put JetBrains Mono on all marketing copy just because the product is technical.
- Do not give every surface a drop shadow; the featured plan carries the main elevation effect.

## Motion and responsive

### Motion

**Observed:**

- Declared color transitions use 0.15s cubic-bezier(.4,0,.2,1); square story controls use scale over 0.15s cubic-bezier(.16,1,.3,1).
- Declared square control states are scale 1.06 on hover and 0.94 when active.
- Assurance marquees declare 40s linear infinite animation.
- Chapter content uses rise/fade and blur-to-clear treatments; declared rise/fade durations include 1.2s and 1.8s with cubic-bezier(.08,1,.2,1).
- Selector progress animations declare several durations, including 10s linear and 12s cubic-bezier(.45,0,.55,1).

**Transfer:**

- Keep the ribbon continuously moving as a narrow supporting signal rather than making the main headline a marquee.
- Tie lime progress marks to the selected demonstration or testimonial.
- Use the short scale response only on compact square controls, not entire page panels.

**Unknown:**

- Exact playback sequence of the data art and all selector interactions.
- Focus-visible styling was not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px, with additional fine-grained rules.
- Main frame retains a 12px minimum side gutter and 1280px maximum width.
- Several chapter sections declare 96px top padding below the desktop 192px setting; chapter headings include a 32px base size.
- Customer grids declare two columns before four at desktop; footer grids progress through two, three and four columns.

**Transfer:**

- On narrower screens, stack heading and support, preserving bright/dim line hierarchy.
- Collapse the demonstration split into a vertical selector and its corresponding panel; do not squeeze readable code into a miniature desktop layout.
- Stack plans with the recommended option retaining its light surface; keep the closing question and paired actions centered.

**Unknown:**

- Exact mobile composition and all breakpoint-specific typography sizes were not established.
- Touch behavior and reduced-motion treatment are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
