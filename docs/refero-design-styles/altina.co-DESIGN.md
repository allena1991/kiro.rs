# Altina — heirloom technology, italic warmth

## Overview

A light, editorial style that makes advanced technology feel like a beautifully made personal object. Warm stone and peach backgrounds, dark brown old-style serif headlines and ochre italics sit beside restrained grotesk support text. Monumental product photography, intimate real-life scenes and polished material close-ups give the sparse layouts the feeling of a design atelier rather than a software dashboard.

### Essentials

- Headlines have a spoken italic turn: Junicode at weight 400, 110px/1.1 with -0.04em tracking in the opening; one meaningful word or phrase turns italic and #765d2a while punctuation stays brown.
- The first screen is a product encounter, not a feature grid: a centered wordmark, a single-line promise about 848px wide, restrained 20px support, and a nearly edge-to-edge object filling the lower half of a 900px stage.
- Conversion floats like a small object: a 206×46px dark-brown capsule with a 38px cream circular arrow inset, fixed at the bottom center; the closing form uses a separate 164×56px outline pill.
- Color behaves like tinted paper: nearly all page area is stone, peach or ivory; ochre is reserved for italic emphasis, while stronger color comes from photography rather than saturated interface fills.
- Imagery alternates between monumental and intimate: full-bleed 1440×900px craft photography, a small centered 432×270px lived-use image, and tightly cropped 720×405px material details. For intangible products, stage a single authored interface or process artifact with the same scale contrasts.
- The ending returns to the object: a 560px ivory footer of ruled, equal-width panels sits over a 340px full-width product close-up that fades into its backing. Preserve this oversized closing image and soft disappearance; use an enlarged product detail or representative artifact when no physical object exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Brown ink | `#322813` | `--color-ink` | text, action, border | Main serif text, conversion capsule and outlined action edges. |
| Powder peach | `#e9d3c3` | `--color-peach` | background | Warmer endpoint of the page and opening gradients. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ochre italic | `#765d2a` | `--color-emphasis` | text, accent | Selected italic words and editorial section headings; not a broad color fill. |
| Link hover brown | `#695732` | `--color-hover` | link | Declared hover color for footer navigation and legal links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft brown heading | `#403b31` | `--color-secondary-heading` | text | Contextual, human-use section heading. |
| Warm grey label | `#7a756b` | `--color-muted` | text | Small uppercase navigation and editorial labels. |
| Ivory rule | `#e5e0da` | `--color-rule` | border | Fine footer and form separators. |
| Warm stone | `#e2e1dc` | `--color-stone` | background | Cooler endpoint of the warm page gradient. |
| Paper cream | `#f8f5ef` | `--color-card` | surface, text | Editorial and press cards; reversed text on photography and the translucent navigation capsule. |
| Footer ivory | `#f9f5f0` | `--color-footer` | background, text, surface | Footer panels, floating action's circular inset and its pale label. |
| Closing porcelain | `#faf5f0` | `--color-closing` | background | Backing beneath the final full-width product image. |
| White overlay | `#ffffff` | `--color-white` | text | Reversed narrative words over changing visual scenes. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product mechanism demonstrations | Chapter black | `#1a1a1a` | `--color-chapter` | action | Selected circular chapter control. |
| company and editorial pages | Editorial charcoal | `#3f3a31` | `--color-editorial-ink` | text | Article titles, dates and press quotations. |

## Typography

