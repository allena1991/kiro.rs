# Clau. — fat letters, loud colour fields

## Overview

A playful, art-director portfolio style: whole screens of flat colour (lavender, ink-black, cobalt, white) carry gigantic ultra-black display letters next to a calm neo-grotesk set at large, relaxed sizes. It suits personal studios, creative agencies, record labels, illustrators and launch pages for expressive products that want to feel hand-made and confident rather than corporate. Mostly light-and-lavender at the top with dark chapters below; imagery is vivid illustration, 3D renders and object photography staged edge-to-edge on solid bands. Density is airy and sparse: few words, huge type, generous vw-based padding.

### Essentials

- The headline is a sculpture, not a sentence: one or two words in an ultra-black display face filling the width — 504px/1 (about 35vw) for the brand mark, 288px/1.05 for chapter words such as a section name, weight 400 of the fat cut, tracking normal, colour #1a1a1a on light fields or #ffffff on dark ones.
- Everything else is one neo-grotesk at regular weight only, sized big and relaxed: 30px/40px for the reading voice, 20px/30px for lists and captions, 20px/26px for nav; no bold except emphasis inside a paragraph (700), no small text below 20px.
- Colour arrives as whole-viewport flat fields, never as accents on components: a lavender #8e93ff opening field, ink #1a1a1a / near-black #0b0f1a / #0d0d0d dark chapters, a cobalt #5277f6 band, white #ffffff in between. No gradients, no shadows, no borders, no rounded cards.
- A fixed round sticker always floats in the bottom-left corner: a 150px circle (radius 75px) in signal green #5cd987 with circular uppercase text running around a 60px line-drawn smiley; on hover it turns lavender #8e93ff.
- Links are plain text with underlines, never buttons: underline with 4px offset, an ↗ arrow after outbound links, the same colour as the text; navigation is four bare 20px words in the top corners.
- Discipline names run as oversized sliding lines: 144px (10vw) grotesk h2 lines offset horizontally past the viewport edges, separated by a 4px #1a1a1a rule across the container.
- The page ends on a dark #1a1a1a contact screen with a giant fat-display call (e.g. a two-word 'email me' stack) and a green marquee ticker along the bottom edge with a pill-outlined 'Get in touch' and a smiley glyph.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender field | `#8e93ff` | `--color-lavender` | background, accent | Opening field of the main page: the whole intro, bio and info-columns chapter sit on it; also the sticker's hover fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal green | `#5cd987` | `--color-signal-green` | background, accent | The floating sticker and the closing marquee ticker strip; the only small-area colour on the site. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ink | `#1a1a1a` | `--color-ink` | text, background, border | All text on light fields, the 4px separator rule, and the dark gallery / closing contact fields. |
| Paper | `#ffffff` | `--color-paper` | background, text | White gallery chapters and pairs-of-images bands; text colour on all dark fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| project case-study pages | Cobalt | `#5277f6` | `--color-cobalt` | background | Saturated blue band behind three-up image rows, used as a rhythm break among dark chapters. |
| project case-study pages | Black | `#000000` | `--color-black` | background | Behind edge-to-edge full-bleed image strips with no padding. |
| project case-study pages | Coal | `#0d0d0d` | `--color-coal` | background | Near-black bands holding single wide hero images. |
| project case-study pages | Night navy | `#0b0f1a` | `--color-night` | background | Blue-black field behind a project opening, its info block and selected full-width image bands. |
| project case-study pages | Graphite | `#191919` | `--color-graphite` | background | Alternate near-black image band, barely distinct from coal. |

## Typography

