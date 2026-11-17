# ClickHouse — highlighter meets infrastructure

## Overview

A dark technical marketing style with the energy of a fluorescent highlighter rather than a futuristic chrome aesthetic. Olive-black grounds, acid yellow punctuation, sturdy grotesk headlines and practical sans-serif text give complex products an approachable, developer-facing character. Diagrams, restrained interface illustrations and human video proof carry the story; spacious section breaks surround fairly dense cards and resource lists.

### Essentials

- A plainspoken promise gets billboard scale without ornamental typography: the default opening uses basier 600 at 96px/1, normal tracking, centered in two lines, with a 24px/32px support line.
- The opening is a promise, not a giant dashboard: a 77px translucent navigation bar, 96px top breathing room, paired 46px actions, then a narrow announcement strip and a moving logo field within the first 900px.
- Conversion controls look like small engineered rectangles: 4px corners, 12px 24px padding and 16px/20px medium text; pills are reserved for filters and selectors.
- Fluorescent yellow interrupts an overwhelmingly dark page: #faff69 marks actions, diagram routes and proof cards, and expands into a full-width decision band. Preserve at least one substantial yellow proof or decision surface rather than sprinkling yellow over every card.
- Technical explanation becomes a luminous network: dark rectangular nodes, thin yellow orthogonal connectors and a glowing central hub. Include this visual device; a simple SVG system diagram is the fallback when there is no product interface to show.
- Headlines occasionally receive a physical highlighter patch: one short phrase on a slightly tilted contrasting rectangle, yellow behind dark text or dark behind white text on yellow. Carry this device into a section lead or closing call without recoloring the whole headline.
- The page lands with a bright invitation and practical escape hatch: a 36px/45px centered heading on a yellow panel with a dark 46px button, an attached dark alternative-access strip where applicable, then a dense five-column footer and newsletter area.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Fluorescent yellow | `#faff69` | `--color-primary` | accent, action, link, background | Primary actions, emphasis patches, diagram nodes, quote cards and decision bands. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted olive edge | `#4f5101` | `--color-secondary-edge` | border | Outline for secondary actions and pill filters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-heading` | text | Headlines and labels against dark surfaces. |
| Light grey | `#dfdfdf` | `--color-body` | text | Paragraphs on dark backgrounds. |
| Secondary grey | `#a0a0a0` | `--color-muted` | text | Lead paragraphs, footer links and secondary explanations. |
| Graphite | `#414141` | `--color-band` | surface, border | Value and learning chapter bands, technical nodes, and the source hue for 80% card edges. |
| Soft card edge | `#383838` | `--color-card-edge` | border | Visible result of #414141 at 80% on the dark base. |
| Olive end of canvas | `#292924` | `--color-canvas-light` | background | Lighter end of the page's 275deg horizontal gradient. |
| Panel grey | `#282828` | `--color-panel` | surface | Command panels; full-width chapter ground on solution and company pages. |
| Footer separator | `#212120` | `--color-footer-rule` | border | Visible result of #a0a0a0 at 10% on the base; legal-row separator. |
| Subtle white rule | `#1f1f1e` | `--color-soft-rule` | border, surface | Visible 5% white wash on the base; navigation rule and technical card wash. |
| Olive charcoal | `#1f1f1c` | `--color-olive-panel` | surface | Inset value panels and dark cards on yellow bands. |
| Deep neutral | `#151515` | `--color-deep-panel` | surface, text | Footer canvas and primary-button ink; source hue for translucent dark cards and header. |
| Olive-black base | `#131312` | `--color-canvas` | background | Underlying page canvas. |
| Black end of canvas | `#0f0f0f` | `--color-canvas-dark` | background | Darker end of the page gradient. |
| Black ink | `#000000` | `--color-ink` | text | Headings, quotes and body text on bright bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical capability cards | Raised white edge | `#424241` | `--color-strong-rule` | border | Visible 20% white edge on the base. |
| partner or ecosystem spotlights | Warm paper | `#f3f2ef` | `--color-paper` | background | Editorial partner-feature band with dark text. |

## Typography

