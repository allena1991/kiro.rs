# Contra — creative work on stage

## Overview

An open, bright marketing style that gives practical software the energy of a creative portfolio. Oversized regular grotesk typography, charcoal actions and cool gray surfaces leave room for vivid portraits, layered interfaces and small iridescent accents. It suits products that want to feel both professionally useful and personally empowering, with sparse narrative sections balanced by richer proof walls.

### Essentials

- Headlines have the scale of a promise, not the weight of a slogan: regular grotesk at 80px/0.92 with -0.02em tracking; capability headlines stay at 80px/0.94.
- The opening pairs calm language with a dimensional human stage: a left-aligned two-line headline, 480px support measure and one action face a roughly 540px square layered portrait composition.
- Conversion stays charcoal and rounded rather than colorful: primary actions are 60px tall with 30px corners, 12px 24px padding and 16px/1.4 lettering with 0.04em tracking.
- White dominates the page; color lives chiefly inside media and tiny proof devices. Use #f5f6f9 for broad inset panels, #b4ff6a as a narrow collage seam, and gold–pink–lavender gradients for a thin benefit badge rather than broad text fills.
- Proof floats over people and their output: translucent white badges with 8px backdrop blur, 16–20px corners and pale blue-gray light sit partly outside portrait edges. Include this layered proof device even without portraits, using a real product outcome and a compact status card.
- A closing promise gets its own stage: an inset 40px-radius gray panel, a centered 80px/1.02 headline, one support line and one charcoal action, with a soft green glow rising from its bottom edge.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Benefit gold | `#f3ca4d` | `--color-gold` | accent | First stop in the small benefit badge gradient. |
| Collage lime | `#b4ff6a` | `--color-lime` | accent | Narrow rectangular seam between portrait and creative output; not a button color. |
| Benefit pink | `#ff979a` | `--color-pink` | accent | Middle stop in the small benefit badge gradient. |
| Benefit lavender | `#cbabff` | `--color-lavender` | accent | Last stop in the small benefit badge gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#222834` | `--color-action` | action, text | Primary buttons and opening headline. |
| Slate support | `#677083` | `--color-muted` | text | Main supporting paragraphs, metric descriptions and small uppercase labels. |
| Deep slate | `#4a5264` | `--color-secondary` | text, link | Testimonial copy and link hover color. |
| Footer black | `#131313` | `--color-footer-ink` | text, link | Navigation and directory links. |
| Primary ink | `#14171f` | `--color-ink` | text, accent | Core section text, numerical proof and small framing marks. |
| Warm headline black | `#262320` | `--color-warm-ink` | text | Large capability and closing headlines. |
| Glass edge | `#d0d4dc` | `--color-edge` | border | Fine outlines around frosted proof labels and demonstration cards. |
| Cool gray panel | `#f5f6f9` | `--color-panel` | surface, background | Inset feature stages, comparison emphasis and closing panel. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Dominant canvas, cards and reversed button text. Translucent white at 0.8 makes frosted labels; white at 0.2 makes light glass over imagery, appearing white on the canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| discovery directories | Directory slate | `#677084` | `--color-directory-muted` | text | Compact gallery support lines. |
| partnership and enterprise stories | Case study night | `#13171f` | `--color-story-dark` | background | Full-width reversed case-study band. |
| company storytelling | Pale culture canvas | `#f9fafb` | `--color-culture-canvas` | background, surface | Alternating editorial tiles and sculpture closing stage. |

## Typography

