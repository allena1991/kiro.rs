# Drizzle — doodles meet developer proof

## Overview

A bright, matter-of-fact developer style with a mischievous human streak. System sans typography, pencil-like annotations and tiny illustrated characters interrupt an otherwise restrained white-and-gray interface. Real product views and compact technical proof carry more weight than promotional artwork; spacious marketing chapters give way to denser, readable technical explanations.

### Essentials

- The headline gets corrected by a human hand: 40px/1.2 bold system sans with a blue 30px handwritten replacement tilted -4deg above a crossed-out word. Preserve this annotation device with new language.
- The opening is a small workshop, not a billboard: a 910px split composition pairs a compact left promise and 2×2 utility actions with a roughly 480px-wide illustrated scene on the right, surrounded by white space.
- Actions feel like tools: the opening uses pale 191×40px rectangular cells with 4px gaps; deeper conversion buttons are charcoal, 48px tall, with 3–4px corners rather than pills.
- White does almost all the talking: #ffffff canvas, #222222 headlines, pale gray groups and #e8e8e8 edges; blue is reserved for handwritten corrections and links, while other saturated colors stay in logos, proof graphics and product imagery.
- Proof is a working artifact: stage a real interface or compact data panel in a 906–1024px-wide light frame, not a floating device mockup. When no interface exists, use a truthful workflow diagram or annotated output.
- Small handmade illustrations break the technical rhythm: thin black outlines, pale blue-gray fills, dot eyes and stick-like limbs on white. Every landing page needs an equivalent human-scale drawn scene; a simple SVG tool-character vignette is sufficient.
- The close stays human and useful: varied-height, 328px-wide social cards can form a 3-column wall; the final footer is a 210px-tall white directory with a single top hairline, not an oversized final slogan.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Link blue | `#006be6` | `--color-link` | link, text | Inline technical links and mentions. |
| Blue pen | `#3e7ff0` | `--color-pen-blue` | text, accent | Handwritten headline corrections; never a page-wide fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal slate | `#282b3b` | `--color-body` | text, action | Default paragraph text and dark conversion button fill. |
| Black | `#000000` | `--color-black` | text, accent | Utility labels, footer text and illustration outlines. |
| Headline ink | `#222222` | `--color-ink` | text | Default marketing headings and compatibility labels. |
| Support gray | `#333333` | `--color-support` | text | Marketing support lines. |
| Utility gray | `#4b5563` | `--color-utility-text` | text | Navigation labels and interface descriptions. |
| Annotation gray | `#909090` | `--color-muted` | text | Eyebrows, quiet handwritten asides and inactive controls. |
| Tile edge | `#e4e5e6` | `--color-tile-edge` | border | Visible rgba(33,39,46,0.12) edge on white for compatibility tiles and secondary buttons. |
| Card edge | `#e8e8e8` | `--color-card-edge` | border | Social cards, media frames and partner cards. |
| Proof edge | `#ebebeb` | `--color-proof-edge` | border | Outer edge of the comparison panel. |
| Footer rule | `#ececec` | `--color-footer-edge` | border | Top rule of the directory footer. |
| Quiet edge | `#efefef` | `--color-quiet-edge` | border | Announcement strip and explanatory callouts. |
| Utility fill | `#f6f6f7` | `--color-button-pale` | surface, action | Opening action cells and small release controls. |
| Logo band gray | `#f8f8f8` | `--color-logo-bed` | surface | Contained partner-logo band. |
| Proof gray | `#fafafa` | `--color-proof-bed` | surface | Backing for comparison panels and technical code blocks. |
| Tile wash | `#fbfbfc` | `--color-tile-wash` | surface | Visible pale wash made with rgba(241,242,243,0.27) over white on compatibility tiles and secondary actions. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Default canvas, cards and reversed button labels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical and product overview articles | Editorial heading | `#0f172a` | `--color-article-heading` | text | Tightly tracked article headings and product-overview hero. |
| technical and product overview articles | Editorial ink | `#37352f` | `--color-article-ink` | text | Long-form explanations. |
| release progress modules | Release green | `#4bb74b` | `--color-progress` | accent | Small release-progress fill. |

