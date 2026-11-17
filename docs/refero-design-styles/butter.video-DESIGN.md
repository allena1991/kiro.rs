# Butter — chrome toys, elastic type

## Overview

A light, spacious creative-tool aesthetic that pairs plainspoken grotesk typography with playful digital objects. Cool gray canvases and soft rounded panels give glossy icons, dark interface collages and electric color effects room to perform. It suits expressive software and maker-oriented products that want technical credibility without corporate stiffness.

### Essentials

- Headlines behave like unadorned oversized speech: regular-weight DieGrotesk at 107.6px/0.992 for the opening, 60.4px/0.97 for statements and 45.5px/0.96 for features, with small positive tracking rather than tight negative tracking.
- The opening is a pale stage with a toy-like object hanging into it: a 900px scene, gray-to-off-white background, centered single-line promise across roughly three quarters of the width, 30px support/action gaps and a cropped reflective object above it. Use an original glossy product-symbol assemblage if literal product media is unavailable.
- Controls are rounded rectangles, not capsules: primary actions are 50px high with 16px corners and 8px 30px padding; the compact navigation action uses 10px corners at 39px high.
- Color lives inside the work, not across the page furniture: #fafafa canvas and #ededed panels dominate; vivid neon, chrome and photographic color are concentrated into objects, demonstrations and the closing artwork. Preserve this neutral-majority balance.
- Make capabilities tangible with collectible rounded objects: glossy squircle tiles punctuate a 60.4px statement and reappear as larger demonstrations. Use original symbols with lit edges and dark centers rather than flat feature icons.
- The ending is an artwork, not a final sales banner: a 60px rounded page edge overlaps the gray footer, four link groups lead into a near-full-width black word sculpture with multicolor downward glow, followed by small muted legal lines. Recreate the sculpture with the new identity or a short original word.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal action | `#1e1e1e` | `--color-action` | action, text | Primary button faces and navigation/footer links. |
| Primary ink | `#0f0f0f` | `--color-ink` | text | Headlines and primary copy. |
| Footer label gray | `#7e7e7e` | `--color-footer-label` | text | Visible 50% ink over the panel-gray footer for group labels. |
| Muted copy | `#9c9c9c` | `--color-muted` | text | Visible result of 40% primary ink over the off-white canvas; supporting card copy and eyebrows use rgba(15,15,15,0.4). |
| Inactive label | `#b4b4b4` | `--color-inactive` | text | Visible result of 30% ink on the canvas; inactive feature selectors and social-proof captions. |
| Silver atmosphere | `#d6d6d6` | `--color-hero-top` | background | Top of the opening gradient, fading to the canvas. |
| Action lettering | `#ebebeb` | `--color-on-action` | text | Light lettering over dark actions. |
| Panel gray | `#ededed` | `--color-panel` | surface, background | Feature cards, navigation trays, secondary buttons and footer. |
| Off-white canvas | `#fafafa` | `--color-canvas` | background, text | Continuous main page and light icon-button faces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Acid yellow edge | `#d9c915` | `--color-ochre` | border | Recommended-plan gradient lower region. |
| pricing pages | Emerald edge | `#1fda7c` | `--color-emerald` | border | Recommended-plan gradient middle. |
| pricing pages | Lime edge | `#4ce956` | `--color-lime` | border | Recommended-plan gradient transition. |
| pricing pages | Soft green edge | `#4ed57c` | `--color-green` | border | Recommended-plan gradient upper edge. |
| pricing pages | Pale lemon edge | `#fffd80` | `--color-lemon` | border | Recommended-plan gradient near its foot. |
| pricing pages | Mint edge | `#bbfac9` | `--color-mint` | border | Recommended-plan gradient start. |
| pricing pages | Cream edge | `#ffffe8` | `--color-cream` | border | Recommended-plan gradient end. |
| pricing pages | Comparison rule | `#d7d7d7` | `--color-rule` | border | Visible 15% ink over panel gray; accordion and comparison separators. |

## Typography

