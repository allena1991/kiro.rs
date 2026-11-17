# Airtable — systems with vivid edges

## Overview

A bright, architectural marketing style that makes complex software feel approachable and useful. Warm-white grids and rounded grotesk typography hold richly colored interface scenes, with dark editorial cards and a graphic blue-and-violet finale providing contrast. It suits collaborative tools and operational products with substantial capabilities to explain, balancing spacious introductions with dense, practical proof.

### Essentials

- A conversational headline sits above a working system: centered 79.2px/1.1 type at weight 550, a 16px support line, paired actions, then a 1024px-wide layered interface scene.
- The page is an open ledger, not a pile of floating cards: 1344px shells with continuous 1px #e0dcdb side rails, zero-gap two- and three-column grids, and 40px interior padding.
- Actions have two distinct silhouettes: ordinary landing-page buttons are 48px high with 4px corners and 12px 24px padding; the global header uses 12px corners and 16px 24px padding.
- Color lives in contained demonstrations and punctuation: the main reading canvas stays white, feature art uses saturated magenta, resource labels use pink, yellow and cyan, and broad cobalt is reserved for the graphic call to action.
- Interfaces become dimensional evidence: place a legible main application window in front of faint rectilinear bars, overlap two or three contextual cards, and crop the scene at its lower edge. When no interface exists, construct an equivalent workflow diagram rather than substituting generic stock art.
- A stepped-bar graphic and a white statement card form the signature conversion device: a 596px cobalt band, violet horizontal stair-step bars, and an approximately 874px-wide square-edged card with 40px padding and a 64px/1.1 closing line.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Graphic cobalt | `#012978` | `--color-cobalt` | background | Backing of the stepped conversion graphic. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Resource yellow | `#ffcd05` | `--color-resource-yellow` | text, accent | Second category accent on dark resources. |
| Resource cyan | `#35cbfd` | `--color-resource-cyan` | text, accent | Third category accent on dark resources. |
| Stepped violet | `#a640f7` | `--color-violet` | accent | Vivid stair-step bars over cobalt; match the flat electric-violet appearance. |
| Announcement link | `#254fad` | `--color-link` | link | Small announcement links and navigation emphasis. |
| Demonstration magenta | `#7a015c` | `--color-magenta` | background | Saturated patterned backing for product demonstration scenes. |
| Resource pink | `#f797ef` | `--color-resource-pink` | text, accent | Small uppercase resource categories on dark cards. |
| Announcement blue wash | `#f0f6ff` | `--color-promo` | background | Thin announcement strip. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Platform black | `#161616` | `--color-ink` | text, action, background | Default headline, button and editorial-dark ink. |
| Shell navy-black | `#181d26` | `--color-shell-ink` | text, action, border | Global navigation, support-page headings and header actions. |
| Slate body | `#333840` | `--color-body` | text | Footer links and integration-campaign headings. |
| Blue-gray support | `#525965` | `--color-muted` | text | Visible result of rgba(4,14,32,0.69) on white; subdued supporting paragraphs. |
| Warm hairline | `#e0dcdb` | `--color-rule` | border | Continuous section rails, grid divisions and separators. |
| Warm panel | `#f8f6f6` | `--color-warm-panel` | surface | Media backing and secondary tab bands. |
| Cool utility white | `#f8fafc` | `--color-utility` | background, surface | Footer utility bar and campaign setup cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, white content cards and inverse type. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan action blue | `#166ee1` | `--color-pricing-action` | action, link | Recommended-plan pill and pricing help links. |
| pricing pages | Recommended-plan edge | `#0d52ac` | `--color-pricing-edge` | border, background | Recommended plan outline and popularity ribbon. |
| pricing pages | Recommended-plan wash | `#f8fbff` | `--color-pricing-tint` | surface | Visible half-opacity #f0f6ff over white; recommended plan only. |
| pricing pages | Pricing ink | `#1d1f25` | `--color-pricing-ink` | text, border | Plan names, comparison copy and outlined pricing actions. |
| integration campaigns | Campaign paragraph gray | `#333333` | `--color-campaign-body` | text | Longer integration-campaign paragraphs. |
| pricing pages | Plan edge | `#c4c7cd` | `--color-pricing-rule` | border | Plan outlines and small new-feature badges. |

## Typography

