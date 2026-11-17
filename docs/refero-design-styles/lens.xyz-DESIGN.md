# Lens — playful contour systems

## Overview

A bright, friendly technology style that makes infrastructure feel approachable rather than industrial. White space and charcoal grotesk typography carry the message, with whisper-pastel contour drawings, soft organic badges and occasional vivid product imagery. It suits platforms, developer products and ecosystems that need both technical credibility and an inviting consumer face; the overall density is low.

### Essentials

- A small friendly emblem leads, not an enormous slogan: center an approximately 150×100px organic symbol above a 46px/1.2, weight-600 Saans headline and a 20px/1.45 muted support line within a 1082×460px opening stage.
- Technical structure is drawn almost in pencil: fine pastel curved lines, faint dashed section edges and softly irregular icon enclosures sit on white. Include this contour language and an outlined organic footer pattern even when no product artwork is available; SVG paths and an original geometric emblem are the fallback.
- Headings speak in two tones at one scale: 28px/1.35, weight-500 Saans pairs a charcoal proposition with a 60%-opacity charcoal explanation; the centered exploration variant uses Inter 28px/1.45 for its second line.
- Actions are compact little blocks, not pills: a black 44px-high primary with 10px corners sits beside a white 44px-high secondary with 8px corners and a 1px shadow-edge; smaller actions are 36px high. A tiny northeast arrow finishes the label.
- White is the dominant field across the full page; saturation is concentrated inside product media and small identity marks. Paired 550×705px showcases with 40px corners can hold vivid pink, lavender and blue imagery, while supporting illustration panels remain nearly white.
- Proof stays human-sized: 21px/1.4, weight-500 figures sit beneath soft outlined badges in a centered three-column row, rather than becoming billboard numerals. The ending returns to a white patterned footer with a small logo and sparse 14px link columns.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Affiliation blue | `#3654ff` | `--color-blue` | text, link | A single compact partner-name accent, not the general link color. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black action | `#000000` | `--color-primary` | action, background | Default primary conversion surface. |
| Charcoal | `#2c2d30` | `--color-ink` | text, accent | Primary headings, titles, emblem and icons. |
| Soft charcoal | `#808183` | `--color-muted` | text, link | Supporting text and navigation; charcoal at 60% opacity over white. |
| Control edge | `#eeeeee` | `--color-control-edge` | border | Charcoal at 8% opacity around circular carousel controls. |
| Button edge | `#f2f2f2` | `--color-edge` | border | Black at 5% opacity used as a secondary button's 1px shadow-edge. |
| Lavender backing | `#f4f1f6` | `--color-showcase` | surface | Backing under vivid product showcase imagery. |
| Frosted caption | `#f8f8f8` | `--color-glass` | surface | Visible light caption band; rgba(245,245,245,0.72) over a light backing, with blur. |
| Badge wash | `#f9f9f9` | `--color-badge` | surface | Charcoal at 3% opacity for the compact affiliation badge. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page field, secondary buttons and reverse primary-action labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| developer landing pages | Builder green | `#00b94a` | `--color-developer-green` | action | Saturated green primary action in the developer-oriented variant. |
| related-product closing promotions | Mint halo | `#e7ffec` | `--color-halo` | background | Very pale green concentric promotion field; green at 12% opacity is further reduced by animated layer opacity. |
| technical capability pages | Quiet panel | `#fbfbfb` | `--color-subtle` | surface | Nearly white feature-card field, using charcoal at 2% opacity. |

## Typography

