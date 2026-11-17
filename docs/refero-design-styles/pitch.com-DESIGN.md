# Pitch — purple stagecraft for teams

## Overview

An outgoing, design-literate software style that combines theatrical purple atmosphere with clean white working space. Rounded geometric sans headlines, friendly reading text and monospace chapter labels make complex tools feel creative rather than technical. Interface collages, oversized controls and personable portrait testimonials give it a polished, collaborative energy, with spacious storytelling around comparatively dense product demonstrations.

### Essentials

- The promise behaves like a stage title: centered Mark Pro Bold at 180px/0.8 with -0.04em tracking, spanning two tightly stacked lines above a working control rather than a conventional button row.
- Purple supplies the scenery, not just the links: #280f62 anchors the opening and closing acts, white carries most capability explanation, and #ebe3fe and #c6a5ff connect them through soft blurred light. Lime #c4ee87 is reserved for compact actions and selected proof panels, not the whole canvas.
- Actions deliberately mix silhouettes: 30px-radius white or deep-purple pills sit beside 4px-radius lime rectangles, usually 44px high in navigation and 52px in major conversion groups.
- The product is staged as an editable object: rounded 24px media fields contain interface fragments, floating toolbars, selection outlines and oversized cursors. Use a real workflow or a simplified, legible task composition when finished product media is unavailable.
- Proof becomes a colorful wall, not a row of grayscale logos alone: 312×410px testimonial cards with 20px corners and 24px gaps mix violet, lime and full-bleed portraits with lavender light behind white quotes.
- Chapter labels have a technical wink: uppercase Space Mono at 18px/1.6 with -0.02em tracking sits above tightly tracked 48px/1.2 bold section headings; substantial chapters use 120px vertical breathing room.
- The ending remains a designed scene: a soft white-to-purple horizon leads into deep purple, then a rounded split footer pairs a broad white directory with a narrow purple conversion panel. Include the glow and split ending even when the product has no visual catalog.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage purple | `#280f62` | `--color-deep-purple` | background, text, action | Dominant dark canvas, purple headings and solid pill actions. |
| Pale lavender | `#ebe3fe` | `--color-pale-lavender` | surface, border, text | Feature cards, story captions, pale hero lettering and faint plan outlines. |
| Lilac | `#c6a5ff` | `--color-lilac` | text, surface, border, accent | Headings on dark bands, announcement strip, graphic controls and purple outlines. On light-header page types it also replaces lime on the small signup rectangle. |
| Lightened purple glass | `#533f81` | `--color-glass-purple` | surface | Visible white at 20% over stage purple; used for dark-section question panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric purple | `#5318eb` | `--color-electric-purple` | text, link, surface, accent | Feature headings, chapter labels, statistics, quote cards and link hover. |
| Lime | `#c4ee87` | `--color-lime` | surface, action, accent | Rectangular actions and intermittent bright proof or collaboration cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text, action | Main explanatory canvas, cards, light buttons and text on dark purple. |
| Integration backing | `#f6f6f6` | `--color-integration-gray` | surface | Pale circular backings for integration logos. |
| Secondary gray | `#666666` | `--color-muted-gray` | text | Centered introductory paragraphs and secondary explanatory copy. |
| Reading gray | `#363636` | `--color-body-gray` | text | Body copy accompanying feature explanation. |
| Purple black | `#0c021c` | `--color-ink` | text, accent | Main headings, reading text and dark icons on light surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstration panels | Media lavender white | `#f8f5ff` | `--color-media-tint` | surface | Quiet interior backing around interface fragments. |
| pricing pages | Comparison lavender white | `#f5efff` | `--color-comparison-tint` | surface | Feature comparison body, distinct from stronger lavender cards. |

## Typography

