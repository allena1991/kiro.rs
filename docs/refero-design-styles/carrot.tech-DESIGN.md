# Carrot — acid citrus editorial

## Overview

An outspoken, light marketing style that pairs literary serif statements with matter-of-fact sans-serif explanations. Acid yellow-green, warm orange and pale clay give practical software a cultural rather than corporate feeling. Flat silhouettes, dotted plotting fields, device mockups and warm documentary photographs share a spacious, sharply cut layout.

### Essentials

- Literary headlines on a fluorescent field: Signifier 300 at 72px/1.15 with -0.01em tracking, supported by DM Sans rather than another display face.
- The opening is an editorial spread, not a centered slogan: 40px side gutters, a 24px category line, a three-line left headline and a black geometric object on a 662px-wide dotted field at right.
- Corners are snipped, never softened: 4px diagonal cuts on compact black actions, 8px cuts on cards and photographs; button padding is 8px 14px 9px.
- Color belongs to the whole environment: yellow-green is the default canvas, orange carries a substantial explanatory or proof chapter, and both retain black text. Clay is the scoped product-detail alternative; white is mostly confined to devices and comparison marks.
- Technology is staged as a physical thing: crisp laptop and phone compositions sit on an 8% black wash, while close human activity fills clipped photographic panels without decorative frames.
- A plotting-field silhouette and a monumental closing statement are signature devices: use a 36px repeat of 2px black squares behind a single solid object or two proof bars, then a 72px serif invitation above a small black action. A simple SVG silhouette supplies the object when bespoke media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm citrus orange | `#ff8736` | `--color-orange` | background, accent, link | Full-width explanatory and proof chapters; underline hover accent. Keep black typography over it. |
| Acid yellow-green | `#e7eb5d` | `--color-canvas` | background | Default full-page environment and closing conversion areas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border, action, accent | All primary type, 1px rules, silhouettes and primary actions. |
| Olive wash | `#d5d856` | `--color-wash` | surface | Visible result of black at 8% over the yellow-green canvas. The same transparent wash adapts to orange and clay. |
| Muted olive ink | `#535521` | `--color-muted` | text | Secondary form notes; black at 64% over the yellow-green canvas, adapting to other canvases. |
| Comparison white | `#ffffff` | `--color-white` | text, accent, surface | Text on black actions, after-state proof bars and legend squares; not the main page canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product-detail narratives and recruitment chapters | Pale clay | `#e9d7c8` | `--color-clay` | background | Warm alternative canvas for detailed product narratives and recruitment material. |

## Typography

- **Signifier** — Large promises, section titles, proof statements and quotations. Light literary serif with pointed details, strong stroke contrast and compact expressive proportions. OpenType features: "liga", "onum". If unavailable, use **Spectral**. Use weight 300 and retain tight tracking; check line breaks against the intended editorial width. Font stack: "Signifier", "Spectral", Times, serif.
- **DM Sans** — Navigation, body copy, category lines, card headings and actions. Clear, approachable sans-serif; regular body copy and restrained medium-weight labels. Font stack: "DM Sans", Helvetica, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Signifier | 300 | 72px | 1.15 | -0.01em, features "liga", "onum" | Main promises, large section titles and closing statements. |
| statement | Signifier | 300 | 50px | 1.15 | -0.01em, features "liga", "onum" | Proof stories, compact editorial headings and quotations. |
| lead | DM Sans | 400 | 29px | 1.25 | normal | Opening explanation and substantial supporting paragraphs; also question rows. |
| card-heading | DM Sans | 500 | 29px | 1.25 | -0.01em | Benefit and capability card titles. |
| category | DM Sans | 400 | 24px | 1.25 | normal | Opening category line and closing support copy. |
| label | DM Sans | 500 | 24px | 1.25 | normal | Illustrated item titles and newsletter label. |
| contact-action | DM Sans | 400 | 24px | 1.4 | normal | Closing conversion button. |
| body | DM Sans | 400 | 20px | 1.4 | normal | Benefit-card paragraphs and editorial supporting text; standard action text. |
| compact | DM Sans | 400 | 20px | 1.25 | normal | Navigation, footer links, illustrated-item copy and secondary actions. |
| small-heading | DM Sans | 500 | 20px | 1.25 | normal | Logo-strip label, footer column headings and comparison labels. |
| attribution | DM Sans | 400 | 17px | 1.4 | normal | Short attribution beneath a large quotation. |

