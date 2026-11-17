# Amrit Palace — candlelit editorial ceremony

## Overview

A hospitable, cinematic style pairing fine editorial serifs with small, matter-of-fact sans-serif text. Warm cream and ochre interrupt deep charcoal and richly lit photography, giving the experience the feeling of a printed invitation brought into motion. It suits crafted products, premium services and experiential brands, with sparse storytelling frames alternating with compact ruled information.

### Essentials

- A headline reads like an invitation set across a room: uppercase TT Ramillas Variable at 115.2px, weight 300, line height 0.8 and -0.04em tracking, with tiny labels flanking the lower line.
- The opening is an inhabited scene, not a product card: a 1440px-wide, 900px-tall photograph with a dark top-to-bottom overlay, centered cream headline, bottom-left support and bottom-right proof.
- Actions look framed rather than inflated: rectangular dark or cream fills, 2px corners and a fine offset outline; navigation instead pairs 11.5px labels with 40px ochre icon squares.
- Color behaves like printed stock: cream #d8cbb8 and charcoal dominate, with #d49653 concentrated in one substantial editorial panel, compact icon blocks, stars and the closing word sculpture rather than repeated colorful cards.
- Imagery earns whole chapters: edge-to-edge atmospheric scenes alternate with 45:55 text-and-photo splits and three tall 452px-wide images; use warm directional light and tactile close-ups, or photograph tools and materials if the product has no natural setting.
- Proof and farewell have deliberately different voices: 418px by 446px ruled serif quote cards travel horizontally, while a 198.7px ochre sans-serif brand line spans the dark ending. Preserve both the moving proof strip and monumental typographic sign-off for new content.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm cream | `#d8cbb8` | `--color-canvas` | background, text, surface | Primary light canvas and reverse text on dark scenes. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ochre | `#d49653` | `--color-accent` | surface, accent, link, action | Feature-list stock, compact icon squares, stars, link hover and monumental closing type. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Muted taupe | `#bfb4a3` | `--color-stone` | background | A tonal change behind an editorial image triptych. |
| Soft stock rule | `#beb3a3` | `--color-soft-rule` | border | Visible result of charcoal at 15% over cream; subordinate review separators. |
| Cream-stock rule | `#b6ab9c` | `--color-rule` | border | Visible result of charcoal at 20% over cream; main panel and table separators use rgba(44,44,44,0.2). |
| Reverse rule | `#686055` | `--color-reverse-rule` | border | Cream at 35% over the brown-black footer; use rgba(216,203,184,0.35) so it also adapts to the charcoal inquiry canvas. |
| Charcoal | `#2c2c2c` | `--color-ink` | text, background, action | Primary text, dark framed actions and charcoal backing panels; also the full canvas for inquiry pages. |
| Brown black | `#292622` | `--color-footer` | background | Shared closing information and wordmark canvas. |
| Near-black veil | `#101010` | `--color-veil` | background | Top of the opening image overlay, fading to the same hue at 20% opacity. |

## Typography

