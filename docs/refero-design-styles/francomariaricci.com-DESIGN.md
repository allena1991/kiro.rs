# Franco Maria Ricci — the collector’s cabinet

## Overview

A bibliophile’s sensibility turns a commercial site into a sequence of finely staged objects and illustrated essays. Pale paper, ink black and restrained antique gold frame high-contrast serif typography, with plain sans-serif capitals reserved for practical instructions. Rich illustration, close-up material photography and occasional monochrome portraits provide the color and drama; the surrounding interface stays sparse, rectilinear and deliberately spacious.

### Essentials

- A modest title beside an extravagant object: the opening fills 900px at desktop, with roughly 35% reserved for left-aligned copy and 65% for an edge-to-edge illustrated product stage; the title is 42px regular serif rather than oversized advertising type.
- Typography behaves like a fine printed edition: Bodoni-style serif headings at 42px/1.25, descriptive copy at 18px/1.25, and unexpanded normal tracking throughout; only functional labels switch to Arial capitals.
- Actions are typographic punctuation, not filled buttons: 14px/1.25 bold Arial uppercase labels enclosed in literal curly braces, without a rounded container; hover opacity is 0.7.
- The interface is paper, ink and a little gilding: #f6f6f6 and white carry most reading areas; #bc9c5c is confined to headings, selected actions and the closing identity. Broad color belongs to the opening artwork and photographs, not to a rainbow of UI panels.
- Products occupy ruled display cases: three gapless 480px square cells across a 1440px desktop canvas, separated by 1px black rules, with centered 319px square image areas and abundant empty backing.
- Editorial features alternate image and text like facing pages: equal 720px halves, about 800px tall, centered text within two thirds of its half and 48px between major elements; include an inverse near-black feature as a dramatic counterpoint.
- The ending is a publisher’s colophon, not a sales billboard: include a centered gold identity device, a 42px italic serif name, a small motto, then an 80px separation before compact utility columns. Use a newly drawn monogram or restrained seal if the product has no equivalent emblem.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Antique gold | `#bc9c5c` | `--color-gold` | text, accent, action | Editorial titles, closing identity and one action over a dark image; not a general panel fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Printing black | `#000000` | `--color-ink` | text, border, action, background | Primary reading text, structural hairlines, icons and the backing of dark photographic bands. |
| Near-black velvet | `#0a0a0a` | `--color-velvet` | surface, background | The inverse editorial feature paired with a richly colored image. |
| Pale paper | `#f6f6f6` | `--color-paper` | background, surface | Collection grids, alternating editorial panels and long-form reading canvas. |
| White | `#ffffff` | `--color-white` | background, text | Open editorial panels and the closing colophon; inverse text on near-black and photographic surfaces. |

## Typography

