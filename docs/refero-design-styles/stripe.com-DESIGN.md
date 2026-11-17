# Stripe — spectral infrastructure

## Overview

A light, technically fluent marketing style with dark blue grotesk typography and sudden sweeps of violet, pink and amber light. Restrained text and hairline grids frame richly staged interfaces, abstract data sculptures and polished customer imagery. It suits ambitious software platforms and complex products that need both an expansive promise and detailed operational proof; spacious chapters contain compact, information-rich modules.

### Essentials

- A promise and its explanation share the same typographic breath: light-weight 48px/1.15 display with -0.02em tracking, then inline 32px/1.1 section heading pairs in dark ink and subdued slate.
- The opening is a luminous text stage, not a standard split hero: a roughly 1024px text span inset one grid column, a spectral folded ribbon entering from the upper right, 48px actions below, and a shallow logo rail at the base.
- Utility actions stay architectural rather than bubbly: violet rectangular buttons with 4px corners, 24px horizontal padding and 16px regular labels; compact pill actions belong to the pricing variant.
- White and ice-blue surfaces occupy most of the page; saturated color concentrates in artwork, actions and selected numbers. A deep navy technical chapter creates a sustained contrast rather than making the whole site dark.
- Product interfaces are presented as illuminated objects: white 6px-corner panels and translucent browser chrome float over folded violet–pink–amber fields, with soft shadows and fine edges. Include at least one such product stage; without interface media, construct a credible simplified workflow with real labels and data.
- Hairline architecture and data-as-light anchor the system: 1266px outer rails, 16px gutters, 96px chapter padding, 48px light-weight metrics, plus a luminous fine-line or particle data sculpture. Rebuild the sculpture as SVG curves or a radial point field when no bespoke renderer is available.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#533afd` | `--color-action` | action, link, accent | Default buttons, callout links and small controls. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender edge | `#b9b9f9` | `--color-secondary-edge` | border | Secondary action outlines. |
| Orchid light | `#cb83ff` | `--color-glow-violet` | accent, background | Violet end of the warm spectral atmosphere and data artwork. |
| Rose light | `#ff90b9` | `--color-glow-pink` | accent, background | Middle of spectral gradients, not ordinary body text. |
| Apricot light | `#ffc977` | `--color-glow-amber` | accent, background | Warm light in spectral fields. |
| Cream light | `#fff1dc` | `--color-glow-cream` | background | Warm fade between spectral art and white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, opaque interface panels and text on dark backgrounds. |
| Frosted white | `#fcfdfe` | `--color-glass` | surface | Visible browser glass over white; built from ice band at 45% alpha. Over colored art the underlying hue remains visible. |
| Ice band | `#f8fafd` | `--color-band` | background, surface | Alternating pale bands, utility cards and the default footer. |
| Blue hairline | `#e5edf5` | `--color-edge` | border | Outer rails, panel outlines and solid or dashed dividers. |
| Field edge | `#dfe6ef` | `--color-input-edge` | border | Visible field edge; rgba(212,222,233,0.75) over white. |
| Night slate | `#839bc8` | `--color-night-copy` | text | Subdued explanatory headlines on navy. |
| Muted metric | `#7d8ba4` | `--color-muted` | text | Inactive metric labels and values in the interactive proof stage. |
| Subdued slate | `#64748d` | `--color-subdued` | text | The explanatory half of inline heading pairs and secondary attribution. |
| Blue slate | `#50617a` | `--color-body` | text | Paragraphs, feature explanations and footer links. |
| Night rail | `#182659` | `--color-night-edge` | border | Fine rails and separators within the technical chapter. |
| Blue-black ink | `#061b31` | `--color-ink` | text | Default headings and emphasized text. |
| Technical navy | `#0d1738` | `--color-night` | background | Extended technical storytelling chapter. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial recommendation modules | Aubergine display backing | `#493f4e` | `--color-editorial-back` | background | Solid backing for an editorial object. |
| pricing pages | Pricing ice | `#f6f9fc` | `--color-pricing-canvas` | background, surface | Pricing canvas and rate inset. |
| pricing pages | Pricing navy | `#0a2540` | `--color-pricing-ink` | text, action | Denser pricing hierarchy and newsletter action. |
| pricing pages | Pricing slate | `#425466` | `--color-pricing-body` | text | Pricing explanations. |
| pricing pages | Pricing blurple | `#635bff` | `--color-pricing-action` | action, link, accent | Pricing pill actions, captions and links. |
| pricing pages | Pricing rule | `#e7ecf1` | `--color-pricing-edge` | border | Pricing table dividers. |
| pricing pages | Rate well | `#fafbfd` | `--color-rate-well` | surface | Very pale right-hand rate column. |

## Typography

