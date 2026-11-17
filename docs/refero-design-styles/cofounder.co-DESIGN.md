# Cofounder — pixel pastoral machinery

## Overview

Optimistic pixel-art worlds meet pale, tactile software panels and understated grotesk typography. Sky blue, leaf green and sunflower yellow enliven an otherwise warm off-white site with soft gray text. The feeling is capable but unhurried: expansive marketing compositions surround compact demonstrations, while instructional pages become focused reading environments. It suits tools that make complex work feel approachable and productive.

### Essentials

- A vivid world, not a floating app, introduces the product: a full-width 900px-tall pixel-art landscape leaves open sky behind a left-aligned 46px/1.08 regular headline and places the working object in the lower-right half.
- Headlines speak in two tones rather than two weights: 40px/1.15 at weight 400 pairs rgba(38,35,35,0.8) with rgba(38,35,35,0.5); capability headings use 36px/1.12.
- Controls feel like small physical keys: 41px-high actions have 8px corners, 12px horizontal padding, fine borders and white inset highlights; dark charcoal is the ordinary conversion treatment, off-white is used over colorful art.
- Most of the page stays warm and nearly colorless: #f5f5f2 canvas and pale raised panels dominate, while saturated blue and green belong to illustrated scenes and a full-width demonstration band, not every section.
- Software is staged as delicate machinery: a 1080px-wide framed overview and overlapping 12px-radius panels sit against the same pale canvas, with tiny semantic accents and layered edge shadows instead of heavy dark mockups.
- Playful pixel markings carry the personality beyond the opening: include a letter-grid graphic with 26px Departure Mono, 0.3em tracking and blue outlined discoveries, plus a ragged pixel transition into illustrated color. Use product-relevant words and simple pixel scenery when bespoke art is unavailable.
- The ending remains an illustrated destination: a two-tone 40px closing line and compact link columns sit opposite a 350×475px framed nature card with a frosted action panel; a green pixel fringe closes the page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Scene blue | `#1a6fd1` | `--color-sky` | background, accent | Blue foundation under the illustrated demonstration band; artwork brings lighter sky shades. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Grass lettering | `#549f4b` | `--color-footer-green` | text | Small lettering within the green pixel closing fringe. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm paper | `#f5f5f2` | `--color-canvas` | background, surface, action | Default canvas and light action fill. |
| Solid ink | `#171717` | `--color-ink` | text | Light-button lettering and strongest small text. |
| Charcoal edge | `#383838` | `--color-action-edge` | border | Dark action outline. |
| Soft heading ink | `#4f4d4c` | `--color-heading` | text | Visible rgba(38,35,35,0.8) over warm paper; primary heading tone. |
| Charcoal highlight | `#4f4f4f` | `--color-action-top` | action | Upper stop of the dark action gradient. |
| Muted body ink | `#646261` | `--color-body` | text | Visible rgba(38,35,35,0.7) over warm paper; paragraph tone. |
| Secondary ink | `#8e8c8b` | `--color-faint` | text | Visible rgba(38,35,35,0.5) over warm paper; secondary headline phrases, labels and fine print. |
| Soft edge | `#e7e7e3` | `--color-edge` | border, surface | FAQ separators and recessed neutral fills. |
| Frame gray | `#e8e7e6` | `--color-frame-edge` | border | Illustration frame edges and light header rules. |
| Instrument backing | `#f1f1ee` | `--color-panel` | surface | Overview backing and pale outer mounts. |
| Raised ivory | `#fbfbf8` | `--color-raised` | surface, text | Raised panels and navigation lettering over art. |
| Highlight white | `#ffffff` | `--color-white` | text, accent, surface | White illustration text, inset edge highlights and translucent surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Green-gray hairline | `#dee2de` | `--color-card-edge` | border | Pricing panel and comparison table borders. |
| pricing comparisons | Cost coral | `#f35f58` | `--color-cost` | text | Alternative-cost total, never general emphasis. |
| pricing pages | Success green | `#34a853` | `--color-green` | accent | Small inclusion checks in commercial explanations. |

## Typography

