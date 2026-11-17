# Superr — paper, play and possibility

## Overview

A light, tactile world where technology feels like a beloved everyday object rather than a dashboard. Cream paper, chocolate ink and a burst of tangerine frame soft product renderings, painterly environments and comic-style human stories. Rounded lettering and friendly serifs carry the personality, while a restrained grotesk makes interactions easy to scan. The density is low, with expansive visual scenes punctuated by compact, ruled information cards.

### Essentials

- The opening reads like a friendly parcel inscription: a chunky, irregular lowercase headline occupies a 492px-wide, two-line artwork block, paired with 28px/1.4 regular serif support and a small orange handwritten aside.
- The product is a tangible protagonist, not a thumbnail: an oversized tilted object enters from the lower right of a 900px-tall cream stage and continues beyond the fold; use a dimensional illustrated artifact when the product is intangible.
- Actions resemble outlined paper stickers: a 20px-radius cream outer shell with 4px padding surrounds a 16px-radius, 2px chocolate-outline inner face; text is 20px/30px medium serif.
- Color lives primarily in scenes, not interface chrome: cream and chocolate dominate ordinary sections, green/blue/pink emphasize short capability phrases, and a full-width tangerine closing surface supplies the strongest flat color.
- Information feels like a notebook index: 420px-wide cream cards use 2px chocolate edges, 12px corners, 36px/1.2 serif headings and fine horizontal rules with Roman numerals at the right.
- Human marks bridge the polished render and the page: include hand-drawn annotations, small outlined sticker illustrations and a monumental rounded word sculpture in the closing area; use original SVG doodles and custom rounded lettering when equivalent artwork is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Tangerine | `#ff6f1e` | `--color-orange` | background, accent | Closing surface and handwritten accents; not the default button fill. |
| Pressed orange | `#ce500a` | `--color-burnt` | text, accent | Tone-on-tone closing word sculpture and small closing metadata. |
| Chocolate ink | `#2b1a07` | `--color-ink` | text, border | Default marketing text, outlines and drawn details. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#3b82f6` | `--color-blue` | text, accent | A second capability chapter's emphasized phrase and active index row. |
| Leaf green | `#22c55e` | `--color-green` | text, accent | Short emphasized capability phrases and their active index row. |
| Candy pink | `#ff66cf` | `--color-pink` | text, accent | A third capability chapter's emphasized phrase and active index row. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Literal black | `#000000` | `--color-black` | text | Opening explanatory line; use chocolate for ordinary section copy. |
| Pencil taupe | `#8a7b6a` | `--color-muted` | text | Support lines and availability notes. |
| Paper ruling | `#f2ede9` | `--color-rule` | border, accent | Faint architectural vertical rules, made with chocolate-brown #8d715a at 10% opacity over warm paper. |
| Blush paper | `#f7efe9` | `--color-band` | background | A reassurance chapter that remains warm and low contrast. |
| Warm paper | `#fdfbf9` | `--color-canvas` | background, surface | Default page canvas and layered action shells. |
| Index card | `#fffcf9` | `--color-card` | surface | Opaque capability cards above colorful imagery. |
| White | `#ffffff` | `--color-white` | text | Mission statement and navigation on tangerine. |

## Typography

- **gelica** — Section headings, opening support, buttons and editorial narrative. Soft, rounded contemporary serif with a friendly, almost storybook construction. If unavailable, use **Lora**. Use regular 400 and medium 500; retain natural tracking. Font stack: "gelica", "Lora", Georgia, serif.
- **Geist** — Capability controls, questions, links and brief status text. Clear contemporary grotesk that contrasts with the soft serif. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | gelica | 400 | 40px | 1.2 | normal | Default section heading, centered for reassurance and questions. |
| closing-heading | gelica | 400 | 40px | 1.5 | normal | Two-line closing mission statement. |
| feature-heading | gelica | 400 | 36px | 1.2 | normal | Short multi-line capability statement inside an index card, with selective colored words. |
| hero-support | gelica | 400 | 28px | 1.4 | normal | Two-line explanation beneath the opening headline artwork. |
| support | gelica | 400 | 24px | 1.4 | normal | Muted one-sentence support below a centered heading. |
| button | gelica | 500 | 20px | 1.5 | normal | Primary action and editorial action labels. |
| link | Geist | 500 | 20px | 1.5 | normal | Footer navigation and active capability labels. |
| utility | Geist | 500 | 18px | 1.5 | normal | FAQ questions and compact availability lines. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial letters | letter-title | gelica | 400 | 40px | 1.5 | normal | Left-aligned title in a narrow prose column. |
| editorial letters | letter-body | gelica | 400 | 22px | 40px | normal | Long-form first-person narrative, with generous leading. |

