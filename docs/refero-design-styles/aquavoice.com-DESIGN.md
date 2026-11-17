# Aqua Voice — glass over water

## Overview

A light, unusually tactile software style, with pale grey expanses, luminous blue controls and floating desktop interfaces. Regular grotesk headlines feel conversational rather than corporate; fine borders and soft shadows give the product scenes an almost physical presence. It suits productivity tools and technical products that can demonstrate a concrete improvement, balancing spacious storytelling with denser proof and pricing.

### Essentials

- Headlines sound spoken and stay light: regular grotesk, 52px/1.08 with -0.01em tracking for section promises, not bold display typography.
- The opening is a product theatre, not a text-and-image split: a 1063px-wide translucent monitor frame contains a centered 56.7px headline above three overlapping dark app windows; the complete object and its actions fit within 900px.
- Controls look illuminated from inside: 48px-high pills, 14px 24px padding, 15px/20px medium labels, inset highlights and blue radial light. White and charcoal versions preserve the same optical construction.
- Most of the page is near-white #fafafa with blue confined to actions, small proof accents and atmospheric artwork. A #050608 demonstration chapter is a scoped contrast, not the default page theme.
- Interfaces float rather than sit flat: 16px window corners, layered long shadows, oversized horizontal demonstrations with adjacent panels peeking in. Every landing page needs a staged product scene; without finished media, use a faithful simplified interface with one legible task.
- Proof has two scales: a five-column testimonial mosaic with 288px cards and 8px gaps, and 60px regular-weight metrics over hairline rules. Carry both the human and measurable proof devices into new content.
- A watery closing atmosphere is a signature device: pale blue-grey ground, a soft blue orb and rippled reflection behind a left-aligned 56px closing line and five-column footer. Recreate the light and reflection with SVG when no rendered artwork is available.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button light | `#54a7fa` | `--color-button-light` | action | Radial light within blue conversion pills, fading through 78% and 24% opacity. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof blue | `#4288ff` | `--color-blue` | accent, link | Selected values, comparison bars and focus rings. |
| Light blue | `#67beff` | `--color-sky` | accent | Light end of comparison bars and atmospheric blue highlights. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal base | `#171717` | `--color-charcoal-base` | action | Lower end of charcoal action pills. |
| Display ink | `#202124` | `--color-hero-ink` | text | Headline inside the opening monitor. |
| Blue-black ink | `#292c3d` | `--color-ink` | text | Primary headings, card titles and technical text. |
| Charcoal light | `#2e2e2e` | `--color-charcoal-top` | action | Upper end of charcoal action pills. |
| Soft heading ink | `#3e4150` | `--color-heading` | text | Visible result of ink at 90% over the canvas; also used as a solid supporting text color. |
| Warm button ink | `#4b4b48` | `--color-button-ink` | text | White-button labels and selected billing controls. |
| Display support | `#62666b` | `--color-hero-copy` | text | Small support sentence inside the opening monitor. |
| Muted ink | `#686a76` | `--color-body` | text | Visible ink at 70% over paper for body copy. |
| Faded ink | `#7d7e89` | `--color-caption` | text | Visible ink at 60% over paper for testimonial text and low-emphasis details. |
| Card edge | `#e3e3e3` | `--color-rule` | border | One-pixel card outlines and dividers. |
| Soft ink edge | `#e9eaeb` | `--color-soft-edge` | border | Visible ink at 8% over paper, used around testimonial cards. |
| Water ground | `#eef2f5` | `--color-footer` | background | Lower atmospheric footer ground. |
| Warm grey band | `#f4f4f3` | `--color-band` | background, surface | Alternate demonstration chapter and code well. |
| Button warm base | `#f8f7f4` | `--color-button-base` | surface | Lower edge of white-button shading. |
| Paper canvas | `#fafafa` | `--color-canvas` | background | Default page ground and lower end of card gradients. |
| Button porcelain | `#fdfdfc` | `--color-button-paper` | surface | Middle stop of white-button shading. |
| White | `#ffffff` | `--color-white` | surface, text | Cards, highlights and text on blue or dark surfaces; navigation uses white at 72% opacity. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dark window | `#1c1c1c` | `--color-window` | surface | Dark interfaces within the product stage. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing sections | Pricing slate | `#526174` | `--color-price-copy` | text | Pricing notes and feature links. |
| pricing sections | Pricing secondary | `#647184` | `--color-price-caption` | text | Short plan descriptions and price qualifiers. |
| dark product demonstrations | Demonstration night | `#050608` | `--color-night` | background | Full-width dark demonstration chapter. |
| pricing sections | Pricing ink | `#303b49` | `--color-price-ink` | text | Plan names, prices and pricing headings. |
| device or platform showcases | Device ground | `#efefef` | `--color-device-ground` | surface | Inset physical-device showcase. |
| technical comparison sections | Correct term wash | `#cff2d3` | `--color-success-wash` | surface | Visible green term highlighting; source hue #6ce077 at 30% opacity. |
| technical comparison sections | Incorrect term wash | `#f2cfcf` | `--color-error-wash` | surface | Visible red term highlighting; source hue #e06c6c at 30% opacity. |

## Typography

