# Savee — taste between the words

## Overview

A gallery-minded marketing style with oversized, tightly fitted grotesk headlines and small images tucked directly into the language. Pale gray and near-white surroundings give vivid photography, graphic design and product demonstrations almost exclusive ownership of color. The feeling is cultured but approachable, with airy pacing, soft rounded containers and practical, conversational copy; a black technical variant carries the same visual sensibility into installation-led products.

### Essentials

- Headlines behave like image-bearing sentences: the default opening uses 95.8px medium sans, line height 1 and -0.035em tracking, interrupted by three roughly 87px rounded picture tokens. Carry this device into every new landing page, using original output details or photographed objects if there is no image library.
- The first screen is a promise, not a dashboard: a centered two-line headline in a 1280px envelope, one 21px support line, then two 56px pill actions separated by 12px; only the beginning of the broad image wall enters the first 900px.
- Color belongs to the work rather than the chrome: the page, text, buttons and cards remain neutral, with saturated color confined to bounded pictures and demonstrations. Most of the first screen remains pale gray; later image-led sections can give media half or more of their area.
- Actions look like small black pebbles: #050505 fills, #fdfdfd text, 9999px radius and 20px 40px padding; the secondary action is a solid #dadada pill rather than an accent-colored outline.
- A collectible-image field is part of the identity: staggered five-column media with 16px gaps and 12px corners, or a horizontal reference strip with 16px corners. Use varied original artifacts or carefully art-directed output studies when the product lacks photographic content.
- Editorial sentences alternate with soft exhibition plinths: 64.8px/1.05 section heads, occasional #a3a3a3 phrases at identical size, and #fdfdfd cards with 32px corners on #f3f3f3. Keep this large-type-to-contained-proof contrast even when the narrative order changes.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#050505` | `--color-ink` | text, action, background | Primary light-theme headlines and buttons; also the full canvas of the dark technical variant. |
| Body charcoal | `#404040` | `--color-body` | text, border | Default support copy and navigation; dark-theme outlined details. |
| Link charcoal | `#464646` | `--color-secondary` | text | Secondary-action labels, footer links and feature-catalog headings. |
| Caption gray | `#787878` | `--color-caption` | text | Footer category labels and low-emphasis light-theme metadata. |
| Muted gray | `#a3a3a3` | `--color-muted` | text | Same-size secondary headline phrases, plan descriptions and subdued technical copy. |
| Light edge | `#dadada` | `--color-edge` | border, action | Footer and header hairlines, dividers, and solid secondary buttons. |
| Media bed | `#e4e4e4` | `--color-media-bed` | surface, border | Underlying media surfaces and faint closing-panel edges; it is not a replacement for actual imagery. |
| Demo backing | `#eeeeee` | `--color-demo-bed` | surface | Light backing beneath contained product video. |
| Gallery gray | `#f3f3f3` | `--color-canvas` | background | Default marketing canvas. |
| Near-white | `#fdfdfd` | `--color-paper` | surface, text, background | Raised cards, reversed button text and the pure-light creation-product canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| profile availability demonstrations | Availability green | `#22c55e` | `--color-availability` | accent | An 8px status dot inside a profile availability badge; not a general marketing highlight. |
| dark technical landing pages | Dark panel | `#151515` | `--color-dark-panel` | surface | FAQ and video panels, and the source hue of the 90% dark closing panel. |
| dark technical landing pages | Dark raised | `#1e1e1e` | `--color-dark-raised` | surface, border | Command blocks, selected tool tiles, closing-panel edges and the source hue of 40% prompt cards. |
| dark technical landing pages | Dark rule | `#2f2f2f` | `--color-dark-rule` | border, surface | Prompt-card borders, technical separators and copy-action fills. |
| feature catalogs | Feature explanation | `#5f5f5f` | `--color-feature-body` | text | Larger explanatory paragraphs beside feature demonstrations. |
| dark technical landing pages | Dark-theme muted | `#737373` | `--color-dark-muted` | text | Hero explanation, helper text and footer labels. |
| dark technical landing pages | Dark-theme body | `#d4d4d4` | `--color-dark-body` | text | Prompt cards and technical body text. |
| dark technical landing pages | Dark-theme heading | `#e5e5e5` | `--color-dark-heading` | text, border | Section headings, command text and selected tool edges. |
| dark technical landing pages | Dark-theme display | `#fafafa` | `--color-dark-display` | text | Hero heading and closing sentence. |

## Typography

