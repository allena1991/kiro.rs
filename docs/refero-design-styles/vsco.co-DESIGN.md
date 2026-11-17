# VSCO — craft in color blocks

## Overview

An assertive editorial style that pairs utilitarian grotesk typography with richly human photography. White and near-black fields alternate with sky blue, hot orange and golden yellow, while small rainbow accents mark premium offers. It suits creative tools and connected product ecosystems: expansive at the section level, practical and fairly dense inside cards and navigation.

### Essentials

- Headlines have the compressed impact of a photographic magazine cover: uppercase grotesk at 100px/90px for the opening promise and 54px/50px for major chapters, weight 500, normal tracking.
- The default opening is a white typographic statement, not a device billboard: 40px side gutters, a 1200px headline measure, 29px support text, and two 40px pills; a near-black image rail enters within the first 900px.
- Actions are small labels inside long capsules: 13px/14.3px, weight 600, 0.1em tracking, uppercase, 28px horizontal padding. Gold marks the main opening action; black and outlined pills carry the rest.
- Color belongs to entire benefit chapters rather than scattered decoration: blue #7bbce0, orange #ff6a2f and amber #ffa72a fill edge-to-edge 710px split panels. These colored chapters occupy roughly one quarter of a long ecosystem page; the remainder is predominantly white, gray, black and photography.
- Product proof is photographic, not floating on empty gradients: a crisp image or simplified interface sits over a softened enlargement of the same scene, commonly occupying half a split chapter or a 875px-wide demonstration.
- Human proof becomes a monumental image surface: tall 440px-wide portrait stories with 36px quotes and a 600px monochrome contact-sheet statement. Include the contact-sheet device on a new landing page; use makers, users, workspaces or tangible outcomes when portraits are unavailable.
- Premium offers have a narrow spectral signature: lime through yellow and orange into magenta on a 40px pill, with a black offer card or red photographic banner. Keep the rainbow concentrated in these small conversion details rather than tinting every component.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Spectral orange | `#ff6600` | `--color-spectrum-orange` | accent | Orange middle of premium action gradient. |
| Spectral yellow | `#ffc500` | `--color-spectrum-yellow` | accent | Yellow middle of premium action gradient. |
| Spectral lime | `#ade504` | `--color-spectrum-lime` | accent | Lime end of premium action gradient. |
| Spectral pink | `#e61e7c` | `--color-spectrum-pink` | accent | Magenta end of premium action gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Opening gold | `#ffbc3c` | `--color-action-gold` | action | Main action in the white opening. |
| Work amber | `#ffa72a` | `--color-work-amber` | background | Full split benefit panel with black type. |
| Vivid orange | `#ff6a2f` | `--color-community-orange` | background | Full split benefit panel with black type. |
| Banner red | `#c42304` | `--color-premium-red` | background | Solid-to-transparent left backing in the premium ecosystem banner. |
| Recommendation gold | `#edba58` | `--color-badge-gold` | surface | Small recommended-tier badge. |
| Craft blue | `#7bbce0` | `--color-craft-blue` | background | Full split benefit panel with black type. |
| Badge blue ink | `#386584` | `--color-badge-ink` | text | Text within the ice-blue badge. |
| Badge ice | `#e9f8ff` | `--color-badge-blue` | surface | Business-tier badge background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Primary type on light fields, solid actions, and the premium card. |
| Near-black canvas | `#111111` | `--color-canvas-dark` | background, text | Tool rail and dark product-page canvas. |
| Secondary gray | `#737373` | `--color-muted` | text | Secondary notes on light backgrounds. |
| Pale rule | `#e6e6e6` | `--color-rule-light` | border, surface | Footer divider and light segmented controls. |
| Light card edge | `#e6e6e6` | `--color-card-edge` | border | Visible 10% black edge over white; use rgba(0,0,0,0.1) for the border. |
| Soft gray | `#f2f2f2` | `--color-canvas-soft` | background, surface | Membership band and light business-product and pricing canvases. |
| White paper | `#ffffff` | `--color-paper` | background, text, surface, border | Default opening, editorial sections, light footer, cards and reversed type. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Offer blue | `#0097e8` | `--color-education-blue` | background | Inset secondary offer banner beside photography. |
| dark template libraries | Charcoal panel | `#1c1c1c` | `--color-panel-dark` | surface | Content backing beneath template previews. |
| dark product pages | Dark rule | `#404040` | `--color-rule-dark` | border | FAQ separators on near-black. |
| dark product pages | Reversed secondary gray | `#aaaaaa` | `--color-muted-dark` | text | Secondary footer text on dark backgrounds. |
| light product and pricing pages | Gray rule | `#c0c0c0` | `--color-rule-mid` | border | Light FAQ and comparison-table separators. |

