# Robinhood — electric editorial spectacle

## Overview

A cinematic, predominantly dark identity that pairs literary serif promises with spare grotesk explanations and an electric yellow-green pulse. Product interfaces and sculptural objects become dramatically lit protagonists rather than small supporting thumbnails. It suits ambitious consumer products with a simple entry point and substantial capabilities underneath; light educational and warm metallic premium variants retain the same spacious, direct character.

### Essentials

- Literary promises interrupt a technical world: regular Martina Plantijn at 110px/1 with -0.5px tracking leads the opening; Phonic at 40px/48px and 52px/62px handles explanation.
- The first impression is an immersive stage, not a boxed dashboard: a 900px-tall edge-to-edge dark scene carries a centered two-line headline, a 22px support line and one 44px lime action above the fold.
- Acid color arrives as punctuation and then a flood: #ccff00 marks actions and selected labels against mostly black imagery, with a full-width bright chapter or footer rather than a faint wash everywhere.
- Actions are small capsules beneath enormous promises: 44px height, 36px radius, 32px horizontal padding, regular 16px/24px text; outlined account actions use the same geometry.
- Technology is made tangible: large angled devices, reflective sculpture and isolated objects sit in dark atmospheric environments; use a simple modeled object or luminous SVG diagram when elaborate product media is unavailable.
- The signature visual language joins fine geometric linework to light: include a wireframe illustration or perspective streak field, with a soft dark center protecting the copy.
- The ending is monumental rather than a tidy logo lockup: a 704px cinematic closing call leads toward a ruled, information-rich footer and a near-full-width identity artwork, 1440px × 297px at desktop.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#ccff00` | `--color-lime` | action, accent, background, text, border | Primary conversion capsules, selected display labels, announcement ribbon and full-bleed bright chapters and footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text, surface | Default canvas, navigation and dark image stages; inverse text on light chapters. |
| Warm ink | `#110e08` | `--color-warm-ink` | text, background, action | Ink on lime, warm cinematic backing and inverse capsules on bright chapters. |
| Olive black | `#1c180d` | `--color-olive-black` | background | Warm dark trust chapter with delicate line drawings. |
| Warm rule | `#35322d` | `--color-dark-rule` | border | Fine dividers across the lime footer. |
| Mid rule | `#808080` | `--color-rule` | border | Navigation edge, dark FAQ separators and outlined benefit panels. |
| Muted light | `#bfbfbf` | `--color-muted` | text | Secondary notes on black; also the visible result of white at 75% opacity over black. |
| Light | `#ffffff` | `--color-white` | text, background, border | Primary text on black and the light educational canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| educational libraries | Reading green | `#00c805` | `--color-learning-link` | link | Inline reference links in the white educational footer, distinct from the marketing lime. |
| premium physical-product landing pages | Gold label | `#cfb97d` | `--color-gold` | text, action | Reservation label on black capsules. |
| premium physical-product landing pages | Espresso | `#1c1817` | `--color-espresso` | background | Dark brown material stage. |
| product demonstration panels | Faint dark edge | `#202020` | `--color-faint-edge` | border | Visible white-at-12.5% edge over black in demonstration frames. |
| educational libraries | Slate | `#6a7278` | `--color-slate` | text, border | Muted reading notes and disclosure-band edges on white. |
| educational libraries | Tile edge | `#b4bdc2` | `--color-tile-edge` | border | Library tile outline and chapter divider. |
| premium physical-product landing pages | Warm stone | `#d0c9c1` | `--color-stone` | background | Broad premium chapters and reflective product-stage horizon. |
| educational libraries | Learning gray | `#d3d3d3` | `--color-learning-card` | surface | Backing of tall educational cards; their artwork can supply lime or warmer gray fills. |
| educational libraries | Cool hairline | `#e3e9ed` | `--color-cool-rule` | border | Article list separators. |
| premium physical-product landing pages | Ivory | `#edecdb` | `--color-ivory` | text, border, action | Warm light typography and controls on the metallic dark theme. |

## Typography