- **neoris** — Marketing headings, paragraphs, controls and reading content; the opening support line uses the TT Neoris Trial Variable declaration of the same design. Open, rounded contemporary grotesk with a regular, friendly display voice and finely graduated medium weights. If unavailable, use **Inter**. Use 400 for display and 460–530 for small text; preserve relaxed heading tracking. Font stack: "neoris", "Inter", Arial, sans-serif.
- **IBM Plex Mono** — Uppercase section labels, chapter references and decimal task indexes. Technical but light; small, widely tracked labels contrast with the rounded sans. Font stack: "IBM Plex Mono", ui-monospace, monospace.
- **departureMono** — The letter-grid signature and commercial price numerals. Pixel-built monospaced letters with visibly stepped contours. If unavailable, use **Departure Mono**. Use regular weight; retain the stepped outlines. Font stack: "departureMono", "Departure Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| hero | neoris | 400 | 46px | 1.08 | normal | White opening promise, usually two lines within 580px. |
| heading | neoris | 400 | 40px | 1.15 | normal | Major section statements, reading-page titles and closing promise. |
| capability | neoris | 400 | 36px | 1.12 | 0.009em | Two-tone headings in alternating capability chapters. |
| heading-small | neoris | 400 | 32px | 1.15 | 0.01em | Heading over the letter-grid graphic. |
| word-grid | departureMono | 400 | 26px | 1 | 0.3em | Spaced uppercase discovery letters within the signature puzzle. |
| closing-card | neoris | 460 | 24px | 1.15 | 0.01em | Promise over the illustrated closing card. |
| hero-support | neoris | 460 | 16px | 1.4 | 0.0094em | White translucent opening support copy. |
| body | neoris | 460 | 15px | 1.4 | 0.01em | Marketing paragraphs, text links and navigation lists. |
| action | neoris | 460 | 15px | 1.5 | 0.01em | Main action labels. |
| navigation | neoris | 410 | 15px | 1.5 | 0.01em, features "dlig" | Top navigation over the illustrated opening. |
| eyebrow | IBM Plex Mono | 400 | 12px | 1.5 | 0.12em, uppercase | Section introductions. |
| caption | neoris | 460 | 12px | 1.4 | 0.01em | Security note and discreet closing credits. |
| chapter-label | IBM Plex Mono | 400 | 11px | 1.5 | 0.12em, uppercase | Decimal-numbered capability labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | departureMono | 400 | 50px | 1.1 | -0.05em | Main price numeral, with smaller currency mark and sans billing period. |
| pricing comparisons | commercial-heading | neoris | 400 | 46px | 1.05 | -0.02em | Two-tone value comparison heading. |
| guides and pricing explanations | reading | neoris | 460 | 15px | 1.6 | 0.01em | Long-form guide prose and expanded explanatory answers. |
| pricing pages | faq-question | neoris | 530 | 15px | 1.6 | 0.01em | Question label in disclosure rows. |
| guides | chapter-badge | neoris | 500 | 12px | 16px | normal | Small rounded chapter badge above article title. |

**Notes:**

- Display emphasis comes from contrasting gray tones, not bold words or enlarged isolated keywords.
- Most letter spacing stays normal or slightly positive. Negative tracking belongs to the commercial comparison and pixel price, not the default headline.
- Keep the pixel face out of continuous prose. Roman chapter numerals and uppercase equipment-like labels use IBM Plex Mono instead.

## Layout

**Density:** Airy section staging with compact controls and fine, tightly grouped demonstration details.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap between capability disclosure rows. |
| 12px | Action gaps, frame padding and control group spacing. |
| 16px | Eyebrow-to-heading spacing and small panel insets. |
| 20px | Heading-to-body spacing and opening support offset. |
| 24px | Opening support-to-actions spacing and ordinary container side padding. |
| 32px | Body-to-capability-list spacing and reading title-to-prose spacing. |
| 64px | Space above and below opening article illustration. |
| 78px | Column gap in alternating capability layouts. |
| 80px | Closing composition column gap and top padding. |
| 96px | Capability chapter vertical padding. |
| 120px | Letter-grid section and pricing comparison vertical padding. |

### Containers and grids

- **wide-stage**: max width 1440px · side padding 20px. Wide navigation and opening copy sit close to the viewport edges, unlike the more inset body.
- **marketing-container**: max width 1100px · side padding 24px. Centered body wrapper leaves 1052px for content at desktop.
- **capability-pair**: 2 columns · gap 78px. A 340px text column shares the row with a wider demonstration; reverse sides between chapters.
- **overview**: max width 1080px. Centered broad software overview under a two-line thesis.
- **reading-column** (only for guides): max width 620px. Main article centered in the space to the right of a 260px navigation rail.
- **commercial-content** (only for pricing pages): max width 1080px · side padding 24px. Comparison table spans 1032px; the plan panel narrows to 640px and FAQ to 740px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 8px |
|  | capability-rows | 10px |
|  | demonstration-panels | 12px |
|  | raised-frames | 16px |
| guides | chapter-badges | 100px |
| pricing pages | faq-toggle | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| machined-frame | `inset 0px 0px 0.4px 1.5px rgba(255,255,255,0.35), inset 0px 2px 0px 0px #ffffff, 0px 0px 2px 0px rgba(0,0,0,0.25), 0px 0px 0px 4px rgba(232,231,230,0.32)` | Overview and illustrated closing frame; a white lip, dark fine edge and pale outer mount. |

