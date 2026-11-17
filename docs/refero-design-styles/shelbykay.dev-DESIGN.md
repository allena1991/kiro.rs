# Shelby Kay — earthbound typographic choreography

## Overview

An earthy, light editorial style with outsized grotesk lettering and unusually small, matter-of-fact supporting text. Cream, olive, dusty taupe, peach and blue-grey create distinct chapters, while vivid website imagery supplies most of the visual variety. It suits design-led products and independent services with a substantial visual body of work; dense image indexes alternate with almost empty typographic stages.

### Essentials

- Identity becomes spatial lettering: a 265px uppercase Ranade headline at weight 400 and 0.9 line height stretches across the opening, with a second fragment turned vertically at the right edge.
- The opening is an atmospheric poster rather than a centered sales stack: full-bleed nature footage at 0.1 opacity on cream, a 16px/1.25 support line near the upper left, and 14px uppercase navigation along the bottom of a 900px stage. Use softly washed still photography when footage is unavailable.
- Actions are bare typographic marks, not filled buttons: 14px uppercase bold links, no rounded enclosure, and a 1px background underline treatment; the detail-page return control is only 32px high.
- Color belongs to entire chapters rather than badges: cream #efe6d9, taupe #afa199, peach #d6b292 and slate #7b8785 cover full-width sections. Olive #737955 is reserved for monumental opening lettering; brighter hues live mainly within showcased media.
- Proof reads like an archive contact sheet: four columns of rectangular media with 45px gaps, an independent 168px index rail, and small peripheral identifiers. Use real product views or process photographs when there is no portfolio.
- The final action is a word sculpture: 158.4px bold cream fragments spread left and right over slate, with a smaller 83.2px central symbol and three 14px metadata anchors at the bottom. Recompose the new contact address or conversion phrase into this device rather than replacing it with a conventional footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Moss lettering | `#737955` | `--color-olive` | text, accent | Monumental identity lettering in the opening. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft clay | `#d6b292` | `--color-peach` | background | Full-width capability and credibility chapter. |
| Weathered blue-grey | `#7b8785` | `--color-slate` | background, border | Closing action stage, selection treatment and declared dashed keyboard-focus outline. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Dark olive ink | `#393c2a` | `--color-ink` | text, link, action, surface | Default text and underline color across the light chapters; dark backing for tonal portrait imagery. |
| Dusty taupe | `#afa199` | `--color-archive` | background | Full-width media archive backdrop. |
| Warm cream | `#efe6d9` | `--color-canvas` | background, text | Opening canvas and reverse lettering in the closing stage. Also used at 50% opacity for the detail-view surround. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| project detail views | Veiled taupe | `#b4a79e` | `--color-detail-panel` | surface | Visible taupe panel made with #afa199 at 92% opacity over cream. |

## Typography

- **Ranade** — Identity lettering, chapter headings and closing action sculpture. Broad, blunt sans-serif with open counters; the monumental opening uses regular weight while smaller chapter labels and the closing use bold. If unavailable, use **Manrope**. Use 400 and 700; preserve broad proportions and test line breaks before adjusting size. Font stack: "Ranade", "Manrope", Helvetica, arial, sans-serif.
- **Switzer** — Supporting prose, navigation, indexes, capability lists, credits and metadata. Compact contemporary grotesk, predominantly medium weight with bold labels. If unavailable, use **Inter**. Use 500–700; keep small text compact without adding tracking. Font stack: "Switzer", "Inter", Helvetica, arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| identity-display | Ranade | 400 | 265px | 0.9 | normal, uppercase | fixed | Oversized identity fragments across the opening and rotated at its right edge. |
| closing-display | Ranade | 700 | 158.4px | 1 | normal, uppercase | fixed | Large link fragments distributed over the closing action stage. |
| closing-symbol | Ranade | 700 | 83.2px | 1 | normal, uppercase | fixed | Central connector symbol between closing fragments. |
| chapter-heading | Ranade | 700 | 24px | 1.2 | normal, uppercase | fixed | Short section headings; dark on warm chapters, cream and centered in the closing stage. |
| intro | Switzer | 600 | 16px | 1.25 | normal | fixed | Two-line positioning statement below the opening lettering. |
| label-bold | Switzer | 700 | 14px | 1.2 | normal, uppercase | fixed | Opening navigation, section sublabels and small date marker. |
| label | Switzer | 500 | 14px | 1.2 | normal, uppercase | fixed | Capability lists, proof-item names and bottom metadata. |
| body | Switzer | 500 | 14px | 1.2 | normal | fixed | Short descriptions, values lists, supporting links and credits. |
| index-link | Switzer | 600 | 14px | 1.3 | normal | fixed | Compact title-case links in the archive index. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| project detail views | detail-heading | Ranade | 400 | 28px | 1 | -0.02em, uppercase | size clamp(1.1rem, 2.25vw, 1.4rem) | Compact project heading beside large scrolling media. |
| project detail views | detail-action | Switzer | 600 | 14px | 1.2 | normal, uppercase | fixed | Metadata keys and the external action. |
| project detail views | return-link | Switzer | 500 | 12px | 1.2 | normal, uppercase | fixed | Small return control on the top-right surround. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The contrast is deliberately extreme: 265px identity lettering sits beside 14–16px information, without a ladder of medium-sized marketing headlines.
- Keep tracking normal throughout the core system. Only the 28px detail heading tightens to -0.02em.
- Use uppercase for structural labels and sculptural lettering, not for descriptive paragraphs. Short title-case archive names remain readable as a dense list.

