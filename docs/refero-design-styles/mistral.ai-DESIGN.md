# Mistral — pixel warmth, industrial grids

## Overview

A warm, light technical identity that pairs monumental grotesk sentences with playful pixel objects and an almost architectural framework of fine rules. Cream and stone dominate, with concentrated yellow, orange and red artwork and occasional deep navy chapters. Colorful diagrams, staged interface fragments and natural editorial photography give complex products an approachable but serious presence; spacious marketing compositions can give way to dense comparison tables.

### Essentials

- Headlines behave like plainspoken monuments: medium-weight ALTMistral at 96px/1 with -0.02em tracking, black on warm paper; section statements step down to 56px/60px with -0.01em tracking.
- The opening is a sentence in a playground, not a dashboard: a centered two-line headline in a 700px stage, sparse pixel objects at its edges, 120px warm-color blocks and one compact bordered announcement below it.
- Architecture stays visible: 1px #e4e3de rules connect square-edged modules, 40px desktop side gutters and card padding; the main chapters pair a quarter-width navigation rail with three-quarter-width content.
- Actions are compact rounded rectangles, never capsules: 48px height, 6px radius and 8px 16px padding, with a small right chevron; the default discovery action is pale gray rather than orange.
- Color lives inside objects and bounded scenes: most reading area remains #fbfbf8 or #f5f4ef, while yellow-to-red pixels, bright proof panels and a #151524 resource chapter provide concentrated contrast. Include pixel geometry and a colored proof or product scene on every landing page.
- The ending is a designed object: three ruled link columns give way to a utility area with a centered 240px-wide black pixel silhouette, then four full-width 64px warm-color stripes. Use an original block-built product symbol if there is no mascot; preserve the oversized silhouette and striped horizon.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ember | `#ff5229` | `--color-ember` | accent, background | Pixel blocks, highlighted plan banner, second horizon stripe and the product closing band. |
| Midnight navy | `#151524` | `--color-night` | background, surface | Resource chapters and dark diagram stages. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pixel yellow | `#ffaf01` | `--color-sun` | accent, surface | Pixel objects, active tab markers and diagram highlights. |
| Orange | `#ff8204` | `--color-orange` | accent, surface | Illustrated objects and upper stripe of the closing horizon. |
| Signal red | `#e51300` | `--color-red` | accent, background | Pixel illustrations and third horizon stripe. |
| Deep red | `#c4001d` | `--color-crimson` | accent, background | Bottom horizon stripe and darkest warm pixels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Discovery gray | `#f4f4f5` | `--color-button` | action, surface | Default discovery button fill. |
| Action black | `#09090b` | `--color-action-black` | action | Login and high-intent conversion buttons. |
| Primary ink | `#18181b` | `--color-ink` | text | Headlines, navigation, controls and primary labels. |
| Body ink | `#27272a` | `--color-body` | text | Default long-form paragraphs. |
| Navy rule | `#31313a` | `--color-night-rule` | border | Dividers within navy chapters. |
| Secondary ink | `#3f3f46` | `--color-tertiary` | text | Footer group titles, supporting labels and FAQ answers. |
| Muted gray | `#71717b` | `--color-muted` | text | Inactive headings, explanatory labels and small secondary text. |
| Paper rule | `#e4e3de` | `--color-rule` | border | The continuous fine grid around panels and sections. |
| Inverse text and hover gray | `#e4e4e7` | `--color-inverse` | text, action | Text on navy sections and hover fill of discovery buttons. |
| Translucent action wash | `#efefec` | `--color-soft-action` | action | Visible result of rgba(7, 7, 11, 0.05) over warm paper for secondary customer actions. |
| Warm stone | `#f5f4ef` | `--color-stone` | surface, background | Concept bands, inactive accordion panels and ordinary plan cards. |
| Action off-white | `#fafafa` | `--color-action-white` | text | High-intent button labels. |
| Warm paper | `#fbfbf8` | `--color-canvas` | background, surface | Default page canvas and active panels. |
| White | `#ffffff` | `--color-white` | text | Quotes on bright media panels and headlines on orange closing bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial update collections | Navy card | `#242433` | `--color-night-card` | surface | Raised tonal cards inside dark editorial collections. |
| editorial update collections | Navy secondary text | `#9f9fa9` | `--color-night-muted` | text | Dates and authors beneath dark editorial cards. |

## Typography

