# Dries Bos — folded architectural index

## Overview

An architectural, paper-like interface with the feeling of a folded exhibition catalogue. Warm grey planes, near-black outlines and regular grotesk text create an unusually level hierarchy: the spatial construction, rather than oversized typography, makes the statement. It suits creative tools, specialist services and products with a body of work to explain, moving from compact textual indexes to expansive photographic or interface studies.

### Essentials

- The hero is an object rather than a giant headline: a centered 1150px-wide stack with a trapezoidal top plane, 2px outlines and a 75px title fascia.
- Headlines speak at reading size: Sohne Buch 20px, weight 400, line-height 1.45 and normal tracking serve the opening promise, headings, navigation and rows alike.
- Actions are part of the drawing: unfilled text links and 23px arrow icons replace pill CTAs; rows offer a rightward arrow and the closing panel has a tall upward arrow.
- Color belongs to the exhibited work: the surrounding interface stays warm grey with #d6d4cd canvas, #e8e7e3 fronts and #dfddd8 folded planes; saturated colors remain inside media rather than section fills.
- Proof reads like a catalogue: 79px row interiors, 2px horizontal rules, 25px vertical padding and 30px side padding align dates, names, categories and actions.
- Folded depth is a signature device on every page: flat outlined fronts are connected by receding trapezoids, including above the closing contact panel; construct the geometry in SVG or CSS even when no product imagery exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm black | `#050200` | `--color-ink` | text, border, action, link | All primary text, structural outlines and interface icons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Faded ink | `#999794` | `--color-muted` | text | Secondary copy and index labels on paper fronts; ink at 35% opacity over #e8e7e3. Use the alpha recipe when the backing changes. |
| Outer stone | `#d6d4cd` | `--color-canvas` | background | The visible page surround outside the folded stack. |
| Fold plane | `#dfddd8` | `--color-fold` | surface | Receding top faces; a subtly darker material than the fronts. |
| Paper front | `#e8e7e3` | `--color-front` | surface, background | Flat front faces, text panels, index rows and footer. |

## Typography

- **Sohne Buch** — All marketing text, navigation, captions and numerals. Regular neo-grotesk with a plain, workmanlike rhythm; neither display-heavy nor monospaced. If unavailable, use **Inter**. Use 400 throughout; preserve the small scale and normal body tracking. Font stack: "Sohne Buch", "Inter", Helvetica, Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| reading-heading | Sohne Buch | 400 | 20px | 1.45 | normal | Opening promise, section labels, body paragraphs, index rows, navigation and footer. Distinguish roles through placement, not font size. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies and media-led product explanations | media-caption | Sohne Buch | 400 | 13.2px | 1.45 | 0.02em | Faded explanatory lines directly below visual exhibits. |
| sequential case-study navigation | sequence-counter | Sohne Buch | 400 | 13.2px | 1.45 | 0.05em | Small current/total indicator above the previous/next controls. |

**Notes:**

- Keep the visible hierarchy deliberately flat. A section heading and its paragraph share the same 20px regular recipe; half-width placement, underlining and faded ink carry the distinction.
- Use normal sentence case and normal tracking for reading text. Only the small captions and sequence counters gain positive tracking.
- Secondary explanatory paragraphs use rgba(5, 2, 0, 0.35); primary opening paragraphs remain solid ink.

## Layout

**Density:** Comfortable within a compact catalogue: tightly stacked text and rows sit inside a spacious outer surround and large folded planes.

### Spacing

| Value | Use |
| --- | --- |
| 6.3px | Quarter-base gap between stacked footer links. |
| 10px | Media-to-caption gap. |
| 12.5px | Half-base inset at the inner edge of two-column text panels. |
| 25px | Main text top and bottom padding; gap between paragraphs and history records. |
| 30px | Side padding and padding on all four edges of media exhibits. |
| 75px | Three-base breathing space within the introductory and filter fronts; bottom page surround. |

### Containers and grids

