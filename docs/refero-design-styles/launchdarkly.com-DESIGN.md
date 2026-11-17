# LaunchDarkly — neon control playground

## Overview

A bold technical style with a playful graphic streak: near-black stages, chalk-white panels, acid lime actions and bursts of orange, pink, purple and cyan. Tightly packed grotesk headlines sit above readable, restrained body copy, while floating interface fragments and outlined cartoon objects make complex software feel tangible. It suits developer tools and ambitious technology platforms, balancing spacious framing with dense demonstrations and proof.

### Essentials

- A black instrument stage, not a generic dark hero: a faint square grid backs a centered 80px/1 bold headline with -0.025em tracking, a narrow support line and a lime conversion action; interface fragments rise into the bottom of the first screen.
- Headlines feel compressed and emphatic: use headingFont3 at 64px/1, weight 700, -0.05em for major chapters, with 80px display moments and sentence-case wording rather than all-cap slogans.
- The page is a stack of rounded worlds: 1416px-wide black or #f8f8f8 panels sit 12px from the viewport sides, separated by 16px dark gutters and rounded at 24px.
- Actions are little rectangular instruments: 50px height, 12px corners, 1px outline, 18px medium labels and a separate right arrow; lime #ddff46 is the default conversion color, not a pill shape.
- Color arrives in concentrated graphic payloads: neutral canvases dominate the reading area; orange, pink, cyan and purple occupy media backings, selected words and card bases, with a full-width lime-green finale as the deliberate exception.
- Technical proof is staged like playful cut paper: detached dark UI panels overlap square grids, vivid wedges and white black-outlined symbols. Include this combination of a grid and a cropped graphic sweep; without rich product media, use a simplified chart or workflow card with the same backing.
- The ending becomes a poster: an oversized horizontally clipped black closing line spans a green gradient, above four dark illustrated destination tiles, an oversized directional emblem and compact newsletter/link columns. Preserve the monumental line and graphic tiles with new wording and original symbols.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid lime | `#ddff46` | `--color-lime` | action, accent, surface | Primary actions, active logo tabs and graphic accents. |
| Electric green center | `#adf63d` | `--color-green-middle` | background | Middle stop of the closing gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff9d29` | `--color-orange` | accent, surface, action, text | Capability highlights, graphic panels and matching actions. |
| Graphic pink | `#ee5dac` | `--color-pink` | accent, surface | Illustrated sweeps and colored information cards. |
| Electric blue | `#405bff` | `--color-blue` | text, action, accent | A selected headline word and a matching capability action. |
| Graphic purple | `#a34fde` | `--color-purple` | accent, surface | Graphic arcs and destination-tile markers. |
| Graphic cyan | `#3dd6f5` | `--color-cyan` | accent, surface | Graphic wedges and destination-tile markers. |
| Mint gradient start | `#95eb90` | `--color-green-start` | background | First stop of the closing gradient. |
| Pale citron end | `#eafca1` | `--color-green-end` | background | Final stop of the closing gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | High-contrast text and pricing card fill. |
| Chalk | `#f8f8f8` | `--color-paper` | surface, text, border | Contrasting section panels and default light headlines. |
| Cool statistic white | `#eff3ff` | `--color-stat-light` | text | Statistics on black enterprise-proof panels. |
| Cool light gray | `#d1d6d9` | `--color-body-light` | text, border | Hero support and copy on dark panels. |
| Steel gray | `#abadb0` | `--color-muted` | text | Secondary technical descriptions and subdued interface captions. |
| Small gray text | `#58595b` | `--color-fine-text` | text | Small newsletter copy on green. |
| Graphite text | `#414042` | `--color-body-dark` | text, border | Body copy on light surfaces. |
| Dark hairline | `#2c2c2c` | `--color-edge` | border, surface | Faint card outlines, hover fills and the announcement strip. |
| Raised charcoal | `#212121` | `--color-raised` | surface | Resource bands and email fields. |
| Charcoal canvas | `#191919` | `--color-canvas` | background, surface, text | Default canvas, dark cards and text on light panels. |
| Deep ink | `#0c0c0c` | `--color-quote-ink` | text | Customer story headlines, quotes and results. |
| Stage black | `#000000` | `--color-black` | background, text | Hero and demonstration stages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| question-and-answer sections | Warm graphite edge | `#41403f` | `--color-faq-edge` | border | FAQ outlines. |
| question-and-answer sections | Expanded answer lime | `#d8f56a` | `--color-open-lime` | surface | Expanded FAQ panel and its circular collapse control. |

