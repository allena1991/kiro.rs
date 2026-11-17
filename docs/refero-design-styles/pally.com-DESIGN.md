# Pally — paper objects, living conversations

## Overview

A warm, light product-marketing style that makes capable software feel like a helpful person. Plum-black grotesk typography sits on creamy paper, with bright blue conversations, softly lit miniature objects and small washes of pink and peach. Broad, airy chapters alternate with compact demonstrations and approachable, practical explanations.

### Essentials

- Headlines speak in tightly joined, plain-language phrases: the opening uses 68.2px/0.92, weight 700, -0.048em tracking; section leads use 54px/1.02, weight 600, -0.04em, often ending with a muted plum line.
- The first screen pairs a left-aligned promise with one tangible product object: a 1200px content area, 72px column gap and a 540×675px media stage, with headline, support and conversion all visible within 900px.
- Conversion feels like starting a conversation: 260×54px plum pill buttons sit above small underlined alternatives; a glowing glass composer with a blue send circle provides a signature invitation elsewhere on the page.
- Cream remains the dominant field: #fcf8f6 across the page, #2a0a1e for text and actions, white for raised panels. Saturation stays concentrated in blue messages and small paper objects, not full-width colored bands.
- Software is made tangible through cut-paper miniatures: cream envelopes, colored cards and simple dimensional objects carry soft directional shadows. Every marketing page needs this handmade material counterpoint; use layered SVG paper shapes when custom artwork is unavailable.
- End with identity at architectural scale: a 1328×353px, low-contrast wordmark artwork fills the foot of a warm gradient footer, below useful link columns. Use the new identity as oversized vector lettering rather than a normal-sized logo repeated at the bottom.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep plum | `#2a0a1e` | `--color-ink` | text, action, accent | Primary headings, main actions and dark graphic details. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Message blue | `#0b84fe` | `--color-blue` | accent, action, surface | Outgoing message shapes, send arrow circles and the composer caret. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversation black | `#000000` | `--color-black` | text | Typed composer text and conversational demonstrations. |
| Soft plum | `#69515f` | `--color-body` | text, link | Supporting copy and ordinary links; visible result of plum at 70% over cream. |
| Caption plum | `#7a6470` | `--color-caption` | text | Eyebrows and secondary descriptions; plum at 62% over cream. |
| Tertiary plum | `#97868e` | `--color-tertiary` | text | Compatibility notes and low-priority links; plum at 48% over cream. |
| Receding headline | `#a08f97` | `--color-dim` | text | The last line of a section headline; plum at 44% over cream. |
| Paper rule | `#e3dbdc` | `--color-edge` | border | Visible plum-at-12% rule over cream; section and footer separators. |
| Warm footer paper | `#f8f0ec` | `--color-footer-wash` | background | Bottom stop of the footer gradient. |
| Cream paper | `#fcf8f6` | `--color-canvas` | background | Dominant page field and inverse text on small dark treatments. |
| Milky glass | `#fdfbfa` | `--color-glass` | surface | Visible white-at-48% glass over cream; keep actual transparency in the composer. |
| Porcelain chip | `#fffefe` | `--color-chip` | surface | Visible white-at-86% integration chips over cream. |
| Panel white | `#ffffff` | `--color-white` | surface, text | Cards, interface sheets and inverse button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing or itemized value illustrations | Aubergine hardware | `#552a47` | `--color-printer` | surface | Small dimensional receipt-printer housing. |
| pricing or itemized value illustrations | Receipt ink | `#2b2127` | `--color-receipt-ink` | text | Monospace printing. |
| pricing or itemized value illustrations | Receipt stock | `#fffdf9` | `--color-receipt-paper` | surface | Warm printed-paper illustration. |

## Typography

