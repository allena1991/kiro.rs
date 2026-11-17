# LottieFiles — playful production playground

## Overview

An upbeat software style that pairs oversized geometric sans lettering with colorful, tactile illustrations and real interface demonstrations. White and pale gray dominate, punctuated by deep charcoal stages, teal actions and a concentrated golden-yellow feature moment. It feels approachable without losing technical credibility, with airy storytelling around dense, useful product proof.

### Essentials

- Friendly oversized type, not heavy sales type: DM Sans LF at 96px/1.04, weight 500 and -0.05em tracking opens the story; 64px/1.15 section heads retain the same rounded geometric character.
- A promise shares the stage with a playful object: a left-aligned three-line headline and paired 48px actions sit beside a 600×400px colorful illustration, followed by four compact benefit tiles with 48px colored icon squares.
- Teal is a conversion signal rather than a page tint: #019d91 buttons use 12px corners, 24px side padding and 16px medium Inter; neutral secondary actions keep equal height and a faint outline.
- Color lives inside a mostly white framework: neutral feature cards use #f4f4f5, dark demonstration islands use #09090b with 48px outer corners, and one concentrated yellow chapter uses #f0b100 rather than distributing saturated backgrounds everywhere.
- Product proof is staged as a playground: asymmetric 24px-corner bento cards and dark tabbed demonstrations combine real interface fragments with vivid vector or softly rounded character art. Supply a small original geometric scene when rich product media is unavailable.
- A mint shape pile gives the closing action its own silhouette: a white 24px-corner panel on a pale gray band holds left-aligned copy above circles, tilted capsules and soft polygons clustered along its bottom-right edge; retain this device even when it must be built in SVG.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action teal | `#019d91` | `--color-action` | action, link | Primary actions and directional text links. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Icon yellow | `#ffbf00` | `--color-icon-yellow` | surface | Small square benefit icon backing. |
| Golden chapter | `#f0b100` | `--color-gold` | background | A concentrated capability spotlight with dark nested demonstration panels. |
| Bright mint | `#00ddb3` | `--color-mint` | accent, surface | Small feature icon backings and mint-family illustration accents; softened with white for the shape pile. |
| Icon blue | `#3a86ff` | `--color-icon-blue` | surface | Small square benefit icon backing. |
| Icon pink | `#ff8eed` | `--color-icon-pink` | surface | Small square benefit icon backing. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#09090b` | `--color-ink` | text, background | Main headings and deep demonstration or footer backgrounds. |
| Raised charcoal | `#18181b` | `--color-dark-card` | surface, text | Cards within dark stages; also the foreground in product-led variants. |
| Charcoal rail | `#27272a` | `--color-dark-rail` | surface | Tabbed demo rails and active capability tiles. |
| Supporting gray | `#71717b` | `--color-body` | text | Supporting paragraphs on the default light theme. |
| Inverse supporting gray | `#9f9fa9` | `--color-inverse-muted` | text | Footer links and supporting text on dark demonstrations. |
| Hairline gray | `#e4e4e7` | `--color-edge` | border | Button outlines and panel edges; half-opacity edges remain intentionally faint. |
| Soft gray panel | `#f4f4f5` | `--color-muted` | surface, background | Feature cards, secondary filled buttons and closing band. |
| Faint neutral | `#fafafa` | `--color-faint` | surface, background, text | Benefit tiles, FAQ bands and inverse foreground. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, white inset panels and footer category titles. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Pricing closing teal | `#00c1a2` | `--color-pricing-teal` | background | Full-width closing band behind white copy and character art. |
| enterprise, pricing and product-led pages | Business charcoal | `#20272c` | `--color-business-ink` | text | Regular-weight business and product-led headings. |

## Typography