## Typography

- **headingFont3** — Display headlines, chapter headings and large proof values. Bold contemporary grotesk with rounded bowls, compact spacing and blunt confident forms. If unavailable, use **Inter**. Use 600–700 with the tight tracking intact. Font stack: "headingFont3", "Inter", Arial, sans-serif.
- **bodyFont** — Body copy, navigation, actions and many card titles. Clean grotesk with practical proportions and a less compressed reading texture. If unavailable, use **Inter**. Use 400–600; card titles are denser than paragraphs. Font stack: "bodyFont", "Inter", Arial, sans-serif.
- **monoFont** (only for technical demonstration media) — Chart labels and code-like annotations within technical media. Plain utility monospace, secondary to the marketing grotesks. If unavailable, use **IBM Plex Mono**. Font stack: "monoFont", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | headingFont3 | 700 | 80px | 1 | -0.025em | Centered opening promise and occasional monumental mid-page statement. |
| heading-lg | headingFont3 | 700 | 64px | 1 | -0.05em | Major section headings and split-layout openings. |
| accent-word | bodyFont | 700 | 64px | 1 | normal | Single orange or blue word embedded in a dark capability headline. |
| heading | headingFont3 | 600 | 56px | 1 | -0.05em | Proof and overview section headings. |
| story-result | bodyFont | 700 | 48px | 1.2 | normal | Customer outcome paired with a small label. |
| heading-small | headingFont3 | 600 | 40px | 1.05 | -0.025em | Resource-band heading and compact closing CTA. |
| stat | headingFont3 | 600 | 40px | 1 | -0.05em | Value-first statistics with a hairline above and explanation below. |
| story-heading | headingFont3 | 700 | 40px | 1.2 | normal | Customer-story headline. |
| card-title | bodyFont | 600 | 32px | 1.1 | -0.0203em | Feature and tutorial cards. |
| tile-title | bodyFont | 500 | 24px | 1.1 | -0.021em | Resource titles and plan names. |
| hero-support | bodyFont | 400 | 20px | 31px | -0.03em | Centered opening support, normally two lines. |
| action | bodyFont | 500 | 18px | 1 | -0.01em | Default CTA label. |
| destination-label | bodyFont | 500 | 18px | 1.4 | normal | Labels in the illustrated footer tiles. |
| body | bodyFont | 400 | 16px | 1.5 | -0.03em | General section and card descriptions. |
| navigation | bodyFont | 400 | 16px | 1.5 | normal | Navigation items and untracked utility body copy. |
| header-action | bodyFont | 500 | 16px | 1 | -0.01em | Compact navigation CTA. |
| small | bodyFont | 400 | 14px | 1.5 | normal | Newsletter and footer descriptions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| colored information-card sections | colored-card-title | bodyFont | 500 | 32px | 1.1 | -0.0203em | Black title on a saturated card. |
| deep product capability pages | process-title | headingFont3 | 600 | 28px | 1.3 | normal | Numbered screenshot-led process cards. |
| question-and-answer sections | answer | bodyFont | 400 | 15px | 1.5 | normal | Expanded answer text. |

**Notes:**

- Display tracking is -0.025em; major 64px and 56px headings tighten to -0.05em. Do not apply the same tracking to every size.
- Body copy is usually 16px/1.5 with -0.03em tracking, but navigation stays untracked. Labels are medium weight rather than heavy.
- Use sentence case and deliberate line breaks. A single colored word is an accent treatment, not a full gradient headline.

## Layout

**Density:** Airy framing around compact technical content: tall panels surround tightly grouped labels, rules and media.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Capability-chip gutters and tight control groups. |
| 10px | Button label-to-arrow gaps and some small flex groups. |
| 12px | Outer page inset and FAQ row spacing. |
| 16px | Section gutters, resource-card gutters and compact stacked copy. |
| 24px | Grid gaps, heading-to-support gaps and normal action separation. |
| 31px | Outlined-card inset and hero copy rhythm. |
| 32px | Feature-card padding and medium content separation. |
| 40px | Split capability gap and proof-card internal grid gap. |
| 48px | Resource heading separation and story-panel vertical inset. |
| 56px | Main panel side padding and broad split-layout gap. |
| 88px | Default light feature and resource-panel vertical padding. |
| 112px | Hero, proof and editorial panel vertical padding. |

### Containers and grids

