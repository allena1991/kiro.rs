# Studio.Design — diagonal creative freedom

## Overview

An exuberant portfolio sensibility sits inside a restrained, light-gray product website. Tight grotesk headlines, compact dark buttons and nearly borderless white panels provide a neutral framework for colorful finished work and large interface demonstrations. The feeling is creative, direct and approachable, with spacious compositions rather than dense sales copy; grayscale portraits add an editorial counterpoint.

### Essentials

- The opening is a diagonal exhibition, not a centered software pitch: an 80px/1, weight-600 headline with -0.04em tracking sits upper left while a staircase of colorful work crosses toward the upper right; a 345px support column and compact action balance it at lower right.
- Typography compresses big ideas into short, tightly fitted phrases: Inter headings use -0.04em tracking, with 72px/1 chapter leads and 48px/1.1 weight-700 card titles; body text stays comparatively substantial at 19px/1.4.
- Buttons are small rectangular tabs beside expansive imagery: the opening action is 42px high with 4px corners, feature actions are 46px high with 8px corners, and closing actions are 52px high with 6px corners. All pair short labels with a tiny northeast arrow.
- The architecture is almost entirely neutral: #f2f2f2 and #eeeeee canvases, #ffffff cards and #222222 ink. Saturated color occupies the artwork rather than headline text or page bands; blue #0275fd is confined to pricing recommendations and savings.
- Finished work is the spectacle: use a staircase collage, edge-clipped output galleries and a darkened diagonal work wall somewhere in the composition. When the product has no visual output, construct polished sample outcomes or editorial proof boards rather than substituting generic icons.
- The page shifts from exhibition to workspace to editorial: white 8px-corner capability panels sit on a black-to-#eeeeee vertical fade; grayscale 431px-wide portrait stories contrast with colorful work, and a broad left-aligned closing sentence leads into a four-column #222222 footer.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-white` | surface, text | Capability cards and high-contrast button text. |
| Soft inverse | `#f7f7f7` | `--color-inverse` | text, surface | Footer links, dark-section headlines and pale reverse actions. |
| Opening gray | `#f2f2f2` | `--color-canvas` | background | Default light opening canvas. |
| Gallery gray | `#eeeeee` | `--color-main` | background, text | Main exhibition canvas and light text over dark imagery. |
| Closing gray | `#eaeaea` | `--color-closing` | background | Closing call band; also the visible result of rgba(34,34,34,0.05) over the pricing canvas in the highlighted comparison column. |
| Muted copy | `#555555` | `--color-muted` | text | Centered-page support copy and subdued footer utilities. |
| Primary ink | `#222222` | `--color-ink` | text, background, action | Default headings and copy, dark buttons and footer. |
| Exhibition black | `#000000` | `--color-black` | background, accent | Top of the capability fade and backing beneath diagonal artwork. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Secondary ink | `#333333` | `--color-secondary-ink` | text, border | Commercial-page copy and outlined plan actions. |
| pricing and capability-detail pages | Commercial gray | `#f5f5f5` | `--color-pricing-canvas` | background, border | Commercial canvas and pale capability-detail bands. |
| capability-detail pages | Chapter charcoal | `#141414` | `--color-chapter-dark` | background, text | Dark capability chapters and light-chapter heading ink. |
| capability-detail pages | Raised charcoal | `#242424` | `--color-chapter-card` | surface | Cards against dark capability chapters. |
| capability-detail pages | Detail copy | `#444444` | `--color-detail-copy` | text | Support text inside pale capability chapters. |
| pricing pages | Plan metadata | `#8e8e8e` | `--color-metadata` | text | Plan descriptions and comparison-row labels. |
| pricing pages | Plan edge | `#e6e6e6` | `--color-plan-edge` | border | Vertical separators between contiguous plans. |
| pricing pages | Commercial rule | `#ededed` | `--color-rule` | border | Comparison rules and FAQ row dividers. |
| pricing pages | Decision blue | `#0275fd` | `--color-blue` | accent, surface | Narrow recommendation strips and small savings badges, not ordinary marketing buttons. |

## Typography

