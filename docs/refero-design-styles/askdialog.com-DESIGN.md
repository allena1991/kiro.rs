# Dialog — editorial warmth in orbit

## Overview

An airy technology style that pairs literary serif promises with small, matter-of-fact sans-serif explanations. A pale gray and white world is warmed by apricot light, floating interface fragments and softly rounded stages, with black chapters adding depth. It suits sophisticated software and service products that need to feel approachable without losing technical credibility; photography supplies human context while diagrams and interface scenes explain the mechanism.

### Essentials

- Literary promises, utilitarian explanations: Hedvig Letters Serif at 60px/1.2, weight 400 and -0.03em tracking opens the page; Inter at 14px or 16px carries the explanation.
- The opening feels suspended inside a warm planetary horizon: an oversized 1600px circular field clips beyond the top and sides, holds a centered 920px headline area and resolves into the pale canvas beneath it. Recreate the apricot center and lavender rim even without product artwork.
- Actions are nested, rounded objects rather than rectangular commands: orange pills use 14px/20px medium text, 44px height and 12px 24px padding; the opening joins an input and action inside a white 448px × 56px capsule.
- Color behaves like light, not a category system: most content sits on #f7f7f7 or white, orange #ff9752 marks actions and evidence, and a broad warm glow belongs to the opening. Include a black or #141414 demonstration chapter as a strong counterweight, not a dark tint on every card.
- Explanations become miniature spatial scenes: white 288px × 74px cards with 16px corners flank a softly glowing orb; interface fragments float on broad white stages with 40px or 48px corners. Every new landing page needs a luminous focal object and a concrete product scene; a simple CSS orb plus an honest UI mockup is the minimum equivalent.
- Proof moves sideways while the story moves downward: portrait photography and 208px square integration tiles form clipped horizontal strips, with 16px or 20px gaps. Carry the device into a relevant proof or ecosystem strip rather than filling the page with static logo grids.
- The ending downshifts instead of shouting: a 20px/28px semibold invitation shares a row with an orange pill, followed by a 1px divider and a spacious footer with three narrow link columns; specialized product pages add a 540px soft-glow conversion stage before it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Horizon orange | `#ff7f36` | `--color-horizon-orange` | background | Saturated end of the luminous opening gradient. |
| Horizon peach | `#fa965f` | `--color-horizon-peach` | background | Middle warmth of the opening gradient. |
| Horizon mauve | `#dfb8b5` | `--color-horizon-mauve` | background | Muted cooler end of the opening gradient; combine with a lavender rim. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Apricot action | `#ff9752` | `--color-orange` | action, accent, text | Default conversion actions, technical tags and short quantified proof. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background | Primary light-theme headings and the deepest demonstration stages. |
| Charcoal chapter | `#141414` | `--color-charcoal` | background | Full-width analytical demonstration chapter. |
| Explanatory gray | `#666666` | `--color-body-muted` | text | Black at 60% over white; on the gray canvas it reads slightly darker. Used for explanatory paragraphs. |
| Secondary gray | `#808080` | `--color-secondary` | text, link | Black at 50% over white for captions, footer links and secondary support. |
| Inverse explanatory gray | `#959595` | `--color-inverse-muted` | text | White at 55% over the charcoal stage for secondary descriptions. |
| Divider gray | `#dedede` | `--color-rule` | border | Black at 10% over the pale gray canvas for footer separators. |
| Soft card edge | `#f0f0f0` | `--color-edge` | border | Black at 6% over white for floating diagram card outlines. |
| Pale gray canvas | `#f7f7f7` | `--color-canvas` | background | Default page and footer canvas. |
| Near-white tile | `#fafafa` | `--color-tile` | surface | Integration tile backing, slightly separated from pure white. |
| White stage | `#ffffff` | `--color-white` | surface, text, action | Raised panels and capsules; inverse headings and button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| dark technical landing pages | Dark raised panel | `#141414` | `--color-dark-panel` | surface | Visible result of white at 8% over black. |
| product-detail proof cards | Statistic wash | `#f5f5f5` | `--color-stat-wash` | surface | Black at 4% over white for the inset statistic well. |

## Typography

