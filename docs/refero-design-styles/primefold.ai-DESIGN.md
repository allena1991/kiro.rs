# Primefold — cinematic questions, tangible answers

## Overview

A cinematic business-software style that balances dark, lived-in photography with bright editorial space. Warm black, chalk white and pale stone carry the page, while sea-green and copper light give technical scenes an atmospheric character. Regular-weight grotesk headlines, small practical interface text and large photographic proof panels suit complex products that need to feel useful rather than futuristic.

### Essentials

- Headlines speak at conversational volume despite their size: regular-weight Stack Sans Headline at 64px/72px with 0.02em tracking in the opening, and 48px/56px with the same tracking in sections.
- The opening is an inhabited scene, not a floating app window: a full-bleed 900px photographic stage, left-aligned white copy in a roughly 650px column, paired pill actions and four 215×102px selector tiles along the bottom.
- Actions are small, rounded and tactile: white primary pills and translucent white secondary pills, 43px tall in the opening with 10px 14px padding; ordinary actions use 40px height and 8px 14px padding.
- Color lives in light and media rather than large painted bands: white and #faf9f8 dominate the reading canvas; #1a1814 and #0b0b0c back dark scenes; teal and copper are confined to soft light, thin connectors, tiny badges and checkmarks.
- Technical complexity becomes a staged diagram: a 1280×520px dark panel with 16px corners, thin glowing connections and warm/cool edge light. Use a simplified input → processing → useful result diagram when full product media is unavailable.
- The visual signature continues beyond the content: include a black-backed teal-and-copper light panel with centered white closing copy, then an orderly white footer and an enormous dark wordmark spanning the 1280px content width. Use the new product's own typeset name if no wordmark artwork exists.
- Proof feels editorial rather than dashboard-like: rounded full-bleed photographs carry large white metrics, explanatory sentences and small attribution; 16px grid gaps and 40px inner padding keep the results substantial without visual clutter.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint edge light | `#3fd1bc` | `--color-mint-light` | accent | Cool luminous edges at 50% alpha within technical media. |
| Peach edge light | `#f99d72` | `--color-peach-light` | accent | Warm luminous edges at 55% alpha within technical media. |
| Sea green | `#27a896` | `--color-teal` | accent | Thin active rules, technical light and inclusion checkmarks. |
| Soft copper | `#ca7b57` | `--color-copper` | accent | Warm half of the atmospheric light pairing and small categorical marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Main reading canvas, white cards and inverse text; also the source of translucent glass layers. |
| Lightless black | `#000000` | `--color-black` | background, text | Deep photographic overlays and the dark gaps between colored light forms. |
| Technical black | `#0b0b0c` | `--color-stage` | background, surface | Dark diagram stage. |
| Warm charcoal | `#1a1814` | `--color-ink` | text, background, action | Brand-dark panels, strong text and dark action pills. |
| Graphite | `#212121` | `--color-heading` | text, link | Section headings, factual labels and hovered footer links. |
| Warm reading gray | `#54524e` | `--color-warm-body` | text | Secondary product descriptions, table labels and pricing support copy. |
| Reading gray | `#545454` | `--color-body` | text, link | Ordinary body copy and footer navigation. |
| Label gray | `#616161` | `--color-muted` | text | Section labels and dotted markers. |
| Warm silver | `#cbc7c0` | `--color-inverse-muted` | text | Support text on warm-dark backgrounds. |
| Fine edge | `#e2e2e2` | `--color-rule` | border | Footer rules and fine outer outlines; card edge shadows additionally use black at 8% alpha. |
| Warm chalk | `#faf9f8` | `--color-band` | background, surface | Long pale product chapters, outer pricing cards and FAQ bands. |
| Soft porcelain | `#fafaf9` | `--color-fact-surface` | surface | Small factual cards and segmented control tracks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Mint inclusion wash | `#cbeae6` | `--color-check-wash` | surface | Visible tint of #27a896 at 24% alpha over white behind pricing checks. |
| product demonstrations | Demo panel | `#161513` | `--color-demo-panel` | surface | Warm near-black interior of the staged product interface. |
| product demonstrations | Demo raised surface | `#282622` | `--color-demo-raised` | surface | Raised inset surfaces inside product illustrations. |

## Typography