- **basier** — Headlines and card headings. Sturdy contemporary grotesk with a high x-height, open counters and rounded forms; mostly semibold rather than ultra-heavy. If unavailable, use **Inter**. Use 600 for display and 700 only for the heavier card cut; preserve normal tracking. Font stack: "basier", "Inter", Arial, sans-serif.
- **Inter** — Body text, navigation, buttons, quotes and large proof numerals. Practical neutral sans with readable compact text and crisp numerals. Font stack: "Inter", Arial, sans-serif.
- **Inconsolata** — Executable commands and diagram labels. Narrow, readable monospace that introduces a utilitarian technical note. Font stack: "Inconsolata", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | basier | 600 | 96px | 1 | normal | Default marketing opening; two-line centered promise. |
| stat | Inter | 700 | 72px | 1 | normal | Unboxed proof numerals. |
| heading | basier | 600 | 36px | 1.25 | normal | Section leads and closing invitations. |
| hero-support | Inter | 400 | 24px | 32px | normal | Support directly beneath the default display headline. |
| quote | Inter | 400 | 24px | 1.5 | normal | Large centered quotations beneath human video proof. |
| stat-label | Inter | 700 | 24px | 1.375 | normal | Yellow labels beneath proof numerals. |
| subheading | basier | 600 | 20px | 1.25 | normal | Value statements and secondary card titles. |
| feature-heading | basier | 700 | 20px | 1.25 | normal | Primary feature-card titles. |
| lead | Inter | 400 | 18px | 1.5 | normal | Secondary openings and customer-proof introductions. |
| body | Inter | 400 | 16px | 1.5 | normal | Paragraphs, lists and accordion questions. |
| button | Inter | 500 | 16px | 1.25 | normal | Main conversion actions. |
| text-link | Inter | 700 | 16px | 1.5 | normal | Feature-card exploration links. |
| command | Inconsolata | 600 | 16px | 1.5 | normal | Copyable installation commands and technical diagram labels. |
| compact-action | Inter | 500 | 14px | 1.25 | normal | Small actions and filter chips. |
| navigation | Inter | 500 | 14px | 20px | normal | Top-level navigation. |
| caption | Inter | 400 | 14px | 20px | normal | Footer links and control text. |
| eyebrow | Inter | 600 | 14px | 1.5 | 0.025em, uppercase | Yellow section labels and trust-strip captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | basier | 700 | 50px | 1.5 | normal | Cost-estimator total. |
| product, solution, pricing and company pages | secondary-display | basier | 600 | 48px | 1.25 | normal | Smaller category-specific opening headings. |
| pricing pages | plan-heading | basier | 600 | 31.5px | 1.25 | normal | Centered plan titles. |
| pricing pages | price-caption | Inconsolata | 400 | 18px | 1.5 | normal | Yellow caption over cost-estimator total. |
| company history pages | timeline-year | basier | 600 | 16px | 1.25 | normal | Years aligned beside a thin timeline. |

**Notes:**

- Keep normal tracking even at display scale; the heavy impression comes from size and weight, not condensed letter spacing.
- Section hierarchy drops sharply from 96px display to 36px section headings and 20px card headings; body copy stays at 16px.
- Use white headings, light grey paragraphs and muted grey leads; switch to black text on yellow. Highlight patches change the backing, not the type recipe.
- Monospace is a technical annotation voice, not the general body or eyebrow font.

## Layout

**Density:** Airy chapters with compact internal content: large breaks between sections, close heading-support relationships and information-rich panels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-label gaps and tight control stacks. |
| 16px | Heading-to-paragraph spacing and internal feature rhythm. |
| 24px | Action separation, card padding, filter spacing and common grid gutters. |
| 32px | Container side padding and medium panel gaps. |
| 40px | Large testimonial padding and footer newsletter separation. |
| 48px | Split-column gutter and default hero support-to-action spacing. |
| 64px | Section-heading-to-content gap and bright callout vertical padding. |
| 96px | Major section margins and band vertical padding. |

### Containers and grids

- **container**: max width 1280px · side padding 32px. Centered outer container; 1216px usable content at a 1440px desktop width.
- **reading measure**: max width 768px. Centered section support, secondary openings and closing invitation text.
- **feature grid**: 4 columns · gap 16px. Default feature cards: equal-height, icon-led columns.
- **proof split**: gap 48px. A roughly 40% sticky introduction beside a roughly 60% stack of bright media-proof cards.
- **comparison pair**: 2 columns · gap 64px. Equal diagram examples with headings and explanatory paragraphs below.
- **decision grid**: max width 800px · 2 columns · gap 24px. A wide dark choice spanning both columns above two narrower alternatives on a yellow ground.
- **faq measure**: max width 672px · gap 24px. Question list beside a narrower explanatory column.
- **capability grid** (only for technical product pages): 3 columns · gap 32px. Technical capabilities in a two-row grid.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and question rows | 4px |
|  | cards and callouts | 8px |
|  | filter chips | 9999px (pill) |
| technical product pages | technical icon wells | 6px |
| technical architecture diagrams | large architecture frame | 16px |
| company leadership pages | portrait circles | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | small card | `0px 1px 3px 0px rgba(0, 0, 0, 0.1), 0px 1px 2px -1px rgba(0, 0, 0, 0.1)` | Default dark feature cards; subtle, not the primary separator. |
|  | luminous hub | `0px 4px 60px 0px #faff69` | A central technical node, not every card. |
| pricing pages | recommended plan | `0px 25px 50px -12px rgba(250, 255, 105, 0.2)` | Selected plan emphasis. |

