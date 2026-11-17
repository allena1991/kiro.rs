# Tempo — momentum on pale ground

## Overview

A pale, spacious infrastructure aesthetic pairs tightly set grotesk typography with fine routing lines and cinematic impressions of speed. Black actions and white, generously rounded panels give complex products a composed, tangible presence. Teal-blue motion photography and an occasional expansive serif quotation interrupt the otherwise neutral palette; the density is low around promises and higher inside explanations and directories.

### Essentials

- Compact promises under sweeping linework: centered 53.3px, weight 500 grotesk headlines with 0.95 line height and -0.04em tracking occupy a 600px measure, beneath an 862px floating navigation capsule.
- Speed is expressed in two complementary materials: faint bundled curves over the pale opening, and horizontally streaked photographic color in proof or editorial media. Include both; SVG routes and directionally blurred original photography are the minimum equivalents.
- Almost all reading happens on #f5f5f5 with black headings and white panels; chromatic teal and blue are concentrated inside media and a single immersive proof band rather than dispersed among buttons or headings.
- Actions are small black lozenges, not display objects: 48px high with 32px horizontal padding, 14px/20px medium text, accompanied by an equally sized pale secondary action with an 8px gap.
- A technical index sits above human-scale headings: 10px/16px uppercase labels at 0.06em tracking, 32px above 36px/1.1 headings; major chapters breathe with 100px or 160px top spacing.
- Proof changes scale without turning into a dashboard: 36px metrics sit over 14px captions under thin rules, while a 72px/0.95 light serif quotation floats on a full-width blue motion field. Preserve a large atmospheric proof moment even when the content is an editorial statement rather than a quote.
- Soft panels have a deliberate radius hierarchy: 29.8px for ordinary cards, 59.5px for broad conversion cards, with no drop shadows; the closing composition balances two audience routes before a flat black multi-column footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep ocean | `#001923` | `--color-ocean` | background | Immersive blue photographic proof field, not the default page ground. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-paper` | surface, text | Unshadowed content cards; proof text on dark media. |
| Pale ground | `#f5f5f5` | `--color-canvas` | background, text | Default page ground and text on black actions. |
| Demonstration ground | `#f0f0f0` | `--color-media-stage` | surface | Large product illustration backplates, distinct from white UI objects. |
| Control wash | `#ebebeb` | `--color-soft-fill` | surface | Visible black at 4% over pale ground; secondary controls and form fields. |
| Navigation fog | `#e9e9e9` | `--color-nav-glass` | surface | Visible gray #e1e1e1 at 60% over pale ground, with blur behind it. |
| Opening action wash | `#e9e9e9` | `--color-hero-secondary` | action | Visible #c2c2c2 at 24% over pale ground; opening secondary action. |
| Fine edge | `#e1e1e1` | `--color-rule` | border | Visible black at 8% over pale ground; thin chapter and list rules. |
| Footer gray | `#999999` | `--color-dark-secondary` | text, link | Visible white at 60% over black; footer navigation. |
| Index gray | `#939393` | `--color-muted` | text | Visible black at 40% over the pale ground; eyebrows and subdued conversion support. |
| Inactive gray | `#707070` | `--color-inactive` | text, link | Inactive product selectors and product-stage descriptions. |
| Secondary ink | `#6c6c6c` | `--color-secondary` | text, link | Visible result of black at 56% over the pale ground; standard explanatory copy. |
| Opening charcoal | `#434343` | `--color-hero-support` | text | Centered opening support sentence. |
| Black ink | `#000000` | `--color-ink` | text, action, background | Headings, primary actions, routing details and footer ground. |

## Typography

