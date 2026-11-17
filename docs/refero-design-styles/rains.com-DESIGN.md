# Rains — monumental material encounters

## Overview

An image-led, urban editorial style that makes functional products feel like cultural objects. Vast studio photographs, close material details and architectural scenes dominate a black, white and grey framework, with color carried mostly by the things being photographed. Heavy grotesk headlines contrast with very small practical navigation and compact commerce information; the overall density alternates between immersive imagery and sparse white utility areas.

### Essentials

- The headline behaves like an image-sized label: semibold grotesk at 216.6px/1.02 in the opening, reaching 245px for shorter chapter titles, with normal tracking and a 16px edge inset.
- The opening is a close encounter rather than a text pitch: full-bleed portrait photography behind a single-line title across almost the entire width, a 48px/1 support line and 40px-high actions in the lower half of the first 900px.
- Utilities float like frosted equipment controls: 36px-high navigation capsules with 12px backdrop blur; primary actions are dark 40px pills with 12px 32px padding and 16px bold labels.
- The framework stays monochrome: #ffffff canvas, #10100f ink and #26292a actions. Almost all large colored areas belong to photography, not interface fills; products supply muted green, navy, mauve and occasional stronger accents.
- Images carry the argument: tall full-width material portraits alternate with square-edged two-up pictures separated by 8px and four-column product strips without gutters. If original campaign media is unavailable, use one tightly lit product macro and a consistent neutral-ground product series.
- The identity returns at architectural scale: the closing mark spans 1408px within 16px side margins at desktop, about 446px tall, below compact service and newsletter columns. Recreate this device with the new identity as fitted vector lettering, not a conventional tiny footer logo.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#10100f` | `--color-ink` | text, background, link | Primary typography and solid editorial highlight strips. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Utility sections and inverse labels over imagery. |
| Light frost | `#f0f0f0` | `--color-frost` | surface | Visible light-glass tone over white, made with rgba(227,227,227,0.52); it takes on the image beneath it. |
| Secondary grey | `#555554` | `--color-secondary` | text | Subdued footer metadata. |
| Dark smoke | `#40403f` | `--color-smoke` | surface, action | Visible dark-glass tone over white, made with rgba(16,16,15,0.8); newsletter action and announcement treatment. |
| Graphite action | `#26292a` | `--color-action` | action, surface | Default filled actions on photographic chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial index pages | Muted index text | `#797979` | `--color-muted` | text | Inactive outlined index pills. |
| editorial index pages | Index outline | `#cfcfcf` | `--color-outline` | border | One-pixel inset outlines on index pills. |

## Typography

