# Mapbox — connected product worlds

## Overview

A builder-friendly technology style with bold geometric sans-serif headlines and expansive, predominantly white layouts. Electric blue actions and cool gray structure frame richly detailed product demonstrations, device scenes and real-world photography. The feeling is capable and approachable rather than austere, with dense information reserved for tools, pricing and the directory-like footer. A cinematic dark variant gives visual products a more immersive stage.

### Essentials

- Bold, rounded geometry carries complete promises rather than slogan fragments: Cera pro 700, 56px/1.25 with -0.01em tracking for the main headline; 46px/1.25 for capability chapters.
- The opening pairs language with a working world: a 648px-wide, left-aligned headline group beside a 602×376px rounded demonstration inside a 1344px container. Keep the object, paired actions and an early proof strip visible in the first 900px.
- Conversions look like small blue capsules, not oversized panels: primary and outlined secondary actions share a 52px height, 100px radius and 18px medium text; the header uses a compact 38px version.
- Color belongs to action and demonstration: white and pale #f7f9fc cover most of the default page; #007afc marks links, buttons and short badges. Saturated multicolor imagery stays inside media stages rather than coloring every section.
- Product evidence is tangible and framed: use real interfaces, rendered environments or in-context device footage in 16px-radius cool-gray stages. Every new page needs an authentic product scene; without finished media, construct one focused interface with a believable result rather than abstract decoration.
- A fine routed line connects capability chapters: 1px #e0e4ec rails turn through 24px rounded corners between alternating half-width image-and-copy blocks, separated by 256px. Recreate the routed connector even when the subject has no spatial metaphor.
- The closing invitation has its own architectural frame: a centered 56px headline, 20px support and paired capsules sit within a 1344×424px pale-to-white band, with 128px breathing space above and below. Follow with a practical, multi-column directory rather than a monumental slogan.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#007afc` | `--color-blue` | action, link, accent, surface | Primary actions, text links, selected calculator tracks and announcement badges; not a default full-section fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Utility blue tint | `#cbe4ff` | `--color-tag-wash` | surface | Tiny utility tags attached to footer links. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Secondary action edge | `#a0aaba` | `--color-secondary-edge` | border | Thin outline of the secondary capsule action. |
| Near-black ink | `#0e1012` | `--color-ink` | text, background | Default headings; also the canvas for the immersive dark product variant. |
| Graphite copy | `#333943` | `--color-body` | text | Paragraphs, footer links and small interface explanations on light surfaces. |
| Control edge | `#d5dae2` | `--color-control-edge` | border | Command strip, category badges and numeric-input outlines. |
| Architectural hairline | `#e0e4ec` | `--color-rule` | border | Shared cell edges, section rails and the routed connector; header edges also use this hue at 77.3% opacity. |
| Cool gradient shade | `#eceff5` | `--color-stage-shade` | surface | Upper end of media-stage gradients and fill of the command strip. |
| Cool off-white | `#f7f9fc` | `--color-wash` | background, surface | Section bands, media backings, subdued badges and the top of the closing gradient. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page canvas and raised cards; inverse headings and button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing and usage calculators | Documentation blue wash | `#eff7ff` | `--color-pricing-wash` | surface, border | Documentation chips and small support links. |
| pricing and usage calculators | Muted control label | `#8b96aa` | `--color-muted` | text | Calculator scale values and small supporting labels. |
| immersive product demonstrations and testimonials | Slate edge | `#566171` | `--color-slate` | border, text | Dark secondary-button outlines, device edges and subdued attribution. |
| immersive dark product pages and dark editorial cards | Charcoal band | `#15171b` | `--color-dark-surface` | surface, background | Dark announcements and gradient-backed editorial cards. |
| immersive dark product pages | Raised charcoal | `#161a1d` | `--color-dark-panel` | surface | Inset customer-proof panel, slightly lighter than the dark canvas. |
| immersive dark product pages | Dark hairline | `#1c1f24` | `--color-dark-rule` | border, surface | Dark cell outlines and the light end of dark media gradients. |
| company storytelling and support plans | Editorial charcoal | `#23262d` | `--color-editorial-ink` | text | Company hero text and large plan prices. |
| immersive dark product pages | Silver copy | `#bbc2ce` | `--color-dark-copy` | text, border | Paragraphs and footer links on dark canvases; also device-frame material. |

## Typography