- **panel-shell**: max width 1416px · side padding 12px. Centered rounded panels almost fill the desktop viewport.
- **panel-content**: max width 1304px · side padding 56px. Content inside the panel shell; combines with the outer inset for a 68px text edge.
- **narrow-grid**: max width 1084px · 2 columns · gap 16px. Centered tutorial and illustrated use-case cards.
- **resource-grid**: 4 columns · gap 16px. Four equal compact media-first cards.
- **proof-grid**: 4 columns · gap 24px. Dark statistic grids with 96px between rows; the light company variant uses three columns.
- **pricing-grid** (only for pricing pages): max width 1178px · 3 columns · gap 19px. Three equal 380px plan cards centered inside the light shell.
- **faq-column** (only for question-and-answer sections): max width 864px · gap 12px. 800px text panel plus a separate 48px circular control and 16px gap.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | section panels | 24px |
|  | buttons | 12px |
|  | outlined feature cards | 32px |
|  | resource and process cards | 16px |
|  | floating media widgets | 20px |
|  | circular controls | 50% |
| pricing pages | pricing cards | 30px |
| question-and-answer sections | FAQ panels | 10px |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page ground.

**CSS:** `background: #191919`

**Observed:** Visible as slim gutters between contrasting panels.

**Transfer:** Keep gutters dark even between two light sections.

#### Black stage · level 1

**Use:** Hero, product overview and proof scenes.

**CSS:** `background: #000000; border-radius: 24px; overflow: hidden`

**Observed:** Hard contrast and clipped art define the layer, rather than a drop shadow.

**Transfer:** Give product media a black theatrical backing.

#### Light panel · level 1

**Use:** Feature chapters, pricing and stories.

**CSS:** `background: #f8f8f8; color: #191919; border-radius: 24px; padding: 88px 56px`

**Observed:** Nearly full width; editorial and proof variants use 112px vertical padding.

**Transfer:** Alternate strong light and dark chapters without tinting all backgrounds.

#### Outlined card · level 2

**Use:** Tutorials and use-case explanations.

**CSS:** `background: #191919; border: 1px solid #2c2c2c; border-radius: 32px; padding: 31px; overflow: hidden`

**Observed:** The thin edge separates a card from a matching canvas; vivid art runs along the lower edge.

**Transfer:** Keep the top text field neutral and put color in a cropped base shape.

#### Resource band · level 1

**Use:** Compact educational destinations.

**CSS:** `background: #212121; border-radius: 24px; padding: 88px 56px`

**Observed:** A slightly lighter dark band contains four charcoal resource cards.

**Transfer:** Use this subtle neutral contrast instead of another bright chapter.

#### Green finale · level 0

**Use:** Monumental closing statement and footer.

**CSS:** `background: linear-gradient(160deg, #95eb90, #adf63d 50%, #eafca1); color: #191919`

**Observed:** Green runs behind the giant line, illustrated CTAs and link columns; the end is not a separate black footer.

**Transfer:** Keep the entire final destination area on one continuous luminous field.

#### Colored grid card · level 2

**Only for:** colored information-card sections

**Use:** Three parallel paths or ecosystem destinations.

**CSS:** `background: #ddff46; border-radius: 16px; padding: 46px 40px; overflow: hidden`

**Observed:** Lime, orange and pink variants share black copy, a small icon near the top and an outlined action at the bottom. A faint square grid fades away behind the content.

**Transfer:** Use equal saturation and hierarchy across the cards, not a singled-out recommended card.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 10px; height: 50px; padding: 10px 12px 10px 16px; background: #ddff46; color: #191919; border: 1px solid #191919; border-radius: 12px; overflow: hidden`

**Text style:** `action` — bodyFont 500 · 18px/1 · tracking -0.01em

**Observed:** Label precedes a right arrow held in its own trailing box. Orange and blue variants tie an action to its capability; outline variants reverse the text and border for the background.

**States:** Declared: hover changes text to #fff; a dark pseudo-element supplies the fill treatment. Most linked variants also underline the label.

### Navigation item

**Use:** Desktop menu links in the central sticky navigation island.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 8px 12px; border: 1px solid transparent; border-radius: 8px; color: #ffffff`

**Text style:** `navigation` — bodyFont 400 · 16px/1.5

**Observed:** The header is cut into three islands: identity at left, a centered dark menu with rounded lower corners, and a lime conversion tab at right. The compact CTA is 45px high with 0px 0px 8px 8px corners and uses header-action.

**States:** Declared: hover uses #2c2c2c and rgba(255,255,255,0.1) border; background and border transition 0.3s linear.

### Email conversion bar