## Typography

- **VSCO Gothic** — All marketing headings, paragraphs, navigation and labels. Direct neo-grotesk with plain terminals, compact uppercase settings and a practical regular text cut. OpenType features: "clig" 0, "liga" 0. If unavailable, use **Roboto**. Use 400–700; preserve normal tracking in headlines and compare line breaks before adjusting width. Font stack: "VSCO Gothic", "Roboto", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | VSCO Gothic | 500 | 100px | 0.9 | normal, uppercase | fixed | Primary ecosystem promise on the white opening. |
| heading-lg | VSCO Gothic | 500 | 54px | 0.926 | normal, uppercase | fixed | Major chapter headings, product hero names and closing image statements. |
| editorial-title | VSCO Gothic | 500 | 50px | 0.926 | normal, uppercase | fixed | Large text over narrow editorial image panels. |
| portrait-quote | VSCO Gothic | 400 | 36px | 1 | normal | fixed | Quotes over tall human portraits. |
| plan-title | VSCO Gothic | 500 | 36px | 1 | normal | fixed | Plan names and monthly price strings. |
| lead | VSCO Gothic | 400 | 29px | 1.14 | normal | fixed | Opening support, FAQ questions, introductory statements and feature-card titles. |
| heading | VSCO Gothic | 500 | 29px | 1 | normal, uppercase | fixed | Capability headings, support blocks and FAQ section labels. |
| body-lg | VSCO Gothic | 400 | 24px | 1.2 | normal | fixed | Benefit chapter text and plan descriptions; inline links share the recipe. |
| eyebrow | VSCO Gothic | 600 | 16px | 1.2 | 0.1em, uppercase | fixed | Top labels on editorial photographic panels. |
| body | VSCO Gothic | 400 | 15px | 1.24 | normal | size clamp(14px, 1rem + 0.5vw, 1.5rem) | Compact explanatory text, feature descriptions, footer navigation and support copy. |
| nav | VSCO Gothic | 500 | 15px | 1.5 | 0.08em, uppercase | fixed | Global navigation categories. |
| plan-detail | VSCO Gothic | 400 | 15px | 1.4 | normal | fixed | Plan feature lists beneath the large description. |
| action | VSCO Gothic | 600 | 13px | 1.1 | 0.1em, uppercase | fixed | Main 40px button labels. |
| label | VSCO Gothic | 600 | 13px | 1.2 | 0.1em, uppercase | fixed | Footer column labels and compact directional links. |
| badge | VSCO Gothic | 600 | 11px | 0.9 | 0.05em, uppercase | fixed | Small tier recommendation labels. |
| tab | VSCO Gothic | 600 | 11px | 1.1 | 0.1em, uppercase | fixed | Tool-rail category tabs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| creative planning feature pages | wide-quote | VSCO Gothic | 400 | 48px | 1 | normal | fixed | Long testimonial text over a full-width image. |
| pricing pages | pricing-display | VSCO Gothic | 500 | 44px | 0.9 | normal, uppercase | fixed | Compact two-line pricing introduction. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headlines compress vertically, not through negative tracking: preserve normal letter spacing at 29px–100px and use medium rather than heavy bold.
- Sentence-case body and quote text is markedly softer than the capital headlines. Small capitals gain 0.1em tracking; the navigation uses 0.08em and tier badges 0.05em.
- Large text is left aligned, usually with a constrained measure that creates two or three emphatic lines. The 100px display is not the default for individual product hero names.
- The body size has a viewport formula; maintain that rule while preserving the compact body-to-heading hierarchy.

## Layout

**Density:** Airy chapters with compact interiors: long 150px pauses separate demonstrations, while cards and lists use much smaller gaps.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight pricing-card gutter and compact interface-adjacent groups. |
| 12px | Paired opening action gap and eyebrow-to-title spacing. |
| 16px | FAQ row vertical padding and quote-to-attribution separation. |
| 20px | Heading-to-support space and standard three-column gutter. |
| 24px | Tool-tab separation and footer heading-to-link-stack gap. |
| 30px | Plan-card padding and support-to-media spacing. |
| 32px | Opening support-to-actions gap and portrait content padding. |
| 40px | Global side gutters, footer padding and large internal groups. |
| 56px | Vertical inset within colored benefit blades. |
| 60px | White opening top inset. |
| 100px | Membership band vertical padding and pricing-page section gaps. |
| 150px | Major editorial chapter separation on long landing and product pages. |

### Containers and grids