- **Junicode** — Display text, editorial paragraphs, footer links and contacts, in regular and true italic cuts. Literary old-style serif with calligraphic italics; delicate at regular weight and expressive without bold. Font stack: "Junicode", Georgia, serif.
- **Aspekta** — Supporting copy, technical captions, labels and conversion actions. Restrained contemporary grotesk; mostly regular with a slightly firmer action label. Font stack: "Aspekta", Arial, sans-serif.
- **Noto Serif** (only for product mechanism demonstrations) — Roman numerals inside chapter selectors. Compact, conventional serif numerals distinct from the main display face. Font stack: "Noto Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Junicode | 400 | 110px | 1.1 | -0.04em | Primary landing promise, centered and generally held to a single line at desktop. |
| display-italic | Junicode | 400 italic | 110px | 1.1 | -0.04em | One key phrase within the primary promise. |
| heading-large | Junicode | 400 | 64px | 1.1 | -0.04em | Two-line craftsmanship or quality statement beside oversized details. |
| heading-large-italic | Junicode | 400 italic | 64px | 1.1 | -0.04em | Emphasized word within the craftsmanship statement. |
| contact | Junicode | 400 | 56px | 1.1 | -0.04em | Primary contact address, treated as a display line. |
| context-heading | Junicode | 400 | 54px | 1.1 | -0.04em | Human-use context heading above a small photograph. |
| heading | Junicode | 400 | 52px | 1.1 | -0.04em | Default centered capability heading and narrative overlay text. |
| heading-italic | Junicode | 400 italic | 52px | 1.1 | -0.04em | Capability emphasis; also standalone editorial subheadings. |
| footer-link | Junicode | 400 | 32px | 1.1 | -0.04em | Large, tightly stacked footer navigation and social links. |
| photo-kicker | Junicode | 400 | 28px | 1.1 | -0.04em | Short attribution above a maker or partner mark on photography. |
| photo-support | Aspekta | 400 | 24px | 1.3 | 0.01em | Centered reversed paragraph near the bottom of full-screen craft photography. |
| secondary-contact | Junicode | 400 | 24px | 1.1 | -0.04em | Secondary inquiry address below the main contact. |
| navigation-capsule | Junicode | 400 | 22px | 1 | -0.01em | Single small navigation link in the opening. |
| body | Aspekta | 400 | 20px | 1.3 | 0.01em | Opening explanation and mechanism captions; brown ink at 0.7 opacity for a softer reading tone. |
| detail-caption | Aspekta | 400 | 20px | 1 | 0.01em | Short, separate material specifications under the quality heading. |
| action | Aspekta | 450 | 14px | 1 | -0.01em | Floating and form conversion labels. |
| caption | Aspekta | 400 | 12px | 1.3 | 0.01em | Small signup support and underlined legal links. |
| eyebrow | Aspekta | 400 | 11px | 1.1 | 0.01em, uppercase | Footer column labels and article categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and editorial openings | editorial-display | Junicode | 400 | 82px | 1.1 | -0.04em | Short centered manifesto replacing the product-led opening. |
| company and editorial openings | editorial-display-italic | Junicode | 400 italic | 82px | 1.1 | -0.04em | The manifesto's single emphasized word. |
| company and editorial pages | editorial-body | Junicode | 400 | 32px | 1.2 | -0.02em | Centered long-form paragraphs and founder perspective. |
| editorial cards | article-title | Junicode | 400 | 32px | 1.2 | -0.03em | Left-aligned article heading above its image. |
| editorial cards | article-date | Junicode | 400 | 20px | 1.2 | -0.03em, uppercase | Date aligned opposite a circular arrow beneath the image. |
| company and editorial openings | editorial-support | Aspekta | 400 | 18px | 1.3 | 0.01em | One-line explanation under a manifesto. |
| press proof sections | press-quote | Junicode | 400 italic | 18px | 1.2 | -0.03em | Short centered quote beneath a publication logo. |
| product mechanism demonstrations | chapter-numeral | Noto Serif | 400 | 14px | 1 | normal | Roman numeral chapter selector. |

**Notes:**

- Serif display recipes share weight 400, line height 1.1 and -0.04em tracking; emphasis changes cut and color, not weight or size.
- Supporting grotesk text uses positive 0.01em tracking, while action labels tighten to -0.01em. Keep this contrast rather than applying one tracking token to every family.
- Editorial prose relaxes to 1.2 line height and -0.02em tracking; it is not a smaller marketing headline.

## Layout

**Density:** Airy, with full-screen product stages and large pauses between narrow text groups; utility areas become more tightly stacked.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Article title-to-image and compact editorial internals. |
| 10px | Small editorial support gaps and simple flex group spacing. |
| 16px | Opening headline-to-support separation, grouped captions and form control gap. |
| 20px | Editorial card-grid gutters and outline-action padding. |
| 24px | Card padding, footer left inset and label-to-link separation. |
| 32px | Capability content spacing, footer right-panel inset and centered prose inset. |
| 40px | Desktop side padding for centered capability and editorial sections. |
| 84px | Gap between footer navigation and social groups. |
| 128px | Separation of major editorial content groups. |

### Containers and grids

