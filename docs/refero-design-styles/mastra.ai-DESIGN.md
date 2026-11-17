# Mastra — sculpted developer machinery

## Overview

A near-black technical world with soft, molded edges and unusually tactile interface staging. Pale grotesk headlines, muted gray explanations and small monospaced markings give dense product detail a composed, approachable feel. Orange announcement accents, restrained green and icy blue signals, monochrome portraits and grain-lit demonstrations suit developer tools and complex software that needs to feel usable rather than abstract.

### Essentials

- Headlines sound like plain statements, not posters: greed at 54px/1.1, weight 520, 0.3px tracking for the opening; section statements use 40px/1.1 with a bright first clause and a #939393 continuation at the same size.
- The opening sells through a cropped working object: left-aligned promise and 352px-wide support beside a right-hand interface occupying roughly half the screen, with a smaller floating control card overlapping it.
- Sections feel cut out of black material: 1376px-wide outer stages, 24px insets, 1328px inner content, 40px card corners and 2px #1c1c1c outlines. Include a sculpted stage with an attached tab or raised label on every new landing page.
- Actions resemble softly edged hardware keys: 50px-high pills with 57px radii, 22px side padding and a 1.5px gradient rim; pair a pale #cccccc primary key with a dark or transparent secondary.
- Color is a signal within a mostly neutral world: keep the canvas #080808, cards #0f0f0f and most text gray; concentrate orange in the hanging announcement lip and newsletter tab, green in selected words and status, and blue in specialized labels rather than broad colorful bands.
- Product detail is lit, cropped and partially submerged: oversized dark interfaces, faint grain and soft lower fades replace flat screenshot rectangles. Include a grain-lit material field; when no interface is available, use a readable schematic of the product's actual process.
- The finish is a designed object too: a centered 54px closing invitation over a low-left grainy light field leads into an inset 40px-radius footer slab with a small warm newsletter tab and 12.5px uppercase mono operational markings.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Announcement apricot | `#fdac53` | `--color-orange` | accent, text | Warm announcement and newsletter accents. |
| Active green | `#7aff78` | `--color-green` | text, accent | Selected words, operational status and focused controls; not a default button fill. |
| Newsletter amber wash | `#1b130a` | `--color-warm-wash` | surface | Dark visible warm wash made with 10% apricot over the deepest black; use the alpha treatment on the footer. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pale key | `#cccccc` | `--color-action` | surface, action, text | Primary action fill and readable card/FAQ copy. |
| Key ink | `#000000` | `--color-black-ink` | text | Text and glyphs on pale actions. |
| Black seams | `#020202` | `--color-gutter` | background | Deepest page seams and exposed space between section slabs. |
| Section black | `#080808` | `--color-canvas` | background | Default marketing canvas. |
| Stage black | `#0a0a0a` | `--color-stage` | background, surface | Product stages and underlying page material. |
| Raised charcoal | `#0f0f0f` | `--color-card` | surface, background | Cards, header and footer. |
| Soft raised fill | `#171717` | `--color-subtle-fill` | surface | Small raised elements, selector beds and faint lighting. |
| Panel edge | `#1c1c1c` | `--color-edge` | border, surface | Default panel outline and filled secondary actions. |
| Fine inner edge | `#242424` | `--color-fine-edge` | border | Thin internal media outlines and resource FAQ separators. |
| Working gray | `#939393` | `--color-muted` | text, link | Supporting text, inactive tabs and footer links. |
| Reading gray | `#d9d9d9` | `--color-body` | text | Longer explanatory text and inherited body color. |
| Soft white | `#f0f0f0` | `--color-text` | text | Headlines and emphasized labels. |
| Edge light | `#ffffff` | `--color-white` | text, accent | FAQ questions, icon strokes and translucent rim lighting. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise and resource sections | Enterprise ice | `#6ccdfb` | `--color-blue` | text, accent | Enterprise labels and resource edition markers. |
| pricing sections | Growth depth | `#0d2b0c` | `--color-plan-green` | surface | Bottom of the growth-plan gradient. |
| pricing sections | Enterprise depth | `#0e1e26` | `--color-plan-blue` | surface | Bottom of enterprise-plan gradient. |
| resource conversion forms | Input charcoal | `#262626` | `--color-input` | surface | Resource signup input. |
| resource conversion forms | Input edge | `#424242` | `--color-input-edge` | border | Visible outline on resource signup fields. |

## Typography

