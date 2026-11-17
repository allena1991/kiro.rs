# Trigger.dev — neon workbench cinema

## Overview

A dark developer workbench with a cinematic entrance and an unusually matter-of-fact interior. Acid green actions, violet and pink signals, cool gray grotesks and crisp monospace sit within a continuous ruled scaffold. Product interfaces, schematic workflows and softly defocused technical scenes supply the imagery; spacious demonstrations alternate with dense, useful catalogs. It suits infrastructure, developer tools and technical products that can show how they work.

### Essentials

- Technical cinema above practical copy: a full-width 1440px by 600px dark perspective scene backs a centered 60px/1, weight-600 headline, with a 672px-wide support line and paired actions beneath.
- A continuous engineering scaffold, not floating islands: center sections within 1224px, carry 1px #1c1e21 side rails through headings, media and grids, and mark chapter breaks with 64px patterned strips.
- Color behaves like a signal on equipment: #121317 dominates the canvas, gray carries almost all prose, #a8ff53 fills primary actions, and violet, pink, blue and yellow occupy small icons, labels and diagram strokes rather than broad marketing bands.
- Actions are compact machined rectangles: 40px height, 4px corners, 16px horizontal padding and 18px medium Geist; pair the lime action with a dark outlined utility action at a 12px gap. Navigation uses a 32px compact version.
- Show mechanisms rather than decorative stock imagery: include a legible dark product demonstration and a thin-line schematic with colored paths. Without product media, construct a believable sample workflow in SVG and frame it on the same dark surface.
- Let one emotional signal interrupt the technical rhythm: a bright symbolic glyph with oversized faint echoes, a centered 36px/40px statement mixing bright and muted phrases, and a ruled proof strip using 48px numerals with 0.05em tracking. Adapt the symbol and proof to the new product.
- The ending stays useful: a generously padded conversion band continues the column rails into a directory footer, whose wide identity cell sits beside four narrow link columns and a bottom service-status strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action lime | `#a8ff53` | `--color-lime` | action, accent, border | Primary action fills, navigation hover and selected plan outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal violet | `#7655fd` | `--color-violet` | accent, text | Capability labels, small icons and diagram highlights. |
| Streaming violet | `#826dff` | `--color-violet-light` | accent, text | A lighter violet for streaming labels and their illustrations. |
| Signal pink | `#fa3abf` | `--color-pink` | accent, text | Feature labels and route diagrams. |
| Signal blue | `#3080e0` | `--color-blue` | accent, text | Usage-related labels and diagram details. |
| Signal yellow | `#eccf06` | `--color-yellow` | accent, text | Workflow categories and diagram paths. |
| Live lime | `#afff62` | `--color-live` | surface, accent | A 6px live timeline dot with a translucent 3px ring. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Hero silver | `#e8e9ec` | `--color-hero-ink` | text | Brightest display headline. |
| Bright gray | `#d7d9dd` | `--color-bright` | text | Headings and emphasized phrases. |
| Secondary silver | `#b5b8c0` | `--color-secondary` | text, link | Hero support and utility actions. |
| Muted gray | `#878c99` | `--color-muted` | text | Most descriptive copy, links and captions. |
| Faint technical gray | `#5f6570` | `--color-faint` | text | Code comments and date metadata; not primary explanatory text. |
| Utility outline | `#3b3e45` | `--color-outline` | border | Secondary action borders and quiet timeline dots. |
| Brighter edge | `#272a2e` | `--color-edge` | border, action | Outlined social links, job rows, hover borders and neutral pricing buttons. |
| Glass edge | `#222428` | `--color-glass-edge` | border | Visible announcement outline: secondary silver at 10% alpha over the canvas. |
| Scaffold edge | `#1c1e21` | `--color-rule` | border, surface | Continuous grid rails and selected code-example tabs. |
| Raised charcoal | `#1a1b1f` | `--color-raised` | surface | Hover fills and compact integration tiles; 50% alpha over canvas produces the subtler list-row surface. |
| Subtle list wash | `#16171b` | `--color-list-wash` | surface | Visible result of raised charcoal at 50% alpha over the canvas. |
| Panel charcoal | `#15171a` | `--color-panel` | surface | Illustration cards and testimonial ribbon. |
| Workbench charcoal | `#121317` | `--color-canvas` | background, text | Main canvas, code backing and text on lime actions. |
| Dark glass | `#0e0f12` | `--color-glass` | surface | Visible announcement backing: black at 20% alpha over the canvas, with blur. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| expanded product capability grids | Light signal blue | `#479dec` | `--color-sky` | accent, text | Foundation and workflow labels. |
| expanded product capability grids | Signal green | `#28bf5c` | `--color-green` | accent, text | Monitoring and workflow categories. |

## Typography

