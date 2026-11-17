# Partiful — flashbulbs and flyer energy

## Overview

A sociable, slightly unruly style that pairs blunt poster lettering with clean grotesk text and vivid personal imagery. Black stages and pale gray breathing spaces let flash photography, colorful interface scenes and glossy graphics provide the excitement. It suits consumer products and community-oriented tools that want to feel easy, expressive and already part of real life; compositions are spacious even when the imagery is exuberant.

### Essentials

- Poster voice, not corporate display: condensed, imperfect uppercase headlines use 108.8px/1 at the opening and 50.1px/1 in sections, both with 0.02em tracking; supporting grotesk text stays light and small.
- A human scene carries the opening: a black 946px stage pairs a two-line white promise with a 420×565px rounded portrait and floating conversation fragments; a 987×83px frosted navigation capsule hovers above it.
- Actions stay monochrome and deliberately mixed in shape: 51px-high, 4px-radius rectangular hero actions contrast with 200px-radius navigation and dark-chapter pills; labels are 16px, weight 600.
- Color belongs to the things people make: broad page fields are black, #111111, #f7f7f7 or white, while media may be densely saturated. Keep most structural space neutral; pastel page washes belong to focused acquisition and audience variants.
- Proof behaves like a lively photo album: 340×344px cards mix flash portraits, translucent review slips, a black star card and a huge 100px statistic on an electric textured ground. Include a vivid proof card using a substantiated metric or short testimonial when photography is unavailable.
- The page has a collectible-art personality: include a layered, edge-clipped parade of colorful product outputs or original graphic cards, and a monumental identity sign-off. The closing dark panel has 16px corners, 32px outer gutters and a white identity graphic spanning roughly 1310×315px; a new wordmark can serve as the graphic.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, background, surface | White display lettering on black; clean editorial and product-page fields. |
| Review paper | `#fdfdfd` | `--color-review-paper` | surface, text | Review card backing and large proof numerals. |
| Warm action white | `#fdfdfb` | `--color-warm-white` | text, action | Light button fills and footer text. |
| Warm navigation frost | `#fcfcfa` | `--color-glass` | surface | Visible pale result of warm white at 80% over the light canvas; use rgba(253,253,251,0.8) so it becomes silver on black. |
| Light gray canvas | `#f7f7f7` | `--color-canvas` | background, surface | Default light field and the halo around the oversized closing action. |
| Control gray | `#eeeeee` | `--color-control` | surface | Circular carousel controls. |
| Media gray | `#ececec` | `--color-tile` | surface, text | Neutral media stages and light supporting text on dark backgrounds. |
| Warm caption gray | `#777772` | `--color-caption` | text, link | Secondary descriptions and underlined-link hover. |
| Soft warm gray | `#5f5f5b` | `--color-support` | text | Section support lines and proof captions. |
| Body gray | `#595959` | `--color-body` | text | Default supporting text on the light field. |
| Near-black ink | `#111111` | `--color-ink` | text, background, action | Default heading ink, dark chapters, footer and dark actions. |
| Stage black | `#000000` | `--color-black` | background, text, action | Opening stage; also the base of all-dark feature campaigns. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience, editorial and acquisition pages | Editorial gray | `#666666` | `--color-muted` | text | Visible result of black at 60% on white for audience and editorial copy. |
| acquisition pages | Answer gray | `#969696` | `--color-faq` | text | Dense question-and-answer support text. |
| all-dark feature campaigns | Closing cyan | `#5fd8ff` | `--color-cyan` | text, accent | One emphasized word in a monumental dark closing line. |
| acquisition pages | Lavender wash | `#e5b3ff` | `--color-lavender` | background | Visible violet at 48% over white, built with rgba(200,97,255,0.48). |
| comparison sections | Mint comparison wash | `#f3feff` | `--color-mint-wash` | surface | Visible cyan at 10% over white, built with rgba(133,245,255,0.1). |
| comparison sections | Pink comparison wash | `#fef5ff` | `--color-pink-wash` | surface | Visible pink at 10% over white, built with rgba(244,158,255,0.1). |
| audience landing pages | Bright blue emphasis | `#00c0fa` | `--color-gradient-blue` | text, accent | Bright end of a gradient-clipped changing noun. |
| audience landing pages | Deep blue emphasis | `#043ed1` | `--color-gradient-deep` | text, accent | Deep end of the changing-noun gradient. |

## Typography