- **DieGrotesk** — Headlines, paragraphs, actions and navigation. Regular grotesk with compact proportions, broad rounded bowls and a direct, nearly utilitarian voice. If unavailable, use **Inter**. Use weight 400; retain the positive tracking and close display leading. Font stack: "DieGrotesk", "Inter", Arial, sans-serif.
- **ABCDiatype** — Small sentence-case section labels, artwork captions and footer group labels. Small, widely spaced technical-looking sans; visually typewriter-like without turning the whole page into a code theme. If unavailable, use **IBM Plex Sans**. Use regular weight with the specified tracking. Font stack: "ABCDiatype", "IBM Plex Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DieGrotesk | 400 | 107.6px | 0.992 | 0.0032em | Centered opening promise. |
| statement | DieGrotesk | 400 | 60.4px | 0.97 | 0.006em | Manifesto statements, large capability chapters and prices. |
| heading | DieGrotesk | 400 | 45.5px | 0.96 | 0.008em | Feature headings, section titles and large card headings. |
| subheading | DieGrotesk | 400 | 24.5px | 1.15 | 0.03em | Opening support line, card titles and accordion questions. |
| body | DieGrotesk | 400 | 20.7px | 24px | 0.033em | Short feature explanations and footer links. |
| small | DieGrotesk | 400 | 16px | 21px | 0.044em | Card descriptions, feature lists and button labels. |
| navigation | DieGrotesk | 400 | 16px | 20px | 0.044em | Header links and login. |
| eyebrow | ABCDiatype | 400 | 13.5px | 24px | 0.036em | Sentence-case labels above headings and fine artwork labels. |

**Notes:**

- Keep all core text at weight 400. Scale, line breaks and contrast do the hierarchical work.
- Display leading is slightly less than the font size. Small copy has looser relative tracking; do not apply negative display tracking.
- Section labels sit 25px above headings; paragraph blocks typically sit another 25px below. Distinguish the 24.5px opening support from the 20.7px ordinary body.

## Layout

**Density:** Airy: compact text clusters sit within expansive sections and large media stages.

### Spacing

| Value | Use |
| --- | --- |
| 16px | Button icon gaps and account-tray spacing. |
| 25px | Default grid gutter, label-to-heading gap and stacked-copy rhythm. |
| 30px | Opening copy/action separation and button side padding. |
| 50px | Large card interior and proof-strip vertical padding. |
| 60px | Section-heading to grid separation. |
| 70px | Footer links to word sculpture. |
| 140px | Standard major-section top and bottom padding. |
| 160px | Footer top padding. |
| 260px | Text-first opening top padding. |

### Containers and grids

- **main container**: side padding 66.1px. Centered desktop content spans about 1308px at a 1440px viewport; preserve broad side margins.
- **editorial grid**: 12 columns · gap 25px. Underlying alignment for half-width media and text, four-up showcases and footer groups.
- **split feature**: 2 columns · gap 25px. Two 641px media/card columns at desktop; copy is usually constrained to about 514px and vertically centered.
- **four-up showcase**: 4 columns · gap 25px. Four 308px media tiles or plan columns.
- **text measure**: max width 514px. Feature paragraphs; short enough for three or four lines.
- **opening demonstration**: max width 1086px. Centered wide product film below a text-first product opening.

## Corner radius

| Element | Radius |
| --- | --- |
| feature panels | 32px |
| main buttons and trays | 16px |
| compact header button | 10px |
| page ending | 60px |

## Surfaces and depth

### Surfaces

#### Main canvas · level 0

**Use:** Continuous light page surface ending above the footer.

**CSS:** `background: #fafafa; border-radius: 0px 0px 60px 60px; position: relative; z-index: 1; margin-bottom: -60px`

**Observed:** A single rounded lower edge overlaps the darker footer rather than rounding every section.

**Transfer:** Keep the continuous sheet effect even on a shorter landing page.

#### Silver opening · level 0

**Use:** Atmospheric opening stage.

**CSS:** `background: linear-gradient(#d6d6d6 0%, #fafafa 100%)`

**Observed:** A soft vertical neutral fade, without a hard horizon or colored wash.

