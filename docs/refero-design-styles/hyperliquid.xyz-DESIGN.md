# Hyperliquid — liquid systems, editorial scale

## Overview

An institutional yet organic visual language for ambitious infrastructure and technical products. Cool off-white space and very dark forest green meet luminous mint, with delicate editorial serifs above compact grotesk text. Point-cloud sculpture, richly textured product stages and a monumental typographic ending give otherwise sparse pages a living, computational character.

### Essentials

- Editorial promise, functional explanation: the opening pairs an 80px/1.05 light serif with -0.03em tracking and a separate 18px/1.4 grotesk support column; chapter headings switch to 36px/1.2 regular grotesk.
- The first screen breathes before it performs: 280px top space, 48px side margins, a left headline up to 640px wide and a right support block up to 440px wide; a low-contrast identity strip precedes full-width dark particle art starting at 576px.
- Actions are compact blocks rather than pills: 48px-high, 12px-radius rectangles with 14px/16px uppercase medium labels, 16px horizontal padding and a small directional arrow.
- Color behaves like a change of atmosphere: most of the landing page is #f8f9f9 with #03211c text; mint #97fce3 is concentrated in actions, markers and particles, while deep green fills major art or editorial bands, not every card.
- Computation is rendered as matter: a full-width 540px-high mint particle landscape is echoed by 224px point-cloud chapter sculptures. Create dots along a product-relevant abstract volume when no bespoke media exists.
- Chapters occupy a narrow lane inside a broad frame: 960px central containers, 80px internal side insets, 16px label-to-heading gaps and 72px sculpture-to-copy gaps; rows and tables remain restrained rather than becoming a dashboard of cards.
- The ending is an artwork, not another sales pitch: an oversized name treatment about 1326px wide and 267px high sits at the bottom of a 500px breathing field, directly above a 284px forest footer. Use the new product's own name as the monumental graphic.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sage light | `#77b694` | `--color-glow` | background, accent | Light end of the full-width forest-to-sage editorial atmosphere. |
| Moss | `#447259` | `--color-green` | accent, link | Inline highlighted links and the middle of the atmospheric editorial gradient. |
| Raised forest | `#0f3933` | `--color-footer` | background, surface | Default footer and dark-theme navigation/filter blocks. |
| Deep forest | `#072723` | `--color-forest` | background | Dark feature canvases and the directory theme. |
| Particle field backing | `#042420` | `--color-media-forest` | background | Full-width opening particle stage. |
| Forest ink | `#03211c` | `--color-ink` | text, link | Main headings, body and action labels on light or mint surfaces. |
| Gradient depth | `#011916` | `--color-abyss` | background | Dark upper origin of the editorial atmosphere. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Liquid mint | `#97fce3` | `--color-mint` | action, accent, surface | Primary actions, active navigation, numbered markers and luminous art; footer fill only in the dark directory variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Secondary forest | `#4d625e` | `--color-body-muted` | text | Visible result of forest ink at 70% over the porcelain canvas; explanatory paragraphs. |
| Muted forest gray | `#96a3a1` | `--color-muted` | text | Visible result of forest ink at 40% over the porcelain canvas; eyebrows, metadata and subdued currency prefixes. |
| Muted on forest | `#9fb0ad` | `--color-inverse-muted` | text | White at 60% over raised forest; footer headings and dark filter labels. |
| Forest glass tint | `#e0e3e3` | `--color-glass` | surface | Visible 10% forest-ink tint over porcelain; translucent product window uses rgba(3,33,28,0.1) over its artwork. |
| Control gray | `#e8eaea` | `--color-control` | surface, action | Neutral navigation blocks and secondary actions; active resource-row fill. |
| Pale architectural edge | `#e6ebeb` | `--color-edge` | border | Faint vertical frame edges on resource rows and the translucent product window. |
| Row hover | `#f0f1f1` | `--color-hover` | surface | Resource-row hover and focus-visible fill. |
| Cool porcelain | `#f8f9f9` | `--color-canvas` | background | Default marketing canvas and unboxed chapter backgrounds. |
| White | `#ffffff` | `--color-white` | text, surface | FAQ surfaces and reversed editorial text. |

## Typography