- **ALTMistral** — Headlines, feature titles, navigation and button labels. Compact contemporary grotesk with rounded bowls, open counters and a restrained medium weight. If unavailable, use **Inter**. Use 500; preserve tight tracking and tune line breaks to the compact original. Font stack: "ALTMistral", "Inter", sans-serif.
- **Inter** — Paragraphs, supporting copy and metadata. Neutral, highly legible sans with a less compact reading texture. Font stack: "Inter", sans-serif.
- **Space Mono** — Technical breadcrumbs, diagram labels, dates and editorial category tags. Small utilitarian monospace, usually uppercase. Font stack: "Space Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ALTMistral | 500 | 96px | 1 | -0.02em | Default centered opening headline. |
| heading-lg | ALTMistral | 500 | 56px | 60px | -0.01em | Major section promises and numbered capability chapter titles. |
| heading | ALTMistral | 500 | 44px | 52px | -0.01em | Section headers, closing statements and price numerals. |
| feature-heading | ALTMistral | 500 | 32px | 1.25 | normal | Split feature row titles, quotes and resource card titles. |
| card-heading | ALTMistral | 500 | 24px | 32px | normal | Tabs, chip labels, feature subheadings and FAQ questions. |
| body | Inter | 400 | 16px | 1.5 | normal | Long-form body and feature descriptions. |
| compact-body | Inter | 400 | 16px | 1.5 | -0.01em | Resource card descriptions and short secondary copy. |
| action | ALTMistral | 500 | 16px | 1.5 | 0.01em | Navigation and standard button labels. |
| label | ALTMistral | 500 | 16px | 1.5 | normal | Announcement labels, footer links and table values. |
| small-action | ALTMistral | 500 | 14px | 20px | 0.02em | Language control and compact action labels. |
| caption | Inter | 400 | 13px | 20px | normal | Metadata, plan details and supporting notes. |
| eyebrow | Space Mono | 400 | 11px | 16px | normal, uppercase | Technical breadcrumbs, small tags and diagram markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial and company openings | editorial-display | ALTMistral | 500 | 96px | 1 | -0.02em | Bottom-aligned two-line opening statement beside a symbol or mission summary. |
| flagship product openings | product-display | ALTMistral | 500 | 71.9px | 1 | -0.02em | A wide single-line product promise over a diagram stage. |

**Notes:**

- Keep the grotesk at 500 throughout the hierarchy; scale, whitespace and line breaks create emphasis rather than bold weight changes.
- Tracking tightens from normal at 32px and 24px to -0.01em at 44px and 56px, and -0.02em at display scale. Button labels instead open to 0.01em.
- Use sentence case and retain terminal punctuation in statement headings; reserve uppercase for tiny mono markings.

## Layout

**Density:** Airy at the narrative scale, compact inside controls and technical comparison content; wide pauses surround closely ruled modules.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Title-to-body gap in split features and icon-to-label gaps. |
| 12px | Stacked discovery action gaps. |
| 16px | Short copy stacks, utility gaps and inset proof-grid spacing. |
| 24px | Feature subheading-to-body gaps and footer column rhythm. |
| 40px | Default desktop gutter, module padding and major internal gaps. |
| 80px | Section padding and chapter title-to-description separation. |
| 120px | Chapter title-to-diagram separation. |
| 128px | Resource title-to-description separation and footer utility breathing space. |
| 160px | Large editorial headline lead-in. |

### Containers and grids

- **page frame**: max width 1728px · side padding 40px. Centered outer frame. At a 1440px desktop width most content spans 1360px between gutters; rules can run to the viewport edge.
- **chapter rail**: 4 columns · gap 0px. A quarter-width rail beside three-quarter-width chapters, with a visible vertical boundary; at desktop the content region is 1020px wide.
- **centered statement**: max width 1024px. Centered editorial promises with controlled two-line wrapping.
- **resource grid**: 3 columns · gap 0px. Three equal contiguous ruled cards, approximately 453px wide at desktop.
- **plans** (only for pricing pages): 4 columns · gap 0px. Four contiguous 340px-wide plans, aligned at their bases. The recommended plan rises 40px above its neighbors.
- **editorial slider** (only for company histories and update collections): gap 8px. 448px-wide cards in an overflowing horizontal strip, with another card partially visible.

## Corner radius

