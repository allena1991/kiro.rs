# Manus — painted worlds, practical tools

## Overview

An editorial serif gives approachable authority to a light, functional software presentation. Warm off-white, charcoal and restrained blue surround white interfaces staged over painterly skies and landscapes. The feeling is capable rather than technical: spacious narrative sections alternate with compact controls and concrete product examples.

### Essentials

- Editorial promises, functional explanations: centered Libre Baskerville headlines use 48px/1.2 at weight 600; capability titles switch to system sans at 32px/1.2 and weight 600.
- The opening invites use rather than just admiration: a 680px-wide headline sits above a 768px-wide white task composer with 22px corners, followed by a tray of small example outputs. Preserve this hands-on invitation with a relevant input or a faithful static example.
- Actions are small, soft-ended objects: main buttons are charcoal pills, 40px high with 14px/20px medium text; repeated mid-page actions use a translucent warm-gray pill rather than a loud accent fill.
- Color lives inside bounded demonstrations: the main canvas is #f8f8f7, primary text #1a1a1a and actions #1a1a19. Blue #0081f2 is reserved for short links and selected controls; painterly color occupies media rectangles, not whole scrolling backgrounds.
- A useful interface floats inside an artful world: white UI cards overlap muted painted blue skies, clouds and turquoise scenery, usually inside a 476px square or a 326px-wide process image. Every new landing page needs this contrast; a simplified working UI over a softly textured landscape is the minimum equivalent.
- The ending becomes a small editorial colophon: a full-width #1a1a19 footer opens with a two-line 36px/44px italic serif thought, then a 48px gap to dense 14px/20px link columns and a final social/language utility row.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link and selection blue | `#0081f2` | `--color-blue` | link, accent, border | Inline links and selected billing controls. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button and footer charcoal | `#1a1a19` | `--color-charcoal` | background, action | Primary action fills and the closing footer. |
| Primary ink | `#1a1a1a` | `--color-ink` | text | Headlines, card titles and primary prose. |
| Secondary text | `#4d4d4d` | `--color-secondary` | text | Introductory descriptions, navigation and compact card descriptions. |
| Muted text | `#737373` | `--color-muted` | text | Capability explanations and process captions. |
| Reversed secondary text | `#a3a3a3` | `--color-footer-muted` | text | Visible rgba(255,255,255,0.6) on charcoal; footer links and reversed supporting prose. |
| Input edge | `#e5e7eb` | `--color-input-edge` | border | Faint opaque outline of the main task composer. |
| Warm action wash | `#e9e8e7` | `--color-soft-action` | action | Visible rgba(55,53,47,0.08) over the off-white canvas; repeated mid-page action pills. |
| Subtle divider | `#eeeeed` | `--color-hairline` | border | Visible rgba(0,0,0,0.04) on the off-white canvas; FAQ and comparison rules. |
| Warm panel wash | `#f0f0ef` | `--color-soft-panel` | surface | Visible rgba(55,53,47,0.04) over the off-white canvas; cards, announcement bands and closing panels. |
| Panel edge | `#f0f0f0` | `--color-panel-edge` | border | Visible rgba(0,0,0,0.06) over white; outlines for framed media and white cards. |
| Warm off-white | `#f8f8f7` | `--color-canvas` | background | Default page and sticky navigation canvas. |
| Interface white | `#ffffff` | `--color-white` | surface, text | Task inputs, interface panels and reversed headings. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| playful interactive product campaigns | Arcade amber | `#efa201` | `--color-amber` | text, accent | Small tracked monospace status label in the game-themed closing panel. |
| pricing and selection controls | Selected blue wash | `#ebf5fe` | `--color-blue-wash` | surface | Visible rgba(0,129,242,0.08) over white, used for selected billing choices. |

## Typography

