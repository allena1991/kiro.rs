# Monad — editorial circuitry in pastels

## Overview

A warm, light technical aesthetic that pairs bookish serif headlines with matter-of-fact monospace explanations. Fine outlines and soft mint, periwinkle, coral and amber light make infrastructure feel approachable rather than industrial. Sparse diagrams, small interface fragments and spacious editorial layouts suit complex software and technical services; people-focused content adds natural, warmly lit photography.

### Essentials

- Technical promises read like editorial titles, not dashboard UI: regular serif headlines at 80px/1.2 with -0.02em tracking, stepping down to 48px/1.2 for section leads, against monospace body text at 20px/1.35.
- The opening explains before it dazzles: a centered two-line headline spans roughly two thirds of the canvas, followed by a narrow support paragraph and paired 48px pill actions; a fine-line process diagram enters at the lower edge of the first 900px.
- Color behaves like light falling onto paper: #f6f3f1 dominates, text stays black or charcoal, and 50–75px blurred pastel ellipses illuminate diagrams and card corners. A single periwinkle band provides a stronger change of scene rather than alternating saturated sections.
- Soft silhouettes meet crisp engineering: 16px outlined cards, 40px rounded feature bands, pill buttons and 64px circular logo medallions; borders remain 1px and ordinary cards have no drop shadow.
- A signature system drawing makes the abstract tangible: thin connector paths, compact labeled nodes and small colored signals over a mint or blue glow. Rebuild the new product's input-to-outcome relationship as SVG when interface media is unavailable.
- The ending is a warm illuminated invitation, not a dark conversion slab: a centered 48px serif promise, monospace support and pill actions sit inside a 40px-radius outlined panel with amber light rising from its bottom; the footer returns to bare paper and includes a small location-time detail.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cobalt action | `#3155c5` | `--color-action-blue` | action | Small demo-action pill in the navigation; keep the saturated blue confined to this action. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Periwinkle field | `#cfdaf5` | `--color-feature-band` | background, surface | The broad ecosystem feature band. |
| Periwinkle light | `#a0b5eb` | `--color-blue-light` | accent | Blurred blue illumination behind technical illustrations and card corners. |
| Mint light | `#a7fccd` | `--color-mint-light` | accent | Diffuse mint illumination around process graphics. |
| Gold light | `#e2c161` | `--color-gold-light` | accent | Soft gold halo at panel edges and benefit cards. |
| Coral wash | `#fea78c` | `--color-coral-light` | accent | Visible coral glow from rgba(255,148,115,0.8) over paper; soften further at the edges. |
| Amber wash | `#f59e4f` | `--color-amber-light` | accent | Visible warm closing glow made with rgba(243,122,10,0.7) over paper. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blush paper | `#f8f3f1` | `--color-light-paper` | surface, text | Light button lettering, circular logo backing and form fields. |
| Warm paper | `#f6f3f1` | `--color-canvas` | background, surface, text | Dominant page canvas and light reversed text. |
| Faint rule | `#e3dedd` | `--color-rule` | border | Accordion and footer separators; rgba(36,36,36,0.1) over paper. |
| Soft card edge | `#cecac8` | `--color-card-edge` | border | Process-card edges; rgba(36,36,36,0.2) over paper. |
| Focus gray | `#9c9998` | `--color-focus` | border, text | Focus-visible outline and low-emphasis lettering. |
| Muted charcoal | `#797776` | `--color-muted` | text | Secondary copy, footer headings and legal information; rgba(36,36,36,0.6) over warm paper. |
| Soft charcoal | `#4e4d4d` | `--color-body` | text | Visible body-text tone; rgba(36,36,36,0.8) over warm paper. |
| Charcoal | `#242424` | `--color-ink` | text, border, action | Section headings, outlined benefit cards and default dark pills. |
| Black | `#000000` | `--color-black` | text, background, border | Display titles, announcement strip and strongest outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| contact and recruiting forms | Field edge | `#dcdcdf` | `--color-field-edge` | border | Form input borders. |

## Typography

