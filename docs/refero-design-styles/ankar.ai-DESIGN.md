# Ankar — scholarship meets spectral fields

## Overview

An editorial technology style that pairs literary serifs with tiny technical monospace labels. Cool pale gray reading areas alternate with cinematic working-world photography and broad fields of wine red, indigo and midnight blue. The result feels intellectually ambitious and human rather than like a conventional software dashboard, with sparse compositions and unusually large statements suited to complex enterprise products.

### Essentials

- Literary statements carry the hierarchy rather than bold sans-serif slogans: Crimson Pro Variable at 130px/1.1 with -4px tracking for display, 80px/1.1 with -2px tracking for section leads, all weight 400.
- The opening is a working-world film still, not a floating app window: full-bleed darkened photography across an 810px stage, two-line white display at left, 18px/24px serif explanation and a glass action at right, plus a slim proof capsule near its foot.
- Controls look like small instruments laid over an editorial spread: 12px DM Mono labels, 40px-high actions with 20px radii, a 60px translucent navigation capsule with 30px radii and black conversion button.
- Color is concentrated into fields rather than sprinkled through text: most reading sections use #eef2f6 and black; broad #ba484f, #2f3d86 and #162247 chapter panels and a red-to-indigo closing atmosphere supply the saturated moments.
- Expandable editorial spines are a signature device: 480px-high rounded panels combine one broad story with 200px-wide neighboring strips whose serif titles turn vertically. Carry this device into a new page using capabilities, evidence or customer stories.
- Scientific line art and atmospheric color belong together: fine white branching paths and circular nodes sit on a soft red–indigo field in a 40px-rounded media panel. Use a simple SVG flow diagram over the same atmosphere when no proprietary visualization exists.
- The ending is a second monumental statement, not a utility strip: 130px white serif words bracket a glass CTA above small ruled navigation groups, a muted description and oversized brand artwork at 0.1 opacity. Preserve the atmospheric closing field and low-contrast brand silhouette with the new identity.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Wine red | `#ba484f` | `--color-wine` | surface, accent | Broad active chapter field and the warm side of atmospheric graphics. |
| Indigo | `#2f3d86` | `--color-indigo` | surface, accent | Secondary chapter spine and the cool luminous middle of atmospheric fields. |
| Midnight blue | `#162247` | `--color-navy` | surface, background | Deep chapter spine and dark base for the red–indigo atmosphere; the atmosphere can deepen toward near-black. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Powder blue | `#94b9eb` | `--color-action-blue` | action, accent | Small resource and trust actions; tiny section-marker dots. Keep it off ordinary body text. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Default text on pale sections, solid conversion buttons and backing beneath dark photographic cards. |
| Dark-scene glass | `#5c647e` | `--color-glass-dark` | surface | Representative visible tint of 30% white over midnight blue on glass actions; the precise appearance follows the scene behind it. |
| Mist text | `#a2a7b5` | `--color-muted-light` | text | Representative 60% white over midnight blue for the closing description; secondary footer links use a dimmer white opacity. |
| Blue-gray hairline | `#cdd9e5` | `--color-rule` | border | 1px chapter separators and the outlined proof capsule. |
| Blue paper | `#eef2f6` | `--color-canvas` | background | Dominant reading canvas; also the rounded leading edge below the recruitment opening. |
| Milk glass | `#fafbfc` | `--color-glass-light` | surface | Visible appearance of 70% white over blue paper in navigation; the same material takes on the underlying photograph or atmosphere over media. |
| White type | `#ffffff` | `--color-white` | text, border | Display, body and fine line art over dark media. Translucent white is used for the navigation and glass actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| institutional company pages | Charcoal | `#171717` | `--color-editorial-ink` | text, action | Softer black for institutional editorial text and compact pill actions. |
| institutional company pages | Portrait gray | `#979797` | `--color-caption-gray` | text | Role and background captions under portraits. |
| institutional company pages | Warm opening paper | `#f0efeb` | `--color-warm-paper` | background | Centered institutional opening band. |
| institutional company pages | Warm closing paper | `#f0efec` | `--color-warm-close` | background | Centered institutional conversion band before the atmospheric ending. |
| institutional company pages | Light tile | `#f5f5f5` | `--color-logo-tile` | surface | Low-contrast investor or partner logo tiles. |
| institutional company pages | Chalk | `#fafafa` | `--color-editorial-paper` | background | Institutional reading background. |

## Typography

