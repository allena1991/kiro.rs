# Webflow — blueprints meet theatre

## Overview

A bright, business-minded visual system with the ambition of a creative tool and the clarity of an enterprise platform. Black grotesk headlines and electric blue actions sit on spacious white fields, while interface compositions, human portraits, and luminous fluted backdrops provide concentrated spectacle. It suits products that turn complex work into tangible creative outcomes; the reading experience is sparse at the top and progressively richer in demonstrations and proof.

### Essentials

- Headlines feel like compact declarations rather than airy posters: the default display is 80px/1.04, weight 600, -0.01em tracking; section statements are 56px/1.04 at the same weight.
- The opening is a promise above a moving shelf of evidence: a left-aligned headline, a roughly 407px support line, paired 51px actions, then an edge-faded rail of compact product vignettes after an 80px gap.
- Actions are small architectural blocks, not bubbles: electric blue primary and pale gray secondary fills, 4px corners, 16px by 24px padding, and 16px/1.2 medium text.
- Color is concentrated in demonstrations rather than spread across the reading canvas: white dominates, #080808 carries headlines, #146ef5 marks actions and the 46px announcement strip. Saturated art belongs inside media stages and the monumental footer symbol.
- Proof is cinematic and numerical at once: tall 504px by 756px portrait cards carry a 40px/1.2 result, a 20px descriptor, and a 20px/1.5 quote over a progressively blurred dark lower field. Use a real workflow scene with an attributable result when portrait media is unavailable.
- A page must include both a staged product or output composition and an oversized blue identity sculpture: interface windows float on gridded or softly illuminated backing, while a roughly 672px-wide symbol is clipped by the lower-right footer edge. A simple original geometric emblem and a carefully composed static interface are the minimum equivalents.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#146ef5` | `--color-action` | action, accent, background | Primary buttons, announcement band, focus rings and oversized footer emblem. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Label blue | `#1366e2` | `--color-link-blue` | text, link | Tiny status annotations and resource category labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#080808` | `--color-ink` | text, background | Headlines, body copy, dark feature stages and dark closing bands. |
| Secondary text | `#5a5a5a` | `--color-muted` | text | Supporting text, metadata and footer links. |
| Hairline gray | `#d8d8d8` | `--color-rule` | border, surface | Card edges, section dividers and small proof-card framing. |
| Soft gray | `#f0f0f0` | `--color-soft` | surface, background | Secondary actions, restrained media trays and inactive progress tracks. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page ground, navigation, cards, and reversed text on dark media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| AI-oriented feature campaigns | Luminous lavender | `#cab1ff` | `--color-lavender` | accent | Small luminous region of gradient headline lettering and blue demonstration backdrops. |
| resource cards | Blue category wash | `#e8f1fe` | `--color-blue-wash` | surface | Visible result of 10% electric blue over white behind resource categories. |
| dark conversion bands | Dark secondary action | `#171717` | `--color-dark-action` | action, surface | Secondary buttons on immersive dark closing sections. |
| dark panels and interactive demonstrations | Dark panel edge | `#363636` | `--color-dark-rule` | border, surface | Edges of near-black resource panels and subdued dark controls. |
| company and recruitment pages | Inverse secondary text | `#ababab` | `--color-inverse-muted` | text | Secondary eyebrow on photographic recruitment closing sections. |

## Typography

- **WF Visual Sans Variable** — All marketing headlines, paragraphs, labels, actions and numerals. A compact contemporary grotesk with broad circular counters, assertive semibold headings and a relatively dense lowercase texture. If unavailable, use **Inter**. Use weights 400–600; preserve compact headline line breaks and -0.01em display tracking. Font stack: "WF Visual Sans Variable", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | WF Visual Sans Variable | 600 | 80px | 1.04 | -0.01em | fixed | Primary promise, output-gallery title and monumental light closing invitation. |
| heading-lg | WF Visual Sans Variable | 600 | 56px | 1.04 | normal | fixed | Major section statements, proof introductions and centered dark closing calls. |
| heading | WF Visual Sans Variable | 600 | 40px | 1.2 | normal | fixed | Smaller section titles and prominent results on customer cards. |
| heading-sm | WF Visual Sans Variable | 600 | 32px | 1.2 | normal | fixed | Compact product introduction below a large demonstration and sales-form title. |
| subheading | WF Visual Sans Variable | 500 | 20px | 1.4 | normal | fixed | Card titles, section labels, result descriptors, attribution names and footer group headings. |
| body-lg | WF Visual Sans Variable | 400 | 20px | 1.5 | normal | fixed | Expanded section support lines and testimonial quotations. |
| body | WF Visual Sans Variable | 400 | 16px | 1.6 | normal | fixed | Ordinary explanatory text, feature details and hero support. |
| action | WF Visual Sans Variable | 500 | 16px | 1.2 | -0.01em | fixed | Button labels and compact discovery links. |
| footer-link | WF Visual Sans Variable | 400 | 16px | 1.5 | normal | fixed | Long categorized footer link lists. |
| navigation | WF Visual Sans Variable | 500 | 16px | 1.2 | -0.01em | size clamp(0.8rem, 0.3598rem + 0.71vw, 1rem) | Primary navigation and account actions. |
| announcement | WF Visual Sans Variable | 500 | 14px | 1.6 | normal | fixed | Single-line announcement centered above navigation. |
| micro-tag | WF Visual Sans Variable | 500 | 10px | 1.3 | 0.1em, uppercase | fixed | Small status markers beside footer links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company fact sections | monumental-stat | WF Visual Sans Variable | 600 | 112px | 1.04 | normal | fixed | One dominant company-scale number, contrasted against 32px secondary figures. |
| free-entry product campaigns | closing-statement | WF Visual Sans Variable | 400 | 32px | 1.4 | normal | fixed | Large explanatory paragraph beside an 80px closing invitation. |
| feature campaigns and company pages | feature-heading | WF Visual Sans Variable | 600 | 24px | 1.3 | normal | fixed | Paired feature-card titles and portrait-card names. |
| capability and enterprise pages | feature-title | WF Visual Sans Variable | 600 | 20px | 1.4 | normal | fixed | Expanded capability-tab titles and compact service-benefit headings. |
| FAQ sections | question | WF Visual Sans Variable | 500 | 20px | 1.3 | normal | fixed | FAQ summary labels. |
| resource and people cards | category | WF Visual Sans Variable | 550 | 12.8px | 1.2 | normal, uppercase | fixed | Small resource categories and executive roles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The display and large section heading share a close 1.04 line height; keep letterforms substantial at weight 600 rather than using light oversized type.
- Most sizes use normal tracking. Reserve -0.01em for the 80px display and compact action/navigation labels; uppercase micro-tags use 0.1em.
- Eyebrows are often sentence-case 20px medium text, not universally tiny uppercase labels. The uppercase category and micro-tag recipes serve narrower purposes.
- The default opening uses 16px support, while capability introductions and extended statements use 20px/1.5. Do not average these into one body size.

