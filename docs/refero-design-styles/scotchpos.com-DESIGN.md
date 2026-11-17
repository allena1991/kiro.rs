# Scotch — black glass, bright work

## Overview

A dark, tactile software style that pairs practical business language with almost invisible still-life objects and brightly lit interfaces. White rounded grotesk headlines, restrained gray text and small flashes of vermilion sit on a predominantly black canvas. Product screens, realistic hardware and candid customer photography give the spacious compositions a grounded, working-world feeling rather than a futuristic one.

### Essentials

- The promise floats above a luminous work surface: centered 54px/1.1 semibold Mori headline within 676px, 18px support within 510px, then an 850px-wide black-framed white interface after a 96px gap.
- Black objects disappear into black space: use edge-lit, near-black physical objects behind the main demonstration and again as a tilted closing still life. If the product has no hardware, stage tools or artifacts from its users’ work with the same low-key lighting.
- Orange acts like an indicator light, not a theme wash: #f54900 is confined to 40px-high conversion pills, short links, active markers and small checks; the surrounding page remains black and charcoal, with bright white largely inside product media.
- Small pills contrast with square-ish stages: buttons use 9999px corners and 6px 17px padding; media and content panels use 6px–10px corners, with 16px reserved for the main device bezel.
- Editorial contrast happens within sentences: 34px semibold narrative text mixes white and #666666, with orange dot labels; practical body copy stays at 15px–18px rather than growing to display scale.
- The conversion close is a product cutaway, not a centered text banner: a 1216px-wide, 576px-high #111111 panel pairs an oversized interface clipped on the left with a 42px/1.1 benefit statement and orange action on the right.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#f54900` | `--color-accent` | action, link, accent | Conversion buttons, active indicators, small section dots and text links; not a broad page background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-canvas` | background, text | Main page canvas, device frames and dark secondary actions; reverse text on the white header action. |
| Raised charcoal | `#111111` | `--color-panel` | surface | Closing conversion panel, integration backdrop and subdued proof tiles. |
| Media charcoal | `#1a1a1a` | `--color-stage` | surface | Product demonstration stage and introduction badge. |
| Header hairline | `#1c1c1c` | `--color-header-edge` | border | Visible 11% white rule on black beneath navigation. |
| Panel outline | `#292929` | `--color-edge` | border | Thin outlines around outlined panels and quote cards; also the visible result of a 16% white footer rule on black. |
| Control gray | `#333333` | `--color-control` | surface, border | Previous-slide circle and list dividers. |
| Dim gray | `#666666` | `--color-dim` | text | De-emphasized narrative phrases and footer category labels; white at 40% on black produces the same visible tone. |
| Device rim | `#868686` | `--color-bezel` | border | Thin inset rim around the main product frame. |
| Middle gray | `#999999` | `--color-muted` | text | Secondary descriptions; also the visible result of white at 60% on black. |
| Badge gray | `#a5a5a5` | `--color-badge-text` | text | Introduction badge text. |
| Light gray | `#cccccc` | `--color-secondary` | text | Supporting descriptions beside product media. |
| White | `#ffffff` | `--color-ink` | text, action, surface | Headings, labels and primary text; white header action and luminous interface interiors. |

## Typography