- **TT Ramillas Variable** — Editorial headlines, category titles, quotes and selected contact text. Delicate high-contrast serif with sculptural capitals and very tight display spacing. If unavailable, use **Bodoni Moda**. Use weight 300 where available and preserve compact line height and tight capitals. Font stack: "TT Ramillas Variable", "Bodoni Moda", Georgia, serif.
- **Satoshi** — Small body copy, navigation, metadata, prices, rating numerals and the giant closing line. Clean contemporary sans-serif, predominantly medium weight; noticeably plain beside the elegant serif. If unavailable, use **DM Sans**. Use 500 for text and 700 for catalog names and prices. Font stack: "Satoshi", "DM Sans", Arial, sans-serif.
- **Bad Script** (only for founder or personal-story quotations) — A handwritten personal statement beside an environmental photograph. Narrow, sloping handwriting with an informal human cadence. Font stack: "Bad Script", cursive.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-wordmark | Satoshi | 500 | 198.7px | 0.8 | -0.016em, uppercase | Near-full-width brand sign-off in ochre. |
| display | TT Ramillas Variable | 300 | 115.2px | 0.8 | -0.04em, uppercase | Default cinematic opening, centered on two tightly stacked lines. |
| heading | TT Ramillas Variable | 300 | 69.1px | 0.9 | -0.04em, uppercase | Major light-canvas headings, proof titles and object-stage statements. |
| chapter-heading | TT Ramillas Variable | 300 | 69.1px | 0.8 | -0.04em, uppercase | A tightly stacked centered heading with tiny flank captions; also Roman-numeral story chapters. |
| scene-heading | TT Ramillas Variable | 300 | 64.8px | 0.85 | -0.04em, uppercase | Top-left titles over full-bleed atmospheric media. |
| split-heading | TT Ramillas Variable | 300 | 50.4px | 0.9 | -0.03em, uppercase | Compact two-line editorial headings in split panels. |
| rating | Satoshi | 500 | 41.8px | 1 | -0.04em | Prominent numeric score inside the compact proof card. |
| quote | TT Ramillas Variable | 300 | 25.9px | 1.2 | -0.0056em | Customer quotations in tall ruled cards. |
| body | Satoshi | 500 | 13px | 1.4 | -0.011em | Default short supporting paragraphs. |
| action-caption | Satoshi | 500 | 13px | 1 | -0.011em | Framed action labels and compact metadata. |
| footer-copy | Satoshi | 500 | 13px | 1.4 | normal | Centered operational information and grouped footer links. |
| eyebrow | Satoshi | 500 | 13px | 1 | -0.011em, uppercase | Small operational labels and information headings. |
| navigation | Satoshi | 500 | 11.5px | 1 | -0.012em | Desktop navigation and its dropdown labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| single-offer product storytelling | offer-display | TT Ramillas Variable | 300 | 144px | 0.8 | -0.04em, uppercase | Oversized left-aligned statement interacting with a floating product object. |
| story and single-offer pages | light-opening | TT Ramillas Variable | 300 | 95px | 0.8 | -0.04em, uppercase | Centered title on cream with an isolated object or small image beneath. |
| inquiry pages | inquiry-opening | TT Ramillas Variable | 300 | 76.3px | 0.9 | -0.04em, uppercase | Centered reverse headline above the map-and-form grid. |
| catalog pages | catalog-heading | TT Ramillas Variable | 300 | 54.7px | 1 | -0.05em | Title-case category headings beside dense item grids. |
| founder or personal-story quotations | personal-quote | Bad Script | 500 | 44.6px | 1.1 | -0.0032em | Handwritten statement with centered attribution. |
| purchase instructions | step-title | TT Ramillas Variable | 200 | 36px | 1 | -0.03em, uppercase | Lightweight process headings in horizontal ruled rows. |
| offer-selection rows | offer-title | TT Ramillas Variable | 300 | 31px | 1 | -0.04em | Offer name beside a right-aligned price. |
| inquiry pages | inquiry-support | TT Ramillas Variable | 300 | 26.6px | 1.2 | -0.03em | Warm serif introduction over a restrained form. |
| story principle cards | principle-title | TT Ramillas Variable | 300 | 24.5px | 1 | -0.006em | Title under a small numbered header, with explanation pinned to the card bottom. |
| catalog pages | catalog-item | Satoshi | 700 | 13px | 1 | -0.011em | Names and right-aligned prices. |
| catalog pages | catalog-description | Satoshi | 500 | 13px | 1.5 | -0.011em | Descriptions below item names; softer than the title. |
| catalog pages | catalog-tab | TT Ramillas Variable | 300 | 13px | 1 | -0.011em | Tiny category links in the bottom floating ochre strip. |

**Notes:**

- Capitals carry the main editorial voice; ordinary paragraphs remain sans-serif and sentence case. Catalog headings are a deliberate title-case exception.
- At display scale keep the serif light and closely fitted, generally -0.04em with line heights below 1. Do not carry this compression into quotations or body copy.
- Tiny flank labels provide a horizontal counterweight to centered, tightly stacked titles. The closing brand line switches to sans-serif rather than repeating the hero face.

## Layout

**Density:** Airy narrative stages with compact information inside them: broad empty fields separate headlines, objects and prose, while lists and proof cards remain closely ruled.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Dropdown icon and compact metadata gaps. |
| 12px | Heading-to-support gaps, card header padding and small row spacing. |
| 16px | Grid gutters and operational panel inner padding. |
| 20px | List-row and testimonial text inset. |
| 24px | Inset panel top and bottom breathing room. |
| 28px | Default desktop page side gutter. |
| 42px | Media-stage vertical insets and larger internal separations. |
| 92px | Major light-section top and bottom breathing room. |
| 232px | Ceremonial gap above the giant closing brand line. |

### Containers and grids