**Notes:**

- Keep ordinary serif headings regular rather than bold; hierarchy comes from scale, composition and color.
- Tracking stays normal throughout the marketing typography.
- The opening title and the closing word sculpture are custom rounded lettering, not enlarged versions of the serif headings. Set the opening artwork in two tight lowercase lines within a 492px by 164px block.
- For a lettering fallback, use a heavy rounded display face such as Lilita One, then convert to SVG and subtly vary letter angles and widths. This is an artwork construction choice, not the running text family.

## Layout

**Density:** Airy; screen-sized illustrations alternate with compact ruled controls and narrow reading columns.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small action icon gaps. |
| 12px | Heading-to-support spacing, capability list gaps and footer link gaps. |
| 24px | Top inset of feature cards, FAQ question padding and ordinary section side padding. |
| 32px | Inner side inset of capability card headings and rows; gap below opening lettering. |
| 40px | Space between capability title and list; paragraphs in editorial letters. |
| 48px | Wide closing side inset and editorial title-to-copy gap. |
| 64px | Questions heading-to-list gap and footer top inset. |
| 90px | Reassurance band top and bottom padding. |
| 96px | FAQ top padding and editorial signature separation. |
| 160px | FAQ bottom breathing room; editorial page top and bottom inset. |

### Containers and grids

- **visual stage**: max width 1600px · side padding 48px. Wide staging for closing composition; product scene backgrounds extend edge to edge beyond text containers.
- **section content**: max width 1200px · side padding 24px. Centered content within a full-width reassurance chapter.
- **opening copy**: max width 492px. A compact left-hand text cluster inset about one seventh of the desktop width, with the product taking the right and lower field.
- **question column**: max width 720px · 1 column · side padding 24px. Centered question list; heading spans the same width.
- **letter column** (only for editorial letters): max width 720px · 1 column · side padding 40px. Centered outer column yielding 640px of readable prose at desktop; full-width illustrated strips interrupt the narrow measure.

## Corner radius

| Element | Radius |
| --- | --- |
| action shell | 20px |
| action face | 16px |
| capability card | 12px |
| closing top corners | 56px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action shell | `0px 1px 2px 0px rgba(0,0,0,0.25)` | Small paper-like lift beneath conversion actions. |
| index card | `0px 2px 20px 0px rgba(0,0,0,0.06)` | Subtle separation of a capability index from a painted scene. |

### Surfaces

#### Paper canvas · level 0

**Use:** Ordinary marketing and editorial background.

**CSS:** `background-color: #fdfbf9; color: #2b1a07`

**Observed:** Flat warm paper without a pervasive texture overlay.

**Transfer:** Leave broad areas clear so objects and handwriting can breathe.

#### Index paper · level 1

**Use:** Capability information over media.

**CSS:** `background-color: #fffcf9; border: 2px solid #2b1a07; border-radius: 12px; box-shadow: 0px 2px 20px 0px rgba(0,0,0,0.06)`

**Observed:** Opaque light cards maintain legibility over vivid scenery.

**Transfer:** Use a real paper-like panel rather than translucent glass.

#### Reassurance paper · level 0

**Use:** A quieter promise or constraints chapter.

**CSS:** `background-color: #f7efe9; padding: 90px 24px`

**Observed:** A flat blush-tinted band frames a centered ruled-paper graphic and sparse corner doodles.

**Transfer:** Give one important trust message a distinct warm paper field.

#### Ruled backdrop · level 0

**Use:** Behind a large human-scale illustration.

