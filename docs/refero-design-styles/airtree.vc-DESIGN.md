# Airtree — paper, people, orange seeds

## Overview

An optimistic editorial style with a pale butter-paper ground, forest-charcoal ink and small bursts of hot orange and acid yellow. Narrow, expressive serif statements sit alongside matter-of-fact Swiss grotesk text, with candid photography doing much of the storytelling. It suits relationship-led technology products and institutions: spacious in its promises, compact in its directories, and warmly human rather than futuristic.

### Essentials

- A sentence, not a billboard slogan, carries the opening: regular Prody serif at 42.1px/1.15, centered across a 1014px measure, surrounded by blue-to-paper atmosphere and scattered orange organic dots.
- Navigation behaves like a tiny index: two stacked columns of 14px/1 grotesk links, each preceded by a 9px hollow circle, with a small outlined contact button at the far right.
- Actions feel like fine stationery rather than oversized pills: 0.5px outlines, 8.4px corners and 12.9px Book labels; acid yellow is reserved for conversion details and hover fills.
- Color punctuates rather than paints the whole site: butter paper dominates, charcoal closes the page, orange lives in loose seed-like graphics, and pastel panels are confined to testimonial collections.
- Real people are the main visual proof: large edge-to-edge documentary photographs in rounded frames, narrow 9.4px gutters and bottom-aligned captions; use authentic working scenes when no dedicated product imagery exists.
- Scale changes create the punctuation: 131px serif proof numbers, ruled section starts, an orange organic emblem in open space, and a monumental pale wordmark across the dark ending. Carry these devices into new content using a simple original dot-and-line emblem and the new product’s own name.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hot orange | `#fb5e00` | `--color-orange` | accent, action, link | Organic dots and line illustrations, occasional small emphasis; filled actions belong to application-led campaigns. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#ffff48` | `--color-yellow` | action, accent | Subscribe and participation actions, outlined-button hover fill and small graphic punctuation. |
| Powder sky | `#c1d1df` | `--color-sky` | background, surface | Opening atmospheric fade; also the blue testimonial panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Photo shade | `#000000` | `--color-black` | surface | Transparent-to-black photographic scrims at 50% layer opacity. |
| Forest charcoal | `#262d29` | `--color-ink` | text, background, surface, border | Main text, section rules, media backing and closing band. |
| Pale olive ink | `#a3a699` | `--color-footer-muted` | text | Cream text at 60% opacity over charcoal for footer descriptions and links. |
| Butter paper | `#f7f6e3` | `--color-canvas` | background, text, border | Default canvas, reversed text and pale outlines on dark surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| testimonial collections | Pastel peach | `#ffccb5` | `--color-peach` | surface | Alternating testimonial panel. |
| testimonial collections | Pastel sage | `#bbd4b7` | `--color-sage` | surface | Alternating testimonial panel. |
| application-led campaigns | Soft olive gray | `#6f736a` | `--color-muted` | text | Ink at 65% alpha over butter paper, used for campaign eyebrows and expanded answers. |
| application-led campaigns | Faint paper edge | `#dadac9` | `--color-rule` | border | Ink at 14% alpha over paper; accordion and information separators. |
| application-led campaigns | Action white | `#ffffff` | `--color-white` | text | Text on orange application buttons. |

## Typography