- **edge-to-edge stage**: side padding 28px. Full-width composition rather than a centered max-width shell; media reaches both browser edges, text uses side gutters.
- **editorial split**: 2 columns · gap 0px. A 648px left panel and 792px right panel at desktop form a 45:55 split. Long list stock sits left; story and photograph sit right.
- **image triptych**: 3 columns · gap 14px · side padding 28px. Three 452px-wide, 504px-tall photographs with short centered captions.
- **catalog matrix**: 2 columns · gap 0px. A 576px category column beside an 864px item area divided into two 432px columns; continuous rules connect cells.
- **inquiry grid** (only for inquiry pages): 2 columns · gap 0px. Equal 720px halves, map and direct contacts left, form right; each half uses 28px side padding.
- **form fields** (only for inquiry pages): 2 columns · gap 16px. Two field columns with 42px row gaps; subject and message span both columns.

## Corner radius

| Element | Radius |
| --- | --- |
| framed actions and small proof | 2px |
| testimonial cards and icon squares | 3px |
| ochre feature panel | 4px |

## Surfaces and depth

### Surfaces

#### Cream stock · level 0

**Use:** Default light content canvas.

**CSS:** `background: #d8cbb8; color: #2c2c2c`

**Observed:** Flat warm stock without a white card layer.

**Transfer:** Let type, rules and photography do the organizing.

#### Charcoal backing · level 0

**Use:** Backing for the ochre feature panel and dark inquiry content.

**CSS:** `background: #2c2c2c; color: #d8cbb8`

#### Ochre stock · level 1

**Use:** One substantial, printed-list feature accent.

**CSS:** `background: #d49653; color: #2c2c2c; border-radius: 4px`

**Observed:** The warm accent is nested within charcoal rather than spread over the entire page.

**Transfer:** Use for a curated specification, offering list or proof ledger.

#### Taupe editorial band · level 0

**Use:** Tonal backdrop for a three-image chapter.

**CSS:** `background: #bfb4a3; color: #2c2c2c`

#### Opening veil · level 1

**Use:** Protect the cream title over cinematic photography.

**CSS:** `background-image: linear-gradient(rgb(16, 16, 16), rgba(16, 16, 16, 0.2))`

**Observed:** The top is nearly black while warm table details remain visible lower down.

**Transfer:** Layer above a full-bleed image and below all text.

#### Atmospheric scene veil · level 1

**Use:** Sustain reverse text over full-width media chapters.

**CSS:** `background: rgba(0, 0, 0, 0.3)`

**Observed:** A stronger black veil at 55% is used over the opening video chapter.

#### Ruled stock · level 1

**Use:** Quiet proof cards and information containers.

**CSS:** `border: 1px solid rgba(44, 44, 44, 0.2); border-radius: 3px; box-shadow: none`

**Observed:** Interior rules repeat the outer edge color; fill stays continuous with the page.

#### Closing canvas · level 0

**Use:** Shared information footer and monumental brand sign-off.

**CSS:** `background: #292622; color: #d8cbb8`

## Components

### Cinematic navigation

**Use:** Persistent top-level wayfinding and two conversion routes.

**CSS:** `position: fixed; height: 76px; background: rgba(44, 44, 44, 0.353); backdrop-filter: blur(6.2px); z-index: 99`

**Text style:** `navigation` — Satoshi 500 · 11.5px/1 · tracking -0.012em

**Observed:** Small emblem at left; primary links beside it; utility actions pushed to the right. Cream text on imagery is the default; light-canvas variants use charcoal text and an unobtrusive backing.

**Transfer:** Keep the emblem compact and allow long quiet space between navigation groups.

### Navigation link

**Use:** Small direct links and dropdown triggers.

**CSS:** `color: #d8cbb8; transition: 0.4s`

**Text style:** `navigation` — Satoshi 500 · 11.5px/1 · tracking -0.012em

**Observed:** Dropdown labels add a small chevron; a trigger has 20px vertical padding and a 6px label-to-chevron gap. Light-canvas links reverse to charcoal.

**States:** Declared: hover color #d49653; active outline 0px.

### Icon action square

**Use:** Make key navigation actions tangible without large filled buttons.

**CSS:** `width: 40px; height: 40px; padding: 10px; background: #d49653; border-radius: 3px; overflow: hidden`

**Observed:** A 20px charcoal pictogram occupies the square; the text label sits outside it with a 12px gap.