- **Satoshi-Variable** — Display, headings, large statements and testimonial prose. Rounded geometric sans with open counters and a friendly, substantial medium-to-semibold voice. If unavailable, use **Manrope**. Use weights 500–600 and retain normal tracking; tune line breaks to the broad title shapes. Font stack: "Satoshi-Variable", "Manrope", sans-serif.
- **Geist** — Body text, navigation, controls and pricing numerals. Compact contemporary grotesk with crisp functional detail. Font stack: "Geist", ui-sans-serif, system-ui, -apple-system, sans-serif.
- **Geist Mono** — Public code examples, diagram captions and update dates. Even-width technical text with restrained syntax color. Font stack: "Geist Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Satoshi-Variable | 600 | 60px | 1 | normal | Centered main marketing promise, balanced over two lines. |
| stat | Satoshi-Variable | 600 | 48px | 1 | 0.05em | Large centered quantitative proof. |
| stat-text | Satoshi-Variable | 600 | 48px | 1 | 0.025em | Textual proof in the same strip as numerical statistics. |
| manifesto | Satoshi-Variable | 600 | 36px | 40px | normal | Centered emotional proof statement with bright opening phrase and muted continuation. |
| heading | Satoshi-Variable | 600 | 30px | 1.2 | normal | Section leads and closing conversion headlines. |
| statement | Satoshi-Variable | 500 | 30px | 1.2 | normal | Large benefit sentences beside product illustrations. |
| demo-summary | Satoshi-Variable | 600 | 30px | 1.375 | normal | Large gray explanation alongside a code demonstration. |
| card-heading | Satoshi-Variable | 600 | 24px | 32px | normal | Illustrated cards and explanatory feature headings. |
| minor-heading | Satoshi-Variable | 600 | 20px | 1.5 | normal | Catalog card headings and capability labels. |
| closing-lead | Geist | 400 | 20px | 1.4 | normal | Support within the wide conversion band. |
| lead | Geist | 400 | 18px | 28px | normal | Hero support and compact closing support. |
| action | Geist | 500 | 18px | 28px | normal | Primary and secondary 40px conversion controls. |
| feature-label | Satoshi-Variable | 600 | 18px | 28px | normal | Colored feature labels and code-example tab headings. |
| quote | Satoshi-Variable | 500 | 18px | 28px | normal | Longer customer quotations. |
| update-heading | Satoshi-Variable | 600 | 18px | 1.5 | normal | Update cards and compact capability cards. |
| body | Geist | 400 | 16px | 1.5 | normal | Paragraphs and descriptive card text. |
| announcement | Geist | 500 | 16px | 1.5 | normal | Short release label inside the glass announcement. |
| footer-heading | Satoshi-Variable | 500 | 16px | 1.5 | normal | Directory column titles. |
| small | Geist | 400 | 14px | 20px | normal | Navigation, quiet links, author attribution and sentence-case eyebrows. |
| compact-action | Geist | 500 | 14px | 20px | normal | Navigation action and small text actions. |
| code | Geist Mono | 400 | 14px | 20px | normal | Public code listings and terse diagram captions. |
| date | Geist Mono | 400 | 12px | 16px | normal | Timeline dates below updates. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product detail and pricing pages | detail-display | Satoshi-Variable | 600 | 48px | 1 | normal | Left-aligned product-detail promise or centered pricing title. |
| pricing pages | price | Geist | 500 | 36px | 40px | normal | Plan amount or custom-price label. |
| careers pages | job-heading | Satoshi-Variable | 600 | 30px | 28px | normal | Single-line role title in an outlined opening row. |
| expanded product capability grids | pillar-body | Satoshi-Variable | 500 | 20px | 1.625 | normal | Roomier foundation descriptions. |
| expanded product capability grids | pillar-label | Satoshi-Variable | 600 | 16px | 1.5 | normal | Compact colored headings above roomy descriptions. |

**Notes:**

- Normal tracking is the default even at display sizes; the widely tracked 48px proof values are a deliberate exception.
- Satoshi carries the expressive voice while Geist keeps explanations and controls utilitarian; monospace is reserved for technical artifacts and dates.
- Sentence-case eyebrows are usually muted 14px text, not a pervasive uppercase microtype system. Bright and muted spans can share a single statement without changing size or weight.

## Layout

**Density:** Airy around demonstrations, compact inside catalogs: large dark intervals give diagrams room while ruled grids keep detailed information efficient.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Small footer icon-to-label gaps. |
| 8px | Label-to-heading and tight title-to-support spacing. |
| 12px | Control pairs, card content gaps and scaffold insets. |
| 16px | Compact grid-cell padding and headline-to-intro separation. |
| 24px | Plan cards, job rows and grouped conversion content. |
| 28px | Testimonial figure padding. |
| 32px | Hero stack gaps and padded bands. |
| 40px | Chapter heading offset below patterned strips and proof-cell vertical padding. |
| 48px | Illustration chapter text padding. |
| 64px | Patterned chapter separator height and roomy capability-cell padding. |
| 80px | Vertical padding for standalone product demonstration chapters. |
| 96px | Space below main hero controls and above pricing detail headings. |
| 128px | Culture-opening vertical padding. |
| 192px | Wide closing conversion band vertical padding. |