- **PP Neue Montreal** — Marketing headings, paragraphs, navigation and captions; Book and Medium are complementary cuts of one family. Open, compact neo-grotesk with restrained regular-weight headlines and slightly firmer small labels. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Inter**. 400 and 500; preserve negative display tracking and avoid heavy headings. Font stack: "PP Neue Montreal", Inter, ui-sans-serif, system-ui, sans-serif.
- **Aqua CTA** — Conversion-button labels. Compact medium sans with a clear, practical interface voice. If unavailable, use **IBM Plex Sans**. 500 at 15px. Font stack: "Aqua CTA", "IBM Plex Sans", sans-serif.
- **Aqua Pricing Display** (only for pricing sections) — Plan names, prices and pricing lead. Medium sans with tightly tracked large numerals. If unavailable, use **Inter**. Font stack: "Aqua Pricing Display", "Inter", sans-serif.
- **Aqua Pricing Inter** (only for pricing sections) — Plan descriptions and feature notes. Small neutral sans text. If unavailable, use **Inter**. Font stack: "Aqua Pricing Inter", "Inter", sans-serif.
- **Inter** (only for billing controls) — Compact billing selector labels. Small utilitarian medium sans. Font stack: "Inter", sans-serif.
- **Fragment Mono** (only for developer integration sections) — Actual code examples, not decorative eyebrows. Even-width technical text with a loose reading line. Font stack: "Fragment Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| metric | PP Neue Montreal | 400 | 60px | 1 | -0.02em | fixed | Large time, speed or percentage proof. |
| stage-display | PP Neue Montreal | 400 | 56.7px | 1.065 | -0.0318em | fixed | Centered first-screen headline inside the product monitor. |
| proof-heading | PP Neue Montreal | 400 | 56px | 1.1 | normal | fixed | Centered human-proof heading, usually balanced onto two lines. |
| closing-heading | PP Neue Montreal | 400 | 56px | 1.2 | normal | fixed | Left-aligned closing promise above the atmospheric footer. |
| heading | PP Neue Montreal | 400 | 52px | 1.08 | -0.01em | fixed | Default section promise, capability lead and FAQ heading. |
| compact-metric | PP Neue Montreal | 400 | 24px | 1 | -0.02em | fixed | Comparison values within feature cards; percent signs shrink to 60% of the numeral size. |
| card-title | PP Neue Montreal | 500 | 20px | 1.25 | normal | fixed | Feature headings and demonstration captions. |
| body | PP Neue Montreal | 400 | 17px | 1.6 | normal | fixed | Main explanatory paragraphs. |
| stage-support | PP Neue Montreal | 400 | 15.1px | 1.5 | normal | fixed | One support sentence below the stage headline. |
| quote | PP Neue Montreal | 400 | 15px | 1.5 | normal | fixed | Testimonial content and compact supporting text. |
| nav | PP Neue Montreal | 500 | 15px | 1.2 | normal | fixed | Navigation labels. |
| button | Aqua CTA | 500 | 15px | 1.333 | normal | fixed | All pill conversion buttons. |
| footer-label | PP Neue Montreal | 500 | 13px | 1.5 | 0.06em, uppercase | fixed | Footer column headings, not a default eyebrow for every section. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| developer product pages | api-display | PP Neue Montreal | 400 | 80px | 0.95 | -0.03em | fixed | Centered technical-product hero, within 920px. |
| device or platform showcases | device-heading | PP Neue Montreal | 400 | 64px | 1.05 | -0.035em | size clamp(46px, 4.8vw, 64px) | Large two-line headline beside a physical device. |
| pricing sections | pricing-heading | Aqua Pricing Display | 500 | 52px | 1.08 | -0.03em | size clamp(36px, 4vw, 52px) | Centered pricing introduction. |
| pricing sections | price | Aqua Pricing Display | 500 | 52px | 1.154 | -0.04em | fixed | Large price numeral. |
| integration or use-case directories | directory-heading | PP Neue Montreal | 400 | 48px | 1.1 | normal | fixed | Left-aligned category headings. |
| pricing sections | currency | Aqua Pricing Display | 500 | 39px | 1 | -0.0533em | fixed | Smaller currency mark paired closely with a price. |
| integration or use-case directories | directory-title | PP Neue Montreal | 400 | 36px | 1.2 | normal | fixed | Large names within directory cards. |
| pricing sections | plan-title | Aqua Pricing Display | 500 | 24px | 1.25 | -0.02em | fixed | Plan names. |
| FAQ sections | faq-question | PP Neue Montreal | 500 | 21px | 1.3 | -0.01em | fixed | Accordion question text. |
| pricing sections | plan-copy | Aqua Pricing Inter | 400 | 14px | 1.5 | normal | fixed | Short plan description. |
| developer integration sections | code | Fragment Mono | 400 | 14px | 1.6 | normal | fixed | Readable multi-line code examples. |
| billing controls | billing | Inter | 500 | 12px | 1.333 | normal | fixed | Billing selector. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Use Book for large statements and Medium for small anchors. The Medium cut can be declared as weight 400 while visually functioning as 500.
- Tracking is not uniformly tight: body and testimonial headings are normal, default section headings are -0.01em, and larger technical or device headings tighten to -0.03em or -0.035em.
- Keep the first-screen headline subordinate to the physical product stage. Do not substitute the 80px developer hero for the default staged opening.