- **ATSeasonSans** — Default marketing headlines, labels, card copy and global shell. Friendly contemporary grotesk with broad rounded bowls, open counters and moderate medium weights. If unavailable, use **Inter**. Use 500–650 weights without introducing negative display tracking. Font stack: "ATSeasonSans", "Inter", Haas, system-ui, sans-serif.
- **Haas** — Hero supporting line and integration-campaign text. Neutral neo-grotesk, less rounded and lighter in campaign headings. If unavailable, use **Roboto**. Use regular 400 for headings and paragraphs. Font stack: "Haas", "Roboto", Arial, system-ui, sans-serif.
- **Inter Display** (only for pricing pages) — Plan names, prices and comparison tables. Compact display grotesk with fractional medium weights and slightly negative tracking. If unavailable, use **Inter**. Font stack: "Inter Display", "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | ATSeasonSans | 550 | 79.2px | 1.1 | normal | fixed | Centered two-line default hero promise. |
| closing | ATSeasonSans | 550 | 64px | 1.1 | normal | fixed | Large left-aligned statement inside the graphic conversion card. |
| heading | ATSeasonSans | 550 | 48px | 1.15 | normal | fixed | Primary capability chapter headings. |
| quote | ATSeasonSans | 550 | 32px | 1.25 | normal | size clamp(20px, 2.5vw, 32px) | Customer statement in a large white panel. |
| card-heading | ATSeasonSans | 550 | 24px | 1.3 | normal | size clamp(18px, 2vw, 24px) | Capability names and large tab labels. |
| resource-title | ATSeasonSans | 650 | 20px | 1.35 | normal | fixed | White titles on dark editorial cards. |
| body | Haas | 400 | 16px | 1.35 | 0.01em | fixed | Short supporting line below the opening promise. |
| card-body | ATSeasonSans | 550 | 16px | 1.35 | normal | fixed | Concise capability descriptions. |
| button | ATSeasonSans | 650 | 16px | 1.35 | normal | fixed | Default landing-page buttons. |
| navigation | ATSeasonSans | 650 | 16px | 1.3 | 0.01em | fixed | Global navigation and header actions. |
| footer-link | ATSeasonSans | 550 | 16px | 1.35 | 0.01em | fixed | Footer directory links. |
| eyebrow | ATSeasonSans | 650 | 14px | 1.35 | normal | fixed | Plain sentence-case label above the main promise. |
| resource-label | ATSeasonSans | 550 | 12px | 1.35 | normal, uppercase | fixed | Colored category markings on resource cards. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Inter Display | 475 | 64px | 1 | -0.0025em | fixed | Paid plan prices. |
| focused feature and company pages | compact-display | ATSeasonSans | 500 | 48px | 1.15 | normal | fixed | More compact centered opening statement. |
| pricing pages | pricing-display | Inter Display | 475 | 44.8px | 1.25 | -0.0036em | fixed | Centered plan-selection headline. |
| integration campaigns | campaign-heading | Haas | 400 | 40px | 1.2 | normal | fixed | Centered hero and demonstration chapter headings. |
| focused feature and company pages | compact-heading | ATSeasonSans | 500 | 32px | 1.25 | normal | fixed | Centered explanatory headings and FAQ title. |
| pricing pages | plan-heading | Inter Display | 475 | 28px | 1.25 | -0.0057em | fixed | Plan names and pricing help headings. |
| integration campaigns | campaign-body | Haas | 400 | 20px | 1.625 | normal | fixed | Longer text beside conceptual product illustrations. |
| focused feature and company pages | compact-card-heading | ATSeasonSans | 600 | 18px | 1.35 | 0.01em | fixed | Numbered steps, small benefits and understated statistics. |
| pricing pages | pricing-question | Inter Display | 575 | 17px | 1.5 | -0.0094em | fixed | Pricing FAQ questions. |
| feature-page FAQs | question | ATSeasonSans | 600 | 16px | 1.35 | 0.01em | fixed | Accordion questions. |
| integration campaigns | campaign-button | Haas | 500 | 16px | 1.35 | 0.01em | fixed | Connection and setup-guide actions. |
| pricing pages | plan-button | Inter Display | 575 | 16px | 1.25 | -0.01em | fixed | Plan-selection pills. |
| focused feature and company pages | caption | ATSeasonSans | 500 | 14px | 1.35 | 0.02em | fixed | Dense benefit support and FAQ answers. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Default display and chapter headings use normal tracking, not fashionably compressed spacing. Weight 550 carries the hierarchy without a heavy bold face.
- Small body and footer type use 0.01em tracking; dense 14px explanations use 0.02em. Pricing is a separate typographic system with -0.2px tracking.
- The compact feature/company hierarchy is 48px → 32px → 18px → 14px; do not average it into the default 79.2px → 48px → 24px hierarchy.

## Layout

**Density:** Airy introductions and chapter bands, with dense edge-to-edge proof grids below.

### Spacing

**Spacing system:**

- **horizontal grid** 8px, horizontal — Dominant horizontal spacing increment; smaller 4px and 12px details serve tight controls.

| Value | Use |
| --- | --- |
| 8px | Card title-to-body gap. |
| 12px | Footer link stack and compact details. |
| 16px | Paired action gap and resource label-to-title gap. |
| 24px | Hero stack rhythm and tab padding. |
| 32px | Compact card padding and campaign grid gutters. |
| 40px | Default cell padding and separation before hero media. |
| 48px | Outer desktop shell margin and footer column gap. |
| 64px | Opening top padding and compact chapter bands. |
| 80px | Primary chapter lead-in and resource-section bottom space. |
| 128px | Integration and customer-story chapter breathing room. |

