# Gradient Labs — human systems in miniature

## Overview

Warm editorial restraint meets a miniature architectural world. Cream and stone canvases alternate with confident black chapters, pale blue fields and concentrated orange, while regular grotesk headings sit beside delicate italic serif labels. Fine-lined isometric illustration, cropped product interfaces and personable proof make complex operational software feel tangible, with spacious chapters and compact information inside cards.

### Essentials

- Headlines feel conversational rather than corporate: regular-weight Linear Sans at 56px/1.04 with -0.05em tracking for the main promise, 48px/1.1 with -0.04em for chapters; italic 20px/1.35 serif labels provide the counterpoint.
- The opening is an inhabited landscape, not a framed dashboard: a 720px-wide text area floats above cream isometric architecture that spills past both edges; tiny people and task labels populate the lower and right portions of a 762px stage. Recreate this spatial metaphor even when only simple SVG blocks are available.
- Actions are compact capsules with arrows, not rectangles: orange with black text on cream, black with white text on colored bands; 52px height, 16px 28px padding, 100px radius, and 16px regular text. The navigation action shrinks to 36px.
- Color arrives by chapter: cream, stone and black occupy most of the long page; pale blue backs a substantial explanation or proof chapter, orange concentrates in actions, a 234deg integration backdrop and a 499px closing band. Mint belongs to a scoped capability variant, not every section.
- Illustrations and interfaces share a constructed world: hairline cube geometry, off-white faces, muted shaded sides, small orange and blue accents; white 20px-radius cards frame sharp, legible interface fragments rather than floating neon windows.
- Editorial chapter markings and a spatial closing call are signature devices: a 1px horizontal rule precedes a square marker and light italic label, then a 16px gap to the heading; the orange closing call pairs a 56px outcome line with a small isometric pedestal and long diagonal room lines. Use a simple outlined block sculpture as the fallback.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Working orange | `#ff8933` | `--color-orange` | background, accent, action, link | Primary light-canvas actions, conversion bands and one endpoint of the integration gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Apricot | `#ffa666` | `--color-peach` | background, accent | Announcement strip, lighter gradient endpoint and library category badges. |
| Air blue | `#bbe2ea` | `--color-blue-field` | background | Large explanatory and testimonial chapters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, action | Headlines, linework, dark chapters, footer and black actions. |
| Translucent charcoal | `#1f1f1f` | `--color-review-panel` | surface | Visible white at 12% over black in the independent-evaluation panel. |
| Translucent story grey | `#242424` | `--color-story-pill` | surface | Visible white at 14% over black behind small customer-story links. |
| Olive charcoal | `#2b2b28` | `--color-dark-card` | surface, text | Trust and security cards on black, and some editorial body text. |
| Charcoal text | `#383835` | `--color-body` | text, surface | Body copy on light surfaces and circular icon wells in dark cards. |
| Soft charcoal | `#3a3a3a` | `--color-review-action` | action | Independent-evaluation action pills on the dark closing panel. |
| Warm grey | `#67675f` | `--color-muted` | text | Secondary support copy and metadata. |
| Stone field | `#ede9de` | `--color-stone` | background, border, text | Workflow and library bands; faint card and tile edges; muted light text on dark. |
| Warm paper | `#faf7f0` | `--color-canvas` | background, surface | Default canvas and navigation; also small conversational quote cards. |
| Card white | `#ffffff` | `--color-white` | surface, text | Feature cards and inverse text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| categorized libraries | Category yellow | `#ffed77` | `--color-yellow` | accent | Small category badges paired with peach and mint. |
| outreach-focused product chapters and categorized libraries | Capability mint | `#7acba7` | `--color-mint` | background, accent | Capability chapter variant and small category badges. |
| technical product demonstrations | Demo black | `#0b0b0b` | `--color-demo-black` | surface | Dark gridded media stage. |
| technical product launch chapters | Technical card charcoal | `#1a1a1a` | `--color-technical-card` | surface | Visible white at 10% over black in the technical feature grid. |
| customer-story indexes | Proof green | `#378032` | `--color-proof-green` | text | Compact metric values in customer-story cards. |

## Typography

