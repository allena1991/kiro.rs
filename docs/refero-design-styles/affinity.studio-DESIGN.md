# Affinity — editorial type at play

## Overview

A bold, creative-tool style that puts expressive serif typography on a black stage, surrounded by colorful work rather than decorative gradients. Warm charcoal, chalk white and stone sections give the saturated imagery room to speak, while acid green marks actions and small moments of emphasis. The feeling is capable but irreverent: spacious editorial headlines, practical sans-serif explanations, and richly framed interfaces, illustration and photography.

### Essentials

- Editorial drama comes from a chunky serif, not tight grotesk lettering: 148px/1.04 bold display with an italic final word, 80px/0.98 section headings, and normal tracking throughout.
- The opening is a gallery with a clear center: a 900px black stage holds a centered short promise and paired actions, while independent artwork rectangles enter from the edges without obscuring the message.
- Actions are soft rectangles rather than pills: acid-green primary and stone secondary buttons use 12px corners, 48px height and 16px/24px medium sans-serif labels; compact actions are 40px high.
- Color lives in work and bounded proof, not in every section: black and warm charcoal dominate the default landing page, with one white editorial respite; green is concentrated in actions, quote marks and a 72px graphic strip.
- Product proof is oversized and art-directed: a 1288px-wide demonstration or 595×552px detail scene pairs actual interface controls with vivid finished work; use a representative output with a small meaningful control overlay when full product media is unavailable.
- The page behaves like an editable canvas: show selection handles or vector nodes on at least one artwork, and end with a monumental word sculpture inside 1px ruled borders. Adapt the typography to the new product name or a short product promise rather than replacing this device with a small logo.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#a7f175` | `--color-lime` | action, accent, link, background | Primary CTA fill, dark-section links, quote marks, selection accents and the narrow graphic strip. |
| Gallery coral | `#e35b67` | `--color-coral` | surface | A bounded colored card in the numbered benefit gallery, not a global background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text | Default canvas and text on light sections. |
| Action ink | `#0e1318` | `--color-action-ink` | text | Dark text and icons on bright or stone buttons. |
| Feature black | `#151515` | `--color-feature-dark` | surface | Raised dark feature card on the black canvas. |
| Warm charcoal | `#211d1d` | `--color-charcoal` | background, surface | Long product chapters, quotes and conversion bands; warmer than the black stage. |
| Charcoal edge | `#373434` | `--color-card-rule` | border | Subtle outline of dark conversion cards. |
| Graphite copy | `#505050` | `--color-secondary-light` | text, border | Supporting copy and outlined editorial tags on white or pale sections. |
| Soft metadata | `#707477` | `--color-muted-light` | text | Visible appearance of rgba(17,23,29,0.6) on white for metadata and subdued descriptions. |
| Warm rule | `#b0a79e` | `--color-footer-rule` | border | Fine frame surrounding the footer and its giant lettering. |
| Silver copy | `#c4c4c4` | `--color-secondary-dark` | text | Supporting copy on dark sections. |
| Stone | `#e0dcd6` | `--color-stone` | surface, background, action | Secondary buttons, monumental closing lettering and warm FAQ backgrounds. |
| Feature parchment | `#f0e7de` | `--color-parchment` | surface | Light companion to a wide dark release card. |
| Gallery cream | `#efe9de` | `--color-cream` | surface | Light card in the numbered benefit gallery. |
| Chalk white | `#ffffff` | `--color-white` | text, surface | Headlines on dark sections, editorial canvas and inverse action surfaces. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| FAQ sections | Stone divider | `#c9c7c5` | `--color-faq-rule` | border | Visible result of rgba(57,70,96,0.14) over stone in FAQ separators. |
| capability and acquisition pages | Cool paper | `#f6f6f6` | `--color-light-canvas` | background | Alternating light capability chapters. |

## Typography

