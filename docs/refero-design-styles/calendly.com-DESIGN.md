# Calendly — buoyant work in motion

## Overview

A warm, light software identity that makes complex work feel approachable and already handled. Inky blue grotesk headlines and crisp utilitarian text alternate with expressive editorial serif moments. Soft blue, mint and lilac atmospheres carry floating interface illustrations and friendly people photography, while spacious cream surroundings keep the experience unhurried.

### Essentials

- Two voices separate promise from explanation: Calendly Sans headlines at 72px/1.1, weight 500, -2px tracking; Wulkan Text capability headings at 48px/1.1, weight 500, -2px tracking.
- An opening promise sits above a luminous working model: centered 640px headline, 560px support, paired 50px dark actions, then a 1200px-wide rounded product stage entering the first screen.
- Softness is structural, not pill-shaped: 64px rounded section islands, 48px cards and 20px primary buttons; the navigation uses a 16px button variant.
- Color lives behind work, not across every paragraph: cream and stone dominate the reading canvas, with blue–mint–lilac gradients reserved for product stages and proof bands; the final footer is solid #071a31.
- Product explanations float as white interface fragments over blurred color and fine rhythmic bars: use a 580px square stage opposite a 532px text column; a simplified HTML task card is the fallback when finished product art is unavailable.
- Connected shapes make completion tangible: join white word capsules with narrow concave bridges, pairing 36px sans nouns with 36px serif outcomes; carry this device into a people-and-outcomes strip or an equivalent product-result scene.
- The ending is a destination rather than a thin utility bar: a 64px-radius navy island holds a 60px/1.1 closing sentiment, three dense link columns and separate 48px download/social tiles.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Midnight ink | `#071a31` | `--color-ink` | text, background, action, border | Primary headings, dark actions and closing island. At 5% over cream it makes faint control wells; at 10% it makes restrained rules. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale interface backing | `#c3dffe` | `--color-soft-blue` | surface | Light blue backing around the opening interface illustration. |
| Cornflower | `#6bb1ff` | `--color-blue` | accent, text, border | Graphic bars, focused action borders and blue proof numerals. |
| Honeydew | `#f2f8de` | `--color-honeydew` | accent, surface | Fine graphic bars and pale testimonial action strips. |
| Mint graphic | `#baf0ec` | `--color-mint` | accent | Geometric outcome ribbons and luminous media fields. |
| Lavender graphic | `#d4c2ff` | `--color-lavender` | accent | Fine outcome bars and soft illustration fields. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Floating white | `#ffffff` | `--color-white` | surface, text | Raised cards, interface fragments and floating navigation. |
| Magnolia | `#fcfbf8` | `--color-canvas` | background, text | Default page canvas and inverse text. |
| Warm stone | `#f5f3ee` | `--color-stone` | surface, background | Opening enclosure and warm cards. |
| Stage underlay | `#e4e6e9` | `--color-stage-base` | surface | Neutral foundation beneath colorful product artwork; not a substitute for the artwork. |
| Silver rule | `#d8dce0` | `--color-rule` | border | Capability separators and quiet edges. |
| Slate copy | `#5f6d77` | `--color-secondary` | text | Supporting paragraphs and subordinate descriptions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| quantified proof sections | Jade numeral | `#5ddfd7` | `--color-stat-jade` | text | Large serif proof numbers. |
| quantified proof sections | Lilac numeral | `#b89ffa` | `--color-stat-lilac` | text | Large serif proof numbers. |

## Typography

