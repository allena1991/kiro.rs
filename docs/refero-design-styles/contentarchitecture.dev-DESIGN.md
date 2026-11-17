# Content Architecture — typographic machinery on paper

## Overview

An off-white and charcoal technical editorial style with a distinctly computational imagination. Restrained grotesk headlines and utilitarian monospace labels sit beside swirling letter sculptures, ASCII imagery and dense interface demonstrations. It suits developer tools and expert products that want to feel authored, tangible and production-tested rather than glossy or corporate; expansive stages alternate with compact technical detail.

### Essentials

- The opening is a split between paper and a typographic machine: a 900px-tall stage, roughly equal light and dark halves, a 43.1px medium-weight two-line headline on the left and edge-clipped circular letter art on the right.
- Headlines speak normally while labels behave like terminal markings: Geist Sans 500 at 45.9px/1.1 for section leads, Geist Mono 400 at 15.7px/1.25 in uppercase for labels and numbered entries.
- Conversion controls resemble joined tickets rather than pills: 48px high, 8px corners, 24px horizontal padding per word segment, with a narrow notched bridge and a 6px orange status dot.
- Color is almost entirely withheld: #f1eee7 paper and #232323 charcoal occupy the broad surfaces; #ff9100 appears only as tiny status indicators, never as a section fill.
- Imagery is made of language: use concentric rings of monospace letters, low-contrast character fields and ASCII-rendered project imagery. When no product artwork exists, synthesize a letter-built object from the product vocabulary rather than introducing generic stock art.
- The interface floats like a small instrument panel: centered navigation 16px below the top, an 8px checker-textured bezel, a dark inset and a narrow pale announcement ticker.
- Scale carries the dramatic moments: a 265.4px tightly tracked numeric proof treatment and a circular paper closing island within full-bleed letter rings balance the otherwise modest headline scale.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff9100` | `--color-orange` | accent | Small availability and conversion status dots. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#232323` | `--color-ink` | text, background, surface, action | Primary ink on paper and the dominant dark field. |
| Bezel black | `#000000` | `--color-deep` | surface, border | Checker-bezel backing and its fine outer ring. |
| Dark-field rule | `#444444` | `--color-dark-rule` | border | White at 15% over charcoal for accordion separators; 12% is used on ticket rows. |
| Warm gray | `#5b5a56` | `--color-muted` | text | Supporting copy on paper. |
| Dim index | `#7b7b7b` | `--color-index-muted` | text | Visible white at 40% over charcoal for numbering and secondary technical markings. |
| Dim panel label | `#9c9c9c` | `--color-nav-muted` | text | Visible white at 55% over charcoal for inactive navigation. |
| Paper rule | `#d2d0ca` | `--color-light-rule` | border | Charcoal at 15% over warm paper for footer separators. Input edges use the stronger 20% alpha recipe. |
| Pale gray | `#dedede` | `--color-silver` | text, action, surface | Dark-section body copy, secondary buttons and inverted action segments. |
| Warm paper | `#f1eee7` | `--color-paper` | background, surface | Light sections, opening copy panel and closing circular island. |
| White | `#ffffff` | `--color-white` | text | Headings and primary labels on charcoal. |

## Typography