- **Untitled Serif** — Display titles, section leads, card headings and form labels. A restrained editorial serif with moderate contrast and conventional proportions, predominantly regular. If unavailable, use **Libre Caslon Text**. Use regular weight and retain tight tracking; check line breaks against its wider lowercase. Font stack: "Untitled Serif", "Libre Caslon Text", "Times New Roman", serif.
- **ABC Diatype Mono** — Body copy, navigation, buttons, labels and footer. Open, readable monospaced text that supplies the technical character even in prose. If unavailable, use **IBM Plex Mono**. Use 400 for normal text; preserve the compact negative tracking in body copy. Font stack: "ABC Diatype Mono", "IBM Plex Mono", ui-monospace, monospace.
- **Untitled Sans** (only for compact process cards) — Short explanatory paragraphs alongside process illustrations. Plain proportional sans that allows denser explanations without competing with the serif titles. If unavailable, use **Inter**. Font stack: "Untitled Sans", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Untitled Serif | 400 | 80px | 1.2 | -0.02em | Centered primary marketing promise and editorial page titles. |
| heading | Untitled Serif | 400 | 48px | 1.2 | -0.02em | Section leads, feature-band title and closing promise; also the split technical-detail opening. |
| card-heading | Untitled Serif | 400 | 32px | 1.2 | -0.02em | Benefit-card titles and embedded question rows. |
| small-heading | Untitled Serif | 400 | 24px | 1.2 | -0.02em | Process-card headings, culture items and visible form labels. |
| body | ABC Diatype Mono | 400 | 20px | 1.35 | -0.02em | Primary support paragraphs, benefit explanations and closing support. |
| small-body | ABC Diatype Mono | 400 | 16px | 1.35 | -0.025em | Embedded accordion answers, announcements and small secondary copy. |
| eyebrow | ABC Diatype Mono | 400 | 16px | 1.3 | 0.05em, uppercase | Trust-strip labels, footer group headings and location-time detail. |
| navigation | ABC Diatype Mono | 400 | 16px | 1.35 | 0.05em, uppercase | Desktop header navigation. |
| footer-link | ABC Diatype Mono | 400 | 16px | 1.3 | 0.05em, capitalize | Short directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| dedicated question pages | faq-heading | Untitled Serif | 400 | 40px | 1.2 | -0.02em | Larger question titles in the narrower standalone accordion. |
| technical feature chapters | detail-heading | Untitled Serif | 400 | 22.4px | 1.2 | -0.02em | Three small subheadings within a feature chapter. |
| compact process cards | compact-copy | Untitled Sans | 400 | 16px | 1.35 | -0.02em | Proportional explanatory copy in the technical mosaic. |
| company and recruiting sections | editorial-small-body | ABC Diatype Mono | 400 | 16px | 1.35 | -0.02em | Values, benefits and team support copy. |
| technical-detail openings | compact-button | ABC Diatype Mono | 400 | 14.4px | 1.1 | 0.05em, uppercase | Smaller trial pill beneath the split opening. |
| technical feature chapters | detail-body | ABC Diatype Mono | 400 | 13.6px | 1.35 | -0.029em | Compact descriptions in feature subcolumns. |

**Notes:**

- Keep editorial serif and technical mono in dialogue: headings are not bold sans, and prose is not uniformly proportional sans.
- All regular serif recipes use 1.2 line height and -0.02em tracking. Mono prose uses 1.35 line height, while uppercase labels reverse the tracking to +0.05em.
- Default display is 80px; the compact split technical opening deliberately uses the 48px heading recipe rather than shrinking the whole marketing system.

## Layout

**Density:** Airy: long section intervals frame compact, information-rich cards and finely spaced technical labels.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Vertical space between footer links. |
| 12px | Process-mosaic gutters and header action gap. |
| 16px | Small title-to-copy intervals and logo-to-label gaps. |
| 20px | Benefit-card gutters and form horizontal inset. |
| 24px | Benefit title-to-copy interval, footer columns and form row gap. |
| 32px | Navigation link spacing. |
| 40px | Container side padding, benefit-card padding, heading-to-content separation and embedded accordion inset. |
| 48px | Technical chapter inner padding. |
| 50px | Trust-strip vertical padding. |
| 60px | Breathing space before the footer and technical subcolumns. |
| 64px | Split form gutter and compact-section spacing. |
| 80px | Closing-panel vertical padding. |
| 100px | Standard major-section vertical padding. |
| 128px | Technical-chapter stack outer vertical padding. |
| 200px | Tall feature-band vertical breathing room. |

### Containers and grids