- **Stack Sans Headline** — All marketing headlines, section headings and small display titles. Open, rounded grotesk with single-storey forms and a relaxed regular weight. If unavailable, use **DM Sans**. Use weight 400 and preserve the positive tracking of large headings. Font stack: "Stack Sans Headline", "DM Sans", sans-serif.
- **Inter** — Paragraphs, labels, navigation, buttons and tables. Practical neutral sans with compact, legible small text. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Inter", sans-serif.
- **ABC Favorit Trial** — Oversized outcome metrics and product-family titles. Plain, slightly idiosyncratic grotesk; light book weight for large numerals. If unavailable, use **Inter**. Use weight 350 with -0.03em tracking for metrics. Font stack: "ABC Favorit Trial", "Inter", sans-serif.
- **monospace** — Small dotted section markers, not ordinary text. Braille-like dot arrangements acting as tiny technical punctuation. Font stack: "monospace", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| outcome-metric | ABC Favorit Trial | 350 | 80px | 0.01 | -0.03em, features "ss11" | Individually positioned metric glyphs in photographic proof artwork, not flowing paragraph text. |
| display | Stack Sans Headline | 400 | 64px | 1.125 | 0.02em, features "ss04" | White opening statement; typically two lines. |
| heading | Stack Sans Headline | 400 | 48px | 56px | 0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11", "ss04", "ss11" | Main section headings, photographic quotations and the closing invitation. |
| outcome-explanation | Stack Sans Headline | 400 | 32px | 1.25 | normal, features "ss04", "ss11" | Large explanatory sentence below a photographic metric. |
| title | Stack Sans Headline | 400 | 20px | 1.4 | normal, features "ss04", "ss11" | Photographic card titles, plan names and accordion questions. |
| hero-support | Inter | 400 | 18px | 24px | normal | Short supporting copy on the photographic opening. |
| body-strong | Inter | 500 | 16px | 1.5 | -0.01em | Navigation, ordinary buttons, factual card headings and table entries. |
| hero-action | Inter | 500 | 16px | 1.43 | -0.01em | Opening white and translucent action pills. |
| marker | monospace | 400 | 16px | 1.3 | normal | Tiny dotted prefix beside an eyebrow label. |
| body | Inter | 400 | 14px | 20px | -0.006em | Default paragraphs, card descriptions and footer links. |
| label | Inter | 500 | 14px | 20px | -0.006em | Eyebrow text, compact labels and attribution. |
| caption | Inter | 400 | 12px | 16px | normal | Small attribution, trust notes and footer utility links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| informational, company and pricing pages | interior-display | Stack Sans Headline | 400 | 56px | 1.2 | 0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11", "ss04", "ss11" | Smaller opening headline for focused informational pages. |
| informational, company and pricing pages | interior-support | Inter | 400 | 16px | 1.5 | -0.01em | Opening support copy on focused informational pages. |

**Notes:**

- Large headings keep positive 0.02em tracking rather than the tightly compressed tracking common in software marketing. Small Inter copy uses slight negative tracking.
- Keep headline weight 400; contrast comes from scale and photographic backing, not boldness. Most body text is only 14px.
- The outcome metric is a positioned lettering treatment: give the metric its own tall block and position the glyphs independently. Its near-zero line box must not control the height of a normal text paragraph.
- The monumental closing wordmark is artwork sized to the container, not an additional heading level.

## Layout

**Density:** Airy section structure with compact text and controls: large chapter breaks surround small, closely grouped labels and descriptions.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight title-to-copy and label-to-icon gaps. |
| 10px | Factual card interior group gaps. |
| 12px | FAQ row gaps and stacked short links. |
| 16px | Eyebrow-to-heading and heading-to-support spacing; product-card grid gaps. |
| 20px | Support-to-action spacing and minimum container side padding. |
| 24px | Factual card padding and general card-grid gaps. |
| 32px | Pricing card padding and photographic role-card text inset. |
| 40px | Outcome-card inner padding. |
| 56px | Heading-group to main content separation. |
| 64px | Footer top padding and wide footer column spacing. |
| 88px | Focused information-section top or bottom breathing room. |
| 120px | Major marketing chapter top padding and generous section endings. |
| 156px | Opening copy offset below the top of the page. |

### Containers and grids

- **main-container**: max width 1280px · side padding 20px. Centered content with 80px visible gutters at 1440px; aligns headings, stages, cards and footer.
- **outer-wrapper**: max width 1320px · side padding 20px. Wrapper including the content's side padding; also establishes navigation width.
- **opening-copy**: max width 650px. Left-hand headline and short supporting copy over the full-bleed scene.
- **centered-copy**: max width 620px. Centered closing invitation and compact section leads.
- **product-grid**: 3 columns · gap 16px. Three equally wide product cards, about 416px each.
- **fact-grid**: 4 columns · gap 24px. Four roughly 302px factual cards; a three-column variant uses roughly 411px cards.
- **trust-split**: 2 columns · gap 56px. Two roughly 612px chapters: textual explanation with vertical active rule on the left, pale technical diagram on the right.
- **proof-grid**: 2 columns · gap 16px. Alternating narrow and wide photographic outcome tiles, roughly 500px and 764px wide; reverse the proportions on the next row.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| selector-tiles | 8px |
| fact-and-role-cards | 12px |
| product-and-proof-panels | 16px |
| major-media-and-closing-panel | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| hairline-card | `rgba(0, 0, 0, 0.08) 0px 0px 0px 1px` | Thin card definition without a conventional drop shadow. |
| soft-panel | `rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(36, 36, 36, 0.04) 0px 1px 2px 0px` | Raised white panels, small fact cards and large closing panels. |
| button-edge | `rgba(38, 57, 90, 0.16) 0px 0px 0px 1px, rgba(38, 57, 91, 0.1) 0px 1px 1px 0px` | Subtle blue-gray tactile outline on pills. |