- **EuropaGroNr2SH** — Headlines, navigation, product labels and actions. Compact, sturdy neo-grotesk with a large lowercase presence; the semibold heading cut feels blunt and utilitarian rather than luxurious. If unavailable, use **Inter**. Use 400 for prose and 600–700 for headings and controls; preserve normal tracking. Font stack: "EuropaGroNr2SH", "Inter", ui-sans-serif, system-ui, Arial, sans-serif.
- **EuropaGroNr2SB** — Regular body prose and outlined index pills. The regular text companion to the sturdy heading face, compact and plainly functional. If unavailable, use **Inter**. Use regular 400 with normal tracking. Font stack: "EuropaGroNr2SB", "Inter", ui-sans-serif, system-ui, Arial, sans-serif.
- **EuropaGroNr2SB-Con** (only for seasonal editorial campaigns) — Credits, featured-person labels and editorial biographies. Narrow sans serif with tall compressed capitals, resembling printed credits rather than code. If unavailable, use **Barlow Condensed**. Use regular 400; do not replace it with monospace. Font stack: "EuropaGroNr2SB-Con", "Barlow Condensed", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter-display | EuropaGroNr2SH | 600 | 245px | 1.02 | normal | Short photographic chapter labels; shrink longer titles to maintain one line, rather than changing weight or tracking. |
| opening-display | EuropaGroNr2SH | 600 | 216.6px | 1.02 | normal | Single-line opening title, fitted across the available width. |
| display-support | EuropaGroNr2SH | 600 | 48px | 1 | normal | One-sentence support immediately below monumental titles. |
| image-tile-title | EuropaGroNr2SH | 600 | 40px | 0.9 | normal | Paired category-image links, with underline treatment. |
| section-heading | EuropaGroNr2SH | 600 | 24px | 0.9 | normal | Small headings in white editorial sections and collection endings. |
| product-label | EuropaGroNr2SH | 700 | 20px | 0.9 | normal | Product name and price share the same scale and weight. |
| service-statement | EuropaGroNr2SH | 600 | 20px | 0.9 | normal | Compact multiline service reassurance at the start of the footer. |
| action | EuropaGroNr2SH | 700 | 16px | 1 | normal | Primary, outline and newsletter buttons. |
| navigation | EuropaGroNr2SH | 700 | 14px | 1 | normal, uppercase | Compact navigation and utility labels. |
| body | EuropaGroNr2SB | 400 | 14px | 1.2 | normal | Short introductory prose, support text and newsletter descriptions. |
| utility-heading | EuropaGroNr2SH | 600 | 14px | 1.2 | normal | Footer column labels and newsletter invitation. |
| footer-link | EuropaGroNr2SH | 400 | 14px | 0.9 | normal | Plain service and company links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial index pages | index-display | EuropaGroNr2SH | 600 | 120px | 0.9 | normal | Black typographic introduction on white. |
| location and spatial portfolio pages | directory-heading | EuropaGroNr2SH | 600 | 32px | 0.9 | normal | Practical directory and gallery titles after the image-led opening. |
| seasonal editorial campaigns | campaign-feature | EuropaGroNr2SB-Con | 400 | 32px | 1.2 | normal, uppercase | Featured subject heading; the name is reversed out on an inline dark strip. |
| seasonal editorial campaigns | image-closing-heading | EuropaGroNr2SH | 600 | 32px | 1.02 | normal | Small closing invitation over a wide architectural photograph. |
| seasonal editorial campaigns | campaign-caption | EuropaGroNr2SB-Con | 400 | 20px | 1.2 | normal, uppercase | Credits, context lines and editorial highlight text. |
| seasonal editorial campaigns | campaign-body | EuropaGroNr2SB-Con | 400 | 16px | 1.35 | normal | Short biographical paragraphs alongside large portraits. |
| editorial index pages | index-pill | EuropaGroNr2SB | 400 | 14px | 0.9 | normal | Outlined topic links beneath the introduction. |

**Notes:**

- Normal letter spacing is consistent across the hierarchy. The force comes from weight, image scale and the abrupt jump from 14–20px utilities to 216.6–245px headlines, not decorative tracking.
- The core family uses a semibold heading cut and a regular body cut. Preserve this distinction even if using one substitute family.
- Photographic headline letters have a light-glass masked treatment and read white over pale studio scenes but grey over dark scenes; keep this material relationship rather than adding a rectangular panel behind the title.
- Fit long display titles to the line. Short titles need not be stretched to fill the entire width; the default upper size is 245px.

## Layout

**Density:** Airy in section composition but compact in text and controls; long image stages meet tightly grouped functional information.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Image gutters, navigation capsule separation and swatch-row gaps. |
| 12px | Button vertical padding and heading-to-prose separation. |
| 16px | Page inset, hero text-stack separation and product metadata padding. |
| 20px | Gap between paired hero actions; spacing after newsletter prose. |
| 32px | Button side padding and separation between index introduction elements. |
| 48px | Footer major grid gap and separation before metadata. |
| 56px | White section vertical padding and breaks around paired imagery. |
| 80px | Footer top padding. |

### Containers and grids

