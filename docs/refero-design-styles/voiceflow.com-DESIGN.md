# Voiceflow — editorial landscapes, working systems

## Overview

An airy, light technology style that pairs literary serif headlines with matter-of-fact grotesk text. Cool mist backgrounds, white panels and charcoal chapters give electric blue actions a clear purpose, while sunlit landscapes and tactile nature photography soften the technical subject. Layered interfaces, drifting proof mosaics and faint geometric fields make sophisticated software feel approachable without losing operational credibility.

### Essentials

- Literary promises above working systems: light Tiempos Headline at 72px/1.06 with -0.03em tracking leads the opening; 48px/1.16 serif chapter headings contrast with 24px/1.2 sans feature sentences.
- A landscape is part of the promise, not a thumbnail: center a two-line headline over a 1400px-wide, 390px-high scenic plate that fades into white; float a white proof card over its lower right. Use an original sunlit landscape and a credible outcome card when product-specific photography is unavailable.
- Small blue controls carry the conversion: default buttons are 40px high, 10px rounded, with 11px 20px 9px padding; pair the saturated primary with a restrained gray secondary separated by 8px.
- Color lives inside scenes, not across the whole canvas: #f2f7f7 and near-white dominate the light majority; #397dff is reserved for actions and links. A substantial charcoal capability chapter and dark closing panel create contrast without turning the whole page dark.
- Interfaces sit inside gently machined panels: 10px card corners, 1px pale edges, 24px grid gaps and finely layered shadows; show useful fragments of real work, not a wall of tiny full-screen interfaces.
- Proof has texture and movement: combine mixed-width white quote and metric cards with a faint dot field, fading at the viewport edges. Carry the geometric field into technical illustration; a static SVG dot wave is the minimum equivalent.
- The ending is an invitation embedded in navigation: a 36px/1.2 white serif closing line sits left of four compact link columns inside a #1f2429 panel, with a ruled identity row beneath.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#397dff` | `--color-blue` | action, link, accent | Primary actions, text links, active markers and small branded emblems. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Headline ink | `#1a1e23` | `--color-ink` | text, background | Primary headings and the deepest marketing chapter background. |
| Charcoal | `#1f2429` | `--color-charcoal` | background, surface, text | Footer, technical cards, quote bands and secondary serif headings. |
| Charcoal edge | `#2b3239` | `--color-dark-edge` | border, surface | Rules in dark chapters and raised technical interface panels. |
| Secondary action ink | `#30373f` | `--color-secondary-ink` | text | Gray secondary action labels. |
| Dark secondary fill | `#38414a` | `--color-dark-button` | surface, text | Secondary buttons on dark bands; base text color. |
| Slate text | `#515a63` | `--color-body` | text | Paragraphs and navigation labels on light backgrounds. |
| Muted text | `#6e797b` | `--color-muted` | text | Secondary descriptions, attribution and metric labels. |
| Feature sentence gray | `#7d8688` | `--color-feature-muted` | text | Continuation of a light feature-card title after its darker feature name. |
| Quiet caption | `#9aa1a3` | `--color-caption` | text | Dark-surface labels, footer category headings and small secondary text. |
| Dark secondary label | `#d4d7d7` | `--color-dark-button-label` | text | Labels inside charcoal secondary actions. |
| Pale edge | `#e2e4e5` | `--color-edge` | border, text | Light card outlines and footer links on charcoal. |
| Secondary wash | `#ededed` | `--color-secondary-wash` | surface | Visible result of rgba(25,29,34,0.08) over white for secondary actions; changes subtly with backing. |
| Soft gray panel | `#f1f2f2` | `--color-panel` | surface | Light feature demonstration cards. |
| Cool mist | `#f2f7f7` | `--color-canvas` | background | Default page canvas visible between inset bands. |
| Near-white band | `#fdfdfd` | `--color-band` | surface | Inset rounded marketing bands. |
| White | `#ffffff` | `--color-white` | surface, text | Proof and editorial cards, interface backing and text on dark fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| culture and mission sections | Geometric field backing | `#e2e6e6` | `--color-field` | background | Subdued geometric backdrop. |

## Typography

