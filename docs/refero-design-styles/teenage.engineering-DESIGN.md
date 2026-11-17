# teenage engineering — equipment meets fight poster

## Overview

Industrial product design meets the energy of a printed campaign poster. Mostly pale grey and black, with sharp orange signals, the style pairs technical sans lettering with oversized outline artwork, tactile photography and mischievous illustration. It suits physical tools and inventive products whose construction deserves as much attention as their promise; expansive image chapters alternate with unusually compact technical information.

### Essentials

- A campaign image, not a sales paragraph, owns the entrance: full-width photography continues beyond the first 900px, with an outlined product-name graphic across roughly half the screen width and small functional descriptors beneath.
- Headlines behave like printed equipment labels: TechnoType 52.9px/1.1111 at weight 700 on 68px-high orange or black tabs; supporting statements use 26.4px/1.1111 at weight 500 with normal tracking.
- Conversion looks like a small hardware control, not a friendly pill: dark add-to-bag buttons are 93×31px with 4.4px corners, sitting beside 13.2px product names and prices.
- Colour is a signal in an otherwise neutral environment: #ff5000 belongs on headline tabs, 68px full-width conversion strips and tiny details, while long reading and image chapters remain pale grey or black.
- The product is examined, not merely displayed: alternate full-bleed macro photography with frontal isolated objects, exploded construction views and thin-line technical drawings. If photography is unavailable, use a carefully lit render plus an annotated vector elevation.
- A narrow repeating message and a little graphic mischief interrupt the laboratory tone: use a 41px dark ticker with 26.4px lettering, plus original cut-paper-style annotation stickers or speech bubbles around demonstrations and commerce.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5000` | `--color-signal` | accent, background, action | Headline tabs, broad but shallow store strips and isolated price emphasis. |
| Utility orange | `#f05a24` | `--color-utility-orange` | link, accent | Small resource links in the black technical chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool paper | `#f9faf9` | `--color-canvas` | background | Default campaign page canvas. |
| Pale assembly ground | `#f5f7f6` | `--color-detail-canvas` | background | Exploded component chapter backing. |
| Ticker white | `#f1f2f2` | `--color-ticker-text` | text | Repeating text on the dark message strip. |
| Warm tab lettering | `#e9e8e1` | `--color-tab-text` | text | Light lettering on orange, black and grey headline tabs. |
| Equipment grey | `#e5e5e5` | `--color-panel` | surface, text | Purchase cards and demonstration panels; reversed technical and footer lettering. |
| Macro grey | `#dfdfdf` | `--color-photo-ground` | background | Neutral backing around full-width material photography. |
| Blue grey | `#989fa5` | `--color-steel` | background, surface | Accessory campaign backing and tactile-feature headline tab. |
| Almost black | `#0f0e12` | `--color-ink` | text, background, action | Default dark controls and ticker backing. |
| Technical black | `#000000` | `--color-black` | text, background | Main campaign copy and the technical closing chapter. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| system overview pages | Technical grey | `#7f7f7f` | `--color-muted` | text | Small comparison information and resource links. |
| system overview pages | Comparison charcoal | `#272727` | `--color-charcoal` | background | Multi-product specification table backing. |
| system overview pages | Explore blue | `#0071bb` | `--color-link-blue` | link | Explore and store text links. |
| printed-collage campaigns | Kraft beige | `#dbd0b9` | `--color-kraft` | background, text | Warm campaign ground and reversed credits. |
| printed-collage campaigns | Printed green | `#00503a` | `--color-forest` | text, action | Bundle titles and buy controls. |
| printed-collage campaigns | Printed orange | `#f05123` | `--color-print-orange` | text, accent | Expressive price numerals and closing display lettering. |
| printed-collage campaigns | Warm credits black | `#1b1718` | `--color-warm-black` | background | Long credit roll and footer backing. |
| system overview pages | Port diagram grey | `#dbdbdb` | `--color-port-ground` | surface | Orthographic connection studies. |

## Typography

