# Glossier — everyday polish, handwritten play

## Overview

A bright, approachable retail style pairs matter-of-fact grotesk typography with tactile product photography and playful hand-drawn gestures. White and pale pink carry most of the experience, with electric blue giving announcements and promotions a sharp jolt. It suits personal, design-conscious products whose materials, packaging and everyday use deserve more space than their sales copy. The imagery is expansive while navigation, labels and purchasing controls remain compact.

### Essentials

- Small sales copy lives inside a big visual statement: a 670px full-width opening carries a 384px white information card with 16px padding, a 20px regular headline and a 40px rectangular action.
- Hierarchy stays conversational rather than monumental: Apercu at weight 400, 14px/1.4 body copy, 12px/1.7 uppercase section labels, and a 32px/1.3 promotional lead; oversize lettering belongs to artwork rather than every heading.
- Buttons look like cut-paper tabs with an incomplete frame: square corners, 8px 16px padding, 40px height, and black 1px bottom and right edges; blue fills mark conversion moments.
- White shelving and pale blush bookends let objects supply the color: #ffffff canvas, #f7f7f7 product stages and #faf2f4 closing band dominate, while #0600ff is concentrated in the 32px announcement strip, badges and promotional artwork.
- Objects are given air, not card chrome: four 340px product columns separated by 16px, isolated products low in pale portrait stages, then paired tactile photographs and unequal-height editorial images.
- A friendly drawn gesture signs off the commerce: an oversized black freehand emblem about 454px wide occupies the lower right of the blush ending. Carry an original hand-drawn sign into every new page; when photography is unavailable, pair a carefully lit object render with simple original line art.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Badge pink | `#f6e3e6` | `--color-badge-pink` | surface | Secondary status badge beside an electric-blue promotional badge. |
| Blush paper | `#faf2f4` | `--color-closing` | background | Expansive closing information band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0600ff` | `--color-electric` | background, accent, action | Announcement strip, conversion button and promotional badges. A full blue field belongs to a promotional opening rather than all sections. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, border | Primary typography, fine action edges and drawn graphics. |
| Secondary gray | `#666666` | `--color-muted` | text | Product classification and supporting metadata. |
| Selected gray | `#e8e8e8` | `--color-selected` | surface | Selected option cells, distinguished additionally by a black perimeter. |
| Option gray | `#f0f0f0` | `--color-option` | surface, border | Unselected choice cells; also the visible result of the navigation's 6% black hairline over white. |
| Studio gray | `#f7f7f7` | `--color-stage` | surface | Pale product-image backing; keeps transparent and light objects legible. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, information panels and reversed text on electric blue. |

## Typography

- **Apercu** — All headings, navigation, body and actions. Friendly grotesk with open counters and an unforced regular weight. If unavailable, use **DM Sans**. Use regular 400 and retain the small measured sizes rather than compensating with bold weights. Font stack: "Apercu", "DM Sans", "Gill Sans", sans-serif.
- **Apercu Mono** — Compact uppercase product badges. Practical monospaced markings that contrast with the conversational sans. If unavailable, use **Roboto Mono**. Use weight 400 for compact retail labels. Font stack: "Apercu Mono", "Roboto Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| promo-heading | Apercu | 400 | 32px | 1.3 | normal | Short horizontal offer or benefit announcement. |
| hero-heading | Apercu | 400 | 20px | 1.4 | normal | Main heading in the white opening information card. |
| body | Apercu | 400 | 14px | 1.4 | normal | Support paragraphs, product names, prices and editorial captions. |
| button | Apercu | 400 | 14px | 1.15 | 0.002em | Compact opening and section-header actions. |
| card-action | Apercu | 400 | 14px | 1.4 | 0.002em | Full-width product actions and centered photographic tile labels. |
| choice | Apercu | 400 italic | 14px | 1.4 | normal | Product size or format choices. |
| footer-link | Apercu | 400 | 14px | 20px | 0.002em | Utility links in the closing columns. |
| section-label | Apercu | 400 | 12px | 1.7 | 0.003em, uppercase | Compact section leads, opening eyebrow and footer column headings. |
| badge | Apercu Mono | 400 | 12px | 1.4 | normal, uppercase | Product status and promotional flags. |
| category-caption | Apercu | 400 | 12px | 1.7 | 0.04em, uppercase | Labels below category photographs. |