- **Tiempos Headline-81ad1a66702885c1** — Promises, section headings, editorial titles, long feature quotes and enterprise numerals. Light editorial serif with pronounced contrast, compact letterfit and expressive terminals. If unavailable, use **Newsreader**. Use weight 300 and retain tight tracking; tune line breaks to the original editorial width. Font stack: "Tiempos Headline-81ad1a66702885c1", "Newsreader", Georgia, "Liberation Serif", serif.
- **UCity Pro-8cd2cb40d9534eaf** — Body, navigation, controls, card descriptions and compact proof metrics. Open, rounded grotesk with a friendly but operational voice; regular body and semibold controls. If unavailable, use **DM Sans**. Use 300–600; keep feature names the same weight as their surrounding sentence. Font stack: "UCity Pro-8cd2cb40d9534eaf", "DM Sans", Arial, "Liberation Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Tiempos Headline-81ad1a66702885c1 | 300 | 72px | 1.06 | -0.03em | fixed | Centered two-line landing-page promise. |
| heading-lg | Tiempos Headline-81ad1a66702885c1 | 300 | 48px | 1.16 | -0.02em | fixed | Major capability chapter headings and substantial quotations. |
| heading | Tiempos Headline-81ad1a66702885c1 | 300 | 36px | 1.2 | -0.02em | fixed | Recurring section leads, centered proof statement and closing invitation. |
| feature-lead | UCity Pro-8cd2cb40d9534eaf | 300 | 36px | 1.2 | -0.02em | fixed | Sentence title within a wide product demonstration panel. |
| heading-sm | Tiempos Headline-81ad1a66702885c1 | 300 | 28px | 1.2 | -0.02em | fixed | Editorial rail heading and audience-card headings. |
| feature-title | UCity Pro-8cd2cb40d9534eaf | 400 | 24px | 1.2 | -0.02em | fixed | Feature name and its muted continuation in one sentence. |
| editorial-title | Tiempos Headline-81ad1a66702885c1 | 300 | 20px | 1.3 | -0.02em | fixed | Titles below story and article images. |
| body-lead | UCity Pro-8cd2cb40d9534eaf | 400 | 18px | 1.55 | normal | fixed | Expanded introductory and narrative paragraphs. |
| feature-support | UCity Pro-8cd2cb40d9534eaf | 400 | 18px | 1.5 | normal | size clamp(1rem,1.4vw,1.125rem) | Support text inside the wide demonstration panel. |
| body | UCity Pro-8cd2cb40d9534eaf | 400 | 16px | 1.5 | normal | fixed | Default explanatory copy. |
| hero-support | UCity Pro-8cd2cb40d9534eaf | 400 | 16px | 1.55 | normal | fixed | Centered support paragraph under the opening promise. |
| inline-stat | UCity Pro-8cd2cb40d9534eaf | 600 | 16px | 23px | normal | fixed | Numbers within a compact centered validation line. |
| eyebrow | UCity Pro-8cd2cb40d9534eaf | 600 | 14px | 22px | normal | fixed | Sentence-case section labels above serif headings. |
| navigation | UCity Pro-8cd2cb40d9534eaf | 400 | 14px | 1.75 | normal | fixed | Navigation links and small editorial calls to action. |
| button | UCity Pro-8cd2cb40d9534eaf | 600 | 14px | 1.375 | normal | fixed | Main conversion controls. |
| footer-link | UCity Pro-8cd2cb40d9534eaf | 400 | 14px | 1.5 | normal | fixed | Compact navigation on dark surfaces. |
| proof-quote | UCity Pro-8cd2cb40d9534eaf | 400 | 14px | 22px | normal | fixed | Short quotations in the drifting proof mosaic. |
| caption | UCity Pro-8cd2cb40d9534eaf | 400 | 12px | 17px | normal | fixed | Footer category labels and small explanatory captions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| audience, company and platform pages | page-title | Tiempos Headline-81ad1a66702885c1 | 300 | 64px | 1.125 | -0.04em | fixed | Alternative page opening, centered or split with photography. |
| story directories | story-title | Tiempos Headline-81ad1a66702885c1 | 300 | 64px | 1.04 | -0.03em | fixed | Left-aligned directory promise. |
| enterprise assurance sections | enterprise-stat | Tiempos Headline-81ad1a66702885c1 | 300 | 56px | 1.14 | normal | fixed | Large numerals and baseline-aligned unit suffixes. |
| platform and audience pages | platform-lead | UCity Pro-8cd2cb40d9534eaf | 400 | 18px | 1.75 | normal | fixed | Relaxed support paragraphs in split introductions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep editorial serif headings light, never bold; use tight tracking rather than heavy weight to give large promises authority.
- The feature-card name is darker, not heavier, than the continuation. Keep both parts in a single sans-serif sentence.
- The 72px landing title has a tighter line height than chapter headings; reserve the 64px alternative for supporting page types.
- Use Newsreader and DM Sans as intentional substitutions when the proprietary families are unavailable.

## Layout

**Density:** Airy outside, compact inside: wide narrative pauses surround tightly constructed interface and proof panels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Primary/secondary action gap, small card content gaps and outer band inset. |
| 12px | Editorial-card inset and compact grid gutter variant. |
| 16px | Heading-to-paragraph spacing and quote-card vertical padding. |
| 20px | Control horizontal padding and proof-card horizontal padding. |
| 24px | Default card-grid gaps, eyebrow-to-heading spacing and support-to-action spacing. |
| 32px | Feature title inset and closing heading-to-action gap. |
| 40px | General page gutters and editorial-heading-to-grid separation. |
| 48px | Heading group to product demonstration or tab group. |
| 56px | Inner horizontal gutters in inset capability bands. |
| 64px | Split-column gaps, footer upper padding and footer signoff separation. |
| 80px | Standard major-section top padding. |
| 120px | Capability-band lower padding and long-form section padding. |

### Containers and grids