### Containers and grids

- **ruled shell**: max width 1344px · side padding 0px. Centered main shell; leaves 48px outside each rail at 1440px.
- **shell copy**: max width 1264px · side padding 40px. Text lives inward of the shell rules, not flush against them.
- **hero object**: max width 1024px. Centered wide interface composition below the opening actions.
- **capability grid**: 2 columns · gap 0px. Equal 671px desktop cells joined by shared rules; copy above a 360px-tall visual.
- **resource grid**: 3 columns · gap 0px. Three adjoining dark editorial cards about 448px wide.
- **footer directory**: max width 1248px · 5 columns · gap 48px. Inset five-column link directory beneath a compact navigation/social row.
- **campaign grid** (only for integration campaigns): max width 1536px · 12 columns · gap 32px · side padding 32px. Twelve-column grid with centered 1114px media and asymmetric prompt tiles.
- **plan grid** (only for pricing pages): max width 1250px · 4 columns · gap 16px. Four parallel plan columns with 297px card faces and aligned internal content.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | landing actions | 4px |
|  | header actions | 12px |
|  | editorial cells | 0px |
| integration campaigns | campaign panels | 16px |
| integration campaigns | prompt tiles | 32px |
| pricing pages | plan actions | 9999px (pill) |
| pricing pages | plan cards | 12px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| header haze | `0px 0px 20px 0px rgba(15,48,106,0.05)` | Very light cool shadow below the white navigation. |

### Surfaces

#### White ledger · level 0

**Use:** Default page canvas and ruled content chapters.

**CSS:** `background: #ffffff; color: #161616`

**Observed:** A white field with persistent vertical shell rails; the grid, not elevation, organizes the page.

**Transfer:** Let fine shared borders carry most grouping.

#### Ruled shell · level 0

**Use:** Main section frame.

**CSS:** `max-width: 1344px; margin-inline: auto; border-left: 1px solid #e0dcdb; border-right: 1px solid #e0dcdb`

**Transfer:** Align successive section borders into continuous page-length rails.

#### Warm visual well · level 1

**Use:** Capability illustrations and inactive tab bands.

**CSS:** `background: #f8f6f6; overflow: hidden`

**Observed:** Flat, square-edged backing without a card shadow.

**Transfer:** Use it to distinguish media from adjacent white copy.

#### Dark editorial band · level 0

**Use:** Resources and customer proof framing.

**CSS:** `background: #161616; color: #ffffff; border-color: rgba(255,255,255,0.23)`

**Observed:** Internal hairlines become translucent white; customer quotes sit on white within this dark frame.

**Transfer:** Use a concentrated dark chapter rather than turning the whole page dark.

#### Graphic conversion field · level 0

**Use:** Signature statement-and-action stage.

**CSS:** `background: #012978; position: relative; overflow: hidden`

**Observed:** Violet stepped bars run behind a square white card, not across its text.

**Transfer:** Recreate using Stepped system bars and a white statement card.

#### Recommended plan · level 1

**Only for:** pricing pages

**Use:** Single promoted plan column.

**CSS:** `background: rgba(240,246,255,0.5); border-left: 1px solid #0d52ac; border-right: 1px solid #0d52ac`

**Observed:** A dark-blue top ribbon and blue action distinguish it from neutral neighboring plans.

**Transfer:** Promote only one plan, preserving comparable vertical alignment.

## Components

### Global navigation

**Use:** Persistent site orientation and conversion access.

**CSS:** `background: #ffffff; position: sticky; top: 0px; z-index: 4; box-shadow: 0px 0px 20px 0px rgba(15,48,106,0.05)`

**Text style:** `navigation` — ATSeasonSans 650 · 16px/1.3 · tracking 0.01em

**Observed:** A 42px pale-blue announcement strip sits above a 79px main row. Brand mark at left, sentence-case category links and small chevrons, actions and login at right; the brand mark simplifies while scrolling.

**Transfer:** Keep the global shell visually distinct from the smaller landing actions.

### Primary button

**Use:** Main landing-page conversion.

**CSS:** `background: #161616; color: #ffffff; border: 1px solid #161616; border-radius: 4px; padding: 12px 24px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — ATSeasonSans 650 · 16px/1.35

**Observed:** Pairs with Secondary button in a centered row with 16px separation; closing cards align the same pair to the left.

**States:** Declared: hover background and border #404040 with white text; focus-visible 2px solid #161616 outline with 2px offset.

### Secondary button

**Use:** Sales-assisted path beside the primary conversion.

**CSS:** `background: #ffffff; color: #161616; border: 1px solid #161616; border-radius: 4px; padding: 12px 24px; height: 48px`

