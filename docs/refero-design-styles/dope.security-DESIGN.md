# dope.security — cinematic flight hardware

## Overview

A cinematic, dark technology style that makes enterprise software feel like a first-class journey. Black canvases and white grotesk typography meet languid editorial serifs, violet light, pink sunsets and blue cloudscapes. Dense technical demonstrations sit inside an otherwise spacious, theatrical presentation, with translucent ticket-like panels and instrument-style markings.

### Essentials

- Headlines alternate engineered confidence and editorial flourish: the opening combines 88px Whyte Inktrap at weight 500, line-height 0.8 and -0.03em tracking with 88px GrandSlang in upright and italic cuts.
- The first screen is a destination, not a dashboard grid: a 960px atmospheric stage puts a roughly 45%-width headline column opposite a translucent ticket, with a 54px fixed hairline navigation above and small telemetry below.
- Conversion controls feel like illuminated glass: primary closing actions are 64px pills with 32px horizontal padding, 12px backdrop blur and asymmetric 0.5px white and rose edges; navigation actions instead use compact 4px corners.
- Color lives in the scenery and selected artifacts: most reading sections remain #090909 with #f7f9fa text; violet #af50ff is concentrated in active controls, fine edges and light, while cloud scenes, ticket cards and the closing atmosphere carry the broad blue–pink color fields.
- Technical lettering becomes an object: include an oversized split-flap capability board with 73.6px mono capitals, 0.2em tracking, 100px rows and 16px gaps. Use a stable sliced-letter treatment when animation is unavailable.
- Product proof floats in darkness: a roughly 907px-wide interface scene is staged with detached detail cards and violet browser chrome; pair it with a bright, horizontally overflowing ticket-card rail, 423×297px cards and 24px gaps. When product media is unavailable, use a purposeful schematic with the same hierarchy rather than stock devices.
- The ending is an atmospheric landing: a light 50px/1.2 closing line and glass actions lead into a grainy violet–blue footer, a broad concave dark horizon, four information columns and a fine bottom rule. Preserve this theatrical closing device wherever the page's narrative places its final action.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#af50ff` | `--color-violet` | accent, action, border | Active product selector, play accents, highlighted pricing outlines and hover illumination. |
| Violet atmosphere | `#6c4bd6` | `--color-halo` | background, accent | A radial light overlay in the opening, at opacity 0.437 rather than a flat violet section. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Badge edge blue | `#4d5da5` | `--color-blue-edge` | border | Half-pixel top edge on technical proof badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pure white | `#ffffff` | `--color-white` | text, border | Action text, strong outlines and selected labels. |
| Cool white | `#f7f9fa` | `--color-paper` | text | Default marketing headings and body copy. |
| Muted instrumentation | `#6b6b6b` | `--color-muted` | text, border | White at 40% over the canvas for low-priority instrumentation and fine structural edges. |
| Faint rule | `#474747` | `--color-rule` | border | White at 25% over the canvas, used on interface frames and glass top edges. |
| Ghost numeral | `#454545` | `--color-ghost-number` | text | Cool white at 25% over black behind ticket captions; the numeral also uses soft-light blending. |
| Smoke glass | `#222222` | `--color-glass` | surface | Visible white at 10% over the near-black canvas; the same transparent wash allows atmospheric art to show through. |
| Low glass | `#1a1a1a` | `--color-badge` | surface | White at 7% over the canvas for small proof badges. |
| Rose glass | `#141212` | `--color-rose-glass` | surface | Rose rgb(237,195,196) at 5% over the canvas for main glass actions. |
| Near-black canvas | `#090909` | `--color-canvas` | background, text | Default reading canvas and dark text on violet active controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| customer proof and pricing pages | Lavender detail | `#d4a0ff` | `--color-lavender` | text | Attributions and feature-list details. |
| pricing and product-detail chapters | Sunrise peach | `#fa9e98` | `--color-peach` | accent | Subtle peach-to-white clipped display headings. |

## Typography

