# Toggl — soft clockwork optimism

## Overview

A friendly, unusually colorful software style that pairs rounded grotesk headlines with practical, plainspoken explanations. Warm ivory and plum dominate, with sherbet pink and acidic lime cards, oversized numerals, and delicate technical linework. Layered interface scenes and softly blurred workplace photography make analytical products feel human; spacious chapters alternate with compact information grids.

### Essentials

- Soft, compact headline shapes carry serious promises: Aeoniksoft 75.6px/0.95 at weight 500 with -0.02em tracking; section leads use 61.2px/1 at weight 600.
- The opening is a luminous instrument, not a generic split hero: a centered 619px text column sits inside 1218px and 1047px clock rings, with pink ticks and two 353px interface panels beneath the actions.
- Actions are small capsules rather than rectangular slabs: the opening uses a 43px plum pill with 14.4px soft-sans text; statement calls use a 56px pink pill with 21.6px text.
- Color comes in alternating chapters: ivory and white remain the majority canvas, pink and lime fill whole proof cards, and dark olive supports luminous metrics. Plum, not black, anchors headings; hot pink is reserved for actions, ticks, and small emphases.
- Product explanations float on a soft stage: white interface fragments overlap on ivory-to-pink gradients, fine 0.5px rules provide structure, and atmospheric photographic bands interrupt the flat canvas. Without interface assets, use a credible simplified diagram with the same layered framing.
- Clockwork line art and buoyant proof are signature devices: repeat radial rectangular ticks and extended construction lines around a statement call, then contrast a 140.4px proof headline with staggered lime/pink metric cards and a dark panel carrying 133.2px numerals. Adapt the metric to a verified outcome rather than removing the device.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep action plum | `#37083e` | `--color-action-plum` | action, text, surface | Default opening button, announcement strip, and inverted cards. |
| Headline plum | `#4e0e58` | `--color-plum` | text, link | Core headline color and navigation text. |
| Olive ink | `#424a12` | `--color-olive-ink` | text | Text over lime surfaces and problem labels. |
| Aubergine night | `#18061b` | `--color-footer` | background | Footer canvas. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Statement violet | `#ae40c0` | `--color-display-violet` | text | Monumental proof lettering. |
| Technical lime | `#c8dd5f` | `--color-label-lime` | text | Widely tracked trust label. |
| Electric pink | `#ec84ff` | `--color-hot-pink` | action, accent, border | Conversion pills, radial ticks, and delicate accent outlines. |
| Card violet | `#8b299b` | `--color-violet` | text | Pink-card metrics and feature subheads. |
| Luminous metric | `#d6e878` | `--color-metric` | text | Giant numerals on dark olive. |
| Chartreuse tile | `#cede71` | `--color-lime-strong` | surface, accent, border | Icon tiles and inset checklist panels. |
| Light olive badge | `#e4efa9` | `--color-badge` | surface | Trust badges. |
| Sherbet lime | `#e9f4b3` | `--color-lime` | surface, text | Proof cards and light text in olive chapters. |
| Clock edge glow | `#f4d3f5` | `--color-clock-glow` | background | Pink illumination at the sides of the opening clock. |
| Sherbet pink | `#fae0fe` | `--color-pink` | surface, text | Proof cards and signup panels; reversed text on plum. |
| Pink hover wash | `#fdf0ff` | `--color-hover-wash` | surface | Hover fill of white provider and download pills; pale recommended comparison column. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lime edge | `#dae1b0` | `--color-lime-edge` | border | Fine construction lines on lime-backed audience cards. |
| Muted sage | `#a9ae8f` | `--color-olive-muted` | text | Secondary text within dark trust panels. |
| Deep olive | `#20240f` | `--color-olive-mid` | surface | Adjacent ROI panel and dark checklist insets. |
| Warm charcoal | `#363137` | `--color-ink` | text | Body copy and plain text links. |
| Muted gray | `#9d9898` | `--color-muted` | text | Attributions and secondary metadata. |
| Timeline gray | `#cbc9bf` | `--color-strong-rule` | border | Stronger timeline and question separators. |
| Lilac edge | `#ecdcee` | `--color-pink-edge` | border | Dividers inside pink gradient product stages. |
| Warm stone | `#e7e5da` | `--color-stone` | background, border | Secondary opening backgrounds and default 0.5px grid rules. |
| Warm reversed white | `#f4f2ec` | `--color-soft-white` | text | Metric explanation on dark panels. |
| Warm ivory | `#f8f7f1` | `--color-canvas` | background | Default canvas and warm endpoints of gradients. |
| Paper white | `#ffffff` | `--color-white` | surface, text | Navigation islands, interface backing, and bright proof chapters; reversed headings over photography. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| joined trust and sales panels | Olive night | `#151808` | `--color-olive-dark` | surface | Opaque trust panel in joined proof bands. |

