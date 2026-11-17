# Agility Robotics — fieldwork meets cinema

## Overview

An industrial but approachable marketing style, with warm stone canvases, charcoal typography and cinematic views of technology doing real work. Regular grotesk headlines and small monospaced labels give it the feel of equipment documentation without becoming a dashboard. Broad photographic stages alternate with sparse editorial columns; color belongs to the objects and environments rather than the interface. It suits tangible products, operational software and technically ambitious companies with practical results to show.

### Essentials

- The promise is a plainspoken, nearly edge-to-edge sentence above the demonstration: regular 80px grotesk, 0.93 line height and -0.03em tracking, centered after 250px of opening space.
- The interface stays warm and achromatic: #f0eeeb dominates, #d6d3ce marks secondary chapters and #292827 anchors endings; saturated color is confined to photography and demonstrations, not marketing fills.
- Media is the main event, not a thumbnail: broad 1430px stages with 5px outer gutters and 24px corners alternate with half-width 668×834px portraits of products in use. Use an environment photograph or clearly lit working prototype when cinematic footage is unavailable.
- Actions look like small equipment controls: 36px-high rectangles, 6px radius, 11px 13px padding, 12px bold mono capitals and a separated right arrow; dark, outline and cream variants share the same geometry.
- A riveted viewing plate is a signature device: a centered 600px-wide black translucent tile, 12px corners, 55px padding and 5.5px backdrop blur, with four 6px square corner marks over a full photographic scene.
- Proof is drawn as engineering notation rather than spectacle: use hairline circle-and-arrow diagrams with numbered 28px captions, or the same small mono labels and registration marks to explain a product mechanism. Keep broad chapter spacing at 150px and internal text gaps at 12px–30px.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm charcoal | `#292827` | `--color-ink` | text, background, action | Main lettering, solid controls and dark closing canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Smoked plate | `#30302f` | `--color-plate` | surface | Black at 80% over warm paper; over photography its visible tone follows the image. |
| Raised charcoal | `#393837` | `--color-panel` | surface | Backing of photographic route cards; not a drop shadow. |
| Dark hairline | `#494847` | `--color-dark-rule` | border | White at 15% over charcoal, used for the footer's final separator. |
| Process gray | `#6a6660` | `--color-process-ink` | text, action | Process numbers and stone-band button hover. |
| Control taupe | `#958d83` | `--color-taupe` | text, border, action | Outline controls, attribution text and filled hover controls. |
| Muted gray | `#938f89` | `--color-muted` | text, border | Secondary footer text and secondary hover lettering. |
| Paper hairline | `#c2bfba` | `--color-rule` | border | Visible half-opacity gray separator on warm paper; source hue #938f89 at 50%. |
| Chapter stone | `#d6d3ce` | `--color-stone` | background, surface, text | Secondary editorial bands, process panel and inverse button text on those bands. |
| Navigation wash | `#eae6de` | `--color-nav-wash` | surface | Visible warm translucent navigation over paper; source hue #e8e3d8 at 70%. |
| Warm paper | `#f0eeeb` | `--color-canvas` | background, text, action | Dominant page canvas, inverse text and light controls. |
| Media white | `#ffffff` | `--color-white` | surface | Light backing for logo panels and product imagery. |

## Typography