- **content**: max width 1296px · side padding 40px. Centered ordinary-page content; at 1440px the max-width leaves 72px to each edge.
- **inset-bands**: max width 1424px · side padding 56px. Near-full-width sections sit 8px from the viewport edge, with text and product panels aligned inside.
- **feature-grid**: 6 columns · gap 24px. Two half-width cards followed by three third-width cards; span three and two tracks respectively. Share the structure between light and dark chapters.
- **editorial-grid**: 3 columns · gap 24px. Equal 416px-wide article or story cards in the main container.
- **proof-intro**: max width 1024px · side padding 40px. Centered emblem, statement and inline validation above edge-to-edge proof cards.
- **footer-columns**: 4 columns · gap 24px. Four compact link columns to the right of the closing invitation; the upper split uses a 64px gap.
- **split-hero** (only for platform pages): 2 columns · gap 64px. Equal 616px columns: compact text and low-set customer logos at left, tall scenic photograph at right.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards-and-actions | 10px |
|  | band-and-navigation | 12px |
|  | wide-demonstration | 16px |
|  | circular-icons | 50% |
| navigation and audience-card actions | compact-action | 8px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card-edge | `rgba(22, 26, 30, 0.01) 0px 1px 3px 1px, rgba(22, 26, 30, 0.08) 0px 4px 8px -6px, rgba(22, 26, 30, 0.08) 0px 1px 5px -4px, rgba(22, 26, 30, 0.04) 0px 0px 0px 1px, rgba(22, 26, 30, 0.02) 0px 1px 0px 0px` | White proof and editorial cards have a contact edge, not a dramatic floating shadow. |
| band-edge | `rgb(255, 255, 255) 0px 1.5px 0px 0px inset, rgba(26, 30, 35, 0.02) 0px 1px 0px 0px, rgba(26, 30, 35, 0.04) 0px 0px 0px 1px, rgba(26, 30, 35, 0.04) 0px 1px 8px -4px, rgba(26, 30, 35, 0.04) 0px 4px 12px -6px, rgba(26, 30, 35, 0.01) 0px 1px 3px 1px` | Softly delineated inset marketing bands. |

### Surfaces

#### Canvas · level 0

**Use:** The continuous cool background between content bands.

**CSS:** `background: #f2f7f7`

**Observed:** The light canvas remains visible around rounded near-full-width chapters.

**Transfer:** Preserve the cool cast instead of replacing it with warm cream.

#### Inset light band · level 1

**Use:** Long product and capability chapters.

**CSS:** `background: #fdfdfd; border-radius: 12px; margin: 8px 8px 0px; padding: 80px 0px 120px; box-shadow: rgb(255, 255, 255) 0px 1.5px 0px 0px inset, rgba(26, 30, 35, 0.02) 0px 1px 0px 0px, rgba(26, 30, 35, 0.04) 0px 0px 0px 1px, rgba(26, 30, 35, 0.04) 0px 1px 8px -4px, rgba(26, 30, 35, 0.04) 0px 4px 12px -6px, rgba(26, 30, 35, 0.01) 0px 1px 3px 1px`

**Observed:** A shallow beveled edge separates the band from the canvas; the opening uses the same shell with custom interior spacing.

**Transfer:** Group related capability demonstrations within a band rather than giving every paragraph a separate box.

#### White card · level 2

**Use:** Proof, stories and compact capabilities.

**CSS:** `background: #ffffff; border-radius: 10px; box-shadow: rgba(22, 26, 30, 0.01) 0px 1px 3px 1px, rgba(22, 26, 30, 0.08) 0px 4px 8px -6px, rgba(22, 26, 30, 0.08) 0px 1px 5px -4px, rgba(22, 26, 30, 0.04) 0px 0px 0px 1px, rgba(22, 26, 30, 0.02) 0px 1px 0px 0px`

**Observed:** Fine edge shadows give white cards definition on mist backgrounds.

**Transfer:** Use this material for readable proof over texture or photography.

#### Dark capability band · level 1

**Use:** A deeper technical chapter contrasting with light product explanations.

**CSS:** `background: #1a1e23; border-radius: 12px; margin: 8px 8px 0px; padding: 80px 0px 120px`

**Observed:** White serif introduction sits above charcoal feature cards; the composition matches the light chapter.

**Transfer:** Reserve this contrast for detailed control, extensibility or operational depth.

#### Closing panel · level 1

**Use:** Shared final invitation and site navigation.

**CSS:** `background: #1f2429; border-radius: 12px; padding: 64px 48px 32px; margin: 0px 8px 8px`

**Observed:** The panel contains both conversion and navigation; it is not merely a legal strip.

**Transfer:** Keep the invitation and supporting navigation in one visual object.

#### Navigation veil · level 3

**Use:** Translucent backing behind fixed navigation as content passes beneath.

**CSS:** `border-radius: 12px; backdrop-filter: blur(24px); background: rgba(226, 230, 230, 0.5)`

**Observed:** Two veil layers include white at 0.2 alpha and cool gray at 0.5 alpha; veil opacity changes while the foreground links remain legible.

**Transfer:** Apply opacity to the backdrop layer, never to the links or logo.

## Components

### Navigation link

**Use:** Centered desktop menu links.

**CSS:** `display: flex; align-items: center; padding: 4px 12px; gap: 4px; color: #515a63`

**Text style:** `navigation` — UCity Pro-8cd2cb40d9534eaf 400 · 14px/1.75

**Observed:** A small logo anchors the left, a compact conversion button anchors the right, and the menu sits between. The fixed header reserves 91px including 20px top and bottom spacing; its compact backing becomes more apparent over scrolled content.

