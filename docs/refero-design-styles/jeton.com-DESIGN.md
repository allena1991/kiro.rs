# Jeton — sculpted red momentum

## Overview

An exuberant, red-led style that makes everyday software feel physical and immediate. White and tomato-red expanses alternate with soft monochrome sculptures, oversized grotesk type, tactile product scenes and warm, candid photography. It suits consumer technology and approachable services: spacious and theatrical in its storytelling, compact and practical when presenting details.

### Essentials

- Make a low-slung, split-screen promise rather than a conventional centered hero: a 105.8px/1, weight-500 white headline occupies the lower left, while a 23px support line and compact actions sit in the right third of a 930px red stage.
- Treat red as architecture, not a small highlight: #f73b20 fills the opening and selected full-width demonstration chapters, while white carries the intervening explanations and footer. On white, major headings and actions stay red; reserve #360802 for dense information.
- Make simple objects feel sculptural: stage a softly lit red disc or product silhouette against tonal red planes, with rounded edges, shallow relief and a restrained highlight. A CSS-built beveled disc is the minimum equivalent when no product render exists.
- Separate action shapes by job: conversion controls are 48px high with 12px corners and 24px horizontal padding; the persistent bottom navigation is a 371px-wide, 48px-high capsule with 14px labels.
- Let the type become an event: ordinary section leads are 72px/1 with 0.01em tracking, while the monumental invitation reaches 155.4px/0.9. Include an oversized invitation or proof statement rather than shrinking every message into cards.
- Close with a graphic identity, not only utility links: use five light footer columns, a nearly full-width red wordmark artwork, then two wide photographic proof panels with bottom color fades. If there are no partner images, use original customer or product-context photographs with small factual captions.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tomato red | `#f73b20` | `--color-brand` | background, text, action, link, accent | Dominant opening and demonstration fill; headings, controls and links on white. |
| Lighter navigation red | `#f84d35` | `--color-dock` | surface | Floating navigation capsule, with a 10% white overlay. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft red wash | `#fff5f4` | `--color-blush` | surface | Visible 5% brand red over white; feature-card and field backing, using rgba(247,59,32,0.05). |
| Photographic wine fade | `#7a2739` | `--color-wine` | background | Bottom fade on photographic proof panels, not a general text color. |
| Sculpture backing | `#6b3843` | `--color-plum` | background | Backing for the dimensional device scene; accompanies muted plum, peach and teal materials within the artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, text, surface | Main reading canvas, reverse type and solid reverse buttons. |
| Outer neutral | `#f6f6f6` | `--color-underlay` | background | Underlying document neutral; the visible reading page remains white. |
| Oxblood ink | `#360802` | `--color-ink` | text, border | Dense explanatory text and table rules; warmer than black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| filterable information pages | Selection track blush | `#fee9e6` | `--color-filter-wash` | surface, border | Visible 10% brand red over white in switcher tracks; also the fine outline on white editorial badges. |

## Typography

