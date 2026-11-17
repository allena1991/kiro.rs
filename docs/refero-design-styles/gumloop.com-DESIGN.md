# Gumloop — playful infrastructure theater

## Overview

A light, product-led style that makes serious infrastructure feel approachable through rounded geometric headings and tiny candy-colored characters. White and cool gray dominate, with black actions, exceptionally pale technical illustrations, and occasional dark chapters. Detailed interfaces carry the story at generous scale while compact grotesk body text keeps the surrounding explanation economical. It suits capable software platforms with several audiences and concrete workflows to demonstrate.

### Essentials

- A modest headline introduces an oversized working world: left-aligned Gellix 48px/1 at weight 500 with -0.025em tracking, about 501px wide, above a 1360px-wide product stage rather than beside a decorative hero image.
- Tiny candy-colored symbols supply the personality: a short strip of roughly 28px rounded shapes with 6px gaps accompanies the opening and closing invitation. Keep these saturated marks a tiny fraction of an otherwise white and gray page; create original abstract symbols when no product characters exist.
- Actions look like compact interface controls, not advertising badges: black and white paired buttons, 36px high, 8px corners, 14px/20px medium sans text and 18px horizontal padding; navigation uses 32px-high variants.
- Technical scenes are almost paper-white: white interface windows overlap on #f3f3f6 stages with 1px #ebebf1 edges and 8px corners. Recreate a plausible workflow with real labels when finished product media is unavailable; preserve the layered window composition.
- Proof mixes human headings with machine numerals: geometric 36px/1.25 headings sit beside GeistMono 60px/1 light figures, above orderly low-contrast logo tiles with 12px gutters.
- Dense demonstrations breathe inside sparse architecture: a 1440px outer container with 40px side insets, 48px heading-to-media gaps, 20px two-column gutters and 64px section padding; deeper dark chapters expand to 160px.
- The closing invitation is a compact island in a broad pale panel: 1360px-wide, 8px corners, about 398px tall, a 384px centered text column, the colorful symbol strip, a 36px/40px two-line heading and one black action. Preserve this recognizable device somewhere in a new landing-page design.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender atmosphere | `#e8e8f4` | `--color-purple-wash` | accent, background | Soft local glow behind capability art: source violet #6e6ade at 0.2 opacity, further reduced by an overall opacity of 0.4 over a gray stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#18191b` | `--color-ink` | text, background, action | Default headlines, strong text, primary buttons and full-width dark chapters. |
| Dark chapter card | `#242526` | `--color-inverse-surface` | surface | Visible white 0.05 layer over near-black, used for dark bento cards. |
| Deep gray | `#5f5f68` | `--color-body-strong` | text | Stronger explanatory text inside illustrative controls. |
| Secondary gray | `#7f7f86` | `--color-body-muted` | text | Visible result of #5f5f68 at 0.8 opacity over white; descriptions and secondary links. |
| Dark chapter muted gray | `#9999a2` | `--color-inverse-muted` | text | Secondary markings and labels on dark chapters. |
| Inverse body | `#b5b5b6` | `--color-inverse-body` | text | White at 0.68 opacity over near-black for dark chapter paragraphs. |
| Raised edge | `#e2e2e9` | `--color-edge` | border | Slightly stronger outlines in layered shadows and small controls. |
| Pale lavender edge | `#ebebf1` | `--color-rule` | border | Default 1px card edges, table rules and footer separator. |
| Cool gray stage | `#f3f3f6` | `--color-subtle` | surface, background | Large product stages, logo tiles, feature illustrations and closing panels. |
| Muted control gray | `#f4f4f5` | `--color-muted-surface` | surface | Inset control rows and small neutral chips within demonstrations. |
| Soft white | `#fcfcfc` | `--color-background` | background, surface | Inputs and softly differentiated interface backing; also the canvas of the focused product variant. |
| White | `#ffffff` | `--color-white` | background, surface, text | Default marketing canvas, raised windows and inverse headings. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Focus blue | `#0190ff` | `--color-focus` | border, accent | Focus-visible border on actions; not a default marketing button fill. |

## Typography

