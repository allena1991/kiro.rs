# Apollo — serif meets solar energy

## Overview

An editorial serif voice gives complex software an approachable, almost conversational presence. White and warm stone pages are punctuated by electric yellow and liquid pastel color, with carefully isolated interface scenes rather than dense dashboards. The combination suits connected platforms and workflow products: spacious at the story level, precise and practical at the point of action.

### Essentials

- Conversational promises wear an editorial serif: seasonMix at weight 550, 72px/1 for the centered opening and 40px/1.1 for capability chapters, with -0.01em tracking.
- A bright white sheet sits inside a stone-colored browser-wide frame: 24px outer gutters, a 72px fixed navigation bar, 54px inner side padding, and 8–12px sheet corners.
- The opening sells before it demonstrates: an 848px-wide two-line headline, a 520px support and conversion column, then an expansive 1284×642px media stage beginning near the bottom of the first 900px.
- Conversion controls are squared-off, not capsules: 8px corners, 48px default height, black outlines or electric #ebf212 fills; black takes over on luminous backgrounds.
- Color behaves like energy behind the product: mostly white and #f7f5f2 content, with neon yellow and cyan, pink, and lilac fluid fields concentrated in media trims and a luminous conversion panel. Include this luminous device on every new landing page, even if implemented as a simple layered gradient.
- Product stories are calm square stages opposite text: roughly 602px square, pale warm backing, floating white UI fragments, selective yellow controls, and occasional pastel edge ribbons. When no interface exists, use a legible connected-card diagram rather than generic stock art.
- Proof can become typography-as-art: a 290px serif numeral in deep plum sits beside a much smaller 48px proof heading; captions remain 12px uppercase mono. Use a real metric or an equally emphatic short outcome, not an invented number.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric yellow | `#ebf212` | `--color-sunbeam` | action, accent | Main bright actions, small highlights and text selection; not the default paragraph background. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Monumental plum | `#3f3653` | `--color-plum` | text | Oversized typographic social proof. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline black | `#000000` | `--color-ink` | text, action, border | Display headings, primary dark buttons, outlined controls and strong icons. |
| Body charcoal | `#1a1a1a` | `--color-body` | text, action | Main paragraphs and selected conversion tabs. |
| Warm support ink | `#47423d` | `--color-support` | text, accent | Secondary body copy, benefit lists and dark-button hover. |
| Muted stone | `#736f6c` | `--color-muted` | text, border | Eyebrows, attribution captions and understated controls. |
| Input stone | `#94918e` | `--color-input-edge` | border | Input outlines and diagram connectors. |
| Stone frame | `#ccc9c6` | `--color-frame` | background, border | Outer page surround, navigation, footer and accordion separators. |
| Panel edge | `#e5e3e1` | `--color-edge` | border, surface | Faint panel edges and outlined-action hover. |
| Soft divider | `#edebe8` | `--color-soft-rule` | border, surface | Conversion-tab tracks and fine pricing-table dividers. |
| Warm paper | `#f7f5f2` | `--color-sand` | background, surface | Explanatory bands, proof cards and feature-card backing. |
| White sheet | `#ffffff` | `--color-canvas` | background, surface, text | Main content sheet, white cards, fields, and inverse button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages and pressed bright actions | Recommended-plan olive | `#c7cc43` | `--color-plan-edge` | border | Recommended-plan outline; also the pressed bright-action fill. |
| pricing pages | Add-on lavender white | `#faf8fe` | `--color-addon-wash` | surface | Extremely pale end of the add-on card gradient. |
| pricing pages | Recommended-plan cream | `#fffff7` | `--color-plan-wash` | surface | Visible result of rgba(254,255,217,0.2) on white. |

## Typography

