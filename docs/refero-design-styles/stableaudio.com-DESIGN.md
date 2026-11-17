# Stable Audio — grain and signal

## Overview

A dark, tactile technology style where soft silver contours drift behind crisp, practical product language. Bold grotesk headings and compact rectangular controls give the atmosphere an instrument-like discipline. Mostly black and charcoal with white text, it suits creative tools and technical products that can show their interface, balancing spacious scenes with dense capability cards.

### Essentials

- An atmospheric field, not a flat dark theme: black #000000 and warm charcoal #131311 dominate, with oversized grainy silver loops behind the opening and a full-width editorial band. Recreate the loops even when no product artwork exists.
- A centered promise above an emerging instrument: 60px/80px, weight 700 headline in a 640px column, 520px support line, paired actions and a tilted interface entering the bottom of the first screen.
- Headings have weight without typographic theatrics: Inter 700, 36px/56px with -0.9px tracking for section leads; compact card titles use 20px/32px with -0.3px tracking.
- Actions are cut rectangles: white primary controls, dark #27262b lettering, 14px/24px bold text and 14px 28px padding for the hero; outlines instead of pills for secondary actions.
- Color is a tiny operational signal in an overwhelmingly neutral page: amber #f8a815 identifies a recommended offer or demo start; lavender #a188d4 belongs only to the persistent download strip, not the main hero.
- Cards feel like smoked, lightly grained panes: white at 0.043 alpha, 40px backdrop blur, a 1px inset highlight and a fine gradient edge; 16px grid gaps contrast with 96px section padding.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal white | `#ffffff` | `--color-white` | text, action, border | Headings, primary buttons and strong outlines. |
| Black stage | `#000000` | `--color-canvas` | background | Atmospheric opening and dark media fields. |
| Translucent header | `#0f0f0e` | `--color-header` | background | Visible rgba(19,19,17,0.796) over black in the navigation bar. |
| Warm charcoal | `#131311` | `--color-ground` | background, text | Main content ground and footer; inverse newsletter button lettering. |
| Smoked pane | `#1d1d1b` | `--color-glass` | surface | Visible white at 0.043 alpha over the warm charcoal ground; preserve the translucent construction over imagery. |
| Soft rule | `#262626` | `--color-rule` | border | White at 0.15 alpha on black for separators; its visible value shifts with the ground. |
| Button ink | `#27262b` | `--color-button-ink` | text, surface | Primary control lettering and the charcoal tint of editorial overlays. |
| Input edge | `#333333` | `--color-edge` | border | White at 0.2 alpha over black for field and footer edges. |
| Hairline shaded end | `#3a3a3a` | `--color-hairline-dark` | border | Visible rgba(96,96,96,0.6) on black at one end of pane outlines. |
| Hairline lit end | `#444444` | `--color-hairline-light` | border | Visible rgba(136,136,136,0.5) on black at the other end of pane outlines. |
| Dim white | `#999999` | `--color-subtle` | text | White at 0.6 alpha over black for subdued questions and metadata. |
| Lavender gray | `#a9a8b2` | `--color-muted` | text, accent | Footer descriptions, attribution labels, small bullet dots. |
| Soft white | `#b3b3b3` | `--color-body` | text | White at 0.7 alpha over black for supporting text; it remains slightly warmer over charcoal. |
| Editorial white | `#bfbfbf` | `--color-editorial-copy` | text | White at 0.75 alpha over dark media for explanatory paragraphs. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and interactive demonstrations | Amber signal | `#f8a815` | `--color-amber` | action, accent, border | Recommended plan border, label and action; compact start action in an interactive demonstration. |
| download pages | Download lavender | `#a188d4` | `--color-lavender` | action, border | Small active action in the persistent bottom strip. |
| pricing pages | Plan charcoal | `#141413` | `--color-plan` | surface | Opaque offer cards. |
| download pages | Legal gray | `#737373` | `--color-legal` | text | White at 0.45 alpha over black beneath download actions. |

## Typography

