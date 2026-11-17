# Dashlane — espresso and electric signals

## Overview

A warm, dark technical style that makes enterprise software feel protective rather than forbidding. Espresso brown, soft white, icy mint and restrained periwinkle frame light grotesk headlines, monospaced labels and layered translucent interface illustrations. The composition is spacious around major promises and more structured inside proof cards, with selective workplace photography and fine drafting-grid details.

### Essentials

- Light headlines carry a single mint signal: Saans 300 at 72px/1.1 for the opening, 56px/1.1 for section leads and 0.01em positive tracking; emphasize a meaningful word without changing weight.
- The opening pairs a narrow, multiline promise with an equally substantial product stage: two 592px columns separated by 80px, 18px/27px supporting copy and actions 40px below it.
- Actions are compact instruments, not pills: 4px corners, 8px 16px padding and 16px/24px medium text; mint fill plus mint outline in the content, periwinkle equivalents in navigation.
- The page remains overwhelmingly espresso #200f0a: color occupies isolated words, actions, fine bars and purple proof panels rather than alternating bright section fills.
- Product imagery is layered like transparent instrumentation: offset window outlines, muted brown and violet panes, mint signals and fine pale edges. Include this depth device even without existing product media by drawing a few representative panels.
- Technical markings temper the soft typography: uppercase mono labels at 16px/1.1 with 0.06em tracking, faint square grids and thin warm borders; quantified proof uses 100px light numerals above narrow outlined bars.
- A particle-ribbon callout supplies the atmospheric signature: mint specks curve behind an 8px-radius outlined panel with a 48px light headline and floating violet planes; reproduce this motif with SVG particles and simple translucent quadrilaterals.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal mint | `#a2f6f5` | `--color-mint` | text, action, link, border, accent | Emphasized words, content actions, small icons and technical line art. |
| Espresso canvas | `#200f0a` | `--color-canvas` | background, surface | Dominant continuous page canvas, including the footer and transparent card interiors. |
| Proof violet | `#2b2538` | `--color-violet` | surface | Testimonial cards and restrained feature-panel backing. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navigation periwinkle | `#858df9` | `--color-indigo` | action, text, border, accent | Navigation actions, active product tabs and selected proof-bar outlines. |
| Deeper periwinkle | `#6c74df` | `--color-indigo-deep` | accent, background, border | Progress strips and navigation interaction color; pricing recommendation banner. |
| Lavender label | `#b6bbfb` | `--color-lavender` | text, border | Small publication and novelty badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm pale edge | `#e3ccc0` | `--color-edge` | border | Fine outlines around proof cards, product stages and the final callout. |
| Action ink | `#1d0e09` | `--color-action-ink` | text | Dark labels on filled mint and periwinkle buttons. |
| Soft violet | `#34283a` | `--color-soft-violet` | surface | Muted progress-bar fills and tinted technical cards. |
| Warm mid-gray rule | `#796f6c` | `--color-tab-rule` | border | Baseline behind product tabs. |
| Muted warm gray | `#a69f9d` | `--color-muted` | text | Footer fine print and secondary legal links. |
| Warm white | `#fcfaf9` | `--color-text` | text | Headlines, body copy, navigation and active pagination marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| paired product capability panels and announcements | Warm technical taupe | `#4d3f3b` | `--color-taupe` | surface | Secondary capability-panel backing and announcement strip. |
| FAQ sections | Cool pale rule | `#e2e4e8` | `--color-faq-rule` | border | Accordion row separators. |

## Typography

