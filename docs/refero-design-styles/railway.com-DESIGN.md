# Railway — night trains and cloudscapes

## Overview

A dark, atmospheric software style that pairs literary serif promises with matter-of-fact sans-serif explanations. Aubergine-black, muted blue and forest-green panels give detailed interfaces the feeling of instruments seen at night, with violet reserved for actions and small signals. Illustrated skies, technical line drawings and mechanical information displays soften a dense technical story. A separate campaign expression trades the night palette for lavender skies, theatrical photography and expansive italic serif type.

### Essentials

- Literary promises sit above working machinery: IBM Plex Serif headlines at 54px/1.12, weight 500, -2px tracking introduce a centered interface stage rather than a giant sans-serif slogan.
- The opening is a window into a night world: a 16px-radius illustrated enclosure with 16px outer gutters, a 72px navigation bar, 128px of space before the headline, and a 1064px-wide dark product window beginning within the first 900px.
- Actions are small illuminated controls, not pills: the default pair is 58px high with 8px corners, 12px 24px padding, a muted #553f83 primary and a translucent black secondary, both using 20px/32px medium sans-serif.
- Color belongs to chapter-sized enclosures and signals: #13111c remains the canvas; low-chroma #1b2132, #1f2b2e and #251823 distinguish long chapters. Saturated violet occupies controls, tiny accents and interface details, not the general page background.
- A journey line connects the argument: a narrow vertical rail with circular stations and a small outlined vehicle-like marker accompanies feature chapters; use an abstract progress rail when the product has no literal journey metaphor.
- Proof becomes physical instrumentation: include a split-flap-style information board with 44px × 56px dark cells, 4px corners and 40px monospace characters. Use genuine product metrics or meaningful status labels rather than invented live numbers.
- Product imagery is staged at architectural scale: a dark 1px-edged interface expands to 1160px beneath a 544px text introduction, while small benefits live in restrained three-column groups. If no interface exists, construct a clear diagram of the product's workflow with the same dark backing and fine connectors.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted violet control | `#553f83` | `--color-action` | action | Default landing-page primary action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender signal | `#a78bfa` | `--color-lavender` | text, accent, link | Short emphasized footer phrases and small accent details. |
| Muted plum | `#251823` | `--color-plum-panel` | background | Warm social-proof chapter backing. |
| Midnight blue | `#1b2132` | `--color-blue-panel` | background | Large feature chapter backing. |
| Deep blue green | `#1f2b2e` | `--color-green-panel` | background | Large analytical or explanatory chapter backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mechanical black | `#0b0b0f` | `--color-flap` | surface | Split-flap board cells. |
| Night aubergine | `#13111c` | `--color-canvas` | background | Default page canvas and navigation backing. |
| Raised aubergine | `#1c1a28` | `--color-card` | surface | Featured footer cards and softly highlighted content. |
| Translucent elevation | `#1f1d27` | `--color-raised` | surface | Visible white at 5% over the night canvas; the translucent version adapts to tinted chapters. |
| Subtle edge | `#2b2933` | `--color-edge` | border | Visible white at 10% over the night canvas; use rgba(255,255,255,0.1) for adaptive edges. |
| Board label grey | `#6b7280` | `--color-flap-label` | text | Muted uppercase labels on the mechanical information board. |
| Distant grey | `#878593` | `--color-faint` | text | Low-priority captions and inactive labels. |
| Muted grey | `#a1a0ab` | `--color-muted` | text | Footer links and secondary descriptions. |
| Light grey | `#dcdce0` | `--color-secondary` | text | Navigation and detailed comparison content. |
| Soft white | `#f7f7f8` | `--color-foreground` | text | Default text on dark surfaces. |
| Signal white | `#ffffff` | `--color-white` | text, surface | Headlines, primary links and occasional inverted sales actions. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#42946e` | `--color-success` | text, accent | Operational status and green chapter labels. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface well | `#0d0c14` | `--color-window` | surface | Dark backing within framed product demonstrations. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan violet | `#853bce` | `--color-plan-purple` | action | Recommended-plan actions; more saturated than the default landing action. |
| pastel campaign pages | Daylight blue | `#5b8fe2` | `--color-sky` | background | Lower campaign canvas behind the landscape ending. |
| pastel campaign pages | Editorial plum | `#4d3e75` | `--color-campaign-plum` | text | Italic editorial introduction on pale backing. |
| pastel campaign pages | Lavender dusk | `#ccc0e7` | `--color-lavender-dusk` | background | Lower campaign gradient transition. |
| pastel campaign pages | Lilac dusk | `#dbd3ee` | `--color-dusk` | background | Transition between lilac and blue. |
| pastel campaign pages | Cloud lilac | `#edddf2` | `--color-lilac` | background | Broad pastel story backing. |
| pastel campaign pages | Cloud cream | `#fefbf1` | `--color-cream` | background | Upper end of the cream-to-lilac campaign gradient. |
| pastel campaign pages | Campaign ink | `#040406` | `--color-campaign-ink` | text, border | Black typography and portrait-card rules. |
| pricing and technical product pages | Comparison backing | `#181622` | `--color-band` | background, surface | Comparison tables, plan cards and FAQ bands. |
| pricing pages | Solid control edge | `#33323e` | `--color-solid-edge` | border | Opaque plan-card and control boundaries. |