- **stage**: max width 1440px · side padding 0px. Full-bleed product stages and photography; the opening is 900px high at desktop.
- **capability**: max width 1440px · side padding 40px. Centered content stack with a 679px heading and approximately 621×373px demonstration.
- **material-split**: 2 columns · gap 0px. Equal 720px halves at desktop: sticky centered copy on the left, three stacked 720×405px macro images on the right.
- **footer-panels**: 2 columns · gap 0px. Two equal 720px panels above a full-width closing image; thin rules define the divisions.
- **prose** (only for company and editorial pages): max width 700px · side padding 32px. Narrow centered editorial text with 636px available for paragraphs.
- **proof-grid** (only for press proof sections): max width 1200px · 2 columns · gap 20px. Two equal 590px press tiles per row.
- **article-column** (only for editorial cards): max width 590px · 1 column · gap 20px. A centered vertical sequence of substantial editorial cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | floating-action | 39px |
|  | action-inset | 55px |
|  | outline-action | 52px |
|  | navigation | 45.9px |
|  | media | 8px |
| editorial and press cards | editorial-card | 12px |
| product mechanism demonstrations | chapter-control | 50% |

## Surfaces and depth

### Surfaces

#### Tinted canvas · level 0

**Use:** Continuous warm background connecting product and editorial sections.

**CSS:** `background: linear-gradient(#e2e1dc 0%, #e9d3c3 100%)`

**Observed:** The page gently warms from stone to peach rather than alternating flat bands.

**Transfer:** Let a long gradient unify sparse content.

#### Opening tint · level 0

**Use:** Product-led opening stage.

**CSS:** `background: linear-gradient(270deg, #e2e1dc 0%, #e9d3c3 100%); overflow: clip`

**Observed:** Peach on the left, stone on the right; photographic edges dissolve into the same field.

**Transfer:** Keep the tonal difference subtle enough for brown text and transparent product cutouts.

#### Ivory footer · level 0

**Use:** Ruled signup, navigation and contact panels.

**CSS:** `background: #f9f5f0`

#### Closing image backing · level 0

**Use:** Final full-width product return.

**CSS:** `background: #faf5f0; overflow: clip`

#### Smoked navigation glass · level 1

**Use:** Small opening navigation capsule.

**CSS:** `background: rgba(50, 40, 19, 0.5); backdrop-filter: blur(35px); border-radius: 45.9px`

**Observed:** The translucent brown reads as warm grey over the pale gradient.

**Transfer:** Keep glass local to the small navigation element; the main content stays paper-like.

#### Cream card · level 1

**Only for:** editorial and press cards

**Use:** Article and publication proof content.

**CSS:** `background: #f8f5ef; border-radius: 12px; padding: 24px; box-shadow: none`

**Observed:** Pale surfaces are differentiated by fill rather than heavy edges or elevation.

**Transfer:** Use this contained treatment for reading and third-party proof, not for every marketing section.

## Components

### Floating conversion

**Use:** Persistent primary conversion across product storytelling.

**CSS:** `position: fixed; bottom: 24px; left: 50%; transform: translateX(-50%); width: 206px; height: 46px; background: #322813; color: #f9f5f0; border-radius: 39px; overflow: hidden`

**Text style:** `action` — Aspekta 450 · 14px/1 · tracking -0.01em

**Observed:** A short label sits on the left; a cream circular inset on the right holds a bent arrow. The inset is 38×38px with a 4px outer inset and a 16px icon. It remains centered over photographs and technical scenes, then gives way to the closing form.

**Transfer:** Use one concise conversion verb phrase; preserve the circular arrow as part of the silhouette.

### Navigation capsule

**Use:** Single secondary destination opposite a centered wordmark.

**CSS:** `background: rgba(50, 40, 19, 0.5); color: #f8f5ef; backdrop-filter: blur(35px); border-radius: 45.9px; height: 44px; padding: 11.1px 13.9px`

**Text style:** `navigation-capsule` — Junicode 400 · 22px/1 · tracking -0.01em

**Observed:** A small capsule sits near the top right, independent of the centered identity. There is no broad multicolumn navigation bar.

### Outline submit

**Use:** Conversion within the footer email row.

**CSS:** `border: 1px solid #322813; border-radius: 52px; padding: 20px; height: 56px; width: 164px; background: transparent; color: #322813`

**Text style:** `action` — Aspekta 450 · 14px/1 · tracking -0.01em

**Observed:** One centered label, no circular icon inset; sits to the right of the unboxed email entry.

### Signup row