- **saans** — Hero, section headings and compact statistics. Friendly contemporary grotesk with rounded joins, a substantial x-height and gently geometric shapes. If unavailable, use **DM Sans**. Use weights 500–600; retain normal tracking for headings. Font stack: "saans", "DM Sans", Arial, sans-serif.
- **inter** — Supporting text, navigation, descriptions, captions and actions. Compact, legible UI grotesk with slightly negative tracking. Font stack: "inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | saans | 600 | 46px | 1.2 | normal, features "ss01" | Centered first-screen headline. |
| heading | saans | 500 | 28px | 1.35 | normal | Section propositions and their same-size muted continuations. |
| heading-support | inter | 500 | 28px | 1.45 | -0.018em | Centered exploration section's explanatory second line. |
| stat | saans | 500 | 21px | 1.4 | normal | Numeric values, suffixes and short categorical proof. |
| hero-support | inter | 400 | 20px | 1.45 | -0.025em, features "cv11" | One muted sentence under the opening headline. |
| item-title | inter | 500 | 18px | 1.4 | -0.015em | Card titles and inline title-plus-description feature statements. |
| body-lg | inter | 400 | 18px | 1.45 | -0.0167em | Stat labels and standalone supporting descriptions. |
| showcase-name | inter | 600 | 18px | 1.1 | 0.08em, uppercase | Product name on the frosted showcase caption. |
| body | inter | 400 | 16px | 1.4 | -0.022em | Short descriptions in centered discovery tiles. |
| action | inter | 500 | 15px | 1.1 | -0.009em | Labels inside the two opening actions. |
| action-small | inter | 400 | 14px | 18px | -0.006em | Compact secondary-action container text; the inner label has a medium visual weight. |
| footer-link | inter | 400 | 14px | 1.4 | -0.006em | Muted footer links. |
| footer-title | inter | 500 | 14px | 1.4 | -0.006em | Dark footer column headings. |
| showcase-caption | inter | 500 | 11px | 1.45 | 0.06em, uppercase | Small proof or availability line under a showcase name. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| related-product closing promotions | promotion-support | saans | 500 | 26px | 1.35 | 0.015em | Centered descriptor in the related-product closing promotion. |

**Notes:**

- Keep the first headline compact enough to remain a single centered line on desktop; its scale is only modestly larger than the rest of the page.
- The proposition and its continuation often share size and weight; color, not a new scale, separates them.
- Use uppercase tracking only for showcase metadata, not general navigation or section headings.

## Layout

**Density:** Airy overall, with compact text groups inside generous white sections.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Title-to-description gaps and stat-value-to-label gaps. |
| 16px | Hero headline-to-support gap, icon-to-text rhythm and action-pair gap. |
| 24px | Hero support-to-actions gap and spacing between paired showcase cards. |
| 32px | Tile vertical padding and capability-grid column gap. |
| 36px | Opening emblem-to-text separation. |
| 48px | Default section inset, content-group separation and footer row gap. |
| 64px | Technical section top and bottom padding. |
| 104px | Desktop footer column separation. |

### Containers and grids

- **content stage**: max width 1082px · side padding 48px. Centered structural stage; inset content is 986px wide, while the opening artwork fills the stage.
- **site chrome**: max width 1178px · side padding 48px. Header and footer outer container, yielding an aligned 1082px inner span.
- **showcase pair**: max width 1124px · 2 columns · gap 24px. Two equal 550px-wide product stages, slightly wider than the standard inner content.
- **proof row**: max width 800px · 3 columns · gap 0px. Centered three-part proof with equal widths and no heavy separators.
- **discovery rail**: max width 986px · gap 24px. Horizontal row of 286px-wide tiles; partially visible neighboring content implies continuation.
- **capability grid** (only for technical capability pages): 2 columns · gap 32px. Two 477px-wide cards with 16px row spacing.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary actions | 10px |
|  | secondary actions | 8px |
|  | showcase cards | 40px |
|  | app icons | 20px |
|  | badge and carousel controls | 9999px (pill) |
| technical capability pages | feature cards | 16px |
| related-product closing promotions | promotion logo | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| header seam | `rgba(44, 45, 48, 0.04) 0px 1px 0px 0px` | Almost invisible division beneath the fixed navigation. |
| secondary edge | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px` | Outline-like shadow on white secondary actions. |
| primary relief | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | Subtle physical relief on black conversion buttons. |
| floating control | `rgba(44, 45, 48, 0.08) 0px 8px 24px 0px` | Carousel arrows above the pastel rail. |

### Surfaces

#### White field · level 0

**Use:** All ordinary page sections.

**CSS:** `background: #ffffff; color: #2c2d30`