## Typography

- **ui-sans-serif** — Headlines, body, navigation and action labels. Familiar system grotesk with sturdy semibold headings and unpretentious regular body text. OpenType features: "calt", "rlig", "ss01". Font stack: "ui-sans-serif", system-ui, -apple-system, "Segoe UI", Roboto, Arial, sans-serif.
- **FirstTimeWriting** — Corrections and sotto-voce asides. Thin, uneven, narrow handwriting with a casual baseline. If unavailable, use **Patrick Hand**. Use 400; preserve narrow width and slight rotation. Font stack: "FirstTimeWriting", "Patrick Hand", cursive.
- **ui-monospace** — Compact proof labels and numeric results. Small utilitarian monospaced text; numbers stay integrated with the graph rather than becoming huge stats. Font stack: "ui-monospace", SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ui-sans-serif | 700 | 40px | 1.2 | normal | Compact left-aligned landing promise. |
| heading | ui-sans-serif | 600 | 32px | 1.5 | normal | Main marketing chapter headings, centered or left-aligned. |
| product-heading | ui-sans-serif | 600 | 32px | 1.2 | -0.02em | Tighter centered product-demonstration heading. |
| pen-correction | FirstTimeWriting | 600 | 30px | 1.6 | normal | Blue replacement words above a struck word. |
| hand-aside | FirstTimeWriting | 400 | 26px | 1 | normal | Muted handwritten punchline beneath a product heading. |
| support | ui-sans-serif | 500 | 20px | 1.5 | normal | One- or two-line marketing support. |
| body | ui-sans-serif | 400 | 16px | 1.5 | normal | Social proof and prose. |
| button | ui-sans-serif | 700 | 16px | 1 | normal | Dark conversion actions. |
| secondary-button | ui-sans-serif | 600 | 16px | 1 | normal | Secondary actions paired with dark buttons. |
| tile-label | ui-sans-serif | 600 | 16px | 1.5 | normal | Compatibility tile names. |
| eyebrow | ui-sans-serif | 600 | 16px | 1.5 | 0.08em, uppercase | Small product-family label above centered demonstrations. |
| caption | ui-sans-serif | 400 | 14px | 1.5 | normal | Footer links and smaller explanatory text. |
| utility | ui-sans-serif | 600 | 14px | 1.5 | normal | Opening utility actions. |
| metric-label | ui-monospace | 500 | 12px | 1 | normal | Graph labels and metric summaries. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product overview articles | article-display | ui-sans-serif | 700 | 44px | 1.1 | -0.02em | Centered hero above a broad product interface. |
| technical and product overview articles | article-heading | ui-sans-serif | 600 | 24px | 1.5 | -0.015em | Long-form section headings. |
| product overview articles | question | ui-sans-serif | 600 | 20px | 1.5 | -0.015em | Plain FAQ question and small contact heading. |

**Notes:**

- The default marketing scale is modest: the 40px opening is only a little larger than the 32px chapter headings. Do not inflate it into a monumental display.
- Default marketing tracking is normal. Tighten only the dedicated product heading and editorial variants.
- Handwriting is an interruption, not a general font system: blue corrections are heavier, gray asides are thin. Keep the sans heading fully legible underneath.

## Layout