- **Suisseintl** — Body, navigation, card titles and labels; Book is the lighter text cut used for lead copy and small metadata. Clear Swiss grotesk with unforced proportions and a neutral, conversational regular weight. If unavailable, use **Inter**. Use 400 for regular and Book roles, 500–600 only for compact labels. Font stack: "Suisseintl", "Inter", Arial, sans-serif.
- **Prody** — Opening statement, large proof numerals and selected editorial headings. Narrow, lively serif with pointed details and a literary rather than luxurious character, despite its generic sans-serif fallback. If unavailable, use **Instrument Serif**. Use regular roman; tune measure to preserve the long-line, condensed editorial feel. Font stack: "Prody", "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| stat | Prody | 400 | 131px | 1 | normal | size 9.1vw | Unboxed proof numerals with small labels below. |
| display | Prody | 400 | 42.1px | 1.15 | normal | size 2.925vw | Centered opening promise; also serif directory headings and photo-hero statements. |
| heading | Suisseintl | 400 | 42.1px | 1.15 | normal | size 2.925vw | Primary content-section headings. |
| card-heading | Suisseintl | 400 | 32.8px | 1.15 | normal | size 2.275vw | Editorial titles over large photographs. |
| lead | Suisseintl | 400 | 28.1px | 1.15 | normal | size 1.95vw | Book-cut section introductions and smaller ruled section headings. |
| body | Suisseintl | 400 | 18.7px | 1.15 | normal | size 1.3vw | Supporting descriptions, links and footer copy. |
| label | Suisseintl | 600 | 14px | 1 | normal | size 0.975vw | Names and filter titles in repeated collections. |
| nav | Suisseintl | 400 | 14px | 1 | normal | size 0.975vw | Compact index navigation. |
| footer-label | Suisseintl | 600 | 14px | 1 | normal, uppercase | size 0.975vw | Footer column headings. |
| caption | Suisseintl | 400 | 12.9px | 1 | normal | size 0.89375vw | Book-cut compact actions, category tags and portrait roles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| application-led campaigns | campaign-heading | Prody | 400 | 37px | 1.05 | -0.01em | size clamp(26px, 3vw, 37px) | Editorial FAQ heading. |
| application-led campaigns | campaign-subhead | Prody | 400 | 26px | 1.4 | normal | size clamp(20px, 2vw, 26px) | Centered sentence beneath an abstract campaign illustration. |
| testimonial collections | quote-body | Suisseintl | 400 | 18.7px | 1.25 | normal | size 1.3vw | Longer quotations and prose within pastel testimonial panels. |
| application-led campaigns | campaign-body | Suisseintl | 400 | 18px | 1.25 | normal | fixed | Long-form manifesto paragraphs. |
| application-led campaigns | campaign-action | Suisseintl | 500 | 17px | 1 | normal | fixed | Orange filled application action. |
| application-led campaigns | faq-question | Suisseintl | 500 | 17px | 1.4 | normal | fixed | Accordion question text. |
| application-led campaigns | faq-answer | Suisseintl | 400 | 17px | 1.65 | normal | fixed | Muted expanded answer text. |
| people and customer directories | compact-body | Suisseintl | 400 | 12.9px | 1.35 | normal | size 0.89375vw | Book-cut directory descriptions and compact directory introductions. |
| application-led campaigns | campaign-eyebrow | Suisseintl | 500 | 12px | 1.25 | 0.1em, uppercase | fixed | Small muted chapter labels above long-form text or FAQ headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Most type is regular and normally tracked. Contrast comes from serif versus grotesk and changes of scale, not heavy display weights or compressed tracking.
- Keep Book-cut lead text and small captions visually lighter than semibold names; the regular and Book declarations belong to one sans family.
- Serif text inside photo heroes is left aligned; the default opening and isolated closing quotation are centered. The latter should have the visual size and line count of the display recipe.
- The smaller serif campaign heading alone tightens to -0.01em. Do not apply that tracking to all headings.

## Layout

**Density:** Airy at chapter level, tightly packed within navigation and media grids; long pauses on paper separate image-rich passages.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 9.4px | One grid step: card gutters and metadata gaps. | 0.65vw |
| 18.7px | Two steps: section-top inset, caption separation and compact card padding. | 1.3vw |
| 28.1px | Three steps: outer horizontal margins and stacked card-text gaps. | 1.95vw |
| 37.4px | Four steps: large photographic card inset and grid top separation. | 2.6vw |
| 46.8px | Five steps: directory row gap and footer top padding. | 3.25vw |
| 74.9px | Eight steps: proof-block separation, testimonial-grid top gap and many section bottoms. | 5.2vw |
| 149.8px | Sixteen steps: breathing room around the opening promise and before major transitions. | 10.4vw |

### Containers and grids

- **main container**: max width 1550px · side padding 28.1px. Centered page content with fluid side margins; 1384px usable width at the desktop reference width.
- **editorial grid**: 12 columns · gap 9.4px. Underlying alignment system. Directory tiles span three columns, photographic cards span six; headings and copy often divide into left and right halves.
- **paired media**: 2 columns · gap 9.4px. Two 687px photographic panels; a further editorial slide can peek beyond the right edge.
- **opening measure**: max width 1014px. Centered two-line serif promise, substantially narrower than the full media rail.
- **directory grid** (only for people and customer directories): 4 columns · gap 9.4px. Four equal 339px image tiles at desktop with 46.8px row gaps; text stays below the image on paper.
- **reading column** (only for application-led campaigns): max width 660px · side padding 32px. Centered long-form argument and FAQ; related information can widen to 720px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact actions | 8.4px |
|  | media cards | 18.7px |
|  | index dots | 50% |
| institutional and customer directory introductions | panoramic hero | 37.4px |
| application-led campaigns | application button | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Main page ground.

**CSS:** `background: #f7f6e3; color: #262d29`

