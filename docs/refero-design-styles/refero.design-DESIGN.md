# Refero — editorial taste, tool-like clarity

## Overview

An airy white software aesthetic that pairs literary serif promises with tightly set grotesk explanations and useful, app-like controls. Cool gray surfaces and black actions keep the framing restrained while colorful interface collages carry the visual energy. It suits creative tools, developer products and reference-rich services, balancing spacious reading passages with dense, tangible product proof.

### Essentials

- Literary promises inside a working-tool shell: regular Title serif at 50px/1.2 with -0.02em tracking, surrounded by Base-Variable controls at 16px/1.5 and weight 500–600.
- A centered promise leads into a tangible demonstration: an 860px headline column, 660px support column, one black 48px-high pill action and a 675px-wide rounded media stage below.
- Oversized soft containers make the product feel approachable: core feature cards have 64px corners, a 4% blue-gray wash and a two-column grid with 16px gutters; illustrations occupy roughly the upper two thirds.
- Color belongs to the work, not the page furniture: white canvas, #777d90 supporting text, #525769 card prose and black actions dominate; saturated color is concentrated inside product imagery, with pastel feature washes as a pricing variant.
- Proof is a carefully arranged collection, not a stock-photo banner: use layered interface panels, one enlarged detail and a colorful collection of relevant artifacts. If there is no finished interface, compose a legible outcome card and a small workflow vignette instead.
- The close repeats the editorial identity rather than shouting a final sales pitch: a 48px symbol, a centered 40px/1.2 serif positioning line, 14px utility links and a small contact line, with 64px top and bottom breathing room.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page background, selected controls and inverse text. |
| Cool porcelain | `#f7f8fb` | `--color-soft` | surface, text | Cards and inverse button labels; the 4% rgba(55,80,155,0.04) wash produces the same visible cool-white role. |
| Pale edge | `#eef0f6` | `--color-rule` | border, surface | Chip outlines, grid separators and media backing. |
| Fine control edge | `#c2c6d7` | `--color-control-edge` | border | Visible thin blue-gray control outline; built with rgba(1,17,88,0.24) on white. |
| Slate gray | `#777d90` | `--color-muted` | text, link | Supporting prose and inactive controls; rgba(3,14,49,0.54) over white serves this same visible role. |
| Deep slate | `#525769` | `--color-card-copy` | text | Longer explanations on tinted feature cards. |
| Charcoal | `#13151b` | `--color-control-ink` | text, action | Navigation, compact action surfaces and closing typography. |
| Black ink | `#000000` | `--color-ink` | text, action | Headings and main marketing actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog collections | Layer gray | `#dddfea` | `--color-layer-mid` | surface | Middle layers in stacked interface thumbnails. |
| catalog collections and plan comparisons | Distant gray | `#c2c6d7` | `--color-layer-back` | surface, text | Back layers of interface stacks and de-emphasized price suffixes. |
| pricing feature storytelling | Icy blue wash | `#f0f7fe` | `--color-blue-wash` | surface | Visible rgba(106,173,240,0.1) over white. |
| pricing feature storytelling | Peach wash | `#fcf5ee` | `--color-peach-wash` | surface | Visible rgba(228,158,88,0.1) over white. |
| pricing feature storytelling | Orchid wash | `#fcf3fc` | `--color-pink-wash` | surface | Visible rgba(227,135,227,0.1) over white. |

## Typography

