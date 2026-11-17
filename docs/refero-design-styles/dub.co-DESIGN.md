# Dub — luminous product machinery

## Overview

An airy, light software-marketing style that makes infrastructure feel approachable and unusually tangible. Soft geometric sans headings, practical grotesk text and occasional fine serif quotations sit inside a ruled architectural frame. White and pale gray dominate, with tiny candy-colored identifiers, washed rainbow light and meticulously layered interface illustrations; dark atmospheric calls to action provide the strongest contrast.

### Essentials

- A modest headline lets the product do the selling: Satoshi 48px/1.15 at weight 500, normal tracking, centered above a 908px-wide framed interface rather than oversized display lettering.
- The page reads as one ruled instrument panel: a centered 1080px frame, 1px #e5e5e5 vertical rails and horizontal section rules, with 40px inner heading insets and 80px chapter padding.
- Actions are compact rounded rectangles, not capsules: 8px corners, 14px/20px Inter at weight 500, 38px height and 8px 20px padding; black primary and white outlined secondary.
- Color behaves like indicator lights and atmosphere: keep the majority of the page white or near-white, use 16px orange, green and purple category squares, and diffuse multicolor illumination at 0.08 opacity behind the main product stage.
- Product proof floats in pale technical space: nested white panels, 1px edges, 12px inner and 20px outer top corners, faint shadows and lower-edge fades. Include a layered product scene; if no interface exists, diagram a real workflow with the same white modules and hairline connectors.
- A sculpted dark light-well supplies the signature contrast: use a #171717 band, a white concave top notch, faint grid, blurred rainbow overlay and centered 48px/48px light heading with paired 40px actions. Preserve this device on ordinary landing pages, without prescribing where it must occur.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Metric orange | `#ea580c` | `--color-metric` | text, accent | Infrastructure proof numbers; do not turn this into the primary action color. |
| Orange identifier | `#fb923c` | `--color-orange` | accent, surface | Small category icon squares. |
| Green identifier | `#4ade80` | `--color-green` | accent, surface | Small category icon squares. |
| Purple identifier | `#c084fc` | `--color-purple` | accent, surface | Small category icon squares. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action black | `#000000` | `--color-black` | action, background | Primary conversion buttons. |
| Heading ink | `#171717` | `--color-ink` | text, background | Primary headings and the dark atmospheric band. |
| Quotation ink | `#262626` | `--color-quote-ink` | text | Manifesto text, secondary button labels and editorial quotations. |
| Strong body | `#404040` | `--color-strong-body` | text, link | Long editorial text and emphasized link hover. |
| Body gray | `#525252` | `--color-body` | text | Opening support text and ordinary card prose. |
| Secondary text | `#737373` | `--color-secondary` | text, link | Capability descriptions, footer links and metric labels. |
| Muted gray | `#a3a3a3` | `--color-muted` | text, border | Secondary text on dark bands, hover outlines and numbered labels. |
| Stronger edge | `#d4d4d4` | `--color-edge` | border | Nested product frame, announcement and editorial quotation outlines. |
| Structural rule | `#e5e5e5` | `--color-rule` | border | Continuous frame rails, panel edges and section dividers. |
| Soft gray | `#f5f5f5` | `--color-soft` | surface, background | Opening product stage, inactive tabs and plan headers. |
| Pale canvas | `#fafafa` | `--color-canvas` | background, surface, text | Demonstration bands, customer tiles and light text on the dark call. |
| White | `#ffffff` | `--color-white` | background, surface, text | Main marketing canvas, raised panels and text on dark actions. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Operational green | `#22c55e` | `--color-status` | accent | Tiny status indicator in the footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | FAQ rule | `#e2e8f0` | `--color-faq-rule` | border | Cooler horizontal FAQ dividers. |
| company and culture pages | Culture rule | `#ededed` | `--color-culture-rule` | border | Lighter rails and grid divisions. |

## Typography