**Observed:** Continuous white space rather than alternating full-bleed color bands.

**Transfer:** Let imagery and thin graphic boundaries distinguish sections.

#### Showcase backing · level 1

**Use:** Large product demonstration cards.

**CSS:** `background: #f4f1f6; border-radius: 40px; overflow: hidden`

**Observed:** Tall equal stages contain a saturated media backdrop, device view and lower caption band.

**Transfer:** Use this surface for the strongest visual proof rather than every feature.

#### Frosted caption · level 2

**Use:** Bottom strip of a product showcase.

**CSS:** `background: rgba(245, 245, 245, 0.72); backdrop-filter: blur(16px); padding: 12px 18px`

**Observed:** A patterned translucent band spans the card; product identity is grouped on the left and acquisition action on the right.

**Transfer:** Keep the media visible through the light band and labels dark.

#### Quiet feature panel · level 1

**Only for:** technical capability pages

**Use:** Illustrated capabilities and paired tooling cards.

**CSS:** `background: rgba(44, 45, 48, 0.02); border-radius: 16px; overflow: hidden`

**Observed:** Cards are only slightly separated from white; oversized outline illustrations can protrude beyond the text area.

**Transfer:** Use soft drawing and compact explanations, not dark borders or strong elevation.

#### Halo stage · level 0

**Only for:** related-product closing promotions

**Use:** Atmospheric centered final promotion.

**CSS:** `background: #ffffff; overflow: hidden; position: relative`

**Observed:** Two translucent green circular fields radiate behind a white circular logo; the stage is bounded by faint dashed guide lines.

**Transfer:** Keep the action and text opaque while the colored fields remain pale.

## Components

### Fixed navigation

**Use:** Persistent site orientation.

**CSS:** `height: 80px; position: fixed; background: #ffffff; box-shadow: rgba(44, 45, 48, 0.04) 0px 1px 0px 0px; display: flex; align-items: center; justify-content: center`

**Text style:** `footer-title` — inter 500 · 14px/1.4 · tracking -0.006em

**Observed:** Small dark logo on the left, a closely grouped set of muted links beside it and a utility link pushed to the far right. The inner row uses 48px side padding and a 24px navigation gap.

**States:** Declared: hover darkens link text to charcoal; focus-visible uses a 2px teal outline.

### Primary button

**Use:** Main conversion on a general landing page.

**CSS:** `background-color: #000000; background-image: linear-gradient(rgba(255, 255, 255, 0.05) 0%, rgba(0, 0, 0, 0.05) 100%); color: #ffffff; height: 44px; border: 1px solid rgba(0, 0, 0, 0.03); border-radius: 10px; box-shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — inter 500 · 15px/1.1 · tracking -0.009em

**Observed:** Text is followed by a tiny northeast arrow on a circular chip. Opening primary and secondary actions have equal visual width, 184px in the default pair.

**States:** Declared: hover background is black; focus-visible uses a 2px teal outline.

**Transfer:** Size to the label with approximately 26px horizontal content padding.

### Secondary button

**Use:** Documentation, details and lower-priority conversion.

**CSS:** `background: #ffffff; color: #2c2d30; height: 44px; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — inter 500 · 15px/1.1 · tracking -0.009em

**Observed:** A low-contrast arrow chip follows the label. The compact variant is 36px high, uses action-small typography and ranges from 88px-wide short labels to wider descriptive labels.

**States:** Declared: hover retains white and strengthens the shadow-edge to rgba(0,0,0,0.1); focus-visible uses a 2px teal outline.

### Product showcase

**Use:** Lead product or ecosystem proof.