**Notes:**

- Use regular weight throughout; hierarchy comes from placement, capitalization and image scale more than weight changes.
- Section titles are smaller than paragraph text. The 32px promotional lead is an exception, not a default section heading.
- Large repeated campaign lettering is a graphic layer, separate from the readable heading in the opening card.

## Layout

**Density:** Compact retail controls inside airy, image-led sections; close reading distances coexist with large photographic fields.

### Spacing

**Spacing system:**

- **vertical rhythm** 8px, vertical — Principal vertical spacing rhythm for panels, controls and section separation; small text stacks use finer increments.

| Value | Use |
| --- | --- |
| 6px | Category image-to-caption gap. |
| 8px | Opening eyebrow and heading separation; spacing between adjacent badges. |
| 16px | Page side gutters, grid gaps, white panel padding and main image-to-content separation. |
| 24px | Horizontal gap from a small promotional object image to its text. |
| 48px | Breathing space before a paired editorial feature. |
| 56px | Inset from the top of the opening visual to its information card. |
| 80px | Broad breathing spaces between commerce and closing content. |

### Containers and grids

- **page-container**: max width 1920px · side padding 16px. Near-edge-to-edge desktop content, centered only once the maximum width is reached. Hero art and closing color extend full bleed.
- **opening-card**: max width 384px · side padding 16px. Compact left-aligned message overlay, leaving most of the visual unobscured.
- **product-shelf**: 4 columns · gap 16px. Four equal 340px cards at a 1440px desktop width, with shared image and action baselines.
- **paired-features**: 2 columns · gap 16px. Two equal 696px photographic links with centered white labels.
- **category-strip**: 5 columns · gap 16px. Five 269px category tiles with concise uppercase captions.
- **editorial-trio**: 3 columns · gap 16px. Three equal-width photographs about 459px wide, preserving different image heights and independent captions.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons-and-media | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Main page and unboxed content.

**CSS:** `background: #ffffff; color: #000000`

#### Studio stage · level 0

**Use:** Product photographs and category imagery.

**CSS:** `background: #f7f7f7; border-radius: 0px; box-shadow: none`

**Observed:** A flat pale field supports the object; the container itself has no decorative edge.

**Transfer:** Match image backing to the stage so the object feels isolated rather than boxed.

#### Information slip · level 1

**Use:** Readable message layered on the opening visual.

**CSS:** `background: #ffffff; padding: 16px; max-width: 384px; border-radius: 0px; box-shadow: none`

**Observed:** A plain opaque rectangle interrupts the louder graphic behind it.

**Transfer:** Keep the panel small and its text concise so the visual remains dominant.

#### Blush closing band · level 0

**Use:** Brand statement, practical links and large drawn sign-off.

**CSS:** `background: #faf2f4; padding: 16px; color: #000000`

**Observed:** A continuous pale pink field, not separate raised footer cards.

**Transfer:** Let empty space and an original drawn emblem give the ending its character.

## Components

### Announcement strip

**Use:** Persistent concise offer or service message.

**CSS:** `background: #0600ff; color: #ffffff; height: 32px; position: fixed; top: 0px; width: 100%; z-index: 13`

**Text style:** `body` — Apercu 400 · 14px/1.4

**Observed:** Left-aligned text with a small inline underlined action; previous, next and pause controls sit at the far right. It sits above the navigation.

**Transfer:** Use a true offer or service fact, not a long slogan.

### Navigation bar

**Use:** Persistent product browsing and utility access.

**CSS:** `background: #ffffff; height: 40px; position: fixed; top: 32px; width: 100%; border-bottom: 1px solid rgba(0,0,0,0.06); z-index: 13`

**Text style:** `section-label` — Apercu 400 · 12px/1.7 · tracking 0.003em · uppercase