- **Whyte Inktrap** — Main marketing text, headings, navigation and numbers; the ABC-prefixed declaration is the same visual family in customer quotes. Contemporary grotesk with distinctive ink traps; compact and direct, capable of very tight display setting. If unavailable, use **Inter**. Use weights 300–700 and retain the role-specific tracking. Font stack: "Whyte Inktrap", "Inter", Arial, sans-serif.
- **GrandSlang** — Editorial words inserted into otherwise sans headings, italic comparison connectors and expressive labels. High-contrast, eccentric display serif with long sweeping italic gestures. If unavailable, use **Bodoni Moda**. Use regular and italic; tune line breaks to preserve the long gestures. Font stack: "GrandSlang", "Bodoni Moda", Georgia, serif.
- **Whyte Inktrap Mono** — Split-flap capability lettering and coordinate-style microcopy. Mechanical monospaced counterpart to the main grotesk. If unavailable, use **Space Mono**. Use regular with the wide display tracking. Font stack: "Whyte Inktrap Mono", "Space Mono", ui-monospace, monospace.
- **Karla** (only for culture pages) — Supporting culture-page prose. Friendly humanist sans that softens the theatrical display typography. Font stack: "Karla", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Whyte Inktrap | 500 | 88px | 0.8 | -0.03em | fixed | Default opening's principal product phrase. |
| display-serif | GrandSlang | 400 | 88px | 0.8 | -0.03em | fixed | Upright editorial lead-in within the opening headline. |
| display-italic | GrandSlang | 400 italic | 88px | 0.8 | -0.03em | fixed | Expressive connecting words within the opening headline. |
| ticket-number | Whyte Inktrap | 400 | 88px | 1 | normal | fixed | Translucent two-digit ticket index behind the bottom title. |
| chapter-bold | Whyte Inktrap | 700 | 80px | 0.9 | -0.07em | fixed | Confrontational problem-statement chapter. |
| split-flap | Whyte Inktrap Mono | 400 | 73.6px | 0.9 | 0.2em, uppercase | fixed | Oversized capability-board lettering. |
| showcase-heading | Whyte Inktrap | 500 | 64px | 1.2 | -0.04em | fixed | Centered introduction above a major product scene. |
| showcase-italic | GrandSlang | 400 italic | 64px | 1.2 | normal | fixed | Editorial companion word in the showcase heading. |
| closing | Whyte Inktrap | 300 | 50px | 1.2 | normal | fixed | Centered closing invitation; light rather than emphatic. |
| heading | Whyte Inktrap | 400 | 48px | 1.2 | normal | fixed | Left-aligned heading above ticket-card rails. |
| ticket-serif | GrandSlang | 400 italic | 32px | 1.2 | normal | fixed | Comparison connector or audience title at the foot of a ticket. |
| hero-support | Whyte Inktrap | 700 | 28px | 1.2 | -0.01em | fixed | Short, forceful benefit beneath the opening headline. |
| subheading | Whyte Inktrap | 400 | 28px | 1.2 | normal | fixed | Product explanation heading below a major scene. |
| action-large | Whyte Inktrap | 300 | 28px | 1 | normal | fixed | Closing glass-pill action labels. |
| body | Whyte Inktrap | 300 | 20px | 1.6 | normal | fixed | Default descriptive marketing paragraphs. |
| footer-title | Whyte Inktrap | 700 | 20px | 0.8 | normal, uppercase | fixed | Footer column headings. |
| footer-body | Whyte Inktrap | 400 | 18px | 1.556 | normal | fixed | Short manifesto paragraph in the footer. |
| footer-link | Whyte Inktrap | 400 | 18px | 1.11 | normal | fixed | Footer navigation and contact links. |
| active-tab | Whyte Inktrap | 700 | 16px | 1.5 | normal | fixed | Selected product tab. |
| ticket-label | Whyte Inktrap | 400 | 14px | 1.25 | 0.07em, uppercase | fixed | Small functional label at the top of a colored ticket. |
| telemetry | Whyte Inktrap Mono | 400 | 14px | 1.5 | normal | fixed | Small coordinate-like labels on the atmospheric stage. |
| navigation | Whyte Inktrap | 400 | 12px | 1 | normal, uppercase | fixed | Navigation, compact nav actions and proof badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing objection handling | outline-faq | Whyte Inktrap | 400 | 368px | 0.675 | normal | fixed | Monumental outlined backdrop behind a smaller filled FAQ heading. |
| pricing comparison chapters | outline-word | Whyte Inktrap | 700 | 201.6px | 1 | normal, uppercase | size 14vw | Oversized outlined backdrop lettering behind the comparison matrix. |
| culture pages | culture-stat | Whyte Inktrap | 400 | 128px | 1.125 | -0.015em | fixed | Three oversized facts; fine serif plus signs supply contrast. |
| culture pages | culture-display | Whyte Inktrap | 400 | 112px | 0.75 | -0.015em | fixed | Centered two-line people-focused headline. |
| culture pages | culture-italic | GrandSlang | 400 italic | 112px | 0.75 | -0.015em | fixed | Muted expressive word nested inside the culture headline. |
| product-detail openings | product-display | Whyte Inktrap | 400 | 96px | 1 | -0.0167em | fixed | A product statement split across the upper-left and lower-right corners of a cinematic scene. |
| pricing pages | gradient-heading | Whyte Inktrap | 400 | 80px | 1 | -0.07em | fixed | Centered major headings with a peach upper edge fading to white. |
| customer-proof openings | proof-display | Whyte Inktrap | 400 | 80px | 1 | -0.05em | fixed | Centered two-line headline beneath a rating capsule. |
| product-detail and pricing benefit rows | benefit-heading | Whyte Inktrap | 400 | 64px | 1 | normal | fixed | Large benefit or quantified claim, set beside two peers. |
| pricing pages | faq-question | Whyte Inktrap | 400 | 24px | 1.4 | normal | fixed | Accordion questions and the adjacent contact card. |
| culture openings | culture-body | Karla | 400 | 24px | 1.5 | normal | fixed | Single supporting line below the mixed-type headline. |
| product-detail and pricing benefit rows | benefit-body | Whyte Inktrap | 300 | 20px | 1.5 | normal | fixed | Compact explanatory line beneath a benefit. |
| customer-proof pages | quote | Whyte Inktrap | 400 | 20px | 1.25 | -0.04em | fixed | Dense, readable customer testimony inside glass cards. |
| culture portrait galleries | culture-caption | Whyte Inktrap | 400 | 12px | 1.5 | 0.2em, uppercase | fixed | Underscored names, job roles and previous affiliations beside a thin vertical rule. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep editorial inserts at the same nominal size and baseline as their surrounding phrase; the contrast comes from construction and italic movement, not a different color for every word.
- Tracking tightens sharply in the 80px bold and pricing headings, but ordinary 48px headings and 20px body text keep normal tracking. Do not apply one global negative tracking rule.
- The opening uses closely stacked lines and a muted final serif line; the main benefit and action remain distinct beneath it.
- Decorative lettering is not a substitute for a readable filled heading. Outline backdrops remain behind the comparison or FAQ title.

