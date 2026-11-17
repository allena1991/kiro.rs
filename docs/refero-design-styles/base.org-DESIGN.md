# Base — electric modular infrastructure

## Overview

An exceptionally white, open technical style with electric blue punctuation and small, finely drawn machine-like illustrations. Regular-weight grotesk type makes ambitious promises feel matter-of-fact, while monospaced captions lend proof a technical register. It suits infrastructure and platform marketing with a sparse editorial surface; a dark developer-oriented variant introduces terminals, luminous edges and vivid tool panels.

### Essentials

- Big promises, small chapter titles: regular grotesk headlines use 72px/1.03 and -0.04em tracking, while ordinary section headings stay at 28px/36px with -0.025em tracking.
- The opening is a clearing in a digital field: a centered two-line headline occupies about 550px of a 1440px-wide white stage, surrounded by faint blue pixel trails rather than a giant product mockup.
- Actions are compact capsules, not blocks: 48px-high pills with 20px side padding, 16px regular labels and a blue primary paired with a white hairline secondary; navigation uses a 34px capsule.
- Color is concentrated rather than spread: white and near-white dominate, blue marks actions and labels, and a saturated 333px-high art band supplies the major color event.
- Technical pictures behave like diagrams on a workbench: thin outlines, tiny square nodes, rings and blue modules sit centered in 12px-radius hairline frames; use a simple custom process diagram when elaborate artwork is unavailable.
- Every page needs a digital-material flourish and a monumental brand ending: include segmented vertical-line artwork in blue and white, plus an oversized low-contrast silhouette of the new product's own mark, spanning the content width. These devices need not dictate section order.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#0000ff` | `--color-blue` | action, accent, link, background | Primary capsules, section labels and saturated art bands; wide-gamut blue is represented by this hex fallback. |
| Blue-band translucent button | `#3333ff` | `--color-band-button` | surface | Visible white-at-20% fill over electric blue; use rgba(255,255,255,0.2). |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas and reversed text or buttons. |
| Near-white wash | `#f8f8f8` | `--color-wash` | background, surface | Proof bands, editorial cards and gentle hover fills. |
| Hairline gray | `#efefef` | `--color-edge` | border, surface | Card edges and separators; also the light fill of the monumental brand silhouette. |
| Silhouette underlay | `#e5e5e5` | `--color-underlay` | surface | Backing layer beneath the masked closing brand artwork. |
| Body gray | `#787878` | `--color-body` | text | Default paragraph and metric-caption color. |
| Support gray | `#6f6f6f` | `--color-support` | text | Hero supporting line and muted large introductory statements. |
| Action ink | `#171717` | `--color-action-ink` | text, surface | Secondary action labels; also the raised panel tone in the dark variant. |
| Black | `#000000` | `--color-ink` | text | Headings and primary editorial text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| developer-oriented landing pages | Developer charcoal | `#111111` | `--color-dark-canvas` | background | Dark page canvas. |
| developer-oriented landing pages | Dark panel edge | `#262626` | `--color-dark-edge` | surface, border | Terminal rim, footer silhouette and dark panel outlines. |
| developer-oriented landing pages | Dark muted text | `#9a9a9a` | `--color-dark-muted` | text | Body text on charcoal. |
| developer-oriented landing pages | Developer action blue | `#224bff` | `--color-dark-blue` | action, background | Dark-theme primary actions and closing band. |
| developer-oriented landing pages | Terminal blue | `#5b8cff` | `--color-light-blue` | text, accent | Labels, terminal output and luminous edge detail. |
| developer tool showcases | Scanline cobalt | `#2f4ad7` | `--color-tool-blue` | surface | Blue tool-card graphic backing. |
| developer tool showcases | Tool lime | `#67ed0e` | `--color-tool-green` | surface | Bright green tool-card graphic backing. |
| developer ecosystem carousels | Ecosystem yellow | `#ffe143` | `--color-tile-yellow` | surface | A single colorful ecosystem tile. |

## Typography

