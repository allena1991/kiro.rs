# Figma — expressive tools on display

## Overview

A white, editorial product stage where restrained grotesk typography makes room for exuberant visual work. Black actions and fine rules organize richly colored interface compositions, grainy pastel fields and playful graphic details. It suits creative software and collaborative products that can demonstrate what people make, with spacious storytelling above a more densely indexed feature catalog.

### Essentials

- Headlines behave like paired editorial statements rather than advertising billboards: 44px/1.1 regular type introduces the product, with its promise in muted gray at the same size; capability pairs step down to 30px/1.2 with -0.7px tracking.
- The opening is a wide workbench: 40px side margins, text and two 84px-high actions above a 1360×730px product stage, separated by 40px. The media, not an oversized slogan, dominates the first screen.
- Actions have deliberately unequal silhouettes: black primary at 16px radius beside a hairline outlined secondary pill; compact actions use 8px radius and 46px height, not universal pills.
- Color belongs to the work: the default page stays white through its narrative and feature catalog, while large rectangular media fields carry intense artwork and textured pastels. Black becomes a full-width closing footer; pastel full-section bands are a separate explanatory-page variant.
- Include a tactile demonstration field: softly mottled pink/lilac grain or mint halftone surrounds crisp enlarged interface fragments. Without finished media, stage one credible workflow or output on the same textured field rather than substituting an abstract glow.
- Proof is an editorial spread: a 44px quote and an 88px/1 statistic are separated by vertical 1px rules, with 16px attribution and a 14px qualification; a blue radial portrait detail and monochrome logo strip give the spread a playful edge.
- Include a monumental conversion bar: a centered 44px closing thought sits above a nearly container-wide black action, 136px high, 24px radius, with a 56px/1 regular label. This is a signature device, not an ordinary small footer button.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Radial blue | `#00b6ff` | `--color-blue-detail` | accent | Small radial portrait ornament in proof spreads. |
| Pale cyan | `#c7f8fb` | `--color-cyan-label` | surface, background | New-feature badges; also a full-width registration band in the campaign variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action, border | Headings, actions, rules and the dark directory footer. |
| Secondary gray | `#757575` | `--color-muted` | text | Visible black at 54% over white; same-size supporting headlines and feature descriptions. |
| Reversed secondary gray | `#999999` | `--color-footer-muted` | text | White at 60% on black for directory labels. |
| Hairline gray | `#d6d6d6` | `--color-rule` | border | Visible black at 16% over white; fine row dividers and inset button outlines. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, unboxed content and reversed action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| event campaigns | Campaign green | `#24cb71` | `--color-campaign-green` | background | Solid agenda/details field paired with black text. |
| explanatory product pages | Cream band | `#fff2df` | `--color-cream-band` | background | Template explorer and integration chapters. |
| explanatory product pages | Lavender band | `#ede1fe` | `--color-lavender-band` | background | Full-width explanatory capability chapters. |
| pricing pages | Pale lime band | `#f3ffe3` | `--color-lime-band` | background | Long FAQ chapter and closing trust strip. |
| explanatory product pages | Ice blue band | `#e9faff` | `--color-ice-band` | background | Feature chapters with white interface images. |
| pricing pages | Soft comparison gray | `#ebebeb` | `--color-soft-rule` | border, surface | Visible black at 8% over white; comparison dividers and segmented-control tracks. |
| pricing pages | Soft control gray | `#f5f5f5` | `--color-soft-fill` | surface | Visible black at 4% over white; pale control and product-index fill. |

## Typography

