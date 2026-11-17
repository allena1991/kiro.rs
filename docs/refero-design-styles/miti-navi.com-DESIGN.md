# Miti Navi — sculpted maritime romance

## Overview

A sunlit, tactile luxury style with sand-colored grounds, blue outdoor imagery and near-black lettering. Delicate, high-contrast serif headlines meet utilitarian monospaced navigation, creating a mixture of romance and workshop practicality. It suits premium physical products and experiential services, with low text density and an unusually sculptural frame around the main image.

### Essentials

- The opening is a shaped window, not a rectangular banner: an 820px hero beneath an 87px header, with bowed sides and a broad central downward cusp framing the identity.
- Romantic headlines contrast with equipment-like controls: Voyage at 72px/0.9 and 46px/0.9, weight 400, beside GT Pressura Mono at 16px/1.4.
- The product inhabits an outdoor world: a nearly screen-filling daylight scene carries natural blue and material color; the surrounding interface remains sand and near-black, with no chromatic accent fills.
- The main action is an inscription rather than a pill: uppercase 14px mono with 1px tracking, 15px vertical padding and a fine underline; the persistent resource action is a square-edged 37px-wide dark vertical tab.
- The identity sits in the frame's central cusp: a compact 120×65px mark beneath the centered language controls, with navigation distributed to either side.
- Short headings become editorial medallions: centered 46px serif text, often broken into two lines, with a short fine rule above. Preserve this device alongside the shaped image stage on new pages, using a carefully lit product photograph or material study when lifestyle media is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Marine ink | `#000e13` | `--color-ink` | text, action, background | Display text, navigation, thin rules and the persistent resource tab. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-utility` | text | Compact language controls. |
| Charcoal | `#232323` | `--color-body` | text | Body copy and section headings on sand. |
| Pale sand | `#e6dece` | `--color-stage` | background, surface | Backing of the opening image stage. |
| Frame sand | `#e6decf` | `--color-frame` | border, surface | The sculptural image mask and its upper edge; visually almost continuous with the page ground. |
| Warm sand | `#e8ded0` | `--color-canvas` | background, text | Default page ground and reversed lettering on the dark resource tab. |

## Typography

- **Voyage** — Hero and section headings. Slender, high-contrast decorative serif with flowing joins, sharp fine strokes and a calligraphic rhythm. If unavailable, use **Bodoni Moda**. Use weight 400; retain the tight line stacking and tune line breaks to the broader letterforms. Font stack: "Voyage", "Bodoni Moda", Georgia, serif.
- **GT Pressura Mono** — Navigation, body copy and action labels. Compact industrial monospace, regular rather than bold, contrasting sharply with the ornamental serif. If unavailable, use **Roboto Mono**. Use weight 400 and keep control labels compact. Font stack: "GT Pressura Mono", "Roboto Mono", ui-monospace, monospace.
- **Times** — Widely spaced serif labels over opening headlines. Small traditional serif capitals with conspicuously open tracking. Font stack: "Times", 'Times New Roman', serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Voyage | 400 | 72px | 0.9 | normal | Two-line opening promise; center the lines within the caption group even when the group is offset to one side. |
| heading | Voyage | 400 | 46px | 0.9 | normal | Centered editorial section leads. |
| body | GT Pressura Mono | 400 | 16px | 1.4 | normal | Body text and navigation; navigation labels use capital letters. |
| eyebrow | Times | 400 | 14px | 1.4 | 4px, uppercase | Small centered category or identity above the hero title. |
| action | GT Pressura Mono | 400 | 14px | 1.4 | 1px, uppercase | Underlined discovery action. |
| language | GT Pressura Mono | 400 | 14px | 1.4 | normal, uppercase | Two-letter language controls. |
| resource | GT Pressura Mono | 400 | 12px | 1.4 | 1px, uppercase | Rotated persistent resource label. |

**Notes:**

- Keep serif headlines regular and delicately drawn; emphasis comes from scale and line breaks rather than weight.
- The 0.9 headline line height produces closely interlocking lines. Keep tracking normal; do not imitate the effect with compressed letter spacing.
- The serif eyebrow's 4px tracking is deliberately much more open than the mono action's 1px tracking.

## Layout

**Density:** Airy: small caption groups sit against broad photographic stages and open sand grounds; navigation is compact.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Resource tab vertical padding and navigation side margins. |
| 15px | Vertical padding of text actions; horizontal padding of the resource tab. |
| 16px | Column side padding. |
| 30px | Header vertical padding and gaps around hero heading groups. |
| 32px | Inner side padding of editorial containers. |
| 60px | Standard section top and bottom padding and hero caption side padding. |
| 240px | Deep lead-in to a major product chapter; use only when populated content justifies the pause. |