- **Saans** — All marketing headings, paragraphs and action labels. Open, contemporary grotesk with light strokes, broad counters and a relaxed but businesslike tone. If unavailable, use **Public Sans**. Use 300 for text and headings, 500 for actions; preserve line breaks and positive tracking. Font stack: "Saans", "Public Sans", sans-serif.
- **SaansMono** — Eyebrows, tab labels, footer categories and small technical markings. Plain monospaced capitals that read like instrument labels rather than code. If unavailable, use **IBM Plex Mono**. Use light cuts for eyebrows and regular for footer categories. Font stack: "SaansMono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Saans | 300 | 100px | 1.1 | 0.01em | Large quantified proof in three outlined cards. |
| display | Saans | 300 | 72px | 1.1 | 0.01em | Opening promise; mint emphasis inherits the same recipe. |
| heading-lg | Saans | 300 | 56px | 1.1 | 0.01em | Primary section leads, centered product introductions and trust statements. |
| heading | Saans | 300 | 48px | 1.1 | 0.01em | Split editorial sections, product-stage titles and closing callout. |
| quote | Saans | 300 | 28px | 1.2 | 0.01em | Customer quotations in violet panels. |
| body-lg | Saans | 300 | 18px | 1.5 | 0.02em | Hero support and spacious explanatory paragraphs. |
| body | Saans | 300 | 16px | 1.5 | 0.01em | Feature descriptions and plan details. |
| eyebrow | SaansMono | 300 | 16px | 1.1 | 0.06em, uppercase | Section labels and proof-strip captions. |
| action | Saans | 500 | 16px | 1.5 | normal | Filled buttons, outlined buttons and action links. |
| small-link | Saans | 300 | 14px | 1.5 | 0.01em | Navigation and footer links. |
| footer-label | SaansMono | 400 | 14px | 1.1 | 0.06em, uppercase | Mint footer categories. |
| tab | SaansMono | 300 | 14px | 1.257 | 0.06em, uppercase | Product-stage tab strip. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product deep-dive pages | feature-heading | Saans | 300 | 36px | 1.1 | 0.01em | Large capability cards and staggered feature mosaic. |
| pricing and product comparison pages | card-heading | Saans | 300 | 28px | 1.1 | 0.01em | Plan names, comparison categories and compact feature-card titles. |
| press and resource grids | article-title | Saans | 300 | 28px | 1.071 | 0.01em | Multiline editorial resource titles. |
| FAQ sections | faq-question | Saans | 300 | 24px | 1.1 | 0.02em | Expandable product questions. |
| pricing FAQs | pricing-question | Saans | 500 | 24px | 1.1 | 0.02em | Heavier question treatment for buying decisions. |
| FAQ sections | faq-answer | Saans | 300 | 16px | 1.625 | 0.01em | Long-form answers under expanded questions. |
| press and resource grids | publication-label | SaansMono | 300 | 12px | 1.1 | 0.01em, uppercase | Small outlined publication badge. |

**Notes:**

- Large type stays light; size, line breaks and one mint phrase create hierarchy instead of bold weight or tight negative tracking.
- Use 0.01em tracking on display and ordinary text, 0.02em on larger supporting copy and FAQ questions, and 0.06em on technical labels.
- The 48px recipe also serves price figures; this is a shared size, not a heavier numeral style.

## Layout

**Density:** Airy between narrative blocks, structured and compact within bordered cards and navigation.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Action icon gaps and button vertical padding. |
| 12px | Footer link separation and tab bottom padding. |
| 16px | Paired-action spacing and answer inset. |
| 20px | Heading-to-copy spacing and three-card gutters. |
| 24px | Paired capability-panel gutters and mosaic gaps. |
| 32px | Card padding, eyebrow-to-title separation and internal quote gaps. |
| 40px | Copy-to-action spacing and space before proof cards. |
| 56px | Desktop gaps between product tabs. |
| 64px | Default section vertical padding and quotation horizontal padding. |
| 80px | Desktop side padding, split-column gaps and more spacious section starts. |
| 120px | Major chapter starts and footer vertical padding. |

### Containers and grids

- **marketing-container**: max width 1440px · 12 columns · gap 20px · side padding 80px. Centered desktop frame; full-width canvas runs behind a 12-column alignment grid.
- **opening-split**: 2 columns · gap 80px. Equal copy and media columns, each about 592px at desktop.
- **inset-editorial**: max width 1063px · 2 columns · gap 80px. Inset customer stories, announcement scenes and trust illustrations; roughly 485–492px per side.
- **proof-grid**: 3 columns · gap 20px. Equal outlined statistics cards across the main frame.
- **testimonial-rail**: max width 803px · gap 40px. Card width in an intentionally right-bleeding horizontal rail, with the next quote partially visible.
- **integration-grid** (only for product ecosystem sections): 4 columns · gap 20px. Two rows of small logo cards.
- **resource-grid** (only for press and resource sections): 3 columns · gap 32px. Image-led resource cards with unboxed copy below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | cards-and-navigation | 8px |
|  | product-stage | 12px |
|  | round-controls | 50% |
| press and resource grids | badges | 2px |
| pricing pages | selector | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Espresso canvas · level 0

