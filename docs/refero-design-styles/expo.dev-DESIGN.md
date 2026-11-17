# Expo — radiant tools, soft machinery

## Overview

A bright developer-oriented style that makes complex infrastructure feel tangible and approachable. Tight grotesk headlines, small technical mono labels and compact controls sit among expansive pale cards, sculptural symbols and floating interface fragments. The palette is mostly white, cool gray and black, with blue links and localized pools of colored light; a darker, layered look gives company storytelling its own atmosphere.

### Essentials

- Headlines feel compact rather than monumental: Inter 600 at 48px/1.1 with -1.2px tracking in the opening, -2px for section leads; 64px/1.1 with -3px tracking is reserved for statement-scale proof and centered product promises.
- The opening is a three-part instrument panel: a 416px headline-and-action column, a central radiant object in a 656px square stage, and a separate 352px support column inside 1280px of usable width. Keep the supporting explanation out of the headline stack.
- Controls are small black and gray capsules, not colorful slabs: the opening pair is 40px high with 40px radius, 16px horizontal padding and 14px semibold labels; deeper conversion controls grow to 48px.
- Color is emitted by objects, not spread across the page: white and #f9f9fb dominate, #0d74ce marks links, and blue/orange light stays inside illustrated cards. Carry a localized glow and a sculptural symbol into every new landing page, using layered SVG shapes if no rendered artwork exists.
- Capabilities live in soft machinery: 40px-radius pale cards, 64px interior padding and 64px feature-grid gaps hold floating UI fragments, fine connectors and bottom fades. Media is a staged object with air around it, not a full-bleed stock image.
- Proof becomes a sentence with objects embedded: 64px semibold metric lines alternate numbers, small logos or overlapping 48px portraits, and nouns. A tactile 535px rounded-square closing object behind a short call to action echoes the opening.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Subscription blue | `#0090ff` | `--color-action-blue` | action | Small newsletter action, not the main conversion action. |
| Object orange | `#f76809` | `--color-glow-orange` | accent | Orange source of the localized blue/orange light pool, softened by blur and white backing. |
| Object blue | `#2788f3` | `--color-glow-blue` | accent | Color on small rendered objects and the blue source of a diffused light pool. Blur and white backing make the surrounding glow pastel. |
| Link blue | `#0d74ce` | `--color-link` | link, text | Capability links and informational badge lettering. |
| Information wash | `#e6f4fe` | `--color-badge` | surface | Small product-name and recommendation badges. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#000000` | `--color-black` | action, background | Default main actions and company-story canvas. |
| Graphite ink | `#1c2024` | `--color-ink` | text | Headlines and primary marketing text. |
| Dark rule | `#363a3f` | `--color-dark-rule` | border | Command bar borders and dark-stat separators. |
| Secondary gray | `#60646c` | `--color-muted` | text | Support copy, navigation and footer links. |
| Fine rule | `#d9d9e0` | `--color-rule` | border | Comparison rows and fine separators; navigation uses this hue at 0.306 alpha. |
| Card edge | `#e0e1e6` | `--color-edge` | border, surface | Outlined white cards, plan dividers and directory search fill. |
| Control gray | `#f0f0f3` | `--color-control` | surface | Secondary capsules and expanded supporting panels. |
| Cool pale stage | `#f9f9fb` | `--color-soft` | surface, background | Large rounded capability cards and illustration backings. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default page canvas, raised UI plates and reversed button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company storytelling | Layer cyan | `#04c2d6` | `--color-cyan` | accent | Luminous central plate gradient. |
| company storytelling | Cyan outline | `#59d2ff` | `--color-cyan-edge` | border | Inset outline on the luminous plate. |
| company storytelling | Layer blue | `#002279` | `--color-deep-blue` | accent | Deep end of the luminous plate gradient. |
| technical product detail pages | Charcoal panel | `#18191b` | `--color-dark-panel` | surface | Inverted closing panel. |
| company storytelling | Sculpture charcoal | `#212225` | `--color-dark-layer` | surface | Lower opaque plates in the exploded sculpture. |
| inverted sections and company storytelling | Reverse secondary | `#b0b4ba` | `--color-reverse-muted` | text | Supporting copy and links on dark fields. |
| inverted sections and company storytelling | Reverse ink | `#edeef0` | `--color-reverse` | text | Headlines on dark fields. |

## Typography