- **main-container**: max width 1432px · side padding 40px. Centered outer container; at 1440px the text edges sit 44px from the window and the usable content width is 1352px.
- **benefit-grid**: 2 columns · gap 20px. Equal-width outlined benefits; desktop cards are about 666px wide.
- **process-mosaic**: 3 columns · gap 12px. One tall card occupies the left third; the right two thirds contain stacked landscape cards.
- **footer-directory**: 4 columns · gap 24px. Directory occupies the right portion of the footer, opposite the brand and social block.
- **technical-container** (only for technical feature pages): max width 1600px · side padding 72px. Feature chapters occupy 1296px of the 1440px viewport.
- **form-split** (only for contact and recruiting forms): 2 columns · gap 64px. Equal form and photographic columns; each is about 644px wide at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons | 9999px (pill) |
|  | cards | 16px |
|  | feature-and-closing-panels | 40px |
|  | logo-medallions | 50% |
| contact and recruiting forms | form-fields | 10px |
| company credibility sections | investor-tiles | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| logo-medallion | `0px 0px 10px 0px rgba(0,0,0,0.1)` | Small circular logo carriers in the ecosystem field; do not extend to normal cards. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous warm background.

**CSS:** `background: #f6f3f1; color: #242424`

#### Outlined card · level 1

**Use:** Benefit groups that stay visually attached to the page.

**CSS:** `background: transparent; border: 1px solid #242424; border-radius: 16px; box-shadow: none; overflow: hidden`

**Observed:** The page color continues through the card; an inset pastel halo supplies local illumination.

**Transfer:** Use thin outlines to group content instead of filled gray tiles.

#### Process card · level 1

**Use:** Technical mosaic panels.

**CSS:** `border: 1px solid rgba(36,36,36,0.2); border-radius: 16px; overflow: hidden; position: relative`

**Observed:** Softer edges than the benefit cards keep multiple nested process illustrations from becoming heavy.

**Transfer:** Maintain the softer outline when cards contain their own interface borders.

#### Periwinkle field · level 0

**Use:** An expansive ecosystem or compatibility feature.

**CSS:** `background: #cfdaf5; border-radius: 40px; overflow: hidden`

**Observed:** A nearly full-width band carries left-aligned text and a large clipped field of names and circular marks to the right.

**Transfer:** Use as one strong chromatic change of scene, not the default card fill.

#### Pastel halo · level 0

**Use:** Light behind diagrams and at card corners.

**CSS:** `background: linear-gradient(rgba(255,148,115,0.8) 7%, rgba(160,181,235,0.8) 83.82%); border-radius: 50%; filter: blur(50px); position: absolute`

**Observed:** Large ellipses sit behind rather than over the readable content; blue-mint and gold-orange combinations also occur.

**Transfer:** Keep the neutral page visible around every glow; match the soft light rather than a hard gradient boundary.

#### Warm invitation panel · level 1

**Use:** Signature closing conversion surface.

**CSS:** `position: relative; border: 1px solid #242424; border-radius: 40px; padding: 80px 16px; overflow: hidden; margin-bottom: 60px`

**Observed:** A gold glow brushes the top edge and a broad amber glow rises from below, leaving the central text clear.

**Transfer:** Keep the illuminated lower edge and centered content even when the action is an enquiry rather than a trial.

#### Fading navigation backing · level 2

**Use:** Sticky navigation without a hard rectangular lower edge.

**CSS:** `background: linear-gradient(#f6f3f1 48%, rgba(246,243,241,0.85) 70%, rgba(246,243,241,0)); z-index: 1000`

**Observed:** Paper fades toward transparency beneath the navigation row.

**Transfer:** Keep the backing neutral so technical art can pass behind it without changing the header's tone.

## Components

### Sticky navigation

**Use:** Persistent global wayfinding.

**CSS:** `position: sticky; z-index: 1000; height: 184px`

**Text style:** `navigation` — ABC Diatype Mono 400 · 16px/1.35 · tracking 0.05em · uppercase

**Observed:** A 62px black announcement strip sits over a 122px navigation row. Brand mark is left, spaced uppercase links and small chevrons occupy the middle, and login plus cobalt demo pills align right.

**States:** Declared: hover on the primary text link changes color to rgba(36,36,36,0.4) with no underline; focus-visible uses a 2px solid #9c9998 outline with 2px offset; active outline is 0px.

**Transfer:** Keep the navigation visually narrow and letterspaced despite the generous row height.

### Primary pill

**Use:** Default conversion action in the opening and closing panel.

**CSS:** `background: #242424; color: #f8f3f1; border-radius: 9999px; height: 48px; padding: 0px 32px; display: inline-flex; align-items: center; justify-content: center; font-size: 18px; line-height: normal; letter-spacing: -0.4px; text-transform: uppercase`

**Text style:** `small-body` — ABC Diatype Mono 400 · 16px/1.35 · tracking -0.025em