- **Calendly Sans** — Main promises, section headings, capability titles and outcome nouns. Friendly compact sans with open counters and tightly fitted large text. If unavailable, use **Inter**. Use 400–500; retain negative tracking and constrained headline width. Font stack: "Calendly Sans", "Inter", system-ui, -apple-system, "Segoe UI", Roboto, sans-serif.
- **Geist** — Body text, actions, navigation and uppercase section markers. Clean contemporary grotesk with sturdy small-text readability. Font stack: "Geist", system-ui, -apple-system, "Segoe UI", Roboto, sans-serif.
- **Wulkan Text** — Capability chapter headings, quotes, outcome verbs and expressive numbers. High-contrast editorial serif with sculptural curves and a warm literary tone. If unavailable, use **Libre Caslon Display**. Match line breaks carefully; use the closest available weight and preserve tight tracking. Font stack: "Wulkan Text", "Libre Caslon Display", Georgia, serif.
- **ui-sans-serif** — Closing footer sentiment. Plain system sans contrasts with the more authored headline face. Font stack: "ui-sans-serif", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Calendly Sans | 500 | 72px | 1.1 | -2px | Centered first-screen promise. |
| heading-lg | Calendly Sans | 500 | 60px | 1.1 | -2px | Main chapter and conversion headings, usually within 640px. |
| closing-line | ui-sans-serif | 500 | 60px | 1.1 | -2px | Large left-hand sentiment inside the dark footer. |
| heading-editorial | Wulkan Text | 500 | 48px | 1.1 | -2px | Left-aligned capability chapters and centered FAQ headings. |
| heading-small | Calendly Sans | 500 | 36px | 1.1 | -1px | Result headlines, plan names and outcome nouns. |
| outcome-serif | Wulkan Text | 500 | 36px | 1.1 | -1px | Completion word in connected outcome capsules. |
| quote-editorial | Wulkan Text | 500 | 28px | 1.2 | normal | Customer quotes in image-led proof cards; names on company profile cards. |
| item-heading | Calendly Sans | 500 | 20px | 1.4 | normal | Capability list titles and FAQ questions. |
| lead | Geist | 400 | 18px | 1.4 | normal | Hero and section support paragraphs. |
| footer-heading | Geist | 500 | 18px | 1.4 | normal | Footer link-group titles. |
| body | Geist | 400 | 16px | 1.4 | normal | Capability descriptions and compact card paragraphs. |
| action | Geist | 500 | 16px | 1.4 | normal | Section conversion actions. |
| navigation | Geist | 500 | 14px | 1.4 | normal | Navigation and short utility links. |
| small | Geist | 400 | 14px | 1.4 | normal | Compact descriptions, header actions and footer links. |
| eyebrow | Geist | 600 | 12px | 1 | 1px, uppercase | Short categorical section markers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| quantified proof sections | proof-number | Wulkan Text | 400 | 90px | 1.1 | -0.02em, features "dlig" | Oversized colorful serif metric. |
| pricing pages | pricing-opening | Calendly Sans | 500 | 48px | 1.1 | -2px | Compact left-aligned opening above plan cards. |
| company and enterprise pages | quote-wide | Calendly Sans | 400 | 36px | 1.1 | -1px | Wide testimonial panel quotation. |

**Notes:**

- Keep the large sans promise distinct from the serif explanation; do not apply serif styling to every headline.
- Large headings use a fixed -2px tracking; 36px text steps back to -1px. Body and controls return to normal tracking.
- Regular prose is weight 400. The main heading tone comes from weight 500, not heavy bold.

## Layout

**Density:** Airy between chapters, compact within functional elements: long feature narratives are punctuated by tightly grouped controls and micro-labels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small label groups, footer links and icon-tile gaps. |
| 12px | Navigation action gaps and icon-to-label gaps. |
| 16px | Heading/support pairs and action groups. |
| 24px | Outer island inset, grid gaps and card padding. |
| 32px | Support-to-action spacing and horizontal story-card gaps. |
| 48px | Opening demonstration panel padding and larger interior groups. |
| 56px | Capability row vertical padding and heading rule clearance. |
| 64px | Section heading-to-content separation. |
| 96px | Closing art clearance and pricing opening top padding. |
| 120px | Major chapter top and bottom padding. |

### Containers and grids

- **content**: max width 1280px · side padding 40px. Centered desktop wrapper yielding 1200px of usable content at 1440px.
- **section-island**: max width 1920px · side padding 24px. Wide rounded bands inset from the page edge.
- **heading**: max width 640px. Centered two- or three-line headline; lead text narrows to 560px.
- **capability-split**: max width 1200px · 2 columns · gap 88px. 532px text column opposite a 580px square stage; alternate sides between chapters.
- **card-grid**: max width 1200px · 3 columns · gap 24px. Equal 384px feature tiles or narrower centered metric cards.
- **faq**: max width 770px. Centered single column of questions beneath a serif heading.
- **plans** (only for pricing pages): max width 1200px · 4 columns · gap 24px. Four 282px outer plan columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | section islands | 64px |
|  | cards | 48px |
|  | primary actions | 20px |
|  | header actions | 16px |
|  | outcome capsules | 24px |
|  | icon tiles | 12px |
|  | square feature art | 80px |
| pricing pages | plan inner panels | 40px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating-panel | `0px 4px 5px 0px rgba(95,109,119,0.04), 0px 8px 15px 0px rgba(95,109,119,0.03), 0px 30px 50px 0px rgba(95,109,119,0.08)` | Navigation, wide quote panels and outer plan cards. |
| quantified proof sections | metric-card | `0px 4px 5px 0px rgba(95,109,119,0.04), 0px 4px 10px 0px rgba(95,109,119,0.03), 0px 10px 20px 0px rgba(95,109,119,0.05)` | White proof cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default reading ground.