- **Inter** — All marketing headings, prose and controls. High-x-height contemporary grotesk, tightened at display sizes and predominantly medium or semibold. Font stack: "Inter", -apple-system, system-ui, sans-serif.
- **JetBrains Mono** — Technical captions, proof labels and command bars. Explicitly monospaced technical counterpoint to the rounded illustrations. Font stack: "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Inter | 600 | 64px | 1.1 | -0.0469em | Oversized proof sentences and centered product promises. |
| opening | Inter | 600 | 48px | 1.1 | -0.025em | Default asymmetric opening headline. |
| heading | Inter | 600 | 48px | 1.1 | -0.0417em | Major section leads and closing headlines. |
| card-heading | Inter | 600 | 32px | 1.1 | -0.0156em | Capability card titles and compact section introductions. |
| feature-heading | Inter | 600 | 24px | 1.2 | -0.021em | Small bento headings and detailed capability chapters. |
| lead | Inter | 500 | 24px | 1.2 | -0.021em | Prominent card support and centered product introduction copy. |
| body | Inter | 500 | 16px | 1.4 | normal | Default marketing support, feature bullets, text links and testimonial copy. |
| body-regular | Inter | 400 | 16px | 1.4 | normal | Longer technical explanations. |
| label | Inter | 600 | 16px | 1.4 | normal | Footer group headings and short benefit labels. |
| button-lg | Inter | 500 | 16px | 1 | normal | 48px conversion capsules. |
| small-support | Inter | 500 | 14px | 1.4 | normal | Centered capability card explanations and ordinary header links. |
| small | Inter | 400 | 14px | 1.4 | normal | Compact descriptive copy and plan details. |
| button | Inter | 600 | 14px | 1 | normal | Opening conversion pair. |
| nav-control | Inter | 500 | 14px | 1 | normal | Navigation menu controls and compact plan actions. |
| footer-link | Inter | 400 | 14px | 1.625 | normal | Footer link lists. |
| technical-caption | JetBrains Mono | 400 | 12px | 1.6 | normal, uppercase | Technical proof caption above the moving icon strip. |
| micro-action | Inter | 600 | 12px | 1 | normal | Newsletter action. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Inter | 700 | 64px | 1.1 | -0.0469em | Centered pricing promise. |
| company storytelling | company-display | Inter | 600 | 56px | 1.1 | -0.0357em | Left-aligned company mission headline. |
| company storytelling | company-stat | Inter | 600 | 32px | 1.4 | -0.0313em | Compact milestone strip with vertical rules. |
| company storytelling | company-lead | Inter | 600 | 24px | 1.4 | -0.021em | Substantial mission prose on the dark opening. |
| technical service chapters | command | JetBrains Mono | 400 | 15px | 1.625 | -0.002em | Single-line CLI command. |

**Notes:**

- Keep the default opening less tightly tracked than the equally sized section headings. Statement-scale text tightens to -3px without becoming heavy; the pricing headline alone uses 700.
- Marketing prose is often 500 rather than 400. Use the regular recipe for extended technical explanations, not for every support line.
- Mono is a small technical annotation or a real command, never the main headline face. No fluid typography formula is prescribed.

## Layout

**Density:** Airy at section scale, compact inside actions and technical lists; objects and pale stages consume more area than prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Opening action pair and small icon-label gaps. |
| 12px | Footer link-list gaps and close heading/support pairing. |
| 16px | Bento gutters, testimonial gutters and compact card padding. |
| 24px | Headline-to-support-to-action rhythm and default container side padding. |
| 32px | Testimonial padding and compact section stacks. |
| 40px | Workflow-card inner inset and caption-to-heading groups. |
| 48px | Separation between media and card text. |
| 64px | Capability interiors, paired-feature gutters and chapter separation. |
| 80px | Proof-to-content spacing and directory top/bottom inset. |
| 88px | Desktop footer top padding. |
| 112px | Dark closing-panel vertical inset. |
| 128px | Service chapter padding and major transitions. |
| 200px | Vertical breathing room around oversized metric statements. |

### Containers and grids

- **main-container**: max width 1328px · side padding 24px. Centered desktop wrapper; usable content is 1280px at a 1440px viewport, leaving 80px to each visible content edge.
- **paired-features**: 2 columns · gap 64px. Two 608px cards; full-width stages alternate with pairs.
- **sculpture-bento**: 2 columns · gap 16px. Unequal 524px and 740px outer columns. Tall sculpture card left; wide short card over two smaller cards right.
- **reading-column**: max width 672px · side padding 24px. Centered explanations, FAQs and narrow introductory blocks.
- **wide-intro**: max width 768px. Centered product lead and dark closing-panel support.
- **pricing-grid** (only for pricing pages): 4 columns · gap 0px. Four connected 320px plan columns inside the main container.
- **comparison-grid** (only for pricing pages): 5 columns · gap 0px. 256px label column and four equal value columns.
- **directory** (only for company directories): max width 600px · side padding 24px. 552px usable single-column list inside a much wider pale stage.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature-stage | 40px |
|  | opening-controls | 40px |
|  | capsule | 9999px (pill) |
|  | quote-card | 16px |
|  | closing-object | 32% |
| technical service chapters | product-stage | 24px |
| product detail summaries | utility-card | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-interface | `0px 10px 20px 0px rgba(0,0,0,0.1), 0px 3px 6px 0px rgba(0,0,0,0.05)` | Lift an interface plate or small app tile, not the large pale card. |
| closing-object | `inset 0px 2.5px 21px 0px rgba(255,255,255,0.9), inset 8.4px 8.4px 168px 0px rgba(134,134,134,0.16)` | Tactile white rounded-square closing object. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing page field.