- **Pilat** — Marketing headlines, paragraphs, navigation and labels. Compact contemporary grotesk with large x-height, nearly monoline forms and tightly joined headline spacing. If unavailable, use **Inter**. Use weights 400–500 and preserve the compact measures and negative headline tracking. Font stack: "Pilat", "Inter", Arial, sans-serif.
- **HB Set** — Monumental atmospheric proof statements. Light, high-contrast editorial serif with graceful fine strokes. If unavailable, use **Newsreader**. Use weight 300, upright, with tight line spacing. Font stack: "HB Set", "Newsreader", Georgia, serif.
- **Tempo JetBrains Mono** (only for numbered technical explanations and protocol demonstrations) — Small sequence indices and code. Practical monospace; sequence labels are light and widely tracked. If unavailable, use **JetBrains Mono**. Font stack: "Tempo JetBrains Mono", "JetBrains Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| proof-statement | HB Set | 300 | 72px | 0.95 | -0.04em | fixed | A large centered quotation or editorial proof statement against immersive motion imagery. |
| display | Pilat | 500 | 53.3px | 0.95 | -0.04em | size clamp(36px, 1.6667vw + 29.3px, 72px) | Opening promise, usually two lines in a 600px measure; left aligned for editorial indexes. |
| heading | Pilat | 500 | 36px | 1.1 | -0.02em | fixed | Section headings and prominent metric values. |
| selector-heading | Pilat | 500 | 30px | 1.1 | -0.02em | fixed | Product chapter selectors; also shorter form and newsletter headings. |
| conversion-heading | Pilat | 500 | 22px | 1.2 | -0.02em | fixed | Titles in broad audience conversion panels. |
| card-heading | Pilat | 500 | 20px | 1.2 | -0.02em | fixed | Capabilities, story headlines and feature-row titles. |
| body | Pilat | 500 | 16px | 22px | normal | fixed | Opening support, explanatory paragraphs and ordinary text links. |
| small | Pilat | 500 | 14px | 20px | normal | fixed | Buttons, captions, footer lists and compact editorial summaries. |
| navigation | Pilat | 500 | 14px | 16px | normal | fixed | Navigation capsule links. |
| eyebrow | Pilat | 500 | 10px | 16px | 0.06em, uppercase | fixed | Section category labels and article categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| numbered technical explanations | sequence-index | Tempo JetBrains Mono | 400 | 10px | 14px | 0.06em | fixed | Two-digit index at the far left of a ruled row. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Medium weight is the baseline even for body copy; do not compensate for small sizes with bold headings.
- Display tracking is twice as tight proportionally as section and card headings. Keep line breaks compact rather than stretching the opening across the entire page.
- The serif is a single expressive change of register for major proof, not an alternate body font.

## Layout

**Density:** Airy between chapters, compact within text pairs and controls; illustrations have much more breathing room than their labels.

### Spacing

**Spacing system:**

- **grid** 8px — Primary spacing rhythm; 12px text pairs and 4px control insets are deliberate half-step exceptions.

| Value | Use |
| --- | --- |
| 8px | Paired actions and tight support pairs. |
| 12px | Card heading to paragraph and paragraph to text link. |
| 16px | Compact media rail gaps and metric-to-caption separation. |
| 24px | Default card grid gutters. |
| 32px | Eyebrow to heading, ruled row padding and medium card padding. |
| 48px | Heading to grids, conversion panel subgroups and form padding. |
| 64px | Broad conversion card padding and feature-card copy insets. |
| 80px | Inset section sides and footer padding. |
| 100px | Lighter chapter starts and directory group separation. |
| 160px | Major chapter starts. |
| 192px | Default conversion section bottom breathing room. |
| 240px | Form-led closing section bottom breathing room. |

### Containers and grids

- **wide canvas**: max width 2560px · side padding 60px. Default broad marketing sections; at 1440px the content width is 1320px.
- **inset technical content**: max width 2560px · side padding 80px. Product demonstrations, technical chapters and footer; 1280px of content at 1440px.
- **copy measure**: max width 600px. Opening and section heading measure; support copy may narrow to 400px or 280px beside large diagrams.
- **three card grid**: 3 columns · gap 24px. Capabilities, resource cards and editorial proof indexes.
- **split stage**: 12 columns · gap 24px. One-third text column beside two-thirds media; left-hand rule-led text balances a large diagram or illustration.
- **audience pair**: 2 columns · gap 24px. Equal-width conversion cards.
- **directory results** (only for searchable ecosystem directories): 2 columns · gap 16px. Right-side result cards beside a persistent left search and category rail; results occupy about three fifths of the content width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 9999px (pill) |
|  | ordinary cards | 29.8px |
|  | conversion panels | 59.5px |
| searchable ecosystem directories | directory cards | 44.6px |
| lead collection sections | form panels | 74.4px |
| lead collection sections | form fields | 22.3px |