**CSS:** `background-color: #fdfbf9; background-image: repeating-linear-gradient(90deg, transparent 0px, transparent 235px, rgba(141,113,90,0.1) 235px, rgba(141,113,90,0.1) 237px)`

**Observed:** Sparse faint vertical rules sit behind the hands-and-product artwork.

**Transfer:** Use faint rules as a drawing-sheet reference, not a technical grid.

#### Tangerine closing · level 0

**Use:** Default landing-page ending.

**CSS:** `background-color: #ff6f1e; border-radius: 56px 56px 0px 0px; overflow: clip`

**Observed:** A rounded-top orange panel overlaps a strip of illustrated human scenes.

**Transfer:** Preserve the sudden change of material and the oversized tone-on-tone lettering.

## Components

### Floating navigation

**Use:** Persistent orientation and a single conversion route.

**CSS:** `position: fixed; top: 16px; width: 100%; z-index: 50`

**Observed:** No full-width painted bar or conventional menu. A small outlined sticker symbol sits at the left; the Paper action sits at the right. The action is not visible at the settled opening, but appears in later scenes.

**Transfer:** Use an original compact emblem and one primary action; keep the surrounding scene visible.

### Paper action

**Use:** Primary conversion and story-reading actions.

**CSS:** `background-color: #fdfbf9; padding: 4px; border-radius: 20px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.25)`

**Text style:** `button` — gelica 500 · 20px/1.5

**Observed:** An outer paper shell surrounds an inset outlined face. Its width follows the short label rather than stretching across a column; the usual total height is 63px.

**States:** Declared: hover retains the base shadow and zero translation; focus-visible and active appearance are unknown.

**Transfer:** Use the same shell for editorial and commercial actions rather than inventing unrelated button styles.

### Action face

**Use:** Inner face of every Paper action.

**CSS:** `background-color: #fdfbf9; color: #2b1a07; border: 2px solid #2b1a07; border-radius: 16px; padding: 10.7px 20px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `button` — gelica 500 · 20px/1.5

**Observed:** The inset border leaves an even cream margin inside the outer shell, creating a sticker cutline.

### Capability index

**Use:** Compact capability navigation laid over a full-screen product scene.

**CSS:** `background-color: #fffcf9; border: 2px solid #2b1a07; border-radius: 12px; width: 420px; max-width: 480px; padding: 24px 0px 16px; display: flex; flex-direction: column; gap: 40px; box-shadow: 0px 2px 20px 0px rgba(0,0,0,0.06)`

**Text style:** `feature-heading` — gelica 400 · 36px/1.2

**Observed:** A two-line serif analogy sits above five ruled capability rows. Row labels use 20px/30px Geist, regular by default and medium when active; the selected row matches the heading's accent. Serif Roman numerals sit at the right. Heading and row text are inset 32px.

**Transfer:** Use a memorable analogy and short, user-facing capabilities. Preserve the ruled index instead of converting it into a tile grid.

### Question row

**Use:** Low-noise objection handling.

**CSS:** `width: 100%; text-align: left; padding-top: 24px; display: flex; flex-direction: column; color: #2b1a07`

**Text style:** `utility` — Geist 500 · 18px/1.5

**Observed:** A question is followed by 20px of clear space and a faint dashed horizontal separator. Repeated rows occupy about 73px each; no boxed background or conspicuous plus icon is visible.

**States:** Declared: hover opacity 0.8; focus-visible and active appearance are unknown.

### Closing links

**Use:** Small editorial, contact and social navigation groups.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px; color: #ffffff`

**Text style:** `link` — Geist 500 · 20px/1.5

**Observed:** Two narrow vertical groups sit to the right of the mission line. At wide desktop size, the groups are separated by 116px rather than evenly distributed across a mega-footer.

### Closing panel

**Use:** Default landing-page brand sign-off.

**CSS:** `background-color: #ff6f1e; border-radius: 56px 56px 0px 0px; height: 700px; display: flex; flex-direction: column; overflow: clip`

**Text style:** `closing-heading` — gelica 400 · 40px/1.5