**CSS:** `background: #ffffff; color: #1c2024`

#### Soft stage · level 1

**Use:** Primary card and bento backing.

**CSS:** `background: #f9f9fb; border: 1px solid transparent; border-radius: 40px; box-shadow: none`

**Observed:** The broad surface is nearly flat; object lighting supplies depth. Large capability stages clip their media and may fade it into the backing at the bottom.

**Transfer:** Keep the backing neutral and concentrate volume in the media.

#### Outlined plate · level 2

**Use:** Testimonials and compact proof cards.

**CSS:** `background: #ffffff; border: 1px solid #e0e1e6; border-radius: 16px`

**Observed:** Thin cool edges distinguish white-on-white without heavy elevation.

**Transfer:** Use a fine edge for text-led proof, reserving floating shadows for depicted interfaces.

#### Closing porcelain · level 1

**Use:** Behind the final centered promise.

**CSS:** `background: #ffffff; border-radius: 32%; box-shadow: inset 0px 2.5px 21px 0px rgba(255,255,255,0.9), inset 8.4px 8.4px 168px 0px rgba(134,134,134,0.16)`

**Observed:** A 535px square with a subtle radial cool-gray rim and extremely faint texture, partially dissolved by a white bottom fade.

**Transfer:** Retain the softly modeled rounded square, not a conventional rectangular CTA card.

#### Dark closing panel · level 1

**Only for:** technical product detail pages

**Use:** A second, technical route to adoption after a conventional conversion call.

**CSS:** `background: #18191b; color: #edeef0; border-radius: 24px; padding: 112px 24px`

**Observed:** Centered heading and muted support sit over a white capsule action; it is inset to the main container, not a full-page theme switch.

**Transfer:** Offer a genuinely distinct adoption path here.

#### Company canvas · level 0

**Only for:** company storytelling

**Use:** Mission opening and final footer.

**CSS:** `background: #000000; color: #edeef0`

**Observed:** A white content region with 40px top corners interrupts the black shell; the directory uses a pale stage.

**Transfer:** Keep this inverted treatment confined to the company narrative.

## Components

### Navigation

**Use:** Persistent orientation and account access.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 69px; background: #ffffff; border-bottom: 0.5px solid rgba(217,217,224,0.306)`

**Text style:** `nav-control` — Inter 500 · 14px/1

**Observed:** A small wordmark and links occupy the left; repository proof, outlined login and black signup occupy the right. Menu controls have chevrons and 36px capsule hit areas. The company variant reverses the shell and text.

**States:** Declared: hover menu background #f0f0f3; focus-visible 2px solid #0588f0 outline with 1px offset.

### Primary button

**Use:** Default first-screen conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 40px; padding: 0px 16px; border: 1px solid transparent; border-radius: 40px; background: #000000; color: #ffffff`

**Text style:** `button` — Inter 600 · 14px/1

**Observed:** The label precedes a small right arrow. Deeper section calls use a 48px capsule, 24px horizontal padding and button-lg typography; header actions use 36px.

**States:** Declared: hover background #1c2024; focus-visible background #1c2024 and 2px solid #0588f0 outline with 1px offset; active scale 1 1.

### Secondary button

**Use:** Human-assisted alternative beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 40px; padding: 0px 16px; border: 1px solid transparent; border-radius: 40px; background: #f0f0f3; color: #1c2024`

**Text style:** `button` — Inter 600 · 14px/1

**Observed:** Visually equal capsule geometry but lower contrast than the main action. Product-detail variants are 48px high with 24px side padding.

**States:** Declared: hover background #e8e8ec; focus-visible background #e8e8ec and 2px solid #0588f0 outline with 1px offset; active scale 1 1.

### Capability card

**Use:** A visual outcome with a short explanatory block.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 48px; padding: 64px; background: #f9f9fb; border: 1px solid transparent; border-radius: 40px; overflow: hidden`

**Text style:** `card-heading` — Inter 600 · 32px/1.1 · tracking -0.0156em

**Observed:** Media and centered text share the card; title, small-support explanation and blue Text link have 24px spacing. Paired cards may reverse media/text order. Full-width variants remove bottom padding so the interface can dissolve into the edge.

**Transfer:** Give each card one recognizable result and one deliberately composed object.

### Text link

**Use:** Low-pressure onward route from a capability.

**CSS:** `display: flex; align-items: center; gap: 4px; color: #0d74ce`

**Text style:** `body` — Inter 500 · 16px/1.4

**Observed:** A small right chevron follows the label. Service-chapter documentation links instead use gray text and a fine underline with an external arrow.

**States:** Declared: focus-visible 2px solid #0588f0 outline with 1px offset.

### Quote card

**Use:** Human proof in a masonry field.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 32px; background: #ffffff; border: 1px solid #e0e1e6; border-radius: 16px`