## Typography

- **Aeonik** — Body, navigation, labels, and large numerical proof. Clean geometric grotesk, open and pragmatic rather than mechanical. If unavailable, use **DM Sans**. Use 400–600; preserve the airy paragraph leading. Font stack: "Aeonik", "DM Sans", Arial, sans-serif.
- **Aeoniksoft** — Headlines, card titles, button text, and footer links. Rounded terminals and soft geometric joins give compact headlines a conversational quality. If unavailable, use **Nunito Sans**. Use 500–700 with tight display tracking. Font stack: "Aeoniksoft", "Nunito Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-display | Aeoniksoft | 500 | 140.4px | 0.95 | -0.02em | Monumental two-line proof statement. |
| trust-metric | Aeonik | 600 | 133.2px | 1 | -0.0303em | Singular metric on dark trust panel. |
| display | Aeoniksoft | 500 | 75.6px | 0.95 | -0.02em | Main centered opening and major capability chapter titles. |
| card-metric | Aeoniksoft | 600 | 75.6px | 0.95 | -0.02em | Outcome numerals on colored proof cards. |
| heading-lg | Aeoniksoft | 600 | 61.2px | 1 | -0.01em | Default section heading. |
| heading-light | Aeoniksoft | 500 | 61.2px | 1 | -0.01em | Centered heading over atmospheric bands. |
| heading | Aeoniksoft | 500 | 41.4px | 1 | normal | Product-stage headings, questions, closing statements, and compact page openings. |
| subheading | Aeoniksoft | 500 | 25.2px | 1.15 | 0.01em | Feature tabs, platform tiles, and short testimonial text. |
| card-title | Aeoniksoft | 500 | 21.6px | 1.15 | 0.01em | Capability grid titles. |
| lead | Aeonik | 400 | 21.6px | 1.3 | 0.01em | Opening supporting line and major product explanations. |
| button-lg | Aeoniksoft | 500 | 21.6px | 1 | -0.01em | Large conversion pill. |
| body | Aeonik | 400 | 18px | 1.5 | 0.01em | Paragraphs in cards and capability lists. |
| badge | Aeonik | 600 | 16.2px | 1.333 | normal | Trust badge text. |
| small | Aeonik | 500 | 14.4px | 1.5 | 0.01em | Navigation, checklist items, and short section support. |
| button | Aeoniksoft | 500 | 14.4px | 1 | -0.01em | Default pill and arrow-link labels. |
| footer-link | Aeoniksoft | 400 | 14.4px | 1.5 | 0.01em, capitalize | Footer directory links. |
| eyebrow | Aeonik | 600 | 12.6px | 1.3 | 0.01em | Small section marker above problem statement; use capital lettering. |
| provider | Aeonik | 500 | 12.6px | 1.3 | 0.01em | Download and provider pill labels. |
| trust-label | Aeonik | 600 | 11.9px | 1.697 | 0.152em, uppercase | Technical label at top of metric panel. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability catalog pages | catalog-opening | Aeoniksoft | 700 | 61.2px | 1 | -0.01em | Strong split opening for a capability catalog. |
| objection-handling sections | faq-question | Aeoniksoft | 500 | 21.6px | 1 | 0.01em | Accordion question. |
| objection-handling sections | faq-answer | Aeonik | 400 | 16.2px | 1.5 | -0.01em | Accordion expanded answer. |

**Notes:**

- Display tracking tightens to -0.02em while most paragraph and small-label text uses +0.01em; button text reverses this to -0.01em.
- Rounded headings remain compact and sentence case. Reserve widely spaced capitals for the small technical trust label.
- The desktop sizing system is viewport-relative through a 1vw root. Preserve proportional relationships across the desktop range, then set readable narrow-screen sizes rather than shrinking the whole composition indefinitely.

## Layout

**Density:** Airy chapters with compact interior information: broad pauses separate demonstrations, while grid cells and pills are closely packed.

### Spacing