**CSS:** `width: 550px; height: 705px; background: #f4f1f6; border-radius: 40px; overflow: hidden; position: relative; display: flex; flex-direction: column; justify-content: flex-end`

**Text style:** `showcase-name` — inter 600 · 18px/1.1 · tracking 0.08em · uppercase

**Observed:** A tall device preview occupies most of the stage. The Frosted caption combines an 80px icon, uppercase name, tiny availability line and acquisition action.

**Transfer:** Replace the device with an equally legible upright product view when the product is not mobile.

### Discovery tile

**Use:** Browseable products or integrations.

**CSS:** `width: 286px; height: 289px; padding: 32px 12px; display: flex; flex-direction: column; align-items: center; gap: 16px; position: relative`

**Text style:** `item-title` — inter 500 · 18px/1.4 · tracking -0.015em

**Observed:** An 80px identity icon sits above a centered title and muted description, then a compact Secondary button. Pale multi-color washes provide the backing; white gutters and faint dashed perimeter lines structure the rail.

**Transfer:** Use the same composition for integrations, templates or use cases, preserving comparable description lengths.

### Carousel control

**Use:** Previous and next discovery items.

**CSS:** `width: 36px; height: 36px; background: rgba(255, 255, 255, 0.88); border: 1px solid rgba(44, 45, 48, 0.08); border-radius: 9999px; box-shadow: rgba(44, 45, 48, 0.08) 0px 8px 24px 0px; display: flex; align-items: center; justify-content: center`

**Observed:** A simple 16px chevron floats at each side of the rail, vertically centered.

**States:** Declared: hover background becomes white and border becomes rgba(44,45,48,0.14); focus-visible uses a 2px rgba(44,45,48,0.3) outline with 3px offset; active uses translateY(-50%) scale(0.97).

### Affiliation badge

**Use:** A small relationship or endorsement signal between chapters.

**CSS:** `background: rgba(44, 45, 48, 0.03); border-radius: 9999px; padding: 4px 16px; display: flex; align-items: center; gap: 8px`

**Text style:** `footer-link` — inter 400 · 14px/1.4 · tracking -0.006em

**Observed:** Muted introductory words, a small partner icon and a blue partner name form a single compact line, 28px high.

**Transfer:** Use for a genuine affiliation; keep it visually subordinate to the main proof.

### Stat item

**Use:** Compact quantitative or reach proof.

**CSS:** `padding: 32px 0px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 16px`

**Text style:** `stat` — saans 500 · 21px/1.4

**Observed:** An outlined organic badge with a muted line icon sits above the value; a body-lg label follows with a 4px gap. Three equal items share an 800px row.

**Transfer:** A short nonnumeric reach statement can occupy one item without changing scale.

### Footer links

**Use:** Low-pressure navigation at the end of the page.

**CSS:** `display: flex; flex-wrap: wrap; row-gap: 48px; column-gap: 104px`

**Text style:** `footer-link` — inter 400 · 14px/1.4 · tracking -0.006em

**Observed:** Three compact columns pair dark medium headings with muted links separated by 16px. A small logo anchors the left, while copyright and social glyphs sit along a lower row over the organic outline pattern.

**States:** Declared: hover darkens links to charcoal; focus-visible uses a 2px teal outline.

### Capability card

**Only for:** technical capability pages

**Use:** Concise performance or reliability proof.

**CSS:** `background: rgba(44, 45, 48, 0.02); border-radius: 16px; padding: 24px 24px 24px 152px; height: 148px; position: relative; overflow: hidden; display: flex; align-items: center`

**Text style:** `item-title` — inter 500 · 18px/1.4 · tracking -0.015em

**Observed:** A large pale illustration fills the left side, sometimes beyond the card boundary; short dark title and muted statement occupy the remaining width.

**Transfer:** Give each card one operational benefit with a concrete supporting sentence.

### Builder button

**Only for:** developer landing pages

**Use:** Technical onboarding conversion.

