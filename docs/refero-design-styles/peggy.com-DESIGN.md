# Peggy — gallery walls, looping lines

## Overview

An approachable gallery sensibility pairs fine, light serif headlines with matter-of-fact sans-serif labels. The mostly white and pale gray architecture gives rich paintings, candid people and oversized phone demonstrations the color and attention. Black conversion bands and loose looping lines add a distinctive graphic counterpoint. It suits cultural marketplaces, creative tools and community-led products with spacious storytelling and compact browsing metadata.

### Essentials

- A literary welcome beside a human-scale image: equal-width hero halves, a 72px/1 Reckless headline at weight 300, and a full-height portrait or product scene; the left half ends in a black action shelf.
- Gallery walls rather than floating cards: white rectangular modules on #f4f4f4, separated by 8px seams, with 48px desktop internal padding and no rounded panel corners.
- The interface stays monochrome while the exhibits supply the color: white and gray dominate structural areas, #141414 is reserved for actions and conversion bands, and saturated color lives primarily inside imagery.
- Buttons are cut rectangles, not soft capsules: the hero action is white on black, 64px high with 20px 24px padding; the header action is black, 38px high with 8px 32px padding and a 1px border.
- Objects are presented like an exhibition: 288px-wide browsing items with 24px gaps, preserved image proportions, small 12px/16px metadata, and a partially visible next item rather than a compressed grid.
- A continuous drawn line connects the experience: broad unfilled loops thread behind product scenes and return as subdued arcs on a #141414 closing panel with a centered 60px/1 serif invitation. Recreate the loops even when the product has no illustrative assets.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action charcoal | `#141414` | `--color-charcoal` | text, background, action | Dark bands, filled actions, object metadata and line drawings. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gallery white | `#ffffff` | `--color-white` | surface, text, action | Main panels and inverted text or actions on charcoal. |
| Headline black | `#000000` | `--color-ink` | text | Serif headings and general text. |
| Editorial gray | `#666666` | `--color-muted` | text | Paragraphs, biographies and secondary labels. |
| Muted inverse | `#b9b9b9` | `--color-inverse-muted` | text | Closing support text: white at 70% opacity over charcoal. |
| Cool banner text | `#e2e8f0` | `--color-banner-text` | text | App-install banner title, support text and download symbol. |
| Profile hairline | `#eeeeee` | `--color-profile-edge` | border | Fine perimeter around community profile cards. |
| Seam gray | `#f4f4f4` | `--color-canvas` | background, border | Outer canvas and exposed gutters between white panels. |
| Media backing | `#f9f9f9` | `--color-media` | surface | Light neutral backing for demonstration imagery and avatars. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| performance and resale modules | Data label gray | `#6b7280` | `--color-data-label` | text | Labels and explanations inside performance comparisons. |
| performance and resale modules | Data outline | `#d1d5db` | `--color-data-edge` | border | Performance card edges and media dividers. |
| performance and resale modules | Data strip | `#f3f4f6` | `--color-data-fill` | surface | Shallow comparison strip within a performance card. |
| performance and resale modules | Positive return | `#15803d` | `--color-positive` | text | Small positive return percentages; not a marketing accent. |

## Typography