- **Hedvig Letters Serif** — Hero promises, chapter headings and selected large statistics. Regular, fine-stroked editorial serif with broad, open forms and a literary rather than ornamental tone. Font stack: "Hedvig Letters Serif", Georgia, serif.
- **Inter** — Explanations, navigation, captions, actions and footer. Compact neutral sans-serif; regular body text and medium action labels. Font stack: "Inter", Arial, sans-serif.
- **Hedvig Letters Sans** — Feature titles and case-study headings. Plain, softly human sans-serif kept at regular weight. Font stack: "Hedvig Letters Sans", Arial, sans-serif.
- **Fragment Mono** — Small process tags within explanatory diagrams. Tiny monospaced labels that distinguish a process from marketing prose. Font stack: "Fragment Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Hedvig Letters Serif | 400 | 60px | 1.2 | -0.03em | Primary promise, centered in the default opening. |
| heading-large | Hedvig Letters Serif | 400 | 48px | 1.2 | -0.025em | Centered ecosystem and FAQ headings. |
| heading-inverse | Hedvig Letters Serif | 400 | 48px | 1.2 | -0.03em | Large heading over the charcoal demonstration chapter. |
| heading | Hedvig Letters Serif | 400 | 42px | 1.2 | -0.03em | Core capability and mechanism chapter headings. |
| feature-title | Hedvig Letters Sans | 400 | 26px | 1.2 | -0.02em | Short title inside a broad white feature stage. |
| footer-invitation | Inter | 600 | 20px | 1.4 | -0.025em | Compact closing invitation above the footer divider. |
| hero-support | Inter | 500 | 16px | 1.6 | -0.02em | White centered explanation beneath the opening promise. |
| section-support | Inter | 400 | 16px | 1.625 | normal | Support beneath a core section heading, usually restrained to 448px. |
| body-small | Inter | 400 | 14px | 1.625 | normal | Default feature explanations and analytical benefit descriptions. |
| action | Inter | 500 | 14px | 20px | normal | Pill labels, FAQ questions and small card titles. |
| navigation | Inter | 500 | 14px | 20px | -0.02em | Navigation and the opening inline-form action. |
| secondary | Inter | 400 | 14px | 20px | normal | Footer links, secondary support and tab labels. |
| caption | Inter | 400 | 12px | 16px | normal | Diagram card subtitles and compact reassurance. |
| process-tag | Fragment Mono | 400 | 12px | 16px | normal | Process labels above a diagram's two sides. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail pages | detail-display | Hedvig Letters Serif | 400 | 60px | 1.1 | -0.03em | Left-aligned product name in a split opening. |
| product-detail proof cards | proof-number | Hedvig Letters Serif | 400 | 44px | 1 | -0.03em | A single orange comparison number in a nested proof card. |
| product-detail, case-study and dark technical pages | closing-display | Hedvig Letters Serif | 400 | 42px | 1.15 | -0.03em | Centered final conversion stage title. |
| product-detail, case-study and dark technical pages | detail-feature-title | Hedvig Letters Sans | 400 | 26px | 1.3 | -0.02em | Multiline feature and case-study titles. |
| case-study pages | stat-number | Hedvig Letters Sans | 400 | 26px | 1.3 | normal | Centered numbers in a restrained three-column proof strip. |
| product-detail, case-study and dark technical pages | detail-body | Inter | 400 | 16px | 1.6 | normal | Longer explanations in split feature panels. |

**Notes:**

- Keep display and chapter serifs at weight 400; impact comes from width, close tracking and line breaks, not boldness.
- Use the 42px chapter heading as the default. The 48px centered heading is a distinct ecosystem or FAQ role, not a replacement for every heading.
- Serif tracking is usually -0.03em, while feature sans titles use -0.02em and body copy stays untracked. Do not turn process tags into uppercase eyebrows.
- The hero's second line can be much wider than its first. Preserve coherent phrases rather than balancing every line mechanically.

## Layout

**Density:** Airy at the section scale and compact inside interfaces: broad stages surround small explanatory clusters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small action, icon and tab gaps. |
| 12px | FAQ row separation. |
| 16px | Heading-to-description gap, small card padding and outer container inset. |
| 20px | Opening stack gap and integration tile spacing. |
| 24px | Three-column card gap and button horizontal padding. |
| 32px | Diagram row gaps and text-group separation. |
| 40px | Footer column gaps and analytical benefit grid gaps. |
| 48px | Heading-to-content distance in FAQ and ecosystem stages; divider margins. |
| 56px | Text padding within core feature panels. |
| 64px | Footer vertical padding and diagram offset below its introduction. |
| 80px | Ecosystem stage vertical padding. |
| 96px | Core mechanism stage vertical padding and spacing before major detail chapters. |
| 112px | Dark chapter vertical padding and offset before major capability sections. |
| 128px | Deep black demonstration-stage vertical padding. |
| 160px | Top padding for the default opening content. |

### Containers and grids

