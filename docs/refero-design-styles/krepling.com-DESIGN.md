# Krepling — pastel machines in motion

## Overview

An expansive software-marketing style that makes infrastructure feel tangible through floating objects, luminous pastel stages and simplified interface sculptures. Regular-weight grotesk typography and spare black-and-white layouts give the colorful product stories room to breathe. Mostly light grey, it moves into charcoal chapters and a glowing dark conclusion; the density is low even when the product is complex.

### Essentials

- The promise lives around the object, not above it: a full-screen diagonal sculptural scene separates a 64px/1.1 lower-left headline from a 32px upper-right proposition and an 18px lower-right support line.
- Big type stays conversational rather than heavy: weight 400 throughout, 96px chapter names and 80px statements with -0.01em tracking; gradient color picks out the final benefit phrase.
- Color belongs to stages and artifacts, not the whole interface: light grey #f1f1f1 and white dominate, charcoal #171717 supports an immersive chapter, and pastel gradients fill large product stages while saturated purple is concentrated in 49px actions.
- Controls are soft rectangles rather than pills: 10px button corners, 14px cards, and 8px logo tiles; a black contextual callout uses a distinctly deeper 30px corner.
- Features become objects on a shelf: centered 930px cards with short upper-left copy, large lower illustrations and alternating white/black faces; simplified connected interface modules provide the fallback when a product has no polished media.
- Every new landing page carries a luminous product stage, a gradient-emphasized statement and a dark product-led closing scene: the closing pairs a 48px invitation with an oversized interface at the right over a soft purple glow, followed by unusually open footer columns.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Conversion purple | `#b154f9` | `--color-purple` | action, border | Filled primary actions and secondary action outlines. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof yellow | `#ffe01b` | `--color-proof-yellow` | surface | Saturated ecosystem-logo tile; contained within proof strips. |
| Emphasis blue | `#77b5ff` | `--color-text-blue` | text | First stop of blue-to-purple benefit emphasis. |
| Emphasis violet | `#a782ff` | `--color-text-violet` | text | Last stop of blue-to-purple benefit emphasis. |
| Sky stage | `#8dc8ff` | `--color-sky` | background | Blue side of a blue-to-mint product stage. |
| Mint stage | `#9dffca` | `--color-mint` | background | Green side of a blue-to-mint product stage. |
| Violet stage | `#c9a9ff` | `--color-violet` | background | Purple side of an ice-to-violet product stage. |
| Header outline | `#e0bafd` | `--color-pale-purple` | border | Subtle outline on light navigation's signup action. |
| Lavender stage | `#ddccff` | `--color-lavender` | background | Cool side of a peach-to-lavender stage. |
| Ice stage | `#ccedff` | `--color-ice` | background | Light side of an ice-to-violet product stage. |
| Peach stage | `#f8d1c9` | `--color-peach` | background | Warm side of a pastel product stage. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, surface | Primary light-theme text, black feature cards and contextual callouts. |
| Charcoal chapter | `#171717` | `--color-charcoal` | background | Immersive dark capability chapter and shared closing region. |
| Footer low emphasis | `#5d5d5d` | `--color-footer-muted` | text | Visible result of white at 0.3 opacity over charcoal for low-emphasis footer text. |
| Secondary ink | `#6c6b6b` | `--color-body` | text | Paragraphs on light backgrounds. |
| Navigation secondary | `#999999` | `--color-nav-muted` | text | Secondary navigation treatment; use black for the light opening's visible links. |
| Secondary on black | `#b3b3b3` | `--color-muted-dark` | text | Supporting text on black feature and plan cards. |
| Fine separator | `#e6e6e6` | `--color-rule` | border | Visible black at 0.1 opacity over white for accordion separators. |
| Light grey canvas | `#f1f1f1` | `--color-canvas` | background | Default light marketing canvas and FAQ background. |
| White | `#ffffff` | `--color-white` | surface, text, action | Cards and reversed text; also the clean integration-proof band. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company-story partner grids | Partner cyan | `#00ace5` | `--color-partner-cyan` | surface | One identity-led partner-card fill. |
| company-story partner grids | Partner orange | `#f89734` | `--color-partner-orange` | surface | One identity-led partner-card fill. |
| company-story partner grids | Partner pink | `#fadbeb` | `--color-partner-pink` | surface | One identity-led partner-card fill. |
| company-story partner grids | Partner near-black | `#150f0e` | `--color-partner-dark` | surface | One identity-led partner-card fill. |
| company-story pages | Stat panel | `#2e2e2e` | `--color-stat-panel` | surface | Dark stat-card face. |