- **-apple-system** — Navigation, explanatory headings, body copy and controls. A native system sans with open counters and economical interface proportions. Font stack: "-apple-system", system-ui, "Segoe UI Variable Display", "Segoe UI", Helvetica, Arial, sans-serif.
- **Libre Baskerville** — Hero promises, section headings and the italic footer thought. Broad, bookish serif with strong contrast and readable, substantial lowercase forms. Font stack: "Libre Baskerville", Georgia, Cambria, "Times New Roman", Times, serif.
- **ui-monospace** (only for playful interactive product campaigns) — Small arcade status text. Plain technical monospace, widely tracked for a game-console accent. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, "Liberation Mono", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Libre Baskerville | 600 | 48px | 1.2 | normal | Centered outcome-led opening promise. |
| heading | Libre Baskerville | 600 | 40px | 1.2 | normal | Centered section introductions. |
| heading-close | Libre Baskerville | 600 | 40px | 1.2 | -0.02em | Compact centered closing-call headline. |
| footer-thought | Libre Baskerville | 400 italic | 36px | 44px | normal | Left-aligned two-line thought at the top of the dark footer. |
| capability-title | -apple-system | 600 | 32px | 1.2 | normal | Left-aligned explanatory heading beside a demonstration. |
| body | -apple-system | 400 | 16px | 1.5 | normal | Hero support, section descriptions and capability prose. |
| card-title | -apple-system | 500 | 16px | 1.5 | normal | Compact feature-card names and process labels. |
| question | -apple-system | 500 | 16px | 1.25 | normal | FAQ questions and comparison cells. |
| small | -apple-system | 400 | 14px | 20px | normal | Compact card copy, process descriptions and footer links. |
| control | -apple-system | 500 | 14px | 20px | normal | Navigation labels, primary buttons and footer column labels. |
| soft-control | -apple-system | 510 | 14px | 20px | normal | Repeated soft action pills. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| playful interactive product campaigns | game-display | Libre Baskerville | 400 | 46px | 52px | normal | Short literal product-category headline. |
| playful interactive product campaigns | game-heading | Libre Baskerville | 600 | 40px | 1.4 | normal | Airier heading above dense visual demos and gallery sections. |
| minimal task-entry portals | invitation | Libre Baskerville | 400 | 36px | 1.5 | normal | Single conversational question above the input. |
| team and business product pages | team-capability | -apple-system | 600 | 32px | 1.25 | -0.0156em | Titles within alternating half-image feature panels. |
| customer proof panels | testimonial | Libre Baskerville | 700 | 30px | 1.2 | normal | Substantial white quotation over photography. |
| playful interactive product campaigns | game-card-title | -apple-system | 600 | 24px | 32px | normal | White instructional card headings. |
| playful interactive product campaigns | arcade-status | ui-monospace | 400 | 12px | 1.5 | 0.3em, uppercase | Small gold console-like status phrase. |

**Notes:**

- The largest type is a bookish serif, not an oversized geometric sans. Keep the normal tracking of the primary headline and section headings; only closing-call headings tighten to -0.02em.
- Use a single serif family for both upright titles and italic closing text. Sans headings explain the mechanics while serif headings frame the narrative.
- Keep supporting text visibly smaller than headings: 16px body for introductions and 14px copy inside compact repeated units. No viewport-relative type formula is required.

## Layout

**Density:** Airy narrative framing with compact, functional UI clusters; the outer page breathes while the demonstrations remain plausible tools.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card title-to-description gaps and footer link rhythm. |
| 12px | Section heading-to-support gap, compact tray padding and navigation item padding. |
| 16px | Icon-to-copy gaps and primary-button side padding. |
| 24px | Page side gutters, card padding and repeated-card grid gaps. |
| 48px | Heading-group-to-content spacing and vertical gaps between capability rows. |
| 80px | Default major-section top and bottom padding; horizontal gap between unboxed capability halves. |
| 100px | Footer top and bottom padding. |
| 160px | Breathing room after the final conversion panel before the footer. |

### Containers and grids