- **TWK Lausanne Pan** — Supporting copy, UI labels, navigational text and sober feature headings. Compact contemporary grotesk with a high x-height; light body cuts contrast with tightly tracked bold titles. If unavailable, use **Inter**. Use weights 300–700; preserve the light body and compact heading widths. Font stack: "TWK Lausanne Pan", "Inter", Arial, sans-serif.
- **Partiful Janky Inter Display** — Core marketing headlines, proof numerals and oversized closing action. Very condensed, heavy-looking uppercase letters with uneven edges and a handmade flyer character; visually bold despite its regular cut. If unavailable, use **Anton**. Use weight 400 and positive tracking; soften the mechanical regularity with a very subtle SVG displacement. Font stack: "Partiful Janky Inter Display", "Anton", Impact, sans-serif.
- **Partiful Display** (only for audience, editorial and all-dark feature pages) — Sentence-case opening titles and expressive closing lines. Wide, rounded grotesk display with tight joins and compact spacing. If unavailable, use **Manrope**. Use 500–600 and retain tight tracking. Font stack: "Partiful Display", "Manrope", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Partiful Janky Inter Display | 400 | 108.8px | 1 | 0.02em, uppercase | Default opening promise; break into two short, emphatic lines. |
| stat | Partiful Janky Inter Display | 400 | 100px | 1 | -0.01em, uppercase | Single huge proof number, anchored near the top of a colored card. |
| list-display | TWK Lausanne Pan | 400 | 69.6px | 1 | -0.0003em | Oversized centered category or destination links. |
| heading | Partiful Janky Inter Display | 400 | 50.1px | 1 | 0.02em, uppercase | Core section headings and oversized conversion label. |
| card-heading | TWK Lausanne Pan | 700 | 28px | 1.1 | -0.02em | Titles below large instructional media. |
| stat-caption | Partiful Janky Inter Display | 400 | 28px | 1 | 0.02em, uppercase | Short lower caption paired with the proof number. |
| hero-support | TWK Lausanne Pan | 400 | 24px | 1.2 | -0.02em | Single support line under the opening headline. |
| small-text | TWK Lausanne Pan | 300 | 19.2px | 1.2 | -0.02em | Media captions, text links and footer links. |
| footer-heading | TWK Lausanne Pan | 700 | 19.2px | 1.2 | -0.02em | Footer column labels. |
| body | TWK Lausanne Pan | 300 | 18.1px | 1.2 | -0.02em | Concise section support and dark chapter descriptions. |
| navigation | TWK Lausanne Pan | 400 | 16px | 1.2 | normal | Capsule navigation labels. |
| button | TWK Lausanne Pan | 600 | 16px | 1.2 | normal | Default rectangular and pill action labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| all-dark feature campaigns | closing-display | Partiful Display | 500 | 104px | 1.2 | -0.04em | Monumental final sentence with one cyan word. |
| all-dark feature campaigns | feature-heading | TWK Lausanne Pan | 700 | 56px | 1.2 | -0.04em | Broad sentence-case feature chapter headings. |
| all-dark feature campaigns | feature-display | TWK Lausanne Pan | 700 | 52px | 1 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Sentence-case opening promise on a dark product stage. |
| audience and editorial pages | editorial-display | Partiful Display | 500 | 48px | 1 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered sentence-case opening titles. |
| audience, editorial and acquisition pages | editorial-heading | TWK Lausanne Pan | 700 | 36px | 1.2 | -0.04em | Editorial chapters and acquisition opening titles. |
| all-dark feature campaigns | feature-lead | TWK Lausanne Pan | 550 | 29px | 1.2 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Large support line in dark feature openings. |
| audience, editorial and acquisition pages | editorial-lead | TWK Lausanne Pan | 550 | 24px | 1.4 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Audience eyebrow, lead paragraph and press quotation. |
| acquisition pages | compact-heading | TWK Lausanne Pan | 700 | 24px | 1.2 | -0.04em | Gallery headings and FAQ questions. |
| audience landing pages | raised-card-heading | TWK Lausanne Pan | 650 | 22px | 1.4 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Raised capability-card titles. |
| audience, editorial and acquisition pages | editorial-body | TWK Lausanne Pan | 550 | 20px | 1.4 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Longer explanatory copy and raised-card descriptions. |
| acquisition pages | answer | TWK Lausanne Pan | 700 | 18px | 1.2 | -0.04em | Compact answer text beneath questions. |
| audience, editorial and acquisition pages and all-dark feature campaigns | product-button | TWK Lausanne Pan | 550 | 16px | 1.4 | -0.02em | Compact product-page conversion labels. |

**Notes:**

- Poster lettering looks heavy through its construction, not a bold weight setting. Keep its uppercase rhythm and condensed silhouette distinct from the clean grotesk.
- Core supporting text uses -0.02em tracking and 1.2 line height. Editorial variants relax to 1.4 line height while their bold headings tighten to -0.04em.
- Do not replace all headings with one universal scale: the default poster treatment and the sentence-case product/editorial treatments are separate families of composition.

## Layout

**Density:** Airy stages with compact local groups: large empty fields frame vivid media, while labels and support lines remain close together.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap and inline label separation. |
| 12px | Adjacent actions and paired carousel controls. |
| 14px | Footer link rhythm. |
| 16px | Button vertical padding, review-slip padding and thumbnail-to-caption gap. |
| 24px | Button horizontal padding and dark campaign grid gaps. |
| 28px | Default three- and four-column media-grid gaps and proof-card gaps. |
| 32px | Media-to-title gap and outer footer inset. |
| 48px | Opening support-to-action gap and footer-column separation. |
| 56px | Heading group to large instructional grid. |
| 64px | Default horizontal section padding and proof heading-to-carousel spacing. |
| 96px | Top padding of major light sections. |
| 112px | Secondary light-section vertical padding and opening side padding. |
| 128px | Bottom padding of major light sections. |
| 144px | Generous top and bottom padding around the oversized category list. |
| 100px | Product and editorial chapter spacing and dark campaign padding. |

### Containers and grids