| Value | Use |
| --- | --- |
| 7.2px | Title-to-body and icon-to-label gaps. |
| 14.4px | Opening heading-to-support gap and small card padding. |
| 18px | Card grid gutter. |
| 21.6px | Button side padding and action-group gap. |
| 25.2px | Product stage inset. |
| 28.8px | Proof card inset. |
| 36px | Page side inset and heading-to-action separation. |
| 43.2px | Large card inset and icon-to-content spacing. |
| 57.6px | Tab-to-stage gap and signup panel inset. |
| 72px | Heading-to-grid gap; small section padding. |
| 108px | Capability chapter top spacing. |
| 129.6px | Broad chapter transitions. |
| 288px | Top space within the illustrated statement call. |

### Containers and grids

- **container**: max width 1800px · side padding 36px. Centered content wrapper; 1368px usable width at a 1440px viewport.
- **opening-copy**: max width 619px. Centered headline and supporting copy, approximately half the viewport width.
- **capability-grid**: 4 columns · gap 0px. Shared-edge information cells; use three columns for service-heavy chapters.
- **audience-grid**: 2 columns · gap 18px. Equal-width large cards; one dark metric panel can occupy a peer cell.
- **proof-grid**: 3 columns · gap 18px. Three 444px outcome cards with deliberately offset vertical positions.
- **footer-directory**: 5 columns · gap 28.8px. Five spacious text directories above a low legal and social row.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pill | 450px |
| large-card | 14.4px |
| proof-card | 10.8px |
| inset-panel | 7.2px |
| clock | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| navigation | `0px 0px 24px 0px rgba(0, 0, 0, 0.06)` | White floating navigation islands. |
| timeline-card | `0px 1.8px 28.8px 0px rgba(236, 132, 255, 0.08)` | Highlighted interface fragment in a timeline scene. |

### Surfaces

#### Ivory canvas · level 0

**Use:** Default page background.

**CSS:** `background: #f8f7f1`

#### White proof chapter · level 0

**Use:** Large social-proof and platform-board sections.

**CSS:** `background: #ffffff`

#### Pink product stage · level 1

**Use:** Large product explanation panel.

**CSS:** `background: linear-gradient(135deg, #f8f7f1, #fae0fe); border-radius: 7.2px; padding: 25.2px`

**Observed:** A fine ruled inner frame divides explanation from a layered product scene.

**Transfer:** Use the gradient as a pale backing, not as a multicolor rainbow.

#### Lime card material · level 1

**Use:** Audience cards over photographic bands.

**CSS:** `background: #e9f4b3; border-radius: 14.4px`

**Observed:** A creamy, softly mottled lime wash with faint inset construction lines; it reads as a lit paper panel rather than glass.

**Transfer:** Layer broad low-opacity white radial gradients over lime, then draw thin lime-edge lines inset 21.6px.

#### Dark trust material · level 1

**Use:** Standalone metric card over an atmospheric scene.

**CSS:** `background: rgba(35, 40, 22, 0.8); border-radius: 14.4px; padding: 43.2px; overflow: hidden`

**Observed:** Dark olive translucency supports lime numerals and faint off-center concentric circles. Joined sales panels use opaque olive night with only their outer corners rounded.

**Transfer:** Retain the luminous metric contrast and quiet circular linework.

#### Footer night · level 0

**Use:** Closing directory.

**CSS:** `background: #18061b; padding-bottom: 18px`

**Observed:** Subtle diffuse violet light sits behind the left half, never behind every link.

**Transfer:** Use a restrained transparent violet radial wash, with links remaining legible.

#### Stone opening · level 0

**Only for:** pricing and split catalog openings

**Use:** Muted backing for more utilitarian page types.

**CSS:** `background: #e7e5da`

## Components

### Floating navigation

**Use:** Persistent global orientation.

**CSS:** `display: flex; align-items: center; gap: 43.2px; padding: 7.2px 28.8px; background: #ffffff; border-radius: 450px; box-shadow: 0px 0px 24px 0px rgba(0, 0, 0, 0.06)`

**Text style:** `small` — Aeonik 500 · 14.4px/1.5 · tracking 0.01em

**Observed:** Two separate islands: logo and main links on the left, demo/login and dark action on the right. A slim plum existing-user announcement sits above them.

### Primary button

**Use:** Default opening conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #37083e; color: #fae0fe; border-radius: 450px; padding: 14.4px 21.6px; position: relative; overflow: hidden`

**Text style:** `button` — Aeoniksoft 500 · 14.4px/1 · tracking -0.01em

**Observed:** Text remains above a circular pink pseudo-layer used for the color reversal.

