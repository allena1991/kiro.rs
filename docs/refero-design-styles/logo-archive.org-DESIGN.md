# LogoArchive — the editorial cabinet

## Overview

An almost monochrome digital exhibition, with charcoal rooms, acid-yellow markers and regular grotesk lettering interrupted by elegant serif italics. Product interfaces and sculptural device photography are treated like collected objects rather than busy software dashboards. The feeling is cultured, assured and spacious, suited to creative tools, reference products and specialist memberships; small controls stay dense inside very broad compositions.

### Essentials

- Headlines mix two editorial voices: regular Suisse International at 96px/1 in the opening, with individual words in Suisse Works Book italic at the same size; tracking stays normal, not aggressively tightened.
- The opening is a sentence-sized exhibition: a centered 1080px-wide text block contains two white 200×74px capsules of moving monochrome symbols, with the promise bright and the endorsement clause visibly dimmer. Use original geometric product motifs when there are no suitable objects to show.
- Rounded rooms, not floating widgets: default panels are #27272a with 28px corners, separated by 24px strips of #18181b; split interiors use 6px seams and 22px inner corners, without shadows.
- Yellow behaves like a highlighter: #fde533 belongs to 24px-high labels and the main 48px pill action, leaving nearly all of an ordinary page charcoal, black and gray. A full yellow offer panel is reserved for organization sales.
- The product gets museum staging: a dark interface is shown at substantial scale, either in a browser with an overlapping phone or on a black tablet standing on a gray plinth against black. Include this staged product proof; a simple original screen in a dark device frame is the minimum equivalent.
- Graphic echoes create the exhibition atmosphere: large monochrome product-related symbols float quietly around a central message on black, and a monumental low-contrast action word overlaps a fading row of 35px category pills. Preserve both devices using original abstract symbols and a relevant verb.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Highlighter yellow | `#fde533` | `--color-yellow` | accent, action, surface, border | Main actions and tiny labels; a broad offer fill only for organization sales. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Headlines, primary feature text, inline object capsules and the organization-sales button. |
| Pale gray | `#dadee4` | `--color-fine-text` | text, accent | Small attribution text and quiet separators. |
| Cool gray text | `#a8afb7` | `--color-muted` | text | Supporting copy, plan titles and secondary action labels. |
| Faded tag gray | `#525254` | `--color-closing-tags` | surface | Visible white at 50% with a further 50% group opacity over charcoal in the closing pill row; individual pills fade further toward one edge. |
| Inset gray | `#343538` | `--color-inset` | surface, border | Secondary buttons, testimonial inset and small circular list markers. |
| Exhibition gray | `#27272a` | `--color-panel` | surface, border | Main rounded panels and pricing cards; pricing outlines use the same color as their fill. |
| Charcoal canvas | `#18181b` | `--color-canvas` | background, text | Default page and fixed navigation canvas; also dark text on the white organization-sales button. |
| Gallery black | `#000000` | `--color-black` | background, text, surface | Immersive graphic rooms, device-photo backing and text on yellow. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| organization capability narratives | First stack gray | `#303033` | `--color-stack-first` | surface | Lightest numbered feature card. |
| organization capability narratives | Second stack gray | `#29292c` | `--color-stack-second` | surface | Second numbered feature card. |
| organization capability narratives | Third stack gray | `#232326` | `--color-stack-third` | surface | Third numbered feature card. |
| organization capability narratives | Last stack gray | `#1d1d20` | `--color-stack-last` | surface | Darkest numbered feature card. |
| organization sales | Photo support gray | `#b8b8b8` | `--color-photo-support` | text | Visible white at 72% over black for support copy on the photographic opening. |

## Typography