- **Crimson Pro Variable** — Core display, section headings, card titles and quotations. Fine, literary serif with expressive contrast; regular weight and compressed spacing. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Crimson Pro Variable", Georgia, serif.
- **Crimson Text** — Core explanatory paragraphs and small closing description. Readable book serif; creates continuity with display type rather than switching to a software sans. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Crimson Text", Georgia, serif.
- **DM Mono** — Navigation, actions, section markers, numbering, metadata and technical proof. Small regular monospaced labels; normal tracking and mostly sentence case. Font stack: "DM Mono", ui-monospace, monospace.
- **EB Garamond** (only for institutional company pages) — Centered title, editorial headings and portrait names. Traditional Garamond forms, regular weight, tightly set headings. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "EB Garamond", Georgia, serif.
- **Switzer** (only for institutional company pages) — Compact institutional body and portrait captions. Neutral contemporary grotesk, visually secondary to the serif. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Inter**. Use regular weight and retain compact 14px body sizing. Font stack: "Switzer", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Crimson Pro Variable | 400 | 130px | 1.1 | -4px | Two-line opening promise and monumental atmospheric closing line. |
| heading-lg | Crimson Pro Variable | 400 | 80px | 1.1 | -0.025em | Major section leads, usually split into two or three lines. |
| spine-title | Crimson Pro Variable | 400 | 52px | 1 | -1px | Photographic story titles and vertically rotated chapter spines. |
| heading | Crimson Pro Variable | 400 | 45px | 1.1 | -1px | Numbered benefits, implementation headings and testimonial names. |
| heading-sm | Crimson Pro Variable | 400 | 36px | 1.1 | -1px | Supporting card claims, assurance headings and listing titles. |
| quote | Crimson Pro Variable | 400 | 30px | 1.1 | -1px | Long quotations over photographic proof cards. |
| body | Crimson Text | 400 | 18px | 24px | normal | Core explanations, feature detail and recruitment copy. |
| footer-description | Crimson Text | 400 | 14px | 1.2 | normal | Muted descriptive paragraph beside closing navigation. |
| label | DM Mono | 400 | 12px | 1.6 | normal | Eyebrows, navigation, numbers, metadata, text links and proof labels. |
| button | DM Mono | 400 | 12px | 14px | normal | Black and glass conversion actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| institutional company pages | institutional-title | EB Garamond | 400 | 64px | 1.06 | -0.018em | Centered opening title over warm paper. |
| institutional company pages | institutional-heading | EB Garamond | 400 | 48px | 1 | -0.01em | Mission, people, partner and community headings; centered closing invitation. |
| institutional company pages | portrait-name | EB Garamond | 400 | 40px | 1.1 | -0.012em | Names beneath square portraits. |
| institutional company pages | portrait-caption | Switzer | 400 | 16px | 1.58 | normal | Muted role and professional background under portrait names. |
| institutional company pages | institutional-body | Switzer | 400 | 14px | 1.58 | normal | Compact mission text alongside a larger serif statement. |

**Notes:**

- Keep the dominant serif at weight 400; scale and line breaks, not boldness, create authority.
- The core scale descends from 130px to 80px to 45px and 36px. Spine titles form a separate 52px treatment rather than a new global heading tier.
- Body copy remains serif on ordinary marketing and recruitment pages. The smaller Garamond-plus-grotesk system is reserved for institutional editorial content.
- Avoid tracked all-caps as the default label voice: most 12px mono labels are mixed case at normal tracking.

## Layout

**Density:** Airy at section scale, compact inside controls and chapter panels; long editorial intervals surround tightly connected labels and detail.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Default local gap between copy, headings, labels and controls. |
| 20px | Card insets and horizontal button padding. |
| 40px | Desktop page gutters and space before major media rows. |
| 80px | Desktop heading-pair gap and institutional section padding. |
| 120px | Recurring separation between major marketing chapters and opening top padding. |
| 16px | Institutional logo-grid gaps. |
| 24px | Institutional two-column gutters. |
| 32px | Logo-tile padding and spacing above documentary image pairs. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 40px. Centered desktop wrapper yielding 1360px content at a 1440px viewport. The opening and closing atmosphere bleed to the viewport edges.
- **opening-pair**: 2 columns · gap 80px. Two equal 640px columns inside the desktop content width; large statement left and narrower-looking serif explanation with action right.
- **heading-pair**: 2 columns · gap 80px. Asymmetric lead-and-support row: the heading occupies about two thirds, support about one third, often bottom aligned.
- **implementation-grid**: 2 columns · gap 40px. Widely separated numbered service headings, left and right, without enclosing cards.
- **institutional-container** (only for institutional company pages): max width 1040px · side padding 24px. Centered editorial width nested within 200px desktop outer gutters; inner content spans 992px.
- **portrait-pair** (only for institutional company pages): 2 columns · gap 24px. Two square 484px portraits with left-aligned names and captions.
- **partner-grid** (only for institutional company pages): 3 columns · gap 16px. Two rows of 320px-wide, 199px-high logo tiles.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and chapter cards | 20px |
|  | navigation capsule | 30px |
|  | diagram panels and large section edges | 40px |
|  | proof capsule | 80px |
| institutional company pages | editorial images | 4px |
| institutional company pages | institutional buttons | 500px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| glass inner rim | `rgba(255, 255, 255, 0.4) 0px 2px 2px 0px inset, rgba(255, 255, 255, 0.4) 0px -2px 2px 0px inset` | Glass actions over photographs and atmospheric color. This is an inner highlight, not an external drop shadow. |