- **BodoniSvntytwoITCStd** — Titles, descriptions, navigation identity and utility links; Book and BookIt provide upright and true italic cuts. High-contrast modern serif with fine hairlines, compact proportions and a literary italic. If unavailable, use **Bodoni Moda**. Use regular 400 and italic 400; preserve compact line lengths and normal tracking. Font stack: "BodoniSvntytwoITCStd", "Bodoni Moda", "Bodoni MT", serif.
- **Arial** — Uppercase actions, utility headings and collection descriptors. Plain utilitarian grotesk; deliberately subordinate to the serif. Font stack: "Arial", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening-title | BodoniSvntytwoITCStd | 400 | 42px | 40px | normal | Compact left-aligned first-screen title. |
| heading | BodoniSvntytwoITCStd | 400 | 42px | 1.25 | normal | Editorial section titles in gold, black or white according to surface. |
| identity-closing | BodoniSvntytwoITCStd | 400 italic | 42px | 1.25 | normal | Centered gold closing name. |
| identity-small | BodoniSvntytwoITCStd | 400 | 22px | 1.25 | normal | Upper-right navigation identity. |
| page-number | BodoniSvntytwoITCStd | 400 italic | 22px | 1.25 | normal | Current collection index, with smaller slash and total. |
| body | BodoniSvntytwoITCStd | 400 | 18px | 1.25 | normal | Centered editorial feature descriptions and small closing motto. |
| opening-support | BodoniSvntytwoITCStd | 400 | 16px | 1.25 | normal | Opening description and short photographic band support. |
| collection-label | BodoniSvntytwoITCStd | 400 italic | 16px | 1.25 | normal, uppercase | Collection names and category tabs above ruled product cells. |
| action | Arial | 700 | 14px | 1.25 | normal, uppercase | Curly-braced conversion links and social links. |
| utility-heading | Arial | 400 | 14px | 1.25 | normal, uppercase | Footer column titles and secondary collection descriptors. |
| utility-text | BodoniSvntytwoITCStd | 400 | 14px | 1.25 | normal | Footer links, short credo and newsletter text. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| long-form editorial pages | essay-body | BodoniSvntytwoITCStd | 400 | 20px | 1.25 | normal | Left-aligned paragraphs in a two-column essay composition. |
| long-form editorial pages | essay-emphasis | BodoniSvntytwoITCStd | 700 | 20px | 1.25 | normal | Selected phrases within the essay, not standalone promotional statistics. |

**Notes:**

- Use one serif family across display and reading sizes; the distinction comes from scale, alignment, italic cut and color rather than heavy display weights.
- The opening title has tighter leading than later headings. Preserve its 40px line height instead of applying the general 1.25 heading ratio everywhere.
- Functional capitals are small and untracked. Avoid turning them into widely spaced luxury labels.
- True italic appears in collection labels, page numbering and the final name; long-form essays may also italicize work titles.

## Layout

**Density:** Airy at the section scale and compact inside utility groups; objects receive far more space than their labels.

### Spacing

**Spacing system:**

- **horizontal-step** 8px, horizontal — Horizontal spacing and padding follow an 8px step.

| Value | Use |
| --- | --- |
| 8px | Small icon gaps and checkbox-to-text separation. |
| 16px | Header action spacing and consent separation. |
| 20px | Opening title-to-description spacing; footer name separation and utility title-to-links gap. |
| 32px | Desktop header vertical padding. |
| 40px | Desktop outer page gutter. |
| 48px | Vertical spacing inside editorial features and padding above and below collection headers. |
| 64px | Colophon vertical padding and collection index inset. |
| 80px | Editorial panel breathing room and identity-to-utility separation. |
| 112px | Essay column gap and outer text inset. |
| 128px | Long-form chapter separation and ornament-to-prose spacing. |

### Containers and grids

- **full-bleed-canvas**: side padding 0px. No desktop maximum-width cap; media and ruled structures reach both viewport edges.
- **utility-container**: side padding 40px. Header and footer content inset from the full desktop canvas.
- **editorial-pair**: 2 columns · gap 0px. Equal halves across the canvas; 720px each at desktop. Text is centered in a 480px inner width against a full-height image.
- **collection-grid**: 3 columns · gap 0px. Three contiguous square cells; each is 480px wide at desktop, with 319px square media centered inside.
- **essay-grid** (only for long-form editorial pages): 2 columns · gap 112px · side padding 112px. Heading and prose occupy opposing columns. Visible prose width is 552px at desktop, with the title side left largely open.

## Corner radius

| Element | Radius |
| --- | --- |
| Ruled cells and fields | 0px |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Collection areas and long-form reading.

**CSS:** `background-color: #f6f6f6`

**Observed:** Continuous flat paper without texture simulation or depth effects.

**Transfer:** Let the photographs supply material texture.

#### White editorial field · level 0

**Use:** Light text panels and closing identity area.

**CSS:** `background-color: #ffffff`

**Observed:** A clean surface contrasted against pale-paper sections and large image blocks.

**Transfer:** Keep the change in paper tone subtle.

