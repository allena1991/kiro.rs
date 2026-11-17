# Kosinov — miniature mark, expansive index

## Overview

A stark white editorial portfolio with tiny uppercase wayfinding and a compact, playful black-and-white mark suspended in open space. Regular neo-grotesk typography keeps the surrounding design almost anonymous while colorful interface imagery supplies the personality. It suits design-led tools, studios, and products with substantial visual proof: sparse at the opening and closing, dense through the image index.

### Essentials

- The opening whispers rather than shouts: a centered 202×151px artwork box in a 429px white stage, framed by a 51px fixed navigation rail with 13px uppercase text.
- A small comic-style word emblem interrupts an otherwise strictly typographic system: white letter faces, black outlines and offset dark depth, with the visible lettering smaller than its image box. Recreate this compact graphic device with the new product's own short name.
- Actions look like index entries, not buttons: black 13px regular text without a filled shape, with a 1px underline on hover and 0.7 opacity while active.
- Color belongs to the work rather than the chrome: the page, header and directory stay white with black text; colorful imagery occupies three nearly edge-to-edge 467×350px tiles per row, separated by about 9.7px white gutters.
- Proof is staged as a contact sheet: square-cornered 4:3 image tiles containing front-facing black-framed phones or tablets on pale gray grounds, without external titles or descriptions.
- The ending becomes an oversized personal note, not a promotional banner: 29.8px regular text at 1.4 line height occupies the right three quarters, balanced by a small monochrome portrait, followed by uppercase resource columns and a three-position bottom rail.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link, action | All marketing typography and text actions; also the graphic emblem's outline. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Continuous page ground, fixed header, gutters and closing directory. Colorful interface art stays within media rather than becoming page chrome. |

## Typography

- **Neue Haas Grotesk** — All navigation, labels, lists and the large closing statement. Neutral neo-grotesk with compact uppercase labels and unembellished regular-weight prose. If unavailable, use **Roboto**. Use 400 throughout and retain normal tracking; tune line breaks rather than adding weight. Font stack: "Neue Haas Grotesk", "Roboto", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Neue Haas Grotesk | 400 | 29.8px | 1.4 | normal | Large closing statement in sentence case; the largest live text role. |
| index-label | Neue Haas Grotesk | 400 | 13px | 1.2 | normal, uppercase | Navigation, centered two-line principle, section indexing, directory headings and bottom rail. This is also the opening's verbal headline role. |
| directory-list | Neue Haas Grotesk | 400 | 13px | 1.5 | normal, uppercase | Stacked capabilities, resources and contact links. |

**Notes:**

- The hierarchy uses size and placement, not boldness: the statement is 2.3 times the label size, and every text role remains weight 400.
- Uppercase is for short operational language; the long closing statement keeps normal sentence case.
- The opening emblem is artwork, not a fourth live-text display style. Keep it visibly small rather than using it to justify an oversized hero heading.

## Layout

**Density:** Airy at the opening and ending, tightly packed through the media index; near-10px edge spacing makes the white intervals inside the composition feel much larger.

### Spacing

| Value | Use |
| --- | --- |
| 9.7px | Default page-content padding, including the header and footer inset. |
| 9.7px | Gallery gutters and the gap between its indexing rail and media. |
| 64.8px | Extra space after the image index before the closing statement. |
| 103.7px | Opening stage vertical padding around the padded artwork region. |
| 259.2px | Deep lower breathing room beneath the closing directory. |

### Containers and grids

- **edge-to-edge content**: side padding 9.7px. Use the full available width rather than a centered narrow content container; at 1440px, content spans about 1421px.
- **media index**: 3 columns · gap 9.7px. Equal 4:3 tiles, about 467×350px at desktop. Both row and column gaps read as narrow white seams.
- **closing statement split**: 4 columns · gap 13px. Reserve roughly one quarter for a small portrait; the prose spans the remaining three quarters. The picture occupies only a fraction of its column.
- **directory alignment**: 4 columns · gap 13px. Resources at the left edge, proof names aligned beneath the statement start, capabilities near the midpoint and contact pushed to the right edge; retain open space between the last two groups.

## Corner radius

| Element | Radius |
| --- | --- |
| media tiles | 0px |

## Surfaces and depth

### Surfaces

#### Continuous white sheet · level 0

**Use:** Page, header and closing region.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No visible borders, rounded containers or raised cards divide the page. The fixed header is opaque white and sits above the scrolling images.