- **-apple-system** — All marketing headings, prose and interface labels. System grotesk with a high x-height, compact bold headlines and neutral regular prose. If unavailable, use **Inter**. Use 400, 500, 600 and 700; preserve tight tracking and line breaks. Font stack: "-apple-system", system-ui, "SF Pro Text", "SF Pro Display", Inter, sans-serif.
- **ui-monospace** (only for pricing or itemized value illustrations) — Printed receipt text, line items and totals. Utilitarian fixed-width printing, with a bold total. Font stack: "ui-monospace", "SF Mono", SFMono-Regular, Menlo, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| closing-display | -apple-system | 600 | 135.4px | 0.94 | -0.048em | size clamp(64px, 9.4vw, 140px) | Monumental short closing line. |
| hero | -apple-system | 700 | 68.2px | 0.92 | -0.048em | fixed | Default marketing opening; three compact lines of direct promise. |
| heading | -apple-system | 600 | 54px | 1.02 | -0.04em | fixed | Main chapter headings and the compact closing invitation. |
| feature-title | -apple-system | 600 | 26px | 1.12 | -0.032em | fixed | Large feature tile titles; narrower tiles use 21px/1.12 and -0.028em. |
| hero-support | -apple-system | 400 | 18.7px | 1.45 | -0.012em | fixed | Two short supporting lines beneath the opening promise. |
| body | -apple-system | 400 | 17px | 1.45 | -0.012em | fixed | Main explanatory paragraphs. |
| card-body | -apple-system | 400 | 15px | 1.42 | -0.008em | fixed | Feature tile explanations. |
| footer-link | -apple-system | 400 | 15px | 1.3 | -0.008em | fixed | Footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing chapters | value-display | -apple-system | 600 | 83.5px | 0.96 | -0.046em | fixed | Oversized price promise beside a receipt. |
| feature explainers and catalogs | editorial-title | -apple-system | 700 | 72px | 0.98 | -0.045em | fixed | Feature explainer and catalog openings. |
| feature explainers | editorial-heading | -apple-system | 600 | 40px | 1.05 | -0.038em | size clamp(30px, 2.8vw, 40px) | Left-rail chapter headings. |
| pricing or itemized value illustrations | receipt-total | ui-monospace | 700 | 19px | 1.56 | 0.02em | fixed | Emphatic printed total. |
| catalogs | catalog-title | -apple-system | 600 | 18px | 1.2 | -0.024em | fixed | Compact catalog card titles. |
| feature explainers | editorial-body | -apple-system | 400 | 17.5px | 1.6 | -0.01em | fixed | Longer prose and lists in the right column. |
| catalogs | catalog-body | -apple-system | 400 | 14px | 1.42 | -0.006em | fixed | Two-line catalog descriptions. |
| catalogs | filter | -apple-system | 500 | 14px | 1.2 | normal | fixed | Category controls. |
| pricing or itemized value illustrations | receipt | ui-monospace | 400 | 13px | 1.56 | normal | fixed | Receipt lines and small centered printing. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Tracking tightens with scale: small markers have slightly positive tracking, body text slightly negative tracking, and display lettering compresses to roughly -0.04em to -0.048em.
- Use sentence case, not uppercase, for marketing labels and headlines. A dim continuation keeps the same size and weight as its dark first line.
- Keep display lines close enough to feel like a single compact object; do not apply body leading to headlines.
- Eyebrows use the main sans at 13px, weight 500, normal leading and 0.01em tracking. Component labels and composer text keep their complete type declarations in their component CSS.

## Layout

**Density:** Airy chapters with dense, legible miniature demonstrations; space separates ideas while close text and object groupings make each chapter feel cohesive.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 7px | Title-to-description spacing in feature tiles and icon-to-chip labels. | fixed |
| 12px | Eyebrow rule gap and compact card groups. | fixed |
| 14px | Primary action to alternative channels; catalog grid gaps. | fixed |
| 16px | Bento grid gutters. | fixed |
| 18px | Eyebrow to section heading. | fixed |
| 30px | Large tile vertical padding. | clamp(22px, 2.2vw, 30px) |
| 32px | Large tile horizontal padding and grouped footer gaps. | fixed |
| 44px | Heading area to integration stage. | fixed |
| 56px | Page side padding and broad grid separations. | fixed |
| 72px | Split-hero gap; vertical padding of explainer chapters. | fixed |
| 108px | Short divider sections and compact closing section padding. | fixed |
| 117px | Main landing chapter vertical padding. | fixed |

### Containers and grids

