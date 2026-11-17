# Ploy — inflatable industrial optimism

## Overview

A theatrical, light-first technology style that pairs hard-working condensed headlines with playful inflated objects. Acid yellow, bubblegum pink, powder blue and fresh green interrupt pale gray editorial space, while a charcoal ending gives the page a substantial final act. Cinematic live-action scenes, glossy translucent sculpture and crisp interface panels make automation feel tangible rather than abstract. It suits ambitious software and service products with a strong outcome story and room for spacious, high-impact demonstrations.

### Essentials

- Headlines behave like compressed posters, not ordinary software headings: FK Screamer 700, uppercase, 144px/0.86 for the opening and closing, with 96px and 72px chapter variants.
- The default opening is a film stage with a promise laid over it: a 1376px-wide, 866px-tall media panel, 12px corners, 32px side gutters and 96px top clearance; centered white headline spans up to 1020px, followed by a 384px support line and two pill actions.
- Actions are small capsules against monumental type: 14px semibold Geist labels, 46px main actions and a 12px gap; dark-on-light by default, white primary and outlined secondary over film.
- Color arrives in room-sized slabs rather than scattered decorations: 1392px-wide bands inset 24px with 20px corners, using yellow, pink, blue or green one at a time. Alternate these substantial color fields with pale editorial space; reserve charcoal for the ending and occasional conversion interlude.
- Soft inflated sculpture must interrupt the hard typography: translucent blue, lime, pink and yellow forms sit behind words, replace a visual pause between phrases, or swell into a page-sized object. Without bespoke 3D media, use a carefully lit SVG balloon form with seams and specular highlights, not a flat icon.
- Proof looks like working artifacts: white 12px-radius metric panels on a pink stage, and 4px-radius punched cards with corner dots for audience or quote material. Use one of these artifact devices to make the promise concrete.
- The ending is a second spectacle, not a thin link strip: a charcoal 20px-radius enclosure holds a giant inflated word sculpture, a short contact proposition, a ruled summary-assistant band and five compact link columns. Rebuild the sculpture with the new product's own short word or abstract emblem.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#fffa64` | `--color-yellow` | background, accent, action | Large activity and conversion bands; bright sculptural accents. |
| Fresh green | `#d1f48c` | `--color-green` | background, accent | Process bands, testimonial cards and inflated objects. |
| Balloon pink | `#ffb8fc` | `--color-pink` | background, accent, border | Metric stage, audience panels, inflated sculpture and action focus rings. |
| Powder blue | `#c3dbff` | `--color-blue` | background, accent, text | Gallery bands, inflated objects and accent text inside dark labels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#d1f864` | `--color-lime` | accent, text | Small category accents, bullets and dark capsule lettering; not a replacement for the larger green band. |
| Pale blue paper | `#e7f1ff` | `--color-blue-wash` | surface | Upper title area of strategy cards inside blue gallery bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#212121` | `--color-ink` | text, background, action | Primary text, dark buttons, label capsules and the enclosing footer. |
| Dark raised fill | `#333333` | `--color-dark-raised` | surface | White at 8% over charcoal for summary destination capsules. |
| Dark hairline | `#454545` | `--color-dark-rule` | border | White at 16% over charcoal for footer rules and capsule outlines. |
| Secondary gray | `#5c5c5c` | `--color-muted` | text | Secondary text and navigation, produced by charcoal at 72% over the gray canvas. |
| Caption gray | `#808080` | `--color-caption` | text | Trust captions and secondary metadata, using charcoal at 55% over the gray canvas. |
| Unrevealed headline | `#dbdbdb` | `--color-reveal-gray` | text | Charcoal at 12% on gray, backing the progressive dark fill of statement lettering. |
| Subtle edge | `#e3e3e3` | `--color-rule` | border | Hairlines and card edges, charcoal at 8% on gray; retain rgba(33,33,33,0.08) when backing changes. |
| Pale gray canvas | `#f4f4f4` | `--color-canvas` | background, text | Default page ground and light text on compact dark actions. |
| Paper white | `#ffffff` | `--color-white` | surface, text, action | Cards, question panels and text over cinematic media or charcoal. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Recommended column wash | `#fff9ff` | `--color-pricing-wash` | surface | Pink at 8% over white in the recommended comparison column; its header uses the same hue at 30%. |
| pricing pages | Comparison edge | `#dfdfdf` | `--color-table-rule` | border | Slightly stronger table grid, charcoal at 10% over gray. |
| pricing pages | Explanation gray | `#e5e5e5` | `--color-stone` | background | Neutral explanatory band between pricing cards and comparison detail. |

## Typography

