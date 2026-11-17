# WRITER — luminous work on black

## Overview

A theatrical enterprise style that pairs black space and rounded geometric sans-serif type with tactile, grainy color. Bright interface collages and warmly lit people make complex software feel concrete and human, while violet actions keep the otherwise restrained canvas purposeful. The default is dark and spacious; editorial company and pricing treatments switch to white, fine serif titles, and pastel panels.

### Essentials

- Headlines sound monumental without shouting: white Poppins at 64px/1, weight 500, -2px tracking, centered in an 800px-wide opening text block; section heads step down to 40px/1.2 with -0.02em tracking.
- The opening is a human-and-product stage rather than a floating dashboard: an 83px navigation, 140px hero top padding, a three-line promise, a 460×54px email/action capsule, and a 1050px-wide layered scene beginning beneath it.
- Actions are saturated islands: #5551ff rounded pills, 54px tall in the opening, with white 16px text; use 45px pills in navigation and 60px black/white pills in the closing call.
- Black owns the page; color lives inside the media: #000000 canvas, #1a1a1c resource band, #131315 closing band, and noisy violet, peach, pink, and mint light inside bounded illustrations rather than full-page rainbow washes.
- A tactile light field is a signature device: fine textile-like grain over soft multicolor gradients, with white interface cards layered in front. Every new landing page needs this treatment; if no interface exists, stage a concise output or process diagram against the same luminous backing.
- Proof has a human face and an oversized result: wide portrait-and-stat cards in a bleeding horizontal rail, followed elsewhere by calm three-column explanations. Keep the 1050px content stage and let selected proof media escape its edges.
- The ending resolves into a compact centered promise, paired contrasting actions, then a black directory footer with a ruled newsletter capsule; it is not a repeated hero illustration.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric violet | `#5551ff` | `--color-action` | action, accent | Primary actions, small active details, and light-field accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale periwinkle | `#e4e9ff` | `--color-lavender` | surface, action | Light exploration action on dark; highlighted pricing columns and editorial link cards. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-foreground` | text, surface, background | Headings on black, interface panels, closing light action; white canvas for editorial and pricing variants. |
| Email field mist | `#e8ebf0` | `--color-form` | surface | Opening email capsule behind the violet submit button. |
| Cool body gray | `#e4e7ed` | `--color-body` | text, border | Default card and technical supporting text on dark backgrounds; light editorial dividers. |
| Soft gray | `#d2d4d7` | `--color-support` | text | Large support lines, feature explanations, resource descriptions. |
| Directory gray | `#bdbdbd` | `--color-muted` | text, link | Footer secondary links. |
| Diagram edge | `#393b40` | `--color-edge` | border | Fine edges and internal rules on explanatory media. |
| Input charcoal | `#333333` | `--color-input` | surface, text | Newsletter field; long editorial body text on white. |
| Footer rule | `#2d2d2d` | `--color-rule` | border, surface | Newsletter rules and circular social backings. |
| Raised charcoal | `#1b1b1d` | `--color-card` | surface | Technical feature and stat cards. |
| Resource charcoal | `#1a1a1c` | `--color-resources` | background | Full-width editorial resource band. |
| Closing charcoal | `#131315` | `--color-closing` | background | Default final conversion band. |
| Near-black diagram panel | `#010101` | `--color-panel` | surface | Outlined explanatory carousel. |
| Stage black | `#000000` | `--color-canvas` | background, text | Default marketing canvas; also text and actions on light surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product landings | Action outline | `#4f4f4f` | `--color-outline` | border | Secondary documentation action outline. |
| technical evaluation sections | Plum charcoal | `#2d2932` | `--color-chart` | surface | Chart stages and cost-comparison stats. |
| technical product landings | Technical closing gray | `#1f2022` | `--color-technical-closing` | surface, background | Technical closing band and speaker attribution panel. |
| pricing pages | Pricing mist | `#f5f5f9` | `--color-pricing-base` | surface, border | Unhighlighted plan card and comparison column. |
| pricing pages | Comparison hairline | `#b6bece` | `--color-pricing-rule` | border | Comparison category dividers. |
| pricing pages | Lilac closing wash | `#ead6ff` | `--color-pricing-close` | background | Full-width pricing closing call. |
| company culture sections | Culture pink | `#ffcee8` | `--color-culture-pink` | surface | One of three flat illustrated principle cards. |
| company culture sections | Culture lilac | `#e6cdff` | `--color-culture-lilac` | surface | Second illustrated principle card. |
| company culture sections | Culture periwinkle | `#c5cdff` | `--color-culture-blue` | surface | Third illustrated principle card. |
| technical evaluation sections | Model mint | `#b1efdd` | `--color-mint` | accent | Model identity accent; mint also characterizes luminous technical artwork. |

## Typography