- **wide-stage-container**: max width 1312px · side padding 16px. Centers broad 1280px feature stages within the desktop window.
- **mechanism-container**: max width 1280px · side padding 16px. Contains a 1248px rounded mechanism or ecosystem stage.
- **reading-container**: max width 1152px · side padding 16px. 1120px content width for product media, dark chapter content and footer.
- **opening-copy**: max width 920px · side padding 32px. Centered opening headline width; explanatory copy narrows to 640px and action form to 448px.
- **faq-container**: max width 768px · side padding 16px. 736px accordion column, centered independently from wider panels.
- **feature-split**: 2 columns · gap 0px. Equal-width visual and text halves, alternating sides across feature stages.
- **benefit-grid**: 4 columns · gap 40px. Small icon-led explanatory benefits beneath the analytical media.
- **related-grid** (only for product-detail pages): 3 columns · gap 24px. Related capability cards with a small image and a compact title/action baseline.
- **case-stats** (only for case-study pages): 3 columns · gap 16px. Three calm metric wells inside a white rounded strip.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | inline-form | 28px |
|  | floating-cards | 16px |
|  | media-frame | 24px |
|  | mechanism-stage | 40px |
|  | feature-stage | 48px |
| product-detail pages | related-cards | 28px |
| case-study pages | stat-wells | 32px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-card | `0px 10px 30px 0px rgba(0,0,0,0.05)` | White diagram cards; barely perceptible lift. |
| demo-media | `0px 30px 80px 0px rgba(0,0,0,0.06)` | Large demonstration frame on the gray canvas. |
| form-capsule | `0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.02), 0px 4px 8px 0px rgba(0,0,0,0.02)` | Opening form capsule. |

### Surfaces

#### Canvas · level 0

**Use:** Default light marketing canvas.

**CSS:** `background: #f7f7f7; color: #000000`

#### White stage · level 1

**Use:** Broad feature explanations.

**CSS:** `background: #ffffff; border-radius: 48px; overflow: hidden`

**Observed:** A wide rounded stage holds one explanation and one large visual. It is a background plane, not a heavily outlined card.

**Transfer:** Keep a single capability per stage and substantial open space around its visual.

#### Mechanism stage · level 1

**Use:** Centered diagram or ecosystem story.

**CSS:** `background: #ffffff; border-radius: 40px; padding: 96px 56px; overflow: hidden`

**Observed:** The diagram has a centered introduction above it; the ecosystem version uses 80px vertical padding.

**Transfer:** Use when the relation between parts matters more than a screenshot.

#### Horizon field · level 0

**Use:** Warm luminous opening backdrop.

**CSS:** `background: linear-gradient(to top, #ff7f36 0%, #fa965f 40%, #dfb8b5 100%)`

**Observed:** The gradient is layered through a huge clipped circular composition and soft masks; the visible center is orange and the rounded lower rim is muted lavender and pink.

**Transfer:** Use the Luminous field imagery recipe to recreate the visible lighting rather than showing a flat rectangular gradient.

#### Black stage · level 1

**Use:** High-contrast external-workflow demonstration.

**CSS:** `background: #000000; color: #ffffff; border-radius: 40px; padding: 128px 0px`

**Observed:** Centered within the narrower reading container; product fragments occupy one half and serif copy the other.

**Transfer:** Reserve black for a substantial product argument rather than a tiny decorative card.

#### Charcoal chapter · level 0

**Use:** Full-width analytical proof chapter.

**CSS:** `background: #141414; color: #ffffff; padding: 112px 0px; overflow: hidden`

**Observed:** A heading and small white action sit above a wide, dramatically tilted analytical interface, followed by four compact benefits.

**Transfer:** Give the demonstration enough scale to become the chapter's main image.

#### Closing glow stage · level 1

**Only for:** product-detail, case-study and dark technical pages

**Use:** Final conversion panel before the compact footer.

**CSS:** `background: linear-gradient(#ffffff 0%, #f7f7f7 100%); border-radius: 48px; min-height: 540px; padding: 0px 24px; overflow: hidden`

**Observed:** A soft peach and lavender atmospheric image spreads behind a centered heading, paragraph and pill. The dark version places the same warmth over black with a white action.

**Transfer:** Rebuild the atmosphere using low-opacity warm and lavender blurred fields; match the softness rather than exact gradient stops.

#### Dark feature stage · level 1

**Only for:** dark technical landing pages

**Use:** Technical product chapters.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 48px; overflow: hidden`

**Observed:** Same broad split construction as White stage, but over a black canvas. Visuals may be white editor panels or dark workflow fragments.

**Transfer:** Preserve the stage geometry when changing theme rather than introducing an unrelated card system.

## Components

### Primary button

**Use:** Main conversion action and footer invitation.

**CSS:** `background: #ff9752; color: #ffffff; border-radius: 9999px; padding: 12px 24px; height: 44px`

**Text style:** `action` — Inter 500 · 14px/20px