**Observed:** White two-line mission at upper left, Closing links at upper right, an enormous darker orange word sculpture below, and a small metadata baseline at the bottom.

**Transfer:** Keep the word sculpture almost full width, using the new product's own name or a short original rallying word.

### Letter sign-off

**Only for:** editorial letters

**Use:** Personal close rather than a commercial footer.

**CSS:** `margin-top: 96px`

**Text style:** `letter-body` — gelica 400 · 22px/40px

**Observed:** An orange handwritten signature sits above a role line and a medium-weight organization name. The prose column remains left aligned; the page ends with 160px of cream breathing room and no orange footer panel.

**Transfer:** Use a genuine author signature, role and organization for a personal essay.

## Imagery and graphics

### Dimensional everyday object

**Use:** Opening product protagonist and later personalization scenes.

**Observed:** A brown notebook with softened corners, paper label and attached yellow pencil is rendered with matte material, gentle highlights and real depth. It is rotated diagonally and enlarged until part of it exits the viewport. Later pastel blue and pink variants are surrounded by annotations and stickers.

**Transfer:** Present the new product as a familiar, touchable artifact with subtle wear or material grain. For software, create a dimensional folio, card stack or tool-like container holding a real interface, not a generic floating browser window.

**Build:** Model a rounded rectangular cover with a thin stacked edge, matte roughness and a restrained area-light highlight. Place a cream label with a double dark outline on the front; rotate the group about 15–20 degrees and let the lower edge leave the stage. A minimum SVG version uses offset rounded paths for cover, edge and label, with one soft contact shadow.

### Painted capability environments

**Use:** Immersive edge-to-edge capability chapters.

**Observed:** The object appears open on a lush meadow dotted with tiny flowers, held against a soft blue sky with cream clouds, and resting on pale striped bedding beside a pencil and biscuits. The scenes mix soft painterly texture with believable product volume; an opaque index panel occupies roughly one third of the screen.

**Transfer:** Create original environments associated with ease, curiosity or everyday use. Make the product large and readable, with the busiest scenery away from the text panel.

**Build:** Layer a painted or textured backdrop, a perspective product cutout and a soft cast shadow; place the opaque Capability index above them. For a minimum illustrated version, use irregular SVG grass strokes and small flower clusters, or broad soft cloud shapes, with a consistent hand-painted edge rather than a smooth mesh gradient.

### Handmade margins

**Use:** Annotations around important objects and spare feature clusters.

**Observed:** Uneven dark pen drawings, curving arrows, short handwritten notes and small colorful outlined stickers sit in otherwise empty cream margins. Orange handwriting interrupts the opening serif explanation and introduces the large product-personalization scene.

**Transfer:** Include original marginal notes that point at a real feature. Keep handwriting brief and irregular, subordinate to the main type hierarchy.

**Build:** Draw SVG paths with rounded caps, dark chocolate strokes of about 2px and slight asymmetry. Add a cream cutline around sticker silhouettes and one flat bright fill. Curve arrow shafts with a loose cubic path; rotate short hand-lettered labels a few degrees. Keep most drawings below 110px wide.

### Ruled promise sheet

**Use:** A signature reassurance graphic.

**Observed:** A slightly tilted cream sheet carries pale blue horizontal rules, a pink left margin, dark handwritten short lines and pink cross marks. It casts a small paper shadow. Four widely spaced illustrated tokens with handwritten captions surround it.

**Transfer:** Turn an important set of commitments or boundaries into a tangible handwritten note; use truthful content appropriate to the new product.

**Build:** Use a cream rectangle around 360px wide within a 440px-wide art area; rotate it slightly. Add repeating thin blue SVG lines about 48px apart and one pink vertical margin. Place handwritten statements and small cross or check paths on the rules. Apply a soft downward shadow and position four tiny illustrated emblems near the outer corners.

### Comic human stories

**Use:** Human proof, transition into the closing panel and editorial illustration strips.

**Observed:** Warm comic-style drawings portray people passing a notebook, sharing lunch and working together. Clear dark contours, muted clothing colors and cream interiors replace glossy corporate photography. Office vignettes sit in thin dark rectangular frames; the editorial strip is loosely tilted and extends beyond both edges.