### Containers and grids

- **outer-stage**: max width 1440px · side padding 0px. Center the full-bleed hero, navigation and horizontal media bands.
- **scaffold**: max width 1224px · 12 columns · gap 0px · side padding 12px. Default ruled content frame. Three equal modules span four columns each; feature chapters can split five and seven columns.
- **reading**: max width 576px · side padding 12px. Section heading and support group.
- **hero-support**: max width 672px · side padding 0px. Centered supporting paragraph and emotional proof statement.
- **hero-title**: max width 1024px · side padding 0px. Balanced two-line display title.
- **catalog**: max width 1224px · 3 columns · gap 0px · side padding 0px. Shared-border capability, quote and FAQ grids.
- **timeline**: 4 columns · gap 24px · side padding 12px. Short update cards above a thin continuous timeline.
- **plans** (only for pricing pages): max width 1440px · 4 columns · gap 0px · side padding 0px. Full-width plan comparison; each column has 24px inner padding.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-small-cards | 4px |
| media-panels | 6px |
| announcement-and-caption | 9999px (pill) |
| avatar-and-status | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| live-dot-ring | `0px 0px 0px 3px rgba(175,255,98,0.3)` | A narrow status halo on the latest timeline point, not a general card shadow. |

### Surfaces

#### Canvas · level 0

**Use:** The continuous page backing.

**CSS:** `background: #121317; color: #d7d9dd`

#### Ruled scaffold · level 0

**Use:** Section frames and uninterrupted structural rails.

**CSS:** `border-top: 1px solid #1c1e21; border-right: 1px solid #1c1e21; border-left: 1px solid #1c1e21`

**Observed:** Adjacent sections share edges; internal modules align to the same rails.

**Transfer:** Use borders as layout infrastructure rather than drawing separate rounded containers around every chapter.

#### Illustration card · level 1

**Use:** Workflow examples within a horizontal rail.

**CSS:** `background: #15171a; border: 1px solid #1c1e21; border-radius: 4px; box-shadow: none`

**Observed:** Media rests above a darker, densely captioned lower portion.

**Transfer:** Keep elevation minimal; let colored diagram strokes distinguish the content.

#### List wash · level 1

**Use:** Quiet rows within capability lists.

**CSS:** `background: rgba(26,27,31,0.5); border-radius: 4px`

#### Announcement glass · level 2

**Use:** Small release pill over the cinematic scene.

**CSS:** `background: rgba(0,0,0,0.2); border: 1px solid rgba(181,184,192,0.1); border-radius: 9999px; backdrop-filter: blur(12px)`

#### Diagram backing · level 0

**Use:** Large product schematics and chapter pauses.

**CSS:** `background: #121317`

**Observed:** Tiny cross marks fade away under a canvas-colored horizontal mask so the text area stays clear.

**Transfer:** Rebuild with the Patterned separators graphic rather than a high-contrast texture.

#### Hatched close · level 0

**Use:** Centered conversion panels.

**CSS:** `background-color: #121317; background-image: repeating-linear-gradient(45deg, rgba(135,140,153,0.06) 0px, rgba(135,140,153,0.06) 1px, rgba(18,19,23,0) 1px, rgba(18,19,23,0) 4px); border-top: 1px solid #1c1e21`

**Observed:** Fine diagonal lines add material to an otherwise very restrained conversion panel.

**Transfer:** Keep pattern contrast low enough that the control pair remains the brightest object.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; height: 60px; background: #121317; border-bottom: 1px solid #1c1e21; z-index: 49`

**Text style:** `small` — Geist 400 · 14px/20px

**Observed:** Identity at the left, a compact text menu immediately alongside it, community and account utilities at the right, then a lime compact action. The content spans the outer stage with 12px side insets.

**States:** Declared: hover navigation text becomes #a8ff53; focus-visible navigation text becomes #a8ff53.

### Primary button

**Use:** Main signup or conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; background: #a8ff53; color: #121317; border-radius: 4px`

**Text style:** `action` — Geist 500 · 18px/28px

**Observed:** Label precedes a small right chevron. Navigation variant uses 32px height, 10px side padding and compact-action typography.

**Transfer:** Use one clear imperative, with a related outlined utility action beside it.

### Secondary button

**Use:** Utility, documentation or assisted setup next to conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 40px; padding: 0px 16px; background: #121317; border: 1px solid #3b3e45; border-radius: 4px; color: #b5b8c0`

**Text style:** `action` — Geist 500 · 18px/28px

**Observed:** Copy variant includes a violet sparkle on the left and a duplicate-square icon on the right. Sales and documentation variants use a trailing chevron or external arrow instead.

### Announcement pill

**Use:** One short release message above the hero headline.

**CSS:** `display: flex; align-items: center; gap: 16px; height: 38px; padding: 6px 12px 6px 8px; background: rgba(0,0,0,0.2); border: 1px solid rgba(181,184,192,0.1); border-radius: 9999px; backdrop-filter: blur(12px)`