**Observed:** A compact text-only pill. Small feature actions use 40px height and 10px 20px padding; detail-page conversion actions grow to 48px. White inverse pills appear on black stages.

**Transfer:** Use one short verb-led action, without a large arrow or icon.

### Navigation

**Use:** Wayfinding at the opening and during long-page reading.

**CSS:** `display: flex; align-items: center; gap: 28px`

**Text style:** `navigation` — Inter 500 · 14px/20px · tracking -0.02em

**Observed:** The initial header spans the stage with a small wordmark at left and text links, language selector, login and a white pill action at right. During scrolling it becomes a centered floating cluster: separate capsules for the mark, link group, login and orange action.

**Transfer:** Keep the modular capsule silhouette, not a full-width opaque sticky toolbar.

### Inline trial form

**Use:** A low-friction way into the product at the opening.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #ffffff; border-radius: 28px; padding: 6px; width: 448px; height: 56px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.02), 0px 4px 8px 0px rgba(0,0,0,0.02)`

**Text style:** `navigation` — Inter 500 · 14px/20px · tracking -0.02em

**Observed:** Input on the left, orange pill on the right. The input has no visually competing border; its own rounded field is inset into the outer white capsule.

**Transfer:** Ask for one meaningful identifier, such as a work email or project URL.

### Floating explanation card

**Use:** Small inputs and outputs around the luminous focal object.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 16px; padding: 16px; max-width: 288px; box-shadow: 0px 10px 30px 0px rgba(0,0,0,0.05)`

**Text style:** `action` — Inter 500 · 14px/20px

**Observed:** An icon and medium title share a baseline, followed by a 12px gray subtitle. Cards form slightly staggered groups on either side of the orb.

**Transfer:** Use concise nouns for the title and one concrete capability or boundary underneath.

### Process tag

**Use:** Identify the two sides of a mechanism diagram.

**CSS:** `background: rgba(255,151,82,0.1); border: 1px solid rgba(255,151,82,0.4); border-radius: 9999px; color: #ff9752; padding: 4px 16px`

**Text style:** `process-tag` — Fragment Mono 400 · 12px/16px

**Observed:** Tiny monospaced words float above the card columns, with muted explanatory pills below the diagram.

**Transfer:** Name a process step, not a marketing category.

### Integration tile

**Use:** Moving ecosystem proof strip.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 20px; background: #fafafa; border: 1px solid rgba(0,0,0,0.05); border-radius: 16px; width: 208px; height: 208px`

**Text style:** `secondary` — Inter 400 · 14px/20px

**Observed:** Centered platform mark with a small neutral name; repeated in a horizontally clipped, moving row.

**Transfer:** Use relevant partner marks or simple neutral symbols when no integration artwork exists.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `display: flex; align-items: center; gap: 12px; background: #ffffff; border-radius: 16px; padding: 16px 20px; min-height: 60px; width: 100%`

**Text style:** `action` — Inter 500 · 14px/20px

**Observed:** The plus sits before the question, not at the far right. Rows form a narrow centered stack separated by 12px.

**Transfer:** Keep each collapsed question to one clear line where possible.

### Footer link

**Use:** Low-emphasis navigation beneath the final invitation.

**CSS:** `color: rgba(0,0,0,0.5); text-decoration: none`

**Text style:** `secondary` — Inter 400 · 14px/20px

**Observed:** Three narrow columns have compact bold labels; links stack with 10px list spacing. In the dark theme, links use white at 50%.

**States:** Declared: hover color #000000 on light, #ffffff on dark; focus-visible unknown.

**Transfer:** Keep legal links inside the company column rather than a dense full-width legal bar.

### Proof inset

**Only for:** product-detail proof cards

**Use:** One explicit comparative result near a product promise.

**CSS:** `background: rgba(0,0,0,0.04); border-radius: 16px; padding: 28px 24px`

**Text style:** `proof-number` — Hedvig Letters Serif 400 · 44px/1 · tracking -0.03em

**Observed:** The orange serif number and small gray comparison label sit inside a white 28px-radius outer card with 16px padding; a named study or attribution is below the inset.

**Transfer:** Always pair a number with its baseline and attribution.

### Newsletter capsule

**Only for:** dark technical editorial sections

**Use:** Editorial subscription conversion inside a dotted dark stage.

**CSS:** `display: flex; align-items: center; gap: 8px; background: rgba(255,255,255,0.08); border-radius: 28px; padding: 6px; width: 440px; height: 56px`

**Text style:** `secondary` — Inter 400 · 14px/20px

**Observed:** A white subscription pill sits inside the dark email capsule. Reassurance and a small orange login link follow beneath it; the surrounding stage has a faint outline.