- **Suisse International** — All primary headings, paragraphs, labels and controls. Neutral neo-grotesk with open regular-weight letterforms; large statements feel typeset rather than branded with a heavy display cut. If unavailable, use **Inter**. Use 400 for text and 500 for actions; retain normal tracking. Font stack: "Suisse International", "Inter", -apple-system, system-ui, "Segoe UI", Roboto, sans-serif.
- **Suisse Works** — Selected headline words and small chapter numbers. Bookish high-contrast serif, most recognizably used in flowing italics inside grotesk sentences. If unavailable, use **Libre Baskerville**. Use regular italic for emphasis; adjust wrapping to preserve the mixed sentence. Font stack: "Suisse Works", "Libre Baskerville", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Suisse International | 400 | 96px | 1 | normal | fixed | Default opening sentence and its endorsement continuation. |
| display-italic | Suisse Works | 400 italic | 96px | 1 | normal | fixed | One emphatic word within the opening sentence. |
| section-heading | Suisse International | 400 | 64.8px | 0.9 | normal | size calc(19.4px + 3.15789vw) | Centered statements in large exhibition panels. |
| section-italic | Suisse Works | 400 italic | 64.8px | 1.2 | normal | size calc(19.4px + 3.15789vw) | Emphasis within the large section statements. |
| split-heading | Suisse International | 400 | 37.7px | 0.95 | normal | size calc(18.7px + 1.31579vw) | Left-aligned headline beside a large product image. |
| split-italic | Suisse Works | 400 italic | 37.7px | 1.2 | normal | size calc(18.7px + 1.31579vw) | Emphatic words in split-panel headlines. |
| quote | Suisse International | 400 | 24.2px | 1.2 | normal | size calc(12.8px + 0.789474vw) | Testimonial quotation in the lighter inset. |
| body | Suisse International | 400 | 20.1px | 1.4 | normal | size calc(14.4px + 0.394737vw) | Supporting paragraph in split panels. |
| immersive-support | Suisse International | 400 | 19.5px | 1.2 | normal | size calc(11.9px + 0.526316vw) | Narrow centered paragraph within the symbol field; white at 50% opacity. |
| support | Suisse International | 400 | 18px | 1.2 | normal | fixed | One-line opening support; also compact plan amounts. |
| tag | Suisse International | 400 | 16px | 1.2 | normal | fixed | Category pills over the monumental closing word. |
| compact | Suisse International | 400 | 14px | 1.2 | normal | fixed | Pricing feature lists, billing switches and short qualifiers. |
| action | Suisse International | 500 | 14px | 1 | normal | fixed | Text inside pill actions, including the smaller navigation action. |
| label | Suisse International | 400 | 12px | 1.2 | normal | fixed | Yellow marker text, attribution and billing qualification. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| organization sales | offer-amount | Suisse International | 400 | 60px | 0.9 | normal | size clamp(36px, -12px + 5vw, 60px) | Isolated price on the right of the yellow offer panel. |
| organization sales | sales-heading | Suisse International | 400 | 56px | 1 | normal | size clamp(32px, 4vw, 56px) | Photographic sales opening and final contact question. |
| organization sales | sales-italic | Suisse Works | 400 italic | 56px | 1.2 | normal | fixed | Single audience-expanding word in the photographic opening. |
| organization capability narratives | manifesto | Suisse International | 400 | 42.4px | 1 | normal | fixed | Short large paragraphs staggered across two columns. |
| organization sales | capability-heading | Suisse International | 400 | 36px | 1.05 | normal | size clamp(24px, 2.5vw, 40px) | Numbered feature-card headline and the yellow offer headline. |
| organization sales | offer-italic | Suisse Works | 400 italic | 36px | 1.2 | normal | fixed | Single emphasis word inside the offer headline. |
| pricing comparisons | plan-title | Suisse International | 400 | 28px | 1.2 | normal | fixed | Muted pricing-card titles. |
| organization sales | sales-support | Suisse International | 400 | 18px | 1.45 | normal | fixed | Two-line support below the photographic opening headline. |
| organization capability narratives | chapter-number | Suisse Works | 400 | 14px | 1 | normal | fixed | Upright book-serif chapter index with a small dot. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight and normal tracking persist even at the largest sizes. Hierarchy is primarily scale, contrast, line breaks and the change to serif italic.
- The serif is an inline interruption, not a second all-purpose heading system. Its 1.2 line height can lift the line box beyond the tighter grotesk rhythm.
- The giant closing word is vector artwork spanning about the viewport width and 287px in height, not another body-text size.
- Keep the endorsement continuation dimmer than the opening promise. It is the same 96px recipe, not a small subtitle.

## Layout