## Layout

**Density:** Airy at section scale, with tightly assembled product media and compact typographic stacks inside cards.

### Spacing

**Spacing system:**

- **grid** 8px — Primary non-fluid layout rhythm for section padding, column gutters and content gaps.

| Value | Use |
| --- | --- |
| 8px | Short heading-to-detail gaps and compact title stacks. |
| 16px | Button separation, local text gaps and footer link rhythm. |
| 24px | Heading support gaps, form grid gaps and medium card padding. |
| 32px | Column gutters, card content padding and paragraph-to-action breathing room. |
| 48px | Heading-to-proof-card gap, media offsets in editorial cards and footer group separation. |
| 80px | Default section top and bottom padding; hero-to-vignette rail gap. |
| 144px | Bottom breathing room after the large closing section, only for free-entry product campaigns. |

### Containers and grids

- **main-container**: max width 1440px · side padding 72px. Centered content system. At a 1440px desktop viewport the visible content spans 1296px, leaving equal side margins; preserve the column alignment from navigation to footer.
- **split-feature**: 2 columns · gap 32px. Two 632px media columns or a text column opposite a 632px-wide demonstration. Capability copy narrows further to about 448px inside its half.
- **benefit-grid**: 3 columns · gap 32px. Three open benefit columns or image-led outcomes across the content width.
- **footer-grid**: 4 columns · gap 32px. Four 300px readable columns with multiple heading/link groups per column. Let the longest group extend much farther down than its neighbors.
- **proof-rail**: gap 24px. Fixed-width 504px portrait cards extend beyond the container and clip at the viewport edge, creating a carousel rather than three squeezed equal cards.
- **reading-column** (only for company narratives): max width 853px. Centered company narrative and selected text-led sections, narrower than the general page grid.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | cards-and-media | 8px |
|  | floating-product-window | 2.1px |
| AI-oriented feature campaigns | product-selector | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-interface | `rgba(0, 0, 0, 0.29) 0px 6px 13px 0px, rgba(0, 0, 0, 0.26) 0px 24px 24px 0px, rgba(0, 0, 0, 0.15) 0px 53px 32px 0px, rgba(0, 0, 0, 0.04) 0px 95px 38px 0px, rgba(0, 0, 0, 0.01) 0px 148px 42px 0px` | Deep layered elevation under a hero-scale product window; ordinary content cards remain flat. |

### Surfaces

#### White reading canvas · level 0

**Use:** Default background for the majority of a new landing page.

**CSS:** `background: #ffffff; color: #080808`

**Observed:** Large unboxed reading fields separate concentrated media moments.

**Transfer:** Let copy and media alignment create structure before adding containers.

#### Bounded media tray · level 1

**Use:** Large demonstration stage and its lower video action strip.

**CSS:** `background: #f0f0f0; border: 1px solid #d8d8d8; border-radius: 8px; overflow: clip`

**Observed:** A broad media rectangle sits above a shallow full-width playback strip; the visual artwork can be much darker than the tray itself.

**Transfer:** Contain a single complete product scene, not an array of unrelated decorative panels.

#### Outline card · level 1

**Use:** Sales forms and compact supporting resources.

**CSS:** `background: #ffffff; border: 1px solid #d8d8d8; border-radius: 8px; overflow: clip`

**Observed:** Thin flat edges rather than ambient shadows distinguish these cards from floating product imagery.

**Transfer:** Use a white inset panel for functional content, especially forms.