**States:** Declared: hover color #1a1e23; focus-visible box-shadow 0px 0px 0px 1px #397dff, outline 0px.

### Primary button

**Use:** Default conversion action on light and dark sections.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background: #397dff; color: #ffffff; border-radius: 10px; padding: 11px 20px 9px; height: 40px; box-shadow: rgba(15, 30, 97, 0.08) 0px 6px 16px -8px, rgba(15, 30, 97, 0.06) 0px 4px 12px -6px, rgba(15, 30, 97, 0.06) 0px 3px 8px -4px, rgba(15, 30, 97, 0.04) 0px 2px 6px -3px, rgba(15, 30, 97, 0.04) 0px 1px 4px -2px, rgba(15, 30, 97, 0.02) 0px 1px 3px -1px, rgba(15, 30, 97, 0.01) 0px 1px 2px 0px, rgba(47, 104, 219, 0.32) 0px -1px 0px 1px inset, rgba(255, 255, 255, 0.32) 0px 1px 2px -1px inset`

**Text style:** `button` — UCity Pro-8cd2cb40d9534eaf 600 · 14px/1.375

**Observed:** The principal action includes a small right arrow. A compact variant in navigation and audience cards is 37px high with 8px corners and 10px 14px 8px padding.

**States:** Declared: hover background-color #2f68db; focus-visible outline 2px solid #397dff, outline-offset 4px and box-shadow 0px 0px 0px 1px #397dff; active background-color #264eb4.

### Secondary button

**Use:** Sales or explanatory action beside the primary on light surfaces.

**CSS:** `background: rgba(25, 29, 34, 0.08); color: #30373f; border-radius: 10px; padding: 11px 20px 9px; height: 40px; box-shadow: rgba(22, 26, 30, 0.02) 0px 0px 0px 1px inset`

**Text style:** `button` — UCity Pro-8cd2cb40d9534eaf 600 · 14px/1.375

**Observed:** Shares the primary action's visual baseline but has no arrow.

**States:** Declared: hover background-color #1a1e231f and color #252b31; focus-visible outline 2px solid #397dff, outline-offset 4px; active background-color #1a1e2333.

### Dark secondary button

**Use:** Secondary action in charcoal chapters and the footer.

**CSS:** `background: #38414a; color: #d4d7d7; border-radius: 10px; padding: 11px 20px 9px; height: 40px; box-shadow: rgba(0, 0, 0, 0.4) 0px 1px 2px -1px, rgba(255, 255, 255, 0.1) 0px 1px 2px -1px inset`

**Text style:** `button` — UCity Pro-8cd2cb40d9534eaf 600 · 14px/1.375

**Observed:** Gray action remains subordinate to the blue button while retaining a small inset highlight.

**States:** Declared: hover background-color #3e4852 and color #e2e4e5; focus-visible outline 2px solid #397dff, outline-offset 4px; active background-color #515a63.

### Feature card

**Use:** Illustrated capability cards in the six-track grid.

**CSS:** `display: flex; flex-direction: column; position: relative; overflow: hidden; background: #f1f2f2; border: 1px solid #e2e4e5; border-radius: 10px`

**Text style:** `feature-title` — UCity Pro-8cd2cb40d9534eaf 400 · 24px/1.2 · tracking -0.02em

**Observed:** A sentence title sits 32px inside the upper edge, with its feature name in ink and continuation muted; a square arrow sits upper right. Interface fragments occupy most of the card below. Dark variants use charcoal fill, a white 0.12-alpha border and white titles with half-opacity continuations.

**Transfer:** Show one useful action or result per card; use two wide cards and three narrower ones when the content supports that emphasis.

### Editorial card

**Use:** Articles and customer stories.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 10px; padding: 12px; max-width: 416px`

**Text style:** `editorial-title` — Tiempos Headline-81ad1a66702885c1 300 · 20px/1.3 · tracking -0.02em

**Observed:** White card material surrounds a landscape image, followed by a serif title and blue Read link. Stories add a muted outcome line and anchor the story link near the bottom; their images carry centered customer marks.

**States:** Declared: hover increases box-shadow; focus-visible box-shadow 0px 0px 0px 1px #397dff, outline 0px.

**Transfer:** Keep image, title, outcome and action separate rather than placing all copy over photography.

### Proof mosaic card

**Use:** Varied logo, quotation and metric tiles in a horizontally extended proof field.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 16px 20px; display: flex; flex-direction: column; justify-content: space-between; max-width: 510.2px`

**Text style:** `proof-quote` — UCity Pro-8cd2cb40d9534eaf 400 · 14px/22px

**Observed:** The same white card material supports short horizontal logo-plus-quote cards, logo-only tiles, and taller outcome cards. Cards are not all equal width or height; the mosaic extends beyond the viewport and fades at both edges.

**Transfer:** Mix concise testimonials, brand marks and real results without making every tile a testimonial paragraph.

### Footer link

**Use:** Navigation inside the closing panel.

**CSS:** `display: flex; align-items: center; padding: 8px 0px; color: #e2e4e5`