- **baseSans** — Headlines, titles, navigation and action labels. Regular grotesk with open counters, broad round forms and tightly fitted display text. If unavailable, use **Inter**. Use weight 400 and retain tight display tracking. Font stack: "baseSans", "Inter", Arial, sans-serif.
- **baseSansText** — Paragraphs, descriptions and footer links. Text-tuned companion sans with untracked, readable small text. If unavailable, use **Inter**. Font stack: "baseSansText", "Inter", Arial, sans-serif.
- **baseSansMono** — Metric captions and technical annotations. Small technical monospace, mostly regular and uppercase. If unavailable, use **Geist Mono**. Font stack: "baseSansMono", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | baseSans | 400 | 72px | 1.03 | -0.04em | Default centered opening promise. |
| intro-statement | baseSans | 400 | 32px | 1.25 | -0.04em | Two-tone introductory statement with the product name in black and the remainder gray. |
| heading | baseSans | 400 | 28px | 36px | -0.025em | Section leads and closing invitation. |
| lead | baseSans | 400 | 20px | 1.4 | -0.025em | Hero supporting copy and feature titles. |
| card-title | baseSans | 400 | 18px | 28px | -0.025em | Compact card titles and accordion questions. |
| body | baseSansText | 400 | 16px | 1.4 | normal | Supporting paragraphs and card descriptions. |
| action | baseSans | 400 | 16px | 1.4 | -0.01em | Main button labels. |
| navigation | baseSans | 400 | 16px | 1.4 | normal | Desktop menu labels. |
| label | baseSans | 400 | 14px | 20px | -0.01em | Blue chapter eyebrows, footer column headings and compact CTA labels. |
| metric-caption | baseSansMono | 400 | 12px | 20px | normal, uppercase | Restrained uppercase captions under metrics. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| focused product landing pages | product-display | baseSans | 400 | 56px | 64px | -0.04em | Centered product promise or left-hand headline alongside a demonstration. |
| focused product landing pages | product-metric-caption | baseSansMono | 400 | 12px | 20px | -0.01em, uppercase | Labels below the larger standalone proof figures. |

**Notes:**

- Headings remain weight 400; the hierarchy comes from size and negative tracking, not boldness.
- Use -0.04em on the largest promises and introductory statement; ease to -0.025em for section and card titles. Body paragraphs use the text family with normal tracking.
- Metric values are plain sans numerals, visually larger than their small mono captions; keep them as short independent expressions rather than prose.

## Layout

**Density:** Airy at the page level, compact inside controls and text groups; large white intervals separate technically dense illustrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gaps and footer link rhythm. |
| 12px | Closing text stacks and paired band actions. |
| 16px | Hero text stacks, action pairs and three-column card gutters. |
| 20px | Compact card padding and button side inset. |
| 24px | Editorial carousel gutter and general panel padding. |
| 28px | Dark showcase card padding. |
| 32px | Desktop container side inset, two-column gutters and section-heading-to-content spacing. |
| 40px | Centered heading-to-metric group spacing. |
| 48px | Statement-to-feature-grid separation and footer group separation. |
| 64px | Wide proof-column gutters and split FAQ gutter. |
| 80px | Standard desktop section vertical padding. |
| 112px | Roomier centered proof-band vertical padding. |
| 160px | Split product hero top padding. |

### Containers and grids

- **Content container**: max width 1200px · side padding 32px. Centered border-box container; at 1440px the interior is 1136px wide and begins 152px from the window edge.
- **Feature pairs**: 2 columns · gap 32px. 552px-wide illustrated capability modules, arranged as pairs.
- **Compact feature trio**: 3 columns · gap 16px. 368px-wide bordered capability cards.
- **Footer columns**: 4 columns · gap 32px. 260px-wide groups: status and social identity followed by grouped navigation.
- **Proof columns** (only for focused product landing pages): 4 columns · gap 64px. Standalone short figures and captions across a full-width neutral band.
- **Setup column** (only for developer onboarding sections): max width 800px · side padding 0px. Centered instructional sequence narrower than the ordinary content container.

## Corner radius

| Element | Radius |
| --- | --- |
| Action capsules | 9999px (pill) |
| Cards and picture frames | 12px |
| Large demonstration panels | 16px |
| Navigation menu target | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| developer demonstrations | Terminal halo | `0px 0px 18px 2px rgba(34,75,255,0.25)` | Subtle blue rim around a dark demonstration window, not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Proof wash · level 0

**Use:** Quiet full-width proof or demonstration bands.

**CSS:** `background: #f8f8f8`

**Observed:** Flat neutral contrast without floating shadows.