**Text style:** `announcement` — Geist 500 · 16px/1.5

**Observed:** A small violet newness badge precedes the release title; a circular arrow affordance closes the pill.

### Workflow card

**Use:** Illustrated examples in a horizontally scrolling rail.

**CSS:** `display: flex; flex-direction: column; background: #15171a; border: 1px solid #1c1e21; border-radius: 4px; margin-right: 12px`

**Text style:** `card-heading` — Satoshi-Variable 600 · 24px/32px

**Observed:** Desktop cards are 384px wide and 338px tall. The upper 184px holds a fine-line flow diagram; the lower portion has 12px padding, heading, short explanation and a small example link. A partial next card signals horizontal continuation.

**States:** Declared: hover border-color #272a2e and background-color #1a1b1f; active background-color #121317.

### Capability cell

**Use:** Dense feature or integration catalog.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 16px; border-right: 1px solid #1c1e21; border-bottom: 1px solid #1c1e21`

**Text style:** `minor-heading` — Satoshi-Variable 600 · 20px/1.5

**Observed:** Small colored icon next to title, muted explanatory sentence below, compact learn-more link at the bottom. Cells share their boundaries rather than floating apart; compact product catalogs use update-heading and small body type.

### Feature list row

**Use:** Long categorized capability lists.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 8px; padding: 8px 12px; background: rgba(26,27,31,0.5); border-radius: 4px`

**Text style:** `body` — Geist 400 · 16px/1.5

**Observed:** Rows sit at 12px vertical gaps inside three equal category columns, with a restrained trailing arrow.

**States:** Declared: hover background-color #1a1b1f.

### Code example tab

**Use:** Select a public implementation example beside its code.

**CSS:** `display: flex; flex-direction: column; padding: 16px; text-align: left; background: #1c1e21; border: 1px solid #1c1e21; border-radius: 4px`

**Text style:** `feature-label` — Satoshi-Variable 600 · 18px/28px

**Observed:** Selected state is filled; siblings are canvas-colored with the same border. Heading sits above a small gray explanation. The tab list occupies roughly one third of the section and the code occupies the remaining width.

**States:** Declared: hover background-color #1c1e21 and opacity 1; focus-visible outline-style none with zero box-shadow.

### Social icon link

**Use:** Small social links in the footer identity cell.

**CSS:** `display: block; width: 34px; height: 34px; padding: 8px; border: 1px solid #272a2e; border-radius: 4px`

**Observed:** 16px grayscale social mark centered in each outlined square; links form a row near the bottom of the identity area.

### Footer directory

**Use:** Final site navigation and operational reassurance.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); max-width: 1224px; border-top: 1px solid #1c1e21; border-right: 1px solid #1c1e21; background-image: linear-gradient(90deg, #1c1e21 1px, rgba(0,0,0,0) 1px); background-size: 16.6667% 100%`

**Text style:** `footer-heading` — Satoshi-Variable 500 · 16px/1.5

**Observed:** A four-column-span identity cell has the logo at top and Social icon links at bottom. Four two-column-span directories use 12px inner padding, 16px row gaps, small icon-led links and small headings. A separate bottom strip places live service status left and muted copyright right. Total desktop footer height is 472px.

### Recommended plan

**Only for:** pricing pages

**Use:** Highlight one plan without changing the dark theme.

**CSS:** `display: flex; flex-direction: column; padding: 24px; border: 1px solid #a8ff53`

**Text style:** `price` — Geist 500 · 36px/40px

**Observed:** Plan name, large amount and small billing interval precede a horizontal divider and a full-width action, then tightly spaced benefit rows. The favored plan has lime name and action; other plans use neutral #272a2e actions. Four desktop columns are 360px wide.

### Position row

**Only for:** careers pages

**Use:** Clickable job opening.

**CSS:** `display: flex; padding: 24px; border: 1px solid #272a2e`

**Text style:** `job-heading` — Satoshi-Variable 600 · 30px/28px

**Observed:** Title, employment/location metadata and a compact apply link stack at 12px gaps. Rows have square corners, 150px desktop height and 16px gaps.

**States:** Declared: hover adds a diagonal-line pattern and opacity 1.

## Imagery and graphics

### Cinematic technical stage

**Use:** Required opening atmosphere on a general marketing landing page.

**Observed:** A magnified terminal lies diagonally in perspective across the upper half of the screen. Gray monospaced commands, sparse green and violet signals and shallow focus fade into charcoal behind the centered copy. It is a dark backdrop, not a legible documentation panel.

**Transfer:** Use the new product's primary working artifact: a terminal, editor, timeline or instrument panel. The minimum version is an HTML panel with a few plausible lines, perspective, selective blur and a strong bottom fade.

**Build:** Place a 1440px-wide, 600px-high media layer behind the hero. Render a wide dark panel with mono rows, rotate it approximately -25deg and apply perspective with an X-axis tilt. Blur distant duplicate rows by 2–5px, dim the overall panel, and overlay linear and radial canvas-colored fades. Keep the central text zone nearly solid charcoal; use only a few green and violet marks. Match the shallow focus and dark fade rather than exact gradient stops.