**Notes:**

- The serif hierarchy changes size, not weight: both 72px and 50px use 300 with -0.01em tracking and 1.15 line height.
- Keep category labels in sentence case at 24px; these are conspicuous lines, not tiny uppercase eyebrows.
- Use the 20px/1.25 recipe for compact repeated descriptions, and 20px/1.4 for longer text inside benefit cards.
- Allow natural word wrapping. Large statements remain left aligned, including the text within a centered quotation container.

## Layout

**Density:** Airy between chapters, purposeful within components: broad pauses and open fields contrast with compact actions and readable multi-line cards.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Main gutters, grid gaps, card padding and inset structure; compact button padding is a separate recipe.

| Value | Use |
| --- | --- |
| 8px | Heading-to-description gap and small card-title offsets. |
| 12px | Opening action offset and form-note gap. |
| 16px | Media-to-title separation and navigation item separation. |
| 24px | Card interiors, comparison-group separation and closing action offset. |
| 32px | Grid gaps and separation before benefit descriptions. |
| 40px | Page gutters and the top inset of ruled bands. |
| 48px | Heading-to-illustrated-grid separation and proof action spacing. |
| 80px | Opening headline-to-explanation separation. |
| 120px | Major chapter separation and breathing room around closing bands. |
| 160px | Default opening category-to-headline margin. |

### Containers and grids

- **page container**: max width 1500px · side padding 40px. Centered outer container; 1360px usable content at a 1440px viewport.
- **editorial halves**: 2 columns · gap 32px. Equal 664px columns at desktop for text/image chapters and heading/support pairs; opening uses nearly equal halves with a 24px art inset.
- **three-column grid**: 3 columns · gap 32px. 432px-wide illustrated capability blocks and deeper feature tiles.
- **four-column grid**: 4 columns · gap 32px. 316px-wide benefit cards, module blocks and footer columns.
- **statement measure**: max width 1000px. Wide serif statements in text-led chapters.
- **quote measure**: max width 720px. Centered container for a left-aligned quotation and its attribution.
- **description measure**: max width 400px. Descriptions below illustrated capability media.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 0px |
| cards and photographs | 0px |

## Surfaces and depth

### Surfaces

#### Citrus canvas · level 0

**Use:** Default marketing environment.

**CSS:** `background: #e7eb5d; color: #000000`

**Observed:** Color extends edge to edge and remains visible between every text and media element.

**Transfer:** Treat the canvas as the dominant color mass, not as a narrow accent strip.

#### Orange chapter · level 0

**Use:** Explanatory and quantified-proof passages.

**CSS:** `background: #ff8736; color: #000000`

**Observed:** A sustained orange environment covers module explanations and proof, then returns to yellow-green.

**Transfer:** Give one meaningful narrative passage this warm contrasting field rather than alternating every card.

#### Cut wash · level 1

**Use:** Benefit cards, media backing and form fields.

**CSS:** `background: rgba(0,0,0,0.08); clip-path: polygon(8px 0%, 0% 8px, 0% calc(100% - 8px), 8px 100%, calc(100% - 8px) 100%, 100% calc(100% - 8px), 100% 8px, calc(100% - 8px) 0%); box-shadow: none`

**Observed:** A flat darkening of the current canvas, with diagonal cuts at every corner; no outline or raised depth.

**Transfer:** Use transparency so the surface remains part of the chapter color.

#### Ruled band

**Use:** Chapter separators, question rows and footer boundary.

**CSS:** `border-bottom: 1px solid #000000`

**Observed:** Thin black lines span either the content width or the full viewport; no ornamental divider.

**Transfer:** Let the line establish the transition while maintaining the colored field.

#### Clay canvas · level 0

**Only for:** product-detail narratives and recruitment chapters

**Use:** More documentary product storytelling and human-centered material.

**CSS:** `background: #e9d7c8; color: #000000`

**Observed:** Entire product-detail openings and feature narratives use clay; their closing conversion and footer return to citrus. Recruitment material can retain clay through the footer.

**Transfer:** Choose this as a coherent page-type variant, not an extra arbitrary card color.

## Components

### Navigation

**Use:** Global orientation above the opening spread.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 66px; padding: 0px 40px; max-width: 1500px; border-bottom: 1px solid #000000`

**Text style:** `compact` — DM Sans 400 · 20px/1.25

**Observed:** A small wordmark at left; plain links and two compact black actions right. A downward chevron accompanies the product menu. The bar belongs to the canvas rather than a separate white panel.