**Density:** Airy between marketing chapters, compact within utility grids and technical prose.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Opening action-grid seams and release-control micro-spacing. |
| 8px | Icon-to-label gaps and chart-card padding. |
| 10px | Compatibility tile grid gaps. |
| 12px | Small stacks and update-column gaps. |
| 16px | Card padding, comparison grid gaps and paired action gaps. |
| 20px | Social-card gaps and internal social-card vertical separation. |
| 24px | Page side padding, demonstration stack gaps and panel-to-action spacing. |
| 32px | Release header to update columns; editorial chapter separation. |
| 40px | Split capability composition gap. |
| 80px | Opening metadata-to-action separation. |
| 144px | Landing hero separation below the 104px navigation assembly. |
| 160px | Typical marketing chapter separation. |
| 200px | Extra separation before split capability chapters. |

### Containers and grids

- **marketing shell**: max width 1024px · side padding 24px. Centered outer shell for product demonstrations and the social wall.
- **chapter container**: max width 910px. Centered opening, release and capability compositions inside the wider shell.
- **compatibility grid**: max width 450px · 2 columns · gap 10px. Two columns of 220px-wide compatibility tiles beside a roughly 420px text-and-drawing column.
- **comparison grid**: max width 872px · 2 columns · gap 16px. Paired metrics arranged in aligned rows inside the proof panel.
- **social masonry**: max width 1024px · 3 columns · gap 20px. Three independent stacks of variable-height 328px social cards.
- **article column** (only for technical and product overview articles): max width 994px. Long-form shell with 48px left and 40px right padding, leaving a 906px content column.

## Corner radius

| Element | Radius |
| --- | --- |
| dark buttons | 4px |
| secondary buttons | 3px |
| proof panel | 8px |
| social cards | 12px |
| navigation capsule | 40px |
| avatars | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| metric card | `0px 0px 0px 1px rgba(0,0,0,0.08), 0px 1px 2px 0px rgba(0,0,0,0.1), 0px 2px 4px 0px rgba(0,0,0,0.075)` | Only compact metric cards and dashboard controls; other cards mostly use borders. |
| navigation edge | `0px 2px 4px 0px rgba(0,0,0,0.02), 0px 1px 0px 0px rgba(0,0,0,0.06)` | Very shallow fixed-navigation separation. |

### Surfaces

#### White canvas · level 0

**Use:** Default page and footer ground.

**CSS:** `background: #ffffff; color: #222222`

**Observed:** Sections generally share one continuous white ground, with no large colored hero field.

**Transfer:** Create hierarchy through spacing and grouped artifacts rather than alternating saturated bands.

#### Proof panel · level 1

**Use:** Contained working comparison dashboard.

**CSS:** `background: #fafafa; border: 1px solid #ebebeb; border-radius: 8px; padding: 16px`

**Observed:** A 906px-wide outer bed holds paired white graph cards.

**Transfer:** Use for live proof, a test result or a measurable product workflow.

#### Logo band · level 1

**Use:** Grouped ecosystem proof.

**CSS:** `background: #f8f8f8; padding: 15px 0px`

**Observed:** A 1024px-wide contained horizontal band uses white logo tiles and subtle white-to-gray edge fades.

**Transfer:** Group related external tools or supporters without turning the entire page into a logo carousel.

#### Fading product frame · level 1

**Use:** Broad light-interface demonstration.

**CSS:** `background: #ffffff; border-top: 1px solid #e8e8e8; border-left: 1px solid #e8e8e8; border-right: 1px solid #e8e8e8; border-radius: 8px 8px 0px 0px; padding: 4px 4px 0px; mask-image: linear-gradient(rgb(0, 0, 0) 55%, rgba(0, 0, 0, 0))`

**Observed:** The upper interface remains crisp while the lower half dissolves into the page; no heavy drop shadow or device hardware.

**Transfer:** Use the fade for a representative overview, not for instructional detail that must be read.

## Components

### Navigation capsule

**Use:** Primary global destinations in the center of a fixed header.

**CSS:** `display: flex; background: #ffffff; border: 1px solid rgba(0,0,0,0.08); border-radius: 40px; padding: 4px 16px; height: 43px; line-height: normal`

**Text style:** `utility` — ui-sans-serif 600 · 14px/1.5