**Transfer:** Choose one direct product-related symbol for each action rather than enclosing every link in a square.

### Framed action

**Use:** Primary in-section conversion.

**CSS:** `background: #2c2c2c; color: #d8cbb8; border-radius: 2px; outline: 1px solid #2c2c2c; outline-offset: 4px; padding: 12px`

**Text style:** `action-caption` — Satoshi 500 · 13px/1 · tracking -0.011em

**Observed:** A thin separated outer frame makes a double-edge effect around a plain rectangular fill. Reverse cream treatment sits on dark media; the inquiry submit variant is 54px tall and spans the form.

**Transfer:** Give the label comfortable horizontal room while keeping the frame close and corners almost square.

### Ochre feature ledger

**Use:** An editorial list made into a large colored object.

**CSS:** `background: #d49653; color: #2c2c2c; border-radius: 4px; padding-bottom: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `split-heading` — TT Ramillas Variable 300 · 50.4px/0.9 · tracking -0.03em · uppercase

**Observed:** The headline and a small pictogram share the top. Full-width ruled rows pair names and right-aligned prices with small descriptions beneath. A framed action anchors the bottom.

**Transfer:** Adapt the ledger to key services, configurations or selected specifications.

### Testimonial card

**Use:** Moving customer proof strip.

**CSS:** `width: 418px; height: 446px; border: 1px solid rgba(44, 44, 44, 0.2); border-radius: 3px; display: flex; flex-direction: column; justify-content: space-between; padding-bottom: 20px; overflow: hidden`

**Text style:** `quote` — TT Ramillas Variable 300 · 25.9px/1.2 · tracking -0.0056em

**Observed:** A shallow ruled header pairs ochre stars with the platform label; quote is inset 20px; author sits at the bottom, leaving a deliberately open middle. Cards continue past both screen edges.

**Transfer:** Use attributable customer statements and preserve the editorial emptiness rather than adding avatars or badges to fill it.

### Rating plaque

**Use:** Compact numeric proof in the hero and beside the proof heading.

**CSS:** `background: #d8cbb8; color: #2c2c2c; border: 1px solid rgba(44, 44, 44, 0.2); border-radius: 2px; overflow: hidden`

**Text style:** `rating` — Satoshi 500 · 41.8px/1 · tracking -0.04em

**Observed:** The 331px by 136px plaque has stars and a source symbol above a divider; an oversized score and tiny denominator sit opposite a concise qualitative label and review count.

**Transfer:** Use a verified score or equivalent concise proof metric; keep the supporting explanation tiny.

### Operational footer cell

**Use:** Structured practical information within the closing canvas.

**CSS:** `border-right: 1px solid rgba(216, 203, 184, 0.35); padding: 16px; display: flex; flex-direction: column; justify-content: space-between; align-items: center`

**Text style:** `footer-copy` — Satoshi 500 · 13px/1.4

**Observed:** Uppercase labels sit above centered compact details. Address and schedule cells share top and bottom rules; contact links are underlined. The upper footer groups two wide information zones around a compact emblem.

**Transfer:** Use availability, service regions, contact details or support hours relevant to the new product.

### Catalog item grid

**Only for:** catalog pages

**Use:** Dense browsable offerings without detached cards.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; border-top: 1px solid rgba(44, 44, 44, 0.2); border-bottom: 1px solid rgba(44, 44, 44, 0.2)`

**Text style:** `catalog-item` — Satoshi 700 · 13px/1 · tracking -0.011em

**Observed:** Each cell pairs bold name and price, then a softer description after 12px. Cell padding is 20px; shared vertical and horizontal rules connect the whole area. Category headings remain in a separate left column.

**Transfer:** Apply to a product catalog or detailed service matrix.

### Inquiry field

**Only for:** inquiry pages

**Use:** Understated form controls on charcoal.

**CSS:** `background: transparent; color: #d8cbb8; border: 0px; border-bottom: 1px solid rgba(216, 203, 184, 0.35); padding: 6px 16px 6px 0px; height: 42px; transition: 0.4s`

**Observed:** Fields are visually lines, not boxes. Two columns handle short values; the message spans the form and is 212px tall.

### Numbered principle card

**Only for:** story principle cards

**Use:** A centered, scroll-led sequence of values or methods.

**CSS:** `background: #d8cbb8; border: 1px solid rgba(44, 44, 44, 0.2); border-radius: 2px; width: 317px; height: 403px; position: sticky; overflow: hidden`