**Text style:** `footer-link` — UCity Pro-8cd2cb40d9534eaf 400 · 14px/1.5

**Observed:** Links stack with 4px gaps beneath muted category captions; category-to-links spacing is 20px.

**States:** Declared: hover color #ffffff with underline and text-underline-offset 4px; focus-visible box-shadow 0px 0px 0px 1px #397dff.

### Explore arrow

**Use:** Compact link in the upper-right corner of illustrated feature cards.

**CSS:** `display: grid; align-items: center; width: 48px; height: 48px; background: #ffffff; border: 1px solid #e2e4e5; border-radius: 10px`

**Observed:** A 24px northeast arrow with a 2px square-ended stroke sits at the center. The dark variant uses a raised charcoal backing.

**States:** Declared: hover color #2f68db; focus-visible outline 2px solid currentColor with outline-offset 4px.

**Transfer:** Keep the arrow a separate visible action rather than stretching a blue button across every card.

### Search field

**Only for:** story and resource directories

**Use:** Small search opposite the industry filter.

**CSS:** `display: flex; align-items: center; height: 36px; background: #ffffff; border-radius: 10px; padding: 0px 10px; box-shadow: rgb(226, 228, 229) 0px 0px 0px 1px inset`

**Text style:** `navigation` — UCity Pro-8cd2cb40d9534eaf 400 · 14px/1.75

**Observed:** A magnifier sits inside a 288px-wide field; a smaller select sits at the opposite end of the filter row.

### Audience card

**Only for:** pricing and purchase-path pages

**Use:** Offer two routes according to audience rather than a conventional price matrix.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 10px`

**Text style:** `heading-sm` — Tiempos Headline-81ad1a66702885c1 300 · 28px/1.2 · tracking -0.02em

**Observed:** Two equal white cards contain serif heading, concise description, a 572px-wide nature photograph, a full-width compact blue action, and a ruled list of benefits. Inner sections use 32px padding; neither route is promoted with a bright outer fill.

**Transfer:** Use real buying distinctions and explain next steps; show prices only when appropriate to the new offer.

### Compact capability card

**Only for:** platform overview pages

**Use:** A concise capability or assurance grid without large imagery.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 28px; background: #ffffff; border-radius: 10px`

**Text style:** `body` — UCity Pro-8cd2cb40d9534eaf 400 · 16px/1.5

**Observed:** Small monochrome icon and a short sans title precede a two-to-three-line explanation. Cards use the white card material and form three columns with 12px horizontal and 24px vertical gaps.

## Imagery and graphics

### Scenic opening plate

**Use:** A required atmospheric visual counterweight to the opening promise.

**Observed:** A panoramic coastal road with a car, sunlit hills and blue sea fills the lower opening; the upper edge fades into the white text area. The composition reads as a softly painterly real-world scene, with a white testimonial card over the right and a narrow logo selector beneath.

**Transfer:** Choose a relevant environment or outcome scene with directional sunlight and open space for proof. Without specialized product media, use original landscape photography and a simple, sharply typeset result card.

**Build:** Place a cover image in a wide 390px-high plate with 16px lower corners. Mask the upper region from transparent to opaque by 42% of its height. Let the image sit behind the action area but keep all headline text on white; float a 380px-wide white card in the lower-right region.

### Dot waves and geometric fields

**Use:** Signature background texture behind proof and product fragments.

**Observed:** Very faint gray dots form warped sheets, circular meshes and curved waves. They remain low contrast on the cool canvas and become soft white specks on charcoal; areas of texture fade away around text.

**Transfer:** Include a geometric field even when there is no custom illustration. Prefer a restrained static mesh to a noisy generic gradient.

**Build:** Use SVG circles of 0.5–1px radius on a 10–12px lattice, painted rgba(110,121,123,0.16). Displace rows with a sine wave or map points to latitude rings on a flattened sphere. Apply a broad radial mask so edges dissolve. For dark panels use rgba(255,255,255,0.08); place the field behind the interface, not over its text.

### Product fragments

**Use:** Capability panels and wide demonstrations.

**Observed:** Cropped white interface windows show a few meaningful rows, a workflow, an outcome chart or a task checklist; overlapping cards and soft contact shadows add depth. A broad light panel stages a fan of mobile devices and a central web conversation. Dark variants show code and event logs in raised charcoal windows.

**Transfer:** Use the new product's actual workflow; keep the meaningful action readable and omit irrelevant app chrome. Minimum equivalent: a clean HTML checklist, connected three-node diagram or small outcome chart in the same panel material.

**Build:** Build a clipped panel with a 1px edge and 10px corners. Layer a primary interface window low in the card, then offset one small supporting panel or cursor above it. Use white backing for light scenes and #2b3239 for dark scenes; keep bright status colors confined to the interface.

### Nature-backed demonstrations

**Only for:** platform, audience and editorial pages

**Use:** Portrait feature illustrations, split heroes and wide product stages.

**Observed:** Macro condensation, water reflecting trees, leaf veins and motion-blurred green foliage create tactile photographic backdrops. Crisp interfaces float over or sit inset into these scenes; a split introduction uses a tall sunlit green hillside photograph with defocused foreground flowers.