**Observed:** Solid charcoal with a compact uppercase label; secondary actions use light paper or a faint outline and sit beside it. Header actions add a small right chevron.

**Transfer:** Keep the main action dark; reserve cobalt for the navigation demo action.

### Benefit card

**Use:** Outcome-led explanations.

**CSS:** `position: relative; border: 1px solid #242424; border-radius: 16px; padding: 40px; overflow: hidden`

**Text style:** `card-heading` — Untitled Serif 400 · 32px/1.2 · tracking -0.02em

**Observed:** Small dark icon first, serif title next, then monospace explanation; the title-to-body gap is 24px. An upper-left halo is clipped behind the content.

**Transfer:** Give each benefit a distinct pastel light, not a distinct solid card color.

### Process card

**Use:** Illustrated steps or capabilities in an asymmetric mosaic.

**CSS:** `position: relative; display: flex; flex-direction: column; border: 1px solid rgba(36,36,36,0.2); border-radius: 16px; padding: 24px 16px; overflow: hidden`

**Text style:** `small-heading` — Untitled Serif 400 · 24px/1.2 · tracking -0.02em

**Observed:** Tall variant places a process illustration beneath icon, heading and proportional copy. Landscape variants divide text and diagram side by side and use 64px vertical padding.

**Transfer:** Preserve asymmetric card proportions rather than making every capability an identical tile.

### Question row

**Use:** Embedded objection handling.

**CSS:** `display: flex; justify-content: space-between; gap: 16px; padding: 40px; border-bottom: 1px solid rgba(36,36,36,0.1)`

**Text style:** `card-heading` — Untitled Serif 400 · 32px/1.2 · tracking -0.02em

**Observed:** Serif question at left, 24×38px drawn downward arrow at far right, answer revealed below in small-body text. The dedicated question-page variant uses 40px serif questions, black rules and 32px circled plus signs.

**Transfer:** Keep the embedded version broad and lightly ruled; use the larger, narrower variant only for a question-focused page.

### Logo medallion

**Use:** Named integrations in the chromatic ecosystem field.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 64px; height: 64px; padding: 15px; background: #f8f3f1; border-radius: 50%; box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1)`

**Observed:** A roughly 34px mark sits inside the disc; a large serif name follows with a 16px gap. Items near the field edges fade.

**Transfer:** Use small relevant symbols if partner marks are unavailable, but retain the paired disc-and-name construction.

### Footer directory link

**Use:** Footer navigation and small resource lists.

**CSS:** `color: #000000; text-decoration: none; transition: color 0.2s`

**Text style:** `footer-link` — ABC Diatype Mono 400 · 16px/1.3 · tracking 0.05em · capitalize

**Observed:** Four link columns follow muted uppercase headings, opposite a brand and social block; links use 10px vertical gaps. A local-time line sits beneath the directory before a faint rule and compact legal baseline.

**States:** Declared: hover changes color to rgba(36,36,36,0.6) with no underline; focus-visible uses a 2px solid #9c9998 outline with 2px offset; active outline is 0px.

### Compact trial pill

**Only for:** technical-detail openings

**Use:** Small action under the split technical promise.

**CSS:** `background: #000000; color: #f6f3f1; border: 1px solid #000000; border-radius: 60px; height: 38px; padding: 10.8px 23px 9.4px`

**Text style:** `compact-button` — ABC Diatype Mono 400 · 14.4px/1.1 · tracking 0.05em · uppercase

**Observed:** A deliberately smaller action than the standard marketing pill.

**States:** Declared: hover makes the background transparent and text black with no underline; focus-visible uses a 2px solid #9c9998 outline with 2px offset; active outline is 0px.

### Technical chapter card

**Only for:** technical feature chapters

**Use:** Deep explanation of one capability with a matching demonstration.

**CSS:** `border: 1px solid #000000; border-radius: 16px; padding: 48px`

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

**Observed:** A half-width editorial heading and monospace support sit opposite a roughly 516×420px illustration. Three small explanatory columns sit below the support; adjacent chapters reverse image and text.

**Transfer:** Use actual product mechanisms and short supporting benefits rather than arbitrary illustration.

### Form field

**Only for:** contact and recruiting forms

**Use:** Enquiry or application input.

**CSS:** `background: #f8f3f1; border: 1px solid #dcdcdf; border-radius: 10px; height: 67px; padding: 8px 20px`

**Text style:** `body` — ABC Diatype Mono 400 · 20px/1.35 · tracking -0.02em

**Observed:** Serif labels use small-heading with 16px separation above inputs. Names split in two columns, other inputs span full width; the textarea is 164px tall with 20px inset. A select uses a small right-aligned chevron.

