# Elvina Prasad — staggered typographic theatre

## Overview

An oversized grotesk-led style with the feeling of a personal creative manifesto rather than a conventional sales funnel. Black and chalk-white fields carry staggered words, fine rules and exposed arrow links, while vivid color arrives through product mockups and printed work. It suits design-led products, creative services and visual portfolios, combining very low-density presentation with more substantial editorial case studies.

### Essentials

- Words become the main object: 177.6px, weight 500 grotesk at 1.1 line height, split into staggered left–right–left lines rather than a centered headline block.
- The opening is a monochrome typographic stage: a 900px black field, small fixed corner navigation and a bottom-right scroll cue; the same words persist as a white-backed collage of rectangular product images moves through them. Use real product views or original specimen panels as the media fallback.
- Actions are labels with detached arrow medallions, not filled pills: uppercase 32px or 38.4px text beside a 76px circle, 1px outline and 32px arrow.
- Color belongs to the work, not the furniture: default sections remain black, white or #f7f7f7 throughout; saturated product imagery supplies concentrated color within hard rectangular frames. Solid purple or periwinkle headers belong only to individual case studies.
- Contrast weight inside monumental statements: linking phrases use weight 300 at the same 177.6px size as weight-500 key words; 27.2px support copy occupies the space left between the words.
- Treat proof as an asymmetric index, not a card dashboard: a 648px ruled list sits on the right beneath a staggered heading pair, with 38.4px uppercase titles and bare right arrows.
- Close with a direct human invitation: an 80px question with -0.05em tracking, a 38.4px uppercase arrow action, right-aligned navigation and a fine horizontal rule on an untextured full-width field.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text, border | Default opening, statement and closing fields; inverse text and rules on light sections. |
| Chalk | `#f7f7f7` | `--color-chalk` | background, text | Light editorial and index sections; primary monumental text on black. |
| Pure white | `#ffffff` | `--color-white` | background, text, border | Collage ground, body copy and arrow outlines on black. Metadata uses this hue at 60% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| campaign case-study openings | Project periwinkle | `#6666ff` | `--color-periwinkle` | background | Single flat opening field for a campaign case study. |
| application case-study openings | Project purple | `#a64ac9` | `--color-purple` | background | Single flat opening field for a colorful application case study. |
| case-study metadata and biography details | Muted metadata | `#999999` | `--color-muted` | text | Visible result of 60% white over black for secondary metadata; over colored headers it remains an alpha-white treatment rather than a fixed gray. |

## Typography

- **Neue Montreal** — All editorial text, display words, labels and navigation; regular and variable editions share one visual family. A clean, broad neo-grotesk whose open counters remain legible at very large sizes; thin connecting language contrasts with medium-weight nouns. If unavailable, use **Inter**. Use weights 300–500; preserve the spacious labels and untracked monumental words. Font stack: "Neue Montreal", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Neue Montreal | 500 | 177.6px | 1.1 | normal | Opening word sculpture and staggered major section heading pairs. |
| display-light | Neue Montreal | 300 | 177.6px | 1.1 | normal | Connecting phrases within the monumental statement. |
| closing-question | Neue Montreal | 500 | 80px | 1 | -0.05em | Human invitation at the start of the footer. |
| menu | Neue Montreal | 400 | 40px | 1 | 0.05em, uppercase | Fixed menu label in the top-right corner. |
| subtitle | Neue Montreal | 400 | 38.4px | 1 | 0.05em, uppercase | Project index titles, accordion labels and closing action. |
| action | Neue Montreal | 400 | 32px | 1 | 0.05em, uppercase | Text-arrow actions and footer navigation. |
| support | Neue Montreal | 300 | 27.2px | 1.4 | 0.05em | Compact support paragraph tucked between oversized statement words. |
| support-light-field | Neue Montreal | 400 | 27.2px | 1.4 | 0.05em | Short introduction beside a major light-field heading. |
| scroll | Neue Montreal | 300 | 22.4px | 1 | 0.05em, uppercase | Bottom-right opening scroll prompt. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study openings | case-title | Neue Montreal | 500 | 188.8px | 1.1 | normal | One short project name above descriptive and administrative metadata. |
| case-study endings | next-title | Neue Montreal | 400 | 168px | 1.1 | normal | Centered project name on a full-height next-item image. |
| case-study overviews and biography detail sections | ticker | Neue Montreal | 400 | 104px | 1 | 0.05em, uppercase | Repeated, edge-clipped chapter wording spanning beyond the viewport. |
| case studies | chapter | Neue Montreal | 300 | 72px | 1 | normal | Process and reflective closing section titles. |
| work galleries | gallery-title | Neue Montreal | 400 | 48px | 1 | 0.05em, uppercase | Title beneath a landscape project thumbnail. |
| case studies | subheading | Neue Montreal | 500 | 32px | 1.4 | 0.0375em | Short process subheads inside the reading column. |
| case-study openings | metadata-value | Neue Montreal | 300 | 30.4px | 1 | 0.05em, uppercase | Category and year values under small labels. |
| case studies and biography details | editorial-lead | Neue Montreal | 300 | 28.8px | 1.2 | 0.05em | Introductory paragraph above a ruled accordion. |
| case studies and biography sections | body | Neue Montreal | 300 | 24px | 1.3 | 0.05em | Editorial paragraphs and expanded detail panels. |
| case studies and biography details | metadata | Neue Montreal | 300 | 17.6px | 1 | 0.05em | Secondary category, year and next-item labels. |