### Surfaces

#### Blue paper · level 0

**Use:** Default light reading canvas.

**CSS:** `background: #eef2f6; color: #000000`

**Observed:** Broad uninterrupted areas carry headings, numbers and fine separators; ordinary copy is not placed on raised white cards.

**Transfer:** Let typography and rules organize most content.

#### Navigation glass · level 2

**Use:** Fixed navigation backing.

**CSS:** `background: rgba(255, 255, 255, 0.7); border-radius: 30px; backdrop-filter: blur(4px); filter: blur(1px)`

**Observed:** The blur belongs to a backing layer beneath crisp logo, links and action. It becomes near-white over pale sections and milky gray over media.

**Transfer:** Keep the blurred backing separate from its text layer.

#### Photo veil · level 1

**Use:** Readable white text on story imagery.

**CSS:** `background: linear-gradient(90deg, rgba(0, 0, 0, 0.1) 0%, rgba(0, 0, 0, 0.5) 100%)`

**Observed:** Directional veils support a quote or caption while leaving the subject visible. Narrow neighboring panels can use a stronger fade toward black.

**Transfer:** Choose the veil direction to support the text position; do not flatten every image to the same gray.

#### Chapter color · level 1

**Use:** Solid active chapter panel.

**CSS:** `background: #ba484f; color: #ffffff; border-radius: 20px; overflow: hidden`

**Observed:** The expanded panel uses wine red; adjacent collapsed chapters use indigo and midnight blue. Thin translucent white rules and subtiles add internal structure.

**Transfer:** Use the three fields as a small chapter family, not an alternating rainbow of sections.

#### Spectral atmosphere · level 0

**Use:** Signature closing field and diagram backing.

**CSS:** `background: radial-gradient(ellipse at 5% 5%, rgba(186, 72, 79, 0.95) 0%, rgba(186, 72, 79, 0) 55%), radial-gradient(ellipse at 30% 30%, rgba(47, 61, 134, 0.95) 0%, rgba(47, 61, 134, 0) 70%), #162247`

**Observed:** A broad, soft wine-red light at the upper left blends diagonally through violet and indigo into very dark navy at the lower right. The field feels continuous, softly textured and much larger than a small decorative glow.

**Transfer:** Match the soft field and deep falloff; exact gradient stops are not essential. Use the imagery build recipe for subtle texture.

#### Institutional paper · level 0

**Only for:** institutional company pages

**Use:** Warmer, more restrained editorial variant.

**CSS:** `background: #fafafa; color: #171717`

**Observed:** A warm #f0efeb title band and #f0efec conversion band surround chalk reading sections; low-contrast #f5f5f5 tiles organize partner logos.

**Transfer:** Use for company narrative and people-focused editorial content, not as a replacement for the default cinematic opening.

## Components

### Floating navigation

**Use:** Persistent orientation and conversion.

**CSS:** `height: 60px; border-radius: 30px; display: flex; align-items: center; padding: 0px 10px; gap: 40px`

**Text style:** `label` — DM Mono 400 · 12px/1.6

**Observed:** A separate Navigation glass backing sits 20px below the viewport top, inset 40px from either side. A black logo anchors the left, five small links are centered, and Primary button sits at the right.

**Transfer:** Preserve the left identity / central links / right action balance with a small number of destinations.

### Primary button

**Use:** Navigation conversion action.

