# GitHub — luminous collaborative playground

## Overview

A black, spacious technology stage made approachable by jewel-like purple light and toy-like three-dimensional objects. Humanist grotesk typography and small terminal-like labels balance technical credibility with an inviting, collaborative tone. Expansive product demonstrations alternate with finely ruled information grids; white product and commercial variants retain the same architecture with softer mint and pastel backdrops.

### Essentials

- Big promises feel conversational rather than shouted: the default headline is Mona Sans 64px/1.08, weight 425, -0.035em tracking; chapter headings are 40px/1.2 at 460.
- The opening is a deep-blue theatre, not a dashboard: a centered two-line promise above an email/action cluster, with purple-lit floating objects entering the bottom of the first 900px; the full interface demonstration follows below.
- Actions are practical rectangles inside the spectacle: 6px corners, 16px/24px medium labels and green #08872b primary fills; the email shell has 8px corners and the adjacent dark action has a white 1px outline.
- Color behaves like emitted light: black occupies most of the default page, white and sage-gray carry text, purple and lilac concentrate behind hero objects and interface frames, while green is reserved for actions, tiny cursor blocks and selective proof.
- Interfaces are exhibited as objects: a 1280px stage with 24px rounded glass framing, thin luminous edges and 40–60px blurred violet light; include this lit stage even when the substitute is a carefully composed workflow diagram.
- Editorial grids stay visible but subdued: 1px #21262d rules organize two- and three-column chapters, 48–64px inner spacing protects the copy, and 40px statistics read as short statements rather than giant isolated numerals.
- A friendly object language brackets the story: small glossy symbols introduce chapters and a much larger sculptural grouping leads the closing invitation; use original rounded product-related forms when there is no mascot. Mono 14px uppercase labels with a small green rectangular cursor supply the technical counterpoint.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action green | `#08872b` | `--color-primary` | action, accent | Primary buttons, newsletter subscription and light-theme cursor details. |
| Midnight blue | `#000240` | `--color-hero-blue` | background | Opening atmosphere fading toward black. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint light | `#5fed83` | `--color-cursor` | accent, border | Tiny cursor rectangles, quotation markers and the footer's 2px upper boundary. |
| Violet falloff | `#5049c2` | `--color-glow-mid` | accent | Midtone halo surrounding lilac lights. |
| Periwinkle edge | `#8c93fb` | `--color-glass-edge` | border | Fine outer edge of the opening interface frame. |
| Ice blue | `#a2daff` | `--color-link` | link | Inline exploration links against black. |
| Lilac light | `#e6b7fe` | `--color-glow-light` | accent | Bright center of blurred purple illumination behind product scenes. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-canvas` | background | Default marketing canvas and the negative space surrounding illuminated demonstrations. |
| Shell charcoal | `#0d1117` | `--color-shell` | background, surface | Global shell and dark technical surfaces, distinct from the pure black marketing stage. |
| Forest charcoal | `#0f1511` | `--color-footer` | surface, background | Footer canvas and enterprise proof panels. |
| Forest rule | `#191f1b` | `--color-footer-rule` | border, surface | Footer columns and dark product-template gridlines. |
| Stage rule | `#21262d` | `--color-rule` | border | Hairlines dividing the default black chapters and columns. |
| Control rule | `#353d37` | `--color-control-rule` | border | Accordion row dividers and subdued control edges. |
| Sage gray | `#a4aea6` | `--color-muted` | text | Default supporting text, inactive disclosures and secondary labels on dark. |
| Bright white | `#ffffff` | `--color-white` | text, surface, border | Headlines and action labels on dark; canvas in the light variants. |

### Inside product imagery only

Colors used only inside product imagery and demos: use them to recreate that imagery, not for the page itself.

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface charcoal | `#151a22` | `--color-product-panel` | surface | Dark interior backing of the main product demonstration. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Commercial link blue | `#0969da` | `--color-light-link` | link | Commercial comparison links. |
| dark product proof sections | Signal green | `#23ea57` | `--color-proof-green` | text, accent | A selected phrase or outcome in a dark testimonial. |
| light commercial pages | Commercial ink | `#1f2328` | `--color-ink` | text | Headlines and prices on commercial white pages. |
| light product pages | Light sage ink | `#58635b` | `--color-light-muted` | text | Support copy on the white product variant. |
| pricing pages | Commercial gray | `#59636e` | `--color-commercial-muted` | text | Commercial plan descriptions and comparison labels. |
| light product pages | Light gridline | `#e4ebe6` | `--color-light-rule` | border | Light product section boundaries and vertical rails. |
| light pages | Mint footer | `#f2f5f3` | `--color-light-footer` | background, surface | Light-theme footer. |
| pricing pages | Comparison gray | `#f6f8fa` | `--color-light-table` | surface | Plan feature areas and paid comparison columns. |
| light product pages | Pale mint paper | `#f9fbf9` | `--color-feedback` | surface | Softly differentiated feedback invitation. |

## Typography