- **Poppins** — Default marketing headings, copy, navigation, actions, captions, and numerals. Geometric sans with circular counters and a friendly broad lowercase; medium display weights rather than heavy grotesk bold. Font stack: "Poppins", sans-serif.
- **CanelaDeck** (only for company editorial and pricing openings) — Light-theme primary titles. Refined high-contrast serif with expressive tapered forms. If unavailable, use **DM Serif Display**. 400; preserve open tracking and short titles. Font stack: "CanelaDeck", "DM Serif Display", Georgia, serif.
- **Graphik** (only for company editorial prose and people captions) — Long company narrative and small professional-role captions. Neutral, even-textured sans distinct from the rounder marketing face. If unavailable, use **DM Sans**. 400; retain the generous prose leading. Font stack: "Graphik", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 500 | 64px | 1 | -2px | fixed | Default opening promise, centered and broken into compact balanced lines. |
| closing-heading | Poppins | 500 | 44px | 1.25 | -0.02em | fixed | Centered final promise. |
| heading | Poppins | 500 | 40px | 1.2 | -0.02em | fixed | Main section heading and large standalone customer quotation. |
| card-heading | Poppins | 500 | 25px | 1.2 | -0.02em | fixed | Three-column editorial capability headings. |
| lead | Poppins | 400 | 20px | 1.6 | normal, features "clig" 0, "liga" 0 | fixed | Supporting copy below main headings. |
| footer-heading | Poppins | 600 | 20px | 31px | normal | fixed | Footer column titles and newsletter invitation. |
| resource-heading | Poppins | 500 | 18px | 1.2 | normal | fixed | Compact resource row titles. |
| body | Poppins | 400 | 16px | 1.6 | normal | fixed | Card paragraphs and explanatory technical copy. |
| eyebrow | Poppins | 500 | 16px | 1 | 0.1em | fixed | Primary uppercase section labels. |
| hero-action | Poppins | 500 | 16px | 1.15 | normal | fixed | Opening email capsule submit label. |
| action | Poppins | 600 | 16px | 1.6 | normal | fixed | Standalone technical actions. |
| closing-action | Poppins | 600 | 16px | 1.25 | normal, features "clig" 0, "liga" 0 | fixed | Contrasting final action pair. |
| footer-link | Poppins | 400 | 16px | 1.2 | normal | fixed | Footer directory links. |
| navigation | Poppins | 600 | 14px | 1.5 | normal | fixed | Navigation links and compact header action. |
| eyebrow-small | Poppins | 500 | 13px | 1.6 | 1px, uppercase, features "clig" 0, "liga" 0 | fixed | Editorial, proof, and platform section labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company editorial pages | editorial-display | CanelaDeck | 400 | 70px | 1.05 | normal | fixed | Centered company title. |
| technical product landings | technical-display | Poppins | 500 | 64px | 65px | -0.02em | size clamp(36px, 5vw, 64px) | Two-line technical product opening. |
| technical evaluation landings | model-display | Poppins | 500 | 64px | 1.2 | -0.02em | fixed | Short model or technology promise above a monumental graphic. |
| quantified technical proof | stat | Poppins | 500 | 64px | 1 | -0.02em | fixed | Dominant result inside stat tiles. |
| pricing pages | pricing-display | CanelaDeck | 400 | 64px | 1 | normal | fixed | Short pricing title. |
| pricing pages | pricing-heading | Poppins | 400 | 35px | 50px | normal | fixed | Comparison and FAQ section titles. |
| scroll-linked product demonstrations | step-heading | Poppins | 400 | 30px | 34px | normal | fixed | Left-side active chapter in the sticky demonstration. |
| company editorial pages | editorial-heading | Poppins | 500 | 28px | 1 | normal | fixed | Prose chapter and culture headings. |
| technical product landings | technical-card-heading | Poppins | 500 | 24px | 1.25 | normal | fixed | Feature and assurance card headings. |
| pricing pages | plan-name | Poppins | 600 | 24px | 1.5 | 3px, uppercase | fixed | Plan names above descriptive copy. |
| pricing pages | faq-question | Poppins | 500 | 22px | 1.5 | normal | fixed | Questions in the light-theme FAQ. |
| company editorial pages | editorial-body | Graphik | 400 | 20px | 1.8 | normal | fixed | Long-form narrative in narrow columns. |
| technical product landings | technical-label | Poppins | 600 | 16px | 1 | 3px, uppercase | fixed | Widely tracked technology chapter labels. |
| pricing pages | comparison | Poppins | 400 | 14px | 25px | normal | fixed | Dense comparison rows. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The default headline is medium, not bold; negative tracking intensifies at the opening scale. Small labels reverse that relationship with positive tracking.
- Keep Poppins in paragraphs as well as headings on dark pages. The serif and Graphik combination belongs to the light editorial variant, not the default landing page.
- Use the technical-display viewport formula only for that opening variant; the default display retains its own tighter tracking.

## Layout

**Density:** Airy at the section scale and compact inside product illustrations; long black intervals make each bright object read as a deliberate stage.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight technical card gutters. |
| 12px | Paired-action gap and title-to-copy gap in demonstration steps. |
| 16px | Heading-to-support spacing and regular internal text rhythm. |
| 24px | Action side padding and technical stat content gaps. |
| 26px | Opening headline-to-form gap. |
| 27px | Three-column editorial card gutters. |
| 30px | Customer rail gutters and stacked full-width feature scenes. |
| 40px | Section introduction-to-media separation. |
| 60px | Technical chapter top and bottom padding; technical introduction-to-chart gap. |
| 100px | Major band padding and editorial block separation. |
| 112px | Resource band vertical padding. |
| 140px | Default opening top padding and light-theme FAQ padding. |

### Containers and grids