**States:** Declared: hover color #37083e; focus-visible solid outline 1.8px; active outline 0px.

### Statement button

**Use:** High-emphasis closing or signup action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #ec84ff; color: #37083e; border-radius: 450px; padding: 16.2px 28.8px 18px; overflow: hidden`

**Text style:** `button-lg` — Aeoniksoft 500 · 21.6px/1 · tracking -0.01em

**Observed:** A dark circular pseudo-layer reverses the bright fill. Compact pink variants use the default button recipe and 12.6px top, 14.4px bottom, 21.6px side padding.

**States:** Declared: hover color #ec84ff and transform scale(1.2); focus-visible solid outline 1.8px; active outline 0px.

### Arrow link

**Use:** Low-pressure secondary actions beside pills or at the bottom of cards.

**CSS:** `display: flex; align-items: center; gap: 5.4px; color: #363137`

**Text style:** `button` — Aeoniksoft 500 · 14.4px/1 · tracking -0.01em

**Observed:** Small right arrow follows a short label; no filled container. On lime cards the label takes olive ink.

**States:** Declared: hover color #37083e; focus-visible solid outline 1.8px; active outline 0px.

### Capability cell

**Use:** Practical feature and service summaries.

**CSS:** `display: flex; flex-direction: column; gap: 43.2px; padding: 14.4px 36px 14.4px 14.4px; border-right: 0.5px solid #e7e5da; border-bottom: 0.5px solid #e7e5da`

**Text style:** `card-title` — Aeoniksoft 500 · 21.6px/1.15 · tracking 0.01em

**Observed:** Lime icon tile first, then title and paragraph separated by 7.2px, then an Arrow link. The grid supplies the top and left edges; cells do not become separate raised cards.

### Outcome card

**Use:** Quantified customer proof.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #e9f4b3; border-radius: 10.8px; padding: 28.8px`

**Text style:** `card-metric` — Aeoniksoft 600 · 75.6px/0.95 · tracking -0.02em

**Observed:** Small customer mark at top, very large metric near the bottom, then one compact explanatory line. A pink variant pairs violet text with the pink fill; three cards are staggered rather than strictly level.

**Transfer:** Use one verified outcome per card, with a useful unit and a compact description.

### Trust badge

**Use:** Short verifiable assurances beneath a large metric.

**CSS:** `background: #e4efa9; color: #363137; padding: 10.8px 21.6px; border-radius: 9999px`

**Text style:** `badge` — Aeonik 600 · 16.2px/1.333

**Observed:** Badges wrap into two rows below the explanation, rather than becoming a full-width badge cloud.

### Provider pill

**Use:** Download platforms and alternate signup methods.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 7.2px; padding: 9px 14.4px; background: #ffffff; color: #363137; border-radius: 450px`

**Text style:** `provider` — Aeonik 500 · 12.6px/1.3 · tracking 0.01em

**Observed:** Small platform mark precedes a compact label; multiple options sit adjacent.

**States:** Declared: hover background #fdf0ff; focus-visible solid outline 1.8px; active outline 0px.

### Footer link

**Use:** Dense but calm directory navigation.

**CSS:** `color: #fae0fe`

**Text style:** `footer-link` — Aeoniksoft 400 · 14.4px/1.5 · tracking 0.01em · capitalize

**Observed:** Grouped under small column labels. The directory begins well below a compact pale wordmark; legal links sit at bottom left and a plum social capsule at bottom right.

**States:** Declared: hover outline 0px; focus-visible solid outline 1.8px; active outline 0px.

### Signup panel

**Only for:** signup-focused conversion sections

**Use:** Conversion over an atmospheric workplace image.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 57.6px; padding: 57.6px 57.6px 21.6px; background: #fae0fe; border-radius: 14.4px`

**Text style:** `heading` — Aeoniksoft 500 · 41.4px/1

**Observed:** Centered 585px panel with a two-line heading, Statement button, alternate Provider pills, and small consent text at the bottom.

### Active feature tab

**Only for:** capability catalog pages

**Use:** Selected explanation in a detailed capability chapter.

**CSS:** `display: flex; flex-direction: column; padding: 21.6px 25.2px; background: #ffffff; border-radius: 14.4px`

**Text style:** `subheading` — Aeoniksoft 500 · 25.2px/1.15 · tracking 0.01em

**Observed:** Selected title and explanatory paragraph share the white card; inactive titles remain unboxed below it. The right side holds a substantially larger product scene.

### Demo field

**Only for:** sales inquiry forms