| Element | Radius |
| --- | --- |
| main modules | 0px |
| buttons | 6px |
| announcement | 8px |
| chapter navigation | 12px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default reading ground.

**CSS:** `background: #fbfbf8; color: #18181b`

**Observed:** Warm rather than pure white; large quiet fields remain visibly structured by hairlines.

**Transfer:** Keep this ground continuous through most of a landing page.

#### Stone band · level 0

**Use:** Concept illustration sections and inactive panels.

**CSS:** `background: #f5f4ef`

**Observed:** A subtle warm shift, not a gray floating card.

**Transfer:** Use to separate an abstract narrative from product explanation.

#### Ruled module · level 1

**Use:** Feature rows and joined content cells.

**CSS:** `border-right: 1px solid #e4e3de; border-bottom: 1px solid #e4e3de; border-radius: 0px; padding: 40px`

**Observed:** Cells share edges and sit on the page rather than floating above it.

**Transfer:** Join repeated modules into one architectural grid.

#### Navy chapter · level 0

**Use:** Deeper resources and selected technical artwork.

**CSS:** `background: #151524; color: #e4e4e7; border-top: 1px solid #31313a`

**Observed:** Light typography and low-contrast navy dividers preserve the same grid language.

**Transfer:** Concentrate dark contrast into a bounded chapter rather than converting the whole page to dark mode.

#### Orange closing band · level 0

**Only for:** flagship product conversion sections

**Use:** A final high-intent invitation.

**CSS:** `background: #ff5229; color: #ffffff; padding: 40px 40px 80px`

**Observed:** A 380px-high band with fine grain, bottom-aligned statement and a pale action at the opposite side.

**Transfer:** Use a short distinctive outcome, not a second hero.

#### Dark editorial card · level 1

**Only for:** editorial update collections

**Use:** News or research collections within a navy chapter.

**CSS:** `background: #242433; border: 1px solid #31313a; border-radius: 0px`

**Observed:** Artwork above text; the metadata footer is ruled into small cells.

**Transfer:** Keep surfaces tonal, with illustration providing most of the contrast.

## Components

### Navigation cell

**Use:** Persistent desktop top navigation.

**CSS:** `height: 48px; padding: 0px 16px; display: flex; align-items: center; border-right: 1px solid #e4e3de`

**Text style:** `action` — ALTMistral 500 · 16px/1.5 · tracking 0.01em

**Observed:** Logo is the leftmost cell; ordinary navigation clusters left, contact and black Login sit at the right. The overall fixed header includes a bottom rule and is 49px high.

**States:** Declared: hover background-color #fbfbf8.

**Transfer:** Keep the segmented full-width bar and the strong rightmost utility cell.

### Discovery button

**Use:** Default landing-page action for learning about a capability.

**CSS:** `background: #f4f4f5; color: #18181b; border-radius: 6px; height: 48px; padding: 8px 16px; display: flex; align-items: center; gap: 8px`

**Text style:** `action` — ALTMistral 500 · 16px/1.5 · tracking 0.01em

**Observed:** Text precedes a small right chevron. Width follows content; multiple discovery actions stack rather than forming a broad filled bar.

**States:** Declared: hover background-color #e4e4e7.

### Announcement card

**Use:** Single compact action near the bottom of the opening stage.

**CSS:** `background: #fbfbf8; border: 1px solid #e4e3de; border-radius: 8px; padding: 4px 12px 4px 4px; display: flex; align-items: center; gap: 16px`

**Text style:** `label` — ALTMistral 500 · 16px/1.5

**Observed:** Small square illustrated thumbnail, short release label, right chevron. The original construction occupies 180px by 58px.

**Transfer:** Use a real release, event or meaningful product shortcut, with only one label.

### Concept chip

**Use:** Objects in a connected conceptual illustration.

**CSS:** `background: #f5f4ef; border: 1px solid #e4e3de; padding: 8px 16px; border-radius: 0px`

**Text style:** `card-heading` — ALTMistral 500 · 24px/32px

**Observed:** Alternates muted text-only chips and paper chips with a tiny colorful pixel icon. Small black square terminals sit at the midpoint of the left and right edges.

**Transfer:** Use short nouns for the new product's assets or outcomes; connect them to fine diagram lines.

### Feature row

**Use:** Core benefit explanation beside product imagery.

**CSS:** `display: flex; gap: 40px; padding: 40px; border-right: 1px solid #e4e3de; border-bottom: 1px solid #e4e3de`