- **__mori_658136** — Headlines, editorial statements, quotations and button labels. Rounded contemporary grotesk with open counters and a friendly, substantial semibold. If unavailable, use **Manrope**. Use 600 for headings and actions, 400 for quotes; preserve the relatively compact headline widths. Font stack: "__mori_658136", "Manrope", ui-sans-serif, system-ui, sans-serif.
- **__Inter_f367f3** — Paragraphs, navigation, small labels, numbers and metadata. Neutral, highly legible sans with restrained tracking and clear businesslike numerals. Font stack: "__Inter_f367f3", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | __mori_658136 | 600 | 54px | 1.1 | normal | fixed | Default landing headline, centered and generally balanced over two lines. |
| stat | __Inter_f367f3 | 500 | 54px | 1.1 | -0.02em | fixed | Prominent percentage set over customer photography. |
| closing-heading | __mori_658136 | 600 | 42px | 1.1 | normal | fixed | Benefit-led conversion panel headline. |
| heading | __mori_658136 | 600 | 34px | 1.17 | normal | fixed | Core section headings and feature chapter titles. |
| narrative | __mori_658136 | 600 | 34px | 1.25 | normal | fixed | Extended contrast statement with white and dim gray phrases. |
| quote | __mori_658136 | 400 | 20px | 1.3 | normal | fixed | Customer quotation within a narrow outlined card. |
| lead | __Inter_f367f3 | 400 | 18px | 1.45 | -0.01em | fixed | Hero support and integration descriptions. |
| body | __Inter_f367f3 | 400 | 16px | 1.5 | 0.005em | fixed | Feature descriptions and supporting paragraphs. |
| label | __Inter_f367f3 | 500 | 16px | 1.5 | 0.01em | fixed | Short feature labels and integration eyebrows. |
| small | __Inter_f367f3 | 400 | 15px | 1.5 | 0.005em | size calc(0.78125rem + 0.195312vw) | Concise descriptions, checklist continuations and conversion support. |
| small-emphasis | __Inter_f367f3 | 500 | 15px | 1.5 | 0.005em | fixed | White lead-in phrases within small descriptions. |
| button | __mori_658136 | 600 | 15px | 1.4 | 0.02em | size calc(0.78125rem + 0.195312vw) | Primary, header and secondary action labels. |
| text-link | __Inter_f367f3 | 500 | 15px | 1.4 | normal | fixed | Orange inline action links. |
| section-label | __Inter_f367f3 | 500 | 15px | 1.5 | normal | fixed | Icon-led section labels, orange narrative labels and footer links. |
| navigation | __Inter_f367f3 | 400 | 14px | 1 | 0.01em | size calc(0.875rem + 0vw) | Desktop navigation. |
| caption | __Inter_f367f3 | 400 | 13px | 1.5 | normal | fixed | Introduction badge and footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail and company-story openings | secondary-display | __mori_658136 | 600 | 48px | 1.125 | normal | fixed | Slightly smaller centered hero with an icon eyebrow. |
| careers listings | listing-title | __mori_658136 | 600 | 24px | 1.2 | -0.01em | fixed | Repeated role titles above muted department and location metadata. |
| company-story editorial sections | story-body | __Inter_f367f3 | 400 | 20px | 1.45 | normal | fixed | Narrow, long-form origin narrative with white emphasis at its conclusion. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Mori supplies the rounded voice; Inter keeps longer reading and navigation utilitarian. Do not use the display face for every paragraph.
- Headings use normal tracking; negative tracking belongs to lead paragraphs, statistics and listing titles, not to every large word.
- Keep the main heading near 676px wide, feature headings near 410px and closing copy near 420px. Use deliberate sentence-case line breaks rather than uppercase display typography.
- White-to-gray phrase contrast is a hierarchy device, not a multicolor headline gradient.

## Layout

**Density:** Airy between chapters, compact within controls and descriptive groups; media takes more room than prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap between short action text and arrow. |
| 12px | Footer link rhythm and compact feature groups. |
| 16px | Device frame padding and panel media inset. |
| 17px | Space between hero actions and horizontal padding of the primary action. |
| 20px | Gap between paired media panels or three product cards; hero heading-to-support gap. |
| 24px | Support-to-action spacing and closing headline-to-support spacing. |
| 28px | Eyebrow-to-heading separation. |
| 32px | Container side padding and internal group separation. |
| 40px | Quote-card padding and closing text-column padding. |
| 44px | Gap between three succinct benefit columns. |
| 48px | Navigation item spacing and footer column gap. |
| 52px | Heading-to-media separation and closing support-to-action spacing. |
| 88px | Default opening top padding beneath the navigation. |
| 96px | Hero action group to main demonstration. |
| 144px | Company-story padding and careers introduction-to-list gap. |
| 164px | Major capability chapter spacing and broad section padding. |

### Containers and grids

