# Bevel — daylight meets iridescence

## Overview

An optimistic, softly futuristic style for personal technology and products that make complicated information feel approachable. White space and pale blue, lilac and mint atmospheres surround large, tightly set system sans headlines, realistic devices and floating interface details. Dark charcoal chapters add depth without turning the whole experience into a dark interface; candid photography and everyday objects keep the polished technology human.

### Essentials

- Headlines feel like one compact promise, not an editorial masthead: centered 80px/1, weight 600, -0.03em tracking in the opening; 64px/1 with the same weight and tracking for major chapters.
- The opening is a daylight product theatre: an 8px outer inset, 24px rounded sky-to-cream backdrop, a compact floating navigation capsule, centered copy and a large overlapping device composition rising through the lower half of the first screen.
- Actions are small charcoal lozenges rather than big colored blocks: 46px high, 12px 18px padding, 128px radius, 16px/1.4 medium text and a 20px leading icon; the navigation version is 38px high.
- Color behaves like transmitted light: white remains the main canvas, pale blue-gray #ebf0f8 supports broad 24px-radius feature stages, and lilac, peach, pink and mint concentrate near their lower edges. A charcoal chapter is a bounded contrast, not the global theme.
- The product escapes its frame: oversized realistic devices and enlarged floating interface cards overlap, extend beyond stage edges and are clipped by the stage. Preserve this layered demonstration even without hardware by staging a crisp primary interface plane with two enlarged detail planes.
- Include a light phenomenon and a sculptural trust emblem: soft iridescent horizontal rays behind the main object, and a monumental low-contrast symbol on a mint-lit charcoal panel. Use abstract SVG ribbons and a simple extruded geometric emblem when bespoke renders are unavailable.
- The final invitation brings technology back into daily life: a centered 64px closing line, 24px support, one charcoal action, and a full-width white-background arrangement of useful objects around the product with soft contact shadows. A different product can use its own tools and contextual objects instead of devices.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Opening sky | `#d2e5ff` | `--color-sky` | background | Upper end of the daylight hero atmosphere. |
| Warm horizon | `#fff9ee` | `--color-cream` | background | Lower end of the hero gradient, warming the device stage. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep mint glow | `#2c7964` | `--color-trust-glow` | accent, background | Visible rgb(63,255,194) at 40% over charcoal, brightest at the outer lower edge of the trust panel. |
| Peach light | `#efc9bc` | `--color-peach` | accent | Visible rgb(244,108,65) at 40% over blue-gray, concentrated near the lower-right feature stage. |
| Mint light | `#c1ebee` | `--color-mint` | accent | Visible rgb(131,227,222) at 40% over blue-gray in feature-stage glow. |
| Lilac light | `#d7d2fb` | `--color-lilac` | accent, surface | Visible lilac at 40% over blue-gray; lower feature-stage glow. Source hue is rgb(185,166,255). |
| Pink light | `#f3cceb` | `--color-pink` | accent | Visible rgb(255,150,194) at 40% over blue-gray in a feature-stage glow. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#1f2025` | `--color-charcoal` | background, action, text | Primary actions, bounded dark chapters and dark trust stage. |
| Primary ink | `#222326` | `--color-ink` | text | Default headline and body text on light surfaces. |
| Secondary gray | `#79797c` | `--color-secondary` | text, link | Visible result of charcoal at 60% over white; support copy and navigation links. Keep the alpha recipe when the backing changes. |
| Dark secondary | `#a5a6a8` | `--color-dark-secondary` | text | White at 60% over charcoal for support text in dark chapters. |
| Blue-gray stage | `#ebf0f8` | `--color-card` | surface, text | Feature stages, review cards, secondary feature rows and light button text. |
| White | `#ffffff` | `--color-white` | background, text, surface | Default page canvas and text on charcoal; also the source of translucent navigation glass. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company mission openings | Blue steel type | `#adc3d4` | `--color-steel` | text | Second stop in the metallic gradient phrase. |
| company mission openings | Silver type | `#c2c9ce` | `--color-silver` | text | First stop in the subtly metallic gradient phrase. |
| company and recruiting pages | Detail gray | `#616265` | `--color-company-detail` | text | Portrait biographies and recruiting row titles. |
| company and recruiting pages | Soft gray | `#8b8c8f` | `--color-muted` | text | Support text on company and recruiting layouts. |
| company and recruiting pages | Faint rule | `#dee1e2` | `--color-rule` | border | Visible ink at 10% over frost canvas; list separators and culture-card outlines. |
| recruiting pages | Smoked frost | `#ebeeef` | `--color-culture-fill` | surface | Visible ink at 4% over frost canvas in culture cards. |
| company and recruiting pages | Frost canvas | `#f3f6f7` | `--color-company-canvas` | background | Cool background for narrative and recruiting content. |
| long-form company narratives | Letter edge | `#f9fafb` | `--color-paper-edge` | surface | Cool near-white edges of the letter panel. |

