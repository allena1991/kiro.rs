# Tines — enterprise in bloom

## Overview

A warm, expansive technology style that makes serious infrastructure feel inventive and human. Cream and violet carry the everyday identity, with mint, pink and apricot illustrations, geometric grotesk headlines, literary serif passages and tiny monospace controls. Dense product interfaces sit inside broad, colorful stages rather than dictating the page's visual density. It suits complex products that need both institutional trust and a sense of creative possibility.

### Essentials

- The promise is conversational, not a slogan floating over a dashboard: left-aligned 64px regular grotesk, 1.05 line height and -0.03em tracking, followed by a 24px serif sentence and two compact actions.
- Small controls counterbalance enormous artwork: uppercase 13px bold mono labels inside 140×36px pills, with 18.2px side padding and an 8px gap between filled and outlined actions.
- Cream is the default field and violet is the reading color: #fcf9f5 and #714bd0 dominate open space; saturated color concentrates in a 48px-radius statement panel and a product stage rather than every section background.
- Typography changes register within the story: 56px regular grotesk section leads give way to 52px serif editorial statements and 24px serif card text, with bold reserved for a decisive clause.
- Illustration behaves like a living environment: purple-outlined, flat pastel flowers, small machines and interlocking shapes spill past section edges. Include an oversized patterned word or symbol sculpture; without bespoke art, fill an SVG text mask with overlapping outlined rosettes and geometric motifs.
- The ending is an event, not a small banner: a nearly edge-to-edge illustrated action phrase sits above a centered 528px-wide support line and paired pills, then gives way to five airy footer columns and a tiny centered utility capsule.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Reading violet | `#714bd0` | `--color-ink` | text, background, action, border | Default text, outlined actions, statement panels and proof cards. |
| Cream edge on violet | `#8463d5` | `--color-glass-edge` | border | Visible result of 14% cream over reading violet on proof cards. |
| Deep violet | `#542f9c` | `--color-deep` | action, text, surface | Navigation conversion button and dark plan surface. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage green | `#009650` | `--color-green` | background, surface | Saturated backing for the selected product demonstration. |
| Lavender edge | `#c3b5ff` | `--color-lavender-edge` | border, surface | Fine outlines and folded edges on lavender panels. |
| Apricot paper | `#ffe2c5` | `--color-peach` | surface, accent | Warm capability and review panels, plus illustration details. |
| Petal pink | `#ffe0ef` | `--color-pink` | surface, accent | Pastel capability and review cards, plus illustration details. |
| Mint framing | `#cae4d4` | `--color-mint` | surface, accent | Product-window frame and stronger mint illustration fills. |
| Pale lavender | `#ece8fd` | `--color-lavender` | surface, background | Search control and pastel capability or review panels. |
| Pale mint | `#e4eee7` | `--color-pale-mint` | surface | Capability panels and introductory plan card. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet hairline on cream | `#ebe4f1` | `--color-rule` | border | Visible result of 12% reading violet over cream; separates footer link groups. |
| Utility lavender wash | `#f5f0f3` | `--color-footer-wash` | surface | Visible result of 5% reading violet over cream, used behind the footer utility capsule. |
| Warm cream | `#fcf9f5` | `--color-canvas` | background, text, surface | Default canvas and reversed text. Cream alpha layers also back translucent controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages and customer-proof collections | Bright violet | `#7a56e0` | `--color-bright-violet` | background, surface, accent | Full pricing canvas and book covers. |
| solution and customer-proof pages | Editorial violet | `#5d38ae` | `--color-secondary-ink` | text, border, action | Deeper reading color for solution and proof-led pages. |
| pricing pages | Mint edge | `#5cbd8b` | `--color-mint-edge` | border | Colored hairline around introductory plan panel. |
| customer-proof collections | Book backing lavender | `#ded8ff` | `--color-medium-lavender` | surface | Backing behind saturated book-shaped proof panels. |
| company and culture pages | Inset charcoal | `#18151f` | `--color-dark-card` | surface | Portrait cards and inset recruitment panel. |
| company and culture pages | Aubergine charcoal | `#1f1c27` | `--color-dark` | background, text | Dark organizational story canvas and reversed light-button text. |
| pricing and customer-proof pages | White | `#ffffff` | `--color-white` | text, action | Reversed pricing text and light actions on the pricing canvas. |

## Typography