- **GeistSans** — Headings, editorial copy, large numbers and quotations. Contemporary neutral grotesk, mostly regular and medium, with open unembellished shapes. If unavailable, use **Geist**. Use 400 and 500 weights. Font stack: "GeistSans", "Geist", ui-sans-serif, system-ui, sans-serif.
- **GeistMono** — Navigation, actions, technical captions, numbering and letter-based graphics. Even-width utilitarian lettering, usually uppercase outside prose and code. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-number | GeistSans | 500 | 265.4px | 0.82 | -0.045em | Monumental numeric proof, with a leading approximation mark where appropriate. |
| section-heading | GeistSans | 500 | 45.9px | 1.1 | normal | Main section leads and short stacked claims. |
| quotation | GeistSans | 400 | 45.9px | 1.1 | normal | Large conversational testimonial text. |
| opening-headline | GeistSans | 500 | 43.1px | 1 | normal | Compact two-line opening promise. |
| body | GeistSans | 400 | 17.5px | 1.25 | normal | Opening support, section introductions and expanded answers. |
| detail | GeistSans | 400 | 15.7px | 1.25 | normal | Feature descriptions and newsletter support. |
| technical-label | GeistMono | 400 | 15.7px | 1.25 | normal, uppercase | Eyebrows, numbered capabilities, question headings and media captions. |
| button-label | GeistMono | 400 | 15.7px | 1 | normal, uppercase | Word segments inside joined conversion buttons. |
| small-label | GeistMono | 400 | 13.7px | 1.25 | normal, uppercase | Navigation, scroll cue and testimonial attribution. |

**Notes:**

- The opening headline is slightly smaller and more tightly led than section headings; do not turn the opening into an oversized billboard.
- Ordinary headings retain normal tracking. Only monumental numbers tighten to -0.045em.
- Monospace is a structural labeling system, not a replacement for readable sans-serif paragraphs.

## Layout

**Density:** Airy at the chapter scale, dense inside technical demonstrations and numbered lists.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Between primary and secondary actions; bezel inset. |
| 12px | Vertical padding in numbered ticket rows. |
| 16px | Desktop grid gutters and support-to-form spacing. |
| 20px | Eyebrow-to-opening-headline gap. |
| 24px | Action horizontal padding, accordion vertical padding and common content group gap. |
| 32px | Opening headline-to-support gap and support-to-actions gap. |
| 40px | Ticket interior padding and footer top/bottom padding. |
| 48px | Quote-card interior padding. |
| 64px | Heading-group to offer-panel separation. |
| 80px | Desktop side gutters. |
| 96px | Gallery row separation and footer group-to-bottom-row gap. |
| 160px | Major section vertical padding. |

### Containers and grids

- **desktop frame**: max width 1440px · side padding 80px. At the desktop baseline, ordinary content spans 1280px between broad equal side gutters; artwork can bleed to the viewport edges.
- **editorial grid**: 12 columns · gap 16px. Align introductory copy and detail columns; the question list occupies seven columns beside a five-column heading and conversion area.
- **project gallery**: 2 columns · gap 24px. Two 628px-wide media tiles per desktop row, with 96px between rows.
- **introductory copy**: max width 600px. Section support paragraphs remain narrower than the full grid.
- **newsletter**: max width 448px · gap 4px. Compact inline email field and joined-word submit action.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and bezels | 8px |
| inset panels | 4px |
| offer ticket | 12px |
| status dot | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| instrument bezel | `0px 0px 0px 1px #000000, 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | Navigation, demo frames and testimonial outer frames; not ordinary text blocks. |

### Surfaces

#### Paper canvas · level 0

**Use:** Opening copy panel, quantitative proof, offer stage and footer.

**CSS:** `background-color: #f1eee7; color: #232323`

**Observed:** Flat warm paper with no paper-grain simulation.

**Transfer:** Use it as a broad contrasting field rather than tinting every card separately.

#### Charcoal field · level 0

**Use:** Capability chapters, gallery, testimonials and objections.

**CSS:** `background-color: #232323; color: #ffffff`

**Observed:** Broad dark sections carry faint typographic texture behind brighter foreground content.

**Transfer:** Keep background letters much dimmer than readable copy.

#### Checker bezel · level 1

**Use:** Small floating navigation and major framed demonstrations.