- **opening-stage**: max width 1116px · 2 columns · gap 50px · side padding 112px. Centered two-part hero: wide left copy, narrower tall media on the right.
- **marketing-container**: max width 1600px · side padding 64px. Full-width light marketing sections; 1312px usable width at a 1440px window.
- **instruction-grid**: 3 columns · gap 28px. Three equal 419px-wide media-and-caption columns at desktop.
- **capability-grid**: 4 columns · gap 28px. Four equal 307px-wide media tiles with captions below.
- **editorial-container** (only for editorial pages): max width 1000px · 2 columns · gap 40px · side padding 40px. Alternating text and 480×400px photo composites.
- **audience-container** (only for audience landing pages): max width 1200px · 2 columns · side padding 40px. Alternating feature rows with 660×422px product art.
- **raised-grid** (only for audience and acquisition pages): max width 1000px · 3 columns · gap 20px. Three 320px-wide raised cards.
- **dark-campaign-container** (only for all-dark feature campaigns): 3 columns · gap 24px · side padding 100px. 1240px usable width and three 397px-wide image columns at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | rectangular-actions | 4px |
|  | media-tiles | 8px |
|  | hero-portrait | 16.4px |
|  | footer-panel | 16px |
|  | navigation-capsule | 50px |
|  | pill-actions | 200px |
|  | closing-action | 111px |
| audience and acquisition pages | raised-cards | 12px |
| comparison sections | comparison-highlight | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | navigation-float | `1px 3px 16px 4px rgba(0,0,0,0.04)` | Extremely faint lift around the translucent navigation. |
|  | closing-halo | `0px 0px 38px 30px #f7f7f7` | Pale breathing space around the oversized dark conversion pill. |
| audience and acquisition pages | raised-card | `0px 0.8px 2.4px -0.6px rgba(0,0,0,0.05), 0px 2.4px 7.2px -1.3px rgba(0,0,0,0.05), 0px 6.4px 19.1px -1.9px rgba(0,0,0,0.05), 0px 20px 60px -2.5px rgba(0,0,0,0.05)` | Soft floating feature cards, without an outline. |

### Surfaces

#### Light canvas · level 0

**Use:** Default light stretches of a marketing page.

**CSS:** `background: #f7f7f7`

**Observed:** Large uninterrupted fields rather than stacks of bordered containers.

**Transfer:** Let typography and media supply the visual boundaries.

#### Black stage · level 0

**Use:** Opening product promise.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Pure black absorbs the surrounding space and makes the human scene luminous.

**Transfer:** Use it for the strongest promise or flagship object.

#### Dark chapter · level 0

**Use:** Immersive capability demonstrations and closing identity panel.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Slightly softer than the opening black; phone imagery sits directly on it.

**Transfer:** Group related demonstrations into a continuous dark field.

#### Media backing · level 1

**Use:** Neutral support for vivid product scenes.

**CSS:** `background: #ececec; border-radius: 8px; overflow: hidden`

**Observed:** The backing is subordinate to the picture; captions remain outside the tile.

**Transfer:** Use a pale stage when the object needs separation from the canvas.

#### Review frost · level 2

**Use:** Readable testimonial slips over photographs.

**CSS:** `background: rgba(247, 247, 247, 0.8); border-radius: 8px; backdrop-filter: blur(2px); padding: 16px`

**Observed:** Compact slips float across the middle or lower half of a candid image.

**Transfer:** Keep the photograph legible around the slip.

#### Clean editorial field · level 0

**Only for:** audience, editorial and acquisition pages

**Use:** Longer explanations and audience pages.

**CSS:** `background: #ffffff; color: #000000`

#### Acquisition glow · level 0

**Only for:** acquisition pages

**Use:** Soft color atmosphere behind a compact conversion opening.

**CSS:** `background: linear-gradient(rgba(255, 255, 255, 0) 0%, rgba(200, 97, 255, 0.48) 100%)`

**Observed:** Lavender is strongest toward the bottom, with blurred blue and pink patches beneath the content.

**Transfer:** Match the soft glow; exact stops of additional atmospheric patches are not essential.

#### Raised white card · level 1

**Only for:** audience and acquisition pages

**Use:** Image-first instructional and capability cards.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0px 0.8px 2.4px -0.6px rgba(0,0,0,0.05), 0px 2.4px 7.2px -1.3px rgba(0,0,0,0.05), 0px 6.4px 19.1px -1.9px rgba(0,0,0,0.05), 0px 20px 60px -2.5px rgba(0,0,0,0.05); overflow: hidden`

**Observed:** Full-bleed image above a padded text compartment, on a faint lavender atmosphere.

**Transfer:** Use this raised construction for concise steps rather than every block.

#### Comparison glow · level 1

**Only for:** comparison sections

**Use:** Highlight one offering in an otherwise plain comparison.

**CSS:** `background: linear-gradient(174deg, rgba(133, 245, 255, 0.1) 0%, rgba(244, 158, 255, 0.1) 98%); border-radius: 20px; padding: 16px; box-shadow: 0px 0px 20px 0px rgba(49, 189, 196, 0.2)`

**Observed:** A very faint luminous column, not a saturated pricing card.

**Transfer:** Keep neighboring columns unboxed and align the feature rows.

## Components

### Floating navigation

**Use:** Shared desktop navigation above every page type.

**CSS:** `width: 987px; height: 83px; background: rgba(253, 253, 251, 0.8); border-radius: 50px; padding: 16px 16px 16px 32px; backdrop-filter: blur(20px); box-shadow: 1px 3px 16px 4px rgba(0,0,0,0.04); box-sizing: border-box`

**Text style:** `navigation` — TWK Lausanne Pan 400 · 16px/1.2

**Observed:** Centered near the top with a small solid identity icon on the left, a horizontal link group, then dark primary and pale login pills. It floats over both dark and pale scenes.

**Transfer:** Use a compact symbol and only the main destinations; keep the capsule detached from page edges.

### Primary button

**Use:** Default action on the black opening stage.

**CSS:** `background: #fdfdfb; color: #000000; border-radius: 4px; padding: 16px 24px; height: 51px; box-sizing: border-box`

