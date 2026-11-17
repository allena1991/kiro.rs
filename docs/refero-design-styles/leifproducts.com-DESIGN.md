# LEIF — sculptural everyday rituals

## Overview

A light, design-led editorial style that treats everyday products as collectible objects. Warm off-white and black frame sunlit still-life photography, tactile human details and expansive landscapes; color lives chiefly inside the pictures. Compact grotesk headlines, restrained sans-serif prose and small monospaced labels lend an art-direction studio sensibility to an otherwise spacious shopping experience.

### Essentials

- Objects lead and headlines stay compact: the default opening divides the desktop into two 720px halves, pairing a full-height still life with a 256×320px inset and a low-set 52px/52px headline.
- Headlines have sculptural density rather than billboard breadth: PP Right Grotesk at 500, 52px with -0.01em tracking; photographic chapter titles rise to 75px with a compressed 51px line box.
- Actions look like small printed instructions: uppercase 13px Söhne Mono, 0.05em tracking, 48px-high buttons with 6px corners; secondary editorial actions are 24px-high underlined labels.
- The interface is nearly monochrome, while objects carry the color: #fafaf9 canvas, #000000 ink and #e5e2dc hairlines dominate; the warm #d4a566 announcement occupies only a 40px strip, not a full section.
- Every landing page needs tactile image contrast: combine a large close-framed object or human-use image with a smaller isolated detail, and include an expansive atmospheric photographic pause. Without bespoke media, use an original sunlit object study and a real location photograph rather than gradients or floating UI.
- Selection feels like an editorial index: 48px dated rows or 122px image-led rows use 1px separators, uppercase mono captions and hollow/solid circular selection marks; retain this index device for benefits, variants or stories.
- The ending is a divided colophon, not a dark conversion slab: a 508px light footer places a 52px closing phrase over three link columns in the right half, with a small identity and trust mark at left.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ochre announcement | `#d4a566` | `--color-announcement` | background, accent | Narrow promotional announcement strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, border | Primary text, filled actions, active index rules and icon strokes. |
| Hover charcoal | `#333333` | `--color-hover` | action, text, border | Declared hover tone for filled buttons and outlined or underlined actions. |
| Secondary gray | `#595959` | `--color-muted` | text | Low-priority footer text and secondary labeling. |
| Stone and rules | `#e5e2dc` | `--color-stone` | border, surface | Section and index hairlines; full flat reward tiles in the membership variant. |
| Warm reverse | `#edede7` | `--color-reverse` | text, border | Type and outlined actions over photographs; filled-button labels. |
| Chalk canvas | `#fafaf9` | `--color-canvas` | background, surface | Continuous page and product information background. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog promotions | Lemon value flag | `#f3ffa9` | `--color-bundle` | surface, accent | Small value flags above catalog imagery. |
| membership pages | Reading gray | `#4a4a4a` | `--color-secondary` | text | Membership tile explanations and introductory support. |
| membership tables and catalog navigation | Faint gray | `#b2b2b2` | `--color-faint` | text | Table thresholds and subdued category labels. |
| membership comparisons | Table edge | `#d9d9d9` | `--color-table-rule` | border | Horizontal benefit-table rules. |
| catalog promotions | White flag | `#ffffff` | `--color-flag-white` | surface | Subscription flags above catalog imagery. |

## Typography