**Use:** Single-field conversion under the opening copy.

**CSS:** `background: #212121; border: 1px solid transparent; border-radius: 16px; width: 500px; height: 58px; position: relative`

**Text style:** `navigation` — bodyFont 400 · 16px/1.5

**Observed:** The field occupies the left side and the Primary button is inset at the right. The footer variant is 340px by 56px with 12px corners and a smaller submit action.

### Illustrated feature card

**Use:** Benefit or tutorial destination.

**CSS:** `background: #191919; border: 1px solid #2c2c2c; border-radius: 32px; padding: 31px; overflow: hidden; position: relative`

**Text style:** `card-title` — bodyFont 600 · 32px/1.1 · tracking -0.0203em

**Observed:** Title and short body sit upper left; a vivid sloped or curved graphic occupies the bottom, with the action near the lower right. A full-width card can sit beneath a pair.

### Resource card

**Use:** Compact learning destinations in a four-column band.

**CSS:** `background: #191919; border-radius: 16px; overflow: hidden`

**Text style:** `tile-title` — bodyFont 500 · 24px/1.1 · tracking -0.021em

**Observed:** A colorful media thumbnail sits above title, muted category and a short description. A dark arrow capsule bridges the lower-right corner of the image and text field.

### Statistic cell

**Use:** Quantified proof within a dark chapter.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.12); padding-top: 16px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `stat` — headingFont3 600 · 40px/1 · tracking -0.05em

**Observed:** Large value first, small explanation below; compliance items can add a tiny lime verification symbol. The light variant changes to dark values and a charcoal top rule.

### Customer story panel

**Use:** Human and quantified evidence.

**CSS:** `background: #f8f8f8; border-radius: 24px; padding: 48px 56px`

**Text style:** `story-heading` — headingFont3 700 · 40px/1.2

**Observed:** A vertical rail of differently rounded customer-logo tiles sits left; the active tile is lime. The main column separates a headline panel from a quote-and-result panel. The lower panel pairs quote and attribution with a square photograph and an attached corner action. Previous and next controls sit together below the quote.

### Destination tile

**Use:** Four illustrated actions in the green finale.

**CSS:** `border-radius: 12px; overflow: hidden; position: relative; height: 150px`

**Text style:** `destination-label` — bodyFont 500 · 18px/1.4

**Observed:** A dark top bar places a 24px colored arrow badge left and a white label right. Large abstract wedges, arcs and waves extend through the lower field; tiles use distinct accent colors.

### Pricing plan

**Only for:** pricing pages

**Use:** Comparable purchase options.

**CSS:** `background: #ffffff; border: 1.5px solid #191919; border-radius: 30px; padding: 38px 28px; display: flex; flex-direction: column`

**Text style:** `tile-title` — bodyFont 500 · 24px/1.1 · tracking -0.021em

**Observed:** Plan name and two-line positioning precede a full-width dark action, then reassurance, price and rule-separated feature groups. The enterprise-style card adds a second lime trial action. Plans align at the top, with no enlarged highlighted middle tier.

### FAQ panel

**Only for:** question-and-answer sections

**Use:** Objection handling.

**CSS:** `background: #d8f56a; border: 1px solid #41403f; border-radius: 10px; overflow: hidden`

**Text style:** `answer` — bodyFont 400 · 15px/1.5

**Observed:** The expanded variant is lime with its answer inside; collapsed variants are white. Each has a separate 48px circle outside the text panel, aligned with the top. Questions have 18px 24px trigger padding; answer text stays narrower than the panel.

**States:** Declared: focus-visible on the question trigger uses 2px solid #000 outline with 2px offset and 10px radius; expand-control hover uses #f8f8f8 and #2e2e2e border.

## Imagery and graphics

### Floating technical stage

**Use:** Default opening product object.

**Observed:** Oversized detached dark metric panels, mini charts, model bars and small colored icon tiles cluster across the lower edge of a black square-grid stage. Some extend beyond the viewport. The text stays clear above them; lime and purple chart marks are bright against subdued gray labels.

**Transfer:** Use a few authentic product fragments or simplified metrics related to the new product. The minimum is one wide workflow or distribution card, one compact chart, and a small graphic token, not an entire dashboard screenshot.

**Build:** Layer a 1px rgba(255,255,255,0.08) square grid at roughly 64px intervals over black; fade it toward the top with a black gradient. Place 20px-radius charcoal cards at staggered heights across the lower third, with thin gray rules and lime or purple SVG polylines. Clip the outer cards to the stage and leave the headline area empty.