**Transfer:** Let reflective objects provide color against this pale stage.

#### Soft panel · level 1

**Use:** Large demonstrations, capability cards and galleries.

**CSS:** `background: #ededed; border-radius: 32px; overflow: hidden; box-shadow: none`

**Observed:** Flat neutral panel; shadows belong to objects and interface art inside it, not to the marketing card itself.

**Transfer:** Use edge clipping to make a substantial interface look larger than its container.

#### Footer field · level 0

**Use:** The broad final artwork field.

**CSS:** `background: #ededed; padding: 160px 0px 60px`

**Observed:** Link groups occupy the upper part; the art dominates the lower part.

**Transfer:** Treat it as a final expressive canvas, not a compact utility bar.

#### Recommended plan edge · level 1

**Only for:** pricing pages

**Use:** A thin spectral frame around one recommended plan.

**CSS:** `background: linear-gradient(#bbfac9 3.28%, #4ed57c 14.37%, #1fda7c 50.97%, #4ce956 60.83%, #d9c915 70.95%, #d9c915 88.34%, #fffd80 94.89%, #ffffe8 100%); border-radius: 32px; padding: 2px; overflow: hidden`

**Observed:** The inner gray card covers almost all the gradient; only its narrow edge remains visible.

**Transfer:** Emphasize one tier without tinting the entire card.

## Components

### Floating navigation

**Use:** Persistent access above the page scene.

**CSS:** `position: fixed; height: 88px; z-index: 30; top: 0px; left: 0px; width: 100%`

**Text style:** `navigation` — DieGrotesk 400 · 16px/20px · tracking 0.044em

**Observed:** Two disconnected light-gray trays: logo, horizontal links and a vertical-ellipsis menu on the left; login and a dark compact action on the right. The trays begin 24px below the top. On scroll the left tray contracts to logo and menu.

**Transfer:** Keep the space between trays transparent so artwork remains visible behind them.

### Account tray

**Use:** Login and compact conversion control.

**CSS:** `display: flex; align-items: center; gap: 16px; background: #ededed; border-radius: 16px; padding: 10.5px 12px 10.5px 22px; height: 60px; box-sizing: border-box`

**Text style:** `navigation` — DieGrotesk 400 · 16px/20px · tracking 0.044em

**Observed:** The action is nested within the pale tray rather than isolated at the edge of the viewport.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 16px; height: 50px; padding: 8px 30px; box-sizing: border-box; border: 1px solid transparent; border-radius: 16px; background: #1e1e1e; color: #ebebeb`

**Text style:** `small` — DieGrotesk 400 · 16px/21px · tracking 0.044em

**Observed:** Short text only in the opening; plan-selection variants are 70px high and fill the card's inner width. A layered spectral underlay is hidden behind the dark face in the resting state.

**States:** Declared: hover is unspecified; focus-visible box-shadow rgb(60, 60, 60) 0px 0px 0px 0.1rem and outline none.

**Transfer:** Use the dark face for conversion and the same rounded-rectangle geometry for all action variants.

### Secondary button

**Use:** Exploration and sales links beside section headings.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 16px; height: 50px; padding: 8px 30px; box-sizing: border-box; border: 1px solid transparent; border-radius: 16px; background: #ededed; color: #0f0f0f`

**Text style:** `small` — DieGrotesk 400 · 16px/21px · tracking 0.044em

**Observed:** A thin right arrow follows the label. It often sits at the right edge of a section-heading row.

### Arrow tile

**Use:** Compact link in a large capability card.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 50px; height: 50px; padding: 8px; box-sizing: border-box; border: 1px solid transparent; border-radius: 16px; background: #fafafa; color: #0f0f0f`

**Observed:** A small line arrow occupies the center; the control sits beside the heading near the card's upper-right corner.

**Transfer:** Give each icon-only link an accessible destination label.

### Capability card

**Use:** Paired capability highlights.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 25px; background: #ededed; border-radius: 32px; overflow: hidden`

**Text style:** `heading` — DieGrotesk 400 · 45.5px/0.96 · tracking 0.008em