- **FK Screamer** — Poster headlines, chapter labels and monumental calls to action. Extremely condensed, tall, heavy sans with tightly packed uppercase forms. If unavailable, use **Anton**. Use 400 for its heavy single cut; tune line breaks to preserve the narrow poster silhouette. Font stack: "FK Screamer", "Anton", Impact, sans-serif.
- **Geist** — Editorial headings, paragraphs, actions, navigation and visible metrics. Clean contemporary grotesk; semibold headings use strongly negative tracking. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | FK Screamer | 700 | 144px | 0.86 | normal, uppercase | Hero promises, statement reveals and monumental closing calls. |
| display-medium | FK Screamer | 700 | 96px | 0.86 | normal, uppercase | Asymmetric chapter headlines and split phrases around an object. |
| chapter | FK Screamer | 700 | 72px | 0.86 | normal, uppercase | Colored-band headings, audience card names and editorial row labels. |
| metric | Geist | 700 | 72px | 0.86 | normal | Dominant result numeral inside a white proof panel. |
| heading | Geist | 600 | 48px | 1.08 | -0.04em | Audience introductions and conversational section statements. |
| heading-small | Geist | 600 | 36px | 1.08 | -0.04em | Summary-assistant band and compact explanatory headings. |
| card-title | Geist | 600 | 30px | 1.25 | -0.04em | Strategy card titles. |
| subheading | Geist | 600 | 28px | 1.08 | -0.04em | Question headings and the right-hand heading in editorial chapter rows. |
| step-title | Geist | 600 | 22px | 1.08 | -0.04em | Process steps and pricing tier names. |
| feature-title | Geist | 600 | 20.8px | 1.33 | -0.04em | Compact feature group titles inside white horizontal panels. |
| body-large | Geist | 400 | 18px | 1.5 | -0.02em | Longer introductory explanations. |
| centered-support | Geist | 400 | 18px | 1.55 | normal | Centered hero and closing support text, usually muted and up to 640px wide. |
| body | Geist | 400 | 16px | 1.5 | -0.02em | Main paragraphs, feature descriptions and footer links. |
| navigation | Geist | 500 | 15.2px | 1 | -0.01em | Desktop navigation destinations. |
| label | Geist | 600 | 14px | 1.4286 | -0.01em | Dark capsule eyebrows with colored lettering. |
| caption | Geist | 600 | 14px | 20px | normal | Trust captions, summary destination links and footer group labels. |
| button | Geist | 600 | 14px | 1 | -0.01em | Standard navigation and hero action labels. |
| form-button | Geist | 600 | 14px | 20px | -0.005em | Submit capsule inside a URL form. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| detailed feature and pricing pages | editorial-heading | Geist | 600 | 64px | 1.08 | -0.04em | Major explanatory and FAQ introductions. |
| pricing pages | price | Geist | 700 | 48px | 1 | normal | Price or custom-plan designation. |
| testimonial walls | quote | Geist | 400 | 18px | 1.45 | -0.005em | Conversational testimonial text, with inline bold emphasis at 700. |
| pricing pages | table-copy | Geist | 400 | 14px | 20px | normal | Comparison values. |

**Notes:**

- Use the condensed family for spectacle and short categorical names; use Geist for explanations and sentence-case editorial statements. Do not turn all headings into the same family.
- Condensed headlines share 0.86 line height with normal tracking. Geist semibold headings consistently use -0.04em; body copy uses -0.02em and capsule labels -0.01em.
- Preserve purposeful headline line breaks: opening promises form a centered rectangular mass, while chapter phrases can align to opposing edges around a sculptural object.
- The editorial 64px heading belongs to information-heavy feature and pricing pages; 48px is the core conversational heading.

## Layout

**Density:** Airy at section scale, compact inside working artifacts. Large pauses separate poster statements while small gaps organize cards and controls.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Submit icon gap and URL-form inner padding. |
| 12px | Action pairs, destination capsule wrapping and compact navigation actions. |
| 16px | Body stacks and metric-card grid gaps. |
| 20px | Process-step content gaps, testimonial gutters and pricing grid gaps. |
| 24px | Outer band gutters, standard card padding and section-heading-to-support gaps. |
| 28px | Opening headline, support and action stack gaps. |
| 32px | Editorial headline-to-body separation and audience card vertical padding. |
| 40px | Editorial grid gutters and summary-band vertical padding. |
| 48px | Chapter row vertical padding and footer enclosure vertical inset. |
| 64px | Trust-band padding and intro-to-detail separation. |
| 76px | Colored gallery top and bottom padding; footer content group separation. |
| 96px | Large panel horizontal inset and hero top clearance. |
| 128px | Editorial section vertical padding and standard large white panel padding. |
| 160px | Deep stage padding around activity scenes. |

### Containers and grids