- **Beastly clauworks** — Giant wordmark and one- or two-word chapter titles only. Ultra-black, high-contrast poster serif with fat rounded bowls, tiny counters and notch-like ink traps; reads as sculpture at 288px and above. If unavailable, use **Ultra**. single weight 400; keep tracking normal and line height 1–1.05; never set below about 120px. Font stack: "Beastly clauworks", "Ultra", Georgia, serif.
- **Suisse Intl clauworks** — Every other text: headings, paragraphs, lists, nav, captions, links. Neutral Swiss neo-grotesk, set at regular weight with normal tracking and generous sizes. If unavailable, use **Inter**. weights 400 and 700; keep tracking normal (do not tighten). Font stack: "Suisse Intl clauworks", "Inter", Helvetica Neue, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| wordmark | Beastly clauworks | 400 | 504px | 1 | normal | size 35vw | The brand mark or a one-word promise spanning the full width in the opening and repeated near the end of long pages. |
| chapter-display | Beastly clauworks | 400 | 288px | 1.05 | normal | size 20vw | Chapter words stacked over two lines (e.g. a gallery title, the closing call), left-aligned at the container edge. |
| sliding-line | Suisse Intl clauworks | 400 | 144px | 1.15 | normal | size 10vw | Oversized discipline lines (two h2s with an em dash pair each) that overflow the viewport and slide sideways. |
| next-link | Suisse Intl clauworks | 400 | 72px | 1.15 | normal | fixed | Right-aligned 'Next project ↗' style link closing a case study. |
| lead | Suisse Intl clauworks | 400 | 30px | 40px | normal | fixed | The reading voice: bio paragraphs in a narrow right-hand column, with inline underlined links. |
| body | Suisse Intl clauworks | 400 | 20px | 1.5 | normal | fixed | List entries, intro text beside a gallery, meta values, outbound links. |
| label | Suisse Intl clauworks | 400 | 20px | 1.5 | normal, uppercase | fixed | Column headings above info lists (EXPERIENCE, PRESS…) — same size as the list, just capitals. |
| nav | Suisse Intl clauworks | 400 | 20px | 1.3 | normal | fixed | Top navigation words and two-line captions under gallery tiles (title / discipline). |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| project case-study pages | project-title | Suisse Intl clauworks | 400 | 187.2px | 158.4px | normal | size 13vw, line height 11vw | H1 of a project page, white on night navy, single line. |
| project case-study pages | lead-tight | Suisse Intl clauworks | 400 | 30px | 38px | normal | fixed | Project description paragraph on dark; emphasised phrases switch to weight 700. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Only two families: the fat display face for 1–2 word sculptures, the grotesk for all else. Never use the display face for sentences.
- Tracking is normal at every size; hierarchy is made by size jumps (20 → 30 → 72 → 144 → 288 → 504px), not by weight or tracking.
- There is no text smaller than 20px in the marketing layer; labels are distinguished by uppercase, not by shrinking.
- Large sizes are viewport-relative (35vw, 20vw, 13vw, 10vw) so the sculptures always fill the same share of the width.

## Layout

**Density:** airy — sections carry one idea each with 129.6px (9vw) vertical padding and huge type taking most of the viewport.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 30px | Gap between consecutive lead paragraphs (margin-bottom). | fixed |
| 64.8px | Side padding of every section and gap between a project title and its hero image. | 4.5vw |
| 57.6px | Inner padding between columns of text blocks. | 4vw |
| 86.4px | Top padding above a chapter display word. | 6vw |
| 129.6px | Vertical padding of every colour band and the bottom padding of chapters. | 9vw |
| 172.8px | Right padding that narrows the bio column. | 12vw |
| 201.6px | Side padding squeezing the gallery intro paragraph into a narrow block. | 14vw |
| 259.2px | Top padding above a project title. | 18vw |

### Containers and grids

- **container**: max width 1310px · side padding 64.8px. Full-width bands with 4.5vw side padding; content spans 1310px at 1440px. Nav sits on the same 64.8px edges.
- **bio column**: max width 648px. Reading paragraphs start at the horizontal centre-left (about 43% from the left) and run to 172.8px from the right edge, leaving the left half empty except for the sticker.
- **info columns**: 4 columns · gap 0px. Four equal 328px columns, each an uppercase label over a 20px list.
- **staggered gallery**: 2 columns · gap 65px. Two 655px columns of tiles offset vertically; the right column starts with an intro paragraph and tiles alternate left/right alignment so the grid feels hand-placed.
- **image pairs and trios**: 3 columns · gap 71px. Inside bands: one 1310px wide image, two 623px images side by side, or three 394px squares/portraits with 71px gaps.

## Corner radius

| Element | Radius |
| --- | --- |
| sticker | 50% |
| ticker pill | 9999px (pill) |
| images and bands | 0px |

## Surfaces and depth

### Surfaces

#### Lavender field · level 0

**Use:** Opening chapter of the main page through bio and info columns.

**CSS:** `background: #8e93ff`

**Observed:** Runs uninterrupted for over three viewports; the giant wordmark and sliding lines sit directly on it.

**Transfer:** Choose one strong flat pastel for the opening field of a new page and keep it for the whole first chapter.

#### Paper band · level 0

**Use:** White chapters: gallery, image pairs.