**Use:** Sales inquiry form.

**CSS:** `background: #ffffff; border: 0.5px solid #e7e5da; border-radius: 7.2px; padding: 10px`

**Observed:** White fields on ivory sit in a two-column form, with full-width email, selects, and message rows; labels sit above controls. The submit action spans the form width.

## Imagery and graphics

### Clock and construction linework

**Use:** Signature opening stage and illustrated statement calls.

**Observed:** Huge fine circles pass beyond the viewport, with rectangular pink hour ticks and pale side glows. The closing variation exposes rectangular construction bounds around a partial clock, making the linework feel like a friendly technical drawing.

**Transfer:** Keep the circular instrument metaphor as an abstract frame for a new product's promise, not a literal timer interface.

**Build:** Use centered SVG circles 1218px and 1047px in diameter, 1px strokes rgba(236,132,255,0.2) and rgba(236,132,255,0.4). Clip them to the opening stage. Place short pink rectangles radially at hour angles, alternating solid and translucent marks. Inside the smaller circle, place a horizontal gradient from clock-glow to transparent at 10%, transparent through 90%, and back to clock-glow. For statement calls, omit the glow, retain upper clock ticks and extend their faint pink rectangular alignment bounds across the section.

### Layered interface scenes

**Use:** Opening proof and capability explanations.

**Observed:** Crisp white dashboards, reports, calendars, and small popovers overlap without heavy device chrome. Plum rails and pink/lime highlights unify them. Opening panels form a restrained centered pair; deep chapters let the scene occupy half or more of the content width.

**Transfer:** Use the new product's most revealing view, with one or two extracted detail cards. Minimum version: one credible white panel plus a smaller overlapping outcome or annotation, with fine warm-gray edges and restrained shadows.

### Atmospheric workplace bands

**Use:** Immersive product-story and audience chapters.

**Observed:** Full-width warm brown and taupe workplace imagery is heavily defocused; darkened regions support white headings. Pale product panels remain sharp in front. Fine vertical construction lines extend through the photograph.

**Transfer:** Use a real work setting related to the new product, blur until people and desks become soft tonal masses, and keep all detailed information on the foreground panels.

**Build:** Place a cover photograph in an oversized background layer, apply blur, then a translucent dark overlay. Add a sparse SVG grid of 0.5px ivory lines at low alpha. Keep the blur amount subordinate to the visible effect: broad warm forms, no recognizable tiny distractions.

### Overhead signup photograph

**Only for:** signup-focused conversion sections

**Use:** Final conversion behind Signup panel.

**Observed:** A high overhead view of a shared workplace shows tables, people, plants, and a stone floor. The photograph is dimmed, with an aubergine fade along the bottom leading into the footer.

**Transfer:** Use a similarly spacious overhead scene with human activity; preserve a quiet central area behind the opaque pink card.

### Radial color sculpture

**Only for:** split catalog, enterprise, and company openings

**Use:** Hero illustration in the right half.

**Observed:** Eight softly rounded bars radiate around a dark circular center bearing a small grid symbol. Lime and magenta blend across the bars with blurred trailing edges; backing varies from plain stone to a dark olive rounded rectangle or lime panel.

**Transfer:** Use the new product's simple symbol in a radial arrangement; retain the soft lime/pink volume rather than adding realistic metallic 3D.

**Build:** Arrange eight rounded rectangles at 45-degree intervals around a circle, leaving a clear central hub. Fill bars with alternating lime-to-pink gradients and overlay blurred low-alpha duplicates slightly offset from their edges. Use a dark olive center with a pale minimal symbol. Minimum version is flat SVG bars with gradient fills and soft offset blur.

### Human company imagery

**Only for:** company and culture stories

**Use:** History collage and trust narrative.

**Observed:** Candid team selfies, meals, outdoor gatherings, and work sessions retain natural color and imperfect framing. A masonry-like collage mixes portrait and landscape images with small rounded corners; a dark editorial section pairs a close work photograph with a firm statement.

**Transfer:** Use genuine informal photography, varying aspect ratios and avoiding polished identical corporate headshots.

### Icons

**Observed:** Small plum or olive utility glyphs use simple solid or light outline geometry. Capability icons sit in 43px lime squares with 7.2px corners; inline arrows are about 12px, navigation chevrons 14px, and platform marks 18px.

**Transfer:** Choose a consistent uncomplicated utility set; retain the lime tile and generous gap below it instead of turning every icon into a multicolor illustration.

## Section recipes

How recurring sections are built.

