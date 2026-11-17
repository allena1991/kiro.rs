# Aaron Poe & Co — stacked work, tight words

## Overview

An image-led portfolio language with the confidence of a creative director’s presentation: compact, tightly packed grotesk lettering against expansive white space and a near-black opening stage. Color comes largely from photographic campaigns, physical product mockups and motion-design studies rather than decorative website chrome. It suits design-conscious products and creative services whose work can carry the argument, with sparse copy and unusually rich visual proof.

### Essentials

- A small promise introduces a dense stack of work rather than a giant sales headline: a centered two-line white statement above overlapping rectangular imagery on #111111, with the stage filling about 860px of a 900px first screen.
- Headlines feel compressed into solid verbal shapes: 42px/44px, weight 700 and -3px tracking, rendered with a 1.40078 scale at desktop for an effective 58.8px size. Short, bold paragraphs form secondary blocks rather than soft editorial body text.
- Navigation is a floating translucent lozenge, not a full-width header: 336px × 41px with 10px corners in its base geometry, visually 471px × 57px at desktop; its transparent pill-shaped actions carry the only persistent conversion link.
- The website frame is almost entirely white and near-black; #fe4271 is reserved for current navigation and link emphasis, while saturated color stays inside photographic and graphic work panels.
- Image evidence is staged as objects: include the overlapping rectangular work stack and an edge-clipped ribbon pairing circular images with oversized category words. If finished campaign media is unavailable, use original product photographs, interface details and simple typographic studies in those same formats.
- The end stays deliberately small: after the final visual statement or image-word ribbon, a widely distributed baseline of studio identity, email, social link and copyright replaces the usual oversized conversion banner.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Active pink | `#fe4271` | `--color-accent` | text, link, action | Current navigation item and hovered editorial links; never the default large-area fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Opening black | `#111111` | `--color-stage` | background | Full-bleed introductory work stage. |
| Primary ink | `#121212` | `--color-ink` | text, surface | Headings, paragraphs and navigation; also the dark mat in technical demonstrations. |
| Caption gray | `#929292` | `--color-muted` | text | Supporting credits, project captions and secondary role lines. |
| Navigation wash | `#f5f5f5` | `--color-nav-wash` | surface | Visible result of #f2f2f2 at 80% opacity over white; the same layer becomes gray over the dark opening. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Default page ground and reversed opening text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case studies | Credit black | `#000000` | `--color-black` | text, surface | Micro-labels and selected demonstration backings. |
| case studies | Metric charcoal | `#282828` | `--color-metric` | text | Large quantitative proof. |
| portfolio project galleries | Warm media edge | `#d5d4ce` | `--color-media-edge` | border | Subtle boundary on a framed project video. |
| portfolio project galleries | Lavender mat | `#e7e9f3` | `--color-lavender-mat` | surface | Pale backing around a device-led project image. |
| portfolio project galleries | Cream mat | `#f5f1e8` | `--color-cream-mat` | surface | Warm backing for a typographic project tile. |

## Typography

- **custom_156352** — Main headings, paragraphs, navigation, captions and numbers. Bold neo-grotesk with a broad x-height, closed spacing and deliberately compressed word shapes. OpenType features: "ss02". If unavailable, use **Inter**. Use weight 700 and retain the tight tracking; inspect line breaks after substitution. Font stack: "custom_156352", "Inter", Arial, sans-serif.
- **custom_152369** (only for motion-identity case studies) — Small uppercase quantitative captions. Compact monospaced lettering that contrasts with the dense grotesk numbers. If unavailable, use **IBM Plex Mono**. Font stack: "custom_152369", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | custom_156352 | 700 | 42px | 44px | -0.0714em, features "ss02" | Large proposition statements and image-word ribbon labels; apply the desktop stage scale described in typographyNotes. |
| body | custom_156352 | 700 | 16px | 18px | -0.019em, features "ss02" | Main introductory support paragraphs; compact blocks with justified lines and a natural last line. |
| navigation | custom_156352 | 700 | 10px | 32px | -0.05em | Four short centered navigation labels, including the contact action. |
| footer-link | custom_156352 | 700 | 7px | 32px | -0.043em | Email and social links along the minimal closing baseline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | metric | custom_156352 | 700 | 44px | 76px | -0.034em, features "dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0 | Three adjacent outcome numbers; symbols and suffixes remain on the same baseline. |
| case studies | case-body | custom_156352 | 700 | 16px | 18px | -0.05em, features "ss02" | Justified explanatory paragraphs, inline partner links and concise capability lists. |
| case studies | micro-label | custom_156352 | 700 | 8px | 1.5 | -0.037em, uppercase, features "dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0 | Credit headings, names and compact stat explanations. |
| portfolio project galleries | project-caption | custom_156352 | 700 | 8px | 2.5 | -0.025em, features "ss02" | Project index at the left and project descriptor at the right beneath each image. |
| motion-identity case studies | metric-caption-mono | custom_152369 | 400 | 8px | 1.5 | normal, uppercase, features "dlig" 0, "hlig" 0, "liga" 0, "rlig" 0, "smcp" 0 | Two- or three-line explanations under quantitative proof. |

