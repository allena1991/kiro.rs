# Hims — larger than life reassurance

## Overview

An expansive, human-facing product style that makes an intimate service feel approachable and tangible. White and black chapters alternate with mint, blue and lavender light, tightly tracked geometric sans typography, and glossy product imagery. Hand-held devices, studio portraits and rounded editorial mosaics give the sparse composition a physical warmth.

### Essentials

- Reassurance is written at billboard scale: medium-weight geometric sans, 81px opening headlines with -0.0575em tracking, 220px chapter titles and 85px narrative paragraphs.
- The opening is a product portrait, not a dashboard grid: a centered two-line purple promise above a hand-held device, inside a white 45px-radius stage inset 64px from the page edges.
- Conversion stays small while the story gets big: a white 54px-high pill with 52px corners, black icon and 14px label remains at the upper right.
- Color lives in light and letterforms: white and black dominate the page canvas; mint-to-blue gradients, a purple headline and pastel gradient prose supply the chromatic accents rather than solid saturated section fills.
- Products are touched and inhabited: photoreal hands and upright devices sit in front of soft colored light; rounded media mosaics connect the interface to people and physical materials. Use a real object-in-hand photograph if there is no screen-based product.
- Chapters have tactile emblems and monumental names: a 372px white rounded-square icon tile with diffuse shadow precedes a centered 220px title; giant 280px pastel words also pass behind the main object.
- Proof feels like encouragement: a compact circular percentage ring, centered explanation and brief green-gradient response punctuate the oversized narrative. Use a truthful progress or outcome measure rather than decorative numbers.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Promise purple | `#5d48db` | `--color-purple` | text, accent | Opening promise; do not spread it into every action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#53aaff` | `--color-blue-light` | text, accent | Top of blue-to-black narrative lettering. |
| Encouragement green | `#3fd194` | `--color-proof-green` | text, accent | Bright end of the short proof-response gradient. |
| Denim blue | `#3577bf` | `--color-blue-deep` | text, accent | Middle of blue-to-black narrative lettering. |
| Narrative mint | `#4fd8ab` | `--color-chapter-mint` | text | Start of mint-blue-lavender narrative lettering. |
| Narrative blue | `#5ea1e7` | `--color-chapter-blue` | text | Middle of mint-blue-lavender narrative lettering. |
| Encouragement teal | `#2fa59e` | `--color-proof-teal` | text, accent | Deep end of the short proof-response gradient. |
| Narrative lavender | `#8375d0` | `--color-chapter-lavender` | text | End of mint-blue-lavender narrative lettering. |
| Cool mint | `#bae1dc` | `--color-mint-cool` | text, accent | Second stop of giant pastel word lettering. |
| Pale mint | `#c0e3d8` | `--color-mint-light` | text, accent | First stop of giant pastel word lettering. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Default canvas, raised panels, icon tiles, conversion pill and reversed text. |
| Black | `#000000` | `--color-ink` | text, background | Primary text on white; full dark chapters and footer. |
| Deep charcoal | `#292526` | `--color-charcoal-end` | surface | Right side of dark feature-panel gradient. |
| Soft black | `#2e2e2e` | `--color-secondary` | text | Centered proof explanation; visible result of 82% black on white. |
| Warm charcoal | `#352f33` | `--color-charcoal-start` | surface | Left side of dark feature-panel gradient. |
| Answer gray | `#8f8f8f` | `--color-muted` | text, link | FAQ answers and their underlined links; visible result of 44% black on white. |
| Hairline gray | `#e0e0e0` | `--color-rule` | border | FAQ row dividers. |
| Ghost gray | `#f0f0f0` | `--color-ghost` | text, surface | Oversized background category words and subtle section seams; a 6% black layer over white has this visible appearance. |

## Typography