## Layout

**Density:** Airy theatrical sections around compact technical clusters; full scenes are separated by substantial black breathing space.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight control and icon spacing. |
| 16px | Repeated board-row gaps, heading support gaps and small card gutters. |
| 20px | Half of the declared 40px column gap; split column padding. |
| 24px | Quote-card padding and ticket-rail gaps. |
| 32px | Small layout gap token and hero action separation. |
| 40px | Main declared row/column gap and footer side margins. |
| 48px | Footer top padding and larger vertical grouping. |
| 64px | Section heading to rail, product tab top/bottom space and closing line to actions. |
| 72px | Default main-scene side padding. |
| 80px | Capability board top padding. |
| 128px | Large chapter separation. |
| 160px | Major section padding and breathing room. |

### Containers and grids

- **main-stage**: max width 2240px · side padding 72px. Centered wide scene container; at 1440px it leaves 1296px of content width.
- **footer-and-secondary**: max width 1440px · side padding 40px. 1360px-wide footer and secondary-page compositions at desktop.
- **hero-split**: 2 columns · gap 40px. A left content column occupying about 45% of the scene, an open center and a large ticket panel on the right.
- **ticket-rail**: 4 columns · gap 24px · side padding 64px. 423px cards overflow the right edge; preserve the suggestion of further content rather than shrinking every card to fit.
- **benefit-row** (only for product-detail and pricing pages): 3 columns · gap 64px. Three large textual benefits without individual card fills.
- **proof-rail** (only for customer-proof pages): 3 columns · gap 24px. 530px testimonial cards in horizontally clipped rows.
- **culture-facts** (only for culture pages): max width 1120px · 3 columns · gap 16px. Three evenly spaced oversized facts beneath the opening.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-actions | 9999px (pill) |
|  | navigation-actions | 4px |
|  | technical-badges | 8px |
|  | tickets | 20px |
| product demonstrations | console-frames | 24px |
| customer proof and pricing pages | quote-and-faq-cards | 12px |
| pricing pages | pricing-plans | 24.3px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| highlighted pricing plans | pricing-halo | `0px 0px 72.9px 0px rgba(175,80,255,0.24)` | Soft violet bloom, not a downward elevation shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #090909; color: #f7f9fa`

#### Atmospheric stage · level 0

**Use:** Opening light overlay over full-bleed cloud imagery.

**CSS:** `background-image: radial-gradient(circle closest-corner at 10% 50%, #6c4bd6, rgba(0,0,0,0) 55%); opacity: 0.437`

**Observed:** A directional dark overlay protects the headline and a bottom fade merges the clouds into black.

**Transfer:** Layer this light over imagery, not over the text; keep the text at full opacity.

#### Glass action · level 1

**Use:** Translucent conversion controls.

**CSS:** `background-color: rgba(237,195,196,0.05); border-top: 0.5px solid rgba(255,255,255,0.25); border-right: 0.5px solid rgba(255,255,255,0.5); border-bottom: 0.5px solid rgba(237,195,196,0.25); border-radius: 9999px; backdrop-filter: blur(12px)`

#### Proof glass · level 1

**Use:** Compact technical validation attached to a scene.

**CSS:** `background-color: rgba(255,255,255,0.07); border-top: 0.5px solid #4d5da5; border-radius: 8px; backdrop-filter: blur(11px)`

#### Atmospheric landing · level 0

**Use:** Broad closing and footer backdrop.

**CSS:** `background-color: #090909`

**Observed:** Fine grain overlays broad violet, cobalt and pink light pools. A huge black concave curve masks the upper portion, making the footer feel like it is beneath a horizon.

**Transfer:** Use the atmospheric landing artwork recipe to give every page a designed ending rather than a flat utility strip.

#### Violet plan glass · level 1

**Only for:** pricing pages

**Use:** Recommended plan and its enclosing bundle.

**CSS:** `background-color: rgba(16,9,13,0.5); background-image: linear-gradient(rgba(96,76,191,0.2), rgba(215,80,251,0.2)); border: 0.5px solid rgba(255,255,255,0.4); border-radius: 24.3px; box-shadow: 0px 0px 72.9px 0px rgba(175,80,255,0.24); backdrop-filter: blur(15.2px)`

**Observed:** The highlighted middle bundle contains two narrower plan panels. Outside plans remain dark, with a faint white wash rather than equal violet emphasis.

**Transfer:** Highlight the meaningful middle choice or bundle, not every plan.

## Components

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; height: 54px; padding: 0px 26px; display: flex; align-items: center; border-bottom: 0.5px solid rgba(255,255,255,0.4); z-index: 20`

**Text style:** `navigation` — Whyte Inktrap 400 · 12px/1 · uppercase

**Observed:** A small white wordmark anchors the left; a vertical hairline separates it from the right-heavy menu and two compact actions. A low-opacity blurred backing lets the opening scenery tint the bar.

**States:** Declared: hover on menu links adds a 4px white-at-75% bottom rule and white-at-75% text; active clears the outline.

### Navigation action

**Use:** Compact demo action; bordered login is the secondary variant.

**CSS:** `background-color: rgba(255,255,255,0.1); color: #ffffff; border-radius: 4px; padding: 10px 18px; height: 32px; display: flex; align-items: center; justify-content: center`

**Text style:** `navigation` — Whyte Inktrap 400 · 12px/1 · uppercase

**Observed:** The secondary action has a 0.5px white border, no filled wash and a 33px height. The two actions are separated by 12px.

