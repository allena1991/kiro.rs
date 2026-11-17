# folk — ruled stages, human tools

## Overview

An airy, light software-marketing style with near-black grotesk headlines, white space and dusty pastel demonstration stages. Fine rules and square frames give it the feel of a practical product catalogue, while grain, small portraits and diagrammatic artwork keep it human. It suits collaborative tools with tangible workflows: the surrounding page is sparse, but the interface scenes are richly detailed.

### Essentials

- Big promises feel typeset, not decorated: Uxumgrotesque at 72px/1, weight 500 and -0.025em tracking; supporting copy is Inter 20px/24.5px with -0.017em tracking.
- The opening is a white proscenium above a working product: a 64px navigation bar, centered headline and support, a compact 480px-wide conversion strip, then an edge-to-edge gray demonstration stage beginning within the first 900px.
- Conversion has two deliberately different silhouettes: the main signup strip is a square 50px-high frame with adjoining fields and dark submit; navigation uses 32px-high, 20px-radius controls. Standalone download and pricing actions use pills only in their own contexts.
- Color belongs behind the work, not on the words: white surrounds near-black text, while dusty blue-gray, sand, lavender, mauve and olive fill 558px-high media bands. In a capability viewport, a stage occupies roughly two thirds of the visible area; text remains on white.
- Chapters are indexed with tiny attached labels: 14px Inter labels in 26px-high square outlined tabs meet a 1px horizontal rule, followed by a 36px heading on the left and 20px explanation on the right.
- Make the machinery visible through restrained graphic devices: include a grain-backed interface or workflow scene and a monochrome line diagram made of dots, rings or a continuous path. When no interface exists, construct a few credible task panels and their connecting lines rather than substituting generic stock art.
- Close with a spacious, ruled reprise: a centered two-line 64px/1 promise and the same conversion strip, then a five-column footer separated by 1px rules. The ending remains white rather than becoming a dark promotional banner.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dusty blue-gray | `#c3d3d6` | `--color-blue-gray` | surface, accent | Capability media stage and related card hover. |
| Dusty sand | `#cfc4a6` | `--color-sand` | surface | Workflow and enrichment media stage. |
| Dusty lavender | `#d2cee0` | `--color-lavender` | surface | Conversation and context media stage. |
| Dusty mauve | `#d8c0d0` | `--color-mauve` | surface | Relationship-detail demonstration stage. |
| Muted olive | `#c9c9a8` | `--color-olive` | surface | Pipeline demonstration stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, interface panels and reversed action text. |
| Pale field wash | `#f8f8f7` | `--color-field` | surface | Visible result of rgba(18, 18, 0, 0.03) over white in signup fields. |
| Warm paper | `#f4f2f0` | `--color-warm-panel` | surface | Grain-backed conceptual media panels. |
| Light control edge | `#d4d4d4` | `--color-edge` | border | Faint outlined navigation action and comparison-table dividers. |
| Graphite stage | `#a8a8a8` | `--color-hero-gray` | background | Full-width opening product stage, softened with fine grain. |
| Warm secondary gray | `#62625e` | `--color-secondary` | text | Secondary descriptions and feature lists; rgba(5, 5, 0, 0.63) over white. |
| Dark rule | `#21201c` | `--color-rule-dark` | border, text | Section rules, card frames and form perimeter. |
| Warm near-black | `#1f1e1c` | `--color-ink` | text, action, border | Default text and submit fill; rgba(3, 2, 0, 0.89) appears this color over white. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| extension product demonstrations | Pale sage | `#d5dac6` | `--color-sage` | surface | Bulk-import workflow stage. |
| audience-specific landing pages | Powder blue | `#bee0ef` | `--color-sky` | background | Full opening band behind both text and outlined product illustration. |
| download product pages | Download charcoal | `#202020` | `--color-download-dark` | action | Standalone download action fill. |
| compact testimonial grids | Lilac highlighter | `#f6dff6` | `--color-quote-highlight` | accent | A short phrase highlighted inline, never a whole quote-card background. |

## Typography