- **Mona Sans** — All marketing headings, paragraphs, navigation and actions. Open, rounded humanist grotesk with a high x-height; variable intermediate weights keep large headlines light without becoming fragile. If unavailable, use **Mona Sans**. Use the freely available variable family; preserve weights 425, 440, 460 and 480 rather than rounding all roles to 400 or 600. Font stack: "Mona Sans", "Mona Sans", -apple-system, system-ui, 'Segoe UI', Helvetica, Arial, sans-serif.
- **Mona Sans Mono** — Uppercase chapter markings, footer labels and technical testimonial accents. Even-width, terminal-like letterforms used as editorial contrast, not as the main body face. If unavailable, use **IBM Plex Mono**. Use 400–500 for labels and 400 for display quotations. Font stack: "Mona Sans Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Mona Sans | 425 | 64px | 1.08 | -0.035em | Default centered opening promise, usually wrapping to two balanced lines. |
| heading | Mona Sans | 460 | 40px | 1.2 | normal | Chapter titles, closing invitation and large statement pairs. |
| stat | Mona Sans | 500 | 40px | 1.3 | normal | Outcome statements with the unit and benefit on the same line. |
| chapter-support | Mona Sans | 400 | 22px | 1.4 | 0.011em | Centered supporting lines beneath immersive chapter headings. |
| statement | Mona Sans | 400 | 22px | 1.4 | normal | Larger left-aligned explanatory copy, often with a white opening phrase and muted continuation. |
| subheading | Mona Sans | 480 | 22px | 1.4 | normal | Accordion titles and resource-card titles. |
| body-lg | Mona Sans | 400 | 18px | 1.5 | 0.01em | Opening support, feature descriptions and exploration links. |
| body | Mona Sans | 400 | 16px | 1.5 | 0.015em | Standard product-page paragraphs and compact supporting text. |
| action | Mona Sans | 500 | 16px | 1.5 | 0.01em | Primary and secondary conversion labels. |
| navigation | Mona Sans | 500 | 16px | 1.5 | 0.015em | Global navigation and segmented-control labels. |
| small-action | Mona Sans | 500 | 14px | 1.5 | 0.015em | Footer links, subscription actions and small utility controls. |
| mono-label | Mona Sans Mono | 480 | 14px | 1.5 | normal, uppercase | Newsletter and footer column headings. |
| eyebrow | Mona Sans Mono | 400 | 14px | 1.5 | 0.015em, uppercase | Product and chapter identifiers paired with a green cursor block. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | commercial-display | Mona Sans | 800 | 64px | 68px | -0.03em | Bold commercial opening and audience-support closing statements. |
| focused product pages | product-display | Mona Sans | 440 | 56px | 1.1 | normal | Product-template opening title and major feedback invitation. |
| pricing pages | commercial-price | Mona Sans | 400 | 48px | 64px | -0.01em | Commercial plan numerals; units remain much smaller. |
| dark technical proof sections | terminal-quote | Mona Sans Mono | 425 | 32px | 1.5 | -0.02em | Large testimonial with a signal-green opening phrase. |
| focused product pages | product-heading | Mona Sans | 480 | 28px | 1.35 | normal | Split product-feature titles and plan names. |
| product FAQ sections | faq-question | Mona Sans | 400 | 20px | 1.3 | normal | Question summaries in long objection-handling sections. |
| pricing pages | commercial-card-heading | Mona Sans | 500 | 20px | 1.2 | -0.01em, features "ss01", "ss02" | Add-on and audience-support card titles. |
| pricing pages | commercial-body | Mona Sans | 400 | 16px | 1.5 | normal | Commercial descriptions. |

**Notes:**

- The core display uses tighter tracking and lighter weight than commercial headings. Do not carry the 800-weight commercial treatment into ordinary marketing chapters.
- Keep technical labels small and uppercase; mono is a secondary voice except in the scoped testimonial treatment.
- Large support copy has a 1.4 line height, body copy 1.5. Default chapter titles are white; subdued continuation phrases use sage gray.
- Headline size is fixed here; preserve readable wrapping rather than stretching letterforms to fill the container.

## Layout

**Density:** Airy stages with compact controls: demonstrations and chapter introductions get substantial breathing room, while navigation, action groups and ruled lists stay efficient.

### Spacing

**Spacing system:**

- **major-step** 8px — Primary layout cadence; 12px and 20px are deliberate intermediate values for controls and copy groupings.

| Value | Use |
| --- | --- |
| 8px | Stacked actions and tight card relationships. |
| 12px | Icon/action gaps, label stacks and footer link stacks. |
| 16px | Heading-to-paragraph gaps, action-group separation and compact side padding. |
| 20px | Opening title-to-support spacing and horizontal button padding. |
| 24px | Accordion top padding and standard gutters. |
| 32px | Form separation, light commercial card padding and footer-column top padding. |
| 48px | Split-panel inner side padding and generous grid gaps. |
| 64px | Standard chapter inner padding and product-template hero insets. |
| 80px | Commercial opening top space and roomy product resource-card vertical insets. |
| 96px | Major closing-section padding and statistic-row vertical padding. |

### Containers and grids

