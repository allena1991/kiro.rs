# Houseplant — high design, low pretension

## Overview

A warm, tactile retail style with the confidence of a design magazine and the friendliness of a living room. Cream and chocolate grounds support colorful objects, atmospheric photography, condensed display lettering, an extended campaign grotesk and rounded editorial serifs. It suits design-led physical products and personality-rich launches, alternating dense shopping grids with broad photographic pauses.

### Essentials

- Headlines switch personalities without losing warmth: extended uppercase campaign type at 50.8px/0.9, weight 900 and -0.05em tracking; condensed statement lettering at 128px/0.9, weight 400 and -0.03em.
- The opening is an inset cinematic room, not a text-and-icon pitch: a 1312px × 620px media panel inside 64px side gutters, 12px corners, with centered copy and a 240px × 48px action near its foot.
- Actions are little rectangular signs: 4px corners, 12px 16px padding, bold 16px labels and a right-hand arrow; outline versions use a 2px inset chocolate edge rather than pills.
- Color lives mainly in the objects: cream #f4f1e0 and oat #e5e0ca dominate shopping areas, chocolate #321e1e grounds narrative panels and the closing region; mint #bbe7db is concentrated in a featured campaign's text, rules and action rather than spread across the page.
- Objects receive real space: 310px × 388px portrait media in four-column grids with 24px gaps, followed by unboxed names, prices and 24px circular material swatches. For nonphysical products, stage a tangible printed or screen-based artifact in the same proportions.
- A monumental closing wordmark is a signature, not a small legal sign-off: full-width vector lettering occupies a 1440px × 246px strip beneath the dark footer. Use the new product's own name as an equally assertive typographic graphic.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chocolate | `#321e1e` | `--color-ink` | text, background, border | Default ink, dark narrative panels and full-width footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#f4f1e0` | `--color-canvas` | background, text, surface | Page canvas, light text on chocolate and light buttons. |
| Oat | `#e5e0ca` | `--color-oat` | surface, text, border, action | Product media backing, directory hero panels, campaign action fill and footer lettering. |
| Dusty mauve | `#baa7a7` | `--color-badge` | surface | Small editorial status badges over product media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| featured product campaigns | Soft mint | `#bbe7db` | `--color-mint` | text, border, action | Featured campaign title, paired rules, border and action fill. |
| catalog filters | Warm taupe edge | `#bab2a6` | `--color-input-edge` | border | Visible chocolate at 30% over cream on price inputs. |

## Typography