- **Gellix** — Headlines, section labels and editorial card titles. Rounded geometric sans with open bowls, single-storey forms and a friendly medium-weight silhouette. If unavailable, use **DM Sans**. Use 400–600; retain tight tracking on large headings. Font stack: "Gellix", "DM Sans", Arial, sans-serif.
- **GeistSans** — Descriptions, navigation, actions, footer links and interface labels. Compact contemporary grotesk with crisp, restrained shapes. If unavailable, use **Geist**. Font stack: "GeistSans", "Geist", system-ui, sans-serif.
- **GeistMono** — Large proof numbers and compact technical date labels. Even-width technical counterpoint; notably light on large numerals. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-number | GeistMono | 300 | 60px | 1 | normal | Large proof metrics, with compact suffixes kept on the baseline. |
| display | Gellix | 500 | 48px | 1 | -0.025em | Default left-aligned opening headline. |
| heading | Gellix | 500 | 36px | 1.25 | -0.025em | Primary section headings in light and dark chapters. |
| closing-heading | Gellix | 500 | 36px | 40px | normal | Centered closing invitation and centered product-section headings. |
| quote | Gellix | 400 | 20px | 1.4 | normal | Customer quotations and outcome summaries. |
| item-heading | Gellix | 500 | 18px | 28px | normal | Update titles and numbered process items. |
| body | GeistSans | 400 | 16px | 1.5 | normal | Section support paragraphs and capability captions. |
| label | Gellix | 500 | 16px | 24px | normal | Metric labels and FAQ question headings. |
| small-body | GeistSans | 400 | 14px | 20px | normal | Footer links, changelog descriptions and compact card text. |
| action | GeistSans | 500 | 14px | 20px | normal | Navigation, buttons and footer category titles. |
| eyebrow | Gellix | 500 | 14px | 20px | normal | Sentence-case labels above section headlines and short arrow links. |
| inverse-body | GeistSans | 400 | 14px | 1.5 | normal | Compact explanatory copy in dark cards. |
| caption | GeistSans | 400 | 12px | 16px | normal | Small credits, attributions and chart markings. |
| update-date | GeistMono | 500 | 12px | 16px | normal, uppercase | Dates below update descriptions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| focused product launches | product-display | Gellix | 500 | 72px | 1 | -0.025em | Centered, three-line launch headline in a 768px column. |

**Notes:**

- Use medium rather than bold for the rounded heading voice. Negative tracking belongs to the 48px and 36px main headings; the centered closing heading deliberately keeps normal tracking.
- The broad marketing scale is restrained: the default opening is 48px, not the 72px launch variant. Large monospace numbers can exceed the size of the nearby heading.
- Keep labels in sentence case except the small monospace update date. Captions often combine a dark medium-weight lead-in with muted regular support on the same line.

## Layout

**Density:** Airy around sections and compact inside product scenes; the contrast makes detailed software feel legible rather than busy.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Character-strip gaps and form label-to-field separation. |
| 8px | Title-to-description gaps inside cards and tight metric stacks. |
| 12px | Paired action gaps and customer tile gutters. |
| 16px | Eyebrow-to-heading and heading-to-support gaps; illustration-to-caption separation. |
| 20px | Two-column capability grid gutters and FAQ vertical button padding. |
| 24px | Card text stacks, form field groups and support-to-closing-action gap. |
| 28px | Opening headline-to-actions and opening copy stack gaps. |
| 32px | Testimonial inner padding and footer column gutters. |
| 40px | Desktop side insets, footer padding and FAQ heading-to-list gap. |
| 48px | Section text-to-media gap and update-card gutters. |
| 56px | Closing panel vertical inner padding. |
| 64px | Ordinary section vertical padding. |
| 96px | Opening top padding and spacious chapter introductions. |
| 160px | Major dark chapter vertical padding. |

### Containers and grids

- **page-container**: max width 1440px · side padding 40px. Centered outer container; yields 1360px usable width at desktop.
- **capability-pairs**: 2 columns · gap 20px. Equal 670px-wide illustrated capability cards with captions below their stages.
- **proof-grid**: 5 columns · gap 12px. Customer tiles arranged as a quiet rectangular proof field.
- **footer-grid**: 6 columns · gap 32px. Six evenly distributed link columns; category headings and small muted links.
- **launch-container** (only for focused product launches): max width 960px · side padding 0px. Narrower feature grid and gradient closing invitation; two 476px columns with an 8px gutter.
- **split-conversion** (only for sales inquiry pages): 2 columns · gap 48px. Vertically centered promise and testimonial on the left; pale form panel on the right.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons-and-stages | 8px |
| logo-tiles | 6px |
| illustrative-chips | 9999px (pill) |
| illustrative-orbs | 50% |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | raised-white-control | `0 0 0 1px #e2e2e9, 0 1px 1px -0.5px rgba(0,0,0,0.016), 0 3px 3px -1.5px rgba(0,0,0,0.016), 0 6px 6px -3px rgba(0,0,0,0.01), 0 12px 12px -6px rgba(0,0,0,0.01), 0 24px 24px -12px rgba(0,0,0,0.01)` | White secondary actions and raised controls; diffuse and edge-led, not a dark floating shadow. |
| sales inquiry forms | input | `0 1px 2px 0 rgba(0,0,0,0.05)` | Minimal depth under soft-white fields. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing page.