#### Inverse editorial field · level 0

**Use:** A dramatic feature alongside rich art.

**CSS:** `background-color: #0a0a0a; color: #ffffff`

**Observed:** One half of a facing-page composition; text and a compact identity graphic sit centered.

**Transfer:** Pair this field with the most visually detailed asset rather than filling the entire page black.

#### Ruled display field · level 0

**Use:** Gapless collections and editorial boundaries.

**CSS:** `background-color: #f6f6f6; border-right: 1px solid #000000; border-bottom: 1px solid #000000`

**Observed:** Hard straight seams, not inset floating cards; no radius or interface shadow.

**Transfer:** Share borders between adjacent cells to avoid double-width rules.

#### Dark photographic band · level 0

**Use:** Collection-level closing invitation before the colophon.

**CSS:** `background-color: #000000; color: #ffffff; border-top: 1px solid #000000`

**Observed:** Low-key full-width object photography carries white headings and a small gold action.

**Transfer:** Darken through lighting and image grading while retaining visible fabric, paper and edge detail.

## Components

### Masthead

**Use:** Sparse navigation above the opening scene.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 32px 40px`

**Text style:** `identity-small` — BodoniSvntytwoITCStd 400 · 22px/1.25

**Observed:** Small circular line emblem at left; right-aligned two-line identity, outline shopping bag and three-line menu at right. The emblem occupies 64px square; the second identity line is italic and subdued.

**Transfer:** Use a custom compact monogram and the new product’s category beneath its name.

### Braced action

**Use:** Primary and secondary conversion links.

**CSS:** `color: #000000; background: transparent; font-family: Arial, sans-serif; font-size: 14px; font-weight: 700; line-height: 1.25; text-transform: uppercase; transition: opacity 0.3s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `action` — Arial 700 · 14px/1.25 · uppercase

**Observed:** A literal opening and closing curly brace frame a short label. The action is a text line, not a filled control; inverse panels use white, and the dark photo band uses gold.

**States:** Declared: hover opacity 0.7; focus-visible not specified.

**Transfer:** Keep the braces even when translating the action.

### Collection header

**Use:** Introduce or switch a collection above a product row.

**CSS:** `border-top: 1px solid #000000; border-bottom: 1px solid #000000; padding: 48px 0px; text-align: center`

**Text style:** `collection-label` — BodoniSvntytwoITCStd 400 italic · 16px/1.25 · uppercase

**Observed:** Centered italic capitals; one version adds a directly adjacent sans-serif descriptor, another distributes an index at left and two category tabs across the width.

**Transfer:** Use a descriptive grouping name rather than a giant heading.

### Object cell

**Use:** Quiet browseable product display.

**CSS:** `border-right: 1px solid #000000; border-bottom: 1px solid #000000; background-color: #f6f6f6; aspect-ratio: 1 / 1`

**Observed:** Square tiles contain a centered square image area with a small front-facing object inside it. The resting view prioritizes the object, not a visible price-and-button stack.

**Transfer:** For software, use a single carefully framed screen or physical output of the tool rather than a miniature dense dashboard.

### Facing-page feature

**Use:** Explain a featured offer, collection or story.

**CSS:** `display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); border-top: 1px solid #000000`

**Text style:** `heading` — BodoniSvntytwoITCStd 400 · 42px/1.25

**Observed:** Equal-height image and text halves alternate sides. In the text half, a compact logo or label may precede a gold title, centered prose and Braced action. Its content occupies two thirds of the half; major groups are 48px apart.

**Transfer:** Describe one meaningful product quality at a time; let the object or contextual image carry half the explanation.

### Footer link

**Use:** Compact utility navigation.

