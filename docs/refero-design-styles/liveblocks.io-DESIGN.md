# Liveblocks — graphite under soft light

## Overview

A black-on-black technical style with bright grotesk headlines and small, matter-of-fact explanations. Charcoal compartments, restrained silver light and occasional pastel interface scenes make complex software feel tangible rather than abstract. The mood suits developer platforms and sophisticated digital tools: spacious at the page level, compact and purposeful inside demonstrations.

### Essentials

- Headlines behave like a clear promise above a dark stage: Suisse 60px/1.1, weight 500, -0.02em tracking, centered in a 672px headline column with a 20px supporting line.
- Black is the atmosphere, not just a section color: #000000 covers nearly the whole marketing canvas; #918d8d explanations and #ffffff emphasis create the hierarchy. Chromatic color stays in small signals, code and bounded media, not broad alternating bands.
- The opening joins readable type to a tangible low-light scene: a compact announcement capsule, two-line promise, paired 44px actions, then a broad product-related object fading into black. Without rich media, construct a dimensional interface or connection diagram rather than omit the stage.
- Conversions are small white rectangles, not bright pills: 44px height, 8px corners, 16px side padding, paired with an unfilled white action; the navigation uses a 36px/6px version.
- Capabilities live in shared graphite compartments: 791px-wide two-column assemblies, 1px #272626 edges, 28px inner padding and only the outer 8px corners rounded. A modest 20px chapter heading precedes them rather than another giant headline.
- Soft material light is a signature device: use graphite texture or a diagonal silver sheen on a demonstration and a huge cropped luminous horizon for a major call. The horizon surrounds a 52px/1.1 balanced statement with 196px vertical breathing room; its neutral version is the default.
- A bright interface strip interrupts the darkness: square 396px product scenes at 16px gaps, with pale blue, cream and graphite backings, clipped at the viewport edges. Use a small set of credible workflow scenes if the product has no finished interface.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-foreground` | text, action, surface | Headlines, inline emphasis, primary actions and light demonstration interiors. |
| Pale blue stage | `#f9fbfd` | `--color-scene-cool` | surface | Bounded light interface showcase backing. |
| Cream stage | `#f6ece2` | `--color-scene-warm` | surface | Warm interface showcase backing. |
| Soft silver | `#b7b4b4` | `--color-subtle` | text, action | Hero support, compact badges and white-button hover fill. |
| Warm gray | `#918d8d` | `--color-secondary` | text | Explanations, footer links and secondary quotation text. |
| Graphite text | `#635f5f` | `--color-recessive` | text | Oversized reliability number and lowest-priority instructional text. |
| Translucent white edge | `#282828` | `--color-divider` | border, surface | Visible result of rgba(253,252,252,0.16) on black; fine dividers, announcement border and subdued controls. |
| Opaque graphite edge | `#272626` | `--color-edge` | border | The 1px compartment outline and shared bento separators. |
| Blue graphite stage | `#21222b` | `--color-scene-dark` | surface | Dark interface showcase backing. |
| Subtle panel edge | `#1e1e1e` | `--color-subtle-edge` | border | Visible result of rgba(253,252,252,0.12) on black; broad demonstration panels and quotation rules. |
| Warm near-black | `#100f0f` | `--color-raised` | surface | Raised demonstration panels and the emphasized commercial tier. |
| Absolute black | `#000000` | `--color-canvas` | background, text | Continuous marketing canvas and text on white actions. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational mint | `#6cefce` | `--color-status` | text, accent | Small operational status line and its 6px dot; never a primary action fill. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical demonstrations | Syntax lavender | `#9f8dfc` | `--color-code-keyword` | text | Keywords in marketing code samples. |
| technical demonstrations | Syntax seafoam | `#70e1c8` | `--color-code-string` | text | Strings in marketing code samples. |

## Typography