**Transfer:** Use a similarly compact identity and a short link set; preserve the action cluster.

### Primary button

**Use:** Default actions beside explanations and in navigation.

**CSS:** `background: #000000; color: #ffffff; padding: 8px 14px 9px; clip-path: polygon(4px 0%, 0% 4px, 0% calc(100% - 4px), 4px 100%, calc(100% - 4px) 100%, 100% calc(100% - 4px), 100% 4px, calc(100% - 4px) 0%); text-align: center; transition: background-color 0.25s, color 0.25s`

**Text style:** `body` — DM Sans 400 · 20px/1.4

**Observed:** Text only, intrinsic width, no arrow. The standard action is 45px high; the opening conversion uses compact text and is 42px high.

**States:** Declared: hover background-color rgba(0,0,0,0.08), color #000000; focus-visible and active unspecified.

### Secondary button

**Use:** Link from an editorial proof statement into a longer case.

**CSS:** `background: rgba(0,0,0,0.08); color: #000000; padding: 8px 14px 9px; clip-path: polygon(4px 0%, 0% 4px, 0% calc(100% - 4px), 4px 100%, calc(100% - 4px) 100%, 100% calc(100% - 4px), 100% 4px, calc(100% - 4px) 0%); transition: background-color 0.25s, color 0.25s`

**Text style:** `compact` — DM Sans 400 · 20px/1.25

**Observed:** A low-emphasis tinted action below the proof text, not an outline button.

**States:** Declared: hover background-color #000000, color #FFFFFF; focus-visible and active unspecified.

### Contact button

**Use:** Final conversion beneath the closing statement.

**CSS:** `background: #000000; color: #ffffff; padding: 8px 14px 9px; clip-path: polygon(4px 0%, 0% 4px, 0% calc(100% - 4px), 4px 100%, calc(100% - 4px) 100%, 100% calc(100% - 4px), 100% 4px, calc(100% - 4px) 0%)`

**Text style:** `contact-action` — DM Sans 400 · 24px/1.4

**Observed:** Larger type gives a 51px-high action while retaining the same compact construction.

**States:** Declared: hover background-color rgba(0,0,0,0.08), color #000000; focus-visible and active unspecified.

### Text link

**Use:** Navigation and footer routes.

**CSS:** `display: inline-flex; color: #000000`

**Text style:** `compact` — DM Sans 400 · 20px/1.25

**Observed:** Plain sentence-case text, no capsule or underline by default; footer links stack with 4px gaps.

**States:** Declared: hover color rgba(0,0,0,0.6); focus-visible and active unspecified.

### Benefit card

**Use:** Detailed parallel benefits and capabilities.

**CSS:** `background: rgba(0,0,0,0.08); padding: 24px; display: flex; flex-direction: column; clip-path: polygon(8px 0%, 0% 8px, 0% calc(100% - 8px), 8px 100%, calc(100% - 8px) 100%, 100% calc(100% - 8px), 100% 8px, calc(100% - 8px) 0%)`

**Text style:** `card-heading` — DM Sans 500 · 29px/1.25 · tracking -0.01em

**Observed:** A medium sans title above regular body paragraphs, separated by 32px. Four narrow cards share a height. Product-feature variants use three columns, a compact category above the title and descriptions aligned low in the tile.

**Transfer:** Use real differences in outcomes; keep text inside the panel rather than adding an unrelated icon to each title.

### Illustrated module

**Use:** Short product or capability explanations in three- or four-column grids.

**CSS:** `padding-bottom: 8px`

**Text style:** `label` — DM Sans 500 · 24px/1.25

**Observed:** A clipped tinted media panel above a title with 16px separation, followed by compact body text after 8px. The default three-column media is 432px by 270px; four-column modules use 316px by 198px. Product-detail square illustrations use a 268px object area inset in a 316px panel.

**Transfer:** Use a device, a silhouette or a concise integration diagram to give each block a clear visual noun.

### Newsletter field

**Use:** Email signup paired with a short editorial invitation.

**CSS:** `background: rgba(0,0,0,0.08); height: 72px; padding: 8px 105px 8px 24px; clip-path: polygon(8px 0%, 0% 8px, 0% calc(100% - 8px), 8px 100%, calc(100% - 8px) 100%, 100% calc(100% - 8px), 100% 8px, calc(100% - 8px) 0%); transition: background-color 0.2s`