- **sohne-var** — All marketing headings, paragraphs, navigation and actions. A clean neo-grotesk with open counters and economical width; light-weight display text feels articulate rather than monumental. OpenType features: "ss01". If unavailable, use **Inter**. Use 300 and 400 for the default system; keep negative display tracking and check line wraps. Font stack: "sohne-var", "Inter", "SF Pro Display", sans-serif.
- **SourceCodePro** (only for code demonstrations) — Code inside technical demonstration panels. Small, even-width programming text, not a marketing headline face. If unavailable, use **Source Code Pro**. Font stack: "SourceCodePro", "Source Code Pro", SFMono-Regular, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-heading | sohne-var | 300 | 56px | 1.03 | -0.025em | Centered, compact heading above the panoramic proof stage. |
| display | sohne-var | 300 | 48px | 1.15 | -0.02em | Default opening promise and its equally sized continuation. |
| metric | sohne-var | 300 | 48px | 1.03 | -0.02em | Proof numbers; also editorial hero text in the culture variant. |
| heading | sohne-var | 300 | 32px | 1.1 | -0.02em | Main section heading and same-size subdued continuation; also closing call. |
| subheading | sohne-var | 300 | 26px | 1.12 | -0.01em | Capability lead, quote and medium panel heading. |
| card-heading | sohne-var | 300 | 22px | 1.1 | -0.01em | Story captions and smaller expandable capability titles. |
| closing-body | sohne-var | 300 | 20px | 1.4 | -0.01em | Support paragraph in the final conversion band. |
| body-lg | sohne-var | 300 | 18px | 1.4 | normal | Section introductions and question labels. |
| body | sohne-var | 300 | 16px | 1.4 | normal | Paragraphs, card explanations and metric captions. |
| body-emphasis | sohne-var | 400 | 16px | 1.4 | normal | Short feature leads, often inline with a light-weight explanation. |
| button | sohne-var | 400 | 16px | 1 | normal | Default primary and secondary action labels. |
| footer-link | sohne-var | 300 | 16px | 1.25 | normal | Compact footer directory links. |
| navigation | sohne-var | 400 | 14px | 1 | normal | Global navigation triggers and compact header actions. |
| eyebrow | sohne-var | 400 | 14px | 1.4 | normal | Sentence-case contextual labels above the hero. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | sohne-var | 500 | 56px | 68px | -0.02em | More assertive pricing opening; no stylistic-set requirement. |
| pricing pages | pricing-heading | sohne-var | 500 | 38px | 48px | -0.0053em | Catalog and FAQ chapter headings. |
| pricing pages | pricing-plan | sohne-var | 500 | 26px | 36px | normal | Plan titles and major rate callouts. |
| pricing pages | pricing-product | sohne-var | 425 | 18px | 24px | 0.011em | Product header in the catalog. |
| pricing pages | pricing-body | sohne-var | 300 | 15px | 1.6 | 0.013em | Dense feature descriptions and supporting pricing copy. |
| pricing pages | pricing-label | sohne-var | 425 | 15px | 1.6 | 0.013em | Table feature names. |
| pricing pages | pricing-rate | sohne-var | 425 | 15px | 19px | 0.013em | Rates within the catalog. |
| pricing pages | pricing-button | sohne-var | 425 | 15px | 24px | normal | Compact pill action labels. |

**Notes:**

- The default hierarchy gets scale from light weight and tight tracking, not boldness. Keep the dark first clause and subdued continuation at identical size and weight.
- Use sentence case throughout. Inline heading pairs read as one continuous statement even when their colors differ.
- Pricing is a separate, denser typographic system: weights 425–500, positive 0.2px tracking for small catalog text and a narrower overall container. Do not average it with the default light-weight system.
- The culture opening uses the metric recipe as a two-line editorial headline. Code remains inside demonstrations, at 12px/24px with medium weight rather than entering the marketing hierarchy.

## Layout

**Density:** Airy chapters with compact internal detail: large media and generous section padding coexist with closely spaced captions and directory links.

### Spacing

**Spacing system:**

- **grid** 8px — Dominant layout rhythm; 12px and 4px serve tighter text and utility spacing rather than defining the chapter grid.

| Value | Use |
| --- | --- |
| 8px | Action-group gap, small label/support separation. |
| 12px | Metric-to-caption gap and close card stacks. |
| 16px | Column gutter and container inner side padding. |
| 24px | Button horizontal padding, panel padding and heading-to-action separation. |
| 32px | Media-to-caption groups and action separation in closing calls. |
| 40px | Opening text-group spacing and selected carousel heading gaps. |
| 64px | Heading-to-media spacing, stacked subsection rhythm and footer group separation. |
| 80px | Proof stage top padding and separation between long audience chapters. |
| 96px | Default major-section vertical padding. |
| 128px | Pricing chapter and footer vertical padding. |

### Containers and grids