- **main-container**: max width 1216px · side padding 32px. Centered desktop content span; at 1440px the painted content begins 112px from each edge. Side padding sits inside the outer centered wrapper.
- **hero-copy**: max width 676px. Centered headline; supporting prose narrows to 510px.
- **main-device**: max width 850px. Centered hero device, visibly narrower than the content container.
- **benefit-grid**: 3 columns · gap 44px. Short icon-and-text benefit columns with minimal card chrome.
- **media-pair**: 2 columns · gap 20px. Asymmetric 807px product stage beside a 389px photo-stat panel; testimonial variant uses 396px quote and 800px video.
- **feature-chapters** (only for product-detail pages): max width 1008px. Main chapter column offset by a 208px left navigation rail inside the full container.
- **listing-column** (only for careers listings): max width 868px. Centered list of full-width divided rows.
- **story-column** (only for company-story editorial sections): max width 440px. Narrow center narrative flanked by dark physical still-life objects.

## Corner radius

| Element | Radius |
| --- | --- |
| actions-and-badges | 9999px (pill) |
| demonstration-and-closing-panels | 6px |
| outlined-cards | 10px |
| media-interiors | 8px |
| main-device-frame | 16px |
| round-controls | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| device-inset-rim | `inset 0px 0px 0px 2px #868686` | Hero device bezel; a fine physical edge rather than a floating card shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous dark page ground.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Sections remain on one black field; separation comes from room, media and occasional thin rules.

**Transfer:** Let the media introduce brightness rather than switching whole chapters to light backgrounds.

#### Charcoal stage · level 1

**Use:** Backing for cropped product demonstrations.

**CSS:** `background: #1a1a1a; border-radius: 6px; overflow: hidden`

**Observed:** Bright product windows enter from the lower or side edge rather than sitting as small centered icons.

**Transfer:** Use a readable section of the new product with ample dark backing.

#### Outlined panel · level 1

**Use:** Integration feature and quotation cards.

**CSS:** `background: #000000; border: 1px solid #292929; border-radius: 10px; overflow: hidden`

**Observed:** The boundary is faint and matte, with no luminous stroke or drop shadow.

**Transfer:** Keep panel interiors close to the page ground.

#### Closing charcoal · level 1

**Use:** Shared conversion stage.

**CSS:** `background: #111111; border-radius: 6px; overflow: hidden`

**Observed:** A full-width inset panel unifies the image and copy halves.

**Transfer:** Use the panel as a real product cutaway with one clear action.

#### Device bezel · level 2

**Use:** Main white interface presentation.

**CSS:** `background: #000000; border-radius: 16px; padding: 16px; box-shadow: inset 0px 0px 0px 2px #868686; overflow: hidden`

**Observed:** The screen itself has an 8px inner radius; its white interior is the brightest area in the opening.

**Transfer:** Place a real or carefully composed product view inside the frame.

#### Photo shade · level 2

**Use:** Readable statistic over a customer photograph.

**CSS:** `background: rgba(0, 0, 0, 0.4); padding: 39px 30px`

**Observed:** The shade covers the whole image; the number and short description sit toward its bottom.

**Transfer:** Keep the person visible and the metric legible without adding a separate white card.

## Components

### Navigation bar

**Use:** Persistent top-level navigation.

**CSS:** `height: 60px; background: #000000; border-bottom: 1px solid rgba(255, 255, 255, 0.11); display: flex; justify-content: space-between; align-items: center`

**Text style:** `navigation` — __Inter_f367f3 400 · 14px/1 · tracking 0.01em

**Observed:** Logo at left, links across the left-middle with 48px gaps, login and a white action at right; the inner content aligns with the main container.

**States:** Declared: hover navigation text becomes #999999; focus-visible and active treatments are unspecified.

### Primary button

**Use:** Main in-page conversion action.

**CSS:** `background: #f54900; color: #ffffff; border-radius: 9999px; padding: 6px 17px; height: 40px; display: inline-flex; align-items: center; justify-content: center; gap: 10px`

**Text style:** `button` — __mori_658136 600 · 15px/1.4 · tracking 0.02em

**Observed:** Short label followed by a small up-right arrow in a translucent circular inset. The careers variant replaces the arrow with a count badge.

**Transfer:** Use a compact verb-led conversion label and retain the inset end marker.

### Header action

**Use:** High-contrast compact conversion control in navigation.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; padding: 6px 19px; height: 35px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — __mori_658136 600 · 15px/1.4 · tracking 0.02em

**Observed:** Plain label without the arrow inset; visually quieter in scale than the orange in-page action.

### Introduction badge

**Use:** Small introductory label above the main headline.