- **main-container**: max width 1200px · side padding 56px. Centered marketing content; at 1440px the content edges sit at 120px and 1320px.
- **opening-stage**: max width 1312px · 2 columns · gap 72px · side padding 56px. A flexible left copy column paired with a 540px-wide right media stage.
- **bento**: 4 columns · gap 16px. Mix double-width 592px tiles with 288px tiles, reversing emphasis across rows.
- **footer**: max width 1440px · side padding 56px. Wider than the main content, with brand information at left and four link columns at right.
- **explainer** (only for feature explainers): 2 columns · gap 64px. 4:8 proportional columns: a compact title rail and a prose/demo rail, with paragraphs capped at 700px.
- **catalog** (only for catalogs): 4 columns · gap 14px. 290px cards with aligned rows inside the main container.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | feature-tiles | 28px |
|  | conversation-sheet | 32px |
|  | composer-field | 53.3px |
|  | round-controls | 50% |
| catalogs | catalog-cards | 24px |
| feature explainers | explainer-cards | 22px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| feature-card | `0px 0px 0px 1px rgba(70,22,40,0.05), 0px 1px 2px 0px rgba(70,22,40,0.04), 0px 18px 36px -28px rgba(70,22,40,0.3)` | White feature cards; faint outline plus close shadow, not a dark floating slab. |
| primary-action | `0px 10px 26px -10px rgba(70,22,40,0.55)` | Plum conversion pills. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #fcf8f6; color: #2a0a1e`

**Observed:** An almost-white warm paper field carries the entire narrative.

**Transfer:** Keep the field continuous through chapters rather than using alternating colored bands.

#### White paper card · level 1

**Use:** Feature demonstrations.

**CSS:** `background: #ffffff; border-radius: 28px; box-shadow: 0px 0px 0px 1px rgba(70,22,40,0.05), 0px 1px 2px 0px rgba(70,22,40,0.04), 0px 18px 36px -28px rgba(70,22,40,0.3)`

**Observed:** Subtle pink, yellow, mint or lilac light stays inside the card behind its object.

**Transfer:** Use a restrained local wash without tinting the text or reducing its contrast.

#### Composer glass · level 2

**Use:** Signature closing invitation.

**CSS:** `background: rgba(255,255,255,0.48); border-radius: 53.3px; backdrop-filter: blur(14px) saturate(2.1) brightness(1.05); box-shadow: 0px 0px 0px 1px rgba(70,22,40,0.07), 0px 30px 60px -26px rgba(70,22,40,0.34), 0px 3px 8px -2px rgba(70,22,40,0.08), inset 0px 2px 1.5px 0px rgba(255,255,255,0.95), inset 0px -2px 3px 0px rgba(70,22,40,0.04)`

**Observed:** A bright upper-left reflection and soft pink-peach halo make the field feel rounded and translucent.

**Transfer:** Reserve this material for the closing action instead of making every panel glass.

#### Footer paper · level 0

**Use:** Shared closing identity field.

**CSS:** `background: linear-gradient(#fcf8f6, #f8f0ec); border-top: 1px solid rgba(42,10,30,0.12)`

**Observed:** Useful links give way to an immense tonal identity mark.

**Transfer:** Keep the footer warm and light even when the logo itself is dark elsewhere.

#### Receipt stock · level 1

**Only for:** pricing or itemized value illustrations

**Use:** Printed value proof.

**CSS:** `background: #fffdf9; padding: 26px 30px 40px`

**Observed:** Long paper strip, jagged torn lower edge and a dark printer bar above; shadows give it physical depth.

**Transfer:** Use itemized proof relevant to the new offer, not a conventional pricing-table imitation.

## Components

### Navigation

**Use:** Persistent lightweight wayfinding.

**CSS:** `display: flex; align-items: center; height: 58px; padding: 0px 56px; gap: 32px; font-size: 15px; font-weight: 400; line-height: normal; letter-spacing: -0.1px`

**Observed:** Small identity at left, right-aligned links and Header action. The bar is fixed above the content. A separate 36px announcement strip can sit above it when an actual announcement exists.

**States:** Declared: hover links change to #2a0a1e.

### Primary button

**Use:** Default main conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #2a0a1e; color: #ffffff; width: 260px; height: 54px; padding: 0px 28px; border-radius: 9999px; box-shadow: 0px 10px 26px -10px rgba(70,22,40,0.55); font-size: 17px; font-weight: 600; line-height: normal; letter-spacing: -0.2px`

**Observed:** A single centered label; alternative underlined channels sit 14px beneath, not as competing filled buttons.

**States:** Declared: hover translateY(-1px), box-shadow 0 14px 30px -10px rgba(70,22,40,0.6).

### Header action

**Use:** Compact conversion at the right end of Navigation.