**CSS:** `background-color: #00b94a; background-image: linear-gradient(rgba(255, 255, 255, 0) 0%, rgba(0, 0, 0, 0.05) 100%); color: #ffffff; height: 44px; border: 1px solid rgba(0, 0, 0, 0.03); border-radius: 10px; box-shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`

**Text style:** `action` — inter 500 · 15px/1.1 · tracking -0.009em

**Observed:** The green counterpart of Primary button, paired with white documentation access; 168px wide for its short label.

**States:** Declared: hover background is rgb(0,163,58); focus-visible uses a 2px teal outline.

## Imagery and graphics

### Contour atmosphere

**Use:** Signature background behind the opening and selected explanatory stages.

**Observed:** Thin, widely spaced curved diagonals in barely visible lavender, green and gray sweep upward across white. The field fades toward the edges and never reduces headline contrast. Dashed pale framing lines suggest a diagram's construction guides.

**Transfer:** Recreate the light contour field around an original product emblem. Preserve its near-white intensity instead of substituting a saturated mesh gradient.

**Build:** Use an SVG viewBox of 1082 by 460 with 12–18 open cubic Bezier paths sweeping from below the lower-left edge toward the upper right. Separate paths by roughly 40px, set fill to none, stroke width to 0.7px and alternate rgba(170,135,180,0.14), rgba(130,175,150,0.12) and rgba(44,45,48,0.08). Mask the field with a white-to-transparent edge fade. Add 1px dashed construction edges using rgba(44,45,48,0.08).

### Friendly identity object

**Use:** Central opening object and recurring small badges.

**Observed:** A dark, flat, three-lobed organic mascot with a white face sits above the headline. Elsewhere circles, softened diamonds, rounded squares and four-lobed shapes enclose delicate line icons.

**Transfer:** Create an original soft geometric mark with one friendly detail, keeping a dark silhouette on white; a three-part arrangement of rounded shapes is a sufficient fallback.

**Build:** Combine overlapping circles or rounded SVG lobes into an approximately 150×100px silhouette filled with charcoal. Use only a few small white strokes or cutouts for character. For secondary badges, use a 64–80px white organic outline enclosure with a 1px rgba(44,45,48,0.1) edge and a muted line icon.

### Vivid device showcases

**Use:** Large paired product-proof stages.

**Observed:** Black-framed upright phones stand against pink pixel-texture and blue-lavender atmospheric backdrops. Their interfaces are crisp and saturated, unlike the pale supporting art. Rounded corners frame the whole scene; the phone is narrower than the stage and rises close to its top.

**Transfer:** Show a real, tightly composed product interaction inside a plausible device or screen frame. Back it with a softly textured color environment rather than lifestyle photography. A polished static interface view with subtle grain is the minimum acceptable substitute.

### Pastel discovery fields

**Use:** Behind discovery tiles and ecosystem summaries.

**Observed:** Very light overlapping mint, cream and lavender washes back bold individual app marks. Identity marks provide the saturation; the field has almost no visual weight.

**Transfer:** Use original integration or category symbols with pale backing, leaving text fully readable.

**Build:** Layer three radial gradients over white: mint rgba(135,238,173,0.16) near one corner, lavender rgba(166,166,216,0.14) near the opposite corner and warm cream rgba(242,208,166,0.12) around the center. Use broad 60–80% radii and retain white gutters.

### Organic network footer

**Use:** Signature full-width ending artwork.

**Observed:** Oversized, barely visible outlines of circles, lobed forms and rounded squares wander behind the footer, connected by faint dashed looping paths and small dots. They extend off every edge while the logo and links remain clear.

**Transfer:** Always carry this soft network drawing into the ending. Use original shapes suited to the product; it can be built entirely in SVG without specialized artwork.

**Build:** Make a full-width SVG approximately 314px high. Scatter 90–160px organic outlines rotated in different directions, use no fill and 1px rgba(44,45,48,0.06) strokes. Connect a subset with long dashed Bezier curves in the same faint tone, with 4–5px endpoint dots. Clip shapes at the bounds and keep all drawing behind the content.