- **Mark Pro** — Display titles, section headings, card headings, quotations and statistics. Geometric sans with broad circular forms, a friendly single-storey character and emphatic bold silhouettes. If unavailable, use **Plus Jakarta Sans**. Use 700 for bold cuts and 400 for catalog labels; tune line breaks to preserve broad silhouettes. Font stack: "Mark Pro", "Plus Jakarta Sans", Arial, sans-serif.
- **Eina 03** — Reading text, navigation, button labels, captions and directory links. Clean geometric-humanist sans with a warm, open lowercase and restrained bold. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **DM Sans**. Use 400 and 700; retain the relaxed 1.6 reading line height. Font stack: "Eina 03", "DM Sans", Arial, sans-serif.
- **Space Mono** — Uppercase chapter labels and compact plan labels. Characterful technical monospace contrasting with the rounded heading sans. Font stack: "Space Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Mark Pro | 700 | 180px | 0.8 | -0.04em | Default theatrical marketing opening, centered and normally broken into two lines. |
| closing-display | Mark Pro | 700 | 92px | 0.9 | -0.0022em | Oversized lilac title in the dark catalog or getting-started chapter. |
| chapter-display | Mark Pro | 700 | 64px | 0.9 | -0.04em | Large verb titles inside numbered workflow cards. |
| stat | Mark Pro | 700 | 60px | 1 | normal | Short purple numerals with a suffix and small explanatory caption. |
| heading | Mark Pro | 700 | 48px | 1.2 | -0.04em | Section leads, large statements and the footer conversion headline. |
| feature-heading | Mark Pro | 700 | 32px | 1.2 | -0.04em | Benefit rows and compact statement titles. |
| card-heading | Mark Pro | 700 | 28px | 1.2 | -0.02em | Feature cards and accordion questions. |
| quote | Mark Pro | 700 | 20px | 1.2 | -0.02em | Dense, personable testimonial text. |
| body-lead | Eina 03 | 400 | 18px | 1.6 | -0.02em | Section introductions and the centered opening support line. |
| eyebrow | Space Mono | 400 | 18px | 1.6 | -0.02em, uppercase | Chapter markers above heading groups. |
| body | Eina 03 | 400 | 16px | 1.6 | normal | Feature explanations, directory links and regular paragraphs. |
| button | Eina 03 | 700 | 16px | 1.2 | -0.02em | Action labels in both pill and rectangular buttons. |
| navigation | Eina 03 | 400 | 16px | 1.6 | -0.02em | Centered header navigation links and audience tabs. |
| caption | Eina 03 | 400 | 14px | 1.6 | normal | Quote attribution and small story outcomes. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product overviews, story indexes and company narratives | secondary-display | Mark Pro | 700 | 92px | 0.9 | -0.0022em | Compact two-line opening instead of the theatrical marketing title. |
| visual catalogs and template browsers | catalog-label | Mark Pro | 400 | 64px | 0.9 | -0.04em, uppercase | Vertical category list; the active label is white while inactive labels use 20% opacity. |
| pricing pages | pricing-display | Mark Pro | 700 | 64px | 0.9 | -0.02em | Left-aligned plan-selection promise. |
| pricing pages | price | Mark Pro | 700 | 40px | 1.1 | -0.024em | Plan price numerals. |
| customer story indexes | story-heading | Mark Pro | 700 | 24px | 1.2 | -0.02em | Compact outcome-led card titles. |

**Notes:**

- Large marketing type compresses line height to 0.8; ordinary 48px section headings relax to 1.2. Do not apply the opening line height to long reading sections.
- Keep bold visual weight consistent across headings even when a title contains a strong span. Catalog categories are the deliberate regular-weight exception.
- Negative tracking is strongest in display and section type; paragraphs remain normal or -0.02em. Chapter labels are monospace but not widely letter-spaced.

## Layout

**Density:** Airy around storytelling, compact within interfaces and proof cards; broad pauses alternate with tightly packed visual detail.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading and close heading-to-copy relationships. |
| 10px | Compact icon groups and stat-to-caption spacing. |
| 12px | Button padding and small control groups. |
| 16px | Directory link gaps and smaller content stacks. |
| 20px | Feature title-to-paragraph gaps and composer inset. |
| 24px | Default card gutter, side inset, card padding and heading-to-introduction gap. |
| 32px | Roomier feature card padding and chapter grid gaps. |
| 40px | Numbered card internal stages and closing title-to-copy spacing. |
| 52px | Content-to-action pause in feature and catalog sections. |
| 64px | Section heading group to main visual and payoff statement to stats. |
| 72px | Opening title to interactive centerpiece. |
| 80px | Start of the first white explanatory chapter. |
| 120px | Major chapter top and bottom padding. |

### Containers and grids

- **content-container**: max width 1224px · side padding 24px. Centered marketing content; at 1440px this leaves 108px on each side.
- **opening-title**: max width 1060px · side padding 24px. Centered marketing opening; the main interactive object is narrower than its heading.
- **centered-introduction**: max width 780px. Centered section title and support paragraph; left-aligned introductory blocks narrow to 550px.
- **feature-row**: 2 columns · gap 40px. Text and a roughly 592px-wide staged product image, with text paragraphs capped at 447px.
- **bento**: 2 columns · gap 24px. Unequal-width feature rows, alternating a wider white panel and narrower lavender or purple panel.
- **footer-shell**: max width 1402px · side padding 24px. Near-full-width inset footer. White directory occupies about 70% of the shell and purple conversion panel about 30%.
- **story-grid** (only for customer story indexes): 2 columns · gap 24px. Two 600px-wide story cards in the standard container.
- **plan-grid** (only for pricing pages): max width 1220px · 4 columns · gap 24px. Four parallel plans with aligned prices and bottom actions; an enterprise panel spans beneath them.

## Corner radius

| Element | Radius |
| --- | --- |
| pill-actions | 30px |
| rectangular-actions | 4px |
| feature-cards | 24px |
| workflow-cards | 32px |
| quote-cards | 20px |
| composer | 16px |
| social-circles | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| composer-glow | `0px 20px 60px -20px rgba(198, 165, 255, 0.35)` | Focused interactive centerpiece; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Explanatory body of the page.

**CSS:** `background: #ffffff; color: #0c021c`