- **DM Sans LF** — Default marketing headings, paragraphs and footer links. Rounded geometric sans with open counters; large text is medium rather than bold. If unavailable, use **DM Sans**. Use weights 400–600 and preserve negative tracking. Font stack: "DM Sans LF", "DM Sans", sans-serif.
- **Inter LF** — Navigation, conversion buttons and footer mission statement. Compact neutral sans that makes controls feel crisp beside the rounder marketing text. If unavailable, use **Inter**. Font stack: "Inter LF", Inter, sans-serif.
- **DM Sans Variable** (only for enterprise, pricing and product-led pages) — Regular-weight headings and question labels. A lighter version of the geometric headline voice. Font stack: "DM Sans Variable", "DM Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DM Sans LF | 500 | 96px | 1.04 | -0.05em | Default opening headline and monumental demonstration introduction. |
| heading-lg | DM Sans LF | 500 | 64px | 1.15 | -0.04em | Centered section leads and split feature headlines. |
| heading | DM Sans LF | 500 | 48px | 1.15 | -0.04em | Closing call headline and large metric numerals. |
| footer-statement | Inter LF | 500 | 32px | 1.1 | normal | Two-line mission statement above the footer directory. |
| card-heading | DM Sans LF | 500 | 24px | 1.12 | -0.01em | Bento card headings. |
| hero-support | DM Sans LF | 400 | 24px | 1.35 | -0.01em | Opening paragraph, substantially quieter than the headline. |
| section-support | DM Sans LF | 400 | 20px | 1.4 | -0.01em | Section support, trust line and testimonial quotations. |
| benefit-label | DM Sans LF | 500 | 20px | 1.14 | -0.01em | Short labels beside colored benefit icons and attribution names. |
| footer-category | DM Sans LF | 600 | 20px | 1.4 | normal | Footer column headings. |
| body | DM Sans LF | 400 | 16px | 1.4 | normal | Compact descriptive copy inside feature cards. |
| action | Inter LF | 500 | 16px | 1.5 | normal | Main and secondary conversion actions. |
| footer-link | DM Sans LF | 400 | 16px | 1.5 | normal | Muted links in the footer directory. |
| navigation | Inter LF | 500 | 14px | 20px | normal | Header menu labels and small controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-family pages | product-display | DM Sans Variable | 400 | 96px | 1.04 | -0.05em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Centered product-family opening above a dark demonstration. |
| enterprise and product-led pages | business-display | DM Sans Variable | 400 | 64px | 1.15 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Split business opening and centered capability chapter leads. |
| enterprise, pricing and product-led pages | business-heading | DM Sans Variable | 400 | 48px | 1.15 | -0.04em, features "blwf", "cv03", "cv04", "cv09", "cv11" | More restrained section and pricing opening headlines. |
| enterprise and product-led pages | compact-closing | DM Sans Variable | 400 | 38px | 1.15 | -0.0505em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Longer closing promises in the mint shape panel. |
| enterprise, pricing and product-led pages | question | DM Sans Variable | 400 | 20px | 1.3 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | FAQ question and plan-name labels. |

**Notes:**

- Tracking tightens with scale: -0.01em on paragraphs and card labels, -0.04em on major section heads and -0.05em on the opening display.
- Default headings use weight 500; business and product-family variants deliberately use 400. Do not substitute a heavy bold cut.
- Headings wrap into compact two- or three-line blocks; support is narrower, lower contrast and separated by 24px in the default theme.

## Layout

**Density:** Airy narrative spacing surrounds compact control groups and dense visual demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card heading-to-description gap and inline icon gaps. |
| 12px | Tight bento gutters. |
| 16px | Paired action gap and benefit tile inset. |
| 24px | Headline-to-support gap, repeated card gutters and compact card padding. |
| 32px | Desktop page gutters and feature card copy inset. |
| 40px | Support-to-action separation. |
| 64px | Headline group to feature media, hero columns and footer groups. |
| 80px | Ordinary desktop section padding and opening top space. |
| 160px | Closing band's vertical padding. |

### Containers and grids

- **page-container**: max width 1440px · side padding 32px. Centered outer frame; inset panels occupy 1376px at the desktop width.
- **centered-copy**: max width 880px · side padding 32px. Centered section headings; narrower 640px support lines underneath.
- **bento-grid**: 3 columns · gap 12px. Unequal feature areas: a broad card beside a narrower vertical stack, then two balanced cards.
- **proof-grid**: 3 columns · gap 24px. Case studies and tool feature cards with consistent image-led tops.
- **faq-column**: max width 760px · gap 10px. Centered narrow column of question panels.
- **footer-directory**: 6 columns · gap 16px. Six categories across the desktop; each occupies two tracks of a twelve-track underlying grid.
- **pricing-container** (only for pricing pages): max width 1200px · 3 columns · gap 16px. Three equal plan cards and business-focused value proof.

## Corner radius

| Element | Radius |
| --- | --- |
| main-actions | 12px |
| header-controls | 6px |
| feature-cards | 24px |
| dark-inner-cards | 16px |
| chapter-islands | 48px |
| small-icon-backings | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | action-edge | `0px 1px 2px 0px rgba(0,0,0,0.05)` | A slight grounding edge on primary and secondary buttons. |
| pricing pages | plan-card | `0px 1px 4px 0px rgba(32,39,44,0.06)` | Plan cards without a floating elevation effect. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #09090b`

