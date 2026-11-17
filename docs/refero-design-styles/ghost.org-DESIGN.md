# Ghost — independent ambition at scale

## Overview

A bold, product-led style with the confidence of an independent editorial business. Heavy grotesk headlines and expansive white space give way to deep navy demonstrations and charcoal proof sections, with acid lime reserved for decisive moments. Large interface scenes, colorful publication imagery and occasional serif testimonials make a substantial software product feel both capable and human.

### Essentials

- The opening makes a business-sized promise, not a slogan floating over decoration: a centered two-line 96px/1 headline at weight 700 with -0.025em tracking, a small yellow announcement above, and a near-edge-to-edge product stage below.
- The product is the spectacle: 1392px-wide desktop demonstrations with 16px corners, alternating with smaller layered interface illustrations. Include a dominant working-product scene; when no finished interface exists, construct a faithful example workflow rather than abstract stock art.
- Color behaves like chapter scenery: white is the default canvas, #e2e8f0 and #0f172a carry substantial capability chapters, and #15171a carries proof and the ending. Acid #d1ff19 occupies small labels, links and one decisive action rather than tinting the whole page; pink can back a single demonstration.
- Buttons look like software controls, not capsules: 6px corners for compact dark actions, 8px for the 62px-high closing action. The yellow announcement alone uses a full pill.
- Tiny chapter labels introduce very large practical statements: 12px/1 uppercase, weight 700, 0.1em tracking above 48px/1.15 bold headings and 24px/1.5 explanatory copy.
- Proof culminates in a typographic invitation: a charcoal field, 15px tracked lime label, 48px gray sentence with a white inline number, a white closing line and a lime action separated by about 63px. Retain this numeric-proof-to-personal-invitation device using a truthful metric or a concrete nonnumeric proof point.
- Ecosystem breadth becomes an arc of physical-looking app tiles: 96px squares with 24px corners, fine gray edges and varied soft shadows surrounding centered copy. Recreate the device with relevant tools or original capability symbols if external integrations are not applicable.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid lime | `#d1ff19` | `--color-lime` | accent, action, link | Chapter labels on dark, selected links and closing conversion action. |
| Announcement yellow | `#fec137` | `--color-yellow` | surface, accent | Small announcement above the opening promise. |
| Light lime | `#bef264` | `--color-learn-text` | text, link | Text on the deep olive secondary action. |
| Pink stage | `#f8b1e2` | `--color-pink-stage` | surface | Single large signup demonstration backing within a navy chapter. |
| Deep olive | `#1a2e05` | `--color-learn-fill` | surface | Subdued secondary action in charcoal proof rows. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate muted | `#64748b` | `--color-muted` | text, link | Eyebrows and subdued editorial links on white. |
| Footer slate | `#94a3b8` | `--color-footer-muted` | text, link | Footer links and secondary dark-section descriptions. |
| Slate body | `#334155` | `--color-body` | text, surface | Explanatory paragraphs on light sections; compact status backing. |
| Deep navy | `#0f172a` | `--color-navy` | background | Full-width capability chapters behind white text and product scenes. |
| Black | `#000000` | `--color-ink` | text, action | Primary headings and text on light surfaces; pricing actions. |
| Charcoal | `#15171a` | `--color-charcoal` | background, action | Proof bands, closing invitation, footer and compact dark buttons. |
| Forest ink | `#112220` | `--color-hero-ink` | text | Oversized opening headline. |
| Navigation gray | `#4d4d4d` | `--color-nav-muted` | text | Visible black at 70% opacity over the white header. |
| Gray secondary | `#6b7280` | `--color-secondary` | text | Secondary captions and institutional supporting statements. |
| Invitation gray | `#9ca3af` | `--color-closing-muted` | text | Large contextual proof sentence against charcoal. |
| Light slate | `#cbd5e1` | `--color-reverse-body` | text | Long supporting text on navy. |
| Tile edge | `#e5e5e5` | `--color-edge` | border | Fine outline on app tiles. |
| Blue gray field | `#e2e8f0` | `--color-chapter-gray` | background, border | Light capability chapter and pale panel outlines. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas, interface backing and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages and economic calculators | Commercial pink | `#ff247d` | `--color-rose` | action, accent, link | Range controls, comparison checks and closing accent instead of lime. |
| company pages | Institutional blue | `#60a5fa` | `--color-stat-blue` | text, accent | Standalone institutional adoption count. |
| economic calculators | Forecast violet | `#3b1f98` | `--color-purple-deep` | surface | Lower-right end of the economic calculator gradient. |
| economic calculators | Forecast purple | `#86279b` | `--color-purple-bright` | surface | Upper-left end of the economic calculator gradient. |
| company and explanatory pages | Reading gray | `#374151` | `--color-reading-ink` | text | Long-form institutional prose. |
| pricing pages | Comparison gray | `#4b5563` | `--color-comparison-text` | text | Feature names in dense comparison rows. |
| pricing pages | Control edge | `#d1d5db` | `--color-control-edge` | border, text | Selected billing-control outline. |
| pricing pages | Panel edge | `#e5e7eb` | `--color-panel-edge` | border | Inset outline on white pricing cards. |
| pricing pages | Pricing lower canvas | `#f3f4f6` | `--color-pricing-bottom` | background | Lower stop of the very subtle white-to-gray commercial page canvas. |
| audience-specific marketing pages | Customer field | `#f1f5f9` | `--color-customer-field` | background | Broad backing for white case-study cards. |

