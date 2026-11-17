# Graphy — luminous objects, lucid stories

## Overview

A buoyant software style with cool, almost porcelain backgrounds and small glowing blue objects floating around direct, confident copy. Rounded geometric sans typography and softly framed interface demonstrations keep complex products approachable rather than technical. The mostly light, spacious presentation ends in a deep plum night scene, where the same glassy objects become luminous.

### Essentials

- A centered promise surrounded by floating product symbols: a 62px bold headline with 1.05 line height, 22px supporting text, and small blue glass objects arranged at the sides rather than behind the words.
- Porcelain daylight is the default: #f2f4f8 canvas, white panels, #20295a headings and #4a527a supporting text occupy almost the entire body; saturated #2e62ff is concentrated in actions and single emphasized words.
- Buttons are soft rectangles, not capsules: primary and demo actions are 54px high with 20px corners and 16px 32px padding; the compact header action uses 12px corners and 42px height.
- Process explanations become a narrow, numbered reading spine: 600px white cards with 30px padding, 8px corners, 32px headings and a large 56px numeral on a translucent tab just outside the left edge.
- Product proof is staged as a luminous object, not a flat screenshot dump: overlap example outputs above a low glass checklist rail, with a diffuse blue-violet halo; use representative outputs or simple vector miniatures when no interface is available.
- The closing call changes the lighting, not the identity: a full-width plum radial field from #28163d to #180d24 carries white 56px type, one blue action, glowing blue objects and tiny stars, then a dotted category rail and restrained footer links.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navy ink | `#20295a` | `--color-ink` | text | Headlines and strong labels. |
| Plum light | `#28163d` | `--color-plum-center` | background | Center of the dark closing scene only. |
| Plum night | `#180d24` | `--color-plum-edge` | background | Outer edge of the dark closing scene only. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#2e62ff` | `--color-blue` | action, accent, text | Primary actions, short emphasized verbs and inline emphasis. A 90% blue layer also appears in plan controls and icons. |
| Category violet | `#5847ff` | `--color-violet` | accent | Small dots beneath category links in the closing rail. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate blue | `#4a527a` | `--color-body` | text | Supporting prose and plan text; also the visible result of navy ink at 80% on the canvas. |
| Muted slate | `#616581` | `--color-muted` | text | Feature explanations, testimonials and secondary descriptive text. |
| Navigation black | `#000000` | `--color-black` | text | Header links, compact signup text and process numerals. |
| Quote heading charcoal | `#333333` | `--color-charcoal` | text | Testimonial names and FAQ questions. |
| Metadata gray | `#999999` | `--color-metadata` | text | Testimonial affiliations. |
| Footer silver | `#c2c2c2` | `--color-footer-muted` | text | Social, backing and legal information on the plum closing field. |
| Cool media edge | `#d7e8f0` | `--color-media-edge` | border | Media-panel outlines use this hue at 50% opacity. |
| Cool media wash | `#eef2f7` | `--color-media-wash` | surface | Visible #d7e8f0 at 15% over the canvas; a faint cool backing for embedded examples. |
| Porcelain canvas | `#f2f4f8` | `--color-canvas` | background, surface, border | Default page canvas, testimonial interiors and faint card edges. |
| White glass | `#f9fafc` | `--color-glass` | surface | Visible white at 50% over the porcelain canvas; navigation and broad translucent panels. |
| White | `#ffffff` | `--color-white` | surface, text | Content cards and text on blue actions or the dark closing field. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| recruiting process sections | Stage label blue | `#2d62ff` | `--color-stage-blue` | text | Small tracked stage markers. |
| pricing and objection-handling sections | FAQ hairline | `#f2f2f2` | `--color-faq-rule` | border | Black at 5% over white separates FAQ rows. |

## Typography