- **content**: max width 1032px · side padding 24px. Centered primary content area for section media, tables, FAQ and grids.
- **navigation-shell**: max width 1080px · side padding 24px. Border-box shell with 1032px usable width; logo left, navigation centered and utilities right.
- **headline-measure**: max width 680px. Centered hero and section copy measure; supports controlled multi-line serif titles.
- **input-stage**: max width 768px. Centered task composer and idea tray, slightly wider than the headline.
- **feature-grid**: 2 columns · gap 24px. Compact capability cards; two 504px columns at desktop.
- **process-grid**: 3 columns · gap 24px. Equal 328px process columns with image, label and description.
- **capability-row**: 2 columns · gap 80px. Alternating 476px square demonstration and equally wide text block.
- **footer-columns**: 7 columns · gap 24px. Dense navigational groups under an otherwise spacious editorial closing line.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action-pills | 9999px (pill) |
|  | feature-cards | 12px |
|  | media-and-closing-panel | 16px |
|  | task-composer | 22px |
|  | idea-tray | 24px |
| visual template galleries | gallery-cards | 20px |
| playful interactive product campaigns | instruction-cards | 24px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| composer-lift | `0px 12px 32px 0px rgba(0,0,0,0.02)` | Very slight separation beneath the white input. |
| tray-edge | `0px 0px 0px 1px rgba(0,0,0,0.06), 0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.04)` | Fine outline and low layered lift around the hero idea tray. |

### Surfaces

#### Canvas · level 0

**Use:** Main page and navigation background.

**CSS:** `background: #f8f8f7`

**Observed:** Continuous off-white rather than alternating stark white bands.

**Transfer:** Let spacing and bounded media define chapters.

#### Warm panel · level 1

**Use:** Small feature cards and soft grouped content.

**CSS:** `background: rgba(55,53,47,0.04); border-radius: 12px`

**Observed:** A low-contrast warm gray wash, generally without a shadow or hard outline.

**Transfer:** Group related content without creating a dashboard-like grid of heavy boxes.

#### White tool · level 2

**Use:** Hero inputs and interactive interfaces.

**CSS:** `background: #ffffff; border: 1px solid #e5e7eb; border-radius: 22px; box-shadow: 0px 12px 32px 0px rgba(0,0,0,0.02)`

**Observed:** Clean white on off-white with delicate separation.

**Transfer:** Reserve this raised treatment for things a user can operate or inspect.

#### Closing panel · level 1

**Use:** Contained final conversion invitation.

**CSS:** `background: rgba(55,53,47,0.04); border-radius: 16px; padding: 80px 48px`

**Observed:** Centered copy on a full content-width soft panel; the text stays within the narrower headline measure.

**Transfer:** Use a clear invitation and one primary button.

#### Dark colophon · level 0

**Use:** Full-width footer.

**CSS:** `background: #1a1a19; color: #ffffff; padding: 100px 24px`

**Observed:** A distinct dark destination after the light page, not another card.

**Transfer:** Keep the editorial thought above navigational density.

#### Selected billing choice · level 2

**Only for:** pricing and selection controls

**Use:** Selected payment cadence or plan option.

**CSS:** `background: rgba(0,129,242,0.08); border: 1px solid #0081f2; border-radius: 12px; padding: 12px 16px`

**Observed:** A fine blue border and pale wash differentiate the selection from white alternatives.

**Transfer:** Use blue only on the selected option, not the entire pricing panel.

## Components

### Sticky navigation

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; z-index: 20; height: 56px; background: #f8f8f7`

**Text style:** `control` — -apple-system 500 · 14px/20px

**Observed:** A Navigation-shell layout holds a small mark and wordmark at left, centered links and a language control plus compact dark action at right. Navigation items have 6px 12px padding and 8px corners.

**Transfer:** Keep the header visually light and the logo modest.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; gap: 6px; background: #1a1a19; color: #ffffff; border-radius: 9999px`

**Text style:** `control` — -apple-system 500 · 14px/20px

**Observed:** Text-centered pill. The navigation version is 32px high with 12px side padding and 14px/18px text. The business-plan conversion button expands to the panel width.

**Transfer:** Use the compact pill for the single clearest action; keep labels short.