**Notes:**

- The base typography and button geometry are composed on a 1028px-wide stage and enlarged by 1.40078 at a 1440px desktop width. Reproduce that scale together, rather than using the base font sizes at full viewport width: display becomes 58.8px/61.6px with -4.2px tracking; body becomes 22.4px/25.2px; navigation becomes 14px with a 44.8px line box; metrics become 61.6px with a 106.5px line box.
- Use either a consistently scaled inner stage or equivalent enlarged declarations, not both. The layout widths below describe the final desktop composition.
- The opening promise is embedded in the visual presentation and reads at about 20px, bold, in two centered lines; keep it much smaller than the display statement below the opening.
- Large words are exceptionally tight. Body tracking is less aggressive on the introductory page than in case-study paragraphs; do not average these into a single recipe.
- Micro text remains visually subordinate even after enlargement. The wider metric line box creates breathing room above the tiny caption, without a surrounding card.

## Layout

**Density:** Airy in composition but compact within text: large unoccupied fields separate dense, bold verbal blocks and closely abutting imagery.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Rendered outer inset of the extremely wide gallery and footer edges. |
| 25px | Rendered top inset of the floating navigation. |
| 80px | Typical rendered white interval between major case-study media bands; use as a compositional guide. |
| 127px | Rendered desktop side margins for primary narrative and case-study media. |

### Containers and grids

- **narrative container**: max width 1186px · side padding 127px. Centered main image and narrative region at 1440px desktop width; this is a composition width, not a permanently narrow text column.
- **offset narrative**: 2 columns · gap 127px. A 468px paragraph block sits on the right under a wide statement; case studies reverse the emphasis with a left paragraph and a 589px image at right.
- **case media pair**: 2 columns · gap 8px. Adjacent image panels within the narrative container; mix equal halves with narrower text against wider media.
- **portfolio field** (only for portfolio project galleries): max width 1424px · 3 columns · gap 8px · side padding 8px. Nearly edge-to-edge, unequal-width three-column project rows; vary image heights and align captions to individual tile edges.
- **archive field** (only for portfolio archives): max width 1424px · 7 columns · side padding 8px. Small images around 96px wide distributed across seven widely spaced columns, with mixed aspect ratios and generous row separation.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation capsule | 10px |
| navigation action | 100px |
| ribbon image | 100px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Default narrative and gallery ground.

**CSS:** `background: #ffffff; color: #121212`

**Observed:** No card shadows or repeated bordered containers around ordinary text.

**Transfer:** Let whitespace separate content rather than adding panels.

#### Black work stage · level 0

**Use:** Opening composition.

**CSS:** `background: #111111; color: #ffffff`

**Observed:** Full viewport width, with a restrained central cluster of images and substantial black space at every edge.

**Transfer:** Treat the darkness as a presentation stage, not a universal dark theme.

#### Navigation wash · level 1

**Use:** Floating navigation backing.

**CSS:** `background: rgba(242, 242, 242, 0.8); border-radius: 10px`

