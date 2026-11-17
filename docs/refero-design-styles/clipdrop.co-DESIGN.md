# Clipdrop — editorial image playground

## Overview

A white, image-led style that pairs expressive editorial serif headlines with practical sans-serif controls. Charcoal type and pale gray cards make a restrained frame for saturated photography, transformation demos and colorful interface collages. It suits creative software and hands-on product pages, with expansive opening statements and dense, useful capability catalogs.

### Essentials

- Editorial promises, utilitarian details: regular serif headlines at 96px/1.1 and -0.02em tracking contrast with 16px medium sans-serif descriptions and 14px semibold controls.
- The opening is a headline above a film, not a dashboard: a centered two-line promise precedes a 1248×702px, 16px-radius media stage with a central white play control.
- A white shell lets the results supply the color: #ffffff spans the page, #ededed backs cards, and saturated imagery occupies the major media areas; coral and pale blue are confined to compact 40px-high actions.
- Soft rectangles distinguish actions from selectors: ordinary buttons use 12px corners and 12px 20px padding, media and cards use 16px corners, and only demonstration filters use fully rounded pills.
- The capability catalog reads as a contact sheet: three equal columns separated by 8px, each 330px-high card holding 208px of media above a 24px-padded icon, title and description area.
- Show the transformation, not just a decorative picture: include a concrete before/after, edited result or short product film. When footage is unavailable, stage a real input and output in the same rounded frame.
- The ending returns to useful small print rather than a sales billboard: a 60px serif FAQ heading leads into 73px ruled rows, a blue expansion button over a white fade, and a compact four-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral action | `#fa4028` | `--color-conversion` | action | Focused conversion button inside a marketing feature chapter. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue ink | `#24355c` | `--color-expansion-ink` | text | Label and plus icon inside the blue expansion action. |
| Expansion blue | `#c9d7f5` | `--color-expansion` | action | Small disclosure-expansion button, not a section background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer black | `#000000` | `--color-black` | text | Small bold footer column headings. |
| Near black | `#171717` | `--color-strong` | text, border | Footer links and dashed upload border. |
| Headline charcoal | `#2d2d2d` | `--color-ink` | text, border, action | Display headings, navigation and selected demonstration filters. |
| Card charcoal | `#404040` | `--color-card-ink` | text | Card titles, FAQ questions and matching pictograms. |
| Description gray | `#767676` | `--color-muted` | text | Capability descriptions, explanatory paragraphs and inline links. |
| Divider gray | `#dddddd` | `--color-rule` | border, background | FAQ bottom rules and footer separator; neutral-button hover fill. |
| Pale gray | `#ededed` | `--color-card` | surface, action | Capability cards, neutral controls and upload target. |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Page and fixed navigation background; reversed text on coral and selected dark actions. |

## Typography

- **SecondaryFont** — Hero and section headings. A high-contrast editorial serif with tapered details and relatively narrow proportions, set at regular weight. If unavailable, use **Instrument Serif**. Use regular; preserve the compact word shapes and negative tracking. Font stack: "SecondaryFont", "Instrument Serif", Georgia, serif.
- **__primary_e9c525** — Descriptions, navigation, buttons, card titles and footer. A compact contemporary sans-serif, plainly drawn with a substantial x-height and medium-to-bold functional hierarchy. If unavailable, use **Inter**. Use weights 500–700 for most visible text. Font stack: "__primary_e9c525", "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | SecondaryFont | 400 | 96px | 1.1 | -0.02em | Centered opening promise, broken into two deliberate lines. |
| section-heading | SecondaryFont | 400 | 60px | 1.1 | -0.02em | Centered section titles and multiline feature statements; also the left-aligned benefit headline on task-oriented product pages. |
| card-title | __primary_e9c525 | 700 | 20px | 1 | normal | Short capability names next to a pictogram. |
| body | __primary_e9c525 | 500 | 16px | 1.4 | normal | Card descriptions, FAQ answers and practical instructions. |
| support | __primary_e9c525 | 600 | 16px | 1.2 | normal | Short centered feature support and FAQ question labels. |
| control | __primary_e9c525 | 600 | 14px | 1 | normal | Navigation, conversion buttons and expansion actions. |
| footer-link | __primary_e9c525 | 600 | 12px | 1 | normal | Compact footer links. |
| footer-heading | __primary_e9c525 | 700 | 12px | 1 | normal | Footer column names. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| task-oriented product openings | product-label | __primary_e9c525 | 600 | 16px | 1.2 | normal, capitalize | Small product-category label above the serif benefit headline. |
| interactive use-case demonstrations | filter | __primary_e9c525 | 500 | 14px | 1 | normal | Labels inside outlined and selected pills. |