## Typography

- **Regular** — All marketing headings, paragraphs, labels and controls. Neutral modern grotesk with open counters, compact large headlines and an unforced regular weight. If unavailable, use **Inter**. Use weight 400 and preserve the measured tracking and line-height relationships. Font stack: "Regular", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| chapter | Regular | 400 | 96px | 1.1 | -0.01em | size max(3rem, 6.66667vw) | Single-word capability chapter names beside a rounded icon tile. |
| statement | Regular | 400 | 80px | 1.1 | -0.01em | size max(2.25rem, 5.55556vw) | Large benefit statements and ecosystem headings; also the pricing-page title. |
| hero | Regular | 400 | 64px | 1.1 | -0.01em | size max(2.25rem, 4.44444vw) | Opening promise; also the company-story recruitment headline and large stat numerals. |
| heading | Regular | 400 | 48px | 1.3 | normal | size max(1.75rem, 3.33333vw) | FAQ headings, closing invitation and secondary section titles. |
| card-heading | Regular | 400 | 32px | 1.3 | normal | size max(1.25rem, 2.22222vw) | Stacked-card titles, opening proposition and larger introductory support; pricing names and prices share this recipe. |
| item-heading | Regular | 400 | 24px | 1.1 | 0.02em | size max(1.25rem, 1.66667vw) | FAQ questions, capability-list titles and contextual-callout copy. |
| body | Regular | 400 | 18px | 1.3 | 0.02em | size max(1.125rem, 1.25vw) | Marketing paragraphs, card descriptions and answers. |
| small | Regular | 400 | 16px | 1.3 | 0.01em | size max(1rem, 1.11111vw) | Navigation, buttons, footer links, plan descriptions and short metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company-story pages | stat-label | Regular | 400 | 16px | 1.3 | 0.01em, uppercase | size max(1rem, 1.11111vw) | Top-left category on tall stat cards. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Large type tightens to -0.01em while 18px and 24px text opens to 0.02em. The hierarchy comes from size and space, not a bold-weight ladder.
- Gradient emphasis is upright even when semantically emphasized. Restrict it to a meaningful clause rather than coloring the entire heading.
- Keep headline wrapping broad and natural: the opening promise is about three lines in a 578px column; statements occupy a 930px measure.

## Layout

**Density:** Airy: full-screen product scenes and long chapter pauses surround short, compact copy blocks.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 8px | Tight supporting-label gaps. | max(0.5rem, 0.555556vw) |
| 10px | Column gutters in the twelve-column grid. | max(0.625rem, 0.694444vw) |
| 16px | Title-to-body spacing and paired-action separation. | 1.11111vw |
| 20px | Page side inset. | fixed |
| 24px | Compact card interiors. | max(1.5rem, 1.66667vw) |
| 32px | Feature-card side padding, action separation from body and callout padding. | max(2rem, 2.22222vw) |
| 48px | Stacked-card top padding and accordion-row vertical padding. | max(2rem, 3.33333vw) |
| 96px | Footer top padding and spacing before supporting grids. | 6.66667vw |
| 192px | Major light-section breathing room, 24 × 8px. | max(8rem, 13.3333vw) |
| 240px | Chapter-title and statement-block vertical padding, 30 × 8px. | max(8rem, 16.6667vw) |

### Containers and grids

