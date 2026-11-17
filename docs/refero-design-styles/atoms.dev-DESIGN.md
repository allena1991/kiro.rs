# Atoms — orbiting possibilities

## Overview

An approachable software style with a bright, spacious stage and playful evidence of what a product can do. Soft white and pale gray fields, electric blue actions, humanist sans typography and occasional italic serif accents balance practical interface imagery with toy-like characters and globe graphics. It suits creation tools and ambitious product platforms; a charcoal variant makes more technical propositions feel focused rather than austere.

### Essentials

- An outcome sits inside an orbit of examples: a centered 56px/58px medium sans headline and 644px-wide prompt composer are surrounded by six lightly tilted miniature projects on white.
- Headlines sound expansive without shouting: major light-theme chapter titles use IBM Plex Sans 56px/56px at 400; the closing promise introduces a blue IBM Plex Serif italic word at 48px/56px and 600.
- Actions feel like small blue controls, not banners: marketing pills use #4267ff with 14px/22px medium labels; card actions switch to a 7px radius and 40px height.
- Color is contained inside objects: most of the long page remains white or #f6f6f6, while blue proof artwork, colorful character headers and one pastel atmospheric callout supply concentrated saturation.
- Proof is a collection, not a uniform KPI strip: combine an oversized illustrated card with smaller portrait, serif-stat and document cards, using 24px corners and 24px internal padding.
- Give the page an atmospheric final invitation and a monumental sign-off: a 480px-tall pastel panel carries a short promise and prompt bar, followed by a #232324 footer with four ruled columns and an oversized low-contrast wordmark. If no custom artwork exists, use layered gradients and the new product's own typographic name.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#4267ff` | `--color-blue` | action, accent, text | Primary actions, important numbers and italic closing emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle | `#7d9aff` | `--color-hover-blue` | action, text, border | Blue action hover and active fill; italic emphasis and fine highlights on dark product landings. |
| Link indigo | `#425ce1` | `--color-link` | link, text | Small secondary links and blue-toned card text. |
| Proof sky | `#5393fa` | `--color-proof-blue` | surface | Backing of the major illustrated proof card, softened by pale artwork. |
| Atmosphere lavender | `#d2b9ff` | `--color-lavender` | background | Pastel invitation gradient. |
| Atmosphere pink | `#efcbff` | `--color-pink` | background | Pink side of the pastel invitation. |
| Atmosphere mist | `#f3e6f9` | `--color-mist` | background | Near-white transition in the atmospheric invitation. |
| Atmosphere blue | `#5f7bf4` | `--color-gradient-blue` | background | Blue undertone of the invitation gradient. |
| Atmosphere cyan | `#6ddaff` | `--color-cyan` | background | Cool edge of the atmospheric invitation. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text | Opening field, demonstration chapters and raised cards; also the base for inverse text. |
| Soft canvas | `#f6f6f6` | `--color-canvas` | background | Long supporting chapters and catalog or pricing canvases. |
| Inverse ink | `#f3f3f3` | `--color-inverse` | text | Visible rgba(255,255,255,0.95) over technical charcoal; white at 0.95 also labels blue actions. |
| Frosted navigation | `#eeeeee` | `--color-nav-fill` | surface | Visible rgba(230,230,230,0.7) navigation capsule over white. |
| Soft inset | `#ededed` | `--color-soft-fill` | surface, border | Subtle metric panels and inset fields; rgba(12,12,12,0.04) over the soft canvas. |
| Light rule | `#e8e8e8` | `--color-rule` | border, surface | Quiet dividers and neutral card controls; rgba(12,12,12,0.06) on the soft canvas. |
| Muted ink | `#757575` | `--color-muted` | text | Supporting descriptions; rgba(12,12,12,0.55) on the soft canvas. |
| Secondary ink | `#3b3b3b` | `--color-body` | text | Paragraphs; visible result of rgba(12,12,12,0.8) on the soft canvas. |
| Footer charcoal | `#232324` | `--color-footer` | background | Shared deep footer. |
| Primary ink | `#181818` | `--color-ink` | text | Primary headings and labels; rgba(12,12,12,0.95) reads approximately this dark on the light canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing comparisons | Recommended plan wash | `#eff3ff` | `--color-plan-wash` | surface | Visible rgba(61,99,255,0.08) over a white plan card. |
| dark technical product landings | Technical charcoal | `#171717` | `--color-dark-canvas` | background | Default canvas of the technical landing variant. |
| dark technical product landings | Near-black stage | `#0c0c0c` | `--color-dark-panel` | surface | Recessed visual stage inside the dark opening. |
| dark technical product landings | Lifted charcoal | `#202020` | `--color-dark-card` | surface | Visible rgba(255,255,255,0.04) on technical charcoal. |
| dark technical product landings | Inverse secondary | `#d1d1d1` | `--color-inverse-body` | text | Visible rgba(255,255,255,0.8) over technical charcoal. |
| dark technical product landings | Inverse muted | `#a2a2a2` | `--color-inverse-muted` | text | Visible rgba(255,255,255,0.6) over technical charcoal. |
| dark technical product comparisons | Comparison indigo | `#212675` | `--color-comparison` | surface | Continuous highlighted comparison column. |