## Typography

- **InterVariable** — All marketing headings, prose, navigation, actions and figures. High-x-height variable grotesk, compact and emphatic at bold display sizes, open and readable in regular paragraphs. OpenType features: "calt", "cv10", "cv11", "liga", "ss01", "ss03". Font stack: "InterVariable", Inter, sans-serif.
- **Georgia** (only for testimonial-led audience pages) — Long standalone customer quotations. Familiar editorial serif, regular roman rather than decorative or italic. Font stack: "Georgia", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | InterVariable | 700 | 96px | 1 | -0.025em | Centered two-line opening promise. |
| proof-number | InterVariable | 700 | 72px | 1 | normal | Single large quantitative proof before customer rows. |
| heading-lg | InterVariable | 700 | 48px | 1.15 | -0.025em | Default capability heading and commercial-page headline. |
| heading-open | InterVariable | 700 | 48px | 1.15 | normal | Split-scene capability heading and white closing invitation. |
| manifesto | InterVariable | 700 | 48px | 1.35 | -0.025em | Large paragraph that explains the whole product after the first demonstration. |
| closing-context | InterVariable | 600 | 48px | 1.15 | normal | Gray contextual sentence interrupted by a bold white figure. |
| heading | InterVariable | 700 | 36px | 1 | -0.025em | Secondary capability statements beside compact illustrations. |
| body | InterVariable | 400 | 24px | 1.5 | normal | Primary explanatory paragraphs on white, gray or navy. |
| action | InterVariable | 600 | 20px | 1.5 | normal | Closing conversion action and prominent links. |
| navigation | InterVariable | 500 | 15px | 1.5 | normal | Header links and footer column headings. |
| secondary-action | InterVariable | 600 | 15px | 1.5 | normal | Subdued learn-more actions in proof rows. |
| footer-link | InterVariable | 400 | 15px | 1.25 | normal | Footer destination links. |
| closing-label | InterVariable | 600 | 15px | 1 | 0.1em, uppercase | Label above the concluding proof sentence. |
| compact-action | InterVariable | 600 | 14px | 1.5 | normal | Compact main button text and announcement text. |
| eyebrow | InterVariable | 700 | 12px | 1 | 0.1em, uppercase | Capability chapter labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | institutional-number | InterVariable | 400 | 60px | 1 | normal | Blue adoption statistic within a prose opening. |
| company transparency sections | chart-number | InterVariable | 600 | 55px | 1.15 | normal | Headline financial figure over the large line chart. |
| audience-specific marketing pages | audience-display | InterVariable | 700 | 45px | 0.9 | normal | Wide single-line heading above a portrait-led audience opening. |
| testimonial-led audience pages | testimonial | Georgia | 400 | 36px | 1.5 | normal | Centered long quotation on white. |
| company transparency sections | metric-number | InterVariable | 600 | 32px | 1.15 | normal | Supporting metric cards beneath the chart. |
| company and audience-specific pages | editorial-body | InterVariable | 400 | 20px | 1.5 | normal | Company narrative and testimonial attribution. |
| pricing pages | comparison | InterVariable | 500 | 14px | 1.5 | normal | Pricing feature lists, billing choices and comparison values. |
| pricing pages | plan-label | InterVariable | 600 | 14px | 1.5 | 0.025em, uppercase | Short uppercase plan names. |

**Notes:**

- Use the tight -0.025em tracking for the monumental opening, general chapter headings and bold explanatory paragraph; preserve normal tracking on the closing invitation and its contextual sentence.
- Body copy is deliberately large relative to software controls: 24px explanatory copy versus 14–15px navigation, buttons and comparison details.
- Short italic emphasis can appear inside a bold capability heading without changing its family or scale. Do not apply italics across the whole heading.
- The first promise and its product stage supply the opening explanation; a separate supporting paragraph and large hero conversion button are not part of the default opening.

## Layout