**Notes:**

- Monumental display words keep normal tracking; do not apply the label spacing to them. Most labels and paragraphs use 0.05em, making the compact uppercase titles feel unusually open.
- The closing question is the exception: its -0.05em tracking and weight 500 create a dense, friendly line against the spacious action beneath it.
- Use the variable edition for navigation and uppercase utility titles when available; it does not introduce a second visual typeface.

## Layout

**Density:** Airy: words and images are separated by substantial full-width intervals, while text-led reading columns use close paragraph spacing.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Paragraph separation and process subhead margins. |
| 14.4px | Space below a case-study chapter heading. |
| 21px | Vertical index-row padding and arrow-circle inner padding. |
| 28px | Gap between monumental statement lines and stacked opening details. |
| 42px | Footer rule-to-bottom-row spacing and two-image gutter. |
| 45px | Gallery title-row vertical padding. |
| 70px | Space before accordion rows and beneath the footer's upper content. |
| 72px | Desktop section side padding. |
| 90px | Vertical padding of the light footer variant. |
| 180px | Opening and dark-footer vertical padding; gap after an editorial ticker. |
| 270px | Default editorial section and work-gallery vertical padding. |
| 450px | Vertical padding around the monumental manifesto. |

### Containers and grids

- **full-width-stage**: side padding 72px. At 1440px the principal stage has 1296px of inner width. Fields run edge to edge; fixed navigation uses separate 45px corner insets.
- **split-index**: 2 columns · gap 16px. Stagger heading words across the full width, then place a 648px list on the right, leaving the left side to a short support paragraph and action.
- **editorial-column** (only for case studies and biography details): max width 842px · side padding 72px. Right-aligned reading column beginning well past the center-left; preserve a broad empty left margin. Reflective conclusions move the same width to the left.
- **gallery-stagger** (only for work galleries): max width 827px. A single landscape work link occupies roughly two thirds of the content width; successive items alternate right and left rather than forming a simultaneous grid.
- **media-pair** (only for case-study media galleries): 2 columns · gap 42px. A 778px image beside a 476px image across the 1296px gallery width, followed by larger full-width work boards.

## Corner radius

| Element | Radius |
| --- | --- |
| arrow-medallion | 50% |

## Surfaces and depth

### Surfaces

#### Black stage · level 0

**Use:** Default opening, statement and closing canvas.

**CSS:** `background: #000000; color: #f7f7f7`

**Observed:** Flat and untextured; drama comes from scale and empty space, not elevation.

**Transfer:** Make this the default for a new landing page.

#### Chalk field · level 0

**Use:** Index and editorial reading sections.

**CSS:** `background: #f7f7f7; color: #000000`

**Observed:** A hard edge changes the entire page field; there is no inset rounded section container.

**Transfer:** Use as a full-width counterpoint to the black stage.

#### White collage field · level 0

**Use:** The scrolling image-and-word composition.