- **Phonic** — Marketing headings, paragraphs, navigation and buttons. Open, unornamented grotesk; regular weight remains readable even with tightened display tracking. If unavailable, use **Inter**. Use 400 as the baseline; preserve negative tracking without adding boldness. Font stack: "Phonic", "Inter", Helvetica, system-ui, Arial, sans-serif.
- **Martina Plantijn** — Opening promises and monumental closing calls. Literate, broad old-style serif with substantial curves and restrained contrast. If unavailable, use **Libre Caslon Display**. Use 400; tune wrapping to retain the broad two-line silhouette. Font stack: "Martina Plantijn", "Libre Caslon Display", Georgia, serif.
- **ITC Garamond Std** (only for premium physical-product landing pages) — Oversized opening and chapter headlines. Tall, narrow old-style forms with compact proportions and expressive terminals. If unavailable, use **Cormorant Garamond**. Use 400 and tight leading; do not substitute the wider default serif. Font stack: "ITC Garamond Std", "Cormorant Garamond", Garamond, Georgia, serif.
- **Capsule Sans Display** (only for educational libraries) — Educational opening, chapter headings and support lines. Rounded, friendly sans with moderately dense medium-weight headlines. If unavailable, use **DM Sans**. Font stack: "Capsule Sans Display", "DM Sans", system-ui, Helvetica, Arial, sans-serif.
- **Capsule Sans Text** (only for educational libraries) — Card headings, compact explanations and article links. Friendly grotesk with a generous x-height and straightforward reading texture. If unavailable, use **DM Sans**. Font stack: "Capsule Sans Text", "DM Sans", system-ui, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Martina Plantijn | 400 | 110px | 1 | -0.0045em | fixed | Default centered marketing opening, usually two lines. |
| closing | Martina Plantijn | 400 | 72px | 78px | -0.0139em | fixed | Cinematic closing call and left-aligned product promise. |
| heading-lg | Phonic | 400 | 52px | 62px | -0.0288em | fixed | Major explanatory and reassurance chapter headings. |
| bright-heading | Phonic | 400 | 52px | 62px | -0.0385em | fixed | Compact centered heading on the lime chapter. |
| heading | Phonic | 400 | 40px | 1.2 | -0.025em | fixed | Feature-scene headline and matching colored lead-in. |
| hero-support | Phonic | 400 | 22px | 24px | -0.0114em | fixed | Wide centered support line under the opening promise. |
| item-heading | Phonic | 400 | 22px | 30px | -0.0227em | fixed | Trust captions and FAQ questions. |
| body | Phonic | 400 | 16px | 1.5 | -0.0156em | fixed | Paragraphs, buttons, navigation and footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| premium physical-product landing pages | premium-display | ITC Garamond Std | 400 | 100px | 0.95 | -0.02em | size min(7.8vw, 100px) | Centered premium promises and repeated chapter titles. |
| demonstration-led product pages | demo-promise | Martina Plantijn | 400 | 54px | 58px | -0.0185em | fixed | Smaller promise above a tall central device. |
| procedural product explanations | step-number | Martina Plantijn | 400 | 52px | 58px | -0.0096em | fixed | Large standalone numbers above short participation steps. |
| educational libraries | learning-heading | Capsule Sans Display | 500 | 52px | 60px | -0.0337em | fixed | Educational opening and centered chapter headings. |
| premium physical-product landing pages | premium-benefit | Phonic | 500 | 32px | 1.1 | -0.045em | fixed | Compact benefit headings in ruled three-column rows. |
| educational libraries | learning-card-heading | Capsule Sans Text | 500 | 32px | 1.25 | -0.01em | fixed | Tall card question or concept title. |
| educational libraries | learning-support | Capsule Sans Display | 500 | 24px | 1.5 | -0.01em | fixed | Chapter support lines and horizontal library tile titles. |
| educational libraries | reading-link | Capsule Sans Text | 400 | 18px | 28px | -0.014em | fixed | Article rows on the light canvas. |
| educational libraries | learning-body | Capsule Sans Text | 400 | 15px | 1.6 | -0.007em | fixed | Compact card explanations. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif is for the emotional promise, not the entire content hierarchy. Keep most marketing text at weight 400.
- Display tracking is deliberately tight but not uniform: preserve each recipe rather than applying one global negative letter-spacing.
- A colored 40px lead-in can have the same scale as the following white headline; it is not a tiny uppercase eyebrow.
- Educational typography is a separate medium-weight sans system, not a reason to bold the core marketing theme.

## Layout