## Layout

**Density:** Airy at the chapter scale and compact within information groups: large empty fields surround tightly stacked 14px text.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Underlying grid gutter and compact detail metadata gaps. |
| 12px | Return-link horizontal padding and closing bottom inset. |
| 16px | Opening bottom inset and detail title-to-description rhythm. |
| 20px | Main desktop side padding. |
| 32px | Top and left surround of detail overlays. |
| 40px | Closing top padding and archive bottom padding. |
| 45px | Archive media grid gaps and detail media separation. |
| 64px | Capability chapter title offset from its top. |
| 80px | Separation before the second offset information group. |
| 112px | Capability title-to-first-information-group interval. |
| 128px | Capability chapter bottom padding. |
| 160px | Sticky detail text top padding. |
| 200px | Deep separation before the lower credibility block. |

### Containers and grids

- **container**: max width 1800px · side padding 20px. Wide desktop content container using a 32-column grid with 8px gutters. Archive media use four columns with 45px gaps beside a 168px index rail; detail views pair 684px media with text capped at 480px.

## Corner radius

| Element | Radius |
| --- | --- |
| media-and-actions | 0px |

## Surfaces and depth

### Surfaces

#### Cream canvas · level 0

**Use:** Opening and base page surface.

**CSS:** `background-color: #efe6d9`

**Observed:** Flat warm background beneath a faint atmospheric image layer.

**Transfer:** Keep the canvas warm rather than pure white.

#### Archive field · level 0

**Use:** Image-index chapter.

**CSS:** `background-color: #afa199`

**Observed:** An uninterrupted matte field behind many separately framed media items.

**Transfer:** Use the whole surface to organize proof without adding individual text cards.

#### Clay field · level 0

**Use:** Capability and credibility chapter.

**CSS:** `background-color: #d6b292`

**Observed:** Flat peach with dark olive text and no dividers or raised panels.

**Transfer:** Separate sparse factual information through offset grid positioning and space.

#### Slate closing stage · level 0

**Use:** Monumental final action.

**CSS:** `background-color: #7b8785; color: #efe6d9`

**Observed:** A full viewport of muted slate with cream lettering and minimal bottom metadata.

**Transfer:** Let the conversion text become the dominant visual object.

#### Detail surround · level 1

**Only for:** project detail views

**Use:** Viewport overlay around the project presentation.

**CSS:** `background-color: rgba(239, 230, 217, 0.5); backdrop-filter: blur(8px); padding: 32px 0px 0px 32px`

**Observed:** An inset top-and-left frame leaves a narrow cream return strip; the inner content reaches the right and bottom edges.

**Transfer:** Keep this treatment for immersive drill-downs rather than the default landing page.

#### Detail panel · level 2

**Only for:** project detail views

**Use:** Inner media-and-description presentation.

**CSS:** `background-color: rgba(175, 161, 153, 0.92); border-radius: 0px; box-shadow: none`

**Observed:** A translucent taupe plane carries scrolling media on the left and fixed-feeling information on the right.

**Transfer:** Keep the project media's own colors inside this neutral frame.