**CSS:** `background: #ffffff; mix-blend-mode: difference`

**Observed:** The overlaid field inverts the fixed black stage and creates locally inverted overlaps between words and colored imagery.

**Transfer:** Keep the text readable before, during and after image intersections; isolate the blending group from unrelated sections.

#### Colored case header · level 0

**Only for:** case-study openings

**Use:** A project-specific opening color field.

**CSS:** `background: #a64ac9; color: #f7f7f7`

**Observed:** Application work uses purple; campaign work uses periwinkle. The color belongs to the presented work, not the surrounding site chrome.

**Transfer:** Choose one project-derived hue for this page type, leaving subsequent reading sections monochrome.

#### Darkened next-image · level 1

**Only for:** case-study endings

**Use:** Scrim between a full-bleed project image and its centered link text.

**CSS:** `background: rgba(0, 0, 0, 0.68)`

**Observed:** The image remains recognizable but markedly subdued behind white text.

**Transfer:** Use an actual next-item image, not an empty black rectangle.

## Components

### Fixed menu

**Use:** Persistent navigation entry opposite a compact brand mark.

**CSS:** `position: fixed; top: 45px; right: 45px; mix-blend-mode: difference; color: #ffffff; overflow: hidden`

**Text style:** `menu` — Neue Montreal 400 · 40px/1 · tracking 0.05em · uppercase

**Observed:** A text-only control at the top-right; the brand mark sits in the opposite corner. Both change apparent color as page fields pass underneath.

**Transfer:** Use a compact original mark and the same isolated text control; keep the opening free of a full navigation bar.

### Arrow circle

**Use:** Shared directional action endcap and scroll affordance.

**CSS:** `width: 76px; height: 76px; padding: 21px; border: 1px solid #ffffff; border-radius: 50%; box-sizing: border-box`

**Observed:** A centered 32px arrow points right for a link and down for scrolling. On light sections the outline and arrow become black.

**Transfer:** Reuse the same circle construction across actions instead of introducing several button silhouettes.

### Text arrow action

**Use:** Editorial navigation and conversion actions.

**CSS:** `display: flex; align-items: center; max-width: 100%; color: #f7f7f7`

**Text style:** `action` — Neue Montreal 400 · 32px/1 · tracking 0.05em · uppercase

**Observed:** Unboxed uppercase label followed by Arrow circle. A 32px right margin on the ordinary label separates it from the endcap; the closing variant uses subtitle text and a closer 14px separation.

**Transfer:** Keep the text outside the circle. Use a short human verb phrase rather than a generic filled primary button.

### Scroll cue

**Use:** Indicate that the opening continues into a visual story.

**CSS:** `display: flex; align-items: center; position: absolute; color: #f7f7f7`

**Text style:** `scroll` — Neue Montreal 300 · 22.4px/1 · tracking 0.05em · uppercase

**Observed:** Anchored to the lower right of the opening stage; label precedes Arrow circle with a downward arrow. On the 900px opening it sits about 45px above the bottom.

**Transfer:** Retain the directional cue even when the subsequent visual story uses static images.

### Project index row

**Use:** Compact linked proof or offering index on a light field.

**CSS:** `display: flex; justify-content: space-between; padding: 21px 0px; color: #000000; border-bottom: 1px solid #000000`

**Text style:** `subtitle` — Neue Montreal 400 · 38.4px/1 · tracking 0.05em · uppercase

**Observed:** A title on the left and a bare right arrow at the far edge, not a circle. Rows span 648px and sit under a top hairline as one continuous index.

**Transfer:** Use short product, example or capability names; keep detail out of the row.

### Footer links

**Use:** Secondary navigation beside the closing invitation.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-end; color: #ffffff`

**Text style:** `action` — Neue Montreal 400 · 32px/1 · tracking 0.05em · uppercase

**Observed:** Four short navigation labels stack flush right opposite the question and contact action. The light footer switches the text to black.

**Transfer:** Keep the list small and directional rather than expanding into many columns.

### Accordion row

**Only for:** case-study overviews and biography details

**Use:** Progressive disclosure of background, credentials and supporting detail.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 21px 0px; color: #f7f7f7; border-top: 1px solid #ffffff`