**CSS:** `color: #000000; font-size: 14px; line-height: 1.25; transition: opacity 0.3s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `utility-text` — BodoniSvntytwoITCStd 400 · 14px/1.25

**Observed:** Serif links form tight vertical lists beneath uppercase sans-serif column headings; they have no enclosing panel.

**States:** Declared: hover opacity 0.7; focus-visible not specified.

### Newsletter line

**Use:** Email entry inside the colophon utility row.

**CSS:** `display: flex; align-items: center; border-bottom: 1px solid #000000; height: 35px; background: transparent; transition: all 0.15s cubic-bezier(0, 0, 0.2, 1)`

**Text style:** `utility-text` — BodoniSvntytwoITCStd 400 · 14px/1.25

**Observed:** An unboxed email field shares its underline with a small rightward submit arrow. The desktop column is 272px wide; consent sits below and social Braced actions follow.

**Transfer:** Keep a visible accessible field label and preserve the single-line visual construction.

### Consent square

**Use:** Newsletter consent beside compact explanatory copy.

**CSS:** `width: 12px; height: 12px; border: 1px solid #000000; margin-right: 8px`

**Observed:** Tiny square aligned with the first line of consent text; no rounded checkbox styling.

**Transfer:** Use a real keyboard-operable checkbox while retaining the fine square outline.

### Identity colophon

**Use:** The shared page ending.

**CSS:** `padding: 64px 40px; background-color: #ffffff; text-align: center`

**Text style:** `identity-closing` — BodoniSvntytwoITCStd 400 italic · 42px/1.25

**Observed:** A centered gold emblem above the italic name and small motto. After 80px, a left-aligned lower row contains a short credo and action, information links, useful links, site/language controls and newsletter. The desktop ending is about 635px tall.

**Transfer:** Retain the ceremonial centered identity and practical lower tier even for a small product.

### Carousel navigation

**Use:** Quiet browsing control at the base of the opening scene.

**CSS:** `display: flex; align-items: center; justify-content: flex-end; column-gap: 8px`

**Text style:** `body` — BodoniSvntytwoITCStd 400 · 18px/1.25

**Observed:** Long fine arrows bracket a current/total count at the lower-right edge. Arrow artwork is 32px wide and 7px high; controls sit roughly 16px from the bottom.

**Transfer:** Use the counter only for actual multiple scenes; retain a deliberate lower-edge finish for a single scene.

## Imagery and graphics

### Object within its own illustration

**Use:** Signature opening artwork and featured-product media.

**Observed:** A black cloth-bound object with gold lettering stands front-on over a much larger illustration taken from its cover. Fine graphite-like bamboo lines and watery blue-green light fill the backdrop; the left copy field is a matching muted blue-green. The product is crisp, dimensional and dominant while the backdrop bleeds to the edges.

**Transfer:** Stage the new product over an enlarged detail of its own material, output or visual world. The minimum equivalent is a clean front-facing object photograph or screen on a coherent full-bleed detail image, with the copy field picking up one subdued color from it.

**Build:** Create a full-height two-part composition, roughly 35:65. Fill the right side with a cover-detail image using object-fit: cover; center the clean object layer over it at roughly 45% of the right-side width and 65% of the scene height. Preserve real contact shading in the asset rather than adding a UI card shadow. Match the flat left field to a muted color in the backdrop; place all type above the imagery.

### Catalog object portraits

**Use:** Repeated collection cells.

**Observed:** Small frontal covers are isolated on near-white backing, with generous space on every side. Black and gold objects alternate with narrow colored covers; color resides inside the object rather than behind each tile.

**Transfer:** Use consistent object scale, camera angle and quiet backing across the row. A flat screenshot with a meaningful silhouette is preferable to an arbitrary stock lifestyle photo.

### Material and cultural detail

**Use:** Large editorial image halves and long-form interludes.

**Observed:** Close views of paper, cloth, gold printing, open spreads, historic paintings and collections. Images retain grain, age, fine linework and natural color. Layouts alternate large square images with wide landscape images, without rounded clipping.

**Transfer:** Show the product’s making, materials, output and setting at intimate scale. Preserve real surface detail instead of replacing it with glossy generic renders.

