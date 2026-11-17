# BitcoinOS — portals and proclamations

## Overview

A cinematic, otherworldly style pairs monumental condensed capitals with literary serif explanations. Near-black and warm white form the architecture, while golden light, blue shadows and richly textured imaginary worlds carry the color. It suits ambitious infrastructure and frontier products that need both a sense of possibility and a credible technical explanation; spacious visual chapters alternate with compact directories and reading panels.

### Essentials

- Proclamations feel compressed into solid blocks: Review Condensed at 128px, weight 900, uppercase, 0.8 line height and normal tracking, balanced by Kalice serif copy at 16px/1.6 with 0.06em tracking.
- The opening is a world, not a boxed product mockup: a full-width cinematic scene begins under a 64px header, with a left-aligned two-line headline occupying about three fifths of the width and the principal illuminated object on the right. Keep the support paragraph to 380px.
- Actions have joined, scalloped geometry: 48px-high warm-white buttons with 8px corners, a separate adjoining 48px arrow cell, and 8px between primary and outlined secondary actions; text is bold 14px sans.
- Color lives in the world behind the words: all structural surfaces, headings and controls remain neutral; gold, amber, moss and blue appear in large image-led stages rather than colored UI cards. Dark stages dominate the default landing-page treatment.
- Light is the product metaphor: stage a small human-scale silhouette against a vast luminous object or opening, with dark textured foregrounds and a legible text zone. Every new page needs an atmospheric light scene; a layered SVG portal and terrain silhouette is the minimum equivalent.
- Small serif brackets label the giant statements: 12px/12px Kalice, weight 400 and 0.06em tracking, set above condensed headings or at the start of hairline-divided entries.
- The ending becomes a graphic object: three aligned navigation columns lead into a centered newsletter inside a huge dark elliptical bowl on charcoal, then an edge-to-edge warm-white word sculpture. Recreate this with the new product's short name or a short original closing word.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Scene gold | `#e7b844` | `--color-scene-gold` | accent | Golden illumination within cinematic artwork, not a UI fill. Match the warm luminous material rather than treating this as a flat brand-color swatch. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm white | `#fffafa` | `--color-foreground` | text, surface, action, border | Display text, primary actions, outlined controls and light cards. |
| Near-black canvas | `#101010` | `--color-canvas` | background, text | Default dark page foundation and text on light actions. |
| Charcoal band | `#1a1a1a` | `--color-raised` | background, surface | Secondary dark bands and the backing behind the footer bowl. |
| Dark hairline | `#272727` | `--color-rule-dark` | border, surface | Dark directory dividers and inactive category controls. |
| Silver copy | `#bababa` | `--color-muted-dark` | text | Body copy, quotes and bracket labels on dark sections. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| light information sections | Black ink | `#000000` | `--color-ink` | text | Strong headings and data on paper. |
| light information sections | Gray copy | `#5e5e5e` | `--color-muted-light` | text | Paragraphs and labels against paper or warm white. |
| people directories | Portrait role gray | `#a3a3a3` | `--color-role-muted` | text | Role titles below black person names. |
| light information sections | Light hairline | `#e5e5e5` | `--color-rule-light` | border | Reading-panel separators and accordion dividers. |
| technical, financial and company-information pages | Warm gray paper | `#f3efef` | `--color-paper` | background, surface | Long-form reading, financial detail and people-directory canvases. |

## Typography