**CSS:** `background: #1a1a1a; color: #a5a5a5; border-radius: 9999px; padding: 4px 16px`

**Text style:** `caption` — __Inter_f367f3 400 · 13px/1.5

**Observed:** Centered, low contrast and much smaller than the headline; it reads as a preface, not a campaign ribbon.

### Arrow text link

**Use:** Secondary exploration action under a section heading or paragraph.

**CSS:** `color: #f54900; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `text-link` — __Inter_f367f3 500 · 15px/1.4

**Observed:** Unboxed sentence-case label followed by a small right arrow; the hero secondary action instead uses white on black with a play icon.

### Integration panel

**Use:** Explain compatibility in one horizontal feature.

**CSS:** `background: #000000; border: 1px solid #292929; border-radius: 10px; padding: 16px 16px 16px 56px; display: flex; gap: 32px; overflow: hidden`

**Text style:** `lead` — __Inter_f367f3 400 · 18px/1.45 · tracking -0.01em

**Observed:** Left half contains a small orange-dot label, heading, paragraph and Arrow text link. Right half is a dark 535px by 328px integration diagram.

**Transfer:** Keep text focused on eliminating duplicate work, and put the ecosystem diagram opposite it.

### Quote card

**Use:** Human testimony beside a larger customer video.

**CSS:** `border: 1px solid #292929; border-radius: 10px; padding: 40px; display: flex; flex-direction: column; gap: 40px; max-width: 396px`

**Text style:** `quote` — __mori_658136 400 · 20px/1.3

**Observed:** Small portrait and attribution at top, quote vertically centered in the remaining space, company and location metadata paired at bottom. It matches the adjacent video's 450px height.

### Photo stat

**Use:** Quantified proof alongside a product demonstration.

**CSS:** `background: rgba(0, 0, 0, 0.4); padding: 39px 30px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `stat` — __Inter_f367f3 500 · 54px/1.1 · tracking -0.02em

**Observed:** A full-height shade overlays a customer-at-work photo. The large percentage and short medium-weight explanation are bottom-aligned.

**Transfer:** Use one substantiated metric rather than a dashboard of unrelated numbers.

### Closing conversion panel

**Use:** Shared product-led final action.

**CSS:** `background: #111111; border-radius: 6px; overflow: hidden; display: flex; align-items: center`

**Text style:** `closing-heading` — __mori_658136 600 · 42px/1.1

**Observed:** An oversized 618px by 576px device image fills the left half and is clipped at the panel edges. The right holds a small brand symbol, benefit headline, muted support with a white rejoinder, and Primary button.

**Transfer:** Use a product detail that substantiates the final benefit; keep the text column near 420px wide.

### Footer columns

**Use:** Sparse wayfinding beneath the conversion panel.

**CSS:** `display: flex; gap: 48px; color: #ffffff`

**Text style:** `section-label` — __Inter_f367f3 500 · 15px/1.5

**Observed:** A small brand mark sits left of two link columns. Dim 13px category labels precede 15px links with 12px vertical gaps. A low-contrast 834px rule and small legal line sit well below; dark tilted still-life artwork fills the right side.

### Listing row

**Only for:** careers listings

**Use:** Open-position navigation.

**CSS:** `display: flex; align-items: center; gap: 32px; padding: 36px 0px; border-bottom: 1px solid #333333`

**Text style:** `listing-title` — __mori_658136 600 · 24px/1.2 · tracking -0.01em

**Observed:** Title and a second line of muted department/location text occupy the left; a 40px outlined circular northeast-arrow action sits at the far right. Two compact dropdown filters precede the list.

## Imagery and graphics

### Edge-lit work objects

**Use:** Signature atmospheric layer in the opening and footer.

**Observed:** Near-black bottles, cut-glass tumbler and faceted decanter are lit only along their rims. Objects are large, partially outside the viewport, and almost merge with the black ground; the footer groups glass and decanter on a tilted dark rectangular plane.

**Transfer:** Use physical objects associated with the new audience's work. Preserve the darkness, reflective edge light and peripheral framing; even an abstract tool silhouette should feel tangible rather than like a colorful floating blob.