#### Soft feature card · level 1

**Use:** Feature explanations and cropped product demonstrations.

**CSS:** `background: #f4f4f5; border-radius: 24px; overflow: hidden`

**Observed:** Text occupies a padded top band while the media reaches the lower edge.

**Transfer:** Use real product output beneath a short heading; keep the surrounding surface flat.

#### Dark island · level 1

**Use:** High-emphasis product demonstration and quantified proof.

**CSS:** `background: #09090b; border-radius: 48px; padding: 80px 32px 32px; color: #fafafa`

**Observed:** Inset within white gutters, with charcoal cards nested inside rather than a page-wide dark theme.

**Transfer:** Group the most technical demonstration into a self-contained stage.

#### Raised dark card · level 2

**Use:** Metrics, comparisons and demonstrations within dark islands.

**CSS:** `background: #18181b; border-radius: 16px; color: #fafafa`

#### Golden spotlight · level 1

**Use:** A concentrated capability highlight.

**CSS:** `background: #f0b100; border-radius: 48px; padding: 80px 32px 32px; color: #09090b`

**Observed:** Centered headline and white secondary action above a dark interactive demonstration.

**Transfer:** Reserve the saturated chapter for a meaningful leap in capability.

#### Closing band · level 0

**Use:** A pale base for the white illustrated closing panel.

**CSS:** `background: linear-gradient(#ffffff 0%, #f4f4f5 20%); padding: 160px 0px`

#### Footer canvas · level 0

**Use:** Final directory and mission statement.

**CSS:** `background: #09090b; color: #fafafa`

#### Pricing closing band · level 0

**Only for:** pricing pages

**Use:** A more direct conversion ending.

**CSS:** `background: #00c1a2; padding: 80px 40px; color: #ffffff`

**Observed:** Full-width teal band with a text block on the left and colorful character illustration on the right.

**Transfer:** Use this pricing-only alternative rather than changing the default illustrated white closing panel.

## Components

### Navigation menu

**Use:** Compact sticky desktop header.

**CSS:** `background: #ffffff; color: #09090b; height: 36px; padding: 8px 16px; border-radius: 6px; display: inline-flex; align-items: center`

**Text style:** `navigation` — Inter LF 500 · 14px/20px

**Observed:** The 64px header places a small symbol and wordmark at left, six menu items through the middle and search, locale, login and a teal signup control at right. Dropdown labels have 12px downward chevrons.

**States:** Declared: hover background #f4f4f5 and text #18181b; focus-visible 1px outline with ring-shadow variables.

### Primary button

**Use:** Main conversion action in light sections.

**CSS:** `background: #019d91; color: #fafafa; height: 48px; padding: 0px 24px; border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05); display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — Inter LF 500 · 16px/1.5

**Observed:** Content-sized rectangular control. Business variants use 20px side padding and white text; compact header controls use 36px height and 6px corners.

**States:** Declared: hover background becomes a 90% teal color mix with transparent; focus-visible uses ring-shadow variables and outline-style none.

### Secondary button

**Use:** A sales or tour action next to the main conversion.

**CSS:** `background: #ffffff; color: #09090b; height: 48px; padding: 0px 24px; border: 1px solid #e4e4e7; border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter LF 500 · 16px/1.5

**Observed:** Equal visual height to the primary action, separated by 16px. On dark or golden panels it can become a pale gray filled control.

**States:** Declared: hover background #f4f4f5 and text #18181b; focus-visible uses ring-shadow variables and outline-style none.

### Benefit tile

**Use:** Fast scanning of distinct strengths below the opening.

**CSS:** `background: #fafafa; border-radius: 16px; padding: 16px; display: flex; align-items: center; gap: 16px`

**Text style:** `benefit-label` — DM Sans LF 500 · 20px/1.14 · tracking -0.01em

**Observed:** A 48px square colored icon at left, short dark label and muted one-line explanation at right. Four equal desktop tiles have 24px gutters.

**Transfer:** Use different colored backings for distinct strengths, while keeping the tile surface neutral.

### Feature card

**Use:** Capability bento and interface proof.

**CSS:** `background: #f4f4f5; border-radius: 24px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-heading` — DM Sans LF 500 · 24px/1.12 · tracking -0.01em