- **saveeFont** — All marketing prose, navigation, headings and actions. Compact contemporary grotesk with open counters, a generous x-height and closely fitted lowercase; medium weights feel assertive without becoming heavy. OpenType features: "calt", "cv01", "liga", "ss07". If unavailable, use **Inter**. Use 400–600 and retain the role-specific tracking; rebalance line breaks around inline images. Font stack: "saveeFont", "Inter", "saveeFont Fallback", sans-serif.
- **ui-monospace** (only for technical setup content) — Executable commands and API method names. Conventional system monospace, functional rather than decorative. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | saveeFont | 500 | 95.8px | 1 | -0.035em | size clamp(45.6px, 6.65vw, 129.6px) | Default image-interrupted hero sentence. |
| heading | saveeFont | 500 | 64.8px | 1.05 | -0.025em | size clamp(36px, 4.5vw, 72px) | Main marketing section headings, centered or in a split composition. |
| price | saveeFont | 500 | 48px | 1 | -0.025em | fixed | Plan prices with a smaller baseline-aligned unit. |
| quote | saveeFont | 500 | 37.4px | 1.15 | -0.0043em | size clamp(24px, 2.6vw, 40px) | Large testimonial inside a raised white panel. |
| lead | saveeFont | 400 | 21px | 1.375 | -0.03em | fixed | Hero support and section introductions. |
| card-heading | saveeFont | 500 | 21px | 27px | -0.03em | fixed | Benefit names and card titles. |
| search-query | saveeFont | 500 | 18px | 24px | -0.025em | fixed | Short demonstration query inside the floating white search pill. |
| body | saveeFont | 400 | 16px | 1.625 | -0.01em | fixed | Explanatory text beneath benefit headings. |
| compact | saveeFont | 400 | 16px | 1.375 | -0.01em | fixed | Footer navigation and compact supporting prose. |
| nav | saveeFont | 500 | 16px | 1.375 | -0.01em | fixed | Primary navigation and emphasized short links. |
| button | saveeFont | 500 | 16px | 1 | -0.01em | fixed | Default primary action. |
| button-secondary | saveeFont | 400 | 16px | 1 | -0.01em | fixed | Secondary pill action. |
| button-small | saveeFont | 500 | 14px | 1 | -0.01em | fixed | Compact header action. |
| caption | saveeFont | 400 | 14px | 20px | normal | fixed | Plan descriptors, units and inclusion notes. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| feature catalogs and dark technical landing pages | catalog-display | saveeFont | 500 | 80px | 1.05 | -0.035em | size clamp(34px, 6vw, 80px) | Short centered catalog hero or technical product promise. |
| feature catalogs | catalog-heading | saveeFont | 500 | 60px | 1 | -0.025em | fixed | Feature chapters beside media. |
| creation-product pages | creation-heading | saveeFont | 600 | 60px | 1 | -0.025em | fixed | Compact product hero and major capability titles. |
| feature catalogs and dark technical landing pages | closing-sentence | saveeFont | 500 | 60px | 1 | -0.055em | fixed | Single compressed conversion sentence in a broad rounded panel. |
| dark technical landing pages | technical-heading | saveeFont | 500 | 48px | 1 | -0.035em | fixed | Capability, installation and prompt-section headings. |
| dark technical landing pages | faq-heading | saveeFont | 600 | 48px | 1 | -0.025em | fixed | FAQ section title. |
| creation-product pages | step-heading | saveeFont | 600 | 36px | 40px | -0.05em | fixed | Two illustrated setup steps. |
| feature catalogs | catalog-lead | saveeFont | 400 | 24px | 1.25 | -0.03em | fixed | Larger descriptions beside catalog demonstrations. |
| dark technical landing pages | technical-lead | saveeFont | 400 | 24px | 1.375 | -0.0067em | size clamp(16px, 1.9vw, 24px) | Centered technical hero explanation. |
| dark technical landing pages | question | saveeFont | 500 | 18px | 24px | -0.015em | fixed | Accordion question text. |
| technical setup content | command | ui-monospace | 400 | 13px | 1.625 | -0.012em | fixed | Copyable installation commands. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium 500 is the default display weight. The 600 creation-product and FAQ variants should not make every headline bolder.
- Tracking tightens from -0.01em in compact copy to -0.025em in section headings and -0.035em in the hero. The conversion-panel sentence is unusually compressed at -0.055em.
- Secondary phrases change color, not size or weight. Keep them inside the same typographic sentence.
- Use sentence case, not a system of uppercase section labels; small technical table labels are a separate utilitarian treatment.

## Layout

**Density:** Airy at section level, closely fitted within the image collections; long stretches of neutral canvas separate substantial proof objects.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Tight footer-list and price-unit spacing. |
| 12px | Action-pair gaps and benefit title-to-copy gaps. |
| 16px | Image-wall gutters and compact media separation. |
| 20px | Button vertical padding and technical example-card padding. |
| 24px | Section heading-to-support gap. |
| 32px | Card-grid and footer-column gaps. |
| 40px | Standard feature-card and pricing-card inner padding. |
| 48px | Hero support-to-actions spacing and technical heading-to-content spacing. |
| 56px | Testimonial vertical padding and search-pill top separation. |
| 64px | Split-feature gutter, major demo separation and testimonial side padding. |
| 96px | Technical chapter bottom padding. |
| 128px | Catalog chapter spacing and post-pricing breathing room. |
| 160px | Default marketing chapter separation. |