- **GT Standard 6 L** — Core marketing headings, paragraphs and navigation. Open, clean grotesk with broad circular forms; regular headlines, medium utility text and light demonstration lettering. If unavailable, use **DM Sans**. Use 400 for headlines and 500 for navigation; retain tight headline tracking. Font stack: "GT Standard 6 L", "DM Sans", Arial, sans-serif.
- **GT Standard L** — Light button lettering; medium cut also serves compact directory headings. Straightforward, softly rounded grotesk, with airy small action lettering. If unavailable, use **DM Sans**. Use 300 for light actions and 500 for directory headings. Font stack: "GT Standard L", "DM Sans", Arial, sans-serif.
- **Inter** — Small directory labels in the footer. Compact neutral sans, uppercase with wide tracking. Font stack: "Inter", Arial, sans-serif.
- **GT Standard M** (only for discovery directories) — Compact gallery descriptions. Small utility grotesk with slightly tightened tracking. If unavailable, use **DM Sans**. Font stack: "GT Standard M", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT Standard 6 L | 400 | 80px | 0.92 | -0.02em | Opening promise and oversized standalone metrics. |
| heading-lg | GT Standard 6 L | 400 | 80px | 0.94 | -0.02em | Capability chapters beside large visual collages. |
| closing | GT Standard 6 L | 400 | 80px | 1.02 | -0.02em | Centered closing promise in the inset stage. |
| heading | GT Standard 6 L | 400 | 48px | 1.15 | -0.0167em | Functional section title above a comparison table. |
| subheading | GT Standard 6 L | 400 | 32px | 36px | -0.0094em | Three-column capability summaries. |
| lead | GT Standard 6 L | 400 | 24px | 1.4 | normal | Hero support, chapter descriptions and metric captions. |
| body | GT Standard 6 L | 400 | 18px | 26px | 0.01em | Secondary feature descriptions and testimonial paragraphs. |
| button | GT Standard L | 300 | 16px | 1.4 | 0.04em | Primary and secondary action labels. |
| nav | GT Standard 6 L | 500 | 16px | 1.5 | 0.01em | Header navigation. |
| footer-link | GT Standard 6 L | 500 | 14px | 24px | normal | Directory links. |
| footer-label | Inter | 500 | 12px | 16px | 0.1em, uppercase | Footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company storytelling closings | sculpture-closing | GT Standard 6 L | 400 | 100px | 0.98 | -0.008em | Two-line closing statement beside iridescent sculpture. |
| company storytelling openings | manifesto | GT Standard 6 L | 400 | 96px | 0.92 | -0.02em | Broad centered statement over portrait videos. |
| discovery directories | directory-display | GT Standard L | 500 | 58px | 1.05 | -0.01em | Centered headline over an assistive search composer. |
| community and company storytelling | panel-heading | GT Standard 6 L | 400 | 56px | 1 | -0.0179em | Inset feature stages, community proof headings and editorial tiles. |
| partnership stories and FAQ sections | story-heading | GT Standard 6 L | 400 | 54px | 1 | normal | Split narrative section titles and two-line FAQ heading. |
| product demonstrations | benefit | GT Standard 6 L | 300 | 26.3px | 1.2 | 0.0076em | Gradient benefit badge above a demonstration card. |
| FAQ sections | question | GT Standard 6 L | 400 | 26px | 32px | normal | Open-ended question rows. |
| discovery directories | directory-heading | GT Standard L | 500 | 23px | 32px | 0.02em | Compact gallery row titles. |
| discovery directories | directory-body | GT Standard M | 400 | 16px | 1.5 | -0.01em | Single-line gallery descriptions. |
| partnership openings | partnership-eyebrow | GT Standard 6 L | 500 | 16px | 28px | 0.06em | Uppercase category label above the promise. |

**Notes:**

- Large type is regular, tightly tracked and close-led; the opening and capability chapters differ in line height without changing size.
- Support text is much smaller but still generous at 24px/1.4. Denser proof and capability summaries step down to 18px/26px.
- Use the light cut for button text, not a bold UI label. Use medium for navigation and footer links.
- The community and company variants use 56px headings rather than shrinking every headline to that size.

## Layout

**Density:** Airy narrative stages with compact, information-rich proof cards and directory regions.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Small repeated proof-card and footer-link gaps. |
| 16px | Heading-to-body spacing in capability summaries; label-to-list spacing. |
| 20px | Metric-to-caption gap and bento gutters. |
| 24px | Small tile padding and adjacent chapter columns. |
| 32px | Hero headline, support and action stack; main chapter copy gaps. |
| 48px | Opening vertical padding beneath the fixed header. |
| 60px | Major inset sides in community panels and footer; closing action separation on editorial variants. |
| 64px | Default capability and metric-band vertical padding. |
| 80px | Default desktop page side padding. |
| 120px | Inset summary columns and comparison sections; reversed story vertical padding. |
| 160px | Sculptural company closing vertical padding. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 80px. Centered desktop stage. The working content spans 1280px at a 1440px window.
- **chapter-split**: max width 1280px · 2 columns · gap 24px. Two equal chapter columns; collage can extend beyond its column and toward the page edge, but copy stays contained.
- **hero-copy**: max width 700px. Headline measure; supporting paragraph narrows to 480px.
- **summary-grid**: max width 1200px · 3 columns · gap 120px · side padding 120px. Three 320px capability descriptions.
- **footer-directory**: max width 1440px · 3 columns · gap 162px · side padding 60px. Three tall link columns beside a separate emblem area; groups stack within columns.
- **community-stage** (only for community storytelling): max width 1320px · 2 columns · gap 20px · side padding 60px. Inset 600px-tall feature bands with balanced text and media halves.
- **proof-wall** (only for community and company storytelling): max width 1117px · 3 columns · gap 10px. Masonry-like vertical stacks of independently sized testimonials.
- **gallery** (only for discovery directories): max width 1368px · 4 columns · gap 2px · side padding 36px. Nearly edge-to-edge visual gallery with 341px-wide images and no heavy card wrappers.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-actions | 30px |
|  | feature-stage | 40px |
|  | hero-glass | 16px |
|  | proof-label | 17px |
|  | floating-status | 20px |
| community proof walls | testimonials | 15px |
| workflow overview bento | workflow-tiles | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | glass-halo | `-3px -3px 32px 0px rgba(228, 232, 247, 0.8)` | Frosted floating hero proof; opposite-side badges reverse the offset. |
| partnership logo fields | logo-halo | `0px 0px 20px 0px rgba(228, 232, 247, 0.8)` | Pale, almost luminous edge rather than a dark lifted-card shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Base for all narrative chapters.