- **Base-Variable** — Section headings, descriptions, navigation and controls. Compact contemporary grotesk with a substantial x-height and close letter spacing; medium weight is the everyday voice. If unavailable, use **Inter**. Use weights 500–600 and preserve negative tracking. Font stack: "Base-Variable", "Inter", -apple-system, system-ui, Helvetica, Arial, sans-serif.
- **Title** — Hero promises, prices, sign-up heading and closing positioning line. Fine high-contrast editorial serif with sharp detailing, close fit and a regular rather than bold silhouette. If unavailable, use **Instrument Serif**. Use regular 400; tune wrapping to the narrow editorial proportions. Font stack: "Title", "Instrument Serif", Georgia, serif.
- **monospace** (only for technical installation content) — Copyable terminal commands. Unembellished system monospace, used as a functional artifact rather than a brand voice. Font stack: "monospace", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Title | 400 | 50px | 1.2 | -0.02em | Centered opening promise; also the short title on plan-selection pages. |
| heading-lg | Base-Variable | 500 | 40px | 1.2 | -0.03em | Narrative section leads; can be a multi-line argument rather than a short label. |
| closing-serif | Title | 400 | 40px | 1.2 | -0.02em | Closing positioning line and price numerals, with muted suffixes in the same recipe. |
| card-heading | Base-Variable | 500 | 25px | 32px | -0.025em | Feature card titles and centered testimonial quotes. |
| body | Base-Variable | 500 | 16px | 1.5 | -0.02em | Support paragraphs, navigation labels and normal controls. |
| action | Base-Variable | 600 | 16px | 1.5 | -0.02em | Primary actions, selected tabs and FAQ questions. |
| small | Base-Variable | 500 | 14px | 20px | -0.02em | Utility links, short secondary annotations and billing notes. |
| caption | Base-Variable | 500 | 12px | 16px | -0.015em | Attribution roles and subordinate interface annotations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalog collections and pricing feature storytelling | catalog-heading | Base-Variable | 500 | 32px | 1.25 | -0.0275em | Taxonomy chapter titles and pastel-panel headings. |
| installation guides | step-heading | Base-Variable | 600 | 20px | 1.4 | -0.0225em | Actionable step names along a vertical timeline. |
| technical installation content | code | monospace | 500 | 15px | 1.6 | -0.021em | Single-line shell command. |

**Notes:**

- Serif is reserved for promises, prices and the closing identity; explanations use the grotesk even when their headings are long.
- Keep weight restrained: the 50px serif is regular, the 40px sans is medium, and 600 is concentrated on controls and step titles.
- Negative tracking intensifies from -0.02em body and serif display to -0.03em major sans headings. Do not apply uppercase tracking to the ordinary sentence-case labels.

## Layout

**Density:** Airy reading sections alternate with compact controls and information-rich product cards.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Dominant section and content rhythm; small exceptions such as 12px and 42px remain literal.

| Value | Use |
| --- | --- |
| 8px | Icon-label spacing and tight control groups. |
| 16px | Heading-to-prose gap, card gutters and stacked utility spacing. |
| 24px | FAQ padding and horizontal footer link gap. |
| 32px | Catalog card padding, testimonial padding and larger grid gutters. |
| 48px | Main side padding, timeline step bottom padding and footer group separation. |
| 64px | Footer top and bottom padding. |
| 96px | Narrative section top padding. |
| 126px | Opening action group to demonstration stage. |

### Containers and grids

- **app shell**: max width 1600px · side padding 48px. Desktop main content sits beside a 270px navigation rail; at 1440px the remaining pane is 1170px and its usable inner width is 1074px.
- **marketing sections**: max width 1136px. Wide section wrapper inside the main pane.
- **reading column**: max width 755px. Centered wrapper with left-aligned narrative headings, prose and installation steps.
- **hero column**: max width 860px. Centered hero heading with a narrower 660px supporting paragraph.
- **feature grid**: 2 columns · gap 16px. Equal cards with a minimum column size of 420px; each is 529px wide in the desktop composition.
- **catalog grid** (only for catalog collections): 3 columns · gap 36px. Three-up image collections; flow-card rows have 32px vertical gaps.
- **plan grid** (only for pricing pages): 3 columns · gap 32px. 357px plan panels aligned at their tops inside a 1167px wrapper.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature panels | 64px |
|  | hero media | 32px |
|  | marketing buttons | 28px |
|  | compact controls | 12px |
|  | segmented control | 24px |
|  | selected segment | 20px |
|  | quote and FAQ cards | 16px |
| pricing pages and catalog collections | plan and filter chips | 20px |
| catalog collections | thumbnail media | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| control lift | `rgba(12, 41, 126, 0.09) 0px 1px 3px 0px, rgba(12, 41, 126, 0.03) 0px 0px 1px 0.4px` | Outlined account actions and white active segments. |
| faint inset edge | `rgba(12, 41, 126, 0.07) 0px 0px 0px 1px inset` | Segmented controls and catalog flow backings. |
| media keyline | `rgba(12, 41, 126, 0.07) 0px 0px 0px 2px` | Opening demonstration frame. |

### Surfaces

#### Canvas · level 0

**Use:** All page types.

**CSS:** `background: #ffffff; color: #000000`

#### Soft feature panel · level 1

**Use:** Default large feature illustration and pricing-summary backing.

**CSS:** `background: rgba(55, 80, 155, 0.04); border-radius: 64px; overflow: hidden`