**Observed:** A warm pale-yellow field connects sections without alternating white bands.

**Transfer:** Let empty space remain this color, including gutters and caption areas.

#### Sky fade · level 0

**Use:** Atmosphere behind the opening, continuing beneath the navigation.

**CSS:** `background-image: linear-gradient(#c1d1df, rgba(193, 209, 223, 0)); height: 630px`

**Observed:** Blue is concentrated at the top and disappears into the paper, without a hard band edge.

**Transfer:** Use this restrained single-axis fade rather than a multi-hue glow.

#### Photographic card · level 1

**Use:** Editorial, participation and portrait image frames.

**CSS:** `background: #262d29; border-radius: 18.7px; overflow: hidden; position: relative; box-shadow: none`

**Observed:** Images fully cover the backing. Large landscape introductory panels use 37.4px corners; square directory portraits keep the smaller corners.

**Transfer:** Use the dark fill as media backing, not as an empty visible tile.

#### Photo shade · level 2

**Use:** Legibility for text near the lower edge of photographs.

**CSS:** `background-image: linear-gradient(rgba(0, 0, 0, 0) 54%, #000000); opacity: 0.5`

**Observed:** The image remains bright above the bottom caption zone.

**Transfer:** Keep this as an image-sized overlay below the text layer.

#### Charcoal ending · level 0

**Use:** Shared subscription, contact and oversized brand sign-off.

**CSS:** `background: #262d29; color: #f7f6e3`

**Observed:** A full-width closing field, 877px tall at desktop, with utility content above a huge cream wordmark.

**Transfer:** Reserve the longest uninterrupted dark field for the ending.

#### Pastel testimony · level 1

**Only for:** testimonial collections

**Use:** Long quotations in a horizontally overflowing collection.

**CSS:** `background: #c1d1df; color: #262d29; border-radius: 18.7px; box-shadow: none`

**Observed:** Powder blue alternates with sage and peach; these are solid panel fills, not gradients.

**Transfer:** Use the three colors only for a coherent proof collection.

## Components

### Index navigation

**Use:** Compact desktop navigation, aligned in the right half of a wide masthead.

**CSS:** `display: flex; align-items: center; gap: 9.4px; color: #262d29`

**Text style:** `nav` — Suisseintl 400 · 14px/1

**Observed:** Each link begins with a hollow circular marker; active destinations fill their marker. Links form two vertical lists with 4.7px row gaps, while the brand sits alone at left and Outline button sits at far right.

**Transfer:** Keep this index-like treatment rather than making a conventional centered horizontal menu.

### Outline button

**Use:** Default contact and compact secondary action.

**CSS:** `background: transparent; color: #262d29; border: 0.5px solid #262d29; border-radius: 8.4px; padding: 8.4px 12.2px`

**Text style:** `caption` — Suisseintl 400 · 12.9px/1

**Observed:** A compact text-only rectangle. On image cards, category tags reverse to cream text and outline; participation actions use acid-yellow fill.

**States:** Declared: hover background-color #ffff48, color #262d29, border-color #ffff48; focus-visible unknown; active outline 0px.

**Transfer:** Use short direct labels, letting width follow the text.

### Arrow square

**Use:** Paired previous and next carousel controls.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 70px; height: 70px; border: 1.5px solid #262d29; border-radius: 18.7px; background: transparent; color: #262d29`

**Observed:** A 22px simple arrow sits centrally. The pair is separated by one grid step; it is right aligned above the opening photo rail and centered beneath the closing quotation.

**States:** Declared: hover background-color #262d29 and color #f7f6e3; focus-visible outline rgb(77, 101, 255) solid 2.3px with 2.3px offset.

**Transfer:** Preserve the rounded square rather than turning these into circular floating buttons.

### Text link

**Use:** Section-level continuation action at the opposite edge from a heading.

**CSS:** `color: #262d29; text-decoration: underline`

**Text style:** `body` — Suisseintl 400 · 18.7px/1.15

**Observed:** Plain text links carry no button backing and sit on the section-heading baseline.

**States:** Declared: hover opacity 0.6; focus-visible unknown; active outline 0px.

### Editorial media card

**Use:** Large image-first content and participation tiles.

**CSS:** `background: #262d29; border-radius: 18.7px; overflow: hidden; position: relative; color: #f7f6e3`

**Text style:** `card-heading` — Suisseintl 400 · 32.8px/1.15

**Observed:** A full-bleed image beneath Photo shade; bottom-left content is inset 37.4px and stacked with 28.1px gaps. Editorial cards carry date, title, one sentence and an outlined category tag. Participation variants carry a small emblem, name, description and yellow action. Desktop panels are about 687px wide and 790–811px tall.