**Transfer:** Illustrate real moments of use, collaboration or care. A minimum version is a few original outlined scenes with flat warm fills and believable gestures, not stock avatar circles.

### Rounded word sculpture

**Use:** Opening headline and monumental landing-page close.

**Observed:** The opening uses dense, soft-edged lowercase lettering in chocolate. The closing uses a nearly full-width darker-orange name artwork about 1344px wide and 373px tall, with subtle inset depth on the tangerine ground.

**Transfer:** Use original custom lettering with rounded irregular terminals. Retain the contrast between a compact two-line opening inscription and an enormous one-line closing sculpture.

**Build:** Convert a heavy rounded lowercase display face to SVG outlines. Slightly vary glyph widths and angles while preserving a tightly packed silhouette. Fill the opening with chocolate; fill the closing with pressed orange and apply a shallow inset effect using an offset blurred alpha mask at low opacity. Scale the closing SVG to the available width inside 48px side margins.

### Icons

**Observed:** The navigation emblem is a 51px by 60px outlined hand sticker with cream backing. Other small symbols are expressive pen drawings or illustrated stickers, not a uniform enterprise icon set.

**Transfer:** Create a distinctive original emblem and a small family of irregular rounded line illustrations. Keep utility symbols secondary and avoid introducing a dense navigation icon vocabulary.

## Section recipes

How recurring sections are built.

### First screen: Inscription and oversized object

**Observed:** A 900px-tall warm-paper stage opens with a small sticker emblem in the upper-left margin. The text cluster starts around one seventh of the page width and occupies a 492px-wide column: an orange handwritten salutation, two tightly stacked lines of chunky lowercase title artwork in a 492px by 164px block, then a 28px/1.4 serif explanation with an orange handwritten interjection. A very large matte notebook enters diagonally from the lower right, taking over roughly the right half and continuing below the frame. Layers run paper canvas, dimensional object, lettering and support, then navigation. A Paper action and muted availability note sit well below the text, still inside the first 900px. The object's full lower edge and subsequent narrative remain below the fold; the repeated upper-right action appears in later scenes rather than competing at the opening.

**Transfer:** Introduce the new product with short rounded title lettering and a touchable original artifact. Without a physical product, make an illustrated dimensional container for the core experience. Preserve the separation between the high text cluster and low action. Editorial letters instead open with the narrow, left-aligned Letter title and prose.

**Avoid:** Do not replace this with a centered SaaS headline above a small screenshot, or shrink the protagonist until its whole outline fits neatly above the fold.

**Text style:** `hero-support` — gelica 400 · 28px/1.4

### Immersive indexed capability

**Observed:** A full-width, approximately screen-height Painted capability environment holds a large product demonstration. Capability index overlays alternate left and right, away from the central object. The statement highlights a few words in one chapter color; the first active row shares that color. Floating navigation stays legible above the scene.

**Transfer:** Choose a small number of meaningful capability chapters, each with its own environment and analogy; the number and order can change.

**Text style:** `feature-heading` — gelica 400 · 36px/1.2

### Scattered feature sketchbook

**Observed:** An airy cream field contains small black doodle-and-caption clusters scattered around a regular serif heading, rather than evenly boxed tiles. Illustrated groups are around 204px wide, with abundant open space between them.

**Transfer:** Use margin-scale illustrated benefits to lighten the transition between major product scenes. Integrate captions into the drawings while retaining readable supporting text.

### Reassurance heading pair

**Observed:** Reassurance paper uses 90px vertical padding. A centered 40px/1.2 heading is followed after 12px by a taupe 24px/1.4 support line. The Ruled promise sheet sits below, with four sparse illustrated corner captions.

**Transfer:** Use this composition for boundaries, reliability or care commitments; choose the commitments that matter for the new audience.

**Text style:** `heading` — gelica 400 · 40px/1.2

### Annotated object gallery

**Observed:** Oversized pastel object variants occupy a horizontally moving paper stage. A 46.1px regular serif heading takes a compact two-line block among the objects. Handmade margins point to details, and some objects are intentionally cut by the viewport.