- **global container**: max width 1440px · side padding 40px. Centered large container with 1360px usable width at a 1440px viewport; media bands may bleed to the edges.
- **opening measure**: max width 1200px. Two-line display; the support line below is constrained to 900px.
- **section measure**: max width 670px. Major chapter title and large supporting paragraph measure.
- **three-up grid**: 3 columns · gap 20px. Three 440px cards across the desktop content area.
- **benefit blade**: 2 columns · gap 0px. Two equal 720px halves at desktop, one colored text field and one edge-to-edge image stage.
- **plan grid**: 3 columns · gap 8px. Three 448px plan cards spanning the desktop content area.
- **footer links**: max width 840px · 4 columns · gap 20px. Four 195px link columns on the right, balanced by a broad brand-and-action area on the left.
- **demonstration split** (only for individual product pages): 2 columns · gap 40px. A wide 875px media area balances a narrow prose column; alternate media alignment.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | plan cards | 10px |
|  | badges | 4px |
|  | standard editorial media | 0px |
| batch-editing demonstrations | demo thumbnails | 6px |

## Surfaces and depth

### Surfaces

#### White editorial canvas · level 0

**Use:** Default marketing opening, human stories, support area and footer.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, untextured paper field. Strong contrast comes from neighboring dark and colored chapters rather than elevation.

**Transfer:** Let type and media provide structure; keep this the default light surface.

#### Dark canvas · level 0

**Use:** Tool discovery rail and immersive product storytelling.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** True-black cards and photographic media sit against a slightly lighter near-black canvas.

**Transfer:** Use a continuous dark field for a tool-focused variant rather than outlining every section.

#### Membership field · level 0

**Use:** Plan comparisons and related purchase content.

**CSS:** `background: #f2f2f2; color: #000000`

**Observed:** A soft-gray full-width field backs white and black offer cards.

**Transfer:** Use the subtle shift from white to distinguish purchase decisions.

#### Color blade · level 0

**Use:** Large outcome-oriented split chapters.

**CSS:** `background: #7bbce0; color: #000000`

**Observed:** Blue, vivid orange and amber variants each fill a whole 710px chapter, with half given to imagery.

**Transfer:** Assign one color to a whole benefit, not to a collection of little cards.

#### Plan paper · level 1

**Use:** Ordinary membership tiers.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 10px; box-shadow: none`

**Observed:** One premium tier reverses to black with a white border and white text.

**Transfer:** Distinguish tiers by inversion and labels rather than shadows.

#### Premium banner fade · level 1

**Use:** Integrated-system promotional banner.

**CSS:** `background: linear-gradient(90deg, #c42304, #c42304 29%, rgba(196, 35, 4, 0) 44%)`

**Observed:** A solid red text zone dissolves into a person photographed against orange-red light; thin white outlined service panels stack between text and person.

**Transfer:** Blend a readable color field into a real scene or well-lit product object.

#### Template panel · level 1

**Only for:** dark template libraries

**Use:** Text area below preview imagery.

**CSS:** `background: #1c1c1c; padding: 20px`

**Observed:** Square-edged dark cards, not elevated panels.

**Transfer:** Separate previews from description with a small tonal step.

## Components

### Global navigation

**Use:** Primary site wayfinding.

**CSS:** `background: #ffffff; color: #000000; height: 100px; padding: 0px 40px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `nav` — VSCO Gothic 500 · 15px/1.5 · tracking 0.08em · uppercase

**Observed:** Sticky shell, 50px symbol at left, category links with small downward chevrons, login and trial pills at right. Category groups have 36px gaps. Dark product pages invert the shell to black and use white controls; header pills are 32px high rather than the main 40px size.

**Transfer:** Use the new brand's own compact symbol and a short taxonomy; retain the horizontal editorial bar.

### Gold action

**Use:** Primary conversion in the white opening.

**CSS:** `background: #ffbc3c; color: #000000; border-radius: 9999px; height: 40px; padding: 2px 28px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — VSCO Gothic 600 · 13px/1.1 · tracking 0.1em · uppercase

**Observed:** Content-width capsule, paired with the Black action rather than spanning the opening width.

**States:** Declared: hover background-color #ffcc69; focus-visible not specified; active outline 0px.

### Black action

**Use:** Secondary opening destination and primary actions on light sections.

**CSS:** `background: #000000; color: #ffffff; border: 2px solid #000000; border-radius: 9999px; height: 40px; padding: 2px 28px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — VSCO Gothic 600 · 13px/1.1 · tracking 0.1em · uppercase

**Observed:** Content-width in editorial areas; plan-card actions stretch across the available inner width. Dark product pages use a white-filled inverse for the strongest action.

### Outline action

**Use:** Exploration and secondary conversion on light or colored fields.

**CSS:** `background: transparent; color: #000000; border: 1px solid #000000; border-radius: 9999px; height: 40px; padding: 2px 28px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — VSCO Gothic 600 · 13px/1.1 · tracking 0.1em · uppercase

**Observed:** Dark fields use a white border and white text. Directional text links elsewhere use an upper-right arrow instead of a pill.

**States:** Declared: hover background-color black, color white, border-color #000000; focus-visible not specified; active outline 0px.

### Premium action

**Use:** Purchase or exploration of the integrated premium tier.

**CSS:** `background-image: linear-gradient(291.72deg, #e61e7c 3.48%, #ff6600 14.14%, #ffc500 32.06%, #ade504 48.97%, #ade504 51.03%, #ffc500 67.94%, #ff6600 85.86%, #e61e7c 96.52%); background-size: 200% 100%; background-position: 100% 50%; color: #000000; border-radius: 9999px; height: 40px; padding: 2px 28px; font-weight: 700`

**Text style:** `action` — VSCO Gothic 600 · 13px/1.1 · tracking 0.1em · uppercase

**Observed:** A small spectral accent within a black card or red banner. The label is visually heavier than other actions. A compact banner variant is content-width; pricing variants fill the card's inner width.

**Transfer:** Reserve this treatment for a single highest-level connected offer.

### Plan card

**Use:** Comparable tiers with a clear premium inversion.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.1); border-radius: 10px; padding: 30px; display: flex; flex-direction: column; justify-content: space-between; gap: 40px`

**Text style:** `plan-title` — VSCO Gothic 500 · 36px/1

**Observed:** Title and badge share the top row, followed by a 24px description, optional billing selector and 36px price, then action and checkmarked benefits. In the ecosystem overview, actions anchor low; in dedicated pricing they sit above benefits. White cards use black actions; the black premium card uses Premium action. Cards are equal height within their row.

**Transfer:** Keep comparable content slots aligned and explain benefits in brief checkmarked lines.

### Tier badge

**Use:** Small recommendation marking next to plan names.

**CSS:** `background: #e9f8ff; color: #386584; border-radius: 4px; padding: 4px 6px; display: flex; align-items: center`

