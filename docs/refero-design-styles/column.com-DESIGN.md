# Column — infrastructure in soft focus

## Overview

A light, technical marketing style that makes complex infrastructure feel tangible and approachable. Navy grotesk typography, pale gray canvases and mint-blue halftone graphics sit beside translucent interface objects, with occasional deep teal chapters. The density is low in the storytelling and deliberately higher inside the product demonstrations; it suits developer platforms and sophisticated business products.

### Essentials

- Headlines sound substantial without becoming billboards: use SuisseIntl at 52px/1.1, weight 600 and -0.03em tracking for the default opening, with a two-line, left-aligned lockup.
- The opening is an atmospheric product stage, not a boxed illustration: an 880px-tall scene combines a pale #f6f6f8 canvas, oversized mint-blue dot art fading behind the copy, and a floating translucent interface card on the right.
- Controls feel like small physical keys: 36px-high buttons have 8px corners, 14px medium labels, 16px side padding, a navy primary and milky white secondary with fine edge shadows.
- Color lives in systems and light: keep most of the page pale neutral, reserve saturated color for compact proof accents and objects, and introduce a bounded #011821 chapter with 12px corners rather than turning the whole page dark.
- Dot fields must carry the visual identity: use fading halftone silhouettes for a main product concept and an 11-by-11 dot matrix for closing action icons. When no suitable object exists, construct a dotted abstract network or layered system silhouette rather than omitting the device.
- Proof is small but unusually specific: use green 24px/1.1 medium metrics with 12px captions, and stage customer stories beside layered UI cards instead of relying only on oversized numbers.
- The ending is a destination: a 12px-inset, 12px-rounded pale panel pairs a 60px/1 closing line with three 344px-by-209px glass action cards and a spacious, integrated link directory.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navy ink | `#111a4a` | `--color-navy` | text, action | Default headings, main buttons and directory labels; supporting copy can use this ink at 60% opacity. |
| Deep teal | `#011821` | `--color-deep-teal` | background | Bounded infrastructure chapters. |
| Announcement indigo | `#3e5199` | `--color-banner-start` | background | Left side of the narrow announcement gradient. |
| Announcement periwinkle | `#5568ad` | `--color-banner-end` | background | Right side of the announcement gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Icy cyan | `#c1e8ef` | `--color-ice` | text | Headlines on deep teal. |
| Proof green | `#167e6c` | `--color-proof-green` | text, accent | Metrics, proof labels and small graph endpoints. |
| Dot blue | `#4575cd` | `--color-dot-blue` | accent | Closing matrix icons, with inactive dots at 20% opacity. |
| Focus blue | `#a2c1ed` | `--color-focus-blue` | border | 2px navigation focus ring and editorial quote rules. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Milk white | `#ffffff` | `--color-white` | surface, text, border | White surfaces, reversed text and glass edges. White at 25%, 50%, 60%, 75% or 80% opacity lets the underlying scene remain visible. |
| Cool canvas | `#f6f6f8` | `--color-canvas` | background | Default marketing canvas. |
| Closing gray | `#eeeff2` | `--color-panel` | surface, background | Closing panel and technical response backing. |
| Cool hairline | `#e3e4e8` | `--color-edge` | border | Section rules and the closing panel's 1px outline. |
| Muted gray | `#7c7f88` | `--color-muted-ink` | text | Captions, directory links and subdued supporting text. |
| Secondary gray | `#575a64` | `--color-secondary-ink` | text | Small descriptive copy and subtle control edges. |
| Body charcoal | `#3b3e47` | `--color-body-ink` | text | Longer explanations and catalog titles. |
| Control charcoal | `#232730` | `--color-control-ink` | text | Secondary button labels. |
| Near-black ink | `#12161e` | `--color-heading-ink` | text | Navigation and product-detail headings. |
| Quote black | `#000000` | `--color-black` | text | Compact customer quotations; alpha versions supply fine shadows. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer story modules | Customer ember | `#ec652b` | `--color-orange` | accent, surface | Active customer tab and compact proof objects; not the default conversion color. |
| product-detail pages | Product frost | `#f6f7fa` | `--color-product-canvas` | background | Slightly cooler canvas for product-detail pages. |
| editorial product launches | Warm stone | `#eceae7` | `--color-warm-canvas` | background | Warm launch theme canvas. |
| editorial product launches | Warm milk | `#f5f3f1` | `--color-warm-panel` | surface | Warm launch closing panel. |
| editorial product launches | Warm hairline | `#e7e4e0` | `--color-warm-edge` | border | Warm panel's outline. |
| editorial product launches | Launch midnight | `#080b32` | `--color-launch-navy` | action, text | Darker blue controls and closing headings in the warm theme. |
| company and culture narratives | Editorial blue | `#1b2d70` | `--color-editorial-blue` | text | Emphasized narrative statements. |

## Typography