**Observed:** The translucent backing shows the tone of whatever passes beneath it; it is rounded but not a full semicircular pill.

**Transfer:** Keep the same lightweight material above both dark and light sections.

#### Technical media mat · level 0

**Only for:** technical product case studies

**Use:** Backing around interface demonstrations.

**CSS:** `background: #121212`

**Observed:** Rectangular dark fields frame smaller light interface views; the mat remains visibly thick around the image.

**Transfer:** Keep product controls inside the image, not as a second marketing-page navigation system.

#### Pastel project mat · level 0

**Only for:** portfolio project galleries

**Use:** Backing for individual portfolio images.

**CSS:** `background: #e7e9f3`

**Observed:** Pale lavender surrounds a cropped upright device; a separate typographic tile uses cream.

**Transfer:** Choose a restrained, content-specific backing and keep the surrounding gallery white.

#### Fine media edge · level 0

**Only for:** portfolio project galleries

**Use:** Boundary around an individual video tile.

**CSS:** `border: 0.7px solid #d5d4ce; box-shadow: inset 0px 0px 0px 1px #d5d4ce`

**Observed:** An edge treatment rather than a raised card.

**Transfer:** Use only when the artwork needs a defined boundary.

## Components

### Floating navigation

**Use:** Persistent route selection and contact access.

**CSS:** `width: 336px; height: 41px; background: rgba(242, 242, 242, 0.8); border-radius: 10px; display: flex; align-items: center; justify-content: space-between`

**Text style:** `navigation` — custom_156352 700 · 10px/32px · tracking -0.05em

**Observed:** Centered near the top and retained during scrolling; four labels, with the identity link first and the contact link last. Current route is pink; all others are ink. Geometry uses the shared desktop stage scale.

**Transfer:** Keep four concise destinations rather than growing the header into a menu bar.

### Navigation action

**Use:** Primary contact action inside the floating navigation.

**CSS:** `height: 32px; border-radius: 100px; background: transparent; color: #121212; display: flex; align-items: center; justify-content: center`

**Text style:** `navigation` — custom_156352 700 · 10px/32px · tracking -0.05em

**Observed:** Reads as a small text action within the capsule rather than a separately filled button; no large hero button competes with the work stack.

**Transfer:** Use a concise contact or inquiry verb in the final position.

### Image word ribbon

**Use:** Signature capability or benefit display.

**CSS:** `display: flex; align-items: center; white-space: nowrap; color: #121212`

**Text style:** `display` — custom_156352 700 · 42px/44px · tracking -0.0714em

**Observed:** Two broad horizontal rows alternate circular images with oversized words; both rows extend beyond the viewport and are clipped at the edges. Base circles are 124px in diameter with 100px corner radii, visually about 174px at desktop. The labels share the main display treatment.

**Transfer:** Pair concise product capabilities with circular details of the product, use context or original graphic studies.

### Footer contact links

**Use:** Quiet direct contact at the page ending.

**CSS:** `color: #121212; background: transparent; height: 32px; border-radius: 24px`

**Text style:** `footer-link` — custom_156352 700 · 7px/32px · tracking -0.043em

**Observed:** Email and one professional social link are distributed across an almost full-width baseline, between a tiny identity at far left and copyright at far right. There is no enclosing dark footer panel.

**Transfer:** Keep contact directly available without turning the end into a second hero.

### Editorial link

**Only for:** case studies

**Use:** Named collaborator or contextual destination within prose.

**CSS:** `color: #121212; background: none; padding-bottom: 1px; text-decoration: none`

**Text style:** `case-body` — custom_156352 700 · 16px/18px · tracking -0.05em

**Observed:** Inherits the paragraph’s heavy grotesk and participates in the line of text.

**States:** Declared: hover color #fe4271, background none, text-decoration none; focus-visible and active treatments are unknown.

### Project tile

**Only for:** portfolio project galleries

**Use:** Image-first selectable work with a restrained descriptor.

**CSS:** `color: #929292; background: transparent`

**Text style:** `project-caption` — custom_156352 700 · 8px/2.5 · tracking -0.025em