- **Aeonik** — All principal marketing headings, paragraphs, actions and labels. Rounded geometric grotesk with open, circular forms; Regular for prose, Medium for most headings, Bold for opening headlines. If unavailable, use **DM Sans**. Use 400, 500 and 700; preserve the open proportions and mostly normal tracking. Font stack: "Aeonik", "DM Sans", Arial, sans-serif.
- **Inter** (only for pricing FAQ questions) — Question labels in the accordion. Compact neutral sans with a firmer semibold tone than the surrounding prose. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Aeonik | 700 | 62px | 1.05 | normal | Centered opening headline. |
| heading-lg | Aeonik | 500 | 56px | 1.15 | normal | Major section headings, large numbered tabs and the white closing headline. |
| heading | Aeonik | 500 | 40px | 1.2 | normal | Social-proof heading and editorial section titles. |
| feature-heading | Aeonik | 500 | 32px | 1.2 | normal | Headlines inside numbered feature cards; one short word changes to blue. |
| quote-name | Aeonik | 500 | 24px | 1.4 | -0.0333em | Names in testimonial identity strips. |
| hero-support | Aeonik | 400 | 22px | 1.35 | normal | Two-line opening support and centered closing support. |
| body | Aeonik | 400 | 18px | 1.35 | normal | General marketing support and example captions. |
| action | Aeonik | 400 | 18px | 1.2 | normal | Primary and demo button labels. |
| feature-body | Aeonik | 400 | 16px | 1.35 | normal | Short, dense explanations inside feature cards. |
| navigation | Aeonik | 400 | 16px | 1.2 | normal | Navigation links and compact supporting labels. |
| compact-action | Aeonik | 500 | 16px | 18px | normal | Header signup and compact plan actions. |
| quote-body | Aeonik | 400 | 16px | 1.6 | normal | Testimonial paragraphs. |
| quote-meta | Aeonik | 400 | 16px | 1.1 | -0.044em | Affiliations under testimonial names. |
| footer-link | Aeonik | 400 | 14px | 1.6 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Social and backing links in the dark footer. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and recruiting pages | editorial-display | Aeonik | 700 | 56px | 1.2 | normal | Bold two-line lead on an editorial letter. |
| recruiting process sections | stage-title | Aeonik | 500 | 24px | 1.3 | normal | Process-card titles. |
| pricing pages | plan-price | Aeonik | 500 | 24px | 1.2 | normal | Price or free-plan proposition, centered. |
| company and recruiting pages | editorial-body | Aeonik | 400 | 20px | 1.2 | normal | Long-form company prose and supporting introduction. |
| pricing pages | plan-features | Aeonik | 400 | 20px | 1.6 | normal | Plan feature lists. |
| pricing FAQ sections | faq-question | Inter | 600 | 16px | 1.5 | normal | Accordion question labels. |
| recruiting process sections | stage-label | Aeonik | 400 | 14px | 1.3 | 0.1em | Uppercase stage identifiers. |

**Notes:**

- Normal tracking is the main rule even at display sizes; the identity strips and small footer links are the localized exceptions.
- The opening uses Bold, while subsequent large headings use Medium. Do not make every heading equally heavy.
- Body text moves between 22px centered promises, 18px general support and 16px card explanations; preserve these roles rather than applying one paragraph size everywhere.

## Layout

**Density:** Airy outer composition with compact inner explanations; generous stage space surrounds the much narrower demonstration column.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight explanation gaps and feature-media separation. |
| 10px | Paired action gap, small groups and ticker-card gaps. |
| 16px | Headline-to-support gap and testimonial padding. |
| 20px | Example-panel and culture-card padding. |
| 24px | Header link spacing and repeated role-row gaps. |
| 30px | Feature-card padding and internal chapter separation. |
| 32px | Plan-card padding and numbered-section vertical inset. |
| 40px | Editorial columns, stage-card padding and footer side inset. |
| 48px | Opening support-to-action separation. |
| 60px | Large heading-to-content and repeated example spacing. |
| 80px | Common editorial section vertical padding. |
| 100px | FAQ outer panel vertical padding. |
| 120px | Deep section endings and desktop side margins at the main container. |

### Containers and grids