- **marketing stage**: max width 1080px · side padding 15px. Centered outer container yielding a 1050px usable stage at desktop.
- **opening text**: max width 800px. Centered headline block, narrower than the image below.
- **editorial triad**: 3 columns · gap 27px. Three equal 332px columns across the main stage; media, label, title, paragraph, then action.
- **feature pairs**: max width 1050px · 2 columns · gap 16px. Two broad media tiles per row; roughly 518px each.
- **technical triad** (only for technical product landings): max width 1020px · 3 columns · gap 8px. Closely fitted dark cards beneath spacious technical introductions.
- **narrative column** (only for company editorial pages): max width 693px. Company prose beside a 273px facts rail; later prose recenters in a 685px measure.
- **plan pair** (only for pricing pages): max width 945px · 2 columns · gap 24px. Two equal 460px cards centered beneath the pricing introduction.
- **wide demonstration** (only for scroll-linked product demonstrations): max width 1460px · 2 columns · gap 48px · side padding 24px. 418px step narrative beside a 926px sticky visual at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | opening controls | 50px |
|  | standalone actions | 60px |
|  | compact actions | 82px |
|  | media panels | 12px |
|  | technical cards | 16px |
|  | social controls | 50% |
| technical evaluation sections | chart stage | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| scroll-linked product demonstrations | violet demonstration glow | `rgba(85, 81, 255, 0.12) 0px 24px 80px 0px` | Subtle illumination under the sticky media panel, not a general card shadow. |

### Surfaces

#### Black stage · level 0

**Use:** Default marketing page canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Large uninterrupted black areas connect sections; no page-wide gradient.

**Transfer:** Keep the strongest colors within bounded visual stages.

#### Outlined explanation · level 1

**Use:** Diagram and descriptive carousel.

**CSS:** `background: #010101; border: 1px solid #393b40; border-radius: 12px; overflow: hidden`

**Observed:** A broad nearly black panel carries luminous art on the left and a compact explanation rail on the right.

**Transfer:** Use one coherent diagram rather than a grid of unrelated icons.

#### Dark card · level 1

**Use:** Technical feature explanations and proof tiles.

**CSS:** `background: #1b1b1d; border-radius: 16px; box-shadow: none`

**Observed:** Subtle tonal separation from black without a bright outline.

**Transfer:** Keep the card subordinate to its title or number.

#### Resource band · level 0

**Use:** Editorial resource collection.

**CSS:** `background: #1a1a1c; padding: 112px 0px`

**Observed:** A full-width tonal change, not a floating rounded container.

**Transfer:** Use a single broad content-rich band to change pace.

#### Closing band · level 0

**Use:** Default closing conversion promise.

**CSS:** `background: #131315`

**Observed:** 397px tall with a centered narrow headline and no illustration.

**Transfer:** Resolve the visual story into a short line and contrasting actions.

#### White editorial canvas · level 0

**Only for:** company editorial and pricing pages

**Use:** Long narrative and decision-oriented pages.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Pastel islands replace the dark page's luminous media; the footer remains black.

**Transfer:** Use the light variant as a complete page treatment, not alternating every section.

#### Plan mist · level 1

**Only for:** pricing pages

**Use:** Entry plan card.

**CSS:** `background: #f5f5f9; border: 1px solid #f5f5f9; border-radius: 16px`

**Observed:** The expanded plan changes fill to pale periwinkle while retaining equal dimensions.

**Transfer:** Highlight scope through color rather than scaling one card above its neighbor.

#### Pastel link panel · level 1

**Only for:** company editorial pages

**Use:** Closing resource triad.

**CSS:** `background: #e4e9ff; border-radius: 12px; padding: 30px 25px`

**Observed:** Three equal cards with a small graphic, heading, paragraph, and bottom link.

**Transfer:** Use quiet flat color instead of the dark theme's light-field collage.

#### Culture panels · level 1

**Only for:** company culture sections

**Use:** Illustrated principles.

**CSS:** `background: #ffcee8; padding: 13px 16px 30px 17px`

**Observed:** Three 339×544px flat rectangles with pink, lilac, and periwinkle fills, 16px gutters, large square illustrations above prose.

**Transfer:** Give each principle its own simple symbolic illustration; preserve the flat poster-like treatment.

#### Chart stage · level 1

**Only for:** technical evaluation sections

**Use:** Comparison diagrams.

**CSS:** `background: #2d2932; border-radius: 8px; overflow: hidden`

**Observed:** Wide 1020px plotting stages with fine axes and restrained violet or mint emphasis.

**Transfer:** Simplify the chart to one comparison and a clear dominant result.

#### Technical final band · level 0

**Only for:** technical product landings

**Use:** Closing action pair.

**CSS:** `background: #1f2022; padding: 100px 24px`

**Observed:** Centered heading with 48px to a violet and white action pair.

**Transfer:** Retain the darker technical page's concise close.

#### Lilac final band · level 0

**Only for:** pricing pages

**Use:** Final pricing conversion call.

**CSS:** `background: #ead6ff; padding: 100px 0px; color: #000000`

**Observed:** 357px full-width band with a regular-weight 44px title, followed after 30px by black and outlined 72px actions.

**Transfer:** Use this warm light close for decision pages, not the ordinary dark landing.

## Components

### Navigation

**Use:** Persistent global wayfinding.

**CSS:** `height: 83px; display: flex; align-items: center; justify-content: space-between; padding: 0px 25px; background: #000000; color: #ffffff`

**Text style:** `navigation` — Poppins 600 · 14px/1.5

**Observed:** Compact white identity at left, links and small downward triangles grouped at right, then login and the violet compact action. Light pages invert the logo and text onto a white translucent bar; no heavy enclosing card.

**Transfer:** Use a compact original wordmark with equivalent visual weight.

### Primary button