**States:** Declared: hover changes the filled action background to white at 40%; active clears the outline.

### Glass pill action

**Use:** Main final conversion action.

**CSS:** `background-color: rgba(237,195,196,0.05); color: #ffffff; border-top: 0.5px solid rgba(255,255,255,0.25); border-right: 0.5px solid rgba(255,255,255,0.5); border-bottom: 0.5px solid rgba(237,195,196,0.25); border-radius: 9999px; backdrop-filter: blur(12px); padding: 0px 32px; height: 64px; display: flex; align-items: center; justify-content: center; gap: 16px`

**Text style:** `action-large` — Whyte Inktrap 300 · 28px/1

**Observed:** An arrow or identity-provider symbol shares the label row. Two provider actions sit beside one another in the final invitation; pricing uses shorter 55px variants with 20px light text.

**States:** Declared: hover uses white at 10% fill and inset violet strokes of 2px plus asymmetric 1px highlights, with the border style removed; active clears the outline.

### Play control

**Use:** Video invitation next to a lightweight text link.

**CSS:** `width: 64px; height: 64px; border: 1px solid #ffffff; border-radius: 50%; backdrop-filter: blur(7px); display: flex; align-items: center; justify-content: center`

**Observed:** A violet triangular play glyph sits in the ring. The ring follows the text, not before it; the text and ring have a 32px gap.

**Transfer:** Name the demo's real duration in the accompanying label.

### Split flap row

**Use:** Capabilities presented as mechanical departure-board lettering.

**CSS:** `height: 100px; border-radius: 8px; background-image: linear-gradient(rgba(255,255,255,0.2), rgba(255,255,255,0)); padding: 1px`

**Text style:** `split-flap` — Whyte Inktrap Mono 400 · 73.6px/0.9 · tracking 0.2em · uppercase

**Observed:** A dark inset face sits within the faint edge. Letterforms are sliced at their horizontal midline, with mixtures of outlined and solid segments and a right-arrow terminus. Rows form a full-width vertical board.

**Transfer:** Use short capability nouns or verbs. For a static implementation, align two clipped text copies around a narrow dark seam; keep the words readable.

### Technical badge

**Use:** Certifications, update guarantees or other small verifiable proof.

**CSS:** `background-color: rgba(255,255,255,0.07); border-top: 0.5px solid #4d5da5; border-radius: 8px; backdrop-filter: blur(11px); padding: 12px 24px`

**Text style:** `navigation` — Whyte Inktrap 400 · 12px/1 · uppercase

**Observed:** Badges hover close to artwork or sit beside a heading. A separate compliance-chip variant uses 6px corners and 9px 15px padding.

### Product selector

**Use:** Switch among closely related product views.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 56px; padding: 6px 8px; border: 1px solid rgba(255,255,255,0.1); border-radius: 9999px; background-color: rgba(175,80,255,0.1)`

**Text style:** `active-tab` — Whyte Inktrap 700 · 16px/1.5

**Observed:** A violet selected pill with dark bold type sits inside a much darker purple track. Other tabs use light regular text and a plus prefix. The selector sits 64px below the main interface scene and 64px above its explanation.

**Transfer:** Use this only for a genuine product family or view switch; do not turn section navigation into identical pills.

### Footer link

**Use:** Utility and contact navigation over the atmospheric landing.

**CSS:** `color: #ffffff; padding: 8px 8px 4px; display: inline-block`

**Text style:** `footer-link` — Whyte Inktrap 400 · 18px/1.11

**Observed:** Links form left-aligned lists under bold uppercase titles. Contact links are flush-left; social and legal links use much smaller tracked capitals along the bottom.

### Console frame

**Only for:** product demonstrations

**Use:** Large layered interface demonstrations.

**CSS:** `width: 1152px; border: 1px solid rgba(255,255,255,0.25); border-radius: 24px; overflow: hidden; position: relative`

**Observed:** Several dark console frames stack with offsets so the older panels remain visible to the right. A 96px lower gradient caption band holds a thin white rule, mixed serif–sans title on the left and a two-digit index on the right.

**Transfer:** Show meaningful product states at an honest scale; keep the shell restrained and let the data carry the color.

### Testimonial card

**Only for:** customer-proof pages

**Use:** Long-form customer testimony in horizontally moving rows.

**CSS:** `width: 530px; height: 402px; background-color: rgba(255,255,255,0.1); border: 1px solid #ffffff; border-radius: 12px; padding: 24px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `quote` — Whyte Inktrap 400 · 20px/1.25 · tracking -0.04em

**Observed:** A white quotation glyph sits inside a small smoke square at the top. The attribution, a violet category badge and a small numeric pill align along the bottom. Two clipped rows create a wall rather than isolated centered quotes.

**Transfer:** Keep quotes specific and leave room for attribution metadata; shorten testimony rather than reducing its type size.

### Plan panel

**Only for:** pricing pages

**Use:** Feature comparison with an upgrade action at the bottom.

**CSS:** `width: 240px; padding: 24px 16px; border: 0.5px solid rgba(255,255,255,0.4); border-radius: 24.3px; background-color: rgba(16,9,13,0.5); background-image: linear-gradient(rgba(96,76,191,0.2), rgba(215,80,251,0.2)); backdrop-filter: blur(15.2px); display: flex; flex-direction: column; justify-content: space-between`

**Observed:** Centered plan title and description precede a compact left-aligned feature list with small circular plus/check markers. A larger shared violet container groups the two middle plans; outer plans use a neutral wash. The entry choice gets a darker action and upgrades get glass actions.

**Transfer:** Let functional distinctions drive grouping; do not invent a numeric price when the offering is sales-led.

### FAQ item

**Only for:** pricing pages

**Use:** Objection handling next to a smaller contact panel.

**CSS:** `border: 1px solid #af50ff; border-radius: 12px; padding-bottom: 8px; margin-bottom: 16px; max-width: 768px`