## Components

### Bottom navigation

**Use:** In-page orientation in the opening.

**CSS:** `display: grid; grid-template-columns: repeat(3, 1fr); color: #393c2a`

**Text style:** `label-bold` — Switzer 700 · 14px/1.2 · uppercase

**Observed:** Three bare text anchors form a low horizontal rail at the left, with a separate year marker farther right. There is no top navigation bar or logo lockup.

**States:** Declared: focus-visible outline #7b8785 dashed 1px; underline background-size transition .4s cubic-bezier(.76, 0, .24, 1).

**Transfer:** Use three concise destination nouns appropriate to the product.

### Underline link

**Use:** Text-based actions and external proof links.

**CSS:** `color: #393c2a; background-image: linear-gradient(90deg, #393c2a, #393c2a); background-size: 0px 1px; background-position: 100% 100%; background-repeat: no-repeat; transition: background-size .4s cubic-bezier(.76, 0, .24, 1)`

**Text style:** `body` — Switzer 500 · 14px/1.2

**Observed:** The underline is a background treatment, not a painted button surface. Proof links are right aligned; the reverse closing credit uses cream lettering and underline.

**States:** Declared: focus-visible outline #7b8785 dashed 1px.

**Transfer:** Keep action wording short enough to sit naturally in a compact text row.

### Archive index link

**Use:** Select or browse an item from the long visual archive.

**CSS:** `color: #393c2a; transition: opacity .4s cubic-bezier(.165, .84, .44, 1)`

**Text style:** `index-link` — Switzer 600 · 14px/1.3

**Observed:** Title-case links stack without pills, bullets or separators in a sticky left rail.

**States:** Declared: focus-visible outline #7b8785 dashed 1px.

**Transfer:** Use item names rather than feature descriptions.

### Capability row

**Use:** Compact factual capabilities within a spacious chapter.

**CSS:** `display: grid; grid-template-columns: repeat(19, 1fr); column-gap: 8px; align-items: center; margin-top: 112px`

**Text style:** `label` — Switzer 500 · 14px/1.2 · uppercase

**Observed:** A bold uppercase group label sits left of a compact list; selected rows have right-aligned technical detail. A second information group shifts farther right and uses sentence-case body text.

**Transfer:** Use short specifications and supporting details instead of boxed feature cards.

### Recognition row

**Use:** Credibility through attributed proof.

**CSS:** `display: grid; grid-template-columns: repeat(2, 1fr); color: #393c2a`

**Text style:** `body` — Switzer 500 · 14px/1.2

**Observed:** An uppercase item name occupies the left half; one or several right-aligned Underline links occupy the other half. A separate bold group label anchors the block to the left.

**Transfer:** Map this format to certifications, customer references or press with actual attributable sources.

### Closing word link

**Use:** Dominant final conversion target.

**CSS:** `display: flex; flex-wrap: wrap; justify-content: center; color: #efe6d9`

**Text style:** `closing-display` — Ranade 700 · 158.4px/1 · uppercase

**Observed:** One link is split into large separately positioned fragments, alternating left and right. A smaller connector sits near the center; bottom metadata stays independent of the link.

**Transfer:** Keep the entire address or conversion phrase a coherent accessible link while arranging visual spans separately.

### Detail visit link

**Only for:** project detail views

**Use:** Open the featured project or demonstration.

**CSS:** `display: flex; align-items: center; gap: 8px; color: #393c2a; background-image: linear-gradient(90deg, #393c2a, #393c2a); background-size: 0px 1px; background-position: 100% 100%; background-repeat: no-repeat`

**Text style:** `detail-action` — Switzer 600 · 14px/1.2 · uppercase

**Observed:** A tiny north-east arrow precedes the label beneath the technical stack and contributor credits.

**States:** Declared: focus-visible outline #7b8785 dashed 1px; underline background-size transition .4s cubic-bezier(.76, 0, .24, 1).

### Detail return control

**Only for:** project detail views

**Use:** Exit the immersive detail view.

**CSS:** `display: flex; position: fixed; align-items: center; height: 32px; padding: 0px 12px; color: #393c2a`

**Text style:** `return-link` — Switzer 500 · 12px/1.2 · uppercase

**Observed:** A small text-only control sits at the upper right in the cream surround, remaining available as media scrolls.