**Transfer:** Keep this distinct from the ordinary demo action: it is a centered editorial invitation with a compact privacy line.

## Imagery and graphics

### Luminous field

**Use:** Signature opening atmosphere and a smaller focal object within the mechanism story.

**Observed:** A huge apricot-orange circular light field fills the upper opening, with mauve-lavender edges curving down to meet gray. The small diagram orb repeats this light as a peach sphere with a pale lavender lower rim and a diffuse orange halo.

**Transfer:** Recreate with gradients instead of substituting an unrelated stock illustration. The glowing sphere is a sufficient focal object for a product with no physical artifact.

**Build:** For the opening, center a 1600px circular layer above the content so only its lower portion is visible; clip overflow at the section. Combine the Horizon field gradient with an orange radial center, a translucent lavender rim and soft masking into the canvas. For the small object, place a radial-gradient sphere inside a 256px square: peach highlight toward the upper left, orange core, lavender lower-right rim; add a larger orange layer at roughly 10% opacity with about 40px blur behind it. Keep all copy above these layers.

### Floating product conversation

**Use:** Concrete capability demonstrations inside white split stages.

**Observed:** Isolated message bubbles, a few product thumbnails, pale suggestions and occasional user photos occupy a roughly square half-stage. The visual sits in white space without a full application window; soft gray assistant bubbles alternate with pale peach customer bubbles.

**Transfer:** Show one real input and one useful product output. Use an authentic UI fragment, not a stock dashboard, and keep small text subordinate to the message of the section.

### Perspective analytical interface

**Use:** The main visual in the charcoal demonstration chapter.

**Observed:** A wide dark dashboard tilts in perspective, with clusters of small colored data points and floating labels. Edges fade and blur into charcoal so it feels like a lit object emerging from darkness, not a crisp rectangular screenshot.

**Transfer:** Use a genuine analytical view at broad scale. Minimum equivalent: an SVG panel with clustered muted dots and short labels, tilted as a whole and faded around its edges.

**Build:** Create a dark rectangular panel within the 1120px media region. Place a few irregular clusters of tiny low-saturation pink, ochre, lavender and green circles with dark rounded text labels. Apply perspective with a shallow X tilt and slight negative Z rotation; overlay charcoal gradients at the top, right and bottom to dissolve the panel into the chapter. Confine these colors to the product view.

### Photographic proof strip

**Use:** Social proof beneath a demonstration and the primary image system for case-study pages.

**Observed:** Portrait product and lifestyle images are rounded and closely spaced, with white partner marks over them and dark translucent gradients for legibility. The broad strip uses 256px × 320px images with 16px gaps; the case-study opening uses staggered columns of 192px × 256px portraits with 12px gaps.

**Transfer:** Choose coherent product-in-context photography with recognizable subjects. When partner photography is unavailable, use real user-work scenes or owned product still lifes and retain the portrait rhythm.

### Handheld product scene

**Only for:** product-detail openings

**Use:** A large human-scale object beside the opening copy.

**Observed:** A desaturated hand holds a front-facing black phone; the image fades into the pale canvas near the bottom. The bright screen shows a small piece of product interaction and the device occupies much of the right half.

**Transfer:** Show the product in a plausible human context with a front-facing usable screen. A clean device mockup with a soft grounding shadow is the minimum equivalent; do not rely on an empty screen.

### Dotted night field

**Only for:** dark technical landing pages and editorial subscription stages

**Use:** Atmosphere behind the technical opening and subscription invitation.

**Observed:** A fine white point matrix hangs over black, brightest near the upper edge and progressively dissolving downward. The subscription version is enclosed by a faint rounded outline.

**Transfer:** Retain the delicate fading field rather than switching to neon circuits or a star photograph.

**Build:** Use an SVG grid of small white circles at roughly 10px intervals, with opacity varying between 0.04 and 0.2. Mask it with a vertical fade and a broad elliptical radial falloff so points become sparse toward the sides and disappear behind the lower content. Keep the black background dominant.

### Icons

**Observed:** Small utilitarian symbols accompany card titles and benefit labels, usually 14px–18px, muted black on white or white on dark. Carousel chevrons use rounded 1.6px strokes; the language selector uses a tiny downward chevron. Ratings use small filled warm stars.

**Transfer:** Choose one restrained icon family, with filled miniature symbols for diagram categories and thin chevrons for navigation. Keep icons subordinate to text rather than giving every feature a colored badge.

## Section recipes

How recurring sections are built.

### First screen: Luminous horizon opening