## Typography

- **Inter** — Navigation, support copy, controls and detail text. Neutral, high-x-height sans-serif; medium support copy gives dark layouts enough presence. Font stack: "Inter", -apple-system, system-ui, 'Segoe UI', sans-serif.
- **IBM Plex Serif** — Default marketing headlines and feature chapter headings. Sturdy editorial serif with bracketed serifs and a technical rather than ornamental tone. Font stack: "IBM Plex Serif", Georgia, Cambria, 'Times New Roman', serif.
- **ui-monospace** — Mechanical information boards, technical rates and operational status. Unembellished fixed-width instrument lettering. Font stack: "ui-monospace", SFMono-Regular, 'SF Mono', Consolas, 'Liberation Mono', Menlo, monospace.
- **Inter Tight** (only for technical product closing calls) — Compact, two-line closing promise. Narrower sans-serif with a compact word silhouette. Font stack: "Inter Tight", Inter, system-ui, sans-serif.
- **Newsreader Variable** (only for pastel campaign pages) — Editorial display, italic emphasis and portrait captions. Expressive, high-contrast reading serif with flowing italic forms. Font stack: "Newsreader Variable", Georgia, 'Times New Roman', serif.
- **Tangerine** (only for pastel campaign openings) — One oversized handwritten question paired with a serif heading. Thin, calligraphic connected script with long ascenders. Font stack: "Tangerine", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | IBM Plex Serif | 500 | 54px | 1.12 | -0.0363em | fixed | Centered opening promise. |
| proof-heading | IBM Plex Serif | 400 | 40px | 1.2 | -0.02em | fixed | Centered customer proof and quantitative proof introduction. |
| board | ui-monospace | 400 | 40px | 1.4 | normal, uppercase | fixed | Split-flap labels and numbers. |
| heading | IBM Plex Serif | 400 | 36px | 48px | -0.02em | fixed | Feature chapter heading, usually wrapped over two lines. |
| hero-support | Inter | 400 | 20px | 1.4 | normal | fixed | Centered opening support line. |
| button | Inter | 500 | 20px | 1.6 | -0.01em | fixed | Default paired opening actions. |
| section-support | Inter | 500 | 18px | 1.6 | -0.005em | fixed | Feature introductions and inline continuation links. |
| body | Inter | 400 | 16px | 1.5 | normal | fixed | Benefit descriptions and detailed content. |
| item-heading | Inter | 600 | 16px | 1.5 | normal | fixed | Benefit titles and technical questions. |
| eyebrow | Inter | 500 | 14px | 20px | -0.005em | fixed | Sentence-case chapter chip. |
| navigation | Inter | 500 | 14px | 20px | normal | fixed | Navigation and featured-card titles. |
| small | Inter | 400 | 14px | 20px | normal | fixed | Footer links and compact descriptions. |
| status | ui-monospace | 400 | 12px | 1.5 | normal | fixed | Operational status link. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pastel campaign endings | campaign-close | Newsreader Variable | 500 italic | 144px | 1.125 | normal | fixed | Monumental final imperative. |
| pastel campaign openings | campaign-script | Tangerine | 700 | 130px | 1 | normal | fixed | Large handwritten second question. |
| pastel campaign pages | campaign-heading | Newsreader Variable | 400 | 88px | 1.125 | normal | size clamp(2.75rem, 7vw, 5.5rem) | Centered film and FAQ headings. |
| pastel campaign pages | campaign-emphasis | Newsreader Variable | 500 italic | 88px | 1.125 | normal | fixed | Single emphasized word within the editorial heading. |
| pastel campaign pages | campaign-opening | Newsreader Variable | 400 | 64px | 1.125 | normal | fixed | Left-aligned opening question. |
| pricing and enterprise openings | commercial-display | IBM Plex Serif | 500 | 56px | 1.25 | -0.025em | fixed | Longer commercial promises. |
| enterprise closing arguments | manifesto | IBM Plex Serif | 400 | 48px | 1.33 | -0.025em | fixed | Large left-aligned closing argument, with the final promise underlined. |
| enterprise pages | enterprise-heading | Inter | 500 | 40px | 1.25 | -0.05em | fixed | Centered proof-led chapter heading. |
| technical product closing calls | technical-close | Inter Tight | 600 | 40px | 1.2 | -0.015em | fixed | Two-line closing conversion heading. |
| enterprise pages | stat | Inter | 600 | 32px | 52px | -0.05em | fixed | Large gradient-filled figures inside glass cards. |
| pricing pages | comparison-heading | Inter | 600 | 32px | 44px | normal | size clamp(28px, 2.5vw, 32px) | Comparison table heading. |
| pastel campaign FAQ rows | campaign-question | Newsreader Variable | 500 | 28px | 39px | normal | fixed | Question in a white rounded accordion row. |
| pastel campaign portrait cards | campaign-caption | Newsreader Variable | 600 | 21px | 1.25 | normal | fixed | Centered name in the narrow colored label under a portrait. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default hierarchy changes family rather than inflating every heading: serif promises and chapter leads, sans-serif explanations, monospace instruments.
- Negative tracking is strongest on the opening promise; retain its -2px setting rather than normalizing it to the feature heading's -0.02em.
- Chapter chips stay sentence case. Uppercase belongs to instrument labels, not the general editorial voice.
- Campaign italic words are weight 500 beside weight 400 roman text; the script family is a separate opening device, not a replacement for all headings.