- **edge container**: max width 1440px · side padding 16px. At a 1440px desktop width, utility content occupies 1408px; image stages run full bleed beyond this container.
- **paired imagery**: 2 columns · gap 8px · side padding 16px. Two 700px-wide photographs within the desktop inset; tall crops, square edges.
- **commerce strip**: 4 columns · gap 0px · side padding 0px. Four equal 360px product columns, each with a 360px by 540px image and 16px-inset metadata.
- **editorial prose**: max width 700px · side padding 16px. Restrained introduction width on white editorial pages.
- **footer grid**: 3 columns · gap 48px · side padding 16px. Newsletter and service reassurance take the left third; four narrow utility columns share the remaining two thirds.
- **campaign feature** (only for seasonal editorial campaigns): 3 columns · gap 0px · side padding 16px. A portrait occupies two thirds of the width, with a one-third text column and 32px internal side separation; reverse sides between features.
- **campaign collage** (only for seasonal editorial campaigns): 3 columns · gap 8px · side padding 16px. Three 464px columns of portrait images and interview tiles, with deliberate unoccupied cells as part of an asymmetric editorial arrangement.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 9999px (pill) |
| image panels | 0px |
| swatches | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | selected swatch | `0px 0px 0px 1px #ffffff, 0px 0px 0px 2px rgba(16,16,15,0.2)` | Double-ring selection indicator on circular product swatches. |
| editorial campaigns and spatial invitations | outline action | `inset 0px 0px 0px 1px rgba(255,255,255,0.8)` | A light edge on transparent photographic actions, not a raised shadow. |
| editorial index pages | index pill edge | `inset 0px 0px 0px 1px #cfcfcf` | Faint perimeter for small topic pills. |

### Surfaces

#### White canvas · level 0

**Use:** All practical and editorial text areas.

**CSS:** `background: #ffffff; color: #10100f`

**Observed:** No decorative paper texture or colored content bands; the imagery supplies material richness.

**Transfer:** Let text sections remain plain and make the transition from photograph to white feel direct.

#### Light glass · level 1

**Use:** Floating navigation and inverse actions over dark media.

**CSS:** `background: rgba(227,227,227,0.52); backdrop-filter: blur(12px); border-radius: 9999px`

**Observed:** Separate capsules reveal the scene underneath; they are not contained in an opaque full-width navigation bar.

**Transfer:** Keep blur local to controls instead of applying it to whole content sections.

#### Dark glass · level 1

**Use:** Newsletter action and slim announcement surface.

**CSS:** `background: rgba(16,16,15,0.8); color: #ffffff; backdrop-filter: blur(12px)`

**Observed:** The button is pill-shaped; the announcement is a square-edged full-width strip with centered small copy.

**Transfer:** Use as a utility material, not the default page background.

#### Inline editorial strip · level 1

**Only for:** seasonal editorial campaigns

**Use:** Credits and highlighted names within narrow editorial typography.

**CSS:** `background: #10100f; color: #ffffff; padding: 1px 5px; border-radius: 0px`

**Observed:** A black strip follows the text line rather than becoming a card or badge.

**Transfer:** Reverse the key phrase or answer only; leave nearby context in black on white.

## Components

### Floating navigation

**Use:** Persistent browsing above full-bleed imagery.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; padding: 16px 16px 0px; z-index: 30; display: flex; gap: 8px`

**Text style:** `navigation` — EuropaGroNr2SH 700 · 14px/1 · uppercase

**Observed:** A compact identity capsule and one long category capsule sit on the left; separate search and cart capsules align right. The row occupies 52px. Each capsule is 36px high and uses Light glass; categories have 32px separation.

**States:** Declared: hover underlines category links with 2px underline offset; focus-visible uses the same underline.

**Transfer:** Keep category labels terse and use the new identity inside the small left capsule.

### Primary button

**Use:** Default marketing action over photography.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 12px 32px; border-radius: 9999px; background: #26292a; color: #ffffff; backdrop-filter: blur(8px)`

**Text style:** `action` — EuropaGroNr2SH 700 · 16px/1

**Observed:** Labels stay on one line; width follows the wording. One or two actions sit left-aligned beneath the support line, not centered.

**States:** Declared: hover background-color transparent and color #10100f; focus-visible uses the same background and color.

### Newsletter button

**Use:** Compact footer sign-up action.