**CSS:** `background-color: #000000; background-image: repeating-conic-gradient(rgba(255,255,255,0.22) 0%, rgba(255,255,255,0.22) 25%, rgba(0,0,0,0) 0%, rgba(0,0,0,0) 50%); background-size: 4px 4px; border-radius: 8px; padding: 8px; box-shadow: 0px 0px 0px 1px #000000, 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** A tiny checkered edge wraps a flat charcoal inset with 4px corners and a fine white-alpha ring.

**Transfer:** Repeat this material on a few important instruments, not every content item.

## Components

### Floating navigation

**Use:** Persistent chapter navigation.

**CSS:** `position: fixed; top: 16px; padding: 8px; border-radius: 8px; background-color: #000000; z-index: 4`

**Text style:** `small-label` — GeistMono 400 · 13.7px/1.25 · uppercase

**Observed:** A centered 515px-wide instrument bezel contains a compact icon-and-links row and a pale announcement ticker beneath. Use Checker bezel for its exterior and a charcoal inset.

**Transfer:** Keep labels brief enough for the compact instrument format.

### Navigation link

**Use:** Chapter links inside the floating instrument.

**CSS:** `height: 30px; padding: 0px 12px; display: flex; align-items: center; color: rgba(255,255,255,0.55)`

**Text style:** `small-label` — GeistMono 400 · 13.7px/1.25 · uppercase

**Observed:** Uppercase labels sit in a single row; the selected chapter has a subtly brighter rectangular backing.

**States:** Declared: hover color #fff; focus-visible outline-style none.

### Joined ticket button

**Use:** Main conversion, reused in the opening, offer, objections and closing island.

**CSS:** `display: inline-flex; height: 48px; align-items: center; background-color: #232323; color: #ffffff; border-radius: 8px`

**Text style:** `button-label` — GeistMono 400 · 15.7px/1 · uppercase

**Observed:** Two independently rounded word segments, each with 24px horizontal padding, are connected by a narrow 6px bridge. Concave cuts at the top and bottom make the join read as a ticket perforation. A small orange dot sits in the upper-right segment. The dark-field variant uses pale-gray segments and charcoal labels.

**Transfer:** Choose a two-word action and keep both parts in one accessible control; construct the join with SVG or masked pseudo-elements.

### Secondary button

**Use:** Supporting media action beside the main conversion.

**CSS:** `height: 48px; padding: 0px 24px; border-radius: 8px; background-color: #dedede; color: #232323; display: flex; align-items: center`

**Text style:** `technical-label` — GeistMono 400 · 15.7px/1.25 · uppercase

**Observed:** A single solid rounded rectangle contrasts with the segmented primary action.

### Scroll cue

**Use:** Bottom-left invitation to enter the long-form story.

**CSS:** `display: flex; align-items: center; gap: 10px; padding: 12px 0px; color: #5b5a56`

**Text style:** `small-label` — GeistMono 400 · 13.7px/1.25 · uppercase

**Observed:** Three nested dotted circles precede a compact text label; it sits apart from the conversion row near the stage floor.

### Offer ticket

**Use:** A single prominent offer or pricing proposition.

**CSS:** `background-color: #232323; color: #ffffff; padding: 40px; border-radius: 12px; display: grid; grid-template-columns: minmax(0px, 7fr) minmax(0px, 5fr)`

**Text style:** `technical-label` — GeistMono 400 · 15.7px/1.25 · uppercase

**Observed:** One wide dark ticket has a giant price on the left and numbered inclusions plus edition selector and Joined ticket button on the right. A vertical dashed perforation and 14px concave cuts mark the join; numbered rows have faint white-alpha separators.

**Transfer:** Present one clear offer, not a conventional three-tier SaaS grid. Use the price treatment for another decisive commercial fact if needed.

### Testimonial panel

**Use:** Large human proof in a horizontal carousel.

**CSS:** `background-color: #232323; color: #ffffff; border-radius: 4px; padding: 48px; display: flex; flex-direction: column; justify-content: space-between; gap: 48px`

**Text style:** `quotation` — GeistSans 400 · 45.9px/1.1