### Containers and grids

- **outer-envelope**: max width 1600px · side padding 33px. Broad media fields, header and footer; centered with narrow page-edge breathing room.
- **hero-envelope**: max width 1280px. Wide centered headline envelope, with inline pictures counted as words.
- **main-container**: max width 1152px. Standard demos, large quote panel and commercial card grids.
- **heading-container**: max width 896px. Centered section headings and technical hero explanation.
- **support-container**: max width 768px. Support copy kept narrower than its headline.
- **split-feature**: max width 1152px · 2 columns · gap 64px. Equal text and portrait-video columns, vertically centered.
- **pricing-grid**: max width 1152px · 3 columns · gap 32px. Equal-height cards with aligned bottom actions.
- **image-wall**: max width 1600px · 5 columns · gap 16px. Staggered columns of variable-height image tiles.
- **footer-grid**: max width 1600px · 5 columns · gap 32px. Brand statement in the first column and four compact link categories.
- **technical-column** (only for dark technical landing pages): max width 768px. Numbered setup with command blocks.
- **prompt-grid** (only for dark technical landing pages): max width 1024px · 3 columns · gap 16px. Short examples in a dense three-by-three field.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | cards | 32px |
|  | gallery-tiles | 12px |
|  | reference-strip | 16px |
|  | portrait-demo | 24px |
|  | inline-picture | 17.2px |
| feature catalogs and dark technical landing pages | conversion-panel | 40px |
| dark technical landing pages | faq | 20px |
| technical setup content | commands | 14px |
| dark technical landing pages | prompt-card | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card | `0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)` | White commercial and capability cards. |
| testimonial | `0px 32px 80px -16px rgba(0,0,0,0.1)` | Wide quote plinth. |
| floating-search | `0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)` | Search demonstration pill and layered portfolio previews. |
| inline-picture | `0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)` | Small pictures embedded in headline text. |

### Surfaces

#### Gallery canvas · level 0

**Use:** Default light marketing ground.

**CSS:** `background: #f3f3f3; color: #404040`

**Observed:** A continuous pale ground rather than alternating colored bands.

**Transfer:** Let images supply the chromatic changes.

#### White plinth · level 1

**Use:** Commercial cards and grouped capability proofs.

**CSS:** `background: #fdfdfd; border-radius: 32px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** No visible hard outline; the white-to-gray contrast and low soft shadow define the object.

**Transfer:** Use for meaningful content groups, not every paragraph.

#### Light navigation glass · level 2

**Use:** Scrolled header backing.

**CSS:** `background: rgba(253,253,253,0.8); border-bottom: 1px solid #dadada; backdrop-filter: blur(24px)`

**Observed:** The opening header is visually almost unbacked; after scrolling a subtle translucent band separates it from media.

**Transfer:** Keep the text and controls crisp above the blur.

#### Creation canvas · level 0

**Only for:** creation-product pages

**Use:** Brighter canvas for template and editor stories.

**CSS:** `background: #fdfdfd; color: #404040`

#### Technical canvas · level 0

**Only for:** dark technical landing pages

**Use:** Black product and installation story.

**CSS:** `background: #050505; color: #d4d4d4`

#### Technical panel · level 1

**Only for:** dark technical landing pages

**Use:** Contained video and FAQ blocks.

**CSS:** `background: #151515; border-radius: 20px`

**Observed:** Near-black on black, without a conspicuous elevation shadow.

**Transfer:** Distinguish through small luminance steps rather than colored panels.

#### Conversion enclosure · level 1

**Only for:** feature catalogs and dark technical landing pages

**Use:** Broad self-contained closing invitation.

**CSS:** `background: rgba(238,238,238,0.9); border: 1px solid #e4e4e4; border-radius: 40px; padding: 80px 32px; min-height: 440px`

**Observed:** Light version is a barely darker gray than the canvas. The dark version uses rgba(21,21,21,0.9) on black with a #1e1e1e edge and a white action.

**Transfer:** Keep the border and fill close enough that the oversized rounded silhouette does most of the work.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #050505; color: #fdfdfd; border-radius: 9999px; padding: 20px 40px; height: 56px`

**Text style:** `button` — saveeFont 500 · 16px/1 · tracking -0.01em

**Observed:** Content-sized, centered label without an arrow. Technical dark-theme actions reverse to near-white fill and dark text; header actions are a smaller size.

**Transfer:** Use a direct verb and the new product's immediate next step.

### Secondary button