**CSS:** `background: #ffffff; color: #18191b`

#### Pale stage · level 1

**Use:** Product theater, capability art and closing panel.

**CSS:** `background: #f3f3f6; border: 1px solid #ebebf1; border-radius: 8px; overflow: hidden`

**Observed:** Broad, almost flat cool-gray planes make white windows and delicate lines readable.

**Transfer:** Stage an actual workflow or a simple diagram with the same low contrast.

#### Raised window · level 2

**Use:** Main interface objects and illustrative white cards.

**CSS:** `background: #ffffff; border: 1px solid #ebebf1; border-radius: 8px`

**Observed:** Nested over stages, sometimes with a stronger edge and a very diffuse control shadow.

**Transfer:** Use thin window chrome and believable UI hierarchy; reserve depth for overlap.

#### Dark chapter · level 0

**Use:** High-trust capability chapters.

**CSS:** `background: #18191b; color: #ffffff; padding-top: 160px; padding-bottom: 160px`

**Observed:** A full-width tonal reset surrounded by light sections, not a page-wide dark theme.

**Transfer:** Use for a cohesive reliability or operational-assurance story rather than isolated black cards.

#### Inverse card · level 1

**Use:** Bento illustrations within the Dark chapter.

**CSS:** `background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.14); border-radius: 8px`

**Observed:** Translucent white layers keep the black chapter nuanced; body copy is white at 0.68 opacity.

**Transfer:** Keep diagrams low-contrast and add small colored status cues.

#### Soft-white launch canvas · level 0

**Only for:** focused product launches

**Use:** Canvas surrounding atmospheric launch media.

**CSS:** `background: #fcfcfc`

**Transfer:** Keep this distinction subtle; the launch variant is not a different saturated theme.

## Components

### Navigation

**Use:** Persistent desktop wayfinding.

**CSS:** `background: #ffffff; height: 53px; border-bottom: 1px solid rgba(235,235,241,0.825)`

**Text style:** `action` — GeistSans 500 · 14px/20px

**Observed:** A 52px inner row plus bottom rule. Wordmark left, centered compact menu, two actions right inside the page-container. Above it sits a separate 32px dark announcement strip. The navigation remains at the viewport top on scroll and switches to dark with inverse text over dark chapters.

**Transfer:** Use the new identity at roughly the same compact scale; keep navigation subordinate to the page.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #18191b; color: #ffffff; border-radius: 8px; height: 36px; padding: 8px 18px; gap: 8px`

**Text style:** `action` — GeistSans 500 · 14px/20px

**Observed:** Paired with Secondary button in the opening; compact 32px-high controls with 14px horizontal padding appear in navigation, and a 40px-high pair appears beside a deeper feature explanation.

**States:** Declared: hover uses the near-black background at 80% opacity; focus-visible border-color is #0190ff.

### Secondary button

**Use:** Lower-emphasis demo or documentation action.

**CSS:** `background: #ffffff; color: #18191b; border-radius: 8px; height: 36px; padding: 8px 18px; box-shadow: 0 0 0 1px #e2e2e9, 0 1px 1px -0.5px rgba(0,0,0,0.016), 0 3px 3px -1.5px rgba(0,0,0,0.016), 0 6px 6px -3px rgba(0,0,0,0.01), 0 12px 12px -6px rgba(0,0,0,0.01), 0 24px 24px -12px rgba(0,0,0,0.01)`

**Text style:** `action` — GeistSans 500 · 14px/20px

**Observed:** The outline is primarily an edge-shadow rather than a heavy border; it sits 12px from the primary action.

**States:** Declared: hover keeps near-black text and an edge-led soft shadow; focus-visible border-color is #0190ff.

### Customer tile

**Use:** Reassurance without a loud logo marquee.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 96px; padding: 0px 24px; background: #f3f3f6; border: 1px solid #ebebf1; border-radius: 6px`

**Observed:** Small grayscale logos centered in equal tiles. A five-column proof field uses 12px gaps; compact pricing proof uses eight 160px-wide, 80px-high tiles.