**Observed:** Copy is inset 32px; a 16px description follows after 8px. Large interface fragments occupy the lower portion and can run to an edge.

**Transfer:** Change the shape and span to suit the amount of demonstration, not to make every tile equal.

### Metric card

**Use:** Quantified outcomes in a dark proof stage.

**CSS:** `background: #18181b; border-radius: 16px; color: #fafafa; height: 194px`

**Text style:** `heading` — DM Sans LF 500 · 48px/1.15 · tracking -0.04em

**Observed:** A 24px inset inner stack separates the large value at top from a small gray outcome label at bottom. Taller neighboring cards show comparative bars or code beside colorful animation.

**Transfer:** Use verified metrics and preserve the low-density contrast between number and caption.

### Demo selector

**Use:** Switching between closely related product demonstrations.

**CSS:** `background: #27272a; border-radius: 16px; padding: 4px; display: flex; gap: 16px; overflow-x: scroll`

**Observed:** A darker 12px-corner selected plate sits behind the active label. Items include a small product icon followed by a label, with 16px vertical and 32px horizontal item padding.

**Transfer:** Keep labels brief and maintain one clear selected state.

### Footer link

**Use:** Dense but legible destination directory.

**CSS:** `color: #9f9fa9`

**Text style:** `footer-link` — DM Sans LF 400 · 16px/1.5

**Observed:** White category headings precede muted link lists with an 8px vertical margin between rows. The bottom row places a small wordmark at left and social icons at right.

**States:** Declared: hover color becomes white at 90% opacity.

### Question panel

**Only for:** enterprise and product-led pages

**Use:** Objection handling in a neutral FAQ band.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 24px; max-width: 760px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `question` — DM Sans Variable 400 · 20px/1.3 · tracking -0.02em

**Observed:** Question at left, small chevron at right. The first panel is expanded with a paragraph; others remain compact. Panels are separated by 10px. Tool pages instead use 12px corners and 24px vertical gaps; pricing uses squarer 4px corners and subtle shadows.

### Upload panel

**Only for:** utility tool pages

**Use:** Immediate task entry instead of a decorative hero action.

**CSS:** `background: #fafafa; border: 2px dashed #e4e4e7; border-radius: 24px; width: 640px; height: 360px; padding: 80px 24px 24px; display: flex; flex-direction: column; align-items: center; justify-content: center`

**Observed:** A slim pale options row with a small switch spans the top. Centered upload icon, short instruction, file-format hint and compact teal file button form the task stack.

**Transfer:** Replace the file operation with the product's simplest useful task; keep settings subordinate.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side plan selection.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 4px 0px rgba(32,39,44,0.06); display: flex; flex-direction: column`

**Text style:** `question` — DM Sans Variable 400 · 20px/1.3 · tracking -0.02em

**Observed:** Three equal cards have faint blue-gray outlines; the recommended middle card gets a mint outline. Each has a 24px inset summary, plan name, audience, price, billing interval, full-width action and separated feature list. Entry action is blue, recommended action teal, sales action charcoal.

**Transfer:** Keep plan differentiation in the action color and edge rather than loud card fills.

## Imagery and graphics

### Playful hero ensemble

**Use:** Primary opening object opposite the large promise.

**Observed:** A group of brightly colored rounded characters with tiny limbs and expressive faces stands on white, without a surrounding frame. Mint, orange, yellow, pink and violet give the otherwise neutral opening its energy; soft shading makes the objects tactile.

**Transfer:** Create an original ensemble of product-relevant objects. A minimum equivalent is three to five simple geometric objects with rounded silhouettes and gentle shading, arranged at differing heights rather than a stock dashboard alone.

**Build:** Use SVG circles, rounded rectangles and soft triangles with two-tone shading and small dark facial details if appropriate. Arrange a taller central object behind smaller foreground objects across a 600×400px stage, leaving white negative space around the silhouette.

### Mint shape pile

**Use:** Signature illustrated closing panel.

**Observed:** Pale mint and brighter mint circles, an elongated oval, rounded triangles, capsules and soft hexagons form a loose stack across the bottom-right of a white panel. Shapes are flat and softly edged, without outlines or cast shadows; the group rises at the right while leaving the upper-left copy clear.

**Transfer:** Retain the abstract pile as an original geometric composition regardless of whether the product has rich illustration assets.