- **folded-stack**: max width 1150px · side padding 0px. Centered single vertical object on the outer canvas; at 1440px it leaves 145px margins. Borders define its width; content has its own inset.
- **text-halves**: 2 columns · gap 0px · side padding 30px. Equal-width structural halves. Put labels or metadata on the left and narrative on the right; the right text begins 12.5px inside its half.
- **media-pair**: 2 columns · gap 25px · side padding 30px. Two 531px-wide exhibits across the interior; a single exhibit can instead span 1086px.
- **index-columns**: 2 columns · gap 0px. Two equal structural halves: date and title share the left half; category and trailing action icons share the right.

## Corner radius

| Element | Radius |
| --- | --- |
| panel-fronts | 0px |
| theme-disc | 50% |

## Surfaces and depth

### Surfaces

#### Outer canvas · level 0

**Use:** Page surround.

**CSS:** `background: #d6d4cd`

**Observed:** A matte, untextured warm grey field surrounds the complete stack.

**Transfer:** Preserve the surround so the site reads as a discrete constructed object rather than a full-bleed page.

#### Outlined front · level 1

**Use:** Every principal content face.

**CSS:** `background: #e8e7e3; border: 2px solid #050200; border-radius: 0px; box-shadow: none`

**Observed:** Fronts remain parallel to the screen. Adjacent fronts share a single rule through a -2px overlap.

**Transfer:** Group each coherent block in one face; use folds to articulate larger changes rather than floating cards.

#### Receding plane · level 1

**Use:** The top face of the stack and visible depth between selected fronts.

**CSS:** `background: #dfddd8; border-top: 2px solid #050200; border-right: 2px solid #050200; border-left: 2px solid #050200`

**Observed:** A flat, darker top plane narrows toward its rear edge. It has no lighting gradient or shadow.

**Transfer:** Use an SVG polygon for clean continuous edges, or a perspective-transformed pseudo-element behind the front. The fill alone supplies depth.

## Components

### Title fascia

**Use:** Persistent identity and utility navigation at the head of the object.

**CSS:** `display: flex; align-items: center; height: 75px; background: #e8e7e3; border: 2px solid #050200`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** Identity is left-aligned with a 30px inset and utilities sit at the far right in square unfilled targets. The fascia sits in front of a large receding top plane. Detail variants replace general utilities with external link, previous/next and close controls.

**Transfer:** Use a concise product name and descriptor; keep the controls subordinate to the fascia rather than introducing a separate navbar.

### Introduction link panel

**Use:** Whole-panel navigation from a brief opening promise.

**CSS:** `display: flex; flex-direction: column; padding-top: 75px; background: #e8e7e3; border: 2px solid #050200; color: #050200`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** Two reading-size lines occupy the lower part of the face, inset by the normal text padding. A simple right arrow sits at the lower right; the entire front is the action.

**States:** Declared: hover color currentcolor; focus-visible outline 2px solid currentColor with outline-offset 2px; active color currentcolor.

**Transfer:** Write a short capability statement followed by who benefits and what changes for them.

### Index filter front

**Use:** Column headings and search before a long index.

**CSS:** `display: flex; flex-direction: column; justify-content: flex-end; padding-top: 75px; background: #e8e7e3; border: 2px solid #050200; color: rgba(5, 2, 0, 0.35)`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** Labels align exactly with the columns beneath. The search glyph anchors the far right. The upper part of this front is intentionally spacious.

### Catalogue row

**Use:** Repeated navigable proof, products or project entries.

**CSS:** `display: flex; flex-direction: column; background: #e8e7e3; border-top: 2px solid #050200; border-radius: 0px`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** The first entry has no internal top rule; subsequent entries add one. Each 79px interior uses 25px vertical padding around a single text line. Date, title and category align in columns, with external-link and right-arrow controls at the trailing edge.

**Transfer:** Use the same catalogue logic for releases, integrations or a small product range; retain metadata instead of converting the list into image cards.

### Plain text link

**Use:** Navigation and contact actions without button chrome.