**Text style:** `body` — Inter 500 · 16px/1.4

**Observed:** Circular avatar, name and smaller handle precede the quote. Cards vary naturally in height; four columns with 16px gutters are clipped to a 600px field with a lower fade.

**States:** Declared: hover background #f0f0f3 and border #d9d9e0; focus-visible the same colors with a 2px solid #0588f0 outline inset 3px.

### Subscribe button

**Use:** Small footer newsletter action.

**CSS:** `height: 32px; padding: 0px 12px; background: #0090ff; color: #ffffff; border: 1px solid #0090ff; border-radius: 32px`

**Text style:** `micro-action` — Inter 600 · 12px/1

**Observed:** A small uppercase mono newsletter label and one-line invitation sit above it; this is the unusually bright action in an otherwise neutral footer.

**States:** Declared: hover background #0588f0; focus-visible background #0588f0 and 2px solid #0588f0 outline with 1px offset; active scale 1 1.

### Footer column

**Use:** Dense destination lists at the end of every page.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px`

**Text style:** `footer-link` — Inter 400 · 14px/1.625

**Observed:** Five 180px link columns with 16px gutters follow a 300px identity/newsletter column. Group headings use label typography and 20px bottom separation. Below: copyright, green operational dot, privacy control, social icons and sometimes a compact theme selector. Desktop footer begins with 88px top padding and closes with about 24px below the utility row.

**States:** Declared: hover link color #1c2024 and opacity 0.8; focus-visible the same with 2px solid #0588f0 outline and 1px offset.

### Command bar

**Only for:** technical service chapters

**Use:** Concrete installation or workflow action paired with product explanation.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 10px; padding: 24px; background: #000000; color: #ffffff; border: 1px solid #363a3f; border-radius: 44px`

**Text style:** `command` — JetBrains Mono 400 · 15px/1.625 · tracking -0.002em

**Observed:** Terminal icon left, one-line command center, copy icon right. Product-detail openings use a narrower gray 50px-high capsule instead of this broad black bar.

**Transfer:** Use a real working command rather than decorative code.

### Plan column

**Only for:** pricing pages

**Use:** Connect plan choice to included capacity.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-top: 1px solid #e0e1e6; border-bottom: 1px solid #e0e1e6; border-left: 1px solid #e0e1e6; overflow: hidden`

**Text style:** `lead` — Inter 500 · 24px/1.2 · tracking -0.021em

**Observed:** A connected row, rounded only at the outer corners, with plan name, audience line, price, full-width 36px capsule, mono inclusions label, checked list and bottom feature link. A small blue badge marks the recommended plan; it does not receive a saturated full-card fill. Enterprise uses a gray contact action.

**Transfer:** Align prices and actions across columns even when descriptions differ.

### Comparison cell

**Only for:** pricing pages

**Use:** Dense entitlement and usage comparison.

**CSS:** `display: flex; padding: 16px 20px; border-top: 1px solid #d9d9e0`

**Text style:** `small` — Inter 400 · 14px/1.4

**Observed:** Five equal columns: left-aligned capability labels with no left padding, four centered values. A sticky pale comparison header maintains plan labels and small actions while category groups introduce their own icon, heading and explanation.

**Transfer:** Keep prose concise and use checks or dashes where they are unambiguous.

### Question row

**Only for:** product detail and pricing pages

**Use:** Objection handling.

**CSS:** `padding: 16px 8px; color: #1c2024`

**Text style:** `body` — Inter 500 · 16px/1.4

**Observed:** Chevron at the left of each question, with unboxed rows in a narrow centered stack. Pricing uses a split layout: explanatory heading left, approximately 616px question column right; expanded answers sit in a 20px-radius gray panel.

**States:** Declared: focus-visible 2px solid #0588f0 outline with 1px offset.

## Imagery and graphics

### Radiant symbol

**Use:** The central signature object of the opening.

**Observed:** A black symbol sits on a white rounded app-like tile with a fine gray edge. Hundreds of faint straight rays and small gray endpoints radiate beyond it, occupying a 656px square stage while the central tile remains compact. It is nearly monochrome, with white space shining through the rays.

**Transfer:** Use the new product's simple symbol or a geometric tool silhouette on the tile. The minimum version is a clean SVG tile and a deterministic radial network, not a generic photograph.

**Build:** In a 656px SVG viewBox place a white 180px rounded square at the center with a fine gray border. Behind it draw many straight radial segments from the tile perimeter toward an irregular outer radius of 230–320px; use gray strokes at 0.1–0.25 alpha, 0.5px width, and 1–2px endpoint dots. Vary lengths and angles without making a solid sunburst. Keep the foreground symbol black and the whole stage behind adjacent text.

### Sculptural tools and light

**Use:** Signature bento media and small identity objects.

**Observed:** A silver tubular symbol has broad matte highlights, a dark inner edge and a small prismatic glint. Rounded technology tiles tilt and overlap like physical tokens. A wide short card holds overlapping app tiles above a diffuse blue/orange pool confined to its lower edge.