**Observed:** One broad field in the right half of the newsletter row, with a Primary button embedded at the right and a subdued consent line below.

**Transfer:** Retain one-field simplicity and the embedded action; provide a separate accessible label.

### Comparison graphic

**Use:** A small, unmistakable visual for paired results.

**CSS:** `width: 320px; height: 320px; display: flex; align-items: flex-end; justify-content: center`

**Observed:** Two 64px-wide bars, black and white, sit on the dotted field with 32px between them. Both have 4px cut corners and a common baseline; height follows the actual comparison. Matching 40px legend squares accompany two-line labels beside the proof statement.

**Transfer:** Show defensible before/after or two-state data with the same spare grammar; do not add chart chrome.

### Footer columns

**Use:** The consistent practical ending after conversion.

**CSS:** `display: grid; grid-template-columns: repeat(4, 1fr); gap: 32px`

**Text style:** `compact` — DM Sans 400 · 20px/1.25

**Observed:** Four equal columns for product routes, company routes, social routes and contact details. Medium-weight headings sit 12px above the links; a small wordmark is isolated near the lower left. Newsletter signup precedes this grid, rather than being squeezed into a column.

**Transfer:** Keep the footer on the chapter canvas and preserve the low, wide distribution of information.

### Question row

**Only for:** product pages with objection handling

**Use:** A restrained accordion for practical questions.

**CSS:** `display: flex; align-items: center; padding: 16px 0px; border-bottom: 1px solid #000000`

**Text style:** `lead` — DM Sans 400 · 29px/1.25

**Observed:** Full content width, question at left and a small down chevron at right; rows are about 69px high including the rule.

**Transfer:** Use short direct questions. Expanded-panel styling and interaction timing are not prescribed.

## Imagery and graphics

### Dotted silhouette stage

**Use:** The principal graphic counterweight to the opening promise, echoed in proof graphics.

**Observed:** A crisp solid-black, faceted hourglass-like object floats in a sparse square-dot field. The field fills nearly half the opening and the object occupies roughly its central half; there is no lighting, texture, outline or shadow.

**Transfer:** Use a single bold geometric symbol expressing the new product's transformation. The minimum equivalent is a carefully proportioned SVG polygon on the same plotted backing.

**Build:** Make a transparent SVG tile 36px by 36px containing a black 2px square at 17px,17px; repeat it across the field, aligned center bottom. Above it center a black SVG silhouette roughly 310px wide and 420px high at desktop: broad top and bottom shoulders with clipped corners and a narrow waist. For other concepts use similarly simple interlocking polygon masses, keeping the background visible.

### Device ensembles

**Use:** Illustrated module media and product explanations.

**Observed:** Front-facing laptops, tablets and phones show pale dashboard screens with citrus sidebars, olive data marks and fine neutral tables. Black device bezels give crisp silhouettes; compositions sit on the Cut wash with little perspective and occupy most of each media panel.

**Transfer:** Use the new product's real UI inside flat device frames. If no UI exists, show one honest simplified workflow with a clear table or status view rather than a dense invented dashboard.

### Documentary work photography

**Use:** Half-width editorial chapters and product-detail image pairs.

**Observed:** Warm, naturally lit close views of hands, people, equipment and real working environments. Strong material detail, selective focus and occasional bright clothing contrast with the flat canvas. Images use 8px corner cuts and 4:3 landscape or 3:4 portrait proportions. Paired compositions bottom-align a tall left image and a shorter right image, leaving open canvas above the latter.

**Transfer:** Photograph actual use, materials and people around the new product; preserve believable warm light and tactile detail instead of abstract office stock.

### Human portrait spread

**Only for:** company and recruitment storytelling

**Use:** Large team portrait and hiring invitation.

**Observed:** An informal full-width group photograph in a bright plant-filled workplace, followed later by an intimate meeting portrait in a half-width panel. Both are cut-corner photographs without overlay text.

**Transfer:** Use a real team or collaborator portrait in a credible environment; match the directness and natural lighting.

### Monumental numeral

**Only for:** long-form mission or problem narratives

**Use:** A single graphic-scale quantity establishing the size of a problem.

**Observed:** A black high-contrast serif number occupies essentially the full 1360px content width in a 212px-high strip on orange; the numeral is artwork rather than ordinary paragraph type.

**Transfer:** Set one verified, meaningful quantity as SVG text or outlined lettering, optically fitted to a wide strip. Let it read as a typographic object, not a dashboard stat card.