**Text style:** `button` — TWK Lausanne Pan 600 · 16px/1.2

**Observed:** The light primary sits before a dark secondary action. On a light section the primary fill reverses to near-black with warm-white lettering.

### Dark button

**Use:** Secondary action on the opening and main action on light instructional sections.

**CSS:** `background: #111111; color: #fdfdfb; border-radius: 4px; padding: 16px 24px; height: 51px; box-sizing: border-box`

**Text style:** `button` — TWK Lausanne Pan 600 · 16px/1.2

**Observed:** Placed beside the light primary on black, and alone beneath the instructional grid. Product-page variants use 48px height, 0 24px padding, product-button typography and pure black; all-dark campaigns reverse that variant to white.

### Pill action

**Use:** Navigation conversions and dark-chapter actions.

**CSS:** `background: #111111; color: #fdfdfb; border-radius: 200px; padding: 16px 24px; height: 51px; box-sizing: border-box`

**Text style:** `button` — TWK Lausanne Pan 600 · 16px/1.2

**Observed:** Dark in the navigation; warm-white with black text in dark demonstration chapters, where a small right arrow follows the label.

### Underlined text link

**Use:** Compact continuation action beside a muted media caption.

**CSS:** `color: #111111; text-decoration-line: underline`

**Text style:** `small-text` — TWK Lausanne Pan 300 · 19.2px/1.2 · tracking -0.02em

**Observed:** A plain inline link, not an outlined button; it sits on the same baseline as the caption.

**States:** Declared: hover color #777772 and underline retained; focus-visible unknown.

### Media tile

**Use:** Repeatable capabilities and introductory how-it-works panels.

**CSS:** `background: #ececec; border-radius: 8px; overflow: hidden`

**Text style:** `card-heading` — TWK Lausanne Pan 700 · 28px/1.1 · tracking -0.02em

**Observed:** The image fills the tile; its title and short muted description sit outside. Large instructional tiles are 419×445px, with 32px before the title; smaller capability tiles are 307×300px, with 16px before a caption.

**Transfer:** Show one recognizable action or outcome per tile rather than a full dashboard.

### Review slip

**Use:** Photo-led social proof.

**CSS:** `background: rgba(247, 247, 247, 0.8); border-radius: 8px; backdrop-filter: blur(2px); padding: 16px; width: 276px; box-sizing: border-box`

**Observed:** A compact title, star row with attribution metadata, then a short review sit over a flash-lit portrait. Multiple slips share a consistent pale material.

**Transfer:** Use real attributable proof and preserve the photo around the text.

### Carousel arrow

**Use:** Manual navigation beneath the proof rail.

**CSS:** `background: #eeeeee; width: 44px; height: 44px; border-radius: 9999px; padding: 1px 6px; display: flex; align-items: center; justify-content: center`

**Observed:** Two round controls with black 22px chevrons, 12px apart, centered 16px below the cards.

### Oversized closing action

**Use:** Final conversion framed by scattered artwork.

**CSS:** `background: #111111; color: #ffffff; border-radius: 111px; padding: 32px 56px; box-shadow: 0px 0px 38px 30px #f7f7f7`

**Text style:** `heading` — Partiful Janky Inter Display 400 · 50.1px/1 · tracking 0.02em · uppercase

**Observed:** A single dark capsule dominates the center of a 700px pale scene; a light, short support line sits beneath it.

**Transfer:** Use one short action so it reads like a graphic object rather than a form.

### Identity footer

**Use:** Shared monumental end treatment.

**CSS:** `background: #111111; color: #fdfdfb; border-radius: 16px; margin: 0px 32px 32px`

**Text style:** `small-text` — TWK Lausanne Pan 300 · 19.2px/1.2 · tracking -0.02em

**Observed:** Compact top-aligned link columns, a support group and stacked platform badges occupy the upper portion. A wide empty interval separates them from the nearly full-width white identity artwork below. Column labels use footer-heading; links use small-text with 14px gaps.

**Transfer:** Retain the monumental wordmark area and adapt destinations and distribution badges to the product.

### Raised capability card

**Only for:** audience and acquisition pages

**Use:** Steps or supporting benefits on focused landing pages.

**CSS:** `background: #ffffff; width: 320px; border-radius: 12px; overflow: hidden; box-shadow: 0px 0.8px 2.4px -0.6px rgba(0,0,0,0.05), 0px 2.4px 7.2px -1.3px rgba(0,0,0,0.05), 0px 6.4px 19.1px -1.9px rgba(0,0,0,0.05), 0px 20px 60px -2.5px rgba(0,0,0,0.05)`

