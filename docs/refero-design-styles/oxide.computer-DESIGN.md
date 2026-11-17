# Oxide — the instrument room

## Overview

An industrial, dark marketing language that makes complex products feel tangible and operable. Cool charcoal, silver-gray type and concentrated phosphor green combine a regular neo-grotesk with small equipment-like monospace labels. Dramatic hardware renders, cropped interfaces and character-based diagrams carry the argument; spacious chapters surround dense technical proof. It suits infrastructure, developer tools and sophisticated physical or software systems.

### Essentials

- The opening is a working machine, not a billboard: a 60px navigation strip above an asymmetric stage, a 65px/1 regular headline low on the left and a tall product object occupying roughly the right 40%. A small operational panel and connector line balance the object; use a purposeful system diagram when no physical product exists.
- Headlines sound and look like engineering statements: SuisseIntl at weight 400, 65px with -0.025em tracking for the main promise, 50px/1.1 with -0.02em tracking for chapters. Bright #dedede assertions share a line or pair with #818284 explanations.
- Color behaves like a live signal inside dark equipment: #0b0e12 dominates the page, #181a1d and #303235 stage media, and #00d892 is concentrated in actions, status marks and small diagram details rather than full-page bands.
- Actions look like instrument keys: uppercase 12px/16px mono with 0.6px tracking, 32px height, 2px corners and a deep #002923 fill. The larger 40px version belongs to forms, not oversized hero pills.
- Product proof is diagrammed as well as pictured: include figure-number captions, fine 1px rules, a character-grid or ASCII graphic and dark operational panels. If detailed renders are unavailable, a sharply constructed SVG schematic with a real state panel supplies the same technical specificity.
- The closing invitation is a two-tone statement beside a compact field of luminous characters: 50px/55px heading, bright promise above a muted invitation, two small actions underneath. The footer returns to a muted two-line statement on the left, three compact link columns on the right and a newsletter field at its base.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live green | `#00d892` | `--color-accent` | accent, action, text | Primary action text, active states and signal details. |
| Deep green well | `#002923` | `--color-green-well` | surface | Primary buttons and icon backplates. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Recessed green | `#00b77d` | `--color-green-link` | link | Inline mono exploration links; brighten to live green on hover. |
| Active green well | `#003e32` | `--color-green-hover` | surface, border | Primary-action hover and fine green feature dividers. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Raised silver | `#dedede` | `--color-text` | text | Primary headings, emphasized phrases and hovered links. |
| Body silver | `#bababb` | `--color-body` | text | Default body copy and selected technical descriptions. |
| Secondary gray | `#a3a4a5` | `--color-secondary` | text | Supporting paragraphs, navigation and links. |
| Receding gray | `#818284` | `--color-tertiary` | text | Muted headline halves, descriptive card copy and captions. |
| Annotation gray | `#5d5e61` | `--color-quaternary` | text | Recessive figure numbers and inactive technical annotations. |
| Texture gray | `#434547` | `--color-texture` | text, accent | Character textures and background diagram marks, not paragraph copy. |
| Graphite edge | `#303235` | `--color-edge` | border, surface | Input and technical-panel edges; brighter neutral media stages. |
| Fine divider | `#1f2124` | `--color-rule` | border, surface | Card outlines, footer rule and navigation hover fill. |
| Equipment panel | `#181a1d` | `--color-panel` | surface | Media cards and operational panels. |
| Subtle raised plane | `#131519` | `--color-raised` | surface | Card hover plane and comparison panels; also the FAQ backing. |
| Blue-black canvas | `#0b0e12` | `--color-canvas` | background | Dominant page background and deepest inset panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| careers and culture content | Human signal amber | `#febb55` | `--color-amber` | text, accent | People-focused notice text and small process icons. |
| careers and culture content | Amber well | `#271f00` | `--color-amber-well` | surface | People-focused notice and icon backplates. |

## Typography