### First screen: Luminous clock opening

**Observed:** An ivory first screen begins under a slim plum announcement and two Floating navigation islands. A centered headline occupies about 619px, set on two compact lines in plum with the display recipe; the support line follows after 14.4px. After 36px comes a dark Primary button beside a small play-led tour link. Behind all text, enormous clock rings and pink edge glows frame the central space. A 50.4px gap leads to two white 353px by 229px interface panels side by side. Within the first 900px the entire headline, support, actions, product panels, and a broad row of review emblems are visible; the next narrative chapter begins below. The rings extend outside the screen while the headline stays clear of the ticks.

**Transfer:** Keep this centered illuminated stage as the default landing-page opening. Replace the interface pair with two meaningful product views, or a simple primary diagram and its result. Pricing opens more compactly with a centered 41.4px promise over stone and immediate plan columns; sales and catalog pages use a 61.2px left headline beside Radial color sculpture; company pages use a ruled split editorial composition.

**Avoid:** Do not substitute a huge isolated laptop mockup, fill the opening with lime, or place the clock in front of the headline.

**Text style:** `display` — Aeoniksoft 500 · 75.6px/0.95 · tracking -0.02em

### Problem marquee

**Observed:** A small centered eyebrow precedes a compact 41.4px problem statement. Floating white icon discs surround it; a horizontal row of lime pills names recognizable frustrations, with faded edges.

**Transfer:** Identify a concrete gap between intention and reality; use short pains in the pills, not a list of product features.

### Heading and ruled capability grid

**Observed:** A left-aligned heading-lg sits above a short small-text support block; 72px separates the heading area from a shared-edge Capability cell grid. Typical layouts use four columns by two rows or three service columns.

**Transfer:** Give each cell one behavior or benefit. The icons, short titles, paragraphs, and bottom links provide rhythm without independent card shadows.

**Text style:** `heading-lg` — Aeoniksoft 600 · 61.2px/1 · tracking -0.01em

### Immersive product chapter

**Observed:** Atmospheric workplace bands carry a centered pale heading, a translucent tab strip, and Pink product stage. The stage divides into two equal areas: a ruled heading and bullet explanation on the left, a large Layered interface scene on the right. Small case-study strips support the explanation.

**Transfer:** Let a small set of tasks control the tabs and pair each with a useful view and one outcome.

**Text style:** `heading` — Aeoniksoft 500 · 41.4px/1

### Monumental proof

**Observed:** A white chapter uses proof-display violet lettering across two lines, a smaller olive explanatory heading, a row of understated customer marks, and three staggered Outcome cards. Lime, pink, lime alternation keeps the giant numbers playful rather than corporate.

**Transfer:** Use a short two-part proof phrase and verified outcomes. Keep the letter scale distinct from the numerical cards.

**Text style:** `proof-display` — Aeoniksoft 500 · 140.4px/0.95 · tracking -0.02em

### Audience and trust pairing

**Observed:** A photographic band holds a centered heading-light and support line, then a two-column grid of Lime card material audience panels and Dark trust material. Each audience card contains a short title, paragraph, and inset checklist. The trust panel contrasts its small top label with an enormous bottom-heavy metric, explanation, and Trust badges.

**Transfer:** Segment by meaningful differences in use or scale, then introduce one verifiable reliability or quality metric in a peer panel.

**Text style:** `trust-metric` — Aeonik 600 · 133.2px/1 · tracking -0.0303em

### Clockwork statement call

**Observed:** Centered 41.4px plum text sits inside exposed clock construction lines and pink ticks. A large 288px top interval makes the illustration breathe. A short reassurance and Statement button sit below, sometimes followed by an Arrow link.

**Transfer:** Use a short question that resolves the reader's last hesitation. The same illustrated call can mark a transition or close a narrative.

**Text style:** `heading` — Aeoniksoft 500 · 41.4px/1

### Directory ending

**Observed:** Footer night holds a pale compact wordmark, five directory columns separated by 28.8px gaps, and a low row of legal links and social icons. The default narrative arrives here after Clockwork statement call. Conversion-heavy pages instead use Signup panel on Overhead signup photograph; company stories can place a striped two-column facts table between their illustrated call and directory.

**Transfer:** Choose the ending appropriate to the page's job, but keep the final dark directory visually distinct from the preceding light narrative.

**Text style:** `footer-link` — Aeoniksoft 400 · 14.4px/1.5 · tracking 0.01em · capitalize

### Capability catalog chapter