- **Editorial container**: max width 1152px · side padding 24px. Centered shared alignment for text chapters, colored-band interiors and footer content.
- **Band enclosure**: max width 1392px · side padding 24px. Nearly full-width colored or dark panel; page background remains visible around its rounded edges.
- **Hero text**: max width 1020px. Centered poster headline over film; support narrows to 384px beneath it.
- **Split editorial grid**: 12 columns · gap 40px. Left label or chapter spans four columns; heading and body span eight. Align repeated rows to the same division.
- **Audience grid**: 2 columns · gap 24px. Sticky introduction on the left, expanded and collapsed punched cards stacked on the right.
- **Proof grid**: 3 columns · gap 16px. Equal white result panels across a colored stage.
- **Gallery rail**: gap 24px. 384px strategy cards or 340px work samples, showing the next item at the right edge rather than squeezing all cards into view.
- **Footer columns**: max width 1152px · 5 columns · gap 32px. Dense link groups below the summary band, followed by a wrapping integrations index and a legal baseline.
- **Pricing grid** (only for pricing pages): max width 1280px · 4 columns · gap 20px. Equal plan cards with aligned prices, features and bottom actions.
- **Testimonial wall** (only for testimonial walls): max width 1280px · 4 columns · gap 20px. Independent vertical card stacks with uneven bottoms and small rotations.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Capsules | 9999px (pill) |
|  | Section enclosures | 20px |
|  | Cinematic media and metric panels | 12px |
|  | Punched cards and white feature strips | 4px |
|  | Strategy cards | 8px |
| pricing pages | Plan cards | 14px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | Result panel | `0px 2px 8px 0px rgba(33,33,33,0.08)` | Crisp low lift for white metric and process cards. |
|  | URL form | `0px 8px 28px -12px rgba(20,20,20,0.1)` | Subtle lift under the long capsule form. |
| testimonial walls | Punched paper | `0px 2px 0px 0px rgba(20,20,20,0.04), 0px 18px 36px -20px rgba(20,20,20,0.18)` | Soft paper-like lift beneath testimonial cards. |
| portfolio-led feature openings | Work sample fan | `0px 16px 38px 0px rgba(20,20,20,0.18)` | Dimensional separation beneath overlapping full-page samples. |

### Surfaces

#### Canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #f4f4f4; color: #212121`

#### Colored stage · level 0

**Use:** Substantial chapters with one dominant bright hue.

**CSS:** `background: #fffa64; border-radius: 20px; padding: 160px 96px`

**Observed:** Blue galleries use 76px vertical inset, pink proof uses 76px top inset and lets cards cross its lower boundary, and green process bands use 128px vertical inset.

**Transfer:** Assign one palette hue to a distinct story beat; keep the text charcoal and interior cards white.

#### White editorial panel · level 0

**Use:** Questions, comparison and explanatory content.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 128px 96px`

**Observed:** A broad inset enclosure rather than individual question cards.

**Transfer:** Keep dense material grouped within a single calm surface.

#### White artifact · level 1

**Use:** Result and process cards on colored backing.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: 0px 2px 8px 0px rgba(33,33,33,0.08); padding: 24px`

**Observed:** Result cards are tightly organized; process cards use 28px internal padding.

**Transfer:** Use self-contained evidence artifacts with a dominant result or short numbered explanation.

#### Charcoal enclosure · level 0

**Use:** Shared ending and occasional conversion interlude.

**CSS:** `background: #212121; color: #ffffff; border-radius: 20px; padding: 48px 32px; overflow: hidden`

**Observed:** The footer contains a very large sculpture area before the denser text layers.

**Transfer:** Keep this a full narrative destination with substantial space above its utility content.

#### Film scrim · level 1

**Use:** Text legibility over the cinematic opening.

**CSS:** `background: radial-gradient(ellipse 70% 58% at center, rgba(0,0,0,0.58), rgba(0,0,0,0.34) 42%, rgba(0,0,0,0) 74%)`

**Observed:** Darkening sits between the film and white text, preserving colored light at the edges.

**Transfer:** Tune the dark center to the new scene while retaining visible environmental detail.

#### Explanation band · level 0

**Only for:** pricing pages

**Use:** Explain the purchasing model without adding another accent hue.

**CSS:** `background: #e5e5e5; border-radius: 20px; padding: 112px 96px`

#### Recommended comparison column · level 1

**Only for:** pricing pages

**Use:** Continuous visual emphasis across the recommended plan column.

**CSS:** `background: rgba(255,184,252,0.08); border-left: 1px solid rgba(33,33,33,0.1)`

**Observed:** The header strengthens the pink fill to 30%; the column remains a pale wash, not an opaque color stripe.

**Transfer:** Apply a single continuous wash to one recommended option.

## Components

### Floating navigation

**Use:** Persistent global navigation above every scene.

**CSS:** `display: flex; align-items: center; height: 48px; padding: 0px 20px 0px 22px; background: #f4f4f4; border-radius: 9999px; gap: 28px`

**Text style:** `navigation` — Geist 500 · 15.2px/1 · tracking -0.01em

**Observed:** A left capsule joins a compact wordmark with text destinations; a detached right cluster holds account and conversion actions. The outer navigation is fixed 24px from the top and constrained to 1400px, with 32px side padding.

**States:** Declared: hover text becomes #212121; focus-visible navigation text has outline-style none.

**Transfer:** Preserve the separated islands and let the pale left capsule remain readable on bright or dark sections.

### Primary button

**Use:** Conversion in pale and colored sections.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #212121; color: #ffffff; height: 46px; padding: 16px 24px; border-radius: 9999px; gap: 12px`

**Text style:** `button` — Geist 600 · 14px/1 · tracking -0.01em

**Observed:** Small dark capsule by default; the cinematic opening reverses it to white with dark text. Pair with an outlined secondary action, not a second equally loud fill. Navigation actions are 48px tall.

**Transfer:** Use a short imperative suited to the new product.

### URL conversion form

**Use:** Low-friction closing conversion.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #f4f4f4; border: 1px solid rgba(33,33,33,0.15); border-radius: 9999px; padding: 6px; height: 54px; max-width: 540px; box-shadow: 0px 8px 28px -12px rgba(20,20,20,0.1)`