**Use:** Continuous background throughout the marketing story.

**CSS:** `background: #200f0a; color: #fcfaf9`

**Observed:** Sections are divided by rhythm and content rather than repeated changes of background.

**Transfer:** Keep the long dark field intact while varying scale and media.

#### Outlined panel · level 1

**Use:** Stats, compact proof and product containers.

**CSS:** `background: transparent; border: 1px solid #e3ccc0; border-radius: 8px; box-shadow: none`

**Observed:** The page canvas shows through the panel; the edge is the primary grouping device.

**Transfer:** Use for bounded facts without turning the page into a filled-card dashboard.

#### Violet proof panel · level 1

**Use:** Customer quotations.

**CSS:** `background: #2b2538; border: 0.5px solid #e3ccc0; border-radius: 8px; box-shadow: none`

**Observed:** A warm pale hairline keeps a dark violet panel legible against brown.

**Transfer:** Reserve this strong fill for human proof and selected product chapters.

#### Technical grid backing · level 1

**Use:** Subtle depth on graphic panels and the final callout.

**CSS:** `background-color: #200f0a; background-image: linear-gradient(rgba(227,204,192,0.07) 1px, transparent 1px), linear-gradient(90deg, rgba(227,204,192,0.07) 1px, transparent 1px); background-size: 48px 48px`

**Observed:** Fine square grids fade into the canvas instead of covering an entire page.

**Transfer:** Mask the grid toward one corner or one half of a panel; keep text in the quiet region.

#### Paired capability surfaces · level 1

**Only for:** product deep-dive pages

**Use:** Two substantial image-led product capabilities.

**CSS:** `background-color: #2b2538; border: 1px solid #e3ccc0; border-radius: 8px; padding: 40px 40px 80px`

**Observed:** The second panel uses warm taupe; both carry a fading grid in the lower-right corner.

**Transfer:** Use contrasting muted backings for complementary capabilities, not bright category colors.

## Components

### Navigation bar

**Use:** Persistent site orientation and conversion actions.

**CSS:** `background: rgba(54,39,35,0.824); border-radius: 8px; padding: 16px 20px; max-width: 1280px`

**Text style:** `small-link` — Saans 300 · 14px/1.5 · tracking 0.01em

**Observed:** Logo left, six compact links in the middle, outlined demo then filled sales action at right. Header actions use periwinkle rather than mint. A small utility row sits above at the opening; on scroll the bar becomes a pale-outlined floating strip.

**Transfer:** Use the same compressed horizontal hierarchy with fewer links if necessary.

### Primary button

**Use:** Primary conversion or a concrete next step.

**CSS:** `background: #a2f6f5; color: #1d0e09; border-radius: 4px; padding: 8px 16px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — Saans 500 · 16px/1.5

**Observed:** Content buttons are mint and typically 40–43px tall; the companion outline sits 16px away. Navigation swaps the fill to periwinkle.

**States:** Declared: hover opacity 0.8, background #609493, color #200f0a, no underline; active background #61827f and color #200f0a. Navigation fill hover and active use #505595.

### Outline button

**Use:** Secondary conversion beside a filled action.

**CSS:** `background: transparent; border: 1.5px solid #a2f6f5; color: #a2f6f5; border-radius: 4px; padding: 8px 16px`

**Text style:** `action` — Saans 500 · 16px/1.5

**Observed:** Matches the filled button's compact rectangle. In navigation both label and border are periwinkle.

**States:** Declared: hover opacity 0.8, background #3a3d39 and mint border, no underline; active background #3a3d39. Navigation hover uses border and text #6c74df with background #48416a.

### Arrow link

**Use:** Lightweight continuation inside feature content.

**CSS:** `color: #a2f6f5; padding: 8px 16px 8px 0px; display: flex; align-items: center; gap: 8px`

**Text style:** `action` — Saans 500 · 16px/1.5

**Observed:** Mint text followed by a small right arrow, aligned to the paragraph edge rather than a button-shaped enclosure.

**Transfer:** Name the destination or action; keep the arrow subordinate.

### Statistic card

**Use:** Quantified evidence presented as an easily compared trio.