## Typography

- **IBM Plex Sans** — Headlines, prose, actions and interface-like marketing labels. Humanist sans with open counters and a practical technical tone; regular chapter headings contrast with medium and semibold controls. Font stack: "IBM Plex Sans", ui-sans-serif, system-ui, sans-serif.
- **IBM Plex Serif** — Italic outcome emphasis and editorial numbers. Brisk, slightly literary contrast within an otherwise practical sans system. Font stack: "IBM Plex Serif", serif.
- **IBM Plex Mono** — Small editorial category labels in visual proof cards. Matter-of-fact monospace that reads like a project annotation. Font stack: "IBM Plex Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| faq-heading | IBM Plex Sans | 400 | 64px | 1.125 | normal | fixed | Expansive FAQ chapter headline on general marketing pages. |
| display | IBM Plex Sans | 500 | 56px | 58px | normal | fixed | Centered opening promise; wrap into two compact lines. |
| chapter | IBM Plex Sans | 400 | 56px | 1 | normal | fixed | Default light-theme section headlines. |
| proof-number | IBM Plex Sans | 600 | 56px | 64px | normal | fixed | Major blue or inverse proof statistics. |
| closing-heading | IBM Plex Sans | 600 | 48px | 56px | normal | fixed | Closing promise; also the centered heading size for technical and standalone pricing sections. |
| closing-emphasis | IBM Plex Serif | 600 italic | 48px | 56px | normal | fixed | One outcome word embedded in the closing promise. |
| editorial-number | IBM Plex Serif | 500 italic | 44px | 1 | normal | fixed | Community and adoption numbers in smaller proof cards. |
| lead | IBM Plex Sans | 400 | 20px | 1.4 | normal | fixed | Section introductions and dark opening support. |
| card-title | IBM Plex Sans | 600 | 20px | 1.4 | normal | fixed | Card names, proof headlines and plan names. |
| question | IBM Plex Sans | 500 | 20px | 1.4 | normal | fixed | Accordion questions. |
| feature-label | IBM Plex Sans | 600 | 18px | 26px | normal | fixed | Feature accordion titles and compact catalog titles. |
| body | IBM Plex Sans | 400 | 16px | 1.5 | normal | fixed | Paragraphs, testimonial text and footer links. |
| proof-annotation | IBM Plex Mono | 400 | 16px | 1.5 | normal | fixed | Short media categories and illustrated proof labels. |
| small | IBM Plex Sans | 400 | 14px | 1.5 | normal | fixed | Navigation, plan details and category labels. |
| caption | IBM Plex Sans | 400 | 14px | 22px | normal | fixed | Dense descriptions and secondary labels. |
| action | IBM Plex Sans | 500 | 14px | 22px | normal | fixed | Buttons and short action links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| dark technical product landings | technical-display | IBM Plex Sans | 600 | 72px | 80px | -0.025em | fixed | Left-aligned technical landing headline. |
| dark technical product landings | technical-emphasis | IBM Plex Serif | 500 italic | 72px | 80px | -0.025em | fixed | Concluding phrase within the technical headline. |
| embedded pricing sections | pricing-heading | IBM Plex Sans | 500 | 56px | 1 | normal | fixed | Embedded pricing chapter headline. |
| example and use-case catalogs | catalog-display | IBM Plex Sans | 500 | 56px | 55px | normal | size calc(32px + 1.66667vw) | Centered catalog opening promise. |
| pricing comparisons | price | IBM Plex Sans | 600 | 32px | 39px | normal | fixed | Plan price before smaller cadence text. |
| dark technical product comparisons | comparison-number | IBM Plex Serif | 500 italic | 32px | 1.125 | 0.01em | fixed | New-way outcome in interactive before-and-after metric cards. |
| example and use-case catalogs | catalog-heading | IBM Plex Sans | 600 | 32px | 1.25 | normal | fixed | Left-aligned catalog section headings. |
| example and use-case catalogs | catalog-lead | IBM Plex Sans | 400 | 24px | 1 | normal | fixed | Broad centered catalog introduction. |
| dark technical product landings | technical-eyebrow | IBM Plex Sans | 500 | 12px | 16px | 0.08em, uppercase | fixed | Metric categories and attribution dividers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the default opening medium and chapter headlines regular; do not propagate the technical variant's semibold weight across the light landing.
- Normal tracking is characteristic through most of the system. Negative tracking belongs to the 72px technical opening, while capitals in technical annotations use positive tracking.
- Serif italic is a brief contrast, not a second body font. Keep adjacent sans and serif words on the same headline baseline.

## Layout

**Density:** Airy at section level, compact within controls and proof cards; large breathing intervals surround dense, concrete demonstrations.

### Spacing

**Spacing system:**

- **primary step** 8px — Dominant declared spacing step; 12px and 20px are deliberate secondary intervals rather than rounded replacements.