**Transfer:** Keep the photographic storytelling dominant; avoid dense card chrome.

### Proof number

**Use:** Sparse numerical social proof.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 18.7px`

**Text style:** `stat` — Prody 400 · 131px/1

**Observed:** Large serif digits above a small body label, with no card, icon or border around each fact. Three facts occupy the left three quarters of a twelve-column grid.

**Transfer:** Use a few meaningful figures with short literal labels; an institutional-story variant uses display-sized numbers stacked in the right half.

### Newsletter field

**Use:** Compact signup within the dark ending.

**CSS:** `background: transparent; border: 0.5px solid #f7f6e3; border-radius: 8.4px; padding: 8.4px 12.2px; height: 47px; color: #f7f6e3`

**Text style:** `caption` — Suisseintl 400 · 12.9px/1

**Observed:** The 339px-wide email field contains a right-aligned acid-yellow Subscribe action, about 92px by 41px, inset 2.8px. The action shares the field’s corner treatment.

**Transfer:** Build a single joined field-and-action silhouette, not a separate oversized form stack.

### Monumental footer

**Use:** Shared ending with useful information and a brand-scale final impression.

**CSS:** `background: #262d29; color: #f7f6e3; padding: 46.8px 28.1px 28.1px`

**Text style:** `footer-label` — Suisseintl 600 · 14px/1 · uppercase

**Observed:** A twelve-column grid supports unequal newsletter, contact, social and legal groups. Uppercase small headings precede softer body text at 60% opacity. Small trust marks sit below signup. A cream wordmark then spans the content width, about 1384px by 370px, with ample space before it.

**Transfer:** Use the new name as a vector or typographic wordmark scaled to the width; retain the generous dark sign-off rather than a small centered logo.

### Directory portrait card

**Only for:** people and customer directories

**Use:** People and customer collections.

**CSS:** `background: #262d29; border-radius: 18.7px; overflow: hidden; aspect-ratio: 1 / 1`

**Text style:** `label` — Suisseintl 600 · 14px/1

**Observed:** The CSS applies to the square image frame only. Name and role sit below on paper, separated from the image by 18.7px. Customer variants add a 9px category dot, a compact description and a stage/date caption; the whole text block remains outside the rounded frame.

**Transfer:** Keep individual and group photos at a consistent square aspect ratio even when original compositions vary.

### Pastel quote card

**Only for:** testimonial collections

**Use:** Attributed extended testimony.

**CSS:** `background: #c1d1df; color: #262d29; border-radius: 18.7px; padding: 18.7px`

**Text style:** `quote-body` — Suisseintl 400 · 18.7px/1.25

**Observed:** Name and semibold role lead at top left, a small circular headshot sits top right, prose follows and a customer logo anchors the bottom. Cards are 457px wide and 464px tall at desktop with blue, sage and peach variants.

**Transfer:** Keep each quote specific enough to read as a real relationship, not a numerical endorsement badge.

### Application pill

**Only for:** application-led campaigns

**Use:** Primary application conversion, repeated after the long-form case.

**CSS:** `display: flex; justify-content: center; align-items: center; gap: 10px; background: #fb5e00; color: #ffffff; border: 1px solid transparent; border-radius: 9999px; padding: 20px 36px`

**Text style:** `campaign-action` — Suisseintl 500 · 17px/1

**Observed:** Label followed by a small right arrow, centered below the campaign illustration or reading column.

**States:** Declared: hover outline 0px; focus-visible unknown; active outline 0px.

**Transfer:** Keep this distinct from the compact default contact action.

### FAQ row

**Only for:** application-led campaigns

**Use:** Objection handling after the principal application argument.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 20px; padding: 22px 4px; color: #262d29`

**Text style:** `faq-question` — Suisseintl 500 · 17px/1.4

**Observed:** A details/summary construction with a small down chevron, a faint 1px bottom rule per row and matching top rule for the list. Answers use softer ink, 48px right padding and 26px bottom padding.

**States:** Declared: hover color #fb5e00; focus-visible and active unknown.

**Transfer:** Use real questions in the narrow reading column, not large boxed FAQ cards.

## Imagery and graphics

### Documentary photo rail

**Use:** Main opening media and image-led proof throughout the page.

**Observed:** Candid indoor gatherings, conversations and groups in real working spaces, naturally lit and warmly colored. A broad central landscape panel is flanked by clipped neighboring panels; small cream captions sit at the bottom. Images have rounded corners but no raised shadow.