### Monochrome human context

**Use:** An editorial feature giving the product a human origin.

**Observed:** A black-and-white portrait is composed deep inside an architectural interior, with the person low in the frame and the surrounding space doing much of the storytelling.

**Transfer:** Photograph a maker or user in their actual working environment, retaining architectural depth and generous context.

### Low-key collection panorama

**Use:** Full-width closing image invitation.

**Observed:** A shelf-like row of tall black volumes and a patterned box fills a roughly 689px band. Soft gray upper space allows white title and support at opposite corners; the gold action sits low at right. The dark image retains tactile cover patterns.

**Transfer:** Photograph a family of products or outputs in a single low-key panorama, leaving clear tonal space above and at the action edge.

### Closing identity ornament

**Use:** Signature ceremonial identity above the utility footer.

**Observed:** A delicate gold heraldic seal is centered at 160px by 142px, separated from its italic name by 20px. The seal is the decorative climax of an otherwise sparse interface.

**Transfer:** Use an original monogram, maker’s stamp or geometric seal. A restrained line-art monogram inside a fine circular frame is the minimum acceptable substitute.

**Build:** Draw an original SVG using the gold palette color: a central initial or compact mark, one thin enclosing oval and a sparse symmetrical set of leaf-like strokes. Fit it within 160px by 142px, leave its interior unfilled, and center it above the name. Avoid adding shadows or a colored badge background.

### Icons

**Observed:** Fine black interface marks: 26px by 21px shopping bag with 1px butt-ended strokes; menu made from 31px hairlines; 32px by 7px carousel arrows and a 12px by 14px newsletter arrow. Decorative identity marks are separate from interface icons.

**Transfer:** Use sparse straight-line SVG controls in black, without circular button backplates; keep arrows long and delicate.

## Section recipes

How recurring sections are built.

### First screen: Illustrated object opening

**Observed:** The first 900px form a complete full-height scene. Masthead overlays the upper edge. A muted blue-green copy field takes approximately the left 35%, while the remaining width is an illustrated setting with a front-facing black object centered over it. Back-to-front layers are flat copy field and enlarged illustration, then object with natural shading, then navigation and text. The 42px Opening-title sits near the upper-left below the emblem, followed by a narrow 16px description and one Braced action with about 20px separations. The object occupies roughly two thirds of the scene height. The title, support, action, whole object and lower-right Carousel navigation are all visible; the collection row begins below the fold.

**Transfer:** Use one flagship product or tangible output as the object, and enlarge one compelling detail as its environment. If no illustration exists, use a tightly photographed material or output detail with a coordinated flat copy field. Long-form editorial pages instead open with a 42px title in the left column and 20px prose in the right, allowing the first major image to begin near the fold.

**Avoid:** Do not turn this into a centered giant slogan above a small floating screenshot, or place a large opaque navigation bar over the illustration.

**Text style:** `opening-title` — BodoniSvntytwoITCStd 400 · 42px/40px

### Ruled collection shelf

**Observed:** Collection header sits directly on a three-column Object cell row. Header padding is 48px vertically; each cell is square with a centered 319px media area. One header uses category tabs and an italic current-page number; another stacks a small italic name over an uppercase descriptor.

**Transfer:** Present a small curated set of editions, configurations or outputs; preserve equal cells and spare resting-state content.

**Text style:** `collection-label` — BodoniSvntytwoITCStd 400 italic · 16px/1.25 · uppercase

### Alternating editorial spreads

**Observed:** Facing-page feature alternates the image side across successive sections. Text halves use a gold 42px heading, 18px centered prose, compact identity art when relevant, and Braced action spaced by 48px. Image halves fill the whole 720px by 800px area. One spread switches to Inverse editorial field with white type.

**Transfer:** Pair one concise argument with one rich asset. The inverse spread should feel like a special plate in the same publication, not a separate design system.

**Text style:** `heading` — BodoniSvntytwoITCStd 400 · 42px/1.25