**Transfer:** Use for tangible variations or different ways to use the product, keeping dimensional objects and annotations at very different scales.

### Human handover

**Observed:** A large comic illustration of two people passing the product spans the width of a faintly ruled cream field. A short 40px regular serif statement occupies remaining space near the top right.

**Transfer:** Show a real moment of trust or exchange using the new product. Preserve the large human gesture and small amount of text.

**Text style:** `heading` — gelica 400 · 40px/1.2

### Plainspoken questions

**Observed:** A 720px centered column begins 96px into the section. A centered heading is separated from the question list by 64px. Question row repeats without individual card shells, with fine dashed separators and a generous 160px bottom inset.

**Transfer:** Use ordinary reader questions, not formal documentation categories.

**Text style:** `heading` — gelica 400 · 40px/1.2

### Story invitation and orange sign-off

**Observed:** Framed comic workplace vignettes surround a centered invitation to read a letter and a Paper action. Below, the Tangerine closing surface overlaps the illustrated strip; Closing panel places a white mission statement and two link groups above a huge tone-on-tone Rounded word sculpture and bottom metadata.

**Transfer:** Close a landing page with a human invitation and a strongly branded material shift. Use the word sculpture as a signature device wherever the new page's narrative places its final brand moment.

**Text style:** `closing-heading` — gelica 400 · 40px/1.5

### Personal letter

**Only for:** editorial letters

**Observed:** A left-aligned 40px/60px title opens a 640px prose measure inside a 720px container, 160px down the page. Text is 22px/40px, paragraphs separated by 40px. An edge-to-edge, tilted comic strip interrupts the text. The ending returns to prose, then Letter sign-off after 96px, with a handwritten orange signature and no commercial footer.

**Transfer:** For founder essays or origin stories, retain the shared cream, chocolate and handwriting vocabulary but use this restrained reading layout instead of the immersive landing-page stage.

**Text style:** `letter-body` — gelica 400 · 22px/40px

## Page flow

**Storyline:** Personal invitation → tangible experience → capability stories → reassurance → human connection → doubts resolved → distinctive sign-off.

### Introduce an unfamiliar product through familiar physical metaphors

1. **Promise** — Inscription and oversized object establishes a personal greeting and familiar artifact.
2. **Product explanation** — A letter-like explanation introduces what the object does before the full media chapters.
3. **Capability stories** — Immersive scenes pair large demonstrations with ruled capability indices.
4. **Reassurance** — Small sketched benefits and a handwritten commitment sheet make utility and boundaries tangible.
5. **Personal relevance** — An annotated object gallery and large human handover illustration connect function to ownership and care.
6. **Objection handling** — A narrow, unboxed question list answers practical doubts.
7. **Closing invitation** — Comic human scenes lead into a letter-reading action, orange mission panel and enormous word sculpture.

**Transfer:** Borrow the emotional progression, not a fixed scene count. Let the product's strongest physical or experiential metaphor determine the chapters.

### Explain the people and motivation behind a product through a personal letter

1. **Personal invitation** — A modest serif title and candid first-person opening establish intimacy.
2. **Human context** — Long-form paragraphs and an overflowing illustrated strip connect the idea to real people.
3. **Motivation** — Short sentences identify the familiar experience worth preserving and improving.
4. **Personal sign-off** — A direct final sentence, orange handwritten signature and author role end on cream without the landing-page footer.

**Transfer:** Use for essays and origin narratives. Keep the typography spacious and make the closing feel signed, not sold.

## Writing

Warm, candid and lightly mischievous. The product is explained through familiar experiences and reassuring boundaries, with enthusiasm that sounds like a person rather than a pitch deck.