**Text style:** `faq-question` — Whyte Inktrap 400 · 24px/1.4

**Observed:** The header uses 24px top and side padding and 16px bottom padding, with a small plus aligned right. The expanded item shows answer text beneath and changes the plus to a close mark. The contact panel matches the outline and corners.

## Imagery and graphics

### Cloud flight stage

**Use:** The default marketing opening and selected atmospheric interludes.

**Observed:** Painterly cumulus clouds form a bright pink horizon below an intensely blue sky, with violet shadows at the edges. A small luminous plane and horizontal trail cross the open center. The image fills the screen behind, rather than sitting in a rectangular content card.

**Transfer:** For a different product, stage its promise as a journey through an equally expansive environment. Minimum acceptable treatment is a licensed cloud photograph recolored into deep cobalt, plum shadows and warm pink rim light, with a restrained abstract moving point instead of a literal vehicle.

**Build:** Fill the stage with a cloud image. Add a navy-to-transparent left overlay and black-to-transparent bottom overlay, plus the Atmospheric stage radial light. Draw a short horizontal SVG line fading from rgba(255,255,255,0) to rgba(255,255,255,0.8), repeat it with 4px blur and place a small white arrowhead at its end. Keep the trail behind the content and in the central negative space.

### Boarding pass glass

**Use:** The major object opposite the opening headline.

**Observed:** A tall, frosted ticket occupies roughly the right third of the opening. Its upper edge and right side catch light, the left side includes a round ticket notch and perforation, and the clouds remain visible through it. Faint route metadata sits above a prominent trial invitation, with two stacked provider pills below; a vertical barcode-like strip runs down the far right.

**Transfer:** Use the new product's entry action as an invitation on a pass, access card or instrument panel. Retain a quiet metadata tier and one strong conversion tier; the decorative code must not compete with the action.

**Build:** Create an SVG rounded panel with a subtractive circular notch near its upper-left corner and a dotted vertical perforation. Fill with rgba(255,255,255,0.08), stroke the top and right at rgba(255,255,255,0.45), and place a blurred duplicate of the scenery behind it. Reserve a narrow right strip for stacked SVG bars and square-code fragments. Use approximately 512×576px at desktop, then size to the available column.

### Colored ticket rail

**Use:** A signature bright proof or exploration rail on the black reading canvas.

**Observed:** Rounded rectangular tickets have circular side bites, blurred cyan, lavender, plum and hot-pink light fields, muted uppercase top labels, oversized translucent indices and a white bottom title with arrow. Adjacent cards extend beyond both sides of the viewport during browsing.

**Transfer:** Use the format for audiences, alternatives, use cases or outcomes; give each card one visual mood rather than literal stock photography.

**Build:** Use a 423×297px panel with 20px corners. Layer two or three radial gradients in cyan, violet and pink, with 40–70px blur on separate oversized ellipses. Mask a roughly 18px circular bite from each side at about one third of the height. Add a subtle dark lower gradient, then place the ticket-label above and ticket-number behind the bottom title.

### Floating product scene

**Use:** Major demonstration on a spacious black stage.

**Observed:** A dark interface about 907×510px dominates the center with a violet browser bar. Small detached message and data cards float just outside its perimeter, while a circular chart overlaps the lower-right edge. The backing remains black, not a generic laptop photograph.

**Transfer:** Use a real interface or a simplified, product-specific diagram with one dominant panel and two or three informative detail callouts. Preserve the thin lines and limited violet/cyan data accents; do not fabricate decorative dashboard noise.

### Atmospheric landing artwork

**Use:** Closing invitation and footer.

**Observed:** Broad soft pools of violet, cobalt and pink with visible fine grain sit behind white columns. The upper boundary is an enormous smooth black concavity, not a straight divider. Culture pages shift toward plum and amber; customer proof adds a pinker cast.

**Transfer:** Keep this ending even if the product has no bespoke artwork. Match the soft glow; exact gradient stops are not essential.

**Build:** Layer wide radial ellipses: rgba(175,80,255,0.55) near bottom-left, rgba(40,100,210,0.65) near bottom-right and rgba(210,80,150,0.2) near center, over black. Add a low-opacity SVG turbulence texture. Overlay a very wide black ellipse above the section so its bottom edge creates the concave horizon. Place content on a separate sharp layer.

### Technical globe horizon

**Only for:** product-detail scenes

**Use:** A capability explanation around a single cinematic object.

**Observed:** A huge near-black sphere rises from below with a bright violet rim, surrounded by scattered pink-lit clouds. Benefit copy and small proof tags float across and around the sphere.

**Transfer:** Use a rim-lit abstract sphere or product-relevant volumetric shape to support the technical explanation without replacing it.

**Build:** Use a large circular black div partly outside the section, with an inset violet top glow and a blurred violet duplicate behind it. Place isolated cloud cutouts above the rim and fade the section bottom back to black.

### Culture collage

**Only for:** culture pages

**Use:** People, working life and press credibility.