**Observed:** Four short destinations sit together; the logo is separate on the far left and compact repository, notification and theme controls sit on the right. The white header is 64px tall below a 40px announcement strip.

**States:** Declared: hover link color #000000; focus-visible behavior is not specified.

**Transfer:** Keep the capsule compact and center it independently of the logo.

### Announcement strip

**Use:** One understated release or product update.

**CSS:** `background: #ffffff; border-bottom: 1px solid #efefef; height: 40px; padding: 0px 8px; display: flex; align-items: center`

**Text style:** `caption` — ui-sans-serif 400 · 14px/1.5

**Observed:** Single centered muted line above the navigation, much quieter than a promotional banner.

### Opening utility cell

**Use:** Fast entry points beneath the promise.

**CSS:** `background: #f6f6f7; color: #000000; width: 191px; height: 40px; display: flex; align-items: center`

**Text style:** `utility` — ui-sans-serif 600 · 14px/1.5

**Observed:** Small gray pictogram precedes a left-aligned label. Four cells share a 2×2 grid with narrow seams and a softly clipped outer silhouette.

**States:** Declared: hover background-color #eff0f3; focus-visible behavior is not specified.

**Transfer:** Offer the primary path plus a few genuinely useful learning or search paths.

### Dark action

**Use:** Section-level conversion after proof or demonstration.

**CSS:** `background: #282b3b; color: #ffffff; border-radius: 4px; height: 48px; padding: 16px 32px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — ui-sans-serif 700 · 16px/1

**Observed:** Centered label, sometimes followed by a small right arrow. Width follows the label; the broader result action is 280px, while paired demo actions are 212px.

### Secondary action

**Use:** Exploration alongside a dark action and community contributions.

**CSS:** `background: rgba(241,242,243,0.27); border: 1px solid rgba(33,39,46,0.12); border-radius: 3px; color: #282b3b; padding: 10px 20px; width: 212px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `secondary-button` — ui-sans-serif 600 · 16px/1

**Observed:** Light counterpart to the dark demo button; community variants are 46px tall with smaller text.

### Compatibility tile

**Use:** Dense but orderly integrations or supported platforms.

**CSS:** `display: flex; align-items: center; background: rgba(241,242,243,0.27); border: 1.5px solid rgba(33,39,46,0.12); width: 220px; height: 57px; padding-right: 10px`

**Text style:** `tile-label` — ui-sans-serif 600 · 16px/1.5

**Observed:** A logo occupies the left icon zone; the name is vertically centered. Some tiles carry a tiny uppercase relationship label and a heart at the upper right.

**Transfer:** Use real integrations or supported workflows; keep names short enough to remain one line.

### Metric card

**Use:** Compact quantified proof.

**CSS:** `background: #ffffff; border-radius: 4px; padding: 8px; height: 120px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 1px 2px 0px rgba(0,0,0,0.1), 0px 2px 4px 0px rgba(0,0,0,0.075)`

**Text style:** `metric-label` — ui-monospace 500 · 12px/1

**Observed:** Small metric label at top left, optional result at top right, graph underneath. The card measures 428px wide in the paired desktop grid.

**Transfer:** Keep the numbers small and credible; let the shape of the plot make the contrast.

### Social proof card

**Use:** Candid, attributed customer reactions.

**CSS:** `background: #ffffff; border: 1px solid #e8e8e8; border-radius: 12px; padding: 16px; display: flex; flex-direction: column; gap: 20px; width: 328px`

**Text style:** `body` — ui-sans-serif 400 · 16px/1.5

**Observed:** Avatar and bold name above muted handle; informal quote below. Optional attached image fills the inner width. Cards keep natural heights in independent columns rather than equal-height rows.

**Transfer:** Use permissioned real reactions, including playful or nuanced ones.

### Inline link

**Use:** Technical references and mentions embedded in prose.

**CSS:** `color: #006be6`