- **SuisseIntl** — All marketing headings, paragraphs, navigation and controls. Even, compact neo-grotesk with a high x-height; light body cuts contrast with firm display cuts. OpenType features: "salt" 2. If unavailable, use **Inter**. Use weights 300–600 and preserve the tight heading tracking. Font stack: "SuisseIntl", "Inter", ui-sans-serif, system-ui, sans-serif.
- **SuisseIntlMono** — Section markers and technical labels. Small utilitarian monospace, usually uppercase. If unavailable, use **IBM Plex Mono**. Font stack: "SuisseIntlMono", "IBM Plex Mono", ui-monospace, Menlo, Consolas, monospace.
- **Inter** (only for product demonstrations) — Amounts and labels inside interface illustrations. Compact, highly legible interface sans. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **SFMono** (only for product demonstrations) — API request and response examples. Small regular monospace, separated from marketing prose. If unavailable, use **Roboto Mono**. Font stack: "SFMono", "Roboto Mono", ui-monospace, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing | SuisseIntl | 600 | 60px | 1 | -0.01em | Large closing invitation, visually stronger than the main opening headline. |
| display | SuisseIntl | 600 | 52px | 1.1 | -0.03em | Default opening headline, held to about 500px so it occupies two strong lines. |
| heading-lg | SuisseIntl | 600 | 48px | 1.1 | -0.03em | Major catalog or platform section headline. |
| dark-heading | SuisseIntl | 500 | 48px | 1.1 | -0.02em | Icy headline introducing a deep teal chapter. |
| heading | SuisseIntl | 500 | 28px | 1.1 | -0.01em | Proof, customer story and developer section leads. |
| stat | SuisseIntl | 500 | 24px | 1.1 | -0.01em | Short, precise green proof figures. |
| hero-support | SuisseIntl | 300 | 20px | 1.4 | normal | Default opening support, limited to 440px. |
| closing-support | SuisseIntl | 400 | 18px | 24px | normal | Single-line support beneath the closing invitation. |
| body | SuisseIntl | 400 | 16px | 22px | normal | Standard explanatory paragraphs. |
| product-link | SuisseIntl | 500 | 16px | 1.1 | normal | Compact product directory row. |
| action-card-title | SuisseIntl | 600 | 16px | 1.1 | normal | Closing route card title. |
| button | SuisseIntl | 500 | 14px | 1 | normal | Compact action labels. |
| navigation | SuisseIntl | 500 | 14px | 1.5 | normal | Header navigation labels. |
| footer-heading | SuisseIntl | 500 | 14px | 1.1 | -0.01em | Directory group headings. |
| footer-link | SuisseIntl | 300 | 14px | 1.5 | normal | Subdued directory links. |
| announcement | SuisseIntl | 500 | 14px | 1.1 | normal | Short top-strip announcement. |
| small-body | SuisseIntl | 400 | 14px | 20px | normal | Descriptions within cards. |
| eyebrow | SuisseIntlMono | 400 | 12px | 1.5 | normal, uppercase | Technical chapter marker, in a faint tint with a terminal-like trailing cursor. |
| stat-caption | SuisseIntl | 400 | 12px | 1.1 | normal | One- or two-line explanations directly under figures. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail pages | product-display | SuisseIntl | 600 | 56px | 60px | -0.02em | Two-line product promise beside a large illustration. |
| editorial product launches | launch-display | SuisseIntl | 600 | 44px | 48px | -0.02em | Centered launch promise above a wide video. |
| product-detail pages | feature-heading | SuisseIntl | 600 | 36px | 40px | -0.01em | Capability leads and catalog introductions. |
| product-detail pages | testimonial | SuisseIntl | 500 | 32px | 1.25 | -0.01em | Standalone customer quotation, left aligned in a wider proof region. |
| company and culture narratives | editorial-lead | SuisseIntl | 600 | 32px | 36px | -0.01em | Conversational, paragraph-like opening statement. |
| company and culture narratives | editorial-pullquote | SuisseIntl | 500 | 24px | 32px | -0.01em | Blue narrative emphasis alongside a thin vertical rule. |
| product-detail pages | product-support | SuisseIntl | 400 | 20px | 1.3 | -0.01em | Gray explanation under the product promise. |
| product-detail pages | catalog-title | SuisseIntl | 500 | 16px | 1.25 | -0.01em | Small title following a line icon in a catalog card. |

**Notes:**

- Use the default display recipe for general marketing. Product-detail, launch and company openings are separate recipes, not a blended type scale.
- Main text uses the alternate glyph feature "salt" 2. Most headings tighten tracking by 1–3% of the size; small body text keeps normal tracking.
- Headings remain sentence case. Uppercase belongs to the small mono section markers, not the main navigation or headline.
- A heading can begin in solid navy and continue in the same type at 40% opacity. Standard support often uses navy at 60% opacity.
- Keep demonstration text subordinate to marketing text; code is typically 12px/18px and small hero snippets 10px/15px.

## Layout