**Transfer:** Normalize logos by optical weight and keep generous empty area inside each tile.

### Capability stage

**Use:** Illustrated capability with editorial caption below.

**CSS:** `height: 440px; background: #f3f3f6; border: 1px solid #ebebf1; border-radius: 8px; overflow: hidden; position: relative`

**Observed:** Two equal stages per row. The caption is outside the panel, separated by 16px, and blends a dark medium lead-in with regular muted explanation.

**Transfer:** Give each illustration one mechanism to explain rather than filling it with a full dashboard.

### Testimonial cell

**Use:** Editorial customer proof.

**CSS:** `background: #ffffff; padding: 32px; display: flex; flex-direction: column; gap: 24px; min-height: 288px; position: relative; overflow: hidden`

**Text style:** `quote` — Gellix 400 · 20px/1.4

**Observed:** Shared outlined two-by-two container with no card gutters. Logo and subtle Read more link at top, quotation in the middle, attribution or a monospace outcome anchored below. Very faint localized color glows appear behind some logos.

**Transfer:** Use verified quotes and a single outcome, keeping each cell like a small editorial excerpt.

### FAQ row

**Use:** Objection handling on commercial pages.

**CSS:** `display: flex; justify-content: space-between; padding: 20px 0px; border-bottom: 1px solid #ebebf1; min-height: 65px`

**Text style:** `label` — Gellix 500 · 16px/24px

**Observed:** One full-width question per line, small right chevron, no enclosing filled card. The list begins with a top rule and sits 40px below the heading.

**States:** Declared: hover text-decoration-line is none; focus-visible border-color is #0190ff.

### Update item

**Use:** Product momentum in a horizontal rail.

**CSS:** `display: flex; flex-direction: column; position: relative; width: 300px; flex-shrink: 0`

**Text style:** `item-heading` — Gellix 500 · 18px/28px

**Observed:** Small symbol at top, title after 40px, small-body description after 8px and uppercase monospace date after 20px. A 1px line joins the symbols; part of it carries a restrained rainbow progression. Neighboring items have 48px gaps.

**Transfer:** Apply to a release rail, milestone history or recent research rather than generic feature cards.

### Closing invitation

**Use:** Concentrated final conversion in a broad pale field.

**CSS:** `background: #f3f3f6; border: 1px solid #ebebf1; border-radius: 8px; overflow: hidden`

**Text style:** `closing-heading` — Gellix 500 · 36px/40px

**Observed:** An original colorful symbol strip precedes a centered two-line headline, muted support and one Primary button. The internal column is 384px wide with 56px vertical panel padding. The surrounding section has 40px top and 24px bottom padding.

**Transfer:** Retain the compact content island; adapt the benefit and action rather than making the whole panel text-heavy.

### Footer columns

**Use:** Dense directory ending shared across page types.

**CSS:** `display: grid; grid-template-columns: repeat(6, minmax(0px, 1fr)); column-gap: 32px; row-gap: 40px`

**Text style:** `small-body` — GeistSans 400 · 14px/20px

**Observed:** Category titles use action typography; column headings are 12px above lists, whose items occupy a 32px rhythm. After 64px, a top rule separates a final identity row from copyright and legal links.

**States:** Declared: link hover adds underline and near-black text.

### Inquiry field

**Only for:** sales inquiry forms

**Use:** Short qualified-contact form.

**CSS:** `background: #fcfcfc; border: 1px solid #ebebf1; border-radius: 8px; height: 40px; padding: 4px 12px; box-shadow: 0 1px 2px 0 rgba(0,0,0,0.05)`

**Text style:** `small-body` — GeistSans 400 · 14px/20px

**Observed:** Visible labels sit 6px above controls; groups are separated by 24px. A textarea is 60px high. The form sits inside a Pale stage with 40px inner padding and a medium rounded headline.

**Transfer:** Ask only the few questions needed to continue; retain the plain vertical stack.

### Comparison cell

**Only for:** pricing pages

**Use:** A detailed feature matrix instead of freestanding subscription cards.

**CSS:** `padding: 16px; border-bottom: 1px solid #ebebf1; border-left: 1px solid #ebebf1`

**Text style:** `label` — Gellix 500 · 16px/24px

**Observed:** Desktop table allocates 544px to feature names and 408px to each of two plans. Feature rows are about 57px high; category bars are 49px high. The enterprise column is a continuous cool-gray strip. Small green circular checks and gray crosses communicate availability; plan actions differ in emphasis.