**Text style:** `principle-title` — TT Ramillas Variable 300 · 24.5px/1 · tracking -0.006em

**Observed:** Number in a ruled top band, serif title just below, short sans-serif explanation pinned low. Multiple cards share a centered vertical stack rather than a four-column feature grid.

**Transfer:** Keep one principle in focus at a time.

## Imagery and graphics

### Candlelit environment

**Use:** Default opening and full-width experiential chapters.

**Observed:** An intimate dining room photographed along a long table, with symmetrical chairs and warm reflective glass; later scenes show brick, patterned walls and red upholstery. Deep brown shadows, amber practical lights and selective highlights dominate. The image is the entire stage rather than a thumbnail behind text.

**Transfer:** Photograph the product's real environment with depth, warm practical light and an inviting human-scale viewpoint. Without a venue, use a closely lit workbench or materials scene; preserve atmospheric depth rather than substituting a flat interface mockup.

### Tactile process and close-ups

**Use:** Split editorial stories and three-image chapters.

**Observed:** Close views of colorful plated food in metal bowls, hands finishing a bright drink, cooking flames and frying bread. Images are tall or near-square and tightly framed; rich natural color remains inside the photograph, not in the surrounding interface.

**Transfer:** Show material, making and finished detail in warm directional light. Use tools, hands and surfaces to make an abstract product feel concrete.

### Floating stock object

**Use:** A tangible object interlude on the light marketing canvas.

**Observed:** Several notched paper cards fan and overlap in cream, charcoal, muted green and ochre, with soft directional shadows. The compact object occupies the lower center of a broad empty field beneath a centered serif statement.

**Transfer:** Use packaging, sample cards, documents or small product objects with tactile edges. Minimum equivalent is a photographed overlapping stack on cream, lit from one side; avoid turning it into glossy dashboard panels.

**Build:** Create 4–5 thin rectangular SVG or CSS planes, about 300px by 200px, with small semicircular side notches via an SVG mask. Overlap around a common lower-center pivot, rotate each between -20deg and 35deg, use cream, charcoal and muted ochre fills, add thin lighter edge strokes and soft black shadows at low opacity. Place the group in a 600px-wide field with ample clearance beneath the title; a real photographed stack is preferable.

### Radial object sculpture

**Only for:** single-offer product storytelling

**Use:** A full-width moving product interlude.

**Observed:** Dozens of thin matte notched cards form a spherical spiral or rosette, in alternating cream, dark green, black and tan, against a warm brown studio field. Soft edge highlights give the paper depth without glossy reflections.

**Transfer:** Repeat one simple product-relevant physical form into a sculptural arrangement. A still studio render is a sufficient minimum when motion is unavailable.

**Build:** In a 3D scene, duplicate a thin rectangular plane with thickness and two side notches around a circular path; increment rotation and elevation to form a dense curved fan. Alternate restrained paper-like materials and illuminate with one broad upper-left area light. Frame the sculpture centrally at roughly three quarters of the scene height.

### Textured chapter field

**Only for:** long-form story chapters

**Use:** A contemplative numbered statement between photography and prose.

**Observed:** A muted olive-brown paper-like field has fine speckles, subtle mottling and low-contrast wear. A Roman numeral sits high, the cream statement is centered and the support copy sits low.

**Transfer:** Use a restrained scanned-paper texture or procedural grain, not an ornamental pattern.

**Build:** Layer a low-opacity monochrome SVG turbulence texture over a muted warm dark field, with a second very broad low-contrast noise layer for mottling. Keep flecks tiny, sparse and darker than the field; use no obvious repeating tile or bright gradient. Maintain generous clear space around centered cream type.

### Icons

**Observed:** Small literal charcoal pictograms, including crossed utensils, a serving cover, envelope and phone, sit inside ochre squares. Chevrons are tiny and plain; rating stars use ochre. There is no decorative multi-color icon grid.

**Transfer:** Choose simple compact silhouette or line pictograms readable at 20px. Reserve them for navigation actions, contact routes and proof.

## Section recipes

How recurring sections are built.

### First screen: Cinematic invitation opening

**Observed:** A 900px-tall edge-to-edge environmental photograph fills the first screen. Layers run from the image through Opening veil to cream type and Cinematic navigation. The main two-line display is centered in the upper-middle, visually spanning about two fifths of the width; small uppercase labels flank the lower line. A short support paragraph anchors the lower-left 28px gutter and a Rating plaque anchors the lower right. Header links and ochre Icon action squares are visible above; there is no separate central hero button. Within the first 900px the entire headline, support, proof and room scene are visible; the next full-screen video story begins below.