### Surfaces

#### Canvas · level 0

**Use:** Default page ground.

**CSS:** `background-color: #131312; background-image: linear-gradient(275deg, #292924 0%, #0f0f0f 100%); color: #dfdfdf`

**Observed:** A very dark horizontal shift from olive charcoal to black, not a flat blue-black background.

**Transfer:** Let this remain visible between self-contained bands.

#### Dark card · level 1

**Use:** Default feature and question-panel material.

**CSS:** `background: rgba(21, 21, 21, 0.5); border: 1px solid rgba(65, 65, 65, 0.8); border-radius: 8px`

**Observed:** Low-opacity neutral fill allows the warm page tone through; the outline does most of the separation.

**Transfer:** Use for grouped information rather than a bright elevated dashboard aesthetic.

#### Graphite chapter · level 0

**Use:** Value and learning chapters.

**CSS:** `background: #414141; padding: 96px 0px`

**Observed:** Full-width medium-dark band surrounding a deeper inset panel or media-and-copy composition.

**Transfer:** Use to interrupt the dark gradient without switching to a light theme.

#### Olive inset · level 1

**Use:** Value panel and choices within a bright decision band.

**CSS:** `background: #1f1f1c; border-radius: 4px; padding: 64px`

**Observed:** A dark inset value panel has a thin yellow gradient rule along its upper edge; decision cards use 8px corners and 32px padding.

**Transfer:** Keep the material matte; emphasize edges rather than heavy shadows.

#### Yellow interruption · level 1

**Use:** Proof, decisions and closing invitations.

**CSS:** `background: #faff69; color: #000000; border-radius: 8px`

**Observed:** Yellow can fill an entire chapter or a large panel. It is not limited to tiny accents.

**Transfer:** Reserve this material for meaningful proof or choice moments.

#### Technical wash · level 1

**Only for:** technical capability cards

**Use:** Product capability grids.

**CSS:** `background: rgba(255, 255, 255, 0.05); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 8px; padding: 24px`

**Observed:** More translucent and visibly edged than the default dark feature cards.

**Transfer:** Keep the typography and rhythm consistent while changing only the material.

#### Paper spotlight · level 0

**Only for:** partner or ecosystem spotlights

**Use:** Contrasting editorial product feature.

**CSS:** `background: #f3f2ef; color: #000000`

**Observed:** Warm light band with a two-column text-and-interface composition.

**Transfer:** Use only for a distinct ecosystem or editorial chapter, not as a second default theme.

## Components

### Navigation

**Use:** Persistent orientation and compact conversion action.

**CSS:** `position: sticky; top: 0px; height: 77px; background: rgba(21, 21, 21, 0.8); border-bottom: 1px solid rgba(255, 255, 255, 0.05); backdrop-filter: blur(8px); z-index: 9999`

**Text style:** `navigation` — Inter 500 · 14px/20px

**Observed:** Logo left; six short navigation labels across the middle; search, terminal, locale, community count and sign-in utilities on the right before a yellow compact action. Menu items have 8px corners and 10px 16px padding.

**States:** Declared: hover navigation labels become fluorescent yellow over a 25% graphite wash; focus-visible not specified; active not specified.

### Primary button

**Use:** Default high-intent action on dark ground.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: #faff69; color: #151515; border: 1px solid #faff69; border-radius: 4px; padding: 12px 24px; height: 46px`

**Text style:** `button` — Inter 500 · 16px/1.25

**Observed:** Label centered; compact navigation and card versions use 14px text with 10px 16px padding and 40px height. On bright callouts, invert to a 90% deep-neutral fill with white text and transparent border; on the main wide decision card the button is white.

**States:** Declared: hover and active yellow fills and borders become a stronger yellow; focus-visible not specified. The inverted dark variant becomes opaque deep neutral on hover and active.

### Secondary button

**Use:** Documentation, sales or alternative access alongside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; background: rgba(21, 21, 21, 0.01); color: #ffffff; border: 1px solid #4f5101; border-radius: 4px; padding: 12px 24px; height: 46px; backdrop-filter: blur(16px)`

**Text style:** `button` — Inter 500 · 16px/1.25

**Observed:** A faint olive outline rather than a bright grey outline. Small versions retain the rectangle but use the compact action recipe.

**States:** Declared: hover and active strengthen the olive-yellow border and apply an 80% panel-grey background; focus-visible not specified.

### Arrow text link

**Use:** Exploration link at the foot of a feature card.

**CSS:** `color: #faff69; font-weight: 700`

**Text style:** `text-link` — Inter 700 · 16px/1.5

**Observed:** Short verb-led label followed by a small right arrow; the feature-card label is heavier than ordinary inline links. Paragraph links use regular body or 14px supporting text and underline on hover.