- **Helvetica Neue LT Pro** — Body, commerce labels, navigation and directory titles. Neutral neo-grotesk; regular paragraphs with tightly tracked bold labels. If unavailable, use **Roboto**. Use 400 and 700; preserve negative tracking in bold labels. Font stack: "Helvetica Neue LT Pro", "Roboto", "Helvetica Neue", Helvetica, Arial, sans-serif.
- **Houseplant** — Large narrative statements and section headings. Distinctive compact display lettering with a strong vertical rhythm. If unavailable, use **Barlow Condensed**. Use 400 and preserve compact line height; tune wrapping to the narrow display proportions. Font stack: "Houseplant", "Barlow Condensed", "Helvetica Neue", Arial, sans-serif.
- **eurostile-extended** — Wide uppercase opening campaign headline. Heavy extended geometric lettering with squared construction. If unavailable, use **Michroma**. Use its wide construction; the available weight is lighter, so retain the broad silhouette rather than condensing it. Font stack: "eurostile-extended", "Michroma", Arial, sans-serif.
- **New Spirit** — Press quotations, small product badges and story chapter titles. Soft rounded serif with a friendly, slightly nostalgic editorial tone. If unavailable, use **Fraunces**. Use 500, with restrained optical character. Font stack: "New Spirit", "Fraunces", Georgia, "Times New Roman", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Houseplant | 400 | 128px | 0.9 | -0.03em | Monumental narrative heading or centered featured-product title. |
| campaign-headline | eurostile-extended | 900 | 50.8px | 0.9 | -0.05em, uppercase | Centered opening campaign headline. |
| section-heading | Houseplant | 400 | 44px | 1 | normal | Section leads above merchandise and editorial grids. |
| quote | New Spirit | 500 | 32px | 1.25 | -0.03em | Centered press quotation. |
| card-heading | Helvetica Neue LT Pro | 700 | 21px | 1.25 | -0.03em | Editorial card titles. |
| body | Helvetica Neue LT Pro | 400 | 18px | 1.5 | normal | Hero support and narrative-panel paragraphs. |
| strong-label | Helvetica Neue LT Pro | 700 | 18px | 1.35 | -0.03em | Eyebrows, merchandise names and newsletter heading. |
| price | Helvetica Neue LT Pro | 400 | 18px | 1.35 | -0.03em | Main price digits beneath names. |
| action | Helvetica Neue LT Pro | 700 | 16px | 1.35 | -0.03em | Button labels. |
| navigation | Helvetica Neue LT Pro | 700 | 14px | 1.35 | -0.03em | Top-level navigation and compact editorial actions. |
| caption | Helvetica Neue LT Pro | 400 | 14px | 1.35 | normal | Editorial card descriptions and footer links. |
| badge | New Spirit | 500 | 12px | 1.8 | -0.03em | Small product status labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company stories | letter-heading | Houseplant | 400 | 96px | 0.9 | -0.03em | Long-form personal letter heading. |
| directories and company stories | directory-title | Helvetica Neue LT Pro | 700 | 48px | 0.9 | -0.03em | Straightforward directory or story opening title. |
| company stories | story-heading | New Spirit | 500 | 32px | 1.25 | -0.02em | Editorial chapter heading and opening quotation. |
| company stories | process-heading | New Spirit | 500 | 32px | 1 | -0.02em | Compact process-panel heading. |
| featured product campaigns | campaign-support | Helvetica Neue LT Pro | 400 italic | 18px | 1.5 | normal | A short provenance-led line below a featured product title. |
| company stories | story-body | Helvetica Neue LT Pro | 400 | 16px | 1.35 | normal | Longer explanatory chapters. |

**Notes:**

- Reserve the widest, heaviest uppercase face for the opening campaign; narrative statements use the compact display family instead.
- Bold sans labels and large display statements share -0.03em tracking, while regular paragraphs remain normally tracked.
- The serif is an editorial counterpoint, not the default paragraph font. Sentence case is normal for commerce and chapter headings.

## Layout

**Density:** Comfortable photographic panels surround compact commerce metadata; 64px section breathing room contrasts with 8px and 12px detail gaps.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-statement and swatch gaps. |
| 12px | Product metadata padding and media-to-name separation. |
| 16px | Editorial card text inset from media and story title-to-body spacing. |
| 24px | Grid gaps and heading-to-grid separation. |
| 40px | Grid row separation for editorial cards and grid-to-action spacing. |
| 64px | Main desktop side gutters, section padding and narrative panel copy insets. |
| 128px | Deep opening space before a standalone story quotation. |

### Containers and grids

- **page-width**: max width 1440px · side padding 64px. Centered desktop wrapper yields 1312px of usable width.
- **merchandise-grid**: 4 columns · gap 24px. Equal portrait merchandise columns, each 310px wide at the desktop width.
- **editorial-grid**: 3 columns · gap 24px. Three 421px cards, with 40px between rows.
- **split-panel**: 2 columns · gap 0px. Equal copy and photographic halves inside the inset rounded panel.
- **quote-measure**: max width 571px. Centered multi-line press quotation; narrative support uses a comparable 570px measure.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 4px |
|  | product-media | 8px |
|  | banners | 12px |
|  | swatches | 50% |
| company stories | process-panel | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| outline-action | `inset 0px 0px 0px 2px #321e1e` | Secondary action edge, not an elevation shadow. |
| selected-swatch | `inset 0px 0px 0px 1.5px #321e1e` | Selected material circle. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default page background.

**CSS:** `background-color: #f4f1e0; color: #321e1e`

**Observed:** Continuous warm ground between sections.

**Transfer:** Let photography and typography supply most of the visual activity.

#### Oat media · level 1