**CSS:** `background: #000000; color: #ffffff; height: 40px; padding: 0px 20px; border-radius: 20px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — DM Mono 400 · 12px/14px

**Observed:** A compact solid capsule rather than a dominant large button. The institutional variant uses charcoal, a 500px radius and 10px 16px padding with 14px medium grotesk text.

**Transfer:** Keep the solid treatment in light or translucent navigation; use Glass button directly on dark photographic fields.

### Glass button

**Use:** Opening exploration, story viewing and the atmospheric closing action.

**CSS:** `background: rgba(255, 255, 255, 0.3); color: #ffffff; height: 40px; padding: 0px 20px; border-radius: 20px; backdrop-filter: blur(1.5px); box-shadow: rgba(255, 255, 255, 0.4) 0px 2px 2px 0px inset, rgba(255, 255, 255, 0.4) 0px -2px 2px 0px inset; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `button` — DM Mono 400 · 12px/14px

**Observed:** The inner rim catches the background light. Closing version is 180px wide and 50px high, inserted between the large words rather than placed on a separate row.

### Resource button

**Use:** Secondary links to trust material or deeper product information.

**CSS:** `background: #94b9eb; color: #000000; height: 40px; padding: 0px 20px; border-radius: 20px; display: inline-flex; align-items: center`

**Text style:** `label` — DM Mono 400 · 12px/1.6

**Observed:** Grouped compact blue capsules sit below the lead, not beside the large heading. Smaller exploration variants are 32px or 33px high.

### Proof capsule

**Use:** Compact social proof anchored inside the opening image.

**CSS:** `border: 1px solid #cdd9e5; border-radius: 80px; padding: 10px 40px; display: flex; align-items: center; gap: 20px; overflow: hidden`

**Text style:** `label` — DM Mono 400 · 12px/1.6

**Observed:** A two-line mono introduction at left precedes a horizontal stream of monochrome logos. The 1360px-wide band is about 58px high and leaves the photograph visible through it.

**Transfer:** Use substantiated proof and real identities; when logos are unavailable, maintain the outlined capsule with short verified proof labels.

### Section marker

**Use:** Introduce a new editorial chapter without a heavy header block.

**CSS:** `border-top: 1px solid #cdd9e5; padding-top: 10px; display: flex; gap: 10px; align-items: center`

**Text style:** `label` — DM Mono 400 · 12px/1.6

**Observed:** Tiny powder-blue dot followed by mixed-case mono text. The rule spans the full content width above a label row about 30px high; inside dark story cards the dot and rule turn white.

### Chapter accordion

**Use:** Show related capabilities as a compact editorial spread.

**CSS:** `height: 480px; border-radius: 20px; overflow: hidden; color: #ffffff; background: #ba484f; display: flex`

**Text style:** `heading` — Crimson Pro Variable 400 · 45px/1.1 · tracking -1px

**Observed:** One 960px expanded chapter is paired with two 200px spines. Each has a mono chapter marker and top rule; the expanded chapter has title, supporting claim, bottom description and detail link, plus thin outlined subtopic tiles. Collapsed 52px titles turn vertically.

**Transfer:** Use the same broad-panel / narrow-spine relationship for a small set of meaningful stages or capabilities.

### Photo story accordion

**Use:** Customer proof and use-case stories.

**CSS:** `height: 480px; background: #000000; color: #ffffff; border-radius: 20px; overflow: hidden; position: relative`

**Text style:** `spine-title` — Crimson Pro Variable 400 · 52px/1 · tracking -1px

**Observed:** Image fills the rounded panel behind Photo veil. A mono indexed marker and rule sit above a large title. The expanded use-case panel is 560px wide with four 200px neighbors; the testimonial version is 960px wide with two narrow neighbors, using 45px names, a large opening quotation mark and 30px quote text.

**Transfer:** Use real-world activity or portrait imagery; preserve vertical neighboring titles and bottom metadata rather than converting to equal cards.

### Closing navigation

**Use:** Utility navigation integrated into the atmospheric ending.

**CSS:** `display: flex; align-items: flex-start; gap: 10px; padding: 10px 10px 0px`

**Text style:** `label` — DM Mono 400 · 12px/1.6

**Observed:** Ruled groups arrange product links and story links in paired label/list columns, followed by a narrow company-links group and a wider muted serif description. Small filled dots mark groups; greater-than glyphs lead child links. Low-opacity identity artwork and legal links form the last row.

**Transfer:** Keep the large closing promise visually separate from the dense utility row while sharing one continuous background.

### Opening row

**Only for:** recruitment and opportunity listings

**Use:** Scannable roles, programs or other opportunities.