- **SuisseIntl** — All marketing headlines, body copy and navigation lists. Neutral neo-grotesk with open counters, regular weight and compact large-scale spacing. If unavailable, use **Inter**. Use 400 for nearly all text and retain negative headline tracking. Font stack: "SuisseIntl", "Inter", -apple-system, system-ui, Helvetica, Arial, sans-serif.
- **GT America Mono** — Navigation controls, action labels, figure captions and character graphics. Technical, even-width lettering with distinctive alternate forms. OpenType features: "calt" 0, "ss02", "ss03", "ss06", "ss07", "ss08", "ss09". If unavailable, use **IBM Plex Mono**. Use 400 and preserve uppercase tracking. Font stack: "GT America Mono", "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SuisseIntl | 400 | 65px | 1 | -0.025em | Default marketing opening promise, usually two lines. |
| heading | SuisseIntl | 400 | 50px | 1.1 | -0.02em | Main chapter statements, closing invitation and muted footer statement. |
| heading-compact | SuisseIntl | 400 | 36px | 42px | -0.013em | Editorial statement paragraphs and smaller section headings. |
| lead | SuisseIntl | 400 | 25px | 32px | normal | Lead explanations, emphasized benefit phrases and prominent list titles. |
| feature-heading | SuisseIntl | 400 | 20px | 26px | 0.009em | Headings inside large visual benefit cards. |
| card-heading | SuisseIntl | 400 | 18px | 24px | 0.014em | Small feature-card titles and medium supporting statements. |
| body | SuisseIntl | 400 | 16px | 22px | 0.021em | Default descriptive paragraphs and technical rows. |
| small | SuisseIntl | 400 | 14px | 18px | 0.03em | Footer links, supporting lists and newsletter field. |
| label | GT America Mono | 400 | 12px | 16px | 0.053em, uppercase, features "calt" 0, "ss02", "ss03", "ss06", "ss07", "ss08", "ss09" | Navigation, actions, figure numbers and equipment-style captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| solution pages | centered-display | SuisseIntl | 400 | 65px | 0.9 | -0.025em | Centered solution opening with a short single-line promise. |
| product detail and solution pages | detail-heading | SuisseIntl | 400 | 52px | 58px | -0.021em | Technical product titles and solution chapter headings. |
| careers and culture content | question | SuisseIntl | 500 | 18px | 24px | 0.011em | FAQ question controls and process stage titles. |

**Notes:**

- Use weight and size sparingly: most hierarchy comes from scale and gray level, not boldness. At 36px tracking is -0.013em, tightening to -0.025em at 65px.
- Allow bright and muted text to occupy the same sentence or successive headline lines; use contrast to distinguish the assertion from its explanation.
- Mono is the equipment marking layer, not the main reading voice. Preserve its alternate-character feature settings when the family supports them.

## Layout

**Density:** Airy between chapters and compact within technical panels; long stretches of dark canvas separate tightly grouped facts.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Small card title-to-copy separation. |
| 8px | Action groups, icon-to-label spacing and form control gaps. |
| 12px | Horizontal button padding and small internal stacks. |
| 16px | Larger button padding and footer column gaps. |
| 20px | Default card padding and grid gutters. |
| 32px | Technical side-panel padding and footer base spacing. |
| 40px | Desktop outer gutters and medium content stacks. |
| 56px | Headline-to-major-media separation. |
| 60px | Culture opening image-to-text separation. |
| 80px | Product title-to-media and large subchapter gaps. |
| 128px | Default major chapter separation. |
| 192px | Breathing space before the shared footer. |

### Containers and grids

- **Content container**: max width 1200px · side padding 40px. Centered desktop chapters; at 1440px, the content starts 120px from each side.
- **Wide stage**: max width 2000px · side padding 40px. Navigation and marketing opening use the broader viewport rather than the narrower chapter column.
- **Underlying grid**: 12 columns · gap 20px. Common chapter alignment system; media, text and cards span several tracks.
- **Three-up cards**: 3 columns · gap 20px. Equal 387px cards within the content container.
- **Paired media**: 2 columns · gap 20px. Two 590px columns; independent vertical stacks create an uneven visual rhythm.
- **Reading measure**: max width 480px. Support text inside large cards and narrow editorial columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Small controls and fields | 1px |
|  | Primary buttons | 2px |
|  | Media and feature cards | 4px |
| careers and culture content | FAQ enclosure | 6px |
| careers and culture content | Culture notice | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page field.