**Build:** Draw an SVG with a 975×326 viewBox. Combine about eleven shapes: two circles, one tall ellipse, two tilted capsules, two rounded triangles, a rounded quadrilateral and soft hexagons. Use rgba(0,221,179,0.25) and rgba(0,221,179,0.6), optionally softened further toward white; rotate individual shapes about 15–40 degrees. Anchor the group to the panel's bottom-right, touching the bottom edge and allowing some occlusion. Match the soft mint appearance; exact tonal stops are not essential.

### Interface demonstrations

**Use:** Bento cards and large dark stages throughout capability stories.

**Observed:** Real editor windows, timelines, comments, layer lists and asset grids are shown as purposeful fragments rather than entire browser desktops. Light workspace UI sits in gray feature cards, while dark editor UI sits inside charcoal stages. Colorful artwork remains visible inside the working canvas; floating tooltips and selection handles explain the operation.

**Transfer:** Show the new product doing one recognizable task per image. Use legible, simplified UI plus a concrete output object; do not replace every demonstration with generic icon art.

### Colorful proof gallery

**Use:** Social proof and creative output collections.

**Observed:** Tall 320×440px customer tiles and square output tiles carry intense, varied palettes inside 16px rounded frames. Galleries extend past the viewport edges and fade softly into the white canvas. Testimonials alternate quotes, small circular portraits and vivid branded work.

**Transfer:** Use authentic outcomes or original output samples with varied visual textures. Keep outer framing consistent even when subjects differ.

**Build:** Place fixed-width rounded tiles in horizontal flex rows with 16px or 24px gaps. Overlay 128px-wide white-to-transparent gradients at both outer edges. Keep illustration and photography inside the cards rather than coloring the page behind them.

### Isometric workflow machine

**Only for:** enterprise pages

**Use:** Explain a connected system and its production path.

**Observed:** A bright isometric machine and a larger connected workbench composition combine mint, blue and yellow platforms, miniature editor screens, controls and a few friendly characters. Fine dark outlines and crisp shaded side faces give the artwork a toy-machine quality on pure white.

**Transfer:** Represent the product's handoffs as two or three connected isometric workstations. The minimum version uses vector blocks, screens and connecting paths rather than a photorealistic factory.

**Build:** Construct three parallelogram platforms with shaded vertical edges, upright rectangular screens and a central cuboid. Connect the platforms with a short conveyor or path; use mint, blue and yellow faces, thin dark outlines and small circular controls.

### Before-after comparison

**Only for:** conversion and transformation product pages

**Use:** Demonstrate preserved quality or editable output.

**Observed:** A large square split image sits between smaller colorful example images. One half has a plain colored backing and the other a transparency checkerboard; a central circular handle and vertical split make the transformation immediately readable.

**Transfer:** Use a genuine before-and-after pair with a shared silhouette and a simple comparison handle.

### Trust emblem

**Only for:** security or responsible technology sections

**Use:** A compact reassurance moment distinct from the feature catalog.

**Observed:** A mint lock inside a layered shield sits at the right of a black rounded panel, opposite white copy and a mint link. Repeated translucent shield contours give it depth without an atmospheric background.

**Transfer:** Choose one recognizable reassurance symbol rather than a collage of badges.

**Build:** Layer three nested shield SVG paths using mint at decreasing opacity toward the outside. Center a simple rounded lock and shackle, with a dark interior field. Keep the symbol about 330px square and preserve generous negative space.

### Icons

**Observed:** Functional icons are mostly 24px outline SVGs with 2px rounded strokes. Header chevrons are 12px; small search and control icons are 16px. Benefit icons sit centered in 48px colored squares with 8px corners.

**Transfer:** Use a consistent rounded-stroke library for controls, and reserve filled or multicolor marks for real integrations and illustration.

## Section recipes

How recurring sections are built.

### First screen: Playful split opening

**Observed:** A white 64px sticky navigation bar sits above an inset two-column opening with 32px page gutters and 80px top padding. The left text block is slightly wider than half the stage: a 96px medium headline wraps across three lines, followed by a 24px gray paragraph after 24px and paired Primary button and Secondary button after 40px. A 600×400px Playful hero ensemble occupies the right, centered vertically against the copy with no container behind it. The white canvas is the back layer; art and copy sit directly on it; the four Benefit tiles form a full-width strip 64px below the hero row. Within the first 900px, the entire hero, both actions, object ensemble, benefit strip and beginning of the trust line are visible. The logo strip and case-study gallery continue below.