- **main-container**: max width 1200px · side padding 40px. Centered desktop marketing content; at 1440px the main container leaves 120px side margins.
- **opening-copy**: max width 900px. Centered headline area; the actual text block remains narrower than the surrounding object field.
- **demonstration-spine**: max width 630px. A 600px feature card centered inside the broad main container; the numbered tab extends left beyond it.
- **editorial-pair** (only for company and recruiting pages): max width 1200px · 2 columns · gap 40px. Headline and supporting story or process cards share two broad columns.
- **plan-grid** (only for pricing pages): 3 columns · gap 30px · side padding 40px. Broad equal-height plan cards across nearly the full viewport.
- **faq-container** (only for pricing FAQ sections): max width 1000px · side padding 20px. White accordion nested within a wider translucent panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | feature-cards | 8px |
|  | primary-actions | 20px |
|  | compact-actions | 12px |
|  | navigation | 20px |
|  | media-panels | 4px |
|  | announcement | 51px |
| pricing pages | plan-cards | 16px |
| recruiting pages | role-rows | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | feature-card | `rgba(0, 0, 0, 0.02) 0px 0.5px 1.6px -0.3px, rgba(0, 0, 0, 0.03) 0px 1.8px 6.2px -0.7px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px -1px` | Soft elevation under the numbered demonstration cards. |
| company and recruiting pages | paper-note | `rgba(29, 46, 99, 0.14) 0px 1px 2px 0px` | Light blue-gray contact shadow on slightly rotated culture cards. |

### Surfaces

#### Porcelain canvas · level 0

**Use:** Default light marketing field.

**CSS:** `background: #f2f4f8`

**Observed:** Cool rather than pure-white; broad uninterrupted breathing room around white cards.

**Transfer:** Keep most of the body on this field.

#### White demonstration card · level 1

**Use:** The principal explanatory surface.

**CSS:** `background: #ffffff; border-radius: 8px; box-shadow: rgba(0, 0, 0, 0.02) 0px 0.5px 1.6px -0.3px, rgba(0, 0, 0, 0.03) 0px 1.8px 6.2px -0.7px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px -1px`

**Observed:** A modest sheet-like edge, not a heavy border or floating dialog.

**Transfer:** Use around a coherent chapter rather than around every sentence.

#### Cool media panel · level 1

**Use:** Nested examples of outputs in context.

**CSS:** `background: rgba(215, 232, 240, 0.15); border: 1px solid rgba(215, 232, 240, 0.5); border-radius: 4px`

**Observed:** Almost-white cool fill with a fine edge, set inside the larger white card.

**Transfer:** Separate the example environment from the explanatory card with tint, not a strong frame.

#### Testimonial gradient edge · level 1

**Use:** Fine lavender perimeter on testimonials.

**CSS:** `background: linear-gradient(rgba(255, 255, 255, 0.3) 0%, rgba(76, 48, 237, 0.2) 100%); padding: 1px; border-radius: 8px`

**Observed:** A porcelain interior covers the gradient, leaving a thin lower lavender edge.

**Transfer:** Use the gradient as a wrapper, never as a saturated quote-card fill.

#### Plum night scene · level 0

**Use:** Signature closing call and footer.

**CSS:** `background: radial-gradient(ellipse at center, #28163d 0%, #180d24 100%); color: #ffffff; overflow: hidden`

**Observed:** The same blue glass motifs reappear against a star-like particle field; the product call and navigation share one uninterrupted dark background.

**Transfer:** Reserve the full dark inversion for the final conversion scene.

#### Editorial letter sheet · level 1

**Only for:** company and recruiting pages

**Use:** Long-form founder or team perspective.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 80px; box-shadow: rgba(29, 46, 99, 0.14) 0px 1px 2px 0px, rgba(29, 46, 99, 0.12) 0px 4px 4px 0px, rgba(29, 46, 99, 0.07) 0px 10px 6px 0px, rgba(29, 46, 99, 0.02) 0px 17px 7px 0px, rgba(29, 46, 99, 0.1) 0px -1px 3px 0px`

**Observed:** Near-full-width sheet with a more tactile contact shadow than the product cards.

**Transfer:** Use for a genuine narrative statement, paired with a small video or signature.

#### FAQ outer glass · level 1

**Only for:** pricing FAQ sections

**Use:** Broad objection-handling band.

**CSS:** `background: rgba(255, 255, 255, 0.5); border-radius: 20px; padding: 100px 10px 100px 0px`

**Observed:** The white accordion is inset inside this low-contrast translucent band.

**Transfer:** Keep the two white levels distinguishable through surrounding canvas.

## Components

### Floating navigation

**Use:** Persistent desktop header.

**CSS:** `background: rgba(255, 255, 255, 0.5); backdrop-filter: blur(2px); border-radius: 20px; max-width: 1200px; height: 58px; padding: 8px 9px 8px 20px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `navigation` — Aeonik 400 · 16px/1.2