- **Roobert** — Headlines, body text, navigation and interface-adjacent captions. Broad, rounded geometric grotesk with open counters and an approachable single-storey flavor. If unavailable, use **DM Sans**. Use 400–600; preserve the tight display tracking and broad line lengths. Font stack: "Roobert", "DM Sans", -apple-system, system-ui, Arial, Roboto, Ubuntu, Helvetica Neue, sans-serif.
- **Reckless** — Editorial statements, support lines, quotations and small card headings. Expressive, high-contrast literary serif; regular text feels humane, bold clauses feel emphatic rather than formal. If unavailable, use **Lora**. Use 400, 500 and 700; tune wrapping to the measured text widths. Font stack: "Reckless", "Lora", Georgia, serif.
- **Roobert Mono** — Uppercase actions, section kickers and footer category headings. Compact technical monospace, usually bold, acting as a counterweight to the rounded display and literary serif. If unavailable, use **IBM Plex Mono**. Use 600–700; keep short labels and measured tracking. Font stack: "Roobert Mono", "IBM Plex Mono", Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Roobert | 400 | 64px | 1.05 | -0.03em | Default landing-page promise, arranged as two conversational lines. |
| heading-lg | Roobert | 400 | 56px | 1.05 | -0.03em | Major section leads and stacked statement-panel lines. |
| editorial-display | Reckless | 400 | 52px | 1.1 | -0.03em | Centered narrative turn in a narrow column. |
| editorial-emphasis | Reckless | 700 | 52px | 1.1 | -0.03em | Decisive second clause within the editorial display. |
| hero-support | Reckless | 500 | 24px | 1.3 | normal | Single serif explanatory sentence under the opening promise. |
| section-support | Reckless | 400 | 24px | 1.25 | -0.01em | Supporting text below large grotesk section leads. |
| card-heading-bold | Reckless | 700 | 24px | 1.1 | -0.01em | Compact benefit headings inside the statement panel. |
| proof-card-text | Reckless | 400 | 24px | 1.2 | -0.01em | Continuous serif text inside violet proof cards; lead clause can be bold at the same size and line height. |
| closing-support | Roobert | 500 | 24px | 1.25 | -0.01em | Centered two-line invitation below the monumental closing artwork. |
| body | Roobert | 500 | 16px | 1.5 | normal | Default benefit paragraphs and feature-card explanations. |
| nav | Roobert | 600 | 14px | 1.15 | normal | Navigation items and compact utility links. |
| footer-link | Roobert | 500 | 14px | 1.2 | normal | Footer links, grouped with small vertical gaps. |
| eyebrow | Roobert Mono | 700 | 13px | 1 | 0.05em, uppercase | Short section identifiers above major headings. |
| button | Roobert Mono | 700 | 13px | 1 | 0.02em, uppercase | Main and secondary conversion pills. |
| nav-action | Roobert Mono | 700 | 13px | 1.15 | normal, uppercase | Navigation conversion action. |
| footer-heading | Roobert Mono | 600 | 11px | 1.15 | 0.02em, uppercase | Footer column titles. |
| utility-label | Roobert Mono | 700 | 11px | 1.4 | 0.02em, uppercase | Label inside the centered footer utility capsule. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| solution and company-story openings | solution-display | Reckless | 400 | 64px | 0.97 | -0.03em | Centered two-line editorial promise, surrounded by illustration. |
| pricing pages | pricing-display | Roobert | 400 | 64px | 1 | -0.03em | Short centered page title. |
| customer-proof pages | proof-display | Reckless | 400 | 56px | 1 | -0.02em | Short title below a broad illustrated opening. |
| company and culture pages | culture-heading | Reckless | 400 | 48px | 1.15 | -0.03em | Section title above portraits, affiliations or principles. |
| company-story statement cards | mission-statement | Roobert | 600 | 48px | 1.1 | -0.03em | Heavy grotesk statement inside a lavender panel, contrasting the surrounding serif headings. |
| solution and pricing pages | editorial-heading | Reckless | 400 | 46px | 1.05 | -0.02em | Section leads above capability grids, badges and questions. |
| book-shaped proof cards | stat | Reckless | 400 | 38px | 1 | normal | Right-aligned outcome number near the foot of the cover. |
| pricing pages | plan-heading | Roobert | 500 | 32px | 1.15 | -0.02em | Plan title centered within paired edition cards. |
| testimonial ribbons | quote | Reckless | 400 | 30px | 1.25 | -0.01em | Large quotation beside a narrow contextual panel. |
| solution capability grids | feature-heading | Reckless | 400 | 24px | 1.3 | -0.01em | Heading inside pastel benefit cards. |
| pricing pages | faq-question | Roobert | 600 | 24px | 1.375 | normal | Question in ruled accordion rows. |
| customer-review collections | review-heading | Reckless | 400 | 24px | 1.275 | normal | Review title beneath quote and star marks. |
| customer-review collections | review-body | Roobert | 400 | 16px | 1.4 | normal | Review prose on pastel cards. |
| book-shaped proof cards | stat-caption | Roobert | 500 | 15px | 1.2 | normal | Right-aligned explanation below an outcome number. |

**Notes:**

- The default large headings are regular grotesk, not serif. Serif becomes the voice of explanation, narrative contrast and proof; solution and company-story openings reverse that priority.
- At display sizes tracking is -0.03em. Small serif headings generally relax to -0.01em; body copy stays at normal tracking. Uppercase is concentrated in monospace labels rather than large headlines.
- Pattern-filled sculptural lettering is artwork, separate from the text hierarchy. Give it a cap-height near 200px at a 1440px-wide desktop composition, with a broad, heavy grotesk silhouette and ornament extending beyond the letters.

## Layout

**Density:** Airy at section scale and compact inside controls: long stretches of cream alternate with tightly grouped copy and broad illustrated objects.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap between paired conversion actions. |
| 12px | Benefit title to paragraph and small inner card group gaps. |
| 24px | Grid gutters, eyebrow-to-heading spacing and proof-card padding. |
| 30px | Pastel feature-card padding and FAQ question vertical padding. |
| 32px | Review-card content padding and ribbon vertical padding. |
| 40px | Default desktop page gutters, stage padding and footer column gaps. |
| 48px | Testimonial ribbon horizontal padding. |
| 55px | Statement-panel padding, heading-to-grid gaps and culture-card padding. |
| 96px | Editorial interlude padding and closing-section bottom padding. |
| 156px | Major section separation and narrower desktop editorial gutters. |

### Containers and grids