**CSS:** `background: #ffffff`

**Observed:** Most of the page remains plain white, including the long footer.

**Transfer:** Let media provide color rather than tinting every section.

#### Inset stage · level 0

**Use:** Closing conversion stage and scoped feature bands.

**CSS:** `background: #f5f6f9; border-radius: 40px; overflow: hidden`

**Observed:** Closing version is 1280px wide and 500px tall; community feature versions are 1320px by 600px.

**Transfer:** Contain a large promise or a clear copy/media pairing, not many small widgets.

#### Hero glass · level 2

**Use:** Floating proof over the opening media stack.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 16px; backdrop-filter: blur(8px); box-shadow: -3px -3px 32px 0px rgba(228, 232, 247, 0.8)`

**Observed:** Badges sit partly outside portrait edges, backed by pale light and legible white content.

**Transfer:** Preserve a white-facing readable center even when the surrounding glass overlaps dark media.

#### Frosted label · level 2

**Use:** Identity labels across portrait edges.

**CSS:** `background: rgba(255, 255, 255, 0.8); border: 1px solid #d0d4dc; border-radius: 17px; backdrop-filter: blur(8px)`

**Observed:** Wide, low name plate pairs a name with smaller attribution. Other floating status panels use 20px corners and stronger 25.5px blur.

**Transfer:** Use one identification plate and one outcome panel per collage, rather than covering every edge.

#### Reversed story · level 0

**Only for:** partnership and enterprise stories

**Use:** Focused case-study interlude.

**CSS:** `background: #13171f; color: #ffffff; padding: 120px 0px`

**Observed:** Full-width dark band holds an editorial title, quote and three oversized metrics.

**Transfer:** Use as one concentrated proof chapter, not a sitewide dark theme.

#### Editorial pale tile · level 0

**Only for:** company storytelling

**Use:** Narrative squares and sculpture stage.

**CSS:** `background: #f9fafb; border-radius: 30px; padding: 60px`

**Observed:** Text tiles alternate with equally sized photographs. Sculpture closing expands the pale fill across the whole width without rounded outer corners.

**Transfer:** Balance one compact story with one human image at a time.

## Components

### Fixed navigation

**Use:** Persistent orientation and conversion.

**CSS:** `height: 74px; background: rgba(255, 255, 255, 0.8); backdrop-filter: blur(10px); position: fixed; top: 0px; width: 100%; z-index: 10`

**Text style:** `nav` — GT Standard 6 L 500 · 16px/1.5 · tracking 0.01em

**Observed:** Brand at left, a short row of links beside it, sign-up pill and login at right. Interior links have 32px gaps; the header action is the compact 48px-tall variant.

**States:** Declared: hover navigation text changes to #4a5264; no underline.

**Transfer:** Use a small number of top-level destinations, keeping the main action visually isolated.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #222834; color: #ffffff; border-radius: 30px; padding: 12px 24px; height: 60px; gap: 12px`

**Text style:** `button` — GT Standard L 300 · 16px/1.4 · tracking 0.04em

**Observed:** Text-only pill used once per major promise. Header variant is 48px tall with 12px 16px padding.

**Transfer:** Use a short verb-led label and size width to content.

### Secondary button

**Use:** Deeper capability exploration.

