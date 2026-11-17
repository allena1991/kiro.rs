# Reevo — condensed posters, pixel patchwork

## Overview

A forceful editorial style for complex software that wants to feel useful, human and unusually confident. Heavy condensed grotesk headlines sit above open white layouts, warm stone bands and abrupt black chapters, with small monospaced labels providing a technical counterpoint. Color is concentrated in pastel category markings and vivid patterned interface stages; candid workplace film and black-and-white portrait collage keep the product story grounded in people.

### Essentials

- Headlines behave like tightly stacked posters: Metrify uppercase at 113.2px/0.8, weight 900 and -0.01em tracking; capability headlines use 76px/0.8 at weight 800.
- The default opening is a centered claim above a wide human product film: a 72px white navigation bar, 56px opening inset, two-line headline across 1231px, bold 26px support, paired 46px actions and a 1344px-wide media stage beginning within the first screen.
- Actions are broad, shallow rectangles rather than pills: 8px corners, 20px horizontal padding, left-aligned 16px medium labels and a small right-edge icon; compact header actions are 36px tall with 4px corners.
- The page stays predominantly white, warm gray and near-black; category color lives in 24px labels, 32px icon squares and the large media half of feature chapters, not in everyday buttons or body copy.
- Product proof is an enlarged fragment on a graphic stage, not a miniature complete application: square media around 777px beside a 437px text column, vivid inset fields, pale checker-and-stripe borders and white interface panels. Use a legible single-workflow illustration when no interface exists.
- Pixel patchwork is a signature device: hard-edged checkerboards, fine stripes and dithered rectangles form 120px section-edge ornaments and portrait corners. A monumental left-aligned closing statement repeats the 113.2px display scale on white, followed by stacked actions rather than a colored CTA card.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orange marker | `#fa7b34` | `--color-marker-orange` | accent | Small square category markers. |
| Blue marker | `#3896fa` | `--color-marker-blue` | accent | Small square category markers. |
| Yellow marker | `#ffdd4e` | `--color-marker-yellow` | accent | Small square category markers. |
| Pink marker | `#e36fb6` | `--color-marker-pink` | accent, text | Small square category markers and timeline context. |
| Green marker | `#54c794` | `--color-marker-green` | accent | Small square category markers. |
| Lemon | `#fffda7` | `--color-lemon` | surface, accent | Category label and icon-square backing. |
| Light blue | `#b4e0ff` | `--color-blue` | surface, accent | Shared-system icon-square backing. |
| Peach icon tile | `#fecfb5` | `--color-peach-icon` | surface | Warmer 32px icon-square variant in the capability map. |
| Mint | `#bef5dd` | `--color-mint` | surface, accent | Category label and icon-square backing. |
| Peach label | `#fedfce` | `--color-peach` | surface, accent | Warm category labels and feature icon backings. |
| Pink icon tile | `#fed3ed` | `--color-pink-icon` | surface | 32px icon-square variant in the capability map. |
| Pink wash | `#ffe2f4` | `--color-pink` | surface, accent | Category labels and the light testimonial-panel variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#121212` | `--color-ink` | text, background, action | Headlines, primary actions and dark chapters. |
| Charcoal | `#3c3c3c` | `--color-body` | text, border, background | Paragraphs and outlined actions; a darker testimonial-band variant. |
| Muted gray | `#92918f` | `--color-muted` | text | Footer category headings, captions and legal information. |
| Stone and hairline | `#e7e7de` | `--color-stone` | background, border | Proof bands, secondary plan fill, separators and label outlines. |
| Warm cream | `#f2f2ea` | `--color-cream` | background, text | Platform overview and product opening bands; warm inverse paragraph text. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, navigation, interface panels and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling | Cyan statement | `#77dbec` | `--color-cyan` | background, accent, text | Company manifesto banner and portrait-caption highlights. |
| mobile-product landing pages | Magenta emphasis | `#d156a2` | `--color-magenta` | text | Second half of the mobile-product opening headline. |
| company and mobile-product pages | Ice blue | `#d8efff` | `--color-ice` | surface | 48px principle icons and mobile capability icons. |
| pricing and detailed product pages | Pale ivory | `#f7f7f0` | `--color-pale` | surface, background | Lightest pricing tier and capability-grid band. |

## Typography