- **Agility Diatype** — Headlines, body, navigation and editorial titles. Matter-of-fact contemporary grotesk, open forms with a tightly fitted regular-weight display voice. OpenType features: "ss01", "ss07", "ss09", "ss10", "ss11". If unavailable, use **Inter**. Use 400 for display and body, 700 for editorial titles; preserve compact tracking. Font stack: "Agility Diatype", "Inter", Arial, sans-serif.
- **Agility Diatype Mono** — Eyebrows, button labels, captions and technical metadata. Compact monospaced industrial notation with small uppercase labels. If unavailable, use **IBM Plex Mono**. Use 700 for labels and 400 for metadata. Font stack: "Agility Diatype Mono", "IBM Plex Mono", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Agility Diatype | 400 | 80px | 0.93 | -0.03em | Centered promise above the main demonstration. |
| heading | Agility Diatype | 400 | 36px | 1 | -0.03em | Section headings, broad introductory statements and customer quotes. |
| card-heading | Agility Diatype | 400 | 28px | 1 | -0.02em | Overlay titles, process descriptions and process numbers. |
| editorial-title | Agility Diatype | 700 | 19px | 1.2 | -0.01em | Editorial card titles and people names; article titles have link underlining. |
| body | Agility Diatype | 400 | 16px | 1.25 | -0.01em | Editorial support paragraphs. |
| card-body | Agility Diatype | 400 | 15px | 1.25 | -0.01em | Centered media-card copy and small announcements. |
| navigation | Agility Diatype | 400 | 14px | 1 | -0.01em | Small mixed-case navigation links. |
| editorial-meta | Agility Diatype Mono | 400 | 13px | 1 | normal | Article category and date, with subdued opacity. |
| footer-link | Agility Diatype | 400 | 13px | 1.2 | normal | Compact inverse navigation columns. |
| label | Agility Diatype Mono | 700 | 12px | 1 | 0.06em, uppercase | Section labels, buttons and diagram labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product-detail, company and recruiting openings | subpage-display | Agility Diatype | 400 | 62px | 0.93 | -0.03em | Left-aligned secondary opening titles and text directly over product footage. |
| recruiting directories | listing-category | Agility Diatype | 700 | 15px | 1.25 | -0.01em | Department heading beside the ruled list. |
| attributions, people directories and role listings | technical-meta | Agility Diatype Mono | 400 | 13px | 1.2 | normal | Names and roles beneath quotes, job titles and locations. |
| product-detail, company and recruiting openings | subpage-eyebrow | Agility Diatype Mono | 700 | 12px | 1 | 0.08em, uppercase | Page category above secondary opening titles. |
| location cards | coordinates | Agility Diatype Mono | 400 | 10px | 1 | 0.06em | Geographic coordinate line pinned near the lower edge. |

**Notes:**

- Display and section titles stay regular rather than bold; negative tracking is strongest at headline scale, relaxes to -0.02em for card headings and -0.01em for body.
- Mono labels are visually distinct from prose through capitals and positive tracking, not larger size. Carry the stylistic-set settings through both families where supported.
- Use one display sentence rather than stacked oversized words. Secondary openings reduce the headline to 62px and introduce an eyebrow.

## Layout

**Density:** Airy between chapters, compact inside captions and controls; image areas carry much more visual weight than prose.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Near-edge media gutters and narrow tile seams. |
| 12px | Heading-to-body gaps and image-to-title gaps. |
| 18px | Label stacks, media-card padding and compact grouping. |
| 30px | Eyebrow-to-heading or text-to-action gaps; process inset. |
| 55px | Desktop site gutter, overlay padding and closely related chapter spacing. |
| 100px | Expanded internal spacing token. |
| 120px | Vertical block spacing token. |
| 150px | Major chapter separation and section padding. |
| 250px | Top padding of text-led desktop openings. |

### Containers and grids

- **site container**: max width 1440px · side padding 55px. Centered editorial container; at a 1440px viewport the interior is 1330px wide.
- **media stage**: side padding 5px. Near-full-width cinema frame; 1430px wide at desktop.
- **editorial split**: 2 columns · gap 5px. Equal structural halves, with a narrow 407px text measure at the top left and a 668px-wide tall photograph at right. Text can remain sticky while the photograph scrolls.
- **proof row**: 3 columns · gap 5px. Three logo, process or location tiles aligned to the site container.
- **resource row**: 4 columns · gap 5px. Four editorial tiles with 329×219px images; headings and metadata beneath, not inside a boxed card.
- **overlay measure**: max width 600px · side padding 55px. Centered viewing plate; support copy is constrained to 400px.
- **directory** (only for recruiting directories): 4 columns · gap 0px. One quarter for the persistent section label, one quarter for department and one half for ruled jobs.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 6px |
| navigation group | 10px |
| small media and viewing plate | 12px |
| large image and process panel | 24px |
| registration marks | 2px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f0eeeb; color: #292827`

