# Channel Studio — computational gallery theatre

## Overview

A black, art-directed gallery with soft silver grotesk typography, coral titles and near-monochrome computational imagery. Vast media stages sit beside unusually compact navigation and factual captions, giving experimental technology the presence of a cultural exhibition. It suits ambitious digital products, research platforms and design-led organizations, with dense information held inside sparse, expansive compositions.

### Essentials

- The opening behaves like an ambient artwork rather than a sales panel: a 1440×900 full-bleed grayscale field, a compact upper-left identity cluster, and a 75px regular statement spanning about two thirds of the width.
- Headlines have the tension of oversized gallery lettering: Lausanne 400 at 75px/0.9 with -0.02em tracking; project titles share this scale instead of being reduced to card labels.
- The interface is black and silver with coral used as lettering, not decoration: #000000 canvas, #cacaca primary text, #ff7777 project names; most page area stays black or belongs to imagery.
- Actions are typographic exits, not filled conversion buttons: 18px regular text with a terminal →, plus a monumental 75px closing link. The only enclosed action is a small outlined form pill.
- Media is the architecture: nearly edge-to-edge 16:9 exhibition panels sit within 19px side margins; detail demonstrations narrow to 1152px with 175px black intervals.
- Computational material bridges the promise and proof: use a soft monochrome distortion field and a silver particle sculpture on black. Without bespoke animation, use a blurred grayscale displacement study and a static shaded SVG point cloud.
- The ending remains deliberately small after the big exit: a half-width underlined email signup, muted support copy, and a 13px copyright/social row, separated from the main story by 192px.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral lettering | `#ff7777` | `--color-coral` | text, link, accent | Project titles, associated discipline metadata and active project navigation. Keep large color fields inside the artwork rather than the interface. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Silver text | `#cacaca` | `--color-text` | text, border, link | Primary headings, paragraphs, navigation, text actions and the form-button outline; not pure white. |
| Muted gray | `#727272` | `--color-muted` | text, border | Newsletter prompt, secondary links, input underlines and press dividers. |
| Black canvas | `#000000` | `--color-canvas` | background, surface | The continuous page background and the negative space around media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| case-study demonstrations | Demonstration edge | `#333333` | `--color-edge` | border | Hairline outlines around browser mockups and interface-study panels. |
| case-study press sections | Charcoal band | `#1c1c1c` | `--color-band` | background, surface | Full-width press ending that is visibly lighter than the surrounding black. |
| organizational overview pages | Institutional green | `#5bec95` | `--color-green` | text, link | Introductory statement and active navigation in the organizational variant; it replaces coral rather than combining with it. |

## Typography

- **Lausanne** — All marketing headings, body, labels, navigation and actions. A clean contemporary grotesk with open counters, a broad readable lowercase and a consistently regular visual weight. If unavailable, use **Inter**. Use 400 and retain the negative display tracking; adjust line breaks to maintain the broad text silhouette. Font stack: "Lausanne", "Inter", Helvetica, Geneva, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Lausanne | 400 | 75px | 0.9 | -0.02em | Opening statement, large project titles and monumental closing action. |
| navigation | Lausanne | 400 | 16px | 0.9 | normal | The tightly stacked primary navigation. |
| body | Lausanne | 400 | 16px | 1.23 | normal | Explanatory paragraphs beneath large statements. |
| footer-small | Lausanne | 400 | 13px | 1.19 | normal | Copyright and social links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case-study pages | case-masthead | Lausanne | 400 | 91.2px | 0.75 | -0.02em | Coral title compressed into the header alongside the identity and navigation. |
| case-study pages | case-title | Lausanne | 400 | 45px | 1 | normal | Title below the full-bleed cover, followed by discipline and collaborator lines. |
| organizational pages and case-study deliverable lists | section-list | Lausanne | 400 | 30px | 1.15 | -0.03em | Equal-scale section labels and stacked lists in split-column information sections. |
| organizational overview pages | organization-intro | Lausanne | 400 | 30px | 1 | -0.03em | Green, paragraph-length introductory heading opposite a particle object. |
| case-study press sections | press-title | Lausanne | 400 | 21px | 2.47 | normal | Publication headline in the ruled press row; the tall line box keeps it separated from the small section label. |
| case-study press sections | press-heading | Lausanne | 400 | 18px | 0.954 | normal | Small label at the top of the charcoal press band. |
| contact sections | form-body | Lausanne | 400 | 16px | 1.3 | -0.01em | Contact support copy and outlined submit action. |
| project indexes | index-meta | Lausanne | 400 | 16px | 1.19 | normal | Project name, discipline and action in three compact lines beneath each thumbnail. |
| case-study figures | artifact-caption | Lausanne | 400 | 13px | 1.23 | normal | Small factual caption beneath archive images and demonstrations. |