**CSS:** `display: flex; align-items: center; height: 34px; padding: 0px 15px; border-radius: 9999px; color: #2a0a1e; box-shadow: inset 0px 0px 0px 1.5px #2a0a1e; font-size: 13.5px; font-weight: 600; line-height: normal; letter-spacing: normal`

**Observed:** Outline treatment preserves the main page button's priority.

**States:** Declared: hover background #2a0a1e, color #fcf8f6.

### Feature tile

**Use:** Default capability proof card.

**CSS:** `background: #ffffff; border-radius: 28px; padding: 30px 32px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(70,22,40,0.05), 0px 1px 2px 0px rgba(70,22,40,0.04), 0px 18px 36px -28px rgba(70,22,40,0.3)`

**Text style:** `feature-title` — -apple-system 600 · 26px/1.12 · tracking -0.032em

**Observed:** Title, short explanation and understated arrow link share a corner; a large paper object and compact conversation demonstrate the benefit. Wide tiles span two grid columns; narrow tiles use 24px 26px 26px padding and 21px titles.

**Transfer:** Show one recognizable object and one concrete before/after exchange per capability.

### Integration chip

**Use:** Satellite controls around a central demonstration.

**CSS:** `display: inline-flex; align-items: center; gap: 7px; height: 36px; padding: 0px 14px 0px 10px; background: rgba(255,255,255,0.86); border-radius: 9999px; box-shadow: 0px 0px 0px 1px rgba(42,10,30,0.06), 0px 1px 2px 0px rgba(70,22,40,0.05), 0px 10px 22px -16px rgba(70,22,40,0.32); font-size: 13.5px; font-weight: 500; line-height: normal; letter-spacing: -0.1px`

**Observed:** Small 18px app symbol followed by text; fine curved lines connect chips to the central white sheet. One selected chip becomes plum with pale text.

**States:** Declared: hover white background, plum text, translateY(-1px) and deeper shadow; focus-visible border-radius 999px.

### Closing composer

**Use:** Signature action shaped as a prewritten message.

**CSS:** `display: flex; align-items: center; height: 106.6px; padding: 0px 98px 0px 38.4px; background: rgba(255,255,255,0.48); border-radius: 53.3px; backdrop-filter: blur(14px) saturate(2.1) brightness(1.05); color: #000000; font-size: 42.6px; font-weight: 400; line-height: normal; letter-spacing: -0.9px`

**Observed:** A separate round plus control at left and blue circular up-arrow at right turn Composer glass into one linked invitation. The full group is 900px wide; the field is 772px wide. The compact catalog version uses a 554×72px field, 36px radius and 28.8px text.

**Transfer:** Prefill a short, natural first request instead of displaying a generic email input.

### Footer links

**Use:** Practical navigation above the monumental identity.

**CSS:** `display: grid; gap: 11px; margin-top: 16px; color: rgba(42,10,30,0.7)`

**Text style:** `footer-link` — -apple-system 400 · 15px/1.3 · tracking -0.008em

**Observed:** Four category columns use small muted labels with a short rule. Brand promise and direct contact links sit separately on the left; a ruled legal row includes a right-aligned back-to-top link.

**States:** Declared: hover text changes to #2a0a1e.

### Catalog card

**Only for:** catalogs

**Use:** Selectable example or preset.

**CSS:** `display: flex; flex-direction: column; padding: 20px 20px 18px; background: #ffffff; border-radius: 24px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(70,22,40,0.05), 0px 1px 2px 0px rgba(70,22,40,0.04), 0px 14px 30px -26px rgba(70,22,40,0.3)`

**Text style:** `catalog-title` — -apple-system 600 · 18px/1.2 · tracking -0.024em

**Observed:** Colored circular icon plus title, two-line explanation, then a right-aligned blue request bubble near the bottom. A faint wash at the top ties the icon color to the card.

**States:** Declared: hover translateY(-2px), box-shadow 0 0 0 1px rgba(70,22,40,0.06), 0 2px 4px rgba(70,22,40,0.04), 0 26px 44px -28px rgba(70,22,40,0.38).

### Category filter

**Only for:** catalogs

**Use:** Compact category selection above a grid.

**CSS:** `display: flex; align-items: center; height: 44px; padding: 6px 16px; background: #ffffff; border-radius: 9999px; box-shadow: inset 0px 0px 0px 1px rgba(42,10,30,0.12); color: rgba(42,10,30,0.7)`

**Text style:** `filter` — -apple-system 500 · 14px/1.2

