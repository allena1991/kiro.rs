# Aaru — worlds in motion

## Overview

A cinematic, evidence-minded style for ambitious software and technical services. Electric blue introduces a mostly black world of regular-weight grotesk typography, photographic miniatures and monochrome particle sculptures. Spacious editorial chapters alternate with dense proof panels; rounded frames keep the technical imagery tactile rather than clinical.

### Essentials

- A saturated opening becomes a dark editorial journey: use an electric-blue #1019ec first screen, then predominantly #000000 with #0d0d0d and #1a1a1a panels. Blue is a major opening field, not a repeating fill for every section.
- The promise is modest in type and immense in setting: a 48px/1.05 regular grotesk headline with -0.03em tracking occupies a 580px column beside floating photographic worlds; keep the opening at 900px high on desktop with proof along its bottom edge.
- Sentences split into assertion and echo: 30px/1.1 headings use -0.02em tracking, a white first line and a 50%-white second line, with occasional #388cff emphasis rather than heavier weight.
- Actions resemble small instrument labels inside soft capsules: primary buttons are white, 44px high, 100px radius, with 14px uppercase text and 0.1em tracking; secondary actions remain bare text with a small arrow.
- Information becomes a spatial object: include a monochrome dot-field sculpture in a 32px-radius charcoal stage and reuse its texture in proof art. Without 3D assets, an SVG field of small gray and white points arranged into a coherent volume is the minimum equivalent.
- Reality brackets the abstraction: stage circular photographic worlds in the opening and a broad, darkened overhead photograph in the closing call. Use relevant work, places or environments when there is no literal product imagery.
- Proof is drawn like calibrated machinery: thin 1px rules, 12px tracked uppercase labels, 24px numerals and 24px-high striped meters make results tangible without giant statistics.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#1019ec` | `--color-electric` | background, accent | Expansive opening background and restrained brand accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Outcome green | `#0ae77a` | `--color-result` | accent | A single observed-result meter contrasted with white comparison meters. |
| Signal blue | `#388cff` | `--color-signal` | text, accent, border | Contrast sentence, focus rings and explanatory chart highlights. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface, action | Headings, active text, solid conversion actions and light demonstration chapters. |
| Black canvas | `#000000` | `--color-canvas` | background, text | Default canvas and dark text on white actions or light chapters. |
| Recessed charcoal | `#0d0d0d` | `--color-recess` | surface | Large contrast panel and technical dark cards; also the visible result of 5%-white over black. |
| Fine white wash | `#0f0f0f` | `--color-glass-wash` | surface | 6%-white glass treatment over black; over imagery the backing remains visible. |
| Raised charcoal | `#1a1a1a` | `--color-card` | surface | Media stages, proof cards and testimonial panels; also 10%-white over black. |
| Quiet edge | `#1a1a1a` | `--color-edge` | border | 10%-white hairlines over black, around proof cards, fields and logo cells. |
| Half-white text | `#808080` | `--color-muted` | text | Secondary heading lines, descriptions and labels; white at 0.5 alpha over black. |
| Soft white | `#cccccc` | `--color-hero-support` | text | Opening support text; white at 0.8 alpha over its backing. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical explainers | Amber annotation | `#f4d778` | `--color-note` | text, accent | Note icons and small disclosure actions inside amber callouts. |
| technical explainers | Amber note wash | `#18160c` | `--color-note-wash` | surface | Visible 10% #f4d778 over black in explanatory callouts. |
| company and editorial lists | Editorial rule | `#333333` | `--color-strong-edge` | border | 20%-white rules on black. |

## Typography