**Notes:**

- Keep all text at regular weight. Scale, line spacing and color carry hierarchy rather than bold cuts.
- The core 75px display is tightly packed at 0.9 line height; the case-study editorial statement uses normal leading and looser -0.01em tracking for much longer sentences.
- Small actions and metadata retain normal tracking. Split-column lists use a more compressed -0.03em at 30px.
- Use sentence case and ordinary title capitalization; technical content is not automatically converted to uppercase or monospace.

## Layout

**Density:** Airy at the page scale and compact within labels: large black intervals separate tightly assembled text and media.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 10px | Header outer inset and the gap from project title row to media. | fixed |
| 19px | Core gallery side margins. | fixed |
| 16px | Editorial heading-to-body separation and textarea inset. | fixed |
| 18px | Case-study two-column and four-column media gutters. | 1.25vw |
| 20px | Project index column gap, metadata offsets and contact field spacing. | fixed |
| 75px | Separation between organizational information sections. | fixed |
| 88px | Index item bottom margin, including room for the metadata block. | fixed |
| 175px | Case-study chapter and media separation. | fixed |
| 192px | Gap before the shared newsletter footer. | fixed |

### Containers and grids

- **gallery**: side padding 19px. Near-full-width project chapters; 1402px of content at a 1440px viewport. Media, title and exit link share the same edges.
- **opening text**: max width 1008px · side padding 19px. Upper-left statement occupying roughly 70% of the desktop width.
- **editorial body**: max width 734px. Short explanatory paragraphs aligned left below the much wider statement.
- **newsletter**: max width 694px. Left-aligned signup line occupying approximately half the page. Its copyright/social row is narrower at 585px.
- **inset media** (only for case studies): max width 1152px. Centered demonstration and artifact stage; 144px side clearance at desktop.
- **information split** (only for organizational pages): 2 columns · gap 0px · side padding 19px. Two equal 701px halves: label left, list or contact content right.
- **index grid** (only for project indexes): 2 columns · gap 20px · side padding 20px. Two equal 690px thumbnails with metadata beneath; no card enclosure.
- **demonstration grid** (only for extended case studies): 2 columns · gap 18px · side padding 22px. Four interface studies in two rows. A separate narrow-screen study uses four 275px portrait panels with the same gutter.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | gallery media | 0px |
| case-study demonstrations | browser frame | 5px |
| contact sections | message field | 10px |
| contact sections | submit action | 78px |

## Surfaces and depth

### Surfaces

#### Black gallery canvas · level 0

**Use:** The continuous base for every page.

**CSS:** `background: #000000; color: #cacaca`

**Observed:** Most sections do not introduce a new surface or a containing card.

**Transfer:** Let text, images and the intervening black space organize the story.

#### Ambient grayscale field · level 0

**Use:** The full-bleed opening artwork.

**CSS:** `background: #000000; overflow: hidden; position: relative`

**Observed:** A soft gray, blurred, almost liquid field fills the first screen; it is a moving image layer rather than a colored interface panel.

**Transfer:** Use the grayscale material recipe as the background and keep text above it.

#### Press band · level 0

**Only for:** case-study press sections

**Use:** A final external-validation area before the common footer.

**CSS:** `background: #1c1c1c; padding: 9px 0px 32px`

**Observed:** The label is small and the article row has a muted top rule. The compact version contains one line; the expanded version includes a large publication image and date.

**Transfer:** Use this band for genuine third-party coverage or equivalent validation, not a generic feature card.

#### Browser demonstration · level 1

**Only for:** case-study demonstrations