- **Linear Sans** — All marketing headings, navigation, buttons, compact labels and quotations. Soft, compact grotesk with open round forms; regular cuts and strongly tightened display spacing. If unavailable, use **DM Sans**. Use 400 for the main hierarchy; retain the tight tracking and tune wrapping to the same widths. Font stack: "Linear Sans", "DM Sans", Arial, sans-serif.
- **Inter** — Explanatory prose, feature descriptions and announcement text. Neutral, highly readable sans with a slightly more utilitarian texture than the headings. Font stack: "Inter", Arial, sans-serif.
- **Tiempos Headline** — Light italic chapter labels and compact metric descriptors. Fine editorial serif italic with lively contrast, used as a small accent rather than a competing display face. If unavailable, use **Newsreader**. Use light 300 italic, preserving its modest scale beside the grotesk. Font stack: "Tiempos Headline", "Newsreader", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Linear Sans | 400 | 56px | 1.04 | -0.05em, features "liga" 0 | Main marketing promise and orange closing headline. |
| heading | Linear Sans | 400 | 48px | 1.1 | -0.04em | Chapter headings, index titles, centered calls and large proof values. |
| heading-small | Linear Sans | 400 | 32px | 1.2 | -0.04em | Lead feature card, featured article and process-step title. |
| card-heading | Linear Sans | 400 | 24px | 1.2 | -0.04em | Feature, trust and catalog card headings. |
| eyebrow | Tiempos Headline | 300 italic | 20px | 1.35 | normal | Sentence-case chapter labels and featured-content labels. |
| lead | Inter | 400 | 20px | 1.45 | -0.01em | Longer hero support and prominent editorial paragraphs. |
| body | Inter | 400 | 16px | 1.45 | -0.01em | Default hero support, feature lead support and stat captions. |
| action | Linear Sans | 400 | 16px | 1.25 | -0.02em, features "dlig" | Main 52px pill actions. |
| body-small | Inter | 400 | 14px | 1.4 | -0.01em | Feature-card descriptions and compact supporting prose. |
| navigation | Linear Sans | 400 | 14px | 1.45 | -0.018em | Header navigation and footer links. |
| action-small | Linear Sans | 400 | 14px | 1.25 | -0.02em, features "dlig" | 36px navigation action and small article-index action. |
| announcement | Inter | 500 | 13px | 1.25 | -0.03em | One-line announcement strip. |
| story-link | Linear Sans | 400 | 11px | 1.25 | -0.02em, features "dlig" | Tiny story capsules beneath customer logos. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical product launches | launch-title | Linear Sans | 400 | 72px | 1 | -0.05em, features "liga" 0 | Centered single-name product launch title. |
| customer-story indexes | metric-small | Linear Sans | 400 | 18px | 1.25 | -0.04em | Compact green result values in customer-story cards. |
| customer-story indexes | metric-caption | Tiempos Headline | 300 italic | 18px | 1.35 | normal | Inline italic description following the compact green number. |
| customer quote walls | quote | Linear Sans | 400 | 16px | 1.25 | -0.03em | Conversational and business quotations. |
| categorized libraries | filter | Linear Sans | 400 | 14px | 1.4 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Filter-pill text. |
| categorized libraries | tag | Linear Sans | 400 | 12px | 1.4 | -0.03em | Colored category labels. |

**Notes:**

- Regular 400 is the hierarchy's default, including large headings and action labels; size, negative tracking and composition do the work instead of boldness.
- Tracking tightens from -0.01em in Inter prose to -0.04em at 24–48px and -0.05em at 56–72px. Do not apply display tracking to paragraphs.
- Serif is reserved for small editorial labels and metric descriptions. Labels retain sentence case; headlines do not become italic.
- Use restrained heading widths: 720px for the opening promise, often 840px for left-aligned chapter headings, and about 720px for centered calls.

## Layout

**Density:** Airy chapters with compact cards: broad section padding surrounds tightly grouped labels, headings and interface details.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight title-to-description gaps, action icon gaps and small controls. |
| 16px | Eyebrow-to-heading gap and tight card-grid gutters. |
| 20px | Customer-story grid and quote-wall gutters. |
| 24px | Hero stack gaps, feature-grid gutters and small card insets. |
| 32px | Primary card padding, support-to-action spacing and medium content separation. |
| 48px | Footer navigation column gutters. |
| 64px | Desktop section side padding and secondary block separation. |
| 72px | Compact logo-band vertical padding and navigation height. |
| 80px | Chapter heading-to-main-content spacing. |
| 128px | Default major-section top and bottom padding. |
| 184px | Vertical padding in the restrained centered closing variant. |

### Containers and grids

- **main-container**: max width 1200px · side padding 64px. Centered content spine; at 1440px the main text and cards begin 120px from the edges. Full-bleed bands wrap this spine.
- **outer-wrapper**: max width 1400px · side padding 64px. Outer section wrapper, containing the narrower main spine and oversized decorative geometry.
- **feature-grid**: 3 columns · gap 24px. Three 384px-wide image-led cards below a full-width feature lead.
- **trust-grid**: 4 columns · gap 16px. Four columns of paired 288px trust cards on a black band.
- **logo-grid**: 5 columns · gap 32px. Five columns of centered white customer marks on black; three rows with 24px row gaps.
- **centered-copy**: max width 720px. Centered product and closing arguments, narrower than the demonstration beneath.
- **catalog-grid** (only for categorized libraries): 2 columns · gap 16px. Two 592px columns of compact 300px-tall use-case cards.
- **story-grid** (only for customer-story indexes): 3 columns · gap 20px. Three columns of customer-story cards, approximately 387px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 100px |
|  | cards | 20px |
|  | media-backing | 24px |
|  | logo-tiles | 16px |
| technical product launch chapters | technical-cards | 12px |
| customer quote walls | quote-bubble | 20px |
| categorized libraries | select | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | interface-halo | `rgba(15, 23, 41, 0.06) 0px 0px 0px 1px, rgba(15, 23, 41, 0.04) 0px 0px 0px 8px` | Soft frame around product images, not general marketing cards. |
| categorized libraries | filter-control | `rgba(18, 18, 18, 0.08) 0px 2px 4px 0px, rgba(18, 18, 18, 0.12) 0px 1px 1px 0px, rgba(18, 18, 18, 0.04) 0px 0px 0px 1px` | Raised filter pills and select fields. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #faf7f0; color: #000000`