- **Reckless** — Hero, editorial chapter headings, profile names and article titles. Fine, high-contrast contemporary serif with delicate hairlines, open counters and a conversational editorial character. If unavailable, use **Newsreader**. Use 300 for large headings and 400 for small editorial titles; preserve natural tracking. Font stack: "Reckless", "Newsreader", ui-serif, Georgia, Cambria, 'Times New Roman', Times, serif.
- **Inter** — Paragraphs, browsing headings, navigation, actions and metadata. Neutral sans-serif with an efficient, compact small-text texture. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **Monument Grotesk** (only for institutional proof and small footer notation) — Stat numerals and understated copyright notation. Plain, unembellished grotesk; the figures read as sans-serif, not a decorative display face. If unavailable, use **Public Sans**. Use regular 400 for the compact stat treatment. Font stack: "Monument Grotesk", "Public Sans", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Reckless | 300 | 72px | 1 | normal | Default marketing opening headline, broken into a few readable lines. |
| heading-lg | Reckless | 300 | 60px | 1 | normal | Editorial feature chapters and dark closing invitation. |
| heading | Reckless | 300 | 48px | 1 | normal | Shorter split-feature headings and paired editorial cards. |
| heading-small | Reckless | 300 | 36px | 40px | normal | Audience pathways and centered institutional-proof introductions. |
| collection-heading | Inter | 400 | 24px | 32px | -0.025em | Browsing rails: modest title with a small action at the opposite edge. |
| profile-name | Reckless | 400 | 24px | 1 | normal | Community card display names. |
| shelf-title | Reckless | 400 | 24px | 32px | normal | Short conversion sentence in the hero action shelf. |
| article-title | Reckless | 400 | 20px | 1.25 | normal | Editorial story titles below square imagery. |
| body | Inter | 400 | 16px | 1.5 | normal | Main explanatory copy and contextual text links. |
| label | Inter | 500 | 16px | 1.5 | normal | Main action labels, footer column headings and sentence-case eyebrows. |
| small | Inter | 400 | 14px | 20px | normal | Biographies, footer links and dense explanations. |
| small-action | Inter | 500 | 14px | 20px | normal | Compact header action, trust labels and browsing links. |
| caption | Inter | 400 | 12px | 16px | normal | Object creator, title, price and short supporting metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| institutional proof | stat | Monument Grotesk | 400 | 36px | 40px | normal | Centered proof numerals above explanatory captions. |
| app distribution notices | banner-title | Reckless | 400 | 20px | 28px | normal | Utility banner title. |
| catalog discovery | filter-heading | Inter | 400 | 20px | 28px | -0.025em | Heading for compact browse-by groups. |
| performance and resale modules | metric | Inter | 600 | 14px | 20px | normal | Prices and return percentages in comparison cards. |

**Notes:**

- Large serif type is light, not bold, with line height equal to size; do not tighten its tracking. Its character comes from stroke contrast and line breaks.
- Sans-serif collection headings use -0.025em tracking while paragraphs and labels retain normal tracking.
- Eyebrows remain sentence case and use the label recipe rather than tracked capitals. Body copy is muted; headline black and action charcoal remain distinct roles.

## Layout

**Density:** Airy editorial panels with compact metadata: large media fields and 48px insets contrast with 12px captions and tight footer lists.

### Spacing

**Spacing system:**

- **horizontal-step** 16px, horizontal — Primary inset increments: 16px, 32px and 48px. Rail gaps and panel seams use separate smaller values.

| Value | Use |
| --- | --- |
| 8px | Panel seams, heading-to-support spacing in audience pathways, icon-to-label gap. |
| 16px | Small panel padding, metadata and footer-heading separation. |
| 20px | Editorial heading-to-paragraph gap and main action vertical padding. |
| 24px | Rail gaps, trust-tile vertical padding and title-row bottom margin. |
| 32px | Audience-pathway action separation and compact button horizontal padding. |
| 40px | Hero shelf vertical padding and proof-grid gaps. |
| 48px | Desktop panel inset, white-section padding and closing action separation. |
| 80px | Institutional statement and story-section vertical padding. |
| 96px | Closing panel vertical padding. |
| 128px | Institutional-proof logo band top padding. |

### Containers and grids

- **main-container**: max width 1280px · side padding 16px. Centered outer container. At a 1440px viewport its inner module width is 1248px, leaving visible pale gray side margins.
- **split-feature**: 2 columns · gap 0px · side padding 48px. Equal white text and image halves; text is vertically centered and inset, while imagery touches the panel boundaries.
- **browsing-rail**: gap 24px · side padding 48px. Horizontal scrolling flex row of 288px items; show about four items plus continuation, not five squeezed columns.
- **trust-grid**: 6 columns · gap 8px. Equal white cells across the main module.
- **footer-grid**: max width 1280px · 5 columns · gap 8px · side padding 16px. Independent white navigation columns, followed by a full-width white legal/social strip.
- **proof-grid** (only for institutional proof): max width 1024px · 4 columns · gap 40px. Centered, unboxed statistic columns.
- **story-column** (only for company storytelling): max width 672px. Narrow long-form founder narrative beneath a wide image and avatar chain.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | panels-and-primary-actions | 0px |
|  | avatars | 9999px (pill) |
| performance and resale modules | offer-action | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| avatar-inset | `inset 0px 2px 4px 0px rgba(0, 0, 0, 0.05)` | Subtle inner definition on circular community avatars; not a general panel shadow. |