- **seasonMix** — All editorial headings and large proof numbers. Soft, compact contemporary serif with conversational warmth, substantial lowercase forms and gently expressive terminals. If unavailable, use **Lora**. Use weight 500–600; tune line breaks to retain the compact two-line opening. Font stack: "seasonMix", "Lora", Georgia, serif.
- **abcDiatype** — Body copy, navigation, actions, card titles and attributions. Matter-of-fact grotesk with open counters; predominantly regular weight rather than heavy SaaS-style bold. If unavailable, use **Inter**. Use weight 400 for nearly all marketing text. Font stack: "abcDiatype", "Inter", Arial, sans-serif.
- **foundersGroteskMono** — Uppercase eyebrows, proof labels and category markings. Small utilitarian monospace used as a restrained editorial annotation. If unavailable, use **IBM Plex Mono**. Font stack: "foundersGroteskMono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monumental-proof | seasonMix | 550 | 290px | 0.6 | -0.9px | A single broad proof numeral or short outcome, staged as artwork rather than a normal heading. |
| display | seasonMix | 550 | 72px | 1 | -0.01em | Centered opening promise. |
| heading-xl | seasonMix | 550 | 64px | 1.05 | -0.01em | Closing conversion headline; also the left-aligned opening on audience-specific pages. |
| heading-lg | seasonMix | 550 | 56px | 1.05 | -0.01em | Major explanatory headings and large objection-handling titles. |
| heading | seasonMix | 550 | 48px | 1.1 | -0.01em | Centered section introductions and proof headings. |
| chapter-heading | seasonMix | 550 | 40px | 1.1 | -0.01em | Alternating capability chapters and price amounts. |
| card-title | abcDiatype | 400 | 24px | 1.2 | -0.01em | Feature-card titles, testimonial quotes and accordion questions. |
| body-lg | abcDiatype | 400 | 20px | 1.3 | -0.01em | Large supporting copy and 56px conversion buttons. |
| body | abcDiatype | 400 | 16px | 1.3 | normal | Paragraphs, navigation and default 48px button text. |
| caption | abcDiatype | 400 | 14px | 1.3 | normal | Attributions, footer links, compact 40px actions and supporting details. |
| label | foundersGroteskMono | 400 | 14px | 1.2 | 0.012em, uppercase | Explanatory labels and audience-opening identifiers. |
| eyebrow | foundersGroteskMono | 400 | 12px | 1.2 | 0.014em, uppercase | Chapter categories, logo-strip captions and proof labels. |
| micro | abcDiatype | 400 | 12px | 1.3 | normal | Conversion reassurance and compact plan descriptions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified testimonial cards | outcome-number | seasonMix | 550 | 88px | 1 | -0.01em | Bottom-right outcome; pair with a smaller suffix and uppercase mono caption. |
| connected-system diagrams | diagram-title | seasonMix | 550 | 35.9px | 1.19 | -0.01em | Centered serif names inside the diagram's rounded white cards. |
| connected-system diagrams | diagram-body | abcDiatype | 400 | 17px | 1.2 | normal | Short centered explanatory text within the diagram cards. |

**Notes:**

- Keep editorial headings at weight 550; do not simulate their warmth with italic or bold sans-serif.
- Serif tracking is consistently -0.01em except for the monumental numeral, whose tracking stays comparatively loose. Large headings use tighter leading than paragraphs.
- Use the sans-serif for quotes even when adjacent to enormous serif numbers. Mono remains a small annotation, never a competing headline.
- The 72px display is the default marketing opening; audience pages use the 64px heading-xl recipe. The 48px heading and 40px chapter-heading are separate roles, not interchangeable size choices.

## Layout

**Density:** Airy narrative spacing around compact, practical controls; text and imagery have room to stand independently.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and tight detail stacks. |
| 12px | Compact interior padding and proof-carousel gaps. |
| 16px | Body stacks, paired actions and heading-to-support spacing in centered sections. |
| 24px | Default heading-to-body gap, card padding and card-grid gutters. |
| 32px | Larger caption and content-group separation. |
| 40px | Heading-pair to card-grid or diagram spacing; accordion-band vertical padding. |
| 48px | Text-column vertical insets and larger grouped-content spacing. |
| 54px | Inner desktop horizontal section inset. |
| 78px | Gap between square media and capability text columns. |
| 80px | Opening top and bottom padding, large media separation and proof-column gaps. |
| 96px | Major warm-band vertical padding and separation before broad proof displays. |
| 120px | Breathing room between adjacent capability scenes, formed by 40px and 80px spaces. |

### Containers and grids

- **outer-sheet**: max width 1872px · side padding 24px. Centered white sheet within the stone surround; 1392px visible sheet width at a 1440px viewport.
- **content**: max width 1284px · side padding 54px. Desktop story content within the sheet. Maintain the outer gutter separately from this inner inset.
- **opening-headline**: max width 848px. Centered two-line serif promise above a narrower support and form stack.
- **conversion-column**: max width 520px. Support copy and conversion controls in the centered opening.
- **section-intro**: max width 630px. Centered eyebrow, heading and paragraph before cards or diagrams.
- **capability-split**: 2 columns · gap 78px. Approximately equal media and text columns; image is roughly 602px square and paragraph width is capped at 560px. Alternate sides across chapters.
- **feature-grid**: 4 columns · gap 24px. Four compact cards across a warm paper band; approximately 302px per card.
- **pricing-grid** (only for pricing pages): 4 columns · gap 0px. Equal 321px-wide plan columns, with vertical rules rather than separate floating cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls-and-feature-cards | 8px |
|  | sheet-and-proof-cards | 12px |
| connected-system diagrams | diagram-cards | 27.2px |
| pricing pages | billing-switch | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Stone surround · level 0