**CSS:** `display: flex; align-items: center; justify-content: center; color: #222834; background: transparent; border: 1px solid #d0d4dc; border-radius: 30px; padding: 12px 24px; height: 60px`

**Text style:** `button` — GT Standard L 300 · 16px/1.4 · tracking 0.04em

**Observed:** A delicate outlined pill beside chapter text; subordinate to the filled conversion button.

**Transfer:** Keep the outline light and avoid pairing two filled actions.

### Metric group

**Use:** Quantified proof below the promise.

**CSS:** `display: flex; flex-direction: column; gap: 20px; max-width: 300px`

**Text style:** `display` — GT Standard 6 L 400 · 80px/0.92 · tracking -0.02em

**Observed:** Three unboxed groups spread across the page. Each giant number uses display and its descriptive line uses lead in slate; no divider or decorative chart is needed.

**Transfer:** Use defensible figures with short lowercase explanations.

### Floating identity plate

**Use:** Human attribution within a capability collage.

**CSS:** `background: rgba(255, 255, 255, 0.8); border: 1px solid #d0d4dc; border-radius: 17px; backdrop-filter: blur(8px); width: 344px; height: 92px`

**Observed:** Name above small role text; overlaps the outer side of a portrait rather than sitting below it like a caption.

**Transfer:** Use a customer, maker or project attribution relevant to the outcome shown.

### Footer directory link

**Use:** Comprehensive long-form site navigation.

**CSS:** `color: #131313; text-decoration: none; line-height: 24px`

**Text style:** `footer-link` — GT Standard 6 L 500 · 14px/24px

**Observed:** Three tall columns of nested groups; footer-label headings precede link stacks with 10px gaps. A standalone emblem anchors the left; copyright and six social icons finish the baseline.

**States:** Declared: hover color #4a5264; text-decoration-line none.

**Transfer:** Preserve the spacious directory silhouette while adjusting link count to the new product.

### Benefit badge

**Only for:** product demonstrations

**Use:** One memorable advantage above a transaction or outcome card.

**CSS:** `background: linear-gradient(90deg, #f3ca4d 0%, #ff979a 45.3125%, #cbabff 100%); border-radius: 100px; width: 244px; height: 64px; padding: 1px`

**Text style:** `benefit` — GT Standard 6 L 300 · 26.3px/1.2 · tracking 0.0076em

**Observed:** White inset pill leaves a thin gradient rim; its short label repeats the gradient as text fill. Badge overlaps a larger white demonstration card.

**Transfer:** Keep the claim short and the gradient confined to this special device.

### Testimonial card

**Only for:** community proof walls

**Use:** Real human social proof in uneven vertical stacks.

**CSS:** `background: #ffffff; border-radius: 15px; overflow: hidden; width: 366px`

**Text style:** `body` — GT Standard 6 L 400 · 18px/26px · tracking 0.01em

**Observed:** Avatar and author metadata at top, small social mark in a corner, quote below. Some cards include full-width square media; variable heights form the wall without uniform trimming.

**Transfer:** Use genuine quotes with differing lengths, preserving author context.

### Workflow tile

**Only for:** workflow overview bento

**Use:** Compact overview of adjacent capabilities.

**CSS:** `background: #f5f6f9; border-radius: 10px; padding: 24px; display: flex; align-items: center; justify-content: center`

**Observed:** Small white interface fragment above a centered short label. Narrow tiles mix with double-width squares; the heading occupies open grid space rather than a separate banner.

**Transfer:** Use one recognizable artifact per capability, not miniature full-page interfaces.

### FAQ row

**Only for:** FAQ sections

**Use:** Resolve objections after proof.