- **Inter** — All marketing headings, paragraphs, buttons and attribution labels. Contemporary grotesk with a high x-height; bold headings, restrained regular explanatory copy. Font stack: "Inter", Roboto, "Helvetica Neue", "Arial Nova", "Nimbus Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 700 | 60px | 80px | -0.0235em | Centered primary promise, usually split across two lines. |
| heading | Inter | 700 | 36px | 56px | -0.0244em | Centered section lead; also the enterprise editorial heading. |
| closing-heading | Inter | 700 | 36px | 1.05 | normal | Tightly stacked two-line statement in the concluding media band. |
| card-heading | Inter | 700 | 20px | 32px | -0.017em | Capability and comparison card titles. |
| body | Inter | 400 | 16px | 1.5 | -0.011em | Support lines, explanatory paragraphs and questions. |
| small | Inter | 400 | 14px | 24px | -0.006em | Card details, footer links and descriptions. |
| action | Inter | 700 | 14px | 24px | -0.006em | Main buttons and underlined navigation links. |
| form-action | Inter | 500 | 14px | 24px | -0.006em | Newsletter submission and footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-heading | Inter | 800 | 30px | 40px | -0.025em | Paid offer names; more prominent than the prices. |
| community proof sections | quote | Inter | 500 | 16px | 22px | -0.011em | Short social excerpts in proof cards. |
| pricing pages | price | Inter | 600 | 16px | 1.5 | -0.011em | Compact monthly price beneath the offer name. |
| pricing pages | recommendation | Inter | 600 | 12px | 16px | 0.025em, uppercase | Amber label aligned beside the chosen offer name. |
| community proof sections | attribution | Inter | 600 | 11px | 1.5 | 0.06em | Author name beside a small platform mark. |

**Notes:**

- The bold hierarchy is compact in width rather than extremely oversized. Keep body copy at 16px and feature details at 14px while giving section headings a loose 56px line box.
- The closing statement deliberately uses a much tighter 1.05 line height than ordinary section leads. Do not normalize these roles.
- Underlining belongs to navigation and inline links, not automatically to filled buttons. An interactive opening can use softly blurred headline artwork while the product landing default stays sharp.

## Layout

**Density:** Airy section framing around compact controls and card copy; the large dark intervals let the background light forms breathe.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Tiny attribution icon gaps and closely stacked bullet items. |
| 8px | Input-to-submit gap and closely related copy. |
| 12px | Card subtitle spacing and proof-card bottom-row padding. |
| 16px | Grid gutters, paired action gap and heading-to-support separation. |
| 20px | Offer and social-card inner padding. |
| 24px | Page side padding and opening headline-to-support separation. |
| 32px | Support-to-hero-actions gap and navigation link gap. |
| 40px | Footer column gutters. |
| 48px | Heading-pair-to-card-grid gap. |
| 96px | Major content section vertical padding. |

### Containers and grids

- **outer frame**: max width 1440px · side padding 24px. Full-width header, footer and media-band content frame.
- **hero copy**: max width 640px. Centered headline with a narrower 520px support paragraph.
- **capability grid**: max width 1100px · 3 columns · gap 16px. Three-column capability cards; comparison sections use two equal columns in this same frame.
- **footer grid**: 4 columns · gap 40px · side padding 24px. Wide newsletter column followed by three link columns; proportions 1.6:1:1:1.
- **compact proof frame** (only for interactive and community landing pages): max width 915px · 3 columns · gap 16px. Three tall access-path cards or two equal proof cards.
- **offer grid** (only for pricing pages): max width 1200px · 4 columns · gap 16px · side padding 24px. Four paid plans below a full-width entry offer.
- **questions** (only for pricing pages): max width 600px · side padding 24px. Centered single-column question list.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | main actions and capability panels | 0px |
|  | newsletter controls | 4px |
| community proof sections | social proof cards | 12px |
| community proof sections | external link discs | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| pane highlight | `inset 0px 1px 0px 0px rgba(255,255,255,0.06)` | A barely lit top edge, not a floating drop shadow. |
| interface depth | `0px 40px 80px rgba(0,0,0,0.65)` | Drop-shadow filter beneath the tilted product interface. |

### Surfaces

#### Black stage · level 0

**Use:** Opening atmosphere and full-width media scenes.

**CSS:** `background: #000000; color: #ffffff`

#### Charcoal ground · level 0

**Use:** Long-form capability content and footer.

**CSS:** `background: #131311; color: #ffffff`

#### Grained glass pane · level 1

**Use:** Comparison and capability cards.