- **Affinity Serif Variable** — Display headlines, chapter titles and quotations. Heavy, high-contrast editorial serif with flared shapes and a notably expressive italic. If unavailable, use **DM Serif Display**. Use its regular and italic cuts for the heavy display silhouette; use a lighter visual treatment for quotations. Font stack: "Affinity Serif Variable", "DM Serif Display", Georgia, serif.
- **Canva Sans** — Body text, navigation, actions, metadata and practical feature titles. Open, friendly contemporary sans-serif with clear proportions and restrained weight changes. If unavailable, use **Noto Sans**. Use 400, 500 and 600; preserve normal tracking. Font stack: "Canva Sans", "Noto Sans", system-ui, Segoe UI, Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Affinity Serif Variable | 700 | 148px | 1.04 | normal | Main promise; short and visually dominant. |
| display-italic | Affinity Serif Variable | 700 italic | 148px | 1.04 | normal | Expressive word within the main promise. |
| heading | Affinity Serif Variable | 700 | 80px | 0.98 | normal | Major chapter headings on both dark and light bands. |
| gallery-heading | Affinity Serif Variable | 700 | 56px | 1 | normal | Numbered benefit cards. |
| split-heading | Affinity Serif Variable | 700 | 56px | 1.1 | normal | Compact title next to layered portrait-format media. |
| quote | Affinity Serif Variable | 400 | 48px | 1.1 | normal | Large testimonials and the price line in acquisition panels. |
| editorial-heading | Canva Sans | 400 | 32px | 1.25 | normal | Article titles, platform names and audience-card titles. |
| lead | Canva Sans | 401 | 24px | 1.4 | normal | Hero support and chapter explanations. |
| card-heading | Canva Sans | 500 | 24px | 32px | normal | Practical titles inside feature cards. |
| body | Canva Sans | 401 | 16px | 1.5 | normal | Card descriptions, footer links and short supporting paragraphs. |
| action | Canva Sans | 500 | 16px | 1.5 | normal | Main conversion buttons. |
| label-strong | Canva Sans | 600 | 16px | 1.5 | normal | Footer column headings and author names in light proof sections. |
| action-small | Canva Sans | 500 | 14px | 22px | normal | Header CTA and compact in-card actions. |
| caption | Canva Sans | 401 | 14px | 22px | normal | Bylines, category tags, author roles and compact badges. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| FAQ sections | faq-display | Affinity Serif Variable | 700 | 112px | 0.96 | normal | Oversized short heading beside a question list. |
| FAQ sections | question | Canva Sans | 400 | 24px | 32px | normal | Accordion question labels. |

**Notes:**

- Keep the display serif exceptionally bold while quotations use regular weight; do not make every serif element equally heavy.
- Normal letter spacing is deliberate, even at 148px. The compressed feeling comes from the letterforms and 0.98 section-heading line height, not negative tracking.
- Use sentence case. The italic is a meaningful word-level change rather than a separate script font.

## Layout

**Density:** Airy at chapter level, compact inside working demonstrations; large fields of black separate dense, colorful media.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Metadata-to-title spacing and footer row gaps. |
| 12px | Feature-card title to description. |
| 16px | Hero title to supporting line, action pairs and small stacked copy. |
| 24px | Chapter heading to paragraph, card gutters and media-to-editorial-copy gaps. |
| 32px | Description to action and standard feature-card text inset. |
| 40px | Numbered gallery-card text inset. |
| 48px | Hero support group to actions and acquisition-panel inset. |
| 64px | Chapter introduction to demonstration or feature grid. |
| 96px | Light editorial and FAQ band vertical padding. |
| 128px | Default major chapter vertical padding. |
| 144px | Deep lower breathing room on numbered gallery chapters. |

### Containers and grids