#### Portrait glass · level 2

**Use:** Lower region of cinematic proof cards.

**CSS:** `background: linear-gradient(rgba(255, 255, 255, 0.16), rgba(0, 0, 0, 0.25) 59%, rgba(0, 0, 0, 0.5)); backdrop-filter: blur(10px); border-radius: 0px 0px 8px 8px; mask-image: linear-gradient(rgba(0, 0, 0, 0), rgba(0, 0, 0, 1), rgba(0, 0, 0, 1))`

**Observed:** A gradual mask makes the image sharp above and softened behind the lower white copy.

**Transfer:** Apply the overlay to the image layer, retaining sharp foreground text.

#### Dark resource panel · level 1

**Only for:** enterprise decision-support sections

**Use:** Paired calculator and product-tour promotions.

**CSS:** `background: #080808; color: #ffffff; border: 1px solid #363636; border-radius: 8px; overflow: clip`

**Observed:** Large white heading and blue action sit above a tightly clipped interface illustration.

**Transfer:** Use for high-intent tools and evidence, not every feature.

#### Fluted closing atmosphere · level 0

**Only for:** immersive product closing sections

**Use:** Full-bleed closing product/output showcase.

**CSS:** `background: linear-gradient(170deg, rgba(8, 8, 8, 0.7), rgba(8, 8, 8, 0.05) 75%); backdrop-filter: blur(32px)`

**Observed:** A dark blurred enlargement of the featured output sits behind broad vertical glass-like divisions; a sharp stack of output windows occupies the front.

**Transfer:** Enlarge and blur the same artwork used in the foreground so the atmosphere is materially connected to the product.

#### Gradient headline accent · level 1

**Only for:** AI-oriented feature campaigns

**Use:** Localized color inside otherwise near-black display lettering.

**CSS:** `background: radial-gradient(circle farthest-side at 0% 0%, #cab1ff 5%, #146ef5 10%, #080808 20%); background-clip: text; color: rgba(0, 0, 0, 0); background-size: 200% 200%`

**Observed:** Only a small region of the headline is lavender and blue; most letters remain dark.

**Transfer:** Keep the illuminated area concentrated rather than rainbow-filling the whole sentence.

## Components

### Primary navigation

**Use:** Persistent site orientation and conversion.

**CSS:** `background: #ffffff; border-bottom: 1px solid #d8d8d8; height: 68px; position: sticky; z-index: 999; display: flex; align-items: center`

**Text style:** `navigation` — WF Visual Sans Variable 500 · 16px/1.2 · tracking -0.01em

**Observed:** Identity at left, compact navigation immediately alongside, account and sales links near the right, then Primary button. The announcement band scrolls away while this white bar remains.

**Transfer:** Keep navigation practical and compact even when the product media below becomes theatrical.

### Announcement strip

**Use:** One current product launch or news link above navigation.

**CSS:** `background: #146ef5; color: #ffffff; padding: 12px 0px; text-align: center`

**Text style:** `announcement` — WF Visual Sans Variable 500 · 14px/1.6

**Observed:** A full-width single-line link with an inline directional arrow; about 46px tall.

**States:** Declared: hover darkens the fill with rgba(0, 0, 0, 0.15) inset shading; focus-visible uses a 2px solid #080808 outline with -2px offset.

### Primary button

**Use:** Main conversion action on light or dark backgrounds.

**CSS:** `background: #146ef5; color: #ffffff; border-radius: 4px; padding: 16px 24px; display: flex; justify-content: center; align-items: center; gap: 6.4px`

**Text style:** `action` — WF Visual Sans Variable 500 · 16px/1.2 · tracking -0.01em

**Observed:** A roughly 51px-high block, sized to the label rather than stretched across the text column. Paired with Secondary button in the opening.

**States:** Declared: hover background #0055d4; focus-visible 2px solid #146ef5 outline with 2px offset; active removes the box shadow and outline.

### Secondary button

**Use:** Sales or demo alternative beside the main action.

**CSS:** `background: #f0f0f0; color: #080808; border-radius: 4px; padding: 16px 24px; display: flex; justify-content: center; align-items: center; gap: 6.4px`

**Text style:** `action` — WF Visual Sans Variable 500 · 16px/1.2 · tracking -0.01em

**Observed:** Same construction and visual height as Primary button, with a 16px gap between actions. In dark conversion bands its fill changes to #171717 with white lettering.

### Customer proof card

**Use:** Quantified customer outcomes with human context.

**CSS:** `position: relative; display: flex; flex-direction: column; padding: 32px; gap: 32px; width: 504px; height: 756px; color: #ffffff; border-radius: 8px; overflow: clip`

**Text style:** `body-lg` — WF Visual Sans Variable 400 · 20px/1.5

**Observed:** Full-bleed portrait video or still, centered white customer identity near the top, then bottom-aligned result, descriptor, quotation and attribution over Portrait glass. A small circular northeast arrow sits at the lower right. Result uses heading; descriptor and name use subheading. Cards live in an overflow rail with small circular previous/next controls.

**Transfer:** Choose one measured result and a human explanation for each card, not a dense dashboard of statistics.

### Sales form panel

**Use:** High-intent lead generation beside a large product demonstration.