- **satoshi** — Marketing headlines and capability titles. Soft geometric sans with broad round forms; medium weight without heavy display drama. If unavailable, use **DM Sans**. Use weight 500 and preserve normal tracking for core headings. Font stack: "satoshi", "DM Sans", system-ui, sans-serif.
- **Inter** — Supporting prose, navigation, actions, labels and company-page headings. Functional high-x-height grotesk; regular prose and medium controls. Font stack: "Inter", system-ui, sans-serif.
- **GeistMono** — Large infrastructure counters. Even-width technical numerals used as proof, not decorative code. If unavailable, use **Geist Mono**. Font stack: "GeistMono", "Geist Mono", ui-monospace, monospace.
- **Rowan** (only for customer stories and testimonial spotlights) — Editorial quotations that distinguish the customer's voice. Fine, personable low-weight serif with expressive italic emphasis. If unavailable, use **Newsreader**. Use weight 300 and slightly tight tracking. Font stack: "Rowan", "Newsreader", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | satoshi | 500 | 48px | 1.15 | normal | Default opening headline; pricing and customer-directory titles use the same recipe left aligned. |
| heading | satoshi | 500 | 48px | 1 | normal | Capability chapter headings, centered social-proof heading and dark call heading. |
| heading-integrations | satoshi | 500 | 40px | 1 | normal | Split text-and-icon-field heading. |
| heading-compact | satoshi | 500 | 36px | 40px | normal | Compact proof section and utility-section titles. |
| update-heading | satoshi | 500 italic | 36px | 40px | normal | A brief product-momentum heading beside a release timeline. |
| manifesto | Inter | 400 | 30px | 1.375 | normal | Short editorial product argument in an isolated text column. |
| metric | GeistMono | 500 | 24px | 32px | normal | Infrastructure counters. |
| hero-support | Inter | 400 | 20px | 28px | normal | Opening description. |
| closing-support | Inter | 500 | 20px | 28px | normal | Muted support line on the dark call. |
| body-lead | Inter | 400 | 18px | 28px | normal | Capability descriptions and proof introductions. |
| body | Inter | 400 | 16px | 24px | normal | Ordinary testimonial prose and compact support paragraphs. |
| control | Inter | 500 | 14px | 20px | normal | Navigation, buttons and footer group headings. |
| small-link | Inter | 400 | 14px | 20px | normal | Footer and feature links. |
| metric-label | Inter | 400 | 14px | 20px | normal, uppercase | Labels above counters. |
| eyebrow | Inter | 500 | 12px | 16px | normal | Sentence-case category labels and announcement text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company pages | company-title | Inter | 500 | 40px | 1.2 | -0.03em | Opening mission heading above photography. |
| customer stories | story-title | satoshi | 500 | 32px | 1.2 | -0.02em | Restrained outcome-led article headline. |
| company pages | company-heading | Inter | 500 | 30px | 1.2 | -0.02em | Split section headings and centered values heading. |
| customer testimonial spotlights | spotlight-quote | Rowan | 300 | 26px | 1.4 | -0.02em | White serif quotation in the dark customer showcase. |
| customer stories | quote | Rowan | 300 | 24px | 1.45 | -0.025em | White editorial quotation cards. |
| company pages | company-card-heading | Inter | 500 | 24px | 32px | -0.02em | Numbered principle cards. |
| pricing pages | plan-title | Inter | 500 | 20px | 1 | normal | Plan names in pale plan headers. |
| customer stories | article-body | Inter | 400 | 16px | 1.75 | normal | Long-form text with room for underlined links and bold lead-ins. |
| company pages | company-body | Inter | 400 | 16px | 24px | -0.02em | Mission support and principle text. |
| pricing pages | faq-question | Inter | 500 | 16px | 24px | normal | Question text inside FAQ toggles. |

**Notes:**

- Core Satoshi headings use normal tracking, with the opening at 1.15 line height and section titles at 1. The compact title is 36px/40px rather than a proportional reduction of the hero.
- Do not apply company-page negative tracking to the default landing-page headings. Company Inter titles tighten from -0.02em to -0.03em at the opening.
- Customer quotes provide a scoped serif contrast; ordinary marketing testimonials remain Inter. Keep controls small rather than enlarging them to match the airy section spacing.

## Layout

**Density:** Airy section architecture surrounding compact, information-rich product objects and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and compact label stacks. |
| 12px | Eyebrow-to-heading and heading-to-description spacing; logo-grid gaps. |
| 14px | Footer link-list gaps. |
| 16px | Outer page side padding, action-pair gap and customer tile gaps. |
| 20px | Directory inner rails, plan side padding and opening headline-to-support gap. |
| 24px | Editorial card content gaps and dark-call support offset. |
| 32px | Chapter description-to-action gap and stat-group separation. |
| 40px | Chapter heading insets, opening actions offset and proof-card padding. |
| 48px | Team-grid gaps and numbered principle-card padding. |
| 64px | Footer vertical padding and opening top padding. |
| 80px | Standard chapter top padding and default opening bottom padding. |
| 96px | Infrastructure proof-band vertical padding and dark-call content top padding. |
| 128px | Dark-call lower breathing room. |
| 160px | Manifesto top breathing room. |

### Containers and grids

- **structural-frame**: max width 1080px · side padding 16px. Centered page-wide rails within full-width horizontal bands. Keep adjacent sections aligned to the same frame.
- **navigation-and-footer**: max width 1024px. Slightly inset header and footer contents.
- **opening-copy**: max width 672px · side padding 16px. Centered opening text; one or two restrained lines rather than spanning the full frame.
- **chapter-copy**: max width 576px · side padding 40px. Left-aligned chapter copy inside the rails; heading itself has a 512px maximum.
- **feature-details**: 3 columns · gap 40px. Three compact benefit descriptions beneath a broad demonstration; separated by fine vertical rules rather than isolated colored cards.
- **logo-strip**: 4 columns · gap 12px · side padding 20px. Two rows of calm logo tiles inside the structural frame.
- **customer-directory** (only for customer directories): 3 columns · gap 16px · side padding 20px. Logo-first 335px-wide tiles organized by category filter.
- **article-and-sidebar** (only for customer stories): max width 1080px · gap 56px · side padding 20px. 620px article column next to an approximately 335px pale company-information sidebar.
- **company-people** (only for company pages): 4 columns · gap 48px. 224px portraits or compact backer rows; leave incomplete final rows naturally aligned left.
- **pricing-columns** (only for pricing pages): 3 columns · gap 0px. Equal ruled plan columns with aligned feature rows, not three floating cards.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 8px |
| cards-and-media | 12px |
| product-stage-outer | 20px |
| category-square | 4px |
| announcement | 9999px (pill) |
| footer-top | 16px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | control | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Light control elevation; never a broad dark shadow. |
| customer stories | quote-card | `0px 1px 2px -1px rgba(0,0,0,0.08), 0px 2px 8px 0px rgba(0,0,0,0.06)` | Editorial quotation panels. |