**CSS:** `background: #0b0e12; color: #bababb`

#### Quiet outline · level 1

**Use:** Default benefit and linked cards.

**CSS:** `background: #0b0e12; border: 1px solid #1f2124; border-radius: 4px; box-shadow: none`

**Observed:** The edge provides organization without a raised floating-card effect.

**Transfer:** Let content and fine dividers establish hierarchy.

#### Media plane · level 1

**Use:** Product imagery, terminal modules and illustrated panels.

**CSS:** `background: #181a1d; border-radius: 4px; overflow: hidden`

**Observed:** Some metal close-up stages use #303235 for a brighter tonal counterpoint.

**Transfer:** Use neutral gray light and focused green detail within the illustration rather than decorating the whole section.

#### Navigation glass · level 2

**Use:** Sticky 60px navigation backing.

**CSS:** `background: rgba(11, 14, 18, 0.85); border-bottom: 1px solid #1f2124; backdrop-filter: blur(12px)`

**Observed:** A low-contrast translucent strip sits above the scrolling page.

**Transfer:** Keep the content legible without a heavy opaque toolbar.

#### Culture FAQ plane · level 1

**Only for:** careers and culture content

**Use:** Long accordion enclosure.

**CSS:** `background: #131519; border: 1px solid #1f2124; border-radius: 6px; overflow: hidden`

#### Culture notice well · level 1

**Only for:** careers and culture content

**Use:** Single compact eligibility or availability notice.

**CSS:** `background: #271f00; color: #febb55; border-radius: 9999px; padding: 8px`

## Components

### Navigation bar

**Use:** Persistent global orientation and conversion.

**CSS:** `height: 60px; position: sticky; top: 0px; z-index: 20`

**Text style:** `label` — GT America Mono 400 · 12px/16px · tracking 0.053em · uppercase

**Observed:** Identity on the left, a compact central set of menus and two actions aligned right. Navigation glass forms the separate backing layer.

**Transfer:** Keep category labels short; reserve right-side emphasis for contact and trial paths.

### Navigation item

**Use:** Category menus and top-level destinations.

**CSS:** `display: flex; align-items: center; padding: 8px 12px; height: 32px; border-radius: 1px; color: #a3a4a5`

**Text style:** `label` — GT America Mono 400 · 12px/16px · tracking 0.053em · uppercase

**Observed:** Small chevrons follow menu labels; adjacent menu controls have a 4px gap.

**States:** Declared: hover background-color #1f2124 and color #dedede; focus-visible solid 1px outline with 0px offset and #009366 color.

### Primary button

**Use:** Contact and other high-intent actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #002923; color: #00d892; height: 32px; padding: 0px 12px; border-radius: 2px; border: 1px solid rgba(0, 216, 146, 0.05)`

**Text style:** `label` — GT America Mono 400 · 12px/16px · tracking 0.053em · uppercase

**Observed:** Small rectangular key with a faint edge, paired with a neutral secondary action rather than scaled into a giant hero control.

**States:** Declared: hover background-color #003e32; focus-visible solid 1px outline with 0px offset and #009366 color.

### Subscribe button

**Use:** Submit a newsletter form.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #002923; color: #00d892; height: 40px; padding: 0px 16px; border-radius: 2px`

**Text style:** `label` — GT America Mono 400 · 12px/16px · tracking 0.053em · uppercase

**Observed:** A taller form variant placed 8px after the input.

**States:** Declared: hover background-color #003e32; focus-visible solid 1px outline with 0px offset and #009366 color.

### Exploration link

**Use:** Text-level link beneath a technical explanation.

**CSS:** `display: flex; align-items: center; color: #00b77d; margin-top: 16px`

**Text style:** `label` — GT America Mono 400 · 12px/16px · tracking 0.053em · uppercase

**Observed:** An inline 12px right-pointing triangle follows the text and moves right on hover.

**States:** Declared: hover color #00d892; focus-visible solid 1px outline with 0px offset and #009366 color.