**CSS:** `display: flex; justify-content: space-between; align-items: center; height: 80px; padding: 0px 10px 40px; overflow: hidden`

**Text style:** `heading-sm` — Crimson Pro Variable 400 · 36px/1.1 · tracking -1px

**Observed:** Title takes half the row, mono location and work format occupy the next quarter, and a right-aligned underlined action occupies the final quarter. Rows have 20px gaps beneath mono category labels.

**States:** Declared: hover on the apply link keeps color #000 and adds underline with currentcolor; focus-visible not specified.

**Transfer:** Retain the typographic table structure instead of turning each opening into a raised card.

## Imagery and graphics

### Cinematic work scene

**Use:** Default opening and selected use-case stories.

**Observed:** A close view of gloved hands working with electronics fills the opening; cool teal-blue clothing and black equipment dominate. Subjects are cropped at human working scale rather than posed as generic corporate stock. The photograph occupies nearly the entire first screen and remains visible under both columns of white type.

**Transfer:** Choose a close, credible scene of the new product's users doing consequential work. Without motion footage, use one excellent still with dark negative space behind the explanation; do not substitute a decorative dashboard.

### Spectral branching diagram

**Use:** Signature visualization accompanying the numbered benefit chapter.

**Observed:** A wide 816px by 480px field with 40px corners blends wine-red upper edges, an indigo middle and midnight lower center. Thin white lines cross a bright circular node; four faint dashed curves branch toward outlined endpoint circles. Diagram detail is sparse against the large color field.

**Transfer:** Represent the product's transformation with a small node-and-path system rather than literal interface details. The minimum version is a single white node with one horizontal path and four gently diverging curves.

**Build:** Use the Spectral atmosphere on a clipped 816px by 480px panel. Overlay an SVG with a 1px white horizontal line across the middle, a small arrowhead at its right, and a filled 40px circle near center. Draw four cubic paths from the node toward upper and lower right endpoints, with 1px rgba(255,255,255,0.4) strokes and a 3px dash pattern. Add 30px dashed endpoint circles. Keep the drawing transparent so the soft field stays dominant.

### Atmospheric closing field

**Use:** Signature closing artwork on every page type; also the recruitment title field.

**Observed:** A huge diagonal red-to-indigo wash fades into nearly black navy. In the ending, white serif words and a glass action float high above fine navigation, then a very large, low-contrast wordmark sits at bottom right with a separate symbol at bottom left.

**Transfer:** Recreate the broad light field, monumental promise and faint silhouette using the new product identity. Use editable vector or text artwork, not a small standard footer logo.

**Build:** Layer two oversize radial ellipses over a navy-to-near-black base: wine red centered beyond the upper-left edge and indigo extending diagonally toward the lower-left. Blur the colored layers by 80px to 120px; each should cover well over half the width. Add an SVG fractalNoise layer at approximately 0.02 opacity for fine, non-grainy texture. Lay the new wordmark above the field at 0.1 opacity, about 502px wide and 100px high at desktop, aligned to the lower right; keep its separate symbol at lower left. Text and controls remain sharp.

### Photographic evidence panels

**Use:** Customer stories, testimonials and recruitment editorial.

**Observed:** Real laboratories, industrial environments, seated interview portraits and a working whiteboard scene fill horizontal rounded panels. Color is natural but darkened, with white typography laid directly over the image. The main subject stays large; the image is not framed as a small thumbnail.

**Transfer:** Photograph users and environments with specific tools and context. Keep faces and working gestures visible, using a directional veil for text rather than a thick opaque caption block.

### Portrait and documentary pairs

**Only for:** institutional company pages

**Use:** People and community chapters.

**Observed:** Square head-and-shoulders portraits use soft warm-neutral backgrounds, natural light and 4px corners. Names sit below in 40px Garamond with gray grotesk captions. Community imagery is a side-by-side pair of approximately 486px by 322px photographs: a seated discussion and an informal group portrait, retaining natural warm and teal ambient color.

**Transfer:** Use honest, consistent portraits and documentary moments; keep the restrained two-column editorial framing rather than heavily tinting the people.

### Icons

**Observed:** Navigation relies mainly on text. Tiny circular section dots, mono numerals and greater-than glyphs act as wayfinding; small SVG markers are about 8px. Larger symbols chiefly belong to trust badges and the identity.

**Transfer:** Prefer a dot, a number or a simple arrow over a generic icon in every feature. Keep certification marks visually distinct from ordinary interface icons.