**Observed:** The inset sits inside Checker bezel. A large multiline quotation is balanced by a small grayscale circular portrait and uppercase attribution at the bottom. The next panel remains partially visible, with a bracketed numeric pager below.

**Transfer:** Show complete readable quotes in the resting state, with specific experience rather than superlatives.

### Question row

**Use:** Numbered objection handling on the dark field.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 24px 0px; border-bottom: 1px solid rgba(255,255,255,0.15); color: #ffffff`

**Text style:** `technical-label` — GeistMono 400 · 15.7px/1.25 · uppercase

**Observed:** A muted question index precedes a bright uppercase question; a 24px square plus/minus control sits at the far edge. Expanded answers use body copy below the heading. The list spans 740px on desktop.

### Email field

**Use:** Low-pressure newsletter signup in the paper footer.

**CSS:** `height: 48px; width: 240px; padding: 0px 16px; border: 1px solid rgba(35,35,35,0.2); border-radius: 8px; background-color: rgba(0,0,0,0); color: #232323`

**Text style:** `technical-label` — GeistMono 400 · 15.7px/1.25 · uppercase

**Observed:** A light outlined field joins an adjacent segmented submit control with a 4px gap; the short explanation sits above.

### Footer bottom row

**Use:** Ownership and maker credit beneath the utility area.

**CSS:** `display: flex; align-items: center; justify-content: space-between; border-top: 1px solid rgba(35,35,35,0.15); padding-top: 24px; gap: 8px`

**Text style:** `technical-label` — GeistMono 400 · 15.7px/1.25 · uppercase

**Observed:** Copyright aligns left and a muted maker link aligns right beneath a long hairline. The row is separated from the signup and resource columns by 96px.

## Imagery and graphics

### Orbital word sculpture

**Use:** Signature opening artwork and monumental closing return.

**Observed:** Pale monospaced text bends into many concentric, slightly disrupted rings on charcoal, interspersed with fine dotted orbits. The opening crops the system into the right half; later it fills the viewport. The closing exposes a large clean circular paper center for a headline and action.

**Transfer:** Use a short product-specific vocabulary to construct the rings. A static SVG with the same density, edge clipping and circular negative space is the minimum acceptable version.

**Build:** Create 12–20 concentric SVG circle paths centered in the art panel; repeat uppercase Geist Mono text along textPath at alternating offsets. Increase letter size toward the outer rings, vary opacity from 0.15 to 1, and break a few runs into isolated glyphs. Add dotted circles using 1px pale strokes with wide dash spacing. Clip to the section. For closing, layer a paper-colored circle about 470px in diameter at the center above the rings, then place real HTML copy and an action above it.

### Character-built object field

**Use:** Dark capability chapters and the atmosphere behind proof content.

**Observed:** A large three-dimensional-looking object silhouette on the right is described entirely by tiny gray uppercase characters. A much fainter full-bleed text raster covers the background, while sharp sans-serif copy remains readable on the left.

**Transfer:** Turn a product-relevant object, diagram or abstract silhouette into a luminance-mapped text grid; an uncomplicated recognizable silhouette is enough when detailed art is unavailable.

**Build:** Render a monochrome object to a canvas and sample its luminance on an 8–12px monospace cell grid. Replace samples with letters from a small product vocabulary, using white alpha between 0.04 and 0.5 over charcoal. Scale the main silhouette to roughly half the page width on the right. Add a second, dimmer text layer across the whole field; mask both away from body copy as needed.

### ASCII project gallery

**Use:** Visual proof in a two-column gallery.

**Observed:** Wide 628×353px media windows show websites and scenes translated into dense grayscale character rasters. Small uppercase mono captions sit immediately below. The treatment unifies otherwise different projects without colorful card backings.

**Transfer:** Apply the same luminance-to-character processing to authentic product outputs, customer work or useful diagrams. Preserve enough contrast to distinguish each scene.

### Pixel-glyph seam

**Use:** Signature transition between paper and charcoal chapters.