- **ABC Oracle** — All marketing headings, paragraphs, labels and controls. A restrained contemporary grotesk with open lowercase forms; regular weight carries almost the entire hierarchy. If unavailable, use **Inter**. Use 400 with the stated tracking; preserve the narrow headline measure. Font stack: "ABC Oracle", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ABC Oracle | 400 | 48px | 1.05 | -0.03em | Opening promise, wrapping into two lines in a 580px measure. |
| heading | ABC Oracle | 400 | 30px | 1.1 | -0.02em | Section leads, assertion-and-echo pairs and the closing call. |
| heading-sm | ABC Oracle | 400 | 24px | 1.1 | -0.01em | Photographic tile labels, proof titles, result numerals and demonstration subheadings. |
| card-heading | ABC Oracle | 400 | 20px | 1.2 | -0.01em | Step captions, capability card titles and technical panel headings. |
| body | ABC Oracle | 400 | 18px | 1.2 | normal | Opening support, section paragraphs, navigation lists and quotations. |
| detail | ABC Oracle | 400 | 14px | 1.26 | normal | Compact explanations, question cards, navigation in the opening and secondary footer text. |
| action | ABC Oracle | 400 | 14px | 1 | 0.1em, uppercase | Primary buttons and bare secondary actions. |
| proof-caption | ABC Oracle | 400 | 13px | 1.25 | normal | Compact benchmark statement in the opening's bottom proof strip. |
| eyebrow | ABC Oracle | 400 | 12px | 1.3 | 0.1em, uppercase | Context labels, tags, chapter markers and newsletter labels. |

**Notes:**

- Keep heading weights at 400: scale, line breaks and color supply the emphasis. Negative tracking tightens from -0.01em on small headings to -0.03em on the opening promise.
- Do not make the muted continuation a separate smaller subtitle; it uses exactly the same heading recipe as the white assertion.
- Labels and actions share 0.1em tracking but have different sizes and line heights. Body copy remains untracked.

## Layout

**Density:** Airy framing with compact information islands: large black intervals separate closely packed controls, captions and proof.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small control gaps, newsletter input-to-button gap and technical row spacing. |
| 12px | Caption stack gaps, label-to-field spacing and compact component internals. |
| 16px | Media-stack gaps and space between step caption and arrow controls. |
| 20px | Proof-card and testimonial grid gutters; logo-cell padding. |
| 24px | Standard card padding and opening headline-to-support gap. |
| 32px | Opening action-to-action gap and vertical inset of comparison panels. |
| 40px | Wide page side gutter, support-to-action spacing and interior proof-card inset. |
| 60px | Footer top and bottom padding and shorter section endings. |
| 100px | Default major section bottom padding. |
| 110px | Heading-to-media separation in the photographic capability chapter. |
| 140px | Default major section top padding and separation before the closing call. |

### Containers and grids

- **editorial-container**: max width 1130px · side padding 40px. Centered editorial content; at 1440px it spans x155–1285. Treat padding as the minimum inset, not an extra addition to the content width.
- **wide-stage**: max width 1360px · side padding 40px. Inset immersive stages and closing photography; 40px outer gutters at desktop.
- **opening-copy**: max width 580px. Left headline measure; support narrows to 560px while the right side remains an independent art field.
- **proof-grid**: max width 1130px · 2 columns · gap 20px. A flexible 785px main proof card and a 325px companion card at desktop, both 662px tall.
- **capability-split**: max width 1130px · 2 columns · gap 40px. A roughly 630px media stack paired with a narrower numbered question index.
- **testimonial-grid** (only for company and customer proof pages): max width 1130px · 3 columns · gap 20px. Three equal 363px-wide quotation cards.
- **technical-reading** (only for technical explainers): max width 750px. Narrow explanatory prose interleaved with wider paired diagrams and a slim chapter rail.

## Corner radius

| Element | Radius |
| --- | --- |
| primary-actions | 100px |
| conversational-action | 999px |
| stages-and-cards | 32px |
| inset-comparison | 24px |
| step-caption | 20px |
| floating-navigation | 16px |
| newsletter-field | 12px |
| circular-controls | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Black remains visible between the inset stages; panels are not stitched into a continuous gray page.

**Transfer:** Keep the interstitial canvas uninterrupted.

#### Electric opening · level 0

**Use:** The main marketing opening.

**CSS:** `background: #1019ec; color: #ffffff`

**Observed:** A luminous blue field has a subtle uneven tonal grain, behind photographic spheres.

**Transfer:** Maintain the bright-blue-to-black contrast over the whole page rather than tinting each section.

#### Recessed stage · level 1

**Use:** The centered contrast argument and technical cards.

**CSS:** `background: #0d0d0d; border-radius: 32px; overflow: hidden`

**Observed:** A near-black interior remains distinct from the true-black outer gutter.

**Transfer:** Use one large frame to hold a claim and its comparison.