- **figmaSans** — Marketing headings, descriptions, navigation and actions. Open, plainspoken grotesk; regular display weight and unusually light variable body weights. OpenType features: "kern". If unavailable, use **Inter**. Use variable weights 320–520 and retain the negative tracking. Font stack: "figmaSans", "Inter", "SF Pro Display", system-ui, helvetica, sans-serif.
- **figmaMono** — Uppercase directory labels, eyebrows and release badges. Matter-of-fact technical markings that contrast with expressive visual work. OpenType features: "kern". If unavailable, use **IBM Plex Mono**. Font stack: "figmaMono", "IBM Plex Mono", "SF Mono", menlo, monospace.
- **Figma-Sans-Display** (only for event campaigns) — Campaign display headings, schedule titles and times. Regular grotesk with compact large-scale setting. If unavailable, use **Inter**. Font stack: "Figma-Sans-Display", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | figmaSans | 400 | 88px | 1 | -0.0142em | A single large proof number beside a quotation. |
| heading-lg | figmaSans | 400 | 44px | 1.1 | -0.015em | Default product identity, promise, proof quotation and closing thought. |
| heading | figmaSans | 400 | 30px | 1.2 | -0.022em | Capability heading/support pairs, feature-index names and large hero action labels. |
| body | figmaSans | 400 | 16px | 1.4 | normal | Default feature descriptions, captions and compact action labels. |
| navigation | figmaSans | 400 | 16px | 1.45 | normal | Header links. |
| eyebrow | figmaMono | 400 | 16px | 1.3 | 0.03em, uppercase | Directory headings and contextual category markers. |
| footer-link | figmaSans | 320 | 16px | 1.45 | -0.0075em | Dense directory links in either footer theme. |
| caption | figmaSans | 400 | 14px | 1.45 | normal | Qualification beneath proof statistics. |
| badge | figmaMono | 400 | 14px | 1.3 | 0.036em, uppercase | New-feature marking beside catalog titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | figmaSans | 400 | 86px | 0.95 | -0.02em | Two-line choice-oriented pricing headline. |
| event campaigns | campaign-display | Figma-Sans-Display | 400 | 86px | 0.9 | -0.02em | White headline on black campaign hero. |
| explanatory product pages | explanatory-display | figmaSans | 400 | 72px | 1 | -0.02em | Benefit-led split hero. |
| full-width conversion bars and portfolio-style openings | closing-action | figmaSans | 400 | 56px | 1 | -0.0223em | Monumental conversion bar label; also the portfolio-style opening headline. |
| explanatory product and pricing pages | chapter-heading | figmaSans | 400 | 56px | 1.1 | -0.015em | Large pastel chapter headings and FAQ titles. |
| event campaigns | campaign-heading | Figma-Sans-Display | 400 | 56px | 1.1 | -0.02em | Schedule titles and campaign section leads. |
| explanatory product and pricing pages | question | figmaSans | 400 | 32px | 1.3 | -0.01em | FAQ questions, benefit-card headings and plan titles. |
| event campaigns | campaign-time | Figma-Sans-Display | 400 | 32px | 1.4 | normal | Time column opposite schedule titles. |
| tabbed product demonstrations | demo-tab | figmaSans | 400 | 24px | 1.3 | normal | Centered text-only product demonstration tabs. |
| explanatory product and pricing pages | chapter-support | figmaSans | 340 | 24px | 1.35 | -0.005em | Lead paragraph below a large chapter title. |
| pricing pages | addon-heading | figmaSans | 520 | 24px | 1.35 | -0.01em | Paid add-on card title. |
| explanatory product and pricing pages | prose | figmaSans | 330 | 18px | 1.4 | normal | Long explanations and FAQ answers. |

**Notes:**

- Regular weight carries nearly all display hierarchy; do not introduce heavy display cuts to compensate for smaller headlines.
- The product identity and gray promise share one recipe, as do the black capability lead and its gray explanation. Color, not size or weight, separates the pair.
- Tracking tightens from normal at 16px to -0.015em at 44px; 30px headings use the distinct -0.022em setting. Preserve the individual recipes rather than interpolating one universal tracking value.

## Layout

**Density:** Airy narrative chapters around large media; compact descriptions and tightly indexed rows keep long pages useful.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small header action gaps and badge horizontal padding. |
| 12px | Hero action gap and compact action vertical padding. |
| 16px | Main grid gutter, image-to-caption interval and directory heading-to-links gap. |
| 24px | Feature-row vertical padding and add-on card padding. |
| 32px | Hero action top separation and demonstration tab top padding. |
| 40px | Default page side inset, heading-to-media gap and proof inner indent. |
| 56px | Closing thought-to-conversion-bar gap. |
| 60px | Explanatory-page side inset and two-column media gap. |
| 64px | Proof section internal vertical separation. |
| 80px | Default chapter top/bottom padding. |
| 120px | Footer and explanatory chapter top/bottom padding. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 40px. White landing-page canvas with 1360px usable width at desktop.
- **heading-measure**: max width 901px. Capability pairs span about two thirds of the main container; some chapters indent this block toward the center.
- **feature-grid**: 3 columns · gap 16px. Equal media-led columns, about 443px each; or a two-thirds demonstration beside a one-third still.
- **catalog-grid**: 4 columns · gap 16px. Four visual quarters: name, optional 328px media, description, right-aligned links. The last two quarters can share one content wrapper.
- **proof-grid**: 2 columns · gap 16px. 1016px quote plus 328px statistic, with separate left rules.
- **explanatory-container** (only for explanatory product, pricing and event pages): max width 1440px · side padding 60px. 1320px usable desktop width, with 480px introduction and 720px detail columns.
- **pastel-feature-grid** (only for explanatory product pages): 2 columns · gap 60px. 540px images and text beneath, with 80px row gaps.
- **plans-grid** (only for pricing pages): 4 columns · gap 0px. Four 330px plan columns divided by left hairlines, with aligned price rows and actions.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | compact-actions | 8px |
|  | hero-primary | 16px |
|  | hero-secondary | 9999px (pill) |
|  | closing-bar | 24px |
|  | release-badge | 4px |
|  | media-controls | 50% |
| pricing pages | addon-panel | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| header-edge | `0px 1px 0px 0px rgba(0,0,0,0.16)` | A dividing line under the fixed white header, not floating elevation. |
| outline-action | `inset 0px 0px 0px 1px rgba(0,0,0,0.16)` | Fine secondary action outline. |