**Density:** Airy exhibition spaces with compact labels and controls; broad panels contain small tightly organized details.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Split-panel seams and outer inset around nested media. | fixed |
| 8px | Between paired actions and label internals. | fixed |
| 16px | Paragraph relationships and action qualification. | fixed |
| 24px | Default separation between rounded rooms and between pricing columns. | fixed |
| 32px | Pricing and split-panel copy padding. | fixed |
| 36px | Header side inset and organization-page outer gutter. | fixed |
| 40px | Opening support-to-action grouping. | fixed |
| 48px | Large label-to-heading spacing, feature chapter spacing and closing headline-to-action gap. | fixed |
| 72px | Organization offer and numbered-feature copy padding. | clamp(32px, 5vw, 72px) |
| 96px | Separation before large organization proof and offer moments. | fixed |
| 120px | Top padding of the product introduction room. | fixed |
| 144px | Opening bottom breathing room. | fixed |
| 160px | Pause after the pricing comparison before the closing word. | fixed |

### Containers and grids

- **Marketing rooms**: max width 1440px · side padding 100px. At desktop, panels occupy 1240px within a centered shell. The closing word breaks out to the page edges.
- **Opening sentence**: max width 1080px · side padding 36px. Centered opening text block, visually spanning most of the usable width without touching the navigation gutter.
- **Split room**: 2 columns · gap 6px. Equal copy and media halves within a rounded outer room; media is inset rather than floating above the room.
- **Plan comparison** (only for pricing comparisons): 3 columns · gap 24px. Equal 397px-wide cards, all aligned at top and action baseline.
- **Organization rooms** (only for organization sales): max width 1440px · side padding 36px. Wider 1368px rooms on black, with 465px maximum feature-copy width.
- **Closing contact** (only for organization sales): max width 620px · side padding 24px. Centered multiline question and one action with equal visual space above and below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Room corners | 28px |
|  | Inset media and quote | 22px |
|  | Actions and inline objects | 9999px (pill) |
|  | Marker labels | 4px |
|  | Closing category pills | 40px |
| pricing comparisons | Billing switch | 20px |

## Surfaces and depth

### Surfaces

#### Charcoal canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #18181b; color: #ffffff`

#### Exhibition room · level 1

**Use:** Large product chapters and split panels.

**CSS:** `background: #27272a; border-radius: 28px; overflow: hidden; box-shadow: none`

**Observed:** Broad bounded rooms separated by exposed canvas; there is no lifted-card shadow.

**Transfer:** Use changes of neutral tone and silhouette to divide the narrative.

#### Inset gray · level 2

**Use:** Testimonial and secondary controls.

**CSS:** `background: #343538; border-radius: 22px`

**Observed:** The inset sits inside the larger room with a narrow seam.

**Transfer:** Reserve the lighter neutral for inset content rather than every panel.

#### Black gallery · level 1

**Use:** Immersive symbol-field chapter.

**CSS:** `background: #000000; border-radius: 28px; overflow: hidden`

**Observed:** The dark field recedes behind a centered message and quiet symbolic artwork.

**Transfer:** Use flat black to make a full room feel deeper without adding shadows.

#### Photo legibility veil

**Only for:** organization sales

**Use:** Between device photograph and foreground text.

**CSS:** `background-image: linear-gradient(to top, rgba(0, 0, 0, 0.9) 0%, rgba(0, 0, 0, 0.5) 38%, rgba(0, 0, 0, 0) 72%)`

**Observed:** The upper device remains readable while the foreground fades into black.

**Transfer:** Keep the fade neutral; do not add colored spotlights.

#### Yellow offer room · level 1

**Only for:** organization sales

**Use:** Single direct commercial offer near the end.

**CSS:** `background: #fde533; color: #000000; border-radius: 28px; padding: 72px`

**Observed:** A rare broad accent field following a long black-and-gray narrative.

**Transfer:** Use this much color only when the organization page reaches its explicit offer.

## Components

### Fixed navigation

**Use:** Persistent orientation and returning-user access.

**CSS:** `position: fixed; height: 78px; background: #18181b; padding: 0px 36px; display: grid; grid-template-columns: repeat(12, 1fr); align-items: center; z-index: 999`

**Text style:** `action` — Suisse International 500 · 14px/1

**Observed:** A small white 32×16px brand symbol anchors the left; a single gray pill anchors the right. The login variant is 36px high rather than the main action height.