**Text style:** `feature-heading` — ALTMistral 500 · 32px/1.25

**Observed:** A narrow text column holds a title, body and Discovery button; a larger rectangular image occupies about two thirds of the inner width. Alternate which side carries the image across rows.

**Transfer:** Show one capability per row; keep the paragraph subordinate to the title.

### Feature selector

**Use:** Tabbed capability or customer proof sections.

**CSS:** `background: #f5f4ef; padding: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-heading` — ALTMistral 500 · 24px/32px

**Observed:** Stacked ruled selectors share a frame with a large media region. Inactive labels are muted; active panel turns paper-colored and reveals supporting copy, with a thin yellow edge marker.

**Transfer:** Use a single active item and connect each selection to a genuinely different diagram or proof panel.

### Resource card

**Use:** Three-way deeper exploration in a dark chapter.

**CSS:** `padding: 40px; border-right: 1px solid #31313a; display: flex; flex-direction: column; justify-content: space-between; gap: 128px`

**Text style:** `feature-heading` — ALTMistral 500 · 32px/1.25

**Observed:** Small monochrome icon above the title, descriptive copy pinned near the bottom; no detached floating-card outline.

**Transfer:** Link to distinct layers of information rather than duplicating sales actions.

### Footer column

**Use:** Grouped link navigation at the page ending.

**CSS:** `padding: 40px 24px; border-right: 1px solid #e4e3de; display: flex; flex-direction: column; gap: 24px`

**Text style:** `label` — ALTMistral 500 · 16px/1.5

**Observed:** Three equal columns. A quieter body-font group title sits above a compact list with 4px gaps; the lower utility area and striped artwork sit outside the columns.

**Transfer:** Group by visitor intent, product depth and organization information.

### Conversion button

**Only for:** pricing and flagship product conversions

**Use:** Sales and start actions.

**CSS:** `background: #09090b; color: #fafafa; border-radius: 6px; height: 48px; padding: 8px 16px`

**Text style:** `action` — ALTMistral 500 · 16px/1.5 · tracking 0.01em

**Observed:** Uses the same text-and-chevron construction as Discovery button; plan actions span the usable card width.

**States:** Declared: hover background-color #18181b.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side commercial tiers.

**CSS:** `background: #f5f4ef; outline: 1px solid #e4e3de; display: flex; flex-direction: column; justify-content: space-between; max-width: 440px`

**Text style:** `card-heading` — ALTMistral 500 · 24px/32px

**Observed:** Icon and tier name precede the promise, large price and small details. Feature bullets occupy the middle; a separated bottom shelf holds Conversion button. Recommended plan is paper-colored with an orange banner above it.

**Transfer:** Keep price numerals at heading scale and unit suffixes at 32px in muted gray; preserve aligned action shelves.

### FAQ row

**Only for:** pricing and objection-handling sections

**Use:** Questions in a ruled accordion.

**CSS:** `padding: 24px 16px; display: flex; align-items: center; justify-content: space-between; gap: 16px`

**Text style:** `card-heading` — ALTMistral 500 · 24px/32px

**Observed:** Question aligned left and chevron right. Answer uses body copy below. Closed rows are about 81px high including the rule; the chevron rotates when open.

**Transfer:** Place a substantial section title in the left column and a wider question stack at right.

### Editorial card

**Only for:** editorial update collections

**Use:** Image-led updates in a horizontal collection.

**CSS:** `background: #242433; border: 1px solid #31313a; display: flex; flex-direction: column`

**Text style:** `card-heading` — ALTMistral 500 · 24px/32px

**Observed:** Landscape artwork spans the top, followed by a tiny category tag, title and compact description. The bottom edge is divided into date, author and arrow cells.

**States:** Declared: hover background-color #151524.

**Transfer:** Use original diagram or pixel artwork related to the update rather than generic stock banners.

## Imagery and graphics

### Pixel playground

**Use:** Required graphic vocabulary of the opening and recurring product moments.

**Observed:** Small crisp sprites sit on large yellow, orange and red squares at the edges of an otherwise spare paper stage. One warm-striped pixel symbol can sit inline with the headline; thin arcs and square anchor points make the scene feel engineered rather than cartoonish.

**Transfer:** Invent a simple product-related block symbol and a few tiny object sprites. A minimum version is a crisp 8-bit tool or abstract emblem on stepped warm blocks, not a smooth illustration.