## Surfaces and depth

### Surfaces

#### Pale canvas · level 0

**Use:** Default reading surface.

**CSS:** `background: #f5f5f5; color: #000000`

#### White panel · level 1

**Use:** Content grouping without elevation effects.

**CSS:** `background: #ffffff; border-radius: 29.8px; box-shadow: none`

**Observed:** White against pale gray supplies the edge; no default outline or floating shadow.

**Transfer:** Use broad uninterrupted panels rather than outlined dashboard tiles.

#### Product backplate · level 0

**Use:** A neutral stage around a smaller product object.

**CSS:** `background: #f0f0f0; border-radius: 29.8px; overflow: hidden`

**Observed:** A white interface object occupies the center with abundant neutral perimeter.

**Transfer:** Frame only the minimum UI needed to explain the benefit.

#### Navigation glass · level 2

**Use:** Persistent floating navigation.

**CSS:** `background: rgba(225, 225, 225, 0.6); backdrop-filter: blur(20px); border-radius: 29.8px`

**Observed:** A restrained gray capsule, not a full-width header stripe.

**Transfer:** Keep the glass limited to navigation rather than repeating it on content cards.

#### Atmospheric proof field · level 0

**Use:** Immersive proof statement.

**CSS:** `background: #001923; color: #ffffff; padding: 80px 48px`

**Observed:** Full-width blue streak photography carries a centered white serif statement in a 900px measure.

**Transfer:** Match the directional light and deep-blue contrast; exact light bands are not essential.

#### Black footer ground · level 0

**Use:** Definite page ending.

**CSS:** `background: #000000; padding: 80px; color: #ffffff`

**Observed:** Flat dark field, with small navigation and a large open left area around a compact brand symbol.

**Transfer:** End with a useful map, not a second oversized hero.

## Components

### Floating navigation

**Use:** Persistent primary wayfinding.

**CSS:** `display: flex; align-items: center; gap: 4px; max-width: 862px; height: 52px; padding: 4px 4px 4px 24px; background: rgba(225, 225, 225, 0.6); backdrop-filter: blur(20px); border-radius: 29.8px; box-sizing: border-box`

**Text style:** `navigation` — Pilat 500 · 14px/16px

**Observed:** Centered 24px below the top edge; compact wordmark on the left, five evenly distributed destinations, and a black 44px contact action at the right. Fixed above subsequent sections.

**Transfer:** Use a compact real wordmark or plain product name with a comparable horizontal footprint.

### Primary button

**Use:** Highest-priority conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #000000; color: #f5f5f5; border-radius: 9999px; height: 48px; padding: 4px 32px; gap: 4px; box-sizing: border-box`

**Text style:** `small` — Pilat 500 · 14px/20px

**Observed:** Text-only pill; width follows content. Closing cards use a 44px version with 24px side padding, while form submits are 52px high.

**States:** Declared: hover unspecified; focus-visible solid 2px outline with 2px offset; active opacity 0.65.

### Secondary button

**Use:** Parallel route beside the primary action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: rgba(194, 194, 194, 0.24); color: #000000; border-radius: 9999px; height: 48px; padding: 4px 32px; box-sizing: border-box`

**Text style:** `small` — Pilat 500 · 14px/20px

**Observed:** Opening companion matches primary height. Supporting actions elsewhere use black at 4%, 24px horizontal padding and heights of 40px or 44px.

**States:** Declared: hover unspecified; focus-visible solid 2px outline with 2px offset; active opacity 0.65.

### Illustrated feature card

**Use:** Explain an outcome through a title, short paragraph and large diagram.

**CSS:** `display: flex; flex-direction: column; background: #ffffff; border-radius: 29.8px; overflow: clip`

**Text style:** `card-heading` — Pilat 500 · 20px/1.2 · tracking -0.02em

**Observed:** Three equal cards, 424px wide by 602px high at desktop. Copy has 64px top and side insets with 12px title-to-body spacing; the lower 424px square contains delicate line or interface art.

**Transfer:** Keep the picture simple and related to the function, with a few small labeled nodes rather than decorative stock icons.

### Customer media card