- **Metrify** — Monumental headlines and condensed chapter titles. Very narrow, heavy grotesk with tall capitals and tightly packed lines. If unavailable, use **Anton**. Match condensed width before tuning line breaks; retain the tight line height. Font stack: "Metrify", "Anton", sans-serif.
- **Haltung** — Paragraphs, mixed-weight editorial headings, controls and quotations. Direct contemporary grotesk; open regular text contrasts with emphatic bold phrases. If unavailable, use **Inter**. Use weights 400, 500, 600 and 700 with the recipe-specific tracking. Font stack: "Haltung", "Inter", system-ui, sans-serif.
- **GTAmericaMono** — Uppercase navigation, eyebrows, category labels and speaker credits. Small utilitarian monospaced markings, not code-heavy decoration. If unavailable, use **IBM Plex Mono**. Font stack: "GTAmericaMono", "IBM Plex Mono", Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Metrify | 900 | 113.2px | 0.8 | -0.01em, uppercase | Primary promise and monumental closing statement. |
| heading-condensed | Metrify | 800 | 76px | 0.8 | -0.01em, uppercase | Capability chapters, FAQ title and plan names. |
| editorial | Haltung | 400 | 42px | 1.05 | -0.01em | Sentence-case section introductions. |
| editorial-emphasis | Haltung | 700 | 42px | 1.05 | -0.01em | Bold outcome phrase inside editorial headings. |
| hero-support | Haltung | 700 | 26px | 1.1 | -0.02em | Centered two-line opening explanation. |
| quote | Haltung | 500 | 26px | 1.1 | -0.02em | Long testimonial set upright, not italic. |
| lead | Haltung | 400 | 20px | 1.35 | normal | Section support and opening explanations outside the default hero. |
| item-title | Haltung | 700 | 20px | 1.15 | -0.02em | Feature names, proof-card quotes and short card headings. |
| body | Haltung | 400 | 18px | 1.35 | normal | Main explanatory paragraphs. |
| question | Haltung | 500 | 18px | 1.35 | normal | FAQ question controls. |
| small-body | Haltung | 400 | 16px | 1.35 | normal | Capability lists and footer links. |
| action | Haltung | 500 | 16px | 1.35 | normal | Primary and secondary button labels. |
| caption | Haltung | 400 | 14px | 1.15 | -0.01em | Small supporting labels and footer headings. |
| compact-action | Haltung | 500 | 14px | 1.15 | -0.01em | Header actions. |
| eyebrow | GTAmericaMono | 400 | 12px | 1.15 | normal, uppercase | Navigation, chapter labels, badges and speaker credits. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interactive product chapters | feature-control | Haltung | 700 | 18px | 1.35 | normal | Selectable feature headings. |

**Notes:**

- Display and condensed chapter type share -0.01em tracking and a deliberately compressed 0.8 line height. Do not apply that compressed leading to ordinary sans-serif copy.
- Editorial headings combine regular and bold within a sentence; the bold phrase is an argument, not a separate colored heading.
- Body copy stays sentence case. Uppercase is reserved for condensed display and the small mono marking system.
- Use controlled line breaks to make solid blocks of headline text; keep paragraph columns around 437px and section introductions around 664px.

## Layout

**Density:** Airy at the chapter scale, compact inside controls and capability lists; large blank intervals make the dense condensed type feel deliberate.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Paired-action gap and small title-to-copy gap. |
| 12px | Capability-row spacing and heading-to-support spacing. |
| 16px | Primary grid gutter and icon-label gap. |
| 20px | Button side padding and FAQ vertical padding. |
| 24px | Card padding and hero headline-to-support gap. |
| 32px | Hero label-to-headline gap and action separation from support. |
| 40px | Category label-to-feature-heading spacing. |
| 48px | Outer desktop gutter and hero action-to-film gap. |
| 56px | Opening top padding, feature-copy-to-action gap and closing grid row gap. |
| 80px | Footer vertical padding. |
| 96px | Eyebrow-to-editorial-heading separation and large content-group gaps. |
| 128px | Major section vertical padding. |

### Containers and grids

- **outer container**: max width 1400px · side padding 48px. Centered desktop wrapper; at 1440px the working width is 1344px.
- **editorial grid**: 24 columns · gap 16px. Desktop alignment system. Text commonly starts one column inside the wrapper, around 105px from the viewport edge.
- **feature split**: gap 16px. A 437px text column at the inset left faces a 777px square media stage on the right; interactive chapters can reverse the media side.
- **proof grid**: 3 columns · gap 16px. Three approximately 400px-wide proof cards within the inset content span.
- **footer grid**: 6 columns · gap 16px. Six approximately 201px-wide link columns with a separate low utility row.
- **plan grid** (only for pricing pages): 3 columns · gap 6px. Three 406px-wide plan panels across a 1231px inset span; tighter seams than the general grid.

## Corner radius