#### Stone chapter · level 0

**Use:** A substantial secondary editorial chapter or process explanation.

**CSS:** `background: #d6d3ce; color: #292827`

**Observed:** A broad continuous field, not a separate color on every card.

**Transfer:** Let a family of related content share this material.

#### Charcoal chapter · level 0

**Use:** Footer and selected closing or historical chapters.

**CSS:** `background: #292827; color: #f0eeeb`

**Observed:** The dark field continues through the footer when preceded by a dark closing chapter.

**Transfer:** Use as an end-weight, rather than alternating dark and light at every section.

#### Frosted navigation · level 2

**Use:** Compact floating navigation groups.

**CSS:** `background: rgba(232, 227, 216, 0.7); backdrop-filter: blur(57px); border-radius: 10px; padding: 5px`

#### Smoked viewing plate · level 2

**Use:** Readable focal point over an immersive photograph.

**CSS:** `background: rgba(0, 0, 0, 0.8); backdrop-filter: blur(5.5px); border-radius: 12px; padding: 55px; max-width: 600px; color: #f0eeeb`

**Observed:** No visible shadow; tiny corner marks make the tile feel fastened to the scene.

**Transfer:** Preserve the translucent dark material even when the image behind it changes.

#### Media backing · level 1

**Use:** Light logo panels and image containers.

**CSS:** `background: #ffffff; border-radius: 12px`

#### Photographic route backing · level 1

**Use:** Backing under darkened route imagery.

**CSS:** `background: #393837; border-radius: 24px; overflow: hidden`

**Observed:** The image remains visible beneath centered copy; this is not intended as an empty charcoal panel.

## Components

### Floating navigation

**Use:** Persistent site orientation.

**CSS:** `display: flex; padding: 5px; background: rgba(232, 227, 216, 0.7); backdrop-filter: blur(57px); border-radius: 10px`

**Text style:** `navigation` — Agility Diatype 400 · 14px/1 · tracking -0.01em

**Observed:** Brand mark sits separately at left; the compact link group is centered with an adjacent conversion control. Individual links use 8px 10px padding and small plus signs for dropdowns.

**States:** Declared: hover individual links use rgba(255,255,255,0.8) background and #292827 text; focus-visible behavior is not established.

### Dark button

**Use:** Primary action on a pale canvas.

**CSS:** `display: flex; align-items: center; column-gap: 10px; background: #292827; color: #f0eeeb; border: 1px solid #292827; border-radius: 6px; padding: 11px 13px; height: 36px; box-sizing: border-box`

**Text style:** `label` — Agility Diatype Mono 700 · 12px/1 · tracking 0.06em · uppercase

**Observed:** The arrow is a separate inline glyph. Secondary text-led openings use a 40px variant with 13px 15px padding.

**States:** Declared: hover background and border #958d83, text #f0eeeb; focus-visible not established; active outline 0px.

### Outline button

**Use:** Secondary action beneath editorial copy.

**CSS:** `display: flex; align-items: center; column-gap: 10px; color: #292827; background: transparent; border: 1px solid #958d83; border-radius: 6px; padding: 11px 13px; height: 36px; box-sizing: border-box`

**Text style:** `label` — Agility Diatype Mono 700 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Fits the label rather than stretching to fill its column.

**States:** Declared: hover background #f0eeeb and border rgba(147,143,137,0.5); focus-visible not established; active outline 0px.

### Cream button

**Use:** Action over photography or dark fields.