- **page grid**: max width 1440px · 12 columns · gap 10px · side padding 20px. At the desktop reference width, 1400px of usable content carries asymmetric column spans rather than a uniformly centered text column; let the grid remain fluid.
- **statement and stack**: max width 930px. Centered large-text statements and sticky showcase cards.
- **right-offset editorial**: max width 1048px. Supporting grids, contextual callouts and FAQ align after a substantial left gutter, about one quarter of the viewport.
- **intro measure**: max width 708px. Feature-chapter introductory copy; ordinary hero support remains substantially narrower.
- **feature list**: 2 columns · gap 136px. 397px text blocks with 96px row separation; open, unboxed icon-and-copy entries.
- **summary cards** (only for capability-directory and company-story pages): 3 columns · gap 10px. 460px-wide overview or stat cards at desktop.
- **pricing comparison** (only for pricing pages): 4 columns · gap 9px · side padding 20px. Three 284px plans surround one emphasized 520px plan, all 709px tall.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 10px |
|  | feature cards | 14px |
|  | accordion and proof tiles | 8px |
|  | contextual callout | 30px |
|  | chapter icon tile | 27px |
| article previews | editorial tags | 100px |

## Surfaces and depth

### Surfaces

#### Light canvas · level 0

**Use:** Default long-form marketing background.

**CSS:** `background: #f1f1f1; color: #000000`

**Observed:** Pale grey extends behind the light opening and capability chapters; white is reserved for faces and proof bands.

**Transfer:** Use grey as the continuous room in which cards and illustrations sit.

#### White face · level 1

**Use:** Product cards and summary cards.

**CSS:** `background: #ffffff; border-radius: 14px; box-shadow: none; overflow: hidden`

**Observed:** Flat, borderless faces distinguish themselves through contrast with the grey canvas.

**Transfer:** Do not add elevation to compensate for sparse content.

#### Dark chapter · level 0

**Use:** Immersive capability passage and closing region.

**CSS:** `background: #171717; color: #ffffff`

**Observed:** White cards and true-black cards both appear against this charcoal room.

**Transfer:** Switch the whole chapter's text and icon contrast, not merely one card.

#### Black face · level 1

**Use:** Contrasting feature card.

**CSS:** `background: #000000; color: #ffffff; border-radius: 14px; overflow: hidden`

**Observed:** Grey body copy and vivid miniature UI remain readable against the black face.

**Transfer:** Alternate this face with White face to create a staged reveal.

#### Pastel product stage · level 0

**Use:** Large illustrative product demonstration.

**CSS:** `background: linear-gradient(90.01deg, #f8d1c9 0.01%, #ddccff 99.99%); border-radius: 14px; overflow: hidden`

**Observed:** The other stage families run sky to mint and ice to violet. Large diffuse circular color fields soften the linear gradient; on capability-directory pages the stage becomes a full-width section background.

**Transfer:** Give each major capability one coherent pastel family, not a mixture of unrelated saturated hues.

#### Benefit emphasis

**Use:** Short benefit clause within monumental text.

**CSS:** `background-image: linear-gradient(95.66deg, #77b5ff 18.09%, #a782ff 88.64%); background-clip: text; -webkit-text-fill-color: rgba(0,0,0,0); font-style: normal`

**Observed:** Related passages use violet-to-peach or pale-blue-to-mint emphasis.

**Transfer:** Keep adjacent text solid black or white so the emphasis has a clear purpose.

## Components

### Navigation

**Use:** Persistent site-level orientation.

**CSS:** `position: fixed; height: 80px; z-index: 4`

**Text style:** `small` — Regular 400 · 16px/1.3 · tracking 0.01em

**Observed:** Compact mark at left, a centered cluster of short links with fine dropdown chevrons, then login and an outlined signup action at right. The initial light view uses dark links over the artwork; the dark company view reverses them. The header is visually transparent rather than a raised toolbar.

**Transfer:** Keep the logo small and the center clear enough that the art can pass behind it.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #b154f9; color: #ffffff; border-radius: 10px; padding: 14px 16px; height: 49px`

**Text style:** `small` — Regular 400 · 16px/1.3 · tracking 0.01em

**Observed:** Text-only action with no decorative arrow. A single main action anchors the default opening.

**States:** Declared: hover background-color #8d31d3; focus-visible and active unknown.

### Outline button

**Use:** Secondary action alongside the primary.

**CSS:** `border: 1px solid #b154f9; color: #ffffff; border-radius: 10px; padding: 14px 16px; height: 51px`

**Text style:** `small` — Regular 400 · 16px/1.3 · tracking 0.01em

**Observed:** Default is reversed on the closing region. Light-background variants use black text; the navigation uses a paler purple outline. Paired footer actions are separated by 16px.

