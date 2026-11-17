# Peak Design — fieldwork meets editorial

## Overview

A practical equipment brand with an unexpectedly literary streak: rounded uppercase sans headings sit beside expressive serif statements and matter-of-fact product information. Mostly white and cool gray, the pages alternate clean studio product studies with black editorial panels and richly observed outdoor, urban and workshop photography. The result suits tactile, well-engineered products, with spacious marketing chapters and denser shopping grids.

### Essentials

- Equipment lettering meets editorial serif: Bryant 700 capitals at 64px/1.1 with -0.005em tracking lead the opening; Exposure at 40px/1.1 or 48px/1.1 and -0.01em takes over for editorial chapters.
- The opening is a two-part campaign spread: a 727px-tall, equal-width media and dark-text-panel composition below a 121px navigation stack, with 64px panel padding and 24px gaps in the copy.
- Actions look like small hardware labels, not bubbles: 4px corners, 1px borders, uppercase Bryant 700 at 14px/1, 40px height and 8px 16px padding; editorial actions step up to 48px and 16px type.
- Color belongs to the objects and their environments: most structural area stays white, cool gray or black; strong campaign color is contained inside the media half rather than spread across the interface. Green prose and charts belong to reporting pages.
- A serif chapter title ends in a long horizontal dash, then gives way to photographic tiles: 40px titles, 32px uppercase tile labels, 8px tile corners and 24px gutters form a recurring signature. Recreate the dash and the real-world photographic staging on new pages; use tightly framed hands, materials or working environments if the product itself is not photogenic.
- Products are shown twice, as isolated objects and as tools in use: pale 4:5 studio stages alternate with close physical interactions and documentary scenes. The same object must feel tangible in both treatments.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Equipment ink | `#1a211e` | `--color-ink` | text, action, border | Default commerce text, filled actions and selected controls. |
| Editorial black | `#000000` | `--color-black` | background, text | Editorial bands and serif titles. |
| Utility black | `#0c0c0c` | `--color-bar` | background | Top utility strip and dark product swatches. |
| Campaign charcoal | `#15151a` | `--color-hero-dark` | surface | Default opening copy panel. |
| Muted green-gray | `#606562` | `--color-muted` | text | Variants, navigation support and secondary commerce information. |
| Input edge | `#cccfcd` | `--color-input-edge` | border | Inputs and unselected swatch outlines. |
| Header edge | `#e6e9e8` | `--color-header-edge` | border | Thin bottom rule under the navigation. |
| Cool mist | `#eef1f0` | `--color-panel` | surface, border | Editorial product panels and inactive category controls. |
| Studio white-gray | `#f7f7f7` | `--color-stage` | surface | Visible studio-stage tint; black at 3% opacity over white. |
| Chalk action | `#fbfdfc` | `--color-button-light` | action, border | Filled reverse buttons and circular tile arrows. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Main page canvas and reversed text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial reports | Report green | `#30a46c` | `--color-green` | text, accent | Report section prose, labels and data accents; not a default commerce CTA color. |
| editorial reports | Report charcoal | `#21201c` | `--color-report-ink` | text, accent | Report statistics and progress marks. |
| editorial reports | Report gray | `#63635e` | `--color-report-muted` | text | Monospaced report captions and sources. |
| editorial reports | Report track | `#dad9d6` | `--color-progress-track` | surface | Fine progress tracks beneath reported targets. |
| editorial reports | Report paper | `#fdfdfc` | `--color-paper` | background, text | Warm report canvas and reversed report text. |

## Typography

