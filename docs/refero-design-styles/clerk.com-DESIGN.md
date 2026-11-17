# Clerk — sculpted software layers

## Overview

A developer-facing style that makes software feel like a finely machined physical object. Bright white and cool gray expanses alternate with charcoal galleries, while violet and icy cyan appear as small signals and pools of light. Bold, tightly set grotesk headlines sit above compact interface scenes, embossed diagrams and restrained dimensional illustrations; the overall composition is spacious even when its cards are information-rich.

### Essentials

- A bold promise above a miniature working world: the default opening uses a left-aligned 56px/64px, 700 headline with -0.035em tracking, a right-aligned 239px × 44px glass action, and a 1200px-wide tabbed product stage below.
- Light and dark behave like separate rooms: use white for the opening, #f7f7f8 for light chapters and #131316 for substantial dark galleries. Keep almost all page area neutral; violet #6c47ff and cyan #5de3ff belong to labels, actions and localized light rather than every panel.
- Small controls feel engineered rather than oversized: ordinary filled buttons are 30px high with 6px corners and 13px/24px medium text; the special opening action is a 44px capsule with overlapping circular symbols.
- Capabilities are illustrated as objects, not a list of icons: use 16px-corner bento cards with 8px seams, 24px text insets, 13px titles and low-contrast sculptural diagrams. Every new landing page needs this dimensional product gallery; simple layered SVG panels with inset edges and a soft directional glow are the fallback.
- Section labels remain conversational: 13px/24px medium sentence-case color labels precede 32px/40px semibold headings by 16px. Preserve the conspicuous jump from the bold opening to these much smaller section leads.
- Theme boundaries have cut shoulders: a 48px transition strip uses short diagonal cuts near the container edges, not a wave or an enormous rounded band. Carry this device into the transition between neutral light and dark rooms.
- Proof closes softly instead of shouting: a 384px text column and two masked vertical streams of 360px-wide testimonial cards share the closing area, followed by a compact five-column directory and an understated copyright/social row. Adapt the proof content, retaining the fading card treatment.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action violet | `#6c47ff` | `--color-violet` | action, accent, text | Small conversion buttons, light-theme section labels and localized light. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ice cyan | `#5de3ff` | `--color-cyan` | text, accent, border, link | Selected dark-theme labels, data emphasis and cool highlights. |
| Lavender label | `#9785ff` | `--color-lavender` | text, accent | Purple labels on dark chapters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | background, surface, text | Opening canvas, elevated light interfaces and dark-theme primary text. |
| Cool pale canvas | `#f7f7f8` | `--color-canvas` | background, surface | Light chapters and default light footer. |
| Pale selection | `#eeeef0` | `--color-selection` | surface, background | Selected opening tab and upper end of bright promotional panels. |
| Pale edge | `#d9d9de` | `--color-edge-light` | border, background | Fine light-theme dividers and lower end of pale promotional gradients. |
| Silver gray | `#b7b8c2` | `--color-secondary-dark` | text | Secondary dark-theme table copy and numeric notes. |
| Dark-theme secondary text | `#9394a1` | `--color-muted-dark` | text | Paragraphs and subdued headings on dark surfaces. |
| Tertiary gray | `#747686` | `--color-subtle-text` | text | Inactive options and tertiary light-theme support. |
| Light-theme secondary text | `#5e5f6e` | `--color-muted-light` | text | Paragraphs and support lines on pale surfaces. |
| Softened ink | `#42434d` | `--color-hover-ink` | text, action | Light-theme link hover and neutral filled button surfaces. |
| Graphite edge | `#2f3037` | `--color-edge-dark` | border, surface | Dark logo-cell borders and miniature control layers. |
| Graphite panel | `#212126` | `--color-panel` | surface | Dark capability cards, visibly separated from the charcoal canvas. |
| Charcoal ink | `#131316` | `--color-ink` | text, background | Primary light-theme text and dark-theme canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Deep pricing canvas | `#0a0a0b` | `--color-pricing-black` | background | Near-black backdrop behind the opening pricing cards. |
| pricing conversion panels | Deep luminous violet | `#561ee3` | `--color-closing-violet` | background | Violet end of the cyan-to-violet conversion panel. |

## Typography