**Observed:** A compact italic wordmark anchors the left, a horizontal category list occupies the middle, and search, region, stores, login and bag utilities sit right. Category text uses 12px with 19.6px line height.

**States:** Declared: hover category links gain a 1px bottom border and retain no text decoration.

**Transfer:** Keep the utility band narrow and use the new product's own short categories.

### Primary button

**Use:** Opening conversion action.

**CSS:** `background: #0600ff; color: #ffffff; height: 40px; padding: 8px 16px; border: 0px; border-radius: 0px; display: inline-flex; align-items: center; justify-content: center; background-image: linear-gradient(#000000,#000000), linear-gradient(#000000,#000000); background-size: 100% 1px, 1px 100%; background-position: 0px 100%, 100% 0px; background-repeat: no-repeat`

**Text style:** `button` — Apercu 400 · 14px/1.15 · tracking 0.002em

**Observed:** A compact content-width rectangle with a fine bottom-and-right framing device rather than a rounded enclosing outline.

### Shelf action

**Use:** Product conversion or secondary section action.

**CSS:** `background: #ffffff; color: #000000; height: 40px; padding: 8px 16px; border: 0px; border-radius: 0px; width: 100%; background-image: linear-gradient(#000000,#000000), linear-gradient(#000000,#000000); background-size: 100% 1px, 1px 100%; background-position: 0px 100%, 100% 0px; background-repeat: no-repeat`

**Text style:** `card-action` — Apercu 400 · 14px/1.4 · tracking 0.002em

**Observed:** Full-width on product cards. The section-header version is content width and uses the shorter button line height; actions align across the shelf.

**States:** Declared: hover and active section-header actions retain text-decoration none.

### Product card

**Use:** Comparable products or purchasable formats.

**CSS:** `display: flex; flex-direction: column; border-radius: 0px; box-shadow: none`

**Text style:** `body` — Apercu 400 · 14px/1.4

**Observed:** A pale image stage carries top-left badges. Below it come linked name, gray category, black price and italic format choices. Description space stretches so the Shelf action lands at the same baseline across cards. At desktop the card is 340px wide and 652px high, with an image wrapper 411px high.

**Transfer:** Keep comparable metadata in a consistent order and show the object clearly before asking for a choice.

### Status badge

**Use:** Short product status or promotion pinned to image top-left.

**CSS:** `background: #0600ff; color: #ffffff; height: 24px; padding: 1px 8px; border-radius: 0px`

**Text style:** `badge` — Apercu Mono 400 · 12px/1.4 · uppercase

**Observed:** Rectangular mono flags sit in a row with an 8px gap. Secondary badges use pale pink with black text.

**Transfer:** Use one useful status and at most one complementary label rather than a stack of pills.

### Format selector

**Use:** Choose a product's size or format.

**CSS:** `display: flex; background: #f0f0f0; height: 44px; padding: 7px 21px; border-radius: 0px`

**Text style:** `choice` — Apercu 400 italic · 14px/1.4

**Observed:** Adjacent gray rectangular cells form a continuous choice strip. The selected cell uses the darker gray, a 1px black perimeter and a white inset outline; the widest cell uses 27px horizontal padding.

**Transfer:** Use italic labels for short format distinctions; keep selected state visible without relying on color alone.

### Photographic link tile

**Use:** Image-led discovery links.

**CSS:** `position: relative; background: #f7f7f7; border-radius: 0px`

**Text style:** `card-action` — Apercu 400 · 14px/1.4 · tracking 0.002em

**Observed:** Two broad photographs sit side by side. A centered white label floats on each image; its tab uses 11px 16px padding, about 42px height, and the same bottom-and-right edge as Shelf action.

**Transfer:** Choose enough visual quiet near the center to keep the label readable.

### Category tile

**Use:** Fast visual browsing across product families.

**CSS:** `display: flex; flex-direction: column; gap: 6px; border-radius: 0px`

**Text style:** `category-caption` — Apercu 400 · 12px/1.7 · tracking 0.04em · uppercase

**Observed:** Five pale-backed portrait images form a row, each with a left-aligned uppercase label beneath. Image size is about 269px by 341px.

