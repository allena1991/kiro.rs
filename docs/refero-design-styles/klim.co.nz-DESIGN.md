# Klim — specimen as spectacle

## Overview

An uncompromising editorial style that treats a product like a cultural object: monumental grotesk lettering, tiny utilitarian controls, and immersive material imagery. Burnt orange and black form the default product world, while monochrome galleries and company stories live on black. It suits craft-led tools, design products, publishing and expressive launches, alternating dense demonstrations with unusually long stretches of open space.

### Essentials

- The product gets the room, not a sales headline: a 48px utility header sits above an almost screen-filling, tightly framed material scene; explanatory copy waits below the first 900px.
- Lettering becomes an exhibit: include a monumental black name or word composition on orange, with a two-line artwork footprint of 1050px × 529px at 1440px; use live grotesk lettering when bespoke artwork is unavailable.
- Controls behave like small labels attached to an exhibition: 16px regular sans, 28px high, 8px horizontal padding and 2px corners; outlined actions rise only to 36px.
- Color is an environment, not a highlight pen: #d33c03 covers the default product page through its footer, with black lettering and darker orange controls. Black-canvas editorial and gallery variants use white text instead.
- Proof is a tightly packed image index: four 343px columns across a 1400px content area, 10px gutters, 2px media corners and 16px captions immediately beneath; use real applications or carefully staged outputs rather than feature icons.
- A long breath precedes the colophon: 450px top padding leads into a distinctive typographic signature, a compact newsletter row and ruled directory columns. Retain the signature-and-directory closing device even for a short landing page.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Burnt orange canvas | `#d33c03` | `--color-canvas` | background, surface, action | Default product environment, including header and footer. |
| Recessed orange | `#bb3502` | `--color-control` | surface, border | Input fills, demonstration controls and media backing on the orange canvas. |
| Orange hairline | `#742101` | `--color-rule` | border, text | Fine dividers and technical secondary labels on orange. |
| Action outline | `#681d01` | `--color-outline` | border, text | Outlined actions and subdued product metadata. |
| Orange directory ink | `#4b1501` | `--color-muted` | text, link | Footer directory links and small-print text on orange. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Purchase red | `#e4001c` | `--color-purchase` | action, surface | A small purchase control in the product utility header, not a section fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, background, action | Primary lettering on orange; canvas for editorial and gallery variants. |
| White | `#ffffff` | `--color-white` | text, action | Purchase text; principal text on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| black-canvas editorial and gallery pages | Charcoal media backing | `#1c1c1c` | `--color-dark-surface` | surface, border | Media backing and form fields on black. |
| black-canvas editorial and company pages | Dark hairline | `#383838` | `--color-dark-rule` | border | Table rows and footer directory separators. |
| black-canvas editorial and gallery pages | Gallery secondary gray | `#555555` | `--color-caption-muted` | text, border | Secondary image caption details and outlined newsletter actions. |
| black-canvas editorial and company pages | Directory gray | `#8d8d8d` | `--color-directory-gray` | text, border, link | Footer links and stronger table category rules. |
| company pages | Table detail gray | `#aaaaaa` | `--color-detail-gray` | text | Descriptions in structured affiliation and proof tables. |

## Typography

- **SOEHNE** — All navigation, editorial prose, captions, section titles and directory text. Matter-of-fact neo-grotesk, compact and highly legible, with unshowy regular text and firm bold titles. If unavailable, use **Inter**. Use 400 and 700; preserve the compact headline line heights. Font stack: "SOEHNE", "Inter", -apple-system, system-ui, Helvetica, Arial, sans-serif.
- **k-die-grotesk-vf** — Monumental product lettering and expressive specimen words. A Helvetica-lineage variable grotesk whose weight and italic range provide the spectacle rather than decorative effects. If unavailable, use **Roboto Flex**. Tune width to fill the line; use its weight range for product exhibitions. Font stack: "k-die-grotesk-vf", "Roboto Flex", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | k-die-grotesk-vf | 400 | 280px | 1 | normal, features "calt", "ss01" | Edge-to-edge exhibition words. For a new product name, fit the lettering to its available width rather than forcing the original character count. |
| section-heading | SOEHNE | 700 | 24px | 1.25 | normal | Small, direct product chapter titles, often placed in a left-hand rail. |
| intro | SOEHNE | 400 | 24px | 1.3333 | normal | Product rationale paragraphs in a narrow reading column. |
| body | SOEHNE | 400 | 16px | 1.5 | normal | Utility links, actions, prose and footer directory text. |
| caption | SOEHNE | 400 | 16px | 1.3333 | normal | Tightly attached image captions, with project title followed inline by subdued descriptive metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| gallery index pages | gallery-title | SOEHNE | 700 | 100px | 0.98 | -0.02em | One-line gallery opening title after a deep upper pause. |
| company pages | statement | SOEHNE | 400 | 40px | 0.98 | normal | Opening company proposition, set as a compact multiline statement. |
| black-canvas editorial and company pages | editorial-heading | SOEHNE | 700 | 36px | 0.98 | normal | Editorial section headings and people names. |
| company pages | profile-role | SOEHNE | 400 | 36px | 1.3333 | normal | Role line immediately after a bold person or collaborator name. |