**CSS:** `padding: 24px 0px 16px; display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `question` — GT Standard 6 L 400 · 26px/32px

**Observed:** Wide question column beside a two-line title; compact plus mark at the far right, roughly 80px closed-row height.

**Transfer:** Organize around buying or adoption doubts; keep questions in natural language.

### Partner chip

**Only for:** partnership logo fields

**Use:** Dense ecosystem proof without a heavy enclosing panel.

**CSS:** `background: rgba(255, 255, 255, 0.2); border-radius: 12px; padding: 13px; height: 48px; box-shadow: 0px 0px 20px 0px rgba(228, 232, 247, 0.8); backdrop-filter: blur(6px)`

**Observed:** Small logo plus uppercase word label; many variable-width chips wrap into centered rows with 10px gaps, making an irregular cloud.

**Transfer:** Use actual integrations or compatible tools rather than inventing affiliations.

## Imagery and graphics

### Layered portrait stage

**Use:** Signature opening visual; include a layered proof scene on every new marketing page.

**Observed:** Large smiling waist-up portrait within a white circular cutout, placed on a rounded rectangular media card. Receding cards expose red, gray and dark strips at the top. Black concave corner marks bracket the square; two glass proof cards float outside it. The scene occupies about the right two fifths of the opening.

**Transfer:** Use a real customer or maker with a product outcome. If portrait media is unavailable, use a high-quality artifact or product view as the central object, retaining the card stack, corner marks and overlapping proof.

**Build:** Make a 540px square stage with a 460px front card; stack three progressively narrower rounded rectangles behind it, offset upward by about 24px each. Use the main image colors in the back cards, soften them with blur, and mask the portrait against a white disc. Place small black square-minus-quarter-circle marks outside all four corners. Anchor two 16px-radius Hero glass cards on opposite edges.

### Portrait and output collage

**Use:** Capability chapters with human credibility.

**Observed:** Tall portrait around 438px by 533px, sometimes color-rich and sometimes naturally lit. A smaller creative work image intrudes from the lower outside edge, joined by a vivid 65px by 235px lime strip. Black corner marks and frosted labels make the composition feel deliberately assembled.

**Transfer:** Pair the person or product with something they produced. Minimum version is one strong image, one smaller output panel, one lime seam and one outcome label.

**Build:** Position a tall image in the media half of a two-column chapter. Place a landscape artifact over its lower outer quarter; put a #b4ff6a vertical rectangle at their join. Add concave black corner marks, a Frosted label near the upper outside edge and a small status panel at the lower inside edge.

### Soft stage light

**Use:** Closing stage and background support behind layered proof.

**Observed:** A pale green glow rises from the bottom center of the gray closing panel; other proof collages use diffuse lavender, mint and blue light. Color dissolves into the neutral backing rather than forming a hard gradient rectangle.

**Transfer:** Include soft light in the closing stage. Match the soft glow; exact stops are not essential.

**Build:** On the Inset stage add an absolutely positioned ellipse about 800px wide and 220px tall, centered partly below the bottom edge. Fill with rgba(180,255,106,0.22), blur by 64px and clip to the panel. Keep text and the button above it.

### Interface stage

**Only for:** product-led community openings

**Use:** Centered demonstration under the promise.

**Observed:** A broad white interface window around 1000px wide is edged with a thin gold–pink–lavender rim and backed by a faint matching aura. The content is an actual discovery interface, not an abstract dashboard texture.

**Transfer:** Show a real high-value product task; reduce internal detail enough to read at marketing scale.

**Build:** Use a 20px-radius white panel with a 1px gradient backing, plus a slightly larger 24px-radius duplicate at 0.2 opacity behind it. Use a 135-degree gold–pink–lavender gradient.

### Human proof wall

**Only for:** community and company storytelling

**Use:** Social proof and culture sections.

**Observed:** Testimonial card walls mix circular avatars, natural portraits and occasional square video stills. Company editorial tiles use black-and-white group photography and candid event imagery with dark translucent location pills; portrait videos form a four-column strip.

**Transfer:** Favor actual people and imperfectly natural settings over stock business handshakes. Keep the media diverse but the surrounding card system neutral.

### Iridescent sculpture

**Only for:** company storytelling closings

**Use:** Oversized symbolic closing object.

**Observed:** A faceted, glassy four-point emblem is cropped beyond the right and lower edges of a pale stage. Translucent mint faces and pink, lavender and yellow reflective bevels contrast with a simple two-line statement at left.

**Transfer:** Use the new product's own simple symbol as a translucent sculptural object. Minimum acceptable version is a clean faceted SVG with pale faces and bright prismatic bevels, not a flat rainbow logo.

**Build:** Draw a simple four-point or product-specific silhouette with concave sides. Duplicate and offset the silhouette diagonally to create depth; connect matching corners with narrow polygons. Fill broad faces with near-white translucent mint, bevels with alternating pink, gold and lavender gradients, and add fine white edge highlights. Scale beyond half the section width and clip at the page edge.

### Portfolio gallery

**Only for:** discovery directories

**Use:** Browsing-first visual proof.

**Observed:** Large rectangular project thumbnails feature websites, printed identities, packaging, animation and editorial artwork. Saturated colors belong to the individual projects; thumbnails touch across 2px gutters rather than becoming separate raised cards.

**Transfer:** Use real outputs from the new ecosystem, maintaining generous image area and minimal metadata.

### Icons

**Observed:** Small predominantly solid SVG marks at 16–24px; black or ink on light surfaces and white when reversed. Arrows indicate exploration, checks support comparison rows, and tiny social marks identify testimonial sources. Concave corner marks are framing devices rather than generic UI icons.

**Transfer:** Choose compact filled icons with matching optical weight. Keep line icons limited to functional symbols; use actual service logos only where an affiliation is real.

## Section recipes

How recurring sections are built.

### First screen: Portrait stage opening

**Observed:** A fixed 74px Fixed navigation sits above a white two-column stage with 48px vertical and 80px side padding. The opening occupies 636px beneath it. A left-aligned, two-line display headline spans roughly half the content width, with a 480px lead paragraph and Primary button separated by 32px gaps. The Layered portrait stage occupies the right, about 540px square: receding cards in back, white disc and portrait in front, concave marks at the outer corners and floating glass proof at both sides. Within the first 900px, all headline, support, action and primary scene are visible, followed by the three Metric groups; the following capability chapter starts below the fold.

**Transfer:** Keep the asymmetry and comparable visual weight for a new promise. Without people, stage a real output or product artifact using the same layered proof construction. Community product openings instead center an 80px promise over a broad Interface stage; partnership openings retain the split but use small circular portraits and an eyebrow. Company storytelling uses a 96px centered manifesto over candid video portraits; directories use a compact centered promise and search composer.

**Avoid:** Do not turn the opening into a centered headline with a tiny generic dashboard, or replace the dimensional collage with a full-bleed stock photograph.

**Text style:** `display` — GT Standard 6 L 400 · 80px/0.92 · tracking -0.02em

### Oversized proof strip

**Observed:** Three Metric groups on white, with 64px vertical padding. Numbers share display scale with the hero rather than a small KPI style; captions sit 20px below.

**Transfer:** Place a few verifiable outcomes near the promise; keep each explanation short enough to scan.

**Text style:** `display` — GT Standard 6 L 400 · 80px/0.92 · tracking -0.02em

### Alternating capability chapter

**Observed:** Chapter split uses 24px column gap, 64px vertical padding and roughly 600px-tall media compositions. Portrait and output collage alternates sides with heading-lg, lead and a Secondary button; copy stack uses 32px gaps.

**Transfer:** Explain one user outcome per chapter, choosing an artifact that makes that outcome tangible.

**Text style:** `heading-lg` — GT Standard 6 L 400 · 80px/0.94 · tracking -0.02em

### Compact capability trio

**Observed:** Three open columns at 320px each, with subheading and body separated by 16px. No separate tinted card surrounds each feature.

**Transfer:** Group supporting operational features here after the more expressive chapters.

**Text style:** `subheading` — GT Standard 6 L 400 · 32px/36px · tracking -0.0094em

### Comparison chapter

**Observed:** Centered heading above a wide table inset by 120px. Very light horizontal rules, compact text and checks keep it functional; the first product column receives a continuous cool gray fill with rounded upper corners.

**Transfer:** Use equivalent rows and honestly comparable alternatives. Keep the visual emphasis on one column rather than heavy cell borders.

**Text style:** `heading` — GT Standard 6 L 400 · 48px/1.15 · tracking -0.0167em

### Glowing closing stage

**Observed:** Inset stage is 1280px by 500px with 40px corners and Soft stage light beneath the centered closing headline. Lead support and Primary button follow with 32px spacing. It is separated from the white directory footer rather than merging into it.

**Transfer:** Restate the central outcome in a shorter, confident phrase. Retain the soft light and one decisive action even if the page has no other tinted section.

**Text style:** `closing` — GT Standard 6 L 400 · 80px/1.02 · tracking -0.02em

### Long directory ending

**Observed:** White footer with a separate emblem at left and three tall grouped link columns; uppercase footer-label headings, regular link stacks and substantial breathing room between groups. Bottom line holds copyright at left and a compact social row at right.

**Transfer:** Finish with this structured directory after the closing stage; reduce group count when content is smaller, not the sense of breathing room.

### Community feature stage

**Only for:** community storytelling

**Observed:** Inset stage bands use a 1320px by 600px two-column composition, panel-heading, body and Secondary button at left or right. Overlapping profile or transaction views occupy the other half, with diffuse blue or lavender light and purposeful edge clipping.

**Transfer:** Adapt to onboarding or membership benefits without making the marketing typography look like the embedded UI.

**Text style:** `panel-heading` — GT Standard 6 L 400 · 56px/1 · tracking -0.0179em

### Proof wall and objections

**Only for:** community and partnership stories

**Observed:** Human proof wall uses three uneven columns on a gray band with a centered panel-heading. FAQ sections return to white: a two-line story-heading at left and broad FAQ rows at right. Partnership variants substitute a Reversed story with giant metrics and later two side-by-side attributed quotes.

**Transfer:** Choose proof forms appropriate to the decision: human experience, quantified outcomes or objections, rather than forcing every type onto one page.

### Editorial culture and sculpture

**Only for:** company storytelling

**Observed:** Alternating 650px square Editorial pale tiles and candid media sit in a two-column checkerboard. Dark translucent location pills sit on the photographs. A large centered numerical statement bridges to the proof wall. The final pale full-width stage pairs sculpture-closing type at left with Iridescent sculpture spilling out at right.

**Transfer:** Use a short founding or operating belief with concrete human scenes; let a product-specific symbol provide the final dimensional flourish.

**Text style:** `sculpture-closing` — GT Standard 6 L 400 · 100px/0.98 · tracking -0.008em

### Browsing gallery

**Only for:** discovery directories

**Observed:** Compact directory-heading and directory-body form heading pairs with 6px gaps; gallery follows 24px below. Four thumbnails span the width across 2px gutters. Larger studio rows use three landscape images with simple author metadata. A pale inline action band interrupts the galleries, then an outlined exploration action precedes the footer.

**Transfer:** Use for catalog or ecosystem browsing; keep project imagery dominant and controls understated.

**Text style:** `directory-heading` — GT Standard L 500 · 23px/32px · tracking 0.02em

## Page flow

**Storyline:** Outcome promise → tangible product or human demonstration → credible proof → capability chapters → decision support → renewed promise → spacious directory.

### Product capability landing page

1. **Promise** — Split opening with oversized claim and layered human proof.
2. **Quantified proof** — Three unboxed oversized metrics.
3. **Capability chapters** — Portrait/output collages alternate with practical demonstration cards.
4. **Decision support** — Open feature trio followed by a lightly ruled comparison table.
5. **Closing call** — Glowing inset promise stage, then full white directory and social baseline.

**Transfer:** Best default for a new product: alternate emotional human proof with concrete workflow value.

### Partnership acquisition

1. **Promise** — Split promise with category eyebrow, circular people and floating proof.
2. **Ecosystem proof** — Trusted-logo strip followed by luminous chip cloud.
3. **Case study** — Reversed title, quote and large numerical results.
4. **Capability chapters** — Alternating people, output galleries and short benefit lists.
5. **Objection handling** — Attributed quotes and FAQ rows.
6. **Closing call** — Monumental centered invitation and single action, followed by the long white footer.

**Transfer:** Use for a relationship-led offering where compatible tools and actual outcomes establish trust.

### Community or user acquisition

1. **Promise** — Centered promise and action above a gradient-edged interface stage.
2. **Benefits** — Three open summaries and alternating cool-gray feature panels.
3. **Capability overview** — Logo proof and an irregular workflow bento with miniature artifacts.
4. **Social proof** — Three-column human testimonial wall.
5. **Objection handling** — Split FAQ title and question rows.
6. **Closing call** — Simple centered invitation, support and pill action, then the full directory.

**Transfer:** Use a broader capability overview when the offer spans several related jobs.

### Company belief and human credibility

1. **Positioning** — Centered manifesto and candid four-column portrait videos.
2. **Human story** — Alternating editorial text squares and team/event media.
3. **Quantified proof** — One oversized centered earnings statement.
4. **Social proof** — Community testimonial wall on cool gray.
5. **Closing call** — Two-line monumental invitation beside cropped iridescent sculpture; directory ends at the social baseline.

**Transfer:** Pair beliefs with people and real operational outcomes, not abstract values alone.

### Discovery and catalog browsing

1. **Promise** — Compact centered headline and assistive search composer over a cool light aura.
2. **Participation** — Horizontal topic/challenge media strip and browsing filters.
3. **Product proof** — Studio row and repeated project galleries, interrupted by an inline conversion band.
4. **Exploration** — Large mixed project grid and outlined exploration action.
5. **Directory** — Tall grouped navigation with copyright, trust badge and social links.

**Transfer:** Use this denser variant for a catalog, keeping expressive artwork inside thumbnails rather than enlarging the whole page's UI.

## Writing

Confident, practical and creative-person friendly. The tone promises independence and momentum, then explains the actual task or benefit without sounding technical for its own sake.

**Do not copy:** Do not reuse Contra's brand name, logo, proprietary artwork, customer names, partner affiliations, testimonials, numerical claims, earnings, commission claims or legal statements. Replace them with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your when describing benefits; use we for a company belief. Product descriptions often start with an imperative verb.
- **Rhythm:** Short 3–9 word outcome headings, one or two plain-language support sentences, and short verb-led actions. Feature details can be longer, while proof labels remain compressed.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the audience's desired outcome, not an abstract category. | 5–9 words | “Everything creatives need to get paid”<br>“Get discovered as a freelancer” |
| Capability headline | Direct action plus object, or a familiar workflow with a useful modifier. | 3–7 words | “Sell digital products”<br>“Contracts with built-in payments” |
| Supporting line | Explain what can be done, with the mechanism close behind the benefit. | 12–30 words | “Manage products, contracts, clients, and payments all on a platform built for creatives.”<br>“Everything you need to sell your creative work and get paid.” |
| Action | Plain verb-led invitation; free only when true. | 2–5 words | “Get started”<br>“Request partnership”<br>“Get started for free” |
| Proof caption | Lowercase, compact explanation directly under a figure. | 3–5 words | “in earnings processed”<br>“more earnings per sale” |
| Closing promise | Short audience-aligned restatement, not a new feature list. | 3–9 words | “Payments built for creativity”<br>“Get more creative” |

**Words and phrasing to use:** built for; get started; your work; all in one place; create; manage; connect; keep; trusted by

**Avoid:** revolutionary solution; synergize; unlock unparalleled potential; enterprise-grade everything; hustle harder

**Rules:**

- Put an observable task or outcome in each capability headline.
- Follow emotional promises with mechanisms: how the work happens, who benefits and what friction disappears.
- Let proof numbers carry confidence; keep adjacent claims precise and supportable.
- Use everyday professional language rather than puns in controls or decorative technical jargon.

## Do's and Don'ts

### Do

- Set opening headlines at 80px, regular weight, -0.02em tracking and 0.92 line height.
- Keep the hero support measure near 480px and its stack gaps at 32px.
- Use the 60px charcoal pill for the main action and the 48px variant in navigation.
- Make one layered proof scene with translucent labels and concave corner marks.
- Preserve 80px desktop page sides and 64px chapter vertical padding for the default landing composition.
- Give numerical proof display scale and a 20px caption gap.
- Keep broad panels cool gray with 40px corners and reserve vivid lime for narrow seams.
- Give the closing promise a centered glowing stage before the long white footer.

### Don't

- Do not turn regular display type into a heavy 700-weight slogan.
- Do not use lime, pink or a rainbow gradient as the default conversion button fill.
- Do not put every paragraph inside a raised card; capability trios are open columns.
- Do not replace pale blue-gray glass halos with heavy black drop shadows.
- Do not round portfolio thumbnail galleries into isolated 40px cards; their 2px gutters are deliberate.
- Do not make all testimonial cards the same height or trim every quote to equal length.
- Do not spread the partnership dark band into a general dark page theme.
- Do not apply 100px sculpture-closing type or iridescent company symbolism to every ordinary feature chapter.

## Motion and responsive

### Motion

**Observed:**

- Declared link color transitions use 0.3s cubic-bezier(0.44, 0, 0.56, 1).
- Navigation and footer links change to deep slate on hover; exploration text links can retain underlines.

**Transfer:**

- Keep link feedback concentrated in the text color, preserving the still, clean surface around the layered scenes.

**Unknown:**

- Entry and scroll choreography, hero stack cycling cadence and actual animation playback timings are unknown.

### Responsive

**Observed:**

- Styles declare width boundaries around 810px and 1200px, with additional refinements around 1400px.

**Transfer:**

- Recommended narrow layout: stack the promise before the portrait stage and keep the two proof labels attached to the media, not to page coordinates.
- Recommended narrow layout: reduce display scale and side padding together; preserve close headline leading and keep the white breathing room around the scene.
- Recommended narrow layout: turn proof walls and capability splits into vertical sequences while retaining varied card heights and the centered closing glow.

**Unknown:**

- Exact mobile typography, navigation behavior, column changes and padding values are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
