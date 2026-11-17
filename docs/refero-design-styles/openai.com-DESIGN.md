# OpenAI — intelligence in living color

## Overview

An expansive, light marketing style that pairs a matter-of-fact grotesk with vivid islands of photography, atmospheric color and product imagery. White and pale gray carry the reading experience; black actions and an occasional cyan headline give it definition. It suits ambitious tools and platforms that need both human credibility and technical breadth, with sparse opening screens and denser editorial collections below.

### Essentials

- A two-part promise becomes a physical label: the default opening uses 64px medium type at -0.01em tracking, with the first phrase in cyan inside a white 13px-radius lozenge and the second phrase in black immediately below.
- Human proof forms a shallow stage rather than a logo strip alone: overlapping photographic cards with 8px white frames and 20.8px corners rise from the lower edge of the opening. Use real working scenes; when customer media is unavailable, stage original task photography or finished product outputs in the same frames.
- Actions are small, almost typographic objects: 14px/1 medium labels, 40px pill buttons and 20px horizontal padding. A black primary sits beside a bare chevron link or pale secondary; navigation uses 36px buttons.
- Color is contained, not a page-wide theme: the canvas stays white, the closing band uses a 4% black wash, and vivid hues occupy framed media. Pale blue atmosphere supports the opening and selected feature bands without tinting ordinary paragraphs.
- Content reads like an image-led publication: 24px gutters, square images with 6.1px corners, titles underneath at 18px/1.32 and metadata at 14px/1.4. Preserve this device even with few stories, using original abstract color art when no photograph is appropriate.
- The final invitation is a broad, unillustrated pause: 48px/1.16 centered medium type, 32px to actions and 120px vertical padding inside a pale band, followed by an airy five-column directory footer. Adapt the invitation to the new product rather than turning it into a dense sales panel.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Intelligence cyan | `#28b5f6` | `--color-headline-accent` | text, accent | The highlighted first phrase of the default opening; keep body text black. |
| Blue atmosphere | `#f3f9fe` | `--color-air` | background | Visible pale blue endpoint of a 20% pale-blue wash over white; supports selected product feature bands. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action, background | Main text, black primary actions and compact announcement bars. |
| Secondary gray | `#666666` | `--color-muted` | text | Secondary copy and dates, rendered as black at 60% over white. |
| Soft edge | `#e0e0e0` | `--color-edge` | border | One-pixel black-at-12% outlines on controls and media frames. |
| Warm photo backing | `#ece7df` | `--color-photo-backing` | surface | Warm backing beneath the framed proof photographs, not an ordinary section background. |
| Faint band edge | `#ebebeb` | `--color-band-edge` | border | Black-at-8% separator beneath pale blue feature bands. |
| Locale gray | `#f1f1f1` | `--color-locale` | surface, action | Language and region selector at the bottom of the footer. |
| Pale neutral wash | `#f5f5f5` | `--color-wash` | surface, background, action | Closing bands and secondary pills, using black at 4% over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, photographic frames and inverse action text; the fixed navigation uses white at 85% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| newsletter forms | Subdued control gray | `#8f8f8f` | `--color-subdued` | text | Low-emphasis subscription action, rendered as black at 44% over white. |

## Typography