### Surfaces

#### Paper canvas · level 0

**Use:** Ordinary page foundation.

**CSS:** `background: #f5f5f2`

**Observed:** A warm gray-white continuous ground, not alternating pure-white and gray stripes.

**Transfer:** Let whitespace separate related sections.

#### Raised instrument · level 1

**Use:** Large software overview backing.

**CSS:** `background: #f1f1ee; border-radius: 16px; box-shadow: inset 0px 0px 0.4px 1.5px rgba(255,255,255,0.35), inset 0px 2px 0px 0px #ffffff, 0px 0px 2px 0px rgba(0,0,0,0.25), 0px 0px 0px 4px rgba(232,231,230,0.32)`

**Observed:** Low-contrast interior UI sits inside a tactile edge rather than a heavy device bezel.

**Transfer:** Reconstruct the visible workflow with a few purposeful pale panels.

#### Frosted caption · level 2

**Use:** Text panel over the illustrated closing card.

**CSS:** `background: linear-gradient(rgba(255,255,255,0.06) 0%, rgba(255,255,255,0.03) 100%); border-radius: 8px; padding: 16px; backdrop-filter: blur(25px); box-shadow: inset 0px -1px 0px rgba(0,0,0,0.12), inset 0px -1px 2px rgba(0,0,0,0.1), inset 0px 1px 1px rgba(255,255,255,0.24)`

**Observed:** The underlying green landscape supplies the panel's color. White text and a light action stay legible above it.

**Transfer:** Place over a dark-enough area of a colorful pixel scene.

#### Illustrated blue band · level 0

**Use:** Immersive demonstration chapter.

**CSS:** `background-color: #1a6fd1; overflow: hidden`

**Observed:** Blue sky, stepped cloud silhouettes and pixel foliage frame white heading text and a broad pale application panel.

**Transfer:** Use the scene construction in imagery rather than a bare solid-blue rectangle.

#### Article illustration mount · level 1

**Only for:** guides

**Use:** Opening chapter artwork.

**CSS:** `background: rgba(242,242,237,0.24); border: 1.5px solid #e8e7e6; border-radius: 12px; padding: 8px; box-shadow: 1px 2px 2px #ffffff, 1px 4px 5px #ffffff, inset 2px 3px 4px rgba(152,146,140,0.16)`

**Observed:** A thin pale mount backs a saturated illustration with its own 8px corners.

**Transfer:** Keep the illustration full article width and reserve 64px around the framed image.

## Components

### Fixed navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; height: 91px; width: 100%; background-color: rgba(245,245,242,0.55); z-index: 201`

**Text style:** `navigation` — neoris 410 · 15px/1.5 · tracking 0.01em

**Observed:** A small serif-like wordmark anchors the left; right-aligned links are grouped in translucent rounded tabs over art. On paper sections the bar becomes opaque, dark-lettered, with a fine bottom rule. The far-right conversion key remains compact.

**Transfer:** Use the new product's identity and short plain-language destinations.

### Light action

**Use:** Primary conversion over vivid imagery and within the closing card.

**CSS:** `height: 41px; padding: 0px 12px; background: #f5f5f2; color: #171717; border: 1px solid rgba(32,32,32,0.1); border-radius: 8px; box-shadow: 0px 2px 3px rgba(0,0,0,0.06), inset 0px 0px 0.4px 1.5px rgba(255,255,255,0.35), inset 0px 2px 0px #ffffff`

**Text style:** `action` — neoris 460 · 15px/1.5 · tracking 0.01em

**Observed:** A centered text label without a large icon or oversized footprint.

**States:** Declared: hover background rgb(237, 237, 234); focus-visible not specified.

### Dark action

**Use:** Default conversion on pale content sections.