**Use:** Default opening conversion submit.

**CSS:** `height: 54px; padding: 0px 28px; background: #5551ff; color: #ffffff; border-radius: 50px`

**Text style:** `hero-action` — Poppins 500 · 16px/1.15

**Observed:** Sits flush against the right end of the email capsule. Standalone technical variants use 10px 24px padding, 60px radius, a 1px violet border, and the action recipe; compact header variants use 14px text and a 45px height.

**States:** Declared: hover background-color #2e2ae8; border-color #2e2ae8.

**Transfer:** Keep one short conversion verb phrase; do not widen it with an explanatory sentence.

### Email capsule

**Use:** Low-friction opening conversion.

**CSS:** `display: flex; align-items: center; width: 460px; height: 54px; background: #e8ebf0; border-radius: 50px`

**Observed:** A borderless input fills the left portion with 25px horizontal inset; Primary button completes the capsule on the right. The form follows the headline directly, with no separate support paragraph.

**Transfer:** Use one meaningful field only; preserve the joined silhouette.

### Closing action pair

**Use:** Final conversion choice.

**CSS:** `display: flex; justify-content: center; gap: 12px; flex-wrap: wrap`

**Text style:** `closing-action` — Poppins 600 · 16px/1.25

**Observed:** One black pill with white text and one white pill with black text; both 60px tall with 20px 24px padding and 60px radius. The white action receives the stronger visual emphasis against the charcoal band.

**States:** Declared: hover black action background-color #4a4a4a and color #ffffff; white action background-color #828282 and color #ffffff.

### Editorial capability column

**Use:** Explain the platform or supporting capabilities.

**CSS:** `display: flex; flex-direction: column; color: #ffffff`

**Text style:** `card-heading` — Poppins 500 · 25px/1.2 · tracking -0.02em

**Observed:** 332×187px image above a tiny tracked category label, title, 16px body, and a violet arrow-led pill. Three columns sit directly on black rather than on raised cards.

**Transfer:** Make the picture carry evidence: a diagram, document, or output rather than decorative stock art.

### Newsletter capsule

**Use:** Footer subscription invitation.

**CSS:** `display: flex; align-items: center; height: 55px; border-radius: 72px`

**Observed:** A charcoal input with 27px left inset and a violet 150px arrow submit overlap into one continuous capsule. It sits beside the newsletter title inside a 136px band with 1px dark rules and 35px vertical padding.

**Transfer:** Include an accessible field label and arrow-button name without changing the spare appearance.

### Footer directory link

**Use:** Secondary navigation in the closing directory.

**CSS:** `color: #bdbdbd; padding: 9px 0px`

**Text style:** `footer-link` — Poppins 400 · 16px/1.2

**Observed:** Four directories follow a circular identity mark; category titles use footer-heading. Groups have deliberate breaks before conversion or secondary links.

**States:** Declared: hover color #ffffff.

### Secondary button

**Only for:** technical product landings

**Use:** Documentation beside a conversion action.

**CSS:** `height: 54px; padding: 10px 24px; border: 1px solid #4f4f4f; border-radius: 60px; color: #ffffff; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Poppins 600 · 16px/1.6

**Observed:** Transparent outlined action placed before the filled action with a 12px gap.

**States:** Declared: hover opacity 0.85.

### Technical feature card

**Only for:** technical product landings

**Use:** Compact capability and assurance explanations.

**CSS:** `background: #1b1b1d; border-radius: 16px; padding: 51px 33px 55px 31px; color: #ffffff`

**Text style:** `technical-card-heading` — Poppins 500 · 24px/1.25

**Observed:** Small white outline icon above a left-aligned heading, followed by body copy. Equal-height cards are tightly grouped in threes without separate action footers.

**Transfer:** Use one clear capability per card and a simple literal icon.

### Stat tile

**Only for:** quantified technical proof

**Use:** Make a small set of results immediately scannable.

**CSS:** `background: #1b1b1d; border-radius: 16px; padding: 36px 32px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `stat` — Poppins 500 · 64px/1 · tracking -0.02em

**Observed:** Small identity or symbol, dominant number, then a short explanation. Cost-comparison variants use plum charcoal and 32px padding.

**Transfer:** Use real verified results; keep units visually attached to the number.

### Plan card

**Only for:** pricing pages

**Use:** Compare two levels of adoption.

**CSS:** `background: #f5f5f9; border: 1px solid #f5f5f9; border-radius: 16px; padding: 28px 40px 52px; width: 460px; display: flex; flex-direction: column`

**Text style:** `plan-name` — Poppins 600 · 24px/1.5 · tracking 3px · uppercase

**Observed:** Plan name, audience description, black pill, brief trial note where relevant, bold included-features lead, then checkmarked list. The expanded plan has pale periwinkle fill; both use black actions and share top-block alignment.

**Transfer:** Keep the audience distinction explicit and comparison columns continuous below.

### FAQ reading panel

**Only for:** pricing and technical evaluation pages

**Use:** Detailed objection handling without a pile of accordions.

**CSS:** `display: flex; justify-content: space-between; gap: 40px`

**Text style:** `body` — Poppins 400 · 16px/1.6

**Observed:** Narrow left index and wider right reading column. The light variant indexes categories and uses 22px questions; the dark variant indexes individual questions and uses 20px medium links. The pricing reading area is 520px tall and internally scrollable, with 45px between answers.

**Transfer:** Use an index only when the answers justify a reading panel; make the active topic clear.