**CSS:** `position: relative; color: #050200`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** A text-only action. Footer links are stacked; external destinations carry a small northeast arrow. An underline can be supplied by a 1.5px pseudo-element.

**States:** Declared: hover color currentcolor; focus-visible outline 2px solid currentColor with outline-offset 2px; active color currentcolor.

### Inline reference link

**Use:** Linked names and concrete proof inside editorial prose.

**CSS:** `color: #050200; background-image: linear-gradient(#050200, #050200), linear-gradient(#050200, #050200); background-size: 100% 1.5px, 0% 1.5px; background-position: 100% 100%, 0px 100%; background-repeat: no-repeat`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** Continuous sentence flow is retained around the underlined reference. Secondary paragraphs use the faded-ink equivalent rather than a different type style.

**States:** Declared: hover color currentcolor; focus-visible outline 2px solid currentColor with outline-offset 2px; active color currentcolor.

### Closing contact front

**Use:** Final navigation and conversion area.

**CSS:** `display: flex; flex-direction: column; background: #e8e7e3; border: 2px solid #050200; height: 189px`

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

**Observed:** A receding plane introduces the final face. Two equal halves hold primary navigation on the left and email, social destinations and newsletter on the right. A tall upward arrow occupies the far-right edge and returns to the start. Link groups use 25px by 30px padding and quarter-base gaps.

**Transfer:** End with a direct contact or conversion route, a few secondary destinations and the tall return arrow; do not inflate this into another hero.

### Theme disc

**Use:** Compact utility control in the title fascia.

**CSS:** `width: 23px; height: 23px; border: 1.5px solid #050200; border-radius: 50%; background: conic-gradient(from -45deg, #050200 0deg, #050200 180deg, rgba(0, 0, 0, 0) 180deg, rgba(0, 0, 0, 0) 360deg)`

**Observed:** A diagonally divided solid/empty disc sits within a 73px utility target alongside fullscreen and accessibility controls.

**Transfer:** Keep the two-tone disc when providing a theme switch, with an accessible label rather than visible explanatory text.

### Media mat

**Only for:** case studies and media-led product explanations

**Use:** A generous frame around visual evidence.

**CSS:** `padding: 30px`

**Observed:** Sits inside Outlined front. A full-width exhibit is 1086px wide; paired exhibits use equal widths and a 25px gap. Captions stay below the image rather than overlaying it.

**Transfer:** Show real product scenes, material tests or use-context photography in these frames.

## Imagery and graphics

### Folded object drawing

**Use:** Signature dimensional construction around the main content, including the opening and closing faces.

**Observed:** Flat paper-colored fronts have thin black edges and receding grey top faces. The opening top plane spans the stack width at its front edge and narrows at its rear; its visible depth is about 183px. Intermediate connectors are shallower. There are no cast shadows or textured paper effects.

**Transfer:** Recreate the folded construction even for a text-only product. It supplies the main visual event independently of artwork.

**Build:** Place an SVG behind the 1150px front. For the opening plane use a 1150 by 183 viewBox and a polygon with points 0,183 75,0 1075,0 1150,183; fill #dfddd8, stroke #050200, stroke-width 2 and vector-effect non-scaling-stroke. Hide the bottom stroke under the front border. For connectors use the same inward-sloping edges with a shallower height and let the preceding face occlude the upper part.

### Landscape collage and physical counterpart

**Only for:** spatial or cultural case studies

**Use:** Large concept exhibit followed by paired real-world and constructed views.

**Observed:** A muted, cut-paper mountain landscape layers pale green hills, white cloud silhouettes and dark sketched buildings. The next pair contrasts a leafy outdoor architectural photograph with isolated black line drawings on a grey backing. Media occupies far more area than the small explanatory captions.

**Transfer:** Pair a real environment with a diagram or material interpretation of the product. Keep natural greens and dusty tones inside the image mat, not the surrounding interface.