- **sofia** — All marketing headlines, explanations, actions and FAQ text. Rounded geometric sans with single-storey forms, broad circular counters and a friendly medium weight. If unavailable, use **DM Sans**. Use 400 and 500; retain the tight display tracking and check line wraps. Font stack: "sofia", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| word-sculpture | sofia | 500 | 280px | 1 | -0.0575em | fixed | Pastel word fragments behind the primary product image. |
| chapter | sofia | 500 | 220px | 1 | -0.0575em | size 15.2778vw | Very short chapter names, black on white or white on black. |
| narrative | sofia | 500 | 85px | 98px | -0.0475em | size 5.90278vw, line height 6.80556vw | Long editorial statements treated as display text; gradient clipped into the letters. |
| stat | sofia | 500 | 84px | 205px | -0.0575em | size 5.83333vw, line height 14.2361vw | Numeral centered within the circular proof graphic. |
| hero | sofia | 500 | 81px | 1.04 | -0.0575em | size 5.625vw | Centered opening promise, normally two short lines. |
| feature-lead | sofia | 500 | 44px | 52px | -0.0475em | size 3.05556vw, line height 3.61111vw | Centered stage introductions and proof explanations. |
| panel-copy | sofia | 500 | 39px | 1.18 | -0.0475em | size 2.70833vw | Narrow centered explanation inside dark feature panels. |
| utility-heading | sofia | 500 | 32px | 1.25 | normal | size 2.22222vw | FAQ section heading. |
| footer-link | sofia | 400 | 24px | 60px | normal | fixed | Large ruled destination links at the top right of the footer. |
| badge-label | sofia | 500 | 20px | 1.15 | -0.0125em | size 1.38889vw | Short labels beneath icons in circular feature badges. |
| question | sofia | 500 | 18px | 24px | normal | size 1.25vw, line height 1.66667vw | FAQ question rows. |
| answer | sofia | 400 | 18px | 30px | normal | size 1.25vw, line height 2.08333vw | FAQ answer paragraphs and inline links. |
| action | sofia | 500 | 14px | 20px | -0.0175em | fixed | Primary pill label. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium weight carries the display hierarchy; size, line break and tracking do the work instead of heavy bold.
- Use -0.0575em tracking for hero, chapter and giant words; narrative and panel paragraphs loosen slightly to -0.0475em.
- Utility text returns to normal tracking and regular-weight answers. The 205px stat line height centers the number in its ring, not in ordinary prose.

## Layout

**Density:** Airy, with viewport-sized product scenes and large editorial pauses contrasted against compact utility rows.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 16px | Answer inset below its question and pill vertical padding. | fixed |
| 22px | Pill horizontal padding. | fixed |
| 32px | Dark panel separation and FAQ row vertical padding. | 2.22222vw |
| 64px | Primary panel and footer side insets. | fixed |
| 90px | Space above chapter titles and below narrow dark-panel copy. | 6.25vw |
| 160px | Editorial block top and left padding. | 11.1111vw |
| 200px | Chapter title to main media-panel separation. | 13.8889vw |
| 250px | Major chapter lead-in and editorial breathing room. | 17.3611vw |

### Containers and grids

- **wide-stage**: max width 1312px · side padding 64px. At 1440px, main media panels and the footer content span the page less two 64px insets; this is a viewport-related stage rather than a fixed maximum container.
- **editorial-measure**: max width 1124px · side padding 160px. Oversized narrative text uses 160px left and 156px right padding at desktop.
- **faq-split**: 2 columns. Section label occupies the left half; a 660px question list sits in the right half within the wide stage.
- **product-and-caption**: 2 columns. A centered upright device stays dominant; a narrow 340px text column sits to its left during explanatory scenes.

## Corner radius

| Element | Radius |
| --- | --- |
| media-panels | 45px |
| conversion-pill | 52px |
| circular-badges | 50% |
| emblem-tile | 74.4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| media-stage | `0px 27px 104px 0px rgba(0,0,0,0.12)` | Large rounded white panels. |
| emblem | `0px 8px 127px 0px rgba(0,0,0,0.11)` | Floating rounded-square chapter emblems. |
| conversion | `0px 8px 30px 0px rgba(0,0,0,0.06)` | White pill against a white canvas. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

#### Black chapter · level 0

**Use:** Immersive feature chapters and the closing footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The entire backdrop reverses, while the small conversion action stays white.

**Transfer:** Use a full chapter reversal to distinguish a deeper product experience, not alternating colors on every small block.

#### Raised media stage · level 1

**Use:** Large product scenes and demonstrations.

**CSS:** `background: #ffffff; border-radius: 45px; box-shadow: 0px 27px 104px 0px rgba(0,0,0,0.12); overflow: hidden`