- **Cera pro** — Headings, marketing copy, navigation, actions and footer. Geometric sans-serif with open round forms, friendly proportions and a strong bold cut. OpenType features: "lnum". If unavailable, use **DM Sans**. Use 400, 500 and 700; preserve line breaks and the broad geometric feel. Font stack: "Cera pro", "DM Sans", "Trebuchet MS", sans-serif.
- **ui-monospace** (only for developer command strips) — A copyable installation command beneath a product demonstration. Small regular-width monospace, subordinate to the marketing hierarchy. Font stack: "ui-monospace", Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Cera pro | 700 | 56px | 1.25 | -0.01em | Default hero and major section headings, including the closing invitation. |
| heading | Cera pro | 700 | 46px | 1.25 | -0.01em | Alternating capability chapters. |
| story-heading | Cera pro | 700 | 36px | 1.3 | -0.01em | Large editorial overlays and product announcement titles. |
| card-heading | Cera pro | 700 | 28px | 1.35 | -0.01em | Resource cells and compact value propositions. |
| faq | Cera pro | 500 | 22px | 1.65 | normal | Accordion questions. |
| lead | Cera pro | 400 | 20px | 1.65 | normal | Section support and capability paragraphs. |
| feature-link | Cera pro | 500 | 19px | 1.333 | normal | Blue arrow links beneath capability paragraphs. |
| action | Cera pro | 500 | 18px | 1.333 | normal | Hero and closing capsules. |
| body | Cera pro | 400 | 16px | 1.65 | normal | Resource descriptions and compact marketing paragraphs. |
| small-link | Cera pro | 500 | 16px | 1.333 | normal | Blue arrow links inside resource cells. |
| navigation | Cera pro | 500 | 15px | 1.25 | normal | Main navigation labels. |
| navigation-action | Cera pro | 500 | 15px | 1.333 | normal | Compact header conversion button. |
| footer-link | Cera pro | 400 | 15px | 1.4 | normal | Directory links. |
| eyebrow | Cera pro | 500 | 14px | 1 | 0.1em, uppercase | Short rectangular category and announcement badges. |
| footer-heading | Cera pro | 700 | 14px | 18px | 0.1em, uppercase | Directory category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| immersive dark product openings | dark-display | Cera pro | 700 | 68px | 1.2 | -0.01em | Short centered product name over a cinematic demonstration. |
| design-tool product openings | tool-display | Cera pro | 700 | 56px | 1.15 | -0.02em | Centered two-line outcome headline above a wide editor demonstration. |
| company storytelling | company-display | Cera pro | 700 | 48px | 1.1 | -0.02em | Left-aligned company-purpose headline. |
| support plans | price | Cera pro | 700 | 44px | 48px | -0.02em | Large plan amount; billing period stays small and on the same baseline. |
| company storytelling and support plans | compact-heading | Cera pro | 700 | 32px | 1.2 | -0.02em | Editorial heading pairs and support-plan names. |
| testimonial bands | quote | Cera pro | 500 | 24px | 1.65 | normal | Centered testimonial, with a separate 20px attribution. |
| company storytelling | company-eyebrow | Cera pro | 700 | 16px | 1 | 0.1em, uppercase | Blue company-purpose label without a badge container. |
| design-tool feature comparisons | comparison-caption | Cera pro | 400 | 14px | 20px | -0.01em | One-sentence explanation above paired before-and-after images. |
| pricing and usage calculators | pricing-body | Cera pro | 400 | 14px | 1.65 | normal | Dense product and billing descriptions. |
| developer command strips | command | ui-monospace | 400 | 13.5px | 1.65 | normal | Copyable command, not marketing body text. |

**Notes:**

- Use the same geometric family for nearly everything; technical credibility comes from the content and demonstrations, not a site-wide monospace treatment.
- Default bold headings use -0.01em tracking. The design-tool and company editorial variants tighten to -0.02em and reduce leading; keep these recipes scoped rather than applying their tighter setting everywhere.
- Main paragraphs use 1.65 leading, providing a deliberate contrast to compact medium-weight action labels. Do not increase body weight to imitate the headings.
- Default heroes need not add a support paragraph when the headline itself states the promise; capability chapters and centered chapter introductions do use supporting copy.

## Layout

**Density:** Airy narrative sections with compact navigation and utility controls; shared-edge information grids provide deliberate pockets of density.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer list gaps and compact stacked content. |
| 16px | Small text and media separation. |
| 20px | Section heading to support paragraph. |
| 22.5px | Gap between paired hero actions. |
| 24px | Badge-to-heading and compact content groups. |
| 32px | Raised-card padding and stacked calculator controls. |
| 36px | Named medium spacer. |
| 40px | Resource-cell padding. |
| 43.2px | Global side padding and recurring layout gaps at desktop. |
| 48px | Directory grid gaps and named extra-large spacer. |
| 64px | Small section padding and named huge spacer. |
| 84px | Named small section padding. |
| 108px | Medium section padding and closing-band vertical padding. |
| 128px | Chapter introduction top spacing and space around the closing band. |
| 256px | Vertical separation between alternating capability blocks. |

### Containers and grids

- **main container**: max width 1344px · side padding 43.2px. Centered marketing container; at 1440px the max width leaves 48px visible margins.
- **outer rails**: max width 1440px. Full-width horizontal rules with inset vertical rails following the main container edges.
- **chapter heading**: max width 960px. Centered major heading; support text narrows to 768px.
- **chapter support**: max width 768px. Centered 20px support, generally one to three lines.
- **alternating feature**: 2 columns · gap 94.1px. Media occupies 672px, copy about 578px; the 7% gap uses the container width. Reverse the order on successive blocks and center text vertically.
- **shared-edge grid**: 3 columns · gap 1px. Three joined resource cells per row, about 447px each, with collapsed-looking hairlines rather than separate floating cards.
- **directory grid**: 5 columns · gap 48px. Brand/action column plus four directory groups; the product group spans two internal subcolumns.
- **raised plan grid** (only for support plans): 3 columns · gap 40px. Equal 421px support-plan cards inside the main container.
- **comparison grid** (only for design-tool feature comparisons): 2 columns · gap 112px. Two wide tool-feature descriptions with smaller 462px paired demonstrations underneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 100px |
|  | media stages | 16px |
|  | hero video | 20px |
|  | routed connector corners | 24px |
|  | badges and numeric controls | 4px |
| developer command strips | command strip | 10px |
| support plans and company values | raised cards | 12px |
| immersive dark product pages | proof panel | 24px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| support plans | plan lift | `0px 2px 6px 0px rgba(95, 126, 155, 0.2)` | Subtle blue-gray lift, not a floating dark shadow. |
| design-tool product openings | editor lift | `0px 0px 20px 0px rgba(95, 126, 155, 0.2)` | Soft halo around the broad editor demonstration. |
| company storytelling | values lift | `0px 2px 8px 0px rgba(95, 126, 155, 0.2)` | White value cards on the pale section band. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff; color: #333943`