**Build:** Draw an original silhouette on an 8px SVG grid using rects, then scale with crispEdges. Assemble the stage edges from 120px squares and 60px half-blocks in pixel yellow, ember and orange; rotate one square 45deg. Behind them add 1px paper-rule arcs and straight vertical guides with 4px ink anchor squares. Keep the center largely empty.

### Connected concept field

**Use:** A large conceptual promise expressed as a playful diagram.

**Observed:** A stone field holds staggered rows of Concept chip objects. Very thin diagonal strings cross the entire width behind them, with tiny square nodes at chip edges. A centered heading remains clearly above the dense part of the field.

**Transfer:** Turn product inputs, constraints or outcomes into movable-looking labeled objects. Keep some muted and some illustrated, rather than coloring every chip.

**Build:** Use an SVG behind absolutely arranged HTML chips; draw 1px #e4e3de paths from offscreen left and right through chip-center endpoints. Put 4px #18181b squares at the chip terminals. Stagger roughly three chips per row across four rows; use an accessible stacked wrap of the same labels when space is limited.

### Color-block product scenes

**Use:** Product demonstrations occupying the larger side of Feature row.

**Observed:** Rectangular green, blue, hot orange or yellow mosaics form the backing for isolated interface snippets, a code panel, a server diagram or a sticker board. UI is staged as one focused object, not a full browser screenshot; geometry and fine lines remain visible behind it.

**Transfer:** Make a simplified, believable fragment of the new interface or a block diagram. If UI is unavailable, use labeled workflow blocks on a bright tiled field.

**Build:** Lay out uneven rectangles on a coarse grid, varying opacity over one saturated base hue. Add a finer 1px low-alpha grid and one centered paper or navy panel. Allow an occasional small pixel object to overlap the panel edge; keep corners mostly square and avoid a heavy drop shadow.

### Technical diagram plates

**Use:** Numbered capability chapters and detailed product narratives.

**Observed:** Wide pale plates, often about 938px by 499px, show yellow and orange blocks connected by thin gray orthogonal paths with black anchor points. Dark variants use a navy stage, wireframe grids and a luminous pixel object at the center; small mono labels look like engineering annotations.

**Transfer:** Translate the actual product workflow into a few legible nodes. The minimum acceptable artwork is a careful SVG block diagram, not an empty decorative rectangle.

**Build:** Create an SVG with a pale stone background, rect nodes in pixel yellow and orange, 1px connecting paths with right-angle turns and 4px square terminals. Keep labels short and attach them to nodes. Dark variant swaps the backing to midnight navy and draws a low-alpha white grid around a warm pixel symbol.

### Bright proof panel

**Use:** A vivid human proof element within an otherwise neutral customer section.

**Observed:** Two small paper proof cells sit beside a taller richly colored quote panel. White 32px quote text is placed over subtle red contour-like or flowing texture, with attribution low in the panel.

**Transfer:** Use a verified customer outcome and an attributed quote. Keep color in the large quote panel, not every adjacent cell.

**Build:** Fill a rectangle with signal red and add low-opacity curving SVG contour lines in deeper red. Set white quote text at the top with 24px inset and an attribution near the bottom. For other proof types, keep the same saturated panel-to-paper-cell contrast.

### Striped closing horizon

**Use:** Required terminal artwork beneath the footer utility area.

**Observed:** A large black pixel silhouette rises from the center of the paper footer into a full-width warm horizon. Four 64px horizontal stripes descend from orange through ember and red to crimson; faint drafting arcs and a small pixel figure give it depth.

**Transfer:** Replace the silhouette with an original geometric product emblem. Preserve its scale, placement at the stripe boundary and warm horizontal layering.

**Build:** Stack four 64px-high full-width bands in orange, ember, signal red and deep red. Add a very subtle grain overlay and 1px rgba(24,24,27,0.08) arcs. Center a 240px-wide block-built ink silhouette immediately above the bands; place one tiny original sprite away from center within a lower stripe.

### Editorial people and places

**Only for:** company and culture narratives

**Use:** Human context and team profiles.

**Observed:** Natural city, office and event photography with architectural orange-red accents alternates with text in ruled half-width modules. Photos are square or wide rectangles with square corners. Portraits use a consistent neutral gray background and straightforward front-facing framing.

**Transfer:** Use real people and environments, restrained natural color, and consistent portrait crops; avoid lifestyle-photo collages.