**Build:** Arrange two or three transparent object cutouts behind the main media. Use a black base, desaturate strongly, reduce brightness until broad faces disappear, and retain a narrow soft gray rim on one side. Without photography, draw SVG silhouettes with near-black fills and thin gray edge paths, apply a faint blurred duplicate behind the edge, and mask the bottom into black. For the footer put the group on a roughly 620px square dark plane rotated clockwise about 20 degrees, clipping beyond the right edge.

### Luminous product stage

**Use:** Main demonstration and recurring feature media.

**Observed:** White interface windows are framed in black tablet or desktop hardware with a thin metallic rim. Some are front-on and tightly clipped; the payment hardware is rendered in realistic three-quarter view on pure black. Product imagery is substantially larger than its supporting copy.

**Transfer:** Show the new product doing one recognizable task, with legible large regions and a believable frame. If detailed hardware is unavailable, a simple black rounded frame and a high-quality interface composition are the minimum acceptable version.

### Integration lattice

**Use:** Ecosystem graphic within the Integration panel.

**Observed:** A warm full-color central brand tile interrupts rows of gray partner tiles on a nearly black grid. The rows are clipped and fade at top and bottom; the center is the only richly colored tile.

**Transfer:** Use the new brand symbol in the middle and authorized partner marks in low-contrast monochrome. The diagram must feel like infrastructure, not a colorful logo cloud.

**Build:** In a 535px by 328px #111111 stage, draw thin low-contrast horizontal and vertical grid lines. Place 70px–78px dark rounded tiles at regular intersections, one centered hero tile larger than its neighbors. Use gray symbols for peripheral tiles, keep color in the central symbol, and overlay 98px top and bottom linear gradients from #111111 to transparent.

### Customer proof photography

**Use:** Photo-stat panels and testimonial videos.

**Observed:** Real people in working environments, shelves and storefronts; natural light, subdued saturation and no cutout treatment. Video previews use a black 20% overlay and an orange circular play control; the quote lives separately to the left.

**Transfer:** Photograph genuine users in context, favoring candid expressions and recognizable surroundings over glossy studio portraits.

### Workflow artifact collage

**Only for:** product-detail openings and problem statements

**Use:** Make everyday workflow friction tangible around a clear central message.

**Observed:** Rotated legacy windows, invoices, a CSV sheet, a dark task form and taped handwritten notes sit around the edges. The central headline stays clear; paper is off-white, forms retain their utilitarian appearance, and pieces are partially clipped by the viewport.

**Transfer:** Use real artifacts from the new audience's process, not decorative stickers unrelated to the promise.

**Build:** Create four separate rectangular SVG or HTML artifacts: two dense gray-white tables, one dark form and one off-white note with a small colored tape strip. Rotate each independently by roughly 10–25 degrees, place them toward opposite side edges and behind the central product frame, and clip their outer edges. Leave a clear central column at least 676px wide for the headline.

### Editorial photo triptych

**Only for:** company-story openings

**Use:** Humanize the mission before the origin narrative.

**Observed:** Three photographs share a 342px height; narrow 317px side images flank a 558px center image. Small gaps and modest rounded corners keep them as one strip, with warm natural workplace light.

**Transfer:** Show three distinct moments of the audience at work, not three versions of a founder headshot.

### Remote-use lifestyle stage

**Only for:** remote-access feature chapters

**Use:** A richer environmental backdrop for a mobile product view.

**Observed:** A large front-facing phone rises out of a wide sunset photograph with soft palm silhouettes, blue-gray sky and warm coral clouds; the phone and its white interface dominate the center-right and are clipped at the bottom.

**Transfer:** Choose an out-of-office setting relevant to the product's mobility promise. Keep environmental color inside the media frame rather than spreading it into the page.

### Icons

**Observed:** Small white or gray functional glyphs accompany short section labels; many sit inside dark rounded square chips. Text-link arrows are about 11px, button markers about 13px, feature symbols about 24px–26px; careers arrows use an 18px–19px thin white outline. Orange check chips are 16px with black checks.

**Transfer:** Use simple, consistent functional line symbols and compact square backing when labeling sections; reserve orange chips and round markers for active states and actions.

## Section recipes

How recurring sections are built.

### First screen: Dark product stage opening