**Observed:** Artwork is a hard-edged rectangle; the index sits below its left edge and the short project name aligns to the right. Different tiles have different aspect ratios and can have their own pastel backing.

**Transfer:** Use the caption as a catalog notation, not a card title and paragraph.

### Outcome trio

**Only for:** case studies

**Use:** Quantified proof embedded in an image narrative.

**CSS:** `display: flex; justify-content: space-between; color: #282828; background: transparent`

**Text style:** `metric` — custom_156352 700 · 44px/76px · tracking -0.034em

**Observed:** Three large figures occupy the left half of a case-study spread, with tiny uppercase captions underneath. The right half continues with visual material. Captions use micro-label for technical products or metric-caption-mono for motion-identity work.

**Transfer:** Show three defensible outcomes with short explanatory labels, without icons, boxes or decorative dividers.

### Credit cluster

**Only for:** case studies

**Use:** Compact attribution below the project introduction.

**CSS:** `display: flex; color: #000000; background: transparent`

**Text style:** `micro-label` — custom_156352 700 · 8px/1.5 · tracking -0.037em · uppercase

**Observed:** Two or three mini-columns distinguish contribution, team and creative partners. Dark headings precede gray names, all uppercase and close-set.

**Transfer:** Use for contributors, disciplines or factual specifications rather than a feature-card grid.

## Imagery and graphics

### Overlapping work stack

**Use:** Signature central object in the introductory stage.

**Observed:** A roughly 390px-wide by 380px-tall cluster of about ten overlapping portrait and landscape rectangles mixes human photography, packaging, hardware, interface details and graphic identity work. A monochrome athletic torso dominates the center; bright lime, lilac and sky-blue details peek out behind it. Slight tilts and unequal depths suggest a loose physical stack, with no consistent frame or shadow.

**Transfer:** Make an original stack of the product in use, its packaging or interface, human context and typographic studies. The minimum version is six well-composed original images with one dominant central portrait and contrasting edges; avoid stock-image uniformity.

**Build:** Create an isolated relative-positioned cluster about 390px × 380px at desktop. Absolutely layer six to ten image rectangles, with widths roughly 110px–170px, mixed portrait and landscape ratios, rotations within about 5 degrees and substantial overlap. Put one tall monochrome image at the front center; let saturated and pale images peek from behind, then overlap one landscape detail at the lower right. Use object-fit: cover and preserve hard edges. Back the entire scene with the Black work stage.

### Circular ribbon pictures

**Use:** Punctuation within the Image word ribbon.

**Observed:** Photographic portraits, illustration and identity graphics are cut into equal circular medallions next to large black category labels. Their varied visual languages are held together by the consistent circle and white backing.

**Transfer:** Use image details from the same product story as the main media; when photography is limited, make simple black-and-white typographic or geometric studies.

**Build:** Clip square images to 100px corner radii on a 124px base box, scale with the surrounding ribbon and alternate one circle with one short text label. Duplicate the row contents beyond both viewport edges; offset the second row so its image-word pattern does not align vertically.

### Real world product proof

**Only for:** case studies

**Use:** Case-study openings and supporting panels.

**Observed:** A laptop is photographed obliquely on perforated metal in monochrome while its interface stays electric blue; a separate motion project shows a monitor on a domestic desk and a phone held in a hand. These appear as large rectangular panels, sometimes full container width and sometimes half-width beside compact text.

**Transfer:** Photograph the product in a believable material environment. Keep one strong perspective, tangible surfaces and a clear focal interface rather than adding a generic floating browser frame.

### Motion system boards

**Only for:** motion-identity case studies

**Use:** Visual explanation of design systems and output.

**Observed:** Soft sage, terracotta, cream and deep olive fields contain rounded module cards, tactile three-dimensional product shapes, expressive typography and warm daylight photography. One board constructs a visual equation of motion pillar × visual module = output, using three stacked-card diagrams. Color belongs to these artworks, not the white page frame.

**Transfer:** Show a simple visual grammar becoming a finished outcome; use the new product’s own content and campaign palette. Preserve the warm, softly lit material quality and large clean backing.