### Icons

**Observed:** Most interface icons are compact filled SVGs at 16px, 20px or 24px in the current text color; arrows and chevrons sit at action ends. Colorful pixel-object illustrations are a separate vocabulary, generally 32px to 56px.

**Transfer:** Use a single compact solid icon family for navigation and utility controls. Reserve multicolor pixel objects for illustration and selected feature markers.

## Section recipes

How recurring sections are built.

### First screen: Sentence playground opening

**Observed:** A fixed segmented Navigation cell bar sits over a 700px-high paper stage. The central headline is 96px/1, medium weight, centered in two lines across roughly 628px; an inline pixel symbol punctuates the sentence. From back to front: paper ground, fine vertical guides and broad arc, edge stacks of 120px warm blocks and tiny sprites, then headline and Announcement card. The card is centered near the stage bottom, separated from the headline by about 160px. There is no supporting paragraph or large screenshot in this default opening. Within the first 900px the full headline, main pixel scene and announcement are visible, plus the upper 200px of a bordered logo strip; the next concept narrative falls below.

**Transfer:** Use a short declarative product promise with an original inline block symbol and edge objects. Without polished artwork, use a deliberately crisp pixel emblem and warm square stacks. Flagship product pages instead open with a 71.9px left-aligned promise across the top, a narrow support-and-action column below and a dark diagram occupying the center half. Editorial openings use a large bottom-aligned sentence beside a symbolic object; company openings pair a roughly 70% title region with a mission summary and a wide real photograph.

**Avoid:** Do not replace the sparse center with a large dashboard, multiple CTA pills, a gradient headline or a paragraph-heavy hero.

**Text style:** `display` — ALTMistral 500 · 96px/1 · tracking -0.02em

### Logo proof rail

**Observed:** A 272px-high horizontally overflowing row of square logo cells follows a major opening or contextual chapter. Logos are centered, grayscale and generally capped around 112px wide; shared rules create a continuous grid.

**Transfer:** Use a relevant set of real partner, integration or customer marks; preserve the small mark-to-cell ratio and edge overflow.

### Concept statement

**Observed:** A stone band with a 160px lead-in holds a centered heading-lg sentence over Connected concept field. The diagram has far more horizontal extent than the heading.

**Transfer:** Explain the product's central tension in ordinary language, then turn its nouns into connected objects.

**Text style:** `heading-lg` — ALTMistral 500 · 56px/60px · tracking -0.01em

### Editorial heading pair

**Observed:** Centered promises sit in a 1024px measure with a large lead-in. Utility section headers are left-aligned at heading scale, sometimes with a Discovery button opposite. A heading and its paragraph use an 8px or 24px gap depending on title scale.

**Transfer:** Choose centered statements for a conceptual pivot and left-aligned headers for browsable content, not the same alignment everywhere.

### Rail and capability chapters

**Observed:** Quarter-width chapter navigation remains beside a three-quarter-width ruled content column. Feature row alternates media and text. Technical variants start each chapter with a 56px title, then a wide diagram after 120px, followed by three joined benefit cells with 24px headings and 16px body copy.

**Transfer:** Use the rail for genuine product chapters. The explanatory variant can replace imagery with readable paragraphs separated from the title by 80px.

**Text style:** `heading-lg` — ALTMistral 500 · 56px/60px · tracking -0.01em

### Selectable proof

**Observed:** A left selector column occupies about one quarter of the frame. The remaining region combines two paper fact cells with Bright proof panel using 16px gaps; Feature selector reveals the relevant proof and a yellow edge marker indicates the current item.

**Transfer:** Group proof by audience or job and combine one quantified result with a short outcome and an attributed statement.

### Deep exploration close

**Observed:** Navy chapter starts with a 44px invitation and continues into three contiguous Resource card cells. Icons and titles sit high, descriptions low, with 128px internal separation and dark rules.

**Transfer:** Offer deeper technical, practical or organizational paths as a contrasting closing chapter.

**Text style:** `heading` — ALTMistral 500 · 44px/52px · tracking -0.01em

### Pixel horizon ending

**Observed:** Footer column occupies a three-column ruled band, followed by a spacious paper utility area with social links left, distribution links right, small metadata and controls along the lower corners. A 240px-wide black pixel emblem sits centrally at the baseline, immediately above Striped closing horizon. This ending is shared across all page types.