**Transfer:** Pair real, detailed textures with restrained product UI. Preserve light direction, organic greens and generous photographic area instead of replacing these images with abstract neon art.

### Human and customer photography

**Only for:** company and customer-story pages

**Use:** Story thumbnails, company panorama and team portrait.

**Observed:** Daylit offices, domestic scenes, vehicles and stadiums are warm but softly desaturated. Customer marks are centered on thumbnail imagery. A wide informal outdoor group portrait carries a white serif message card over its lower-left area; a company introduction uses a broad motion-blurred forest panorama.

**Transfer:** Use candid environmental photographs, not isolated headshots or posed stock handshake imagery.

### Fine line ribbons

**Only for:** enterprise assurance and culture sections

**Use:** Wide decorative separators and mission backdrops.

**Observed:** Thin curved lines form shallow arches across dark assurance bands; a pale line field flows behind moving white culture cards.

**Transfer:** Use monochrome line geometry as a restrained texture supporting a special section, not a background for every content block.

**Build:** In a wide SVG, duplicate 20–40 quadratic curves with staggered control points. Use 1px strokes in rgba(255,255,255,0.05) on charcoal, or rgba(110,121,123,0.08) on pale gray. Clip to narrow horizontal bands for assurance sections; use broader diverging ribbons behind culture cards.

### Icons

**Observed:** Feature exploration uses 24px northeast arrows with 2px square-ended strokes in 48px buttons. Small controls use 14–16px symbols; footer social icons are 18px, solid and muted until hover.

**Transfer:** Choose simple geometric outline icons for capabilities and compact filled glyphs for utilities. Match the arrow's stroke and square caps instead of using decorative multicolor icons outside product UI.

## Section recipes

How recurring sections are built.

### First screen: Scenic promise opening

**Observed:** A near-white shell sits 8px inside the cool canvas with 12px corners. A sparse header spans the top. The centered 72px serif promise is constrained to about 720px and breaks into two compact lines; a 602px-wide support paragraph follows after about 22px. Paired actions sit beneath it, then a small tertiary row of circular integration marks. Behind the lower action area, the scenic opening plate fades up into white and occupies most of the bottom half of the first screen. Its white proof card is anchored at lower right. A six-part customer selector runs below the plate, with a fine active underline. Within the first 900px the entire headline, support, actions, main scene, proof card and logo rail are visible; the larger proof mosaic begins later.

**Transfer:** Use two complementary promises—human benefit and accountable result—over an original landscape or relevant environment, retaining the proof-card layer even without custom media. Directory pages instead open left-aligned with a 64px title and a faint sphere; company and purchase-path pages center a 64px title above imagery or cards; a platform page splits text and tall photography.

**Avoid:** Do not replace the scenic first screen with a floating dashboard centered on a saturated gradient, or let a long paragraph push all imagery below the first viewport.

**Text style:** `display` — Tiempos Headline-81ad1a66702885c1 300 · 72px/1.06 · tracking -0.03em

### Proof constellation

**Observed:** The proof-intro container centers a small blue emblem in a pale geometric ring, a 36px serif statement and a compact line of semibold numbers with muted descriptors. A gray explanatory action precedes a wide mosaic of white proof cards over a dot field. Cards fade at the sides; small award badges sit beneath.

**Transfer:** Use verified adoption, usage or outcome signals appropriate to the product. Keep the emblem, varied proof cards and geometric atmosphere, even with fewer customers.

**Text style:** `heading` — Tiempos Headline-81ad1a66702885c1 300 · 36px/1.2 · tracking -0.02em

### Chapter heading pair

**Observed:** An eyebrow precedes a 48px serif statement by 24px, followed by 16px body copy and paired actions after 24px. A large demonstration sits 48px beneath the heading group. Smaller platform sections use 36px headings with 12px spacing around the support text.

**Transfer:** Write a section-level benefit rather than a list of feature nouns; keep the introduction narrower than its full-width illustration.

**Text style:** `heading-lg` — Tiempos Headline-81ad1a66702885c1 300 · 48px/1.16 · tracking -0.02em

### Illustrated capability chapter

**Observed:** The inset light band contains an editorial lead, a compact role-tab rail, a wide gray demonstration panel and the feature-grid composition. The large panel pairs a 36px sans sentence on the left with an enlarged workflow on the right. Feature cards below use the same tone and geometric texture. A dark capability band repeats the grid for deeper technical work.

**Transfer:** Use the broad panel for the most important workflow and the smaller cards for supporting powers. Retain the tonal shift for technical depth without repeating the same interface everywhere.

**Text style:** `feature-title` — UCity Pro-8cd2cb40d9534eaf 400 · 24px/1.2 · tracking -0.02em

### Editorial and story rail

**Observed:** A 28px serif heading precedes a three-column grid of editorial cards at 24px gaps. Story directories begin with filters and a larger spotlight: roughly three-fifths image and two-fifths text with a 36px serif title. Repeated stories use 20px serif titles, muted outcome lines and blue bottom links.

**Transfer:** Use articles, project examples or customer outcomes as appropriate; keep the larger spotlight separate from the repeated grid.

**Text style:** `editorial-title` — Tiempos Headline-81ad1a66702885c1 300 · 20px/1.3 · tracking -0.02em

