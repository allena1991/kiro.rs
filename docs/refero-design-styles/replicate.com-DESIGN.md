# Replicate — electric developer workbench

## Overview

An approachable developer workbench wrapped in exuberant digital color. White and charcoal foundations, hot pink and red surrounds, and acidic yellow fluid art contrast with square-edged panels and matter-of-fact grotesk and monospace typography. It suits technical products that can show tangible inputs and outputs, with dense working examples balanced by expansive statements and playful media collages.

### Essentials

- The promise sits on an electric halftone field rather than a neutral billboard: white 72px/1 bold display type with -0.025em tracking, left aligned above a working demonstration in an approximately 894px opening.
- Practical controls stay unapologetically rectangular: black primary buttons with 1px borders, 0px radius, 54px height and 12px 16px padding; secondary actions use 42px height and 8px 12px padding.
- Color behaves like a surround, not a card theme: white dominates reading areas; a pink-to-red gradient forms narrow exposed gutters around off-white technical chapters and a charcoal proof chapter. The opening and thin closing stripes carry the most saturated fluid color.
- Technical credibility is staged as input beside output: an off-white 672px code panel with 14px/20px monospace text joins a 448px visual result, with sharp corners and a shared 288px height.
- Include a kinetic catalog device: 480px × 160px bordered cards in edge-clipped horizontal rows, square thumbnails occupying roughly one third, compact metadata and red activity labels. For products without a catalog, use examples or customer-created outcomes.
- Include a monumental word-and-media sculpture: 128px/1 bold black words interleave with 208px-high rectangular demonstrations across an expansive white field. Use original interface recordings or simple outcome stills when rich media is unavailable; carry the electric art into three narrow stripes near the footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#ea2804` | `--color-red` | accent, text, border | Capability headings, technical rules, diagrams and gradient surround. |
| Electric pink | `#ff6bfc` | `--color-pink` | background, accent | Gradient surround and fluid art. |
| Deep pink | `#e54fe2` | `--color-pink-deep` | background | Opening gradient under fluid media. |
| Coral blush | `#f97e82` | `--color-blush` | background | Warm endpoint of the technical chapter surround. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#e8ff00` | `--color-acid` | accent, background | Luminous lobes within fluid artwork, not text or ordinary controls. |
| Warm red link | `#dd4425` | `--color-red-link` | text, border, link | Outlined actions inside technical chapters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, surface | Main canvas and reversed text. |
| Warm white | `#fffcfc` | `--color-red-wash` | surface | Backing for warm red outlined actions. |
| Off-white workbench | `#fcfcfc` | `--color-panel` | surface, text | Code and catalog panels. |
| Soft gray | `#f9f9f9` | `--color-soft` | surface, background | Thumbnail backing, data bands and contact section. |
| Band gray | `#f0f0f0` | `--color-band` | surface, border | Trust bands, conversion bands and subtle panel dividers. |
| Faint edge | `#e8e8e8` | `--color-edge` | border, surface | Catalog pricing card outlines and shortcut backing. |
| Rule gray | `#e0e0e0` | `--color-rule` | border | Footer and data row separators. |
| Secondary gray | `#646464` | `--color-muted` | text | Descriptions, navigation and captions. |
| Charcoal ink | `#202020` | `--color-ink` | text, background, border | Primary text, strong card edges and dark proof chapter. |
| Action black | `#000000` | `--color-black` | action, background, border | Filled conversion controls. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Online green | `#2b9a66` | `--color-status` | accent | Small online indicator, not a marketing accent. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise sales pages | Enterprise blue | `#3358d4` | `--color-blue` | text, background, border | Single-color halftone art, highlighted headline and benefit borders. |
| enterprise sales pages | Enterprise icon wash | `#edf2fe` | `--color-blue-wash` | surface | Circular icon backing. |
| pricing pages | Data note gray | `#838383` | `--color-tertiary` | text | Subordinate annotations in detailed pricing data. |

## Typography