**States:** Declared: hover background-color rgba(177,84,249,0.25) on dark and rgba(177,84,249,0.1) on light; focus-visible and active unknown.

### White button

**Use:** Action on a black contextual callout or photographic invitation.

**CSS:** `background: #ffffff; color: #000000; border-radius: 10px; padding: 14px 16px; height: 49px`

**Text style:** `small` — Regular 400 · 16px/1.3 · tracking 0.01em

**Observed:** Small white control sits at the far right of a black callout; company-story hero uses it as a reversed primary action.

**States:** Declared: hover background-color #e1e1e1; focus-visible and active unknown.

### Showcase card

**Use:** One capability demonstrated as a large object.

**CSS:** `background: #ffffff; border-radius: 14px; overflow: hidden; margin-bottom: 16px`

**Text style:** `card-heading` — Regular 400 · 32px/1.3

**Observed:** Title and one short paragraph occupy the top-left with 48px top and 32px side insets; the illustration fills the lower area and can run off the side edges. Black face is the contrasting variant. Cards overlap within a centered sticky stage rather than forming a dense dashboard grid.

**Transfer:** Use one result per face and a simplified cluster of two or three product modules beneath the copy.

### Contextual callout

**Use:** Compact next step after a capability or proof block.

**CSS:** `display: flex; justify-content: space-between; align-items: center; background: #000000; color: #ffffff; border-radius: 30px; padding: 32px`

**Text style:** `item-heading` — Regular 400 · 24px/1.1 · tracking 0.02em

**Observed:** A 1048px-wide, 113px-high black slab aligned to the right-offset editorial grid. Copy sits left; White button sits right. It is followed by 192px of section breathing room.

**Transfer:** Use one concise summary and one action; keep it a horizontal bridge, not a second hero.

### FAQ row

**Use:** Answer concrete adoption objections.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 48px 20px; color: #000000`

**Text style:** `item-heading` — Regular 400 · 24px/1.1 · tracking 0.02em

**Observed:** Rows sit within an 8px-rounded white list about 930px wide. Fine black-at-0.1 top separators divide subsequent rows; a narrow 18px by 11px chevron sits right. Answers use body text and are concealed in the resting view.

**Transfer:** Use full-width question buttons and preserve the broad row hit area.

### Proof tile

**Use:** Ecosystem or compatibility proof in an edge-clipped strip.

**CSS:** `display: flex; justify-content: center; background: #ffe01b; border-radius: 8px; width: 349px; height: 138px; margin-left: 8px; margin-right: 8px`

**Observed:** Centered logos sit inside vivid tiles. Two rows have a 16px vertical gap and different horizontal offsets, continuing beyond both viewport edges. Tile colors follow the represented identity rather than the conversion-purple token.

**Transfer:** For a product without partner marks, use named input types, compatible formats or concise outcome symbols in the same tiled strip.

### Closing footer

**Use:** Shared final invitation and site directory.

**CSS:** `background: #171717; padding-top: 96px; padding-bottom: 32px; overflow: hidden`

**Text style:** `small` — Regular 400 · 16px/1.3 · tracking 0.01em

**Observed:** A split upper scene puts a two-line invitation and paired actions on the left, with a 716px by 521px interface image reaching the right edge. A soft purple glow sits behind the image. Below it, the small mark and three spacious link groups lead to location/contact, five tiny social symbols and low-emphasis copyright.

**Transfer:** Close with a real product view or a legible simplified work surface, never only a text-and-button strip.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side offer comparison.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ffffff; border-radius: 14px; padding: 32px 24px 24px`

**Text style:** `card-heading` — Regular 400 · 32px/1.3

**Observed:** Name and price share the same scale; the monthly suffix is grey. Description, compact quota badges and a bottom-aligned full-width Outline button are separated by generous empty space. The recommended plan is nearly twice as wide, black, and carries a white Popular pill plus a Primary button; quota badges reverse on that face.

**Transfer:** Highlight one useful choice through width and inversion, not a larger price font.

### Stat card

**Only for:** company-story pages

**Use:** Sparse quantified credibility below the opening.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #2e2e2e; border-radius: 14px; padding: 32px`