- **TechnoType** — Default campaign headings, support statements, technical captions and purchase metadata. Thin-looking engineered sans forms with unusual mechanical details; the declared bold cut still feels light rather than emphatically heavy. If unavailable, use **Michroma**. Use regular weight and tune width before adding weight; preserve the technical all-cap appearance. Font stack: "TechnoType", "Michroma", Unicode, sans-serif.
- **te-20** — Body defaults, footer, and system overview support text. Spare neo-grotesk with a light visual colour and compact spacing. If unavailable, use **Roboto**. Use light and regular cuts; avoid geometric circular alternates. Font stack: "te-20", "Roboto", Unicode, sans-serif.
- **te-40** (only for system overview and catalogue closing sections) — Light mixed-case section titles. Light neo-grotesk, less mechanical than campaign lettering. If unavailable, use **Roboto**. Use weight 300. Font stack: "te-40", "Roboto", Unicode, sans-serif.
- **riddim** (only for printed-collage campaigns) — Sculptural numerals and expressive thank-you lettering. Rounded, cut-out display shapes with blocky stencil-like joins. If unavailable, use **Bungee**. Use only for short numerals or a short display line; it is a tonal alternative, not a matching alphabet. Font stack: "riddim", "Bungee", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | TechnoType | 700 | 52.9px | 1.1111 | normal | Core headline tabs and full-width conversion bands; the glyphs appear uppercase. |
| statement | TechnoType | 500 | 26.4px | 1.1111 | normal | Centered benefit paragraphs and ticker text. |
| technical-heading | TechnoType | 400 | 26.4px | 1.1111 | normal | Left-aligned section titles within the black technical chapter. |
| feature-list | TechnoType | 500 | 19.1px | 1.154 | normal | Dense two-column campaign feature lists and assembly annotations. |
| footer | te-20 | 300 | 16px | 1.5 | normal | Utility footer links and copyright. |
| body-default | te-20 | 300 | 16px | 1.5 | normal | Base text when no campaign recipe applies. |
| caption | TechnoType | 700 | 13.2px | 1.1111 | normal | Small technical explanations, demonstration captions and compact purchase control labels. |
| metadata | TechnoType | 400 | 13.2px | 1.1111 | normal | Purchase card titles and prices; specification details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| printed-collage campaigns | campaign-price | riddim | 400 | 52.9px | 1.1111 | normal, uppercase | Sculptural prices beside smaller currency labels; local transforms enlarge these beyond the base recipe. |
| system overview and catalogue pages | system-heading | te-40 | 300 | 39.7px | 1.1111 | normal | Mixed-case system chapter headings and catalogue closing line. |
| system overview pages | system-statement | te-20 | 100 | 26.4px | 1.1111 | normal | System introductions and split-row descriptive paragraphs. |
| system overview pages | system-link | te-20 | 300 | 26.4px | 1.1111 | normal | Explore actions and use-case subheadings. |
| printed-collage campaigns | credits-display | riddim | 400 | 26.4px | 1.1111 | normal, uppercase | Closing thanks artwork; the display wrapper uses scale(4.5). |
| printed-collage campaigns | credits | TechnoType | 400 | 19.1px | 1.154 | normal | Centered, one-name-per-line credit roll. |
| system overview pages | system-spec | te-20 | 100 | 13.2px | 1.1111 | normal, uppercase | Tight uppercase hardware bullet lists. |
| system overview pages | system-caption | te-20 | 300 | 13.2px | 1.1111 | normal | Comparison data and small resource links. |

**Notes:**

- Normal tracking is characteristic throughout; do not add fashionable negative tracking or widely spaced micro-labels.
- The hierarchy doubles from 13.2px captions to 26.4px statements to 52.9px tabs. A heading's nominal bold weight does not imply a chunky conventional grotesk.
- Opening product-name lettering is outline artwork rather than ordinary headline text. Use an original SVG word sculpture about 660px wide with roughly 210px visible capital height at desktop; its optical proportions matter more than the text font's em box.

## Layout

**Density:** Airy image chapters with compact technical islands; full-bleed photographs are allowed to last longer than a viewport, while captions and purchase labels sit tightly together.

### Spacing