**Text style:** `badge` — VSCO Gothic 600 · 11px/0.9 · tracking 0.05em · uppercase

**Observed:** Ice-blue business badge and gold popular badge appear beside titles. These are tiny rectangular markings, not large promotional ribbons.

### FAQ row

**Use:** Objection handling with minimal visual furniture.

**CSS:** `border-bottom: 1px solid #c0c0c0; padding: 16px 0px`

**Text style:** `lead` — VSCO Gothic 400 · 29px/1.14

**Observed:** A full-width question and small right-aligned chevron inside an approximately 90px collapsed row. Heading above uses the smaller uppercase Heading recipe. Dark product variants replace the divider with #404040 and use white question text.

**Transfer:** Let long questions wrap naturally; keep the chevron on the far right.

### Editorial photo panel

**Use:** Campaign or story navigation presented as magazine covers.

**CSS:** `background: #000000; color: #ffffff; padding: 40px; position: relative`

**Text style:** `editorial-title` — VSCO Gothic 500 · 50px/0.926 · uppercase

**Observed:** Portrait-format 546px by 675px panel with full-bleed photography behind an eyebrow and headline at top, a small white capsule at bottom. Panels meet without gutters in an overflowing horizontal rail.

**Transfer:** Use one bold story per image, not a stack of small links.

### Tool rail tab

**Use:** Compact filtering above horizontal image cards.

**CSS:** `color: #ffffff; border-bottom: 2px solid #ffffff; padding: 8px 0px; position: relative`

**Text style:** `tab` — VSCO Gothic 600 · 11px/1.1 · tracking 0.1em · uppercase

**Observed:** Selected state is a simple underline. Unselected labels are muted and have a transparent underline. Tabs are spaced 24px apart; cards below have 20px gutters.

### Footer directory

**Use:** Dense but orderly ending and secondary conversion.

**CSS:** `background: #ffffff; color: #000000; padding: 40px; display: flex; flex-direction: column; gap: 40px`

**Text style:** `body` — VSCO Gothic 400 · 15px/1.24

**Observed:** Wide brand column on the left with two outlined actions near its bottom; four link columns on the right with Label headings and compact Body links. A pale horizontal rule separates a small legal and language row. Dark product pages invert the directory to black with white links. The business-product variant is shorter: a stacked 54px outcome headline at left, three link columns at right, brand and actions below.