**Use:** Cinematic outcome-led proof in a horizontal rail.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: space-between; align-items: flex-start; background: #000000; color: #f5f5f5; border-radius: 29.8px; padding: 32px; overflow: hidden`

**Text style:** `card-heading` — Pilat 500 · 20px/1.2 · tracking -0.02em

**Observed:** Full-bleed real-world image, small white logo at top left and concise outcome at bottom left. The active card is 835px by 469px, followed by 469px square cards separated by 16px; the rail continues beyond the right edge.

**Transfer:** Choose subject motion, natural light and dark zones for text; use a bottom gradient plus diagonal shade rather than a uniform opaque scrim.

### Ruled metric

**Use:** Sparse quantitative proof.

**CSS:** `display: flex; flex-direction: column; gap: 16px; border-top: 1px solid rgba(0, 0, 0, 0.16); padding-top: 23px`

**Text style:** `heading` — Pilat 500 · 36px/1.1 · tracking -0.02em

**Observed:** Three equal columns. The value appears first visually, then a small muted descriptive caption; there is no card fill or accent-colored number.

**Transfer:** Keep units inline with the number, and include enough caption context to make the measurement meaningful.

### Audience conversion card

**Use:** Offer two modes of adoption.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 48px; padding: 64px; background: #ffffff; border-radius: 59.5px`

**Text style:** `conversion-heading` — Pilat 500 · 22px/1.2 · tracking -0.02em

**Observed:** Eyebrow, title-and-paragraph group, then action; a 12px internal text pair sits within the larger group rhythm. Default is two equal cards, 648px by 366px. The assisted route has the dark action and the self-serve route a pale one.

### Footer link column

**Use:** Compact grouped destinations on the black ending.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #ffffff`

**Text style:** `small` — Pilat 500 · 14px/20px

**Observed:** White group heading above 28px link rows in white at 60%. Four destination columns occupy the right two thirds; a company subgroup sits beneath the first column, with social, legal and locale links along the bottom.

**States:** Declared: hover links turn #ffffff; focus-visible links turn #ffffff with solid 2px outline and 2px offset.

**Transfer:** Keep groups compact and use the left area for a small brand symbol, not giant lettering.

### Directory card

**Only for:** searchable ecosystem directories

**Use:** Scannable provider or integration result.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 32px; background: #ffffff; border-radius: 44.6px`

**Text style:** `body` — Pilat 500 · 16px/22px

**Observed:** 360px by 186px tile; small monochrome mark in a 40px pale badge, then a name and 14px one-line service description. Results repeat in a two-column grid.

**States:** Declared: hover unspecified; focus-visible 2px solid black outline with 4px offset.

**Transfer:** Preserve the mark-to-copy separation and short functional descriptions.

### Numbered disclosure

**Only for:** technical product explanations

**Use:** Answer detailed adoption questions without a card stack.

**CSS:** `border-top: 0.5px solid rgba(0, 0, 0, 0.08); padding: 32px 0`

**Text style:** `body` — Pilat 500 · 16px/22px

**Observed:** Two-digit sequence index at far left, question and answer beginning around one third across the width, plus/minus at far right. Answer measure is 480px. The first row is open while subsequent rows are collapsed.

**States:** Declared: hover unspecified; focus-visible summary solid 2px outline with 8px offset.

**Transfer:** Use native details and summary; put the answer under the question, not under the index.

### Lead form panel

**Only for:** lead collection sections

**Use:** Focused closing request after an explanatory page or directory.

**CSS:** `display: flex; flex-direction: column; gap: 32px; padding: 48px; background: #ffffff; border-radius: 74.4px`

**Text style:** `small` — Pilat 500 · 14px/20px

**Observed:** Centered 845px-wide panel with a 30px heading. Paired name fields, full-width email, paired company and role, then full-width message. Field wash is black at 4%, with 22.3px corners; labels sit above. Privacy link bottom left and black submit bottom right.

**Transfer:** Preserve the compact field sequence and a single action; use only fields needed to route the request.

## Imagery and graphics

### Bundled route linework

**Use:** A signature atmospheric line motif at the opening, with related functional diagrams in explanation sections.

