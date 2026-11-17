# Fuser — luminous creative machinery

## Overview

A light, gallery-like style with the playful tactility of a creative workstation. Rounded grotesk headings and restrained interface sans text sit against pale gray canvases, while vivid photography, generative graphics and product demonstrations supply most of the color. Frosted controls, lilac light and a monumental graphic sign-off make the otherwise spacious pages feel alive. It suits tools that turn complex processes into expressive, tangible results.

### Essentials

- The work is the opening headline: a roughly 509px-high strip of overlapping, tabbed media nodes dominates the first screen, with a modest 30px/36px promise beneath it rather than giant type above it.
- Controls feel like illuminated hardware: 40px-high pale pill actions use 2px gray translucent edges, 12px backdrop blur and a soft pink–violet halo; the floating navigation is a 896px-wide, 54px-high glass bar with 16px corners.
- Headings have two gears: the default section voice is Marund 48px/1.1, weight 450, -0.025em tracking; dedicated topic introductions use 96px/1, weight 600, -0.05em tracking.
- The canvas stays almost colorless between exhibits: #fafafa backgrounds, #525252 body text and 160px section padding give saturated media room to breathe. Color occupies the framed work, small violet accents and atmospheric light—not solid-colored content bands.
- Images are objects in a working system: rounded gray node frames, tiny ports and thin connecting curves stage varied media sizes; repeat that device in an airy closing constellation. Without finished artwork, use real output samples or a small, well-made procedural composition in the same frames.
- The ending becomes a brand-scale sculpture: a black modular word graphic spans about 1152px above small footer columns on a full-width pink–lilac glow. Every new landing page needs this graphic sign-off, made from its own name or a short idea rather than ordinary oversized typesetting.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lilac control | `#a3b3ff` | `--color-lilac` | surface, border, action | Small demo actions and slider handles, not broad page fills. |
| Link violet | `#4f39f6` | `--color-link` | link, accent | Small editorial and announcement links. |
| Benefit violet | `#432dd7` | `--color-benefit` | text, accent | Offer labels and small check marks. |
| Lilac light | `#bcb8fb` | `--color-atmosphere` | background | Visible violet atmospheric wash from roughly 40% violet light over a pale field; strongest in the graphic sign-off. |
| Rose light | `#f6c6d3` | `--color-rose-light` | background | Visible pink component of the atmospheric sign-off and button halos; blend softly into lilac rather than making hard stops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Display black | `#000000` | `--color-black` | text, accent | Hero promise, dedicated topic display and graphic lettering. |
| Strong ink | `#0a0a0a` | `--color-strong-ink` | text | Selected controls, callout titles and pricing figures. |
| Ink | `#171717` | `--color-ink` | text | Default section headings, action labels and footer lettering. |
| Question ink | `#262626` | `--color-question-ink` | text | FAQ questions and numbered chapter paragraphs. |
| Secondary ink | `#404040` | `--color-secondary-ink` | text | Split-heading support paragraphs and callout detail. |
| Body gray | `#525252` | `--color-body` | text | Main support text and longer statements. |
| Muted gray | `#737373` | `--color-muted` | text | Section labels, inactive selectors and minor supporting labels. |
| Control edge | `#b7b7b7` | `--color-control-edge` | border | Visible control outline on canvas, made with 50% #737373. |
| Panel edge | `#d4d4d4` | `--color-edge` | border | Secondary media and pricing panel edges. |
| Frame gray | `#e5e5e5` | `--color-frame` | surface, border | Node framing, fine separators and prompt panel fill. |
| Glass gray | `#ebebeb` | `--color-glass` | surface | Visible navigation wash: 70% frame gray over the canvas; imagery remains visible beneath it. |
| Panel | `#f5f5f5` | `--color-panel` | surface | Neutral media backing and the darker end of subtle callout gradients. |
| Canvas | `#fafafa` | `--color-canvas` | background, surface | Default page field and pale media-frame rim; translucent action faces use this at 90% opacity. |
| Image text white | `#ffffff` | `--color-white` | text | Overlaid titles and captions on dark images. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Live port green | `#00c950` | `--color-port` | accent | Tiny connection ports on floating media nodes. |

## Typography