### Surfaces

#### White workbench · level 0

**Use:** Default narrative and feature catalog canvas.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Content sits directly on the canvas; rectangular media carries its own color rather than being enclosed in rounded cards.

**Transfer:** Keep substantial white space between visual chapters.

#### Ruled index · level 0

**Use:** Long feature lists.

**CSS:** `background: #ffffff; border-top: 1px solid rgba(0,0,0,0.16)`

**Observed:** A repeated horizontal rule organizes varied image heights and text-only entries.

**Transfer:** Let the content determine row height while retaining common column alignment.

#### Dark directory · level 0

**Use:** Default page ending.

**CSS:** `background: #000000; color: #ffffff; border-top: 1px solid rgba(255,255,255,0.16); padding: 120px 0px`

**Observed:** Broad flat black field, light links, dim mono headings and no card elevation.

**Transfer:** Use a directory appropriate to the new product rather than a second sales panel.

#### Pastel chapter · level 0

**Only for:** explanatory product pages

**Use:** Long illustrated benefit chapters.

**CSS:** `background: #ede1fe; color: #000000; padding: 120px 0px`

**Observed:** Lavender, cream and ice blue are separate full-width chapter fields; white interface images sit on top.

**Transfer:** Choose one pale color for each sustained chapter, not one per paragraph.

#### Lime FAQ field · level 0

**Only for:** pricing pages

**Use:** Objection handling after comparison tables.

**CSS:** `background: #f3ffe3; padding: 120px 0px`

**Observed:** The soft field continues through the final monochrome trust strip before the black footer.

**Transfer:** Keep dense answers high-contrast and unboxed.

#### Add-on panel · level 1

**Only for:** pricing pages

**Use:** Secondary commercial options.

**CSS:** `border: 1px solid rgba(0,0,0,0.16); border-radius: 16px; padding: 24px; box-shadow: none`

**Observed:** Panels stack in the detail column opposite an open introduction.

**Transfer:** Reserve outlined cards for discrete purchasable extras.

#### Campaign green field · level 0

**Only for:** event campaigns

**Use:** Agenda and details.

**CSS:** `background: #24cb71; color: #000000; padding: 120px 60px`

**Observed:** Solid saturated color and black rules, without gradients or elevation.

**Transfer:** Give time-based campaign content a clear contrasting chapter.

## Components

### Navigation

**Use:** Persistent site orientation.

**CSS:** `height: 78px; position: fixed; top: 0px; z-index: 25; background: #ffffff; padding: 16px 40px; box-shadow: 0px 1px 0px 0px rgba(0,0,0,0.16); display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — figmaSans 400 · 16px/1.45

**Observed:** Small multicolor mark at left, dropdown labels with thin chevrons, then login and two compact conversion actions at right.

**States:** Declared: hover removes text decoration on navigation actions; focus-visible uses a 2px dashed black outline with 4px offset.

**Transfer:** Keep the mark small and the header practical rather than decorative.

### Primary button

**Use:** Main hero conversion.

**CSS:** `background: #000000; color: #ffffff; border-radius: 16px; padding: 24px 32px; height: 84px; display: flex; justify-content: center`

**Text style:** `heading` — figmaSans 400 · 30px/1.2 · tracking -0.022em

**Observed:** Large label centered inside a solid black rounded rectangle. The adjacent secondary has a different silhouette.

**States:** Declared: hover and active use black mixed with 15% transparency; focus-visible uses a 2px dashed black outline with 4px offset.

### Secondary button

**Use:** Secondary hero conversion.

**CSS:** `background: transparent; color: #000000; border-radius: 9999px; padding: 24px 32px; height: 84px; box-shadow: inset 0px 0px 0px 1px rgba(0,0,0,0.16)`