### Grid-backed feature illustrations

**Use:** Capability media beside copy and in deep product sections.

**Observed:** UI fragments are enlarged and clipped against bright lime, orange-pink or blue-purple backings with square rules. White stickers with black outlines—stars, pointers and symbolic objects—overlap the backing and the UI. The art usually takes as much or more space than the accompanying body copy.

**Transfer:** Keep the UI recognizable at a glance and simplify dense text. Substitute an original outlined symbol meaningful to the new capability.

**Build:** Use a rounded overflow-hidden frame. Fill with a two-color accent gradient, add two perpendicular repeating-linear-gradients with 1px rgba(0,0,0,0.15) rules every 49px, then place a charcoal or white UI panel offset down and right. Add a white SVG four-point star with a black outline at a corner.

### Graphic sweeps

**Use:** Required visual punctuation in a statement section or illustrated card base.

**Observed:** Broad cropped swoops and jagged wedges carry pink-purple or orange-yellow gradients. They enter from the bottom, sometimes behind a monochrome outlined character or object; there is no photorealistic 3D lighting.

**Transfer:** Create original sweeping geometry and an original symbolic object. The minimum acceptable graphic is a clean oversized curve or zigzag plus a black-outlined white symbol.

**Build:** Draw an SVG path spanning the lower half of a panel: either an asymmetric oval swoosh rotated about -12deg or a three-point zigzag rising to the right. Fill with an orange-to-pink or pink-to-purple linear gradient, clip to the section corners, and overlap a white four-point star outlined in #191919. Use the same shapes at smaller scale in destination tiles.

### Proof-panel corner art

**Use:** Large numerical proof sections.

**Observed:** A folded angular orange-to-lime shape intrudes from the top right; a pink-purple curved sweep enters from the bottom right. The statistics remain on an otherwise flat neutral panel.

**Transfer:** Frame genuine metrics with cropped geometry instead of adding a decorative icon to every statistic.

**Build:** Place an SVG polygon in the upper-right quarter with points forming a downward notch, filled with an orange-to-lime gradient. Place an ellipse or broad curved path in the bottom-right quarter with pink-purple fill. Hide overflow and keep both behind the content.

### Closing poster lettering

**Use:** Required monumental closing device.

**Observed:** An oversized black question repeats horizontally, interrupted by a small starburst, and clips at both viewport edges. Its scale is far larger than the ordinary headings and makes the footer feel like a moving poster.

**Transfer:** Write a short new question about the user's desired outcome. Retain the huge single-line repetition and clipping, above the destination tiles.

**Build:** Render the phrase as accessible live text with an aria-hidden duplicate in a single no-wrap flex track. Use a bold grotesk around 112px at a 1440px viewport, with a line height near 1.2; size fluidly with the viewport. Insert a small black starburst SVG between repeats and clip horizontal overflow.

### Customer photography

**Use:** Customer proof panels.

**Observed:** Warm natural lifestyle or business portraits, square-framed at about 424px with 24px corners and a thin dark edge. Photography is concentrated in proof, rather than used as a full hero background.

**Transfer:** Use credible human context tied to the outcome, preserving natural color and simple square framing.

### Culture illustration and portraits

**Only for:** company and recruiting pages

**Use:** Humanizing editorial content.

**Observed:** Playful black-outlined white characters and symbolic objects sit over bright sloped card bases; leadership portraits are small 96px squares with 12px corners, natural color and pale neutral backings.

**Transfer:** Use original symbolic illustrations for values and consistent square headshots for people; keep these motifs out of ordinary product demonstrations.

### Icons

**Observed:** Directional arrows dominate actions: filled 16px by 12px marks, not oversized chevrons. FAQ controls use compact 16px strokes, 1.6px and round caps. Colorful rounded-square badges hold black stars, dots or simple geometric marks; white outlined stickers are more expressive than the utility icons.

**Transfer:** Use consistent small utility arrows and thin control glyphs. Save expressive black-and-white outlined symbols for media and keep them visually separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Grid stage opening

**Observed:** A 37px rounded announcement strip sits above a sticky three-island header. Behind it, a nearly full-width Black stage with 24px corners fills more than one screen. The centered two-line display headline spans about half the viewport, with generous black space above and a roughly 608px support measure below. The 20px support uses a 31px line height; a centered 500px Email conversion bar carries the Primary button. Behind the copy is a faint square grid, fading near the top. Floating technical stage cards rise from the lower edge, partly visible in the first 900px; the headline, support, form and beginnings of the main product object are all visible. The remaining card collage and logo strip fall below the fold.