### Surfaces

#### Reading canvas · level 0

**Use:** Default background for new marketing pages.

**CSS:** `background: #ffffff; color: #212121`

**Observed:** Bright open reading space alternates with media-rich dark panels.

**Transfer:** Let media provide contrast rather than tinting every section.

#### Chalk chapter · level 0

**Use:** Grouped product explanations and FAQs.

**CSS:** `background: #faf9f8`

**Observed:** A continuous pale band can contain multiple chapters; its top corners use 16px rounding.

**Transfer:** Group related chapters into a single pale field.

#### White panel · level 1

**Use:** Cards and framed editorial content.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(36, 36, 36, 0.04) 0px 1px 2px 0px`

**Transfer:** Keep the edge almost imperceptible; hierarchy comes from contents and framing.

#### Technical stage · level 1

**Use:** Large explanatory product diagram.

**CSS:** `background: #0b0b0c; border-radius: 16px; overflow: hidden`

**Observed:** Wide landscape panel with teal light below the left edge and copper light above the right; readable UI sits in front.

**Transfer:** Use the Atmospheric light treatment behind a simplified working diagram.

#### Atmospheric closing panel · level 1

**Use:** Signature invitation panel.

**CSS:** `background: #1a1814; border-radius: 24px; overflow: hidden; padding: 82px 20px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(36, 36, 36, 0.04) 0px 1px 2px 0px`

**Observed:** Colored, out-of-focus light sweeps sit between the dark backing and centered white text.

**Transfer:** Keep the center readable and the corners deep black; match the soft glow rather than relying on exact gradient stops.

#### Frosted statistics · level 1

**Only for:** company pages

**Use:** Compact facts over a city photograph.

**CSS:** `background: rgba(120, 120, 120, 0.24); border-radius: 16px; backdrop-filter: blur(5px); padding: 40px 41px; box-shadow: rgba(255, 255, 255, 0.18) 0px 0px 0px 1px, rgba(0, 0, 0, 0.24) 0px 0px 0px 2px, rgba(0, 0, 0, 0.12) 0px 2px 2px 0px`

**Observed:** Four translucent 308×216px fact panes across the lower hero, with a muted label above a 48px figure.

**Transfer:** Use a small number of verifiable organizational facts, not decorative counters.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; height: 72px; z-index: 8; width: 100%`

**Text style:** `body-strong` — Inter 500 · 16px/1.5 · tracking -0.01em

**Observed:** Logo left; text navigation and small down chevrons across the right, followed by sign-in and conversion pills. Transparent with white text over dark openings; after scrolling, a centered translucent white bar uses 5px backdrop blur and rounded corners with dark text. Pricing starts with a white header.

**Transfer:** Keep the menu sparse and the two utility actions compact.

### Primary button

**Use:** Main action on dark photography and closing panels.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #ffffff; color: #1a1814; border-radius: 9999px; padding: 10px 14px; height: 43px; box-shadow: rgba(38, 57, 90, 0.16) 0px 0px 0px 1px, rgba(38, 57, 91, 0.1) 0px 1px 1px 0px`

**Text style:** `hero-action` — Inter 500 · 16px/1.43 · tracking -0.01em

**Observed:** Text-only pill paired with a translucent action. Ordinary placements use 40px height, 8px 14px padding and body-strong text. On pale pricing surfaces the emphasized action inverts to warm charcoal with light text.

**States:** Declared: hover on ancestor changes box-shadow to rgba(38, 57, 90, 0.16) 0px 0px 0px 1px, rgba(38, 57, 91, 0.15) 0px 5px 5px 0px; focus-visible uses a white 3px solid outline with 2px outline offset.

### Glass button

**Use:** Secondary action over dark photographic media.

**CSS:** `background: rgba(255, 255, 255, 0.24); color: #ffffff; border-radius: 9999px; padding: 10px 14px; height: 43px; backdrop-filter: blur(11.6px); box-shadow: rgba(38, 57, 90, 0.16) 0px 0px 0px 1px, rgba(38, 57, 91, 0.1) 0px 1px 1px 0px`