**Observed:** Near-black headings sit on white; cool hairlines establish structure without texture.

**Transfer:** Keep ordinary landing pages light and reserve complexity for the product scene.

#### Media stage · level 1

**Use:** Backing for composed devices, interfaces and capability demonstrations.

**CSS:** `background: linear-gradient(#eceff5, #f7f9fc); border-radius: 16px; overflow: hidden`

**Observed:** A low-contrast cool gradient sits behind full-color demonstrations. Media is usually half the content width.

**Transfer:** Stage a focused product outcome on the same cool backing instead of placing an unframed image beside text.

#### Architectural frame · level 0

**Use:** Section boundaries, resource grids and routed connective lines.

**CSS:** `border: 1px solid #e0e4ec`

**Observed:** The page uses continuous, shared hairlines rather than shadows to join most sections. Thin routes turn at rounded corners between alternating blocks.

**Transfer:** Use SVG paths or adjacent border segments to connect meaningful chapter centers without crossing copy.

#### Pale band · level 0

**Use:** A quiet change of chapter or explanatory backdrop.

**CSS:** `background: #f7f9fc`

**Observed:** Used behind broad customer demonstrations, company narratives and a run of product capabilities.

**Transfer:** Apply to an entire coherent chapter, not alternating individual cards at random.

#### Closing band · level 0

**Use:** Final conversion invitation.

**CSS:** `background: linear-gradient(#f7f9fc, #ffffff); padding: 108px 43.2px`

**Observed:** Contained by the main rails and horizontal rules, with an airy outer section surrounding it.

**Transfer:** Keep the gradient nearly imperceptible and let type and paired actions do the work.

#### Dark canvas · level 0

**Only for:** immersive dark product pages

**Use:** Cinematic opening and technical product chapters.

**CSS:** `background: #0e1012; color: #bbc2ce`

**Observed:** White headings, blue actions and subdued charcoal rules; light and pale chapters can interrupt this canvas as full bands.

**Transfer:** Use as a distinct page theme, retaining the same hierarchy and structural rails.

#### Dark media stage · level 1

**Only for:** immersive dark product pages

**Use:** Dark demonstrations and editorial-card backings.

**CSS:** `background: linear-gradient(#1c1f24, #15171b); border-radius: 16px`

**Observed:** The gray separation from the canvas remains subtle; actual product media supplies the color.

**Transfer:** Preserve the dark-on-dark hierarchy rather than introducing white card boxes throughout the dark theme.

#### Dark proof panel · level 1

**Only for:** immersive dark product pages

**Use:** Inset customer story.

**CSS:** `background: #161a1d; border-radius: 24px; padding: 96px 80px 112px`

**Observed:** A centered heading and muted logo row sit above a half-media, half-narrative story.

**Transfer:** Use genuine proof in one coherent inset panel.

#### Violet atmosphere · level 0

**Only for:** immersive dark product openings

**Use:** Soft light beneath a large device demonstration.

**CSS:** `background: radial-gradient(46.92% 46.92% at 51.46% 50%, rgba(164, 73, 255, 0.9) 0%, rgba(164, 73, 255, 0) 100%); width: 2000px; height: 2000px; position: absolute; border-radius: 1920px`

**Observed:** Most of the luminous field is behind the device; visible edges read as a restrained violet haze, not a bright purple section.

**Transfer:** Position behind the media layer and clip at section edges; match the soft glow, not a sharp circle.

## Components

### Navigation

**Use:** Fixed top-level orientation and compact conversion.

**CSS:** `height: 63px; padding: 0px 43.2px; background: rgba(255, 255, 255, 0.773); border-bottom: 1px solid rgba(224, 228, 236, 0.773); display: flex; align-items: center`

**Text style:** `navigation` — Cera pro 500 · 15px/1.25

**Observed:** Brand mark left, short dropdown labels through the center, language control, login and a compact blue capsule at right. A separate fixed wrapper holds the navigation. A promotional variant adds a 52px dark-blue announcement strip above it; the dark theme reverses text and canvas. The compact signup uses navigation-action text and 8px 16px padding.

**Transfer:** Keep navigation visually lighter and denser than the opening content; use the promotional strip only for a genuine announcement.

### Primary button

**Use:** Primary hero and closing conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 52px; padding: 15.8px 21px; background: #007afc; color: #ffffff; border: 1px solid #007afc; border-radius: 100px; box-sizing: border-box`

**Text style:** `action` — Cera pro 500 · 18px/1.333

**Observed:** Single short text label with no decorative icon. The fill makes it dominant beside an outlined action. Plan-card actions use 12px 24px padding and a 50px height, spanning the card interior.

**States:** Declared: hover and active outline 0px on the anchor; the compact navigation and plan variants change background and border to #3195ff on hover.

### Secondary button

**Use:** Contact or documentation action paired with primary conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 52px; padding: 15.8px 21px; background: transparent; color: #0e1012; border: 1px solid #a0aaba; border-radius: 100px; box-sizing: border-box`

**Text style:** `action` — Cera pro 500 · 18px/1.333