**Build:** Use a viewBox matching a 1360px by 212px strip. Fit a light serif numeral line across its width with tight optical spacing, no label inside the artwork, no border and no decorative units. Put its explanation in a separate serif statement below.

### Icons

**Observed:** Small filled black SVG chevrons and identity marks; action-adjacent icons are 24px by 24px. Large capability symbols use heavy solid silhouettes with angled cuts rather than thin outline pictograms.

**Transfer:** Use filled geometric symbols with minimal detail. Reserve small chevrons for disclosure and keep conversion buttons text-only.

## Section recipes

How recurring sections are built.

### First screen: Editorial object opening

**Observed:** The Citrus canvas sits behind the Navigation and a nearly equal two-column spread inside 40px gutters. A 24px category line starts 40px below the 67px navigation boundary. The left half then pauses with a 160px margin before a 72px light serif headline wrapping to three lines. A 29px explanation follows after an 80px inset and a compact Primary button sits 12px beneath it. At right the Dotted silhouette stage fills about 662px by 717px, beginning level with the category line; the solid object is centered within the plotted field. Within the first 900px the complete category, headline, explanation, action and object are visible. The illustrated grid begins below the fold, after a 120px pause.

**Transfer:** For a new marketing page retain the category/promise/explanation stack and balance it with one large purpose-built silhouette, even without a rendered product. Product-detail openings instead use a full-width one- or two-line promise on Clay canvas, followed by a ruled two-column introduction and illustrated grid visible at the foot of the first screen. Company openings use the same text-led grammar; mission openings use Orange chapter and a numeral strip.

**Avoid:** Do not turn this into a centered headline above a giant browser window, or hide the action below an oversized decorative object.

**Text style:** `display` — Signifier 300 · 72px/1.15 · tracking -0.01em

### Heading and explanation pair

**Observed:** A 50px serif statement occupies the left 664px column, with a 20px or 29px sans explanation in the right column. A Ruled band can introduce the pair; 120px chapter spacing keeps it separate from media below.

**Transfer:** Use the left side to state a distinct benefit or premise and the right side to explain the mechanism.

**Text style:** `statement` — Signifier 300 · 50px/1.15 · tracking -0.01em

### Illustrated capability grid

**Observed:** Three Illustrated modules across for introductory capabilities, four across for product modules. Media precedes all copy; the serif section heading sits 48px above the row when present. A sustained Orange chapter can carry the whole group.

**Transfer:** Choose the column count according to content depth, not according to how many generic selling points can be invented.

### Text and documentary panel

**Observed:** Equal text/media halves, with the text at left and a 664px by 498px photographic panel at right. A 72px heading is separated from the explanation by open space; a Primary button follows when there is a deeper route. A 1px divider and 120px pauses articulate the chapter.

**Transfer:** Alternate abstract benefits with grounded use in the real world. A product-detail version can replace the split text panel with the staggered portrait/landscape photo pair.

**Text style:** `display` — Signifier 300 · 72px/1.15 · tracking -0.01em

### Editorial quantified proof

**Observed:** A 50px serif outcome statement spans about three quarters of the content width; a 320px square image or Comparison graphic anchors the right. Compact two-line legend groups sit under the statement, and a Secondary button sits lower in the text column. A ruled client strip follows with a 20px medium label and monochrome logos fitted to 120px by 60px cells.

**Transfer:** Use a verified outcome and relevant logos. When paired data exists, prefer the spare black/white bars to a decorative chart.

**Text style:** `statement` — Signifier 300 · 50px/1.15 · tracking -0.01em

### Benefit field

**Observed:** A 72px serif title above four Benefit cards separated by 32px. Panels carry 24px padding, 29px medium titles and 20px/1.4 paragraphs. The three-column feature variant adds compact categories and aligns descriptions near the bottom.

**Transfer:** Make each card a distinct consequence or capability. Adjust equal heights to the new copy, retaining the airy title-to-description relationship.

**Text style:** `display` — Signifier 300 · 72px/1.15 · tracking -0.01em

### Isolated quotation

**Observed:** A left-aligned 50px serif quotation in a centered 720px measure, with a 17px attribution 24px below. No portrait, quote icon or card backing.

**Transfer:** Use a short authentic customer statement as an editorial pause between denser blocks.

**Text style:** `statement` — Signifier 300 · 50px/1.15 · tracking -0.01em

### Closing invitation and practical ending