- **PP Right Grotesk** — Section headlines and the closing phrase. Compact, slightly idiosyncratic grotesk with a strong condensed vertical impression and tightly packed large letters. If unavailable, use **Barlow Semi Condensed**. Use 500 for main headlines and 200 for small editorial section titles; tune width before enlarging. Font stack: "PP Right Grotesk", "Barlow Semi Condensed", sans-serif.
- **Söhne** — Descriptions, navigation, product titles and editorial statements. Matter-of-fact neo-grotesk, mostly regular weight with occasional bold questions. If unavailable, use **Inter**. Use 400 for prose and 700 only for questions or emphasis. Font stack: "Söhne", "Inter", sans-serif.
- **Söhne Mono** — Actions, sensory labels, dates and small category headings. Small, evenly spaced monospace capitals that read like product annotations. If unavailable, use **IBM Plex Mono**. Use 400 with 0.05em tracking. Font stack: "Söhne Mono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| photo-display | PP Right Grotesk | 500 | 75px | 51px | -0.01em | Single-line title over a full-width photograph; keep generous margins around its compressed line box. |
| heading | PP Right Grotesk | 500 | 52px | 1 | -0.01em | Default opening title, feature titles and footer closing phrase. |
| editorial-section | PP Right Grotesk | 200 | 34px | 23px | normal | Light editorial section titles above index-and-image compositions. |
| statement | Söhne | 400 | 26px | 1 | -0.01em | Selected story title and larger editorial paragraphs. |
| body | Söhne | 400 | 15px | 20px | normal | Default marketing paragraphs, support lines, prices and navigation. |
| product-title | Söhne | 400 | 15px | 19px | normal | Product name below an image. |
| menu-link | Söhne | 400 | 15px | 1.35 | normal | Footer link columns. |
| action | Söhne Mono | 400 | 13px | 1.2 | 0.05em, uppercase | Primary, outline and underlined actions. |
| index-caption | Söhne Mono | 400 | 12px | 14px | 0.05em, uppercase | Dated editorial index rows and sensory descriptors. |
| eyebrow | Söhne Mono | 400 | 11px | 13px | 0.05em, uppercase | Section labels, product notes and footer group headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| membership and institutional storytelling | display | PP Right Grotesk | 500 | 75px | 67px | -0.01em | Membership opening, FAQ heading and long responsibility headline. |
| membership rewards | tile-title | Söhne | 400 | 18px | 26px | normal | Reward amount or activity title at the bottom of a tile. |
| membership FAQs | question | Söhne | 700 | 15px | 20px | 0.01em | Compact FAQ questions. |
| membership rewards | tile-copy | Söhne | 400 | 13px | 18px | normal | Small explanation beneath reward amounts. |
| catalog navigation | catalog-label | Söhne Mono | 400 | 13px | 16px | 0.05em, uppercase | Horizontal category navigation below a catalog. |
| catalog promotions | flag | Söhne Mono | 400 | 11px | 1.2 | 0.05em, uppercase | Small promotional flags. |

**Notes:**

- Main display tracking remains -0.01em at both 52px and 75px. The compact 75px/51px photo title is a distinct single-line treatment, not a general paragraph recipe.
- Mono labels share 0.05em tracking across 11px, 12px and 13px sizes. Use sentence case for prose and titles; reserve capitals for annotations and actions.
- Maintain the deliberate contrast between 52px display headings and 15px support copy. Larger 26px editorial prose is reserved for short, narrow statements rather than all body text.

## Layout

**Density:** Airy in composition but compact within information groups: broad unused areas surround tightly set paragraphs, ruled lists and product metadata.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Paired action gap and small image-list inset. |
| 12px | Product metadata top padding, compact row padding and social-image gap. |
| 16px | Product information side padding and footer half-grid gap. |
| 20px | Default page edge, image/text gutter, and common grid gap. |
| 40px | Announcement height, modest inter-chapter bands and footer bottom padding. |
| 80px | Main navigation height, editorial section lead-in and footer title-to-menu separation. |
| 120px | Long-form section bottom breathing room. |
| 160px | Social-strip vertical padding and deep editorial ending space. |

### Containers and grids

- **page-edge**: side padding 20px. Fluid edge-to-edge page; text and inset media sit inside a narrow page edge rather than a centered boxed website.
- **opening-halves**: 2 columns · gap 0px. Equal 720px halves at desktop: full-bleed left photograph and an off-white editorial right stage.
- **editorial-halves**: 2 columns · gap 20px · side padding 20px. Two 690px columns for portrait image and narrative; keep copy narrower than its column.
- **narrow-copy**: max width 394px. Narrow statements alongside large portrait media; short supporting paragraphs can narrow further to 260px.
- **index-detail**: 2 columns · gap 119px · side padding 20px. 473px index at left, image and explanation at right; broad central breathing space.
- **footer-columns**: 3 columns · gap 20px. Three link groups within the right half of the footer.
- **catalog-grid** (only for catalog pages): 3 columns · gap 0px. Three flush 480px columns with 480×600px images and separate 132px information regions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 6px |
|  | selection-indicator | 50% |
| catalog promotions | promotional-flags | 3px |