- **Marund** — Headlines, navigation labels, editorial prose and media captions. Soft, rounded grotesk with close-set display forms and light, open prose cuts. OpenType features: "ss00", "ss03". If unavailable, use **Inter**. Use 300–600 weights with the specified tracking; preserve rounded, compact proportions. Font stack: "Marund", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Inter Variable** — Support copy, conversion actions, commercial cards and footer links. Neutral interface sans that keeps the decorative workstation framing legible. Font stack: "Inter Variable", ui-sans-serif, system-ui, sans-serif.
- **Fira Code Variable** (only for process carousels) — Small two-digit process indices. Widely tracked technical numerals used as marginal annotations, not as a general text voice. Font stack: "Fira Code Variable", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| heading | Marund | 450 | 48px | 1.1 | -0.025em | size clamp(2.25rem, 7.2vw, 3rem) | Main section headlines, FAQ heading and closing call. |
| opening-promise | Marund | 400 | 30px | 1.2 | normal | fixed | Compact centered promise below the opening media stage. |
| statement | Marund | 400 | 30px | 1.4 | normal | fixed | Centered editorial statement with a small attribution beneath. |
| callout-title | Inter Variable | 500 | 24px | 1.25 | normal | fixed | Offer or contact-band title. |
| footer-tagline | Marund | 400 | 24px | 1 | normal | fixed | Compact two-line brand descriptor beside a symbol and vertical divider. |
| image-title | Marund | 400 | 22px | 1 | normal | fixed | Top-left title inside full-bleed image cards. |
| selector | Marund | 400 | 20px | 1.4 | normal | fixed | Demonstration selectors beneath large media. |
| question | Marund | 400 | 18px | 1.375 | normal | fixed | FAQ row text. |
| eyebrow | Marund | 400 | 16px | 1.5 | normal | fixed | Sentence-case gray section marker. |
| body | Inter Variable | 400 | 16px | 1.5 | -0.025em | fixed | Centered support paragraphs under section headlines. |
| opening-support | Inter Variable | 400 | 16px | 1.625 | normal | fixed | Opening support line, separated from the promise by 12px. |
| image-copy | Inter Variable | 400 | 16px | 1.5 | normal | fixed | Short bottom-aligned image-card descriptions. |
| action-large | Inter Variable | 500 | 16px | 1.5 | normal | fixed | Larger callout conversion action. |
| action | Inter Variable | 400 | 14px | 20px | normal | fixed | Standard pill labels, footer links and short commercial details. |
| navigation | Marund | 400 | 14px | 20px | normal | fixed | Compact navigation labels. |
| offer-label | Inter Variable | 500 | 14px | 20px | normal | fixed | Violet label above a commercial callout title. |
| footer-label | Inter Variable | 500 | 12.9px | 1 | 0.14em, uppercase | fixed | Footer column categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated topic and program introductions | topic-display | Marund | 600 | 96px | 1 | -0.05em | size clamp(2.5rem, 8.1vw, 6rem) | Bold centered introduction; usually one to three balanced lines. |
| numbered capability chapters | chapter-heading | Marund | 500 | 36px | 1.15 | normal | fixed | Narrow left-column headline beside a large media panel. |
| pricing pages | price | Inter Variable | 500 | 36px | 0.8 | normal | fixed | Whole currency amount with much smaller decimals and billing unit stacked at its right. |
| pricing pages | plan-title | Inter Variable | 500 | 24px | 32px | normal | fixed | Plan name at the top of a card. |
| process carousels | process-title | Marund | 600 | 24px | 1.25 | normal | fixed | Short verb heading under a thin fading rule. |
| dedicated topic and program introductions | topic-support | Marund | 300 | 20px | 1.5 | normal | size clamp(1rem, 3vw, 1.25rem) | Light centered explanatory paragraph. |
| interactive opening demonstrations | prompt | Marund | 400 | 20px | 1.375 | normal | fixed | Two-line prompt inside a floating input panel. |
| numbered capability chapters | chapter-body | Marund | 300 | 18px | 24px | normal | fixed | Compact supporting paragraph beneath a chapter headline. |
| editorial split-heading sections | split-support | Marund | 300 | 18px | 1.625 | normal | fixed | Right-column introduction next to a 48px heading. |
| dedicated topic and program introductions | topic-label | Marund | 500 | 16px | 1.5 | 0.025em | fixed | Small sentence-case topic marker above the display. |
| captioned media galleries | caption-title | Marund | 500 | 16px | 1.375 | normal | fixed | Title outside and below the image. |
| process carousels | process-body | Marund | 300 | 16px | 1.625 | normal | fixed | Light explanatory paragraph. |
| captioned media galleries | caption | Marund | 300 | 14px | 1.625 | normal | fixed | One or two descriptive lines 6px beneath the caption title. |
| process carousels | process-index | Fira Code Variable | 400 | 12px | 16px | 0.1em | fixed | Two-digit index aligned to the right of each title. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default opening promise is smaller than the 48px section headings because the media is the hero. Do not substitute the 96px topic-display recipe on ordinary immersive openings.
- Keep Marund's stylistic sets on its text; Inter remains neutral. Display tracking tightens sharply, while prose and small navigation stay normally tracked.
- Sentence-case section markers contrast with the tightly sized, widely tracked uppercase footer categories.

## Layout

**Density:** Airy at section scale, compact within controls and demonstration UI; major sections have 160px breathing room while labels and controls use 6–24px gaps.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Callout text stack and gallery caption-title-to-copy gap. |
| 8px | Compact control padding and footer link gaps. |
| 12px | Opening promise-to-support gap and footer label-to-links gap. |
| 16px | Image-card inset, grid gutter and FAQ icon-to-text gap. |
| 20px | Topic introduction stack and gallery gutter. |
| 24px | Centered section heading stack and pricing grid gutter. |
| 32px | Desktop section side padding and callout inset. |
| 40px | Demonstration-to-selector gap. |
| 64px | Large introduction-to-media gap and footer bottom padding. |
| 72px | Centered lead-to-demonstration separation. |
| 96px | Numbered chapter gutter and separation. |
| 160px | Default major section vertical padding. |
| 288px | Separation between sections on editorial topic pages. |

### Containers and grids