### Surfaces

#### White canvas · level 0

**Use:** Main marketing surface.

**CSS:** `background: #ffffff`

**Observed:** White occupies most of the composition; structural rails persist through successive sections.

**Transfer:** Treat whitespace as a continuous surface, not empty space between unrelated cards.

#### Ruled frame · level 0

**Use:** Shared architectural wrapper.

**CSS:** `max-width: 1080px; margin: 0px auto; border-left: 1px solid #e5e5e5; border-right: 1px solid #e5e5e5`

**Observed:** Full-width horizontal boundaries intersect the frame. Company sections use the lighter culture rule.

**Transfer:** Make rails and section boundaries a single consistent system.

#### Pale demonstration band · level 0

**Use:** Technical product diagrams and capability demonstrations.

**CSS:** `background: #fafafa; border-top: 1px solid #e5e5e5; border-bottom: 1px solid #e5e5e5`

**Observed:** Quiet almost-white backing makes white UI panels readable without strong shadows. The opening stage uses soft gray instead.

**Transfer:** Keep interface framing more prominent than the background.

#### Dark light-well · level 0

**Use:** Signature contrast call.

**CSS:** `background: #171717; position: relative; overflow: hidden`

**Observed:** A low-intensity rainbow overlay sits behind a faint rectilinear grid, not a bright gradient fill. A broad white notch interrupts the upper edge.

**Transfer:** Use the sculpted edge and subdued colored light together; retain a sharply readable foreground.

#### Company glass grid · level 1

**Only for:** company pages

**Use:** Staggered principle cards over atmospheric sky imagery.

**CSS:** `background: rgba(255,255,255,0.45); border-top: 1px solid #ededed; backdrop-filter: blur(12px); padding: 48px`

**Observed:** Two columns are vertically staggered; white cloud and cyan light show softly through the top of the grid.

**Transfer:** Use a restrained atmospheric photograph behind transparent ruled panels, not frosted floating tiles.

## Components

### Navigation

**Use:** Persistent compact global header.

**CSS:** `height: 56px; position: sticky; top: 0px; z-index: 30; background: rgba(255,255,255,0.12); border-bottom: 1px solid rgba(245,245,245,0.165); backdrop-filter: blur(2.6px)`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Logo at left, five compact navigation entries centered, outlined login and black signup at right in a 1024px inner container. Dropdown items have tiny down chevrons. The translucent backing becomes more opaque and blurred over content.

**Transfer:** Keep the logo compact and actions subordinate to the opening promise.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #000000; color: #ffffff; border: 1px solid #000000; border-radius: 8px; padding: 8px 20px; height: 38px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Paired with Secondary button. Header variant is 32px high; pricing actions are 36px high. On dark calls the primary reverses to white with heading-ink text, 40px high and 0px 20px padding.

**States:** Declared: hover background-color rgb(38 38 38/1); box-shadow 0 0 #0000,0 0 #0000,0 1px 2px 0 rgb(0 0 0/0.05).

### Secondary button

**Use:** Demo, exploration and supporting navigation actions.

**CSS:** `background: #ffffff; color: #262626; border: 1px solid #e5e5e5; border-radius: 8px; padding: 8px 20px; height: 38px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `control` — Inter 500 · 14px/20px

**Observed:** Same geometry as the primary. Exploration controls use heading-ink labels. Dark-call variant uses white text, rgba(255,255,255,0.2) backing, transparent border, 4px backdrop blur, 40px height and 0px 20px padding.

**States:** Declared: hover border-color rgb(163 163 163/1); box-shadow 0 0 #0000,0 0 #0000,0 1px 2px 0 rgb(0 0 0/0.05).

### Announcement pill

**Use:** Small topical update above the opening headline.

**CSS:** `display: flex; height: 30px; background: #ffffff; border: 1px solid #d4d4d4; border-radius: 9999px; filter: drop-shadow(0px 1px 1px rgba(0,0,0,0.05))`

**Text style:** `eyebrow` — Inter 500 · 12px/16px

**Observed:** Two text segments: announcement at left and a short learn-more action at right, divided by a vertical edge with a tiny diagonal arrow.

**States:** Declared: hover background-color rgb(250 250 250/1).

**Transfer:** Keep the update short enough to remain visually subordinate.

### Category badge

**Use:** Tiny colored category identifier beside a sentence-case eyebrow.

