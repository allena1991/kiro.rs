# NCDA — monumental gallery rhythm

## Overview

An architectural editorial style that pairs a monumental identity with almost administrative supporting text. White and charcoal canvases, regular grotesk lettering, tiny bookish serif captions and timepiece numerals create a cultured, gallery-like atmosphere. Warm, tactile photography and cinematic footage carry the emotion while the interface stays monochrome and unusually sparse. It suits design-led products, collections and services whose workmanship can be shown rather than loudly claimed.

### Essentials

- Identity becomes the main object: a black wordmark spans about 1335px of a 1440px opening, with roughly 340px-high visible capitals anchored near the bottom; a short 20.9px introduction sits in the upper-right instead of a conventional centered sales headline.
- Headings behave like compressed gallery signage: regular grotesk capitals at 62.4px, line height 0.8 and -0.05em tracking sit directly above unframed images; avoid bold display weights.
- The interface is monochrome, the work supplies the color: white is the default canvas, #191919 is primary text, #808080 handles secondary text and links; warm stone, brass, wood and occasional saturated hues remain inside rectangular media rather than decorative UI fills.
- Actions are bare type, not button objects: 20.9px gray text with no fill, border, radius or shadow; collection links end with spaced square-bracket counts and darken on hover.
- Proof moves across the page rather than filling a uniform grid: 879px-wide media blocks alternate left and right within a 1335px content field, with 150px between chapters and a tiny 11px plus beneath the image.
- Include both a monumental typographic identity and a generous photographic or cinematic proof scene. If no finished product photography exists, use a carefully lit real-use detail or material study, keeping the same square framing and restrained text-to-image ratio.
- The ending is a colophon, not a sales banner: a small black identity at left and three bottom-aligned gray information columns at 14.5px/1.4, with 27.8px vertical padding and substantial white breathing room before it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Identity black | `#000000` | `--color-identity` | text, accent | Wordmark artwork and utility navigation including clocks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mid gray | `#808080` | `--color-secondary` | text, link, action | Supporting copy, colophon text and plain-text actions; inactive navigation on dark surfaces. |
| Charcoal ink | `#191919` | `--color-ink` | text, background, link | Primary editorial text and dark media backing; hover destination for secondary links. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas and header; reversed text on dark archive and cinematic media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark editorial archives | Silver caption | `#bfbfbf` | `--color-archive-caption` | text | Serif identifying lines below white archive entries. |
| portfolio indexes | Pale category gray | `#d9d9d9` | `--color-inactive` | text, action | Unselected category links against white. |

## Typography