### Soft action

**Use:** Repeated section-level conversion or exploration.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 10px 12px; background: rgba(55,53,47,0.08); color: #1a1a1a; border-radius: 48px`

**Text style:** `soft-control` — -apple-system 510 · 14px/20px

**Observed:** The inner label wrapper adds 4px at either side. Usually centered after a grid or table rather than placed in every card.

**Transfer:** Repeat one consistent action through a long page without adding visual noise.

### Task composer

**Use:** Hands-on opening invitation.

**CSS:** `display: flex; flex-direction: column; gap: 12px; max-width: 768px; padding: 12px 0px; background: #ffffff; border: 1px solid #e5e7eb; border-radius: 22px; box-shadow: 0px 12px 32px 0px rgba(0,0,0,0.02)`

**Text style:** `body` — -apple-system 400 · 16px/1.5

**Observed:** A spacious text area sits above a bottom utility row: add/import affordances on the left and a 32px circular upward-arrow submit control at right. The desktop stage is 128px high; the text region has 16px left inset.

**Transfer:** Use a real input if the product accepts a task. Otherwise show a legible example request in this exact tool-like composition.

### Idea tray

**Use:** Examples immediately below the opening input.

**CSS:** `background: #ffffff; border-radius: 24px; padding: 12px 12px 24px; overflow: hidden; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.06), 0px 1px 2px 0px rgba(0,0,0,0.04), 0px 2px 4px 0px rgba(0,0,0,0.04)`

**Text style:** `control` — -apple-system 500 · 14px/20px

**Observed:** A title row with tiny previous/next and dismiss controls introduces four miniature example previews; a second row offers three use-case suggestions. It sits 24px below the composer.

**Transfer:** Use a small selection of plausible outputs, not decorative empty thumbnails.

### Feature card

**Use:** Concise ownership, control or capability benefits.

**CSS:** `background: rgba(55,53,47,0.04); border-radius: 12px; padding: 24px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `card-title` — -apple-system 500 · 16px/1.5

**Observed:** An outline icon precedes the title on one line; a 14px description follows with an 8px gap. Cards have equal height within each two-column row and no heavy shadow.

**Transfer:** State one useful capability per card.

### FAQ row

**Use:** Full-width objection handling.

**CSS:** `display: flex; flex-direction: column; max-width: 1032px; border-bottom: 1px solid rgba(0,0,0,0.04)`

**Text style:** `question` — -apple-system 500 · 16px/1.25

**Observed:** The clickable inner row has 24px top and bottom padding, question at left and a muted 28px plus icon at right. Closed rows are 73px tall; the list is unboxed.

**Transfer:** Keep answers in expandable rows rather than a collection of separate raised cards.

### Comparison table

**Use:** Explain practical differences between approaches.

**CSS:** `border: 1px solid rgba(0,0,0,0.06); border-radius: 12px; overflow: hidden`

**Text style:** `question` — -apple-system 500 · 16px/1.25

**Observed:** Three columns: row topic, traditional approach and product approach. Approximately 64px rows use bottom rules; dark row labels contrast with muted descriptions. A Soft action follows below.

**Transfer:** Compare concrete capabilities, not an oversized wall of check marks.

### Footer link

**Use:** Dense navigation within the dark colophon.

**CSS:** `display: block; color: rgba(255,255,255,0.6); margin-top: 8px`

**Text style:** `small` — -apple-system 400 · 14px/20px

**Observed:** Each group starts with a white medium-weight label, followed by regular-weight links. Copyright sits left on the bottom row; social icons and outlined language selector sit right.

**Transfer:** Retain the compact rhythm even when the number of groups changes.

### Pricing panel

**Only for:** team and business product pages

**Use:** A single configurable plan rather than a broad tier matrix.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.06); border-radius: 16px; padding: 24px 24px 32px; max-width: 600px`

**Text style:** `small` — -apple-system 400 · 14px/20px