| Value | Use |
| --- | --- |
| 14.7px | Card and caption-column gaps. |
| 22px | Utility-link flex gap and small content spacing. |
| 33.1px | Footer vertical padding. |
| 54px | Typical gap from a headline tab to its supporting statement. |
| 66.1px | Desktop page-side inset. |
| 103px | Breathing room before a technical or tactile chapter. |
| 147px | Long pause between major media and text beats. |
| 176px | Extended gap between technical demonstrations and the next image chapter. |

### Containers and grids

- **page-inset**: side padding 66.1px. Full-width page with a 1308px working area at 1440px; not a fixed global max-width container.
- **statement-column**: max width 902px. Centered campaign promise, generally several tight lines wide.
- **commerce-grid**: max width 1087px · 2 columns · gap 14.7px. Centered pair of 536px purchase cards.
- **caption-grid**: max width 1087px · 3 columns · gap 22px. Explanations aligned directly below a demonstration graphic.
- **system-split** (only for system overview pages): 2 columns · gap 0px. Two equal 720px panels at desktop, one square product image and one inset text panel; alternating sides.
- **use-case-grid** (only for system overview pages): max width 1087px · 5 columns · gap 14.7px. Five narrow illustrated use cases with 206px square symbols and dense copy.
- **catalogue-grid** (only for system overview commerce sections): 3 columns · gap 0px. Edge-to-edge product and accessory squares, interrupted by full-width photographic stages.

## Corner radius

| Element | Radius |
| --- | --- |
| purchase-controls | 4.4px |
| headline-tabs | 7.3px |
| purchase-cards | 22px |
| workflow-panel | 14.7px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default light campaign ground.

**CSS:** `background: #f9faf9; color: #000000`

**Observed:** The main reading surface is flat; full-width media runs flush into it.

**Transfer:** Use this ground between high-impact image chapters.

#### Purchase card · level 1

**Use:** Grouped object, price and purchase action.

**CSS:** `background: #e5e5e5; border-radius: 22px; box-shadow: none`

**Observed:** Soft corners distinguish commerce from the otherwise square-edged page, without borders or floating elevation.

**Transfer:** Keep the object large and leave the textual row at the bottom.

#### Black technical band · level 0

**Use:** Specifications, dimensions and closing utility content.

**CSS:** `background: #000000; color: #e5e5e5; padding-left: 66.1px; padding-right: 66.1px`

**Observed:** A long black chapter follows the bright store strip; tiny resource links supply its colour.

**Transfer:** Use a decisive full-width inversion rather than a dark card on a light ground.

#### Assembly ground · level 0

**Use:** Exploded parts and tactile material stories.

**CSS:** `background: #f5f7f6`

**Observed:** A near-white variation separates a component study from neighbouring product photography.

**Transfer:** Keep the tone close to the page canvas rather than inventing a new accent colour.

#### Patterned commerce ground · level 0

**Use:** Accessory and bundle campaign stage.

**CSS:** `background-color: #989fa5`

**Observed:** A faint diagonal repeat of tiny outlined markings covers the blue-grey ground behind the cards.

**Transfer:** Create an original low-contrast repeat that reads as packaging print, not a wallpaper illustration.

#### Port-study ground · level 0

**Only for:** system overview pages

**Use:** Square orthographic connection diagrams.

**CSS:** `background: #dbdbdb`

**Observed:** Pairs of pale grey panels hold straight-on product edges, fine leaders and small annotations.

**Transfer:** Use a uniform backing across comparisons.

#### Warm credit ground · level 0

**Only for:** printed-collage campaigns

**Use:** Long final credits and utility footer.

**CSS:** `background: #1b1718; color: #dbd0b9`

**Observed:** Orange display lettering sits over a narrow beige credit column with extensive empty space around it.

**Transfer:** Use for a genuine collaboration-led campaign ending, not as the default technical close.

## Components

### Headline tab

**Use:** Chapter headline framed as a printed label.

**CSS:** `background: #ff5000; color: #e9e8e1; border-radius: 7.3px; height: 68px; width: fit-content; margin-left: auto; margin-right: auto`