**CSS:** `background: #ffffff; padding: 129.6px 64.8px`

#### Dark chapter · level 0

**Use:** Gallery and closing contact on dark.

**CSS:** `background: #1a1a1a; padding: 86.4px 0 129.6px 0`

**Observed:** Same layout as the white version with all text flipped to white.

#### Night band · level 0

**Only for:** project case-study pages

**Use:** Project opening, meta block and some wide-image bands.

**CSS:** `background: #0b0f1a; padding: 129.6px 64.8px`

#### Coal image band · level 0

**Only for:** project case-study pages

**Use:** Single 1310×750 hero image per band.

**CSS:** `background: #0d0d0d; padding: 129.6px 64.8px`

#### Cobalt band · level 0

**Only for:** project case-study pages

**Use:** Three-up image rows as a bright break.

**CSS:** `background: #5277f6; padding: 129.6px 64.8px`

#### Black bleed strip · level 0

**Only for:** project case-study pages

**Use:** Full-bleed 1440px images with no padding.

**CSS:** `background: #000000; padding: 0px`

## Components

### Corner navigation

**Use:** Site navigation, fixed at the top.

**CSS:** `color: #1a1a1a; padding: 30px 64.8px; background: transparent`

**Text style:** `nav` — Suisse Intl clauworks 400 · 20px/1.3

**Observed:** Bare words: Home/About/Contact clustered left at about 145px intervals, one word (the playground/work link) alone at the right edge. Colour flips to white on dark fields. No logo, no button.

**States:** Declared: hover and active keep the colour with no underline.

### Inline underline link

**Use:** Every action inside prose: email, portfolio request, socials.

**CSS:** `color: #1a1a1a; text-decoration: underline; text-underline-offset: 4px`

**Text style:** `lead` — Suisse Intl clauworks 400 · 30px/40px

**Observed:** Sits inside 30px paragraphs; on dark fields it is white. Outbound links in 20px lists add a ↗ arrow after the label.

**States:** Declared: hover and active keep the colour, underline with 4px offset; one gallery link rotates 3.5deg on hover.

### Fixed smiley sticker

**Use:** Persistent call to request a portfolio, floating bottom-left on every screen.

**CSS:** `background: #5cd987; border-radius: 50%; width: 150px; height: 150px; position: fixed; display: flex; align-items: center; justify-content: center`

**Observed:** Circular text in small black uppercase grotesk runs around the rim (with a middle dot separator); a 60px black line-drawn smiley with x-eyes sits in the centre; the ring rotates. It overlaps imagery and text without a backing.

**States:** Declared: hover background #8e93ff; transition background-color 0.2s, opacity 0.5s linear.

### Sliding discipline lines

**Use:** Statement of disciplines between opening and bio.

**CSS:** `font-size: 144px; line-height: 165.6px; color: #1a1a1a; overflow: hidden`

**Text style:** `sliding-line` — Suisse Intl clauworks 400 · 144px/1.15

**Observed:** Two h2 lines, the first shifted right and the second left so both are cropped by the viewport; a 1310px × 4px ink rule sits between them.

**Transfer:** Write two 'Discipline — Discipline' lines for the new product and offset them in opposite directions.

### Info columns

**Use:** Résumé-style facts: experience, clients, press, expertise.

**CSS:** `color: #1a1a1a; padding: 0 64.8px`

**Text style:** `body` — Suisse Intl clauworks 400 · 20px/1.5

**Observed:** Four columns; uppercase label then about 30px gap then a plain list; press entries are underlined links with ↗.

### Gallery tile

**Use:** Work and experiment entries in the staggered gallery.

**CSS:** `width: 510px; border-radius: 0px`

**Text style:** `nav` — Suisse Intl clauworks 400 · 20px/1.3

**Observed:** Square or portrait image (510×510, 510×637, some 655px wide) with no frame, followed by a two-line caption: title, then discipline. Tiles alternate left/right within their column with about 156px vertical gaps.

### Contact ticker footer

**Use:** Closing screen and final call.

**CSS:** `background: #1a1a1a; color: #ffffff`

**Text style:** `chapter-display` — Beastly clauworks 400 · 288px/1.05

**Observed:** A dark full viewport: giant white fat-display call stacked over two lines top-left; bottom-right a short list of ↗ social links and a 30px copyright line; along the bottom edge a signal-green marquee strip with a 38px grotesk sentence repeating, a smiley glyph and a pill-outlined 'Get in touch'.