### Containers and grids

- **Editorial container**: max width 1320px · side padding 32px. Centered content container; at 1440px the outer edges leave 60px on each side before internal padding.
- **Opening caption**: max width 594px · side padding 60px. A centered caption group occupying about 45% of the main container, offset left by default; maintain room for the main object to its right.
- **Centered heading column**: max width 397px · side padding 16px. Short serif section leads centered in a one-third-width editorial column. A narrower 290px title produces a compact two-line chapter label.

## Corner radius

| Element | Radius |
| --- | --- |
| Actions and editorial surfaces | 0px |

## Surfaces and depth

### Surfaces

#### Sand canvas · level 0

**Use:** Continuous editorial background.

**CSS:** `background-color: #e8ded0; color: #232323`

**Observed:** Flat, matte and untextured; no raised card treatment.

**Transfer:** Let photographic texture supply the richness instead of adding paper grain or gradients.

#### Sculpted stage · level 0

**Use:** Opening image backing and silhouette.

**CSS:** `background-color: #e6dece; position: relative`

**Observed:** The image is bounded by a pale frame whose upper curves dip into a broad central cusp; the sides bow outward and return toward the lower corners.

**Transfer:** Use an SVG mask over a fully rendered image; preserve the contour independently of subject matter.

#### Dark resource strip · level 1

**Use:** Persistent secondary conversion surface.

**CSS:** `background-color: #000e13; color: #e8ded0; padding: 10px 15px`

**Observed:** A narrow solid strip flush with the right viewport edge, with square corners and no shadow.

**Transfer:** Reserve the dark fill for the always-available document or guide action.

## Components

### Split masthead

**Use:** Global desktop navigation and identity.

**CSS:** `position: relative; padding-top: 30px; padding-bottom: 30px; z-index: 3`

**Text style:** `body` — GT Pressura Mono 400 · 16px/1.4

**Observed:** Two navigation groups flank an 80px-wide centered language pair. The identity is placed lower, inside the image frame's central cusp, rather than inline with the links.

**Transfer:** Use the new identity as a compact mark and distribute a concise set of destinations symmetrically.

### Navigation link

**Use:** Unboxed global destinations.

**CSS:** `position: relative; color: #000e13; padding-top: 15px; padding-bottom: 15px; margin-left: 10px; margin-right: 10px`

**Text style:** `body` — GT Pressura Mono 400 · 16px/1.4

**Observed:** Uppercase words, with a clipped text wrapper containing normal and duplicate rollover labels. A short fine line marks the current destination; no enclosing button surface.

### Discovery link

**Use:** Primary exploration action over the hero image.

**CSS:** `position: relative; padding-top: 15px; padding-bottom: 15px; color: #000e13; background: transparent`

**Text style:** `action` — GT Pressura Mono 400 · 14px/1.4 · tracking 1px · uppercase

**Observed:** A fine underline spans the label width. The label sits below the headline and remains much smaller than the serif promise.

**Transfer:** Use one short exploratory action rather than a filled purchase button.

### Resource tab

**Use:** Always-available document download.

**CSS:** `position: fixed; background-color: #000e13; color: #e8ded0; padding: 10px 15px; transform: rotate(90deg); z-index: 3`

**Text style:** `resource` — GT Pressura Mono 400 · 12px/1.4 · tracking 1px · uppercase

**Observed:** The rotated result occupies 37×190px for the source label, flush right and 130px below the viewport top. It remains visible while the main navigation scrolls away.

**Transfer:** Keep the same compact dark tab; let the long dimension follow the new label.

### Language pair

**Use:** International site utility.

**CSS:** `display: flex; justify-content: space-between; align-items: center; width: 80px; color: #000000`

**Text style:** `language` — GT Pressura Mono 400 · 14px/1.4 · uppercase

**Observed:** Two small text controls centered above the identity, without separators, flags or containers.

### Hero label

**Use:** Name the opening category without competing with the promise.

**CSS:** `position: relative; padding-top: 10px; padding-bottom: 20px; margin-bottom: 30px; color: #000e13`

**Text style:** `eyebrow` — Times 400 · 14px/1.4 · tracking 4px · uppercase

**Observed:** Centered above the display title, with a short horizontal rule beneath the lettering.

### Editorial heading

**Use:** Introduce a product or capability chapter.

**CSS:** `color: #232323; text-align: center`

**Text style:** `heading` — Voyage 400 · 46px/0.9

**Observed:** A narrow one- or two-line serif lead, with a short fine rule above; it belongs directly on sand rather than inside a card.