**Text style:** `form-button` — Geist 600 · 14px/20px · tracking -0.005em

**Observed:** An unboxed input expands at left; a compact dark submit capsule with a right arrow sits inside at right. The submit is 40px tall with 10px 20px padding. A muted reassurance line sits underneath; the default presentation places both inside a small white punched panel.

**States:** Declared: hover submit background uses charcoal at 85%; focus-visible submit outline is 2px solid #ffb8fc with 2px offset.

**Transfer:** Request the smallest useful starting input rather than a multi-field lead form.

### Category capsule

**Use:** Eyebrows above section headings and small artifact categories.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 0px 12px; gap: 6px; background: #212121; color: #c3dbff; border-radius: 9999px`

**Text style:** `label` — Geist 600 · 14px/1.4286 · tracking -0.01em

**Observed:** Blue is the default label color; pink, yellow and lime vary by chapter. It reads as a little badge rather than letterspaced all-caps metadata.

**Transfer:** Keep labels brief and subordinate to the much larger heading.

### Metric artifact

**Use:** Quantified product proof on a colored stage.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 12px; padding: 24px; box-shadow: 0px 2px 8px 0px rgba(33,33,33,0.08); overflow: hidden`

**Text style:** `metric` — Geist 700 · 72px/0.86

**Observed:** Category identity at top, oversized black numeral with a light colored sparkline, a small result caption, a gray activity note, then a compact row of secondary metrics and a live-status line. Three panels project beyond the lower edge of the pink stage.

**Transfer:** Replace dashboard detail with a real result and one legible supporting action; preserve the strong numeral-to-caption contrast.

### Punched audience card

**Use:** Audience or use-case selector beside a sticky introduction.

**CSS:** `position: relative; border: 1px solid rgba(33,33,33,0.08); border-radius: 4px; padding: 32px 24px`

**Text style:** `chapter` — FK Screamer 700 · 72px/0.86 · uppercase

**Observed:** Four contrasting circular punches mark the corners. A compressed uppercase name shares the top with a short sentence. The selected card expands into a blue panel with bullets and actions; collapsed cards remain on the canvas. Feature-page selections use pink.

**Transfer:** Give one audience the full detail view while the other choices remain shallow title strips.

### Strategy card

**Use:** Reusable workflows, guides or practical examples inside a blue rail.

**CSS:** `display: flex; flex-direction: column; max-width: 384px; border-radius: 8px; overflow: hidden; background: #ffffff`

**Text style:** `card-title` — Geist 600 · 30px/1.25 · tracking -0.04em

**Observed:** A pale blue upper title field sits above a white lower field with small author attribution and a compact explanation. The rail has 24px gaps and paired circular previous/next controls.

**Transfer:** Make the top field a substantial typographic cover rather than a tiny image thumbnail.

### Editorial chapter row

**Use:** Detailed capability or principle explanation.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 40px; padding: 48px 0px; border-top: 1px solid rgba(33,33,33,0.08)`

**Text style:** `subheading` — Geist 600 · 28px/1.08 · tracking -0.04em

**Observed:** A condensed chapter word occupies the left four columns. The right eight hold a sentence-case subheading, body and optional three short bullet lines. It is a ruled editorial layout, not a collection of boxes.

**Transfer:** Use the same column split through successive chapters, including one-word category labels.

### Question row

**Use:** Objection handling inside a white editorial panel.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 40px; padding: 32px 0px; border-top: 1px solid rgba(33,33,33,0.08)`

**Text style:** `subheading` — Geist 600 · 28px/1.08 · tracking -0.04em

**Observed:** Accordion version places the question across eleven columns with a small right chevron; its answer opens below. The long-form feature version instead uses a left question column and visible answer at right, with 40px vertical padding.

**States:** Declared: focus-visible toggle outline is 2px solid #ffb8fc with 2px offset.

**Transfer:** Use accordion rows for transactional questions and visible paired answers for long-form education.

### Summary destination capsule

**Use:** Assistant or research destinations inside the footer summary band.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 20px; border-radius: 9999px; background: rgba(255,255,255,0.08); border: 1px solid rgba(255,255,255,0.16); color: #ffffff`

**Text style:** `caption` — Geist 600 · 14px/20px

**Observed:** Five destinations wrap with 12px gaps beside a short heading and description; the entire band is bounded by white 16% hairlines and padded 40px vertically.

**States:** Declared: hover background is white at 16%; focus-visible outline resolves to 2px solid white with 4px offset.

**Transfer:** Provide genuinely useful summary or comparison destinations while keeping the compact wrapping capsule group.

### Testimonial paper

**Only for:** testimonial walls

**Use:** Dense social proof that feels like spontaneous messages.

**CSS:** `position: relative; background: #d1f48c; border: 1px solid rgba(33,33,33,0.08); border-radius: 4px; padding: 32px 24px; box-shadow: 0px 2px 0px 0px rgba(20,20,20,0.04), 0px 18px 36px -20px rgba(20,20,20,0.18)`

**Text style:** `quote` — Geist 400 · 18px/1.45 · tracking -0.005em