**Notes:**

- The headline face is visually serif despite its generic sans-serif fallback declaration; preserve that serif/sans contrast.
- Large headings share -0.02em tracking and weight 400. Sans-serif copy keeps normal tracking and gains weight rather than scale for functional hierarchy.
- Use a short second line to resolve the opening promise; use a narrower centered multiline measure for a substantial feature statement. Do not apply bold to the serif hierarchy.

## Layout

**Density:** Airy between chapters and compact within catalogs: large media receives breathing room while related tools sit almost edge to edge.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Catalog gutters, icon/title gaps and small internal stacks. |
| 16px | Desktop container side padding, filter gaps and upload icon/instruction spacing. |
| 24px | Card text padding and FAQ row padding. |
| 28px | Feature chapter headline, support, action and collage separation. |
| 32px | Section heading to content and opening headline to media separation. |
| 48px | Product opening top padding and split-column gap. |
| 64px | FAQ and use-case vertical padding; footer column gap. |
| 80px | Breathing space separating large marketing chapters. |

### Containers and grids

- **main container**: max width 1280px · side padding 16px. Centered desktop shell; at 1440px the content occupies 1248px with 96px outer margins. Navigation, catalog and FAQ share these edges.
- **capability grid**: 3 columns · gap 8px. Equal-width capability cards, approximately 411px wide at desktop.
- **feature media**: max width 1000px. Centered collage beneath a narrower centered text and action stack.
- **footer grid**: 4 columns · gap 64px. A compact centered grid around 642px wide, with approximately 112px columns rather than links spread across the whole page.
- **upload target** (only for task-oriented product pages): max width 768px. Centered file-entry area beneath a split text-and-demo opening.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 12px |
|  | cards and media | 16px |
| task-oriented product pages | upload target | 24px |
| interactive use-case demonstrations | filter pills | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Continuous page ground and navigation.

**CSS:** `background: #ffffff; color: #2d2d2d`

**Observed:** No alternating dark bands or raised marketing panels; sections are separated mainly by whitespace.

**Transfer:** Keep the outer shell neutral and let media carry the intense colors.

#### Capability card · level 1

**Use:** Repeated capability links.

**CSS:** `background: #ededed; border-radius: 16px; box-shadow: none`

**Observed:** A single pale-gray rounded block joins the media and lower text area without a stroke.

**Transfer:** Use a flat container, not a floating shadowed card.

#### FAQ fade · level 2

**Use:** Soft disclosure boundary at the bottom of the short FAQ list.

**CSS:** `background-image: linear-gradient(to top, #ffffff, rgba(255, 255, 255, 0)); padding: 16px`

**Observed:** A 72px-high overlay crosses the last visible question and carries the centered expansion control.

**Transfer:** Use this only for a list that really expands; keep the final visible row partly softened.

#### Upload surface · level 1

**Only for:** task-oriented product pages

**Use:** Primary file entry target.

**CSS:** `background: #ededed; border: 2px dashed #171717; border-radius: 24px`

**Observed:** An intentionally simple, wide target rather than a styled form with multiple fields.

**Transfer:** Adapt the interaction to the product's input while retaining the broad centered invitation.

## Components

### Fixed navigation

**Use:** Persistent site access without competing with the page promise.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 60px; z-index: 30; background: #ffffff`

**Text style:** `control` — __primary_e9c525 600 · 14px/1

**Observed:** A compact wordmark sits on the shared left edge, with navigation and a neutral account action aligned right. Text links alternate with filled neutral controls; the tool menu has a down chevron.

**Transfer:** Use a small wordmark and a short functional navigation list rather than a large brand banner.

### Neutral button

**Use:** Menu and account actions.

**CSS:** `background: #ededed; color: #2d2d2d; border-radius: 12px; height: 40px; padding: 12px 20px; display: flex; align-items: center; justify-content: center; gap: 8px`

**Text style:** `control` — __primary_e9c525 600 · 14px/1

**Observed:** The menu variant includes a trailing 20px chevron and uses 18px right padding; the account variant has text only.