**Notes:**

- Regular 16px utility text remains deliberately small beside the enormous display material. Do not scale the navigation up to match the spectacle.
- Most lettering has normal tracking. The gallery index title alone tightens to -0.02em.
- The product name is also presented as two-line vector lettering in a 1050px × 529px footprint; treat that block as typographic artwork rather than ordinary introductory copy.
- Weight variation is part of a product exhibition, not a requirement to alternate weights in every editorial heading.

## Layout

**Density:** Airy at the section scale and compact at the component scale: a sparse exhibition shell surrounds tightly set controls, captions and directories.

### Spacing

| Value | Use |
| --- | --- |
| 5px | Adjacent utility controls and the name-to-role pairing. |
| 8px | Horizontal action padding and small control internals. |
| 10px | Desktop grid gutters and adjacent outlined actions. |
| 20px | Page side inset and footer bottom padding. |
| 20.6px | Separation before an action row or between profile text groups. |
| 34.3px | Section heading-to-content gap and portrait-to-name gap. |
| 68.6px | Product chapter top padding. |
| 137.1px | Deep internal breaks, profile rows and separation before technical disclosure lists. |
| 450px | Major exhibition pauses and the top of the closing colophon. |

### Containers and grids

- **full-width framework**: 12 columns · gap 10px · side padding 20px. Fluid desktop framework, 1400px usable width at a 1440px viewport; no fixed maximum-width container.
- **reading column**: gap 10px. Chapter label occupies the first two framework columns; intro begins in the third and spans six columns, 695px wide at desktop. Disclosure rows can expand to eight columns, 930px wide.
- **proof grid**: 4 columns · gap 10px · side padding 20px. 343px single-column media at desktop, with occasional two-column 695px images. Respect differing image aspect ratios rather than equal-height tiles.
- **people grid** (only for company pages): 2 columns · gap 128px. Two 460px biography columns, offset inward from the left section label rail. Portraits are 343px wide and descriptions remain narrower than the overall framework.

## Corner radius

| Element | Radius |
| --- | --- |
| controls and media | 2px |

## Surfaces and depth

### Surfaces

#### Orange canvas · level 0

**Use:** Default product landing-page environment.

**CSS:** `background: #d33c03; color: #000000`

**Observed:** The color carries continuously through narrative, demonstrations, proof and closing directory.

**Transfer:** Let one emphatic flat color unify the page instead of alternating a different backdrop for every chapter.

#### Recessed orange · level 1

**Use:** Controls and media backing on the product canvas.

**CSS:** `background: #bb3502; border-radius: 2px; box-shadow: none`

**Observed:** A darker shade creates separation without depth or gloss.

**Transfer:** Use tonal recesses only where controls or imagery need an edge.

#### Black editorial canvas · level 0

**Only for:** editorial, company and gallery pages

**Use:** The alternate reading and image-index environment.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Media, white text and thin gray rules sit directly on black.

**Transfer:** Keep this as a complete scoped theme rather than inserting arbitrary dark cards into the orange system.

#### Charcoal backing · level 1

**Only for:** black-canvas editorial and gallery pages

**Use:** Backing for imagery and text inputs.

**CSS:** `background: #1c1c1c; border-radius: 2px; box-shadow: none`

**Observed:** Mostly concealed by the image, with no raised-card treatment.

**Transfer:** Use it as backing, not as a padded dashboard card.

## Components

### Utility navigation

**Use:** Persistent orientation and access to the product's key actions.

**CSS:** `position: sticky; top: 0px; height: 48px; padding: 10px 20px; z-index: 5`

**Text style:** `body` — SOEHNE 400 · 16px/1.5