## Imagery and graphics

### Grain-lit product collage

**Use:** Signature opening scene and major product demonstration.

**Observed:** White software cards overlap a softly multicolored textile-like backing: violet at the edges, peach and pink in the middle, mint highlights. In the opening, a waist-up cutout portrait interrupts the backdrop and sits between two stacks of task cards. The 1050px-wide scene begins after the form and continues below the fold; later examples use tilted overlapping interfaces within a rounded stage.

**Transfer:** Show the new product's own task and output. If a polished interface is unavailable, create two legible white output cards and a short process list around a well-lit person or meaningful product object; keep the grain-lit backing as the recognizable device.

**Build:** Use a rounded 1050px-wide clipped stage. Layer broad elliptical radial gradients in rgba(85,81,255,0.7), rgba(255,150,170,0.65), rgba(255,200,120,0.7), and rgba(110,225,195,0.55), with 60–100px blur and uneven overlapping positions. Add an SVG fractalNoise layer plus a fine repeating diagonal mesh at low opacity for woven grain. Place crisp white rounded interface cards in front; tilt selected cards about 6 degrees and let the portrait rise slightly above the backing. Match the soft light rather than exact gradient stops.

### Luminous process diagram

**Use:** Explain connected or cyclical work inside Outlined explanation.

**Observed:** A thin pale lavender infinity path, black circular stops, and small arrows sit over a dark grainy cloud of blue-violet, pink, and green. A small lavender task label attaches to the route; the right rail stays mostly black and typographic.

**Transfer:** Use a loop, branching route, or sequence appropriate to the product; the light should explain continuity, not become an unrelated wallpaper.

**Build:** Draw one SVG path with no fill and a 2px pale-periwinkle stroke, then add circular black nodes and tangent arrowheads. Behind it place blurred translucent violet, coral, and mint ellipses with a dark central vignette and an SVG noise overlay. Reserve about two thirds of the panel for this art and one third for descriptions.

### Human proof rail

**Use:** Customer outcome cards.

**Observed:** 488×332px portrait composites use muted charcoal, moss, or mauve backings, white customer identity, a large result or short quote at left, and a cutout person at right. Fine radiating lines fan out behind the person. Three cards cross the viewport with 30px gutters; a right-edge dark fade signals more content.

**Transfer:** Use real customer portraits and substantiated results; in their absence, use a named speaker and a concrete qualitative quote rather than fabricated metrics.

**Build:** Create a flat muted-color rounded rectangle, position a softly lit cutout portrait at the lower right, and clip it to the card. Draw a fan of thin radial SVG lines behind the silhouette in low-opacity black or white. Keep the result on a clear left area, identity at top, and speaker attribution near the bottom.

### Output montage

**Use:** Wide narrative benefit scenes.

**Observed:** Broad dark-charcoal rounded panels combine a short left text column, a centered person, and oversized white product/output panels spilling toward the right. Generated documents and reports give the scene a collage-like depth without heavy drop shadows.

**Transfer:** Stage one task and its finished artifacts, rather than filling the panel with a complete tiny application.

### Technical identity sculpture

**Only for:** technical evaluation landings

**Use:** Memorable technology identifier below the opening actions.

**Observed:** An enormous mint two-character identifier has granular texture and a vertical fade to black at its lower edge. It occupies much of the lower first screen, with no surrounding card.

**Transfer:** Use a short original model identifier or a similarly simple geometric emblem; keep it subordinate to the readable opening headline.

**Build:** Render the identifier as outlined SVG text or paths around 390px high at desktop, use a mint-to-black vertical fill, and clip a fine SVG noise texture to the letters. Fade the bottom with a black gradient mask; use a roughly 27vw artwork height.

### Technical chart artwork

**Only for:** technical evaluation sections

**Use:** Capability, endurance, cost, and comparison proof.

**Observed:** Wide plum-charcoal chart panels use thin gray axes, mint highlighted marks, and restrained white labels. One endurance diagram uses a violet-to-periwinkle segmented timeline with small white event cards. A comparative bar chart instead appears as a white sheet inside a textured violet/blue backing.

**Transfer:** Preserve the quiet plotting structure and one highlighted series; choose the chart that makes the new product's verified evidence simplest.

### Governance orbit and landscape pair

**Only for:** technical governance landings

**Use:** Opening systems metaphor and before/after explanation.

**Observed:** The opening shows thin white concentric arcs across black, a white outline shield above them, and small gray system-icon discs on radial stems. A later pair contrasts a grayscale broken rocky span with a continuous rocky landscape under a grainy blue-green luminous sky.

**Transfer:** Use spare line geometry to express oversight; for a before/after story keep the same photographic terrain and change only the continuity and light.

**Build:** For the orbit, draw three broad SVG elliptical arcs with 2px white strokes and fade their ends into black. Place a small outline shield at the upper center and four gray circular icon nodes below the arcs on radial hairlines. For the landscape, use matched rocky silhouettes; apply grayscale to the obstructed version and a blue/mint grain-gradient sky to the resolved version.

### People capsules

**Only for:** company editorial pages

**Use:** Opening team ribbon and founder, leadership, and advisor groups.

**Observed:** Head-and-shoulder cutouts sit in touching horizontal oval capsules on white. The opening ribbon is a tight two-row mosaic of monochrome faces on lilac. Larger people groups use color portraits, pale lavender or blush backing, centered name and compact role captions, then tiny circular social icons.