**Transfer:** Separate material with white space, typographic alignment and image edges rather than changing the page background.

#### Opaque navigation overlay · level 1

**Use:** Persistent top layer over the moving image index.

**CSS:** `background: #ffffff; position: fixed; top: 0px; z-index: 399`

**Observed:** An uninterrupted opaque strip masks imagery beneath the navigation; it has no visible edge, blur or shadow.

**Transfer:** Keep the navigation ground opaque rather than making the media show through.

## Components

### Fixed navigation rail

**Use:** Persistent about and contact access with a compact principle at the center.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 51px; padding: 9.7px; box-sizing: border-box; background: #ffffff; color: #000000; z-index: 399`

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

**Observed:** Left and right text actions align to the outer edges. A narrow two-line motto is centered on the viewport independently of their widths. No logo, menu icon, border or button fill appears in this rail.

**Transfer:** Use two short destinations and a two-line product principle; keep the central phrase secondary to the artwork.

### Plain text action

**Use:** Navigation and return actions in place of conventional buttons.

**CSS:** `color: #000000; text-decoration: none; transition: color 0.2s`

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

**Observed:** The action is simply a short uppercase label; no surrounding container distinguishes it from nearby editorial labels.

**States:** Declared: hover underline 1px, text-underline-offset 0.15em, color #000000; focus-visible unspecified; active opacity 0.7.

**Transfer:** Use an explicit short destination or verb. Give the action prominence through position, not a colored pill.

### Centered principle

**Use:** Compact verbal anchor in the header and above the gallery.

**CSS:** `color: #000000; text-align: center`

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

**Observed:** A short uppercase sentence wraps into two balanced lines, about 220–229px wide at desktop. It reads as an editorial maxim rather than a headline paired with body copy.

**States:** Declared: hover underline 1px, text-underline-offset 0.15em, color #000000; focus-visible unspecified; active opacity 0.7.

**Transfer:** Write one specific principle that can hold two lines without a separate supporting paragraph.

### Gallery index rail

**Use:** Introduce the image collection without a large section heading.

**CSS:** `display: flex; position: relative; justify-content: flex-start`

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

**Observed:** Three positions distribute a left section action, the Centered principle and a right-aligned date range. The left label rests on the rail's lower line while the middle phrase takes two lines. Images begin roughly 9.7px below.

**Transfer:** Pair a functional collection label with a relevant scope or time range. Keep metadata separate from individual image tiles.

### Media tile

**Use:** Repeatable visual proof unit.

**CSS:** `display: flex; position: relative; flex-direction: column; max-width: 100%; margin-right: 9.7px; margin-bottom: 9.7px`

**Observed:** A linked image fills a square-cornered 4:3 rectangle. Front-facing devices are arranged one large or three small per tile. There is no external card heading, badge or description.

**Transfer:** Use full-frame visual proof with a consistent backing and aspect ratio; an accurate product screen on a flat pale ground is a sufficient replacement for elaborate device art.

### Directory group

**Use:** Compact resource, proof, capability and contact lists beneath the statement.

**CSS:** `color: #000000`

**Text style:** `directory-list` — Neue Haas Grotesk 400 · 13px/1.5 · uppercase

**Observed:** An index-label heading sits above a stacked uppercase list, with about 47px between heading top and first item top. Groups are left-aligned except the rightmost contact group, which is right-aligned. The longest list has seven short lines.

**States:** Declared: hover on links underline 1px, text-underline-offset 0.15em, color #000000; focus-visible unspecified; active opacity 0.7.

**Transfer:** Choose compact groups relevant to the new offering and expose a direct contact route; do not turn them into feature cards.

### Bottom colophon rail

**Use:** A final editorial sign-off and return path.

**CSS:** `position: absolute; bottom: 0px; width: 100%; padding: 9.7px; box-sizing: border-box`

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

**Observed:** A copyright line sits left, a brief expressive phrase is centered, and a return link sits right. It belongs to the document ending rather than staying fixed to the viewport. Substantial white space separates it from the directory.

**Transfer:** Keep the three-position alignment and give the center a brief human sign-off instead of adding another promotional headline.

## Imagery and graphics

### Miniature comic emblem

**Use:** Required playful graphic counterpoint in the otherwise restrained opening.

**Observed:** Two compact lines of hand-shaped white lettering have irregular black outlines and dark offset depth. The visible mark is centered inside a 202×151px image box and occupies only about two thirds of its width; surrounding white space dominates.