**Transfer:** Group comparisons by meaningful capabilities; keep row alignment exact and headers available while reading.

## Imagery and graphics

### Layered product theater

**Use:** Hero stage and larger capability demonstrations.

**Observed:** A white application window on a cool-gray plane, with fine borders, small colored identity icons and a second analytics window overlapping its lower-left area. The main window is offset to the right so the overlap reads clearly; desktop chrome includes tiny traffic-light dots. Most pixels are white or pale gray, while actual content has crisp text and sparse colored charts.

**Transfer:** Create a main task window plus a smaller outcome window for the new product. A faithful, simplified HTML interface with plausible data is the minimum acceptable alternative to polished product media.

### Candy symbol strip

**Use:** Opening identity accent and closing invitation.

**Observed:** A very small horizontal procession of rounded squares, circles and soft blob-like characters in yellow, orange, cyan, pink and purple. Shapes vary in scale and angle, with tiny white facial details; they feel like interface inhabitants rather than large illustrations.

**Transfer:** Make a family of original friendly symbols tied to the new product's modules. Keep the strip small and recurring so personality does not overtake the interface.

**Build:** Use four to six 28px SVG silhouettes with 6px gaps, alternating round rectangles and circles. Add one or two small white inset marks per symbol, rotate outer shapes by roughly 10–25 degrees and scale the outer pair to about half the center pair. Clip the row inside a 128px by 32px viewport; use saturated yellow, orange, pink, purple and cyan.

### Pale mechanism diagrams

**Use:** Capability stages and routing explanations.

**Observed:** Fine gray lines, dotted connector paths, almost-white glass orbs and sparse floating white controls describe sharing, routing and accumulated knowledge. One orb uses curved pink and lavender orbital lines with tiny integration discs; another scene uses a large black central pill connecting two fading columns of task and destination labels.

**Transfer:** Choose one mechanism per scene: circulation, approval, routing or accumulation. Preserve visible structure but let secondary nodes fade toward the stage.

**Build:** Inside a Pale stage, draw SVG 1px gray connectors and a few 24–45px white icon discs. For the orb, use a 338px circle with a white radial highlight at 31% 25%, subtle inner shading and three elliptical pink/lavender paths at different rotations. Place a small dark product disc on one orbit. Add a 384px violet circle at 0.2 alpha, 0.4 opacity and 90px blur behind the art; keep the glow local.

### Pastel cloud backing

**Only for:** focused product launches

**Use:** Large product demo, selected feature diagrams and narrower closing panel.

**Observed:** Diffuse pastel cyan, lavender, blush and peach clouds wash behind white interface cards. The image is soft, slightly mottled and cloud-like, without hard gradient bands or a saturated center. Closing panel is 960px by 300px.

**Transfer:** Keep the atmosphere subordinate to crisp interface content. Match the soft glow; exact stops are not essential.

**Build:** Layer broad overlapping radial gradients in pale cyan, lavender, blush and peach over soft white. Use irregular ellipses centered toward alternate corners, blur their edges by 40–80px and add extremely low-contrast fine noise. Clip to a 6–8px rounded panel. Keep the central headline area light.

### Documentary workplace photography

**Only for:** culture and recruiting pages

**Use:** Wide opening film, two-up photo bands, collage and final gallery.

**Observed:** Daylit office scenes with real people working and laughing, plants, pale walls and warm wood. Images retain natural greens and warm skin tones. Straight two-up bands use fine frames and minimal corners; the collage overlaps three gently tilted prints on a gray panel. The ending is a two-row, horizontally overflowing gallery of 448px by 252px frames, not a conversion panel.

**Transfer:** Photograph actual work and specific environmental details with available daylight. Keep the lived-in atmosphere and alternating wide bands rather than using stock headshots.

### Cinematic customer stories

**Only for:** enterprise sales pages

**Use:** Large horizontal proof carousel.

**Observed:** Wide interview video cards around 1034px by 581px, with another card peeking at the right. A dark bottom-to-top veil supports white logo, quote or light monospace figure, attribution and a tiny translucent View story pill.

**Transfer:** Use a real customer portrait or film still, preserving environmental context and left-aligned lower-third information. A still with verified quote is sufficient.

**Build:** Place a full-bleed interview still in an 8px rounded container. Overlay a black linear gradient from 0.85 alpha at the bottom through 0.3 at the midpoint to 0.1 at the top. Put the logo at upper left and proof text low left; use a white 0.16-alpha pill with 8px backdrop blur for the story link.