- **main-container**: max width 1288px · side padding 24px. Centered main content; at 1440px this leaves 76px visible margins.
- **intro-measure**: max width 910px. Centered chapter explanations and supporting hero copy; use less width for a short single-line promise.
- **feature-grid**: max width 1288px · 12 columns · gap 24px. Three equal cards span four tracks each; wide/narrow feature pairs span eight and four tracks.
- **split-chapter**: 2 columns · gap 16px. A roughly 636px text column beside 595×552px media. Media may approach the outside viewport edge while text stays aligned to the main container.
- **footer-frame**: max width 1472px · side padding 24px. Wider than the content grid; fine vertical side rails bind the directory, word sculpture and utility row.
- **faq-columns** (only for FAQ sections): max width 1288px · 2 columns · gap 32px. Short heading occupies about one third; questions occupy an 848px right column.

## Corner radius

| Element | Radius |
| --- | --- |
| actions | 12px |
| media-cards | 20px |
| editorial-tags | 6px |
| footer-links | 10px |
| carousel-controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | carousel-ring | `inset 0px 0px 0px 1px #ffffff` | Next arrow on the dark numbered gallery. |
| acquisition pages | acquisition-panel | `16px -4px 52px 0px rgba(0,0,0,0.45)` | White conversion panel layered over artwork. |

### Surfaces

#### Black stage · level 0

**Use:** Default page canvas.

**CSS:** `background: #000000; color: #ffffff`

#### Warm chapter · level 0

**Use:** Product demonstrations, testimonial bands and closing conversion chapters.

**CSS:** `background: #211d1d; color: #ffffff`

#### White editorial band · level 0

**Use:** Bright relief for articles and illustrated customer proof.

**CSS:** `background: #ffffff; color: #000000`

#### Feature panel · level 1

**Use:** Media-bearing feature cards.

**CSS:** `background: #151515; color: #ffffff; border-radius: 20px; overflow: hidden`

**Observed:** Pairs contrast a wide dark card with a narrow parchment card. Capability galleries broaden the card palette into saturated teal, purple, pink and pale yellow; each card carries its own high-contrast text.

**Transfer:** Choose backing colors to reinforce the demonstration, not to assign a different accent to every paragraph.

#### Outlined conversion panel · level 1

**Use:** Platform or audience cards on charcoal.

**CSS:** `background: #211d1d; border: 1px solid #373434; border-radius: 20px; overflow: hidden`

#### Cool chapter · level 0

**Only for:** capability and acquisition pages

**Use:** Alternating explanatory chapters.

**CSS:** `background: #f6f6f6; color: #000000`

#### Stone field · level 0

**Only for:** capability and acquisition pages

**Use:** Question sections and dense capability galleries.

**CSS:** `background: #e0dcd6; color: #000000`

#### Raised acquisition panel · level 2

**Only for:** acquisition pages

**Use:** Dominant conversion panel above scattered artwork.

**CSS:** `background: #ffffff; color: #000000; border-radius: 20px; padding: 48px; box-shadow: 16px -4px 52px 0px rgba(0,0,0,0.45)`

## Components

### Navigation

**Use:** Persistent compact access to product, discovery and help.

**CSS:** `position: sticky; top: 0px; height: 80px; z-index: 10; background: rgba(0,0,0,0.78)`

**Text style:** `body` — Canva Sans 401 · 16px/1.5

**Observed:** White wordmark at left, a short row of dropdown labels beside it, and Compact action pushed to the far right. Interior follows main-container; secondary pages use opaque black.

### Primary button

**Use:** Main conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 8px 16px; border-radius: 12px; background: #a7f175; color: #0e1318`

**Text style:** `action` — Canva Sans 500 · 16px/1.5

**Observed:** Text-only in the default paired opening; download contexts add a leading downward-arrow icon. Width follows the label.

### Secondary button

**Use:** Parallel organization or adjacent-product route.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 8px 16px; border-radius: 12px; background: #e0dcd6; color: #0e1318`

**Text style:** `action` — Canva Sans 500 · 16px/1.5

**Observed:** Placed next to Primary button with 16px separation; external destinations can add a trailing external-link icon.

### Compact action

**Use:** Header CTA and actions inside feature or conversion cards.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 8px 16px; border-radius: 12px; background: #a7f175; color: #0e1318`

**Text style:** `action-small` — Canva Sans 500 · 14px/22px