**Use:** Outer frame, navigation and full footer.

**CSS:** `background: #ccc9c6`

**Observed:** A continuous warm gray ground visibly frames the white sheet and reappears around the luminous closing panel.

**Transfer:** Keep the surround visible at both sides; it is a structural part of the page, not a card shadow.

#### White sheet · level 1

**Use:** Main story canvas.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden; box-shadow: none`

**Observed:** Long connected white sections share a single sheet, rather than each being detached cards.

**Transfer:** Group related narrative sections inside one continuous surface.

#### Warm paper band · level 1

**Use:** Explanation, FAQ, trust and supporting-content regions.

**CSS:** `background: #f7f5f2`

**Observed:** Warm tint establishes a new narrative chapter without a dark theme or a heavy border.

**Transfer:** Use for deeper explanation after white product chapters.

#### Flat white card · level 2

**Use:** Small feature summaries on warm paper.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 24px; box-shadow: none`

**Observed:** Simple icon-first cards with no ornamental edge or drop shadow.

**Transfer:** Let contrast against the band distinguish the card.

#### Luminous color field · level 1

**Use:** Signature media edges and closing conversion stage.

**CSS:** `background: radial-gradient(ellipse at 45% 110%, rgba(224,180,255,0.95), rgba(160,255,243,0.8) 28%, rgba(255,255,0,0) 55%), radial-gradient(ellipse at 95% 0%, rgba(246,187,213,0.9), rgba(255,255,0,0) 38%), rgb(255,255,0); border-radius: 12px; overflow: hidden`

**Observed:** Broad neon-yellow regions meet cyan, mint, pink and lilac with irregular, soft-edged liquid contours. The field can fill a panel or appear around a white inset.

**Transfer:** Match the luminous, gently marbled effect; exact gradient stops are not essential. Preserve broad quiet areas beneath text.

#### Recommended plan · level 2

**Only for:** pricing pages

**Use:** Highlight one plan without turning the pricing grid into a colored block.

**CSS:** `background: rgba(254,255,217,0.2); border: 1px solid #c7cc43; border-radius: 12px; padding: 18px`

**Observed:** Extremely light yellow wash; a compact yellow category marker and black purchase button carry the emphasis.

**Transfer:** Highlight one best-fit choice, not all paid choices.

#### Add-on panel · level 2

**Only for:** pricing pages

**Use:** Supplemental offers below the main tiers.

**CSS:** `background: linear-gradient(280deg, #faf8fe -5.1%, #ffffff 77.62%); border: 1px solid #edebe8; border-radius: 12px; padding: 24px`

**Observed:** Two equal-width panels with tiny category labels, serif titles and compact divided feature lists.

**Transfer:** Keep the tint almost white so the panels remain subordinate to primary tiers.

## Components

### Navigation

**Use:** Persistent orientation and compact conversion access.

**CSS:** `position: fixed; top: 0px; height: 72px; padding: 0px 24px; background: #ccc9c6; display: flex; justify-content: space-between; align-items: center; z-index: 999`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** Small symbol and wordmark at left, dropdown categories followed by plain destination links; login, outlined demo and yellow signup actions align at right. The navigation blends into the surround.

**States:** Declared: hover unspecified; focus-visible on dropdown triggers uses a 2px solid currentcolor outline with -2px offset.

**Transfer:** Keep navigation utility-sized; reserve serif language for the page story.

### Bright button

**Use:** Default high-visibility conversion action on white.

**CSS:** `background: #ebf212; color: #000000; border-radius: 8px; height: 48px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** Label is centered, regular weight. Compact navigation versions use 40px height, 16px side padding and caption type.

**States:** Declared: hover background-color rgb(252 255 168/1), color black; focus-visible unspecified; active background-color rgb(199 204 67/1), color black.

### Outline button

**Use:** Secondary conversion, exploration and provider sign-in.

**CSS:** `background: transparent; color: #000000; border: 1px solid #000000; border-radius: 8px; height: 48px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** Provider sign-in adds a small colored identity icon at left. Large closing actions use 56px height, 24px side padding and body-lg type.

**States:** Declared: hover background-color rgb(229 227 225/1), black border and text; focus-visible unspecified; active background-color rgb(204 201 198/1), black border and text.

### Dark button

**Use:** Conversion on luminous fields and high-emphasis closing forms.