- **Review Condensed** — Monumental headlines and emphatic numeric summaries. Very heavy, narrow grotesk with blunt uppercase shapes and extremely tight vertical stacking. If unavailable, use **Barlow Condensed**. Use weight 900; retain the narrow silhouettes and 0.8 line height. Font stack: "Review Condensed", "Barlow Condensed", sans-serif.
- **Review** — Buttons, item titles, footer links and compact data labels. Robust grotesk with dense bold forms; less condensed than the headline face. If unavailable, use **Inter**. Use weights 700 and 900. Font stack: "Review", "Inter", sans-serif.
- **Kalice** — Descriptions, narrative passages, quotes and bracket labels. Editorial serif with delicate contrast and distinctly open tracking, creating a deliberate counterpoint to the heavy sans. If unavailable, use **Libre Caslon Text**. Use regular and italic 400; retain the generous tracking. Font stack: "Kalice", "Libre Caslon Text", serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Review Condensed | 900 | 128px | 0.8 | normal, uppercase | Primary cinematic hero and large chapter proclamations. |
| footer-heading | Review | 900 | 32px | 0.88 | -0.01em, uppercase | Footer navigation and newsletter heading. |
| narrative-lead | Kalice | 400 | 24px | 1.4 | 0.04em | Centered cinematic chapter support or a short standalone explanatory passage. |
| item-title | Review | 700 | 24px | 1.1 | normal | Directory titles, feature names and paired data labels. |
| body | Kalice | 400 | 16px | 1.6 | 0.06em | Default supporting paragraphs and item descriptions. |
| action | Review | 700 | 14px | 1 | 0.02em | Buttons, category controls and short resource links. |
| eyebrow | Kalice | 400 | 12px | 1 | 0.06em | Square-bracket section labels, categories and small indices. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical reading pages | reading-heading | Review Condensed | 900 | 56px | 0.8 | normal, uppercase | Compact headline inside a narrow technical reading column. |
| financial detail sections | data-display | Review Condensed | 900 | 48px | 0.8 | normal, uppercase | A leading numeric value in a light summary card. |
| expanded use-case stories | story-title | Kalice | 400 | 32px | 1.2 | 0.02em, uppercase | Centered titles in the wide illustrated story accordion. |
| people directories | person-label | Review | 700 | 21.7px | 1.1 | normal | Person names and stacked role labels. |
| technical reading and editorial cards | compact-title | Review | 700 | 18px | 1.1 | 0.01em | Small explanatory feature titles, questions and editorial card headlines. |
| expanded use-case stories | quote | Kalice | 400 italic | 16px | 1.6 | 0.06em | A short quote inside an expanded story. |
| technical reading pages | compact-body | Kalice | 400 | 14px | 1.6 | 0.08em | Explanatory paragraphs beneath diagram cards. |

**Notes:**

- Condensed display type is stacked as a near-continuous silhouette; keep normal letter spacing rather than adding fashionable wide tracking.
- Serif paragraphs deliberately breathe horizontally: tracking is 0.04em at 24px, 0.06em at 16px and 0.08em in compact 14px technical prose.
- Section title artwork uses the same heavy condensed uppercase language at a smaller scale than the hero, generally around 72px. Use it as a separate graphic heading rather than making every section another 128px hero.
- The final word sculpture is artwork, not a body heading: fit an extremely bold short word across the whole width and allow its lower portion to extend beyond the viewport.

## Layout

**Density:** Airy cinematic stages with compact internal controls; long pauses around the scenes contrast with closely ruled lists.

### Spacing

**Spacing system:**

- **base** 8px — Primary declared layout step for controls, padding and section rhythm; 12px is a separate recurring gutter.

| Value | Use |
| --- | --- |
| 8px | Action spacing, media inset and tight controls. |
| 12px | Grid gutters across card and directory layouts. |
| 16px | Title-to-description gaps and input inner horizontal padding. |
| 24px | Card padding and title-block gaps. |
| 32px | Internal spacing within directory entries. |
| 48px | Reading-section heading-to-content gaps and row gaps in two-column technical features. |
| 64px | Desktop outer margins, section subchapter spacing and newsletter separation. |
| 88px | Information-band vertical padding. |
| 112px | Hero inner top padding below the header. |
| 128px | Major dark-band entrances and footer top padding. |
| 144px | Roomy company and community transitions. |

### Containers and grids