**Observed:** The header sits in a fixed wrapper with 24px top space. Identity is at left, a compact central link group has 24px gaps, and login plus Compact signup sit at right.

**Transfer:** Use a short navigation set so the translucent bar remains light.

### Primary button

**Use:** Main conversion action in opening, selected chapters and closing.

**CSS:** `background: #2e62ff; color: #ffffff; border-radius: 20px; padding: 16px 32px; height: 54px; display: flex; justify-content: center; align-items: center`

**Text style:** `action` — Aeonik 400 · 18px/1.2

**Observed:** Text-only, centered, with a subtly luminous edge in the rendered treatment; paired with Secondary button in the opening.

**Transfer:** Use one clear verb-led action per conversion group.

### Secondary button

**Use:** Demo action paired with the main opening action.

**CSS:** `background: rgba(255, 255, 255, 0.9); color: #000000; border-radius: 20px; padding: 16px 32px; height: 54px`

**Text style:** `action` — Aeonik 400 · 18px/1.2

**Observed:** Same silhouette as Primary button, separated by a 10px gap; the near-white fill replaces an outline.

### Compact signup

**Use:** Header conversion action.

**CSS:** `background: #ffffff; color: #000000; border-radius: 12px; padding: 12px 20px; height: 42px`

**Text style:** `compact-action` — Aeonik 500 · 16px/18px

**Observed:** White compact action attached visually to the right end of the navigation. The selected pricing-plan action uses the same compact silhouette with a blue fill and white label.

### Navigation link

**Use:** Simple header destinations.

**CSS:** `color: #000000; text-decoration: none`

**Text style:** `navigation` — Aeonik 400 · 16px/1.2

**Observed:** Plain text with no surrounding chip; a small chevron or northeast arrow marks a dropdown or external destination.

**States:** Declared: hover color rgba(0, 0, 0, 0.8) and underline; focus-visible unknown.

### Numbered feature card

**Use:** Sequential explanation with one or more demonstrations.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 30px; width: 600px; max-width: 630px; display: flex; flex-direction: column; gap: 8px; box-shadow: rgba(0, 0, 0, 0.02) 0px 0.5px 1.6px -0.3px, rgba(0, 0, 0, 0.03) 0px 1.8px 6.2px -0.7px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px -1px`

**Text style:** `feature-heading` — Aeonik 500 · 32px/1.2

**Observed:** A translucent white numeral tab protrudes from the upper left. A short headline highlights one word blue, then explanatory prose precedes the media. Chapters can share a single tall card.

**Transfer:** Replace the steps with the new product's real workflow; keep the narrow reading spine and exterior numbering.

### Example panel

**Use:** A product output shown inside another working context.

**CSS:** `background: rgba(215, 232, 240, 0.15); border: 1px solid rgba(215, 232, 240, 0.5); border-radius: 4px; padding: 20px; width: 540px; display: flex; flex-direction: column; gap: 10px; overflow: hidden`

**Text style:** `body` — Aeonik 400 · 18px/1.35

**Observed:** Short heading and caption precede a large framed example; small integration marks sit beside the heading. Examples stack with 60px gaps inside the demonstration card.

**Transfer:** Show the result where people actually use it, not just in an isolated editor.

### Testimonial card

**Use:** Social proof in two horizontally overflowing rows.

**CSS:** `background: linear-gradient(rgba(255, 255, 255, 0.3) 0%, rgba(76, 48, 237, 0.2) 100%); border-radius: 8px; padding: 1px; width: 360px; overflow: hidden`

**Text style:** `quote-body` — Aeonik 400 · 16px/1.6

**Observed:** Porcelain interior, then a white identity strip with circular avatar, name and gray affiliation; prose sits below with 16px padding. Blue phrases punctuate selected quotes. Cards have varying heights; row edges fade away.

**Transfer:** Use authentic quotes with a brief identity strip and keep the mixed heights.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchase tiers.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 32px; width: 424px; min-height: 678px; display: flex; flex-direction: column; align-items: center`

**Text style:** `plan-price` — Aeonik 500 · 24px/1.2