- **suisse** — All marketing headings, prose, labels and actions. Compact neo-grotesk with an even texture; medium rather than bold headlines. If unavailable, use **Inter**. Use 400 and 500; retain tight display tracking and balanced line breaks. Font stack: "suisse", "Inter", -apple-system, system-ui, "Segoe UI", Roboto, "Helvetica Neue", sans-serif.
- **JetBrains Mono** — Technical code and widely tracked chapter labels. Crisp monospace with distinct punctuation; labels feel like instrument markings. Font stack: "JetBrains Mono", "Roboto Mono", Menlo, Monaco, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | suisse | 500 | 60px | 1.1 | -0.02em | Default centered landing promise. |
| stat | suisse | 500 | 60px | 1 | normal | Low-contrast oversized reliability figure within a shallow full-width cell. |
| display-section | suisse | 500 | 52px | 1.1 | -0.02em | Broad editorial promises, showcase introductions and closing call. |
| heading-card-lg | suisse | 500 | 32px | 1.2 | -0.01em | Lead statement inside a wide compartment and prominent plan price. |
| quote | suisse | 400 | 24px | 1.375 | normal | Customer quotation within a shared-edge proof assembly. |
| quote-emphasis | suisse | 500 | 24px | 1.375 | normal | White non-italic emphasis within the quotation. |
| chapter-heading | suisse | 500 | 20px | 1.375 | 0.004em | Narrow, left-aligned capability chapter heading and bright inline emphasis. |
| lead | suisse | 400 | 20px | 1.375 | 0.004em | Hero support and chapter explanation. |
| card-title | suisse | 500 | 16px | 1.375 | 0.004em | Compact compartment titles. |
| card-body | suisse | 400 | 16px | 1.375 | 0.004em | Capability summaries and quiet proof-strip captions. |
| action | suisse | 500 | 16px | 1.5 | normal | 44px buttons and accordion questions. |
| navigation | suisse | 500 | 14px | 20px | normal | Header navigation, compact buttons and announcement text. |
| footer-link | suisse | 400 | 14px | 1 | normal | Dense footer directory links. |
| detail | suisse | 400 | 14px | 20px | normal | Small status and attribution lines. |
| eyebrow | JetBrains Mono | 400 | 14px | 1 | 0.125em, uppercase | Widely spaced small chapter markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company-story pages | story-display | suisse | 500 | 64px | 1.1 | -0.02em | Long left-aligned editorial opening statement. |
| pricing and company-story pages | secondary-heading | suisse | 500 | 30px | 1.2 | normal | FAQ title or stacked company fact numeral. |
| feature-detail pages | quote-band | suisse | 400 | 30px | 1.4 | -0.015em | Standalone centered testimonial between fine horizontal rules. |
| feature-detail pages | quote-band-emphasis | suisse | 500 | 30px | 1.4 | -0.015em | White emphasized clause within a standalone testimonial. |
| company-story pages | photo-caption | suisse | 400 | 16px | 1.5 | normal | Understated caption directly below documentary photography. |
| technical demonstrations | code | JetBrains Mono | 400 | 14px | 20px | normal | Readable implementation samples. |

**Notes:**

- Keep the medium headline weight at 500. Display tracking tightens to -0.02em, card statements use -0.01em, while prose has barely positive 0.004em tracking.
- The default chapter hierarchy is deliberately modest: a 20px medium heading above a 20px regular explanation, not a display heading above every block.
- Use white medium-weight phrases inside gray paragraphs and quotations. Quotation emphasis is upright, not decorative italic.

## Layout

**Density:** Airy between narrative blocks and tightly compartmentalized within product demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gap and photograph-to-caption gap. |
| 12px | Paired desktop action gap. |
| 16px | Showcase strip gaps and headline-to-support separation. |
| 20px | Narrow chapter heading-to-prose gap. |
| 28px | Compartment padding and structural grid gutter. |
| 48px | Generous internal group spacing and photo separation. |
| 64px | Vertical padding inside broad demonstration panels. |
| 96px | Chapter copy-to-bento separation. |
| 128px | Editorial block breathing room. |
| 196px | Large section breathing room and closing-call vertical padding. |
| 280px | Separation around long-form capability chapters. |

### Containers and grids