### Working product demonstrations

**Use:** Large practical proof after the promise and inside capability chapters.

**Observed:** A bordered 1222px-wide, roughly 16:9 video stage shows an editor or a purple folder-and-type scene. Playback controls live in the heading rail; a glass pill caption sits near the lower center. Smaller editor fragments and status panels fade into their charcoal backing rather than sitting in bright browser chrome.

**Transfer:** Show one coherent action in the real interface, with a short verb-led caption. A static sample interface with an emphasized state is the minimum acceptable alternative.

**Build:** Frame a dark 16:9 panel with a 1px scaffold edge. Add a centered working artifact, low-contrast edge fades and a bottom caption pill with black at 10% alpha, 16px backdrop blur and a faint silver outline. Keep stage controls small and aligned with the section heading.

### Signal schematics

**Use:** Required mechanism illustrations in examples and explanatory chapters.

**Observed:** Fine gray connectors join small outlined nodes on a charcoal field. Green, violet, magenta, blue or yellow highlights encode branches and active states. Larger use-case art tilts rectangular tiles in an isometric plane, with dashed colored connectors, simple line glyphs and generous empty space.

**Transfer:** Diagram a real relationship in the new product: input, processing, review and output. Preserve the thin strokes, dark field and sparse highlighted state even when the exact interaction differs.

**Build:** Use SVG with 1px neutral rails, 1.5px colored paths and compact outlined rounded nodes. For flat workflows, route orthogonal connectors between labeled rectangles. For larger tiles, skew a group into an isometric plane, place 2–4 outlined cards with 4px corners, and join them with dashed colored paths and tiny arrowheads. Use a single accent family per diagram plus lime for completion. Fade the outer edges into the canvas.

### Patterned separators

**Use:** Required chapter rhythm and technical material behind diagrams.

**Observed:** A 64px-tall strip of extremely faint crosses or diagonal hatching sits before many section headings. Cross patterns also appear near the edges of larger illustrations; masks clear the center behind copy.

**Transfer:** Recreate the subtle pattern in SVG or CSS and use it to join chapters, not as a loud wallpaper.

**Build:** Tile a 64px SVG containing small 1px plus marks in muted gray at 8% alpha. Cover the center with a horizontal canvas gradient opaque from 25% to 75%. For hatched bands use 1px gray at 6% alpha repeated every 4px at 45deg, with canvas fades at the edges.

### Emotional signal sculpture

**Use:** An expressive brand-proof pause within a long technical page.

**Observed:** A bright pink heart sits above a centered statement; larger translucent heart silhouettes recede behind it, creating a soft concentric pulse. Below, three ruled cells display large statistics or short textual proof. The icon is a focal signal, not a full-color section background.

**Transfer:** Choose one meaningful simple symbol for a genuine product value and repeat its silhouette at decreasing opacity. Pair it with substantiated proof rather than using the symbol as empty decoration.

**Build:** Center a filled SVG glyph above the statement. Duplicate it behind itself at approximately 2×, 3× and 4× scale, using pink at roughly 3–6% alpha and a soft 4px blur. Clip the echoes to the ruled section. Keep the foreground glyph crisp and the prose bright-to-muted.

### Human proof details

**Use:** Testimonial masonry and short endorsement ribbons.

**Observed:** Small circular headshots and customer marks accompany gray quotations. The photography is tightly cropped to faces, with natural color and no surrounding lifestyle scene; logos are small, often monochrome, aligned opposite the attribution.

**Transfer:** Use authentic portraits and restrained organization marks so the quotes, not photography, remain dominant.

### Product signal field

**Only for:** product overview openings

**Use:** Abstract technical opening alternative to the cinematic stage.

**Observed:** A broad right-hand field of tiny directional glyphs is almost invisible except for sparse colored points, creating the impression of distributed activity beside a left-aligned title.

**Transfer:** Turn the product's smallest meaningful unit into a regular field with only a few active colored instances.

**Build:** Create an SVG grid of tiny arrowhead glyphs at regular intervals over charcoal; keep most at very low gray opacity, brighten a handful in violet, lime, blue and pink, and use a radial mask to fade the perimeter.

### Icons

**Observed:** Most interface icons are 16px outlines with 1.5px rounded strokes. Tiny 9px by 8px arrows close links. Colored 20–24px capability marks contrast with gray navigation and footer symbols; solid brand marks are a separate category.

**Transfer:** Choose one rounded-stroke icon family for controls and directories, keep it small and muted, and reserve saturated glyphs for capability headings and diagram states.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** The 60px Navigation sits above a 782px hero. Back to front: Canvas, a full-width 600px technical video with diagonal perspective and soft focus, dark edge fades, then a centered stack. A small Announcement pill precedes the two-line display title; the title spans roughly two thirds of the viewport within a 1024px maximum. The 672px support line sits below it; Primary button and Secondary button share a centered row with 12px between them. Hero content uses 32px stack gaps, with extra space before the actions and 96px after them. Within the first 900px the scene, announcement, complete headline, support and controls are visible, followed by the top of the demonstration's category tabs. The actual code demonstration continues below the fold.