**Observed:** Large tonal blocks without a heavy perimeter or drop shadow; illustrations can reach the edges while prose remains inset.

**Transfer:** Use this broad rounded material for substantive product stories, not every text paragraph.

#### Utility card · level 1

**Use:** Quotes and FAQ rows.

**CSS:** `background: #f7f8fb; border-radius: 16px`

**Observed:** Cool solid fill, little elevation and a simple silhouette.

#### Pastel feature panel · level 1

**Only for:** pricing feature storytelling

**Use:** A more colorful explanation of purchase value.

**CSS:** `background: rgba(106, 173, 240, 0.1); border: 1px solid rgba(55, 80, 155, 0.039); border-radius: 16px; overflow: hidden`

**Observed:** Blue and peach panels are paired above a wide orchid panel; text colors are coordinated darker versions of each hue. Oversized interface crops emerge from the lower edge with matching diffuse colored shadows.

**Transfer:** Keep colored material inside discrete proof panels; do not tint the entire page.

#### Prismatic recommended plan · level 1

**Only for:** pricing pages

**Use:** Single recommended plan.

**CSS:** `background: conic-gradient(from 180deg, rgba(255,132,117,1), rgba(255,92,120,1), rgba(255,135,198,1), rgba(255,165,0,1), rgba(255,117,66,1), rgba(255,132,117,1)); border-radius: 20px; padding: 4px; overflow: hidden`

**Observed:** A warm coral-orange-pink conic rim surrounds inner panels covered by a 90%-opaque cool-white layer, leaving a soft blush glow beneath the content. Other plans remain white with fine blue-gray outlines; all plan actions look black.

**Transfer:** Highlight only the best-fit choice. Apply the pale inner overlay before adding copy and actions.

## Components

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 16px; background: #000000; color: #f7f8fb; border-radius: 28px`

**Text style:** `action` — Base-Variable 600 · 16px/1.5 · tracking -0.02em

**Observed:** A single compact centered hero action. Pricing actions widen to the plan's inner width and become 56px high. Installation actions use 8px corners; shell actions use 12px corners rather than marketing pills.

### Navigation item

**Use:** Persistent tool-like navigation.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 40px; padding: 0px 12px; border-radius: 12px; color: #13151b`

**Text style:** `body` — Base-Variable 500 · 16px/1.5 · tracking -0.02em

**Observed:** Left icon followed by label; the rail groups creation and destinations near the top and purchase, integrations and account near the bottom. A black creation action precedes destinations.

**States:** Declared: hover background rgba(55,80,155,.039); focus-visible unknown.

### Outlined account action

**Use:** Secondary account entry in the rail.

**CSS:** `display: flex; align-items: center; gap: 8px; height: 41px; padding: 0px 12px; border: 0.5px solid rgba(1, 17, 88, 0.24); border-radius: 12px; color: #13151b; box-shadow: rgba(12, 41, 126, 0.09) 0px 1px 3px 0px, rgba(12, 41, 126, 0.03) 0px 0px 1px 0.4px`

**Text style:** `body` — Base-Variable 500 · 16px/1.5 · tracking -0.02em

**Observed:** Full rail width, with an entry-arrow icon before the text.

**States:** Declared: hover background rgba(55,80,155,.039); focus-visible unknown.

### Context badge

**Use:** Small product-context label above the hero.

**CSS:** `display: inline-flex; align-items: center; gap: 8px; height: 40px; padding: 0px 16px; border-radius: 20px; background: rgba(55, 80, 155, 0.04); color: #000000`

**Text style:** `body` — Base-Variable 500 · 16px/1.5 · tracking -0.02em

**Observed:** One small monochrome icon precedes a sentence-case category; centered above the headline with a 16px gap.

### Feature story card

**Use:** Main capability proof.

**CSS:** `display: flex; flex-direction: column; background: rgba(55, 80, 155, 0.04); border-radius: 64px; overflow: hidden`

**Text style:** `card-heading` — Base-Variable 500 · 25px/32px · tracking -0.025em

**Observed:** A large image occupies the top, followed by a text block padded 53px 57px 59px. Title precedes a 16px/24px explanation in deep slate with a 16px gap. A desktop card is 529px by 736px.

**Transfer:** Choose one clear visual argument per card: detail, breadth, structured output or workflow.

### Footer link

**Use:** Compact closing navigation.

**CSS:** `color: rgba(3, 14, 49, 0.54); transition: color 0.2s`