#### Purple stage · level 0

**Use:** Theatrical opening, audience chapter, dark catalog and closing environment.

**CSS:** `background: #280f62; color: #ffffff`

**Observed:** Lavender titles and white body copy sit directly on the dark field; panels do not need extra outlines.

**Transfer:** Use as a substantial narrative environment rather than a thin decorative stripe.

#### Lavender card · level 1

**Use:** Capability and story information panels.

**CSS:** `background: #ebe3fe; border-radius: 24px; box-shadow: none`

**Observed:** Flat, generous rounded fields carry both text and substantial interface artwork.

**Transfer:** Alternate with white and deep-purple cards; retain a limited surface palette.

#### Purple feature card · level 1

**Use:** A high-contrast capability in a mixed card group.

**CSS:** `background: #280f62; color: #ffffff; border-radius: 24px`

#### Soft lavender light · level 0

**Use:** Atmosphere behind white capability sections.

**CSS:** `background: radial-gradient(ellipse at center, rgba(198, 166, 255, 0.4) 0%, #ffffff 100%)`

**Observed:** Broad, soft lavender pools fade into white without a hard panel edge.

**Transfer:** Keep the glow low-contrast and larger than the card group; exact stops are not essential.

#### Composer glass surround · level 1

**Use:** Halo around the opening interactive object.

**CSS:** `background: rgba(255, 255, 255, 0.16); border-radius: 24px; padding: 12px; backdrop-filter: blur(10px)`

#### Question glass · level 1

**Use:** Accordion rows over the dark stage.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 24px; color: #ffffff`

#### Comparison field · level 1

**Only for:** pricing pages

**Use:** Expanded feature-comparison group.

**CSS:** `background: #f5efff; border: 1.5px dashed #c6a5ff; border-radius: 20px`

**Observed:** White inset rows sit within a pale group field, beneath color-coded plan tabs.

**Transfer:** Keep rows compact and category grouping clearly visible.

## Components

### Navigation

**Use:** Persistent global header.

**CSS:** `height: 80px; background: rgba(40, 15, 98, 0.97); display: flex; align-items: center; padding: 0px 24px; color: #ffffff`

**Text style:** `navigation` — Eina 03 400 · 16px/1.6 · tracking -0.02em

**Observed:** Logo left, centered text links with small dropdown chevrons, and white pill plus lime rectangular actions right. The default is dark. Light product, pricing and story-index headers use an almost opaque white background, dark links, purple login pill and lilac signup rectangle. A 44px announcement strip sits above the default header when there is news.

**Transfer:** Keep the three-part balance and persistent header without importing the announcement when there is no real announcement.

### Primary pill

**Use:** Main action on white or lavender.

**CSS:** `background: #280f62; color: #ffffff; border-radius: 30px; height: 52px; padding: 12px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — Eina 03 700 · 16px/1.2 · tracking -0.02em

**Observed:** Text comes first and a simple right arrow closes the action. The compact navigation version is 44px high.

### Lime action

**Use:** Contrasting companion action and signup.

**CSS:** `background: #c4ee87; color: #0c021c; border-radius: 4px; height: 44px; padding: 10px 12px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `button` — Eina 03 700 · 16px/1.2 · tracking -0.02em

**Observed:** Its squarer silhouette distinguishes it from adjacent pills. Major dark-section action groups use a 52px-high version.

### White pill

**Use:** Action on a dark field or dark header.

**CSS:** `background: #ffffff; color: #0c021c; border-radius: 30px; height: 44px; padding: 12px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `button` — Eina 03 700 · 16px/1.2 · tracking -0.02em

**Observed:** Often contains a trailing arrow and pairs with the lime rectangle. Major conversion groups use a 52px-high version.

### Task composer

**Use:** Interactive centerpiece of the theatrical opening.

**CSS:** `background: #ffffff; border: 1px solid rgba(255, 255, 255, 0.4); border-radius: 16px; padding: 20px; outline: 2px solid #c6a5ff; outline-offset: 2px; box-shadow: 0px 20px 60px -20px rgba(198, 165, 255, 0.35); backdrop-filter: blur(16px); display: flex; flex-direction: column; gap: 16px`

**Observed:** A 678×166px white working field sits in Composer glass surround. The large text-entry area comes first; a lower toolbar puts add and prompt controls left and the small generation action right.

**Transfer:** Replace it with one meaningful input, search, configuration or task preview. If the product cannot act inline, use a clearly labeled interactive-looking preview linked to the actual workflow rather than fake functionality.

### Feature card

**Use:** Capability explanation within mixed bento layouts.

**CSS:** `background: #ebe3fe; color: #0c021c; border-radius: 24px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `card-heading` — Mark Pro 700 · 28px/1.2 · tracking -0.02em

**Observed:** Heading and short paragraph group above or beside a substantial interface scene. White and deep-purple variants share the construction; purple reverses the text. Layouts vary panel width rather than forcing equal cards.

### Testimonial card

**Use:** Human proof inside a full-width, two-row wall.

**CSS:** `background: #5318eb; color: #ffffff; width: 312px; height: 410px; border-radius: 20px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `quote` — Mark Pro 700 · 20px/1.2 · tracking -0.02em