**Text style:** `display` — TechnoType 700 · 52.9px/1.1111

**Observed:** Text-sized centred tab; black and blue-grey variants mark other kinds of chapters. Width follows the phrase.

**Transfer:** Choose a short, physical-sounding benefit phrase.

### Add to bag

**Use:** Compact card-level conversion.

**CSS:** `background: #0f0e12; color: #e5e5e5; border-radius: 4.4px; width: 93px; height: 31px; text-align: center`

**Text style:** `caption` — TechnoType 700 · 13.2px/1.1111

**Observed:** Sits at the right end of the card's bottom information row, after name and price.

**Transfer:** Use similarly brief purchase verbs; preserve the small scale.

### Purchase tile

**Use:** Accessory or bundle selection.

**CSS:** `background: #e5e5e5; border-radius: 22px; width: 536px; height: 573px; position: relative`

**Text style:** `metadata` — TechnoType 400 · 13.2px/1.1111

**Observed:** A large isolated object fills most of each tile. The name is bottom-left, price near the right, followed by Add to bag. Two tiles sit side by side with a narrow gutter.

**Transfer:** Keep every product's metadata on the same baseline; compose bundles as a single still life.

### Message ticker

**Use:** Repeated sales or campaign message as a graphic divider.

**CSS:** `background: #0f0e12; color: #f1f2f2; height: 41px; overflow: hidden; white-space: nowrap`

**Text style:** `statement` — TechnoType 500 · 26.4px/1.1111

**Observed:** Identical short messages repeat without a visible card boundary; text is clipped by both viewport edges.

**Transfer:** Use truthful product, price or availability information in an original repeated phrase.

### Store strip

**Use:** Full-width conversion or merchandise chapter marker.

**CSS:** `background: #ff5000; color: #e9e8e1; height: 68px; padding-left: 66.1px; padding-right: 66.1px; text-align: center`

**Text style:** `display` — TechnoType 700 · 52.9px/1.1111

**Observed:** An uninterrupted bright ribbon rather than a button floating in whitespace.

**Transfer:** Use a short action with room for the letters to dominate the band.

### Resource link

**Use:** Documentation and companion-tool navigation.

**CSS:** `color: #f05a24; text-decoration: none`

**Text style:** `caption` — TechnoType 700 · 13.2px/1.1111

**Observed:** Small orange labels above relevant tool previews in the technical chapter.

**States:** Declared: hover text-decoration underline; focus-visible and active unspecified.

### Workflow viewer

**Use:** Explain a product's working logic.

**CSS:** `background: #e5e5e5; border-radius: 14.7px; width: 1087px; height: 536px; position: relative`

**Observed:** A thin black outlined diagram lives in the rounded panel. Square arrow controls sit outside both sides; three small caption columns follow beneath. An orange speech bubble and original cartoon annotation punctuate the panel.

**Transfer:** Diagram three meaningful stages of a new product's workflow, not an entire interface.

### Utility footer

**Use:** Final site navigation and locale controls.

**CSS:** `background: #000000; color: #e5e5e5; display: flex; justify-content: space-between; align-items: center; padding: 33.1px 66.1px`

**Text style:** `footer` — te-20 300 · 16px/1.5

**Observed:** A single shallow row: locale selector at left, utility links in the centre, copyright at right. Light pages invert the text and backing; the collage campaign uses warm black.

**States:** Declared: hover text-decoration underline on links; focus-visible and active unspecified.

### Explore link

**Only for:** system overview pages

**Use:** Low-key navigation after product descriptions.

**CSS:** `color: #0071bb; text-decoration: none`

**Text style:** `system-link` — te-20 300 · 26.4px/1.1111

**Observed:** An unboxed text action, sometimes centred under an introductory paragraph and sometimes left-aligned below a specification list.

**States:** Declared: hover text-decoration underline; focus-visible and active unspecified.

### Catalogue closing call

**Only for:** catalogue pages

**Use:** A concise final invitation after the image-led catalogue.

**CSS:** `background: #0f0e12; color: #e5e5e5; height: 103px; text-align: center; padding-left: 66.1px; padding-right: 66.1px`