**Text style:** `hero-action` — Inter 500 · 16px/1.43 · tracking -0.01em

**Observed:** Placed beside the solid white action, with quieter contrast but the same silhouette.

**States:** Declared: hover on ancestor changes box-shadow to rgba(38, 57, 90, 0.16) 0px 0px 0px 1px, rgba(38, 57, 91, 0.15) 0px 5px 5px 0px; focus-visible uses a white 3px solid outline with 2px outline offset.

### Hero selector tile

**Use:** Switch between product perspectives within the opening scene.

**CSS:** `display: flex; flex-direction: column; gap: 16px; width: 215px; height: 102px; padding: 20px; background: rgba(255, 255, 255, 0.12); border: 1px solid rgba(255, 255, 255, 0.16); border-radius: 8px; backdrop-filter: blur(3.5px)`

**Text style:** `body-strong` — Inter 500 · 16px/1.5 · tracking -0.01em

**Observed:** Small mark above the label; a row of four rests near the bottom of the full-screen image. The selected tile is opaque white with dark lettering and a fine progress line at its bottom.

**Transfer:** Name product views or audience modes, not arbitrary feature bullets.

### Product card

**Use:** Explain a small family of related offerings.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 18px; padding: 2px; width: 416px; height: 560px`

**Text style:** `title` — Stack Sans Headline 400 · 20px/1.4

**Observed:** A slim label strip with a colored square mark precedes a large warm-black media area; a white lower caption block names and explains the offering. Inner panels use 16px corners. One variant uses a small icon constellation rather than a photograph.

**Transfer:** Preserve the dark stage and white caption structure across all cards, while varying each media subject.

### Photographic role card

**Use:** Connect product value to a recognizable person or work context.

**CSS:** `width: 465px; height: 488px; border-radius: 12px; overflow: hidden; display: flex; flex-direction: column; justify-content: flex-end; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px`

**Text style:** `title` — Stack Sans Headline 400 · 20px/1.4

**Observed:** Full-bleed human photograph, black bottom gradient, white title and compact supporting line, sometimes followed by a small translucent arrow pill. The text group is inset 32px. A horizontal rail deliberately shows partial neighboring cards.

**Transfer:** Choose distinct real work scenes and keep faces unobscured by copy.

### Fact card

**Use:** Short factual reassurance or principles.

**CSS:** `background: #fafaf9; border-radius: 12px; padding: 24px; display: flex; flex-direction: column; gap: 10px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px, rgba(36, 36, 36, 0.04) 0px 1px 2px 0px`

**Text style:** `body-strong` — Inter 500 · 16px/1.5 · tracking -0.01em

**Observed:** Small dark line icon above a medium-weight factual heading, then body text. Three- and four-column versions share the same treatment; heights follow the copy.

**Transfer:** One claim per card with a plain explanation, not an embellished badge wall.

### Newsletter capsule

**Use:** Small footer subscription form.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #ffffff; width: 320px; height: 48px; border-radius: 9999px; padding: 6px 6px 6px 16px`

**Text style:** `body` — Inter 400 · 14px/20px · tracking -0.006em

**Observed:** A quiet email field shares one outlined capsule with a dark 100×36px Subscribe button. Button lettering is 13px/16px, medium weight. The form sits under a short two-part newsletter invitation.

**Transfer:** Keep subscription subordinate to the page's main conversion.

### Footer

**Use:** Navigation and monumental brand ending.

**CSS:** `background: #ffffff; padding: 64px 20px 0px; border-radius: 0px 0px 24px 24px; box-shadow: #e2e2e2 0px 0px 0px 1px`

**Text style:** `body` — Inter 400 · 14px/20px · tracking -0.006em

**Observed:** A 320px brand-and-newsletter column sits left of four compact link columns. Utility and trust rows are separated by fine rules; social icons align with utility links. Beneath the rounded white panel, a huge dark wordmark fills the content width and meets the bottom edge.

**States:** Declared: hover on footer links changes text to #212121 and keeps text-decoration-line none.

**Transfer:** Use short category headings and restrained gray text links. The wordmark must be visibly monumental, even when built as plain typeset lettering.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchase options.

**CSS:** `background: #faf9f8; border-radius: 16px; padding: 32px; display: flex; flex-direction: column; gap: 24px; width: 416px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px`

**Text style:** `title` — Stack Sans Headline 400 · 20px/1.4

**Observed:** Plan name and small badge, brief description, 48px price or availability phrase, full-width pill action, divider, then checked features. The central emphasized card is white with a dark action; outer cards are chalk with white actions. Checks are 16px teal marks on 20px mint circles; feature rows have 12px gaps.

