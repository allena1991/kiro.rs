# Wallpaper Projects — material meets monument

## Overview

An art-directed, light editorial style pairing warm ivory with charcoal and an occasional immersive field of muted color. Narrow, high-contrast serif statements sit beside broad grotesk numerals and small monospaced explanations. Architectural photography, tactile materials and deliberately uneven image scales give the pages the feeling of a studio portfolio rather than a conventional sales funnel. It suits visually led products and services that benefit from patient looking and a personal invitation.

### Essentials

- The opening is an artwork with a name, not a pitch deck: a full 900px-tall image field, a white serif wordmark spanning 1360px inside 40px side margins, a long central downward arrow and a small 40px-high change-scene pill.
- Editorial type changes register dramatically: Cardinal Fruit at 180px/1 with -0.05em tracking for monumental statements, 48px serif introductions, and 14px monospaced explanations at 1.3 line height.
- Actions are tiny rounded capsules against vast space: 40px height, 20px radius, 12px uppercase mono labels with 0.025em tracking; charcoal on ivory and white on charcoal.
- Color belongs to the work, not the interface: ivory #fbf9f3 carries the long middle of the page, charcoal #1e1e1e supplies text, rules and the closing band, and white supplies reversed text and pills. Chromatic fields stay inside the full-bleed opening or rectangular media.
- The gallery is a hanging arrangement rather than equal tiles: square-cornered images vary from 340px to 793px wide, sit at staggered heights, and carry 36px serif titles with 40px thin northeast arrows. Use staged product photographs or material studies when finished projects are unavailable.
- Typography itself supplies a proof device: an 80px uppercase broad-sans label sits above a 180px italic serif name in a spacious, centered interlude. Retain this contrast with a relevant collaborator, credential or short proof phrase.
- The ending remains an editorial scene: an 815px charcoal closing band pairs a 48px serif invitation and white pill with a 349×465px portrait image on the left, while an underlined newsletter field and compact support columns settle low on the right.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm ivory | `#fbf9f3` | `--color-canvas` | background | Continuous canvas through editorial introductions, process and galleries. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#1e1e1e` | `--color-ink` | text, background, border, action | Primary text, thin gallery rules, dark capsules and the closing canvas. |
| White | `#ffffff` | `--color-reverse` | text, surface, action, border | Reversed type, white action capsules and newsletter underline. |

## Typography

- **Cardinal Fruit** — Statements, introductions, gallery titles and italic proof names. Very narrow high-contrast serif with long elegant ascenders and expressive italic forms. If unavailable, use **Instrument Serif**. Use regular and italic; preserve the narrow proportions and generous display scale. Font stack: "Cardinal Fruit", "Instrument Serif", Georgia, serif.
- **Soehne Breit Buch** — Broad numerals, uppercase proof labels and small section labels. Extended grotesk with wide circular numerals and a matter-of-fact regular weight. If unavailable, use **Archivo Expanded**. Use regular weight; keep it visibly broader than the serif. Font stack: "Soehne Breit Buch", "Archivo Expanded", "Helvetica Neue", sans-serif.
- **Soehne Mono Buch** — Explanatory prose, capsule labels and utility information. Compact utilitarian monospace, creating a deliberate contrast with the tall serif. If unavailable, use **IBM Plex Mono**. Font stack: "Soehne Mono Buch", "IBM Plex Mono", Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Cardinal Fruit | 400 | 180px | 1 | -0.05em | Monumental single-sentence chapter statement. |
| proof-name | Cardinal Fruit | 400 italic | 180px | 1 | -0.025em | Expressive single-name or short-phrase proof line. |
| proof-label | Soehne Breit Buch | 400 | 80px | 1 | normal, uppercase | Centered proof-interlude label. |
| step-number | Soehne Breit Buch | 400 | 72px | 1 | normal | Large two-digit process markers. |
| intro | Cardinal Fruit | 400 | 48px | 1.24 | -0.02em | Primary editorial introduction, restrained to a 1000px text measure. |
| closing-copy | Cardinal Fruit | 400 | 48px | 1.2 | -0.025em | White editorial invitation on the dark closing band. |
| heading | Cardinal Fruit | 400 | 36px | 1 | -0.05em | Small heading introducing a gallery chapter. |
| media-title | Cardinal Fruit | 400 | 36px | 1 | -0.025em | Titles directly under photographs. |
| body | Soehne Mono Buch | 400 | 14px | 1.3 | -0.02em | Short explanatory blocks in narrow columns. |
| support | Soehne Mono Buch | 400 | 14px | 1.6 | -0.02em | Contact information and supporting utility copy in the closing band. |
| eyebrow | Soehne Breit Buch | 400 | 12px | 1.5 | 0.1em, uppercase | Chapter labels, process labels and invitation prompts. |
| action | Soehne Mono Buch | 400 | 12px | 1 | 0.025em, uppercase | Capsule actions and view controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial archive pages | archive-intro | Cardinal Fruit | 400 | 48px | 1 | -0.025em | Wide explanatory paragraph above a dense gallery. |
| editorial archive pages | pagination | Cardinal Fruit | 400 | 28px | 1.5 | normal | Centered underlined sequence of page numbers. |

