# Fathom — small tech, big heart

## Overview

A light, personable software style that pairs matter-of-fact product explanations with small, charming line drawings. White space and green-tinted greys dominate, with violet actions, restrained mint highlights and occasional butter-yellow emphasis. Bold system sans headlines, readable conversational paragraphs and real interface imagery make it feel useful rather than aspirational; hand-drawn characters soften the technical detail. It suits independent software, practical services and products whose trustworthiness is part of their appeal.

### Essentials

- Headlines sound like plain-spoken convictions and sit unusually tightly: system sans, 56px/0.95, weight 700, -0.025em tracking; section heads use 40px/0.95 and -0.015em.
- The opening is a modest illustrated promise, not a giant product billboard: an 880px centered column, a 2.2:1 text-to-art split with a 48px gap, and a roughly 260px line illustration; the full-width interface starts near the bottom of the first screen.
- Actions have two distinct scales: 54px-high primary and secondary buttons with 6px corners and 18px text, versus 31px-high utility pills with 24px corners and 13.6px text.
- Color behaves like punctuation: white and green-grey occupy almost the whole page; #6a51ec belongs to actions, underlined links and small icons, not full-width brand panels. Mint is a small contextual action and yellow a phrase-sized marker.
- A human little drawing accompanies the serious product story: thin dark outlines, white interiors, pale grey organic backing and a small lavender offset. Carry this illustrated wit through the opening and a later section; use an original friendly object-character if there is no mascot.
- Proof feels like a community, not a card catalogue: grey logos in evenly spaced rows, unboxed two-column quotes at 18px/1.5 with small circular portraits, and a framed interface with a 40px browser bar and soft shadow.
- Give the page a personal, signed-note moment: 13.6px/1.5 monospace prose inside a 2px grey outline with 6px corners, 48px padding and a slightly skewed pale sheet behind it. Its content can be a practical product promise rather than a company manifesto.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Violet | `#6a51ec` | `--color-accent` | action, link, accent | Primary buttons, underlined links, feature icons and active indicators. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter marker | `#fff2cc` | `--color-marker` | background | Visible phrase highlight made with rgba(255,201,51,0.25) over white. |
| Faint lavender | `#f2f0ff` | `--color-step-edge` | border | Visible setup-step rule made with rgba(149,128,255,0.12) over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep green ink | `#242925` | `--color-ink` | text | Display headlines, navigation and FAQ questions. |
| Heading charcoal | `#353b37` | `--color-heading` | text | Section headings, emphasized copy and secondary-action text. |
| Body grey | `#4e5551` | `--color-body` | text | Paragraphs, captions and footer links. |
| Pencil grey | `#969c98` | `--color-muted` | border, accent | Signed-note outline and muted small graphic details. |
| Dividing grey | `#dce0dd` | `--color-rule` | border, background | Fine separators, progress tracks and compact closing band. |
| Transparent charcoal edge | `#e9e9e9` | `--color-browser-edge` | border | Visible toolbar hairline; rgba(31,33,38,0.1) over white. |
| Button grey | `#eceeed` | `--color-soft` | surface, border | Secondary buttons, browser toolbar and unselected pricing edges. |
| Pale green-grey | `#f4f6f5` | `--color-wash` | surface, background | Footer, illustration backing, open FAQ rows, selected feature panels and utility pills. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page ground, interface framing and reversed primary-action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing toggles and feature-detail links | Mint highlight | `#80ffd5` | `--color-mint` | action | Small annual-billing and deeper-feature pills. |
| pricing selectors | Lavender edge | `#aa99ff` | `--color-selected` | border | Selected plan border. |

## Typography