## Surfaces and depth

### Surfaces

#### Chalk field · level 0

**Use:** Default canvas and editorial text regions.

**CSS:** `background-color: #fafaf9; color: #000000`

**Observed:** The same light field continues across major chapters and the footer. Depth comes from photography rather than raised panels.

**Transfer:** Let imagery create material variation; keep interface surfaces flat.

#### Ruled band · level 0

**Use:** Separate editorial chapters, social strip and closing areas.

**CSS:** `background-color: #fafaf9; border-top: 1px solid #e5e2dc`

**Observed:** Thin warm-gray rules define sections without contrasting background blocks.

**Transfer:** Use one rule at meaningful narrative breaks.

#### Ochre strip · level 0

**Use:** Small promotional announcement.

**CSS:** `background-color: #d4a566; color: #000000; height: 40px`

**Observed:** A narrow full-width bar with centered short copy and a close icon at the far right.

**Transfer:** Keep this color concentrated in the strip, not a theme covering the whole page.

#### Stone tile · level 0

**Only for:** membership rewards

**Use:** Reward or activity proof cards.

**CSS:** `background-color: #e5e2dc; border-radius: 0px; box-shadow: none`

**Observed:** Flat 403×250px tiles sit in a two-by-two grid; no outline or elevation.

**Transfer:** Retain the broad empty center between the top icon and bottom text.

## Components

### Main navigation

**Use:** Global navigation above the editorial opening.

**CSS:** `height: 80px; padding: 0px 40px 0px 20px; display: grid; grid-template-columns: 80px 1fr; column-gap: 157px; align-items: center; color: #000000`

**Text style:** `body` — Söhne 400 · 15px/20px

**Observed:** Small identity at left, a sparse text menu farther right, and currency/search/account/bag controls at the opposite edge. The opening navigation visually shares the image and canvas beneath it; solid light treatment belongs to interior pages.

**Transfer:** Use the new identity at a similarly compact scale and keep utilities visually subordinate.

### Primary button

**Use:** Main shopping or joining action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; background-color: #000000; color: #edede7; border-radius: 6px; gap: 10px; transition: 0.3s`

**Text style:** `action` — Söhne Mono 400 · 13px/1.2 · tracking 0.05em · uppercase

**Observed:** Label-width rectangle, not a full-column action. It can sit well below the support copy rather than immediately attached to it.

**States:** Declared: hover background-color #333333, color #edede7 and text-decoration none; focus-visible unknown.

### Outline button

**Use:** Secondary or exploratory action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 23px; border: 1px solid #000000; border-radius: 6px; color: #000000; background: rgba(0,0,0,0); transition: 0.3s`

**Text style:** `action` — Söhne Mono 400 · 13px/1.2 · tracking 0.05em · uppercase

**Observed:** Same silhouette as the filled action. A reverse version uses warm-light type and border over photography.

**States:** Declared: hover color #333333, border-color #333333 and transparent background; focus-visible unknown.

### Underlined action

**Use:** Editorial continuation and specific product-family shopping.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 24px; border-bottom: 1px solid #000000; color: #000000; transition: 0.3s`

**Text style:** `action` — Söhne Mono 400 · 13px/1.2 · tracking 0.05em · uppercase

**Observed:** A short mono instruction sits directly above a black rule; no surrounding button fill.

**States:** Declared: hover color #333333, border-color #333333 and transparent background; focus-visible unknown.

### Product card

**Use:** Commerce selection in a flush image-led grid or horizontal rail.