**Text style:** `body` — ui-sans-serif 400 · 16px/1.5

**Observed:** Links remain ordinary inline text rather than badges or conversion buttons.

### Directory footer

**Use:** Final navigation after the narrative ends.

**CSS:** `border-top: 1px solid #ececec; background: #ffffff; min-height: 210px`

**Text style:** `caption` — ui-sans-serif 400 · 14px/1.5

**Observed:** Brand lockup, one-line tagline and three social icons on the left; three compact destination columns on the right. Column headings are 18px/1.5 semibold. The default extends to the page edges with 24px side padding; article variants remain in the reading column.

**Transfer:** Close with helpful routes and a short product descriptor, not another hero.

## Imagery and graphics

### Handmade workshop scene

**Use:** Signature landing illustration and smaller chapter punctuation.

**Observed:** Pale blue-gray droplet-like characters with thin black contours, dot eyes and long straight legs gather beside a small framed game board. The board has a warm brown edge, pale gray face and monochrome pixel marks. Smaller characters stand alone under capability copy; white remains the backing.

**Transfer:** Draw a new simple character or animated tool object related to the new product. A flat SVG scene with one framed task surface and two or three tiny characters is the minimum; it should look deliberately handmade rather than like stock vector art.

**Build:** Use an SVG about 480px wide: uneven closed paths filled with low-saturation blue-gray, 2px black outlines, two dot eyes and single-line limbs. Put a roughly 315×170px gray work board behind them with a narrow brown double edge. Add a small stack or tool silhouette and a few monochrome marks; preserve ample empty white around the shapes.

### Blue pen correction

**Use:** Signature human intervention in a headline.

**Observed:** A blue zigzag crosses one word; replacement handwriting sits above it at a slight tilt, partly outside the sans line box.

**Transfer:** Correct one complacent or conventional word with a short, energetic alternative. Preserve the tension between neat typesetting and messy editing.

**Build:** Wrap the target word in a relative inline span. Overlay an SVG zigzag with a 3px blue stroke and no fill across the word. Position 30px handwriting above it, center it over the target, and rotate -4deg. Use #3e7ff0 for both; leave room above the line.

### Real product interface

**Use:** Major demonstrations and product-overview chapters.

**Observed:** Broad desktop interfaces show dense tables, sidebars, filters and small controls. Light demonstrations sit close to the white canvas in Fading product frame; embedded or extension demonstrations can show a dark third-party console while the surrounding page remains white.

**Transfer:** Use the actual product at a useful representative state. For a non-interface product, substitute a legible workflow or output artifact at the same broad scale; do not imitate a database UI.

### Technical proof graphics

**Use:** Performance proof and explanatory articles.

**Observed:** Paired plot cards use fine blue-green traces, pale cyan area fills and narrow lavender bars. Explanatory figures use flat boxes, cylinders, elbow connectors and dashed groups; a separate technical diagram uses pale yellow blocks on a nearly white backing. Terminal output appears as an intact dark rectangle within the article.

**Transfer:** Use real metrics and simple labeled schematics. Confine these stronger colors to the proof artifact.

**Build:** Within paired white cards, draw an SVG plot with very faint dashed horizontal guides, a thin blue trace and translucent cyan fill. For throughput use evenly spaced narrow lavender vertical bars. For architecture, connect flat pastel rectangles and a cylinder with thin elbow paths; use dashed outlines to group environments.

### Logo collections

**Use:** Compatibility lists and supporter proof.

**Observed:** Original multicolor logos live in small outlined white tiles; most of the page around them remains neutral. A larger featured partner tile uses extremely faint diagonal rain-like streaks behind a centered mark.

**Transfer:** Keep partner marks intact and subordinate to the typographic narrative. If featuring a relationship, give one tile more width rather than adding a saturated band.