**Text style:** `system-heading` — te-40 300 · 39.7px/1.1111

**Observed:** One mixed-case sentence centred in a dark strip immediately above the light utility footer.

**Transfer:** Join one concrete service fact to a direct shopping invitation.

## Imagery and graphics

### Campaign poster

**Use:** Default marketing opening and visual identity anchor.

**Observed:** A grainy, dark photographic scene fills the viewport edge to edge. A forceful human gesture is centred, with red details supplying energy; thin white outlined product lettering crosses the subject. Small descriptors sit below the letters, with a restrained series label at the left.

**Transfer:** Choose an original photograph with one unmistakable gesture or an equally strong product silhouette. If no campaign shoot is possible, light a render against a near-black physical-looking set and retain the outline word sculpture.

**Build:** Create the product name as original SVG outline paths with transparent fill and a pale 4px stroke at a 1440px artboard width. Give the word roughly 660px total width and 210px visible capital height; centre it across the subject, with a short orange descriptor lower-left and a light two-line functional descriptor lower-right.

### Material macro and assembly

**Use:** Recurring proof of physical quality.

**Observed:** Close views of brushed metal, glossy black display glass, moulded keys and coloured controls extend full width. Shallow depth of field and raking light reveal texture; an exploded key stack places translucent housings, spring and circuit layers on a pale ground with numbered markers.

**Transfer:** Show actual joints, seams, controls or material layers. For software or services, substitute an original exploded process diagram with a similarly controlled neutral ground.

### Bench product portrait

**Use:** Object reveal, demonstrations, commerce and family overviews.

**Observed:** Frontal cut-outs on light grey alternate with dramatic black studio photography. Soft contact shadows belong to the object itself; metal edges, perforations and tiny orange details remain legible. Hands occasionally establish scale and tactility.

**Transfer:** Use consistent camera height and lighting for commerce, then change scale radically for editorial chapters. Retain natural material colour instead of washing the whole scene orange.

### Technical linework

**Use:** Demonstration and end-of-page engineering proof.

**Observed:** Orthographic front, side and back drawings use pale fine lines on black; dimensions and arrowheads sit outside the object. Workflow illustrations use black fine lines on grey with a single orange title bar.

**Transfer:** Draw a simplified but accurate vector elevation or process schematic; include only labels that help explain the new product.

**Build:** Use an SVG with unfilled geometry and 1px strokes, circles and rounded rectangles for repeated features, thin dimension leaders and small triangular arrowheads. Reverse stroke colour between black technical bands and pale workflow panels.

### Print repeat and annotation stickers

**Use:** Signature playful interruption around technical demos and merchandise.

**Observed:** A faint diagonal line-art repeat covers the blue-grey commerce backing. A few white-edged comic figures, orange starbursts and speech bubbles overlap card edges; the surrounding layout remains highly ordered.

**Transfer:** Use original small pictograms and brief spoken annotations tied to the product. Keep the neutral repeat barely perceptible and the stickers isolated.

**Build:** Tile a 48px SVG containing two original outlined geometric marks at low white opacity; rotate the repeat 45 degrees over #989fa5. For a sticker, wrap a simple black line drawing in a 4px off-white outline, add one orange polygon speech bubble, and overlap a single panel corner. Keep lettering short and the drawing roughly 80–140px wide.

### Printed tabletop collage

**Only for:** printed-collage campaigns

**Use:** A warmer campaign universe spanning opening, feature explanations, contributors and merchandise.

**Observed:** Top-down photographs layer kraft packaging, torn paper, printed inserts, fabric, tape and coiled cables. Forest-green and orange screenprint-like graphics repeat across objects; photographic grain, folds and imperfect paper edges remain visible. Copy is composed as printed matter within the scene.

**Transfer:** Photograph a coherent kit of original packaging and working materials on a pale tabletop. The minimum version is a small real still life plus one restrained printed feature card, not a pile of digital torn-paper filters.

**Build:** Layer three paper rectangles at slight differing angles over a kraft-coloured plane, then one fabric fold and a looping cable. Use green and orange two-colour vector marks on paper surfaces, a sparse halftone portrait or object illustration, subtle edge shadows and irregular paper masks. Prefer real material photographs over synthetic noise.

