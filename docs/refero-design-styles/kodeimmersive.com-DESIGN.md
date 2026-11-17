# Kode Immersive — spatial type manifestos

## Overview

A theatrical, editorial style for ambitious creative and technology products. Stark white chapters and black stages are interrupted by a vivid orange field, with uppercase grotesk copy and monumental display lettering. Full-width graphic experiences carry the spectacle while small, almost equipment-like controls keep the interface sparse.

### Essentials

- The opening is a stage rather than a sales card: a full-width 1440 × 902px graphic region under a fixed 50px navigation strip; keep the first impression dominated by one graphic experience, with a typographic composition as the fallback.
- Language becomes architecture: uppercase OT Brut at 120px/0.9, weight 400, distributed word-by-word across 1396px lines with 36px minimum gaps and deliberately indented first lines.
- Supporting prose is itself display type: uppercase Aeonik Pro at 34px/0.9, weight 400, contained in a right-hand 552px column rather than a conventional small body paragraph.
- Actions have punctuation instead of button chrome: 16px/0.75 uppercase labels, with square brackets separated from the label by 4.8px; no raised or rounded button shells.
- Color arrives in whole chapters: white carries the long editorial passages, orange #ff4c00 carries a viewport-height statement, and black carries the 900px closing stage. Orange returns as a link hover, not as multicolored decoration.
- A monumental final statement leads into a full-height contact stage: 120px lettering, a 160px pause before the right-column support, 256px bottom padding, then white contact typography over black with a full-width graphic layer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff4c00` | `--color-signal` | background, accent, link | Full-bleed introductory statement field and hover color for inverse contact links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure white | `#ffffff` | `--color-paper` | background, text | Long editorial fields and inverse navigation and contact text. |
| Absolute black | `#000000` | `--color-ink` | text, background | Editorial text on white and orange; the closing stage background. |

## Typography

- **Aeonik Pro** — Supporting statements, navigation and contact information. Regular contemporary grotesk, compact uppercase setting without added tracking. If unavailable, use **Inter**. Use weight 400; preserve the unusually tight line heights. Font stack: "Aeonik Pro", "Inter", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **OT Brut** — Monumental editorial statements. A distinct display face used as word-by-word uppercase architecture, at regular weight. If unavailable, use **Space Grotesk**. Use weight 400 and tune word spacing to retain the expansive line composition. Font stack: "OT Brut", "Space Grotesk", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | OT Brut | 400 | 120px | 0.9 | normal, uppercase | fixed | Monumental manifesto passages and the final oversized statement. |
| statement | Aeonik Pro | 400 | 34px | 0.9 | normal, uppercase | size calc(20.3px + 0.95238vw) | Right-column prose used as section leads and supporting statements. |
| contact-action | Aeonik Pro | 400 | 34px | 0.75 | normal, uppercase | size calc(17.5px + 1.14286vw) | Large inverse links in the closing stage. |
| contact-detail | Aeonik Pro | 400 | 18px | 0.95 | normal, uppercase | fixed | Email and postal contact details. |
| control | Aeonik Pro | 400 | 16px | 0.75 | normal, uppercase | size calc(13.3px + 0.19048vw) | Navigation links and compact utility labels. |
| person-label | Aeonik Pro | 400 | 16px | 1 | normal, uppercase | size calc(13.3px + 0.19048vw) | Names paired with short roles in the contact stage. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Hierarchy comes from scale and layout, not a ladder of bold weights: all principal recipes use weight 400 and normal tracking.
- Use manual editorial line groupings for the display passages. Space words across each row rather than stretching individual glyphs.
- The statement recipe is prose with display behavior; its 0.9 line height is intentional, not a conventional reading-text default.

## Layout

**Density:** Airy at section scale and compressed within typography: large pauses surround tightly stacked uppercase lines.

### Spacing

| Value | Use |
| --- | --- |
| 4.8px | Bracket-to-label spacing. |
| 10px | Five-column grid gutters. |
| 18px | Contact detail stack gap and navigation vertical padding. |
| 22px | Desktop side insets. |
| 30.6px | Gap between supporting statement paragraphs. |
| 36px | Minimum gap between display words. |
| 96px | Gaps between manifesto thought groups and graphic-chapter vertical padding. |
| 128px | Main manifesto top and bottom padding. |
| 160px | Pause between the closing display passage and its supporting statement. |
| 256px | Closing editorial chapter bottom padding. |

### Containers and grids