**Transfer:** Let actual chapter content follow the title, keeping the title's scale and narrow measure.

## Imagery and graphics

### Daylight product world

**Use:** Dominant opening scene.

**Observed:** Large marine photographs show dark-hulled craft against pale blue sky, textured blue water and dry muted hills. Natural daylight and gently softened color feel leisurely rather than cinematic-dark. The primary object sits center-right on the default composition, leaving open sky for the left caption; the scene fills most of the first screen.

**Transfer:** Photograph the product in a credible, bright environment with a broad calm region for lettering. If no location shoot is available, use one well-lit product render with a softly colored horizon or a close material study, not a grid of interface panels.

### Curved window frame

**Use:** Signature framing device for the first screen.

**Observed:** A sand-colored silhouette encloses the image, with a wide concave upper sweep meeting in a downward central point beneath the identity. The outer sides are gently barrel-shaped, while the bottom is almost straight. The result resembles an open book or sail-shaped viewing aperture, not a rounded rectangle.

**Transfer:** Keep the shaped window and inset pale border for any product category; replace its image and identity, not the visual mechanism.

**Build:** Create an SVG with a 1440×900 viewBox and an even-odd filled sand overlay. Draw an inner window starting near (112,80), curving through the upper-left shoulder toward a central cusp near (720,242), then up to the right shoulder near (1328,80). Bow the right side outward near (1410,450), returning to (1368,864); draw an almost straight bottom to (72,864), then bow the left side through (30,450) back to the start. Fill the surrounding area with frame sand. These control points are a construction guide; keep the broad cusp, the side bow and the image's large scale.

### Material perspective

**Only for:** craft and capability pages

**Use:** Alternative opening subject.

**Observed:** A highly realistic deck view uses converging timber planks, reflective curved glazing and slender metal rails, looking toward a calm sea horizon. Warm timber contrasts with cool aqua reflections; centered black lettering overlays the perspective.

**Transfer:** Use close architectural or manufacturing detail to convey craft. Preserve long perspective lines and daylight reflections instead of inserting generic workshop icons.

## Section recipes

How recurring sections are built.

### First screen: Shaped scene opening

**Observed:** An 87px sand masthead precedes an 820px image stage. Back to front: pale stage, full daylight image, centered caption group offset to the left, sculptural pale mask around the image, then the identity in the central cusp and the fixed Resource tab at the right. The image occupies nearly all available width, inset by roughly 48–72px around its lower and side edges. The main object occupies the center-right and reaches high into the frame. A small Hero label and rule precede a 72px, two-line serif promise spanning about the left third, followed by the Discovery link. Within the first 900px, navigation, identity, headline, action and nearly the whole scene are visible; the next editorial chapter begins below. No supporting paragraph competes with the image.

**Transfer:** Build the same hierarchy around a different product: one calm environmental image, a large isolated object, a short emotional promise and one discovery action. Keep the shaped frame even when using a single studio image. Collection and brand-story variants place the caption on the right; craft-focused variants center it over a perspective image and omit the discovery action when it is not needed.

**Avoid:** Do not replace the shaped image window with a rounded card, center the default caption over the main object, or add a dense paragraph and multiple filled buttons.

**Text style:** `display` — Voyage 400 · 72px/0.9

### Editorial chapter lead

**Observed:** The Editorial heading sits directly on Sand canvas, centered in a 397px or 290px measure, at 46px/0.9. A short fine rule above it and 60px section padding connect the practical chapter to the romantic opening.

**Transfer:** Use a brief selection, progress or capability statement to introduce real content. Keep the visual medallion treatment, but size the surrounding space to the content rather than stretching the title into an empty screen.

**Text style:** `heading` — Voyage 400 · 46px/0.9

### Resource-led close

**Observed:** The Resource tab provides a persistent secondary path throughout the page, independent of the large editorial chapters.

**Transfer:** For a new page, end with a concise next-step invitation on Sand canvas and a Discovery link while retaining the Resource tab. Use the same Editorial heading hierarchy rather than introducing a new colored conversion panel.

## Page flow

**Storyline:** Emotional product world → focused selection or capability chapters → practical next step, with a persistent resource path.

### General marketing landing page

1. **Promise** — Left-caption shaped image stage with a discovery action.
2. **Selection** — Centered editorial heading invites the reader to find a suitable offering.
3. **Progress proof** — A compact two-line serif heading introduces work in progress.
4. **Next step** — Carry the exploration action and persistent resource path into a concise ending.

**Transfer:** Use the emotional opening as the default; populate subsequent chapters with the new product's actual offering and proof.