- **ABC Diatype** — All supporting text, chapter headings, actions, figures and metadata; Regular and Medium cuts form one family. Compact contemporary grotesk with direct forms, regular body weight and tightly spaced larger headings. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". If unavailable, use **Inter**. 400 and 500; preserve the negative tracking and avoid bold headings. Font stack: "ABC Diatype", "Inter", Arial, sans-serif.
- **Teodor** — Opening promises and long-form editorial declarations. Light, high-contrast editorial serif with graceful thin strokes and closely fitted letters. If unavailable, use **Bodoni Moda**. 300 where available, otherwise 400; tune line breaks to retain the open editorial silhouette. Font stack: "Teodor", "Bodoni Moda", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Teodor | 300 | 80px | 1.05 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Default landing-page headline, broken into two substantial lines. |
| editorial | Teodor | 300 | 40px | 1.15 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Long white declarations on an atmospheric green band. |
| heading | ABC Diatype | 400 | 36px | 1.2 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Chapter statements, including sentence-length headings. |
| article-title | ABC Diatype | 400 | 24px | 1.25 | -0.03em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Editorial titles in horizontal news rows. |
| stat | ABC Diatype | 400 | 24px | 1.2 | normal | Compact quantified proof; figures remain much smaller than chapter headings. |
| body | ABC Diatype | 400 | 18px | 1.4 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Support lines, explanatory prose, resource names and FAQ questions. |
| eyebrow | ABC Diatype | 500 | 14px | 16px | normal, uppercase | Chapter labels, navigation, actions, table metadata and footer links. |
| number-marker | ABC Diatype | 500 | 12px | 12px | -0.01em, uppercase | Two-digit square chapter markers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical, directory and organization pages | statement-opening | Teodor | 300 | 64px | 1.05 | -0.03em | Wide editorial opening sentence with a small topic label occupying an indent on the first line. |
| architecture explanations and compact market strips | technical-body | ABC Diatype | 400 | 16px | 1.4 | -0.01em | Denser supporting text alongside technical diagrams. |
| interactive directories | filter | ABC Diatype | 500 | 12px | 12px | -0.01em | Uppercase category tab labels. |

**Notes:**

- Serif carries the promise and editorial conviction; grotesk carries explanation and navigation. Neither relies on heavy weights.
- Use -0.03em on large serif and grotesk headings, -0.01em on prose, and normal tracking on the uppercase 14px labels.
- The monumental closing name is custom vector artwork, not an additional body-font recipe. Fit lettering to its broad, shallow frame.

## Layout

**Density:** Airy chapters with compact utility rows; long rests separate a small sculpture, its statement and its action.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Navigation-block separation, stacked FAQ separation and compact metadata groups. |
| 12px | Media-gallery gutters and frequent small flex gaps. |
| 16px | Label-to-heading gap, horizontal action inset and icon separation. |
| 24px | FAQ inner padding, news row vertical padding and top offset for navigation. |
| 32px | Heading-to-paragraph gap and label-to-resource-list gap. |
| 40px | Broad inner frame inset and chapter subregion padding. |
| 48px | Opening and navigation side margins. |
| 56px | Between editorial declarations. |
| 72px | Sculpture-to-copy and copy-to-action spacing. |
| 80px | Central chapter side inset and wide row column gap. |
| 104px | FAQ top padding and separation before editorial lists. |
| 120px | Organization chapter bottom padding and long subsection gaps. |
| 160px | Major central chapter top and bottom breathing space. |
| 240px | Clear space above the closing name graphic. |
| 280px | Top padding of opening text fields. |

### Containers and grids

- **outer-frame**: max width 1520px · side padding 16px. Broad page frame; nested 40px insets define most wide editorial content.
- **hero**: max width 1520px · 2 columns · side padding 48px. Unequal landing opening: 640px headline and 440px support block, spaced apart with balanced lower edges.
- **chapter-lane**: max width 960px · side padding 80px. Centered chapter and row lane; inner prose width is 800px.
- **reading-column**: max width 800px. Long heading statements, paragraphs and FAQ group.
- **organization-split** (only for organization pages): 2 columns · gap 80px · side padding 40px. Wide numbered chapters pair a left heading with a right narrative and resource links.
- **photo-mosaic** (only for community and culture pages): 2 columns · gap 12px. Alternating 792px/524px and 524px/792px image pairs with 400px-high frames.
- **technical-grid** (only for technical feature explanations): 3 columns · gap 0px. Dark utility grid with fine boundaries; a wide lower cell can span two columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls-and-faq | 12px |
|  | product-window | 16px |
| community and culture pages | photographs | 8px |
| interactive directories | directory-orbs | 50% |