**Transfer:** Pair the form with a tall warm photograph and retain the editorial labels instead of dashboard-style uppercase micro-labels.

## Imagery and graphics

### Illuminated system diagram

**Use:** Signature opening object and recurring technical explanations.

**Observed:** Fine gray connector lines join small outlined input and output labels around a central transformation symbol. Mint light radiates behind the center, with tiny coral, yellow and green signals along the paths. The opening diagram is broad, symmetrical and partially below the fold, not enclosed in a browser mockup.

**Transfer:** Draw a truthful input-to-outcome model for the new product. Minimum acceptable artwork is a carefully spaced SVG network with a central action, two groups of labeled terminals and one soft glow.

**Build:** Use an SVG spanning the content width. Place rounded terminal capsules on left and right, join them with 1px curved paths, and route them into a small stack of translucent rounded diamonds at center. Add tiny geometric signal markers on paths. Put a 448×295px blue-to-mint ellipse behind the center with blur(60px); keep paths and labels sharply drawn in front.

### Pastel light fields

**Use:** Required recurring material behind system art, in benefit-card corners and at the close.

**Observed:** Glows are oversized blurred ellipses clipped by rounded panels, not grainy gradients or glossy reflections. Process artwork uses coral-to-blue, blue-to-mint and gold-to-orange; benefit glows occupy the upper-left region and fade toward untouched paper.

**Transfer:** Carry the light system to new diagrams and outcomes even when no product imagery exists.

**Build:** For a benefit card, position a 376×238px ellipse partly beyond its upper-left edge, blur by 60px and set opacity to 0.7. Use blue, mint, gold or coral as neighboring gradient stops. For the closing panel, place a full-width gold ellipse mostly above the panel and a full-width amber ellipse below its center; blur both by 60px and clip inside the 40px-radius outline. Use rgba(243,122,10,0.7) for the lower glow.

### Interface fragments

**Use:** Evidence of how a capability works.

**Observed:** Small white workflow nodes, blue outlined condition chips, rule editors and chart panels are isolated rather than shown as full-screen applications. They float against paper and local glows, with lower edges sometimes softly fading; the chapter illustration occupies roughly half its card.

**Transfer:** Use a simplified real workflow or a clean interface excerpt that demonstrates one thing. Preserve legible hierarchy but do not reproduce an entire dense application shell.

### Curved ecosystem field

**Use:** A colorful compatibility or breadth-of-coverage moment.

**Observed:** Large serif names and light circular logo discs form a bowed vertical stream in the right half of a periwinkle band. Fine nested angular paths point inward; names at the top, bottom and right are intentionally clipped and faded.

**Transfer:** Represent categories, tools or destinations relevant to the new product. Keep the text on the left still and the right-hand field expansive.

**Build:** Clip a tall list inside the Periwinkle field. Offset rows horizontally along a shallow curve, pair each with a 64px disc, and apply an alpha mask toward top and bottom. Draw three thin open chevron paths behind the list in low-opacity charcoal; add a 454×516px coral-blue ellipse at the far right with blur(75px).

### Orbital line sculpture

**Only for:** technical-detail openings

**Use:** Abstract counterpart to a split product promise.

**Observed:** Multiple black elliptical loops pinch toward a common center, with a few small colored beads on their paths and a diffuse periwinkle glow behind. The graphic occupies the right half without a visible frame.

**Transfer:** Create a line-based metaphor for the new product's coordination or circulation, keeping it planar and fine rather than metallic 3D.

**Build:** Draw six to eight overlapping vertical cubic-Bezier loops in SVG with 1px charcoal strokes, a shared narrow middle and varied widths. Place a few small filled circles on the paths. Back the group with a blue elliptical glow blurred about 60px.

### Human editorial photography

**Only for:** company, recruiting and contact pages

**Use:** Team story, working culture and the companion image to a form.

**Observed:** A wide outdoor group photograph is centered below an editorial title. Culture images are tall, naturally lit workplace views through glass, with foliage and warm reflections. The form companion shows hands on a laptop with shallow-focus amber lights, occupying one full column; leader portraits are small circular headshots.

**Transfer:** Use authentic people and work settings with natural green and amber tones. Keep photography out of the default diagram-led product opening and avoid decorative cutout collages.

### Icons

**Observed:** Charcoal or black technical line symbols, mostly 33–40px in feature cards; tiny navigation chevrons are 12×8px with 1.5px strokes. Embedded accordions use a larger drawn arrow, while dedicated question lists use a thin circled plus.