## Typography

- **-apple-system** — All marketing headlines, prose, navigation and action labels. A native neo-grotesk sans with open small text and compact, emphatic semibold display setting. If unavailable, use **Inter**. Use weights 400–700 with the role-specific tracking retained. Font stack: "-apple-system", system-ui, Inter, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | -apple-system | 600 | 80px | 1 | -0.03em | Centered opening promise, normally wrapping into two compact lines. |
| heading | -apple-system | 600 | 64px | 1 | -0.03em | Major section leads, feature-stage headlines and closing invitation. |
| support | -apple-system | 400 | 24px | 1.3 | normal | One or two lines beneath a large headline. |
| feature-title | -apple-system | 600 | 24px | 0.9 | -0.01em | Short titles in the secondary-feature selector. |
| body | -apple-system | 500 | 18px | 1.4 | 0.0094em | Secondary feature descriptions and footer links. |
| review-title | -apple-system | 600 | 18px | 1.3 | normal | Review titles and small footer group headings. |
| review-body | -apple-system | 400 | 18px | 1.3 | normal | Verbatim customer testimony and its metadata. |
| action | -apple-system | 500 | 16px | 1.4 | normal | Navigation links and primary action labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and recruiting pages | company-heading | -apple-system | 700 | 52px | 1.1 | 0.0033em | Mission opening, recruiting opening, company section leads and architectural closing invitation. |
| recruiting pages | culture-title | -apple-system | 600 | 24px | 1.1 | 0.007em | Titles within culture cards. |
| company and recruiting pages | company-support | -apple-system | 400 | 20px | 1.4 | 0.0085em | Centered company or recruiting section introductions and row locations. |
| long-form company narratives | letter-body | -apple-system | 500 | 19px | 1.5 | 0.03em | Long-form founder-style letter paragraphs. |
| recruiting pages | culture-body | -apple-system | 400 | 18px | 1.4 | 0.0094em | Descriptions within culture cards. |

**Notes:**

- Display and major headings tighten to -0.03em; body and action text do not inherit that tracking. Keep headings weight 600 rather than replacing them with extra-bold.
- The company/recruiting variant deliberately changes to 52px weight 700 with almost neutral tracking; do not average this with the product-marketing display.
- The 24px feature-selector title has a compressed 0.9 line height and is intended for short labels, not paragraphs. No viewport-based type formula is established.

## Layout

**Density:** Airy at section scale, compact within demonstrations: expansive 160px chapter breathing room surrounds tightly grouped copy and interfaces.

### Spacing

**Spacing system:**

- **step** 8px — Declared base spacing step; 16px is the companion declared token. Some local 12px, 20px and 28.8px values are intentional exceptions.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Small title-description and selector-item gaps. | fixed |
| 12px | Action icon-to-label gaps and review header spacing. | fixed |
| 16px | Main headline-to-support gap and column gutters. | calc(0.5 * clamp(1rem, 0.714rem + 1.429vw, 2rem)) |
| 24px | Copy-to-action spacing and feature-row padding. | fixed |
| 32px | Feature-stage gaps, review padding and default page side inset. | fixed |
| 40px | Navigation group separation and company side padding. | fixed |
| 80px | Section heading-to-media separation. | fixed |
| 160px | Major chapter and footer vertical padding. | clamp(5rem, 3.571rem + 7.143vw, 10rem) |

### Containers and grids