**Density:** Airy in the marketing narrative, with large product stages and long chapter pauses; deliberately compact in navigation and commercial comparisons.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact action vertical padding and footer link padding. |
| 12px | Announcement-to-headline gap. |
| 16px | Compact action horizontal padding and tight heading introduction. |
| 24px | Standard paragraph separation, desktop side gutters and chapter-heading support gap. |
| 32px | Customer-card and pricing-card grid gaps. |
| 36px | Twelve-column chapter gaps and footer-column gaps. |
| 40px | Proof-row heading-to-card spacing. |
| 48px | Spacing between app-tile columns and commercial-page groups. |
| 54px | Illustration-to-copy grid gap and company-page side padding. |
| 72px | Core capability-band vertical padding and split-scene breathing room. |
| 80px | Major illustration-row and proof-row separation. |
| 99px | Top padding before the oversized explanatory paragraph. |
| 108px | Bottom padding after the oversized explanatory paragraph. |
| 126px | Closing invitation top and bottom padding. |
| 144px | Opening headline group separation below the header. |

### Containers and grids

- **marketing-container**: max width 1400px · side padding 24px. Centered desktop content rail; at 1440px the inner scene is 1392px wide.
- **chapter-grid**: 12 columns · gap 36px. Main capability composition, with copy around five columns and the product around seven; media can continue beyond the outer edge.
- **illustration-grid**: 12 columns · gap 54px. Compact illustration beside explanatory copy, vertically centered; alternate sides between adjacent feature rows.
- **customer-row**: 4 columns · gap 32px. Four image-led customer examples beneath a category header on charcoal.
- **footer-columns**: 5 columns · gap 36px. Five destination groups below a brand/navigation row.
- **audience-cards** (only for audience-specific marketing pages): 3 columns · gap 32px · side padding 36px. Three-column white case-study cards on pale slate.
- **pricing-grid** (only for pricing pages): 4 columns · gap 32px · side padding 36px. Four equal-width summary plans; comparison sections use a fifth column for row labels.
- **reading-column** (only for company pages): max width 734px · side padding 54px. Narrow centered, left-aligned institutional narrative, contrasted with wide photographs and data.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact-actions | 6px |
|  | closing-action | 8px |
|  | product-stage | 16px |
|  | app-tiles | 24px |
|  | announcement | 9999px (pill) |
| pricing pages | pricing-cards | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | soft-panel | `0px 0px 1px 0px rgba(0,0,0,0.1), 0px 2px 6px 0px rgba(0,0,0,0.03)` | White product panels and compact dark actions. |
|  | tile-lift | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Raised app tiles; nearby tiles use shallower shadows to vary apparent height. |
| pricing pages | plan-lift | `inset 0px 0px 0px 1px #e5e7eb, 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | White summary plans on a near-white canvas. |

### Surfaces

#### White canvas · level 0

**Use:** Default narrative background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Broad uninterrupted fields; most narrative content is not boxed.

**Transfer:** Let the product scene and typography provide structure before adding cards.

#### Navy chapter · level 0

**Use:** Major capability demonstration.

**CSS:** `background: #0f172a; color: #ffffff; padding: 72px 24px; overflow: hidden`

**Observed:** White bold headings, light-slate paragraphs and lime labels; large interface objects carry the color and detail.

**Transfer:** Use a full-bleed chapter, not a dark card floating in an otherwise identical section.

#### Slate chapter · level 0

**Use:** Light capability chapter with white product panels.

**CSS:** `background: #e2e8f0; padding: 72px 24px; overflow: hidden`

**Observed:** The same background joins a heading, a full-width interface and paired feature illustrations into one extended chapter.

**Transfer:** Group related demonstrations within one material field.

#### Charcoal proof · level 0

**Use:** Quantitative proof, customer examples and continuous closing/footer field.

**CSS:** `background: #15171a; color: #ffffff`

**Observed:** More neutral than the navy capability field, with muted gray supporting text.

**Transfer:** Give proof and conversion a shared dark foundation.

#### White product panel · level 1

**Use:** Large editor or management demonstration.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 0px 1px 0px rgba(0,0,0,0.1), 0px 2px 6px 0px rgba(0,0,0,0.03)`

**Observed:** Almost container-wide, with subtle edges rather than conspicuous browser chrome.

**Transfer:** Render a readable, coherent interface scene rather than many miniature generic windows.

#### Pink demonstration stage · level 1

**Use:** Contrasting backing for a centered white workflow panel.

**CSS:** `background: #f8b1e2; border-radius: 16px; overflow: hidden`

**Observed:** A nearly square large panel in the wider half of a navy split section; soft tonal light surrounds the white panel.

**Transfer:** Use a restrained pink field and gentle translucent light around one concrete product task; exact light stops are not essential.

#### Pricing canvas · level 0

**Only for:** pricing pages

**Use:** Summary cards and extensive comparison tables.

**CSS:** `background: linear-gradient(#ffffff, #f3f4f6)`

**Observed:** Extremely subtle tonal change over the full commercial narrative.

**Transfer:** Keep the background lower contrast than the raised white plan columns.

#### Forecast field · level 1