- **TWK Everett** — Editorial headings, body, actions and utility text; regular is the default, with a light cut for dark archive entries. Clean, compact grotesk with open round forms; ordinary-weight text becomes sculptural at identity scale. If unavailable, use **Inter**. Use 400 for the default and 300 for the archive; preserve tight display tracking. Font stack: "TWK Everett", "Inter", Arial, sans-serif.
- **TWK Everett Mono** — Live time numerals in the utility header. Monospaced numerals give the otherwise editorial page a precise timekeeping detail. If unavailable, use **IBM Plex Mono**. Use 400 and keep city codes in the sans family. Font stack: "TWK Everett Mono", "IBM Plex Mono", monospace.
- **Suisse Works** — Compact image credentials and collection metadata. Small, traditionally bookish serif with deliberate positive tracking, contrasting with the grotesk headings. If unavailable, use **Libre Baskerville**. Use 400; retain the small size and open tracking. Font stack: "Suisse Works", "Libre Baskerville", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | TWK Everett | 400 | 62.4px | 0.8 | -0.05em, uppercase | size calc(-23.7px + 5.98291vw) | Main category headings immediately above showcase media. |
| body | TWK Everett | 400 | 20.9px | 1.353 | -0.01em | size calc(3.7px + 1.19658vw) | Opening identification and support, counted links, inquiry text and return-to-top text. |
| utility | TWK Everett | 400 | 20.9px | 0.8 | -0.01em | fixed | Menu control, city codes and clock punctuation. |
| clock | TWK Everett Mono | 400 | 20.9px | 0.8 | -0.01em | fixed | Hours, minutes and seconds in the utility header. |
| colophon | TWK Everett | 400 | 14.5px | 1.4 | normal | size calc(3.9px + 0.737179vw) | Contact and organizational information in the footer. |
| image-symbol | TWK Everett | 400 | 11px | 1.438 | 0.04em | fixed | Tiny plus beneath showcase images. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| collection landing pages | media-title | TWK Everett | 400 | 62.4px | 1 | -0.05em, uppercase | fixed | Centered white title over a full-viewport photographic or video scene. |
| portfolio indexes and expanded menus | category-nav | TWK Everett | 400 | 31.9px | 1.2 | -0.01em, uppercase | fixed | Stacked category navigation and expanded editorial menu. |
| dark editorial archives | archive-entry | TWK Everett | 300 | 14.5px | 1.4 | normal | size calc(3.9px + 0.737179vw) | White institution and distinction lines on a dark archive. |
| portfolio indexes, object collections and editorial archives | caption | Suisse Works | 400 | 11px | 1.438 | 0.04em | size calc(2px + 0.623932vw) | Labels and values in image credentials and collection metadata. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use weight 400 throughout the default editorial hierarchy; hierarchy comes from scale, placement and tone rather than bold emphasis.
- Display tracking tightens to -0.05em, ordinary sans text uses -0.01em, and tiny captions open to 0.04em.
- The monumental opening identity is vector-like artwork, not the 62.4px heading scaled a little larger. Fit its visible letterforms to the full content width and preserve its exceptionally tall silhouette.
- Within the introductory sentence, make the organization or product name charcoal and the continuation gray without changing weight.

## Layout

**Density:** Airy at the page scale, compact within captions and utility clusters; long visual pauses separate large images from the next chapter.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 15px | Heading-row to image separation. | 1.04167vw |
| 26.3px | Top padding before the tiny plus under showcase images. | 1.82292vw |
| 27px | Vertical separation between archive entries. | 1.875vw |
| 27.8px | Footer top and bottom padding. | 1.92708vw |
| 52.5px | Outer content inset at desktop. | 3.64583vw |
| 78.8px | Space below a portfolio image-and-credentials block. | 5.46875vw |
| 112.5px | Separation between object collection image groups. | 7.8125vw |
| 150px | Gap between alternating showcase chapters. | 10.4167vw |
| 187.5px | Vertical breathing room above and below the centered exploration cue. | 13.0208vw |
| 450px | Long white pause between the last default showcase chapter and the footer. | fixed |

### Containers and grids

- **content-field**: max width 1335px · side padding 52.5px. Desktop content field at a 1440px window; fluid side insets, not a narrow centered reading column.
- **alternating-showcase**: max width 879px. Media and heading occupy roughly two thirds of the content field, alternately flush to its left or right edge.
- **intro-column**: max width 576px. Opening sentence sits in the upper-right portion of the full content field.
- **portfolio-pair** (only for portfolio indexes): 2 columns · gap 32px. Unequal 879px and 424px image columns share a 556px media height; swap which side is wide between rows.
- **collection-pair** (only for object collections): max width 1061px · 2 columns · gap 33px. Two 514px portrait images; singles are centered on the same field. Portrait heights are 728px or 771px.
- **archive-column** (only for dark editorial archives): max width 576px. Right-hand archive field with year markers beside a narrow 325px text list, counterbalanced by fixed menu columns on the left.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and actions | 0px |

## Surfaces and depth

### Surfaces

#### White editorial canvas · level 0

**Use:** Default marketing page background and unframed content.

**CSS:** `background: #ffffff; color: #191919`

**Observed:** Images, labels and links sit directly on the page without cards or separating rules.

**Transfer:** Let alignment and whitespace organize content instead of introducing panels.

#### Cinematic media stage · level 0

**Use:** Backing for full-bleed video and large media windows.

**CSS:** `background: #191919; overflow: hidden`