**States:** Declared: hover background-color #dddddd; focus-visible not specified.

### Coral conversion button

**Use:** A focused next step within a marketing feature chapter.

**CSS:** `background: #fa4028; color: #ffffff; border-radius: 12px; height: 40px; padding: 12px 20px; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `control` — __primary_e9c525 600 · 14px/1

**Observed:** A single centered action beneath the support sentence; it stays compact relative to the large heading and image.

**States:** Declared: hover background-color rgb(255 122 100/1); focus-visible not specified.

### Capability link card

**Use:** Browse a family of related capabilities.

**CSS:** `background: #ededed; border-radius: 16px; height: 330px; display: flex; flex-direction: column; justify-content: flex-end; position: relative`

**Text style:** `card-title` — __primary_e9c525 700 · 20px/1

**Observed:** The entire card is linked. A full-width 208px-high rounded video preview sits above a 123px text block with 24px padding. A 24px pictogram precedes the single-line title; a muted description follows and is limited to two lines.

**Transfer:** Use an outcome demonstration above a concise capability title and one practical sentence.

### FAQ disclosure row

**Use:** Handle specific practical objections.

**CSS:** `display: flex; align-items: center; gap: 16px; padding: 24px; color: #404040`

**Text style:** `support` — __primary_e9c525 600 · 16px/1.2

**Observed:** A 24px right-pointing chevron precedes the question in a full-width disclosure. Each closed row is 72px tall plus a 1px bottom rule in divider gray. Answers use the body recipe with underlined inline links; the chevron rotates on open.

**States:** Declared: hover on ancestor background-color #ededed; focus-visible not specified.

### Expansion button

**Use:** Reveal additional FAQ content.

**CSS:** `background: #c9d7f5; color: #24355c; border-radius: 12px; height: 40px; padding: 12px 20px 12px 18px; display: flex; align-items: center; justify-content: center; gap: 6px`

**Text style:** `control` — __primary_e9c525 600 · 14px/1

**Observed:** A 20px plus icon sits before the label. The button floats centrally over the FAQ fade, not at the page edge.

**States:** Declared: hover background-color rgb(160 189 251/1); focus-visible not specified.

### Footer link

**Use:** Low-key navigation within the compact footer.

**CSS:** `color: #171717; margin-top: 4px; margin-bottom: 4px`

**Text style:** `footer-link` — __primary_e9c525 600 · 12px/1

**Observed:** Plain text with no filled container; social variants pair the name with a small monochrome icon.

**States:** Declared: hover opacity 0.5; focus-visible not specified.

### Upload dropzone

**Only for:** task-oriented product pages

**Use:** Let the visitor start working immediately.

**CSS:** `background: #ededed; border: 2px dashed #171717; border-radius: 24px; height: 208px; max-width: 768px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 16px`

**Text style:** `body` — __primary_e9c525 500 · 16px/1.4

**Observed:** A 32px upload pictogram is centered above a short instruction. A downward example prompt and four 120px-square rounded photographic samples sit beneath the target, with 16px gaps.

**Transfer:** Provide realistic sample inputs for a new product; use one simple interaction rather than a multi-step form.

### Use-case filter

**Only for:** interactive use-case demonstrations

**Use:** Switch the scene to an audience or application.

**CSS:** `border: 1px solid #2d2d2d; border-radius: 9999px; padding: 8px 16px; height: 32px; display: flex; align-items: center; gap: 8px; color: #2d2d2d`

**Text style:** `filter` — __primary_e9c525 500 · 14px/1

**Observed:** A centered wrapping row of short pills sits between the section heading and demonstration. The selected pill uses headline charcoal fill and white text.

**States:** Declared: hover unselected background-color rgba(45, 45, 45, 0.25); selected hover background-color rgba(45, 45, 45, 0.5); focus-visible not specified.

## Imagery and graphics

### Opening product film

**Use:** Main visual proof directly below the opening statement.

**Observed:** A large landscape photograph/video of a person against a bright blue mural fills the rounded stage. Natural texture, saturated red clothing and real-world surroundings make it feel like creative work rather than abstract software art. A dark translucent veil makes the central white circular play symbol legible.

**Transfer:** Use a real scene with a clearly readable subject and a demonstrable transformation. A still before/after of actual product output is the minimum equivalent when a film is unavailable.