**Observed:** The section boundary breaks into small square steps, short word fragments and isolated characters. Debris disperses above and below a jagged edge rather than forming a smooth wave.

**Transfer:** Repeat the seam device at major tonal changes, using vocabulary relevant to the new product.

**Build:** Use an SVG mask with a mostly horizontal boundary stepped in 8–24px rectangular cells. Scatter small monospace glyph fragments within about 160px of the edge, clustering them densely at the boundary and thinning with distance. Alternate paper and charcoal rectangular chips; keep the rest of each section flat.

### Framed product instrument

**Use:** Hands-on demonstration within a light chapter.

**Observed:** A broad dark editor-style interface with file tree, readable document and terminal sits in Checker bezel on paper. Dense muted interface detail contrasts with the spacious surrounding chapter.

**Transfer:** Show an authentic working interface for the new product; retain the dark framed staging without borrowing an unrelated code editor. Internal interface styling remains subordinate to the marketing hierarchy.

### Icons

**Observed:** A compact solid brand symbol anchors navigation. Utility icons are small restrained line marks; accordion toggles use simple plus/minus strokes in 24px squares. Portraits are circular and grayscale rather than colorful badges.

**Transfer:** Use minimal functional line symbols and a compact original brand mark; do not populate editorial sections with large decorative icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Split typographic opening

**Observed:** The first 900px contain the complete promise and primary artwork. Warm paper fills the left half; a charcoal orbital word sculpture fills the right half from top to bottom with no card frame. The centered Floating navigation overlaps both. A compact left-aligned copy group sits near the vertical middle inside the 80px gutter: uppercase eyebrow, 20px gap, two-line opening-headline, 32px gap to four short support lines, then 32px to Joined ticket button plus Secondary button separated by 8px. The copy width is about 511px. A Scroll cue sits near the bottom-left. Artwork clips at the outer edges and remains the dominant visual object; later proof chapters fall below the fold.

**Transfer:** Give a new product a short plainspoken promise and its own vocabulary-built orbital sculpture. Without dedicated media, make the SVG ring composition the main object. Shorter product pages can use this same split opening with fewer later chapters; secondary editorial pages can retain the restrained heading scale and framed navigation without duplicating the long scroll scene.

**Avoid:** Do not center all hero copy above a small decorative orb, enlarge the headline to fill the screen, or place the art inside a rounded card.

**Text style:** `opening-headline` — GeistSans 500 · 43.1px/1

### Cost made tangible

**Observed:** Paper chapter pairs a short three-line section-heading and brief support with an enormous proof-number on the left. On the right, a narrow dotted estimate sheet lists compact uppercase time or effort rows. The content pins while the number and ledger develop over a long scroll span.

**Transfer:** Quantify a real customer burden or outcome with a large numeric treatment and a concrete supporting ledger; do not fabricate a figure.

**Text style:** `proof-number` — GeistSans 500 · 265.4px/0.82 · tracking -0.045em

### Capability field

**Observed:** Charcoal field opens with a four-line section-heading and support on the left, a character-built object on the right, then numbered technical-label feature notes. Notes are narrow and stagger horizontally rather than forming a uniform card grid.

**Transfer:** Use a sequence of specific decisions or capabilities, with clear short titles and detail copy. Keep the object and text texture secondary to the reading path.

**Text style:** `section-heading` — GeistSans 500 · 45.9px/1.1

### Demonstration instrument

**Observed:** A large Framed product instrument sits within a spacious Paper canvas chapter, using Checker bezel and a dark inset. Pixel-glyph seams mediate its entry and exit.

**Transfer:** Give visitors a believable view of the actual tool or output. Let authentic detail carry authority instead of adding marketing labels to every control.

### Output and testimony

**Observed:** A left-aligned section-heading and narrow support introduce the two-column ASCII project gallery with 24px column gaps and 96px row spacing. Testimonial panel follows as a horizontally overflowing set with large quotations and small mono attribution.