### Collection panorama invitation

**Observed:** Dark photographic band spans the canvas before the colophon. White 42px title is placed high left; 16px support sits high right, and a gold Braced action sits low right over the low-key collection image. The band has 48px upper and 40px lower breathing room.

**Transfer:** Use this device to invite exploration of the wider range or a deeper archive without introducing a large filled CTA.

**Text style:** `heading` — BodoniSvntytwoITCStd 400 · 42px/1.25

### Ceremonial practical ending

**Observed:** Identity colophon closes both page types. The centered seal, gold italic name and gold 18px motto form the upper tier; a compact utility row begins 80px later, containing credo, links, language and Newsletter line. There is no separate oversized final sales headline.

**Transfer:** Close with the product’s identity and a compact expression of purpose, then give visitors practical ways to continue.

**Text style:** `identity-closing` — BodoniSvntytwoITCStd 400 italic · 42px/1.25

### Essay chapter pair

**Only for:** long-form editorial pages

**Observed:** Paper canvas carries a two-column heading/prose pair with 112px gap and insets. Alternate chapters place a small black ornamental image above the left-hand prose, while the heading moves to the right over a 1px horizontal rule. Ornament images occupy 128px by 130px areas, with 128px before prose. Chapter gaps are 128px. Large artwork and product photographs interrupt the text at full width.

**Transfer:** Use for origin, craft or process narratives, not as the default sales layout. Replace ornaments with original small printer-like marks tied to each chapter.

**Text style:** `essay-body` — BodoniSvntytwoITCStd 400 · 20px/1.25

## Page flow

**Storyline:** Flagship object or editorial premise → curated breadth → deeper illustrated arguments → wider-world invitation → identity and practical continuation.

### A commercial landing page that makes browsing feel like collecting

1. **Promise** — Full-height illustrated object opening with a single braced conversion link.
2. **Range preview** — A ruled three-object shelf under a compact tabbed collection header.
3. **Editorial distinction** — An inverse facing-page feature followed by another restrained collection shelf.
4. **Capability chapters** — Alternating light spreads explain selected objects, output and human origin.
5. **Closing invitation** — Low-key collection panorama with a gold text action.
6. **Practical continuation** — Ceremonial identity colophon, utility links and understated newsletter.

**Transfer:** Use the rhythm of curated objects and deeper arguments, varying the number and order of spreads for the offer.

### An illustrated editorial story establishing depth, craft and point of view

1. **Premise** — Two-column title and essay opening below the sparse masthead.
2. **Visual immersion** — Full-width art detail and object photography shown at generous scale.
3. **Argument chapters** — Alternating heading/prose pairs and ornament-led chapters with occasional bold phrases.
4. **Contextual proof** — Material details, publications, portraits and environmental photographs support the narrative.
5. **Closing image** — A large environmental image completes the editorial narrative before the shared colophon.
6. **Practical continuation** — The same centered identity and compact footer used by the commercial layout.

**Transfer:** Use for a product’s origin, methods or cultural context; replace the long historical sequence with only the chapters the new story merits.

## Writing

Cultivated, descriptive and assured, with the confidence of an editor selecting worthwhile objects. Sensory qualities and concrete cultural or material detail do the persuading; practical actions remain brief and direct.

**Do not copy:** Do not reuse the publisher’s name, heraldry, logos, artwork, edition titles, historical facts, quotations, superlatives or claims as assets or claims for another product. Source examples illustrate voice only.