**CSS:** `border: 1px solid #e3ccc0; border-radius: 8px; padding: 32px`

**Text style:** `stat` — Saans 300 · 100px/1.1 · tracking 0.01em

**Observed:** Light oversize percentage first, an 18px explanation beneath, then a narrow outlined progress bar at the bottom. Three cards share equal height; violet and mint bar tints distinguish the measures.

**Transfer:** Use verified figures with short explanations and proportional bar lengths.

### Testimonial card

**Use:** Customer validation in a horizontally clipped rail.

**CSS:** `background: #2b2538; border: 0.5px solid #e3ccc0; border-radius: 8px; padding: 44px 64px 64px; max-width: 803px; margin-right: 40px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quote` — Saans 300 · 28px/1.2 · tracking 0.01em

**Observed:** Customer logo, generous quotation, then a small round portrait with name and smaller role. A partial next card, circular arrow controls and small dots make the rail apparent. A full-width executive variant places attribution at the right.

**Transfer:** Keep attribution visibly human and the quotation spacious rather than squeezing several into tiny cards.

### Product tabs

**Use:** Switch among product demonstrations inside a single bordered stage.

**CSS:** `color: #fcfaf9; padding: 0px 20px 12px; border-bottom: 6px solid #858df9`

**Text style:** `tab` — SaansMono 300 · 14px/1.257 · tracking 0.06em · uppercase

**Observed:** Active tab has a thick periwinkle underline over a fine gray baseline. The row sits inside a 12px-radius outlined container, above a text-left/media-right scene; inactive tabs retain only the shared baseline.

**Transfer:** Use short functional labels, preserving the contrast between mono labels and large light content titles.

### Footer directory

**Use:** Dense navigational ending on the same dark canvas.

**CSS:** `background: #200f0a; padding: 120px 32px; max-width: 1344px; color: #fcfaf9`

**Text style:** `small-link` — Saans 300 · 14px/1.5 · tracking 0.01em

**Observed:** Five desktop columns organize multiple groups with mint uppercase mono category labels and 12px gaps between links. The last column carries downloads and a two-row social grid of 36px outlined circles. Muted legal text sits well below the directory.

**Transfer:** Group by reader task rather than flattening all destinations into one list.

### Closing call panel

**Use:** Final conversion within the atmospheric particle ribbon.

**CSS:** `background-color: #200f0a; border: 1px solid #e3ccc0; border-radius: 8px; padding: 20px 20px 20px 96px; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 64px; align-items: center`

**Text style:** `heading` — Saans 300 · 48px/1.1 · tracking 0.01em

**Observed:** An inset panel about 1051px wide and 372px tall holds a short headline and paired actions on the left, violet planes on the right; particle art extends well outside its boundary.

**Transfer:** Give the new product a similarly tangible final invitation rather than a plain centered text strip.

### FAQ row

**Only for:** FAQ sections

**Use:** Answer objections without building another card grid.

**CSS:** `border-bottom: 1px solid #e2e4e8; color: #fcfaf9; width: 600px`

**Text style:** `faq-question` — Saans 300 · 24px/1.1 · tracking 0.02em

**Observed:** Question left, mint plus or minus at the far right; first answer is open. Closed rows are typically 118px tall. Answers use the faq-answer recipe. Pricing questions use pricing-question instead.

**Transfer:** Place the section title in the left column and the accordion in the right; preserve the asymmetric empty space.

### Plan card

**Only for:** pricing pages

**Use:** Compare packages before the detailed feature matrix.

**CSS:** `border: 1px solid #e3ccc0; border-radius: 8px; padding: 32px; max-width: 448px`

**Text style:** `card-heading` — Saans 300 · 28px/1.1 · tracking 0.01em

**Observed:** Mono product label, plan name, short benefit, 48px mint price, billing qualifier, full-width filled action, centered text action, then bullets. A tailored tier uses soft violet and a periwinkle banner above its edge.

**Transfer:** Keep pricing qualifiers close to the figure and align action rows across tiers.

### Publication badge

**Only for:** press and resource grids

**Use:** A small source label between the thumbnail and article title.

**CSS:** `background: #34283a; color: #b6bbfb; border: 1px solid #b6bbfb; border-radius: 2px; padding: 4px 8px`