**Use:** Low-profile email collection at the base of the left footer panel.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 24px 32px 24px 24px; border-top: 1px solid #e5e0da; border-bottom: 1px solid #e5e0da; height: 106px`

**Observed:** A wide, borderless serif email prompt occupies the left side and Outline submit occupies the right. A tiny two-line support statement sits above the row in the otherwise spacious identity panel.

**Transfer:** Retain the unboxed field and ruled row; use a meaningful accessible label separate from the prompt.

### Footer navigation link

**Use:** Site menu and social destinations in the upper-right footer panel.

**CSS:** `color: #322813; text-decoration: none`

**Text style:** `footer-link` — Junicode 400 · 32px/1.1 · tracking -0.04em

**Observed:** Links stack with 2px gaps below uppercase labels; navigation and social groups are separated by 84px.

**States:** Declared: hover color #695732; focus-visible and active styling are unspecified.

### Display contact

**Use:** Large direct contact destination in the lower-right footer panel.

**CSS:** `color: #322813`

**Text style:** `contact` — Junicode 400 · 56px/1.1 · tracking -0.04em

**Observed:** A small uppercase label leads a prominent serif address with a 24px gap; a secondary 24px address sits below under its own small label.

### Article card

**Only for:** editorial cards

**Use:** Longer reading destinations within a narrow centered column.

**CSS:** `background: #f8f5ef; border-radius: 12px; padding: 24px; width: 590px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `article-title` — Junicode 400 · 32px/1.2 · tracking -0.03em

**Observed:** Category capsule, left-aligned serif title, 542×312px rounded image, then an uppercase serif date opposite a circular arrow. Title and image are separated by 8px; the card is about 557px high.

**Transfer:** Use materially rich photography or a real process image, not a generic colored illustration.

### Press tile

**Only for:** press proof sections

**Use:** Publication-led third-party proof.

**CSS:** `background: #f8f5ef; border-radius: 12px; padding: 24px; width: 590px; height: 181px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 16px`

**Text style:** `press-quote` — Junicode 400 italic · 18px/1.2 · tracking -0.03em

**Observed:** A publication mark is centered above one short italic quotation. Tiles form a two-column grid beneath a standalone ochre italic heading.

### Chapter selector

**Only for:** product mechanism demonstrations

**Use:** Two-step explanation beneath a centered product scene.