- **-apple-system** — All marketing headlines, prose, navigation and actions. Familiar system grotesk with a compact, bold headline cut and open regular text. Font stack: "-apple-system", system-ui, sw, Helvetica, Arial, sans-serif.
- **jb** — Personal signed-note prose. Small, evenly spaced technical lettering used as a personal letter rather than a terminal. If unavailable, use **JetBrains Mono**. Use weight 400 at 13.6px; retain the relaxed 1.5 line height. Font stack: "jb", "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | -apple-system | 700 | 56px | 0.95 | -0.025em | Primary page promise; wrap into compact, intentional lines. |
| heading-lg | -apple-system | 700 | 40px | 0.95 | -0.015em | Section leads and spacious closing calls. |
| heading | -apple-system | 700 | 24px | 1.25 | normal | Benefit headings and capability titles. |
| bridge-copy | -apple-system | 400 | 23.2px | 1.5 | -0.01em | A short full-width narrative bridge between product proof and benefits. |
| body | -apple-system | 400 | 18px | 1.5 | normal | Default paragraphs and testimonials. |
| hero-body | -apple-system | 400 | 18px | 1.6 | normal | Opening support copy. |
| text-link | -apple-system | 600 | 18px | 1.5 | normal | Underlined inline and capability links; also small setup headings in charcoal. |
| faq-question | -apple-system | 700 | 18px | 1.25 | normal | Expandable question summaries. |
| selector-copy | -apple-system | 400 | 15.2px | 1.6 | normal | Expanded feature-selector explanation. |
| small-body | -apple-system | 400 | 14.4px | 1.5 | normal | Setup explanations and footer description. |
| footer-link | -apple-system | 400 | 14.4px | 1.4 | normal | Compact footer navigation. |
| small-heading | -apple-system | 600 | 14.4px | 1.5 | normal | Footer column labels. |
| caption | -apple-system | 500 | 13.6px | 1.4 | normal | Quote attribution, step labels and reassurance captions. |
| letter | jb | 400 | 13.6px | 1.5 | normal | Personal, signed statement panel. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | -apple-system | 600 | 32px | 1 | normal | Monthly cost inside selectable plan rows. |
| editorial and feature pages | band-heading | -apple-system | 700 | 24px | 1.2 | -0.015em | Compact closing-band lead. |
| editorial and feature pages | band-support | -apple-system | 400 | 24px | 1.2 | -0.015em | Second line beneath the compact closing lead. |

**Notes:**

- Headlines are bold but not oversized: the largest size is 56px, and tight 0.95 line height creates the characteristic compact stack.
- Negative tracking belongs to display and major section headings; body, controls and small labels retain normal tracking.
- Keep paragraphs readable rather than typographically precious: default 18px/1.5, with 18px/1.6 in the opening. Emphasis is semibold, not a new display face.
- Eyebrows are not a universal section device. Small sentence-case step labels and quote attributions use the caption recipe.
- Control-specific CSS overrides the related prose or caption recipe: navigation is 16px weight 500, main buttons 18px weight 500, utility pills 13.6px weight 500, each with normal line height and normal tracking.

## Layout

**Density:** Airy section spacing around compact, readable content; most of the page remains white rather than being divided into colored cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small action clusters and icon spacing. |
| 10.8px | Declared utility-pill padding. |
| 12px | Main action gap, FAQ answer offset and setup-rule inset. |
| 19.2px | Paragraph separation and heading top padding. |
| 24px | Panel padding and ordinary grid gaps. |
| 32px | General grid gutters and opening action separation. |
| 48px | Hero split gap, quote-column gutter, letter padding and preview offset. |
| 64px | Setup-column gutters and capability-grid separation. |
| 72px | Recurring section separation, header top margin and footer padding. |
| 96px | Separation before the compact closing band. |

### Containers and grids

- **Main column**: max width 880px. Centered desktop rail shared by navigation, opening, interface proof, grids and footer. At 1440px the margins are 280px.
- **Reading column**: max width 704px. Paragraph width ceiling within wider sections; editorial chapters use a centered 736px outer rail.
- **Question column**: max width 736px. Narrower FAQ list, with the active summary background extending 12px to the left of the text.
- **Hero split**: 2 columns · gap 48px. 2.2fr text beside 1fr illustration, vertically centered.
- **Quote and benefit grid**: 2 columns · gap 48px. Two 416px columns inside the main rail, with no enclosing cards.
- **Setup grid**: 3 columns · gap 64px. Three approximately 251px columns, each marked by a faint left rule.
- **Logo grid**: 4 columns · gap 68px. 160px-wide logo slots, centered visually, usually 64px tall.
- **Capability grid** (only for feature catalogue pages): 2 columns · gap 64px. Two 408px columns with small icons, headings, explanatory text and links.
- **Pricing split** (only for pricing pages): 2 columns · gap 32px. A 500px selector column beside a 348px inclusion panel.

## Corner radius

| Element | Radius |
| --- | --- |
| Main buttons and small panels | 6px |
| Utility pills | 24px |
| Browser frame and selected feature | 12px |
| Feature media stage | 14px |
| Portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Browser elevation | `rgba(31, 33, 38, 0.08) 0px 0px 0px 1px, rgba(31, 33, 38, 0.12) 0px 14px 40px 0px` | Only the main interface demonstration and its smaller feature variant. |