- **Inter** — Headlines, paragraphs, testimonial labels, actions and commercial information. Contemporary grotesk with a high x-height; large text is tightly tracked and medium-to-bold rather than ultra-black. Font stack: "Inter", "Noto Sans JP", sans-serif.
- **Inter Tight** — Top navigation and capability-card action labels. Compact grotesk, slightly more compressed than the main text family. Font stack: "Inter Tight", Inter, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 80px | 1 | -0.04em | Default two-line opening headline. |
| chapter | Inter | 600 | 72px | 1 | -0.04em, features "palt" | Large left-aligned introduction to the capability exhibition. |
| heading | Inter | 700 | 64px | 1 | -0.04em, features "palt" | Headline over the diagonal work wall. |
| closing-heading | Inter | 600 | 64px | 1.66 | -0.04em, features "palt" | Broad closing invitation above the footer. |
| card-heading | Inter | 700 | 48px | 1.1 | -0.04em | Capability panel titles, usually broken into two short lines. |
| story-heading | Inter | 700 | 36px | 1.2 | -0.04em | Person or organization name below a portrait. |
| body | Inter | 500 | 20px | 1.4 | -0.04em | Opening support text and first-person story quotations. |
| wall-body | Inter | 400 | 20px | 1.4 | -0.04em, features "palt" | Support text over darkened artwork. |
| closing-action | Inter | 600 | 20px | 1.4 | -0.04em | Final conversion button. |
| card-body | Inter | 500 | 19px | 1.4 | normal | Capability panel explanations. |
| hero-action | Inter | 600 | 16px | 1.15 | -0.04em | Opening conversion action. |
| account-action | Inter | 600 | 16px | 1.4 | -0.04em | Top-right account action. |
| card-action | Inter Tight | 700 | 16px | 1.4 | normal | Action tabs on capability panels and the diagonal work wall. |
| footer-link | Inter | 400 | 16px | 1.66 | normal, features "palt" | Footer navigation lists. |
| navigation | Inter Tight | 500 | 15px | 1.4 | normal, features "palt" | Compact top navigation labels. |
| story-label | Inter | 500 | 14px | 1.2 | -0.04em, features "palt" | Short occupational label above a story title; often uppercase. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and capability-detail openings | centered-display | Inter | 700 | 80px | 1 | -0.04em, features "palt" | Single centered promise below a small page label. |
| dark capability-detail chapters | detail-dark-heading | Inter | 700 | 64px | 1.4 | -0.04em, features "palt" | Centered chapter promise. |
| light capability-detail chapters | detail-light-heading | Inter | 700 | 64px | 1.2 | -0.05em, features "palt" | Centered chapter promise on pale surfaces. |
| pricing pages | price | Inter | 700 | 36px | 32px | normal | Compact primary price numeral with smaller currency and period alongside. |
| pricing pages | plan-heading | Inter | 700 | 24px | 1.4 | 0.02em | Plan names. |
| pricing and capability-detail openings | centered-support | Inter | 500 | 21px | 1.4 | normal, features "palt" | Centered support paragraph below the headline. |
| pricing and capability-detail openings | page-label | Inter | 600 | 20px | 1.4 | normal, features "palt" | Page-type label above the opening headline. |
| capability-detail chapters | detail-label | Inter | 500 | 20px | 1.4 | normal, features "palt" | Category label above each chapter heading. |
| capability-detail chapters | detail-body | Inter | 500 | 18px | 1.4 | normal, features "palt" | Centered explanations on dark or pale bands. |
| pricing pages | faq-question | Inter | 700 | 18px | 1 | normal | Question text in accordion rows. |
| pricing pages | plan-action | Inter | 600 | 14px | 1.4 | normal | Full-width outlined plan actions. |

**Notes:**

- Use the default opening's weight 600, not the weight 700 of centered commercial and capability-detail openings.
- The main heading family keeps -0.04em tracking across 36–80px sizes; the pale detail-chapter variant tightens to -0.05em. Small navigation and capability body text return to normal tracking.
- Keep expressive fonts inside depicted work separate from the marketing typography. A serif title inside a demonstration is not a second marketing typeface.

## Layout

**Density:** Airy at page scale, compact within controls: artwork and large panels carry the visual weight while paragraphs remain short.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Story label-to-name gap and tight internal separation. |
| 12px | Vertical button padding. |
| 16px | Capability title-to-copy gap and closing headline-to-action spacing. |
| 20px | Output-gallery tile gap and header outer inset. |
| 28px | Opening support-to-action gap and paired capability column gap. |
| 30px | Centered opening text gaps and capability row spacing. |
| 32px | Panel media separation and interior group spacing. |
| 48px | Wide capability panel top padding and centered-page section separation. |
| 64px | Inset around the diagonal work wall. |
| 80px | Leading interior inset of the wide capability panel. |
| 96px | Editorial heading-to-story grid interval and detail chapter content lead-in. |
| 100px | Closing call top and bottom padding. |
| 120px | Top of the capability exhibition fade. |
| 128px | Detail chapter vertical padding. |
| 140px | Opening text layer top and bottom breathing room. |