**Observed:** Quote mark and left-aligned bold quotation sit above a centered attribution and customer mark. Lime versions use dark text; portrait versions place white copy over a lavender lower glow.

**Transfer:** Mix equally sized photo and text-only proof cards. Use verified quotations and identifiable people; use text-only cards if photography is unavailable.

### Question row

**Use:** Objection handling on the dark stage.

**CSS:** `background: rgba(255, 255, 255, 0.2); color: #ffffff; border-radius: 24px; padding: 24px; display: flex; align-items: center; gap: 10px`

**Text style:** `card-heading` — Mark Pro 700 · 28px/1.2 · tracking -0.02em

**Observed:** Centered question text takes most of a 604px-wide row, with a 32px white circular plus control at the right. Rows stack with 24px gaps. Pricing uses left-aligned dark questions on pale lavender beside a separate heading column.

**Transfer:** Preserve the friendly, substantial question panels; expand content within the same card rather than turning the list into a dense table.

### Directory link

**Use:** Footer directory and simple inline navigation.

**CSS:** `color: #0c021c; text-decoration: none`

**Text style:** `body` — Eina 03 400 · 16px/1.6

**Observed:** Unboxed links form long left-aligned columns, spaced by 16px, under bold group headings.

**States:** Declared: hover color #5318eb and text-decoration-line none; focus-visible unknown.

### Plan card

**Only for:** pricing pages

**Use:** Parallel plan choices.

**CSS:** `background: #ffffff; border: 1px solid #ebe3fe; border-radius: 32px; padding: 16px 16px 32px 16px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `price` — Mark Pro 700 · 40px/1.1 · tracking -0.024em

**Observed:** A colored plan-name cap overlaps behind the white body; caps progress from pale lavender through lilac and electric purple to deep purple. Price and billing unit lead, followed by a dashed summary box, inclusions and bottom outlined action. Enterprise uses a full-width purple-black cap and white interior.

**Transfer:** Keep the color progression attached to tier hierarchy, not arbitrary feature categories.

### Comparison panel

**Only for:** pricing pages

**Use:** Grouped side-by-side feature details.

**CSS:** `background: #f5efff; border: 1.5px dashed #c6a5ff; border-radius: 20px`

**Observed:** A category header with icon and chevron opens compact white rows. Colored plan labels align above corresponding columns. Other categories appear as rounded lavender header bars.

**Transfer:** Retain the alignment between tier columns and summary cards; group by reader questions rather than listing every technical attribute at once.

### Story card

**Only for:** customer story indexes

**Use:** Outcome-led customer editorial links.

**CSS:** `background: #ebe3fe; color: #280f62; border-radius: 24px; overflow: hidden`

**Text style:** `story-heading` — Mark Pro 700 · 24px/1.2 · tracking -0.02em

**Observed:** A wide branded image occupies the upper area; a rounded lavender caption panel overlaps its lower half, with a small customer mark near the upper right and title below. Some cards add a compact measured outcome or quote.

**Transfer:** Use the customer's visual identity in the image, but normalize all captions to the lavender surface and consistent type.

## Imagery and graphics

### Purple collage stage

**Use:** Signature atmospheric opening behind the main promise.

**Observed:** Small presentation-like artifacts float at different sizes around the edges of a saturated purple environment. They are dim, softened and partly clipped, leaving a clear central reading area. Lavender light blooms at the sides and bottom while the middle-right stays deep purple.

**Transfer:** Stage artifacts of the new product's outputs around a single foreground task. The minimum version is six to ten original output thumbnails, not generic stock technology art.

**Build:** Use a #280f62 full-bleed field. Place small rectangular artifact images in absolute layers around the perimeter, lower their opacity to roughly 0.15–0.3 and soften with a small blur. Add oversized radial lavender light layers using rgba(198,165,255,0.35), with a 60px blur. Keep the central heading and white task field sharp and above every atmospheric layer; clip the entire scene.

### Editable interface collage

**Use:** Primary feature media, occupying roughly half a row or most of a capability card.

**Observed:** White application windows, vivid designed content and floating controls sit on lavender gradient backings. Selection outlines, dotted inset frames, white-edged black cursors and lifted toolbars make the media feel actively manipulated. The content can include editorial photography, bold type and colorful slides without recoloring the surrounding website.

**Transfer:** Show one actual task with one or two exaggerated controls, not a whole unreadably small application. Minimum version: one faithful interface panel, a selected output area and a floating toolbar on a softly lit lavender backing.

**Build:** Create a 24px-rounded lavender media field. Add two broad blurred purple radial pools behind a white app panel. Use a fine lavender dashed rounded rectangle as an inset selection boundary. Layer a small white toolbar across an edge and an SVG cursor with dark fill and thick white outline near the relevant control. Keep realistic content inside the app distinct from marketing type.

### Portrait proof