**CSS:** `display: inline-flex; height: 40px; padding: 12px 32px; border-radius: 9999px; background: rgba(16,16,15,0.8); color: #ffffff; backdrop-filter: blur(12px)`

**Text style:** `action` — EuropaGroNr2SH 700 · 16px/1

**Observed:** Sits below a small heading and two-line description, separate from the service-link columns.

**States:** Declared: hover background-color #10100f; focus-visible background-color #10100f.

### Product card

**Use:** Direct commerce proof between photographic chapters.

**CSS:** `width: 360px; border-radius: 0px; background: #ffffff`

**Text style:** `product-label` — EuropaGroNr2SH 700 · 20px/0.9

**Observed:** A 360px by 540px full-body studio product image comes first. Beneath it, a 16px-padded row places product name left and price right, followed 8px later by small circular color options. No surrounding border, shadow or enclosing rounded surface.

**Transfer:** Use equal-scale product views on the same pale photographic ground. Keep names and prices in one compact row.

### Color swatch

**Use:** Variant selection below product labels.

**CSS:** `width: 12px; height: 12px; border-radius: 50%; background-size: cover; background-position: 50% 50%; box-shadow: 0px 0px 0px 1px #ffffff, 0px 0px 0px 2px rgba(16,16,15,0.2)`

**Observed:** The active color gets a white inner ring and faint dark outer ring. Other swatches have no selection edge; the row uses 8px gaps.

**Transfer:** Use actual product colors or tiny material textures rather than unrelated interface accent colors.

### Service link

**Use:** Footer lists and practical navigation.

**CSS:** `display: inline-block; padding: 8px 0px; color: #10100f`

**Text style:** `footer-link` — EuropaGroNr2SH 400 · 14px/0.9

**Observed:** Plain, stacked text links under small semibold column headings, without card backgrounds or separators.

### Monumental closing mark

**Use:** The final identity impression after all utility content.

**CSS:** `display: block; width: 100%; height: auto; color: #10100f`

**Observed:** A fitted vector wordmark spans the inset content width, 1408px by 446px at desktop, beneath the tiny legal row. Its black mass is much larger than any nearby copy.

**Transfer:** Use a custom fitted SVG of the new wordmark. If no logo artwork exists, convert a heavy condensed uppercase rendering of the new product name to vector paths and fit it to the full content width.

### Outline image button

**Only for:** editorial campaigns and spatial invitations

**Use:** Secondary invitation on wide photographs.

**CSS:** `display: inline-flex; height: 40px; padding: 12px 32px; border-radius: 9999px; color: #ffffff; background: transparent; backdrop-filter: blur(8px); box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.8)`

**Text style:** `action` — EuropaGroNr2SH 700 · 16px/1

**Observed:** An inset light edge replaces the dark fill. Collection overview endings use the inverse black edge and black label on white.

**States:** Declared: hover background-color transparent and color #10100f; focus-visible uses the same treatment.

### Index topic pill

**Only for:** editorial index pages

**Use:** Jump links beneath a text introduction.

**CSS:** `display: inline-block; padding: 12px 16px; border-radius: 9999px; color: #797979; box-shadow: inset 0px 0px 0px 1px #cfcfcf`

**Text style:** `index-pill` — EuropaGroNr2SB 400 · 14px/0.9

**Observed:** A horizontal sequence of short topic labels; the outlines remain light and the pills are much smaller than the introductory title.

**States:** Declared: hover background-color rgba(252,252,252,1) and color #10100f; focus-visible uses the same treatment.

### Editorial highlight

**Only for:** seasonal editorial campaigns

**Use:** Credits, subjects and interview answers.

**CSS:** `display: inline; padding: 1px 5px; background: #10100f; color: #ffffff`

**Text style:** `campaign-caption` — EuropaGroNr2SB-Con 400 · 20px/1.2 · uppercase

**Observed:** Narrow uppercase text reversed on an unrounded text-hugging strip. Several highlighted phrases may follow an unhighlighted prompt on the same line.

## Imagery and graphics

### Immersive product portraits

**Use:** Opening and major chapter stages.