**Observed:** The secondary action keeps the canvas visible. In dark sections it uses white text with a slate outline.

**States:** Declared: hover and active outline 0px on the anchor.

### Category badge

**Use:** Small technical context above a hero or editorial title.

**CSS:** `display: inline-flex; background: #f7f9fc; color: #0e1012; border: 1px solid #d5dae2; border-radius: 4px; padding: 5.6px 7.7px 4.2px`

**Text style:** `eyebrow` — Cera pro 500 · 14px/1 · tracking 0.1em · uppercase

**Observed:** Rectangular, tightly fitted label rather than a pill. Announcement variants use blue fill with white text; dark story variants use charcoal fill and a subdued edge.

### Arrow text link

**Use:** Capability detail link without adding another button.

**CSS:** `display: inline-flex; align-items: center; color: #007afc; text-decoration: none`

**Text style:** `feature-link` — Cera pro 500 · 19px/1.333

**Observed:** Label and simple right arrow share a baseline. Resource cells use the smaller small-link recipe. The link sits after the paragraph, not embedded in a colored box.

### Resource cell

**Use:** Joined resource, benefit or product-index grid.

**CSS:** `border: 1px solid #e0e4ec; padding: 40px; display: flex; flex-direction: column; background: transparent`

**Text style:** `card-heading` — Cera pro 700 · 28px/1.35 · tracking -0.01em

**Observed:** Heading, body description, then an Arrow text link. Neighboring borders overlap to form one ruled grid; corners stay square. Dark-theme cells change the rule to charcoal and headings to white.

**Transfer:** Keep descriptions short enough for parallel cells to retain a common visual height.

### Editorial story card

**Use:** Image-led announcements and customer stories.

**CSS:** `position: relative; background: #0e1012; color: #ffffff; padding: 48px 43.2px; overflow: hidden`

**Text style:** `story-heading` — Cera pro 700 · 36px/1.3 · tracking -0.01em

**Observed:** Large edge-to-edge image with category badge and bold lower overlay headline. Horizontal carousels expose neighboring cards, separated by thin vertical rules. Rectangular cards contrast with rounded standalone demonstrations.

**Transfer:** Use a darkened, meaningful product or customer image under the text; retain readable white headlines without turning every card into a blue tile.

### FAQ row

**Use:** Objection-handling accordion alongside a chapter heading.

**CSS:** `padding: 32px 40px; border: 1px solid #e0e4ec; display: flex; align-items: center; justify-content: space-between; gap: 24px`

**Text style:** `faq` — Cera pro 500 · 22px/1.65

**Observed:** Questions fill most of the row; a small muted plus sits right. Rows share boundaries and sit in the wider right column, while the large heading occupies the left. The dark variant switches outlines to charcoal and text to white.

### Footer directory

**Use:** Practical end of the page.

**CSS:** `background: #ffffff; color: #333943; padding: 60px 43.2px; border-top: 1px solid #e0e4ec`

**Text style:** `footer-link` — Cera pro 400 · 15px/1.4

**Observed:** Brand and short action list at left; four directory groups occupy the rest, with product subgroups internally split in two. Uppercase footer-heading labels lead 15px regular links at 8px list gaps. Tiny pale-blue utility tags attach to relevant links. A 60px pale bottom strip contains legal text and 24px social marks. Dark pages preserve this architecture with inverse colors.

**States:** Declared: hover on directory links changes text to #007afc; active outline 0px.

**Transfer:** Scale the number of links to the new product while keeping clear groups and the generous separation from the bottom utility strip.

### Command strip

**Only for:** developer command strips

**Use:** Immediately actionable setup beneath a demonstration.

**CSS:** `display: flex; align-items: center; gap: 10px; max-width: 430px; padding: 11px 12px; background: #eceff5; color: #333943; border: 1px solid #d5dae2; border-radius: 10px`

**Text style:** `command` — ui-monospace 400 · 13.5px/1.65

**Observed:** A small centered installation label sits above the strip. Inside, a prompt precedes one code line, with a copy icon aligned at the far end.

**Transfer:** Only use when the product genuinely offers a copyable command; for other products put a concrete next-step utility under the demonstration.

### Support plan card

**Only for:** support plans

**Use:** Compare service levels after usage pricing.

**CSS:** `background: #ffffff; border: 1px solid transparent; border-radius: 12px; box-shadow: 0px 2px 6px 0px rgba(95, 126, 155, 0.2); padding: 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 32px`

**Text style:** `compact-heading` — Cera pro 700 · 32px/1.2 · tracking -0.02em

**Observed:** Plan name, short audience description, large price or conversational alternative, divider, blue-check benefits, then a full-width primary capsule pinned low. Billing interval remains small. No single card is given a loud contrasting fill.

### Numeric usage input

**Only for:** pricing and usage calculators

**Use:** Editable amount paired with a slider.

**CSS:** `background: #ffffff; border: 1px solid #d5dae2; border-radius: 4px; width: 144px; height: 35px; padding: 5px 8px 3px; box-sizing: border-box`

**Observed:** Input sits to the right of a thin blue-and-gray track; a muted metric caption and information icon sit beneath it. The far-right monthly-cost rail remains pale across all rows.

**Transfer:** Preserve alignment between editable usage and resulting price; use real units and billing logic.

## Imagery and graphics

### Working product scene

**Use:** Primary opening demonstration and recurring feature media.

