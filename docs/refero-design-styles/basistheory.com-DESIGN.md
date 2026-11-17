# Basis Theory — machined mint infrastructure

## Overview

A bright, technically assured style that makes invisible infrastructure feel like a tangible engineered object. White space and tightly packed grotesk headlines surround pale isometric assemblies, while charcoal chapters bring depth and weight. Mint and acid green act as illuminated signals rather than broad brand fills; small monospaced markings and softly raised panels keep the technical detail approachable.

### Essentials

- Headlines feel compressed rather than heavy: an 80px grotesk opening uses 0.8 line height and -0.04em tracking; section headings use 56px/1 with the same tight tracking.
- The opening pairs a compact left-hand promise with an oversized floating machine: a 1200px container holds a roughly half-width text column and a pale exploded isometric assembly that extends toward the right edge.
- Actions are soft rectangular keys, not pills: main buttons are 44px high with 16px corners, compact buttons are 36px high with 12px corners, and mint #94faf0 carries the principal action.
- Color behaves like an electronic indicator: most of the page remains white, pale gray or charcoal; mint and lime #bff660 are concentrated in buttons, 18px icon squares, 16×7px eyebrow markers and small parts of illustrations.
- Diagrams become physical hardware: thin-edged translucent plates, offset code panels, four-corner fasteners and soft shadows give abstract capabilities a constructed form. Include an engineered product scene and a machined proof treatment; use simple layered SVG plates and meaningful symbols when detailed product art is unavailable.
- Dark sections are textured rather than flat: charcoal #18181b and #27272a carry faint diagonal striations, grain and selective white text emphasis. A monumental 64px/0.9 two-tone closing statement inside a 32px-rounded dark panel is a recurring signature.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Illuminated mint | `#94faf0` | `--color-mint` | action, accent, surface | Primary conversion buttons, small markers, icon backing and controlled highlights within product illustrations. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#bff660` | `--color-lime` | action, accent, surface | Alternating small feature indicators and developer-oriented highlights; not a replacement for the default mint action. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, raised white panels and bright text on dark sections. Dark supporting copy uses white at 50%, 70% or 80% opacity according to emphasis. |
| Porcelain | `#fafafa` | `--color-pale` | surface, background | Feature cards and recessed trays inside raised proof panels. |
| Pale alloy | `#f4f4f5` | `--color-media` | surface | Light illustration backing and layered product panels. |
| Fine edge | `#f2f2f2` | `--color-rule` | border | Faint upper edges on light proof cards and separator details. |
| Silver fastener | `#eeeef0` | `--color-fastener` | surface, accent | Tiny recessed circular corner details on machined proof cards. |
| Zinc gray | `#71717a` | `--color-muted` | text, link | Support paragraphs, navigation and technical labels on light backgrounds. |
| Soft charcoal | `#3f3f46` | `--color-secondary-ink` | text | Eyebrow lettering and strongly emphasized secondary copy. |
| Graphite | `#27272a` | `--color-panel` | surface, action, background | Dark cards, code backing and small dark buttons. |
| Deep charcoal | `#18181b` | `--color-ink` | text, background | Primary heading and body ink; deepest marketing bands and closing panel. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| announcement bars | Lime wash | `#d4f796` | `--color-announcement` | background | Slim announcement strip above the navigation. |
| code demonstrations | Code gray | `#858591` | `--color-code-comment` | text | Subdued comments in dark code examples. |

## Typography