**Observed:** The image covers the stage edge to edge; the charcoal is backing, not a decorative band left around the footage.

**Transfer:** Use a complete still or film with a matching dark backing and no browser-like frame.

#### Dark archive canvas · level 0

**Only for:** dark editorial archives

**Use:** Text-led reverse editorial index.

**CSS:** `background: #191919; color: #ffffff`

**Observed:** Flat charcoal fills the entire page; gray navigation and silver serif sublines establish hierarchy without containers.

**Transfer:** Use this full reversal for dense institutional proof, not as the default marketing theme.

## Components

### Clock header

**Use:** Persistent utility strip establishing a live, international presence.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 62px; background-color: #ffffff; z-index: 999`

**Text style:** `utility` — TWK Everett 400 · 20.9px/0.8 · tracking -0.01em

**Observed:** Two local clocks align left, with monospaced numerals and sans city codes. A text menu control aligns at the far right. Interior-page variants add a centered small wordmark; the default opening leaves the center empty.

**Transfer:** Use two meaningful locations or operating contexts and retain the clock device rather than adding a conventional row of marketing links.

### Menu text control

**Use:** Open or close the expanded navigation.

**CSS:** `color: #000000; background: none; border: 0px; border-radius: 0px; transition: color 0.2s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `utility` — TWK Everett 400 · 20.9px/0.8 · tracking -0.01em

**Observed:** A bare word at the right edge of the header; it changes to Close in the expanded menu.

**States:** Declared: hover color #808080; focus-visible and active treatments are unknown.

### Counted collection link

**Use:** Secondary navigation beside a major showcase heading.

**CSS:** `color: #808080; background: none; border: 0px; border-radius: 0px; transition: color 0.2s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `body` — TWK Everett 400 · 20.9px/1.353 · tracking -0.01em

**Observed:** Right aligned on the heading baseline, with a mixed-case verb phrase and a spaced bracketed count. No icon box or surrounding button shape.

**States:** Declared: hover color #191919; focus-visible and active treatments are unknown.

**Transfer:** Use a real destination and real count; carry the same treatment to a primary inquiry if conversion is needed.

### Image plus marker

**Use:** Small recurring punctuation beneath showcase and collection images.

**CSS:** `color: #191919; padding-top: 26.3px`

**Text style:** `image-symbol` — TWK Everett 400 · 11px/1.438 · tracking 0.04em

**Observed:** A solitary plus aligns with the image's left edge in a shallow caption strip. It is visually tiny relative to the image.

**Transfer:** Retain the marker as gallery punctuation; do not promise an expansion interaction unless implemented.

### Colophon footer

**Use:** Understated closing contact and organizational information.

**CSS:** `background-color: #ffffff; color: #808080; padding-top: 27.8px; padding-bottom: 27.8px`

**Text style:** `colophon` — TWK Everett 400 · 14.5px/1.4

**Observed:** Small black wordmark occupies the left; three information columns across the remaining field contain identity, contact details and administrative links. All groups align at the bottom rather than at their first text line. No dividing rule.

**States:** Declared: hover email color #191919; focus-visible and active treatments are unknown.

**Transfer:** Adapt the information to the new organization and retain the visual hierarchy; email is the quiet closing action.

### Image credentials

**Only for:** portfolio indexes and object collections

**Use:** Factual annotations below imagery.

**CSS:** `display: flex; align-items: flex-start; color: #191919`

**Text style:** `caption` — Suisse Works 400 · 11px/1.438 · tracking 0.04em

**Observed:** Three compact rows pair labels with values; label columns are about 152px wide. Credentials begin about 25px below media and have no rules, badges or bold labels.

**Transfer:** Use equivalent factual fields such as model, material, context or collaborator.

### Category list

**Only for:** portfolio indexes

**Use:** Category orientation at the start of each visual chapter.