**CSS:** `background: #ffffff; border: 1px solid #d8d8d8; border-radius: 8px; overflow: clip`

**Text style:** `body` — WF Visual Sans Variable 400 · 16px/1.6

**Observed:** A 32px-padded inner body contains a two-column grid of labeled rectangular inputs with 24px gaps; the default example is about 521px wide. The blue submit action sits below the fields, followed by small consent text. The enterprise opening uses a longer form in the right-hand column.

**Transfer:** Adapt the field count to the buying motion; preserve the calm outlined panel and aligned labels.

### Editorial update card

**Use:** Recent announcements and learning resources on a white field.

**CSS:** `display: flex; flex-direction: column; border-radius: 8px`

**Text style:** `subheading` — WF Visual Sans Variable 500 · 20px/1.4

**Observed:** Muted body-size category above a compact medium title, then a 300px by 169px thumbnail after 48px. The default card is unboxed; the image supplies the visual weight. Titles have an animated underline rather than a blue button.

**Transfer:** Use a restrained crop of actual product or event imagery. Maintain title-above-image order.

### Footer link group

**Use:** Dense yet scannable destination lists.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px; margin-bottom: 48px`

**Text style:** `footer-link` — WF Visual Sans Variable 400 · 16px/1.5

**Observed:** A 20px medium heading precedes links by 24px. Links are secondary gray; tiny uppercase blue tags can sit beside selected destinations. Four columns share the page grid, and the longest column determines much of the footer depth.

**States:** Declared: hover text #080808; focus-visible text #080808 with a 2px solid #146ef5 outline and 2px offset.

**Transfer:** Retain meaningful category grouping without padding the list merely to mimic its length.

### FAQ row

**Only for:** objection-handling sections

**Use:** A short question with an expandable answer.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 24px 0px; border-bottom: 1px solid #d8d8d8`

**Text style:** `question` — WF Visual Sans Variable 500 · 20px/1.3

**Observed:** A wide right-hand list faces a narrow section title. Blue plus marks align at the far right. Closed rows are about 81px tall for a single-line question, expanding naturally for wrapped text; answers use body.

**States:** Declared: hover color #146ef5; focus-visible 2px solid #146ef5 outline with 2px offset.

**Transfer:** Use actual buyer objections and plain answers; retain the linear list rather than turning each question into a floating card.

### Resource category tag

**Only for:** resource cards

**Use:** Compact categorical marking on a white inset resource card.

**CSS:** `background: rgba(20, 110, 245, 0.1); color: #1366e2; border-radius: 4px; padding: 2px 6px`

**Text style:** `category` — WF Visual Sans Variable 550 · 12.8px/1.2 · uppercase

**Observed:** A small uppercase label above the title; the white inset card floats visually within a softly colored illustration frame. It is not the primary action.

**Transfer:** Use the category to orient readers, and a separate underlined action to open the resource.

## Imagery and graphics

### Miniature outcome shelf

**Use:** The default opening’s lower visual field.

**Observed:** A horizontal shelf of compact product vignettes uses roughly 248px-wide image areas and short centered captions. Light interface fragments, avatars and charts alternate with a taller photographic/result card. White fades at both viewport edges soften the overflow; white space separates the shelf from the headline.

**Transfer:** Create three or more small visual demonstrations of distinct outcomes, not generic feature icons. If no finished interface exists, compose credible small workflow fragments with a short descriptive caption.

**Build:** Place image-and-caption groups in a horizontal flex rail. Give normal visual tiles a 248px by 186px image box, with 16px caption separation; reserve 248px by 330px for a taller proof tile. Overlay a pointer-events:none linear-gradient(90deg, white 1%, transparent 20%, transparent 80%, white 99%) edge mask.

### Blueprint product theatre

**Use:** A hero-scale demonstration after the opening and compact product introductions.

**Observed:** A complete dark application window, about 971px by 607px, floats in the center of a much wider stage. Behind it is a charcoal technical grid with faint circles, line markings and a subdued identity shape. Strong layered downward shadows make the window feel physically suspended; the stage ends in a pale playback strip.

**Transfer:** Show the product doing meaningful work, including its output in context. Minimum equivalent: one polished static application composition over an original technical grid, with a real output preview rather than arbitrary chrome.

**Build:** Use the Bounded media tray. Inside its image area, layer a dark translucent field over a pale ground, then 1px white grid lines at low opacity at roughly 56px intervals, a few large outlined circles and fine dashed construction lines. Center the product window at about three quarters of stage width, use the floating-interface shadow, and keep all technical markings much lower contrast than the interface.

### Cinematic customer portraits

**Use:** Customer proof cards and occasional editorial workflow photography.

**Observed:** People are shown at desks or in real offices, in natural daylight with restrained saturation. Tall crops keep a clear face and upper body above the darker text area; lower backgrounds are blurred rather than covered with a solid opaque text box.

**Transfer:** Use authentic people or a real working context, and reserve the lower half for legible white outcome copy. Keep photographic color natural even when adjacent product art is saturated.

### Perspective output gallery

**Use:** A large showcase device that turns product results into spatial objects.