**CSS:** `position: relative; background-color: #fafaf9; border-radius: 0px`

**Text style:** `product-title` — Söhne 400 · 15px/19px

**Observed:** A 4:5 image fills the width. Beneath it, 12px top and bottom and 16px side padding frame a title at left and price at right; the information region is 132px tall. Seasonal rail images are 472×590px; catalog images are 480×600px. Small mono notes sit low in the information region.

**States:** Declared: hover product-title text-decoration underline; focus-visible unknown.

**Transfer:** Use consistent object scales within each family. Do not add a prominent purchase button to every tile.

### Editorial index row

**Use:** Choose a story or feature detail without using tabs in boxes.

**CSS:** `display: grid; grid-template-columns: auto 1fr 16px; gap: 20px; align-items: baseline; padding: 12px 0px 11px; border-bottom: 1px solid #000000; height: 48px; box-sizing: border-box; transition: 0.3s`

**Text style:** `index-caption` — Söhne Mono 400 · 12px/14px · tracking 0.05em · uppercase

**Observed:** Active row uses a black rule and solid circular endpoint; other rows use warm-gray rules and hollow endpoints. A sensory variant is 122px tall, with a 172×106px thumbnail, 12px gaps and small mono descriptors.

**Transfer:** Keep the active marker and linked visual detail; adapt row content to variants, features or dispatches.

### Footer link

**Use:** Grouped navigation in the closing colophon.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `menu-link` — Söhne 400 · 15px/1.35

**Observed:** Plain stacked text, 4px gaps within each list, with a small uppercase mono group label above.

**States:** Declared: hover text-decoration underline; focus-visible unknown.

### Colophon footer

**Use:** The shared ending.

**CSS:** `background-color: #fafaf9; border-top: 1px solid #e5e2dc; padding: 68px 20px 40px; color: #000000`

**Text style:** `heading` — PP Right Grotesk 500 · 52px/1 · tracking -0.01em

**Observed:** A 508px desktop closing area. The left half holds a small identity, a trust mark and a low-priority note. The right half starts with a 52px closing phrase, then three navigation columns. A final fine-print baseline holds currency, legal links, credits and copyright.

**Transfer:** Use an original short brand philosophy as the closing phrase; preserve the asymmetric hierarchy.

### FAQ row

**Only for:** membership FAQs

**Use:** Dense objection handling beside a large heading.

**CSS:** `padding: 12px 0px 11px; border-bottom: 1px solid #e5e2dc`

**Text style:** `question` — Söhne 700 · 15px/20px · tracking 0.01em

**Observed:** Rows are about 44px tall in a 690px-wide list. A tiny plus follows the question instead of a large chevron at the far edge.

**Transfer:** Use concise concrete questions and preserve the narrow ruled rhythm.

### Reward tile

**Only for:** membership rewards

**Use:** Explain repeatable reward activities.

**CSS:** `background-color: #e5e2dc; height: 250px; position: relative`

**Text style:** `tile-title` — Söhne 400 · 18px/26px

**Observed:** A small black outline icon is pinned near the top-left. Amount or activity and a 13px explanation sit at the lower left with 20px internal spacing from the edges. Four tiles form a two-column grid.

**Transfer:** Make the amount legible but not monumental; preserve the large empty center.

### Value flag

**Only for:** catalog promotions

**Use:** Annotate a specific commercial benefit on an image.

**CSS:** `background-color: #f3ffa9; color: #000000; padding: 8px 20px; border-radius: 3px`

**Text style:** `flag` — Söhne Mono 400 · 11px/1.2 · tracking 0.05em · uppercase

**Observed:** Small flag positioned near the top-right of the product image. Subscription flags use white instead of lemon.

**Transfer:** Limit flags to meaningful distinctions, not every product.

### Benefit table row

**Only for:** membership comparisons

**Use:** Compare levels with minimal visual furniture.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr 1fr 1fr; padding: 12px 0px; border-bottom: 1px solid #d9d9d9`

**Text style:** `body` — Söhne 400 · 15px/20px