**CSS:** `color: #d9d9d9; text-transform: uppercase; transition: color 0.2s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `category-nav` — TWK Everett 400 · 31.9px/1.2 · tracking -0.01em · uppercase

**Observed:** A short vertical stack of category names, with the active entry charcoal and a diagonal down-right arrow in the left gutter. A 58.5px indent leaves room for that arrow.

**States:** Declared: hover color #191919; focus-visible and active treatments are unknown.

**Transfer:** Keep a compact set of meaningful categories rather than a pill filter toolbar.

### Expanded archive menu

**Only for:** expanded menus and dark editorial archives

**Use:** Fixed two-column navigation alongside a scrolling editorial list.

**CSS:** `position: fixed; color: #808080; padding-left: 52.5px; display: flex`

**Text style:** `category-nav` — TWK Everett 400 · 31.9px/1.2 · tracking -0.01em · uppercase

**Observed:** The first column groups work categories, the second institutional destinations. Active text reverses to white with a diagonal arrow; the menu remains visible while the right list scrolls.

**States:** Declared: hover color #ffffff; focus-visible and active treatments are unknown.

**Transfer:** Keep navigation visibly separate from the archive content and preserve the sparse column structure.

### Archive entry

**Only for:** dark editorial archives

**Use:** Dated proof or recognition list item.

**CSS:** `color: #ffffff; margin-bottom: 27px; transition: color 0.2s cubic-bezier(0.77, 0, 0.175, 1)`

**Text style:** `archive-entry` — TWK Everett 300 · 14.5px/1.4

**Observed:** Institution first, distinction on the next line prefixed with a down-right arrow, then a silver serif project or place line after 4.4px. A year sits in its own slim column beside the first entry of a group.

**States:** Declared: hover color #808080 on linked entries; focus-visible and active treatments are unknown.

**Transfer:** Use authentic dated proof in this archival hierarchy; nonlinked entries keep the same typography.

## Imagery and graphics

### Monumental wordmark artwork

**Use:** Signature identity statement in the opening composition.

**Observed:** Black geometric lettering stretches nearly the full content width in the bottom portion of a white screen. The mark has tall capitals, very little vertical margin below, and distinctive diagonal cuts; it reads as graphic architecture rather than a sentence.

**Transfer:** Set a short new product name or a compact identifying word as a full-width typographic object. A carefully spaced all-caps grotesk word is the minimum acceptable version when a custom identity is unavailable.

**Build:** Create a responsive SVG with a 1335-by-340 viewBox containing black vector letterforms. Fit the new word optically edge to edge, preserving consistent cap height and generous internal counters; anchor the SVG to the bottom of the opening content field with about 44px clearance. Keep its background transparent and use no bevel, texture, gradient or shadow.

### Architectural proof photography

**Use:** Large showcase chapters and the first full-bleed proof scene.

**Observed:** Wide interior views show curving plaster, honed stone, wood paneling, textiles, greenery and brass in warm directional daylight. Close-ups dwell on tactile sculptural surfaces. Images are sharp rectangular windows, usually larger than all accompanying text combined; muted cream and brown dominate, with dark green and richer colors supplied by the subject.

**Transfer:** Photograph the new product in a considered real setting, balancing a broad contextual view with a close detail. For software or intangible services, show real use or a crisp demonstration within the same unframed editorial media field, not a generic floating-device collage.

### Cinematic use footage

**Use:** Immersive proof scene and selected portfolio media.

**Observed:** The default full-width scene shows an inhabited, softly lit space with visible human activity. Collection footage uses hands handling angular brass objects on green marble, with a near-black upper field. No play-button decoration competes with the subject.

**Transfer:** Show one purposeful action with material or use context; a high-quality still from that action is the minimum fallback. Keep the image edge to edge and text separate except for the scoped collection title.

### Portrait object studies

**Only for:** object collections

**Use:** Centered singles and paired object imagery in a slow collection sequence.

**Observed:** Tall photographs isolate a translucent wall light on textured plaster, polished metal tables in curved rooms, angular metal pieces on dark green marble, and serving objects against richly patterned dark tile. Soft window light or low-key illumination makes stone grain and brushed metal visible. Singles are 514px wide; pairs retain equal portrait scale with a 33px gap.