### Feature card

**Use:** Default four-column capability introduction.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: rgba(21, 21, 21, 0.5); border: 1px solid rgba(65, 65, 65, 0.8); border-radius: 8px`

**Text style:** `feature-heading` — basier 700 · 20px/1.25

**Observed:** Large yellow outline icon in a rounded square above title and paragraph; 24px inner content padding. Arrow text link sits at the bottom in a separate padded region so card actions line up.

**Transfer:** Use concise benefits of comparable depth; retain an icon, title, paragraph and bottom action.

### Video proof card

**Use:** Human customer proof as a substantial bright panel.

**CSS:** `background: #faff69; color: #000000; border-radius: 8px; padding: 40px; margin-bottom: 44px`

**Text style:** `quote` — Inter 400 · 24px/1.5

**Observed:** Wide 16:9 video thumbnail first, centered quote below with a 32px gap, then bold attribution. Speaker imagery retains warm stage light. A dark circular play control with yellow triangle floats at the media center.

**Transfer:** Use real customer speech. If no video is available, stage a real portrait or relevant work image in the same wide frame above the quote.

### Filter chip

**Use:** Category navigation beside proof content.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(21, 21, 21, 0.01); color: #ffffff; border: 1px solid #4f5101; border-radius: 9999px; padding: 10px 16px; height: 40px; backdrop-filter: blur(16px)`

**Text style:** `compact-action` — Inter 500 · 14px/1.25

**Observed:** Wrapping cluster under an uppercase yellow label; pills are small and outlined, not large filled topic badges.

**States:** Declared: hover and active strengthen the olive-yellow border and add an 80% panel-grey background; focus-visible not specified.

### Numbered accordion

**Use:** Objection handling and technical details.

**CSS:** `display: grid; grid-template-columns: auto 1fr; background: rgba(21, 21, 21, 0.5); border: 1px solid rgba(65, 65, 65, 0.8); border-radius: 4px; padding: 16px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Default question rows are 58px tall with 24px gaps. A muted two-digit number has a right divider; question text follows with 16px left padding and a plus at the far right. Technical-detail versions omit the number.

### Closing invitation

**Use:** Bright conversion panel before the footer.

**CSS:** `background: #faff69; color: #000000; border-radius: 8px 8px 0px 0px; padding: 64px 16px`

**Text style:** `heading` — basier 600 · 36px/1.25

**Observed:** Centered heading, short support line 16px below and dark primary-button variant after 24px. A single highlighted word reverses white-on-dark. The default has a dark bottom strip with 24px 48px padding, side and bottom outlines, lower 8px corners, alternative access text and a Command panel. Standalone variants close all four corners; pricing uses a dark panel with the normal yellow action.

**Transfer:** Keep the invitation concrete and low-risk. Adapt the attached strip to an alternative way to use or evaluate the product; do not add a fake command for a nontechnical product.

### Command panel

**Use:** Alternative self-managed installation access.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #282828; border: 1px solid rgba(65, 65, 65, 0.4); border-radius: 8px; padding: 24px 32px`

**Text style:** `command` — Inconsolata 600 · 16px/1.5

**Observed:** A single executable line with yellow prompt marker and a copy icon at the right, beside explanatory alternative-access text.

**Transfer:** Provide a valid command or replace this panel with an equally concise real access instruction.

### Footer

**Use:** Dense utility navigation after the closing invitation.

**CSS:** `background: #151515; padding: 64px 0px 32px`

**Text style:** `caption` — Inter 400 · 14px/20px

**Observed:** Five narrow link columns occupy about two thirds of the container; the right side holds logo, newsletter description, dark email field with inset yellow sign-up button, and outlined community action. Column titles are bold 14px/20px; links are muted with 6px vertical margins. A faint ruled legal row follows after 44px and has 32px top padding.

**States:** Declared: hover footer links become white; focus-visible and active not specified.

### Plan card

**Only for:** pricing pages

**Use:** Comparable service tiers.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: rgba(21, 21, 21, 0.5); border: 1px solid #faff69; border-radius: 8px; box-shadow: 0px 25px 50px -12px rgba(250, 255, 105, 0.2)`

**Text style:** `plan-heading` — basier 600 · 31.5px/1.25

**Observed:** Three equal cards with 24px content padding: centered title and description, full-width yellow compact action, checklist, feature-expansion link, ruled lower section with two separately metered prices, then an outlined estimation action. Recommended middle tier gets yellow border and soft glow; the other tiers use the normal dark-card edge.

## Imagery and graphics

### Luminous system graph

**Use:** Signature technical explanation somewhere within a marketing page.

**Observed:** A broad diagram nearly fills the usable container: matte dark center hub surrounded by smaller grouped nodes, thin yellow orthogonal arrows and small directional captions. The hub has an acid-yellow halo; external ecosystem marks retain their own colors while diagram structure stays neutral and yellow.