**Observed:** Header version includes a leading download icon. Feature cards use white on dark panels and black on pale panels instead of competing green.

### Numbered benefit card

**Use:** Horizontal, browseable product benefits.

**CSS:** `position: relative; width: 630px; border-radius: 20px; background: #211d1d; overflow: hidden`

**Text style:** `gallery-heading` — Affinity Serif Variable 700 · 56px/1

**Observed:** A small fraction such as 1/5 leads a serif title, then 16px explanatory copy within 40px insets. Media fills the lower part. Cream and coral cards use black text; a partial next card remains visible beyond the right edge.

### Feature card

**Use:** Release highlights and capability proof.

**CSS:** `position: relative; border-radius: 20px; background: #151515; overflow: hidden`

**Text style:** `card-heading` — Canva Sans 500 · 24px/32px

**Observed:** 32px text inset, title, 12px gap to body, optional Compact action, then bottom-flush artwork with interface fragments. Wide/narrow pairs share a height around 520px.

### Category tag

**Use:** Small editorial classification below article titles.

**CSS:** `display: inline-flex; padding: 2px 8px; height: 28px; border: 1px solid #505050; border-radius: 6px; color: #505050`

**Text style:** `caption` — Canva Sans 401 · 14px/22px

**Observed:** Outlined, low-emphasis rectangular label rather than a filled pill.

### Carousel arrow

**Use:** Previous and next controls beside gallery headings.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 56px; height: 56px; padding: 0px 20px; border-radius: 9999px; box-shadow: inset 0px 0px 0px 1px #ffffff; color: #ffffff`

**Observed:** Two circular controls at the right of the heading; previous has a half-opacity ring. Light proof sections invert the rings and arrows.

**States:** Declared: hover background-color #ffffff12; focus-visible unspecified; active background-color #ffffff26.

### Footer directory link

**Use:** Grouped navigation above the closing word sculpture.

**CSS:** `display: inline-flex; padding: 4px 12px; border-radius: 10px; color: #ffffff`

**Text style:** `body` — Canva Sans 401 · 16px/1.5

**Observed:** 192px-wide link rows, 8px vertical gaps and semibold group labels. Four compact columns align to the right, leaving a deliberate broad blank field at left.

### Platform card

**Use:** Closing conversion choices for different destinations.

**CSS:** `background: #211d1d; border: 1px solid #373434; border-radius: 20px; overflow: hidden`

**Text style:** `editorial-heading` — Canva Sans 400 · 32px/1.25

**Observed:** Three equal 413px-wide cards: sans-serif platform name, short muted description, Compact action, and a device or output image anchored at the bottom. An unavailable option uses subdued copy and a disabled-looking low-contrast action.

### FAQ disclosure

**Only for:** FAQ sections

**Use:** Expandable objections and practical answers.

**CSS:** `width: 100%; padding: 4px 8px; border-radius: 12px; text-align: left`

**Text style:** `question` — Canva Sans 400 · 24px/32px

**Observed:** Question fills the row with a trailing chevron; first answer is open, using body text and 16px paragraph gaps. Separate 1px rules and 24px list gaps create the rhythm rather than boxed cards.

**States:** Declared: hover background-color #404f6d0f, color #0f1015; focus-visible unspecified; active background-color #39466024, color #0f1015.

## Imagery and graphics

### Orbiting creative gallery

**Use:** Signature opening imagery around a short centered promise.

**Observed:** Separate square and portrait artwork rectangles float on pure black: tactile illustration, vivid editorial art, a surreal macro image and a fashion photograph. Images clip against the viewport edges; the center remains an uninterrupted black reading field. Media uses bright color without a shared tint or heavy shadow.

**Transfer:** Use four to six distinctly composed outputs or applications of the new product. A minimum version uses original abstract posters, a macro object photograph and one credible output preview, keeping their rectangles independent.