### Surfaces

#### Canvas · level 0

**Use:** Main marketing background.

**CSS:** `background: #ffffff; color: #4e5551`

#### Soft panel · level 1

**Use:** Open FAQ summary, expanded feature item and supporting information.

**CSS:** `background: #f4f6f5; border-radius: 6px`

**Observed:** The treatment groups a useful piece of information, not every paragraph. Feature-selector panels have 12px corners; the media stage uses 14px.

**Transfer:** Keep large story sections unboxed and reserve the wash for active or supporting content.

#### Browser frame · level 1

**Use:** Interactive interface proof.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden; box-shadow: rgba(31, 33, 38, 0.08) 0px 0px 0px 1px, rgba(31, 33, 38, 0.12) 0px 14px 40px 0px`

**Observed:** A pale toolbar caps a nearly full-width product image. This is the strongest elevation on the page.

**Transfer:** Frame one legible product view rather than a stack of floating windows.

#### Letter sheet · level 1

**Use:** The personal note device.

**CSS:** `border: 2px solid #969c98; border-radius: 6px; padding: 48px; position: relative`

**Observed:** An independent pale sheet sits slightly askew behind a straight outlined frame; text is arranged in two columns with a 32px gutter.

**Transfer:** Use an inset pseudo-element filled with #f4f6f5, 6px corners and a subtle roughly -2deg rotation behind the content. Keep the outline level.

#### Phrase marker

**Use:** Emphasis on one important phrase.

**CSS:** `background: rgba(255, 201, 51, 0.25); border-radius: 6px; padding: 2px 6.8px`

**Observed:** Looks like a translucent highlighter, not a badge with its own message.

**Transfer:** Highlight a factual condition or useful distinction sparingly.

#### Footer field · level 0

**Use:** Full-width final navigation area.

**CSS:** `background: #f4f6f5; padding: 72px 0px`

**Observed:** Five uneven columns sit within the main rail: a wider topical list, three narrower groups, and a wider brand/contact description.

**Transfer:** Keep the footer light and information-rich, with short sentence-case group names.

#### Compact closing band · level 0

**Only for:** editorial and feature pages

**Use:** A lower-density alternative to the illustrated closing call.

**CSS:** `background: #dce0dd; padding: 24px 0px`

**Observed:** A 106px band has a bold lead and regular second line at left, plus two compact action pills at right.

**Transfer:** Use after an explanatory page with sufficient product detail already established.

## Components

### Navigation trigger

**Use:** Desktop primary navigation.

**CSS:** `display: inline-flex; align-items: center; gap: 5.6px; padding: 10px; color: #242925; background: none; font-family: -apple-system, system-ui, sw, Helvetica, Arial, sans-serif; font-size: 16px; font-weight: 500; line-height: normal; letter-spacing: normal`

**Text style:** `body` — -apple-system 400 · 18px/1.5

**Observed:** A small downward chevron follows expandable items. The header places a compact wordmark left, menu center, and compact conversion/sign-in pills right.

**States:** Declared: hover color hsl(250, 100%, 80%); focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Primary button

**Use:** Main conversion action in openings, action breaks and closing calls.

**CSS:** `background: #6a51ec; color: #ffffff; border-radius: 6px; padding: 16px 24px; height: 54px; box-sizing: border-box; font-family: -apple-system, system-ui, sw, Helvetica, Arial, sans-serif; font-size: 18px; font-weight: 500; line-height: normal; letter-spacing: normal`

**Text style:** `body` — -apple-system 400 · 18px/1.5

**Observed:** Text-only rectangular control, paired with a secondary button. The pricing confirmation version spans its selector column.

**States:** Declared: hover background hsl(250, 70%, 45%), color #ffffff; focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Secondary button

**Use:** A lower-commitment exploration path beside conversion.

**CSS:** `background: #eceeed; color: #353b37; border-radius: 6px; padding: 16px 24px; height: 54px; box-sizing: border-box; font-family: -apple-system, system-ui, sw, Helvetica, Arial, sans-serif; font-size: 18px; font-weight: 500; line-height: normal; letter-spacing: normal`

**Text style:** `body` — -apple-system 400 · 18px/1.5

**Observed:** Same scale as Primary button, with no heavy border or icon. It also appears in pairs of exploration actions.