**Density:** Airy at section level, compact inside the controls and product objects; the long pauses make technical detail feel approachable.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Headline-to-support gap and compact directory grid gaps. |
| 12px | Gap between paired buttons and between row icon and label. |
| 16px | Button side padding and space before an opening action group. |
| 20px | Container side padding, main twelve-column gutter and closing-card gutter. |
| 24px | Eyebrow-to-rule breathing room and bento gutters. |
| 32px | Catalog card padding and grid gutters. |
| 40px | Space before closing route cards and footer column gutters. |
| 48px | Internal separation of major elements in a story card. |
| 64px | Editorial image-to-text chapter spacing. |
| 72px | Product section padding and closing directory padding. |
| 96px | Large catalog introduction padding. |
| 120px | Top breathing room of proof and audience chapters. |
| 144px | Deep platform chapter padding and major chapter separation. |

### Containers and grids

- **container**: max width 1112px · side padding 20px. Centered desktop shell with 1072px of usable content; align headings, media, metrics and directory edges to it.
- **main-grid**: 12 columns · gap 20px. Underlying composition grid; mix five-column copy and seven-column scenes, or two balanced columns.
- **opening-grid**: 2 columns · gap 100px. Balanced copy and floating interface stage. The atmospheric background extends well beyond both columns.
- **closing-grid**: 3 columns · gap 20px. Three equal route cards within the closing panel.
- **catalog-grid** (only for product-detail pages): 3 columns · gap 32px. Equal 336px-by-300px cards within the content shell.
- **section-box** (only for product-detail pages): max width 1280px. Broad milky box surrounds the regular content shell, leaving 80px outer margins at a 1440px viewport.
- **editorial-column** (only for company and culture narratives): max width 536px. Inset long-form reading column alternating with full-shell photo pairs.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls-and-small-cards | 8px |
|  | chapter-panels | 12px |
|  | dots | 50% |
| product-detail pages | broad-feature-boxes | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| catalog-edge | `0px 0px 0px 1px rgba(0,0,0,0.05), 0px 1px 3px 0px rgba(0,0,0,0.05)` | Low-relief catalog cards. |
| floating-glass | `24px 48px 64px 0px rgba(30,30,44,0.15), 0px 0px 0px 1px #ffffff inset` | Hero interface card, creating more depth than the surrounding marketing controls. |
| closing-card | `0px 1px 2px 0px rgba(0,0,0,0.1)` | Glass route cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default page field.

**CSS:** `background: #f6f6f8`

**Observed:** Almost white, with enough cool tone to reveal white cards and soft light.

**Transfer:** Keep text sections on this field rather than introducing unrelated gray bands.

#### Deep platform · level 0

**Use:** A distinct technical capability chapter.

**CSS:** `background-color: #011821; background-image: radial-gradient(circle, rgba(255,255,255,0.075) 0px, rgba(255,255,255,0.075) 1px, rgba(0,0,0,0) 1px); background-size: 16px 16px; border-radius: 12px; margin: 0px 12px`

**Observed:** A near-full-width bounded dark field retains tiny dots, low-contrast glass objects and icy cyan headings.

**Transfer:** Use it for a deep explanation of the new product's system, not as a full-site dark theme.

#### Closing field · level 0

**Use:** Shared action destination and footer backing.

**CSS:** `background: #eeeff2; border: 1px solid #e3e4e8; border-radius: 12px; margin: 0px 12px; overflow: hidden`

**Observed:** The integrated panel contains the invitation, three route cards and a link directory. A low-opacity spectrum pattern is subdued behind a neutral veil.

**Transfer:** Preserve a single continuous field for both conversion and navigation.

#### Floating glass · level 2

**Use:** Hero interface object.

**CSS:** `background: rgba(255,255,255,0.8); border-radius: 8px; backdrop-filter: blur(8px); box-shadow: 24px 48px 64px 0px rgba(30,30,44,0.15), 0px 0px 0px 1px #ffffff inset`

**Observed:** A compact 324px-wide object with a clean white content area and a dimmer code/status tail floats over the dotted art.

**Transfer:** Show one real action or result, not an entire dashboard.

#### Milky feature box · level 1

**Only for:** product-detail pages

**Use:** Large capability demonstration sections.

**CSS:** `background: rgba(255,255,255,0.6); border-radius: 16px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.04); backdrop-filter: blur(4px); padding: 72px 0px`

**Observed:** The broad panel frames copy and technical UI while retaining the regular inner shell.

**Transfer:** Use as a deliberate enclosure around a related capability, not each paragraph.

#### Warm launch field · level 0

**Only for:** editorial product launches

**Use:** Alternate launch theme.

**CSS:** `background: #eceae7`

**Observed:** Warm gray canvas with a soft blush glow behind the video; closing field changes to #f5f3f1 with #e7e4e0 edges and #080b32 ink.

**Transfer:** Apply the whole warm theme consistently to the launch, rather than mixing warm and cool cards arbitrarily.

## Components

### Navigation item

**Use:** Top-level navigation in a transparent, aligned header.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 8px 16px; border-radius: 8px; color: #12161e`

**Text style:** `navigation` — SuisseIntl 500 · 14px/1.5

**Observed:** Wordmark at left, navigation centered, sign-in and a milky get-started trigger at right; dropdown items use a small down chevron.

**States:** Declared: hover background-color rgba(0,0,0,0.02), box-shadow 0 0 1px 0 rgba(0,0,0,0.25); focus-visible box-shadow 0 0 0 2px #a2c1ed.