**Text style:** `button` — ATSeasonSans 650 · 16px/1.35

**Observed:** Same typographic strength and height as the primary action, but outlined rather than visually faded.

**States:** Declared: hover background #f5f5f5 with #161616 text; focus-visible 2px solid #161616 outline with 2px offset.

### Header action

**Use:** Global sign-up conversion.

**CSS:** `background: #181d26; color: #ffffff; border: 1px solid #181d26; border-radius: 12px; padding: 16px 24px`

**Text style:** `navigation` — ATSeasonSans 650 · 16px/1.3 · tracking 0.01em

**Observed:** About 55px tall; an outlined demo action sits immediately before it.

**States:** Declared: hover background and border rgba(4,14,32,0.69); focus-visible 2px solid rgba(4,14,32,0.69) outline with 2px offset; active background rgba(7,12,20,0.82).

### Capability cell

**Use:** A substantial capability explained through short copy and a visual.

**CSS:** `display: flex; flex-direction: column; border-right: 1px solid #e0dcdb; border-bottom: 1px solid #e0dcdb`

**Text style:** `card-heading` — ATSeasonSans 550 · 24px/1.3

**Observed:** White copy block with a title, one short sentence and a small arrow link above a Warm visual well. Copy uses 40px padding and 8px internal gaps; illustration takes roughly two thirds of the cell height.

**Transfer:** Use a specific product mechanism in each cell, not an abstract value proposition.

### Feature tab

**Use:** Switch a large explanatory product scene.

**CSS:** `background: #ffffff; border-bottom: 1px solid #181d26; padding: 24px 40px; display: flex; align-items: center; gap: 8px`

**Text style:** `card-heading` — ATSeasonSans 550 · 24px/1.3

**Observed:** An active 80px row has a small black square marker. Its explanatory copy expands above the label; inactive rows are warm gray, and the scene occupies the wider right portion.

**States:** Declared: focus-visible 2px solid #161616 outline with -2px offset.

**Transfer:** Use short conceptual labels; retain the asymmetry between narrow explanation and broad demonstration.

### Resource card

**Use:** Editorial or educational proof.

**CSS:** `background: #161616; padding: 40px; border-bottom: 1px solid rgba(255,255,255,0.23); display: flex; flex-direction: column; gap: 16px`

**Text style:** `resource-title` — ATSeasonSans 650 · 20px/1.35

**Observed:** A colored uppercase category appears above a white title in a roughly 167px text band; a 447px by 270px image continues directly below it. Neighboring cards share thin inverse dividers.

**Transfer:** Keep the category accent tiny and let the cover or interface collage carry the richer palette.

### Footer directory

**Use:** Complete end-of-page navigation.

**CSS:** `display: grid; grid-template-columns: repeat(5, 1fr); gap: 48px`

**Text style:** `footer-link` — ATSeasonSans 550 · 16px/1.35 · tracking 0.01em

**Observed:** A top navigation row places the mark and key links left and social icons right. A fine rule separates five link columns; stacks use 12px gaps. A cool full-width utility strip with legal links and app badges ends the page.

**Transfer:** Preserve the structured directory ending even when the preceding closing call is more expressive.

### FAQ row

**Only for:** feature-page FAQs

**Use:** Resolve specific adoption objections.

**CSS:** `display: flex; flex-direction: column; border-bottom: 1px solid #e0dcdb; padding-bottom: 24px`

**Text style:** `question` — ATSeasonSans 600 · 16px/1.35 · tracking 0.01em

**Observed:** Full-width question trigger and right-edge chevron; 14px answer below when expanded. The list occupies the right two thirds of a ruled section, with a stationary title on the left.

**Transfer:** Use practical questions and compact answers rather than decorative icon cards.

### Plan action

**Only for:** pricing pages

**Use:** Selection action repeated across comparable plans.

**CSS:** `background: #ffffff; color: #1d1f25; border: 2px solid #1d1f25; border-radius: 9999px; padding: 16px; height: 56px`

**Text style:** `plan-button` — Inter Display 575 · 16px/1.25 · tracking -0.01em

**Observed:** Outlined full-width pills on ordinary plans; the promoted plan uses a filled #166ee1 pill without the thick border, 52px tall. The comparison header repeats a smaller-width version.

### Campaign guide action

**Only for:** integration campaigns

**Use:** Setup documentation beside a connection action.

**CSS:** `color: #181d26; border: 1px solid #181d26; border-radius: 12px; padding: 16px 24px; height: 56px; backdrop-filter: blur(6px); box-shadow: 0px 0px 1px 0px rgba(0,0,0,0.32), 0px 0px 2px 0px rgba(0,0,0,0.08), 0px 1px 3px 0px rgba(0,0,0,0.08), inset 0px 0px 0px 1px rgba(1,20,53,0.12)`

**Text style:** `campaign-button` — Haas 500 · 16px/1.35 · tracking 0.01em