**Observed:** The opening is dark analog imagery with multicolored refracted light, grain and oversized ghost lettering. Below, staggered lifestyle images overlap smaller monochrome portraits; tiny uppercase role captions sit beside thin rules. Press logos appear as white marks over a plum-and-amber field and huge outlined lettering.

**Transfer:** Mix genuine everyday photography with direct monochrome portraits, keeping an irregular editorial arrangement rather than a uniform employee-card grid.

**Build:** For the analog opening, place a dark photograph beneath blurred red, yellow and blue translucent ellipses, subtle horizontal scan lines and a fine grain overlay; keep the central type clean.

### Icons

**Observed:** Navigation is predominantly typographic. White right arrows terminate cards and actions; play glyphs are violet inside thin white or violet rings. Technical plus signs, a small crosshair and white quote glyphs echo equipment markings. Most action arrows are about 19×17px and card arrows about 24px.

**Transfer:** Use simple filled arrows, plus signs and sparse technical marks. Match their visual mass to the light type; keep provider or partner symbols authentic when they identify an actual integration.

## Section recipes

How recurring sections are built.

### First screen: Cinematic invitation opening

**Observed:** A 960px-tall cloud stage begins behind the fixed Navigation. Back-to-front layers are cloud imagery, violet light and edge-darkening overlays, a small bright horizontal trail, a left mixed-type headline and a translucent Boarding pass glass on the right. Main content has 72px side gutters. The headline occupies about 45% of the width: an upright serif lead-in and italic connective surround a bold grotesk product phrase, all at 88px with tightly overlapping 0.8 line-height. Its last serif line is muted. Below sit a short 28px bold benefit and a text-plus-Play control invitation. The ticket takes roughly the right third, with a large invitation and two stacked outlined provider actions. Within the first 900px the complete headline, benefit, video invitation, ticket, main actions and small bottom telemetry are visible; the capability board begins below the first screen.

**Transfer:** Make the new promise a similarly compact mixed-type composition and keep the invitation object equally substantial. Without elaborate art, use a recolored cloud photograph, a restrained luminous path and an SVG access ticket. Product-detail pages can split a 96px statement between opposite corners around a central play ring; pricing opens with a centered 80px gradient headline and a media frame; customer proof opens with a rating capsule, 80px two-line title and quote wall; culture opens with centered mixed type and oversized facts.

**Avoid:** Do not replace the scene with a generic centered SaaS headline, tiny interface thumbnail and solid violet rectangle. Do not hide the entry actions below the opening or put legibility-destroying light directly beneath the headline.

**Text style:** `display` — Whyte Inktrap 500 · 88px/0.8 · tracking -0.03em

### Mechanical capability board

**Observed:** Split flap row components form a wide vertical list on Canvas, inset 72px, with 80px top and 160px bottom padding. Each row is 100px tall with 16px gaps. Letterforms alternate solid and outlined fragments while the arrow stays anchored on the right.

**Transfer:** Use a concise set of product capabilities; preserve the physical display-board character without repeating the same word twice for visual length.

**Text style:** `split-flap` — Whyte Inktrap Mono 400 · 73.6px/0.9 · tracking 0.2em · uppercase

### Problem chapter

**Observed:** A weight-700, 80px headline with -0.07em tracking sits left on a nearly black scene, supported by tiny technical chapter markings and expansive media space. Later a smaller centered rhetorical sentence bridges into a cinematic explanation.

**Transfer:** Name a real old-way friction and dramatize the change with a purposeful diagram or object. Keep the chapter self-contained rather than stretching empty space to imply depth.

**Text style:** `chapter-bold` — Whyte Inktrap 700 · 80px/0.9 · tracking -0.07em

### Editorial product showcase

**Observed:** A centered 64px mixed serif–sans heading introduces Floating product scene with about 33px separation. Product selector sits below, followed by a two-column explanation with a 28px subheading and 20px light body. Large 160px section padding lets the scene dominate.

**Transfer:** Use one coherent demonstration with a short explanatory pair beneath, not a dozen equal feature thumbnails.

**Text style:** `showcase-heading` — Whyte Inktrap 500 · 64px/1.2 · tracking -0.04em

### Bright ticket proof rail

**Observed:** A 48px left-aligned heading and bent directional arrow introduce Colored ticket rail after 64px. Cards remain at 423×297px with 24px gaps; partial offscreen cards imply horizontal exploration.

**Transfer:** Choose a proof or audience dimension that rewards browsing. Keep the indexed, notched artifacts and vary their colored light fields.

**Text style:** `heading` — Whyte Inktrap 400 · 48px/1.2

### Atmospheric final invitation and footer

**Observed:** A centered 50px light invitation has Glass pill actions about 64px beneath it. Atmospheric landing continues into an approximately 635px utility footer with 40px side gutters, 48px top padding and 24px bottom padding. A stacked mixed-type wordmark and 320px manifesto/contact column sit left; three link columns sit to the right. Bold 20px capitals label the columns; a small rotated bracketed footer label marks the right edge. A 1px low-opacity rule separates tiny widely tracked social and legal links at the bottom. Product landings use paired provider actions, customer proof uses one demo action, while pricing and culture finish directly with the footer after their final content chapter.

**Transfer:** Keep the invitation specific to the new page's conversion goal and retain the glow, curved dark horizon and generous columnar ending. Use the new identity's own mixed-type wordmark rather than enlarging a logo mechanically.

**Text style:** `closing` — Whyte Inktrap 300 · 50px/1.2

### Benefit triptych

**Only for:** product-detail and pricing pages