### Primary button

**Use:** Main opening conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #111a4a; color: #ffffff; border-radius: 8px; padding: 0px 16px; height: 36px; box-shadow: 0px 0px 0px 1px #111a4a, 0px 2px 4px 0px rgba(0,0,0,0.25), 0px 1px 2px 0px rgba(0,0,0,0.25)`

**Text style:** `button` — SuisseIntl 500 · 14px/1

**Observed:** A right chevron follows the short label. A 10%-opacity white-to-transparent top glaze gives the key a slight bevel; the warm launch variant uses midnight blue.

**States:** Declared: hover background-color #111a4a and box-shadow 0 0 0 1px #111a4a, 0 2px 4px rgba(0,0,0,0.25); focus-visible not specified; active reduces the lower shadow to 0 1px 3px rgba(0,0,0,0.15).

### Secondary button

**Use:** Documentation or explanatory action paired with the primary.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(255,255,255,0.5); color: #232730; height: 36px; padding: 0px 16px; border-radius: 8px; backdrop-filter: blur(2px); box-shadow: 0px 0px 0px 1px rgba(87,90,100,0.12)`

**Text style:** `button` — SuisseIntl 500 · 14px/1

**Observed:** Same physical scale as the primary, but translucent and visually quieter. Action groups have a 12px gap.

**States:** Declared: hover background-color #ffffff, box-shadow 0 1px 1px rgba(0,0,0,0.15), 0 0 0 1px rgba(87,90,100,0.2); focus-visible not specified; active removes the lower shadow and retains the edge.

### Announcement strip

**Use:** A compact global launch notice above the header.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 40px; padding: 0px 20px; background: linear-gradient(90deg, #3e5199 0%, #5568ad 100%); color: #ffffff`

**Text style:** `announcement` — SuisseIntl 500 · 14px/1.1

**Observed:** One short announcement, a lighter secondary invitation and a small right arrow form a single horizontal link.

**States:** Declared: hover filter brightness(1.08); focus-visible not specified.

### Product row

**Use:** Compact category directory on the main marketing page.

**CSS:** `display: flex; align-items: center; gap: 12px; padding: 8px; height: 56px; border-radius: 8px; background: rgba(17,26,74,0.03); color: #111a4a`

**Text style:** `product-link` — SuisseIntl 500 · 16px/1.1

**Observed:** A raised 40px square icon tile precedes the label. Rows form a two-column grid beside a narrow category heading.

**States:** Declared: hover background-color rgba(17,26,74,0.05); focus-visible not specified.

**Transfer:** Use concise names for the new product's modules or services.

### Closing route card

**Use:** Three distinct paths to the next step.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; gap: 48px; padding: 24px 32px 32px; height: 209px; border-radius: 8px; background: rgba(255,255,255,0.25); border: 1px solid #ffffff; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.1); backdrop-filter: blur(12px)`

**Text style:** `action-card-title` — SuisseIntl 600 · 16px/1.1

**Observed:** A 66px dot-matrix icon is placed above a bottom-aligned title and a small supporting caption; the entire card is the link.

**States:** Declared: hover background rgba(255,255,255,0.5); focus-visible not specified.

**Transfer:** Offer learning, self-service and human-contact routes appropriate to the product.

### Footer link

**Use:** Directory links inside the closing destination or plain editorial footer.

**CSS:** `color: #7c7f88; text-decoration: none`

**Text style:** `footer-link` — SuisseIntl 300 · 14px/1.5

**Observed:** Groups sit to the right of the wordmark. The broad product group occupies two columns; other groups use one each, with 40px column gutters and 20px list gaps.

**States:** Declared: hover color #12161e; focus-visible not specified.

### Metric pair

**Use:** Quantified proof within an airy four-column row.

**CSS:** `display: flex; flex-direction: column; gap: 4px; color: #167e6c`

**Text style:** `stat` — SuisseIntl 500 · 24px/1.1 · tracking -0.01em

**Observed:** A short green figure sits over a muted caption using stat-caption. Metrics remain modest in scale and span the full content width beneath the graph.

**Transfer:** Use independently defensible proof; when numbers do not exist, pair concise factual milestones with captions.

### Catalog card

**Only for:** product-detail pages

**Use:** Related capability exploration.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: rgba(255,255,255,0.5); border-radius: 8px; padding: 32px; height: 300px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.05), 0px 1px 3px 0px rgba(0,0,0,0.05); backdrop-filter: blur(2px)`

**Text style:** `catalog-title` — SuisseIntl 500 · 16px/1.25 · tracking -0.01em

**Observed:** A blue 24px line icon, small title, 14px description and bottom-pinned Learn more link. Warm-theme cards retain the geometry but use warm stone-white surfaces.

**Transfer:** Describe one concrete capability per card. Keep equal height and bottom-link alignment.

### Standalone testimonial

**Only for:** product-detail pages

**Use:** A spacious social-proof pause between demonstrations and catalog.

**CSS:** `position: relative; padding-bottom: 56px; background: radial-gradient(farthest-side at 50% 100%, rgba(244,106,53,0.15) 0%, rgba(244,106,53,0) 100%); box-shadow: 0px -1px 0px 0px rgba(0,0,0,0.1) inset`

**Text style:** `testimonial` — SuisseIntl 500 · 32px/1.25 · tracking -0.01em

**Observed:** The quote occupies about 755px of a 1080px-wide region. Beneath it are a customer logo, a slim vertical divider, name and role; fine wave contours appear in the warm glow.

**Transfer:** Use a substantive customer observation rather than a generic compliment.

### Editorial pullquote

**Only for:** company and culture narratives

**Use:** Emphasis within a long-form story.

**CSS:** `border-left: 2px solid #a2c1ed; padding-left: 32px; color: #1b2d70`