**Density:** Airy image-led chapters with compact text clusters; the footer and article lists deliberately become denser.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer link rhythm and small repeated-item gaps. |
| 12px | Button-pair and small flex gaps. |
| 16px | Card title-to-description and stacked reading actions. |
| 18px | Educational tile and tall-card grid gaps. |
| 24px | Headline-to-support gaps, footer cell padding and image-caption separation. |
| 28px | Tall educational card padding. |
| 32px | Capsule horizontal padding and paired-benefit gap. |
| 36px | FAQ side gutters and bright chapter copy-to-action spacing. |
| 48px | Trust-grid column gap. |
| 64px | FAQ vertical padding and article-list closing space. |
| 72px | Bright chapter top space and feature-grid title-to-art distance. |
| 96px | Demonstration heading-to-feature navigation distance. |
| 112px | Educational chapter top space and heading-cluster-to-card distance. |

### Containers and grids

- **marketing-container**: max width 1200px · side padding 24px. Centered content within full-width cinematic bands; imagery may extend all the way to the edges.
- **feature-copy**: max width 400px. Narrow left- or right-aligned copy stack occupying less than half a scene; the object takes the other half.
- **centered-copy**: max width 700px. Centered reassurance headings and performance explanations.
- **faq**: max width 1000px · side padding 36px. Single-column questions and answers.
- **trust-grid**: max width 700px · 2 columns · gap 48px. Four freestanding line drawings and captions; two columns with generous vertical air.
- **footer-split**: 2 columns · gap 0px · side padding 24px. Equal halves: three narrow navigation columns on the left and a dense disclosure column on the right.
- **benefit-pair** (only for service-product explanations): max width 1188px · 2 columns · gap 32px. Equal tall benefit panels with text above isolated metaphor photography.
- **educational-cards** (only for educational libraries): max width 1002px · 3 columns · gap 18px. Three 322px × 540px cards, centered inside the wider reading container.
- **reading-list** (only for educational libraries): max width 798px. Centered article-link lists under educational card groups.
- **library-grid** (only for educational libraries): max width 1002px · 2 columns · gap 18px. 492px × 220px horizontal tiles, with incomplete final row left aligned.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-capsules | 36px |
| educational libraries and premium physical-product landing pages | reading-and-reservation-capsules | 24px |
| educational libraries | educational-cards | 16px |
| educational libraries | library-tiles | 12px |
| service-product explanations | benefit-panels | 20px |
| product demonstration panels | demonstration-frame | 10px |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default marketing canvas and media surround.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The media and page canvas blend without a card edge.

**Transfer:** Keep the image edges dark enough to dissolve into the section.

#### Warm trust band · level 0

**Use:** Reassurance chapter.

**CSS:** `background: #1c180d; color: #ffffff`

**Observed:** Subtle olive warmth distinguishes the band from pure-black product scenes.

#### Lime field · level 0

**Use:** Bright teaching or conversion chapter and default marketing footer.

**CSS:** `background: #ccff00; color: #110e08`

**Observed:** A solid saturated field, not a translucent highlight or gradient wash.

#### Light reading canvas · level 0

**Only for:** educational libraries

**Use:** Long-form browsing chapters.

**CSS:** `background: #ffffff; color: #000000`

#### Premium stone · level 0

**Only for:** premium physical-product landing pages

**Use:** Large statement and benefit chapters.

**CSS:** `background: #d0c9c1; color: #000000`

#### Premium material stage · level 0

**Only for:** premium physical-product landing pages

**Use:** Metallic product demonstrations.

**CSS:** `background: #1c1817; color: #edecdb`

**Observed:** Subtle grain, dark reflective floors and warm pools of light back the objects.

**Transfer:** Match the soft gold glow and dark horizon; exact gradient stops are not essential.

#### Demonstration frame · level 1

**Only for:** product demonstration panels

**Use:** Large landscape product animation.

**CSS:** `background: #000000; border: 1px solid rgba(255, 255, 255, 0.125); border-radius: 10px; overflow: hidden`

**Observed:** The edge is barely brighter than the canvas; no drop shadow.

## Components

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 32px; border: 1px solid #ccff00; border-radius: 36px; background: #ccff00; color: #110e08`

**Text style:** `body` — Phonic 400 · 16px/1.5 · tracking -0.0156em

**Observed:** Text-only capsule with width determined by the label. On the bright chapter, invert to warm ink with white text. A monochrome product opening uses a white-filled version.

**States:** Declared: hover opacity 0.85; focus-visible unspecified.

### Outlined account button

**Use:** Secondary account action in the navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 44px; padding: 0px 32px; border: 1px solid #ccff00; border-radius: 36px; color: #ccff00; background: transparent`