- **Uxumgrotesque** — Headlines, capability titles and plan headings. Rounded, compact grotesk with distinctive friendly lowercase and a dense medium-weight silhouette. If unavailable, use **DM Sans**. Use weight 500 with the specified tight tracking; preserve compact line breaks. Font stack: "Uxumgrotesque", "DM Sans", Arial, sans-serif.
- **Inter** — Body copy, testimonials, navigation, labels and links. Neutral UI-oriented sans with a clear small-text rhythm. Font stack: "Inter", Arial, sans-serif.
- **Geist Mono** — Bracketed announcement above the opening headline. Small utilitarian monospaced capitals. Font stack: "Geist Mono", ui-monospace, monospace.
- **Instrumentserif** (only for audience-specific social proof) — Small rating numerals beneath a logo matrix. Slender editorial serif contrast against the grotesk system. If unavailable, use **Instrument Serif**. Font stack: "Instrumentserif", "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Uxumgrotesque | 500 | 72px | 1 | -0.025em | Default opening headline; one line for a short broad promise, two for a longer product proposition. |
| section-heading | Uxumgrotesque | 500 | 64px | 1 | -0.023em | Major section introductions and the closing promise. |
| capability-heading | Uxumgrotesque | 500 | 36px | 1 | -0.021em | Feature chapters and numbered split rows. |
| quote | Inter | 400 | 28px | 1.214 | -0.021em | Wide editorial testimonial rows. |
| body | Inter | 400 | 20px | 1.225 | -0.017em | Opening support and capability explanations. |
| small | Inter | 400 | 14px | 1.225 | -0.017em | Navigation, footer links and attribution metadata. |
| chapter-tab | Inter | 400 | 14px | 1.12 | normal | Attached chapter labels on rules. |
| announcement | Geist Mono | 400 | 13px | 1 | normal, uppercase | Bracketed announcement above the main promise. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience and pricing pages | compact-display | Uxumgrotesque | 500 | 64px | 1 | -0.025em | Short audience promise or pricing-page title. |
| audience and pricing pages | compact-heading | Uxumgrotesque | 500 | 48px | 1 | -0.023em | Alternating capability sections and compact proof headings. |
| audience-specific social proof | rating | Instrumentserif | 400 | 28px | 1 | normal | Rating numerals beside small star and provider labels. |
| pricing pages | plan-title | Uxumgrotesque | 500 | 24px | 1 | normal | Plan names. |
| pricing pages | table-heading | Uxumgrotesque | 500 | 24px | 1.6 | normal | Comparison category headings. |
| audience and pricing FAQs | faq-question | Uxumgrotesque | 500 | 20px | 1.3 | normal | Question rows. |
| pricing pages | price | Uxumgrotesque | 500 | 18px | 1.08 | normal | Price and per-member unit, intentionally modest rather than a giant numeral. |
| audience-specific landing pages | compact-body | Inter | 400 | 16px | 1.5 | -0.017em | Audience-specific support paragraphs. |
| pricing pages | table-body | Inter | 400 | 15px | 1.2 | normal | Feature lists and comparison values. |
| pricing pages | plan-action | Inter | 400 | 15px | 1.6 | normal | Plan action labels. |
| audience and pricing pages | compact-quote | Inter | 400 | 15px | 1.3 | normal | Quotes inside bordered compact proof cards. |
| download product pages | download-action | Inter | 400 | 15px | 1.225 | -0.017em | Standalone download label. |

**Notes:**

- Keep headline weight at 500, not a conventional bold 700. The visual force comes from tight tracking and a line height equal to the font size.
- The main landing-page explanation is 20px; the audience-page variant is 16px. Do not average them into an 18px universal body style.
- Small labels remain regular weight. Serif numerals are a tightly scoped proof accent, not a second headline family.

## Layout

**Density:** Airy marketing structure with compact controls and densely populated product scenes.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Tight attribution and component stacks. | fixed |
| 16px | Headline-to-support gap and tab-to-title gap. | fixed |
| 24px | Page gutters, card padding, grid gaps and rule-to-heading inset. | fixed |
| 32px | Vertical padding in wide quote rows. | fixed |
| 48px | Support-to-conversion gap and split title-row column gap. | fixed |
| 64px | Media-band vertical padding and split-row separation. | fixed |
| 72px | Opening media vertical padding. | max(4rem, 5vw) |
| 96px | Major section padding, media side insets and wide quote column gaps. | fixed |
| 160px | Space after a full capability stage. | fixed |

### Containers and grids