**CSS:** `display: flex; align-items: center; column-gap: 10px; background: #f0eeeb; color: #292827; border: 1px solid #f0eeeb; border-radius: 6px; padding: 11px 13px; height: 36px; box-sizing: border-box`

**Text style:** `label` — Agility Diatype Mono 700 · 12px/1 · tracking 0.06em · uppercase

**Observed:** Same compact geometry as the other actions; used inside the viewing plate.

**States:** Declared: hover background and border #958d83, text #292827; focus-visible not established; active outline 0px.

### Riveted viewing plate

**Use:** Signature callout over a broad image.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; background: rgba(0, 0, 0, 0.8); backdrop-filter: blur(5.5px); border-radius: 12px; padding: 55px; max-width: 600px; color: #f0eeeb; text-align: center`

**Text style:** `card-heading` — Agility Diatype 400 · 28px/1 · tracking -0.02em

**Observed:** Eyebrow, title, compact support copy and Cream button form the stack. Four small cream square registration marks sit inside the corners. The opening announcement is a smaller left-aligned relative with 18px padding.

**Transfer:** Use one crisp point of view over an image that explains the broader working context.

### Numbered process panel

**Use:** Explain how an unfamiliar purchase or mechanism becomes practical.

**CSS:** `display: flex; background: #d6d3ce; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — Agility Diatype 400 · 28px/1 · tracking -0.02em

**Observed:** Three equal cells in a 1330×420px shared panel, divided by hairlines. Small uppercase labels occupy the top, line diagrams the middle, then gray two-digit numbers and regular text at the bottom. Cells have 30px top, bottom and left insets and 18px right inset.

**Transfer:** Use a small set of concrete steps with geometric schematics, not colorful pictograms.

### Editorial tile

**Use:** News, resources and proof that can be explored further.

**CSS:** `display: flex; flex-direction: column; row-gap: 12px; padding: 0px 2.5px`

**Text style:** `editorial-title` — Agility Diatype 700 · 19px/1.2 · tracking -0.01em

**Observed:** A 3:2 image with 12px corners sits above a bold linked heading; 13px mono category and date follow, with 0.7 opacity. Tiles sit directly on the chapter surface, without a perimeter border.

**Transfer:** Use genuine portraits, restrained product imagery or a simple typographic brand panel as thumbnail content.

### Photographic route card

**Use:** One or two substantial next-step destinations.

**CSS:** `display: flex; position: relative; justify-content: center; padding: 18px; background: #393837; border-radius: 24px; overflow: hidden`

**Text style:** `card-heading` — Agility Diatype 400 · 28px/1 · tracking -0.02em

**Observed:** An edge-to-edge darkened photo backs centered title, support and a small translucent action. Square paired variants are 663×663px; a wide variant is 1335×390px. Tiny registration marks bracket the image.

**Transfer:** Keep the imagery legible and the text short; distinguish human assistance from self-directed exploration.

### Footer link column

**Use:** Quiet navigation at the actual page ending.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; row-gap: 6px; color: #f0eeeb`

**Text style:** `footer-link` — Agility Diatype 400 · 13px/1.2

**Observed:** A modest brand symbol occupies the left half; three compact link columns occupy the right with 15px gaps. The footer has 55px top and side padding; legal links and a faint white 15% top rule finish the bottom. Product pages may add a ruled caveat strip above the navigation.

**States:** Declared: hover underline in #938f89, underline offset 0.2em and text #f0eeeb; focus-visible not established; active outline 0px.

### Ruled role row

**Only for:** recruiting directories

**Use:** Dense searchable opportunity listings.

**CSS:** `display: flex; align-items: flex-start; border-top: 1px solid rgba(147, 143, 137, 0.5)`

**Text style:** `technical-meta` — Agility Diatype Mono 400 · 13px/1.2

**Observed:** The inner link adds 24px vertical padding. Title and location form two aligned columns and an uppercase mono apply action sits at right. Rows grow from about 65px to 80px when text wraps.