**Text style:** `body` — Phonic 400 · 16px/1.5 · tracking -0.0156em

**Observed:** Sits beside a filled capsule, visually lighter without becoming a text-only link.

**States:** Declared: hover opacity 0.85; focus-visible unspecified.

### Fixed navigation

**Use:** Persistent compact global navigation.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; background: #000000; color: #ffffff; padding: 0px 24px 0px 36px; border-bottom: 1px solid #808080; display: flex; align-items: center`

**Text style:** `body` — Phonic 400 · 16px/1.5 · tracking -0.0156em

**Observed:** Identity left, a single horizontal menu in the middle, locale and paired account actions right. A 45px lime announcement ribbon sits directly below on the core dark theme. Premium controls switch to ivory; educational navigation becomes white with black text and rules.

### FAQ row

**Use:** Objection handling in a narrow dark column.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 12px; padding: 15px 0px; border-bottom: 1px solid #ffffff; color: #ffffff`

**Text style:** `item-heading` — Phonic 400 · 22px/30px · tracking -0.0227em

**Observed:** Question left, solid downward triangle right, roughly 73px collapsed row height. Expanded answers use body text below the question; the triangle points upward. Separator is visually fine and subdued against black.

### Footer trust strip

**Use:** Transition from final call to navigation and disclosures.

**CSS:** `display: flex; align-items: center; padding: 24px; border-top: 1px solid #35322d; border-bottom: 1px solid #35322d; color: #110e08`

**Text style:** `body` — Phonic 400 · 16px/1.5 · tracking -0.0156em

**Observed:** Two half-width cells, 85px tall at desktop: paired underlined reference links on the left, follow label and social icons on the right; a short vertical divider separates the reference links.

**Transfer:** Use relevant trust or policy references alongside a compact social group; continue into Footer split and monumental identity.

### Tall learning card

**Only for:** educational libraries

**Use:** A self-contained foundational concept link.

**CSS:** `position: relative; width: 322px; height: 540px; padding: 28px; border-radius: 16px; background: #d3d3d3; color: #000000; overflow: hidden`

**Text style:** `learning-card-heading` — Capsule Sans Text 500 · 32px/1.25 · tracking -0.01em

**Observed:** Question at the top, compact explanation beneath, geometric illustration in the lower half. Artwork supplies the actual lime or warm gray backing in different subject groups.

**Transfer:** Keep the title and summary live; use a single thin-line conceptual diagram below, not a miniature interface.

### Article row

**Only for:** educational libraries

**Use:** Secondary reading links beneath card groups.

**CSS:** `display: flex; justify-content: space-between; padding: 16px 0px; border-top: 1px solid #e3e9ed; color: #000000`

**Text style:** `reading-link` — Capsule Sans Text 400 · 18px/28px · tracking -0.014em

**Observed:** A full-width title and a small pale right chevron; about 61px tall, with a final rule closing the list.

### Library tile

**Only for:** educational libraries

**Use:** Broad horizontal link to a reference concept.

**CSS:** `position: relative; width: 492px; height: 220px; padding: 24px; border: 1px solid #b4bdc2; border-radius: 12px; overflow: hidden`

**Text style:** `learning-support` — Capsule Sans Display 500 · 24px/1.5 · tracking -0.01em

**Observed:** Title sits upper left; a black wireframe sculpture rises at lower right and is cut by the lower edge. Pale image backing rather than a heavy colored card.

### Benefit panel

**Only for:** service-product explanations

**Use:** Paired product advantages made tangible with visual metaphors.

**CSS:** `display: flex; flex-direction: column; align-items: center; width: 578px; height: 802px; border: 1px solid #808080; border-radius: 20px; overflow: hidden; background: #000000; color: #ffffff`

**Text style:** `heading` — Phonic 400 · 40px/1.2 · tracking -0.025em

**Observed:** Centered heading and short support at the top; a large isolated object fills the lower portion. Tiny qualifying note remains secondary.

### Reservation button

**Only for:** premium physical-product landing pages

**Use:** Premium waitlist or reservation action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 36px; border-radius: 24px; background: #000000; color: #cfb97d`

**Observed:** A small bold 14px/22px Phonic label with -0.1px tracking; a terms link remains separate, not squeezed into the button.

## Imagery and graphics

### Cinematic product scene

**Use:** Hero and full-width feature chapters.