**Transfer:** Give each category one clear representative object rather than miniature collages.

### Footer link

**Use:** Practical navigation in the closing band.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `footer-link` — Apercu 400 · 14px/20px · tracking 0.002em

**Observed:** Links form vertical lists under small uppercase headings. Rows are about 29px apart and the columns spread widely across the band.

**States:** Declared: hover and active text-decoration underline.

**Transfer:** Group links by reader task, with legal material kept in a separate low baseline.

## Imagery and graphics

### Isolated product portrait

**Use:** Product shelves and category navigation.

**Observed:** Small sculptural bottles stand low and centered against almost white gray. Soft directional light produces delicate side shadows and reveals frosted glass, translucent liquid and colored caps. The surrounding negative space is substantial; images dominate their cards.

**Transfer:** Use a well-lit packshot or a simple physically plausible render on #f7f7f7, with a soft contact shadow and generous clearance above the object.

### Tactile editorial photograph

**Use:** Paired discovery tiles and lifestyle stories.

**Observed:** Packaging, pink tissue, ribbons, metallic scissors and transparent tape create close, touchable still lifes. Other images show objects among books or on a bathroom surface, and a person using the product at a mirror. Colors stay natural and softly lit; square, portrait and landscape ratios coexist without a universal crop.

**Transfer:** Photograph the new product with ordinary materials that explain its use or ritual. Mix a restrained studio view with a believable lived-in setting; preserve meaningful native aspect ratios.

### Drawn closing sign

**Use:** Large friendly signature device in the ending.

**Observed:** A black freehand smiling gesture and waving shape occupy roughly 454px by 243px in the lower right of a spacious blush footer, much larger than any utility text.

**Transfer:** Create a distinct original gestural emblem related to the new product's personality, using the same blunt hand-drawn warmth rather than a polished corporate icon.

**Build:** Use a transparent SVG with two irregular open-contour forms, rounded line joins and ends, and black strokes around 12–18px at a 454px-wide rendered size. Add two or three simple filled marks for personality. Place it at the lower right on blush with ample empty space around it; do not enclose it in a badge.

### Typographic promotion field

**Only for:** promotional openings

**Use:** High-impact campaign visual behind a restrained information slip.

**Observed:** Electric blue fills the entire opening. Four oversized rows of white uppercase lettering run beyond the horizontal edges, interrupted by loose white line drawings. The repeated words function as pattern, with the actual offer stated separately in the white card.

**Transfer:** Replace the repeated phrase with a short new campaign line and original drawings. A static typographic composition is sufficient.

**Build:** Create a 670px-high overflow-hidden blue field. Stack four single-line rows in regular sans at roughly 140px with a roughly 172px row pitch at 1440px width; offset alternate rows horizontally so words are clipped at both edges. Insert original white SVG outline drawings about 100–200px wide, using loose 2–3px round-ended strokes. Layer the white Information slip above the pattern.

### Icons

**Observed:** Utility glyphs are tiny and functional: roughly 12–17px, black on white or white on blue. Arrows, pause, search and bag functions remain visually subordinate; the large drawn closing sign is a separate illustration language.

**Transfer:** Choose simple single-color utility glyphs and reserve expressive irregular strokes for editorial artwork.

## Section recipes

How recurring sections are built.

### First screen: Graphic field and information slip

**Observed:** A fixed 32px Announcement strip and 40px Navigation bar leave the opening visual starting below 72px of chrome. A 670px-high full-bleed typographic blue field fills most of the first screen. The white Information slip sits toward the upper left, inset 16px from the side and 56px from the visual's top, with a 384px maximum width and 16px padding. Its stack is a small uppercase eyebrow, a 20px regular heading, two short lines of 14px support and a Primary button separated from support by 16px. Behind it, huge white repeated lettering and line drawings carry the scale. Within the first 900px, the full opening, all copy and the action are visible, followed by the next shelf's heading, right-aligned action and upper image edges; the product details are below the fold.