- **Neo Grotesk** — Display headings and prominent panel titles; bold cut for proof abbreviations. Compact neo-grotesk with broad rounded counters, closely packed lowercase and a medium visual weight. If unavailable, use **Inter Tight**. Use 500 for medium and 700 for bold; retain tight tracking and compressed leading. Font stack: "Neo Grotesk", "Inter Tight", Arial, sans-serif.
- **Inter** — Body, quotations, navigation, buttons and numerals. Matter-of-fact screen sans with a substantial medium body weight. OpenType features: "salt". Font stack: "Inter", Arial, sans-serif.
- **Kode Mono** — Small equipment-like section labels and proof captions. Compact technical monospace, usually semibold and uppercase. Font stack: "Kode Mono", ui-monospace, monospace.
- **Chivo Mono** (only for code demonstrations) — Code examples behind feature illustrations. Readable monospaced code with restrained syntax color. Font stack: "Chivo Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Neo Grotesk | 500 | 80px | 0.8 | -0.04em | Default marketing opening; wrap a concise outcome into a compact three-line block. |
| closing | Neo Grotesk | 500 | 64px | 0.9 | -0.03em | Large closing promise, with a muted first phrase and a bright white conclusion. |
| heading | Neo Grotesk | 500 | 56px | 1 | -0.04em | Major capability or trust section heading; also the large title in a dark developer panel. |
| feature-heading | Neo Grotesk | 500 | 32px | 1.2 | -0.03em | Editorial feature chapters beside layered product art. |
| quote | Inter | 500 | 32px | 1.3 | -0.04em, features "salt", "ss01", "ss03", "ss04", "tnum" | Centered testimonial statements on a dark band, with selected words in full white. |
| proof-title | Neo Grotesk | 700 | 32px | 1 | -0.01em | Short uppercase proof abbreviations beneath colored emblems. |
| body | Inter | 500 | 18px | 1.5 | -0.0056em, features "salt" | Hero support and major section introductions. |
| action | Inter | 600 | 16px | 1.2 | -0.02em, features "salt" | All filled and glass button labels. |
| proof-caption | Kode Mono | 600 | 16px | 1 | normal, uppercase | Compact classification or status below the proof title. |
| body-small | Inter | 500 | 14px | 1.5 | -0.014em, features "salt" | Card explanations and denser technical prose. |
| benefit | Inter | 500 | 14px | 1.4 | -0.007em, features "salt" | Short benefit lines beside small icon squares. |
| navigation | Inter | 500 | 14px | 1 | normal, features "cv10", "cv11", "cv12", "cv13", "salt", "ss01", "ss02", "ss03", "ss04" | Compact top navigation. |
| footer-link | Inter | 500 | 14px | 16px | -0.01em | Footer link columns and their muted headings. |
| trust-eyebrow | Kode Mono | 600 | 14px | 0.9 | 0.02em, uppercase | Centered technical strapline above a large trust heading. |
| eyebrow | Kode Mono | 600 | 12px | 1 | 0.02em, uppercase | Technical chapter markings, paired with a tiny colored capsule. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| secondary product, comparison and pricing pages | secondary-opening | Neo Grotesk | 500 | 56px | 0.9 | -0.04em | Compact product or use-case openings; centered in a 600px column for comparison and pricing introductions. |
| quantified proof panels | stat | Inter | 500 | 55px | 1 | -0.05em | Large centered figures within circular gauges. |
| process explanations | diagram-heading | Neo Grotesk | 500 | 48px | 1 | -0.04em | Centered introduction to a dark process diagram. |
| solution pages | product-section-heading | Neo Grotesk | 500 | 48px | 0.9 | -0.04em | Centered multi-line introduction above solution details. |
| pricing pages | price | Neo Grotesk | 500 | 40px | 1.2 | -0.05em | Plan price or short sales-led alternative. |
| photographic proof panels | photo-quote | Inter | 500 | 28px | 1.2 | -0.03em, features "salt", "ss01", "ss03", "ss04", "tnum" | Left-aligned quotation or capability statement over darkened photography. |
| benefit card grids | card-heading | Inter | 600 | 18px | 1.1 | -0.022em, features "salt" | Short benefit-card titles. |
| code demonstrations | code | Chivo Mono | 400 | 14px | 1.5 | normal | Code in a dark backing panel. |
| quantified proof panels | stat-caption | Inter | 500 | 13px | 1 | normal | Centered explanation below a gauge. |
| quantified proof panels | stat-label | Kode Mono | 600 | 11px | 1.1 | normal, uppercase | Tiny multi-line measurement label within a gauge. |

**Notes:**

- Keep medium grotesk headings visually light enough for their tightly packed counters; reserve the bold cut for short proof labels.
- The largest heading has unusually tight 0.8 leading. Most section headings relax to 1 or 1.2, while closing and secondary opening statements retain 0.9.
- Use negative tracking for prose and actions but slight positive tracking for small mono markings. Selective bright words, rather than bolding an entire quote, create emphasis on dark backgrounds.

## Layout

**Density:** Airy sections surround compact, information-rich components; headlines are compressed while chapters have substantial breathing room.

### Spacing

**Spacing system:**

- **horizontal grid** 8px, horizontal — Explains most container padding and column spacing; individual component gaps also use 10px and 22px.

| Value | Use |
| --- | --- |
| 8px | Eyebrow-to-heading separation and tight benefit stacks. |
| 10px | Card text stacks and compact repeated details. |
| 16px | Paired actions and heading-to-body separation. |
| 24px | Outer side padding, feature-card grid gaps and compact panel padding. |
| 32px | Main text-stack gaps, larger grid gaps and action separation from copy. |
| 40px | Light feature-card padding and proof-tray inset. |
| 56px | Large feature and closing-panel padding. |
| 72px | Centered secondary-page opening padding. |
| 80px | Major section top padding. |
| 88px | Space below the closing panel and generous feature-column separation. |
| 112px | Secondary product opening top padding. |
| 128px | Separation between alternating feature chapters. |
| 144px | Default opening top padding below navigation. |
| 160px | Separation between developer-panel title area and capability icon rail. |

### Containers and grids