- **wide canvas**: max width 1520px · side padding 40px. Default centered outer system. At 1440px the working width is 1360px; art can overflow the text container and be clipped by the viewport.
- **editorial container**: max width 1128px · side padding 156px. Narrower desktop grid for solutions, plans, portraits and proof collections; use the width as the controlling maximum and let side gutters shrink with the viewport.
- **landing intro**: max width 1024px. Left-aligned opening headline. Section intros usually narrow to 832px, with supporting serif paragraphs limited to 768px.
- **narrative column**: max width 440px. Centered editorial paragraphs; the associated display occupies a 416px column while illustration brackets both sides.
- **closing copy**: max width 528px. Centered support copy under the wide closing word sculpture.
- **benefit grid**: 3 columns · gap 24px. Pastel 360px-wide cards within the editorial container.
- **proof row**: 4 columns · gap 24px. 322px-wide violet cards in the wide container.
- **footer columns**: 5 columns · gap 40px. Unequal link columns, approximately 168–190px wide, distributed across the wide canvas.
- **edition pair** (only for pricing pages): 2 columns · gap 24px. Two equally sized 552px-wide edition panels, not a dominant recommended middle tier.
- **illustrated category grid** (only for solution detail navigation): 4 columns · gap 24px. 264px-wide illustrated tiles; a short final row is centered.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion pills | 9999px (pill) |
|  | feature and proof cards | 14px |
|  | large statement panel | 48px |
|  | product window | 24px |
| customer-proof collections | review and book backing | 24px |
| book-shaped proof cards | book cover | 4px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Default landing-page field.

**CSS:** `background: #fcf9f5; color: #714bd0`

**Observed:** The unpainted space remains warm rather than stark white.

**Transfer:** Let cream carry most reading sections and keep saturated surfaces localized.

#### Violet statement panel · level 1

**Use:** A high-impact statement and benefit chapter.

**CSS:** `background: #714bd0; color: #fcf9f5; border-radius: 48px; padding: 55px; overflow: hidden`

**Observed:** Inset within the page gutters, with art growing along the bottom edge rather than a separate image frame.

**Transfer:** Use one emphatic claim opposite a small benefit matrix.

#### Pastel panel · level 1

**Use:** Capability and explanatory cards.

**CSS:** `background: #ece8fd; border: 1px solid #c3b5ff; border-radius: 14px; padding: 30px; box-shadow: none`

**Observed:** Lavender is joined by mint, pink and apricot variants with related darker ink and colored hairline borders.

**Transfer:** Assign a coherent color family to each idea; keep text legible and the fills flat.

#### Violet proof surface · level 1

**Use:** Compact assurances and differentiators.

**CSS:** `background: #714bd0; color: #fcf9f5; border: 1px solid rgba(252,249,245,0.14); border-radius: 14px; backdrop-filter: blur(12px)`

**Observed:** The visible result is a nearly solid violet card, not glossy glass.

**Transfer:** Use the edge to clarify the shape, not as a luminous effect.

#### Product stage · level 1

**Use:** Large selected demonstration behind overlapping product windows.

**CSS:** `background: #009650; border-radius: 0px 0px 48px 48px; overflow: hidden`

**Observed:** Color-matched tabs form the top edge; the active surface spreads beneath them.

**Transfer:** Choose a saturated family related to the selected use case, reserving most of the panel for the product.

#### Frosted navigation backing · level 2

**Use:** Soft sticky navigation backdrop.

**CSS:** `background: rgba(252,249,245,0.9); backdrop-filter: blur(10px); border-radius: 990px`

**Observed:** A shallow rounded layer is inset behind the navigation, allowing a soft hint of content through while scrolling. Pricing and culture themes tint it to match their canvas.

**Transfer:** Keep the visual effect subtle; never make the entire navigation content translucent.

#### Pricing canvas · level 0

**Only for:** pricing pages

**Use:** Full-page commercial variant.

**CSS:** `background: #7a56e0; color: #ffffff`

**Observed:** The violet theme continues through the closing call and footer.

**Transfer:** Use the full theme consistently instead of inserting unrelated dark pricing cards into an otherwise ordinary page.

#### Culture canvas · level 0

**Only for:** company and culture pages

**Use:** Organizational storytelling variant.

**CSS:** `background: #1f1c27; color: #fcf9f5`

**Observed:** Warm portraits and pastel principle panels punctuate aubergine charcoal.

**Transfer:** Maintain the same typography contrast and illustrated ending as the light theme.

#### Dark inset panel · level 1

**Only for:** company and culture pages

**Use:** Portrait frames and recruitment callout.

**CSS:** `background: #18151f; border: 1px solid rgba(252,249,245,0.14); border-radius: 14px`

**Observed:** A darker, flat inset rather than a raised shadowed card.

**Transfer:** Use modest edges to separate related content from the dark canvas.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #714bd0; color: #fcf9f5; border: 1px solid transparent; border-radius: 9999px; height: 36px; min-width: 140px; padding: 0px 18.2px`

**Text style:** `button` — Roobert Mono 700 · 13px/1 · tracking 0.02em · uppercase

**Observed:** Compact centered text with no oversized arrow. The filled action pairs with Secondary button; light-on-violet and cream-on-charcoal variants reverse the same construction.

**Transfer:** Choose one short conversion verb phrase and keep the adjacent alternative visually lighter.

### Secondary button

**Use:** Second action beside a filled conversion pill.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(252,249,245,0.65); color: #714bd0; border: 1px solid #714bd0; border-radius: 9999px; height: 36px; min-width: 140px; padding: 0px 18.2px; backdrop-filter: blur(12px)`