**CSS:** `height: 41px; padding: 0px 12px; background: linear-gradient(rgba(32,32,32,0.1),rgba(32,32,32,0.1)),linear-gradient(#4f4f4f,rgba(32,32,32,0.85)); color: rgba(255,255,255,0.9); border: 1px solid #383838; border-radius: 8px; box-shadow: 0px 0px 0px 1px rgba(64,64,64,0.12), inset 0px 2px 0px rgba(255,255,255,0.24), inset 0px -0.5px 2px rgba(0,0,0,0.25), 0px 2px 8px rgba(0,0,0,0.03), 0px 3px 4px rgba(0,0,0,0.16)`

**Text style:** `action` — neoris 460 · 15px/1.5 · tracking 0.01em

**Observed:** Charcoal gradients and edge highlights create a physical key. Some instances add a small right arrow. Guide inline actions shrink to 33px high with 13px labels; the wide overview action is 44px high.

### Capability disclosure

**Use:** Selectable capabilities beneath a chapter description.

**CSS:** `display: flex; align-items: center; gap: 12px; width: 340px; padding: 12px 16px; background: rgba(255,255,255,0.6); border: 1px solid rgba(0,0,0,0.1); border-radius: 10px; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.8)`

**Text style:** `body` — neoris 460 · 15px/1.4 · tracking 0.01em

**Observed:** A 10px mono decimal index leads a 14px/21px weight-500 label; a thin 16px plus is pinned to the far right. Rows are about 47px tall and stack with 8px gaps.

**States:** Declared: hover translate 0 0, background #fff and border-color color-mix(in oklab, #000 20%, transparent); focus-visible 2px solid rgba(38,35,35,0.8), offset 2px.

**Transfer:** Give each row a specific task, not a vague benefit.

### Illustrated closing card

**Use:** Final conversion object beside the footer links.

**CSS:** `width: 350px; height: 475px; padding: 12px; background: rgba(251,251,248,0.8); border-radius: 16px; box-shadow: inset 0px 0px 0.4px 1.5px rgba(255,255,255,0.35), inset 0px 2px 0px #ffffff, 0px 0px 2px rgba(0,0,0,0.25), 0px 0px 0px 4px rgba(232,231,230,0.32)`

**Text style:** `closing-card` — neoris 460 · 24px/1.15 · tracking 0.01em

**Observed:** An inset 326×451px pixel illustration fills the frame. A Frosted caption overlaps its lower portion with a promise and Light action.

**Transfer:** Use an original nature-and-progress metaphor with a clear foreground focal point.

### Footer link cluster

**Use:** Closing navigation beside the illustrated conversion object.

**CSS:** `display: flex; flex-direction: column; gap: 32px; margin-top: 48px`

**Text style:** `body` — neoris 460 · 15px/1.4 · tracking 0.01em

**Observed:** A short inline family of educational links precedes two narrow columns of company and utility links. Small square social keys and a quiet security line follow. It is not a full-width mega-footer.

### Plan panel

**Only for:** pricing pages

**Use:** Present one simple commercial offer.

**CSS:** `max-width: 640px; padding: 16px 12px 32px; background: #fbfbf8; border: 1px solid #dee2de; border-radius: 16px; display: flex; flex-direction: column; gap: 24px; box-shadow: inset 0px 0px 0.4px 1.5px rgba(255,255,255,0.35), inset 0px 2px 0px #ffffff, 0px 0px 2px rgba(0,0,0,0.25), 0px 0px 0px 4px rgba(232,231,230,0.32)`

**Text style:** `body` — neoris 460 · 15px/1.4 · tracking 0.01em

**Observed:** A small product label and wide pixel-flower banner sit above left-aligned price numerals, billing unit and a green-check inclusion list. Explanatory text and an underlined calculator link live outside the panel.

**Transfer:** Show one understandable offer before presenting usage caveats.

### FAQ disclosure

**Only for:** pricing pages

**Use:** Answer commercial objections.

**CSS:** `display: flex; justify-content: space-between; align-items: center; width: 100%; padding: 16px 8px; background: transparent; border: 0px`

**Text style:** `faq-question` — neoris 530 · 15px/1.6 · tracking 0.01em

**Observed:** Within a 740px column, question rows use fine #e7e7e3 separators and a 36px circular tactile plus/minus key. The first answer is expanded; prose is inset 8px and leaves generous room before the right edge.

### Chapter badge

**Only for:** guides

**Use:** Identify the reading chapter without competing with the title.

**CSS:** `display: inline-flex; padding: 4px 8px; border-radius: 100px; background: linear-gradient(rgba(251,251,248,0.5),rgba(251,251,248,0)); box-shadow: inset 0px 0px 0px 1px #ffffff, 0px 0px 0px 1px rgba(0,0,0,0.12), 0px 2px 2px rgba(0,0,0,0.02)`