**Observed:** The opening uses real in-car screen footage with daylight reflections and a dark, legible navigation interface, framed in a 602×376px rounded rectangle. Other scenes show phones, tablets, rendered terrain, data layers and editor interfaces. They are full-color, concrete and comparable in scale to the headline.

**Transfer:** Show the new product doing something recognizable in a real environment or a faithful interface. Minimum acceptable version is a well-composed single workflow panel with a visible result and restrained controls, not a generic dashboard collage.

### Layered device and interface compositions

**Use:** Capability chapters and proof panels.

**Observed:** Half-width cool-gradient stages hold one prominent device or a small coordinated set of screens; floating data panels clarify the benefit. Color can be vivid inside the demonstrations, while surrounding copy remains neutral. Edges are clean and the interface is not given a heavy extruded 3D treatment.

**Transfer:** Compose one main result with one or two contextual details on the Media stage. Use domain-relevant data and remove irrelevant controls.

### Routed chapter connector

**Use:** A persistent signature linking alternating feature blocks.

**Observed:** A very pale 1px line descends from the center of a media block, travels sideways through a rounded 24px turn and continues toward the next block. The route occupies the whitespace behind the foreground, with alternating left and right turns.

**Transfer:** Retain this device for any new product, using a routed process line when there is no geographic equivalent.

**Build:** Draw an SVG path behind the feature stack with fill none and stroke #e0e4ec at 1px. Use vertical and horizontal segments with 24px quadratic corner turns; begin near each media center, traverse roughly one quarter of the 1344px container, and connect across the 256px inter-block space. Clip under foreground media and keep the line out of text areas. In dark chapters use #1c1f24.

### Device halo

**Only for:** immersive dark product openings

**Use:** Cinematic product demonstration.

**Observed:** A broad tablet-like frame rises below centered white type. A violet haze blooms behind its lower half; the device has a narrow slate edge, a thicker silver inner rim and a dark inner backing. The media begins in the first screen and continues below it.

**Transfer:** Frame the new product's central visual in a believable display; preserve the restrained halo without making neon the whole theme.

**Build:** Place Violet atmosphere behind a centered device about 1024px wide. Build nested rounded wrappers: 2px slate outer edge with 38px upper corners, 24px silver rim with 36px upper corners, then a dark gradient inner surface with 16px upper corners. Clip real product media inside the inner surface and keep the headline above the luminous area.

### Before-and-after feature pairs

**Only for:** design-tool feature comparisons

**Use:** Explain individual controls visually.

**Observed:** Two adjoining views of the same terrain or data visualization show a single setting change. Small white control chips overlap the lower image edge; the marketing heading above remains unusually large at 46px while its explanation is only 14px.

**Transfer:** Show the same source material in two states, changing only the capability being discussed. Keep the control chip small enough that the result remains dominant.

### Team documentary collage

**Only for:** company storytelling

**Use:** Humanize purpose and culture chapters.

**Observed:** Natural-light workplace and group photography appears in rounded rectangles. One collage stacks three tall scenes at slightly offset heights with small white pill captions; other chapters use a broad group image or two historical images side by side. Color is realistic rather than heavily graded.

**Transfer:** Use genuine working moments and people, framed with the same cool-neutral page structure.

**Build:** For the three-scene collage, arrange three portrait rectangles across a 672px-wide stage, offset the middle upward, round the corners and place small white caption pills across selected seams. Use subtle lift only on captions; keep the backdrop white.

### Connected people sphere

**Only for:** company storytelling openings

**Use:** A visual counterpart to a company-purpose statement.

**Observed:** A large blue-and-white globe fills the right half of the opening, with small circular portraits outlined in white positioned over and around it. The left half remains plain text on white.

**Transfer:** Represent the new organization's reach or collaboration as a similarly simple network object, rather than requiring a geographic globe.

**Build:** Use a shaded blue sphere in SVG or WebGL on a transparent background, add simplified white land or network shapes, and position 44px circular portraits with 2px white borders along its visible surface. Keep it within a 672px square stage and avoid labels or dense topology.

### Icons

**Observed:** Navigation chevrons are small and unobtrusive. Carousel chevrons use thin rounded strokes, while footer social marks are solid 24px silhouettes. Blue 48px outline illustrations introduce pricing benefits; FAQ rows use small muted plus signs.

**Transfer:** Use simple functional chevrons and arrows with restrained stroke weight; keep decorative outline illustrations to compact benefit summaries, not every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Working-world opening

**Observed:** A fixed 63px Navigation sits above a broad white opening; its promotional variant adds a 52px announcement strip. Within the 1344px container, the main composition begins after a generous top margin, with a left copy group and a slightly narrower right demonstration. The left uses Category badge, a three-line display headline about half the container width, then Primary button and Secondary button 34px below. There is no support paragraph in this variant. The right 602×376px video starts higher than the copy, has 20px corners and small pagination marks beneath; a Command strip sits below the media. Back-to-front layers are white canvas, barely visible structural rails, copy and product video, then controls. In the first 900px the entire headline, actions, media, utility and beginning of a monochrome logo strip are visible; editorial news and capability chapters remain below.

**Transfer:** Replace the real-world footage with a faithful product workflow or an in-context use scene of equal visual weight. Keep one concrete next step beneath the demonstration; use the Command strip only for developer tooling. A pricing opening centers a display heading and support above three small benefits; a design-tool opening centers tool-display and a single capsule over a 1224px-wide editor scene; an immersive opening uses dark-display over Device halo; a company opening pairs company-display with a people/network object.