**Observed:** Matte, nearly textureless warmth; the architectural illustration shares the same backing.

**Transfer:** Use as uninterrupted negative space rather than a texture layer.

#### Stone band · level 0

**Use:** Workflow explanations and catalog chapters.

**CSS:** `background: #ede9de`

**Observed:** A slightly deeper neutral than the main canvas, allowing white cards to separate without drop shadows.

**Transfer:** Group dense material into a stone chapter.

#### Black band · level 0

**Use:** Logo proof, quantified results, trust chapters and the footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Hard full-width switches, not floating dark cards on cream.

**Transfer:** Create a decisive contrast chapter where proof needs weight.

#### Blue field · level 0

**Use:** Broad feature explanation or human testimonial chapter.

**CSS:** `background: #bbe2ea; padding: 128px 64px`

**Observed:** A substantial pastel field with white cards and black typography.

**Transfer:** Reserve a whole chapter for the blue rather than dispersing it into every component.

#### Orange call band · level 0

**Use:** Signature conversion chapter.

**CSS:** `background: #ff8933; padding: 128px 64px; overflow: hidden`

**Observed:** 499px-tall desktop band, with text left and architectural artwork extending beyond the right and top.

**Transfer:** Carry a concise outcome and one black action alongside the spatial motif.

#### White card · level 1