**Observed:** A small serif plan name precedes two cadence choices; the blue-selected choice carries a corner saving tab. Below are seat controls, a pooled usage summary, total price, a full-width Primary button and a compact icon-led inclusion list.

**Transfer:** Adapt the calculator to the product's real billing unit; keep the total and conversion clear.

## Imagery and graphics

### Painted interface stage

**Use:** Signature visual proof in capability chapters and process steps.

**Observed:** A clean white browser or prompt card floats in front of a muted painterly sky. Broad blue-gray brushwork, cream clouds and sometimes turquoise water give a handmade texture. Square media occupies about half a capability row; smaller 3:2 media heads each process column. Cards overlap the painting with small, soft shadows rather than a device frame.

**Transfer:** Show a real task and resulting artifact for the new product. Preserve the calm painted backing and crisp interface contrast; a single simplified UI card over a textured sky is an acceptable minimum.

**Build:** Use a 476px square clipping container with 16px corners. Layer a muted blue-gray base, irregular cream SVG cloud paths in the upper-right and lower-left, and a few low-opacity turquoise brush-like polygons at the bottom. Apply an SVG feTurbulence/displacement texture lightly to the backdrop only. Place a white interface card about two thirds of the container width near the center, then overlap its lower edge with a smaller white prompt card. Keep the UI untextured and readable.

### Large output showcase

**Use:** Late-page proof of what the product produces.

**Observed:** A 1032px-wide, approximately 16:9 media frame on a desaturated blue painted backing contains a centered real interface. Tabs above choose categories; previous/next controls and a Soft action sit below.

**Transfer:** Use credible output examples with their natural visual identity. Do not turn the surrounding page into the output's theme.

### Game-world demonstration

**Only for:** playful interactive product campaigns

**Use:** Interactive examples, template galleries and game-like closing calls.

**Observed:** Gallery thumbnails are vivid playable worlds, cropped to 16:9 above compact white card bodies. An interactive hillside combines painterly scenery with a small pixel character and stars. The closing panel uses intricate isometric block terrain around a dark green central clearing, with white centered serif text and a white pill action.

**Transfer:** For a playful product, show actual outputs and let a small part of the UI echo their world. A simpler isometric border with a clear dark center is the minimum closing-art equivalent.

**Build:** For the closing artwork, tile SVG cube groups along both side edges and the bottom of a 1032px by 354px panel with 16px corners. Construct each cube from a diamond top and two shaded vertical faces; vary muted forest green, turquoise, tan and rust. Increase density near the corners, leave the central third dark and clear, and place two small pixel-heart shapes at the top left. Center the headline and raised white action over the clearing.

### Business feature illustration

**Only for:** team and business product pages

**Use:** Alternating half-image capability panels.

**Observed:** White interface cards and overlapping deliverables float on restrained sage, blue-gray or warm stone backgrounds. Each 516px square fills one half of a 1032px-wide warm panel; the other half contains vertically centered text. More expressive collaboration imagery uses a painted bright coastal scene behind a white shared-work card.

**Transfer:** Illustrate the actual workflow with sparse readable UI. Alternate muted studio-like backdrops with a bounded painterly scene, not an all-over decorative background.

### Customer photograph

**Only for:** customer proof panels

**Use:** Large testimonial story card.

**Observed:** A warm, natural group photo fills a 1032px by 581px rounded frame. A dark overlay gives white text contrast. Small avatar and attribution sit upper-left; a bold serif quote and short learn-more link anchor the lower-left. Outer text inset is 48px.

**Transfer:** Use an authentic customer or team photograph, not generic technology stock art. Keep faces visible above the quote and darken locally enough for white copy.

### Icons

**Observed:** Small outline SVGs use 2px strokes with rounded caps. Most inline icons are 16px, action arrows 14px–20px and FAQ plus signs 28px. They inherit charcoal or muted gray; footer social marks reverse to white.

**Transfer:** Use a consistent round-capped outline set for functions and compact solid marks only for social identities or clear media actions.

## Section recipes

How recurring sections are built.