**Text style:** `heading` — figmaSans 400 · 30px/1.2 · tracking -0.022em

**Observed:** A restrained outlined pill, paired on the same baseline as Primary button.

**States:** Declared: hover and active strengthen the inset outline to black at 40%; focus-visible uses a 2px dashed black outline with 4px offset.

### Compact button

**Use:** Header and in-chapter conversion.

**CSS:** `background: #000000; color: #ffffff; border-radius: 8px; padding: 12px 22px; height: 46px`

**Text style:** `body` — figmaSans 400 · 16px/1.4

**Observed:** Text-width action rather than a fixed-width tile. Header secondary uses the same dimensions and corner treatment with an inset outline.

**States:** Declared: hover and active use black with 15% transparency; focus-visible uses a 2px dashed black outline with 4px offset.

### Arrow link

**Use:** Exploration, documentation and supporting conversion.

**CSS:** `color: #000000; display: inline-flex; position: relative; border-radius: 2px; text-decoration: underline; text-underline-offset: 2px`

**Text style:** `body` — figmaSans 400 · 16px/1.4

**Observed:** Underlined label followed by a small straight right arrow. Links sit below feature copy or at the far right of catalog rows.

**States:** Declared: hover removes text decoration; focus-visible uses a 2px dashed black outline with 4px offset.

### Feature index row

**Use:** Detailed capability catalog.

**CSS:** `display: grid; grid-template-columns: 328px 328px 672px; gap: 16px; padding: 24px 0px; border-top: 1px solid rgba(0,0,0,0.16)`

**Text style:** `heading` — figmaSans 400 · 30px/1.2 · tracking -0.022em

**Observed:** Name at left, optional media next, description in the next quarter and links at the far right. Entries without media preserve the shared alignment; images vary between square, portrait and landscape.

**Transfer:** Use this instead of a uniform bento grid for a broad inventory.

### Release badge

**Use:** Mark genuinely new capabilities.

**CSS:** `background: #c7f8fb; color: #000000; border-radius: 4px; padding: 6px 8px`

**Text style:** `badge` — figmaMono 400 · 14px/1.3 · tracking 0.036em · uppercase

**Observed:** Tiny uppercase mono label attached inline to a catalog heading, not a floating sticker.

### Closing bar

**Use:** Signature final conversion.

**CSS:** `background: #000000; color: #ffffff; border-radius: 24px; padding: 40px 80px; height: 136px; display: flex; justify-content: center; align-items: center`

**Text style:** `closing-action` — figmaSans 400 · 56px/1 · tracking -0.0223em

**Observed:** Spans the full inner width beneath a centered closing thought.

**States:** Declared: hover rounds corners to 80px and uses black with 15% transparency; focus-visible uses a 2px dashed black outline with 4px offset.

### Footer directory

**Use:** Default ending with deep navigation.

**CSS:** `background: #000000; color: #ffffff; padding: 120px 60px; display: grid; grid-template-columns: 390px repeat(4, 180px); column-gap: 60px`

**Text style:** `footer-link` — figmaSans 320 · 16px/1.45 · tracking -0.0075em

**Observed:** Brand and circular social actions occupy the broad first column; four narrower columns use uppercase mono labels and light links. A subordinate category can stack below the product column. Locale and privacy links finish the bottom edge. The explanatory product variant reverses to white with black links and gray labels.

**States:** Declared: hover underlines links at 1px; focus-visible uses a 2px dashed white outline with 4px offset in the dark theme.

### FAQ row

**Only for:** explanatory product and pricing pages

**Use:** Substantive objection handling.

**CSS:** `border-bottom: 1.5px solid #000000`

**Text style:** `question` — figmaSans 400 · 32px/1.3 · tracking -0.01em

**Observed:** Question with a thin up/down arrow at the right, prose beneath when expanded. Detail column is 720px wide; the section title sits separately in the left column.

**Transfer:** Answers can be multiple paragraphs; retain the open editorial layout.

### Add-on card

**Only for:** pricing pages

**Use:** Discrete secondary paid option.

**CSS:** `border: 1px solid rgba(0,0,0,0.16); border-radius: 16px; padding: 24px`

**Text style:** `addon-heading` — figmaSans 520 · 24px/1.35 · tracking -0.01em

**Observed:** Title then short gray explanation, with a right-aligned Arrow link below; stacked with 24px gaps.

### Demo tabs

**Only for:** tabbed product demonstrations

**Use:** Switch between product workflows beneath a large demonstration.

**CSS:** `display: flex; justify-content: center; column-gap: 43.2px; padding: 32px 0px 16px`