### Diagram and tooling art

**Only for:** technical capability pages

**Use:** Explain modular relationships and developer workflows.

**Observed:** A dashed circular orbit links white organic icon badges around a central symbol; small labels sit beneath each node. Tooling cards use pale interface miniatures and a pastel sheet of small glyphs, not dense readable application screens.

**Transfer:** Map the new product's relationships into a simple orbit or a small authentic interface illustration. Keep strokes muted, backings white and emphasis on structural relationships.

**Build:** Draw a dashed ellipse in rgba(44,45,48,0.1), place six soft badge shapes around it and one in the center, and connect only where the model requires. Use 1.5px round line icons with restrained muted green/lavender accents.

### Mint promotion rings

**Only for:** related-product closing promotions

**Use:** Centered closing product callout.

**Observed:** Large pale concentric disks surround a 72px white circular logo badge. The larger disk extends beyond the visible stage; text and a small white action remain centered in front.

**Transfer:** Use a single related offering's own symbol, with the same spacious ring treatment.

**Build:** Position two absolute circular layers of 394px and 728px behind the logo, with rgba(40,211,88,0.12) backgrounds. Use reduced opacities around 0.56 and 0.36 and clip the overall stage. Keep circles hard-edged but faint rather than turning them into neon blur.

### Icons

**Observed:** Small action arrows use rounded 1.5px strokes; compact arrow chips are about 23px, while carousel chevrons are 16px. Standalone explanatory icons use soft rounded strokes and muted colors within irregular white badges.

**Transfer:** Choose simple 1.5px round-stroke symbols; use northeast arrows for outbound actions and chevrons for browsing. Avoid heavy solid icon sets for the explanatory diagrams.

## Section recipes

How recurring sections are built.

### First screen: Emblem and contour opening

**Observed:** A fixed 80px white Fixed navigation precedes a centered 1082×460px stage, beginning 128px into the page. Back to front: White field, Contour atmosphere, dark Friendly identity object, headline, support and paired actions. The emblem occupies approximately 150×100px and sits 36px above the text group. The short 46px headline spans roughly one third of the stage; the muted 20px support follows at 16px. Actions follow after 24px, with Secondary button left and Primary button right, separated by 16px. The stage has 56px top and 100px bottom padding. Within the first 900px, the complete emblem, headline, support and actions are visible, followed by the upper portion of the two vivid Product showcases starting around 618px; their captions fall below the fold.

**Transfer:** Lead with an original soft emblem and the contour field even without custom animation. Show the most legible product proof beginning below the opening instead of enlarging the headline to fill the viewport. Developer-oriented openings retain the same structure but use Builder button and a compact capability overview below.

**Avoid:** Do not replace the emblem with a giant dashboard, stretch the headline across the full page or place a dense wall of copy above the actions.

**Text style:** `display` — saans 600 · 46px/1.2

### Two-tone heading pair

**Observed:** A short dark 28px proposition is paired with a muted same-size explanatory sentence, often only 0–4px away. General exploration and growth chapters are centered; technical benefit chapters can align to the content's left edge. A 48–64px section inset gives the pair room.

**Transfer:** Write a short promise plus one explanatory continuation. Use the heading-support variant only for the centered exploration introduction.

**Text style:** `heading` — saans 500 · 28px/1.35

### Paired vivid proof

**Observed:** Two Product showcases share a 24px gutter and extend slightly wider than the standard content stage. Product media dominates each card, with compact Frosted caption metadata below.

**Transfer:** Compare two offerings or two meaningful product experiences. Let the card's tall media ratio carry visual richness, not extra paragraphs.

### Discovery chapter

**Observed:** A centered Two-tone heading pair precedes the Discovery tile rail by 48px. Three whole pastel-backed tiles and partial neighbors are visible within the 986px opening, with Carousel controls floating at the sides. A small Affiliation badge has its own generous white interval below.