**Transfer:** Keep consistent framing and background treatment across a group; use fewer portraits rather than changing image styles mid-row.

### Icons

**Observed:** Mostly small white outline symbols, commonly 24px, above technical card headings. Directional arrows are simple and often lead exploration labels; carousel arrows sit in 40px circles. Social glyphs sit in dark circles; people-grid social circles are much smaller.

**Transfer:** Choose thin, plain outline icons with consistent visual weight, not filled multicolor illustrations. Reserve colored service marks for meaningful product integrations.

## Section recipes

How recurring sections are built.

### First screen: Human product stage opening

**Observed:** Black stage behind a persistent 83px Navigation. The centered opening content begins with an uppercase eyebrow around 140px from the top; the display headline occupies an 800px measure and three balanced lines at 64px/1, followed after 26px by Email capsule with Primary button. There is no separate explanatory paragraph in this default opening. After roughly 55px, a 1050px-wide Grain-lit product collage enters: textured backing behind a central human cutout, white task panels in front at both sides. Within the first 900px the complete headline and form are visible, plus the portrait and substantial upper portions of both task stacks; the lower artwork and trust strip continue below the fold.

**Transfer:** Write a promise specific enough to carry the opening without another paragraph, then stage a person or product object between a request and a finished output. Keep the textured light and legible white artifacts even without elaborate source media. Technical landings use a two-line technical-display title, support copy and outlined/filled actions before an orbit or identifier graphic; company and pricing openings use white canvas and serif titles instead.

**Avoid:** Do not turn the default first screen into a left-text/right-dashboard split, add a separate oversized support paragraph, or shrink the media into a small centered thumbnail.

**Text style:** `display` — Poppins 500 · 64px/1 · tracking -2px

### Centered capability introduction

**Observed:** Eyebrow above a heading, 10–16px separation between label and title, 16px to the lead paragraph, then about 40px to media. Most are centered; explanatory chapters can align left while retaining the same type relationships.

**Transfer:** Use one outcome-focused title and one concise paragraph; put detail in the visual or cards rather than extending the intro.

**Text style:** `heading` — Poppins 500 · 40px/1.2 · tracking -0.02em

### Explanatory carousel

**Observed:** Outlined explanation spans the 1050px stage. Luminous process diagram dominates the left; a roughly 287px descriptive rail on the right contains small dot controls, a colored category tab, short heading, paragraph, and two ruled metadata groups. Active and inactive dots are 12px circles.

**Transfer:** Use the rail for the currently highlighted step and show how it belongs to the larger system.

### Paired feature gallery

**Observed:** A centered introduction leads to two rows of broad media tiles, approximately 518px wide with a 16px horizontal gap and 28px row separation. Charcoal header portions contain small icons and centered titles; lower portions contain white interfaces over grainy color.

**Transfer:** Use this for a small set of visually demonstrable capabilities, with each image showing a different useful output.

### Bleeding human proof

**Observed:** Centered eyebrow and heading remain on black; the Human proof rail escapes the content container. Cards have 30px gaps and text case-study links underneath; circular previous/next controls sit below at the left.

**Transfer:** Let genuine people and outcomes interrupt the interface-heavy rhythm.

### Editorial capability triad

**Observed:** A left-aligned small eyebrow and two-line heading introduce three Editorial capability columns, separated by 27px. Images are equal-height evidence thumbnails; actions align near the bottoms of their columns.

**Transfer:** Explain supporting technology or trust with three complementary forms of evidence, not three duplicate benefit claims.

### Resource split

**Observed:** Resource band holds a centered introduction, then two roughly 509px columns. The left is a large featured learning image and caption; the right is four compact image/title/body/link rows. A slender vertical divider separates the columns.

**Transfer:** Offer one substantial next step plus a few narrower resources; retain the difference in scale.

### Compact closing promise

**Observed:** Closing band centers a 540px-wide closing-heading inside a 700px wrapper, with 86px top and 105px bottom padding. Closing action pair follows after 36px. There is no extra art. Technical final band and Lilac final band are scoped alternatives.

**Transfer:** End with an invitation that restates the outcome in fewer words, then offer the two natural next actions.

**Text style:** `closing-heading` — Poppins 500 · 44px/1.25 · tracking -0.02em

### Directory and newsletter ending

**Observed:** A black footer follows every page type. Inside the 1050px stage, a circular identity mark sits beside four directories; the upper area has 80px top and bottom padding. Footer directory links sit below white footer-heading titles. The Newsletter capsule occupies the right half of a ruled band while its invitation sits left. A compact bottom row contains copyright, circular social marks, and widely tracked uppercase privacy/legal links.

**Transfer:** Retain this information-rich ending even on light pages; use the new product's own compact identity mark rather than an oversized decorative sign-off.

### Evidence chapter

**Only for:** technical evaluation landings

**Observed:** A centered widely tracked technical-label precedes a 40px heading and 16px body copy; 60px below is a 1020px-wide Chart stage. Selected chapters add a three-card Stat tile row underneath.

**Transfer:** Choose a small number of verifiable comparisons; let the chart explain the claim instead of decorating an unsupported superlative.

**Text style:** `heading` — Poppins 500 · 40px/1.2 · tracking -0.02em

### Sticky demonstration

**Only for:** technical product walkthroughs

**Observed:** A wide left-aligned chapter heading leads to a two-column scene: 418px narrative steps at left and a 926×529px sticky panel at right with a subtle violet shadow. Steps are separated by 162px; the active chapter is bright while inactive chapters dim to 0.3 opacity. The bright interface is framed by textured pastel light.