**Transfer:** Photograph users making, discussing or using the new product in lived-in settings. If product media is unavailable, stage a credible working conversation rather than substituting a glossy abstract render.

### Orange seed field and emblem

**Use:** Signature organic punctuation across the opening and an isolated graphic pause later.

**Observed:** Sparse irregular orange near-circles of varied size float over the sky fade and overlap photography. A later orange linear emblem gathers rounded seed-like tips around a thin vertical branching structure, centered in a broad paper clearing.

**Transfer:** Create a simple original organic symbol relevant to the new product and repeat its rounded parts as scattered opening marks. A dot-and-line emblem is the minimum acceptable version; retain the playful flat orange treatment.

**Build:** Use SVG paths for six to eight near-circular blobs, each with slightly uneven Bezier contours, filled #fb5e00 without outlines or shadow. As design guidance, vary diameters from 20px to 90px, scatter around rather than over the headline and allow one to cross the photo boundary. Construct an original centered emblem around 122px by 193px using a 3px orange spine and short branches ending in the same blobs; give it approximately 150px of paper breathing room.

### Editorial cover art

**Use:** Image surfaces for educational and opinion content.

**Observed:** One cover uses warm orange botanical shadows and soft-focus leaves with a small acid-yellow organic dot. Another uses powder-blue architecture with a large centered orange quotation embedded in the artwork. The cover occupies nearly the entire tall card and text overlays its lower portion.

**Transfer:** Use a restrained photographic metaphor or original typographic cover tied to the article; keep the palette coordinated without applying an orange filter to every image.

**Build:** For a simple original cover, place a peach or sky-colored field beneath a photographic plant or architectural detail, soften the image edges and overlay one small #ffff48 irregular circle. For a text-led cover, center a short orange quotation in the upper half while reserving the bottom third for the card title.

### Natural portrait wall

**Only for:** people and customer directories

**Use:** Repeated square imagery above compact metadata.

**Observed:** Relaxed waist-up or chest-up portraits with books, plants, windows and warm pendants in the background. People face the camera with approachable expressions. Customer entries broaden this into small founder teams in offices and outdoors, retaining natural color.

**Transfer:** Normalize image framing and light rather than cutting people onto a uniform colored backdrop. Keep the environment as part of the story.

### Panoramic introduction

**Only for:** institutional and customer directory introductions

**Use:** Wide photographic hero beneath the common masthead.

**Observed:** A 1384px by 692px rounded panel uses either an environmental group photograph or an atmospheric harbor scene framed through bridge structure. A dark lower scrim supports a small eyebrow, serif headline and one support sentence at bottom left.

**Transfer:** Use an authentic place or group that represents the product’s world, leaving a legible lower-left text zone.

### Organic photo constellation

**Only for:** institutional approach stories

**Use:** A visual chapter beside explanatory text.

**Observed:** Three overlapping rounded organic image masks occupy the right half: a 552px main aerial photograph, a 276px conversation scene and a 184px close portrait. The left half stays mostly empty above low-set prose and small pagination dots.

**Transfer:** Combine environment, collaboration and individual detail; preserve the hierarchy of one large and two small windows.

**Build:** Use three absolute-positioned image wrappers with overflow hidden and asymmetric rounded clip paths. Set the main wrapper to 552px square, place a half-size wrapper across its lower-left edge and a one-third-size wrapper over its upper-right edge. Use object-fit cover and no outlines or shadows.

### Orange constellation field

**Only for:** application-led campaigns

**Use:** Abstract hero in place of photography.

**Observed:** An airy rectangular cloud of hundreds of tiny orange dots, with just a few fine charcoal line segments connecting small clusters. The drawing is centered between a status eyebrow and a single serif sentence.

**Transfer:** Use a point field to evoke exploration or emerging connections, not a literal product interface.

**Build:** Create an SVG viewBox 0 0 1100 413. Concentrate irregularly spaced orange circles with 1px to 3px radii in the middle two thirds, taper density toward the edges, and join a few clusters of three or four points with 1px charcoal strokes at reduced opacity. Leave most points unconnected and retain the paper background.

### Icons

**Observed:** Simple 22px directional arrows in rounded-square controls, tiny 9px hollow or filled circular navigation markers, understated chevrons and small monochrome program emblems. Decorative motifs use organic dots rather than a stock icon suite.

**Transfer:** Use thin, direct directional shapes and small monochrome identifiers. Keep illustrative personality in the organic graphics, not in large multicolor feature icons.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric sentence opening