| Value | Use |
| --- | --- |
| 8px | Related controls and price-to-cadence separation. |
| 12px | Prompt internals and compact nested grids. |
| 16px | Small control side padding and text group gaps. |
| 20px | Carousel gaps and feature chip vertical padding. |
| 24px | Card padding and standard grid gutters. |
| 32px | Action separation and larger panel padding. |
| 40px | Closing headline-to-prompt separation. |
| 48px | Catalog section padding and footer lower-band separation. |
| 64px | Desktop content side gutters and footer top padding. |
| 80px | Default major section padding and grid-to-heading intervals. |
| 128px | Generous light chapter padding. |
| 160px | Technical chapter separation and space after the light closing panel. |

### Containers and grids

- **marketing container**: max width 1620px · side padding 64px. Centered outer content; 1312px of usable width at a 1440px viewport.
- **opening composer**: max width 720px. Composer cap; the opening column is 644px wide at desktop.
- **three-column grid**: 3 columns · gap 24px. Pricing, compact features and use-case cards.
- **footer columns**: 4 columns · gap 80px · side padding 64px. Wide ruled columns with final community column right-aligned.
- **technical content** (only for dark technical product landings): max width 1092px. Inset technical narrative and comparison width, centered within the outer grid.
- **example gallery** (only for example and use-case catalogs): 2 columns · gap 24px. Large 644px-wide example previews.
- **technical specialists** (only for dark technical product landings): 4 columns · gap 24px. Small illustrated specialist cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing pills | 9999px (pill) |
|  | editorial cards | 24px |
|  | structured panels | 16px |
|  | atmospheric callout | 32px |
|  | card buttons | 7px |
| dark technical product landings | small roster tiles | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | soft card lift | `rgba(12, 12, 12, 0.08) 0px 8px 24px -4px, rgba(12, 12, 12, 0.04) 0px 4px 4px 0px` | White carousel and testimonial cards. |
|  | composer edge | `rgba(12, 12, 12, 0.08) 0px 1px 4px 0px` | Opening prompt composer. |
| dark technical product landings | dark stage lift | `rgba(0, 0, 0, 0.45) 0px 24px 64px -16px` | Dark opening roster panel. |

### Surfaces

#### Light stage · level 0

**Use:** Default opening and demonstration sections.

**CSS:** `background: #ffffff`

**Observed:** White is a continuous stage, not a separate rounded page shell.

**Transfer:** Let examples and text carry the structure.

#### Soft chapter band · level 0

**Use:** Supporting feature and social-proof chapters.

**CSS:** `background: #f6f6f6`

**Observed:** Full-width pale-gray bands alternate with white chapters.

**Transfer:** Change the canvas between narrative modes, not between every paragraph.

#### Raised editorial card · level 1

**Use:** Illustrated capability cards and testimonial collections.

**CSS:** `background: #ffffff; border: 1px solid rgba(12,12,12,0.06); border-radius: 24px; padding: 24px; box-shadow: rgba(12, 12, 12, 0.08) 0px 8px 24px -4px, rgba(12, 12, 12, 0.04) 0px 4px 4px 0px`

**Observed:** Rounded white objects lift gently from a pale-gray field.

**Transfer:** Keep shadows local to cards, not on whole sections.

#### Atmospheric invitation · level 0

**Use:** Signature conversion panel.

**CSS:** `background-image: linear-gradient(45deg, #d2b9ff, #efcbff 20%, #f3e6f9 60%, rgba(255,255,255,0)), linear-gradient(-60deg, rgba(255,255,255,0), #5f7bf4 0px, #6ddaff 40%); border: 1px solid rgba(12,12,12,0.12); border-radius: 32px; overflow: hidden`

**Observed:** A broad pastel blend with fine grain, pale pink-lilac on the left and cool blue on the right; the default panel is 480px tall. Catalog invitations use a more horizontal blend and 24px corners.

**Transfer:** Retain the soft luminous color transition behind a very short promise and one white control.

#### Dark technical canvas · level 0

**Only for:** dark technical product landings

**Use:** Alternate product-story theme.

**CSS:** `background: #171717`

**Observed:** A continuous charcoal field replaces the alternating light bands.

**Transfer:** Use the scoped inverse typography and finer light borders throughout this variant.

#### Dark technical card · level 1

**Only for:** dark technical product landings

**Use:** Capability, testimonial and comparison cards.

**CSS:** `background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.12); border-radius: 16px; padding: 24px`

**Observed:** The surface is only slightly brighter than the field, without heavy elevation.

**Transfer:** Use 32px padding for larger explanatory cards.

#### Dark opening stage · level 1

**Only for:** dark technical product landings

**Use:** Compact roster or system diagram beside the opening promise.

**CSS:** `background: radial-gradient(circle at 100% 0%, rgba(66,103,255,0.18), rgba(0,0,0,0) 55%), radial-gradient(circle at 0% 100%, rgba(125,154,255,0.12), rgba(0,0,0,0) 60%), #0c0c0c; border: 1px solid rgba(255,255,255,0.12); border-radius: 24px; padding: 32px; box-shadow: rgba(0, 0, 0, 0.45) 0px 24px 64px -16px`