**Observed:** Fine parallel gray curves sweep down from beyond the upper edge and arc across the pale ground. They fade toward the edges and never cross the headline densely. Functional diagrams use the same curving language with small nodes and minimal labels.

**Transfer:** Translate the product's flow into routes, links or conduits. A static vector composition is sufficient if interactive artwork is unavailable.

**Build:** Use an SVG viewBox of 1440 543 with 6–10 long cubic Bézier routes entering from above. Duplicate each route at 2px offsets to create bundles of 2–3 strokes, using rgba(0,0,0,0.08) to rgba(0,0,0,0.24), stroke-width 1px, fill none. Add sparse short angled notches and an opacity mask fading to transparent at the sides and lower edge. Keep the visible drawing mostly in the top 200px.

### Directional photographic atmosphere

**Use:** Signature color material for editorial covers, featured proof and the immersive statement.

**Observed:** Long horizontal or shallow diagonal streaks turn city lights, greenery and blue reflections into impressions of movement. Deep teal, near-black and occasional warm cream highlights dominate. Editorial covers are roughly 16:9; featured directory cards are near-square; the statement uses a full-width blue field.

**Transfer:** Make original low-shutter-speed photographs of an environment relevant to the new product. A minimum version uses a real photo with strong directional blur, dark framing and a few retained light streaks rather than a smooth generic gradient.

**Build:** Scale a photograph beyond its clipped frame, apply an SVG feGaussianBlur with stdDeviation='28 1', and angle the image layer by about -8deg. Overlay narrow, softly blurred horizontal light bands using rgba(255,255,255,0.12) over a deep ocean base. Add broad black translucent side shading and fine monochrome noise; leave a dark calm area behind text. Tune blur so some environmental texture remains.

### Human-world proof photography

**Use:** Hero film and customer media cards.

**Observed:** Cinematic city streets, couriers, people working and walking, cropped closely with natural directional light and muted green-blue or warm brown grading. Subjects are often caught in movement; text sits on darker portions.

**Transfer:** Show the product's consequences in a real environment rather than studio portraits or floating devices. Keep a human action recognizable even when the surroundings blur.

### Minimal product models

**Use:** Capability cards and broad neutral demonstration stages.

**Observed:** Small white UI panels, thin gray connectors, circular nodes and restrained status details on pale gray. Centered interfaces occupy only part of the stage; purple charts and green status indicators remain internal to the demonstration.

**Transfer:** Use one legible simplified interface task or a vector process diagram, not an entire dashboard. Keep functional color within the UI.

### Paired identity artwork

**Only for:** customer story indexes

**Use:** Story thumbnail alternative to documentary imagery.

**Observed:** Two white partner marks centered on a black field with sweeping bundled routes, sometimes in a restrained partner hue. Some editorial pairings use pale ground instead.

**Transfer:** Pair authorized new identities with an original route composition; use simple typography if marks are unavailable.

**Build:** On a 16:10 black panel, place two white identity labels on the horizontal center with a short vertical divider. Draw 5–8 thin bundled SVG arcs behind them, sweeping from lower left to upper right, with low-opacity white strokes and one restrained partner color.

### Icons

**Observed:** Small filled SVG arrows, chevrons and disclosure marks, predominantly 16px or 18px; 20px symbols appear in footer actions. Icons inherit black, pale text or muted ink and sit at the end of short links or within circular controls.

**Transfer:** Use a consistent compact geometric icon set. Prefer simple chevrons to oversized outlined arrows and use tiny nodes for diagrams rather than colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Route canopy opening

**Observed:** Pale canvas is the back layer; a wide, faint bundled-route canopy occupies the top portion, with Floating navigation above it. A centered 600px-wide, two-line display promise begins about 247px down, taking roughly the middle third of the width. The support sentence follows with 32px spacing, then paired 48px Primary button and Secondary button with an 8px gap. A low-contrast monochrome proof-logo strip stretches near the lower edge of the opening. The first 900px show the entire promise, support, actions, logos and the upper portion of a large rounded cinematic film, inset 60px from each side. The opening copy region is about 647px high; the film continues below the fold.

**Transfer:** Retain the compact promise and abstract route canopy even without specialized media; use an original SVG route sculpture and a real-world product-context film or still. Technical landing variants add a 10px category above the centered promise and bring a large UI/process panorama into the lower fold. Editorial indexes use a left-aligned promise at 180px top spacing; directory introductions stay centered; company narratives put a more prominent line sculpture above a left-aligned title.