**Observed:** Heading and Arrow tile at the top, a large product-art region in the middle, muted small copy at the bottom. Text is inset 50px; imagery can meet the edge.

**Transfer:** Use one concrete capability per card; retain media dominance.

### Footer link group

**Use:** Grouped exploration, contact and utility links above the artwork.

**CSS:** `display: flex; flex-direction: column; gap: 5px; color: #1e1e1e`

**Text style:** `body` — DieGrotesk 400 · 20.7px/24px · tracking 0.033em

**Observed:** Four groups align to the editorial grid. A small technical-style group label is separated from the links by 26px. Links have no resting underline.

**Transfer:** Keep utility copy above the sculpture, not superimposed over it.

### Plan grid

**Only for:** pricing pages

**Use:** Compare commercial tiers.

**CSS:** `display: grid; grid-template-columns: repeat(4, 1fr); gap: 25px`

**Text style:** `small` — DieGrotesk 400 · 16px/21px · tracking 0.044em

**Observed:** Tall gray rounded columns carry a light inset name strip, muted short description, 60.4px price, billing qualifier, dark full-width action and a checkmarked feature list. The recommended tier has a small badge above its spectral edge.

**Transfer:** Keep price and action baselines aligned across tiers; adapt tier count to the offer.

### Question row

**Only for:** pricing pages

**Use:** Objection handling with expandable answers.

**CSS:** `border-bottom: 1px solid rgba(15, 15, 15, 0.15)`

**Text style:** `subheading` — DieGrotesk 400 · 24.5px/1.15 · tracking 0.03em

**Observed:** Right-hand accordion beside a left-hand heading and contact action. Question and thin chevron share a row, answer uses muted small copy. Closed rows are about 101px high; the open answer extends the row.

**Transfer:** Use real purchase objections rather than adding another promotional grid.

## Imagery and graphics

### Suspended glossy assemblage

**Use:** Signature object in the opening.

**Observed:** A close-up cluster of keys and charms intrudes from the top edge: chrome rings, glossy black and white forms, bright green and magenta accents. It is about a third of the viewport wide, cropped rather than shown as a complete centered packshot; the pale background leaves the headline unobstructed.

**Transfer:** Create an original object that turns the new product's central metaphor into something tactile. Minimum version: three overlapping lit symbolic objects, one metallic, one black and one brightly colored.

**Build:** Render or compose a cluster of 3–5 extruded symbols attached to a ring; use polished metal, a glossy dark material and one saturated enamel color. Place the cluster at top center, extend it beyond the viewport and keep it above the headline. A simplified SVG version can use offset duplicate paths for extrusion plus clipped white highlight gradients and soft contact shadows.

### Collectible squircle language

**Use:** Inline statement punctuation and enlarged capability art.

**Observed:** Puffy rounded-square objects carry distorted type, blurred marks, neon glows and textured imagery. Tiny versions replace visual pauses inside oversized copy; enlarged versions sit on dark library stages or pale panels. Their lit, soft edges distinguish them from flat app-icon grids.

**Transfer:** Turn the new product's outcomes into a small coherent family of tactile badges; include inline objects in a statement as well as a larger example.

**Build:** Use rounded-square masks with corners about 22% of the width, dark central fills, radial pale edge highlights and inset white glows. Clip original lettering or imagery inside. Create 3–5 variations using blur, displacement or a bright cyan/green halo, keeping each silhouette consistent.

### Interface cutouts and output galleries

**Use:** Capability proof throughout the page.

**Observed:** Near-black editor fragments, floating controls and overlapping windows are staged on pale gray cards. Some fill square 641px frames; others intentionally extend beyond an edge. Output examples mix fashion, product photography, typographic posters and colorful effects. Four-up galleries show diverse aspect ratios rather than identical mini-browser windows.

**Transfer:** Use authentic interface fragments and real output for the new product. Without full UI, build one legible task/result scene with a few controls, not a generic dashboard mockup.

### Monumental spectral word sculpture

**Use:** Required expressive closing artwork.