- **outer-container**: max width 1280px · side padding 40px. Centered desktop frame including side padding, leaving 1200px of usable content at a 1440px viewport.
- **structural-grid**: max width 1200px · 12 columns · gap 28px. Align wide imagery, narrow text and central eight-column assemblies.
- **chapter-copy**: max width 576px. Centered column with left-aligned heading and supporting prose.
- **hero-title**: max width 672px. Centered, balanced two-line default promise. Broader feature promises may span 896px.
- **bento-assembly**: max width 791px · 2 columns · gap 1px. Central eight-column compartment construction; wide lead cells span both columns.
- **showcase-strip**: 4 columns · gap 16px. 396px square scenes in a horizontally overflowing rail, revealing partial neighbors.
- **directory**: max width 1200px · 4 columns · gap 28px. Three stacked link-group columns with a right-aligned brand, status and trust column.
- **plans** (only for pricing pages): max width 1200px · 4 columns · gap 1px. Equal commercial tiers in a shared-edge assembly.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-actions | 8px |
|  | small-actions | 6px |
|  | assembly-shell | 8px |
|  | announcement | 9999px (pill) |
| feature-detail pages | demonstration-panel | 24px |
| company-story pages | portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| compartment-ring | `0px 0px 0px 1px #272626` | A structural hairline rather than elevation. |
| horizon-light | `0px 0px 86.4px 0px rgba(255,255,255,0.6) inset` | Soft rim inside the giant circular closing backdrop. |

### Surfaces

#### Black canvas · level 0

**Use:** Unbroken marketing atmosphere.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Sections mostly remain on the same black field instead of alternating fills.

**Transfer:** Let typography, spacing and framed media distinguish chapters.

#### Graphite assembly · level 1

**Use:** Shared shell for capability and proof cells.

**CSS:** `background: #000000; border-radius: 8px; box-shadow: 0px 0px 0px 1px #272626; overflow: hidden`

**Observed:** Internal cells share straight edges; only the perimeter is rounded.

**Transfer:** Use a single clipped shell around a 1px-gap grid.

#### Brushed graphite · level 1

**Use:** Wide lead compartment behind a large statement and related capability links.

**CSS:** `background-color: #000000; border: 1px solid #272626`

**Observed:** An extremely dark cloudy graphite texture catches light at the right and lower edges without competing with text.

**Transfer:** Create a mostly black material with soft gray ridges and fine monochrome grain rather than a colorful gradient.

#### Closing horizon · level 0

**Use:** Atmospheric rim behind a major conversion statement.

**CSS:** `background-color: #000000; overflow: hidden; position: relative`

**Observed:** A 5760px circular dark field is cropped into a shallow horizon; a soft neutral rim is the default. A warm copper-to-red rim belongs to warm feature campaigns.

**Transfer:** Use the luminous horizon graphic recipe, then keep all text and actions sharp above it.

#### Light showcase backing · level 1

**Use:** Bounded scene in the interface rail.

**CSS:** `background: #f9fbfd; border-radius: 8px; padding: 28px; overflow: hidden`

**Observed:** Cream and blue-graphite variants alternate with the light stage, not with the page canvas.

**Transfer:** Choose the backing per interface contrast while retaining a coherent strip.

#### Silver demonstration panel · level 1

**Only for:** feature-detail pages

**Use:** Broad backing for bright interface demonstrations.

**CSS:** `background-color: #100f0f; background-image: linear-gradient(45deg, rgba(0,0,0,0) 25%, rgba(255,255,255,0.075) 50%, rgba(0,0,0,0) 75%, rgba(0,0,0,0) 100%); border: 1px solid rgba(253,252,252,0.12); border-radius: 24px; padding: 64px 0px`

**Observed:** The interface is the bright object, while the softly reflective backing remains almost black.

**Transfer:** Keep a generous dark surround around one crisp, readable interface.

## Components

### Fixed navigation

**Use:** Persistent lightweight wayfinding.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 80px; background: #000000`

**Text style:** `navigation` — suisse 500 · 14px/20px

**Observed:** Wordmark at left, short links alongside, sign-in and Compact button at far right. A faint lower rule separates it from scrolled content; navigation items have 8px 12px padding.

**Transfer:** Keep the desktop row visually small against the large opening.

### Primary button

**Use:** Main conversion or documentation action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #000000; border-radius: 8px; padding: 0px 16px; height: 44px`

**Text style:** `action` — suisse 500 · 16px/1.5

**Observed:** Text-sized, not a full-width banner; often paired with Text action.

**States:** Declared: hover background #b7b4b4; focus-visible outline-style none and no visible shadow; active background #ffffff.

**Transfer:** Use one filled action in a pair. Provide an accessible visible focus treatment in a new implementation.

### Compact button

**Use:** Header conversion and compact commercial actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ffffff; color: #000000; border-radius: 6px; padding: 0px 14px; height: 36px`

**Text style:** `navigation` — suisse 500 · 14px/20px

**Observed:** Header uses the white version; secondary commercial actions use translucent white fill and white text.