**CSS:** `background: #000000; color: #ffffff; border-radius: 8px; height: 48px; padding: 0px 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** May span the width of a stacked email form. Sales-led endings use a 56px-high version with body-lg type; the recommended plan also uses this dark treatment.

**States:** Declared: hover background-color rgb(71 66 61/1); focus-visible unspecified; active background-color rgb(0 0 0/1).

### Conversion selector

**Use:** Switch between self-serve and sales-led intent above the opening form.

**CSS:** `display: flex; gap: 4px; padding: 4px; background: #edebe8; border-radius: 12px; max-width: 520px`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** Two equal-width rectangular tabs: selected dark charcoal with white text, unselected white with a faint edge. Each tab has 8px corners and 12px vertical, 20px horizontal padding.

**Transfer:** Use only when the visitor genuinely has two conversion routes.

### Email field

**Use:** Minimal friction conversion in openings and closing panels.

**CSS:** `height: 48px; background: #ffffff; border: 1px solid #94918e; border-radius: 8px; display: flex; align-items: center`

**Text style:** `body` — abcDiatype 400 · 16px/1.3

**Observed:** Opening form places this beside the Bright button with a 16px gap. The closing version stacks it above the Dark button. Input text has 12px horizontal inset; provider alternatives follow a thin divided 'or' row.

**Transfer:** Keep visible form complexity to one field when the conversion allows it.

### Feature card

**Use:** Compact reasons-to-believe in a four-column band.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 24px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `card-title` — abcDiatype 400 · 24px/1.2 · tracking -0.01em

**Observed:** Icon above a regular sans-serif title; short body paragraph follows with an 8px text gap. White cards sit on Warm paper band; the reversed variant uses warm cards on white.

**Transfer:** Use concise operational benefits with distinct icons rather than repeating the same claim.

### Testimonial card

**Use:** Readable customer proof with human attribution.

**CSS:** `background: #f7f5f2; border-radius: 12px; overflow: hidden; min-height: 368px; display: flex`

**Text style:** `card-title` — abcDiatype 400 · 24px/1.2 · tracking -0.01em

**Observed:** A 745px-wide main card uses 40px inner padding. Quote above, portrait and identity at lower left; an outcome number can sit lower right. Carousel shows a partial next card with 12px separation and small outlined arrow controls below.

**Transfer:** Keep quotations readable and preserve the partial-next-card cue rather than shrinking several quotes into tiny tiles.

### Accordion row

**Use:** Objection handling without a grid of boxed cards.

**CSS:** `border-bottom: 1px solid #ccc9c6; border-radius: 0px`

**Text style:** `card-title` — abcDiatype 400 · 24px/1.2 · tracking -0.01em

**Observed:** Full-width question trigger uses 24px vertical padding and a plus or minus at far right. The open answer appears directly beneath in support-colored body text. Desktop question column is 622px wide beside a large serif title.

**Transfer:** Write direct practical questions; allow answers to determine expanded height.

### Footer directory

**Use:** Dense but organized ending after conversion or FAQ.

**CSS:** `background: #ccc9c6; color: #1a1a1a`

**Text style:** `caption` — abcDiatype 400 · 14px/1.3

**Observed:** Oversized black abstract brand symbol anchors the left column; copyright and muted legal links follow. Narrow link columns occupy the right, with grouped headings and an additional row of resource, company and social destinations. Small square assistant links and a compact outlined utility action complete the directory. Content has 136px top and bottom breathing room.

**Transfer:** Give the new brand's own symbol comparable visual presence. If it lacks a standalone symbol, use a bold typographic monogram; retain the generous blank space around it.

### Recommended plan card

**Only for:** pricing pages

**Use:** One visibly preferred option in a flat four-tier matrix.

**CSS:** `background: rgba(254,255,217,0.2); border: 1px solid #c7cc43; border-radius: 12px; padding: 18px; display: flex; flex-direction: column`

**Text style:** `card-title` — abcDiatype 400 · 24px/1.2 · tracking -0.01em

**Observed:** Compact category marker first, then tier title, short description, 40px serif price, billing terms, allowance, purchase action, trial text and a long feature list. The preferred tier uses a Dark button while adjacent purchase actions remain yellow.

**Transfer:** Keep vertically comparable content aligned across tiers; use the subtle outline rather than enlarging the preferred tier.

## Imagery and graphics

### Isolated interface scenes

**Use:** Alternating product chapters and wide demonstrations.