- **basier-square** — Body copy, controls, navigation and enterprise headings. Open, squared grotesk with an unpretentious software-tool tone. If unavailable, use **Inter**. Use regular body and bold enterprise headings; preserve compact widths. Font stack: "basier-square", "Inter", ui-sans-serif, system-ui, sans-serif.
- **rb-freigeist-neue** — Marketing headings and monumental word sculpture. Expressive grotesk; light section headings contrast with emphatic bold display words. If unavailable, use **DM Sans**. Use weights 400, 600 and 700; keep the tight display tracking. Font stack: "rb-freigeist-neue", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **jetbrains-mono** — Code, technical values and rate tables. Crisp, highly legible developer monospace. Font stack: "jetbrains-mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | rb-freigeist-neue | 700 | 128px | 1 | normal | Oversized words interleaved with demonstration media. |
| display | rb-freigeist-neue | 700 | 72px | 1 | -0.025em | Two-line opening promise in white. |
| heading | rb-freigeist-neue | 400 | 48px | 1 | normal | Main marketing section headings, centered or left aligned. |
| capability | rb-freigeist-neue | 600 | 30px | 1.2 | normal | Red technical chapter and dark proof card titles. |
| hero-support | basier-square | 400 | 24px | 32px | normal | Short opening explanation. |
| lead | basier-square | 400 | 20px | 1.4 | normal | Section support and closing paragraph. |
| body-lg | basier-square | 400 | 18px | 28px | normal | Large button labels and dark proof descriptions. |
| label-strong | basier-square | 600 | 18px | 28px | normal | Footer group titles and enterprise card titles. |
| body | basier-square | 400 | 16px | 1.5 | normal | Ordinary reading copy and medium buttons. |
| small | basier-square | 400 | 14px | 20px | normal | Navigation, card descriptions and compact footer labels. |
| code | jetbrains-mono | 400 | 14px | 20px | normal | Short code demonstrations and aligned numerical rates. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| enterprise sales pages | enterprise-display | basier-square | 700 | 72px | 1 | normal | Centered promise with a solid blue highlighted second line. |
| enterprise sales pages | enterprise-heading | basier-square | 700 | 48px | 1 | normal | Bold capability and contact headings. |
| pricing pages | pricing-title | rb-freigeist-neue | 600 | 36px | 1.25 | -0.025em | Plain utility-page title. |
| company editorial pages | editorial-heading | rb-freigeist-neue | 400 | 36px | 40px | normal | Mission and recruitment headings. |
| pricing pages | utility-heading | rb-freigeist-neue | 400 | 24px | 32px | normal | Anchor-linked pricing subsections and compact conversion band heading. |
| enterprise sales pages | enterprise-lead | basier-square | 400 | 20px | 1.625 | normal | Relaxed gray descriptions alongside blue graphic panels. |
| company editorial pages | art-caption | basier-square | 400 | 13px | 1.5 | normal | Right-aligned art attribution beneath a wide image. |

**Notes:**

- Regular 48px marketing headings deliberately feel lighter than the bold opening and 128px sculpture. Do not normalize all headings to semibold.
- Negative tracking belongs to the 72px opening and 36px utility title; most other roles keep normal tracking.
- Monospace is a distinct layer of working detail, not the default body face.

## Layout

**Density:** Airy chapters around compact working panels; reading sections breathe while code, metadata and tables remain dense.

### Spacing

**Spacing system:**

- **rhythm** 8px, vertical — Primary vertical rhythm; 6px and 10px local gaps serve compact text and form groups.

| Value | Use |
| --- | --- |
| 8px | Icon gaps and heading-to-description gaps in small cards. |
| 16px | Heading-to-support spacing and paragraph separation. |
| 24px | Technical panel padding and hero-to-demo gap. |
| 32px | Major grid gaps, CTA separation and benefit padding. |
| 48px | Technical two-column gaps and sculpture row spacing. |
| 64px | Desktop page side padding and utility section separation. |
| 96px | Major chapter vertical breathing room. |
| 160px | White lead-in to monumental word sculpture. |

### Containers and grids