**Text style:** `demo-tab` — figmaSans 400 · 24px/1.3

**Observed:** Three text-only choices; active black versus muted gray siblings, with a short explanatory paragraph centered below.

**Transfer:** Use only for genuinely distinct demonstrations, not as general page navigation.

## Imagery and graphics

### Textured product stage

**Use:** Hero and major demonstration chapters; a required tactile visual device.

**Observed:** A sharp, enlarged interface sits in a wide rectangular pink/lilac field dusted with peach grain. The hero stage fills almost all the container width and continues below the first fold. UI panels, artwork, cursor and selection outlines are clearly legible; the media edge stays square.

**Transfer:** Compose a real task or output for the new product, with only enough interface chrome to explain the interaction. Minimum acceptable treatment is one believable output and one enlarged tool interaction on a tactile field.

**Build:** Make a 1360:730 SVG field with broad lilac and blush shapes, softly masked peach patches and an SVG feTurbulence noise layer at low opacity. Clip all layers to a rectangle; inset the main interface roughly one tenth of the field width. Use a crisp foreground and fine grain, not a blurred neon halo. Match the soft mottling; exact color stops are not essential.

### Mint halftone demonstration

**Use:** Secondary oversized product scene.

**Observed:** Mint-green grain backs a central white prompt panel; pale cyan dots and diamonds cluster around the perimeter, varying in size and fading toward the middle. A secondary warm-yellow product still occupies the adjacent third.

**Transfer:** Frame the new product's central interaction with a light dotted or diamond field; let the interaction remain the focal point.

**Build:** Create a muted mint rectangle, overlay low-opacity monochrome SVG noise, then distribute small pale-cyan circles and 45-degree squares on a regular grid. Scale shapes up near the edges and mask their opacity down toward the center. Place one white interaction card in the calm center; keep a 16px gap to the smaller neighboring media.

### Expressive capability tiles

**Use:** Three-column capability groups and portfolio-style media walls.

**Observed:** Square and portrait tiles mix vivid flat illustration, photographic outputs and UI overlays: vector handles, brushes, prompt cards and timeline strips. Cropping is assertive; no decorative browser frame or universal card border surrounds them.

**Transfer:** Show the effect of a tool with a close-up output plus one relevant control. Mix output types while preserving shared rectangular edges and 16px gutters.

### Editorial proof strip

**Use:** Trust spread between capability chapters.

**Observed:** A broad quotation sits beside a much narrower large percentage; both use thin left borders. A small grayscale portrait has a blue radial halo. A horizontal run of black customer logos follows.

**Transfer:** Use an attributable quote and a defensible statistic or benchmark; if there is no percentage, use a similarly compact verified number. Add a monochrome proof strip relevant to the product.

**Build:** For the portrait ornament, use a 76px circular repeating-conic-gradient with blue segments from 0deg to 18deg and transparent segments from 18deg to 30deg. Center the smaller circular portrait over it. Keep the ornament tiny relative to the quote.

### Resource carousel

**Only for:** portfolio and resource discovery pages

**Use:** Exploration after the main conversion chapter.

**Observed:** A horizontal track extends past the container edge, alternating 328px-square and 328×492px portrait images. Small underlined category captions sit below; previous/next circles and a fractional index sit above.

**Transfer:** Use real templates, outputs or examples with different aspect ratios rather than identical feature cards.

### Playful whiteboard collage

**Only for:** explanatory product pages

**Use:** Split opening, capability illustrations and signup closing.

**Observed:** Black outline doodles over lavender and orange blocks; white board views contain sticky notes, handwritten headings, cursors, reactions and occasional cutout photos. The closing form is flanked by two enormous hand-drawn black curved arrows.

**Transfer:** Use informal marks related to the product's activity, not stock people illustrations. Keep board images white against the full-section pastel.

**Build:** Draw loose SVG loops and curved arrows with black strokes and no fill, uneven but clean joins. For a hero collage, overlap a few square pastel blocks with outlined symbols and one small checkerboard patch. For the closing, use two isolated looping arrow paths pointing inward around a narrow centered form.

### Campaign modular geometry

**Only for:** event campaigns

**Use:** Hero-bottom artwork and the ribbon immediately before the campaign footer.

**Observed:** A black ground carries tightly fitted circles, quarter-circles, rectangles, letterlike angular cuts and dot matrices in lilac, violet and pale cyan. The lower ribbon is 300px tall and spans edge to edge.

**Transfer:** Create a modular visual alphabet for the campaign; keep hard vector edges and deliberate clipping rather than applying a generic gradient.