**Observed:** White application panels float on pale warm-gray square grounds. Usually one main card or window is large enough to read its purpose, with background rows faded away and a detail popover in front. Thin pastel ribbons or electric-yellow strips peek from behind the card. The image occupies roughly half the content width; text stays outside it.

**Transfer:** Create a simplified but credible view of the new product's core operation, with real labels and a single focal interaction. Without a UI, build two or three connected information cards with a meaningful state change.

**Build:** Use a roughly 602px square pale backing with 8px corners. Center a white main panel occupying about 70–85% of the square; layer one smaller popover above it. Place a 12–24px Luminous color field ribbon behind the upper or lower edge. Fade nonessential rows with a white alpha gradient; keep the selected control yellow and readable.

### Liquid solar fields

**Use:** Signature energetic artwork for conversion, media edging and editorial thumbnails.

**Observed:** Intense yellow dominates broad regions; pastel cyan, mint, pink and lilac flow around it in irregular contours. Some fields look softly blurred, others have fine grain at color boundaries. They are flat luminous color, not metallic 3D or conventional rainbow stripes.

**Transfer:** Use the Luminous color field surface as the minimum acceptable treatment. Preserve this color energy even without custom artwork.

**Build:** Layer a yellow base with several oversized elliptical cyan, lilac and pink alpha gradients. Make the colored lobes overlap unevenly near corners and the lower edge; use 20–45px blur on separate absolutely positioned layers. For a richer version, displace the flattened SVG with low-frequency turbulence and add a very faint noise overlay. Keep the main text zone broadly yellow or place a white inset over it.

### Connected-system sketch

**Use:** Explain how a complex product's parts reinforce one another.

**Observed:** Three tall white rounded cards sit nearly touching on warm paper. Serif titles and centered short descriptions top each; small black-outline conceptual illustrations with yellow details occupy the middle; pale rectangular labels sit at the bottom. Dashed rounded looping paths and small arrowheads surround the cards.

**Transfer:** Explain the new product's own functional relationships, not a generic list of features. A minimum version uses simple line icons and directional loops.

**Build:** Draw an SVG loop behind three equal cards in a 2:1 stage. Use a 1px muted dashed stroke and rounded path turns. Add small open arrowheads along upper and lower runs. Put simple monochrome line drawings inside each card and fill one small area yellow; avoid fully colored cartoon scenes.

### Portrait proof

**Use:** Proof galleries and testimonial attributions.

**Observed:** Small square or upright portraits, natural color, often over a pale neutral or luminous yellow backing. These support the quote or stat rather than becoming full-bleed lifestyle photography.

**Transfer:** Use genuine attribution portraits with modest rounded corners and restrained framing.

### Human and interface collage

**Only for:** audience-specific openings

**Use:** Sales-led or role-specific hero visual.

**Observed:** A large warmly lit cutout portrait sits inside a pale sage-stone square. Small white status widgets hover at opposing corners, a yellow icon tile sits above, and a short luminous color rectangle peeks behind the person. The portrait remains natural rather than heavily color-graded.

**Transfer:** Use a relevant person in comfortable professional clothing with a warm, candid expression; pair with actual product states rather than decorative fake charts.

### Editorial thumbnail cards

**Only for:** resource sections

**Use:** Related learning content on warm paper.

**Observed:** Four 302×201px thumbnails use the same fluid color art, sparse dark symbols or short media labels, and small play controls where relevant. Uppercase mono category below, then a multiline 24px sans title.

**Transfer:** Create a consistent family of color-field thumbnails; vary the contour and one simple symbol rather than introducing an unrelated illustration style.

### Icons

**Observed:** Small monochrome utility symbols, generally 18px in benefit rows, 16px beside actions and 32px above feature-card titles. Visible forms are lightweight and outline-like; provider and integration identities retain their own marks. Accordion plus/minus and carousel arrows are understated.

**Transfer:** Choose compact, simple utility icons with comparable optical weight. Keep benefit icons in support ink and align them to the first text line; do not use large multicolor icon badges.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and conversion opening

**Observed:** A 72px Stone-surround Navigation sits above a white rounded sheet with 24px side gutters. After 80px top padding, a centered 72px serif headline spans roughly two thirds of the width in two compact lines, capped at 848px. A 520px-wide body support line follows 24px below. The Conversion selector, reassurance, Email field with Bright button, provider Outline buttons and small consent line make a narrow vertical conversion stack. The background remains white and unobstructed. After 80px separation, a broad 1284×642px rounded media stage introduces luminous color. Within the first 900px the full headline, support, conversion stack and only the top of this main object are visible; most of the demonstration and all logo proof continue below the fold.