- **greed** — Marketing headlines, paragraphs, navigation and actions. Rounded contemporary grotesk with broad, open lowercase forms; medium rather than bold display weight. OpenType features: "ss01", "ss02", "ss06". If unavailable, use **DM Sans**. Use variable weights 400–520 and preserve the slightly positive tracking. Font stack: "greed", "DM Sans", ui-sans-serif, system-ui, sans-serif.
- **commitMono** — Feature selectors, status markings, technical labels and code. Even-width utilitarian monospace, used as an equipment-label counterpoint to the soft sans. If unavailable, use **Commit Mono**. Font stack: "commitMono", "Commit Mono", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | greed | 520 | 54px | 1.1 | 0.0047em | fixed | Default landing headline and closing invitation. |
| section-statement | greed | 520 | 40px | 1.1 | 0.0064em | fixed | Centered, two-tone section statement; also the compact pricing opening. |
| lead | greed | 400 | 22px | 1.36 | 0.0116em | fixed | Opening support and product chapter descriptions. |
| question | greed | 400 | 22px | 1.36 | 0.015em | fixed | FAQ questions; retain regular rather than heading weight. |
| body | greed | 400 | 17px | 1.36 | 0.015em | fixed | Reading copy, customer stories and expanded answers. |
| label | greed | 450 | 17px | 1.4 | 0.015em | fixed | Feature card heading/support pairs and story links; color creates hierarchy instead of size. |
| action | greed | 470 | 17px | 1 | 0.025em | fixed | Main 50px actions. |
| tab | commitMono | 520 | 17px | 1 | 0.014em, uppercase | fixed | Technical feature selectors above demonstration stages. |
| footer-link | greed | 400 | 15.2px | 1.067 | 0.017em | fixed | Compact footer links within 34px-tall rows. |
| footer-heading | greed | 500 | 15.2px | 1.5 | 0.017em | fixed | Footer group headings; hierarchy is color and weight, not larger size. |
| navigation | greed | 500 | 15px | 1 | 0.017em | fixed | Desktop navigation labels. |
| newsletter-label | greed | 450 | 14.5px | 1.36 | 0.025em | fixed | Warm label attached to the newsletter field. |
| status | commitMono | 400 | 12.5px | 0.96 | 0.02em, uppercase | fixed | Security and live operational markings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| flagship product and expanded conversion sections | monumental | greed | 520 | 68px | 1.1 | 0.0037em | fixed | Centered flagship product promise or short expanded closing invitation. |
| resource landing pages | resource-display | greed | 500 | 68px | 1.1 | 0.0037em | size clamp(36px,calc(36px + 32*(100vw - 390px)/890),68px) | Multiline resource title beside a physical object. |
| long product pages | chapter-heading | greed | 500 | 54px | 1.1 | 0.0047em | size clamp(30px,calc(30px + 24*(100vw - 390px)/890),54px) | Single-word centered capability chapter title. |
| resource and customer directory sections | resource-heading | greed | 520 | 32px | 1.1 | 0.008em | fixed | Resource card titles, content guide and directory heading. |
| pricing sections | price | greed | 520 | 32px | 0.723 | 0.015em | fixed | Price or short custom-price phrase inside a taller aligned price row. |
| resource proof cards | physical-proof-stat | commitMono | 520 | 32px | 1.1 | 0.008em | fixed | Numeral embedded in a photo-backed proof card label, not an oversized dashboard KPI. |
| pricing sections | plan-heading | greed | 520 | 24px | 1.1 | 0.015em | fixed | Plan names and comparison category headings. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Positive tracking remains nearly constant at 0.3px across most sans sizes; do not impose the tight negative tracking typical of dark software sites.
- Display line height is 1.1; reading text is 1.36 and card labels are 1.4. A heading and its muted continuation can be one flowing sentence at the same 40px scale.
- Mono is a structural marking, not the primary marketing voice. Small internal demonstration text belongs to the product interface, not the marketing type scale.

## Layout

**Density:** Airy between chapters, compact inside working objects. Large dark pauses separate shallow heading blocks from dense, carefully inset demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Chapter heading to support line and action icon gap. |
| 20px | Gap between hero actions and padding of FAQ summary rows. |
| 24px | Default card grid gap, stage inset, section seams and hero heading-to-support separation. |
| 28px | FAQ panel inset and alternate selector gap. |
| 38px | Default marketing card inset and horizontal content padding. |
| 64px | Expanded closing headline-to-action spacing. |
| 96px | FAQ heading lead-in and closing content bottom padding. |
| 112px | Footer grid top and bottom padding. |
| 135px | Clearance reserved beneath the hanging announcement lip. |
| 180px | Top and bottom space around product chapter headers. |

### Containers and grids