### Surfaces

#### Canvas · level 0

**Use:** Background visible as outer margins and modular seams.

**CSS:** `background: #f4f4f4`

**Observed:** The gray is structural rather than a decorative colored section.

**Transfer:** Keep white modules sharply separated by the exposed canvas.

#### Gallery panel · level 1

**Use:** Default editorial, browse and footer module.

**CSS:** `background: #ffffff; border-radius: 0px; box-shadow: none`

**Observed:** Flat, rectangular and largely borderless; panels are separated by gutters instead of elevation.

**Transfer:** Let media and type establish hierarchy.

#### Media stage · level 1

**Use:** Backing for phone scenes and graphic compositions.

**CSS:** `background: #f9f9f9; overflow: hidden`

**Observed:** Neutral backing nearly merges into the white panel, with hard edge cropping for tall demonstration scenes.

**Transfer:** Use this backing behind an oversized product object and a looping line.

#### Conversion band · level 1

**Use:** Hero action shelf and closing panel.

**CSS:** `background: #141414; color: #ffffff; border-radius: 0px`

**Observed:** The shelf is plain; the closing panel adds low-contrast overscale looping arcs.

**Transfer:** Use dark surfaces for a decisive action rather than making every feature dark.

#### Video legibility veil · level 2

**Use:** Lower edge of the hero portrait video.

**CSS:** `background: linear-gradient(to top, rgba(20, 20, 20, 0.4), rgba(20, 20, 20, 0))`

**Observed:** A transparent-to-dark veil supports the white play symbol and caption at the lower left.

**Transfer:** Keep the face visible and let the overlay fade away above the control.

#### Comparison strip · level 1

**Only for:** performance and resale modules

**Use:** Price and return comparisons within an outlined card.

**CSS:** `background: #f3f4f6; padding: 10px`

**Observed:** Three small aligned data groups sit side by side; surrounding explanation rows stay white.

**Transfer:** Use only for genuinely comparable quantities.

## Components

### Navigation

**Use:** Persistent minimal brand and conversion header.

**CSS:** `height: 80px; background: #ffffff; border-bottom: 8px solid #f4f4f4; padding: 16px 48px; display: flex; align-items: center; box-sizing: border-box`

**Observed:** A small line-drawn brand symbol sits left; the Compact action sits at the far right. The containing header is sticky at the top with z-index 10. There is no visible full navigation menu.

**Transfer:** Use the new product's small symbol with substantial empty space between identity and action.

### Compact action

**Use:** Header conversion.

**CSS:** `background: #141414; color: #ffffff; border: 1px solid #141414; border-radius: 0px; padding: 8px 32px; height: 38px; box-sizing: border-box; display: inline-block; text-align: center`

**Text style:** `small-action` — Inter 500 · 14px/20px

**Observed:** A compact black rectangle, visually subordinate to the main page action.

### Primary action

**Use:** Hero shelf conversion and dark-panel invitation.

**CSS:** `background: #ffffff; color: #141414; border: 0px; border-radius: 0px; padding: 20px 24px; height: 64px; display: block; text-align: center; box-sizing: border-box`

**Text style:** `label` — Inter 500 · 16px/1.5

**Observed:** The default sits on the right side of the hero shelf. Closing actions widen horizontal padding to 40px. A catalog introduction reverses to charcoal with white text and uses 12px 40px padding for a 48px height.

**Transfer:** Keep one clear action per invitation; width follows the label and padding.

### Browse link

**Use:** Secondary action opposite a collection title.

**CSS:** `color: #141414; background: transparent; display: block; text-decoration: none`

**Text style:** `small-action` — Inter 500 · 14px/20px

**Observed:** Text only, aligned to the far edge of the title row; no arrow or surrounding pill. Contextual editorial links instead use the body recipe.

### Trust tile

**Use:** Compact reassurance strip near the beginning or closing action.

**CSS:** `background: #ffffff; padding: 24px 16px; display: flex; flex-direction: column; align-items: center; text-align: center`

**Text style:** `small-action` — Inter 500 · 14px/20px

**Observed:** One solid black 40px pictogram above a single short label, separated by 8px. Repeated equal cells form a six-column strip.