**Transfer:** Replace the call with the new product's two-word action; keep the ticker sentence as an invitation.

### Project meta block

**Only for:** project case-study pages

**Use:** Facts and description below a project's hero.

**CSS:** `color: #ffffff; background: #0b0f1a`

**Text style:** `lead-tight` — Suisse Intl clauworks 400 · 30px/38px

**Observed:** Left: two columns of label/value pairs (Category, Role, Client, Credits, Year) in 20px; right: a 30px/38px description with 700-weight key phrases, then a 20px line of ↗ links.

### Next project link

**Only for:** project case-study pages

**Use:** Hand-off to the next case study.

**CSS:** `color: #1a1a1a; text-align: right; text-decoration: none`

**Text style:** `next-link` — Suisse Intl clauworks 400 · 72px/1.15

**Observed:** Alone on white, right-aligned, 129.6px padding above and below.

## Imagery and graphics

### Hero art panel

**Use:** Directly under the opening wordmark, cropped by the fold.

**Observed:** A large saturated 3D render (glossy spheres, crystals on coral red) spanning the container width with square corners, sitting straight on the lavender field.

**Transfer:** Use one bold, colour-saturated hero image (render, illustration or product still) at full container width, contrasting with the field colour.

**Build:** Without art: a 1310px-wide block in a contrasting saturated colour (e.g. coral) with two or three large flat CSS circles in darker tones; no gradients over the field.

### Gallery artwork

**Use:** Staggered gallery tiles.

**Observed:** Vivid illustration, 3D typography, record sleeves and odd video stills, each on its own flat backdrop (black, orange, mint, pink); no frames, shadows or rounding.

**Transfer:** Show the product's best visuals as unframed square/portrait tiles, each on its own strong solid colour.

### Object mockups on bands

**Only for:** project case-study pages

**Use:** Wide project images inside coloured bands.

**Observed:** Record sleeve with a coloured vinyl sliding out, photographed flat on near-black; pairs on a mid-grey studio backdrop with soft cast shadow; exhibition photography as full-bleed strips.

**Transfer:** Stage the product as a physical object or device on a flat dark or grey backdrop, centred, one per band.

### Icons

**Observed:** Almost none: ↗ arrows set as text after outbound links, and a 60px black outline smiley inside the sticker and in the ticker.

**Transfer:** Use text arrows for links; keep a single friendly line-drawn mascot glyph as the only pictogram.

## Section recipes

How recurring sections are built.

### First screen: Wordmark on a colour field

**Observed:** Full lavender #8e93ff field. Back to front: the flat field; the giant fat-display wordmark 'Clau.' at 504px filling the width edge to edge about 170–500px from the top; directly below it the hero art panel starts at about 525px and is cut by the fold; corner navigation (three words left, one right) at 30px from the top; the green sticker fixed bottom-left overlapping the art. No support line or button in the first 900px — the brand word and the colour are the message. Below follow the sliding discipline lines and the bio column.

**Transfer:** Open with the product's name or one-word promise in the fat display face at about 35vw on a single flat pastel field, with one saturated hero visual peeking from under it, and the sticker in the corner carrying the call. Project pages open instead on night navy with a 13vw white grotesk title and a wide object image.

**Avoid:** Do not add a subheading, buttons, gradients or a centred hero; do not shrink the wordmark to fit a sentence or put it in a card.

**Text style:** `wordmark` — Beastly clauworks 400 · 504px/1

### Bio column

**Observed:** After the sliding lines, three to five 30px/40px paragraphs in a 648px column to the right of centre, 30px apart, with inline underlined links; the left half stays empty.

**Transfer:** Use for the product's story in first person, one idea per paragraph.

### Chapter word + staggered gallery