**Observed:** A huge black, slanted, flowing word silhouette spans nearly the full width. Layered cyan, pink, yellow-green and green bands spill down from its lower contour into a blurred glow. The sculpture occupies about 1360px by 583px, dwarfing the footer links; the upper black silhouette stays crisp.

**Transfer:** Create an original word or identity silhouette with the same black-top, luminous-extrusion construction. A short typeset word converted to SVG paths is an acceptable minimum.

**Build:** Convert a heavy italic word to an SVG path. Put a crisp black copy on top; behind it stack offset duplicates downwards in cyan, pink and lime with progressively larger blur and lower opacity. Keep offsets aligned to the silhouette, not a rectangular glow. Build a soft diffuse final layer under the colored bands and leave surrounding gray visible.

### Enterprise frosted tiles

**Only for:** pricing pages

**Use:** Small enterprise-benefit matrix.

**Observed:** Six pale squircle tiles in a three-by-two arrangement show restrained line icons, including a numeral. Their edges melt into the white background through an inset white glow, with small muted labels underneath.

**Transfer:** Use six or fewer concrete enterprise assurances, keeping these much less colorful than the product-art tiles.

**Build:** Use 170px gray squares with approximately 22% corner rounding, a white inset glow extending about 15% of tile width and centered thin gray SVG icons; place short labels beneath.

### Icons

**Observed:** Sparse line SVGs: action arrows about 14px by 11px at 1px stroke with rounded caps; pricing checkmarks about 18px by 13px at 2px stroke. Accordion chevrons are small, thin and gray.

**Transfer:** Use restrained single-stroke utility symbols; reserve expressive, dimensional symbols for artwork rather than navigation.

## Section recipes

How recurring sections are built.

### First screen: Suspended-object opening

**Observed:** A 900px-tall Silver opening sits beneath Floating navigation. From back to front: neutral vertical fade, a top-cropped glossy object cluster, centered headline and support/action cluster, floating trays. The 107.6px regular headline spans roughly three quarters of the width around the vertical middle; the object occupies the upper third and hangs behind the navigation. A 24.5px support line and Primary button follow at 30px intervals. Within the first 900px, object, entire promise, support and action are visible, with a generous empty lower field. Social proof and detailed UI begin below the fold.

**Transfer:** Use an original symbolic assemblage and a concise outcome promise rather than relying on a full product interface in the first screen. For detailed product pages, use a text-first opening with 260px top padding, 20.7px support and a wide demonstration immediately below. For pricing, use the same display recipe on a plain canvas, then billing controls and plan tops within the first screen.

**Avoid:** Do not turn the opening into a left-copy/right-dashboard template, a colored gradient billboard or a crowded set of badges.

**Text style:** `display` — DieGrotesk 400 · 107.6px/0.992 · tracking 0.0032em

### Object-punctuated statement

**Observed:** A centered 60.4px statement spans about 1078px over three lines. Small glossy squircle objects sit inline between phrases. Large surrounding whitespace makes the sentence itself the visual event.

**Transfer:** Write a single clear positioning statement and use original miniature objects at meaningful pauses, preserving readable syntax.

**Text style:** `statement` — DieGrotesk 400 · 60.4px/0.97 · tracking 0.006em

### Capability chapter

**Observed:** A 12-column editorial grid pairs a vertically centered text cluster with a 641px square or similarly tall demonstration. Eyebrow, heading and body are separated by 25px. Standard chapters use 140px vertical padding; expressive manifesto chapters use the larger statement recipe and more space. Media alternates sides.

**Transfer:** Pair one benefit with one demonstrable behavior; vary which side holds the media without changing alignment.

**Text style:** `heading` — DieGrotesk 400 · 45.5px/0.96 · tracking 0.008em

### Showcase grid and gallery

**Observed:** An eyebrow and heading precede either four narrow showcase tiles or a broad Soft panel gallery by 60px. Narrow tiles use 308px by 401px media followed by a 24.5px label and small muted description. Gallery outputs vary in size and aspect ratio, with fine captions below.