**Observed:** Close-cropped models and products against pale seamless studio grounds, with black equipment, cables and sculptural props. Soft, clear light reveals waterproof coatings, knit ribs and shiny padded fabric. Tall images occupy the whole page width and continue through roughly two desktop view heights; text overlays the lower half rather than competing beside them.

**Transfer:** Photograph a person using the new product, or a large object macro, against a cool light-grey studio ground with a few purposeful tools from its world. Keep convincing shadows, material detail and a large subject; minimum acceptable media is a sharply lit close-up with ample pale negative space.

### Material proof macro

**Use:** A visual chapter that makes function tangible.

**Observed:** A dark shoe surface, woven elastic and water droplets are shown at huge scale with cool neutral light; another campaign stages metal tableware under falling water against a dark ground. These are tactile photographic scenes, not interface gradients.

**Transfer:** Show the new product's defining material under a relevant physical condition: light raking across a finish, droplets, folds or a cutaway. Keep the condition real and the composition severe; use a single high-resolution still if motion footage is unavailable.

### Catalog studio series

**Use:** Four-up commerce strips and dense overview grids.

**Observed:** Full-length frontal figures at a consistent scale on pale grey studio backgrounds, with the product color left intact. Overview images isolate individual items on white and place them in ten narrow columns.

**Transfer:** Use consistent camera height, lighting, pose and object scale. For non-wearable products, use straight-on isolated objects with the same baseline and generous internal breathing room.

### Editorial interview collage

**Only for:** seasonal editorial campaigns

**Use:** Long-form cultural storytelling alongside product imagery.

**Observed:** Portrait photographs, overhead scenes and pale interview tiles occupy a three-column grid. Some grid cells intentionally remain white; black answer strips and tiny product labels punctuate the pictures. Dominant black props and white studio floor make occasional colored products vivid without graphic color blocks.

**Transfer:** Pair creators, users or making-process images with short questions and answers. Retain the asymmetric grid and printed-credit typography rather than turning interviews into testimonial cards.

**Build:** Use a three-column CSS grid with 8px gaps and 16px outer inset. Place portrait media at a 4:5 ratio, reserve selected cells as editorial negative space, and place concise question-and-answer text within neighboring cells; reverse only key answer spans using Inline editorial strip.

### Architectural material gallery

**Only for:** location and spatial portfolio pages

**Use:** Media-only opening, environment proof and alternating spatial essays.

**Observed:** Wide and portrait interiors emphasize brushed steel shelving with circular cutouts, beige textured walls, pale tile grids, timber seating, exposed services and dark sculptural furniture. Occasional yellow planes or blue displays exist inside the photographed space. A two-thirds-width tall view alternates left and right, with smaller details and short text in the remaining third.

**Transfer:** Photograph the new product's real environment with straight architectural lines, restrained neutral materials and balanced light. Alternate broad spatial views with tactile details; keep all imagery square-edged.

### Icons

**Observed:** Utility symbols are small and monochrome: 14px search/cart glyphs, a 20px globe with 0.8px rounded strokes and 28px carousel arrows with 1px square-ended strokes. They sit next to labels or at the edges of image strips.

**Transfer:** Use minimal black utility symbols at these sizes. Avoid decorative icon grids; use icons only for a real action or navigation aid.

## Section recipes

How recurring sections are built.

### First screen: Immersive label opening

**Observed:** A full-bleed 1440px-wide studio portrait extends through a 1799px-tall stage. In the first 900px, a close face and dark coated upper body fill the background, Floating navigation occupies the top edge, and the lower half carries a single-line 216.6px/1.02 semibold title across almost the full width. A left-aligned 48px support sentence follows with 16px separation; two Primary buttons follow with another 16px separation and 20px between them. All main text and actions are visible before the first fold, while the portrait's lower body and next commerce strip remain below. The layer order is photograph, light-glass masked title and support, then dark filled controls; no enclosing text panel.