**Build:** Use an SVG grid of rectangular cells on black. Fill cells with circles, quarter-circle cuts, angular glyphlike paths and repeated dot arrays in lilac, violet and pale cyan. Vary module widths, align shared edges, and clip the first and last cells at the viewport.

### Campaign portraits

**Only for:** event campaigns

**Use:** Four-column participant directory.

**Observed:** Black-and-white cutout head-and-shoulder portraits on solid saturated green, violet, lilac, cyan, yellow or orange fields. Images are 308×231px with plain name and role text below.

**Transfer:** Normalize portrait crop and grayscale treatment; vary flat backgrounds while keeping identical image proportions.

### Icons

**Observed:** Small monochrome utility arrows and chevrons, generally 18–24px with 1.3px strokes and butt caps. Product marks add color; play/pause controls sit in 36px circular black buttons. Footer social icons are reversed in pale translucent circles.

**Transfer:** Use simple thin-stroke utility icons, straight arrows on exploration links and small colored product marks only where they identify a tool. Keep illustration-scale doodles separate from navigation icons.

## Section recipes

How recurring sections are built.

### First screen: Wide product workbench opening

**Observed:** A fixed 78px Navigation sits over White workbench. After 80px of breathing room, the left block uses heading-lg for product name with a small colored mark, then a gray two-line promise at exactly the same scale. The block occupies about two fifths of the width; Primary button and Secondary button align to its lower edge on the right with 12px between them. A 40px interval leads to the 1360×730px Textured product stage. In the first 900px, the identity, complete promise, both actions and most of the dominant interface scene are visible; the scene's bottom, Demo tabs and explanatory paragraph fall below the fold. Layers are white canvas, grainy pastel field, enlarged interface/output, then cursor and selection details.

**Transfer:** Use the new product's name and a short two-part promise, then build a convincing task scene on a textured field. Do not needlessly enlarge the headline when the media is simpler. A portfolio opening instead centers a layered output collage between a 56px left headline and right action; an explanatory opening uses a 72px left benefit headline and 480px illustration; pricing opens with an 86px choice headline; event campaigns use a black 86px headline stage and a wide outlined registration action.

**Avoid:** Do not turn this into a centered giant slogan above a tiny dashboard, a dark gradient SaaS hero, or a rounded browser-window mockup floating in empty space.

**Text style:** `heading-lg` — figmaSans 400 · 44px/1.1 · tracking -0.015em

### Paired capability lead

**Observed:** 80px chapter padding; heading and support share heading, black then muted gray on consecutive lines within the 901.3px heading measure. Media starts 40px below. Some headings sit at the container edge, others are indented into the composition.

**Transfer:** Write a direct benefit followed by a practical explanation; keep their equal scale so the transition feels like one thought.

**Text style:** `heading` — figmaSans 400 · 30px/1.2 · tracking -0.022em

### Asymmetric demonstration spread

**Observed:** A two-thirds moving demonstration beside a one-third still, or three equal media columns with 16px gutters. Caption blocks use body, black title, gray explanation and Arrow link 16px below. Images lead; copy stays small.

**Transfer:** Give the most consequential workflow the widest area; secondary examples should explain adjacent capabilities rather than repeat it.

### Proof interlude

**Observed:** Proof-grid pairs a heading-lg quotation and stat number, both with left rules and 40px internal indents. Attribution uses body, qualification uses caption; 64px internal separation leads to the monochrome logo strip and small pause control.

**Transfer:** Interrupt a long demonstration story with human experience and one clearly qualified measure.

### Ruled capability catalog

**Observed:** A heading-lg introduction sits 80px above Feature index rows. Titles use heading, descriptions body in gray, Arrow links align right. Optional media preserves square, portrait or landscape proportions. Release badge appears inline on selected titles.

**Transfer:** Let a long inventory become an editorial index; preserve alignment across both illustrated and text-only rows.

### Monumental closing conversion

**Observed:** An 80px-padded white section centers a heading-lg thought. After 56px, Closing bar spans the full inner container. The next major field is Dark directory.

**Transfer:** End the argument with a short aspirational line and a single decisive action. Keep the bar as a strong graphic anchor.

**Text style:** `closing-action` — figmaSans 400 · 56px/1 · tracking -0.0223em

### Pastel explanatory chapter

**Only for:** explanatory product pages

**Observed:** Pastel chapter uses 120px vertical padding and 60px side insets. chapter-heading and chapter-support introduce a 780px text measure; 80px below, two 540px image-led columns use 60px gutters and 80px row gaps. Cream template explorers instead place a 390px ruled selection list beside an 840×560px board preview.