**Transfer:** Retain the broad category gutter and fine rules; do not turn each opportunity into a rounded card.

## Imagery and graphics

### Cinematic working product

**Use:** The opening and broad demonstration chapters.

**Observed:** Close views of teal-and-black machines alternate with wide, naturally lit factory scenes. Shallow focus, real metal, pale walls and restrained environmental color make the object feel tangible; some wider scenes use polished illustrative realism. The media occupies more area than the text and is clipped to rounded rectangles.

**Transfer:** Photograph a new product in use, with credible materials and a specific working environment. For software, show the actual interface within a real task context rather than inventing a robot equivalent. Minimum acceptable treatment is one sharp product-in-use photograph with convincing light and depth.

### Editorial product portrait

**Use:** Right half of explanatory split chapters.

**Observed:** Tall 668×834px framing isolates a working product or two product generations against pale surroundings. The subject is allowed to extend beyond the frame; backing is light and corners are 24px.

**Transfer:** Choose an equivalent close or medium product view with space around the silhouette; prioritize material detail over decorative composition.

### Engineering circles

**Use:** Process explanation and a recurring technical proof accent.

**Observed:** Very thin charcoal geometry on stone: concentric solid and dotted circles, two intersecting circles linked by a horizontal arrow, and circular arc arrows. Shapes are small relative to their cells and float between top labels and bottom captions.

**Transfer:** Map geometry to the new mechanism: convergence, transfer, repetition or feedback. Keep the diagram as spare as an engineering sketch.

**Build:** Create an SVG with a 225×130 viewBox. Use fill='none', a 1px stroke in #292827 at roughly 0.7 opacity, circles around 110px–130px in diameter, and dotted variants with stroke-dasharray='1 2'. Use a 3px endpoint dot and a small triangular arrowhead for a directional line. For feedback use two open circular arcs with arrowheads at opposing ends. Do not add gradients or shadows.

### Registration marks

**Use:** Corners of image overlays and photographic proof cards.

**Observed:** Four 6×6px cream squares with 2px corners create a subtle equipment-panel motif.

**Transfer:** Repeat the four-corner arrangement on the signature media plate; it should read as a fastening detail, not confetti.

**Build:** Position four 6px square elements about 18px inside each corner of the plate; set background #f0eeeb and border-radius 2px. Use dark squares on a pale image when contrast requires it.

### Location atmosphere

**Only for:** company and recruiting location chapters

**Use:** A three-card geographic portrait.

**Observed:** Tall 442×530px images show a river valley, a dim city street and a rolling hillside. Centered titles and compact descriptions sit high in the frame; coordinates are centered at the bottom. Four tiny marks frame each photograph. Text switches dark or light according to local image brightness.

**Transfer:** Choose atmosphere rather than office-building stock photos: a landscape, street or neighborhood that conveys the place. Use subtle darkness only where needed to keep text legible.

### People and field history

**Only for:** company and recruiting narratives

**Use:** Leadership, culture and historical proof.

**Observed:** Leadership uses close head-and-shoulder portraits on warm gray, arranged three across beside a narrower editorial introduction. Culture uses candid workshop photographs, not posed celebration. A dark historical carousel uses large portrait-shaped archival images and small uppercase mono dates and captions.

**Transfer:** Keep portraits consistent in crop and backing. Show genuine work in culture scenes and reserve rougher archival imagery for the historical rail.

### Icons

**Observed:** Icon vocabulary is minimal: small text arrows and plus signs, a simple solid play/pause mark around 12×11px, and 6px square registration marks. There is no decorative multicolor icon grid.

**Transfer:** Use a single solid utility-icon family and literal arrow glyphs for actions. Keep technical explanation in line diagrams rather than oversized interface icons.

## Section recipes

How recurring sections are built.

### First screen: Promise above cinema