**Observed:** Four corner punches, tiny channel icon and label, quote with bold phrases, then circular avatar and compact attribution. White, blue, pink, yellow and green cards are interleaved; slight rotations and unequal heights give the wall physical character.

**Transfer:** Use authentic short quotes and preserve informal language rather than rewriting each into a polished slogan.

### Plan card

**Only for:** pricing pages

**Use:** Compare purchasable tiers.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border: 1px solid rgba(33,33,33,0.08); border-radius: 14px; padding: 32px`

**Text style:** `price` — Geist 700 · 48px/1

**Observed:** Tier name and short description precede a large price, usage selector, included/excluded features and bottom action. Recommended plan has a pink border, small dark badge with pink lettering and a restrained shadow. Its action and the enterprise action are dark; lower-tier actions are white and outlined.

**Transfer:** Align prices and actions across tiers; emphasize one recommendation without enlarging the whole card.

## Imagery and graphics

### Cinematic working world

**Use:** Default opening media stage.

**Observed:** A dim office-like environment with a printer and enormous soft inflatable figures, lit by warm amber and cool green-blue light. The full-width moving scene fills most of the opening; central darkening keeps the white headline dominant without hiding the setting.

**Transfer:** Stage a relevant real-world tool or environment with a surreal inflated form under mixed colored light. Minimum acceptable version is a single high-quality still with real depth, strong shadow and a darkened central text zone.

### Inflated objects and word sculpture

**Use:** Signature visual punctuation throughout the story and a monumental sculptural ending.

**Observed:** Soft pillow-like lobes, flowers, rings and letterforms have translucent vinyl skins, inflated bulges, uneven welded seams, creases and broad studio highlights. Blue, pink, green and yellow objects float on gray or charcoal; small forms interrupt headings while a much larger compound form occupies a deep scrolling stage.

**Transfer:** Make a new emblem and short word sculpture in the same material language. Keep their irregular physical construction and soft light rather than substituting glossy rigid plastic or generic gradient blobs.

**Build:** For a minimum SVG version, assemble overlapping rounded lobes or outlined letter paths into a 320px object. Fill each shape with a pale blue, pink, green or yellow radial gradient with a near-white upper-left hotspot and a darker translucent rim. Add a thin inset contour at 4px from the edge, several short curved crease strokes at joins with charcoal at 12%, and a blurred white highlight at 35% opacity. Use overlapping translucent lobes and restrained soft shadow to imply volume. For a word sculpture, arrange individually padded letter silhouettes with small independent rotations across a 1152px stage.

### Soft chromatic proof backdrop

**Use:** Pink quantitative proof chapter.

**Observed:** Pink is not entirely flat: soft purple-pink light blooms rise from the lower edge behind white dashboard panels; the top stays lighter and clear for the heading.

**Transfer:** Keep the numerical artifacts crisp and let a low-frequency glow create depth behind them.

**Build:** Place two oversized radial ellipses behind the cards near the lower left and lower center, using pink and charcoal at 8% to 12% alpha; blur by 70px and clip within the 20px enclosure. Keep the upper third mostly the base pink. Match the soft glow; exact stops are not essential.

### Punched paper details

**Use:** Audience cards, compact conversion panel and testimonial paper.

**Observed:** Tiny circular corner marks create the impression of punched or pinned paper. They contrast with the backing: dark on pale paper and pale on selected color panels.

**Transfer:** Use four marks as a repeated construction detail, not as a random decorative dot field.

**Build:** Create four 8px circular pseudo-elements or SVG circles inset roughly 12px from the card corners. Use charcoal on light cards and white on colored selected cards. Keep the edge border at charcoal 8% and the corners at 4px.

### Work sample fan and gallery

**Only for:** portfolio-led feature pages

**Use:** Demonstrate actual output in the opening and in a blue proof rail.

**Observed:** Three tall website samples overlap in a fan to the right of a left-aligned headline, with mild perspective and a deep soft shadow. Later samples become upright 340px by 425px panels with 12px corners, dark capsules below and a next sample cut by the right edge.

**Transfer:** Show real artifacts from the new product at a scale where their visual identity is apparent. Keep surrounding marketing typography distinct from the artifacts' own typography.

### Icons

**Observed:** Small round-capped outline icons, typically 14px to 20px, with 2px to 2.4px strokes. Arrows sit after submit labels, chevrons at the far right of question rows, and checks inside feature lists. Small filled channel marks belong only to testimonial chrome.

**Transfer:** Choose compact rounded-stroke symbols in the surrounding text color; avoid large colored icon tiles. Let the sculptural objects carry the expressive imagery.

## Section recipes

How recurring sections are built.

### First screen: Cinematic poster opening

**Observed:** The top 96px is pale canvas with a floating navigation row. Below it a 1376px by 866px film panel with 12px corners occupies almost the full viewport width. Layers run from environmental film, through a dark central scrim, to a centered white 144px uppercase poster headline up to 1020px wide. The headline forms three dense lines across roughly two thirds of the window, with the main object visible behind and around it. A narrow two-line 16px support paragraph and paired 46px capsule actions follow at 28px intervals. Within the first 900px the headline, support, both actions, main scene and a small lower-left announcement card are visible; the bottom of the media and trust band fall below the fold.

**Transfer:** Use a new cinematic environment plus an inflated product-related emblem; a carefully lit still is sufficient when motion media is unavailable. Keep the overlay text as the primary focal point. Transactional feature and pricing pages can instead open on gray with a centered 144px two-line headline, dark category badge, 640px support and a single action; a portfolio-led feature page uses the 96px headline left and a three-artifact fan right. A testimonial index opens with a 48px sentence-case statement above its wall.

**Avoid:** Do not replace this with a small text-left/UI-right startup hero, a bright abstract gradient rectangle or an unshaded stock photograph. Do not make the poster headline share equal visual weight with a large dashboard.

**Text style:** `display` — FK Screamer 700 · 144px/0.86 · uppercase

### Trust marquee

**Observed:** A 1280px-wide logo rail follows a small centered caption, separated by 40px. The whole band uses 64px vertical padding. Grayscale marks sit in one horizontal line with fading edges rather than individual customer cards.

**Transfer:** Use real customers or partners, with uniform visual weight and a restrained caption.

### Statement and sculptural interruption

**Observed:** A centered 144px uppercase statement appears on pale gray with a 446px inflated object behind it. Words have a pale charcoal backing and progressively fill dark. A short centered body line follows before a white three-column feature strip.

**Transfer:** State the problem or reversal in a few short phrases; let an inflated object interrupt the text without obscuring its meaning.

**Text style:** `display` — FK Screamer 700 · 144px/0.86 · uppercase

### Chromatic working proof

**Observed:** A pink Colored stage pairs a 72px chapter phrase at upper left with a short explanation at upper right. A three-column Metric artifact grid sits lower and crosses the stage boundary by about 60px. The following yellow activity stage splits a 96px headline into upper-left and lower-right phrases around a stack of three white notification cards and a translucent object.

**Transfer:** Show a concrete outcome and a sequence of real actions. Preserve the two complementary proof modes: results as artifacts, activity as a staged running feed.

### Blue gallery chapter

**Observed:** A blue Colored stage starts with a 72px phrase punctuated by a small inflated object. Support and paired circular controls sit to the right. A Gallery rail of Strategy cards or tall work samples spans the lower half, with the next item partially visible.

**Transfer:** Use repeatable workflows, deliverables or examples rather than generic feature cards.

**Text style:** `chapter` — FK Screamer 700 · 72px/0.86 · uppercase

### Monumental object stage

**Observed:** An inflated compound object occupies a deep pale section while individual 144px headline words anchor to opposing sides. Below the spectacle, a white three-column feature strip gives each group a category capsule, a compact heading and small colored bullets.

**Transfer:** Build one large object from a few repeated soft shapes, then pair it with a brief practical breakdown. Keep it an unmistakable full-scale moment rather than a thumbnail.

### Process band

**Observed:** A green Colored stage uses the Split editorial grid for a small label at left and 96px headline with 18px support at right. Five numbered steps run below on a faint horizontal rule, each with a dark circular number, 22px title and short description. A final ruled line carries a concise case-study link.

**Transfer:** Map a short adoption or usage process onto numbered milestones; adapt the number of steps to the actual story.

### Audience selection

**Observed:** The Audience grid places a dark Category capsule and 48px heading in a sticky left column. At right, Punched audience cards stack with 4px gaps; one is expanded in blue or pink while other titles remain visible in shallow outlined strips.

**Transfer:** Use relevant audience or use-case choices. The selected card should tell a useful story, not merely change its color.

**Text style:** `heading` — Geist 600 · 48px/1.08 · tracking -0.04em

### Final invitation

**Observed:** The core closing call uses a centered 144px condensed command on gray, a short support line and a URL conversion form in a small white punched panel. Feature and pricing variants use a yellow Colored stage with a 265px to 332px inflated star above the headline, a muted 18px support paragraph and a single dark action plus a small secondary link. The testimonial variant uses a green inflated four-lobe emblem above its gray closing call.

**Transfer:** Retain a monumental invitation and one simple starting action; select the gray form-led or yellow action-led treatment based on the conversion model.

**Text style:** `display` — FK Screamer 700 · 144px/0.86 · uppercase

### Sculptural utility ending

**Observed:** All page types end in the Charcoal enclosure. A 1152px by 648px inflated word sculpture stage precedes a short brand proposition at left and contact link at right. A 190px-tall ruled band contains a 36px summary heading, body and Summary destination capsules. Below come five link columns, a dense wrapping integrations index, and a final copyright/legal/status line with maker credit opposite.

**Transfer:** Use the new product's own short word or emblem as a large soft sculpture, then transition into practical destinations. Keep the summary band and substantial link architecture even when the exact categories differ.

**Text style:** `heading-small` — Geist 600 · 36px/1.08 · tracking -0.04em

### Detailed editorial chapters

**Only for:** information-heavy feature pages

**Observed:** An introductory label sits in the left four columns while a 64px sentence-case heading and 18px body occupy the right eight. After a 64px gap, Editorial chapter rows repeat the split with 72px condensed labels, 28px subheadings and 16px explanations.

**Transfer:** Use when product comprehension needs sustained reading; alternate with a blue gallery or colored conversion chapter rather than presenting the entire page as card grids.

**Text style:** `editorial-heading` — Geist 600 · 64px/1.08 · tracking -0.04em

### Pricing and comparison

**Only for:** pricing pages

**Observed:** A centered monumental opening leads to a monthly/annual capsule toggle and four Plan cards in a 1280px grid. A gray explanation band uses a side heading with a stack of ruled text pairs. A broad white panel then holds a 1152px comparison table with 65px rows, a wider feature column and four plan columns; the recommended column carries a continuous pale pink wash.

**Transfer:** Keep the offer selection distinct from the model explanation and the exhaustive comparison. Use one restrained recommendation treatment across both cards and table.

### Question panel

**Only for:** detailed feature and pricing pages

**Observed:** A White editorial panel contains a dark category badge at left, 64px sentence-case heading at right and a 64px gap before Question rows. Transactional variants are accordions; the long-form feature variant shows paired question and answer columns openly.

**Transfer:** Choose the answer format to match reading needs; keep the same thin rules and typographic hierarchy.

**Text style:** `editorial-heading` — Geist 600 · 64px/1.08 · tracking -0.04em

## Page flow

**Storyline:** Outcome promise → trust → problem reversal → working proof → practical capabilities and examples → audience fit → objection handling where needed → low-friction invitation → sculptural utility ending.

### Broad product landing page with the strongest expressive range

1. **Promise** — Cinematic poster scene and paired actions.
2. **Social proof** — Grayscale trust marquee.
3. **Problem reversal** — Revealed poster statement with an inflated interruption and three-part explanation.
4. **Working proof** — Pink metric stage, then yellow activity feed.
5. **Practical examples** — Blue strategy-card rail and monumental object with capability breakdown.
6. **Adoption and fit** — Green numbered process band and split audience selector.
7. **Closing call** — Gray monumental command and compact starting form.
8. **Utility ending** — Charcoal sculpture, summary destinations and dense links.

**Transfer:** Use this as the default expressive vocabulary; choose narrative beats that serve the new product rather than reproducing every chapter.

### Testimonial index that makes spontaneous enthusiasm the content

1. **Promise** — Left-aligned 48px sentence-case statement.
2. **Social proof** — Four uneven columns of colorful punched quote cards.
3. **Closing call** — Green inflated emblem and monumental invitation with a starting form.
4. **Utility ending** — Shared charcoal sculpture and full utility footer.

**Transfer:** Use for substantial real testimony; keep the paper texture and informal quotations instead of a polished carousel.

### Focused feature education with compliance and setup reassurance

1. **Promise** — Centered two-line poster headline with small inflated punctuation.
2. **Social proof** — Trust marquee.
3. **Mechanism** — Blue numbered two-by-two process-card band.
4. **Capability detail** — Centered editorial statement with four white explanatory columns.
5. **Conversion interlude** — Charcoal split callout with an inflated object at the upper-right edge.
6. **Audience fit** — Split punched-card selection.
7. **Trust and objections** — Ruled principle chapters and white accordion panel.
8. **Closing call** — Yellow sculpture-led invitation, then the complete charcoal ending.

**Transfer:** Use this structure when a feature requires explanation of operation, boundaries and responsible use.

### Long-form flagship feature page grounded in actual output

1. **Promise and demonstration** — 96px poster headline at left with three overlapping work samples at right.
2. **Problem reversal** — Trust rail and sculptural statement reveal.
3. **Capability chapters** — Sentence-case editorial introduction followed by condensed-label chapter rows.
4. **Output proof** — Blue gallery of tall actual deliverables.
5. **Depth and audience fit** — More ruled capability chapters, audience selector and category definition.
6. **Objection handling** — Open paired question/answer rows in a white panel.
7. **Closing call** — Yellow sculptural invitation and complete charcoal utility ending.

**Transfer:** Borrow the clear editorial rhythm for products whose craft and capabilities need sustained explanation.

### Purchase decision page with clear tier comparison and model education

1. **Promise** — Centered two-line poster statement on gray.
2. **Offer selection** — Billing toggle and four aligned white plan cards.
3. **Model explanation** — Gray band with ruled heading-and-explanation pairs.
4. **Comparison** — White full-width table with pale pink recommended column.
5. **Objection handling** — White accordion panel.
6. **Closing call** — Yellow invitation with inflated star and short action, followed by the full charcoal ending.

**Transfer:** Carry over the restrained table and card system without losing the expressive final act.

## Writing

Confident, direct and slightly mischievous. Big claims are expressed through concrete work and everyday consequences, then grounded in plain operational detail.

**Do not copy:** Do not reuse Ploy names, logos, proprietary product labels, customer identities, quotations, fundraising claims, performance numbers, compliance claims or setup-time promises. Source examples illustrate cadence only; replace every factual assertion with the new product's substantiated truth.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name as an active worker; use we when describing partnership or responsibility.
- **Rhythm:** Poster headlines are brief declarative promises or reversals, often split into two clauses. Support uses one or two plain sentences. Detailed chapters mix a short sentence-case heading with a fuller paragraph and compact bullets. Fragments and deliberately abrupt full stops create pace.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Turn an ordinary work burden into a strong outcome statement addressed to the reader. | 5–12 words | “Your website should be working harder than you are.”<br>“Pay for what you build.” |
| Reversal | Pair a familiar situation with a short contrasting consequence. | 4–10 words across two clauses | “You slept 8 hours. [Brand] didn't.”<br>“Launch is the starting line, not the finish.” |
| Chapter heading | Name the capability, then explain its benefit in a brisk conversational sentence. | 1–3 word label; 5–10 word subheading | “Code with taste, built at AI speed.”<br>“Your brand evolves. So does every page.” |
| Supporting line | Say what the product does and what the reader can expect next; favor tangible verbs. | 1–2 sentences | “[Brand] takes what you have and puts it on autopilot.”<br>“Bring the brand. Ship the page.” |
| Primary action | Short verb-led commitment with a low barrier. | 2–5 words | “Start Free”<br>“Build your first page” |
| Closing invitation | A direct command, or a playful invitation that ties back to the proof. | 3–8 words | “Stop maintaining your website.”<br>“Be the next group-chat screenshot.” |
| Reassurance | Compact factual fragments separated by centered dots. | 3 short fragments | “Free tier · No card · 60-second slurp” |

**Words and phrasing to use:** ship; build; bring; watch; working; on-brand; keeps working; at your pace; while you sleep; real work

**Avoid:** revolutionary ecosystem; unlock limitless potential; seamless synergy; next-generation solution; unqualified superlatives

**Rules:**

- Lead with a recognizable burden or outcome, not a category taxonomy.
- Give the product active verbs: it watches, drafts, fixes or reports; explain what that means in the next sentence.
- Use vivid informal language sparingly for a distinctive action, then explain it plainly.
- Keep transactional and trust explanations literal; playful headlines must not blur restrictions.
- Let authentic quotes retain their irregular grammar and emphasis; keep editorial copy more controlled.

## Do's and Don'ts

### Do

- Use 144px uppercase condensed display with 0.86 line height for the biggest promises.
- Keep the default content alignment at 1152px and the colored outer enclosure inset 24px.
- Preserve 20px section corners, 12px metric corners and 4px paper corners as distinct construction scales.
- Give color a whole chapter-sized stage; let white artifacts sit sharply against it.
- Use 48px/1.08 Geist at weight 600 and -0.04em for conversational section introductions.
- Make the inflated object feel physically soft with seams, creases and broad highlights.
- Use 12px gaps for action groups and 40px gutters for editorial column divisions.
- End with the giant soft sculpture and a complete charcoal utility enclosure, including the ruled summary band.

### Don't

- Do not widen the condensed headlines into a standard geometric sans; their tall packed silhouette is the main visual tension.
- Do not round every surface into 20px cards; punched paper must stay at 4px.
- Do not turn the palette into multicolor text or a rainbow gradient on every heading; keep headline lettering charcoal or white.
- Do not promote tiny UI icons into the main illustration system; 14px–20px outline symbols are supporting details.
- Do not give every card a heavy shadow; low-lift metric panels and flat editorial rows should remain distinct.
- Do not place all page content inside isolated equal-sized tiles; the 12-column editorial split and large unboxed statements are essential contrasts.
- Do not set long paragraphs in the condensed display face or all caps.
- Do not shrink the ending to a copyright strip or remove its generous sculpture stage.

## Motion and responsive

### Motion

**Observed:**

- Opening intro declares a 0.72s animation with cubic-bezier(0.22,1,0.36,1).
- Action color transitions use 0.15s cubic-bezier(.4,0,.2,1); navigation color uses 0.2s with the same curve.
- Strategy links declare 0.2s transform transitions with cubic-bezier(0,0,.2,1). Testimonial cards declare 0.3s box-shadow transitions.
- Statement lettering uses a pale backing and a horizontal dark text-clipped fill. The trust rail has a marquee treatment with transparent edge masking.

**Transfer:**

- Let motion carry the staged object and statement relationship, while the white artifacts remain easy to read.
- Use the measured short transitions for small actions and retain the longer opening entrance as a separate theatrical gesture.

**Unknown:**

- Exact scroll-reveal timing, marquee speed and sculptural video playback behavior are not established.

### Responsive

**Observed:**

- Desktop navigation capsule is enabled at 960px and above.
- Opening headline declarations step from 144px to 96px below the large breakpoint, 80px below the medium breakpoint, and 56px at 540px and below.
- Audience headings declare 42px below the large breakpoint and 32px at 540px and below; 64px editorial headings declare 52px and 40px variants.
- Editorial chapter grids declare a single column below the large breakpoint with 24px gaps and 32px vertical row padding. Large band side insets reduce from 96px to 24px, then 16px at 540px and below.
- The footer summary band declares a stacked arrangement at 760px and below.

**Transfer:**

- Preserve the poster silhouette and object-to-type overlap as type steps down; do not simply miniaturize the entire desktop composition.
- Stack the label above the explanation in editorial rows and put the audience choices after their introduction.
- Keep galleries as legible rails instead of fitting four miniature samples across a narrow screen.

**Unknown:**

- Exact mobile media framing, navigation expansion and pricing-table replacement were not visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