**Use:** Merchandise media and directory opening backing.

**CSS:** `background-color: #e5e0ca; border-radius: 8px; overflow: hidden`

**Observed:** Product cards round only the media box; directory panels use 12px corners.

**Transfer:** Keep supporting names and prices on the surrounding cream ground.

#### Chocolate banner · level 1

**Use:** Large narrative split panels and featured media banners.

**CSS:** `background-color: #321e1e; color: #f4f1e0; border-radius: 12px; overflow: hidden`

**Observed:** Inset, flat and shadowless; media shares the enclosing rounded outline.

**Transfer:** Use a dark chapter to interrupt shopping density.

#### Photo veil

**Use:** Light tonal support behind opening text.

**CSS:** `background-image: linear-gradient(rgba(50, 30, 30, 0) 0%, rgba(50, 30, 30, 0.02) 24.884%, rgba(50, 30, 30, 0.04) 48.501%, rgba(50, 30, 30, 0.05) 100%)`

**Observed:** Very subtle chocolate gradient over opening media; featured banners deepen the lower veil to 0.95 opacity.

**Transfer:** Choose dark enough media for light text; do not rely on this subtle veil to rescue a busy light image.

#### Process panel

**Only for:** company stories

**Use:** Text and process-photo carousel.

**CSS:** `background-color: #e5e0ca; border-radius: 24px; overflow: hidden`

**Observed:** A 580px-tall split panel with 80px copy padding and a 16px internal gap.

**Transfer:** Use for a longer craft or development explanation.

## Components

### Sticky navigation

**Use:** Persistent shopping and editorial navigation.

**CSS:** `position: sticky; top: 0px; z-index: 100; height: 80px; background-color: #f4f1e0; color: #321e1e`

**Text style:** `navigation` — Helvetica Neue LT Pro 700 · 14px/1.35 · tracking -0.03em

**Observed:** Logo left, navigation across the middle, search and cart at the right; navigation links have 40px hit heights and 40px gaps.

**States:** Declared: hover retains chocolate text; focus-visible uses a blue outline on header links.

### Primary button

**Use:** Main action on the photographic opening.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; width: 240px; height: 48px; padding: 12px 16px; border-radius: 4px; background-color: #e5e0ca; color: #321e1e`

**Text style:** `action` — Helvetica Neue LT Pro 700 · 16px/1.35 · tracking -0.03em

**Observed:** Centered label followed by a 24px arrow icon. A cream fill serves dark narrative panels; mint fill belongs to featured campaigns. The interaction outline uses an outward pseudo-element with a 3px chocolate border and 7px corners.

**States:** Declared: focus-visible outline 2px solid chocolate, offset 4px, with a 3px cream ring and blue half-opacity glow.

### Outline button

**Use:** A centered browse-more action beneath grids.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; width: 240px; height: 48px; padding: 12px 16px; border-radius: 4px; color: #321e1e; background-color: transparent; box-shadow: inset 0px 0px 0px 2px #321e1e`

**Text style:** `action` — Helvetica Neue LT Pro 700 · 16px/1.35 · tracking -0.03em

**Observed:** Uses the same label-and-arrow construction as Primary button; the compact story variant is 186px × 40px.

**States:** Declared: hover background chocolate and text cream; focus-visible outline 2px chocolate, offset 4px, cream ring and blue glow.

### Product card

**Use:** Repeated merchandise presentation.

**CSS:** `display: flex; flex-direction: column; width: 310px; color: #321e1e`

**Text style:** `strong-label` — Helvetica Neue LT Pro 700 · 18px/1.35 · tracking -0.03em

**Observed:** A 310px × 388px Oat media box precedes an unboxed name, Price treatment, ratings and Material swatches. Information has 12px vertical padding; the name has a 264px maximum measure. Status badge sits 12px inside the upper-left media corner.

**Transfer:** Use stable media proportions even when products vary in size.

### Status badge

**Use:** Short product status over media.

**CSS:** `position: absolute; background-color: #baa7a7; color: #321e1e; border-radius: 2.8px; padding: 2.9px 8.5px 2.2px 10px`