**Observed:** A warm Paper canvas supports a separate left brand mark and a centered Floating navigation within a 101px header zone. The headline sits after 250px of top space, centered across the 1330px interior; display type is 80px, regular and tightly tracked, forming one broad line. After 30px, a near-edge media stage begins at 354px and spans 1430px with 24px corners. Within the first 900px the whole headline and the upper 546px of a large, shallow-focus product film are visible. A small smoked announcement sits inside the media at upper left; the supporting sentence and inline arrow action live there, not under the headline. There is no separate hero button row. The rest of the 890px-tall film and its playback control continue below the fold. Layers are paper, clipped film, compact announcement and playback UI, with navigation above them.

**Transfer:** Give a different product the same immediate visual weight using a strongly lit close-up or a convincing task scene. If footage is unavailable, use one excellent still with a small announcement rather than shrinking the image. Product-detail and company openings use left-aligned 62px titles with a category label and a right-aligned dark action above the cinema. Recruiting opens with a full-bleed 810px-high work photograph and a light 62px title near the lower left.

**Avoid:** Do not make this a conventional split hero with a tiny object beside a paragraph, or add a centered pair of oversized CTA pills beneath the promise.

**Text style:** `display` — Agility Diatype 400 · 80px/0.93 · tracking -0.03em

### Editorial product split

**Observed:** Editorial split places a label above a 36px heading, a 16px support paragraph and Outline button at left, against a tall working-product image at right. The text measure is about 407px; label and action separation use 30px and the heading-to-copy gap is 12px. A Stone chapter provides a coherent variant for a related story.

**Transfer:** Use for a product explanation, differentiator or operating principle; keep the asymmetry in visual density even though structural halves are equal.

**Text style:** `heading` — Agility Diatype 400 · 36px/1 · tracking -0.03em

### Shared proof row

**Observed:** A label and 36px heading introduce three aligned logo panels or the Numbered process panel. Logos sit in restrained white rounded panels; the process alternative uses a continuous stone panel with fine dividers, small schematics and bottom-aligned numbers and descriptions.

**Transfer:** Use independent logos for endorsement and linked diagram cells for explanation; neither requires inflated numeric claims.

### Immersive viewing plate

**Observed:** An 890px-high rounded scene with 5px exterior gutters surrounds a centered Riveted viewing plate. Its title is 28px, support copy 15px and button label 12px mono. The scene remains expansive on all sides rather than becoming a text background strip.

**Transfer:** Use the scene to show the consequence of the product at a larger scale and the plate to state one memorable principle.

### Resources on the chapter surface

**Observed:** A 36px section title is paired with a small mono arrow link at the opposite side. Four Editorial tiles align below with image-to-title gaps of 12px and tiny metadata. A 150px chapter gap keeps this row distinct from the footer.

**Transfer:** End a narrative with useful next reading rather than another summary paragraph.

### Dark field closing

**Observed:** A Charcoal chapter can combine a left-aligned label, 36px title, short 16px support and cream action aligned to the far right. A broad rounded aerial image follows. Some product narratives continue into two square Photographic route cards before the footer; recruiting ends directly from the broad image into the footer.

**Transfer:** Use an environmental overview to widen the story at the end, then supply one clear next step. Match the footer background to the closing chapter.

### Actual footer ending

**Observed:** All endings settle into the Charcoal chapter, with a brand symbol on the left and Footer link columns at right. A narrow legal row and faint top separator finish the page. Product-led variants prepend a caveat strip with a small number and explanatory text; company and recruiting variants omit that strip.

**Transfer:** Keep the final moment informational and calm, not a second giant headline or subscription panel.

### Historical image rail

**Only for:** company history narratives

**Observed:** A dark chapter with 150px top and bottom spacing introduces a 36px title, short support paragraph and small Prev/Next controls. The horizontal rail contains 438×548px archival photographs, small gray dates and uppercase mono captions. The next image peeks beyond the viewport.

**Transfer:** Use for an actual developmental story; each image should demonstrate a change rather than act as abstract decoration.