**Observed:** A two-line chapter word at 288px (white chapter or dark #1a1a1a variant), then the two-column staggered gallery with a narrow 20px intro paragraph at the top of the right column.

**Transfer:** Name each chapter with one fat word, then let images do the talking.

### Colour-band image sequence

**Observed:** Alternating full-width bands (white pairs, coal wide images, cobalt trios, black bleed strips), each 129.6px top and bottom padding, one image idea per band.

**Transfer:** Alternate band colours to pace a long visual story; never put two same-colour bands with the same layout in a row.

### Dark contact close

**Observed:** See Contact ticker footer: dark field, giant white two-line call, social links bottom-right, green marquee at the bottom edge.

**Transfer:** Every page ends here; the call names the single action.

## Page flow

**Storyline:** brand word on a colour field → disciplines statement → personal story → credentials → work gallery → contact close

### Personal portfolio front page

1. **Promise** — Giant wordmark on lavender with a hero art panel.
2. **Capabilities** — Sliding discipline lines with the rule.
3. **Story** — Bio column in 30px.
4. **Social proof** — Fat 'Get in touch' word and four info columns (experience, clients, press, expertise).
5. **Work proof** — Chapter word and staggered gallery on white.
6. **Closing call** — Dark contact ticker footer.

**Transfer:** For a product: name → what it does in two sliding lines → why in first person → who uses it → what it makes → contact.

### Project case study

1. **Promise** — Night-navy opening with 13vw title and wide object image.
2. **Context** — Project meta block.
3. **Product demonstration** — Colour-band image sequence.
4. **Next step** — Next project link.
5. **Cross-sell** — Dark gallery, wordmark repeat, bio, sliding lines, info columns.
6. **Closing call** — Dark contact ticker footer.

**Transfer:** Use for feature or case pages: title, facts, then image bands, then a link onward.

## Writing

Warm, casual first person with a wink; confident without selling, humour slipped into practical lines.

**Do not copy:** Do not reuse the designer's name, the 'Clau.' wordmark, client, press and employer names, the Secret 7" / War Child project facts, or the sticker and ticker wording verbatim. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** I talk to you directly; the brand refers to itself as 'I' or a nickname.
- **Rhythm:** Display words of one or two; paragraphs of 1–3 relaxed sentences; links phrased as everyday actions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Display word | Name or a single invitation | 1–2 words | “Playground”<br>“[Brand]” |
| Lead paragraph | Friendly introduction, then a light joke | 1–3 sentences | “If you would like to see my full portfolio just send me a request, or send me a good pizza recipe by email.” |
| Primary action | Lower-case verb phrase as a link | 2–4 words | “send me an email”<br>“Next project” |
| Ticker | Open invitation sentence repeated | 6–8 words | “Reach me out for work inquiries and commissions” |

**Words and phrasing to use:** Hi there!; simply; stuff; just for fun; send me

**Avoid:** solutions; leverage; Get started today; world-class

**Rules:**

- Write links as things a friend would say.
- Allow one playful aside per block.
- Keep labels plain nouns in capitals (Experience, Press).

## Do's and Don'ts

### Do

- Set the brand word in the fat display face at 35vw (504px at 1440) with line height 1 and normal tracking.
- Fill whole chapters with one flat colour: lavender #8e93ff opening, #1a1a1a or #0b0f1a dark chapters, #5277f6 bands.
- Keep all grotesk text at weight 400 and 20px or larger; use 30px/40px for reading paragraphs.
- Pad every band 129.6px (9vw) top and bottom and 64.8px (4.5vw) at the sides.
- Make actions underlined text links with 4px underline offset and ↗ for outbound.
- Keep the 150px signal-green sticker fixed bottom-left on every page.
- End every page on the dark contact screen with a green marquee ticker.
- Show images unframed with square corners on solid colour backdrops.

### Don't

- Don't add filled or rounded buttons; the only pill is the outline inside the ticker.
- Don't use the display face for sentences or anything under about 120px.
- Don't tighten tracking on big grotesk headings — it stays normal.
- Don't add shadows, borders or card containers around images or text.
- Don't use gradients or tinted overlays on the colour fields.
- Don't use green or lavender as text or small accents on components beyond the sticker and ticker.
- Don't centre the reading text; it lives in a column right of centre.

## Motion and responsive

### Motion

**Observed:**

- Transforms transition 0.4s and 0.75s cubic-bezier(0.5, 0.25, 0, 1).
- Sticker: opacity 0.5s linear, background-color 0.2s; ring text rotates (spin keyframes).
- Sliding discipline lines translate horizontally with scroll.
- Page load in/out and banner (marquee) keyframes declared.

**Transfer:**

- Move the discipline lines in opposite directions on scroll; keep the ticker scrolling continuously.

**Unknown:**

- Exact scroll mapping of the sliding lines and ticker speed.

### Responsive

**Observed:**

- Single breakpoint at 768px.

**Transfer:**

- Sizes are vw-based, so the wordmark keeps filling the width; stack the bio and gallery columns to one below 768px.

**Unknown:**

- Actual mobile layouts were not seen.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