**Build:** For the featured tile backing, place sparse short diagonal 1px strokes in black at very low alpha across a 240×144px white rectangle, behind the centered logo. Keep contrast low enough that the pattern reads only on close inspection.

### Icons

**Observed:** Mostly small monochrome SVGs: utility outlines at 16–18px with 2px round strokes; social and repository marks at 20–24px in solid black. Opening utility cells use soft gray pictograms; colored integration marks retain their own identities.

**Transfer:** Use simple line icons for actions and recognizable filled marks for external destinations. Do not scale utility icons into decorative feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Workshop opening

**Observed:** A fixed 40px announcement strip and 64px white navigation sit above a large white pause. The 910px-wide split hero starts 144px below that header assembly. On the left, the 40px bold promise takes about two fifths of the composition; one word is crossed and corrected in blue handwriting. Tiny backing metadata and two light technical tags follow. After an 80px pause, four Opening utility cells form a 2×2 block. On the right, a roughly 480px illustrated workshop scene aligns with the promise and actions, with a 315×170px board and small foreground characters. All of this fits inside the first 900px; the next chapter's heading, avatar strip and top of the updates also appear near the fold, while the full update columns continue below it. Layers are plain white ground, typeset promise, pen marks, utility cells and the foreground drawing.

**Transfer:** Use a compact benefit claim and correct one word with a human alternative. Recreate the illustration as a simple SVG scene around the new product's task, not a giant dashboard. Product-overview articles instead open with a centered 44px heading, gray handwritten aside, two pale actions and a broad interface. Technical proof pages open with a centered 32px corrected title, two short support lines and the working proof panel.

**Avoid:** Do not center the default landing promise over a full-bleed illustration, enlarge it to 80px, or replace the handmade scene with glossy 3D art.

**Text style:** `display` — ui-sans-serif 700 · 40px/1.2

### Shipping proof

**Observed:** Left-aligned heading and small contributor line sit above overlapping grayscale 40px circular avatars. A compact release-progress control sits to their right, with a thin 10px green bar. Below, 280px-wide update columns have 12px gaps and pale gray backing; 20px white edge fades hint at horizontal continuation.

**Transfer:** Show the people and concrete changes behind the product. Use actual updates and a truthful progress indicator; keep each item short rather than writing full feature essays.

### Quantified proof stage

**Observed:** Centered heading and Support line lead into Proof panel after 24px. Metric cards form two aligned columns and three rows, with small selectors above. A Dark action sits 24px below the panel.

**Transfer:** Compare a small set of meaningful metrics, explain what was measured and route to deeper methodology.

**Text style:** `heading` — ui-sans-serif 600 · 32px/1.5

### Split compatibility chapter

**Observed:** A 910px split composition puts heading and support in a 420px left column, with a small handmade drawing low in that column. A two-column Compatibility tile grid fills the right side. A 40px composition gap and roughly 200px section separation keep dense logo lists from overwhelming the page.

**Transfer:** Use for integrations, operating contexts or supported workflows. Let the small drawing make the utility list feel human.

**Text style:** `heading` — ui-sans-serif 600 · 32px/1.5

### Centered product chapter

**Observed:** An uppercase Eyebrow sits 8px above Product-heading, with a Hand-aside tucked immediately beneath. A horizontal row of labeled tabs follows; the active tab is dark with a thin underline while others are muted. A pale explanatory strip precedes Fading product frame; paired Secondary action and Dark action close the demonstration.

**Transfer:** Use for a related product or substantial capability. Keep the description above the interface short, and use tabs only when each has meaningful content.

**Text style:** `product-heading` — ui-sans-serif 600 · 32px/1.2 · tracking -0.02em

### Supporter and contribution proof

**Observed:** A centered heading and cheeky one-line support precede Logo band: a larger featured relationship on the left and compact logo tiles to the right. A dark action sits underneath. A separate contribution module uses a pricing-shaped heading, conversational reversal, light community actions and small flanking drawings rather than a conventional price-card grid.