**Observed:** Wrap chips with 8px gaps; selected category is plum with white type.

**States:** Declared: hover inset outline becomes rgba(42,10,30,0.3), text #2a0a1e.

### Catalog search

**Only for:** catalogs

**Use:** Find an example before filtering.

**CSS:** `width: 380px; height: 46px; padding: 0px 16px 0px 44px; background: #ffffff; border-radius: 9999px; box-shadow: inset 0px 0px 0px 1px rgba(42,10,30,0.12)`

**Observed:** A small muted magnifier sits inside the left inset; the field precedes the wrapping category chips.

## Imagery and graphics

### Tangible product stage

**Use:** Hero media and focused demonstrations.

**Observed:** One nearly upright, lightly angled phone stands on cream with a soft ground shadow, dark thin rim and readable white conversation screen. It is isolated rather than embedded in a full photograph; peach-pink light blooms behind it. The 540×675px stage visually balances the left copy.

**Transfer:** Use one clean device, product object or framed outcome panel with the same near-frontal view and soft ground contact. A simple white dimensional frame holding a legible product outcome is the minimum alternative to a polished device render.

### Layered paper miniatures

**Use:** Signature feature art, supporting proof and closing ornaments.

**Observed:** Paper envelopes, a wax seal, clipboard, tickets, plane, flowers and small everyday objects use flat colored faces, folded edges and a little extrusion. Cream, pink, cobalt, tomato red, green and mustard appear locally; slight rotations and warm shadows keep them playful rather than glossy. Closing objects enter from the page edges around the centered action.

**Transfer:** Make a small set of objects that represent the new product's outcomes. Keep flat cut faces and believable soft shadows; simplified layered SVG silhouettes are sufficient if the material and scale remain consistent.

**Build:** Layer 3–6 SVG polygons per object: a cream base, a slightly offset darker backing, colored face pieces and thin folded-edge facets. Rotate each object slightly in a different direction, add a warm rgba(70,22,40,0.2) drop shadow below and right, and retain wide empty space around it. For an envelope use a rectangle, two triangular folds, a darker back sheet offset 12px and a small red circular seal.

### Soft local light

**Use:** Behind the hero object, selected feature art and the closing composer.

**Observed:** Low-contrast blush, peach and cream pools have no visible boundary and never become a full-page rainbow. White foreground panels remain legible.

**Transfer:** Keep the light subordinate to type and objects; match the soft glow, exact stops are not essential.

**Build:** Place two absolutely positioned elliptical radial gradients behind the object, one pink and one warm peach, each fading to transparent by 72%. Use rgba(232,102,75,0.12) for peach and rgba(255,190,206,0.25) for blush, overlap them slightly, blur 30px and keep their combined footprint close to the object rather than the whole section.

### Relationship and connection diagrams

**Use:** Explain invisible connections in a tangible way.

**Observed:** The people map uses fine concentric rings, radial labels and a dark central node on a pinkish field, paired with a white detail card. The integration diagram uses curved hairlines radiating to small labeled chips around a central conversation sheet.

**Transfer:** Map the new product's entities or workflow using thin, low-contrast lines and one clear focal panel rather than a dense technical network.

**Build:** Use an SVG viewBox scaled to a 700×519px map or 1200×600px integration stage. Draw concentric circles or cubic-bezier connector paths at 1px with rgba(42,10,30,0.1), place small nodes on rings, and layer one plum central node above a soft blush radial gradient. Keep labels small and sparse.

### Monumental tonal identity

**Use:** Required footer signature.

**Observed:** An enormous pale identity mark spans almost the entire footer width and meets the bottom edge, with letterforms and emblem treated as one graphic rather than live heading text.

**Transfer:** Use the new product's own wordmark or custom-set name as a low-contrast vector graphic, large enough to become the footer's final landscape.

**Build:** Place an SVG wordmark in a 1328×353px proportional frame with 56px side insets and 54px top spacing after the legal row. Fill it with plum at roughly 8% opacity over the warm footer gradient and clip overflow at the page bottom.

### Printed receipt proof

**Only for:** pricing or itemized value illustrations

**Use:** Memorable physical accounting of value.

**Observed:** A 404×678px cream receipt hangs beneath a 444×50px aubergine printer. Monospace line items use dotted leaders, dashed separators, a bold total, barcode and short closing note; the lower paper edge is irregularly torn.