**Observed:** Brand, catalogue and product breadcrumb sit left; section selector, theme control, trial/download, purchase and hamburger sit right. Small controls float on the current canvas rather than in a heavy separate masthead.

**Transfer:** Use a short breadcrumb and only the relevant utility controls; retain the left/right balance.

### Label link

**Use:** Compact navigation, chapter jumps and see-more actions.

**CSS:** `display: inline-flex; align-items: center; height: 28px; padding: 0px 8px; background: #d33c03; color: #000000; border-radius: 2px`

**Text style:** `body` — SOEHNE 400 · 16px/1.5

**Observed:** Usually blends into the page; an arrow may follow the label. The black theme uses black backing and white text.

**States:** Declared: hover swaps foreground and background through theme variables; active uses the same inversion. Focus-visible treatment is unknown.

### Outline action

**Use:** Downloads, secondary conversion and newsletter submission.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 36px; padding: 0px 8px; color: #000000; border: 1px solid #681d01; border-radius: 2px`

**Text style:** `body` — SOEHNE 400 · 16px/1.5

**Observed:** Text is centered, with a small arrow for resource links; adjacent resource actions share a row. Newsletter submission uses a 225px-wide version.

**States:** Declared: hover swaps foreground and background through theme variables; active uses the same inversion. Focus-visible treatment is unknown.

### Purchase label

**Use:** Primary commercial action within the utility bar.

**CSS:** `display: inline-flex; align-items: center; height: 28px; padding: 0px 8px; background: #e4001c; color: #ffffff; border-radius: 2px`

**Text style:** `body` — SOEHNE 400 · 16px/1.5

**Observed:** The only bright red control is kept very small and sits next to the download action, not in a giant conversion panel.

### Proof media

**Use:** Application examples and editorial image links.

**CSS:** `display: block; filter: grayscale(1); opacity: 0.8; object-fit: cover; border-radius: 2px`

**Observed:** Images carry nearly all the visual information; no padded text container encloses them. On orange, monochrome images read as warm brown-tinted proof; on black they read as muted gray.

**Transfer:** Show real outputs, packaging, documents, installations or product use. Keep useful original aspect ratios.

### Proof caption

**Use:** Identification directly below proof imagery.

**CSS:** `margin-top: 2px; margin-bottom: 4px; color: #000000`

**Text style:** `caption` — SOEHNE 400 · 16px/1.3333

**Observed:** Title comes first, followed by a compact enclosed media count and a subdued product/category description inline. On black, title is white and the description is gray.

**Transfer:** Replace the category with the product attribute actually demonstrated; keep captions factual.

### Email field

**Use:** Compact closing newsletter form.

**CSS:** `width: 225px; height: 36px; padding: 0px 8px; background: #bb3502; border: 1px solid #bb3502; border-radius: 2px`

**Observed:** An input and Outline action occupy equal-width adjacent columns; a short invitation sits in the preceding column.

### Directory link

**Use:** Dense grouped footer navigation.

**CSS:** `color: #4b1501`

**Text style:** `body` — SOEHNE 400 · 16px/1.5

**Observed:** Links run in 24px rows below thin ruled category headings. Black-theme directory links use gray rather than white.

**States:** Declared: hover and active change text to the theme hover color. Focus-visible treatment is unknown.

### Colophon footer

**Use:** Distinctive final signature, newsletter invitation and navigational directory.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); column-gap: 10px; padding: 450px 20px 20px 20px; background: #d33c03`

**Observed:** A 578px × 60px expressive blackletter signature balances the compact newsletter row. A 137.1px break introduces directory headings: a wide three-column product list and three narrower groups. Back-to-top, copyright, build note and social symbols align at the foot.

**Transfer:** Create an original typographic signature or carefully drawn wordmark with a visibly different texture from the utility sans; retain the asymmetry and compact directory.

## Imagery and graphics

### Material product theatre

**Use:** The dominant opening scene and campaign-scale showcases.

**Observed:** A front-facing stack of perforated orange and black plastic crates fills the center of a pale gray studio field. The subject is tightly clipped above and below, occupying about half the scene width; soft physical highlights reveal molded ribs, lattice and openings. A thin orange frame surrounds the scene, contrasting neutral photography with the continuous colored page.

**Transfer:** Stage a meaningful physical object, output or structural analogy with tactile detail, restrained studio lighting and a neutral background. For an intangible product, make a simple stack or assembly of representative output sheets or panels rather than a generic laptop mockup.