**Observed:** A descriptive first column and three centered level columns. Plain black dots indicate inclusion; small faint mono labels identify levels and spend thresholds.

**Transfer:** Keep comparison cells sparse and typographic rather than turning levels into separate pricing cards.

## Imagery and graphics

### Sculptural product still life

**Use:** Primary opening image and supporting object detail.

**Observed:** Warm, directional daylight makes physical forms, translucent amber liquid, metallic reflections, paper grain and wood edges tangible. Objects are stacked or balanced against pale stone backdrops, with shadows retained. The large opening image occupies half the viewport; the companion is a much smaller 4:5 rectangle with square corners.

**Transfer:** Photograph the new product as a physical design object on pale timber or stone. If the product is intangible, stage an original tool, sample, printed artifact or material associated with its use; retain directional light, contact shadows and the large/small image contrast.

### Human-use close study

**Use:** Editorial product chapters and supporting details.

**Observed:** Close framing cuts bodies at torso, shoulder or hands. Warm skin, foam and translucent packaging fill tall 4:5 or taller rectangles, with natural window light and gentle grain. Smaller scenes show a bathing detail, while larger scenes closely frame the held object.

**Transfer:** Show the new product in a believable human context without a smiling stock-photo pose. Emphasize touch, scale and material; retain natural imperfections and directional light.

### Atmospheric landscape

**Use:** Full-width visual pause or values chapter.

**Observed:** An 1440×800px coastal view carries muted blue-green water, distant trees and small people under a hazy sky. An institutional variant shows a sunlit ochre rock face and low vegetation. Pictures are edge-to-edge, square-cornered, naturalistic and spacious; text overlays are confined to a small upper-left area.

**Transfer:** Use a real landscape or environment connected to the new product's world. Select a quiet, low-detail area for light text; a simple original location photograph is the minimum replacement, not an abstract color field.

### Sensory material study

**Use:** Feature selector thumbnails and selected detail.

**Observed:** Smoke, cream, flowers, fruit, leaves and earth act as visual translations of sensory descriptions. The selected image pairs a green fruit and pale cream on a rough gray block, lit as an artful still life; thumbnails are narrow horizontal cuts.

**Transfer:** Translate product attributes into original tactile material studies: flexibility as folded fabric, warmth as sunlit timber, smoothness as glazed ceramic. Pair a macro detail with a larger object composition.

### Process and place

**Only for:** institutional and editorial storytelling

**Use:** Origin, partnerships and cultural context.

**Observed:** Macro botanical footage, monochrome bottle wireframes, gallery exteriors, warm restaurant interiors and documentary event photography alternate with narrow text. Portrait architectural images are 690×863px; 11px uppercase mono credits sit immediately below.

**Transfer:** Use real process documentation, original technical drawings and inhabited architecture. For a wireframe equivalent, render the new object's own geometry in thin black lines on a pale ground rather than copying the bottle pattern.

### Icons

**Observed:** Black outline utility symbols, generally 16×16px with 1px butt-ended strokes; small table and FAQ marks are 12×12px, larger commerce controls 24×24px. Selection endpoints are hollow circles that become filled black for the active item. Reward tiles use larger, simple outline pictograms.

**Transfer:** Choose restrained single-color line icons. Keep utility icons small and let text carry meaning; reserve filled circles for selection rather than using colorful icon containers.

## Section recipes

How recurring sections are built.

### First screen: Sculptural split opening

**Observed:** At 1440×900px, a 40px ochre announcement runs across the top and an 80px navigation overlays the scene below. A 720×860px still life fills the left half from below the announcement to the bottom edge. The right half is Chalk field: a 256×320px companion detail is anchored toward the upper-right, while the title and support sit low at the left edge of that half with a 20px inset. The 52px heading is a short single line; 15px/20px support wraps into a narrow block below it. The Primary button sits near the bottom, separated from support by 99px. Back-to-front layers are the pale canvas, left photographic stage, inset photograph, typography and controls. Both images, headline, support and action are visible in the first 900px; the commerce rail begins below the fold.