**Observed:** A large product or abstract data graphic occupies much of a dark scene. Opening data marks sit behind white serif type; later scenes show angled monitors and phones with real interface detail, dark reflective frames, cool gray sky or lavender horizon light. Copy occupies a much narrower area than the media.

**Transfer:** Stage one credible product view as the protagonist. When no physical device exists, place a simplified meaningful diagram into the same dark, luminous space; avoid inventing dense interface detail.

**Build:** Use a black full-bleed layer. Add a wide low-opacity cool-light ellipse behind the object with a 100px blur, fading to transparent edges. Overlay the product with realistic edge highlights; add a dark radial scrim beneath text. For a diagram fallback, draw a thin SVG path across the lower two thirds in lime, with one softly blurred lime endpoint and ample black around the heading.

### Geometric wireframes

**Use:** Reassurance, capability explanations and educational concept artwork.

**Observed:** Fine pale strokes form impossible cubes, nested rings, toggles and stepped pyramids on dark grounds; on pale or lime grounds the strokes become black. Drawings are deliberately bigger than utility icons, around 200px square in the reassurance grid.

**Transfer:** Translate an abstract benefit into one geometric construction, preserving the thin line and low visual mass.

**Build:** In a 240px SVG viewBox, draw repeated ellipses, offset isometric polygons or stacked rectangles with fill none and a 1px stroke. Use white at about 55% opacity on dark bands or black at about 65% on light cards; highlight only one plane or ring in lime. Keep 20px clear around the silhouette.

### Perspective light field

**Use:** Signature cinematic closing atmosphere and educational opening background.

**Observed:** Many fine white streaks recede over black, spreading toward the viewport edges. The center stays darker so a large serif statement and lime capsule remain readable; another treatment resolves into small distant points.

**Transfer:** Use this field as the recurring atmosphere even when the product has no cinematic assets.

**Build:** Create an SVG covering the section with 8–12 staggered rows of 1px white strokes. Fan the outer columns away from a vanishing point near the upper center; vary streak lengths from 10px to 70px and opacity from 0.15 to 0.65. Overlay a black radial ellipse covering about 60% of the center. Keep the text and button on a separate front layer.

### Monumental identity

**Use:** Default marketing-page ending.

**Observed:** A wide identity silhouette fills nearly the whole page width in a 297px-high artwork band. Dark ink sits on lime by default; dark monochrome and premium endings use lime or ivory lettering on black. The educational ending instead remains a white ruled information grid.

**Transfer:** Use the new identity as custom vector lettering or a carefully fitted word sculpture. Preserve the near-edge-to-edge scale and weight rather than a conventional small footer logo.

**Build:** Fit a single heavy sans word inside an SVG viewBox with roughly 24px side breathing room at 1440px width. Keep letter contours crisp and the artwork about 300px tall; scale the vector uniformly, without stretching individual letters.

### Reflective monochrome sculpture

**Only for:** procedural product explanations

**Use:** Left-copy product opening with a sculptural right half.

**Observed:** Tall open rectangular metal columns cluster into a rising skyline, cropped at the lower edge. Silver faces, black tops and fine bright edges emerge from an almost-black backdrop.

**Transfer:** Model a small family of simple extruded shapes that communicates the new product's mechanism.

**Build:** Arrange 12–16 isometric rectangular prisms in staggered heights on the right half; make tops nearly black, front faces medium gray and side faces darker. Add hairline white edge reflections and a faint gray radial glow behind the cluster.

### Premium metallic still life

**Only for:** premium physical-product landing pages

**Use:** Opening product, virtual-object chapter and two-up benefit scenes.

**Observed:** Gold objects float or stand on polished dark floors: a beveled card, overlapping translucent cards, small figurines and keys. Warm rim light, softly reflected silhouettes and fine metal grain create luxury without bright decorative colors.

**Transfer:** Render the new object with brushed metal, a restrained warm highlight and a plausible contact reflection. Minimum version: one carefully lit object on an espresso-to-stone horizon, not a generic gold gradient rectangle.

**Build:** Layer an espresso canvas, a broad warm radial light behind the object and a blurred dark floor reflection beneath it. Give the object a narrow ivory rim, a subtle gold face gradient and very low-opacity noise; fade all edge lighting into the background.

### Icons

**Observed:** Utility icons are restrained monochrome SVGs: 20px social marks, 12px dropdown chevrons, 22px × 13px solid FAQ triangles and small 16px information symbols. Larger 200px line illustrations are a different visual layer, not enlarged navigation icons.