**Avoid:** Do not turn the default into an all-centered text-only hero, put a support paragraph between every headline and action by habit, or shrink the demonstration to a thumbnail. Avoid a full-bleed blue background or giant typographic artwork that competes with the working product.

**Text style:** `display` — Cera pro 700 · 56px/1.25 · tracking -0.01em

### Chapter heading pair

**Observed:** A centered display heading within 960px, followed after 20px by lead copy within 768px. Introductory chapters use 128px top and 108px bottom spacing and meet a full-width hairline.

**Transfer:** Use these as pauses before related capability groups; a badge is not required above every chapter.

**Text style:** `display` — Cera pro 700 · 56px/1.25 · tracking -0.01em

### Alternating connected capability

**Observed:** A 672px Media stage faces a roughly 578px copy block with heading, lead copy 20px below and Arrow text link about 33px later. Text centers vertically against the image. Successive blocks reverse sides, with 256px between them and the Routed chapter connector visible in the gap.

**Transfer:** Explain one concrete capability per block; retain varied media rather than repeating one interface at different scales.

**Text style:** `heading` — Cera pro 700 · 46px/1.25 · tracking -0.01em

### Announcement callout

**Observed:** Inset two-column callout on Pale band or a dark charcoal band. A small blue Category badge precedes a story-heading, lead copy and outlined capsule; a 602×339px demonstration occupies the other half. Hairlines and rails bound the section.

**Transfer:** Give an important new capability a recognizable announcement role without changing the whole design system.

**Text style:** `story-heading` — Cera pro 700 · 36px/1.3 · tracking -0.01em

### Joined resource index

**Observed:** A Chapter heading pair introduces a shared-edge three-column grid of Resource cells, usually two rows. Each cell has a 28px title, 16px description and small blue arrow link; all boundaries remain square and continuous.

**Transfer:** Use for resources, product families or next steps, keeping the grid more directory-like than promotional.

**Text style:** `card-heading` — Cera pro 700 · 28px/1.35 · tracking -0.01em

### Editorial proof carousel

**Observed:** Large Editorial story cards sit in a horizontal track with neighboring cards peeking beyond the viewport. Headline and Category badge overlay product or customer media. Below, 44px square previous/next controls and small outlined rectangular pagination marks distinguish this carousel from the opening's dot controls.

**Transfer:** Use for genuine stories or releases; maintain editorial scale and varied imagery rather than miniaturizing into a row of identical feature tiles.

**Text style:** `story-heading` — Cera pro 700 · 36px/1.3 · tracking -0.01em

### Segmented audience proof

**Observed:** A centered display heading and lead line introduce a wide rounded outline tab rail. A selected pill leads a bordered pale-gradient panel with product media on one side and a badge, 36px title, short paragraph and blue arrow link on the other.

**Transfer:** Translate to relevant audience groups or workflows; show a distinct outcome for the selected group rather than only swapping its title.

**Text style:** `story-heading` — Cera pro 700 · 36px/1.3 · tracking -0.01em

### FAQ split

**Observed:** A large display heading sits in the left column; a roughly 723px-wide stack of FAQ rows fills the right. Questions use medium weight, shared outlines and small plus signs.

**Transfer:** Answer practical adoption objections using clear questions; keep the heading aligned as a section anchor rather than centering it above the list.

**Text style:** `faq` — Cera pro 500 · 22px/1.65

### Framed closing invitation

**Observed:** Closing band sits within an approximately 680px-tall section, leaving 128px above and below the 424px inner band. A centered display heading leads one line of lead text after 20px and paired capsules after 34px. The dark variant fades charcoal into the dark canvas and keeps its thin structural rails.

**Transfer:** Offer a low-friction self-service route and a human-contact route in parallel; a pricing page can ask about billing instead of repeating the signup promise.

**Text style:** `display` — Cera pro 700 · 56px/1.25 · tracking -0.01em

### Directory ending

**Observed:** Footer directory ends every page. Light pages end with a pale utility strip, dark pages with a charcoal strip. The company narrative moves directly from a joined resource index into the directory, without the separate conversion band used by product and pricing pages.

**Transfer:** Maintain a useful end state and adapt categories to the product's actual information architecture.

**Text style:** `footer-link` — Cera pro 400 · 15px/1.4

### Customer demonstration panel

**Only for:** immersive dark product pages

**Observed:** Dark proof panel contains a centered 44px heading, a subdued row of customer marks and a lower two-column story. A rounded device composition takes about half the width, with 20px narrative and a blue link opposite it.

**Transfer:** Use one substantive customer outcome with the product visibly in use; keep partner marks subdued relative to the scene.

**Text style:** `price` — Cera pro 700 · 44px/48px · tracking -0.02em

### Quiet testimonial band

**Only for:** testimonial bands

**Observed:** A pale inset band uses centered quote text across a 1152px maximum width, followed by a separate subdued 20px attribution. Its 24px medium text is intentionally far smaller than chapter headings.

**Transfer:** Give a short, specific customer observation ample whitespace without turning it into giant display typography.

**Text style:** `quote` — Cera pro 500 · 24px/1.65

### Feature comparison gallery

**Only for:** design-tool feature comparisons

**Observed:** Two-column comparison rows use 46px headings, 14px captions after about 15px, then paired image states after about 18px. Rows have 100px separation; small white product-control chips overlap the lower image edge.

**Transfer:** Explain configurable changes through controlled before/after comparisons, with one setting per pair.

**Text style:** `heading` — Cera pro 700 · 46px/1.25 · tracking -0.01em