**Text style:** `button` — Roobert Mono 700 · 13px/1 · tracking 0.02em · uppercase

**Observed:** The opening uses a cream translucent fill; the closing uses an unfilled outline. Dark and violet themes reverse the border and label colors.

### Navigation item

**Use:** Main desktop navigation.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 8px 12px; border-radius: 50px; color: #714bd0`

**Text style:** `nav` — Roobert 600 · 14px/1.15

**Observed:** Brand mark and menu group sit left; account links, a compact conversion pill and a 38px search circle sit right, all inside a 68px sticky header. Menu chevrons are tiny and muted.

**States:** Declared: hover background-color color-mix(in srgb, currentcolor 10%, transparent 90%).

### Navigation conversion

**Use:** Persistent conversion inside the header.

**CSS:** `display: flex; align-items: center; background: #542f9c; color: #fcf9f5; border-radius: 990px; padding: 10px 20px; height: 35px`

**Text style:** `nav-action` — Roobert Mono 700 · 13px/1.15 · uppercase

**Observed:** Slightly smaller and darker than the body conversion pills. The pricing and culture themes use a cream fill instead.

**States:** Declared: hover background-color color(display-p3 .3827 .2622 .7236); color #fcf9f5.

### Violet assurance card

**Use:** A row of concise differentiators on cream.

**CSS:** `display: flex; flex-direction: column; gap: 40px; background: #714bd0; color: #fcf9f5; border: 1px solid rgba(252,249,245,0.14); border-radius: 14px; padding: 24px; backdrop-filter: blur(12px)`

**Text style:** `proof-card-text` — Reckless 400 · 24px/1.2 · tracking -0.01em

**Observed:** A bold lead clause runs directly into regular serif explanation; a small illustrative object anchors the lower portion. Four equal cards form the desktop row.

**Transfer:** Keep each card a continuous thought, not a mini dashboard or dense feature checklist.

### Footer link

**Use:** Deep navigation after the closing call.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 3.5px 0px; color: #714bd0`

**Text style:** `footer-link` — Roobert 500 · 14px/1.2

**Observed:** Links are grouped under footer-heading labels; 6px gaps separate items, with fine rules between subgroups. Group leaders use bold text, and external links carry tiny diagonal arrows.

**States:** Declared: hover color var(--pageAccent).

### Footer utility capsule

**Use:** Centered discovery utility between copyright and privacy controls.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; background: rgba(113,75,208,0.05); border-radius: 999px; padding: 4px 4px 4px 16px; width: 325px; height: 40px; box-sizing: border-box`

**Text style:** `utility-label` — Roobert Mono 700 · 11px/1.4 · tracking 0.02em · uppercase

**Observed:** A tiny uppercase prompt is followed by five 32px icon links. The same low-contrast capsule uses white or cream alpha fills on colored themes.

**Transfer:** Adapt to a real useful discovery or ecosystem function; keep the compact icon rail and small-label character.

### Pastel capability card

**Only for:** solution capability grids

**Use:** Explain one capability in a consistent grid.

**CSS:** `display: flex; flex-direction: column; gap: 24px; background: #ece8fd; border: 1px solid #c3b5ff; border-radius: 14px; padding: 30px`

**Text style:** `feature-heading` — Reckless 400 · 24px/1.3 · tracking -0.01em

**Observed:** Serif title, sans body and a small whimsical object at the lower right. Repeated cards alternate pastel families without changing their structure.

**Transfer:** Use a short outcome-led title and a single explanatory paragraph; retain an illustrated metaphor rather than a generic icon badge.

### Book proof card

**Only for:** customer-proof collections

**Use:** Turn a case study or quantified result into a tactile object.

**CSS:** `display: flex; justify-content: flex-end; align-items: flex-end; background: #7a56e0; color: #ffffff; border-radius: 4px 12px 12px 4px; padding: 18px 18px 18px 24px; width: 185px; height: 246px; box-sizing: border-box; overflow: hidden`

**Text style:** `stat` — Reckless 400 · 38px/1

**Observed:** The cover occupies the right portion of a 360×270px pastel backing with a logo upper left. A slim darker spine and upper-right bookmark make it read as a book. Quotes or stat-caption text align to the lower right; the number is not centered.

**Transfer:** Use genuine outcomes or a short quotation. Keep the book metaphor when the proof collection changes subject.

### Review card

**Only for:** customer-review collections

**Use:** Longer attributed proof among book cards and accreditation tiles.

**CSS:** `display: grid; gap: 15px; background: #ece8fd; border-radius: 24px; color: #542f9c`

**Text style:** `review-body` — Roobert 400 · 16px/1.4

**Observed:** Quote mark upper left, five small stars upper right, then review-heading and prose. Content has 32px inner padding; the author, role and external review link form a separate bottom block. Cards vary in height rather than sharing a rigid baseline.

### Edition card

**Only for:** pricing pages

**Use:** Present a simple two-path commercial choice.

**CSS:** `display: grid; position: relative; background: #e4eee7; border: 1px solid #5cbd8b; border-radius: 14px; padding: 0px 30px 30px; overflow: hidden`

**Text style:** `plan-heading` — Roobert 500 · 32px/1.15 · tracking -0.02em

**Observed:** A small tab hangs from the top center, followed by centered title and summary. A 160×42px pill straddles a horizontal dividing line; a check list and small retro machine illustration occupy the lower part. The paid counterpart is deep violet with cream text and action.

**Transfer:** Contrast adoption stages, not a forest of competing prices.

### FAQ row