- **Rail container**: max width 1266px · side padding 16px. Centered outer frame with 1px left and right rails; leaves 1232px of usable content at desktop.
- **Twelve-column scaffold**: 12 columns · gap 16px. Core composition grid; hero text is inset one column, section headlines often occupy eight columns, paired media occupy six each.
- **Three-up detail grid**: 3 columns · gap 16px. 400px-wide feature or proof modules within the main content span; align top edges and place explanation below media.
- **Four-up metric rail**: 4 columns · gap 0px. Equal metric cells separated by hairlines; product and culture variants use 316px-wide cells.
- **Pricing container** (only for pricing pages): max width 1080px · side padding 16px. Narrower catalog frame. A 270px navigation column sits beside an 810px product stack; product rate rows split 55% description and 45% price.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions and fields | 4px |
|  | Media and product panels | 6px |
| pricing pages | Pricing cards | 8px |
| pricing pages | Pricing actions | 16.5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Browser float | `0px 15px 35px 0px rgba(23,23,23,0.08)` | Translucent browser frames over spectral artwork. |
|  | Inner panel | `0px 3px 6px 0px rgba(23,23,23,0.06)` | White panel inside a larger product stage. |
| pricing pages | Catalog card | `0px 2px 5px -1px rgba(50,50,93,0.25), 0px 1px 3px -1px rgba(0,0,0,0.3)` | Long pricing product cards. |
| pricing pages | Plan elevation | `0px 13px 27px -5px rgba(50,50,93,0.25), 0px 8px 16px -8px rgba(0,0,0,0.3)` | Opening plan pair and selected proof cards. |

### Surfaces

#### White canvas · level 0

**Use:** Primary marketing canvas.

**CSS:** `background: #ffffff; color: #061b31`

#### Rail frame · level 0

**Use:** Continuous structural edges shared by otherwise separate sections.

**CSS:** `max-width: 1266px; padding-left: 16px; padding-right: 16px; border-left: 1px solid #e5edf5; border-right: 1px solid #e5edf5`

**Observed:** Rails persist across white and pale bands and do not turn into thick card borders.

**Transfer:** Use the same frame throughout long-form content.

#### Ice band · level 0

**Use:** Soft section contrast and closing utility areas.

**CSS:** `background: #f8fafd`

#### Technical night · level 0

**Use:** Technical depth, integrations and high-scale proof.

**CSS:** `background: #0d1738; color: #ffffff`

**Observed:** A sustained full-width navy band with dark blue rails and slate-blue explanations, not black.

**Transfer:** Reserve it for a meaningful shift from promise to technical substance.

#### Browser glass · level 2

**Use:** Outer shell of a staged product interface.

**CSS:** `background: rgba(248,250,253,0.45); border-radius: 6px; outline: 1px solid rgba(229,237,245,0.5); backdrop-filter: blur(12px); box-shadow: 0px 15px 35px 0px rgba(23,23,23,0.08)`

**Observed:** Translucent chrome surrounds a much more opaque white interface; a slim address capsule and tiny window controls make the framing recognizable.

**Transfer:** Keep transparency in the frame rather than behind readable interface content.

#### Opaque product panel · level 3