**Observed:** Subtle opposing blue glows frame small repeated tiles.

**Transfer:** Replace the roster with a real, similarly compact system view.

## Components

### Navigation capsule

**Use:** Compact persistent site navigation.

**CSS:** `background: rgba(230,230,230,0.7); border-radius: 9999px; backdrop-filter: blur(12px); height: 32px; padding: 0px 16px; display: flex; gap: 24px; align-items: center`

**Text style:** `small` — IBM Plex Sans 400 · 14px/1.5

**Observed:** A 56px sticky header places a small symbol-and-name at left, the capsule immediately beside it, and separate login and blue signup pills at right. The dark variant uses a translucent gray capsule.

**States:** Declared: hover navigation text becomes rgba(12,12,12,0.55).

**Transfer:** Keep the menu short and adjacent to the identity rather than centered across the whole screen.

### Primary pill

**Use:** Marketing conversion and signup actions.

**CSS:** `background: #4267ff; color: rgba(255,255,255,0.95); border: none; border-radius: 9999px; height: 32px; padding: 0px 16px; display: inline-flex; align-items: center; justify-content: center; gap: 4px`

**Text style:** `action` — IBM Plex Sans 500 · 14px/22px

**Observed:** Signup uses the compact default. Larger in-page pills use 40px or 48px heights and 24px side padding; the prominent feature CTA reaches 64px. A small arrow may follow the label.

**States:** Declared: hover background #7d9aff; active background #7d9aff.

### Card action

**Use:** Full-width plan and customer-story conversion.

**CSS:** `background: #4267ff; color: rgba(255,255,255,0.95); border: none; border-radius: 7px; height: 40px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — IBM Plex Sans 500 · 14px/22px

**Observed:** A flatter rectangular action anchors the bottom of a story card or the top of a plan feature list. Entry plans use a faint neutral fill; intermediate plans use a pale blue fill with indigo text; the recommended plan uses solid blue.

**States:** Declared: hover background #7d9aff; active background #7d9aff.

### Opening composer

**Use:** Turn the promise into an immediate first interaction.

**CSS:** `background: #ffffff; border: 1px solid rgba(12,12,12,0.12); border-radius: 24px; padding: 16px; max-width: 720px; height: 152px; display: flex; flex-direction: column; gap: 12px; box-shadow: rgba(12, 12, 12, 0.08) 0px 1px 4px 0px`

**Observed:** A multiline plain-language field occupies the upper area; a small blue Start pill with a right arrow sits at lower right.

**Transfer:** If the product cannot accept a prompt, use a real brief, search or signup interaction in the same low-friction composition.

### Closing prompt bar

**Use:** Single-line interaction inside the atmospheric invitation.

**CSS:** `background: #ffffff; border: 1px solid rgba(12,12,12,0.04); border-radius: 40px; padding: 16px 16px 16px 24px; display: flex; align-items: center; justify-content: space-between`

**Observed:** A wide 866px bar in the general landing and 740px bar in the catalog places muted input text left and a compact blue Start action right.

**Transfer:** Keep it visually much simpler than the opening composer.

### Illustrated capability card

**Use:** Make specialist capabilities friendly and scannable.

**CSS:** `background: #ffffff; border: 1px solid rgba(12,12,12,0.06); border-radius: 24px; padding: 24px; box-shadow: rgba(12, 12, 12, 0.08) 0px 8px 24px -4px, rgba(12, 12, 12, 0.04) 0px 4px 4px 0px`

**Text style:** `card-title` — IBM Plex Sans 600 · 20px/1.4

**Observed:** A colorful capsule-backed character comes first, then a role title and short paragraph; a small black circular plus sits at lower right. Cards are about 310px wide in an edge-clipped horizontal carousel.

**Transfer:** Use distinct abstract helpers or friendly object illustrations tied to the new capabilities.

### Feature selector

**Use:** Pair a short benefit list with a changing product preview.

**CSS:** `background: #f6f6f6; border-radius: 32px; padding: 20px 24px`

**Text style:** `feature-label` — IBM Plex Sans 600 · 18px/26px

**Observed:** Content-width rounded rows stack in a white panel; the active row grows to include body text while its associated preview dominates the right side.

**Transfer:** Use concise benefit titles and reveal one explanation at a time.

### FAQ row

**Use:** Wide, low-noise objection handling.

**CSS:** `border-bottom: 1px solid rgba(12,12,12,0.06); padding: 32px 24px; display: flex; justify-content: space-between; gap: 20px`

**Text style:** `question` — IBM Plex Sans 500 · 20px/1.4

**Observed:** Each collapsed row is 93px tall including its rule; a plus icon is aligned at far right. Dark rows replace the divider with white at 0.12.

**Transfer:** Prefer a long readable question to a separate card for every answer.

### Footer column

**Use:** Shared terminal navigation.

**CSS:** `border-top: 1px solid rgba(255,255,255,0.16); padding: 16px 0px 0px; display: flex; flex-direction: column; gap: 24px`

**Text style:** `body` — IBM Plex Sans 400 · 16px/1.5