**Text style:** `subtitle` — Neue Montreal 400 · 38.4px/1 · tracking 0.05em · uppercase

**Observed:** A full-width uppercase heading and a diagonal up-right arrow frame each row in the right-aligned reading column. Closed rows are about 112px tall. Expanded content uses body paragraphs beneath the heading rather than an inset card. Biography details include experience entries, recognition links with bullet-separated names and years, and compact expertise lists.

**Transfer:** Use this structure for explanatory detail or fit questions; preserve the open black ground.

### Gallery link

**Only for:** work galleries

**Use:** Image-led discovery of individual projects or use cases.

**CSS:** `display: flex; flex-direction: column; max-width: 827px; color: #f7f7f7`

**Text style:** `gallery-title` — Neue Montreal 400 · 48px/1 · tracking 0.05em · uppercase

**Observed:** A sharp landscape image about 827px by 461px, then a title and bare right arrow in a row with 45px vertical padding, finishing with a fine rule. Links alternate left and right on the black field.

**Transfer:** Show a composed real artifact rather than an icon or a category illustration.

### Next feature

**Only for:** case-study endings

**Use:** Continue the story into another related project.

**CSS:** `display: flex; position: relative; flex-direction: column; justify-content: center; align-items: center; height: 900px; overflow: hidden; color: #ffffff`

**Text style:** `next-title` — Neue Montreal 400 · 168px/1.1

**Observed:** Full-bleed imagery under Darkened next-image, a small next-item label and a very large centered title; the entire stage is a link.

**Transfer:** Use a recognizable preview of the destination. Follow it with the shared invitation footer.

## Imagery and graphics

### Floating artifact collage

**Use:** Signature visual continuation of the opening typography.

**Observed:** Unequal portrait rectangles containing phone mockups, print pieces and identity work float through broad white space. Images occupy different vertical levels and cross the giant words; the composite locally inverts at overlaps. There are no frames, corner rounding or interface card shadows around the images.

**Transfer:** Use several original product views, customer artifacts or designed specimen panels. When no photography exists, compose two or three high-quality interface or typographic specimens on their own colored grounds.

**Build:** Create an isolated scrolling wrapper over a fixed 900px Black stage. Place 3–4 sharp rectangular images at varied vertical offsets, using two approximate width classes of 335px and 422px with portrait proportions. Offset them between left edge, center and right edge rather than equal columns. Apply the White collage field blending treatment to the scrolling group so the stationary words invert as the white ground passes. Keep imagery behind or locally intersecting the readable words, not inside masked letters.

### Product mockup scenes

**Use:** Colorful proof within the collage, gallery links and case-study media.

**Observed:** Black or white phone hardware presents crisp bright interfaces on pale gray or lavender grounds; scenes range from three front-facing phones with one raised central device to diagonal arrays of phones with soft physical shadows. Flat screen grids are also shown on black with generous gutters.

**Transfer:** Place actual screens in restrained device frames or use crisp flat interface panels on a pale neutral ground. Keep shadows inside the artwork, not on the surrounding page sections.

### Printed artifact still lifes

**Only for:** brand and campaign case studies

**Use:** Hero-scale evidence and gallery thumbnails.

**Observed:** Posters and booklets are arranged diagonally on muted green or gray surfaces. Directional lighting and soft leafy shadows add materiality; the printed artwork itself is saturated yellow, pink, violet or turquoise. Other boards show flat poster pairs or paired social panels surrounded by black gutters.

**Transfer:** Use original packaging, documents or campaign pieces. Pair a believable material scene with flatter inspection views so the work can be read as well as admired.

### Process boards

**Only for:** case studies

**Use:** Explain the thinking between the opening proof and final gallery.

**Observed:** Research photographs, personas, journey maps and grayscale wireframes are rectangular images aligned with the 842px reading column. Later outcome boards expand to the 1296px width and organize phone sequences with small captions internal to the artwork.

**Transfer:** Show legible original diagrams and intermediate work; their typography and colors belong to the artifact rather than the marketing type system.

### Environmental portrait

**Only for:** biography pages

**Use:** Human context beside a personal narrative.

**Observed:** One tall natural-color portrait, about 599px by 800px, sits on the right of a chalk field. The subject is framed within an architectural doorway in cool dark clothing; the left column carries two paragraphs. There is no cutout, circle mask or decorative frame.