**Observed:** Paper is overlaid with Sky fade, then a loose orange seed field, Index navigation and centered serif promise. The masthead occupies about 150px; its brand sits left and the two small link columns begin around the page midpoint. The promise occupies about two thirds of the width and two lines at 42.1px/1.15, with roughly 150px breathing room above and below. Arrow square controls sit at the right just before a panoramic photo rail begins around the lower third of the first screen. Within 900px, the navigation, contact action, complete promise, orange marks, controls and upper part of the photo rail are visible. There is no separate support paragraph or large central CTA in this opening; full photographs and captions continue below the fold.

**Transfer:** Make the sentence a clear account of whom the new product helps and what future it enables. Pair it with original orange organic marks and real working photography; the emblem and dots provide a strong first screen even without bespoke media. Institutional introductions instead use Panoramic introduction; directories can open with a ruled heading/filter strip; application-led campaigns use Orange constellation field above a smaller serif subhead and Application pill.

**Avoid:** Do not replace the editorial sentence with a huge bold sans headline, a dashboard mockup centered above the fold or a stacked pair of oversized CTAs.

**Text style:** `display` — Prody 400 · 42.1px/1.15

### Ruled section introduction

**Observed:** A 1px charcoal rule spans the main container. A heading sits 18.7px below it, with support text another 18.7px below where needed. A Text link aligns at the far right. Content begins after a 37.4px or 74.9px gap.

**Transfer:** Use the rule as a chapter marker; choose heading for major editorial sections and lead for smaller institutional chapters.

**Text style:** `heading` — Suisseintl 400 · 42.1px/1.15

### Unboxed numerical proof

**Observed:** A lead sentence occupies the left side below a full-width rule, with Text link at right. Three Proof number blocks start after about 74.9px; serif figures dwarf the literal small labels and leave the rightmost quarter open.

**Transfer:** Carry a few decisive facts in this sparse typographic construction rather than adding a metric-card dashboard.

**Text style:** `stat` — Prody 400 · 131px/1

### Paired image chapters

**Observed:** Ruled section introduction precedes two adjacent Editorial media cards with narrow gutters and tall image areas. Additional editorial slides extend beyond the content edge. Program-like offerings use the participation variant with yellow actions.

**Transfer:** Use image-led chapters for different use cases, resources or ways to participate; keep the text near the lower edge and the image responsible for mood.

### Isolated quotation

**Observed:** A broad paper field centers an attribution, a two-line serif quotation at the visual scale of the opening statement, a small monochrome customer mark and paired Arrow square controls below. The field is about 752px tall with no surrounding card.

**Transfer:** Give one strong customer sentence room to stand as an editorial closing thought, without a competing sales headline.

**Text style:** `display` — Prody 400 · 42.1px/1.15

### Dark wordmark sign-off

**Observed:** Monumental footer begins as a full-width charcoal surface. Small utility groups occupy the upper area and the joined Newsletter field provides the bright yellow conversion detail. The lower area is dominated by the new name in cream, almost edge to edge, with 28.1px outer margins. This same ending works after a quote, a directory, editorial news or campaign information.

**Transfer:** Make the end both useful and memorable: preserve the compact upper grid and the oversized own-name sign-off rather than adding another generic CTA panel.

### Portrait directory

**Only for:** people and customer directories

**Observed:** A ruled introductory strip pairs a serif heading at left with compact filter lists and a short explanation at right. Filters use hollow circles with a filled selected state. A four-column Directory portrait card grid begins after a paper pause; rows are separated by 46.8px. The final incomplete row stays left aligned, followed by generous paper space before Monumental footer.

**Transfer:** Let a long collection remain a straightforward browsing surface. Use compact metadata rather than enclosing every entry in a new panel.

**Text style:** `display` — Prody 400 · 42.1px/1.15

### Institutional split story

**Only for:** institutional storytelling

**Observed:** After Panoramic introduction, a two-column paper section pairs 28.1px Book lead paragraphs on the left with ordinary prose, short semibold propositions and smaller serif facts stacked on the right. Organic photo constellation forms a later approach chapter; a small portrait row can follow.

**Transfer:** Alternate emotional introductions with specific operational details. Keep the explanatory text on paper instead of adding colored boxes.

**Text style:** `lead` — Suisseintl 400 · 28.1px/1.15

### Pastel proof rail

**Only for:** testimonial collections

**Observed:** Ruled section introduction leads to three visible Pastel quote cards with a sliver of the next card. Cards begin 74.9px below the heading, share a bottom logo baseline and alternate powder blue, sage and peach.

**Transfer:** Use attributed customer stories as a scoped palette change, retaining the same rounded geometry and narrow gutter.