- **main**: max width 1152px · side padding 32px. Default centered media and footer width.
- **wide**: max width 1280px · side padding 32px. Wide demonstrations and split FAQ layout.
- **lead**: max width 672px. Centered support copy and standard lead stack.
- **statement**: max width 768px. Editorial statement and longer closing promise.
- **image-grid**: 3 columns · gap 16px. Portrait full-bleed work cards; six cards form two rows.
- **editorial-container** (only for editorial topic pages): max width 1280px · side padding 24px. Inset within the wide container, leaving 1232px of usable desktop width.
- **chapter** (only for numbered capability chapters): 2 columns · gap 96px. 288px narrative rail beside an approximately 848px media panel; media carries about two thirds of the available width.
- **caption-grid** (only for captioned media galleries): 3 columns · gap 20px. 397px-wide portrait media or asymmetric one-third/two-thirds spans.
- **plans** (only for pricing pages): max width 1280px · 3 columns · gap 24px. Equal-width, equal-height commercial cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | navigation-and-media | 16px |
|  | prompt-and-gallery-panels | 24px |
|  | floating-image-nodes | 7.2px |
| pricing pages | plan-actions | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media-lift | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | Image cards and floating output nodes. |
| inset-hardware | `inset 0px 0px 2px 0px rgba(0,0,0,0.3), inset 0px 1px 0px 0px rgba(0,0,0,0.1)` | Recessed prompt and small sculpted controls. |

### Surfaces

#### Canvas · level 0

**Use:** Main page field.

**CSS:** `background: #fafafa`

#### Work grid · level 0

**Use:** Opening and floating closing scenes.

**CSS:** `background-image: linear-gradient(rgba(0,0,0,0.035) 1px, transparent 1px), linear-gradient(90deg, rgba(0,0,0,0.035) 1px, transparent 1px), radial-gradient(circle at 1px 1px, rgba(0,0,0,0.045) 2px, transparent 2px); background-size: 64px 64px`

**Observed:** A low-contrast square grid with slightly darker registration intersections fades into the page near the edges.

**Transfer:** Use the grid only behind staged work, with a pale mask to keep it from reading as graph paper.

#### Glass navigation · level 3

**Use:** Floating global control bar.

**CSS:** `background: rgba(229,229,229,0.7); border: 1px solid rgba(115,115,115,0.5); border-radius: 16px; backdrop-filter: blur(40px) contrast(1.5) saturate(3); filter: drop-shadow(0px 4px 24px rgba(0,0,0,0.25))`

**Observed:** The bar remains translucent over neutral or colored media.

**Transfer:** Keep the glass material separate from the flat page canvas.

#### Media panel · level 1

**Use:** Broad inset media backing.

**CSS:** `background: #f5f5f5; border: 1px solid #e5e5e5; border-radius: 16px; overflow: hidden`

**Observed:** Wide topic introductions use a 16:10 panel; captioned portrait galleries use 24px corners, and numbered media use gray backing with a slightly stronger edge.

**Transfer:** Fill it with finished work or a real demonstration; let the backing appear around interface nodes.

#### Callout band · level 1

**Use:** Offer and contact information strip.

**CSS:** `background: linear-gradient(to bottom right, #f5f5f5, #fafafa); border: 1px solid #e5e5e5; border-radius: 16px`

**Observed:** A nearly flat pale gradient distinguishes the band without becoming a colored card.

**Transfer:** Reserve for a compact commercial proposition, not every feature.

#### Atmospheric sign-off · level 0

**Use:** Full-width graphic ending.

**CSS:** `background: radial-gradient(80% 40% at 40% 60%, rgba(97,95,255,0.4), transparent 100%), radial-gradient(80% 40% at -50% 40%, rgba(255,32,86,0.4), rgba(97,95,255,0.4), transparent 100%), radial-gradient(80% 50% at 150% 50%, rgba(255,32,86,0.4), rgba(97,95,255,0.4), transparent 100%), radial-gradient(200% 100% at 50% 100%, rgba(97,95,255,0.4), rgba(255,32,86,0.4), transparent 100%)`

**Observed:** Pale pink at the upper edge becomes richer violet through the center and bottom, with a fine soft grain and black graphic lettering.

**Transfer:** Match the broad glow and pink-to-lilac balance; exact gradient stops are not essential.

## Components

### Floating navigation

**Use:** Persistent global wayfinding.

**CSS:** `max-width: 896px; height: 54px; padding: 8px 8px 8px 16px; border-radius: 16px; background: rgba(229,229,229,0.7); border: 1px solid rgba(115,115,115,0.5); backdrop-filter: blur(40px) contrast(1.5) saturate(3); display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — Marund 400 · 14px/20px

**Observed:** Small symbol at left, compact category dropdowns with chevrons, then login, a bright conversion pill and a moon-like theme control. It floats in a sticky 70px header layer; a slim announcement ribbon sits above it at the page opening.

**Transfer:** Reduce category count before shrinking the labels; maintain the isolated glass-bar silhouette.

### Primary button

**Use:** Standard marketing conversion and editorial action.

**CSS:** `height: 40px; padding: 8px 10px 8px 16px; border: 2px solid rgba(115,115,115,0.5); background: rgba(250,250,250,0.9); color: #171717; border-radius: 9999px; backdrop-filter: blur(12px) contrast(1.5) saturate(5); display: inline-flex; align-items: center; gap: 4px`

**Text style:** `action` — Inter Variable 400 · 14px/20px

**Observed:** A right chevron closes the pill. A separate blurred pink–violet backglow surrounds it, while its face stays almost white. The navigation variant is 36px high with 6px 6px 6px 12px padding.