**Text style:** `chapter-badge` — neoris 500 · 12px/16px

**Observed:** A tiny pale badge sits 24px above the article title.

## Imagery and graphics

### Pixel pastoral world

**Use:** Signature opening scene and colorful demonstration setting.

**Observed:** Crisp stepped pixels render a sunny park, distant skyline, voluminous clouds, flowers and a large shade tree. A laptop and notebook sit in grass at lower right while blue sky behind the copy remains uncluttered. The illustration occupies the entire first screen; small green-glass task notices hover above the object.

**Transfer:** Create a new optimistic place where the product's work happens, retaining sky, greenery, tangible tools and layered depth. Minimum version: an original low-resolution landscape with one readable work object and two or three small status notices.

**Build:** Draw an SVG with a 480×300 viewBox and shape-rendering crispEdges, then scale to fill a 1440×900 stage. Use axis-aligned stepped polygons for cyan sky clouds, several green foliage planes and a dark tree at the right edge. Place a simple gridded work object in the lower-right third. Use a translucent dark-green notification stack above it, with 8px corners, tiny bright dots and white labels. Keep the upper-left sky free of texture.

### Pixel transition fringe

**Use:** Signature boundaries between illustrated scenes and paper, and the final green edge.

**Observed:** The meeting point breaks into irregular square fragments rather than a smooth wave. The footer finishes with a shallow bright grassy pixel band and centered fine lettering.

**Transfer:** Carry the scene's dominant color into the paper edge; retain the ragged square silhouette even in a simplified illustration system.

**Build:** Use an SVG strip spanning the width, about 75px high at desktop. Stack a solid lower band with irregular horizontal runs of 2–8px squares stepping upward; scatter sparse detached squares above. Use green hues sampled from the new scene for the ending and white squares to erode the lower edge of blue scenes. Avoid blur.

### Pale software compositions

**Use:** Overview and capability demonstrations.

**Observed:** Small, sharp UI text and very pale panels show task boards, orchestration nodes, email previews and analytics. Panels overlap with restrained shadows; an email report brings a 40px 58% statistic, a luminous green bar and tiny comparison chips into the foreground. Demonstrations are wider than their accompanying text columns.

**Transfer:** Render a truthful simplified workflow using the new product's own UI. Preserve the pale hierarchy, front-to-back overlap, one legible focal metric and sparse semantic colors; do not enlarge every internal label.

### Printed chapter objects

**Use:** Educational resource showcase.

**Observed:** Ivory book-cover cards in a two-column arrangement sit on a faint oversized square grid. Each has a simple sans title, rule, mono chapter notation and saturated pixel illustration: launch vehicle, factory arms, satellite dish or fast train. A translucent rounded outer mount and soft lower shadow make each cover feel tangible.

**Transfer:** Use illustrated metaphors for the new resource topics and preserve the quiet printed cover around the vivid image.

**Build:** Create two columns of tall ivory rectangles with a subtle left spine, fine gray rule, a roughly square colorful pixel image and small mono footer. Add a larger 16px-radius translucent mount behind each and a faint grid made from 1px lines at 80px intervals; fade the grid toward the section edges using a radial mask.

### Letter discovery grid

**Use:** Signature breadth-of-application graphic.

**Observed:** A centered 874×460px field of widely spaced pixel capitals contains relevant phrases hidden among filler letters. Thin pale-blue rounded outlines identify several discoveries, while unselected letters stay gray.

**Transfer:** Use meaningful new use cases or outcomes hidden horizontally. Keep the puzzle legible as artwork rather than a demanding interactive game.

**Build:** Lay out a fixed-column character matrix using the word-grid recipe; separate visual rows with generous vertical gaps. Draw SVG capsule paths over a few word runs with a 2px pale-blue stroke and no fill. Build capsule curves from short stepped segments for a pixel-like outline. Selected letters darken; filler remains at rgba(38,35,35,0.5).

### Guide chapter art

**Only for:** guides

**Use:** First illustration in a reading chapter.

**Observed:** Saturated pixel scenes communicate a metaphor rather than literal interface steps. A rocket ascends through peach clouds for starting; yellow robotic arms stand against blue factory windows for building. The image occupies the 620px reading width inside the Article illustration mount.

**Transfer:** Choose one concrete metaphor for the chapter's transformation, in the same sunny high-contrast pixel treatment.

### Integration plaque

**Only for:** pricing pages

**Use:** Explain the supporting technical ecosystem.