- **suisse** — Marketing headlines, paragraphs and interface-like navigation. Compact neo-grotesk with a high x-height, direct forms and dense bold headlines. If unavailable, use **Inter**. Use 400, 450, 500, 600 and 700; retain the tight headline tracking. Font stack: "suisse", "Inter", Arial, sans-serif.
- **geistNumbers** — Numeric glyphs paired with the main grotesk. Numeral-specific overlay rather than the main letterform family. If unavailable, use **Geist**. Font stack: "geistNumbers", "Geist", Arial, sans-serif.
- **soehneMono** (only for technical explanations and pricing details) — Technical component names and breakdown labels. Restrained small monospace, not a general body face. If unavailable, use **IBM Plex Mono**. Font stack: "soehneMono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | suisse | 700 | 56px | 64px | -0.035em | Default landing-page promise; balanced across two lines. |
| section-heading | suisse | 600 | 32px | 1.25 | -0.015em | Default major chapter headings and closing proof lead. |
| hero-support | suisse | 400 | 18px | 1.55 | normal | Single support sentence under the opening promise. |
| body | suisse | 400 | 15px | 24px | normal | Section paragraphs and benefit descriptions. |
| label-action | suisse | 500 | 13px | 24px | normal | Sentence-case eyebrows, card titles and text actions. |
| caption | suisse | 400 | 13px | 20px | normal | Capability-card paragraphs and testimonial text. |
| nav-label | suisse | 500 | 13px | 1.53 | normal | Navigation and small utility buttons. |
| footer-link | suisse | 500 | 13px | 16px | normal | Directory links. |
| footer-label | suisse | 450 | 13px | 16px | normal | Muted category labels above footer link lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail and technical campaign openings | centered-display | suisse | 700 | 64px | 72px | -0.025em | Centered product-detail and technical campaign promises. |
| pricing openings | pricing-display | suisse | 700 | 64px | 1.12 | -0.035em | Centered pricing promise. |
| company storytelling | company-display | suisse | 700 | 64px | 72px | -0.035em | Mission statement beneath a dimensional emblem. |
| product-detail, pricing and technical campaign pages | compact-heading | suisse | 600 | 32px | 1.12 | -0.015em | Tighter multi-line capability headings and short plan prices. |
| company storytelling | feature-quote | suisse | 450 | 24px | 32px | normal | One prominent quotation, kept narrower than the page. |
| company storytelling | company-heading | suisse | 600 | 20px | 1.4 | -0.015em | Supporter and people-section headings. |
| FAQ sections | question | suisse | 500 | 15px | 24px | normal | Disclosure questions. |
| pricing details | technical-eyebrow | soehneMono | 500 | 11px | 20px | 0.1em, uppercase | Breakdown label above a detailed comparison. |

**Notes:**

- The 56px opening is intentionally much bolder and tighter than the 32px section scale. Do not enlarge all subsequent headings to compete with it.
- Core labels use sentence case and no extra tracking; widely tracked uppercase mono belongs only to detailed technical breakdowns.
- Use the main grotesk for letters with the numeral family as a numeric overlay. Product demonstrations may carry their own small UI typography without changing the marketing type system.

## Layout

**Density:** Airy between chapters, tightly packed inside product galleries and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Bento seams, compact icon spacing and title-to-card-copy gaps. |
| 12px | Filled-button horizontal padding and compact stacked text gaps. |
| 16px | Eyebrow-to-heading and heading-to-support gaps; pricing-card seams. |
| 20px | Testimonial card padding. |
| 24px | Capability-card text insets and FAQ vertical padding. |
| 32px | Desktop container side padding. |
| 48px | Angled theme-transition strips. |
| 56px | Opening introduction-to-product-stage gap. |
| 64px | Section introduction-to-gallery gap and paired-chapter column gap. |
| 80px | Text-to-product split gap and broad promotional-panel padding. |
| 112px | Closing proof area's upper breathing room. |
| 128px | Main chapter top padding and footer separation. |
| 172px | Dark-chapter bottom padding including the transition allowance. |

### Containers and grids

- **container**: max width 1264px · side padding 32px. Centered outer wrapper; yields 1200px of working content at desktop.
- **bento-grid**: 3 columns · gap 8px. Equal-width columns with tall cards spanning two standard rows; wide cards can span two columns.
- **text-product-split**: gap 80px. A 384px text column beside a 736px product object in the 1200px working area.
- **paired-chapters**: 2 columns · gap 64px. Two centered introductions with a separate rectilinear logo or object grid below each.
- **footer-directory**: 5 columns · gap 16px. Five 167px link columns occupying the right three quarters, with the small brand mark in the left quarter.
- **pricing-grid** (only for pricing pages): 4 columns · gap 16px. Four 288px plan shells aligned across the working area.

## Corner radius

| Element | Radius |
| --- | --- |
| ordinary-buttons | 6px |
| capability-cards | 16px |
| navigation-and-proof | 12px |
| opening-stage | 16.5px |
| opening-tab | 12.5px |
| glass-action | 22px |
| circular-symbols | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| dark-card-edge | `inset 0px 1px 0px rgba(255,255,255,0.025), inset 0px 0px 0px 1px rgba(255,255,255,0.025)` | Low-contrast separation without a bright stroke. |
| glass-action | `0px 8px 16px rgba(0,0,0,0.06), 0px 2px 4px -1px rgba(0,0,0,0.08), 0px 1px 1px -0.5px rgba(0,0,0,0.16)` | Small opening capsule suspended above the page. |
| proof-card | `0px 0px 0px 0.5px rgba(0,0,0,0.1), 0px 2px 10px -4px rgba(0,0,0,0.06), 0px 8px 12px -4px rgba(0,0,0,0.06)` | Fine outlines and soft lift for closing testimonial cards. |