- **Marketing container**: max width 1920px · side padding 64px. Broad centered desktop canvas; at 1440px the usable width is 1312px.
- **Reading measure**: max width 672px. Support paragraphs and contact forms.
- **Heading measure**: max width 768px. Centered marketing heading with balanced two-line wrapping.
- **Technical chapter**: max width 1280px · 2 columns · gap 48px. Inset off-white workbench with prose beside code and nested left rules.
- **Dark proof grid**: 2 columns · gap 64px. Two-by-two diagrams and explanation cards inside the charcoal chapter.
- **Pricing grid** (only for pricing pages): max width 1152px · 3 columns · gap 16px. Compact media-led rate examples.
- **Rate table** (only for pricing pages): max width 896px. Left-aligned utility reading and detailed rate comparison.
- **Enterprise benefit grid** (only for enterprise sales pages): max width 1280px · 3 columns · gap 32px. Blue-outlined centered benefits.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Buttons and panels | 0px |
|  | Filter pills | 9999px (pill) |
|  | Category shelf upper corners | 4px |
| enterprise sales pages | Icon medallions | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Opening code panel | `0px 25px 50px -12px rgba(0, 0, 0, 0.25)` | Single floating workbench panel over electric media; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default reading ground.

**CSS:** `background: #ffffff; color: #202020`

#### Electric surround · level 0

**Use:** Exposed color around technical and dark chapters.

**CSS:** `background: linear-gradient(to right bottom, #ff6bfc, #ea2804, #f97e82)`

**Observed:** The color appears mainly as narrow outside gutters, not as a full colored reading surface.

**Transfer:** Keep prose on opaque interior panels while the surround ties adjacent chapters together.

#### Opening underpainting · level 0

**Use:** Backing beneath the fluid halftone artwork.

**CSS:** `background: linear-gradient(to right bottom, #ff6bfc, #e54fe2, #ea2804)`

**Observed:** Fluid yellow and magenta media and a white top fade sit over this backing.

**Transfer:** Layer the electric art above the gradient rather than expecting the gradient alone to carry the scene.

#### Technical paper · level 1

**Use:** Long capability explanations and working examples.

**CSS:** `background: #fcfcfc; border-top: 1px solid #ea2804; border-left: 1px solid #ea2804; padding: 24px`

**Observed:** Nested left and top rules create progressively inset technical chapters.

**Transfer:** Use rules as structural connectors between related capabilities.

#### Charcoal proof · level 1

**Use:** Operational proof, rates and scale stories.

**CSS:** `background: #202020; color: #ffffff; padding: 96px 144px`

**Observed:** Centered heading and monochrome logos precede open red-ruled diagram cards; this is an inset chapter inside the electric surround.

**Transfer:** Keep charts and technical details in red with white descriptions, rather than adding unrelated data colors.

#### Utility band · level 0

**Use:** Trust and compact conversion bands.

**CSS:** `background: #f0f0f0; padding: 32px`

#### Contact ground · level 0

**Only for:** enterprise sales pages

**Use:** Full-width contact section.

**CSS:** `background: #f9f9f9; padding: 64px 0px`

## Components

### Navigation

**Use:** Compact top-level orientation above the visual promise.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 32px; padding: 0px 64px; height: 72px; max-width: 1920px`

**Text style:** `small` — basier-square 400 · 14px/20px

**Observed:** A 40px announcement strip sits above the bar. The left cluster pairs a 32px-high identity with a 512px-wide search field; the right cluster holds restrained text links and a compact black action. The opening uses a white atmospheric fade; utility pages use a translucent white fixed header.

### Primary button

**Use:** Opening conversion and major sales actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 0px; padding: 12px 16px; height: 54px`

**Text style:** `body-lg` — basier-square 400 · 18px/28px

**Observed:** A small leading lightning or conversation icon gives the otherwise plain rectangle a specific purpose. Contact submission stretches to the form width.

### Compact primary button

**Use:** Section and closing conversions.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 0px; padding: 8px 12px; height: 42px`

**Text style:** `body` — basier-square 400 · 16px/1.5

**Observed:** Pairs closely with a white outlined alternative; label width determines overall width.

### Secondary button

**Use:** Alternative action beside a filled control.

**CSS:** `background: #ffffff; color: #202020; border: 1px solid #202020; border-radius: 0px; padding: 8px 12px; height: 42px`

**Text style:** `body` — basier-square 400 · 16px/1.5