**Transfer:** Retain the cinematic working-artifact backdrop and centered copy for the default landing page. If no film exists, build the perspective terminal or interface described in Cinematic technical stage. Product-detail pages instead open with a 48px left-aligned title and copy occupying about five columns, with a diagram in seven columns. Pricing opens with a centered 48px title and comparison columns; careers uses a narrow centered-but-left-aligned 30px statement with bright inline emphasis.

**Avoid:** Do not place a bright dashboard on one side of this default opening, replace the atmosphere with a generic gradient orb, or move all useful text below the first viewport.

**Text style:** `display` — Satoshi-Variable 600 · 60px/1

### Chapter heading rail

**Observed:** Patterned separators introduces a chapter with a 64px strip, followed by a 40px offset to a left-aligned heading. The text group uses 12px side insets and a 576px maximum, sometimes a small sentence-case eyebrow and muted support; a compact text action sits at the opposite end. Ruled scaffold carries the side rails through the header.

**Transfer:** Use this to make independently sized content chapters feel like parts of one instrument panel.

**Text style:** `heading` — Satoshi-Variable 600 · 30px/1.2

### Code and consequence

**Observed:** A row of compact category tabs sits over a two-part demonstration. Code uses the code recipe on Canvas; a large muted explanation uses demo-summary in the narrower companion area. Later code chapters use Code example tabs in one third of the frame and the selected listing in the rest.

**Transfer:** Connect implementation to its useful result. For non-code products, show a meaningful configuration or structured input beside the outcome rather than fake source code.

**Text style:** `demo-summary` — Satoshi-Variable 600 · 30px/1.375

### Alternating mechanism chapter

**Observed:** An equal split alternates image-left and image-right across ruled rows of about 321px height. Text sits within a 384px measure with 48px or 64px local padding. A colored minor-heading precedes the larger statement; the mechanism drawing remains dark and low contrast except for active signals. More explanatory product chapters use feature-label, card-heading and body, with a bordered mono caption below the visual.

**Transfer:** Give each chapter one benefit, one visible mechanism and one accent family; let content choose the number of chapters.

**Text style:** `statement` — Satoshi-Variable 500 · 30px/1.2

### Illustrated example rail

**Observed:** Chapter heading rail introduces Workflow cards in a horizontal overflow band with top and bottom rules; 12px gaps and a visible partial card imply continuation. Larger product overview variants use a sticky explanatory left column and two columns of 420px-tall isometric illustration cards on the right.

**Transfer:** Use the rail for peer examples and the sticky-column variant for a deeper case catalog; avoid turning either into an unrelated collection of stock photos.

**Text style:** `card-heading` — Satoshi-Variable 600 · 24px/32px

### Dense capability matrix

**Observed:** Capability cells meet edge-to-edge in three desktop columns. A separate categorized variant uses Feature list rows with 12px gaps inside three columns. The expanded foundation variant has 64px cell padding, colored pillar-label and pillar-body descriptions rather than compact catalog typography.

**Transfer:** Choose the dense matrix for breadth, and the roomier foundation variant for a smaller number of principles. Do not average their padding or type sizes.

**Text style:** `minor-heading` — Satoshi-Variable 600 · 20px/1.5

### Proof signal and strip

**Observed:** Emotional signal sculpture anchors a centered 672px-wide manifesto. The opening phrase is bright while the continuation is muted. A three-cell proof strip follows, each cell about 407px wide and 164px tall, with 40px vertical padding, centered 48px value and 16px caption at a 12px gap.

**Transfer:** Use a product-specific value and real proof. The middle cell can carry short text at stat-text tracking rather than forcing every proof point into a number.

**Text style:** `manifesto` — Satoshi-Variable 600 · 36px/40px

### Quote masonry

**Observed:** Three shared-border columns contain varying-height quotations. Quote type is larger and softer than ordinary body copy; 28px figure padding, portrait attribution, organization mark and optional quiet story link create each unit. A canvas gradient fades the lower rows into a centered compact read-more control.

**Transfer:** Keep quote lengths genuinely varied and use the fade only when more content is actually available.

**Text style:** `quote` — Satoshi-Variable 500 · 18px/28px

### Update timeline

**Observed:** Four columns with 24px gaps use update-heading, a small support paragraph and a 12px mono date. A faint line and 6px dot join the row; the newest dot has a lime 3px halo, older dots use neutral gray.

**Transfer:** Show ongoing product activity or releases in a compact proof row, using actual dates rather than a decorative timeline.

**Text style:** `update-heading` — Satoshi-Variable 600 · 18px/1.5

### Wide conversion close

**Observed:** A ruled 1224px band uses 192px vertical padding. The main half contains a 30px heading, 20px support, and the paired Primary button and Secondary button. Two narrower companion areas offer commercial reassurance and an alternate operating model. Vertical rails continue into Footer directory.