**States:** Declared: hover background hsl(140, 8%, 96%), color hsl(140, 6%, 22%); focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Compact primary pill

**Use:** Header conversion and compact closing bands.

**CSS:** `background: #6a51ec; color: #ffffff; border-radius: 24px; padding: 10.8px 12px; font-family: -apple-system, system-ui, sw, Helvetica, Arial, sans-serif; font-size: 13.6px; font-weight: 500; line-height: normal; letter-spacing: normal`

**Text style:** `caption` — -apple-system 500 · 13.6px/1.4

**Observed:** A compact 31px visible pill rather than a scaled-down rectangular button.

**States:** Declared: hover background hsl(250, 70%, 45%); focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Utility pill

**Use:** Sign-in, explanatory links and small contextual actions.

**CSS:** `background: #f4f6f5; color: #4e5551; border-radius: 24px; padding: 10.8px 12px; font-family: -apple-system, system-ui, sw, Helvetica, Arial, sans-serif; font-size: 13.6px; font-weight: 500; line-height: normal; letter-spacing: normal`

**Text style:** `caption` — -apple-system 500 · 13.6px/1.4

**Observed:** A quiet text tag. Scoped mint variants identify annual billing or a deeper feature explanation; those can include a small right arrow.

**States:** Declared: hover background hsl(140, 6%, 93%); focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Inline link

**Use:** Specific explanations inside prose and capability blocks.

**CSS:** `color: #6a51ec; text-decoration: underline`

**Text style:** `text-link` — -apple-system 600 · 18px/1.5

**Observed:** Descriptive anchor text flows naturally in a sentence; it is not a trailing generic learn-more on every paragraph.

**States:** Declared: hover color and text-decoration-color hsl(140, 6%, 22%); focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### FAQ summary

**Use:** Objection-handling accordion.

**CSS:** `background: #f4f6f5; color: #242925; border-radius: 6px; padding: 16px 24px 16px 12px; position: relative`

**Text style:** `faq-question` — -apple-system 700 · 18px/1.25

**Observed:** Default shown variant is the open row, with an upward chevron at the far right. Closed rows have no fill and a downward chevron. Answers use body copy below, with 12px top space and 32px bottom space; only the first answer is initially visible.

**States:** Declared: focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

### Browser preview

**Use:** Large clickable product demonstration.

**CSS:** `background: #ffffff; border-radius: 12px; overflow: hidden; box-shadow: rgba(31, 33, 38, 0.08) 0px 0px 0px 1px, rgba(31, 33, 38, 0.12) 0px 14px 40px 0px`

**Observed:** 40px toolbar in Button grey with a 1px rgba(31,33,38,0.1) bottom edge, three conventional traffic-light dots of 12px diameter and 7px spacing, and the interface image below. A centered Utility pill follows with 24px separation.

**States:** Declared: hover box-shadow rgba(31,33,38,0.1) 0px 0px 0px 1px, rgba(31,33,38,0.16) 0px 18px 48px; focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

**Transfer:** Use a real interface or an accurate static reconstruction showing one useful workflow.

### Setup step

**Use:** A short, sequential explanation of adoption.

**CSS:** `border-left: 1.5px solid rgba(149, 128, 255, 0.12); padding-left: 12px`

**Text style:** `small-body` — -apple-system 400 · 14.4px/1.5

**Observed:** Caption label, semibold 18px heading, then small-body explanation with inline violet links. Three steps sit side by side without number circles or enclosing cards.

### Personal note

**Use:** A signed, human statement that interrupts the normal marketing rhythm.

**CSS:** `border: 2px solid #969c98; border-radius: 6px; padding: 48px; position: relative`

**Text style:** `letter` — jb 400 · 13.6px/1.5

**Observed:** Two prose columns on the Letter sheet surface, with a linked signature near the end. No oversized title or quotation-mark ornament.

**Transfer:** Write a real point of view or promise in the product team's voice.

### Feature selector

**Use:** Explain related capabilities beside a changing product image.

**CSS:** `background: #f4f6f5; border-radius: 12px; width: 360px`

**Text style:** `selector-copy` — -apple-system 400 · 15.2px/1.6

**Observed:** An expanded item holds a 46px trigger with a 19px icon, a semibold 16.8px label, explanatory copy inset 44.8px to align after the icon, and a 2px progress track. Other items collapse to plain rows with grey icons. The adjacent media stage is 484px wide.

**Transfer:** Make each row demonstrate a distinct useful outcome; preserve a meaningful static selected state.