## Layout

**Density:** Airy section framing with tighter, internally organized product and proof groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Testimonial mosaic gutters and button icon-label gaps. |
| 12px | Card title-to-body spacing. |
| 20px | Section heading-to-support spacing and feature-grid gutters. |
| 24px | Default card padding, page-side safety padding and directory gutters. |
| 28px | Pricing card padding and FAQ vertical question padding. |
| 32px | Pricing grid gaps, metric group separation and navigation spacing. |
| 40px | Heading group-to-content separation and directory-card padding. |
| 64px | Header pill height and footer bottom breathing room. |
| 80px | Directory chapter spacing and large metric-column gutters. |
| 128px | FAQ section vertical padding. |
| 160px | Default major marketing-section breathing room. |

### Containers and grids

- **marketing container**: max width 1248px · side padding 24px. Centered wrapper yielding 1200px of content at desktop.
- **section intro**: max width 720px. Balanced centered heading and support copy; also the FAQ content width.
- **feature grid**: max width 1200px · 2 columns · gap 20px. Feature-card pairs; occasional unequal pair widths keep the grid from feeling mechanical.
- **testimonial wall**: 5 columns · gap 8px. Viewport-wide staggered columns, clipped beyond the side edges and faded toward the bottom.
- **footer columns**: max width 1200px · 5 columns · gap 24px. Plain categorized links beneath the atmospheric closing artwork.
- **pricing grid** (only for pricing sections): max width 1104px · 3 columns · gap 32px. Equal plan columns with a full-width business row underneath.
- **directory grid** (only for integration or use-case directories): max width 1120px · 3 columns · gap 24px. Equal cards with a partial last row left aligned.
- **developer content** (only for developer product pages): max width 952px · side padding 24px. Narrower proof, comparison, code and resource sections.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 9999px (pill) |
|  | feature and pricing cards | 24px |
|  | testimonials and app windows | 16px |
| device or platform showcases | device showcase | 32px |
| technical comparison sections | term highlights | 5px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | card lift | `rgba(0, 0, 0, 0.01) 0px 2px 3px 0px, rgba(0, 0, 0, 0.15) 0px 12px 28px -20px` | Very low lift beneath the main gradient cards. |
|  | light app float | `rgba(0, 0, 0, 0.05) 0px 2px 4px 0px, rgba(25, 40, 55, 0.18) 0px 24px 48px -16px, rgba(25, 40, 55, 0.18) 0px 56px 80px -32px` | Floating light application windows. |
| dark product demonstrations | dark app float | `rgba(0, 0, 0, 0.05) 0px 2px 4px 0px, rgba(0, 0, 0, 0.65) 0px 24px 48px -16px, rgba(0, 0, 0, 0.65) 0px 56px 80px -32px` | Dark application windows over the dark demonstration ground. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #fafafa`

#### Porcelain card · level 1

**Use:** Capabilities, plans, resources and technical proof.

**CSS:** `background: linear-gradient(155deg, #ffffff 12%, #fafafa); border: 1px solid #e3e3e3; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.01) 0px 2px 3px 0px, rgba(0, 0, 0, 0.15) 0px 12px 28px -20px`

**Observed:** Almost white at the top, barely greyer at the bottom; the edge is more important than the shadow.

**Transfer:** Use for self-contained content, with padding appropriate to the component rather than an identical inner layout everywhere.

#### Navigation glass · level 3

**Use:** Floating navigation pill.

**CSS:** `background-color: rgba(255, 255, 255, 0.72); background-image: linear-gradient(rgba(255, 255, 255, 0.34) 0px, rgba(0, 0, 0, 0) 62%); border-radius: 9999px; backdrop-filter: blur(44px) saturate(1.8); box-shadow: rgba(255, 255, 255, 0.92) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.4) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.05) 0px 0px 0px 0.5px inset, rgba(0, 0, 0, 0.03) 0px 1px 2px 0px, rgba(0, 0, 0, 0.12) 0px 10px 28px -12px`

**Observed:** The brand mark stands separately on the left; only the right navigation cluster is enclosed.

**Transfer:** Keep glass concentrated on chrome and controls, not every content card.

#### Warm demonstration band · level 0

**Use:** Alternate light product demonstration.

**CSS:** `background: #f4f4f3`

**Observed:** Subtle grey warmth separates a writing-focused demonstration from the paper sections.

**Transfer:** Use for a related capability chapter with light UI.

#### Water footer ground · level 0

**Use:** Atmospheric page ending.

**CSS:** `background: #eef2f5`

**Observed:** A pale cool transition behind the closing artwork settles into a flat footer ground.

**Transfer:** Blend the reflective scene into this ground so it feels continuous.

#### Night demonstration band · level 0

**Only for:** dark product demonstrations

**Use:** Contrast chapter for dark interfaces.

**CSS:** `background: #050608; color: rgba(255, 255, 255, 0.9)`

**Observed:** The whole chapter changes ground, including captions and metrics, while the core heading sizes remain unchanged.

**Transfer:** Keep this a concentrated immersive chapter.

#### Device plinth · level 1

**Only for:** device or platform showcases

**Use:** Physical hardware and cross-platform handoff.