### Icons

**Observed:** Utility icons are chiefly 16px SVG outlines with 1.5px rounded strokes; 12px and 20px variants serve compact controls. Integration identities and character symbols are filled and colored. Small arrows follow text links, while carousel controls are 36px circles.

**Transfer:** Use a consistent rounded outline set for utilities, preserving full-color identity icons only where they convey a real connection or status.

## Section recipes

How recurring sections are built.

### First screen: Product stage opening

**Observed:** A separate 32px dark announcement sits above the 53px navigation. The white opening has 96px top padding inside page-container. At left, a short candy symbol strip introduces a 501px-wide, two-line display headline, with 28px stack gaps; there is no explanatory paragraph in this default opening. Paired Primary button and Secondary button sit 12px apart. After 48px, a full-width Pale stage begins, 1360px wide and 850px tall, with a large white product window behind an overlapping lower-left analytics window. Within the first 900px, the identity strip, full headline, both actions and upper portion of the product scene are visible; the lower interface and proof section continue below the fold. The right side of the heading area remains intentionally open.

**Transfer:** Write a short multi-verb promise and create a real task-plus-outcome scene for the new product. Without media, use a simplified HTML interface and a small result panel, not a decorative abstract dashboard. Sales inquiry pages instead open with a split testimonial/form composition; pricing and recruiting use left-aligned display headlines; focused launches use the centered product-display recipe and a pastel-backed demonstration.

**Avoid:** Do not replace the opening with a centered giant slogan, a side-by-side stock illustration or a paragraph-heavy hero. Do not shrink the product stage to fit its entire height above the fold.

**Text style:** `display` — Gellix 500 · 48px/1 · tracking -0.025em

### Section lead stack

**Observed:** Eyebrow, heading and body stack in 16px gaps, followed by 48px before substantial media. Text is usually left aligned and support is constrained to about 640px; labels can end in a tiny arrow.

**Transfer:** Use a specific short capability label, one outcome headline and one explanatory sentence. Keep heading and supporting measure distinct.

**Text style:** `heading` — Gellix 500 · 36px/1.25 · tracking -0.025em

### Proof field

**Observed:** A broad heading occupies the left side of the top row; two proof-number stacks align at the right, each with label above and 8px separation. Below a 48px gap, Customer tiles fill a five-column field. Ordinary section padding is 64px.

**Transfer:** Pair verified scale or outcome metrics with relevant customer or partner marks. Preserve light monospace numerals rather than making all proof bold.

### Feature explanation and demonstration

**Observed:** A narrow text rail with eyebrow, heading, body and paired actions sits alongside a much larger white workflow demonstration. A slim vertical tab rail indexes examples. Other capability scenes use the capability-pairs layout with Capability stage panels and captions outside.

**Transfer:** Let explanatory copy anchor one side while the mechanism dominates the other. Use original examples reflecting actual user tasks.

### Insights rail

**Observed:** Section lead stack and circular previous/next controls introduce a horizontally clipped row of white data cards about 435px wide with 20px gutters. Each card has a title, a short question and a distinct chart or ranked list; one card can visibly continue off the right edge.

**Transfer:** Show actual product outputs with different visual structures, such as ranked items, a trend and a health summary, rather than repeating identical metric cards.

### Trust chapter

**Observed:** Dark chapter contains a white heading and an asymmetrical two-column bento: one tall Inverse card at left and two shorter cards at right, separated by 20px. A five-column row of smaller illustrated assurances follows after 48px. Charts use muted gray and sparse pink or green highlights.

**Transfer:** Translate the chapter into the new product's reliability, governance or operational confidence story, preserving translucent layering rather than generic padlock artwork.

### Editorial proof and updates

**Observed:** A shared two-column grid of Testimonial cells follows a short heading. A separate recent-updates rail uses Update items with tiny symbols joined by a 1px track, title, support and uppercase date.

**Transfer:** Use a proof grid for measured impact and an update rail for ongoing progress. The two formats need different content density.

### FAQ and conversion ending

**Observed:** Commercial pages place FAQ rows below a heading with 40px separation, then Closing invitation and Footer columns. The default panel contains the recurring candy symbol strip, centered closing-heading, body copy after 16px and action after 24px. Focused launches instead use the pastel 960px by 300px panel and one demo action. Recruiting concludes its narrative with documentary gallery strips before the same footer directory.

**Transfer:** Resolve objections before making a compact final invitation. Match the appropriate page-type ending rather than adding an identical sales panel to every page.