#### Raised proof · level 1

**Use:** Proof and media panels.

**CSS:** `background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 32px; overflow: hidden`

**Observed:** A faint outline rather than a drop shadow separates the panel from the canvas.

**Transfer:** Prefer this low-contrast material to elevated dashboard chrome.

#### Glass caption · level 2

**Use:** Readable captions over dense particle art.

**CSS:** `background: rgba(255, 255, 255, 0.06); backdrop-filter: blur(20px); border-radius: 20px`

**Observed:** The drawing remains faintly present beneath the caption.

**Transfer:** Reserve blur for layers that actually overlap imagery.

#### Light demonstration chapter · level 0

**Only for:** product walkthroughs

**Use:** Interface demonstrations before and after a dark technical explanation.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Full-width light fields meet dark chapters through soft grayscale transition bands, 240px high; the initial transition spans 400px.

**Transfer:** Use a deliberate light chapter for direct product use, with smooth luminance transitions rather than a checkerboard of alternating sections.

#### Amber explanation · level 1

**Only for:** technical explainers

**Use:** Definitions, caveats and deeper explanation.

**CSS:** `background: rgba(244, 215, 120, 0.1); border-radius: 16px; padding: 20px 24px 22px`

**Observed:** A dim amber inset interrupts white prose without becoming a promotional banner.

**Transfer:** Use for conceptual help and limits, not for conversion.

## Components

### Primary button

**Use:** The default conversion action.

**CSS:** `display: flex; align-items: center; background: #ffffff; color: #000000; border-radius: 100px; height: 44px; padding: 16px 32px; box-sizing: border-box`

**Text style:** `action` — ABC Oracle 400 · 14px/1 · tracking 0.1em · uppercase

**Observed:** The white fill is a separate backing layer. A secondary bare uppercase action with a right arrow sits beside it, rather than a second filled button.

**States:** Declared: focus-visible outline #388cff solid 2px; the opening variant also declares white outline-color and 3px outline-offset.

**Transfer:** Keep the capsule width content-driven.

### Conversational button

**Use:** A warmer bridge from organizational proof to a sales conversation.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #ffffff; color: #000000; border-radius: 999px; padding: 16px 24px`

**Text style:** `body` — ABC Oracle 400 · 18px/1.2

**Observed:** Sentence case, a small right arrow, and centered placement distinguish this action from the uppercase conversion buttons.

**States:** Declared: hover transform scale(1.025), opacity 1; focus-visible outline #388cff solid 2px with 0px offset; active transform scale(0.975).

### Floating navigation

**Use:** Compact persistent navigation after the expansive opening navigation.

**CSS:** `width: 284px; height: 62px; border-radius: 16px; backdrop-filter: blur(26px); overflow: hidden`

**Observed:** A dark translucent surface floats at the upper center, with a small wordmark at left and a two-line menu control at right. The first screen instead has a wide horizontal wordmark, page links, sign-in and a small rounded rectangular contact action.

**Transfer:** Use the compact bar over long immersive chapters; do not display the expanded menu contents by default.

### Photographic tile

**Use:** Capability category artwork beside a numbered question index.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #1a1a1a; border-radius: 32px; overflow: hidden`

**Text style:** `heading-sm` — ABC Oracle 400 · 24px/1.1 · tracking -0.01em

**Observed:** A 608×320px landscape image fills the frame; a centered white category label sits over a radial black veil. The corresponding active index item expands to compact question cards.

**States:** Declared: focus-visible outline #388cff solid 2px with 0px outline-offset.

**Transfer:** Choose human activity appropriate to the new category rather than illustrative icons.

### Step caption

**Use:** Interpretation of the active stage in an immersive diagram.

**CSS:** `display: flex; flex-direction: column; gap: 12px; background: rgba(255, 255, 255, 0.06); backdrop-filter: blur(20px); border-radius: 20px; padding: 24px; max-width: 555px`

**Text style:** `card-heading` — ABC Oracle 400 · 20px/1.2 · tracking -0.01em

**Observed:** Small outline icon and step fraction sit above a title and a muted detail line. Circular previous/next controls flank the caption; three small progress dots sit below it.

**Transfer:** Explain one change in the system per step, not a bundle of features.

### Proof card