**Transfer:** Choose simple schematic line icons with sparse geometry. Avoid multicolor filled app-style icons for explanatory features; use partner marks only inside their circular carriers.

## Section recipes

How recurring sections are built.

### First screen: Centered promise over circuitry

**Observed:** The first 184px belongs to Sticky navigation. Beneath it, a regular 80px serif promise forms two centered lines across roughly two thirds of the width; a narrow 20px mono support paragraph follows with about 40px separation. Primary pill and a light secondary pill sit centered beneath it with a 16px gap. Warm paper is the back layer, mint-lit circuitry enters below the actions, and labels and connectors stay in front of the glow. Within the first 900px the whole headline, support and actions are visible plus the upper portion of the main diagram; the complete diagram and trust strip continue below. The opening section extends 1019px beneath the header.

**Transfer:** Use the same hierarchy and a custom schematic of the new product's inputs, transformation and outcomes. Without media, make the diagram in SVG rather than leaving an empty hero. A technical-detail page can instead open with a 48px left-aligned promise and orbital illustration at right; editorial pages use an 80px centered title and authentic photograph, while question pages open with a short centered title.

**Avoid:** Do not replace the diagram with a generic dashboard rectangle or put a giant luminous object above the promise. Do not make the opening a dark gradient or a dense three-column sales layout.

**Text style:** `display` — Untitled Serif 400 · 80px/1.2 · tracking -0.02em

### Heading and illustrated mosaic

**Observed:** A left-aligned heading leads the Process card mosaic with 40px separation and 100px section padding. One tall left card spans the height of three stacked right-hand landscape cards; 12px gutters maintain a close family. Each card combines a small technical icon, small-heading, compact-copy and isolated mechanism illustration.

**Transfer:** Use this asymmetric arrangement when the story has one foundational mechanism and several supporting capabilities; change the number of explanations without turning the asymmetry into equal tiles.

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

### Trust ribbon

**Observed:** An uppercase mono eyebrow introduces a horizontal row of subdued customer marks; the strip has 50px top and bottom padding. Logo sizes remain modest, around 150–180px wide and roughly 30px high, with broad intervals.

**Transfer:** Use genuine credibility marks or brief proof statements in the same low-emphasis strip.

**Text style:** `eyebrow` — ABC Diatype Mono 400 · 16px/1.3 · tracking 0.05em · uppercase

### Chromatic breadth band

**Observed:** Periwinkle field pairs a left-aligned 48px title, mono explanation and dark pill with the Curved ecosystem field on the right. The band is about 692px tall and content has 40px horizontal inset; imagery spills toward the edge while text remains contained.

**Transfer:** Give a compatibility or reach story this stronger chromatic treatment; keep it distinct from the neutral benefit grid.

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

### Illuminated benefit grid

**Observed:** A 48px section heading precedes a two-column Benefit card grid with 20px gutters. Cards use 40px padding, 32px serif titles and 20px mono paragraphs; a small dark icon and clipped pastel corner glow make each panel recognizable.

**Transfer:** Translate features into concrete outcomes and vary the glow family without altering the typography.

**Text style:** `card-heading` — Untitled Serif 400 · 32px/1.2 · tracking -0.02em

### Ruled questions

**Observed:** The embedded version places full-width Question rows under a 48px section heading with 100px section padding. A dedicated question page narrows the list to about 1073px, uses 40px serif questions and black rules, and replaces the arrow with a 32px circled plus. Answers use mono text, 16px embedded and 20px dedicated.

**Transfer:** Choose the broad light version for a landing-page objection block and the narrower, stronger-lined version for a question-focused page.

**Text style:** `card-heading` — Untitled Serif 400 · 32px/1.2 · tracking -0.02em

### Warm closing invitation and paper footer

**Observed:** Warm invitation panel centers a 48px promise, mono support and paired pills over amber lower-edge light. Its content width is roughly two thirds of the panel and vertical inset is 80px. A 60px interval leads into a paper footer with 40px top and 24px bottom padding, a 200×57px brand mark and social block on the left, four directory columns on the right, local-time microcopy, then a faint rule and legal baseline. The company-story version changes the close to a future-facing invitation with one recruiting action.

**Transfer:** End the narrative with an equally warm, outlined action scene and retain the location-time footer device using a meaningful timezone. Adapt the promise and actions to the new product rather than adding unrelated final proof.

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

### Alternating technical chapters

**Only for:** technical feature pages