**Observed:** A softer, more rounded and lightly elevated action system than ordinary product landing pages; its primary companion is dark-filled.

## Imagery and graphics

### Layered working interface

**Use:** Main opening object and product proof.

**Observed:** A dark, detailed application window with a plum sidebar, colorful chips and subtle edge shadow floats over a barely visible rectilinear pattern. Small white instruction or result cards overlap its top and lower corners. It is wide and front-facing rather than tilted, with the bottom allowed to extend beyond the first viewport.

**Transfer:** Use a real interface or an honest simplified reconstruction of the new product's workflow. Minimum version: a readable central table or board, a side navigation, and two contextual task/result cards. Keep microcopy subordinate to the marketing headline.

### Stepped system bars

**Use:** Signature background device behind the hero object and graphic conversion card.

**Observed:** Flat horizontal rectangles of unequal lengths form staggered stair-step tracks. The opening uses an almost-white low-opacity version; the conversion field uses electric violet over deep cobalt. Edges are crisp, without blur or gradients.

**Transfer:** Retain this rectilinear rhythm with different content; it supplies continuity even when product imagery is unavailable.

**Build:** Use an SVG with a 1440 by 596 viewBox over cobalt. Construct four to six tracks from adjacent 360px-wide rectangles, varying heights from 8px to 52px and offsetting each segment vertically to descend in steps. Repeat at several vertical intervals and clip to the field. Fill with flat violet. Put the white card on a higher layer. For the opening, reuse the geometry in black at 0.05 opacity behind the lower half of the product scene.

### Patterned demonstration stage

**Use:** Broad media area beside feature tabs.

**Observed:** A saturated magenta rectangular well holds a front-facing product table and a floating white natural-language prompt. Alternating dark and bright horizontal rectangles create a compressed woven/checkered field; the UI fills most of the well and crops at its edges.

**Transfer:** Show one task and its result, not an entire desktop collage. The minimum equivalent is a clear UI panel and one prompt on a constructed patterned backing.

**Build:** Fill a 916px by 700px stage with magenta. Overlay rows of rectangular bands in rgba(0,0,0,0.2), alternating widths near 90px, 180px and 360px; offset vertical seams across rows. Place the interface inset from the top and sides, and the prompt card above it. No photographic texture or glow is needed.

### Capability diagrams

**Use:** Warm visual wells under capability descriptions.

**Observed:** Simplified white application cards, enlarged prompt fields, small linked service nodes, dotted connector lines, square-pixel data matrices and staggered miniature app panels. The art is legible in concept rather than a dense browser screenshot.

**Transfer:** Reduce each mechanism to a few meaningful nodes or interface fragments on warm gray. Keep a clear visual hierarchy and use the new product's true categories.

**Build:** For a data-system diagram, place four white circular service nodes on the left, connect with dashed 1px gray paths to a right-hand matrix of 12px gray squares on 24px centers, and clear a rectangle in the matrix for a short scale or outcome label. For an app-library diagram, overlap three white panels diagonally, each with a distinct dark header and three short functional rows.

### Editorial covers and collages

**Use:** Lower halves of Resource cards.

**Observed:** Rich magenta publication covers, green-backed interface collages and dark-red application panels alternate beneath a consistent black text band. Covers are front-facing or gently dimensional, with strong color fields rather than lifestyle photography.

**Transfer:** Create new cover artwork or a small montage of genuine product views. Preserve the image-to-text split and high color concentration.

### Natural work photography

**Only for:** company pages and customer stories

**Use:** Humanize product purpose, workplace locations and customer proof.

**Observed:** Warm daylight on a laptop and pale timber desk; large office windows, green plants and natural interiors; customer event portraits crop vertically beside wide quote panels. Photography is rectangular and editorial, not circular headshots scattered as decoration.

**Transfer:** Choose natural light, believable working environments and a warm material palette. Keep a single substantial image rather than a stock-photo mosaic.

### Campaign walkthrough media

**Only for:** integration campaigns

**Use:** Hero, setup instructions, use-case chapters and prompt examples.

**Observed:** Large 1114px-wide 16:9 recordings show two tools working side by side. Setup cards isolate enlarged controls on pale cool backing. Prompt tiles are pale-backed images of white rounded composer cards, with small warm-colored send buttons; their layouts alternate a wide tile and a narrow tile, then two equal tiles.

**Transfer:** Demonstrate an actual cross-tool task. Minimum prompt artwork is a white composer with a realistic short task, a small add control and a send arrow, without imitating another product's identity.

### Icons

**Observed:** Utility icons are compact and mostly monochrome: 12px filled navigation chevrons, 16px directional arrows with about 1.3px round strokes, and 16px white playback strokes inside 40px circular controls. Integrations appear as 56px marks in a rigid grid; pricing uses small checks and information symbols.