**Observed:** Muted category label precedes bright links separated by 12px. Four columns sit above the oversized wordmark; social icons, a short slogan, theme control and language pill gather at lower right.

**States:** Declared: hover links become rgba(255,255,255,0.8) and underline.

### Plan card

**Only for:** pricing comparisons

**Use:** Compare offer levels in a three-column grid.

**CSS:** `background: #ffffff; border: 1px solid rgba(12,12,12,0.06); border-radius: 16px; backdrop-filter: blur(10px)`

**Text style:** `price` — IBM Plex Sans 600 · 32px/39px

**Observed:** 24px inner padding contains plan name, large price, cadence, brief positioning, a credit selector, Card action, and small icon-led feature rows. The recommended rightmost card gains a blue outer wrapper and narrow recommendation band with an 8% blue wash inside; nonrecommended cards start 32px lower.

**Transfer:** Keep feature baselines aligned and use the highlight to indicate one genuine recommendation.

### Technical capability card

**Only for:** dark technical product landings

**Use:** Dense capability grids in the technical narrative.

**CSS:** `background: rgba(255,255,255,0.04); border: 1px solid rgba(255,255,255,0.12); border-radius: 16px; padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-title` — IBM Plex Sans 600 · 20px/1.4

**Observed:** Specialist versions start with a colorful character header and end with a small role pill; simpler feature versions are text-only. Larger explanation cards use 32px padding.

**Transfer:** Keep all cards in one grid visually consistent, with color reserved for their illustration or role marker.

## Imagery and graphics

### Orbiting project miniatures

**Use:** Signature opening stage around the central promise.

**Observed:** Six real project previews float around the central column, roughly 236–314px wide, each in a pale rounded frame with a tiny caption. They tilt gently in alternating directions and retain their original rich photography and distinctive designs; no single preview overpowers the centered promise.

**Transfer:** Create six plausible outputs or artifacts for the new product. A minimum version can use polished static UI examples rather than custom 3D artwork.

**Build:** Place three preview cards on each side of a 644px central interaction column. Use 11px frame corners, a 1px low-alpha dark edge and a pale-gray backing; alternate rotations of about 5–10 degrees as design guidance. Keep their centers outside the text column and let the image supply the color.

### Product demonstration scenes

**Use:** Large visual counterpart to capability explanations.

**Observed:** Crisp browser interfaces occupy more space than the accompanying copy, often 792–832px wide. Some are shown directly on white; others sit on cyan-to-periwinkle backings. Floating inspector panes or toolbars overlap the main screen without turning the entire section into a device mockup.

**Transfer:** Show a believable working state of the new product with one highlighted task. Use restrained borders and soft shadows around the main application, not a laptop photograph.

### Friendly capability helpers

**Use:** Illustrated headers and small identity markers for capability families.

**Observed:** Softly shaded, glossy rounded characters with tiny expressive faces and simple occupational props peek from saturated capsule backings. Lavender, yellow, pink, sky blue and green appear locally inside these illustrations; white or charcoal card bodies remain neutral.

**Transfer:** Create original friendly object characters or soft geometric helpers, assigning one color to each capability. The minimum is a rounded shaded form with a simple face and one identifying prop.

**Build:** Use SVG ellipses for the body, two small dark eyes with white glints, a curved mouth and a pale radial highlight. Clip the lower body behind a wide capsule backing about 260px by 100px; put a simple hat, lens or tool above the body. Keep highlights soft rather than metallic.

### Illustrated proof collection

**Use:** Signature proof device paired with heterogeneous metric cards.

**Observed:** A pale blue square-like card carries an oversized dotted globe above a lower-left mono label and large blue number. Nearby smaller cards combine a real customer portrait, italic serif statistic, overlapping avatars, document links and a textured award panel. The globe is pale and finely detailed, not a saturated space scene.

**Transfer:** Represent the new product's reach, scale or workflow with a large delicate dot-based illustration and surround it with genuinely different proof formats.

**Build:** Draw a circular SVG field of small dots with varying opacity, concentrating density to describe a globe or product-relevant silhouette. Use dark neutral dots with occasional blue dots, a near-white radial veil and a sky-blue lower-right wash. Reserve the bottom quarter for the metric; use 24px corners and padding.

### Globe and customer story

**Use:** Spatial social proof for a distributed audience.

**Observed:** A 630px pale globe with thin geographic outlines and blue location dots sits beside a 480px white story card. A project preview occupies the card top, a small identity capsule overlaps the image edge, and body copy ends in a full-width action. The graphic is much larger than the testimonial text.

**Transfer:** Use a globe only when geographic reach is meaningful; otherwise draw a pale network or workflow map with blue nodes tied to the customer stories.

**Build:** Use a pale SVG sphere or circular network with hairline neutral contours. Add blue circular markers and one active marker with layered translucent blue rings; position the story card alongside rather than over the main diagram.

### Pastel atmosphere

**Use:** Signature invitation material.

**Observed:** The light invitation blends pink, lavender, near-white and cyan-blue with a faint fine-grain texture, contained in one broad rounded panel.