**Observed:** Full website compositions are presented as thin rectangular planes tilted in perspective, repeating across the white canvas and continuing beyond both edges. The centered title is 80px; the composition is closer to a gallery installation than a conventional screenshot grid.

**Transfer:** Use full output artifacts—reports, designed pages, visual plans or other credible results. Make an original shallow-perspective rail if 3D rendering is unavailable.

**Build:** Place tall output images on rectangular planes with a shared perspective parent, align their upper edges along a diagonal and use a consistent rotateY tilt. Stagger horizontal positions to show multiple surfaces without making a pile; keep the background white, borders thin and shadows restrained. Continue the planes offscreen so the field feels larger than the viewport.

### Monumental footer emblem

**Use:** The final visual punctuation on every page.

**Observed:** A saturated blue identity symbol about 672px by 418px sits at the lower-right edge of the white footer, continuing beyond the right and bottom boundaries. It contrasts with small gray copyright and social icons at the lower left; it is a shape, not an extra headline.

**Transfer:** Use an original product emblem or simple distinctive geometric monogram. If no emblem exists, create a bold abstract cut-paper shape from the product’s initial and scale it to the same visual mass.

**Build:** Create a single-color SVG silhouette filled #146ef5 in a 672px-wide box. Anchor it to the footer’s lower-right region, extend it beyond both edges and clip the footer overflow. Keep it behind link content and leave copyright legible in the opposing corner.

### Luminous fluted media

**Only for:** capability demonstrations and AI-oriented campaigns

**Use:** Backing for product close-ups, prompt experiences and feature carousels.

**Observed:** Soft but saturated blue, lavender, purple or green illumination is divided into broad vertical bands with visibly different brightness. Fine grain gives it a printed, tactile surface rather than a slick rainbow mesh. Sharp dark or light UI panels float above the light; some windows are deliberately clipped by the media edge.

**Transfer:** Choose one dominant hue tied to the feature and one luminous neighbor. Keep color inside the rounded media rectangle; a minimum version is a layered gradient, vertical translucent strips and one crisp interface fragment.

**Build:** Create an overflow-hidden 8px-radius rectangle. Layer broad radial glows over a blue or near-black base, using lavender and white at low alpha for light. Add 4–6 unequal vertical strips, each roughly 15–25% of the width, with alternating white alpha gradients and dark alpha shading. Blur the light layer by 32px, not the UI, and add an SVG feTurbulence grain overlay at very low opacity. Match the soft glow; exact stops are not essential.

### Dark output stack

**Only for:** immersive product closing sections

**Use:** Closing demonstration beneath a centered heading and paired actions.

**Observed:** A sharp frontal output window sits over several successively narrower windows peeking out above it. The front image is roughly 864px wide, with related frames up to 960px wide. The same artwork is enlarged, blurred and darkened behind the scene, with broad fluted divisions. White text remains separate above the stack.

**Transfer:** Layer several genuine outputs or views of one product rather than unrelated decorative windows. Use a static offset stack as the minimum equivalent.

**Build:** Place 4–7 image planes in a centered relative stage; move successive back planes upward by small increments and reduce their width so only a thin header strip shows. Enlarge a copy of the foreground image to cover the section background, apply the Fluted closing atmosphere, then lay a bottom fade into #080808 behind the sharp stack.

### Culture deck and portraits

**Only for:** company and recruitment pages

**Use:** Human identity, company principles and team leadership.

**Observed:** Company storytelling mixes natural event photography with a row of narrow 177px by 254px principle cards. Those cards use orange, vivid green, blue and dark violet treatments, a simple 48px line icon near the top and a short 20px label near the bottom. Leadership appears in 182px by 324px portrait cards with white names over a frosted lower field, a soft shadow and a wide pale geometric ribbon behind the row. The closing recruitment band uses full-bleed stage photography darkened behind left-aligned white type.

**Transfer:** Use the expanded palette only for culture storytelling. Replace principle labels and portraits with the new organization’s own human material; keep the narrow-card scale and bottom-weighted label composition.

**Build:** For the principle deck, use four equal narrow 8px-radius panels with solid or softly glowing contrasting fills, one simple outlined icon at the top and a bottom-aligned two-line label. For the portrait row, position repeated upright photographs above a pale low-contrast SVG ribbon; add a translucent lower overlay with blur(48px) so names remain sharp.

### Icons

**Observed:** Small arrows and chevrons are functional and monochrome. Discovery links use a right arrow; external examples use a northeast arrow; playback uses a filled triangle. Benefit illustrations are delicate blue line drawings within pale outlined shapes. Culture-card icons are larger 48px line drawings with 2.3px strokes and butt caps; footer social marks sit in 24px targets and use secondary gray.

**Transfer:** Use simple functional SVGs with the same baseline and color as their label. For benefit illustrations, favor a small line drawing with restrained blue accents over multicolor filled icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Promise and outcome shelf

**Observed:** The first screen begins with Announcement strip at 46px and Primary navigation at 68px. On White reading canvas, the hero starts after 80px of top padding. The 80px semibold single-line promise spans a little over half the content width, leaving the right side open. A 16px/1.6 support line is constrained to about 407px and sits 24px below it; Primary button and Secondary button follow after 32px. A small audience-oriented selector/caption aligns to the far right at action level. After 80px, Miniature outcome shelf spans beyond the content edges. Its product fragments and captions, plus part of a taller proof tile, are visible within the first 900px; customer logos and the large product theatre fall below. Layers are white canvas, rail imagery and edge fades, then foreground labels and controls.