**Transfer:** Use concise operational assurances appropriate to the product.

### Collection rail

**Use:** Object-led browsing and curated proof.

**CSS:** `display: flex; gap: 24px; padding: 0px 48px 48px; overflow-x: scroll; align-items: stretch`

**Text style:** `caption` — Inter 400 · 12px/16px

**Observed:** Each item is 288px wide. Unboxed imagery retains its own proportions and is centered within the shared media zone; creator, title and price align below. A title row precedes the rail by 24px. Catalog variants use 280px items and add circular follow/save controls.

**Transfer:** Use finished outputs, objects or customer projects as the exhibits; retain their distinct silhouettes.

### Profile card

**Use:** Community members and partner discovery.

**CSS:** `width: 288px; border: 1px solid #eeeeee; border-radius: 0px; display: block`

**Text style:** `profile-name` — Reckless 400 · 24px/1

**Observed:** Square cover image above an overlapping 64px circular avatar with a 2px white edge. The padded text region begins 48px up into the cover; below the avatar come serif name, small handle and a short biography. Cards stretch to a shared height.

**States:** Declared: hover border-color rgb(223 227 232/1); focus-visible not specified.

**Transfer:** Choose an expressive project cover and a genuine person or organization avatar.

### Footer column

**Use:** Grouped navigation at the page ending.

**CSS:** `background: #ffffff; padding: 48px`

**Text style:** `label` — Inter 500 · 16px/1.5

**Observed:** Five white columns separated by gray seams. A medium sans-serif heading precedes a tight stack of small black links by 16px. A separate shallow white strip carries copyright left and three 24px social symbols right.

**Transfer:** Organize a small useful link set rather than a dense sitemap.

### Editorial article card

**Use:** Related stories and educational content.

**CSS:** `width: 288px; display: block; border: 0px`

**Text style:** `article-title` — Reckless 400 · 20px/1.25

**Observed:** Square editorial image, small muted author line and a serif title. The cards share the Collection rail spacing and avoid ornamental card shells.

**States:** Declared: hover text-decoration-line underline; focus-visible not specified.

**Transfer:** Use specific, curious story titles and images that reward browsing.

### Performance card

**Only for:** performance and resale modules

**Use:** Evidence-rich comparison of an object and its transaction history.

**CSS:** `display: flex; flex-direction: column; border: 1px solid #d1d5db; border-radius: 0px`

**Text style:** `small` — Inter 400 · 14px/20px

**Observed:** Media first, then creator identity with a small return figure at right, Comparison strip, a conditional explanation, and current-owner row with a black pill Offer action. Uses a three-column grid with 24px gaps; green is restricted to positive figures.

**Transfer:** Keep the evidentiary sequence and replace financial fields only with relevant, verifiable metrics.

### Category tile

**Only for:** catalog discovery

**Use:** Visual browse-by selector.

**CSS:** `display: block; padding: 16px; background-size: cover; background-position: 100% 100%; aspect-ratio: 1 / 1; border: 0px`

**Text style:** `small-action` — Inter 500 · 14px/20px

**Observed:** A 164px square tile with a text label at its upper edge, repeated in a three-column group with 16px gaps; category and price groups occupy adjacent white panels.

**Transfer:** Use a subtle representative image or texture, with enough separation for the label.

### Distribution notice

**Only for:** app distribution notices

**Use:** Installation prompt immediately below the header.