- **wide-container**: max width 1440px · side padding 24px. Default marketing grid; at 1440px viewport its content spans 1392px.
- **hero-support**: max width 750px. Centered supporting copy below a broad headline.
- **feature-title-pair**: 2 columns · gap 48px. Equal-width title and explanation above a full-width media stage.
- **split-row**: 2 columns · gap 24px. Equal text and warm media-panel columns; at desktop each is 684px wide.
- **catalogue-grid**: 5 columns · gap 24px. Tall capability cards and footer columns share this broad rhythm.
- **compact-container** (only for audience and pricing pages): max width 1280px. Centered audience and pricing layouts; content occupies 1152px at the desktop viewport.
- **plan-grid** (only for audience and pricing pages): 3 columns · gap 16px. Equal square-framed plans and compact proof cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | marketing-panels | 0px |
|  | navigation-controls | 20px |
| download product pages | download-action | 100px |
| pricing pages | plan-actions | 9999px (pill) |
| compact testimonial grids | portrait | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-interface | `0px 4px 12px 0px rgba(0, 0, 0, 0.1)` | Raised product overlays only; not ordinary marketing cards. |
| interface-card | `0px 1px 1px 0px rgba(0, 0, 0, 0.06)` | Very light elevation within product demonstrations. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and text-bearing sections.

**CSS:** `background: #ffffff; color: rgba(3, 2, 0, 0.89)`

#### Grained opening stage · level 0

**Use:** Edge-to-edge main product demonstration.

**CSS:** `background-color: #a8a8a8; padding: 72px 0px; overflow: hidden; border-radius: 0px`

**Observed:** Fine monochrome grain overlays the gray ground; a wide white application begins inside the band with generous top clearance.

**Transfer:** Keep the gray matte backing and replace the application with a credible view of the new product.

#### Dusty media band · level 0

**Use:** Full-width capability demonstrations within the page gutters.

**CSS:** `background-color: #c3d3d6; border: 1px solid rgba(65, 113, 129, 0.4); border-radius: 0px; padding: 64px 96px; overflow: hidden`

**Observed:** Default blue-gray alternates with sand, lavender, mauve and olive. Each uses a low-opacity darker edge related to its fill. The stage carries fine grain and contains opaque foreground panels over faded contextual UI.

**Transfer:** Assign a dusty stage color to each capability; keep the text outside on white.

#### Warm diagram panel · level 0

**Use:** Conceptual graphics in split rows.

**CSS:** `background-color: #f4f2f0; border: 1px solid rgba(133, 111, 90, 0.4); padding: 96px; overflow: hidden; border-radius: 0px`

**Observed:** Light repeating paper grain supports delicate rings, pills, workflow blocks and analytical graphics.

**Transfer:** Use thin conceptual diagrams rather than adding another full application view.

#### Floating product panel · level 1

**Use:** Opaque focal UI over a muted context view.

**CSS:** `background: #ffffff; outline: 1px solid rgba(127, 127, 127, 0.24); box-shadow: 0px 4px 12px 0px rgba(0, 0, 0, 0.1); border-radius: 0px`

**Observed:** Panels have square corners; gentle elevation separates them from flat tinted grounds.

**Transfer:** Reserve elevation for the active product object.

#### Powder-blue audience opening · level 0

**Only for:** audience-specific landing pages

**Use:** A compact text-and-product hero sharing one colored background.

**CSS:** `background-color: #bee0ef; border-bottom: 1px solid rgba(3, 2, 0, 0.89)`

**Observed:** Subtle grain, centered text and outlined product art all inhabit the blue field.

**Transfer:** Use this as a scoped audience-page alternative, not the default white opening.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `position: sticky; top: 0px; height: 64px; padding: 0px 24px; background: #ffffff; z-index: 1000`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** Three-part composition: small wordmark at left, centered product/solution/resource links, and login plus demo action at right. Dropdown triggers use small downward carets.

### Navigation action

**Use:** Secondary conversion in the header.

**CSS:** `display: flex; align-items: center; height: 32px; padding: 8px 12px; background: #ffffff; border: 1px solid #d4d4d4; border-radius: 20px`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** An understated outlined control beside the unboxed login link.

**States:** Declared: hover background-color rgba(15, 8, 0, 0.059); focus-visible unknown; active outline 0px.

### Signup strip

**Use:** Primary conversion in the opening and closing call.

**CSS:** `display: flex; align-items: center; width: 480px; height: 50px; border: 1px solid #21201c; border-radius: 0px`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** One continuous frame encloses an email input, team-size selector with caret, and dark submit. Inner widths are 252px, 110px and 116px; controls are 48px high. The selector has a dark left divider; the submit has white text.