**States:** Declared: hover background #b7b4b4; focus-visible outline-style none and no visible shadow; active background #ffffff.

### Text action

**Use:** Secondary action alongside a white button.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; color: #ffffff; background: transparent; border-radius: 8px; padding: 0px 16px; height: 44px`

**Text style:** `action` — suisse 500 · 16px/1.5

**Observed:** Trailing arrow signals a destination; a chevron signals a choice such as an install menu.

**States:** Declared: hover not specified; focus-visible outline-style none and no visible shadow; active background rgba(253,252,252,0.2).

### Announcement capsule

**Use:** Compact topical hook above the default promise.

**CSS:** `display: flex; align-items: center; gap: 8px; border: 1px solid rgba(253,252,252,0.16); border-radius: 9999px; padding: 4px 4px 4px 12px; height: 38px; color: #ffffff`

**Text style:** `navigation` — suisse 500 · 14px/20px

**Observed:** Small subdued New badge leads the sentence; a circular arrow cap closes it. One short product phrase has a pale ivory-to-steel-blue text sheen.

**States:** Declared: hover border rgba(253,252,252,0.18); focus-visible outline-style none and no visible shadow.

**Transfer:** Keep this to one short update, not a second navigation bar.

### Capability cell

**Use:** Compact explanation in a Graphite assembly.

**CSS:** `position: relative; display: flex; flex-direction: column; padding: 28px; box-shadow: 0px 0px 0px 1px #272626; overflow: hidden`

**Text style:** `card-title` — suisse 500 · 16px/1.375 · tracking 0.004em

**Observed:** A small monochrome icon, title and gray Card-body description occupy the top-left. Large cells place a dim diagram underneath; shallow cells remain text-led. Cells themselves have square corners.

**Transfer:** Keep explanations short enough to leave room for the illustration.

### Showcase tile

**Use:** Bright product proof in a horizontally clipped rail.

**CSS:** `position: relative; width: 396px; height: 396px; background: #f9fbfd; border-radius: 8px; padding: 28px; overflow: hidden`

**Text style:** `chapter-heading` — suisse 500 · 20px/1.375 · tracking 0.004em

**Observed:** Small title and comparison caption at upper left, tiny identifying mark at upper right, close-up interface below. Other tile backings use cream, white and blue graphite.

**Transfer:** Show a focused interaction, not a tiny entire application.

### Footer link

**Use:** Dense grouped directory.

**CSS:** `display: inline-flex; align-items: center; padding: 8px; gap: 8px; border-radius: 4px; color: #918d8d`

**Text style:** `footer-link` — suisse 400 · 14px/1

**Observed:** White medium group titles precede muted vertical links. Stacked groups align into three columns; a separate fourth column holds brand, mint status, social marks and small trust seals, with copyright near the bottom.

**States:** Declared: hover color #ffffff; focus-visible outline-style none and no visible shadow.

### Plan card

**Only for:** pricing pages

**Use:** Compare commercial choices.

**CSS:** `position: relative; padding: 28px; background: #100f0f; box-shadow: 0px 0px 0px 1px #272626; overflow: hidden`

**Text style:** `navigation` — suisse 500 · 14px/20px

**Observed:** Tier label, muted audience description, 32px price, billing detail, included features and bottom-aligned action. Only the emphasized tier uses the raised fill and white conversion button; peers stay black with subdued actions.

**Transfer:** Emphasize one tier with near-black fill, not a saturated brand panel.

### FAQ row

**Only for:** pricing pages

**Use:** Resolve purchasing objections after the comparison.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 28px; gap: 56px; color: #ffffff; text-align: left`

**Text style:** `action` — suisse 500 · 16px/1.5

**Observed:** Question at left, 20px gray chevron at right; each row sits above a 1px translucent-white rule. The list occupies two thirds of a shared shell while its title occupies the left third.

**Transfer:** End the list with a plain question input and send control rather than another promotional card.

## Imagery and graphics

### Low-light product stage

**Use:** Main opening scene behind and beneath crisp hero content.

**Observed:** An immersive black field contains a blurred, low-angle interface-like object and tiny yellow collaboration markers. The scene fills the lower half of the first screen and fades into surrounding darkness; readable type stays in front.

**Transfer:** Create a tangible workflow object in near-black, with one tiny functional color signal. A minimum version is a dark perspective interface plane with soft side light and a sharp marker; do not make blur the subject.