**Observed:** A small blue glass object leads a centered tier name, price, discount and billing switch; feature list is left-aligned and the action anchors the bottom. The recommended tier remains white with a fine blue perimeter and a top-right corner label.

**Transfer:** Favor a border and compact badge over a full blue plan fill.

### FAQ accordion

**Only for:** pricing FAQ sections

**Use:** Resolve practical purchase questions.

**CSS:** `background: #ffffff; border-radius: 20px; max-width: 1000px; padding: 0px 20px`

**Text style:** `faq-question` — Inter 600 · 16px/1.5

**Observed:** Repeated 64px closed rows have 20px vertical padding, a small plus at left and a 1px black-at-5% separator. No heavy row outlines.

**Transfer:** Use direct customer questions; retain the restrained closed-row presentation.

### Culture note

**Only for:** company and recruiting pages

**Use:** Short principles or fit descriptions.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 20px; display: flex; flex-direction: column; gap: 20px; box-shadow: rgba(29, 46, 99, 0.14) 0px 1px 2px 0px; transform: rotate(2deg)`

**Text style:** `body` — Aeonik 400 · 18px/1.35

**Observed:** Small white paper-like notes form a three-column field with subtly alternating tilts; blue outline icons precede short prose.

**Transfer:** Use sparingly for human principles rather than as the default product feature grid.

### Role row

**Only for:** recruiting pages

**Use:** Open-position listing.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 12px 12px 12px 24px; min-height: 78px; display: flex; flex-wrap: wrap; align-items: center; column-gap: 24px; row-gap: 16px`

**Text style:** `body` — Aeonik 400 · 18px/1.35

**Observed:** Position title sits at left, location metadata toward the right and a Primary button at the far edge. Rows stack at 24px intervals.

**Transfer:** Maintain a readable title–metadata–action sequence.

## Imagery and graphics

### Floating blue glass symbols

**Use:** Signature framing device in the opening, closing and small pricing markers.

**Observed:** Small extruded bar groups, rings, pie segments and divided squares hover around the copy. They use translucent periwinkle-to-blue faces, pale frosted sections, fine bright edges and soft violet-blue shadows. The objects flank the main text rather than becoming a central hero illustration.

**Transfer:** Use simple symbols of the new product's outputs or tools. Minimum acceptable version: two or three carefully shaded SVG primitives with frosted highlights and a diffuse glow, repeated consistently in the closing scene.

**Build:** Construct SVG groups from rounded rectangles, ring arcs or segmented disks. Fill blue faces with a diagonal gradient between blue at 90% opacity and white at 75%; add thin white strokes at 50%, a slightly offset darker-blue side face and a broad blue shadow at 15–25% opacity. Rotate individual groups slightly, keep their size subordinate to the headline and place them in left and right clusters. On dark backgrounds strengthen the glow without enlarging the objects.

### Luminous proof stage

**Use:** A high-impact product-proof scene between promise and detailed explanation.

**Observed:** Three output cards overlap in a shallow fan: the central tall white card rises highest, with a dark example to one side and a pale lavender example to the other. Orange, green and violet occur inside the outputs, while the surrounding atmosphere stays cool. A translucent checklist rail crosses the foreground.

**Transfer:** Show three distinctive results in contrasting internal themes. If there is no interface, compose real output artifacts or informative diagrams; keep their typography legible and the surrounding stage pale.

**Build:** Layer three rectangular SVG or HTML output panels within a roughly 1146px-wide stage. Raise the middle panel and overlap side panels behind it. Add a wide blue-violet ellipse at low opacity behind the group with soft blur, then a 960px glass rail in front with an 8px radius, white top highlight and six evenly spaced blue check dots. A faint blurred horizontal light streak sits behind the rail; exact glow stops are not essential.

### Interface demonstrations

**Use:** Detailed workflow chapters and examples in context.

**Observed:** Short demonstration videos occupy a 540px by 400px media area in white cards. Pale blue UI backings, restrained graphs and small floating controls soften technical detail. Context examples show outputs inside slides, social posts, documents and messages; these sit in Cool media panels.

**Transfer:** Use legible, task-specific interface states and brief captions. Recreate the new product's interaction, retaining pale cool backing and selective bright output colors rather than reproducing unrelated controls.