**Text style:** `raised-card-heading` — TWK Lausanne Pan 650 · 22px/1.4 · tracking -0.04em

**Observed:** A 320×240px vivid image sits over text padded 30px. Cards form a three-column row with 20px gaps; acquisition steps add a numeral to the title and use smaller explanatory text.

**Transfer:** Limit each card to one benefit and one brief explanation.

## Imagery and graphics

### Flash-lit human scene

**Use:** Opening portrait and testimonial photography.

**Observed:** Close, unposed photographs of people laughing or gathered together, direct flash against dim interiors, warm skin and saturated incidental light. The opening photo is a tall 420×565px image with softly rounded corners, occupying about a third of the main composition; pale chat bubbles and circular avatars overlap its lower-left edge.

**Transfer:** Photograph the real human outcome of the product rather than people posing with devices. If no suitable photography exists, create a tall product-in-use composition with two small conversational outcome bubbles; retain the intimate framing and black surround.

**Build:** Use an object-fit:cover portrait inside a 16.4px-radius mask. Overlay warm-white rounded speech balloons with small triangular tails, circular avatar crops to their left and a second small balloon containing three pale dots; let the overlays extend beyond the image edge.

### Collectible output parade

**Use:** Signature expressive product showcase and closing artwork field.

**Observed:** Colorful rectangular outputs form a diagonal procession from beyond the lower-left edge to beyond the upper-right edge, overlapping in perspective. Graphic variety includes glossy 3D letters, photographic collages, bold flat color and irreverent poster designs. Near the closing action, smaller versions scatter and rotate across the pale field.

**Transfer:** Make original example outputs, artifacts or use-case posters for the new product. A minimum version uses typographic cards, cropped product details and varied color blocks rather than a uniform set of interface panels.

**Build:** Place roughly 12–18 rounded cards on a clipped pale stage. For the diagonal scene, use cards around 232×293px, perspective around 1200px, rotateY around -25deg and overlap each new card while stepping upward. For the closing field, distribute 150–170px cards with varied positive and negative rotation, leaving a clear central halo for the action. These transform settings are a construction guide, not a fixed alignment system.

### Product demonstration scenes

**Use:** How-it-works tiles and immersive dark chapters.

**Observed:** Large upright phones with recognizable dark bezels show pale aqua interfaces and bright personalized artwork. Light sections use full-bleed pastel-backed tiles; dark chapters place a roughly 280×597px phone directly on charcoal, with a heading left and short copy plus action right.

**Transfer:** Show a believable central interaction with a few legible details, not every screen. For non-mobile tools, use a tall interface fragment or output object at a comparable visual scale.

### Electric proof card

**Use:** Signature saturated proof accent among photographs and black star cards.

**Observed:** A deep blue, violet and magenta light field with fine square-grid texture supports a huge white number above a small uppercase caption. The card is 340×344px with 8px corners; the color is concentrated inside the card.

**Transfer:** Use a verified metric or a short testimonial as the graphic content, keeping its white poster treatment and vivid backing.

**Build:** Layer a deep-blue base with broad rgba(190,0,255,0.7) and rgba(255,0,180,0.6) radial glows near the upper-left and lower-middle. Blur the light fields around 50px, then overlay perpendicular repeating linear gradients of rgba(255,255,255,0.05) at a fine 4px pitch. Anchor the number near the top-left and the caption near the bottom-left.

### Monumental identity artwork

**Use:** Signature graphic at the end of every page type.

**Observed:** A white symbol and broad lowercase wordmark form a 1310×315px graphic, almost spanning the dark panel. It is far larger than the navigation identity and sits below a generous empty interval.

**Transfer:** Typeset the new product's name as an original wide identity lockup; adapt its proportions to fill the width without compressing individual letters.

**Build:** Use an SVG with a scalable viewBox around 1310×315. Fit a custom text outline or typographic wordmark plus a simple original symbol across it, fill white, and keep it inset from the dark panel edges. Treat it as artwork rather than another heading recipe.

### Pastel atmosphere

**Only for:** audience and acquisition pages

**Use:** Soft background energy around heroes, card rows, FAQs and closing calls.

**Observed:** Extremely blurred cyan, violet, pink and occasional mint pools dissolve into white. Text remains black; opacity and white overlays make the center readable. The audience opening also has tilted output cards, small profile portraits and tiny expressive stickers framing the edges.

**Transfer:** Keep an empty readable center. Use original artifacts related to the product as the edge collage; let color feel like reflected light rather than a hard-edged gradient slab.

**Build:** On white, place 600–1000px elliptical fields using rgba(200,97,255,0.25), rgba(0,192,250,0.12) and rgba(244,158,255,0.2), blur around 100px, then overlay translucent white to soften transitions. Position the strongest pools away from dense text. The audience variant places tilted cards and circular portraits at both side edges.

### Grainy feature artwork

**Only for:** all-dark feature campaigns

**Use:** Vivid card imagery on black product pages.

**Observed:** White interface fragments and ticket-shaped objects float at small angles over intensely colored, granular cyan-blue or orange-pink fields. A large three-column row is followed by a dark bento composition and a smaller horizontally clipped capability rail. The hero presents a glowing ticket or credential object against pure black.