**Transfer:** Keep the field luminous and low-contrast enough for dark type. Match the soft glow; exact texture is less important than the pale transition.

**Build:** Use the Atmospheric invitation surface, add a full-size monochrome SVG turbulence texture at 0.1 opacity, and overlay a small pink-to-transparent corner gradient. Keep all layers clipped to the panel.

### Monumental footer name

**Use:** Required terminal graphic on every page type.

**Observed:** A low-contrast dark-gray name graphic, 787px wide and 142px tall, fills the lower-left footer and is clipped by the bottom edge. It balances a much smaller utility cluster on the right.

**Transfer:** Render the new product's own name as oversized heavy typography or vector lettering; keep it tonal, not a bright second headline.

**Build:** Place a wide name SVG or heavy sans text below the link columns, using white at roughly 0.08 over the footer charcoal as design guidance. Set overflow hidden on the footer and align the artwork to its lower-left content edge.

### Technical horizon glow

**Only for:** dark technical product landings

**Use:** Atmospheric terminal conversion panel.

**Observed:** The dark closing card has a deep indigo base and a luminous lavender-blue light pooled along its lower edge, with a few minute star-like marks. It is not simply a flat charcoal card.

**Transfer:** Use the same horizon-like light behind a brief promise and one blue action.

**Build:** Inside a 16px rounded near-black panel, layer a wide elliptical radial gradient at 50% 115% using periwinkle at 0.8 fading through indigo to transparent; add a second broad blue ellipse at the bottom. Blur the color layer about 40px as design guidance and add a few 2px low-opacity white diamond marks.

### Icons

**Observed:** Small filled SVG symbols dominate: 14–16px in links and plan rows, 20–24px for larger controls. Arrows are thin and unobtrusive; plus signs appear at FAQ right edges and in circular card controls.

**Transfer:** Choose simple filled utility glyphs, keeping color inherited from the label. Avoid oversized outlined icon badges except for the illustrated capability identities.

## Section recipes

How recurring sections are built.

### First screen: Orbit and composer opening

**Observed:** A 56px sticky header caps an uninterrupted white first screen. Six tilted framed examples form a loose perimeter around a narrow central column. A small builder-trust line sits above the centered 56px/58px medium two-line outcome headline, which occupies about one third of the screen width. Beneath a 44px separation sits the 644px-wide, 152px-tall Opening composer, its blue Start pill anchored lower right. Back-to-front layers are white field, project miniatures, trust cue and headline, then composer. Within the first 900px the complete promise, trust cue, interaction and all six miniatures are visible; the fuller output gallery belongs to the next scroll rather than competing with the opening.

**Transfer:** Use polished examples of the new product's output around a real first interaction. For a catalog opening, widen the central promise to about 817px, add a 24px support line and replace the composer with one pill while examples remain around it. For a technical landing, use a 72px left-aligned headline with serif emphasis beside a compact dark system panel. Pricing opens directly with a centered 48px heading, one support line, billing toggle and plan grid.

**Avoid:** Do not replace the orbit with a full-bleed application screen, a generic abstract blob or a row of unrelated stock photos; do not put multiple competing CTAs into the central column.

**Text style:** `display` — IBM Plex Sans 500 · 56px/58px

### Chapter heading pair

**Observed:** Regular 56px chapter text sits at the left of the 1312px content field. A supporting block of 20px/28px copy can sit opposite at up to 472px wide, with a short underlined action below. Other proof chapters center the title and leave 56–80px before the visual content.

**Transfer:** Use a brief promise plus a concrete explanation, changing alignment to fit the next visual rather than repeating identical centered headings.

**Text style:** `chapter` — IBM Plex Sans 400 · 56px/1

### Mixed proof bento

**Observed:** An Illustrated proof collection fills the width below a left headline and right pill action. The large globe card is about half the grid width, while a portrait and serif metric share the upper right and document rows fill the space beneath them. Corners are consistently 24px even as card sizes differ.

**Transfer:** Mix one large visual proof item with smaller numerical, human and documentary evidence; preserve varied forms rather than making every proof item a matching statistic.

### Capability carousel

**Observed:** A split Chapter heading pair introduces a horizontally clipped row of Illustrated capability cards, separated by 20px. Neighbor cards remain partially visible at both edges; pale-gray canvas continues behind the row.

**Transfer:** Use the carousel when there are several distinct roles or modes, with a clear illustration and one short outcome for each.

### Selectable product theater

**Observed:** A 56px chapter heading precedes a white 16px-radius panel about 1312px by 666px. Feature selectors occupy the smaller left column and a vivid demonstration fills the larger right column. A separate demonstration series uses a 400px text rail and 832px previews on white, separated vertically by 80px.

**Transfer:** Connect each benefit to a visible state change or concrete screen rather than repeating a static illustration.

### Customer proof stage

**Observed:** A centered 56px heading leads into Globe and customer story on pale gray. A subsequent testimonial wall uses 320px white cards in staggered columns with 16px gutters, bold 20px quote summaries, regular 16px body and small avatar attribution.