**CSS:** `background: rgba(255,255,255,0.043); backdrop-filter: blur(40px) saturate(1.5); box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06); border-radius: 0px; overflow: hidden`

**Observed:** A separate masked 1px outline uses a horizontal gradient between rgba(96,96,96,0.6) and rgba(136,136,136,0.5). A fine noise layer lies inside the pane.

**Transfer:** Create the edge as an absolutely positioned pseudo-element with 1px padding, two masks and mask-composite: exclude; inherit the pane radius.

#### Editorial veil · level 1

**Use:** Readable left column above the concluding contour scene.

**CSS:** `background: linear-gradient(to right, rgba(39,38,43,0.85), rgba(39,38,43,0.6), rgba(0,0,0,0))`

**Observed:** The right side remains open to the moving light contours; the enterprise variant uses black instead of charcoal in the veil.

#### Offer pane · level 1

**Only for:** pricing pages

**Use:** Opaque plan comparisons.

**CSS:** `background: #141413; box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06); border-radius: 0px`

**Observed:** Uses the same fine gradient outline and grain as the translucent cards; a chosen offer adds an amber border.

## Components

### Fixed navigation

**Use:** Persistent orientation and account actions.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; z-index: 50; background: rgba(19,19,17,0.796)`

**Text style:** `action` — Inter 700 · 14px/24px · tracking -0.006em

**Observed:** Wordmark left, three underlined product links centered and two account actions right. Inner frame is 1440px with 24px side padding; center links have 32px gaps. Opening can appear transparent against the artwork.

**Transfer:** Keep navigation sparse enough to leave the background scene visible.

### Primary button

**Use:** Primary hero conversion.

**CSS:** `display: flex; align-items: center; gap: 10px; background: #ffffff; color: #27262b; padding: 14px 28px; border-radius: 0px; height: 52px`

**Text style:** `action` — Inter 700 · 14px/24px · tracking -0.006em

**Observed:** A small platform symbol precedes the label. Header signup is a smaller 42px control with 8px 16px padding; plan actions stretch across the card and use 10px 16px padding.

**States:** Declared: hover opacity 0.9.

### Outline button

**Use:** Secondary account or product destination.

**CSS:** `display: flex; justify-content: center; align-items: center; background: transparent; border: 1px solid #ffffff; color: #ffffff; padding: 8px 16px; height: 42px; border-radius: 0px`

**Text style:** `action` — Inter 700 · 14px/24px · tracking -0.006em

**Observed:** Sits beside the white account button. Compact destination buttons use 12px bold text and 34px height.

**States:** Declared: hover background-color rgba(255,255,255,0.15).

### Underlined navigation link

**Use:** Product navigation without a filled hit area.

**CSS:** `color: #ffffff; text-decoration-line: underline; text-underline-offset: 4px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 700 · 14px/24px · tracking -0.006em

**Observed:** Links are visibly underlined even before interaction, separating them from footer links.

**States:** Declared: hover opacity 0.75.

### Capability pane

**Use:** Explain one capability or compare two operating modes.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: rgba(255,255,255,0.043); backdrop-filter: blur(40px) saturate(1.5); box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06); border-radius: 0px; overflow: hidden`

**Text style:** `card-heading` — Inter 700 · 20px/32px · tracking -0.017em

**Observed:** Title then muted small text; two comparison panels are 542px wide, while the three-column feature grid has 356px cards. Grained glass pane supplies the noise and outline. Larger comparison cards can have a separated download area.

**Transfer:** Use real distinctions in workflow; do not add decorative charts to fill a short card.

### Newsletter field

**Use:** Low-key footer subscription.

**CSS:** `background: transparent; color: #ffffff; border: 1px solid rgba(255,255,255,0.2); border-radius: 4px; padding: 8px 12px; height: 42px; min-width: 0px`

**Text style:** `small` — Inter 400 · 14px/24px · tracking -0.006em

**Observed:** Expands beside a small white submit button with an 8px gap. The introductory line and short description sit above it.

### Newsletter submit

**Use:** Submit the adjacent footer field.

**CSS:** `background: #ffffff; color: #131311; border-radius: 4px; padding: 8px 16px; height: 42px`

**Text style:** `form-action` — Inter 500 · 14px/24px · tracking -0.006em

**Observed:** Rounded only slightly, unlike the square main actions.