**Use:** A featured result with a companion story.

**CSS:** `display: flex; flex-direction: column; background: rgba(255, 255, 255, 0.1); border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 32px; overflow: hidden`

**Text style:** `heading-sm` — ABC Oracle 400 · 24px/1.1 · tracking -0.01em

**Observed:** The broad card gives its upper 336px to particle-wave art; the lower area splits narrative and striped comparison meters, inset 40px. The narrow companion has art, label, title, a short description and a ruled date/arrow row.

**Transfer:** Use measured comparisons with the same unit and relevant context; retain the art-to-data relationship.

### Striped meter

**Use:** Measured comparison within a featured proof card.

**CSS:** `height: 24px; background-image: repeating-linear-gradient(90deg, #0ae77a 0px, #0ae77a 1px, rgba(0, 0, 0, 0) 1px, rgba(0, 0, 0, 0) 7px)`

**Text style:** `heading-sm` — ABC Oracle 400 · 24px/1.1 · tracking -0.01em

**Observed:** Each 320px track places a detail label above left and a 24px percentage above right. Fine vertical stripes encode width; white and half-white comparison bars precede one green outcome bar.

**Transfer:** Set fill width from the value; preserve the 1px stripe / 7px repeat instead of replacing it with a smooth bar.

### Logo cell

**Use:** A ruled matrix of organizational proof.

**CSS:** `display: flex; justify-content: center; align-items: center; background: #000000; border-top: 1px solid rgba(255, 255, 255, 0.1); border-left: 1px solid rgba(255, 255, 255, 0.1); padding: 20px`

**Observed:** The marketing matrix uses 226×120px cells, mostly monochrome marks, and a shaped staggered outline. Linked cells carry a small white folded-corner triangle. Company variants use a regular three-column investor matrix or five-column experience matrix.

**Transfer:** Use authentic proof marks, normalize their optical size, and keep the grid linear rather than wrapping each mark in a rounded card.

### Newsletter field

**Use:** Compact subscription form in the footer.

**CSS:** `width: 195px; height: 40px; padding: 0px 14px; border: 1px solid rgba(255, 255, 255, 0.1); border-radius: 12px; background: #000000; color: #ffffff; box-sizing: border-box`

**Text style:** `detail` — ABC Oracle 400 · 14px/1.26

**Observed:** A tracked uppercase label is above the field; the Subscribe button sits 8px to its right. The form stays compact within a much wider brand column.

### Subscribe button

**Use:** Newsletter submission.

**CSS:** `height: 40px; padding: 0px 18px; background: #ffffff; color: #000000; border-radius: 100px`

**Text style:** `action` — ABC Oracle 400 · 14px/1 · tracking 0.1em · uppercase

**Observed:** A small white capsule aligned with the newsletter field; it does not stretch to column width.

**States:** Declared: hover opacity 0.8; focus-visible outline #388cff solid 2px with 0px offset.

### Technical callout

**Only for:** technical explainers

**Use:** An inline definition with a deeper disclosure.

**CSS:** `background: rgba(244, 215, 120, 0.1); border-radius: 16px; padding: 20px 24px 22px; margin-top: 32px`

**Text style:** `detail` — ABC Oracle 400 · 14px/1.26

**Observed:** Amber outline information icon and a short heading precede the explanatory paragraph. A small amber-tinted uppercase pill with a plus sign follows.

**Transfer:** Put the plain-language definition first and the deeper detail behind the disclosure.

### Press row

**Only for:** company and editorial lists

**Use:** External coverage or dated editorial proof.

**CSS:** `display: grid; grid-template-columns: 555px 1fr auto; align-items: center; padding: 40px 20px; border-bottom: 1px solid rgba(255, 255, 255, 0.2)`

**Text style:** `detail` — ABC Oracle 400 · 14px/1.26

**Observed:** Publication mark at left, muted date or program title in the middle, northeast arrow at far right. The list has a matching top rule and no card fill.

**States:** Declared: hover background rgba(255, 255, 255, 0.1); focus-visible outline #388cff solid 2px with 0px offset.

## Imagery and graphics

### Photographic worlds

**Use:** Signature opening art beside the promise.