**Transfer:** Keep labels short enough that the pill remains a small luminous object rather than a banner.

### Callout button

**Use:** Offer-band conversion.

**CSS:** `height: 52px; padding: 12px 20px; border: 2px solid rgba(115,115,115,0.5); background: linear-gradient(to right, rgba(0,0,0,0), rgba(163,179,255,0.2)), rgba(250,250,250,0.9); border-radius: 9999px; color: #0a0a0a; backdrop-filter: blur(12px) contrast(1.5) saturate(5)`

**Text style:** `action-large` — Inter Variable 500 · 16px/1.5

**Observed:** A slightly larger chevron and a cool tint distinguish this from the standard primary pill; it remains accompanied by the same warm-cool backglow.

### Demo selector

**Use:** Switch between different output demonstrations.

**CSS:** `height: 44px; padding: 8px 20px; border-radius: 9999px; color: #0a0a0a; background: rgba(229,229,229,0.3); box-shadow: inset 0px 2px 8px rgba(161,161,161,1), inset 0px -2px 4px #ffffff`

**Text style:** `selector` — Marund 400 · 20px/1.4

**Observed:** The selected item looks recessed; unselected items are plain gray labels. The group sits 40px below media and uses generous 64px gaps.

**States:** Declared: hover color #0a0a0a on unselected items.

**Transfer:** Use a handful of meaningful short categories, not a dense filter toolbar.

### Image card

**Use:** Colorful gallery of possible results.

**CSS:** `border-radius: 16px; padding: 16px; display: flex; flex-direction: column; justify-content: space-between; gap: 8px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1); position: relative`

**Text style:** `image-title` — Marund 400 · 22px/1

**Observed:** Full-bleed portrait image behind a top-left title plus small symbol and a bottom-left description in image-copy. Cards are 352px by 414px in the desktop grid; text switches between black and white according to the image.

**Transfer:** Choose an image with usable text areas rather than adding a large opaque caption plate.

### FAQ row

**Use:** Plain-language objection handling.

**CSS:** `padding: 16px 0px; display: flex; gap: 16px; text-align: left; width: 100%; color: #262626`

**Text style:** `question` — Marund 400 · 18px/1.375

**Observed:** A 24px square slot holds a 20px plus at the left; question text follows. Each wrapper has a 1px #e5e5e5 top rule and the last one also has a bottom rule. Desktop rows sit in a 672px column opposite a narrow heading.

**States:** Declared: hover unspecified; focus-visible solid 2px outline, 2px offset, #7c86ff.

**Transfer:** Keep answers inside expandable rows, and preserve the plus-first rather than chevron-last arrangement.

### Offer band

**Use:** Low-pressure trial or organization-level proposition.

**CSS:** `padding: 32px; border: 1px solid #e5e5e5; border-radius: 16px; background: linear-gradient(to bottom right, #f5f5f5, #fafafa); display: flex; align-items: center; gap: 32px`

**Text style:** `callout-title` — Inter Variable 500 · 24px/1.25

**Observed:** Offer-label, callout-title and one action-sized detail line stack at the left with 6px gaps; Callout button sits at the right. The default band is 1024px wide and 148px high; commercial variants reach 1152px and grow for longer copy.

**Transfer:** Use for one clear commercial reassurance with a single action.

### Footer column

**Use:** Compact navigation under the graphic sign-off.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px; color: #171717`

**Text style:** `action` — Inter Variable 400 · 14px/20px

**Observed:** Footer-label heads a list of plain links separated by 8px; four columns sit to the right of the brand descriptor. The category headings are smaller and more tracked than the links.

**Transfer:** Keep the practical footer small relative to the word sculpture.

### Prompt panel

**Only for:** interactive opening demonstrations

**Use:** Make the product feel immediately usable within the opening stage.

**CSS:** `max-width: 448px; padding: 16px; border: 4px solid rgba(115,115,115,0.5); border-radius: 24px; background: #e5e5e5; backdrop-filter: blur(40px) contrast(1.5) saturate(3); box-shadow: inset 0px 0px 2px rgba(0,0,0,0.3), inset 0px 1px 0px rgba(0,0,0,0.1); display: flex; flex-direction: column; align-items: flex-end; gap: 10px`

**Text style:** `prompt` — Marund 400 · 20px/1.375

**Observed:** A two-line textarea sits above a small lilac Generate action aligned right. The panel overlaps the central node rather than replacing the output imagery.

**Transfer:** Use a real input only if it performs a meaningful action; otherwise show an honest, labeled product demonstration.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side commercial comparison.

**CSS:** `border: 1px solid rgba(212,212,212,0.7); border-radius: 16px; background: linear-gradient(to bottom right, rgba(240,242,249,0.3), #fafafa); display: flex; flex-direction: column; overflow: hidden`

**Text style:** `plan-title` — Inter Variable 500 · 24px/32px

**Observed:** Plan title and audience line precede a divided lower panel. A recessed 64px-high quantity capsule and lilac slider come before the compact price, dashed savings badge, check-mark list and bottom action. The recommended middle card gets an elevated badge and a soft green outer glow, not a solid saturated fill. Default side actions are 46px-high rounded rectangles with 12px corners; the recommended action uses a lilac treatment.

**Transfer:** Preserve the tactile quantity control and split-decimal price only when quantities genuinely affect cost.

### Process step

**Only for:** process carousels

**Use:** Explain participation or a multistep service without heavy cards.