**Transfer:** Make a coherent series with the new object's material, silhouette and use context. Pair a tactile close detail with an in-use view; keep all compositing inside the rectangular image rather than painting decorative textures onto the page.

### Icons

**Observed:** Symbol vocabulary is typographic: small plus marks under images, down-right arrows at active categories and archive distinctions, a down arrow before the exploration cue and an up arrow after the return-to-top label. They inherit the text color rather than occupying colored containers.

**Transfer:** Use matching simple text glyphs or optically equivalent thin arrows; keep the plus at the 11px caption scale and directional arrows at the scale of their associated text.

## Section recipes

How recurring sections are built.

### First screen: Monumental identity opening

**Observed:** A white 900px-tall first screen has the Clock header at the top, a compact introduction in a 576px upper-right column beginning about 106px from the top, then an expansive empty middle. The sentence identifies the organization in charcoal before continuing in gray, using body typography rather than a sales slogan. Monumental wordmark artwork fills nearly the whole 1335px content width in the lower portion, its visible capitals about 340px high. Layers are white canvas, small utility text, introduction and black identity artwork. Within the first 900px, all of the wordmark, introduction and Menu text control are visible; there is no filled CTA and no photography yet. The full-width moving proof scene begins below the fold.

**Transfer:** Keep the low-anchored typographic object, upper-right factual introduction and live utility strip for an ordinary landing page. Fit the new identity to the same visual footprint; a strong typeset short name can replace custom artwork. Collection pages instead open with full-viewport use footage and a centered media-title; portfolio indexes open with category navigation and unequal image pairs; editorial archives open directly into a dark fixed-menu/list arrangement.

**Avoid:** Do not turn the introduction into a centered multi-line jumbo slogan, shrink the identity to a normal header logo, or add a pill CTA row into the empty middle.

**Text style:** `body` — TWK Everett 400 · 20.9px/1.353 · tracking -0.01em

### Full-bleed proof and exploration pause

**Observed:** Cinematic media stage spans 1440px by 810px after the identity screen, with edge-to-edge footage. A white breathing section follows: the centered down-arrow exploration cue uses the body recipe in uppercase with 187.5px above and below.

**Transfer:** Use one immersive proof scene followed by a restrained orientation cue; adapt the cue to capabilities, collections or use cases.

**Text style:** `body` — TWK Everett 400 · 20.9px/1.353 · tracking -0.01em

### Alternating showcase chapter

**Observed:** An 879px-wide block alternates between the content field's left and right edges. A heading and Counted collection link share a baseline; the image starts 15px below the row. Natural image ratios vary from broad landscape to tall portrait. Image plus marker sits below; 150px separates chapters.

**Transfer:** Use chapters to introduce distinct benefits, product families or outcomes. Preserve asymmetric alignment and varied media ratios instead of equalizing everything into cards.

**Text style:** `heading` — TWK Everett 400 · 62.4px/0.8 · tracking -0.05em · uppercase

### White colophon close

**Observed:** The last image is allowed to finish before the Colophon footer. The default showcase leaves a 450px white pause. The portfolio variant adds centered body-size return-to-top text with an up arrow before the same footer; the collection variant leaves a shorter 120px pause. The footer is 137px tall with a small identity at left and bottom-aligned information columns.

**Transfer:** Close with real contact information rather than an inflated pitch. Long visual indexes can offer the quiet return-to-top action; retain the same colophon on ordinary landing pages.

**Text style:** `colophon` — TWK Everett 400 · 14.5px/1.4

### Unequal portfolio pair

**Only for:** portfolio indexes

**Observed:** Category list introduces each chapter above two media columns, one 879px wide and one about 424px wide, separated by 32px. Media shares a 556px height while the wide side alternates. Image credentials sit about 25px below each image. The first media row begins about 334px below the page top.

**Transfer:** Use a large contextual proof image beside a narrower detail, and retain compact factual annotations.

**Text style:** `caption` — Suisse Works 400 · 11px/1.438 · tracking 0.04em

### Collection information and portrait sequence