**Transfer:** Keep the top bar extremely sparse instead of introducing a multi-link navigation menu.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #fde533; color: #000000; border: 1px solid #fde533; border-radius: 9999px; height: 48px; padding: 8px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Suisse International 500 · 14px/1

**Observed:** Text-led action with content-driven width. It leads a pair of pills in the opening; the closing email variant adds a small envelope.

**Transfer:** Use a concrete verb and keep it the brightest small object in the composition.

### Secondary button

**Use:** Pricing navigation and lower-emphasis conversion.

**CSS:** `background: #343538; color: #a8afb7; border: 1px solid #343538; border-radius: 9999px; height: 48px; padding: 8px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Suisse International 500 · 14px/1

**Observed:** Placed beside the yellow action with an 8px gap. Pricing versions stretch across the card; the navigation version is shorter.

**Transfer:** Use gray fill, not a white outline or transparent text link.

### Yellow marker

**Use:** Short section introduction or small announcement.

**CSS:** `background: #fde533; color: #000000; border-radius: 4px; padding: 4px 8px; display: inline-flex; align-items: center`

**Text style:** `label` — Suisse International 400 · 12px/1.2

**Observed:** A compact sentence-case tab above the headline. An announcement variant adds a tiny darker status tab inside its left edge.

**Transfer:** Treat the marker as a highlighter strip rather than an uppercase eyebrow spread across the page.

### Quote inset

**Use:** Human proof within an equal-column room.

**CSS:** `background: #343538; border-radius: 22px; padding: 32px 48px 32px 32px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quote` — Suisse International 400 · 24.2px/1.2

**Observed:** A circular portrait zone occupies the upper portion; a gray quote sits lower, followed by a small name, dot separator and professional role. A simple label occupies the other half of the room.

**Transfer:** Keep one quote prominent, with attribution subordinate rather than filling the panel with a testimonial grid.

### Closing category pill

**Use:** A fading horizontal vocabulary strip over the giant closing word.

**CSS:** `background: rgba(255, 255, 255, 0.5); color: rgba(0, 0, 0, 0.5); border-radius: 40px; padding: 8px 16px; margin: 0px 5px`

**Text style:** `tag` — Suisse International 400 · 16px/1.2

**Observed:** The row has a further 50% group opacity. Individual pills progressively fade toward one side; they overlap the lower-middle of the oversized word rather than becoming a separate tag cloud.

**Transfer:** Use a handful of product-relevant categories with short names.

### Plan card

**Only for:** pricing comparisons

**Use:** Membership comparison.

**CSS:** `background: #27272a; border: 2px solid #27272a; border-radius: 28px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `plan-title` — Suisse International 400 · 28px/1.2

**Observed:** A muted title precedes a small amount and tiny billing qualification, then the Billing switch, compact feature list and full-width Secondary button. Three equal cards share the same gray treatment; no plan is given a colorful recommended badge.

**Transfer:** Let differences in audience and features carry the comparison; do not enlarge the price into the headline.

### Billing switch

**Only for:** pricing comparisons

**Use:** Choose billing period within each plan.

**CSS:** `background: #18181b; border-radius: 20px; padding: 4px; display: flex; align-items: center; justify-content: center`

**Text style:** `compact` — Suisse International 400 · 14px/1.2

**Observed:** Centered in the card. The selected period has a #27272a inset with 20px corners and 4px 10px padding; the other has no fill and reduced opacity. The group is visually subdued.

**Transfer:** Keep this control secondary to the plan name and feature list.

### Numbered capability card

**Only for:** organization capability narratives

**Use:** Explain a single capability through a sparse demonstration.

**CSS:** `background: #303033; border-radius: 28px; padding: 6px; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 6px; position: sticky; margin-bottom: 24px`

**Text style:** `capability-heading` — Suisse International 400 · 36px/1.05

**Observed:** The left half starts with a dot and book-serif index, then a regular headline after 48px. Copy is padded by 72px and limited to 465px. The right half is black with 22px corners and a small centered interface vignette. Successive cards darken through #29292c, #232326 and #1d1d20 and shorten by 24px, forming a visible stack.

**Transfer:** Make each card explain one outcome through an isolated visual rather than a full product tour.

### Organization offer

**Only for:** organization sales

**Use:** A direct price-and-action block.