**Transfer:** Mix real outputs, not four interchangeable stock images, while keeping the shared panel and caption treatment.

### Tabbed creation modes

**Observed:** A large 641px by 706px visual panel sits beside three stacked 60.4px text selectors. Active text is dark, inactive text is 30% ink; only the active item has a short 20.7px explanation.

**Transfer:** Use for genuinely different ways of working, showing the selected workflow rather than a decorative tab strip.

### Artwork ending

**Observed:** The Main canvas ends with 60px lower corners over the Footer field. Four Footer link groups precede the Monumental spectral word sculpture by 70px. The full ending is about 1127px tall with 160px top and 60px bottom padding; muted legal lines align at opposite bottom edges. All page types finish with this artwork rather than a separate closing CTA band.

**Transfer:** Retain the visual crescendo even for shorter content: utility navigation above an oversized original identity sculpture, then a quiet legal baseline.

### Feature-card chapters

**Only for:** detailed product pages

**Observed:** Centered eyebrow and 45.5px heading introduce two-column Soft panel grids. Large art dominates each tile; 24.5px titles and 16px descriptions sit near the base. Occasional full-width cards interrupt the pair rhythm. A compact floating three-part chapter selector accompanies these chapters.

**Transfer:** Group capabilities into a few navigable themes and alternate pairs with wide demonstrations.

### Commercial comparison and objections

**Only for:** pricing pages

**Observed:** A centered display promise and billing switch lead into Plan grid. An enterprise split section introduces a frosted icon matrix. A long feature comparison retains the gray plan-column backdrops with 1px horizontal rules; category rows use chevrons. The final content block is a two-column heading/contact area and Question row stack.

**Transfer:** Use comparable entitlements, clear prices and genuine questions; preserve the neutral structure and narrow recommended-tier accent.

## Page flow

**Storyline:** Promise → credibility → tangible demonstrations → capability and workflow depth → examples or purchase reassurance → expressive identity ending.

### Broad creative-product marketing landing page

1. **Promise** — Centered theatrical headline, suspended reflective object and one conversion action.
2. **Social proof** — Small muted trust caption and horizontally arranged customer marks.
3. **Positioning** — Oversized centered statement with inline collectible objects, followed by an enlarged timeline-like art scene.
4. **Capability chapters** — Large editorial split sections show a library, customization and reusable workflows.
5. **Product demonstration** — Four-up overview, stacked workflow selectors and varied output gallery.
6. **Depth and proof** — A scaling demonstration, paired capability cards and a selected-work showcase.
7. **Identity ending** — Rounded page sheet gives way to link groups and glowing word sculpture.

**Transfer:** Use this as an adaptable balance of theatrical promise, tangible proof and editorial depth; choose the chapters that fit the new product.

### Commercial decision and objection handling

1. **Promise** — Display headline, one support sentence and monthly/annual billing switch.
2. **Pricing** — Four aligned plan cards with one narrowly accented recommended tier.
3. **Enterprise reassurance** — Split copy and six frosted assurance tiles.
4. **Comparison** — Detailed horizontal-rule feature matrix under continuous plan backdrops.
5. **Objection handling** — Left heading and contact action beside right accordion.
6. **Identity ending** — The shared sculpture-led footer.

**Transfer:** Keep offer comparison functional and restrained; use art chiefly in the shared ending.

### Detailed product-capability landing page

1. **Promise** — Text-first display opening and action above a wide product film.
2. **Social proof** — Muted trust line and brand marks.
3. **Capability chapters** — Alternating square demonstration and concise explanatory text.
4. **Feature depth** — Centered chapter headings, paired cards and occasional wide scenes, with floating chapter navigation.
5. **Technical credibility** — Rendering, workflow and code-related demonstrations remain visual rather than dense specifications.
6. **Identity ending** — The same rounded sheet and monumental footer art.

**Transfer:** Expose more capabilities than a broad landing page while keeping each explanation short and media dominant.

## Writing

Confident, enabling and lightly playful. It presents sophisticated creative power in ordinary language, grounding big promises in concrete actions and editable objects.