**Only for:** pricing pages

**Use:** Expandable objection handling on the violet canvas.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.2); color: #ffffff`

**Text style:** `faq-question` — Roobert 600 · 24px/1.375

**Observed:** A semantic disclosure row with question left and plus sign far right. Summary padding is 30px vertically; collapsed rows are about 94px tall. Expanded answers use sans body text and underlined inline links.

## Imagery and graphics

### Patterned word sculpture

**Use:** Signature opening object and monumental closing action artwork.

**Observed:** Huge heavy letters or numerals carry densely packed flat flowers, rosettes and purple line drawings. Mint, pink, apricot and lavender fill the opening symbol. The closing phrase is predominantly violet, with pale contour drawings inside it, pink loops behind the ends and a few figures or flowers breaking the silhouette. It spans nearly the full viewport, far larger than the nearby text.

**Transfer:** Use a short product-relevant symbol or promise at the opening and an original two-word invitation for the ending. Minimum acceptable treatment is a clean SVG text mask with a deliberate dense ornamental pattern, not plain giant text.

**Build:** Create an SVG with a 1440px-wide viewBox. Convert a heavy grotesk word or symbol to paths and use it as a clipPath. Fill with #714bd0, then tile overlapping 24–90px rosettes, pointed starbursts, circles and curved stems using #cae4d4, #ffe0ef, #ffe2c5 and #ded8ff, outlined in #714bd0. For the ending, reduce fills to two violet tones with pale contour lines; place two broad pink oval loops behind the first and last letters and add a few outlined flowers in front. Keep contours sharp and flat; no photographic texture or blur.

### Illustrated machine garden

**Use:** Editorial interlude, statement-panel edge and isolated chapter illustrations.

**Observed:** Retro rounded monitors sprout cables and vines at both viewport edges around a narrow center column. Their cream screens contain multicolored concentric wavy stars. Elsewhere, flower beds, a satellite dish, instruments, layered shields and small impossible machines turn abstract capabilities into playful physical objects. Purple outlines and pastel fills tie everything together.

**Transfer:** Choose physical metaphors for the new product: connected instruments, paper mechanisms or tools. Maintain fine violet linework, cream negative space and pastel flat fills. A few well-drawn SVG objects are preferable to generic stock 3D.

**Build:** Build monitors from nested 80–220px rounded rectangles with 1–2px violet outlines, lavender side faces and cream screens. Generate nested 12–20-point wavy star paths in mint, pink and apricot, with no fill. Connect groups using curved SVG paths, parallel cable strokes and tiny leaves. Position clusters outside the center 440px reading column. For a flower bed, overlap radial petal paths along the panel bottom, varying sizes and rotations and clipping them at the rounded boundary.

### Product windows on a color stage

**Use:** Demonstrations and use-case exploration.

**Observed:** Real light interface windows overlap on saturated green, the front window larger and fully opaque while the back window recedes through tint and opacity. A mint frame has 5px padding, 24px outer corners and a stronger bottom edge; the interface itself has 19px corners. The UI remains rectangular and legible rather than tilted in perspective.

**Transfer:** Use two meaningful views of the new product, such as configuration and result. If no finished UI exists, build a representative functional panel with real labels and a plausible task outcome; keep the internal interface quieter than the stage.

**Build:** Layer two absolutely positioned windows inside a clipped stage with 40px inset. Give the front frame #cae4d4 fill, 5px padding, 24px radius, a 1px related mint edge and a 3px bottom edge. Place the larger window toward the lower right; tint the rear view with a mint overlay and 0.5 opacity. Above the windows, use a small cream selected segment within a two-choice capsule.

### Floating editorial vignettes

**Only for:** solution and customer-proof openings

**Use:** Set a page theme before the main text or bracket its centered promise.

**Observed:** Flat pastel illustrated islands contain a clock, graph, flowers or a tiny geometric landscape. The customer-proof opening gives these shapes a broad 1128×447px field before a split title-and-intro row. Solution openings instead place cropped instruments at the far left and right of centered copy.

**Transfer:** Illustrate the outcome rather than the interface, keeping large cream gaps between islands and no rectangular photo frame.

**Build:** Use organic SVG blob outlines with violet strokes, offset pastel side faces and a few internal simple geometric objects. Vary the island scale; let one central island be largest and scatter smaller companions with ample negative space.

### Human hands and warm portraits

**Only for:** company and culture pages

**Use:** Humanize the organizational narrative.

**Observed:** The dark opening shows disembodied illustrated hands emerging from pastel oval cuffs, holding a paper plane, nested figure and small flag. Portraits are warm, waist-up photographs against the same honey-colored timber setting, tightly framed in four-column dark cards.

**Transfer:** Use original hand-and-tool metaphors and consistently lit real portraits. Keep warm photography within organizational storytelling rather than introducing it as the default product hero.

**Build:** For illustration, draw tapered forearms and outlined cream hands emerging through tilted pastel ellipses; add a darker back half to each cuff for simple depth. Hold a small product-relevant object above each wrist. Use flat fills and fine violet outlines on the charcoal field.

### Icons

**Observed:** Most small marks are solid SVGs colored to match adjacent text. Search is 16×16px in a 38px circle; external arrows are tiny, while proof cards use 17×16px stars, a quote mark and a 19×33px bookmark. Marketing illustrations are much more detailed than the controls.

**Transfer:** Use restrained matching monochrome controls; reserve detailed, colored drawing for the illustrative system. Keep arrows beside the label rather than in large circular badges.

## Section recipes