**Observed:** Same rectangular silhouette and baseline as the compact primary action.

### Warm outline action

**Use:** Capability-specific documentation links.

**CSS:** `background: #fffcfc; color: #dd4425; border: 1px solid #dd4425; border-radius: 0px; padding: 8px 12px; height: 42px`

**Text style:** `body` — basier-square 400 · 16px/1.5

**Observed:** Used within off-white technical chapters; on charcoal the background becomes transparent.

### Catalog card

**Use:** Dense horizontal proof of a working ecosystem.

**CSS:** `background: #fcfcfc; border: 1px solid #202020; border-radius: 0px; width: 480px; height: 160px`

**Text style:** `small` — basier-square 400 · 14px/20px

**Observed:** Square artwork occupies the left third with a dividing rule. The right side has 16px padding, a creator/product heading, two-line gray description and a bottom metadata row: red activity count at left, subdued verification at right.

**Transfer:** Use relevant outcomes, templates or integrations rather than abstract feature cards.

### Category pill

**Use:** Filter a media or example shelf.

**CSS:** `display: flex; gap: 8px; border: 1px solid #202020; border-radius: 9999px; padding: 4px 8px; height: 30px`

**Text style:** `small` — basier-square 400 · 14px/20px

**Observed:** The selected category reverses to charcoal with off-white text; the shelf itself is white with only its upper corners rounded.

### Code panel

**Use:** Opening working demonstration and capability examples.

**CSS:** `background: #fcfcfc; border-radius: 0px; max-width: 672px; min-height: 288px; box-shadow: 0px 25px 50px -12px rgba(0, 0, 0, 0.25)`

**Text style:** `code` — jetbrains-mono 400 · 14px/20px

**Observed:** Opening variant has language tabs, a thin active underline and padded code joined directly to result media. In technical chapters, use a simple 1px charcoal outline instead of the floating shadow.

**Transfer:** Show a genuinely small input producing an intelligible result; internal syntax color is subordinate.

### Footer rail

**Use:** Operational status and final navigation.

**CSS:** `border-top: 1px solid #e0e0e0; padding: 16px 0px; background: #ffffff`

**Text style:** `small` — basier-square 400 · 14px/20px

**Observed:** Status sits left with a 12px green dot and pale green ring; utility links and three small theme controls sit right. The expanded marketing footer adds a brand column and three link groups above, with 64px padding and 12px link spacing.

### Enterprise benefit card

**Only for:** enterprise sales pages

**Use:** Concise service and assurance benefits.

**CSS:** `border: 2px solid #3358d4; border-radius: 0px; padding: 32px; text-align: center`

**Text style:** `label-strong` — basier-square 600 · 18px/28px

**Observed:** A blue line icon in a 64px pale blue circle precedes the title; gray 16px body text follows after 8px. Cards are equal-height rectangles.

### Contact control

**Only for:** enterprise sales pages

**Use:** Single-column sales inquiry form.

**CSS:** `background: #fcfcfc; box-shadow: 0px 0px 0px 1px #202020; border-radius: 0px; width: 672px; min-height: 40px`

**Text style:** `body` — basier-square 400 · 16px/1.5

**Observed:** Small labels sit above each field, with red required markers. The message area is 112px high; fields stack with 24px group spacing and terminate in a full-width Primary button.

### Rate row

**Only for:** pricing pages

**Use:** Dense, scan-friendly usage billing comparison.

**CSS:** `border-bottom: 1px solid #e0e0e0; padding: 8px; height: 57px`

**Text style:** `code` — jetbrains-mono 400 · 14px/20px

**Observed:** A bold sans hardware name and subdued mono identifier lead; primary per-second rate and gray per-hour rate share one cell. Quantities align in narrow columns, with full-width annotation cells for specialized capacity.

## Imagery and graphics

### Electric fluid halftone

**Use:** Signature opening artwork, with a restrained return at the footer.

**Observed:** Broad magenta, red and acidic yellow pools swell and fold like liquid light. A fine, regular dot screen gives the opening a printed-computational texture; white fog clears the navigation zone. Art fills nearly the whole first screen behind text, rather than being confined to a hero card.