**Text style:** `quote-body` — Suisseintl 400 · 18.7px/1.25

### Press index

**Only for:** institutional news collections

**Observed:** A ruled lead heading occupies the left half while a compact single-column list sits in the right half. Each row has a square publication mark beside an underlined title and a softer reading action; the publication tiles are about 103px square with 8.4px corners.

**Transfer:** Use authentic publication marks as image assets, preserving the split editorial composition rather than making a full-width logo wall.

**Text style:** `lead` — Suisseintl 400 · 28.1px/1.15

### Long-form invitation

**Only for:** application-led campaigns

**Observed:** A centered 660px reading column carries small uppercase labels, 18px/1.25 paragraphs, short semibold introductions and a numbered benefit list with small orange indices. An Application pill ends the argument. FAQ row follows under a serif title, then a quieter ruled information band before the common dark footer.

**Transfer:** Explain who the offer suits, what the exchange involves and what is not promised. Reserve the orange pill for the actual application path.

**Text style:** `campaign-body` — Suisseintl 400 · 18px/1.25

## Page flow

**Storyline:** Human promise → lived-world imagery → concrete proof → useful ways to engage → personal endorsement or practical answers → subscription and monumental brand sign-off.

### Broad marketing landing page

1. **Promise** — Centered serif sentence in a blue-to-paper field with orange organic punctuation.
2. **Lived-world proof** — Rounded panoramic documentary rail, followed by a moving logo strip and an isolated orange emblem.
3. **Quantified proof** — Ruled lead and three unboxed oversized serif numbers.
4. **Useful engagement** — Editorial image rail and paired participation cards.
5. **Personal endorsement** — Isolated serif quotation with attribution and carousel controls.
6. **Closing action** — Dark subscription/contact grid and monumental pale wordmark.

**Transfer:** Use the devices as narrative punctuation while choosing the order and number of chapters to fit the new product.

### Application or invitation landing page

1. **Invitation** — Abstract orange point constellation, small status line, serif subhead and orange application action.
2. **Rationale** — Narrow long-form argument with numbered benefits and candid eligibility discussion.
3. **Conversion** — Repeated centered application pill.
4. **Objection handling** — Compact ruled accordion.
5. **Conditions** — Subdued information band separated by a fine rule.
6. **Closing action** — Shared dark subscription and wordmark ending.

**Transfer:** Use this variant when understanding and self-selection matter more than rapid product scanning.

### People directory

1. **Orientation** — Shared masthead, ruled serif title, function filters and a short introduction.
2. **Human credibility** — Four-column square portrait collection with small name and role captions.
3. **Closing action** — Paper breathing room followed by the common dark footer.

**Transfer:** Keep the opening utilitarian and let the portraits provide the warmth.

### Customer or project directory

1. **Promise** — Panoramic environmental image with bottom-left serif statement.
2. **Wayfinding** — Compact stage, sector and view filters marked with circles.
3. **Breadth of proof** — Long four-column square image directory with category dots, descriptions and small metadata.
4. **Closing action** — A left-aligned partial final row, open paper and the shared dark footer.

**Transfer:** Use a rich directory instead of a decorative logo grid when individual relationships or projects matter.

### Institutional story

1. **Welcome** — Environmental group hero with brief greeting and support sentence.
2. **Conviction and scale** — Split-column argument, semibold principles and small stacked serif statistics.
3. **Approach** — Organic photo constellation beside low-set explanatory text.
4. **People** — Small portrait selection with continuation link.
5. **External validation** — Pastel quotation rail and right-column press index.
6. **Closing action** — Shared subscription/contact grid and oversized wordmark.

**Transfer:** Pair a warm human introduction with specific working principles and outside voices, avoiding a generic corporate manifesto wall.

## Writing

Warm, plainspoken and ambitious without being grandiose. Confidence comes through practical detail and long-term commitment, with occasional colloquial language that makes the institution feel like people.

**Do not copy:** Do not reuse Airtree’s name, logo, proprietary illustrations, program names, geographic claims, financial claims, statistics, legal details or customer quotations. The examples illustrate tone only; supply the new product’s own truthful facts and identity.