### Embedded closing invitation

**Observed:** The closing panel puts a 36px serif invitation in a 410px-wide left column, with blue and dark-secondary actions 32px below. Four link columns sit to the right, separated from the invitation by 64px. After the upper area, a 64px pause and a fine dark rule introduce the identity row: small white brand mark at left, quiet copyright and optional locale beneath, three social icons at right. The same composition closes all page types; the story directory omits the locale.

**Transfer:** Make the closing line a direct benefit-oriented invitation and keep the main conversion pair beside navigational closure, rather than adding an unrelated full-screen finale.

**Text style:** `heading` — Tiempos Headline-81ad1a66702885c1 300 · 36px/1.2 · tracking -0.02em

### Audience routes

**Only for:** pricing and purchase-path pages

**Observed:** A centered 64px title leads to two equal audience cards separated by 24px. Each gives a distinct route, nature image, full-width action and five compact benefits rather than a table of dollar amounts. Three nature-backed capability images and a broad tabbed demonstration add value context before the closing panel.

**Transfer:** Separate self-serve and consultative paths or other genuine audience differences. Keep visual weight equal unless the actual offer requires a different hierarchy.

**Text style:** `page-title` — Tiempos Headline-81ad1a66702885c1 300 · 64px/1.125 · tracking -0.04em

### Enterprise assurance

**Only for:** enterprise product pages

**Observed:** A rounded charcoal band pairs a 36px white heading with small muted context. Curved line separators frame three widely spaced metrics; 56px light-serif numerals and unit suffixes share a baseline. Four certification summaries sit beneath with small seals, 14px labels and muted descriptions.

**Transfer:** Use three defensible operational measures and relevant assurances, making units as prominent as the numbers.

**Text style:** `enterprise-stat` — Tiempos Headline-81ad1a66702885c1 300 · 56px/1.14

### Company narrative and culture

**Only for:** company pages

**Observed:** A centered serif belief statement opens above a full-width forest panorama. A white narrative section pairs a broad 18px text column with a pale 36px serif pull quote. Later, an outdoor team image supports an overlapping white message card, a dark trust strip introduces compact metrics, and centered investor tiles precede a mission statement over fine line ribbons and drifting white value cards.

**Transfer:** Tell an actual origin and operating philosophy with a real team photograph. The line-backed culture cards can carry principles, working methods or commitments instead of imitating company values verbatim.

**Text style:** `heading-lg` — Tiempos Headline-81ad1a66702885c1 300 · 48px/1.16 · tracking -0.02em

## Page flow

**Storyline:** Outcome promise → tangible scene or demonstration → social validation → capability depth → relevant next steps → invitation with navigation.

### Broad product marketing landing page

1. **promise** — Centered editorial statement over a scenic plate, with a floating proof card and logo selector.
2. **social proof** — Emblem, compact statistics, drifting quotation mosaic and small award badges.
3. **product demonstration** — Large device composition showing the breadth of real interactions.
4. **capability chapters** — Light feature chapter followed by a matching dark technical chapter.
5. **education** — Three editorial cards connect to deeper thinking.
6. **closing call** — Invitation and navigation share one dark panel.

**Transfer:** Move from emotional credibility to visible operation; adapt the number of chapters to the new product's depth.

### Customer outcome directory

1. **promise** — Left-aligned editorial title, brief context and faint spherical mesh.
2. **discovery** — Industry filter and search lead to an oversized spotlight and a three-column story grid.
3. **testimonial** — Dark serif quotation band with subtle curved dot geometry.
4. **quantified proof** — Centered validation, badges and a broad wall of compact review cards.
5. **closing call** — Shared dark invitation and navigation, without a locale row.

**Transfer:** Organize outcomes for scanning, then reinforce the collection with one memorable quote and compact third-party proof.

### Purchase-path selection

1. **promise** — Centered serif title addresses the team behind the work.
2. **pricing** — Two image-rich audience routes with distinct actions and benefit lists.
3. **value justification** — Three photographic capability illustrations explain breadth, control and visibility.
4. **product demonstration** — Four descriptive tabs introduce a large interface over a photographic backing.
5. **closing call** — Shared dark invitation and navigation.

**Transfer:** Explain who each route is for before listing detailed capabilities; use an audience-led structure when pricing is consultative.

### Company and philosophy narrative

1. **belief** — Centered title and broad motion-blurred nature image.
2. **origin** — Long-form narrative beside a pale pull quote.
3. **human credibility** — Outdoor group photograph with overlapping message card.
4. **social proof** — Dark customer/stat strip followed by centered investor tiles.
5. **principles** — Mission statement and horizontally moving white principle cards on a fine-line backdrop.
6. **closing call** — Shared dark invitation and navigation.

**Transfer:** Alternate reading-heavy narrative with people, trust and philosophy so the page remains human rather than becoming a corporate timeline.

### Platform capability overview

1. **promise** — Split introduction with left-hand copy and logos, tall sunlit nature image at right.
2. **product demonstration** — Four workflow tabs and a broad interface on organic photographic texture.
3. **capabilities** — Six compact text-and-icon cards.
4. **assurance** — Charcoal enterprise metrics and certification summaries.
5. **extension** — Large nature-backed interface scene paired with explanatory copy and a documentation action.
6. **discovery** — Two-by-two platform links with pale sculptural mesh imagery.
7. **closing call** — Shared dark invitation and navigation.