**Transfer:** Use an authentic portrait in an everyday built environment with natural light and restrained color; match the vertical framing and rectangular edge.

### Icons

**Observed:** The interface relies almost entirely on simple arrows: straight right, straight down and diagonal up-right. Small arrows are roughly 32px, with the directional silhouette rendered as a solid SVG; circles are independent 1px outlines.

**Transfer:** Choose consistent plain arrows rather than a varied pictogram library. Use bare arrows on ruled rows and circled arrows for the more deliberate action.

## Section recipes

How recurring sections are built.

### First screen: Staggered word stage

**Observed:** The first 900px are a black typographic stage with a compact mark at top-left and Fixed menu at top-right, each inset 45px. Three oversized words form a left–right–left composition across most of the 1296px inner width: the middle line is anchored toward the right while the last returns to the left. Display text is 177.6px/1.1, weight 500, in chalk; overlapping line boxes make the phrase feel like a single word sculpture. Broad black space surrounds it, with Scroll cue at the lower right. There is no support paragraph, media object or conversion button above the first fold. Below it, Floating artifact collage moves across the persistent words, inverting the field to white before the next black section arrives.

**Transfer:** Write a short three-part product promise and shape the words into an equally assertive staggered composition. Build the same subsequent collage from original product specimens when photography is unavailable. Biography openings instead use two large left-aligned lines on black; gallery openings repeat a single display word beyond both edges on chalk. Case studies use a 720px colored opening with a left-aligned case-title, short description, category/year pairs and the scroll cue, allowing the first media scene to appear at the bottom of the first screen.

**Avoid:** Do not center a conventional headline over a subtitle and pair of filled buttons, and do not put a stock hero photo behind the opening words.

**Text style:** `display` — Neue Montreal 500 · 177.6px/1.1

### Interlocking manifesto

**Observed:** Black stage with 450px vertical padding. Display-light connecting phrases and display key words alternate across multiple rows. Support copy occupies a narrow left pocket beside a stronger key word, while Text arrow action balances another word on the right.

**Transfer:** Use a short contrast between method and outcome, retaining the weight change and pocket of prose rather than turning each phrase into a separate feature card.

**Text style:** `display-light` — Neue Montreal 300 · 177.6px/1.1

### Split proof index

**Observed:** Chalk field with 270px vertical and 72px horizontal padding. Two display words sit on opposite sides and adjacent levels. Support-light-field text and Text arrow action fill the left side; Project index row links begin under the right heading.

**Transfer:** Index selected outcomes, examples or offerings without making a thumbnail grid.

**Text style:** `display` — Neue Montreal 500 · 177.6px/1.1

### Human invitation footer

**Observed:** Black stage is the landing default: 180px vertical and 72px horizontal padding, 674px total height. A closing-question on the left sits over a subtitle-sized Text arrow action; Footer links stack on the right. Below the upper content, a 1px horizontal rule and tiny left/right notes complete the field. The alternate editorial and gallery footer is a 494px chalk field with 90px vertical padding and black content, preserving the same internal arrangement.

**Transfer:** Ask a simple question that opens a conversation, then provide a direct next action. Preserve the opposing navigation block and the fine-rule ending rather than adding a newsletter form.

**Text style:** `closing-question` — Neue Montreal 500 · 80px/1 · tracking -0.05em

### Editorial ticker and disclosure

**Only for:** case-study overviews and biography details

**Observed:** Black stage, 270px top padding, an oversized repeated ticker clipped at both viewport edges, followed after 180px by editorial-lead copy in the 842px right column. Accordion row begins after another 70px. Biography content uses the same composition for credentials and tools.

**Transfer:** Repeat one short chapter phrase as a typographic band, then put meaningful detail in the offset reading column. Use disclosures only for content that benefits from progressive depth.

**Text style:** `ticker` — Neue Montreal 400 · 104px/1 · tracking 0.05em · uppercase

### Process reading chapter

**Only for:** case studies

**Observed:** Chalk field with 270px vertical and 72px side padding. A right-aligned 842px column combines chapter, subheading and body recipes with process images at the same width. Section title-to-copy gap is 14.4px; paragraph and subhead separations are generally 10px.