**Transfer:** Start a new marketing page with this centered stage and authentic or simplified product fragments. Product-detail pages can use the same stage with two adjacent CTAs instead of the form. Editorial company pages use a left-aligned 64px promise and right-side outlined illustration; platform overviews use a left promise and a vivid grid-backed product collage on the right. Pricing opens on Light panel with a centered 64px headline, one blue phrase and plan cards already entering the first screen.

**Avoid:** Do not replace the stage with a full-screen dashboard, a photorealistic glowing orb or a colored gradient headline. Keep the product object below the promise rather than directly behind readable text.

**Text style:** `display` — headingFont3 700 · 80px/1 · tracking -0.025em

### Sticky benefit chapter

**Observed:** A Light panel pairs a 64px heading and compact numbered selectors on the left with ruled benefit rows on the right. The left column stays sticky. Active rows expose a brief description, outlined action and 419px-wide colorful media frame; inactive rows reduce to bold titles and small colored symbol badges. The broad column gap is 56px.

**Transfer:** Use this for a family of outcomes whose detail benefits from progressive focus, without requiring a particular number of rows.

**Text style:** `heading-lg` — headingFont3 700 · 64px/1 · tracking -0.05em

### Statement and sweep

**Observed:** A centered heading, small outlined asymmetric tag and broad Graphic sweeps form a high-impact visual pause. The 80px headline may span three lines while the graphic occupies the lower half and clips into the rounded panel.

**Transfer:** Express a broader promise between dense chapters. Keep the graphic device, but choose an original symbol and wording.

**Text style:** `display` — headingFont3 700 · 80px/1 · tracking -0.025em

### Capability matrix

**Observed:** Light panel contains a 600px dark feature card and a two-column array of 328px by 80px outlined capability tiles. Tile gaps are 8px; corners alternate between simple 16px rounds and 8px 54px 8px 54px asymmetry. The feature card has a 64px headline with one accent-word, support near the bottom and matching action. A companion chapter reverses the composition.

**Transfer:** Use for product families or complementary modes. Give the tiles short concrete capability names; the large card states the outcome.

**Text style:** `heading-lg` — headingFont3 700 · 64px/1 · tracking -0.05em

### Overview video

**Observed:** Black stage places a small icon/label and 56px heading in a narrow left column, while a 952px-wide interface poster fills the right. The poster is clipped by the section edge and has a lime play control at its center.

**Transfer:** Use a product walkthrough poster whose large shapes read clearly before playback.

**Text style:** `heading` — headingFont3 600 · 56px/1 · tracking -0.05em

### Proof grid

**Observed:** A 56px heading and short support introduce Statistic cells in a four-column grid, with 24px column gaps and 96px row gaps. Proof-panel corner art frames the right edge. The company variant changes to a light panel and three columns.

**Transfer:** Combine performance, scale and trust signals without inflating numbers or turning each cell into a separate card.

**Text style:** `heading` — headingFont3 600 · 56px/1 · tracking -0.05em

### Illustrated destination grid

**Observed:** A centered major heading introduces a 1084px-wide two-column group of Illustrated feature cards; 16px gaps and a full-width final card give variation. The lower graphics supply most of the color.

**Transfer:** Use for learning paths, use cases or next steps; keep all descriptions short enough to leave the graphic base open.

**Text style:** `card-title` — bodyFont 600 · 32px/1.1 · tracking -0.0203em

### Deep product process

**Observed:** Numbered screenshot-led black cards use a two-column grid with 24px horizontal and 32px vertical gaps. A wide card can span the pair. Each has 24px padding, an enlarged UI fragment on a vivid grid/sweep backing, a colored numbered badge, a 28px title and muted explanation.

**Transfer:** Use for detailed workflows, keeping the overall page typography separate from the UI's smaller internal text.

**Text style:** `process-title` — headingFont3 600 · 28px/1.3

### Editorial company content

**Observed:** A light chapter pairs a large left headline with a narrower right prose column below a ruled section label. Recruiting calls move back to black, centered copy and corner illustration. Value cards use a two-by-two illustrated grid; the people chapter pairs a left headline with ruled categories and compact portrait rows. Three ruled utility columns lead into the green finale.

**Transfer:** Use this scoped format for origin, culture, leadership and contact information, not as extra product feature chapters.

**Text style:** `heading-lg` — headingFont3 700 · 64px/1 · tracking -0.05em