**Text style:** `hero` — Regular 400 · 64px/1.1 · tracking -0.01em

**Observed:** Three 460px by 381px cards on black. Uppercase small category at top-left; 64px numeral and an 18px muted caption sit near the bottom with an 8px gap. The composition intentionally leaves a deep interior pause.

**Transfer:** Use a small number of meaningful metrics; retain the tall shape rather than filling it with charts.

## Imagery and graphics

### Sculptural opening

**Use:** Default landing-page first impression.

**Observed:** Two oversized, softly lit ivory hollow cylinders enter diagonally from opposing edges; luminous elliptical rims frame a glassy sphere and drifting rounded app tiles. Almost-white, blush and lavender materials blend into the grey room. The object dominates the middle and left while typography occupies clear corner zones.

**Transfer:** Translate the product's central mechanism into a floating exchange between two simple volumes. Minimum acceptable version: layered SVG ellipses and tapered panels with a translucent orb and a few rounded semantic tiles, not a generic stock illustration.

**Build:** Construct two groups rotated roughly -30deg: a long tapered ivory panel plus concentric ellipse rims, one group clipped by the upper-left boundary and the other by the bottom edge. Shade with white-to-grey gradients and low-alpha peach/violet overlays. Place a translucent white circular orb between them with a fine highlight rim, then three to five colored rounded-square artifacts at varied rotations. Blur only the distant shading, preserving sharp rims and foreground text.

### Pastel interface sculpture

**Use:** Signature product stages and feature-card artwork.

**Observed:** Simplified storefronts, carts, controls, charts and product tiles float on pastel gradient fields. Modules connect through rounded necks and stepped silhouettes rather than ordinary rectangles stacked in a browser. Small photographic products or customer faces introduce reality without becoming full-bleed photography. Large central stages dwarf their surrounding copy; card illustrations are smaller and clipped by the face.

**Transfer:** Diagram the new product's input, action and result with two or three simplified modules. Keep only enough authentic UI to explain the mechanism; preserve the large soft shapes and quiet backing.

**Build:** Use the Pastel product stage surface at up to 1400px width. Overlay large circular diffuse fields at 0.3 opacity, with blur around 187px at desktop. Center a main rounded work surface and flank it with smaller control and result blocks; join related blocks with narrow rounded SVG connectors. Use pale translucent white modules on light stages and muted charcoal modules on black faces. Alternate peach/lavender, sky/mint and ice/violet families by capability.

### Closing interface glow

**Use:** Required final product-led scene.

**Observed:** A crisp white application window is enlarged, rounded and clipped at the right edge; a subdued magenta-to-violet halo diffuses into charcoal behind it. The glow extends toward the invitation but does not wash over the lower directory.

**Transfer:** Use a readable work surface showing a meaningful task. If no interface exists, construct a simple pipeline or result board with real labels and the same luminous backing.

**Build:** Place a 716px-wide product panel to the right of the closing invitation. Behind it use overlapping absolute elliptical radial gradients in rgba(177,84,249,0.25) and rgba(248,209,201,0.12), softened with about 96px blur. Keep the outer edge transparent and the charcoal canvas dominant; exact glow stops are not essential.

### Human and workplace photography

**Only for:** company-story and recruiting pages

**Use:** Break the abstract product language with real people and working environments.

**Observed:** An edge-clipped strip of 584px by 385px candid workplace photos follows the mission text. Founder portraits are tall 343px by 571px rounded images with white name and role labels near the bottom; color and monochrome can coexist. Recruitment uses a full-width lounge photo with a dark scrim and a large white invitation.

**Transfer:** Choose candid, lived-in workplaces and close human portraits; avoid polished corporate handshake imagery.

### Identity and editorial artwork

**Only for:** company-story partner grids and article previews

**Use:** Institutional proof and editorial discovery.

**Observed:** Partner marks are centered on tall 343px by 571px orange, cyan, blush, near-black or white cards with names and small descriptors at the bottom. Article previews are two large white cards with inset 663px by 379px colorful vector illustrations, 32px titles and thin outlined pill categories.

**Transfer:** Let external identities own their card colors. For articles, use simple topical vector scenes over bright gradient backing rather than product UI or team portraits.