### Plan option

**Only for:** pricing pages

**Use:** Select a capacity-based subscription.

**CSS:** `display: grid; grid-template-columns: max-content minmax(0px, 1fr); align-items: center; gap: 16px; background: #ffffff; color: #6a51ec; border: 2px solid #aa99ff; border-radius: 6px; padding: 24px 48px 24px 16px`

**Text style:** `price` — -apple-system 600 · 32px/1

**Observed:** Selected variant: price left, smaller capacity label beside it, radio marker at right. Unselected rows use #eceeed edges and Body grey text. A mint annual-billing pill sits beneath the stack, followed by a selected-plan summary and full-width Primary button.

**States:** Declared: focus-visible outline 2px solid hsl(250, 80%, 62%), outline-offset 4px.

## Imagery and graphics

### Friendly diagram illustrations

**Use:** A required humanizing device in the opening and later product storytelling.

**Observed:** Small hand-drawn cats participate in simple charts and product metaphors. Thin dark slightly irregular outlines, white interiors, sparse lavender or mint details, and soft green-grey organic blobs keep the drawings low contrast. Opening art occupies roughly a third of the rail; feature illustrations use roughly 320×240px stages.

**Transfer:** Create an original object-character or friendly abstract helper with the same restrained line quality. Minimum version: a simple useful-object diagram with one expressive detail and an offset lavender backing; retain both the human touch and ample white space.

**Build:** Use an SVG viewBox around 320×240. Place a pale #f4f6f5 irregular ellipse behind the subject. Draw two or three white rounded geometric objects with #353b37 outlines around 1–2px; add a duplicate backing offset about 6px right and 5px down using rgba(106,81,236,0.15). Use sparse dots or short dashes for detail and one small mint or violet accent; no blur or glossy shading.

### Interface demonstrations

**Use:** Primary functional proof, full-width near the opening and smaller within the feature selector.

**Observed:** A light analytics interface has pale violet charts, dense data rows and a dark metric strip. It is shown straight-on inside Browser preview; smaller related views sit in a washed, rounded media stage. There are no dramatic perspective transforms or device mockups.

**Transfer:** Show the new product's real information hierarchy and a believable populated workflow. Keep colors inside the interface subordinate to the violet marketing actions; do not reproduce analytics charts for an unrelated product.

### Community proof

**Use:** Customer-logo rows and testimonial sections.

**Observed:** Logos are reduced to a consistent grey, contained rather than stretched, in regular 160×64px slots. Portraits are small circular photographs with natural mixed lighting, followed by unboxed text and discreet attribution. Closing calls replace photography with three overlapping illustrated characters.

**Transfer:** Use genuine identities and permissioned logos. Keep photography modest and contextual rather than turning quotes into glossy campaign cards.

### Technical flow diagrams

**Only for:** technical feature explainers

**Use:** Make a complex process understandable after the introductory benefits.

**Observed:** Full-rail white-backed flow diagrams mix thin arrow connectors, simple boxes, dark circular process symbols, small mono annotations and occasional tiny character drawings. One diagram is restrained black-and-white with flags; another uses brightly differentiated cyan, pink and violet node bodies and offset grey shadows.

**Transfer:** Map the new product's actual process. Use labeled nodes and legible arrows; reserve brighter color for distinguishing process stages, not page-wide decoration.

**Build:** Construct a semantic SVG flowchart on white, up to 880px wide. Use vertical and horizontal paths with arrowheads, white label headers, rounded colored node bodies and a small grey backing offset down-right. Keep explanations next to nodes rather than as a distant legend. Choose only the few stage colors necessary for the new process.

### Icons

**Observed:** Small, lightly drawn technical icons use violet for capabilities and grey for inactive selector rows. Feature icons are generally 32px high; selector icons are 19px. Navigation chevrons are 14×9px with 1.7px round strokes. Avoid solid heavy icon tiles.

**Transfer:** Choose a consistent thin-outline set with round ends, using a single violet mark above a capability title and compact muted icons in control rows.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** White canvas behind all layers. The centered 880px header begins 72px below the top, with a 96×43px wordmark, centered text navigation and compact pills. After another 72px comes the Hero split: the left two-thirds contains a small announcement pill, a tight two-line display headline, a regular support line with a semibold continuation, the Primary button and Secondary button separated by 12px, and a small trial/price reassurance line. The right third centers a 260×255px Friendly diagram illustration, not a large framed image. Below is a centered trust caption and four grey logos. Within the first 900px the full headline, support, actions, illustration, proof row and top of the Browser preview are visible; most of the interface extends below the fold.