**Transfer:** Use to distinguish quantitative proof from white capability chapters.

#### Hairline frame · level 1

**Use:** Capability pictures and cards.

**CSS:** `background: #ffffff; border: 1px solid #efefef; border-radius: 12px; box-shadow: none`

**Observed:** The boundary is deliberately faint; framed pictures contain large internal white margins.

**Transfer:** Let the picture, not a heavy panel treatment, carry visual detail.

#### Electric art band · level 0

**Use:** High-impact conversion moment.

**CSS:** `background: #0000ff; color: #ffffff; overflow: hidden`

**Observed:** Full-width 333px-high field with segmented line art on the right and a blue-to-transparent cover that protects the copy at the left.

**Transfer:** Give a short invitation an intentionally vivid material backdrop.

#### Developer canvas · level 0

**Only for:** developer-oriented landing pages

**Use:** Alternate charcoal world.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Raised cards use dark neutral fills and very low-contrast edges, not broad luminous gradients.

#### Terminal panel · level 1

**Only for:** developer demonstrations

**Use:** Hero runtime or command demonstration.

**CSS:** `background: #171717; border-radius: 16px; backdrop-filter: blur(16px); box-shadow: 0px 0px 18px 2px rgba(34,75,255,0.25)`

**Observed:** A thin dark rim and restrained blue edge light surround an approximately 544px by 440px terminal.

## Components

### Primary button

**Use:** Main conversion on white.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #0000ff; color: #ffffff; border: 1px solid transparent; border-radius: 9999px; height: 48px; padding: 0px 20px 0px 18px; gap: 10px`

**Text style:** `action` — baseSans 400 · 16px/1.4 · tracking -0.01em

**Observed:** A small square mark precedes the label. Width follows content. The band variant reverses to white with black text and a blue mark; dark product pages use developer action blue.

**States:** Declared: hover background-color rgba(0,0,204,1); active transform returns to identity.

### Secondary button

**Use:** Exploratory action paired with a primary.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #171717; border: 1px solid #efefef; border-radius: 9999px; height: 48px; padding: 0px 20px; gap: 12px`

**Text style:** `action` — baseSans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Text-only in the opening; deeper-page versions can carry a trailing chevron. Neutral filled actions use a light gray capsule.

**States:** Declared: hover background-color rgba(248,248,248,1); active transform returns to identity.

### Band secondary button

**Use:** Second action against the electric art band.

**CSS:** `background: rgba(255,255,255,0.2); color: #ffffff; border: 1px solid transparent; border-radius: 9999px; height: 48px; padding: 0px 20px`

**Text style:** `action` — baseSans 400 · 16px/1.4 · tracking -0.01em

**Observed:** Sits beside the reversed Primary button without an outline.

**States:** Declared: hover background-color rgba(255,255,255,0.3); active transform returns to identity.

### Navigation menu target

**Use:** Desktop top navigation.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 6px 12px; border-radius: 8px`

**Text style:** `navigation` — baseSans 400 · 16px/1.4

**Observed:** Four centered menu targets with small down chevrons. A compact mark anchors the left and a compact CTA anchors the right in a 64px-high fixed row below a 40px announcement strip.

### Compact navigation CTA

**Use:** Persistent conversion entry.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 6px; background: #0000ff; color: #ffffff; border-radius: 9999px; height: 34px; padding: 0px 12px 1px`

**Text style:** `label` — baseSans 400 · 14px/20px · tracking -0.01em

**Observed:** Short label with right chevron; reversed white on the dark theme.

### Compact capability card

**Use:** Route readers into a product capability.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 20px; border: 1px solid #efefef; border-radius: 12px`

**Text style:** `card-title` — baseSans 400 · 18px/28px · tracking -0.025em

**Observed:** Small blue diagram icon above a title and short Body description; a pale chevron occupies the upper right. The entire card is linked.

**States:** Declared: hover background-color rgba(248,248,248,1).

### Editorial card

**Use:** News and customer-story carousel.

**CSS:** `background: #f8f8f8; border-radius: 12px; overflow: hidden; max-width: 350px`

**Text style:** `card-title` — baseSans 400 · 18px/28px · tracking -0.025em

**Observed:** A 2:1 image spans the top. Below it are a single-line title, short gray description and small date. Text area uses 20px side and bottom insets and 16px top inset. Cards extend beyond the right content boundary in a 24px-gap horizontal track.