**CSS:** `background: #efefef; border-radius: 32px; padding: 48px 64px 56px; box-shadow: #ffffff 0px 1px 0px 0px inset, #e3e3e3 0px 0px 0px 1px`

**Observed:** Text occupies the left, a realistically lit device the right.

**Transfer:** Stage a physical object or one substantial product artifact rather than a collage.

## Components

### Floating navigation

**Use:** Persistent desktop navigation.

**CSS:** `display: flex; align-items: center; gap: 32px; height: 64px; padding: 0px 8px 0px 32px; border-radius: 9999px`

**Text style:** `nav` — PP Neue Montreal 500 · 15px/1.2

**Observed:** Uses Navigation glass behind a compact right-hand pill. Three menu triggers have small down chevrons, followed by a direct pricing link and the Primary button. A separate brand mark aligns on the left of the 1200px header row.

**States:** Declared: hover menu text becomes black; focus-visible outline #4288ff solid 2px with 2px offset.

**Transfer:** Keep categories few and action-led; preserve the separate logo and capsule.

### Primary button

**Use:** Main conversion action and emphasized paid plan.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 14px 24px; border-radius: 9999px; color: #ffffff; background: radial-gradient(65% 105% at 50% 78%, #54a7fa 0%, rgba(84, 167, 250, 0.78) 28%, rgba(84, 167, 250, 0.24) 46%, rgba(84, 167, 250, 0) 70%), linear-gradient(rgba(107, 181, 255, 1), rgba(73, 146, 255, 1) 35%, rgba(61, 139, 239, 1) 70%, rgba(70, 155, 252, 1)); box-shadow: rgba(36, 109, 190, 0.55) 0px 0px 0px 0.5px inset, rgba(32, 90, 160, 0.1) 0px 2px 4px 0px, rgba(73, 146, 255, 0.18) 0px 6px 14px 0px`

**Text style:** `button` — Aqua CTA 500 · 15px/1.333

**Observed:** A thin reflective rim makes the pill feel like illuminated glass. Platform actions add a small platform icon before the label. Width follows content except in pricing cards, where it fills the card.

**States:** Declared: hover behavior is unspecified; focus-visible outline #2f6fc9 solid 2px with 3px offset.

### Secondary button

**Use:** Documentation and quieter plan actions.

**CSS:** `height: 48px; padding: 14px 24px; border-radius: 9999px; color: #4b4b48; background: linear-gradient(#ffffff, #fdfdfc 55%, #f8f7f4); box-shadow: rgba(75, 75, 72, 0.04) 0px 1.5px 2.5px 0px inset, rgba(0, 0, 0, 0.05) 0px 1px 1px 0px, rgba(42, 40, 35, 0.08) 0px 2px 6px -2px`

**Text style:** `button` — Aqua CTA 500 · 15px/1.333

**Observed:** White ceramic-looking sibling of Primary button, not a transparent outlined control.

**States:** Declared: hover behavior is unspecified; focus-visible outline #2f6fc9 solid 2px with 3px offset.

### Charcoal button

**Use:** Editorial conversion moments within light feature sections.

**CSS:** `height: 48px; padding: 14px 24px; border-radius: 9999px; color: #fafafa; background: linear-gradient(#2e2e2e, #171717); box-shadow: rgba(255, 255, 255, 0.35) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.45) 0px -2px 4px 0px inset, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px, rgba(23, 23, 23, 0.5) 0px 2px 22px 0px`

**Text style:** `button` — Aqua CTA 500 · 15px/1.333

**Observed:** A compact dark punctuation mark under a centered promise; it retains the same luminous edge logic as the blue control.

**States:** Declared: hover behavior is unspecified; focus-visible outline #2f6fc9 solid 2px with 3px offset.

### Testimonial card

**Use:** Human proof mosaic.

**CSS:** `width: 288px; padding: 24px; background: #ffffff; border: 1px solid rgba(41, 44, 61, 0.08); border-radius: 16px`

**Text style:** `quote` — PP Neue Montreal 400 · 15px/1.5

**Observed:** A 40px round avatar and small handle precede a short, unpolished user quote. Cards vary in height and column offset. Text is muted; the surrounding wall fades at the edges.

**Transfer:** Use authentic concise feedback and preserve staggered heights.

### Feature card

**Use:** Explain one capability with a small visual and benefit.

**CSS:** `display: grid; gap: 24px; padding: 24px; border: 1px solid #e3e3e3; border-radius: 24px; background: linear-gradient(155deg, #ffffff 12%, #fafafa); box-shadow: rgba(0, 0, 0, 0.01) 0px 2px 3px 0px, rgba(0, 0, 0, 0.15) 0px 12px 28px -20px`

**Text style:** `card-title` — PP Neue Montreal 500 · 20px/1.25

**Observed:** A pale interface fragment or fine-line illustration occupies the upper area; a title and Body paragraph anchor the lower area. Media is typically 153px high, occasionally 170px.

**Transfer:** Use one focused visual explanation per card.

### Metric row