**Build:** Place a wide dark interface plane below the actions, rotate it away from the viewer with perspective, add subdued gray content lines and 1px edges. Add a broad radial white light at low alpha behind it, fade all four edges to black and keep the text overlay outside the transformed plane.

### Graphite material and luminous symbols

**Use:** Lead compartments, small feature emblems and supporting diagrams.

**Observed:** Dark cloud-like brushed material, polished metallic icons and low-contrast dotted globes or storage diagrams. White edges catch light but most of the object remains black.

**Transfer:** Make the concept tactile without requiring a complex illustration. A beveled monochrome SVG plus faint graphite texture is the minimum.

**Build:** Layer a black fill, two broad blurred gray ellipses at 0.04–0.08 alpha, and low-opacity monochrome SVG turbulence. Give a compact icon a gray gradient face, narrow white highlight and dark lower edge; keep it about 32px, never a colorful sticker.

### Luminous horizon

**Use:** Signature atmospheric conversion device.

**Observed:** The upper rim of a huge dark sphere arcs across the page, then recedes around the centered call. Neutral silver is the standard; a feature-detail treatment uses a copper edge with red light beneath it.

**Transfer:** Use a horizon to make an important promise feel expansive, even without a product illustration.

**Build:** Center a 5760px circular layer in an overflow-hidden full-width section. Keep its inner 90% black, increase neutral light through the outer 10%, and add an inset white glow of 86.4px at 0.6 alpha. Crop it so only a shallow arc and spill of light remain visible around the call. Match the soft glow; exact stops are not essential.

### Focused interface proof

**Use:** Rail tiles, paired bright demos, code and wide dashboard proof.

**Observed:** Readable close-ups of comments, editors, inboxes and charts. Light interfaces sit on pale or charcoal backing; the wide dashboard uses a slim browser frame and dark charcoal interior. Code remains sharp on black, with small lavender and mint syntax accents.

**Transfer:** Use believable product content and a single focal interaction. For an unfinished product, build a small working HTML panel rather than a generic decorative mockup.

### Technical graph paper

**Only for:** technical demonstrations

**Use:** Backing for a centered code implementation scene.

**Observed:** A thin gray square grid spans the width behind a black code panel; the grid recedes into black toward its edges.

**Transfer:** Use for an implementation proof, not behind ordinary copy.

**Build:** Layer two repeating linear gradients, horizontal and vertical, with 1px rgba(253,252,252,0.16) rules at 28px intervals. Fade the field with a radial mask and place a black code slab above it.

### Connected system diagram

**Only for:** infrastructure landing pages

**Use:** Large explanatory object under the opening promise.

**Observed:** A roughly square smoked central server card with five small inset tiles connects to six avatars via hairline white curves. Small pastel agent discs and real faces are the main color; labels remain tiny and neutral.

**Transfer:** Show inputs and outputs around one central product object; use generic role symbols if people are not relevant.

**Build:** Use a central 394px graphite panel with 8px corners, a faint upper-right highlight, and inset 110px tiles. Draw symmetrical SVG Bezier connectors to three circular nodes per side with small white junction dots. Keep external labels outside the curves.

### Documentary people photography

**Only for:** company-story pages

**Use:** Editorial opening, full-bleed photo rail and small team portraits.

**Observed:** Natural-color group photos and candid travel moments, wide landscape framing, no graphic duotone. A 1200px-wide opening photograph has an 8px caption gap; the rail overflows both sides with 16px spacing. Team faces are circular inside shared-edge black cells.

**Transfer:** Use authentic group context and candid interaction, preserving natural light and ordinary clothing rather than staged studio portraits.

### Icons

**Observed:** Marketing marks are mostly monochrome filled SVGs at 16px, 20px and 32px, often silver on black. Several product emblems have softly beveled metallic light. Fine interface outlines use 1.2–1.5px rounded strokes.

**Transfer:** Choose compact, legible monochrome symbols for marketing; reserve colored avatars and fine outline tool icons for the demonstration itself.

## Section recipes

How recurring sections are built.

### First screen: Dark product stage opening