**Text style:** `small` — Base-Variable 500 · 14px/20px · tracking -0.02em

**Observed:** A centered wrapping utility row with 24px horizontal and 12px vertical gaps; contact follows as a separate small line.

**States:** Declared: hover color #13151b; focus-visible unknown.

### Billing switch

**Only for:** pricing sections

**Use:** Billing-period selection.

**CSS:** `position: relative; background: rgba(55, 80, 155, 0.04); border-radius: 24px; padding: 4px; height: 64px; box-shadow: rgba(12, 41, 126, 0.07) 0px 0px 0px 1px inset`

**Text style:** `action` — Base-Variable 600 · 16px/1.5 · tracking -0.02em

**Observed:** Two or three labels share the track. The white selected segment is 56px high with 20px corners and Control lift; inactive labels are slate. Width is 300px for two periods and 366px for three.

### Command strip

**Only for:** technical installation content

**Use:** Copyable setup command.

**CSS:** `position: relative; background: rgba(55, 80, 155, 0.04); border-radius: 12px; padding: 12px 48px 12px 12px`

**Text style:** `code` — monospace 500 · 15px/1.6 · tracking -0.021em

**Observed:** A 48px-high strip in the reading column, with a copy icon at the right and no oversized terminal-window decoration.

### Filter chip

**Only for:** catalog collections

**Use:** Wrapping taxonomy selectors.

**CSS:** `display: inline-flex; align-items: center; height: 40px; padding: 0px 16px; border: 1px solid #eef0f6; border-radius: 20px; color: #000000`

**Text style:** `body` — Base-Variable 500 · 16px/1.5 · tracking -0.02em

**Observed:** Many concise chips wrap across lines before the image grid; the selected chip is black with inverse text.

### FAQ row

**Only for:** pricing pages

**Use:** Purchase objection handling.

**CSS:** `background: #f7f8fb; border-radius: 16px; padding: 24px; margin-bottom: 16px`

**Text style:** `action` — Base-Variable 600 · 16px/1.5 · tracking -0.02em

**Observed:** 72px closed rows in a centered 752px column, question left and small downward chevron right. The text reserves 36px on the right.

### Testimonial card

**Only for:** pricing proof sections

**Use:** Human validation in an edge-clipped quote rail.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #f7f8fb; border-radius: 16px; padding: 32px; text-align: center`

**Text style:** `card-heading` — Base-Variable 500 · 25px/32px · tracking -0.025em

**Observed:** 365px by 540px cards separated by 12px; quotation marks decorate the quote, an external-link arrow sits at the top right, and a circular portrait, name and 12px role anchor the bottom.

**States:** Declared: hover background #eef0f6; focus-visible unknown.

### Email input

**Only for:** account conversion sections

**Use:** Inline sign-up form.

**CSS:** `background: #ffffff; height: 40px; padding: 0px 16px; border: 0.5px solid rgba(1, 17, 88, 0.24); border-radius: 12px; transition: border-color 0.2s`

**Observed:** Full width of a 436px form; a compact charcoal email action follows 8px below. A provider action and a thin-rule 'or' divider appear above.

## Imagery and graphics

### Product demonstration stage

**Use:** Opening product proof below the hero.

**Observed:** A centered 675px by 506px video frame with 32px corners and a faint 2px blue-gray perimeter. It is narrower than the hero heading and set well below the action.

**Transfer:** Show a short legible workflow or a still with a real result, not a decorative empty browser window. A static before-and-after artifact can carry the demonstration when video is unavailable.

### Explanatory interface collage

**Use:** Signature visual language inside large feature cards.

**Observed:** A zoomed interface control with selection handles, a dense collection of colorful rounded app symbols, a phone over a metadata sheet and a chat-style research vignette each explain a different capability. Card artwork occupies about 448–480px above the prose, using cool-white backing, black text and localized vivid color.

**Transfer:** Include a tangible product detail and an organized breadth-of-work collage. For a product without polished UI, draw one enlarged output artifact, surround it with smaller related objects and give each card one readable interaction.

**Build:** For the enlarged-detail scene, place a pale gray rounded control partly off the left edge of a 529px-wide panel, outline its selected bounds with a 1px bright-blue SVG rectangle and square handles, then add a small orange cursor and rounded label near its lower right. For breadth, arrange varied 24px–100px rounded artifact tiles densely on a cool-white base, with pale offset backplates and a few overlaps; clip at the panel edges. Keep these saturated colors inside the artwork.