**CSS:** `background: #fde533; color: #000000; border-radius: 28px; padding: 72px; display: grid; grid-template-columns: minmax(0px, 1fr) auto; gap: 115.2px; align-items: center`

**Text style:** `capability-heading` — Suisse International 400 · 36px/1.05

**Observed:** A left-aligned mixed-font promise and white 48px pill action sit opposite an isolated large price with two compact billing lines. The headline area can extend to 760px.

**Transfer:** Use the Offer amount recipe for a single price, not a dense pricing table.

## Imagery and graphics

### Inline object capsules

**Use:** Inside the default opening sentence.

**Observed:** Two horizontal white capsules, each 200×74px, interrupt the 96px text. Dark monochrome symbols are arranged in a moving strip and clipped at the capsule edges; the endorsement capsule is dimmed with its clause.

**Transfer:** Use original product-shaped symbols, tiny monochrome work samples or abstract geometric motifs. Keep the objects legible at text scale rather than inserting miniature dashboards.

**Build:** Create a white 200×74px rounded overflow-hidden inline block aligned to the text baseline. Place a horizontal flex strip of simple SVG rings, cut circles and stacked bars inside, filled #18181b, each about 40px high. Repeat the strip so a loop does not expose a gap; dim the entire second clause rather than changing the symbol palette.

### Device exhibition

**Use:** Product-proof room and split feature imagery.

**Observed:** A dark browser window is backed by gray and overlapped by a slim phone on its right. The other treatment is a nearly front-on black tablet on a hard-edged gray plinth, lit softly from above against a deep black vignette; its white product graphics supply almost all the image contrast.

**Transfer:** Show a real interface or original schematic in a dark browser and device frame. For the plinth scene, a simple rectangular pedestal, soft overhead light and black backdrop are sufficient; preserve the restrained grayscale rather than inventing glossy colorful hardware.

### Peripheral symbol field

**Use:** Behind centered benefit and proof statements.

**Observed:** Large monochrome emblems are spaced loosely around the edges of a black or charcoal room. Some are clipped by the room boundary; the central text remains clear. They are much dimmer than the text and have no bright colored glow.

**Transfer:** Use a family of original geometry derived from the new product's objects or outputs. The minimum equivalent is a handful of bold abstract rings, bars and cut circles, not borrowed customer marks.

**Build:** Use an absolute SVG layer clipped by the room's 28px corners. Scatter several roughly 129–140px symbols around the top and sides, extending some beyond the edges. Fill with white at low opacity over black, or a similarly low-contrast neutral over #27272a. Leave a clear central region behind the label, headline and paragraph; place all copy in a higher stacking layer.

### Monumental closing verb

**Use:** Graphic ending to the default marketing narrative.

**Observed:** A single grotesk action word spans the page edge to edge as vector artwork, 1440×287px at desktop, with 10% opacity. It is partially clipped at the edges and crossed by the Closing category pill row. The composition follows a long 160px pause after pricing and leaves 200px below.

**Transfer:** Choose an original short verb that expresses the product's core activity. Render it as responsive SVG text or outlined type, fitting its visible letter height to the strip instead of forcing an arbitrary font size.

**Build:** Make a full-width SVG with a 1440×287 viewBox. Set an oversized regular grotesk word to fill the viewBox optically, allowing the first and last glyphs to run beyond the sides. Use white with opacity 0.1 over #18181b. Overlay a centered, single-line pill row at about the lower-middle, with progressively decreasing opacity toward one edge.

### Perspective object carousel

**Only for:** organization sales

**Use:** A visual interlude between capability explanation and summary proof.

**Observed:** A shallow curved parade of dark rectangular collection cards floats against black. The central cards face the reader while outer cards turn away in perspective; white symbols dominate each card with tiny metadata beneath. The whole assembly occupies about 922×459px.

**Transfer:** Use original product outputs or work samples as cards; retain a grayscale display and strong central objects. A static arrangement of five perspective-rotated cards is the minimum equivalent.

**Build:** Use a black stage with CSS perspective and horizontally arranged #27272a cards. Keep the middle nearly front-on and rotate the outer cards inward about their vertical axes; scale and overlap the farther cards behind. Center white original symbols in each card and place a small muted caption beneath. Tune perspective by eye to a shallow cylindrical arc rather than a flat tilted row.

### Icons