### First screen: Hands-on promise opening

**Observed:** The first 900px contains a 56px Sticky navigation, a 44px low-contrast announcement band, then 80px of space before a centered 680px headline group. The 48px serif display spans three balanced lines, followed 12px later by a two-line 16px support sentence. After 48px, the 768px Task composer becomes the main object. Its white input and utility row are fully visible; the Idea tray starts 24px below and extends beyond the first screen. Layers are off-white canvas, dark centered type, then white tool surfaces with fine edges. The primary in-body action is the input's submit arrow, while the header carries a compact conversion pill.

**Transfer:** Default to this editorial promise plus usable example stage for a product landing page. Without an operational input, create a static request-and-output pair that still makes the workflow concrete. A minimal task portal opens with a small 240px by 135px video, a 36px serif question and input; a business page uses a short display promise, two small action pills and a wide video; a playful campaign uses a shorter 46px headline above an interactive scene.

**Avoid:** Do not replace the opening with a left-aligned giant sans headline, a full-bleed saturated gradient or a tiny floating product image beside lots of empty text.

**Text style:** `display` — Libre Baskerville 600 · 48px/1.2

### Editorial section introduction

**Observed:** A centered heading and support line share a 680px measure with a 12px gap. The main content follows after 48px; major sections typically have 80px vertical padding.

**Transfer:** Use this frame to introduce proof, process or objections, without forcing the same section count.

**Text style:** `heading` — Libre Baskerville 600 · 40px/1.2

### Alternating capability chapter

**Observed:** A Painted interface stage occupies one 476px half of the content width; a vertically centered text block occupies the other, separated by 80px. Subsequent rows reverse sides and are separated by 48px. Text uses a sans title, then short explanations with bold lead-ins and em-dash elaborations.

**Transfer:** Explain a different capability in each row and make the image demonstrate that claim.

**Text style:** `capability-title` — -apple-system 600 · 32px/1.2

### Practical comparison

**Observed:** An Editorial section introduction leads into the Comparison table. Thin rules, muted prose and equal content alignment carry the argument; a centered Soft action follows.

**Transfer:** Use when readers need to understand a category difference before exploring details.

### Compact benefit grid

**Observed:** Feature cards fill a two-column grid with 24px gaps inside the 1032px content width. A Soft action sits 48px below the grid.

**Transfer:** Use concise capability or reassurance statements when a large illustration would add little.

### Three-step visual process

**Observed:** Three equal process columns use 24px gaps. Each begins with a 326px by 217px painted UI image with 16px corners, followed by a 16px medium-weight step label and 14px explanatory copy. The group is introduced by a centered serif title and closes with a Soft action.

**Transfer:** Show input, transformation and useful result, or the equivalent meaningful stages for the new product.

### Objection list

**Observed:** An Editorial section introduction precedes a full-width list of FAQ rows. Each closed question is a single horizontal band, not a pill or raised card.

**Transfer:** Resolve setup, ownership, pricing and suitability questions with the same direct tone.

**Text style:** `question` — -apple-system 500 · 16px/1.25

### Contained closing call

**Observed:** The Closing panel holds a centered compact serif heading, an 8px support gap and a Primary button 24px below. It is content-width rather than edge-to-edge, with substantial separation before the Dark colophon.

**Transfer:** End the argument with one next step. Campaigns can replace the soft panel with a product-specific illustrated world; enterprise upgrade calls use a dark image-backed 1032px by 400px variant with white headline and a white action.

**Text style:** `heading-close` — Libre Baskerville 600 · 40px/1.2 · tracking -0.02em

### Editorial colophon ending

**Observed:** Dark colophon begins with a left-aligned two-line italic serif thought. A 48px gap leads to seven compact link groups. The bottom utility row aligns copyright left and social marks plus an outlined language selector right. The full desktop footer is 748px tall and shared by the short portal and longer product pages.

**Transfer:** Write an original concise brand philosophy for the italic line; scale the navigation groups to the new information architecture without losing the light-to-dark ending contrast.