**Transfer:** State the new product’s broad promise above a small shelf of tangible results. Without finished media, use carefully made static workflow fragments and one credible proof card. Product-overview pages can instead place a small label in the left third and the 80px promise/support/actions in the right two thirds; sales-led pages use a 56px proof-oriented promise opposite Sales form panel. Company openings center the 80px promise over Perspective output gallery.

**Avoid:** Do not replace the open right-hand space with a giant decorative orb, center the default headline, or promote the compact shelf into a full-height dashboard hero.

**Text style:** `display` — WF Visual Sans Variable 600 · 80px/1.04 · tracking -0.01em

### Product theatre and supporting ledger

**Observed:** A full-width Bounded media tray contains Blueprint product theatre and a full-width playback action. Below it, a compact identity tile and 32px heading/action occupy the left half; four one-line benefits with small blue icons and gray dividers form a ledger on the right.

**Transfer:** Explain the product through one complete demonstration, then a concise list of how it fits into daily work.

**Text style:** `heading-sm` — WF Visual Sans Variable 600 · 32px/1.2

### Heading and support pair

**Observed:** A 56px heading occupies the left portion of the container while 20px/1.5 support sits opposite, or support follows directly below with a 24px gap. Default vertical section padding is 80px. The widest text-led statements still leave generous unused horizontal space.

**Transfer:** Use the heading to name the benefit and the paragraph to explain mechanism. Choose split or stacked arrangement according to the amount of copy.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### Cinematic proof rail

**Observed:** A 56px two-line proof heading faces small circular arrow controls. After 48px comes a row of Customer proof card instances with 24px visible gaps, overflowing the right edge. A centered 16px sentence and underlined sales link follow below.

**Transfer:** Pair a broad proof claim with specific result stories. Keep the rail's large portrait scale rather than reducing it to a row of tiny review cards.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### Sales conversion split

**Observed:** A 56px heading and muted 16px paragraph precede Sales form panel in a roughly five-column text/form area. Opposite, a much larger shadowed product window extends toward or beyond the right edge. In the sales-led opening, form and proof-oriented introductory text instead start side by side at the top.

**Transfer:** Use this when the buying path requires a conversation. Let the product view carry excitement while the form stays plain and usable.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### Editorial updates

**Observed:** A 40px section heading introduces three widely spaced Editorial update card instances. Categories and titles appear above the images, with 48px between title area and thumbnail.

**Transfer:** Keep this block light and editorial; let each update have one clear title and one representative image.

**Text style:** `heading` — WF Visual Sans Variable 600 · 40px/1.2

### Gallery release into footer

**Observed:** A centered 80px gallery title introduces Perspective output gallery over a large white field. It releases into a white footer with a 1px gray top rule and 80px top padding. Footer link group instances sit in four columns; the bottom-left copyright and gray social row face Monumental footer emblem at lower right. Footer bottom padding is 32px.

**Transfer:** Use outputs as the final proof before navigation. Preserve the asymmetry of small utility content opposite an oversized identity form, regardless of the number of footer destinations.

**Text style:** `display` — WF Visual Sans Variable 600 · 80px/1.04 · tracking -0.01em

### Alternating capability chapter

**Only for:** product-overview and enterprise pages

**Observed:** An approximately 632px by 711px visual faces a narrower 448px text area in a two-column section with 80px vertical padding. Product-overview chapter headings use 56px; enterprise subchapters use 40px. A 20px support paragraph and blue or underlined action sit above a tab list. The active tab shows a short title, body paragraph and dark progress rule; inactive labels are gray with pale tracks. Consecutive chapters alternate media left and right in the enterprise variant. Product overview adds a compact sticky section-navigation strip beneath the main navigation.

**Transfer:** Organize deep capabilities into a handful of meaningful chapters, each with one decisive visual. Keep the active/inactive hierarchy explicit and preserve the graphic's half-page scale.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### FAQ with narrow title column

**Only for:** enterprise and feature campaigns

**Observed:** A 56px title sits in the left third while FAQ row instances fill the larger right column. Questions use 20px/1.3 medium text; blue plus marks provide the main color. No enclosing shaded section is needed.

**Transfer:** Resolve practical objections after the benefits have been made tangible.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### Immersive closing invitation

**Only for:** product-overview, enterprise and feature campaign pages

**Observed:** A roughly 1051–1125px full-width dark section uses Fluted closing atmosphere and Dark output stack. Centered 56px white headline, 20px supporting line and paired blue/dark actions sit above the foreground output. The enterprise variant asks for a demo; the broader product version emphasizes creative potential. A white footer follows.

**Transfer:** Make the last pitch both an invitation and a final visible product result; use the same output for foreground clarity and background atmosphere.

**Text style:** `heading-lg` — WF Visual Sans Variable 600 · 56px/1.04

### Light free-entry close

**Only for:** free-entry product campaigns

**Observed:** An 80px two-line invitation and two actions sit in a left column, with a 32px/1.4 explanatory paragraph in a right column. The white section ends with 144px bottom padding and a thin rule before the footer.