- **Addressing the reader:** Mostly impersonal third-person description. Direct imperatives appear in actions; the reader is invited to look and discover rather than addressed continuously as 'you'.
- **Rhythm:** Titles are short nominal phrases, often two to five words. Supporting copy can be one richly qualified sentence or two compact paragraphs; long-form writing uses longer sentences, parenthetical turns and occasional rhetorical questions. No breathless exclamation rhythm.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening title | Name the featured object plainly; use a period to separate creator or category from title when useful. | 2–5 words | “Milo Manara. Visioni” |
| Editorial heading | A concise thematic phrase with literary resonance. | 2–4 words | “Letteratura e Immagini”<br>“Il piacere dei testi” |
| Support | Describe material, experience and significance with specific nouns rather than generic benefits. | One sentence or two short paragraphs | “La storia millenaria del Castello di Tabiano in un itinerario attraverso le trasformazioni architettoniche, storiche e artistiche di questa antica fortezza feudale.” |
| Primary action | A direct imperative inside curly braces. | 2–4 words | “{ Ordina ora }”<br>“{ SCOPRI DI PIÙ }” |
| Closing motto | Compress a point of view into a short category-as-craft phrase. | 3–5 words | “Editoria come arte” |

**Words and phrasing to use:** material nouns; precise craft terms; collezione; eleganza; immagini; scopri; careful descriptions of texture and form

**Avoid:** disruptive; game-changing; 10x; hurry; best-in-class; generic innovation slogans

**Rules:**

- Let a description explain why something deserves attention rather than asserting excellence without detail.
- Keep the practical verb in the action, not in every heading.
- Use italic for titles and conceptual emphasis in essays; reserve bold for a few genuinely important phrases.
- Translate the cultivated register naturally instead of imitating ornate Italian syntax word for word.

## Do's and Don'ts

### Do

- Keep general editorial headings at 42px, weight 400 and 1.25 line height.
- Preserve the opening’s asymmetric roughly 35:65 copy-to-media balance.
- Use 1px black shared rules around contiguous display cells.
- Keep feature prose near 480px wide within a 720px half.
- Separate editorial text groups by 48px rather than packing them into a compact sales card.
- Set conversion labels in 14px bold Arial capitals enclosed by braces.
- Give the closing identity 64px vertical padding and an 80px pause before utilities.
- Keep artwork rich in visible texture while UI fields remain flat.

### Don't

- Do not turn antique gold into broad section fills; it is a lettering and identity accent.
- Do not round the square collection cells or add elevated card shadows.
- Do not replace the serif body with a general-purpose sans-serif throughout.
- Do not add expanded letter spacing to the 14px utility capitals.
- Do not raise commercial headings to 80px when the object should carry the scale.
- Do not apply the essay’s 20px left-aligned paragraphs to every centered feature panel.
- Do not give every catalog item a colored backdrop or a permanently visible stack of action buttons.
- Do not flatten material photography into uniformly glossy, textureless mockups.

## Motion and responsive

### Motion

**Observed:**

- Braced actions and ordinary utility links declare opacity transitions of 0.3s with cubic-bezier(0, 0, 0.2, 1), and hover opacity 0.7.
- The newsletter underline wrapper declares an all-property transition of 0.15s with cubic-bezier(0, 0, 0.2, 1).
- The opening has multiple scenes with thin arrow controls and a current/total counter.

**Transfer:**

- Keep interaction feedback subordinate to the editorial content: subtle text fading and restrained field adjustments preserve the printed-page character.

**Unknown:**

- Carousel autoplay interval, scene-transition choreography and scroll-reveal timing are not established.
- No visible focus-visible treatment is established for the text actions.

### Responsive

**Observed:**

- Styles declare width breakpoints at 768px, 1024px, 1280px, 1441px and 1920px.
- Editorial headings declare a 32px base size and 42px desktop size.
- Collection layouts declare two columns at the medium breakpoint and three at the larger breakpoint; editorial pairs declare two columns from the medium breakpoint.

**Transfer:**

- On narrow layouts, retain the object-first visual argument by stacking the illustrated stage and compact text rather than shrinking both into unreadable columns.
- Allow the colophon utilities to stack while keeping its emblem/name/motto centered.
- Keep the collection hairline system intact as the grid reduces its column count.

**Unknown:**

- Exact mobile hero proportions, menu-open design and artwork positioning are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