**States:** Declared: hover opacity 0.8; focus-visible outline transparent solid 2px, outline-offset 2px, box-shadow 0 0 #0000,0 0 #0000,0 0 #0000.

### Social excerpt card

**Only for:** community proof sections

**Use:** Show practical third-party use rather than polished testimonial slogans.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 20px; border-radius: 12px; background: rgba(255,255,255,0.043); backdrop-filter: blur(40px); box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06); overflow: hidden`

**Text style:** `quote` — Inter 500 · 16px/22px · tracking -0.011em

**Observed:** Small platform icon and Attribution text first, excerpt below, then a separated bottom link row with a 32px white external-link disc. The frame has a fine gradient edge. Two-column cards measure 450px by 218px; marquee cards are 260px squares.

**States:** Declared: hover background-color rgba(255,255,255,0.14).

### Plan card

**Only for:** pricing pages

**Use:** Compare offers with a single clear recommendation.

**CSS:** `display: flex; flex-direction: column; background: #141413; padding: 20px; border-radius: 0px; box-shadow: inset 0px 1px 0px 0px rgba(255,255,255,0.06)`

**Text style:** `plan-heading` — Inter 800 · 30px/40px · tracking -0.025em

**Observed:** Name first, small semibold price second, two benefits, allocation and license details, then a full-width action aligned at the bottom. Recommended card adds a 2px amber outline, uppercase amber label and amber action. A free offer is a separate horizontal panel above the paid row.

**Transfer:** Keep price visually subordinate to the offer name; recommend by outline, not a bright filled card.

### Question row

**Only for:** pricing pages