**Build:** Place a landscape still or video in a 16px-radius overflow-hidden frame with a 16:9 aspect ratio. Overlay rgba(51,51,51,0.35) across the media and center a white circular play control with a dark triangular glyph; keep all shading inside the frame.

### Capability demonstration thumbnails

**Use:** The top portion of every capability card.

**Observed:** A varied contact sheet: portrait resizing on a dotted editor backing, surreal generated photography, product imagery with a dark prompt capsule, transparent checkerboard cutouts, and selective-edit brush marks. Pictures are bright and concrete; each thumbnail explains one operation.

**Transfer:** Art-direct distinct examples for each capability instead of repeating a generic interface. Show the smallest credible input/output scene; avoid unreadable full-app windows in these narrow media slots.

### Color-backed integration collage

**Use:** Large proof graphic below a feature statement and conversion action.

**Observed:** A 1000×586px rounded collage places overlapping browser windows over a vivid yellow field, with a handheld phone photo to one side and before/after creative output toward the lower edge. Purple window-edge accents and internal shadows give the artwork depth while the surrounding page stays flat.

**Transfer:** Combine two or three real outputs or interface panels against one saturated color field. A minimum version is one clear output image and one readable interface panel; keep the collage depth inside the artwork rather than shadowing the page's containers.

**Build:** Use a 16px-radius clipped landscape canvas. Fill most of it with saturated yellow, reserve a vertical photographic strip on the left, then overlap rectangular browser panels at different sizes across the center and upper right. Add narrow purple backing rectangles and restrained internal shadows behind the panels.

### Dotted transformation stage

**Only for:** interactive product demonstrations

**Use:** Resizing previews and the larger use-case scene.

**Observed:** A very faint regular gray dot field fades into white. A sharp wide photograph sits in front of a narrower tall extension of the same scene, with softly blurred added background. The dominant front image has rounded corners; the overlapping formats make the operation visible without much text.

**Transfer:** For another product, show two states or formats of the same artifact on the dotted ground. Keep the central output clear and the supporting layer softer, not two unrelated stock images.

**Build:** Create a white ground with radial-gradient(circle, rgba(45,45,45,0.12) 1px, transparent 1px) on a roughly 12px grid. Fade its edges with a white radial mask. Center a narrow vertical image behind a larger landscape image; round both by 16px and use a lightly blurred extension of the same content for the rear layer. Exact dot spacing is less important than the faint editor-paper effect.

### Icons

**Observed:** Compact monochrome pictograms, predominantly filled at 24px next to card titles and disclosure questions. Navigation chevrons are 20px with 2px rounded strokes; footer social marks are 16px. The expansion action uses a 20px plus and the upload target a 32px pictogram.

**Transfer:** Choose simple editing or action metaphors with similar visual weight. Align icons beside sans-serif labels, never as colorful badge containers.

## Section recipes

How recurring sections are built.

### First screen: Headline and film opening

**Observed:** A fixed 60px White canvas navigation sits above the content. The centered regular serif promise starts after 56px of breathing room and spans two lines at 96px/1.1, with a wider first line and a short resolving second line. A 32px gap leads to the Opening product film in the shared 1248px content width. Layers are white page, large rounded photographic stage, dark media veil, then central white play control. Within the first 900px, the entire headline and most of the 702px-tall film are visible; the film continues below the fold and the catalog is later. There is no separate support paragraph or CTA cluster in this opening; play and the navigation are the actions.

**Transfer:** For a new marketing page, pair a two-line result promise with an immediately credible product film or staged input/output visual. Preserve the headline's scale relative to the image and keep the stage wider than any later collage. Task-oriented pages instead use the split product opening and direct input target.

**Avoid:** Do not replace the stage with a floating dashboard, add an eyebrow and two-button sales cluster to the default hero, or put the headline over the photograph.

**Text style:** `display` — SecondaryFont 400 · 96px/1.1 · tracking -0.02em

### Capability contact sheet

**Observed:** A centered section-heading precedes the capability grid by 32px. Capability link cards form three equal columns with 8px gutters; the repeated 330px card heights and media/text split create a dense catalog inside the airy page.

**Transfer:** Use this arrangement for features, workflows or related products. Retain a specific visual demonstration for each card rather than turning it into an icon-only feature grid.

**Text style:** `section-heading` — SecondaryFont 400 · 60px/1.1 · tracking -0.02em