**Transfer:** Use when a no-cost entry point deserves a clearer explanation after a theatrical product close.

**Text style:** `display` — WF Visual Sans Variable 600 · 80px/1.04 · tracking -0.01em

### Company narrative and fact constellation

**Only for:** company pages

**Observed:** A centered 853px reading area alternates 56px text headings with two stacked square documentary photographs. A later fact section breaks that narrow column: small photos occupy the far left, one 112px number dominates the center, and a narrow right-hand list uses 32px figures and thin gray dividers. Press appears as ruled headline/date rows; leadership and backing marks become horizontal rails.

**Transfer:** Mix institutional facts with visible people and varied scale. One dominant fact is more characteristic than an equal grid of giant numbers.

**Text style:** `monumental-stat` — WF Visual Sans Variable 600 · 112px/1.04

### Photographic recruitment close

**Only for:** company and recruitment pages

**Observed:** A full-bleed dark stage photograph forms an approximately 825px band. An 80px white invitation, small gray eyebrow, short white paragraph and blue action align left with the main content margin; people remain legible on the right. The same white categorized footer follows.

**Transfer:** Show real people in a meaningful shared setting, with a dark left region that makes the invitation clear.

**Text style:** `display` — WF Visual Sans Variable 600 · 80px/1.04 · tracking -0.01em

## Page flow

**Storyline:** Broad promise → tangible product or output evidence → capability and outcome stories → credible proof and practical reassurance → conversion or showcase → expansive utility footer.

### Broad brand and product landing page

1. **Promise** — Open declarative headline, compact support and two actions above a miniature outcome shelf.
2. **Social proof** — Low-key monochrome logo strip.
3. **Product demonstration** — Large blueprint-backed application theatre followed by a short benefit ledger.
4. **Quantified proof** — Portrait-based customer result rail.
5. **Conversion** — A restrained sales form beside an oversized interface.
6. **Continuity** — Recent updates lead into a spatial output gallery.
7. **Ending** — White categorized footer ends with small legal/social content opposite an oversized clipped blue emblem.

**Transfer:** Use the broadest promise and the most legible output fragments; let deeper proof and a direct contact path follow without imposing a fixed section count.

### Sales-led enterprise landing page

1. **Proof-led promise** — A 56px claim and three compact benefit statements face a full sales form.
2. **Social proof** — Customer logos and three image-led outcomes.
3. **Capability chapters** — Alternating feature visuals with active detail tabs.
4. **Service reassurance** — Three compact service-benefit columns.
5. **Quantified proof** — Cinematic customer rail.
6. **Objection handling** — Split FAQ list, dark decision-support panels and framed learning resources.
7. **Closing call** — Dark fluted demo invitation above stacked output windows.
8. **Ending** — White link directory and monumental blue emblem.

**Transfer:** Lead with a defensible business outcome and an immediate route to sales; use governance, reliability or service topics only when appropriate to the new product.

### Product-overview landing page

1. **Category expansion** — Small left label beside a large right-column headline, support and sales action.
2. **Capability chapters** — Sticky section links and repeated text/tab/media splits.
3. **Quantified proof** — Oversized customer portrait rail.
4. **Closing call** — Centered white statement on dark fluted atmosphere, paired actions and output stack.
5. **Ending** — White four-column directory with clipped blue identity sculpture.

**Transfer:** Use repeated chapter structure to make a broad product understandable while changing the visual proof in each chapter.

### Focused emerging-capability campaign

1. **Promise** — Small pill selector beside a right-column gradient-accented display heading.
2. **Interactive demonstration** — Blue luminous prompt stage.
3. **Benefits** — Heading/support pair, large paired media, centered transition and full-width feature carousel.
4. **Capability expansion** — Illustrated benefit columns and two-column image-led capabilities.
5. **Trust** — Centered responsibility statement and partner logo band.
6. **Objection handling** — Ruled FAQ list.
7. **Closing call** — Dark output stack followed by a second white free-entry invitation.
8. **Ending** — The same white footer and oversized blue mark.

**Transfer:** Give a focused capability its own scoped light treatment and demonstration, then explain practical control and entry conditions.

### Company identity and recruitment page

1. **Purpose** — Centered 80px statement over a perspective output gallery.
2. **Origin and principles** — Narrow documentary narrative followed by a colored principle-card deck.
3. **Institutional proof** — One giant fact, smaller ruled facts and press rows.
4. **Human credibility** — Portrait leadership rail, backing-logo strip and compact reviews.
5. **Closing invitation** — Dark full-bleed photograph with large left-aligned recruitment copy.
6. **Ending** — White utility directory with small legal content and huge blue emblem.

**Transfer:** Use the institution’s own people, principles and facts, while preserving the shift between narrow narrative, expansive proof and human photography.

## Writing

Confident, commercially literate and creative without becoming whimsical. The language connects freedom to act with tangible business results, then reassures the reader through concrete mechanisms and controls.