**Build:** Position a gallery layer behind the hero copy. At a 1440px width, use edge tiles around 180–295px wide, with one entering from the top, one at left-middle, one at right-lower-middle and one cut by the bottom. Use object-fit: cover, hard rectangular framing and no glow. Reserve roughly the central half of the stage for text.

### Interface and output detail

**Use:** Large demonstrations and split capability chapters.

**Observed:** Actual dark application chrome surrounds intensely colored finished work. Detail scenes enlarge a relevant toolbar, dialog or cursor over artwork; 595×552px framing emphasizes the operation rather than a distant entire desktop. Larger demonstrations span the main container.

**Transfer:** Pair an authentic product control with its output at readable scale. Keep the control purposeful and the result visually rich; do not reproduce every internal UI style as marketing chrome.

### Editable selection motif

**Use:** Signature artwork annotation in galleries and proof.

**Observed:** A portrait-format foreground artwork has a thin magenta bounding box, white round corner handles and a small attached label; two smaller, darker artworks recede behind it. Elsewhere lime selection handles and fine guide rules frame illustrated customer work.

**Transfer:** Use one meaningful selection frame on a product output or diagram; it should suggest active work, not a generic decorative border.

**Build:** Layer a 414×518px foreground artwork over two smaller rectangles around 332×415px and 276×346px. Add a 2px magenta stroke and 12px white circular handles at the four corners, with a matching outline. Attach a small same-hue label at the lower right. Receding tiles are darker and partially occluded; a simpler version uses just one selected output with visible handles.

### Monumental editable lettering

**Use:** Required closing graphic inside the footer frame.

**Observed:** A near-full-width stone-colored word sculpture fills a 1390×449px black stage. Oversized letterforms touch the frame; one central letter is drawn as a thin vector outline with nodes and Bezier handles, accompanied by a small collaborator label. Horizontal guide rules cross the artwork.

**Transfer:** Use the new product name or a short ownable word, scaled to fill the frame. When custom lettering is unavailable, convert a heavy serif word to SVG paths and outline one letter while preserving the solid neighbors.

**Build:** Create an SVG with a 1390×449 viewBox, black backing and stone filled letter paths fitted edge to edge. Render one letter fill:none with a thin pale stroke; add circular nodes and tangent lines at curve joins. Add top, baseline and side guides at 1px, plus one compact green name label near the edited letter. Keep utility text outside this art, below the stage.

### Editorial thumbnails and human proof

**Use:** Bright article bands, testimonials and audience-specific cards.

**Observed:** Article thumbnails are bold designed compositions rather than stock photo tiles; three 408×330px images sit over bylines and plain sans-serif titles on white. Testimonials pair large regular serif copy with a small circular portrait. Organization cards use full-height workplace photography with a darkened upper zone for text.

**Transfer:** Use original output-led editorial covers and credible human attribution. For audience cards, crop real working environments and protect legibility with restrained dark overlays.

### Icons

**Observed:** Mostly compact filled SVG glyphs at 24px and 16px: download arrows, dropdown chevrons, playback and external-link marks. Circular gallery controls contain simple directional arrows; occasional outline icons are secondary.

**Transfer:** Use a single simple UI icon family, monochrome and optically sized; reserve colored symbols for actual demonstrated product UI.

## Section recipes

How recurring sections are built.

### First screen: Gallery promise opening

**Observed:** A full 900px black first screen with Navigation over the top. The centered promise sits near the visual middle, spanning about half the viewport width in display and display-italic. Orbiting creative gallery is behind it, reaching all four edges but leaving the central message clear. A single lead line follows with 16px separation; paired Primary button and Secondary button sit 48px below that group, separated by 16px, with a tiny endorsement lockup beneath. The first 900px contain the whole promise, support, both actions and partially cut artwork tiles. The narrow green graphic strip begins below the fold.

**Transfer:** Keep a short two-part promise and equivalent output gallery for a new marketing page. Capability pages instead use a centered display title, lead paragraph, one primary action and a wide product demonstration beginning near the lower third; acquisition pages use a left headline with a white conversion panel on the right over scattered artwork.