### Footer link group

**Use:** Grouped site navigation at the end.

**CSS:** `display: flex; flex-direction: column; gap: 8px`

**Text style:** `label` — baseSans 400 · 14px/20px · tracking -0.01em

**Observed:** A black section label heads muted text-family links at 14px/20px. Four columns include a blue operational-status link and social icons at the left; legal links and copyright sit below the oversized mark.

### FAQ row

**Only for:** explanatory product landing pages

**Use:** Objection handling in a focused product narrative.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 20px 0px 12px; width: 100%`

**Text style:** `card-title` — baseSans 400 · 18px/28px · tracking -0.025em

**Observed:** A hairline top rule belongs to the row wrapper. A plus indicator sits opposite the question; the expanded answer uses Body text directly below. Rows occupy the right-hand 556px column.

### Ecosystem tile

**Only for:** developer ecosystem carousels

**Use:** Colorful third-party discovery card.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 28px; background: #ffe143; border: 1px solid rgba(154,154,154,0.1); border-radius: 12px; width: 370px; height: 370px`

**Text style:** `lead` — baseSans 400 · 20px/1.4 · tracking -0.025em

**Observed:** Title and short description align at the top, a large partner illustration below. Neighboring tiles use contrasting light gray, brown or teal backings. The track deliberately reveals an overflow card.

## Imagery and graphics

### Pixel-field atmosphere

**Use:** Signature opening material behind the promise.

**Observed:** The field is mostly white, with sparse islands of blue, pale green and violet-looking rectangular marks. Vertical trails appear around the periphery and behind the actions; the center is washed clear for type. It reads as a digital signal, not a full illustration.

**Transfer:** Use abstract signal trails to suggest the new product's activity. A flat SVG of tiny blue marks fading into white is the minimum acceptable version.

**Build:** Scatter groups of 3–7 vertical columns of 2–6px rectangles with unequal heights around the stage edges. Vary blue opacity from 0.05 to 0.45. Place a radial white overlay above them, opaque through roughly the central third and transparent at the edges; add white top, bottom and 96px side fades. Keep text and controls on the highest layer.

### Instrument diagrams

**Use:** Core capability illustrations.

**Observed:** White-backed vector constructions resemble gauges, circuit paths, token rings and small mechanical consoles. Thin black and pale-gray outlines meet electric-blue squares, tiny colored accents and visible node handles. Pictures occupy the upper part of paired frames, with text outside below.

**Transfer:** Create a precise diagram of a process or benefit with two or three recognizable modules connected by thin paths. Preserve the generous white backing rather than substituting glossy 3D or full-bleed photography.

**Build:** Use SVG groups of concentric circles, straight paths with rounded elbows, small outlined square nodes and one saturated blue central module. Use 1–2px lines and tiny endpoint squares. Center the construction within a hairline frame with at least 40px of air around its main geometry.

### Segmented signal art

**Use:** Signature saturated-band artwork.

**Observed:** A large wave-like mass of extremely fine vertical threads and short white or pale segments enters from the right and clips at the band edges. It balances the left-aligned invitation without competing with the text.

**Transfer:** Rebuild as an abstract activity field for any product; no literal financial shape is needed.

**Build:** On electric blue, draw hundreds of 1px vertical SVG strokes spaced about 6px apart. Modulate their endpoints with overlapping sine-like envelopes, adding brighter short white segments at selected positions and lower-opacity long threads. Scale beyond the band bounds. Overlay a left-to-right blue-to-transparent gradient, opaque through 30% and transparent by 70%.

### Monumental mark silhouette

**Use:** Signature footer anchor.

**Observed:** An oversized low-contrast geometric brand silhouette spans 1136px by 372px beneath the link columns, followed by a very small legal row. It is an intentionally solid shape, not a row of content cards. Dark pages render it in charcoal gray.

**Transfer:** Use the new product's own recognizable word or symbol as a broad, low-contrast closing sculpture; a custom geometric monogram is a suitable fallback.

**Build:** Create a single SVG mask from a simplified wordmark or monogram and stretch its containing block to the content width while preserving aspect ratio. Fill with hairline gray on white, or dark panel gray on charcoal. Give it enough height to feel architectural, about 372px at a 1136px width.