### Dark star field

**Use:** Atmosphere behind the final conversion scene.

**Observed:** Tiny white points and soft blue glows surround the floating glass objects across the upper closing area; footer links remain uncluttered below.

**Transfer:** Re-light the opening symbols in a dark field so the ending feels like the same world after sunset.

**Build:** Place irregular 1px to 3px white dots on an absolutely positioned SVG over Plum night scene, with varied opacity and a few blurred duplicates. Cluster points near the side objects and leave the headline and action clear. Use white glow shadows on selected dots, not a uniform tiled star pattern.

### Human identity media

**Only for:** company pages and testimonial proof

**Use:** Small founder video, signatures and testimonial portraits.

**Observed:** Human photography is supporting material, not a full-bleed lifestyle backdrop. The founder video is a small landscape thumbnail; testimonials use circular headshots beside names.

**Transfer:** Use real people at compact scale to anchor claims without changing the site's product-led visual emphasis.

### Icons

**Observed:** Small interface-adjacent icons are mostly simple single-color arrows, checks and plus signs, around 14px to 24px. Culture cards use larger blue outline symbols around 41px; benefit rows place blue icons in 48px pale squares.

**Transfer:** Use clean rounded outline symbols for human benefits, compact checks for lists and small directional arrows for links. Match the blue or text color to the surrounding role rather than introducing a multicolor icon family.

## Section recipes

How recurring sections are built.

### First screen: Daylight product opening

**Observed:** Porcelain canvas fills the first screen. Floating navigation spans 1200px above a centered content stack. A translucent announcement pill appears above the 62px bold navy headline, with a 48px separation. The headline occupies about half the viewport width and stays one line when the promise is short. Two 22px supporting lines sit roughly 16px below; paired Primary button and Secondary button follow after 48px, with a small underlined resource link below. Blue glass symbols frame both sides of the copy, with a faint dotted-grid atmosphere beneath. A low logo strip with fading side edges is visible near the bottom of the first 900px. Detailed product demonstration and the benefits scene follow below the fold; no giant central app window competes with the promise.

**Transfer:** Keep the centered promise and side-object frame for a new product. Use symbolic SVG output objects if no polished render is available. Company pages simplify the opening to a small tag, headline, one support line and a single action. Pricing pages use a compact 56px title and two 18px lines, bringing the plan grid into the first screen.

**Avoid:** Do not turn the opening into a split-screen sales layout, fill the center with a large dashboard, or use a saturated blue hero background.

**Text style:** `display` — Aeonik 700 · 62px/1.05

### Proof stage and glass rail

**Observed:** A centered 56px heading introduces Luminous proof stage with a small frosted emblem above. Overlapping output examples rise above the foreground rail; the diffuse halo connects them without a hard enclosing card.

**Transfer:** Use this device to make an abstract benefit tangible through contrasting examples. The content and its location in the story can change.

**Text style:** `heading-lg` — Aeonik 500 · 56px/1.15

### Numbered demonstration spine

**Observed:** A centered section title leads into Numbered feature cards. Each card sits inside the broad container with its numeral tab protruding at upper left; a 32px headline colors one short word blue. Explanation is 16px and media is 540px wide. Some chapters contain two demonstrations; the final card stacks several Example panels.

**Transfer:** Organize a new workflow into meaningful chapters with enough room to see the output. Preserve the numbered spine, not the source's number of steps.

**Text style:** `feature-heading` — Aeonik 500 · 32px/1.2

### Fading testimonial wall

**Observed:** A centered 40px heading and small supporting trust line lead to two offset rows of Testimonial cards. Rows overflow the viewport with 10px card gaps and masked left/right edges; varying quote lengths create an uneven lower edge.

**Transfer:** Use a supplied customer count only when substantiated. Authentic proof can be shorter, but retain identity strips and edge-faded horizontal composition.

**Text style:** `heading` — Aeonik 500 · 40px/1.2

### Nightfall conversion and footer

**Observed:** Plum night scene is a full-width 854px composition combining conversion and footer. A small white identity mark precedes a centered 56px white headline, 22px support and one Primary button. Blue glass symbols and tiny stars frame the call. Below, a category-link rail spans the width with 8px violet dots beneath labels and a right-aligned all-items link. Social and backing links form two broad groups; a white-at-20% hairline separates them from compact legal links and copyright at the bottom. The same complete ending is used across all page types.