**Transfer:** Keep the integrated strip; adapt the qualifier to one meaningful segmentation field.

### Email field

**Use:** First field in the signup strip.

**CSS:** `height: 48px; width: 252px; padding: 0px 10px 0px 16px; background: rgba(18, 18, 0, 0.03); border-radius: 0px`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** Muted placeholder; no separate rounded input enclosure.

### Chapter tab

**Use:** Small sticky feature index attached to a horizontal rule.

**CSS:** `display: flex; align-items: center; height: 26px; padding: 0px 6px; background: #ffffff; border: 1px solid rgba(3, 2, 0, 0.89); border-radius: 0px; margin-bottom: -1px`

**Text style:** `chapter-tab` — Inter 400 · 14px/1.12

**Observed:** A narrow adjoining square holds a dark dot; the label and dot touch the long rule. The bar sits beneath the sticky navigation as feature chapters advance.

### Catalogue card

**Use:** Visual inventory of capabilities or tool consolidation.

**CSS:** `display: flex; flex-direction: column; height: 374px; background: #ffffff; border: 1px solid #21201c; border-radius: 0px`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** Small category, slightly larger title, centered black line-art object, then a rule and a small comparison or supporting strip. Desktop cards are 259px wide.

**States:** Declared: hover background-color #c3d3d6 with fine grain; focus-visible unknown; active outline 0px.

**Transfer:** Use abstract diagrams to distinguish capabilities, not unrelated pictorial illustrations.

### Editorial quote row

**Use:** Default long-form customer proof.

**CSS:** `display: grid; grid-template-columns: 2fr 1fr; column-gap: 96px; row-gap: 16px; align-items: center; padding: 32px 0px; border-top: 1px solid #21201c`

**Text style:** `quote` — Inter 400 · 28px/1.214 · tracking -0.021em

**Observed:** Quote on the broad left; a small square portrait, name and compact role on the right. Rows span the full wide container without enclosing boxes.

### Footer link

**Use:** Grouped resource navigation.

**CSS:** `display: block; padding: 8px 0px; color: rgba(3, 2, 0, 0.89); text-decoration: none`

**Text style:** `small` — Inter 400 · 14px/1.225 · tracking -0.017em

**Observed:** Links stack under muted category labels in four columns beside the brand column.

**States:** Declared: hover underline with text-underline-offset 2px; focus-visible unknown; active outline 0px.

### Download pill

**Only for:** download product pages

**Use:** Direct installation action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; padding: 8px 12px; height: 34px; background: #202020; color: #ffffff; border-radius: 100px`

**Text style:** `download-action` — Inter 400 · 15px/1.225 · tracking -0.017em

**Observed:** Short text with a small northeast arrow; centered under the support line.

**States:** Declared: hover opacity 0.85; focus-visible unknown; active outline 0px.

### Plan card

**Only for:** pricing pages

**Use:** Equal-weight plan comparison.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 16px; padding: 24px; border: 1px solid rgba(3, 2, 0, 0.89); border-radius: 0px`

**Text style:** `plan-title` — Uxumgrotesque 500 · 24px/1

**Observed:** Plan name, modest inline price, muted annual total, thin divider, checkmarked list and bottom-aligned 38px-high pill action. Only the recommended plan has a dark action; the other actions are outlined. A small gray popularity tag sits near the heading.

### Compact quote card

**Only for:** audience and pricing pages

**Use:** Dense proof grid.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 16px; padding: 24px; border: 1px solid rgba(3, 2, 0, 0.89); border-radius: 0px`

**Text style:** `compact-quote` — Inter 400 · 15px/1.3

**Observed:** Inline pastel highlighting emphasizes one short phrase. Grayscale circular portrait and author sit at the bottom. A wider video card completes the lower row.

### FAQ row

**Only for:** audience and pricing FAQs

**Use:** Objection handling with a compact question list.

**CSS:** `border-bottom: 1px solid rgba(3, 2, 0, 0.89); padding: 0px 0px 20px; border-radius: 0px`

**Text style:** `faq-question` — Uxumgrotesque 500 · 20px/1.3

**Observed:** Question at left and small downward chevron at right in roughly 67px-high rows. Expanded answers use muted Inter text below; the closed list remains visually sparse.

## Imagery and graphics