**Transfer:** Use the same close encounter with the new product: one image-sized promise, one short benefit and one or two concrete destinations. Without a campaign portrait, enlarge a material-rich product still until it dominates the frame. Editorial indexes instead open on white with index-display prose and topic pills; spatial pages open with a wide environment video and place the practical heading below it. Seasonal editorials can open with a media-only poster carrying condensed embedded credits.

**Avoid:** Do not replace this opening with a centered small heading above a floating product card, a two-column text-and-thumbnail layout or a dark gradient marketing panel.

**Text style:** `opening-display` — EuropaGroNr2SH 600 · 216.6px/1.02

### Sticky photographic chapter

**Observed:** Immersive product portraits run full width, often about 1800px tall. A viewport-height sticky text layer holds a chapter-display, display-support and Primary button group 16px inside the left edge as the image continues behind it. Longer titles shrink to fit rather than wrap.

**Transfer:** Use for a major capability or product family. Keep the prose to a single functional sentence; let a genuinely different image carry each chapter.

**Text style:** `chapter-display` — EuropaGroNr2SH 600 · 245px/1.02

### Commerce interruption

**Observed:** A commerce strip uses four Product cards with no column gap and 56px white space after the group. The pale image grounds meet directly; metadata remains compact and black on white.

**Transfer:** Use a short range of real variants, configurations or complementary products as tangible proof between immersive chapters.

**Text style:** `product-label` — EuropaGroNr2SH 700 · 20px/0.9

### Paired visual destinations

**Observed:** Two tall, square-edged photographs sit in paired imagery with 56px vertical section padding. Underlined image-tile-title links align left near the vertical center, above the photographs.

**Transfer:** Offer two useful ways into the new collection or product world. Make both destinations equally vivid and keep their labels short.

**Text style:** `image-tile-title` — EuropaGroNr2SH 600 · 40px/0.9

### Plain editorial heading pair

**Observed:** White sections use section-heading above 14px body prose, separated by 12px, within the 16px edge container. Large image rails follow; the heading does not become a display-scale campaign promise.

**Transfer:** Use to introduce practical archives, updates or resources. Keep the heading and explanation subordinate to the following media.

**Text style:** `section-heading` — EuropaGroNr2SH 600 · 24px/0.9

### Utility to monumental identity

**Observed:** White canvas begins with 80px top padding. A left third contains a tightly stacked service-statement, then a 40px break before newsletter copy and Newsletter button; the other two thirds hold four Service link columns. After the utility area and tiny legal row, Monumental closing mark fills almost the entire width. All four page types end with this same black-on-white identity treatment.

**Transfer:** Close with useful reassurance and a restrained subscription invitation, then make the new identity the final graphic object. Keep the closing mark even on short informational pages.

**Text style:** `service-statement` — EuropaGroNr2SH 600 · 20px/0.9

### Featured subject editorial

**Only for:** seasonal editorial campaigns

**Observed:** A 939px by 1173px portrait occupies two thirds of the inset width; a narrow campaign-feature heading and campaign-body biography occupy the other third with 32px separation. The text column sticks beside the portrait. Reverse the arrangement for another feature, then use Editorial interview collage.

**Transfer:** Use for a maker, customer or process story that merits a longer visual chapter; retain the contrast between a large image and a small factual text column.

**Text style:** `campaign-feature` — EuropaGroNr2SB-Con 400 · 32px/1.2 · uppercase

### Spatial portfolio essay

**Only for:** location and spatial portfolio pages

**Observed:** After a 1440px by 810px environment video and practical directory, directory-heading introduces a staggered gallery. Tall 936px by 1170px photographs alternate sides within 16px edges. Detail views occupy smaller adjacent cells, and compact 24px statements sit in the remaining third. A centered newsletter invitation closes the gallery before the shared footer.

**Transfer:** Use to reveal product contexts, installations or environments. Keep intentional asymmetry but fill the composition with meaningful photography rather than equal cards.

**Text style:** `directory-heading` — EuropaGroNr2SH 600 · 32px/0.9

### Collection overview ending

**Only for:** seasonal editorial campaigns