**Observed:** The first screen layers Canvas, an oversized clipped Luminous field, an initial transparent Navigation, then a centered vertical content stack. A small white rating capsule leads into a two-line display headline occupying about two thirds of the window width; its second line is broader. The 60px serif headline is white, followed by a 640px-wide white support paragraph, one small proof line and Inline trial form. The stack starts after 160px top padding, with 16px–20px gaps. The glowing curved horizon ends well above the 722px section bottom, leaving pale space before the next stage. Within the first 900px the whole promise, explanation, proof and action are visible, along with the top of a 1120px-wide product demonstration starting around 722px; its tabs and photographic proof fall below the fold.

**Transfer:** Keep this as the default landing-page impression: a single luminous field, serif promise, narrow explanation and one actionable input or pill. A gradient orb supplies the main object if no equivalent product artwork exists. Product-detail openings instead use left-aligned detail-display copy and a large device scene; case-study openings use left-aligned display copy and staggered photography; dark technical openings center the same display role over Dotted night field.

**Avoid:** Do not replace the horizon with a small floating gradient blob beside the headline, add three competing actions, or turn the opening into an equal-size grid of cards.

**Text style:** `display` — Hedvig Letters Serif 400 · 60px/1.2 · tracking -0.03em

### Demonstration and moving proof

**Observed:** A 1120px × 630px product media frame with 24px corners and Demo-media shadow leads into a compact white pill tab bar 28px below it. The active tab is black. After a larger gap, portrait proof imagery runs sideways beyond the viewport.

**Transfer:** Use one large demonstration, a small number of named views and a moving proof strip. Keep the media's story visible without requiring tiny interface text to carry the pitch.

### Mechanism around a glow

**Observed:** Mechanism stage begins with a centered heading and a 448px support line, separated by 20px. After 64px, Process tags sit above two groups of Floating explanation cards. Three cards on either side flank the luminous object in a three-column composition; small muted pills label each side below.

**Transfer:** Map the new product's inputs and outcomes around one luminous object. Preserve the asymmetry of staggered card placement and the light center instead of drawing a rigid flowchart.

**Text style:** `heading` — Hedvig Letters Serif 400 · 42px/1.2 · tracking -0.03em

### Alternating capability stages

**Observed:** A heading and support line introduce broad White stages. Each stage pairs a roughly square Floating product conversation scene with vertically centered copy, a 26px feature-title, 16px gap to body-small, occasional short orange proof and a small Primary button. Visual and text sides alternate; core text padding is 56px. Detail-page versions use 580px-square visuals and detail-feature-title with detail-body, while dark technical versions use Dark feature stage.

**Transfer:** Give each stage a concrete user task. Alternate sides when useful, while keeping identical panel radii and matching text widths.

**Text style:** `feature-title` — Hedvig Letters Sans 400 · 26px/1.2 · tracking -0.02em

### Ecosystem marquee

**Observed:** A centered heading-large and compact support line introduce a clipped row of Integration tiles inside Mechanism stage. Tiles begin 48px below the introduction and move horizontally with 20px gaps.

**Transfer:** Translate this to integrations, compatible tools, supported workflows or other genuine ecosystem proof.

**Text style:** `heading-large` — Hedvig Letters Serif 400 · 48px/1.2 · tracking -0.025em

### Dark product chapter

**Observed:** Black stage introduces a contrasted product interaction in two columns. Charcoal chapter expands the argument into a large left-aligned heading-inverse, support, a white small action and a perspective analytical interface 56px below. Four small icon-led benefit blocks sit underneath.

**Transfer:** Use the dark treatment for the product's deepest or most consequential mechanism, and let one large product visual dominate it.

**Text style:** `heading-inverse` — Hedvig Letters Serif 400 · 48px/1.2 · tracking -0.03em

### FAQ stack

**Observed:** A centered heading-large and small secondary sentence sit 48px above FAQ rows in the 736px reading column. The section uses 96px vertical padding.

**Transfer:** Answer purchase and adoption uncertainty without turning the section into a dense knowledge base.

**Text style:** `heading-large` — Hedvig Letters Serif 400 · 48px/1.2 · tracking -0.025em

### Glow conversion and restrained footer

**Observed:** Specialized pages place Closing glow stage before the footer: centered closing-display, a narrow explanation and one action on peach-lavender light. Every ending then uses a 1120px-wide compact invitation row, footer-invitation at left with a secondary line 4px below and Primary button at right. A 1px rule has 48px margins. Below, the small mark and two trust seals occupy the left, while three 143px link columns with 40px gaps occupy the right. The footer has 64px vertical padding. The dark variant retains the geometry on black with inverse text and a white-at-10% rule.

**Transfer:** Close with a direct invitation and useful wayfinding. Place any real trust marks low in the left-hand space; keep the restrained scale even if the page previously used dramatic imagery.

**Text style:** `footer-invitation` — Inter 600 · 20px/1.4 · tracking -0.025em