**Observed:** An 800×360px pale inset plaque holds three centered partner marks separated by thin vertical rules. Soft-blue pixel erosion at both ends keeps the otherwise restrained plaque connected to the art direction.

**Transfer:** Use actual relevant integrations with equal visual weight and retain pixel edges instead of a generic logo carousel.

**Build:** Place three marks in a centered flex row inside a 16px-radius pale rectangle. Add inset white edge highlights and shallow gray inset shading; draw blue square clusters densely at the left and right edges and sparsely toward the center. Keep the middle clear.

### Icons

**Observed:** Thin round-cap pluses use 16×16px boxes and 1px strokes in muted gray; small arrows sit at action ends. Commercial inclusion checks are 21px green pixel-edged seals. Social marks are solid, centered in 36px pale keys.

**Transfer:** Choose thin simple line icons for controls and compact solid marks for identity; reserve the stepped seal construction for positive commercial inclusions.

## Section recipes

How recurring sections are built.

### First screen: Illustrated world opening

**Observed:** A 91px fixed navigation overlays a full-width pixel world. Open sky supports left-aligned copy beginning below the navigation: a regular 46px/1.08 white-gradient headline spans about 580px, followed after 20px by a 540px-wide support line and after 24px by Light action and translucent secondary action with a 12px gap. Landscape layers run behind everything: distant skyline, clouds, foreground grass, right-edge tree, lower-right laptop and notebook. Three small task notices float above the object. Within the first 900px the complete headline, support, actions and principal illustrated object are visible; social proof begins below the scene.

**Transfer:** Make this the default landing-page opening. Without elaborate artwork, construct the Pixel pastoral world minimum version with one purposeful object and clear sky behind the text. Commercial pages instead open with the Plan panel; guides open with Chapter badge, title, introductory prose and framed chapter art beside a reading rail.

**Avoid:** Do not replace the landscape with a centered headline on a blank canvas, a dark space scene or an enormous floating dashboard. Do not let text cover the main work object.

**Text style:** `hero` — neoris 400 · 46px/1.08

### Two-tone thesis and overview

**Observed:** A centered two-line heading uses heading in primary and faint gray, above a 1080×600px Raised instrument overview. Three short explanatory columns sit below; a hairline-bounded action row closes the section.

**Transfer:** State what the product is, show how its pieces relate, then explain the operating model in concise clauses.

**Text style:** `heading` — neoris 400 · 40px/1.15

### Alternating capability chapter

**Observed:** Within the marketing-container, a 340px text column sits beside a wider Pale software composition with a 78px gap. Chapter-label leads a two-tone capability heading, body copy and a Capability disclosure stack after 32px. Chapters use 96px vertical padding and reverse the text/media sides.

**Transfer:** Choose outcome-sized chapters with concrete tasks beneath them. Keep one dominant software story per row rather than a collage of unrelated features.

**Text style:** `capability` — neoris 400 · 36px/1.12 · tracking 0.009em

### Resource invitation

**Observed:** A centered heading, compact two-line support and Dark action introduce Printed chapter objects on a faint grid. A small download key sits below the covers.

**Transfer:** Turn educational or reference content into tangible illustrated objects rather than ordinary blog tiles.

### Immersive tool chapter

**Observed:** Illustrated blue band expands edge to edge with pixel foliage and clouds. Centered white two-tone heading and supporting text lead three short tab-like statements separated by vertical rules. A broad pale demonstration panel rises below them.

**Transfer:** Use this concentrated color chapter for a vivid working explanation; keep surrounding narrative sections on Paper canvas.

### Discovery field

**Observed:** A heading-small and short centered support introduce the Letter discovery grid after 60px. The whole section has 120px vertical padding.

**Transfer:** Translate breadth into a playful field of meaningful words rather than a grid of logo badges.

**Text style:** `heading-small` — neoris 400 · 32px/1.15 · tracking 0.01em

### Illustrated closing destination

**Observed:** Within the marketing-container, the two-tone closing promise sits at left over Footer link cluster, social keys and caption-sized security text. An 80px gap separates this from Illustrated closing card at right. A faint grid fades behind the composition; Pixel transition fringe closes the full width.

**Transfer:** Restate the broad outcome, offer compact navigation and give the final action its own vivid framed scene. Keep it welcoming rather than a giant sales banner.

**Text style:** `heading` — neoris 400 · 40px/1.15

### Commercial explanation

**Only for:** pricing pages