**Use:** Human cards in the testimonial wall and supporting audience proof.

**Observed:** Faces fill rounded cards with natural, informal framing, mixing black-and-white portraits and warm color photography. A saturated lilac-to-transparent lower wash supports white quote text and attribution.

**Transfer:** Choose candid, credible people rather than studio corporate headshots. Keep facial detail unobscured and put the glow behind the text only.

**Build:** Use object-fit: cover inside a 20px-rounded clipped card. Overlay a bottom-up gradient from #c6a5ff to rgba(198,165,255,0), extending over the lower half. Set quote content above it with 24px insets.

### Blurred horizon

**Use:** Signature transition between the white explanatory world and the deep-purple closing world.

**Observed:** A broad curved white horizon falls away into a soft lavender fringe and then a solid dark-purple field; it reads like light, not a decorative wave line.

**Transfer:** Carry this device into every marketing page's closing environment, regardless of whether the page has a catalog.

**Build:** Start a #280f62 band and position a white ellipse wider than the viewport above its top edge. Blur the ellipse edge by about 40–60px and place a second lower-opacity lilac ellipse behind it. Clip the band so only a shallow luminous arc remains. Match the soft glow; exact stops are not essential.

### Catalog preview strip

**Only for:** visual catalogs and template browsers

**Use:** Rich dark-section browsing scene.

**Observed:** Regular-weight uppercase categories stack vertically in a narrow right-hand column. Only one category is bright white; its landscape previews form a horizontal strip below, fading into the dark field at the sides. Other categories remain dim.

**Transfer:** Use original output examples or workflow categories. For a product without templates, show saved setups, use cases or deliverable examples.

**Build:** Stack 64px category labels with 32px gaps. Set inactive labels to opacity 0.2. Under the active label, lay out 198×120px previews in a clipped horizontal row and use transparent-to-#280f62 edge overlays to fade both ends.

### Logo cloud and ribbons

**Only for:** customer-proof and company pages

**Use:** Branded proof around a compact opening or closing invitation.

**Observed:** Customer marks appear in white rounded capsules, either floating around a title, orbiting a dark circular quote symbol, or continuing off both edges in two horizontal rows. Pale lavender glows sit behind rather than within the logos.

**Transfer:** Use genuine partner or customer marks. If none are available, replace the mark capsules with verified short outcome labels and retain the composition without implying endorsement.

**Build:** Build variable-width white capsules with 16px 24px padding and fully rounded ends. Arrange two staggered rows or an asymmetrical cluster around one purple circle. Back the cluster with 800×500px radial lavender ellipses fading to transparent. Keep logos predominantly dark purple.

### Company documentary photography

**Only for:** company narratives

**Use:** Editorial explanation of people and culture.

**Observed:** Outdoor team interactions, a flag in clear daylight and people working behind glass alternate with white and lavender text panels. Images are generously framed and rounded rather than circular headshots.

**Transfer:** Use real places and team activities, balancing cool daylight with warmer indoor scenes. Preserve the same card geometry as product chapters.

### Icons

**Observed:** Small interface-style symbols use dark ink or purple outlines, often 20px with roughly 1.5–2px strokes and rounded joins. Marketing feature icons can be 32px; colored circular icon chips are about 40px. Right arrows close pill actions, chevrons mark menus and plus signs sit inside circular question controls.

**Transfer:** Choose a consistent simple outline set. Use filled logos only for actual organizations and reserve oversized white-edged cursors for product imagery.

## Section recipes

How recurring sections are built.

### First screen: Theatrical task opening

**Observed:** The first screen is a full-width Purple collage stage beneath Navigation. A centered two-line white title spans about three quarters of the viewport and is set in display. Its block occupies roughly 288px of height, with a 72px pause before a much narrower, 702px-wide Composer glass surround containing Task composer. A short centered body-lead support line follows with a 24px gap. Layers run from deep-purple canvas, to dim floating artifacts, to lavender light, to the sharp title and glowing white task field. Within the first 900px the title, entire composer, lower toolbar action and two-line support are visible. The logo proof row and white explanatory chapter fall below this screen. The primary in-scene action is the task control; conventional signup and login remain in the header.

**Transfer:** Use a short outcome promise and one useful product task, with original output artifacts around it. Without finished artwork, use a simplified real task panel and carefully arranged output thumbnails with the same glow and scale. Product-overview variants use secondary-display above a wide framed demonstration on pale lavender; story indexes use a compact title with logo capsules, company narratives use a smaller dark atmospheric title, and pricing opens with a left-aligned pricing-display beside billing controls.

**Avoid:** Do not replace the centerpiece with three generic CTA buttons, or place a small headline above an enormous laptop mockup. Do not sharpen the background artifacts until they compete with the promise.

**Text style:** `display` — Mark Pro 700 · 180px/0.8 · tracking -0.04em

### Chapter heading group

**Observed:** An eyebrow sits 8px above heading, with body-lead support 24px below. Left-aligned variants cap text at 550px; centered variants use 780px. Capability chapters commonly have 120px top and bottom padding and 64px between heading group and content.