**Text style:** `publication-label` — SaansMono 300 · 12px/1.1 · tracking 0.01em · uppercase

**Observed:** Tiny lavender uppercase label precedes a 28px multiline title; it does not become a large pill.

## Imagery and graphics

### Layered interface stage

**Use:** Opening product object and tabbed demonstrations.

**Observed:** Brown-tinted interface windows occupy roughly half a split opening. Several thin outlined windows step upward behind the front pane, with violet cards and mint labels drawing attention to one result. Lower product stages enlarge and clip the interface against the right edge.

**Transfer:** Draw a simplified representation of the new product's real workflow, retaining a believable hierarchy and one foreground result; detailed application chrome is less important than depth and restraint.

**Build:** Layer three rounded rectangles with 12–24px upward and rightward offsets and rgba(227,204,192,0.25) outlines. Fill the front pane with espresso at partial opacity, place a small violet result panel over it and use mint only on the key signal. Fade the lower edges into the canvas.

### Particle ribbon and violet planes

**Use:** Signature atmospheric callout.

**Observed:** A mint particle band enters from the lower-left, curls underneath the central panel and rises toward the upper-right. It is airy granular light, not a solid neon streak. Two pairs of tall violet planes float on the right of the panel and fade downward; a faint grid occupies its left.

**Transfer:** Retain the particle ribbon and simple planes around a new closing message, even when there is no product-specific artwork.

**Build:** Use an SVG viewBox 0 0 1440 644. Scatter small circles around two curved paths crossing behind the panel, varying radius about 0.5–1.5px and mint opacity 0.08–0.35; taper density at the edges. Inside the right half, layer two pairs of skewed quadrilaterals filled with violet-to-transparent gradients. Keep particles behind the opaque panel, and use a masked 48px grid on its left.

### Drafted technical illustration

**Use:** Abstract trust, innovation and architecture explanations.

**Observed:** Fine mint and pale outlines form familiar conceptual objects such as a certificate, light bulb or cloud lock. They float in a sparse perspective frame with corner brackets, small crosses, subtle greenish translucent planes and occasional glow. Art typically balances a 485–592px text column.

**Transfer:** Choose one simple object meaningful to the new product and redraw it as an instrument diagram, not a glossy stock 3D icon.

**Build:** Construct the object in SVG with 1–2px mint strokes. Add open pale corner brackets and four small registration crosses. Behind it place a skewed quadrilateral with a mint-to-transparent fill at low opacity; selectively blur a duplicate stroke for a soft local glow. Leave most of the art transparent.

### Workplace and customer photography

**Use:** Customer stories and product capability chapters.

**Observed:** Customer stories use a clean rectangular location image with a discreet white customer mark. Product chapters use close, candid people working at screens, natural office light or cool monitor reflections, and softly blurred backgrounds; images are rounded but not framed like browser windows.

**Transfer:** Use real people engaged with the new product's context, with restrained color grading and no exaggerated celebratory poses.

### Staggered photo and benefit mosaic

**Only for:** product deep-dive pages

**Use:** An expansive differentiation chapter.

**Observed:** 520px by 326px photos and muted violet, taupe or olive text tiles form an offset wall that bleeds beyond the content width. Tiles have 8px corners and 24px gaps, with text tiles carrying fine grids and one small outlined symbol.

**Transfer:** Alternate real contextual photos with a few concise benefits; preserve the stagger and edge bleed rather than reducing the section to a conventional even grid.

**Build:** Arrange equal rectangular tiles in offset flex rows with 24px gaps; shift neighboring rows horizontally, allowing edge tiles to leave the viewport. Build text tiles from the Outlined panel, tinted backings and a lower-right masked grid. Add a simple SVG target or layered-sheet symbol.

### Announcement glow card

**Only for:** new capability announcements

**Use:** A compact visual beside an inset editorial introduction.

**Observed:** A dark horizontal card has a softly glowing mint rounded central label, violet atmospheric edges, a faint grid and small corner brackets.

**Transfer:** Use a short new-capability label rather than illustrating an entire workflow.

**Build:** Place a dark 8px-radius label over a violet translucent radial glow, add a mint low-opacity blurred duplicate behind the label, then overlay fine square lines and two open corner brackets.

### Icons