**Observed:** A narrow icon rail sits to the left of a 75.6px capability heading. Below, a 450px explanation column holds Active feature tab and unboxed sibling titles; a roughly 763px product scene dominates the right. Ruled supplementary rows sit under the tabs.

**Transfer:** Group detailed capabilities into task-based chapters and keep only the selected explanation in a white card.

**Text style:** `display` — Aeoniksoft 500 · 75.6px/0.95 · tracking -0.02em

### Commercial comparison

**Observed:** Four equal 342px plan columns share 0.5px borders, compact labels, prominent prices, full-width pills, and long feature lists. The recommended column is pink with a dark action. A detailed comparison uses compact roughly 42px rows, a pale pink column wash, checkmarks, and category rules.

**Transfer:** Preserve comparison alignment and the single highlighted plan; add-ons use larger stone panels with offset product detail art.

### Question and answer split

**Observed:** A 61.2px olive heading anchors the left; a 726px question list occupies the right. Small pale sequence labels resemble times, a chevron sits at each far edge, and gray rules separate entries. Expanded copy uses the faq-answer recipe and is indented 63px within the list.

**Transfer:** Answer practical objections directly; use the numbered rhythm and one visible expanded answer rather than a wall of equal paragraphs.

**Text style:** `faq-question` — Aeoniksoft 500 · 21.6px/1 · tracking 0.01em

## Page flow

**Storyline:** Promise → recognizable friction → product explanation → useful capabilities → quantified and human proof → right-fit guidance → reassurance and action → dark directory.

### Broad product landing page

1. **Promise** — Centered luminous clock opening with product pair and review emblems.
2. **Problem and solution** — Problem marquee, oversized solution statement, and a timeline-like interface story.
3. **Capability demonstration** — Atmospheric tabbed product stage followed by ruled capability grid.
4. **Proof and fit** — Audience cards, monumental results, and dark trust metric.
5. **Closing action** — Illustrated clock statement call leads into dark directory.

**Transfer:** Adapt the narrative breadth to one new product; preserve the contrast between expansive scenes and compact practical grids.

### Commercial decision page

1. **Offer framing** — Compact centered stone opening and billing switch above four plan columns.
2. **Pricing** — Plan columns, two add-on panels, and illustrated trial reassurance.
3. **Proof** — Dark olive benefit and trust band.
4. **Comparison and objections** — Long aligned feature matrix, then split FAQ.
5. **Closing action** — Platform board, photographic signup panel, and dark directory.

**Transfer:** Let readers compare first, then explain value and remove risk; maintain a single pink recommendation column.

### High-consideration sales page

1. **Promise** — Stone split opening with a checklist and radial sculpture, followed by customer marks.
2. **Quantified proof** — Staggered case-study tiles and joined ROI/trust band.
3. **Implementation confidence** — Onboarding grid and human testimonial panels.
4. **Capability chapters** — Alternating pink and lime product stages, then customization and security grids.
5. **Conversion and reassurance** — Split demo form, FAQ, photographic signup panel, and dark directory.

**Transfer:** Use practical implementation promises and credible human proof before a detailed inquiry form.

### Capability catalog

1. **Promise** — Split illustration-led opening.
2. **Product demonstration** — Repeated task chapters with icon rail, active explanation card, and large layered interface scenes; a dark conversion interlude breaks the length.
3. **Social proof** — A tilted horizontal row of pink and lime review cards.
4. **Access and scale** — Platform board and large-team sales/trust pair.
5. **Closing action** — Photographic signup panel and dark directory.

**Transfer:** Organize by user outcomes rather than mirroring an application menu; retain major chapter scale and active-card hierarchy.

### Company story and credibility

1. **Identity** — Ruled editorial split opening with radial sculpture and review emblems.
2. **Evolution** — Colored product-family mosaic and a large statement about changing customer needs.
3. **Principles and history** — Lime/dark trust pair, informal photo collage, and dark ethical statement with work photograph.
4. **Culture** — Ruled principles grid and staggered values tiles.
5. **Closing action and facts** — Illustrated recruiting call, alternating pale-lime/white facts table, then dark directory.

**Transfer:** Use real history, operating principles, and human imagery; the company variant is more editorial and less conversion-driven.

## Writing

Warm, direct, and grounded in everyday work. Confidence comes from specific product behavior and recognizable frustrations, with occasional breezy questions and emphatic short statements.