**Build:** For editorial art, combine flat geometric people and topic objects in the lower two thirds of a landscape frame. Back them with a broad blue-to-violet or magenta-to-violet field; leave generous sky above and avoid detailed textures.

### Icons

**Observed:** Capability-list symbols are delicate black outlines, generally around 32px tall with 1px strokes and butt caps. Chapter icons sit inside 80px by 74px tiles with 27px corners, switching black/white with the chapter. Navigation chevrons are 12px by 7px; social marks are solid white at 15px.

**Transfer:** Choose sparse diagram-like outline symbols with thin strokes, not heavy filled icon packs. Use compact solid marks only for social identities.

## Section recipes

How recurring sections are built.

### First screen: Sculptural corner opening

**Observed:** A 900px-high visible stage under transparent Navigation holds the Sculptural opening artwork from edge to edge. Back-to-front layers are pale canvas, oversized diagonal volumes, floating orb and app artifacts, then dark type. The upper-right proposition is set at 32px in a narrow column; the three-line 64px promise anchors the lower-left and occupies about two fifths of the width. An 18px support line and Primary button anchor the lower-right, with 32px between support and action. All four text/action areas and the central object are visible in the first 900px. The next chapter title is below the fold; the opening section extends to 1125px.

**Transfer:** Retain the opposing corner composition and an oversized exchange-object scene for a new product; use the SVG construction when bespoke 3D is unavailable. Capability-directory openings retain the lower-left promise but move support and two actions upper-right over a diagonal tray of floating artifacts. Pricing opens more compactly with an 80px title and 24px support over an isometric tile floor. Company-story openings use the same corner logic on black with luminous metallic volumes and white type.

**Avoid:** Do not turn this into a centered SaaS headline above a laptop mockup, or hide the main object and conversion action below the first screen.

**Text style:** `hero` — Regular 400 · 64px/1.1 · tracking -0.01em

### Capability chapter and statement

**Observed:** A centered chapter label combines chapter typography and a rounded icon, with 240px vertical padding. A large Pastel product stage follows. A centered 930px-wide statement block uses statement typography, upright Benefit emphasis on the payoff clause and another 240px top/bottom pause. Light canvas is the default; Dark chapter is a deliberate immersive variant.

**Transfer:** Use this device for the product's major value propositions without requiring a fixed number of chapters.

**Text style:** `statement` — Regular 400 · 80px/1.1 · tracking -0.01em

### Stacked demonstration

**Observed:** Showcase cards occupy a centered 930px stage, each with top-left copy and lower illustrative modules. White and black cards move over one another inside a sticky 900px-tall viewport. The surrounding chapter remains open rather than tightly packing the next feature beneath the card.

**Transfer:** Use a few distinct demonstrable benefits per stack; for a shorter page keep one overlap pair rather than a long catalog.

### Ecosystem ribbon

**Observed:** A white band with a right-offset 80px heading introduces two rows of Proof tile components, clipped at both edges and horizontally offset. A large 48px inline list of capabilities with fine icons can follow before Contextual callout.

**Transfer:** Include a colorful tiled proof device using ecosystem evidence or supported formats; let it serve the new page's proof needs rather than copying the original topics.

### Objection panel

**Observed:** Light canvas with 192px vertical padding contains a 48px heading and a right-offset 930px white list of FAQ rows. The resting composition shows five collapsed questions.

**Transfer:** Ask concise practical questions about adoption, compatibility or access. Keep answer prose subordinate to the scan-friendly questions.

### Product-led closing

**Observed:** Closing footer begins with a 48px invitation on the left, paired Primary button and Outline button below, and Closing interface glow to the right. The lower region contains widely spaced directory groups rather than a dense boxed sitemap. All four page types share this construction.

**Transfer:** Make the final image demonstrate the promised outcome and keep the CTA distinct from the quieter directory below.

**Text style:** `heading` — Regular 400 · 48px/1.3

### Capability directory chapter

**Only for:** capability-directory pages

**Observed:** Full-width pastel backing carries an icon and 48px category, an 80px outcome heading and 32px supporting statement limited to 708px. A broad white card pairs a narrow copy column with a dominant illustration; two supporting cards align to the right below it. An unboxed two-column icon list and Contextual callout conclude the chapter.