**Observed:** Plan panel opens the page. Credit mechanics follow in three equal columns with 32px gaps and top hairlines. A compact summary pill introduces a two-tone commercial-heading above a 1032px-wide comparison table with approximately 68px rows. Integration plaque, a 740px FAQ column and Illustrated closing destination complete the explanation.

**Transfer:** Move from simple price to mechanics, comparative value, dependencies and objections. Use real rates and honest qualification, not decorative pricing tiers.

**Text style:** `commercial-heading` — neoris 400 · 46px/1.05 · tracking -0.02em

### Focused reading environment

**Only for:** guides

**Observed:** Below the fixed header, content begins at 137px. A 260px left rail contains a short guide identity, small Dark action, Roman-numbered chapter groups and 200px-wide topic links with tactile dots; the current dot glows pale blue. The main 620px column opens with Chapter badge and heading, then reading prose, generous paragraph spacing and Guide chapter art. A slender right-edge ladder of short gray ticks highlights the reading position in blue. Subsequent sections mix headings, lists, inset explanatory diagrams and pale-blue product callouts with small top-right actions. Endings remain in the reading shell: a final contextual callout and a short next-step handoff, not the illustrated marketing footer.

**Transfer:** Use this layout for practical long-form teaching. Break complex ideas with pale framed diagrams and connect product help to the specific step. End with momentum toward the next chapter.

**Text style:** `reading` — neoris 460 · 15px/1.6 · tracking 0.01em

## Page flow

**Storyline:** Promise → working model → outcome chapters → useful learning material → deeper demonstration → breadth → final invitation; commercial and educational pages narrow this pattern to their purpose.

### Broad product landing page

1. **Promise** — Full-screen pixel landscape with direct white promise and two compact actions.
2. **Social proof** — A short adoption line and pale recessed customer marks.
3. **Product demonstration** — Two-tone definition, framed orchestration overview and a small activation strip.
4. **Capability chapters** — Alternating text and software stories with numbered task disclosures.
5. **Education** — Illustrated printed guide covers and a download invitation.
6. **Deep demonstration** — Blue landscape band with tabbed statements and pale software stage.
7. **Breadth** — Word-search-like discovery graphic.
8. **Closing call** — Compact link footer, illustrated action card and grassy pixel fringe.

**Transfer:** Adapt the narrative beats to the product while retaining the illustrated world, tactile software, playful discovery device and welcoming final scene.

### Detailed practical product-building guide

1. **Orientation** — Persistent chapter rail, tiny chapter badge, plain title and explanatory introduction above factory pixel art.
2. **Instruction** — Long-form sections move from preparation through execution and maintenance; lists and framed process diagrams interrupt the prose.
3. **Contextual conversion** — Pale-blue feature callouts attach compact actions to the task being explained.
4. **Next step** — A final feature callout precedes a plain next-chapter heading and several encouraging paragraphs within the reading shell.

**Transfer:** Teach a complex workflow in a calm reading column; keep conversion tied to actual help and end by handing off to the next task.

### Introductory decision-making guide

1. **Orientation** — Chapter badge, title and approachable introduction above a pixel rocket illustration.
2. **Instruction** — Short sections, criteria lists, examples and occasional framed concept diagrams help readers decide what to do.
3. **Contextual conversion** — Pale-blue product-help panels offer a small action at relevant points.
4. **Next step** — A concise action-oriented final section and feature panel finish with a quiet next-chapter note; the reading rail stays present.

**Transfer:** Use fewer technical diagrams and more concrete decision criteria for introductory learning content.

### Explain a simple subscription and variable usage

1. **Offer** — Single raised plan panel with pixel-flower banner, pixel price and green-check inclusions.
2. **Mechanics** — Three ruled columns explain monthly allowance, rollover and top-up behavior.
3. **Value comparison** — Two-tone heading and restrained ruled table compare work categories and costs.
4. **Dependencies** — Wide integration plaque and explanatory text clarify the supporting services.
5. **Objection handling** — FAQ list with one expanded answer.
6. **Closing call** — The illustrated card-and-links footer repeats the broad invitation.

**Transfer:** Keep the offer simple, disclose dependencies and usage caveats before the final invitation.

## Writing

Practical optimism with a patient teacher's confidence. Broad promises are followed by concrete tasks, plain explanations and reminders of user control.