**Observed:** Marketing icons are sparse. Feature-list markers use white 10×10px checks or plus-like strokes at 2px with round caps inside 18px gray circles; the email action uses a black 12×12px outline envelope with 2px round strokes. Large decorative emblems are solid silhouettes, not ordinary interface icons.

**Transfer:** Use compact round-stroke icons only to clarify a list or action; use bold original silhouettes for the decorative artwork.

## Section recipes

How recurring sections are built.

### First screen: Sentence exhibition opening

**Observed:** A fixed 78px Charcoal canvas navigation bar sits above an all-charcoal first screen. The opening starts after a 118px top offset, then 86.4px of internal top space. A centered 1080px-wide sentence occupies about four 96px lines and most of the screen's width. The promise is white, one word uses Display italic, and two Inline object capsules interrupt the sentence; the endorsement continuation is dimmer but equally large. A single 18px support line sits below, followed by a centered pair of Primary button and Secondary button with an 8px gap, then a small qualification 16px lower. All of the headline, capsules, support, actions and qualification are visible within the first 900px. The main browser-and-phone product scene belongs below the fold, not behind the headline.

**Transfer:** Write a compact product promise and an equally large proof continuation, then thread original geometric object capsules through the sentence. If there are no product visuals, use simple monochrome rings and bars in those capsules and reserve an original schematic for the next room. Organization sales instead opens with the Device exhibition on black, a 56px mixed-font promise overlapping its lower area, two-line support and one yellow action.

**Avoid:** Do not replace the inline capsules with a giant hero screenshot, turn the endorsement into a small subtitle, or fill the first screen with a feature grid.

**Text style:** `display` — Suisse International 400 · 96px/1

### Introduction room

**Observed:** An Exhibition room uses 120px top padding, a centered Yellow marker, then a narrow multiline Section heading with Section italic emphasis. The headline is about 620px wide; a large 992×550px browser-and-phone composition is centered below with a substantial gap and can extend to the room's lower edge.

**Transfer:** Introduce the actual product experience with one editorial statement and one large coherent visual, not multiple small thumbnails.

**Text style:** `section-heading` — Suisse International 400 · 64.8px/0.9

### Human proof room

**Observed:** A two-column Exhibition room uses 6px padding and seam. A short proof label occupies the left; the Quote inset fills the right, with portrait zone, quotation and 12px attribution. The full room is much shorter than the main product chapters.

**Transfer:** Use one attributable reaction as a change of pace between large product scenes.

**Text style:** `quote` — Suisse International 400 · 24.2px/1.2

### Immersive benefit room

**Observed:** A Black gallery about 930px high places the Peripheral symbol field behind a centered message. The content starts deep within the room, around 312px from its top: Yellow marker, 48px pause, Section heading with an italic word, then a narrow Immersive support paragraph. A small horizontal strip of wordmarks can supply social proof near the bottom.

**Transfer:** Turn a key outcome into a visual pause; keep the central writing area unobstructed even when peripheral symbols are numerous.

**Text style:** `section-heading` — Suisse International 400 · 64.8px/0.9

### Split participation room

**Observed:** An Exhibition room uses two equal columns and a 6px seam. The left has 32px padding, Yellow marker, a two-line Split heading with inline italics, and a muted paragraph limited to 465px. The right is a nearly full-height Device exhibition image with 22px corners, occupying about half the room.

**Transfer:** Use this for a secondary audience, contribution pathway or distinct capability. Keep the image as substantial as the copy.

**Text style:** `split-heading` — Suisse International 400 · 37.7px/0.95

### Graphic closing strip

**Observed:** After the plan comparison, a 160px charcoal pause leads into the Monumental closing verb with the fading Closing category pill row. The word bleeds to both edges; this is a graphic sign-off, not a conventional footer with link columns.

**Transfer:** Close a general marketing narrative with a relevant action word and concise categories; adapt its position to the story rather than making the preceding section order fixed.

### Compact plan comparison

**Only for:** pricing comparisons

**Observed:** Three Plan cards use a 24px gutter and matching 491px heights. Titles are 28px muted gray, amounts only 18px with 12px billing text. Centered Billing switches precede 14px feature lists. Gray full-width actions align at the bottom; no bright recommended plan dominates.

**Transfer:** Present audience or usage differences without adopting the oversized-price conventions of a typical SaaS pricing table.