**Use:** Large outcome proof under a demonstration.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; align-items: flex-end; gap: 16px; padding-bottom: 16px; border-bottom: 1px solid rgba(44, 48, 51, 0.1)`

**Text style:** `metric` — PP Neue Montreal 400 · 60px/1 · tracking -0.02em

**Observed:** Large value left, small descriptive label aligned to its baseline at right. Two 560px rows share an 80px gutter. On a dark ground the rule changes to white at 15% and text to white.

**Transfer:** Use units integral to a real user outcome, not decorative counters.

### Plan card

**Only for:** pricing sections

**Use:** Plan comparison or one usage-based offer.

**CSS:** `display: grid; padding: 28px; border: 1px solid #e3e3e3; border-radius: 24px; background: linear-gradient(155deg, #ffffff 12%, #fafafa); box-shadow: rgba(0, 0, 0, 0.01) 0px 2px 3px 0px, rgba(0, 0, 0, 0.15) 0px 12px 28px -20px`

**Text style:** `plan-title` — Aqua Pricing Display 500 · 24px/1.25 · tracking -0.02em

**Observed:** Name, short description, price with smaller currency and billing qualifier, full-width action, divider, then blue circular checks and linked benefits. The highest individual tier gets Primary button; other plans use Secondary button. Business is a horizontal card with an internal vertical divider.

**Transfer:** Keep the price block visually stronger than the feature list.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling.

**CSS:** `border-bottom: 1px solid rgba(0, 0, 0, 0.08); padding: 28px 0px; display: flex; align-items: center; justify-content: space-between; gap: 32px`

**Text style:** `faq-question` — PP Neue Montreal 500 · 21px/1.3 · tracking -0.01em

**Observed:** Plain unboxed rows in a 720px-wide list. A thin plus sits at the far right; the list also has a top rule. Closed rows are about 84px high.

**Transfer:** Use native expandable details with the question left aligned.

### Directory card

**Only for:** integration or use-case directories

**Use:** Link to a specific app, workflow or compatible tool.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; min-height: 331px; padding: 40px; border: 1px solid #e3e3e3; border-radius: 24px; background: linear-gradient(155deg, #ffffff 12%, #fafafa); box-shadow: rgba(0, 0, 0, 0.01) 0px 2px 3px 0px, rgba(0, 0, 0, 0.15) 0px 12px 28px -20px`

**Text style:** `directory-title` — PP Neue Montreal 400 · 36px/1.2

**Observed:** Recognizable app icon, generous separation, large name, one brief task-specific sentence, then a small View label with a right arrow. The entire card is linked.

**States:** Declared: hover behavior is unspecified; focus-visible outline #4288ff solid 2px with 2px offset.

### Code panel

**Only for:** developer integration sections

**Use:** A concrete integration example.

**CSS:** `background: #f4f4f3; border-radius: 16px; padding: 20px`

**Text style:** `code` — Fragment Mono 400 · 14px/1.6

**Observed:** The code well sits within a Porcelain card with a language header and divider; the inner well has 28px outer spacing. Syntax stays subdued blue-black and grey.

**Transfer:** Show a complete minimal request with a meaningful response path, not a decorative fragment.

### Billing selector

**Only for:** billing controls

**Use:** Monthly versus annual billing.

**CSS:** `height: 28px; padding: 0px 12px; border-radius: 9999px; background: #ffffff; color: #4b4b48; box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.1) 0px 1px 2px -1px`

**Text style:** `billing` — Inter 500 · 12px/1.333

**Observed:** Selected white pill sits in a 188px by 36px warm-grey track with 4px padding. A smaller discount note follows the annual label; the control aligns right of the centered pricing support line.

## Imagery and graphics

### Floating desktop theatre

**Use:** Signature first-screen product scene.

**Observed:** A very pale translucent monitor and stand frame three dark app windows. The central window is front-facing and larger; the side windows fan outward and recede. Deep soft shadows separate them from the near-white screen. A tiny dark command pill floats beneath the windows; controls sit outside the monitor along the bottom of the viewport.

**Transfer:** Create three coherent views of a different product performing one task. Minimum acceptable version is a carefully drawn simplified interface, not blank rectangles or generic dashboard filler.

**Build:** Use a 1063px-wide relative stage with a thin double-outline monitor, translucent white screen and a centered outlined stand. Put a 474px by 295px main window above two roughly 398px by 279px side windows. Apply 16px corners, perspective rotation to the sides and layered downward shadows. Keep headline and support above the window fan, with a small dark interaction hint below.

### Horizontal application demonstrations

**Use:** Capability chapters on light and scoped dark grounds.

**Observed:** Large app windows occupy most of the viewport width: 803px by 500px on light ground, 893px by 556px on dark. A neighboring window remains partially visible. A one-line caption sits directly below each window, with tiny compatibility icons and a fine progress line beneath the rail.

**Transfer:** Show a real task at a readable scale. Use matching light or dark interface styling, with adjacent content suggesting continuation instead of reducing every example to a small tile.

### Pale interface diagrams

**Use:** Upper visual area of Feature card.

**Observed:** Small interface fragments dissolve into pale backgrounds: editing marks, a dictionary list, stacked preferences, transcript history and a delicate wireframe globe. Mostly grey and white, with tiny blue selected states; the visual does not fight the text.

**Transfer:** Use reduced UI fragments or a fine-line conceptual diagram for each capability. Keep one semantic focus and let the edges fade.