**Transfer:** Use simple line arrows and chevrons aligned to the type. Keep colorful vendor or capability marks inside demonstrations and integration grids, not beside every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Centered system opening

**Observed:** A white global shell occupies the first 121px, followed by a ruled hero with 64px top padding. A small centered Eyebrow precedes a two-line Display promise spanning roughly two thirds of the viewport in actual glyph width. A muted single-line Body sits 24px below it; Primary button and Secondary button follow after another 24px. Behind the media is faint stepped geometry; in front is a 1024px by 451px layered interface scene, separated from the actions by 40px. In the first 900px the entire headline, support and actions are visible, plus most of the main interface and overlapping cards; the lower interface edge and subsequent proof strip fall below the fold.

**Transfer:** Use a two-part human-centered promise and one credible working scene. Without existing product media, build the simplified Layered working interface. Focused feature and company pages use Compact display with a 16px support gap; integration campaigns use Campaign heading and a centered 1114px recording; pricing opens directly with Pricing display and aligned plan columns.

**Avoid:** Do not turn this into a split-screen hero, replace the working scene with a giant icon, or stretch the headline into an edge-to-edge single line.

**Text style:** `display` — ATSeasonSans 550 · 79.2px/1.1

### Ruled chapter lead

**Observed:** A full-shell heading band uses 80px top padding, 40px side and bottom padding, and a 1px lower rule. Heading is left-aligned for capability chapters or centered over the interactive feature panel. Compact variants use a small bordered eyebrow, a 32px heading and a 16px support gap.

**Transfer:** Use a plain statement of the capability or outcome, then let the next grid carry detail.

**Text style:** `heading` — ATSeasonSans 550 · 48px/1.15

### Proof rail

**Observed:** A centered trust line precedes six monochrome logos in equal, adjoining ruled cells; the default strip is 180px tall. It feels like part of the page's ledger rather than a floating carousel.

**Transfer:** Use real proof marks or concise evidence categories in equally weighted cells.

### Asymmetric feature demonstration

**Observed:** Below a centered chapter title, a roughly 426px explanation rail sits beside a 916px-wide Patterned demonstration stage. Feature tab expands the selected explanation; inactive bands remain shallow. The saturated media side is 700px tall.

**Transfer:** Use two or three genuinely different mechanisms, each with its own scene, and keep the interaction's active state visually clear.

### Integration wall

**Observed:** A left-hand stack of three 48px statements, support text and an outlined action sits beside four narrow, ruled columns of integration marks. The 567px section has 128px top and bottom breathing room; logo columns extend vertically and are clipped.

**Transfer:** Pair cross-tool reach or ecosystem breadth with a rigid logo or capability wall, not a loose cloud of badges.

### Capability ledger

**Observed:** Capability cell forms a two-column, two-row zero-gap grid. Each cell is about 671px by 542px, with white copy above Warm visual well. Feature-page variants use three or four adjoining smaller columns with 32px padding and Compact card heading.

**Transfer:** Use equal cells for equal conceptual weight; combine short mechanism-focused copy with diagrams.

### Customer statement stage

**Observed:** Dark editorial band encloses a wide white statement panel and a narrower vertical customer photograph. The quote is 32px/1.25, with identity and role beneath; a segmented 2px progress track and 40px circular previous, pause and next controls sit below.

**Transfer:** Use authentic customer evidence and a substantial photograph. Keep quote text dark on white even though the surrounding chapter is dark.

**Text style:** `quote` — ATSeasonSans 550 · 32px/1.25

### Editorial resource row

**Observed:** A left-aligned Heading introduces three contiguous Resource cards. Colored Resource label and white Resource title sit above full-width images; no gaps or rounded tile treatment separate the cards.

**Transfer:** Offer useful next steps through distinct formats such as a guide, an example and a demonstration.

### Graphic statement conversion

**Observed:** Graphic conversion field spans the page at 596px tall. Stepped system bars pass behind a centered white square-edged card about 874px wide with 40px padding. A left-aligned Closing statement and 40px action gap make this a decisive visual finish; compact company/feature variants use 48px type and a 471px–526px field.

**Transfer:** Use a short invitation or verified proof statement relevant to the new product. Preserve the graphic device and white card even without any product-specific art.

**Text style:** `closing` — ATSeasonSans 550 · 64px/1.1

### Directory ending

**Observed:** Footer directory follows 64px of separation after the main content. Its top row, rule, five columns and cool utility strip repeat across page types; the full ending is about 579px tall. Pricing puts help links and a narrow centered FAQ before this shared directory instead of a graphic call to action.

**Transfer:** Give the page a useful, fully resolved end rather than stopping after the promotional band.

### Feature objection handling

**Only for:** feature-page FAQs

**Observed:** A ruled section splits approximately one third title and two thirds FAQ row list. The list has a left rule, 40px padding and 24px row gaps; one answer is expanded while the rest remain question-height.