**Transfer:** Preserve a strong original silhouette and the striped horizon even when the available footer links are fewer.

### Product conversion close

**Only for:** flagship product pages

**Observed:** Orange closing band holds a white 44px statement near its bottom left and a pale Discovery button at the right, with 80px bottom padding and subtle grain behind both.

**Transfer:** End on the differentiating result the product enables, with a direct expert or start action.

**Text style:** `heading` — ALTMistral 500 · 44px/52px · tracking -0.01em

### Pricing comparison and objections

**Only for:** pricing pages

**Observed:** A compact 56px title shares its row with currency controls. Plan card grid is followed by a ruled comparison table: a wider label column plus four 275px plan columns, warm tint on alternating plan columns, 72px cells and category headers at 32px. The FAQ has a substantial left title and a wider right question stack.

**Transfer:** Prioritize comparable terms and explicit limits; retain the dense table as a scoped information design rather than spreading this density through a landing page.

### History and people

**Only for:** company narratives

**Observed:** Alternating half-width photograph/text sections lead into a horizontal timeline of 448px cards with tiny dark mono date tags, then three equal ruled portrait cells. Updates switch to a navy chapter with Editorial card and 8px slider gaps.

**Transfer:** Use milestones, real photography and people to explain origin and credibility rather than reusing product feature cards.

## Page flow

**Storyline:** A decisive promise → an illustrated explanation of the stakes → navigable capabilities → concrete proof → deeper paths or a focused closing action → a graphic footer horizon.

### Broad product or platform introduction

1. **Promise** — Centered monumental sentence in a sparse pixel playground with one announcement.
2. **Social proof** — Ruled strip of small grayscale marks.
3. **Problem framing** — A connected field of labeled assets under a large conceptual statement.
4. **Capability chapters** — A rail and alternating illustrated feature rows.
5. **Customer proof** — Selectable audiences, paper fact cells and a vivid quote panel.
6. **Further exploration** — Navy resource cards, then the shared pixel horizon footer.

**Transfer:** Move from reader agency to specific tools and then real outcomes; adapt the number of chapters to the product.

### Explain a strategic product category or principle

1. **Promise** — Oversized lower-left statement balanced by a tall pixel symbol and a concise definition.
2. **Problem framing** — Successive split-screen statements with diagram changes.
3. **Framework** — Selectable layers paired with a large explanatory diagram.
4. **Capability chapters** — A rail beside substantial titled prose chapters.
5. **Closing call** — Centered light statement and customer action in navy, followed by the shared footer.

**Transfer:** Use a few diagrammatic stages to explain a difficult idea before expanding the practical criteria.

### Sell a flagship technical product

1. **Promise and demonstration** — Wide title above narrow support copy and a central dark pixel-workflow diagram.
2. **Social proof** — Grayscale logo rail.
3. **Differentiation** — A selector paired with a large geometric illustration.
4. **Capability chapters** — Numbered chapters, large workflow plates and joined benefit cells beside a rail.
5. **Use cases** — A wide summary diagram and four tall selectable use-case cells.
6. **Closing call** — Orange textured band with white statement and pale action, then the shared footer.

**Transfer:** Show the product's process as an ordered system and connect each step to benefits before the final invitation.

### Support a purchase decision

1. **Orientation** — Compact title and currency control.
2. **Pricing** — Four aligned plan cards with a raised recommended tier.
3. **Comparison** — Dense ruled feature table with persistent plan context.
4. **Objection handling** — Large left title beside a right accordion.
5. **Ending** — Shared light utility footer and warm pixel horizon without another sales hero.

**Transfer:** Make terms, inclusions and limits easy to compare; keep the graphic brand ending after the dense information.

### Explain an organization and its credibility

1. **Mission** — Large sentence, narrow mission summary and wide event photograph; a later centered mission statement provides a pause.
2. **Context and origin** — Alternating editorial photography and substantial text.
3. **Milestones** — Horizontal dated cards with navigation controls.
4. **People and proof** — Three consistent portraits followed by a grayscale partner rail.
5. **Continuity** — Dark update collection, then the shared footer.

**Transfer:** Translate mission into concrete origin, milestones, people and ongoing work; preserve the photographic tone.

## Writing

Confident, plainspoken and technically literate. Serious claims about control and capability are balanced by direct, almost conversational sentences rather than promotional exuberance.