**Transfer:** Make the platform legible through workflow first, then control, trust and extension; finish with practical routes into the product.

## Writing

Confident and outcome-driven, with a warm editorial surface and operational specificity underneath. Technical control is described in plain language, and claims are grounded in actions, customer stories and measurable results.

**Do not copy:** Do not reuse the Voiceflow name, logos, customer marks, award artwork, proprietary interface assets, exact claims, customer counts, performance figures or quotations. Source examples illustrate language patterns, not claims available to a new product.

- **Addressing the reader:** Speak to teams using you and your; use we in company narrative. The product is named when defining its category or role, not in every sentence.
- **Rhythm:** Short, balanced promises; sentence-length benefit headings; one or two concise support sentences. Longer paragraphs belong to company narrative, not conversion blocks. Prefer periods and measured confidence to exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Pair a human outcome with an accountable business result. | 6–12 words | “AI agents customers love. ROI you can prove.” |
| Supporting line | Define the category, the team served and the span of value in one sentence. | 14–22 words | “The AI agent platform that helps CX teams own every customer interaction, from resolution to ROI.” |
| Capability heading | Use a feature noun as the subject of a useful verb phrase. | 5–10 words | “Collaboration brings your team into every improvement”<br>“Agent logs explain every action your agent takes” |
| Proof headline | Name the team, achievement and concrete timescale or result. | 8–16 words | “How Turo built a scalable multilingual support chatbot in two months” |
| Primary action | An ordinary verb and practical next step. | 2–5 words | “Get started”<br>“Talk to sales”<br>“Start building for clients” |
| Closing invitation | Ask the reader to take ownership of the desired outcome. | 6–10 words | “Take control of your AI customer experiences” |

**Words and phrasing to use:** build, launch, improve; control; your team; your business; impact; real numbers; tailor-made; scale; consistent; production

**Avoid:** revolutionary; magical; game-changing as an unsupported claim; effortless everything; future-proof; limitless; excessive AI jargon

**Rules:**

- Lead with the result for the reader, then explain the mechanism.
- Make a feature heading a readable sentence rather than a slogan plus a disconnected label.
- Use numbers only with a clear metric, unit and defensible context.
- Describe complexity as control and practical capability rather than mystique.
- Keep button labels direct; avoid playful or cryptic conversion language.

## Do's and Don'ts

### Do

- Set the default promise in a 72px light serif with -0.03em tracking.
- Keep the cool canvas visible in the 8px gutters around 12px-rounded bands.
- Pair 40px blue and gray actions at an 8px gap.
- Use 24px gaps for the principal image-card grids.
- Keep feature names and continuations at the same 24px weight, differentiated by color.
- Stage crisp interface fragments against faint geometric fields or tactile nature photography.
- Give major capability bands 80px top and 120px bottom breathing room.
- Keep the dark footer invitation at 36px and its supporting links at 14px.

### Don't

- Do not replace the light serif headline hierarchy with bold geometric sans headlines.
- Do not spread action blue into full-page backgrounds or tint every card blue.
- Do not make every proof tile the same dimensions; the varied mosaic is part of the composition.
- Do not turn the default 10px action corners into exaggerated pills; rounded-pill controls belong only to particular specialized actions.
- Do not use deep black for every dark surface; distinguish #1a1e23 chapters, #1f2429 cards and #2b3239 raised details.
- Do not apply navigation veil opacity to the foreground text.
- Do not make dot fields high-contrast polka dots; they should recede beneath the content.
- Do not substitute a dense comparison spreadsheet for the two-route purchase composition when the buying paths are the point.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions animate background-color, color, opacity, box-shadow and border-color over 0.15s; navigation link color changes use 0.2s.
- Declared opening word entrances use 0.5s cubic-bezier(0.2,0.7,0.3,1); the support/action pop uses 0.26s with a 0.595s delay.
- Declared proof drift uses a 192s linear infinite loop; culture-card scrolling uses 36s linear infinite loops.
- Declared product scenes include 4s ease-in-out floating, 12s log arrivals and 20s linear dial rotation.

**Transfer:**

- Keep the opening promise's word entrance short and legible, and reserve slow continuous movement for proof mosaics or geometric/product scenes.
- Preserve a complete readable still composition when recreating an animated field; movement supports depth rather than supplying missing content.

**Unknown:**

- Exact scroll-trigger behavior, full keyframe transforms and reduced-motion variants are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 480px, 540px, 640px, 673px, 740px, 800px, 1200px and 1280px.
- Feature support text declares clamp(1rem,1.4vw,1.125rem).

**Transfer:**

- On narrow screens, preserve the scenic plate and proof card as distinct layers but place the card after the image if necessary to keep both readable.
- Collapse the six-track feature grid into a single reading sequence, keeping feature title before its illustration.
- Stack the closing invitation above the navigation columns; retain the inset shell and fine signoff rule.

**Unknown:**

- Mobile type sizes, actual collapsed navigation behavior and exact grid breakpoint assignments are unknown; stacking guidance is a recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