How recurring sections are built.

### First screen: Conversational promise with a symbol stage

**Observed:** A 68px sticky navigation sits over Cream canvas. Below it, a small outlined announcement capsule begins a left-aligned copy stack in 40px gutters. The display headline occupies roughly two thirds to three quarters of the width across two lines at 64px/1.05, regular violet grotesk. A 24px serif support sentence follows after about 19px, then Primary button and Secondary button after 24px. A violet monochrome logo rail stretches beneath the actions. The lower half of the first 900px is dominated by a huge flower-filled symbol sculpture extending beyond the viewport edges. Its lower edge meets the top of a framed product demonstration with a lavender playback rail. The promise, support, both actions, logos and much of the object are visible above the fold; most of the interface continues below. Layers run cream field, sculptural illustration, then the foreground product frame and controls; the copy stays unobstructed.

**Transfer:** For a new landing page, use a two-part promise with conversational syntax and an original oversized patterned symbol tied to the product's value. Without bespoke artwork, use the Patterned word sculpture SVG recipe and a credible product panel below it. Commercial pages can open compactly with a short centered title and paired edition cards; solution pages use a centered serif promise with edge illustrations; proof pages lead with a broad vignette field; company stories use the scoped dark serif opening.

**Avoid:** Do not substitute a centered slogan above a generic laptop mockup, or put the headline inside the patterned object. Do not shrink the main object to a thumbnail beside the copy.

**Text style:** `display` — Roobert 400 · 64px/1.05 · tracking -0.03em

### Eyebrow and heading pair

**Observed:** A mono eyebrow sits 24px above heading-lg; section-support follows after 24px. The intro occupies a broad left column and leaves room for an isolated illustration on the right. Larger sections are separated by 156px.

**Transfer:** Use labels as chapter identifiers and write the heading as an outcome, not a category name.

**Text style:** `heading-lg` — Roobert 400 · 56px/1.05 · tracking -0.03em

### Illustrated editorial interlude

**Observed:** A 416px centered editorial-display headline alternates regular and bold clauses, with a small tangled-arrow emblem below it and serif paragraphs within a 440px column. Illustrated machine garden clusters bracket the text at both edges. Vertical padding is 96px.

**Transfer:** Use this for a tension-and-resolution turn in the story; keep the central copy clear and let the surrounding objects dramatize the tension.

**Text style:** `editorial-display` — Reckless 400 · 52px/1.1 · tracking -0.03em

### Statement and benefit matrix

**Observed:** Violet statement panel spans the wide working area. Three stacked heading-lg lines sit left; a two-column benefit matrix sits right with 40px gutters and 55px row gaps. Each benefit uses card-heading-bold and body. A flower bed grows from the lower left, while the lower right contains a short serif conclusion and a cream action.

**Transfer:** Group one ambitious promise with a small set of tangible reasons to believe it. Preserve the asymmetric balance of large statement, compact explanation and bottom-edge art.

**Text style:** `heading-lg` — Roobert 400 · 56px/1.05 · tracking -0.03em

### Tabbed product theater

**Observed:** Five colored use-case tabs form a continuous top strip. Each tab combines a 24px serif title, compact sans description and 30px side padding. The selected tab's color expands into Product stage. A small two-choice view capsule sits above overlapping Product windows on a color stage.

**Transfer:** Use the number of tabs warranted by the new product. Demonstrate distinct tasks or audiences, keeping the result visible and each tab visually tied to its stage.

### Violet assurance row

**Observed:** A left-aligned Eyebrow and heading pair with an isolated illustration leads into four Violet assurance cards, 24px apart. Their continuous serif copy makes a bolder first claim and then explains it; small objects settle toward the bottom.

**Transfer:** Use for trust, interoperability, reliability or time-to-value claims, backed by concrete wording rather than icon-only feature names.

**Text style:** `proof-card-text` — Reckless 400 · 24px/1.2 · tracking -0.01em

### Monumental closing invitation

**Observed:** Patterned word sculpture presents a nearly full-width action phrase in a section approximately 518px tall. The visual reaches beyond the text container; closing-support is centered beneath it within 528px, then two conversion pills. The theme continues seamlessly into the footer.

**Transfer:** Make the closing phrase an original, very short invitation, rendered as artwork rather than another heading. Preserve the scale even when a page has little content; use the SVG patterned-letter fallback if needed.

**Text style:** `closing-support` — Roobert 500 · 24px/1.25 · tracking -0.01em

### Five-column ending

**Observed:** After the closing invitation, five Footer link columns occupy a broad open field with 50px top and 40px side padding. Mono category titles and fine subgroup rules establish hierarchy. At the bottom, copyright aligns left, Footer utility capsule sits centered and a privacy control aligns right. Cream, violet and charcoal page themes each continue to the final pixel.

**Transfer:** Organize the new product's real destinations into a similarly legible hierarchy; do not inflate the link count just to match the height.

**Text style:** `footer-heading` — Roobert Mono 600 · 11px/1.15 · tracking 0.02em · uppercase

### Pastel capability and category chapters

**Only for:** solution pages

**Observed:** An editorial-heading introduces a three-column Pastel capability card grid in the 1128px container. A later centered heading introduces four-column illustrated category tiles: large saturated image area, two thin horizontal tonal bands, then a pale serif label strip; shorter last rows are centered.

**Transfer:** Separate explanatory benefits from navigational categories. Let the former be text-led and the latter image-led.

**Text style:** `editorial-heading` — Reckless 400 · 46px/1.05 · tracking -0.02em