**Only for:** object collection landing pages

**Observed:** Full-viewport footage carries a centered white media-title. On white below, a body-size collection title is paired with a type label and year; a small serif metadata block sits beside a two-line inquiry sentence with gray email link. Portrait object studies then alternate centered singles and equal pairs across a 1061px field, separated by 112.5px. Small plus markers punctuate the image groups.

**Transfer:** Make the title and metadata factual, put custom-order or inquiry information near the start, and let the object sequence carry the remaining argument.

**Text style:** `media-title` — TWK Everett 400 · 62.4px/1 · tracking -0.05em · uppercase

### Dark dated editorial archive

**Only for:** dark editorial archives

**Observed:** Dark archive canvas holds fixed navigation on the left and a 576px right-hand content field beginning near the top. Years align beside narrow stacked Archive entries, whose white sans descriptions are followed by silver serif identifying lines. The ending is the last dated entry followed by about 135px of charcoal breathing room; no white colophon or separate conversion banner follows.

**Transfer:** Use for a dense chronology of recognition, releases or references while preserving the readable two-speed navigation/list composition.

**Text style:** `archive-entry` — TWK Everett 300 · 14.5px/1.4

## Page flow

**Storyline:** identity and positioning → immersive proof → visual capability or collection chapters → quiet contact colophon; archival variants move directly from orientation to dated proof.

### Introduce a design-led organization or offering through identity and selected work

1. **Identity and positioning** — Oversized lower-screen wordmark with a short upper-right identifying sentence and live clock header.
2. **Immersive demonstration** — Full-width footage gives the product or service a lived setting.
3. **Orientation** — Centered down-arrow cue in a deep white pause.
4. **Capability chapters** — Alternating wide visual blocks with uppercase headings, counted links and tiny plus markers.
5. **Closing contact** — Long white pause followed by a bottom-aligned contact colophon.

**Transfer:** Translate work categories into the new product's most visual capabilities without requiring a fixed number of chapters.

### Provide a chronological institutional proof archive

1. **Orientation** — Charcoal page with fixed two-column navigation, active arrow and reversed active item.
2. **Dated proof** — Years accompany a narrow right-side list of institutions, distinctions and serif identification lines.
3. **Archive completion** — The oldest entries end naturally in dark breathing room, while fixed navigation remains available.

**Transfer:** Use for authentic dated proof or release histories rather than turning it into a card grid or applying the dark theme to every page.

### Let readers browse work or outcomes across categories

1. **Category orientation** — Stacked category text uses a diagonal arrow and charcoal active entry.
2. **Visual proof** — Unequal paired images with alternating wide side and small serif credential tables.
3. **Related chapters** — The category list recurs as later categories begin.
4. **Return navigation** — Centered up-arrow return-to-top line after the final image pair.
5. **Closing contact** — Shared white colophon.

**Transfer:** Use categories relevant to the new product and pair a broad view with a complementary detail.

### Present a small crafted collection with inquiry-led conversion

1. **Immersive promise** — Full-viewport use footage with a centered white uppercase title.
2. **Collection facts** — Sparse title, type and year row, then tiny serif metadata beside a short email inquiry.
3. **Material demonstration** — Slow sequence of centered portrait singles and equal pairs showing details and use contexts.
4. **Closing contact** — Final portrait and tiny plus lead to a shorter white pause and shared colophon.

**Transfer:** Keep conversion understated and front-loaded, using the imagery sequence to convey care, variation and use.

## Writing

Factual, restrained and culturally assured. The language identifies what something is and lets imagery and named proof carry persuasion.