### Containers and grids

- **opening-stage**: max width 1440px · side padding 30px. Full-width exhibition stage. Headline takes roughly two fifths of the width at upper left; the support column occupies the lower-right quarter.
- **capability-grid**: max width 1368px · 2 columns · gap 28px · side padding 36px. Desktop layout width at 1440px, not a fixed site-wide maximum: a wide lead panel followed by paired panels around 670px wide, with 30px row separation.
- **story-grid**: max width 1051px · 2 columns · gap 190px. Narrower editorial grid, with 431px portrait columns and a conspicuously wide center gutter.
- **work-gallery**: 3 columns · gap 20px. 480px-wide output tiles overflow the viewport edges; rows are roughly 353px tall including their vertical inset.
- **footer-columns**: 4 columns · gap 0px · side padding 100px. Four equal 310px columns at desktop: identity, two link lists and a short utility list.
- **commercial-content** (only for pricing pages): max width 1178px · 5 columns · gap 0px. Centered contiguous plan matrix. Five equal plan columns; comparison tables reserve a separate leading feature-label column.
- **detail-grid** (only for capability-detail pages): max width 1147px · 2 columns · gap 23px. Two 562px cards within a right-shifted content field, leaving room for a persistent left chapter index.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | opening-and-account-actions | 4px |
|  | capability-panels-and-tabs | 8px |
|  | closing-action | 6px |
| capability-detail pages | detail-cards | 6px |
| pricing pages | commercial-group-outer-corners | 16px |
| pricing pages | plan-actions | 48px |
| pricing pages | billing-toggle | 96px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action-tab | `0px 2px 15px 0px rgba(0, 0, 0, 0.1)` | Small feature and work-wall actions. |
| interface-media | `0px 2px 20px 0px rgba(0, 0, 0, 0.1)` | Large interface windows separated from their panel backing. |
| portrait-or-detail-card | `0px 3px 30px 0px rgba(0, 0, 0, 0.05)` | Occasional portrait lift and pale detail cards; most broad panels remain flat. |

### Surfaces

#### Opening canvas · level 0

**Use:** Default first-screen ground.

**CSS:** `background: #f2f2f2; color: #222222`

#### Exhibition canvas · level 0

**Use:** Output galleries and editorial sections.

**CSS:** `background: #eeeeee`

#### Capability fade · level 0

**Use:** Dramatic neutral transition behind capability panels.

**CSS:** `background-image: linear-gradient(#000000 0%, #eeeeee 100%); padding-top: 120px; padding-bottom: 100px`

**Observed:** A full-width vertical fade extends behind a long panel field; the light chapter title starts in its near-black upper portion.

**Transfer:** Keep it monochrome and long enough to become the pale ground behind later panels.

#### White capability panel · level 1

**Use:** Main product capability grouping.

**CSS:** `background: #ffffff; border-radius: 8px; overflow: hidden`

**Observed:** Flat, almost borderless framing lets the interface image supply detail.

#### Work wall scrim · level 1

**Use:** Legibility over the diagonal image exhibition.

**CSS:** `background-image: linear-gradient(90deg, rgba(0, 0, 0, 0.8) 1%, rgba(0, 0, 0, 0.3))`

**Observed:** The left edge is substantially darker than the right; colorful page examples remain visible underneath.

**Transfer:** Darken artwork instead of adding a separate floating text card.

#### Closing band · level 0

**Use:** Final invitation before the footer.

**CSS:** `background: #eaeaea; padding: 100px 0px`

#### Footer charcoal · level 0

**Use:** Full-width ending and utility area.

**CSS:** `background: #222222; color: #f7f7f7`

#### Pale detail chapter · level 0

**Only for:** capability-detail pages

**Use:** Alternating light capability chapters.

**CSS:** `background: #f5f5f5; padding: 128px 0px`

#### Dark detail chapter · level 0

**Only for:** capability-detail pages

**Use:** Dark capability chapters.

**CSS:** `background: #141414; padding: 128px 0px; color: #f7f7f7`

#### Dark detail card · level 1

**Only for:** capability-detail pages

**Use:** Paired demonstration cards on dark chapters.

**CSS:** `background: #242424; border-radius: 6px; padding-top: 48px; overflow: hidden`

**Observed:** Pale equivalents are white with a faint 0px 3px 30px shadow at black 5% alpha.