**Build:** For a simplified spatial concept, layer irregular SVG hill silhouettes in muted natural tones, add lightly textured image fills and place dark line-drawn objects at distinct depths. Use crisp white cloud silhouettes and a small number of graphic directional markers. A clean original diagram paired with photography is the minimum alternative to elaborate collage.

### Atmospheric interface study

**Only for:** immersive or environment-led case studies

**Use:** Full-width interface boards and paired visual-system studies.

**Observed:** Near-black green backings support centered desktop browser views with generous margins; bark, forest and a water-filled vessel appear in subdued low light. Paired boards isolate light/dark palette steps or compare data labels with and without the photograph. Tiny technical lettering belongs to the work itself.

**Transfer:** Show the new product's actual visual system as a staged board, then a complementary detail or layer decomposition. Preserve low-light tonal restraint without imposing the demonstrated product's fonts on the marketing page.

### Device and use-context study

**Only for:** application and commerce case studies

**Use:** Large full-width demonstrations, paired mobile screens and real-use photography.

**Observed:** A tablet is centered on a pale field; a mobile interface is paired with a close handheld phone photograph. Later, enlarged icon construction and a horizontal sequence of phones demonstrate the system. Bright red, citrus and pastel gradients are contained within these exhibits.

**Transfer:** Use original device mockups or sharply framed interface exports plus one contextual photograph. A single clean product screen on a pale backing is preferable to decorative stock devices; keep all surrounding mats neutral.

### Icons

**Observed:** Near-black SVG arrows and utility symbols, usually 23px by 23px; previous/next arrows extend to 45px by 23px. The appearance is spare and linear, with no filled button containers. The footer return arrow is stretched vertically into a conspicuous drawn line.

**Transfer:** Choose simple arrow, external-link, close, search and utility silhouettes. Keep them aligned to the row ends; do not introduce a separate colorful icon family.

## Section recipes

How recurring sections are built.

### First screen: Folded index opening

**Observed:** A warm grey surround exposes the complete silhouette of a centered 1150px object. Back to front: the outer canvas, a darker receding trapezoid, the 75px Title fascia, a shallower folded connector and the Introduction link panel. The rear of the top plane begins about 164px below the viewport top; its front meets the fascia around 347px. The opening promise is two 20px regular lines low in the introduction face rather than an oversized headline. Identity and three utility controls are visible above it, and a right arrow closes the promise. Within the first 900px, the filter headings and first catalogue entry also appear; the remaining proof list and contact front continue below. No large product image competes with the folded geometry.

**Transfer:** Make a similarly short two-line promise for the new product, preserving the tabletop-like silhouette and reading-size typography. Use the folded drawing as the primary object when no artwork is available. Editorial pages open with a label on the left and prose on the right; case studies open with faded metadata on the left, a solid lead and faded explanatory paragraph on the right, plus sequential controls in the fascia.

**Avoid:** Do not substitute a full-bleed photographic hero, a centered oversized slogan or a floating rounded CTA for the constructed stack.

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

### Catalogue proof

**Observed:** Index filter front introduces aligned metadata columns; Catalogue row repeats as a continuous ruled list inside Outlined front. The list reads as one object, with no gutters between entries.

**Transfer:** Present proof as comparable records, allowing a row to open deeper detail. Use a fold to articulate a larger chapter change rather than breaking every row into a separate card.

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

### Label and narrative

**Observed:** Outlined front is divided into two equal structural halves. A short section label or faded role/output metadata occupies the left; the right has a roughly 531px text measure. Text has 25px vertical padding, 30px outer insets and 12.5px inner insets. Solid leading prose precedes faded supporting prose by 25px.

**Transfer:** Use this for benefits, methodology, context or constraints. Keep the label brief and let the right-hand paragraph do the explaining.

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

### Drawn closing panel

**Observed:** Closing contact front repeats across all page types, preceded by a folded connector. Small navigation on the left balances contact links on the right, while the long upward arrow completes the edge drawing. A 75px canvas margin remains below the object.

**Transfer:** Give the reader one direct route to the business and a small secondary list. Retain the folded entry and elongated return arrow as the visual full stop.

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