- **Sequel Sans** — All marketing text, navigation and controls. Open, contemporary grotesk with a generous x-height and rounded bowls; medium display cuts and a lighter book text weight. If unavailable, use **Inter**. Use 450 for book text and 500 for headings; retain the open spacing of small text. Font stack: "Sequel Sans", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| invitation | Sequel Sans | 500 | 155.4px | 0.9 | normal | size clamp(56px, 19.1px + 9.47vw, 180px) | Monumental centered proof or invitation, usually two lines. |
| statement | Sequel Sans | 500 | 110.4px | 1 | normal | size clamp(72px, 57.7px + 3.66vw, 120px) | Centered, short unifying statement; a transform can enlarge it within a scroll scene. |
| display | Sequel Sans | 500 | 105.8px | 1 | normal | fixed | Two-line opening promise, white against red. |
| heading-lg | Sequel Sans | 500 | 72px | 1 | 0.01em | size clamp(40px, 28.1px + 3.05vw, 80px) | Major chapter headings and demonstration titles. |
| heading | Sequel Sans | 500 | 43.8px | 1.2 | 0.01em | size clamp(27px, 20.8px + 1.6vw, 48px) | Longer benefit statements, heading pairs and editorial section titles. |
| lead | Sequel Sans | 500 | 23px | 1.2 | 0.01em | size clamp(19px, 17.5px + 0.38vw, 24px) | Support lines, feature-card titles and prominent explanatory copy. |
| body | Sequel Sans | 450 | 16px | 1.5 | 0.03em | fixed | Paragraphs, ordinary text links and dense information. |
| button | Sequel Sans | 450 | 16px | 1.25 | 0.03em | fixed | Conversion and account controls. |
| small | Sequel Sans | 450 | 14px | 1.4 | 0.03em | fixed | Dock navigation, compact descriptions and editorial badges. |
| eyebrow | Sequel Sans | 400 | 14px | 1.4 | 0.03em | fixed | Outlined section tags and segmented-filter labels. |
| caption | Sequel Sans | 400 | 12px | 1.5 | 0.03em | fixed | Tiny scroll cue. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| structured information and instructional pages | subheading | Sequel Sans | 500 | 33.4px | 1.2 | 0.01em | size clamp(23px, 19.1px + 0.99vw, 36px) | Filter question headings and accordion row titles. |
| update listings | editorial-title | Sequel Sans | 500 | 19.6px | 1.2 | 0.01em | size clamp(18px, 17.4px + 0.15vw, 20px) | Short multi-line titles below thumbnails. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines use medium weight rather than heavy bold. The largest display roles have normal tracking; ordinary headings and leads use 0.01em, while small text opens to 0.03em.
- Keep words in sentence case and make deliberate two-line silhouettes. The oversized identity at the footer is vector artwork, not another body-font heading.
- The unifying statement uses a scale(2) enlargement in its scroll composition; preserve room for the enlarged words rather than treating its font size as its final visual width.

## Layout

**Density:** Airy theatrical chapters around compact utility controls; large media fields and viewport-sized pauses contrast with tightly grouped navigation and data.

### Spacing

| Value | Use |
| --- | --- |
| 2px | Inset and gaps inside segmented controls and the dock. |
| 8px | Icon-label separation, compact title-to-description gaps and gaps between review cards. |
| 16px | Section tag to heading; review-card padding and attribution separation. |
| 20.1px | Common desktop inter-card and grid gutter. |
| 24px | Button horizontal padding and horizontal marketplace-badge gap. |
| 30.4px | Top navigation vertical padding and roomy filter-row padding. |
| 56px | Monumental invitation to supporting line. |
| 108.8px | Vertical padding around the editorial listing and lower photographic chapters. |
| 156.9px | Large separation around an overview chapter. |
| 200.9px | Top and bottom breathing room around the monumental invitation. |

### Containers and grids

- **desktop-content**: max width 1337px · side padding 51px. Wide content, footer and visual grids at a 1440px viewport. The underlying row uses 41.2px side padding plus about 10px inner column gutters.
- **footer-columns**: 5 columns · gap 21.7px. Equal-width utility groups across the wide container.
- **focused-information** (only for structured information pages): max width 828px. Centered tables and focused explanatory content, leaving substantial outer white space.
- **editorial-grid** (only for update listings): 3 columns · gap 20.1px. Three approximately 319px-wide update cards, left aligned; the featured opening can give one card double width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | conversion-controls | 12px |
|  | review-cards | 16px |
|  | dock | 112px |
|  | section-tag | 9999px (pill) |
|  | proof-panels | 19.3px |
| filterable information pages | inset-information-sheet | 36.1px |
| product feature showcases | feature-media-card | 22.4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| review-lift | `0px -4px 16px 0px rgba(0, 0, 0, 0.05)` | Very light lift on translucent reviews; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Explanations, ordinary chapters and footer.

**CSS:** `background: #ffffff; color: #f73b20`

**Observed:** White is the actual visible reading plane, not the slightly gray outer document.

**Transfer:** Use clean white space to make the next red chapter feel decisive.

#### Red stage · level 0

**Use:** Opening and immersive demonstration chapters.

**CSS:** `background: #f73b20; color: #ffffff; overflow: hidden`