**Use:** Alternative commercial route next to the main action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #dadada; color: #464646; border-radius: 9999px; padding: 20px 40px; height: 56px`

**Text style:** `button-secondary` — saveeFont 400 · 16px/1 · tracking -0.01em

**Observed:** Sits beside the black action, not as an underlined text link. Technical dark variant is transparent with a 1.3px charcoal outline and pale text.

### Header action

**Use:** Compact signup in the fixed navigation.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #050505; color: #fdfdfd; border-radius: 9999px; padding: 16px 20px; height: 46px`

**Text style:** `button-small` — saveeFont 500 · 14px/1 · tracking -0.01em

**Observed:** Reinforces the main action after the reader scrolls; the opening keeps the header visually lighter.

### Navigation

**Use:** Persistent orientation without overwhelming the hero.

**CSS:** `display: flex; align-items: center; justify-content: space-between; max-width: 1600px; height: 64px; padding: 0px 33px`

**Text style:** `nav` — saveeFont 500 · 16px/1.375 · tracking -0.01em

**Observed:** Brand mark and three short links align left; small social icons, a fine divider, login and the compact action align right. The container sits in a fixed full-width layer.

**Transfer:** Use a similarly sparse product hierarchy, with links spaced 24px apart.

### Inline picture token

**Use:** Break a display sentence with tangible visual examples.

**CSS:** `display: block; overflow: hidden; background: #e4e4e4; border-radius: 17.2px; box-shadow: 0px 1px 3px rgba(0,0,0,0.1), 0px 1px 2px -1px rgba(0,0,0,0.1)`

**Observed:** Three small square object-cover pictures sit in the text flow, sized near 0.86 times the headline size, with slight differing rotations and a small side bearing. Each acts as a picture-swap button.

**Transfer:** Use original objects or outputs that can remain legible at roughly 87px.

### Pricing card

**Use:** Comparable commercial options.

**CSS:** `display: flex; flex-direction: column; background: #fdfdfd; border-radius: 32px; padding: 40px; box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Text style:** `card-heading` — saveeFont 500 · 21px/27px · tracking -0.03em

**Observed:** Title and optional small black popularity badge first, then muted audience descriptor, prominent price with baseline unit, billing note, checkmarked benefits and a bottom-aligned content-width Primary button. No plan gets a saturated background.

**Transfer:** Keep the strongest differentiation in concise content, not ornate card decoration.

### Search demonstration pill

**Use:** A tiny live-looking query above a horizontal output strip.

**CSS:** `display: flex; align-items: center; gap: 12px; max-width: 384px; min-height: 60px; padding: 0px 20px; background: #fdfdfd; border-radius: 9999px; box-shadow: 0px 20px 25px -5px rgba(0,0,0,0.1), 0px 8px 10px -6px rgba(0,0,0,0.1)`

**Text style:** `search-query` — saveeFont 500 · 18px/24px · tracking -0.025em

**Observed:** A muted 20px image-search icon precedes a short query with a typing-like presentation.

**Transfer:** Use a real example query from the new workflow; this is demonstration chrome, not the site's primary search navigation.

### Footer directory

**Use:** Shared low-key ending.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); gap: 32px; padding-top: 32px; max-width: 1600px`

**Text style:** `compact` — saveeFont 400 · 16px/1.375 · tracking -0.01em

**Observed:** Brand and short audience line occupy column one; four remaining categories use muted headings and darker stacked links. Beneath is a full-width hairline with download icons on the left, legal links and a human sign-off on the right. Light and dark versions keep the same structure.

### Floating technical navigation

**Only for:** dark technical landing pages

**Use:** Compact pill navigation above the black product story.

**CSS:** `display: flex; align-items: center; justify-content: space-between; max-width: 738px; height: 64px; padding: 0px 12px 0px 24px; background: rgba(82,82,82,0.3); border-radius: 9999px; backdrop-filter: blur(50px); box-shadow: 0px 18px 70px rgba(0,0,0,0.35)`

**Text style:** `nav` — saveeFont 500 · 16px/1.375 · tracking -0.01em

**Observed:** Centered within a 100px fixed header region; white compact action at the far right, active link brighter than the others.

### FAQ row

**Only for:** dark technical landing pages

**Use:** Objection handling in a narrow vertical stack.

**CSS:** `display: flex; flex-direction: column; background: #151515; border-radius: 20px; padding: 32px 24px; margin-bottom: 24px`

**Text style:** `question` — saveeFont 500 · 18px/24px · tracking -0.015em

**Observed:** Question aligned left, thin plus aligned right; closed rows are 88px tall. Expanded prose sits below with a 12px gap and muted color.

### Prompt card

**Only for:** dark technical landing pages

**Use:** Concrete examples of useful requests.