**Build:** Draw compact rounded rows and light grey text bars with SVG at 153px high. Use ink at 4–8% opacity for inactive detail and #4288ff for one selected chip or caret. Mask peripheral edges into white. For a globe equivalent, use an outlined circle with thin elliptical meridians and latitudes at low ink opacity.

### Reflective blue closing scene

**Use:** Signature atmospheric closing artwork.

**Observed:** A large soft blue sphere sits right of the closing copy above a pale reflective water plane. Its lower half repeats in wavy horizontal reflection, fading into the cool footer ground; faint distant grey forms remain soft and secondary. The scene is wide, about 1200px by 682px, with ample empty space left for text.

**Transfer:** Use a simple blue orb or another abstract product-independent rounded form with the same pale horizon and reflected light. The atmosphere, not a literal object or landscape, is the transferable signature.

**Build:** In a 1200px by 682px SVG, place a roughly 340px blue radial-gradient circle in the right third, using #67beff and #4288ff with a blurred light edge. Duplicate and vertically flip below a horizon near the lower half; compress vertically, distort with low-amplitude horizontal displacement and fade the reflection into #eef2f5. Layer thin semi-transparent horizontal streaks across the reflection. Match the soft glow; exact gradient stops are not essential.

### Physical device still life

**Only for:** device or platform showcases

**Use:** Cross-platform download or companion-product chapter.

**Observed:** A dark phone appears as a real physical object on a warm grey plinth, slightly angled, with directional shadow falling down and right. Copy, a platform switch, QR tile and a short link occupy the left half. The device is much larger than the QR tile.

**Transfer:** Use one realistically lit device or product artifact with restrained material highlights; retain an accessible text route alongside any QR action.

### Clouded hero atmosphere

**Only for:** developer and directory openings

**Use:** Text-first alternative to the desktop theatre.

**Observed:** A nearly white cloudy background provides soft depth behind centered copy. The directory variant scatters recognizable colorful app marks around the perimeter; the developer variant keeps the center unobstructed and adds tiny checked facts below the actions.

**Transfer:** Use low-contrast cloud forms and small relevant ecosystem marks only at the edges.

**Build:** Layer very low-opacity grey blurred cloud shapes over white, then apply a central white radial wash and a bottom fade into paper. Keep all high-contrast marks outside the copy column.

### Icons

**Observed:** Navigation chevrons are 16px with 1.5px rounded strokes. Action icons are usually 18px. Directory cards use recognizable colored app marks; pricing benefits use 16px white checks within blue circles. Conceptual benefit symbols are thin-line drawings rather than filled pictograms.

**Transfer:** Use restrained round-stroke utility icons; retain colored third-party marks only where they identify a real integration. Keep illustrative line icons separate from product UI.

## Section recipes

How recurring sections are built.

### First screen: Desktop theatre opening

**Observed:** The first 900px contains the entire staged monitor, from its top near 124px through the stand near the bottom. A separate brand mark sits upper left, with Floating navigation upper right. Behind the monitor is near-white atmospheric space; the translucent screen is behind a centered Stage-display headline and Stage-support sentence, then tiny platform links. The lower screen is dominated by Floating desktop theatre: three overlapping dark windows with the central view forward. A dark command hint sits under the windows. Mode pills occupy the lower left outside the monitor and a white start action the lower right; the blue conversion remains in the header. Social proof begins below the fold.

**Transfer:** Make the new product the object of attention, using a simplified but legible interface if polished media is unavailable. Keep the whole stage visible before scrolling. Pricing opens instead with the centered Pricing-heading and immediate plan cards; developer pages use Api-display on Clouded hero atmosphere with paired actions; directories use a centered proof-sized headline surrounded by ecosystem marks.

**Avoid:** Do not replace this opening with an oversized left-aligned slogan beside a small rectangular dashboard. Do not move all conversion actions below the fold or use generic stock photography as the main object.

**Text style:** `stage-display` — PP Neue Montreal 400 · 56.7px/1.065 · tracking -0.0318em

### Heading and support

**Observed:** A 720px centered intro pairs Heading with Body copy after 20px; content follows after about 40px. Some demonstration headings align left in the 1200px content width instead. A compact pill can sit between the promise and the proof.

**Transfer:** Use one concrete benefit per heading and one short explanation; choose centered framing for a claim and left alignment for an immersive chapter.

**Text style:** `heading` — PP Neue Montreal 400 · 52px/1.08 · tracking -0.01em

### Human proof field

**Observed:** Proof-heading sits above a small trust label and monochrome company-mark ticker. Testimonial card repeats in five staggered columns with 8px gutters. The wall overflows the viewport slightly and fades out at its lower and side edges.

**Transfer:** Preserve the field-like density and soft disappearance; use real feedback, role attribution and authentic logos rather than uniform quote slides.

**Text style:** `proof-heading` — PP Neue Montreal 400 · 56px/1.1

### Immersive task chapter

**Observed:** A left-aligned Heading introduces Horizontal application demonstrations. Large windows cross the viewport horizontally, captions stay attached below, and a thin progress indicator centers beneath the rail. A Metric row pair can close the chapter. Night demonstration band scopes the dark version; Paper canvas and Warm demonstration band support the light versions.

**Transfer:** Organize a chapter around a task the new product improves. Preserve large media and visible continuation, not the exact number of panels.

### Capability card pairs