## Surfaces and depth

### Surfaces

#### Porcelain canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f8f9f9; color: #03211c`

**Observed:** The uninterrupted pale field makes typography and small objects feel spacious.

**Transfer:** Leave explanatory chapters unboxed.

#### White question panel · level 1

**Use:** FAQ rows and the light half of technical explanations.

**CSS:** `background: #ffffff; border-radius: 12px; box-shadow: none`

**Observed:** White is a small tonal lift above the canvas, not a floating shadow card.

**Transfer:** Separate grouped questions by 4px rather than adding elevation.

#### Forest stage · level 0

**Use:** Full-width art and reversed feature bands.

**CSS:** `background: #072723; color: #ffffff`

**Observed:** Large rectangular bands with subtle vertical rails; the opening art uses the slightly darker media backing.

**Transfer:** Let dark sections feel like environments, not rounded feature cards.

#### Editorial atmosphere · level 0

**Use:** A major conviction or principles passage.

**CSS:** `background-image: radial-gradient(113% 100% at 50% 0px, #011916 0%, #0f3933 34.5035%, #447259 67.2508%, #77b694 99.8856%); color: #ffffff`

**Observed:** Deep green at the top opens into diffuse moss and sage lower down. Fine translucent vertical rails pass through the band.

**Transfer:** Pair sustained editorial prose with the slow tonal opening; keep the glow soft rather than neon.

#### Translucent product window · level 1

**Use:** A product demonstration above rich artwork.

**CSS:** `background: rgba(3,33,28,0.1); backdrop-filter: blur(8px); border-radius: 16px; padding: 4px; border-left: 1px solid #e6ebeb; border-right: 1px solid #e6ebeb`

**Observed:** A wide browser-like frame projects beyond its backing image and is clipped by the central demonstration stage.

**Transfer:** Place an actual interface inside the translucent frame; preserve the slight offset and oversized crop.

#### Forest footer · level 0

**Use:** The ending beneath the monumental name.

**CSS:** `background: #0f3933; color: #ffffff`

**Observed:** A flat full-width band, not a raised panel. The dark directory reverses this band to mint with forest text.

**Transfer:** Keep the color reversal scoped to a fully dark directory.

## Components

### Floating navigation

**Use:** Persistent site orientation.

**CSS:** `position: fixed; top: 0px; height: 72px; z-index: 10; padding: 24px 48px 0px; display: flex; justify-content: space-between`

**Text style:** `eyebrow` — ABC Diatype 500 · 14px/16px · uppercase

**Observed:** Left cluster contains a compact brand plaque followed by separate neutral navigation blocks, spaced 4px apart. Right cluster contains a neutral utility action and mint primary action. Progressive backdrop blur softens passing content without a solid full-width toolbar.

**Transfer:** Use a compact original logotype inside the first block; let the two clusters stay visually separate.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #97fce3; color: #03211c; height: 48px; padding: 24px 16px; border-radius: 12px; display: flex; align-items: center; justify-content: center; gap: 16px`

**Text style:** `eyebrow` — ABC Diatype 500 · 14px/16px · uppercase

**Observed:** Uppercase label with a 16px northeast arrow in content sections; the compact header version can omit the arrow.

**Transfer:** Keep one strong mint action per local decision point.

### Secondary button

**Use:** Documentation, learning and supporting actions.

**CSS:** `background: #e8eaea; color: #03211c; height: 48px; padding: 24px 16px; border-radius: 12px; display: flex; align-items: center; gap: 16px`

**Text style:** `eyebrow` — ABC Diatype 500 · 14px/16px · uppercase

**Observed:** Matches the primary action's geometry; width fits the label and a right or northeast directional arrow.

**Transfer:** Use gray, not a dark filled button, for the supporting action on light pages.