- **editorial-container**: max width 1396px · side padding 22px. Wide desktop content area within full-bleed sections.
- **five-column-grid**: max width 1396px · 5 columns · gap 10px. Navigation, supporting prose and contact information share five equal tracks. Supporting prose occupies the last two tracks, creating a 552px right column.
- **display-lines**: max width 1396px · 1 column · gap 36px. Each display row spans the editorial width; words are distributed with space-between. First-line indents of 156px and 444px create different chapter silhouettes.

## Corner radius

| Element | Radius |
| --- | --- |
| Graphic stages and controls | 0px |

## Surfaces and depth

### Surfaces

#### Editorial field · level 0

**Use:** Long-form display chapters and the graphic interlude.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, edge-to-edge fields without card borders, rounding or shadows.

**Transfer:** Separate content with scale, pauses and chapter boundaries instead of panels.

#### Signal field · level 0

**Use:** The introductory prose statement.

**CSS:** `background: #ff4c00; color: #000000`

**Observed:** A full-width, 900px-tall field; the prose is centered vertically in the right two grid tracks.

**Transfer:** Give one concise positioning statement an uninterrupted color field.

#### Contact stage · level 0

**Use:** The final conversion and contact area.

**CSS:** `background: #000000; color: #ffffff; position: relative; overflow: hidden`

**Observed:** A 900px stage with a full-size graphic layer and a separate foreground information grid.

**Transfer:** Treat the ending as another scene, not a thin legal strip.

## Components

### Fixed navigation

**Use:** Persistent orientation above the full-width stage.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 50px; padding-left: 22px; padding-right: 22px; z-index: 10`

**Text style:** `control` — Aeonik Pro 400 · 16px/0.75 · uppercase

**Observed:** Brand link at the left, sound control toward the right, contact at the far edge. A shared five-column grid aligns these with later prose; light and dark text variants follow the background.

**Transfer:** Keep the navigation vocabulary short and preserve the wide separation of controls.

### Navigation text link

**Use:** Small brand and contact links.

**CSS:** `position: relative; color: #ffffff; transition: color 0.5s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `control` — Aeonik Pro 400 · 16px/0.75 · uppercase

**Observed:** Unboxed text, with an inverse black variant over light sections.

**States:** Declared: hover color rgb(0 0 0/1); focus-visible color rgb(0 0 0/1).

**Transfer:** Maintain background-aware contrast while keeping the text-only silhouette.

### Bracket control

**Use:** Compact utility actions.

**CSS:** `display: inline-grid; column-gap: 4.8px; color: #ffffff; transition: color 0.5s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `control` — Aeonik Pro 400 · 16px/0.75 · uppercase

**Observed:** Opening bracket, label and closing bracket are separate grid children. A black text variant serves light fields.

**Transfer:** Use this punctuation construction for compact secondary interactions rather than enclosing them in pills.

### Manifesto line

**Use:** One row of an oversized editorial statement.

**CSS:** `display: flex; position: relative; justify-content: space-between; column-gap: 36px; max-width: 1396px; padding-left: 156px`

**Text style:** `display` — OT Brut 400 · 120px/0.9 · uppercase

**Observed:** Words are individual elements. The default first row is indented; subsequent rows return to the full measure. The final statement uses a deeper first-row indent.

**Transfer:** Compose new wording into intentional rows; adapt indentation to the shape of the sentence rather than forcing the same word count.

### Statement stack

**Use:** Short positioning prose in the right-hand column.

**CSS:** `display: flex; flex-direction: column; row-gap: 30.6px`

**Text style:** `statement` — Aeonik Pro 400 · 34px/0.9 · uppercase

**Observed:** Two uppercase paragraphs occupy the final two tracks of the grid, leaving the majority of the field open.

**Transfer:** Write enough copy for a compact block, not a full article.

### Closing action link

**Use:** Primary contact invitation at the end.

**CSS:** `position: relative; color: #ffffff; transition: color 0.3s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `contact-action` — Aeonik Pro 400 · 34px/0.75 · uppercase

**Observed:** A large text-only invitation sits in the right-side tracks, paired with a separate brand link toward the left.

**States:** Declared: hover color rgb(255 76 0/1).

**Transfer:** Use an approachable two-word invitation; preserve the absence of button chrome.

### Contact email link

**Use:** Direct contact inside the ending's information stack.