**Transfer:** Model a simple meaningful tool shape in silver and make a few original rounded tokens for adjacent capabilities. A shaded SVG silhouette with a clipped highlight and soft shadow is the minimum acceptable substitute.

**Build:** For the glow, clip a layer to the 40px card radius. Near the bottom place a blue oval about 60% of card width and an orange oval about 50%, plus a narrower white oval; blur their parent by 40px. Keep the top and text backing pale. For a metal token use a thick rounded SVG path with a white-to-gray gradient, a darker narrow inner stroke, a restrained colored edge highlight and a soft floor shadow.

### Floating interface scenes

**Use:** Capability proof throughout the landing page and service chapters.

**Observed:** White dashboard fragments, small notification plates, phones and workflow graphs float over pale neutral stages. Interfaces are selectively enlarged and framed with thin gray edges and soft shadows. Wide 1150px compositions and 478px card compositions fade toward the bottom; service chapters also use 592px-wide portrait stages and 1024px-wide dashboard plates.

**Transfer:** Show a real result from the new product with enough recognizable interface structure to prove it. Limit each scene to a small number of legible fragments and preserve the airy backing; do not recreate every UI detail.

### Porcelain closing object

**Use:** Signature final conversion stage.

**Observed:** A softly lit white rounded square sits behind a short centered 64px promise and black capsule action; its edge and faint texture are just visible against white. The lower region dissolves back into the page.

**Transfer:** Echo the opening's tactile tile as an abstract support for the final promise, without repeating a large illustration.

**Build:** Make a 535px square with 32% radius, the Closing porcelain surface and a radial gray rim that strengthens only toward the edge. Add very faint noise at about 0.012 opacity and cover the lower edge with a white gradient fade. Center headline and action in front within a 620px-high stage.

### Human identity details

**Use:** Social proof; extended directory only for company pages.

**Observed:** Small circular portraits accompany quotes, overlapping metric lines and gray contact controls. The company directory is a long narrow list with individual circular portraits, semibold names, optional small blue affiliation badges and pale social icons aligned right.

**Transfer:** Use actual people in small naturally varied portraits; keep them supporting the typography rather than making a large corporate photo wall.

### Atmospheric dashboard mount

**Only for:** technical product detail pages

**Use:** Large dashboard reveal below a centered promise.

**Observed:** A white dashboard is inset into a broad rounded frame with grainy, blurred dark green, coral, blue and warm light around its perimeter. Later square feature scenes use pale blue, pink or lilac atmospheres behind isolated UI panels; one technical handoff scene uses a deep blue field.

**Transfer:** Keep the main interface crisp and bright, with colored atmosphere confined to its mount.

**Build:** Use an outer 40px-radius clipping panel, a dark neutral backing and several oversized blurred radial ellipses of blue, warm orange and desaturated green at the corners. Add a low-alpha SVG noise overlay, then inset a white rounded dashboard plate with a fine edge and soft shadow. Match the soft light rather than sharp gradient stops.

### Exploded luminous plates

**Only for:** company storytelling

**Use:** Large art beside the mission statement.

**Observed:** Five rounded diamond plates form an exploded vertical stack on black: a dark embossed top symbol, a translucent gridded glass layer, a luminous cyan-to-deep-blue layer and two charcoal lower plates. Fine outlines and dark extruded edges make the stack physical, with no photographic environment.

**Transfer:** Represent the new organization's layered system as an original exploded object, preserving the black field, blue middle light and restrained materials.

**Build:** Create five rounded-square divs or SVG planes with 20% corner radii, rotate X by 60deg and Z by 45deg, then separate them vertically in a 500px by 800px stage. Use a dark top gradient and a white extruded symbol, a glass layer at white 0.06 alpha with a 2px white 0.3-alpha edge and 15px backdrop blur, a -45deg #04c2d6 to #002279 middle plate with a 2px #59d2ff inset outline, and #212225 lower plates with soft black shadows.

### Icons

**Observed:** Compact mostly monochrome SVG pictograms: 20px for navigation, social links and action companions, 16px for checks and small controls, 24px for selected larger utilities. Chevrons, external arrows and terminal/copy symbols carry functional meaning; icon color follows secondary text or reversed button text.

**Transfer:** Choose simple neutral pictograms of consistent optical weight. Keep them small and aligned to the label rather than introducing colorful circular icon medallions.

## Section recipes

How recurring sections are built.

### First screen: Three-part radiant opening

**Observed:** A 69px sticky Navigation sits over a white 528px hero. Within the main-container, the left headline occupies a 416px column and wraps into two compact lines, with the 40px Primary button and Secondary button 24px below it. The Radiant symbol is the visual center: its 656px stage overflows the hero height while the compact tile stays clear of both text blocks. A separate right column holds a small announcement capsule above 16px support copy, inset by 64px to preserve space around the rays. Layers are white canvas, fine radial network, white symbol tile, then text and controls. Within the first 900px the entire promise, both actions, central object, right explanation, mono proof caption and 40px customer-icon strip are visible; the top and heading of the next pale workflow stage enter at the bottom. Most of that stage's demonstration remains below the fold.