### Resource row

**Use:** Applications, integrations, explorers and external resources.

**CSS:** `height: 64px; padding: 16px 80px; display: flex; align-items: center; gap: 80px; border-left: 1px solid #e6ebeb; border-right: 1px solid #e6ebeb; transition: background-color 0.2s`

**Text style:** `body` — ABC Diatype 400 · 18px/1.4 · tracking -0.01em

**Observed:** Small partner icon at left, resource name, muted uppercase domain metadata and a faint northeast arrow at far right. The organization variant is 680px wide with no horizontal inset.

**States:** Declared: hover background-color #f0f1f1; focus-visible background-color #f0f1f1; active background-color #e8eaea.

**Transfer:** Prefer quiet rows to separate boxed partner cards.

### FAQ row

**Use:** Late-stage objection handling.

**CSS:** `background: #ffffff; border-radius: 12px; min-height: 72px; padding: 24px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `body` — ABC Diatype 400 · 18px/1.4 · tracking -0.01em

**Observed:** Question on the left, small downward chevron on the right. Four tightly stacked white rows occupy an 800px lane.

**Transfer:** Use short direct questions; keep expanded-answer styling restrained.

### Quantified proof strip

**Use:** Compact proof immediately after a major art stage.

**CSS:** `display: flex; justify-content: space-between; padding: 24px 80px; max-width: 960px`

**Text style:** `stat` — ABC Diatype 400 · 24px/1.2

**Observed:** Four inline metrics rather than giant KPI cards. A subdued currency prefix is separated from the figure, with a small uppercase label 4px below.

**Transfer:** Use a few verifiable figures and short units; preserve the restrained numerical scale.

### News row

**Use:** Editorial credibility and external coverage.

**CSS:** `display: flex; align-items: flex-start; gap: 80px; padding: 24px 80px; max-width: 960px`

**Text style:** `article-title` — ABC Diatype 400 · 24px/1.25 · tracking -0.03em

**Observed:** Publisher and date form the narrow left metadata column, a sentence-case title fills the wider middle column, and a northeast arrow sits on the right. A low-key read-all row ends the list.

**Transfer:** Use real editorial material, keeping the metadata subordinate to the title.

### Square sequence marker

**Use:** A narrow numbered rail alongside editorial paragraphs.

**CSS:** `width: 24px; height: 24px; background: rgba(232,254,248,0.36); display: flex; align-items: center; justify-content: center`

**Text style:** `number-marker` — ABC Diatype 500 · 12px/12px · tracking -0.01em · uppercase

**Observed:** Small square blocks sit to the left of the prose lane rather than above each paragraph. The highlighted state is brighter mint; the technical architecture variant places mint markers beside compact headings.

**Transfer:** Use the marker rail to give long statements a measured pace.

### Footer columns

**Use:** Final utility navigation.

**CSS:** `background: #0f3933; color: #ffffff; padding: 64px 56px 72px; max-width: 1520px; display: flex; justify-content: space-between`

**Text style:** `eyebrow` — ABC Diatype 500 · 14px/16px · uppercase

**Observed:** A small organic emblem anchors the left; two compact link groups sit on the right. Muted headings lead white uppercase links stacked with 4px gaps. The fully dark directory uses mint backing and forest links.

**Transfer:** Keep the footer shallow and sparse; let the name artwork above carry the visual weight.

### Category tab

**Only for:** interactive directories

**Use:** Filtering the spatial ecosystem scene.

**CSS:** `background: #0f3933; color: rgba(255,255,255,0.6); border: 1px solid rgba(0,0,0,0.08); border-radius: 12px; padding: 12px 14px; height: 38px`

**Text style:** `filter` — ABC Diatype 500 · 12px/12px · tracking -0.01em

**Observed:** A compact horizontal tab strip overlays the top of the graphic region. Selected tab has mint fill and forest text; labels remain uppercase.

**Transfer:** Limit categories to short functional names; keep tabs distinct from the floating navigation.

## Imagery and graphics

### Point-cloud matter

**Use:** Signature full-width opening stage, chapter sculptures and low-contrast interludes.