**Use:** Thin framing for inset interface videos.

**CSS:** `background: #000000; border: 1px solid #333333; border-radius: 5px; box-shadow: none`

**Observed:** A 29px browser bar has three 9px hollow circles with 3.2px gaps and a 9.6px left inset. The screen below is large and unshadowed.

**Transfer:** Add only enough browser chrome to identify the content as a working interface.

## Components

### Identity navigation cluster

**Use:** Brand identification and primary navigation at the upper left.

**CSS:** `display: flex; align-items: center; color: #cacaca`

**Text style:** `navigation` — Lausanne 400 · 16px/0.9

**Observed:** A 179×67px identity mark sits beside four vertically stacked text links; the navigation has 9px side margins. The home header overlays the artwork; inner-page headers sit above content. Active project links are coral, while the organizational active link is green.

**Transfer:** Use the new identity at a comparable visual mass, preserving the small vertical navigation rather than expanding it into a horizontal menu.

### Arrow text action

**Use:** Default way into detailed content.

**CSS:** `color: #cacaca; background: transparent; border: 0px`

**Observed:** Lausanne 18px, weight 400, normal line height and normal tracking. Plain text ends in a typographic right arrow. It is baseline-aligned at the far right of the large coral title row.

**Transfer:** Use a short literal verb and destination; keep the action visually lighter than the title.

### Gallery project panel

**Use:** Large image-led proof chapter.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: space-between; align-items: baseline; margin-top: 20px`

**Text style:** `display` — Lausanne 400 · 75px/0.9 · tracking -0.02em

**Observed:** A coral title link and Arrow text action precede a square-cornered, nearly full-width 16:9 image or video. The title-to-media gap is 10px. There is no card fill, border or descriptive paragraph inside the panel.

**Transfer:** Give each major product outcome its own immersive media panel.

### Monumental exit link

**Use:** The large final action after the media story.

**CSS:** `display: block; color: #cacaca; margin-top: 20px; background: transparent`

**Text style:** `display` — Lausanne 400 · 75px/0.9 · tracking -0.02em

**Observed:** A single left-aligned line spans the available gallery width; it does not become a centered banner or pill.

**Transfer:** Choose the next meaningful destination and let the enlarged lettering be the call to action.

### Newsletter footer

**Use:** Shared low-key ending.

**CSS:** `max-width: 694px; border-bottom: 1px solid #727272; display: flex; align-items: flex-end; justify-content: space-between`

**Observed:** An oversized muted email prompt sits on the underline, with a 15px supporting line 8px below. After 64px of breathing room, a 13px copyright sits left and two social links sit farther right in a 585px row. The footer begins 192px after the preceding content.

**Transfer:** Retain the half-width editorial signup and understated utility row; do not turn the ending into a navigation sitemap.

### Index project tile

**Only for:** project indexes

**Use:** Dense visual browsing.

**CSS:** `position: relative; margin-bottom: 88px`

**Text style:** `index-meta` — Lausanne 400 · 16px/1.19

**Observed:** A 690×388px image is followed after 10px by three tight lines: coral title, coral disciplines, silver arrow action. Two tiles share a row; the last unpaired item stays left aligned.

**Transfer:** Use a compact taxonomy and equal-aspect thumbnails so different projects remain comparable.

### Contact fields

**Only for:** contact sections

**Use:** Direct inquiry inside the right half of an information section.

**CSS:** `border-bottom: 1px solid #727272; margin-top: 20px; margin-bottom: 20px; background: transparent`

**Text style:** `form-body` — Lausanne 400 · 16px/1.3 · tracking -0.01em

**Observed:** Single-line fields are underlined rather than boxed. A 351×254px message field uses a complete outline, 10px radius and 16px padding. The form occupies only half of the right column, leaving further black space.

**Transfer:** Keep the field set short and use an explicit label for each field.

### Outlined submit

**Only for:** contact sections

**Use:** Small form submission action.

**CSS:** `border: 1px solid #cacaca; border-radius: 78px; padding: 4px 12.8px; opacity: 0.5; color: #cacaca; background: transparent`

**Text style:** `form-body` — Lausanne 400 · 16px/1.3 · tracking -0.01em