**States:** Declared: focus-visible outline #7b8785 dashed 1px.

## Imagery and graphics

### Washed botanical atmosphere

**Use:** Full-bleed opening backdrop behind identity lettering.

**Observed:** Close-up outdoor foliage and seed heads fill the stage, softly rendered in near-monochrome cream. At 0.1 opacity with luminosity blending, the image remains much quieter than the olive lettering; there is no framed hero product card.

**Transfer:** Use product-relevant material, landscape or process photography with similarly organic detail. A well-chosen still is the minimum equivalent when motion footage is unavailable.

**Build:** Cover an absolute full-stage layer with nature or material imagery, set object-fit: cover, opacity: 0.1 and mix-blend-mode: luminosity over the cream canvas. Place all text above it; keep contrast low across the entire image rather than adding a local text gradient.

### Archive contact sheet

**Use:** Main visual proof field.

**Observed:** Numerous website views appear in four columns, square-cornered, with narrow darker mats and peripheral identifier marks. Imagery retains its own whites, blacks, saturated accents and changing aspect ratios; the surrounding interface remains muted and tiny.

**Transfer:** Use authentic interface views, output examples, prototypes or editorial process photographs. Preserve variety inside a consistent rectangular mat; do not force all media into identical square thumbnails.

### Tonal portrait

**Use:** Human or maker presence in the capability and credibility chapter.

**Observed:** A 344px by 435px outdoor portrait is pushed to the lower left, separated from the text grid. It is rendered in olive-green monochrome over a dark olive backing, with no border or decorative shape.

**Transfer:** Use an authentic maker or process photograph at the same vertical proportion; keep the green duotone and off-axis placement rather than introducing a headshot card.

**Build:** Use a rectangular image at roughly a 344:435 ratio. Convert to grayscale, then map shadows to dark olive and highlights toward moss using an SVG component-transfer or duotone filter. Preserve face and material detail; use the dark olive backing and avoid rounded masks.

### Immersive project media

**Only for:** project detail views

**Use:** Large left-hand sequence of project views.

**Observed:** Media are 684px wide with natural varying heights, separated by 45px. One project uses peach-backed colorful architecture and photographic collages; another uses dark film pages with monochrome interviews, warm coral lettering and organic photo cutouts. These are showcased designs, not extra styles for the enclosing page.

**Transfer:** Show the new product's own visual system in a sequence of opening view, detail views and broader output. Keep their native colors and typography inside the media, while the outer presentation remains taupe and olive.

### Icons

**Observed:** Only a small solid north-east arrow, 9px by 9px in dark olive, precedes the detail-view external action. The core interface is text-led rather than icon-led.

**Transfer:** Use a simple solid directional arrow for outbound actions; do not introduce an illustrative feature-icon system.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric identity poster

**Observed:** A 900px-high cream stage layers Washed botanical atmosphere behind oversized olive identity lettering. The first identity fragment spans almost the entire top width; its individual letter groups are spread apart. Another short fragment turns vertically along the lower right edge. The 265px regular uppercase identity contrasts with a left-aligned, two-line 16px support statement just below the top lettering. Bottom navigation is anchored at the lower left and a small year sits farther right. Within the first 900px the lettering, atmospheric image, support text and navigation are all visible; the media archive begins below the fold. The central and lower-left field remain largely empty.

**Transfer:** For a new product, use its short name or a compact promise as typographic material, distributing groups across the top and turning a short second fragment at the right. Supply a low-contrast material or process still when no appropriate video exists. Detail views instead open with large left-hand media and a restrained right-hand title and description in the Detail panel.

**Avoid:** Do not replace the distributed identity with a centered multi-line headline, a large filled CTA and a dashboard mockup. Do not enlarge the support text to compete with the identity.

**Text style:** `identity-display` — Ranade 400 · 265px/0.9 · uppercase

### Indexed visual archive

**Observed:** Archive field supports a sticky 24px chapter heading and a 168px Archive index link rail at the left. A four-column media field begins to the right, with 45px gaps and varied image heights. The media region dominates both page width and scroll length.

**Transfer:** Use this for visual proof, use cases or output collections, with a meaningful index and genuine visual variety. The device can be shorter than a portfolio archive without losing its contact-sheet character.

**Text style:** `chapter-heading` — Ranade 700 · 24px/1.2 · uppercase