### Pricing and comparison

**Observed:** The light opening contains Pricing plan cards beneath the centered promise. A later comparison area uses a large title, a ruled three-plan action header and wide category rows; detailed cells are compact and divided by pale horizontal lines. A dark Resource band precedes the shared finale.

**Transfer:** Present a small number of genuinely comparable options and let category rows contain progressively detailed comparisons.

**Text style:** `tile-title` — bodyFont 500 · 24px/1.1 · tracking -0.021em

### Question column

**Observed:** A Light panel centers the 864px FAQ column below a large heading. FAQ panels alternate white collapsed rows with a lime expanded answer, paired with detached circular controls.

**Transfer:** Use plain customer questions and concise explanatory answers; preserve the detached-control silhouette.

**Text style:** `heading-lg` — headingFont3 700 · 64px/1 · tracking -0.05em

### Green poster finale

**Observed:** Green finale carries Closing poster lettering clipped edge to edge. Below it, a large directional emblem anchors the left and four Destination tiles align to its right with 16px gaps. Newsletter and social links sit below the tiles beside three compact link columns; a fine low-opacity dark rule introduces the legal row. The entire ending stays green.

**Transfer:** Rebuild the oversized question, graphic destination tiles and compact practical footer as a single designed destination. Use the new product's own symbol for the large directional emblem.

**Text style:** `destination-label` — bodyFont 500 · 18px/1.4

## Page flow

**Storyline:** Promise → recognizable product behavior → capability chapters → credible proof → practical next steps → monumental invitation and useful footer.

### Broad marketing landing page

1. **Promise** — Centered grid-backed opening with a conversion form and floating interface objects.
2. **Capability chapters** — Sticky benefit list, statement-and-sweep interlude, then complementary capability matrices.
3. **Product demonstration** — Wide video poster followed by illustrated learning paths.
4. **Social proof** — Logo selector, human quote, photograph and measured result.
5. **Next steps** — Four resource cards.
6. **Closing call** — Green poster finale with graphic destination tiles and footer.

**Transfer:** Choose chapters that explain the new product; retain the stage, graphic punctuation and emphatic ending rather than copying a fixed section count.

### Company and recruiting story

1. **Promise** — Left-aligned mission and actions opposite a playful monochrome illustration.
2. **Origin and credibility** — Light editorial split, recognition badges and a light statistics grid.
3. **Human connection** — Centered recruiting call, illustrated values and colored ecosystem cards.
4. **Organizational trust** — Portrait directory and ruled utility columns.
5. **Closing call** — Shared green poster finale.

**Transfer:** Replace company facts with the new organization's real story while preserving the contrast between editorial prose and graphic culture moments.

### Platform explanation

1. **Promise** — Split black hero with vivid interface collage.
2. **Credibility** — Dark numerical proof and three colored tool-path cards.
3. **Product model** — Layer diagram and graphic statement explain how the system fits together.
4. **Capability chapters** — Complementary matrices, overview video and use-case cards.
5. **Conversion and objections** — Logo-backed call followed by light FAQ column.
6. **Closing call** — Shared green poster finale.

**Transfer:** Teach the system model before enumerating workflows; support complexity with enlarged diagrams and concise chapter titles.

### Deep flagship capability landing page

1. **Promise** — Centered grid stage, product icon and paired conversion actions.
2. **Product demonstration** — Numbered benefit selector with large active media.
3. **Mechanism** — Light before-and-after code comparison.
4. **Workflow** — Numbered screenshot-led cards with one wide step.
5. **Proof** — Dark enterprise statistics and customer story.
6. **Objection handling** — Light FAQ column.
7. **Closing call** — Shared green poster finale.

**Transfer:** Use before-and-after to reveal the mechanism, then organize specific workflows with numbered visual steps.

### Purchase evaluation

1. **Pricing promise** — Light hero and three aligned plan cards with a blue headline phrase.
2. **Trust** — Differently rounded logo tiles.
3. **Comparison** — Wide ruled plan matrix with category rows.
4. **Decision support** — Dark resource cards.
5. **Closing call** — Shared green poster finale.

**Transfer:** Keep pricing mostly light and information-dense; use the common navigation and bright ending to maintain continuity with darker landing pages.

## Writing

Confident, practical and technically literate, with a little irreverence. Benefits are stated directly, then explained through concrete mechanisms rather than abstract transformation language.