**Transfer:** Represent how the new product connects people, inputs or services. Minimum version: one central product node, grouped input and output nodes and real labeled connectors, with generic outline symbols instead of borrowed logos.

**Build:** Use a responsive SVG viewBox with a centered rounded rectangle occupying roughly one third of diagram width, two stacked nodes on each side and an optional node below. Use 1px yellow orthogonal paths and small arrowheads; back the center with a rounded rectangle shadow of 0px 4px 60px yellow. Keep 8px node corners, dark olive fills, and neutral dashed inner modules.

### Comparative data animation

**Use:** Paired mechanism explanations.

**Observed:** Two wide dark diagram frames, each about 544px by 264px, show ordered grids of tiny yellow and coral cells. Column captions and table headings stay small; explanatory headings and paragraphs sit outside the frames below.

**Transfer:** Show a tangible before-and-after mechanism with aligned small units rather than a generic abstract chart.

**Build:** Create two SVG grids of rectangular cells with narrow gutters. Fill most active cells yellow, a minority coral; use dark inactive cells. In the first group scatter the coral units across rows; in the second align them into selected columns. Keep the surrounding border faint and the page-level coral glow soft.

### Atmospheric light

**Use:** Warm emphasis behind technical explanation and questions.

**Observed:** Broad low-contrast coral light pools soften the dark page without becoming a separate colorful card. The background remains readable as black and olive.

**Transfer:** Keep the glow behind content and edges, not on the type. Match the soft light; exact gradient stops are not essential.

**Build:** Place a pointer-events-none pseudo-element behind the chapter near its left third and vertical center. Use a large radial coral wash at about 7% opacity, fading to transparent across roughly 800px with generous spread. Clip to the section so adjacent typography remains unaffected.

### Highlighter patch

**Use:** Signature emphasis in one phrase within a heading or support statement.

**Observed:** A slightly tilted rectangle under a word or short phrase, tight to the text. Dark pages use yellow backing and black text; yellow closing panels reverse to dark backing with white text.

**Transfer:** Highlight the actual differentiating phrase, not arbitrary filler.

**Build:** Wrap the phrase in a position-relative inline span. Put a solid contrasting rectangle behind it using a pseudo-element skewed or rotated slightly counterclockwise, leaving about 5px horizontal breathing room at 36px text and about 7px at 48px. Leave the glyphs themselves upright.

### Human proof

**Use:** Media in Video proof card.

**Observed:** Wide speaker frames with warm yellow stage lighting, little visual decoration and a centered play button. Bright surrounding card color ties the human material to the technical palette.

**Transfer:** Use real people with warm but natural light and clean framing; retain the 16:9 media ratio.

### Product light stage

**Only for:** flagship technical product openings

**Use:** A product-centric variant of the opening.

**Observed:** A horizontal acid-yellow light ribbon sweeps through the lower hero behind overlapping dark interface windows and floating result cards. A barely visible square-dot field sits over the dark ground. Text remains centered above the strongest light; the interface extends below the fold.

**Transfer:** Use one credible task and result from the new product. Keep the actual interface legible but subordinate to the promise; do not turn every marketing opening into this more theatrical variant.

**Build:** Layer a 10px repeating SVG tile containing a 2px square at 4% white opacity over the dark ground. Behind a dark interface frame, draw several broad yellow curved SVG strokes with varied width and 24px–64px blur, concentrated in the lower half. Add a diffuse amber-yellow lobe on the right and a few dark result cards over the frame.

### Solution illustration

**Only for:** solution landing pages

**Use:** Right-hand illustration beside a practical benefit checklist.

**Observed:** Overlapping dark browser and analytics panels with simplified grey bars, yellow accents, a muted multicolor donut and soft olive diagonal backing. The image occupies roughly the right two fifths of the hero and does not look photorealistic.

**Transfer:** Illustrate the new product's tangible workflow with two or three flat overlapping panels, not glossy 3D objects.

**Build:** Construct two offset rounded rectangles with faint borders; add a browser bar, grey rounded text lines and one simple chart. Place a translucent olive quadrilateral behind the panels to suggest a shallow diagonal beam.

### Company photography and map

**Only for:** company and culture pages

**Use:** People, history and distributed-team context.

**Observed:** A large black-and-white team photograph follows introductory text. Historic people photography is grayscale with a narrow acid-yellow silhouette offset; leadership portraits are circular grayscale images at 208px. A dotted grey world map uses small yellow glowing location points.

**Transfer:** Use authentic people and real locations. Preserve monochrome photography and restrained yellow annotations rather than decorative corporate stock photography.

**Build:** For the silhouette treatment, mask a second copy of the subject, fill it yellow and offset it slightly behind the grayscale photo. For a distribution graphic, clip a regular grey dot grid to the relevant map or region silhouette and place small yellow circles with soft halos at real locations.