**Build:** Use a centered, high-resolution object photograph or simple 3D assembly on a flat pale-gray image background. Keep front-facing perspective, black and orange material accents, and broad empty lateral margins; cover the media box so the object's vertical ends continue outside the frame. Place the scene inside a 20px orange inset with no decorative shadow.

### Monumental name composition

**Use:** A signature typographic exhibit that must appear in the page's visual story.

**Observed:** Two massive black lines of neo-grotesk lettering sit flush left on orange, roughly three quarters of the page width, with tightly stacked lines and a small contrasting emblem near the short upper line.

**Transfer:** Turn the new product's name or a short defining phrase into an equally forceful word composition; a live-type version is the minimum equivalent when custom lettering is unavailable.

**Build:** Set an SVG viewBox of 1050 by 529 or a proportional live-type block. Stack two left-aligned lines of bold black grotesk lettering, fit each line to its intended width, reduce the line gap almost to touching, and leave open orange space on the right. A small original seal can be drawn with a thin circular outline and simple internal mark; do not add gradients or extruded lettering.

### Annotated detail plates

**Use:** Craft and capability demonstration chapters.

**Observed:** Black isolated letterforms occupy a four-column orange field. Fine pale arrows, outlines and alignment marks point at distinctive construction details; the annotations remain much quieter than the subjects.

**Transfer:** Use enlarged product details, output fragments or simple diagrams with thin dimension-like annotations. Keep the subject legible without explanatory cards.

**Build:** Create equal-width SVG plates around 343px × 349px, transparent on orange. Center one black silhouette or detail per plate, overlay 1px pale annotation lines with tiny arrowheads or contour outlines, and keep labels outside the main silhouette. Use the underlying page as the plate background.

### Application photography

**Use:** Proof galleries and editorial cards.

**Observed:** Books, posters, signage, packaging and interfaces appear in their real environments or in restrained tabletop compositions. Monochrome treatment and reduced opacity unify diverse sources; gutters stay narrow and photos outweigh their captions.

**Transfer:** Use actual customer outputs or staged equivalents under natural or soft studio light. Preserve the variety of closeups, full objects and environmental views.

### People and working space

**Only for:** company pages

**Use:** Opening cultural scene and biographies.

**Observed:** A 930px-wide monochrome photograph shows an informal meeting in a book-lined workspace. Larger team portraits use dark studio backgrounds blending into the page; smaller contributor portraits use simple square frames and varied original backdrops.

**Transfer:** Use documentary working-space photography and direct, unembellished portraits. Avoid uniformly cheerful stock headshots and colored avatar discs.

### Icons

**Observed:** Tiny monochrome arrow, menu, theme, download and select glyphs accompany 16px text. Media counts read as enclosed numerals. The many larger letter symbols belong to the product demonstration, not to a general icon library.

**Transfer:** Choose simple text-scale glyphs or restrained SVG equivalents in the current foreground color; let arrows indicate direction rather than introducing colorful feature illustrations.

## Section recipes

How recurring sections are built.

### First screen: Material stage opening

**Observed:** The first 900px contains a 48px orange Utility navigation and a dominant framed product scene beneath it. Behind everything is Orange canvas; the next layer is a pale neutral studio field inset 20px from the page edges; the central orange-and-black material object is clipped at both ends and fills roughly half the image width. Navigation supplies the product name and the compact download and Purchase label actions. There is no supporting paragraph or freestanding headline over the object. The monumental two-line product name sits below the first screen, after a 270px pause; it spans 1050px within the 1400px framework.

**Transfer:** Give a different product a tactile, immediately recognizable visual analogy rather than leading with a template slogan. Use Material product theatre even if the subject must be constructed from output sheets or simple geometric panels. Follow it with Monumental name composition. Gallery pages instead open with the 100px gallery title above images after a deep pause; company pages open with the 40px statement over documentary photography.

**Avoid:** Do not turn this into a centered headline, paragraph and oversized pill-button stack over a tiny product render. Do not place explanatory copy on top of the material scene.

**Text style:** `display` — k-die-grotesk-vf 400 · 280px/1

### Left rail and reading column

**Observed:** A 24px bold section heading sits in the first two framework columns. Regular 24px prose begins in the third column and spans six columns; paragraph breaks are about 32px. After the rationale and a small continuation link, 137.1px separates the reading material from a wider ruled disclosure list. Outline action links sit below that list.