**Observed:** Five floating spheres show a city, green energy landscape, night infrastructure, communications equipment and a flag scene. One city sphere dominates at roughly 294px diameter; four satellites are roughly 90–106px. Photographs are mapped into rounded volumes with a fine reflective rim on electric blue, not placed in ordinary image cards.

**Transfer:** Use photographs of the environments or outcomes the new product affects. Preserve one dominant world and smaller satellites with varied scale; circular photo windows with restrained edge shading are the minimum version.

**Build:** Create five circular clipping masks on the right half of the stage, one about 294px and the others 90–106px at desktop. Fill with object-fit:cover photos; layer an inset white rim at 0.2 alpha, a soft black inset shadow toward the bottom, and a curved white highlight at 0.1 alpha. Keep irregular orbital spacing and clear space around the left text. Add fine blue-field grain using an SVG turbulence layer with soft-light blending at 0.035 opacity.

### Particle sculptures

**Use:** Signature explanatory stages, proof artwork and capability illustrations.

**Observed:** Monochrome dots form a tilted spatial grid, a globe-like cloud, falling paths, waves, an apple-like volume, orbital rings and grouped clusters. Dim gray fields carry a few bright white selected points. The largest art fills a 1360×820px charcoal frame; smaller point objects float on black above short captions.

**Transfer:** Translate the product's process into changes in arrangement, grouping or trajectory. A coherent SVG point cloud with a selected white subset is sufficient; preserve spatial depth rather than substituting generic glowing blobs.

**Build:** Use SVG circles or canvas points on #1a1a1a: distribute dots on a regular plane, project it with a perspective tilt and sinusoidal depth displacement. Draw mostly 2–4px circles at white alpha 0.15–0.35; make a localized subset white at 0.9–1. For a sphere, sample latitude rings and vary radius and alpha with depth. For proof waves, use short diagonal white dashes in curved bands, fade them toward the lower edge with a black gradient. Clip large scenes to a 32px rounded frame.

### Contextual capability photography

**Use:** Category tiles accompanying question-led capabilities.

**Observed:** Documentary scenes show a craftsperson, crowded retail activity, pedestrians crossing, wind farms and an institutional interior. Landscapes are darkened and sometimes motion-softened; centered white labels remain the focal point.

**Transfer:** Select scenes of actual work or use, not posed portraits holding devices. Maintain natural texture and a dark veil rather than blue duotone.

**Build:** Fill a landscape frame with cover photography; overlay radial-gradient(120% 90%, rgba(0,0,0,0.6) 0px, rgba(0,0,0,0.32) 45%, rgba(0,0,0,0.14) 100%). Place the category label above the veil.

### Closing reality scene

**Use:** Signature closing call before the utility footer.

**Observed:** A broad overhead photograph of people walking through a planted, sunlit architectural space is darkened to muted green and gray. Strong diagonal and grid shadows make the scene graphic. It fills a 1360×800px frame with 32px corners; the small heading pair and action are left-aligned near its vertical middle.

**Transfer:** Choose an overhead human-scale scene related to the new product's world; preserve ambient daylight, visible people and structured shadows. A still photograph is sufficient.

**Build:** Use a cover image in a 32px-radius overflow-hidden frame. Add a uniform black layer around 0.4 alpha, adjusted so white text reads without washing out the foliage and shadows; place the content layer above it, aligned to the editorial inset.

### Landscape-backed interface

**Only for:** product walkthroughs

**Use:** Light chapters demonstrating actual work.

**Observed:** A 940×529px landscape stage bleeds toward one edge; a white application window is inset over a narrow rim of mountain, ridge or sky photography with cool-blue treatment. Nearby text occupies a much narrower column; sides alternate between successive demonstrations.

**Transfer:** Show the new product's real interface with enough legibility to explain a task. Keep the photographic surround thin and the white application plane dominant.

### Working-life photography

**Only for:** company pages

**Use:** Opening collage and founder story.

**Observed:** Warm daylight office scenes form one 836×573px image beside two 279px square images, with rounded corners. A later 555×740px founder portrait is set against a city skyline and paired with a dark floating biography panel. The office-location graphic instead uses a dim particle globe with a blurred text band.

**Transfer:** Use candid working scenes, tactile objects and environmental portraits. Reuse the particle visual language for geography; keep the human photographs natural rather than uniformly tinted.