### Working product stages

**Use:** Main visual language for the opening and capability chapters.

**Observed:** White application views fill most of a wide, grainy gray or dusty pastel rectangle. Context tables and browser pages can fade into the backing, while the active email, task or contact panel remains crisp and opaque. Cropped lower edges imply a real working application rather than a floating decorative mockup.

**Transfer:** Create one clear working state with believable data and a focused overlay. Minimum acceptable version: a sidebar, a compact table or board, and one fully legible action panel.

**Build:** Place a square white interface on a matte gray or pastel rectangle. Add a low-opacity SVG feTurbulence monochrome noise layer across the backing, leaving foreground text crisp. Position context UI beneath the active panel and reduce its opacity; use 1px neutral outlines and the Floating product panel surface for the active object.

### Workflow connectors

**Use:** Explain transformations inside capability stages.

**Observed:** Small white input tiles feed an opaque central panel, then branch into a few output tiles. Fine angular hairlines, tiny square endpoints and occasional dark dots connect them; colors come primarily from small service icons.

**Transfer:** Translate any product process into inputs, one meaningful operation and outputs; use text blocks rather than an elaborate illustration if necessary.

**Build:** Use SVG 1px connector paths with horizontal segments and shallow diagonal joins. Place 4px white endpoint squares at inputs and a 4px dark terminal dot. Layer white rectangular cards above the paths on a sand or sage stage; keep the center object larger than its satellites.

### Monochrome diagram objects

**Use:** Signature abstraction in capability catalogue cards.

**Observed:** Black 1px circles, small hollow-dot fields, stacked ellipses and a looping arrow path sit on white without gradients or shadows. Artwork occupies the middle of each tall card with generous breathing room.

**Transfer:** Include an equivalent geometric metaphor for the new product: sorting, stacking, routing or sensing. A simple ring target or dot matrix is sufficient.

**Build:** Draw SVG in a roughly 257px by 188px viewport. Use 1px dark strokes: either concentric circles around a filled center dot, a regular field of 5px hollow circles with a few filled ones, or overlapping ellipses with the lowest ellipse filled dark. Keep the art centered and monochrome.

### Orbit diagram

**Use:** Conceptual architecture illustration in a warm split panel.

**Observed:** A faint central circular emblem is surrounded by small white labeled pills on a dotted circular orbit. The whole scene is nearly monochrome and low contrast against textured warm paper.

**Transfer:** Replace the central emblem with a neutral product symbol and surround it with meaningful entities or capabilities.

**Build:** Center two concentric SVG circles and a simple abstract internal mark. Draw a larger dotted circular path in low-opacity dark ink and distribute 6–8 white pills around it, each with a tiny line icon and label. Back it with Warm diagram panel; keep shadows nearly imperceptible.

### Human proof

**Use:** Attribution and testimonial video imagery.

**Observed:** Small real portraits are square in editorial rows and circular grayscale in compact grids. Video imagery is desaturated, candid and work-oriented, with a simple black circular play control.

**Transfer:** Use genuine portraits at modest scale; keep the product, not lifestyle photography, visually dominant.

### Soft integration relief

**Only for:** audience-specific landing pages

**Use:** Alternating explanatory media blocks.

**Observed:** Warm off-white rectangular images contain white raised discs or chips, softly lit with shallow shadows, arranged around a central disc. Small colored service marks are the only saturation. Other panels use simplified UI fragments, connector paths and pill labels.

**Transfer:** Build restrained white relief from simple circles and rectangular UI fragments; use a warm grain ground and diffuse shadows rather than glossy 3D.

### Browser companion stage

**Only for:** download product pages

**Use:** Show an extension in its host context.

**Observed:** A pale square drafting grid spans the ground behind a large grayscale browser profile; a narrow tinted strip backs the opaque companion panel at right. Small service tabs sit above the browser.

**Transfer:** Show the new tool within its real host environment, muted beneath a crisp companion panel; preserve the grid and asymmetric large-view/small-overlay composition.

**Build:** Layer two 1px light-gray linear gradients at right angles over white, repeating every 40px. Set a broad browser view on the left and an opaque narrower overlay to the right, backed by a dusty blue-gray rectangle.

### Icons

**Observed:** Small practical UI symbols, mostly 16px or 20px, with thin 1px strokes or compact filled silhouettes. Carets stay small; chapter markers are dots. Service logos retain color inside demonstrations, while ordinary marketing diagrams remain monochrome.