- **content**: max width 1328px · side padding 38px. Centered content area; at desktop the text begins inside the outer stage rather than flush with its edge.
- **stage-shell**: max width 1376px · side padding 24px. Black sculpted shell around product media or card groups.
- **statement**: max width 1000px · side padding 24px. Centered section statements with balanced line wrapping.
- **feature-grid**: 3 columns · gap 24px. Equal feature cards; customer proof can make one portrait card span two rows.
- **footer-grid**: 5 columns · gap 36px. A wider brand/newsletter/status rail plus four link columns; lower link groups wrap onto a second row.
- **workflow-grid** (only for long product capability sections): 2 columns · gap 24px. Wider process illustrations with smaller top-left copy.
- **resource-column** (only for resource landing pages): max width 1120px · gap 24px · side padding 24px. Narrower editorial composition; square proof cards in two columns and a full-width video card.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action | 57px |
|  | panel | 40px |
|  | faq-summary | 20px |
|  | floating-control | 26px |
|  | newsletter-tab | 18px |
| resource previews | book-cover | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | header | `0px 4px 60px 0px rgba(0,0,0,0.75)` | Separates the sticky header from media moving underneath. |
|  | glass-inner-edge | `inset 0px 1px 0px rgba(255,255,255,0.03)` | Barely visible inner light on the FAQ panel. |
| resource previews | book-object | `0px 16px 36px 0px rgba(0,0,0,0.46)` | Physical cover preview lifted from its card. |

### Surfaces

#### Seamed canvas · level 0

**Use:** Underlying page and dark gutters.

**CSS:** `background: #020202`

**Observed:** Black seams separate almost-black section planes rather than using white space.

**Transfer:** Let the gaps read as recessed channels.

#### Section plane · level 0

**Use:** Main page sections.

**CSS:** `background: #080808`

#### Sculpted panel · level 1

**Use:** Shared card, product and footer material.

**CSS:** `background: #0f0f0f; border: 2px solid #1c1c1c; border-radius: 40px; overflow: hidden`

**Observed:** Panels sit inside a deeper black shell; curved shoulders and attached top labels make the shell look molded rather than merely rounded.

**Transfer:** Use an SVG shell or overlapping rounded shapes with concave joins; keep the interior and seam colors distinct.

#### Hero working plane · level 1

**Use:** Right-side opening demonstration.

**CSS:** `background: radial-gradient(86.18% 69.41% at 2.35% 1.44%, #171717 26.99%, #080808 87.68%); border-top-left-radius: 40px; padding: 38px`

**Observed:** A lit upper-left corner drops into near-black at the right and bottom; only top and left edges need to remain visible.

**Transfer:** Clip a large working view into the plane, then float a smaller menu across its left boundary.

#### FAQ glass · level 1

**Use:** Default FAQ container.

**CSS:** `background: rgba(15,15,15,0.78); border: 2px solid #1c1c1c; border-radius: 40px; padding: 28px; backdrop-filter: blur(2px); box-shadow: inset 0px 1px 0px rgba(255,255,255,0.03)`

**Observed:** Dark translucency is subtle, not milky frosted glass.

#### Growth plan · level 1

**Only for:** pricing sections

**Use:** Highlighted middle plan.

**CSS:** `background: linear-gradient(#0f0f0f 29%, #0d2b0c 100%); border: 2px solid #1c1c1c; border-radius: 40px`

**Observed:** The color accumulates toward the bottom, leaving the heading region charcoal.

**Transfer:** Keep tint tied to the plan label, not a glowing outline.

#### Enterprise plan · level 1

**Only for:** pricing sections

**Use:** Enterprise offer.

**CSS:** `background: linear-gradient(#0f0f0f 28%, #0e1e26 100%); border: 2px solid #1c1c1c; border-radius: 40px`

#### Resource field · level 2

**Only for:** resource conversion forms

**Use:** Wide email field beside the resource action.

**CSS:** `background: #262626; border: 1px solid #424242; border-radius: 58px; padding: 6px 6px 6px 28px; height: 48px`

**Observed:** A horizontal pill rather than a rectangular form module.

## Components

### Navigation

**Use:** Persistent desktop navigation.

**CSS:** `background: #0f0f0f; border-bottom: 2px solid #1c1c1c; height: 64px; position: sticky; top: 0px; z-index: 500; box-shadow: 0px 4px 60px 0px rgba(0,0,0,0.75)`

**Text style:** `navigation` — greed 500 · 15px/1 · tracking 0.017em

**Observed:** Brand at left, small dotted menu labels and plain destination links across the middle; repository proof and compact account/demo actions sit on the right. Navigation links have 17px side padding and 38px height.

**States:** Declared: hover menu labels turn white on #1c1c1c.

### Announcement lip

**Use:** A timely secondary message attached beneath navigation.

**CSS:** `color: #000000; height: 52px; position: relative`

**Observed:** Warm apricot hanging strip, offset toward the left rather than spanning the screen. Its upper shoulders flare outward into the header and its lower corners curl into a broad pill-like edge. Text is a single date/message line with a small arrow.