**Transfer:** Preserve the half-width object stage, upper-right detail and low-set compact promise for a new product. Create an original physical artifact study if bespoke product imagery is unavailable. Membership pages instead use a 75px title with paired actions at left and a 400×500px portrait at right; catalogs use a compact title/description with a 460×306px image before the grid; institutional stories begin with a narrow 52px statement beside a 690×863px portrait.

**Avoid:** Do not center the headline above a giant isolated object, fill the right half with text, or make the small detail the same size as the main image.

**Text style:** `heading` — PP Right Grotesk 500 · 52px/1 · tracking -0.01em

### Flush product rail

**Observed:** A lightweight 34px section title precedes Product cards with square 4:5 media. Three cards are visible at desktop and a fourth extends beyond the viewport in the seasonal rail. In the catalog variant, three equal columns repeat vertically below a 70px filter band.

**Transfer:** Use this for comparable products or tangible options; maintain consistent backgrounds and title/price alignment.

**Text style:** `product-title` — Söhne 400 · 15px/19px

### Small story beside large detail

**Observed:** One half carries a tall, closely framed human-use image; the other holds a 332×415px inset image, narrow 15px support and Underlined action. Large empty areas surround the smaller content. Image and text roles reverse between chapters.

**Transfer:** Pair a contextual moment with a more intimate detail to explain one benefit without another oversized heading.

**Text style:** `body` — Söhne 400 · 15px/20px

### Landscape chapter

**Observed:** A full-width 800px-tall landscape carries an 11px mono eyebrow, a 75px title, short 15px support and reverse Outline button at the upper-left with 20px edge padding. The landscape remains the dominant visual area.

**Transfer:** Use for a broader promise, origin or long-term benefit. Keep the text small in area relative to the scene.

**Text style:** `photo-display` — PP Right Grotesk 500 · 75px/51px · tracking -0.01em

### Index and selected study

**Observed:** A small section title precedes a 473px-wide left index. Sensory rows combine thumbnail, mono description and circular marker; the selected study at right is a 453×566px image plus a 52px title, sensory caption, short description and Underlined action. The detail area is sticky on desktop. The editorial variant places a 610×762px image at left and a 473px dated index plus 26px story title at right.

**Transfer:** Use the index device to let readers browse variants or stories while seeing one richly photographed detail at a time.

**Text style:** `index-caption` — Söhne Mono 400 · 12px/14px · tracking 0.05em · uppercase

### Closing colophon

**Observed:** An editorial landing can finish with four 254×317px social images separated by 12px, flanked by a small follow label and handle, with 160px vertical breathing room. Colophon footer follows on the light field. A membership variant adds a 302px ruled call-to-action band with a 52px title, 26px support and Outline button; a catalog instead ends with restrained information accordions and a 160px category-link band. Institutional stories end with paired portrait partnership cards before the same footer.

**Transfer:** Choose the ending that matches the page's purpose while retaining the closing phrase, divided footer and small grouped links. Keep a human or editorial trace near the end instead of stacking more sales cards.

**Text style:** `heading` — PP Right Grotesk 500 · 52px/1 · tracking -0.01em

### Narrative portrait chapter

**Only for:** institutional storytelling

**Observed:** Two 690px columns with a 20px gutter and 20px page edges. One tall portrait image or video is paired with an 11px label and a narrow column of 26px/26px prose. Chapters can alternate image sides; square edges and top hairlines keep them editorial.

**Transfer:** Use for origin or process explanations that deserve longer reading without increasing body-copy density everywhere.

**Text style:** `statement` — Söhne 400 · 26px/1 · tracking -0.01em

### Evidence in a table and tiles

**Only for:** membership pages

**Observed:** A 660×990px monochrome hand photograph sits beside a 52px heading, concise support, Benefit table rows and Primary button. Another chapter puts its heading at left and a two-by-two grid of Reward tiles at right with 20px gaps.

**Transfer:** Use for a membership or structured benefit system; retain simple black dots and modest amounts instead of oversized statistics.