**Observed:** A small 94×31px outline pill sits left-aligned below the message field; its subdued appearance is distinct from the unboxed main-page actions.

**Transfer:** Reserve this enclosed treatment for forms.

### Press article row

**Only for:** case-study press sections

**Use:** A link to external validation.

**CSS:** `border-top: 1px solid #727272; margin-top: 10px; margin-bottom: 34px`

**Text style:** `press-title` — Lausanne 400 · 21px/2.47

**Observed:** Article title and muted publication name sit left; a small arrow action sits right on the same baseline. Expanded entries place an inset publication image and date below.

**Transfer:** Keep the article title factual and let the publication name play a secondary role.

### Figure carousel

**Only for:** case-study figures

**Use:** Inspecting an artifact or related sequence without adding card UI.

**CSS:** `position: relative; background: #000000`

**Text style:** `artifact-caption` — Lausanne 400 · 13px/1.23

**Observed:** A centered artifact is flanked by slender 22×39px chevrons near the outer edges. The caption is left-aligned to the 1152px figure stage with about 13px top separation. Controls do not sit inside circles.

**Transfer:** Use contain sizing for artifacts so material edges remain visible; use the same framing for a short sequence of product studies.

## Imagery and graphics

### Soft computational material

**Use:** Signature atmospheric artwork in the first screen.

**Observed:** The full-screen image is grayscale and softly defocused, with broad horizontal folds, dark cavities and silver-gray ridges. No object silhouette or horizon is clearly defined; the headline is the only sharp large element.

**Transfer:** Create a grayscale study of the product's underlying material or process. The minimum version is a layered blurred displacement field, not a colorful gradient.

**Build:** Fill the stage with black. Layer three broad SVG ellipses or curved ribbons with gray fills made from rgba(202,202,202,0.25), rgba(202,202,202,0.5) and rgba(114,114,114,0.7), extending beyond the edges. Bend them with feTurbulence plus feDisplacementMap; blur 45px–90px and add a restrained turbulence grain layer. Keep the top-left behind the headline darker and let a pale ridge gather toward the lower right. Match the soft sculptural folds; exact stops are not essential.

### Silver particle sculpture

**Use:** Signature computational bridge between the opening statement and visual proof; also appears beside organizational text.

**Observed:** Thousands of tiny gray and silver beads describe a twisted, perforated cloth-like volume on pure black. Directional highlights make the points read as matter rather than a flat star field. The landing treatment is large and partly off-frame; the organizational treatment is a smaller isolated vertical object.

**Transfer:** Use a point-cloud version of a meaningful product form, data model or folded surface. A still shaded point sculpture is the minimum acceptable version.

**Build:** Sample a warped rectangular mesh into an SVG point field: rotate it in perspective, bend its middle into an S-shaped fold and leave irregular holes. Draw 2px–5px circles, varying size with depth and fill opacity from rgba(114,114,114,0.25) to rgba(202,202,202,1). Place the brightest points on the upper-left ridges, with dark points disappearing into black. Use a few thin connecting arcs only where they reinforce the surface; do not add colored glows.

### Exhibition cover imagery

**Use:** Large gallery panels and index thumbnails.

**Observed:** Subjects range from glossy translucent sculptural bodies against pale blue to grayscale mineral formations, photogrammetric landscapes floating on black, architectural photography and vintage electronics against pink. Images are strongly composed, edge-to-edge and mostly 16:9; their own color can be much richer than the interface.

**Transfer:** Choose one visually concrete hero treatment per outcome: a material macro, an isolated artifact, a spatial reconstruction or documentary setting. If no bespoke render exists, use a carefully lit photograph rather than generic abstract stock art.

### Interface studies

**Only for:** case-study demonstrations

**Use:** Showing working systems in full, paired or multi-device arrangements.

**Observed:** Desktop screens sit inset on black, sometimes within thin browser frames. Studies range from single 1152px-wide demonstrations to two-by-two panels, four portrait screens, and a staggered desktop/tablet/phone montage. Embedded serif faces, bright media and dense controls belong to the demonstrated products rather than the surrounding marketing typography.