**Observed:** Mint dots form a rolling landscape on dark forest, while tiny dark or pale particles describe a rectangular volume, organic emblem and globe in 224px chapter frames. The art alternates between immersive field and a small specimen above text. A pale wave of particles crosses a 960px-wide interlude.

**Transfer:** Translate an original product concept into a dotted volume. The minimum version is a coherent spherical or wave-shaped point field, not random confetti.

**Build:** Use SVG or canvas circles sampled on a regular 3D sphere or sine-wave mesh. Project into a 1440px by 540px stage; vary circle radii around 1px–5px with depth and use mint at varied alpha on #042420. For 224px specimens, project several hundred 1px–2px forest dots on transparent backing, leaving the silhouette porous. For the interlude, distribute pale forest dots along a shallow sine wave and fade the top and bottom into porcelain.

### Textured product stage

**Use:** Large product proof within the central lane.

**Observed:** A bright teal-green pointillistic water-like surface sits behind a dark interface. Horizontal marks and layered pools of turquoise, moss and near-black create rich depth. The interface is offset inward from the top-left and extends beyond the visible right boundary, with a translucent browser cap.

**Transfer:** Pair a genuine interface with an original data-like green texture. Preserve the painterly density behind the frame and the disciplined dark UI in front.

**Build:** Create a 960px by 560px backing using layered SVG paths or short horizontal rounded strokes. Modulate stroke density with a wave field, mixing mint, moss and forest at varied opacity. Add subtle blur only to distant marks; place the framed interface about 80px inward and 56px below the backing's top, then clip the complete stage.

### Monumental closing name

**Use:** Signature ending on every page type.

**Observed:** A broad vector logotype nearly fills the width, about 1326px by 267px within a 500px field. Upright sans forms transition into a sloping editorial serif portion. The lower letterforms touch or clip into the footer boundary. Dark directory pages reverse the lettering to mint.

**Transfer:** Create a typographic composition from the new product's own name; retain the enormous low-lying scale even when the word is shorter.

**Build:** Set an original name as SVG text or outlined lettering in a 1326px by 267px viewBox. Combine a regular grotesk first segment with an italic light serif second segment when the name allows it; adjust horizontal fit without distorting stroke construction. Anchor it at the bottom of a 500px section with 240px of upper breathing room and clip the lower edge.

### Wireframe architecture

**Only for:** technical explanations

**Use:** Diagram half of an architecture section.

**Observed:** Fine mint isometric outlines build stacked rectangular towers against a deep forest panel. Tiny uppercase labels sit on faces; the neighboring white column contains numbered explanations.

**Transfer:** Represent the new system's actual layers as connected orthogonal volumes, not decorative sci-fi machinery.

**Build:** Draw SVG cube outlines with 1px–2px mint strokes, no fill, on forest. Use three consistent axis directions and vary tower heights; place concise labels on top faces. Keep the diagram in a broad 600px-scale panel.

### Spatial identity cloud

**Only for:** interactive directories

**Use:** The main directory exploration area.

**Observed:** Circular partner identities float in a deep green field, varying dramatically in size and overlap. Some are crisp in the foreground while distant ones blur or dim. Native logo colors provide localized blue, orange and purple without changing the marketing palette.

**Transfer:** Use legitimate new ecosystem identities in a spatial cloud; do not turn it into a uniform card grid.

**Build:** Place circular image planes in an SVG or canvas scene across a 1408px by 1260px region. Stagger centers loosely around a broad oval, use varied diameters and z-order, and reduce opacity or add soft blur with simulated depth. Keep the category strip above the scene.

### Documentary mosaic

**Only for:** community and culture pages

**Use:** Human evidence following an organization introduction.

**Observed:** Wide candid images show people working, presenting and gathering in real spaces. Natural window light, greenery and muted interiors keep the photography grounded; warmer event scenes remain localized. A near-full-width introductory image gives way to alternating broad and narrow 400px-high frames with 12px gutters and 8px corners.

**Transfer:** Show real people and activity in the new organization, retaining natural framing and varied image widths rather than stock portraits.

### Edge character cameo

**Only for:** community and culture pages

**Use:** A playful transition before the monumental ending.

**Observed:** A small illustrated animal paw in a green sleeve peeks from the right edge of a wide pale field; dark outlines and a small pink detail make this a localized exception to the institutional tone.