**Transfer:** Retain the useful main action plus two short reassurance paths; adapt their subjects to the new product rather than requiring the same commercial options.

**Text style:** `heading` — Satoshi-Variable 600 · 30px/1.2

### Compact conversion close

**Only for:** focused product detail pages

**Observed:** A 385px centered Hatched close uses a 30px headline, 18px support and the same paired actions. It directly precedes Footer directory without the wide close's side offers.

**Transfer:** Use the compact variant when the page has already answered most questions.

**Text style:** `heading` — Satoshi-Variable 600 · 30px/1.2

### Comparison and objection handling

**Only for:** pricing pages

**Observed:** A centered 48px heading and 20px support precede four full-width plan columns with Recommended plan treatment on one column. Below, a narrower 1224px compute table uses 41px ruled rows, followed by explanatory pricing detail and a three-column, fully expanded FAQ masonry. FAQ cells use 24px padding, 20px headings and 16px body. A wide conversion close precedes the footer.

**Transfer:** Explain the billing model concretely and keep answers visible; this is an information-dense pricing variant rather than a general landing-page card system.

**Text style:** `detail-display` — Satoshi-Variable 600 · 48px/1

### Recruiting opening and listings

**Only for:** careers pages

**Observed:** A 640px left-aligned block sits in the center of the patterned frame with 128px vertical padding. A small lime eyebrow introduces a 30px medium statement with bright inline phrases and a primary action. A proof strip, compact values grid, Position rows, backer grid and Quote masonry lead directly to Footer directory; there is no separate closing conversion panel.

**Transfer:** Keep the restrained text-led opening and actionable row list for editorial recruiting content, with relevant proof and culture details.

**Text style:** `statement` — Satoshi-Variable 500 · 30px/1.2

## Page flow

**Storyline:** Promise → working mechanism → capability breadth → credible proof → reduced adoption risk → useful final action and directory.

### Broad platform landing page

1. **Promise** — Cinematic opening and compact utility announcement.
2. **Product demonstration** — Tabbed implementation, logo proof and a wide narrated interface stage.
3. **Capability chapters** — Illustrated examples, alternating mechanisms, debugging and realtime demonstrations.
4. **Breadth and reliability** — Dense capability matrix, categorized lists and selectable code examples.
5. **Social and quantified proof** — Emotional signal sculpture, statistic strip and quote masonry.
6. **Momentum** — Compact update timeline.
7. **Closing call** — Wide conversion close, companion reassurance paths and directory footer.

**Transfer:** Borrow the contrast between cinematic promise and practical detail; rearrange or shorten the chapters to fit the product.

### Technical product overview

1. **Promise** — Split title and subtle distributed signal field.
2. **Social proof** — Three compact endorsements immediately below the hero.
3. **Product demonstration** — Editor detail paired with a narrow explanation.
4. **Capability principles** — Roomy colored foundation grid and compact integrations.
5. **Use-case breadth** — Sticky intro with isometric example tiles.
6. **Capability catalog** — Shared-border feature matrix.
7. **Closing call** — Compact hatched conversion panel and full directory footer.

**Transfer:** Make a technical overview concrete through one interface example before expanding into mechanisms and applications.

### Focused mechanism explainer

1. **Promise** — Split hero with a working status diagram and signup/docs pair.
2. **Capability explanation** — Ruled text-and-diagram rows with a colored label and mono configuration caption.
3. **Implementation proof** — Selectable example tabs beside code.
4. **Closing call** — Centered hatched adoption panel and directory footer.

**Transfer:** Explain a small number of contrasting operating modes, then show how the reader implements them.

### Pricing and purchase confidence

1. **Pricing** — Centered promise and four adjacent plan columns with one lime outline.
2. **Billing explanation** — Compute rate table and a compact invocation explanation.
3. **Objection handling** — Fully expanded FAQ masonry rather than hidden accordion-only answers.
4. **Closing call** — Wide enterprise reassurance band with signup and sales actions, then directory footer.

**Transfer:** Prioritize exact charging units, included benefits and visible answers over promotional price badges.

### Recruiting and organizational trust

1. **Mission** — Narrow text-led statement with bright emphasis and direct application action.
2. **Credibility** — Three-cell proof strip.
3. **Culture** — Compact icon-led values in a ruled grid.
4. **Actionable inventory** — Outlined full-width job rows.
5. **External validation** — Backer grid and quote masonry with a fading continuation control.
6. **Ending** — Direct transition from testimonials into the shared directory footer.

**Transfer:** Let a recruiting page be more editorial than cinematic; maintain the scaffold, sparse color and direct route to available roles.

## Writing

Confident builder-to-builder language with a practical streak and occasional exuberant words. Big promises are quickly grounded in explicit mechanisms, working examples and operational detail.

**Do not copy:** Do not reuse the brand name, logo, artwork, customer identities, quotations, community counts, license claims, timing promises, compliance certifications or price facts as claims for another product. Examples here illustrate voice only.