**Do not copy:** Do not reuse Cofounder or General Intelligence Company names, wordmarks, artwork, customer identities, adoption totals, prices, cost comparisons, certification claims or example product claims. Replace them with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. The product is usually named as the subject of an active verb; instructional passages explain what matters before describing the product's help.
- **Rhythm:** Headlines are short statements, often paired with a softer continuation. Support paragraphs use two or three clear sentences; longer guides alternate plain explanations with pointed short directives.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the product and state the complete outcome in ordinary words. | 8–13 words | “[Brand] lets you run an entire company with AI” |
| Paired heading | Start with the reader's work; follow with the work the product takes on. | 4–9 words per clause | “Keep building the product.”<br>“Put [Brand] to work on the company.” |
| Support | Describe a starting input, the work performed and the guardrail. | 20–45 words | “Start with the outcome you need. [Brand] brings the right company context and capabilities together, then keeps you in control of what goes live.” |
| Action | A plain verb phrase promises useful work, not access to a sales process. | 3–6 words | “Put the guide to work”<br>“Run a company” |
| Guide opening | Begin with an accessible belief, then reduce the perceived prerequisites. | One short statement followed by explanation | “Great companies usually start with a simple belief: something should exist that does not exist yet.” |
| Commercial question | Use the reader's actual concern, including limits and recurring costs. | 5–12 words | “Do unused credits roll over?”<br>“Does hosting have an ongoing cost?” |

**Words and phrasing to use:** start with; put to work; your context; stay in control; step by step; what matters; keep moving; what comes next

**Avoid:** revolutionary; 10x everything; magic; game-changing; effortless domination; enterprise-grade as an unsupported claim

**Rules:**

- Name concrete outputs and actions rather than stacking abstract benefits.
- Pair automation claims with approval, control or usage qualifications when relevant.
- Explain specialist terms before assuming expertise in a guide.
- End teaching with a small achievable next step, not a sudden sales pitch.

## Do's and Don'ts

### Do

- Keep the default heading at 40px/1.15 and weight 400, with a lighter gray continuation.
- Use 36px/1.12 chapter headings over 15px/1.4 explanatory paragraphs.
- Stage capabilities with a 340px text column, 78px gap and 96px vertical padding.
- Keep conversion keys 41px high with 8px corners and visible white inset highlights.
- Use 12px frame padding around the 350×475px closing illustration.
- Preserve saturated pixel scenery while keeping the surrounding interface almost monochrome.
- Use 11px uppercase mono chapter labels with 0.12em tracking.
- Let a focal metric emerge from a pale overlapping report panel rather than a giant colorful statistics wall.

### Don't

- Do not use bold 700-weight display text to replace the two-tone regular hierarchy.
- Do not turn the 8px action corners into large pills; pills belong to small badges and circular toggles.
- Do not spread blue across every background or use green as a general heading color.
- Do not add thick black device bezels around the pale software stories.
- Do not apply soft photographic blur to pixel-art edges or smooth the pixel fringe into waves.
- Do not put the pixel font into paragraphs, navigation or ordinary section headlines.
- Do not inflate all internal software labels to marketing text size; keep a single clear focal detail.
- Do not turn the compact footer into a dark mega-footer or a giant wordmark mural.

## Motion and responsive

### Motion

**Observed:**

- Declared: hero-enter uses 0.6s cubic-bezier(0.23,1,0.32,1); notification pops use 0.52s cubic-bezier(0.34,1.56,0.64,1).
- Declared: light actions transition background-color and box-shadow over 0.14s ease-out; capability rows transition background-color, border-color and transform over 0.15s cubic-bezier(.4,0,.2,1).
- Declared: navigation color and font-weight transition over 0.2s. The letter-grid has dedicated stroke and letter keyframes.

**Transfer:**

- Use staged copy arrival and small task-notice pops to enliven the illustrated world, rather than moving the whole layout.
- Keep disclosure and action feedback quick and tactile; preserve readable still compositions.

**Unknown:**

- Exact keyframe paths, carousel cadence, word-grid drawing durations and reduced-motion handling are not established.

### Responsive

**Observed:**

- Desktop navigation is shown at widths of 1000px and above.
- Major headings have declared 32px intermediate and 28px narrow variants; guide titles have a 32px narrow variant.
- The desktop letter matrix is hidden below 920px. The desktop guide shell and closing illustration have mobile-specific visibility changes.

**Transfer:**

- On narrow layouts stack capability text and demonstration, keeping copy before its related panel. Preserve crisp pixel edges and a clear sky text zone when reframing the opening.
- Replace the wide letter matrix with a compact, readable discovery motif rather than shrinking its letters to illegibility. Keep the closing illustrated invitation represented in the mobile composition.

**Unknown:**

- Mobile navigation construction, alternate guide shell, exact narrow hero geometry and mobile footer artwork arrangement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