**Observed:** Runs edge to edge without a card border; dimensional media may cover the flat color.

**Transfer:** Keep a full-bleed red field behind white copy and tonal product art.

#### Review glass · level 1

**Use:** Readable proof over a full-width photograph.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 16px; backdrop-filter: blur(40px); box-shadow: 0px -4px 16px 0px rgba(0, 0, 0, 0.05)`

**Observed:** The underlying scene supplies the dark gray-brown tint; text is white and supporting text is softer.

**Transfer:** Choose a photograph with a sufficiently dark central area; do not turn the glass into an opaque gray card.

#### Proof fade · level 1

**Use:** Bottom legibility on photographic proof panels.

**CSS:** `background: linear-gradient(rgba(122, 39, 57, 0) 15%, #7a2739 69%)`

**Observed:** One panel ends in wine; its companion ends in brand red. White attribution sits near the bottom.

**Transfer:** Fade the lower portion of an authentic scene into a solid brand-related color, leaving the top recognizably photographic.

#### Inset white sheet · level 1

**Only for:** filterable information pages

**Use:** Long tables and update archives on a red outer band.

**CSS:** `background: #ffffff; border-radius: 36.1px`

**Observed:** Approximately 10px of red remains visible on either side; the sheet is broad and uninterrupted, not a stack of separate cards.

**Transfer:** Give complex information one shared rounded white plane.

#### Blush media card · level 1

**Only for:** product feature showcases

**Use:** Floating photo-and-benefit cards.

**CSS:** `background: rgba(247, 59, 32, 0.05); border-radius: 22.4px; padding: 8.8px; backdrop-filter: blur(10px)`

**Observed:** An approximately square photograph occupies most of the card above red title and short text.

**Transfer:** Place sparse, staggered media cards around a central message.

## Components

### Floating dock

**Use:** Persistent primary navigation across long pages.

**CSS:** `display: flex; align-items: center; gap: 2px; padding: 0px 2px; width: 371px; height: 48px; border-radius: 112px; background: #f84d35; color: #ffffff`

**Text style:** `small` — Sequel Sans 450 · 14px/1.4 · tracking 0.03em

**Observed:** Centered near the bottom of the viewport with 28.8px clearance. A home icon begins the capsule, followed by three compact navigation destinations, some with chevrons. A translucent white layer and a lighter selected segment supply depth.

**Transfer:** Keep only a few high-level destinations in the dock; account and locale controls belong at the top.

### Primary button

**Use:** Main conversion and account action on a red or photographic stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 0px 24px; border-radius: 12px; background: #ffffff; color: #f73b20`

**Text style:** `button` — Sequel Sans 450 · 16px/1.25 · tracking 0.03em

**Observed:** A compact rounded rectangle, sometimes with a down chevron for account menus. On white, the product-action version reverses to red fill and white text; the adjacent secondary account action is translucent rather than equally solid.

**Transfer:** Use one solid conversion action; retain the rectangular silhouette rather than turning it into a pill.

### Text link

**Use:** Footer destinations and light navigation actions.

**CSS:** `display: inline-flex; padding: 4px 0px; color: #f73b20`

**Text style:** `body` — Sequel Sans 450 · 16px/1.5 · tracking 0.03em

**Observed:** No enclosing shape. Footer group headings are lighter than the links below, and columns stay visually spare.

**States:** Declared: hover opacity 0.8; focus-visible unknown; active outline 0px.

**Transfer:** Use as the quiet alternative to the solid action.

### Marketplace badge

**Use:** App acquisition beside hero support and in the closing invitation or footer.

**CSS:** `display: inline-flex; width: 148px; height: 44px; border-radius: 12px; backdrop-filter: blur(20px)`

**Observed:** Official marketplace artwork supplies the mark and two-level label. Thin white artwork and outlines appear on red or media; red artwork appears on white. Hero badges stack vertically, while invitation and footer badges form a horizontal pair.

**Transfer:** For products without an app, use an equally compact pair of genuine acquisition or platform links rather than imitating marketplace logos.

### Scroll cue

**Use:** Small bottom-left hint on full-height openings.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 60px; padding: 4.8px 10.2px; height: 30px; color: #ffffff`

**Text style:** `caption` — Sequel Sans 400 · 12px/1.5 · tracking 0.03em

**Observed:** Tiny pointer-like glyph precedes the text; it remains subordinate to the bottom dock.

**States:** Declared: hover background rgba(255,255,255,0.2); focus-visible box-shadow 0px 0px 0px 1px #ffffff, 0px 0px 0px 3px rgba(255,255,255,0.5); active background rgba(255,255,255,0.25).

### Review card

**Use:** Customer proof layered over contextual photography.

**CSS:** `width: 489px; padding: 16px; border-radius: 16px; background: rgba(255, 255, 255, 0.1); backdrop-filter: blur(40px); box-shadow: 0px -4px 16px 0px rgba(0, 0, 0, 0.05); color: #ffffff`

**Text style:** `body` — Sequel Sans 450 · 16px/1.5 · tracking 0.03em

**Observed:** Short review title, softer quote, then a circular initials avatar and name. Cards stack with smaller receding layers; the front card establishes the readable width.

**Transfer:** Use real short quotes and modest pastel identity circles; keep the photography visible around the stack.

### Outline section tag

**Use:** Small subject marker above a chapter heading.

**CSS:** `display: inline-block; padding: 4px 12px; border: 1px solid #f73b20; border-radius: 9999px; color: #f73b20`

**Text style:** `eyebrow` — Sequel Sans 400 · 14px/1.4 · tracking 0.03em

**Observed:** A delicate capsule outline, sentence case, followed by a 16px gap to the heading.

**Transfer:** Use a one- or two-word topic, not an uppercase eyebrow sentence.

### Segmented filter

**Only for:** filterable information pages

**Use:** Choose a category, operation or region.

**CSS:** `display: flex; align-items: center; padding: 2px; height: 48px; background: rgba(247, 59, 32, 0.1); border-radius: 98px; color: #f73b20`

**Text style:** `eyebrow` — Sequel Sans 400 · 14px/1.4 · tracking 0.03em

**Observed:** Active label is a solid red capsule with white type, 44px high and 16px horizontal padding. Remaining choices sit directly on the blush track. Long category tracks scroll horizontally.

**Transfer:** Use short mutually exclusive options and keep the active contrast unambiguous.

### Editorial badge

**Only for:** update listings

**Use:** Category marker over a thumbnail.

**CSS:** `position: absolute; padding: 6px 16px; border-radius: 32px; background: #ffffff; outline: 1px solid #fee9e6; color: #360802`

**Text style:** `small` — Sequel Sans 450 · 14px/1.4 · tracking 0.03em

**Observed:** Pinned to the upper-right corner of the image, inset from its edge; the white capsule is separate from the photo.

**Transfer:** Keep categories short and reserve the picture for the actual change or use case.

### Information row

**Only for:** structured information pages

**Use:** Comparable limits or specifications.

**CSS:** `border-bottom: 1px solid #360802; color: #360802; height: 57px`

**Text style:** `body` — Sequel Sans 450 · 16px/1.5 · tracking 0.03em

**Observed:** Two columns across an 828px table: descriptive label on the left, value on the right. Cells have 16px vertical padding; section headers use the lead recipe with additional separation.

**Transfer:** Group related facts under readable subheads instead of boxing each row.

### Update card

**Only for:** update listings

**Use:** Editorial entries in featured and archive grids.

**CSS:** `display: block; width: 319px; color: #360802`

**Text style:** `editorial-title` — Sequel Sans 500 · 19.6px/1.2 · tracking 0.01em

**Observed:** A 319px by 185px image with rounded corners, category badge, title about 17px below, short muted description 8px later and a date beneath. There is no heavy enclosing card surface. In the opening, copy reverses to white and a featured image doubles in width.

**Transfer:** Use a real product change or user-context image with a specific outcome headline.

## Imagery and graphics

### Tonal red sculpture

**Use:** Signature opening media and product-overview stage.

**Observed:** The opening shows a shallow circular disc near the upper center-right in a softly mottled red field. The product variant shows a tilted rounded card among large cylindrical red podiums. All materials remain red, with salmon highlights and darker red edges; text is overlaid, not baked into the scene.

**Transfer:** Create one simple product-related silhouette in the same material as its backdrop. Use a beveled disc when there is no recognizable physical object.

**Build:** Create a full-bleed #f73b20 plane. Layer a broad white radial gradient at roughly 65% 45% at 0.12 alpha over a darker red translucent radial field. Put a roughly 320px circular element above center, use a subtle top-left highlight and a darker red lower-left inset edge, then add a second slightly offset ellipse for thickness. For a product card, use a rounded rectangle rotated about 30deg, with low-contrast inset highlights; build the podiums from broad ellipses over rectangular cylindrical sides. Keep shadows soft and close; avoid black outlines.

### Dimensional device theatre

**Use:** A major conversion or demonstration chapter.

**Observed:** A large upright phone sits to the right inside concentric sculptural rings. Teal and near-black bands contrast with peach and plum surfaces and a ribbed plum coil. The scene fills the viewport; white headline and action sit in the relatively open left area.

**Transfer:** Show a single legible product view within an oversized physical setting. Keep the supporting colors inside the scene rather than expanding them into the site's interface palette.

**Build:** Build nested wide elliptical SVG bands extending beyond the viewport, alternating plum, muted peach, dark teal and charcoal. Add a repeated array of flattened plum ellipses along the upper inner arc for the ribbed coil. Overlay an upright device frame with the new product's own interface at the right; use soft directional shading rather than neon glow. Minimum version: three layered arcs and one clean device mockup.

### Everyday contextual photography

**Use:** Proof chapters, feature cards and editorial thumbnails.

**Observed:** Warm, natural scenes show people using phones, working or paying in shops and cafés. Hands and devices are often close to camera. The proof photograph fills the whole section behind white type and glass cards; smaller feature photos are square or portrait and sometimes overlap in an editorial collage.

**Transfer:** Photograph the product's actual everyday context, with natural expressions and believable environments. Keep warm neutral lighting and compose quiet zones for copy; use close details when faces are unavailable.

### Playful object field

**Use:** An interactive or capability chapter on white.

**Observed:** Bright circular flag tokens tumble and accumulate along the lower edge around a compact central calculator. The white upper field stays mostly clear for the red heading; the objects carry color without turning the whole page multicolored.

**Transfer:** Use a family of small domain-relevant tokens or symbols, with a similar circular silhouette and varied rotation. If live interaction is unavailable, create a static arranged field that leaves the central control unobstructed.

**Build:** Make 48px–100px circular SVG tokens with clipped simple symbols, rotated independently and clustered into a loose pile along the bottom 25% of the section. Vary vertical overlap and size, with only a few isolated pieces higher up. Place the title and working control above the dense pile, not inside it.

### Monumental identity and proof pair

**Use:** Signature footer ending.

**Observed:** A red vector wordmark stretches about 1337px wide and 356px tall above fine legal lines. Beneath it are two 658px by 264px rounded photo panels: a wide venue image and a pair of people against red, both with white bottom attribution and color fades.

**Transfer:** Draw the new brand's own name as a bold, nearly full-width word sculpture. Follow with two factual proof images or original product-context images; preserve the graphic ending even when partnerships are not relevant.

**Build:** Use an SVG viewBox sized to the new wordmark's natural proportions and fit it to the wide content container in #f73b20. Place a two-column image grid underneath, gap 20.1px, corners 19.3px, overflow hidden. Overlay a transparent-to-wine gradient on one panel and transparent-to-brand-red on the other, settling to solid color near 69% height; center compact white captions near the bottom.

### Icons

**Observed:** Navigation and action icons are usually 24px solid white or red SVGs, with 16px chevrons. Instructional symbols use 24px outlines at 1.5px stroke with square ends; plus signs mark expandable rows. Social marks sit inside 32px red circles.

**Transfer:** Use simple, friendly utility symbols, match the 24px optical size and keep icon colors tied to the surrounding text. Do not mix large decorative line icons into every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Sculpted split opening

**Observed:** A 930px edge-to-edge Red stage establishes a full-height first impression. Behind the content is Tonal red sculpture: an oversized soft red plane and a shallow disc about 320px across near the upper center-right, leaving most of the middle open. A white brand mark sits at the upper left; locale and account controls align at the upper right, within roughly 51px side margins and 30.4px top padding. The display headline sits low on the left, about half the page wide, on two lines. The right third holds a short lead and two vertically stacked Marketplace badges. Within the first 900px the complete headline, support, badges, sculpture, Scroll cue and Floating dock are visible; the following white statement chapter falls below the fold.

**Transfer:** Use the same low-left promise and right-side support for a new product. Replace the disc with a similarly restrained product silhouette, or build the beveled-disc fallback. Structured information pages use this split red opening with a portrait-oriented contextual photo above the right support. Update listings move the headline higher and place a featured thumbnail row within the first screen.

**Avoid:** Do not center the headline at the top, introduce a white boxed hero, or cram a large dashboard behind the copy. Do not make the hero's main action a giant pill.

**Text style:** `display` — Sequel Sans 500 · 105.8px/1

### Expanding statement and capability words

**Observed:** A white chapter centers a short red statement in the statement recipe, enlarged within a scroll stage. Small media snippets orbit its edges. Subsequent large single-word capabilities pair saturated text with rounded square symbols rather than a conventional card grid.

**Transfer:** Give the product's unifying idea a typographic pause, then break it into a few memorable verbs with small tangible visual cues.

**Text style:** `statement` — Sequel Sans 500 · 110.4px/1

### Immersive demonstration

**Observed:** A full-width Red stage centers a heading-lg title above layered product UI or a large device presentation. One demonstration uses a five-step numeric rail at the bottom-left; the scene occupies most of the viewport and does not sit inside an ordinary website card.

**Transfer:** Show one meaningful workflow with a small progress rail. Keep the details inside the product UI and the surrounding chapter visually simple.

**Text style:** `heading-lg` — Sequel Sans 500 · 72px/1 · tracking 0.01em

### Tag and benefit statement

**Observed:** Outline section tag precedes a centered heading with a 16px gap. Longer benefit copy uses the heading recipe in a narrow roughly 659px column; a large red product rendering follows after generous white space. The left-aligned variant pairs a heading-lg title with a lead and a full-bleed contextual photo below.

**Transfer:** Use short subject tags to frame one customer benefit, then let a single large piece of media prove it.

**Text style:** `heading` — Sequel Sans 500 · 43.8px/1.2 · tracking 0.01em

### Photographic review stage

**Observed:** Everyday contextual photography fills an approximately 1098px section. A white heading-lg title is centered above a central stack of Review cards. The stack occupies about one third of the viewport width, leaving the person and room visible around it.

**Transfer:** Pair human context with concise customer proof. Use real stacked cards with readable contrast rather than a logo wall or anonymous stars.

**Text style:** `heading-lg` — Sequel Sans 500 · 72px/1 · tracking 0.01em

### Monumental invitation

**Observed:** A centered invitation spans roughly 998px within an 870px-high White canvas, with 200.9px top and bottom padding. The invitation recipe forms two tight lines; a lead follows about 56px later and paired Marketplace badges another 60px below. A layered red/white color-reversal treatment supports the same message.

**Transfer:** Use a concise invitation or verified proof statement at monumental scale. When downloads are irrelevant, replace the badge pair with equally compact real conversion actions.

**Text style:** `invitation` — Sequel Sans 500 · 155.4px/0.9

### Utility footer and graphic last word

**Observed:** Five footer link columns span the wide container. A second row pairs acquisition links with credentials and 32px social circles, followed by locale and credit controls. Monumental identity and proof pair then supplies the final visual emphasis: giant red wordmark, fine regulatory text and two photographic panels. The same ending appears across the page types; the product-focused variant moves directly from instructional accordions into this footer rather than adding the monumental invitation.

**Transfer:** Keep the utility area light and the final identity emphatic. Use the new product's actual credentials and relevant photography; retain the contrast between tiny information and giant identity.

### Focused information sheet

**Only for:** structured information pages

**Observed:** Inset white sheet sits inside a red band. An 828px centered content column begins with a heading-lg title, Segmented filter and a compact three-column grid of service facts. The detailed variant follows with filter question rows, metadata and grouped Information rows under subheadings.

**Transfer:** For comparison-heavy material, keep the red shell but use oxblood text on a continuous white panel; separate groups with rules, not individual elevated cards.

**Text style:** `subheading` — Sequel Sans 500 · 33.4px/1.2 · tracking 0.01em

### Featured updates and archive

**Only for:** update listings

**Observed:** The red opening contains a high split title/support pair and a three-item featured row with one double-width image. A separate Inset white sheet carries a heading, left category switcher, right search field and three Update cards. Results and dates are small and low contrast.

**Transfer:** Give a new publishing or changelog page a bold editorial front, then a practical searchable archive. Preserve the image hierarchy and quiet text structure.

**Text style:** `editorial-title` — Sequel Sans 500 · 19.6px/1.2 · tracking 0.01em

## Page flow

**Storyline:** Promise → visual explanation → tangible product proof → capabilities or practical details → trust → invitation → utility and graphic identity.

### Broad consumer-product landing page

1. **Promise** — Low split white headline and acquisition links over sculpted red media.
2. **Visual explanation** — Oversized unifying statement and a few large capability verbs.
3. **Product demonstration** — Red workflow stage followed by a dimensional device-and-action scene.
4. **Capability chapters** — White benefit-and-media chapter and a playful interactive object field.
5. **Social proof** — Contextual photography with stacked translucent reviews.
6. **Closing call** — Monumental invitation with compact actions.
7. **Brand ending** — Light utility columns, oversized wordmark, fine print and paired photographic proof panels.

**Transfer:** Alternate a few immersive scenes with white explanatory pauses; choose the chapters that make the new promise credible.

### Fees, comparisons or specification page

1. **Promise** — Red split opening with a human photo above the right support.
2. **Comparison** — Rounded white sheet with category controls and compact service cards.
3. **Detailed information** — Centered filter questions and long grouped two-column tables.
4. **Closing call** — Monumental invitation.
5. **Brand ending** — Shared utility footer, identity and photographic proof pair.

**Transfer:** Use the theatrical shell to make the subject approachable, but let the central document remain calm and directly comparable.

### Flagship feature or physical-product page

1. **Promise** — Tonal red product sculpture and low split headline.
2. **Product demonstration** — Red chapters with large device views and simple benefit titles.
3. **Capabilities** — Staggered blush photo cards around a central action, followed by a contextual photo collage.
4. **Use-case proof** — Tag, benefit title and full-width close-up photography.
5. **Objection handling** — Editorial explanation and device-specific instructional accordions.
6. **Brand ending** — Direct transition into utility columns and the graphic footer, without a separate monumental invitation.

**Transfer:** Move from tactile desire to practical reassurance, preserving different visual scales rather than using a uniform feature grid.

### Product news and release archive

1. **Editorial promise** — Red split title/support with a featured image row.
2. **Discovery** — Rounded white archive with categories, search and thumbnail-led cards.
3. **Closing call** — Monumental invitation.
4. **Brand ending** — Shared utility and graphic footer.

**Transfer:** Keep news scannable and image-led while retaining the same red architecture and oversized final identity.

## Writing

Direct, upbeat and reassuring, with conversational confidence rather than technical bravado. Benefits are everyday and easy to picture; practical details become plain and factual.

**Do not copy:** Do not reuse Jeton names, wordmark artwork, proprietary interface art, user counts, availability claims, fees, regulatory statements, partner identities, athlete likenesses or customer quotations. Replace all claims and examples with facts belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Name the product when useful; use we sparingly for progress and support rather than corporate self-description.
- **Rhythm:** Short two-line promises and simple benefit statements lead. Support is usually one brief sentence; detailed instructional or financial sections may use longer literal explanations. Occasional questions and clipped answers make the voice friendly.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | One immediate benefit in familiar language. | 4–7 words | “One app for all needs”<br>“Ready to use right away” |
| Support | Reassure the reader with a clear outcome or removal of friction. | 4–16 words | “Single account for all your payments.”<br>“No hidden fees, no surprises.” |
| Benefit statement | Ask a concrete capability question, then answer with a brief conversational confirmation. | Several short clauses | “Contactless payments? Sure. Spending limits? Check. Card freezing? Also check.” |
| Action | A familiar verb and immediate destination. | 1–4 words | “Get Started”<br>“Learn more” |
| Editorial title | Name the actual improvement, not a vague announcement. | 5–10 words | “Introducing the [Brand] Virtual Card” |

**Words and phrasing to use:** ready; easily; all in one; your; get started; no surprises; anywhere; faster; simple

**Avoid:** revolutionary ecosystem; disruptive paradigm; unparalleled synergy; enterprise-grade everything; excessive financial jargon

**Rules:**

- State the benefit before the mechanism.
- Use sentence case for marketing headings; reserve capitals for true document labels.
- Keep actions literal, not witty.
- Make proof precise only when it is verifiable; reassurance must not become an unsupported guarantee.
- Use conversational question-and-answer rhythm sparingly as a distinctive benefit treatment.

## Do's and Don'ts

### Do

- Keep opening type medium at 105.8px/1 and use purposeful two-line breaks.
- Use #f73b20 for full-width stages as well as text on white.
- Keep default conversion controls at 48px with 12px corners.
- Keep the 371px floating dock compact, with 14px labels and bottom clearance.
- Use 16px padding and 40px backdrop blur for photographic review cards.
- Let major chapter headings reach 72px and monumental invitations reach 155.4px.
- Give dense tables an approximately 828px content width and 1px oxblood rules.
- Preserve the giant identity artwork and paired 658px by 264px proof images at the ending.

### Don't

- Do not replace medium headlines with 700-weight, tightly tracked display text.
- Do not turn every conversion control into a 9999px pill; that shape belongs to navigation, tags and filters.
- Do not spread the teal and plum of the dimensional artwork across ordinary buttons and text.
- Do not add generic drop shadows to the white information sheet or editorial cards.
- Do not put dense paragraphs on the vivid red stage; use the white information plane.
- Do not make every image a device mockup; warm real-world photography is part of the contrast.
- Do not tint the primary reading canvas gray just because an outer neutral exists.
- Do not shrink the final identity to an ordinary footer logo or replace the photographic ending with a dark utility slab.

## Motion and responsive

### Motion

**Observed:**

- Text links declare opacity 0.3s cubic-bezier(0.2, 0, 0, 1).
- The scroll cue declares background-color 0.2s cubic-bezier(0.25, 0.46, 0.45, 0.94).
- Filter labels declare color 0.1s ease-out with 0.03s delay.
- Scroll compositions include enlarged text, staggered product cards and receding review layers; a coin-loop-orange animation is declared at 2s cubic-bezier(0.445, 0.05, 0.55, 0.95).

**Transfer:**

- Use motion to reveal physical depth and separate chapter scales, not to make every small element bounce.
- Keep the bottom dock stable while the media stages change.
- Provide a complete static sculptural composition and readable front review even without animated media.

**Unknown:**

- Exact scroll choreography, video timing and animation triggering are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 640px, 768px, 1024px and 1440px.
- The measured heading families use clamp formulas; ordinary body and action text remain 16px.

**Transfer:**

- On narrow screens, stack the support beneath the low-positioned promise and keep the tonal sculpture above or behind it without obscuring text.
- Retain the bottom capsule as a compact navigation object; reduce destination length rather than scaling labels to illegibility.
- Collapse paired proof panels and editorial grids into a reading sequence, keeping the oversized identity proportional to the available width.
- Keep dense data legible and grouped; allow horizontal overflow for filter tracks instead of squeezing every option.

**Unknown:**

- Only desktop compositions are established; exact mobile spacing, navigation transformations and media replacements are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