**CSS:** `background: rgba(30,30,30,0.4); border: 1px solid #2f2f2f; border-radius: 8px; padding: 20px; color: #d4d4d4`

**Text style:** `body` — saveeFont 400 · 16px/1.625 · tracking -0.01em

**Observed:** Nine plain quoted examples in a three-column grid; no illustrative icons or oversized titles.

### Command block

**Only for:** technical setup content

**Use:** Copyable implementation instruction.

**CSS:** `background: #1e1e1e; color: #e5e5e5; border-radius: 14px; padding: 24px 24px 64px 24px; overflow-x: auto; white-space: pre`

**Text style:** `command` — ui-monospace 400 · 13px/1.625 · tracking -0.012em

**Observed:** A compact Copy pill occupies the lower right; the generous bottom inset protects the command line. Numbered steps sit outside the block in 32px outlined circles.

## Imagery and graphics

### Collected-image wall

**Use:** Primary visual proof and the first large media field.

**Observed:** A deliberately eclectic mixture of editorial portraits, product still lifes, fashion, posters, interfaces and graphic experiments. Full-color images retain their own palettes; five staggered columns use roughly 262px widths, 16px gutters and 12px clipped corners. Images are edge-to-edge without captions, frames or color overlays.

**Transfer:** Curate a similarly varied set of original customer outputs, objects or artifact close-ups. If outputs are abstract, create genuinely differentiated editorial studies rather than repeating one interface mockup.

**Build:** Use a five-column grid of independent vertical flex columns with 16px gaps. Vary image aspect ratios and offset alternate columns by 64px. Clip the shared media region rather than forcing aligned row bottoms; preserve object-cover framing.

### Headline picture inserts

**Use:** Signature small-image interruptions in the opening sentence.

**Observed:** A dark portable device, a fashion portrait and a blue sculptural chair become small rounded collectibles at text scale. Their slight rotations make them feel placed, not bullet-point icons.

**Transfer:** Select three distinct, closely framed product-related details with clean silhouettes and different tonal weights. Minimum acceptable execution is three excellent still-image details, not generic line icons.

**Build:** Place three inline-block wrappers in the headline flow, each 0.86 times the font size with 0.06em side margins and a small downward baseline offset. Clip each inner image at 0.18 times the font size radius; add the Inline picture shadow and slight alternating rotations.

### Output reference strip

**Use:** Search and discovery demonstrations.

**Observed:** A wide row of tall editorial portraits beneath a tiny floating query, with 16px rounded corners and portions disappearing beyond both viewport edges. Media visually outweighs the short explanation above it.

**Transfer:** Show a coherent family of results responding to one visible request, rather than unrelated stock art.

**Build:** Create an overflow-clipped horizontal flex strip with 16px gaps, images at 320px high and varying natural widths. Center the Search demonstration pill above it with 56px separation from preceding support copy.

### Contained product cinema

**Use:** Capability chapters and shared-workflow proof.

**Observed:** Product videos combine dark interface grids and intensely colored creative work. A portrait version occupies a 544px by 680px rounded vessel beside text; a broad version is 1152px wide with 32px corners. They are product demonstrations, not browser windows decorated with fake operating-system controls.

**Transfer:** Record or compose a real, focused workflow using the new product. Where video is unavailable, use one carefully staged still with meaningful content.

### Technical reference cinema

**Only for:** dark technical landing pages

**Use:** The first major proof object below the hero.

**Observed:** A broad rounded collage of references sits against black, darkened enough for a translucent outlined monospace prompt to cross the middle. A very soft warm-neutral halo follows the media edges; no bright neon border or multicolor page gradient.

**Transfer:** Stage real outputs behind one concise instruction. Preserve the cinematic low-light treatment and restrained edge glow; exact glow stops are not essential.

**Build:** Use a 1152px-wide 16:9 media vessel with 20px clipping. Behind it duplicate the media into an absolute layer, enlarge slightly, blur about 70px and lower opacity to roughly 0.2. Add a black translucent scrim above the sharp media, then an inset translucent pale outline box containing a short white monospace prompt. Keep the ambient light close to the media.

### Layered template previews

**Only for:** creation-product pages and portfolio capability demonstrations

**Use:** Show the variety and editability of finished output.

**Observed:** Crisp full-page editorial website previews with oversized type, fashion imagery and occasional acid-yellow artwork. Broad horizontal template rows run past the page edge; a second treatment fans three previews with small rotations and soft shadows. Step thumbnails are much smaller, around 320px by 160px, and sit on the bare canvas.

**Transfer:** Show believable finished deliverables in varied layouts. Use contrasting content inside the previews while leaving the marketing canvas neutral.

**Build:** For the fan, overlap three landscape previews with restrained opposing rotations and a stronger central foreground preview; use 8px clipping and the Floating-search shadow. For the gallery, use 418px by 261px images with 40px gaps in an overflow-clipped horizontal row.