**Use:** Feature, story and catalog content.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden`

**Observed:** Flat and clean; image-led cards have a white 2px edge rather than a visible grey outline or heavy shadow.

**Transfer:** Let the surrounding chapter color separate cards.

#### Integration stage · level 1

**Use:** Rows of ecosystem tiles.

**CSS:** `background: linear-gradient(234deg, #ffa666 0%, #ff8933 100%); border-radius: 16px; overflow: hidden; padding: 64px 0px`

**Observed:** Two rows of white logo tiles are clipped at the stage edges over faint cube linework.

**Transfer:** Use relevant ecosystem marks or simple labeled system tiles.

#### Evaluation panel · level 1

**Use:** Independent-evaluation closing device.

**CSS:** `background: rgba(255, 255, 255, 0.12); border-radius: 20px; max-width: 1200px`

**Observed:** A 429px panel on black with centered copy, three charcoal actions and very subtle architectural lines.

**Transfer:** Offer a genuine way to evaluate the new product: compare tools, inspect documentation or test a sample.

#### Mint capability band · level 0

**Only for:** outreach-focused product chapters

**Use:** Alternate capability treatment.

**CSS:** `background: #7acba7; padding: 128px 64px`

**Observed:** Two columns of white icon-led cards.

**Transfer:** Use instead of, not mixed into, the blue feature chapter.

#### Technical feature panel · level 1

**Only for:** technical product launch chapters

**Use:** Compact dark feature grid.

**CSS:** `background: rgba(255, 255, 255, 0.1); border-radius: 12px; overflow: hidden`

**Observed:** Six cards in a three-column, two-row grid on black; text above a tightly cropped demonstration.

**Transfer:** Keep technical UI colors within the media, not the surrounding marketing palette.

#### Dark demonstration stage · level 1

**Only for:** technical product demonstrations

**Use:** Wide technical media frame.

**CSS:** `background: #0b0b0b; border-radius: 20px; overflow: hidden; max-width: 1200px`

**Observed:** A 1200px by 600px stage with faint rectilinear grid and cube corners, holding a smaller central interface.

**Transfer:** Frame one meaningful task rather than a full application shell.

## Components

### Navigation

**Use:** Persistent orientation and compact conversion.

**CSS:** `background: #faf7f0; height: 72px; padding: 28px 64px; backdrop-filter: blur(8px); display: flex; align-items: center; justify-content: center; gap: 20px`

**Text style:** `navigation` — Linear Sans 400 · 14px/1.45 · tracking -0.018em

**Observed:** Sticky outer wrapper. Inside a 1200px spine, a 165px by 25px wordmark sits left, six short text links occupy the center and Compact action sits right. Links use 6px 12px padding and no painted background.

**Transfer:** Keep the small wordmark and restrained link density; retain the right-hand conversion capsule.

### Orange action

**Use:** Default prominent action on cream.

**CSS:** `background: #ff8933; color: #000000; border-radius: 100px; padding: 16px 28px; height: 52px; display: inline-flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `action` — Linear Sans 400 · 16px/1.25 · tracking -0.02em

**Observed:** Short label followed by a small right arrow; width follows copy rather than a full-width control.

**Transfer:** Name the next concrete step.

### Black action

**Use:** Conversion on orange or blue and other bright fields.

**CSS:** `background: #000000; color: #ffffff; border-radius: 100px; padding: 16px 28px; height: 52px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — Linear Sans 400 · 16px/1.25 · tracking -0.02em

**Observed:** Same capsule construction and trailing arrow as Orange action; high contrast against colored chapters.

### Compact action

**Use:** Navigation conversion.

**CSS:** `background: #000000; color: #ffffff; border-radius: 100px; padding: 9px 16px; height: 36px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action-small` — Linear Sans 400 · 14px/1.25 · tracking -0.02em

**Observed:** Smaller capsule at the right of the header; a neutral translucent small variant appears beneath featured editorial content.

### Feature card

**Use:** Image-led capability explanation.

**CSS:** `background: #ffffff; border-radius: 20px; overflow: hidden; display: flex; flex-direction: column; align-items: center; border: 2px solid #ffffff`

**Text style:** `card-heading` — Linear Sans 400 · 24px/1.2 · tracking -0.04em

**Observed:** Default card is 384px wide and 474px tall: media fills the upper 310px; title and description use a 24px side inset and 32px bottom inset. A full-width lead variant pairs 32px text on the left with a wider illustrated agent grid on the right.

**Transfer:** Use one focused interface fragment per card, with a one- or two-line title and short explanatory prose.

### Trust card

**Use:** Assurance points on a black chapter.

**CSS:** `background: #2b2b28; color: #ffffff; border-radius: 20px; padding: 32px; display: flex; flex-direction: column; align-items: flex-start; gap: 24px`

**Text style:** `card-heading` — Linear Sans 400 · 24px/1.2 · tracking -0.04em

**Observed:** 288px by 312px default; a 64px circular charcoal icon well precedes the text stack. Title and small body are separated by 8px; cards have little or no elevation.

### Story capsule

**Use:** Small action tucked under a proof logo.

**CSS:** `background: rgba(255, 255, 255, 0.14); color: #ffffff; border-radius: 100px; padding: 3px 8px; height: 20px; display: inline-flex; gap: 4px`

**Text style:** `story-link` — Linear Sans 400 · 11px/1.25 · tracking -0.02em

**Observed:** Centered under selected white marks; tiny trailing arrow, rather than a full-size button competing with the logo.

### Evaluation action

**Use:** Independent evaluation links within Evaluation panel.

**CSS:** `background: #3a3a3a; color: #ffffff; border-radius: 100px; padding: 16px 28px; height: 52px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — Linear Sans 400 · 16px/1.25 · tracking -0.02em

**Observed:** Three centered pills each include a white tool mark before the label.

**Transfer:** Link to useful independent checks rather than repeating the main sales action.

### Footer link

**Use:** Dense but readable grouped navigation on black.

**CSS:** `color: #ffffff; padding: 6px 12px; height: 36px; display: inline-flex; align-items: center`

**Text style:** `navigation` — Linear Sans 400 · 14px/1.45 · tracking -0.018em

**Observed:** Three link columns to the right of a white logo. Small muted group headings distinguish product, proof, company and resource groups. A faint horizontal divider separates links from social marks and copyright.

### Quote bubble

**Only for:** customer quote walls

**Use:** Short end-user quotation.

**CSS:** `background: #faf7f0; color: #000000; border-radius: 20px 20px 20px 4px; padding: 32px 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `quote` — Linear Sans 400 · 16px/1.25 · tracking -0.03em

**Observed:** Short 220px by 224px cream bubbles stack in pairs. Taller 324px by 468px white business quotes sit alongside, with a logo above and a portrait-and-role lockup at the bottom.

**Transfer:** Preserve the informal quote voice and asymmetric corner; use real attributed remarks.

### Story result card

**Only for:** customer-story indexes

**Use:** Proof browsing with a compact quantified result.

**CSS:** `background: #ffffff; border-radius: 20px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `card-heading` — Linear Sans 400 · 24px/1.2 · tracking -0.04em

**Observed:** A monochrome customer mark sits above the outcome title. A fine stone divider precedes a baseline-aligned green 18px metric and 18px light italic description, with a 12px gap. Default card is about 387px by 258px.

**Transfer:** Make the result specific and verifiable, not a generic praise card.

### Filter pill

**Only for:** categorized libraries

**Use:** Compact category filtering.

**CSS:** `background: #ffffff; border-radius: 100px; padding: 0px 16px; height: 32px; box-shadow: rgba(18, 18, 18, 0.08) 0px 2px 4px 0px, rgba(18, 18, 18, 0.12) 0px 1px 1px 0px, rgba(18, 18, 18, 0.04) 0px 0px 0px 1px; display: inline-flex; align-items: center`

**Text style:** `filter` — Linear Sans 400 · 14px/1.4

**Observed:** Pills occupy the left of a horizontal filter bar. On the right, three white 155px by 36px select fields use 10px radii and the same subtle shadow, each with an italic label and rule above. A small clear-filters text action ends the bar.

## Imagery and graphics

### Inhabited isometric architecture

**Use:** Signature opening landscape and smaller closing sculpture.

**Observed:** Cream impossible-looking buildings, tiled bridges and stairs are drawn with thin black outlines and flat olive-grey shaded faces. Tiny people carry parcels or use laptops, with sparse orange clothing and blue props; rounded stone task labels hover near activities. The opening art spills beyond the viewport and occupies most of its lower half, leaving the upper left clear.

**Transfer:** Translate the new product's work into connected stations and small human actions. The minimum equivalent is a clean SVG landscape of connected blocks, two or three figures and meaningful task labels, not stock office photography.

**Build:** Draw SVG cube faces on 30-degree diagonals with vertical uprights; use the paper canvas for top faces, stone for fronts and a darker low-opacity black overlay for side faces. Use 1px black strokes, no blur or glossy shading. Arrange three staggered stations linked by small repeated cube steps across an oversized 2080px-wide artboard. Reserve the upper-left region for live text. Add a few orange and muted blue props; use simple line figures at a much smaller scale than the structures.

### Architectural line field

**Use:** Spatial motif behind integration tiles, dark evaluation and demonstration panels, and the orange closing call.

**Observed:** Fine low-contrast cube outlines and room-like diagonals extend well beyond their panels. The orange closing uses stronger black lines converging near the upper right and a small off-white cube pedestal with one person.

**Transfer:** Repeat this graphic language across the page so the opening has an architectural echo at the end.

**Build:** Use a clipped SVG layer under live content. For closing artwork, draw three 1px black rays from a point near the upper-right quarter: one vertical upward and two at roughly 30 degrees downward, then place a small stacked cube sculpture on the right. For panel backgrounds, tile connected 30-degree cube outlines in rgba(0,0,0,0.06) on orange or rgba(255,255,255,0.05) on charcoal. Keep the text layer above all lines.

### Workflow and interface fragments

**Use:** Main demonstrations, feature-card media and process explanations.

**Observed:** White interface cards with warm neutral backing, tiny status chips and fine connector paths form clear task diagrams. Some are full-width panels; others are tightly cropped to show the relevant control, conversation or validation. Warm halo frames soften selected product images. Dark technical demonstrations use a black gridded room around a smaller central UI.

**Transfer:** Show one task progressing between two or three states. Keep product-specific colors inside the UI, with readable labels, rather than copying a whole app shell.

**Build:** Place three or four white rounded panels on a stone or paper 12px-radius field. Link panels with thin neutral elbow paths and small arrows, then add one orange status emphasis. For dark variants, use Dark demonstration stage with thin grid lines and restrained green/red states only inside the interface.

### Ecosystem tiles

**Use:** Wide integration stage and library opening variant.

**Observed:** Monochrome marks sit in white 16px-radius tiles. Horizontal strips show two rows of 124px by 64px tiles with 16px horizontal and 24px vertical gaps; the library variant uses two vertical columns of larger tiles. Rows clip cleanly at the orange stage boundaries.

**Transfer:** Use relevant partners, compatible systems or plainly labeled categories in the same monochrome tile treatment.

**Build:** Layer two flex rows over Integration stage, repeat the tile set to allow edge clipping, and vary the row's starting offset. Use white tiles with a 1px stone edge and center marks without colored brand backgrounds.

### Human proof media

**Use:** Testimonial carousel and featured customer conversation.

**Observed:** On black, a colorful quote artwork sits left of a short white outcome and white action, below three large stats. Quote artwork includes italic text, horizontal rules and a small attribution. The customer index opens its featured story with a monochrome interview still, centered white customer mark and rounded frame.

**Transfer:** Use genuine interview stills or a typeset quote card with a portrait lockup. Keep photography documentary and subdued so it does not overwhelm the illustration language.

### Icons

**Observed:** Small solid monochrome arrows and pictograms: 9–12px arrows in story and action links, 18–24px feature symbols, and 24px white symbols in 64px circular trust wells. Navigation is mostly text; icons are functional rather than decorative.

**Transfer:** Choose a consistent filled icon family with simple silhouettes. Use tiny trailing right arrows on actions and reserve larger circular wells for trust or capability cards.

## Section recipes

How recurring sections are built.

### First screen: Inhabited landscape opening

**Observed:** A 40px peach announcement strip sits above 72px paper Navigation. The 762px cream hero places a two-line 56px regular headline in a 720px area aligned with the 1200px spine at upper left, followed by a 500px-wide 16px support paragraph and Orange action, separated by 24px. Behind the live copy, a 2080px-wide isometric landscape is centered and clipped by both viewport edges; its main structures grow across the lower half and rise at the right. Back-to-front layers are paper, architecture and figures, floating task labels, then live text and action. Within the first 900px, all hero copy, the action and the populated main landscape are visible; the first black proof band begins at about 874px, while its logo contents lie below the fold.

**Transfer:** Keep the upper-left promise clear and let a new product's connected tasks inhabit the lower/right architecture. Use the simple SVG block-and-figure fallback when custom illustration is unavailable. Product-detail openings can instead center a 56px promise and 20px support above a large video; technical launches center a 72px product name above a collaborative UI. Proof indexes open left-aligned with a 48px title and featured media; libraries pair that title with orange ecosystem tiles.

**Avoid:** Do not replace the landscape with a centered floating dashboard or put the headline over busy illustrated faces. Do not enlarge the text to fill the full screen width.

**Text style:** `display` — Linear Sans 400 · 56px/1.04 · tracking -0.05em

### Ruled chapter heading

**Observed:** A 1px horizontal rule spans the content spine; beneath it a small square marker leads the 20px light italic Eyebrow. A 16px gap introduces a left-aligned 48px Heading. Major sections use 128px vertical padding and usually 80px between the heading block and main media or cards. Black chapters reverse the marking and text.

**Transfer:** Use short functional labels to organize any topic, maintaining the rule/square/italic relationship.

**Text style:** `heading` — Linear Sans 400 · 48px/1.1 · tracking -0.04em

### Interactive workflow chapter

**Observed:** On Stone band, Ruled chapter heading introduces a large white 1200px by 632px, 24px-radius panel. A narrow left list of six task rows uses 18px labels, icons and fine dividers; the selected item has orange emphasis and reveals a short description. A wider right pane shows the associated connected workflow. An Orange action sits below.

**Transfer:** Organize capabilities into task-oriented tabs and show only the active task's meaningful flow; the interaction must clarify the mechanism, not merely swap decorative illustrations.

### Quantified proof and colorful quote

**Observed:** A Black band begins with an italic proof label, then three centered 48px metrics with 16px captions and faint vertical dividers. Below, a carousel pairs a brightly colored quote artwork at left with a concise white result and light action at right; 40px circular arrows sit at the sides and five small pagination dots below.

**Transfer:** Pair a small set of substantiated quantitative outcomes with one human account. Use a designed colored quote card when no interview artwork exists.

### Platform feature chapter

**Observed:** Blue field contains Ruled chapter heading, a full-width White card lead and a three-column Feature card row with 24px gutters. The lead uses 32px text and 16px support on the left; small isometric stations and metrics occupy the right. Each lower card gives most of its height to interface imagery before the 24px heading and compact prose. Black action is centered below.

**Transfer:** Use one broad mechanism and several supporting capabilities, preserving a clear distinction between the wide lead and smaller cards.

### Trust chapter

**Observed:** On Black band, Ruled chapter heading leads into a four-column grid with 16px gutters, two Trust cards per column. Each is a self-contained assurance with an icon well, 24px title and 14px description.

**Transfer:** Replace compliance-specific topics with the new product's concrete reliability, control and safety guarantees.

### Partner and integration chapters

**Observed:** Integration stage follows a 48px ruled heading and 20px support paragraph on paper. A separate stone editorial chapter pairs a 48px heading with two balanced 20px paragraphs and a row of monochrome experience marks; its underlined text link turns orange on hover.

**Transfer:** Distinguish technical compatibility from human delivery expertise; either can occupy the architectural tile language without requiring a specific industry.

### Spatial closing call and footer

**Observed:** Orange call band uses a small square-led italic label, 56px two-line outcome, 32px separation to Black action, and a small right-aligned architectural pedestal with long room diagonals. The default extended close adds Evaluation panel on Black band with 48px centered question, 16px support and three Evaluation actions. The footer itself is spacious black: white logo left, three navigation columns with 48px gutters right, 128px outer vertical breathing room, then a faint rule, social marks left and copyright right. A thin cream legal-utility strip follows. The technical-launch variant closes on paper with centered 48px outcome, 20px support, Orange action and 184px vertical padding before the same black footer.

**Transfer:** Keep the spatial artwork and decisive outcome/action device in the page, adapting its placement to the narrative. Use the paper closing variant only for technical launches. Independent evaluation should offer a real check on suitability rather than an extra sales slogan.

**Text style:** `display` — Linear Sans 400 · 56px/1.04 · tracking -0.05em

### Story index and quote wall

**Only for:** customer-proof pages

**Observed:** A left-aligned ruled 48px title and 16px support open on paper. A featured white split card places a 32px outcome title left and monochrome interview media right; Story result cards follow in three columns. Blue field then holds a wide horizontal quote wall: tall white business cards alternate with paired cream Quote bubbles, clipping at both viewport edges. A black five-column logo band follows.

**Transfer:** Offer both deep case studies and quick human evidence; retain the unusual mixture of tall business quotes and short conversational bubbles.

### Technical launch chapters

**Only for:** technical product launches

**Observed:** Centered 72px product name, 20px italic introduction and 20px support open on paper. A wide collaborative editor image follows with floating colored participant labels. A black chapter uses six Technical feature panels in a three-by-two grid. Subsequent paper sections center 48px headings above 1200px by 600px process and demonstration media.

**Transfer:** Lead with the new tool's collaborative act, then show controls, testing and repeatable improvement in focused demonstrations rather than a generic feature collage.

**Text style:** `launch-title` — Linear Sans 400 · 72px/1 · tracking -0.05em

### Filtered task library

**Only for:** categorized libraries

**Observed:** Paper opening splits a ruled 48px title and 20px support left from an orange ecosystem-tile panel right. Stone band introduces a second 48px heading, Filter pills and three select fields. A wide featured White card pairs a 32px task title and metadata with conversation media; below, two 592px columns of 300px cards carry 24px titles, short descriptions, small yellow/peach/mint category badges and compact channel/category chips.

**Transfer:** Make the library browsable by user task, channel or domain. Keep visual hierarchy above metadata and retain the broad featured example.

## Page flow

**Storyline:** Promise → concrete mechanism → quantified and human proof → capability or task chapters → trust and fit → decisive outcome call → useful navigation.

### Broad marketing landing page that explains an unfamiliar operational product

1. **Promise** — Left-aligned promise above an inhabited architectural landscape.
2. **Social proof** — Black monochrome logo grid with tiny story capsules.
3. **Product demonstration** — Stone workflow tab panel makes the mechanism legible.
4. **Quantified proof** — Three large metrics and a colored testimonial on black.
5. **Capability chapters** — Blue feature cards, orange integration stage, black trust cards and stone delivery explanation.
6. **Closing call** — Orange spatial call, dark independent-evaluation panel, black navigation footer and thin legal utility.

**Transfer:** Alternate explanation and proof so a complex product feels both understandable and dependable; reuse the devices without requiring the same chapter count.

### Focused product-detail page centered on an active task

1. **Promise** — Centered outcome headline and orange action above a large documentary video.
2. **Capability explanation** — Black split section pairs two concise benefits with a product control image.
3. **Process demonstration** — Paper chapter with five step pills and a split text/interface explanation.
4. **Differentiation** — Mint two-column icon cards explain safe, goal-directed behavior.
5. **Related tasks and thinking** — Compact tagged task cards and a featured editorial split card.
6. **Closing call** — Orange architectural call directly into the spacious black footer and legal strip.

**Transfer:** Lead with the pain and the action the product completes, then show setup, safeguards and useful next reading.

### Technical launch for a collaborative software capability

1. **Introduction** — Centered product name and concise support above a collaborative editor scene.
2. **Capability chapters** — Black six-card feature grid with close-up media.
3. **Mechanism** — Paper process diagram explains a repeatable improvement loop.
4. **Product demonstration** — Dark gridded media stage under a centered outcome heading.
5. **Closing call** — Centered paper outcome with orange action, then black footer and legal utility.

**Transfer:** Use the centered launch variant and technical demonstrations while preserving the regular type and paper/black chapter contrast.

### Proof index that helps buyers find comparable successes

1. **Orientation** — Ruled editorial title and compact introduction.
2. **Featured proof** — Split interview story followed by three-column result cards.
3. **Human proof** — Blue quote wall combines business endorsements and end-user reactions.
4. **Social proof** — Black logo grid with selected tiny story links.
5. **Closing call** — Orange spatial conversion band, black footer and legal utility.

**Transfer:** Separate detailed stories, short reactions and recognizable logos so each form of proof has its own pace.

### Browsable task library that turns an abstract platform into concrete possibilities

1. **Orientation** — Split editorial heading and orange ecosystem tile scene.
2. **Discovery controls** — Stone library heading, category pills and labeled dropdown filters.
3. **Featured example** — Wide white task card with conversation media.
4. **Task catalog** — Two-column tagged cards with short practical descriptions and metadata.
5. **Closing call** — Orange architectural conversion band into black footer and legal utility.

**Transfer:** Adapt filters to meaningful product categories and keep task names specific enough to browse without extra explanation.

## Writing

Calmly confident, operationally specific and human. Promises are ambitious but grounded in tasks, safeguards, controls and concrete outcomes rather than futuristic spectacle.

**Do not copy:** Do not reuse Gradient Labs names, logos, proprietary illustrations, customer marks, quotations, metrics or product claims. Source examples illustrate structure and voice only; every new claim and attribution must belong to the new product.

- **Addressing the reader:** Speak directly to teams as you/your; use we for the provider and plain product nouns for the mechanism. Customers and end-users remain people rather than abstract throughput.
- **Rhythm:** Headlines often span 5–12 words and two lines. Support is one or two clear sentences; cards favor a short capability title and one compact explanation. Short contrasts, task verbs and occasional conversational questions interrupt the longer operational descriptions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the category and audience, or contrast an old pain with a new outcome. | 5–12 words | “AI-native customer operations for financial services”<br>“Outbound felt endless. Until now.” |
| Chapter headline | State a capability through an outcome, often using a practical contrast. | 6–12 words | “We handle what others hand off”<br>“Works with your existing stack, from day one” |
| Eyebrow | Short functional topic in sentence case, not an all-caps slogan. | 1–5 words | “End-to-end automation”<br>“Partners in your success” |
| Supporting line | Explain what it does, naming tasks and how they connect. | 15–40 words | “A suite of specialist agents for lending, disputes, and KYC with a platform that runs the operations in between.”<br>“Define the goal: collect a document, verify a transaction, prevent fraud. Choose your channel: text, voice, or both.” |
| Card title | Specific capability or action, not a vague benefit noun. | 2–8 words | “Provably compliant at every step”<br>“Freeze and replace a lost card” |
| Primary action | Concrete low-friction next step. | 3–5 words | “See it in action”<br>“Get a personalised demo” |
| Closing question | Acknowledge fit uncertainty and invite a useful check. | 8–12 words | “Not sure if [Brand] is right for you?” |

**Words and phrasing to use:** from day one; working together; end-to-end; at every step; built for; your team; goal; controls; safe; how it works; case closed

**Avoid:** revolutionary paradigm; unprecedented synergy; magic; supercharge everything; 10x without proof; disrupt the future

**Rules:**

- Tie an ambitious headline to a concrete task, interface or verified proof nearby.
- Use parallel active verbs for task lists; name the object of the work.
- Explain safeguards as part of the capability, not as a legal afterthought.
- Keep eyebrow labels informative and brief; let the headline carry the promise.
- Retain authentic informal language in attributed user quotations rather than polishing every voice into marketing prose.
- Use British spellings where appropriate, such as personalised and specialised.

## Do's and Don'ts

### Do

- Keep the main promise at 56px/1.04, weight 400 and -0.05em tracking.
- Use the 1200px centered spine for live text and cards while artwork can exceed the viewport.
- Pair a 20px light italic label with a square marker and a 1px chapter rule.
- Keep primary actions at 52px with 100px radii; use the 36px compact variant in the header.
- Stage white 20px-radius cards on colored fields without general-purpose drop shadows.
- Echo the isometric opening geometry in a later panel and the closing call.
- Give black proof and trust chapters as much deliberate spacing as the cream sections.
- Use 18px green numbers with light italic descriptors for compact story-card results.

### Don't

- Do not make headline weight 700; the characteristic silhouette is regular with tight spacing.
- Do not turn all serif labels into uppercase sans-serif microcopy.
- Do not use bright orange as the entire page canvas; concentrate it in actions, ecosystem staging and the closing band.
- Do not apply multicolored gradients or purple glows to the marketing canvas.
- Do not round every object into the same shape: actions use 100px, content cards 20px and logo tiles 16px.
- Do not promote tiny 11px story capsules into the main action hierarchy.
- Do not add heavy elevation to white cards; the broad colored backing provides separation.
- Do not merge the blue explanatory field and mint capability variant into a rainbow card grid.

## Motion and responsive

### Motion

**Observed:**

- The navigation remains sticky during scrolling.
- Horizontal ecosystem tile strips and the quote wall use translated repeated content with clipped edges.
- A text link declares color and underline-property transitions of 0.3s cubic-bezier(0.44, 0, 0.56, 1); its hover color is orange.
- Some utility controls declare background-color transitions of 0.3s. No main-action hover or focus-visible transformation is established.

**Transfer:**

- Keep repeated tile and quote strips continuous and clipped to their stages, while maintaining readable live copy above them.
- Use the known orange text-link hover sparingly; preserve the flat capsule construction rather than adding ungrounded button movement.

**Unknown:**

- Ticker speed, direction changes, autoplay timing, carousel timing and scroll-reveal easing are unspecified.
- No general focus-visible or active-state visual system is established.

### Responsive

**Observed:**

- Desktop composition uses a 1200px main spine, 64px outer side padding and 72px navigation.
- Styles declare width boundaries near 480px, 640px, 810px, 992px and 1200px.

**Transfer:**

- On narrower screens, retain the paper opening, regular tight headline and architectural metaphor; move the main scene below the text instead of letting it obscure the promise.
- Collapse the three- and four-column card chapters into fewer columns while preserving media-before-copy order and the distinct blue, stone and black bands.
- Stack the spatial closing headline and sculpture without sacrificing the black capsule's contrast; let clipped ecosystem rows remain a recognizable device.
- Wrap catalog filters into readable labeled groups instead of compressing three select fields into one thin row.

**Unknown:**

- Exact mobile typography, side padding, navigation collapse and illustration positioning are not established; the stacking rules are adaptation guidance rather than measured mobile behavior.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