**Notes:**

- All principal text uses regular weight; scale, width and type class do the work instead of bold emphasis.
- The monumental upright serif tightens to -0.05em; image captions and italic proof names use -0.025em. Small sans eyebrows open to 0.1em.
- The opening name is a white vector wordmark, 1360×254px at desktop, rather than an ordinary heading. For new copy use the display family and fit the lettering to the available width without distorting it.

## Layout

**Density:** Airy overall, with compact monospaced text islands and extensive open space between staggered images.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Separation below small section labels. |
| 25px | Archive card top inset, bottom padding and row separation. |
| 32px | Archive card horizontal inset and closing bottom padding. |
| 40px | Desktop page side margins and process-grid gap. |
| 50px | Gap before gallery actions and archive heading bottom space. |
| 60px | Introduction-to-image gap and process inner grid gap. |
| 80px | Closing band top inset. |
| 100px | Main chapter vertical padding and space before the closing band. |
| 200px | Deep pause below the monumental process headline. |

### Containers and grids

- **full-width editorial frame**: side padding 40px. A 1360px content span at a 1440px desktop window; full-bleed media and closing backgrounds extend beyond it.
- **statement measure**: max width 1000px. Introduction text and closing invitation; proof labels use a centered version of this measure.
- **hanging gallery**: 12 columns · gap 0px · side padding 40px. Unequal spans and deliberate empty columns: a narrow text island at left, a seven-column lead image at right, followed by alternating smaller images.
- **process matrix**: 2 columns · gap 40px · side padding 40px. Two columns of steps with wide numerals beside 300px text columns; the second row shifts inward.
- **archive grid** (only for editorial archive pages): 3 columns · gap 0px · side padding 40px. Equal 453px columns with ruled edges and approximately 388×499px portrait media.

## Corner radius

| Element | Radius |
| --- | --- |
| action capsules | 20px |
| media and editorial panels | 0px |

## Surfaces and depth

### Surfaces

#### Ivory canvas · level 0

**Use:** Long editorial body.

**CSS:** `background: #fbf9f3; color: #1e1e1e`

**Observed:** One continuous flat warm surface, without raised content panels.

**Transfer:** Let empty canvas establish separation between stories.

#### Charcoal closing band · level 0

**Use:** Final invitation and utility information.

**CSS:** `background: #1e1e1e; color: #ffffff; padding: 80px 40px 32px`

**Observed:** A full-width reversal, with a portrait image and widely separated text clusters.

**Transfer:** End with a substantial editorial scene rather than a thin legal strip.

#### Ruled archive surface

**Only for:** editorial archive pages

**Use:** The equal-column browsing grid.

**CSS:** `background: #fbf9f3; border-right: 1px solid #1e1e1e; padding: 25px 32px 0px`

**Observed:** Vertical strokes frame inner columns; an outer row wrapper supplies the bottom rule and 25px breathing room.

**Transfer:** Use rules instead of floating cards or tinted boxes.

## Components

### Corner navigation

**Use:** Persistent visual anchors at the top corners.

**CSS:** `width: 40px; height: 10px; position: relative`

**Observed:** A small two-line brand mark anchors the left corner; a two-hairline menu control anchors the right. Both reverse over the opening artwork and become dark over ivory. Desktop horizontal inset is 40px.

**Transfer:** Use a compact text mark and spare menu glyph, not a horizontal link bar.

### Dark capsule