**Text style:** `badge` — New Spirit 500 · 12px/1.8 · tracking -0.03em

**Observed:** Small serif text on a muted tab, rather than a loud uppercase sales pill.

### Price treatment

**Use:** Compact prices immediately beneath product names.

**CSS:** `display: flex; align-items: center; gap: 1px; color: #321e1e`

**Text style:** `price` — Helvetica Neue LT Pro 400 · 18px/1.35 · tracking -0.03em

**Observed:** Main integer digits are 18px; dollar sign is 12px and cents are 11.6px. Optional starting-price text precedes the number rather than becoming a separate badge.

### Material swatches

**Use:** Product variant choices beneath pricing.

**CSS:** `width: 24px; height: 24px; border-radius: 50%; background-size: cover; box-shadow: inset 0px 0px 0px 1.5px #321e1e`

**Observed:** Image-backed circles sit in an 8px-gap row; unselected circles use a lighter 1px inset edge. An overflow count follows when needed.

**Transfer:** Show the actual material or finish rather than generic brand-colored dots.

### Editorial card

**Use:** Partnerships, projects or related collections.

**CSS:** `display: flex; flex-direction: column; background-color: #f4f1e0; border-radius: 4px; overflow: hidden`

**Text style:** `card-heading` — Helvetica Neue LT Pro 700 · 21px/1.25 · tracking -0.03em

**Observed:** Landscape 421px × 281px image, then a 16px top inset, bold title, short 14px description and compact action with arrow. No boxed shadow surrounds the text.

**Transfer:** Give every card a concrete visual subject and a short reason to explore it.

### Newsletter field

**Use:** Footer email subscription.

**CSS:** `display: flex; position: relative; width: 340px; height: 41px; border-bottom: 2px solid #e5e0ca; color: #e5e0ca; background-color: transparent`

**Text style:** `caption` — Helvetica Neue LT Pro 400 · 14px/1.35

**Observed:** Underlined field with a right-edge arrow submit button; a bold invitation above and small privacy line below.

### Closing footer

**Use:** Utility navigation and monumental brand sign-off.

**CSS:** `background-color: #321e1e; color: #e5e0ca; border-top: 1px solid #e5e0ca`

**Text style:** `caption` — Helvetica Neue LT Pro 400 · 14px/1.35

**Observed:** A 719px-tall closing region: newsletter on the left, four compact link groups on the right, followed by lower utility content and full-width vector wordmark. Body begins with 64px top padding; link columns have 121px gaps.

**Transfer:** Keep the large wordmark separate from the utility grid so the ending feels like a graphic composition.

## Imagery and graphics

### Domestic product photography

**Use:** Opening media and narrative photography.

**Observed:** Photography carries a richly furnished, tactile domestic mood. Warm amber illumination, dark wood, golden upholstery, red patterned carpet and glossy objects create depth and saturated local color, while page furniture stays neutral.

**Transfer:** Stage the new product in a believable lived-in setting with wood, fabric and warm practical light. Minimum equivalent: a carefully art-directed still life with one warm lamp, one tactile support and a dark background, filling the rounded media panel.

### Merchandise portraits

**Use:** Product grids.

**Observed:** Tall 310px × 388px media areas with oat backing keep varied objects on a consistent visual stage; text occupies much less area than the product image.

**Transfer:** Photograph the whole object with room around its silhouette. Use matching camera height and a warm neutral backing across a collection; preserve authentic material color.

### Narrative portraits

**Use:** Human-authored narrative panels.

**Observed:** A seated group portrait fills one half of a chocolate split banner; copy occupies the opposite half. The portrait uses the full height rather than a small circular avatar.

**Transfer:** Show makers or users in the environment where the product belongs, using an intimate editorial photograph rather than a corporate headshot.

### Monumental wordmark

**Use:** The graphic closing device.

**Observed:** A vector wordmark spans the full 1440px width in a 246px-tall strip at the foot of the chocolate region.

**Transfer:** Render the new name as an oversized, edge-to-edge cream or oat wordmark. If no custom artwork exists, use a tightly fitted heavy or compact display treatment as live text.