### Packaging farewell

**Only for:** system overview pages

**Use:** A last tactile image after specifications.

**Observed:** A hand lowers a pale rectangular package onto two neatly stacked boxes, shot close on a nearly white ground. It fills the final visual chapter and then yields directly to the light footer.

**Transfer:** Close a family overview with a simple physical act involving storage, packing or putting the product away, rather than adding another sales headline.

### Icons

**Observed:** Functional arrows are sparse black line symbols, in 44px square controls for the workflow viewer and 22px controls for system carousels. Product-use illustrations are much larger square pictograms; the opening navigation pairs thin line drawings with small multi-line labels.

**Transfer:** Keep navigation and controls linear and utilitarian. Reserve filled pictograms and cartoon gestures for explanatory or campaign artwork; do not scatter a generic icon before every heading.

## Section recipes

How recurring sections are built.

### First screen: Poster opening

**Observed:** The first screen is a full-width photographic poster continuing through a 1249px opening chapter. Back to front: dark grainy scene, central human gesture, large pale outline product-name artwork crossing the lower torso, small orange and pale functional descriptors, a small series label at left, then the slim illustrated navigation across the top. The word artwork occupies roughly half the viewport width, with about 210px visible capital height. Within 900px the navigation, figure, outline name and two descriptor blocks are visible; the photograph continues below the fold. The physical product reveal and 41px Message ticker arrive later, and there is no oversized hero button. The display recipe governs subsequent campaign headings; the opening name is a graphic treatment rather than a filled text headline.

**Transfer:** Make an original action photograph or strongly lit product scene, overlay a short outline name and two compact descriptors, and preserve the image-first first impression. A system overview can instead open with a full-width dark product film and a small watch action, followed by a centred introduction; a catalogue opens with a single cinematic product portrait and a tiny label.

**Avoid:** Do not replace the poster with a split SaaS hero, a floating dashboard, a large orange CTA or a paragraph of sales copy above the image.

**Text style:** `display` — TechnoType 700 · 52.9px/1.1111

### Tab and statement

**Observed:** Headline tab is centred above a 902px-wide statement column, usually with a 54px gap. Short supporting copy is visually uppercase, tight and centred. A small purchase control can follow; the surrounding ground stays nearly white.

**Transfer:** Use a short headline as the chapter's printed label and one focused product benefit beneath it.

**Text style:** `statement` — TechnoType 500 · 26.4px/1.1111

### Three-step demonstration

**Observed:** Three compact image demonstrations sit in a row below a chapter statement, each with small captions. Workflow viewer expands this into a broad diagram followed by three aligned caption columns.

**Transfer:** Explain use through actions and visible results. Keep the demonstration separate from the specifications inventory.

**Text style:** `caption` — TechnoType 700 · 13.2px/1.1111

### Material chapter

**Observed:** A full-width macro or exploded assembly carries the section; tiny corner captions or numbered leaders explain what is being shown. Assembly ground gives the exploded component room to breathe.

**Transfer:** Move from whole object to construction detail, then return to an isolated view before a dense explanation.

### Merchandise chapter

**Observed:** Store strip introduces a large accessory still life on Patterned commerce ground. Purchase tile pairs follow in a centred two-column grid, punctuated by a few annotation stickers; another Store strip closes the shopping region.

**Transfer:** Group related options into calm pairs, preserving the image-first composition and compact purchase row.

### Technical close

**Observed:** Black technical band contains a left title, compact multi-column feature data and orange Resource links. A wide orthographic dimension drawing follows below; small rights text and Utility footer finish the page without another giant headline.

**Transfer:** End a product story with useful engineering proof and support destinations rather than a generic newsletter card.

**Text style:** `technical-heading` — TechnoType 400 · 26.4px/1.1111

### System comparison chapters

**Only for:** system overview pages

**Observed:** Centred mixed-case introductions use a 39.7px heading and 26.4px supporting paragraph on grey. Alternating 720px image/text halves then compare family members. Larger square use-case pictograms, port diagrams, a three-column accessory grid and a charcoal specification table extend the narrative.