### Centered feature invitation

**Observed:** A narrow centered multiline section-heading leads a support sentence, Coral conversion button and Color-backed integration collage. The stack uses 28px gaps; the artwork is 1000px wide, narrower than the main media stage. An 80px white interval separates it from adjacent chapters.

**Transfer:** Use for a deeper integration, advanced capability or alternate audience. Let the statement explain the benefit and the collage establish credibility; keep the action singular.

**Text style:** `section-heading` — SecondaryFont 400 · 60px/1.1 · tracking -0.02em

### Useful ending

**Observed:** The FAQ section has 64px vertical padding, a centered section-heading and a 32px gap to full-width FAQ disclosure rows. FAQ fade and Expansion button soften the list's end. Below, a 1px divider spans the shared content width; after 40px of space, four small footer columns sit centered within roughly 642px. Bold 12px headings lead semibold 12px links with 8px between neighboring link boxes. A tiny centered copyright line closes the white page.

**Transfer:** Close with genuine questions, compact institutional navigation and a small ownership line. Preserve the contrast between monumental FAQ title and miniature footer; there is no need to insert a second sales hero.

**Text style:** `section-heading` — SecondaryFont 400 · 60px/1.1 · tracking -0.02em

### Split product opening

**Only for:** task-oriented product pages

**Observed:** A small product-label and a left-aligned 60px serif benefit headline occupy the left side; a 448×299px transformation preview sits on the right, separated by 48px. The content begins 48px below navigation. Beneath this split row, a centered Upload dropzone, example prompt and four square examples all fit in the first 900px.

**Transfer:** Use this variant when the page is also an actual entry point to a tool. Put the key input in the opening viewport and give visitors examples to try before explaining every capability.

**Text style:** `section-heading` — SecondaryFont 400 · 60px/1.1 · tracking -0.02em

### Tabbed transformation demonstration

**Only for:** interactive product demonstrations

**Observed:** A full-width faint dotted field backs a centered section-heading, a pill-filter row after 32px, and a large layered image stage after another 32px. The image occupies about 685×673px of the content area. A centered body caption follows after 32px; the whole section uses 64px top and bottom padding.

**Transfer:** Use a short set of applications to explain the same operation across contexts. Keep the same subject across layered formats so the result, not the tab mechanism, remains the focus.

**Text style:** `section-heading` — SecondaryFont 400 · 60px/1.1 · tracking -0.02em

## Page flow

**Storyline:** result promise → tangible demonstration → capability discovery or applications → deeper adoption path → practical objections → compact institutional close

### A broad creative-product marketing landing page

1. **Promise** — A two-line editorial headline names the result and speed.
2. **Product demonstration** — A wide rounded film supplies immediate visual proof.
3. **Capability discovery** — A tightly packed catalog combines preview media with functional labels.
4. **Deeper adoption** — A centered statement, one coral action and a color-backed collage introduce an advanced path.
5. **Objection handling** — Practical FAQ disclosures end in a blue expansion action.
6. **Institutional close** — Four tiny link columns beneath a hairline finish the page without a final conversion banner.

**Transfer:** Use the broad promise to draw visitors in, then move from visible results to specific capabilities and one deeper action. Adapt the number and order of proof chapters to the product.

### A product-specific page that also starts the actual task

1. **Promise** — A small category label and serif benefit headline sit beside a transformation preview.
2. **Immediate activation** — A wide dashed input target and realistic examples let the visitor begin.
3. **Applications** — Filter pills switch a layered demonstration on a faint dotted ground.
4. **Capability discovery** — The shared catalog exposes neighboring operations.
5. **Objection handling** — A shorter FAQ explains the task and its limitations.
6. **Institutional close** — The same miniature footer closes the page.

**Transfer:** For a hands-on utility, replace the film-led opening with a visible input and sample content. Reuse the editorial type, neutral shell and helpful ending rather than making the page resemble a separate application.

## Writing

Direct, optimistic and outcome-led. The big statements promise creative results quickly, while the smaller copy behaves like concise task guidance.