**Transfer:** Offer a browseable collection of integrations, tools or applications. Preserve the identity-icon, brief description and compact-action hierarchy.

### Human-scale proof ending

**Observed:** Centered heading and same-size muted supporting statement sit above the 800px Stat item row with 48px group separation. Three equal items use badges rather than colored boxes; 21px values remain smaller than section headings. A faint dashed divider and generous white gap lead to the footer.

**Transfer:** Close the argument with a few relevant proof points or reach indicators, keeping their size restrained rather than escalating into giant numbers.

**Text style:** `stat` — saans 500 · 21px/1.4

### Patterned navigation ending

**Observed:** A 314px white footer uses 56px top and 48px bottom padding. Organic network footer art fills the width. A small logo is aligned left of three Footer links columns; copyright and small social glyphs form the lower row. The same composition closes both consumer and developer narratives.

**Transfer:** Finish with the original product's small identity, sparse useful navigation and the soft network pattern. Keep the drawing quieter than every link.

### Technical capability chapters

**Only for:** technical capability pages

**Observed:** Two-tone heading pairs introduce 2×2 Capability cards, a split explanatory diagram stage, three unboxed onboarding benefits, two large tooling cards and a two-column list of icon-led functions. Tooling cards are about 473×378px; the function list has 40px between columns and 138px-tall entries. Dark inline titles run directly into muted explanatory text.

**Transfer:** Select the formats needed to explain the product: operational proof, relationship diagram, workflow reassurance or modular features. Preserve the pale line-drawing system rather than treating every chapter as another vivid showcase.

**Text style:** `heading` — saans 500 · 28px/1.35

### Related-product halo close

**Only for:** related-product closing promotions

**Observed:** A 421px-high Halo stage centers a 72px logo badge, a 28px title, 26px muted descriptor and compact Secondary button with a 16px gap. Mint promotion rings sit behind the stack, clipped by a dashed guide frame. White space separates this promotion from the footer.

**Transfer:** Use as a related-offering handoff at the end of a technical story, not as the default general-page ending.

**Text style:** `promotion-support` — saans 500 · 26px/1.35 · tracking 0.015em

## Page flow

**Storyline:** Compact promise → visible product or ecosystem proof → explanatory benefits → reassurance or reach → light patterned navigation ending.

### General ecosystem or product landing page

1. **Promise** — Centered emblem, contour field, short headline and paired conversion/documentation actions.
2. **Product proof** — Two large vivid device showcases with compact frosted metadata.
3. **Discovery** — Centered heading pair, pastel browsing rail and small affiliation signal.
4. **Quantified proof** — Centered growth statement with three modest icon-led statistics.
5. **Navigation ending** — White organic-pattern footer with sparse columns and social links.

**Transfer:** Use the vivid proof emphasis as the default for a new marketing page, selecting proof and discovery content appropriate to its audience.

### Developer platform or technical product landing page

1. **Promise** — Same centered emblem opening with a green technical conversion action.
2. **Capability overview** — Three pale diagrammatic entry points followed by a compact operational-benefit card grid.
3. **Product explanation** — Split text-and-orbit illustration stage.
4. **Objection handling** — Three unboxed usability benefits and paired tooling cards.
5. **Capability detail** — Two-column icon-led modular feature list.
6. **Closing call** — Pale mint concentric-ring related-product promotion.
7. **Navigation ending** — The shared white organic-pattern footer.

**Transfer:** Favor pale technical drawings and concrete workflow benefits over saturated device media; use the halo promotion when a related offering provides a useful next step.

## Writing

Friendly, concise and assured. Technical subjects are presented through immediate benefits and approachable nouns rather than an austere engineering manifesto.