**Observed:** Technical chapter cards stack with 20px intervals within a 1296px-wide region. Each combines a 48px heading, 20px mono support and three compact subcolumns with a roughly 516×420px illustration. Text and media alternate sides across chapters; the outer stack uses 128px vertical padding.

**Transfer:** Use repeatable capability chapters when buyers need deeper mechanism-level explanation, not as the default for every marketing section.

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

### Editorial people and principles

**Only for:** company and recruiting pages

**Observed:** A centered 80px title and wide team image introduce the story. A mission statement receives its own outlined, mint-lit 40px-radius panel. Three circular leader portraits and compact captions supply human proof. Long-form principles pair a tall photograph with a ruled right-hand text column; investor marks occupy two large 20px-radius outlined tiles with pastel light.

**Transfer:** Adapt these modules to the organization's actual story and proof. Keep the imagery human and the text-column rhythm editorial rather than reusing the product mosaic.

**Text style:** `heading` — Untitled Serif 400 · 48px/1.2 · tracking -0.02em

### Form with warm photographic counterweight

**Only for:** contact and recruiting forms

**Observed:** A heading and two short mono paragraphs lead the left half, followed by serif-labeled fields in a 24px-gap form. A tall warm photograph fills the right half across a 64px gutter. Recruiting benefits preceding the form use a left introductory statement and a right two-column grid of lightly top-ruled items.

**Transfer:** Use this for a high-intent enquiry or application. Let the image balance the full form height rather than placing a small avatar above it.

**Text style:** `small-heading` — Untitled Serif 400 · 24px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible mechanism → credibility and breadth → practical outcomes or deeper chapters → remaining questions → warm invitation → paper directory.

### Broad marketing landing page

1. **Promise** — Centered editorial statement, compact mono support, paired pills and a lower-edge system drawing.
2. **Social proof** — Subdued trust ribbon.
3. **Mechanism** — Asymmetric illustrated mosaic.
4. **Breadth** — Periwinkle field with a curved stream of named connections.
5. **Practical outcomes** — Two-column outlined benefit cards with colored corner light.
6. **Objection handling** — Full-width lightly ruled questions.
7. **Closing call** — Warm outlined invitation and paper footer.

**Transfer:** Use the centered opening as the default; borrow the modular narrative without fixing the number or order of sections.

### Company story and credibility

1. **Origin** — Centered editorial title, wide team photo and explanatory narrative.
2. **Purpose** — Mint-lit mission statement in an outlined panel.
3. **Human proof** — Three small circular portraits with names and roles.
4. **Principles** — Tall workplace photo paired with long ruled explanations.
5. **Institutional proof** — Two large illuminated supporter tiles.
6. **Closing invitation** — Future-facing warm panel with one team action, then shared footer.

**Transfer:** Use human photography and narrative detail for organizational trust while retaining the type contrast and illuminated panels.

### Recruiting and high-intent contact

1. **Invitation** — Centered 80px serif proposition over a soft coral-blue halo with two mono paragraphs.
2. **Reasons to engage** — Left introduction beside a right-hand two-column grid of top-ruled benefits.
3. **Conversion** — Serif-labeled application form beside a tall warm laptop photograph.
4. **Closing call** — Shared amber invitation followed by paper directory.

**Transfer:** Adapt to any people-led enquiry while keeping benefits, form and photography aligned to that purpose.

### Resolve detailed questions

1. **Orientation** — Short centered 80px serif title.
2. **Objection handling** — Narrow question list with large serif triggers, black rules and circled plus signs.
3. **Closing call** — Shared warm invitation and complete paper footer.

**Transfer:** Keep the opening unusually simple and give the questions most of the narrative space.

### Explain a product in depth

1. **Promise** — Split 48px editorial title and mono support opposite an orbital line sculpture, with a compact trial action.
2. **Ecosystem proof** — Partner marks followed by a customer trust ribbon.
3. **Capability chapters** — Alternating outlined feature cards with mechanism illustrations and three small explanatory columns each.
4. **Closing call** — Warm invitation followed by the full paper footer.

**Transfer:** Use the scoped split opening and repeated chapters when clarity of individual mechanisms matters more than the broad overview.

## Writing

Direct, technically literate and conversational. Concrete operational relief is expressed in plain language, with occasional blunt fragments and understated humor rather than enterprise ceremony.