- **stage-container**: max width 1280px · side padding 16px. Centered main frame; at a 1440px desktop width its rails sit about 80px from the viewport edges. Full-bleed chapter rules extend beyond it.
- **heading-measure**: max width 924px · side padding 24px. Centered default opening title; opening support is constrained further to 600px.
- **chapter-measure**: max width 652px. Centered chapter descriptions beneath a title measuring about 758px.
- **split-stage**: 2 columns · gap 0px. Equal halves for feature accordion and media, with 48px copy insets; alternative proof grids use a wider seven-column lead beside five columns of supporting proof.
- **ruled-triad**: 3 columns · gap 0px. Edge-to-edge capability, resource or customer-story columns, separated by thin vertical rules.
- **footer-columns**: max width 1280px · 4 columns · gap 24px · side padding 32px. Newsletter above four link columns; legal links, social symbols and locale form a separate lower strip.
- **faq-measure** (only for product FAQ sections): max width 816px. Centered question list; a categorized variant reserves a left navigation column.
- **plan-quartet** (only for product pricing sections): 4 columns · gap 48px. Four product tiers inside a 1248px panel.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 6px |
|  | email-shell | 8px |
|  | product-interior | 12px |
|  | luminous-frame | 24px |
|  | segmented-control | 60px |
| pricing pages | commercial-plan | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | commercial-plan | `0px 56px 112px 0px rgba(37,41,46,0.32)` | Wide, low-opacity grounding shadow beneath tall plan cards. |
| pricing pages | commercial-card | `0px 0px 0px 1px rgba(53,72,91,0.14), 0px 3px 2px 0px rgba(0,0,0,0.04), 0px 7px 5px 0px rgba(0,0,0,0.02), 0px 13px 10px 0px rgba(0,0,0,0.02), 0px 22px 17px 0px rgba(0,0,0,0.02)` | Fine edge with a layered soft shadow for commercial resource cards. |

### Surfaces

#### Black stage · level 0

**Use:** Default long-form marketing canvas.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Most of the page remains black; faint rules define structural rails rather than separate floating cards.

**Transfer:** Let negative space connect chapters and keep atmospheric light local to media.

#### Midnight opening · level 0

**Use:** Opening atmospheric field.

**CSS:** `background: linear-gradient(#000240, #000000 117%); overflow: hidden`

**Observed:** Deep blue at the top falls into a near-black field; purple illumination collects around the floating objects lower in the scene.

**Transfer:** Keep text on the quiet upper area and reserve the brighter energy for the central object.

#### Ruled panel · level 1

**Use:** Feature grids, proof columns and large content frames.

**CSS:** `border-left: 1px solid #21262d; border-right: 1px solid #21262d`

**Observed:** Horizontal boundaries extend to full viewport width while vertical rails align to the 1280px frame.

**Transfer:** Subdivide with single shared rules rather than doubled card borders.

#### Luminous glass · level 2

**Use:** Outer frame for the lead interface demonstration.

**CSS:** `background: rgba(255,255,255,0.15); border-top: 1px solid #8c93fb; border-right: 1px solid #8c93fb; border-left: 1px solid #8c93fb; border-radius: 24px 24px 0px 0px; padding: 20px 20px 0px`

**Observed:** A dark interface sits within a translucent rim. Other chapter stages use white translucent hairlines and blue light near the lower edge.

**Transfer:** Place the halo behind this layer; keep the interface itself crisp, not blurred.

#### Forest footer · level 0

**Use:** Default ending canvas.

**CSS:** `background: #0f1511; border-top: 2px solid #5fed83`

**Observed:** The pale green upper rule strongly marks the transition out of the black story; internal separators are much darker.

**Transfer:** Retain the colored boundary even when the final content before it is restrained.

#### Light product rails · level 0

**Only for:** light product pages

**Use:** White product-template canvas.

**CSS:** `background: #ffffff; color: #000000; border-left: 1px solid #e4ebe6; border-right: 1px solid #e4ebe6`

**Observed:** White paper, sage support text and almost invisible green-gray rails retain the same geometric structure as the dark template.

**Transfer:** Switch the complete theme rather than alternating random white tiles inside the black default.

#### Feedback paper · level 1

**Only for:** light product pages

**Use:** Centered late-page participation invitation.

**CSS:** `background: #f9fbf9; border-left: 1px solid #e4ebe6; border-right: 1px solid #e4ebe6; padding: 64px`

**Observed:** A pale mint panel remains nearly white and contains a centered title, one short paragraph and two actions.

**Transfer:** Use this quieter invitation where participation matters more than another sales claim.

#### Commercial card · level 1

**Only for:** pricing pages

**Use:** Add-on and audience-support cards.

**CSS:** `background: #ffffff; border-radius: 6px; padding: 32px; box-shadow: 0px 0px 0px 1px rgba(53,72,91,0.14), 0px 3px 2px 0px rgba(0,0,0,0.04), 0px 7px 5px 0px rgba(0,0,0,0.02), 0px 13px 10px 0px rgba(0,0,0,0.02), 0px 22px 17px 0px rgba(0,0,0,0.02)`

**Observed:** These are discrete raised cards, unlike the default site's contiguous ruled columns.

**Transfer:** Use the raised style only for commercial choice-making.

## Components

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; background: #08872b; color: #ffffff; border: 1px solid transparent; border-radius: 6px; padding: 6px 20px; min-height: 43px`

**Text style:** `action` — Mona Sans 500 · 16px/1.5 · tracking 0.01em