**Transfer:** Create an original short product-name emblem with the same outlined, slightly unruly energy. A carefully outlined two-line SVG word graphic is the minimum acceptable version; keep it small and monochrome.

**Build:** Use SVG text converted to paths or hand-adjusted heavy sans letter paths in two tight rows. Apply white fills with thin black outlines, then duplicate the group behind, offset a few pixels down and right, with black fill. Slightly rotate individual letters rather than the whole block; fit the visible paths into the central two thirds of a 202×151px white artboard.

### Device contact sheet

**Use:** Dominant proof imagery through the middle of the page.

**Observed:** Pale gray 4:3 fields hold crisp black-framed phones and landscape tablets viewed straight on, without hands, room photography or dramatic perspective. Some tiles carry three matching phones, others one enlarged device. Cream, pink, yellow, orange, blue and dark interface palettes vary within screens while the backing remains consistent. The gallery occupies much more area than the prose.

**Transfer:** Make actual product views legible at the large-device scale, then mix them with three-view compositions for rhythm. For non-screen products, use straight-on specimens or documents on the same pale neutral field, with consistent scale and margins.

### Monochrome contextual portrait

**Use:** Small human or maker cue beside the closing statement.

**Observed:** A narrow black-and-white photograph shows a person beside tall glass doors in a modern interior. It is flush with the left inset and top-aligned with the prose, approximately 124px wide and 187px tall, leaving most of its quarter-column empty.

**Transfer:** Use an understated monochrome maker, workshop or process photograph with architectural framing. Keep it small; its role is context rather than a hero portrait.

## Section recipes

How recurring sections are built.

### First screen: Small emblem opening

**Observed:** The Continuous white sheet fills the viewport. The Fixed navigation rail sits in front at the top with left and right actions and a two-line central principle. Beneath it, a 429px-tall opening centers the Miniature comic emblem in a 202×151px image box. There is no large live headline or body paragraph: the principle uses index-label typography. The Gallery index rail begins around 438px down, and the Media tile grid begins around 479px. Within the first 900px the viewer sees the entire opening, indexing rail, first gallery row and the start of the second row; most proof and all closing prose fall below. Actions are the header destinations and the gallery label, not a hero button cluster.

**Transfer:** For a different product, retain the small original outlined emblem, short principle and early visual proof. If there is no polished product media, prepare a simple straight-on document or specimen series on pale gray fields. A detail page can use the same compact stage with a relevant object or name and a shorter collection below.

**Avoid:** Do not replace the tiny central artwork with a giant centered SaaS headline, a full-bleed scene or a pair of filled call-to-action buttons.

**Text style:** `index-label` — Neue Haas Grotesk 400 · 13px/1.2 · uppercase

### Contact-sheet proof chapter

**Observed:** The Gallery index rail introduces a three-column image field on the Continuous white sheet. Media tiles are approximately 467×350px with 9.7px seams; the collection runs for seven rows. Color lives inside this image field and titles do not interrupt the rows.

**Transfer:** Use as much verified visual proof as the product merits; preserve consistent framing and the dense uninterrupted rhythm rather than prescribing a fixed row count.

### Statement and directory close

**Observed:** After 64.8px of extra gallery-end spacing, a small Monochrome contextual portrait aligns left with a large statement in the right three quarters. The statement uses 29.8px regular text at 1.4 line height, with a second short paragraph separated by an empty line. Directory groups begin roughly 93px after the statement box, aligned to the same underlying columns. The page ends with deep white breathing room and the Bottom colophon rail, not a colored closing banner.

**Transfer:** Close with a concise positioning statement and a factual availability or operating-context line. Pair with a small contextual photograph and useful resource lists, then finish with a centered human sign-off and a return path.

**Text style:** `statement` — Neue Haas Grotesk 400 · 29.8px/1.4

## Page flow

**Storyline:** compact identity and principle → sustained visual proof → considered positioning → practical resources and contact → editorial sign-off

### A visual-proof-led landing page that establishes taste before explaining the offer

1. **Identity and promise** — Tiny outlined emblem in a wide white stage; persistent edge actions and a centered maxim.
2. **Product demonstration** — An indexing rail followed by an uninterrupted three-column contact sheet of device imagery.
3. **Positioning** — Small monochrome contextual image beside a wide sentence-case statement.
4. **Practical detail and closing call** — Uppercase resource and capability lists plus direct contact links, followed by a widely separated three-part colophon.