- **Bryant** — Uppercase campaign headlines, category titles, buttons and navigation labels. Rounded, open geometric sans with a friendly, utilitarian silhouette. If unavailable, use **Nunito Sans**. Use 700 for headlines and actions, 500 for tabs; preserve uppercase and measured tracking. Font stack: "Bryant", "Nunito Sans", Arial, sans-serif.
- **Exposure-10** — Editorial headings and section titles. Expressive serif with sturdy curved forms and lively terminals; sentence case contrasts with the equipment lettering. If unavailable, use **Fraunces**. Use 400; keep line breaks compact and optical contrast moderate. Font stack: "Exposure-10", "Fraunces", Georgia, serif.
- **Geist** — Body copy, navigation, product names and supporting information. Neutral contemporary grotesk; functional rather than expressive. Font stack: "Geist", Arial, sans-serif.
- **Geist Mono** — Technical color-count captions and report labels. Even-width, compact technical lettering. Font stack: "Geist Mono", ui-monospace, monospace.
- **Bryant Pro** (only for editorial reports) — Report statistics and compact equipment headings. Bold rounded sans with tabular numerals for data. If unavailable, use **Nunito Sans**. Use 700; tabular numerals for metrics. Font stack: "Bryant Pro", "Nunito Sans", Arial, sans-serif.
- **Exposure[-10]** (only for editorial reports) — Green introductory prose and the report closing appeal. The same literary serif character in smaller running text and centered closing type. If unavailable, use **Fraunces**. Use 400, retaining the report-specific leading. Font stack: "Exposure[-10]", "Fraunces", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Bryant | 700 | 64px | 1.1 | -0.005em, uppercase | Main split-campaign headline, usually three lines. |
| editorial-heading | Exposure-10 | 400 | 48px | 1.1 | -0.01em | Short benefit or release statement in a split panel. |
| section-title | Exposure-10 | 400 | 40px | 1.1 | -0.01em | Chapter heading, often followed by a long dash. |
| editorial-emphasis | Exposure-10 | 400 italic | 40px | 1.1 | -0.01em | A single emphasized word inside a sentence-case editorial heading. |
| tile-title | Bryant | 700 | 32px | 1.1 | normal, uppercase | Lower-left title over photography. |
| footer-heading | Bryant | 700 | 24px | 1 | normal, uppercase | Footer column and location headings. |
| eyebrow | Bryant | 700 | 16px | 1.2 | 0.0375em, uppercase | Short subject label above campaign and editorial headings. |
| body | Geist | 400 | 16px | 1.4 | normal | Compact supporting paragraphs in campaigns and split panels. |
| product-name | Geist | 700 | 16px | 1 | normal | Product names beneath studio images. |
| button-editorial | Bryant | 700 | 16px | 1 | normal, uppercase | 48px-high editorial panel actions. |
| caption | Geist | 400 | 14px | 1 | normal | Variants, supporting product metadata and footer links. |
| button | Bryant | 700 | 14px | 1 | normal, uppercase | Compact campaign actions, filtering controls and signup actions. |
| category-tab | Bryant | 500 | 14px | 1 | 0.057em, uppercase | Category selector tabs above a carousel. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| collection pages | collection-display | Bryant | 700 | 64px | 1 | -0.005em, uppercase | Collection title over a wide environmental image. |
| editorial reports | report-closing | Exposure[-10] | 400 | 48px | 1.2 | -0.02em | Centered closing appeal on a dark illustrated field. |
| editorial reports | report-lead | Exposure[-10] | 400 | 24px | 1.4 | normal | Green prose introducing a reporting chapter. |
| editorial reports | report-stat | Bryant Pro | 700 | 24px | 1.2 | normal, uppercase, features "tnum" | Percentages and values aligned against mono descriptions. |
| editorial reports | report-label | Geist Mono | 400 | 12px | 1.5 | 0.02em, uppercase | Section labels, captions and dataset descriptions. |

**Notes:**

- Three voices share the hierarchy: rounded capitals announce and label, serif sentences editorialize, and Geist handles practical detail.
- The serif is regular, not bold. Large sans headlines use only mildly negative tracking; tabs and eyebrows deliberately open up.
- Report numerals use the bold visual cut even though its family declaration uses weight 400. Mono labels remain small and quiet.

## Layout