### Icons

**Observed:** Simple rounded line SVGs: utility icons mostly 16px with 2px round strokes; feature marks use yellow outlines at 48px and small technical card icons use 24px with 1.5px round strokes. Icons often sit in thin outlined square wells; checks and right arrows punctuate lists and links.

**Transfer:** Use one consistent outline set with rounded caps. Reserve filled triangles for video play; keep category icons yellow and utilities grey or white.

## Section recipes

How recurring sections are built.

### First screen: Promise opening

**Observed:** Canvas behind Navigation, then a centered two-line display headline in the upper half with 96px breathing room below the navigation. The headline reads as about half the viewport width while its centered container spans 1216px; it uses 96px/1 semibold white text, not a gradient fill. Hero-support sits 16px below; Primary button and Secondary button are centered 48px later with a 24px horizontal gap. There is no main product object in this default opening: the type is the focal object. A 98px dark announcement strip with small marks and two concise updates bridges into a graphite-tinted logo field. In the first 900px the headline, support, actions, announcements, trust caption and at least one logo row are visible; capability cards begin below the fold. Layers stay simple: dark gradient, type and actions, translucent strip, then logo proof.

**Transfer:** Lead with an equally concise category promise and use real proof marks or short verified proof labels below. Product-centric openings use secondary-display and Product light stage; solution openings left-align secondary-display and a checklist beside Solution illustration. Pricing opens with a compact centered title and plans; company pages open with centered introduction and photography.

**Avoid:** Do not insert a giant dashboard above the announcement strip in the default opening, stretch the heading into one tiny line, or add decorative gradient lettering.

**Text style:** `display` — basier 600 · 96px/1

### Heading pair

**Observed:** A yellow uppercase eyebrow precedes a centered 36px/45px heading by 16px. A short light-grey paragraph follows by 16px within a 768px reading measure; cards or artwork follow after 64px.

**Transfer:** Name the chapter briefly, make the heading an outcome or clear question and support it with one grounded explanation.

**Text style:** `heading` — basier 600 · 36px/1.25

### Feature grid

**Observed:** Heading pair above four Feature cards with 16px gutters. Strong outline icons precede titles and short paragraphs; bottom Arrow text links align. The technical variant uses three columns, 32px gutters and Technical wash surfaces.

**Transfer:** Keep parallel grammatical structures and comparable copy depth across cards.

### Sticky human proof

**Observed:** Proof split holds a 36px left introduction, muted 18px lead and Filter chips beside a tall stack of Video proof cards. The left introduction stays near the sticky navigation while the reader moves through the proof.

**Transfer:** Use a few substantial customer stories, with filtering only when it serves actual content. A small library can retain the split without filters.

### Value enclosure

**Observed:** Graphite chapter encloses Olive inset with a 3px yellow gradient rule at its upper edge. Centered heading and support introduce three unboxed value columns at 48px gutters, then five bright small value tiles at 24px gutters and a short closing text link.

**Transfer:** Translate the value tiles to concrete product qualities. Keep the contrast of unboxed explanations and bright compact proof tiles; adapt the number of items to actual content.

### Mechanism chapter

**Observed:** Heading pair above Luminous system graph or a Comparison pair. Diagrams are the dominant media and their explanations sit outside rather than over them. A centered Secondary button can end the chapter.

**Transfer:** Make the diagram reveal one real mechanism. Simplify labels before shrinking them.

### Yellow choice band

**Observed:** Full-width Yellow interruption with black centered heading and support; Decision grid places one wide Olive inset choice above two smaller dark alternatives. The wide option uses a white full-width action; the narrow alternatives use Secondary button.

**Transfer:** Use for deployment, access paths or other meaningful product choices, not only technical infrastructure.

### Unboxed quantified proof

**Observed:** A 36px statement and small outlined community icons sit on the left; four unboxed 72px/1 white numerals form a staggered two-by-two group on the right with 24px bold yellow labels. A short inline number in the statement receives Highlighter patch.

**Transfer:** Use verified scale or participation metrics; preserve the spacious irregular alignment rather than turning these into matching cards.

**Text style:** `stat` — Inter 700 · 72px/1

### Questions and practical close

**Observed:** A left heading and short helpful explanation sit beside Numbered accordion at 672px measure. Atmospheric light warms the section. Closing invitation follows, then Footer; the alternative Command panel strip attaches only to the invitation, not the footer.

**Transfer:** Address real buyer uncertainty and give a usable next step. A nontechnical offering can use a booking or evaluation alternative instead of a command.

### Pricing workspace