**Text style:** `editorial-pullquote` — SuisseIntl 500 · 24px/32px · tracking -0.01em

**Observed:** An unboxed statement hangs slightly left of the reading column, separated from neighboring paragraphs by about 40px.

**Transfer:** Emphasize a genuine conviction or productive tension in the new organization's story.

## Imagery and graphics

### Halftone product atmosphere

**Use:** Signature art in the opening and selected audience or proof chapters.

**Observed:** A huge field of circular points resolves into a globe-like silhouette, with mint above and blue below. Dot sizes and opacity diminish at the periphery; a white haze protects copy. A navy point and short dotted trail suggest movement. The scene extends behind the text rather than occupying a hard-edged image rectangle.

**Transfer:** Map the new product's idea to a dotted network, flow or layered silhouette. The minimum version is a recognizable abstract structure made from dots, softly faded behind one glass result card.

**Build:** Use SVG circles on an 8px sampling lattice, varying radii from 0.5px to 3px inside a rounded silhouette. Color by vertical position using green and blue translucent fills. Mask the whole group with a broad radial fade, place a 1080px-by-748px radial cyan wash at rgba(113,210,240,0.15) behind it, and add canvas-colored linear fades at the left and bottom. Keep the visible art concentrated in the right two thirds.

### Floating product objects

**Use:** Opening, customer proof and capability chapters.

**Observed:** White translucent account or transaction cards overlap above a softly lit backdrop. One result is emphasized while secondary cards recede through scale, opacity and blur. Dark chapter objects use icy gray glass inside a larger transparent teal tray; a stack narrows toward the back.

**Transfer:** Reduce a real workflow to two or three purposeful cards. Keep the primary object crisp and subordinate the rest; do not substitute unrelated decorative mockups.

**Build:** Use Floating glass for the leading card, offset two backing cards by 12–24px, reduce their scale and opacity, and put the cluster over a radial dot field. In the dark chapter, back the cluster with a rounded translucent tray, a faint light top edge and two compact destination tiles along its bottom.

### Endpoint graph

**Use:** Quantified proof chapter.

**Observed:** A rising sequence of thin vertical strokes ends in 8px green dots. Pale green-gray trails fade into a dotted backing; the graphic occupies the right half and extends down toward a restrained metric row.

**Transfer:** Show a credible trend, process cadence or repeated events using endpoint marks rather than a heavy dashboard chart.

**Build:** Lay out 8px-wide rounded vertical bars at 16px intervals with varying heights. Fade each bar from rgba(176,200,196,0.5) through rgba(156,217,93,0.05) to transparent and cap it with an 8px #167e6c circle. Fade the outer group radially and keep the lower-left marks especially light.

### Fine wave light

**Use:** Behind proof quotes and selected product objects.

**Observed:** Extremely fine sinusoidal contours sit in a warm, low-contrast glow. They add material depth without competing with the UI or text.

**Transfer:** Use a contour field to connect technical precision with soft light, keeping the pattern barely visible.

**Build:** Repeat an SVG sine path with a shallow 4px amplitude and 24px wavelength at 6px vertical intervals, using rgba(0,0,0,0.04) strokes. Apply a radial mask and place it over a bottom-centered radial gradient from rgba(244,106,53,0.15) to transparent.

### Closing dot icons

**Use:** Signature symbols on the closing route cards.

**Observed:** Simple file, arrow and conversation outlines are drawn in blue dots over a fainter square matrix. The icon stays visually light despite its 66px footprint.

**Transfer:** Choose three simple route symbols that remain legible when sampled on a grid.

**Build:** Build an 11-by-11 grid on a 6px pitch. Inactive circles are 2px diameter at 20% opacity; active circles are 4px diameter in #4575cd. Switch cells on to trace an outline, leaving the faint matrix visible.

### Isometric layer sculpture

**Only for:** product-detail pages

**Use:** Product opening illustration.

**Observed:** One opening uses a giant luminous white dotted sphere; another uses upright translucent planes in navy, violet and pink, staggered inside a rounded transparent isometric frame. Both are large, softly shadowed objects on a pale field.

**Transfer:** Represent the new product's architecture as layered translucent planes, or use a bright dotted sphere when coverage or connectivity is the concept.

**Build:** For the layered version, place six rounded SVG rectangles on staggered isometric planes; move from dark blue in front to pale violet and pink behind, with low-opacity contour lines and a broad soft blue-violet shadow beneath. Keep labels very small and secondary to the silhouette.