**Transfer:** Use for a genuinely interconnected family, not for unrelated benefits of one item.

**Text style:** `system-heading` — te-40 300 · 39.7px/1.1111

### Collage credit roll

**Only for:** printed-collage campaigns

**Observed:** Warm credit ground holds a sculptural orange thank-you line over a long narrow list of beige names. A small collective thank-you statement follows, then a 32px orange information ribbon and the shallow dark Utility footer.

**Transfer:** For a collaboration-led release, close with real contributors and a short acknowledgement; retain the generous dark breathing space.

**Text style:** `credits` — TechnoType 400 · 19.1px/1.154

## Page flow

**Storyline:** campaign hook → object reveal → promise → demonstrations and material proof → related purchase options → useful technical close

### A single-product campaign balancing cultural energy with engineering credibility

1. **Hook** — Full-bleed action poster and outline product-name artwork, followed by a repeating message.
2. **Product reveal** — Oversized frontal product media on pale ground, then a tabbed promise and compact purchase control.
3. **Capability proof** — Short demonstrations alternate with macros, feature lists, workflow illustration and exploded construction.
4. **Purchase options** — Packaging story and related-object still life lead to paired commerce cards.
5. **Objection handling and close** — Bright store ribbon transitions to black specifications, support links, dimension drawings and a minimal footer.

**Transfer:** Choose one strong campaign metaphor and substantiate it with direct product evidence. Vary the length and order of proof chapters to fit the new product.

### An interconnected family overview with comparison and use-case depth

1. **Hook** — Dark full-width product film and small watch action.
2. **Promise** — Centred light mixed-case introductions and family portrait.
3. **Comparison** — Alternating square image/text rows, small uppercase feature bullets and blue explore links.
4. **Use cases** — Five-column pictograms and annotated connection studies.
5. **Purchase options** — Accessory film and edge-to-edge product grid.
6. **Technical proof and close** — Charcoal comparison table, then a final packaging photograph and light utility footer.

**Transfer:** Organize around how related tools work together; use the quieter typographic variant throughout this page type.

### A tactile, contributor-led printed campaign

1. **Hook** — Full-width tabletop collage with packaging, a large sculptural price and illustrated navigation.
2. **Demonstration** — Printed feature inserts alternate with full-width documentary performance videos and thin caption ribbons.
3. **Human proof** — Contributor portraits are arranged as dark printed cards on the physical collage.
4. **Purchase options** — Merchandise flat lays give way to generous white bundle stages with green actions and orange prices.
5. **Acknowledgement and close** — Portrait thanks, an extended credit roll, a narrow information ribbon and dark utility footer.

**Transfer:** Carry one coherent set of physical materials through the campaign and acknowledge actual collaborators where relevant.

### An image-led catalogue for discovery rather than detailed comparison

1. **Discovery hook** — One dramatically lit product occupies the opening, with illustrated navigation overlaid.
2. **Range exploration** — Long full-width product portraits alternate light and dark studio scenes, occasional human scale cues and small corner labels.
3. **Range compression** — Later products share split panels instead of receiving another full-screen chapter.
4. **Closing call** — A dark single-sentence delivery/store strip precedes the light utility footer.

**Transfer:** Treat the catalogue as an exhibition of objects, not a standard dense ecommerce thumbnail grid.

## Writing

Matter-of-fact engineering language with flashes of bravado and comic timing. Confidence is grounded in concrete controls, materials and operations rather than abstract lifestyle benefits.

**Do not copy:** Do not reuse brand names, product names, logos, licensed photographs, campaign characters, Japanese artwork, celebrity quotations, proprietary feature names, prices, performance claims or contributor lists. Source examples illustrate voice only; replace every factual claim with verified information for the new product.