**Transfer:** Use a brief original character detail tied to the new community, staying mostly outside the frame.

**Build:** Draw a compact outlined SVG hand, tool or mascot fragment in a muted green sleeve. Clip it at the right edge of a 361px-high field, leaving most of the region free of illustration.

### Icons

**Observed:** Small 16px directional arrows and chevrons are simple and unobtrusive. Partner identities appear at 32px–40px; technical utility illustrations use larger 56px mint outlines.

**Transfer:** Choose plain arrows for navigation and thin geometric outline symbols for technical concepts. Keep colored partner identities inside the resource and directory contexts.

## Section recipes

How recurring sections are built.

### First screen: Editorial promise above living matter

**Observed:** The Porcelain canvas sits behind Floating navigation with its blocks 24px from the top and 48px from the sides. After a 280px upper rest, the two-line 80px serif headline occupies the left half, up to 640px wide; an 18px support line occupies a 440px block on the right, with a Primary button 36px below it. The text field ends around 488px. A faint horizontal identity strip then spans the page, followed at 576px by the 1440px-wide, 540px-high Point-cloud matter stage. Within the first 900px, the whole headline, support and action are visible, plus the upper part of the dark particle landscape; the lower artwork and proof figures fall below the fold.

**Transfer:** Write a short infrastructural promise and keep its explanation separate. Replace the source landscape with an original mint wave or product-shaped point field if bespoke media is unavailable. Technical and organization pages instead use the statement-opening recipe across the wide frame, with a tiny first-line topic indent; directory pages use that composition reversed on forest.

**Avoid:** Do not center everything into a conventional stacked SaaS hero, shrink the art to a card, or place a dense product dashboard behind the opening words.

**Text style:** `display` — Teodor 300 · 80px/1.05 · tracking -0.03em

### Specimen and statement

**Observed:** A 224px Point-cloud matter specimen sits at the left edge of the 800px reading column. After 72px, a muted eyebrow precedes a 36px chapter statement by 16px. Supporting Body copy follows by 32px; a Secondary button or Primary button can sit 72px after the text. The enclosing Chapter lane supplies 80px side insets.

**Transfer:** Use one strong capability or explanation per specimen chapter; align art and copy rather than centering them.

**Text style:** `heading` — ABC Diatype 400 · 36px/1.2 · tracking -0.03em

### Product proof and resources

**Observed:** A compact market strip leads into the Textured product stage and Translucent product window. The large interface is deliberately clipped within the 960px lane. A Resource row list follows under a muted label with 32px spacing.

**Transfer:** Pair an actual demonstration with a short directory of related tools or integrations; use only meaningful adjacent resources.

### Compact quantified proof

**Observed:** The Quantified proof strip follows a large dark art field. Four 24px figures with small uppercase labels share a 960px lane and only 24px vertical padding.

**Transfer:** Treat statistics as quiet corroboration of the promise, not as a second hero.

### Atmospheric editorial rail

**Observed:** The Editorial atmosphere spreads edge-to-edge. A small particle specimen introduces a sequence of 40px serif declarations within the 800px lane; 24px Square sequence markers occupy a separate left rail. Paragraphs are separated by 56px with 160px upper and about 200px lower breathing room. Their emphasis changes along the passage while fine vertical rails hold the layout.

**Transfer:** Use the device for a sustained point of view or product philosophy, with an appropriate number of declarations rather than reproducing specific topics.

**Text style:** `editorial` — Teodor 300 · 40px/1.15 · tracking -0.03em

### Questions and typographic sign-off

**Observed:** A pale point-wave interlude introduces an 800px FAQ group with a muted label, 32px gap and four 72px FAQ rows separated by 4px. The Monumental closing name then fills the lower part of a 500px pale field before Footer columns in a 284px band. Technical and organization endings retain the same name-and-footer construction without requiring FAQ; the dark directory uses mint lettering and a mint footer.

**Transfer:** Resolve uncertainties where useful, then end with the oversized original name and sparse utility links rather than appending another oversized conversion panel.

### Split architecture and utility band

**Only for:** technical pages