**Avoid:** Do not replace the canopy with a glowing 3D orb, enlarge the headline to billboard size or turn the first screen into a dense dashboard. Do not center all later sections just because the opening is centered.

**Text style:** `display` — Pilat 500 · 53.3px/0.95 · tracking -0.04em

### Indexed chapter heading

**Observed:** A 10px uppercase eyebrow sits 32px above a left-aligned 36px heading, generally constrained to 600px. The next grid begins 48px below. Major chapter top padding is 160px; lighter explanatory chapters use 100px. Technical variants use 24px between eyebrow and heading.

**Transfer:** Use a short category label and an outcome-led heading; change spacing by chapter importance, not arbitrarily.

**Text style:** `heading` — Pilat 500 · 36px/1.1 · tracking -0.02em

### Three outcome models

**Observed:** Three Illustrated feature cards on the wide canvas use 24px gutters. Text leads above understated diagrams. Technical variants put roughly 395px-wide gray 4:3 diagram stages above the title and paragraph, separated by 48px gutters.

**Transfer:** Choose three meaningfully different benefits and give each one a specific visual model, not repeated stock art.

**Text style:** `card-heading` — Pilat 500 · 20px/1.2 · tracking -0.02em

### Pinned capability stage

**Observed:** One-third width text selectors sit beside a two-thirds Product backplate. Ruled 30px product names are stacked at 32px intervals; only the active item expands into a 16px paragraph and a text link. A small centered white UI object changes in the right stage as the chapter advances.

**Transfer:** Use the pattern for a small suite of related capabilities. Keep the stage stable in size and let content, not layout, change.

**Text style:** `selector-heading` — Pilat 500 · 30px/1.1 · tracking -0.02em

### Measured proof and atmospheric statement

**Observed:** Ruled metric components share a three-column row beneath an indexed heading. An Atmospheric proof field contrasts with the surrounding light reading ground: small white identity above a centered 72px light serif statement, then a two-line attribution with 40px group spacing.

**Transfer:** Present credible scale in unboxed values and give one important endorsement or editorial conclusion an immersive treatment. Its position can move to fit the story.

**Text style:** `proof-statement` — HB Set 300 · 72px/0.95 · tracking -0.04em

### Ruled explanation and diagram

**Observed:** A Split stage composition has short ruled descriptions in the left third and an 845px-wide fine-line diagram on the right. Thin routes fan outward from a small origin, pass repeated nodes, then bend toward a common destination.

**Transfer:** Explain system behavior through one clear path and repeated operations. Keep connectors thin enough that the drawing feels technical rather than cartoonish.

**Text style:** `card-heading` — Pilat 500 · 20px/1.2 · tracking -0.02em

### Editorial resources

**Observed:** Three 424px by 239px rounded motion-photo covers lead into titles, compact summaries and category labels. Copy is outside the image on the pale ground, 24px below the cover; 12px separates heading and summary.

**Transfer:** Use a few substantive next reads with visually related covers; maintain a narrower summary measure than the image width.

**Text style:** `card-heading` — Pilat 500 · 20px/1.2 · tracking -0.02em

### Audience close and footer

**Observed:** A major indexed heading precedes two Audience conversion cards with 24px gutter and 48px heading-to-grid spacing. The whole chapter has 160px top and 192px bottom padding. Black footer ground follows, 560px tall at desktop, with a small symbol at left and compact destination groups at right.

**Transfer:** Offer assisted and self-serve next steps when both are real; otherwise adapt the paired panels to two meaningful adoption modes without making one a fake choice.

**Text style:** `conversion-heading` — Pilat 500 · 22px/1.2 · tracking -0.02em

### Editorial proof index

**Only for:** customer story collections

**Observed:** Left-aligned eyebrow and display promise introduce a three-column white-card index with 24px gutters. Each card has 411px by 257px media above a 32px inset copy area, category, 20px headline, muted summary and a low read-story link. A ruled newsletter band closes the index before Black footer ground.

**Transfer:** Use a consistent card hierarchy while mixing documentary photographs, interface compositions and paired identities.