**Observed:** A restrained 40px section lead with small Technical badges sits above three open columns. Each benefit uses a 64px regular title and a 20px light explanation separated by 16px. No boxes surround the benefits.

**Transfer:** Use three contrasting reasons to choose the product, including a measured claim only when substantiated.

**Text style:** `benefit-heading` — Whyte Inktrap 400 · 64px/1

### Stacked demonstration chapters

**Only for:** product-detail pages

**Observed:** Console frame panels overlap in a staged stack under a centered heading. Lower caption bands mix serif and sans words, a hairline and reverse-order two-digit indices. As chapters advance the current panel shifts left and previous frames remain visible behind.

**Transfer:** Give each panel one meaningful workflow or product state; a static stepped stack is a sufficient alternative to scroll choreography.

### Plan constellation

**Only for:** pricing pages

**Observed:** A centered gradient heading and short support line introduce tall plan panels. The middle pair shares Violet plan glass, framed by quieter entry and complete-offering columns. The plan area is followed by a compact savings prompt, open benefits, alternating media/text explanations and a broad console image.

**Transfer:** Present a clear progression from entry to fuller capability; use glow to explain the hierarchy rather than to decorate every item.

**Text style:** `gradient-heading` — Whyte Inktrap 400 · 80px/1 · tracking -0.07em

### Comparison and objections

**Only for:** pricing pages

**Observed:** A filled heading sits over a huge 14vw outlined word, followed by a dense violet-hairline matrix. Narrow comparison cells are about 136px wide; the featured column has a faint green vertical wash. Later a 368px outline FAQ backdrop supports a smaller filled heading, a left contact card and a right 768px FAQ list.

**Transfer:** Separate exhaustive evaluation from ordinary landing-page explanation. Keep readable headings in front of decorative outline words and leave contact help beside the questions.

### Customer proof wall

**Only for:** customer-proof pages

**Observed:** An outlined black rating capsule precedes a centered two-line 80px heading against grainy deep blue and violet light. Testimonial card rows span beyond the screen, with 24px gutters and attribution metadata pinned at the foot. A bright audience ticket rail and three review-summary panels add alternate proof formats.

**Transfer:** Mix concrete narratives, real ratings and audience relevance without making up endorsements.

**Text style:** `proof-display` — Whyte Inktrap 400 · 80px/1 · tracking -0.05em

### Culture editorial

**Only for:** culture pages

**Observed:** A centered 112px mixed-type title over analog light is followed by a single Karla support line and three 128px facts. A staggered collage uses monochrome headshots over larger everyday images and 12px tracked captions. The final editorial section features white press marks, a large mixed-type title and outline background lettering.

**Transfer:** Show a distinct lived identity with authentic people and work imagery, then close with outside recognition and the shared footer.

**Text style:** `culture-display` — Whyte Inktrap 400 · 112px/0.75 · tracking -0.015em

## Page flow

**Storyline:** Atmospheric promise → tangible product mechanism → evidence and capability chapters → evaluation or audience proof → low-friction invitation → atmospheric utility landing.

### Flagship marketing landing

1. **Promise** — Cloud environment, mixed-type promise and glass access ticket.
2. **Capability overview** — Mechanical split-flap board makes technical breadth tangible.
3. **Problem and mechanism** — Oversized problem headline followed by a cinematic contrast between old and new approaches.
4. **Product demonstration** — Floating console scene, family selector and concise explanatory pair.
5. **Evaluation** — Bright indexed ticket rail for alternatives.
6. **Closing call** — Light trial invitation, paired glass actions and atmospheric footer.

**Transfer:** Keep the alternation of immersion, explanation and proof; shorten cinematic chapters when the new story needs less explanation.

### Detailed product introduction

1. **Promise** — Corner-anchored split statement around a cinematic object and central play ring.
2. **Mechanism** — Large editorial sentence and a cloud-filled arch beside explanatory prose.
3. **Benefits** — Open benefit triptych and rim-lit globe atmosphere.
4. **Capabilities** — Three visual capability tiles and a deeper explanation.
5. **Product demonstration** — Large numbered console frames stack through successive workflows.
6. **Social proof** — Violet capsule labels and review-summary panels.
7. **Closing call** — Trial invitation with paired provider actions, then curved atmospheric footer.

**Transfer:** Move from a distinctive mechanism to visible working states, allowing details to be denser than the main landing.

### Culture and people storytelling

1. **Identity** — Analog-light opening with centered mixed headline and three oversized facts.
2. **Human proof** — Staggered everyday imagery, smaller monochrome portraits and technical role captions.
3. **External recognition** — White press marks on a dark warm-violet field with large outlined lettering.
4. **Utility ending** — Shared four-column footer, with warmer atmospheric color and no separate trial block.

**Transfer:** Use personality and real people instead of copying the product-demo pacing.

### Commercial evaluation and objection handling

1. **Reassurance** — Centered promise above a wide bordered media presentation.
2. **Offer structure** — Tall plan constellation with the middle bundle glowing violet.
3. **Value proof** — Savings prompt, three open benefits and alternating media/text explanations.
4. **Social proof** — Three review-summary panels.
5. **Comparison** — Outline backdrop word and detailed hairline matrix.
6. **Objection handling** — Monumental outline FAQ word, adjacent contact help and violet accordion list.
7. **Utility ending** — Blue-violet atmospheric footer immediately after questions.

**Transfer:** Use denser structured information only where a buyer is evaluating; keep the same cinematic materials around it.

### Customer confidence and fit