**CSS:** `width: 16px; height: 16px; display: flex; align-items: center; justify-content: center; background: #fb923c; border: 1px solid rgba(0,0,0,0.05); border-radius: 4px`

**Observed:** A 10px dark glyph sits inside the colored square. Orange, green and purple distinguish capability families. The adjacent label uses Eyebrow with an 8px gap.

**Transfer:** Assign stable colors to product families rather than coloring whole sections.

### Product frame

**Use:** Main opening interface stage.

**CSS:** `border-top: 1px solid #e5e5e5; border-left: 1px solid #e5e5e5; border-right: 1px solid #e5e5e5; border-radius: 20px 20px 0px 0px; padding: 12px 12px 0px; mask-image: linear-gradient(#000000 50%, rgba(0,0,0,0) 90%)`

**Observed:** An outer 908px-wide frame wraps an 882px white inner window with stronger edges and 12px top corners. It shows a real dashboard with sidebar, chart, small tasks and table fragments.

**Transfer:** Use one coherent interface, then mask its lower edge into the stage instead of displaying a hard rectangular image.

### Footer link group

**Use:** Compact navigation inside the white ending.

**CSS:** `display: flex; flex-direction: column; gap: 14px; margin-top: 10px; color: #737373`

**Text style:** `small-link` — Inter 400 · 14px/20px

**Observed:** Medium 14px group heading above regular links. Product links carry colored category squares; other columns remain plain. Product and solutions stack in one column, alongside resources, company and comparisons.

**States:** Declared: hover color rgb(64 64 64/1).

### Status chip

**Use:** Small operational trust signal at the foot of the page.

**CSS:** `display: flex; align-items: center; gap: 8px; background: #ffffff; border: 1px solid #e5e5e5; border-radius: 8px; padding: 8px 10px 8px 8px`

**Observed:** An 8px green status dot precedes compact 12px medium text with 12px line height. Sits in the lower footer row opposite legal text, with a small certification mark between.

**States:** Declared: hover background-color rgb(250 250 250/1); active background-color rgb(245 245 245/1).

### Quotation card

**Only for:** customer stories

**Use:** Customer voice between article passages.

**CSS:** `display: flex; flex-direction: column; gap: 24px; background: #ffffff; border: 1px solid #d4d4d4; border-radius: 12px; padding: 32px 24px 32px 32px; box-shadow: 0px 1px 2px -1px rgba(0,0,0,0.08), 0px 2px 8px 0px rgba(0,0,0,0.06)`

**Text style:** `quote` — Rowan 300 · 24px/1.45 · tracking -0.025em

**Observed:** Serif quote above a small row of customer logo, circular portrait and muted name/role. Inline underlining, medium emphasis and italic words retain editorial character.

**Transfer:** Use a real attributed quotation; retain the delicate serif contrast.

### Customer tile

**Only for:** customer directories

**Use:** Compact browsable proof grid.

**CSS:** `background: #fafafa; border-radius: 12px; height: 140px; position: relative`

**Observed:** Logo centered in ample space; small read-story or diagonal external-link affordance sits at the top right. Category filters appear above the three-column grid.

**States:** Declared: hover background-color rgb(245 245 245/1).

**Transfer:** Use real partner or customer marks at optical, not identical bounding-box, sizes.

### Plan header

**Only for:** pricing pages

**Use:** Tier summary at the top of each ruled plan column.

**CSS:** `background: #f5f5f5; border-radius: 12px; height: 224px; padding: 24px 20px 20px; display: flex; flex-direction: column; justify-content: space-between; box-shadow: 0px 0px 0px 1px rgba(229,229,229,0.7)`

**Text style:** `plan-title` — Inter 500 · 20px/1

**Observed:** Name and price at top, short audience description in the middle and full-width action below. The middle recommended tier alone receives a black action; all columns retain the same pale header. Feature lists continue outside the rounded header.

**Transfer:** Let recommendation emerge from action contrast and a tiny badge, not a saturated plan background.

### FAQ row

**Only for:** pricing pages

**Use:** Final objection handling.

**CSS:** `border-bottom: 1px solid #e2e8f0; padding: 12px 0px`

**Text style:** `faq-question` — Inter 500 · 16px/24px

**Observed:** 688px reading width; inner question toggle has 16px vertical padding and a 20px plus aligned right. Last row has no divider. Opening state rotates the plus by 45 degrees.

**Transfer:** Keep FAQ text left aligned and questions terse.

## Imagery and graphics

### Luminous interface stage

**Use:** Primary product proof and repeated capability demonstrations.

**Observed:** Large white software window on a very pale gray stage, lavender light toward the left and mint toward the right. A soft white recessed tab shelf joins the stage to the opening. Later scenes isolate a few useful interface fragments, white list rows and small connector lines rather than repeating full dashboards. Objects fade into the background below.

**Transfer:** Create a legible workflow using genuine product modules. Minimum acceptable substitute is a polished SVG or HTML composition of a sidebar, chart and two meaningful summary panels; keep labels sparse and true to the product.