**CSS:** `background: #fcfbf8; color: #071a31`

#### Warm enclosure · level 0

**Use:** Opening promise plus demonstration; also plan overview and FAQ islands.

**CSS:** `background: #f5f3ee; border-radius: 64px; overflow: clip`

**Observed:** A very broad quiet field with rounded corners, not a visibly outlined box.

**Transfer:** Group related narrative into one soft enclosure.

#### Warm card · level 1

**Use:** Feature summaries and supporting link cards.

**CSS:** `background: #f5f3ee; border-radius: 48px; padding: 24px`

#### Raised white · level 2

**Use:** Proof, navigation and floating interface fragments.

**CSS:** `background: #ffffff; border-radius: 64px; box-shadow: 0px 4px 5px rgba(95,109,119,0.04), 0px 8px 15px rgba(95,109,119,0.03), 0px 30px 50px rgba(95,109,119,0.08)`

**Observed:** Soft cool-gray lift without a dark perimeter stroke.

**Transfer:** Use lift only where a card floats above another surface.

#### Dark ending · level 0

**Use:** Final navigation and closing sentiment.

**CSS:** `background: #071a31; color: #fcfbf8; border-radius: 64px`

#### Luminous stage · level 1

**Use:** Color atmosphere behind explanatory media.

**CSS:** `background: #e4e6e9; border-radius: 64px; overflow: hidden`

**Observed:** The neutral underlay is covered by broad blue, mint and lilac light fields; white objects hover in front.

**Transfer:** Use the Atmospheric fields recipe for the visible treatment.

#### Quote action band · level 1

**Only for:** company and enterprise testimonials

**Use:** Full-width bottom action on a white quote panel.

**CSS:** `background: #f2f8de; padding: 24px 0px; text-align: center`

#### Comparison cells · level 0

**Only for:** pricing comparison tables

**Use:** Quiet vertical shading behind plan values.

**CSS:** `background: rgba(245,243,238,0.5); mix-blend-mode: multiply`

**Observed:** Rows have 1px ink-at-10% separators; value columns are shaded while descriptive labels stay on cream.

**Transfer:** Keep dense comparison data flat rather than placing each cell in a card.

## Components

### Primary button

**Use:** Default section conversion action.

**CSS:** `background: #071a31; color: #fcfbf8; border: 2px solid transparent; border-radius: 20px; padding: 12px 20px; height: 50px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `action` — Geist 500 · 16px/1.4

**Observed:** A rounded rectangle, sometimes with a right arrow. Header actions use the smaller 16px-radius variant and small text. Over blue hero art, use a cream-filled inverse action.

**States:** Declared: hover background #0e396a; focus-visible border #6bb1ff with outline none; active background #1e5ea7.

### Provider button

**Use:** Paired signup choices in the default opening.

**CSS:** `background: #071a31; color: #fcfbf8; border: 2px solid transparent; border-radius: 20px; padding: 4px 16px 4px 4px; height: 50px; gap: 12px`

**Text style:** `action` — Geist 500 · 16px/1.4

**Observed:** An inset 38px cream icon square leads the label. Two options sit side by side with a quieter text alternative below.

**States:** Declared: hover background #0e396a; focus-visible border #6bb1ff; active background #1e5ea7.

**Transfer:** Use provider choices only when the new product actually supports them; otherwise retain the same compact action grouping.

### Outline header button

**Use:** Secondary utility action beside the filled header conversion.

**CSS:** `color: #071a31; background: transparent; border: 1.5px solid #071a31; border-radius: 16px; padding: 12px 16px; height: 48px`

**Text style:** `small` — Geist 400 · 14px/1.4

**Observed:** A restrained outline balances the dark conversion button. Section-level outline actions increase radius to 20px and use action text.