### Layered catalog previews

**Only for:** catalog collections

**Use:** Browsable example grids and featured-site cards.

**Observed:** Three-up landscape interface thumbnails are paired with small identity icons and understated labels. Flow previews stack three successively smaller panels behind a front image inside a cool-gray 24px-radius backing. Larger two-up site cards combine an icon, a 40px title, a muted 20px descriptor and overlapping interface previews clipped at the bottom.

**Transfer:** Use genuine product outputs or relevant documents. Keep media at readable proportions and vary the examples rather than repeating generic dashboard wireframes.

**Build:** For a flow stack, use a front 269px by 151px image, a middle 215px by 121px panel and a back 172px by 97px panel, all with 8px corners; center them horizontally and offset the smaller panels upward. Place the stack inside a 333px-wide backing padded 32px.

### Pastel proof constellation

**Only for:** pricing proof sections

**Use:** A visual breadth claim between centered heading and small quantified caption.

**Observed:** Colorful product symbols float on overlapping translucent pastel rounded squares, ranging from small tiles to larger offset backplates. The arrangement reads as a broad, balanced field rather than a strict logo grid.

**Transfer:** Use relevant output categories, supported integrations or original artifact symbols instead of a generic customer-logo wall.

**Build:** Arrange SVG symbols in an irregular grid over white. Behind each, add a rounded square with a very low-opacity blue, pink, mint or yellow fill; vary tile sizes and vertical offsets, overlap several backplates and leave white channels through the composition. Keep the header and caption outside the field.

### Icons

**Observed:** Most navigation icons are 24px monochrome outlines with approximately 1.5px–1.8px round strokes; small contextual symbols use 20px, while the identity mark is 48px. Tiny colorful category symbols appear beside catalog headings and feature-list labels.

**Transfer:** Use simple recognizable outline icons aligned to the text baseline; reserve filled or colorful symbols for product categories and visual proof.

## Section recipes

How recurring sections are built.

### First screen: Editorial product opening

**Observed:** A white app-like shell frames a centered editorial promise. A 270px rail occupies the left; the right pane has a 128px sticky search-and-mode header. The hero begins after 96px of top space: Context badge, 16px gap, Display headline in an 860px column, 16px gap to two lines of slate Body text in a 660px column, then Primary button after 40px. The headline spans roughly three quarters of the usable pane and remains regular black serif. After 126px, the Product demonstration stage begins; within the first 900px the full badge, headline, support and action are visible together with the upper part of the media. The stage continues below the fold, before compatibility proof. Layers are white canvas, faint media perimeter, product content and black text/actions; no atmospheric full-bleed background.

**Transfer:** Default to this promise-led opening for a new marketing page. Replace the stage with a real workflow or outcome illustration if there is no video. Keep the rail useful with actual destinations; a search header belongs only when the product offers meaningful search. A plan page opens with a short serif title, billing switch and three plans; a catalog opens with an interactive task field and suggested tasks instead of an additional large image.

**Avoid:** Do not turn the opening into a full-bleed dark dashboard, a giant bold sans slogan, or a split layout with competing primary actions. Do not use an empty media frame as the main object.

**Text style:** `display` — Title 400 · 50px/1.2 · tracking -0.02em

### Reading-column argument

**Observed:** A 755px left-aligned reading column sits centered within a wide section. Heading-lg can carry a complete multi-line argument, followed by Body prose after 16px. Major chapters begin with 96px top padding; additional paragraphs use 24px gaps.

**Transfer:** State a recognizable problem, explain its cause and make the product mechanism concrete without adding a card around the whole passage.

**Text style:** `heading-lg` — Base-Variable 500 · 40px/1.2 · tracking -0.03em

### Illustrated capability grid

**Observed:** Feature story cards form two equal columns with 16px gaps. Explanatory interface collage art sits above the title and prose; the 64px corners and Soft feature panel material unify different kinds of illustration.

**Transfer:** Use the grid to prove distinct capabilities through a close-up, breadth view, structured result and workflow example; adapt the number of cards to the story.

### Compact purchase summary

**Observed:** A Heading-lg and support line lead into a wide Soft feature panel. The 1074px-wide panel uses 77px vertical and 74px horizontal padding, a feature list at left and a 300px purchase column at right. Billing switch sits above a serif price and compact sign-in action.