**Density:** Airy editorial chapters surround compact product information; broad section padding contrasts with short label and metadata gaps.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon gaps and compact button vertical padding. |
| 12px | Product metadata stacks. |
| 16px | Product information padding, small control side padding and form gaps. |
| 20px | Tile overlay inset and paired hero action gap. |
| 24px | Default copy stack and marketing-grid gutter. |
| 32px | Collection outer padding and chapter-title-to-tile separation. |
| 40px | Utility-strip side padding and carousel heading space. |
| 64px | Default desktop section, panel and page side padding. |
| 128px | Combined outer and inner inset in boxed split editorial chapters. |

### Containers and grids

- **marketing-frame**: max width 1440px · side padding 64px. At desktop, boxed chapters occupy 1312px within the page; full-bleed campaigns escape the side gutter.
- **split-campaign**: 2 columns · gap 0px. Equal media and copy halves; the text half has 64px padding and copy no wider than 640px.
- **category-grid**: 3 columns · gap 24px. Square 421px photographic tiles at desktop; shorter editorial tiles use the same columns with 281px height.
- **product-carousel**: 4 columns · gap 24px. Four approximately 332px-wide studio products in the marketing carousel.
- **collection-grid** (only for collection pages): 4 columns · gap 8px · side padding 32px. 338px product stages, with 64px row gaps and tightly packed columns.
- **report-frame** (only for editorial reports): max width 1440px · side padding 24px. Fine outlined report modules; inner 16px insets put readable content 40px from the window edge.
- **letter-column** (only for editorial reports): max width 550px. Centered personal introduction followed by an explanatory diagram.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 4px |
|  | photo-tiles | 8px |
|  | tile-arrow | 50% |
| collection pages | swatches | 2px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Main page surface.

**CSS:** `background: #ffffff; color: #1a211e`

**Observed:** Untextured and flat, with broad space between chapters.

**Transfer:** Let photography carry the material character.

#### Campaign charcoal · level 0

**Use:** Opening copy panel.

**CSS:** `background: #15151a; color: #ffffff; padding: 64px`

**Observed:** Full-height partner to a vivid media panel; edges remain square.

**Transfer:** Keep the copy field solid so complex artwork has a calm counterweight.

#### Editorial black · level 0

**Use:** Release and documentary chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Used as a full-width band or the narrow text third of a boxed image story.

**Transfer:** Alternate scale and placement rather than making every dark chapter identical.

#### Cool mist panel · level 0

**Use:** Product editorial copy or grouped object study.

**CSS:** `background: #eef1f0; padding: 64px`

**Observed:** Flat pale green-gray, joined edge-to-edge with a tall lifestyle photograph.

**Transfer:** Use for an object-plus-story pairing, not as a raised card.

#### Studio stage · level 0

**Use:** Isolated catalog product images.

**CSS:** `background: rgba(0, 0, 0, 0.03); aspect-ratio: 4 / 5`

**Observed:** Pale stages contrast very gently with the white canvas; realistic product shadows remain inside the imagery.

**Transfer:** Maintain consistent image bounds while allowing object proportions to vary.

#### Report paper · level 0

**Only for:** editorial reports

**Use:** Data and documentary editorial canvas.

**CSS:** `background: #fdfdfc; color: #21201c`

**Observed:** Modular two-column compositions, thin framing rules and no raised cards.

**Transfer:** Separate prose, charts and legends into adjoining flat cells.

## Components

### Sticky navigation

**Use:** Persistent commerce navigation.

**CSS:** `position: sticky; top: 0px; z-index: 20; background: #ffffff; border-bottom: 1px solid #e6e9e8`

**Observed:** A 40px black utility strip sits above an 80px white row containing a small angular mark, category links, wide search, support, account and cart. The white row remains visible during long shopping journeys.

**Transfer:** Keep the search and practical utilities prominent; use the new brand's own small mark.

### Reverse button

**Use:** Primary action on the opening dark panel.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 40px; padding: 8px 16px; background: #fbfdfc; color: #1a211e; border: 1px solid #fbfdfc; border-radius: 4px`

**Text style:** `button` — Bryant 700 · 14px/1 · uppercase

**Observed:** Label precedes a compact right arrow; paired with an outlined action rather than a second filled button.

**Transfer:** Use a short verb and object, not a sentence.

### Outline button