**Transfer:** Translate the offer into an honest itemized receipt, service ticket or packing slip; preserve the physical paper metaphor without reusing the original economics.

**Build:** Use Receipt stock with a polygon bottom edge alternating shallow 3–14px notches; put the shadow on an outer wrapper so the torn edge casts it. Add a rounded plum bar above, a dark inset slot, a tiny green indicator, dotted leaders and an SVG barcode of alternating narrow vertical lines.

### Icons

**Observed:** Small interface icons are restrained rounded outlines, commonly 17–18px with 2px round strokes; integration symbols sit at 18px, while catalog icons use colored circular backings around 38–41px. Illustrative paper symbols are a separate, more dimensional family.

**Transfer:** Use rounded, simple outline symbols for controls and a distinct layered-paper treatment for narrative illustration; do not mix heavy solid UI glyphs into light labels.

## Section recipes

How recurring sections are built.

### First screen: Tangible promise opening

**Observed:** Cream canvas behind a fixed 58px Navigation bar, with a separate narrow announcement above when needed. In a 900px-tall first screen, the main composition is vertically centered beneath the header: a left copy column about half the 1200px content width and a 540×675px product stage at right, separated by 72px. The compact three-line hero uses dark plum, 68.2px/0.92 at 700; it occupies the upper half of the copy group. Two support lines follow after 31.7px, then a Primary button after 36px and underlined alternatives 14px below it. Back-to-front layers are cream, local blush light, grounded device, and the legible conversation screen. Headline, support, action, alternatives and complete primary object are visible inside the first 900px; the next narrative chapter begins below the fold.

**Transfer:** Pair a plain-language outcome with one isolated tangible demonstration. Without a device render, place a clean outcome panel in a thin dimensional frame with a ground shadow and local glow. Feature explainers open with an eyebrow, 72px editorial title and fuller prose beside a smaller relationship diagram; catalogs use the same editorial title above their search and grid.

**Avoid:** Do not center the default hero above a sprawling dashboard collage, or let the first action slip below the fold. Do not put the headline inside the product screen.

**Text style:** `hero` — -apple-system 700 · 68.2px/0.92 · tracking -0.048em

### Heading pair

**Observed:** An eyebrow with a short horizontal rule sits 18px above a heading. The heading may continue in dim plum on the next line. Split headers put body copy in the right half aligned near the headline baseline; centered chapters keep support directly underneath.

**Transfer:** Use the dark line for the main claim and the dim continuation for its conversational afterthought.

**Text style:** `heading` — -apple-system 600 · 54px/1.02 · tracking -0.04em

### Object and evidence chapter

**Observed:** Within 117px vertical chapter padding, one central object or relationship graphic is balanced by slim text or detail columns. Trust content uses small ruled explanations around a sealed envelope; relationship content pairs a 700×519px radial map with a 430px detail card.

**Transfer:** Explain a less visible benefit through one physical metaphor and short, inspectable evidence points.

### Capability bento

**Observed:** A heading pair precedes the bento by 45px. Feature tiles use a four-column grid with 16px gaps: one double-width card and two single-width cards form one row, with reversed emphasis in the next. Paper miniatures, soft local light and small conversations occupy much of each tile, while titles and explanations remain short.

**Transfer:** Vary emphasis according to the content's importance rather than making all capability cards identical.

**Text style:** `feature-title` — -apple-system 600 · 26px/1.12 · tracking -0.032em

### Conversational objections

**Observed:** A 54px heading and short explanation at left face a 650×738px white conversation sheet at right, with 32px corners. Questions align right in blue speech bubbles; an expanded answer appears left in gray, turning the FAQ into an exchange rather than a stack of accordion bars.

**Transfer:** Write real objections as short customer messages and answer them in direct, concrete language.

**Text style:** `heading` — -apple-system 600 · 54px/1.02 · tracking -0.04em

### Monumental closing invitation

**Observed:** A 750px cream closing stage centers the 135.4px short closing line, a single support sentence and Closing composer. Paper miniatures enter from the edges without blocking the action; a soft local light pool sits behind the composer. Small reassurance and alternative links align below the action. Catalogs use a simpler 507px closing stage with a 54px heading and compact composer.

**Transfer:** Finish with a brief handoff to the reader and an action that already looks begun; keep the elaborate edge objects for broad marketing compositions.

**Text style:** `closing-display` — -apple-system 600 · 135.4px/0.94 · tracking -0.048em