**Observed:** A fixed 80px black navigation sits over a centered stage. At 1440px, a 38px Announcement capsule begins 48px below navigation; 24px separates it from a two-line 60px promise in a 672px column. A small yellow collaborative caret interrupts one word. Lead support follows in two balanced lines, then Primary button and Text action sit side by side at 12px gap. Layers are black canvas, dim broad product scene, then sharp white type and controls. Within the first 900px the announcement, whole headline, support, both actions and the large low-angle scene are visible; the trust strip and bright showcase rail fall below.

**Transfer:** Keep the default composition for a new landing page, substituting a product-related dark object or constructed interface plane. Feature-detail openings may add a small icon/title and a wide connected diagram or warm interface halo; pricing opens with a simple centered title, support and plans; company stories open left-aligned with an editorial statement and documentary photograph.

**Avoid:** Do not replace the dark stage with a flat full-color hero, a right-side stock illustration or an oversized headline that pushes the product object entirely below the fold.

**Text style:** `display` — suisse 500 · 60px/1.1 · tracking -0.02em

### Bright proof interruption

**Observed:** A balanced 52px introduction with gray setup and brighter conclusion precedes the Showcase tile strip by about 96px. The rail ignores the narrow text column and clips partial neighbors at the viewport edges.

**Transfer:** Use a few concrete end-user outcomes, each illustrated by one close interaction, to interrupt long black chapters.

**Text style:** `display-section` — suisse 500 · 52px/1.1 · tracking -0.02em

### Narrow chapter to shared assembly

**Observed:** A 576px centered but left-aligned text column contains Chapter-heading, a 20px gap, then Lead prose with selected white phrases. A Graphite assembly begins 96px below. Two-column cells combine small icons, brief descriptions and dim diagrams; wide lead compartments use Brushed graphite and a 32px statement beside links.

**Transfer:** Explain one conceptual benefit in the heading pair, then prove it through a small family of features rather than repeating the sentence in cards.

**Text style:** `chapter-heading` — suisse 500 · 20px/1.375 · tracking 0.004em

### Trust assembly

**Observed:** A wide quotation cell puts customer identity at top and the 24px gray/white quote near its lower edge. Small square arrow controls sit at upper right. Shallow Capability cells follow, then a 60px dark-gray reliability statement shares a final cell with compact certification seals. The number has a black fade toward its lower edge.

**Transfer:** Use an attributable quotation, compact operational proof and one real measured figure; retain the dim monumental stat rather than coloring it brightly.

**Text style:** `quote` — suisse 400 · 24px/1.375

### Implementation proof

**Observed:** A narrow chapter and actions precede a two-pane interactive cursor scene with small colored labels and code tabs underneath. A feature-detail alternative uses Technical graph paper behind a centered black code slab.

**Transfer:** Show the shortest credible implementation or workflow that supports the promise; keep the visible result connected to the code.

**Text style:** `code` — JetBrains Mono 400 · 14px/20px

### Horizon conversion and directory

**Observed:** Closing horizon surrounds a centered 52px balanced statement in a 672px column with 196px padding above and below. Paired Primary button and Text action follow at 24px. The full directory starts immediately after the 632px call: three tall link columns and a right brand/status column, with social icons, small trust seals and copyright anchored low. All five page types share that directory.

**Transfer:** Use the horizon as a major conversion beat on marketing pages, with a concise future-facing outcome. Keep commercial and editorial endings scoped to their direct-to-directory variant.

**Text style:** `display-section` — suisse 500 · 52px/1.1 · tracking -0.02em

### Demonstration chapter

**Only for:** feature-detail pages

**Observed:** Mono Eyebrow, centered 52px heading, 20px support and a compact action introduce a large Silver demonstration panel. A bright interface appears inside; a second, lower split panel pairs prose with code. Related notification scenes use two equal dark rounded panels and small floating monospace event capsules.

**Transfer:** Demonstrate adaptability through a real interface before explaining advanced customization.

**Text style:** `display-section` — suisse 500 · 52px/1.1 · tracking -0.02em

### Commercial comparison and objections

**Only for:** pricing pages

**Observed:** Centered 60px title with 24px supporting prose, billing toggle and four shared-edge Plan cards. Below a trust strip, a long ruled comparison matrix keeps feature labels in the wider left column and four aligned value columns. The ending is a split FAQ shell with a question input, then the full Footer link directory; there is no luminous conversion call.

**Transfer:** Use an exhaustive table only when buyers genuinely compare many capabilities. Maintain the dark understated tier emphasis and direct transition from objection handling to footer.