**Transfer:** For a new product, state one uncomplicated outcome and use the original diagram-character to make its mechanism tangible. If there is no finished interface, create an accurate static workflow view for Browser preview rather than inflating the hero art. Pricing opens with a similar illustrated split and plan explanation; editorial pages replace the right illustration with a small facts column; feature catalogues use a centered multiline promise and logo rows.

**Avoid:** Do not turn this into a full-bleed gradient, a huge floating dashboard above the actions, or a centered headline by default. Do not enlarge the small illustration to compete with the promise.

**Text style:** `display` — -apple-system 700 · 56px/0.95 · tracking -0.025em

### Plain heading and support

**Observed:** Heading-lg leads a left-aligned section on Canvas, followed directly by 18px prose. Headings include 19.2px top and 10px bottom padding; paragraphs usually separate by 19.2px. The narrative bridge instead uses bridge-copy without a heading.

**Transfer:** Explain one idea in a headline and expand it with a specific short paragraph. Use the larger bridge sentence only for a meaningful change of argument.

**Text style:** `heading-lg` — -apple-system 700 · 40px/0.95 · tracking -0.015em

### Illustrated benefit pairs

**Observed:** Two unboxed 416px columns with a 48px gutter; a small Friendly diagram illustration precedes a 24px heading and body copy. A centered exploration-action pair can follow. The feature-catalogue variant alternates text and 320×240px illustrations across successive rows.

**Transfer:** Pair distinct benefits, not two synonymous claims. Alternate sides only for a longer feature narrative.

**Text style:** `heading` — -apple-system 700 · 24px/1.25

### Selectable product chapter

**Observed:** Feature selector occupies 360px on the left of an 880px rail and a washed 484×460px media stage sits right, separated by 36px. One expanded selector is softly filled; the selected explanation and progress track align after the icon.

**Transfer:** Use when several outcomes can each be demonstrated visually. Keep the product view synchronized with the selected explanation.

### Logo and quote proof

**Observed:** A bold section lead and prose introduce a four-column Logo grid. Quotes follow in two unboxed columns with 48px gutters, small circular portraits, 18px body text and caption attributions.

**Transfer:** Let genuine proof accumulate in a calm grid. With limited proof, shorten the section rather than enlarge the logos or invent figures.

### Adoption steps and personal note

**Observed:** A heading and support paragraph introduce three Setup step components with 64px gutters. A compact grey integration-logo array follows. The Personal note then offers a distinctly different, monospace two-column reading texture on Letter sheet.

**Transfer:** Explain the real path to first value, then use the signed-note device wherever a human promise best strengthens the story. These devices need not stay adjacent.

### Questions and next steps

**Observed:** A heading-lg sits above a Question column of FAQ summary components. The first answer is open; others remain plain rows. On technical pages a centered action pair with tiny reassurance captions precedes a short list of specific onward links.

**Transfer:** Use genuine buying or implementation questions, answer the first directly and link to deeper material without repeating whole chapters.

**Text style:** `faq-question` — -apple-system 700 · 18px/1.25

### Illustrated closing call

**Observed:** A 40px compact multiline heading and supporting paragraph occupy roughly two thirds of the rail; Primary button and Secondary button follow. Three overlapping 112×140px character drawings sit at the lower right. This white section leads into Footer field with 48px separation.

**Transfer:** Reaffirm the user outcome in warmer language and reuse the original illustrated family, not a new art direction.

**Text style:** `heading-lg` — -apple-system 700 · 40px/0.95 · tracking -0.015em

### Capability catalogue

**Only for:** feature catalogue pages

**Observed:** A centered heading-lg introduces two 408px columns with 64px gutters. Each unboxed item starts with a small violet icon, then a 24px bold title, body copy and one or two descriptive links. Rows leave substantial breathing room, about 120px between content groups.

**Transfer:** Group by outcomes and keep titles concrete. Let text length vary naturally while aligning related rows.

**Text style:** `heading` — -apple-system 700 · 24px/1.25

### Capacity pricing

**Only for:** pricing pages

**Observed:** Pricing split holds stacked Plan option rows at left and a pale inclusion panel at right. A mint annual switch and quiet more-plans pill sit under the choices. Confirmation below includes the selected capacity, a full-width Primary button and small candid billing terms. Quotes, logos and FAQ provide reassurance afterward.