### Professional record

**Only for:** editorial company and credentials pages

**Observed:** A label occupies the left quarter while records fill the remaining three quarters. Each record aligns date, organization and role into three columns; dates and roles are faded while organization names stay dark. Records separate by 25px. Related compact rows contain education, recognition, events and link lists.

**Transfer:** Use the same record language for milestones, compatibility, standards or product history; preserve the alternating solid and faded information roles.

**Text style:** `reading-heading` — Sohne Buch 400 · 20px/1.45

### Visual exhibit chapter

**Only for:** case studies and media-led product explanations

**Observed:** Media mat fills Outlined front with either one 1086px-wide image or two 531px-wide images. Media panels often reach roughly 727–908px in height. A 13.2px caption sits 10px beneath the relevant visual. Receding planes articulate the transitions without adding colorful chapter backgrounds.

**Transfer:** Alternate overview, comparison and detail at the pace the product needs. A useful visual explanation takes precedence over more text headings.

**Text style:** `media-caption` — Sohne Buch 400 · 13.2px/1.45 · tracking 0.02em

## Page flow

**Storyline:** compact identity and promise → indexed or editorial proof → deeper visual explanation where useful → direct contact and return navigation

### General marketing or portfolio index

1. **Promise** — Folded silhouette, utility fascia and two-line linked introduction.
2. **Proof** — Muted index headings followed by a long, consistently ruled catalogue.
3. **Closing call** — Folded contact front with navigation, contact destinations and tall return arrow.

**Transfer:** Use this as the default landing-page grammar: a short promise and navigable evidence rather than a conventional giant headline and card grid.

### Company or expertise editorial page

1. **Positioning** — Section label opposite link-rich introductory prose, followed by a practical capabilities paragraph.
2. **Credentials** — Aligned professional records and a compact education row.
3. **Capabilities and recognition** — Label/narrative rows, linked recognition list and short event list.
4. **Connection** — Dedicated social-link row followed by the shared contact front.

**Transfer:** Translate biography into the new organization's expertise and useful credentials; use factual lists rather than promotional tiles.

### Spatial concept case study

1. **Context** — Role, collaborators and output opposite primary and secondary explanatory paragraphs.
2. **Product demonstration** — Large layered landscape exhibit with a small conceptual caption.
3. **Supporting proof** — Paired physical-context photograph and isolated structure drawings.
4. **Closing call** — Shared folded contact front.

**Transfer:** Explain a product's concept, then connect the digital interpretation to its physical or practical counterpart.

### Immersive visual-system case study

1. **Context** — Role and output opposite an introductory narrative.
2. **System explanation** — Paired light/dark palette boards.
3. **Product demonstration** — Two expansive interface presentations on contrasting tonal backings.
4. **Detail proof** — Paired data-only and image-plus-data studies.
5. **Closing call** — Shared folded contact front.

**Transfer:** Demonstrate a visual system through contrasts and layer breakdowns while retaining the neutral architectural wrapper.

### Application and commerce case study

1. **Context** — Role/output metadata opposite a longer product and use-case explanation.
2. **Product demonstration** — Large themed tablet exhibit with a small caption.
3. **Use-context proof** — Paired mobile app and real-world interaction photograph.
4. **System detail** — Enlarged icon study followed by a wide repeated-phone presentation.
5. **Closing call** — Shared folded contact front.

**Transfer:** Move from overall expression to actual use, then show one system detail before the shared ending.

## Writing

Matter-of-fact and personally confident, with occasional playful curiosity. Claims are tied to specific work, roles and interactions rather than inflated slogans.