### Identity footer

**Observed:** Footer paper is 788px tall at desktop. A small brand promise and direct contact options sit at left; four Footer links columns sit at right. A horizontal rule separates a muted legal and back-to-top row. After 54px, Monumental tonal identity fills a 1328×353px region along the bottom.

**Transfer:** Make the useful information compact enough to leave the last visual impression to the oversized tonal identity.

### Itemized value

**Only for:** pricing chapters

**Observed:** A split layout with a 72px gap pairs an 83.5px price promise, supporting copy and Primary button at left with Printed receipt proof at right. A small ruled explanation below the action answers how the offer works.

**Transfer:** Make the economic model understandable through a physical proof artifact and plain language rather than extra badge treatments.

**Text style:** `value-display` — -apple-system 600 · 83.5px/0.96 · tracking -0.046em

### Explainer chapter rail

**Only for:** feature explainers

**Observed:** A 1px top rule and 72px vertical padding frame each chapter. A 40px heading with eyebrow sits in a 4-part left rail; prose, lists, 22px-radius cards or paired phone demonstrations sit in the 8-part right rail with a 64px gap. The ending uses small example cards and a Primary button, then one concise assurance chapter before Footer paper.

**Transfer:** Use this calmer, prose-led system for detailed mechanics and permissions rather than extending the full hero treatment to every topic.

**Text style:** `editorial-heading` — -apple-system 600 · 40px/1.05 · tracking -0.038em

### Example catalog

**Only for:** catalogs

**Observed:** Editorial title and concise introduction lead to Catalog search, wrapping Category filters and a four-column Catalog card grid with 14px gutters. Small colorful circular icons and blue request bubbles make examples immediately actionable. A compact composer closing leads into the shared footer.

**Transfer:** Offer reusable presets, workflows or examples in the same object-like cards, with a visible example request rather than abstract category descriptions.

**Text style:** `editorial-title` — -apple-system 700 · 72px/0.98 · tracking -0.045em

## Page flow

**Storyline:** Direct promise → tangible demonstration → practical capabilities → trust and value explained plainly → low-friction invitation → monumental identity.

### Broad product landing page

1. **Promise** — Split copy-and-object opening with a complete action group.
2. **Product demonstration** — A short promise bridge with a small live activity count, then a relationship visualization and tangible workflow examples.
3. **Capability chapters** — Asymmetric paper-art feature bento and integration satellites around a central conversation.
4. **Trust and value** — Ruled assurance points around a physical object, followed by itemized receipt pricing.
5. **Objection handling** — Interactive conversation-style FAQ.
6. **Closing call** — Monumental short line, glass composer and paper ornaments, then the wide tonal-identity footer.

**Transfer:** Borrow the alternation between airy object chapters and compact practical proof; adapt chapter number and order to the new offer.

### Detailed feature explainer

1. **Promise** — Editorial title and fuller prose beside a small relationship diagram.
2. **Mechanism** — Starting-point cards, paired conversations and numbered instructions.
3. **Capability detail** — Ruled two-column chapters containing prose, lists and small icon cards.
4. **Control and limits** — Explicit boundaries and side-by-side example exchanges.
5. **Closing call** — Three small example-request cards and a main action, followed by a concise privacy assurance and the shared monumental footer.

**Transfer:** Keep detailed explanations in the calmer chapter-rail variant; make limits as visible as capabilities.

### Actionable example catalog

1. **Orientation** — Editorial promise, short definition and direct action.
2. **Discovery** — Search and pill categories above a dense four-column preset grid.
3. **Closing call** — Invitation to describe a custom need through the compact glass composer.
4. **Identity** — The same link columns, legal row and immense pale footer mark.

**Transfer:** Use for templates, integrations or use cases where visitors should select an example and begin immediately.

## Writing

Warm, matter-of-fact and casually capable. The product sounds like a resourceful person who can handle specifics, not a futuristic platform delivering grand transformations.