**Transfer:** Create original abstract fluid art with the same hot/cold color tension. Minimum acceptable treatment is a layered organic gradient field plus a convincing dot-density mask, not a smooth two-stop gradient.

**Build:** Make an oversized SVG or canvas field with overlapping pink and red ellipses and one yellow lobe occupying the lower-right third; blur the color layer by about 64px and warp it with low-frequency displacement. Overlay a regular 4px-spaced dot lattice whose dot radius follows broad sine-wave contours, using charcoal at low alpha. Add a white-to-transparent vertical fade over the top 270px. Preserve large contiguous bright pools and fine dots rather than random noise.

### Input-output demonstration

**Use:** Opening proof and technical explanation panels.

**Observed:** A light code editor occupies three fifths of a joined wide rectangle, with generated photographic or illustrative output at right. Result media is edge-to-edge, with a short white caption and small technical attribution near the bottom; no device bezel surrounds it.

**Transfer:** Pair a real input or configuration with the resulting artifact, report, visualization or interface. Use richly colored outcome imagery against the deliberately plain editor.

### Outcome thumbnail stream

**Use:** Catalog card strips and pricing examples.

**Observed:** Eclectic photoreal, illustrated and typographic artwork is cut to square thumbnails in horizontal cards or 16:9 images above utility cards. The surrounding card system stays neutral so the artwork supplies variety.

**Transfer:** Choose a coherent collection of real outputs rather than tinting every thumbnail to the brand palette.

### Word-and-media sculpture

**Use:** Signature monumental invitation.

**Observed:** Huge black words alternate with thin black-bordered videos or interface stills. Three spacious rows use different alignments; media is about 208px high and words are baseline-heavy at 128px. The collage is neither a tiled gallery nor a conventional centered CTA.

**Transfer:** Write a short aspirational sentence and split it into strong word groups; weave original demonstrations into the gaps. Minimum acceptable version uses sharp interface stills with varied widths.

**Build:** Use three flex rows with space-between, bottom alignment, 32px gaps and 48px row separation. Set words in the word-sculpture recipe and media in 208px-high, roughly 384–457px-wide rectangles with 1px dark borders. Add three fine red vertical rules that fade down toward a small colored identity tile above the words.

### Electric footer stripes

**Use:** Signature visual punctuation above the expanded footer.

**Observed:** Three thin horizontal slices of the same fluid color field span the viewport, separated by white lanes, within a 96px band.

**Transfer:** Reuse the opening art through a stripe mask, preserving a shared visual thread.

**Build:** Place the fluid art across a 96px-high full-width container. Mask it with three 16px-high horizontal bars separated by 16px white gaps. Keep the artwork continuous behind the mask.

### Red technical diagrams

**Use:** Operational proof on charcoal.

**Observed:** Thin red line charts, vertical bar clusters, outlined recursive squares and rate tables occupy the upper half of open cards. Red titles and white explanations sit below; graphics feel like instrumentation rather than decorative illustration.

**Transfer:** Use authentic product behavior: a throughput trace, resource allocation drawing or compact data comparison.

**Build:** Draw SVG polylines and narrow bars in signal red, with red fill at low alpha under line charts. For an abstract alternative, subdivide a rectangular SVG into unequal nested boxes using 1px red strokes and a few subtle red gradient fills.

### Blue halftone panels

**Only for:** enterprise sales pages

**Use:** Enterprise opening band and capability illustrations.

**Observed:** Blue and white dot fields form large waves and soft voids. Feature panels are roughly 640px × 404px with blue outlines and central white circular medallions containing simple blue icons. This cooler visual system replaces the electric multicolor artwork.

**Transfer:** Map each benefit to a straightforward icon while keeping the shared single-color wave language.

**Build:** Use a regular SVG dot grid; vary dot radius by a low-frequency wave height field to transition from solid blue to white. Frame the panel with 2px blue, then place a 136px white circle with 4px blue border and a 64px icon at its center.

### Editorial liquid banner

**Only for:** company editorial pages

**Use:** Art-led introduction above mission prose.

**Observed:** A full-width 400px-high close view of glossy, blurred pink and yellow fluid art has no headline over it. A tiny right-aligned caption credits its creation underneath.