### Folded testimonial ribbon

**Only for:** solution and pricing pages

**Observed:** A narrow contextual panel joins a wider quotation panel. The wide panel overlaps its neighbor by 72px, has 32px vertical and 48px horizontal padding and rounds only its right corners at 14px. A little fold connects the layers; quote text sits beneath a quote symbol, followed by attribution and logo. The light variant is lavender, the pricing variant darker violet.

**Transfer:** Use one substantive quotation plus a relevant context or outcome. Preserve the paper-ribbon construction instead of turning it into a generic centered testimonial.

**Text style:** `quote` — Reckless 400 · 30px/1.25 · tracking -0.01em

### Proof library and review collage

**Only for:** customer-proof pages

**Observed:** A regular three-column grid of Book proof cards begins the collection. A longer masonry-like chapter mixes those books, Review cards and accreditation tiles on pastel backings. All columns remain 360px wide with 24px gutters; uneven heights and side fades make the collection feel abundant without changing the grid.

**Transfer:** Use varied kinds of genuine proof, not repeated invented metrics. Retain the book cover device and the right-aligned stat treatment.

**Text style:** `stat` — Reckless 400 · 38px/1

### Edition pair and ruled objections

**Only for:** pricing pages

**Observed:** A short pricing-display title is flanked by small machine illustrations. Two Edition cards sit below in the first screen, then a monochrome logo rail. A ribbon quote, a row of accreditation badges and editorial-heading introduce a full-width FAQ row list before the closing call.

**Transfer:** Keep the commercial choice understandable within the first viewport, then answer adoption concerns without adding dense comparison tables by default.

**Text style:** `pricing-display` — Roobert 400 · 64px/1 · tracking -0.03em

### Dark organizational chapters

**Only for:** company and culture pages

**Observed:** Culture canvas begins with centered solution-display, short sans support and a broad hand illustration. A split story-and-mission chapter pairs serif narrative with a lavender mission-statement panel. Four-column warm portraits, a monochrome affiliation rail and three pastel principle cards follow. Principle cards place body text first and a serif name with a small object at the bottom. Dark inset panel provides a separate recruitment call before the shared ending.

**Transfer:** Adapt the chapters to the organization's real story. Keep the strong illustration, human photography and pastel-on-charcoal contrast without importing these sections into every product page.

**Text style:** `solution-display` — Reckless 400 · 64px/0.97 · tracking -0.03em

## Page flow

**Storyline:** Promise → visible product or metaphor → narrative tension → capability explanation → credible proof → invitation → deep navigation; emphasis shifts with the page's purpose.

### Introduce a complex product with both creative energy and institutional confidence

1. **promise** — Conversational two-line grotesk promise, serif explanation, paired actions and a logo rail above an enormous patterned symbol.
2. **product demonstration** — A framed interface demonstration connects the opening art to real functionality.
3. **narrative tension** — Narrow centered serif argument surrounded by connected illustrated machines.
4. **capability explanation** — Violet statement panel and tabbed full-color product theater show how the promise works.
5. **credibility** — Four violet assurance cards pair emphatic serif clauses with small illustrative objects.
6. **closing call** — Monumental patterned invitation, support sentence and paired actions lead into the five-column footer.

**Transfer:** Keep the movement from imaginative promise to tangible product and grounded trust; adapt the chapter count to the offer.

### Explain commercial access and remove adoption uncertainty

1. **commercial choice** — Violet canvas, centered title, flanking drawings and two contrasting edition panels visible immediately.
2. **social proof** — Logo rail, folded quotation and accreditation badges.
3. **objection handling** — Ruled disclosure questions spanning the broad container.
4. **closing call** — Shared patterned invitation and theme-matched footer.

**Transfer:** Offer a clear choice first, then proof and practical answers; maintain the scoped violet theme throughout.

### Make the product relevant to a particular audience or problem

1. **audience promise** — Slim local navigation, centered serif headline and cropped edge illustrations.
2. **problem framing** — Ruled split editorial heading and explanatory paragraph.
3. **capabilities** — Pastel text cards followed by larger illustrated category-navigation tiles.
4. **social proof** — A folded ribbon combines context, outcome and a substantial quotation.
5. **closing call** — Shared illustrated invitation and cream footer.

**Transfer:** Narrow the vocabulary to the audience while keeping the same illustration grammar and pastel materials.

### Demonstrate breadth and depth of customer outcomes

1. **visual introduction** — A broad field of floating illustrated islands precedes a split heading-and-intro row.
2. **case study discovery** — Three-column library of small book-shaped story cards.
3. **corroborating proof** — A long varied collection of attributed reviews, outcome books and accreditation badges.
4. **closing call** — Large patterned action artwork resolves the abundance before the cream footer.

**Transfer:** Make every card traceable to real proof; retain varied card types and the visual book metaphor rather than flattening everything into a logo grid.

### Explain the people, origins and principles behind the product

1. **organizational belief** — Dark serif opening with illustrated hands and a concise sans statement.
2. **origin and mission** — Split narrative and heavy grotesk mission card.
3. **human credibility** — Warm consistent portraits and affiliation marks.
4. **principles and participation** — Pastel principle cards and an inset recruitment call.
5. **closing call** — The same patterned invitation, then a charcoal version of the five-column footer.

**Transfer:** Use the scoped dark theme to support a more personal narrative while retaining the shared closing device.

## Writing

Confident and plainspoken about consequential work, but warm enough to acknowledge real human constraints. The product is powerful without sounding punitive; control is framed as something that enables people rather than blocks them.