**Do not copy:** Do not reuse Clipdrop or Jasper names, logos, media artwork, product names, exact performance claims, free/HD promises or source-specific API claims as facts for a different product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the visitor as you or your and begin with an imperative when useful. Product descriptions use the product name or a plain functional noun rather than a long corporate introduction.
- **Rhythm:** Headlines are brief result statements, sometimes resolved by a short speed phrase. Cards use short functional titles and one sentence; FAQ answers use a small sequence of concrete verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Imperative result plus a short time-to-value phrase. | 5–10 words | “Create stunning visuals in seconds”<br>“Instantly adapt your images to any social format” |
| Capability description | Name the operation and practical output, in one compact sentence. | 7–16 words | “Resize your images for any social media”<br>“Teleport anything, anywhere with AI” |
| Feature support | One declarative sentence identifying what the product lets the reader do. | 12–20 words | “The Jasper API lets you embed best-in-class AI image models directly into your product.” |
| Action | Verb plus a concrete destination or a simple disclosure label. | 2–5 words | “Explore the API docs”<br>“Show more” |
| Instruction | A literal action invitation, with examples close by. | 5–12 words | “Click or drop a file here to start”<br>“↓ Try with an example” |
| Question | Ask the practical question a visitor would type, not an abstract brand question. | 6–15 words | “How to remove an object from a picture?”<br>“How does the Universal Resizer work?” |

**Words and phrasing to use:** create; instantly; your; try; upload; select; download; resize; remove; explore

**Avoid:** paradigm; synergy; disruptive ecosystem; journey into the future; lengthy corporate self-description

**Rules:**

- Make the operation understandable before naming the underlying technology.
- Use sentence case for benefits and plain noun phrases for catalog titles.
- In answers, move directly from input to action to output.
- Keep descriptions useful enough that the imagery need not explain the entire workflow.

## Do's and Don'ts

### Do

- Keep serif display type at weight 400 with -0.02em tracking.
- Align the major media, catalog and FAQ to the same 1248px content span at desktop.
- Keep ordinary controls at 40px high with 12px corners.
- Give card copy a 24px inset while letting thumbnail media fill the card width.
- Use 8px catalog gutters to preserve the contact-sheet effect.
- Keep saturated page accents small; give rich color to the photographs and collages.
- Use the blue plus action over a 72px white fade for an expandable FAQ list.
- Keep footer links at 12px and the four-column link group much narrower than the main container.

### Don't

- Do not make display headlines bold grotesks; the serif/sans contrast is fundamental.
- Do not spread pale blue across whole chapters; it belongs to the small expansion action.
- Do not turn ordinary buttons into pills; reserve full rounding for demonstration filters.
- Do not add card shadows or heavy strokes to the flat #ededed capability surfaces.
- Do not widen catalog gutters to 24px or 32px; the measured grid is compact at 8px.
- Do not set card descriptions in the heading charcoal; use #767676 for their secondary role.
- Do not spread footer columns across the entire main width or enlarge them into a second navigation bar.
- Do not substitute abstract gradient blobs for the concrete editing/result demonstrations.

## Motion and responsive

### Motion

**Observed:**

- Neutral, coral and blue buttons declare all-property transitions of 0.15s with cubic-bezier(0.4, 0, 0.2, 1).
- FAQ summaries declare all-property transitions of 0.3s with the same curve; the chevron rotates when open.
- The layered demonstration image declares opacity over 1s with cubic-bezier(0.4, 0, 0.2, 1) and a 0.5s delay.
- The input target declares color-related transitions over 0.2s with cubic-bezier(0.4, 0, 0.2, 1).

**Transfer:**

- Use short surface-color changes for compact controls, keeping the page shell still.
- Reserve the slower opacity treatment for changes within the transformation demonstration.

**Unknown:**

- Video playback and scroll-trigger choreography are not specified.
- Focus-visible and active appearances beyond the stated selections are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px.
- Heading classes specify 48px, 60px and 96px opening sizes; section headings specify 36px, 48px and 60px sizes.
- The catalog declares two columns before switching to three at the large breakpoint, with a 4px gap before the medium breakpoint and 8px afterward.
- The product opening switches from a centered vertical stack to left-aligned side-by-side content at the medium breakpoint. Footer columns switch from two to four there.

**Transfer:**

- Follow the declared two-column catalog before the desktop three-column layout; keep the media/text hierarchy intact.
- Stack the task-oriented opening before the input target on narrow screens, keeping its direct interaction easy to find.
- Reduce the headline using the discrete size steps rather than preserving desktop size through horizontal overflow.

**Unknown:**

- Exact rendered mobile wraps, menu interaction and small-screen media framing are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