**Transfer:** Choose left alignment for narrative turns and centered alignment for a family of capabilities; preserve the mono-to-bold contrast.

**Text style:** `heading` — Mark Pro 700 · 48px/1.2 · tracking -0.04em

### Benefit and staged demonstration

**Observed:** A two-column Feature-row pairs a 32px purple feature-heading with body copy and a roughly 592px-wide Editable interface collage. A small purple outline icon sits beside the title. Long vertical breathing room lets the demonstration remain the focus as the reader moves through benefits.

**Transfer:** Give each row a single outcome and one visual task; vary the visible output, not the typography.

### Payoff statement and numbers

**Observed:** A narrow eyebrow column sits left of a broad purple statement. Below the statement, three aligned statistics use stat with 10px between number and body caption, 24px between columns and 64px above the stat row. The number, suffix and caption are treated as one unit.

**Transfer:** Use a concise argument followed by a few verified metrics. If numeric proof is unavailable, retain the broad statement and use short concrete outcome labels rather than invented numbers.

**Text style:** `stat` — Mark Pro 700 · 60px/1

### Numbered workflow deck

**Observed:** An introductory heading group leads into oversized rounded workflow cards on lavender light. Each card begins with a parenthesized two-digit step, a 64px chapter-display verb and a small icon cluster. Large interface artwork fills the center, then a card heading and paragraph close the card. White and deep-purple cards overlap or continue beyond the viewport with a slight theatrical angle.

**Transfer:** Use this as a visual explanation of a process, keeping each step about a reader action rather than a feature inventory.

**Text style:** `chapter-display` — Mark Pro 700 · 64px/0.9 · tracking -0.04em

### Capability bento

**Observed:** Feature card groups use 24px gutters and mixed widths. A wider white panel carries a detailed task image; neighboring lavender and dark-purple panels alternate their text/media order. Product chapters also use a full-width lime collaboration card with a large image on one side and compact copy on the other.

**Transfer:** Let content importance determine panel area. Mix surface colors with restraint so each chapter still has one clear visual lead.

**Text style:** `card-heading` — Mark Pro 700 · 28px/1.2 · tracking -0.02em

### Two-row proof wall

**Observed:** Testimonial card rows extend beyond both viewport edges and are offset from one another, with 24px gaps both ways. Portraits alternate with electric-purple and lime quotes; a white summary proof tile interrupts the second row. A centered text action follows below.

**Transfer:** Preserve the edge-to-edge abundance and alternating material, even with fewer original endorsements by building a shorter wall rather than repeating fabricated quotes.

**Text style:** `quote` — Mark Pro 700 · 20px/1.2 · tracking -0.02em

### Integration bridge

**Observed:** A centered heading sits over an arcing arrangement of 92px pale circular logo backings, with a wider purple product capsule at the center. A compact arrow link closes the scene, followed by the Blurred horizon.

**Transfer:** Use this composition to connect the product to a real ecosystem. Without integrations, adapt the smaller nodes to supported inputs and the center to the resulting output.

### Dark audience chapter

**Observed:** Purple stage carries a centered lavender heading, thin-underlined audience tabs, then a two-column photograph and explanation. Stacked proof cards give the right column depth. White pill and Lime action form a centered conversion group beneath.

**Transfer:** Show distinct reader contexts with corresponding proof, rather than duplicating the same generic paragraph under every tab.

**Text style:** `heading` — Mark Pro 700 · 48px/1.2 · tracking -0.04em

### Dark visual catalog

**Observed:** A closing-display lilac title, raised count, short white introduction and White pill fill the left half; Catalog preview strip fills the right. The dark field continues into neighboring sections rather than creating isolated rounded boxes.

**Transfer:** Use for rich output libraries or getting-started choices; retain the editorial left/right contrast even if the catalog becomes a set of workflow examples.

**Text style:** `closing-display` — Mark Pro 700 · 92px/0.9 · tracking -0.0022em

### Question chapter

**Observed:** On Purple stage a centered lilac heading leads into a 604px-wide stack of Question row components. The pricing variant is white with its heading left and pale-lavender questions right.

**Transfer:** Use this chapter for genuine purchase or adoption objections; match the theme to its surrounding narrative.

**Text style:** `card-heading` — Mark Pro 700 · 28px/1.2 · tracking -0.02em

### Luminous split ending

**Observed:** Blurred horizon establishes the purple closing environment. Oversized subdued brand lettering spans above a near-full-width rounded footer shell. Social links use 32px pale-lavender circles. A white directory with four text columns fills about 70% of the shell; a deep-purple conversion panel fills the rest. The panel repeats a 48px lilac category promise inside a dashed editable-selection frame with a cursor motif, then White pill and Lime action. Copyright anchors its lower edge. The actual final page edge retains the purple surround and rounded shell, not a plain white legal strip.

**Transfer:** End with the product's own short category promise and useful directory. Keep the split composition, editable-object motif and luminous purple surround even when the directory is shorter.