**CSS:** `width: 288px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `process-title` — Marund 600 · 24px/1.25

**Observed:** A 1px fading horizontal rule sits above a verb heading with process-index at its upper right. Process-body explains the step below. The 20px-gutter horizontal rail overflows its container; a pale right-edge fade and arrow signal more content.

**Transfer:** Use short action verbs and keep each step a readable standalone block.

## Imagery and graphics

### Tabbed node stage

**Use:** Signature opening and major product demonstrations.

**Observed:** Multiple tall gray frames resemble tabbed node objects with small circular controls and side sockets. The central node is largest, flanked by smaller ones that continue off-screen. Media ranges from fashion and product photographs to pixel art, vivid acid-green/magenta generative visuals and miniature interface galleries. Rounded frames are light, beveled and softly shaded rather than dark browser chrome.

**Transfer:** Show outputs appropriate to the new product in a mix of scales. Minimum acceptable execution is three excellent real output images in custom SVG frames with a central overlapping product control; do not rely on generic laptop mockups.

**Build:** Draw an SVG frame with a 16px rounded main rectangle, a short rounded tab protruding at top left and a small side socket. Fill with frame gray, add a 1px semi-transparent gray stroke and a narrow pale inset rim; clip a photograph 8px inside. Add three 8px top circles and 4px side dots. Arrange five frames across a full-width clipped stage, about 323–403px wide and 407–509px tall at desktop, with the central one raised.

### Orbit of capabilities

**Use:** Signature ecosystem or breadth-of-output illustration.

**Observed:** An approximately 1152px-wide elliptical gray scaffold wraps around a large central portrait image. Two smaller images overlap the center, while pill labels ride the scaffold at its outer edges. A pale pink-violet haze sits behind it.

**Transfer:** Translate the labels into integrations, outputs or tools for the new product. With limited media, one strong central result and two detail views are sufficient.

**Build:** Use SVG elliptical arcs and four curved horizontal ribs in frame gray, with a fine gray edge and a soft inset highlight. Place a 350px-wide rounded image in the center and two 110–145px-wide detail cards over its lower-right and upper-left edges. Distribute eight pale inset pill labels around the arcs. Back with a low-opacity pink/lilac radial gradient.

### Closing constellation

**Use:** Signature airy conversion scene.

**Observed:** Eight differently sized media nodes drift around a centered heading and action on a faint grid and lilac haze. White rims and soft shadows turn photographs into small floating objects; tiny green circular input ports and triangular output ports sit at their horizontal midpoints. Some media extends beyond the scene edges.

**Transfer:** Keep a generous clear center for copy and surround it with real results, diagrams or cropped details from the product. Three or four distinct assets can be reused at different scales if the content library is small.

**Build:** Position mixed portrait and landscape images around a central empty oval, roughly 120–276px wide, with 6.9px pale padding, 7.2px outer corners and 5.8px image corners. Add the media-lift shadow, a 6px green circle at the left midpoint and a green triangle at the right. Use the Work grid with pale edge fades and a 10% violet radial glow behind the center.

### Modular word sculpture

**Use:** Required graphic sign-off above the practical footer.

**Observed:** Black letters are assembled from thick, softly pinched bead-like segments with rounded ends and diamond-shaped negative spaces. The word graphic occupies a single wide strip approximately 1152px by 230px over the atmospheric field; it reads as drawn artwork, not a font specimen.

**Transfer:** Create a distinct graphic of the new name or a short brand idea in the same modular spirit. If custom lettering is impractical, build a recognizable abstract emblem repeated into a wide sculpture; retain the black silhouette and monumental scale.

**Build:** Construct an SVG on a regular square grid. Use thick rounded strokes and overlapping circles as modules; connect horizontal, vertical and diagonal segments into letter skeletons, then union shapes. Cut small rotated-square counters where joints meet. Set fill to ink, no outline, and size the whole artwork to about four fifths of the desktop width.

### Atmospheric light and halos

**Use:** Unify the opening, glowing controls and closing graphic.

**Observed:** Soft violet and pink light spreads without distinct gradient bands. The opening has only a trace of color; the footer is much more chromatic and subtly grainy. Primary actions have a localized pink-violet glow while their text remains dark.

**Transfer:** Keep ordinary sections neutral, then intensify the same light at the closing signature. A blurred gradient is an acceptable minimum; preserve the luminous pale face of the controls.

**Build:** For a button, put an absolute pill-shaped layer behind the face, fill it with a pink-to-violet gradient at roughly 50% opacity and blur by about 12px; let the glow extend 8–16px outside the edge. For the footer use Atmospheric sign-off and overlay a very low-opacity monochrome SVG turbulence texture. Keep the light behind, never over, text.

### Editorial work gallery

**Only for:** topic and capability pages

**Use:** Show concrete outcomes and explain use cases.

**Observed:** Photoreal product studies, packaging, garments, interiors and cinematic collages fill rounded panels without device mockups. Numbered chapters use near-square large media; galleries alternate one-third/two-thirds landscape and portrait spans or show three equal portraits. Titles and short descriptions sit outside below the media.

**Transfer:** Use coherent art direction within each panel, but allow different panels distinct palettes. For abstract tools, combine one finished result with detail studies rather than using decorative stock photography.

### Creative computation studies

**Only for:** creative-tool feature pages

**Use:** Demonstrate expressive range.

**Observed:** Large video panels show iridescent blob fields, interactive image manipulations and code explanations. A three-card portrait gallery includes translucent organic forms, repeated figure geometry and luminous green point-cloud waves, mixing pale and black image backdrops inside a neutral page.

**Transfer:** Create actual procedural outputs related to the tool; a static well-rendered frame is preferable to an unrelated animated gradient.

### Documentary community photography

**Only for:** program and community pages

**Use:** Human proof of participation.

**Observed:** Natural-color event photographs show people working on laptops, a presenter and projected creative work. The broad lead photo is 16:10, followed by three portrait event images with simple captions; no duotone or heavy branded tint is applied.

**Transfer:** Photograph people engaged with the product in real spaces, and let room light and screens provide the color.

### Icons

**Observed:** Small filled SVG chevrons and symbols dominate: 16px navigation chevrons, 17px action arrows, 19px arrows in larger actions and 24px theme controls. Violet 14px checks mark commercial benefits. FAQ toggles use a typographic plus rather than a framed icon.

**Transfer:** Choose compact filled silhouettes with restrained detail. Keep chevrons aligned to the label baseline and reserve colorful marks for benefits or tiny live ports.

## Section recipes

How recurring sections are built.

### First screen: Immersive workbench opening

**Observed:** The first 897px is a complete media-first scene. Back to front: a gray-to-pale canvas, the Work grid with pink-lilac edge haze, a full-width clipped strip of tabbed media nodes beginning below the floating navigation, and a Prompt panel overlapping the lower center. The largest node is about 403px by 509px; neighboring nodes descend in scale and run off both edges. The object strip takes the broad middle of the screen, while the 30px opening-promise sits centered beneath it across roughly half the viewport width. A two-line 16px opening-support follows after 12px. Within the first 900px the navigation, media, prompt action, promise and support are all visible; the social-proof strip is below the fold. The only dominant action inside the scene is the small Generate pill, supplemented by the navigation conversion.

**Transfer:** Default new marketing pages to this product-stage composition, using a central result or interactive artifact and surrounding inputs or variations. If the new product has no native canvas, build three tabbed output frames around a real result and replace the prompt with a truthful compact action. Dedicated topic and program pages instead open at 256px with topic-label, topic-display, topic-support and one or two Primary buttons; a 16:10 Media panel begins 64px beneath. Commercial pages use the smaller 48px heading and restrained centered copy, leaving the plans below.

**Avoid:** Do not turn the opening into a conventional giant headline above a small screenshot, or use a dark full-bleed dashboard as its main visual. Do not enlarge the supporting promise to compete with the media.

**Text style:** `opening-promise` — Marund 400 · 30px/1.2

### Centered capability exhibit

**Observed:** A 672px-wide lead stack uses eyebrow, heading, body and Primary button separated by 24px. The section has 160px vertical padding. After about 72px, a wide Tabbed node stage or product output demonstration fills 896–1024px of width; Demo selectors sit 40px below it.

**Transfer:** Give each major capability one clear promise and one large visual example; change the demonstration content without changing the quiet text hierarchy.

**Text style:** `heading` — Marund 450 · 48px/1.1 · tracking -0.025em

### Image-led proof gallery

**Observed:** A centered lead introduces Image cards arranged in three columns with 16px gaps. The 352px by 414px cards carry small title/icon pairs above and short descriptions below, both directly over the image.

**Transfer:** Use outcomes, example projects or results that establish range; let the image collection carry the color rather than tinting each card shell.

### Orbit proof

**Observed:** A centered heading and restrained support sit above Orbit of capabilities. Small counts appear in the eyebrow rather than as giant statistics. A short reassurance and a monochrome provider-logo row follow below.

**Transfer:** Turn breadth into a spatial system around a strong result. Use counts only when verifiable and keep them subordinate to the image.

### Editorial heading pair

**Observed:** Across a 1232px content area, a 48px heading occupies an approximately 416px left column while split-support occupies a 576px right column. A gallery or full-width Media panel follows after 64–88px; the sides align with the media edges.

**Transfer:** Use for richer explanatory pages when a centered lead would become too tall. Place the action below the left heading if needed.

**Text style:** `heading` — Marund 450 · 48px/1.1 · tracking -0.025em

### Split FAQ

**Observed:** A 48px heading wraps into a narrow left column. FAQ rows form a 672px right column with fine horizontal rules and no enclosing card; the reference layout spans a 1280px container.

**Transfer:** Answer the few questions that prevent action; use the same restrained outline treatment regardless of page length.

**Text style:** `heading` — Marund 450 · 48px/1.1 · tracking -0.025em

### Editorial statement

**Observed:** A muted eyebrow sits above a centered 768px-wide statement in 30px/42px type. A small two-person attribution and role are separated from the paragraph by 80px; the whole section retains 160px vertical padding.

**Transfer:** Use for an earned point of view, founder note or meaningful testimonial. Keep it typographically quiet instead of turning it into a giant quote mark.

**Text style:** `statement` — Marund 400 · 30px/1.4

### Floating conversion scene

**Observed:** Closing constellation surrounds a centered 48px heading and Primary button on Work grid. The composition spans about 957px of page height; a large clear center and pale edge masks keep the scattered imagery from crowding the action.

**Transfer:** Include this output-centered signature somewhere on a new landing page; it can introduce a result gallery or close the story. Supporting topic pages can use a simpler centered heading, support and one or two pills before the same graphic sign-off.

**Text style:** `heading` — Marund 450 · 48px/1.1 · tracking -0.025em

### Graphic sign-off and footer

**Observed:** Atmospheric sign-off forms an approximately 927px-tall ending with 160px top padding. Modular word sculpture sits above the practical footer, followed by 80px breathing room. A symbol, 48px vertical divider and footer-tagline sit on the left; four Footer columns align on the right. Small copyright and privacy links sit low at left, with 64px bottom clearance. The same graphic ending anchors all page types.

**Transfer:** Always provide a brand-scale graphic release after the content. Make the lettering or emblem specific to the new identity while retaining black artwork over luminous pink-lilac light.

### Numbered capability chapter

**Only for:** topic and feature pages

**Observed:** A 288px left narrative rail, 96px gutter and 848px-wide, 800px-high media panel create a strongly asymmetric pair. Chapter-heading and a small two-digit marker share the first row, followed by chapter-body after 20px. The narrative rail remains vertically engaged with the tall media as the reader scrolls. Chapters are separated by 96px.

**Transfer:** Explain a small number of distinct capabilities through substantial demonstrations, not equal-size icon cards.

**Text style:** `chapter-heading` — Marund 500 · 36px/1.15

### Tactile commercial comparison

**Only for:** pricing pages

**Observed:** A small centered introduction is followed by Offer band, compact monthly/annual pills, then three Plan cards with 24px gutters and about 696px height. The quantity controls and unusual split-decimal prices are prominent; the middle plan is gently illuminated. A second Offer band handles a larger commercial need. Later a restrained interactive cost table uses small pastel modality tags and 44px rows rather than marketing-sized cards.

**Transfer:** Use interactive quantities only where cost changes meaningfully. Keep explanatory controls in product-ui scale and preserve the pale material instead of making the recommended card dark.

**Text style:** `price` — Inter Variable 500 · 36px/0.8

## Page flow

**Storyline:** Tangible promise → concrete work → breadth or capability proof → commercial reassurance → objections → renewed invitation → graphic brand release.

### Immersive product marketing landing page

1. **Promise** — A media-first workbench makes the result tangible, with a modest promise beneath it.
2. **Social proof** — Small customer marks sit in a quiet strip between fine fading rules.
3. **Capability demonstration** — Centered leads alternate with large output demonstrations, a colorful work-card gallery and selectors.
4. **Commercial reassurance** — A flexibility message leads into a pale trial callout.
5. **Breadth proof** — An orbit illustration combines output media, small labels and provider marks.
6. **Objection handling** — Split FAQ gives way to a short editorial statement.
7. **Closing call** — A floating media constellation invites action before the glowing graphic footer.

**Transfer:** Use a few strong product exhibits rather than repeating identical feature cards; keep the constellation and graphic release even with a shorter narrative.

### Audience or use-case exploration

1. **Promise** — Bold centered topic display and a concrete review-board photograph establish a shared problem.
2. **Capability chapters** — Three asymmetric numbered chapters show decisions, outcomes and useful handoff.
3. **Range proof** — Split headings introduce an asymmetric gallery and a three-portrait gallery with external captions.
4. **Objection handling** — A split FAQ addresses fit and adoption.
5. **Closing call** — A centered invitation and paired pills precede the common graphic footer.

**Transfer:** Organize the story around the reader's decisions and deliverables, using tailored finished-work media rather than sector icon tiles.

### Commercial decision and cost explanation

1. **Promise** — Compact 48px centered heading and plain flexibility copy.
2. **Pricing** — Trial band, billing toggle and three tactile adjustable Plan cards.
3. **Alternative path** — A pale organization-level contact band.
4. **Cost education** — A centered lead introduces a detailed interactive comparison table.
5. **Objection handling** — Commercial FAQ resolves billing and ownership concerns.
6. **Closing call** — A brief contact invitation leads to the shared glowing graphic footer.

**Transfer:** Keep the commercial page calmer than the immersive landing page, but retain the same pills, glass materials and brand-scale ending.

### Explain one expressive product capability

1. **Promise** — A bold topic display, light paragraph and paired action/guide pills introduce a large live-tool demonstration.
2. **Product explanation** — An editorial heading pair leads to a full-width workflow example.
3. **Capability chapters** — Numbered media-led chapters demonstrate different modes of use.
4. **Range proof** — Three portrait computational studies make the underlying tools tangible.
5. **Objection handling** — A split FAQ answers technical fit questions.
6. **Closing call** — A short creative imperative and paired pills lead to the common graphic footer.

**Transfer:** Explain the mechanism in plain language and prove it with actual outputs; the visual media may be vivid while the surrounding page stays neutral.

### Community or participation program

1. **Invitation** — Bold centered title and a short participation promise introduce a wide media panel.
2. **Human proof** — A split editorial introduction leads to a documentary group photograph and caption.
3. **Process** — A horizontally scrolling sequence uses verb titles, fine rules and small mono indices.
4. **Activity proof** — Three portrait event photos with short external captions demonstrate real participation.
5. **Closing call** — A compact contact invitation precedes the same luminous graphic footer.

**Transfer:** Swap polished product output for genuine participation imagery and make eligibility/process explicit without changing the brand's type and materials.

## Writing

Confident but companionable, with practical explanations of what the reader can make and how the work moves forward. Creative encouragement is balanced by concrete mechanisms, costs and choices rather than sweeping transformation claims.

**Do not copy:** Do not reuse Fuser's name, marks, modular wordmark, proprietary imagery, customer/provider endorsements, founder quotations, model counts, credit allocations, prices, trial terms or factual performance claims. Source examples illustrate cadence only; replace them with truthful content for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we when explaining a considered product decision; name the product when a mechanism needs clarity.
- **Rhythm:** Headlines are short statements, often conversational fragments or paired beats. Supporting paragraphs usually contain two to four clear sentences with active verbs. Actions are compact imperatives; technical detail is explained without ceremonial language.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Identify the tool and intended user plainly; let the visual do the emotional work. | 8–12 words | “The node-based AI workflow builder for creative teams” |
| Section headline | A familiar expression or clipped contrast makes a practical benefit memorable. | 5–9 words | “Now, there’s an app for that.”<br>“Busy month. Quiet month. Both work.” |
| Supporting line | Name the object, explain the mechanism, then connect it to the next task. | 20–45 words | “Recipes are prebuilt AI workflow templates. Bring a product image, logo or brief, then adapt a working process to your next project.” |
| Capability explanation | Start with the reader's decision or action, then show what makes it usable. | 25–50 words | “Create imagery and video, explore a 3D asset, compose an editable layout or build a live website.” |
| Primary action | Verb plus a concrete next step; avoid exaggerated commitment. | 2–6 words | “Get Started”<br>“Start a sketch”<br>“Bring your team’s next brief” |
| Closing invitation | A small creative imperative or open-ended question lowers pressure. | 4–8 words | “Go make something new”<br>“Give the idea some rules.”<br>“Something else in mind?” |

**Words and phrasing to use:** make; build; bring; work; your team; next; canvas; sketch; refine; reuse; live; one click

**Avoid:** revolutionary; game-changing; unleash your potential; supercharge; synergy; limitless possibilities; best-in-class

**Rules:**

- Lead with work the reader recognizes before naming the underlying technology.
- Use a concrete noun in most conversion labels.
- Explain commercial flexibility in ordinary language and state limits honestly.
- Keep small section markers in sentence case; reserve all caps for footer categories.
- Allow a witty headline, then follow it with useful explanation rather than another slogan.

## Do's and Don'ts

### Do

- Keep the opening's 30px promise subordinate to a roughly 509px media stage.
- Use 48px/1.1, weight 450 and -0.025em tracking for ordinary section headings.
- Keep body support in a 672px column even when media expands to 1152px.
- Give major landing sections 160px vertical padding and compact lead stacks 24px gaps.
- Pair pale 40px pills with translucent edges and localized pink-violet backglow.
- Use 16px gutters for overlay image cards and 20px gutters for external-caption galleries.
- Make the black graphic sign-off span roughly four fifths of the desktop width.
- Keep FAQ questions at 18px with plus-first 24px icon slots and fine gray separators.

### Don't

- Do not apply the 96px, weight-600 topic display to every section.
- Do not replace the rounded glass navigation with a full-width opaque header band.
- Do not turn violet into a default solid card or section background; the main field is #fafafa.
- Do not use the tiny green ports as general-purpose marketing highlights or large badges.
- Do not wrap the FAQ in shadowed cards; its only separators are 1px rules.
- Do not make every media panel a browser mockup; the tabbed node silhouette is different.
- Do not use mono for the main editorial voice; it is restricted to small process indices.
- Do not replace the graphic footer with plain oversized sans text above an otherwise conventional link list.

## Motion and responsive

### Motion

**Observed:**

- Controls declare 0.2s transitions; navigation labels declare 0.3s with cubic-bezier(.4, 0, .2, 1).
- Demonstration selector surfaces declare all 0.2s cubic-bezier(.4, 0, .2, 1); larger output cards declare all 0.5s with the same curve.
- Marquees declare 25s linear infinite motion. The small assistant sparkle declares a 4s ease-in-out infinite animation.
- Numbered chapter narrative rails use sticky positioning with scroll-related translation; process galleries use horizontal snap scrolling.

**Transfer:**

- Keep the luminous pill face readable while light or nearby media moves.
- Use slow continuous drift for breadth demonstrations and short state changes for controls; do not apply looping motion to prose.
- Keep the graphic sign-off strong as a static composition rather than depending on an entrance animation.

**Unknown:**

- Exact scroll choreography and timing of node-stage changes are unspecified.
- No complete hover sequence or reduced-motion behavior is established.

### Responsive

**Observed:**

- Fluid topic display uses clamp(2.5rem, 8.1vw, 6rem); section headings use clamp(2.25rem, 7.2vw, 3rem); topic support uses clamp(1rem, 3vw, 1.25rem).
- Layout declarations include single-column to three-column galleries, stacked chapter pairs and horizontally snapping media rails. Numeric breakpoint thresholds are unspecified.

**Transfer:**

- On narrow screens retain the central node and partial neighbors rather than miniaturizing the complete wide stage.
- Stack editorial heading pairs and place chapter text beneath its media; remove sticky translation from the narrow layout.
- Use a horizontal media rail when portrait cards would become too narrow, retaining visible partial next content.
- Let the word sculpture scale as one SVG artwork and reflow practical footer columns beneath it.

**Unknown:**

- Exact mobile navigation, spacing and image arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