**Transfer:** Keep the centered promise and practical conversion stack as the default marketing composition. Use a real product scene or a connected-card visual in the wide stage. Product-specific openings simplify to two actions and a broad demonstration; audience-specific openings become a 64px left-aligned headline, one-field demo form and square human/interface collage at right. Pricing opens with a left headline, right support and billing switch above tiers.

**Avoid:** Do not put a full-height dashboard behind the headline, replace the main serif with bold sans, or compress the demonstration so everything fits above the fold.

**Text style:** `display` — seasonMix 550 · 72px/1 · tracking -0.01em

### Capability split

**Observed:** Square Isolated interface scenes alternate left and right beside 560px-max text. A 40px serif heading and paragraph sit near the top of the text column; the benefit rows and Outline button sit low, with deliberate open space between. Use a 78px column gap, 48px vertical text inset and about 120px separation between chapters. Audience and product variants add a 12px mono eyebrow.

**Transfer:** Choose a single user outcome per chapter and show one operation that makes it credible; alternate direction without alternating visual language.

**Text style:** `chapter-heading` — seasonMix 550 · 40px/1.1 · tracking -0.01em

### Centered heading pair and feature grid

**Observed:** A 630px centered introduction pairs uppercase mono annotation, 48px or 56px serif heading and compact body support. Below a 40px gap, four Feature cards form a 24px-gutter row. Warm paper band contrasts with the white cards.

**Transfer:** Use to condense reasons-to-believe after deeper product chapters, not to replace every chapter with a card grid.

**Text style:** `heading` — seasonMix 550 · 48px/1.1 · tracking -0.01em

### System explanation

**Observed:** A Warm paper band inset inside the sheet holds a 56px centered headline, short support and Connected-system sketch. The wide 1136×568px diagram stage follows 40px below. Card titles use diagram-title; their diagrams and tags are subordinate to the system relationships.

**Transfer:** Use the product's own feedback loop or connected stages. Keep the editorial framing and lightly technical diagram rather than prescribing a particular number of business layers.

**Text style:** `heading-lg` — seasonMix 550 · 56px/1.05 · tracking -0.01em

### Monumental proof spread

**Observed:** A 48px serif heading and short proof statement occupy the left third; an enormous 290px deep-plum numeral dominates the remaining width. Below, a four-column human proof gallery uses 12px uppercase role captions, small portraits, 24px names and muted 14px attribution. Thin vertical separators maintain order.

**Transfer:** Use a verified metric, or a short truthful outcome in the same oversized serif treatment. Preserve the contrast between colossal proof and small editorial annotations.

**Text style:** `monumental-proof` — seasonMix 550 · 290px/0.6 · tracking -0.9px

### Quote carousel

**Observed:** A narrow 48px serif proof heading and supporting paragraph sit left with an Outline button near the bottom. Testimonial cards occupy the wider right region; a partial next card runs beyond the content edge. Small square previous/next controls sit below at right. Quantified variants use outcome-number with a smaller suffix and mono descriptor.

**Transfer:** Use fewer, larger quotations with credible attribution. Keep the carousel's horizontal stage independent of the normal content grid.

**Text style:** `heading` — seasonMix 550 · 48px/1.1 · tracking -0.01em

### FAQ split

**Observed:** A 56px serif heading at left faces a 622px question column of Accordion rows at right. Warm paper band is the usual background, with 40px vertical padding and 54px horizontal inset; pricing uses a white variant. Questions are 24px sans and answers use body or compact caption text.

**Transfer:** Answer practical adoption, integration, cost and trust concerns with the same matter-of-fact tone.

**Text style:** `heading-lg` — seasonMix 550 · 56px/1.05 · tracking -0.01em

### Luminous closing conversion

**Observed:** After the main white sheet ends, a separate 12px-rounded Luminous color field panel appears against Stone surround with a 24px gap. A left-aligned 64px serif closing line spans several lines above short support. The default self-serve variant uses a narrow stacked Email field, Dark button and provider alternatives, leaving the right half as color. Sales-led variants use one or two 56px actions instead. A product variant puts the copy and actions on an inset white panel with a thick luminous frame.

**Transfer:** Make the ending a vivid renewed promise, not a dark repeated hero. Use a full fluid field for short conversion copy or the white inset when more legibility is needed; follow with Footer directory.

**Text style:** `heading-xl` — seasonMix 550 · 64px/1.05 · tracking -0.01em

### Pricing matrix and usage explainer

**Only for:** pricing pages