- **main container**: max width 1312px · 12 columns · gap 12px · side padding 64px. Centered desktop content aligned across hero copy, grids and footer.
- **full-bleed stage**: max width 1440px · side padding 0px. Cinematic backgrounds and rounded edge-to-edge bands.
- **directory grid**: 4 columns · gap 12px. Four 319px entries span the main container; text sits inside 24px padding.
- **three-column proof**: 3 columns · gap 12px. Three 429px community, address or navigation groups.
- **hero support**: max width 380px. Narrow left-aligned description against a large right-side image.
- **newsletter**: max width 430px · gap 4px. Centered input and submit row inside the footer bowl.
- **reading column** (only for technical reading pages): max width 650px · 2 columns · gap 12px. A narrow main reading track with paired 319px explanatory cards, alongside a 275px contents rail.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 8px |
| cards and inset media | 16px |
| logo wells | 12px |
| major band corners | 48px |
| footer bowl | 50% |

## Surfaces and depth

### Surfaces

#### Dark canvas · level 0

**Use:** Default marketing foundation.

**CSS:** `background: #101010; color: #fffafa`

**Observed:** Flat, matte and nearly black; scene lighting provides depth rather than raised shadows.

**Transfer:** Keep the structural page dark even when the illustration contains intense light.

#### Charcoal band · level 0

**Use:** Separate a collection of applications or stories from the dark directory.

**CSS:** `background: #1a1a1a; border-radius: 48px 48px 0px 0px; padding: 128px 0px 88px`

**Observed:** A broad full-width band with rounded upper corners, followed by a continuous charcoal story area.

**Transfer:** Use for a substantial secondary chapter, not as a background for every card.

#### Story panel · level 1

**Use:** Expanded illustrated narrative inside the charcoal band.

**CSS:** `background: #101010; border-radius: 16px 16px 0px 0px; padding: 8px`

**Observed:** The dark panel contains a narrow text region and a large rectangular image on its right.

**Transfer:** Preserve the low-contrast nesting and let the image create the visual emphasis.

#### Footer bowl · level 0

**Use:** Sculptural newsletter surround.

**CSS:** `background: #1a1a1a; border-radius: 0px 0px 48px 48px; overflow: hidden`

**Observed:** A near-black oversized ellipse overlays this charcoal backing and drops into a deep curved bottom beneath the centered form; legal text sits in the lower corners.

**Transfer:** Layer a 1440px-wide ellipse over a 590px charcoal band; keep the content above both shapes.

#### Paper canvas · level 0

**Only for:** technical, financial and company-information pages

**Use:** Readable information-heavy chapters.

**CSS:** `background: #f3efef; color: #000000`

**Observed:** Warm gray, not bright blue-white; technical pages introduce a warm-white reading sheet with 48px upper corners.

**Transfer:** Use this inversion for dense explanation while retaining dark cinematic openings or closing calls.

#### Light card · level 1

**Only for:** light information sections

**Use:** People, press and financial summary content.

**CSS:** `background: #fffafa; border-radius: 16px; padding: 24px; box-shadow: none`

**Observed:** Warm-white cards float through tonal difference only. Image and text can form separate touching rounded blocks.

**Transfer:** Retain softly notched joins between stacked blocks instead of adding shadows.

## Components

### Navigation bar

**Use:** Persistent wayfinding above image-led sections.

**CSS:** `position: fixed; height: 64px; padding: 8px; max-width: 1440px; z-index: 50`

**Text style:** `action` — Review 700 · 14px/1 · tracking 0.02em

**Observed:** A 48px square logo anchors the left, a short bold wordmark sits centrally, and compact section links plus a 48px menu square align right. Deeper in the page, logo and menu remain visually dominant while the full link row recedes.

**Transfer:** Use a simple original mark and a compact product name; preserve the three-part balance.

### Primary button

**Use:** Main conversion action over dark scenes.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; background: #fffafa; color: #101010; border-radius: 8px`

**Text style:** `action` — Review 700 · 14px/1 · tracking 0.02em

**Observed:** The label cell may join a separate arrow square with matching rounded corners. The touching corners make a small inward notch rather than one uninterrupted capsule.

**States:** Declared: hover on ancestor changes the label cell background-color to transparent; focus-visible not specified.

**Transfer:** Use an up-right arrow for external progression; omit the separate cell only for simple form submission.

### Outline button