**Transfer:** Pair a single deep customer story with a broader collection of shorter authentic reactions; use spatial artwork appropriate to the audience.

### Offer comparison

**Observed:** Centered pricing headline and compact billing toggle lead to three equal Plan cards with 24px gutters. The recommended rightmost offer rises by 32px and has a narrow blue recommendation strip; the rest stays white or faintly tinted.

**Transfer:** Use the same structure for tiers or service packages. A standalone pricing page moves this block to the opening and follows it with billing FAQs, then the shared footer.

### Open-rule questions

**Observed:** The light general landing uses a 64px regular centered heading and 80px gap before wide FAQ rows. Technical and standalone pricing variants use 48px semibold headings and 1092px content width. Catalog questions use a 32px left heading and three small explanatory tiles before the rows.

**Transfer:** Keep questions closely tied to the immediate decision: ownership, effort, fit, billing or next steps.

### Atmospheric close and tonal footer

**Observed:** A centered closing promise uses Closing heading with one blue Closing emphasis word, followed after 40px by Closing prompt bar inside Atmospheric invitation. The panel is inset 64px, and 160px of space separates its bottom from the shared footer. The 524px footer has four Footer columns, the Monumental footer name and a lower-right utility group. Technical landings use Technical horizon glow with a single Card action instead of a prompt bar.

**Transfer:** Retain an atmospheric conversion device and a tonal monumental name somewhere in the page. A focused pricing page can end after objections directly in the same footer rather than adding another conversion panel.

**Text style:** `closing-heading` — IBM Plex Sans 600 · 48px/56px

### Catalog examples and steps

**Only for:** example and use-case catalogs

**Observed:** 32px section headings introduce three image-led category cards with 24px corners, a numbered three-step explanation beside a large preview, then a two-column gallery of 644px-wide examples. Each example has a compact caption and Preview example link below. A later three-column grid uses text-only 16px-radius cards and small pagination controls.

**Transfer:** Separate broad categories, process explanation and concrete examples; use actual outputs with original art direction instead of forcing every preview into the marketing palette.

**Text style:** `catalog-heading` — IBM Plex Sans 600 · 32px/1.25

### Technical outcome comparison

**Only for:** dark technical product comparisons

**Observed:** Four 255px-wide dark metric cards contrast an italic 32px new result with a crossed-out 24px old result; uppercase 12px labels and brief explanations keep the comparison specific. A later table uses a continuous indigo middle column with checkmarks against neutral neighboring columns, 18px by 24px cell padding and fine light rules.

**Transfer:** Compare real outcomes or capabilities with clear criteria, not unsupported superlatives.

**Text style:** `comparison-number` — IBM Plex Serif 500 italic · 32px/1.125 · tracking 0.01em

## Page flow

**Storyline:** Outcome promise → concrete outputs → evidence → capability explanations → customer confidence → offer or comparison → objections → atmospheric invitation and terminal navigation.

### Broad product marketing landing

1. **promise** — Orbiting output miniatures surround a short outcome headline and immediate prompt interaction.
2. **product demonstration** — A six-example gallery expands the opening artifacts into readable outputs.
3. **social proof** — Heterogeneous proof bento and a horizontal trust-logo strip establish breadth.
4. **capability chapters** — Friendly illustrated role carousel, selectable benefit theater and successive large application previews.
5. **customer confidence** — Spatial customer-story stage followed by a staggered testimonial wall.
6. **offer** — Three plans and a compact annual/monthly toggle.
7. **objection handling** — Wide ruled FAQ rows.
8. **closing call** — Pastel prompt invitation followed by the charcoal footer and oversized tonal name.

**Transfer:** Preserve the movement from possibility to working detail to confidence; adapt the number and placement of chapters to the new product.

### Technical product landing

1. **promise** — Dark split hero pairs a large sans-and-serif promise with a compact roster-like system panel.
2. **capability explanation** — Four-column illustrated grid establishes the parts of the system.
3. **quantified proof** — Interactive new-way versus old-way metric cards.
4. **differentiation** — Two-column explanatory cards lead to use-case and supporting capability grids.
5. **social proof** — Compact trust-stat bar, muted logo strip and three testimonial cards.
6. **comparison** — Feature table highlights one continuous indigo column.
7. **objection handling** — Inverse FAQ rows.
8. **closing call** — Luminous horizon panel and one blue action lead into the shared footer.

**Transfer:** Use the dark variant for a focused systems story with more explicit explanation and comparison than the broad landing.

### Focused pricing decision

1. **offer** — Heading and short reassurance sit directly above the billing toggle and three plan cards.
2. **objection handling** — Centered FAQ headline, help link and billing-specific ruled questions.
3. **terminal navigation** — Shared charcoal footer appears directly after the questions; there is no extra atmospheric conversion block.

**Transfer:** Keep the decision surface close to the opening and reserve the rest for purchase friction.

### Examples and use-case discovery