**Transfer:** Isolate a few meaningful controls or outputs as white, gently tilted objects. Keep the surrounding page black so the colored art feels illuminated.

**Build:** Fill rounded image frames with overlapping radial glows in cyan, cobalt, violet and orange, then add a low-opacity monochrome SVG feTurbulence texture. Layer white UI fragments above, rotated only a few degrees with restrained soft shadows. For a ticket object, use rounded corners and paired circular side cutouts, with a luminous purple halo.

### Editorial memory album

**Only for:** editorial and culture pages

**Use:** Human opening image and alternating story chapters.

**Observed:** A 960×600px black-and-white group photograph opens the story below a small ornamental emblem and centered title. Later, 480×400px composites arrange overlapping polaroid-style photos of real gatherings, with white paper borders and slight rotations.

**Transfer:** Use documentary photographs of the product's people and context; avoid uniform studio headshots. Create simple overlapping paper frames if bespoke collage art is unavailable.

### Icons

**Observed:** Most marketing controls use solid monochrome symbols; carousel chevrons are 22×22px with 2px round strokes. Tiny arrows accompany some actions, while colorful emoji and stickers are confined to expressive media.

**Transfer:** Choose simple black or white controls matched to the surface. Reserve illustrated emoji-like details for collages, not for a rainbow navigation system.

## Section recipes

How recurring sections are built.

### First screen: Human-stage opening

**Observed:** A black stage about 946px tall begins with Floating navigation centered 32px from the top. Beneath it, a centered 1116px-wide two-part composition leaves broad black margins: a roughly 533px copy area on the left and a 420×565px portrait toward the right, separated by about 50px. The white display promise is broken into two blunt lines and vertically balanced against the portrait. Hero-support follows about 16px below; Primary button and Dark button sit 48px below the support with 12px between them. Layers run black field, portrait, floating chat balloons and avatars, then navigation above everything. Within the first 900px the navigation, full promise, support line, both actions and main portrait are visible; press proof starts below the opening stage.

**Transfer:** Start with the human or tangible result of the new product. Without photography, create a similarly tall expressive product scene and overlay short conversational outcome fragments. Focused acquisition pages instead open with a 36px sentence-case promise beside wide colorful media on a lavender wash; audience pages use a centered 48px title framed by edge collages; all-dark feature pages use a 52px sentence-case title beside a luminous object.

**Avoid:** Do not center a giant headline above a generic dashboard or fill the black stage with decorative gradients. Do not allow long introductory copy to displace the main object below the fold.

**Text style:** `display` — Partiful Janky Inter Display 400 · 108.8px/1 · tracking 0.02em · uppercase

### Heading and support pair

**Observed:** A 50.1px uppercase heading sits above a single light 18.1px support line with an 8px gap. It is centered for introductions and proof, left-aligned for broad visual showcases. Light sections use 96–128px vertical padding and 64px side padding.

**Transfer:** Give each chapter one short promise and one clarifying sentence. Use the same alignment throughout each local group.

**Text style:** `heading` — Partiful Janky Inter Display 400 · 50.1px/1 · tracking 0.02em · uppercase

### Press proof ribbon

**Observed:** A shallow horizontal band alternates monochrome publication marks and brief quotations. The default version has large pale quote panels, while focused pages use a denser edge-clipped strip on a softly tinted field.

**Transfer:** Use earned proof marks or short attributable endorsements in a horizontal rhythm; keep the marks monochrome so the product art retains the color.

### Instructional media grid

**Observed:** Three Media tiles share equal widths and 28px gaps. Large media sits above card-heading titles after 32px, then small-text captions after 8px. A single Dark button is centered below the group.

**Transfer:** Demonstrate a few concrete steps or outcomes, each with its own clear image and short label.

**Text style:** `card-heading` — TWK Lausanne Pan 700 · 28px/1.1 · tracking -0.02em

### Oversized category list

**Observed:** A white field pairs the centered heading group with a vertical sequence of 69.6px regular grotesk links. Each row has 16px vertical padding and rows are separated by 40px. The overall section has 144px top and bottom padding.

**Transfer:** Use a short set of categories, environments or applications when the breadth of the product deserves a typographic pause rather than another card grid.

**Text style:** `list-display` — TWK Lausanne Pan 400 · 69.6px/1 · tracking -0.0003em

### Immersive dark demonstration

**Observed:** A continuous Dark chapter uses near-viewport-height scenes. A short poster heading sits left, an upright phone is centered and light supporting copy plus a pale Pill action sits right. This makes the interface the shared focal point across several capabilities.

**Transfer:** Carry a single central object through a small set of feature states; use a browser fragment or physical artifact if a phone is not appropriate.

**Text style:** `heading` — Partiful Janky Inter Display 400 · 50.1px/1 · tracking 0.02em · uppercase

### Mixed proof rail

**Observed:** A centered heading pair leads a horizontally clipped rail of 340×344px cards with 28px gaps. Flash portraits with Review slips alternate with black star cards and Electric proof card artwork. Carousel arrows sit below.

**Transfer:** Mix human testimony with a substantiated visual proof point rather than repeating identical quote boxes.