**Use:** Secondary action beside a filled hero action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 8px 16px; background: transparent; color: #ffffff; border: 1px solid #ffffff; border-radius: 4px`

**Text style:** `button` — Bryant 700 · 14px/1 · uppercase

**Observed:** Same compact geometry as the reverse action; the pair has a 20px gap.

### Editorial button

**Use:** Action on a light editorial panel.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 48px; padding: 12px 24px; background: #1a211e; color: #ffffff; border: 1px solid #1a211e; border-radius: 4px`

**Text style:** `button-editorial` — Bryant 700 · 16px/1 · uppercase

**Observed:** A larger sibling of the campaign action. On black sections the fill reverses to chalk with dark text.

### Category tab

**Use:** Select a product family above the carousel.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 8px 16px; background: #eef1f0; color: #1a211e; border: 1px solid #eef1f0; border-radius: 4px`

**Text style:** `category-tab` — Bryant 500 · 14px/1 · tracking 0.057em · uppercase

**Observed:** Tabs sit in a compact row with 4px gaps. The selected item reverses to ink with white type; circular previous and next controls sit at the opposite end.

### Photographic tile

**Use:** Browse categories or related editorial stories.

**CSS:** `position: relative; background: #000000; border-radius: 8px; overflow: hidden`

**Text style:** `tile-title` — Bryant 700 · 32px/1.1 · uppercase

**Observed:** Edge-to-edge photograph with a subtle dark veil, lower-left title and lower-right 32px chalk circle containing an arrow. Overlay content is inset 20px. Category tiles are square; editorial tiles are landscape.

**Transfer:** Keep real physical context visible behind the label.

### Product card

**Use:** Commerce carousel and collection browsing.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `product-name` — Geist 700 · 16px/1

**Observed:** A 4:5 Studio stage sits above an unboxed white metadata area: bold product name, muted variant, price, then mono color count or square swatches. Information stacks use 12px gaps and 16px vertical padding. Some collection cards carry a small status pill at the image's upper-left.

**Transfer:** Use the image, not an enclosing border or shadow, to group the card.

### Email input

**Use:** Footer newsletter subscription.

**CSS:** `height: 40px; padding: 2px 12px; background: #ffffff; border: 1px solid #cccfcd; border-radius: 4px`

**Observed:** The field shares a row with a compact ink signup button, separated by 16px. Search uses the same outline language at 48px height with extra left space for a search icon.

### Footer columns

**Use:** Practical closing navigation and ongoing relationship.

**CSS:** `display: grid; grid-template-columns: 1fr 560px; padding: 64px`

**Text style:** `footer-heading` — Bryant 700 · 24px/1 · uppercase

**Observed:** Three narrow link columns occupy the left; location abbreviations and newsletter occupy the wider right. Beneath them a long rule leads to social icons and locale, then legal links, a centered brand/copyright group and small certification marks.

**Transfer:** Preserve the utilitarian density and the generous white space around the bottom rows.

### Selected swatch

**Only for:** collection pages

**Use:** Product color selection.

**CSS:** `width: 20px; height: 20px; background: #0c0c0c; border-radius: 2px; outline: 2px solid #1a211e; outline-offset: 1px`

**Observed:** Small squares in a wrapping row with 8px gaps; unselected choices use a 1px pale outline. Color belongs to the actual variant.

**Transfer:** Keep the selected outline distinct from the swatch color.

### Report target row

**Only for:** editorial reports