**Observed:** Small action and navigation glyphs are mainly 16px or 20px solid SVGs in mint or warm white. Large technical icons are delicate outlines. Carousel controls use 36px line-arrow art inside 48px circles; social controls use 36px mint-outlined circles.

**Transfer:** Use compact, simple arrows and checks for interaction, reserving thin outlined conceptual symbols for feature illustrations. Avoid mixing heavy pictograms into the drafted artwork.

## Section recipes

How recurring sections are built.

### First screen: Split product promise

**Observed:** The default opening is a warm dark field beneath a two-level header. A small announcement strip can add 44px above the utility links and main navigation. The main stage uses 64px vertical padding in a 1440px frame with 80px sides: equal copy and product columns separated by 80px. The left column starts with a compact announcement chip, then a three-line 72px/1.1 light headline with the leading verb in mint, an 18px support paragraph 20px below and paired compact actions 40px after the copy. The right object is a 592px by 429px layered interface scene, optically centered against the copy. Within 900px the header, full promise, support, actions and main object are visible; the centered mono trust caption and beginning of the customer-logo strip appear at the bottom, with the later proof content below.

**Transfer:** Keep the split promise as the ordinary landing-page default. Without finished media, create a simplified Layered interface stage with one meaningful result. Product deep-dives can center the 72px promise above a wide 1063px demonstration that continues below the fold; pricing opens with a centered title, compact segmented selector and three plan cards; a differentiation page pairs the promise with a Drafted technical illustration.

**Avoid:** Do not replace the object with an empty rectangle or turn the hero into a giant centered headline with a tiny decorative icon. Do not bold the mint word or color the entire promise.

**Text style:** `display` — Saans 300 · 72px/1.1 · tracking 0.01em

### Technical section lead

**Observed:** Use a 16px uppercase mono eyebrow, 32px separation and a 56px light headline; a single mint word can sit inline. Supporting copy follows at about 20px and a continuation action at 32–40px. Center this grouping over a demonstration, or align it left for a capability chapter.

**Transfer:** Make each chapter about one outcome, using the mono line as its category rather than repeating the headline.

**Text style:** `heading-lg` — Saans 300 · 56px/1.1 · tracking 0.01em

### Quantified proof trio

**Observed:** A left-aligned 56px heading and mint action lead into three Statistic cards separated by 20px. Each holds a 100px number, an 18px explanation and an outlined progress bar. The enclosing section uses 64px padding.

**Transfer:** Use comparable verified metrics; this device can appear wherever numeric proof strengthens the story.

**Text style:** `stat` — Saans 300 · 100px/1.1 · tracking 0.01em

### Tabbed product theatre

**Observed:** Centered section introduction above a 12px-radius bordered demonstration stage. Product tabs run across its top; the active underline is 6px periwinkle. Beneath, a 48px title, short paragraph and Arrow link sit left while the interface illustration fills and clips at the right.

**Transfer:** Demonstrate distinct workflows in one substantial stage, not a row of unrelated thumbnails.

### Inset editorial pair

**Observed:** A roughly 1063px inset two-column composition uses an 80px gap, 48–56px light heading, 18px supporting copy and actions after 40px. The adjacent image can be a customer location, an announcement or technical illustration. Content is vertically centered; section padding is 64–80px.

**Transfer:** Use this quiet pair to vary scale between broader card sections.

### Human proof rail

**Observed:** A 56px left-aligned heading is balanced by circular previous/next controls on the right. Testimonial cards form a right-bleeding rail with one complete card and part of the next, plus tiny pagination dots below.

**Transfer:** Let the partial card communicate continuation; use the full-width executive quote variant for a single authoritative statement.

### Atmospheric final invitation

**Observed:** Closing call panel sits within the Particle ribbon and violet planes. Its headline is 48px with a mint phrase and paired actions below. The bordered panel is inset while granular artwork spans nearly the full page width.

**Transfer:** Close with a short product invitation and the same tactile technical atmosphere, without adding a large sales form.

### Directory ending

**Observed:** The Footer directory follows the atmospheric callout on marketing and product pages; pricing moves directly from FAQs to the directory. All endings retain the brown canvas, five link columns, mint mono labels, download/social area and muted legal row.

**Transfer:** End with useful navigation rather than a new visual theme; preserve the spacious gap before the small legal line.