**Text style:** `stat` — Partiful Janky Inter Display 400 · 100px/1 · tracking -0.01em · uppercase

### Artwork conversion and identity close

**Observed:** A 700px pale field scatters small collectible graphics around the Oversized closing action. Identity footer follows as a dark inset panel with compact navigation above a monumental white lockup. This ending combines an exuberant action moment with a calm, oversized brand sign-off.

**Transfer:** Keep the scattered artifacts and monumental identity device, but place them wherever the new narrative benefits from a strong visual punctuation. The footer always retains its distinctive large lockup.

### Audience feature alternation

**Only for:** audience landing pages

**Observed:** A centered 48px opening title and short lead are framed by edge collages. A monochrome proof strip and a three-person testimonial row lead into alternating 1200px-wide feature rows, with 660×422px art and 36px headings. Raised capability cards and photo-backed community examples build toward paired app and web actions before Identity footer.

**Transfer:** Adapt the changing noun to an audience's actual use cases. Let examples and real people establish breadth, then alternate demonstrations rather than duplicating the collage throughout.

**Text style:** `editorial-display` — Partiful Display 500 · 48px/1 · tracking -0.02em

### Acquisition gallery and objections

**Only for:** acquisition pages

**Observed:** A 36px opening title and 24px support sit beside 580×330px colorful media on Acquisition glow. Below the press ribbon, a 1000px gallery uses three 320px columns, then circular category thumbnails, Raised capability cards, a three-column comparison with Comparison glow on its center column, reviews and documentary photography. A two-column open FAQ uses 24px questions and 18px answers, not closed accordion rows.

**Transfer:** Use an explicit searchable promise and concrete examples, then answer practical objections. Close with a short glowing action band, a restrained information tail, platform actions when relevant and Identity footer.

**Text style:** `compact-heading` — TWK Lausanne Pan 700 · 24px/1.2 · tracking -0.04em

### Dark feature campaign

**Only for:** all-dark feature campaigns

**Observed:** Black persists from a two-column promise and glowing ticket object through colorful output rails and large feature cards. Chapter headings are 56px bold sentence case; three wide art panels are followed by a bento with one tall left panel and two stacked right panels. A smaller horizontal capability rail precedes a 104px closing sentence with a cyan word and then Identity footer.

**Transfer:** Use this variant when one feature deserves a focused launch story. Replace the ticket with a meaningful luminous artifact and keep saturated backgrounds inside media, not the entire page.

**Text style:** `feature-heading` — TWK Lausanne Pan 700 · 56px/1.2 · tracking -0.04em

### Editorial story and invitation

**Only for:** editorial and culture pages

**Observed:** A centered 48px title and small ornamental emblem lead into a 960×600px monochrome group portrait. After a press ribbon, alternating 1000px-wide chapters pair 36px headings and 20px/1.4 paragraphs with 480×400px polaroid composites. A compact centered invitation with a small image cluster and black action closes the narrative before Identity footer.

**Transfer:** Tell the origin, human problem, approach and people in a few substantial illustrated chapters. Adapt the final invitation to recruiting, participation or another relevant action.

**Text style:** `editorial-heading` — TWK Lausanne Pan 700 · 36px/1.2 · tracking -0.04em

## Page flow

**Storyline:** Blunt promise → tangible human or product demonstration → borrowed credibility → capability chapters and expressive examples → social proof or objections → emphatic action → monumental identity.

### Broad consumer product introduction

1. **Promise** — Black human-stage opening with poster headline and two actions.
2. **Credibility** — Monochrome press ribbon.
3. **Product demonstration** — Three visual steps followed by collectible output artwork and an oversized category list.
4. **Capability chapters** — Immersive dark central-object scenes, then a compact four-tile light overview.
5. **Social proof** — Mixed photographic, star and statistic rail.
6. **Closing call** — Scattered output art surrounds a giant dark action, followed by the identity footer.

**Transfer:** Balance the product's practical explanation with a vivid sense of how using it feels.

### Search-driven category acquisition

1. **Promise** — Explicit sentence-case title, product montage and low-friction action on a pastel field.
2. **Product examples** — Template-style gallery and circular category entry points.
3. **Product demonstration** — Three raised instructional cards.
4. **Differentiation** — Aligned comparison columns with one glowing recommendation.
5. **Social proof** — Review streams and a broad human photo collage.
6. **Objection handling** — Two-column open FAQ.
7. **Closing call** — Glowing conversion band, small information tail, app-download invitation and shared identity footer.

**Transfer:** Use the category's actual search language without losing the colorful artifact-led visual voice.

### Audience-specific product explanation

1. **Promise** — Centered changing-noun headline framed by output and portrait collage.
2. **Credibility** — Publication marks and compact personal endorsements.
3. **Capability chapters** — Alternating product art and text, then three raised benefit cards.
4. **Social proof** — Three photographic example communities with overlaid titles.
5. **Closing call** — A free-start invitation with paired distribution choices and shared identity footer.

**Transfer:** Show that the same tool fits different groups through real use cases, not industry jargon.

### Focused feature launch and conversion

1. **Promise** — Sentence-case white title, availability badge, light action and glowing artifact on black.
2. **Product examples** — Edge-clipped colorful output rail.
3. **Capability chapters** — Three large image panels, an asymmetric distribution bento and smaller capability rail.
4. **Closing call** — Oversized farewell line with one cyan word and an accompanying graphic, then the shared identity footer.