### Technical demonstration sequence

**Only for:** technical product case studies

**Use:** Capability and process proof.

**Observed:** Light editor interfaces, timing graphs, typographic presets and output examples are inset into near-black rectangular mats. Later pairs show a dark-mode switch study beside a bright-blue real-world output, ending with a blue typographic composition inside a large black field.

**Transfer:** Show real workflow frames and export results in a consistent mat, with enough interface detail to establish credibility; do not promote screenshot-internal fonts and controls to page-wide rules.

### Small format archive

**Only for:** portfolio archives

**Use:** Long-tail breadth at the end of a work index.

**Observed:** Seven widely separated columns of small, mixed-aspect images show packaging, logos, photography, motion frames and graphic experiments. Individual images remain tiny relative to the open field. The ground moves visually from white toward light gray deeper in the archive; no card labels are attached.

**Transfer:** Use a curated contact sheet of genuine additional work or use cases, retaining natural image proportions and wide spacing rather than enlarging everything into a dense feed.

## Section recipes

How recurring sections are built.

### First screen: Dark stack opening

**Observed:** The Black work stage fills about 860px of the first 900px, with a narrow strip of the White canvas visible below. Floating navigation sits centered about 25px from the top and occupies roughly one third of the viewport width. Behind it is uninterrupted near-black; below it, a compact white two-line promise is centered above the Overlapping work stack. The promise reads at about 20px and occupies less than a fifth of the viewport width; the image cluster occupies roughly a quarter of the width and sits in the central part of the screen. Layers are dark ground, slightly tilted image rectangles, frontmost hero images and the persistent navigation. All of the promise and the image stack is visible before the fold; the large editorial display statement and support copy come later. Contact lives in the navigation; there is no separate hero CTA block.

**Transfer:** For a new product, use a two-line outcome promise above a stack of original use-context, interface and product-detail images. Preserve the small text-to-object ratio even if the images must be simple typographic studies. Case-study pages instead open on the White canvas with one broad media panel under the navigation; work-index pages open with a large left-aligned display statement and an offset supporting paragraph.

**Avoid:** Do not replace the compact centered promise with an enormous left-aligned headline, or spread the stack into a regular card grid.

**Text style:** `body` — custom_156352 700 · 16px/18px · tracking -0.019em

### Statement with offset support

**Observed:** A broad two-line display statement spans the main 1186px narrative width. Its support block sits below on the right in a 468px column, leaving a conspicuously empty left half. Paragraphs are bold, tightly led and justified. A line of black client marks bridges the visual opening into this narrative area.

**Transfer:** State the product’s point of view in a complete sentence, then put concrete context in a separate offset block; use relevant trust marks only when available.

**Text style:** `display` — custom_156352 700 · 42px/44px · tracking -0.0714em

### Ribbon close

**Observed:** The Image word ribbon takes over the lower white page in two edge-clipped rows, with large circles and display-size capability words. A generous white interval separates the preceding narrative from the ribbon, then Footer contact links and tiny baseline identity close the page.

**Transfer:** Make a memorable visual list from benefits, disciplines or use cases; the device can appear elsewhere in a new page, while the closing baseline remains restrained.

**Text style:** `display` — custom_156352 700 · 42px/44px · tracking -0.0714em

### Case introduction and credits

**Observed:** A broad opening image is followed by a split spread: 468px of bold justified narrative at left, an approximately 589px-wide square or upright image at right and the Credit cluster below the paragraph. Explanatory section leads use the same case-body voice rather than oversized headings for every chapter.

**Transfer:** Explain responsibility, intention and the user-facing change in one compact paragraph, and let attribution or specifications stay tiny.

**Text style:** `case-body` — custom_156352 700 · 16px/18px · tracking -0.05em

### Media-led proof chapters

**Observed:** Full-width media panels alternate with pairs of unequal-height images and small narrative blocks, separated by white intervals around 80px. Outcome trio occupies the left half while a visual demonstration continues at right. Motion-system boards use campaign-colored artwork; technical demonstrations use the Technical media mat.