**Transfer:** Use the narrow rationale column to explain origins, decisions or tradeoffs, then reveal technical depth through concise disclosures.

**Text style:** `intro` — SOEHNE 400 · 24px/1.3333

### Detail exhibition

**Observed:** A small section heading leads a four-column field of Annotated detail plates with 10px gutters. The objects are far larger than their labels; a small downward link follows the field.

**Transfer:** Demonstrate distinctive product construction at enlarged scale instead of enumerating generic features.

**Text style:** `section-heading` — SOEHNE 700 · 24px/1.25

### Captioned proof field

**Observed:** A 24px chapter heading precedes Proof media in four narrow-gutter columns; some images span two columns. Proof caption is almost attached to the image edge. A small see-more arrow link sits below, aligned inward with the text framework.

**Transfer:** Choose representative uses with varied image shapes and sparse identification; the gallery should feel like a body of work rather than testimonial cards.

**Text style:** `caption` — SOEHNE 400 · 16px/1.3333

### Signature colophon closing

**Observed:** Colophon footer preserves the page theme. A deep top pause precedes the expressive signature opposite the newsletter invitation, Email field and Outline action. Ruled directory groups and a compact bottom utility line complete the ending. The long gallery index uses a minimal alternative after the same 450px pause: back-to-top, copyright and build note only.

**Transfer:** End a product or company page with the signature-and-directory device rather than a generic centered sales banner. Reserve the minimal footer for a deep browsing index.

### Specimen and inspection chapters

**Only for:** interactive product demonstrations

**Observed:** Tiny toolbar metadata precedes near-full-width 280px exhibition words. Later text samples show the product at smaller scales; feature tabs and toggles lead to a split inspector with an enlarged selected object at left and a dense outlined choice grid at right. The grid uses 57px cells and 1px tonal outlines, not raised cards.

**Transfer:** Adapt to a genuine hands-on product exploration: a large result paired with compact controls and indexed choices. Keep the surrounding marketing typography separate from the demonstrated product's own UI.

**Text style:** `display` — k-die-grotesk-vf 400 · 280px/1

### Editorial and company proof

**Only for:** black-canvas editorial and company pages

**Observed:** White 36px bold names pair with 36px regular role lines and 16px prose in two inward-offset columns. Collaborator rows put the name/discipline at left and prose at right. A structured closing proof table uses thin gray top rules, 13.7px vertical cell padding and secondary gray descriptions.

**Transfer:** Use people, partners or institutional proof when relevant; preserve the table-like factual tone instead of inventing numerical impact counters.

**Text style:** `editorial-heading` — SOEHNE 700 · 36px/0.98

## Page flow

**Storyline:** material intrigue → named proposition → rationale → enlarged craft and hands-on proof → real applications → signature colophon

### Expressive product landing page with substantial inspection depth

1. **Intrigue** — A full-screen material film followed by a monumental product-name composition.
2. **Rationale** — Left-rail chapter label, narrow editorial explanation and technical disclosures with resource actions.
3. **Capability demonstration** — Style overview, annotated detail plates, editable specimens and a structured feature/choice inspector.
4. **Application proof** — Captioned image field showing the product used outside its own presentation.
5. **Closing orientation** — Theme-colored signature, newsletter row and dense grouped directory.

**Transfer:** Translate the long specimen middle into the new product's most convincing interactive or enlarged proof; retain the contrast between visual spectacle and tiny practical controls.

### Campaign-led product portfolio

1. **Discovery** — Successive viewport-scale media campaigns, each with a tiny product label at the lower edge.
2. **Catalogue access** — Broad shallow product bands pair expressive name artwork at left with small variant and purchase lists at right.
3. **Proof and editorial depth** — Four-column application gallery followed by a three-column image-led article grid.
4. **Closing orientation** — Black signature colophon with newsletter and directory.

**Transfer:** Use immersive campaign worlds for distinct offerings, then return to a sober index; do not require a fixed campaign count.

### Deep visual browsing and application discovery

1. **Orientation** — Sparse black opening, 100px white title, and compact filter menus in the utility bar.
2. **Accumulated proof** — Long four-column image index, varied aspect ratios and occasional two-column anchors, each with a factual inline caption.
3. **Exit utility** — Minimal back-to-top and legal/build line after a 450px pause, without the full newsletter directory.

**Transfer:** Use for a portfolio, case library or output gallery; filtering should serve the material instead of turning it into a dashboard.

### Culture, craft and the people behind a product