**Transfer:** Pair visual results with concise first-hand testimony. Adapt the gallery length to available proof rather than filling empty slots.

### Single offer stage

**Observed:** Paper canvas with 160px vertical and 80px horizontal padding holds a three-line section-heading, a compact grayscale social-proof cluster and the Offer ticket. The wide ticket arrives after a 64px gap; a small qualification line follows below.

**Transfer:** Keep the commercial model unmistakable and put inclusions into numbered rows rather than multiple competing cards.

**Text style:** `section-heading` — GeistSans 500 · 45.9px/1.1

### Objection columns

**Observed:** On Charcoal field, a five-column left rail carries the heading and Joined ticket button while a seven-column right rail holds Question row items. A bright first answer is expanded; the other questions remain compact separated rows.

**Transfer:** Use factual buyer objections, enough detail to remove uncertainty and a repeated conversion in the supporting rail.

**Text style:** `section-heading` — GeistSans 500 · 45.9px/1.1

### Circular closing and utility footer

**Observed:** Orbital word sculpture returns full bleed around a roughly 470px Paper canvas circle containing a two-line benefit and Joined ticket button. The bottom dissolves through Pixel-glyph seam into a paper footer. The footer has a compact brand lockup and short newsletter promise on the left, resource and legal columns to the right, an Email field with segmented submit, and Footer bottom row below a 96px gap.

**Transfer:** End with a concise reclaimed-benefit statement inside the circular island, then offer a quieter ongoing relationship in the footer. Keep utility links distinctly smaller in narrative importance than the closing action.

**Text style:** `section-heading` — GeistSans 500 · 45.9px/1.1

## Page flow

**Storyline:** Promise → tangible cost → decisions and capabilities → working demonstration → output proof → human proof → offer → objections → benefit reclaimed → ongoing relationship.

### Long-form expert-product landing page that earns a purchase through concrete detail and distinctive typographic staging

1. **Promise** — Split paper copy and immersive word sculpture, with paired actions.
2. **Quantified problem** — Monumental number beside a compact effort ledger.
3. **Capability chapters** — Staggered numbered explanations across a dark character field.
4. **Product demonstration** — Wide authentic interface in a checker bezel.
5. **Outcome proof** — Monochrome ASCII gallery with terse captions.
6. **Social proof** — Large conversational quotations in framed carousel panels.
7. **Commercial offer** — One perforated dark ticket on paper, with giant commercial figure and numbered inclusions.
8. **Objection handling** — Two-column heading and numbered expandable question list.
9. **Closing call** — Paper circular island amid oversized orbital type.
10. **Ongoing relationship** — Practical signup and resource columns on paper, followed by a ruled ownership row.

**Transfer:** Use only the narrative blocks that help a new buyer decide, while retaining the distinctive orbital artwork, typographic material, ticket action and circular close. Compress proof into fewer stronger examples on shorter pages.

## Writing

Confident, practical and maker-led. Technical specificity establishes credibility, while short benefit statements keep it human rather than sounding like documentation.

**Do not copy:** Do not reuse the brand name, wordmark, author identity, customer names, testimonials, prices, time-saving figures, adoption counts or product-specific claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you; the maker can use my or I when describing first-hand work. Product explanations name concrete parts and actions instead of an abstract corporate we.
- **Rhythm:** Headlines tend to be short statements split across two to four lines. Support uses compact sentences and lists of concrete nouns, sometimes ending with three clipped imperative verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name a familiar task or object, then negate a recurring frustration. | 6–10 words | “The stack agents don't reinvent.” |
| Section lead | A concrete problem followed by a short emphatic sentence. | 8–16 words | “The page builder alone costs you days. Every single time.” |
| Supporting copy | Specific implementation nouns establish scope before a brief benefit. | 2–4 short sentences | “This is the part nobody quotes for and everybody rebuilds. Days gone before the real work starts.” |
| Action | Two plain words with a practical verb. | 2 words | “Get access”<br>“Watch reel”<br>“Stay updated” |
| Closing benefit | Return the opening cost to the reader as something regained. | 6–10 words | “The next 5 days are yours.” |
| Newsletter promise | Describe exactly when contact happens, minimizing implied noise. | One sentence | “One short email when the repo changes or a discount goes live.” |