**Transfer:** Use a brief outcome promise and an original ensemble of product-relevant objects; if rich artwork is unavailable, use the simple geometric scene described in Playful hero ensemble. Enterprise openings use a 64px regular split headline, an eyebrow and an isometric machine. Product-family openings center a 96px regular headline above a dark tabbed demonstration. Utility pages center a 64px heading and place Upload panel immediately beneath it. Pricing opens with a centered 48px regular promise and three plan cards.

**Avoid:** Do not turn the default opening into a centered text-only banner, place the hero art in a gray card, or shrink the headline to ordinary section scale.

**Text style:** `display` — DM Sans LF 500 · 96px/1.04 · tracking -0.05em

### Centered heading pair

**Observed:** A 64px heading sits centered over a 20px muted support line, separated by 24px; the copy group is often 640–880px wide. One or two actions follow after 40px, and the demonstration starts after 64px. Business chapters use business-heading or business-display instead.

**Transfer:** Give each chapter one clear outcome before revealing details; keep the support narrower than the image grid.

**Text style:** `heading-lg` — DM Sans LF 500 · 64px/1.15 · tracking -0.04em

### Asymmetric capability bento

**Observed:** Feature card groups use 12px gutters, 24px corners and 32px copy insets. One broad card sits beside two compact stacked cards; subsequent rows can use two equal cards. Product media reaches the lower edge, while text remains in a consistent top band.

**Transfer:** Choose spans based on the demonstration's shape. Pair one substantial workflow with shorter supporting capabilities rather than three identical marketing blurbs.

### Tabbed dark demonstration

**Observed:** Dark island introduces a major workflow with a display-size heading, muted support and Demo selector. A Raised dark card below places explanation and a pale action on the left, with a large working interface on the right.

**Transfer:** Use this contained dark stage to make one important workflow feel tangible; keep the rest of the page light.

### Quantified proof playground

**Observed:** Dark island contains a centered 64px inverse heading, small monochrome technology marks and a tight 12px-gutter bento. Metric card values use the 48px heading recipe, with captions at the bottom. A taller comparison card uses horizontal pill bars, while larger cards mix code fragments with colorful output.

**Transfer:** Combine measured performance or business outcomes with a concrete demonstration; use comparative visual lengths only when the underlying data supports them.

**Text style:** `heading` — DM Sans LF 500 · 48px/1.15 · tracking -0.04em

### Golden capability spotlight

**Observed:** Golden spotlight carries a centered 64px black headline, dark support and pale secondary action. A black inner stage combines four small dark capability tiles on one side with a large vivid demonstration on the other.

**Transfer:** Use a single concentrated chapter to distinguish a new capability or category leap from the ordinary feature grid.

### Proof gallery

**Observed:** A centered heading and action introduce Colorful proof gallery. Large image cards, portrait-plus-quote cards and video cards alternate in a horizontal composition with soft edge fades; the work provides the visual saturation.

**Transfer:** Use customer evidence and concrete output rather than a uniform row of quotation cards.

### FAQ band

**Observed:** A full-width faint neutral band uses 80px vertical padding and a centered heading above a 760px question column. Question panel rows have white backgrounds, right-aligned chevrons and one expanded answer; tool variants increase row separation to 24px.

**Transfer:** Answer real adoption barriers and operational questions; use the first open answer to set a helpful, specific tone.

### Mint illustrated closing

**Observed:** Closing band wraps a 1376×400px white panel with 24px corners. Copy and action occupy the upper-left with 32px inset, while Mint shape pile occupies a 975×326px bottom-right area. A 48px headline and 20px support lead into the teal action. Longer business promises use compact-closing and a taller panel. The footer follows as an abrupt full-width dark canvas.

**Transfer:** End with a concise renewed promise and one action. Preserve the abstract mint illustration rather than replacing the panel with a generic centered CTA.

**Text style:** `heading` — DM Sans LF 500 · 48px/1.15 · tracking -0.04em

### Mission and directory footer

**Observed:** Footer canvas starts with a 32px medium two-line mission statement constrained to 350px. Outlined audience links sit below it; download badges occupy the other side. A 1px white-at-20% divider follows 96px below the top content, then a six-column directory with white 20px category headings and muted 16px links. The bottom row holds a small logo and copyright at left, social icons and a brief maker line at right; desktop padding is 64px vertically and 32px horizontally.

**Transfer:** Use an inclusive product belief, two relevant audience paths and a disciplined directory. Preserve the generous dark top tier and compact bottom signature rather than ending at the CTA.