1. **promise** — A broad centered promise is surrounded by floating project artifacts.
2. **orientation** — Three visual categories explain the kinds of outcomes available.
3. **process** — Three numbered steps accompany a large example preview.
4. **product demonstration** — Two-column output gallery with compact preview links.
5. **discovery** — Paginated text-card directory offers more specific starting points.
6. **offer** — The shared plan comparison.
7. **objection handling** — Three small guidance tiles precede FAQ rows.
8. **closing call** — Horizontal pastel invitation and prompt bar, then the shared footer.

**Transfer:** Use the catalog variant to help visitors recognize their own scenario before asking them to choose an offer.

## Writing

Direct, optimistic and commercially practical. It makes ambitious promises approachable by naming concrete outputs and by reminding the reader that they remain in control.

**Do not copy:** Do not reuse Atoms names, mascots, logos, customer quotes, adoption counts, award rankings, research credentials, pricing or performance claims. Replace them with the new product's own identity and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; describe the product by name when explaining what performs the work. Imperatives make the next action feel straightforward.
- **Rhythm:** Short outcome-led headlines alternate with explanatory sentences. Repetition and three-part verb sequences create momentum; descriptions then name tangible tasks, integrations or outputs rather than abstract benefits.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Turn a simple starting point into a desirable finished outcome. | 6–12 words | “Turn ideas into products that sell” |
| Technical promise | Three active verbs followed by the mechanism. | 9–14 words | “Build, launch, and grow with your AI agent team” |
| Support | Brief reassurance with parallel clauses. | 6–20 words for compact support | “Free to start. Flexible to scale.”<br>“No coding. No manual setup. Just describe what you want to build.” |
| Benefit heading | Contrast a fast or complete result with the frustrating alternative. | 5–10 words | “Go live in minutes, not weeks”<br>“Working software, not just code snippets” |
| Primary action | Imperative plus a tangible activity or outcome. | 2–7 words | “Try for free”<br>“Explore what you can build” |
| Process | Tell the reader exactly what to do at each stage. | 4–8 words per step heading | “Describe the result you want”<br>“Open it and make it yours”<br>“Publish and share” |

**Words and phrasing to use:** build; launch; grow; real; your; describe; start; change; publish; in one place; not just; you decide

**Avoid:** revolutionary; synergistic; paradigm shift; unleash limitless potential; effortless magic; autonomous everything

**Rules:**

- Anchor broad promises in specific nouns and tasks in the next sentence.
- Use contrasts to explain a meaningful difference, not to insult competitors.
- Make ease feel credible through the steps involved and what the reader controls.
- Keep action labels short; put reassurance near the action rather than inside it.

## Do's and Don'ts

### Do

- Keep default chapter headlines at 56px/56px and weight 400.
- Stage six colorful output miniatures around a narrow central opening interaction.
- Use 24px gutters and 24px card padding as the main grid recipe.
- Reserve #4267ff for actions and decisive accents while the canvas stays neutral.
- Give illustrated proof and testimonials 24px corners, with only soft local shadows.
- Use 7px corners and 40px height for full-width card actions.
- Include a luminous invitation treatment and a low-contrast monumental footer name.
- Keep dense comparisons inside a 1092px-wide technical narrative.

### Don't

- Do not apply the 72px semibold technical headline to every light-theme chapter.
- Do not turn the marketing canvas into a continuous saturated blue background.
- Do not use serif body paragraphs; keep serif contrast brief and editorial.
- Do not give every metric the same sans number treatment: preserve italic 44px secondary proof.
- Do not make all action shapes identical; pill marketing controls and 7px card controls have distinct roles.
- Do not put heavy drop shadows on the large product demonstration or the page container.
- Do not force the colors inside output examples to match the marketing palette.
- Do not replace the footer's tonal name artwork with a second bright sales headline.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare all-property transitions of 0.15s with cubic-bezier(0.4,0,0.2,1).
- Dark hero text declares a 0.3s entrance with cubic-bezier(0.16,1,0.3,1); capability reveals declare opacity and transform over 0.5s ease-out.
- Logo loops declare 28s linear motion, a document loop 12s linear, and a marquee 40s linear; a small dark hero status dot declares a 2.4s ease-in-out pulse.

**Transfer:**

- Keep movement concentrated in orbiting or cycling examples, proof strips and small status details; keep text readable at rest.
- Use the declared compact button transition for blue-fill feedback and the slower reveal treatment for capability cards.

**Unknown:**

- Precise orbit trajectories, full scroll choreography and the behavior of every interactive comparison face are not established.

### Responsive

**Observed:**

- Styles declare families of breakpoints around 640px, 768px, 1024px, 1280px and 1440px.
- The catalog headline declares calc(32px + 1.66667vw). Technical hero classes declare reduced top/bottom padding of 48px/56px and chapter margins of 80px at narrower layouts.

**Transfer:**

- As design guidance, reduce the orbit to a compact perimeter that never overlaps the central promise or composer.
- Stack the technical headline above its system panel; preserve the serif phrase and blue action rather than shrinking the whole desktop scene.
- Let wide example and pricing grids become fewer columns while maintaining their content order; keep card padding and readable label sizes.

**Unknown:**

- Narrow-screen renders, exact grid-collapse thresholds and mobile navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