**Transfer:** Match directory depth to the new site's information architecture, preserving the unusually spacious brand column.

## Imagery and graphics

### Photographic product stage

**Use:** Benefit blades and product demonstrations.

**Observed:** A clear central photo, device-less UI panel or before-and-after window sits over a blurred enlargement of the same source image. Backdrops retain the original scene's navy, warm brown, muted green or orange tones. Foreground imagery is sharp, large and often clipped by the stage edge; outside rectangular media stays square while inner UI can have rounded corners.

**Transfer:** Photograph the new product in use or show a tangible result. Minimum equivalent: a sharp result image and one legible functional overlay over a softened duplicate, not a generic laptop mockup.

**Build:** Place one object-fit:cover image as the background. Duplicate it in an oversized absolute layer with blur(24px), clipped to the stage. Put a sharp centered result panel above it, with a thin rgba(255,255,255,0.7) outline where necessary. A comparison may use two image halves with a vertical 1px seam; keep UI labels subordinate.

### Portrait proof

**Use:** Human testimonials and documentary video posters.

**Observed:** Real practitioners fill tall 440px by 788px cards. Faces and tools dominate the upper area; white quotes sit over a darker lower area with attribution and a small story action. Color remains photographic rather than uniformly tinted.

**Transfer:** Choose users engaged in their own work, with varied environments and natural expressions. If people are unavailable, show hands at work or contextual results, maintaining a large human-scale subject.

### Monochrome contact sheet

**Use:** Signature brand statement surface, usually near the ending.

**Observed:** A 1440px by 600px band presents eight closely framed portraits in four columns and two rows with narrow pale gutters. Photographs are grayscale and darkened; a white 54px uppercase statement overlays the upper-left area.

**Transfer:** Create a contact sheet of users, makers, workspaces or real outputs. Keep the repeated crops tightly framed and the overlaid statement about the new audience's ambition.

**Build:** Use a four-column, two-row CSS grid with approximately 10px gutters and equal image cells. Apply grayscale(1) to images and a black overlay around 40% opacity, tuning for readable white type. Overlay the heading at 40px inset; keep the band 600px high at desktop.

### Spectral announcement strip

**Use:** Compact announcement above navigation and premium visual identity.

**Observed:** A shallow 56px strip runs lime and yellow at the left through orange to pink-red at the right with fine grain. Small black copy and a black pill sit on it; the spectral identity recurs much more narrowly in premium actions.

**Transfer:** Use a specific new launch or offer message. Keep color saturated but the strip shallow.

**Build:** Create a horizontal lime-to-yellow-to-orange-to-magenta gradient using the spectral palette. Add an SVG feTurbulence noise layer at low opacity over it for fine grain; avoid large cloudy blobs. Align copy and the small action inside 40px gutters.

### Integrated offer scene

**Use:** Compact ecosystem cross-sell banner.

**Observed:** A 400px-high inset banner has red typography backing on the left, white outlined stacked service cards in the middle, and a sharply lit cut-out person at right over orange-red photography. The cards may run beyond the top and bottom of the banner and connect by dotted lines.

**Transfer:** Replace the person with a photographed user or tangible product. Use two or three outlined outcome cards to explain connected functions.

**Build:** Layer an orange-red scene under Premium banner fade. Put the headline and action in the left half; place a vertical stack of 320px-wide outlined 10px-radius cards in the middle with 2px white borders and short dotted connectors. Position the photographic subject at the right edge in front of the stack.

### Collaborative board demonstration

**Only for:** creative planning feature pages

**Use:** Hero and three-step feature demonstrations.

**Observed:** Dark dotted workspaces hold overlapping photos of fashion, shoes, courts, interiors and food. Slim toolbars, invite panels, colored collaborator cursors and comment bubbles communicate a working canvas. The surrounding marketing page stays near-black, not dotted.

**Transfer:** Show a few real artifacts in a convincing workflow, with one legible collaboration moment. Treat cursor colors and toolbar details as product UI, not general brand decoration.

**Build:** Inside the demo only, use a dark field with a repeating radial dot pattern spaced about 20px apart. Layer three rectangular content images at different sizes, then add one small toolbar and one comment card. Keep dots low contrast and content dominant.

### Icons

**Observed:** Small monochrome utility glyphs: 16px chevrons and link symbols, 20px arrows, and 23px outlined checkmarks with 2px strokes. Icons sit inside actions or at card bottoms rather than acting as colorful illustrations.

**Transfer:** Use simple geometric utility icons in the surrounding text color; retain small arrow and checkmark accents, and reserve multicolor marks for actual product UI.