#### Commercial canvas · level 0

**Only for:** pricing pages

**Use:** Neutral backdrop for commercial information.

**CSS:** `background: #f5f5f5`

**Observed:** The recommended comparison column uses rgba(34,34,34,0.05), reading as #eaeaea against this ground.

## Components

### Floating navigation

**Use:** Persistent brand and primary navigation.

**CSS:** `position: fixed; top: 20px; left: 20px; right: 20px; height: 62px; padding: 8px 10px; border-radius: 4px; backdrop-filter: blur(50px); display: flex; justify-content: space-between; align-items: center; z-index: 5`

**Text style:** `navigation` — Inter Tight 500 · 15px/1.4

**Observed:** Identity sits left; short navigation labels occupy the right half and terminate in Account action. The transparent glass picks up the colors and tones of artwork behind it.

**States:** Declared: hover on navigation labels reduces opacity to 0.6.

**Transfer:** Use a compact identity and a short menu rather than a full opaque masthead.

### Opening action

**Use:** Default first-screen conversion.

**CSS:** `background: #222222; color: #ffffff; border-radius: 4px; height: 42px; padding: 12px 28px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `hero-action` — Inter 600 · 16px/1.15 · tracking -0.04em

**Observed:** A northeast arrow follows the label; the action belongs directly to the lower-right support paragraph.

**States:** Declared: hover opacity 1.

### Account action

**Use:** Top-right persistent login and registration entry.

**CSS:** `background: #222222; color: #ffffff; border-radius: 4px; height: 46px; padding: 12px 20px 12px 24px; display: inline-flex; align-items: center`

**Text style:** `account-action` — Inter 600 · 16px/1.4 · tracking -0.04em

**Observed:** One compact rectangular action combines two account destinations with a diagonal slash.

**States:** Declared: hover opacity 1.

### Feature action tab

**Use:** Small action over a panel's media, generally near its lower-right corner.

**CSS:** `background: #222222; color: #f7f7f7; border-radius: 8px; height: 46px; padding: 12px 24px; box-shadow: 0px 2px 15px 0px rgba(0, 0, 0, 0.1); display: inline-flex; align-items: center`

**Text style:** `card-action` — Inter Tight 700 · 16px/1.4

**Observed:** The tab contains a label and tiny northeast arrow. Dark media uses a white tab with dark ink; the work-wall version uses the soft inverse fill.

**States:** Declared: hover removes the dark tab's shadow and keeps opacity 1; the white lead-panel tab also removes its shadow on ancestor hover.

**Transfer:** Pin the tab to the media area rather than creating a full-width card footer.

### Capability panel

**Use:** Large benefit plus product demonstration.

**CSS:** `background: #ffffff; border-radius: 8px; padding: 48px 0px 0px 80px; overflow: hidden; display: flex; align-items: center; justify-content: space-between`

**Text style:** `card-heading` — Inter 700 · 48px/1.1 · tracking -0.04em

**Observed:** The lead panel spans the grid, with a left text group and right interface extending to the panel edge. Subsequent paired cards stack text above media. Feature action tab floats over the lower-right media area.

**Transfer:** Show one real task per panel. Keep explanations in card-body type and let cropped interface windows occupy about half or more of the panel.

### Portrait story

**Use:** Human proof with editorial pacing.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; width: 431px`

**Text style:** `story-heading` — Inter 700 · 36px/1.2 · tracking -0.04em

**Observed:** Tall grayscale portrait first, then a short occupational label, name, slash-led first-person quote and a bare Read Story link with northeast arrow. Label-to-name gap is 8px, name-to-quote 16px; there is no white card behind the text.

**Transfer:** Use real practitioners or people affected by the product; preserve portrait scale and direct testimony rather than compressing them into logo cards.

### Closing action

**Use:** Final conversion below the broad closing sentence.

**CSS:** `background: #222222; color: #ffffff; border-radius: 6px; height: 52px; padding: 12px 24px 12px 32px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `closing-action` — Inter 600 · 20px/1.4 · tracking -0.04em

**Observed:** Larger label than other marketing buttons, followed by a northeast arrow. It stays left aligned with the closing sentence.

**States:** Declared: hover opacity 1.

### Footer navigation

**Use:** Complete ending after the closing band.

**CSS:** `background: #222222; color: #f7f7f7; display: flex; flex-wrap: wrap; justify-content: space-between; padding: 60px 100px`

**Text style:** `footer-link` — Inter 400 · 16px/1.66