- **marketing container**: max width 1200px · side padding 24px. Centered page structure; 120px outside margins at a 1440px desktop width.
- **opening split**: max width 1200px · 2 columns · gap 32px. Text occupies roughly half the width; art may overflow the right column and is larger than a conventional illustration thumbnail.
- **feature split**: max width 1200px · 2 columns · gap 88px. Alternate an editorial copy block and a 500px-wide layered media assembly.
- **section introduction**: max width 800px. Centered headings above diagrams or solution grids.
- **proof rail**: max width 1200px · 4 columns · gap 32px · side padding 40px. Four centered proof plaques within a recessed light tray; quantified proof uses three plaques.
- **compact introduction** (only for comparison and pricing pages): max width 600px. Centered introductory headline and support for comparison or pricing.
- **benefit grid** (only for benefit card grids): max width 1200px · 3 columns · gap 24px. Three pale benefit cards; solution-specific variants use 16px gaps.
- **plan comparison** (only for pricing pages): max width 1070px · 2 columns · gap 32px. Equal-height light and dark plan cards.

## Corner radius

| Element | Radius |
| --- | --- |
| major panels | 32px |
| media and primary actions | 16px |
| compact actions | 12px |
| benefit icon squares | 4px |
| eyebrow capsule | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| raised panel | `rgba(0, 0, 0, 0.01) 0px 0.8px 3.7px 0px, rgba(0, 0, 0, 0.02) 0px 2.4px 11.1px 0px, rgba(0, 0, 0, 0.05) 0px 6.4px 29.4px 0px, rgba(0, 0, 0, 0.16) 0px 20px 92px 0px, rgba(0, 0, 0, 0.05) 0px 0px 0px 1px` | Large white proof stage and dark developer panel. |
| proof plaque | `rgba(0, 0, 0, 0.02) 0px 2.8px 2.2px 0px, rgba(0, 0, 0, 0.03) 0px 6.7px 5.3px 0px` | Small white plaques, enough to separate them from a nearly white backing. |
| button inner edge | `rgba(255, 255, 255, 0.13) 0px 0px 0px 2px inset` | Mint and dark filled action keys. |

### Surfaces

#### Canvas · level 0

**Use:** Default page surface.

**CSS:** `background: #ffffff; color: #18181b`

#### Pale card · level 1

**Use:** Grouped benefit content.

**CSS:** `background: #fafafa; border-radius: 32px; padding: 40px`

**Observed:** Mostly flat, with extremely faint diagonal texture at the edges rather than a visible outline.

**Transfer:** Use for explanatory content, allowing text and one small colored emblem to lead.

#### Raised proof stage · level 1

**Use:** Large light trust or metric module.

**CSS:** `background: #ffffff; border-radius: 32px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.01) 0px 0.8px 3.7px 0px, rgba(0, 0, 0, 0.02) 0px 2.4px 11.1px 0px, rgba(0, 0, 0, 0.05) 0px 6.4px 29.4px 0px, rgba(0, 0, 0, 0.16) 0px 20px 92px 0px, rgba(0, 0, 0, 0.05) 0px 0px 0px 1px`

**Observed:** A white title area sits above a porcelain tray; the tray holds small physical-looking plaques.

**Transfer:** Group verifiable product proof into a single substantial object rather than scattered badges.

#### Graphite feature panel · level 1

**Use:** Developer-oriented feature stage.

**CSS:** `background: #27272a; color: #ffffff; border-radius: 32px; padding: 56px; border: 1px solid rgba(255, 255, 255, 0.05)`

**Observed:** Faint grain, a large cropped dark isometric object and a low icon rail give it depth.

**Transfer:** Use dark art on dark backing with small illuminated mint or lime details.

#### Dark chapter · level 0

**Use:** High-contrast testimonial and process sections.

**CSS:** `background: #18181b; color: #ffffff`

**Observed:** Very subtle diagonal lines are strongest at the edges and fade toward the text.

**Transfer:** Keep the background almost black, with texture subordinate to the message.

#### Closing stage · level 1

**Use:** Final high-impact conversion panel.

**CSS:** `background: #18181b; border-radius: 32px; padding: 56px; overflow: hidden; box-shadow: rgba(0, 0, 0, 0.17) 0px 0.7px 3.5px -0.6px, rgba(0, 0, 0, 0.17) 0px 1.8px 9px -1.2px, rgba(0, 0, 0, 0.16) 0px 3.6px 18.1px -1.8px, rgba(0, 0, 0, 0.15) 0px 6.9px 34.3px -2.3px, rgba(0, 0, 0, 0.13) 0px 13.6px 68.2px -2.9px, rgba(0, 0, 0, 0.08) 0px 30px 150px -3.5px`

**Observed:** A broad dim light sweep and fine grain sit behind the lower-aligned message; nominal height is 405px.

**Transfer:** Preserve the theatrical dark object on a white page; match the soft sweep rather than using a bright gradient.

## Components

### Navigation