### Linked benefit card

**Use:** Compact navigable use cases or capabilities.

**CSS:** `display: block; padding: 20px; border: 1px solid #1f2124; border-radius: 4px`

**Text style:** `card-heading` — SuisseIntl 400 · 18px/24px · tracking 0.014em

**Observed:** Short heading with a green right-pointing triangle, then body copy separated by 4px. Three columns share the same edge treatment.

**States:** Declared: hover background-color #131519; focus-visible solid 1px outline with 0px offset and #009366 color.

**Transfer:** State a benefit, then a mechanism or bounded use case.

### Visual benefit card

**Use:** Large illustrated capability proof.

**CSS:** `position: relative; background: #303235; border-radius: 4px; overflow: hidden`

**Text style:** `feature-heading` — SuisseIntl 400 · 20px/26px · tracking 0.009em

**Observed:** Text occupies a 20px inset at the top, while a tightly framed product image and dark operational overlays fill the lower portion. A darker media-plane variant sits alongside it.

**Transfer:** Make each image explain the capability instead of supplying unrelated atmosphere.

### Newsletter field

**Use:** Email entry in a subscription strip or footer.

**CSS:** `height: 40px; padding-left: 12px; border: 1px solid #303235; border-radius: 1px; background: #0b0e12; color: #dedede`

**Text style:** `small` — SuisseIntl 400 · 14px/18px · tracking 0.03em

**Observed:** A single-line field stretches to fill the available width; no large label or rounded form capsule surrounds it.

### Footer link

**Use:** Dense grouped navigation lists.

**CSS:** `display: inline-block; color: #a3a4a5`

**Text style:** `small` — SuisseIntl 400 · 14px/18px · tracking 0.03em

**Observed:** Regular sans links beneath mono category labels, arranged in three narrow columns.

**States:** Declared: hover color #dedede; focus-visible solid 1px outline with 0px offset and #009366 color.

### FAQ question

**Only for:** careers and culture content

**Use:** Long-form practical objections.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 18px; min-height: 60px; width: 100%; text-align: left; color: #a3a4a5`

**Text style:** `question` — SuisseIntl 500 · 18px/24px · tracking 0.011em

**Observed:** Each full-width row has a fine bottom rule and a small right-facing disclosure mark at the far edge, inside Culture FAQ plane.

**States:** Declared: hover is unspecified on the button; focus-visible outline-style none with 0px offset, 1px outline-width and #9a6c00 outline-color.

## Imagery and graphics

### Industrial product stage

**Use:** Primary opening object and large product chapters.

**Observed:** Three black metal racks stand in a slight three-quarter view with luminous green internal elements and narrow silver highlights. The object is isolated on the dark field, not in a rounded photographic frame. Low-right gray illumination and extremely subtle technical texture establish depth.

**Transfer:** Use a real object or a crisp product-system composition, with dark structural masses, restrained highlights and a few active green elements. For software-only products, use a large operational schematic with a small authentic interface state rather than a generic device mockup.

**Build:** Layer a dark base, a 320deg diagonal gray gradient concentrated in the lower-right quarter, and the isolated object above it. Keep the center-left nearly black. Add a thin 1px elbow connector between the small top-left panel and the main object. Match the soft light; exact gradient stops are not essential.

### Technical character field

**Use:** Signature background texture, chapter separators and closing-call artwork.

**Observed:** Tiny mono punctuation, bars, dots and plus signs form ordered fields. Green dominates the closing block, with a few violet characters; other fields are almost invisible gray. The hero texture fades away before it reaches the headline.

**Transfer:** Include this device on every marketing page. Use characters related to the new system's operation while maintaining the precise lattice and restrained contrast.

**Build:** Create an SVG text lattice with repeated mono dots, colons, pluses or vertical bars. For a closing block, use a roughly 220px-wide field of 16 columns and 8 rows; color most glyphs rgba(0,216,146,0.35) and a few rgba(197,138,255,0.8). For backdrop texture, use gray at low alpha, tile a 247px by 285px area and apply a diagonal opacity mask so it disappears toward text. Avoid blur on glyphs.

### Operational proof collage