### Surfaces

#### Pale canvas · level 0

**Use:** Default light chapters.

**CSS:** `background: #f7f7f8; color: #131316`

#### White opening · level 0

**Use:** Default first-screen stage.

**CSS:** `background: #ffffff; color: #131316`

#### Dark gallery · level 0

**Use:** Capability and ecosystem rooms.

**CSS:** `background: #131316; color: #ffffff`

**Observed:** Full-width dark bands, not isolated black cards floating on a permanently white page.

**Transfer:** Change theme for a complete chapter and switch the text and edge roles together.

#### Dark capability panel · level 1

**Use:** Dimensional benefit illustrations.

**CSS:** `background: #212126; border-radius: 16px; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.025), inset 0px 0px 0px 1px rgba(255,255,255,0.025); overflow: hidden`

**Observed:** The card artwork remains graphite-on-graphite with small highlights; text sits in a separate, legible inset layer.

**Transfer:** Keep object contrast lower than headline contrast.

#### Light capability panel · level 1

**Use:** Bright counterpart to the dark benefit gallery.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 1px 1px rgba(0,0,0,0.05), 0px 4px 6px rgba(34,42,53,0.04)`

**Observed:** Milky white UI fragments and portrait chips sit above soft gray backing.

**Transfer:** Preserve restrained lift and faint outlines rather than adding a hard border.

#### Bright campaign panel · level 1

**Only for:** technical comparison promotions

**Use:** A deliberate light interruption within a dark page.

**CSS:** `background: linear-gradient(#eeeef0, #d9d9de); border-radius: 16px; padding: 0px 28px 28px; color: #131316`

**Observed:** A centered dark input-like object overlaps the upper edge, with four tilted app tiles scattered around a centered headline and violet button.

**Transfer:** Stage a small representative product interaction above the panel, not a generic stock illustration.

#### Luminous conversion panel · level 1

**Only for:** pricing conversion panels

**Use:** High-color conversion moment after dense comparison content.

**CSS:** `background: radial-gradient(100% 100% at 50% 0px, rgba(0,0,0,0) 31.25%, rgba(0,0,0,0.4) 100%), radial-gradient(200% 160% at -20% -80%, #5de3ff 0%, #561ee3 100%); border-radius: 12px; padding: 80px; color: #ffffff`

**Observed:** A 1200px-wide panel, 362px high, combining a concise promise, supporting reassurance and a small action.

**Transfer:** Reserve this much saturation for one bounded conversion moment, not the overall page.

## Components

### Floating navigation

**Use:** Persistent desktop navigation across themes.

**CSS:** `display: flex; align-items: center; background: rgba(248,248,248,0.9); border-radius: 12px; padding: 8px 8px 8px 12px; height: 42px; box-shadow: inset 0px 0px 0px 0.5px rgba(255,255,255,0.9), 0px 0px 0px 0.5px rgba(19,19,22,0.15), 0px 2px 3px rgba(0,0,0,0.04)`

**Text style:** `nav-label` — suisse 500 · 13px/1.53

**Observed:** A slim 1228px bar slightly wider than the working content, with a small mark, left-side menu groups and right-side sign-in utilities. Sticky positioning keeps it close to the upper edge. Dark rooms use a translucent charcoal variant.

**Transfer:** Keep the mark and menus compact; preserve the floating edge rather than a full-bleed masthead.

### Utility button

**Use:** Sign-in and sign-up actions in the header.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 26px; padding: 0px 10px; border: 0.5px solid transparent; border-radius: 6px; color: #131316`

**Text style:** `nav-label` — suisse 500 · 13px/1.53

**Observed:** A compact pair divided visually from the navigation; the default does not use a loud violet fill.

**States:** Declared: hover border-color rgba(19,19,22,0.12) and background-color rgba(19,19,22,0.02); focus-visible outline 2px solid #131316 with 2px offset. Dark variant uses white outline and a white 5% hover fill.

### Glass copy action

**Use:** Default opening conversion device for an assisted or copyable workflow.

**CSS:** `display: flex; align-items: center; width: 239px; height: 44px; background: rgba(247,247,248,0.85); border-radius: 22px; backdrop-filter: blur(12px); box-shadow: 0px 8px 16px rgba(0,0,0,0.06), 0px 2px 4px -1px rgba(0,0,0,0.08), 0px 1px 1px -0.5px rgba(0,0,0,0.16)`

**Text style:** `caption` — suisse 400 · 13px/20px

**Observed:** Overlapping 30px circular tool symbols at left and a dark 110px × 30px inner capsule at right. White circular symbols have fine bevels; dark symbols carry a narrow highlight.

**Transfer:** Use a copyable starter, configuration, or first useful operation; retain the compact tactile outer shell.

### Violet button

**Use:** Explicit conversion actions outside the default opening capsule.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #6c47ff; color: #ffffff; height: 30px; padding: 0px 12px; border-radius: 6px; box-shadow: 0px 0px 0px 0.5px #6c47ff, inset 0px 1px 0px rgba(255,255,255,0.07)`

**Text style:** `label-action` — suisse 500 · 13px/24px

**Observed:** A tiny directional arrow can end the label. Pricing gives the entry plan violet while paid-plan actions use graphite-gray fill; the visual hierarchy is not a giant recommended-plan badge.

**States:** Declared: focus-visible outline 2px solid #ffffff with 2px offset.

### Arrow text link

**Use:** Explore a capability or browse a category.

**CSS:** `display: inline-flex; align-items: center; height: 24px; color: #131316`

**Text style:** `label-action` — suisse 500 · 13px/24px

**Observed:** A 10px directional icon follows with an 8px gap and reduced opacity. The dark-room version is white.

**States:** Declared: focus-visible outline 2px solid #131316 with 2px offset; dark variant uses white.

### Product stage tabs

**Use:** Switch between product scenarios above a major demonstration.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 4px; padding: 5px 4px 2px; position: relative`

**Text style:** `label-action` — suisse 500 · 13px/24px

**Observed:** Four equal 295px × 36px tabs span the stage; the selected backing is pale gray with 12.5px corners and a violet dot. Inactive dots are fine outlined circles. The enclosing stage has 16.5px corners and an extremely faint inset edge.

**Transfer:** Use scenario names rather than full descriptions.

### Capability card

**Use:** Explain one capability through short copy and a physicalized product object.

**CSS:** `display: flex; flex-direction: column; background: #212126; border-radius: 16px; overflow: hidden; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.025), inset 0px 0px 0px 1px rgba(255,255,255,0.025)`

**Text style:** `label-action` — suisse 500 · 13px/24px

**Observed:** Standard cards are about 395px × 260px, tall cards about twice that height. Text uses a 24px inset, then an 8px gap into caption copy; some objects precede the copy and some follow it. A wide card spans two columns. Light chapters use the Light capability panel.

**Transfer:** Give each object a different silhouette while preserving shared lighting and edge treatment.

### Outlined logo cell

**Use:** Ecosystem or compatibility proof.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #131316; border: 1px solid #2f3037; padding: 32px 0px`

**Observed:** Rectangular cells share edges without rounded corners. Monochrome outlined marks are centered, with lower edges fading into the dark canvas. Cells vary between roughly 140px and 279px in height.

**States:** Declared: focus-visible outline 2px solid #ffffff with 2px offset.

**Transfer:** Use legitimate partner marks or simple product-category symbols in the same low-contrast outline treatment.

### Testimonial card

**Use:** Closing peer proof in fading vertical streams.

**CSS:** `display: flex; flex-direction: column; gap: 24px; width: 360px; background: #f7f7f8; border-radius: 12px; padding: 20px; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.1), 0px 2px 10px -4px rgba(0,0,0,0.06), 0px 8px 12px -4px rgba(0,0,0,0.06)`

**Text style:** `caption` — suisse 400 · 13px/20px

**Observed:** Variable-height quotes keep natural paragraph rhythm above a small portrait, name and muted role. Two streams sit in a 584px-high masked window with 16px vertical card gaps. The dark variant uses charcoal and subtle pale edges.

**States:** Declared: hover background-color #ffffff; focus-visible outline 2px solid #131316 with 2px offset.

### Footer directory

**Use:** Low-volume ending on either theme.

**CSS:** `display: grid; grid-template-columns: repeat(5, minmax(0px, 1fr)); column-gap: 16px; row-gap: 32px`

**Text style:** `footer-link` — suisse 500 · 13px/16px

**Observed:** Muted category labels precede links by 20px; link rows use 12px spacing. The small mark sits apart on the left. Below, a faint top rule separates copyright at left from five 16px social icons at right, with 80px bottom breathing room.

**Transfer:** Use useful product, resources, organization and legal groups; do not turn the ending into a second hero.

### FAQ disclosure

**Only for:** FAQ sections

**Use:** Answer practical adoption or pricing objections.

**CSS:** `display: flex; justify-content: space-between; gap: 12px; padding: 24px 0px; color: #ffffff; border-bottom: 1px solid rgba(255,255,255,0.1)`

**Text style:** `question` — suisse 500 · 15px/24px

**Observed:** A broad unboxed text row ending in a 20px muted chevron. Rows are 73px including the divider, growing when a question wraps. A compact heading sits in a separate left column.

**Transfer:** Keep the FAQ visually spare after dense comparison content.

## Imagery and graphics

### Sculpted product miniatures

**Use:** Signature capability illustrations within the bento gallery.

**Observed:** Graphite objects include small beveled discs, a laptop-like session panel, softly embossed hardware, dim rectangular inputs and short signal trails. Directional light comes from above; the illustration often occupies over half the card while the copy stays compact. Light variants turn these into white frosted UI fragments and portrait chips.

**Transfer:** Recast the new product's core operations as one or two tangible interface objects per card. Minimum treatment is layered vector panels with an inset edge, shallow extrusion, soft overhead highlight and one localized cool glow.

**Build:** Layer rounded SVG rectangles and circles using #131316, #212126 and #2f3037. Add a top-left white highlight at 5–10% alpha, an offset dark duplicate for shallow depth, and a small cyan 20% alpha ellipse blurred 8px behind a focal edge. Fade object bottoms with a canvas-colored gradient; keep the illustration subordinate to white titles.

### Layered interface stage

**Use:** Dominant opening product object and later split demonstrations.

**Observed:** Realistic light product interfaces overlap on an almost white stage. The center form is sharpest; adjacent panels recede through a white atmospheric veil. Thin borders, soft gray shadows and faint cyan/lavender light make the product feel suspended. The stage spans the full working width; later demonstrations occupy about three fifths of it.

**Transfer:** Show a credible first useful workflow for the new product. Use one crisp functional panel with two partial contextual panels; never replace the entire scene with a featureless rectangle.

**Build:** Use a pale base panel with 16.5px corners and a 6% charcoal inset edge. Stack three white interface panels at different depths. Place broad cyan and violet low-alpha ellipses behind them and blur by 32px; use white gradient masks on the receding panels, leaving the main controls readable.

### Circuit atmosphere

**Use:** Subtle connective background around technical scenes.

**Observed:** Fine rectilinear paths with clipped diagonal elbows, tiny square nodes and sparse dots sit behind content. They are embossed white-on-white in light openings and barely visible graphite in dark scenes, with broad vignettes hiding their edges.

**Transfer:** Draw an abstract network related to the product's workflow rather than a literal background diagram with labels.

**Build:** Create an SVG wider than the container with 1px paths, straight horizontal and vertical runs and short 45-degree elbows. Add 4–12px square nodes and a few circles. Use #d9d9de at low alpha on light canvas or #2f3037 on dark; mask edges with radial transparency and keep the center behind the headline sparse.

### Cut-shoulder divider

**Use:** Signature transition between light and dark chapters.

**Observed:** The light panel meets the dark canvas with short diagonal shoulders near both ends of the working width; its middle is flat. The transition occupies a 48px strip.

**Transfer:** Preserve the chamfered, engineered silhouette at a theme boundary.

**Build:** Use a 48px-high full-width SVG filled with the incoming canvas color. Draw a flat horizontal center, 45-degree short ramps close to each container edge and short flat outer shoulders. Reverse vertically for the opposite theme change; round only the joins very slightly.

### Monumental emblem

**Only for:** company storytelling

**Use:** Lead image for mission-led organization pages.

**Observed:** A roughly 410px dimensional charcoal emblem floats above a centered white mission statement, backed by a very dark circuit field. Its upper-left rim catches a silver highlight while the lower mass almost merges with the page.

**Transfer:** Use the new organization's own abstract symbol or a neutral geometric sculpture, lit like satin metal rather than chrome.

**Build:** Extrude a simple ring segment, disc or proprietary symbol using offset SVG silhouettes. Shade the face from pale gray at the upper-left rim into #212126 and #131316; add a soft black lower-right shadow and broad low-opacity white spotlight behind it.

### Bright comparison theater

**Only for:** technical comparison promotions

**Use:** A memorable proof or comparison invitation on dark pages.

**Observed:** A pale gradient slab holds a dark input-like box at its upper edge, tilted square app tiles around the sides, and a centered black headline with a small violet action. Colored tiles are richer than the surrounding page but remain isolated objects.

**Transfer:** Replace the input and tiles with the new product's meaningful tools or result objects; keep the light slab and physical staging.

**Build:** Use Bright campaign panel. Center a dark 480px-wide rounded console overlapping its upper edge. Place four roughly 70–78px rounded square tiles around the text with small alternating rotations, narrow highlights and color-matched soft shadows. Keep the middle free for copy.

### People and peer marks

**Only for:** company and testimonial proof

**Use:** Human attribution without becoming a photographic brand.

**Observed:** Small square portraits and monochrome supporter marks sit within rigorous grids. Company portraits are largely desaturated, while small customer avatars can retain natural color. There is no full-bleed lifestyle photography.

**Transfer:** Use real portraits sparingly with name and role; keep images small enough that typography and dimensional product scenes remain dominant.

### Icons

**Observed:** Most functional icons are 16–20px SVGs with round caps and 1.2–1.5px strokes. Text-action arrows are 10px with an 8px leading gap. Dark-table checkmarks use small cyan highlights; ecosystem symbols are thin monochrome outlines rather than colorful badges.

**Transfer:** Choose a consistent rounded-stroke set for controls and use simple filled marks only where the real tool identity requires it.

## Section recipes

How recurring sections are built.

### First screen: Tabbed product opening

**Observed:** A thin dark announcement strip tops a floating navigation bar. On a white canvas, the bold two-line display fills about half of the 1200px working width at left, with a one-line hero-support sentence 16px below it. A Glass copy action anchors the right edge at the level of the support line. The introduction starts after 164px of section-top space. After a 56px gap, Product stage tabs span the full working width above a 741px-high stage including its tab bar. Back-to-front layers are white canvas, faint stage edge, veiled contextual interfaces, a crisp centered working interface and tiny control details. Within the first 900px the headline, support, capsule, tabs and upper working interface are visible; the stage continues below the fold, with customer proof below it.

**Transfer:** Use a two-line outcome promise and show the first useful interaction for the new product. Without finished media, construct the Layered interface stage from credible HTML controls. Product-detail pages instead open with centered 64px type, a pale circuit field and a capsule, followed by a compact assurance strip. Pricing opens dark with a centered heading and plan grid; technical campaigns use centered type with inline tool symbols; organization stories put the Monumental emblem above the mission.

**Avoid:** Do not substitute a centered generic hero with two oversized buttons, put the product entirely below the first screen, or make the demonstration a full-bleed image without the scenario bar.

**Text style:** `display` — suisse 700 · 56px/64px · tracking -0.035em

### Colored chapter introduction

**Observed:** A label-action eyebrow introduces a section-heading after 16px, then a body paragraph after another 16px and a small Arrow text link. Centered introductions constrain the headline to 672px; split chapters use 384–448px copy widths. Main chapters have 128px upper spacing.

**Transfer:** Name the category in the label and the practical outcome in the headline; choose centered alignment for a gallery and left alignment for a product split.

**Text style:** `section-heading` — suisse 600 · 32px/1.25 · tracking -0.015em

### Sculptural capability gallery

**Observed:** Dark gallery and Capability card combine three columns, 8px seams and a 64px gap below the introduction. Tall and short panels interlock; a final wide object can span two columns. The light variant keeps the same 16px card corners but white panels and brighter interfaces.

**Transfer:** Group related outcomes into objects of different proportions, not identical icon-and-copy cards. Retain the low-contrast dimensional material.

### Paired ecosystem chapters

**Observed:** Two centered chapter introductions share a 64px column gap. Each has a separate grid of Outlined logo cell components below it, with generous dark space around the marks and a Cut-shoulder divider into the next theme.

**Transfer:** Use this arrangement to pair complementary kinds of compatibility or evidence without adding a third explanatory column.

### Proof-led close

**Observed:** A 384px column holds a section-heading, support, compact action, fading dotted divider and attributed quotes. Beside it, two vertical streams of Testimonial card sit in a 584px-high window, masked to transparency at the top and bottom. The light version leads into the pale Footer directory; product-detail pages carry the same close on charcoal.

**Transfer:** Close with believable peer outcomes and an immediate low-friction next step. Preserve the mixture of editorial quotes and card streams rather than using a giant final slogan.

### Interactive product explanation

**Only for:** product-detail pages

**Observed:** A 400px explanation column contains a compact-heading, paragraph and vertically divided technical component tabs. A much larger pale product UI sits to the right. Another chapter uses a shallow arc of 48px round provider buttons, with one expanded text button at the center and four concise benefit columns below.

**Transfer:** Use a small set of named workflows and let the right-hand product panel carry the detailed explanation; the arc can show real connected tools or input sources.

**Text style:** `compact-heading` — suisse 600 · 32px/1.12 · tracking -0.015em

### Quantified reassurance

**Only for:** product-detail pages

**Observed:** A claim such as a percentage stays inside the same 32px compact-heading recipe as neighboring outcome headings. Supporting benefits remain 13px copy in small columns; the number is not made into a giant isolated dashboard statistic.

**Transfer:** Use only substantiated metrics and integrate them into a plain outcome sentence.

**Text style:** `compact-heading` — suisse 600 · 32px/1.12 · tracking -0.015em

### Plan shells and comparison

**Only for:** pricing pages

**Observed:** Four 288px plan shells with 16px gaps have 12px corners and pale 12% outlines; each contains an 8px-corner upper summary inset by 4px. One plan catches a cyan top glow. Below add-on rows and partner proof, a detailed table uses a 372px label column and three 276px value columns, subtle dotted rules and small cyan checkmarks. Compact plan headings and actions remain visible during the long comparison.

**Transfer:** Keep the high-level choice concise, then make detailed limits inspectable in a separate matrix; do not give every cell its own card.

### People-backed organization story

**Only for:** company storytelling

**Observed:** The Monumental emblem leads a centered mission. A four-column supporter row begins with a 1px cyan top rule, then a 608px-wide feature-quote occupies a full-width ruled band. A translucent dark 12px-corner people panel uses a four-column portrait grid and a lower fade.

**Transfer:** Substitute genuine trust sources and a concise human perspective; keep supporter information compact rather than turning the page into a press-logo collage.

### Bounded conversion and objections

**Only for:** pricing and technical campaign pages

**Observed:** Pricing uses the Luminous conversion panel before a two-column FAQ disclosure region. The technical campaign substitutes Bright campaign panel, then FAQ rows. Both finish with generous dark space and the Footer directory. Organization pages instead split their final action and recruiting invitation with a fine vertical rule.

**Transfer:** Choose a closing treatment matching the page purpose; keep its special surface bounded and finish with the same compact directory.

## Page flow

**Storyline:** Promise → tangible product experience → capability chapters → compatibility or quantified proof → practical next step and peer reassurance → compact directory; adapt the sequence to the page's decision.

### Broad product landing page

1. **Promise** — Asymmetric bold opening with capsule action and tabbed product stage.
2. **Social proof** — Compact customer-mark strip.
3. **Capability chapters** — Dark sculptural bento, then light capability and split-interface chapters.
4. **Compatibility proof** — Paired centered introductions over outlined mark grids.
5. **Closing reassurance** — Proof-led close with editorial quotes and masked testimonial streams.
6. **Directory** — Pale five-column footer with copyright and social row.

**Transfer:** Move from a usable first experience to supporting breadth, then reassure through peers rather than repeating the opening promise.

### Focused product-detail page

1. **Promise** — Centered pale circuit opening and capsule action.
2. **Risk reduction** — Four small assurance columns.
3. **Product demonstration** — Technical tabs beside a realistic interface, then curved provider buttons and outcome comparisons.
4. **Operational proof** — Dashboard split with a faint cyan-violet halo.
5. **Closing reassurance** — Dark security-style bento continues into dark peer quotes and testimonial streams.
6. **Directory** — Dark footer after a broad vertical gap.

**Transfer:** Explain one product deeply through working UI and practical objections; preserve the dark ending variant.

### Pricing decision page

1. **Choice** — Dark centered promise and four plan shells.
2. **Expansion** — Ruled add-on rows with included and enhanced variants.
3. **Trust** — Bounded partner-support card and customer marks.
4. **Detailed comparison** — Long matrix with repeated compact plan header and dotted rules.
5. **Closing call** — Bounded cyan-to-violet conversion panel.
6. **Objection handling** — Left heading with right-side FAQ disclosures.
7. **Directory** — Dark shared footer.

**Transfer:** Separate plan selection from detailed verification and keep a clear action available during long comparison.

### Organization and mission page

1. **Mission** — Monumental satin-dark emblem above centered bold statement and concise supporting mission.
2. **Institutional proof** — Ruled supporter grid, prominent quote and monochrome mark strip.
3. **Human proof** — Desaturated portrait grid in a translucent graphite panel.
4. **Closing invitation** — Split product action and career-style invitation with restrained buttons.
5. **Directory** — Dark shared footer.

**Transfer:** Use one strong symbolic object, then demonstrate credible human and institutional backing.

### Technical adoption campaign

1. **Promise** — Centered dark headline with overlapping tool symbols embedded between words and a capsule action.
2. **Routes to adoption** — Three-column guide-card grid with 8px seams.
3. **Implementation explanation** — Compact heading beside four numbered practical steps.
4. **Quantified proof** — Filterable comparison matrix with restrained cyan percentage cells and methodology note.
5. **Closing call** — Bright comparison theater with dark input object and tilted tool tiles.
6. **Objection handling** — Sparse FAQ disclosures.
7. **Directory** — Dark shared footer.

**Transfer:** Keep campaign-specific tool imagery and data local; use practical setup routes and measured outcomes for a different technical product.

## Writing

Confident, plainspoken developer marketing with a small amount of conversational relief. Benefits are concrete and implementation-aware, balancing ease of adoption with technical specificity.

**Do not copy:** Do not reuse the brand name, logos, product artwork, customer identities, quotes, funding figures, benchmark results, conversion statistics, security claims, prices or free-tier limits. Replace them with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader as you and your. The product refers to itself by name for concrete capabilities; we appears mainly in organization storytelling.
- **Rhythm:** Short benefit-led headings followed by one or two practical sentences. Longer explanations belong in card captions and comparisons; actions remain compact verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Broad completeness or speed claim attached to a concrete job. | 5–10 words | “Everything you need for authentication”<br>“The easiest way to build user authentication” |
| Supporting line | Clarify the scope in direct product language rather than an abstract mission. | 10–22 words | “More than APIs. The complete user layer for modern apps.”<br>“Point your agent at [Brand]. It does the rest.” |
| Chapter headline | Outcome plus a relieved frustration, or an explicit tool relationship. | 5–9 words | “Subscription billing, without the headache”<br>“Build with SDKs for modern frameworks” |
| Card description | Name the concrete operation, then explain what work is removed. | 15–30 words | “Give every user secure, production-ready API keys without building any of the underlying boilerplate code or UI.” |
| Action | Start, explore, view or apply plus the destination or next task. | 2–5 words | “Start building for free”<br>“View the benchmark”<br>“Apply today” |
| Closing reassurance | A direct invitation followed by a low-friction qualifier. | 5–8 words | “Start now, no strings attached.” |

**Words and phrasing to use:** build; ship; out of the box; components; without the headache; in minutes; your application; primitives; integrate; manage

**Avoid:** revolutionary; unlock limitless potential; next-generation synergy; magical transformation; excessive exclamation marks

**Rules:**

- Pair an ease claim with a concrete implementation mechanism.
- Use actual feature names in small labels and human outcomes in larger headlines.
- Reserve technical acronyms for places where they shorten a familiar concept; explain the consequence in the adjacent sentence.
- Keep numeric claims in useful context and state the qualification close by.
- Let occasional conversational phrasing soften the engineering detail without turning the page into jokes.

## Do's and Don'ts

### Do

- Keep the default opening at 56px/64px and -0.035em tracking, with later section leads at 32px/40px.
- Use 8px gallery seams against 128px chapter spacing so the page feels both spacious and richly engineered.
- Maintain the 1264px outer wrapper with 32px side padding and 1200px working area.
- Keep ordinary violet buttons at 30px high and 6px corners; preserve the special 44px glass capsule for the opening.
- Use 13px card titles and caption copy rather than inflating every card into a headline.
- Give the gallery objects a narrow pale highlight and a deep graphite body.
- Carry the cut-shoulder transition into the light/dark boundary.
- End with 13px directory links, muted labels and a restrained social row.

### Don't

- Do not make violet the background of every section; most of the visual area remains white, pale gray or charcoal.
- Do not replace the 8px seams with widely separated floating feature cards.
- Do not make ecosystem cells rounded like capability cards; their 1px shared borders are rectilinear.
- Do not apply uppercase mono styling to the core sentence-case 13px labels.
- Do not use glossy rainbow chrome for dark miniatures; their tonal range stays close to #212126.
- Do not replace small attributed portraits with full-width lifestyle photography.
- Do not put the 44px capsule shape on every action; ordinary controls retain 6px corners.
- Do not turn a metric sentence into an oversized isolated numeral; detail-page proof stays within the 32px heading hierarchy.

## Motion and responsive

### Motion

**Observed:**

- Utility buttons declare color, fill, edge and shadow transitions of 0.15s cubic-bezier(0.33, 1, 0.68, 1).
- The floating navigation declares a 0.45s cubic-bezier(0.33, 1, 0.68, 1) theme/surface transition.
- Text actions and filled conversion controls declare 0.3s cubic-bezier(0.4, 0.36, 0, 1) transitions; their small arrow has a separate translating/fading treatment.
- Four decorative objects declare float 4s ease-in-out infinite. The testimonial streams use translated vertical lists inside gradient masks.

**Transfer:**

- Keep interface transitions small and material-focused: edge, fill, shadow and tiny arrow changes rather than whole-section movement.
- Retain the fading vertical proof-stream effect; provide a static readable arrangement under reduced motion.

**Unknown:**

- Exact ticker speed, scroll choreography, object floating amplitude and timing of automatic scenario changes are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px among more specialized control breakpoints.
- Capability and guide grids declare one column at the smallest layout, two at intermediate widths and three at wide widths.
- Footer directory declares two columns, then three, then five; the mark and directory stack before the desktop split.
- The main opening declares centered text at intermediate widths and left alignment in the wide split layout.

**Transfer:**

- Stack the opening copy, capsule and product stage on narrow screens while keeping one main product interaction legible.
- Collapse paired chapters and text/product splits vertically; let comparisons scroll within their own area rather than compressing data cells.
- Keep the diagonal transition shoulders short relative to the content edge, preserving the engineered silhouette.

**Unknown:**

- Exact mobile artwork rearrangement, menu behavior and every breakpoint-specific measurement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