**Text style:** `closing-heading` — Gellix 500 · 36px/40px

### Detailed pricing matrix

**Only for:** pricing pages

**Observed:** Left-aligned display headline, horizontal logo strip and a wide three-column table. Plan names, brief price line and action form a 140px header. Comparison cells keep exact row alignment; category bands span the feature area while the enterprise column stays tinted. FAQ and the default closing invitation finish the page.

**Transfer:** Use the matrix when the buyer needs feature-level comparison; avoid visually equal pricing cards followed by a second redundant comparison.

### Recruiting editorial chapters

**Only for:** culture and recruiting pages

**Observed:** A left-aligned display headline and brief support lead directly into a wide office film. Documentary bands alternate with split text/media chapters, a sparse three-column benefits grid, a dark categorized role directory with 77px rows, and a numbered process column. The final photo gallery precedes the footer.

**Transfer:** Organize around authentic work, belonging, practical details and the next step. Preserve the editorial photo rhythm without requiring identical organizational topics.

## Page flow

**Storyline:** promise → working product or human context → credible proof → capability chapters → practical assurance → next step → directory

### Broad platform introduction that makes a complex product tangible

1. **Promise** — Short left-aligned headline, recurring colorful symbols and paired actions over a large layered product scene.
2. **Social proof** — Light monospace counters and a tiled customer field.
3. **Product demonstration** — A narrow explanatory rail beside a large workflow; then browser and collaboration demonstrations.
4. **Capability chapters** — Pale illustrated pairs, an insights carousel, a full-width dark trust chapter and a routing mechanism diagram.
5. **Outcome proof** — Editorial customer grid followed by a slim update rail.
6. **Closing call** — Broad pale invitation panel and six-column footer with identity/legal row.

**Transfer:** Adapt the length to the product; keep a mix of working UI, mechanism art and editorial proof rather than a chain of identical cards.

### Help a buyer compare access and resolve cost objections

1. **Promise** — Plain left-aligned opening headline and a single row of customer tiles.
2. **Comparison** — Feature matrix with two plan columns, a continuous gray enterprise column and grouped rows.
3. **Objection handling** — Full-width ruled FAQ list.
4. **Closing call** — Default pale invitation and shared directory footer.

**Transfer:** Make the table the primary reading task and keep the surrounding promotion compact.

### Launch a focused technical product with a more atmospheric visual register

1. **Promise** — Centered 72px headline, short support and one action.
2. **Product demonstration** — Large activity interface on a diffuse pastel field.
3. **Capability chapters** — Centered section headings, narrow two-column diagrams and a six-item capability grid.
4. **Closing call** — A 960px pastel invitation with a two-line heading and one action, then shared footer.

**Transfer:** Use this scoped variant for a distinct product launch, not as the default for every page.

### Introduce an organization through its actual working environment and make joining concrete

1. **Promise** — Left-aligned title, short support and an application action above a wide workplace film.
2. **Credibility** — Customer proof field and scale counters.
3. **Human context** — Photo collage, expandable editorial links, documentary photo bands and supporter grid.
4. **Practical detail** — Sparse benefits grid and a large dark categorized opportunity directory.
5. **Expectation setting** — Numbered process with detailed descriptions.
6. **Ending** — Two-row photo gallery and shared directory footer; no default pale conversion panel.

**Transfer:** Balance specific human detail with practical decision-making information; use real images rather than posed generic portraits.

### Convert a high-intent buyer while supporting organizational confidence

1. **Promise and conversion** — Split headline/testimonial and compact form panel.
2. **Social proof** — Counters, customer tiles and large cinematic customer-story cards.
3. **Capability chapters** — A split interoperability explanation followed by the shared dark assurance chapter.
4. **Objection handling** — Short enterprise-focused FAQ list.
5. **Closing call** — Default pale invitation and shared directory footer.

**Transfer:** Let the form appear immediately while subsequent content substantiates the decision to engage.

## Writing

Confident, practical and friendly without becoming cute. Technical competence is demonstrated through specific actions, recognizable workflows and concrete outcomes rather than grand future-facing language.

**Do not copy:** Do not reuse the Gumloop or Gumstack names, wordmarks, character artwork, customer marks, customer quotations, product version names, statistics, pricing or performance claims. Source examples illustrate cadence only; all proof and claims must belong to the new product.