**Observed:** Inset 64px from each side; the panel can contain several related storytelling scenes.

**Transfer:** Keep the frame continuous across related product details.

#### Warm dark panel · level 1

**Use:** Feature explanations within black chapters.

**CSS:** `background-image: linear-gradient(90deg, #352f33 0px, #292526 100%); border-radius: 45px; color: #ffffff`

**Observed:** A barely perceptible warm horizontal gradient separates the panel from pure black.

**Transfer:** Preserve this tonal separation rather than using a bright accent fill.

#### Blue narrative lettering

**Use:** Display-size explanatory paragraphs on white.

**CSS:** `background-image: linear-gradient(166.14deg, #53aaff 1.38%, #3577bf 38.84%, #000000 74.76%); background-clip: text; -webkit-text-fill-color: transparent`

**Observed:** The top lines begin sky blue and the final lines become black. Other chapters use mint-blue-lavender, lavender-pink on black, or teal-to-black lettering.

**Transfer:** Apply one continuous gradient across a complete paragraph, not a new gradient per line.

#### Mint narrative lettering

**Use:** Encouraging chapter summaries on white.

**CSS:** `background-image: linear-gradient(123.97deg, #4fd8ab 10.62%, #5ea1e7 43.12%, #8375d0 89.61%); background-clip: text; -webkit-text-fill-color: transparent`

**Transfer:** Reserve this more colorful treatment for an optimistic summary.

## Components

### Primary button

**Use:** Persistent main conversion action.

**CSS:** `background: #ffffff; color: #000000; border-radius: 52px; padding: 16px 22px; height: 54px; box-shadow: 0px 8px 30px 0px rgba(0,0,0,0.06)`

**Text style:** `action` — sofia 500 · 14px/20px · tracking -0.0175em

**Observed:** A compact black platform glyph precedes the label with 7px separation. The action sits at the upper right and stays visually consistent over light and dark chapters.

**Transfer:** Use a relevant platform or action symbol; retain the small white pill rather than a wide colored CTA.

### Minimal navigation

**Use:** Page-wide orientation without competing with the product scene.

**CSS:** `display: flex; justify-content: space-between; align-items: center`

**Observed:** A compact wordmark is at the upper left and Primary button at the upper right; no menu row or filled navigation bar is visible. The mark changes to white over black.

**Transfer:** Use the new identity at comparable scale and keep navigation sparse.

### Chapter emblem

**Use:** Tactile introduction to a product capability.

**CSS:** `width: 372px; height: 372px; display: flex; align-items: center; justify-content: center; background: #ffffff; border-radius: 74.4px; box-shadow: 0px 8px 127px 0px rgba(0,0,0,0.11)`

**Observed:** A solid black category pictogram occupies the center, with ample white around it; the tile precedes an enormous chapter name.

**Transfer:** Choose a single familiar silhouette for each capability.

### Feature badge

**Use:** A short family of related interaction modes.

**CSS:** `width: 116px; height: 116px; background: #ffffff; color: #000000; border-radius: 50%; text-align: center; padding-top: 71px; box-sizing: border-box`

**Text style:** `badge-label` — sofia 500 · 20px/1.15 · tracking -0.0125em

**Observed:** Three white circles overlap horizontally above centered panel copy. Each contains a black solid icon above a brief label; the front circles carry stronger shadows.

**Transfer:** Keep the family small and semantically parallel; do not turn these into a general feature grid.

### FAQ row

**Use:** Practical objection handling near the ending.

**CSS:** `padding: 32px 0px; border-bottom: 1px solid #e0e0e0; color: #000000`

**Text style:** `question` — sofia 500 · 18px/24px

**Observed:** Question and small chevron align on one row. The first answer is expanded; its gray paragraph sits 16px below and includes an underlined inline link.

**Transfer:** Use actual customer questions, keeping the list on the right half of the section.

### Proof ring

**Use:** A concise quantitative problem or outcome.

**CSS:** `width: 205px; height: 205px; position: relative; text-align: center`

**Text style:** `stat` — sofia 500 · 84px/205px · tracking -0.0575em

**Observed:** A gray circular track is partly traced by a green-to-teal arc. A smaller percent sign accompanies the centered black number. Explanation and a short green-gradient response sit below.

**Transfer:** Build the ring in SVG and map the arc to the real measure; follow it with a human interpretation.