**Transfer:** Choose a consistent simple UI icon set. Use small inline icons and connectors rather than oversized feature-icon badges.

## Section recipes

How recurring sections are built.

### First screen: White proscenium opening

**Observed:** A white 64px sticky Navigation sits above a broad centered composition. After 144px of upper breathing room, a 13px bracketed Announcement leads into the 72px Display headline, then the 20px Body support at a 16px gap. The headline can span nearly the full container; support is constrained to 750px. A Signup strip follows 48px below support. After a further 96px, the Grained opening stage begins: edge-to-edge gray backing, white application inset vertically by 72px. Within the first 900px, all opening copy and conversion controls plus the upper portion of the main application are visible. The rest of the 840px-tall stage continues below the fold. Back-to-front layers are white canvas, gray grain stage, application, and focused foreground panel.

**Transfer:** Keep the same hierarchy and broad stage for a new product. Without existing product media, construct a credible workflow board and one active panel. Download pages replace the strip with Download pill and use Browser companion stage; audience pages use Powder-blue audience opening with Compact display and a centered outline-style product scene. Pricing opens with a short centered title above plans.

**Avoid:** Do not squeeze a tiny illustration beside a left-aligned headline or turn this opening into a rounded gradient card. Do not force a long promise onto one line at the expense of the type scale.

**Text style:** `display` — Uxumgrotesque 500 · 72px/1 · tracking -0.025em

### Ruled chapter and demonstration

**Observed:** Chapter tab attaches to a full-width hairline. A 36px Capability heading sits below at left; Body explanation sits in the right half with a 48px column gap. After 24px comes Dusty media band, 1392px by 558px on desktop. A generous 160px lower interval separates capability stages.

**Transfer:** Group capabilities by a short verb, then pair one outcome with one focused demonstration. Repeat the device as needed without making every page equally long.

**Text style:** `capability-heading` — Uxumgrotesque 500 · 36px/1 · tracking -0.021em

### Ruled major statement

**Observed:** A 1px dark rule, 24px top inset and 64px Section heading introduce a broader argument. Major sections use 96px upper and lower padding.

**Transfer:** Use a broad text statement to pivot between demonstration chapters and structural benefits.

**Text style:** `section-heading` — Uxumgrotesque 500 · 64px/1 · tracking -0.023em

### Numbered split explanation

**Observed:** Two equal columns separated by 24px: the left begins at a dark top rule with a tiny bracketed number, 36px heading and 20px support separated by 8px. The right is Warm diagram panel. Rows are separated by 64px.

**Transfer:** Explain less tangible benefits with a conceptual diagram, not another full product view.

**Text style:** `capability-heading` — Uxumgrotesque 500 · 36px/1 · tracking -0.021em

### Catalogue inventory

**Observed:** A 64px heading above five Catalogue cards with 24px gaps. Each white square frame contains a label, title, monochrome diagram and a bottom ruled supporting strip.

**Transfer:** Use this construction for a compact inventory, consolidation argument or capability index. Preserve the line-art middle, not the original categories.

### Editorial proof list

**Observed:** A ruled 64px title introduces Editorial quote rows. Quotes occupy the broad left side; small square portraits and concise attribution occupy the right. The 28px quote text makes proof feel like readable editorial material rather than a wall of badges.

**Transfer:** Choose a few specific customer experiences and preserve the open horizontal construction.

**Text style:** `quote` — Inter 400 · 28px/1.214 · tracking -0.021em

### Logo matrix and ratings

**Observed:** A square-cell ruled logo matrix creates a practical proof table. The wide variant places a trust sentence and three rating lines in a left cell beside a four-column logo grid. The audience variant uses six logo columns and places three small serif rating numerals beneath.

**Transfer:** Use real proof in a monochrome matrix; if customer logos are unavailable, organize verified integrations or independent evaluations with the same tabular restraint.

### Ruled closing and resource footer

**Observed:** A 1px rule starts a roughly 610px-tall white closing call. Centered two-line 64px Section heading and Signup strip are separated by 48px, with about 192px of space above the heading. Another rule introduces five footer columns with 24px gaps and 48px top padding. Brand, small certification seals and a row of five assistant-service icons occupy the first column; four link groups follow. A bottom rule separates social links from legal links and the language control.