### Coverage globe

**Only for:** geographic or network-coverage demonstrations

**Use:** Large editorial product demonstration.

**Observed:** A near-white 1136px by 560px rounded panel combines a narrow translucent list on the left with a large blue-and-gray globe built from vertical rounded bars on the right. Small dark labels attach to points around the globe.

**Transfer:** Represent locations, categories or connected resources using the same fine-bar globe or a comparable topology; keep list and visualization legible as one scene.

**Build:** Use an SVG circular clipping mask over narrow vertical gray bars. Color selected bar segments blue to define regions, and overlay small dark rounded labels. Reserve a 288px left rail with a faint divider and softly fading list ends.

### Developer terminal and scanline tools

**Only for:** developer-oriented landing pages

**Use:** Dark hero demonstrations and tool showcases.

**Observed:** The terminal uses block-character imagery and sparse blue boot messages in a dark window with a faint blue halo. Lower tool panels are cobalt and lime with horizontal or vertical scanlines, top-aligned text and bottom-left white capsules.

**Transfer:** Show a real command or concise process state instead of invented decorative code. Tool cards can depict a product-specific abstract activity pattern.

**Build:** For the terminal, layer a dark rounded panel over a larger dim-blue rim and halo. For tool panels, place repeating 1px low-opacity dark lines every 4px over cobalt or lime, then add a broad low-contrast diagonal wave mask. Keep the text layer free of busy motifs.

### Icons

**Observed:** Utility chevrons are 10px with 1.5px strokes; action arrows are commonly 16px with 1.5px strokes. Compact capability icons are about 32px and use blue outlines with pale fills. Social marks are muted solid glyphs.

**Transfer:** Choose simple geometric utility arrows and small custom technical pictograms; keep expressive diagrams separate from utilitarian navigation icons.

## Section recipes

How recurring sections are built.

### First screen: Promise in a digital clearing

**Observed:** A 684px-high white stage begins behind the navigation. From back to front: Pixel-field atmosphere, white radial and edge fades, centered copy, then capsule actions. The 72px Display wraps into two balanced lines across roughly 550px in the middle of the stage; its first line begins around the upper third. A 20px gray Lead sits 16px beneath it. Primary button and Secondary button form a centered pair below, separated by 16px. Within the first 900px, the navigation, complete headline, support, actions, atmospheric field and monochrome partner strip are visible; the next capability row only begins near the fold. The main visual object is the ambient signal field, not a screenshot.

**Transfer:** Use an equally direct promise and create Pixel-field atmosphere even without product imagery. Focused product pages use the 56px Product-display: either centered over the field, or left-aligned in a two-column stage with a real demonstration at the right. Developer-oriented pages use the charcoal canvas and terminal scene.

**Avoid:** Do not turn the default opening into a full-bleed app screenshot, a dark gradient hero or a wall of feature cards.

**Text style:** `display` — baseSans 400 · 72px/1.03 · tracking -0.04em

### Trust strip

**Observed:** A small centered trust sentence sits above a single row of monochrome partner marks. The strip is roughly 120–132px high, with subdued edges and substantial space around the marks.

**Transfer:** Use verified customer or integration proof in muted monochrome; let the promise remain the visual leader.

### Heading and capability chapter

**Observed:** A blue Label precedes a 28px Heading by 8–16px, with optional Body support 8px below. Chapters use 80px vertical padding. Compact capability cards form trios; Instrument diagrams form paired framed pictures with Lead titles and Body descriptions below.

**Transfer:** Organize a few concrete benefits per chapter, choosing compact cards for routes and larger diagram frames for explanations.

**Text style:** `heading` — baseSans 400 · 28px/36px · tracking -0.025em

### Two-tone platform statement

**Observed:** A 32px Intro-statement begins with a black product name and continues in gray across two lines. An exploratory capsule aligns to its right; 48px separates the statement from the paired diagram grid.

**Transfer:** Make the statement define the product in a single sentence rather than list features.

**Text style:** `intro-statement` — baseSans 400 · 32px/1.25 · tracking -0.04em

### Quantified proof band

**Observed:** Proof wash carries a centered Heading and Body support above four compact metric groups. The broad overview version uses short values, mono Metric-caption labels and subtle 24px-high vertical separators. Product variants use a 208px-high band with four larger values and 64px column gutters; dark variants use a faint charcoal band.