- **Addressing the reader:** Use we for the organization and you or your for the reader. Describe relationships as people helping people, not an abstract platform servicing users.
- **Rhythm:** Headlines can be full sentences rather than compressed slogans. Follow with one short support sentence; longer explanatory chapters use readable paragraphs and occasional concise proposition headings.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | We + concrete commitment + named audience + consequential outcome. | A full sentence, often 12–18 words | “We back Aussie and Kiwi founders building the iconic technology companies of tomorrow” |
| Supporting line | Explain the practical content or value in one sentence, often with concrete nouns. | One sentence | “Company-building guides, how-to's, templates, databases, interviews and analysis.”<br>“We're right by your side, right from the start.” |
| Section heading | Direct navigational noun phrase, with little promotional decoration. | 2–5 words | “Our programs”<br>“What our founders say” |
| Invitation | Name a significant personal decision in conversational language. | One sentence | “A residency for founders working out what's worth their next decade.” |
| Primary action | A direct verb describing what happens next. | 2–4 words | “Get in touch”<br>“Apply to join”<br>“Meet everyone” |
| Welcome | A human greeting, followed by a self-aware conversational transition. | Brief greeting and one sentence | “G'day. Kia Ora.”<br>“We’re excited to meet you. But first, here's our pitch to you.” |
| Reassurance | A short confident answer to the reader’s real concern. | 3–6 words before explanation | “We have answers.” |

**Words and phrasing to use:** right from the start; working out; building; gather, learn and collaborate; next decade; alongside; here’s our pitch; in practice

**Avoid:** disruptive synergy; unparalleled solutions; unlock limitless potential; best-in-class platform; frictionless everything

**Rules:**

- Lead with the audience and the commitment rather than a feature inventory.
- Make abstractions tangible through a room, a conversation, a prototype or another familiar working detail.
- Keep section links literal: See more, About us and Meet everyone are the model for clarity.
- Use contractions and occasional colloquial phrasing; preserve a serious, specific account of obligations and limits in longer offers.
- Label numbers with what they count; do not make the reader decode a naked metric.

## Do's and Don'ts

### Do

- Use the 42.1px regular serif recipe for the opening and reserve 131px type for numerical proof.
- Keep the paper ground continuous through gaps, caption areas and open space.
- Align chapters to the 12-column grid and use 9.4px gutters between media panels.
- Pair full-width 1px rules with 18.7px heading insets to establish chapter starts.
- Make photographic cards image-led with 18.7px corners and bottom-set pale content.
- Carry the flat orange organic motif through both scattered dots and a concentrated emblem.
- Use compact 8.4px-corner actions and a bright yellow signup detail as the default action language.
- Finish with the dark information field and an own-name wordmark almost as wide as the container.

### Don't

- Do not set all headings in semibold grotesk; the regular serif/grotesk contrast is the hierarchy.
- Do not use white as the default page canvas or replace the charcoal ending with pure black.
- Do not turn the default contact action into a 59px orange pill; that geometry belongs to the application variant.
- Do not add shadows or floating glass panels to the flat paper-and-photography composition.
- Do not use pastel testimonial colors as alternating full-page feature backgrounds.
- Do not place names and role captions inside the portrait image; they sit on paper below it.
- Do not inflate the 9.4px media gutters into broad 32px card spacing.
- Do not replace the compact index navigation with a row of large icon-backed tabs.

## Motion and responsive

### Motion

**Observed:**

- Compact outlined actions declare border-color, color and background-color transitions of 0.3s. Footer copy and many links declare opacity 0.4s.
- Arrow controls declare color 0.2s, background-color 0.2s and transform 0.3s cubic-bezier(0.075, 0.82, 0.165, 1).
- Two continuous scroll animations are declared at 50s linear infinite. The image rail and quotation use previous/next controls.
- Campaign questions declare color 0.16s; the application button declares background-color 0.18s, color 0.18s and transform 80ms.

**Transfer:**

- Use the measured understated fades for small actions; keep the organic artwork and media rail as the sources of visual movement.
- A continuous logo strip should retain the very slow linear character rather than becoming a fast news ticker.

**Unknown:**

- The exact orange-dot animation choreography, scroll-trigger timing and carousel autoplay behavior are not established.

### Responsive

**Observed:**

- The root font size is 1.3vw, so rem-based type and spacing scale together.
- Styles declare width breakpoints at 479px, 480px, 767px, 768px, 991px, 992px, 1200px and 1600px.
- Campaign subhead and FAQ heading use explicit clamp formulas rather than the main rem-based scale.

**Transfer:**

- On narrow layouts, preserve readable type rather than allowing small captions to shrink indefinitely; treat a minimum readable size as an implementation decision.
- Reduce the directory’s column count and let media rails remain horizontally browsable, preserving rounded frames and close gutters.
- Keep organic marks away from text, retain the single centered promise and scale the footer wordmark to its container width.

**Unknown:**

- Exact mobile column counts, navigation transformation, minimum root size and narrow-screen artwork positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