**Transfer:** Show real workflows at a legible scale, alternate an overview with focused details, and keep the surrounding stage black. Do not promote the embedded product's type or palette into the marketing system.

### Artifacts and documentary proof

**Only for:** case-study figures and event chapters

**Use:** Evidence of the product in cultural or physical use.

**Observed:** An open aged book retains its cream paper, gold ornament and page texture, isolated on black. Event photographs retain dim auditorium lighting and large projected screens; two-by-two documentary grids use 18px gaps. Object images are contained, while environmental images can fill wide panels.

**Transfer:** Photograph genuine source objects or the product in use with natural material color intact. Pair artifacts with precise captions and event images with a brief factual chapter heading.

### Icons

**Observed:** The primary directional language is the text glyph →. Image carousels use thin open chevrons, 22×39px, with no enclosing disc. Decorative feature-icon sets are absent.

**Transfer:** Prefer typographic arrows for links and simple line chevrons for directional controls; keep them silver and subordinate to the artwork.

## Section recipes

How recurring sections are built.

### First screen: Ambient statement opening

**Observed:** The first 900px is one full-width 1440×900 artwork stage. Back to front: black base, soft grayscale moving material filling the stage with cover sizing, upper-left identity/navigation cluster inset 10px, and a silver 75px/0.9 statement below it inset 19px. The statement has a 1008px maximum width and breaks into roughly three lines, leaving most of the lower screen to the image. The navigation occupies only about 255×67px; it is not a full-width bar. There is no separate supporting paragraph or sales button in this first screen. The continuation statement, client proof and project panels fall below the fold.

**Transfer:** Open a new landing page with a concise category-and-purpose statement against its own monochrome material study. Make the statement sharp and the image soft. If animation is unavailable, use the static material build. Case studies instead compress a coral 91.2px title beside the navigation over a full-bleed 16:9 cover; an index starts directly with two columns of thumbnails; an organizational page starts with the particle object left and green prose right.

**Avoid:** Do not center a short slogan over a tiny product mockup, add a colored CTA pill, or force support copy and proof badges into the first screen.

**Text style:** `display` — Lausanne 400 · 75px/0.9 · tracking -0.02em

### Computational proof bridge

**Observed:** A second full-height black stage continues the large statement, then pairs a small client label and compact monochrome logos with the Silver particle sculpture. The sculpture is dominant, offset toward the center-right, with large black breathing space before the gallery begins.

**Transfer:** Preserve the computational object and understated proof treatment somewhere in the story, placing genuine customer marks or another concise trust signal beside it. Its position can change with the narrative.

### Immersive gallery chapter

**Observed:** The Gallery project panel puts a large coral project name at left and Arrow text action at the far-right baseline, then a nearly full-width 16:9 media panel after 10px. Successive chapters are separated by short black intervals rather than card borders.

**Transfer:** Use this for a product capability, use case or outcome with visually strong proof.

**Text style:** `display` — Lausanne 400 · 75px/0.9 · tracking -0.02em

### Large exit and small footer

**Observed:** The final gallery panel gives way to Monumental exit link after 20px. Newsletter footer follows after a 192px gap, leaving the right half predominantly black. The project index ends with its last left-aligned tile and the same footer; the organizational variant ends with a compact biography section before it.

**Transfer:** Use a large textual exit for the primary next step and retain the small signup/social ending, without duplicating the same conversion message.

### Editorial case introduction

**Only for:** case-study pages

**Observed:** Below the cover is a 45px coral project title with 20px top and bottom padding, compact discipline and collaboration lines, and a large editorial statement in Lausanne 75px, weight 400, normal line height and -0.01em tracking. A 16px paragraph follows after 16px, limited to 734px. The next demonstration begins after a 175px interval.

**Transfer:** State what was made, who it serves and why the approach matters, then explain the mechanism in a restrained paragraph.

### Information split

**Only for:** organizational pages and deliverable summaries

**Observed:** An equal two-column section places a 30px label in the left half and a 30px list in the right. Lists have no bullets or enclosing cards. Organizational sections repeat after 75px; contact and biography keep the same right-hand alignment but switch to smaller copy.

**Transfer:** Use for capabilities, supported workflows, partner lists or direct contact, retaining equal visual status between section label and list.