**States:** Declared: hover background #071a31 and text #fcfbf8; focus-visible 2px solid #6bb1ff outline at -2px offset; active background and border #0e396a.

### Floating navigation

**Use:** Persistent desktop navigation after the opening header.

**CSS:** `background: #ffffff; border-radius: 64px; height: 72px; box-shadow: 0px 4px 5px rgba(95,109,119,0.04), 0px 8px 15px rgba(95,109,119,0.03), 0px 30px 50px rgba(95,109,119,0.08)`

**Text style:** `navigation` — Geist 500 · 14px/1.4

**Observed:** Brand and category links occupy the left; sales, login and conversion sit on the right. The floating bar is inset 48px from both desktop edges. The initial header is a flat 68px row, with a 40px announcement strip on applicable pages.

### Capability row

**Use:** Scroll-linked explanatory chapters.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding: 56px 0px; max-width: 532px`

**Text style:** `item-heading` — Calendly Sans 500 · 20px/1.4

**Observed:** A small outline icon precedes the title. Description and a 32px arrow control sit below, above a 1px silver separator. The active item is emphasized while inactive rows recede; the large visual remains alongside the list.

**Transfer:** Give each row one meaningful state or task, not a long inventory of features.

### Feature tile

**Use:** Compact capability summaries.

**CSS:** `background: #f5f3ee; border-radius: 48px; padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `body` — Geist 400 · 16px/1.4

**Observed:** Top row places an outline icon left and a small square diagonal arrow right; title and short paragraph follow. Desktop tiles form a three-column grid.

**Transfer:** Use a concise title and a two- or three-line description.

### Outcome capsule

**Use:** Short noun/result overlays on people and product art.

**CSS:** `color: #071a31; border-radius: 24px; padding: 0px 12px; height: 56px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `heading-small` — Calendly Sans 500 · 36px/1.1 · tracking -1px

**Observed:** White capsule artwork connects the noun, colored icon and serif completion word using hourglass-like bridges. Text stays on a single line; its shadow belongs to the whole connected group.

**Transfer:** Pair a concrete object with a completed state, such as Project / Delivered, using outcome-serif for the second word.

### Footer link

**Use:** Dense grouped navigation within the dark ending.

**CSS:** `color: rgba(252,251,248,0.698); display: inline-flex; gap: 8px`

**Text style:** `small` — Geist 400 · 14px/1.4

**Observed:** Links sit in 200px-wide groups at an 8px vertical gap; group headings are brighter and slightly larger.

**States:** Declared: hover color #fcfbf8; focus-visible outline 2px solid #6bb1ff at 0px offset.

### Footer icon tile

**Use:** Download and social destinations below the footer divider.

**CSS:** `background: rgba(252,251,248,0.05); border: 1px solid rgba(252,251,248,0.1); border-radius: 12px; width: 48px; height: 48px; display: inline-flex; align-items: center; justify-content: center`

**Observed:** A centered 24px icon sits inside each tile; download and social groups align to opposite sides.

**States:** Declared: hover background rgba(252,251,248,0.1); focus-visible outline 2px solid #6bb1ff at 0px offset.

### Metric card

**Only for:** quantified proof sections

**Use:** Outcome-led proof on a colored atmosphere.

**CSS:** `background: #ffffff; border-radius: 48px; padding: 24px; box-shadow: 0px 4px 5px rgba(95,109,119,0.04), 0px 4px 10px rgba(95,109,119,0.03), 0px 10px 20px rgba(95,109,119,0.05)`

**Text style:** `proof-number` — Wulkan Text 400 · 90px/1.1 · tracking -0.02em

**Observed:** Large pastel serif number dominates a white card; explanatory label precedes it. Enterprise variants add a customer mark, faint rule and bottom case-study link, with gently alternating card tilts.

**Transfer:** Use independently supportable metrics and let the card number remain the strongest element.

### Plan panel

**Only for:** pricing pages