**Do not copy:** Do not reuse the Mistral name, logos, mascots, pixel artwork, product names, proprietary category claims, customer logos, quotes, prices, statistics or organizational history. Source examples illustrate syntax only; replace them with truthful material for the new product.

- **Addressing the reader:** Use you and your for the reader's agency, we for what the provider supplies. Longer explanatory sections can shift to direct imperatives.
- **Rhythm:** Short declarative headlines often use a period. Paired clauses set up a clear division of responsibility; supporting paragraphs expand with precise technical nouns. Actions stay brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A decisive statement of position or a verb-led outcome, not a slogan full of qualifiers. | 3–10 words | “Sovereignty is existential.”<br>“Build AI models that know your enterprise.” |
| Capability title | Two short parallel clauses: what we provide, what you control. | 6–13 words | “We make the models. You keep them.”<br>“We host it. Or you do.” |
| Supporting copy | A concrete capability followed by the reader's options or practical result. | 20–45 words | “Customize models around your data, use cases, and requirements with Forge. The intelligence you create is uniquely yours.” |
| Action | Discover plus a destination for exploration; a plain verb phrase for conversion. | 2–5 words | “Discover Research”<br>“Talk to an expert” |
| Technical benefit | A terse noun phrase heading followed by an explicit operational consequence. | 2–5 word title | “Rollback with confidence.”<br>“Version everything.” |

**Words and phrasing to use:** build; keep; control; your; run; tailor; operate; specific; workflows; requirements

**Avoid:** revolutionary; magical; unleash limitless potential; game-changing; effortlessly transform everything

**Rules:**

- Pair big promises with the practical mechanism that makes them true.
- Name concrete deployment choices, inputs and outputs when relevant.
- Let short sentences carry confidence; avoid exclamation marks and inflated adjective stacks.
- Use periods in statement headings and questions only when they are real reader questions.

## Do's and Don'ts

### Do

- Keep default display type at 500 weight and -0.02em tracking.
- Use 40px desktop gutters and 1px warm rules to connect modules.
- Stage colorful product artwork inside rectangular plates rather than tinting every section.
- Use pale 48px discovery actions with 6px corners as the marketing default.
- Give diagrams 80px–120px of separation from chapter headings.
- Use 11px uppercase mono markings for technical annotations.
- Keep small logos centered within large 272px ruled cells.
- Finish with the original pixel silhouette and four warm 64px stripes.

### Don't

- Do not turn the default palette into a pure-white and blue enterprise template.
- Do not use 700-weight headlines to compensate for smaller type; the intended weight is 500.
- Do not round joined content modules to 16px or 24px; reserve rounding for controls.
- Do not apply soft floating shadows to the ruled grid; separation is drawn with lines.
- Do not make every action orange; saturated orange belongs primarily to artwork and bounded bands.
- Do not make all technical labels uppercase grotesk; use the tiny mono recipe.
- Do not reduce the footer to links and a copyright line; its silhouette and warm horizon are part of the identity.
- Do not carry pricing-table density into the broad marketing narrative.

## Motion and responsive

### Motion

**Observed:**

- Declared navigation color transitions use .15s cubic-bezier(.4, 0, .2, 1).
- Declared accordion and button interior transitions include all 0.3s cubic-bezier(.4, 0, .2, 1).
- Logo rails are horizontally overflowing and support dragging; conceptual chips declare grab and grabbing cursors.
- The product opening and company opening use sticky desktop stages; diagrams and artwork change through the narrative.

**Transfer:**

- Use brief color feedback on segmented navigation and actions; keep diagram changes subordinate to readable copy.
- Preserve the relationship between active chapter navigation and the current content chapter.

**Unknown:**

- Actual scroll-animation timing, complete narrative animation paths and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Layout declarations include stacked flex layouts, smaller 16px insets, and desktop 40px insets; no numeric breakpoint thresholds are established.
- Plan layouts declare full-width, half-width and four-across arrangements; portrait and resource grids also have stacked variants.

**Transfer:**

- On narrow screens, stack feature text and media, replace the quarter-width rail with compact chapter navigation and preserve the numbered headings.
- Let concept chips wrap in reading order rather than shrinking the type to fit their desktop positions.
- Keep the pixel silhouette and full-width striped horizon; reduce peripheral opening artwork before reducing headline legibility.

**Unknown:**

- Mobile opening scale, precise breakpoint values, table overflow behavior and navigation collapse behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