- **Addressing the reader:** Address the reader as you and your; use we for the team and the product name for concrete descriptions of behavior.
- **Rhythm:** Short sentence-case headlines, often a verb plus outcome. Supporting paragraphs are usually one or two compact sentences; long technical lists remain direct and scannable. Occasional emphatic language is balanced by precise nouns and plain explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct action and durable outcome, or a concise category promise. | 4–10 words | “Build and deploy durable AI agents and workflows”<br>“Concurrency and fair queues” |
| Capability headline | Start with a useful verb; name the benefit without an abstract slogan. | 4–8 words | “Find and fix bugs fast”<br>“Break less things with totally type-safe agents” |
| Supporting line | Explain what happens and how; use concrete product behavior. | 1–2 sentences | “Each deploy is an atomic version ensuring started tasks are not affected by code changes.” |
| Primary action | An immediate building verb; lower the perceived effort with a short qualifier. | 2–5 words | “Start building now”<br>“Get started for free” |
| Closing promise | Turn adoption into a near-term achievable task. | 5–9 words | “Deploy your first agent this evening” |
| Objection answer | Answer directly, then supply the constraint or implementation detail. | 1–3 sentences | “Tasks can run for as long as you need, with no timeouts.” |

**Words and phrasing to use:** build; deploy; reliable; durable; regular code; type-safe; no timeouts; get started; works with; control; invincible

**Avoid:** revolutionary ecosystem; unleash limitless potential; seamless synergy; world-class solutions; enterprise-grade everything

**Rules:**

- Follow an ambitious adjective with a concrete explanation of the mechanism.
- Use technical terms when they are the clearest nouns, and put implementation detail near the benefit.
- Keep button labels task-oriented; differentiate signup from documentation and assisted setup.
- Write proof as attributable testimony or verifiable quantities, not anonymous superlatives.

## Do's and Don'ts

### Do

- Carry 1px #1c1e21 rails through adjacent 1224px sections.
- Keep the display at 60px/1 and weight 600, with normal tracking.
- Use 12px gaps for paired actions and horizontal card spacing.
- Give 40px actions 4px corners; reserve fully rounded forms for announcement and caption pills.
- Use 14px/20px mono for public implementation examples and 12px/16px for dates.
- Keep capability matrices edge-to-edge, with 16px cell padding by default.
- Preserve the proof-strip exception: 48px values with 0.05em tracking.
- Make technical illustrations dark enough that the bright text remains the reading priority.

### Don't

- Do not brighten the canvas to pure black or replace its cool charcoal with a blue gradient.
- Do not turn ordinary section titles into oversized 60px display headings; the recurring section role is 30px/36px.
- Do not use the 64px foundation-cell padding on every compact catalog card.
- Do not replace the ruled structure with widely spaced rounded bento islands.
- Do not give every action a lime fill; neutral and outlined controls preserve the conversion hierarchy.
- Do not set all UI labels in monospace or uppercase; body and navigation are primarily Geist.
- Do not add broad drop shadows to cards; borders, not elevation, define their edges.
- Do not flatten the footer into a centered logo and a short legal row; retain its directory density and status strip.

## Motion and responsive

### Motion

**Observed:**

- Navigation text transitions use 0.15s cubic-bezier(.4, 0, .2, 1); workflow cards and feature rows use 0.3s with the same curve.
- Code tabs declare all-property transitions at 0.2s cubic-bezier(.4, 0, .2, 1).
- Two marquee animations are declared at 40s linear infinite. The hero and demonstration use video; the demonstration exposes play/pause, replay and fullscreen controls.
- Outlined job rows declare moving diagonal-line treatment on hover.

**Transfer:**

- Keep interaction emphasis in subtle background, edge and text changes rather than large transforms.
- Provide the same small playback affordances for a narrated product stage; keep cinematic media separate from interface controls.

**Unknown:**

- Exact video loops, diagram animation timings and scroll-trigger behavior are not established.

### Responsive

**Observed:**

- Desktop outer stage is 1440px and the ruled scaffold is 1224px.
- Declared width breakpoints include 480px, 640px, 768px, 990px, 1024px, 1224px and 1440px.
- Heading classes specify a 30px base display, 48px intermediate display and 60px desktop display. Hero controls change from a vertical stack to a horizontal row.
- Capability grids declare single-column, two-column and three-column arrangements; plans declare one, two and four columns. Workflow examples use horizontal overflow.

**Transfer:**

- On narrow screens retain the cinematic scene as a faded background above and behind the title, not as a tiny side thumbnail.
- Stack the conversion pair and split chapters while keeping the shared rails aligned.
- Keep example rails horizontally scrollable and preserve readable code through local horizontal overflow rather than shrinking mono text.
- Collapse the footer identity cell above paired directory columns, keeping the status strip separate.

**Unknown:**

- Exact narrow-screen compositions and media masks have not been visually established; the collapse rules are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