**Transfer:** Reuse this more systematic composition when users need to inspect capabilities rather than watch a flagship narrative.

### Comparative offers

**Only for:** pricing pages

**Observed:** Compact illustrated title opens directly into four Plan cards; the black recommended plan is 520px wide versus 284px peers. Shared benefits then appear as a long two-column icon list on grey, followed by Contextual callout and Closing footer.

**Transfer:** Use the asymmetric emphasis only when one offer deserves recommendation, and keep price styling consistent across tiers.

### Company credibility and culture

**Only for:** company-story pages

**Observed:** A black sculptural opening leads into three Stat cards. On grey, a broad 48px mission statement uses selected gradient phrases, followed by candid image strips, tall identity cards and founder portraits aligned after a large left gutter. A full-width recruiting photograph and two editorial preview cards broaden the narrative before the shared close.

**Transfer:** Choose the equivalent mission, credible proof and human material for the new organization; retain the distinction between abstract black opening and grounded photography.

## Page flow

**Storyline:** spatial promise → staged product explanation → concrete capability proof → contextual next step → shared product-led close

### Flagship marketing narrative

1. **promise** — Full-screen sculptural corner composition with a clear proposition and single action.
2. **capability chapters** — Large chapter names, pastel interface stages, gradient-payoff statements and alternating stacked demonstrations.
3. **ecosystem proof** — Bright edge-clipped tile ribbons and a typographic capability inventory.
4. **objection handling** — Right-offset accordion on grey after a compact black callout.
5. **closing call** — Glowing interface scene, paired actions and open footer directory.

**Transfer:** Select the strongest capabilities rather than reproducing the original narrative length; retain spatial art, gradient payoff and product-led close.

### Offer selection

1. **orientation** — Compact illustrated title over isometric tiles.
2. **pricing** — Four tall plans with one wide black recommendation.
3. **shared value** — Two-column unboxed benefit inventory with thin icons.
4. **closing call** — Black contextual bridge followed by glowing product footer.

**Transfer:** Prioritize comparability and keep the recommendation visual, with the same atmospheric brand language around it.

### Detailed capability evaluation

1. **promise** — Diagonal artifact tray with corner headline and upper-right actions.
2. **orientation** — Three overview cards summarize the major capability areas.
3. **capability chapters** — Pastel category intros, broad illustrated cards, supporting pairs and unboxed feature lists.
4. **ecosystem proof** — Colored logo ribbon with a partner-oriented contextual bridge.
5. **closing call** — Shared glowing product footer.

**Transfer:** Use repeatable chapters for comprehensive product information while limiting each illustration to one mechanism.

### Organizational trust and recruitment

1. **mission promise** — Black luminous sculpture with white corner text and reversed actions.
2. **quantified proof** — Three tall, dark stat panels beneath the first screen.
3. **credibility** — Large mission text, candid photo strip, colorful institutional identity cards and founder portraits.
4. **human invitation** — Full-width workplace photograph with white recruitment copy.
5. **editorial discovery** — Two illustrated article cards and a short black blog callout.
6. **closing call** — Shared glowing product footer.

**Transfer:** Keep culture photography and institutional colors scoped to the organizational story rather than importing them into every product page.

## Writing

Confident, expansive and benefit-led, with a friendly practical explanation beneath each ambitious claim. Technical capability is presented as creative freedom and operational ease, not developer bravado.

**Do not copy:** Do not reuse the brand name, marks, customer or partner assets, proprietary artwork, product names, prices, investor identities, company metrics or unsubstantiated superlatives as claims for another product. Examples illustrate syntax only.