### Launch video stage

**Only for:** editorial product launches

**Use:** Main media after the centered promise.

**Observed:** A 900px-by-506px, 8px-rounded video poster shows a presenter in an airy real workspace with warm wood, shelving and greenery. The stage graphic uses pink halftone art, tying the documentary media to the technical visual language.

**Transfer:** Use a real demonstration or presenter, with natural warm surroundings and an uncluttered image; give it a designed dot-art backdrop rather than a generic stock-video still.

### Candid culture photography

**Only for:** company and culture narratives

**Use:** Editorial opening, story interludes and founder profile.

**Observed:** Natural-light office images mix warm wood, plants, glass and human playfulness. Asymmetric 709px/347px photo pairs share a 420px height and 8px corners; later images include an office, an upside-down book and physical instant prints spread on a wood tabletop.

**Transfer:** Photograph real working environments and small human details, not posed studio portraits. Alternate narrow prose with wide pairs and a portrait-oriented photo beside a concise biography.

### Icons

**Observed:** Small interface arrows are 16px with 1.5px strokes. Capability icons are mostly 24px outlined symbols with thin rounded strokes in blue or green; product rows place them inside raised 40px tiles. Closing icons use dots rather than normal strokes.

**Transfer:** Use simple functional line symbols, consistent within each group; keep the unusual dot-matrix language for the larger closing symbols.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric opening

**Observed:** A 40px announcement sits over a transparent header with wordmark, centered navigation and right-side account actions. The first scene is 880px tall: a centered 1112px shell contains two columns with a 100px gap. A small trust badge sits above left copy; the display headline is about 486px wide and wraps into two lines, followed after 8px by a two-line support and paired 36px actions. Behind it, Halftone product atmosphere spans much of the viewport, fading at the text edge. Floating glass sits to the right at about 324px wide, combining a result with a code tail. Back-to-front layers are cool canvas, cyan wash, dotted structure, protective pale fades, copy and floating object. Within the first 900px the headline, support, actions, dominant object and a low monochrome logo strip are visible; the quantified proof chapter begins below.

**Transfer:** Use this as the default new marketing opening. Replace the globe with a dotted model of the new product and the interface card with one meaningful result. Product-detail openings are shorter split stages with product-display and one large sculpture; editorial launches center launch-display over a video, while company narratives use editorial-lead and asymmetric photography.

**Avoid:** Do not turn this into a centered giant headline above a conventional dashboard rectangle, or shrink the dot art into an isolated icon.

**Text style:** `display` — SuisseIntl 600 · 52px/1.1 · tracking -0.03em

### Marked section lead

**Observed:** A tiny tinted mono Eyebrow precedes a 1px rule across the content shell. Below, a 28px medium heading may continue in a lighter 40%-opacity phrase; longer catalog leads use heading-lg. Support sits 8–20px below and a compact secondary action follows.

**Transfer:** Give each chapter a short technical marker, a proposition and an explanation. Select heading size by narrative importance rather than using the largest recipe everywhere.

### Light quantified proof

**Observed:** An Endpoint graph spreads behind the right half of a 28px heading-and-support column. Four Metric pairs span the full width below, using 24px green figures and 12px captions. There is no heavy chart frame or axis furniture.

**Transfer:** Pair compact proof facts with one restrained data or process graphic; keep the information hierarchy in the text.

### Customer story stage

**Observed:** A 1072px-wide, 12px-rounded white panel has a row of customer-logo tabs across the top; one active tab is orange and raised. Below, a 28px case headline, small capability tags and a compact quotation occupy the left; layered Floating product objects and warm dots occupy the right. The quotation is anchored low, separated from the headline by substantial air.

**Transfer:** Turn one customer workflow into a visual narrative, using a product-specific accent only within this story module.

### Deep capability chapter

**Observed:** Deep platform introduces a 48px icy headline opposite an isometric stack. Successive rows pair a narrow text and code column with a wider glass object tray. Text headings are 20px medium, descriptions are 16px light, and the art is muted rather than neon. The chapter has 144px top and bottom padding and a 12px outer inset.

**Transfer:** Explain the new product's primitives with one crisp object per row and real technical detail; keep the visual focus on a single result at a time.

### Audience selector

**Observed:** A marked chapter pairs a vertical list of 40px/44px, weight-500 choices with a 448px-by-600px dotted illustration on the right. The selected choice has a milky glass plate and dark teal text; inactive choices are faded. Two restrained 16px paragraphs update below the choices.

**Transfer:** Use this for genuinely distinct use cases or audiences; create a distinct halftone silhouette for each, with the same scale and lighting.

### Product directory

**Observed:** The main marketing directory puts a 48px heading above category rows. A narrow 20px category title sits at left and a two-column Product row grid sits right, with 8px gaps and 72px between categories. Product-detail pages instead use a 36px lead and a three-column Catalog card grid over very faint waves.

**Transfer:** Choose the compact directory when showing breadth, and the descriptive card variant when readers need to compare unfamiliar modules.

### Closing destination