### Usage pricing ledger

**Only for:** pricing and usage calculators

**Observed:** The opening centers display and lead text above three benefit summaries. A 56px secondary category rail remains below Navigation. Large category names introduce shared-edge rows: product title and documentation chip, 14px description, compact detail action, thin usage slider, Numeric usage input and a persistent pale right-hand cost column. Product rows commonly have 40px vertical padding; the description-to-controls subgrid uses a 72px gap.

**Transfer:** Use this utilitarian ledger for usage-based pricing. Retain explicit units and a visible cost result rather than replacing the page with three generic subscription cards.

**Text style:** `pricing-body` — Cera pro 400 · 14px/1.65

### Plan comparison and regional note

**Only for:** pricing pages

**Observed:** Three Support plan cards follow the usage ledger, using 32px plan headings and 44px price figures. A later pale 16px-radius split panel pairs a region-specific billing explanation with a broad contextual image. The final call changes to a billing question while preserving Closing band construction.

**Transfer:** Separate service packages from usage costs, and isolate genuine regional caveats in a bounded explanatory panel.

**Text style:** `compact-heading` — Cera pro 700 · 32px/1.2 · tracking -0.02em

### Company narrative pair

**Only for:** company storytelling

**Observed:** On Pale band, a 32px left heading highlights a short phrase in blue; 16px text occupies the wider right column. White 12px-radius value cards or paired documentary images follow. Company proof combines a centered logo field and a 24px-radius pale leadership panel with three vertical portraits.

**Transfer:** Use the asymmetric heading/body pair for purpose or history, and give people and real artifacts the visual emphasis rather than inventing product-like UI.

**Text style:** `compact-heading` — Cera pro 700 · 32px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Promise → working demonstration → trust and capability chapters → proof or practical resources → adoption objections → appropriate next step → directory.

### Introduce a broad platform and route different audiences to useful capabilities

1. **Promise** — Split working-world opening with paired actions, a compact setup utility and early monochrome proof strip.
2. **Freshness and demonstration** — Editorial news carousel followed by a broad live product demonstration.
3. **Capability chapters** — Centered introduction, then alternating connected media-and-copy blocks.
4. **Audience proof** — Segmented audience panel and large customer-story cards.
5. **Adoption confidence** — Developer-experience chapters and shared-edge resource index.
6. **Closing call** — Framed conversion band, then the full directory.

**Transfer:** For a broad product, show breadth through individual concrete use scenes, not an undifferentiated feature matrix.

### Explain usage-based costs and service options transparently

1. **Pricing promise** — Centered headline, support and three small icon-led benefit summaries.
2. **Pricing** — Sticky category rail and repeated usage-calculator ledger rows.
3. **Service comparison** — Three raised support-plan cards with large amounts and benefit checks.
4. **Qualification** — Pale split regional billing note with contextual image.
5. **Objection handling** — Billing-oriented closing invitation and directory.

**Transfer:** Keep calculation and billing mechanics primary; separate optional services and exceptions from core metering.

### Make a highly visual product feel both immersive and developer-ready

1. **Promise and demonstration** — Dark centered headline and actions over a violet-backed device scene.
2. **New capability and benefits** — Dark announcement and three joined benefit cells.
3. **Capability chapters** — Centered chapter headings and alternating demonstrations across dark, white and pale full-width chapters.
4. **Customization proof** — A horizontal style gallery and detailed product scenes.
5. **Social proof** — Inset dark customer-story panel.
6. **Practical discovery** — Three editorial news cards and a shared-edge product index.
7. **Objection handling and closing** — Split FAQ, dark framed call and dark directory.

**Transfer:** Use the dark variant when the visual output merits a cinematic stage; preserve light chapters to distinguish explanatory topics.

### Show that a design tool offers powerful control without intimidating the user

1. **Outcome promise** — Centered two-line headline and one action above a broad editor demonstration.
2. **Freshness and capability summary** — Pale announcement followed by three joined benefit cells.
3. **Product demonstration** — Alternating feature scenes and a quietly scaled testimonial band.
4. **Control proof** — Two-column before-and-after feature comparisons.
5. **Customer proof** — Pale customer-example carousel with a large central output.
6. **Objection handling and closing** — Split FAQ, framed signup/contact call and directory.

**Transfer:** Teach controllable outcomes with visual comparisons before introducing deeper technical detail.

### Connect organizational purpose, people and credibility

1. **Purpose** — Split company statement and a large connected-people sphere.
2. **Principles** — Asymmetric heading/body pair on pale background followed by three subtly raised cards.
3. **Human demonstration** — Connected alternating chapters using documentary collages and a simple roles illustration.
4. **History** — Pale editorial heading pair and two-image documentary carousel.
5. **Social proof and people** — Muted customer logo field followed by a broad portrait-led leadership panel.
6. **Further discovery** — Joined impact-resource grid leads straight into the directory.

**Transfer:** Let real people and artifacts replace the product demonstrations; preserve the rails, geometric type and restrained blue vocabulary.

## Writing

Confident, practical and enthusiastic about building. Benefits are paired with specific mechanisms, and enterprise capability is expressed in approachable language rather than ceremonial corporate prose.

**Do not copy:** Do not reuse Mapbox names, logos, customer identities, artwork, command paths, proprietary product labels, performance figures, market claims, prices or testimonial quotations as claims for a new product. Source examples illustrate writing structure only.