**Observed:** Secondary-display title and muted lead above three Plan cards and a provider-region selector. An estimator uses a 736px form area beside a 368px dark summary with yellow border and 28px padding. Form controls are 40px tall, 4px corners, panel-grey fills and graphite edges; the summary has a yellow monospace caption above a 50px total. A full-width yellow principles band precedes numbered questions and a dark closing call.

**Transfer:** Make both the pricing model and the assumptions behind an estimate visible; keep the prominent summary adjacent to editable inputs.

**Text style:** `secondary-display` — basier 600 · 48px/1.25

### Company narrative

**Observed:** Centered secondary-display title and 768px introduction above wide grayscale photography. Alternating text-and-map or text-and-photo splits lead into a timeline: 16px yellow years, 12px yellow dots and a thin connecting rule. A graphite leadership band holds three circular portraits with 4px yellow left rules beside captions, followed by a logo field, standalone bright recruitment invitation and Footer.

**Transfer:** Use the same restrained narrative devices for authentic organizational history or a mission story; retain a people-led opening rather than a product demo.

**Text style:** `secondary-display` — basier 600 · 48px/1.25

## Page flow

**Storyline:** promise → grounded proof → capability and mechanism chapters → meaningful choices → uncertainty removed → practical invitation → utility footer

### Broad marketing landing page

1. **promise** — Large centered typographic claim, paired actions, announcement strip and logo field.
2. **capability introduction** — Four icon-led dark feature cards.
3. **human proof** — Sticky introduction beside bright video-and-quote cards.
4. **value and mechanism** — Inset value enclosure, glowing ecosystem graph and paired mechanism illustrations.
5. **choice** — Yellow decision band with dark alternatives.
6. **quantified proof** — Unboxed large white numerals with yellow captions.
7. **objection handling** — Numbered accordion beside helpful introductory copy.
8. **closing call** — Yellow invitation with dark alternative-access strip and command.
9. **utility** — Five link columns, newsletter and separated legal row.

**Transfer:** Borrow the alternation between practical text, luminous technical explanation and substantial yellow proof, choosing only the chapters relevant to the offering.

### Pricing and buying evaluation

1. **pricing promise** — Compact centered heading, metering explanation and provider-region choice.
2. **comparison** — Three tall tier cards with recommended middle-tier glow.
3. **trust and alternatives** — Logo row, supporting pricing links and two ancillary offer cards.
4. **personalized estimate** — Editable form beside sticky bordered total.
5. **principles** — Yellow two-column explanation of cost control and transparency.
6. **objection handling** — Numbered questions.
7. **closing call** — Dark invitation with paired trial and sales actions.
8. **utility** — Shared full footer.

**Transfer:** Keep plan comparison, cost assumptions and billing reassurance distinct instead of compressing them into one table.

### Flagship technical product landing page

1. **promise and demonstration** — Highlighted secondary-display promise above a yellow light ribbon and layered interface.
2. **benefits** — Three yellow-top-rule cards.
3. **system explanation** — Dark framed architecture with dashed layer groups.
4. **social proof** — Four dark quote cards on a panel crossing an angled yellow band.
5. **capability chapters** — Six translucent capability cards.
6. **ecosystem spotlight** — Warm paper editorial band with interface media.
7. **extensibility** — Architecture illustration beside yellow-left-rule copy.
8. **education** — Graphite demo-and-copy chapter with three related resource cards.
9. **resources** — Two-column linked rows with icons and external arrows.
10. **closing call** — Standalone bright invitation followed by full footer.

**Transfer:** Use the stronger product stage only when a coherent interface or workflow merits it; preserve the diagram and education chapters for technical credibility.

### Solution-specific product evaluation

1. **promise** — Left-aligned heading, checklist and paired actions beside flat interface illustration.
2. **proof** — Numbered benefit rows followed by four dark customer quotes against yellow.
3. **applications** — Graphite chapter with check-list cards.
4. **mechanism** — Large architecture diagram beside expandable explanations.
5. **benefits** — Unboxed two-column icon-and-copy grid.
6. **supporting resources** — Dark bordered panel with highlighted heading and ordered yellow links.
7. **closing call** — Standalone bright invitation and full footer.

**Transfer:** Turn an abstract category into practical uses, then show how the product supports them and where to learn more.

### Company credibility and recruiting

1. **identity** — Centered introduction and grayscale team photograph.
2. **working model** — Text beside dotted regional map with glowing locations.
3. **history** — Photo beside yellow-dot timeline.
4. **people** — Graphite band with circular leadership portraits and ruled captions.
5. **institutional proof** — Partner or investor logo field.
6. **closing call** — Yellow recruiting invitation and shared full footer.

**Transfer:** Use real organizational evidence and people; substitute relevant affiliations and milestones rather than product-performance proof.

## Writing

Confident, practical and technically fluent, with approachable human reassurance around the harder claims. Benefits are expressed as concrete speed, control, scale and ease, not speculative technological grandeur.