**Transfer:** Choose the scoped visual system that suits the content, then alternate whole-system views with close details and measured outcomes rather than repeating identical feature rows.

### Case ending

**Observed:** The final image is a major work sample, not a conversion panel. One variant pairs a cream message panel with a vertical strip of warm human photographs on sage; the technical variant centers a blue typographic output inside a near-black mat. A tiny right-aligned Next link sits immediately below, followed by open white space and the common footer baseline.

**Transfer:** Finish with a strong result image, offer a small continuation link and keep contact on the shared baseline. Match the final artwork to the new product rather than inventing a large closing claim.

### Portfolio chapters and archive

**Observed:** The index opens with a display statement and right-offset support. Each work chapter then has an identity-and-role block at left, a compact responsibility paragraph across the remaining width and three unequal media columns with Project tile captions. After the selected chapters, a small Archive heading and year range introduce the Small format archive, which runs through the final footer baseline.

**Transfer:** Organize selected proof by product family, discipline or outcome, then use a small-format archive for breadth; preserve the change of image scale rather than repeating the main gallery indefinitely.

## Page flow

**Storyline:** Visual promise → concise point of view → image-led evidence and explanatory detail → breadth or outcomes → memorable final artwork → minimal contact baseline.

### Introduce a creative offering through a concentrated visual identity and an editorial point of view

1. **Visual promise** — Dark stage with small centered statement and overlapping image stack.
2. **Trust** — A horizontal line of recognizable black client marks.
3. **Positioning** — Large statement with right-offset compact supporting paragraphs.
4. **Capability breadth** — Two rows of circular images and oversized category words.
5. **Contact** — Tiny widely spread baseline with direct email and professional social link.

**Transfer:** Use the stack as the visual hook and the ribbon as a second distinctive way to communicate breadth; allow the narrative order to adapt to the product.

### Explain an expressive identity through its visual grammar, real applications and outcomes

1. **Product demonstration** — Wide motion-art opening under the persistent navigation.
2. **Context and attribution** — Compact left narrative and credits beside a monitor photograph.
3. **System explanation** — Sage visual equation board and alternating application images.
4. **Quantified proof** — Three bold outcomes with tiny monospaced uppercase captions.
5. **Human application** — Phone-in-hand and warm photographic campaign images paired with short narrative.
6. **Continuation and contact** — Final cream-and-sage paired artwork, small Next link and common baseline footer.

**Transfer:** Use an expressive campaign system only within the work, while preserving the white page frame and compact explanatory voice.

### Demonstrate a technical creative product through its workflow and finished outputs

1. **Product demonstration** — Large photographic laptop image with vivid interface color against a monochrome setting.
2. **Context and attribution** — Left narrative and credits beside a typographic motion sample.
3. **Capability chapters** — Dark-matted interface, timing graph and preset demonstrations.
4. **Quantified proof** — Three large figures followed by a compact capability list.
5. **Output range** — Paired demonstrations of modes, image ratios and finished motion compositions.
6. **Continuation and contact** — Blue typographic result on a black mat, tiny Next link and common baseline footer.

**Transfer:** Replace the source tool views with genuine workflow images and output examples, retaining the dark mats as the scoped presentation language.

### Establish breadth and collaborative responsibility across a body of work

1. **Point of view** — Large opening statement with right-offset prose about collaboration.
2. **Selected proof** — Three work chapters combining a role label, responsibility text and unequal-width image galleries.
3. **Breadth** — Archive heading and date range followed by seven columns of tiny mixed-aspect images.
4. **Contact** — The archive ends directly above the shared minimal footer baseline.

**Transfer:** Use the chapter structure for selected proof and the small-format field for additional examples; keep the two scales distinct.

## Writing

Confident, personally accountable and collaborative. Strong claims are expressed plainly, then supported by actual work, responsibility and quantified outcomes rather than promotional adjectives.