**Transfer:** Use sustained color to organize an educational story, with the demonstrated output much larger than accompanying prose.

### Commercial comparison

**Only for:** pricing pages

**Observed:** pricing-display spans two lines above a pale rounded product index. Four plan columns use left hairlines rather than raised cards; aligned price rows lead to compact full-width actions. Free entry uses an outline action, paid tiers black actions. Add-on panels follow, then a ruled comparison table with centered check/dash status columns and text-based qualifiers.

**Transfer:** Make plan differences scannable with alignment and rules, not oversized price numerals or a highlighted floating recommendation card.

### Split FAQ and alternative signup ending

**Only for:** explanatory product and pricing pages

**Observed:** A 480px left title column faces a 720px answer column of FAQ rows. Pricing retains the Lime FAQ field through a final logo strip and enters Dark directory directly. The explanatory product returns to white, then ends with a centered narrow signup form surrounded by looping hand-drawn arrows, followed by a light footer directory.

**Transfer:** Let longer answers expand naturally. Use the illustrated signup ending for low-friction account creation, not for every commercial page.

### Campaign schedule and closing ribbon

**Only for:** event campaigns

**Observed:** Black opening and a 98px sticky dark header lead into a pale-cyan registration band and Campaign green field. Ruled schedule rows place 32px times left and 56px titles right. A white four-column portrait directory and compact FAQ follow. The 300px Campaign modular geometry ribbon leads to a 635px black footer with a large white wordmark near the upper left and small copyright at lower right.

**Transfer:** Use this stronger chromatic theme for a finite program or launch, preserving the schedule's typographic scale and the hard-edged geometric ending.

## Page flow

**Storyline:** promise → convincing product scene → capability chapters → human and quantified proof → deeper inventory or comparison → decisive conversion or objection handling → directory ending

### Flagship product landing page

1. **promise** — Equal-scale identity and gray promise with paired actions over a textured interface stage.
2. **capability chapters** — Expressive creation, practical workflow and system-level benefits in differently proportioned media spreads.
3. **social proof** — Quote, large statistic and logo strip interrupt the demonstrations.
4. **depth** — A long ruled feature index explains specific capabilities.
5. **closing call** — Centered thought and full-width black conversion bar lead into a black directory footer.

**Transfer:** Default for a new marketing page: prioritize demonstrated outcomes and let detailed capabilities become an index.

### Broad creative platform overview

1. **promise** — Narrow left headline, central layered output collage and right conversion action.
2. **product demonstration** — Large workflow scenes followed by a four-column wall of expressive technical examples.
3. **social proof** — Quote/stat spread with monochrome logo track.
4. **closing call** — Monumental conversion bar.
5. **discovery** — Mixed-aspect resource carousel before the black directory footer.

**Transfer:** Use the collage and resource track when several product modes or output categories need equal visibility.

### Explanatory, benefit-led product page

1. **promise** — Mono eyebrow, large left headline, prose and two small actions beside playful illustration; a trust strip follows.
2. **capability chapters** — Lavender benefit grid, cream template selector, ice-blue feature grid and cream integration spread.
3. **objection handling** — White split FAQ with generous expanded answers.
4. **closing call** — Centered account form with oversized hand-drawn arrows.
5. **directory** — White version of the shared footer.

**Transfer:** Use this warmer educational variant when explaining a category or attracting first-time users.

### Plan selection and commercial clarity

1. **choice** — Small announcement, choice-oriented headline, product index and four ruled plan columns.
2. **extension** — Open introduction beside stacked add-on panels.
3. **comparison** — Filter controls and a long ruled feature matrix.
4. **objection handling** — Lime split FAQ followed by a monochrome trust strip.
5. **directory** — Black shared footer, without a repeated monumental sales bar.

**Transfer:** Prioritize comparable details and practical answers over product theater.

### Finite event or campaign registration

1. **invitation** — Dark headline stage, date/time, broad outlined registration action and modular geometric artwork.
2. **details** — Pale-cyan registration band followed by saturated green details and ruled schedule.
3. **human proof** — Four-column grayscale cutout portrait wall.
4. **objection handling** — Compact split FAQ on white.
5. **brand ending** — Geometric ribbon and spacious black wordmark footer.

**Transfer:** Use the campaign theme only for a time-bound program with its own visual alphabet.

## Writing

Confident, useful and creatively optimistic. Short promises are followed by concrete descriptions of what the reader can do; playful phrasing is grounded by practical workflow detail.