## Layout

**Density:** Airy at chapter scale, compact inside working interfaces and information groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and compact secondary text gaps. |
| 12px | Heading-to-support gap and paired-action gap. |
| 16px | Outer enclosure gutter and product-page panel separation. |
| 24px | Opening headline-to-support gap, feature-card padding and testimonial grid gap. |
| 32px | Support-to-action gap, chip-to-heading gap and main grid gutters. |
| 48px | Testimonial padding and major content group separation. |
| 64px | Proof heading-to-card separation and small feature group breathing room. |
| 80px | Text introduction-to-large product illustration separation. |
| 96px | Common chapter vertical padding and opening text block bottom space. |
| 128px | Opening top space and large panel chapter inset. |
| 256px | Space above and below the enterprise closing argument. |

### Containers and grids

- **main-container**: max width 1160px · side padding 16px. Centered alignment for navigation, feature artwork and pricing content.
- **chapter-enclosure**: max width 1696px · side padding 16px. Nearly full-width rounded chapters; at 1440px the visible enclosure is 1408px wide.
- **editorial-intro**: max width 544px. Narrow feature introduction inset one main-grid column from the left.
- **chapter-grid**: max width 1160px · 12 columns · gap 32px. Align text introductions, the journey rail and full-width product scenes.
- **proof-grid**: 3 columns · gap 24px. Three equal testimonial cards.
- **technical-grid** (only for technical product pages): 3 columns · gap 16px. Compact capability cards beneath a section heading.
- **faq-column** (only for pricing pages): max width 720px. Centered question list within the wider comparison-colored band.
- **campaign-shell** (only for pastel campaign pages): max width 1632px · side padding 48px. Broad photographic and editorial compositions, with film media centered at 1152px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | chapter panels | 16px |
|  | default actions | 8px |
|  | content cards | 12px |
|  | product window | 10px |
|  | split-flap cell | 4px |
| pricing pages | pricing controls | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | panel edge | `inset 0px 0px 0px 1px rgba(255,255,255,0.1)` | Subtle enclosure edge, not a floating drop shadow. |
| enterprise testimonial cards | sales card | `0px 10px 30px 0px rgba(0,0,0,0.35)` | Deep shadow behind slightly tilted technical proof cards. |

### Surfaces

#### Night canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #13111c; color: #f7f7f8`

#### Chapter enclosure · level 1

**Use:** Long feature chapter with an integrated product stage.

**CSS:** `background: #1b2132; border-radius: 16px; box-shadow: inset 0px 0px 0px 1px rgba(255,255,255,0.1); overflow: clip`

**Observed:** Blue is the default chapter variant; analytical chapters use deep blue green and customer proof uses muted plum. Each remains low-chroma and dark.

**Transfer:** Use the tint to distinguish a whole argument, not every individual card.

#### Interface well · level 2

**Use:** Framed demonstration within the atmospheric opening.

**CSS:** `background: #0d0c14; border: 1px solid rgba(255,255,255,0.1); border-radius: 10px; overflow: hidden`

**Observed:** The working scene reads as a coherent application window, not an array of isolated feature cards.

**Transfer:** Keep the frame and information hierarchy when rebuilding the new product's interface.

#### Glass proof · level 2

**Only for:** enterprise pages

**Use:** Metric grids over technical atmospheric art.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); border-radius: 8px; backdrop-filter: blur(12px)`

**Observed:** Nearly touching cards use a 4px grid gap and centered data.

**Transfer:** Keep the background detail subordinate to legible figures.

#### Comparison band · level 1

**Only for:** pricing pages

**Use:** Extended feature comparison and objection handling.

**CSS:** `background: #181622; padding: 128px 32px`

**Observed:** A broad unrounded band distinguishes dense rows from the darker surrounding page.

**Transfer:** Use for sustained technical comparison rather than a decorative interlude.

#### Pastel continuum · level 0

**Only for:** pastel campaign pages

**Use:** Continuous editorial story background.

**CSS:** `background: linear-gradient(#fefbf1 0%, #edddf2 72%, #edddf2 100%); color: #040406`

**Observed:** The later continuum moves through lilac dusk and lavender dusk to daylight blue; the visual progression crosses section boundaries.

**Transfer:** Preserve the long tonal progression rather than restarting a gradient on every section.

## Components

### Navigation bar