**Transfer:** Preserve the separated promise, symbol and explanation even with different content. Generate the central network in SVG around an original tool silhouette if rendered art is unavailable. Centered product-detail openings instead use statement typography, a small product badge, lead copy, 48px actions and a copyable command above a wide dashboard mount. Service indexes use a centered promise and two pale endorsement cards; pricing opens with pricing-display over connected plans. Company stories open dark with company-display beside exploded plates.

**Avoid:** Do not turn the default opening into a conventional centered headline over a giant dashboard, or let the ray network collide with the copy. Do not enlarge the headline to 64px simply because the supporting page types use it.

**Text style:** `opening` — Inter 600 · 48px/1.1 · tracking -0.025em

### Workflow explainer stage

**Observed:** A full-width Soft stage with 40px interior inset pairs a left 32px heading and stacked 24px workflow labels with a large right isometric diagram. The active item exposes body copy; inactive items remain short gray labels. A small playback control accompanies the active label.

**Transfer:** Use this for an ordered process with one visual state per step. Draw a fine wireframe system of cubes, translucent blue planes and one dark active block rather than a generic row of feature icons.

**Text style:** `card-heading` — Inter 600 · 32px/1.1 · tracking -0.0156em

### Sculptural bento

**Observed:** The sculpture-bento layout pairs a tall silver-object card with a right column of one wide short light-pool card and two smaller token/interface cards. The tallest card carries a 48px title, lead copy and a black capsule; smaller cards use feature-heading. All stages share pale backing and 40px corners.

**Transfer:** Mix one foundational promise, one integration and two tangible capabilities without forcing equal card sizes.

**Text style:** `heading` — Inter 600 · 48px/1.1 · tracking -0.0417em

### Capability pairs and panoramic stages

**Observed:** A centered heading introduces paired Capability cards, alternating with 1280px-wide stages. The full-width version centers a two-line card-heading, short support and Text link, then leaves 48px before the wide interface scene. Bottom fades prevent the media edge from feeling cut off.

**Transfer:** Alternate close-up outcomes and a broad system view according to the story. Keep the component visual language consistent rather than changing the background for each capability.

**Text style:** `card-heading` — Inter 600 · 32px/1.1 · tracking -0.0156em

### Proof sentences

**Observed:** A white field with 200px vertical padding holds centered 64px metric lines separated by 16px. Each line reads as number, inline object and outcome noun. Small logos, tool icons and overlapping 48px avatars break the text without becoming separate stat cards.

**Transfer:** Turn verified product evidence into typographic sentences; when figures are unavailable use short substantiated milestones with inline artifacts rather than invented numbers.

**Text style:** `statement` — Inter 600 · 64px/1.1 · tracking -0.0469em

### Community proof field

**Observed:** A centered 48px heading, support paragraph and gray community capsule precede a four-column masonry field of Quote cards. The field is 600px high and fades across its lower half.

**Transfer:** Use authentic comments of differing lengths to create a human texture. Keep the conversion invitation outside the quote cards.

**Text style:** `heading` — Inter 600 · 48px/1.1 · tracking -0.0417em

### Tactile close and resource footer

**Observed:** The default closing promise sits in front of Closing porcelain, followed by a slim trust-mark rail and a fine horizontal divider. The final resource footer uses Footer column and Subscribe button components. Service-index closings instead use a broad 40px-radius pale panel; technical detail pages add Dark closing panel after the main call and explanatory bridge. Company stories return to black only at the footer.

**Transfer:** Finish with a concise outcome and one clear action, then a useful dense resource area. Retain the tactile rounded-square device somewhere in the landing-page composition even if the close itself is a pale panel.

**Text style:** `statement` — Inter 600 · 64px/1.1 · tracking -0.0469em

### Service chapter

**Only for:** technical service indexes

**Observed:** A blue icon-and-name label leads a 48px heading in a 592px text column, paired with a 592px pale media stage. Lists have small monochrome icons; a ruled documentation row and black Command bar ground the claim. Alternating chapters reverse the text and media. Broader chapters split headline and benefits above a 1024px interface plate.

**Transfer:** Give each service its own outcome, concrete operation and proof artifact. Keep the chapter navigation in gray capsules below the main Navigation.

**Text style:** `heading` — Inter 600 · 48px/1.1 · tracking -0.0417em

### Detailed feature demonstration

**Only for:** technical product detail pages

**Observed:** A repeated 1280px row has a 640px text half with 128px right inset and a 640px square visual half. Text is vertically centered, with a 24px feature-heading and 16px regular paragraph separated by 24px; rows are separated by 64px.