**Transfer:** Place unresolved practical questions here; it can follow the graphic conversion band without weakening that visual climax.

### Plan choice and comparison

**Only for:** pricing pages

**Observed:** A centered Pricing display precedes four outlined columns with 12px outer corners, aligned names, descriptions, 64px prices, billing notes and Plan actions. One plan has Recommended plan backing and a popularity ribbon. A long comparison uses a left feature-name column, four centered plan columns, 36px rows, 64px category separations and a persistent plan/action header.

**Transfer:** Keep commercial comparisons factual and scannable. Use dotted underlines for explainable terms and reserve filled blue for the promoted choice.

### Company proof and places

**Only for:** company pages

**Observed:** Compact centered introduction gives way to a large photo/text split, a ruled trust rail and three-cell proof bands. Statistics are understated 18px semibold values with 14px captions rather than giant numerals. A five-tab location selector spans the shell above a narrow address/action column and broad daylight office image; an awards wall repeats the gridded logo treatment.

**Transfer:** Use evidence appropriate to the organization: scale, outcomes, locations or community. Preserve the modest numeric hierarchy and real photography.

### Campaign demonstration chapters

**Only for:** integration campaigns

**Observed:** Centered 40px headings, short support lines and 56px actions introduce 1114px by 627px recordings. Alternating split sections use 40px text and 20px/1.625 paragraphs beside 680px-wide conceptual illustrations. Setup is a three-column row of 437px-wide, 16px-radius cool cards with 32px gutters.

**Transfer:** Organize around distinct tasks and stages of adoption; show the result as clearly as the initiating conversation.

### Campaign prompt gallery and close

**Only for:** integration campaigns

**Observed:** An asymmetric prompt-image grid uses 32px gaps and 32px corners: a 907px tile beside a 437px tile, then two 672px tiles. The ending becomes a restrained 1376px-wide bordered, 16px-radius white panel with 40px padding, a 32px regular heading, support line and one connection action before Footer directory.

**Transfer:** Provide ready-to-use examples for the new workflow; keep this campaign ending separate from the default graphic closing treatment.

## Page flow

**Storyline:** Human-centered promise → visible working proof → capability mechanisms → credible adoption evidence → useful next steps → decisive action → practical directory.

### Broad platform landing page

1. **Promise** — Large centered two-line headline with a layered working scene.
2. **Social proof** — Monochrome ruled logo rail.
3. **Mechanisms** — Interactive asymmetric demonstration, ecosystem wall and two-column capability ledger.
4. **Customer proof** — Dark-framed white quote and customer image.
5. **Next steps** — Three dark editorial resource cards.
6. **Closing call** — Stepped cobalt-and-violet field with white statement card.
7. **Directory** — Full navigation columns and cool utility bar.

**Transfer:** Use as the default expressive product-marketing narrative; vary the number and ordering of mechanism chapters.

### Focused feature landing page

1. **Promise** — Compact centered headline, support, paired actions and broad recording.
2. **Explanation** — Four numbered cells followed by three illustrated benefit cells.
3. **Demonstration** — Dark large-media workflow carousel with caption and template link.
4. **Reassurance** — Small governance or control benefit band.
5. **Next steps** — Dark editorial resources.
6. **Closing call** — Graphic white-card conversion band.
7. **Objections** — Split-title FAQ before the shared directory.

**Transfer:** Lead with the outcome, then show how it happens and what remains under the user's control.

### Integration activation campaign

1. **Promise** — Compact complementary-product statement and side-by-side walkthrough.
2. **Activation** — Three setup cards.
3. **Use-case proof** — Alternating audience/context splits and centered recording chapters.
4. **Advanced use** — Developer-oriented illustration and focused action.
5. **Practical examples** — Asymmetric prompt-composer gallery.
6. **Closing call** — Rounded bordered white panel with one connection action, followed by the shared directory.

**Transfer:** Make the relationship between tools explicit and remove setup uncertainty before adding richer examples.

### Company credibility and recruiting

1. **Belief** — Compact centered premise and two actions.
2. **Purpose** — Daylit product-at-work photograph beside text.
3. **Proof** — Logo rail, small numeric proof and concise outcome cells.
4. **People and place** — Five-tab office gallery and gridded recognition wall.
5. **Closing call** — Personal invitation on the graphic conversion field, then shared directory.

**Transfer:** Connect organizational belief to observable practice rather than a chronological biography.

### Plan selection and commercial comparison

1. **Choice** — Centered headline above four aligned plan columns.
2. **Reassurance** — Trust statement and restrained logo row.
3. **Comparison** — Long categorized matrix with persistent plan actions.
4. **Clarification** — Footnotes, three pricing-help paths and centered FAQ.
5. **Directory** — Shared link columns and utility strip; no extra graphic conversion band.

**Transfer:** Use a denser, quieter scoped system that prioritizes factual comparison over storytelling.