**Transfer:** Replace the room with an equally deep, warm product environment or material-making scene. Preserve the opposing lower-corner support and proof anchors. Story and single-offer pages can instead use light-opening on cream with a small isolated image or floating object; inquiry pages open with inquiry-opening over charcoal and bring practical controls into the first screen.

**Avoid:** Do not replace this with a generic centered headline, pill CTA and floating browser window on a blank gradient. Do not hide the atmospheric image behind an opaque card.

**Text style:** `display` — TT Ramillas Variable 300 · 115.2px/0.8 · tracking -0.04em · uppercase

### Full-bleed story scene

**Observed:** A 900px media chapter carries scene-heading at the upper left with 28px horizontal and 42px vertical insets, short support and a Framed action. Atmospheric scene veil protects the cream text. Later media chapters extend to 1215px, with heading high and supporting prose low.

**Transfer:** Use an immersive demonstration, real process or environmental story, with only one primary idea per scene.

**Text style:** `scene-heading` — TT Ramillas Variable 300 · 64.8px/0.85 · tracking -0.04em · uppercase

### Ledger and editorial split

**Observed:** A 45:55 composition places Ochre feature ledger on Charcoal backing with 24px vertical and 28px side insets. Across the seam, split-heading and small prose sit high on Cream stock, a Framed action follows, and a large tightly framed photograph anchors the lower right.

**Transfer:** Pair a concise curated offering list with one explanatory story and tangible product photography.

**Text style:** `split-heading` — TT Ramillas Variable 300 · 50.4px/0.9 · tracking -0.03em · uppercase

### Centered captioned triptych

**Observed:** Taupe editorial band uses 92px top and bottom breathing room, a centered chapter-heading with tiny flank captions and a short centered paragraph 12px below. Three tall photographs follow after a broad gap; each ends with a modest serif title and small centered description.

**Transfer:** Show three aspects of an experience, craft or workflow without turning the section into feature-icon cards.

**Text style:** `chapter-heading` — TT Ramillas Variable 300 · 69.1px/0.8 · tracking -0.04em · uppercase

### Object statement stage

**Observed:** A centered heading on Cream stock sits above an isolated floating stack with extensive negative space. The stage is much taller than the text, allowing the tangible object to become the main visual event.

**Transfer:** Stage one material product equivalent beneath a succinct benefit statement; support and action should remain subordinate to the sculptural object.

**Text style:** `heading` — TT Ramillas Variable 300 · 69.1px/0.9 · tracking -0.04em · uppercase

### Proof marquee

**Observed:** A light section uses 92px vertical breathing room. A two-line heading sits left and Rating plaque right. Testimonial cards move through an edge-clipped horizontal strip below; the short centered invitation and underlined review link close the section.

**Transfer:** Include a horizontal proof strip using actual attributed quotes or similarly concise verified observations. Preserve the serif quote scale and open card interiors.

**Text style:** `heading` — TT Ramillas Variable 300 · 69.1px/0.9 · tracking -0.04em · uppercase

### Monumental practical ending

**Observed:** Closing canvas spans about 1072px in height. Ruled operational information and a compact emblem occupy the top, followed by four small centered link groups. A 232px pause separates links from the near-full-width ochre closing-wordmark. Tiny legal and credit text align left, center and right along the bottom with 20px bottom space.

**Transfer:** End with useful product-specific contact or access information, compact navigation and a typographic brand line sized to fill the width. The giant line is an essential closing device, not a second promotional paragraph.

**Text style:** `closing-wordmark` — Satoshi 500 · 198.7px/0.8 · tracking -0.016em · uppercase

### Roman-numeral story chapters

**Only for:** long-form story pages

**Observed:** An opening on cream is followed by sparse narrative layouts, a numbered textured statement, a personal script quote beside a large environmental photograph, and centered sticky Numbered principle cards. Roman numerals give chapters a book-like cadence.

**Transfer:** Use for origin, philosophy or craft stories; choose relevant chapters rather than reproducing the subject matter.

**Text style:** `chapter-heading` — TT Ramillas Variable 300 · 69.1px/0.8 · tracking -0.04em · uppercase

### Offer selection and process

**Only for:** single-offer commerce pages