**Do not copy:** Do not reuse the Butter name, logo, proprietary artwork, customer identities, pricing, usage allowances, uniqueness claims or source headlines as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Name the product when explaining what it does; prioritize the reader's agency over company self-description.
- **Rhythm:** Short declarative headlines, occasional paired fragments, compact support paragraphs and simple verb-led actions. Technical nouns are welcome when immediately connected to a useful behavior.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A terse promise of expanded creative possibility. | 3–7 words | “Engineered for Creativity”<br>“It’s a whole new timeline.” |
| Section label | Small conversational framing line rather than a shouted category. | 3–7 words | “There’s a block for that”<br>“Create more. Start over less.” |
| Capability headline | Name an action and outcome, or use two complementary fragments. | 4–11 words | “Turn anything into everything.”<br>“One project. Everyone in sync.” |
| Support | Concrete operations followed by the benefit of keeping work reusable or editable. | 1–3 short sentences | “Combine fully editable blocks for motion, captions, effects, layouts, and brand assets.” |
| Action | Direct verb, short destination or commitment. | 2–4 words | “Get Started”<br>“View All Features”<br>“Contact Sales” |

**Words and phrasing to use:** build; remix; editable; your own; one project; reuse; customize; flexible; right in your browser

**Avoid:** revolutionary ecosystem; synergize; unparalleled excellence; enterprise-grade everything; effortless magic

**Rules:**

- Tie each broad promise to a concrete action in the next support line.
- Use playful contrasts sparingly, especially paired sentence fragments.
- Keep labels sentence case; let typography, not capitalization, carry emphasis.
- Describe technical capabilities through what the user can do with them.

## Do's and Don'ts

### Do

- Keep headlines regular at weight 400, with positive tracking and compact leading.
- Use the 25px gutter to align copy, panels and footer groups.
- Give ordinary chapters 140px top and bottom breathing room.
- Keep panel corners at 32px and action corners at 16px.
- Constrain feature body copy to about 514px rather than filling a half-page column.
- Make vivid objects sit inside a predominantly #fafafa and #ededed framework.
- End with an oversized original black word sculpture and downward spectral light.

### Don't

- Do not use bold condensed display type or negative tracking as the main voice.
- Do not turn every 50px action into a full capsule with 9999px rounding.
- Do not add generic elevation shadows to the flat gray marketing panels.
- Do not tint every capability section with a different saturated background.
- Do not replace the small sentence-case labels with uppercase colored eyebrow pills.
- Do not style the entire page like the dark editor UI shown inside demonstrations.
- Do not make all gallery examples identical landscape browser windows.
- Do not apply the recommended-plan spectral outline to every card.

## Motion and responsive

### Motion

**Observed:**

- Declared link mask-position transitions use 0.6s cubic-bezier(0.835,0.12,0.225,0.77); transforms use 0.4s with that curve.
- Declared color transitions include 0.5s cubic-bezier(0.835,0.12,0.225,0.77). Other background transitions use 0.5s cubic-bezier(0.2,0.715,0.205,0.99).
- Navigation contracts to a logo/menu tray while the account action remains available. Artwork includes changing material color and product-film scenes.

**Transfer:**

- Use masked duplicate-label movement for text links rather than adding visible duplicate words.
- Keep movement concentrated in collectible objects, media demonstrations and the expressive closing sculpture.

**Unknown:**

- Full artwork choreography and interaction timing are not established.
- The spectral button underlay's exact hover reveal behavior is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 424px, 640px, 768px, 1024px, 1240px and 1800px; some page styles also distinguish adjacent boundary widths.

**Transfer:**

- On narrow screens, preserve the object-over-centered-promise relationship while wrapping the headline rather than shrinking it into ordinary body text.
- Stack split demonstrations and reduce showcase columns; retain substantial rounded panels and the final full-width word sculpture.
- Let detailed comparison content scroll horizontally rather than compressing entitlement text into unreadable columns.

**Unknown:**

- Narrow-screen layouts, exact fluid type formulas and mobile navigation behavior are not established. These adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