**Only for:** economic calculators

**Use:** Interactive value or revenue estimate.

**CSS:** `background: linear-gradient(to left top, #3b1f98, #86279b); border-radius: 16px; overflow: hidden`

**Observed:** White illustrative subscription cards stagger on the left; white explanatory copy, pink sliders and a large result occupy the right.

**Transfer:** Reserve this vivid gradient for a meaningful economic interaction rather than general feature cards.

## Components

### Header navigation

**Use:** Slim opening navigation on white.

**CSS:** `display: flex; align-items: center; max-width: 1400px; padding: 27px 0px; color: rgba(0,0,0,0.7)`

**Text style:** `navigation` — InterVariable 500 · 15px/1.5

**Observed:** Brand at the left, navigation after a 40px interval, account link and Compact dark action at the far right. Dropdown chevrons are small filled shapes in 20px boxes.

**States:** Declared: hover text becomes rgba(0,0,0,0.9).

**Transfer:** Keep the menu secondary to the promise; use a small number of plainly named destinations.

### Compact dark action

**Use:** Persistent header conversion action.

**CSS:** `background: #15171a; color: #ffffff; border: 1px solid transparent; border-radius: 6px; padding: 8px 16px; box-shadow: 0px 0px 1px 0px rgba(0,0,0,0.1), 0px 2px 6px 0px rgba(0,0,0,0.03)`

**Text style:** `compact-action` — InterVariable 600 · 14px/1.5

**Observed:** The verb is semibold; the appended free qualifier is regular 14px/21px. The control is 39px high.

### Announcement pill

**Use:** Small news hook above the opening headline.

**CSS:** `background: #fec137; border-radius: 9999px; padding: 8px 3px; display: inline-block`

**Text style:** `compact-action` — InterVariable 600 · 14px/1.5

**Observed:** Text sits in an inner span with 20px horizontal padding. This is a compact linked badge, not the main conversion button.

### Closing action

**Use:** Decisive action in the charcoal invitation.

**CSS:** `background: #d1ff19; color: #000000; border-radius: 8px; padding: 16px 24px`

**Text style:** `action` — InterVariable 600 · 20px/1.5

**Observed:** A trailing arrow continues the label. The control is 62px high and sits on its own below the large closing line. The commercial variant uses pink with white text.

**Transfer:** Use lime as the default; reserve the pink variant for commercial decision pages.

### Proof row action

**Use:** Subdued secondary destination beside customer-category headings.

**CSS:** `background: #1a2e05; color: #bef264; border-radius: 8px; padding: 8px 16px`

**Text style:** `secondary-action` — InterVariable 600 · 15px/1.5

**Observed:** Right-aligned to the category row rather than repeated over every customer image.

**States:** Declared: hover background becomes rgb(163 230 53/1) and text becomes rgb(0 0 0/1).

### App tile

**Use:** Physical-looking ecosystem symbols around centered explanatory copy.

**CSS:** `width: 96px; height: 96px; display: flex; align-items: center; justify-content: center; border: 1px solid #e5e5e5; border-radius: 24px; overflow: hidden; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Observed:** Each contains a single colorful symbol or tool mark. Tiles occupy staggered columns with 48px gaps; a central opening leaves room for copy.

**Transfer:** Keep the curved arrangement and dimensional shadows even when replacing tool marks with original functional symbols.

### Footer link

**Use:** Destination links within five footer columns.

**CSS:** `display: block; color: #94a3b8; padding: 8px 0px`

**Text style:** `footer-link` — InterVariable 400 · 15px/1.25

**Observed:** Column labels are brighter and medium-weight. The footer begins with a brand/navigation row and ends with small credibility marks, status and legal links.

**States:** Declared: hover text becomes rgb(255 255 255/1).

### Plan card

**Only for:** pricing pages

**Use:** Equal-weight plan summaries.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 24px 0px 32px; display: flex; flex-direction: column; box-shadow: inset 0px 0px 0px 1px #e5e7eb, 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Text style:** `comparison` — InterVariable 500 · 14px/1.5

**Observed:** Uppercase plan name, one-line audience description, large bold price with lighter currency mark, short checkmarked feature list, black full-width inset action pinned to the bottom. Four equal cards; none is inflated into an oversized recommended plan.

### Billing choice

**Only for:** pricing pages

**Use:** Compact monthly/yearly selection beside audience-size controls.

**CSS:** `background: #ffffff; color: #000000; border: 1px solid #d1d5db; border-radius: 6px; padding: 8px 12px; box-shadow: 0px 0px 1px 0px rgba(0,0,0,0.1), 0px 2px 6px 0px rgba(0,0,0,0.03)`

**Text style:** `comparison` — InterVariable 500 · 14px/1.5

**Observed:** Selected control has a white surface and thin outline; inactive choice is unfilled with muted text. The audience control is separate, using a pink track and value bubble.