**Transfer:** One explanatory idea per row. Vary the interface detail and subtle light tint, not the fundamental alignment.

**Text style:** `feature-heading` — Inter 600 · 24px/1.2 · tracking -0.021em

### Pricing selection and comparison

**Only for:** pricing pages

**Observed:** A centered 64px bold promise precedes four connected Plan columns. A narrow helper block includes a blue badge, contact action and a copyable plain-text recommendation prompt. A sticky comparison strip anchors long five-column ruled tables grouped under category labels. Questions lead into a 16px-radius gray closing panel with a centered 48px promise and 40px black action.

**Transfer:** Combine fast plan selection with rigorous entitlement detail. Keep the recommended plan visually restrained and make machine-readable help a useful secondary affordance.

**Text style:** `pricing-display` — Inter 700 · 64px/1.1 · tracking -0.0469em

### Company narrative and directory

**Only for:** company storytelling

**Observed:** The black opening gives 128px vertical room to a 508px mission column and 500px exploded sculpture, separated by 128px. Semibold 24px gray mission prose leads to a 32px milestone strip with dark vertical dividers. A white rounded-top transition carries partner marks into a 40px-radius pale directory stage; its centered search and 552px single-column rows are deliberately narrow. A white 48px invitation and black 48px action precede the black footer.

**Transfer:** Use the dark system sculpture for the organization's point of view, then lighten the page for approachable human content. Adapt the list to team members or contributors rather than making a compulsory roster.

**Text style:** `company-display` — Inter 600 · 56px/1.1 · tracking -0.0357em

## Page flow

**Storyline:** Promise → tangible system demonstration → capability outcomes → substantiated proof → adoption help → decisive closing call → resource-rich footer.

### Broad product landing page: make infrastructure feel like a coherent toolkit

1. **promise** — Asymmetric three-part opening with radiant central tile.
2. **social proof** — Mono caption and moving app-icon strip.
3. **product demonstration** — Workflow stage followed by sculptural bento.
4. **capability chapters** — Paired cards alternating with panoramic interface stages.
5. **quantified proof** — Oversized metric sentences with inline objects.
6. **social proof** — Community invitation and fading masonry quotes.
7. **closing call** — Porcelain object, concise promise and action, then trust rail.
8. **resources** — Five destination groups beside identity and newsletter, followed by utilities.

**Transfer:** Use the same contrast between tangible tools, concise outcomes and large-scale proof without fixing the number of sections.

### Single technical product detail: turn a problem into an observable result

1. **promise** — Centered question, product badge, lead, two actions and command.
2. **product demonstration** — Wide dashboard mounted in colored light.
3. **capability summary** — Centered explanation and four compact outlined benefit cards.
4. **capability chapters** — Repeated text-left, square-media-right demonstrations.
5. **adoption help** — Video introduction and narrow questions.
6. **closing call** — Centered benefit and dual actions, explanatory bridge, then dark alternate-adoption panel.
7. **resources** — White resource footer.

**Transfer:** Move from problem to visible evidence, then answer practical objections and offer both direct and assisted adoption.

### Multi-service overview: explain a platform as a set of concrete operations

1. **promise** — Centered statement and contact action over two endorsement cards.
2. **capability chapters** — Capsule chapter navigation, alternating text/media rows, commands and ruled documentation links.
3. **compatibility proof** — Pale full-width band with overlapping tool tiles and a two-tone heading.
4. **product demonstration** — Broader dashboard chapters within the service sequence.
5. **closing call** — Large pale rounded panel, brief imperative and black action.
6. **resources** — Shared white footer.

**Transfer:** Let each service have its own proof artifact while shared chapter construction makes them feel like one system.

### Pricing: provide a quick choice and a careful comparison

1. **promise** — Centered bold pricing statement.
2. **pricing** — Four connected plan columns with audience lines, inclusions and actions.
3. **adoption help** — Contact route and copyable plain-text plan-comparison prompt.
4. **comparison** — Sticky plan strip over long ruled category tables.
5. **objection handling** — Split FAQ section with expandable gray answers.
6. **closing call** — Inset gray invitation panel.
7. **resources** — White resource footer with utility row.

**Transfer:** Keep audience fit and price immediately legible, then progressively reveal operational detail.

### Company story: explain a point of view and put people behind it

1. **mission** — Black split opening with luminous exploded plates and substantial prose.
2. **quantified proof** — Small ruled milestone strip.
3. **social proof** — White rounded-top partner transition.
4. **human proof** — Long searchable directory in a pale rounded stage.
5. **closing call** — Centered white invitation and black capsule.
6. **resources** — Inverted black resource footer.

**Transfer:** Keep the company's story distinct from a product pitch through material contrast and human-scale information.

## Writing

Technically fluent, direct and encouraging. Confidence comes from describing what the tools actually do, with brief human reassurance rather than grandiose language.