**CSS:** `background: #141414; color: #e2e8f0; padding: 16px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `banner-title` — Reckless 400 · 20px/28px

**Observed:** A 96px-high band with dismiss control, a 64px app symbol, serif title and small installation instruction; a cloud-download symbol sits at the far right.

**Transfer:** Use only when installation is a real primary entry point.

## Imagery and graphics

### Human introduction

**Use:** Default marketing hero right half.

**Observed:** A close, naturally lit portrait video fills the entire 624px-wide half, cropped around face and shoulders. Muted pale green surroundings and everyday clothing make the scene personable rather than glossy. White playback control and a short caption sit low over the image.

**Transfer:** Use a candid maker, customer or host in a real setting. If no video exists, use one strong photographic portrait with the same close framing; do not simulate playback on a still.

### Exhibition objects

**Use:** Browsing rails and output-led proof.

**Observed:** Highly varied painting, collage and photographic subjects provide saturated blues, yellows, reds and greens against white. Rectangular works, circular frames and irregular objects retain their boundaries; images have no uniform tint or forced aspect ratio. Tiny captions yield attention to the work.

**Transfer:** Use real product outputs or carefully photographed objects. The minimum equivalent is a small set of high-quality, clearly differentiated finished examples, presented on white without decorative backgrounds.

### Loop-thread product scene

**Use:** At least one major demonstration or illustrative scene.

**Observed:** Oversized upright phone hardware is cropped at the panel edge on an almost-white backing. Broad black unfilled loops pass behind the device; interface content is secondary to the device silhouette and colorful examples. Other compositions use floating profile panels, an audio card or an avatar field with the same thread.

**Transfer:** Replace phones with the product's natural object or a few carefully composed UI panels. Without a rich interface, use one clear output image and an oversized framing object, keeping the line behind it.

**Build:** Use an SVG viewBox of 0 0 608 711 behind the main object. Draw two or three open cubic Bezier paths with no fill, a #141414 stroke about 6px wide, and sweeping loops that enter and exit different edges. Place the main object centrally in front, occupying roughly two thirds of the panel width and almost its full height. Clip the complete composition to the rectangular Media stage; avoid closed concentric rings.

### Dark looping arcs

**Use:** Signature background of the closing conversion panel.

**Observed:** Enormous low-contrast curves traverse a charcoal field, cropped well beyond the panel edges. They are spare, smooth and drawn, not a mesh, glow or noisy texture.

**Transfer:** Always retain a graphic line counterpart to the product scene, while allowing the invitation to remain the focal point.

**Build:** On #141414, position an absolute SVG with a 1248 by 420 viewBox and hidden overflow. Draw three or four off-center cubic arcs, no fill, stroke rgba(255,255,255,0.12), about 8px wide. One curve rises from lower left to above the upper middle, another sweeps down from upper middle toward the right, and one broad arc crosses the bottom. Keep foreground text and action above this layer.

### People and testimony collage

**Only for:** community and trust storytelling

**Use:** Social proof feature panels.

**Observed:** Circular portraits form a close repeating field; elsewhere white quote cards pair a portrait column with serif quotation text. Black looping lines run behind the collage, which fills an entire feature half.

**Transfer:** Use real community imagery or two to three permissioned customer quotations; keep portrait colors natural, with white cards and charcoal type.

### Company line diagrams

**Only for:** company and mission storytelling

**Use:** Conceptual illustration opposite an editorial statement.

**Observed:** Minimal black-outlined circles, thin pale connectors and near-white backing. One panel shows a central open node radiating to smaller nodes; another shows alternating dark and faint circles passing horizontally across the field.

**Transfer:** Turn the new organization's abstract purpose into a simple relationship, expansion or access diagram rather than adding generic business stock art.

**Build:** For a 608px by 711px panel, center an open 28px circle with a 3px charcoal stroke. Connect it with 1px rgba(20,20,20,0.12) lines to roughly twelve irregularly spaced 12px open circles. For an amplification variant, replace the network with a horizontal chain of open circles of varied diameters, alternating charcoal and faint outlines, clipped at both edges.

### Team panorama

**Only for:** company storytelling

**Use:** Centered introduction and founder narrative.

**Observed:** A wide natural-color group photograph spans the module; a white looping line overlays its edges. A later horizontal chain of 56px circular portraits overlaps by 12px above a narrow text column.

**Transfer:** Use a genuine environmental group portrait, then a compact portrait chain to make the organization feel human.

### Icons

**Observed:** Trust pictograms are chunky black silhouettes in 40px boxes: recognizable objects, not fine-line generic feature badges. Play controls are white, 48px, on the portrait. Social icons are 24px; app-banner symbols use the cool pale text color.

**Transfer:** Choose a coherent solid pictogram family for reassurance and keep line art for the signature thread and brand identity. Do not mix colored icon badges into the monochrome modules.

## Section recipes

How recurring sections are built.

### First screen: Portrait and action-shelf opening

**Observed:** The first 900px contain an 80px sticky Navigation, a 96px Distribution notice, then an approximately 671px-tall split hero. At desktop the module is 1248px wide. Its left half has a vertically centered white editorial area with 48px inset, a 72px/1 light serif headline spanning about three lines, and muted body copy beneath with 20px separation. A 144px charcoal shelf anchors the base of that half, placing a short serif conversion sentence left and Primary action right. The right half is one full-height portrait video with a lower-edge Video legibility veil, play control and caption. Layers are gray canvas, white/charcoal modules, portrait, then controls. The complete headline, supporting copy, action and face fit above the fold; only the start of the reassurance strip is visible below.

**Transfer:** Default new marketing pages use this balanced editorial-and-human composition. Replace the portrait with a real person or a purposeful Loop-thread product scene if the product has no human footage. Audience-specific pages retain the split and shelf but shorten the promise. Catalog pages instead open with a left-aligned 60px serif promise and dark action over white before the first rail; company pages use a centered 60px statement and wide team image.

**Avoid:** Do not replace the equal halves with a centered SaaS headline over a small dashboard, put the action in a floating pill, or shrink the main image into a rounded thumbnail.

**Text style:** `display` — Reckless 300 · 72px/1

### Alternating editorial feature

**Observed:** Equal-width image and text halves on Gallery panel, generally 608px by 711px for each side in inset variants. Full-height photography or Loop-thread product scene meets a vertically centered text block with 48px padding. Text uses heading-lg, body and an occasional contextual link; consecutive chapters swap sides and retain 8px horizontal seams.

**Transfer:** Explain one user benefit per chapter, pairing the statement with a visible mechanism or an evocative real-world use.

**Text style:** `heading-lg` — Reckless 300 · 60px/1

### Curated browsing rail

**Observed:** A Collection-heading and Browse link share one horizontal title row with 48px side insets. Collection rail follows after 24px; natural object proportions occupy most of the module, with caption text below. Editorial article and Profile card variants use the same rail infrastructure.

**Transfer:** Use curated outputs or customer projects as visual evidence. A new landing page can use a single strong rail instead of repeating catalog categories.

**Text style:** `collection-heading` — Inter 400 · 24px/32px · tracking -0.025em

### Looped closing invitation

**Observed:** Conversion band with Dark looping arcs, 96px vertical and 48px side padding. Centered heading-lg sits in a maximum 512px headline block; muted inverse body support follows, then Primary action after 48px. The rectangular module remains framed by the same gray canvas as the rest of the page.

**Transfer:** Finish with a short invitation that returns to the visitor's desired outcome. Reuse the thread motif even for products with little imagery.

**Text style:** `heading-lg` — Reckless 300 · 60px/1

### Audience pathways and footer

**Observed:** Two white audience-pathway panels separated by 8px, with 48px insets, 36px serif titles, an 8px support gap and contextual links 32px below. Footer column modules follow, with a separate legal/social strip. Some endings place Trust tiles between the closing invitation and these pathways; audience-specific and company endings go directly from trust strip to footer.

**Transfer:** Offer alternate routes only when the product serves distinct audiences. Preserve the light modular footer rather than extending the dark call-to-action into the whole ending.

**Text style:** `heading-small` — Reckless 300 · 36px/40px

### Paired capability cards

**Only for:** feature-overview pages

**Observed:** Two equal Gallery panels separated by 8px, each with a wide media composition above a 48px-inset heading and body. The image-to-copy transition is hard-edged; the pair shares the visual thread across the upper media fields.

**Transfer:** Pair two complementary activities, using one connected illustration to unite them.

**Text style:** `heading` — Reckless 300 · 48px/1

### Institutional endorsement band

**Only for:** institutional proof

**Observed:** A centered 36px serif introduction sits over six monochrome institutional logos. The canvas stays pale gray, with 128px top padding, a 56px gap to logos and substantial bottom space; no individual logo cards.

**Transfer:** Use recognizable permissioned proof marks, balanced by visual weight rather than stretched to equal widths.

**Text style:** `heading-small` — Reckless 300 · 36px/40px

### Statement with small statistics

**Only for:** institutional proof

**Observed:** Gallery panel with 80px vertical padding. Centered 48px serif statement and body support precede a four-column proof grid by 80px. Each unboxed column has a regular 36px grotesk number, an 8px gap and centered 14px explanation. Grid maximum width is 1024px with 40px gaps.

**Transfer:** Present a few defensible facts that explain the problem or purpose, rather than oversized celebratory counters.

**Text style:** `stat` — Monument Grotesk 400 · 36px/40px

### Founder story

**Only for:** company storytelling

**Observed:** Centered label and 48px serif title, followed by a wide looping line with an overlapping avatar chain. A narrow narrative column below holds several continuous body paragraphs and a plain signed attribution; no testimonial speech bubble.

**Transfer:** Tell a concrete personal origin story, then connect it to the larger product purpose.

**Text style:** `heading` — Reckless 300 · 48px/1

## Page flow

**Storyline:** Welcoming promise → visible examples or mechanism → human and institutional reassurance → invitation → useful alternate paths and modular footer.

### Broad discovery landing page balancing a welcome with an exhibition of available outcomes

1. **Promise** — Portrait-and-shelf opening with a direct welcome and practical explanation.
2. **Reassurance** — Six small trust cells immediately after the hero.
3. **Visible proof** — Curated object rails and a more detailed comparison grid.
4. **Product demonstration** — Large paired-phone scene and editorial explanation.
5. **Discovery** — Browse-by groups, profiles, partners and editorial stories.
6. **Closing call** — Dark looping invitation, two audience pathways and five-column light footer.

**Transfer:** Use tangible examples to carry a broad product promise; shorten the number of rails to suit the amount of strong content.

### Audience-specific recruitment and qualification

1. **Audience promise** — Short split-hero declaration with portrait and signup shelf.
2. **Differentiation** — Alternating full-height product illustration and explanatory text.
3. **Use cases** — Plain list of practical activities beside real process photography.
4. **Objection handling** — Inventory, eligibility and economics chapters; small footnote for compatibility limits.
5. **Institutional proof** — Centered logo band on gray.
6. **Closing call** — Dark signup invitation, trust cells, then the modular footer without audience-pathway cards.

**Transfer:** Explain the value, show how it works, be explicit about fit and cost, and close with a tailored invitation.

### Catalog entry with a clear operating promise

1. **Promise** — Left-aligned 60px serif introduction, short operational explanation and dark action.
2. **Discovery** — Repeated curated rails organized by editorial selection and object category; small follow/save controls sit with metadata.
3. **Closing call** — Dark invitation, trust strip, two audience pathways and modular footer.

**Transfer:** Keep the opening compact enough for the first collection to enter the first screen; keep product color inside the objects.

### Explain the reasons to trust and adopt a product

1. **Promise** — Split hero with oversized product imagery and a bottom action shelf.
2. **Trust and mechanism** — Alternating chapters establish curation, authentication and community with images.
3. **Institutional proof** — Open logo band with a centered serif introduction.
4. **Capabilities** — Two adjacent media-led cards demonstrate complementary activities.
5. **Human proof** — Quote-card collage accompanies the economic benefit chapter.
6. **Closing call** — Dark invitation, trust strip, audience pathways and light footer.

**Transfer:** Answer distinct adoption concerns with visible mechanisms, not a generic feature checklist.

### Explain an organization's origin, purpose and point of view

1. **Identity** — Centered sentence-case label and 60px serif statement above a wide group photograph.
2. **Origin story** — Avatar chain, looping line and signed long-form narrative.
3. **Purpose** — Alternating 48px-heading chapters with spare circle-and-line diagrams.
4. **Quantified context** — Centered statement and four modest stat columns.
5. **Closing call** — Dark looping invitation, trust strip and light footer; no audience-pathway pair.

**Transfer:** Ground purpose in a concrete origin and show the surrounding problem with a few real facts.

## Writing

Welcoming cultural fluency without gatekeeping. The voice moves easily between friendly invitations and clear explanations of how things work, with an occasional gently playful turn.

**Do not copy:** Do not reuse Peggy's name, logo, proprietary product labels, artwork, artist identities, institutional relationships, quotations, numerical claims, fees, patent claims or investment promises. Source examples illustrate sentence shape only.

- **Addressing the reader:** Speak directly to you and your; use we for the organization and the product name when explaining a mechanism. Make room for both newcomers and experienced users.
- **Rhythm:** Headlines are often 3–10 words but can expand into a conversational sentence. Support paragraphs typically use two to four plain sentences. Short questions and fragments create pace; explanatory chapters tolerate longer paragraphs without turning into slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A welcome followed by an expansive but accessible possibility. | 7–12 words | “Welcome to [Brand]. A whole world of art.” |
| Benefit headline | Plain-language reassurance, sometimes balancing two clauses. | 4–9 words | “All the benefits, none of the hassle.”<br>“Let us do the vetting” |
| Supporting explanation | State who the product is for, then list the practical things it lets you do. | 25–60 words | “[Brand] is the social marketplace that allows you to discover, buy, and sell art. A place for the art-curious and the art-expert, for the art gallery and artist.” |
| Primary action | Direct verb plus destination or product; no clever ambiguity. | 2–3 words | “Download [Brand]”<br>“Join Now” |
| Closing invitation | Brief desire-to-action turn, with a friendly question when appropriate. | 3–7 words | “Like? Collect it.” |
| Audience pathway | A simple audience label and a question that invites further exploration. | Short label plus one sentence | “Curious about displaying your art on [Brand]?” |

**Words and phrasing to use:** welcome; discover; community; get to know; your; curious; a place for; confidence; all the benefits

**Avoid:** disruption jargon; exclusive luxury rhetoric; hype-heavy superlatives; frictionless everything; guaranteed returns; abstract enterprise language

**Rules:**

- Explain unfamiliar mechanisms through an everyday action before naming technical detail.
- Make inclusivity concrete by naming different levels of familiarity or different uses.
- Use a small witty contrast occasionally, not a pun in every heading.
- Keep reassurance operational: safety, support, access or process, only where the product can substantiate it.
- Use short action labels; leave the emotional argument to the heading and support line.

## Do's and Don'ts

### Do

- Keep the large serif light at weight 300 and use 72px/1 for the default hero.
- Expose 8px canvas seams between white rectangular modules.
- Give editorial text 48px desktop insets while images reach their module edges.
- Carry one continuous looping-line graphic into the closing charcoal invitation.
- Preserve object proportions in 288px rails with 24px gaps.
- Pair 12px/16px object captions with modest 24px sans-serif collection titles.
- Keep the footer light, using separate white columns and a shallow legal/social strip.
- Use a real face or purposeful oversized object to balance the first-screen headline.

### Don't

- Do not turn the light serif into a heavy 700-weight fashion headline.
- Do not round the default 64px conversion action into a pill; capsules belong to avatars and the scoped Offer action.
- Do not wash the entire page in a saturated brand color; reserve chromatic intensity for the exhibits.
- Do not use colored icon circles for trust cells; their 40px pictograms are black silhouettes.
- Do not normalize all browsing images to square thumbnails or remove unusual silhouettes.
- Do not add general card elevation or drop shadows to the white modular architecture.
- Do not inflate proof numbers into enormous display type; the institutional figures are 36px.
- Do not fill the minimal header with an invented multi-link desktop menu.

## Motion and responsive

### Motion

**Observed:**

- A portrait video has a visible play affordance.
- Horizontal browsing rails have scrollable overflow.
- No action or surface transition timing is established; editorial article links declare underline on hover and profile cards declare a border-color change.

**Transfer:**

- Keep product-thread scenes legible as static compositions; use portrait playback as the primary rich-media interaction.
- Let the partly revealed rail item communicate horizontal continuation.

**Unknown:**

- Playback behavior, autoplay policy and animation timing are unspecified.
- Carousel-related animation names exist, but no element-level movement or duration is established.

### Responsive

**Observed:**

- Width breakpoints are declared at 640px, 767px, 768px, 1024px, 1139px, 1280px and 1536px.
- Hero classes use full-width children below the medium split layout; display classes step from 36px to 48px to 72px.
- Trust-strip classes progress from two to three to six columns; footer classes progress from two to five columns.
- Text panel padding steps from 16px horizontal and 32px vertical through 32px horizontal to 48px desktop.

**Transfer:**

- On narrow screens, stack the portrait/product scene and editorial half, keeping the action shelf attached to its text.
- Retain horizontal object rails rather than squeezing all objects into a miniature grid.
- Keep the line motif clipped to the media panel and preserve the hard-edged gray seams as the layout narrows.

**Unknown:**

- Exact mobile order, image heights and all breakpoint-specific behavior are not fully established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