**Do not copy:** Do not reuse the studio identity, client and collaborator names, project titles, contact details, awards, financing figures, proprietary product terms or project-specific claims. Replace all examples with truthful content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Opening copy describes the maker or capability directly; editorial prose often uses third person, while case studies use first-person plural. The reader is addressed sparingly when describing a concrete experience.
- **Rhythm:** Short labels sit beside complete, conversational paragraphs. Openings use two concise lines; case studies allow longer explanations and occasional questions. There is no oversized slogan cadence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Experience or capability followed by a tangible outcome. | One sentence, roughly 8–14 words. | “An experienced designer crafting award winning interactions.” |
| Supporting line | Define the collaborative relationship and the benefit in plain words. | Two short clauses or sentences. | “And dependable sidekick for ambitious startups. Building interfaces to empower and excite users.” |
| Navigation | Brief destination noun rather than a sales command. | 1–2 words. | “Work”<br>“About”<br>“Newsletter” |
| Metadata | A role label, em dash and factual value. | One compact line per attribute. | “Role — Design & Development”<br>“Output — Website” |
| Visual caption | Explain the mechanism or intent of what is shown. | A fragment or one short sentence. | “Brand expression through theming”<br>“Checkin via NFC chip” |

**Words and phrasing to use:** crafting; interfaces; dependable; ambitious; with; building; Role; Output

**Avoid:** revolutionary; unleash; game-changing; ultimate solution; exclusive opportunity

**Rules:**

- Write a specific capability before a broad aspiration.
- Use linked references inside normal prose rather than a separate cloud of promotional badges.
- Keep metadata factual and captions explanatory; a caption should add information beyond the heading.
- Let one concrete use case carry the excitement instead of stacking superlatives.

## Do's and Don'ts

### Do

- Keep opening and section text at 20px, weight 400 and line-height 1.45.
- Maintain 2px warm-black outlines around the folded fronts.
- Use the 1150px centered stack and preserve visible canvas on both sides.
- Inset prose by 25px vertically and 30px at the outer sides.
- Confine vivid product colors to the media exhibits.
- Use equal structural halves for labels and explanations.
- End with the 189px contact front and tall return arrow.
- Keep captions at 13.2px with 0.02em tracking and 10px separation from media.

### Don't

- Do not introduce bold display cuts to compensate for the intentionally flat hierarchy.
- Do not round panel corners or soften the stack with drop shadows.
- Do not tint the marketing wrapper to match each demonstrated product.
- Do not replace the catalogue's 2px rules with detached cards and broad gutters.
- Do not set metadata in uppercase monospace; it uses the same regular grotesk as prose.
- Do not turn external links into filled social-logo buttons.
- Do not overlay captions on photographs; they belong below the visual.
- Do not add paper grain, bevel highlights or photorealistic shadows to the simple two-tone folding.

## Motion and responsive

### Motion

**Observed:**

- Fronts declare 1s entrance and fade animations with cubic-bezier(0.16, 1, 0.3, 1) and ease-out timing; the opening block has a .35s delay and later blocks add .165s increments.
- Fronts declare padding-top, background, background-color and box-shadow transitions at .33s ease. The fascia also declares transform .33s ease and perspective-origin .66s.
- The theme disc declares transform .25s ease and background .33s ease.
- Linked text keeps its color on hover and active; focus-visible uses a 2px currentColor outline offset by 2px.

**Transfer:**

- Animate the folded object and its fronts as a coherent construction rather than animating every sentence independently.
- Retain unfilled, same-color actions; use the drawn underline and object movement instead of bright hover fills.

**Unknown:**

- Exact travel distances, full interaction choreography and utility outcomes are not established.
- Thumbnail reveal and text-cycle behavior are not specified sufficiently to reproduce their complete sequence.

### Responsive

**Observed:**

- Width breakpoints are declared at 400px, 450px, 770px and 1370px.
- The desktop stack has a 1150px maximum width; utility and metadata groups include desktop-specific variants.

**Transfer:**

- On narrower screens, retain the single folded object and reduce its width to fit the surround rather than turning it into unrelated cards.
- When equal halves cannot sustain readable paragraphs, stack label or metadata above narrative; keep media within the same outlined mats.
- Preserve the small reading-size hierarchy and right-edge directional controls rather than introducing a mobile display headline.

**Unknown:**

- Exact mobile dimensions, fold depths, column changes and alternate utility navigation are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