**Use:** Capability cards and larger product demonstrations.

**Observed:** Dark terminals, tables, utilization graphs and small popovers sit over close-up metal surfaces or charcoal backings. Green status marks, fine rules and small labels make the images feel functional. Some interface scenes fade into the page at their lower edge.

**Transfer:** Show a plausible, limited task with one useful state, not an entire tiny dashboard. Minimum acceptable treatment is a native-looking table or chart backed by a strong product detail image.

**Build:** Place two or three near-square dark panels over the lower half of a neutral product image. Use 1px gray dividers, one step-line green chart or a few status cells, and restrained green backplates. Add a canvas-colored bottom fade only when the scene should dissolve into the page.

### Engineering explorer

**Use:** Deep product explanation after broader benefits.

**Observed:** A bright silver three-quarter component floats diagonally over a ruled dark grid. Numbered green markers connect the object to a right-side list. The 700px-wide visual and 500px-wide explanation share a 636px-tall ruled enclosure; a figure caption is pinned to the lower edge.

**Transfer:** Use an annotated product diagram or static render if interactive 3D is unavailable. Keep the object readable, the perspective coherent and the callouts few.

**Build:** Draw 1px #1f2124 grid lines in SVG at roughly 29px horizontal and 64px vertical intervals. Place a transparent-background render above them, add small green square numbers, and line up the explanation rows with those identifiers. Add a mono figure-number tag at the base.

### Candid work photography

**Only for:** careers and culture content

**Use:** People-focused opening.

**Observed:** Two unequal-width photographs share a 611px height with a 20px gutter: a narrower conversational office scene and a wider communal worktable. Natural daylight, subdued clothes, wood and cool dark furnishings are preserved without a green tint.

**Transfer:** Use authentic activity and working relationships, not posed headshots or neon-filtered stock images.

### Amber process diagram

**Only for:** careers and culture content

**Use:** Explain a staged human process.

**Observed:** A sparse amber character diagram occupies the left half, while stacked process stages on the right combine a small icon, title, paragraph and occasional mono duration. Thin vertical rules join the stages.

**Transfer:** Pair a simple branching or sequential schematic with practical explanations of a human workflow.

**Build:** Construct the left graphic from 1px stepped SVG paths, small squares, dotted vertical strokes and left-pointing arrows with bracketed numbers. Use amber at varying alpha over the dark canvas. Align each numbered stop to its corresponding right-column paragraph.

### Monochrome endorsement wall

**Only for:** company credibility sections

**Use:** Institutional or partner proof.

**Observed:** Pale gray logos are centered in #303235 rectangular tiles, 4px corners, arranged three across with 32px gaps. Shapes remain generously padded and comparable in optical size.

**Transfer:** Normalize supplied partner marks into monochrome and give each the same optical prominence.

### Icons

**Observed:** Small solid geometric icons dominate: 12px arrows and menu details, 16px benefit and action marks, with 24px icons inside feature cards. Accent icons often sit on tiny deep-green rectangular backplates; culture content swaps these for amber. Thin-stroke utility marks are subordinate.

**Transfer:** Choose crisp filled system symbols with few details; do not substitute oversized outline illustrations for the small equipment-like marks.

## Section recipes

How recurring sections are built.

### First screen: Working product opening

**Observed:** A 60px Navigation bar tops an 840px asymmetric dark stage. Behind everything, Industrial product stage light and Technical character field fade from the lower right. A compact operational panel sits high left, connected by a fine elbow line toward a tall object on the right; the object is about 570px wide and 678px high. The two-line display headline sits low left within a 720px measure and starts at the wide 40px gutter, not the chapter container edge. There is no separate supporting paragraph or local hero button row: conversion actions live in the header. Within the first 900px the full promise, operational panel, main object and a low-contrast customer-logo strip are visible. The first explanatory chapter starts below the fold.

**Transfer:** Give another product an equally tangible main object or system diagram, a small real operational state and a concise two-line promise. Preserve the low-left text/high-right object tension. Product detail pages instead open with a green category name, a 52px bright/muted heading pair and a wide cropped media stage; solution pages use the centered-display recipe beneath a compact data illustration; culture pages use a centered 52px title above paired candid photographs.