### Comparison row

**Only for:** pricing pages

**Use:** Dense but orderly detailed plan comparison.

**CSS:** `display: flex; align-items: center; gap: 32px; border-top: 1px solid rgba(0,0,0,0.05)`

**Text style:** `comparison` — InterVariable 500 · 14px/1.5

**Observed:** Feature label is left-aligned; four centered plan values sit over softly raised white columns. Rows are about 47px high, with 12px vertical label padding. Pink checks indicate availability; gray dashes indicate absence.

## Imagery and graphics

### Working product theater

**Use:** Opening stage and major capability demonstrations.

**Observed:** A very large straight-on dashboard opens in dark mode, with a sidebar, metric strip and fine magenta line chart. Later white editor and membership scenes fill the same broad rail. Corners are rounded without a heavy device bezel; interfaces remain visually coherent and text-like, not abstract geometry.

**Transfer:** Show the new product doing a recognizable job in one dominant frame. If no interface exists, design a plausible task-specific mockup with real content, consistent navigation and one useful result. Keep the dark opening/light secondary demonstration contrast.

### Layered feature vignettes

**Use:** Secondary benefits beside 36px headings.

**Observed:** Small white UI fragments overlap on the section background: media cards, email previews, charts and promotional forms. A single rotated photo or foreground cursor adds depth; most surfaces remain straight-on. Muted gray backing and soft shadows keep colorful chart lines or imagery legible.

**Transfer:** Reduce each capability to two or three task-specific fragments; preserve plenty of empty space around the illustration.

**Build:** Use a 549px square SVG or positioned HTML stage. Layer two or three white panels with 8–16px corners and low-opacity black shadows; offset them by 20–60px. Place one relevant content image or a simple line chart in the foremost panel, and one small dark pointer or action chip near its edge. Reuse the surrounding chapter color rather than drawing an enclosing frame.

### Publication mosaic

**Use:** Transition within a dark capability chapter.

**Observed:** Five staggered columns of colorful website thumbnails sit on navy, with 16px gutters and independently varied vertical positions. Different typography, photography and color systems demonstrate output diversity while the shared tile alignment keeps order.

**Transfer:** Use varied, credible examples of outputs made with the new product. Preserve five-column density and stagger, rather than displaying the same template repeatedly.

### Ecosystem arc

**Use:** Signature compatibility or capability-breadth section.

**Observed:** Bright app symbols form a loose arch around a centered headline, paragraph and link. Their white or colored rounded-square bodies appear at different heights, with soft shadows suggesting floating weight.

**Transfer:** Keep this surrounding-symbol device on new landing pages. Without partner marks, use original symbols for compatible workflows or capabilities.

**Build:** Arrange App tile instances in a horizontal flex row with 48px gaps. Stagger column offsets through 0px, 40px, 80px and 120px, mirroring the rise around the center. Add a second lower tile only on outer columns; clip the oversized composition at the page edges. Leave a central white area roughly 672px wide for copy. Vary shadow depth rather than tile size.

### Customer image strips

**Use:** Social proof on charcoal and pale card grids.

**Observed:** Landscape photographs or publication artwork contain a strong customer identity; bright and muted examples coexist. Dark proof rows use 324px by 201px images with small name/category captions below, not prose-heavy cards. Audience-specific white cards add a paragraph and destination row.

**Transfer:** Use authentic examples in their own visual language. Keep image treatment consistent in ratio and framing, not by forcing every example through a monochrome filter.

### Human company photography

**Only for:** company and recruiting pages

**Use:** Wide narrative relief between narrow prose sections.

**Observed:** Natural-color candid travel and team photographs form edge-aligned mosaics, including double-width images among single-width cells. Separate portrait rosters use small square photos, compact names, roles and dates. A very pale world map with sparse outlined location pins complements the people.

**Transfer:** Use real working or social moments and simple grid joins. Keep the varied landscape mosaic distinct from the orderly portrait roster; avoid staged studio sameness.

### Transparency data

**Only for:** company transparency sections

**Use:** Quantified institutional proof.

**Observed:** A charcoal full-width line chart with a blue line, small data dots and translucent area fill is followed by six subtle metric cards. A white headline figure sits over the chart, with much lighter currency styling than the digits.

**Transfer:** Use truthful operational data with an explanatory heading. The chart should be legible, not decorative noise.

**Build:** Draw an SVG polyline from real data over a fine low-contrast grid, add small circles at sample points, and close the path into a translucent blue-to-transparent area. Place a 55px semibold headline metric over the quieter left part; follow with six equally sized dark metric panels using an inset rgba(255,255,255,0.05) outline.

### Circular explanatory model

**Only for:** company explanatory pages

**Use:** Explain a self-reinforcing process between prose and institutional proof.