- **Addressing the reader:** Speak directly to you and your business; use we for mission and organizational commitment. Imperative verbs lead capability and action copy.
- **Rhythm:** Headlines range from one-word chapter names to broad sentence-length promises. Short titles are followed by one or two explanatory sentences; compact actions use two or three words, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Broad outcome or category-strength claim in a complete sentence. | 6–13 words | “The world’s most powerful commerce platform.”<br>“Everything you need to create a best-in-class online store” |
| Supporting proposition | Turn a technical barrier into a plain-language contrast. | 10–18 words | “Build your store using clicks instead of code.”<br>“Your online store should be a sales channel, not an engineering challenge.” |
| Capability title | Short action or outcome phrase, understandable without product terminology. | 1–5 words | “Plan and adapt”<br>“Streamline your business” |
| Supporting detail | Concrete mechanism followed by the practical benefit. | 15–45 words | “Use custom triggers and events across multiple integrations to elevate customer experiences.” |
| Action | Low-friction verb phrase; distinguish starting from asking for help. | 2–3 words | “Get started”<br>“Request a demo”<br>“Find open roles” |
| Objection | A direct customer question about fit or adoption. | 5–12 words | “Can I use my existing domain?” |

**Words and phrasing to use:** build; create; grow; manage; streamline; visibility; in minutes; all in one place; without writing code

**Avoid:** hacker swagger; ironic asides; dense unexplained acronyms; exclamation-heavy urgency; cute button microcopy

**Rules:**

- Pair ambitious promises with a concrete mechanism in the next supporting line.
- Use short functional labels for navigation and controls rather than campaign slogans.
- Let gradient emphasis land on the payoff of a sentence, not arbitrary nouns.
- Keep technical descriptions focused on what the reader can accomplish.

## Do's and Don'ts

### Do

- Keep all marketing typography at weight 400; make scale and spatial separation carry the hierarchy.
- Use 20px page insets and 10px grid gutters while preserving the wide internal editorial offset.
- Keep 18px body copy at 1.3 line height and 0.02em tracking.
- Give large cards 14px corners and enough interior space for the lower illustration.
- Use a 49px filled purple action and a 51px outlined secondary when pairing actions.
- Keep the dark product-led conclusion with a 48px invitation and oversized right-edge interface.
- Separate long-form narrative pauses from compact list details using the 96px, 192px and 240px rhythm.
- Preserve the colorful tile-strip proof device with 349px by 138px tiles, adapting its content to available proof.

### Don't

- Do not create a bold 700-weight headline system; regular grotesk is essential to the softness.
- Do not use purple as the default section background; it is an action color or one part of a controlled stage gradient.
- Do not add heavy shadows or glass borders to the flat marketing cards.
- Do not replace the 10px rectangular action shape with fully rounded pills; reserve pills for small tags and recommendation badges.
- Do not make all pricing tiers equal width when using the recommended-plan treatment.
- Do not substitute black-on-charcoal low-contrast text for the white headings and grey supporting copy of dark chapters.
- Do not turn the thin 32px capability icons into oversized filled badges.
- Do not populate every card with dense application chrome; the illustrative modules must remain sparse and legible.

## Motion and responsive

### Motion

**Observed:**

- Declared chapter-heading reveal: transform 1.6s cubic-bezier(0.19,1,0.22,1) with 0.1s delay, paired with opacity 0.6s at the same delay.
- Declared product-stage scale transition: transform 1.6s cubic-bezier(0.19,1,0.22,1).
- Sticky showcase cards overlap as the page advances. Proof strips shift horizontally; their speed is not established.
- Some links use opacity 0.3s cubic-bezier(0.25,0.46,0.45,0.94), with hover opacity 0.7. Button hover fills are declared but their timing is not established.

**Transfer:**

- Use long, soft spatial reveals for major chapter artifacts rather than bouncing or spring-loaded controls.
- Keep card overlap and stage expansion tied to the capability narrative; do not apply the same movement to every paragraph.

**Unknown:**

- Exact scroll-to-animation mapping, proof-strip speed, button timing, focus-visible and active styling.

### Responsive

**Observed:**

- Declared width breakpoints at 599px, 600px, 999px, 1000px and 1400px.
- Type and several spacing values follow viewport formulas with minimums, as listed in their scales.

**Transfer:**

- As a narrow-screen adaptation, stack the corner text areas around a single coherent sculptural scene rather than shrinking the entire desktop canvas.
- Let the proof ribbon remain edge-clipped; convert plan and supporting grids into readable vertical sequences.
- Retain the product-led close by placing the interface after the invitation and actions, preserving its glow.

**Unknown:**

- Actual mobile layouts, header-menu construction and whether sticky demonstrations remain active at narrow widths.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