**Transfer:** Always include the dark re-lit closing scene and dotted category rail. Categories can become output types, use cases or resources; retain the conversion above and utility navigation below.

**Text style:** `heading-lg` — Aeonik 500 · 56px/1.15

### Letter and note field

**Only for:** company and recruiting pages

**Observed:** Editorial letter sheet pairs a bold 56px left-column title and small lower video with a right-column narrative in 20px prose. A subsequent centered 40px heading and support introduce the subtly tilted Culture notes on a porcelain-to-white gradient.

**Transfer:** Use the letter for a genuine perspective and the note field for concise principles relevant to the organization.

**Text style:** `editorial-display` — Aeonik 700 · 56px/1.2

### Benefit and process pairs

**Only for:** company and recruiting pages

**Observed:** White benefit band uses a two-column composition: 40px heading, paragraph and action at left, six icon-led rows at right. The process section returns to porcelain, pairing a left explanatory heading with vertically stacked white 580px cards at right. Stage labels are blue 14px uppercase with 0.1em tracking; titles are 24px and compact metadata follows the body.

**Transfer:** Keep the process concrete through durations, participants or deliverables, and use the paired layout for scannability rather than adding decorative diagrams.

**Text style:** `heading` — Aeonik 500 · 40px/1.2

### Role list and backing proof

**Only for:** recruiting pages

**Observed:** A 40px section title sits above broad Role rows; a compact centered investor and individual-backer strip follows before the shared dark closing scene.

**Transfer:** Use the final light section to resolve practical participation details and provide credible backing, then return to the product conversion.

**Text style:** `heading` — Aeonik 500 · 40px/1.2

### Plan comparison and objections

**Only for:** pricing pages

**Observed:** Compact centered title precedes three Plan cards with small glass symbols. The middle recommendation is outlined blue, not filled blue. A broad white integration offer and a low fading customer-logo strip lead toward FAQ outer glass; the centered 56px FAQ heading sits above FAQ accordion.

**Transfer:** Keep plan artwork subordinate to price and inclusions. Present a developer or enterprise extension as a separate wide offer when relevant, then answer practical objections.

**Text style:** `plan-price` — Aeonik 500 · 24px/1.2

## Page flow

**Storyline:** Promise → tangible output proof → understandable capability chapters → trust or practical decision support → nightfall conversion and utility navigation.

### Product marketing and conversion

1. **Promise** — Centered headline, two support lines, paired actions and floating blue symbols.
2. **Product proof** — Overlapping output examples above a glass benefit rail.
3. **Capability chapters** — Narrow numbered cards explain the workflow through demonstrations and contextual outputs.
4. **Social proof** — Two edge-faded testimonial rows.
5. **Closing call** — Dark re-lit product scene, category rail and complete footer.

**Transfer:** Make a concrete result visible early and let the detailed workflow earn the closing action.

### Recruiting and organizational trust

1. **Invitation** — Centered bold headline, short support and one open-roles action.
2. **Perspective** — Large white letter sheet with narrative and small founder video.
3. **Fit and benefits** — Tilted principle notes followed by a two-column benefit band.
4. **Process transparency** — Editorial heading paired with staged cards and compact logistics.
5. **Decision support** — Broad role rows and compact backing proof.
6. **Closing call** — Shared nightfall product conversion and complete footer.

**Transfer:** Explain the working experience and practical next steps without abandoning the product's visual identity.

### Plan selection and purchase reassurance

1. **Orientation** — Short centered title and two lines clarifying the free-to-paid progression.
2. **Pricing** — Three equal-height white plan cards, a blue recommendation outline and anchored actions.
3. **Extended offer** — Wide integration proposition and a fading customer-logo strip.
4. **Objection handling** — Question accordion nested in a translucent white band.
5. **Closing call** — Shared nightfall scene, dotted category links and complete utility footer.

**Transfer:** Keep comparison factual and the recommendation lightweight; follow it with practical questions before the shared conversion.

## Writing

Plainspoken, optimistic and result-led. Technical capability is explained through familiar verbs and useful outcomes, while company prose is warm and candid about how work happens.