**Transfer:** Expose the real billing dimension and total selected price. Keep shared inclusions outside the individual selectable rows.

**Text style:** `price` — -apple-system 600 · 32px/1

### Evidence-led feature explanation

**Only for:** technical feature explainers

**Observed:** An illustrated split opening leads into a simple four-column comparison table with 1px grey horizontal rules, followed by icon-led explanations and white-backed Technical flow diagrams. Body prose alternates with diagrams instead of enclosing every explanation in a card.

**Transfer:** Explain the mechanism after the reader understands why it matters. Use a table only when the differences can be stated truthfully and briefly.

### Compact close and footer

**Only for:** editorial and feature pages

**Observed:** Compact closing band uses a two-line 24px lead/support combination at left and utility-sized actions right. Footer field begins immediately below, with five text-led columns, underlined violet contextual links in the final description and a small copyright line.

**Transfer:** Use the compact variant when a long explainer has already made the case; keep the shared footer light rather than introducing a dark theme.

**Text style:** `band-heading` — -apple-system 700 · 24px/1.2 · tracking -0.015em

## Page flow

**Storyline:** Plain promise → tangible product or mechanism proof → useful capabilities → community reassurance → practical adoption and objections → a human closing invitation.

### Broad product landing page

1. **Promise** — Illustrated split with compact actions, price reassurance and a small trust-logo strip.
2. **Product demonstration** — Full-rail Browser preview shows the working product.
3. **Capability chapters** — A narrative bridge, illustrated benefit pairs and a selectable demonstration.
4. **Social proof** — A larger muted logo array and unboxed portrait quotes.
5. **Adoption** — Short setup steps, integrations and a Personal note.
6. **Objection handling** — A narrow FAQ with one answer open.
7. **Closing call** — Spacious illustrated invitation followed by the light five-column footer.

**Transfer:** Use this as the default landing-page language. Adjust the number and order of proof blocks to the new product rather than reproducing every section.

### Subscription decision page

1. **Promise** — Plain pricing promise with a small friendly illustration.
2. **Pricing** — Capacity options, shared inclusions and a clear selected-plan confirmation.
3. **Reassurance** — Short quotes, candid billing explanation and muted customer logos.
4. **Objection handling** — Questions about trial, cancellation and limits.
5. **Closing call** — Spacious illustrated call and shared footer.

**Transfer:** Make billing understandable before asking for commitment; carry the same playful drawing language into the decision.

### Company and point-of-view page

1. **Positioning** — A conviction-led headline and prose with a small facts sidebar.
2. **Social proof** — A restrained customer-logo array.
3. **Origin story** — Narrow reading column with a small group illustration and linked personal sign-off.
4. **Credibility** — Quotes and editorial chapters explaining how the organization operates.
5. **Closing call** — Contact links, Compact closing band and shared footer.

**Transfer:** Tell an honest organizational story in the reading-column variant; keep facts small rather than turning them into giant metrics.

### Technical differentiator explainer

1. **Promise** — Illustrated split states a concrete protection or benefit.
2. **Comparison** — Plain ruled table makes the distinction inspectable.
3. **Mechanism** — Icon-led explanations, prose and two substantial process diagrams.
4. **Reassurance** — Muted logos and technical FAQ.
5. **Next steps** — Action pair, descriptive onward links, Compact closing band and shared footer.

**Transfer:** Use diagrams to make the new mechanism legible and keep specialized colors confined to process nodes.

### Capability overview

1. **Positioning** — Centered compact headline and prose with two rows of grey logos.
2. **Capability chapters** — Alternating illustrated benefits ending in a small browser demonstration.
3. **Action break** — Centered conversion/exploration pair with three small reassurance captions.
4. **Capability catalogue** — Unboxed two-column grid of small violet icons, titles, paragraphs and links.
5. **Objection handling** — A support prompt and expandable questions.
6. **Closing call** — Compact closing band and shared footer.

**Transfer:** Use the centered opening only for a broad capability catalogue, and maintain the distinction between illustrated lead benefits and quieter detailed items.

## Writing

Forthright, warm and a little opinionated. Benefits are described through ordinary tasks and specific product behavior; ethical convictions are expressed as practical choices rather than corporate mission language.