### Footer destination

**Use:** Small set of related product destinations.

**CSS:** `width: 240px; border-top: 1px solid #ffffff; color: #ffffff`

**Text style:** `footer-link` — sofia 400 · 24px/60px

**Observed:** Text on the left, thin white right arrow on the right. Stacked rows share hairlines and the final row closes with a bottom rule.

**Transfer:** Use a few high-value destinations, not a dense sitemap.

### Editorial statement

**Use:** Long-form benefit summary with the visual force of a headline.

**CSS:** `padding: 160px 156px 0px 160px`

**Text style:** `narrative` — sofia 500 · 85px/98px · tracking -0.0475em

**Observed:** A single left-aligned text block spans 1124px at desktop; Blue narrative lettering is the default. Statements often end with a short plainspoken resolution.

**Transfer:** Write several linked short sentences rather than a conventional headline over small body copy.

## Imagery and graphics

### Human-held product portrait

**Use:** Opening and recurring product demonstrations.

**Observed:** An upright smartphone with a dark burgundy edge is held by a realistically lit hand, the forearm entering from below. It is centered against white or muted plum, with warm skin highlights and a crisp, readable screen; the opening adds diffuse pink-lavender light.

**Transfer:** Photograph the new product in a real hand with similar intimacy and clear silhouette. For software, use one clean interface in a realistic device; if device photography is unavailable, a sharply rendered device and separate hand-free product scene is the minimum.

**Build:** Place the isolated portrait above two large overlapping radial gradients in a rounded overflow-hidden stage. Use translucent pink and lavender at roughly 20–30% alpha, fade to transparent at about 70% radius, and position both behind the lower half of the headline and upper device. Keep the edge white and the light soft, without a visible gradient boundary.

### Rounded editorial mosaic

**Use:** Immersive introductions to a breadth of content or products.

**Observed:** A full-width collage of tall rounded cards combines presenter portraits, close-up materials, simple graphic cards and glossy three-dimensional objects. A second variant mixes large skin portraits and packshots on mint, cream, amber and watery turquoise sets. The central held device overlaps the collage.

**Transfer:** Combine real use, product details and one abstract material image in a coherent rounded mosaic. Let some images run beyond the viewport and vary tile span; avoid making every tile a captioned card.

**Build:** Use a multi-column CSS grid with 30px rounded clipping and roughly 30px gutters at 1440px. Let one portrait span two columns or rows and fill the other cells with isolated objects and tactile details. Place the main product portrait on a separate centered foreground layer.

### Pastel word sculpture

**Use:** Oversized verbal motif behind the opening product.

**Observed:** Enormous mint and pale-blue words stretch across the stage and sometimes extend beyond its edges; the physical product remains in front, interrupting the letters.

**Transfer:** Break a short product promise into a few simple fragments and preserve the layered scale contrast.