**Use:** Primary actions on ivory.

**CSS:** `background: #1e1e1e; color: #ffffff; border-radius: 20px; height: 40px; padding: 8px 16px 7px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Soehne Mono Buch 400 · 12px/1 · tracking 0.025em · uppercase

**Observed:** A compact text-only action placed under a narrow explanation; the introduction contact variant uses 12px 24px padding.

### Light capsule

**Use:** Contact action in the closing band.

**CSS:** `background: #ffffff; color: #1e1e1e; border-radius: 20px; height: 40px; padding: 8px 16px 7px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Soehne Mono Buch 400 · 12px/1 · tracking 0.025em · uppercase

**Observed:** The small light pill sits near the end of the serif invitation rather than centered in a separate action row.

### Scene switch

**Use:** Change the immersive opening artwork.

**CSS:** `background: #ffffff; color: #1e1e1e; border: 1px solid transparent; border-radius: 20px; height: 40px; padding: 8px 16px 7px`

**Text style:** `action` — Soehne Mono Buch 400 · 12px/1 · tracking 0.025em · uppercase

**Observed:** Anchored low at the right edge of the artwork, opposite a tiny artwork identifier.

**States:** Declared: hover on ancestor changes border-color to rgba(30,30,30,var(--tw-border-opacity)); focus-visible behavior is unspecified.

**Transfer:** Switch between product views or material studies while retaining the same title layer.

### Image caption link

**Use:** Clickable title below a gallery image.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-end`

**Text style:** `media-title` — Cardinal Fruit 400 · 36px/1 · tracking -0.025em

**Observed:** A serif title occupies the left, with an unboxed northeast arrow on the right. Some project entries precede the title with a small uppercase year.

**Transfer:** Use a concise descriptive title; allow wrapping without shrinking the serif.

### Newsletter underline

**Use:** Compact signup within the closing utility cluster.

**CSS:** `display: flex; justify-content: space-between; height: 30px; border-bottom: 1px solid #ffffff`

**Observed:** A 340px-wide transparent email row puts the input on the left and a small sans Subscribe action flush right. An uppercase category label sits above it; there is no surrounding input box.

**Transfer:** Keep the form as a single quiet line alongside support information.

### Process step

**Use:** Explain a collaborative or considered purchase process.

**CSS:** `display: grid; grid-template-columns: repeat(6, minmax(0px, 1fr)); gap: 60px`

**Text style:** `body` — Soehne Mono Buch 400 · 14px/1.3 · tracking -0.02em

**Observed:** A large two-digit broad-sans marker sits beside an uppercase eyebrow and a narrow mono paragraph. The text is small enough to leave visibly open space within the step.

**Transfer:** Use meaningful numbered stages; keep the wide numeral and narrow explanation contrast.

### Archive tile

**Only for:** editorial archive pages

**Use:** Repeated image-led browsing entry.

**CSS:** `border-bottom: 1px solid #1e1e1e; padding-bottom: 25px; margin-bottom: 25px; position: relative`

**Text style:** `media-title` — Cardinal Fruit 400 · 36px/1 · tracking -0.025em

**Observed:** Inside the ruled wrapper: 25px top and 32px side insets, portrait media, a multiline serif title and a northeast arrow below or beside the last line. Row height follows the longest title.

**States:** Declared: hover background-color rgba(30,30,30,1) and color rgba(255,255,255,1); focus-visible behavior is unspecified.

### View toggle

**Only for:** editorial archive pages

**Use:** Choose list or grid browsing.

**CSS:** `background: #ffffff; border: 1px solid #1e1e1e; border-radius: 20px; height: 40px; position: relative`

**Text style:** `action` — Soehne Mono Buch 400 · 12px/1 · tracking 0.025em · uppercase

**Observed:** A centered 219px-wide shared capsule holds two controls with 20px horizontal padding. The active grid half is charcoal with white lettering; the inactive half remains white.

## Imagery and graphics

### Immersive material field

**Use:** Full-bleed opening backdrop.

**Observed:** A softly reflective, out-of-focus surface fills the entire first screen. Muted copper, rose, violet, blue-gray and pale silver melt into irregular vertical pools; the result feels metallic and photographic rather than a clean digital gradient. White lettering stays sharp above it.