**Observed:** Four equal columns. The identity column includes a compact mark, a small two-part greeting and subdued social icons; middle columns contain category headings and stacked links; the final column is a short utility list. A darker-looking low-contrast utility row beneath holds copyright left and language right.

**States:** Declared: ordinary footer links retain opacity 1; selected utility links reduce opacity to 0.7; the language link changes to soft inverse text with an underline.

### Plan card

**Only for:** pricing pages

**Use:** Contiguous plan comparison with one emphasized choice.

**CSS:** `background: #ffffff; padding: 40px 32px; border-right: 1px solid #e6e6e6; display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `plan-heading` — Inter 700 · 24px/1.4 · tracking 0.02em

**Observed:** Plan name, tiny audience description, compact price row, benefits and bottom-aligned Plan action. Outer corners of the overall group are 16px; inner cards are square. One plan reverses to charcoal with pale text. Bright blue strips rise above selected columns, while the matching comparison table highlights the recommended column with a faint gray wash.

**Transfer:** Keep five equal columns only when five meaningful plans exist; preserve contiguous edges and a single reversed emphasis rather than separate floating cards.

### Plan action

**Only for:** pricing pages

**Use:** Bottom-aligned plan selection.

**CSS:** `background: transparent; color: #222222; border: 1px solid #333333; border-radius: 48px; height: 52px; padding: 0px 20px; display: flex; align-items: center; justify-content: center`

**Text style:** `plan-action` — Inter 600 · 14px/1.4

**Observed:** Spans the card's inner width. The reversed recommended plan uses a pale-filled action; the two-column team-plan variant uses the same outline stretched across a wider card.

**States:** Declared: hover background #333333, border 1px solid #333333 and text #ffffff.

### FAQ row

**Only for:** pricing pages

**Use:** Objection handling below commercial tables.