### Icons

**Observed:** Mostly solid monochrome SVGs: 16px utility icons, 18px download marks and larger 36px partner marks. Search and plus controls use simple thin outlines; search strokes are 2px with round caps. Small icons take body or muted text colors rather than accents.

**Transfer:** Choose a consistent compact monochrome set. Keep platform or partner marks recognizable and confined to proof or compatibility groups; use line icons only for simple interactive functions.

## Section recipes

How recurring sections are built.

### First screen: Sentence with collectibles opening

**Observed:** Gallery canvas behind a sparse 64px fixed Navigation. A wide two-line display sentence is centered in a 1280px envelope with substantial empty space above; its visible text begins roughly a third of the way down the first screen. Three Inline picture tokens participate in the sentence rather than float around it. The headline occupies about 192px of visible line height. A single Lead line follows after 48px, then Primary button and Secondary button after another 48px, with a 12px action gap. In the first 900px the reader sees navigation, the entire headline, support and actions, plus the tops of the staggered Collected-image wall beginning around 792px; most media proof lies below the fold. Layers are flat gray ground, text, inline pictures with tiny shadows, and solid actions—no hero backdrop illustration.

**Transfer:** Write one outcome-led sentence that can break into two balanced lines, then interrupt it with three original output or object details. When there is no image library, art-direct three tangible studies of the product's result and continue them into the image field below. Catalog pages instead open with a short 80px centered heading and broad visual grid; creation products use a 60px semibold promise above an overflowing template gallery; technical products use the dark variant, an 80px centered promise, white primary action, plan note and overlapping-avatar proof before the cinema.

**Avoid:** Do not replace this with a conventional text-left/dashboard-right hero, scatter decorative icons around the margins, or enlarge the three inserts into an unrelated floating collage.

**Text style:** `display` — saveeFont 500 · 95.8px/1 · tracking -0.035em

### Two-tone heading and image strip

**Observed:** Centered Heading with one phrase in muted gray at the same scale, followed by Lead support after 18px. Search demonstration pill sits above Output reference strip. The media can extend beyond the container while the prose stays narrow.

**Transfer:** Pair an old friction with a concise better outcome, then prove the distinction with visible results.

**Text style:** `heading` — saveeFont 500 · 64.8px/1.05 · tracking -0.025em

### Editorial split capability

**Observed:** Split-feature layout places left-aligned Heading, support after 24px and Primary button after 32px opposite a portrait Contained product cinema. Both columns share the vertical center. Small inclusion note and monochrome compatibility marks sit near the action.

**Transfer:** Use for a capability that deserves one rich proof object instead of a list.

**Text style:** `heading` — saveeFont 500 · 64.8px/1.05 · tracking -0.025em

### Raised proof chapters

**Observed:** Centered Heading and Lead precede two White plinth cards. Text occupies the top of each card, with substantial media entering below; some illustrations are clipped by the card edge. A separate wide quote uses 56px 64px padding, Quote typography and author identity beneath, followed by small pagination dots.

**Transfer:** Alternate broad visual demonstrations with a small number of substantial proof objects. Use the quote panel for a real endorsement or a clearly attributed editorial insight.

**Text style:** `quote` — saveeFont 500 · 37.4px/1.15 · tracking -0.0043em

### Broad demo with benefit footnotes

**Observed:** Centered Heading, support at 24px and Primary button precede a 1152px-wide rounded video after 64px. Four compact benefit columns below use Card-heading and Body recipes, with 40px gutters.

**Transfer:** Let one credible workflow carry the chapter; use the lower columns to explain what the reader just saw.

**Text style:** `heading` — saveeFont 500 · 64.8px/1.05 · tracking -0.025em

### Neutral commercial close

**Observed:** Two-tone Heading and Lead introduce three Pricing cards with a 64px grid offset. Each card shares the same near-white surface and black action. Price is 48px, with a smaller unit aligned to its baseline; a plain comparison link sits 80px below. A 128px breathing interval leads into Footer directory.

**Transfer:** Use a compact choice architecture as the final conversion object when the page needs commercial detail.

**Text style:** `price` — saveeFont 500 · 48px/1 · tracking -0.025em

### Alternating catalog demonstrations

**Only for:** feature catalogs

**Observed:** An understated 21px category label precedes a 60px Catalog-heading after 20px, with Catalog-lead after 16px and pill action after 28px. Text blocks stay around 450px wide. Alternating media include three phone views, image-search output, related-content columns and a grid-control video. Chapters are separated by 128px. A three-column resource gallery uses tall 405px by 501px media, shorter titles and copy below.

**Transfer:** Give each capability a distinct visual proof and alternate its side rather than putting every feature inside the same generic card.