**Observed:** A fixed 60px Navigation bar sits above a centered black stage. The content begins with 88px top padding: Introduction badge, a 676px-wide two-line display headline, a 510px-wide support sentence after 20px, and Primary button beside a black secondary play action after 24px, separated by 17px. After 96px, an 850px-wide Device bezel holds a white interface. Edge-lit work objects sit behind it at both sides, never behind the headline. Within the first 900px the full headline, support and actions are visible, followed by the upper portion of the main interface; the device bottom and small feature icon tiles continue below the fold.

**Transfer:** Use the default centered promise and luminous product contrast for a new landing page. Replace the interface with a credible workflow demonstration and replace peripheral objects with audience-relevant tools; when no complex artwork is available use simple edge-lit silhouettes and a framed interface. Product-detail openings use secondary-display with scattered Workflow artifact collage pieces; company-story openings use secondary-display, one action and Editorial photo triptych instead of the device.

**Avoid:** Do not turn this into a conventional equal-width text-left/image-right hero, an all-orange masthead or a tiny fully visible device surrounded by empty space.

**Text style:** `display` — __mori_658136 600 · 54px/1.1

### Capability introduction and paired proof

**Observed:** A small icon-led section label precedes a left-aligned heading near 410px wide. Three compact benefit snippets sit to its right with 44px gaps. Arrow text link sits under the heading. After about 52px, a Charcoal stage with a large cropped interface occupies roughly two thirds of the width beside a Photo stat; tabs sit beneath with an orange active indicator.

**Transfer:** Group one central capability with three short outcomes, then prove it with one large demonstration and one human metric.

**Text style:** `heading` — __mori_658136 600 · 34px/1.17

### Compact integration feature

**Observed:** Integration panel uses a narrow eyebrow-to-heading gap of 28px, then supporting lead copy and a separated text link; Integration lattice fills the opposite half. The panel's faint outline is its only outer decoration.

**Transfer:** Use this self-contained block for compatibility or workflow continuity rather than another broad product chapter.

**Text style:** `heading` — __mori_658136 600 · 34px/1.17

### Centered hardware demonstration

**Observed:** A centered icon label, compact multi-line 34px headline and orange exploration link lead into a wide, realistic product hardware view on black. Three short icon-led benefit lines appear beneath, with white key phrases and muted continuations.

**Transfer:** Stage a main physical or digital product object as tangible proof; keep supporting labels restrained so it retains visual dominance.

**Text style:** `heading` — __mori_658136 600 · 34px/1.17

### Contrast statement

**Observed:** A roughly 900px-high black scene centers a 699px text column between oversized peripheral workflow artifacts. An orange dot label precedes 34px/1.25 narrative copy whose phrases alternate white and dim gray. The related solution block shifts to a narrow left text column and an oversized interface extending beyond the right container edge.

**Transfer:** Make a clear before/after argument in short statements, then substantiate the alternative with specific capabilities and a real product view.

**Text style:** `narrative` — __mori_658136 600 · 34px/1.25

### Testimonial pair

**Observed:** A thin top rule and 56px inset introduce the icon label and 34px heading. Previous and next circular controls sit at the far right, gray then orange. After 52px the Quote card sits beside an 800px by 450px customer video with a centered orange play control, separated by 20px.

**Transfer:** Pair one concise named human statement with its corresponding environmental video or photograph; metadata should stay subordinate.

**Text style:** `heading` — __mori_658136 600 · 34px/1.17

### Product cutaway close and atmospheric footer

**Observed:** Closing conversion panel spans the main container and is 576px high. The oversized left device cutaway balances a right-aligned column of brand symbol, 42px benefit headline, a muted support line ending in a white rejoinder, and Primary button. Beneath it, Footer columns occupy the left half of a 670px black footer while Edge-lit work objects form a tilted dark plane on the right. The legal rule is shorter than the main container and leaves the artwork uninterrupted.

**Transfer:** Retain both devices: a tangible final product benefit and a dark atmospheric afterimage. Use the new product's strongest visual detail in the cutaway and audience-relevant objects in the footer; link groups should remain sparse.

**Text style:** `closing-heading` — __mori_658136 600 · 42px/1.1

### Product chapter rail

**Only for:** product-detail pages

**Observed:** A restrained left rail names the capability chapters; the current item is white with an orange dot and other items are gray. The 1008px main column begins with a 34px heading and alternates three 323px-wide visual cards, a split checklist/image view, and wide device scenes. Captions combine a white 15px medium phrase with a muted continuation.