**Transfer:** Use this concise purchase treatment on product pages; reserve the full three-plan comparison for a dedicated decision page.

### Identity close

**Observed:** All page types end with a centered 48px symbol above a 40px regular serif positioning line, separated by 16px. A 48px gap leads to Footer links and a contact line 16px below. The whole white footer uses 64px top and bottom padding. The catalog additionally places a 436px-wide account form above this close; the plan page arrives through FAQs, while the technical page arrives through a short business-contact passage.

**Transfer:** Retain the symbol-plus-editorial-positioning device on every new page, using the new product's own concise category statement. Keep closing navigation small; use a contextual final action above it rather than enlarging the footer.

### Installation timeline

**Only for:** technical product pages

**Observed:** A reading-column heading and short support line precede a thin vertical timeline with hollow circular nodes. Steps use Step-heading, a 4px gap to support text and 48px bottom spacing. A tool-selector row and compact 8px-corner actions appear inside steps; Command strip is a separate related setup chapter.

**Transfer:** Break setup into prerequisites, connection, authorization and successful first use; choose steps that match the actual product.

### Plan decision and proof

**Only for:** pricing pages

**Observed:** A short Display title and Billing switch precede three top-aligned plan cards with 32px gutters. Only the recommended card uses Prismatic recommended plan; all primary actions appear black and 56px high. Prices use Closing-serif, with muted billing suffixes. Supplemental offers, logos, a rating badge, pastel feature panels, a category-chip rail and Testimonial cards add proof. A fine-rule comparison table uses 84px rows and avoids zebra-striping; plans repeat before FAQ rows.

**Transfer:** Let the purchase decision lead, then supply substantive proof and explicit feature differences. Repeat purchase controls after long comparisons when useful.

### Browsable collection chapter

**Only for:** catalog pages

**Observed:** Catalog-heading with a small colorful category symbol, then Filter chips and a three-up landscape preview grid. Labels sit below media rather than on dark overlays. Flow collections use Layered catalog previews; featured examples switch to larger two-up cards. A 95px-high pale rounded 'more' strip closes a collection.

**Transfer:** Present examples by useful customer task, not by arbitrary visual categories. Make the closing strip a continuation link rather than another sales banner.

## Page flow

**Storyline:** Promise → tangible product proof → explanatory capabilities → practical adoption or purchase → remaining questions → editorial identity close.

### A focused product landing page that makes a technical capability feel designed and usable

1. **Promise** — Centered serif outcome, small context badge and one installation action.
2. **Product demonstration** — Narrow rounded video stage followed by compatible-tool marks.
3. **Problem and mechanism** — Reading-column argument followed by large illustrated capability cards.
4. **Practical adoption** — Rationale, vertical setup timeline and copyable command.
5. **Purchase** — Single broad rounded feature-and-price summary.
6. **Partnership invitation** — Short text passage with a direct contact link.
7. **Identity close** — Centered symbol, serif category statement and compact utilities.

**Transfer:** Borrow the move from taste-led outcome to concrete mechanism and easy setup; not every product needs integration instructions.

### An exploratory catalog that lets visitors experience the product before signing in

1. **Interactive promise** — Serif category statement, task-entry panel, mode controls and suggested tasks.
2. **Social proof** — Low-key company-mark strip.
3. **Product exploration** — Repeated taxonomy headings, filter chips and three-up interface grids; layered flow previews and larger two-up featured examples add variety.
4. **Conversion** — Provider sign-in, email field and compact email action.
5. **Identity close** — Shared editorial footer.

**Transfer:** Use an interactive opening only when there is a real task the visitor can try, then let the output collection do the selling.

### A purchase-decision page that explains differences while reinforcing quality

1. **Plan selection** — Serif title, billing switch and three plans with a prismatic recommended option.
2. **Alternative paths** — Three small supplemental offer columns.
3. **Social proof** — Company marks, rating badge and an airy symbol constellation.
4. **Capability proof** — Pastel media cards, quantified collection heading, chip rail and centered quote carousel.
5. **Comparison** — Fine-line feature matrix followed by repeated plan selection.
6. **Objection handling** — Narrow centered FAQ stack.
7. **Identity close** — Shared symbol and serif positioning line.

**Transfer:** Lead with a clear decision, distinguish the best-fit option without changing every button color, and answer transactional questions before the shared close.

## Writing

Direct, knowledgeable and design-literate without sounding ceremonial. Concrete mechanisms and recognizable tasks carry the confidence; warmth comes through plain speech rather than inflated enthusiasm.