**Transfer:** Use this as a proof-first narrative for another product: lead with a memorable small graphic, let examples carry the middle, then supply a clear explanation and direct next step. The devices can move or repeat without turning the reference sequence into a fixed template.

## Writing

Measured, declarative and design-literate, with a small expressive flourish reserved for the graphic mark and final sign-off. Confidence comes from specificity and displayed work rather than superlatives.

**Do not copy:** Do not reuse the designer's name, logo artwork, client names, geographic biography, employment history, dates or claims as facts for another product. Write original principles and a new closing sign-off rather than copying the signature slogans. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The maker speaks in the first person in long-form prose; navigation and lists are impersonal destination labels. Direct second-person persuasion is absent.
- **Rhythm:** Tiny uppercase labels and two-line maxims surround a single extended sentence-case statement. Lists contain short noun phrases, while the prose connects intent, method and lasting outcome.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening principle | A restrained assertion that contrasts durable practice with a less useful alternative. | About 8–12 words over two lines. | “CLARITY, RESTRAINT, AND INTENT MATTER MORE THAN NOISE” |
| Collection principle | A compact phrase naming the basis of the work, using a short parallel list. | About 7–10 words. | “GROUNDED IN STRUCTURE, RESEARCH, & LASTING RELEVANCE” |
| Positioning statement | First-person work description followed by the principles and intended long-term result. | One extended paragraph, then one short contextual paragraph. | “I build clear, durable design languages for products and brands.” |
| Action | Literal destination rather than a persuasive promise. | One to four words. | “CONTACT”<br>“BACK TO HIGHLIGHTS” |
| Sign-off | A brief human phrase in the same understated label typography. | About 4–6 words. | “IT WAS ALL A DREAM” |

**Words and phrasing to use:** clear; durable; structure; judgment; coherence; character; systems

**Avoid:** revolutionary; game-changing; unlock your potential; 10x; limited-time offer

**Rules:**

- Let the images establish capability before making a long claim.
- Use concise category names for directory headings and concrete nouns for their entries.
- Keep capability descriptions factual; no exclamation marks or urgency devices.
- Give the large closing paragraph a coherent argument rather than a stack of slogan fragments.

## Do's and Don'ts

### Do

- Keep the two label recipes at 13px and weight 400; use the 1.5 line-height version for stacked directory items.
- Keep the header opaque white and 51px tall so scrolling imagery does not compete with its tiny text.
- Align edge text to the 9.7px page inset rather than a narrow centered container.
- Make the image field three equal 4:3 columns at desktop with approximately 9.7px seams.
- Preserve a compact outlined emblem in the opening even when the product has no existing illustrated logo.
- Set the long closing statement at 29.8px, weight 400 and 1.4 line height.
- Retain the centered sign-off and edge-aligned copyright and return link at the document ending.

### Don't

- Do not introduce a gray body-text tier; marketing text uses black rather than a muted neutral hierarchy.
- Do not apply rounded card corners to the contact sheet; device corner shapes belong inside the imagery.
- Do not add drop shadows to the page containers or directory; the sheet remains flat.
- Do not add caption boxes under each tile; the consistent image rectangle is the proof unit.
- Do not letterspace uppercase labels into a technical mono aesthetic; tracking stays normal in the grotesk.
- Do not turn the portrait into a large headshot that fills its entire column.
- Do not make the bottom colophon viewport-fixed; the top navigation is persistent, while the sign-off belongs to the page end.

## Motion and responsive

### Motion

**Observed:**

- Text actions declare color 0.2s transitions.
- Links declare a 1px hover underline at 0.15em offset and active opacity 0.7.

**Transfer:**

- Keep link feedback typographic: underline and opacity rather than changing button fills or moving cards.

**Unknown:**

- No demonstrated running entrance animation or precise easing for these components is established.

### Responsive

**Observed:**

- The desktop composition spans a 1440px viewport; no width breakpoint behavior is established.

**Transfer:**

- For narrow layouts, preserve the compact emblem and small labels while reducing the image index to fewer columns before device screens become unreadable.
- Reflow the closing statement and directory into a readable vertical sequence, preserving the distinction between 1.2 label and 1.5 list line heights. Treat this as adaptation guidance rather than a fixed breakpoint rule.

**Unknown:**

- Mobile navigation, exact breakpoints and fluid typography formulas are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