**Observed:** A cream opening isolates one floating stock object and small selectable variants. An oversized statement and radial object scene give way to 541px-tall split rows: object image left, offer name and price top right, support below and Framed action low. Numbered instructions use 32px vertical padding and continuous rules.

**Transfer:** Use the sculptural introduction to establish desirability, then make variants and purchase steps concrete.

**Text style:** `offer-title` — TT Ramillas Variable 300 · 31px/1 · tracking -0.04em

### Ruled catalog chapter

**Only for:** catalog pages

**Observed:** A title-case category heading and support sit in the left 40% of the width while Catalog item grid fills the right 60%. Shared hairlines, not rounded cards, organize the two item columns. An ochre category strip floats near the bottom. A centered course-builder panel and timed availability feature precede ordinary categories.

**Transfer:** Use for large assortments or a detailed service catalog; keep category prose distinct from the dense comparison grid.

**Text style:** `catalog-heading` — TT Ramillas Variable 300 · 54.7px/1 · tracking -0.05em

### Dark inquiry workspace

**Only for:** inquiry pages

**Observed:** Centered inquiry-opening appears after 172.8px of top space, then equal-width ruled columns pair direct contacts and a dark monochrome map with an inquiry-support introduction and Inquiry fields. Ochre contact icons punctuate the top row. A full-width atmospheric image precedes the shared ending.

**Transfer:** Bring contact routes and the task into view quickly, keep the form linear and use a dark contextual location or service-area visual.

**Text style:** `inquiry-opening` — TT Ramillas Variable 300 · 76.3px/0.9 · tracking -0.04em · uppercase

## Page flow

**Storyline:** Atmospheric promise → tangible experience or offering → editorial detail → human proof → practical information and monumental sign-off.

### Experiential marketing landing page

1. **Promise** — Cinematic invitation with corner support and proof.
2. **Experience** — Full-screen video story with a small action.
3. **Offering detail** — Ochre ledger beside editorial copy and close-up imagery.
4. **Capability chapters** — Captioned triptych, process photography and floating-object stage.
5. **Credibility** — Environmental chapter and moving customer quotations.
6. **Practical ending** — Operational information, grouped links and giant ochre brand line.

**Transfer:** Alternate spacious emotional scenes with compact concrete information rather than repeating a uniform card section.

### Origin and philosophy narrative

1. **Introduction** — Centered title and small image on cream.
2. **Origin** — Roman-numeral chapter with offset prose and environmental photograph.
3. **Point of view** — Textured statement and handwritten personal quote.
4. **Principles** — Centered sticky numbered cards.
5. **Human proof** — Atmospheric process scene and testimonial marquee.
6. **Practical ending** — Shared ruled footer and monumental brand line.

**Transfer:** Give a history or craft narrative book-like chapters, preserving sparse layouts and a human statement.

### Direct inquiry and practical access

1. **Invitation** — Short centered reverse title.
2. **Task completion** — Direct contact routes, dark map and two-column line-only form.
3. **Atmosphere** — Wide product-environment photograph.
4. **Practical ending** — Shared operational footer and oversized ochre type.

**Transfer:** Shorten the emotional preamble when visitors have a task; keep the shared visual sign-off.

### Single-offer commerce story

1. **Product introduction** — Centered title, floating object, small variant choices and framed action.
2. **Desirability** — Oversized benefit statement and sculptural repeated-object video.
3. **Selection** — Ruled split rows pairing object, offer, price and action.
4. **Objection handling** — Numbered delivery and usage instructions.
5. **Trust** — Environmental chapter and moving quote cards.
6. **Practical ending** — Shared information and monumental brand sign-off.

**Transfer:** Make a simple purchase feel tactile, then explain variants and fulfillment clearly.

### Browsable detailed catalog

1. **Orientation** — Centered cream title with flank labels, handwritten support and full-width photograph.
2. **Guided selection** — Centered course-builder panel and an availability-led feature.
3. **Detailed offering** — Category columns beside continuous two-column ruled item grids; bottom category navigation.
4. **Practical ending** — The same ruled information footer and enormous ochre brand line, without a testimonial section.

**Transfer:** Let density rise inside a stable category structure; retain the photographic introduction and brand-scale ending.

## Writing

Warm, composed and sensory, with the confidence of an established host. Evocative headlines give way to practical, reassuring details rather than hype.