**Text style:** `footer-statement` — Inter LF 500 · 32px/1.1

### Transformation tool ending

**Only for:** utility tool pages

**Observed:** After FAQ band, a 32px-corner dark split panel cross-promotes a related capability: text and a small teal action on the left, a bright vector portrait with selection handles and a prompt callout on the right. Footer canvas then closes the page.

**Transfer:** Use a relevant next task rather than the default closing shape panel when the user has arrived to complete a single utility operation.

## Page flow

**Storyline:** Promise → tangible output → trust → capability chapters → quantified or customer proof → adoption reassurance → renewed action → mission and directory.

### Broad platform marketing

1. **Promise** — Split oversized headline, character ensemble and four benefit tiles.
2. **Social proof** — Muted trust statement, monochrome logos and colorful tall customer cards.
3. **Product demonstration** — Searchable output gallery, dark tabbed editor stage and asymmetric workflow bento.
4. **Capability chapters** — Split asset story, dark performance bento and golden capability spotlight.
5. **Customer proof** — Mixed output, portrait quotation and video gallery.
6. **Closing call** — White mint-shape panel on a gray band, then mission-led dark directory.

**Transfer:** Use the visual rhythm of open canvas, contained demonstrations and colorful proof without requiring the same number of chapters.

### Plan selection and commercial evaluation

1. **Promise and pricing** — Centered regular-weight benefit headline, trust line and three equal white plan cards.
2. **Value justification** — Outcome cards with large metrics and a framed resource promotion.
3. **Capability proof** — Three-column feature illustrations, case-study carousel, compact feature list and integration tile rows.
4. **Plan comparison** — Wide table with compact plan actions and a faint mint recommended column.
5. **Objection handling** — Narrow question stack on a faint canvas.
6. **Closing call** — Full-width teal illustrated conversion band followed by the shared dark directory.

**Transfer:** Make the buying choice early, then give enough product and operational proof to justify it.

### Enterprise adoption and organizational alignment

1. **Promise** — Regular 64px split headline, sales and tour actions, isometric machine and trusted logos.
2. **Problem framing** — Two-column narrative and a structured requirements matrix.
3. **Capability chapters** — Governed workflow bento, numbered progression beside a live example and connected-workbench illustration.
4. **Adoption reassurance** — Pale rounded AI and governance chapters with explicit operational controls.
5. **Business proof** — Three-column case-study cards connect vivid outcomes with business-case captions.
6. **Objection handling and closing** — Detailed FAQ, mint shape closing with paired actions, then shared mission and directory.

**Transfer:** Lead with organizational outcomes and address ownership, controls and rollout without removing the playful product illustrations.

### Product-family education and exploration

1. **Promise** — Centered 96px headline above a black tabbed product demonstration.
2. **Trust** — Muted adoption statement and logos.
3. **Capability chapters** — Centered labeled chapter leads, gray feature bento, split guide panel and large working examples.
4. **Output proof** — Theme demonstration, before-after conversion and colorful generated-output gallery.
5. **Trust and objection handling** — Black shield reassurance panel followed by white FAQ cards on a faint band.
6. **Closing call** — Short promise in the mint shape panel and shared dark directory.

**Transfer:** Repeat a recognizable chapter language while changing the demonstration type to suit each capability.

### Immediate single-task utility

1. **Task entry** — Scrollable tool navigation, centered 64px promise and upload panel.
2. **Ease and confidence** — Small proof metrics followed by three numbered steps.
3. **Capability proof** — Six illustrated feature cards, split integration promotion and compact developer-access card.
4. **Objection handling** — Narrow FAQ stack in a faint full-width band.
5. **Next task and ending** — Related capability in a dark illustrated split panel followed by the shared mission and directory.

**Transfer:** Put a usable operation before the long marketing explanation; keep the latter useful for users who need reassurance.

## Writing

Friendly, enabling and concrete. Enthusiastic creative promises are supported by practical workflow language, named controls and straightforward benefits rather than abstract futurism.