**Avoid:** Do not replace the composition with a centered headline, giant pill CTA and generic floating browser. Do not add a long hero paragraph where the diagram and object should carry the explanation.

**Text style:** `display` — SuisseIntl 400 · 65px/1 · tracking -0.025em

### Two-tone thesis

**Observed:** A heading-compact statement crosses much of the content container. Selected assertion phrases are raised silver while connective explanation recedes in gray. A 40px content stack leads into unequal-width product imagery.

**Transfer:** Write one readable argument and emphasize the result, not arbitrary colored words.

**Text style:** `heading-compact` — SuisseIntl 400 · 36px/42px · tracking -0.013em

### Visual capability chapter

**Observed:** A heading statement spans roughly ten grid tracks, followed by a 56px pause and Paired media. Visual benefit card modules use independent heights on each side, pairing metal close-ups with terminals, economic diagrams or state panels.

**Transfer:** Alternate physical proof and operational proof without turning every module into the same generic card.

**Text style:** `heading` — SuisseIntl 400 · 50px/1.1 · tracking -0.02em

### Compact proof grid

**Observed:** Linked benefit card modules form a three-column grid with 20px gutters. A short title and a compact paragraph occupy the upper edge; taller variants add a small accent icon and fine-rule example lists beneath.

**Transfer:** Use three related mechanisms or use cases with similarly sized descriptions; keep list items concrete.

**Text style:** `card-heading` — SuisseIntl 400 · 18px/24px · tracking 0.014em

### Explorer chapter

**Observed:** Engineering explorer spans the content container inside a full-width top-and-bottom rule. The image dominates the left portion while a heading, explanation, Exploration link and numbered detail rows occupy the right.

**Transfer:** Use the explorer where component-level detail helps the decision, even when the implementation is static.

**Text style:** `heading` — SuisseIntl 400 · 50px/1.1 · tracking -0.02em

### Signal closing invitation

**Observed:** A 182px-tall invitation uses a bright 50px promise over a muted same-size conversational line, with Primary button and a neutral outlined companion below. A compact Technical character field sits at the right, separated by ample empty canvas. Marketing and product pages use this call before the footer; solution pages can place resources between the call and footer.

**Transfer:** Include the character-field invitation device in marketing and product landing pages, adapting the promise and next action to the decision being asked.

**Text style:** `heading` — SuisseIntl 400 · 50px/1.1 · tracking -0.02em

### Statement footer

**Observed:** After 192px of breathing room, a fine top rule introduces a 505px footer. The left half holds a muted two-line heading statement; the right half holds three narrow navigation columns with mono labels and Footer link lists. A Newsletter field and Subscribe button sit at the lower left; a compact social-icon row aligns beneath the links. The same dark footer is used even after amber culture content.

**Transfer:** Close with a short ownable product idea and useful navigation, not another oversized promotional image.

**Text style:** `heading` — SuisseIntl 400 · 50px/1.1 · tracking -0.02em

### Technical comparison and specification

**Only for:** product detail and solution pages

**Observed:** A detail-heading introduces plain ruled rows rather than rounded cells. Specifications use a left label and right value; comparisons introduce a narrow criterion column and two alternatives, with the preferred column on a slightly raised dark surface. Body text remains 16px/22px.

**Transfer:** Separate verifiable values from explanatory commentary; give the preferred option tonal backing rather than a bright color fill.

**Text style:** `detail-heading` — SuisseIntl 400 · 52px/58px · tracking -0.021em

### Compatibility chapter

**Only for:** solution pages

**Observed:** A detail-heading and 25px lead precede a two-column set of outlined integration links. Mono category text sits above, recognizable green marks sit left within each row, and a small outbound arrow occupies the upper right. A lower paragraph introduces a compact row of outlined compatibility tags.

**Transfer:** Distinguish official integrations from general compatibility rather than treating every logo as the same endorsement.

**Text style:** `detail-heading` — SuisseIntl 400 · 52px/58px · tracking -0.021em

### Human information chapter

**Only for:** careers and culture content