### Comparison and buying tools

**Only for:** pricing pages

**Observed:** Three Plan cards follow the centered title and pill-shaped audience selector. The tailored plan gets a violet backing and periwinkle banner. Below, a long table groups features beneath 28px category headings; 65px rows use pale 0.5px separators, circled mint checks, dashes and occasional text values. Plan headings and outlined actions remain aligned over the value columns.

**Transfer:** Prioritize decision clarity: explain packages first, then offer a structured detailed comparison.

### Split objection handling

**Only for:** FAQ sections

**Observed:** A 48px section title occupies the left half; 600px FAQ rows occupy the right, separated from the title by an 80px column gap. The first answer is expanded; subsequent rows use mint plus marks and thin cool separators.

**Transfer:** Use questions that match actual evaluation concerns and leave the left column relatively spare.

### Editorial resource trio

**Only for:** press and resource sections

**Observed:** A 48px heading and small action share the upper row, then three 400px-wide items with 32px gaps. Each has a 400px by 232px thumbnail, Publication badge, 28px multiline title and mint continuation link.

**Transfer:** Allow thumbnail variety while keeping the typographic sequence consistent.

## Page flow

**Storyline:** Promise → tangible product view → evidence → capability chapters → trust and objections → invitation and directory, adapted to the page's decision task.

### Broad marketing landing page

1. **Promise** — Split product promise with a layered interface scene.
2. **Social proof** — Centered mono trust caption and horizontal customer logos.
3. **Quantified proof** — Three oversized metric cards and a supporting action.
4. **Product demonstration** — Centered introduction and tabbed product theatre.
5. **Capability chapters** — Three technical benefit columns with a periwinkle progress strip.
6. **Customer proof** — Inset customer story followed by the human proof rail.
7. **Trust** — Split statement and certification artwork.
8. **Closing call** — Particle-ribbon invitation followed by the directory ending.

**Transfer:** Balance tangible product imagery with numeric and human proof; vary inset pairs, broad stages and sparse chapter headings.

### Package selection and purchase evaluation

1. **Pricing** — Centered title, audience toggle and three plan cards.
2. **Detailed comparison** — Grouped long-form feature matrix with aligned plan actions.
3. **Social proof** — Human proof rail.
4. **Objection handling** — Split FAQs with a contact link.
5. **Directory** — Footer directory directly after FAQs, without an atmospheric conversion panel.

**Transfer:** Let pricing and comparison do the work; keep visual spectacle subordinate to package clarity.

### Differentiation and institutional credibility

1. **Promise** — Split headline and mint drafted concept illustration.
2. **Differentiation** — Three technical pillars under a centered heading.
3. **New capability** — Inset announcement glow card.
4. **Product demonstration** — Centered promise and tabbed workflow theatre.
5. **Trust** — Drafted interstitial, full-width executive quote and illustrated proof list.
6. **External validation** — Awards pairing and editorial resource trio.
7. **Closing call** — Particle-ribbon invitation and footer directory.

**Transfer:** Translate abstract credibility into diagrams, attributable statements and external validation rather than a wall of assertions.

### Flagship product explanation

1. **Promise** — Centered two-line headline with mint adjective, paired actions and a wide layered demonstration.
2. **Differentiation** — Four outlined before-to-after benefit cards.
3. **New capability** — Inset announcement scene.
4. **Capability chapters** — Paired image-led cards with muted violet and taupe backing.
5. **Social proof** — Human proof rail.
6. **Differentiation** — Staggered photo and benefit mosaic.
7. **Ecosystem proof** — Four-column integration-logo grid.
8. **Trust** — Inset text and large drafted architectural illustration.
9. **Objection handling** — Split FAQ section.
10. **Closing call** — Particle-ribbon invitation and footer directory.

**Transfer:** Use the centered opening for a product with enough interface depth to support a wide demonstration; keep the offset mosaic scoped to a substantial product story.

## Writing

Assured, practical and technically fluent. The tone combines preventive confidence with plain-language outcomes, softening complex enterprise ideas through short contrasts rather than jokes or alarmism.