**Transfer:** Present real ecosystem support and honest participation options. Adapt the pricing reversal only when the business model makes it true.

**Text style:** `heading` — ui-sans-serif 600 · 32px/1.5

### Candid social wall and directory ending

**Observed:** A centered heading leads to Social proof cards in three independent stacks, 20px apart. Card heights and attached images vary, producing an uneven lower edge. After white breathing room, Directory footer closes the page without a new conversion banner.

**Transfer:** Allow real voices and uneven lengths to carry the close; reduce the number of cards to the available authentic material.

**Text style:** `heading` — ui-sans-serif 600 · 32px/1.5

### Technical narrative and practical ending

**Only for:** technical and product overview articles

**Observed:** A 906px column uses 16px/1.5 paragraphs with 6px vertical padding, 24px section headings and blue inline links. Broad interface images or flat diagrams punctuate the prose. Instructions use numbered lists, inline code chips and pale bordered code blocks. Product overviews close with plain expanded FAQ questions, a short next-steps paragraph and community links; proof articles close with reproduction steps and final code output. Both finish with Directory footer inside the content width.

**Transfer:** Move from explanation to verification and then practical next steps. Keep FAQ answers visible instead of turning the ending into a card grid.

**Text style:** `article-heading` — ui-sans-serif 600 · 24px/1.5 · tracking -0.015em

## Page flow

**Storyline:** Human promise → working proof → capability context → ecosystem credibility → practical participation or next steps → useful directory.

### Broad developer-product landing

1. **Promise** — Compact split hero with pen correction, utility actions and handmade workshop scene.
2. **Delivery proof** — Contributor portraits, release progress and horizontally grouped updates.
3. **Quantified proof** — Paired compact performance plots and deeper-results action.
4. **Capability context** — Split text-and-drawing chapters beside compatibility tiles.
5. **Product demonstration** — Centered product introduction, tabbed description and broad fading interface.
6. **Ecosystem credibility** — Contained supporter logo band and contribution invitation.
7. **Social proof** — Long candid masonry wall.
8. **Directory ending** — Hairline-separated footer with brand descriptor and grouped links.

**Transfer:** Borrow the balance of useful proof and human interruption, not a required count or sequence of chapters.

### Detailed product overview with an editorial argument

1. **Promise** — Centered tight heading, handwritten aside, light actions and wide interface.
2. **Origin and capabilities** — Candid origin story, compact variant table and direct bullet list.
3. **Architecture** — A broad flat family diagram explains relationships.
4. **Capability chapters** — Named versions alternate paragraphs, real interfaces, setup detail and inline references.
5. **Adoption proof** — Small grouped customer tiles and launch links.
6. **Objection handling** — Plain visible FAQ questions and direct prose answers.
7. **Next steps** — Brief future-update note, community links and contained directory footer.

**Transfer:** Use this denser form when the product needs explanation, deployment context or multiple delivery forms.

### Technical proof and reproducibility

1. **Framed claim** — Centered corrected title and disarmingly qualified support.
2. **Working proof** — Interactive paired graph dashboard with playback controls.
3. **Methodology** — Plain prose, actual output and a test-system diagram.
4. **Reproduction** — Numbered setup steps and light code blocks.
5. **Practical ending** — Final output command followed directly by the contained directory footer.

**Transfer:** Expose how the claim can be checked rather than adding a sales CTA after every paragraph.

## Writing

Technically confident, conversational and occasionally self-mocking. The product feels made by people who use it daily and can admit constraints without retreating into corporate language.