**Observed:** Closing field begins with a 60px invitation about 100px below its edge and an 18px support line after 8px. Three Closing route cards sit below with 20px gutters. The integrated footer follows after generous space: a faint wordmark on the left and four directory columns to the right, with 72px padding. The warm launch theme preserves this structure in warmer neutrals. Company narratives end instead with a plain white directory and a 1px-separated legal strip, without the large invitation.

**Transfer:** Keep this closing device on new marketing and product pages, adapting the three routes to actual next steps. Use the plain editorial ending only for a company or culture narrative.

**Text style:** `closing` — SuisseIntl 600 · 60px/1 · tracking -0.01em

### Capability demonstration

**Only for:** product-detail pages

**Observed:** Within Milky feature box or an open pale canvas, a 36px capability heading and 16px explanation align beside a navy code panel. Alternate the media side for subsequent chapters; larger demonstrations can center the lead above paired code panels and an oversized white interface view.

**Transfer:** Translate benefit into concrete operation and visible result. Keep code and interface examples tied to the same claim.

### Asymmetric bento

**Only for:** product-detail pages with multiple program benefits

**Observed:** A 36px lead precedes a three-column grid with 24px gaps. A large 707px-wide white card spans two columns beside stacked 341px cards; the next row reverses the emphasis. Cards have 12px corners, 32–48px padding, blue check icons, and low-relief UI illustrations. Large card titles are centered at 24px, smaller titles at 16px.

**Transfer:** Reserve the large spans for benefits that can be demonstrated visually; put service or trust facts in the small cards.

### Human editorial story

**Only for:** company and culture narratives

**Observed:** An inset 32px opening statement sits on a green-blue glow with fine contour texture above staggered photographs. The story alternates a 536px text column with broad photo pairs, uses Editorial pullquote for convictions, and ends its narrative with a 520px-wide portrait-oriented image beside a short founder introduction.

**Transfer:** Tell a concrete origin or operating philosophy through actual people and details. Keep the typography more paragraph-like than the product promise.

## Page flow

**Storyline:** Promise → tangible product or human demonstration → proof → capability or belief chapters → broader exploration → an appropriate next step.

### Establish a multi-capability platform and its trustworthiness

1. **Promise** — Atmospheric split opening with dotted art, compact product result and a monochrome proof strip.
2. **Quantified proof** — Marked lead, endpoint graph and four modest green metrics.
3. **Social proof** — Tabbed customer story with layered UI.
4. **Technical credibility** — Developer explanation and a tangible request/response object.
5. **Capability chapters** — Bounded deep teal system chapter with successive product scenes.
6. **Audience relevance** — Large vertical selector and matching dotted artwork.
7. **Exploration** — Compact categorized product rows.
8. **Closing call** — Large invitation, dot-icon routes and integrated footer.

**Transfer:** Use a broad-to-specific platform narrative, retaining the graphic and closing devices without requiring the same number of chapters.

### Explain a technical operation through control, speed and visibility

1. **Promise** — Split product-display opening beside a luminous dotted sphere.
2. **Capability demonstration** — Milky timing-and-code section with small operational figures.
3. **Mechanism** — Alternating interface view and code example.
4. **Transparency** — Centered lead above raw data, request examples and a large interface view.
5. **Social proof** — Standalone quotation over fine warm waves.
6. **Exploration** — Descriptive capability catalog and a secondary category row.
7. **Closing call** — Shared three-route closing destination and footer.

**Transfer:** Borrow the promise-to-mechanism progression for any product where direct control is the main benefit.

### Introduce a major product launch with an editorial presentation

1. **Promise** — Centered launch title and actions above a wide presenter video on warm stone.
2. **Differentiation** — Milky explanation beside a concise code example.
3. **Ecosystem demonstration** — System relationship graphic and a vertical sequence of related operations.
4. **Social proof** — Standalone warm-wave quotation.
5. **Exploration** — Warm-surface catalog cards.
6. **Closing call** — Warm variant of the shared closing destination and directory.

**Transfer:** Use the warm video-led variant for an editorial launch, not as the default platform opening.

### Make a complex service program feel programmable and trustworthy

1. **Promise** — Split product opening with an isometric stack of translucent planes.
2. **Capability chapters** — Asymmetric white bento mixing demonstrations and small trust benefits.
3. **Social proof** — Large customer quotation and attribution.
4. **Exploration** — Shared descriptive catalog and related service category.
5. **Closing call** — Shared invitation, three dotted route cards and integrated footer.

**Transfer:** Use this structure when benefits mix software functionality with human expertise or compliance support.

### Humanize the organization and explain its conviction

1. **Introduction** — Conversational inset statement and playful natural-light photo pair.
2. **Belief** — Narrow prose with blue ruled pullquotes and broad office photographs.
3. **Operating philosophy** — Concrete cultural details and inline links.
4. **Human proof** — Physical instant-print photograph beside a concise founder biography.
5. **Navigation ending** — Plain white directory followed by a separate legal strip.

**Transfer:** Use a slower editorial rhythm and genuine human material; do not bolt the large product conversion block onto this narrative.

## Writing