**Text style:** `display` — Pilat 500 · 53.3px/0.95 · tracking -0.04em

### Directory and form close

**Only for:** ecosystem directories and lead-focused product pages

**Observed:** Directories open with a centered promise and an edge-clipped rail of motion-photo featured cards, then shift to persistent left search/categories and two-column Directory cards on the right. Group titles use 36px and subgroup titles 20px. Lead form panel ends the content with 160px top and 240px bottom breathing room, followed by Black footer ground. Technical product pages use the same form close after Numbered disclosure rows.

**Transfer:** Keep taxonomy concise, descriptions practical and results visually uniform; switch from browsing to one focused request at the end.

**Text style:** `selector-heading` — Pilat 500 · 30px/1.1 · tracking -0.02em

## Page flow

**Storyline:** Compact promise → real-world or product demonstration → outcome chapters → credible proof → deeper explanation or resources → appropriate adoption route → compact black site map.

### Broad product or platform introduction

1. **Promise** — Route-canopy opening with two actions, logos and a cinematic proof film.
2. **Outcome framing** — Three illustrated cards group the main ways the product creates value.
3. **Product demonstration** — Pinned selector chapter alternates small UI models on a stable neutral stage.
4. **Social and quantified proof** — Cinematic customer rail, ruled metric row and immersive serif statement.
5. **Deeper understanding** — Fine-line explanation stage and three editorial resources.
6. **Closing call** — Paired audience adoption panels followed by the black site map.

**Transfer:** Use this as the default marketing vocabulary; vary the number and order of proof and explanation chapters to fit the new product.

### Focused technical product landing

1. **Promise and demonstration** — Centered category, display promise, single action, monochrome logos and a wide UI/process panorama.
2. **Benefits** — Three neutral diagram stages with short benefit descriptions.
3. **Mechanism** — Ruled explanation paired with a step sequence and request-response model.
4. **Capabilities** — Three detailed miniature process illustrations.
5. **Customer proof** — Large rounded cinematic case-study panel with light text.
6. **Objection handling** — Numbered disclosure rows.
7. **Closing call** — Centered lead form and black site map.

**Transfer:** Lead with the benefit, then show how the mechanism works before asking for technical commitment.

### Company or product rationale

1. **Identity** — Expansive routing sculpture over a left-aligned display title.
2. **Rationale** — Narrow explanatory prose and a concise ruled fact table.
3. **Use cases** — Numbered broad ruled rows with descriptions beginning in the middle column.
4. **Credibility** — Centered heading and monochrome identity grid.
5. **Exploration** — Six small white destination cards.
6. **Closing call** — Paired adoption panels and black site map.

**Transfer:** Explain the reason for the organization through product choices and facts rather than a decorative culture gallery.

### Customer proof library

1. **Framing** — Left-aligned category and display promise.
2. **Proof collection** — Three-column story grid mixing films, identity graphics and interface imagery.
3. **Ongoing relationship** — Two-column ruled newsletter band with email field and black subscribe action.
4. **Ending** — Black site map.

**Transfer:** Let useful outcome headlines and varied but consistently framed media carry a long collection.

### Searchable provider or integration ecosystem

1. **Orientation** — Centered promise and brief taxonomy summary.
2. **Featured proof** — Edge-clipped rail of near-square streaked photographic cards.
3. **Discovery** — Persistent search and category rail beside repeated two-column provider groups.
4. **Participation** — Large centered request form.
5. **Ending** — Black site map.

**Transfer:** Adapt the layout to a real taxonomy without carrying directory density into an ordinary landing page.

## Writing

Assured, practical and business-facing. It makes technical infrastructure understandable through outcomes and precise mechanisms rather than hype or playful metaphors.

**Do not copy:** Do not reuse Tempo's name, wordmarks, partner identities, product names, customer claims, quotations, performance figures or financial promises. Source examples illustrate voice only; replace them with authorized, supportable facts.