**Text style:** `footer-thought` — Libre Baskerville 400 italic · 36px/44px

### Browsable output proof

**Only for:** products with inspectable example outputs

**Observed:** The large output showcase has a centered serif heading, support, a row of small category tabs after 48px and a wide media frame below. The game variant uses three columns of thumbnail cards, 20px gaps, genre filter pills and compact play/remix links.

**Transfer:** Let readers inspect plausible output breadth; keep filters and navigation subordinate to the output.

### Business proof and pricing

**Only for:** team and business product pages

**Observed:** Alternating half-image panels establish capabilities; a tabbed collaboration panel follows. A wide dark photographic security banner sits above four compact icon-led assurances. A single centered Pricing panel is followed by a Customer photograph story, FAQ rows and a dark image-backed enterprise invitation.

**Transfer:** Select appropriate business proof and a real pricing model; keep certification or customer detail subordinate to the product story.

## Page flow

**Storyline:** Promise and usable invitation → capability or output proof → practical process and control → objections → contained conversion invitation → editorial dark colophon.

### Minimal task-entry portal

1. **Invitation** — Small video above a conversational serif question and broad task input; outlined suggestion chips follow.
2. **Closing identity** — The light full-screen entry area gives way directly to the dark italic-thought footer and dense navigation.

**Transfer:** Use for a product whose central interaction can stand alone without an extensive explanation.

### Interactive creator-product landing page

1. **Promise** — Short category headline over a faint game-like interactive stage and task composer.
2. **Output proof** — Filterable three-column playable gallery with remix actions.
3. **Capability demonstration** — A large adjustable visual example sits beside three white explanatory cards.
4. **Process** — Three illustrated steps explain creation, followed by publishing/sharing steps and adjacent-tool cards.
5. **Objection handling** — Full-width FAQ rows.
6. **Closing call** — Isometric illustrated game-world banner and raised white action, followed by the shared dark footer.

**Transfer:** Useful for creative tools: show outputs early and let the workflow feel tangible.

### Default product landing page

1. **Promise and invitation** — Centered editorial title and support above a task composer and example tray.
2. **Differentiation** — Compact integration group and practical comparison table.
3. **Capability chapters** — Alternating painted product scenes with sans explanatory titles.
4. **Control and process** — Two-column benefit cards, then three illustrated steps.
5. **Output proof** — Tabbed wide showcase of real examples.
6. **Objection handling** — Question rows.
7. **Closing call** — Soft contained conversion panel, then shared dark editorial footer.

**Transfer:** Use as the default narrative vocabulary for a new marketing page, shortening or reordering proof to match the product.

### Team-oriented business conversion page

1. **Promise** — Centered serif title, short support, paired primary/secondary actions and a wide video.
2. **Social proof** — Quiet partner logo row.
3. **Capability chapters** — Alternating half-image warm panels and tabbed collaboration demonstration.
4. **Trust** — Wide dark certification artwork with four security assurances below.
5. **Pricing** — One configurable white plan card with blue selected cadence.
6. **Customer proof** — Large photographic story with white serif quotation.
7. **Objections and expansion** — FAQ rows lead to an enterprise invitation and shared dark footer.

**Transfer:** Use for a buying group that needs collaboration, governance, cost and customer reassurance in addition to product proof.

## Writing

Direct and encouraging, with editorial confidence and little technical ceremony. Promises emphasize useful finished work; the explanations name mechanisms and controls plainly.