**Use:** Persistent desktop navigation.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 80px; background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(8px); filter: saturate(1.4); z-index: 5; padding: 0px 24px`

**Text style:** `navigation` — Inter 500 · 14px/1

**Observed:** A compact logo anchors the left, links with small chevrons follow, and login plus a compact demo key sit at the right. An announcement bar adds 40px above the initial navigation; scrolling leaves the navigation alone.

### Primary button

**Use:** Default main action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 12px; height: 44px; padding: 12px 16px 12px 22px; background: #94faf0; color: rgba(9, 9, 11, 0.95); border-radius: 16px; box-shadow: rgba(255, 255, 255, 0.13) 0px 0px 0px 2px inset`

**Text style:** `action` — Inter 600 · 16px/1.2 · tracking -0.02em

**Observed:** Label precedes a small right arrow. Header variant is 36px high with 12px corners and 8px 16px padding. Lime replaces mint for developer and premium-plan actions.

### Dark button

**Use:** Compact contextual exploration action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 8px 16px; background: #27272a; color: #ffffff; border-radius: 12px; box-shadow: rgba(255, 255, 255, 0.13) 0px 0px 0px 2px inset`

**Text style:** `action` — Inter 600 · 16px/1.2 · tracking -0.02em

**Observed:** A short self-contained key below a benefit list. Secondary product openings use a 44px version with a right arrow.

### Glass button

**Use:** Secondary action alongside a mint primary action on dark panels.

**CSS:** `height: 44px; padding: 12px 22px; background: rgba(255, 255, 255, 0.1); color: #ffffff; border-radius: 16px; backdrop-filter: blur(5px); box-shadow: rgba(255, 255, 255, 0.03) 0px 0px 0px 1px inset`

**Text style:** `action` — Inter 600 · 16px/1.2 · tracking -0.02em

**Observed:** Less visually assertive than the colored key. On the white opening, the secondary implementation action reads as white with a faint edge and dark text.

### Technical marker

**Use:** Section category or product-state label.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #3f3f46`

**Text style:** `eyebrow` — Kode Mono 600 · 12px/1 · tracking 0.02em · uppercase

**Observed:** A 16×7px mint capsule precedes uppercase monospace text. Use lime for alternating capability chapters; dark stages use muted gray or mint lettering.

### Benefit row

**Use:** Short outcome lists and plan inclusions.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 2px 0px 2px 30px; border-radius: 8px`

**Text style:** `benefit` — Inter 500 · 14px/1.4 · tracking -0.007em

**Observed:** A separate 18×18px icon square with 4px corners is positioned at the row start; its 14px glyph is dark over mint or lime. Lists stack at 8px gaps, or 10px in plan comparisons.

### Proof plaque

**Use:** Tangible trust credential or product-quality proof.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 32px; background: #ffffff; border-radius: 16px; border-top: 1px solid #f2f2f2; width: 256px; height: 320px; box-shadow: rgba(0, 0, 0, 0.02) 0px 2.8px 2.2px 0px, rgba(0, 0, 0, 0.03) 0px 6.7px 5.3px 0px`

**Text style:** `proof-title` — Neo Grotesk 700 · 32px/1 · tracking -0.01em

**Observed:** Four small silver circular fasteners occupy the corners. A colored clipped-corner emblem sits above the bold abbreviation, followed by a fine rule and mono proof-caption. Quantified variants are 240×294px and replace the emblem with a circular gauge.

**Transfer:** Use real standards, independently supported qualities or verified metrics; maintain the hardware-like plaque construction.

### Footer columns

**Use:** Dense utility navigation after the closing stage.

**CSS:** `background: #ffffff; padding: 40px 0px 0px; color: #18181b`

**Text style:** `footer-link` — Inter 500 · 14px/16px · tracking -0.01em

**Observed:** Logo and a small credential occupy the first area, then five narrow link columns with muted headings and 16px vertical link gaps. A full-width 56px charcoal strip contains subdued copyright and small social icons.

### Benefit card

**Only for:** benefit card grids

**Use:** Compact explanatory capability.

**CSS:** `background: #fafafa; border-radius: 32px; padding: 40px`

**Text style:** `card-heading` — Inter 600 · 18px/1.1 · tracking -0.022em

**Observed:** A 48px clipped-corner colored emblem leads, followed by a short title and body-small description. Icon-to-copy separation is 24px and title-to-description separation is 10px. Some solution cards use 32px padding.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side self-serve and sales-led offers.

**CSS:** `background: #fafafa; border-radius: 32px; overflow: hidden; width: 519px`

**Text style:** `price` — Neo Grotesk 500 · 40px/1.2 · tracking -0.05em

**Observed:** A 40px-inset upper area orders technical marker, price with billing qualifier, support line and action. A divider separates a lower inclusion list. The other equal-height card is graphite, with white title, muted pale copy and lime checks and action; a small physical proof badge sits at upper right.

### Lead form panel

**Only for:** lead-generation solution pages