**Build:** Use an SVG viewBox with a wide, shallow aspect ratio of 1440 to 246. Fit the new name across its width in oat, preserve letter proportions, remove surrounding illustration and align the graphic to the footer's bottom edge.

### Social image ribbon

**Use:** Lived-with-product proof near the ending.

**Observed:** Off-edge horizontal track of 240px × 300px photographs, separated by 24px, with 36px vertical padding on the default marketing layout; the story variant uses 64px.

**Transfer:** Mix product use, detail and setting photographs in a continuous portrait ribbon instead of embedding full social interface chrome.

### Featured object banner

**Only for:** featured product campaigns

**Use:** A large pause between commerce blocks.

**Observed:** A 1312px × 510px image-backed banner carries a centered 128px mint title. One subject is a divided box of green, orange and pink cones; another campaign centers an authored collection. Mint borders and paired horizontal rules frame the action.

**Transfer:** Use a close, material-rich arrangement of the featured product with open space for the title; keep the accent concentrated in lettering and rules.

**Build:** Place cover-fit media inside a 12px rounded chocolate container. Add a downward chocolate alpha gradient from 0 to 0.95, a 2px mint inset outline, then centered title and support. Draw paired mint bars 4px and 2px high with a 4px gap beside the centered mint action.

### Icons

**Observed:** Chocolate utility glyphs use simple silhouettes and fine outline work: 24px search at 1.3px stroke, 20px header icons at 1.5px stroke, 24px button arrows and 28px carousel arrows. Small stars sit with product ratings.

**Transfer:** Keep utility marks monochrome, small and subordinate to photographic objects; use arrows to make rectangular actions feel directional.

## Section recipes

How recurring sections are built.

### First screen: Cinematic inset opening

**Observed:** An 80px Sticky navigation precedes a 1312px × 620px rounded media stage within the page-width wrapper. Back-to-front layers are image or video, Photo veil, then bottom-centered text and Primary button. The campaign headline uses campaign-headline, centered within a 984px measure and wrapping into two emphatic lines; an 18px support line follows. The action sits below the copy, with 64px breathing room to the stage's bottom. The full stage, headline, support and action fit within the first 900px, followed by 64px space and the upper portion of a portrait category row; the rest of that row continues below the fold.

**Transfer:** Make the media the proposition: show the new product inhabiting a vivid, warm setting, using a strong still life if video is unavailable. Retain the lower-centered copy and sign-like action. Directory pages instead open with the compact Oat media title panel; company stories open with a shorter full-image narrative banner.

**Avoid:** Do not replace the media-led opening with an abstract gradient, a left-aligned software pitch or an enormous text block that pushes the object below the fold.

**Text style:** `campaign-headline` — eurostile-extended 900 · 50.8px/0.9 · tracking -0.05em · uppercase

### Portrait category rail

**Observed:** A horizontal row of 310px × 388px category images with 24px gaps extends beyond the right edge; bold short labels sit beneath. A slim 2px chocolate scroll indicator supports browsing.

**Transfer:** Group the new offering into visually recognizable families; keep the rail image-first rather than adding descriptive paragraphs.

### Chocolate split statement

**Observed:** Chocolate banner spans the inset content width, with equal photo and copy halves. Copy uses 64px horizontal insets, strong-label eyebrow, an 8px gap to statement, then 24px to body copy. A light Primary button sits below the prose.

**Transfer:** Use for a belief, product premise or human origin story; keep the statement brief enough to become a compact typographic shape.

**Text style:** `statement` — Houseplant 400 · 128px/0.9 · tracking -0.03em

### Merchandise showcase

**Observed:** A section-heading leads Product card grids by 24px. Four equal columns use 24px gaps; a centered Outline button follows the grid by 40px. One or two rows work as curated marketing showcases; catalog pages repeat the same system more extensively.

**Transfer:** Show a tightly selected group on landing pages; let a directory carry the full inventory.

**Text style:** `section-heading` — Houseplant 400 · 44px/1

### Editorial collection grid