### Culture and recruiting directory

**Only for:** recruiting pages

**Observed:** A work-scene opening leads into a broad 36px introduction, a three-image culture row, numbered values separated by fine rules, Location atmosphere cards and a long directory. A small Open roles label remains in the broad left gutter; department headings and Ruled role rows occupy the remaining width. A dark environmental closing and ordinary footer conclude the page.

**Transfer:** Treat the directory as a useful structured destination, using the preceding imagery to convey a credible workplace rather than turning every vacancy into marketing.

## Page flow

**Storyline:** Plain promise → working demonstration → practical explanation → independent proof → process or capability detail → wider context → useful next steps → restrained informational ending.

### Broad brand and product landing

1. **Promise** — One centered sentence above near-edge film.
2. **Explanation** — Sparse editorial product split.
3. **Social proof** — Three partner panels.
4. **Practical reassurance** — Numbered geometric process panel.
5. **Expanded vision** — Immersive scene with riveted plate.
6. **Credibility** — Stone editorial chapter and wide fieldwork image card.
7. **Next reading** — Four compact editorial tiles.
8. **Ending** — Dark caveat strip, brand symbol, navigation and legal row.

**Transfer:** Use the broad visual demonstration as the anchor; let explanatory chapters build trust before asking for a deeper commitment.

### Product family and application landing

1. **Promise** — Left title, category, support and conversion action above film.
2. **Product demonstration** — Full-width footage with inverse product text.
3. **Capabilities** — Tabbed software explanation and split workflow selector with one large image.
4. **Independent proof** — Large quote with mono attribution and small slide indicators.
5. **Enablement** — Four resource tiles.
6. **Expanded relevance** — Dark heading band and aerial environmental image.
7. **Closing action** — Paired photographic routes for direct help and independent exploration.
8. **Ending** — Caveat strip and dark footer.

**Transfer:** Make different products and capabilities legible as distinct demonstrations, then give both assisted and self-directed next steps.

### Company credibility and human depth

1. **Promise** — Compact left-aligned opening above a cinematic story.
2. **Position** — Broad regular-weight editorial statement.
3. **Human credibility** — Leadership portrait grid with narrow introduction.
4. **Social proof** — Partner panels.
5. **Place** — Three atmospheric location cards.
6. **Operational proof** — Large facility scene and centered viewing plate.
7. **Track record** — Dark historical image rail.
8. **Future and next steps** — Another immersive principle and paired photographic routes.
9. **Ending** — Editorial tile row followed by the shorter dark footer without a caveat strip.

**Transfer:** Combine people, place and actual operating history; use photographic chapters to avoid a corporate text wall.

### Recruiting narrative and usable opportunity directory

1. **Invitation** — Full-bleed candid work scene and lower-left title.
2. **Team proposition** — Broad editorial statement, candid triptych and ruled numbered principles.
3. **Place** — Three atmospheric location cards.
4. **Opportunity discovery** — Long category-and-row directory with mono role and location columns.
5. **Wider purpose** — Dark statement band, cream action and broad overhead scene.
6. **Ending** — Dark footer continuous with the closing chapter, without product caveats.

**Transfer:** Reserve dense typography for the actual directory and show work, not generic perks, in the preceding narrative.

## Writing

Confident, practical and skeptical of hype. Ambition is grounded in deployment, real work and concrete proof, with warmth coming from the people doing it.