**CSS:** `position: relative; color: #ffffff; transition: color 0.3s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `contact-detail` — Aeonik Pro 400 · 18px/0.95 · uppercase

**Observed:** Email appears with location and postal information in a left-aligned stack, separated by 18px gaps.

**States:** Declared: hover color rgb(255 76 0/1).

**Transfer:** Use a real direct-contact route appropriate to the new product.

## Imagery and graphics

### Full-bleed graphic experience

**Use:** The opening and closing stages, with a wide graphic interlude within the editorial story.

**Observed:** The opening reserves 1440 × 902px for a canvas; the ending reserves 1440 × 900px. An interior graphic pairs canvas and SVG in a 1396 × 448px frame. These are graphic stages rather than conventional thumbnail galleries.

**Transfer:** Use one original product-linked graphic experience. When no suitable artwork exists, make a finished typographic scene from a short product phrase, with the same large scale and uninterrupted framing; do not substitute generic stock photography.

**Build:** For a minimum typographic scene, place a single SVG in a full-width overflow-hidden wrapper. Use a black or white palette field, uppercase text paths or live display lettering, and a few separately grouped words. Align the graphic to the editorial margins; place readable controls in HTML above it. Keep the interior SVG's wide 1396:448 aspect ratio. Use original letterforms or wording; surface texture and lighting are not necessary.

## Section recipes

How recurring sections are built.

### First screen: Graphic stage opening

**Observed:** A full-width graphic region occupies the first 902px, with a fixed 50px navigation layer above it and compact utility controls near the lower edge. The first 900px are devoted to the graphic experience rather than the positioning paragraphs; those begin in the next full-height field. Keep background, main graphic and readable controls as separate layers. The opening does not establish a separate HTML hero-headline and support stack.

**Transfer:** Give a different product a single dominant graphic composition that fills the opening. If original scene artwork is unavailable, use the display recipe to create a finished product-phrase composition, while keeping actions in the compact control recipe. For a more informational landing page, the right-column positioning statement can follow immediately without an interaction gate.

**Avoid:** Do not make entry dependent on a loading screen or an Enter overlay, and do not turn an unresolved graphic region into intentional empty space.

**Text style:** `display` — OT Brut 400 · 120px/0.9 · uppercase

### Right-column signal statement

**Observed:** The Signal field spans 900px. A 552px Statement stack occupies the last two of five columns, with 297px of space above and below the 306px text block.

**Transfer:** Use a short positioning statement plus a welcoming continuation. Retain the asymmetric weight and uninterrupted color.

### Typographic manifesto

**Observed:** The Editorial field holds 120px Manifesto lines with 108px row height, 128px top and bottom padding and 96px pauses between thought groups. Words spread across each line; the first line begins with a 156px indent.

**Transfer:** Turn a product benefit or point of view into a monumental sentence composition. Let the wording determine how many thought groups it needs.

**Text style:** `display` — OT Brut 400 · 120px/0.9 · uppercase

### Wide graphic and explanation

**Observed:** An Editorial field uses 96px vertical padding. A 1396 × 448px graphic frame spans the content width; a 552px statement follows at the right edge.

**Transfer:** Show a distinctive product-linked word sculpture, schematic or graphic demonstration, then explain its consequence in one short statement.

**Text style:** `statement` — Aeonik Pro 400 · 34px/0.9 · uppercase

### Monumental closing promise

**Observed:** An Editorial field uses 112px top padding and 256px bottom padding. Seven tightly stacked display rows begin with a deeper 444px indent. A 160px pause separates the composition from its right-column support.

**Transfer:** Use a final expansive product promise as a typographic landmark. Change the row count to fit the copy while retaining the dramatic indent and pause.

**Text style:** `display` — OT Brut 400 · 120px/0.9 · uppercase

### Full-height contact ending

**Observed:** The Contact stage spans 900px. Its foreground uses 32px top, 22px side and 24px bottom padding on the five-column grid. Names and roles sit near the top; the right-side information stack includes email and address. Large Closing action links sit below the details, with a full-size graphic layer behind the grid.

**Transfer:** Close with direct routes to a person or team and a generous graphic scene, rather than a dense directory of unrelated links.

**Text style:** `contact-action` — Aeonik Pro 400 · 34px/0.75 · uppercase

## Page flow

**Storyline:** graphic invitation → concise positioning → oversized point of view → graphic demonstration → expansive closing promise → direct contact

### An experiential marketing page that communicates an ambitious creative point of view and invites a conversation

1. **Graphic invitation** — A viewport-scale canvas stage with sparse persistent controls.
2. **Positioning** — A short uppercase statement placed in the right two tracks of an orange field.
3. **Value narrative** — A word-by-word monumental manifesto across a white field.
4. **Graphic demonstration** — A wide canvas/SVG interlude with a right-aligned explanation; the middle experience is not expressed as a card grid.
5. **Closing promise** — A second oversized editorial composition followed by a short support line.
6. **Final action** — A black full-height contact stage with names, direct contact details and a large invitation link.

**Transfer:** Borrow the contrast between graphic immersion, short asymmetric prose and monumental language. Adapt the number and order of chapters to the product; retain the graphic stage, architectural type and substantial ending.

## Writing

Bold, expansive and welcoming. The voice pairs creative ambition with an invitation to participate, using declarative statements rather than technical feature inventories.

**Do not copy:** Do not reuse the brand name, logo artwork, names, addresses, contact details or its claims about creative capabilities and client relationships. Source quotations illustrate tone only.

- **Addressing the reader:** Use we for the maker and you for the reader; move between confident statements and inclusive invitations.
- **Rhythm:** Short clauses build into larger sentence compositions. Supporting prose is one or two compact paragraphs; action labels remain one or two words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Monumental statement | An expansive consequence stated in ordinary language, broken into visual thought groups. | 6–20 words per thought | “The emotional impact is off the scale.”<br>“Tell stories people love, share & remember.” |
| Supporting invitation | Invite the reader into a new possibility with an active opening. | One short sentence | “Come with us into the emerging world of immersive storytelling.” |
| Closing support | Describe a lasting customer outcome with a confident we statement. | One sentence | “We help our clients stay bold, and form strong, enduring connections with their customers.” |
| Contact action | Warm, direct invitation rather than transactional urgency. | 1–2 words | “Let's Connect”<br>“Contact” |

**Words and phrasing to use:** create; step into; possibility; bold; connections; with us

**Avoid:** best-in-class; 10x; disruptive solution; limited time; synergy

**Rules:**

- Write plain, confident clauses that remain legible when enlarged and split across rows.
- Make the supporting statement add meaning rather than explain how to navigate the graphic.
- Use uppercase styling as the typographic voice; do not compensate with excessive exclamation marks.

## Do's and Don'ts

### Do

- Keep the core type at weight 400; let 120px versus 34px create hierarchy.
- Align supporting prose to the last two tracks of a five-column, 10px-gap grid.
- Use 22px desktop side insets consistently across navigation, type and contact fields.
- Preserve 108px rows for 120px monumental lettering.
- Use 96px pauses between manifesto thought groups instead of card borders.
- Keep contact links text-only and use #ff4c00 as their hover color.
- Give the ending a full 900px stage rather than compressing it to a utility strip.

### Don't

- Do not turn the interface into pill buttons; the characteristic control is a bracketed 16px label.
- Do not use soft gray cards or shadow stacks to organize the white editorial fields.
- Do not replace regular uppercase supporting statements with bold sentence-case subheads.
- Do not apply orange to every heading or sprinkle it across individual words; reserve its large use for a coherent field.
- Do not center all supporting paragraphs; their 552px right-column placement is a defining counterweight.
- Do not simulate justification by adding letter spacing; distribute whole words with 36px minimum gaps.
- Do not fill the closing stage with a conventional many-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Navigation and bracket controls declare 0.5s color-related transitions with cubic-bezier(0, 0, 0.2, 1).
- Inverse contact links declare 0.3s color-related transitions with the same easing.
- Opacity transitions of 0.3s and a 2s repeating pulse with cubic-bezier(0.4, 0, 0.6, 1) are also declared.

**Transfer:**

- Retain the measured color transitions on the sparse text controls; keep graphic motion independent from readable navigation.
- A static, finished SVG composition is the minimum fallback for the graphic stages.

**Unknown:**

- The graphic scenes' choreography, scroll timing and pulse appearance are not specified.

### Responsive

**Observed:**

- Width breakpoints are declared at 390px, 767px, 768px and 1440px.
- Container classes switch from 10px side padding to 22px at the medium breakpoint.
- Navigation, statements and footer links use the fluid size formulas in their typography recipes.

**Transfer:**

- On narrow screens, recompose display sentences into shorter rows rather than keeping desktop word positions.
- Move the right-column statements into the available width while retaining their separation from the graphic stage. Reduce the large first-line indents before shrinking the type into unreadability.

**Unknown:**

- Narrow-screen scene framing, precise display size changes and the final mobile contact grid are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