**Do not copy:** Do not reuse the studio’s name, personal biography, client names, project titles, collaborator names, proprietary artwork, contact details, metrics or claims as facts about another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** First person singular for responsibility, with explicit credit to partners and teams; outcomes are described in terms of people and the experience rather than repeatedly addressing the reader as you.
- **Rhythm:** Complete, conversational statement headlines; short dense paragraphs; terse noun labels for capabilities and actions. Lists are factual and compact rather than slogan-heavy.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short active phrase that connects the work to a larger cultural or human result. | About 10 words over two centered lines. | “Building brands for products that live in culture” |
| Positioning statement | A first-person complete sentence that joins craft with purpose. | About 15–20 words. | “I'm a brand designer and creative leader with a passion for building brands that matter.”<br>“Great brands are built by great teams, and I’ve spent my career building both.” |
| Explanatory lead | Name the system and explain its intended human effect with active verbs. | One sentence, about 20–30 words. | “The Hims & Hers motion system is designed to remove barriers, create intuitive experiences, and build stronger, more personal connections.” |
| Capability label | Short discipline or system noun phrase. | Two words. | “Art Direction”<br>“Identity Systems” |
| Action | An unembellished destination or continuation word. | One word. | “Contact”<br>“Next” |

**Words and phrasing to use:** built; led; create; system; collaboration; team; experience; motion; people

**Avoid:** revolutionary; game-changing; unlock your potential; world-class solutions; !!!

**Rules:**

- Explain what changed for people before expanding on the craft.
- Make ownership explicit, but place collaborative credit alongside it.
- Use numerical proof only with a clear label defining the outcome.
- Keep image captions descriptive: a project name, an em dash and a discipline or deliverable.

## Do's and Don'ts

### Do

- Retain the 42px/44px, weight-700 display recipe and its shared desktop scale.
- Keep the opening object near 390px wide within a full-width dark stage.
- Use #fe4271 only for route emphasis and editorial link interaction.
- Carry the 10px base corner radius and translucent fill into the centered navigation capsule.
- Set main support copy in compact bold blocks, with a right-offset 468px narrative column.
- Mix broad rectangular media with equal circular ribbon images rather than using one image shape everywhere.
- Keep outcome numbers unboxed, grouped in threes with tiny uppercase explanations.
- Close with the near-full-width miniature contact baseline, not a second promotional hero.

### Don't

- Do not substitute a thin geometric display face for the dense weight-700 grotesk.
- Do not loosen display tracking to normal; the compressed -3px base tracking is central to the word shapes.
- Do not make every section dark because the opening is dark; the narrative ground is #ffffff.
- Do not turn the contact link into a large filled pink button.
- Do not put soft shadows and rounded corners on every work image; the primary media panels are hard-edged.
- Do not turn the circular ribbon pictures into a standard icon-feature grid.
- Do not attach paragraphs and prominent CTA buttons to every portfolio tile; captions stay at the tiny index-and-descriptor scale.
- Do not let the archive images grow to the size of selected work; its small mixed-aspect objects create a deliberately different rhythm.

## Motion and responsive

### Motion

**Observed:**

- Declared transitions use 545ms cubic-bezier(0.4, 0.24, 0.4, 1) on matched action and surface rules.
- Editorial links declare a pink hover color without background or underline.
- The floating navigation stays present across scrolling views; the image-word ribbons occupy different horizontal positions and clip at the viewport edges.
- Media panels show motion-design sequences and changing output frames.

**Transfer:**

- Preserve the image-word ribbon as a horizontally continuous visual device, keeping its circles and words together.
- Use the declared transition timing where implementing comparable navigation or surface transitions; do not assign it to every media animation.

**Unknown:**

- Exact ribbon direction, looping speed and scroll linkage are not established.
- Playback controls, complete animation choreography and focus-visible styling are not established.

### Responsive

**Observed:**

- The desktop composition is 1440px wide; its inner-stage enlargement factor is 1.40078.
- No width breakpoints are established.

**Transfer:**

- For a narrow-screen adaptation, preserve the centered promise and layered stack as one composition, shrink the media cluster before sacrificing its overlap and keep the image-word ribbon clipped horizontally.
- Stack the offset narrative columns and case-study image pairs while preserving the contrast between selected work and much smaller archive objects.

**Unknown:**

- Mobile type sizes, navigation changes, archive column counts and exact responsive breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