**Observed:** Centered 36px bright/muted heading pairs introduce benefits and credibility. Benefits use a two-column arrangement with small amber icon wells; roles use full-width ruled rows with 25px titles and secondary metadata. FAQ question controls sit inside Culture FAQ plane. Monochrome endorsement wall provides the last credibility block before the footer.

**Transfer:** Use this warmer variant for practical human concerns, with specific commitments and process information.

**Text style:** `heading-compact` — SuisseIntl 400 · 36px/42px · tracking -0.013em

## Page flow

**Storyline:** promise → tangible demonstration → mechanism and trade-offs → capability proof → decision detail → invitation → navigational close

### Broad marketing landing page establishing a new product category

1. **Promise** — Asymmetric working-product stage with operational panel, large object and subdued customer marks.
2. **Product demonstration** — Two-tone thesis, paired product images and four compact system explanations.
3. **Problem framing** — Side-by-side alternatives expressed through character diagrams and concise limitations.
4. **Capability proof** — Large visual cards followed by an expansive interface demonstration.
5. **Use cases** — Compact linked benefits and taller illustrated industry panels.
6. **Decision detail** — Annotated explorer and interface-based operational benefits.
7. **Closing call** — Signal invitation and statement footer with subscription.

**Transfer:** Move from a concrete new possibility to an inspectable mechanism; let the product determine the number of proof chapters.

### Solution landing page translating a technical platform into a particular need

1. **Promise** — Centered title beneath a small active data illustration, followed by three compact benefit markers.
2. **Capability proof** — Three tall illustrated benefits.
3. **Trade-off clarification** — Ruled comparison with subtly emphasized preferred column.
4. **Compatibility reassurance** — Integration links and compact compatible-tool tags.
5. **Use cases** — Three detailed application cards with short example lists.
6. **Economic proof** — Compact benefit cards with bounded quantitative language rather than giant isolated numbers.
7. **Closing call** — Signal invitation, practical resource cards and shared footer.

**Transfer:** Organize around the buyer's objection and workflow; connect claims to compatible tools and concrete workloads.

### Technical product detail for evaluation

1. **Product definition** — Category label, bright/muted heading pair and a large material close-up overlaid with telemetry.
2. **Capability proof** — Three tall illustration cards with compact explanations.
3. **Differentiation** — Generation or architecture chapter with three benefit-and-example cards.
4. **Decision detail** — Full-width ruled specification table.
5. **Closing call** — Signal invitation then shared statement footer.

**Transfer:** Begin with what the product lets a person do, then supply operational evidence and exact specifications.

### People-focused recruiting or culture information

1. **Invitation** — Centered title and paired candid work photographs.
2. **Shared purpose** — Two-column mission explanation and concise commitments.
3. **Available paths** — Ruled opportunity list and compact amber availability notice.
4. **Practical commitments** — Centered heading pair and icon-led benefits.
5. **Process clarity** — Amber character diagram beside detailed stages.
6. **Objection handling** — Long compact FAQ accordion.
7. **Credibility** — Monochrome endorsement wall.
8. **Navigational close** — Shared dark footer, without the marketing signal invitation.

**Transfer:** Replace sales persuasion with transparency about commitments, process and expectations.

## Writing

Matter-of-fact, technically literate and confident. Ambition is expressed through a clear contrast or a concrete operational benefit, with explanations that sound accountable rather than mystical.

**Do not copy:** Do not reuse Oxide names, logos, product artwork, customer or investor marks, proprietary product names, quoted claims, compensation figures, savings percentages or specification numbers as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct imperatives for tasks, 'your' for control and ownership, and 'we' for human commitments. Product explanations can remain impersonal when describing mechanisms.
- **Rhythm:** Headlines are short clauses, usually four to ten words. Support lines use one or two factual sentences; compact fragments work in technical lists. Human-process copy can be longer and more conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the experience or capability in familiar terms, often contrasting two worlds. | 4–10 words | “On-prem that feels like the public cloud”<br>“AI starts with big data” |
| Chapter headline | Lead with a practical outcome or a pointed assertion. | 4–10 words | “Your data stack runs unchanged”<br>“Manage your cloud with a single, unified interface” |
| Supporting proof | Explain the mechanism, then bound the benefit with specifics or exclusions. | 15–35 words | “A fully auditable security chain, with a hardware root of trust, open-source firmware, and cryptographic isolation.”<br>“One-time purchase. No monthly cloud bills that scale with your data. No egress fees.” |
| Action | Plain verb plus object, or a short conversational invitation. | 2–5 words | “Contact sales”<br>“Explore hardware in 3D”<br>“Talk to our team” |
| Human-process explanation | Explain what happens and who is responsible without euphemism. | 1–3 sentences | “The materials are reviewed thoroughly by a broad group of [Brand] employees.” |