**Transfer:** Carry the feature's tangible artifact from hero to supporting demonstrations while preserving the dark environment.

### Company story and participation

1. **Identity** — Ornamental emblem, centered title and monochrome group photograph.
2. **Credibility** — Press quotations and publication marks.
3. **Origin and approach** — Alternating editorial text and polaroid composites explain the human problem and the product's approach.
4. **People** — A human team chapter continues the same alternating rhythm.
5. **Closing call** — Small centered image cluster, invitation headline and action, then the shared identity footer.

**Transfer:** Keep company storytelling grounded in human behavior and lived scenes rather than a list of abstract values.

## Writing

Friendly, socially fluent and bluntly confident. Practical benefits sound like a friend removing friction; occasional slang supplies irreverence without making every sentence a joke.

**Do not copy:** Do not reuse the Partiful name, logos, proprietary artwork, publication quotations, review text, ratings, usage counts, free-forever promises, availability claims or competitor claims as assets or facts for another product. Source examples illustrate tone only.

- **Addressing the reader:** Speak directly to you and your people. Use we for the team and simple verbs for what the product does.
- **Rhythm:** Core headlines are often three to six words or two clipped clauses. Support is usually one sentence; editorial pages expand into conversational paragraphs. Action labels are short verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A confident social observation or a two-part announcement, not an abstract positioning statement. | 3–12 words | “Parties are back”<br>“The party's on [Brand]. Now the tickets are too” |
| Section headline | Compress a useful outcome into a spoken phrase; use short parallel clauses when appropriate. | 3–7 words | “One link. Everyone’s in.”<br>“More than an invite”<br>“Easy AF ticketing” |
| Supporting line | Name a familiar frustration, then describe the concrete fix. | One sentence or two short sentences | “No more chaotic group chats. Send one message and reach all your guests individually.”<br>“Everything your guests need, all in one place.” |
| Primary action | Verb plus the immediate object or next step; mention low friction only when true. | 2–4 words | “Create for free”<br>“Try it out”<br>“Start selling” |
| Closing reassurance | A short human payoff rather than a formal sales summary. | 5–12 words | “Your social life will thank you”<br>“Create yours in 2 minutes — no credit card, no app, no catch.” |
| Editorial chapter | Start from something people say, then give it a memorable twist. | A short conversational phrase | “From “we should hang out” to “last night was a movie” |

**Words and phrasing to use:** your; everyone; make it yours; no more; one link; try it out; actually; real; no catch; all in one place

**Avoid:** enterprise-grade; leverage; seamless ecosystem; unlock synergies; revolutionary platform; best-in-class

**Rules:**

- Lead with what people can do or feel, then explain the mechanism.
- Use contractions and everyday language; reserve stronger slang for a headline where it earns its place.
- Tie reassurance to a specific concern rather than a generic promise.
- Keep longer story paragraphs warm and concrete, with examples of ordinary behavior.

## Do's and Don'ts

### Do

- Use the 108.8px poster display only for a genuinely short opening promise.
- Keep the 50.1px uppercase section title paired with lighter 18.1px support.
- Let 64px side gutters frame light marketing grids and 28px gaps separate their tiles.
- Place product imagery on a neutral field before adding saturated content inside it.
- Give social proof mixed materials: candid photo, translucent slip, star graphic and vivid proof card.
- Keep rectangular hero actions at 4px radius and navigation actions at 200px radius.
- Retain the 32px inset and monumental white identity artwork at the close.
- Use the 36px sentence-case editorial variant for longer explanations, with 20px/1.4 body copy.

### Don't

- Do not turn the light 300-weight supporting copy into semibold SaaS body text.
- Do not apply the poster face to paragraph copy or navigation.
- Do not make every card a white shadowed panel; default media stages are flat and pale.
- Do not replace the monochrome controls with saturated primary-color buttons.
- Do not add thick outlines to media tiles or a heavy stroke around the frosted navigation.
- Do not turn the large category list into small chips; its 69.6px typography is the point.
- Do not shrink the identity footer to a standard copyright strip with a tiny logo.
- Do not distribute pastel glow behind every default section; reserve page-level washes for the scoped variants.

## Motion and responsive

### Motion

**Observed:**

- The central demonstration object is presented through multiple chapter states, and horizontal proof and artwork rails imply movement.
- A text-link hover changes to #777772 while retaining its underline. No action or surface transition durations are established.

**Transfer:**

- Keep the centered demonstration object visually continuous between chapter states.
- Provide the paired circular controls for a horizontally clipped proof rail rather than relying entirely on automatic movement.

**Unknown:**

- Exact animation triggers, durations, easing and scroll-pinning behavior are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px, 960px, 1200px and 1440px.

**Transfer:**

- On narrow screens, preserve the promise-before-object reading order and keep the conversational overlays attached to the media.
- Collapse instructional and capability grids without losing the image-above-caption relationship; keep artwork and proof rails horizontally clipped where appropriate.
- Scale the monumental identity artwork to the panel width instead of letting it become a conventional small logo.

**Unknown:**

- Exact mobile navigation, type sizes, gutters and stacking breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