**Transfer:** Emphasize a plan by inversion, not a saturated background or giant ribbon.

### Comparison row

**Only for:** pricing pages

**Use:** Dense feature comparison beneath the plan cards.

**CSS:** `height: 72px; max-width: 1280px; background: #ffffff; display: grid; grid-template-columns: 2fr 1fr 1fr 1fr`

**Text style:** `body-strong` — Inter 500 · 16px/1.5 · tracking -0.01em

**Observed:** Wide left feature column and three centered plan values; fine horizontal rules instead of vertical boxing. Category headings use title text. A persistent comparison header repeats the plan names and actions; included features use mint checks, exclusions use muted crosses, future availability uses short quarter labels.

**Transfer:** Keep statements, exclusions and future availability visibly distinct.

### FAQ row

**Only for:** pricing and objection-handling sections

**Use:** Resolve one practical question at a time.

**CSS:** `background: #ffffff; border-radius: 12px; padding: 18px 24px; box-shadow: rgba(0, 0, 0, 0.08) 0px 0px 0px 1px`

**Text style:** `title` — Stack Sans Headline 400 · 20px/1.4

**Observed:** Question left, fine plus or minus right. Closed rows are 76px tall; the open row expands to show body text and uses 24px bottom padding. Rows stack 12px apart on a chalk band.

**Transfer:** Use actual buying questions and plain, complete answers.

## Imagery and graphics

### Inhabited business photography

**Use:** Opening scene, role rail, customer quotation and outcome panels.

**Observed:** Full-bleed photographs of people in a meeting room, stores, offices and industrial settings alternate with architectural skylines. Light is directional, often dusk-like; teal interiors and warm sunlight are subdued by deep black overlays. Images are the whole frame behind white text, not small decorative thumbnails.

**Transfer:** Use an authentic environment in which the new product matters. If bespoke photography is unavailable, use one strong workplace or architectural photograph with clean text space and a dark 108deg left-to-right overlay; preserve warm/cool lighting rather than adding a blue technology filter.

### Atmospheric light

**Use:** Signature dark closing panel and technical media backing.

**Observed:** Large defocused ribbons of green-turquoise and copper sweep diagonally through near-black space. Their blurred edges overlap into soft smoky gradients; there is no crisp geometric mesh or star field.

**Transfer:** Recreate the light with layered CSS or SVG even without original artwork. Keep bright areas away from small copy and preserve deep black negative space.

**Build:** Clip the scene to the panel radius. Start with a black field; place an elongated teal ellipse near the left edge, rotated about -35deg, and a copper ellipse near the upper center/right, rotated about -25deg. Add a smaller teal glow below center. Blur the light forms by roughly 40–80px at a 1280px panel width and vary opacity around 0.3–0.7. Overlay a dark translucent scrim behind text. For edge highlights, use a 135deg gradient from rgba(249,157,114,0.55) through rgba(255,255,255,0.08) at 38% and 62%, to rgba(63,209,188,0.5); inset a dark panel by 1px.

### Connected product theater

**Use:** Explain the transformation from inputs into an actionable result.

**Observed:** A wide landscape stage holds a vertical stack of small input pills at left, a warm-black conversational processing panel in the middle and a result area to the right. Fine teal lines bend through rounded corners into the center; a copper line leads out. Small UI labels remain subordinate to the large section headline.

**Transfer:** Use a few representative inputs, one concise user request and one fully designed result. A diagram made with HTML panels and SVG connectors is sufficient; do not reproduce a whole application.

**Build:** Within a 1280×520px Technical stage, reserve roughly one quarter for input pills, one third for the request panel and the remainder for the result. Draw 1px teal connector paths with orthogonal bends and rounded joins. Use 18px panel corners, a 1px warm/cool gradient rim and a 24px 60px dark shadow. Put Atmospheric light behind the diagram, not over its text.

### Photographic outcome mosaic

**Use:** Large, attributable proof.

**Observed:** Asymmetric paired cards show real customer environments with dark bottom gradients. Logos sit near the upper left, white 80px metrics below, 32px explanatory sentences lower down and small attribution at the foot. Rows alternate narrow/wide proportions.

**Transfer:** Use verified proof appropriate to the new product. Without numeric results, make a concrete qualitative outcome the large text; retain the photographic framing and attribution.

### Monumental wordmark

**Use:** Signature visual ending below footer utilities.

**Observed:** A single dark brand name spans almost the full 1280px content width beneath the rounded white footer. The scale makes it read as artwork rather than a legal signature; its lower edge reaches the viewport boundary.