**Do not copy:** Do not reuse the Tines name, product names, logos, proprietary illustrations, customer identities, testimonials, numerical claims, awards or mission statement. Use original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you in the promise and explanatory copy. Use we for organizational beliefs and the product name for functional explanation; describe teams as capable people, not risk sources.
- **Rhythm:** Short conversational headline clauses contrast with one or two fuller explanatory sentences. Benefit titles are often two to six words; periods and parallel phrasing create confidence without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Acknowledge what the reader has already asked for, then offer the missing enabling condition. | Two clauses, roughly 6–12 words each. | “You told everyone to use AI.”<br>“Now give them a secure place to do it.” |
| Section statement | Parallel fragments balance aspiration with reassurance. | Three short lines, 2–4 words per line. | “Freedom to build.”<br>“Complete security.”<br>“No compromises.” |
| Benefit heading | Action or outcome first, with a useful tension resolved. | 3–6 words. | “Control without bottlenecks”<br>“Faster triage, sharper focus” |
| Explanation | Concrete capabilities followed by a human benefit or a clear boundary of control. | Two concise sentences. | “Know what exists, who built it, and what it touches. Focus on empowering teams without leaving a mess to untangle.” |
| Primary action | Direct verb plus the object or next step. | 2–4 words. | “Book a demo”<br>“Sign up free”<br>“Get pricing” |
| Closing invitation | A short art-sized invitation followed by two low-pressure ways forward. | Two-word artwork phrase plus one supporting sentence. | “Start today”<br>“Sign up today to get started or schedule time with our team to learn more.” |

**Words and phrasing to use:** build; important work; teams; control; visibility; your terms; without bottlenecks; ready to run; empower; the whole team

**Avoid:** revolutionary disruption; military-grade everything; unprecedented synergy; 10x claims without proof; fear-first threats; effortless magic

**Rules:**

- Pair ambitious promises with named capabilities or credible outcomes.
- Frame guardrails as enabling conditions, not restrictions.
- Use parallel clauses and contrasts to make technical ideas readable.
- Let reader quotations keep their human cadence; keep attribution clear.
- Keep conversion language literal and short enough for compact mono pills.

## Do's and Don'ts

### Do

- Keep the default opening at 64px regular grotesk with -0.03em tracking and serif support.
- Use 40px outer gutters for broad landing chapters and a 1128px editorial maximum for narrower grids.
- Keep body conversion pills at 36px high and separate paired actions by 8px.
- Preserve the 48px corners on the large violet statement panel and 14px corners on ordinary feature cards.
- Use 24px gutters consistently in three- and four-column card systems.
- Include large patterned letter artwork and smaller purple-outlined physical metaphors in the same visual system.
- Give quotations a literary serif voice and real attribution, with the ribbon as a distinct proof treatment.
- Carry the current canvas theme through the final footer and its centered 325×40px utility capsule.

### Don't

- Do not make every heading bold; 400 is the default at 56px and 64px.
- Do not replace warm cream with a cold white canvas on ordinary landing pages.
- Do not spread equal amounts of pink, green and orange across all reading sections; reserve saturation for stages, art and defined proof panels.
- Do not turn 36px conversion pills into tall 56px app-store-style buttons.
- Do not add floating-card shadows to flat pastel surfaces; separation comes from color and fine edges.
- Do not let product UI typography and internal status colors take over the marketing type hierarchy.
- Do not put the full aubergine culture theme on an ordinary product landing page.
- Do not center the numbers on book covers or strip away the spine and bookmark that make the proof tactile.

## Motion and responsive

### Motion

**Observed:**

- The logo rail declares a 30s linear infinite drift.
- Body button surfaces declare filter 0.1s and background-color 0.1s transitions. The navigation backing declares opacity 0.2s.
- Product windows declare transform 0.25s cubic-bezier(0.22, 1, 0.36, 1) and opacity 0.25s. Product-visual and timeline introductions declare 0.6s with the same easing; timeline elements include a 0.2s delay.
- The two-choice view control declares clip-path 0.28s cubic-bezier(0.22, 1, 0.36, 1). Focus-visible on its controls declares a solid 2px outline with 2px offset; the larger product window declares 3px offset.

**Transfer:**

- Let the logo rail drift slowly while reading copy stays still.
- Use the measured product-window transitions to exchange foreground and background views; preserve legibility throughout.
- Keep the two-choice selector's moving fill as a clipped capsule rather than introducing unrelated bouncing controls.

**Unknown:**

- Scroll-linked artwork timing and complete interaction choreography are not established.
- No complete reduced-motion behavior is established.

### Responsive

**Observed:**

- Declared width breakpoints include 420px, 512px, 640px, 768px, 920px, 1024px, 1280px and 1440px, with neighboring min/max boundaries.
- The broad system uses a 1520px maximum; editorial containers use a 1128px maximum.

**Transfer:**

- On narrow screens, keep the promise before the patterned symbol and product frame; scale the SVG with its viewBox rather than shrinking every text role proportionally.
- Move edge illustrations away from the 440px narrative column or simplify them into smaller brackets when they would compete with copy.
- Reduce multi-column cards to fewer columns while retaining 24px inter-card spacing where practical; preserve the book cover's right-hand relationship to its backing.
- Turn the use-case theater into a readable selector above one foreground product view rather than stacking several tiny windows.

**Unknown:**

- Mobile arrangements, exact font sizes at breakpoints, menu behavior and tab overflow behavior are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