## Section recipes

How recurring sections are built.

### First screen: Typographic promise opening

**Observed:** A 56px Spectral announcement strip sits above the 100px Global navigation. The White editorial canvas then carries a left-aligned two-line uppercase Display headline in a 1200px measure, beginning after 60px of top breathing room. A 900px-wide Lead support paragraph follows after 20px, then Gold action and Black action after 32px with a 12px gap. This white opening is 438px high below navigation, ending around two thirds of the first screen. Dark canvas follows immediately: a 54px two-line heading, small Tool rail tabs and the top edges of image cards are visible within the first 900px. The large photographic film and deeper benefit chapters fall below the fold. The first impression is type and contrast, not a floating central object.

**Transfer:** Write a broad audience promise with the new product's concrete job, then introduce a real result or demonstration rail below it. If media is limited, use three carefully composed result examples rather than a decorative hero object. Individual product variants open with a 500px photographic stage, left-side 54px product heading and 29px support plus white actions; pricing variants use a 44px heading above immediately visible plan cards.

**Avoid:** Do not center the headline over a gradient, make the opening a full-screen device mockup, or push all product imagery below the first screen.

**Text style:** `display` — VSCO Gothic 500 · 100px/0.9 · uppercase

### Section heading pair

**Observed:** Heading-lg or Heading sits above a support line with 20px separation. Large chapter introductions keep text near a 670px measure; explanatory product introductions may use a 900px Lead measure. Everything aligns with the 40px page gutter.

**Transfer:** Choose the larger heading for a major outcome chapter and the smaller uppercase heading for a practical tool or help section.

**Text style:** `heading-lg` — VSCO Gothic 500 · 54px/0.926 · uppercase

### Alternating color blade

**Observed:** Color blade is a 710px-high, equal-width split. Text uses 56px vertical inset and 40px horizontal gutters, Heading-lg above Body-lg paragraphs with underlined inline product links; Outline action anchors near the bottom. Photographic product stage fills the other half. Alternating image-left and image-right gives long pages an editorial rhythm.

**Transfer:** Use one whole panel per customer outcome, preserving the shared baseline and full-bleed media treatment. Keep the colored field as a major signature device without requiring a fixed number of chapters.

**Text style:** `heading-lg` — VSCO Gothic 500 · 54px/0.926 · uppercase

### Tool discovery rail

**Observed:** Dark canvas carries a constrained two-line Heading-lg, Tool rail tabs, then a clipped horizontal strip of 272px-wide image cards with 20px gutters and compact Label captions. A circular 48px next control overlaps the rail's right edge.

**Transfer:** Offer a handful of concrete entry points or fresh capabilities; let photography carry the browsing appeal.

### Plan comparison

**Observed:** Membership field with 100px vertical breathing room, a Heading-lg introduction and three Plan cards separated by 8px. One black premium card contrasts with two white cards. Dedicated pricing uses a smaller 44px introduction, visible prices and billing controls, then a wide blue secondary-offer banner. Its comparison table has a black header, light-gray category rows and white detail rows divided by 1px gray rules.

**Transfer:** Use the card band to establish meaningful choice; reserve a detailed expandable matrix for a dedicated purchase page.

### Alternating product proof

**Observed:** On individual product pages, 875px by 486px photographic demonstrations alternate left and right against the page canvas. The narrow text column uses a 29px heading, compact 15px body and a small action; chapters are separated by 150px. A later 1360px-wide media demonstration can expand the proof.

**Transfer:** Show a sequence of distinct jobs rather than changing the same interface screenshot's caption. Use the dark variant for immersive creative tooling and soft-gray with white cards for operational tooling.

### Editorial and human proof

**Observed:** Editorial photo panels meet without gutters in a horizontal rail. Portrait proof uses three 440px-wide cards with 20px gutters, preceded by a major uppercase heading; a short explanatory line and Outline action may follow. The photographs are the surface, not thumbnails above white text boxes.

**Transfer:** Use credible real stories and outcomes with a clear subject; let copy occupy the image only where it remains legible.

### FAQ and final statement

**Observed:** A 29px uppercase heading introduces full-width FAQ rows. After a generous chapter gap, Monochrome contact sheet carries a 54px white statement, followed directly by Footer directory. Light marketing and pricing pages end with a white directory; dark tool pages end with a black directory. The business-product variant instead uses a 500px monochrome working scene with two actions, then a short white footer with a stacked outcome headline.

**Transfer:** Resolve practical objections, then close with an audience-level visual statement rather than another generic boxed CTA. Adapt the directory's size to the new site while keeping a distinct visual ending.