**Text style:** `section-list` — Lausanne 400 · 30px/1.15 · tracking -0.03em

### Evidence-led media essay

**Only for:** extended case studies

**Observed:** Single inset demonstrations alternate with wide media, two-by-two detail grids, four portrait studies and occasional body-only passages. A testimonial in Lausanne 45px, weight 400, normal line height and -0.01em tracking occupies the right half opposite a documentary image. Later chapter headings in Lausanne 30px, weight 400, normal line height and -0.01em tracking introduce event photographs. Intervals are commonly 175px, not a repeated card stack.

**Transfer:** Choose the media arrangement according to the proof: overview, interaction detail, cross-device behavior, independent response and real-world use. Use only chapters justified by the product.

### Press and utility ending

**Only for:** case-study pages

**Observed:** Press band follows the final media chapter: a small 18px label, ruled article row, and in the extended version a large publication image. After 192px of black space comes Newsletter footer. There is no unrelated related-project grid at the end.

**Transfer:** Close a detailed narrative with independent validation, then the shared understated utility footer.

## Page flow

**Storyline:** Atmospheric proposition → visible work or product proof → explanatory detail and validation → typographic exit → understated newsletter utility.

### Express an ambitious offering through visual proof

1. **Promise** — Two expansive media stages carry a sentence-length proposition and a computational object with compact customer proof.
2. **Product proof** — Large coral titles introduce immersive, nearly full-width media panels with small right-aligned actions.
3. **Closing action** — A display-size arrow link opens the broader body of work.
4. **Retention** — An underlined email prompt and tiny social/copyright row close the page.

**Transfer:** Use the same shift from ambient abstraction to concrete outcomes, choosing the quantity and order of outcomes to suit the offer.

### Explain a digital experience through archive-like evidence

1. **Identification** — A coral masthead and full-bleed cover introduce the work, followed by title, disciplines and collaborators.
2. **Context** — A full-width editorial summary and short paragraph establish the mechanism.
3. **Capability proof** — Inset interface videos, a split deliverables list and a series of product views show how the system behaves.
4. **Material proof** — A contained artifact carousel adds factual captions and tangible texture.
5. **Independent validation** — A compact ruled press band precedes the shared newsletter footer.

**Transfer:** Combine explanation, actual interaction views and source-material detail for a focused product story.

### Document a complex platform across interfaces and real-world use

1. **Identification** — Compact header title, cover, discipline lines and a large editorial introduction.
2. **Demonstration** — Inset browser videos lead into a documentary image and large testimonial.
3. **System depth** — Wide studies, two-by-two views, multi-device arrangements and portrait panels vary the pace.
4. **Adoption proof** — Brief chapter headings introduce talks, launch documentation and image grids.
5. **Independent validation** — An expanded press band includes publication imagery before the newsletter footer.

**Transfer:** Organize a long story around different kinds of proof, not one identical block repeated for every feature.

### Introduce an organization and provide a direct contact route

1. **Positioning** — A particle object on black faces a green paragraph-length statement and smaller body copy.
2. **Credibility** — Equal-column sections list customers and capabilities without cards or logos.
3. **Contact** — The same split grid carries underlined fields, message box and small outline submit.
4. **Human context** — A concise principal biography and secondary profile link precede the shared footer.

**Transfer:** Use the green variant for an organizational narrative; substitute relevant partner, capability and team information.

### Let visitors browse a substantial body of visual work

1. **Orientation** — Compact identity navigation with small size-control affordances at the opposite edge.
2. **Browse** — Two columns of 16:9 thumbnails, each followed by three lines of compact metadata.
3. **Retention** — The unpaired final tile remains left aligned; black space leads to the common email footer.

**Transfer:** Favor directly comparable images and concise metadata rather than introducing a separate hero.

## Writing

Intellectually ambitious and matter-of-fact. The writing joins technology and form through concrete descriptions of what was made, with cultural confidence but little sales pressure.