**Do not copy:** Do not reuse the Pally name, logo, distinctive artwork, personal names, sample conversations, usage numbers, free-service promises, privacy guarantees or business-model claims. Examples below demonstrate rhythm only; write truthful equivalents for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Marketing refers to the product by name or it; conversations use a brief first-person voice.
- **Rhythm:** Short sentence-case headlines, often with a period. Support lines use everyday verbs; explanatory prose becomes longer only when mechanics or limits need clarity. Fragments and contractions feel natural, without salesy exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Ownership, ordinary product category, then a simple next action. | 3 compact lines | “Your own personal assistant. Just text [Brand].” |
| Capability headline | Describe work disappearing from the reader's day. | 5–9 words | “Six things you’ll stop doing yourself.” |
| Support | A concrete verb list followed by a human payoff. | 1–2 short sentences | “It remembers, books, chases and calls.” |
| Trust | Name an assurance, then state its practical boundary. | Short label plus a sentence | “It checks first.”<br>“Before it sends, books or buys anything you haven’t already asked for or approved.” |
| Primary action | Verb plus product or direct object, naming the real next step. | 2–4 words | “Text [Brand]” |
| Closing line | Brief conversational handoff. | 2–6 words | “Your move.”<br>“Have your own recipe in mind?” |

**Words and phrasing to use:** your own; just; keeps track; asks first; hand it over; books; chases; when it matters

**Avoid:** revolutionary; unlock your potential; AI-powered ecosystem; seamless synergy; supercharge; enterprise-grade everything

**Rules:**

- Lead with the practical outcome, not the underlying technology.
- Explain limits in the same calm language as benefits.
- Use real objects, times and tasks in demonstrations so the conversation can be understood immediately.
- Keep miniature exchanges informal and concise; marketing prose stays properly punctuated.
- State the commercial model plainly where value is discussed.

## Do's and Don'ts

### Do

- Keep the main canvas #fcf8f6 and primary ink #2a0a1e.
- Set the default hero at 700 with 0.92 leading and -0.048em tracking.
- Use 54px/1.02 section heads with a dim continuation when a second thought is needed.
- Keep main content at 1200px and large chapter padding at 117px.
- Combine 28px white feature tiles with 16px bento gutters.
- Use a 260×54px filled pill for the main action and a 34px outlined pill in the header.
- Give objects layered paper edges, warm shadows and localized light.
- Preserve the giant pale footer identity and glass conversational invitation as signature devices.

### Don't

- Do not make cobalt blue the canvas or the default marketing heading color; it belongs to messages and send controls.
- Do not turn all buttons into sharp rectangles or use 8px corners on the feature tiles.
- Do not use a geometric display novelty font instead of the compact system grotesk.
- Do not spread high-opacity gradients across entire sections; the color belongs behind a local object.
- Do not apply the 135px closing type to every chapter; ordinary leads are 54px.
- Do not replace the oversized footer art with a tiny centered copyright-only ending.
- Do not use monochrome technical wireframes as the only imagery; the paper-object counterpoint is essential.
- Do not style every panel as translucent glass; the standard feature surface is white paper.

## Motion and responsive

### Motion

**Observed:**

- Declared: main pills transition transform over 0.3s with cubic-bezier(.22,.7,.12,1) and shadow over 0.3s; hover lifts them 1px.
- Declared: cards transition transform and box-shadow over 0.6s with cubic-bezier(.22,.7,.12,1); catalog hover lifts 2px.
- Declared: integration chip color, background and shadow transition over 0.5s, transform over 0.6s, using cubic-bezier(.22,.7,.12,1).
- Declared: navigation color changes over 0.25s; filter changes over 0.2s. The live indicator has a 2.4s ease-out infinite animation and the composer caret a 1.06s step-end blink.
- Rotating examples include small pause controls.

**Transfer:**

- Keep motion on the scale of handling small objects: 1–2px hover lifts, modest shadow changes and a blinking prefilled-message caret.
- For any rotating demonstration, keep a visible pause control near its caption.

**Unknown:**

- Exact choreography and timing of scroll-driven scenes and full demonstration playback.

### Responsive

**Observed:**

- Declared width breakpoints include 699/700px, 899/900px, 999px, 1099/1100px and 1199/1200px.
- Closing display uses clamp(64px, 9.4vw, 140px); explainer headings use clamp(30px, 2.8vw, 40px).

**Transfer:**

- On narrow layouts, stack the copy before the isolated object and retain the complete action group before the next chapter.
- Reduce bento and catalog column counts while keeping the small conversation examples readable; move diagrams and detail cards into a vertical sequence.
- Scale the footer identity proportionally and keep it clipped at the lower edge; reposition closing paper ornaments away from the composer.

**Unknown:**

- Exact mobile container padding, collapsed navigation construction and card stacking breakpoints.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