**Use:** Secondary action adjacent to the primary.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; color: #fffafa; background: transparent; border: 1px solid #fffafa; border-radius: 8px`

**Text style:** `action` — Review 700 · 14px/1 · tracking 0.02em

**Observed:** A single outlined label cell sits beside the filled action, without an extra arrow cell.

**States:** Declared: hover on ancestor keeps background-color transparent; focus-visible not specified.

### Directory entry

**Use:** Logo-led partner, integration or capability entries.

**CSS:** `border-top: 1px solid #272727; padding: 8px 8px 8px 24px; display: flex; justify-content: space-between; gap: 12px`

**Text style:** `item-title` — Review 700 · 24px/1.1

**Observed:** The top zone pairs a bracket category on the left with a monochrome logo in a 160px by 104px well on the right. Beneath it, a 24px-padded body holds a bold title, a 16px gap and serif explanation. There is no filled card shell on the default dark canvas.

**Transfer:** Use concise descriptions and one-color marks rather than full-color badges.

### Footer link row

**Use:** Prominent grouped navigation at the end.

**CSS:** `height: 50px; border-top: 1px solid #272727; position: relative; overflow: hidden; color: #fffafa`

**Text style:** `footer-heading` — Review 900 · 32px/0.88 · tracking -0.01em · uppercase

**Observed:** Three columns align their labels and links left, center and right respectively. A charcoal pseudo-layer covers each row's full area beneath the text.

### Newsletter input

**Use:** Email collection inside the centered footer.

**CSS:** `height: 48px; width: 327px; border: 1px solid #fffafa; border-radius: 8px; display: flex; align-items: center; background: transparent`

**Observed:** The actual field has 16px side padding. A filled Submit button sits 4px to its right; a bracket label and bold sans heading sit above the row.

### Category control

**Only for:** filterable directories

**Use:** Compact category selection above a collection.

**CSS:** `height: 48px; background: #272727; color: #fffafa; border-radius: 8px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Review 700 · 14px/1 · tracking 0.02em

**Observed:** Controls sit in an 8px-gap row; the selected all-items option inverts to warm white with dark text. A grid-view switch is aligned at the opposite edge.

**States:** Declared: hover on ancestor sets background-color to transparent; focus-visible not specified.

### Story accordion

**Only for:** expanded use-case stories

**Use:** A small set of deep illustrated applications.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 16px; overflow: hidden`

**Text style:** `story-title` — Kalice 400 · 32px/1.2 · tracking 0.02em · uppercase

**Observed:** A bracketed index stays left, a large uppercase serif title is centered, and plus/minus stays right. The open row reveals the Story panel with a 429px text region and 650px by 474px image; closed rows retain their ruled header.

**Transfer:** Use for a few substantive audience stories rather than a dense FAQ.

### FAQ row

**Only for:** technical reading pages

**Use:** Compact objection handling inside a narrow light column.

**CSS:** `border-top: 1px solid #e5e5e5; display: flex; flex-direction: column; justify-content: center`

**Text style:** `compact-title` — Review 700 · 18px/1.1 · tracking 0.01em

**Observed:** A roughly 59px closed row pairs a left question with a 14px plus at the far right; the answer uses the body serif recipe below.

### Person card

**Only for:** people directories

**Use:** Human proof on warm paper.