**Build:** For the stage, place a 1600px-wide, approximately 500px-high conic color field behind the nested Product frame, centered near the lower stage. Use red, yellow, mint, cyan, blue and violet source hues at 0.08 opacity, 200px blur and overlay blending. Match the pale lavender/mint impression rather than emphasizing distinct rainbow stripes. Form a centered white shelf above the stage with a shallow SVG concave contour.

### Dotted editorial theater

**Use:** A product argument or positioning passage.

**Observed:** A 530px text column floats inside a wider dotted field. Small white icon tiles and person-plus-stat cards hover on both sides, gently rotated. Orange, green and purple square glyphs also punctuate the text inline. The lower passage and decorations soften toward white.

**Transfer:** Keep the central argument readable; use small real workflow artifacts as peripheral objects. A dot texture, four white mini-cards and three inline category symbols are a sufficient equivalent.

**Build:** Use an SVG pattern of tiny pale-gray circles on an approximately 12px lattice, masked to fade around the perimeter. Put a white text island over its center. Place two 200px-class statistic cards at each side with 4–10 degree rotations, thin neutral borders and negligible shadow. Fade the bottom with a white alpha mask; keep text in the manifesto recipe.

### Infrastructure globe

**Use:** Quantified scale proof.

**Observed:** A luminous almost-white globe fills the right two thirds of a pale band, continents described in fine gray dots and sparse peach activity points. Small event cards overlap the lower right; the orange monospaced metrics remain in a narrow left column.

**Transfer:** Use a domain-relevant network, orbit or system diagram if geography is irrelevant. Retain the pale sphere-like light and restrained dot geometry; the diagram should support the numbers, not compete.

**Build:** Render a 600px-class circular white-to-transparent radial halo, then clip a field of gray SVG dots to a hemisphere or network silhouette. Add a few low-opacity orange points and three narrow white event cards at the lower right. Mask all artwork gradually into the pale backing.

### Dark spectral notch

**Use:** Signature contrasting call panel.

**Observed:** A white central recess cuts about 64px into the top of a 608px dark band, with softly rounded sloping shoulders. A barely visible square grid and dark violet, blue, green and ochre light sit behind centered text. The foreground remains mostly neutral, with white and translucent actions and a compact ratings row.

**Transfer:** Rebuild the sculpted light-well rather than substituting a plain black rectangle. Use actual trust indicators if available; otherwise replace the rating row with a short factual reassurance.

**Build:** Use an SVG top-edge mask with a broad centered flat-bottom white recess and rounded shoulders. On #171717, add an oversized conic-gradient layer extending 40px outside each edge, rotated from -81deg, with blue, violet, red, yellow, mint and cyan stops. Blur 30px, set opacity 0.3 and overlay blend. Above it draw 1px white grid lines at very low alpha and fade the grid toward the bottom; keep foreground type and actions above both layers.

### Integration tile field

**Use:** A compact ecosystem interlude.

**Observed:** Copy stays on the left while colorful app icons float in a faint square grid on the right, mixing solid logo tiles with empty recessed grid cells. The stage is pale gray; icons have rounded corners and small contact shadows.

**Transfer:** Use relevant integrations or workflow symbols, avoiding a uniformly packed logo wall.

**Build:** Create a fine 60px-class square SVG grid with a center-right fade. Scatter 60px white or brand-colored icon tiles in an irregular checkerboard, with 8px corners and soft 0px 2px 4px black-alpha shadows. Give a few tiles very slight rotation.

### Customer film panels

**Only for:** customer directories and stories

**Use:** Human proof at the opening.

**Observed:** Interview stills show people in real work or social environments, with natural skin tones, dark contextual backgrounds and restrained saturated light. The directory uses one wide 568px card beside three narrow portrait strips, all 480px high and 12px rounded. Story detail expands to 1040px by 510px with 16px corners and bottom-overlay statistics.

**Transfer:** Use authentic interview or product-user imagery, not abstract office stock. Preserve darkened lower areas for white titles and use a customer-associated tint subtly behind the image.

### Culture photography and sky

**Only for:** company pages

**Use:** Mission opening, people grid, values atmosphere and life-at-company band.

**Observed:** Natural coastal and outdoor team photography opens in a large two-thirds image beside two stacked smaller images, 12px rounded. Individual portraits are warm, frontal square images with 8px corners. A later wide photo ribbon varies image sizes and fades at both edges. A soft cyan sky-and-cloud glow backs the principle grid.

**Transfer:** Use real team scenes with natural color and a shared portrait treatment; preserve the asymmetric collage and edge-faded photo ribbon. Keep the sky imagery as atmosphere, not a literal illustration of each principle.

**Build:** For the values atmosphere, place a wide bright sky photo behind the centered heading and upper two-column grid. Mask it radially into white and overlay the Company glass grid. Minimum equivalent is a pale cyan radial light with a few soft white blurred cloud shapes.

### Icons

**Observed:** Small rounded outline SVGs dominate: 12px or 16px, usually 1.5px strokes and round caps. Dropdown chevrons are 10px. Product-family glyphs are darker solid or stroked symbols in 16px colored squares; footer social marks are compact monochrome solids.