- **marketing container**: max width 1440px · side padding 32px. Centered full-width marketing layout; at a 1440px window, broad cards span 1376px.
- **opening text**: max width 689px · side padding 16px. Centered headline block; support beneath is narrower, about 599px of text.
- **feature stage**: 2 columns · gap 32px. Copy and oversized product media occupy opposing halves. Reverse orientation for a distinct capability instead of making every stage identical.
- **review rail**: gap 32px. 384px-wide cards continue beyond both viewport edges; do not force all reviews into a contained grid.
- **company reading column** (only for long-form company narratives): max width 700px. Readable prose within a wider 900px letter panel.
- **culture grid** (only for recruiting pages): max width 820px · 2 columns · gap 20px. Two equal 400px cards per row with a centered introduction above.
- **opportunity list** (only for recruiting pages): max width 960px. Single wide list with left titles and right metadata plus arrow.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature stages | 24px |
|  | navigation and reviews | 32px |
|  | primary action | 128px |
| long-form company narratives | letter panel | 20px |
| company and recruiting pages | architectural invitation | 40px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating integration tile | `rgba(0, 0, 0, 0.25) 0px 0px 16px -8px` | Small rotated logo tiles around the product demonstration. |
| recruiting pages | culture card | `rgba(0, 0, 0, 0.06) 0px 2px 10px 0px` | Faint lift for translucent culture cards. |
| long-form company narratives | letter panel | `rgba(71, 71, 71, 0.04) 0px 4px 34px 2px` | Diffuse lift beneath the long-form panel. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background-color: #ffffff`

**Observed:** Clean white intervals separate the colored product stages.

**Transfer:** Let white carry the page rather than placing every section in a tinted box.

#### Daylight opening · level 0

**Use:** First-screen atmosphere.

**CSS:** `background-image: linear-gradient(#d2e5ff, #fff9ee); border-radius: 24px`

**Observed:** A sky-colored field with cloud haze and iridescent horizon light behind the product.

**Transfer:** Keep the backdrop lighter than the ink and the product silhouette.

#### Pastel stage · level 1

**Use:** Large capability demonstrations.

**CSS:** `background-color: #ebf0f8; background-image: radial-gradient(circle at 75% 100%, rgba(185, 166, 255, 0.4), rgba(185, 166, 255, 0.4) 10%, rgba(255, 255, 255, 0) 64%); border-radius: 24px; overflow: hidden`

**Observed:** Lilac is the default; sibling stages use peach, pink or mint at 20–40% opacity. Some early stages use a bottom-oriented linear gradient instead. The backing remains blue-gray.

**Transfer:** Assign one soft hue per capability without tinting the text or action.

#### Charcoal chapter · level 0

**Use:** A bounded advanced-capability narrative.

**CSS:** `background-color: #1f2025; color: #ffffff`

**Observed:** A long dark band contains a centered atmospheric introduction and several light Pastel stages.

**Transfer:** Use a single dark chapter to signal a deeper product layer, with the light cards retaining readability.

#### Sculptural trust stage · level 1

**Use:** A focused assurance statement.

**CSS:** `background-color: #1f2025; background-image: radial-gradient(circle at 50% 0px, rgba(255, 255, 255, 0) 40%, rgba(63, 255, 194, 0.2) 90%, rgba(63, 255, 194, 0.4)); border-radius: 24px; overflow: hidden`

**Observed:** White centered text sits over a giant barely raised emblem; mint illumination grows toward the edges.

**Transfer:** Pair one credible assurance with a restrained geometric sculpture, not a dashboard.

#### Letter paper · level 1

**Only for:** long-form company narratives

**Use:** A substantial personal narrative.

**CSS:** `background-image: linear-gradient(90deg, #f9fafb, #ffffff 50%, #f9fafb 101%); border: 2px solid rgba(255, 255, 255, 0.6); border-radius: 20px; box-shadow: rgba(71, 71, 71, 0.04) 0px 4px 34px 2px`

**Observed:** A 900px-wide document-like panel includes faint editor controls, a title separator and personal sign-off; the prose is 700px wide.

**Transfer:** Use a document metaphor for a real first-person story, preserving generous inner margins.

#### Frost grid · level 0

**Only for:** company and recruiting pages

**Use:** Subtle technical texture behind narrative content.

**CSS:** `background-color: #f3f6f7; background-image: linear-gradient(rgba(34, 35, 38, 0.025) 1px, transparent 1px), linear-gradient(90deg, rgba(34, 35, 38, 0.025) 1px, transparent 1px); background-size: 81px 81px`

**Observed:** A very faint square grid fades into a near-white canvas at section boundaries.