**CSS:** `background: #fffafa; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `person-label` — Review 700 · 21.7px/1.1

**Observed:** A separate inset warm portrait block touches the information block. Black name and gray role stack without a gap; small square social links and a circular plus sit beneath. Four columns have staggered starts.

**Transfer:** Use consistent amber-lit portraits and stagger real content, never empty decorative cards.

## Imagery and graphics

### Cinematic light worlds

**Use:** Opening, chapter transitions and closing conversion stage; the signature visual language.

**Observed:** Vast ridged terrain, stone or fiber-like canyons surround a cloaked human-scale figure and radiant geometric objects. Gold and amber light wash textured surfaces against deep green, blue and near-black shadows. The scene occupies almost the entire viewport; text stays flat warm white above a darker region.

**Transfer:** Create an original spatial metaphor for the product: an illuminated instrument, portal or abstract system within an expansive dark environment. A carefully lit static render is sufficient; preserve scale, texture and the bright focal point.

**Build:** For a minimum SVG version, use a 1440px by 988px scene with a dark base, three irregular curved terrain silhouettes and nested contour strokes 8px apart. Place a luminous ellipse or narrow doorway in the right half, layer rgba(255,205,80,0.18) light fields at 160px and 320px blur behind it, and add a small dark figure or simple plinth at its base. Add fine low-opacity grain and a left-to-right black-alpha gradient for copy contrast. Match the soft glow; exact stops are not essential.

### Segmented scene mask

**Use:** Give large cinematic scenes a distinctive cut-apart framing.

**Observed:** One continuous image is divided into large rounded triangular and trapezoidal pieces. Thin dark diagonal seams cross the scene; corners soften near the top edge and around joins. Technical inset imagery repeats the cut geometry with light seams.

**Transfer:** Keep a coherent image across segments rather than filling each shape with unrelated media.

**Build:** Use an SVG mask in a shared viewBox: draw three or four rounded polygons separated by 3px diagonal channels, with slopes crossing from lower left to upper right and from upper left toward lower center. Round shape junctions with quadratic curves of roughly 24px depth. Reveal one background image through all pieces; use the surrounding canvas color in the channels.

### Monumental closing word

**Use:** Final full-width graphic beneath the footer bowl.

**Observed:** A huge warm-white short word fills and slightly exceeds the width; heavy broad letterforms are cropped by the bottom edge, making language feel architectural.

**Transfer:** Set a short original product name or original closing word as outlined SVG lettering. Preserve the broad weight even if the brand normally has a lighter logo.

**Build:** Create an SVG viewBox about 1440px by 535px, set an extra-heavy sans word to fill the width with minimal side bearing, convert it to paths, and render it in warm white on near-black. Let the page edge clip the lower shapes; do not scale a long phrase into illegibility.

### Luminous story illustration

**Only for:** expanded use-case stories

**Use:** Large rectangular image beside a paragraph and quote.

**Observed:** A tiny figure stands before a huge door or crescent opening; warm light spills over long steps into a blue-green landscape. The image is 650px by 474px with softened corners, materially quieter than the hero.

**Transfer:** Depict a single benefit as a spatial scene, using a small human or object to demonstrate scale.

### Monochrome diagrams

**Only for:** technical reading pages

**Use:** Explain mechanisms in paired cards.

**Observed:** Thin gray line art depicts interlocking links, circles, network nodes, stacked cells and shields on warm-gray rectangular fields. Low-contrast dimensional shading stays subordinate to the title and paragraph.

**Transfer:** Use simple SVG diagrams with thin neutral lines and restrained isometric shading; avoid colorful dashboard screenshots as substitutes.

### Amber portrait wall

**Only for:** people directories

**Use:** Staggered human proof.

**Observed:** Head-and-shoulders photography has warm orange-brown side lighting, dark clothing and backgrounds, and small out-of-focus glowing points. A 303px by 233px image is inset 8px into a 319px rounded white block.

**Transfer:** Photograph or grade all portraits with a consistent dark amber ambience; preserve natural expressions and close framing.

### Icons

**Observed:** Simple monochrome SVG strokes with rounded caps, generally 2px. Arrows and menu marks are about 20px; small row plus icons are 12px–14px. Logos are solid monochrome rather than line-icon approximations.

**Transfer:** Use a consistent rounded-stroke arrow/plus/menu set, with dark icons on white controls and white icons over dark sections.

## Section recipes

How recurring sections are built.

### First screen: World-stage opening

**Observed:** A 64px fixed Navigation bar sits above an edge-to-edge segmented cinematic scene that continues below the first 900px. Layers run from near-black base to amber ridged environment, right-side illuminated figure/object, diagonal Segmented scene mask, dark left contrast zone, then text and controls. A small bracket label introduces a left-aligned 128px two-line proclamation spanning roughly three fifths of the width. The support line is 16px serif in a 380px column; actions follow after 24px with an 8px gap. The principal figure fills the right half from near the upper text line down beyond the fold. Within 900px the headline, support, both actions and most of the object are visible; the directory begins below the scene.

**Transfer:** Use an original atmospheric product metaphor and preserve the left-copy/right-object balance. Without complex art, build the Cinematic light worlds SVG fallback and its segmented mask. Technical pages instead open with a rounded white reading sheet, a 56px condensed headline and inset scene alongside a contents rail; company narratives can use a centered giant statement over a circular scene.

**Avoid:** Do not replace the scene with a small floating SaaS screenshot, center all hero elements by default, or use a plain black screen with a tiny luminous dot.

**Text style:** `display` — Review Condensed 900 · 128px/0.8 · uppercase

### Bracketed section proclamation

**Observed:** A 12px serif bracket label sits above a smaller heavy condensed uppercase graphic headline, with 24px title-block rhythm. Collection headings are centered; application-band headings can align left. White and silver words can share a single heading to separate premise from payoff.

**Transfer:** Use a short categorical label and a brief outcome-led heading; preserve the dramatic size jump from label to title.

### Ruled collection

**Observed:** Below the section proclamation, Category controls lead into four Directory entry columns with 12px gutters. Each entry starts with a fine horizontal rule, a bracket category and monochrome mark, then a bold title and serif paragraph. Charcoal application bands repeat the same entry language with 128px top and 88px bottom padding.

**Transfer:** Adapt to integrations, use cases or capabilities, keeping the open ruled construction rather than turning everything into filled tiles.

### Illustrated story reveal

**Observed:** A centered proclamation introduces the Story accordion on a charcoal band. An open header centers uppercase serif text between an index and minus. The Story panel pairs a short paragraph and italic quote on the left with a large luminous landscape on the right.

**Transfer:** Use this contrast of compressed sans section heading and elegant serif item titles for deeper audience stories.

### Immersive chapter

**Observed:** A viewport-filling environment supports centered 128px condensed chapter words and a narrow 24px serif lead. Subsequent narrative blocks shift to a left or right column; each starts with a short 24px by 4px dash, followed by a bold problem line and serif explanation. The environment continues behind the prose.

**Transfer:** Use for a product transformation narrative with real explanatory substance; keep the background focal light clear of the prose.

### Paper explanation and proof

**Observed:** Warm paper hosts light cards, data lists, monochrome diagrams and compact accordions. Financial details pair two broad columns of bold labels and values; a leading 48px condensed number anchors the chart summary. Company proof uses staggered Person cards, followed by four editorial cards with scene thumbnails and 18px bold titles.

**Transfer:** Invert only the information-heavy part of a page; retain the same spacing, condensed headings, serif paragraphs and rounded joins.

### Cinematic closing call

**Observed:** A roughly 980px dark scene places a bracket label, a centered two-line monumental invitation and joined Primary button above a small figure in a blue-lit canyon. A bottom gradient fades the environment into the Dark canvas. The financial variant swaps in a darker ribbed portal scene and a purchase action.

**Transfer:** Restate the visitor's next step as an invitation over a new light scene, not a repeated feature list.

### Bowl and word ending

**Observed:** After the conversion or community stage, three Footer link row columns align left, center and right, each introduced by a small bracket label. Below, a small vertical orange-lit image precedes a centered newsletter label, 32px bold sans heading and 430px form. The Footer bowl curves beneath them on charcoal, with small legal links at its lower corners. The Monumental closing word follows edge to edge.

**Transfer:** Keep both the curved newsletter stage and huge closing word; use original imagery and the new product's navigation structure.

## Page flow

**Storyline:** Immersive promise → concrete capabilities or directory → deeper applications and proof → cinematic invitation → sculptural utility ending.

### General brand or product story

1. **Promise** — Centered monumental words over an immersive world, supported by a serif promise and primary action.
2. **Social proof** — A bracketed introduction and monochrome partner marks.
3. **Capability chapters** — Several cinematic environments alternate centered proclamations with narrower narrative passages and resource actions.
4. **Community invitation** — A compact proclamation and three outlined social destinations.
5. **Utility ending** — Three-column navigation, bowl-shaped newsletter stage and enormous closing word.

**Transfer:** Borrow the cinematic chapter rhythm without reproducing the long scroll length or exact number of environments.

### Financial or commercial detail landing

1. **Promise** — Left-aligned monumental statement over a golden scene and a joined purchase action.
2. **Quantified explanation** — Light partner strip, allocation summary and two-column detail accordions.
3. **Access and proof** — Rounded provider carousel, numeric summary and thin neutral chart.
4. **Mechanism explanation** — Return to a dark atmospheric narrative with narrow serif passages.
5. **Trust and updates** — Three outlined verification entries and a four-column staggered social feed.
6. **Closing call** — Dark portal invitation with purchase action, then the shared sculptural footer.

**Transfer:** Use for a product with genuine metrics and distribution channels; separate financial facts from the visionary opening.

### Technical explanation and documentation gateway

1. **Orientation** — Rounded warm-white sheet with a fixed contents rail, compact condensed headline, serif summary and segmented square artwork.
2. **Mechanism** — Two-column monochrome diagram cards.
3. **Progress and resources** — Three roadmap panels, a second segmented scene and ruled technical product explanations.
4. **Objection handling** — Compact FAQ accordions, community link and restrained stat summaries.
5. **Closing call** — Full-width blue canyon invitation and the shared bowl-and-word ending.

**Transfer:** Use a readable 650px main column and keep cinematic imagery at major transitions rather than behind all technical prose.

### Integration or application directory landing

1. **Promise** — A left-aligned giant headline, narrow description and paired actions over a right-heavy golden scene.
2. **Discovery** — Centered proclamation, category controls and open four-column directory.
3. **Benefits** — Charcoal band repeats a smaller selection as application-oriented entries.
4. **Audience depth** — Wide serif-titled story accordion with text, quote and image.
5. **Closing call** — Blue atmospheric invitation, then three-column navigation, newsletter bowl and giant word.

**Transfer:** This is the default new marketing-page composition; replace the directory with a small set of product capabilities if needed while retaining the stage, ruled collection language and sculptural ending.

### Company narrative and human credibility

1. **Origin hook** — An immense centered milestone statement overlays a circular cinematic composition.
2. **History** — A second atmospheric chapter combines a proclamation with narrow dated prose.
3. **Human proof** — Warm paper and staggered four-column portrait cards.
4. **External proof** — Four light editorial cards with cinematic thumbnails.
5. **Closing call** — The shared blue canyon invitation and bowl-and-word footer.

**Transfer:** Use a true defining moment and real people; keep the circular art and staggered portrait treatment scoped to company storytelling.

## Writing

Visionary and declarative, with a touch of mythic rebellion. Short commands promise a change in the world, while longer serif passages explain mechanisms and establish confidence.

**Do not copy:** Do not reuse BitcoinOS or BOS names, logos, distinctive character artwork, network names as implied partners, proprietary product names, token figures, milestone numbers, investment claims or attributed quotations. Replace all with original assets and substantiated claims for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Headlines often command the reader directly; explanatory copy alternates product-led third person with 'we' and 'our'. Reader-facing benefits use 'you' sparingly.
- **Rhythm:** Headlines are short stacked proclamations; support ranges from one compact sentence to a narrowly set explanatory paragraph. Labels and actions stay terse. Technical sections use fuller causal explanations rather than poetic fragments.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct imperative with an ambitious destination or a brief invitation into a new era. | 4–8 words | “PLUG INTO THE MOTHERCHAIN”<br>“Be early to bitcoin again” |
| Chapter headline | A forceful verb and an abstract obstacle or transformation. | 3–5 words | “Reject the Silos”<br>“A NEW WORLD UNFOLDS” |
| Supporting line | Name the product's role, then explain what becomes possible. | 12–25 words for a lead; longer for mechanisms | “The unifying OS that deeply integrates Bitcoin with the internet.”<br>“Join an ecosystem of projects that complement and supercharge the Bitcoin network.” |
| Primary action | Verb-led invitation or direct resource destination. | 1–4 words | “Join the Revolution”<br>“Partner With Us”<br>“View Docs” |
| Technical heading | Name a mechanism or ask a direct practical question. | 3–9 words | “Rollups & True L2s”<br>“What is BOS and how does it work?” |

**Words and phrasing to use:** unlock; build; transform; unify; a new era; without compromise; possibility; proven; creation

**Avoid:** cute diminutives; overly chatty greetings; corporate synergy jargon; unexplained superlatives in factual paragraphs; emoji-led marketing copy

**Rules:**

- Let the headline carry ambition and the paragraph carry the mechanism.
- Use bracket labels as calm navigation metadata, not another promotional sentence.
- Make a bold claim only when the following paragraph or proof block can explain it.
- Use active verbs and contrast old limitations with a concrete new capability.
- Keep resource labels literal even when surrounding copy is mythic.

## Do's and Don'ts

### Do

- Keep the default canvas #101010 and display text #fffafa.
- Pair 128px/0.8 condensed capitals with tracked 16px/1.6 serif prose.
- Maintain a 1312px desktop content width with 64px sides and 12px collection gutters.
- Use 48px action cells with 8px corners and a separate adjoining arrow square.
- Separate open directory entries with 1px #272727 rules rather than elevated shells.
- Use 24px interior padding and 16px corners for light information cards.
- Keep an illuminated atmospheric scene, bracket labels and the monumental closing word in the new design.
- Reserve 88px–128px band padding for substantial changes of chapter.

### Don't

- Do not replace the literary serif paragraphs with a standard all-sans interface voice.
- Do not spread 128px display lines to a loose 1.2 line height; their compressed silhouette is essential.
- Do not introduce saturated brand-color buttons or colored feature-card fills; the UI stays neutral.
- Do not add drop shadows to 16px cards; tonal contrast and hairlines do the separation.
- Do not turn the 8px-corner action language into pill-shaped marketing buttons.
- Do not frame every illustration inside a browser window; scenes are environments, not UI demonstrations.
- Do not use full-color logo badges inside the otherwise monochrome ruled directory.
- Do not flatten the footer into a small legal strip; preserve its deep curve and oversized graphic word.

## Motion and responsive

### Motion

**Observed:**

- Declared button-cell transition: all .28s cubic-bezier(.455,.03,.515,.955).
- Declared directory-top transition: all .35s cubic-bezier(.455,.03,.515,.955). Footer-row borders use .35s cubic-bezier(.86,0,.07,1).
- Declared header-inner transition: all 1s cubic-bezier(.86,0,.07,1).
- Scenes use scroll-linked chapter changes and segmented wipes; a small repeating action strip accompanies the immersive narrative.

**Transfer:**

- Use the segmented mask as the visual vocabulary for scene changes; the static scene must still compose correctly at rest.
- Keep button label and arrow cells coordinated through the declared short transition rather than animating them as unrelated controls.

**Unknown:**

- Exact scene animation durations, scroll pinning implementation and trigger thresholds are not established.
- No demonstrated focus-visible treatment or complete menu-open interaction is available.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 799px, 800px, 1108px, 1120px, 1440px and 1720px; additional page-specific breakpoints exist.
- The desktop header is fixed at 64px and the primary container reaches 1312px.

**Transfer:**

- On narrow layouts, keep the image's luminous focal object visible while moving copy into its dark negative space; retain the heavy condensed block rather than fitting a desktop-width headline onto one line.
- Collapse four-column collections and story splits into a readable single track; move the technical contents rail into compact navigation.
- Keep the curved footer silhouette and full-width word artwork as the page narrows, scaling the artwork as one graphic.

**Unknown:**

- Mobile sizes, column counts, exact breakpoint behavior and touch-menu states were not demonstrated. Narrow-layout guidance is a transfer recommendation, not a measured implementation.
- No fluid typography formula is established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