**Text style:** `plan-title` — Suisse International 400 · 28px/1.2

### Staggered editorial explanation

**Only for:** organization capability narratives

**Observed:** On black, three short 42.4px/1 paragraphs are staggered across two columns, right then left then right. Each column is about 619px wide, separated by 129.6px, with 30px between paragraph groups. Word-level contrast moves between dim and bright, making prose itself the visual object.

**Transfer:** Use a few concrete paragraphs to explain credibility or breadth before a deeper capability narrative.

**Text style:** `manifesto` — Suisse International 400 · 42.4px/1

### Stacked capability demonstration

**Only for:** organization capability narratives

**Observed:** Numbered capability cards become a sticky stack of broad two-column rooms. Successive cards darken and reduce in height from 720px to 648px. Each chapter pairs a short 36px headline with a small isolated demonstration on black: an object and action pills, collections, a search cluster or invitations.

**Transfer:** Explain distinct outcomes through compact illustrative interactions. Keep each demonstration centered with extensive negative space rather than showing every interface control.

**Text style:** `capability-heading` — Suisse International 400 · 36px/1.05

### Offer and personal close

**Only for:** organization sales

**Observed:** The Organization offer is a 343px-high yellow room with black copy, a white pill action and a right-aligned 60px amount. It is followed by an unboxed black contact section about 720px high: a 620px-wide centered question at 56px/1, a 48px gap, and one yellow email action, with about 200px above and below the content. The ending remains black with no conventional multi-column footer.

**Transfer:** Separate the explicit offer from the invitation to talk. Use the latter to remove a final practical objection without adding another feature list.

**Text style:** `sales-heading` — Suisse International 400 · 56px/1

## Page flow

**Storyline:** editorial promise → staged product proof → credibility → immersive outcome → audience or capability detail → commercial choice → graphic or personal close

### General product and membership landing page

1. **Promise** — Oversized mixed-font sentence with inline symbol capsules, an equally large endorsement clause and two compact actions.
2. **Product demonstration** — Large rounded introduction room with centered headline and browser-plus-phone scene.
3. **Social proof** — Short split testimonial room with one lighter quote inset.
4. **Outcome** — Black symbol-field room with a centered benefit statement and a small proof strip.
5. **Secondary pathway** — Equal-column copy and device photograph introduce another way to participate.
6. **Pricing** — Three subdued equal cards with small amounts, billing switches and aligned gray actions.
7. **Graphic close** — Monumental dim verb crossed by a fading row of category pills.

**Transfer:** Use this as the default landing-page grammar. Keep the sentence-led opening, staged proof and graphic devices, while choosing only the narrative blocks relevant to the new product.

### Organization sales and shared-access explanation

1. **Audience promise** — Tablet-on-plinth photograph fills a black opening; mixed-font headline overlaps the lower image above support and one yellow action.
2. **Credibility** — Three large paragraphs alternate across a two-column black field.
3. **Capability chapters** — Numbered sticky split cards pair outcome headlines with isolated interaction illustrations.
4. **Product breadth** — A perspective carousel presents original objects on black.
5. **Quantified proof** — Large gray symbol-field room with a yellow label and mixed-font scale claim.
6. **Offer** — One broad yellow panel contrasts the promise and white action against a separate large price.
7. **Objection handling and close** — Centered question and one email pill on black, with expansive vertical space.

**Transfer:** Use the darker, wider variant for an organization buyer who needs deeper capability explanation and a single shared-access offer. Preserve the personal closing invitation rather than adding a dense FAQ footer.

## Writing

Cultured confidence with a collector's specificity. The product is presented as unusually comprehensive, but its breadth is grounded in concrete quantities, research and practical actions rather than technical bravado.