**Avoid:** Do not substitute a generic two-column dashboard hero, a gradient orb, or a centered white card for this default composition. Do not let edge art run behind the support line.

**Text style:** `display` — Affinity Serif Variable 700 · 148px/1.04

### Graphic proof strip

**Observed:** A 72px lime band with compact dark marks and 24px top and bottom breathing room separates the opening from the first product chapter.

**Transfer:** Carry a narrow graphic strip somewhere in the page using relevant partner marks, compatibility symbols or a short typographic motif; keep it visibly subordinate to the gallery.

### Heading and demonstration

**Observed:** Warm chapter holds a centered heading and lead copy within intro-measure, followed 64px later by a main-container-wide demonstration with 20px corners and a faint light edge. A compact tab bar and explanatory caption follow the media.

**Transfer:** Use one strong product demonstration to make the promise tangible; tabs should represent genuinely different working modes.

**Text style:** `heading` — Affinity Serif Variable 700 · 80px/0.98

### Alternating split chapters

**Observed:** Cool chapter alternates with Black stage. Each chapter is around 808px high with 128px top and bottom space, a large serif heading above lead copy and a 595×552px Interface and output detail. Text and image alternate sides; dark text is graphite and inverse copy is silver.

**Transfer:** Use a handful of substantive capability explanations, each with one visual operation. Reverse the composition to maintain a steady visual cadence.

**Text style:** `heading` — Affinity Serif Variable 700 · 80px/0.98

### Numbered gallery

**Observed:** Left-aligned chapter heading and right-aligned Carousel arrow pair lead a horizontal row of Numbered benefit card elements after 64px. Cards have a 24px gap and intentionally reveal the next item at the viewport edge.

**Transfer:** Give each benefit a clear numbered label and a distinct proof image; preserve the editorial serif card titles.

**Text style:** `gallery-heading` — Affinity Serif Variable 700 · 56px/1

### Quote as breathing space

**Observed:** A Warm chapter contains a lime opening quotation mark, large regular serif testimony and a small portrait/name/role group beneath. The copy occupies most of the width but leaves space at right for a small customer mark.

**Transfer:** Use a real specific endorsement; preserve the contrast between the oversized quote and compact attribution.

**Text style:** `quote` — Affinity Serif Variable 400 · 48px/1.1

### Release and capability mosaic

**Observed:** A centered heading and lead precede Feature card pairs with an eight-track wide card and a four-track narrow card, separated by 24px. Media is bottom-flush and text sits at the top. Capability pages expand this into a multirow Stone field with stronger bounded color.

**Transfer:** Use the asymmetry to emphasize one substantial capability alongside a concise companion, not to make every feature equally prominent.

**Text style:** `card-heading` — Canva Sans 500 · 24px/32px

### Light editorial respite

**Observed:** White editorial band uses 96px vertical padding and a left serif chapter heading. Three plain image-and-text columns follow: thumbnail, 24px gap, caption, 8px gap, editorial-heading and Category tag.

**Transfer:** Offer useful educational or editorial material as a brighter break in the dark product narrative.

**Text style:** `editorial-heading` — Canva Sans 400 · 32px/1.25

### Closing conversion choices

**Observed:** Warm chapter uses 128px padding, a centered playful heading and lead explanation, then three Platform card elements at 24px gutters. Device imagery fills their lower portions; primary actions remain near the top of each card.

**Transfer:** Use platform, role or deployment choices only when the product warrants them. A single route can use the same prominent chapter treatment without inventing three offers.

**Text style:** `heading` — Affinity Serif Variable 700 · 80px/0.98

### Question field

**Observed:** Stone field has 96px vertical padding and the faq-columns layout. The 112px serif title balances an 848px column of FAQ disclosure rows, separated by fine rules. The first answer is expanded.

**Transfer:** Group practical purchase and usage objections in a stable two-column section, keeping answers plain and specific.

**Text style:** `faq-display` — Affinity Serif Variable 700 · 112px/0.96