**Observed:** A compact filled rectangle, also embedded at the right edge of the email shell. Standalone product actions are 43px tall; the closing email action grows to 48px.

**States:** Declared: hover removes text decoration and changes to the primary hover token; focus-visible uses a 4px solid #0377ff outline with 2px offset and no shadow; active uses primary pressed background and border tokens.

### Outline action

**Use:** Secondary action next to the opening and closing email form.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 12px; background: rgba(31,35,40,0.4); color: #ffffff; border: 1px solid #ffffff; border-radius: 6px; padding: 6px 20px; height: 52px; backdrop-filter: blur(20px)`

**Text style:** `action` — Mona Sans 500 · 16px/1.5 · tracking 0.01em

**Observed:** Same visual priority as the email shell in height, but darker and outlined so the green action remains dominant. The final invitation uses a 56px version.

**States:** Declared: hover removes text decoration and uses secondary hover background and border tokens; focus-visible uses a 4px solid #3094ff outline, 2px offset and no shadow; active uses secondary pressed tokens.

### Email action shell

**Use:** Paired email entry and primary action in the opening and closing invitation.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 3px; background: linear-gradient(90deg, rgba(255,255,255,0.95) 0%, rgba(255,255,255,0.57) 300%); border: 1px solid #ffffff; border-radius: 8px; min-height: 52px`

**Text style:** `body` — Mona Sans 400 · 16px/1.5 · tracking 0.015em

**Observed:** Input on the left and Primary button inset on the right share one luminous shell. A separate Outline action sits 16px away. Width is about 426px in the opening and 459px in the close.

**Transfer:** Use one low-friction field; retain an accessible external or visually hidden label rather than relying only on the prompt.

### Global navigation

**Use:** Persistent brand and navigation strip.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 8px; color: #ffffff`

**Text style:** `navigation` — Mona Sans 500 · 16px/1.5 · tracking 0.015em

**Observed:** A 32px brand symbol leads a left-aligned menu with small downward triangles; search, sign-in and sign-up are right aligned as 32px controls. The navigation occupies a 72px strip beneath a 42px announcement ribbon. Product variants add a 61–62px local navigation row.

**States:** Declared: hover turns menu text to #a4aea6; focus-visible uses the brand focus outline with 0px offset and no shadow.

### Exploration link

**Use:** Secondary route from a capability or proof statement.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; column-gap: 4px; padding-bottom: 2.1px; color: #a2daff`

**Text style:** `body-lg` — Mona Sans 400 · 18px/1.5 · tracking 0.01em

**Observed:** A small 16px arrow follows the label. The link sits about 24px below large statements or 16px below feature copy; light product variants use blue rather than ice blue.

**States:** Declared: hover removes text decoration; focus-visible uses the brand outline and 2px offset without shadow.

### Segmented control

**Use:** Switch between capability views or customer categories.

**CSS:** `position: relative; padding: 8px 16px; border: 1px solid transparent; border-radius: 60px; height: 40px; color: #ffffff; background: linear-gradient(rgba(255,255,255,0.12), rgba(153,153,153,0.12))`

**Text style:** `navigation` — Mona Sans 500 · 16px/1.5 · tracking 0.015em

**Observed:** The selected pill sits within an outlined 58px-high black capsule; repeated choices have 4px separation. The product-pricing variant uses a green selected pill within a compact two-way control.

**States:** Declared: focus-visible uses a 2px accent outline with -2px offset and no shadow.

### Feature disclosure

**Use:** Compact selectable feature list beside a changing product scene.

**CSS:** `display: grid; gap: 4px; padding: 24px 0px 20px; border-bottom: 1px solid #353d37`

**Text style:** `subheading` — Mona Sans 480 · 22px/1.4

**Observed:** Rows are about 80px closed. The active title is white, inactive titles sage gray, and a small purple plus sits at the far edge. The open row reveals body copy and an Exploration link; its paired media occupies the other half of the stage.

**Transfer:** Keep one feature open and make its media demonstrate the named benefit rather than rotating decorative pictures.

### Resource column

**Use:** Contiguous three-column capability and learning grids.

**CSS:** `border-left: 1px solid #191f1b; padding: 80px 64px`

**Text style:** `subheading` — Mona Sans 480 · 22px/1.4

**Observed:** Content proceeds from a 44–56px green-backed icon tile to an optional short category badge, title, muted body and a small outlined circular arrow near the lower left. Columns share horizontal boundaries; light variants change edges and tile backing to pale mint.

**Transfer:** Keep titles specific and allocate equal vertical space to each column; do not convert the grid to a pile of individually shadowed cards.

### Footer navigation

**Use:** Shared final site-wide navigation.

**CSS:** `display: flex; flex-direction: column; gap: 16px; padding-top: 32px; border-top: 1px solid #191f1b`

**Text style:** `small-action` — Mona Sans 500 · 14px/1.5 · tracking 0.015em

**Observed:** Four columns under mono uppercase headings; links stack with 12px gaps. Above them sits a newsletter block, with a small green rectangular marker, two-line support copy and compact green subscribe action. Below is a separate legal, social and locale row.

**Transfer:** Use relevant product, ecosystem, help and company groupings; preserve the quieter mono markings at the edges.

### FAQ disclosure