**Use:** Communicate measured progress.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 8px`

**Text style:** `report-stat` — Bryant Pro 700 · 24px/1.2 · uppercase

**Observed:** A 12px mono target description faces a 24px bold percentage; an 8px gap separates the label row from a 2px gray track with charcoal proportional fill. Groups have 24px vertical spacing.

**Transfer:** Use real values and denominators, retaining small typography rather than inflating every statistic.

## Imagery and graphics

### Campaign object poster

**Use:** The media half of the opening.

**Observed:** A warm yellow poster contains upright isolated products in staggered columns, cut by the bottom edge; their material grain and soft shadows remain visible. Pale mint lettering with heavy black offset edging makes the artwork playful, while the adjacent website typography stays restrained. The artwork occupies half the opening, not the whole page.

**Transfer:** Create a colorful material study of the new product in several configurations. If bespoke poster art is unavailable, use a clean arrangement of three to six real object photographs on one warm field, keeping the website headline separate.

**Build:** Use a rectangular warm ochre image background with three staggered columns of transparent object photographs. Give objects soft downward shadows using rgba(0,0,0,0.2), 8px offset and 12px blur. Clip the lowest objects at the frame edge. If including lettering within the art, use a stout serif with pale mint fill, 2px black stroke and 4px black offset shadow; treat these colors as local illustration colors, not UI tokens.

### Studio object study

**Use:** Product browsing and the object portion of editorial splits.

**Observed:** Front or three-quarter product views sit centrally on very pale gray. Dark hardware, fabric weave and leather are lit softly enough to show surface detail. Scale varies with object proportions but stages remain consistent.

**Transfer:** Photograph or render the object with diffuse neutral light, believable contact shadows and no decorative props. For intangible products, stage a physical interaction or a clean representation of the deliverable rather than inventing an empty object tile.

### Working-world photography

**Use:** Category tiles, full-width collection openings and lifestyle halves of splits.

**Observed:** People carry and manipulate equipment in woods, streets, public transit and travel settings. Frames are close, often cutting faces or limbs; the product is legible through use rather than isolated against scenery. Natural greens, browns, subdued city colors and dark fabric dominate.

**Transfer:** Show a credible user performing one concrete task. Choose foreground texture and useful hand positions; retain natural color instead of applying a strong brand-color filter.

### Mechanism closeup

**Use:** Dark product demonstration chapter.

**Observed:** A large right-hand crop shows fingers operating a small clip on textured fabric. Tight focus, dark hardware and skin tones convey physical function against a black page band.

**Transfer:** Use a close physical interaction that explains the mechanism. For software, use a focused action demonstration with surrounding context minimized, retaining the text/media split.

### Documentary craft

**Use:** Editorial proof stories.

**Observed:** A wide, candid workshop view shows a maker sewing at a crowded workbench; a black text panel attaches to the image's right edge. Report storytelling also includes hiking groups and monochrome archival film imagery.

**Transfer:** Document the actual process or people behind the product with ambient light and visible work surfaces; pair it with a specific, supportable explanation.

### Report topographic field

**Only for:** editorial reports

**Use:** Immersive closing appeal.

**Observed:** A dark green-black 1360px by 720px field surrounds centered white text with sparse mint mountain chevrons and meandering dashed paths. Marks gather around the perimeter, leaving the center open.

**Transfer:** Translate the idea into a diagrammatic landscape related to the new subject while preserving the quiet central clearing.

**Build:** On the ink background, place SVG groups of open two-segment chevrons, 8–28px wide, with 1px pale green strokes at roughly 60% opacity. Scatter groups near corners and side edges, varying scale. Add two irregular curved paths with 1px muted green strokes, 5px dash spacing and no fill. Keep the central half nearly empty.

### Report word sculpture

**Only for:** editorial reports

**Use:** Opening title artwork.

**Observed:** A cream equipment-style word repeats in a tall stack on the dark left half, alternating upright and inverted forms. Thin vertical rules flank the stack; tiny report identifiers anchor it above and below. The other half is an immersive mountain photograph.

**Transfer:** Use a short subject word rather than the original wording, with a matching typographic sculpture.

**Build:** Build an SVG with four stacked copies of a short uppercase word in a wide-tracked mono-like sans. Flip alternate rows vertically and use tightly shared baselines. Flank the stack with 2px vertical cream lines and align small identifiers to the left edge. Center the complete sculpture within half the viewport.

### Report green data fan

**Only for:** editorial reports

**Use:** Quantified proof.

**Observed:** Large semicircular donut and circular pie forms use discrete green steps from deep forest to pale mint. Legends pair small square color keys, mono descriptions and right-aligned bold values; the charts are flat, without axes, glows or gradients.

**Transfer:** Use a pie only for real parts of a whole, with a matching textual legend.

**Build:** Use SVG path sectors in a seven-step green ramp. For a semicircular donut, clip the circle to its upper half and remove a centered inner circle about half its diameter. Put the legend below, with 32px square keys, 12px mono labels and 24px bold tabular values.

### Icons

**Observed:** Small monochrome utility symbols: 16px arrows inside actions, 24px search/account/cart symbols, and 32px social symbols. Tile arrows sit in 32px circular chalk fields; carousel arrows use 48px outlined circles.

**Transfer:** Choose simple recognizable SVG silhouettes and fine outline utility icons. Match text color and preserve compact placement rather than adding colorful icon badges.

## Section recipes

How recurring sections are built.

### First screen: Split campaign opening

**Observed:** Below the 121px navigation stack, a full-width 727px campaign is divided into equal halves. Back to front: vivid campaign object poster on the left, flat Campaign charcoal on the right, then a vertically centered, left-aligned copy stack inset 64px. An equipment eyebrow precedes the white 64px uppercase display, wrapping into three substantial lines; a short support paragraph and Reverse button plus Outline button follow with 24px vertical gaps. The object poster fills its half and clips at the bottom, whereas text has clear breathing room. Within the first 900px, navigation, the entire campaign headline, supporting text, both actions and the main object arrangement are visible. Only a narrow white start of the next chapter appears; its title is below the fold.

**Transfer:** Preserve the balanced media/copy contrast for a new product, using an original object arrangement or close material study if no campaign poster exists. Collection pages instead open with a 480px environmental photograph, a 64px/1 uppercase heading and short white support copy aligned left. Reports use a full-viewport split between a typographic word sculpture and a landscape photograph.

**Avoid:** Do not turn the media into a small floating thumbnail, center all the text across both halves, or place the website headline on top of busy poster lettering.

**Text style:** `display` — Bryant 700 · 64px/1.1 · tracking -0.005em · uppercase

### Dashed chapter and browsing grid

**Observed:** A Section title sits at the left edge of the 64px marketing frame and ends in a long horizontal dash. Product browsing adds Category tabs and circular arrows; category browsing uses Photographic tiles in three columns with 24px gaps. The heading-to-tile separation is 32px.

**Transfer:** Use the dash as a recurring editorial marker, then choose a carousel for comparable objects or a photographic grid for distinct use cases.

### Lifestyle and object editorial spread

**Observed:** A boxed equal split joins a tall edge-to-edge lifestyle image with a Cool mist panel. Inside the panel, a clean object group sits above the eyebrow, 48px editorial heading, compact paragraph and Editorial button. The outer frame is inset 64px; the combined card clips to 8px corners.

**Transfer:** Pair lived context with a clear object or configuration study, explaining one meaningful distinction rather than listing every feature.

**Text style:** `editorial-heading` — Exposure-10 400 · 48px/1.1 · tracking -0.01em

### Black mechanism chapter

**Observed:** A full-width Editorial black band holds a left copy stack inset from the main frame and a large right closeup. The 48px serif statement, 16px eyebrow, support and light Editorial button occupy less area than the image. Desktop content is separated by 24px internal gaps.

**Transfer:** Make one feature tangible through a physical action or tightly framed demonstration rather than a feature-icon matrix.

### Documentary story strip

**Observed:** Within the 64px page frame, an approximately two-thirds-width workshop photograph joins a one-third-width black copy panel. The latter contains an eyebrow, 40px serif statement, short paragraph and film action. The whole strip has a restrained rounded outer edge.

**Transfer:** Use a demonstrable process, craftsmanship story or independently supportable proof point, with the image doing most of the emotional work.

**Text style:** `section-title` — Exposure-10 400 · 40px/1.1 · tracking -0.01em

### Hands-on closing bridge

**Observed:** The final marketing chapter uses a pale split band: left-aligned eyebrow, a 40px serif sentence with one italic word and practical supporting copy face a 656px by 369px retail interior image. It leads directly into Footer columns rather than a giant sales slogan.

**Transfer:** Close with a concrete next interaction—try, find, visit or learn—before the practical footer. Choose a real environment that supports the interaction.

**Text style:** `section-title` — Exposure-10 400 · 40px/1.1 · tracking -0.01em

### Collection shopping field

**Only for:** collection pages

**Observed:** A horizontal filter rail follows the photographic opening, with compact uppercase text controls, result count and sorting. Below, four Product cards per row use 8px column gaps and 64px row gaps. Occasional editorial promotion cards replace a product cell with a closeup above a cool-gray message panel.

**Transfer:** Keep dense comparison efficient; insert useful product guidance at product-cell scale, not an unrelated full-width interruption.

### Report chapter and quantified proof

**Only for:** editorial reports

**Observed:** A 12px mono label precedes a 24px green serif paragraph with 24px separation. Adjoining flat cells place prose or documentary media against charts and compact legends. Target groups use Report target rows; chart legends pair 32px square keys with right-aligned 24px values. Captions sit directly below photography in uppercase mono.

**Transfer:** Use precise dates, scopes and denominators; balance qualitative narrative against small readable metrics.

**Text style:** `report-lead` — Exposure[-10] 400 · 24px/1.4

### Report appeal and restrained ending

**Only for:** editorial reports

**Observed:** A 40px-inset Report topographic field holds a centered equipment label, 48px serif appeal, short support and an outlined mono action with separated arrow cell. After this dark field, the page ends in a short white footer with policy links and copyright, not the commerce footer.

**Transfer:** End a report with one concrete participation action and a compact accountability footer.

**Text style:** `report-closing` — Exposure[-10] 400 · 48px/1.2 · tracking -0.02em

## Page flow

**Storyline:** campaign promise → useful product discovery → lived-use demonstration → editorial proof → concrete next interaction → practical footer

### Marketing landing page that balances product discovery with brand credibility

1. **Promise** — Equal-width campaign artwork and uppercase dark-panel statement with paired actions.
2. **Product discovery** — Tabbed best-seller carousel followed by a dashed serif chapter title and photographic category grid.
3. **Capability chapters** — Alternating pale lifestyle/object spread and black closeup demonstration.
4. **Credibility** — Editorial browsing tiles and a wide documentary story strip.
5. **Closing interaction** — Pale hands-on discovery bridge, then a complete commerce footer.

**Transfer:** Adapt the number and arrangement of chapters to the new product while preserving the alternation of isolated object, use context and editorial proof.

### Collection page optimized for sustained comparison

1. **Orientation** — Environmental banner with short uppercase category title and supporting sentence.
2. **Product comparison** — Sticky shopping utilities and a dense four-column catalog with variants, prices and swatches.
3. **Objection handling** — Editorial product and warranty messages inserted into catalog cells.
4. **Ongoing relationship** — Catalog ends in the same white multi-column footer with location links and signup.

**Transfer:** Let browsing dominate; keep educational interruptions the size of a catalog tile and retain a proper ending even after long grids.

### Editorial report mixing personal narrative, documentary proof and quantified accountability

1. **Identity and orientation** — Full-screen split with word sculpture, immersive landscape and report-download action.
2. **Human introduction** — Narrow centered letter, portrait and strategy diagram.
3. **Quantified proof** — Green serif chapter summaries alternate with targets, maps, chart cells and photographic stories.
4. **Participation** — Dark illustrated field with a centered appeal and one action.
5. **Accountability** — Short policy-link footer and copyright.

**Transfer:** Keep this quieter report variant scoped to long-form accountability or research stories, using the new project's own reporting structure rather than the original topics.

## Writing

Confident, direct and outdoors-literate, with a little irreverence. Practical specifications coexist with warm editorial lines; accountability copy admits complexity instead of sounding self-congratulatory.

**Do not copy:** Do not reuse Peak Design names, product names, logos, proprietary feature names, original campaign artwork, slogans, certifications, warranty promises, report statistics or company claims. Examples illustrate cadence, not claims available to another product.

- **Addressing the reader:** Use you and your for use cases and invitations; we and our for concrete organizational actions. Product metadata stays impersonal.
- **Rhythm:** Short sentence-case serif statements contrast with uppercase equipment labels. Support often uses brief fragments or a single plain sentence; reporting paragraphs can be longer but stay concrete.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Campaign headline | A plainly stated expansion of choice or usefulness, not an abstract manifesto. | 5–9 words | “With More Options Than Ever Before” |
| Editorial headline | A conversational promise with a small turn of phrase. | 4–8 words | “Your next essential just dropped.”<br>“Three colors you’ll only find with us.” |
| Supporting line | Specific materials, options or use case; fragments are acceptable when informative. | 1–3 short sentences | “Discover new arrivals to inspire your next adventure.”<br>“Camera gear that offers beautiful functionality for both professional and casual photographers.” |
| Action | Verb plus product, activity or destination. | 2–5 words | “Shop New Arrivals”<br>“Watch the Film”<br>“Download the full report” |
| Report narrative | Describe the work, acknowledge imperfection, and explain the next action. | 2–4 direct sentences | “We conducted social and environmental audits on all of our Tier 1 factories. Some aced it, others need work. We don’t just walk away from the tough ones—we work with them, track progress, and push for better conditions.” |

**Words and phrasing to use:** thoughtfully designed; essential; new arrivals; hands-on; gear; your next; we track; we work with

**Avoid:** revolutionary ecosystem; unparalleled excellence; disruptive innovation; luxury redefined; effortlessly seamless

**Rules:**

- Lead with the object or what someone can do with it, then name the practical distinction.
- Keep headline warmth separate from specification detail; the support line can carry compatibility and materials.
- Make an invitation actionable, not a vague 'Discover more' on every button.
- Report progress with dates and scope, and make room for work still to be done.

## Do's and Don'ts

### Do

- Use 64px rounded uppercase sans for the opening and regular 40–48px serif for editorial chapters.
- Keep 64px desktop side gutters around ordinary marketing chapters.
- Maintain 24px gutters between photographic tiles and 12px gaps inside product metadata.
- Pair a 40px chalk-filled action with a 40px outlined action on the dark opening panel.
- Use 8px photographic tile corners and 4px control corners as distinct families.
- Show the product both on a pale 4:5 stage and in a credible lived setting.
- Carry the long-dash chapter title device into the new page.
- End with useful navigation and an ongoing interaction rather than abandoning the page after the last image.

### Don't

- Do not replace the rounded equipment sans with a condensed industrial display face.
- Do not bold every serif heading; its default weight is 400.
- Do not turn all 4px buttons into pills; circles belong to arrow controls.
- Do not apply report green to ordinary shopping buttons or large commerce backgrounds.
- Do not add floating shadows around each product card; product grouping is flat and image-led.
- Do not use the collection's 8px column gutters for the marketing photographic grid, which uses 24px.
- Do not make supporting commerce text monospaced; Geist handles the practical reading.
- Do not scale ordinary report statistics into giant numerals; their measured treatment is 24px against 12px labels.

## Motion and responsive

### Motion

**Observed:**

- The commerce header is sticky and product discovery includes horizontal carousel controls.
- Report text links declare a hover change to charcoal with an underline.

**Transfer:**

- Keep horizontal motion associated with comparable product browsing; editorial split panels should remain understandable at rest.

**Unknown:**

- No action or surface transition durations were established; animation timing and easing for the main scenes are unspecified.

### Responsive

**Observed:**

- Commerce CSS includes width breakpoints at 768px and 896px among several narrower device thresholds; report CSS includes thresholds around 810px and 1200px.

**Transfer:**

- On narrow screens, stack the media and copy halves while preserving their contrasting surfaces; keep headline, support and actions together.
- Reduce photographic grid columns without squeezing overlay labels, retaining the 20px content inset when feasible.
- Keep studio stages proportionate and let category controls scroll rather than shrinking their uppercase text excessively.

**Unknown:**

- Exact mobile typography, ordering, navigation transformation and breakpoints for individual components are not established. These stacking rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