**Transfer:** Make the dominant visual a coherent graphic field rather than enlarging the sales heading. For a non-promotional product introduction, use a tactile product scene at the same scale while retaining the compact message slip and original drawn gesture elsewhere. Without suitable photographs, use a clean object render plus original line art. Detail-oriented pages can open with the same small heading and a single dominant product image.

**Avoid:** Do not replace this with a centered giant headline above a pair of pill buttons, or shrink the artwork into a boxed illustration beside a long paragraph.

**Text style:** `hero-heading` — Apercu 400 · 20px/1.4

### Compact heading and shopping shelf

**Observed:** A 12px uppercase section label anchors the left while a white Shelf action sits at the right. After 16px, a four-column Product card shelf uses 16px gutters and aligned purchase actions. Thin segmented progress marks sit beneath the row.

**Transfer:** Use this for comparable offers or formats; preserve visual equivalence and compact headings instead of adding a second display headline.

**Text style:** `section-label` — Apercu 400 · 12px/1.7 · tracking 0.003em · uppercase

### Horizontal benefit strip

**Observed:** A 128px square product image sits beside a 32px regular promotional lead, short support and an underlined terms link. The image-to-copy gap is 24px and vertical padding is 16px.

**Transfer:** Use a compact tangible benefit or bonus between larger image chapters. Keep the statement short enough to read at a glance.

**Text style:** `promo-heading` — Apercu 400 · 32px/1.3

### Paired photographic invitations

**Observed:** Two equal landscape Photographic link tiles span the container with a 16px gap. White centered tabs carry the only overlaid copy; imagery and physical materials do the storytelling.

**Transfer:** Pair two useful discovery paths with photographs that share light quality but differ in composition.

### Visual category index

**Observed:** A five-column Category tile row uses 16px gaps, pale image fields and 12px uppercase captions with 0.04em tracking.

**Transfer:** Use a short visual taxonomy between narrative blocks, keeping each object legible without dense explanation.

**Text style:** `category-caption` — Apercu 400 · 12px/1.7 · tracking 0.04em · uppercase

### Unequal-height editorial trio

**Observed:** A small uppercase heading precedes three equal-width images separated by 16px. Their heights differ: about 574px, 688px and 459px; captions sit 16px below their own images. There are no matching card boxes or shared caption baseline.

**Transfer:** Mix human use, contextual still life and close product detail. Let native image ratios create an editorial rhythm.

**Text style:** `body` — Apercu 400 · 14px/1.4

### Blush utility ending with drawn signature

**Observed:** After an 80px white breathing space, the Blush closing band runs about 763px tall. A short brand paragraph occupies roughly the left third near the top. Four widely separated link columns follow, with two grouped left and two right, leaving an open center. Legal links sit along the lower left while the large Drawn closing sign occupies the lower right. The ending is practical and playful rather than another oversized sales call.

**Transfer:** Close with a brief belief in the user's everyday experience, task-oriented navigation and an original large drawn signature. Preserve the broad empty area even with fewer links.

**Text style:** `body` — Apercu 400 · 14px/1.4

## Page flow

**Storyline:** visual offer → comparable choices → tangible benefit → discovery paths → everyday-use inspiration → practical links and friendly sign-off

### An image-led retail landing page balancing immediate purchase with discovery

1. **Promise** — Full-bleed campaign art with a compact white message and direct action.
2. **Product comparison** — Four pale product portraits, small badges, format choices and aligned purchase controls.
3. **Conversion incentive** — A compact horizontal benefit with a small object image and larger regular-weight line.
4. **Discovery** — Paired tactile photographic links followed by a compact visual category index.
5. **Usage inspiration** — Three differently proportioned photographs with conversational captions.
6. **Closing reassurance** — Blush utility band, short brand belief, practical navigation, legal baseline and large drawn gesture.

**Transfer:** Adapt the number and order of discovery blocks to the product. Preserve the contrast between small functional copy, large physical imagery and an expressive friendly sign-off.

## Writing

Warm, direct and lightly cheeky. The writing sells an everyday pleasure without making it sound complicated or exclusive; practical commerce language stays plainly useful.