**Text style:** `display` — suisse 500 · 60px/1.1 · tracking -0.02em

### Editorial story and people

**Only for:** company-story pages

**Observed:** A 64px left-aligned statement spans roughly eight structural columns, above a wide natural photo and quiet caption. A sticky left fact rail with 30px numerals and a fine right divider sits beside longer 20px white prose. An overflowing photo rail leads to a shared-edge values assembly and four-column circular-portrait grid. Contact and recruiting actions live above that final grid; it ends directly at the full directory, without a luminous call.

**Transfer:** Use an editorial statement, authentic documentary scenes and a concise factual sidebar to explain an organization's character; adapt the last grid to people or relevant contributors.

**Text style:** `story-display` — suisse 500 · 64px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Promise → concrete product proof → capability chapters → implementation confidence → trust → an appropriate final action → directory.

### Broad product marketing landing page

1. **Promise** — Centered stage opening and announcement over a dim product object.
2. **Social proof** — Muted trust caption and monochrome logo strip.
3. **Product demonstration** — Bright close-up rail with a large two-tone introduction.
4. **Capability chapters** — Narrow explanations above compartmentalized dark diagrams and benefit grids.
5. **Implementation confidence** — Paired result demo and code tabs.
6. **Trust** — Quote-led assembly, operational features and recessive oversized stat.
7. **Closing call** — Neutral luminous horizon and two actions, then the complete directory.

**Transfer:** Move from outcome to mechanism to confidence; vary chapter depth without losing the stage, compartments and luminous signature.

### Commercial comparison page

1. **Pricing** — Simple title, lead, billing selector and four equal tiers with one softly raised option.
2. **Social proof** — Small gray logo strip.
3. **Comparison** — Extended shared-edge matrix with grouped capability headers and aligned tier columns.
4. **Objection handling** — Split title and accordion list ending in a question input.
5. **Ending** — Direct transition to the full directory.

**Transfer:** Keep the visual drama subordinate to practical comparison; do not append a generic conversion section.

### Feature-detail landing page

1. **Promise** — Centered three-line benefit inside floating contextual UI fragments and a warm halo.
2. **Flexibility proof** — Small metadata diagrams paired with code and a broad centered heading.
3. **Customization proof** — Bright interface in a broad dark reflective panel, followed by a split advanced example.
4. **Workflow extension** — Two notification scenes with a floating event capsule rail.
5. **Social proof** — Centered gray/white quote between fine horizontal rules.
6. **Implementation confidence** — Code on graph-paper backing, then three example cards.
7. **Breadth** — Small related-capability assembly.
8. **Closing call** — Warm luminous horizon, paired actions and directory.

**Transfer:** Make one feature concrete through use, adaptation and implementation before broadening the story.

### Infrastructure landing page

1. **Promise** — Centered benefit above a connected server-and-avatars diagram.
2. **Mechanism** — Narrow explanatory pair, textured support panel and integration rows.
3. **Trust** — Operational features, a dim giant stat and small seals.
4. **Product proof** — Wide dark dashboard in a slim browser frame.
5. **Breadth** — Shared-edge related-capability cells.
6. **Closing call** — Neutral horizon, paired actions and directory.

**Transfer:** Explain the system with one central object and connectors, then show real operational visibility.

### Company story and recruiting page

1. **Editorial promise** — Large left-aligned statement and full-width documentary group photo.
2. **Origin story** — Sticky factual sidebar beside long white prose.
3. **Human proof** — Large horizontally overflowing candid photographs with quiet captions.
4. **Principles** — Centered introduction and two-by-two shared-edge statements.
5. **People and action** — Centered contact/recruiting pair above circular portraits in a four-column grid.
6. **Ending** — Direct transition from team grid to full directory.

**Transfer:** Change the source of credibility from product diagrams to people and facts while retaining black framing and the same type system.

## Writing

Confident, technically literate and approachable. Benefits are direct, with concrete implementation language underneath rather than elaborate hype.