**Use:** Persistent orientation above dark marketing content.

**CSS:** `position: sticky; top: 0px; height: 72px; padding: 16px 0px; background: #13111c`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** Centered main-container holds a left identity, a compact middle menu with small downward chevrons, and two plain right-side actions. No oversized filled signup button.

### Primary button

**Use:** Default landing conversion.

**CSS:** `background: #553f83; color: #ffffff; border: 1px solid rgba(255,255,255,0.15); border-radius: 8px; padding: 12px 24px; height: 58px`

**Text style:** `button` — Inter 500 · 20px/1.6 · tracking -0.01em

**Observed:** A right arrow is part of the short label. It sits beside the Secondary button, not alone across the container.

### Secondary button

**Use:** Alternative route beside the default conversion.

**CSS:** `background: rgba(0,0,0,0.35); color: #ffffff; border: 1px solid rgba(255,255,255,0.25); border-radius: 8px; padding: 12px 24px; height: 58px`

**Text style:** `button` — Inter 500 · 20px/1.6 · tracking -0.01em

**Observed:** Equal typographic emphasis to the primary, with darker backing rather than a bright fill.

**States:** Declared: hover background-color rgba(255,255,255,0.1).

### Chapter chip

**Use:** Name the current capability chapter.

**CSS:** `display: inline-flex; align-items: center; background: rgba(255,255,255,0.08); color: #ffffff; border-radius: 8px; padding: 6px 12px`

**Text style:** `eyebrow` — Inter 500 · 14px/20px · tracking -0.005em

**Observed:** The neutral variant accompanies tinted enclosures. Green and warm amber label variants accompany plain-canvas chapters along the journey rail.

### Continuation link

**Use:** Continue a feature explanation without a new button block.

**CSS:** `display: inline-flex; align-items: center; color: #ffffff`

**Text style:** `section-support` — Inter 500 · 18px/1.6 · tracking -0.005em

**Observed:** Often ends the supporting paragraph inline; otherwise sits immediately beneath it.

### Testimonial card

**Use:** Detailed customer proof in a three-column group.

**CSS:** `background: rgba(255,255,255,0.05); outline: 1px solid rgba(255,255,255,0.25); outline-offset: -1px; border-radius: 12px; padding: 48px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** A second fine inset rectangle sits 8px inside the card. Company mark comes first, quote in the middle, avatar and attribution pinned toward the bottom; desktop cards are 360px wide and 500px tall.

**Transfer:** Keep comparable quote lengths so the attribution baseline stays coherent.

### Featured footer card

**Use:** Editorial promotions above footer utility information.

**CSS:** `background: #1c1a28; border: 1px solid rgba(255,255,255,0.1); border-radius: 12px; padding: 16px 24px`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Two stacked cards occupy a wider left column. Each combines a medium-weight title, short lavender phrase, muted description and underlined inline arrow link.

### Operational status

**Use:** A small reassuring instrument in the footer.

**CSS:** `display: flex; align-items: center; color: #42946e`

**Text style:** `status` — ui-monospace 400 · 12px/1.5

**Observed:** Sits beside the small identity mark below a thin divider; copyright aligns to the opposite side.

### Capability card

**Only for:** technical product pages

**Use:** Explain a set of product primitives.

**CSS:** `background: rgba(255,255,255,0.04); outline: 1px solid rgba(255,255,255,0.1); outline-offset: -1px; border-radius: 12px; padding: 24px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Small outlined icon above a semibold item title and short muted description. Three columns, with 16px gaps, within a tinted chapter.

### Metric card

**Only for:** enterprise pages

**Use:** Quantified reliability or scale proof.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); border-radius: 8px; backdrop-filter: blur(12px); padding: 64px 40px; text-align: center`

**Text style:** `stat` — Inter 600 · 32px/52px · tracking -0.05em

**Observed:** Number is filled with a vertical white-to-30%-white gradient; an explanatory sans-serif label sits directly beneath. The figure is visible light text, not black or invisible text.

### Pricing FAQ trigger

**Only for:** pricing pages

**Use:** Compact objection handling in a narrow column.

**CSS:** `width: 100%; height: 44px; color: #ffffff; background: transparent`

**Text style:** `item-heading` — Inter 600 · 16px/1.5

**Observed:** A lavender plus precedes the left-aligned question. Rows are separated by fine rules rather than enclosed in individual cards.

**States:** Declared: hover opacity 0.6; focus-visible opacity 0.6.

### Lead input

**Only for:** pricing conversion forms

**Use:** Collect a short qualification detail.