**Use:** Contact form inset into a dark conversion module.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 24px; width: 560px`

**Observed:** A white form sits on the right of a 32px-rounded graphite panel; the left carries a short promise and three benefit rows. Fields are stacked, softly rounded and pale blue-gray; longer responses use a taller textarea.

**Transfer:** Keep only the fields needed to start a useful conversation; preserve the dark-to-white inset contrast.

## Imagery and graphics

### Exploded infrastructure assembly

**Use:** Signature opening object and feature-chapter illustrations.

**Observed:** White translucent rounded plates float in an isometric stack, connected by very fine gray routing paths. A small dark central module contains a bright mint symbol; other layers contain sparse form and system details. The opening object occupies most of the right half and extends beyond its nominal column; code-backed chapter art is roughly 500×380px.

**Transfer:** Translate the new product into input, processing and output layers. The minimum equivalent is a custom SVG assembly with meaningful modules, not a generic dashboard pasted into a browser.

**Build:** Use three rounded rectangular SVG plates in a shared isometric transform, offset vertically by 28–40px. Fill the upper plates white at 85–95% opacity, add 1px gray edges and soft low-opacity black shadows. Put a dark 160px central chip on the top plate with a simple mint symbol. Draw thin elbow connectors and two or three tiny interface modules beneath; add a faint dot or character field fading under the stack.

### Offset code and object panels

**Use:** Alternating editorial capability chapters.

**Observed:** A dark syntax panel sits behind a pale illustration panel, with the front panel shifted down and toward the outer edge. Both have 16px corners and subtle depth. The code is supporting texture; the white isometric diagram is the focal object.

**Transfer:** Show short authentic code related to the capability and pair it with a simplified product workflow.

**Build:** Layer two 500×380px rounded panels. Place the code panel at the back in graphite; offset the porcelain front panel about 64px horizontally and vertically. Clip both panels, use a fine shadow edge and leave a visible strip of code at the top and left. Put the layered SVG assembly inside the front panel.

### Dark illuminated machine

**Use:** Developer-oriented signature feature panel.

**Observed:** A dark isometric chip with a lime center is cropped against the top-right edge of a graphite panel. Seven small smoked tiles along the bottom contain mint linework, nodes and product symbols; gray captions sit below.

**Transfer:** Construct a darker version of the opening assembly using the new product's central mechanism, then reduce its capabilities to a consistent icon rail.

**Build:** Reuse the isometric plate geometry with graphite faces, translucent white edges and corner fasteners. Put one lime symbol at its center. Along the lower edge, draw equally sized square tiles with a faint white inner edge, mint paths and small illuminated dots. Keep the large chip low-contrast except for its center.

### Machined proof and gauges

**Use:** Signature proof treatment, including credentials and quantified outcomes.

**Observed:** White plaques sit in a pale recessed tray, each with four corner fasteners. Credential plaques carry clipped-corner colored emblems; metric plaques use thin open circular tracks changing from turquoise through mint to lime, with black figures and tiny mono labels inside.

**Transfer:** Use this physical construction for the new product's strongest substantiated proof; metric gauges belong only with meaningful quantitative claims.

**Build:** Draw four 10px silver circles inset 12px from plaque corners. For credential emblems use an SVG square with two diagonally clipped corners and a dark center glyph. For gauges draw a 195px SVG circular light-gray track with an 8px rounded stroke and a second partial path with a turquoise-to-lime gradient; leave a visible gap, center the stat recipe and put the stat-label below it.

### Dark technical texture and light sweep

**Use:** Dark chapters and the closing stage.

**Observed:** Fine diagonal grooves and grain fade in and out across almost-black surfaces. The closing stage has broad dim gray illumination toward the right, never a conspicuous colored aura.

**Transfer:** Maintain a near-monochrome material so colored keys and white emphasis remain the brightest objects.

**Build:** Overlay a repeating 135deg gradient of rgba(255,255,255,0.025) lines 1px wide separated by 5px, then mask it with a broad radial fade. Add a monochrome SVG noise layer at about 0.05 opacity. For the closing stage place a blurred broad diagonal white ellipse behind the right side at less than 0.08 opacity.

### Photographic proof panel

**Only for:** customer and solution proof sections

**Use:** Human context behind a quote or real-use demonstration.

**Observed:** Natural workplace or consumer photography fills a 1200px-wide, 32px-rounded panel. A heavy charcoal overlay reduces saturation and brightness so the quote reads clearly at left. At right, a bright pale product diagram or mint-framed interface overlaps the photograph.

**Transfer:** Use authentic use-context photography with subdued contrast, plus one product-specific demonstration. Keep the image's human subject discernible rather than using a decorative stock portrait.

### Process diagram

**Only for:** technical explanation sections

**Use:** Explain connections and system boundaries.

**Observed:** Fine orthogonal connectors join dark rounded nodes, with the central product module picked out in mint. Diagram backings can be charcoal or a white inset panel; grouping boundaries are faint and labels remain small.

**Transfer:** Show the actual input-to-output relationships of the new product, limiting color to the main mechanism and occasional partner markers.

### Icons

**Observed:** Small filled SVG glyphs at 14px sit inside 18px rounded squares; button arrows are 20px. Feature emblems use 48px clipped-corner backing with a 24px dark glyph. Larger technical illustrations use thin mint paths and nodes rather than emoji.

**Transfer:** Choose simple system-like glyphs with compact silhouettes. For feature emblems, use the clipped-corner tile construction; keep arrows and checks consistent across actions and proof lists.

## Section recipes

How recurring sections are built.

### First screen: Engineered object opening

**Observed:** A white first screen begins beneath a fixed 80px Navigation and a 40px announcement strip. Inside the 1200px marketing container, a left-aligned three-line display headline takes roughly half the content width. Top padding is 144px beneath the header. A 500px-wide body paragraph follows after 32px; a horizontal group of three compact Benefit rows follows, then paired Primary button and light secondary action at 16px separation. The right half is dominated by Exploded infrastructure assembly, with faint connectors extending toward the viewport edges and a character-field shadow beneath it. Layers run from white canvas to fine paths, lower plates, translucent top plate and mint-centered dark chip. The headline, support, benefits, both actions and complete central assembly are visible within 900px; only the start of a dark logo band appears at the bottom, with the later capability sections below.

**Transfer:** Use a short outcome headline and an abstract but meaningful engineered representation of the new product. Without detailed art, construct the layered SVG assembly described in imagery. Secondary product and use-case pages use secondary-opening, a technical marker, compact support or benefit list and one dark action aligned to the right, followed by a full-width proof panel. Comparison and pricing openings center the same smaller heading over a short support line.

**Avoid:** Do not replace the large right-hand assembly with a small flat icon, center the default opening, or spread the compressed headline across the full width.

**Text style:** `display` — Neo Grotesk 500 · 80px/0.8 · tracking -0.04em

### Heading and editorial chapters

**Observed:** A 56px heading introduces the topic with a two-column support passage. Subsequent chapters alternate text and Offset code and object panels, with 128px between chapters. Each text block uses Technical marker, feature-heading, three Benefit rows and a Dark button. Chapter composition stays on white, despite the dark backing inside each media assembly.

**Transfer:** Divide a complex product into a few distinct outcomes; alternate object placement to give a long page movement without adding unrelated section colors.

**Text style:** `feature-heading` — Neo Grotesk 500 · 32px/1.2 · tracking -0.03em

### Dark quotation and developer stage

**Observed:** A centered quote uses quote at 32px/1.3, white at 50% opacity with key phrases in full white. Attribution sits 40px below. A Graphite feature panel overlaps the transition from the Dark chapter to white canvas, combining a 56px heading, lime action, Dark illuminated machine and low capability rail.

**Transfer:** Pair human proof with a concrete invitation to implement; the capability rail can represent tools, integrations or core product operations.

**Text style:** `quote` — Inter 500 · 32px/1.3 · tracking -0.04em

### Raised trust stage

**Observed:** Raised proof stage combines a centered trust-eyebrow, heading, body support and Dark button. A pale lower tray holds four Proof plaques at 32px gaps with 40px inset. The panel is a substantial physical object, not a row of unframed logos.

**Transfer:** Give the product's most credible assurances an equally tangible stage; the proofs need not be security standards.

**Text style:** `heading` — Neo Grotesk 500 · 56px/1 · tracking -0.04em

### Monumental closing and utility footer

**Observed:** Closing stage sits on white with 88px below it. The large closing line begins in white at 70% opacity and ends in full white, followed by an 18px support line and paired Primary button and Glass button. Text is left-aligned with 56px inset and substantial atmospheric room above. Footer columns follow on white and end with a 56px dark copyright strip. This ending is consistent across the page types.

**Transfer:** Write a contrasting more-of-this/less-of-that promise for the new product and retain the two-tone typographic close. Reorganize footer columns for the new information architecture without making the ending an undifferentiated dark footer.

**Text style:** `closing` — Neo Grotesk 500 · 64px/0.9 · tracking -0.03em

### Photographic statement

**Only for:** customer and solution proof sections

**Observed:** A darkened photographic panel puts a photo-quote at left and a large overlapping light demonstration at right. Important words are full white within otherwise muted white text; a small attribution follows beneath.

**Transfer:** Use customer testimony or a concise real-world statement with a product demonstration, balancing emotional context and technical clarity.

**Text style:** `photo-quote` — Inter 500 · 28px/1.2 · tracking -0.03em

### Process explanation chapter

**Only for:** technical explanation pages

**Observed:** A centered technical marker, diagram-heading, short support and mint action sit above a wide Process diagram. Three explanatory columns below the diagram use short headings, body-small and compact glass documentation actions. The dark field occupies an entire chapter.

**Transfer:** Explain how the product operates before listing implementation details; nodes should describe actual system roles.

**Text style:** `diagram-heading` — Neo Grotesk 500 · 48px/1 · tracking -0.04em

### Quantified proof tray

**Only for:** solution pages with supported metrics

**Observed:** Three 240×294px Proof plaque variants sit at 32px gaps inside a Raised proof stage. Large stat figures are enclosed by open gradient gauges; tiny stat-label text sits inside and stat-caption sits below.

**Transfer:** Use only comparable, meaningful figures with clear context. Keep the plaque and fastener construction even when the gauge shape changes.

**Text style:** `stat` — Inter 500 · 55px/1 · tracking -0.05em

### Benefit and demonstration grids

**Only for:** solution pages

**Observed:** Centered product-section-heading and support precede three columns. Short variants use Benefit card; longer 389px-wide cards use 16px corners, compact text, small pastel product-data chips and a lower pale-gray illustration area. A separate graphite demonstration shell uses 16px corners and a large inset light interface.

**Transfer:** Keep the outer marketing construction consistent while showing the new product's actual UI inside; do not turn demo typography into the page's body system.

**Text style:** `product-section-heading` — Neo Grotesk 500 · 48px/0.9 · tracking -0.04em

### Customer and differentiation mosaic

**Only for:** comparison and company-positioning pages

**Observed:** A centered compact introduction gives way to a 32px-rounded dark customer panel: 40px heading, four photographic customer tiles and a smaller monochrome logo rail. Pale feature cards below vary in width, mixing concise copy, icon emblems and dark technical diagrams. A graphite split feature with white diagram inset adds emphasis.

**Transfer:** Move from external credibility to specific design advantages, using mixed-width cards only when the material supports different levels of detail.

### Plan comparison

**Only for:** pricing pages

**Observed:** A 600px centered introduction leads into two Plan cards within a 1070px grid. Light self-serve and dark sales-led cards align their upper actions and use colored checks in the lower feature lists. A centered underlined pricing-detail link follows; the Closing stage is narrower at 1024px and its headline wraps.

**Transfer:** Compare materially different purchase paths instead of manufacturing an arbitrary three-tier layout.

**Text style:** `price` — Neo Grotesk 500 · 40px/1.2 · tracking -0.05em

### Embedded contact module

**Only for:** lead-generation solution pages

**Observed:** A 1200px graphite panel uses 24px inset and 32px column gap. Benefit-led copy sits on the left and Lead form panel on the right. A subtle fine path in the dark backing is subordinate to the bright form.

**Transfer:** Place assurance alongside the form without making the form look like a separate website.

## Page flow

**Storyline:** Outcome promise → tangible product explanation → external or quantified proof → capability depth → implementation confidence → conversion → utility navigation.

### Broad marketing landing page

1. **promise** — Large split opening with a floating engineered object.
2. **social proof** — Dark customer logo strip.
3. **capability chapters** — Introductory heading and alternating text/code-object assemblies.
4. **customer proof** — Centered dark testimonial with selective bright words.
5. **implementation confidence** — Dark developer stage followed by raised trust plaques.
6. **closing call** — Monumental two-tone dark panel, then white link columns and dark legal strip.

**Transfer:** Use this as the default visual range for a new product landing page; reorder chapters around the buyer's questions.

### Use-case landing page

1. **promise** — Compact left-aligned heading, technical marker, three benefits and right-side action.
2. **customer proof** — Photographic testimonial with overlapping pale illustration.
3. **benefits** — Three pale feature cards.
4. **product explanation** — Full dark process chapter and documentation columns.
5. **quantified value** — Centered heading above three pale horizontal outcome rows with colored icons.
6. **closing call** — Shared dark closing panel and full utility footer.

**Transfer:** Connect an audience-specific promise to operational explanation and a clear value model.

### Differentiation and credibility page

1. **positioning** — Centered smaller heading and short support with investor logos below.
2. **social proof** — Large dark customer panel with photographic tiles and monochrome logos.
3. **differentiation** — Mixed-width pale cards and diagram-backed capability blocks.
4. **strategic capability** — Dark split panel with a large white technical diagram inset.
5. **objection handling** — Additional light assurance cards.
6. **closing call** — Shared closing panel followed by utility footer.

**Transfer:** Use external proof before detailed product advantages; do not turn the page into a wall of mission statements.

### Flagship solution and demonstration page

1. **promise** — Compact product opening with clear support and a dark action.
2. **quantified proof** — Three circular metric gauges in a raised light tray.
3. **product demonstration** — Dark photographic statement beside a mint-framed real interface.
4. **use cases** — Three tall explanatory cards with data chips and UI illustrations.
5. **hands-on evaluation** — Large dark demo shell with explanation and dataset controls above a light interface.
6. **ease and assurance** — Centered heading and three small pale benefit cards.
7. **lead generation** — Dark panel with proof rows beside an inset white form.
8. **closing call** — Shared dark close and utility footer.

**Transfer:** Give a focused product more room for direct demonstration and substantiated outcomes than a broad platform page.

### Pricing and purchase-path comparison

1. **purchase confidence** — Centered short headline with a reassuring support line.
2. **pricing** — Two equal-height plan cards, one light and one graphite.
3. **detail access** — Small underlined link below the plans.
4. **closing call** — Narrower dark closing panel followed by the shared utility footer.

**Transfer:** Keep the plan comparison brief, legible and visually related to the rest of the marketing system.

## Writing

Confident and operational, with warmth supplied by direct outcomes and the occasional conversational turn. Technical language is welcome when it clarifies how the product works; benefits remain concrete rather than visionary.

**Do not copy:** Do not reuse Basis Theory or Linque names, logos, product diagrams, customer marks, testimonials, certifications, pricing, performance percentages, coverage figures or other claims. Replace these with the new product's own supported content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your, especially around existing tools and workflows. Use we or our for invitations and assurances, and the product name when explaining its mechanism.
- **Rhythm:** Short outcome-led headings contrast with explanatory sentences and compact benefit fragments. Headings often use two linked clauses; support copy can name several concrete operations in one sentence. Actions are brief verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | State an outcome as an active promise, with little introductory framing. | 5–9 words | “Built to keep customers transacting”<br>“Secure every e-commerce transaction” |
| Support | Explain the mechanism and connect it to a business outcome. | One or two sentences | “An agnostic payment vault can slide into any payment stack without disrupting business.” |
| Feature heading | Name the improvement, then explain the enabling choice. | 10–20 words | “Keep recurring revenue flowing with smart retries, token updates, and backup routing.” |
| Primary action | Use a concrete next step rather than a vague invitation. | 2–5 words | “Request a demo”<br>“Start implementing”<br>“Talk to an expert” |
| Conversational section heading | Use a plainspoken phrase sparingly to break up technical density. | 4–8 words | “Kiss abandonment and churn goodbye” |
| Closing promise | Contrast the desirable outcome with the unwanted burden. | Two short linked statements | “More of the transactions you want.”<br>“Less of the risk and fraud you don't.” |

**Words and phrasing to use:** built for; keep; reduce; without disrupting; existing; flexible; start; secure; in minutes; your team

**Avoid:** revolutionary; game-changing; magical; limitless possibilities; unmatched excellence; vague AI transformation language

**Rules:**

- Lead with what improves for the reader, then name the mechanism.
- Keep benefit lists parallel and specific; each row should carry one idea.
- State compatibility and constraints directly rather than hiding them behind broad claims.
- Use proof figures with qualifiers and explanatory captions.
- Distinguish the low-friction self-serve action from the conversational sales action.

## Do's and Don'ts

### Do

- Keep the opening's 80px headline tightly stacked at 0.8 line height.
- Use 1200px as the desktop structural width and 24px minimum side padding.
- Pair 44px action heights with 16px corners and 36px compact actions with 12px corners.
- Make small technical labels 12px Kode Mono with 0.02em tracking and a 16×7px colored marker.
- Keep proof physically staged: white plaques, four corner fasteners, faint edges and a pale tray.
- Let feature media overlap its backing rather than making every illustration a flat isolated rectangle.
- Use white at different opacities to emphasize selected words within dark quotes and the closing line.
- Keep the closing object distinct from the white footer, with 88px breathing room below it.

### Don't

- Do not turn the mint accent into a full-page pastel wash; the primary canvas is white.
- Do not use fully rounded pill buttons in place of the 12px and 16px rectangular keys.
- Do not use heavy display weights everywhere; bold is reserved for short proof abbreviations.
- Do not apply the small mono face to body paragraphs or large marketing headings.
- Do not flatten white proof plaques into bare inline certification logos.
- Do not replace thin routing diagrams and pale plates with saturated cartoon illustrations.
- Do not use a universal 8px gap for everything; retain 10px text stacks, 22px details and the larger chapter rhythm.
- Do not carry the interface's pastel data-chip colors into the general marketing palette.
- Do not render the final footer entirely charcoal; only its bottom utility strip is dark.

## Motion and responsive

### Motion

**Observed:**

- No action or surface transition timings are established.
- The initial announcement strip is absent from later scrolled views while the 80px navigation remains fixed.
- Product demonstrations include video, and some layered media have changing offsets.

**Transfer:**

- Keep navigation separate from the decorative object layers so it remains stable as the page scrolls.
- Use the engineered assemblies and demonstrations as the focus of any movement, keeping text and actions readable.

**Unknown:**

- Exact animation durations, easing, triggers and hover/focus behavior for the main buttons are not established.

### Responsive

**Observed:**

- Styles declare width boundaries around 810px, 1200px and 1440px; additional 400px and 768px rules occur in some contexts.

**Transfer:**

- On narrow layouts, stack the promise before its engineered object and preserve the central chip and plate relationships rather than shrinking the entire desktop scene to illegibility.
- Convert proof rails and plan comparisons to readable stacked modules; maintain plaque corners and their physical depth.
- Keep the closing statement's two-tone emphasis when it wraps, and reduce its inset before sacrificing the action labels.

**Unknown:**

- Exact mobile font sizes, column transitions, navigation replacement and artwork cropping are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