**Do not copy:** Do not reuse Superr, SuperrBook, the hand emblem, lettering artwork, team identities, signatures, proprietary illustrations, claims or commitments. Source quotations are tone examples only; replace them with truthful statements for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** A conversational we speaks to you; product chapters sometimes adopt the user's collective us or our to make the benefit feel shared.
- **Rhythm:** Short conversational headlines, often 3–7 words, alternate with one-line reassurance and compact benefits. Editorial passages mix flowing sentences with very short emphatic fragments. Contractions, questions, ampersands and occasional exclamation marks feel natural.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening inscription | An informal introduction rather than a category-defining superlative. | 2–4 words | “meet superrbook” |
| Supporting line | Explain the product in ordinary words with one everyday outcome. | 8–12 words | “It's an AI notebook that makes learning fun” |
| Capability heading | A familiar analogy or a person-like benefit. | 4–9 words | “It’s kinda like magic paper”<br>“It’s a friend who’s got our back” |
| Primary action | A playful first-person expression of intent, not a formal transaction. | 2–4 words | “I call dibs!” |
| Reassurance | Acknowledge a real concern without defensive technical language. | 7–12 words | “We know the no-list is important to you.” |
| Editorial opening | Signal that this is an honest personal account. | Two short sentences | “Let me tell you how we got here.”<br>“Not the polished version. The real one.” |

**Words and phrasing to use:** kinda like; our way; with you in mind; easy-peesy; fun; friend; magic; care

**Avoid:** revolutionary; enterprise-grade; unlock potential; leverage; synergy; best-in-class

**Rules:**

- Lead with what the product feels like to use; explain mechanisms only when needed.
- Make short capability labels concrete verbs plus objects.
- Write reader questions as people actually ask them, including uncertainty and colloquial phrasing.
- Use playful asides sparingly so the main explanation remains clear.
- In editorial writing, let a short fragment punctuate a longer thought.

## Do's and Don'ts

### Do

- Keep core headings at 40px/1.2 regular serif with natural tracking.
- Keep feature statements at 36px/1.2 and color only the meaningful phrase.
- Construct actions as a 20px outer shell around a 16px outlined face.
- Let large objects cross the edges of a 900px visual stage.
- Use 2px chocolate outlines on capability cards, with much softer internal rules.
- Give FAQ content a 720px measure and 64px of separation below its heading.
- Keep orange concentrated in handwritten accents and a dramatic closing field.
- Use original handwriting, sticker details and near-full-width closing lettering to connect the visual chapters.

### Don't

- Do not turn the 12px-corner capability panel into a collection of pill tiles.
- Do not make all headings heavy rounded display type; keep that treatment for lettering artwork.
- Do not substitute pure black for the chocolate default throughout the page.
- Do not use orange-filled conversion buttons; the cream double-layer paper construction is the signature action.
- Do not use glass blur or neon gradients behind the index cards.
- Do not give every section a colored background; cream must remain the connective field.
- Do not reduce human illustration to anonymous circular avatar rows.
- Do not attach the orange commercial footer to a signed editorial letter; it ends with the author and cream space.

## Motion and responsive

### Motion

**Observed:**

- The opening and object-gallery stages use sticky viewport-height containers; the gallery traverses a horizontal object strip within a longer vertical section.
- Declared action transition: all 0.2s cubic-bezier(.4,0,.2,1). Capability card transforms declare .15s with the same easing; question text color declares 0.3s.
- FAQ hover opacity is 0.8. No matched element animations establish a universal looping effect.

**Transfer:**

- Use scroll progression to reveal tangible object details and chapter changes, while keeping the ruled control panel readable.
- Keep a coherent static composition when the object stage is not moving.

**Unknown:**

- Exact scroll-to-object transforms, reveal timing and clip-path choreography are not established.
- Focus-visible and active styles are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1023px, 1024px, 1280px and 1536px.
- Capability titles declare 26px below the large desktop size; FAQ headings declare 24px at the narrow size.
- Capability panels move from absolute desktop overlays toward relative, full-width blocks at narrow widths. Closing corners declare 40px at narrow sizes instead of 56px.

**Transfer:**

- At narrow widths, stack the product scene and its capability index instead of obscuring the product with an overlay.
- Retain a deliberately oversized object and small marginal drawing details without allowing essential copy or actions to leave the viewport.
- Keep the editorial reading measure fluid inside its side padding and let illustration strips overflow independently.

**Unknown:**

- Only the desktop arrangement is visually established; exact narrow-screen object positions and the sticky gallery behavior are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