**Text style:** `heading-lg` — VSCO Gothic 500 · 54px/0.926 · uppercase

### Template library and walkthrough

**Only for:** creative planning feature pages

**Observed:** A small uppercase heading and compact paragraph lead a horizontal 440px-wide template rail. Preview images sit above Template panel descriptions and small directional labels. Nearby full-width photographic quotes use Wide-quote over a black-to-transparent overlay. A practical step list and large video walkthrough explain adoption before FAQ.

**Transfer:** Use previews to make starting easy, then show a realistic short path through the workflow rather than substituting a decorative gallery.

## Page flow

**Storyline:** Broad promise → tangible product and human proof → outcome chapters or capability demonstrations → offer and adoption details → objections → photographic audience statement and directory.

### Introduce a connected product ecosystem

1. **Promise** — White typographic opening with a compact announcement and contrasting actions.
2. **Discovery** — Dark tabbed image rail and full-width documentary film.
3. **Offer framing** — Soft-gray band with three contrasting plan cards.
4. **Capability chapters** — Alternating colored split blades with large photographic product stages.
5. **Connected value** — Red inset offer scene with outlined service cards.
6. **Editorial and social proof** — Cover-like story rail and tall portrait testimonials.
7. **Support and closing** — Three practical support columns, monochrome contact sheet, then white directory footer.

**Transfer:** Borrow the alternation between explicit product choices and aspirational human outcomes, not the precise number of sections.

### Help visitors choose and understand a subscription

1. **Pricing** — Compact heading and three aligned plan cards with prices, trials and billing choices; wide blue secondary offer.
2. **Social proof** — Wide photographic testimonial carousel.
3. **Comparison** — Expandable category matrix with a black plan header and ruled detail rows.
4. **Objection handling** — Light FAQ rows.
5. **Closing** — Monochrome contact sheet followed by the full white directory.

**Transfer:** Move decision-making up front, then provide progressively deeper detail without giving every feature its own marketing chapter.

### Explain a focused professional creative tool

1. **Product promise** — Photographic hero with a large result scene and smaller stacked examples.
2. **Product demonstration** — Introductory statement followed by alternating wide demos and narrow explanations.
3. **Adoption** — Large app demonstration and download guidance.
4. **Connected value** — Red integrated-offer banner.
5. **Capability breadth** — Three-up image-led tool cards and compact utility-link grid.
6. **Objection handling** — Dark FAQ rows.
7. **Closing** — Monochrome contact sheet and black directory.

**Transfer:** Lead with the tool's visible result, prove a few major jobs, then reveal breadth and resolve questions.

### Sell a business workflow product and reduce switching friction

1. **Promise** — Shallow service announcement and photographic hero with operational UI overlays and two actions.
2. **Capability breadth** — Six white feature cards on gray, then a compact utility grid.
3. **Social proof** — Three quote cards and a paired photographic reassurance banner.
4. **Adoption support** — Three setup and transition cards plus a large presenter walkthrough.
5. **Pricing** — One white purchase card paired with a vivid photographic scene.
6. **Objection handling** — Light FAQ rows.
7. **Closing** — Monochrome working scene with actions and a short white footer with a stacked 54px benefit statement.

**Transfer:** Make transition support and concrete workflow benefits as prominent as features; use the lighter operational variant.

### Teach a collaborative creative feature

1. **Promise** — Dark hero with layered board artifacts, collaborator cursors and left-aligned product introduction.
2. **Context and social proof** — Introductory statement, compact motion demonstration and full-width photographic quote.
3. **Capability chapters** — Wide demo, then three parallel workflow columns with tall illustrations.
4. **Adoption** — Template rail, second photographic quote, practical step list and video walkthrough.
5. **Objection handling** — Dark FAQ rows.
6. **Related value** — Three photographic related-feature cards and a small return link.
7. **Closing** — Monochrome contact sheet and black directory.

**Transfer:** Pair the freedom of an open creative tool with tangible examples, templates and concise first-use instructions.

## Writing

Confident, craft-aware and encouraging without being whimsical. Broad audience ambition is paired with plain descriptions of what the tools actually do.

**Do not copy:** Do not reuse VSCO names, logos, source photography, named product features, testimonials, prices, trial terms, user counts or claims of market leadership. Source examples below illustrate sentence construction only.