Confident, technically literate and mildly contrarian. Claims are expressed through direct operations, control and concrete constraints rather than grand futuristic language; human narratives allow dry humor.

**Do not copy:** Do not reuse Column's name, wordmark, customer logos, quotations, regulatory status, financial claims, operating metrics or proprietary product artwork. Substitute the new product's real facts, authorized customer material and original graphics. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to builders as you and your. Use we when describing how the organization built or operates the product; product explanations use active verbs.
- **Rhythm:** Short sentence-case headlines, often 4–9 words; one- or two-sentence support lines; longer explanations enumerate concrete actions. Compact actions are usually 2–4 words. Avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Lead with an operational verb or a concise claim of control. | 4–10 words | “Move, hold, and lend the dollar at scale”<br>“Complete control of FedWire”<br>“Build a national lending program” |
| Capability lead | Replace an old constraint with a direct benefit. | 4–9 words | “Say goodbye to business hours”<br>“Truly instant, 24/7/365” |
| Explanation | Explain the operation and remove ambiguity with a concrete mechanism. | 1–3 sentences | “Originate and settle loans directly from our APIs. Never send spreadsheets again.”<br>“Programmatically send wire transfers in one API call. Funds are transferred instantly to any U.S. bank account.” |
| Action | Name the next useful activity, not an abstract conversion. | 2–4 words | “Read our docs”<br>“Start building”<br>“Contact sales” |
| Closing invitation | A simple imperative with an immediate time horizon. | 3–5 words | “Start building today” |
| Human narrative | A candid admission or a concrete anecdote interrupts the institutional voice. | One short statement | “We were always told that banks can't be software companies.”<br>“We are a bit of a weird company — not your standard tech or finance company.” |

**Words and phrasing to use:** build; direct; control; programmatically; native; flexible; from scratch; on your terms; one API call; without layers

**Avoid:** revolutionary; game-changing; unlock limitless potential; magic; disrupt everything; effortlessly amazing

**Rules:**

- Pair a bold benefit with a mechanism, an interface action or a precise limit.
- Use technical nouns where they clarify capability; explain them through verbs rather than padding the headline with jargon.
- Use comparisons to legacy constraints sparingly and follow them immediately with the practical alternative.
- Let captions explain what a number means; the number alone is not the argument.
- Keep humor in people-oriented narrative, not in operational or compliance promises.

## Do's and Don'ts

### Do

- Keep the 1112px shell and 20px side padding aligned across otherwise different chapter layouts.
- Use 52px/1.1, weight 600 and -0.03em tracking for the default opening promise.
- Keep 36px controls small enough that the product scene, not the CTA, dominates the opening.
- Give the dot atmosphere a radial fade and a pale protective zone behind the copy.
- Use 24px green figures with 12px explanatory captions rather than giant dashboard statistics.
- Stage one crisp result card against dimmer, offset cards to communicate depth.
- Retain the 12px outer inset and rounded continuity of the closing destination.
- Use candid warm photography only within the human editorial variant.

### Don't

- Do not turn 8px button corners into full pills; the small key-like geometry is important.
- Do not use orange as the general conversion color; it belongs to compact customer proof accents.
- Do not give every text block a white card; open pale sections provide the narrative breathing room.
- Do not use giant uppercase mono headings; the mono voice belongs at 12px in chapter markers.
- Do not bring saturated neon bloom into the dark chapter; use low-contrast teal glass and icy text.
- Do not flatten the related-product catalog into rows of centered icons and centered text; it is left aligned with bottom-pinned links.
- Do not replace the closing dot-matrix symbols with oversized solid emoji or generic filled icons.
- Do not exaggerate interface shadows across all marketing cards; the strongest shadow belongs to floating product objects.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare box-shadow, background-color and border-color transitions of 0.2s. Navigation background and footer text color transitions are 0.2s.
- Catalog cards declare box-shadow 0.75s and background-color 0.4s. Closing route cards declare background 0.2s.
- The bounded dark and closing panels declare border-radius 0.5s transitions.
- Dot fading, typing cursors, gradient animation and staged interface-object changes belong to the visual language; the company gradient declares an 8s animation repeated four times.

**Transfer:**

- Keep small control feedback quick and restrained; preserve the slower surface response on catalog cards.
- Animate dots and object layers as atmospheric support to readable, settled copy, not as competing decorative motion.

**Unknown:**

- Exact scroll triggers, path behavior and full motion choreography are not defined here; do not infer timing for new effects from the settled compositions.

### Responsive

**Observed:**

- Declared width breakpoints include 374px, 479px, 480px, 640px, 768px, 870px, 1112px and 1280px; the main marketing styling also includes 1024px and 1200px.

**Transfer:**

- As a narrow-screen adaptation, stack copy before the product object, keep the dot atmosphere behind the object, and retain its fading edge.
- Collapse catalog and closing routes to fewer columns while preserving the icon-title-caption order; allow the compact category directory to become a single column.

**Unknown:**

- Specific mobile type sizes, navigation behavior and exact breakpoint-to-layout mappings are not established. These stacking rules are design guidance rather than a separate measured mobile system.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