**Transfer:** Use this only when there are distinct visual states to demonstrate; on narrow screens pair each narrative with its own readable visual.

**Text style:** `step-heading` — Poppins 400 · 30px/34px

### Large quotation

**Only for:** technical product landings

**Observed:** A centered customer quote uses the 40px heading recipe across an 850px measure, followed by a compact rounded attribution panel containing a portrait, name, role, and customer identity.

**Transfer:** Let one credible quote stand alone rather than compressing it into another card grid.

**Text style:** `heading` — Poppins 500 · 40px/1.2 · tracking -0.02em

### Company editorial sequence

**Only for:** company editorial pages

**Observed:** White canvas opens with editorial-display and a two-row People capsules ribbon. A 693px prose column shares the stage with a 273px facts rail. People groups center on the page, followed by a 685px centered narrative column, Culture panels, a large black hiring capsule, then a pastel resource triad.

**Transfer:** Adapt the mix to an organization's own story: people, factual context, principles, and an onward action. Keep capsule portraits and flat pastel posters distinct from product imagery.

**Text style:** `editorial-heading` — Poppins 500 · 28px/1

### Pricing comparison

**Only for:** pricing pages

**Observed:** Pricing-display and a short support line precede the equal Plan card pair. Below the trust line, a comparison table uses a broad left feature column and two 236px colored result columns, 39px typical rows, and category hairlines. The result fills continue down the entire table; top and bottom corners round only at its ends.

**Transfer:** Group features into meaningful decision categories and preserve the plan colors throughout the table.

**Text style:** `pricing-heading` — Poppins 400 · 35px/50px

### Reading FAQ

**Only for:** pricing and technical evaluation pages

**Observed:** A left-aligned title leads into FAQ reading panel: index at left and full answers at right, not collapsed accordion bars. Technical pages use black with light text; pricing uses white and a category index.

**Transfer:** Choose categories or questions as the index according to the content volume, and keep answer text genuinely useful.

## Page flow

**Storyline:** Promise → tangible product or organizational proof → focused capability chapters → trust and decision support → appropriate next action → directory and subscription.

### Broad marketing landing: connect a product promise to useful work and business impact

1. **Promise** — Centered headline and joined email action over a human/interface stage.
2. **Social proof** — Quiet enterprise trust line and logo ribbon.
3. **Product explanation** — Luminous system diagram, full-width workflow example, then paired feature media.
4. **Outcome proof** — Bleeding portrait-and-result rail.
5. **Capability chapters** — Wide human/output montages, then three evidence-led capability columns.
6. **Enablement** — Split featured learning resource and compact editorial rows.
7. **Closing call** — Compact dark promise and contrasting actions.
8. **Directory** — Black footer, ruled newsletter capsule, social and legal row.

**Transfer:** Choose chapters that fit the new product; preserve the contrast between luminous demonstrations, human outcomes, and quiet explanatory text.

### Company editorial: establish credibility through people, substance, and principles

1. **Promise** — White serif title with capsule portrait mosaic.
2. **Context** — Long-form narrative with a narrow facts sidebar.
3. **Credibility** — Founder, leadership, investor, and advisor groups with consistent capsule framing.
4. **Purpose** — Centered prose and a three-color illustrated principle row.
5. **Onward action** — Large black hiring capsule and three pastel resource links.
6. **Directory** — Shared black newsletter footer.

**Transfer:** Replace organizational facts with the new organization's own relevant evidence; use this light editorial mode only for narrative pages.

### Technical evaluation: make performance and control legible

1. **Promise** — Centered sans title, support line, paired docs/demo actions, monumental mint identifier.
2. **Quantified proof** — Three large numerical tiles.
3. **Evidence chapters** — Repeated heading-and-chart stages for capability, endurance, cost, and neutrality.
4. **Flexibility** — Two-by-two interface gallery.
5. **Trust** — Three technical assurance cards with a centered exploration action.
6. **Objection handling** — Question index beside detailed answers.
7. **Directory** — Transitions directly from FAQ into the shared black footer, without a separate closing conversion band.

**Transfer:** Use evidence-led chapters for any technically evaluated product; prefer measured comparison to a long generic feature list.

### Pricing: clarify fit and reduce purchase uncertainty

1. **Decision opening** — White serif title and two equal pastel plan cards.
2. **Social proof** — Compact trust line.
3. **Comparison** — Long feature matrix with continuous tinted plan columns.
4. **Objection handling** — Category-indexed reading FAQ.
5. **Closing call** — Full-width lilac invitation with black and outlined actions.
6. **Directory** — Shared black newsletter footer.

**Transfer:** Retain two clearly differentiated adoption paths when appropriate; do not invent extra tiers merely to fill a grid.

### Technical product landing: balance user autonomy with operational confidence

1. **Promise** — Centered two-line sans title, small support text, docs/demo pair, white orbital systems graphic.
2. **Problem and resolution** — Matched before/after landscape images and concise lists.
3. **Capability overview** — Three charcoal feature cards.
4. **Social proof** — Large centered quotation and speaker panel.
5. **Product demonstration** — Scroll-linked narrative and large sticky interface panel.
6. **Trust** — Certification ribbon, three assurance cards, single action.
7. **Closing call** — Charcoal band with violet and white actions.
8. **Directory** — Shared black newsletter footer.