### Icons

**Observed:** Marketing arrows and process icons are small white or half-white outline SVGs, typically 12–18px with 1.25–1.5px rounded strokes. Circular navigation controls are 44px. Social marks are compact solid glyphs; labels, not large icons, carry the hierarchy.

**Transfer:** Use a consistent thin-line family for arrows, people and process symbols. Reserve solid marks for social identities and tiny status points.

## Section recipes

How recurring sections are built.

### First screen: World-stage opening

**Observed:** A full-width 900px electric-blue field carries a wide top navigation, a left-aligned promise and an independent photographic sphere cluster at right. The 48px display heading wraps into two lines across a 580px measure; an 18px support paragraph sits 24px below, then actions 40px below that. The text block is vertically centered rather than pushed to the top. The large city world sits around the right-middle, with four smaller worlds distributed above and below; the art does not overlap the text. Layers run blue field, subtle grain, spheres, text and actions, then navigation and the bottom proof strip. The first 900px include all of the headline, support, white primary action, bare arrow action, the main art and a 49px-high logo/benchmark strip. The next dark argument panel is below the fold.

**Transfer:** Lead with a decision or outcome, paired with a dominant photographic world and smaller contextual worlds. If custom 3D is unavailable, use the circular photo-window construction. Product walkthroughs instead open on white with a central portrait/data collage, small left title and right explanation; company pages open with a centered 30px heading and warm photographic collage.

**Avoid:** Do not replace the opening with a giant centered headline, dashboard screenshot or grid of equal bubbles. Do not place a dark overlay across the whole blue field or hide the bottom proof strip.

**Text style:** `display` — ABC Oracle 400 · 48px/1.05 · tracking -0.03em

### Assertion and echo

**Observed:** A white 30px first line immediately precedes a half-white continuation at the same size and line height. Content aligns to the 1130px editorial container; split headers pair this compact title at left with an 18px explanation at right. Major chapters begin with 140px top padding.

**Transfer:** Make the second line extend or qualify the first. Use signal blue only for a sharp contrast statement, not for every echo.

**Text style:** `heading` — ABC Oracle 400 · 30px/1.1 · tracking -0.02em

### Contrast argument

**Observed:** The Recessed stage holds a centered two-line contrast heading, a compact explanation, a segmented category control and an inset 920×300px comparison panel. The panel uses 24px corners, 32px vertical and 40px horizontal padding. Two columns distinguish stated expectation from modeled behavior; a ruled outcome row closes the panel while faint particles sit behind it.

**Transfer:** Contrast the familiar approach with the new mechanism using a concrete scenario and one observable result.

### Immersive mechanism

**Observed:** A 1360×820px rounded particle stage occupies most of the desktop viewport within 40px gutters. A Step caption near its lower center interprets the active diagram, flanked by circular controls and followed by tiny dots. Successive states change a plane of points into selected profiles, a spatial cloud and trajectories.

**Transfer:** Explain a mechanism through a small number of meaningful visual state changes. Keep a readable static state with the same art and caption if interactive rendering is unavailable.

### Question-led capabilities

**Observed:** A heading pair precedes a two-column chapter by 110px. The left stack uses Photographic tiles; a numbered text index on the right highlights one category and opens three compact rounded question cards beneath it. A small white primary action closes the index.

**Transfer:** Organize by what a customer needs to decide, then write questions specific enough to suggest actual use.

### Measured proof pair

**Observed:** The Proof grid pairs a broad Proof card with a narrow companion. Monochrome particle art occupies the upper portion; narrative and Striped meters share the lower half. Labels are 14px, figures 24px and comparison tracks 24px high.

**Transfer:** Use honest comparable measures and one clearly identified outcome. The companion can carry a related report, case or dated result.

### Capability orbit carousel

**Observed:** A heading pair and circular previous/next controls sit above a horizontal row of three capability summaries. Each summary has a monochrome point sculpture in an approximately 448px square art field, then a 20px title, 18px muted description and small circular arrow. The row can extend beyond the viewport.

**Transfer:** Recast the new product's domains as distinct point arrangements; keep descriptive text below, not on top of, these smaller sculptures.

### Photographic closing and utility footer