**Transfer:** Use filled monochrome utility symbols for actions and thin geometric constructions for concepts. Invert icon color with the surface; avoid multicolor icon badges.

## Section recipes

How recurring sections are built.

### First screen: Immersive promise opening

**Observed:** A fixed 64px black navigation and 45px lime ribbon cap a 900px full-width dark media stage. Behind the copy, a luminous data path crosses the lower scene while dim interface markings occupy the upper center. The white 110px/110px serif promise wraps into two centered lines about 568px wide, with a wider support line around 825px and one Primary button below. Layers run from warm-black backing, through full-bleed media and a subtle dark text scrim, to headline, support and capsule. Within the first 900px the full headline, support, action and main graphic are visible; the last part of the stage and the next chapter remain below.

**Transfer:** Use one short promise and an expansive scene that makes the product feel substantial. Without source-quality media, use Cinematic product scene's luminous diagram fallback behind the centered type. A focused procedural product can open with a left-aligned 72px serif promise and right-side sculpture; a demonstration-led service uses the 54px promise over a tall central device; educational browsing uses a compact 550px streak-backed sans opening.

**Avoid:** Do not turn the first screen into a rounded hero card, a crowded benefit grid or a tiny headline beside a floating screenshot.

**Text style:** `display` — Martina Plantijn 400 · 110px/1 · tracking -0.0045em

### Full-bleed feature scene

**Observed:** An 800px-tall image chapter places a roughly 400px copy stack to one side and a large device or material object opposite. A 40px lead-in can share scale with the main headline; support is 16px/24px, followed by Primary button. Small qualifying text sits near the lower edge rather than competing with the headline.

**Transfer:** Alternate the copy side where appropriate and tell one capability per scene; use product detail and atmosphere instead of a repeated card template.

**Text style:** `heading` — Phonic 400 · 40px/1.2 · tracking -0.025em

### Reassurance constellation

**Observed:** Warm trust band carries a centered 52px heading over a two-by-two grid of 200px line drawings. Each is followed by a centered 22px/30px caption with 24px separation; the columns are 48px apart and the items feel freestanding rather than boxed.

**Transfer:** Choose four concise reassurance ideas and turn each into a distinct wireframe metaphor.

**Text style:** `heading-lg` — Phonic 400 · 52px/62px · tracking -0.0288em

### Bright teaching chapter

**Observed:** Lime field carries a centered 576px-wide 52px heading, support 24px below, then an inverse Primary button after 36px. A roughly 500px-wide product preview rises into the lower part of the 745px band.

**Transfer:** Create a single vivid interruption for a learning or activation benefit. Keep text dark and the preview secondary to the centered statement.

**Text style:** `bright-heading` — Phonic 400 · 52px/62px · tracking -0.0385em

### FAQ column

**Observed:** A centered 52px heading introduces a 1000px-wide column of FAQ rows with generous top clearance. Closed questions form a crisp ruled rhythm; expanded body copy stays aligned to the question rather than appearing in a separate raised card.

**Transfer:** Group genuine objections into answerable questions, using the same dark canvas and thin rules.

**Text style:** `item-heading` — Phonic 400 · 22px/30px · tracking -0.0227em

### Cinematic closing call

**Observed:** A 704px-wide-screen chapter centers a 72px serif statement and Primary button over Perspective light field. A soft dark center protects the words, with no explanatory paragraph required.

**Transfer:** Finish the product narrative with a short invitation and one action. Retain the atmospheric field and monumental type even with a static implementation.

**Text style:** `closing` — Martina Plantijn 400 · 72px/78px · tracking -0.0139em

### Footer split and monumental identity

**Observed:** Footer trust strip leads to equal page halves: three link columns left and disclosures right, with 24px padding and an 8px link rhythm. The default Lime field continues behind both, ending with Monumental identity artwork. Monochrome product endings switch to black with light links; premium endings use ivory. Educational pages end in a white, black-ruled two-column grid with no giant identity band.

**Transfer:** Let real navigation and necessary disclosures determine height; retain the emphatic identity ending for marketing pages, and the ruled information ending for a learning portal.

### Numbered process

**Only for:** procedural product explanations

**Observed:** Centered title and action precede three equal columns in a 1200px container. Large serif numerals sit above short centered step labels; subtle vertical lines distinguish the columns without card backgrounds.