**Words and phrasing to use:** already made; real work; shipped; decisions; handled; production; clone; rename; ship

**Avoid:** revolutionary; game-changing; unlock your potential; seamless solutions; world-class ecosystem

**Rules:**

- State the operational detail before the broad advantage.
- Keep technical labels compact and descriptive; paragraphs remain conversational.
- Use numbers only when they are supportable and useful to the buying decision.
- Let the closing line resolve a tension raised earlier rather than introducing a new feature.

## Do's and Don'ts

### Do

- Keep broad section fills to paper #f1eee7 and charcoal #232323.
- Use 500-weight 45.9px/1.1 section headings rather than oversized heavy display text.
- Keep body support at 17.5px/1.25 and smaller detail at 15.7px/1.25.
- Reserve 265.4px numerals and -0.045em tracking for a few dramatic proof moments.
- Use the 48px segmented action with 8px corners throughout conversion moments.
- Stage full-width art against 80px-gutter editorial content.
- Include the 4px checker texture in instrument bezels and repeat the glyph seam at major tonal transitions.
- Keep offer interiors at 40px padding and quote interiors at 48px padding.

### Don't

- Do not use orange as a button fill or broad promotional band; it is a tiny signal dot.
- Do not replace ticket controls with fully rounded capsule buttons.
- Do not give every feature a shadowed card; numbered notes sit directly on their chapter field.
- Do not apply negative tracking to ordinary headings; their tracking is normal.
- Do not mix saturated stock photography into the ASCII gallery treatment.
- Do not use pale low-opacity type for substantive paragraphs on charcoal; use #dedede.
- Do not spread the compact floating navigation into a full-width conventional header bar.
- Do not turn the practical paper footer into a second dark mega-navigation chapter.

## Motion and responsive

### Motion

**Observed:**

- Navigation color transitions are declared at 0.3s cubic-bezier(.4, 0, .2, 1); button segment color transitions at .15s with the same curve.
- Scroll-cue animation is declared as heroScrollCue 1.44s steps(8, end) infinite.
- A cursor blink is declared at .9s steps(1, end) infinite. Labels and numerical displays use odometer-like duplicated text structures.
- Scroll progression changes the orbital scene, the quantitative proof and the letter-built boundary treatment. An announcement ticker runs linearly.

**Transfer:**

- Keep the stepped mechanical character of the scroll cue and the compact rolling-label treatment rather than adding springy bounces.
- Use a complete static SVG version of the orbital composition and a fully readable quote as the reduced-motion presentation.

**Unknown:**

- Exact orbital motion, scroll interpolation and ticker duration are not established.
- Partial quotation reveals are not the intended resting content state.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Layout declarations use a single-column base and a 12-column large-screen grid. Side padding changes from 16px to 80px; the fixed header changes from left alignment with 8px padding to centered with 16px padding.
- The offer ticket declares stacked halves at smaller sizes and horizontal halves on larger layouts.

**Transfer:**

- On narrow screens stack copy above the orbital artwork while preserving a generous circular crop; do not shrink the entire desktop scene into an unreadable miniature.
- Stack ticket halves and move their perforation to the horizontal join. Collapse the gallery and question rails to one column.
- Preserve legible mono labels and show the complete conversion label as one control when space is constrained.

**Unknown:**

- Only desktop visual behavior is established; exact mobile typography, artwork height and navigation expansion behavior remain unspecified.
- Viewport-relative type formulas are not available; the listed recipes define the desktop baseline.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