**Observed:** The wide architecture section pairs a 600px white explanation column with a dark wireframe diagram region. Numbered compact text aligns to its layers. A later Forest stage combines a broad particle illustration and 36px statement with a three-column utility grid; a lower cell can span two columns.

**Transfer:** Explain actual system structure first, then map it to practical capabilities.

**Text style:** `technical-body` — ABC Diatype 400 · 16px/1.4 · tracking -0.01em

### Numbered organization chapters

**Only for:** organization pages

**Observed:** Wide pale chapters place a small sequence number above a two-column heading/prose split. Headings use 36px grotesk; narrative occupies the right column and may continue into News row or Resource row lists. Chapters use 40px top padding, an 80px number-to-heading interval and 120px bottom padding; documentary images break the sequence.

**Transfer:** Describe the new organization's actual groups, programs or contributors without forcing every chapter into a card.

**Text style:** `heading` — ABC Diatype 400 · 36px/1.2 · tracking -0.03em

### Directory as a spatial scene

**Only for:** interactive directories

**Observed:** A 64px white serif statement opens on forest with 280px top padding. Category tabs sit near the top of a 1408px-wide Spatial identity cloud; the scene remains open and layered instead of segmented into tiles.

**Transfer:** Give users a short functional explanation before exploring identities by category.

**Text style:** `statement-opening` — Teodor 300 · 64px/1.05 · tracking -0.03em

## Page flow

**Storyline:** Promise → visual world → practical demonstration and proof → deeper explanation or participation → typographic sign-off and utility navigation.

### Broad product or infrastructure landing page

1. **Promise** — Split serif headline and support/action above an identity strip and immersive particle landscape.
2. **Quantified proof** — Small four-metric row supports the opening claim.
3. **Product demonstration** — A specimen-led capability statement introduces a textured interface stage and adjacent resource rows.
4. **Capability chapters** — Particle specimens introduce integration and technical explanations, interrupted by a full-width editorial atmosphere.
5. **Credibility and objections** — News rows, a particle-wave interlude and a compact FAQ.
6. **Brand sign-off** — Monumental name above a forest footer.

**Transfer:** Adapt the mix of proof, demonstration and chapters to the new product while retaining the specimen art, atmospheric contrast and oversized ending.

### Technical explanation and architecture page

1. **Technical promise** — Wide 64px serif statement with an inline documentation action.
2. **System explanation** — Numbered white explanation column paired with mint-on-forest isometric architecture.
3. **Trust and resources** — Particle globe above a substantial security statement, then explorer rows.
4. **Utility explanation** — Dark particle stage and a fine-divided capability grid.
5. **Brand sign-off** — Pale monumental name field and forest footer.

**Transfer:** Move from structure to assurance to practical uses, using the split diagram and dark grid as scoped technical devices.

### Ecosystem or integration directory

1. **Orientation** — White editorial statement on a fully forest canvas.
2. **Exploration** — Compact category strip over a spatial cloud of circular identities.
3. **Brand sign-off** — Mint monumental name on forest, followed by a mint footer with dark links.

**Transfer:** Use the dark immersive variant for spatial exploration, not as the default landing-page theme.

### Organization and community narrative

1. **Orientation** — Wide serif statement, a subdued organization identity strip and a near-full-width documentary image.
2. **Human proof** — Numbered split chapter and alternating wide/narrow photo mosaic.
3. **Organization explanation** — Repeated numbered chapters pairing headings with prose, occasional actions, news and contributor rows.
4. **Personality** — Small illustrated edge cameo within a pale transition.
5. **Brand sign-off** — Monumental name above the same forest utility footer.

**Transfer:** Replace the source's groups with the new organization's actual structure and real documentary material; keep the culture-specific photography and cameo scoped here.

## Writing

Direct, ambitious and technically literate. Broad institutional promises are followed by concrete mechanisms and restrained factual support, not exuberant sales language.

**Do not copy:** Do not reuse Hyperliquid names, logo forms, mascot, ecosystem identities, financial claims, network statistics, founder details, news titles or quotations as new-product content. Examples illustrate voice only.