**Transfer:** Photograph a close-up material, a defocused product surface or a soft reflected-light study. With no original photography, use a low-frequency textured color field, not a product mockup on a pedestal.

**Build:** For a minimum equivalent, make a 1440×900 SVG with a muted warm brown base; layer oversized translucent rose and slate-violet ellipses near the upper left and right, a pale silver band across the top, and diffuse peach patches below. Blur the color layers by 60–100px, add subtle low-opacity fractal-noise luminance texture, and place a crisp white title and a 1px vertical arrow above the texture. Match the soft reflected-light quality; exact color stops are not essential.

### Architectural editorial photography

**Use:** Large staggered gallery images and the closing portrait.

**Observed:** Real interiors and installed work show depth, natural side light, rich shadows and occasional saturated upholstery or painted surfaces. Images are flush rectangles with no frame, radius or shadow. The lead photograph can be 793×1003px while secondary pictures shrink to 340px wide.

**Transfer:** Show the product operating in an inhabited environment. For intangible products, stage a real working context and pair it with material or process details rather than filling every slot with interface mockups.

### Material and studio pair

**Use:** Supporting visual explanation after the introduction.

**Observed:** Two adjacent landscape images around 450×340px pair a lived-in studio with overlapping metallic sample sheets. Their scale is subordinate to the serif introduction, and both stay left of the full page width.

**Transfer:** Pair a making/working scene with a close-up of the output, using the same soft daylight and honest texture.

### Product still life

**Use:** Focused product or extension chapter.

**Observed:** A 500×617px portrait still life shows draped colored fabric, a pale jug and foliage against a warm gray wall. Soft directional light and substantial empty background create a tactile, restrained composition; the nearby copy is much smaller.

**Transfer:** Stage one product with a few contextual objects and a neutral wall. Keep surface texture and natural shadows visible rather than isolating it on pure white.

### Archive swatch and room mix

**Only for:** editorial archive pages

**Use:** Equal portrait browsing images.

**Observed:** Most entries show finished rooms; some use flat repeating patterns on a light backing. Both occupy the same portrait frame and retain their natural color without interface tinting.

**Transfer:** Mix complete use cases with detail or pattern studies while keeping one consistent frame ratio.

### Icons

**Observed:** Unboxed northeast arrows recur beside titles: 40×40px SVG, 1.5px strokes with butt caps. The opening uses a much longer, finer downward arrow. The menu is two short horizontal hairlines.

**Transfer:** Use sparse directional marks rather than pictorial feature icons. Match the square footprint and thin open construction.

## Section recipes

How recurring sections are built.

### First screen: Immersive name opening

**Observed:** A 900px-high full-bleed Immersive material field fills the first screen. Above it, Corner navigation sits at the top edges; a monumental white serif vector name spans nearly the full width inside 40px margins, occupying a 1360×254px band in the upper portion. A long thin downward arrow descends through the open center, a tiny uppercase artwork identifier rests at bottom left and Scene switch rests at bottom right. There is no support paragraph or conversion stack in this screen; the ivory introduction starts below the first 900px.

**Transfer:** Retain the name-as-art scale, immersive textured backing, central arrow and change-scene action for a different product. Use a short product name or identity phrase with an original soft material study when finished photography is unavailable. Archive pages instead open on ivory with View toggle centered above a small eyebrow and a full-width archive-intro paragraph.

**Avoid:** Do not turn the opening into a two-column text-and-mockup layout or add a stack of sales bullets over the atmospheric field.

**Text style:** `display` — Cardinal Fruit 400 · 180px/1 · tracking -0.05em

### Editorial introduction and paired details

**Observed:** Ivory canvas with 100px top and bottom space. An eyebrow leads into the 1000px-wide intro paragraph; Dark capsule sits near its final line. A 60px pause leads to the Material and studio pair, leaving the right side of the page open.

**Transfer:** Define the product or practice in one editorial paragraph, then explain it through a pair of complementary views.

**Text style:** `intro` — Cardinal Fruit 400 · 48px/1.24 · tracking -0.02em

### Monumental process chapter

**Observed:** A centered display statement stretches across the content frame. A 200px pause separates it from the Process step matrix: broad 72px numerals, 12px uppercase labels and 14px mono prose in two columns and two rows, with the lower row shifted inward.

**Transfer:** Translate the service journey or adoption experience into a few concrete stages while preserving the typographic size contrast.