1. **Social proof** — Rating capsule, centered headline and a two-row quote wall.
2. **Audience relevance** — Bright indexed ticket rail explains who benefits.
3. **Independent validation** — Three review-summary panels.
4. **Closing call** — Centered invitation and one glass demo action.
5. **Utility ending** — Pink-violet atmosphere carries the shared footer.

**Transfer:** Let customer narratives carry the story and vary proof format before the final invitation.

## Writing

Confident, slightly irreverent enterprise writing with a premium travel metaphor. Technical claims are delivered plainly, then relieved by a short colloquial line or editorial wink.

**Do not copy:** Do not reuse the company or product names, logo, proprietary artwork, customer quotations, competitor claims, numerical performance assertions, ratings, certifications, patents or customer counts. Replace these with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we for the maker. Product descriptions alternate direct benefits with concise factual explanations.
- **Rhythm:** Headlines favor short declarative phrases and occasional rhetorical questions. Supporting paragraphs use ordinary sentences; emphatic short fragments often arrive in pairs. Capitalized equipment labels supply a separate clipped register.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category, then make its changed location or experience the reveal. | 4–10 words | “A Secure Web Gateway”<br>“on your device” |
| Supporting benefit | A decisive sentence removing one familiar pain. | 5–12 words | “Never re-route the Internet again.” |
| Chapter heading | Use colloquial confidence rather than abstract enterprise nouns. | 3–8 words | “One very-fast SWG”<br>“Maximum impact. Zero trade-offs.” |
| Primary action | Immediate verb plus a clear destination or identity provider. | 2–5 words | “Try now with Google”<br>“Book a Demo” |
| Reassurance | State the low-friction next step, then a short concrete explanation. | 8–18 words | “Start for free, upgrade when you're ready. Installs in minutes.” |
| Closing invitation | Give a direct invitation and remove a practical obstacle. | 5–16 words | “Trial it now, for free.” |
| Footer manifesto | Dry dissatisfaction with the old way, followed by plain, repeated improvements. | A short paragraph with a final fragment | “It’s not that we’re mad at yesterday’s cybersecurity. Just disappointed. So we made it better. We made it easier. We made it dope.” |

**Words and phrasing to use:** direct; instant; on your device; first-class; easy; ready; one console; zero trade-offs

**Avoid:** synergistic; best-in-class solutions; revolutionary ecosystem; unlock limitless potential; exclamation-heavy hype

**Rules:**

- Anchor every technical benefit in a concrete mechanism or visible product state.
- Keep metaphors coherent: movement, routes, access and ease form one language rather than unrelated space and gaming clichés.
- Use short contrast pairs to make a point, then stop; do not turn the whole page into slogans.
- Keep technical acronyms in explanatory sections, with a human-readable benefit nearby.

## Do's and Don'ts

### Do

- Pair the 88px grotesk opening with upright and italic serif words at the same scale.
- Keep default reading sections near-black and reserve saturated light for the scene, bright tickets, selected controls and ending.
- Preserve the split-flap board's 100px rows and 16px rhythm.
- Give ticket rails 24px gutters and enough overflow to show that browsing continues.
- Use a 64px glass pill for the closing action and a 4px-cornered compact action in the navigation.
- Stage the product as one dominant panel with a few detached informative callouts.
- Use 20px light body copy with a 1.6 line-height for relaxed explanations.
- Give the final footer four clear information groups and an atmospheric background rather than a flat strip.

### Don't

- Do not turn #af50ff into a solid background for every section; it is primarily active ink, edge light and atmosphere.
- Do not replace editorial serifs with a script or handwriting face; their contrast is typographic, not casual.
- Do not make all headings bold: the 48px rail heading, 50px closing line and 96px product display are deliberately lighter.
- Do not put heavy drop shadows on every dark card; thin edges and luminous materials do most of the separation.
- Do not reuse the glowing middle-plan treatment on every ordinary content card.
- Do not shrink the ticket rail into four equal small columns; the 423px artifacts need their visual mass.
- Do not mix the culture page's dense tracked role captions into ordinary body paragraphs.
- Do not render faint outline backdrop words as the only readable section title.

## Motion and responsive

### Motion

**Observed:**

- Glass closing actions declare a 0.2s transition; the play ring declares 0.1s and the fixed navigation 0.15s.
- Comparison cells declare background-color 0.2s cubic-bezier(0.215,0.61,0.355,1). Testimonial cards declare background 0.3s.
- The presentation uses sliced split-flap letters, overlapping numbered console panels and horizontal card rails.

**Transfer:**

- Keep physical letter slicing and stepped interface layering as the characteristic movement language; static versions must still retain the seam and overlap.
- Use the declared violet inset illumination on primary-action hover rather than a scale-up effect.

**Unknown:**

- Scroll choreography timing, video playback behavior, easing for undeclared interactions and focus-visible styling are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 480px, 600px, 767px, 768px, 991px, 1280px, 1440px and 1920px. The comparison backdrop uses 14vw type.
- The desktop opening content is wrapped in flexible columns and its outer container has a 2240px maximum width.

**Transfer:**

- On narrower layouts, keep the headline before the access ticket and preserve the contrast of expressive type against a broad image; the ticket's metadata can simplify while the action stays clear.
- Keep ticket rails horizontally scrollable rather than reducing the artifacts to tiny tiles. Stack explanatory columns and pricing choices when their readable width no longer fits.
- Reduce decorative outline lettering independently of the readable heading; maintain a useful console view rather than scaling its labels into illegibility.

**Unknown:**

- Exact narrow-screen font sizes, stacking thresholds, mobile navigation and touch behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