**Transfer:** Explain choices with actual process artifacts, allowing longer prose here than on the landing page.

**Text style:** `chapter` — Neue Montreal 300 · 72px/1

### Alternating artifact gallery

**Only for:** work galleries

**Observed:** A 720px chalk opening repeats a display word horizontally beyond the viewport, then black sections present one Gallery link at a time, alternating sides. Each gallery interval uses 270px vertical padding; the large empty opposite side is part of the composition.

**Transfer:** Use for a browse page with a small curated collection, not for a dense searchable catalog.

**Text style:** `gallery-title` — Neue Montreal 400 · 48px/1 · tracking 0.05em · uppercase

### Media outcome and reflection

**Only for:** case studies

**Observed:** Full-bleed mockup scenes break out of the reading width. A black gallery follows with Media pair layouts, full-width 1296px boards and screen arrangements. A left-aligned 842px conclusion uses chapter and body before the Next feature.

**Transfer:** Separate finished outcomes from process with a change in scale and field, then close the case with a frank reflection and a related destination.

**Text style:** `chapter` — Neue Montreal 300 · 72px/1

## Page flow

**Storyline:** Typographic promise → visual artifacts → human method or context → selected proof or deeper explanation → personal invitation.

### A visual, personality-led marketing landing page

1. **Promise** — Monumental staggered words on black.
2. **Product demonstration** — The words persist as a bright artifact collage scrolls across them.
3. **Method** — Interlocking light and medium-weight statements with a small paragraph.
4. **Selected proof** — A split light-field heading and ruled link index.
5. **Closing call** — Dark human invitation footer.

**Transfer:** Use an original product promise, artifact story and short method statement; keep the same typographic energy and generous pacing.

### An application case study that makes the process inspectable

1. **Identification** — Purple project header with title, short description and metadata, then a large phone mockup.
2. **Context** — Repeated chapter band and right-column overview with three disclosure rows.
3. **Process** — Light reading chapter with research photographs, personas, journey map, wireframes, testing and outcome explanation.
4. **Product demonstration** — Large device scenes and screen-sequence boards on black.
5. **Reflection** — Left-column conclusion followed by a full-height related-project link.
6. **Closing call** — Chalk invitation footer.

**Transfer:** Explain the product's decisions with original evidence of work, not just a sequence of polished final screens.

### A campaign case study emphasizing finished visual output

1. **Identification** — Periwinkle project header followed by a large printed-artifact scene.
2. **Context** — Black overview with clipped chapter band, introductory copy and disclosure rows.
3. **Process** — Concise light-field prose chapter explaining the two major output formats.
4. **Product demonstration** — Full-width device montage, paired posters and large campaign boards on black.
5. **Reflection** — Personal conclusion followed by a darkened next-project image stage.
6. **Closing call** — Chalk invitation footer.

**Transfer:** Use the longer gallery when visual deliverables carry the argument; retain the context and reflective ending.

### A human introduction with credentials available at greater depth

1. **Identity** — Two large lines combining professional and personal descriptors on black.
2. **Human context** — Light two-column prose and environmental portrait.
3. **Fit and credibility** — Repeated chapter band, right-column introduction and accordions for experience, recognition and expertise.
4. **Closing call** — Chalk invitation footer.

**Transfer:** Balance professional purpose with one personal detail, then let readers inspect credentials without crowding the initial narrative.

### A curated visual browsing page

1. **Orientation** — Repeated oversized title clipped on a chalk opening, with scroll cue.
2. **Selected proof** — Five image-led links alternate right and left on a continuous black ground.
3. **Closing call** — Chalk invitation footer.

**Transfer:** Show one strong artifact at a time and make the whole thumbnail/title unit a destination.

## Writing

Warm, personal and candid, with creative confidence expressed through simple statements rather than grand claims. Reflective passages explain intent, choices and what could improve.