**Only for:** product FAQ sections

**Use:** Long-form objection handling.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 40px; padding: 24px 48px 24px 0px; border-bottom: 1px solid #191f1b`

**Text style:** `faq-question` — Mona Sans 400 · 20px/1.3

**Observed:** A small green triangle marks expansion. Open content uses body text beneath the question and a green active boundary. The simplest list is 816px wide; the categorized version pairs a left mono navigation with a narrower question column.

### Commercial plan card

**Only for:** pricing pages

**Use:** Commercial tier selection.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ffffff; border-radius: 12px; box-shadow: 0px 56px 112px 0px rgba(37,41,46,0.32)`

**Text style:** `commercial-body` — Mona Sans 400 · 16px/1.5

**Observed:** Three tall cards: centered plan heading and short description, 48px price with smaller units, action row, then a light-gray feature list. The recommended tier has a saturated blue surrounding frame and uppercase ribbon. The free tier has an outlined action, paid tiers dark subtly graded actions.

**Transfer:** Keep the recommendation a single clear frame; let the comparison matrix below handle exhaustive detail.

## Imagery and graphics

### Glossy object constellation

**Use:** Signature opening, chapter emblems and sculptural closing invitation.

**Observed:** Rounded toy-like figures float in violet and pink light, with a warm yellow companion accent. Smooth reflective surfaces, oversized soft features and bright rim highlights make them friendly rather than industrial. Small emblems hover above chapter titles; the closing group expands to dominate the upper half of the invitation.

**Transfer:** Create original, rounded product-related objects or abstract friendly tools. Minimum version: three carefully shaded rounded forms with a translucent face or inset detail, each at a different depth, lit violet and lilac with one warm accent.

**Build:** Use an SVG or 3D composition of three overlapping rounded volumes. Add elliptical dark undersides, broad violet-to-lilac gradient fills and narrow white highlight shapes at the upper-left edge. Place small separated forms over a centered blurred violet ellipse in the opening; enlarge and overlap them into a horizontal shoulder-to-shoulder group for the close.

### Violet light and particles

**Use:** Required atmospheric device behind primary objects and demonstrated workflows.

**Observed:** A broad lilac center falls through violet to black; sparse tiny star points and crosses float between text and the stage. Thin blue light settles near the bottom of some media panels. The light is localized, leaving the surrounding copy field predominantly black.

**Transfer:** Match the soft emitted glow; exact stops are less important than keeping the halo brightest immediately behind the object and dark at text edges.

**Build:** Layer a 1086px circular radial-gradient at the lower-left origin with #e6b7fe at 10%, #5049c2 at 20%, fading to rgba(87,78,255,0) at 60%; blur 40px and rotate -45deg behind the media. Add a second blurred ellipse behind the frame for concentrated violet light. Scatter an SVG field of 1–3px white points and a few four-point crosses at low opacity across a roughly 512px by 622px central area.

### Framed product demonstrations

**Use:** Large opening demonstration and repeated capability stages.

**Observed:** Real editor, task and discussion interfaces are displayed as crisp dark or pale windows within Luminous glass. Some fill almost the full 1280px stage; smaller panels float in a half-width compartment. Interfaces are deliberately cropped at the lower or right edge to increase apparent scale.

**Transfer:** Show a real workflow state, simplify irrelevant chrome and keep the key action legible. Without finished product media, compose a credible window containing a short input-to-result workflow; retain the glass rim, glow and purposeful edge crop.

### Pastel dithered media backing

**Only for:** focused product pages

**Use:** Product-template hero and split feature demonstrations.

**Observed:** Cool cyan, mint, lilac and pale peach fields sit behind crisp software windows. A small square halftone pattern intensifies near corners and lower edges. The backing is a rectangular image compartment, not an all-page rainbow wash.

**Transfer:** Frame a relevant workflow window on a bright, very low-contrast gradient, with a deliberate crop at an edge.

**Build:** In a rectangular panel, blend radial pastel cyan, mint and lilac fields over white. Overlay a repeated 2px square pattern with a 6px pitch, masked to fade toward the center; keep its opacity low. Inset the interface 48–64px and give it a pale 1px rim with rounded corners.

### Customer proof photography

**Only for:** customer proof sections

**Use:** Human context beside a measured result or quotation.

**Observed:** Ordinary offices and real team meetings in natural warm light; rectangular, largely unfiltered photos balance dark green or charcoal panels. They occupy roughly half a proof block rather than becoming full-bleed lifestyle heroes.

**Transfer:** Use authentic working environments, restrained color and no glow effects on the people.

### Green modular skyline

**Only for:** focused product page transitions

**Use:** Decorative seam before late-page resources or questions.

**Observed:** A low strip of translucent green and mint cubes, some with pixel-patterned faces, rises from the lower edge. It acts as a playful transition rather than a full illustration section.

**Transfer:** Use a compact architectural arrangement related to the new product's modularity, preserving the low horizon and translucent light.

**Build:** Draw isometric cubes using three SVG parallelograms per cube, with pale mint top faces, saturated green side faces and white-to-transparent highlights. Vary heights, cluster toward the side edges and clip the bases to a horizontal strip; add sparse square motifs to selected faces.

### Icons

**Observed:** Mostly compact filled SVG symbols at 16px, with mixed line-and-fill arrows using 1.5px round strokes. Section icons are 20–22px inside rounded green-backed tiles; the brand symbol is 32px. Ice-blue arrows follow inline links; tiny green rectangular blocks punctuate mono labels.

**Transfer:** Choose a coherent compact icon family with simple silhouettes and open counters. Use tile-backed symbols for concepts, tiny arrows for routes and the green rectangular marker for editorial labels; do not use emoji as a substitute for the interface icon system.

## Section recipes

How recurring sections are built.

### First screen: Midnight constellation opening

**Observed:** A 42px pale announcement ribbon and 72px dark navigation top a deep-blue field. Center a light, tightly tracked 64px two-line promise within a 924px measure, occupying about two-thirds of the page width, with a white 18px support line in a 600px measure below. After 32px, place Email action shell and Outline action in a centered group with 16px separation. Behind and beneath the copy, purple light rises around small floating glossy objects and sparse stars. Within the first 900px the full headline, support, actions and the upper floating object scene are visible; the full-width software window begins below the fold, around the next stage. Layers run midnight field → diffuse violet light → particles and glossy forms → crisp white copy and controls.

**Transfer:** Use the same hierarchy for a different promise, with original three-dimensional product metaphors or shaded abstract forms when no mascot exists. Focused product pages instead open with a 56px title and mono eyebrow in a ruled panel: centered for a compact solution pitch, or seven/five split with support and download controls on the right. Commercial pages use the scoped bold white opening and show the tops of plan cards within the first screen.

**Avoid:** Do not move the full dashboard above the title, replace the deep-blue field with a generic rainbow gradient, or enlarge the headline to a heavy billboard that squeezes out the action cluster and object scene.

**Text style:** `display` — Mona Sans 425 · 64px/1.08 · tracking -0.035em

### Illuminated chapter introduction

**Observed:** A small glossy chapter symbol sits above a centered heading and chapter-support copy. The heading is 40px/48px; copy follows by about 12–16px and is constrained to 652px. The intro gives way to a large Luminous glass demonstration framed within the stage-container, with the glow bridging the two.

**Transfer:** Use this device to elevate a major capability, not every small feature; retain at least one illuminated chapter stage in a marketing story.

**Text style:** `heading` — Mona Sans 460 · 40px/1.2

### Split feature theatre

**Observed:** Feature disclosure fills one half of a 1280px stage with 48px side insets; the other half is a product panel backed by blue-violet light. One row is expanded with 18px body and an Exploration link. The focused product variant replaces the disclosure with a 28px heading and 16px paragraph beside Pastel dithered media backing.

**Transfer:** Tie each title to a visibly different workflow state. Keep the changing media and its text on the same horizontal stage.

### Proof lattice and statistic seam

**Observed:** Ruled panel supports a wide explanatory statement beside two stacked proof snippets, or three capability columns over two equal statistic cells. Statistics use stat typography at 40px/52px with smaller muted explanatory text directly underneath; no detached giant percentage is required.

**Transfer:** Let the result and its context form one short phrase; use verified, relevant outcomes and make the hierarchy work even with a modest number.

### Resource triad

**Observed:** A centered 40px heading and brief body introduce Resource column in three contiguous cells. Icon, optional category badge, title, body and circular arrow follow in vertical order; faint vertical rails and full-width horizontal rules hold the section together.

**Transfer:** Adapt to learning, support, integrations or product capabilities without needing thumbnail artwork.

### Sculptural closing invitation

**Observed:** An enlarged horizontal grouping of glossy rounded objects dominates the top of a generous black closing stage. A centered 40px invitation follows beneath it, then an 18px muted paragraph and the repeated Email action shell plus Outline action. The section uses 96px outer padding and the art is given a 1280px-wide theatre.

**Transfer:** End the expressive story with a larger reprise of the opening's object language and an inclusive invitation; a new product can use an oversized grouping of original abstract tools or forms instead of characters.

**Text style:** `heading` — Mona Sans 460 · 40px/1.2

### Newsletter and navigation ending

**Observed:** Forest footer starts with a 2px mint rule. Within a 1280px container inset 32px, a compact brand symbol and newsletter block precede four Footer navigation columns separated by 24px gaps. The newsletter title is uppercase mono with a green block marker, support follows by 12px and Subscribe by 20px. A separate lower strip contains legal links, social symbols and locale. The light variant uses mint paper, dark text and green top boundary.

**Transfer:** Keep this useful, quiet finish after whichever narrative ending is appropriate; preserve the mono labels and clear change of surface.

### Technical quotation

**Only for:** dark technical proof sections

**Observed:** A green-backed quotation tile leads a 744px-wide mono quotation at 32px/48px. A signal-green opening clause joins the white continuation at the same weight; a 312px attribution block aligns toward the lower right beyond a 120px gap and begins with a fine upper rule.

**Transfer:** Use one short testimonial with a distinct useful claim and clear attribution. Reserve this monospace display for technical credibility rather than all customer copy.

**Text style:** `terminal-quote` — Mona Sans Mono 425 · 32px/1.5 · tracking -0.02em

### Plan comparison

**Only for:** pricing pages

**Observed:** A bold 64px commercial heading and short support introduce three tall Commercial plan card choices. A subsequent dark customer-proof band interrupts the white page before a four-column comparison matrix: descriptive labels at left and three tier columns, with paid columns shaded #f6f8fa. Category headings and expandable definitions organize dense 14px details.

**Transfer:** Separate quick plan choice from exhaustive comparison. Keep units, eligibility and usage language explicit.

### Product tier panel

**Only for:** product pricing sections

**Observed:** A centered heading and compact individual/business Segmented control introduce four evenly spaced tiers. Plan names are 28px, price lines remain restrained at 28px rather than monumental, and green actions align across columns. The recommended tier has a small uppercase best-value strip; dark panels use forest charcoal, light versions retain white with pale mint emphasis.

**Transfer:** Use this quieter panel when pricing is one chapter of a longer product story rather than the sole purpose.

### Quiet product endings

**Only for:** focused product pages

**Observed:** Dark product pages resolve with Resource triad and long FAQ disclosure lists, sometimes with mono category navigation and a footnote band before Forest footer. The light product variant uses Feedback paper with a 56px title and download/feedback actions, then Green modular skyline and a resource triad before the light footer.

**Transfer:** Choose the ending that answers the visitor's next practical concern; do not force another large sales hero after a long FAQ.

### Commercial audience close

**Only for:** pricing pages

**Observed:** After the comparison matrix, a tiny friendly globe sits above a centered 64px, weight-800 two-line statement. Three Commercial card panels below present audience-specific assistance with pale icon circles, short descriptions and route links, followed immediately by the mint footer.

**Transfer:** Use this pattern for legitimate audience-specific access or support routes rather than ending a dense comparison with another exhaustive sales table.

## Page flow

**Storyline:** Shared promise → visible workflow → capability chapters interleaved with proof → practical choice or participation → reassurance and useful next routes → newsletter and site navigation.

### Broad platform landing story that makes a complex suite feel approachable

1. **Promise** — Centered light headline, email conversion and floating illuminated forms.
2. **Product demonstration** — Large glowing interface followed by segmented capability controls and a moving customer-logo strip.
3. **Capability chapters** — Repeated illuminated stage introductions, split disclosures and finely ruled proof lattices.
4. **Quantified proof** — Two statement-sized outcomes beneath a three-column product grid; customer stories later use a category switcher and three columns.
5. **Closing call** — Large sculptural reprise, inclusive invitation and repeated email/action pair.
6. **Utility ending** — Small attribution note, then newsletter and four-column forest footer.

**Transfer:** Use broad chapters to organize a multi-capability product; vary demonstration, proof and disclosure density rather than repeating identical cards.

### Focused technical solution story with trust and evaluation support

1. **Promise** — Centered mono eyebrow, 56px title, demo/pricing pair and a small self-serve route.
2. **Product demonstration** — Two framed solution previews, customer logos and a large blue-backed workflow panel.
3. **Social proof** — A large mono testimonial with green lead clause and ruled attribution.
4. **Pricing** — Two dark protection-option columns with aligned actions.
5. **Reassurance** — Three resource columns, a small modular art seam and a centered question accordion.
6. **Utility ending** — Forest footer directly after objections, without another sales hero.

**Transfer:** For complex technical purchases, give both demonstration and self-service routes, then resolve uncertainty through proof, clear options and questions.

### Commercial choice and detailed plan evaluation

1. **Promise** — White centered opening with heavy 64px title and one dark trial action.
2. **Pricing** — Three elevated tier cards, one blue-framed recommendation, then six add-on cards and a calculator route.
3. **Social proof** — Dark photographic customer band with a pastel-gradient quotation.
4. **Comparison** — Long four-column matrix organized into capability categories, with compact repeated plan actions.
5. **Audience support** — Friendly globe, bold closing statement and three assistance cards.
6. **Utility ending** — Pale mint newsletter and navigation footer.

**Transfer:** Keep high-level choice first and detailed comparison later; finish with helpful audience routes rather than pressure.

### Flagship product story connecting workflow, enterprise value and plan selection

1. **Promise** — Split ruled opening: mono identifier and 56px title left, support and download/pricing controls right; large pastel-backed interface below.
2. **Capability chapters** — Logo strip, three benefit columns and stacked split workflow demonstrations.
3. **Social proof** — Forest-green panel with a natural team photograph and a selected green outcome phrase.
4. **Enterprise reassurance** — Three resource-like capability columns with category badges.
5. **Pricing** — Four-tier dark panel and a row of eight platform tiles with a comparison route.
6. **Objection handling** — Resources, categorized FAQ, short footnotes and forest footer.

**Transfer:** Use the split opening to pair a memorable promise with immediate practical details; give enterprise readers governance reassurance before plan choice.

### Download-led product introduction with a complete workflow walkthrough

1. **Promise** — White split opening with mono label, title, platform indicators and split download action.
2. **Product demonstration** — Large light interface video, workflow tabs and an explanatory caption.
3. **Capability chapters** — Disclosure/media split, then a large tutorial thumbnail with an editorial explanation and command-like captions.
4. **Extensibility** — Three light ruled resource columns.
5. **Pricing** — Four tiers with a pale recommended panel and compact individual/business switch.
6. **Participation** — Mint feedback invitation, green modular art seam and related resources.
7. **Utility ending** — Pale newsletter and four-column footer; no FAQ is appended.

**Transfer:** Lead with the download decision and compatibility details; alternate visual demonstration with explanation, then invite practical feedback instead of inventing a universal FAQ ending.

## Writing

Confident about capability, warm about participation and concrete about how work improves. Technical detail is welcome, but the main voice talks about momentum, craft and working together rather than abstract enterprise transformation.

**Do not copy:** Do not reuse GitHub names, logos, mascots, product screenshots, customer identities, quotes, prices, performance figures or market-leadership claims. Replace them with original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Name the product plainly in support copy; use we for helpful explanations or invitations rather than self-congratulation.
- **Rhythm:** Headlines are short, sentence-case promises; support generally takes one or two direct sentences. Capability copy favors verbs and parallel phrases. Dense pricing and FAQ sections are allowed to become literal and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Memorable outcome or shared ambition, not a feature inventory. | 3–10 words | “The future of building happens together”<br>“Command your craft”<br>“From issue to merge, in one app” |
| Chapter heading | A plain-language improvement with an active verb or a paired result. | 4–10 words | “Accelerate your entire workflow”<br>“Work together, achieve more”<br>“Extend agents with your own tools” |
| Supporting line | Explain what happens and why it helps, using concrete workflow nouns. | One or two sentences | “Ship faster with secure, reliable CI/CD.”<br>“Open a session from real work across your issues, pull requests, or prompts.” |
| Primary action | Verb plus destination or commitment; platform specifics are explicit for downloads. | 2–5 words, longer for platform qualifiers | “Request a demo”<br>“Get started”<br>“Start free for 30 days” |
| Secondary route | Explore or read plus a specific subject. | 3–7 words | “Read customer story”<br>“Explore documentation” |
| Closing invitation | Inclusive belonging or participation rather than manufactured urgency. | 3–10 words | “Help us build”<br>“Millions of developers and businesses call [Brand] home” |

**Words and phrasing to use:** build; ship; work together; your workflow; craft; from … to …; built-in; explore; get started; help us

**Avoid:** revolutionary synergy; disrupt everything; unlock limitless potential; hurry; last chance; effortless magic

**Rules:**

- Make the title emotional and the supporting sentence operational.
- Use parallel verbs for related capabilities, not parallel buzzwords.
- Attach a number to a named outcome and provide its qualifying context nearby.
- Use contractions and ordinary language in reassurance and participation copy.
- Keep technical units and platform compatibility explicit in plan and download language.

## Do's and Don'ts

### Do

- Use the 64px/1.08 weight-425 title for the default expressive opening.
- Keep ordinary chapter headings at 40px/48px and let the imagery provide the spectacle.
- Align faint 1px rails to a 1280px centered frame.
- Retain 6px button corners and 8px email-shell corners, even beside 24px media framing.
- Localize purple light behind objects and keep copy fields predominantly black.
- Give split feature copy 48px insets and resource columns 64px side insets.
- Repeat the friendly object language at a larger scale near the closing invitation.
- Use 14px uppercase mono markings and a small green rectangular cursor as the technical signature.

### Don't

- Do not turn every heading into the 800-weight pricing style.
- Do not replace all neutral text with bright white; retain #a4aea6 for support and inactive rows.
- Do not use pill-shaped primary conversion buttons; pills belong to segmented selectors.
- Do not add default card shadows to black feature grids; use shared 1px rules.
- Do not flood entire sections with saturated green; it is an action, marker and proof accent.
- Do not shrink every product window into a thumbnail; let major demonstrations approach the 1280px frame.
- Do not make statistics enormous isolated digits; keep the 40px result phrase and its context together.
- Do not put natural customer photography inside the violet toy-material treatment.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions use background-color 0.2s and border-color 0.2s.
- Declared reveal transitions use opacity and transform over 0.6s with cubic-bezier(0.16,1,0.3,1); some titles also reveal through clip-path.
- Logo strips have a declared linear horizontal marquee and a visible pause control.
- Mono cursor markers have a declared stepped blink lasting three iterations after a 0.25s delay.

**Transfer:**

- Keep product content crisp as stages reveal; use movement to bring the lit object or demonstration into attention, not to animate all paragraphs independently.
- Retain pause controls for moving logo strips and video demonstrations.

**Unknown:**

- Exact scroll choreography, 3D scene timing, resolved marquee duration and hover-token colors are unspecified.

### Responsive

**Observed:**

- Desktop composition uses a 1280px maximum frame, a twelve-column underlying grid and wrapping action groups.
- A 768px commercial breakpoint is declared.

**Transfer:**

- On narrow layouts, preserve the dark field, central glow and headline/action hierarchy; stack the split copy before its corresponding media.
- Keep product windows large enough to communicate one action, intentionally clipping peripheral chrome instead of reducing the whole interface to illegible scale.
- Turn multi-column resource and plan sections into sequential blocks with shared hairline boundaries; retain the mono labels and distinctive end surface.

**Unknown:**

- Exact mobile headline sizes, navigation behavior and all narrow-screen art repositioning are unspecified; these stacking rules are adaptation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