**Transfer:** Set the new product's own name in a broad simple grotesk or use its own wordmark, sized to span the available width.

**Build:** Create a 1280px-wide overflow-hidden art container, separated from the utility panel by about 32px. Place a dark SVG wordmark at width 100%, preserving its aspect ratio. Without an asset, fit a single-line regular grotesk name to the container and adjust font size to fill the width; keep the art block about 218px tall at desktop.

### Layered trust diagrams

**Only for:** trust and security explanations

**Use:** Make technical protection tangible.

**Observed:** The light variant puts two white file tiles above thin teal connectors leading to a central certification-style disc on a pale square backing. The dark opening variant places two symbols inside a tall capsule surrounded by many fine concentric racetrack outlines; tiny warm and teal edge reflections give depth.

**Transfer:** Replace certification symbolism with truthful technical concepts. Keep the layered outline construction rather than using a generic giant shield.

**Build:** For the dark variant, draw 6–8 concentric SVG rounded-rectangle outlines around a central 176px-wide capsule, increasing the outlines toward roughly 432×598px. Use 1px low-opacity white strokes and short teal/copper gradient arcs near the lower left. Stack two inset symbol plates inside. For the light variant, use thin teal paths joining white file tiles to a circular central node on a chalk panel.

### People portrait rail

**Only for:** company pages

**Use:** Introduce the people behind the product.

**Observed:** Square 240px portraits in a horizontally overflowing row, with 12px rounded corners and small names and roles below. Photography shares a dark office setting and greenish natural light; expressions are informal rather than corporate cut-outs.

**Transfer:** Keep a consistent real environment and framing across portraits. Use plain backgrounds if no shared location is available.

### Icons

**Observed:** Small functional symbols, usually 16–24px, dark on pale cards and white on dark media. Arrow controls use rounded 1.6–2px strokes; pricing inclusion symbols use a 16px teal check within a 20px pale mint circle. Tiny colored square monograms identify product families. Eyebrows use a dotted monospace marker, not a large icon.

**Transfer:** Choose simple thin outline symbols with consistent optical weight. Reserve filled marks and stronger colors for small product identifiers and status checks.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px full-height photograph fills the first screen: a meeting room and city view with people occupying the lower half and a teal wall at the right. Layers run from cover photograph to dark directional scrim, then left-aligned white copy and actions, with Navigation above and Hero selector tiles near the bottom. The display headline begins around 156px from the top and spans roughly half the page width in two lines; a short hero-support line sits below it, then paired Primary button and Glass button. The main object is the inhabited environment itself, not an isolated app image. All of the headline, support, actions and four bottom selectors fit within the first 900px; pale explanatory chapters begin below the fold.

**Transfer:** Use a compelling real setting and a concise two-part promise for a new landing page. Without custom media, a carefully art-directed workplace photo is enough. Focused information pages instead use interior-display: dark split text/diagram for technical reassurance, a white text-led opening above pricing, or a skyline with frosted fact panes for organizational storytelling.

**Avoid:** Do not replace this first impression with a centered white SaaS hero, a giant floating browser window or a headline that competes with faces.

**Text style:** `display` — Stack Sans Headline 400 · 64px/1.125 · tracking 0.02em

### Dotted chapter lead

**Observed:** Small dotted marker plus muted label, followed 16px later by a heading and another 16px later by body support. Main content follows after about 56px. Most headings align left within the main container; the product-family introduction is centered in a roughly 600px column.

**Transfer:** Use short thematic labels and a sentence-like heading; center only when introducing a compact collection.

**Text style:** `heading` — Stack Sans Headline 400 · 48px/56px · tracking 0.02em

### Dark transformation stage

**Observed:** A Dotted chapter lead sits on a Chalk chapter above a Technical stage. Connected product theater occupies the stage, with the main request visually larger than its input labels.

**Transfer:** Explain one meaningful workflow rather than several unrelated features.

### Product-family triptych

**Observed:** Centered Dotted chapter lead followed by three Product cards with 16px gaps. Their dark media areas align, while each carries a distinct miniature scene.

**Transfer:** Use this for a small family of offerings or three distinct product modes; keep captions brief.

### Quotation panorama

**Observed:** A broad photographic carousel with 24px corners, about 650px high, shows a large left-aligned white quotation, a small product identifier, an action and low-left attribution. Neighboring slides peek at the edges; white circular arrows sit at the sides and tiny dots at the bottom.

**Transfer:** Let an attributable user observation carry the section. Preserve the wide cinematic framing and quiet controls.

**Text style:** `heading` — Stack Sans Headline 400 · 48px/56px · tracking 0.02em

### Role rail

**Observed:** Left-aligned heading and small arrow controls precede a horizontal rail of Photographic role cards with 24px gaps. Partial cards beyond both edges imply continuation.