**Do not copy:** Do not reuse Monad's name, logo, partner marks, team identities, customer list, proprietary diagrams, security claims, free-tier allowances, performance numbers or source testimonials as facts about another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to the reader as you and your; use we for the team and the product name when explaining responsibility. Keep navigation labels impersonal and short.
- **Rhythm:** Headlines are usually short declarative phrases; supporting copy names the mechanism and its practical payoff. Body paragraphs can switch into two- or three-beat fragments, including repeated No statements, then return to a concrete sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a complicated job, then remove its friction. | 5–10 words | “Security Data Pipelines, Made Easy”<br>“A Smarter Way to Manage Security Data” |
| Support | Use active verbs to explain responsibility and the reader's relief. | One or two sentences | “We handle the tough data challenges, so security teams can prioritize what really matters.” |
| Benefit | State a useful outcome, then make it vivid with a practical contrast. | 3–7 word title; a short paragraph | “Onboard in Minutes”<br>“Connect your first data source and see results before your coffee gets cold.” |
| Technical explanation | Lead with the operation, follow with specific consequences. | One compact sentence or short fragments | “Tag it, OCSF it, normalize it. Your data doesn't just move, it evolves.” |
| Action | Short verb-first invitation, displayed in uppercase. | 2–4 words | “Start Trial”<br>“Explore integrations”<br>“Join our team” |
| Question | Ask a real first-person or buyer-oriented question rather than a marketing slogan. | One complete question | “What if [Brand] doesn’t have an integration I need?” |

**Words and phrasing to use:** connect; transform; route; managed; real-time; your way; no headaches; less noise; builders; what matters

**Avoid:** synergistic; paradigm-shifting; world-revolutionizing; unlock limitless potential; best-in-class without explanation

**Rules:**

- Pair a technical noun with a clear user outcome.
- Prefer active verbs and actual product behavior to abstract promises.
- Use blunt fragments sparingly for cadence, not as every paragraph's template.
- Keep numbers inside explanatory copy rather than inventing a separate oversized statistics wall.
- Let the close restate the product's utility and invite action without a sudden change in voice.

## Do's and Don'ts

### Do

- Set the default opening in regular 80px serif with 1.2 line height and -0.02em tracking.
- Keep primary prose monospaced at 20px/1.35 and compact answers at 16px/1.35.
- Use the 1432px outer container with 40px side padding for ordinary content.
- Use 1px outlines and 16px radii for feature cards; reserve 40px radii for broad bands and the close.
- Clip 50–75px-blurred pastel light behind crisp diagrams and dark text.
- Retain the 48px pill silhouette for primary marketing actions.
- Keep 100px vertical padding around major neutral sections and 20px gutters between benefit cards.
- Give the footer a location-time detail, four compact directory columns and a light legal baseline.

### Don't

- Do not make ordinary body copy a generic proportional sans; the technical mono is a central part of the identity.
- Do not replace regular serif headings with bold geometric display type.
- Do not apply the small 38px technical trial action to all marketing buttons.
- Do not make cobalt a full-section fill; its role is a small navigation action.
- Do not add elevated drop shadows to every card; the soft shadow belongs to circular logo medallions.
- Do not turn a pastel halo into a sharp rainbow gradient covering an entire card.
- Do not pull the 13.6px technical subcolumn text into primary body copy.
- Do not replace the paper footer with a black band or omit the amber-lit outlined invitation.

## Motion and responsive

### Motion

**Observed:**

- Text links declare color transitions of 0.2s.
- The compact trial action declares color, background-color and border-color transitions of 0.3s with cubic-bezier(0.165,0.84,0.44,1).
- Some surfaces declare opacity 0.5s with cubic-bezier(0.165,0.84,0.44,1), and some elements declare transform 0.3s.
- The ecosystem names form a curved stream with edge fading.

**Transfer:**

- Keep link feedback subtle and preserve the faint-outline structure during hover.
- If animating the ecosystem stream, keep its labels following the bowed field rather than introducing horizontal card slides.

**Unknown:**

- Exact stream speed and path timing are unknown.
- Scroll-reveal choreography and duplicated button-label animation timing are not established.

### Responsive

**Observed:**

- Declared CSS width breakpoints include 479px, 767px, 768px, 991px, 992px, 1122px, 1440px and 1920px.

**Transfer:**

- On narrow layouts, retain the editorial-serif and mono contrast, stack landscape process content and media, and preserve the halo as a backing rather than a separate block.
- Collapse the tall-left mosaic into a readable single-column sequence; keep its diagrams substantial instead of shrinking them into icons.
- Stack the form and photograph and reduce the directory to fewer columns while preserving the time detail.

**Unknown:**

- Exact mobile typography, navigation behavior and breakpoint-specific spacing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