**Transfer:** Keep the grid perceptible only at close inspection; fade its ends with a frost-colored overlay.

## Components

### Floating navigation

**Use:** Persistent compact marketing navigation.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 40px; padding: 8px; background-color: rgba(255, 255, 255, 0.6); backdrop-filter: blur(12px); border-radius: 32px`

**Text style:** `action` — -apple-system 500 · 16px/1.4

**Observed:** A centered capsule about 493px wide and 54px high floats 16px below the top. Logo first, two quiet links, compact Primary button last. Company layouts instead use a full-width 74px sticky glass bar with a 20px blur.

**Transfer:** Keep navigation terse enough to remain a small island; scope the full-width bar to company-oriented layouts.

### Primary button

**Use:** Main conversion action in opening and closing.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; background-color: #1f2025; color: #ebf0f8; border-radius: 128px; padding: 12px 18px; height: 46px`

**Text style:** `action` — -apple-system 500 · 16px/1.4

**Observed:** Leading platform icon followed by a short label. The navigation variant uses 8px 16px padding and a 38px height. The company closing variant is a glossier 52px lozenge with white rim light.

**States:** Declared: hover scale(1.025) with rgba(255,255,255,0.5) inset glow; focus-visible unknown; active scale(0.99).

**Transfer:** Use a relevant simple icon only when it adds meaning to the action.

### Quiet text link

**Use:** Secondary navigation without competing with conversion.

**CSS:** `color: rgba(31, 32, 37, 0.6); transition: color 0.15s`

**Text style:** `action` — -apple-system 500 · 16px/1.4

**Observed:** Text-only links sit between the identity and primary action.

**States:** Declared: hover color #1f2025; focus-visible unknown; active outline 0px.

### Capability stage

**Use:** One large benefit paired with visual demonstration.

**CSS:** `background-color: #ebf0f8; border-radius: 24px; overflow: hidden; height: 620px`

**Text style:** `heading` — -apple-system 600 · 64px/1 · tracking -0.03em

**Observed:** Two-column composition: a compact headline and support block opposite an oversized phone and floating interface detail. Pale glow stays behind the media; the outer stage clips the layered artwork. Earlier capability stages are 658px high.

**Transfer:** Use real interface content with one enlarged detail so the benefit is legible at a glance.

### Feature selector row

**Use:** Compact index of secondary capabilities beside a live product view.

**CSS:** `background-color: #ebf0f8; border-radius: 24px; padding: 24px; transition: transform 0.25s`

**Text style:** `feature-title` — -apple-system 600 · 24px/0.9 · tracking -0.01em

**Observed:** Title above a short body description, circular arrow or progress mark at right. Active row is 555px wide while neighboring rows are 513px; the list has 8px gaps and a top/bottom fade mask. A large phone stays beside it.

**Transfer:** Link each row to a meaningful demonstration; preserve an obviously dominant selected row.

### Review card

**Use:** User proof in an edge-running horizontal rail.

**CSS:** `background-color: #ebf0f8; border-radius: 32px; padding: 32px; width: 384px; min-height: 358px`

**Text style:** `review-body` — -apple-system 400 · 18px/1.3

**Observed:** Stars first, semibold title, muted author/date, then a plain quoted paragraph. Cards have no visible outline or heavy shadow; neighboring cards remain partially outside the viewport.

**Transfer:** Use real testimony with varied natural lengths rather than equalized marketing slogans.

### Footer group

**Use:** Utility navigation at the end of the page.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px`

**Text style:** `review-title` — -apple-system 600 · 18px/1.3

**Observed:** Muted group heading followed by dark 18px links. A broad identity column sits left, four utility columns occupy the right; social icons sit low left and trust badges low right. Footer has 160px top and bottom padding and 32px side insets. Company variants use 16px links on frost.

**Transfer:** Keep the footer on the page canvas rather than introducing a new colored band.

### Culture card

**Only for:** recruiting pages

**Use:** Explain a working principle in a small grid.

**CSS:** `display: flex; flex-direction: column; gap: 4px; padding: 24px; background-color: rgba(34, 35, 38, 0.04); border: 1px solid rgba(34, 35, 38, 0.1); border-radius: 24px; backdrop-filter: blur(4px); box-shadow: rgba(0, 0, 0, 0.06) 0px 2px 10px 0px`

**Text style:** `culture-title` — -apple-system 600 · 24px/1.1 · tracking 0.007em

**Observed:** Pale outlined icon above the title; short gray description follows. Each card is about 400px by 208px.

**Transfer:** Use concrete working behaviors instead of abstract virtue lists.

### Opportunity row

**Only for:** recruiting pages

**Use:** A restrained list of available roles.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 16px; padding: 16px 0px; border-top: 1px solid rgba(34, 35, 38, 0.1)`