**Words and phrasing to use:** control; on-demand; integrated; predictable; verifiable; provision; run; manage; your; no; standard

**Avoid:** magic; revolutionary; supercharge; limitless; delightful; game-changing; effortless transformation

**Rules:**

- Pair each substantial benefit with an inspectable mechanism.
- Use technical nouns only when they clarify the buyer's decision.
- Make quantitative claims bounded and substantiated; keep them within a proof explanation.
- Express constraints and exclusions directly, including what the product does not require.
- Use sentence case for marketing prose and titles; uppercase belongs to small mono controls and markings.

## Do's and Don'ts

### Do

- Keep display headings at weight 400 and 65px with -0.025em tracking.
- Let #0b0e12 remain continuous between sections, using 128px chapter gaps.
- Use 20px gutters for three-up cards and paired 590px media columns.
- Use #818284 to recede explanatory headline lines without changing their weight.
- Keep primary controls at 32px high with 2px corners; use 40px for form submission.
- Stage photographic or rendered details on #181a1d or #303235 with crisp 4px corners.
- Include figure-number markings and an intentional character-field graphic.
- Give long technical descriptions a roughly 480px measure.

### Don't

- Do not turn the green accent into full-width lime section backgrounds.
- Do not use pure white for every paragraph; preserve the neutral hierarchy from #dedede to #818284.
- Do not replace 1px low-contrast rules with glowing borders or heavy drop shadows.
- Do not make every text style monospace; body reading remains a neutral sans.
- Do not increase ordinary card radii beyond 4px or convert action keys to capsules.
- Do not enlarge small metrics into a loud numerical billboard; keep proof contextual.
- Do not apply the amber people-content theme to ordinary product chapters.
- Do not tint candid work photography green or force it into dark product-render lighting.

## Motion and responsive

### Motion

**Observed:**

- Declared navigation backing opacity transition: .15s cubic-bezier(.4, 0, .2, 1).
- Declared action and surface color transitions include .15s cubic-bezier(.4, 0, .2, 1); other matched transitions include opacity 0.25s and all 0.5s with the same curve.
- A marquee is declared at 45s linear infinite; a gentle-ping animation is declared at 2s cubic-bezier(0, 0, 0.2, 1) infinite.
- The exploration-link arrow translates right on hover.

**Transfer:**

- Keep interactive feedback concentrated in tiny arrows, state color and the operational graphics; do not make the main prose fly through the layout.
- Use a slow continuous logo strip only where a proof strip exists.

**Unknown:**

- Exact timing and choreography of terminal typing, character fields, 3D exploration and scroll reveals are not specified.

### Responsive

**Observed:**

- Desktop composition is based on 1440px width.
- Grid classes specify three benefit columns from 1000px, two from 700px and one below that.
- Large paired visual cards split at 800px; the product explorer uses a side-by-side arrangement from 1100px.
- Opening texture and diagonal backing layers are hidden below 700px, where the opening changes to a vertical flex composition.
- Full desktop navigation controls and right actions appear from 1100px.

**Transfer:**

- On narrow screens, stack the working panel, promise and product into a deliberate vertical composition rather than shrinking the desktop collage.
- Keep the signature character artwork as a small standalone accent when the large masked background texture is removed.
- Reflow annotated object and explanation together so callout numbers retain their relationship.

**Unknown:**

- Exact mobile type sizes, menu-open composition, image framing and footer reflow are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