**Observed:** Pale blue concentric rings surround a stronger central orbit. Four black line icons sit at cardinal points, with short centered explanations in the quadrants and a blue cyclic-arrow symbol at the center.

**Transfer:** Use this treatment only for a genuine circular relationship; substitute the product's real actors or stages.

**Build:** Use concentric circles of 350px, 600px, 850px, 1100px, 1350px and 1600px diameter, centered in a 750px-high clipped pale blue-white band. Give outer rings thin blue strokes with progressively lower alpha. Place four small black line icons on white circular backings along the central orbit, add a few blue dots, and extend a thin blue vertical connector beyond the orbit.

### Icons

**Observed:** Navigation chevrons use filled shapes in 20px boxes. Comparison helper icons are 16px with gray 2px round strokes; pricing availability checks are pink. Arrows in marketing actions are simple inline right arrows. Company process graphics use black outline symbols rather than glossy illustrations.

**Transfer:** Use compact functional symbols and arrows. Confine colorful boxed app symbols to the ecosystem device rather than turning every feature label into an icon badge.

## Section recipes

How recurring sections are built.

### First screen: Promise and product stage

**Observed:** White canvas, slim Header navigation, then a large blank interval of 144px before a centered Announcement pill. A two-line dark forest headline follows after 12px, occupying roughly the central 810px at 96px/1 with tightly packed bold letters. Below another 72px pause, a dark working-product scene spans the page within 24px side gutters, with 16px top corners. In the first 900px, the header, announcement, entire promise and upper 347px of the dashboard are visible. No support paragraph sits in this opening; detailed explanation and the rest of the interface continue below the fold. The only conversion control above the fold is the compact header action; the announcement is a news link.

**Transfer:** Default new landing pages use this promise-over-working-product composition. Construct a credible workflow scene if finished product media is unavailable. Audience-specific pages instead use a 45px left-aligned headline above a narrow copy/action/quote rail and a dominant portrait. Pricing opens with a centered 48px heading, reassurance, controls and four plans; company narratives open as a narrow left-aligned 48px heading and prose column.

**Avoid:** Do not replace the dashboard with a generic floating laptop, put paragraphs and multiple giant buttons between the promise and product, or stretch the headline into a full-width single line.

**Text style:** `display` — InterVariable 700 · 96px/1 · tracking -0.025em

### Oversized product explanation

**Observed:** White canvas with 99px top and 108px bottom padding. A bold 48px/1.35 paragraph spans up to 1152px, followed after 36px by an unusually prominent muted text action.

**Transfer:** Explain what the product enables in complete plain sentences after the visual first impression. Keep this as an editorial statement, not another hero.

**Text style:** `manifesto` — InterVariable 700 · 48px/1.35 · tracking -0.025em

### Capability chapter

**Observed:** Navy chapter or Slate chapter joins an Eyebrow, a 48px heading, 24px supporting copy and a large White product panel. Split variants use five columns of copy and seven of media, vertically centered; a media-first variant uses the Pink demonstration stage. Supporting paragraphs and links have 24px separations.

**Transfer:** Give one chapter a coherent field and a concrete task. Let important UI exceed the copy in area rather than squeezing both into equal small cards.

**Text style:** `heading-lg` — InterVariable 700 · 48px/1.15 · tracking -0.025em

### Alternating feature pair

**Observed:** Two broad illustration-and-copy rows use the illustration-grid, 549px-square Layered feature vignettes and 36px headings above 24px body text. The image swaps sides in the following row; no individual card encloses each pair.

**Transfer:** Pair related secondary capabilities and vary visual direction while retaining one shared chapter background.

**Text style:** `heading` — InterVariable 700 · 36px/1 · tracking -0.025em

### Ecosystem breadth

**Observed:** Ecosystem arc wraps around centered copy on White canvas. A small uppercase label introduces a 36px heading, a roughly 672px-wide paragraph and muted arrow link. The arc is visually larger than the copy but leaves it unobstructed.

**Transfer:** Demonstrate breadth with real compatibility, output formats or original workflow symbols. Keep the arc as the visual signature rather than reducing it to a conventional logo strip.

### Quantified customer proof

**Observed:** Charcoal proof begins with a centered 72px figure and short supporting line. Customer rows follow at 80px intervals: category heading left, two-line purpose statement in the middle, Proof row action at right, then four landscape images after 40px. Thin dark rules separate rows.

**Transfer:** Choose a credible aggregate proof point and show several distinct kinds of users or outcomes. The content categories should reflect the new product rather than the original business.

**Text style:** `proof-number` — InterVariable 700 · 72px/1

### Proof invitation and full footer

**Observed:** Charcoal proof continues uninterrupted through the ending. A centered closing-label, gray 48px context sentence with a white bold inline figure, and white 48px invitation sit in a roughly 780px reading area with 24px vertical gaps. Closing action appears about 63px below the final line. The invitation has 126px top and bottom padding. A full footer follows: brand and short navigation row, five link columns with 36px gaps, then small credibility marks at left and legal/contact links at right. Pricing uses rose for the label, action and highlighted footer destination; other variants use lime.