**Transfer:** Give company storytelling a distinct art moment, then return to plain two-column prose; keep attribution visibly modest.

**Build:** Reuse the fluid field without the dot lattice, magnifying the color folds so broad yellow and magenta masses occupy the whole band. Add soft red edges and a narrow bright yellow ridge; match the fluid glow rather than relying on exact gradient stops.

### Icons

**Observed:** Most small controls use filled 14–18px symbols in current text color. Enterprise illustrations use larger blue outline symbols inside circles. Icons are sparse and functional: arrows, lightning, search, chat and theme controls.

**Transfer:** Choose simple SVG silhouettes for compact controls and consistent line icons for the scoped enterprise medallions; do not turn all feature titles into colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Electric working opening

**Observed:** A full-bleed fluid halftone field runs about 894px tall. Back-to-front layers are gradient underpainting, fluid color, dot screen, white top fade, compact Navigation, left-aligned two-line white promise and support, Primary button, then joined Code panel and result media. The content starts beneath a broad top breathing zone; the heading takes roughly the left third while the art remains open to the right. The 72px/1 headline is bold and tightly tracked, with a subtle dark offset shadow; support is 24px/32px and the action follows after 16px. A 24px gap separates the action cluster from a 288px-high working demonstration spanning about 1120px. Within 900px, the header, complete promise, support, CTA and full demonstration are visible; only the top of the next white category shelf appears at the bottom, with catalog cards below the fold.

**Transfer:** Use an equally short outcome promise and a direct input/output example. If no code applies, substitute a compact real workflow panel with a result beside it. Utility pages instead open on white with a 36px title, 16px explanation and 64px padding below the header; enterprise sales pages use centered blue 72px bold text over a blue dot-field band, with the second line reversed in a solid highlight. Company editorial pages open with an unlettered fluid banner and caption.

**Avoid:** Do not center the default promise, place the demo in a laptop mockup, or reduce the opening to a pastel gradient behind an isolated floating card.

**Text style:** `display` — rb-freigeist-neue 700 · 72px/1 · tracking -0.025em

### Centered claim and streaming proof

**Observed:** A light 48px heading is centered within 768px, followed by 20px support inside 672px with 16px separation. Paired compact buttons follow after 32px. Two edge-clipped Catalog card rows sit beneath with 32px between them. Small gradient-ring contributor avatars and fine dashed red rules add an ecosystem cue above.

**Transfer:** Move from a short credible claim into many tangible examples. Use portraits or original simple identity marks inside 64px circles with a 2px pink-red-yellow gradient ring.

**Text style:** `heading` — rb-freigeist-neue 400 · 48px/1

### Nested technical chapter

**Observed:** Technical paper sits in the Electric surround. A 48px introduction leads into rows pairing a red 30px capability title, 20px explanation and Warm outline action with working code examples. Successive left/top rules step inward by 32px, with 24px inner padding and 48px prose-to-demo gaps.

**Transfer:** Use this structure to explain increasing levels of control or complexity; keep examples legible and the structural red lines continuous.

**Text style:** `capability` — rb-freigeist-neue 600 · 30px/1.2

### Dark operational proof

**Observed:** Charcoal proof contains a centered light 48px title, a short white support block and warm outlined action. A monochrome customer-logo group leads into the Dark proof grid. Each open card uses a top and left red rule, Red technical diagrams above, 30px red title and 18px white description below.

**Transfer:** Use real operating evidence and a few customer marks to make advanced claims feel practical rather than ceremonial.

**Text style:** `heading` — rb-freigeist-neue 400 · 48px/1

### Monumental invitation and expanded ending

**Observed:** After 160px of white lead-in, the Word-and-media sculpture makes a short invitation architectural. A 448px-wide 20px paragraph and compact black action follow at left. Electric footer stripes separate this from a spacious white footer with identity left and three navigation groups right; the Footer rail closes the page.

**Transfer:** Make the invitation about what the reader could create, and show artifacts inside its syntax. Preserve the sculpture and stripe devices while allowing their placement to suit a shorter page.

**Text style:** `word-sculpture` — rb-freigeist-neue 700 · 128px/1