**Do not copy:** Do not reuse Webflow names, logos, proprietary interface artwork, customer identities, quotations, statistics, ROI claims, partner claims or product-specific promises. Source phrases below illustrate tone only; write original claims supported by the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your team' in benefits and calls to action. Use 'we' for commitments and support; refer to the product by name when explaining what it enables.
- **Rhythm:** Headlines are usually short declarations or balanced clauses; support is one or two substantive sentences. Feature titles begin with active verbs, and paragraphs explain the means after the benefit. Em dashes connect ideas without a breathless exclamation-heavy tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A forward-looking benefit expressed as a compact declaration. | 4–9 words | “Build for what’s next”<br>“More than a website builder” |
| Supporting line | Name who benefits, the job and the business consequence. | One sentence or two short sentences | “[Brand] gives every team the tools to build, manage, and grow a website that drives real revenue.” |
| Capability heading | An active verb plus a meaningful constraint removed. | 4–8 words | “Move quickly without sacrificing quality or process”<br>“Scale content without constraints” |
| Trust statement | Plain assurance, with a short emphatic final fragment. | 4–9 words | “Your data, your control. Always.” |
| Primary action | Direct action with a clear next step, sometimes a low-friction qualifier. | 2–6 words | “Get started”<br>“Get started — it's free”<br>“Talk to an expert” |
| Closing invitation | An ambitious outcome or human invitation, followed by a practical action. | 4–8 words | “Make creativity your competitive edge”<br>“Come build with us” |

**Words and phrasing to use:** build; manage; grow; bring ideas to life; your team; at scale; without constraints; built-in; control; measurable outcomes

**Avoid:** magical everything; revolutionary!!!; vague disruption language; cute assistant banter; unsupported superlatives; technical acronyms without a benefit

**Rules:**

- Pair a benefit with a mechanism: say what becomes faster, then explain the workflow or control that makes it possible.
- Use numbers only when they have context, attribution and a real basis; keep one main result per proof card.
- Keep CTA labels literal. A sales action should promise a conversation, not pretend to be an instant product action.
- Let short assertive headings carry ambition and use paragraphs for nuance, especially about governance, safety and scale.

## Do's and Don'ts

### Do

- Keep default display type at 80px, weight 600 and 1.04 line height, with -0.01em tracking.
- Align ordinary content to the same 72px desktop margins used by navigation and footer.
- Use 80px section padding and 24px or 32px local gaps to separate spacious reading from dense demonstrations.
- Keep ordinary actions at 4px radius with 16px by 24px padding.
- Use 1px #d8d8d8 rules to organize forms, FAQ rows and footer transitions.
- Give each cinematic proof card a single 40px result and an intelligible 20px descriptor.
- Include an oversized blue silhouette in the footer and a staged product/output composition elsewhere on the page.
- Keep the sharp product window separate from blurred atmosphere; apply blur to backing layers, not labels.

### Don't

- Do not turn every action into a pill; the rounded selector belongs to a narrow feature-campaign role.
- Do not use the 112px company statistic recipe as the ordinary hero headline.
- Do not cover the whole reading page in blue, purple gradients or dark cards; concentrate saturation in media and actions.
- Do not add generic soft shadows to every card; thin outlined content panels are deliberately flat.
- Do not make all section labels 12px uppercase; ordinary labels often use 20px sentence case.
- Do not shrink portrait proof cards to fit exactly three across the container; preserve their 504px width and edge overflow.
- Do not use the pale secondary action on dark conversion bands; use the #171717 variant with white text.
- Do not convert the footer into a dark compact strip; its white directory and oversized blue emblem are a distinct final composition.

## Motion and responsive

### Motion

**Observed:**

- Action colors and surfaces declare 300ms cubic-bezier(0.455, 0.03, 0.515, 0.955) transitions; animated text underlines declare background-size 450ms cubic-bezier(0.645, 0.045, 0.355, 1).
- Display reveal declares scale animation for 1.2s with cubic-bezier(0.455, 0.03, 0.515, 0.955). Other elements declare 0.75s scale animations.
- Marquee timelines declare 140s linear and 40s linear variants. Gradient headline motion declares a 5s linear infinite loop.
- Announcement hover shading declares box-shadow 0.3s cubic-bezier(0.165, 0.84, 0.44, 1).

**Transfer:**

- Use the declared slow linear rail motion for broad visual shelves and reserve faster transitions for controls and underlines.
- Keep a readable settled composition for every product scene; atmospheric movement should not replace the actual demonstration.

**Unknown:**

- Exact reveal choreography, carousel autoplay timing and interaction-driven animation sequences are not established.

### Responsive

**Observed:**

- CSS width breakpoints include 479px, 767px, 768px, 991px and 992px; a 1440px breakpoint is also present in the default landing system.
- Navigation font size uses clamp(0.8rem, 0.3598rem + 0.71vw, 1rem).

**Transfer:**

- At narrow widths, stack split text/media chapters while retaining one large demonstration per chapter; keep proof rails horizontally scrollable instead of squeezing card contents.
- Keep the footer emblem oversized and clipped, but separate its silhouette from legal and social content. Preserve the identity-versus-utility contrast.
- Reduce perspective depth and visible plane count in output galleries before sacrificing readable outputs.

**Unknown:**

- Exact mobile font sizes, menu construction, side margins, column collapse rules and motion changes are not established; the transfer rules are design guidance rather than specified mobile behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