**Observed:** A wide architectural photograph holds a small image-closing-heading, a compact support line and Outline image button at its lower left. On white below, a 24px title introduces a dense ten-column, four-row overview of isolated products, followed by a centered black-outline action and 56px bottom space.

**Transfer:** After the emotional story, give the reader a concrete view of the available range and one route to browse everything.

**Text style:** `image-closing-heading` — EuropaGroNr2SH 600 · 32px/1.02

## Page flow

**Storyline:** Immersive encounter → tangible range or context → deeper visual chapters → practical next destination → service reassurance and monumental identity.

### Image-led collection or product-family landing

1. **Promise** — A close studio portrait with an image-sized label and direct shopping actions.
2. **Tangible proof** — Four-up product strip followed by paired visual destinations.
3. **Capability chapters** — Repeated full-bleed product portraits and material macros, punctuated by two-up images and a moving editorial scene.
4. **Context and final destination** — Collaboration imagery and a physical environment chapter extend the product into a broader world.
5. **Reassurance and identity** — Compact service/newsletter footer culminates in a full-width black vector mark.

**Transfer:** Use the chapter system for a few genuinely different product advantages; preserve the contrast of enormous imagery and modest functional actions without reproducing the original number of chapters.

### Long-form seasonal editorial with commerce woven into the story

1. **Atmospheric introduction** — Square photographic poster, condensed credits and a wide film.
2. **Human context** — Paired portraits lead into alternating two-thirds portrait features with narrow biographies and interview collages.
3. **Product proof** — Full-width image invitations and four-item shopping strips interrupt the editorial.
4. **Range and final action** — A large closing portrait leads to an environment invitation, a ten-column product overview and a centered browse action.
5. **Reassurance and identity** — The shared utility footer and monumental mark.

**Transfer:** Build a visual essay around real users or making culture, connecting each story back to tangible products instead of a separate sales pitch.

### Editorial index and institutional introduction

1. **Orientation** — A 120px black title, narrow factual introduction and small outlined topic pills on white.
2. **Discovery** — Small heading pairs introduce horizontal image rails, then a three-panel edge-to-edge archive with centered underlined labels.
3. **Experiential proof** — An architectural film with a small bottom-left statement and outline action.
4. **Practical trust** — A directory map and plain document links, not decorative proof cards.
5. **Reassurance and identity** — The same newsletter/service footer and oversized wordmark.

**Transfer:** Use this lighter, more informational variant for an about page or resource index, retaining imagery and the same closing identity rather than adopting campaign-scale headings everywhere.

### Practical locator plus spatial portfolio

1. **Context** — A wide interior video starts without a large headline overlay.
2. **Utility** — A 32px title introduces a location list alongside a pale map with dark cluster markers.
3. **Experiential proof** — A staggered architectural gallery alternates large left/right photographs, details and short statements.
4. **Closing invitation** — Centered newsletter heading and a narrow form precede the shared footer.
5. **Reassurance and identity** — Service columns and a full-width black mark finish the page.

**Transfer:** Pair a useful directory or finder with a material-rich portfolio of real environments; keep the functional map subordinate to the product world's imagery.

## Writing

Direct, composed and design-literate. Functional statements coexist with brief cultural references; confidence comes from naming things plainly rather than piling on superlatives.

**Do not copy:** Do not reuse the Rains name, logos, collection names, collaborators, photography, artist quotes, proprietary product names, shipping promises, warranty terms or performance claims. Replace all of them with the new product's own identity and verified facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly impersonal product statements and imperative actions. Institutional copy uses we; occasional invitations address the reader as you without sounding conversationally chatty.
- **Rhythm:** Headlines are usually one category, a short title or a named volume. Support is a single compact sentence. Editorial paragraphs are factual and compact; actions begin with a verb. Full stops can punctuate even a one-word title.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A named release, volume or plain product category; no long persuasive sentence. | 1–5 words | “Winter: Volume I”<br>“Footwear.” |
| Supporting line | One clear functional idea with a little conceptual confidence. | 4–10 words | “A collection dedicated to performance.”<br>“Engineered to handle water.”<br>“When rainwear isn’t necessary.” |
| Primary action | Shop or Explore followed by an explicit destination. | 2–5 words | “Shop Backpacks”<br>“Explore the campaign” |
| Editorial section introduction | A simple noun title followed by one sentence explaining what can be found there. | 1–2 word title; 5–10 word sentence | “Updates on the most recent from [Brand].”<br>“New store openings around the world.” |
| Closing invitation | Short physical verbs, then one practical next step. | 5–8 words | “See it, touch it, try it on.” |