**CSS:** `width: 30px; height: 30px; border-radius: 50%; background: #1a1a1a; border: 1px solid rgba(0,0,0,0.25); color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `chapter-numeral` — Noto Serif 400 · 14px/1

**Observed:** Two Roman-numeral circles flank a 266px fine horizontal track. The active circle is dark; the inactive circle reads as a pale outlined control in the rendered scene.

**Transfer:** Use only for a short, authored mechanism story rather than a generic carousel navigation system.

## Imagery and graphics

### Monumental product portrait

**Use:** Opening and closing signature image.

**Observed:** An almost full-width, straight-on view of glossy dark tortoiseshell eyewear dominates the lower opening. Highlights describe real material; the lower arms disappear into soft cream haze. The closing returns to a black frame on porcelain with a similar fade.

**Transfer:** Use an enlarged front view or characteristic contour of the new object. For software, enlarge one carefully composed interface or data artifact; retain a dark recognizable silhouette and soft bottom dissolution rather than a device mockup collage.

**Build:** Place a transparent product cutout at full stage width, roughly 469px high at desktop. Layer a bottom-aligned 453px veil with backdrop-filter blur(35px), filter blur(5px), and a vertical mask rising from transparent to opaque near the bottom. Fade into the underlying stone-peach gradient in the opening and porcelain in the closing; tune the mask to retain crisp upper edges.

### Craft environment photograph

**Use:** Full-screen provenance or making chapter.

**Observed:** Warm, softly lit showroom photography shows several objects arranged diagonally on cream stone shelves, with one foreground object in crisp focus and peripheral pieces cut by the frame. The palette is sepia, charcoal and cream. A small maker attribution sits high and a reversed supporting paragraph sits low.

**Transfer:** Photograph the new product in a credible making, display or use environment. Preserve soft directional light, tactile backing and foreground/background depth. A carefully lit tabletop composition is the minimum acceptable substitute.

### Human context window

**Use:** Small photographic counterpoint to expansive product stages.

**Observed:** A centered 432×270px image of people talking around a restaurant table sits beneath a two-line 54px serif heading. Ambient amber lighting and natural gestures make it feel observed rather than posed; the image occupies much less space than the surrounding canvas.

**Transfer:** Choose a specific human situation improved by the product, framed as a modest, intimate window rather than a full-bleed lifestyle banner.

### Material macro stack

**Use:** Craftsmanship proof beside the large quality statement.

**Observed:** Three edge-to-edge 720×405px images stack in the right half. Polished metal, translucent amber acetate and glossy black surfaces are tightly cut, sometimes beyond recognition as a whole object; peach backing aligns with the page. Fine pale seams divide images.

**Transfer:** Show real construction at close range: fasteners, joinery, material thickness or precise interface details. Keep one consistent warm background and alternate reflective and translucent textures.

### Mechanism particle scene

**Only for:** product mechanism demonstrations

**Use:** Explain an invisible process around a visible product.

**Observed:** A three-quarter isolated product floats on a blush-neutral stage around 621×373px. Small brown-grey particles form a loose directional cloud beneath and in front of the object, with no dashboard chrome.

**Transfer:** Visualize the new mechanism through a sparse, localized field around the object. A still product render with a restrained SVG particle cloud is sufficient when animated technical artwork is unavailable.

**Build:** Use an SVG viewBox of 621 by 373 behind a transparent product render. Scatter irregular 1px circles using rgba(50,40,19,0.25) and rgba(118,93,42,0.35), concentrating them in a shallow curved funnel from lower left toward a functional point on the object. Thin the field toward the perimeter with an opacity mask; keep broad clear space around the product. Do not replace the product with particles.

### Editorial process image

**Only for:** editorial cards

**Use:** Visual anchor inside article cards.

**Observed:** A technical wafer-like grid is photographed diagonally with muted green and gold reflections; it fills a 542×312px image with 8px corners. Technical subject matter is treated as a physical material rather than a flat icon.

**Transfer:** Use an authentic image of the new domain's process or materials with subdued color and shallow depth.

### Icons

**Observed:** Icons are sparse directional marks: a 16px bent arrow within the floating cream disc, fine circular external-link arrows on cards, and an upward arrow in the footer. They use restrained thin dark strokes rather than filled pictograms.

**Transfer:** Favor small directional arrows and circles over feature-icon sets. Keep arrows subordinate to serif text and product imagery.

## Section recipes

How recurring sections are built.

### First screen: Product encounter opening

**Observed:** A 900px full-width Opening tint stage layers a centered wordmark high at the top, a compact Navigation capsule at the upper right, a centered 110px regular-and-italic promise across roughly three fifths of the width in the upper-middle, then 20px supporting copy in a 515px column with a 16px gap. The headline has dark-brown regular words, one ochre italic phrase and brown punctuation. A nearly edge-to-edge Monumental product portrait begins below the copy, fills the lower half and fades down into the background. Floating conversion sits bottom-center above the haze. Within the first 900px the identity, complete promise, explanatory and availability lines, action and main object are all visible; the next full-screen craft photograph begins below the fold.

**Transfer:** For another product, pair a short human outcome with one sculptural object or enlarged representative interface. Keep the visual dominance and soft fade even if the artwork is a simple carefully lit cutout. Company or editorial pages instead use a sparse 82px manifesto with a single italic word, 18px support and no opening object; centered prose can begin before the first fold.

**Avoid:** Do not shrink the object into a card beside the headline, add a row of feature badges, or move the main conversion into a large pair of inline hero buttons.

**Text style:** `display` — Junicode 400 · 110px/1.1 · tracking -0.04em

### Full-screen craft endorsement

**Observed:** Craft environment photograph fills a 1440×900px stage; a 28px serif attribution and maker mark sit near the upper center, while a 24px reversed paragraph occupies a narrow lower-center column. Floating conversion overlays the image.

**Transfer:** Use one credible origin, partnership or making story with a real environmental image; let the photograph carry most of the information.

**Text style:** `photo-support` — Aspekta 400 · 24px/1.3 · tracking 0.01em

### Intimate context and narrative

**Observed:** A centered 54px serif heading with italic ending introduces a small Human context window after about 43px. A tall, sticky storytelling region allows 52px narrative words and media to change over a longer scroll rather than packing many cards side by side.

**Transfer:** Tell a compact sequence of recognizable situations using one visual focus at a time. Keep the small opening image against a broad neutral field.

**Text style:** `context-heading` — Junicode 400 · 54px/1.1 · tracking -0.04em

### Centered mechanism chapter

**Observed:** A centered 52px heading within 679px introduces a roughly 621×373px Mechanism particle scene. A 20px caption follows about 28px below and Chapter selector follows about 30px later. The scene sits inside a 900px sticky stage with 40px outer padding while the longer section advances its story.

**Transfer:** Explain one mechanism at a time with a short heading and one concrete caption. Use a static authored scene if only one step is needed.

**Text style:** `heading` — Junicode 400 · 52px/1.1 · tracking -0.04em

### Split material proof

**Observed:** Material-split places a sticky centered text block in the left half of the screen and Material macro stack in the right. The 64px two-line heading ends in an ochre italic word; 20px support and two short material captions sit below. Imagery touches the outer right edge and uses only fine seams between frames.

**Transfer:** Choose two or three verifiable details of construction and give each a tactile close-up, not a bulleted feature card.

**Text style:** `heading-large` — Junicode 400 · 64px/1.1 · tracking -0.04em

### Ruled closing with object return

**Observed:** Ivory footer is 560px tall above a 340px Closing image backing. Its equal halves contain identity, tiny signup support and Signup row on the left; two columns of Footer navigation link above Display contact, secondary inquiry and small legal links on the right. Fine warm rules divide the panels. A small circular back-to-top arrow sits at the upper right. The page ends with a full-width Monumental product portrait whose lower edge dissolves into porcelain; both page types share this ending.

**Transfer:** Preserve a useful, spacious ruled footer and a final oversized return to the product or representative artifact. Adapt links and contact roles to the new business without replacing the ending with a generic banner CTA.

### Editorial manifesto and philosophy

**Only for:** company and editorial pages

**Observed:** An 82px centered statement with ochre italic emphasis sits after a long top pause in a 630px opening. A small 18px support line follows. Subsequent centered 32px serif prose lives inside Prose, with distinct paragraphs, a founder quotation and an attribution. A 52px ochre italic philosophy heading introduces another prose block.

**Transfer:** Use this quieter text-led variant for mission, origin or design principles; keep the prose column narrow and the serif paragraphs much larger than utility text.

**Text style:** `editorial-body` — Junicode 400 · 32px/1.2 · tracking -0.02em

### Editorial and publication proof

**Only for:** company and editorial pages

**Observed:** Article card entries stack in a 590px centered column. A later 52px italic proof heading leads a 1200px two-column grid of Press tile components with 20px gutters. A substantial warm-canvas pause separates this proof from the footer.

**Transfer:** Use articles for depth and publication tiles for independent validation. Preserve their distinct widths rather than flattening them into one uniform card grid.

**Text style:** `heading-italic` — Junicode 400 italic · 52px/1.1 · tracking -0.04em

## Page flow

**Storyline:** Human promise → tangible design credibility → real-life relevance → mechanism or philosophy → detailed proof → direct conversion and object reprise.

### Product-led marketing that makes new technology desirable and understandable

1. **Promise** — A large centered serif-and-italic statement above a monumental front-facing object.
2. **Credibility** — Full-screen craft-environment photography with attribution and a concise supporting paragraph.
3. **Human relevance** — A small intimate scene expands into scroll-led contextual narrative.
4. **Mechanism explanation** — Centered isolated product scenes, short captions and Roman-numeral chapter controls.
5. **Material proof** — A split composition of sticky quality copy and stacked construction close-ups.
6. **Closing conversion** — Ruled signup and contact panels followed by an oversized softly fading object return.

**Transfer:** Lead with human value, then show why the product deserves trust through making, mechanism and details; preserve the image-scale contrasts while adapting the narrative order.

### Company and editorial trust-building with a text-led opening

1. **Belief** — Short manifesto with one ochre italic word and a small plainspoken explanation.
2. **Origin and perspective** — Large centered serif paragraphs and a founder quotation in a narrow column.
3. **Design rationale** — Standalone italic heading and a deliberate explanatory paragraph.
4. **Deeper reading** — A vertical column of image-led article cards with categories and serif dates.
5. **Independent validation** — Publication marks paired with short italic quotes in a two-column cream grid.
6. **Closing conversion** — The same ruled signup/contact footer and fading product image as the product-led layout.

**Transfer:** Use the text-led variant when the reader needs conviction and context more than a demonstration; retain the shared conversion and physical-product finish.

## Writing

Understated, warm and design-literate. Technical confidence is grounded in material choices and ordinary human experiences, not futurist spectacle.

**Do not copy:** Do not reuse Altina or Cubitts identities, product artwork, contact details, founder names or quotations, publication endorsements, material suppliers, percentages, launch dates, testing status or hearing-performance claims. Supply the new product's own verified facts and authorized assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Headlines often speak impersonally; explanation uses we for intent and you for recognizable lived situations. Product language stays human before introducing the mechanism.
- **Rhythm:** Short complete headline statements, often three to eight words, with a meaningful italic turn. Supporting text is one compact paragraph or a few short sentences; detailed editorial prose is longer and calmly argued.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Made for a human activity or desired state, with the key noun emphasized. | 3–6 words | “Made for conversation.”<br>“Style removes stigma.” |
| Section heading | Pair a tangible design quality with a durable benefit. | 4–12 words | “Meticulous design, enduring quality.”<br>“For the places and moments where conversation matters most.” |
| Supporting explanation | Connect a technical fact to a visible or human outcome in direct language. | One short sentence or compact paragraph | “Beamforming microphones focus on who you’re listening to.”<br>“Every detail chosen for how it looks, feels, and lasts” |
| Primary action | A plain verb-led commitment, repeated consistently. | 3–4 words | “Join the Waitlist” |
| Editorial heading | Use simple descriptive labels rather than campaign slogans. | 1–4 words | “Our Design Philosophy”<br>“Press” |

**Words and phrasing to use:** crafted; meticulous; enduring; design; comfort; performance; chosen; looks, feels, and lasts; nearly invisible

**Avoid:** revolutionary; game-changing; disrupt; supercharge; 10x; magic; ultimate solution

**Rules:**

- Introduce advanced mechanisms only after establishing the human activity they support.
- Keep technical captions concrete: name the mechanism and what it does in one sentence.
- Use material and construction facts as proof rather than decorative superlatives.
- End display statements with ordinary punctuation; let italics provide the emphasis instead of exclamation marks.

## Do's and Don'ts

### Do

- Keep the main opening at 110px/1.1, weight 400, with -0.04em tracking and a true italic emphasis.
- Let the 206×46px floating conversion capsule remain visually small against the product stage.
- Use 20px grotesk supporting text with 1.3 line height and 0.01em tracking.
- Give the closing contact address display status at 56px instead of hiding it among tiny utility links.
- Use 24px card padding and 20px gutters for the scoped editorial proof treatments.
- Keep full-bleed imagery and narrow 700px prose columns as distinct scales.
- Return to a full-width, softly fading product detail beneath the 560px footer.
- Ground technical benefits in one specific scene or visible construction detail.

### Don't

- Do not turn the ochre #765d2a text accent into a saturated page-wide action band.
- Do not apply bold sans-serif styling to the 52px and 64px serif section headings.
- Do not round full-screen photograph stages into oversized cards; reserve 8px corners for contained media.
- Do not add elevation shadows to the cream editorial cards; fill and spacing establish their hierarchy.
- Do not reuse the 12px caption recipe for main support copy; that role is 20px.
- Do not build the footer as a dark block with tiny link columns; its light ruled halves and 32px links are deliberate.
- Do not multiply feature icons across the page; the icon vocabulary is primarily small arrows.
- Do not give every paragraph the tight -0.04em display tracking; long serif prose uses -0.02em.

## Motion and responsive

### Motion

**Observed:**

- Product narrative regions and the material-copy column use sticky positioning; a primary conversion is fixed near the bottom center.
- Footer navigation and legal links declare hover color #695732. No action transitions or keyframe animations are established.

**Transfer:**

- Tie changing mechanism scenes to a single sticky stage, keeping the heading, caption and chapter control visually anchored. A static scene should retain the same stage composition.

**Unknown:**

- Scene-change timing, scroll interpolation, transition duration, easing behavior and keyboard focus appearance are unspecified.

### Responsive

**Observed:**

- Stylesheet width thresholds occur at 810px, 1024px and 1440px.

**Transfer:**

- On narrow layouts, preserve the centered promise, italic emphasis, product silhouette and circular-inset conversion; reduce type scale before sacrificing the object.
- Stack material proof and footer halves into reading order, and turn press proof into one column. Keep the final object reprise full width.

**Unknown:**

- Exact narrow-screen type sizes, padding, navigation behavior and sticky-stage adaptation are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