**Do not copy:** Do not reuse ClickHouse names, logos, customer marks, quotes, installation commands, proprietary illustrations, acquisition news, performance multiples, funding facts, credits or trial terms. Replace them with the new product's own verified assets and claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct imperative verbs for benefits and actions, you for reader outcomes, and we for assistance or operating principles. Name the product where it improves clarity.
- **Rhythm:** Short category promises and outcome headings, followed by one or two concrete explanatory sentences. Lists use parallel verbs; longer technical explanations are kept in separate chapters. Exclamation marks are rare outside signup reassurance.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Clear category leadership or outcome with minimal qualification. | 4–9 words | “The leading database for AI”<br>“Real-time analytics with [Brand]” |
| Supporting line | Explain the scale, speed or practical mechanism beneath the claim. | 10–30 words | “Powering agentic systems with millisecond queries at petabyte scale.” |
| Capability heading | Verb-led benefit or compact descriptive quality. | 2–8 words | “Build real-time data products that scale”<br>“Scale effortlessly” |
| Primary action | Direct verb plus a low-risk next step. | 2–5 words | “Start free cloud trial”<br>“Contact sales” |
| Reassurance | State how the product or team removes operational uncertainty. | 8–25 words | “Pay only for what you use”<br>“Running a proof of concept? Our engineers can help you size and tune it.” |
| Section question | Ask the buyer's actual technical question plainly. | 4–12 words | “Why is [Brand] so fast?”<br>“How do I keep costs under control?” |

**Words and phrasing to use:** real-time; at scale; open; build; control; resource efficient; get started; learn more; production-ready; without

**Avoid:** magical; revolutionary; unlock limitless possibilities; next-generation synergy; game-changing ecosystem

**Rules:**

- Make each claim attach to a tangible mechanism, user task or verified proof.
- Separate a short benefit headline from the paragraph explaining how it works.
- Keep lists parallel and action-oriented rather than mixing nouns with full sentences.
- Explain pricing and evaluation terms plainly; reassurance belongs close to the action.
- Use technical terms where they carry information, not as decorative keyword strings.

## Do's and Don'ts

### Do

- Keep the default opening at 96px/1 semibold with normal tracking.
- Use a 1280px outer container with 32px side padding.
- Maintain 16px between headings and supporting copy.
- Use 4px rectangular action corners and 8px card corners.
- Give yellow a substantial proof or decision surface as well as small action roles.
- Keep diagram routing thin and yellow, with a glow concentrated on the central node.
- Pair 72px white proof numerals with 24px bold yellow labels.
- End with a concrete invitation and a genuinely useful footer newsletter area.

### Don't

- Do not replace the olive-black 275deg canvas with navy gradients.
- Do not tighten display tracking into a condensed poster look.
- Do not make ordinary actions pill-shaped; that geometry belongs to filters.
- Do not add a luminous shadow to every feature card; normal cards use faint neutral edges.
- Do not use monospace for general paragraphs or uppercase eyebrows.
- Do not convert the warm stage and grayscale company photography into glossy generic 3D imagery.
- Do not make the 72px proof numerals small metrics inside matching tinted cards.
- Do not omit the dense utility ending in favor of an oversized logo-only footer.

## Motion and responsive

### Motion

**Observed:**

- Declared action color, fill and border transitions use .15s cubic-bezier(.4, 0, .2, 1); default feature-card transitions use 0.3s with the same easing.
- Declared opening fade-up is .5s ease both; reduced-motion classes disable it.
- Declared hub pulse is 2s cubic-bezier(.4, 0, .6, 1) infinite; announcement rings use 2.5s with the same easing family.
- Declared logo-field animations use 10s linear; some opacity transitions use 0.3s.

**Transfer:**

- Use restrained entrance motion on the promise and a soft pulsing hub, keeping the diagram structure stable.
- Keep logo motion slow and linear rather than turning proof into an aggressive marquee.

**Unknown:**

- Exact logo travel distance, light-ribbon behavior, on-scroll triggers and focus-visible styling are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 897px, 901px, 1023px, 1024px, 1280px and 1536px.
- The opening declares smaller type below the 96px desktop tier; action rows become full-width vertical stacks before the medium-width layout.
- Feature grids declare one column, then two, then four; technical capability grids declare one, two and three columns.

**Transfer:**

- Preserve the highlighter patch and luminous graph on narrow screens; simplify node labels or stack groups rather than squeezing a full diagram into unreadable text.
- Let the sticky proof split become a normal introduction above the proof cards; preserve the warm media framing.
- Stack decision alternatives and estimator summary after their introduction or inputs, keeping bright choice emphasis intact.

**Unknown:**

- Mobile rendered navigation, exact type values at every breakpoint and detailed diagram rearrangements are unknown; the collapse guidance is a recommended adaptation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