**Transfer:** Show different contexts of use through people and environments, not an identical icon for every audience.

### Split explanation with active rule

**Observed:** Heading and body copy sit at the upper left, followed by ample white space and three stacked explanations lower down. A thin pale vertical rule with a teal active segment runs beside the list. A pale square technical diagram fills the right half.

**Transfer:** Use for architecture, process or reliability; keep the diagram legible and give the active explanation a real visual counterpart.

### Proof mosaic

**Observed:** Dotted chapter lead followed by the Photographic outcome mosaic with alternating narrow and wide panels, 16px gaps, 16px corners and 40px text insets.

**Transfer:** Lead with concrete outcomes and explanations, using only proof that can be attributed.

### Focused fact grid

**Observed:** A Dotted chapter lead precedes a three- or four-column grid of Fact cards separated by 24px. Short headings and compact paragraphs keep the card heights close.

**Transfer:** Use for concise principles or factual assurances, not an exhaustive feature inventory.

### Atmospheric invitation

**Observed:** An Atmospheric closing panel spans 1280px, about 388px tall, with a centered heading in a 620px text column, 12px to supporting copy and 20px to a single white action. The glow is the visual attraction; the copy stays short.

**Transfer:** Use the invitation appropriate to the page's intent: a conversation, a trial, documentation or joining the team. Retain the signature light treatment.

**Text style:** `heading` — Stack Sans Headline 400 · 48px/56px · tracking 0.02em

### Footer and wordmark reveal

**Observed:** Footer follows the invitation with a left newsletter block and four right-hand link columns. Fine rules separate legal and trust rows. A rounded white lower edge ends the information panel; Monumental wordmark artwork extends below it.

**Transfer:** Keep the utility content practical and restrained so that the oversized name becomes the final visual statement.

### Purchase comparison

**Only for:** pricing pages

**Observed:** A white, left-led interior-display opening and paired actions precede product and billing pill selectors, then three Plan cards. A comparison table follows, with category headings and 72px Comparison rows under repeated plan actions. A Fact card grid reinforces shared standards before the FAQ rows on a Chalk chapter.

**Transfer:** Separate the promise, plan choice, detailed comparison and objections into readable density levels; carry the emphasized plan's dark action through the table.

## Page flow

**Storyline:** Promise → tangible mechanism → contexts and proof → practical reassurance → focused invitation → utility navigation and monumental brand ending.

### Broad product or platform landing page

1. **Promise** — Cinematic opening with switchable product perspectives.
2. **Product demonstration** — A pale chapter with a dark connected transformation stage.
3. **Capability chapters** — Product-family cards and a photographic role rail.
4. **Social proof** — A panoramic customer quotation and asymmetric outcome mosaic.
5. **Reassurance** — Split explanation with a thin active rule and pale diagram.
6. **Closing call** — Atmospheric invitation, compact footer and oversized wordmark.

**Transfer:** Use the media-led opening as the default. Reorder proof and explanation around the new product's actual buying questions.

### Technical reassurance or trust-focused page

1. **Promise** — Warm-dark split opening: 56px text left and concentric capsule diagram right.
2. **Reassurance** — Three concise Fact cards.
3. **Capability explanation** — Two wide dark atmospheric panels with white explanatory text near the bottom.
4. **Closing call** — Documentation or contact invitation, followed by the shared footer and huge wordmark.

**Transfer:** Start with a concrete principle and substantiate it in plain language; use only legitimate technical assurances.

### Organization and people page

1. **Purpose** — A skyline-backed opening with a concise purpose statement and two actions.
2. **Quantified context** — Four frosted fact panes across the lower hero.
3. **Principles** — Small pale factual cards.
4. **People** — An overflowing rail of square environmental portraits with names and roles.
5. **Closing call** — Recruiting-oriented atmospheric invitation, shared footer and oversized wordmark.

**Transfer:** Use organizational facts, principles and genuine people to support the purpose instead of turning the page into another feature list.

### Pricing and purchase evaluation

1. **Promise** — White opening with a short two-sentence headline and concise access explanation.
2. **Pricing** — Product and billing selectors above three restrained plan cards.
3. **Detailed comparison** — Category-led feature matrix with repeated plan headers and pill actions.
4. **Reassurance** — Four pale cards clarifying standards common to every plan.
5. **Objection handling** — Practical questions in white accordion rows on a chalk band.
6. **Closing call** — Atmospheric conversation invitation, shared footer and large wordmark.

**Transfer:** Let pricing be the densest page type while retaining the same headline, edge, button and closing vocabulary.

## Writing

Direct, assured and grounded in work. The language presents intelligence as something the reader can question and use, with warmth coming from plain speech rather than jokes or hype.