**Transfer:** Keep each value brief with its unit attached, then identify what it measures in a restrained uppercase caption. Use substantiated proof rather than decorative numbers.

### Wide customer proof rows

**Observed:** Large 12px-radius Hairline frames stack vertically. Each begins with a category heading and muted inline explanation, then splits into two customer summaries with marks, Body text and neutral capsules; a fine vertical rule divides the halves.

**Transfer:** Use for categorized examples or complementary integrations rather than forcing all proof into identical small tiles.

### Instructional and assurance modules

**Observed:** Explanatory product narratives combine numbered steps, full-width hairline benefit rows, and a split FAQ section with a Heading on the left and FAQ rows in a 556px right column. Developer onboarding instead narrows to an 800px column with a vertical numbered guide, tool selectors and copyable commands.

**Transfer:** Choose the explanatory module that removes the reader's actual implementation uncertainty; keep technical interaction controls scoped to onboarding.

### Electric invitation and architectural footer

**Observed:** Electric art band is 333px high. A left-aligned Heading, a short muted-white Body paragraph, and paired reversed Primary and Band secondary buttons occupy the content inset; Segmented signal art fills the right. Below, the footer uses 80px top and 20px bottom padding, four link columns, 48px separation before Monumental mark silhouette, and a final legal row. Dark pages preserve this structure while reversing the surrounding canvas.

**Transfer:** Use a short direct invitation and the new product's monumental mark. Preserve both the saturated art moment and the large low-contrast brand anchor without tying them to a fixed section count.

**Text style:** `heading` — baseSans 400 · 28px/36px · tracking -0.025em

## Page flow

**Storyline:** promise → trust and quantified proof → capability explanation → concrete examples or implementation help → vivid invitation → architectural brand ending

### Broad platform introduction

1. **Promise** — Centered large headline in a white digital clearing.
2. **Trust** — Monochrome partner strip and compact capability routes.
3. **Quantified proof** — Centered neutral metrics band.
4. **Capability chapters** — Two-tone introductory statement and paired instrument diagrams.
5. **Examples** — Overflowing editorial carousel.
6. **Closing call** — Electric invitation followed by link columns, monumental mark and legal row.

**Transfer:** Use this as the default broad marketing narrative, adapting the number and order of explanatory chapters.

### Focused platform capability introduction

1. **Promise** — Centered smaller product headline and blue category label.
2. **Quantified proof** — Four standalone figures in a wash band.
3. **Capability chapters** — Compact trio followed by paired illustrated modules.
4. **Conversion reinforcement** — Neutral atmospheric invitation between chapters.
5. **Social proof** — Stacked wide frames divided into paired customer stories.
6. **Closing call** — Electric band and full architectural footer.

**Transfer:** Suitable for a product with multiple integration paths and strong customer proof.

### Explain an operational product in depth

1. **Promise and demonstration** — Left-hand headline beside a live activity panel.
2. **Trust and proof** — Partner strip and four-value band.
3. **Use cases** — Numbered asymmetric card grid with one tall card and four smaller cards.
4. **Coverage demonstration** — Large rounded panel with list rail and bar-built globe.
5. **Capability assurance** — Hairline benefit rows and numbered process.
6. **Objection handling** — Specialized feature trio, pale cross-link panel and split FAQ.
7. **Closing call** — Electric band and full architectural footer.

**Transfer:** Use where buyers need workflow clarity, operating detail and reassurance before conversion.

### Developer adoption and onboarding

1. **Promise and demonstration** — Charcoal split hero with terminal output.
2. **Capability chapters** — One wide illustrated card above two smaller cards.
3. **Implementation help** — Narrow numbered setup sequence with tool choices and prompt controls.
4. **Ecosystem proof** — Colorful overflow tile carousel and metric strip.
5. **Tools** — Paired saturated scanline cards.
6. **Technical assurance** — One illustrated interoperability card beside two stacked protocol explanations.
7. **Closing call** — Electric invitation and charcoal architectural footer.

**Transfer:** Reserve this darker, more hands-on variant for products with an actionable technical setup.

## Writing

Direct, confident and infrastructural. Big claims are stated calmly, then made concrete through capabilities, operating details and proof rather than emotional persuasion.