- **Addressing the reader:** Mostly impersonal product-led statements; actions use direct verbs. Long-form declarations explain the system's intent without a chatty 'we' or repeated 'you'.
- **Rhythm:** Short declarative landing promises alternate with sentence-length chapter statements and denser explanatory paragraphs. Labels and actions are brief uppercase units; prose stays sentence case without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name an ambitious category-level purpose, not a list of features. | About 5–8 words | “Infrastructure to House All Finance” |
| Support line | Concrete category breadth, then an operational distinction. | Two compact sentences | “Markets for crypto, commodities, indices, and FX. Open 24/7 onchain, without intermediaries.” |
| Chapter label | A short functional topic in uppercase. | 1–6 words | “Trade everything in one place”<br>“Security” |
| Chapter heading | A direct product action or an explanatory sentence. | 2–25 words | “Integrate [Brand]”<br>“HYPE is the native token of the [Brand] blockchain.” |
| Primary and secondary actions | Simple imperative; explain destination or next step. | 1–3 words | “Trade”<br>“Start building”<br>“Read the docs” |
| Question | Ask the basic practical question in the reader's terms. | 4–7 words | “What makes [Brand] unique?” |

**Words and phrasing to use:** infrastructure; purpose-built; supports; access; integrate; open; transparent; independent; build; secured by

**Avoid:** revolutionary magic; effortless everything; supercharge; game-changing; to the moon; exclamation-heavy slogans

**Rules:**

- Follow a broad claim with the actual mechanism that makes it credible.
- Use specific operational nouns and verifiable measures where relevant, without inventing proof.
- Let short labels orient longer explanations; do not turn every heading into a punchline.
- Keep calls to action literal and destination-aware.

## Do's and Don'ts

### Do

- Keep the default canvas cool porcelain with forest ink, allowing dark bands to punctuate rather than blanket the landing page.
- Pair 80px light serif promises with 18px regular grotesk explanations.
- Hold chapter copy to an 800px lane inside a 960px frame with 80px side insets.
- Preserve 48px control height and 12px corner radius across mint and gray actions.
- Include coherent point-cloud matter at immersive and specimen scales.
- Make numbered editorial passages feel like a rail: 24px square markers alongside 40px serif statements.
- Finish with a broad 1326px-scale name composition seated on the footer boundary.
- Use 64px resource rows for adjacent tools rather than a wall of raised cards.

### Don't

- Do not substitute bold geometric display lettering for the 300-weight serif opening.
- Do not turn the 12px-radius buttons into capsules or oversized full-width bars.
- Do not spread mint across every paragraph, card and icon; its role is concentrated action and light.
- Do not enlarge 24px proof figures into competing display headlines.
- Do not add generic soft drop shadows to white questions or neutral navigation blocks.
- Do not import the colored directory identities into the main marketing palette.
- Do not use a dense tiled partner grid in place of the scoped spatial cloud.
- Do not make the footer a sprawling sitemap; two small link groups and a left emblem carry it.

## Motion and responsive

### Motion

**Observed:**

- A market ticker declares a 55s linear infinite scroll.
- Resource rows declare background-color 0.2s transitions.
- Inline highlighted links declare 0.15s color, background-color, border-radius and corner-shape transitions with cubic-bezier(0.44,0,0.56,1).
- Editorial declarations vary in opacity and slight vertical position along the long green passage; particle artwork is presented as video or canvas.

**Transfer:**

- Use the slow horizontal ticker as a subtle utility strip, not a fast marquee of promotional copy.
- Keep the point-cloud silhouette readable through motion; the static form must carry the same composition.
- For a static editorial version, retain clear text contrast and marker hierarchy rather than freezing the dimmed transition state.

**Unknown:**

- Exact particle animation implementation, scroll-trigger timing and editorial opacity curves are not specified.

### Responsive

**Observed:**

- Declared width boundaries include 420px, 480px, 810px, 1025px and 1380px; technical layouts also declare 960px.

**Transfer:**

- On narrow screens, stack the promise and support in reading order while retaining the art as a broad lower stage.
- Let the closing name fit the width as artwork, keeping its low position against the footer.
- Collapse wide chapter and organization splits into a single reading lane; retain specimen-to-copy hierarchy and allow directory tabs to scroll horizontally.

**Unknown:**

- Exact mobile type sizes, navigation transformation and breakpoint-specific layout rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