**Do not copy:** Do not reuse Primefold or product names, logos, customer identities, quotations, outcome numbers, dates, locations, compliance assertions or pricing promises. Replace them with the new product's own verified content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your; use we for operational commitments. Refer to the product by name sparingly, with action-led sentences carrying most explanations.
- **Rhythm:** Short complete sentences and paired clauses. Headlines often contain two small statements; support lines explain a concrete mechanism or benefit. Very little exclamation, jargon or ornamental metaphor.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A compact promise followed by a condition or reinforcing statement. | 5–12 words | “Everything answers. If you simply ask.”<br>“Start free. Stay for the answers.” |
| Chapter headline | A plain result or principle, often in two balanced clauses. | 4–9 words | “Real impact. Real outcomes.”<br>“Security is the foundation. Not a feature.” |
| Support line | Explain what happens next in the reader's work, without abstract superlatives. | One or two concise sentences | “Bring a real business question. Get the answer you need to move forward.” |
| Action | Specific verb plus a simple object or time commitment. | 2–6 words | “Book a call”<br>“See open roles”<br>“Start free for 30 days” |
| Reassurance | A direct assurance followed by an explanation of the mechanism. | One short paragraph | “Every answer links back to the source it came from, and low-confidence results are flagged for review.” |
| Question | The practical question a buyer would ask aloud. | 6–14 words | “What happens when the trial ends?” |

**Words and phrasing to use:** ask; understand; act; your data; next move; built in; trace back; real; work; answer

**Avoid:** revolutionary; supercharge; unleash; next-generation; game-changing; magic; limitless

**Rules:**

- Pair an abstract promise with a concrete work result.
- Prefer a short active verb to a noun-heavy capability label.
- Explain limitations and future availability plainly rather than disguising them as benefits.
- Use attributed observations and substantiated results instead of unqualified superiority claims.
- Let headlines sound spoken; keep tiny labels factual and useful.

## Do's and Don'ts

### Do

- Keep the main reading width at 1280px with aligned section and footer edges.
- Use 64px/72px regular display text and 48px/56px regular section headings with 0.02em tracking.
- Preserve 14px/20px body text so the large heading-to-body contrast remains distinctive.
- Use 16px gaps for product and proof grids, 24px for factual grids.
- Stage dark diagrams and photographic proof inside 16px or 24px rounded frames.
- Use translucent white glass over photographs, with 5px navigation blur and 11.6px secondary-action blur.
- Give major chapters 88px or 120px breathing room while keeping card interiors compact.
- Carry the atmospheric teal/copper invitation and monumental wordmark through to the page ending.

### Don't

- Do not make the default canvas dark from top to bottom; dark scenes contrast with white and chalk reading chapters.
- Do not turn teal into a full-width solid marketing band; it belongs in light, connectors and small status marks.
- Do not set large headings in heavy 700-weight type or compress them with negative tracking.
- Do not enlarge ordinary action pills into 56px rectangles; the normal control height is 40px.
- Do not give every card a strong drop shadow; most edges are only a black 8% one-pixel ring.
- Do not put a browser chrome wrapper around every product illustration; the technical stage is a composed scene.
- Do not replace the people photography with glossy isolated 3D objects or a grid of generic colored icons.
- Do not end immediately after legal links; the huge brand-name artwork is part of the visual ending.

## Motion and responsive

### Motion

**Observed:**

- Opening action pills declare box-shadow 0.3s transitions.
- Carousel arrow controls declare transform 0.15s and scale 0.15s; active scale is 0.9.
- Carousel dots and arrow actions declare white 3px focus-visible outlines with 2px offsets.
- The opening includes product-view selectors and the quotation area includes slide arrows and progress dots.

**Transfer:**

- Use the declared shadow change for tactile pill feedback and the 0.9 pressed scale for carousel arrows.
- Keep the page's readable hierarchy intact without relying on animated glyph duplication or moving light.

**Unknown:**

- Slide autoplay interval, light animation timing, scroll-entry sequencing and exact easing assignments are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px.

**Transfer:**

- Below the wide layout, stack the split technical story and reduce multi-column grids while retaining the dark stage and pale reading canvas.
- On narrow screens, retain photographic emphasis but choose a subject position that leaves headline space; move the selector tiles into an accessible rail rather than shrinking their labels.
- Fit the final wordmark to the available width and preserve its artwork-like scale relative to utility text.
- For dense pricing comparisons, retain the feature-to-plan relationships in a horizontally scrollable comparison rather than squeezing text into illegible columns.

**Unknown:**

- Exact mobile typography, navigation behavior, grid counts and spacing at each breakpoint are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