**Do not copy:** Do not reuse Dashlane or Omnix names, logos, proprietary illustrations, customer marks, quotations, prices, percentages, patent counts, certifications or leadership claims. Replace these with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader and their organization as you and your. Use we for accountable product commitments and the product name for concrete capabilities.
- **Rhythm:** Short promise-led headlines, often 3–8 words, alternate with one or two explanatory sentences. Paired clauses and before-to-after contrasts create momentum; labels and actions remain terse.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct action or leadership promise with one meaningful emphasized phrase. | 3–9 words | “Prevent credential breaches”<br>“The proactive credential security platform” |
| Section lead | Two compact outcomes, or a familiar phrase turned into a concrete proof claim. | 4–8 words | “Protect more. Manage less.”<br>“The proof is in the patents” |
| Supporting line | Start with a reader problem or action, then explain the mechanism without a jargon pileup. | 18–35 words | “Provide each employee with an encrypted vault for every login, keeping enterprise credentials secure on any device.” |
| Comparison title | From an inadequate old mode to a more useful new one. | 4–9 words | “From manual to automated”<br>“From reactive to real-time” |
| Primary action | Verb plus concrete destination or sales task. | 2–4 words | “Contact Sales”<br>“Request a demo”<br>“See customer stories” |
| Eyebrow | A brief chapter category rather than another persuasive sentence. | 1–4 words | “customer story”<br>“introducing” |

**Words and phrasing to use:** proactive; day one; visibility; protect; secure; continuous; real-time; from … to …; trusted; find and fix

**Avoid:** revolutionary magic; effortless everything; fear-heavy breach rhetoric; playful hacker slang; vague transformation superlatives

**Rules:**

- Tie a broad promise to a visible mechanism or proof point nearby.
- Use benefit contrasts to explain change, not lengthy competitive attacks.
- Let a specific action label finish a paragraph; avoid repeating the same sales sentence in every section.
- Reserve leadership and first-to-market language for claims that can be supported.

## Do's and Don'ts

### Do

- Keep the primary display at 72px, weight 300, with 1.1 line height and 0.01em tracking.
- Use 80px desktop side padding and an 80px gap for split scenes.
- Preserve 4px action corners against 8px card corners and 12px product-stage corners.
- Keep content actions mint and persistent navigation actions periwinkle.
- Include the fine-grid, translucent-panel depth language alongside the atmospheric particle motif.
- Use 100px numerals in spacious proof cards with short captions and slender bars.
- Retain the partial next testimonial at the right edge and small pagination below.
- Use uppercase mono category labels to organize both technical chapters and the footer.

### Don't

- Do not shift the continuous canvas to pure black or alternate every section with white.
- Do not use bold 700-weight display typography or compressed negative tracking.
- Do not convert the ordinary rectangular actions into fully rounded pills.
- Do not paint whole marketing sections mint; preserve it as a signal against espresso.
- Do not add elevation shadows to every card; thin pale edges provide separation.
- Do not make the interface art bright white, sharply isolated or as busy as a full application screenshot.
- Do not replace the granular ribbon with a thick solid neon swoosh.
- Do not force the dense pricing table, publication badges or staggered photo wall into every ordinary landing page.

## Motion and responsive

### Motion

**Observed:**

- Actions declare color-related transitions of 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Navigation declares padding and background-color transitions of 0.3s cubic-bezier(0.4, 0, 0.2, 1).
- The announcement chip declares a 15s linear infinite animation; a logo strip declares a 60s linear infinite slide.

**Transfer:**

- Keep interaction movement concentrated in compact controls and slow horizontal supporting strips; retain the settled readability of the large text and product stage.

**Unknown:**

- Particle-art animation timing and video choreography are not specified.
- Focus-visible appearance is not established.

### Responsive

**Observed:**

- CSS includes width breakpoints at 390px, 640px, 768px, 991px, 992px, 1024px, 1280px, 1400px, 1440px, 1536px and 1600px.
- Product tab rows use horizontal overflow; detailed comparison tables also allow horizontal overflow.

**Transfer:**

- For narrow layouts, stack promise copy before product imagery, keep the mint emphasis in reading order and reduce side padding while preserving generous chapter separation.
- Keep tabs and detailed comparison as horizontally scrollable structures rather than compressing every label into unreadable columns.
- Retain the closing panel and particle ribbon in a stacked composition, with the planes behind or below the message.

**Unknown:**

- Exact narrow-screen type sizes and navigation transformation are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