**Do not copy:** Do not reuse Figma product names, logos, campaign artwork, customer marks, quotations, market-share statistics, dates, prices or proprietary claims. Example phrases illustrate structure only; write original copy for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; speak about teams and shared work without adopting a corporate we-heavy voice. Product names clarify the tool behind a capability.
- **Rhythm:** Compact headlines and paired sentences; one or two supporting sentences, then a brief verb-led action. Contractions are natural. Exclamation marks belong to the campaign's invitation tone, not ordinary feature copy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Product promise | Two complementary statements: expansive benefit, then exactness. | 8–14 words | “Made for the big picture. Perfect down to every pixel.” |
| Capability lead | Direct benefit with a memorable parallel phrase. | 5–12 words | “Powerfully expressive. Incredibly precise.”<br>“An infinite canvas for infinite expression.” |
| Practical support | Explain the mechanism with active verbs and real objects. | 15–35 words | “Create pixel-perfect designs with vector editing. Use vector brushes, advanced stroke settings, fills, and more.” |
| Primary action | Short verb-led start; mention free only where true. | 2–5 words | “Get started”<br>“Start a whiteboard” |
| Exploration link | Action plus destination or artifact. | 2–5 words | “Get the guide”<br>“Browse all templates” |
| Closing thought | Aspirational sentence about removing a constraint. | 7–12 words | “Ideas no longer have to wait their turn” |
| Commercial headline | Two plain imperatives that frame a choice. | 6–10 words | “Pick your plan, choose your seats” |
| FAQ | A real reader question, answered directly before qualification. | 5–16 words per question | “Can I purchase products individually?” |

**Words and phrasing to use:** make; build; draw; shape; together; your team; context; details; explore; start; from … to …

**Avoid:** revolutionary ecosystem; unparalleled synergy; unlock limitless potential; best-in-class solutions; vague AI superlatives

**Rules:**

- Pair an expressive promise with an explanation of the action or mechanism.
- Describe observable product behavior before broad business outcomes.
- Keep exploration labels artifact-specific when a guide, template or documentation is the destination.
- Put qualifications beside the number or commercial statement they constrain.
- Use human language for benefits and accurate technical names for mechanisms.

## Do's and Don'ts

### Do

- Keep the default opening at 44px/1.1 with regular weight and a same-size gray promise.
- Give primary product media the full 1360px inner width at desktop.
- Preserve 16px gutters even when mixing two-thirds and one-third media.
- Use 80px narrative padding and 120px footer padding as distinct rhythms.
- Retain the 84px hero actions with different primary and secondary silhouettes.
- Give the closing conversion a full-width 136px-high black bar and 56px label.
- Use 1px rules to organize the catalog and 40px indents to frame proof.
- Carry the tactile grain or halftone treatment into at least one prominent demonstration.

### Don't

- Do not make all headings 56–86px; those sizes belong to specific page variants and conversion devices.
- Do not apply the secondary pill silhouette to the 16px-radius primary hero action.
- Do not round every image or add floating drop shadows to the flat media grid.
- Do not spread the campaign's saturated green across an ordinary product landing page.
- Do not use blue as the default link or button color; actions remain black.
- Do not turn the feature index into a grid of equally tall rounded cards.
- Do not increase feature captions from 16px to headline scale; media should carry the expression.
- Do not replace the separate 88px proof number and 14px qualification with a wall of decorative statistics.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare background and box-shadow transitions at 180ms ease-out.
- The closing conversion bar additionally transitions border-radius at 180ms ease-out and changes to 80px radius on hover.
- Header background declares 0.4s cubic-bezier(0.8,0,0.2,1).
- The blue radial portrait ornament declares a 25s linear infinite animation; product demonstrations have explicit play/pause controls.

**Transfer:**

- Keep the distinctive closing-bar corner morph and restrained action transitions.
- Preserve independent play/pause controls for moving demonstrations and logo tracks rather than making media an uncontrolled background.

**Unknown:**

- Exact demonstration choreography and scroll-trigger timing are unspecified.

### Responsive

**Observed:**

- Marketing styles declare width breakpoints including 480px, 560px, 768px, 960px, 1024px, 1280px and 1440px.
- Campaign styles declare 767px/768px and 1024px/1025px boundaries.

**Transfer:**

- On narrow layouts, stack the opening text and actions before the product stage while preserving the name/promise equal-scale relationship.
- Collapse asymmetric media spreads into a dominant scene followed by supporting examples; preserve texture as backing rather than reducing the interface to illegibility.
- Turn catalog columns into a clear reading stack of name, media, description and links. Keep commercial comparisons navigable instead of compressing every tier into one tiny viewport.

**Unknown:**

- Exact mobile typography, side insets, menu behavior and table overflow treatment are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