**Do not copy:** Do not reuse Lens names, mascot artwork, product identities, partner marks, claims, download counts, adoption statistics or quoted promises as the new product's own assets or facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for benefits, we for enabling help and the product name for concrete capabilities.
- **Rhythm:** Headlines are generally two to six words. Follow them with a single short sentence or fragment; card titles often end with a period and run directly into supporting text.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A short category promise or a direct build-with proposition. | 3–5 words | “New Social Layer”<br>“Build SocialFi with [Brand]” |
| Supporting line | Name the audience or experience in one calm sentence. | 6–10 words | “For onchain culture and communities”<br>“The full-stack platform for social and financial experiences.” |
| Section heading pair | Brief dark promise followed by a same-scale explanation. | 3–13 words across the pair | “Focus on your product. We make it easy.”<br>“Your users will love it. It's never been easier to bring users onchain.” |
| Feature title and support | A concrete benefit label, then one factual explanation. | 2–4 word title plus a short sentence | “Simple onboarding. Users can join with an email address or phone number.” |
| Primary action | Direct verb plus object; retain specific destination names for technical links. | 1–3 words | “Create Account”<br>“Start Building”<br>“Developer Docs” |

**Words and phrasing to use:** build; grow; explore; your product; your users; simple; flexible; portable; get started

**Avoid:** revolutionary paradigm; unprecedented synergy; unlock infinite potential; world-changing magic; aggressive scarcity language

**Rules:**

- Tie technical nouns to user or builder outcomes immediately.
- Keep card descriptions to one compact idea, usually one or two lines.
- Use destination-specific actions when possible; reserve Learn More for an explanatory next step.
- Prefer periods to exclamation marks and benefit statements to promotional questions.

## Do's and Don'ts

### Do

- Keep the primary headline at 46px/1.2 and the ordinary section scale at 28px/1.35.
- Pair dark propositions with 60%-opacity charcoal continuations at the same scale.
- Keep ordinary content within the 1082px stage with 48px inner side padding.
- Use 44px opening actions and 36px compact actions; preserve their distinct 10px and 8px corners.
- Concentrate vivid imagery in the 40px-radius showcase pair while keeping diagram art almost white.
- Build proof with 21px figures, organic outline badges and three balanced columns.
- Carry the faint contour lines and organic footer network through every new landing page.
- Use 11px tracked uppercase only for the small showcase proof line.

### Don't

- Do not turn the entire site dark to match the black primary button.
- Do not apply the developer green to every link, headline or card background.
- Do not make 21px stat values larger than the 28px section headings.
- Do not turn every 8px-radius secondary button into a full pill; pills belong to badges and circular controls.
- Do not replace outline-like button shadows with broad elevated card shadows.
- Do not use uppercase, widely tracked navigation in place of the 14px mixed-case labels.
- Do not put dense application UI text into the pale explanatory diagrams; their job is structural illustration.
- Do not give the footer pattern enough contrast to compete with the muted 14px links.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.17s transitions; navigation links use color 0.1s ease-in-out and footer links use color 0.15s.
- Carousel controls declare background, border-color and transform transitions of 0.17s; active scale is 0.97.
- Two promotional halo layers declare a 28s ease-out infinite animation; one has a -14s delay.

**Transfer:**

- Keep interaction changes subtle: stronger hairline edges, darker link text and minimal control compression.
- For a related-product halo, retain the slow layered breathing character rather than adding fast pulsing or dramatic glow.

**Unknown:**

- The full halo keyframe trajectory and all scroll-driven choreography are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 432px, 512px, 640px, 768px, 769px, 820px, 821px, 900px, 1024px, 1055px and 1178px.
- The capability grid declares repeat(auto-fill, minmax(350px, 1fr)); navigation and footer groups use wrapping where specified.

**Transfer:**

- On narrow widths, preserve the centered emblem–headline–support hierarchy; let the short headline wrap before shrinking it into navigation-scale text.
- Stack the vivid showcase pair and technical split stages while retaining their media emphasis. Keep the discovery collection horizontally browseable.
- Reduce outer insets before allowing the pale contour stage to crowd the text; keep footer shapes clipped behind wrapped navigation.

**Unknown:**

- Exact narrow-screen typography, navigation collapse and spacing changes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