## Section recipes

How recurring sections are built.

### First screen: Cinematic editorial opening

**Observed:** An 810px full-bleed dark working scene sits behind a fixed Floating navigation, inset 40px horizontally and 20px from the top. Starting below it with 120px top padding, two columns separated by 80px share the stage: a two-line 130px white serif promise fills most of the left column, while a 640px-wide 18px/24px explanation and Glass button occupy the right, aligned around the upper-middle of the title. The photographic subject crosses the center and lower half, larger than either text block. Proof capsule spans almost the full width near the bottom with 30px breathing room beneath. Within the first 900px, the complete headline, explanation, action, scene and proof strip are visible; only the beginning of the pale reading area follows. The first major reading heading falls below the fold.

**Transfer:** Choose two short complementary phrases and a credible full-bleed work photograph with usable dark negative space. If no footage exists, a strong still preserves the composition. Institutional company content opens instead with a centered 64px Garamond title and small dark pill in a 508px warm-paper band. Recruitment content opens with a broad spectral field, a large left title, mono lead-in and short right-hand explanation, followed by a pale section with 40px rounded top corners.

**Avoid:** Do not replace the photographic stage with a centered software screenshot, enormous filled CTA or a generic glowing orb. Do not put all the opening copy into a single centered stack at desktop.

**Text style:** `display` — Crimson Pro Variable 400 · 130px/1.1 · tracking -4px

### Ruled heading pair

**Observed:** Section marker sits above an asymmetric heading/support row. The 80px serif heading takes the broad left area; 18px/24px support sits in the narrower right area with an 80px gap, often aligned toward the bottom of the title. Major chapters are separated by 120px, while 40px separates a lead from its media.

**Transfer:** Use a short contextual marker, a benefit-led two- or three-line heading and one concrete explanatory paragraph. Change the narrative order to fit the new product without changing the editorial hierarchy.

**Text style:** `heading-lg` — Crimson Pro Variable 400 · 80px/1.1 · tracking -0.025em

### Numbered benefit and diagram

**Observed:** A 480px-high composition pairs three numbered benefit headings on the left with Spectral branching diagram on the right. Mono numbers align in a narrow gutter; 45px serif titles occupy the main left text area. The expanded benefit adds 18px explanatory copy and simple bullets, separated by 10px gaps.

**Transfer:** Choose a few genuinely distinct outcomes and connect them to a sparse transformation diagram. Keep one explanation visually expanded so the composition retains focus.

**Text style:** `heading` — Crimson Pro Variable 400 · 45px/1.1 · tracking -1px

### Chapter spine spread

**Observed:** Chapter accordion forms a continuous 1360px row with one broad 960px chapter and two 200px vertical spines, all 480px high. Color differentiates the stages, while mono numbering, white rules and thin outlined subtopic tiles provide structure.

**Transfer:** Organize a product family, workflow or capability story into broad-and-narrow editorial panels; keep the vertical title device even when the subject changes.

### Photographic proof spread

**Observed:** Photo story accordion uses a broad active story beside slim 200px neighboring stories, all 480px tall. Use-case stories put a 52px title near the top and a short result near the bottom. Testimonials use 45px names, a large quote mark and 30px quotation alongside the visible person.

**Transfer:** Use a small number of substantiated stories with distinct scenes and clearly credited voices. One dominant panel prevents the section from becoming a uniform testimonial grid.

### Open numbered implementation

**Observed:** A large heading pair is followed by a spacious two-column arrangement of numbered 45px service headings on Blue paper. Rows have substantial breathing room rather than visible enclosing tiles.

**Transfer:** Use for the human support or operational work surrounding a product; show distinct steps or commitments without decorative icons.

### Assurance chapter

**Observed:** A three-line 80px lead has small Resource buttons beneath it and serif support in a narrow right column. Below, ruled assurance rows combine mono numbers, 36px headings and 18px explanations. Technical certifications are grouped as restrained monochrome marks and mono labels.

**Transfer:** Explain ownership, protection and accountability with plain claims and linked details; use only verifiable trust proof.

**Text style:** `heading-sm` — Crimson Pro Variable 400 · 36px/1.1 · tracking -1px

### Monumental atmospheric ending

**Observed:** A full-width Spectral atmosphere carries a large white closing line in the display recipe, with the 180px by 50px Glass button embedded between its phrases. The closing statement remains visually high while Closing navigation gathers near the base. Navigation groups have fine top rules, muted mono text and a small 14px serif description. A low-opacity oversized wordmark and separate symbol finish above the legal row; 40px top corners soften the field's entry.