**Observed:** Feature card pairs sit in the 1200px content area with 20px gutters, under a centered heading and action. Pale interface diagrams occupy the top; titles and support stay left aligned. One comparison card replaces its image with two 10px-high rounded bars, blue for the product and grey for the baseline.

**Transfer:** Mix interface fragments, fine-line concepts and one compact quantified proof; do not make every card the same illustration.

### Atmospheric closing and footer

**Observed:** Closing-heading sits left in a 550px column with Primary button about 20px below it. Reflective blue closing scene occupies the right and continues behind the transition to Water footer ground. Below, five link columns use Footer-label with plain small links and 24px column gaps. A fine rule precedes the bottom brand/status row, social icons, legal links and copyright; the footer ends with 64px breathing room.

**Transfer:** End with a concise invitation, a luminous action and the reflected-blue atmosphere. Technical pages instead use a centered Heading, short Body and paired actions on paper before the same five-column link structure, without the water scene.

**Text style:** `closing-heading` — PP Neue Montreal 400 · 56px/1.2

### Pricing comparison

**Only for:** pricing sections

**Observed:** Pricing-heading and a compact support line sit above the right-aligned Billing selector. Three Plan cards occupy 1104px with 32px gutters; the business card spans below. Pricing uses its own slate text colors and medium display cut. Technical usage-based pricing uses one centered plan card and a secondary documentation action below.

**Transfer:** Choose seat tiers or one usage-based offer as appropriate. Keep action emphasis within the shared pill system.

**Text style:** `pricing-heading` — Aqua Pricing Display 500 · 52px/1.08 · tracking -0.03em

### Technical proof and integration

**Only for:** developer product pages

**Observed:** A narrower 952px area holds a three-column strip of 60px metrics, detailed comparison tables and transcript examples inside Porcelain card. Correct and incorrect terms have small 5px-radius green and red washes. A large benchmark chart uses blue for the product and greys for competitors, with a small methodology caption below. Three ruled setup steps lead to Code panel, then pricing and a two-column resource grid.

**Transfer:** Provide inspectable proof alongside the headline metric. Color only the meaningful difference; state benchmark scope, direction and date near the chart.

### Directory category chapter

**Only for:** integration or use-case directories

**Observed:** Directory-heading is left aligned above a short Body description and occasional underlined guide link. Directory cards form three equal columns with 24px gutters and 80px between categories. Incomplete rows remain left aligned.

**Transfer:** Group by reader task, using short tool-specific benefit sentences instead of repeating generic integration copy.

**Text style:** `directory-heading` — PP Neue Montreal 400 · 48px/1.1

### Objection list

**Only for:** FAQ sections

**Observed:** A 720px-wide block uses Heading above FAQ row with 40px separation and 128px vertical section padding. No surrounding card or extra background is applied.

**Transfer:** Keep the questions direct and specific to buying or adopting the product.

## Page flow

**Storyline:** Immediate promise and product presence → human or measurable proof → task-led capability chapters → commercial choice and adoption reassurance → closing invitation.

### Flagship product landing page

1. **Promise and product demonstration** — A complete desktop theatre shows the tool in use before the reader scrolls.
2. **Social proof** — Monochrome trust ticker and fading testimonial mosaic.
3. **Quantified proof** — Side-by-side faster versus slower task demonstration.
4. **Capability chapters** — Dark, paper and warm-grey horizontal app demonstrations, each focused on a real task, with large outcome rows.
5. **Platform extension** — Physical-device plinth with QR handoff and platform switch.
6. **Capability summary** — Paired illustrated cards, including compact comparison bars.
7. **Pricing** — Three plans and a horizontal business offer.
8. **Closing call** — Reflected blue atmosphere, large invitation, categorized footer and status row.

**Transfer:** Use the staged product, human proof, measurable proof and atmospheric ending as devices; adapt chapter count and order to the new product.

### Purchase decision page

1. **Pricing** — Centered commercial promise, billing toggle and plan comparison immediately.
2. **Objection handling** — Narrow unboxed accordion list.
3. **Closing call** — Watery blue closing invitation followed by the complete footer.

**Transfer:** Reduce narrative detours; keep the tactile plan cards, scoped pricing typography and practical questions.

### Technical product adoption page

1. **Promise** — Large centered technical claim on clouded white with primary and documentation actions plus small checked facts.
2. **Social proof** — Shared trust ticker and testimonial field.
3. **Product rationale** — Narrow prose explaining the specific technical problem.
4. **Quantified proof** — Metric strip, score tables, highlighted transcript comparisons and a benchmark chart with methodology.
5. **Adoption** — Three ruled setup steps and a readable code example.
6. **Pricing** — One usage-based pricing card.
7. **Further exploration** — Two-column resource cards.
8. **Objection handling** — Shared FAQ list.
9. **Closing call** — Centered paired-action call on paper, then a plain five-column footer and status/legal row.

**Transfer:** Replace every benchmark and example with defensible new-product material while keeping the inspectable proof and low-friction integration structure.

### Integration and workflow discovery page

1. **Promise** — Centered benefit statement with scattered ecosystem icons and one blue action.
2. **Capability directory** — Repeated task-category introductions and three-column linked cards.
3. **Social proof** — Shared faded testimonial field after the directory.
4. **Adoption reassurance** — Short centered compatibility and trust statement with a product-guide action.
5. **Capability summary** — Paired feature cards with pale diagrams and one compact metric comparison.
6. **Closing call** — Shared reflective blue closing and complete footer.