**Transfer:** Repeat the broad promise in fewer words, repeat the primary conversion and finish with useful navigation. Include the compact assistance-icon utility row where the product offers equivalent help; otherwise use a similarly restrained support utility row.

**Text style:** `section-heading` — Uxumgrotesque 500 · 64px/1 · tracking -0.023em

### Alternating audience chapters

**Only for:** audience-specific landing pages

**Observed:** A 1152px content area alternates 611px by 451px framed illustrations with text. The grid uses a wider media column, narrower copy column and 80px gap; headlines are 48px and support is 16px. Warm relief artwork alternates left and right.

**Transfer:** Use for a targeted use-case story with shorter copy and more literal explanations.

**Text style:** `compact-heading` — Uxumgrotesque 500 · 48px/1 · tracking -0.023em

### Plans and comparison

**Only for:** pricing pages

**Observed:** A centered 64px title leads into a billing switch and currency control above three Plan cards. Compact 18px pricing shares a line with the billing unit. Below, a long comparison uses a feature-label column and three aligned plan columns, 53–56px rows and 0.5px light dividers. Category headings are 24px; plan names remain visible above the comparison as it scrolls.

**Transfer:** Prioritize legible inclusion differences, not giant prices or a vividly colored recommended-plan slab.

**Text style:** `compact-display` — Uxumgrotesque 500 · 64px/1 · tracking -0.025em

### Compact proof and objections

**Only for:** audience and pricing pages

**Observed:** Compact quote cards form a three-column grid with 16px gaps and occasional inline pastel highlights; the lower row includes a wider grayscale video. FAQ rows are a plain ruled list with chevrons. The audience layout places proof before FAQs; pricing places FAQs before proof.

**Transfer:** Adjust order to the reader’s remaining doubts; retain the small-type boxed proof variant only in these denser page types.

## Page flow

**Storyline:** Promise → visible product work → credibility → capability outcomes → broader structural value → proof or objections → spacious conversion reprise and resources.

### Broad platform marketing

1. **Promise and conversion** — Centered broad headline, integrated signup and large gray application stage.
2. **Social proof** — Ruled logo matrix with trust copy and ratings.
3. **Capability chapters** — Verb tabs, heading pairs and full-width dusty media stages.
4. **Structural value** — Large ruled statement followed by numbered split diagrams.
5. **Consolidation argument** — Five framed line-art capability cards.
6. **Customer proof** — Large editorial quote rows.
7. **Closing call and resources** — White centered reprise, signup strip and ruled five-column footer.

**Transfer:** Use enough product chapters to demonstrate the promise, then shift to conceptual value and proof instead of endlessly repeating screens.

### Targeted audience acquisition

1. **Audience promise** — Powder-blue opening with smaller headline, signup strip and product illustration.
2. **Credibility** — Six-column logos and small serif ratings.
3. **Benefit preview** — Three warm framed overview illustrations.
4. **Capability demonstration** — Alternating illustration and 48px text chapters.
5. **Further exploration** — Three resource tiles for demonstration, comparison and releases.
6. **Proof and objections** — Compact quote grid, video and ruled FAQs.
7. **Closing call and resources** — Shared spacious white conversion ending and footer.

**Transfer:** Keep the story specific to one audience while preserving the shared ending and controlled typography.

### Focused companion-product download

1. **Product promise** — Centered two-line display and download pill above drafting-grid browser context.
2. **Capability demonstration** — Three task-focused pastel stages with tabs and heading pairs.
3. **Customer proof** — Wide editorial quote rows.
4. **Closing call and resources** — Shared platform-level conversion reprise and footer.

**Transfer:** Center the opening on direct installation, demonstrate the tool in context, then connect it back to the broader product value.

### Plan selection and purchasing confidence

1. **Pricing** — Short centered title, billing controls and three outlined plan cards.
2. **Detailed comparison** — Long feature matrix grouped by capability categories.
3. **Objection handling** — Ruled FAQ list.
4. **Customer reassurance** — Compact highlighted quote grid and video.
5. **Closing call and resources** — Shared white promise, integrated form and complete footer.

**Transfer:** Use the denser type and narrower content area for evaluation while keeping the closing experience consistent with marketing.

## Writing

Confident, direct and human, with a slight impatience for unnecessary work. Product capabilities are described through practical outcomes and concrete actions, with occasional conversational wit.