| Element | Radius |
| --- | --- |
| main actions | 8px |
| compact actions and trust badges | 4px |
| labels and icon tiles | 2px |
| chapter panels | 0px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default page, navigation and closing statement.

**CSS:** `background: #ffffff; color: #121212`

**Observed:** Flat and untextured; whitespace carries the hierarchy.

**Transfer:** Keep the surrounding page plain so the graphic media stages have impact.

#### Cream chapter · level 0

**Use:** System overviews and product openings.

**CSS:** `background: #f2f2ea; color: #121212; padding: 128px 0`

**Observed:** Full-width warm band with a pixel ornament attached to its upper edge.

**Transfer:** Use for a cohesive explanation of the product rather than for every card.

#### Black chapter · level 0

**Use:** Problem framing, selected feature demonstrations and narrative contrast.

**CSS:** `background: #121212; color: #ffffff; padding: 128px 0`

**Observed:** A solid near-black field, warm pale supporting copy and white linework; no ambient glow.

**Transfer:** Give a high-stakes argument or focused product chapter the strongest contrast.

#### Stone proof band · level 0

**Use:** Customer-proof collections and portrait quote stages.

**CSS:** `background: #e7e7de; padding: 128px 0`

**Observed:** Flat warm-gray backing behind white cards or a black quote block.

**Transfer:** Separate proof from white feature chapters without adding gradients.

#### Shared-layer strip · level 1

**Use:** A unifying caption beneath a capability map.

**CSS:** `background: rgba(18, 18, 18, 0.075); padding: 12px 16px`

**Observed:** A shallow neutral overlay across the cream overview, darker than its backing.

**Transfer:** Use a full-width strip to explain what several capabilities share.

#### Pale capability band · level 0

**Only for:** detailed product and pricing pages

**Use:** Dense capability collections.

**CSS:** `background: #f7f7f0; padding: 128px 0`

**Observed:** Slightly lighter than the cream chapter; carries a two-column graphic-card grid.

**Transfer:** Use when several detailed benefits need one visual container.

#### Cyan manifesto banner · level 0

**Only for:** company storytelling

**Use:** A compact, emphatic company opening.

**CSS:** `background: #77dbec; color: #121212`

**Observed:** Inset between the outer gutters; a stepped pixel fringe dissolves its bottom edge into white.

**Transfer:** Keep this brighter identity treatment separate from normal product openings.

## Components

### Navigation

**Use:** Persistent wayfinding.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 72px; background: #ffffff`

**Text style:** `eyebrow` — GTAmericaMono 400 · 12px/1.15 · uppercase

**Observed:** Logo at left, small uppercase mono links centered and two compact actions at right. Dropdown triggers use small downward chevrons; link hit areas are 36px tall with 16px side padding.

**Transfer:** Balance the logo and action zones so navigation stays centered, not crowded against the wordmark.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: space-between; height: 46px; padding: 0px 20px; gap: 6px; background: #121212; color: #ffffff; border-radius: 8px`

**Text style:** `action` — Haltung 500 · 16px/1.35

**Observed:** Label at left and a 16px right chevron at the far edge. The paired opening actions share a 500px maximum row; closing actions are 324px wide and stacked.

**States:** Declared: hover opacity 0.8.

**Transfer:** Keep the action broad enough for the left label and right icon to read as separate anchors.

### Secondary button

**Use:** Product tour, download or deeper explanation.

**CSS:** `display: inline-flex; align-items: center; justify-content: space-between; height: 46px; padding: 0px 20px; gap: 6px; border: 1px solid #3c3c3c; border-radius: 8px; color: #3c3c3c; background: transparent`

**Text style:** `action` — Haltung 500 · 16px/1.35

**Observed:** Shares the primary action's visual footprint; uses an outlined play-square, QR symbol or right chevron appropriate to the destination.