**Do not copy:** Do not reuse Fathom's name, mascot artwork, customer logos, personal names, quotes, prices, adoption figures, legal-compliance claims or independent-funding claims. Replace all examples with facts and assets appropriate to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. The team uses we and our when explaining decisions; the product is named when clarity matters.
- **Rhythm:** Short sentence-case headings, often four to ten words, followed by conversational paragraphs of two to four sentences. Contractions, occasional parentheses and plain-language contrasts keep longer explanations human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A concrete outcome, often framed as removing a familiar annoyance. | 4–10 words | “Analytics without the cookies”<br>“Simple and sustainable pricing” |
| Supporting line | Describe what the user can see or do before naming the underlying principle. | One or two sentences | “See where visitors come from, which pages they read, and what converts.” |
| Capability heading | Verb-led task or a crisp contrast; no abstract feature-category jargon. | 4–10 words | “Save the filters you use every week”<br>“See humans, not bots” |
| Primary action | Short literal commitment, paired with an equally literal exploration path. | 3–5 words | “Start free trial”<br>“View a live demo” |
| FAQ answer | Answer yes or no first, then explain the practical consequences without evasion. | One short paragraph | “Yes. Every plan includes Data Isolation, including the smallest. It’s enabled by default.” |
| Personal conviction | Plain first-person statement with a mildly defiant human phrase. | A short heading or several direct sentences | “We’re happily small tech” |

**Words and phrasing to use:** easy to use; your website; get started; without; we built; real people; cancel anytime; if you get stuck; here’s why

**Avoid:** revolutionary ecosystem; unlock unprecedented potential; enterprise transformation journey; best-in-class synergy; frictionless magic; vague AI superlatives

**Rules:**

- Lead with the job someone needs to do; explain the mechanism immediately after the benefit.
- Use contrasts sparingly and concretely: what the product does versus the nuisance it removes.
- Place candid conditions near actions, not only in legal text.
- Make links descriptive enough to explain where they lead.
- Let warmth come from contractions, helpful specifics and a personal point of view, not a stream of jokes.

## Do's and Don'ts

### Do

- Keep the default content rail at 880px, with narrower 704px prose and roughly 736px FAQs.
- Use 56px/0.95 bold display type with -0.025em tracking and 40px/0.95 section heads.
- Pair the violet conversion action with a grey exploration action at a 12px gap.
- Keep major section separation around 72px while retaining the smaller 19.2px paragraph rhythm.
- Include original low-contrast line-art wit in both the opening and later storytelling.
- Let the interface demonstration carry the strongest shadow and the largest visual footprint.
- Preserve the signed monospace note as a human change of texture.
- End with a pale green-grey footer and compact sentence-case link groups.

### Don't

- Do not substitute saturated violet section backgrounds for the predominantly white canvas.
- Do not give full-size action buttons pill corners; their measured corners are 6px.
- Do not use the small utility-pill typography for the main conversion pair.
- Do not box every testimonial and capability in rounded elevated cards.
- Do not turn the small facts sidebar into enormous display numerals.
- Do not use monospace for ordinary body copy, navigation or all feature headings.
- Do not color customer-logo grids in their original competing brand palettes.
- Do not make the faint setup rules dark enough to read as heavy dividers.

## Motion and responsive

### Motion

**Observed:**

- Declared button background transitions are 0.2s; compact pills transition background and color over 0.2s.
- Declared inline links transition color and text-decoration-color over 0.2s.
- Expanded feature-panel background uses 0.25s cubic-bezier(.22, .8, .24, 1). A progress track and selected/closed feature states are present.
- FAQ rows use expanded and collapsed states with directional chevrons.

**Transfer:**

- Keep motion tied to the small controls, link feedback and synchronized feature demonstration; do not animate the entire reading column.
- Maintain a useful selected feature view even when automatic progression is absent.

**Unknown:**

- Automatic feature-cycle timing, progress duration and animation playback behavior are not established.

### Responsive

**Observed:**

- Desktop composition uses an 880px maximum rail. CSS declares breakpoints including 600px, 704px, 832px and 980px; a separate desktop header is marked for hiding on mobile.

**Transfer:**

- Recommended narrow-screen adaptation: stack hero copy before its small illustration, preserve action order and the distinction between 6px buttons and 24px pills.
- Recommended narrow-screen adaptation: reduce multi-column proof, setup and catalogue grids to a single reading sequence; place each selected feature view beside or directly after its explanation rather than leaving a detached media stage.

**Unknown:**

- Exact mobile typography, container padding, navigation interaction and breakpoint-specific layout changes are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