**Transfer:** Always retain the large atmospheric closing statement and faint identity artwork, adapting the words and identity to the new product. The field can support a scroll-held statement, but its length should serve the content rather than introduce empty space.

**Text style:** `display` — Crimson Pro Variable 400 · 130px/1.1 · tracking -4px

### Institutional editorial sequence

**Only for:** institutional company pages

**Observed:** Chalk sections use a centered 992px inner width, 80px vertical chapter padding and 48px Garamond headings. A split mission statement leads into Portrait and documentary pairs, a three-column partner grid and documentary photographs. The mission statement has a slim warm-red vertical accent. A centered 358px warm-paper conversion band uses two lines of 48px serif and a compact dark action before the shared atmospheric ending.

**Transfer:** Use for a company narrative, credibility or people page; preserve the smaller Garamond/grotesk hierarchy, paired photography and warm bands without importing this quieter opening into an ordinary product landing page.

**Text style:** `institutional-heading` — EB Garamond 400 · 48px/1 · tracking -0.01em

### Recruitment editorial and listings

**Only for:** recruitment and opportunity pages

**Observed:** The spectral opening flows into split 80px statements and compact bold serif subheads with 18px explanations. Full-width 1360px by 480px portrait and editorial photo panels separate culture content from opportunity listings. The listings use Section marker category labels and Opening row entries, followed by a direct email invitation before the shared ending.

**Transfer:** Balance the purpose of the work with concrete working conditions, human testimony and an easily scanned opportunity list.

## Page flow

**Storyline:** Promise and real-world context → outcomes and capability chapters → evidence and operational reassurance → renewed invitation → atmospheric brand ending.

### Explain a complex enterprise product and make a high-trust conversion feel earned

1. **Promise** — Cinematic editorial opening with a two-part statement, explanatory copy and proof capsule.
2. **Outcomes** — Ruled heading pair followed by numbered benefits and an abstract branching diagram.
3. **Capability chapters** — Colored chapter spines connect stages of the offering.
4. **Social proof** — Photographic story accordion demonstrates different working contexts.
5. **Implementation reassurance** — Open numbered headings explain the work around adoption.
6. **Objection handling** — Assurance chapter links to detailed trust resources and technical proof.
7. **Human proof** — Portrait testimonial accordion gives named voices the largest role.
8. **Closing call** — A centered large question and then the shared atmospheric statement with embedded action and utility navigation.

**Transfer:** Choose the proof and reassurance a new audience needs, retaining the contrast of pale editorial chapters, colored spines and dark real-world stories rather than copying a fixed section sequence.

### Establish the people, purpose and institutional credibility behind an organization

1. **Orientation** — Centered Garamond title and small dark action on warm paper.
2. **Purpose** — Editorial split statement with compact grotesk explanation.
3. **Human credibility** — Large paired square portraits with names and background captions.
4. **Institutional proof** — Low-contrast partner-logo tile grid.
5. **Community proof** — Documentary photograph pair under a centered serif statement.
6. **Closing call** — Warm centered invitation followed by the same monumental atmospheric ending.

**Transfer:** Use the restrained institutional variant for an organization story, keeping people and documentary content more prominent than product features.

### Connect meaningful work with concrete opportunities to participate

1. **Purpose** — Spectral title field followed by a rounded pale reading area.
2. **Motivation** — Large split statements explain the work and why now.
3. **Human proof** — Wide portrait quote panel makes an employee voice tangible.
4. **Working experience** — Two columns of specific culture and benefit statements.
5. **Editorial proof** — Wide documentary story image with oversized white serif title.
6. **Opportunity** — Invitation, category markers, typographic opening rows and a direct contact route.
7. **Closing call** — Shared atmospheric ending with the embedded action and quiet oversized identity.

**Transfer:** Adapt to recruiting, fellowship or partner opportunities by replacing culture claims with specific working realities and the list with actionable openings.

## Writing

Ambitious and intellectually serious, but grounded in people doing difficult work. Product promises describe decisions, outcomes and collaboration rather than magic or autonomous spectacle.

**Do not copy:** Do not reuse Ankar's identity, customer logos, named people, quotes, proprietary imagery, certifications, numerical proof or claims. All source examples illustrate syntax and tone only; replace them with verified facts and original assets.