**Do not copy:** Do not reuse the Graphy name, logo, product terminology as a brand asset, customer or investor names, quoted endorsements, user counts, prices, performance claims or proprietary artwork. Replace all examples with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work in product copy; use we for team perspective and first-person customer language only in authentic testimonials.
- **Rhythm:** Headlines are usually three to six words. Supporting promises fit one or two sentences; card explanations are short and practical. Longer narrative paragraphs belong only to editorial company content.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the product category directly, with one differentiator. | 4–6 words | “The AI Graph Maker” |
| Supporting promise | Move from a messy starting point to a clear result, then explain why it matters. | One or two short sentences | “From messy data to beautiful graphs in a click,”<br>“[Brand] is the fastest way to tell stories with data.” |
| Feature heading | Use a short imperative or familiar active phrase with one expressive word. | 3–6 words | “Make your data shine”<br>“Tell your story” |
| Primary action | State the immediate next step rather than a vague aspiration. | 2–4 words | “Start for free”<br>“View Open Roles” |
| Editorial support | Explain the human working experience with specific everyday language. | One or two sentences | “You’ll work closely with founders and teammates who care deeply about what they build, how it works, and how it feels for the people using it.” |
| Objection handling | Write the exact practical question a customer would ask. | One question | “Can I use [Brand] for free?” |

**Words and phrasing to use:** your; beautiful; clear; story; share; in seconds; no need to; work; build; start

**Avoid:** revolutionary paradigm; unlock synergies; best-in-class ecosystem; enterprise-grade transformation; disrupt everything

**Rules:**

- Lead with the result, then explain the mechanism in familiar terms.
- Use one expressive word in a heading rather than a string of adjectives.
- Keep interface and integration details in the explanatory card, not in the main promise.
- Support confidence with a real demonstration, a specific inclusion or an attributed quote.
- Company prose may be longer and more conversational, but should remain concrete.

## Do's and Don'ts

### Do

- Keep the opening headline at 62px/1.05 and subsequent major headings at 56px/1.15.
- Maintain navy headings and slate supporting text instead of default black body copy everywhere.
- Use 20px corners on the 54px primary action and 12px corners only on compact 42px actions.
- Center the 600px demonstration spine within the 1200px page container.
- Make nested media panels subtly cooler than their white parent card.
- Repeat the blue glass symbols in both daylight and the plum closing scene.
- Use thin gradient edges and 16px prose padding on testimonial cards.
- Keep plan prices at 24px rather than turning them into oversized statistic displays.

### Don't

- Do not tighten all headline tracking; normal tracking is characteristic at 32px, 40px, 56px and 62px.
- Do not round every card to 24px; the main explanatory cards use 8px corners.
- Do not make secondary buttons outlined capsules; their near-white filled 20px-corner silhouette matters.
- Do not color entire body sections electric blue; reserve that intensity for actions, small objects and short emphasis.
- Do not flatten the floating symbols into ordinary line icons; preserve frosted faces and luminous edges.
- Do not replace the narrow chapter spine with a generic three-column feature grid.
- Do not make the recommended plan a solid blue slab; keep it white with a blue edge.
- Do not use large lifestyle photography to lead the product story; human images stay small and supporting.

## Motion and responsive

### Motion

**Observed:**

- Header remains fixed across scroll positions.
- Horizontal proof and category rails use translated overflow tracks and side masks.
- Header links declare reduced black opacity and underline on hover; footer social links declare reduced silver opacity and underline.
- No action or surface transition durations are established.

**Transfer:**

- Retain fixed translucent navigation and edge-masked horizontal rails; any movement should keep the center copy readable.

**Unknown:**

- Ticker speed, direction, interaction behavior and easing are not established.
- Demonstration-video timing and hover/focus treatments for filled buttons are not established.

### Responsive

**Observed:**

- Declared width boundaries occur around 810px, 1200px and 1600px.

**Transfer:**

- Recommended adaptation: stack editorial and pricing columns, keep numbered tabs adjacent to their chapter titles and fit media to the available card width.
- Recommended adaptation: reduce the number of side objects before letting them overlap the centered promise; retain the daylight-to-nightfall motif on narrow screens.

**Unknown:**

- Mobile type sizes, navigation collapse behavior and exact responsive object placement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