**Observed:** Three Editorial cards per row, with 24px column and 40px row gaps. The section-heading sits 24px above; landing-page excerpts end with a centered Outline button.

**Transfer:** Use the format for collaborations, projects, applications or complementary product families.

**Text style:** `section-heading` — Houseplant 400 · 44px/1

### Press pause

**Observed:** A centered logo carousel and arrows sit above a serif quotation, with 64px between the logo row and quote stage. Quote measure is 571px, type 32px/1.25, and the section has 64px top and bottom padding.

**Transfer:** Use a genuine concise external assessment; maintain the typographic pause rather than turning it into testimonial cards.

**Text style:** `quote` — New Spirit 500 · 32px/1.25 · tracking -0.03em

### Graphic closing

**Observed:** Social image ribbon or a final merchandise showcase hands off to Closing footer. Newsletter and compact link columns occupy its upper part; the monumental wordmark occupies its own full-width lower strip.

**Transfer:** Close with practical routes and a visually memorable name, not another copy-heavy sales hero.

### Directory opening

**Only for:** catalog and collection directories

**Observed:** A 1312px × 310px oat panel with 12px corners pairs breadcrumbs and a 48px bold sans title on the left with product or collection imagery on the right. Copy has 40px horizontal and 64px vertical inset. The grid starts after 64px; catalog controls occupy a compact filter/sort row above it.

**Transfer:** Use a functional title and visually summarize the range; do not promote this compact opening to the default launch composition.

**Text style:** `directory-title` — Helvetica Neue LT Pro 700 · 48px/0.9 · tracking -0.03em

### Personal narrative and process

**Only for:** company stories

**Observed:** A 465px image banner opens with a 48px title and short support line. A standalone 32px serif quotation follows with 128px top space. A chocolate letter panel uses letter-heading and 18px paragraphs beside a tall portrait; subsequent split chapters use story-heading, 16px prose and a compact outline action. Process panel adds a 2px underlined subheading and slim 40px × 4px slide indicators.

**Transfer:** Use an authored voice and concrete making details, alternating intimate narrative and useful process explanations rather than a list of corporate values.

**Text style:** `story-heading` — New Spirit 500 · 32px/1.25 · tracking -0.02em

## Page flow

**Storyline:** Atmospheric promise → browsable objects → point of view → curated offering → external or lived-use proof → utility and graphic sign-off.

### A personality-led marketing and shopping landing page

1. **Promise** — Cinematic inset opening and portrait category rail.
2. **Point of view** — Chocolate split statement with human photography.
3. **Product demonstration** — Curated merchandise grid and featured object banner.
4. **Breadth** — Editorial collection cards.
5. **Social proof** — Press pause and social image ribbon.
6. **Closing** — Newsletter, utility navigation and monumental wordmark.

**Transfer:** Balance emotional context with shoppable proof; adapt the order and number of blocks to the new product.

### A visual directory of related projects or partnerships

1. **Orientation** — Compact oat title panel with breadcrumbs and explanatory line.
2. **Breadth** — Three-column editorial collection grid across multiple rows.
3. **Context** — Chocolate split narrative panel.
4. **Conversion** — Curated product row.
5. **Closing** — Shared dark utility footer and wordmark.

**Transfer:** Let the directory supply variety, then reconnect it to a coherent product point of view.

### A complete merchandise catalog

1. **Orientation** — Compact oat title panel.
2. **Selection** — Filter and sort controls followed by a long four-column product grid.
3. **Editorial return** — Featured authored-collection banner.
4. **Social proof** — Press quote and portrait social ribbon.
5. **Closing** — Shared newsletter and graphic footer.

**Transfer:** Scope high inventory density to browsing destinations rather than marketing launches.

### An authored company or product origin narrative

1. **Introduction** — Image-backed title and short statement.
2. **Point of view** — Standalone serif quote.
3. **Human origin** — Personal letter beside a large portrait.
4. **Capability chapters** — Alternating split media and process panel.
5. **Conversion** — Short merchandise showcase.
6. **Lived-use proof** — Social image ribbon.
7. **Closing** — Shared dark footer and full-width wordmark.