**Transfer:** Use a coherent thin rounded icon set, keep navigation arrows tiny and reserve colorful squares for stable product categories rather than every bullet.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and recessed product stage

**Observed:** A 56px Navigation sits above a white, centered promise composition within the 1080px Ruled frame. Opening content begins with Announcement pill after 64px top breathing room; the 48px Display headline follows by 20px and stays a single modest line at desktop. Hero-support follows by 20px, constrained to 640px and usually two lines. Primary button and Secondary button sit 40px below support, 16px apart. The white opening occupies about 403px below navigation. A pale stage begins immediately beneath, with category tabs on a recessed white shelf and the 908px Product frame centered below it. Back to front: white ruled field and faint fading grid, soft color light, shelf and framed interface, crisp text and controls. Within the first 900px, the entire promise, support, actions, tabs and upper dashboard are visible; the lower demonstration and logo proof continue below the fold.

**Transfer:** Write one direct outcome headline and show one persuasive working object. Without a finished interface, build the minimal Luminous interface stage from real product concepts rather than a generic mock dashboard. Pricing opens left aligned with this same Display recipe and switches; directories open left aligned above film panels; customer stories use Story-title above a large interview still; company pages use Company-title above a photographic collage.

**Avoid:** Do not turn the opening into a full-height text-only hero, giant type poster, split illustration layout or saturated gradient billboard. Do not push the first product object entirely below 900px.

**Text style:** `display` — satoshi 500 · 48px/1.15

### Capability chapter

**Observed:** 80px top padding, 40px heading inset, Category badge plus Eyebrow, 12px to Heading and 12px to Body-lead. Copy is no wider than 576px; Secondary button appears after 32px. A full-width Pale demonstration band follows, then three benefit details with short labels, gray 14px prose and tiny learn-more links. A testimonial strip closes the chapter with a dot-field backing and customer attribution.

**Transfer:** Use this as a reusable capability explanation, selecting different product scenes rather than repeating identical dashboard images.

**Text style:** `heading` — satoshi 500 · 48px/1

### Manifesto theater

**Observed:** A narrow 530px Manifesto column uses short paragraphs separated by 32px inside the Dotted editorial theater. Inline category symbols interrupt prose; surrounding cards stay peripheral. 160px top and 128px bottom breathing room make it feel like a considered argument rather than a card grid.

**Transfer:** Explain a useful contrast between an old process and a better outcome, while using relevant artifacts around the central text.

**Text style:** `manifesto` — Inter 400 · 30px/1.375

### Scale proof band

**Observed:** A pale band pairs a 304px text-and-counter column with Infrastructure globe art. Heading-compact and a short gray description sit above vertically stacked Metric values with uppercase Metric-label, 8px label-to-number spacing and 32px between groups. The band uses 96px vertical padding.

**Transfer:** Show a small set of defensible operating metrics alongside a relevant dotted system illustration.

**Text style:** `metric` — GeistMono 500 · 24px/32px

### Ruled proof mosaic

**Observed:** Centered Heading and Body-lead introduce a white mosaic. Four underlying columns use 1px gaps filled by Structural rule; logo-only cells alternate with two-column testimonial cells. Testimonials use 40px padding, a customer mark above prose, colored category tags below and a small person attribution at the bottom right.

**Transfer:** Mix concise customer statements with logo-only cells to vary density without changing the grid.

**Text style:** `body` — Inter 400 · 16px/24px

### Momentum timeline

**Observed:** An equal split inside the rails places italic Update-heading, brief description and changelog button at left. At right, a vertical rule connects 48px circular icon markers through rows about 144px tall; each row contains a medium 16px release title and muted date.

**Transfer:** Use for product updates or any genuine sequence of progress. Keep the title's italic exception local.

**Text style:** `update-heading` — satoshi 500 italic · 36px/40px

### Dark closing call and white footer

**Observed:** Dark light-well contains a centered two-line Heading at a 512px maximum, 24px to Closing-support at a 560px maximum, 40px to reversed Primary button and glass Secondary button separated by 12px. A three-part ratings row follows. The white footer uses 64px vertical padding, a logo and socials block at left and compact Footer link groups at right, then Status chip, certification and legal line across the bottom. Pricing instead moves directly from FAQ row list to this white footer without the dark call.

**Transfer:** Use the dark sculpted device as a high-contrast action moment on ordinary landing pages, and adapt its reassurance row to truthful proof. Keep transactional pricing endings utility-first.

**Text style:** `heading` — satoshi 500 · 48px/1

### Pricing decision system

**Only for:** pricing pages

**Observed:** Left-aligned Display title and Hero-support precede product and billing segmented controls. Three equal ruled columns contain Plan header and feature lists. A centered testimonial separates summaries from comparison. Comparison repeats plan names, prices and actions in a sticky compact header over 53px ruled feature rows grouped by collapsible category. Another centered testimonial precedes a 688px FAQ list and white footer.

**Transfer:** Use the same columns and alignment for any tier structure; let the middle-tier action carry recommendation.

**Text style:** `display` — satoshi 500 · 48px/1.15