**Text style:** `display` — Cardinal Fruit 400 · 180px/1 · tracking -0.05em

### Hanging evidence gallery

**Observed:** A 36px heading, narrow mono description and Dark capsule form a small left-side text island. A large image starts to its right. Other images hang lower, alternate sides and vary in width; Image caption link sits directly below each one. Main padding is 100px vertically and 40px horizontally.

**Transfer:** Arrange real demonstrations or outcomes as an uneven editorial gallery; use empty columns to give each image its own breathing room.

**Text style:** `heading` — Cardinal Fruit 400 · 36px/1 · tracking -0.05em

### Typographic proof interlude

**Observed:** A centered proof-label sits above an italic proof-name. The composition uses a 1000px label measure, 100px vertical padding and a 175px-high name stage, creating an approximately 455px chapter without a boxed testimonial.

**Transfer:** Use a collaborator, credential or short attributed proof phrase as a typographic event. Preserve both the broad uppercase line and the oversized italic line.

**Text style:** `proof-name` — Cardinal Fruit 400 italic · 180px/1 · tracking -0.025em

### Portrait product vignette

**Observed:** Within a centered editorial measure, Product still life sits at left and a small eyebrow, narrow mono paragraph and Dark capsule sit to the right near its upper portion. The image is 500×617px, with generous surrounding ivory.

**Transfer:** Give a related offering or focused feature one tangible scene and a brief explanation instead of another dense grid.

**Text style:** `body` — Soehne Mono Buch 400 · 14px/1.3 · tracking -0.02em

### Editorial invitation ending

**Observed:** Charcoal closing band opens with an uppercase prompt and a 1000px-wide closing-copy paragraph, with Light capsule near the paragraph end. A 349×465px interior portrait and social caption anchor the left below. Newsletter underline, support details, information links and a separate shop/legal cluster align low on the right, leaving a large dark void above them. Copyright sits at the bottom right. The same ending follows all three page types.

**Transfer:** Close with one open invitation, one atmospheric portrait and compact practical utilities. Preserve the low-right utility alignment and the image/text imbalance.

**Text style:** `closing-copy` — Cardinal Fruit 400 · 48px/1.2 · tracking -0.025em

### Ruled archive

**Only for:** editorial archive pages

**Observed:** After the opening description, Archive tile repeats in three equal columns with no intercolumn gap. Vertical edges divide portrait images and serif titles; horizontal rules separate rows. Centered pagination closes the grid, followed by 100px of separation before the dark ending.

**Transfer:** Use this denser mode for browsing many examples, not as the default rhythm of a marketing landing page.

**Text style:** `archive-intro` — Cardinal Fruit 400 · 48px/1 · tracking -0.025em

## Page flow

**Storyline:** immersive identity or editorial orientation → explanation → visual evidence and proof interludes → focused offering → personal invitation and practical utilities

### Brand-led marketing landing page

1. **Identity** — Full-screen artwork and monumental name.
2. **Promise** — Serif introduction with contact action and paired process/material photographs.
3. **Objection handling** — Monumental reassurance and numbered stages.
4. **Visual proof** — Large staggered case gallery and typographic collaborator interlude.
5. **Offering breadth** — A second hanging gallery and oversized publication-name proof.
6. **Focused offering** — Portrait still life beside concise copy and shop action.
7. **Closing call** — Dark invitation, atmospheric portrait, signup and support clusters.

**Transfer:** Use the immersive identity as the default opening; distribute visual proof and typographic pauses according to the new story rather than repeating a fixed section count.

### Case-study browsing archive

1. **Orientation** — Centered view switch, uppercase category and broad serif introduction.
2. **Evidence library** — Three-column ruled portrait grid with long descriptive titles and northeast arrows.
3. **Continuation** — Centered numbered pagination.
4. **Closing call** — Shared charcoal invitation and utility scene.

**Transfer:** Use for many completed outcomes; let image and title carry each entry rather than adding summaries to every card.

### Designed-range browsing archive

1. **Orientation** — View switch and longer serif range description.
2. **Offering library** — Ruled portrait grid mixing room scenes and flat patterns.
3. **Continuation** — Centered pagination.
4. **Closing call** — Shared charcoal invitation and utility scene.

**Transfer:** Use for a product family or collection library, keeping photography and detail studies within the same frame system.