**Transfer:** Turn truthful recent momentum into an invitation to the reader, then finish with useful navigation and compact trust details. Keep the shared dark field and the gray-to-white hierarchy even if proof is qualitative.

**Text style:** `closing-context` — InterVariable 600 · 48px/1.15

### Editorial testimonial pause

**Only for:** testimonial-led audience pages

**Observed:** White full-width band with 72px vertical padding. A centered Georgia 36px/1.5 quotation occupies an 896–1024px column; a 20px sans attribution follows about 35px below, with the cited publication underlined.

**Transfer:** Use a substantive customer statement as a calm typographic pause between colorful demonstrations and case-study grids.

**Text style:** `testimonial` — Georgia 400 · 36px/1.5

### Commercial comparison

**Only for:** pricing pages

**Observed:** Centered title and reassurance lead to audience-size control and Billing choice, then four Plan cards separated by 32px. A long grouped comparison follows with one label column and four plan columns. Category headings interrupt the 47px rows; white raised column backings and very faint horizontal rules prevent the table becoming a harsh spreadsheet.

**Transfer:** Let readers compare stable dimensions across equal plans. Keep a uniform black action in each summary card; pink belongs to checkmarks, controls and commercial accents.

**Text style:** `comparison` — InterVariable 500 · 14px/1.5

### Institutional narrative and proof

**Only for:** company pages

**Observed:** A roughly 734px prose column opens with a 48px heading and 20px body text; a centered blue 60px count punctuates the explanation. Broad candid photo mosaics, a charcoal chart, the circular process model, a roster and pale map break out of this narrow rail. Benefits use a three-column grid and a centered dark recruiting action.

**Transfer:** Alternate readable editorial passages with tangible evidence of the organization, using people and process rather than filling every section with product mockups.

## Page flow

**Storyline:** promise → tangible demonstration → explanation → capability chapters → credible outcomes → direct invitation → useful navigation

### General product marketing and conversion

1. **Promise** — Oversized centered outcome headline over a dark working-product stage.
2. **Explanation** — Large bold editorial paragraph states what the product does.
3. **Capability chapters** — Dark and pale chapters alternate full-width interface scenes, output mosaics and paired illustrations.
4. **Social proof** — Ecosystem arc, aggregate metric and image-led customer-category rows.
5. **Confidence** — Short independent-minded positioning statement and another substantive product view.
6. **Closing call** — Numeric proof becomes a personal invitation, followed by the continuous dark footer.

**Transfer:** Borrow the shifts in visual scale and chapter material; choose only the capability chapters needed to make the new product's case.

### Audience-specific persuasion through people, examples and economics

1. **Audience promise** — Headline above a portrait-led opening with copy, action and short testimonial in a narrow left rail.
2. **Product demonstration** — Large dark annotated workflow followed by colorful capability panels.
3. **Social proof** — Three-column white customer cards on pale slate alternate with serif quotation bands.
4. **Value proof** — Violet calculator stages illustrative cards beside input sliders and an annual result.
5. **Closing call** — Shared lime-accented proof invitation and full charcoal footer.

**Transfer:** Use the audience's real people and outputs to personalize the system; keep calculator treatment scoped to a meaningful economic model.

### Help readers choose and compare plans

1. **Decision framing** — Centered heading, short reassurance, audience-size slider and billing choices.
2. **Pricing** — Four equally sized white summary cards with black actions.
3. **Detailed comparison** — Long category-based tables with softly raised white value columns and pink checks.
4. **Closing call** — Shared charcoal invitation with pink instead of lime, followed by full footer navigation.

**Transfer:** Preserve equal plan treatment and the separation between short summary and detailed comparison; do not import long storytelling chapters into the decision area.

### Explain the organization and make its people and operating model credible

1. **Identity** — Narrow headline and prose, blue adoption statistic and candid photo mosaic.
2. **Quantified proof** — Wide charcoal financial chart and compact supporting metrics.
3. **Operating model** — Pale concentric-ring process diagram followed by readable explanation.
4. **Human proof** — Portrait roster, pale location map, benefits and recruiting action.
5. **Community proof** — More candid mosaic photography and contributor roster with participation action.
6. **Closing call** — Shared lime invitation and complete charcoal footer.

**Transfer:** Tell the new organization's real story through narrow prose and wide evidence; portraits, diagrams and recruiting material belong only where they serve that purpose.

## Writing

Confident, practical and openly independent. Product capability is described with concrete verbs and occasional conversational wit; supporting detail earns the ambitious headlines.

**Do not copy:** Do not reuse the Ghost name, logo, publication identities, customer artwork, quotations, organizational claims, adoption counts, revenue figures or trial terms. Source examples illustrate language patterns only; all factual claims and proof must belong to the new product.