**Do not copy:** Do not reuse the personal name, monogram, project names, product artwork, university or employer names, awards, dates, recognition claims, personal biography, land acknowledgement or other source-specific assertions. Write original product-specific claims and invitation copy. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The creator speaks as I and me; team case studies shift naturally to we and our. The reader is addressed directly in invitations and fit-oriented explanation.
- **Rhythm:** Opening phrases are often one to three words per visual line. Short uppercase actions interrupt expansive display language; editorial sections use complete, explanatory sentences and occasional conversational asides.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact human-centered assertion divided into three substantial words. | 3–5 words | “Human centred designs” |
| Method statement | Parallel phrases with a connecting verb and emphatic final noun. | 3–4 words per phrase | “Motivated by empathy.”<br>“Devoted to creativity.” |
| Supporting line | A first-person reason for the work or a brief introduction to selected proof. | One sentence | “Some opportunities and projects that I’m proud of!” |
| Editorial chapter | Plain labels that name the reader's next question. | 1–4 words | “Background Information”<br>“Concluding thoughts” |
| Action | A friendly invitation to learn more or start a conversation. | 2–5 words | “Get to know me”<br>“Make magic with me” |
| Closing question | A short, low-pressure question rather than a sales command. | 3–5 words | “Have an idea?” |

**Words and phrasing to use:** people; create; explore; opportunity; proud; questions; learn; together

**Avoid:** revolutionary; disruptive; world-class; 10x; dominate; limited-time offer

**Rules:**

- Let the short headline express a point of view; reserve explanations for the quieter paragraph pockets.
- Use parallel syntax when two monumental phrases share a section.
- Describe process with specific actions and reasons, including limitations and possible improvements.
- Keep navigation labels literal and short; let warmth live in the invitation rather than clever menu terminology.

## Do's and Don'ts

### Do

- Keep the first stage black and 900px tall at the desktop reference size, with the three-part display sculpture as its main object.
- Preserve the 300-versus-500 weight contrast at the same 177.6px scale in statement sections.
- Use 72px side gutters for ordinary sections and 45px corner insets for fixed navigation.
- Keep action circles 76px with a 1px outline and a centered 32px arrow.
- Place the compact proof index on the right at 648px rather than filling the entire section with rows.
- Use full-width field changes and 270px editorial padding to create distinct reading chapters.
- Keep artifact images sharp-edged and their supporting color contained within the work.
- End with the 80px question, uppercase action and opposing navigation block.

### Don't

- Do not turn the 38.4px uppercase index titles into small 16px UI labels.
- Do not apply the 0.05em utility tracking to the 177.6px display words.
- Do not use weight 700 for emphatic words; the contrast is built with weights 300 and 500.
- Do not round project images or add drop shadows to the marketing sections; physical shadows belong inside the mockup artwork.
- Do not spread purple and periwinkle across ordinary navigation, row fills and footer chrome.
- Do not replace the staggered gallery with a uniform three-column tile wall.
- Do not surround each disclosure row with a raised or rounded card; use continuous hairlines on the open field.
- Do not scale all headings down to the 72px chapter style; that recipe belongs to long-form case-study reading, not the opening.

## Motion and responsive

### Motion

**Observed:**

- The opening headline remains fixed as the image collage scrolls across it; color inversion accompanies the transition between black and white fields.
- Text elements declare transitions of font-variation-settings 0.5s and font-size 0.8s ease-in-out.
- Repeated chapter wording is clipped beyond viewport edges; transformed text positions are present.

**Transfer:**

- Preserve the stationary-word/moving-artifact relationship as the distinctive scroll behavior. A reduced-motion version can retain the staggered word composition and place the collage after it without motion.
- Keep type-based emphasis rather than adding animated background ornaments.

**Unknown:**

- Exact scroll interpolation, repeating-band speed and trigger timing are not established.
- No specific hover, focus-visible or active visual changes are established for the controls; declared type transitions do not establish their target values.
- The opened-menu composition is not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 479/480px, 767/768px and 991/992px for the editorial, biography and gallery page types.

**Transfer:**

- On narrow screens preserve the word-by-word stagger and relative alignment, reducing type to fit the longest word rather than forcing desktop dimensions.
- Collapse the offset reading column to the available content width; retain the contrast between monumental words and compact prose.
- Stack footer invitation and navigation while retaining their distinct alignment; keep arrow medallions visually separate from labels.

**Unknown:**

- Mobile type sizes, side gutters, gallery alternation and exact breakpoint-specific layout rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