**Text style:** `company-support` — -apple-system 400 · 20px/1.4 · tracking 0.0085em

**Observed:** Semibold 20px title left, regular gray 20px location right, then a 15px arrow. Each row is 61px high within a 960px-wide list; department headings group the rows.

**Transfer:** Keep this a typographic list, not separate rounded cards.

## Imagery and graphics

### Iridescent daylight rays

**Use:** Signature opening atmosphere behind the main object.

**Observed:** A pale cloudy sky is crossed by diffuse mint, cyan, lavender and peach horizontal rays that converge behind the device. Color is luminous rather than saturated; no sharp neon lines compete with copy.

**Transfer:** Retain the luminous convergence even for a product with no physical device; place an interface plane or simple dimensional object at its center.

**Build:** On Daylight opening, add soft white radial cloud patches across the upper third. Behind the product, layer wide SVG ribbons converging toward the lower center: mint rgba(131,227,222,0.35), lilac rgba(185,166,255,0.25) and peach rgba(255,171,148,0.25). Stretch each ribbon across the stage, taper at the center, blur 20–40px and fade to transparent at both ends. Keep rays below the copy.

### Device and interface theatre

**Use:** Opening object and capability demonstrations.

**Observed:** Realistic silver-edged phones and a dark wearable overlap in the hero; feature stages use tall phones roughly 370–392px wide with white interface cards projecting in front. Screens remain bright and readable, with soft shadows and restrained perspective. Some media extends beyond the rounded stage edges.

**Transfer:** Stage a truthful interface inside a clean device frame, or use a browser/interface slab with comparable dimensional edges. Minimum version: one crisp interface plus two enlarged detail cards, all sharing one light direction.

### Orbiting integration tiles

**Use:** A connection-focused capability stage.

**Observed:** Small white rounded logo squares rotate around a large phone on a pale mint stage. Concentric translucent arcs create a sense of connection without connector lines.

**Transfer:** Use the product's actual integration categories or document types, keeping them secondary to the main interface.

**Build:** Place 84–115px rounded white squares on concentric SVG circles centered near the phone. Rotate squares by alternating slight angles and use a 16px radius with a compact diffuse shadow. Draw oversized circular arcs with a soft white inner glow; clip everything to the 24px stage.

### Sculptural assurance emblem

**Use:** Signature trust statement.

**Observed:** An enormous dark embossed emblem sits behind centered white copy, nearly filling the 650px-high stage. Its edges catch faint gray highlights; green illumination pools at the lower corners.

**Transfer:** Use a simple original geometric symbol related to the product's assurance. Minimum version is an SVG silhouette with a softly lit bevel, not a flat white logo.

**Build:** Create a 550px-wide simple SVG silhouette with rounded contours. Fill near charcoal, add a fine white-at-10% upper-left edge and a black-at-20% lower-right edge offset by 2px. Layer over Sculptural trust stage, behind the text, allowing the shape to extend outside the panel's top edge before clipping.

### Everyday object closing arrangement

**Use:** Signature final invitation.

**Observed:** A full-width white-background still life groups a phone and wearable with bottle, sunglasses, keys, earbuds and cap. Edge objects are intentionally cut off; material detail is crisp, color natural, shadows soft and close to each object.

**Transfer:** Arrange tools and ordinary objects from the new product's daily context around one central product view. For software without physical tools, use a central interface with a small set of relevant photographed objects; do not replace the arrangement with a generic stock photograph.

### Community story rail

**Use:** Social proof before or after product explanation.

**Observed:** Tall 236px by 420px story-like images combine candid activity and meal photographs with user interface overlays. Cards run horizontally beyond the screen with 32px gaps and softened outer edges. A later photo canopy uses narrow rounded portrait tiles above the reviews.

**Transfer:** Use authentic contextual user imagery; overlay a few meaningful product outcomes, not decorative charts.