**Transfer:** Lead with the human consequence of technical controls, then demonstrate the concrete mechanisms and independently support the trust claims.

## Writing

Confident, operational, and conversational. The language combines ambitious outcomes with concrete verbs, puncturing abstract enterprise language with short contrasts and everyday phrasing.

**Do not copy:** Do not reuse WRITER names, logos, product identifiers, proprietary artwork, customer identities, quotations, numerical results, evaluation claims, certifications, or company facts. Source examples illustrate cadence only; all new claims must be appropriate and substantiated for the new product.

- **Addressing the reader:** Address the reader as you and your team; use we for the maker when explaining an intentional choice. Let the product perform active verbs rather than describing it as a collection of tools.
- **Rhythm:** Short declarations and balanced contrasts lead; one or two explanatory sentences follow. Longer technical paragraphs name mechanisms and practical consequences. Periods, em dashes, and occasional contractions create authority without promotional exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A plain-language outcome or durable promise, often in two clauses. | 5–15 words | “Built for the long run.”<br>“Scale agentic work with enterprise governance” |
| Section headline | Challenge a familiar category, then replace it with a stronger behavior. | 6–15 words | “Not a tool you prompt. An agent you delegate to.”<br>“Eight hours. One goal. No hand-holding.”<br>“Say “go” instead of “no” |
| Supporting line | Begin with what the user does; explain what happens and why it matters. | 20–40 words | “Describe what you need and [Brand] executes from start to finish, delivering polished, on-brand work in minutes.” |
| Proof caption | Connect a result to a real unit of work, not a vague transformation claim. | 6–15 words | “Average cost per finished task. 52% less than the last generation.” |
| Primary action | Direct verb and explicit destination or commitment. | 2–4 words | “Request a demo”<br>“Explore docs”<br>“Contact sales” |
| Closing invitation | Bring a broad outcome into the reader's immediate future. | 6–10 words | “Your AI transformation journey starts today.” |

**Words and phrasing to use:** built for; your team; from start to finish; work; control; connect; scale; on-brand; not … but …; instead of; finished work

**Avoid:** revolutionary magic; unleash limitless possibilities; synergy; game-changing; frictionless everything; unqualified best-in-class

**Rules:**

- Pair every ambitious outcome with a mechanism, a product demonstration, or valid proof.
- Use short contrasts to distinguish behavior, not to attack a competitor.
- Keep uppercase labels categorical; let headlines remain sentence case.
- Write technical detail in ordinary language before naming specialized systems.
- Use action labels that reveal the next step and its level of commitment.

## Do's and Don'ts

### Do

- Keep the default opening at 64px Poppins, weight 500, with -2px tracking and balanced lines.
- Preserve the 1080px outer container and 15px side insets for the 1050px content stage.
- Use violet for compact actions and bounded light fields while black remains the dominant canvas.
- Keep the opening form a joined 460×54px capsule rather than two detached controls.
- Give bright interface artifacts a grainy, soft-color backing and enough scale to read as useful work.
- Distinguish tightly spaced technical triads at 8px from editorial triads at 27px.
- Use 1px charcoal hairlines in the footer and explanation panels, not bright separators.
- Carry light editorial pages back into the same black directory/newsletter ending.

### Don't

- Do not make the 64px headline weight 700; the round medium-weight form is central to the tone.
- Do not use a smooth full-bleed neon gradient as the page canvas; the colored material belongs inside visual stages.
- Do not put every column into a raised card: the editorial capability columns sit directly on black.
- Do not apply the serif opening to an ordinary dark product landing; it identifies the light editorial and pricing variants.
- Do not cover dark cards with broad generic shadows; the violet shadow belongs to the sticky demonstration alone.
- Do not turn the FAQ reading panel into a stack of giant rounded accordion bars.
- Do not give every button a rectangle or modest corner radius; preserve the 50px, 60px, and 82px pill constructions.
- Do not scatter multicolor filled icons through explanatory copy; use small restrained outline symbols.

## Motion and responsive

### Motion

**Observed:**

- The opening submit declares transform 0.2s and background-color 0.2s transitions; footer links declare color 0.2s.
- Technical secondary actions declare opacity 0.2s; final contrasting actions declare 0.3s ease-in-out transitions.
- The technical walkthrough uses a sticky media panel, with inactive narrative steps at 0.3 opacity and a bright active step.
- The explanatory carousel uses translated slide wrappers, dot pagination, and previous/next controls.

**Transfer:**

- Use the changing product scene to support the currently active narrative step; the muted inactive steps should remain secondary rather than appearing disabled.
- Keep interaction color changes subordinate to the still, luminous media composition.

**Unknown:**

- Autoplay behavior, complete scroll choreography, reduced-motion handling, and undeclared timing relationships are not established.

### Responsive

**Observed:**

- The technical product title declares clamp(36px, 5vw, 64px).
- Styles include many viewport breakpoints, including 768px, 992px, and 1024px; the visible layout described here is desktop.

**Transfer:**

- At narrower widths, keep the centered promise and joined conversion capsule readable; scale the collage as a single coherent scene instead of letting overlapping cards obscure the action.
- Stack paired galleries and triads when their text measure becomes cramped, retaining the distinction between bright imagery and black breathing space.
- For the wide demonstration, pair each step with its visual rather than retaining a 418px sidebar on a small screen.

**Unknown:**

- Exact mobile navigation, mobile spacing, stacking breakpoints, and carousel gestures are not established. These narrow-layout adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