### Case-study proof

**Only for:** case-study pages

**Observed:** A white strip contains three 32px-radius metric wells with 26px stat-number and muted captions. A second broad White stage pairs a short case title, challenge and solution labels, a few concise features and a small orange action with tall lifestyle photography. Small circular previous/next controls sit above the story.

**Transfer:** Write a compact account of problem, intervention and result. Keep metrics calm rather than inflating them to hero scale.

**Text style:** `detail-feature-title` — Hedvig Letters Sans 400 · 26px/1.3 · tracking -0.02em

### Related capabilities

**Only for:** product-detail pages

**Observed:** A centered heading and support introduce three white 28px-radius cards with 24px gaps. Each holds a muted visual well and a compact baseline with title at left and a light learn-more link at right.

**Transfer:** Use for adjacent product paths rather than adding another full-width feature chapter.

**Text style:** `heading` — Hedvig Letters Serif 400 · 42px/1.2 · tracking -0.03em

### Editorial night invitation

**Only for:** dark technical editorial sections

**Observed:** A 1280px × 495px black panel with 48px corners and a faint outline contains Dotted night field, a centered serif publication title, a short editorial promise, Newsletter capsule, reassurance and a member login link.

**Transfer:** Use a publication or ongoing-learning offer only when it is a real second conversion goal; preserve its distinct, intimate editorial scale.

## Page flow

**Storyline:** Promise → tangible demonstration → moving proof → mechanism and capabilities → deeper product argument → uncertainty reduction → compact invitation and wayfinding.

### Broad marketing landing page

1. **Promise** — Warm circular horizon, centered serif promise, proof and inline trial.
2. **Product demonstration** — Large media frame with small view tabs, followed by moving portrait proof.
3. **Mechanism** — A luminous center between inputs and outcomes on a white stage.
4. **Capability chapters** — Alternating broad white feature stages and an ecosystem marquee.
5. **Deeper product argument** — Black interaction stage followed by a charcoal analytical chapter.
6. **Objection handling** — Narrow three-row FAQ.
7. **Closing call** — Compact invitation, divider and spacious three-column footer.

**Transfer:** Use when introducing a product platform; adapt the number of arguments to the new product while retaining the luminous object, concrete demonstration and sideways proof device.

### Customer proof landing page

1. **Social proof promise** — Left-aligned serif introduction beside staggered portrait photography.
2. **Quantified proof** — Moving marks and a restrained three-number strip.
3. **Case study** — Challenge, solution and results beside lifestyle photography.
4. **Closing call** — Soft-glow conversion stage followed by the shared compact footer.

**Transfer:** Lead with people and outcomes, not technical architecture; keep the same typography and stage geometry.

### Specific product capability landing page

1. **Promise** — Split opening with a serif product name, device-in-hand visual and nested comparison card.
2. **Capability chapters** — Alternating square conversation scenes and concise feature explanations.
3. **Adjacent paths** — Three compact related-capability cards.
4. **Closing call** — Centered glow stage and shared footer.

**Transfer:** Go deeper on one user task; use proof near the first action and explain concrete interactions with consistent split stages.

### Technical category and ownership landing page

1. **Promise** — Centered white serif statement over a fading dot matrix on black.
2. **Product architecture** — Large system diagram followed by a centered explanatory statement.
3. **Capability chapters** — Dark raised split panels with editor and workflow scenes.
4. **Editorial invitation** — Outlined dotted subscription stage with an email capsule.
5. **Closing call** — Warm glow stage and inverse version of the shared footer.

**Transfer:** Use the dark theme for technical depth and control-oriented narratives, retaining the same serif-to-sans hierarchy and rounded-stage rhythm.

## Writing

Confident, conversational and product-literate. Editorial headlines make a clear promise while plain explanations describe what the product does and how a buyer benefits; proof is concrete rather than breathless.

**Do not copy:** Do not reuse Dialog's name, wordmark, partner assets, customer names, study attributions, proprietary product names, quotes or performance claims. Source numbers are examples of how to present verified proof, not claims available to a new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the buyer as you and your. Refer to the product by its name in explanatory sentences, and use direct imperatives for actions.
- **Rhythm:** Headlines use short clauses and deliberate full stops, often pairing a statement with an outcome. Support copy is one or two compact sentences; feature descriptions can be longer but remain a single small paragraph. Actions are two to four words.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the buyer's new capability, then extend its reach in a second clause. | 6–12 words | “Your brand agent. Everywhere your customers shop.” |
| Mechanism heading | Stack short imperatives with a memorable once/everywhere contrast. | 8–13 words | “Build your brand agent. Train it once. Deploy it everywhere.” |
| Capability heading | Describe a change from old friction to a new mode of working. | 4–9 words | “From quizzes to real conversations” |
| Supporting line | Explain a practical capability and remove an adoption objection. | 12–30 words | “Seamlessly connect your existing commerce platform — no custom development required.” |
| Proof caption | Number, outcome, comparison baseline and attribution. | 8–16 words | “+16.1% conversion vs a Typeform quiz (Karacare A/B test)” |
| Primary action | Short, literal next step without metaphor. | 2–4 words | “Book a demo”<br>“Try the simulator” |
| Closing invitation | A small direct question rather than another sweeping manifesto. | 3–5 words | “Ready to start?” |
| Editorial promise | Concrete evidence plus immediate usefulness; finish with a terse exclusion. | 12–20 words | “Real cases, verified numbers, and something you can act on Monday. Nothing else.” |