**Do not copy:** Do not reuse NCDA names, logos, project names, contact details, locations, award claims, dates, counts or third-party quotations as the new brand's assets or achievements. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal identification by organization, category or object name. Direct address appears gently in inquiry copy, with a polite invitation rather than pressure.
- **Rhythm:** One-word category headings, short factual labels and one-sentence support. Actions name a destination directly; administrative details remain compact and unembellished.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identification | Organization name followed by a plain statement of specialization. | One short sentence | “NC Design and Architecture Ltd. is an Interior Design Studio specializing in bespoke residential and hospitality projects.” |
| Chapter heading | A single concrete category noun set in capitals. | 1 word | “PUBLIC”<br>“BESPOKE” |
| Collection action | View All plus a plural object type and a spaced bracketed count. | 3–5 words plus count | “View All Projects [ 03 ]” |
| Inquiry | Conditional need followed by a polite email invitation. | Two short lines | “If you like a customized product,”<br>“please enquire at hello@ncda.biz” |
| Image facts | Plain label-value pairs rather than persuasive captions. | 1-word labels with brief values | “Description”<br>“Client”<br>“Area” |
| Return action | Literal navigation instruction followed by a directional arrow. | 4–5 words | “Back to the Top ↑” |

**Words and phrasing to use:** bespoke; projects; products; editions; description; enquire; View All

**Avoid:** revolutionary; unlock your potential; game-changing; limited-time offer; exclamation-heavy celebration

**Rules:**

- Identify the offering clearly before adding any abstract brand language.
- Use counts only when they describe real destination contents.
- Keep factual details in labels and captions, not in long benefit paragraphs.
- For proof, name the institution and distinction rather than adding self-congratulatory adjectives.
- Let a direct contact address serve as the invitation when an inquiry is the appropriate next step.

## Do's and Don'ts

### Do

- Keep regular uppercase showcase headings at 62.4px with -0.05em tracking and 0.8 line height.
- Reserve an entire opening screen for the low-anchored identity and short upper-right introduction.
- Use the 52.5px desktop inset consistently across header, showcase and colophon.
- Preserve 879px showcase widths and alternate their alignment within the 1335px content field.
- Keep text actions gray and unboxed, with a 0.2s color transition to charcoal.
- Retain the tiny 11px plus punctuation beneath showcase media.
- Use tactile, directional light and complete rectangular images rather than decorative interface effects.
- End ordinary pages with the bottom-aligned 14.5px gray colophon.

### Don't

- Do not give the default page a charcoal canvas just because the editorial archive is reversed.
- Do not promote the 31.9px category-navigation style into the main showcase-heading role.
- Do not introduce colored CTA fills; chromatic intensity belongs to photography and film.
- Do not use 8px or 16px corner radii on media, links or imaginary cards; the framing is square.
- Do not add drop shadows, glass layers or hairline panels to organize the white canvas.
- Do not turn the tiny serif credentials into bold sans marketing summaries.
- Do not replace the clock-and-menu utility strip with a dense conventional navigation bar.
- Do not spread the default introductory paragraph across the full width; it belongs in a compact upper-right column.

## Motion and responsive

### Motion

**Observed:**

- Text actions declare color 0.2s cubic-bezier(0.77, 0, 0.175, 1).
- The fixed header declares transform 300ms and background-color 0.4s using cubic-bezier(0.77, 0, 0.175, 1).
- Footer background changes declare 0.5s with the same easing; media includes moving footage.

**Transfer:**

- Carry the declared color transition into plain-text actions, keeping the underlying rectangular editorial composition stable.
- Use actual use footage for cinematic proof rather than decorative bouncing UI elements.

**Unknown:**

- The exact scroll triggers, identity transformation behavior and complete playback choreography are not established.
- Focus-visible and active appearances beyond the listed hover colors are unknown.

### Responsive

**Observed:**

- Typography and several spacing values use viewport-based formulas.
- Declared width breakpoints include 320px, 480px, 520px, 521px, 600px, 670px, 1050px, 1366px, 1600px and 1920px.

**Transfer:**

- On narrow layouts, fit the monumental identity to the available width without horizontal clipping and keep the introductory sentence distinct above it.
- Collapse unequal portfolio pairs and collection pairs into a single reading column; preserve the image, then its credentials or plus marker, before the next image.
- Retain a compact clock-and-menu utility strip rather than importing a new pill navigation language.

**Unknown:**

- Exact mobile column changes, minimum typography sizes and clock visibility are not established; the narrow-layout guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