**Transfer:** Reduce onboarding to a few real actions, using typographic numbers rather than badges.

**Text style:** `step-number` — Martina Plantijn 400 · 52px/58px · tracking -0.0096em

### Demonstration and proof

**Only for:** demonstration-led product pages

**Observed:** A centered promise sits above a tall device. Later, two ruled feature labels sit side by side above a 1080px landscape Demonstration frame, with the inactive label subdued. Fine dashed vertical trails connect large sections. Quantified proof uses a large plain-language heading, short explanation and a wide restrained chart rather than a giant isolated statistic.

**Transfer:** Move from a tangible interface action to its measurable value. Keep chart annotation modest and qualifiers adjacent to claims.

### Premium material chapters

**Only for:** premium physical-product landing pages

**Observed:** 100px/95px serif headlines sit centered above enormous metallic objects. Stone statement chapters contrast with espresso demonstrations; a warm curved horizon joins the themes. Three ruled benefit columns and a small perks list provide compact information between the immersive scenes.

**Transfer:** Build premium value through material realism and scale, then use plain language and small icons for practical benefits.

**Text style:** `premium-display` — ITC Garamond Std 400 · 100px/0.95 · tracking -0.02em

### Educational chapter and reading list

**Only for:** educational libraries

**Observed:** On Light reading canvas, a centered 52px heading and 24px support introduce three Tall learning cards after 112px of air. A narrower Article row list follows under its own heading, with black reading capsules below and a long thin chapter divider. The final library becomes a two-column Library tile grid and a centered browse action.

**Transfer:** Repeat the same teaching rhythm for distinct concepts without importing marketing serif headlines into every chapter.

**Text style:** `learning-heading` — Capsule Sans Display 500 · 52px/60px · tracking -0.0337em

## Page flow

**Storyline:** Broad promise → tangible product demonstration → practical capabilities and reassurance → explanation or objections → cinematic invitation → information-rich identity ending.

### Broad consumer-product marketing landing page

1. **Promise** — Centered serif statement over luminous full-bleed product media.
2. **Capability chapters** — Alternating image scenes with narrow side copy.
3. **Reassurance** — Warm dark line-illustration grid.
4. **Activation** — Lime teaching chapter with product preview.
5. **Closing call** — Serif invitation over receding light marks.
6. **Reference ending** — Lime split footer and enormous identity artwork.

**Transfer:** Use a few distinct scenes to make the breadth legible, not a wall of equal feature cards.

### Focused access or onboarding product page

1. **Promise** — Left serif copy opposite reflective abstract sculpture.
2. **Process** — Three large numbered steps.
3. **Objection handling** — Long dark ruled question list.
4. **Closing call** — Atmospheric educational invitation.
5. **Reference ending** — Separate risk explanation then black footer and lime identity.

**Transfer:** Explain participation simply before detailed questions; preserve the sculptural opening and restrained monochrome treatment.

### Premium physical-product launch or reservation page

1. **Promise** — Narrow serif headline above a dramatically lit metal object.
2. **Value** — Giant stone-background statement and compact ruled benefits.
3. **Capability chapters** — Espresso scenes with metallic metaphors and large objects.
4. **Closing call** — Floating product over stone with a reservation capsule.
5. **Reference ending** — Stone disclosure area, black footer and ivory identity.

**Transfer:** Use tangible material quality as the proof of premium positioning, with concise practical information between scenes.

### Managed or complex service product explanation

1. **Promise** — Small centered serif statement and central device.
2. **Product demonstration** — Ruled feature selector above a large animation frame.
3. **Capabilities** — Three wireframe concepts and paired photographic benefit panels.
4. **Quantified proof** — Low-fee comparison chart and performance explanation with qualification.
5. **Objection handling** — Ruled FAQ with expandable answers.
6. **Closing call** — Large serif invitation above a lime split footer and identity.

**Transfer:** Balance interface credibility, conceptual metaphors and qualified proof before asking for commitment.

### Educational library and discovery portal

1. **Orientation** — White navigation over a short black streak-field opening.
2. **Teaching chapters** — Centered sans introduction and three tall illustrated concept cards.
3. **Deeper reading** — Narrow ruled article lists and black browse capsules.
4. **Reference discovery** — Horizontal library tiles.
5. **Reference ending** — Muted disclosures and a white ruled information footer.

**Transfer:** Use repeated learning modules rather than cinematic product chapters; keep line art and spacing as the connective identity.