- **Addressing the reader:** Speak to the reader as you and your. Refer to the product by name when explaining what it does; use we sparingly for commitments and support.
- **Rhythm:** Headlines are usually short, forceful phrases or two balanced clauses. Support copy is one or two direct sentences; feature paragraphs can be longer but stay concrete. Uppercase is a visual hierarchy device, not a reason to write in a shouting voice.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the audience's broad need or contrast a desired outcome with avoidable work. | 4–10 words | “Everything a Photographer Needs”<br>“Grow Your Business, Not Your To-Do List” |
| Chapter heading | Short active phrase naming a human outcome. | 3–6 words | “HONE YOUR CRAFT”<br>“FIND YOUR PEOPLE”<br>“MEET CLIENTS AND GET PAID” |
| Supporting line | Connect a tool's concrete job with a visible or practical benefit. | 1–2 sentences | “Finish editing a full photoshoot in seconds, not hours.”<br>“Allow your clients to schedule consults or book sessions completely unassisted.” |
| Primary action | Brief verb-led label, frequently clarifying cost or destination. | 2–4 words | “Try for Free”<br>“BROWSE ALL FEATURES” |
| Closing statement | A compact aspiration or paired benefit rather than a generic invitation. | 4–6 words | “WHERE PHOTOGRAPHERS TURN PRO”<br>“Book more. Work less.” |
| Feature explanation | Concrete operations in sequence, followed by the friction removed. | 2–4 short sentences | “No export, no re-uploading, no switching apps.”<br>“Turn individual ideas into a collective vision.” |

**Words and phrasing to use:** your craft; your look; your way; build; gather; refine; share; deliver; connected; workflow; from first step to final result

**Avoid:** revolutionary disruption; magic at your fingertips; supercharge everything; crush it; limitless possibilities; cutesy interface jokes

**Rules:**

- Lead with the outcome, then explain the mechanism in recognizable verbs.
- Use contrast such as minutes versus hours only when the new product can support it.
- Keep button labels actionable and specific; use directional labels for secondary editorial destinations.
- Treat AI as assistance to a human process, not as the main personality of the brand.
- Let customer stories sound like individual people rather than slogans.

## Do's and Don'ts

### Do

- Keep the opening Display at weight 500 and 0.9 line height; use width and line breaks to create impact.
- Preserve 40px desktop page gutters even when neighboring media bleeds to the viewport edges.
- Pair 40px capsule actions with 13px uppercase labels and 0.1em tracking.
- Give colored benefit blades an equal text/media split and 56px vertical text inset.
- Use 20px gutters for three-up imagery and the tighter 8px gutter for plan cards.
- Keep photographic subjects large enough to compete with 54px chapter headings.
- Use a 10px radius for plan cards but square external edges for editorial images.
- Retain the monochrome contact-sheet statement as a recognizable visual counterweight to saturated chapters.

### Don't

- Do not make every heading 100px; focused product names and chapter leads use 54px.
- Do not add negative tracking to imitate compressed headline line height.
- Do not turn all imagery into softly rounded SaaS cards; square photographic stages are fundamental.
- Do not spread the premium spectrum across body text, every icon or entire page backgrounds.
- Do not replace the black premium tier with an elevated white card and a large drop shadow.
- Do not treat 15px compact body copy as the opening support size; the opening uses 29px.
- Do not render every benefit as a tiny icon card; the signature chapters use 710px split surfaces.
- Do not end with a generic centered CTA card instead of the photographic statement and structured directory.

## Motion and responsive

### Motion

**Observed:**

- Declared color, border and opacity transitions use 0.45s cubic-bezier(0.215, 0.61, 0.355, 1).
- Premium actions declare background-position 0.85s.
- Horizontal image and template rails have next controls; video demonstrations use visible play or pause controls.

**Transfer:**

- Let capsule inversions and underline changes carry interaction feedback rather than introducing bouncy motion.
- Keep spectral motion confined to the premium action and preserve image-led rails as browsing devices.

**Unknown:**

- Exact scroll-reveal sequencing and video autoplay behavior are not established.
- Focus-visible styling is not established; do not suppress keyboard focus when implementing the style.

### Responsive

**Observed:**

- The declared CSS includes breakpoint families around 479px, 767–768px, 991–992px and wider desktop thresholds; only the 1440px composition is defined here.
- Body text declares clamp(14px, 1rem + 0.5vw, 1.5rem).

**Transfer:**

- On narrow layouts, stack the two halves of a benefit blade while retaining its single colored field and strong photo stage.
- Preserve the rail treatment for editorial covers instead of shrinking every cover to a small tile.
- Reduce display size enough to preserve intentional short lines and keep the supporting copy subordinate.
- Collapse the directory into readable groups while keeping the brand-and-action region distinct.

**Unknown:**

- Exact mobile gutter, headline sizes, navigation transformation and column-collapse thresholds are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