**CSS:** `background: #ffffff; border-bottom: 1px solid #ededed; height: 89px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `faq-question` — Inter 700 · 18px/1

**Observed:** Questions are inset 40px from the group edges; a thin plus sits at far right. Rows form one wide white group with 16px outer top and bottom corners. Expanded answers use smaller regular paragraphs and occasional underlined links.

**Transfer:** Keep question text direct and service-oriented. Do not display closed answers outside their rows.

## Imagery and graphics

### Staircase exhibition

**Use:** Signature first-screen artwork.

**Observed:** A diagonal chain climbs from beyond the bottom-left edge to beyond the upper-right edge. Each step pairs a vivid rectangular finished-work image with a square color or typographic tile; diagonal slash motifs recur in the companion tiles. Media occupies the center, leaving upper-left headline and lower-right support legible. Rectangles touch without rounded frames or device mockups.

**Transfer:** Create a coordinated set of finished outputs for the new product. If outputs are not intrinsically visual, use designed report covers, annotated outcomes or editorial result boards with strong image-and-type compositions; a generic icon mosaic is not an equivalent.

**Build:** Build an overflow-hidden stage with repeated steps offset right and upward by one square per step. At desktop, use roughly 190px squares and 380px-wide image companions. Fill companion tiles with colors sampled from adjacent artwork; create the diagonal slash with a thick cream SVG parallelogram or a rotated rectangular pseudo-element. Run the chain behind the text layer, allowing the first and last steps to leave the viewport. Treat these dimensions as a composition guide.

### Interface windows

**Use:** Evidence inside capability panels and the centered detail opening.

**Observed:** Large desktop editor windows show dark tool chrome around colorful content; the lead window is roughly 657×406px and extends into the right edge of its white panel. Other examples sit around 612×378px or 630×390px. Corners are 4–8px with restrained black 10% shadows, not glows.

**Transfer:** Use actual product screens with one clear operation and enough surrounding chrome to establish context. A carefully authored static interface with realistic content is an acceptable minimum; avoid empty dashboard shells.

### Edge-clipped output gallery

**Use:** Broad visual proof field.

**Observed:** Three finished-site images per row, around 480×333px, separated by 20px and clipped at the outer page edges. The content varies strongly in color and type while the backing stays pale gray; there are no explanatory cards below each image.

**Transfer:** Curate heterogeneous but polished examples of outcomes, matching image ratios and crop logic rather than making every example look like the marketing site.

### Grayscale practitioner portraits

**Use:** Editorial social proof.

**Observed:** Large vertical portraits, approximately 431×600px, use grayscale with both soft daylight and deep silhouette treatments. Small 8px corners and occasional faint shadow; text sits below on the gallery canvas.

**Transfer:** Choose authentic portraits with environmental or character detail. Preserve a varied grayscale range instead of tinting every image to the same washed-out gray.

### Diagonal work wall

**Use:** Signature high-contrast invitation panel.

**Observed:** A 1312×700px black-backed panel with 8px corners and 64px outer side margins contains a dense rotated grid of finished pages. Strong black gutters separate tilted rectangles. A left-heavy scrim supports a pale headline and paragraph with a light action tab; artwork remains visible to the right.

**Transfer:** Use the new product's output boards or curated proof imagery. Reuse the opening's media vocabulary but change its spatial treatment into a dense, darkened wall.

**Build:** Place a four-column grid of square media boards behind an overflow-hidden black panel; oversize the grid beyond all edges and rotate it about -45deg. Use black gutters around 12–20px and cover each tile with its image. Add Work wall scrim above the grid and a left-aligned text layer above that. Use the 434px tile dimension as a desktop construction guide, keeping exact rotation and tile packing flexible.

### Icons

**Observed:** Small northeast arrows are the dominant action marker, approximately 9–12px; larger arrows are not used to compete with text. Navigation uses a tiny downward chevron. Commercial tables use open circles for inclusion and faint horizontal dashes for absence; FAQ rows use fine plus marks.

**Transfer:** Use simple monochrome arrows and geometric status marks. Preserve open-circle comparison marks rather than replacing them with colorful checks; keep social icons subdued and subordinate.

## Section recipes

How recurring sections are built.

### First screen: Diagonal exhibition opening

**Observed:** The first 900px form a complete light-gray stage. Floating navigation overlays the top. Behind the text, Staircase exhibition crosses from below the lower-left edge to above the upper-right edge. In front, the 80px/1 weight-600 display wraps into two strong lines over about two fifths of the width at upper left, with a 30px side inset and 140px top breathing room. A 345px-wide body paragraph anchors the lower-right quarter, followed after 28px by Opening action. The first screen shows the headline, work chain, support and action in full, while the chain continues beyond its top and bottom boundaries. The next demonstration section begins below the fold.

**Transfer:** Make the collage show tangible outcomes, not abstract decorations, and adapt line breaks so the title and support occupy opposite corners of the exhibition. For a product without suitable media, create high-quality outcome boards and companion slash tiles. Pricing opens instead with a small page label, centered-display and centered-support on pale gray; capability-detail openings use that same centered hierarchy above a broad interface window, reserving a left index rail.

**Avoid:** Do not turn this into a centered headline over a single floating laptop, put the paragraph beneath the upper-left title, or obscure the collage with a solid navigation slab.

**Text style:** `display` — Inter 600 · 80px/1 · tracking -0.04em

### Capability exhibition

**Observed:** A chapter lead sits in the dark top of Capability fade; the panel field below starts with one wide Capability panel and continues with paired white panels. At desktop the content spans 1368px, with 28px column gaps and 30px row spacing. Titles use card-heading, explanations card-body, and Feature action tab sits over media.

**Transfer:** Organize around user benefits with one task per media scene. The wide introductory panel can establish the product's main workspace; paired panels cover narrower workflows.

**Text style:** `card-heading` — Inter 700 · 48px/1.1 · tracking -0.04em

### Output proof field

**Observed:** Edge-clipped output gallery uses repeated three-column rows on Exhibition canvas. One compact graphic mark can separate row groups without adding a large block of explanatory prose.

**Transfer:** Let varied real outputs substantiate the promise. Adjust the number of rows to the available quality of examples, keeping the edge-clipped exhibition character.

### Editorial proof pair

**Observed:** A large centered editorial heading introduces a narrower two-column grid after 96px. Portrait story columns are 431px wide with a 190px gutter; imagery is taller than the accompanying copy. Names, slash-led testimony and Read Story actions remain left aligned.

**Transfer:** Give human evidence room to be read as stories rather than condensed testimonial widgets.

**Text style:** `story-heading` — Inter 700 · 36px/1.2 · tracking -0.04em

### Dark diagonal invitation

**Observed:** Diagonal work wall sits inside 64px side margins, using heading and wall-body in pale text and a light Feature action tab. The text occupies the left portion while tilted examples fill the entire background.

**Transfer:** Use this device for a low-friction starting point, collection or secondary conversion relevant to the product; it need not advertise templates.

**Text style:** `heading` — Inter 700 · 64px/1 · tracking -0.04em

### Closing invitation and complete footer

**Observed:** Closing band presents a broad closing-heading aligned to the left of a 1296px content field with Closing action 16px below; it is not a centered CTA card despite the headline's internal text alignment. After 100px bottom padding the full-width Footer navigation begins, followed by a subdued utility strip. The same ending works after galleries, long capability chapters and pricing tables.

**Transfer:** End with a brief verb-led invitation using the new product's core outcome, then provide real navigation and utilities. Preserve the strong pale-to-charcoal boundary.

**Text style:** `closing-heading` — Inter 600 · 64px/1.66 · tracking -0.04em

### Centered chapter pair

**Only for:** capability-detail pages

**Observed:** Alternating Dark detail chapter and Pale detail chapter bands start with a 20px label, a 32px gap to a 64px headline, then a 24px gap to centered detail-body text around 700px wide. Demonstration content follows in paired 562px cards. Dark headings use a 1.4 line height; pale headings use 1.2 and tighter tracking. A persistent left chapter index explains the right-shifted content.

**Transfer:** Keep each chapter tied to one capability and use light/dark alternation to distinguish kinds of work rather than changing the color palette arbitrarily.

**Text style:** `detail-dark-heading` — Inter 700 · 64px/1.4 · tracking -0.04em

### Commercial comparison

**Only for:** pricing pages

**Observed:** A centered page label, 80px headline and 21px support sentence lead to a compact annual/monthly toggle. Contiguous Plan cards use one charcoal reversal and narrow blue recommendation strips. Below, a full comparison table repeats plan headers with a faint highlighted column, compact row labels, open-circle inclusion marks and hairline category rules. A separate two-column team offering and a grouped FAQ follow.

**Transfer:** Separate fast plan choice from detailed comparison. Use real plan counts, relevant units and plain-language FAQs rather than copying the particular offers.

**Text style:** `centered-display` — Inter 700 · 80px/1 · tracking -0.04em

## Page flow

**Storyline:** Outcome promise → tangible product and output proof → focused capability or decision blocks → human evidence or objections → final invitation → full utility footer.

### Broad product marketing with a creative exhibition character

1. **Promise** — Opposite-corner headline and support around a diagonal chain of finished work.
2. **Product demonstration** — Large media-led demonstration followed by a dark-to-light capability panel exhibition.
3. **Output proof** — Multiple edge-clipped rows of diverse finished examples.
4. **Human proof** — Large grayscale portraits, occupational labels and first-person stories.
5. **Secondary conversion** — Dark diagonal work wall offers a concrete starting point.
6. **Closing call** — Broad pale invitation, small dark action and complete charcoal footer.

**Transfer:** Use finished outcomes and workspace demonstrations as the main argument, with editorial proof to humanize the product. The exhibition devices can move to suit the story.

### Focused capability explanation

1. **Promise** — Centered headline and support above a large interface window with a left chapter index.
2. **Capability chapters** — Alternating dark and pale bands with category labels, 64px headings, paired demonstrations and an interactive animation field.
3. **Expanded demonstration** — Full-bleed video-backed scene and paired integration examples broaden the argument.
4. **Closing call** — Shared pale invitation and charcoal link footer.

**Transfer:** Use the indexed chapter structure when the product requires deeper explanation; do not import the left rail into a short general landing page.

### Plan selection and purchase reassurance

1. **Promise** — Centered small label, direct 80px commercial headline and one support sentence.
2. **Pricing** — Billing toggle and contiguous plan cards with blue strips and one reversed plan.
3. **Detailed comparison** — Compact table with repeated headers, category rules and faint recommended-column emphasis.
4. **Alternative offer** — Separate team-oriented pricing in two wider contiguous columns.
5. **Objection handling** — Wide grouped white FAQ rows, followed by a secondary support link.
6. **Closing call** — Shared broad invitation and complete dark footer.

**Transfer:** Maintain the neutral comparison architecture while tailoring plans, billing choices and objections to the new offer.

## Writing

Confident and warmly playful. Benefits are made concrete with short verbal turns and light wordplay, while explanations and commercial terms stay direct and practical.

**Do not copy:** Do not reuse Studio.Design names, logo artwork, customer identities, portrait assets, project artwork, testimonials, prices, savings percentages, capability counts or product-specific claims. Source quotations illustrate rhythm only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your. Refer to the product by name when introducing it, then return to the reader's outcome; let testimonial voices speak in first person.
- **Rhythm:** Headlines are often 3–7 words, sometimes two fragments separated by periods. Support is one or two conversational sentences. Short imperative actions punctuate the longer image-led sections.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A welcoming imperative or rhythmic series of short clauses about the reader's outcome. | 5–8 words | “Say Hello To Your New Site.”<br>“Dream it. Make it. Love it.” |
| Capability title | Name the task, then twist it into a compact benefit with a rhyme, pun or spoken fragment. | 3–6 words | “CMS without mess.”<br>“Create site by side”<br>“Figma one sec. Site the next.” |
| Supporting explanation | State the task and the friction removed in plain, concrete language. | 15–35 words | “Publish your designs as live websites with just one click. Coding and server setup? It's all taken care of.” |
| Primary action | Verb plus immediate outcome, with a low-friction qualifier when true. | 2–5 words | “Start For Free”<br>“Get started for free” |
| Objection handling | Use the actual question a buyer asks, then answer without promotional embellishment. | 6–12 words for questions | “Can I cancel or downgrade my plan?”<br>“What payment methods are accepted?” |

**Words and phrasing to use:** your; start; make; create; easy; built in; in a click; all taken care of; short task-based wordplay

**Avoid:** enterprise-grade transformation; revolutionary ecosystem; unparalleled synergy; dense technical jargon in headlines; urgent scarcity language

**Rules:**

- Use playful phrasing to clarify a benefit, not to conceal what the product does.
- Keep paragraphs short enough to sit beside large media rather than becoming the main visual mass.
- Pair broad creative freedom with a concrete operation or outcome in the next sentence.
- Let commercial answers be factual, including limitations and billing conditions.
- A slash can introduce a story quote; do not scatter decorative slashes through every paragraph.

## Do's and Don'ts

### Do

- Set the default hero at 80px/1, weight 600, with -0.04em tracking and deliberate two-line wrapping.
- Balance upper-left display text with a 345px lower-right support column rather than aligning all opening content to one axis.
- Keep capability panels white with 8px corners and substantial 48–80px internal breathing room.
- Use 9–12px northeast arrows as subordinate action details.
- Let colorful outcomes occupy broad media areas while page backgrounds remain gray, white or charcoal.
- Include a darkened diagonal work wall with pale type, 8px corners and 64px desktop side margins.
- Give portrait stories 431px columns and generous space between them at desktop.
- Close with a left-aligned 64px invitation on #eaeaea, then a full-width #222222 four-column footer.

### Don't

- Do not apply pill corners to every CTA: 48px outlined pills belong to plan selection, not the ordinary 4–8px marketing actions.
- Do not use #0275fd as a default hero background or primary marketing button fill; it marks commercial choices.
- Do not introduce serif or display fonts into marketing headings because one appears inside depicted customer work.
- Do not turn the broad capability panels into small equal-height icon cards with 24px titles.
- Do not add thick borders or strong colored shadows around the white panel grid; contrast comes from backing and media.
- Do not tint all human portraits to a single flat gray; retain daylight detail and deep shadow variation.
- Do not put story quotes in white floating cards or replace their portraits with tiny circular avatars.
- Do not center the closing invitation or reduce the ending to a lone CTA without link columns and utilities.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.3s transitions with cubic-bezier(0.4, 0.4, 0, 1), plus transitionable gradient custom properties.
- The navigation declares an 800ms duration with cubic-bezier(0.2, 1, 1, 1); the white lead-panel action declares 400ms with cubic-bezier(0, 0.5, 0.22, 1).
- Navigation label hover opacity is 0.6; many action hover rules explicitly retain opacity 1. Feature tab shadows are removed in declared hover states.

**Transfer:**

- Keep interaction concentrated in the glass header, action tabs and image-led demonstrations. Preserve the declared opacity and shadow changes rather than adding large button lifts.

**Unknown:**

- Timing and trajectories of collage movement, scrolling scenes and interactive demonstrations are not established.
- No focus-visible or active appearance is established for the main actions.

### Responsive

**Observed:**

- The established composition is desktop at 1440×900px; no width breakpoint rules are established.

**Transfer:**

- On narrow screens, preserve the diagonal exhibition but place readable text and actions above its clipped media layer; do not shrink the 345px support column into unreadable fragments.
- Stack capability and portrait columns while keeping text before media and preserving rectangular action tabs.
- Move the chapter index into a compact section navigation when it would consume the reading width; keep plan comparisons horizontally navigable if their labels cannot fit. These are adaptation recommendations, not alternate measured layouts.

**Unknown:**

- Mobile font sizes, exact breakpoints, menu behavior and small-screen gallery motion remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