**Do not copy:** Do not reuse the source brand names, mascots, logos, customer artwork, testimonials, adoption figures, prices, performance claims or privacy promises. Replace them with original assets and verified claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you or your team; use we sparingly for a belief or a helpful offer. Product names appear when a specific tool or workflow needs identification.
- **Rhythm:** Headlines are short sentence-case promises, sometimes with a punchy sequence of verbs. Supporting copy usually fits one to three sentences. The default opening can use an exclamation mark, but instructional and enterprise copy remains matter-of-fact.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | An energetic creative outcome or a plain production benefit. | 5–10 words | “Great designs come alive with motion!”<br>“Motion that makes it to production” |
| Capability headline | Name the useful result with an active verb; keep the mechanism subordinate. | 5–11 words | “Turn ideas into vectors in seconds”<br>“Implement your animations in just a few clicks” |
| Support | List concrete operations and contexts in an approachable sentence. | 15–40 words | “Create, manage and implement lightweight animations across websites, apps, presentations, social and more.” |
| Primary action | Verb plus object or a low-friction entry promise. | 2–5 words | “Get started for free”<br>“Watch product tour” |
| Closing promise | A compact sequence of actions, or reassurance that makes the next step manageable. | 3–9 words | “Create, collaborate and ship.”<br>“You don't have to systematize motion overnight” |
| FAQ answer | Start with a specific small step, then explain how it scales. | 2–4 sentences | “Start with one product moment where motion has a clear job: explain progress, confirm success, prevent a mistake, or guide an action.” |

**Words and phrasing to use:** create; customize; manage; ship; your team; ready-to-use; get started; in just a few clicks; workflow; keep control

**Avoid:** revolutionary paradigm; disrupt everything; unprecedented synergy; autonomous magic; frictionless transformation without explanation

**Rules:**

- Pair broad creative promises with concrete operations in the supporting line.
- Explain control, editability and handoff when introducing automation.
- Write card titles as useful capabilities rather than slogans.
- Keep action labels explicit about their destination or next operation.
- Use metrics as proof with context, not isolated decoration.

## Do's and Don'ts

### Do

- Keep default opening type at 96px, weight 500, with -0.05em tracking.
- Use 32px desktop gutters so the largest inset panels read as 1376px islands.
- Pair 48px teal and white actions with a 16px gap.
- Use 24px feature-card corners inside larger 48px chapter islands.
- Give interface proof substantial space: one large working example beats many tiny thumbnails.
- Retain the mint geometric pile in the default closing panel.
- Keep footer links at 16px and category headings at 20px, with the 32px mission above them.
- Let customer work carry varied saturated palettes inside consistent rounded frames.

### Don't

- Do not turn all headings into weight 700; the rounded medium and regular cuts are central to the tone.
- Do not make conversion buttons full pills; 12px corners distinguish them from circular controls and comparison bars.
- Do not use teal as a wash across every section; preserve the white and gray framework.
- Do not make every feature card the same height and span when the workflow needs asymmetric emphasis.
- Do not add broad blurred shadows to feature cards; most of the hierarchy comes from flat fills and nested contrast.
- Do not substitute moody photography for the bright object illustrations and practical product demonstrations.
- Do not apply the pricing page's full-width teal closing band to ordinary landing pages.
- Do not end with only a small copyright row; preserve the mission tier and substantial dark directory.

## Motion and responsive

### Motion

**Observed:**

- Controls declare 0.15s cubic-bezier(.4,0,.2,1) color and box-shadow transitions; other surfaces declare 0.2s or 0.3s all-property transitions.
- Illustration elements declare float-bob 3s ease-in-out; gallery slide and slide-reverse animations are declared at 100s linear infinite.
- Horizontal gallery edge fades and demo rails accompany the moving visual content.

**Transfer:**

- Use slow continuous gallery drift and restrained bobbing to keep the playful artwork alive while headline and controls remain stable.
- Keep the immediate button feedback to the declared short color and shadow changes rather than large scale effects.

**Unknown:**

- Exact movement paths and autoplay behavior of canvas demonstrations are not established.

### Responsive

**Observed:**

- Core layout CSS declares 640px and 1024px breakpoints. Hero layout switches from a vertical stack to a row at the larger breakpoint; page gutters switch from 16px to 32px.
- The closing panel declares 480px height on narrow layouts and 400px on desktop; its shape art uses 680px width and 200px height on narrow layouts, offset horizontally by 40px.
- Footer directory declares two columns, then three, then six visible groups as width increases.

**Transfer:**

- Stack the promise and illustration on narrow screens, preserving the visual object instead of deleting it.
- Keep the mint pile bottom-right and clipped within the taller closing panel, leaving a clear upper copy area.
- Allow tool rails and galleries to scroll horizontally rather than squeezing every item into a row.

**Unknown:**

- Exact mobile headline recipes and all narrow-screen image compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