- **Addressing the reader:** Use your and you for the reader's work; use we for organizational commitments. Introduce the product by its name and then describe what teams can do with it.
- **Rhythm:** Very short hero phrases contrast with measured explanatory paragraphs. Headings usually carry one thought in 3–10 words; body paragraphs use concrete verbs and may pair a broad proposition with a practical consequence. Actions stay brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A familiar idea followed by a concise reframing, with punctuation supplying the hinge. | 2–5 words | “Invention, reinvented.” |
| Section lead | Name an ambitious outcome or connect the starting question to the finished result. | 3–10 words | “Unlock breakthrough innovation.”<br>“From first question to protected invention.” |
| Capability heading | A concrete verb plus the object of the work. | 3–7 words | “Back the right ideas”<br>“See the landscape before choosing a direction” |
| Reassurance | A direct ownership or operational commitment, followed by its meaning in practice. | 4–8 words for the heading | “Your data stays yours”<br>“A platform, implemented with you.” |
| Primary action | Literal verb plus destination or conversation; no clever substitute for the action. | 3–6 words | “Book a Demo”<br>“Explore The Platform”<br>“Visit The Trust Center” |
| Recruitment invitation | Offer ownership and difficulty as a meaningful opportunity. | One concise sentence | “Built by people who like hard problems”<br>“You’ll own meaningful problems, not small pieces of someone else’s roadmap.” |

**Words and phrasing to use:** work; teams; knowledge; stronger ideas; connect; protect; built for; with you; what comes next; meaningful problems

**Avoid:** magic; effortless everything; crush it; 10x your life; AI wizardry; revolutionary!!!

**Rules:**

- Make the headline aspirational and the supporting paragraph operational.
- Pair broad capability claims with a real workflow, constraint or result.
- Use direct reader ownership language for trust and implementation.
- Let named human voices provide warmth; keep buttons and metadata factual.
- Use sentence case for most labels; reserve capitals for actual technical standards.

## Do's and Don'ts

### Do

- Keep display serif at 130px/1.1 and weight 400 on desktop.
- Use 40px side gutters around a 1360px content region at a 1440px viewport.
- Keep 12px mono labels distinct from 18px/24px serif explanations.
- Use 120px intervals between major pale editorial chapters.
- Keep one broad panel beside 200px vertical spines in the 480px story spreads.
- Use 20px action and story-card radii, reserving 40px for large diagram or section edges.
- Leave the underlying image visible through 30% white glass actions.
- Finish with an atmospheric statement and identity silhouette at 0.1 opacity.

### Don't

- Do not make the 80px headings bold; it destroys the bookish hierarchy.
- Do not turn the pale reading areas into a grid of elevated white SaaS cards.
- Do not apply the blue resource-button fill to every conversion action; navigation stays black and media actions stay glass.
- Do not spread wine red across body copy or all section backgrounds; concentrate it into chapter and atmosphere fields.
- Do not replace the tiny mono navigation with 16px semibold grotesk navigation.
- Do not add heavy external shadows to media panels; the characteristic highlight is the glass button's inset rim.
- Do not make every story an equal thumbnail card; preserve the broad-panel and narrow-spine contrast.
- Do not use warm institutional paper and 64px centered Garamond as the default product opening.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains fixed above the page.
- The closing statement uses a sticky wrapper within the long atmospheric field.
- Chapter and photo-story groups have expanded and collapsed panel configurations.
- Recruitment apply links declare a hover underline while retaining black text.

**Transfer:**

- Keep the navigation backing translucent as content passes beneath it.
- If implementing panel expansion, keep the 480px stage stable and let panel width and title orientation carry the change.
- A scroll-held closing statement should stay readable over one continuous atmosphere rather than reveal an empty intermediate screen.

**Unknown:**

- Expansion trigger, duration and easing are not established.
- No action transition timing or complete focus-visible treatment is established.
- Background video playback and other on-scroll timing are not specified.

### Responsive

**Observed:**

- Styles define width boundaries around 810px, 1200px and 1440px, with an additional institutional boundary around 940px.

**Transfer:**

- On narrow layouts, preserve the hierarchy by stacking explanation beneath the opening statement and keeping the work scene full bleed.
- Convert broad-and-narrow story spreads into readable sequential panels or a horizontally navigable set; do not squeeze 52px vertical titles into unreadable slivers.
- Keep the closing promise, glass action and faint identity artwork together, allowing the words and action to wrap rather than overflow.

**Unknown:**

- Mobile font sizes, gutter values, navigation substitution and panel interaction were not established. The narrow-layout guidance is a design recommendation, not a measured breakpoint recipe.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