**Observed:** A Closing reality scene spans the wide stage. A white-and-muted heading pair at 30px and a Primary button form a small left-aligned block with 40px gap. Below, 60px padding introduces a 420px-tall black utility area: brand and compact newsletter at left, 18px navigation and 14px muted policy lists to the right, tiny login/contact capsules at the far edge. Social icons and billing/copyright occupy the lower row. This ending is consistent across page types.

**Transfer:** Close the abstract product narrative with people in a real setting and one short invitation. Keep the utility footer spatially separate from the image and compact in content density.

### Technical explanation chapters

**Only for:** technical explainers

**Observed:** A narrow chapter rail accompanies 750px prose blocks. Short 30px headings and 18px explanations alternate with Technical callouts, segmented controls and wider paired charts on #0d0d0d panels with 24px corners. White interface demonstrations bracket this dark instructional middle.

**Transfer:** Explain assumptions, relationships and validation without turning the whole page into a dashboard. Keep interaction controls close to the visual they change.

### Human and institutional proof

**Only for:** company pages

**Observed:** After the collage opening, two-column heading/prose introductions lead into numbered ruled accordions, a portrait with interactive biography, a particle globe, three quotation cards, Press rows and ruled logo matrices. The quotation cards are 440px tall with the logo at top and quote/attribution near the bottom.

**Transfer:** Alternate human-scale photography and institutional proof; adapt the accordion to principles, commitments or common questions rather than forcing a fixed topic list.

## Page flow

**Storyline:** Promise in a world → contrast with the old approach → mechanism made visible → practical questions → measured and institutional proof → human closing invitation.

### Broad marketing landing page that makes an unfamiliar capability credible

1. **Promise** — Blue world-stage opening with action pair and bottom proof strip.
2. **Reframe** — Centered contrast argument with a concrete two-column example.
3. **Social proof** — Ruled organizational mark grid and conversational action.
4. **Mechanism** — Large particle stage explained in successive captioned states.
5. **Practical relevance** — Photographic categories paired with customer questions.
6. **Quantified proof** — Broad measured case card and narrower related story.
7. **Breadth** — Point-sculpture capability carousel with short summaries.
8. **Closing call** — Overhead photography and split-line invitation, followed by a full utility footer.

**Transfer:** Borrow the alternation of immersive explanation and specific proof; change the amount and ordering of chapters to fit the product.

### Deep product and methodology walkthrough

1. **Orientation** — White opening with central portrait/profile collage and small flanking explanations.
2. **Product demonstration** — Light interface chapters alternate text and landscape-backed application windows.
3. **Mechanism and limits** — A grayscale bridge enters black prose, amber definitions, source explorers and interactive relationship diagrams.
4. **Validation** — Paired technical cards and a particle-backed case-study call.
5. **Usable output** — A light chapter demonstrates returned analysis and export choices.
6. **Closing call** — The same photographic invitation and utility footer as the broad landing page.

**Transfer:** Separate direct interface use from deeper technical explanation through light and dark chapters, while sharing type and controls.

### Company credibility through people, working principles and external trust

1. **Human introduction** — Centered compact heading and daylight office collage.
2. **Purpose** — A two-column belief statement and supporting explanation.
3. **Commitments** — Five numbered accordion rows with quiet rules.
4. **People and place** — Environmental founder portrait with biography overlay, then a particle location globe.
5. **External proof** — Quotation cards, publication rows, investor grid and experience-logo matrix.
6. **Closing call** — Shared photographic invitation and utility footer.

**Transfer:** Use authentic human evidence and relevant external signals without importing the product walkthrough's white chapters.

## Writing

Confident and intellectually direct, with an emphasis on mechanisms, concrete decisions and observable consequences. It pairs short declarative claims with explanations that acknowledge conditions and limits.