**Do not copy:** Do not reuse Glossier names, product names, trademarks, branded illustrations, campaign artwork, proprietary slogans or factual offers, prices and claims. Examples describe tone and structure, not reusable assertions. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your; use we for the brand's beliefs and service commitments.
- **Rhythm:** Short benefit headlines, brief sentence pairs and simple imperative actions. Exclamation marks accent a real offer rather than appearing on every line; captions often read as one friendly sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State a concrete immediate benefit with everyday words. | 5–9 words | “Take 20% off all Best Sellers!” |
| Support | A friendly pair of clipped sentences followed by a practical condition. | 2–3 short sentences | “Treat yourself now. Thank yourself later. Available now for a limited time.” |
| Section label | Plain uppercase shopping or discovery cue. | 2–3 words | “SHOP SALE”<br>“GET THE LOOK” |
| Action | Short familiar verb phrase with no cleverness to decode. | 2–3 words | “Shop now”<br>“Add to bag” |
| Editorial caption | Suggest a personal ritual or useful occasion in one casual line. | 5–10 words | “Gift, stock up or treat yourself to something new.”<br>“Save big on your signature scent.” |
| Closing belief | Human-centered we statement that ends by reassuring the reader. | One short paragraph | “We believe beauty is about having fun, celebrating freedom, and being present.” |

**Words and phrasing to use:** you; your; we; treat yourself; everyday language; plain shopping verbs; concrete formats and conditions

**Avoid:** disruptive; revolutionary; unparalleled; elite; technical jargon in promotional headlines; overwrought luxury language

**Rules:**

- Make the action more literal than the campaign line.
- Keep conditions and terms close to the offer without letting them dominate the paragraph.
- Let captions add a use or occasion, not repeat the product name.
- Use uppercase for labels and statuses; keep sentences in normal sentence case.

## Do's and Don'ts

### Do

- Keep readable opening headings at 20px and weight 400 even when the artwork behind them is enormous.
- Use 16px side gutters and 16px grid gaps to let photography approach the page edges.
- Keep commerce actions 40px high with square corners and fine bottom-and-right framing.
- Use 12px mono uppercase type for image badges and 14px italic type for format choices.
- Pair low-density pale product stages with materially rich editorial photographs.
- Give the pale blush ending enough space for a roughly 454px-wide original drawn gesture.

### Don't

- Do not turn all section labels into 48px bold marketing headlines; their default role is 12px uppercase.
- Do not use gray text for prices or primary product names; reserve #666666 for supporting classification.
- Do not introduce rounded card shells, pill badges or soft drop shadows into the flat shelf system.
- Do not wash the whole page in blue; keep broad reading areas white and the ending pale blush.
- Do not give the three editorial images identical heights merely to align their captions.
- Do not use the mono face for paragraphs; its role is compact product flags.

## Motion and responsive

### Motion

**Observed:**

- Primary and shelf actions declare font-size 0.4s ease-in-out transitions.
- The announcement content changes between short offers and provides previous, next and pause controls.
- Navigation and footer containers declare 0.2s ease-in-out transitions; the affected properties are not specified.

**Transfer:**

- If rotating announcement messages, preserve a visible pause control and keep the strip height stable.
- Keep the typography-pattern opening effective as a static field; it should not rely on animation to communicate the offer.

**Unknown:**

- Announcement timing, the visible marching-edge animation behavior and exact carousel movement were not established.

### Responsive

**Observed:**

- Desktop composition uses a 1920px maximum container with 16px side gutters.
- Declared stylesheet breakpoints include 767px, 768px, 979px, 980px, 1024px and 1025px.

**Transfer:**

- On narrow screens, retain the small information slip and give its text priority over the decorative repeated lettering.
- Reduce shelf columns or expose a horizontal shelf rather than making objects and 14px purchase text illegibly small.
- Stack the paired photographs and closing link groups while retaining the original drawn signature and pale blush field.

**Unknown:**

- Exact mobile grid counts, navigation collapse, image substitutions and type changes are not established. These narrow-screen adaptations are guidance rather than a measured layout.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