### Customer directory and spotlight

**Only for:** customer directories

**Observed:** Left-aligned opening text and action pair lead into Customer film panels and a compact logo strip. A 1038px dark spotlight uses a small portrait above Spotlight-quote, attribution and read-story link, a subtle oversized customer symbol on the right and six logo tabs along the bottom; the selected tab emits blue light. A heading and category filter lead into Customer tile grid, then the dark call and footer.

**Transfer:** Use customer-associated visuals and real outcomes; preserve the asymmetry of the film cards and the contrast of the editorial spotlight.

**Text style:** `spotlight-quote` — Rowan 300 · 26px/1.4 · tracking -0.02em

### Case study editorial

**Only for:** customer stories

**Observed:** Breadcrumb, customer logo, a 540px Story-title and compact introduction precede a 1040px interview panel with three bottom-aligned results. Below, a 620px article column runs beside a pale information sidebar. Article-body, bold problem lead-ins, underlined links, 24px Satoshi subsection links, Quotation card and thinly framed product or social proof media alternate. A final customer quote and direct paragraph action close the article before the dark call and white footer.

**Transfer:** Keep the story specific: initial friction, implementation, workflow improvements, measurable result and attributed recommendation. Let the sidebar summarize context without competing with the narrative.

**Text style:** `story-title` — satoshi 500 · 32px/1.2 · tracking -0.02em

### Company editorial chapters

**Only for:** company pages

**Observed:** Company-title and short support precede the asymmetric three-photo collage. Logo proof leads into a centered sky-backed heading over staggered Company glass grid principle cards, numbered in muted gray. Later chapters pair Company-heading on the left with supporting text on the right across a 96px column gap. A horizontal year-marked history rail, four-column portrait grid, edge-faded culture ribbon and four-column backer list precede the shared dark call and footer.

**Transfer:** Borrow the collage, staggered grid, horizontal history and human portrait treatment for an organization narrative without forcing every subject into a feature-card template.

**Text style:** `company-heading` — Inter 500 · 30px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Outcome promise → tangible product or human demonstration → contextual proof → capability or narrative depth → quantified or attributed reassurance → next action and compact utility ending.

### Broad product landing page

1. **promise** — Centered headline, concise product definition, compact action pair and recessed interface stage.
2. **social proof** — Small logo strip and a dotted editorial positioning passage.
3. **capability chapters** — Repeated category-led sections, broad pale demonstrations and compact benefit rows, interspersed with integration and scale proof.
4. **attributed proof** — Ruled logo-and-quotation mosaic.
5. **product momentum** — Italic lead beside a vertical release timeline.
6. **closing call** — Sculpted dark light-well, reassurance row and white multi-column footer.

**Transfer:** Adjust chapter count to the product; keep the alternating airy explanation, tangible proof and compact reassurance.

### Pricing and purchase evaluation

1. **choice framing** — Left-aligned promise and trial reassurance, product selector and billing switch.
2. **pricing** — Three ruled plan columns with pale summary headers.
3. **social proof** — Centered customer quotation with logo, person and story link.
4. **comparison** — Sticky tier summary over grouped ruled feature rows.
5. **objection handling** — Second customer quote followed by narrow FAQ toggles.
6. **utility ending** — White footer immediately after FAQs; no dark call.

**Transfer:** Prioritize aligned comparisons and specific buyer questions over adding promotional sections.

### Detailed customer outcome story

1. **outcome promise** — Customer identity, outcome-led smaller headline, interview still and three results.
2. **context and friction** — Readable article with problem bullets and context sidebar.
3. **implementation and outcomes** — Subsection links, interface media, quoted experience and social proof.
4. **recommendation** — Final attributed quote and a short direct invitation.
5. **closing call** — Shared dark call and white footer.

**Transfer:** Use real operational details and keep the primary reading column narrow.

### Customer proof directory

1. **promise** — Left-aligned introduction and actions above asymmetric film panels.
2. **attributed proof** — Dark serif testimonial spotlight with selectable customer logos.
3. **exploration** — Category filters and a three-column logo tile directory.
4. **closing call** — Shared dark call and white footer.

**Transfer:** Mix one deep human endorsement with scannable breadth instead of showing only a logo wall.

### Organization and culture narrative

1. **mission** — Tighter Inter heading above a natural team-photo collage.
2. **credibility** — Compact logo strip.
3. **principles** — Sky-backed staggered numbered glass grid.
4. **history** — Horizontal year-and-image milestone rail.
5. **people and culture** — Warm portraits, mixed-size photo ribbon and compact backer rows.
6. **closing call** — Shared dark call and white footer.

**Transfer:** Choose relevant organization chapters; keep the lighter editorial type and real human imagery scoped to this narrative.

## Writing

Confident, practical and lightly enthusiastic. Outcome language is paired with concrete mechanisms, while short personal statements make technical infrastructure feel human.

**Do not copy:** Do not reuse Dub names, logos, branded product names, customer marks, quotations, statistics, review scores, proprietary artwork or business claims. Source examples illustrate syntax and tone only; replace them with truthful material belonging to the new product.