**Observed:** A ruled closing band carries a 72px serif statement, a 24px explanation in a narrow measure about 55px lower and a Contact button 24px below. A 120px pause leads to another full-width rule. Newsletter text at left faces the Newsletter field at right, then Footer columns and a small bottom-left wordmark complete the page. Product narratives return from clay to citrus here; the mission variant has a longer closing sentence and no supporting paragraph. The recruitment variant instead ends with a documentary text/image hiring invitation and Primary button, then the same newsletter and footer on clay.

**Transfer:** Include a substantial closing thought and one next step, then finish with signup and practical navigation; adapt the invitation to the page's purpose without adding a separate dark footer.

**Text style:** `display` — Signifier 300 · 72px/1.15 · tracking -0.01em

### Question list

**Only for:** product pages with objection handling

**Observed:** A 50px serif section title sits 48px above full-width Question rows.

**Transfer:** Answer the main adoption uncertainties without turning the section into a card grid.

**Text style:** `statement` — Signifier 300 · 50px/1.15 · tracking -0.01em

### Mission panels

**Only for:** long-form mission narratives

**Observed:** Text-led chapters occupy roughly 901px each, divided by 1px rules. A 72px serif statement begins about 40px beneath each rule in a 1000px measure; occasional 29px support lines follow after 32px. A long Orange chapter establishes tension and the Citrus canvas marks the turn toward the solution.

**Transfer:** Use one thought per panel and short conversational reversals. Retain the deliberate open field, but reserve this unusually slow pacing for an actual essay rather than ordinary product features.

**Text style:** `display` — Signifier 300 · 72px/1.15 · tracking -0.01em

## Page flow

**Storyline:** promise → explanation and capability evidence → grounded use → quantified or human proof → closing invitation → newsletter and practical routes

### Broad product introduction and audience routing

1. **promise** — Editorial object opening with a benefit-led serif promise.
2. **capability overview** — Three illustrated modules explain the core value.
3. **audience routing** — Two large documentary text/image chapters lead to deeper uses.
4. **mechanism** — Four product modules on an orange field.
5. **quantified proof** — Serif case statement, paired bars and a monochrome client strip.
6. **benefits and social proof** — Four tinted benefit panels and an isolated quotation.
7. **closing call** — Large invitation, contact action, newsletter and footer.

**Transfer:** Use the object opening as the default, then balance practical mechanism with documentary evidence and one strong proof treatment.

### Focused operational product landing page

1. **promise** — Text-led clay opening and a ruled heading/explanation pair.
2. **capabilities** — Four illustrated modules.
3. **grounded use** — Staggered photographs, followed by a text/image end-user chapter.
4. **objection handling** — Full-width ruled question rows.
5. **proof** — Editorial outcome with an image, legend and client strip.
6. **closing call** — Citrus invitation, newsletter and footer.

**Transfer:** Use this variant when the reader needs adoption clarity and practical answers before making contact.

### Detailed product narrative for a professional buyer

1. **promise** — Two-line clay headline and a heading/explanation pair.
2. **capability overview** — Four illustrated modules.
3. **early proof** — Large serif outcome with a square location image.
4. **grounded use** — Bottom-aligned documentary image pair.
5. **capability detail** — Three-column feature tiles with categories and low-aligned descriptions.
6. **secondary audience** — Text/image chapter addressing an end user.
7. **quantified proof** — Comparison graphic and client logos.
8. **closing call** — Citrus invitation, newsletter and footer.

**Transfer:** Support a professional decision with proof near both the beginning and end, separating detailed features with tactile imagery.

### Company credibility and recruiting

1. **purpose** — Citrus text-led promise and an editorial argument pair.
2. **background** — Compact factual company narrative opposite a serif heading.
3. **human proof** — Full-width informal group portrait.
4. **closing call** — Clay hiring invitation paired with a meeting photograph and application action.
5. **practical ending** — Newsletter and four-column footer remain on clay.

**Transfer:** Use the shared editorial hierarchy while giving real people the visual emphasis; the closing action serves participation rather than a sales conversation.

### Long-form argument for the product's reason to exist

1. **problem** — Orange opening and monumental numeric artwork.
2. **tension** — Slow full-height serif panels establish the contradiction with occasional sans support.
3. **reframe** — A conversational turn transitions the color field from orange to citrus.
4. **mechanism and impact** — Further isolated statements connect information, behavior and outcomes.
5. **closing call** — Long serif invitation and contact button, then newsletter and footer.