**Transfer:** Use a rail when several substantial capabilities deserve separate chapters; change media layout to fit each argument instead of repeating identical cards.

**Text style:** `heading` — __mori_658136 600 · 34px/1.17

### Editorial origin and credentials

**Only for:** company-story pages

**Observed:** A 440px central story column carries an orange-dot label, 34px heading and 20px/1.45 paragraphs with 36px paragraph spacing; dark work objects flank it. A later credentials block sets a left headline beside two columns of 397px by 247px #111111 logo tiles with 20px gaps and 10px corners.

**Transfer:** Explain why the category needed a better tool, then show relevant credentials in restrained monochrome. Use actual authorized marks and meaningful relationships.

**Text style:** `story-body` — __Inter_f367f3 400 · 20px/1.45

### Careers introduction and list

**Only for:** careers sections

**Observed:** A centered 868px column begins with a small icon label and a 34px statement mixing dim gray with white. After 144px, an orange-dot label and two compact outlined dropdown filters precede Listing row items separated by 1px rules.

**Transfer:** Apply this to open roles or similarly navigable opportunities; the list is a text hierarchy, not a grid of promotional cards.

**Text style:** `listing-title` — __mori_658136 600 · 24px/1.2 · tracking -0.01em

## Page flow

**Storyline:** Audience-specific promise → tangible product proof → capability outcomes → human or institutional credibility → product-led final action → atmospheric wayfinding.

### Broad product landing page

1. **Promise** — Centered statement and two actions above a luminous framed interface and edge-lit physical objects.
2. **Social proof** — Low-profile monochrome customer marks and a short endorsement line.
3. **Capability outcomes** — Asymmetric demonstration/photo-stat pair, compact compatibility panel and a centered hardware scene.
4. **Problem and alternative** — Peripheral artifact collage frames a contrast statement; a large modern product view supports the alternative.
5. **Human proof** — Outlined quote paired with customer video.
6. **Closing call** — Product cutaway conversion panel followed by sparse footer columns and tilted dark still life.

**Transfer:** Lead with a clear audience promise, alternate conceptual explanation with tangible demonstrations, and use human proof to earn the final action. The exact chapter order follows the new product's argument.

### Focused product-detail page

1. **Promise** — Smaller centered headline, one orange action and workflow artifacts orbiting a main interface.
2. **Outcome summary** — Three icon-led benefit columns followed by the compatibility feature.
3. **Capability chapters** — Left chapter rail with alternating card triplets, checklist/media splits and wide desktop or mobile views.
4. **Human proof** — Customer quote and video pair.
5. **Related product** — Left text link area with thin rules beside a large hardware image and orange northeast-arrow control.
6. **Closing call** — Shared product cutaway conversion panel and atmospheric footer.

**Transfer:** Use deeper demonstrations and a navigable chapter rail while keeping the same restrained palette and shared ending.

### Company mission and recruiting page

1. **Mission** — Centered statement, orange recruiting action with count badge, and warm workplace photo triptych.
2. **Origin** — Narrow editorial narrative framed by near-black work objects.
3. **Institutional credibility** — Backer marks and an asymmetric credential tile grid.
4. **Opportunity** — Two-tone recruiting statement, department/location filters and divided role rows.
5. **Closing call** — The same product-led conversion close and dark still-life footer.

**Transfer:** Keep the company story tied to the audience's work, scope recruitment controls to actual opportunities, and retain the shared visual close.

## Writing

Confident, practical and audience-aware, with a little impatience toward cumbersome tools. Benefits are expressed as time saved, fewer chores and more control rather than abstract technological grandeur.