**Use:** Nested pricing overview.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; gap: 48px; box-shadow: 0px 4px 5px rgba(95,109,119,0.04), 0px 8px 15px rgba(95,109,119,0.03), 0px 15px 30px rgba(95,109,119,0.06)`

**Text style:** `heading-small` — Calendly Sans 500 · 36px/1.1 · tracking -1px

**Observed:** White summary panel nests inside a cream 48px-radius outer column with 8px inset. Plan name and optional add-on toggle sit above a serif price and full-width action. Only the recommended plan gets a luminous colored outer sleeve, an uppercase popularity marker and dark action.

## Imagery and graphics

### Atmospheric fields

**Use:** Signature material behind product demonstrations, proof bands and outcome scenes.

**Observed:** Broad blurred blue light grades into mint, lilac and occasional warm pink. Fields feel like soft illuminated fabric rather than distinct gradient stripes. Product squares deepen toward navy along one edge; proof bands fade back into cream at the bottom.

**Transfer:** Retain the soft glow and readable foreground contrast; exact gradient stops are not essential.

**Build:** Recommended reconstruction: layer three oversized radial ellipses over a blue base, using rgba(107,177,255,0.9), rgba(186,240,236,0.85) and rgba(212,194,255,0.85). Blur the overlapping fields by 60px–100px inside the rounded stage; use a navy-to-transparent edge layer for depth and a cream-to-transparent bottom layer on proof bands. Keep the glow broad enough that no ellipse has a visible boundary.

### Floating task models

**Use:** Hero demonstration and alternating capability chapters.

**Observed:** Cropped task-oriented interface fragments hover above a bright square backdrop. White rounded cards, pale double rims, gentle shadows and oversized readable labels replace full application chrome. Fine horizontal or vertical bars run behind the cards; occasional headshots humanize the task.

**Transfer:** Build a simplified HTML/SVG model of one actual product action, occupying roughly half the stage width. A white task card plus two meaningful states is the minimum acceptable model.

**Build:** Use a 580px square rounded stage, center a white task card around 300px wide with a translucent pale outer rim, then overlap one smaller status capsule. Add a horizontal band of evenly spaced 1px–4px lines behind it, tinted honeydew, mint or lavender. Use SVG rectangles with gradually varying widths rather than a generic dotted texture.

### Connected workflow shapes

**Use:** Multi-step overview and outcome labels.

**Observed:** White cards are linked with narrow pinched bridges; tall overview cards carry huge faint circular arcs near the bottom. This repeats the connected capsule geometry used on people scenes.

**Transfer:** Keep this physical connection device for a new workflow, even when no original illustration is available.

**Build:** Arrange rounded rectangles with a 24px gap. Bridge neighboring cards with a narrow white rectangle and cut concave semicircles from its top and bottom using an SVG path or mask. Behind the lower content, place oversized quarter-circle arcs filled with extremely pale mint and lavender gradients; clip them to the card group.

### People with outcomes

**Use:** Conversion strip and customer proof.

**Observed:** Warm, natural-color portraits and working scenes are framed in generous rounded rectangles. In the outcome strip, cutout standing people extend slightly above pastel rectangular backings. A central card is larger than partially visible side cards, with connected labels crossing the torso.

**Transfer:** Use genuine users or product-makers in relaxed work contexts. If portrait cutouts are unavailable, stage a real product object against the same glow with connected outcome labels; do not replace the scene with generic decorative blobs.

**Build:** For the strip, center a 656px-wide art group with smaller neighboring groups scaled to 0.85 and clipped by the viewport. Use a 48px-radius gradient backing, a foreground cutout extending above it, an approximately 120px-high band of fine rhythmic lines behind the subject and a connected white label across the lower middle.

### Company photography

**Only for:** company and culture pages

**Use:** Leadership profiles and horizontal culture stories.

**Observed:** Leadership uses evenly lit chest-up portraits on neutral light-gray backgrounds, inset in stone cards. Culture photography is candid, warmly colored and framed in 384px by 288px rounded landscape panels moving across a horizontal rail.

**Transfer:** Keep portrait lighting and framing consistent; use event and collaboration images for the rail rather than mixing them into executive profile cards.

### Icons

**Observed:** Small outline symbols commonly use 16px or 24px boxes with 2px round-capped strokes in ink. Category marks add pastel rounded backplates; arrows are simple, thin and directional. Integration marks retain their native colors inside warm 112px tiles.

**Transfer:** Use one rounded outline family for marketing controls, with colored backplates reserved for stable product categories. Keep third-party marks visually separate from this outline vocabulary.

## Section recipes

How recurring sections are built.

### First screen: Promise over working stage

**Observed:** A cream page carries a flat header and a wide stone enclosure inset 24px with 64px corners. The centered promise occupies a 640px column in two lines at 72px/1.1, weight 500, -2px tracking, with generous breathing room above. A 560px support line follows at 24px distance; paired Provider buttons follow at about 32px, with a small text alternative and reassurance below. A 1200px-wide glowing product stage begins at 624px down the first screen, showing category tabs and the upper part of a cream 996px demonstration panel. Within the first 900px the full headline, support and actions are visible, plus a substantial preview of the main object; most of the demonstration continues below. Layers run stone enclosure, blurred atmosphere, category controls, cream content panel, pale blue media backing, floating white task card.

**Transfer:** Default new marketing pages should use this text-first promise over a luminous working model. Replace the model with a simplified task/result illustration if necessary. Product and enterprise variants instead open with a nearly full-screen blue atmosphere, inverse centered headline and light action; company openings may omit the action. Pricing opens with a smaller left headline and right support/billing controls above four plan cards.

**Avoid:** Do not turn the opening into a left-copy/right-dashboard split or a wall of small feature cards. Do not push all product evidence below the first screen.

**Text style:** `display` — Calendly Sans 500 · 72px/1.1 · tracking -2px

### Heading pair

**Observed:** Eyebrow above heading-lg with a 16px gap; lead copy follows at 16px and actions at 32px. Centered headings use a 640px width and support narrows to 560px. Left-aligned variants reserve the opposite side for actions.

**Transfer:** Use the eyebrow to classify the next argument, the headline to state its benefit and the support to explain the mechanism.

**Text style:** `heading-lg` — Calendly Sans 500 · 60px/1.1 · tracking -2px

### Capability chapter

**Observed:** A 1200px split pairs a 532px list with 580px square Floating task models. The heading-editorial title and small category label sit above a rule; Capability rows follow. The text and stage stay aligned through a chapter, and their sides alternate in subsequent chapters. Major chapters have 120px vertical padding.

**Transfer:** Show one product capability through several meaningful states; reserve long scroll-linked treatment for a genuine explanatory sequence.

**Text style:** `heading-editorial` — Wulkan Text 500 · 48px/1.1 · tracking -2px

### Connected process overview

**Observed:** Centered heading and support lead into connected tall white cards, with one wider active card and narrower neighboring steps at 24px gaps. Each holds a short stage title, compact description and lower interface artwork. Connected workflow shapes unify the group.

**Transfer:** Express a before/during/after progression for the new product, not necessarily the same number of steps.

### Image-led proof fan

**Observed:** A white heading sits on Atmospheric fields above a central 762px by 513px raised proof card. Sans result headline and serif quote occupy the left half, a rounded working photograph the right. Narrow portrait slivers flank both sides; a small segmented progress indicator sits below.

**Transfer:** Make the result and human context equally legible; use a real working image and a short attributed quote.

### Ecosystem field

**Observed:** Centered heading, support and arrow link introduce two staggered rows of colorful integration marks in warm rounded tiles. Two broad Feature tiles below summarize related families of connections.

**Transfer:** Show an ecosystem only where the product has real connections; retain the staggered visual rhythm rather than a rigid logo wall.

### Outcome conversion strip

**Observed:** A centered heading pair and Primary button lead to People with outcomes separated by about 96px. The art rail extends beyond both viewport edges. Outcome capsules make noun and completion word read as a single connected statement.

**Transfer:** Carry the connected completion device into a conversion moment, using people or a tangible product result.

### Closing destination

**Observed:** Dark ending is inset 24px and extends about 990px vertically. A 400px left column holds a large closing sentiment and a brand signature near its bottom; three 200px link columns occupy the right. A restrained divider separates this from download/social tile groups and a final locale/legal row. The sentiment and links start with roughly 96px interior top breathing room.

**Transfer:** End with a short human benefit, useful destination groups and an unmistakable brand signature. Adapt the number of links to the new product without collapsing the composition into a narrow strip.

**Text style:** `closing-line` — ui-sans-serif 500 · 60px/1.1 · tracking -2px

### Numerical proof fan

**Only for:** company and enterprise pages

**Observed:** Three Metric cards sit on an Atmospheric fields band under an inverse heading. Large blue, jade and lilac serif numbers anchor the cards; slight alternating tilts soften the arrangement. Enterprise cards add marks and case-study links; company cards are shorter and simpler.

**Transfer:** Use a small set of complementary, defensible metrics, each with a clear label.

**Text style:** `proof-number` — Wulkan Text 400 · 90px/1.1 · tracking -0.02em

### Wide testimonial

**Only for:** company and enterprise pages

**Observed:** Raised white panel spans 1200px, with 64px interior padding, a 36px regular sans quote, a small portrait and subdued name/title tags. Quote action band forms the full bottom edge. Company variants add logo tabs above; enterprise uses a single customer mark.

**Transfer:** Use this text-led proof treatment when a quote needs space rather than a large working photograph.

**Text style:** `quote-wide` — Calendly Sans 400 · 36px/1.1 · tracking -1px

### Comparison and objections

**Only for:** pricing pages

**Observed:** Nested Plan panels on Warm enclosure lead to a flat feature matrix. Persistent plan headings and compact buttons sit above shaded value columns; descriptive feature labels use small text and fine rules. A separate warm FAQ island follows, with a centered serif title and 770px question column.

**Transfer:** Keep the commercial choice visually simple before revealing dense details; use dark actions only for the highlighted plan.

### FAQ list

**Only for:** product and pricing pages

**Observed:** A heading-editorial title sits above a narrow centered list. Rows are about 81px high, separated by ink-at-10% rules; a 32px pale square plus control precedes each 20px question. Product variants sit on cream; pricing puts the list inside Warm enclosure.

**Transfer:** Choose objections that affect purchase or adoption, not encyclopedic product documentation.

**Text style:** `heading-editorial` — Wulkan Text 500 · 48px/1.1 · tracking -2px

## Page flow

**Storyline:** Promise → tangible working model → capability explanation → human or numerical proof → ecosystem and objections → completed-outcome conversion → substantial closing destination.

### Broad product marketing landing page

1. **Promise** — Centered large sans promise over a luminous demonstration.
2. **Product demonstration** — Multi-category task model and connected workflow overview.
3. **Capability chapters** — Alternating serif-headed lists and square stages.
4. **Social proof** — Image-led result carousel with a white central card.
5. **Ecosystem** — Staggered mark field and linked family cards.
6. **Closing call** — Outcome conversion strip, then the dark closing destination.

**Transfer:** Choose the chapters that explain the new product best; preserve the contrast between neutral reading areas and luminous models.

### Company identity and trust

1. **Promise** — Inverse centered purpose statement on a blue atmospheric island.
2. **Context** — Narrow 560px editorial prose.
3. **Quantified proof** — Short serif-number cards on a luminous band.
4. **People** — Two-column leadership profiles with serif names.
5. **Social proof** — Logo-tabbed wide quote with pale action strip.
6. **Culture** — Left heading and career action followed by horizontal candid photographs.
7. **Closing call** — Outcome conversion strip and dark closing destination.

**Transfer:** Translate the company story into an insight, scale, accountable people and lived culture; keep this people-heavy treatment scoped to company content.

### Enterprise evaluation and reassurance

1. **Promise** — Inverse atmospheric hero with a contact action and small customer mark rail.
2. **Capability summary** — Three-column warm feature grid.
3. **Ecosystem** — Staggered integration marks and family cards.
4. **Quantified proof** — Tilted white case-study metric cards.
5. **Risk reduction** — Compliance marks in rounded neutral panels.
6. **Social proof** — Wide quote with bottom action band.
7. **Closing call** — Outcome conversion strip and dark closing destination.

**Transfer:** Balance practical breadth, verified outcomes and procurement reassurance; let the contact action replace provider signup.

### Focused product capability education

1. **Promise** — Inverse centered product hero with light primary and outline secondary actions.
2. **Capability chapters** — Serif-headed scroll-linked list and square task model.
3. **How it works** — Numbered horizontal image rail with compact mixed-weight captions.
4. **Context expansion** — Second capability chapter with art on the opposite side.
5. **Social proof** — Image-led proof fan.
6. **Objection handling** — Centered FAQ list.
7. **Related capabilities** — Horizontal product rail followed directly by the dark closing destination.

**Transfer:** Teach the single core task first, then show adjacent value. The ending can use related capabilities instead of the people conversion strip.

### Commercial comparison and plan selection

1. **Pricing** — Compact split intro, billing controls and four nested plan columns.
2. **Comparison** — Long flat feature matrix with persistent plan actions.
3. **Objection handling** — Warm FAQ island.
4. **Closing call** — Outcome conversion strip and dark closing destination.

**Transfer:** Keep plan summaries scannable, details aligned and the highlighted plan visually distinct without making every column colorful.

## Writing

Warmly decisive and practical. Benefits sound like work becoming easier, supported by concrete mechanisms rather than futuristic spectacle.

**Do not copy:** Do not reuse Calendly names, logos, character names, proprietary graphics, customer identities, quotations, usage figures, comparative claims or product-specific promises. Examples illustrate sentence construction only.

- **Addressing the reader:** Speak directly to the reader as you and your. Use we for company perspective, and the product name as the actor when explaining automation.
- **Rhythm:** Short sentence-case headlines, often five to ten words; one or two plainspoken support sentences. Compact labels and verb-led actions keep the reading rhythm brisk without shouting.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the whole burden, then resolve it with a brief confident completion. | 6–10 words | “All the work around meetings, handled.” |
| Support | Explain the range of useful work, ending in a simple reduction of effort. | 18–30 words | “From AI-powered scheduling to automated meeting recaps and follow-ups, get the busywork done with fewer tools and less effort.” |
| Capability heading | Benefit-first phrasing anchored to a recognizable activity. | 5–10 words | “A better way to book your meetings” |
| Capability description | Use concrete verbs in sequence, then state what the reader controls. | 12–24 words | “Connect your calendars, set your hours, and control exactly when you're available to meet.” |
| Action | Short familiar action with a low-friction next step. | 2–4 words | “Start for free”<br>“Talk to sales” |
| Closing sentiment | A broad human benefit, not a technical feature list. | 4–7 words | “Make space for what matters.” |

**Words and phrasing to use:** handled; make space; your work; next steps; easy; flexible; control; connect; get started

**Avoid:** revolutionary paradigm; disrupt everything; unprecedented synergy; technical jargon without a task; aggressive urgency

**Rules:**

- Describe the task before naming the technology that powers it.
- Tie automation to time, confidence or continuity rather than novelty.
- Use parallel verbs to make complex workflows easy to follow.
- Keep proof numerical or attributable; keep broad benefit language free of invented superlatives.

## Do's and Don'ts

### Do

- Keep default hero type at 72px/1.1 and medium weight.
- Use 120px chapter padding to separate major arguments.
- Pair 48px serif feature headings with 16px sans descriptions.
- Retain 24px outer island insets and 64px corner softness.
- Give colorful task models enough room to read at 580px square.
- Use 20px primary button corners and 16px header button corners.
- Set connected noun/result labels at 36px with contrasting sans and serif families.
- Keep the footer visually substantial, with 200px link groups and 48px icon tiles.

### Don't

- Do not make primary actions bright blue; navy is the default conversion color.
- Do not replace warm cream with a cold pure-white page canvas.
- Do not set the main promise in a heavy 700-weight grotesk.
- Do not cover every neutral card with a strong shadow; elevation distinguishes floating layers.
- Do not use full application chrome when a single task card can explain the benefit.
- Do not apply the 90px colorful serif numeral treatment to ordinary body statistics.
- Do not make 20px-radius buttons into fully rounded pills.
- Do not style dense pricing matrices as a grid of individually raised cards.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.15s color/background/border transitions with cubic-bezier(.4,0,.2,1).
- Capability rows declare opacity transitions at 0.15s with cubic-bezier(.4,0,.2,1).
- Metric cards declare rotate, background-color and box-shadow transitions at 0.2s with cubic-bezier(.4,0,.2,1).
- A trust-mark rail declares infinite linear scrolling; its mark entrance declares 0.6s ease.
- Long capability and horizontal story sequences hold content while the explanatory state advances.

**Transfer:**

- Use state changes to reveal a concrete task outcome, not to obscure the model.
- For long explanations, keep the heading and visual stable while adjacent task states change; make the connected shapes continuous across changes.

**Unknown:**

- Exact playback timing and choreography of the illustrated models and horizontal scroll sequences.

### Responsive

**Observed:**

- Desktop composition is defined at 1440px; CSS includes breakpoints at 640px, 768px, 1024px, 1440px and 1920px among others.
- Grid declarations include one-column bases and multi-column desktop variants.

**Transfer:**

- Recommended narrow-screen adaptation: stack capability copy and model, preserve the connected capsule motif, and let narrative rails remain horizontally browsable.
- Keep the rounded island feeling with reduced edge insets rather than flattening all sections into edge-to-edge blocks.

**Unknown:**

- Actual mobile headline sizes, navigation behavior and scroll-pinning treatment.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