**Text style:** `heading` — PP Right Grotesk 500 · 52px/1 · tracking -0.01em

### Expansive headline with small tabbed proof

**Only for:** institutional responsibility chapters

**Observed:** A 75px multiline headline sits at the upper left while a 334×418px human-use image is anchored upper right. Much lower, a 335px list of 48px mono rows sits beside small explanatory copy. Hollow and filled circular endpoints continue the index vocabulary.

**Transfer:** Use for an institutional promise supported by several specific practices, giving one practice concise detail at a time.

**Text style:** `display` — PP Right Grotesk 500 · 75px/67px · tracking -0.01em

## Page flow

**Storyline:** Object-led promise → tangible options → intimate benefit story → atmospheric wider context → browsable details or proof → editorial continuation → light colophon.

### Editorial commerce landing

1. **Promise** — Split still life, small companion image, compact title and one dark action.
2. **Product selection** — Flush horizontal product rail with titles and prices.
3. **Benefit story** — Small lifestyle detail and narrow copy beside a tall object-in-use image.
4. **Wider context** — Full-width landscape with sparse reverse text.
5. **Guided discovery** — Sensory index linked to a large still-life detail.
6. **Editorial continuation** — Dated story index, then four social images.
7. **Closing** — Divided light colophon with a short philosophy line and three menu groups.

**Transfer:** Adapt the material-led editorial pacing rather than repeating a fixed number of chapters.

### Membership explanation and conversion

1. **Promise** — Large title, short proposition, join/login actions and portrait.
2. **Benefits** — Monochrome image and sparse level-comparison table.
3. **Mechanism** — Flat reward activity tiles followed by ruled redemption amounts beside a close product video.
4. **Participation proof** — Large human-held object image with a short explanatory text and outline action.
5. **Objection handling** — Large FAQ title and compact question rows.
6. **Final action** — Light ruled signup band followed by the shared colophon.

**Transfer:** Use the table, tiles and questions only when the offer has a real participation system to explain.

### Catalog browsing

1. **Category promise** — Short category heading and support beside a small monochrome image.
2. **Product selection** — Filter band and three-column product grid with occasional value flags.
3. **Objection handling** — Restrained category information and FAQ accordions.
4. **Adjacent discovery** — Single horizontal mono category-navigation band.
5. **Closing** — Shared light colophon.

**Transfer:** Let the catalog be repetitive and utilitarian; keep editorial atmosphere in the introduction and photography rather than inserting feature panels between every row.

### Origin and institutional story

1. **Point of view** — Narrow 52px statement beside a tall human-held product image.
2. **Material proof** — Botanical macro and narrow 26px prose, then a brief naming aside.
3. **Context** — Full-width landscape followed by process imagery and origin prose.
4. **Practices** — Expansive multiline headline with small linked proof tabs.
5. **External context** — Paired architectural partnership images with credits, headings and outline actions.
6. **Closing** — Shared divided colophon.

**Transfer:** Tell the new product's own origin through materials, process and real settings; keep institutional modules scoped to that story.

## Writing

Design-literate, tactile and warm without sounding precious. Brief poetic headings introduce concrete descriptions of what the object feels like and what a reader can do next.

**Do not copy:** Do not reuse LEIF names, logos, campaign artwork, slogans, sensory product names, partner identities, quotations, cultural acknowledgments, sustainability percentages, reward amounts or other brand-specific claims. Replace them with original language and verified facts appropriate to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for practical instructions. Descriptive product passages can remain impersonal; invitations are direct but not pushy.
- **Rhythm:** Headlines are often two or three words. Follow with one short descriptive paragraph; larger institutional statements use several short paragraphs. Em dashes add a gentle turn, and ampersands pair concise sensory ideas. Exclamation marks are occasional in membership copy rather than the default.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A short phrase that gives the object a character rather than listing features. | 2–4 words | “Rare forms” |
| Supporting line | An invitation tied to tactile or everyday value; one sentence with a soft rhetorical turn. | 12–25 words | “Explore our seasonal takes on familiar favourites, made to gift — or treasure.” |
| Sensory descriptor | Two complementary sensory qualities joined by an ampersand. | 2–4 words | “Smoky & Meditative”<br>“Buttery & Soft” |
| Action | Simple verb plus destination or category. | 2–4 words | “Explore Limited Edition”<br>“Read Article”<br>“Login to redeem” |
| Editorial statement | A confident design observation explained through a concrete object. | One short paragraph | “Our message is the bottle. It sounds back-to-front but formulas were developed to deliver on the promise that had already taken shape.” |
| Closing invitation | A plain question followed by a practical reason to act. | 3-word heading plus one sentence | “Ready to join?” |