### Human company photography

**Only for:** company and recruiting pages

**Use:** People, place and credibility.

**Observed:** Recruiting opens with ten candid 233px square photos in staggered columns with 32px corners and soft shadows. A later place story uses overlapping white instant-photo frames with slight rotation. Advisors use two 200px monochrome portraits with 14px corners, understated biographies and a fine central separator.

**Transfer:** Use actual team moments and recognizable working environments. Preserve candid lighting for culture and grayscale consistency for expert portraits.

### Architectural light invitation

**Only for:** company and recruiting pages

**Use:** Closing conversion banner.

**Observed:** A 1360px by 540px rounded banner shows pale sculptural ribs sweeping toward a vanishing point. The neutral relief catches cool gray shadows, behind centered white copy and a glossy dark action.

**Transfer:** Replace the artwork with a subtle original folded or ribbed architectural relief, preserving its luminous silver tone.

**Build:** Draw repeated tapered curved ribs in SVG, converging near the lower center. Alternate near-white faces with translucent gray shadows, blur the deepest shadows slightly, and place inside a 40px-radius panel with 40px outer side margins. Maintain sufficient localized contrast behind the text.

### Icons

**Observed:** Marketing actions use a 20px solid leading platform icon. Footer social marks are mostly 24px solid silhouettes. Secondary feature controls use 22px outlined symbols with 2px round strokes inside pale circular rings; culture icons are larger pale outline illustrations.

**Transfer:** Match the icon language to its role: solid for familiar brands/actions, round-stroke outlines for utility controls, soft illustrative outlines only in culture content.

## Section recipes

How recurring sections are built.

### First screen: Daylight product opening

**Observed:** A Daylight opening fills almost the entire first 900px with an 8px white inset and 24px corners. Floating navigation sits centered above a two-line 80px display occupying roughly the middle half of the width. Below it, a 24px support line spans about 600px, then Primary button and a small rating line. Back-to-front layers are sky/cream field, cloud haze, converging iridescent rays, overlapping phone and wearable, and foreground copy/navigation. The main device grouping begins below the action around the middle of the screen, dominates the lower half and continues below the fold. Within 900px the headline, support, action, rating and substantial device detail are visible; the bottom of the object and subsequent compatibility proof fall below.

**Transfer:** Use one strong central product silhouette or dimensional interface plane with enlarged details in place of hardware. Keep the centered promise and small action above it, not beside it. Company narratives open more softly with a 52px mission headline and washed-out tilted interface artwork; recruiting opens with a small context label, 52px invitation and staggered candid-photo wall.

**Avoid:** Do not turn the opening into a standard left-copy/right-browser split, a dark neon hero, or a huge CTA row that pushes the main object entirely below the fold.

**Text style:** `display` — -apple-system 600 · 80px/1 · tracking -0.03em

### Heading and support pair

**Observed:** A 64px heading and 24px secondary support are separated by 16px. Major introductions are centered, while copy inside Capability stage is left-aligned and vertically centered. Heading-to-media gaps commonly expand to 80px.

**Transfer:** State one outcome in the heading and one mechanism in the support; adjust the line breaks to preserve a compact block.

**Text style:** `heading` — -apple-system 600 · 64px/1 · tracking -0.03em

### Three outcome cards

**Observed:** Three tall cards about 437px wide by 739px high share 24px corners and blue-gray backing. Short headings and support sit above large phones and floating metric cards; peach, blue and green glows differentiate their bottoms.

**Transfer:** Use a trio only when there are genuinely distinct outcomes. Keep the visual product proof larger than the prose; do not treat it as an icon grid.

### Alternating capability theatre

**Observed:** Capability stage uses a broad 1376px panel with text on one side and overlapping product media on the other. Adjacent panels have 32px gaps; the connection-focused variant reverses the text/media orientation and adds Orbiting integration tiles.

**Transfer:** Give each important capability a visible interaction or result and a single accent atmosphere.

### Deeper capability chapter

**Observed:** Charcoal chapter begins with softly glowing character-like spheres and small glass labels above a centered two-line lead, with its introductory phrase muted and product phrase white. Several light Capability stages follow on the same dark backing.

**Transfer:** Use original luminous abstract forms or an appropriate product intelligence metaphor; keep the tonal shift for the more advanced layer of the story.