**Transfer:** Keep categories reader-oriented and each card specific; use authentic compatibility marks rather than decorative icon confetti.

## Writing

Direct, conversational confidence backed by practical detail. Benefits feel like relief from everyday friction; technical claims are followed by inspectable explanations rather than hype.

**Do not copy:** Do not reuse the brand names, product names, customer quotes, logos, benchmark scores, comparative claims, prices, discounts, platform availability, certifications or other source-specific assets and facts. Supply independently valid equivalents. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you or your. The product is named as an active helper; we appears when explaining a technical decision.
- **Rhythm:** Short spoken headlines, often four to nine words, alternate with compact explanatory paragraphs. Three-part fragments add pace; periods are common even in headlines. Technical sections allow longer factual sentences.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A plain verb and an everyday destination; no category jargon. | 3–8 words | “Talk into your apps.” |
| Capability lead | Three short outcomes that sound natural aloud. | 5–10 words | “Clearer messages. Faster updates. Less effort.” |
| Supporting line | Explain the mechanism and where the result lands. | 12–30 words | “Aqua transcribes you perfectly and pastes the text where your cursor is.” |
| Primary action | Verb plus immediate task or platform; documentation is a clear secondary route. | 2–5 words | “Get Started on Mac”<br>“Start Transcribing”<br>“Read Documentation” |
| Technical reassurance | Concrete compatibility statement followed by what changes and what stays. | 12–25 words | “Keep your OpenAI SDK workflow. Change the base URL and model, then send an audio file.” |
| Closing invitation | Let the product take over a familiar burden. | 5–9 words | “Let your voice do the writing.” |

**Words and phrasing to use:** your; works in; keep; without; ready-to-send; the way you work; start free; less effort

**Avoid:** revolutionary; unleash; supercharge; game-changing; seamless synergy; future-proof everything

**Rules:**

- Lead with the user's task, then explain the mechanism.
- Name the concrete place the result is used.
- For numerical claims include the unit, comparison and method close by.
- Use technical nouns accurately when the reader needs them, not as decoration.
- Keep directory card descriptions short and distinct; one task per card.
- Use sentence case for headings and plain verb phrases for actions.

## Do's and Don'ts

### Do

- Keep default section headings at 52px/1.08, regular weight and -0.01em tracking.
- Stage a legible interface at large scale, with 16px window corners and layered downward shadows.
- Use the 1200px content area for immersive sections and the 720px intro width for concise claims.
- Give feature cards 24px padding and 24px corners; reserve 40px padding for directory cards.
- Keep conversion pills 48px high with 15px/20px labels.
- Let testimonial cards vary in height within 8px-gutter columns and a fading wall.
- Pair 60px outcome figures with smaller baseline-aligned labels and fine rules.
- Make the closing atmosphere fade into #eef2f5 rather than stop at a hard image edge.

### Don't

- Do not turn every heading bold; the regular grotesk is part of the character.
- Do not spread saturated blue across ordinary section backgrounds; reserve broad blue for soft atmospheric art.
- Do not flatten pill buttons into solid rectangles or generic outlined controls.
- Do not apply the dark demonstration ground to pricing, FAQs or every feature chapter.
- Do not use 24px card corners on app windows; their 16px corners distinguish the product layer.
- Do not enlarge small diagram colors into multicolored card backdrops.
- Do not put the FAQ inside a heavy bordered card; its structure is the thin row rule.
- Do not set code in the marketing sans or use monospace as the default section label.

## Motion and responsive

### Motion

**Observed:**

- Declared: testimonial entrance uses wall-cascade-in for 0.7s with cubic-bezier(0.2,0.7,0.2,1).
- Declared: the trust ticker scrolls for 80s linearly and repeats infinitely.
- Declared: text links transition color and text-decoration-color over 0.15s; glass controls transition --glass-overlay over 0.15s ease-out.
- The large application chapters use horizontal continuation with a thin progress line; the physical-device video includes a pause control.

**Transfer:**

- Use a slow trust-mark drift, a soft staggered proof reveal and restrained control highlights rather than making the whole page kinetic.
- Preserve a stationary readable caption with each moving app panel and offer a pause control for persistent device demonstrations.

**Unknown:**

- Exact scroll-to-horizontal mapping, entrance triggers and any additional motion timing are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 810px, 1000px, 1024px, 1100px and 1280px.
- Social-proof headings declare a 40px smaller-width variant. Directory category headings declare 36px and directory card names 30px.
- Directory grids declare one, two and three-column variants; testimonial walls declare fewer columns at narrower widths.

**Transfer:**

- On narrow screens preserve the staged-product hierarchy by reducing the window fan and keeping one central task legible; do not shrink all interface text to fit three windows.
- Collapse feature and pricing grids into readable stacks, keep category groups intact, and retain the reflected-blue ending with copy clear of the orb.
- Treat these as adaptation guidance; choose breakpoints by content fit rather than assuming all declared widths control the same component.

**Unknown:**

- Exact mobile monitor composition, navigation expansion, footer reflow and scroll-rail behavior are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