**Do not copy:** Do not reuse Liveblocks names, logos, customer identities, comparison-brand assets, proprietary illustrations, testimonials, compliance badges or numerical performance and pricing claims. Replace all of them with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader through your product and your users; use imperative verbs in promises and actions. Product descriptions name the product directly; company storytelling uses we and our.
- **Rhythm:** Short declarative headings, followed by one or two explanatory sentences. Technical nouns are balanced with simple verbs; emphasized clauses carry the payoff. Exclamation marks are rare.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the outcome and the working context; avoid a vague category slogan. | 5–14 words | “Realtime sync for collaborative apps”<br>“Build apps where people and agents work on shared data” |
| Chapter heading | A compact benefit statement with a full stop. | 3–9 words | “First‑class developer experience.”<br>“A platform you can trust at scale.” |
| Supporting line | Explain what happens, then state the practical advantage. | 15–35 words | “Keep your application data in sync as people and AI agents work together, with automatic conflict resolution built in.” |
| Primary action | Plain verb and object; state a low-friction starting point when true. | 2–5 words | “Get started for free”<br>“Browse examples”<br>“Read the docs” |
| Card explanation | One capability and one short reassurance. | 8–18 words | “Data is stored and synced across sessions. No backend to manage.” |
| Photo caption | An unforced factual line that names the occasion. | 7–14 words | “Celebrating a successful year in style.” |

**Words and phrasing to use:** build; ship; keep; sync; built-in; your product; your users; a few lines of code; at scale; carefully crafted

**Avoid:** revolutionary ecosystem; unleash limitless possibilities; game-changing as an unsubstantiated author claim; supercharge everything; salesy urgency

**Rules:**

- Pair an end-user benefit with the mechanism that makes it believable.
- Make the important clause visually white instead of turning an entire paragraph into bold promotional copy.
- Keep technical terms where they remove ambiguity, not merely to sound sophisticated.
- Use specific action labels and factual supporting details rather than a repeated Learn more everywhere.

## Do's and Don'ts

### Do

- Use 60px/1.1, weight 500 and -0.02em tracking for the primary centered promise.
- Keep chapter copy to 576px while central shared-edge assemblies widen to 791px.
- Use 28px padding in compartments and 1px edges instead of floating-card shadows.
- Retain a bright interface rail with 396px square tiles and clipped neighboring scenes.
- Pair a white 44px action with an unfilled same-height action at 12px gap.
- Reserve 196px vertical breathing room around the luminous major call.
- Use small silver symbols and a 6px mint status dot to punctuate the black field.
- Keep white medium-weight emphasis inside #918d8d explanatory text.

### Don't

- Do not promote all 20px chapter headings to 52px; the contrast between modest chapters and display moments matters.
- Do not round every internal compartment to 24px; that radius belongs to broad feature-demo backings.
- Do not make the primary action a mint or purple pill; the dominant conversion treatment is white with 8px corners.
- Do not replace the #272626 assembly ring with thick high-contrast outlines.
- Do not turn the 60px reliability figure into a bright colorful KPI; its recessive graphite treatment is distinctive.
- Do not spread cream and pale blue across whole page bands; they belong to bounded product scenes.
- Do not use a generic uniform drop shadow under every black cell; shared hairlines provide structure.
- Do not force the horizon call onto commercial or company-story endings; their final actions already belong in the preceding content.

## Motion and responsive

### Motion

**Observed:**

- Primary and secondary actions declare 0.3s cubic-bezier(0,0,.2,1) transitions on color, opacity, shadow and transforms.
- The announcement text declares a 3.4s mask-flare-loop using cubic-bezier(.33,1,.68,1), both infinite, with a diagonal luminance mask.
- The interface rail uses horizontal transforms and a grab/grabbing cursor.

**Transfer:**

- Keep action movement subordinate to the product stage; use the brief declared transition for button color changes.
- A slow diagonal sheen can enliven the announcement without changing the typography or contrast hierarchy.

**Unknown:**

- The complete opening 3D choreography, scroll-trigger timing and reduced-motion behavior are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 360px, 639px, 640px, 767px, 768px, 1023px, 1024px, 1280px and 1536px.
- Desktop container padding is 40px; declared inner and outer gutter tokens also include 16px. Desktop navigation items switch at the 1024px class boundary.

**Transfer:**

- On narrow layouts retain the dark stage, centered promise and visible primary action; reduce the stage object's width rather than hiding it.
- Collapse shared-edge assemblies to one column while preserving a single rounded perimeter.
- Let the bright showcase rail continue to reveal a partial next tile, and stack the editorial fact rail above the story when a sidebar no longer fits.

**Unknown:**

- Mobile type sizes, exact stacking order, menu behavior and stage scaling have not been visually established; the narrow-screen transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