**Do not copy:** Do not reuse Expo names, logo shapes, proprietary artwork, customer identities, quotations, claimed usage numbers, pricing, affiliations or compliance claims. Replace these with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your, particularly their app, team or users. Use we and our for human support and company intent, and the product name when identifying a concrete capability.
- **Rhythm:** Short outcome headlines alternate with more specific explanatory sentences. Two-line headlines are common; support typically contains one to three compact sentences. Technical detail is allowed when it explains a task or consequence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact category statement or a direct question about the reader's real situation. | 3–10 words | “Agentic mobile infrastructure”<br>“How is your app doing in production?” |
| Capability title | Verb plus concrete outcome, often grounded in the reader's work. | 4–10 words | “Get your app on every device”<br>“See which screen is slowing things down.” |
| Supporting explanation | Name the mechanism, then clarify a practical benefit or remove a barrier. | 1–3 short sentences | “Cloud simulators your coding agent can drive on demand. It runs your app, verifies its own work, and attaches screenshots, recordings, and logs as proof. No Mac required.” |
| Primary action | Plain verb with a low-friction destination. | 2–5 words | “Get started”<br>“Talk to our team” |
| Technical chapter | Describe a specific operation and where it happens; retain accurate platform terms. | 10–20 words | “Deploy your app to the web and host API routes in one command.” |
| Closing call | Compressed imperative or preventive outcome, less detailed than the preceding proof. | 3–9 words | “Find it before your users do”<br>“Build beautiful native apps” |

**Words and phrasing to use:** build; ship; run; see; your users; in one command; real sessions; from a single codebase; no prior knowledge needed

**Avoid:** revolutionary; unparalleled; synergy; unlock limitless potential; effortlessly transform everything

**Rules:**

- Lead with the work the reader can accomplish, not an abstract adjective.
- Make technical claims specific enough to connect to an interface artifact or an operation.
- Use a short reassuring sentence after a dense explanation when it removes a real obstacle.
- Keep labels in sentence case; reserve uppercase for small mono technical captions.
- Distinguish direct adoption from human-assisted adoption using plain action labels.

## Do's and Don'ts

### Do

- Keep the default 48px opening at weight 600 and -1.2px tracking.
- Use 40px corners on the main pale capability stages and 16px corners on bordered quote cards.
- Keep usable desktop content at 1280px inside the 1328px padded wrapper.
- Pair the 40px black opening capsule with a gray companion and an 8px gap.
- Use 64px interiors and 48px media-to-copy separation for roomy feature cards.
- Preserve a radiant symbol, localized colored light and a tactile rounded-square device in the landing-page visual vocabulary.
- Stage interface proof as crisp floating plates with thin edges and soft elevation.
- Let verified metric sentences use 64px type and inline objects rather than a conventional stat grid.

### Don't

- Do not promote the blue newsletter color into every primary action; the main conversion color is black.
- Do not add a heavy drop shadow to the 40px-radius pale stages; depth belongs to their objects.
- Do not set every page headline at 700; that weight is a pricing variant.
- Do not use 32px capability type for long explanatory paragraphs; support remains 14px or 16px.
- Do not turn each 256px comparison cell into a separately rounded card; the table relies on continuous rules.
- Do not use the black company shell as the default landing-page theme.
- Do not turn small mono captions into widely tracked decorative headline typography.
- Do not show large unframed stock photos where a product artifact or a sculptural tool should provide proof.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.15s color/background transitions with cubic-bezier(.4, 0, .2, 1); selected cards use 0.3s.
- The customer icon strip declares a 30s linear infinite carousel.
- Colored light layers declare 11s, 14s and 9s ease-in-out loops, with negative delays on the latter layers; a status pulse uses 2.2s linear infinite.
- The workflow explainer includes an autoplay pause/resume control.

**Transfer:**

- Keep interaction motion concentrated in color changes and small icon translations; preserve the slow moving light and icon-strip character for signature scenes.
- Offer the playback affordance when a process illustration cycles through multiple states.

**Unknown:**

- Exact trajectories and settled scroll-animation behavior are unspecified; no additional timing or easing is prescribed.

### Responsive

**Observed:**

- The main wrapper uses 16px side padding at narrow widths and 24px at desktop.
- Capability grids declare one column before the medium-width two-column version; gutters grow from 24px to 40px to 64px.
- The quote field declares one, two, three and four columns across increasing widths.
- The main link cluster is hidden below the large layout; product detail rows declare a stacked narrow layout.
- The closing object uses a narrow-screen width capped at 400px, growing to 535px at desktop.

**Transfer:**

- On narrow screens keep the opening's promise and actions together, move the symbol into its own stage and place support beneath; do not squeeze three columns.
- Stack paired cards while preserving object scale relative to their text. Keep wide UI scenes clipped or simplified so their primary result remains recognizable.
- Reduce long chapter layouts to headline, explanation, proof artifact and concrete operation in that reading order.

**Unknown:**

- Mobile renders and exact menu behavior are not established. Narrow-screen ordering guidance is a transfer recommendation, not an additional measured layout.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