### Secondary capability selector

**Observed:** A heading/support pair leads a faded vertical Feature selector row list on the left, paired with a tall isolated phone on the right. Active row is wider and more prominent than surrounding rows; the product has a small soft contact shadow.

**Transfer:** Use this to condense a longer capability inventory while maintaining visual focus on one outcome at a time.

### Assurance monument

**Observed:** Sculptural trust stage centers a short 64px white heading and two-line 24px translucent-white support over Sculptural assurance emblem. The stage is 650px tall within a white chapter with 160px vertical padding.

**Transfer:** State one defensible assurance and keep the symbol and lighting subordinate to it.

### Edge-running social proof

**Observed:** A photo canopy frames a centered heading/support pair above Review cards. The review rail uses 32px gaps and visibly continues beyond the viewport; the earlier community rail uses tall story images.

**Transfer:** Use genuine customer voices and contextual imagery, letting the rail suggest breadth without a wall of logos.

### Everyday closing invitation

**Observed:** A centered heading/support pair, 24px gap to Primary button, and Everyday object closing arrangement create a large final conversion section on white. It has 160px vertical breathing room. The utility footer follows on the same canvas.

**Transfer:** Make the final promise lower-pressure and more actionable than the hero; embed the product in a recognizable everyday setting.

### Company letter and expert proof

**Only for:** company narratives

**Observed:** Letter paper holds a long first-person narrative, separated paragraphs and personal sign-off. It is followed by a modest centered expert introduction and two monochrome portrait biographies, then Architectural light invitation and the same broad footer structure.

**Transfer:** Use the letter only for a substantive point of view; follow it with concrete human credibility rather than more marketing claims.

### Culture and opportunities

**Only for:** recruiting pages

**Observed:** Centered 52px section leads introduce a two-column Culture card grid, an instant-photo place story and a 960px Opportunity row list. Architectural light invitation closes before the frost-canvas footer.

**Transfer:** Balance lived team imagery, specific working principles and easy-to-scan opportunities; retain the smaller company type system.

## Page flow

**Storyline:** Personal promise → tangible product or human demonstration → credibility → focused capability or belief chapters → assurance → low-pressure invitation → utility footer.

### Product-marketing landing page

1. **Promise** — Centered daylight product theatre with a short benefit headline and one action.
2. **Social proof** — Compatibility marks, small award laurels and an edge-running community story rail.
3. **Capability chapters** — Three outcome cards followed by broad alternating product stages.
4. **Deeper product layer** — Charcoal introduction with luminous forms and a sequence of pale demonstration panels.
5. **Breadth and assurance** — Secondary capability selector and monumental dark trust stage.
6. **Customer validation** — Photo canopy and review rail.
7. **Closing call** — Everyday-object arrangement beneath a calm invitation and single action, then utility footer.

**Transfer:** Keep the contrast between tangible product demonstrations, human proof and soft atmosphere; adapt the number and placement of chapters to the new offer.

### Company mission and point of view

1. **Mission** — Centered 52px headline with a silver-gradient final phrase over a pale tilted interface composition.
2. **Point of view** — Long personal letter inside a document-like panel.
3. **Credibility** — A pair of monochrome expert portraits and brief biographies.
4. **Closing call** — Architectural relief invitation with glossy action, then frost utility footer.

**Transfer:** Explain why the organization exists through a real narrative, then show people who make its ambitions credible.

### Recruiting and team culture

1. **Invitation** — Centered compact headline over staggered candid photo columns.
2. **Human demonstration** — Introductory team prose and a wide embedded video.
3. **Working principles** — Small translucent culture-card grid.
4. **Place and belonging** — A centered place story above overlapping instant-photo frames.
5. **Opportunity** — Department-grouped typographic role list.
6. **Closing call** — Architectural relief invitation and shared utility footer.

**Transfer:** Replace product-feature depth with specific working behaviors and direct opportunities, retaining the softer frost canvas and company typography.

## Writing

Warm, direct and optimistic, with technological confidence expressed as practical help rather than futuristic spectacle. Personal agency and clear outcomes matter more than technical terminology.