## Writing

Confident, pragmatic and conversational. Big claims are framed as useful changes to everyday work, then explained through concrete actions rather than technical spectacle.

**Do not copy:** Do not reuse Airtable or partner names, logos, product names, customer quotes, community counts, prices, scale claims or proprietary artwork. Source examples illustrate syntax only; replace them with truthful content for the new product.

- **Addressing the reader:** Use you and your team for practical instructions; use we for organizational belief. Refer to the product by name when explaining an actual mechanism.
- **Rhythm:** Headlines favor short clauses and paired contrasts. Supporting text is usually one sentence; explanatory sections allow compact two- or three-sentence paragraphs. Actions are brief verb phrases, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Pair people or stages in one simple contrast, often split into two balanced lines. | 6–12 words | “Humans and agents, on the same page”<br>“Start with the mess. End with an app” |
| Supporting line | State the operational relationship in plain language, avoiding a second slogan. | 10–22 words | “One relational source of truth for every app, agent, and workflow.” |
| Capability description | Start with a direct verb, identify an input or action, and end in the useful result. | 8–20 words | “Describe what you need in plain language and build it.” |
| Reassurance heading | Name the reader's control, not an abstract promise of trust. | 5–9 words | “Nothing runs without your say so” |
| Primary action | Immediate verb phrase with a low-friction next step. | 2–5 words | “Try it now”<br>“Read setup guide” |
| Closing invitation | Make the final appeal personal and concrete. | 8–17 words | “There's something at your company only you know how to fix.” |

**Words and phrasing to use:** build; work; your team; shared; connected; describe; start; run; source of truth; plain language

**Avoid:** revolutionary; unleash limitless potential; magic without explanation; next-generation synergy; effortless transformation

**Rules:**

- Follow broad promises with a visible mechanism or specific example.
- Use parallel sentence structures for related capabilities.
- Keep technical terms for sections where they clarify an actual task.
- Write FAQ questions as readers would ask them; answer directly before adding conditions.
- Numbers belong with a clear denominator, scope or timeframe.

## Do's and Don'ts

### Do

- Keep default display at 79.2px/1.1 and weight 550, with normal tracking.
- Align 1344px section rails continuously across adjacent chapters.
- Use 40px cell padding and 8px title/body gaps in substantial capability cells.
- Stage a 1024px-wide working scene below the centered opening copy.
- Carry the stepped rectilinear motif from faint hero backing into the saturated conversion field.
- Use 12px uppercase colored labels above 20px white resource titles.
- Keep customer quote panels white inside the dark proof chapter.
- Preserve 48px footer column gaps and a separate cool utility strip.

### Don't

- Do not use pricing's pill buttons as the default landing-page action; ordinary actions have 4px corners.
- Do not put shadows under every grid cell; shared 1px rules provide structure.
- Do not apply negative tracking to the default 48px and 79.2px headings.
- Do not spread cobalt or magenta behind every text section; concentrate them in graphic and demonstration stages.
- Do not enlarge company statistics into 80px display numerals; their scoped treatment is 18px semibold.
- Do not make every eyebrow uppercase; uppercase is concentrated in resource categories.
- Do not use blurred gradient blobs in place of crisp stepped bars.
- Do not turn the footer into a single centered legal row; retain the five-column directory.

## Motion and responsive

### Motion

**Observed:**

- Landing actions declare background-color, color and border-color transitions of 0.15s. Header actions declare 0.2s linear transitions.
- Integration-logo columns declare opposing 28s linear infinite scrolls.
- The hero object declares a 1.15s ease-out rise with a 1.22s delay; the opening pattern declares a 2.6s ease-out animation.
- Feature media declares opacity 0.4s cubic-bezier(0.76,0,0.24,1) and visibility changes. Customer stories expose segmented progress, previous/next and pause controls.

**Transfer:**

- Keep the moving logo wall clipped inside its ruled columns.
- Use the rise to introduce the working object while leaving the promise readable.
- Retain explicit pause controls on autoplay demonstrations and story sequences.

**Unknown:**

- Exact graphic-bar animation trajectories and carousel interval are not established.

### Responsive

**Observed:**

- Desktop shell width is 1344px; declared CSS includes 640px, 768px, 832px, 1024px and 1152px breakpoint families. Pricing declares a 768px breakpoint.
- Capability titles use clamp(18px, 2vw, 24px); customer quotes use clamp(20px, 2.5vw, 32px).

**Transfer:**

- On narrow layouts, retain the centered promise above the working object and preserve the stepped graphic behind the conversion card.
- Stack explanatory copy above its demonstration rather than shrinking the tab rail to unreadable width.
- Reduce grid column counts while preserving shared rules and the copy-above-media cell order; keep commercial plan comparison usable through a dedicated narrow layout.

**Unknown:**

- Mobile navigation, exact column-collapse thresholds and narrow pricing behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