- **Addressing the reader:** Address the reader directly with imperative verbs and occasional you/your. Name the product when explaining a capability; use we/our more in company and relationship narratives.
- **Rhythm:** Headlines are usually complete benefit phrases of roughly 4–12 words, occasionally longer in the opening. Supporting copy is one compact paragraph with generous leading; action labels are brief and literal. Technical terms coexist with warm phrases such as start building.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Lead with what the reader can build or achieve, joining concrete objects to an understandable outcome. | 8–14 words | “Build agents, apps, and vehicles that understand the physical world”<br>“Design beautiful custom maps with [Brand] Studio” |
| Capability heading | An active verb plus a specific improvement, often followed by the mechanism. | 4–10 words | “Optimize guidance with customized navigation”<br>“Design life-like landscapes, no code required” |
| Supporting line | Explain what the product enables and name the tools or mechanism that make it credible. | One or two sentences | “Access maps, navigation, search, data, and location AI services via APIs and SDKs in a comprehensive, developer-friendly platform.” |
| Primary action | Short action with a clear commitment level; free or documentation can make the next step explicit. | 2–5 words | “Get started for free”<br>“View documentation” |
| Pricing reassurance | Plain-language benefit followed by a transparent operational explanation. | Brief heading and one sentence | “Flexible pricing options so you can build without friction.”<br>“Automatically get volume pricing as your usage grows, no negotiation necessary.” |
| Closing invitation | A direct question followed by the two realistic ways to proceed. | 4–6 word heading; one support sentence | “Ready to get started?”<br>“Create an account or talk to one of our experts.” |

**Words and phrasing to use:** build; customize; control; flexibility; real-time; cross-platform; ready-to-use; start building; performance; developers; your use case

**Avoid:** revolutionary magic; unlimited superpowers; disrupt everything; vague AI-first jargon; ceremonial corporate language; unsupported superlatives

**Rules:**

- Follow a benefit with a concrete capability or workflow detail.
- Use technical names when they help a reader choose or implement, not as decorative buzzwords.
- Keep resource labels literal and parallel; let the explanatory line carry nuance.
- Make contact and self-service actions equally understandable, while visually prioritizing the self-service route.
- For company copy, describe what people do and how they work rather than relying entirely on mission language.

## Do's and Don'ts

### Do

- Use 56px bold geometric headlines with -0.01em tracking as the default major scale.
- Keep 20px support copy at 1.65 leading and usually within 768px for centered introductions.
- Give the main product scene roughly half the content width and show a genuine result.
- Keep the 1px routed connector visible in the 256px gaps between alternating chapters.
- Use 100px-radius capsules for conversion and 4px-radius rectangles for category labels.
- Use shared 1px outlines and 40px padding in resource grids.
- Keep the closing gradient pale and contained by the same 1344px structural frame.
- Keep 15px directory links compact, grouped and useful after the main narrative.

### Don't

- Do not replace the geometric bold hierarchy with a thin fashion-grotesk or a serif display face.
- Do not spread saturated blue across every background; its default job is action, link and short label.
- Do not apply the 12px raised-plan-card treatment to every resource cell; the core grid is flat and square.
- Do not apply the 68px dark-display or tight 56px tool-display recipe to ordinary capability headings.
- Do not enlarge the 24px testimonial until it competes with the 56px chapter scale.
- Do not make media frames thick, glossy or heavily extruded; the scene is the feature, not the device hardware.
- Do not use a single button style for all controls: 52px conversion capsules, 38px header actions and 35px numeric inputs have distinct roles.
- Do not reduce the ending to a lone logo and copyright line; preserve a navigable directory.

## Motion and responsive

### Motion

**Observed:**

- Declared: primary and secondary button inner surfaces transition border-color and background-color over 0.2s with ease.
- Declared: the command strip transitions border-color and background over 0.15s.
- Declared: support cards transition box-shadow and background-color over 0.4s with cubic-bezier(0.19, 1, 0.22, 1), and color over 50ms.
- Declared: a horizontal marquee animation uses 60s linear infinite; carousel pagination includes changing active widths and opacity.
- Declared: carousel controls have a 2px focus-visible outline with 2px offset in a blue-violet focus color. The large arrow controls are 44px square.

**Transfer:**

- Keep conversion feedback focused on fill and border changes, rather than adding scale or bounce to capsules.
- Use the slow marquee for an early trust strip; keep interactive story carousels distinct from that passive motion.
- If adding the routed connector progressively, preserve the completed static path as the legible design state.

**Unknown:**

- Autoplay cadence, actual scroll-trigger timing and complete animation choreography are unspecified.
- No hover visual is established for every large conversion-button variant; do not infer a new transform behavior.

### Responsive

**Observed:**

- Declared breakpoint families include 479px, 767px, 991px, 1024px, 1200px and 1280px; desktop composition uses a 1344px max-width container.
- The opening layout declares wrapping, and paired action groups wrap.

**Transfer:**

- For narrow layouts, stack copy above the media while retaining the badge, strong headline and main action before the demonstration. Keep the media substantial rather than turning it into an icon.
- Collapse alternating features into a single reading column and redraw the routed line as a simpler vertical connection with rounded turns that do not cross text.
- Reduce resource and plan grids to fewer columns, keep cost labels attached to usage inputs, and regroup footer categories instead of compressing all desktop columns.
- These are adaptation recommendations; preserve the distinct light, dark and editorial roles when changing layout.

**Unknown:**

- Exact mobile headline sizes, side padding, navigation collapse threshold and all mobile arrangements are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