**CSS:** `background: rgba(19,17,28,0.5); border: 1px solid rgba(255,255,255,0.1); border-radius: 6px; padding: 8px 12px; height: 42px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** External label above the field; a 48px-padded translucent panel holds stacked fields, a file-upload zone and a full-width violet submit action.

## Imagery and graphics

### Illustrated night stage

**Use:** Signature atmosphere behind the opening promise and product demonstration.

**Observed:** A dark teal star field framed by hand-drawn violet-grey clouds; contours are visible but subdued. Clouds gather at the edges and lower corners, leaving a dark reading clearing at center. The scene fills the entire rounded hero enclosure behind both text and interface.

**Transfer:** Create a similarly restrained nocturnal world related to the new product's promise. Minimum version: an original cloud silhouette drawing and sparse stars over a deep blue-green ground, not a bright stock nebula.

**Build:** Use an SVG background covering the enclosure: deep blue-green base, sparse 1px–2px white dots at 10%–25% opacity, layered irregular cloud paths at the edges in muted violet-grey with darker 1px contour strokes. Add a translucent black top veil and a soft blue-green lower fade. Keep the central text zone almost empty.

### Product instruments

**Use:** Main feature demonstrations and opening application stage.

**Observed:** Dark application windows with thin borders contain connected service nodes, small status indicators, line charts and layered environment panels. Large scenes use the full 1160px content width; split features pair a narrow text column with an approximately 465px diagram.

**Transfer:** Show the new product doing a specific job. If the product has no screen, use connected labeled objects and an explicit before/after state instead of decorative dashboard filler.

### Journey rail

**Use:** Signature orientation device across capability chapters.

**Observed:** A fine vertical low-opacity colored rail sits left of the editorial column. Circular station rings and a slim outlined carriage-like marker interrupt it; the rail changes from cool green to warm amber as chapters change.

**Transfer:** Retain the progress-line and station grammar for a different sequence of capabilities, without requiring a transport subject.

**Build:** Draw a 6px-wide translucent colored vertical band with a brighter 1px center line. Place small hollow station circles at chapter starts. Add a slim rounded SVG capsule beside the line with several tiny outlined compartments. Use green at low opacity on dark canvas, with one amber chapter variation.

### Split-flap proof board

**Use:** Signature mechanical treatment for meaningful proof data.

**Observed:** A full-width airport-style board uses rows of individually framed black flaps, muted uppercase labels left and luminous numbers right. Each cell has a center hinge line and layered fine edges; the overall effect is physical rather than a generic counter strip.

**Transfer:** Use a few verified counts, durations or statuses. A static board is an acceptable minimum and retains the mechanical treatment.

**Build:** Build rows of fixed 44px × 56px cells with 2px column gaps, 4px corners, #0b0b0f fill and rgba(255,255,255,0.086) borders. Add a horizontal hinge at half height and subtle duplicated edge lines. Set 40px/56px monospace characters, grey labels and white values; center the board and clip the horizontal excess at the outer page boundary.

### Technical atmosphere

**Only for:** enterprise pages

**Use:** Back large commercial proof with intricate but low-contrast systems art.

**Observed:** Dense circuit-like architectural linework fills the opening; darker wireframe blocks flank statistics. A green matrix of tiny squares backs reliability figures, a violet dotted globe sits behind support cards, and repeated page-like outlines stand on a faint square grid in the assurance chapter.

**Transfer:** Choose one technical metaphor per chapter. Minimum version: original SVG contour stacks and a subdued dot or grid field, with clean text above.

**Build:** For outline stacks, repeat a tall angular closed path with black fill and 1px white strokes at 10%–20% opacity, offset by about 16px. Back it with crossed 1px rgba(255,255,255,0.04) grid lines. For the matrix use 8px squares, 4px gaps, green fill and a dark vertical fade. For the globe clip a violet dot field to an ellipse and darken its edges.

### Pastel theatrical collage

**Only for:** pastel campaign pages

**Use:** An emotionally playful editorial story, separate from the default technical aesthetic.

**Observed:** Pink clouds and a rainbow frame a cut-out seated person in pale clothing. A wide film still follows. Portraits appear as collectible white cards with black inner borders and colored nameplates; later, an uneven collage mixes portraits, tiny quotes and poster-like photographs. A surreal seated creature illustrates an interactive transformation slider.

**Transfer:** Art-direct original human or object imagery with soft daylight, pastel theatrical backing and deliberately earnest humor. Minimum version: one well-lit cutout, original cloud shapes, a framed film still and a coherent portrait series.

**Build:** Layer full-bleed pastel cloud photography or softly blurred SVG cloud masses behind a clean cutout. Use a broad multi-band translucent rainbow arc behind the subject. Build portrait frames at 315px × 425px with 12px white corners, an inset 2px black rectangle and a narrow colored bottom nameplate. Keep the scene oversized and let clouds cross section boundaries.

### Landscape ending

**Only for:** pastel campaign endings

**Use:** Final emotional release and integrated footer.

**Observed:** Huge white roman and italic serif imperatives float above a blue sky and rolling green grass. A small warm metallic box containing grass sits centrally in the landscape. Legal links and identity are placed directly on the darkened lower grass, not in the normal multi-column footer.

**Transfer:** End with a tangible object representing the new product's emotional reward, set within a tactile landscape. Use an original still-life composite if interactive 3D is unavailable.

**Build:** Use three overlapping rolling-hill image layers with realistic grass texture, a centered isolated object, and a bottom black gradient growing from transparent to roughly 66% opacity. Keep the sky simple behind the white headline and place the footer inside the landscape.

### Icons

**Observed:** Mostly outline SVGs with round caps, 1.5px–2px strokes; 20px–24px for feature marks and 12px chevrons in navigation. Icons use restrained violet, green or white rather than multicolor illustration.

**Transfer:** Use a consistent outline icon family. Preserve fine strokes and small scale; let chapter artwork carry the expressive role.

## Section recipes

How recurring sections are built.

### First screen: Night-world product opening

**Observed:** A 72px sticky Navigation bar sits above a 16px-gutter, 16px-radius enclosure. Back-to-front layers are illustrated sky, a dark veil, centered editorial copy, then the Interface well. The 54px serif headline spans about two fifths of the viewport width in a single line, with 128px top space inside the enclosure. Support follows after 24px; the Primary button and Secondary button follow after 32px with a 12px gap. Within the first 900px, the complete headline, support and actions are visible, and the upper approximately 400px of a 1064px-wide application scene is visible below them. The demonstration's lower portion and its compact chapter-navigation controls continue below the fold.

**Transfer:** Give a different product a concise emotional outcome and an equally tangible working scene. Rebuild a minimal interface or workflow diagram if no polished media exists. Technical product openings keep this centered type/action structure but replace sky art with a tabbed code stage; commercial openings use the 56px serif variant with either a two-column chart or centered architectural background. Pastel campaigns instead use their scoped photographic opening and paired serif/script question.

**Avoid:** Do not replace the illustrated enclosure with a naked black hero, enlarge the headline into a viewport-filling sans-serif block, or push all product evidence below the first screen.

**Text style:** `display` — IBM Plex Serif 500 · 54px/1.12 · tracking -0.0363em

### Journey chapter

**Observed:** Chapter chip, Heading and Section-support form a 544px introduction offset within the 12-column grid. The Journey rail sits to the left. Chip-to-heading gap is 32px and heading-to-support gap is 12px; the Continuation link can finish the paragraph. Large Product instruments follow after 80px; a three-column benefit group beneath uses 16px semibold titles and 16px/24px muted descriptions.

**Transfer:** Make each chapter explain one transformation, then show it, then summarize a few practical benefits. Alternate a full-width stage with a split diagram composition to vary density.

### Customer proof enclosure

**Observed:** Muted-plum Chapter enclosure with centered 40px serif heading, support, a small story link and three Testimonial cards after 64px. A second layer of smaller social quotations extends horizontally beneath the main cards.

**Transfer:** Use longer, attributed proof in the main row and short reactions in the secondary stream. Retain the two scales of evidence without requiring a particular customer category.

### Mechanical quantified proof

**Observed:** Centered Proof-heading and short support introduce the Split-flap proof board. The board occupies the full page width, unlike the constrained text above it.

**Transfer:** Turn meaningful product evidence into a physical instrument. Keep labels readable and values grouped by row, rather than presenting a decorative mass of random digits.

### Utility footer

**Observed:** A wider featured-card column sits left of a three-column, two-row link-group area with 32px group gaps. Muted 14px/20px links follow medium-weight headings. Compliance marks sit low on the left; a thin divider introduces the identity, Operational status and right-aligned copyright. Footer shell is 1280px wide with 48px side padding and 96px bottom padding.

**Transfer:** End ordinary marketing pages with editorial promotions plus useful navigation, not another oversized conversion banner. A commercial enterprise variant uses four simple link columns instead.

### Commercial comparison

**Only for:** pricing pages

**Observed:** A split opening pairs a 56px serif statement with a thin violet usage chart. A wide entry plan precedes three joined paid-plan columns; the center plan is taller, with 48px vertical padding versus 32px on its neighbors. A Comparison band contains a five-column table: feature names plus four plans, fine row rules and small green checks. Later, spend-threshold cards form a 720px column, followed by quote carousel, split lead form and Pricing FAQ triggers.

**Transfer:** Make the commercial logic visible before dense feature details. Use plan-specific blue, violet and neutral controls only within this page type.

### Enterprise instrument chapters

**Only for:** enterprise pages

**Observed:** Centered 40px sans-serif headings and muted support sit over Technical atmosphere. Metric cards form close-set three-column grids; later a two-column grid overlays the dotted globe. Large tilted testimonial panels and a black assurance panel provide contrasting proof constructions.

**Transfer:** Use architectural art to imply scale, but let quantified claims, attributed outcomes and readable assurance copy do the selling.

### Enterprise closing argument

**Only for:** enterprise pages

**Observed:** A 702px-wide left-aligned serif argument is isolated by 256px top and bottom padding. The final line is underlined. This leads to a centered 736px-wide glass conversion panel with one white sales action and an outlined self-service action, backed by dim logo tiles; the footer has four link columns, status, compliance marks and a blurred technical ground.

**Transfer:** Separate the final conviction statement from the conversion controls. Substitute a real product-specific argument and only the proof marks the new product can support.

**Text style:** `manifesto` — IBM Plex Serif 400 · 48px/1.33 · tracking -0.025em

### Technical questions and closing call

**Only for:** technical product pages

**Observed:** A narrow left title column accompanies a wider open question-and-answer grid. Questions are 16px semibold, answers are muted 16px/28px, and rows use 24px vertical insets with fine dividers. The ending returns to a centered two-line 40px Inter Tight promise, support, a glowing violet pill action and a shallow technical ground before the common footer.

**Transfer:** Use permanently readable answers when the product needs explanation. Reserve the glowing pill for this closing variant; the opening actions remain rectangular.

**Text style:** `technical-close` — Inter Tight 600 · 40px/1.2 · tracking -0.015em

### Pastel editorial story and ending

**Only for:** pastel campaign pages

**Observed:** A full-bleed theatrical opening gives way to a centered 88px Newsreader heading with italic emphasis, a 1152px-wide film, collectible portrait cards, a playful transformation control and an irregular proof collage. White FAQ rows sit over the long lilac-to-blue gradient. The final Landscape ending pairs a smaller roman setup with a 144px italic line and a white action, integrating the minimal footer into the grass.

**Transfer:** Use a coherent imaginative world and an emotionally concrete ending for campaign content. Preserve the shift from performance to reflection rather than importing the default dark table aesthetic.

**Text style:** `campaign-heading` — Newsreader Variable 400 · 88px/1.125

## Page flow

**Storyline:** Emotional promise → tangible working proof → capability chapters → attributed or quantified proof → objections and commercial choice → a deliberate closing gesture and useful footer.

### Broad product marketing landing page

1. **Promise** — Centered serif headline and paired actions inside a nocturnal illustrated enclosure.
2. **Product demonstration** — A large working application stage, compact chapter controls and customer marks.
3. **Capability chapters** — Journey-linked tinted enclosures alternate wide interfaces with split diagrams and small benefit groups.
4. **Social proof** — Plum testimonial chapter and a smaller horizontal stream of reactions.
5. **Quantified proof** — Large mechanical split-flap information board.
6. **Closing gesture** — A full-width technical artwork transition precedes featured editorial cards, utility columns, operational status and copyright.

**Transfer:** Keep the alternation between an emotional promise and concrete instruments; shorten or reorder chapters to fit the new product.

### Commercial evaluation and pricing

1. **Pricing promise** — Serif argument beside a thin usage chart.
2. **Pricing** — Broad entry plan, joined paid-plan trio and explicit unit rates.
3. **Comparison** — Long categorized five-column feature matrix.
4. **Expansion** — Spend-threshold unlock cards and a commercial-details action.
5. **Proof and conversion** — Quote carousel followed by explanatory steps beside an upload-and-contact form.
6. **Objection handling and ending** — Narrow accordion FAQ in a raised dark band, then the common promotional utility footer.

**Transfer:** Keep charges and limits explicit; let deeper comparisons remain denser than a general landing page.

### High-trust sales-led evaluation

1. **Promise and social proof** — Serif headline over architectural linework, white demo action and gridded customer marks.
2. **Quantified proof** — Glass statistic grids and a green reliability matrix.
3. **Attributed outcomes** — Large tilted quote panels.
4. **Capability and assurance** — Cost-benefit grid, globe-backed support metrics and an outlined assurance chapter.
5. **Closing argument** — Isolated large serif statement with an underlined final promise.
6. **Closing call and ending** — Glass two-action sales panel over dim logos, then a four-column footer with status and technical atmosphere.

**Transfer:** Substitute validated scale, performance and assurance material for the new audience.

### Technical product launch

1. **Promise and demonstration** — Centered serif opening, rectangular actions and tabbed code stage.
2. **Capability proof** — Small timing demonstration and a large dashboard scene.
3. **Capability inventory** — Compact three-column primitive cards.
4. **Pricing explanation** — Green-tinted scenario calculator with exact rates and a worked cost breakdown.
5. **Objection handling** — Open questions and answers beside a left heading column.
6. **Closing call and ending** — Two-line sans-serif closing promise, violet glowing action, technical ground and the common utility footer.

**Transfer:** Show the product's entry point, practical primitives and real usage model before asking for adoption.

### Emotion-led theatrical campaign

1. **Emotional hook** — Pastel photographic collage with a serif question and oversized script reply.
2. **Film** — Centered editorial heading and wide film stage.
3. **Human proof** — Collectible portrait cards followed by a surreal transformation interaction.
4. **Social proof** — Irregular photographic and quotation collage.
5. **Objection handling** — White serif FAQ rows over the descending pastel gradient.
6. **Closing call and ending** — Monumental italic imperative, white action, tactile landscape and minimal integrated legal footer.

**Transfer:** Use a distinct art-directed campaign world without making it the default product-page theme.

## Writing

Confident technical relief, with occasional dry warmth. The product absorbs complexity so the reader can work peacefully; precise explanations back up the short emotional promises.

**Do not copy:** Do not reuse Railway's name, logos, customer identities, testimonials, proprietary artwork, live counters, market-share claims, performance guarantees, prices or compliance claims. Replace them with original assets and substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. The product is named as the actor that handles the difficult parts; we appears in service or commercial offers.
- **Rhythm:** Short outcome-led headings contrast with one or two explanatory sentences. Paired fragments and restrained wordplay are common; technical FAQ answers become longer and explicitly qualified.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A concrete activity paired with an emotional or practical release. | 3–8 words | “Ship software peacefully”<br>“A full computer on demand” |
| Chapter heading | A practical capability followed by removal of friction; balanced fragments work well. | 4–12 words | “Instant networking. Zero setup.”<br>“Grow big without the growing pains” |
| Support | Say what the reader does, what the product handles and what no longer needs attention. | 1–2 sentences | “Connect your repo, [Brand] handles the rest. Auto-config, instant previews, no new tools to learn.” |
| Action | A direct verb and short object, often followed by an arrow. | 1–4 words | “Deploy →”<br>“Read the docs”<br>“Book a demo” |
| Commercial argument | Name a familiar waste or frustration, then offer a concrete correction. | 1–2 short sentences | “You're overpaying for compute. Let's fix that.” |
| Campaign line | Earnest emotional language punctured by a dry literal aside; restricted to the playful campaign voice. | A short imperative or question | “Touch grass”<br>“You are not a slop cannon.” |

**Words and phrasing to use:** peacefully; without the complexity; handles the rest; from the moment; by default; in minutes, not months; actually works; just pay for what it uses

**Avoid:** revolutionary ecosystem; unleash limitless potential; next-gen synergy; effortlessly magical; unsupported superlatives

**Rules:**

- Lead with the outcome, then identify the mechanism in ordinary language.
- Use technical nouns when they increase clarity; explain billing, isolation and lifecycle boundaries rather than burying them in slogans.
- Support numeric claims with a named unit, time period and relevant qualifier.
- Let wit come from a familiar frustration or a concrete metaphor, not from a stream of jokes.
- Use explicit question-and-answer prose for real adoption objections.

## Do's and Don'ts

### Do

- Keep the ordinary marketing canvas #13111c and default section titles in IBM Plex Serif at 36px/48px.
- Keep 16px gutters around 16px-radius chapter enclosures.
- Use the 544px introduction against an approximately 1160px demonstration for a strong text-to-object scale contrast.
- Preserve 12px heading-to-support spacing and 32px support-to-action spacing in the opening.
- Use 1px low-alpha edges to reveal panels without making them look metallic or glossy.
- Pair 58px actions with 8px corners in the opening.
- Include the journey rail and mechanical proof-board vocabulary as recognizable design devices.
- Keep the operational footer link monospace, green and 12px/18px.

### Don't

- Do not make violet the main page fill; #553f83 is a control color, not the canvas.
- Do not turn ordinary 8px-radius opening actions into full pills; that belongs to the technical closing variant.
- Do not use all-caps widely tracked sans-serif eyebrows; the chapter chips are sentence case at 14px.
- Do not replace the dark application stage with a collection of bright white dashboard cards.
- Do not flatten chapter panels into dozens of independently colored tiles.
- Do not make enterprise gradient figures transparent in appearance; their white gradient must remain visible.
- Do not import Tangerine script or 88px Newsreader headings into ordinary technical marketing chapters.
- Do not give every panel a large drop shadow; most depth comes from hairline edges and subtle tinted surfaces.

## Motion and responsive

### Motion

**Observed:**

- Declared button filter and color transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Declared horizontal marquee tracks use 90s linear infinite motion; social streams include 120s linear infinite motion.
- Some declared entrances transition opacity and transform over 0.98s cubic-bezier(0.2, 0.72, 0.16, 1).
- The campaign cloud flutter is declared at 13s ease-in-out infinite.

**Transfer:**

- Let ambient tracks drift slowly behind or beneath readable proof. Preserve the mechanical board's physical cell construction even when implemented as a static display.
- Use the short filter/color transition on compact controls rather than an exaggerated lift or bounce.

**Unknown:**

- Exact interaction choreography, board update schedule and scroll-trigger timing are not specified.

### Responsive

**Observed:**

- Dark-page styles declare width breakpoints at 376px, 768px and 1200px.
- The ordinary opening headline declares 40px on smaller widths and 54px at the larger variant. Opening support changes from 18px to 20px, while actions retain 32px line height.
- The technical capability grid declares one, two and three-column variants. The broad chapter grid uses 24px gutters before its 32px desktop gutters.

**Transfer:**

- On narrow layouts, preserve the night-world enclosure and emotional headline, then use a simplified vertical product diagram instead of squeezing the full desktop application.
- Stack the split feature layouts and retain a slim journey rail alongside the headings. Reflow the proof board into fewer label/value pairs while retaining individual flaps.
- Keep campaign cutouts subordinate to readable copy when the side-by-side theatrical opening collapses.

**Unknown:**

- Only desktop layouts are confirmed; exact mobile artwork placement, navigation behavior and breakpoint-specific heights are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