**Do not copy:** Do not reuse Refero's name, identity mark, product names, customer logos, quotes, counts, prices, claims or contact details. Source examples illustrate syntax and must be replaced with truthful content for the new product.

- **Addressing the reader:** Speak to 'you' and 'your' in outcomes and instructions; refer to the product by name when explaining its mechanism, and use 'we' for a direct business invitation.
- **Rhythm:** Short imperative actions and plain noun labels sit beside medium-length explanatory sentences. Headlines can be a compact promise or a full two-part diagnosis; support text usually explains one mechanism and one result.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Give the reader or their tool a valuable quality, stated as a direct outcome. | 5–9 words | “Give your AI agent design taste” |
| Section argument | Name a familiar failure, then explain the missing ingredient. | Two short sentences | “You can spot an AI-generated page instantly — they all look the same. [Brand] MCP fills the design knowledge gap that causes this.” |
| Supporting line | Explain what happens before describing the improved output. | One or two sentences | “It studies before it builds — and the output looks designed, not generated.” |
| Primary action | Use a concrete verb or task; make the next step unmistakable. | 2–4 words | “How to install”<br>“Start with Free”<br>“Continue with Email” |
| Utility heading | Plain task or category name rather than a branded metaphor. | 1–5 words | “Why it matters”<br>“Compare Plans”<br>“Page Types” |

**Words and phrasing to use:** real; curated; proven; research; patterns; before it builds; in seconds; your tool; you're all set

**Avoid:** revolutionary; unleash; supercharge; 10x without proof; world-changing; magic as an explanation

**Rules:**

- Explain the product's inputs and resulting behavior, not merely its category.
- Use counts only when they establish useful scope; pair them with a noun rather than giant detached numerals.
- Write installation steps as actions and FAQs as real buyer questions.
- Keep compact interface labels in sentence case; save expressive language for the central promise.

## Do's and Don'ts

### Do

- Pair the 50px regular serif opening with 16px medium grotesk support, not a second display face.
- Use 96px section top spacing to separate narrative chapters without boxing each passage.
- Inset feature-card prose by 57px while allowing artwork to reach the clipped outer edges.
- Keep the default feature grid at two columns with 16px gaps and 64px card corners.
- Use one black 48px-high marketing action as the hero's visual anchor.
- Let relevant interface artifacts supply vivid color against the white and cool-gray frame.
- Finish with the 48px identity symbol and 40px serif positioning line, followed by small utility links.

### Don't

- Do not turn every surface into a 64px-radius blob: compact controls use 12px and quote cards use 16px.
- Do not introduce a saturated brand-color button system; main marketing actions remain black even in the highlighted plan.
- Do not use heavy black borders or deep neutral drop shadows where blue-gray alpha keylines are used.
- Do not enlarge paragraph text into a second headline; everyday explanatory copy stays 16px/24px.
- Do not make all headings serif; capability narratives use 40px medium grotesk.
- Do not place text labels over darkened thumbnail images; collection captions belong beneath the media.
- Do not let a three-plan table become the ordinary landing-page default; use the wide rounded purchase summary there.

## Motion and responsive

### Motion

**Observed:**

- Primary marketing action declares a 0.2s transition; filter chips and testimonial cards also declare 0.2s.
- The selected billing segment declares 0.3s ease-out; footer link color declares 0.2s.
- Catalog image layers declare transform 0.2s and thumbnail backings declare box-shadow 0.15s.

**Transfer:**

- Preserve subtle control feedback and restrained selected-segment movement; keep interface art readable as a still.
- Use movement for collections and product demonstration, not to animate every paragraph.

**Unknown:**

- Exact behavior of the opening video and long-running rails is not established.
- Focus-visible, pressed states and animation choreography are not fully known.

### Responsive

**Observed:**

- The feature grid declares repeat(auto-fill, minmax(420px, 1fr)).
- Declared width breakpoints include 768px, 980px, 1100px, 1293px, 1320px and larger desktop thresholds.

**Transfer:**

- For a narrow layout, let the feature grid become one column and keep the illustration above its prose.
- Adapt the desktop rail into compact navigation rather than retaining a 270px sidebar next to narrow content.
- Preserve the centered serif promise, one primary action and outcome stage; stack the purchase-summary columns.

**Unknown:**

- Mobile navigation structure, exact typography changes and side-padding values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