**Do not copy:** Do not reuse Aaru's name or marks, partner and investor logos, customer quotations, study titles, proprietary artwork, accuracy benchmarks, dates or numerical claims. Replace them with the new product's substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The reader is addressed as you in actions and practical outcomes. Explanations use the product's name as the subject; company writing shifts to we and our.
- **Rhythm:** Headlines tend toward short clauses, often paired across two lines. Support uses compact but information-rich sentences; technical chapters permit longer explanatory paragraphs. Actions are brief imperatives without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | State the new capability and the consequential moment it comes before. | 10–14 words | “Simulate what people will do before you commit.” |
| Contrast heading | Two parallel clauses replace a familiar behavior with a stronger mechanism. | 5–7 words per clause | “Ask people, and they answer.”<br>“Simulate them, and they act.” |
| Section lead | A plain claim names the mechanism rather than celebrating the brand. | 3–7 words | “Traits move together.”<br>“Training works at two resolutions.” |
| Support | Explain what the system does, what grounds it and how the reader uses it. | One to three sentences | “[Brand] builds simulated populations grounded in real-world behavior and outcomes.” |
| Action | Direct verb plus the object of the next useful step. | 3–7 words | “Test your decision”<br>“Bring us your hardest decision” |
| Closing invitation | Two short lines connect foresight to agency. | 3 words per line | “See the future”<br>“Change the present” |

**Words and phrasing to use:** test; before you commit; conditions; outcomes; observed; grounded; decision; what happens next

**Avoid:** magic; revolutionary; effortless perfection; unlimited certainty; game-changing; AI-powered everything

**Rules:**

- Lead with the decision improved, not a list of model capabilities.
- Explain an abstraction through a recognizable consequence or contradiction.
- Place qualifications near the claim they constrain, particularly in technical prose.
- Write category questions that a customer could actually bring to a working session.
- Use paired clauses and parallel verbs without turning every heading into a slogan.

## Do's and Don'ts

### Do

- Keep the main promise at 48px, weight 400 and -0.03em tracking, within a 580px measure.
- Use 30px white/muted heading pairs to organize black chapters.
- Preserve 40px outer gutters around 32px-radius immersive frames at desktop.
- Keep real proof close to the opening through the narrow bottom strip.
- Use 140px top and 100px bottom section padding as the dominant chapter rhythm.
- Give the particle art a coherent form, selected bright points and a dim gray supporting field.
- Build comparison meters from 1px vertical stripes on a 7px repeat.
- End with the broad human-scale photograph and compact black utility footer.

### Don't

- Do not add bold 700-weight headings to manufacture emphasis; regular weight is structural here.
- Do not repeat electric-blue panels throughout the dark body; the opening owns that broad color gesture.
- Do not use generic blue-purple gradient text in place of white and half-white heading lines.
- Do not replace 32px framed art with a collection of small shadowed dashboard cards.
- Do not turn the 24px proof numerals into oversized typographic billboards.
- Do not make the ruled organizational matrices rounded or widely gapped; their edges share a thin grid.
- Do not apply glass blur to every card; reserve it for overlapping captions and floating navigation.
- Do not use emoji, chunky filled feature icons or bright multi-hue icon tiles alongside the fine particle art.

## Motion and responsive

### Motion

**Observed:**

- The proof-logo strip declares a 56s linear infinite leftward animation.
- The conversational action declares transform 0.4s cubic-bezier(0.19, 1, 0.22, 1).
- The step caption declares opacity and transform transitions of 0.45s cubic-bezier(0.4, 0, 0.2, 1), each delayed 0.15s.
- Subscribe declares opacity 0.3s; the newsletter field declares border-color 0.15s ease-out.
- A sticky full-viewport stage presents changing particle arrangements with caption and progress controls.

**Transfer:**

- Use the slow linear logo movement as a proof texture, not as the reading surface for critical claims.
- Tie changes in the particle arrangement to a specific explanatory step and retain a legible settled frame.
- Use the stated caption transition when swapping stage explanations; keep the numerical progress visible.

**Unknown:**

- Exact WebGL timelines, camera movement and scroll-to-state mappings are not specified.

### Responsive

**Observed:**

- CSS includes breakpoints around 480px, 768px, 1024px, 1440px and 1600px; desktop geometry is the established composition.

**Transfer:**

- On narrow screens, preserve the promise before its world art, maintain one dominant sphere and reduce satellites before reducing text legibility.
- Stack photographic tiles and their questions rather than compressing the two-column index.
- Let proof cards and logo grids reflow; keep stripe spacing and caption text intact.
- Retain the compact floating navigation and keep it clear of the opening's headline.

**Unknown:**

- Exact narrow-screen sizes, gutters, stacking behavior and touch interactions are unspecified; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