**Words and phrasing to use:** collection; volume; engineered; performance; fabric; urban; explore; featuring; spaces; designed

**Avoid:** revolutionary; game-changing; unlock your potential; ultimate solution; delightful; supercharge; magical

**Rules:**

- Name the object before explaining its benefit.
- Keep the main support line to one claim that the image can reinforce.
- Use factual, destination-specific action labels rather than vague conversion language.
- Keep editorial credits concise; uppercase is a typographic treatment, not a reason to shout in the prose.

## Do's and Don'ts

### Do

- Keep desktop text and utility areas 16px inside the viewport edge while letting photographic stages run full bleed.
- Use 216.6px/1.02 opening type and 245px/1.02 short chapter type, with normal tracking and semibold weight.
- Place 48px/1 support lines beneath display titles with a 16px gap.
- Make default image actions 40px pills with 12px 32px padding and 16px bold labels.
- Keep paired image gutters at 8px and commerce strips at four equal columns with no gutter.
- Use 56px white section padding to punctuate long photographic stages.
- Finish with the full-width vector identity beneath the compact utility footer.
- Let photographed materials and products carry color while the page framework stays white, near-black and grey.

### Don't

- Do not add a site-wide accent-color button system; the default action fill is #26292a.
- Do not round photographs to match the controls; images and editorial strips have 0px corners.
- Do not introduce card drop shadows; the characteristic shadows are one-pixel inset edges or swatch rings.
- Do not replace normal tracking with fashion-style widely spaced capitals or tightly kerned display type.
- Do not enlarge navigation to body-hero scale; its uppercase labels stay 14px/1 within 36px-high capsules.
- Do not use condensed campaign credits as the default typeface for ordinary marketing prose.
- Do not place product names in pale lightweight captions; their 20px/0.9 weight-700 treatment matches prices.
- Do not end on a conventional dark multi-column footer; the closing utility area is white and the black identity is the dominant final object.

## Motion and responsive

### Motion

**Observed:**

- Photographic chapter text uses a sticky viewport-height overlay while the long media stage scrolls behind it.
- Primary and newsletter actions declare 0.2s transition duration; index pills and swatches declare 0.3s, and the search capsule declares 0.5s.
- Category links declare an underline on hover and focus-visible; filled photographic actions switch to transparent with dark text.

**Transfer:**

- Keep the text-to-picture relationship stable within each long photographic chapter, then release it at the next chapter.
- Retain the source-specific action state changes and local glass treatment rather than adding decorative entrance effects.

**Unknown:**

- Per-element easing for these controls and video playback behavior are not established.
- No specific scroll-scrubbing, automatic slide timing or entrance-animation sequence is prescribed.

### Responsive

**Observed:**

- Width breakpoints are declared at 414px, 440px, 768px, 1024px, 1280px and 1536px; the spatial page also declares 600px.
- Desktop category navigation is restricted to the large-screen layout; product items declare half-width and quarter-width variants.
- The hero support class changes from 16px at smaller widths to 48px on large screens; paired image links declare a smaller-screen 75vh height capped at 125vw.

**Transfer:**

- On narrow screens, fit the monumental title to available width and preserve its overlay relationship with the dominant image rather than introducing a separate text card.
- Reduce commerce strips to two visible items and simplify navigation to compact utility capsules.
- Stack the editorial feature's image and text while retaining the condensed-credit identity only in its scoped campaign context.

**Unknown:**

- Exact mobile rendering, menu behavior and fitted headline sizing rules at each breakpoint are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