### Offset capability ledger

**Observed:** Clay field begins with a small chapter heading and generous empty space. Capability row groups are staggered across the grid rather than sharing one left edge. A Tonal portrait occupies the lower left, while Recognition rows sit toward the right with their proof links flush right. The section closes with 128px bottom padding, not a separate boxed CTA.

**Transfer:** Turn product capabilities, operating principles and third-party proof into compact lists across offset columns. Retain the contrast between tiny facts and broad empty fields.

**Text style:** `label-bold` — Switzer 700 · 14px/1.2 · uppercase

### Sculptural closing action

**Observed:** Slate closing stage fills 900px with a centered 24px chapter label near the top. Closing word link fragments at 158.4px alternate between left and right, spanning most of the stage; an 83.2px connector remains near the center. A three-column line of 14px metadata finishes the page with 12px bottom padding. There is no extra footer beneath it.

**Transfer:** Recompose a contact address, short invitation or conversion phrase into a readable word sculpture. Keep one unmistakable action and use the bottom line for location, status and attribution relevant to the new product.

**Text style:** `closing-display` — Ranade 700 · 158.4px/1 · uppercase

### Pinned-detail presentation

**Only for:** project detail views

**Observed:** Detail surround is inset 32px at the top and left. Detail panel divides large 684px-wide scrolling media from a sticky text column capped at 480px. The title, short description and year cluster near the upper right with 16px gaps; technical metadata, credits and Detail visit link stay near the lower right. The Detail return control sits at the upper-right viewport edge. The final media item ends the scroll: a colorful tiled output view in one case and a dark events view in the other, with the same pinned information still present. Neither detail ending adds the sculptural contact stage.

**Transfer:** Use for case studies or deep demonstrations. Start with an overview media view, continue into details and finish with a substantial output view while retaining the project context and outbound action.

**Text style:** `detail-heading` — Ranade 400 · 28px/1 · tracking -0.02em · uppercase

## Page flow

**Storyline:** Identity and positioning → visual demonstration → compact capabilities and attributed proof → oversized final invitation; focused detail views expand the demonstration without repeating the landing-page close.

### A visual landing page for an independent service or design-led product

1. **Identity and promise** — Atmospheric identity poster combines a huge name, short positioning statement and bottom destination links.
2. **Product demonstration** — Indexed visual archive gives the work far more space than descriptive copy.
3. **Capabilities and credibility** — Offset capability ledger combines small factual lists, a tonal image and attributed recognition.
4. **Closing call** — Sculptural closing action makes a contact address the final visual event, ending with three small metadata anchors.

**Transfer:** Let visuals establish quality, then use concise facts to clarify scope. Adapt the length and placement of the archive while preserving the strong typographic stages.

### An immersive visual case study with colorful output

1. **Project context** — A large overview view sits left of a compact title, description and year.
2. **Product demonstration** — A single-column media sequence progresses through editorial, exploration and photographic output views while the information column stays in place.
3. **Final action** — The final tiled output image ends the gallery; stack, credits, external Visit action and the top return control remain accessible.

**Transfer:** Use the detail shell for colorful project content without applying those colors to the enclosing interface.

### An immersive visual case study with dark editorial output

1. **Project context** — A film-oriented overview view leads beside a compact purpose statement and date.
2. **Product demonstration** — Large dark media views move through cast, credits and event information against the unchanged taupe presentation.
3. **Final action** — The last events view ends the media sequence, alongside persistent technical credits, Visit action and return control rather than a separate footer.

**Transfer:** The same detail structure accommodates dark or campaign-specific imagery while keeping the outer design consistent.

## Writing

Restrained, specific and craft-oriented. Confidence comes from visible work and named facts rather than promotional superlatives; the closing adds a little conversational warmth.