- **Addressing the reader:** Address the reader as you or your; use we for human organizational statements and the product name when describing a mechanism.
- **Rhythm:** Short, often multi-clause headlines with plain verbs; one or two support sentences explain the actual mechanism. Compact action labels and sentence-case section labels; punctuation stays conversational and restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A sequence of useful actions, or a direct promise tied to the reader's work. | 5–10 words | “Build, share, optimize & control agents”<br>“Pricing that scales with you” |
| Section headline | A human benefit with a concrete technical noun, sometimes a compact three-beat statement. | 4–10 words | “Your agents. Your spend. One control plane.”<br>“A real browser for every agent” |
| Support | Explain what happens and where, using a list of real actions instead of adjectives. | 20–35 words | “Agents sign in with your saved logins, browse from trusted connections, hand off to you when a site needs it, and record every session.” |
| Action | A plain verb plus a specific destination or next step. | 1–3 words | “Book a demo”<br>“Read the handbook”<br>“Explore agents” |
| Human context | A short warm assertion backed by tangible specifics. | 8–16 words | “We invest in the team the way we invest in the product.” |
| Update title | State the new capability directly; capitalize as a concise release title. | 3–10 words | “Open Artifacts in Google Workspace or Microsoft Office” |

**Words and phrasing to use:** build; share; your team; work; across; control; real; trusted; one; from idea to outcome

**Avoid:** revolutionary; disruptive; game-changing; unleash limitless potential; magic solution; enterprise synergy

**Rules:**

- Lead with what people can accomplish, then explain how the system does it.
- Use technical terms when they help buyers evaluate a real capability; do not substitute buzzwords for mechanisms.
- Use exact customer outcomes only when verified, with an attribution nearby.
- Pair terse card lead-ins with practical descriptions; do not make every card another slogan.

## Do's and Don'ts

### Do

- Keep default opening headlines at 48px/1, weight 500 and -0.025em tracking.
- Use a 1440px outer width and 40px desktop side insets so stages and proof fields align.
- Keep primary and secondary actions compact at 36px high with 8px corners.
- Maintain 48px between section introductions and substantial visual media.
- Use 20px gutters for capability pairs and 12px gutters for customer tiles.
- Give large proof numerals a light 60px monospace treatment.
- Place capability captions 16px below the image stage rather than inside a heavy caption bar.
- Carry the tiny colorful symbol motif into the compact centered closing invitation.

### Don't

- Do not make a saturated accent color the default button fill; conversion controls are near-black or white.
- Do not turn the pale stage into a hard-edged blue or purple gradient slab.
- Do not use 700-weight display headings; the visual voice depends on rounded medium shapes.
- Do not give all panels 24px or 32px corners; the recurring stage and card radius is 8px.
- Do not make the proof field a fast full-color logo ticker; its tiled grayscale treatment is deliberately calm.
- Do not promote screenshot-internal integration colors into the marketing navigation or body palette.
- Do not stretch ordinary support paragraphs across the entire 1360px content width; around 640px is the common measure.
- Do not replace the footer directory with an oversized wordmark poster; the ending is organized links followed by a modest identity/legal row.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.15s transitions with cubic-bezier(.4, 0, .2, 1). Navigation color changes declare 0.3s with the same curve.
- The small symbol strip declares 0.5s transforms with cubic-bezier(0.77, 0, 0.175, 1), including translation, rotation and scale; reduced-motion declarations remove these transitions.
- Illustrative scenes use changing highlights, fades and pulses; full animation choreography is not specified here.

**Transfer:**

- Use motion to move emphasis among small symbols and workflow states while leaving the page's text structure stable.
- Keep the recurring symbol strip a tiny contained motion accent, not a full-width scrolling decoration.

**Unknown:**

- Exact trigger timing, scroll synchronization and complete demonstration playback sequences.

### Responsive

**Observed:**

- Desktop container uses 40px side padding; class declarations use 24px before the medium breakpoint.
- Capability pairs declare one column before the medium breakpoint; customer proof declares two, then three, then five columns. Footer declares two, then three, then six columns.
- The default headline declares 36px before medium and 48px afterward. The closing headline declares 24px before medium and 36px afterward.
- Opening action pairs declare a vertical full-width layout before the small breakpoint and a horizontal layout afterward.

**Transfer:**

- On narrow screens, preserve the product-stage silhouette and readable central task rather than uniformly miniaturizing every interface label.
- Stack split editorial text before its media and keep the closing text island centered inside reduced side padding.

**Unknown:**

- Rendered mobile states, navigation menu behavior and all intermediate demonstration reflows.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