**Do not copy:** Do not reuse Agility names, logos, product names, customer endorsements, quoted testimonials, operational numbers, geographic coordinates or claims of firsts. Replace them with substantiated material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker, you and your for operational benefits, and the product name when explaining what a system actually does.
- **Rhythm:** Short, balanced headline clauses with full stops; compact opening fragments can lead into a longer explanatory sentence. Support text is functional, with few embellishments and no celebratory punctuation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Pair the product category with an outcome in two clipped clauses. | 4–7 words | “Humanoid robots. Proven results.”<br>“Delivering now. Dreaming bigger.” |
| Supporting line | Start with the real context, then extend its practical relevance. | 1–3 compact sentences | “Built for industrial environments. Ready for so much more.” |
| Credibility statement | Reject empty rhetoric briefly, then explain demonstrated capability. | Short opening fragments followed by factual prose | “No vaporware. No hype. Just innovation that works.” |
| Primary action | Plain verb plus a specific destination or task. | 2–5 words | “Explore Solutions”<br>“Watch the video” |
| Human invitation | Direct invitation, then concrete descriptions of the work. | 4–12 words in short clauses | “Come build with us”<br>“Hard problems. Real deployment. A team that ships.” |

**Words and phrasing to use:** work; built; proven; deploy; real-world; capable; reliable; team; results; your operation

**Avoid:** magical; revolutionary as an unsupported claim; effortless everything; game-changing; limitless potential; exclamation-heavy celebration

**Rules:**

- Lead with a useful outcome rather than a technological superlative.
- Separate today's capability from future work and qualify material limitations plainly.
- Name the working environment or task when explaining value.
- Keep section labels taxonomic and button labels specific.
- Let facts carry confidence; use a quote only with a real attributed source.

## Do's and Don'ts

### Do

- Keep the main centered promise at 80px, weight 400 and -0.03em tracking on desktop.
- Use 55px editorial gutters and 5px cinema gutters as deliberately different scales.
- Make at least one broad photographic chapter carry a smoked, riveted viewing plate.
- Keep 36px section titles at line height 1 and pair them with compact 16px support.
- Use 6px corners for controls, 12px for smaller panels and 24px for major stages.
- Preserve 150px breathing room between major chapters while grouping text at 12px–30px.
- Keep the editorial resource row at four columns on the desktop composition.
- Let photographs supply chromatic intensity while navigation and actions remain neutral.

### Don't

- Do not substitute a bright teal UI palette for the neutral controls just because a photographed object is teal.
- Do not make every heading bold; 700 belongs mainly to small labels and editorial titles.
- Do not introduce floating card shadows; elevation here comes from image layering and translucency.
- Do not replace compact 36px controls with 56px rounded pills.
- Do not put a white box and border around every editorial tile; the chapter canvas is its backing.
- Do not enlarge metadata into body copy; retain the 12px–13px mono distinction.
- Do not turn the ruled directory into a mosaic of promotional cards.
- Do not darken every scene uniformly; preserve local material detail and use focused text protection.

## Motion and responsive

### Motion

**Observed:**

- Controls declare 0.2s transitions; the broader stylesheet also includes 0.3s transitions and a small number of 0.1s background/color changes.
- Film stages have play/pause controls; a declared focus-visible state for those controls uses a 2px #3b79c3 outline with 2px offset and 6px corners.
- Historical and testimonial sections use explicit previous/next controls or slide indicators. No matched animation sequence establishes a general entrance pattern.

**Transfer:**

- Retain actual playback control on moving demonstration scenes.
- Keep hover transitions concentrated on the small neutral controls instead of making the whole page feel kinetic.

**Unknown:**

- Autoplay sequencing, scroll-trigger behavior and reduced-motion adaptations are not established.

### Responsive

**Observed:**

- Stylesheet width breakpoints include 479px, 767px, 768px, 990px, 991px, 1280px and 1550px; recruiting also includes 1299px.

**Transfer:**

- On narrow screens, stack editorial text above its media while preserving the difference between near-edge stages and inset reading columns.
- Reduce the broad promise to fit natural lines rather than squeezing letters; keep the plate's corner marks visible and let its support text wrap.
- Reflow role metadata beneath the title when necessary, preserving the apply action and fine row boundaries.

**Unknown:**

- Exact mobile type sizes, gutters, navigation behavior and stacking rules are not established. These narrow-screen adaptations are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