**Transfer:** Make a different product's motivation and development tangible; use the chapter structure without importing the original subject matter.

## Writing

Design-literate but cheerfully unpretentious. Confidence comes from loving and using the objects, with casual jokes and tactile specifics rather than formal luxury language.

**Do not copy:** Do not reuse Houseplant names, logos, founder identities, product names, celebrity associations, press endorsements, quotations or factual claims. Source examples illustrate rhythm only; write original claims supported by the new product.

- **Addressing the reader:** Conversational we and you; first-person singular works in a signed personal letter. Products are described as useful things in people's actual homes.
- **Rhythm:** Headlines are short and memorable, often a twist on familiar language. Support is usually one sentence; narrative paragraphs can run longer and finish with a dry joke. Actions stay direct and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An irreverent contrast that frames a desirable way of living. | 5–9 words | “The lowest form of high living.” |
| Supporting line | A small scene or emotional premise, followed by a plain-spoken payoff. | 10–18 words | “Every good memory down here needed a room first. We just furnished it.” |
| Section statement | Blunt, everyday words made monumental through type. | 3–6 words | “WE LIKE NICE THINGS” |
| Primary action | Verb plus specific destination or product family. | 2–5 words | “Shop Furniture”<br>“How We Got Here” |
| Directory support | A conversational summary with a little repetition or self-aware humor. | 12–20 words | “A collection of all the cool things we’ve done with our very cool friends.” |

**Words and phrasing to use:** nice things; thoughtful; beautiful; crafted; your living room; we made; friends

**Avoid:** disruptive ecosystem; unparalleled excellence; elevate your journey; exclusive luxury lifestyle; synergistic

**Rules:**

- Connect good design to a specific everyday use rather than abstract aspiration.
- Let the image show material quality; use copy to explain why the object exists.
- A restrained swear or joke can puncture self-importance in long editorial prose; do not force it into every label.
- Keep shopping labels descriptive even when campaign language is playful.

## Do's and Don'ts

### Do

- Preserve 64px desktop gutters around large rounded media panels.
- Use 44px compact display headings above grids, not the campaign font everywhere.
- Keep merchandise imagery at the 310px × 388px portrait proportion.
- Retain 24px column gaps in both product and editorial grids.
- Use 4px action corners and the measured 48px action height.
- Concentrate mint in a featured campaign's title, action and paired rules.
- Give the closing wordmark a full-width strip rather than fitting it inside a utility column.

### Don't

- Do not substitute pure black and white for chocolate and warm cream.
- Do not add floating drop-shadow cards to flat merchandise grids.
- Do not turn the small serif status tabs into bright uppercase sales stickers.
- Do not use circular profile photos in place of the half-panel narrative portrait.
- Do not make navigation widely tracked capitals; its 14px bold labels use -0.03em.
- Do not wrap product names and prices inside the oat media backing.
- Do not use the 128px statement recipe for ordinary card titles.

## Motion and responsive

### Motion

**Observed:**

- Social image ribbons declare an 80s linear infinite horizontal animation.
- Outline actions declare background-color and color transitions of 0.28s cubic-bezier(.33, 1, .68, 1).
- Swatch inset edges declare box-shadow transitions of 0.2s cubic-bezier(.33, 1, .68, 1); navigation color uses 0.25s ease.

**Transfer:**

- Keep the social ribbon a slow continuous photographic drift; keep product choices and actions brisk rather than theatrical.

**Unknown:**

- Hero video sequence, carousel autoplay timing and scroll-trigger behavior are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 750px, 990px, 1120px and 1280px.
- Desktop wrapper is capped at 1440px with 64px side padding. A 12px page-gutter token is declared.

**Transfer:**

- For narrow layouts, prioritize the media-led opening and its lower-centered action; shorten copy before shrinking it excessively.
- Stack narrative halves and reduce grid columns while retaining portrait media ratios and the separation between media and metadata. Treat this as adaptation guidance.
- Keep the closing name full-width and the social ribbon horizontal rather than compressing them into small thumbnails.

**Unknown:**

- Exact mobile columns, gutter switches, font scaling and navigation replacement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