**Do not copy:** Do not reuse the brand name, emblem, card artwork, restaurant photography, founding date, locations, menu items, prices, ratings, review counts, customer quotations or personal attributions as the new product's assets or claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we and our for the maker or team and you or your when welcoming or guiding the reader. Direct instructions are gentle but concrete.
- **Rhythm:** Headlines favor two to seven words, often split into two balanced lines. Supporting copy expands into one short paragraph; actions remain literal and brief. Longer narrative paragraphs use paired contrasts and occasional em dashes.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Sensory noun followed by a lingering emotional result. | 3–6 words | “Flavors That Stay” |
| Editorial heading | Two balanced fragments that connect contemporary experience to enduring craft. | 4–8 words | “Signature Dishes. Classic Roots.”<br>“Where Tradition Meets Modern Comfort” |
| Supporting line | From one tangible quality to another, ending in a warm emotional promise. | 12–24 words | “From warm hospitality to bold flavors, every detail tells a story.” |
| Action | Plain verb and concrete object or immediate outcome. | 2–4 words | “Reserve a Table”<br>“Order Now”<br>“View Full Menu” |
| Process instruction | Direct verb phrase naming one decision at a time. | 2–4 words | “Choose your amount”<br>“Select delivery” |
| Personal statement | Contrast the thing provided with how the recipient feels. | 10–18 words | “Hospitality is not just what we serve, it’s how we make you feel.” |

**Words and phrasing to use:** crafted; warmth; care; rooted; experience; connection; thoughtfully; from our…to yours; whether it’s…or…

**Avoid:** disruptive; game-changing; 10x; crushing it; limited-time hype; dense technical jargon

**Rules:**

- Let emotional headings introduce concrete material or process details rather than unsupported superlatives.
- Explain selection and fulfillment in direct everyday language.
- Use sensory language specific to the new product; do not force food metaphors onto unrelated services.
- Keep practical details legible and literal even when the surrounding scene is theatrical.

## Do's and Don'ts

### Do

- Keep default display capitals at weight 300 with -0.04em tracking and compressed 0.8–0.9 line height.
- Hold desktop text 28px from full-width edges while letting photography bleed.
- Use 13px medium sans-serif support to make the serif scale feel monumental.
- Reserve ochre for a substantial ledger, 40px action squares, proof stars and the giant closing line.
- Give quote cards the full 446px height so the author can sit low beneath a short quotation.
- Keep frames and table rules at 1px with almost square 2–4px corners.
- Balance a warm full-scene photograph with a flat cream editorial field.
- Finish with practical information followed by a near-full-width sans-serif brand line.

### Don't

- Do not replace cream #d8cbb8 with bright white; that removes the printed-stock warmth.
- Do not set the main headlines in bold sans-serif; save the giant sans-serif treatment for the closing sign-off.
- Do not round the rectangular actions into pills or enlarge the 3px card corners into soft dashboard tiles.
- Do not scatter ochre across every section background or every heading.
- Do not add elevation shadows to the ruled proof and catalog cards; their hierarchy comes from hairlines and spacing.
- Do not insert large app-style icons into every narrative block; the small pictograms belong to actions and contacts.
- Do not make catalog category headings uppercase simply because marketing display type is uppercase.
- Do not turn the centered principle-card sequence into a conventional four-up feature grid.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.4s transitions; the fixed header declares 0.45s.
- The proof marquee declares a 27s linear infinite animation.
- Principle cards and catalog heading blocks use sticky positioning.

**Transfer:**

- Keep the quote strip continuously flowing rather than paginating it into a conventional slider.
- Use the sticky narrow card stack only for a deliberate long-form principle chapter.

**Unknown:**

- The exact timing and triggers for object transformations and headline reveals are not established.
- No focus-visible treatment is established for the framed in-section action.

### Responsive

**Observed:**

- Styles include width breakpoints at 479px, 480px, 767px, 768px, 991px and 1024px; variants also include 769px and 992px.

**Transfer:**

- For narrow screens, preserve the two-line editorial hierarchy and small flank labels when space permits; stack the editorial split and catalog columns rather than compressing paragraphs into narrow strips.
- Keep the proof strip horizontally continuous with partial neighboring cards visible. Scale the closing brand line to the available width instead of wrapping it into footer body copy.
- Place support and proof beneath the main atmospheric headline when opposite corners no longer fit.

**Unknown:**

- Exact mobile typography, menu behavior and section heights are not established; narrow-screen arrangements above are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