**Do not copy:** Do not reuse folk or folkX names, logos, customer identities, quotations, review scores, customer counts, price points, integration counts, superiority claims or proprietary illustrations. Source examples demonstrate voice and structure only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your team. Name the product plainly; favor the user’s action over corporate we-statements.
- **Rhythm:** Short imperative or outcome-led headings, usually 4–9 words; one-sentence explanations. Occasional paired fragments create emphasis. Technical terms appear when they clarify a real workflow.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Unifying proposition using one, entire or connects, tied to the reader’s work. | 6–10 words | “One platform for your entire sales motion”<br>“folkX connects your CRM to your favorite socials” |
| Capability heading | Action plus a concrete result, sometimes naming the friction removed. | 4–9 words | “Find your next customer”<br>“Migrate without the headache” |
| Supporting line | Explain what changes for the user with a compact sequence of practical verbs. | 10–24 words | “Prospect, enrich, and qualify the contacts worth your time”<br>“Prep, call, record, and review conversations directly in [Brand]” |
| Action | Verb plus immediate next step, not aspirational rhetoric. | 2–4 words | “Start for free”<br>“Download Chrome extension”<br>“Get a demo” |
| Section pivot | Two compact benefit fragments or a candid human objection. | 4–9 words | “Consolidate tools. Cut costs.”<br>“A CRM that doesn’t destroy your soul” |

**Words and phrasing to use:** your team; one platform; in-context; shared; connect; collect; find; without the headache; next actions

**Avoid:** revolutionary; unparalleled; synergize; disruptive ecosystem; unlock infinite potential

**Rules:**

- Name a user task before naming the enabling technology.
- Make support add mechanism or context rather than repeat the heading.
- Keep chapter labels to a short verb or compact verb phrase.
- Use candid wit sparingly; most copy should remain practical.
- Use specific verified proof in customer sections, not anonymous praise invented to fill space.

## Do's and Don'ts

### Do

- Keep the main display at 72px/1 and weight 500 on desktop.
- Use 24px outer gutters and 1px dark rules to organize the wide page.
- Set supporting landing-page copy at 20px/24.5px, not the small navigation size.
- Keep tinted capability stages square with 64px vertical and 96px horizontal insets.
- Preserve the 480px integrated conversion strip in both opening and ending.
- Use 28px quotes in open ruled rows for the default proof treatment.
- Include fine grain in matte media grounds and crisp opaque focal UI above it.
- Keep pricing numerals modest at 18px beside the billing unit.

### Don't

- Do not turn ordinary marketing panels into 16px-radius SaaS cards; their corners are square.
- Do not apply pill styling to the main signup strip just because the header action is rounded.
- Do not use saturated purple or blue as a universal brand fill; the large bands are dusty and task-specific.
- Do not use heavy drop shadows under catalogue cards or testimonial rows; elevation belongs to product overlays.
- Do not spread the serif rating accent into body text or section headings.
- Do not replace the monochrome catalogue diagrams with colorful emoji or generic icon tiles.
- Do not render customer proof as oversized star badges when a ruled matrix or editorial row is appropriate.
- Do not invert the complete footer to black; retain white canvas and thin rules.

## Motion and responsive

### Motion

**Observed:**

- Declared control transitions include background-color 0.15s and background-color 0.15s ease.
- Some surfaces declare background-color, color and box-shadow transitions of 0.4s.
- Orbit graphics declare orbit-turn 180s linear infinite reverse.
- Sticky navigation and sticky chapter-label bars maintain orientation while the page scrolls.

**Transfer:**

- Use the slow orbit only for the conceptual architecture diagram; preserve the legibility of its labels.
- Keep control color feedback subtle and fast; do not animate marketing panels as if they were playful tiles.

**Unknown:**

- Exact reveal choreography, trigger positions and most timing assignments are unknown.

### Responsive

**Observed:**

- Width breakpoints are declared at 479px, 480px, 767px, 768px, 991px, 1440px and 1920px.

**Transfer:**

- Recommended: stack the title/explanation pair and numbered split rows on narrow screens, retaining their rule and tab relationship.
- Recommended: preserve a readable focal panel when reducing a large product scene; crop peripheral application content rather than shrinking every UI label.
- Recommended: allow the three-part conversion form to stack when its 480px strip cannot fit, retaining adjoining square fields and the dark final action.

**Unknown:**

- Mobile layouts, actual navigation collapse behavior and type scaling below desktop are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