**Use:** Objection handling in a compact list.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 16px 0px; color: rgba(255,255,255,0.6); text-align: left; border-bottom: 1px solid rgba(255,255,255,0.15)`

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking -0.011em

**Observed:** Full-width question with a small white downward chevron at the right; long questions wrap rather than truncate. No card background around individual rows.

**States:** Declared: hover color rgba(255,255,255,0.8).

### Persistent download strip

**Only for:** download pages

**Use:** Maintain access to installation actions after the opening.

**CSS:** `position: fixed; bottom: 0px; width: 100%; height: 51px; background: rgba(10,10,10,0.45); border-top: 1px solid rgba(255,255,255,0.15); backdrop-filter: blur(20px) saturate(1.6); z-index: 40`

**Observed:** Two small centered rectangular controls: lavender enabled download and dark disabled alternative. Active control uses 12px bold text, 6px 16px padding and a 30px height. The strip stays below the header in layer order.

## Imagery and graphics

### Silver contour field

**Use:** Signature atmosphere in the opening and editorial conversion bands.

**Observed:** Huge irregular rounded loops and ribbon-like outlines cross the edges of a black field. Their silver-white edges bloom into fine granular gray halos while interiors remain black. Brightness varies along each contour; this is neither a wireframe grid nor a smooth multicolor gradient.

**Transfer:** Always retain this tactile light field. When no equivalent media exists, create an original abstract loop scene instead of substituting stock photography.

**Build:** Use an SVG viewBox of 0 0 1440 1000 with 5–8 asymmetric closed Bezier loops, some extending beyond the frame. Draw no fill; layer a broad white stroke at 0.12 alpha blurred 20px beneath a narrower stroke at 0.35–0.6 alpha blurred 3–8px. Vary stroke widths around 12–36px and rotate the overall field diagonally. Add fine fractal noise, masked to the luminous edges, to break up the light. Preserve broad pure-black areas behind text; match the soft glow rather than relying on exact gradient stops.

### Pane grain

**Use:** Subtle material on cards, not a page-wide paper texture.

**Observed:** Fine almost invisible monochrome grain catches the translucent surfaces and outlines.

**Transfer:** Keep it weaker than the contour texture so small text remains crisp.

**Build:** Tile a 160px SVG with feTurbulence type fractalNoise, baseFrequency 0.8, numOctaves 4 and stitchTiles stitch; draw its filtered rectangle at opacity 0.6, then composite the tile at opacity 0.18 with mix-blend-mode overlay inside the card.

### Tilted product instrument

**Use:** Product proof emerging beneath the hero actions.

**Observed:** A dark, dense interface enters the lower edge in perspective, about 965px wide, with a fine translucent border and heavy soft shadow. Its palette stays near charcoal with restrained internal status marks; the outer marketing scene remains dominant.

**Transfer:** Use a truthful interface or a purpose-built diagram of the new workflow. Minimum equivalent is one wide dark panel with believable controls, not generic floating dashboard tiles.

**Build:** Place the interface inside an overflow-hidden stage; use perspective and a roughly 13deg rotateX tilt, a 1px rgba(255,255,255,0.1) border and filter drop-shadow(0px 40px 80px rgba(0,0,0,0.65)). Let the bottom extend beyond the stage rather than shrinking the whole interface to fit.

### Monochrome entry symbols

**Only for:** interactive landing pages

**Use:** Crown three tall access-path panels.

**Observed:** A globe, laptop and code brackets appear as large white or silver sculptural symbols above card titles, with gentle shaded volume and some overlap of the top edge.

**Transfer:** Choose three familiar symbols for different access paths. Use softly shaded extruded SVG or simple 3D forms, not colorful illustration or circular icon badges.

### Playable artwork rail

**Only for:** interactive demonstrations

**Use:** Small example outputs below the opening interaction.

**Observed:** A narrow horizontal strip of square grayscale cover art with tiny play controls, labels and durations; the outer items fade at the sides.

**Transfer:** Offer a short rail of real product outputs with muted monochrome thumbnails; use small preview documents or result stills for non-audio products.

### Icons

**Observed:** Utility icons are small and mostly white or lavender gray. External arrows use rounded 2.3px strokes in 12–14px frames; question chevrons are 24px with lighter 1.3px strokes. Platform glyphs are solid and about 16px.

**Transfer:** Keep external arrows subordinate to text. Reserve larger sculptural icons for access-path cards, not ordinary feature bullets.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric product opening

**Observed:** The Fixed navigation overlays an edge-to-edge Black stage and Silver contour field. A centered two-line Display headline occupies a 640px column, about half the available page width, with the text group starting well below the 64px header. The 520px support line follows after 24px; a paired action row follows after 32px using Primary button and a visibly unavailable dark alternative. Small legal text sits beneath. A subtle dark radial veil protects the copy. Within the first 900px the headline, support, actions and top edge of the Tilted product instrument are visible; the full interface falls below the fold. The opening stage is about 1001px tall, and the interface rises into its lower portion rather than sitting beside the headline.

**Transfer:** Make this the default new product landing opening: a concise workflow promise, immediate conversion, and one instrument-like product object entering from below. Without a finished interface use an honest dark workflow diagram over the Silver contour field. An interactive landing can replace the action row with a working prompt or task control and output rail; pricing opens with a shorter 342px atmospheric title band so offers arrive quickly.

**Avoid:** Do not turn the opening into a left-copy/right-laptop split, place the complete interface above the fold, or replace the black granular field with a neon gradient.

**Text style:** `display` — Inter 700 · 60px/80px · tracking -0.0235em

### Heading pair and pane grid

**Observed:** On Charcoal ground, 96px top and bottom padding surrounds a centered Heading, a Body support line 16px later and a grid 48px below. The 1100px frame supports either two comparison panes or three columns of Capability pane; gutters are 16px. Card Heading sits above Small descriptive text.

**Transfer:** Use two columns for meaningful alternatives, three for capabilities. Keep the support line brief enough to read as a single thought.

**Text style:** `heading` — Inter 700 · 36px/56px · tracking -0.0244em

### Editorial light band

**Observed:** A full-width 630px-tall Silver contour field is covered by Editorial veil. A left-aligned text block uses Closing heading, a restrained explanatory paragraph and Primary button, leaving most of the right half to the light forms. The enterprise variant uses the ordinary Heading and a fuller bullet-based pitch. An extended interactive variant gives the light scene more scrolling space beside a short capability narrative.

**Transfer:** Include this atmospheric editorial device as a distinct counterpoint to the centered card sections. Use it to resolve trust, explain a meaningful next step or close the story; choose position to suit the content.

**Text style:** `closing-heading` — Inter 700 · 36px/1.05

### Newsletter and link footer

**Observed:** The shared ending is a 391px warm-charcoal band with a white-at-0.2 top rule, 24px side padding and a four-column layout with 40px gutters. The first column is wider and contains a small wordmark, newsletter invitation, one-line description and Newsletter field plus Newsletter submit. The other three columns carry muted category labels and simple link lists. A small maker credit and copyright line sit near the lower left, separated by open space. Download pages retain the Persistent download strip over the bottom edge.

**Transfer:** Close with useful navigation and an approachable subscription invitation, not a giant final headline or a second feature grid.

### Access-path triptych

**Only for:** interactive landing pages

**Observed:** A 915px centered frame contains three 294px-wide tall Grained glass panes. Large Monochrome entry symbols crown the cards; titles, subtitles and compact bullet lists lead to bottom-aligned actions. A centered enterprise-support sentence and underlined contact link close the group.

**Transfer:** Use this to explain three ways into one product, not three unrelated features.

### Partner proof and moving excerpts

**Only for:** community proof sections

**Observed:** Centered Heading and short support lead to a muted monochrome logo row with 64px gaps. Two Social excerpt cards sit below within 915px. A later proof section uses 260px square excerpts in an edge-clipped horizontal marquee with 16px gaps.

**Transfer:** Use genuine ecosystem or customer proof and compact work-in-progress excerpts. Preserve the small Attribution labels and ruled external-link rows rather than inflating quotes into billboard testimonials.

**Text style:** `heading` — Inter 700 · 36px/56px · tracking -0.0244em

### Offer comparison

**Only for:** pricing pages

**Observed:** The compact atmospheric title band precedes a 1200px offer frame. A centered heading introduces a full-width entry offer, then four Plan cards with 16px gutters. Offer names are 30px extra-bold while prices remain 16px semibold. Amber appears only on the recommended offer's border, label and action. A small italic allocation note closes the comparison.

**Transfer:** Make the commercial progression legible through names and benefits; maintain one visual recommendation instead of competing badges.

**Text style:** `plan-heading` — Inter 800 · 30px/40px · tracking -0.025em

### Questions and practical ending

**Only for:** pricing pages

**Observed:** A 600px centered column uses a Heading and support pair, then Question rows 48px below. Rows have hairline bottom separators and right chevrons; 96px section padding separates this block from the footer.

**Transfer:** Answer concrete buying and ownership questions rather than repeating feature marketing.

**Text style:** `heading` — Inter 700 · 36px/56px · tracking -0.0244em

## Page flow

**Storyline:** Promise and immediate use → operating choices → capabilities or practical proof → atmospheric reassurance → questions where needed → newsletter and navigation.

### Product landing with installation conversion

1. **promise** — Centered two-line headline and paired downloads over the contour field; tilted product panel rises from below.
2. **operating choices** — Two equal comparison panes explain different ways to run the product.
3. **capabilities** — Six compact text-led panes in a three-column grid.
4. **trust and closing call** — Left-aligned reassurance and a download action over a full-width light scene.
5. **practical ending** — Shared newsletter and link footer with persistent download actions.

**Transfer:** Use for a focused tool with a tangible interface; explain deployment before individual features.

### Interactive brand landing with ecosystem proof

1. **immediate use** — Soft luminous two-line promise above an interactive task input and a small playable output rail.
2. **access paths** — Three tall icon-crowned cards describe different entry points.
3. **social proof** — Partner marks and two short linked excerpts.
4. **capability narrative** — An expansive light scene carries left-aligned copy, bullets and an action.
5. **community proof** — A continuous rail of compact social excerpts.
6. **practical ending** — Shared newsletter invitation and categorized navigation.

**Transfer:** Lead with a real small interaction when the product supports one, then show adoption paths and credible public use.

### Offer selection with commercial reassurance

1. **orientation** — Short atmospheric title and a single access-summary sentence.
2. **pricing** — Horizontal entry tier followed by four paid offers and one amber recommendation.
3. **complex buying path** — Full-width enterprise editorial band with left-aligned pitch and contact action.
4. **objection handling** — Narrow centered question accordion.
5. **practical ending** — Shared newsletter and categorized footer.

**Transfer:** Keep the hero shorter for decision pages and let plan names, benefits and one recommendation do the work.

## Writing

Direct, practical and creatively literate. The language promises another way to work rather than a miraculous replacement, then explains controls, ownership and access in plain terms.

**Do not copy:** Do not reuse the brand names, wordmarks, partner logos, artist handles, quotations, plan prices, model names, licensing assurances or quantitative capability claims. Replace them with verified facts and original language for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for the reader's workflow; we for support and community-building. Name the product when explaining an action or technical capability.
- **Rhythm:** Short sentence-case headings often end with a period. Follow with one or two compact explanatory sentences; use bullet fragments for practical distinctions. Actions are terse verb phrases, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Connect the product to an existing working context, not an abstract superlative. | 6–10 words | “Bring [Brand] into your session.” |
| Section heading | A short human phrase about agency or access. | 5–8 words | “The controls are in your hands.”<br>“Start anywhere you make music.” |
| Support line | One plain sentence explaining a useful choice. | 10–24 words | “Switch between models depending on what you're creating and where.” |
| Feature detail | Describe a concrete input, action and resulting workflow. | 12–30 words | “Drag any generation from the plugin directly onto a track in your session.” |
| Action | Verb plus destination, platform or named offer. | 2–5 words | “Download for Mac”<br>“Talk to our team” |
| Reassurance | State the condition plainly, then its benefit to the user. | Two short sentences | “Trained on fully licensed audio. What comes out is yours.” |

**Words and phrasing to use:** your session; controls; create; switch; choose; work; get in touch; another way; wherever

**Avoid:** revolutionary; game-changing; unleash limitless potential; magic; disrupt; guaranteed perfection

**Rules:**

- Lead with a familiar workflow and then name the new control.
- Pair creative language with concrete operations and constraints.
- Keep technical detail in small card copy rather than expanding the headline.
- Use questions that sound like a customer's practical concern.

## Do's and Don'ts

### Do

- Keep the main hero headline at 60px/80px and weight 700, centered in a 640px column.
- Use 96px vertical section padding and 48px between heading groups and grids.
- Keep pane gutters at 16px even when the surrounding scene is expansive.
- Use a 1px inset white highlight at 0.06 alpha rather than a floating card shadow.
- Preserve the 36px/37.8px closing statement as a tighter variant of section type.
- Use fine grain and irregular silver light contours as the atmospheric signature.
- Let the dark interface enter from below the first screen instead of competing horizontally with the promise.
- Keep the newsletter invitation and categorized link columns as a useful, modest ending.

### Don't

- Do not give ordinary main actions 9999px pill corners; their silhouettes are rectangular.
- Do not turn amber into a full section background; its job is recommendation or start-state emphasis.
- Do not spread the lavender strip color across hero buttons or headings.
- Do not enlarge prices into the strongest text in an offer card; offer names are 30px while prices are 16px.
- Do not round capability panels to match social cards; 12px corners belong to the social proof variant.
- Do not make the contour field a smooth rainbow mesh; keep silver edges, black interiors and visible granularity.
- Do not add large colorful feature icons to the text-led capability grid.
- Do not introduce a serif or marketing-wide monospace face; the main voice is Inter throughout.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.15s cubic-bezier(0.4,0,0.2,1) transitions for opacity or color properties.
- The navigation background declares a 0.3s color transition with cubic-bezier(0.4,0,0.2,1).
- Social proof rails declare a 30s linear infinite marquee animation; social-card background changes use 0.3s.
- The product interface uses perspective rotation; the download strip declares a 0.3s opacity transition.

**Transfer:**

- Keep color and opacity changes small so the granular light scene remains the primary motion impression.
- Use the continuous marquee only for the social excerpt rail, not for every card grid.

**Unknown:**

- Exact contour-video loop duration and production method.
- The full interface entrance choreography and sticky-strip appearance threshold.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px and 1024px.
- The center navigation is hidden below its desktop breakpoint; the secondary login control is hidden at narrow widths.
- Offer-grid declarations step from one column to two and then four; the footer changes from a two-column structure to a wide four-column arrangement.
- The interface wrapper declares progressively narrower viewport proportions as the viewport grows.

**Transfer:**

- Keep the contour field edge-to-edge and the copy centered when stacking actions and comparison panels.
- Preserve hierarchy by retaining a wide, partially revealed interface rather than reducing it to a tiny complete thumbnail.
- On narrow screens, stack the newsletter controls and retain the small rectangular button shape.

**Unknown:**

- Rendered mobile line breaks, exact narrow-screen type sizes and the full mobile navigation interaction were not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