**Do not copy:** Do not reuse LaunchDarkly's name, logos, character artwork, customer identities, quotes, pricing, certifications, adoption figures or performance claims. Replace every brand-specific claim and asset with truthful original content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you in promises and imperatives. Use we for the company story, and the product name when describing a specific mechanism.
- **Rhythm:** Short assertive headlines often pair two clauses or contrast a problem with an outcome. Supporting copy usually explains one idea in one or two sentences; actions stay brief and verb-led.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A fast-moving promise balanced by reassurance. | 6–10 words | “Move at AI speed. Stay in control.” |
| Capability headline | Verb-led outcome, with concrete object and context. | 4–9 words | “Ship AI-built code with confidence.”<br>“Stop hardcoding. Start iterating faster.” |
| Support | Explain the mechanism and why it matters without repeating the title. | 12–30 words | “Progressively release changes and roll back instantly based on real-time impact.” |
| Action | Literal verb plus destination or next step. | 2–4 words | “Book a demo”<br>“View open roles” |
| Editorial headline | A concrete origin or purpose with a slight conversational twist. | 5–10 words | “Making software releases boring since 2014.” |
| FAQ introduction | Plainspoken reassurance instead of formal documentation language. | 5–8 words | “Got questions? We have answers.” |

**Words and phrasing to use:** control; ship; build; real time; confidence; without; automatically; one place; what happens after

**Avoid:** revolutionary; magical; unparalleled; synergy; unlock limitless potential; future-proof everything

**Rules:**

- Pair bold promises with a visible explanation or proof nearby.
- Use specific nouns and operational verbs before category jargon.
- Let a technical detail explain a benefit, rather than using technical vocabulary as decoration.
- Keep numbered workflow titles meaningful independently of their illustration.
- Use restrained conversational punctuation: periods, a purposeful em dash or a direct question, not repeated exclamation marks.

## Do's and Don'ts

### Do

- Keep outer panel gutters at 12px and inter-panel separation at 16px.
- Use 64px/1 chapter headings with -0.05em tracking for the strongest hierarchy.
- Give default CTA buttons 12px corners and a distinct 16px-wide trailing arrow.
- Stage interface fragments on grids and vivid cropped backings, with neutral text regions.
- Use 1px hairlines to organize cards and statistics instead of soft elevation.
- Match colored actions to the orange or blue word in their capability chapter.
- Keep a strong poster-scale closing line and illustrated destination tiles on the continuous green footer.
- Use warm square photography only where it supplies credible human proof.

### Don't

- Do not turn every action into a 9999px capsule; the default is a 12px rounded rectangle.
- Do not brighten the whole dark canvas to medium gray; preserve #191919 and true-black stages.
- Do not use light-gray body text on the light panels; use #414042 for readable contrast.
- Do not add drop shadows to every card; the system separates surfaces with outlines and hard contrast.
- Do not replace the asymmetrically rounded capability tiles and logo tabs with one uniform shape everywhere.
- Do not make all headings 80px; reserve that scale for display and statement moments.
- Do not scatter saturated text colors through body paragraphs; color belongs to selected words, actions and art.
- Do not use all-uppercase marketing headlines or wide tracking at display sizes.

## Motion and responsive

### Motion

**Observed:**

- Floating widgets declare 0.7s fade/slide entry with cubic-bezier(.22,.61,.36,1), and some declare a 12s ease-in-out floating loop.
- Default buttons declare background-color, border-color and color transitions of 0.3s.
- Navigation background and border transitions are 0.3s linear.
- FAQ panels declare a 0.32s cubic-bezier(0.4,0,0.2,1) color/background/border transition.
- The giant closing line repeats as a horizontal marquee; timing is not specified here.

**Transfer:**

- Use slow floating only on the detached product fragments, leaving reading text stable.
- Retain the clipped repetition of the closing poster line even when rendered as a static reduced-motion composition.

**Unknown:**

- Exact marquee duration and scroll-linked section pinning behavior.
- Reduced-motion implementation and animation sequencing across all components.

### Responsive

**Observed:**

- Desktop design uses the 1416px panel shell and 56px inner side padding.
- Styles declare many width breakpoints, including 600px, 768px, 900px, 1024px, 1140px and 1440px.

**Transfer:**

- For narrow layouts, stack split chapters while keeping rounded full-width panels and dark gutters.
- Recompose the floating collage below the headline, retaining deliberate clipping rather than shrinking the whole desktop scene.
- Stack plan and feature grids, preserve label-arrow button separation and keep the closing line wider than the viewport.

**Unknown:**

- Exact mobile sizes, navigation layout and breakpoint-specific padding values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