- **Addressing the reader:** Use direct you/your when describing an action; we/our appears when describing design intent. Product descriptions can otherwise be impersonal and declarative.
- **Rhythm:** Short punchy chapter labels of roughly two to four words alternate with compact multi-sentence explanations. Technical lists are clipped fragments; actions are usually two or three words. Default campaign lettering looks uppercase, while the system voice is predominantly lowercase mixed case.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Chapter headline | A short active metaphor that can double as a printed label. | 2–4 words | “go the distance”<br>“one-two punch”<br>“take the studio with you.” |
| Support statement | Name a tangible property, then explain what it lets the user do. | 1–3 compact sentences | “vintage style keys with a modern touch, combining tactility with pressure sensitivity.”<br>“comes in a redesigned paper-pulp box, ideal for short trips and everyday carry.” |
| Demonstration caption | Lead with a direct operation and use specific nouns. | 15–35 words | “record sounds around you, sample your VOICE, favorite synthS, vinyl RECORDS OR WHATEVER AUDIO THAT YOU'VE GOT ON your phone.” |
| Action | Short verb plus destination or object. | 2–4 words | “add to bag”<br>“visit the guide”<br>“watch full video” |
| Closing invitation | One useful service fact followed by an unembellished action. | One short line | “worldwide delivery. visit our store.” |

**Words and phrasing to use:** built-in; standalone; connect; record; play; portable; everyday carry; workflow; explore

**Avoid:** revolutionize your life; unlock your potential; seamless ecosystem; elevate your experience; premium solutions

**Rules:**

- Write the headline as a label, not a complete advertising thesis.
- Earn superlatives with useful specifications nearby; do not invent category leadership.
- Separate benefit prose from compressed technical lists.
- Use humour in a chapter label or drawing annotation, not in every specification.
- Keep currency and price information blunt and easy to scan.

## Do's and Don'ts

### Do

- Use the 52.9px technical display recipe inside compact 68px headline bands.
- Keep core support statements centred within about 902px.
- Let a 1440px-wide product image extend beyond one viewport when its composition deserves it.
- Keep commerce gutters at 14.7px and the default card corners at 22px.
- Align names, prices and 93×31px controls along one bottom row.
- Use tiny 13.2px captions for diagrams and product proof, not expansive card descriptions.
- Give the black closing chapter real resource destinations and an accurate technical drawing.
- Keep sticker art isolated so the engineering grid remains legible.

### Don't

- Do not turn every action into a 48px-tall pill; purchase controls are compact rounded rectangles.
- Do not apply drop shadows to cards or add glass effects; depth belongs to photographed objects.
- Do not use heavy conventional bold sans as a substitute for the light-looking mechanical display cut.
- Do not spread orange across every section; concentrate it in labels, shallow strips and details.
- Do not fill the catalogue with boxed text-heavy cards; its dominant unit is the product photograph.
- Do not add letter spacing to tiny technical captions; the recipes use normal tracking.
- Do not mix the blue system-overview actions and forest-green collage actions into the default orange/black campaign.
- Do not finish every page with a generic rounded newsletter panel; the ending belongs to its page type.

## Motion and responsive

### Motion

**Observed:**

- Repeating message strips use horizontally translated tracks with clipped edges.
- A campaign background has a declared 250s linear infinite scrolling animation.
- Some surfaces declare background-color 0.2s and transform 0.2s ease-in transitions.
- Resource, explore and footer links declare an underline on hover.

**Transfer:**

- Use the ticker as a narrow graphic beat rather than a large moving headline.
- Keep slow repeat-pattern movement subordinate to the stationary product cards.

**Unknown:**

- Ticker timing, exact pattern displacement and most action focus/active treatments are unspecified.
- Film playback and scroll-trigger timing are not prescribed.

### Responsive

**Observed:**

- The desktop composition is 1440px wide with full-width media and a 66.1px side inset.

**Transfer:**

- On narrow screens, preserve the poster's focal subject and scale the outline name as one SVG graphic rather than wrapping its letters.
- Stack the two commerce columns and system split rows when product silhouettes or metadata would become cramped; keep the compact information row intact where it fits.
- Keep the ticker clipped to the viewport. Let technical drawings scroll or simplify their labels rather than shrinking them into illegibility.

**Unknown:**

- No mobile layout, breakpoint values or mobile navigation arrangement is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