## Writing

Confident but conversational studio language. The voice invites collaboration and explains practical choices without turning them into aggressive performance claims.

**Do not copy:** Do not reuse the brand name, wordmarks, artwork titles, collaborator and client names, publication names, project claims, contact details or copyright details. Source quotations are voice examples only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Speak about working together rather than directing a buyer through a funnel.
- **Rhythm:** Short labels and relaxed invitations alternate with longer editorial descriptions. Process prose can include compact fragments; gallery titles are descriptive names, not miniature advertisements.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Section statement | Simple reassuring sentence with an active verb. | 4–7 words | “Creating with us is easy.” |
| Eyebrow | Short thematic label in plain language. | 2–5 words | “Transforming Spaces”<br>“Have a project in mind?” |
| Supporting explanation | Explain the working relationship with short concrete clauses. | 2–4 short sentences | “We work hand in hand with artists and clients. Experimental and collaborative. Commercial and residential.” |
| Action | Friendly invitation or direct browsing verb. | 2–4 words | “Let's Chat”<br>“Explore All”<br>“Visit our shop” |
| Range description | Explain choice and customization through concrete dimensions. | 2–4 sentences | “Each wallpaper can be customized in scale, color, fabrication, and finish.” |

**Words and phrasing to use:** together; custom-fit; consideration; collaborate; subtle to statement; reach out; design needs

**Avoid:** revolutionary; 10x; dominate; unlock your potential; hurry; best-in-class

**Rules:**

- Make the large serif line editorial, not a keyword pile.
- Keep labels practical and invitations personable.
- Describe what changes for the customer using tangible choices or stages.
- Let descriptive names accompany images without adding promotional badges.

## Do's and Don'ts

### Do

- Keep the main canvas warm ivory and reserve charcoal for type, rules, capsules and the substantial ending.
- Maintain 40px desktop side margins while letting the opening and closing backgrounds bleed edge to edge.
- Pair 180px serif statements with 14px mono explanations rather than scaling all type together.
- Keep action capsules 40px high with 20px corners and uppercase 12px mono labels.
- Use square photographic edges and 36px serif captions with thin 40px directional arrows.
- Create broad pauses with 100px section padding and deliberate empty gallery columns.
- Keep the closing invitation at 48px and its utility text much smaller.
- Use the 80px uppercase/180px italic contrast for a typographic proof moment.

### Don't

- Do not make all photography the same size on a marketing landing page; equal 453px columns belong to archives.
- Do not use colored interface panels to echo hues inside photographs; the interface remains neutral.
- Do not round photographs to match the 20px button radius.
- Do not introduce card shadows or elevated dashboard panels into the flat editorial canvas.
- Do not replace the narrow serif with a heavy geometric sans headline.
- Do not enlarge compact 14px mono explanations into conventional wide 20px body paragraphs.
- Do not turn gallery titles into small uppercase metadata; they remain 36px serif.
- Do not center the closing utilities into a conventional symmetrical footer grid.

## Motion and responsive

### Motion

**Observed:**

- Archive tiles declare background, border, color, fill and stroke transitions over 0.5s with cubic-bezier(0.23, 1, 0.32, 1). Hover reverses tile background and text.
- The scene-switch border transition declares 0.5s with cubic-bezier(0.77, 0, 0.175, 1).
- The proof-name area is built as a looping text stage.

**Transfer:**

- Retain the slow color reversal for archive entries and the subtle border response for the scene switch.
- Keep a stable scene and text frame while artwork or proof names change.

**Unknown:**

- Proof-name change timing, scene change behavior and entrance choreography are not established.
- Keyboard focus and pressed-state treatments are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 800px, 1000px, 1200px and 2000px.
- Below 800px, declared classes reduce page side insets from 40px to 20px, the monumental process heading from 180px to 88px, archive introduction type from 48px to 24px, and the archive grid from three columns to two.
- The 2000px styles increase several headline sizes and measures rather than leaving the desktop composition fixed.

**Transfer:**

- On narrow screens, preserve the oversized-name identity and the photo/title relationship; reflow hanging images into a readable sequence.
- Keep compact capsule labels and the contrast between small explanations and expressive serif statements.

**Unknown:**

- The complete mobile navigation, process-step interaction and narrow-screen ending have not been established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