### Collection introduction

1. **Promise** — Right-caption shaped image stage presents a different way of living.
2. **Progress proof** — Centered heading introduces products being developed.
3. **Selection** — A second centered heading turns attention toward the reader's best fit.

**Transfer:** Emphasize choice and suitability; retain the shared typography and image frame.

### Brand and origin story

1. **Affinity** — Right-caption opening uses a first-person sense of longstanding enthusiasm.
2. **Story** — Extend the editorial canvas into narrative chapters.
3. **Progress proof** — Shared centered heading links the story back to tangible work.

**Transfer:** Use real origin and process content; maintain continuity with the product stage rather than inventing a separate visual identity.

### Craft and capability introduction

1. **Capability promise** — Centered serif title over an immersive material-perspective scene.
2. **Capability chapters** — Continue the sand editorial ground for process and service explanations.

**Transfer:** Lead with physical evidence of craft, followed by concrete capabilities and a relevant next action.

## Writing

Romantic and assured, with simple aspirational promises rather than dense luxury jargon. Practical navigation and progress-oriented headings ground the emotional language.

**Do not copy:** Do not reuse the Miti Navi name, logo, proprietary imagery, product names or unverified claims about construction, history or exceptional craftsmanship. Source phrases are examples of tone, not reusable brand assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your for suitability and desire; use we for a direct capability promise. Identity labels remain impersonal.
- **Rhythm:** Hero lines use roughly 4–9 words, broken into two lyrical lines. Section titles use roughly 4–7 words; actions use a short verb phrase. Avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | A tangible product noun connected to a personal aspiration. | 4–9 words | “The sailboats of your dreams”<br>“Another idea of life at sea” |
| Capability promise | A plain first-person verb followed by a confident quality statement. | 4–6 words | “We build exceptional boats” |
| Section lead | Speak to personal fit or report tangible progress. | 3–7 words | “Find the right boat for you”<br>“Already under construction” |
| Primary action | Invitation to discover, not pressure to transact. | 2–4 words | “Discover [Brand]” |
| Resource action | Direct verb plus useful document. | 3–4 words | “Download our brochure” |

**Words and phrasing to use:** discover; your; right for you; life; dreams; build; already

**Avoid:** disruptive; game-changing; unleash; limited-time offer; best-in-class; revolutionary platform

**Rules:**

- Pair one emotional idea with one tangible product or experience.
- Use uppercase for wayfinding and actions, sentence case for lyrical headlines.
- Keep craft claims concrete and supportable.
- Let headings carry the story; keep supporting prose subordinate.

## Do's and Don'ts

### Do

- Keep the display serif at weight 400 and 0.9 line height.
- Use the 1320px container to organize desktop content.
- Retain the curved-window silhouette and compact central identity.
- Keep the default action at 14px mono with 1px tracking.
- Use 60px section padding as the normal editorial rhythm.
- Keep color in daylight imagery while the interface remains sand and ink.
- Preserve the square-edged vertical resource tab as the persistent conversion device.

### Don't

- Do not turn the 46px chapter leads into bold sans-serif headings.
- Do not add rounded pills to replace the underlined discovery action.
- Do not introduce a saturated interface accent to match the blue in the photographs.
- Do not add drop shadows or raised white cards to the flat sand canvas.
- Do not replace the 4px-tracked serif eyebrow with a heavy badge.
- Do not enlarge the centered identity into a full-width wordmark.
- Do not fill the first screen with multiple small images or technical feature lists.

## Motion and responsive

### Motion

**Observed:**

- Headline fragments declare 1.2s transitions with cubic-bezier(0.82, 0, 0.36, 1); eyebrow fragments declare 1s with the same curve.
- The image mask declares a 3s transition with cubic-bezier(0.82, 0, 0.36, 1).
- The header declares top 1.6s cubic-bezier(0.82, 0, 0.36, 1) with a 1.2s delay. Navigation uses clipped normal and duplicate label layers.

**Transfer:**

- Preserve the relationship between a slow stage reveal and shorter word-fragment reveals; keep settled copy fully readable.
- Keep the fixed resource path independent of moving editorial content.

**Unknown:**

- Exact hover and focus appearances, scroll triggers, and the complete entrance sequence are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 768px, 992px, 1090px, 1200px and 1280px.

**Transfer:**

- On narrow screens, preserve the central cusp and generous image presence, but move the caption into a calm part of the image and reflow the headline without clipping words.
- Reduce navigation complexity before shrinking the mono labels; keep the resource action reachable without obscuring the headline.

**Unknown:**

- Mobile type sizes, exact mask geometry, navigation behavior and tab placement are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