**States:** Declared: hover background-color color-mix(in oklab,#3c3c3c10%,transparent).

### Compact action

**Use:** Header conversion controls.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 36px; padding: 0px 12px; gap: 4px; background: #121212; color: #ffffff; border-radius: 4px`

**Text style:** `compact-action` — Haltung 500 · 14px/1.15 · tracking -0.01em

**Observed:** No trailing icon. A neighboring outlined login action uses charcoal text and border; the pair has an 8px gap.

**States:** Declared: hover opacity 0.8 on the filled action; hover background-color color-mix(in oklab,#3c3c3c10%,transparent) on the outlined action.

### Technical label

**Use:** Opening classification and small availability markings.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 21px; padding: 0px 8px; border: 1px solid #e7e7de; border-radius: 2px; color: #121212`

**Text style:** `eyebrow` — GTAmericaMono 400 · 12px/1.15 · uppercase

**Observed:** Thin outline and compact capitals. Feature-category variants replace the border with a pastel fill and use a 24px height; section eyebrows instead pair an unboxed label with a 24px inverse icon tile.

### Capability row

**Use:** Compact product-system inventory.

**CSS:** `display: flex; align-items: center; gap: 12px; margin-bottom: 12px; color: #121212`

**Text style:** `small-body` — Haltung 400 · 16px/1.35

**Observed:** A 32px square pastel icon tile with 2px corners precedes each label. Groups sit under bold item titles and can carry a small availability label.

**Transfer:** Assign one pastel to each capability family and repeat it consistently in later demonstrations.

### Video proof card

**Use:** Customer proof in a three-column collection.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 0px`

**Text style:** `item-title` — Haltung 700 · 20px/1.15 · tracking -0.02em

**Observed:** A 400px-wide card combines a 400px by 225px monochrome interview still, a small dark play control, bold upright quotation and tiny mono speaker credit pinned low. Overall cards are about 470px tall.

**Transfer:** With no video, use a real monochrome portrait still and retain the quote-credit hierarchy.

### FAQ row

**Use:** Objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 20px 0px; color: #121212; border-bottom: 1px solid #e7e7de`

**Text style:** `question` — Haltung 500 · 18px/1.35

**Observed:** Questions sit in a 664px column; single-line rows are about 65px tall including their hairline. Small plus icons align at the far right; the whole list also has top and bottom rules.

**Transfer:** Place the condensed FAQ heading in the left column rather than above a centered list.

### Footer link

**Use:** Low-density multi-column navigation.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 4px 0px; color: #121212`

**Text style:** `small-body` — Haltung 400 · 16px/1.35

**Observed:** Category headings use the caption recipe in muted gray. Product-family links carry an 8px colored square; ordinary links remain unmarked. The footer ends with legal links, three small outlined trust badges and social symbols.

**Transfer:** Preserve the sparse six-column organization and generous separation from the legal row.

### Feature accordion

**Only for:** interactive product chapters

**Use:** Select a benefit while showing its corresponding media.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 12px 16px; color: #121212`

**Text style:** `feature-control` — Haltung 700 · 18px/1.35

**Observed:** The selected item expands explanatory body text below its heading and uses a dark 1px left rail; closed items retain a pale rail and muted heading. On black chapters the active rail and text reverse to white.

**States:** Declared: closed heading opacity 0.6.

**Transfer:** Link each item to one readable product fragment, not to a different whole-page dashboard.

### Plan panel

**Only for:** pricing pages

**Use:** Tier selection and sales contact.

**CSS:** `display: flex; flex-direction: column; background: #f7f7f0; border-radius: 0px`

**Text style:** `heading-condensed` — Metrify 800 · 76px/0.8 · tracking -0.01em · uppercase

**Observed:** Plan name, bold audience description, email field, full-width contact action, mono allowance bullets and a bottom comparison link. Content has 24px side padding and 32px top padding. The middle tier is stone; the custom tier is black with a white action. Panels measure about 406px by 604px.

**Transfer:** Differentiate tiers with neutral surface value, not ribbons or a neon recommended badge.

### Email input

**Only for:** pricing conversion forms

**Use:** Work-email entry before a sales conversation.

**CSS:** `display: flex; height: 46px; padding: 8px 16px; background: #ffffff; border: 1px solid rgba(18, 18, 18, 0.2); border-radius: 8px; color: #3c3c3c`

**Observed:** Matches the full-width action beneath it. The custom dark tier uses a dark field and a pale translucent border; placeholder text is muted.

## Imagery and graphics

### Pixel patchwork

**Use:** Required graphic punctuation at section boundaries, product stages and portrait corners.

**Observed:** Hard rectangular fragments of checkerboard, tiny dots and narrow horizontal or vertical stripes; monochrome on neutral bands, pastel or saturated on product media. Edge ornaments occupy roughly the right half of a section and are 120px high; thin full-width variants are 40px high.

**Transfer:** Use this vocabulary even without bespoke artwork; adapt its palette to a small set of product categories.

**Build:** Create an SVG pattern library: alternating square cells at 2px, 4px and 8px; 1px stripes on 3px or 4px repeats; 1px dots on a 3px grid. Fill adjoining rectangles of uneven widths with these patterns, leaving hard rectangular cutouts. Use white and ink on dark bands or white against cream and stone on light bands. For a 664px by 120px ornament, divide into two rows of 60px-high rectangles and remove one upper-middle block. Use no blur, bevel or rounded clipping.

### Enlarged interface stage

**Use:** Capability demonstrations beside concise text.

**Observed:** White interface fragments float or crop inside square graphic fields around 721px to 777px. Pale peach, pink, mint and lemon borders surround vivid orange, magenta, green or yellow centers. Panels are front-facing rather than in perspective; slight grain and directional shadows add depth inside the artwork.

**Transfer:** Show one consequential action at a readable scale. If no interface is available, draw a clean white panel with a heading, a few genuine inputs or records and one outcome annotation; place it over the same patterned surround.

**Build:** Use a square container, reserve an approximately 48px patterned perimeter and inset a solid category-colored rectangle. Overlay one or two white UI panels, allowing the lower or right edges to clip. Fill the perimeter with Pixel patchwork in the corresponding pale tint; vary rectangular patches rather than applying one uniform wallpaper. For a minimal version use the palette's marker color as the center and its pastel counterpart as the border.

### Human workflow film

**Use:** Opening product promise and mobile use-case proof.

**Observed:** Warm natural-color workplace scenes, conversations and people using a phone away from a desk. Wide opening film is 1344px by 756px; mobile-product opening uses a 777px square image. Small task or assistant notifications sit over the human scene rather than replacing it.

**Transfer:** Use candid footage of the new audience in the setting where the product helps. Without film, use a well-lit editorial still with one restrained outcome annotation, not a generic device render.

### Monochrome problem photography

**Use:** Problem-framing chapter.

**Observed:** Three square 400px conceptual black-and-white photographs depict physical awkwardness or frustration; each has a restrained translucent colored rectangle and white explanatory text below on black.

**Transfer:** Translate the product's friction into a human or spatial metaphor rather than illustrating abstract AI machinery.

**Build:** Desaturate three consistently lit square photos. Overlay a single hard-edged peach, mint or pink rectangle at approximately 20% alpha over a relevant object or gesture; keep faces and the central action readable.

### Portrait quote collage

**Use:** High-impact single-customer proof.

**Observed:** A 453px square monochrome portrait joins flush to a larger black quotation block inside a stone band. Portrait edges carry checker and stripe fragments plus one colored square; a white mono name strip overlays its lower portion. A product-specific variant uses a pink quote panel on charcoal.

**Transfer:** Keep the portrait human and candid, the quotation upright and the credit small. Use real attribution or replace the quote with an independently supportable proof statement.

**Build:** Place a square grayscale portrait beside a solid quote panel of equal height. Add 48px to 64px square checker/stripe patches at a few corners, one mint or peach square, and a white horizontal credit strip near the portrait bottom. Do not frame the entire portrait with a continuous border.

### Team and backer graphics

**Only for:** company storytelling

**Use:** People and institutional confidence after the company narrative.

**Observed:** A two-column portrait wall uses black-and-white photography, cyan pixel-corner accents and long black mono name bars. Backer marks sit centered in two large black rectangles with a small stepped upper corner.

**Transfer:** Use consistent portrait framing and genuine partner marks; keep these identity-led graphics out of ordinary feature chapters.

**Build:** Reuse Pixel patchwork at portrait corners with one cyan square; anchor a black caption strip across the lower image. For endorsement tiles, use a black rectangle with a small 48px stepped notch and a white authorized mark.

### Icons

**Observed:** Small outline SVG icons, primarily 16px with 2px rounded strokes; 12px variants accompany navigation and small labels. They use charcoal, ink or white, and sit in 32px pastel squares for the capability map or 48px squares for broader principles. Chevron arrows and outlined play-squares occupy button right edges.

**Transfer:** Use a consistent rounded-stroke outline set with simple equipment-like silhouettes; reserve filled icons for recognizable social marks and avoid multicolor pictograms.

## Section recipes

How recurring sections are built.

### First screen: Centered poster opening

**Observed:** White canvas beneath Navigation. A Technical label is centered after a 56px top inset, then a two-line display headline across about 1231px, with 32px between label and headline. The headline uses heavy condensed uppercase, not mixed-weight editorial text. A centered 777px-wide hero-support block follows after 24px. Primary button and Secondary button sit side by side in an approximately 500px row, 8px apart, after 32px of breathing room. Human workflow film starts 48px beneath the actions and spans 1344px. Back-to-front layers are plain white, typographic promise and controls, then the photographic film with small outcome overlays. Within the first 900px the complete label, headline, support and actions are visible along with the upper part of the film; the rest of the 756px-tall film extends below.

**Transfer:** Default to this composition for a new marketing landing page. Replace the claim and film with a strong audience-specific promise and a candid still or one enlarged product workflow. Pricing opens left-aligned with a small mono label and the same display scale above plan panels. Detailed product pages can use a cream opening with a wide interface stage. Mobile-product pages use a 437px text column, 76px condensed heading with a magenta outcome phrase and a square human scene at right. Company storytelling uses the Cyan manifesto banner.

**Avoid:** Do not compress the whole film above the fold, put the headline over the photograph, or replace the condensed headline with a conventional rounded sans hero.

**Text style:** `display` — Metrify 900 · 113.2px/0.8 · tracking -0.01em · uppercase

### Editorial chapter introduction

**Observed:** A small mono eyebrow beside an inverse icon tile precedes a 664px-wide sentence-case heading by 96px. The heading mixes editorial and editorial-emphasis; a 20px lead follows with about 12px spacing. Pixel patchwork sits at the upper-right chapter edge, independent of the text.

**Transfer:** Use for a system explanation, a problem statement or a proof introduction; emphasize the few words that contain the actual outcome.

**Text style:** `editorial` — Haltung 400 · 42px/1.05 · tracking -0.01em

### Capability map

**Observed:** Cream chapter contains a four-column set of titled capability families using Capability row. Category colors remain consistent through each column. A Shared-layer strip spans underneath, with a secondary six-item capability row below it.

**Transfer:** Organize a complicated product into a few understandable families and explain their common enabling layer. The number of families should follow the new product.

### Problem triptych

**Observed:** Black chapter pairs Editorial chapter introduction with three equal square Monochrome problem photography images, bold item-title captions and 18px pale body paragraphs. Image and text groups align on one baseline and use 16px grid gaps.

**Transfer:** Turn a familiar pain into three concrete scenes before demonstrating the alternative.

### Capability split

**Observed:** A narrow 437px text column holds a pastel category label, heading-condensed headline, 18px paragraph and Secondary button; the opposing 777px square uses Enlarged interface stage. Categories keep their media on the right in the default long-form marketing treatment. Interactive chapters reverse sides and use Feature accordion beneath the introductory copy.

**Transfer:** Choose one outcome per chapter. Keep the explanatory side much quieter than the colorful media side.

**Text style:** `heading-condensed` — Metrify 800 · 76px/0.8 · tracking -0.01em · uppercase

### Customer proof collection

**Observed:** Stone proof band uses an Editorial chapter introduction above three Video proof cards. The cards share equal height and credits sit low despite differing quote lengths. A Portrait quote collage supplies a separate, wider proof format.

**Transfer:** Use either compact comparative proof or a sustained firsthand story according to the available material; retain at least one human proof treatment.

### FAQ split

**Observed:** White canvas with 128px vertical padding, a 76px condensed title in the left column and FAQ rows in a 664px right column. The questions are sentence case, with far-right plus icons and thin stone rules.

**Transfer:** Keep questions specific to the purchase or workflow and let answers expand within the existing column.

**Text style:** `heading-condensed` — Metrify 800 · 76px/0.8 · tracking -0.01em · uppercase

### Monumental closing and footer

**Observed:** A white closing section uses 128px vertical padding, a left-aligned display headline across roughly 1174px and a plain 20px reassurance line 56px below. Another 56px gap leads to a 324px-wide Primary button stacked above Secondary button with 8px between. The footer has 80px vertical padding, six Footer link columns, then a widely separated utility row with muted legal text, outlined 28px-high trust badges and social marks. Company storytelling ends after its backer band and proceeds directly to this footer rather than inserting the conversion block.

**Transfer:** End conversion pages with a short, rhythmic restatement of the outcome at poster scale, not a new feature list. For company pages let human or institutional proof provide the ending.

**Text style:** `display` — Metrify 900 · 113.2px/0.8 · tracking -0.01em · uppercase

### Detailed capability grid

**Only for:** detailed product pages

**Observed:** Pale capability band contains a 76px condensed heading and a two-by-two grid of roughly 607px-wide graphic cards separated by 16px. Each card has a short white bold benefit and white body paragraph at top, vivid orange or magenta material beneath, and enlarged front-facing interface fragments below.

**Transfer:** Use for closely related operational benefits, not as a generic grid of small white feature cards.

**Text style:** `heading-condensed` — Metrify 800 · 76px/0.8 · tracking -0.01em · uppercase

### Timeline proof

**Only for:** mobile or in-context product storytelling

**Observed:** Black chapter places a condensed headline at left and a short pale lead at right. Below, three equal columns have white 1px left rails, time labels, pink context phrases and 18px body copy. Repeated 1px by 40px low-opacity ticks form a ruler near the column bottoms. A wide natural-color photograph then extends the chapter and overlaps patterned pink art.

**Transfer:** Tell a concrete sequence through the user's day or workflow. If time is irrelevant, use stages with the same ruled treatment.

**Text style:** `heading-condensed` — Metrify 800 · 76px/0.8 · tracking -0.01em · uppercase

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Left-aligned display promise leads into Plan panels with a 6px grid gap. A thin outlined assistance banner spans below them. Comparison is an editorial-emphasis heading followed by category groups: 32px bold sans group titles and three-column tables, each cell bordered with stone hairlines and padded 16px 24px. Main comparison rows are 60px high and longer descriptions expand to 76px.

**Transfer:** Compare meaningful limits in a quiet ruled matrix and let neutral tier surfaces establish priority.

## Page flow

**Storyline:** Promise → tangible demonstration → system explanation or problem framing → capability chapters → human proof → purchase reassurance → monumental closing and sparse navigation; adapt the emphasis to the page's purpose.

### Broad marketing landing page

1. **Promise** — Centered poster headline, paired actions and wide human workflow film.
2. **Social proof** — A quiet horizontal customer-logo strip.
3. **System explanation** — Cream capability map with a common-layer strip.
4. **Problem framing** — Black photographic triptych.
5. **Capability chapters** — Condensed outcome headings beside large patterned product stages.
6. **Human proof** — Interview cards and a portrait quote collage, separated by a shared-system demonstration.
7. **Closing call** — Monumental white conversion block and six-column footer.

**Transfer:** Introduce a complex product with one strong promise, then alternate human consequences and clear product evidence rather than listing everything at once.

### Pricing and sales qualification

1. **Promise** — Left-aligned display heading and brief explanation.
2. **Pricing** — Three neutral Plan panels with audience fit, email forms and allowances; an assistance banner below.
3. **Comparison** — Category-grouped ruled comparison matrix.
4. **Objection handling** — FAQ split.
5. **Closing call** — Shared monumental conversion and footer.

**Transfer:** Let tier audiences and meaningful limits do the selling; keep pricing surfaces neutral and reserve black for the custom offer.

### Mobile or context-specific product landing page

1. **Promise** — Split opening with a two-part condensed headline, natural-color scene and small assistant overlays.
2. **Capability chapters** — Three alternating media-and-accordion chapters showing preparation, action and completion.
3. **Scenario proof** — Dark ruled timeline followed by a wide contextual photograph.
4. **Objection handling** — FAQ split.
5. **Closing call** — Shared closing statement with a scenario-specific reassurance line, then footer.

**Transfer:** Anchor capabilities in the real situations where the user cannot use the full desktop product.

### Company narrative and trust

1. **Belief** — Cyan statement banner with a stepped patterned fringe.
2. **Mission** — Large mixed-weight paragraph and two actions.
3. **Narrative argument** — Black pinned text sequence with centered statements and small progress dots.
4. **Principles** — Open icon-and-text grid.
5. **People** — Large editorial paragraph and two-column monochrome portrait wall.
6. **Institutional proof** — Cream band with two black backer tiles.
7. **Navigation ending** — Direct transition to the shared footer; no conversion poster.

**Transfer:** Make the case for the people and beliefs behind the product; keep the scroll-led manifesto specific to this page type.

### Detailed capability landing page

1. **Promise** — Cream display opening, paired actions and enlarged interface scene beneath a sticky category strip.
2. **Capability overview** — Open three-column icon-and-text inventory.
3. **Demonstration** — Dark split chapter with selectable benefits and enlarged interface fragments.
4. **Human proof** — Pink portrait quote panel on charcoal.
5. **Capability demonstration** — Reversed light split followed by four vivid graphic capability cards on pale ivory.
6. **Objection handling** — FAQ split.
7. **Closing call** — Shared monumental conversion block and footer.

**Transfer:** Move from the broad outcome to inspectable workflow details, using one consistent category color family across the art.

## Writing

Confident, plainspoken and grounded in familiar work frustrations. The tone is ambitious without becoming abstract: each large promise is followed by a concrete account of what the product does.

**Do not copy:** Do not reuse Reevo's name, logo, customer identities, partner marks, quotations, sales claims, plan limits or performance assertions. Source examples demonstrate rhythm and structure only; use independently supportable claims and authorized assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your team. Refer to the product by name when explaining its behavior; use we for company beliefs rather than speaking as an omniscient machine.
- **Rhythm:** Compact punchy headlines, often two clauses or three short fragments. Supporting paragraphs use full practical sentences and lists of observable actions. Periods provide the force; exclamation marks are unnecessary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Contrast the familiar failure with the product's distinct alternative. | 6–12 words | “Your sales tools are guessing. [Brand] actually knows.”<br>“From prospect to pipeline.” |
| Capability heading | Lead with a desired result or a recognizable moment, not a feature taxonomy. | 3–9 words | “Numbers you can actually trust.”<br>“Know what changed before the door opens.” |
| Supporting explanation | Explain the action, where it happens and what manual effort disappears. | One to three sentences | “Every interaction, workflow, and record lives in a single memory layer so context compounds instead of scattering across tools.” |
| Primary action | Short verb phrase; human contact is described naturally. | 2–4 words | “Get started”<br>“Talk to a human” |
| Closing statement | Three parallel fragments that progress from breadth to mechanism to result. | 6–10 words | “Every workflow. Full context. Compounding results.” |
| Question | Ask the buyer's practical question directly. | 6–14 words | “Can [Brand] turn a business card or conference badge into a contact?” |

**Words and phrasing to use:** actually; your team; full context; in a click; before; without; one shared; on its own; what changed

**Avoid:** revolutionary synergy; unleash limitless potential; magic; next-generation ecosystem; effortless excellence

**Rules:**

- Pair an ambitious headline with a literal explanation of inputs, actions and outcomes.
- Use the vocabulary of the new audience's daily work rather than carrying over sales terminology by default.
- Name the manual task that disappears; do not simply promise productivity.
- Use bold inline emphasis sparingly to identify the argumentative phrase.
- Write labels as useful classifications and questions as genuine purchase concerns.

## Do's and Don'ts

### Do

- Keep condensed headline leading at 0.8 and tracking at -0.01em.
- Use the 24-column, 16px-gutter desktop alignment to relate headings, media and footer columns.
- Give major chapters 128px vertical space and preserve the 96px pause after an eyebrow.
- Carry pastel category coding from 32px icon tiles into the matching media border.
- Keep body paragraphs at 18px/1.35 and introductory explanations at 20px/1.35.
- Use hard pixel checker and stripe fragments at section edges and portrait corners.
- Keep normal conversion actions black or outlined, 46px high with 8px corners.
- Set testimonial quotes upright and speaker credits in small uppercase mono.

### Don't

- Do not substitute a wide geometric headline face for the narrow poster construction.
- Do not use 0.8 leading for body paragraphs or editorial sentence-case headings.
- Do not turn all neutral chapter bands into multicolor gradients.
- Do not make ordinary buttons pill-shaped or use the category colors as primary-action fills.
- Do not add soft drop shadows and rounded corners to the outer pricing or proof panels.
- Do not render product demonstrations as tiny entire dashboards inside perspective laptops.
- Do not decorate every paragraph with a pastel icon; keep the marking system attached to meaningful groups.
- Do not replace the sparse footer with a dark oversized wordmark wall.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s transitions with cubic-bezier(.4,0,.2,1), commonly for all properties or color-related properties; some use opacity only.
- Filled actions declare hover opacity 0.8; outlined actions declare a faint charcoal hover wash.
- Company storytelling uses a long black scroll-led sequence of centered statements with a pill-shaped active progress dot and smaller inactive dots.

**Transfer:**

- Keep control feedback short and restrained; pixel patchwork should remain crisp during state changes.
- For a company manifesto, use successive focused statements rather than moving all content continuously through the viewport.

**Unknown:**

- Exact scroll-sequence timing, trigger thresholds and media playback behavior are not established.
- No focus-visible treatment is established for the standard action buttons.

### Responsive

**Observed:**

- Declared width breakpoints are 480px, 600px, 840px, 1140px, 1380px and 1536px.
- Layout classes specify 6-column base, 12-column intermediate and 24-column wide grids; outer padding progresses through 24px, 32px, 40px and 48px.
- The opening action group declares a column layout before its side-by-side variant. Capability and proof collections declare horizontal snapping at narrower widths; the footer declares two base columns.
- Pixel section ornaments declare a 60px-high narrow variant and a 120px-high wider variant.

**Transfer:**

- As implementation guidance, preserve the condensed poster shape with fewer words per line rather than squeezing the desktop line breaks.
- Stack feature text and media while retaining the colorful square stage and legible interface fragments; use the declared snapping approach for suitable proof collections.
- Keep the closing actions stacked and let footer categories wrap into fewer columns.

**Unknown:**

- Rendered narrow-screen compositions and exact headline sizes at each breakpoint are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