**Text style:** `heading` — Mark Pro 700 · 48px/1.2 · tracking -0.04em

### Plan selector and comparison

**Only for:** pricing pages

**Observed:** A pale-lit white opening pairs a 64px left title with a pill-shaped yearly/monthly switch. A bordered seat panel with a purple gradient slider precedes the four-column Plan card grid. A full-width enterprise row follows; below, aligned colored tier tabs and Comparison panel groups support detailed evaluation. Proof wall, split FAQ, luminous horizon and split footer finish the page.

**Transfer:** Expose the variables that actually affect purchase before detailed features. Keep tier colors consistent across summary and comparison.

### Customer editorial index

**Only for:** customer story indexes

**Observed:** A secondary-display title sits on a lavender haze with floating white logo capsules. A wide 32px-rounded featured story pairs dark copy area and branded artwork. The directory begins with a heading and small rounded category filters, followed by the two-column Story card grid and a centered load-more pill. A two-row logo ribbon closes before the horizon and footer.

**Transfer:** Make outcomes and identities scannable; preserve a highlighted lead story above the regular grid.

**Text style:** `story-heading` — Mark Pro 700 · 24px/1.2 · tracking -0.02em

### Company narrative and invitation

**Only for:** company narratives

**Observed:** A compact dark atmospheric title fades into a centered introduction, then large editorial imagery, purple statistics and paired white/lavender documentary cards. A large 48px quotation with a small pill-shaped author credit gives the text its own visual moment. A 1224px-wide lavender closing card places the invitation left and Logo cloud and ribbons artwork right.

**Transfer:** Translate this into the new organization's own purpose and people; keep documentary images and a strong first-person statement distinct from product demos.

**Text style:** `heading` — Mark Pro 700 · 48px/1.2 · tracking -0.04em

## Page flow

**Storyline:** Outcome promise → tangible working demonstration → capability explanation → human or quantified proof → useful starting choices and objections → luminous conversion ending.

### Broad marketing landing page

1. **Promise** — Theatrical task opening with a large outcome title and working composer.
2. **Capability explanation** — Left-led chapter heading and spacious benefit/demo rows.
3. **Quantified proof** — Purple payoff statement and three prominent numbers.
4. **Process demonstration** — Large numbered workflow deck.
5. **Human proof** — Two-row portrait and bright-quote wall.
6. **Capability depth** — Mixed-surface bento and integration bridge.
7. **Reader relevance** — Dark audience chapter with contextual proof.
8. **Starting choices and objections** — Dark visual catalog and substantial question rows.
9. **Closing conversion** — Luminous split ending.

**Transfer:** Compress the number of capability chapters to suit the product, but preserve the contrast between theatrical promise, tangible working detail and human proof.

### Purchase evaluation and plan selection

1. **Pricing** — Plan promise, billing switch, seat control and four color-coded plan cards.
2. **Comparison** — Enterprise option followed by grouped feature comparison.
3. **Social proof** — Shared testimonial wall.
4. **Objection handling** — Light split-heading FAQ.
5. **Closing conversion** — White-to-purple horizon and shared split ending.

**Transfer:** Lead with buying variables and clear tier differences; borrow the brand atmosphere without putting a giant theatrical display above a utility task.

### Product overview and capability education

1. **Promise and demonstration** — Compact centered title on pale atmosphere with a broad framed product video.
2. **Positioning** — Centered introduction and illustrated expandable benefit group.
3. **Capability chapters** — Creation, collaboration and delivery explained with varied bento compositions.
4. **Social proof** — Portrait and quote wall.
5. **Starting choices** — Dark getting-started invitation beside visual catalog.
6. **Closing conversion** — Shared split footer.

**Transfer:** Organize chapters around the reader's workflow and alternate the density of demonstration, not the visual identity.

### Customer proof and case-study discovery

1. **Social proof promise** — Compact title surrounded by customer logo capsules.
2. **Featured proof** — Large dark/light featured story card.
3. **Discovery** — Category chips and two-column outcome cards.
4. **Collective proof** — Invitation over lavender glows and two logo ribbons.
5. **Closing conversion** — Luminous horizon and shared split footer.

**Transfer:** Keep the index more editorial and scannable than a product page; use one prominent lead story and clear outcome titles.

### Company purpose and credibility

1. **Identity** — Dark atmospheric short title and concise centered introduction.
2. **Human context** — Large documentary image paired with a broad bold statement.
3. **Quantified credibility** — Purple company statistics.
4. **Trust** — Paired documentary cards and a large founder quotation.
5. **Purpose** — Centered heading and compact editorial paragraph.
6. **Closing invitation** — Lavender invitation card with orbiting proof capsules.
7. **Closing conversion** — Horizon and shared split footer.

**Transfer:** Use authentic origin, people and convictions; preserve the same cards, glows and typography while reducing product-interface media.

## Writing

Confident, creative and commercially grounded. It speaks about serious work with friendly directness, balancing polished design language with concrete verbs and observable outcomes.