**Observed:** Four flat tier columns sit under a 64px serif title and a compact billing switch. Recommended plan card is lightly tinted and outlined. Add-on panels follow in two columns. A warm recommendation band precedes a long comparison table with fine #edebe8 rules and warm rounded category headers. A later usage explainer places a bright coin-like line drawing and dashed connectors between a left introduction and right stacked cost rows. Proof and a long FAQ lead directly to Footer directory without a separate luminous closing panel.

**Transfer:** Keep commercial information more compact and aligned than narrative landing pages. Use transparent usage explanations and a single preferred plan; reserve pill shapes for the billing switch.

**Text style:** `heading-xl` — seasonMix 550 · 64px/1.05 · tracking -0.01em

## Page flow

**Storyline:** Promise → demonstration → credibility → capability chapters → system explanation or adoption support → human and quantified proof → objections → renewed conversion or practical directory.

### Broad platform marketing landing page

1. **promise** — Centered editorial headline and dual-route conversion stack.
2. **product demonstration** — Wide luminous media stage followed by a compact logo strip.
3. **capability chapters** — Alternating square interface scenes and outcome-led text.
4. **system explanation** — Connected-card diagram followed by a four-card reasons band.
5. **adoption confidence** — Split practical controls, trust statements and compact certification marks.
6. **quantified proof** — Monumental plum numeral with human proof gallery.
7. **closing call** — Full luminous signup panel followed by stone directory.

**Transfer:** Tell the whole product story while changing scale between scene, diagram, proof and conversion.

### Sales-led landing page for larger buyers

1. **promise** — Left editorial headline and email demo form opposite a portrait/UI collage.
2. **social proof** — Logo strip and a centered value introduction with four cards.
3. **trust** — Security introduction and small certification tiles.
4. **capability chapters** — Alternating contextual UI chapters.
5. **adoption support** — White service panel inside a luminous frame, then integration-mark tiles.
6. **proof and objections** — Quote carousel followed by a warm split FAQ.
7. **closing call** — Fluid color panel with one dark sales action, then stone directory.

**Transfer:** Increase organizational confidence and explain rollout without abandoning the light editorial style.

### Commercial selection and detailed comparison

1. **pricing** — Split headline and billing control, then four aligned tiers.
2. **expansion** — Two subtle add-on panels.
3. **guided choice** — Centered recommendation band and compact customer logos.
4. **comparison** — Long category-grouped matrix with repeated tier actions.
5. **cost explanation** — Usage mechanism drawing with connected cost rows.
6. **proof** — Large quote cards and outcome numbers.
7. **objection handling** — Extended FAQ leading directly to the shared stone directory.

**Transfer:** Prioritize comparison and transparent costs; do not append a conversion mural simply because narrative pages use one.

### Product landing page for a capability with several environments

1. **promise** — Centered 72px title, compact support, two actions and wide demonstration montage.
2. **social proof** — Mono-captioned logo strip.
3. **capability chapters** — Alternating square demonstrations for distinct usage contexts.
4. **proof** — Large quote carousel.
5. **education** — Four resource thumbnails on warm paper.
6. **objection handling** — Compact split FAQ.
7. **closing call** — White conversion inset inside a luminous frame, then stone directory.

**Transfer:** Explain where a capability works and what changes for the user; keep technical environments as distinct chapters.

### Audience-specific solution landing page

1. **promise** — Role annotation, 64px left headline and demo form opposite a human/interface collage.
2. **credibility** — Logo strip and compact benefit cards.
3. **capability chapters** — A small sequence of alternating scenes connecting foundation, creation and execution outcomes.
4. **compatibility** — Centered reassurance and row of integration tiles.
5. **proof** — Human quote carousel with a narrow introductory column.
6. **objection handling** — Warm split FAQ.
7. **closing call** — Broad fluid-yellow panel with dark and outlined actions, then stone directory.

**Transfer:** Lead with a role's operational friction, then show relief through specific product behavior.

## Writing

Confident and conversational, translating complex infrastructure into everyday operational relief. Claims sound practical and direct, with occasional lightly pointed contrasts rather than breathless futurism.