- **OpenAI Sans** — All marketing headings, body text, navigation, captions and actions. Contemporary, open grotesk with a high x-height and rounded, unforced forms; medium weight carries most headings. OpenType features: "calt", "liga". If unavailable, use **Inter**. Use weights 400–600 and retain the role-specific tracking. Font stack: "OpenAI Sans", "Inter", "OpenAI Sans Variable Scripts", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display-accent | OpenAI Sans | 500 | 64px | 1 | -0.01em | First, cyan phrase of the default two-part opening. |
| display | OpenAI Sans | 500 | 64px | 0.98 | -0.01em | Black continuation of the default opening promise. |
| heading-lg | OpenAI Sans | 500 | 48px | 1.16 | -0.03em | Centered capability chapter headings and closing invitations. |
| heading | OpenAI Sans | 500 | 30px | 1.32 | -0.01em | Feature split headings, category introductions and statement sections. |
| section-label | OpenAI Sans | 500 | 22px | 1.26 | -0.01em | Editorial section labels and the expanded capability selector title. |
| card-title | OpenAI Sans | 500 | 18px | 1.32 | -0.01em | Article and destination titles below images. |
| body | OpenAI Sans | 400 | 17px | 1.647 | -0.01em | Supporting paragraphs and product benefits. |
| body-sm | OpenAI Sans | 400 | 14px | 1.64 | -0.01em | Capability details, form support and compact descriptive text. |
| meta | OpenAI Sans | 500 | 14px | 1.4 | normal | Category, date, reading time and compact catalog summaries. |
| action | OpenAI Sans | 500 | 14px | 1 | normal | Buttons, tabs and short standalone links. |
| navigation | OpenAI Sans | 500 | 13px | 1.514 | normal | Header navigation and footer directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial, category and company pages | editorial-display | OpenAI Sans | 500 | 64px | 1 | -0.03em | Centered black page title with a small category label and a paragraph beneath. |
| interactive product entry pages | prompt-heading | OpenAI Sans | 600 | 28px | 1.214 | 0.0107em | Short question above a functional prompt composer. |
| interactive product entry pages | prompt-example | OpenAI Sans | 400 | 16px | 1.5 | -0.01em | Single-line suggested task in the composer. |

**Notes:**

- Medium weight, not heavy bold, establishes the hierarchy. Most text uses -0.01em tracking; large chapter and editorial headings tighten to -0.03em, while compact actions and metadata stay at normal tracking.
- Keep the two opening phrases distinct: the accented phrase has a full 1 line height and the continuation uses 0.98. Balance each phrase rather than introducing uppercase or a serif contrast.
- Use sentence case throughout. Long centered support text occupies a narrower measure than its heading.

## Layout

**Density:** Airy at chapter scale, compact within navigation and editorial metadata; large pauses separate otherwise economical content.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Opening phrase separation, compact control groups and wrapped metadata row gaps. |
| 12px | Metadata column spacing and newsletter row spacing. |
| 16px | Image-to-title separation and short feature list spacing. |
| 20px | Horizontal button padding and space between paired actions. |
| 24px | Grid gutters and heading-to-support spacing. |
| 32px | Desktop side gutters, title-to-action spacing and section-label-to-grid spacing. |
| 40px | Footer subgroup separation and selected heading-to-media relationships. |
| 48px | Feature row gaps and footer top padding. |
| 64px | Wide-media breathing room after an editorial opening and partner-logo gutters. |
| 80px | Feature-band bottom padding and footer directory-to-bottom-row space. |
| 120px | Major chapter separation and closing-band vertical padding. |

### Containers and grids

- **page-container**: max width 1440px · side padding 32px. Centered desktop shell; content spans 1376px at the standard desktop width.
- **structural-grid**: 12 columns · gap 24px. Underlying alignment grid. Broad statements span eight central columns, wide media ten and full card collections twelve.
- **centered-copy**: max width 1000px. Upper bound for display text; actual centered support paragraphs are substantially narrower.
- **feature-pair**: 2 columns · gap 24px. Balanced text/media pair within a central 1132px region. The text itself is inset within its half rather than filling the entire column.
- **editorial-cards**: 3 columns · gap 24px. Three square-media stories, each about 443px wide.
- **catalog-cards**: 4 columns · gap 24px. Four square-media destinations, each 326px wide, with compact titles and descriptions.
- **footer-directory**: 5 columns · gap 24px. Five equal desktop columns with stacked link groups; a separate bottom utility row spans the shell.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media | 6.1px |
|  | actions | 40px |
|  | proof-photographs | 20.8px |
|  | headline-label | 13px |
|  | newsletter-input | 4px |
|  | segmented-control | 9999px (pill) |
| interactive product entry pages | prompt-composer | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| proof-photographs | `rgba(87, 87, 87, 0.14) 0px 0px 0px 0.5px, rgba(0, 0, 0, 0.09) 0px 19.2px 48px 0px` | White-framed overlapping photographs in the opening. |
| headline-label | `rgba(0, 0, 0, 0.05) 0px 10px 30px 0px` | Very light lift beneath the cyan headline lozenge. |

### Surfaces