**Do not copy:** Do not reuse the studio's identity mark, project names, client logos, proprietary artwork, institutional claims, project counts, awards or attributed quotations. Replace them with the new product's genuine assets and verifiable facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** The organization speaks as itself or as 'we'; most copy describes the work rather than addressing 'you'. Actions use short direct verbs.
- **Rhythm:** The opening is a complete descriptive sentence, sometimes continued across two large stages. Editorial leads can be paragraph-length; supporting paragraphs are compact and technical. Labels and actions remain very short, without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Name the organization, its category and its distinctive combination of disciplines. | One sentence, split into readable large-text phrases. | “Channel is a brand and user experience innovation company”<br>“combining intensive technology with formal design expertise.” |
| Editorial explanation | Describe the work's mechanism through specific actions and materials. | A short paragraph beneath a much larger lead. | “This involved collecting and digitizing all of their correspondence, interviews, scientific papers, and images from their personal and professional lives.” |
| Action | Plain verb plus destination with a terminal arrow. | 2–4 words plus arrow. | “See Project →”<br>“See all projects →”<br>“Go to article →” |
| Metadata | Comma-separated disciplines with no promotional adjectives. | 2–4 discipline names. | “Archiving, Design, Engineering” |
| Retention | A direct signup prompt followed by a low-frequency reassurance. | One short label and one short line. | “Sign up for occasional updates” |

**Words and phrasing to use:** built; combining; digital archive; systems; interface; design; engineering; collaboration; explore

**Avoid:** game-changing; effortless magic; supercharge; unlock your potential; !!!; limited-time offer

**Rules:**

- Connect abstract ambition to a concrete medium, interface or process.
- Use named disciplines as metadata instead of decorative tags.
- Let the work demonstrate value before making a strong evaluative claim.
- Keep supporting copy factual enough to function as exhibition interpretation.

## Do's and Don'ts

### Do

- Keep the default display at 75px, weight 400, 0.9 line height and -0.02em tracking.
- Maintain the 19px gallery side margin while allowing opening and cover media to bleed to the edges.
- Use coral for project lettering and silver for navigation and actions.
- Pair full-width statements with 734px supporting paragraphs rather than making all text equally wide.
- Give inset case-study media a 1152px stage and 175px chapter intervals.
- Keep main actions unboxed, with terminal arrows; reserve the 78px-radius outline pill for form submission.
- Preserve both the ambient material and particle sculpture as visual signatures, using static equivalents when needed.
- End with a half-width signup line and 13px utility text rather than a large multi-column footer.

### Don't

- Do not substitute pure-white primary text for the softer #cacaca.
- Do not fill marketing sections with coral; its interface role is lettering.
- Do not promote the organizational green into the default landing-page palette.
- Do not add drop shadows or rounded-card shells around gallery images.
- Do not use bold display weights to manufacture hierarchy; the typography relies on size and spacing.
- Do not turn compact index metadata into oversized card descriptions.
- Do not import serif fonts or bright colors from demonstrated product interfaces into the surrounding site system.
- Do not shrink artifact images to decorative thumbnails; their material and captions are part of the proof. 

## Motion and responsive

### Motion

**Observed:**

- The main atmospheric material and particle sculpture are video-based media.
- Declared transitions include color 0.25s ease-in-out and background-color 0.25s ease-in-out on selected actions and surfaces.
- Carousel layouts use translated horizontal slide containers; chevrons appear at the media edges.

**Transfer:**

- Use motion to animate the material itself while the upper-left text remains a stable reading anchor.
- Keep demonstrations within their large black stages; retain a meaningful still version of the ambient field and particle object.

**Unknown:**

- Exact video loops, scroll coupling and playback timing are unspecified.
- Hover color targets, focus-visible styles and transition behavior for individual main-page links are not established.

### Responsive

**Observed:**

- Stylesheet width breakpoints are 640px, 768px, 1024px, 1440px and 1920px; the organizational page does not list 640px.
- The 18px media gutter follows 1.25vw.

**Transfer:**

- On narrow layouts, preserve the contrast between oversized statement and tiny navigation while fitting the statement to the available width.
- Stack information splits label-first and collapse media grids before demonstrations become unreadable; retain black separation and image aspect ratios.
- Allow long case-study mastheads to wrap independently of the identity cluster rather than overlapping it.

**Unknown:**

- Mobile font sizes, exact column-collapse thresholds, header substitutions and mobile media framing are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