**Do not copy:** Do not reuse the Scotch name, logo, customer or partner marks, product-specific claims, percentage results, guarantees, testimonials or recruiting counts. Supply the new brand's own substantiated claims and authorized assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your business; use we for the people building the better alternative. Name the audience explicitly in the opening, then move into concrete second-person benefits.
- **Rhythm:** Sentence-case headlines often run 5–12 words; compact paired fragments make capability titles punchy. Support is one or two plain sentences, with occasional rhetorical questions and short rejoinders.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Express category fluency as a benefit to the intended user. | 8–12 words | “The system that knows liquor like you do.”<br>“The back office built for more business and less busywork.” |
| Capability headline | Pair a better action with its practical outcome in two short fragments. | 4–7 words | “Smarter orders. Stocked shelves.”<br>“Faster receiving. Fewer surprises.” |
| Supporting line | Name the manual pain, then explain how the workflow becomes simpler. | 15–40 words | “Stop drowning in spreadsheets and guesswork. [Brand] helps you move faster, sell smarter, and stay in control.” |
| Primary action | Direct invitation using a familiar verb and concrete next step. | 2–4 words | “Book a demo”<br>“Join us” |
| Closing call | State a tangible benefit in everyday language, then overturn the status quo with a short rejoinder. | 8–14 words for the headline | “Spend 20% less time on the stuff you hate.”<br>“But it doesn’t have to be.” |

**Words and phrasing to use:** built for; less busywork; no double entry; stay in control; from anywhere; in seconds; fewer surprises; the stuff you hate

**Avoid:** revolutionary ecosystem; synergize; unprecedented disruption; unlock limitless potential; next-generation magic

**Rules:**

- Put the audience and an intelligible benefit before technology terminology.
- Start small feature captions with a medium-weight action phrase, then finish with a quieter explanation.
- Use category-specific nouns and observable tasks to make claims credible.
- Use a restrained conversational turn occasionally; not every heading needs a joke.
- Use numerical proof only when it is supported; otherwise write a concrete qualitative outcome.

## Do's and Don'ts

### Do

- Keep the main desktop content span at 1216px and align navigation, feature stages and closing panel to it.
- Pair 54px Mori hero type with 18px Inter support, rather than enlarging the paragraph to compete.
- Let black remain the continuous ground across section transitions; use 164px chapter spacing for breathing room.
- Use 40px orange conversion pills inside the page and the compact 35px white action in the header.
- Make product screens large enough to show a recognizable task, with a 16px padded black frame.
- Use 1px #292929 panel outlines and 6px–10px panel corners.
- Keep the quote/video pair asymmetric, with a 396px quote card beside an 800px video.
- Carry a near-black object scene into the footer so the page ends with a tactile afterimage.

### Don't

- Do not turn #f54900 into a full-width section fill or broad ambient orange glow.
- Do not apply pill radii to product media; reserve 9999px for small controls and badges.
- Do not substitute heavy card shadows for the fine device rim and faint panel rules.
- Do not make every paragraph white; preserve #cccccc, #999999 and #666666 hierarchy.
- Do not set primary headlines in all caps, a serif or an ultra-condensed face.
- Do not shrink large product demonstrations into icon-sized illustrations inside generic equal cards.
- Do not use bright multicolor partner tiles around the central integration symbol.
- Do not replace the closing product cutaway with a newsletter form or a plain centered slogan.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color and box-shadow transitions of 0.5s cubic-bezier(0.4, 0, 0.2, 1).
- Navigation declares color transitions of 0.2s cubic-bezier(0.4, 0, 0.2, 1), with hover text changing to #999999.
- Carousel controls declare hover opacity 0.8. Additional declared transforms use 0.3s cubic-bezier(0.61, 1, 0.88, 1).

**Transfer:**

- Keep control feedback subtle: changes in color, inset edge and opacity should preserve the dark physical stage.
- Retain the active orange marker on navigable product chapters; let the marker explain the current chapter rather than decorating every title.

**Unknown:**

- Scroll choreography, exact reveal sequencing, video playback behavior and the header's scroll-direction logic are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 400px, 640px, 768px, 850px, 880px, 950px, 1000px, 1024px, 1280px and 1440px.
- The testimonial pair declares a row layout from 850px; the integration panel and closing conversion declare row layouts from the medium breakpoint. Closing content uses a reversed column direction below that breakpoint.
- Desktop navigation is hidden below the large breakpoint.

**Transfer:**

- On narrow screens, prioritize promise, action and readable product media; allow peripheral objects to clip rather than squeezing the headline.
- Stack the quote and video and the integration copy/diagram; preserve the distinct black and white media contrast.
- Keep the closing headline and action before the large device cutaway when stacking.

**Unknown:**

- Exact mobile menu construction, all narrow-screen dimensions and behavior of the chapter rail are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