- **Addressing the reader:** Headlines address the reader implicitly through imperative verbs and occasionally 'your'; paragraphs name the product directly and explain what it enables. 'Our team' is reserved for human conversion actions.
- **Rhythm:** Short sentence-case promises, usually 5–9 words; one or two direct support sentences. Longer technical answers remain factual and sequential. No exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Start with an action and an outcome; make the infrastructure feel useful rather than abstract. | 5–9 words | “Move money at internet speed”<br>“Open your business to AI agents” |
| Supporting line | Name the product category and its intended use in one concrete sentence. | 10–25 words | “[Brand] is a purpose-built blockchain for stablecoin financial products.” |
| Section heading | Verb-led benefit that introduces a functional family. | 5–10 words | “Build on [Brand]’s powerful financial primitives”<br>“Give agents a way to buy from your business” |
| Action | Plain verb and a specific next step; assisted routes sound human. | 2–5 words | “Talk with our team”<br>“Start building” |
| Customer outcome | Name the actor and a practical change, optionally supported by a meaningful number. | 8–16 words | “Coastal is turning cross-border settlement from days into minutes” |
| Category label | Short neutral taxonomy, not a promotional slogan. | 1–3 words | “Built for scale”<br>“In practice” |

**Words and phrasing to use:** build; enable; purpose-built; in practice; access; connect; global; production; designed for; predictable

**Avoid:** revolutionary; game-changing; magical; unleash; moonshot; supercharge; world's best; effortlessly

**Rules:**

- Explain an acronym when it first becomes necessary, then use it consistently.
- Describe the capability and its user consequence together.
- Use concrete categories and constraints instead of vague superiority.
- Give metrics a descriptive caption and contextual units.
- Prefer a clear action label over a generic 'Learn more' when the destination is known.

## Do's and Don'ts

### Do

- Keep the 600px opening measure and two-line compact display rhythm.
- Keep chapter headings at 36px, weight 500 and -0.02em tracking.
- Give default three-column content grids 24px gutters.
- Use 12px text-pair spacing inside larger 32px or 48px groups.
- Preserve both faint route graphics and directionally streaked photographic atmosphere.
- Use 29.8px ordinary panel corners and 59.5px broad conversion corners.
- Leave 100px or 160px before major reading chapters rather than packing them together.
- Keep quantitative proof unboxed, with 36px values and 14px captions.

### Don't

- Do not use teal as the main button color; conversion actions are black.
- Do not add floating drop shadows to white panels; separation comes from pale ground.
- Do not make body copy 18px regular by default; the normal recipe is 16px/22px medium.
- Do not replace the 10px tracked uppercase index labels with colorful badges.
- Do not use the light serif for body text, navigation or every section heading.
- Do not put rainbow gradient fills behind technical line diagrams.
- Do not replace the black site map with a giant wordmark or oversized final slogan.
- Do not add hard outlines to every card or turn neutral media stages into glass panels.

## Motion and responsive

### Motion

**Observed:**

- Navigation and text links declare color transitions of 0.32s ease-out; form fields declare background-color transitions of 0.16s ease.
- The opening canvas declares opacity 0.15s ease-out.
- The capability presentation is sticky through a long scroll chapter, changing its active description and UI scene.
- Technical demonstrations declare 8s linear looping sequences affecting packet movement, opacity and blur; these are illustration behavior rather than page-wide reveal rules.

**Transfer:**

- Keep chapter-stage dimensions stable while selector state and media change.
- Use subtle directional packets or line motion to reinforce system flow; retain a complete static diagram when animation is absent.
- Use the known color and field transitions without adding unrelated spring effects.

**Unknown:**

- Exact route-canopy choreography, scroll interpolation and mobile motion behavior are not established.

### Responsive

**Observed:**

- The display size uses clamp(36px, 1.6667vw + 29.3px, 72px).
- Declared layout breakpoints include 600px, 768px, 834px, 1000px, 1024px, 1280px, 1512px and 1600px; technical templates also declare 359px, 640px and 767px.

**Transfer:**

- On narrow layouts, retain a faint route canopy above the compact promise rather than shrinking a full desktop scene into unreadability.
- Stack the text-and-stage split with explanation first and keep the product object legible; let the story rail retain horizontal continuation.
- Reduce grid columns and conversion pairs to a vertical reading sequence; replace the directory rail with a compact category control before results.

**Unknown:**

- Exact narrow-screen paddings, navigation replacement, card widths and breakpoint-specific rearrangements are not established; transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