**Do not copy:** Do not reuse the brand name, hand logo, announcement wording, proprietary illustrations, customer identities, quotations, usage numbers, prices, certifications or performance claims. Replace them with the new product's true assets and substantiated facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you or your team. Refer to the product by name when describing what it does; use imperative verbs for actions and process steps.
- **Rhythm:** Short sentence-case headlines alternate with longer benefit-led promises. Support is usually one or two sentences; explanatory rows use brief bold lead-ins followed by em-dash elaboration. Avoid exuberant punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Useful outcome plus removal of a practical barrier. | 5–9 words | “Launch business applications without engineering resources”<br>“Make your team AI-native today” |
| Supporting line | Name use cases, then contrast a faster practical outcome with the old process. | 15–25 words | “From internal tools to customer-facing SaaS — deploy production-ready apps in minutes, not months.” |
| Capability heading | Concrete capability or rhythmic series of short parallel promises. | 4–10 words | “Real applications. Real backend. Real power.”<br>“Change anything as you play” |
| Primary action | Verb plus the useful activity, without elaborate persuasion. | 2–3 words | “Start Building”<br>“Start creating”<br>“Book a Demo” |
| Reassurance | State control in plain declarative language; short sentences accumulate confidence. | 10–25 words | “You own everything you build. Export your code, connect your domain, and take your application anywhere. No lock-in.” |
| Footer thought | A brief antithetical statement, broken into two italic lines. | 4–7 words | “Less structure, more intelligence.” |

**Words and phrasing to use:** build; describe; your; ready-to-go; share; launch; control; no lock-in; plain English

**Avoid:** revolutionary paradigm; unparalleled synergy; next-generation disruption; magical everything; excessive developer jargon

**Rules:**

- Connect each broad promise to a visible workflow, deliverable or control.
- Use concrete nouns for capabilities; explain benefits without turning every sentence into a slogan.
- Process labels begin with verbs and follow the reader's activity rather than internal architecture.
- FAQ questions sound like actual user questions about prerequisites, editing, ownership and cost.

## Do's and Don'ts

### Do

- Keep centered headline groups to a 680px measure within the 1032px content frame.
- Use 48px/1.2 serif for the opening and 40px/1.2 for default section headings.
- Pair painted media with crisp white functional UI; keep texture off interface text.
- Use 24px card padding and 24px grid gaps for compact benefit sections.
- Repeat the 40px warm-gray action pill after explanatory sections instead of making every action visually primary.
- Preserve the 36px/44px italic two-line thought at the top of a charcoal footer.
- Keep FAQ questions at 16px/20px with 24px vertical inner padding.
- Let blue identify links and selections while the page remains predominantly off-white and charcoal.

### Don't

- Do not use pure white as the uninterrupted page canvas; white is the brighter tool surface against #f8f8f7.
- Do not turn all section headings into 32px sans titles; those explain capabilities rather than frame chapters.
- Do not apply the 22px input radius to every object; feature cards use 12px and large media 16px.
- Do not add deep black drop shadows to the main tool: its lift is only 0px 12px 32px at 0.02 alpha.
- Do not expand the sparse link blue into full-section brand-blue backgrounds.
- Do not style FAQ rows as separate floating 24px-rounded cards.
- Do not use the business pricing blue wash on every benefit card; it denotes selection.
- Do not apply arcade monospace labels or pixel motifs to an ordinary business landing page.

## Motion and responsive

### Motion

**Observed:**

- The 56px header remains sticky while the page scrolls.
- Controls and examples support input, tab selection, carousel navigation and expandable questions; only settled visual states establish their appearance.

**Transfer:**

- Keep the input and bounded product demonstrations as the interactive focus rather than moving decorative elements across the page.

**Unknown:**

- Transition durations, easing, full interaction-state colors and animation sequences are not established.

### Responsive

**Observed:**

- The hero heading declares a 32px base size and 48px wider-screen variant; section headings declare 28px and 40px variants.
- Class structure declares a single-column base for benefit grids and split rows, with two-column wider variants; footer columns reduce from seven to two.
- The primary header links are hidden in the narrow base layout.

**Transfer:**

- Stack the painted demonstration and its explanation on narrow screens; retain their pairing and keep example UI legible.
- Keep the task input full-width within side gutters, and use the declared 32px hero and 28px section-heading hierarchy rather than shrinking the entire desktop page.
- Preserve the dark colophon and italic thought while letting link groups flow into two columns.

**Unknown:**

- Exact breakpoint widths, mobile navigation controls and final mobile spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