**Words and phrasing to use:** form; texture; everyday; familiar; explore; discover; soft; thoughtfully; a small change; made to

**Avoid:** revolutionary; game-changing; crush it; unlock your potential; ultimate solution; hurry!!!

**Rules:**

- Make sensory language specific enough to picture: name a texture, material, temperature or quality rather than saying premium repeatedly.
- Keep conversion copy practical when explaining mechanisms; poetic titles do not replace clear terms.
- Write short action labels in natural language and let typography supply the uppercase treatment.
- For broad environmental or social intentions, pair modest language with specific, supportable practices.

## Do's and Don'ts

### Do

- Keep the ordinary opening headline at 52px/52px, 500 weight and -0.01em tracking.
- Use the 20px desktop edge with occasional genuinely edge-to-edge images.
- Stage products in 4:5 rectangles with square corners and real directional shadows inside the photography.
- Keep default prose at 15px/20px; reserve 26px/26px for narrow editorial statements.
- Use 6px button corners and 48px action height, with 0.05em mono tracking.
- Retain the solid/hollow circular selection device and 1px ruled indexes.
- Finish on the same #fafaf9 field with a 52px closing phrase and three compact link groups.
- Concentrate warm accent UI color in the 40px announcement; let photographs provide the broader palette.

### Don't

- Do not turn the 6px rectangular actions into fully rounded pills.
- Do not add drop shadows or elevated rounded containers to the flat editorial surface system.
- Do not apply the lemon promotional flag color to ordinary section backgrounds.
- Do not use the 75px/51px single-line recipe for multiline paragraphs or FAQ headings.
- Do not replace 11–13px mono annotation with oversized bold sans-serif labels.
- Do not make every heading bold sans body type; preserve the distinct display grotesk and lightweight 34px section titles.
- Do not put white cards with large gutters around the flush three-column commerce grid.
- Do not convert the light colophon into a black full-width newsletter billboard.

## Motion and responsive

### Motion

**Observed:**

- Buttons and index rows declare 0.3s transitions. Other surfaces and actions include 0.5s declarations; their detailed property/easing pairings are not uniform.
- Desktop detail compositions include sticky content beside a scrolling index.
- The fixed navigation has translated hidden states as well as the visible opening treatment.

**Transfer:**

- Preserve the index/detail relationship when content changes, including the clear active dot and rule.
- Keep action feedback restrained and tonal: black moves to charcoal rather than a bright accent.

**Unknown:**

- Scroll-trigger logic and complete interaction choreography are not established.
- No single global easing curve or animation duration is established.
- Focus-visible treatment is not established.

### Responsive

**Observed:**

- Declared width boundaries include 576px, 768px, 992px, 1200px, 1400px and 1680px.
- Desktop layouts use separate hidden/shown variants around editorial indexes.

**Transfer:**

- On narrow layouts, preserve the large/small photographic relationship by placing the main object before the smaller detail and its text.
- Convert the wide index/detail composition into a stacked selector with its associated detail; do not shrink the 473px desktop index and all detail columns side by side.
- Keep product metadata and actions readable rather than scaling the desktop page as a single image.

**Unknown:**

- Exact mobile type sizes, column counts, menu behavior and stacking order are not established. These adaptations are design guidance rather than measured mobile recipes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