**Do not copy:** Do not reuse the brand name, mascot shapes, partner marks, customer quotes, adoption numbers, benchmark claims or product-specific promises. Replace all with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the makers and you for the reader. Name the product when describing concrete behavior; use direct second-person imperatives for setup and actions.
- **Rhythm:** Short functional headlines, usually 2–8 words, followed by one or two support lines. Longer editorial paragraphs use conversational turns, em dashes and specific technical nouns; brief jokes interrupt rather than replace the explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | A compact claim interrupted by a handwritten correction. | 4–8 words plus a short correction | “ORM for you to settle”<br>“ship ship ship” |
| Chapter heading | Plain capability statement or intentionally understated maker claim. | 2–6 words | “We ship decently fast”<br>“Connect to any database” |
| Support | Explain usefulness directly; allow a small disarming qualifier. | One or two short sentences | “Take them with a grain of salt, ofc”<br>“We support every major serverful and serverless runtime” |
| Action | Clear verb plus destination, task or person. | 2–5 words | “Go to benchmark results”<br>“Talk to product manager” |
| Aside | A personal reaction in a quieter handwritten voice. | 3–6 words | “Can't believe this either.” |
| Objection handling | Ask the actual practical question and answer it without a long preamble. | Short question, then one or two direct paragraphs | “Does Studio send my data anywhere?” |

**Words and phrasing to use:** ship; build; browse; run; your; under the hood; free when true; plain technical nouns; occasional conversational shorthand

**Avoid:** revolutionary; unlock your potential; seamless digital transformation; enterprise-grade as empty praise; unqualified fastest claims

**Rules:**

- Pair every technical claim with an artifact, mechanism or reproducible explanation.
- Let jokes be brief and slightly self-deprecating; do not make every section a punchline.
- Prefer direct answers to objection-handling slogans.
- Keep action labels descriptive enough to predict the destination.

## Do's and Don'ts

### Do

- Keep the landing display at 40px/1.2 and chapter headings at 32px/1.5.
- Use blue handwriting to edit a single part of the promise.
- Preserve 160–200px pauses between broad marketing chapters.
- Keep compact utility cells at 40px high and deep conversion actions at 48px.
- Use 16px inner padding and 12px corners for natural-height social cards.
- Place 12px monospace metric labels above plots rather than oversized stat numerals.
- Keep product imagery at a broad 906–1024px scale with restrained framing.
- End with a 210px directory footer and a 1px top rule.

### Don't

- Do not turn every button into a 40px-radius capsule; that silhouette belongs to grouped navigation.
- Do not spread blue across hero backgrounds or large section fills.
- Do not give every card a deep shadow; social cards use a simple #e8e8e8 border.
- Do not replace candid variable-height social cards with uniform polished quote tiles.
- Do not substitute glossy floating devices for broad real product artifacts.
- Do not turn the compact proof-label system into giant bold KPI typography.
- Do not apply tight negative tracking to the ordinary 40px marketing headline.
- Do not make editorial paragraphs 20px; reserve that size for marketing support lines.

## Motion and responsive

### Motion

**Observed:**

- Utility action backgrounds declare 0.2s ease-in-out transitions; navigation links declare 0.2s transitions.
- Compatibility and article partner controls include declared 0.2s border/background transitions; some product tabs change color over 0.2s ease-in-out.
- The technical proof panel exposes pause and playback-speed controls.

**Transfer:**

- Use motion as a utility response or live-proof behavior. Preserve the pen-mark illustration's handmade character without adding cinematic hero choreography.

**Unknown:**

- Exact animation behavior and timing of canvas scenes and plot playback are not established.
- No specific entrance-animation sequence is established.

### Responsive

**Observed:**

- Desktop compositions are centered inside 910px and 1024px marketing widths.
- Declared stylesheet breakpoints cluster around 600px, 768px, 836px and 1024px; additional landing-specific thresholds exist.

**Transfer:**

- On narrow screens, stack the promise and workshop scene while keeping the corrected word and its annotation together.
- Allow dense proof artifacts and compatibility groups their own deliberate overflow or stacked treatment; retain small labels rather than shrinking the entire page.

**Unknown:**

- Exact mobile layout, navigation collapse and breakpoints for each component are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