- **Addressing the reader:** Speak directly to you and your work. The product is named as the capable helper; we appears naturally in institutional explanations, without corporate distancing.
- **Rhythm:** Short outcome-led headings often end with a period. Supporting copy runs as two or three plain sentences, with brief standalone punchlines after detail. Actions are simple verbs with a trailing arrow rather than promotional slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Turn an existing asset or effort into a valuable outcome. | 6–10 words | “Turn your audience into a business.” |
| Capability heading | Name the practical job in a short declarative sentence. | 3–8 words | “Publish by web & email newsletter.”<br>“Manage your memberships.” |
| Reassurance | State the constraint removed and the reader's retained control. | One short sentence | “No payment fees — upgrade, downgrade, or cancel anytime.” |
| Conversational emphasis | A brief human phrase breaks up the operational detail. | 2–5 words | “Hello, new friends.”<br>“Today, it's your turn.” |
| Action | A direct verb, immediate task and optional right arrow. | 2–5 words | “Start publishing now →”<br>“Explore [Brand] themes →” |
| Institutional proof | A plain statement invites scrutiny rather than vague prestige. | One concise sentence | “Yes, this is a live feed of our real data.” |

**Words and phrasing to use:** your; build; create; grow; control; independent; custom; native; built-in; front and center

**Avoid:** synergy; revolutionary ecosystem; unlock limitless possibilities; game-changing; best-in-class solutions; frictionless journey

**Rules:**

- Lead with what the reader can do, then explain the underlying capability.
- Use specific task nouns rather than abstract productivity language.
- Use numbers only with a clear time frame or context.
- Put a concrete proof point before the final personal invitation.
- Keep wit brief and occasional; bluntness is emphasis, not the default tone of every paragraph.

## Do's and Don'ts

### Do

- Keep the default opening at 96px/1, weight 700 and -0.025em tracking on desktop.
- Let product stages reach the 24px desktop gutters instead of constraining them to the prose width.
- Use 12px uppercase chapter labels with 0.1em tracking to introduce 48px capability headings.
- Carry 24px/1.5 body copy through capability sections, changing text color for the field rather than shrinking it.
- Preserve the distinction between navy capability chapters and neutral charcoal proof/closing sections.
- Use 16px media corners, 24px app-tile corners and 6–8px action corners according to role.
- Keep four customer images on a 32px-gap rail and allow their original colors to provide variety.
- End with the gray-context/white-proof invitation and a complete five-column desktop footer.

### Don't

- Do not turn every narrative paragraph into a bordered card; broad white and chapter fields are the primary structure.
- Do not use lime as a page-wide wash or as the default paragraph color; it is a small-area signal.
- Do not replace the 6px compact software-button shape with a full pill; pills belong to announcements and small badges.
- Do not use a generic blue gradient for every product chapter; the default chapter fields are solid navy and slate.
- Do not reduce the 96px ecosystem tiles to tiny inline partner logos; their rounded physical presence is characteristic.
- Do not force customer photography into uniform grayscale when surrounding UI scenes are colorful.
- Do not make one pricing plan enormous or brightly filled; equal white summaries and black actions establish the comparison.
- Do not use Georgia for default marketing headlines or body text; it is a testimonial-specific editorial contrast.

## Motion and responsive

### Motion

**Observed:**

- Announcement pill declares all-property transitions of 0.3s with cubic-bezier(0.4,0,0.2,1).
- Proof row actions declare a lime-brighter background and black text on hover; footer links turn white.
- Circular company graphics declare infinite linear spin animations with durations ranging from 10s to 90s.

**Transfer:**

- Keep motion associated with the existing objects: a subtle announcement treatment and slow cyclical movement in a circular explanatory model, not an animated entrance on every text block.

**Unknown:**

- Scroll-animation choreography and most timing-to-element relationships are not established.
- Focus-visible and pressed-state appearances are not established.

### Responsive

**Observed:**

- Desktop navigation is declared as hidden below the large-layout variant.
- Capability layouts declare single-column or full-span content at smaller widths before adopting the desktop twelve-column composition.
- Large product-stage radius variants progress through 8px, 12px and 16px.
- Footer destination grids declare three-, four- and five-column variants and are hidden at the smallest variant.

**Transfer:**

- On narrow screens, preserve promise first and a substantial product demonstration immediately afterward; stack split chapters rather than shrinking desktop copy and media side by side.
- Keep the ecosystem arc as a clipped composition around readable center copy, reducing its visual scale before removing tile detail.
- Keep company prose narrow and let photo mosaics simplify independently of the main narrative column.

**Unknown:**

- Exact mobile headline sizes, menu behavior and commercial-table overflow behavior are not established.
- No verified viewport-relative typography formula is available.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