**Text style:** `catalog-heading` — saveeFont 500 · 60px/1 · tracking -0.025em

### Illustrated setup and customization

**Only for:** creation-product pages

**Observed:** Creation-heading introduces two centered steps with small landscape thumbnails above Step-heading and compact copy. Later chapters switch to asymmetric text/media splits. A domain-oriented chapter uses a very large text-and-image composition. The final action is a solitary 320px-wide black pill with 192px of space above and roughly 208px before the directory.

**Transfer:** Use two or three understandable milestones and show actual deliverable customization. Finish with a single action rather than repeating the full hero.

**Text style:** `creation-heading` — saveeFont 600 · 60px/1 · tracking -0.025em

### Technical explanation and setup

**Only for:** dark technical landing pages

**Observed:** Technical-heading introduces three short capability columns, followed by a narrower method table with fine dark rules and monospace names. A 768px setup column uses outlined numbered circles, Card-heading titles, compact explanation, tool-selector tiles and Command blocks. A 1024px prompt grid then offers concrete examples, followed by FAQ rows in an 896px column.

**Transfer:** Move from what the integration enables to what it exposes, how to connect it and what to ask first. Preserve the contrast between spacious chapter headings and dense practical instructions.

**Text style:** `technical-heading` — saveeFont 500 · 48px/1 · tracking -0.035em

### Enclosed invitation and directory

**Only for:** feature catalogs and dark technical landing pages

**Observed:** Conversion enclosure centers a tightly tracked Closing-sentence, a restrained support line, one contrasting pill and a small social-proof line. The panel spans almost the full outer envelope at 440px minimum height. Dark technical stories add a documentation link and a broad monochrome studio-logo proof row before it. Footer directory follows on the underlying canvas, not inside the rounded panel.

**Transfer:** Use a short outcome sentence and one next action. Keep the wide enclosure distinct from ordinary cards, and preserve the quieter directory beneath.

**Text style:** `closing-sentence` — saveeFont 500 · 60px/1 · tracking -0.055em

## Page flow

**Storyline:** promise → visual abundance → credible proof → capability demonstrations → practical or commercial decision → restrained closing action and directory

### Broad marketing landing page

1. **promise** — Image-interrupted sentence, one support line and paired actions.
2. **visual proof** — Staggered image field, monochrome customer-logo line and a large quote panel.
3. **capability chapters** — Search results strip, editorial split demo, paired resource cards and output-oriented product stories.
4. **shared-workflow proof** — Broad video with four compact benefit explanations.
5. **commercial decision** — Three neutral pricing cards, comparison link and the shared directory footer.

**Transfer:** Adapt the number and order of chapters to the product; retain the visual abundance, large editorial sentences and soft proof plinths.

### Feature catalog

1. **promise** — Short centered display and one-line explanation above a broad visual grid.
2. **capability chapters** — Alternating text/media demonstrations with muted category labels and pill actions.
3. **adjacent value** — Three tall visual resource previews with their own explanations.
4. **closing call** — Wide enclosed invitation, then full directory and legal/download strip.

**Transfer:** Use when visitors need to understand several distinct capabilities without a dense feature matrix.

### Creation-product landing page

1. **promise** — Compact centered semibold hero with one action and status label.
2. **output demonstration** — Overflowing rows of finished template previews.
3. **ease of adoption** — Two illustrated steps and a large domain-oriented composition.
4. **capability demonstration** — Customization video and asymmetric finished-template proof.
5. **closing call** — A lone wide action with generous breathing room, then the shared footer.

**Transfer:** Emphasize finished outcomes and short setup milestones; use the brighter canvas and heavier title variant.

### Technical integration landing page

1. **promise** — Black canvas, floating navigation pill, centered promise, install and plan actions, inclusion note and avatar proof.
2. **product demonstration** — Dark cinematic media montage with a centered command overlay.
3. **capability and trust** — Three explanatory columns followed by a fine-ruled API capability table.
4. **activation** — Numbered installation walkthrough, tool selection and copyable commands.
5. **practical examples** — Three-by-three prompt-card grid.
6. **objection handling** — FAQ stack and documentation route.
7. **closing call** — Monochrome studio-logo proof, dark enclosed invitation and the directory footer.

**Transfer:** Use for a product whose value must be paired with explicit connection instructions; keep the technical density local rather than darkening every ordinary landing page.

## Writing

Direct, visually literate and reassuring. The voice cares about taste and craft but explains practical operations in everyday language rather than presenting itself as an exclusive design institution.

**Do not copy:** Do not reuse the Savee name, logo, proprietary artwork, customer or partner marks, testimonial quotations, audience totals, library counts, prices or product-specific claims. Source examples illustrate syntax and tone only.