### Utility pricing explanation

**Only for:** pricing pages

**Observed:** A plain title and explanation lead to 24px anchor headings marked by muted hash signs. Prose uses a wide 896px measure; media-led price cards form a three-column grid before a compact Rate row table. Informational and volume-support sections conclude in a gray conversion band with one black and one outlined action, followed immediately by the compact Footer rail.

**Transfer:** Explain billing mechanics before asking for a purchase; use numerical examples and caveats rather than a generic three-plan comparison.

**Text style:** `utility-heading` — rb-freigeist-neue 400 · 24px/32px

### Blue enterprise capability and contact

**Only for:** enterprise sales pages

**Observed:** A gray trust band follows the centered blue opening. Large two-column rows pair Blue halftone panels at left with 48px bold headings, 20px relaxed support and 18px bullet lines at right, with 96px between chapters. A centered heading introduces the Enterprise benefit card grid. The ending switches to Contact ground with centered heading, concise support, a 672px stacked form and full-width black submission, then Footer rail.

**Transfer:** Use the cooler single-color system for high-assurance selling, and turn the final CTA into a concrete inquiry form.

**Text style:** `enterprise-heading` — basier-square 700 · 48px/1

### Editorial mission and recruitment ending

**Only for:** company editorial pages

**Observed:** Below the liquid banner and right-aligned 13px caption, a 96px pause precedes two columns: a 36px regular heading at left and 16px paragraphs with an underlined reading link at right. A full-width hairline separates a simple recruitment heading and careers link; the compact Footer rail is the only final navigation.

**Transfer:** Keep institutional prose candid and short. End with a relevant next step rather than forcing a sales CTA onto an editorial page.

**Text style:** `editorial-heading` — rb-freigeist-neue 400 · 36px/40px

## Page flow

**Storyline:** Short promise → tangible working proof → breadth of outcomes → deeper control → operational confidence → invitation to act.

### Product marketing landing page

1. **Promise and demonstration** — Electric art behind a compact left promise and a joined input/output panel.
2. **Breadth proof** — Category shelf, contributor cues and streaming outcome cards.
3. **Capability chapters** — Nested technical paper explains increasingly powerful workflows.
4. **Operational confidence** — Charcoal chapter combines customer marks, diagrams and economical explanations.
5. **Closing invitation** — Monumental words interleaved with media, short support and black action.
6. **Navigation closure** — Electric stripes, expanded link groups and operational status rail.

**Transfer:** Adapt the number of capability chapters to the product; keep the relationship between expressive art and real working detail.

### Usage pricing and billing explanation

1. **Billing premise** — Plain title and short pay-for-use explanation.
2. **Concrete examples** — Descriptive sections and media-led rate examples.
3. **Detailed comparison** — Compact mono rate table and caveats.
4. **Objection handling** — Further billing guidance and high-volume support.
5. **Closing call** — Gray action band with filled and outlined buttons, then compact status footer.

**Transfer:** Use a documentation-like flow when pricing needs explanation rather than artificial plan tiers.

### High-assurance sales page

1. **Scale promise** — Centered blue highlighted headline and one contact action.
2. **Social proof** — Gray customer-logo band.
3. **Capability proof** — Blue halftone diagrams beside bold explanations and bullets.
4. **Service breadth** — Centered outlined benefit grid.
5. **Lead conversion** — Pale contact section with stacked form, then compact footer.

**Transfer:** Trade electric exuberance for single-color assurance without changing square controls or straightforward copy.

### Company mission and recruitment page

1. **Artistic identity** — Unlettered fluid banner and discreet attribution.
2. **Point of view** — Two-column mission statement and explanatory prose.
3. **Participation** — Separated recruitment heading and careers link.
4. **Navigation closure** — Compact operational footer.

**Transfer:** Let a short institutional narrative stay short; use art as the opening gesture instead of adding feature grids.

## Writing

Plain-spoken, technically literate and optimistic. Confidence comes from explaining what happens and how little ceremony is required, not from grand category claims.

**Do not copy:** Do not reuse Replicate or Cloudflare identity assets, model and customer names, artwork, proprietary code, usage counts, performance claims, prices or promises. Source examples illustrate tone and structure only.