**Words and phrasing to use:** your; guide; control; real; recommend; connect; conversations; no custom development; once; everywhere

**Avoid:** revolutionary; unleash; supercharge; game-changing; limitless magic; excessive exclamation marks

**Rules:**

- Tie a feature to a recognizable buyer action instead of listing abstract capabilities.
- Place a claim's baseline and attribution next to the number.
- Let technical depth appear in concrete mechanisms and controls, not jargon-heavy hero text.
- Keep orange proof sentences short enough to read as a compact annotation.

## Do's and Don'ts

### Do

- Keep the opening serif at 60px, weight 400, with -0.03em tracking and a 920px headline measure.
- Use 40px and 48px radii for large stages, reserving 16px corners for small cards.
- Recur to a luminous orange focal object after the opening, supported by pale light and simple explanation cards.
- Keep action text at 14px/20px and use compact 40px–48px pill heights.
- Use a 448px measure for centered explanatory support and a narrower 736px column for FAQ.
- Make the sideways proof strip visibly clipped at its container edges.
- Let one dark chapter carry a full-size product demonstration, with white headings and muted secondary copy.
- Finish with the 20px compact invitation and three narrow footer link columns rather than another oversized headline.

### Don't

- Do not set the editorial serif in a heavy weight to imitate a bold SaaS headline.
- Do not distribute orange, blue, green and purple as equal marketing category colors; keep multicolor details inside product views.
- Do not apply 48px corners to every small element; floating explanation cards use 16px.
- Do not cover the gray canvas with strongly outlined cards or dense repeated drop shadows.
- Do not convert the floating capsule navigation into a solid full-width colored bar.
- Do not make explanatory body text uniformly black; preserve the clear secondary gray role.
- Do not render every media scene as a complete browser window; isolated conversation fragments are a key part of the light stages.
- Do not inflate case-study strip numbers to the 60px hero size; their 26px treatment is deliberately calm.

## Motion and responsive

### Motion

**Observed:**

- Actions declare .15s transitions with cubic-bezier(.4, 0, .2, 1) for color, surface and transform-related properties.
- Several pills declare hover scale 1.03; the subscription action declares scale 1.02. Footer links change to full black or full white on hover.
- Horizontal marquee animations are declared at 55s linear infinite, with the brands variant at 60s. A shimmer mask is declared at 30s linear infinite and an orb pulse at 6s ease-in-out infinite.
- The reading header changes from a broad initial row into a compact floating capsule cluster; core feature stages also use sticky positioning.

**Transfer:**

- Keep proof and ecosystem motion slow enough to read as ambient sideways drift.
- Carry the orb's subtle pulse into a gradient-based replacement rather than introducing bouncing illustrations.
- Keep the compact floating navigation available over both white and dark chapters.

**Unknown:**

- The exact orb canvas behavior and header morph choreography are not specified.
- Some hover filter declarations do not resolve to a usable filter value; focus-visible and active visual treatments are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 640px, 810px and 1024px.
- The opening headline uses 40px at the base size, 50px at an intermediate tier and 60px at the wide tier.
- Several centered chapter headings use 25px base text and left alignment before their desktop centered treatment; the dark analytical heading uses a 30px base size.
- The inline form switches between a stacked base layout and a joined horizontal capsule at the small breakpoint. Split stages use single-column base layouts.

**Transfer:**

- On narrow screens, retain the luminous horizon as the first visual impression but narrow the copy and stack the form action beneath its input.
- Stack split stages while keeping the visual and explanation together; reduce side padding before shrinking interface fragments into illegibility.
- Keep horizontal proof strips clipped and moving rather than compressing every portrait or integration tile into the width.
- Reflow the two-sided mechanism into a single reading sequence while keeping the glowing object between the explanatory groups.

**Unknown:**

- Exact narrow-screen navigation appearance, final mobile spacing and all small-screen media crops are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