**Build:** Set word-sculpture type in an overflow-hidden layer behind the product; apply linear-gradient(166.14deg, #c0e3d8 0px, #bae1dc 100%) clipped to text. Alternate edge alignment between fragments; keep foreground object opaque.

### Circular encouragement graphic

**Use:** A brief proof interlude.

**Observed:** A thin gray ring, green-to-teal progress arc and black percentage are followed by a centered explanation and a short gradient response.

**Transfer:** Use a documented proportion or completion measure; the ring should explain the point, not imply unsupported success.

**Build:** Use a 205px square SVG with two concentric stroked circles, rounded arc ends and a green-to-teal stroke gradient. Put stat type at its center and apply the same two-color gradient at 243.6deg to the short response below.

### Icons

**Observed:** Mostly solid black silhouettes rather than outlined icon sets. Circular badges use approximately 32×36px pictograms; utility chevrons occupy 24px boxes; the pill uses a 17×20px platform glyph. Footer arrows are white and visually lighter.

**Transfer:** Use recognizable filled category symbols, retaining slender arrows only for navigation and disclosure.

## Section recipes

How recurring sections are built.

### First screen: Human product opening

**Observed:** A sparse wordmark-and-action row sits above a rounded white Raised media stage beginning 100px below the top, inset 64px. The centered purple hero promise occupies two lines near the upper quarter, at 81px/1.04. Beneath it, a hand-held upright phone rises from the bottom over pink-lavender light. Within the first 900px the navigation, headline and upper portion of the phone and hand are visible; the forearm and later giant word fragments continue below. There is no supporting paragraph or second action in this first screen. Back-to-front layers are white stage, diffuse light, headline and later pastel words, then the physical device portrait.

**Transfer:** Use one strong product-in-use portrait and a short two-line promise. Without the original media, combine a clean rendered object with soft light and an authentic use photograph elsewhere. A focused feature page can retain this same hierarchy while swapping the interface and promise.

**Avoid:** Do not compress the whole device into a small hero card beside a paragraph, or replace the intimate product portrait with a generic dashboard thumbnail.

**Text style:** `hero` — sofia 500 · 81px/1.04 · tracking -0.0575em

### Monumental capability introduction

**Observed:** Chapter emblem is centered above a chapter title with 90px top spacing. The main Raised media stage begins after a further 200px. White chapters use black names; Black chapter reverses the name to white.

**Transfer:** Use a one- or two-word capability name, letting title and icon establish a memorable chapter marker.

**Text style:** `chapter` — sofia 500 · 220px/1 · tracking -0.0575em

### Product detail sequence

**Observed:** A centered hand-held device dominates a white stage, while a narrow left-side explanatory passage changes across related interface views. A Rounded editorial mosaic can precede the isolated device scene.

**Transfer:** Show a small set of meaningful product states and explain one benefit at a time; retain visual continuity between states.

### Encouraging proof pause

**Observed:** Proof ring is centered high within a Raised media stage, followed by a 478px-wide feature-lead explanation and a short green-gradient response; vivid mosaic content enters below.

**Transfer:** Interrupt a visual product chapter with a single interpretable metric, then return to the product rather than building an analytics dashboard.

**Text style:** `feature-lead` — sofia 500 · 44px/52px · tracking -0.0475em

### Dark interaction chapter

**Observed:** Black chapter supports a muted plum product stage, then Warm dark panel blocks separated by 32px. A centered trio of Feature badge circles precedes narrow 418px panel-copy; another panel shows an enlarged messaging interface.

**Transfer:** Use this variant for a more intimate or supported product experience, keeping the screen bright against warm charcoal.

**Text style:** `panel-copy` — sofia 500 · 39px/1.18 · tracking -0.0475em

### Display prose interlude

**Observed:** Editorial statement follows major media scenes. It uses 85px type with 98px line height, 160px left/top padding and a continuous text gradient. Blue-to-black, mint-to-lavender, lavender-pink on black and teal-to-black variants differentiate chapters.

**Transfer:** Give a substantial product benefit the scale normally reserved for a headline. Choose the gradient according to its chapter background.

**Text style:** `narrative` — sofia 500 · 85px/98px · tracking -0.0475em

### Practical ending and sparse footer

**Observed:** A final teal-to-black display paragraph gives way to a white FAQ section with a 32px heading at left and three hairline-separated questions at right. After generous white space comes a 585px black footer: white identity at upper left, ruled Footer destination links at upper right, legal utilities low left and a small verification badge low right.

**Transfer:** End with a confident benefit summary, practical questions and a sparse destination footer. Retain the strong white-to-black ending rather than adding an unrelated oversized CTA banner.

**Text style:** `utility-heading` — sofia 500 · 32px/1.25

## Page flow

**Storyline:** Human promise → tangible product encounter → capability chapters → concise proof → detailed product use → reassuring summaries → practical questions → sparse destination footer.

### An immersive product introduction that makes a complex service feel simple and personal

1. **Promise** — Short two-line purple headline, one small persistent conversion pill and a human-held product portrait.
2. **Product orientation** — Giant pastel word fragments behind the device, followed by an oversized gradient-lettered benefit statement.
3. **Capability chapters** — Floating category emblems and monumental names introduce distinct parts of the experience.
4. **Quantified proof** — A centered circular measure turns an abstract problem into a brief encouraging statement.
5. **Product demonstration** — Rounded media mosaics resolve into a centered device with successive explanatory passages; a dark chapter gives interaction modes their own treatment.
6. **Reassurance** — Large gradient paragraphs translate functionality into confidence and convenience.
7. **Objection handling** — A restrained split FAQ answers practical access and use questions.
8. **Closing navigation** — A sparse black footer offers related destinations and legal utilities while the compact conversion action remains familiar.

**Transfer:** Borrow the alternation of immersive product scenes and very large plainspoken explanation. Choose chapters and their order for the new product rather than reproducing the length or subject categories.

## Writing

Confident and conversational, with the warmth of someone making an intimidating process ordinary. Functional explanations are direct; reassurance uses contractions, repetition and a little everyday wit.

**Do not copy:** Do not reuse Hims/Hers names, wordmarks, interface assets, provider identities, proprietary imagery, medical claims, outcome percentages or testimonials. Replace them with the new product's identity and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. We and our describe the people and product helping them; inclusive let's appears in encouragement.
- **Rhythm:** Short balanced headline clauses; longer display paragraphs made from short sentences and fragments. Questions are quickly answered, and repeated openings create a friendly spoken cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Two balanced clauses repeat a key word and introduce a contrast. | 4–7 words | “Total care. Totally different.” |
| Chapter name | Plain nouns, not technical feature descriptions. | 1–2 words | “Programs”<br>“Member Shop” |
| Reassuring explanation | Name the concern, then answer it in direct everyday language. | Several short sentences within one display paragraph | “Got questions? Get answers. Even at 3am. Even if it’s awkward.” |
| Encouraging resolution | A brief shared commitment closes the argument. | 3–10 words | “Let’s fix that.”<br>“You got this, and we got you. Let’s go.” |
| Primary action | Simple verb plus immediate next step. | 2–3 words | “Download now” |

**Words and phrasing to use:** you; your; simple; goodbye, guesswork; anywhere; let’s; whatever works for you

**Avoid:** disruptive ecosystem; synergistic; revolutionary platform; clinical jargon without explanation; pressure-based urgency

**Rules:**

- Turn a worry into an approachable next step before listing capabilities.
- Use concrete actions such as watch, book, chat or manage instead of abstract platform language.
- Keep factual claims distinct from emotional reassurance, and substantiate any comparative or quantified claim.
- Let one short sentence finish a long display paragraph with a sense of relief.

## Do's and Don'ts

### Do

- Keep the opening promise centered at 81px with medium weight and tight tracking.
- Give major product stages 64px desktop side insets and 45px corners.
- Use 220px chapter names with short noun labels.
- Keep the primary conversion pill white and 54px high across both light and dark chapters.
- Carry narrative gradients across the full text block, including multiple lines.
- Use real skin, hands and tactile object lighting to humanize digital products.
- Preserve the small circular proof treatment alongside larger visual demonstrations.
- Make FAQ answers quieter than questions with regular weight and 30px line height.

### Don't

- Do not use heavy 700-weight display type in place of the measured medium-weight geometry.
- Do not turn the purple headline color into full-page purple backgrounds.
- Do not replace the 45px panel corners with a uniform 8px card system.
- Do not give all text the same negative tracking; utility questions and answers use normal tracking.
- Do not apply bright borders to separate dark panels; use warm charcoal against black.
- Do not scatter drop shadows onto every content block; reserve diffuse elevation for panels, emblems and the conversion pill.
- Do not place long labels under the circular feature icons; their 116px circles suit single words.
- Do not build a dense multi-column footer sitemap where a few 240px ruled destinations will do.

## Motion and responsive

### Motion

**Observed:**

- The visual sequence keeps a centered hand-held device through changing scenes and interface states.
- Declared surface/action transition: transform 0.6s cubic-bezier(0.19, 1, 0.22, 1). No matched keyframe animations.

**Transfer:**

- If using scroll-driven scenes, preserve the device as the visual anchor while the surrounding words, context and benefit copy change.

**Unknown:**

- Exact scroll pin durations, scene interpolation and action hover/focus appearance are not established.

### Responsive

**Observed:**

- A width breakpoint at 750px is declared. Several headline, paragraph and spacing values scale with viewport width.

**Transfer:**

- Retain the opening's centered promise-over-product hierarchy on narrow screens. Reflow the FAQ to heading above list and move explanatory side copy above or below the device; these are adaptation recommendations.
- Keep the narrative display hierarchy while setting readable minimum sizes rather than shrinking all text indefinitely.

**Unknown:**

- Mobile compositions, breakpoint-specific sizes, device scaling and navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