- **Addressing the reader:** Use you for the builder, we for the team and the product name only where it clarifies an action. Contractions make the explanation conversational.
- **Rhythm:** Short verb-led headings, compact explanatory paragraphs and direct action labels. Pair a simple claim with a concrete mechanism or consequence; allow a playful aspirational sentence at the close.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct verb connects the capability to an accessible mechanism. | 4–8 words | “Run AI with an API.” |
| Supporting line | Brief parallel clauses name what the reader can do, followed by a simplicity claim. | 12–22 words | “Run and fine-tune models. Deploy custom models. All with one line of code.” |
| Capability heading | Name the practical result, not an abstract virtue. | 2–7 words | “Pay for what you use”<br>“Forget about infrastructure” |
| Primary action | Plain imperative with a low-friction qualifier when true. | 2–5 words | “Get started for free”<br>“Talk to us” |
| Technical explanation | Use if/then consequences to explain behavior in ordinary words. | 2–3 short sentences | “If you get a ton of traffic, [Brand] scales up automatically to handle the demand. If you don't get any traffic, we scale down to zero and don't charge you a thing.” |
| Editorial point of view | Admit the problem clearly before describing the desired change. | One compact paragraph | “We don't believe AI is inherently hard. We just don't have the right tools and abstractions yet.” |

**Words and phrasing to use:** run; build; deploy; your own; one line; get started; what you use; we take care of; works; scale

**Avoid:** revolutionary; unparalleled; unlock limitless potential; next-generation ecosystem; synergize; seamlessly transform

**Rules:**

- Use technical nouns accurately, then explain their effect on the reader.
- Place precise limitations alongside billing or capacity explanations.
- Keep actions concrete: explore, publish, learn, contact.
- Reserve playful language for invitations; keep operational copy literal.

## Do's and Don'ts

### Do

- Keep the opening headline at 72px/1 bold with -0.025em tracking on desktop.
- Use 48px regular section headings to contrast with the bold display moments.
- Keep ordinary action rectangles at 0px radius and 42px height; reserve 54px for major actions.
- Use 64px desktop side padding and 672px support-copy measures.
- Let real output media bring color into otherwise neutral cards.
- Use 1px red top/left rules as structural connectors through the technical and dark chapters.
- Keep numerical comparisons at 14px/20px in JetBrains Mono.
- Return the fluid artwork as three narrow stripes around the expanded ending.

### Don't

- Do not make every 48px heading bold; that weight belongs to the scoped enterprise system.
- Do not round code panels, outcome cards or sales inputs into 12px-radius SaaS cards.
- Do not replace black conversion controls with pink or gradient-filled buttons.
- Do not spread enterprise blue throughout an ordinary multicolor marketing page.
- Do not use the code panel's 25px shadow on all cards; most panels are flat and ruled.
- Do not substitute uniform marketing illustrations for the mixed, concrete outcome thumbnails.
- Do not turn the red charts into a rainbow dashboard; their sparseness is part of the proof treatment.
- Do not inflate small navigation and captions to body scale; 14px controls and 13px art credits preserve the workbench hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Fluid media and demonstration videos occupy the opening and word sculpture.
- Horizontal card strips use translated groups, including a reverse-direction row.
- No action transition timing or easing is established.

**Transfer:**

- Let fluid media and streaming outcomes carry the movement; keep the reading hierarchy and squared control geometry stable.
- Provide still media equivalents that preserve the dot field, collage and concrete outcomes.

**Unknown:**

- Animation durations, easing, play triggers and reduced-motion behavior.

### Responsive

**Observed:**

- Desktop composition uses two-column demonstrations and three-column utility or benefit grids.
- Layout classes indicate stacked technical rows on narrow screens and a separate non-desktop treatment for the monumental collage.

**Transfer:**

- Stack prose before demonstrations on narrow screens, keeping code horizontally scrollable.
- Reduce the sculpture to readable word-and-media rows without losing the interleaving device.
- Keep the catalog horizontally clipped instead of shrinking every card into a tiny grid.

**Unknown:**

- Exact breakpoints, mobile type sizes and mobile navigation behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