**Do not copy:** Do not reuse the personal name, email address, location, availability claim, client names, awards, project descriptions or collaborator credits as claims for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Mostly descriptive and impersonal, with the maker's role and scope stated directly. The visitor is not repeatedly addressed as 'you'; the closing contact invitation is the warmest moment.
- **Rhythm:** One-word chapter headings, short noun-based labels, and one or two compact descriptive sentences. Technical lists are fragments; there are no long persuasive paragraphs or emphatic exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Identity | A short proper name treated as the main headline. | 2 words | “[Brand]” |
| Positioning statement | State role, reach and approach directly, without a slogan. | 2 compact sentences | “Freelance Front-End Developer based in France and working worldwide remotely. Focusing on crafting digital experiences with an editorial, modern and unique approach.” |
| Navigation and actions | Use destination nouns or a plain action verb. | 1 word | “Work”<br>“Profile”<br>“Contact”<br>“Visit” |
| Capability labels | Brief craft or technical nouns, sometimes paired with an ampersand. | 1–4 words | “Skills & Stack”<br>“Values & Motives”<br>“Design driven” |
| Detail description | Explain what the project does, then its experiential approach. | 2 sentences | “Personal design and photography project showcasing charismatic houses around the world. Featuring a vibrant and engaging web experience with a focus on exploration and visual storytelling.” |
| Closing metadata | Plain place and status statements, not sales urgency. | 2–5 words | “Toulouse, France”<br>“Available for new projects” |

**Words and phrasing to use:** crafting; digital experiences; editorial; design driven; exploration; visual storytelling; stack; credits

**Avoid:** revolutionary; game-changing; unlock your potential; all-in-one magic; limited-time offer; world's best

**Rules:**

- Describe the offering's role and practical scope before making qualitative claims.
- Let proof links name the publication or recognition rather than summarize it in enthusiastic prose.
- Keep chapter names short enough to function as navigation destinations.
- Use specific technical or operational terms only where they help a visitor understand the work.

## Do's and Don'ts

### Do

- Preserve the 265px-to-14px contrast between identity and structural information.
- Use 20px desktop side padding and an 8px underlying grid gutter.
- Keep the visual archive at four columns with 45px gaps on a wide desktop.
- Keep primary links text-only with a 1px underline treatment.
- Shift compact information groups across the grid instead of placing every group on one left edge.
- Give the final word sculpture 158.4px bold lettering and an independent three-column metadata line.
- Use flat full-width muted color fields rather than layering many panel surfaces.
- Keep showcased media's original aspect ratios and visual identity inside the neutral framing.

### Don't

- Do not use pure black for the main typography; use dark olive #393c2a.
- Do not turn the 24px uppercase chapter titles into 64px promotional headlines.
- Do not introduce rounded pills or soft card corners into the square-edged system.
- Do not add drop shadows to lift the archive off its matte taupe field.
- Do not scatter peach, slate and olive across small decorative badges; they organize large fields and lettering.
- Do not turn the compact capability ledger into a row of illustrated feature cards.
- Do not apply film lettering or bright house-project colors to the outer marketing typography.
- Do not add a multi-column corporate footer after the full-stage closing action.

## Motion and responsive

### Motion

**Observed:**

- Underline links declare background-size .4s cubic-bezier(.76, 0, .24, 1).
- Archive index links declare opacity .4s cubic-bezier(.165, .84, .44, 1).
- Full-stage color fields declare mask-position and -webkit-mask-position transitions of 1.25s cubic-bezier(.76, 0, .24, 1).
- Closing fragments declare transform 1.2s cubic-bezier(.76, 0, .24, 1).
- Media tiles declare opacity and filter transitions of 0.6s cubic-bezier(.165, .84, .44, 1).

**Transfer:**

- Use the declared mask transition to change entire chapter backdrops rather than fading isolated cards.
- Keep letter-fragment transforms tied to the sculptural closing action, with a legible settled arrangement.
- Use small opacity changes for archive indexing so the image contact sheet remains the main focus.

**Unknown:**

- Exact trigger logic and hover endpoint values are unspecified.
- The full opening and closing animation choreography is not established.

### Responsive

**Observed:**

- The design is documented at 1440px width with full-height 900px opening and closing stages.
- The detail title declares clamp(1.1rem, 2.25vw, 1.4rem); no width breakpoints are declared in the supplied style context.

**Transfer:**

- On narrow layouts, preserve the split identity treatment while fitting fragments to the available width; retain the quiet photographic field and compact information.
- Reduce the archive's column count before its images become illegible, and move the index out of the sticky side rail.
- Stack detail information with media and keep return and outbound actions available without pinning a narrow text column beside images.
- Maintain alternating alignment in the closing word sculpture even when fragments need smaller lettering.

**Unknown:**

- Mobile dimensions, breakpoint thresholds, touch behavior and exact small-screen typography are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