**Do not copy:** Do not reuse Apollo names, marks, proprietary layer names, customer logos, testimonial wording, prices, database counts, adoption totals or performance claims. Source examples illustrate cadence only; replace every factual claim with substantiated information about the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your team'. Name the product as the active helper, while the user remains in control.
- **Rhythm:** Headlines often run 5–12 words with one clear verb or contrast. Supporting paragraphs are one or two short sentences. Paired fragments and short declarative sentences create momentum without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A concrete desirable result made simpler by one connected product. | 7–12 words | “Grow revenue with one connected GTM system”<br>“Build a GTM engine that doesn't need babysitting” |
| Capability heading | Start with a verb; name the work or frustration rather than the feature category. | 5–11 words | “Give every team the same source of truth”<br>“Let AI handle the busywork” |
| Supporting line | Explain compatibility or practical impact in plain language, followed by reassurance. | 20–35 words | “Keep the tools you love. Connect the data behind them. Build better pipeline while [Brand] handles the rest.” |
| Section contrast | Brief paired statements replace an abstract superiority claim. | 5–12 words | “Generic AI talks about pipeline. [Brand]’s AI runs it, and gets smarter as you grow.”<br>“Don’t change your workflow. Just add [Brand].” |
| Action | Literal verb plus destination or immediate next step. | 2–5 words | “Sign up for free”<br>“Explore integrations”<br>“Talk to sales” |
| Closing line | Restate the transformation as a decisive shift from friction to a better way. | 8–16 words | “Stop working around your tools. Start building with them.” |

**Words and phrasing to use:** connected; works where you work; your team; build; run; trust; in sync; without switching; ready to get started

**Avoid:** revolutionary; game-changing; unlock limitless potential; synergize; disrupt everything; unqualified best-in-class claims

**Rules:**

- Pair each broad promise with a concrete operation or observable outcome.
- Use technical terms where they identify a real workflow; explain their consequence immediately.
- Use everyday friction words such as 'busywork' beside precise capability terms.
- Use proof numbers sparingly and give them a clear noun or descriptor.
- Keep benefit rows short enough to scan as one idea, not miniature paragraphs.

## Do's and Don'ts

### Do

- Keep the main desktop opening at 72px/1 and -0.01em tracking, with a support column capped at 520px.
- Maintain the 24px stone outer gutter independently of the 54px white-sheet content inset.
- Use 8px corners for buttons and 12px for large proof cards and closing panels.
- Stage one meaningful interface operation on a roughly 602px square backing.
- Separate capability chapters by about 120px rather than enclosing them in individual bordered boxes.
- Let the luminous color device appear as a broad conversion field or a visible media ribbon while most reading surfaces stay white or warm paper.
- Pair monumental proof with 12px mono annotation and human attribution.
- Use 24px card padding and 24px four-column grid gaps.

### Don't

- Do not turn the whole site into a dark dashboard; black fills belong primarily to controls and selected product demonstrations.
- Do not replace the regular 24px sans card titles with heavy bold headings.
- Do not apply pill corners to ordinary actions; the capsule treatment belongs to compact billing controls and small reassurance tags.
- Do not add drop shadows to the marketing card system; flat surface contrast carries its hierarchy.
- Do not color every section heading yellow or plum; core headings stay black.
- Do not fill every square product stage with a full dense application view; isolate the operation and fade secondary context.
- Do not scatter 290px numbers throughout the page; keep that extreme scale for a concentrated proof moment.
- Do not treat resource thumbnails as a new photographic art direction; they share the fluid color family.

## Motion and responsive

### Motion

**Observed:**

- Actions declare all 0.15s cubic-bezier(0.4, 0, 0.2, 1) transitions.
- Some icon links declare opacity 0.2s cubic-bezier(0.4, 0, 0.2, 1) with hover opacity 0.8.
- Comparison category controls declare min-height and background-color transitions at 150ms cubic-bezier(0.4, 0, 0.2, 1).

**Transfer:**

- Keep interaction feedback brief and surface-based: yellow lightens, outlined controls gain a stone fill, dark actions soften to warm support ink.
- Preserve explicit carousel arrows alongside horizontally staged proof rather than relying on animation to reveal content.

**Unknown:**

- Autoplay behavior, scroll reveal choreography, liquid-art movement and exact media playback timing are not established.

### Responsive

**Observed:**

- Declared stylesheet breakpoints include 375px, 640px, 768px, 1023px, 1024px, 1250px, 1280px, 1440px, 1536px and 1920px.
- The opening heading classes specify 44px base, 56px tablet, 64px smaller desktop and 72px desktop sizing.
- Feature-grid declarations use two columns at tablet and four at smaller desktop; capability structures declare stacked alternatives.
- Navigation declares 56px base height, 64px tablet and 72px desktop; the wide category menu is hidden below smaller desktop.

**Transfer:**

- For narrow layouts, preserve the sequence of promise, action and product object; stack capability text and square scenes while retaining the luminous edging.
- Reduce the enormous proof display before it collides with its heading; keep the numeral and its annotation as one unit.
- Reflow feature summaries to two then one column, while retaining the distinction between white cards and warm bands.

**Unknown:**

- Exact mobile compositions, pricing-table overflow behavior and narrow-screen closing-art framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