- **Addressing the reader:** Speak to the reader as you and your; use we sparingly for the people making or curating the product. Name the product when a concrete explanation needs a subject.
- **Rhythm:** Headlines are usually short benefit sentences of four to nine words, with occasional longer two-line promises. Support is one or two concrete sentences; actions are two to four words. Periods are common in section statements, exclamation marks are absent.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A plain superlative or memorable benefit, stated without a colon or technical qualifier. | 5–10 words | “The best place to save and share inspiration”<br>“Give your AI agents taste” |
| Section heading | Name the result or contrast yesterday's friction with today's simpler action. | 4–9 words | “Finding the right reference took hours.”<br>“Now it’s one search.”<br>“Your inspiration, your way” |
| Supporting line | Use a concrete workflow sequence, not a cloud of benefits. | 12–35 words | “References curated by designers, saved in one click and sorted into boards.”<br>“Pick a template in [Brand]’s easy-to-use portfolio editor, put your work next to the references that shaped it, and publish it on your own domain.” |
| Primary action | Verb plus immediate task; state free access only if true. | 2–4 words | “Join for free”<br>“Create your site”<br>“Start creating” |
| Setup heading | Make a practical operation feel short and achievable. | 3–6 words | “Connected in two minutes.”<br>“Select your template” |

**Words and phrasing to use:** your; taste; craft; curated; start from; in one click; build; pick; share; made by

**Avoid:** revolutionary; unlock limitless potential; synergy; cutting-edge ecosystem; 10x everything; exclusive elite community

**Rules:**

- Pair evocative nouns such as taste or inspiration with concrete verbs and visible operations.
- Use numbers only when they help the reader understand scale, price or setup and can be substantiated.
- Explain an unfamiliar technical term in the FAQ rather than loading the opening with definitions.
- In small inclusion notes, plainly state plan restrictions without sales flourish.
- Keep the footer sign-off human and brief.

## Do's and Don'ts

### Do

- Keep the ordinary marketing canvas #f3f3f3 and reserve #fdfdfd for meaningful raised groups.
- Balance the 95.8px hero sentence around three text-scale picture tokens rather than around a separate hero illustration.
- Use 500-weight section headings at 64.8px/1.05 with -0.025em tracking.
- Let 16px image gutters contrast with 128px–160px chapter breathing room.
- Give important proof cards 32px corners and 40px internal padding.
- Keep primary actions 56px high with 20px 40px padding and a fully rounded silhouette.
- Use a same-size muted phrase to create a second voice inside a headline.
- Keep the footer's five-column directory and thin bottom separator visually subordinate to the conversion object.

### Don't

- Do not use a bright brand hue for button fills, card backgrounds or marketing text; vivid color belongs inside media.
- Do not turn every title into a 700-weight headline; medium is the defining default.
- Do not outline all white cards; soft shadows and near-white contrast already provide their edges.
- Do not replace the staggered image wall with equal square tiles separated by oversized gutters.
- Do not spread 40px rounding to tiny media; gallery tiles use 12px corners.
- Do not style the technical variant as neon cyberpunk; black, charcoal and pale type remain the structure.
- Do not add browser traffic lights, glossy device frames or ornamental chrome around every product demonstration.
- Do not enlarge compact footer links to compete with the 21px support copy or the closing action.

## Motion and responsive

### Motion

**Observed:**

- Inline pictures act as image-swap controls; utility classes specify scale/rotate transitions of 300ms with ease-out and hover scale 1.1.
- Image-wall tiles declare 500ms ease-out movement/scale transitions; the gallery has staggered vertical placement.
- Section wrappers name opacity/translate reveal transitions of 1000ms. Exact easing implementation is not established.
- The header's backing and compact conversion action change visibility with scroll. Reduced-motion variants are present in class names.

**Transfer:**

- Keep image swapping local to the collectible picture tokens; keep the sentence readable while the picture changes.
- Use reveal movement to introduce large editorial groups, not independent animations on every line of copy.
- Under reduced motion, keep the final sentence layout and static proof imagery intact.

**Unknown:**

- Exact reveal trigger positions, resolved easing curves and complete hover/focus state styles are not established.

### Responsive

**Observed:**

- A 600px width breakpoint is declared.
- Layout classes specify narrower page margins of 16px on small screens, reduced heading sizes, stacked split features and fewer gallery columns.
- Prompt-grid classes reduce three columns to two and then one. Footer classes reduce five columns to two; legal content becomes vertically stacked.

**Transfer:**

- Keep picture tokens inline with the headline as its font size shrinks; rebalance line breaks before shrinking images below recognition.
- Collapse text/media splits into one column and keep the demonstration close to its explanation.
- Preserve horizontal clipping for broad image strips rather than compressing every artifact into a tiny tile.

**Unknown:**

- Exact mobile renderings, menu behavior and the pixel thresholds associated with named utility breakpoints beyond 600px are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