1. **Point of view** — Compact 40px statement over a large monochrome workplace photograph and narrow factual prose.
2. **Human credibility** — Two-column profiles with portraits, bold names, large regular role lines and compact biographies.
3. **Network proof** — Collaborator rows followed by a ruled affiliation/support table.
4. **Closing orientation** — Black signature colophon, newsletter and directory.

**Transfer:** Use original people and verified relationships to ground the product; maintain documentary restraint.

## Writing

Culturally literate, candid and craft-conscious. The voice can express tension or a sharp opinion, but practical information stays plain and factual.

**Do not copy:** Do not reuse Klim's names, wordmarks, seal, product names, specimen quotations, customer names, biographical details, dates, claims or achievements. Examples illustrate tone only.

- **Addressing the reader:** Editorial passages use we and our for the maker; most labels are impersonal nouns or direct verbs. The reader is rarely addressed with promotional you-language.
- **Rhythm:** Headings are usually one to four words. Utility actions are short verb phrases; introductory prose can sustain several developed sentences, interrupted by occasional very short assertions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Chapter title | Literal noun identifying the material, without a promotional subtitle. | 1–3 words | “Information”<br>“Details” |
| Editorial rationale | Situate the product in a wider context, acknowledge a contradiction, then state the design response. | A developed paragraph with short emphatic sentences | “Graphic designers love it. Type designers hate it.”<br>“A typeface so familiar it feels like air.” |
| Point of view | State a reason the work matters and why it continues. | Two compact sentences | “Typefaces reflect a culture’s priorities and aspirations. This is why we keep designing new typefaces – the job isn’t done.” |
| Action | Concrete verb plus named resource or destination. | 2–6 words | “Download test fonts”<br>“Continue reading”<br>“See more fonts in use” |
| Closing invitation | Plain statement of what subscribing delivers. | One short line | “Get news about our fonts” |

**Words and phrasing to use:** designed; craft; details; information; in use; support; download; contemporary; historical

**Avoid:** revolutionary; supercharge; game-changing; unlock your potential; seamless magic

**Rules:**

- Name what a section contains instead of promising a vague benefit.
- Support quality claims with construction decisions, history or actual applications.
- Let occasional pointed contrasts give the editorial prose personality; keep purchase and support copy literal.
- Keep image captions identifying rather than congratulatory.

## Do's and Don'ts

### Do

- Keep the default orange environment continuous from product narrative to footer.
- Use 20px page insets and 10px grid gutters at desktop.
- Pair 24px chapter labels with narrow 24px regular rationale copy.
- Retain 28px utility labels and 36px outlined resource actions with 2px corners.
- Use 16px captions with a 2px top attachment to proof images.
- Include both an immersive material scene and a monumental name composition somewhere in the story.
- Preserve the 450px colophon pause and the typographic signature opposite the newsletter row.

### Don't

- Do not enlarge navigation text to 20px or make every action 48px tall; the utility scale is deliberately subordinate.
- Do not use 12px rounded corners, floating shadows or glossy panels for the media index.
- Do not scatter purchase red across headings or large backgrounds; it belongs to a tiny commercial control.
- Do not make every proof photograph the same square thumbnail; varied proportions and two-column anchors drive the index.
- Do not turn the technical metadata into fabricated impact statistics or oversized KPI counters.
- Do not use the demonstrated product's typography for all editorial body copy; keep the 16px utility sans system distinct.
- Do not replace the expressive footer signature with another generic sans heading or a centered conversion card.

## Motion and responsive

### Motion

**Observed:**

- Material campaigns use video. No running text or surface animations were established.
- Some controls declare background-color 50ms ease-out, with transform 50ms ease-out on a subset.
- Label and outlined action hover/active states invert theme foreground and background.

**Transfer:**

- Let the material scene provide movement while the utility shell remains visually stable; its still frame must work as a complete composition.

**Unknown:**

- Playback choreography, section transition timing and focus-visible visuals are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 430px, 431px, 768px, 769px, 1024px, 1366px, 1680px and 2000px; desktop uses a fluid framework without a fixed maximum width.

**Transfer:**

- For narrower screens, preserve the material stage and small utility controls; fit the monumental lettering as a coherent block rather than clipping away its meaning.
- As design guidance, collapse the left label rail above the reading column and reduce proof-grid columns while retaining tightly attached captions and varied image ratios.

**Unknown:**

- Exact mobile column counts, navigation substitutions and type scaling rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