**Do not copy:** Do not reuse LogoArchive's name, marks, customer identities, collection artwork, quotations, archive counts, prices, historical claims or superlatives as facts about a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your. Product-led declarative statements alternate with direct action verbs; organization copy explicitly includes the buyer's wider group.
- **Rhythm:** Short declarative headlines, often one sentence over two or three lines; longer informational sentences sit beneath them. The opening can extend into a second large proof sentence. Sentence case and periods dominate, with questions reserved for the personal close.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A definitive category promise with one italicized emphasis word, followed by a proof sentence. | About 8–20 words across the promise and continuation. | “The only logo book you’ll ever need. As used by the world’s best design teams.” |
| Supporting line | Concrete quantity plus a short statement of ongoing value. | Two compact clauses. | “Featuring 5500 carefully curated logos. New logos added daily.” |
| Section marker | A compact sentence-case description of the kind of value about to be shown. | About 4–8 words. | “A new format of logo inspiration”<br>“A design resource unlike any other” |
| Capability heading | Lead with an ordinary verb and name the user's practical outcome. | About 7–16 words. | “Bookmark and create collections for lectures, workshops and tasks.” |
| Primary action | Direct verb, with audience or price qualification only when it reduces uncertainty. | About 2–8 words. | “Get started for only £8.22/month”<br>“Get institutional access” |
| Closing invitation | A short question followed by a plain invitation to speak. | One question and one sentence. | “Have questions? Speak to us about bringing [Brand] to your institution.” |

**Words and phrasing to use:** carefully; discover; access; research; collections; remarkable; your; one subscription

**Avoid:** revolutionary; game-changing; supercharge; hustle; AI-powered everything; excessive exclamation marks

**Rules:**

- Pair a broad promise with a verifiable detail in the support copy.
- Use italics to emphasize a meaningful word, not an entire claim.
- Write capability headlines as actions readers can perform.
- Let plan names describe audiences rather than inventing a playful tier universe.
- Keep billing conditions adjacent to the amount in compact language.

## Do's and Don'ts

### Do

- Use 96px/1 regular grotesk text for the sentence-led opening.
- Match inline serif emphasis to its neighboring sans size.
- Keep 28px room corners and 22px inset corners visibly related.
- Separate default rooms by 24px of exposed charcoal.
- Use 48px action pills with 14px medium-weight text.
- Keep marker labels at 12px/1.2 with 4px corners.
- Use 6px seams for split copy-and-media rooms.
- Let original monochrome symbols echo through inline capsules and a peripheral field.

### Don't

- Do not turn regular headings into 700-weight display type.
- Do not add negative tracking to a system built on normal letter spacing.
- Do not substitute colorful gradients for the black and charcoal room surfaces.
- Do not give every card a shadow; neutral fills supply the depth.
- Do not use a bright recommended-plan card in the subdued three-plan comparison.
- Do not inflate ordinary plan prices beyond their 18px supporting role.
- Do not round the tiny yellow markers into action pills; keep their 4px corners.
- Do not add a conventional multi-column footer where the narrative calls for a graphic sign-off or a single contact invitation.

## Motion and responsive

### Motion

**Observed:**

- Actions and surfaces declare 0.15s ease-in-out transitions; particular hover and focus appearance changes are not specified.
- Two looping animations declare 60s ease-in-out infinite normal playback. Other decorative animations declare alternating ease-in-out infinite playback without a resolved numeric duration.
- Numbered organization capability cards use sticky positioning and visibly accumulate into a layered stack.

**Transfer:**

- Keep the inline-symbol strips clipped inside their pill windows as they move.
- Use motion to reveal or circulate the same restrained monochrome objects, not to introduce additional visual effects.
- For the capability narrative, preserve the sense of successive cards accumulating rather than replacing it with an unrelated slider.

**Unknown:**

- Exact action-state colors, focus-ring styling and property-level transition targets.
- Timing and choreography of word-by-word contrast changes and most decorative movement.

### Responsive

**Observed:**

- Shared CSS width breakpoints include 440px, 600px, 680px, 768px, 800px, 1024px and 1440px; organization styles also include 430px, 480px and 900px.
- Section headings and several support recipes use viewport formulas; organization headings, offer amounts and padding use clamps.

**Transfer:**

- Retain inline serif emphasis and the object-capsule idea when wrapping the opening sentence on a narrow screen; reduce capsule dimensions in proportion to the heading as a design adaptation.
- Stack equal copy/media halves and pricing columns when their contents no longer fit, preserving the narrow inset seam and related corner radii.
- Fit the monumental closing word with its SVG viewBox rather than shrinking it into an ordinary footer label.

**Unknown:**

- Actual narrow-screen layouts, capsule sizing rules and navigation behavior.
- No fluid rule is established for the 96px default opening or the 42.4px staggered paragraphs.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