## Writing

Confident, approachable and practical, with ambitious promises grounded in ordinary language. The tone can be playful in a short line but becomes precise when explaining mechanisms, fees or limitations.

**Do not copy:** Do not reuse Robinhood names, marks, slogans, proprietary artwork, quoted claims, financial returns, rates, offers or numerical promises. Examples show cadence only; new product claims require their own substantiation.

- **Addressing the reader:** Speak to the reader as you and your. Use we for reassurance and operational explanation; name the product when explaining what it does.
- **Rhythm:** Short, direct headline clauses followed by one or two informative sentences. Sentence fragments and paired statements create rhythm; explanatory copy can be longer without turning into jargon.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active outcome in everyday words, with one dominant idea. | 5–10 words | “Trade All in One Place”<br>“Buy shares at the IPO price.” |
| Paired promise | Two linked clauses: effort by the service, relief for the reader. | 8–13 words | “Strategy that works harder. So you don’t have to.” |
| Support | Explain the concrete action and benefit without a second slogan. | One or two sentences | “Pay with disposable card numbers for smarter, more private spending.” |
| Reassurance | We plus a specific protective action. | 8–14 words | “We work hard to keep your data safe and secure.” |
| Teaching | A direct question or friendly invitation into an unfamiliar concept. | 3–10 words | “What is an investment?”<br>“New to futures? We got you.” |
| Action | A short verb-led instruction, with the destination named when needed. | 2–5 words | “Get started”<br>“Reserve your spot”<br>“See Library” |

**Words and phrasing to use:** get started; learn; your; more; built for; take control; right in the app; keep; how

**Avoid:** revolutionary ecosystem; unparalleled synergies; guaranteed success; effortlessly transform everything; corporate throat-clearing

**Rules:**

- State the benefit before the mechanism, then make the mechanism understandable.
- Use concrete verbs and familiar nouns instead of abstract platform language.
- Keep qualifying information close to consequential claims, visually secondary but readable.
- Let educational questions sound like something a person would ask.
- Use compact action labels rather than enthusiastic full-sentence buttons.

## Do's and Don'ts

### Do

- Keep the core opening serif regular at 110px/110px with -0.5px tracking.
- Give feature copy a narrow 400px measure inside an expansive scene.
- Use lime at full strength for conversion capsules and deliberate full-width fields.
- Keep default capsules at 44px tall with 32px horizontal padding.
- Separate conceptual 200px wireframes from small 16–24px utility symbols.
- Use 1px edges and rules instead of elevated card shadows.
- Allow the footer to be dense while keeping 24px cell padding and a steady 8px link rhythm.
- Maintain 112px chapter breathing room around educational introductions and card groups.

### Don't

- Do not use bold sans as the default substitute for the literary serif promise.
- Do not soften the lime field into a pastel or spread lime into every paragraph.
- Do not make all image chapters into bordered cards with 16px corners; most scenes are full bleed.
- Do not add drop shadows to dark panels; the separation comes from a thin edge and lighting.
- Do not turn the 22px reassurance captions into uppercase micro-labels.
- Do not use the premium Garamond and gold reservation styling on an ordinary product page.
- Do not force the white educational footer to end in a giant marketing identity band.
- Do not inflate small action text into large display type; the contrast with monumental headlines is intentional.

## Motion and responsive

### Motion

**Observed:**

- Marketing capsules declare hover opacity 0.85; many dark navigation links change to lime on hover.
- Opacity transitions of 200ms ease-out and a transform transition of 0.4s are declared on a small set of elements.
- Hero and closing atmospheres are video-based; product demonstrations also use video.

**Transfer:**

- Carry the luminous stages and perspective light field into motion when appropriate; a static version should preserve their depth and dark center.
- Keep hover changes restrained to the declared opacity or color treatment rather than introducing large scale effects.

**Unknown:**

- Precise video timing, scroll choreography and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared breakpoint families include 767px/768px, 1023px/1024px and 1279px/1280px.
- The premium serif display uses min(7.8vw, 100px).

**Transfer:**

- On narrow screens, preserve the product-stage hierarchy: headline first, readable support and capsule, then the main object. Recompose the object instead of shrinking the entire desktop scene.
- Stack paired benefit panels and educational card columns while keeping each illustration and title together; these are adaptation recommendations.

**Unknown:**

- Exact mobile typography, navigation collapse, footer stacking and responsive media choices are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