### Ruled monumental ending

**Observed:** A black footer around 1060px tall begins with a warm hairline. Footer directory link columns sit right-aligned above Monumental editable lettering; the side rails continue down to a compact language/social/legal row. The graphic occupies 1390×449px and is framed on all sides.

**Transfer:** Retain the giant editable word device on every new page, adapted to its own identity. Keep the directory and utilities readable, small and separate from the artwork.

### Acquisition and comparison

**Observed:** A black acquisition opening pairs a left-aligned display headline with Raised acquisition panel on the right, layered over colorful artwork. The panel carries identity, lead copy, a 48px serif price, primary action and caption. Later, a pale comparison section uses descriptive rows at left and two white checkmark columns, with a compact expand control.

**Transfer:** Use this variant for a download, signup or purchase destination; supply real price and eligibility details and a concise comparison only when needed.

**Text style:** `display` — Affinity Serif Variable 700 · 148px/1.04

## Page flow

**Storyline:** Expressive promise → tangible product proof → capability chapters and human proof → useful next steps → objections or conversion choices → monumental graphic ending.

### Broad brand and product landing page

1. **Promise** — Centered serif promise in an orbiting artwork gallery with paired audience actions.
2. **Product demonstration** — Narrow graphic strip leads into a large tabbed demonstration.
3. **Capability and proof** — Numbered gallery, layered-media chapter and oversized testimonials build depth.
4. **Freshness and education** — Asymmetric release cards and a bright editorial band broaden the story.
5. **Conversion and ending** — Platform-choice cards lead into the ruled directory and editable word sculpture.

**Transfer:** Default for a new marketing page: use the expressive gallery, deep demonstration and strong graphic ending; vary the intervening chapter sequence to fit the product.

### An integrated-feature campaign

1. **Promise** — Centered display title, support, single CTA and wide demonstration.
2. **Capability chapters** — Alternating light/dark split scenes and a compact feature disclosure explain the workflow.
3. **Capability gallery** — Stone-backed asymmetric colored feature cards provide concrete visual proof.
4. **Adoption and objections** — Setup explanation, adjacent-product next step and warm FAQ field.
5. **Ending** — Shared ruled footer and editable lettering.

**Transfer:** Use for a focused capability ecosystem; keep operational explanations separate from detailed visual cards.

### Acquisition destination

1. **Conversion** — Left display headline and raised white action panel over artwork.
2. **Value and comparison** — Checklist-led split chapter followed by a pale comparison table.
3. **Audience routing** — Two photographic organization cards offer alternative routes.
4. **Objection handling** — Extended warm FAQ column.
5. **Ending** — Shared directory, giant editable lettering and utility row.

**Transfer:** Prioritize the transaction and eligibility while retaining the same artwork, serif scale and monumental ending.

### Capability-specific product landing page

1. **Promise and demonstration** — Centered oversized title and single CTA over a wide product video.
2. **Capability chapters** — Alternating split explanations and a stone-backed colorful mosaic.
3. **Social proof** — Light two-column artwork wall and large serif testimonial.
4. **Applications and onboarding** — Compact icon tiles, another feature explanation and a four-step instructional row.
5. **Objections and ending** — Warm FAQ field and shared ruled footer.

**Transfer:** Best suited to a substantial product feature with enough real media to support both deep explanations and a gallery of outputs.

### Interoperability overview

1. **Promise** — Two-line centered display statement, support, primary CTA and broad supporting image.
2. **Capability chapters** — Three alternating light/dark split scenes explain distinct handoffs.
3. **Objection handling** — Warm FAQ column clarifies setup and pricing.
4. **Ending** — Shared directory, editable word sculpture and utilities.

**Transfer:** Use a shorter chapter sequence for a small set of connections; give each its own clear demonstration rather than a wall of logos.

## Writing

Confident and craft-literate, with a dry wink rather than corporate grandiosity. Large promises are followed by concrete descriptions of how the product removes friction.