**Do not copy:** Do not reuse Pitch's name, logos, customer identities, artwork, proprietary product labels, quotations, adoption counts, time-savings figures, founding facts or other brand-specific claims. Source examples illustrate syntax and tone only; replace them with the new product's substantiated content.

- **Addressing the reader:** Talk directly to you and your team. Use we for company intent, and the product name when explaining what the tool does.
- **Rhythm:** Short, forceful headlines alternate with one or two conversational explanatory sentences. Fragments and three-beat phrases create pace; occasional parentheses and em dashes add a human aside.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct creation verb followed by the business outcome, or a confident new-category declaration. | 4–7 words | “Create slides that win.”<br>“The new era of presentations” |
| Chapter heading | Make a reader benefit concrete, often with a short rhythmic pair. | 4–10 words | “From first draft to closed deal, and beyond”<br>“Great ideas deserve great slides” |
| Supporting line | Connect a specific capability to the full workflow; use compact fragments before the explanatory sentence. | 15–35 words | “Built-in AI. Connected to your stack. Design, deliver, and track decks that land, from first prompt to closed deal.”<br>“From first slide to final delivery, [Brand] is where teams create presentations that actually land.” |
| Feature title | A concrete verb or ownership phrase, not a technical taxonomy. | 3–7 words | “Keep complete design control”<br>“Your brand, built in” |
| Action | Short verb phrase with low-friction qualifier when justified. | 2–5 words | “Start creating”<br>“Sign up for free”<br>“Get a demo” |
| Story title | How a named team achieves a concrete result. | 8–14 words | “How Warm & Fuzzy makes every deck a portfolio piece” |
| Question | A straightforward adoption question in the reader's language. | 5–15 words | “Can I import my existing deck, and if so, in what format?” |

**Words and phrasing to use:** create; build; deliver; together; your team; on-brand; stand out; win; full control; from first … to final …

**Avoid:** revolutionary synergy; enterprise-grade excellence; disruptive paradigm; frictionless magic; guaranteed success

**Rules:**

- Start with the work someone wants to accomplish, then name the mechanism that makes it possible.
- Explain AI through actual tasks and editable results, not a vague intelligence promise.
- Use numbers in proof and pricing only when the new product can substantiate them.
- Keep calls to action about the next real step rather than abstract discovery.
- Let testimonials sound like people; keep the surrounding marketing copy cleaner and shorter.

## Do's and Don'ts

### Do

- Keep the default opening display at 180px/0.8 with -0.04em tracking on desktop.
- Pair 18px monospace labels with 48px bold section leads and a close 8px gap.
- Use the 1224px container for normal content and the wider inset shell for the footer.
- Retain 24px gutters across bento panels and testimonial rows.
- Alternate white, lavender and purple surfaces instead of introducing a new color for every feature.
- Use 32px corners on oversized workflow or plan cards and 24px on regular feature panels.
- Make interface imagery communicate one selected task with a legible foreground control.
- Finish with the luminous horizon and white-directory/purple-conversion split.

### Don't

- Do not use a black-and-gray dark mode in place of the #280f62 purple environment.
- Do not make both adjacent actions identical pills; the 4px lime rectangle is an intentional contrast.
- Do not scatter lime across every heading or wash whole explanatory sections in it.
- Do not add conventional gray drop shadows to all cards; the strong glow belongs to the composer and staged media.
- Do not apply the 180px title treatment to pricing or story-index openings; their smaller variants support utility.
- Do not replace broad rounded media scenes with small outline-icon-only feature grids.
- Do not set catalog categories in bold; their 64px regular-weight contrast is part of the hierarchy.
- Do not flatten testimonial attribution into the bold quote; use the separate 14px reading-text caption.

## Motion and responsive

### Motion

**Observed:**

- Testimonial rows use ticker structures with horizontal translation; rows extend beyond the viewport. The category browser presents one bright active category and associated previews.
- Directory links declare purple hover text without underlining. No action or surface transition durations are established.

**Transfer:**

- Keep the proof wall readable in its resting state; if moved, preserve the two-row offset composition.
- Let catalog selection reveal corresponding previews without changing the overall dark-stage layout.

**Unknown:**

- Ticker speed, autoplay schedule, easing and scroll-trigger timing are not established.
- Button hover and focus-visible styling beyond the directory-link hover are not established.

### Responsive

**Observed:**

- Desktop composition is defined at 1440px. Width breakpoint declarations cluster around 810px and 1200px.

**Transfer:**

- On narrower screens, preserve the centered task-first opening while reducing the title enough to keep its tight line stack and the entire main control legible.
- Stack bento and split editorial columns, but retain the alternation of white, lavender and purple surfaces.
- Keep the quote wall's cropped-edge character through horizontal overflow rather than shrinking cards to unreadable widths.
- Stack the footer directory and conversion panel while retaining their contrasting materials and luminous purple surround.

**Unknown:**

- Exact mobile font sizes, navigation collapse behavior, side insets and reordering are not established; narrow-screen guidance is a design adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