#### Canvas · level 0

**Use:** Default white reading ground.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** The main field remains untextured and unboxed through most chapters.

**Transfer:** Let images supply color and density rather than alternating saturated section fills.

#### Closing wash · level 0

**Use:** The broad final invitation.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 6.1px`

**Observed:** Inset from the outer page edges and flat, without a raised-card shadow.

**Transfer:** Keep this a large pause containing a headline and one compact action group.

#### Blue feature atmosphere · level 0

**Use:** Selected product introduction bands.

**CSS:** `background: linear-gradient(rgba(227, 227, 227, 0) 0%, rgba(193, 227, 252, 0.2) 100%); border-bottom: 1px solid rgba(0, 0, 0, 0.08)`

**Observed:** Almost white at the top, very pale blue at the bottom. A similarly light blue atmosphere backs the default opening.

**Transfer:** Match the soft light rather than using a saturated blue canvas.

#### Headline lozenge · level 1

**Use:** The first phrase in the default opening.

**CSS:** `background-image: linear-gradient(#ffffff, #ffffff), linear-gradient(rgba(87, 87, 87, 0.6) 0%, rgba(87, 87, 87, 0.4) 100%); background-clip: padding-box, border-box; border: 0.5px solid transparent; border-radius: 13px; box-shadow: rgba(0, 0, 0, 0.05) 0px 10px 30px 0px; padding: 7.7px 20.5px 10.2px; color: #28b5f6`

**Observed:** A lightly outlined white label, closely fitted to a short phrase; it is not a filled accent badge.

**Transfer:** Put the distinctive benefit phrase in the label and its plain-language consequence below.

#### Media frame · level 1

**Use:** Wide product demonstrations that need a visible boundary.

**CSS:** `background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 6.1px; overflow: hidden`

**Observed:** Wide demonstrations use a subtle edge; ordinary photographic story images rely on their own contrast instead.

**Transfer:** Use an actual finished view or edited demonstration, not decorative app-window chrome.

## Components

### Navigation

**Use:** Persistent global orientation and conversion access.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; background: rgba(255, 255, 255, 0.85); z-index: 51`

**Text style:** `navigation` — OpenAI Sans 500 · 13px/1.514

**Observed:** Identity at left, a compact horizontal set of topic links, then search; two small pills align at the far right. General editorial navigation uses an opaque white ground. Header action height is 36px.

**Transfer:** Keep only the product's real top-level destinations, preserving the lightweight horizontal line.

### Primary button

**Use:** Default marketing conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 20px; border-radius: 40px; background: #000000; color: #ffffff; gap: 8px`

**Text style:** `action` — OpenAI Sans 500 · 14px/1

**Observed:** Content-sized rather than full-width; a small chevron or external arrow can follow the label. Header version is shorter.

**States:** Declared: hover background-color rgba(0, 0, 0, 0.8); focus-visible solid 1px outline in rgba(0, 0, 0, 0.44), offset 2px.

### Secondary button

**Use:** A lower-emphasis action or editorial destination.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 20px; border-radius: 40px; background: rgba(0, 0, 0, 0.04); color: #000000; gap: 4.2px`

**Text style:** `action` — OpenAI Sans 500 · 14px/1

**Observed:** Used alone in editorial closing bands or beside a black conversion action.

**States:** Declared: hover background-color rgba(0, 0, 0, 0.12); focus-visible solid 1px outline in rgba(0, 0, 0, 0.44), offset 2px.

### Editorial card

**Use:** Stories, updates and destinations beneath section labels.

**CSS:** `position: relative; border-radius: 6.1px; overflow: hidden`

**Text style:** `card-title` — OpenAI Sans 500 · 18px/1.32 · tracking -0.01em

**Observed:** Only the square image is clipped by the rounded wrapper; title and metadata sit outside it on the white canvas. Title follows after 16px. Three-column stories use 443px images; four-column destinations use 326px images. Metadata mixes black category text with gray dates and reading time.

**Transfer:** Keep the whole image visible as a strong thumbnail. Use a concrete outcome title and compact metadata, not a feature-icon card.

### Proof photograph

**Use:** Overlapping real-world proof stage in the default opening.

**CSS:** `background: #ece7df; border: 8px solid #ffffff; border-radius: 20.8px; box-shadow: rgba(87, 87, 87, 0.14) 0px 0px 0px 0.5px, rgba(0, 0, 0, 0.09) 0px 19.2px 48px 0px; overflow: hidden`

**Observed:** Five landscape photographs overlap across the width; the central card rises above its neighbors and side cards tilt gently and extend beyond the page. White customer marks overlay the scenes.

**Transfer:** Use authentic task scenes or product results. Keep the middle card strongest and allow the outer cards to be partially hidden.

### Product tabs

**Use:** Switching among related platform capabilities.

**CSS:** `display: flex; align-items: center; gap: 8px; padding: 4px; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 9999px`

**Text style:** `action` — OpenAI Sans 500 · 14px/1

**Observed:** A centered three-part outlined capsule. The selected inner pill uses a pale wash, 12px vertical and 16px horizontal padding, 44px height and a small leading icon. Unselected labels remain on white.

**States:** Declared: hover selected tab background-color rgba(0, 0, 0, 0.12); focus-visible solid 1px outline in rgba(0, 0, 0, 0.12), offset 2px.

### Capability accordion

**Use:** Browse several applications beside one large demonstration.

**CSS:** `display: flex; flex-direction: column; width: 326px`

**Text style:** `section-label` — OpenAI Sans 500 · 22px/1.26 · tracking -0.01em

**Observed:** The expanded item has a 60px heading row, body-sm detail and a short underlined link. Remaining 55px rows use body-sm labels and faint horizontal separators. The selector takes three grid columns and the demonstration nine.

**Transfer:** Use task families, not a long feature checklist. Expand one item and show its corresponding real demonstration.

### Newsletter field

**Use:** Low-pressure ongoing relationship after the closing invitation.

**CSS:** `display: flex; height: 40px; background: #ffffff; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 4px; overflow: hidden`

**Text style:** `body-sm` — OpenAI Sans 400 · 14px/1.64 · tracking -0.01em

**Observed:** A simple email field about 449px wide sits beside a bare Subscribe action. A two-column row puts a 22px heading and gray support copy on the left, with the form and small consent text on the right.

**Transfer:** Keep the form outside the pale invitation band on white; explain what the reader will receive.

### Footer directory

**Use:** Deep navigation and final utility row.

**CSS:** `display: flex; gap: 24px`

**Text style:** `navigation` — OpenAI Sans 500 · 13px/1.514

**Observed:** Five equal columns on white; subgroup labels are gray and links black. Subgroups separate by 40px. Directory starts with 48px top padding; an 80px pause leads to a row with small social marks left, copyright and privacy centered, and a 40px locale pill right.

**Transfer:** Preserve the directory's spare scale and generous group separation even if there are fewer destinations.

### Prompt composer

**Only for:** interactive product entry pages

**Use:** A functional task-first alternative to a conventional marketing opening.

**CSS:** `display: flex; flex-direction: column; max-width: 768px; height: 104px; padding: 16px 52px 16px 16px; background: #ffffff; border-radius: 24px; box-shadow: rgba(0, 0, 0, 0.04) 0px 3px 6px 0px, rgba(0, 0, 0, 0.04) 0px 4px 80px 8px, rgba(0, 0, 0, 0.62) 0px 0px 1px 0px`

**Text style:** `prompt-example` — OpenAI Sans 400 · 16px/1.5 · tracking -0.01em

**Observed:** A short question sits above the composer; a small circular send control anchors its lower right. Topic chips appear beneath. The surrounding opening is deliberately spacious.

**Transfer:** Use only where a visitor can actually submit a task; make the examples mundane and immediately useful.

### Topic chip

**Only for:** interactive product entry pages

**Use:** Alternative entry routes below the prompt composer.

**CSS:** `display: flex; align-items: center; height: 40px; padding: 0px 12px; border: 1px solid rgba(0, 0, 0, 0.12); border-radius: 9999px; box-shadow: rgba(0, 0, 0, 0.02) 0px 4px 6px 0px, rgba(0, 0, 0, 0.05) 0px 0px 2px 0px`

**Text style:** `action` — OpenAI Sans 500 · 14px/1

**Observed:** Small content-sized outlined pills form a centered wrapping group beneath the composer, with muted text and occasional external-link marks.

**States:** Declared: hover background-color rgba(0, 0, 0, 0.04); focus-visible solid 1px outline in rgba(0, 0, 0, 0.44), offset 2px.

## Imagery and graphics

### Working-world proof

**Use:** Default opening and human outcome stories.

**Observed:** Candid people in meetings, labs, transport and creative work, cropped fairly close. The opening uses overlapping landscape cards; editorial stories use square crops. Natural light, believable rooms and restrained grading matter more than theatrical portrait lighting.

**Transfer:** Commission or select specific working situations with real gestures and tools. Use the Proof photograph construction for the opening, then plain square framing for stories.

### Atmospheric color art

**Use:** Abstract editorial thumbnails and the fallback visual device for technical content.

**Observed:** Softly luminous blue, turquoise, lavender and green fields bend like translucent folds; some artworks add fine grain. They fill square frames edge to edge and carry no headline overlay.

**Transfer:** Produce a small family of related color studies rather than one generic gradient reused everywhere. This is the minimum visual equivalent when a technical story has no natural photograph.

**Build:** In a square SVG, layer three oversized curved paths over a pale blue base. Use turquoise and blue at 0.6–0.9 alpha, add one broad white diagonal curve at 0.7 alpha, then blur the colored shapes by 24–60px on a 443px artboard. Add a faint monochrome turbulence layer at 0.03 alpha. Change the path direction and dominant hue between cards; retain soft light and broad, fold-like shapes.

### Product demonstration

**Use:** Wide capability stages and tabbed platform proof.

**Observed:** A large real interface or edited workflow dominates its section. The marketing copy stays outside the demonstration; the surrounding white area and narrow frame keep the application readable without decorative device mockups.

**Transfer:** Show one legible task or output at a time. Use a genuine interface, with realistic populated content; keep internal UI styling separate from the marketing system.

### Diagrammatic color cards

**Only for:** solution catalogs and audience directories

**Use:** Repeated category art in four-column destination grids.

**Observed:** Flat cyan, coral, pink, green and teal squares contain oversized, cropped diagrams: flowing charts, bars, tables, rows and interface-like panels. A pale inset rectangle provides a second tone; white labels with colored lettering sit near the bottom of many catalog images.

**Transfer:** Reduce each category to one simple diagram. Keep consistent square framing and related two-tone palettes; avoid making each category look like a separate brand.

**Build:** Draw an SVG square with a saturated background, then inset a lighter rectangle from the upper left by roughly one fifth of the width. Fill it with thin 1px chart outlines, two or three broad bars, or a gently curved area chart extending off the lower edge. Add a small white rounded text plate near the lower left where a category label is useful.

### Research mosaic

**Only for:** technical editorial overview pages

**Use:** Wide visual culmination beneath a centered introduction.

**Observed:** A 1143px-wide landscape collage divides into unequal rectangles of blue, violet, pink and turquoise optical art: fine stripes, bead-like arcs, gradients and sparse dots.

**Transfer:** Use an original geometric collage to suggest breadth without pretending it is a quantitative chart.

**Build:** Split a landscape SVG into five irregular-width columns and subdivide alternating columns horizontally. Clip linear gradients, repeating 2px vertical stripes and large circular arcs into the cells. Render one arc as small outlined circles and another as bright dots, then apply very light grain across the whole composition.

### Culture and vision imagery

**Only for:** company and recruitment pages

**Use:** Humanizing broad purpose statements and organizational information.

**Observed:** Large warm office photographs sit in 1143×643 landscape frames. Narrower feature pairs use 554px square artwork: expressive pastel city brushwork or a sunlit hillside with one tree beneath a cloud-filled blue sky. A small, plain illustration credit sits below one artwork.

**Transfer:** Pair natural workplace photographs with original optimistic art grounded in place and daylight. Keep the art beside the text, not behind it; include a discreet credit when appropriate.

### Icons

**Observed:** Small monochrome SVG marks accompany actions: mostly 16px, with external arrows around 9×10px and compact chevrons around 10×16px. Search is unobtrusive; tab icons are about 20px. Footer social marks are tiny and aligned in one row.

**Transfer:** Use compact black or white symbols with the same visual weight as the text. Place directional icons after labels and capability icons before tab labels; avoid large multicolor feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: Labeled promise and proof stage

**Observed:** A 64px fixed Navigation floats above a white-to-pale-blue opening. A compact black announcement strip can sit directly below it, inset by 32px and 48px tall. The centered two-line promise begins well below the strip: the first phrase uses Headline lozenge at 64px/1, the second black phrase uses display at 64px/0.98 with an 8px separation. The phrase block is about 614px wide in a central 909px column, leaving substantial open space around it. A black Primary button and bare chevron sales link sit 32px below; there is no support paragraph between heading and actions. Behind the lower composition is pale blue light, then a full-width Proof photograph fan with the central image higher than its neighbors. Within the first 900px, navigation, strip, complete promise, actions and a substantial photographic band are visible. The opening ends around 835px; partner proof and feature chapters begin below the fold.

**Transfer:** Keep the headline-label device and human or output proof stage for a new marketing landing page. Without customer photography, make original scenes of the task or framed finished outputs rather than removing the stage. Editorial and company overviews instead open with a category label, editorial-display, narrow paragraph and optional actions; functional entry pages use Prompt composer. Catalog pages bring their first image grid into the bottom of the first screen.

**Avoid:** Do not replace this with a left-aligned text block beside a generic laptop render, add a long paragraph between the two headline phrases, or shrink the lower proof stage into a row of small logos.

**Text style:** `display` — OpenAI Sans 500 · 64px/0.98 · tracking -0.01em

### Partner proof strip

**Observed:** A white chapter holds five black partner marks in equal-width cells, with 64px horizontal gutters and generous separation from the opening.

**Transfer:** Use this only when genuine partnerships or customers support the promise; preserve the monochrome treatment without enlarging the marks into a second hero.

### Feature split

**Observed:** Blue feature atmosphere backs a two-column composition: narrow heading, paragraph, compact benefit list and Secondary button on the left; a wide demonstration about 554×312px on the right. Other feature pairs use square 554px media, alternate media sides, and retain inset text columns.

**Transfer:** Give each pair one job: introduce a capability, explain a practical benefit or answer a trust concern. Use the heading recipe, body copy and a single action.

**Text style:** `heading` — OpenAI Sans 500 · 30px/1.32 · tracking -0.01em

### Capability selector stage

**Observed:** A centered heading-lg and support line introduce a broad stage. Capability accordion occupies a narrow left rail while Media frame occupies most of the width to the right; one expanded item controls the visible workflow.

**Transfer:** Map task families to real demonstrations. Keep the media dominant rather than turning the rail into a second paragraph column.

**Text style:** `heading-lg` — OpenAI Sans 500 · 48px/1.16 · tracking -0.03em

### Platform showcase

**Observed:** A centered heading-lg leads to Product tabs, a concise support line and understated detail links. A large product view beneath is about 1143px wide and extends well below the initial section heading.

**Transfer:** Use the tabs for genuinely related products or modes. Change both explanation and demonstration together rather than merely animating the selected label.

**Text style:** `heading-lg` — OpenAI Sans 500 · 48px/1.16 · tracking -0.03em

### Editorial collections

**Observed:** A left section-label and right-aligned View all action precede Editorial card grids by 32px. Three-column story rows use square 443px media; catalog collections use four 326px squares and heading-sized category introductions. A compact news variant pairs 185px squares with titles in two broad columns.

**Transfer:** Mix feature depth with browsable proof. Use the three-column version for stories and the four-column version for a taxonomy, retaining unboxed captions.

**Text style:** `section-label` — OpenAI Sans 500 · 22px/1.26 · tracking -0.01em

### Centered statement and wide image

**Observed:** Editorial chapters use a centered 30px statement within about 909px, then broad 1143×643px art or photography. Career sections combine a short heading, one sentence, a pale action and the wide image after 40px. Featured role listings instead use narrow 909px rows with faint bottom rules and right-aligned Apply now links.

**Transfer:** Use the statement for an important principle or category explanation; use the row format for genuinely enumerable opportunities or resources rather than filling it with promotional paragraphs.

**Text style:** `heading` — OpenAI Sans 500 · 30px/1.32 · tracking -0.01em

### Closing invitation and directory

**Observed:** Closing wash spans the inset content width with 120px top and bottom padding. Centered heading-lg precedes a compact action group by 32px. Short versions are 368px tall; longer two-line invitations expand naturally. Business-oriented variants add a Newsletter field row on white beneath the band. After another 120px pause, Footer directory completes the page; its bottom row contains social, privacy and locale controls.

**Transfer:** End on one relevant invitation, then provide useful navigation. Keep newsletter consent separate from the invitation itself.

**Text style:** `heading-lg` — OpenAI Sans 500 · 48px/1.16 · tracking -0.03em

## Page flow

**Storyline:** Promise → visual proof → capability explanation → browsable breadth or human outcomes → focused invitation → directory.

### A product-led marketing overview with a strong conversion goal

1. **Promise** — Labeled two-part headline above a photographic proof stage.
2. **Social proof** — Monochrome partner marks give way to a product introduction split.
3. **Capability demonstration** — Task selector beside a large workflow, followed by a tabbed platform showcase.
4. **Audience routing** — Four vivid category cards open further paths.
5. **Closing call** — Pale invitation, white newsletter row and shared directory.

**Transfer:** Use this as the default landing-page pattern, selecting proof and capability blocks that fit the product.

### A task-first entry portal with editorial depth

1. **Product entry** — Short question, functional composer and route chips.
2. **Flagship announcement** — Large featured demonstration beside a narrow stack of square stories.
3. **Current activity** — Compact two-column news list.
4. **Outcome proof** — Three-column stories, technical updates and customer collections.
5. **Closing call** — Pale download invitation followed by the directory.

**Transfer:** Use for products visitors can try immediately, while giving returning visitors fresh reasons to browse.

### A technical editorial overview that establishes breadth and credibility

1. **Purpose** — Centered category, large title, explanation and two actions above a wide optical mosaic.
2. **Capability chapters** — Short centered statement then repeated category introductions and three-image collections.
3. **Participation** — Featured opportunities in restrained ruled rows.
4. **Closing call** — Pale index invitation and the shared directory.

**Transfer:** Replace technical domains with the new product's real knowledge areas and route readers to deeper material.

### A solution directory for readers finding their own context

1. **Promise** — Centered black title and narrow support text beneath a slim announcement.
2. **Audience routing** — Four-column diagrammatic collections organized by team and domain.
3. **Application proof** — Three square workflow cards.
4. **Objection handling** — Centered trust statement followed by alternating integration and security feature pairs.
5. **Closing call** — Pale conversion band, newsletter row and directory.

**Transfer:** Organize by the buyer's vocabulary, then answer implementation questions before the final action.

### A company story that makes an abstract mission tangible

1. **Identity** — Small category, one-word title and concise mission paragraph.
2. **Purpose explanation** — Narrow text beside optimistic square artwork.
3. **Human proof** — Centered statement, wide office photograph and a recruitment image chapter.
4. **Current work** — Tabbed four-card editorial collection.
5. **Organizational clarity** — Text/art pair explains structure.
6. **Closing call** — Pale participation invitation and the shared directory.

**Transfer:** Translate purpose into people, work and clear organization rather than a wall of executive statements.

## Writing

Confident and direct, with ambition expressed through useful work rather than breathless promotion. Technical language remains accessible and claims usually identify a capability or outcome.

**Do not copy:** Do not reuse OpenAI or product names, logos, customer marks, campaign identities, mission claims, dates, research achievements or source artwork. Source examples illustrate sentence construction only; substitute truthful claims and original assets for the new product.

- **Addressing the reader:** Use you and your for practical benefits, we for institutional commitments, and the product name for concrete capabilities.
- **Rhythm:** Short sentence-case headlines, usually one concise supporting sentence, and compact verb-led actions. Longer editorial titles can describe a specific result; paragraphs stay economical and avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An ambitious capability phrase paired with an everyday work context. | 5–10 words | “Frontier intelligence everywhere you work”<br>“Put AI to work across your organization” |
| Supporting line | Explain a useful capability and the context in which it helps. | 12–25 words | “Take on your most ambitious work with enterprise controls and governance.”<br>“Explore proven ways to apply AI across your organization—built to fit how your teams work.” |
| Chapter heading | A plain noun category or a practical benefit, not an elaborate slogan. | 1–9 words | “AI for every team”<br>“Built-in enterprise security”<br>“Recent news” |
| Primary action | Short verb plus destination or next step. | 2–4 words | “Get started”<br>“View research index”<br>“Contact sales” |
| Catalog support | Concrete active verbs with a useful result. | 4–12 words | “Turn insights into decisions.”<br>“Create, optimize, and scale campaigns.” |
| Closing invitation | Invite the reader to explore a relevant next step in a single direct line. | 3–12 words | “Explore all research”<br>“Join us in shaping the future of technology” |

**Words and phrasing to use:** work; create; explore; connect; built for; control; research; teams; learn more

**Avoid:** game-changing; mind-blowing; supercharge everything; unleash limitless potential; act now; revolutionary magic

**Rules:**

- Name the task before describing the technology behind it.
- Write feature lists as parallel verbs and specific outputs.
- Use dates, categories and reading time to make editorial material feel current and navigable.
- Keep trust language concrete: controls, privacy, governance and configuration need actual supporting detail.
- Prefer a useful invitation to artificial urgency.

## Do's and Don'ts

### Do

- Keep default opening type at 64px medium with -0.01em tracking; reserve tighter -0.03em for chapter and editorial display roles.
- Use 32px desktop side gutters and a consistent 24px grid gap.
- Set small conversion labels at 14px/1 in content-sized 40px pills.
- Let a central photograph rise above overlapping neighboring frames; retain the 8px white edge.
- Use square media with 6.1px corners and put captions beneath rather than over the image.
- Separate major chapters with 120px pauses while keeping image-to-title gaps at 16px.
- Finish with the broad pale invitation and a small-type directory on white.
- Keep secondary dates and support text at black 60% rather than introducing a colored gray ramp.

### Don't

- Do not turn all headings cyan; the accent belongs to the labeled opening phrase.
- Do not use heavy 700-weight display type in place of the measured 500-weight hierarchy.
- Do not round ordinary story images to 24px; that radius belongs to the composer, not the editorial grid.
- Do not surround every caption with a bordered, padded card; the publication layout depends on exposed white space.
- Do not give all pills a black fill; secondary actions use a 4% black wash and topic routes use outlines.
- Do not add elevated shadows to the full page or every content card; reserve noticeable lift for the opening photo stage.
- Do not scale footer navigation to body size; its 13px medium labels are intentionally much smaller than marketing copy.
- Do not use the warm photo backing as a beige theme across the whole website.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare .2s transitions with cubic-bezier(0, 0, 1, 1).
- Opening photo cards declare box-shadow 0.26s and transform 0.86s cubic-bezier(0.16, 1, 0.3, 1).
- Product tabs declare color transitions of .3s cubic-bezier(.6, 0, .4, 1).
- Media wrappers declare opacity .3s cubic-bezier(0, .56, .46, 1).

**Transfer:**

- Keep control feedback short and the photographic stage more deliberate; do not make every editorial item float like an opening proof card.
- Make selected tabs update their corresponding explanation and demonstration as one coherent state.

**Unknown:**

- Exact automatic sequencing, scroll-trigger thresholds and full reduced-motion behavior are not established.

### Responsive

**Observed:**

- The layout declares grid gutters of 8px, 16px and 24px at progressively wider layout tiers.
- The audience-card strip declares horizontal snap behavior at narrow widths; the footer declares a stacked layout before switching to a horizontal directory.

**Transfer:**

- On narrow screens, preserve the two-part opening hierarchy while allowing the label to wrap; scale its typography to fit rather than cropping the promise.
- Keep the central proof photograph legible and let neighboring cards remain partial edge cues.
- Stack feature pairs and footer groups; use horizontal snapping for compact audience collections where it preserves useful image size.

**Unknown:**

- Only desktop geometry is established. Exact mobile type sizes and component-specific breakpoint mappings remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