**Do not copy:** Do not reuse the brand names, logos, distinctive artwork, customer identities, quotations, file-format claims, free-pricing promises or performance claims as assets or facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Direct you/your addresses the practitioner; we appears in helpful explanations. Product names are used plainly rather than with repetitive trademark language.
- **Rhythm:** Headlines are usually two to seven words, sometimes split into two short clauses. Supporting copy uses full practical sentences; parentheses, contractions and occasional playful asides keep it human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Main promise | An active verb followed by a liberating adverb. | 2–5 words | “Create freely” |
| Section heading | Name the friction removed or make a concise, memorable benefit claim. | 3–7 words | “No more app switching”<br>“Smart features, no fluff”<br>“Precision without the pain” |
| Supporting line | Describe the capability and its scope without generic superlatives. | One sentence or a short paragraph | “Professional design, photo editing, and page layout in one app.” |
| Action | Simple verb or explicit audience/eligibility label. | 2–5 words | “Free for individuals”<br>“Sign up to download” |
| Playful conversion heading | One concise colloquial twist, followed immediately by plain factual copy. | 3–6 words | “Zero bucks given” |

**Words and phrasing to use:** craft; flow; shape; keep moving; your workflow; without; in one app; seriously; no fluff

**Avoid:** revolutionary platform; unlock your limitless potential; synergize; next-generation ecosystem; enterprise-grade magic

**Rules:**

- Make humor a heading-level accent; keep setup, pricing and eligibility explanations literal.
- Explain a real operation before making an emotional claim about creative freedom.
- Use concrete verbs such as edit, export, reshape and customize.
- Keep CTA labels explicit about the destination or action.

## Do's and Don'ts

### Do

- Keep the main serif display at 148px/1.04 on the desktop stage, with a distinct italic word.
- Use 80px/0.98 serif headings to give product chapters editorial weight.
- Use 128px chapter padding and 64px introduction-to-media gaps for the deep product rhythm.
- Keep the main container at 1288px and card gutters at 24px.
- Use 12px action corners and 20px media-card corners consistently.
- Put interface details over vivid, credible outputs rather than showing distant unreadable desktops.
- Carry the editable-node motif into artwork and the 1390×449px closing word stage.
- Balance dark chapters with a purposeful white editorial section rather than making every band identical.

### Don't

- Do not replace bold serif titles with thin geometric sans-serif display text.
- Do not tighten all headings with negative tracking; the core recipes use normal tracking.
- Do not turn green primary actions into fully rounded pills; keep 12px corners.
- Do not spread acid green across large hero or chapter backgrounds; the full-width green treatment is a narrow 72px strip.
- Do not give every panel a floating drop shadow; most cards use flat fills and fine edges.
- Do not use 32px feature titles inside the compact mosaic; those use 24px/32px medium sans-serif.
- Do not replace the right-weighted footer directory with a centered stack of giant navigation links.
- Do not make the closing word sculpture a conventional small centered logo.

## Motion and responsive

### Motion

**Observed:**

- Actions declare background-color, border-color and color transitions at 0.1s linear.
- Navigation declares background-color 0.4s and box-shadow 0.2s transitions.
- Video demonstrations include play/pause controls, and galleries expose previous/next controls.

**Transfer:**

- Keep functional controls available on moving demonstrations; media is part of product proof, not an uncontrollable backdrop.
- Use short color transitions for actions rather than adding large spring movements to the editorial text.

**Unknown:**

- Precise gallery movement, scroll-trigger choreography and hero artwork movement timing are not specified.

### Responsive

**Observed:**

- Width rules include 600px, 768px, 900px, 1024px, 1200px and 1280px among several breakpoints.

**Transfer:**

- On narrow layouts, preserve the central reading field by reducing and moving orbiting tiles to the outer edges before reducing text contrast.
- Stack split chapters and wide/narrow cards when their content no longer fits; keep the footer word sculpture fitted to its frame and utility text outside it.

**Unknown:**

- Exact mobile font sizes, navigation collapse behavior and artwork arrangements are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