**Do not copy:** Do not reuse Toggl names, wordmarks, customer logos, proprietary artwork, testimonials, customer counts, ratings, performance claims, certification claims, or commercial terms. Replace all with the new product's own verified material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to 'you' and 'your team'; use 'we' for intent and commitments, and the product name for concrete capabilities.
- **Rhythm:** Headlines are compact sentence-case promises, often 4–12 words. Supporting text is usually one or two plain sentences; longer explanations mix short declarative lines with specific examples. Exclamation marks appear in friendly conversion copy, not every headline.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product category and a reason to trust it. | 5–10 words | “The time tracker millions trust” |
| Supporting line | State who benefits, what they receive, and what it helps them do. | 15–25 words | “[Brand] gives teams the time data they need for better capacity, profitability, and project planning.” |
| Problem | Concrete friction, not abstract market disruption. | 4–12 words | “Invisible capacity, until burnout”<br>“Know what saying yes actually costs” |
| Action | Verb plus immediate next step; name low friction when true. | 2–6 words | “Start tracking for free”<br>“Speak to Sales” |
| Closing question | Ask about the remaining practical hesitation in conversational language. | 7–12 words | “Want to get team buy-in without the fuss?” |
| Principle | Short contrast followed by a firm operational commitment. | 3–12 words per sentence | “Complexity isn't sophistication”<br>“No screenshots. No keystroke logging. No webcam tracking.” |

**Words and phrasing to use:** your team; actually; without the fuss; in one place; plan with confidence; not guesswork; built for; works together; no learning curve

**Avoid:** revolutionary ecosystem; unleash synergies; world-class disruption; frictionless paradigm; crush your workforce

**Rules:**

- Pair a benefit with the behavior that makes it possible.
- Treat reader objections as reasonable: explain choices and limits plainly.
- Use contrast sparingly: not an afterthought, not guesswork, not another spreadsheet.
- Keep reassurance near conversion, especially signup friction and next-step expectations.

## Do's and Don'ts

### Do

- Keep opening headlines at 75.6px/0.95 with -0.02em tracking and medium soft-sans weight.
- Use 36px desktop side insets and 18px large-card gutters.
- Pair pink panels with violet or plum text, lime panels with olive text.
- Use shared 0.5px rules for capability grids instead of floating every item.
- Give major product stages a 25.2px outer inset and a pale directional gradient.
- Keep outcome-card logos small enough that 75.6px metrics remain dominant.
- Repeat clock ticks and construction lines in a statement device beyond the opening.
- End with a distinct aubergine directory and a restrained pale link hierarchy.

### Don't

- Do not replace plum headlines with neutral black; it removes the soft color contrast.
- Do not give all cards the 450px action radius; content panels use 7.2px–14.4px corners.
- Do not turn the site into a full dark interface; dark olive is a proof or atmosphere contrast to the light majority.
- Do not apply strong generic drop shadows to all cards; only navigation and selected interface fragments float visibly.
- Do not replace 18px/1.5 body paragraphs with tight dashboard typography.
- Do not make every supporting line as wide as the 1368px content area; compact reading columns balance the giant scenes.
- Do not level all proof cards into an identical rigid row; their vertical offsets supply character.
- Do not use saturated pink as an uninterrupted page background; concentrate it in ticks, actions, and bounded panels.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color transitions of 0.333s cubic-bezier(0.48, 1, 0.52, 1); large action transforms declare 333ms cubic-bezier(0.48, 1.4, 0.52, 1).
- White platform pills declare background-color 0.2s. Feature tab panels declare opacity 0.333s cubic-bezier(0.48, 1, 0.52, 1).
- Problem pills declare a 30s linear infinite marquee. Circular pseudo-layers provide button color reversals.

**Transfer:**

- Keep color reversals and the slow problem ticker tied to the corresponding components; preserve the oversized clock as a stable compositional anchor.

**Unknown:**

- Scroll reveal timing, clock animation choreography, and card-flip triggers are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 479px, 767px, 768px, 991px, 992px, and 2000px; sales form CSS also includes 430px.
- Desktop root text sizing is 1vw, affecting rem-based dimensions.

**Transfer:**

- On narrow screens, stack paired product panels and large audience cards, keeping the clock rings oversized and clipped behind the headline.
- Collapse the floating navigation islands into a compact control rather than preserving five desktop links at unreadable sizes.
- Keep comparison columns aligned in a dedicated horizontal reading area; do not compress four plans into narrow prose columns.

**Unknown:**

- Exact mobile type sizes, menu behavior, grid collapse points, and narrow-screen artwork positions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