**Transfer:** Keep this manifesto mode scoped to a sustained argument. Its signature numeral and rhetorical pacing can enrich a mission narrative without dictating the structure of a product page.

## Writing

Earnest, practical and hopeful. Large statements are confident and sometimes philosophical, while supporting copy explains tangible mechanisms, costs and behavior rather than relying on hype.

**Do not copy:** Do not reuse the Carrot identity, proprietary product names, customer names or logos, customer quotations, reported outcomes, statistics or sustainability claims. Replace them with material that is true of the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you or your when describing use and benefits. Use we for the team and the product name for capabilities; shift to inclusive people and companies in mission passages.
- **Rhythm:** Short category lines and outcome-led headlines alternate with explanatory paragraphs of two or three sentences. Mission passages allow short conversational interruptions. Actions are usually two or three words; exclamation marks are rare rather than forbidden.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State the outcome or larger enabling idea rather than enumerating features. | 3–10 words | “The Operating System that Enables Circularity”<br>“Motivating waste reduction.” |
| Supporting line | Explain the mechanism and connect it to the reader's concrete result. | 25–55 words | “[Brand] transforms waste from a cost centre into a managed resource — giving property owners, operators and occupiers the intelligence to act before problems happen, not after.” |
| Card heading | A useful capability or an outcome, expressed plainly. | 2–7 words | “Actionable data at your fingertips”<br>“Cost reduction and financial gains” |
| Primary action | A short invitation to explore or speak with the team. | 2–4 words | “Discover how”<br>“Contact us”<br>“Read the case study” |
| Narrative turn | A conversational interruption followed by a reasoned explanation. | 2–9 words | “Hang on.”<br>“That surely sounds like a paradox?” |

**Words and phrasing to use:** enable; understand; improve; reduce; reward; insight; in real time; with better data; get in touch

**Avoid:** revolutionary; disruptive; unleash limitless potential; world-class; magic; effortless everything

**Rules:**

- Lead with a concrete outcome, then explain what makes it possible.
- Use proof statements as sentences with a subject and result, not floating percentages without context.
- Keep category labels functional and sentence case.
- Use British forms such as centre, behaviour and minimise consistently.
- Let philosophical language live in the headline; keep the supporting explanation practical.

## Do's and Don'ts

### Do

- Keep major serif type at weight 300 with 1.15 line height and -0.01em tracking.
- Use 40px desktop side gutters and 32px gaps across repeated grids.
- Carry citrus or orange across substantial page areas, not just buttons.
- Use 8px diagonal cuts on imagery and panel surfaces and 4px cuts on actions.
- Stage a black silhouette or paired bars over the 36px square-dot field.
- Retain 120px pauses between major chapters.
- Finish with a large serif invitation, compact action, newsletter row and practical footer.

### Don't

- Do not substitute a heavy geometric sans for the 72px literary headline.
- Do not turn the category line into a tiny all-caps eyebrow.
- Do not use pill actions or conventionally rounded cards in place of clipped corners.
- Do not add drop shadows, glass blur or raised white card stacks to the flat tinted panels.
- Do not color every comparison bar differently; keep the black/white pair and explain it in the legend.
- Do not shrink body paragraphs into conventional 14px SaaS copy; repeated marketing text is 20px.
- Do not add arrows to every action or use outline icons as the main illustrative language.

## Motion and responsive

### Motion

**Observed:**

- Actions declare background-color 0.25s and color 0.25s transitions.
- The page canvas declares background-color 2s, consistent with sustained color changes between narrative chapters.
- Form fields declare background-color 0.2s.
- Opening words use individual transform wrappers.

**Transfer:**

- Keep action changes to the black/tinted inversion.
- Use environment-color transitions at major narrative turns, preserving black text throughout.

**Unknown:**

- Exact scroll triggers, silhouette animation behavior, word-reveal timing and easing are unspecified.
- No focus-visible or active treatments were established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 560px, 736px and 980px.

**Transfer:**

- On narrow screens, preserve category → promise → explanation → action reading order, then place the dotted silhouette as its own full-width field.
- Collapse the equal editorial halves and multi-column module grids without changing the serif/sans distinction or the cut-corner treatment.
- Keep paired proof bars together and move them below their explanatory statement when the wide split no longer fits.

**Unknown:**

- Mobile font sizes, gutter values, navigation behavior and precise breakpoint layout changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