**Use:** Readable interface content within a colorful stage.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: 0px 3px 6px 0px rgba(23,23,23,0.06)`

#### Spectral atmosphere · level 0

**Use:** Warm proof-stage light, fading to the page canvas.

**CSS:** `background: radial-gradient(102.68% 99.11% at 50% 104.6%, #cb83ff 0px, #ff90b9 15.77%, #ffc977 30.62%, #fff1dc 50.11%, #ffffff 63.1%, #f8fafd 98.81%)`

**Observed:** The strongest color rises from the bottom center while the top remains almost white.

**Transfer:** Match the warm-to-violet soft glow; exact intermediate stops are not essential.

#### Catalog surface · level 1

**Only for:** pricing pages

**Use:** Long product-and-rate cards on a pale canvas.

**CSS:** `background: #ffffff; border-radius: 8px; box-shadow: 0px 2px 5px -1px rgba(50,50,93,0.25), 0px 1px 3px -1px rgba(0,0,0,0.3); overflow: hidden`

**Observed:** White feature cells sit beside subtly tinted rate wells; dashed dividers make the dense information feel like a ledger.

**Transfer:** Use actual price units and qualifiers, not oversized decorative rates everywhere.

## Components

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #533afd; color: #ffffff; border-radius: 4px; padding: 15.5px 24px 16.5px; height: 48px; box-sizing: border-box`

**Text style:** `button` — sohne-var 400 · 16px/1

**Observed:** Label followed by a small right chevron; naturally sized to its label. Header versions are 40px tall and more compact.

**Transfer:** Use one main action per local decision group.

### Secondary button

**Use:** Alternate conversion or editorial action.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #533afd; border: 1px solid #b9b9f9; border-radius: 4px; padding: 14.5px 24px 15.5px; height: 48px; box-sizing: border-box`

**Text style:** `button` — sohne-var 400 · 16px/1

**Observed:** Unfilled outline treatment sits next to the primary action. Editorial actions can stand alone at the right of a caption.

### Navigation trigger

**Use:** Global navigation category.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 12px 0px; height: 40px; border-radius: 4px; color: #061b31`

**Text style:** `navigation` — sohne-var 400 · 14px/1

**Observed:** Wordmark at the left, evenly spaced category triggers in the middle, sign-in and sales actions at the right. Category menus use a small downward chevron; the header occupies 76px.

### Callout link

**Use:** Low-friction next step under a feature or story.

**CSS:** `color: #533afd; font-weight: 400`

**Text style:** `button` — sohne-var 400 · 16px/1

**Observed:** Short verb-object label followed by a tiny chevron, without an enclosing button surface. Night-band links become a lighter periwinkle.

### Feature detail

**Use:** Compact explanation below a large media demonstration.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 16px`

**Text style:** `body` — sohne-var 300 · 16px/1.4

**Observed:** Small outlined icon above text; the text begins with a regular-weight 16px lead and continues inline in light-weight slate. A Callout link follows below. Typically three equal modules share one row.

**Transfer:** Keep each module a concise consequence of the demonstration, not another large card.

### Metric cell

**Use:** Quantified proof beneath a section introduction.

**CSS:** `display: flex; flex-direction: column; gap: 12px; padding: 36px 16px; border-right: 1px solid #e5edf5; border-bottom: 1px solid #e5edf5`

**Text style:** `metric` — sohne-var 300 · 48px/1.03 · tracking -0.02em

**Observed:** A large light-weight value sits above a small 16px caption. Four cells fill a shared ruled rail; the last cell has no right divider. The panoramic proof variant centers its values and mutes inactive metrics; culture and technical variants use gradient-clipped values.

**Transfer:** Use a real value and a specific unit or time period in the caption.

### Footer column

**Use:** Grouped site directory.

**CSS:** `display: flex; flex-direction: column; gap: 64px; padding: 64px 0px; border-right: 1px dashed #e5edf5`

**Text style:** `footer-link` — sohne-var 300 · 16px/1.25

**Observed:** Four columns occupy the rail frame. Within each group, links have 4px gaps below a darker regular-weight heading. Dashed separators and substantial empty space keep a long directory ordered; the last column drops its right divider.

### Newsletter field

**Use:** Newsletter signup below the directory.

**CSS:** `display: grid; height: 48px; max-width: 433px; border: 1px solid rgba(212,222,233,0.75); border-radius: 4px; overflow: hidden`

**Text style:** `body` — sohne-var 300 · 16px/1.4

**Observed:** A label sits above the email field; a separate Primary button follows across an 8px gap, with small consent copy below. Pricing uses an integrated pill form and a dark pill action instead.

### Pricing pill

**Only for:** pricing pages

**Use:** Compact action within dense pricing content.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #635bff; color: #ffffff; padding: 3px 12px 6px 16px; border-radius: 16.5px; height: 33px; box-sizing: border-box`

**Text style:** `pricing-button` — sohne-var 425 · 15px/24px

**Observed:** The right arrow is a compact 10px stroked icon. The dark custom plan uses a cyan action rather than the default violet.

**States:** Declared: hover background-color var(--buttonColor), opacity 1; focus-visible not specified for this action.

### Pricing product card

**Only for:** pricing pages

**Use:** Product header, benefits and itemized rates in the catalog.

**CSS:** `background: #ffffff; border-radius: 8px; box-shadow: 0px 2px 5px -1px rgba(50,50,93,0.25), 0px 1px 3px -1px rgba(0,0,0,0.3); overflow: hidden; max-width: 810px`

**Text style:** `pricing-body` — sohne-var 300 · 15px/1.6 · tracking 0.013em

**Observed:** Header has 24px padding, product label, short description, checkmarked benefits and a Pricing pill on the right. Subsequent rows divide a wider feature explanation from a pale rate well, with fine solid or dashed separators and 16px 24px cell padding.

**Transfer:** Use multiple compact rows for complex pricing rather than compressing every condition into a single plan tile.

## Imagery and graphics

### Spectral folded ribbon

**Use:** Signature opening artwork and luminous backing for product stages.

**Observed:** A huge silk-like folded sheet sweeps from the upper right, narrows toward the lower right and runs off the page. Amber and orange interiors meet pink, violet and pale blue edges. Many fine parallel striations suggest light travelling along a surface; it overlaps the text area but leaves the left half mainly white.

**Transfer:** Recreate the material and directional energy, not a particular ribbon silhouette. A layered vector sheet with fine line texture is the minimum acceptable substitute; a generic blurred gradient blob is not equivalent.

**Build:** Use a full-width SVG behind content with two broad curved paths entering beyond the top-right edge, sweeping diagonally toward the lower right. Fill the paths with a multi-stop gradient from pale blue through orchid, pink and amber. Add 60–100 thin parallel curved strokes clipped to the sheet, with low-opacity white and violet strokes. Layer a narrower amber highlight along the fold and a soft violet shadow under its pink edge. Fade the left edge to white; keep readable text and actions above the art.

### Illuminated interface still life

**Use:** Large feature stages and bento demonstrations.

**Observed:** White checkout, dashboard, chart and configuration panels are layered at unequal sizes, often partially clipped by a 6px-corner stage. A translucent browser frame and a smaller foreground panel sit over warm-to-violet folded fields. The media is much larger than the accompanying explanation; fine interface text is detailed but not promoted to headline scale.

**Transfer:** Show one believable task and its result with a main window plus one small explanatory panel. If the new product lacks UI, create a labeled diagram or record card and an outcome chart using the same glass/opaque layering.

**Build:** Create a 6px-corner overflow-hidden art container. Behind Browser glass, place two oversized curved SVG sheets with pink, violet and amber gradients; add fine parallel strokes. Add an Opaque product panel as the main window and a smaller white card overlapping its upper-right edge. Keep text outside the brightest art or on opaque panels.

### Data as light

**Use:** Signature proof sculpture and technical scale storytelling.

**Observed:** The light stage uses a radial burst of thin magenta-violet rays ending in tiny points over a warm sunrise field. The dark chapter uses many luminous curved strands crossing like a flowing hourglass, fading at their ends. Below it, three gradient numbers share the line work's color family.

**Transfer:** Represent the new product's scale as a geometric data sculpture rather than literal industry clip art. Use fine-line SVG geometry if no 3D or canvas system is available.

**Build:** For a light field, position a radial center below the bottom edge of a wide SVG; draw 120–200 rays of varying length with 1px strokes at low violet/pink opacity and 1–2px endpoint circles. Back with Spectral atmosphere. For the night version, draw 40–60 cubic Bezier curves in a roughly 1232px by 460px viewBox, crossing near the middle with narrow spacing at the crossing and broad fans at both ends. Use violet, pink and peach gradients with transparent endpoints; duplicate a few curves under a 10px blur for restrained bloom.

### Customer editorial media

**Use:** Social proof, story rows and carousels.

**Observed:** Large landscape photography anchors an expanded story; other customers appear as saturated portrait-format brand art with captions and violet links below. Portrait cards have modest 6px corners, 16px gutters and little surrounding card chrome. Logos appear on the art or as small marks, never as an all-purpose decorative background.

**Transfer:** Use real customer context or carefully art-directed abstract identity images, each with a specific result caption. Keep large media, small type and understated framing.

### Compressed editorial carousel

**Use:** News and research storytelling.

**Observed:** One wide active image is followed by progressively narrower slivers of adjacent images; small square previous/next controls align above the right edge. A two-tone caption and outlined action sit below the image strip.

**Transfer:** Keep the sense of a shelf of stories, using a wide selected panel and compressed previews instead of a uniform card row.

**Build:** Use a clipped flex row within the main rails. Give the active media about two thirds of the row width and distribute the remaining width among shrinking preview panels, with 16px gaps. Put caption details outside the image and use separate 40px square controls.

### Editorial object

**Only for:** editorial recommendation modules

**Use:** A distinctive reflective interlude near the end of a long marketing story.

**Observed:** A physical book cover is centered on an aubergine backing beside a much paler text panel. The object is 296px by 440px within a 504px-wide backing. Title and author use a dark/subdued pair; a short essay and small publication links provide depth rather than another sales pitch.

**Transfer:** Use a relevant publication, designed artifact or field guide. Render a flat cover with subtle depth and shadow if product photography is unavailable; preserve the object-and-commentary contrast.

### Culture collage and workplace photography

**Only for:** culture and recruitment pages

**Use:** Editorial opening artwork and evidence of working life.

**Observed:** The opening combines a tightly framed botanical still life with vivid violet-orange ribbon material and tiny natural detail. Later images show sunlit, plant-rich interiors, stairs, libraries and people working informally, with warm wood, green upholstery and natural light. Photography appears as wide architectural views, paired landscapes and a final three-up portrait group.

**Transfer:** Commission tactile art that links a natural subject to the spectral material, then use candid, environment-led photographs of real work. Avoid posed corporate headshot grids.

**Build:** For the collage, place a full-width macro photograph of a pale organic form behind two curved SVG ribbon bands with deep violet edges and orange-pink fold highlights. Let the organic texture remain crisp and the ribbon weave behind and in front of it.

### Icons

**Observed:** Utility chevrons and arrows are small and crisp: 16px navigation icons use 1.8px strokes; pricing arrows are 10px with 2px strokes. Feature icons use sparse violet outline geometry in small pale outlined squares; product badges and customer marks can be multicolored.

**Transfer:** Use simple geometric icons aligned to text baselines. Separate utility icon style from rich logos and illustrative product art.

## Section recipes

How recurring sections are built.

### First screen: Luminous promise opening

**Observed:** A 76px navigation strip sits above a white rail-framed opening. Inside the 1266px frame, the copy is inset by one of twelve columns and spans roughly 1024px. A small contextual line precedes the display by about 40px. The 48px light-weight headline begins in ink and continues at identical scale in subdued color across several lines; the first promise is nearly one line wide, not a huge bold stacked slogan. Layers run white canvas → fine rails → Spectral folded ribbon extending beyond the upper and right edges → text and actions. The ribbon fills much of the right half without becoming a separate boxed illustration. The action row has a filled violet and outlined companion with an 8px gap. Within the first 900px, navigation, full promise/support, actions, ribbon and a 72px logo rail are visible; the next 32px section heading begins at the bottom, while the detailed product scenes remain below.

**Transfer:** Use this as the default landing-page opening. Replace the contextual datum with a relevant proof or product-category label and keep the sentence-led headline/continuation relationship. Without bespoke art, use the vector Spectral folded ribbon recipe. Product-detail pages can center a 32px two-tone promise above an oversized browser demonstration. Pricing opens with a 56px medium-weight statement and two contrasting plan cards over a diagonal light ribbon. Culture pages open with a left-aligned 48px editorial headline followed by full-width tactile imagery.

**Avoid:** Do not replace this with an isolated left-column headline and a small right-column dashboard, a centered giant bold slogan, or a full-screen colored gradient that removes the white reading area.

**Text style:** `display` — sohne-var 300 · 48px/1.15 · tracking -0.02em

### Continuous heading pair

**Observed:** An ink 32px heading runs directly into a slate continuation at the same weight, size and line height, within an approximately 856px text span. Subsections use the same mechanism at 26px. In the night chapter white replaces ink and blue slate replaces the light-theme subdued text.

**Transfer:** State the capability in the first clause and its consequence in the continuation, allowing natural wrapping across both.

**Text style:** `heading` — sohne-var 300 · 32px/1.1 · tracking -0.02em

### Modular product bento

**Observed:** A large asymmetric grid uses 16px gutters: one two-column-wide demonstration beside a narrower panel, smaller vertical scenes below, then a full-width dashboard stage. Titles sit at the upper-left of each media card, with a small utility icon at the upper-right. White panels contain rich luminous artwork rather than a uniform set of text tiles.

**Transfer:** Map a small number of genuinely different capabilities to differently proportioned demonstrations; keep the visual weight proportional to importance.

### Audience chapter

**Observed:** A 26px capability statement and button occupy the left of a twelve-column header; an 18px paragraph occupies the right. Large customer media or a staged product scene follows, then three Feature detail modules. Chapters have substantial 64px–80px separation.

**Transfer:** Use for distinct user situations, workflows or product packages. Let each chapter connect promise, proof and practical support rather than merely listing audience names.

**Text style:** `subheading` — sohne-var 300 · 26px/1.12 · tracking -0.01em

### Panoramic quantified proof

**Observed:** A centered 56px heading sits above a full-width four-part metric rail. Active and inactive values differ through ink versus muted slate, while captions stay small. The lower half becomes Data as light over Spectral atmosphere; a tiny time-of-day control sits to the right. Product-specific proof uses left-aligned Metric cells without the full sculpture.

**Transfer:** Make scale tangible through a small number of comparable metrics and one luminous visualization. Give each metric enough context to be meaningful.

**Text style:** `proof-heading` — sohne-var 300 · 56px/1.03 · tracking -0.025em

### Technical depth chapter

**Observed:** Technical night holds multiple linked explanations within the same rail frame. Continuous heading pair introduces the chapter; a node-and-connector diagram uses thin dotted paths and small violet labels, a flowing line sculpture leads into gradient metrics, and a three-up row shows different implementation routes with demonstrations above compact explanations.

**Transfer:** Use one sustained contrast band to explain interoperability, scale and adoption paths. Rebuild the diagram with labeled nodes and restrained violet connectors, not generic futuristic imagery.

### Expandable capability or questions

**Observed:** Product benefit rows are around 72px tall with a 22px title, a small icon at left and a square plus/minus control at right. An expanded benefit reveals a wide colorful product stage and three compact explanations. FAQ variants use a roughly one-third left heading column and two-thirds question stack; questions use 18px text and dashed separators, with answers at 16px. Pricing instead stacks white 60px question rows across its narrower frame.

**Transfer:** Use benefits for demonstration-led exploration and questions for practical objections; preserve the distinction between rich expanded media and text answers.

### Editorial interlude

**Observed:** Compressed editorial carousel creates a broad active story with narrow adjacent previews. Editorial object can follow as a two-part light/dark-backed artifact-and-essay module, with the familiar heading pair above.

**Transfer:** Use a real intellectual or practical resource to widen the story beyond conversion; choose either a story shelf or a considered artifact appropriate to the product.

### Pricing ledger

**Observed:** The opening plan pair is white standard versus dark blue custom, each with description and action plus a rate or structured benefits at right. A translucent floating anchor strip follows. The long catalog uses a sticky 270px left directory beside 810px Pricing product cards, 24px vertical gaps, 55/45 feature/rate rows and pale rate wells. Later proof includes a report cover and a wide customer story before questions.

**Transfer:** For complex catalogs, retain navigable itemization and clear price qualifiers. For simpler products, reduce the number of cards without turning the content into an ornamental feature matrix.

### Closing call and directory

**Observed:** The default closing call is a pale band with 96px vertical padding: a 32px lead, 20px support and two actions on the left; one or two compact feature/link modules sit to the right. Small legal notes are separated before a four-column ruled directory. The directory ends with newsletter signup, a locale link, copyright and a small slanted corner emblem. Product-detail pages can close on white; pricing uses 128px rhythm, a white call band and pale footer with an integrated newsletter pill. Culture pages end with three large photographic destination cards and the directory, without the sales call or newsletter.

**Transfer:** Offer a direct conversion path plus one practical alternative, then a genuinely useful directory. End with restrained locale and ownership details rather than another enormous marketing headline.

**Text style:** `heading` — sohne-var 300 · 32px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Promise → visual demonstration → evidence of fit and scale → capability or adoption chapters → deeper proof and useful resources → practical next step → directory.

### Broad platform marketing landing page

1. **Promise** — Large continuous promise and explanation over spectral ribbon, paired actions and a logo rail.
2. **Product demonstration** — Asymmetric bento of interface and data scenes.
3. **Quantified proof** — Centered heading, interactive metric rail and panoramic data sculpture.
4. **Audience fit** — Repeated split headers, large customer imagery, portrait story cards and product stages, followed by compact service explanations and a centered attributed quote.
5. **Technical substance** — Sustained navy chapter with integration diagram, flowing scale artwork and three implementation paths.
6. **Editorial depth** — Compressed story shelf and physical-object recommendation.
7. **Closing call** — Pale conversion band, legal notes, four-column directory, separate newsletter field and final locale/copyright row.

**Transfer:** Balance expansive promise with progressively more concrete demonstrations; choose chapter order for the new decision journey rather than copying every block.

### Focused product-detail marketing page

1. **Promise and demonstration** — Product-local navigation, centered two-tone 32px lead, paired actions and oversized glass browser stage, followed by customer logos.
2. **Problem framing** — Pale opportunity band with a small sentence-case label, medium statement and two explanatory text columns.
3. **Capability chapters** — Three horizontal product modules, then expandable benefits with vivid wide media and compact explanations.
4. **Proof** — Four-cell metrics, three customer story portraits and compact external-validation modules.
5. **Completeness** — A two-by-two capability list and a horizontal carousel of related interface demonstrations.
6. **Objection handling** — Split-layout questions and a three-up resource group.
7. **Closing call** — White conversion band with pricing link, supporting notes, directory, newsletter and final locale row.

**Transfer:** Use the centered opening and denser explanatory modules when a visitor already understands the broad product category.

### Culture and recruitment narrative

1. **Editorial promise** — Left-aligned two-line 48px statement followed by wide botanical-and-spectral collage.
2. **Working context** — Split text introduction, paired workplace photographs and three compact operating-principle explanations.
3. **Meaningful challenge** — Another split text chapter and wide architectural photograph.
4. **Scale proof** — Logo rail, editorial argument and four gradient-number cells.
5. **Exploration** — Compressed news shelf followed by split-layout questions.
6. **Closing destinations** — Three large workplace-image cards direct readers to deeper fit, early-career and role information; shared directory ends with locale and copyright but no newsletter.

**Transfer:** Use tactile imagery and actual working environments to turn abstract mission into tangible conditions, and close with useful destinations rather than a sales pitch.

### Complex product catalog and pricing decision page

1. **Pricing promise** — Medium-weight 56px statement, white and dark plan pair over a diagonal spectral band and floating anchor navigation.
2. **Included value** — Four-column compact feature groups.
3. **Price exploration** — Persistent section navigation beside long white itemized product cards with pale rate wells.
4. **Custom fit** — Split custom-package pitch and raised capability card, then four compact benefits.
5. **Commercial proof** — Report-cover proof module and wide customer story.
6. **Objection handling** — Full-width white question rows on the pale canvas.
7. **Closing call** — White conversion band with small supporting destinations and notes, then pale directory and integrated pill newsletter with copyright.

**Transfer:** Preserve the compact ledger hierarchy for extensive offerings while making category navigation useful; use the pricing-specific palette, weight and action shape only in this context.

## Writing

Confident, technically literate and matter-of-fact, with ambition expressed through concrete capability and evidence rather than hype. Warmth comes from understanding the reader's work and offering a practical next step.

**Do not copy:** Do not reuse Stripe's name, wordmark, slanted emblem, customer identities, proprietary artwork, product names, customer quotations, published statistics or performance claims. Source examples illustrate syntax and tone only; replace them with truthful new-product content.

- **Addressing the reader:** Use you and your for outcomes and constraints. Use we for organizational intent, and the product's name when explaining what the system actually does.
- **Rhythm:** Short capability clauses lead into a fuller explanation. Headlines are usually sentence case and often end with a period; longer support sentences use controlled lists and em dashes. Actions stay brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the enabling infrastructure or product, then connect it directly to a business result. | 6–10 words | “Financial infrastructure to grow your revenue.”<br>“Monetize faster with [Brand] Billing.” |
| Heading continuation | Follow a compact capability statement with a same-scale explanation of breadth or flexibility. | 8–18 words | “Run your business on a reliable platform that adapts to your needs.”<br>“Manage pricing, reduce churn, and grow revenue—on one platform.” |
| Feature lead | Begin with a concrete verb and a practical object; name the change in the reader's work. | 3–9 words | “Connect to existing systems.”<br>“Set up quickly, with or without code.” |
| Proof caption | Pair a number with a specific activity and time period, not an unexplained superlative. | 5–12 words | “in failed payments recovered in 2025” |
| Editorial headline | Frame purposeful work or curiosity without sounding like an advertisement. | 2–8 words | “Stay curious”<br>“Entrepreneurship starts with ideas.” |
| Primary action | Plain imperative or clear next destination. | 2–4 words | “Get started”<br>“Contact sales”<br>“Open roles” |

**Words and phrasing to use:** build; grow; adapt; integrate; launch; scale; flexible; infrastructure; globally; with or without code; get started

**Avoid:** revolutionary; game-changing; magic; unleash your potential; the ultimate solution; effortless everything

**Rules:**

- Tie every broad claim to a demonstration, mechanism or relevant proof.
- Describe outcomes and implementation choices together; do not turn all headings into abstract benefit slogans.
- Use parallel verbs for lists of capabilities, and give each module one coherent job.
- Keep actions specific to the next step; distinguish reading, exploring, starting and contacting.
- Explain qualifiers and commercial conditions plainly, without burying the unit that makes a number meaningful.

## Do's and Don'ts

### Do

- Keep default display at weight 300 and -0.02em tracking; let light-weight scale carry authority.
- Join dark and subdued section clauses at the same 32px/1.1 recipe.
- Carry the 1px rails through white, pale and navy bands, changing only the edge color in the dark chapter.
- Use 16px media gutters and 64px–96px chapter rhythm so dense modules remain breathable.
- Keep spectral color concentrated behind objects and within data art while preserving an expansive white reading field.
- Layer translucent 6px browser chrome around opaque white content, with only subtle soft shadows.
- Pair large 48px metrics with compact contextual captions and fine ruled cells.
- Use the ending as a practical service area: clear conversion choices, useful directory groups and restrained final ownership details.

### Don't

- Do not make the default typography heavy like the pricing variant; weights 425–500 belong to its denser commercial system.
- Do not round ordinary marketing actions into pills; the core shape is 4px corners at 48px height.
- Do not turn every white feature module into a raised shadow card; elevation belongs mainly to staged interfaces and pricing cards.
- Do not use an all-black technical section; preserve blue navy and blue-slate text relationships.
- Do not apply rainbow text to paragraphs or all headings; gradient-clipped typography is a selective metric treatment.
- Do not replace fine data strands with thick neon tubes or busy sci-fi HUD ornament.
- Do not center every chapter; most capability headers are left-aligned or split across the grid.
- Do not let long catalog rows grow into giant rate displays; dense pricing uses 15px labels and rates with clear qualifiers.

## Motion and responsive

### Motion

**Observed:**

- Pricing actions declare background-color and opacity transitions at 0.3s with cubic-bezier(0.25, 1, 0.5, 1); hover preserves opacity 1 and uses a button-color variable.
- Declared arrow entrance/exit keyframes exist for pricing navigation. Interactive controls also include story carousels, expandable questions and a time-of-day selector.

**Transfer:**

- Keep luminous artwork legible as a complete still composition; use small utility controls for local changes rather than making every section an animated event.
- Use the declared pricing action timing only for that scoped action system.

**Unknown:**

- Default marketing-button hover/focus appearance and most artwork animation timing are unspecified.
- The exact transition between compressed carousel panels and alternate time-of-day art is unspecified.

### Responsive

**Observed:**

- The measured desktop frame is 1440px wide. Core layout uses a twelve-column scaffold and a 1266px maximum frame.
- Pricing declares multiple width boundaries including 599px/600px, 899px/900px/901px and 1111px/1112px; no complete alternate layouts are established here.

**Transfer:**

- On narrow layouts, keep the luminous ribbon at an edge and preserve a white reading field; stack the paired display clauses without changing their relative weight.
- Collapse feature and metric groups into fewer columns while retaining their shared rules and 16px gutters. Stack the glass/product scene below its explanation rather than shrinking its labels to illegibility.
- For a narrow pricing catalog, make category navigation compact and keep each rate adjacent to its feature description instead of retaining a desktop sidebar.

**Unknown:**

- Exact mobile typography, rail offsets, breakpoints for the default marketing system and mobile navigation behavior are not specified; the collapse rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