**Do not copy:** Do not reuse Base or Coinbase names, marks, proprietary illustrations, partner endorsements, financial figures, claims or source customer stories. Source quotations below illustrate syntax only; replace them with true statements about the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use imperative verbs for headings and actions, 'your' for reader benefits, and the product name for factual explanations. First-person language is rare outside instructional help.
- **Rhythm:** Headlines are generally 4–9 words, support is one compact sentence, and descriptions usually fit two or three short lines. Full stops are common in promises; no exclamation-driven selling.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a category or unite a valuable capability with an operating advantage. | 5–9 words | “The blockchain for global finance.”<br>“Institutional liquidity meets sub-cent settlement.” |
| Chapter heading | Begin with a concrete verb and state the outcome. | 4–10 words | “Unlock new revenue streams.”<br>“Build for the payment flow you need” |
| Supporting line | Explain the mechanism or trust basis without restating the headline. | 10–22 words | “Built by Coinbase, trusted by leading institutions, and open to all.” |
| Action | Short verb plus destination or task. | 2–3 words | “Explore Ecosystem”<br>“Request Demo”<br>“Copy Prompt” |
| Closing invitation | Simple invitation to begin, followed by a terse operating promise. | 4–6 words | “Start building on [Brand].” |

**Words and phrasing to use:** build; enable; access; connect; open; global; trusted; always on; supported; control

**Avoid:** revolutionary; game-changing; magical; unlimited possibilities; effortless everything

**Rules:**

- Pair each broad claim with a practical mechanism or verifiable proof nearby.
- Keep benefit titles concrete; let the description explain how.
- In instructional sections, give an exact task and expected result instead of brand rhetoric.
- Use operating qualifiers where appropriate rather than implying every workflow works identically.

## Do's and Don'ts

### Do

- Keep the principal promise at weight 400 with -0.04em tracking.
- Preserve the 1200px border-box container and 32px desktop side insets.
- Use 12px corners and #efefef hairlines for ordinary cards.
- Separate major capability chapters with 80px top and bottom padding.
- Pair 48px capsules with short regular-weight labels.
- Give proof captions a 12px uppercase monospace treatment.
- Include segmented signal material and a content-width monumental brand silhouette.
- Keep blue concentrated in labels, actions, diagram modules and the saturated art band.

### Don't

- Do not make regular chapter headings compete with the opening: they are 28px, not another 72px display.
- Do not apply the terminal halo to ordinary white cards; their shadow is none.
- Do not replace pill actions with 12px-radius rectangles.
- Do not distribute lime or yellow across the default light page; those belong to scoped developer showcases.
- Do not put 20px Lead tracking on body paragraphs; use the untracked text family.
- Do not fill every technical diagram frame edge to edge; preserve internal white margins.
- Do not make the footer mark high-contrast blue; its default fill is low-contrast gray.
- Do not convert the horizontally overflowing story track into a cramped four-column desktop grid.

## Motion and responsive

### Motion

**Observed:**

- Actions declare background-color, border-color, color and transform transitions of 0.15s cubic-bezier(0.4,0,0.2,1).
- Chevron opacity transitions use 0.2s cubic-bezier(0.4,0,0.2,1).
- Horizontal marquees declare 45s linear infinite movement; status pings declare 1s cubic-bezier(0,0,0.2,1) infinite animation.
- Developer ecosystem tiles declare transform 0.3s cubic-bezier(0,0,0.2,1).

**Transfer:**

- Use the short declared color transitions for capsules and hairline cards.
- Keep ambient signal movement behind readable copy and preserve horizontal carousel interaction separately from page scroll.

**Unknown:**

- Exact ambient-art timelines and scroll-trigger choreography are not established.

### Responsive

**Observed:**

- CSS declares width breakpoints including 640px, 768px, 1024px and 1280px.
- Component classes declare single-column cards changing to three columns at the medium breakpoint; split heroes and four-column footers likewise switch at medium widths.
- Focused product display classes declare 36px/40px, then 40px/48px, then 56px/64px type.

**Transfer:**

- On narrow layouts, stack the split demonstration below the promise and keep the signal field at the periphery.
- Keep overflow discovery tracks scrollable rather than squeezing all cards into the window.
- Reduce container side insets to 24px for compact layouts.

**Unknown:**

- Mobile composition and the final responsive override for the default 72px opening are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