**Transfer:** Rebuild the silhouette as an SVG path: a straight top, concave shoulder joins, rounded bottom corners and a shallow warm vertical highlight. Use a real short release or invitation, not a second hero.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 50px; padding: 0px 22px; border: 1.5px solid transparent; border-radius: 57px; background: linear-gradient(#cccccc, #cccccc) padding-box, linear-gradient(#ffffff, rgba(255,255,255,0)) border-box; color: #000000`

**Text style:** `action` — greed 470 · 17px/1 · tracking 0.025em

**Observed:** Compact pale pill with a faint bright top rim. In closing sections, the label is followed by a short row of solid integration glyphs; pricing uses a smaller 44px-high variant.

**States:** Declared: hover is unspecified; focus-visible declares 2px #7aff78 with 2px offset but outline-style is none on some controls; active transform scale(0.98).

### Secondary button

**Use:** Quickstart or a lower-priority route beside the main action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 50px; padding: 0px 22px; border: 1.5px solid transparent; border-radius: 57px; background: linear-gradient(#1c1c1c, #1c1c1c) padding-box, linear-gradient(rgba(255,255,255,0.1), rgba(255,255,255,0)) border-box; color: #cccccc`

**Text style:** `action` — greed 470 · 17px/1 · tracking 0.025em

**Observed:** Filled charcoal in the opening; transparent gray text in closing sections. Header versions shrink to 38px and smaller action text.

**States:** Declared: hover color #f0f0f0; focus-visible declares green outline with 2px offset but outline-style none; active scale(0.98).

### Feature selector

**Use:** Choose a product demonstration inside a sculpted stage.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 10px; height: 80px; border: 2px solid transparent; border-radius: 40px; padding: 0px 20px`

**Text style:** `tab` — commitMono 520 · 17px/1 · tracking 0.014em · uppercase

**Observed:** Five or six mono uppercase pills share the stage width. The active selector is visually joined to the panel beneath by a concave shoulder; inactive selectors remain detached dark pills. A small category icon precedes each label.

**Transfer:** Use a short set of actual capabilities and switch both demonstration and bottom caption together.

### Feature card

**Use:** Explain one practical capability with a working illustration.

**CSS:** `position: relative; background: #0f0f0f; border: 2px solid #1c1c1c; border-radius: 40px; padding: 38px; height: 520px; overflow: hidden`

**Text style:** `label` — greed 450 · 17px/1.4 · tracking 0.015em

**Observed:** Small heading and gray support occupy the top-left; the illustration fills the lower two thirds and is often clipped by the card. Three cards share a row. Product-page variants use shorter 402px cards or wide two-column process cards.

**Transfer:** Show a real interaction, process fragment or useful output rather than a generic decorative icon.

### Story card

**Use:** Customer proof through a concrete outcome.

**CSS:** `display: flex; flex-direction: column; position: relative; background: #0f0f0f; border: 2px solid #1c1c1c; border-radius: 40px; padding: 38px 38px 30px; overflow: hidden`

**Text style:** `body` — greed 400 · 17px/1.36 · tracking 0.015em

**Observed:** Full-bleed monochrome portrait or luminous abstract mark behind a narrow top-left outcome title; white organization mark and Read story sit near the bottom. The default proof mosaic pairs one tall portrait with four smaller cards.

**Transfer:** Preserve a 200px title measure and clear dark regions behind copy. If portraits are unavailable, use a monochrome light sculpture of a simple relevant shape.

### FAQ row

**Use:** Objection handling in a shared glass panel.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 20px; padding: 20px; border-radius: 20px`

**Text style:** `question` — greed 400 · 22px/1.36 · tracking 0.015em

**Observed:** Whole-row disclosure with a small right chevron. Open answers appear below in body text; default summaries are about 70px tall. Resource and long-product variants use full-width rows separated by 2px #242424 top rules rather than individually rounded hover areas.

**States:** Declared: hover on repeated default rows uses #171717; focus-visible declares 2px green outline with 2px offset, outline-style none.

### Newsletter tab

**Use:** Small attached signup device in the footer rail.

**CSS:** `background: rgba(253,172,83,0.1); color: #fdac53; padding: 10px 20px; border-radius: 18px 18px 0px 0px`

**Text style:** `newsletter-label` — greed 450 · 14.5px/1.36 · tracking 0.025em

**Observed:** Warm label rises from the top-left of a 340px-wide, 46px-high dark email pill. A warm rounded corner patch extends behind the left end of the input, making the pieces feel fused rather than stacked.

**Transfer:** Use a short cadence-based invitation and a single email field; keep it subordinate to the footer links.

### Footer links

**Use:** Dense destination groups inside the final slab.

**CSS:** `display: flex; align-items: center; min-height: 34px; color: #939393`

**Text style:** `footer-link` — greed 400 · 15.2px/1.067 · tracking 0.017em

**Observed:** Plain links beneath small bright group headings, no bullets, dividers or boxed link tiles.

**States:** Declared: hover color #f0f0f0; focus-visible color #f0f0f0 and outline-style none.

### Plan card

**Only for:** pricing sections

**Use:** Aligned self-service and enterprise offer comparison.

**CSS:** `display: flex; flex-direction: column; background: #0f0f0f; border: 2px solid #1c1c1c; border-radius: 40px; min-height: 540px; overflow: hidden`

**Text style:** `plan-heading` — greed 520 · 24px/1.1 · tracking 0.015em

**Observed:** Plan title, muted audience, price, ruled allowances, then bottom-aligned full-width action. The default free offer is neutral with a dark action; growth has green label and Growth plan material; enterprise has blue label and Enterprise plan material with pale actions. A narrow external rail supplies feature names beside the three cards.

**Transfer:** Align price and allowance rows across plans even when the enterprise offer uses prose.

## Imagery and graphics

### Layered working interfaces

**Use:** Opening object and large feature demonstrations.

**Observed:** Black-on-black interfaces show tables, trace rows, code and conversations. They are enlarged, overlapped and clipped, with fine edges and localized status color; the page does not present an entire browser window on a bright plate.

**Transfer:** Use a few legible interactions from the new product. Minimum acceptable version: one substantial dark table or editor with a floating menu and an accurate sample output. Let detail fade away at the lower edge.

**Build:** Place a dark rounded working plane over the stage, overlap a smaller 26px-radius menu across its left edge, then mask the bottom with a transparent-to-#0a0a0a gradient. Add a low-opacity white radial field behind the interface, never behind all text.

### Grain-lit stage

**Use:** Signature material behind demonstrations and the closing invitation.

**Observed:** A smoky, speckled gray light rises from the lower-left and disappears into black. It is a tactile field, not a sharply defined neon orb. The flagship product variant shifts this material to vivid green while keeping the upper-right dark.

**Transfer:** Include the grain-lit field in a new landing design, with gray as default. Match the soft glow; exact stops are not essential.

**Build:** On #080808, layer a broad radial-gradient ellipse centered near 0% 100%, using rgba(255,255,255,0.16) at its core and transparent by roughly 65%. Overlay SVG fractalNoise with baseFrequency 0.85 and two octaves at low opacity, clipped to the light mask. For the flagship variant replace white with rgba(122,255,120,0.65); keep text above the field.

### Monochrome human proof

**Use:** Customer stories and social proof.

**Observed:** Close, candid portraits are desaturated and strongly darkened where type sits; abstract alternatives use softly glowing silver marks on black. Card edges cut through the image rather than adding an inset thumbnail.

**Transfer:** Use editorial portraits with natural gestures, grayscale treatment and directional dark overlays. Keep logos white and small rather than saturating the entire card.

### Signal illustration

**Use:** Compact product capability cards.

**Observed:** Illustrations are miniature working systems: a green-to-amber rounded waveform, connected process nodes, sparse bar charts and stacked tool pills. Most of each illustration remains charcoal; only the active signal is colored.

**Transfer:** Reduce the new feature to a small meaningful diagram. Keep it anchored in the lower card area with the top-left copy unobstructed.

**Build:** For a waveform, repeat narrow rounded vertical bars at irregular heights across the lower card, gradient from translucent green at the top to apricot at the bottom, and place a dark command pill in front. For a process, use thin dashed gray connectors and dark circular nodes with small pale icons; tint only the active node.

### Soft metallic emblem field

**Only for:** flagship product openings

**Use:** A centered object before the product promise.

**Observed:** A small glossy silver emblem sits on a dark circular puck, surrounded by thin outlined organic cells and faint technical glyphs. The field fades downward into the headline area.

**Transfer:** Use a simple original product symbol rather than a complex mascot; the minimum is a shaded medallion with soft white edge highlights and sparse outline cells.

**Build:** Create a 200px dark circular puck with radial charcoal shading, a thin upper white highlight and soft lower black shadow. Render an original rounded symbol with white-to-gray specular gradients. Scatter irregular closed SVG paths and circles across a wide 600px-high field using 1px low-opacity gray strokes; vertically mask the lower half to black.

### Physical resource media

**Only for:** resource landing pages

**Use:** Hero object, proof photography and author introduction.

**Observed:** An oversized light book cover tilts in perspective on black, its lower edge fading into the plane. Photo proof cards show printed objects and real people; a full-width video portrait uses subdued natural color with black gradient behind bottom labels. Social cards combine small identity lines and square monochrome reader photos in an edge-clipped horizontal rail.

**Transfer:** Stage the actual downloadable or physical artifact with a light front face and restrained depth. For non-book resources, use a clean report or tool preview; follow it with tangible usage proof.

**Build:** Use a real cover layout on a perspective-transformed rectangle with 8px corners and a soft 16px by 36px downward shadow; overlay a top-left white sheen and lower dark mask. Photo cards use a transparent-to-rgba(0,0,0,0.8) vertical gradient with 40px clipping.

### Icons

**Observed:** Marketing utility icons are typically 16px–18px outlines with 1.5px rounded strokes, pale gray or white. Action-adjacent solid glyphs are about 18px–22px; the mono tabs pair one icon with each label.

**Transfer:** Choose simple laboratory, storage, flow and navigation-style symbols appropriate to the product. Keep a consistent fine stroke and avoid large multicolor icon badges.

## Section recipes

How recurring sections are built.

### First screen: Working object opening

**Observed:** The first screen is asymmetrical: a sticky 64px Navigation with an attached Announcement lip; behind it a near-black plane. The left promise sits around the upper-middle with a 54px single-line headline, 22px gray support limited to 352px, one selected green word, then Primary button and Secondary button 36px below, separated by 20px. At the right, a tall plane begins around half the width with a rounded upper-left corner, a cropped table and an overlapping menu. The working object extends toward the right and lower edges, while the text remains freestanding. Within the first 900px, the promise, explanation, both actions, principal object and first row of monochrome proof marks are visible; more proof and the first capability chapter continue below.

**Transfer:** Replace the table with an authentic process or result from the new product; use the layered-interface minimum recipe if no finished media exists. Keep copy compact enough to leave half the first screen for the object. Resource openings use the narrower editorial container and physical artifact with a signup shelf. Pricing opens with a 40px left headline, a right selector and immediate aligned offers. Customer proof opens with a horizontal promise/action bar and story grid. Flagship product openings use the emblem field above a centered 68px promise.

**Avoid:** Do not center the default opening, turn it into a giant gradient headline, or shrink the working object into a small boxed thumbnail beside a long paragraph.

**Text style:** `display` — greed 520 · 54px/1.1 · tracking 0.0047em

### Two-tone statement and sculpted stage

**Observed:** A centered 1000px-wide statement flows from bright assertion into muted elaboration at the same 40px size. Substantial dark space separates it from the stage. Feature selector controls form the stage's upper lip; the large demonstration fills the panel, with a small centered heading/support caption near its bottom under a dark fade.

**Transfer:** Make the first clause name a meaningful capability and the muted clause state what the reader gains. The sculpted stage device must appear, but its place in the narrative and number of repetitions depend on the product.

**Text style:** `section-statement` — greed 520 · 40px/1.1 · tracking 0.0064em

### Proof mosaic

**Observed:** Story card group in a Sculpted panel stage: one tall portrait at left and four smaller cards in two columns at right, with 24px gaps. A small raised tab names the group. Directory variants use a uniform three-column, two-row grid.

**Transfer:** Mix human proof and abstract outcome art so the grid has visual rhythm without varying the typography.

### Capability triptych

**Observed:** Three Feature cards under a two-tone statement. Each begins with a short bright title and muted support, while a chat fragment, signal illustration or operational log fills the lower area.

**Transfer:** Group three genuinely different jobs or audiences; maintain the same inset and visual baseline even when their illustrations differ.

### Editorial updates shelf

**Observed:** Two resource cards occupy one side, with physical cover previews rising from the lower area; compact release rows occupy the other. Small attached top labels identify the two collections. Release copy is modest 17px, with a muted date aligned away from the title.

**Transfer:** Pair evergreen learning with recent product activity; for a product without books use original reports, templates or guides.

### FAQ panel

**Observed:** FAQ glass contains a vertical stack of FAQ rows, with the first answer able to expand into readable 17px body copy. Resource and long-product versions have a small gray section heading above a 40px gap and ruled rows inside a solid panel.

**Transfer:** Write questions about compatibility, limits, effort and production use. Keep answers directly useful rather than repeating the promise.

### Grain-lit closing and footer slab

**Observed:** A centered short invitation uses the default 54px display with primary and transparent secondary actions below. A broad low-left grain-lit field extends behind the ending; expanded product variants use a 68px invitation and 64px action gap, with a green field reserved for the flagship treatment. The footer overlaps this material as an inset Sculpted panel, not a plain edge-to-edge band: 112px vertical inner padding, brand/newsletter/status rail and two rows of link groups. The resource variant ends its FAQ directly with the same footer instead of adding a separate closing invitation.

**Transfer:** Give the ending its own lit atmosphere and compact action, then make the footer feel like a final piece of hardware. Retain newsletter tab and mono status treatment, using only meaningful live-service labels for the new product.

**Text style:** `display` — greed 520 · 54px/1.1 · tracking 0.0047em

### Long product chapter

**Only for:** long product pages

**Observed:** A 54px centered chapter heading and 22px support, separated by 8px, sit inside a header with 180px top and bottom padding. A full-width lead illustration card is followed by three-column detail cards or a two-column process grid. Larger demonstration chapters can pair a tall working view with stacked text cards.

**Transfer:** Use chapters when users need to understand separate systems, not simply to lengthen a landing page.

**Text style:** `chapter-heading` — greed 500 · 54px/1.1 · tracking 0.0047em

### Physical proof and resource contents

**Only for:** resource landing pages

**Observed:** Two square photographic proof cards and a full-width author video precede a horizontally clipped social rail. A narrower contents area uses a sticky one-third introduction beside a two-thirds chapter list, all inside rounded dark panels. A restrained 32px mono count belongs within a photo label, with 20px support rather than a giant stats banner. The contents list uses compact regular 20px text and circular plus/minus controls; the signup pill returns beneath it.

**Transfer:** Show distribution or usage only when supportable. For other resources, use concrete adoption proof and an expandable outline of what the reader will learn.

### Pricing and comparison

**Only for:** pricing pages

**Observed:** Three Plan cards have aligned titles, prices, allowance rows and bottom actions, with a side rail of row names. The long comparison below uses a label column and three value columns divided by 2px dark vertical rules, not a checkerboard of cards. Plan summaries remain above the values during scrolling. A full-width blue-black support panel closes the technical comparison with three service columns.

**Transfer:** Separate the quick choice from detailed allowances. Keep green and blue local to the matching plan; use smaller type and sparse rules for technical comparisons.

### Filterable proof directory

**Only for:** customer directory pages

**Observed:** A centered 32px heading sits above two 36px-high pill filters and a search action. A single rounded panel contains roughly 88px-tall rows with white logo, uppercase mono organization label, muted one-line outcome and right arrow.

**Transfer:** Use when a collection has enough records to need filtering; maintain shared column alignment rather than giving every record its own card.

## Page flow

**Storyline:** Direct promise → visible working proof → capability or adoption detail → confidence and objections → useful next action → structured destination slab.

### Broad product introduction

1. **Promise** — Asymmetrical promise beside an enlarged working interface and immediate actions.
2. **Product demonstration** — Two-tone statements introduce sculpted tabbed stages.
3. **Social proof** — Monochrome outcome mosaic and recognizable organization marks.
4. **Application breadth** — Three practical-use cards with miniature working systems.
5. **Ongoing value** — Resource shelf beside recent release rows.
6. **Objection handling** — Generous disclosure panel.
7. **Closing call** — Grain-lit invitation followed by the dense rounded footer.

**Transfer:** Keep the object-led first impression and sculpted devices; select only the narrative blocks needed to explain the new product.

### Resource acquisition

1. **Resource promise** — Multiline title beside a physical artifact and attached email signup shelf.
2. **Tangible proof** — Photographic distribution and companion-resource cards, author video, reader social rail.
3. **Preview** — Sticky explanatory column beside expandable contents.
4. **Conversion** — Signup pill repeats after the outline.
5. **Objection handling** — Short ruled FAQ.
6. **Destinations** — Shared footer slab without a separate closing hero.

**Transfer:** Replace resource details with the new artifact's benefits, preview and credible usage; let the form remain the central conversion.

### Commercial evaluation

1. **Choice framing** — Compact left headline and right hosting selector above three offers.
2. **Pricing** — Aligned plan cards with neutral, green and blue-black material variants.
3. **Trust** — Monochrome proof marks.
4. **Detailed comparison** — Sticky plan summaries and sparse ruled allowance tables.
5. **Service reassurance** — Wide enterprise support panel.
6. **Closing call** — Short grain-lit invitation and shared footer.

**Transfer:** Keep quick plan scanning distinct from detailed evaluation; do not turn technical comparison into a marketing bento grid.

### Customer confidence and discovery

1. **Social promise** — Horizontal headline and action bar.
2. **Featured proof** — Uniform three-column story grid.
3. **Breadth of adoption** — Filterable logo-and-outcome directory.
4. **Closing call** — Grain-lit invitation and shared footer slab.

**Transfer:** Use this compact flow for case studies, integrations or verified applications with enough entries to browse.

### Deep product understanding

1. **Category promise** — Metallic emblem field and centered large headline.
2. **Capability chapters** — Spacious chapter headers followed by full-width illustrations, detail grids and working views.
3. **Commercial framing** — Two self-hosted offer cards.
4. **Social proof** — Three monochrome story cards.
5. **Objection handling** — Ruled FAQ panel.
6. **Closing call** — Green grain-lit invitation above the shared footer.

**Transfer:** Use the emblem opening and chapter rhythm only for a flagship product needing deeper systems explanation; preserve the neutral default elsewhere.

## Writing

Direct, developer-literate and confidently practical. Claims usually describe what a reader can build, inspect or ship, then earn credibility with concrete mechanisms or specific customer outcomes.

**Do not copy:** Do not reuse Mastra names, logos, emblem artwork, book covers, customer identities, testimonials, adoption counts, commercial terms or performance claims. Source copy examples illustrate voice only.

- **Addressing the reader:** Use you and your for benefits, direct imperative verbs for actions, and the product name as a matter-of-fact subject in explanations.
- **Rhythm:** Short functional headlines, often fragments or a three-part list. Follow with one or two explanatory sentences; allow longer precise answers in FAQs. Avoid exclamation marks and ornate metaphors.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Verb plus a concrete product job, or a comprehensive promise with a specific technical category. | 3–12 words | “Build AI agents”<br>“Everything you need to build AI agents in TypeScript” |
| Section statement | Short bright assertion followed by a plain-language benefit in the same sentence rhythm. | 3–18 words | “Best-in-class, built-in observability.”<br>“You can always see exactly what your [Brand] agents are doing.” |
| Supporting line | Describe the mechanism and practical outcome without a slogan. | 12–30 words | “Define typed agents with instructions, models, tools, and runtime behavior in one place.” |
| Primary action | Verb plus a small concrete next step. | 1–4 words | “Get a demo”<br>“Get your copy”<br>“Quickstart” |
| Proof headline | How an organization built something, tied to a meaningful scale or result. | 8–16 words | “How Range Built an AI-Native Investment Adviser Managing $17B” |
| Closing invitation | A brief invitation to begin, sometimes ending with today. | 3–7 words | “Start building with [Brand] today”<br>“Ship better agents” |

**Words and phrasing to use:** build; ship; production; tools; typed; trace; test; connect; in one place; real-world; workflows

**Avoid:** revolutionize everything; unlock limitless possibilities; magical; supercharge your journey; game-changing ecosystem

**Rules:**

- Lead with a job a practitioner recognizes; name the mechanism in the following line.
- Explain a feature with its behavior and benefit, not a pile of adjectives.
- Use quantitative proof only when it can be substantiated and tied to a real outcome.
- Keep the interface and the marketing explanation consistent in vocabulary.

## Do's and Don'ts

### Do

- Use 54px/1.1 weight-520 display type for the default opening rather than maximal oversized lettering.
- Keep 40px section assertions and their gray continuation in one balanced text block.
- Maintain 24px grid gaps and 38px card insets; the difference is part of the molded construction.
- Give the pale primary action a 50px height, 57px radius and faint bright rim.
- Preserve the 1328px content plane inside the 1376px stage shell.
- Use monochrome portraits or silver abstract marks for proof cards, with narrow top-left titles.
- Reserve 12.5px uppercase mono for small status markings and 17px uppercase mono for feature selectors.
- Give long capability headers 180px vertical breathing room rather than increasing card padding.
- Finish with the inset rounded footer and its small warm signup tab.

### Don't

- Do not replace the charcoal ramp with one uniform pure-black fill; #080808, #0a0a0a and #0f0f0f have different jobs.
- Do not make the primary CTA green or orange; its default fill is #cccccc.
- Do not set marketing headlines at weight 700 or apply negative display tracking.
- Do not spread green or blue gradients across ordinary section backgrounds; plan tints belong to offers and green atmosphere to the flagship ending.
- Do not turn the 40px corners into small 8px cards; 8px is for physical cover previews.
- Do not put every feature into a separate bright icon tile; working illustrations occupy the lower parts of dark panels.
- Do not enlarge footer headings above the 15.2px link scale or add heavy divider lines between every link.
- Do not use glossy colorful people cutouts against the proof cards; keep the portrait treatment monochrome and integrated.
- Do not turn the restrained 32px resource proof number into a giant dashboard-stat strip.

## Motion and responsive

### Motion

**Observed:**

- Declared button transitions cover background, border, color and transform over 0.15s; active buttons scale to 0.98.
- Declared hero object entry uses 0.7s cubic-bezier(.16,1,.3,1) with a 0.36s delay; hero text fades separately.
- Declared feature media entry uses 0.56s cubic-bezier(0.16,1,0.3,1); code entry uses 0.46s with the same curve.
- Declared horizontal slide rails use a 50s linear infinite cycle; waveform elements use a 1.5s wobble.
- Reduced-motion classes disable hero entrance animation and selected text transitions.

**Transfer:**

- Keep tab changes coordinated: selected lip, working media and caption change as one scene.
- Use small press compression rather than bouncy marketing buttons; preserve the slow tactile stage entry.

**Unknown:**

- Actual scroll triggers, full animation trajectories and complete reduced-motion behavior are not established.

### Responsive

**Observed:**

- Declared widths include 640px, 768px, 1024px and 1280px among additional finer breakpoints.
- Desktop navigation and the large right-side hero plane use large-screen visibility classes. Hero actions have column-to-row classes and full-width-to-fit behavior.
- The footer declares two columns at narrow widths, then a wider five-column structure; its radius changes from 32px to 40px.
- Resource and chapter display sizes have explicit clamp formulas in their recipes.

**Transfer:**

- On narrow layouts, retain the sculpted panel language but put the promise before its object; stack action pills and capability cards rather than reducing desktop media to illegible thumbnails.
- Preserve the technical selector function with a compact scrollable set or stacked demonstration; do not force six tiny tabs into the width.

**Unknown:**

- Exact mobile stage silhouettes, menu interaction and all breakpoint-specific spacing remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