- **Addressing the reader:** Address the reader as you and your in benefit copy; use we for the team and product progress, and name the product when defining what it is.
- **Rhythm:** Mostly three-to-seven-word headlines, one or two support sentences and two-to-three-word actions. Longer editorial passages alternate blunt short statements with concrete explanatory sentences; feature rows are terse.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Verb plus a tangible business transformation. | 4–7 words | “Turn clicks into revenue” |
| Supporting line | Define the product category and name the few things it unifies. | 15–25 words | “[Brand] is the modern link attribution platform for short links, conversion tracking, and affiliate programs.” |
| Capability heading | A memorable plain-language benefit, not a technical noun list. | 4–6 words | “Measure what matters”<br>“Connect with your favorite tools” |
| Primary action | Direct verb with low-friction next step. | 2–4 words | “Start for free”<br>“Get a demo” |
| Editorial contrast | Not just a superficial measure; a more useful outcome. | Two short sentences | “Marketing isn't just about clicks. It's about outcomes.” |
| Case study title | How a named customer achieves a quantified workflow result. | 10–15 words | “How Framer manages $900K in monthly partner payouts with [Brand]” |
| Momentum | Short first-person declaration of ongoing improvement. | 3–5 words | “We ship fast” |
| Pricing reassurance | Plain-language terms and transparent trial information. | One sentence | “Simple and transparent pricing that includes a 14-day trial.” |

**Words and phrasing to use:** modern; built-in; real-time; from first step to outcome; all-in-one; grow with you; measure what matters; streamline; powerful

**Avoid:** revolutionary paradigm; unprecedented synergy; magical transformation; breathless superlative chains; vague innovation without a mechanism

**Rules:**

- Connect each technical capability to a user or business outcome.
- Keep section headings sentence case and category labels brief; uppercase is reserved for metric labels.
- Use numbers in outcome stories only when supported; let specificity carry confidence.
- Use short exploration labels after explanations rather than verbose button copy.
- Retain contractions and simple language even in infrastructure descriptions.

## Do's and Don'ts

### Do

- Keep the main frame at 1080px and align neighboring 1px rails.
- Use 48px medium Satoshi headings with normal tracking for core marketing hierarchy.
- Give chapter headings 40px inner insets and 80px top padding.
- Keep ordinary action controls 38px high with 8px corners and 14px medium labels.
- Use 16px colored squares to encode stable categories.
- Stage white interface fragments on #fafafa and preserve bottom fades.
- Use 24px orange monospaced values with small uppercase labels for scale proof.
- Retain the sculpted 608px dark light-well and the separate white footer on ordinary landing pages.

### Don't

- Do not replace the core headline's normal tracking with aggressive negative display tracking.
- Do not give every control pill geometry; reserve 9999px rounding for announcements and small circular devices.
- Do not make orange, green or purple the default button fill.
- Do not replace the fine #e5e5e5 structural lines with thick dark dividers.
- Do not give interface panels broad black shadows; the control shadow is only 0px 1px 2px at 0.05 alpha.
- Do not use the customer-story serif for ordinary feature headings or body copy.
- Do not tint the entire recommended pricing column; recommendation is mainly a dark action inside a pale header.
- Do not turn the white footer into a continuation of the dark call; its compact gray navigation is a distinct ending.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions commonly use 75ms or 0.15s cubic-bezier(0.4,0,0.2,1) for colors; primary and secondary controls declare all-property 0.15s transitions.
- The opening headline and support declare slide-up-fade with 1s duration and respective 0.1s and 0.2s delays, using cubic-bezier(0.16,1,0.3,1). Product frames declare transform or opacity transitions of 0.3s.
- Logo flips declare 0.28s ease-out entry and 0.18s ease-out exit; horizontal and vertical continuous scroll treatments declare 20s linear loops. Footer status uses a 1s ping.
- Story quotations include previous, next and pause controls; the selected quote indicator is an elongated small pill.

**Transfer:**

- Keep movement concentrated in interface demonstrations, proof selectors and small live indicators; preserve stationary structural rails and readable foreground copy.
- Use controlled fades when exchanging product-stage contents rather than changing the whole page background.

**Unknown:**

- Exact trigger behavior, complete keyframe transforms and interaction playback are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px and 1280px, alongside smaller specialized breakpoints.
- Default opening headline classes specify 36px below the 640px step and 48px above it; chapter headings progress through 30px, 36px and 48px.
- The product stage declares a 380px height below the desktop step and 580px above it. Logo strips declare two columns before four; release layout declares one column before two; directory declares one column before three. Desktop navigation is hidden below the 1024px step.

**Transfer:**

- On narrow layouts preserve the promise-to-product relationship: reduce stage height rather than removing the object, retain the white shelf and pale light.
- Stack story sidebar content after the article and convert company split headings into a vertical pair; preserve the rail alignment with 16px outer gutters.
- Let the dark notch shrink proportionally while keeping its shoulders legible and its foreground actions readable.

**Unknown:**

- No narrow-screen rendered layouts were supplied; precise mobile navigation and comparison-table interactions remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