**Do not copy:** Do not reuse Bevel names, logos, character artwork, founder/advisor identities, review quotations, member totals, ratings, medical promises or security claims. Replace them with original identity and substantiated product-specific content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for the team and plain product naming for capabilities. Company letters can use a conversational first-person plural.
- **Rhythm:** Headlines are usually 3–8 words, sometimes a longer two-line proof statement. Supporting copy is normally one sentence; short clauses and contractions keep it conversational. Longer company prose uses questions, examples and narrative turns.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the reader's new relationship to the product rather than its technical category. | 4–7 words | “Your Connected Health Coach” |
| Capability headline | A plain active verb followed by an immediate outcome. | 3–7 words | “Get answers from your data”<br>“Understand what you eat” |
| Supporting line | Explain the benefit and mechanism in everyday words. | 12–24 words | “Track your meals and get a full breakdown of what's fueling your body.” |
| Primary action | Literal verb plus destination or object, without hype. | 2–3 words | “Download app” |
| Closing invitation | Reduce pressure and acknowledge the reader's pace. | 3–6 words | “Ready When You Are” |
| Company narrative | Start like a personal note and build through recognizable everyday tension. | Conversational paragraphs | “Hey there,”<br>“Help us build a product that changes lives.” |

**Words and phrasing to use:** your; understand; connect; clear; one step; built for; get answers; confidence

**Avoid:** revolutionary platform; unlock limitless potential; disrupt; synergy; biohack everything; guaranteed transformation

**Rules:**

- Make each capability understandable before naming its underlying technology.
- Keep support lines focused on one practical outcome, not a list of adjectives.
- Use quantities only when they add credible proof and can be substantiated.
- Let the closing sound inviting rather than urgent; avoid countdown language.
- For culture content, describe observable behavior rather than repeating a value as a slogan.

## Do's and Don'ts

### Do

- Keep the first-screen display at 80px/1 and weight 600 with -0.03em tracking at desktop.
- Use the 24px/1.3 support recipe under 64px section headings with a 16px gap.
- Keep the floating navigation a compact 54px-high glass island with a 12px backdrop blur.
- Give broad product stages 24px corners and 32px separation.
- Use 160px chapter breathing room instead of enlarging every internal card gap.
- Preserve partially visible cards at the edges of proof rails with 32px gaps.
- Keep the product and its enlarged interface details much larger than icons or decorative badges.
- Use the 52px/1.1 company-heading variant only for company and recruiting content.

### Don't

- Do not replace charcoal actions with saturated mint or purple fills; those hues belong to light atmospheres.
- Do not apply the recruiting card's border and shadow to every product stage; the default stages are broad, clean planes.
- Do not tighten the entire page to a dense dashboard rhythm; 160px chapter intervals are integral to the pacing.
- Do not stretch the main action into a full-width rectangle; preserve the 46px lozenge construction.
- Do not use the 24px/0.9 feature title recipe for multiline explanatory copy.
- Do not add hard multicolor gradients to headline text throughout the page; the metallic phrase belongs to the company mission variant.
- Do not turn product detail cards into generic floating rectangles with illegible filler; use meaningful interface details.
- Do not recolor candid company imagery to match the pastel stages; preserve its natural human warmth.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare transform 0.6s cubic-bezier(0.19, 1, 0.22, 1) and box-shadow 0.3s; hover scale is 1.025 and active scale is 0.99.
- Navigation text declares color 0.15s.
- Feature-selector rows declare transform 0.25s.
- The letter panel declares a 0.65s ease fadeIn with a 0.3s delay.
- Proof rails have horizontal translated content; several product scenes include video.

**Transfer:**

- Retain the very small button scale response and quick text-link color change.
- Use product motion to demonstrate a meaningful state change inside the stage while the surrounding headline stays readable.

**Unknown:**

- Rail speed, scene choreography and scroll-trigger timing are not established.
- Focus-visible styling is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479/480px, 767/768px and 991/992px; company layouts also declare 1300px.
- Section padding uses clamp(5rem, 3.571rem + 7.143vw, 10rem).

**Transfer:**

- On narrow screens, keep the centered opening promise above its product object; stack stage copy above media without losing the luminous backing.
- Preserve some deliberate media clipping and edge-running proof rather than shrinking all devices and cards until unreadable.
- Collapse the culture grid and opportunity metadata into readable stacked arrangements while keeping the difference between cards and ruled rows.

**Unknown:**

- Exact mobile typography, navigation collapse behavior and art direction are not established; these narrow-screen arrangements are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
