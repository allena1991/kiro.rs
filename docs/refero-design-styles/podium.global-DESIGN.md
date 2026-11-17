# Podium — fieldwork meets sculpture

## Overview

A cinematic editorial style that sets muscular geometric capitals against stark white and black stages. Organic media sculptures, grainy location footage and technical drawing marks give it a physical, exploratory character. Sparse text and expansive image intervals suit creative services, performance products and visually driven launches.

### Essentials

- The opening is an emblem rather than a slogan: a white 900px stage holds a soft-edged media sculpture occupying roughly half the width, with a 79px fixed header and a small bottom-right scroll cue.
- Capitals behave like blocks of material: Futura 700 at 62px/0.9 for major statements, normal tracking, with justified manifesto lines and an inset proof heading.
- Actions are typographic, not capsules: the closing action is underlined Futura 700 at 54.4px/1, with no filled button shell.
- Color belongs to the work, not the interface: white and black own nearly all page surfaces; blue, earth red, skin and landscape colors live inside photography and textured objects.
- Media breaks out of the ordinary grid: include a floating, overlapping film collage on black and a soft organic media-mask emblem on white; use original detail photography if no film exists.
- Technical marks counterbalance the organic art: a white chapter carries dashed construction lines, nested irregular contours and tiny square handles behind bold text and square-edged proof panels.
- The closing call is a physical monument: a large textured object floats on black above a two-line 54.4px invitation/action, with 12px condensed side notes and a 0.5px dotted footer rule.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cool proof board | `#dddddd` | `--color-proof-panel` | surface | Cool gray rectangular proof-list board in the technical drawing chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Stage black | `#000000` | `--color-black` | background, text | Dark media stages and text on white. |
| Half-white rule | `#808080` | `--color-rule` | border | Visible result of 50% white marks over black; use the alpha recipe for the footer rule. |
| Warm proof board | `#faf7f4` | `--color-warm-panel` | surface | Nearly white warm companion board for a shorter capability list. |
| Stage white | `#ffffff` | `--color-white` | background, text | Opening and technical drawing chapters; reversed text on black. |

## Typography

- **Futura** — All major statements, navigation and narrative text. Geometric sans with heavy, broad capitals and direct regular body text. If unavailable, use **Jost**. Use 400, 500 and 700; preserve the heavy capital silhouettes. Font stack: "Futura", "Jost", system-ui, sans-serif.
- **Univers Condensed** — Small peripheral labels, footer notes and film metadata. Narrow utilitarian sans, distinct from the geometric headlines. If unavailable, use **Roboto Condensed**. Use regular for labels and bold for film metadata. Font stack: "Univers Condensed", "Roboto Condensed", Arial Narrow, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Futura | 700 | 62px | 0.9 | normal, uppercase | size clamp(32px, 20.8px + 2.86vw, 64px) | Main manifesto and large proof heading; the opening itself is image-led. |
| closing | Futura | 700 | 54.4px | 1 | normal, uppercase | fixed | Centered invitation and underlined conversion action. |
| chapter-label | Futura | 700 | 20px | 1 | -0.01em, uppercase | fixed | Process carousel heading. |
| navigation | Futura | 700 | 14px | 1 | -0.03em, uppercase | fixed | Compact fixed-header links. |
| label | Univers Condensed | 400 | 12px | 1.1 | normal, uppercase | fixed | Scroll cue, side notes and bottom credits. |
| eyebrow | Futura | 500 | 12px | 1.5 | normal, uppercase | fixed | Short availability or reach label above the manifesto. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | testimonial | Futura | 700 | 24px | 1 | normal, uppercase | fixed | One-line client reaction before the next-story invitation. |
| case studies | case-heading | Futura | 700 | 20px | 1 | normal, uppercase | fixed | Compact narrative lead after the film opening. |
| case studies | body | Futura | 400 | 16px | 1.2 | normal | fixed | Short production narrative below the lead. |
| case-study film openings | film-metadata | Univers Condensed | 700 | 16px | 1.2 | normal, uppercase | fixed | Film title-group metadata styling; the large visual film title is a separate display layer. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep large statements heavy and closely stacked, not tracked out. Only navigation and the process heading use negative tracking.
- The manifesto fills roughly ten of twelve columns and uses justified lines; the proof statement occupies the centered eight-column region but is left aligned.
- The closing invitation and link share one recipe, so the action reads as the continuation of the sentence rather than a separate UI control.

## Layout

**Density:** Airy overall, with dense headline blocks and compact labels separated by long cinematic intervals.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Case narrative heading-to-body separation. |
| 23.2px | Desktop outer gutter and fixed-header inset. |
| 23.4px | Desktop twelve-column grid gutter. |
| 24px | Process heading-to-carousel gap and video control side padding. |
| 31.4px | Desktop navigation link separation. |
| 32px | Case narrative block vertical padding. |
| 48px | Separation into the proof chapter. |
| 123.9px | Case-study chapter separation and black gallery top/bottom padding. |

### Containers and grids

- **Editorial grid**: 12 columns · gap 23.4px · side padding 23.2px. Full-width desktop grid; narrative and feature video span the middle eight columns, giving a 921px content area at 1440px.
- **Film gallery pair** (only for case studies): 2 columns · gap 23.4px · side padding 23.2px. Two 685px-wide 3:2 stills across the page.
- **Film gallery trio** (only for case studies): 3 columns · gap 23.4px · side padding 23.2px. Three 449px-wide 3:2 stills across the page.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and boards | 0px |

## Surfaces and depth

### Surfaces

#### White stage · level 0

**Use:** Default opening and editorial drawing chapter.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat white rather than a tinted app canvas.

**Transfer:** Let isolated artwork provide the dimensionality.

#### Black stage · level 0

**Use:** Floating collage, cinematic galleries and closing invitation.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Black extends around media without card containers.

**Transfer:** Use it as a theater for work, not as a dashboard theme.

#### Proof boards · level 1

**Use:** Paired short and long lists over technical linework.

**CSS:** `background: #dddddd; color: #000000; border-radius: 0px; box-shadow: none`

**Observed:** A taller cool gray board on the right meets a shorter warm-white board on the left at a shared bottom edge; tiny square corner marks imply pinned drawing objects.

**Transfer:** Use a brief capability inventory opposite a longer proof inventory.

#### Technical drawing field

**Use:** Background for the manifesto, process and proof chapters.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Dashed construction grid, large curved paths and nested gray contours pass behind the content.

**Transfer:** Rebuild with the Technical contour field graphic, keeping all marks subordinate to type.

## Components

### Fixed navigation

**Use:** Persistent brand and three short destinations.

**CSS:** `position: fixed; display: flex; justify-content: space-between; align-items: center; padding: 23.2px; z-index: 50`

**Text style:** `navigation` — Futura 700 · 14px/1 · tracking -0.03em · uppercase

**Observed:** A compact horizontal wordmark sits left, three links sit far right with a 31.4px gap. Ink reverses between white and black stages; there is no enclosing bar.

**Transfer:** Use a similarly dense original wordmark rather than plain small body text.

### Monumental text action

**Use:** Main conversion action in the closing stage.

**CSS:** `color: #ffffff; background: transparent; text-decoration: underline; text-align: center`

**Text style:** `closing` — Futura 700 · 54.4px/1 · uppercase

**Observed:** The action is the second line of the invitation and matches its visual weight. It has no pill, icon or panel.

### Scroll cue

**Use:** Peripheral guidance on the first screen.

**CSS:** `color: #000000; text-align: right`

**Text style:** `label` — Univers Condensed 400 · 12px/1.1 · uppercase

**Observed:** Anchored to the lower-right grid area, with the same outer inset as the header.

### Process filmstrip

**Use:** Human and practical proof of how work happens.

**CSS:** `display: flex`

**Observed:** Portrait frames form a horizontally clipped strip; each desktop slide has a 380px basis including its left gutter and a 470px visible height. A compact heading and small gray progress bar sit above.

**Transfer:** Show tools, people and material experiments rather than polished product packshots.

### Dotted footer rule

**Use:** Separate tiny credits from the closing artwork stage.

**CSS:** `background-image: repeating-linear-gradient(90deg, rgba(255, 255, 255, 0.5) 0px, rgba(255, 255, 255, 0.5) 3px, rgba(0, 0, 0, 0) 3px, rgba(0, 0, 0, 0) 6px); background-size: 100% 0.5px; background-position: 50% 100%`

**Observed:** Runs between the page gutters above a shallow footer; copyright left and credit right.

### Gallery row

**Only for:** case studies

**Use:** Rhythmic image-only proof chapters.

**CSS:** `display: grid; grid-template-columns: repeat(12, 1fr); gap: 23.4px; padding: 0px 23.2px`

**Observed:** Images span either six or four columns and keep a 3:2 ratio; no captions or card shells interrupt the sequence.

### Film player

**Only for:** case studies

**Use:** Main embedded film after the short narrative.

**CSS:** `background: #000000; aspect-ratio: 3 / 2; position: relative`

**Observed:** Centered eight-column media area with a bottom overlay: play at left, a thin waveform-like progress trace across the center, sound at right and fullscreen control. Controls have 24px side insets and 16px internal gaps.

### Testimonial line

**Only for:** case studies

**Use:** Brief social proof immediately before the continuation chapter.

**CSS:** `display: flex; align-items: flex-end; gap: 23.4px; color: #ffffff`

**Text style:** `testimonial` — Futura 700 · 24px/1 · uppercase

**Observed:** A bold reaction sits at left of the centered narrative width, with a much smaller attribution pushed toward the right.

## Imagery and graphics

### Organic media emblem

**Use:** Signature first-screen artwork.

**Observed:** An abstract running-like silhouette is assembled from dark soft-edged lobes on white. Small rectangular clips, landscape fragments and a rough stone object show within it; a detached oval floats above-right. The whole emblem is roughly 650px tall and centered with ample white surrounding it.

**Transfer:** Create an original emblem shaped around the new product's idea, filled with macro details and contextual photography. Minimum version: a custom SVG mask over three original images, not a generic blob stock illustration.

**Build:** Make an SVG mask from one elongated central curved lobe, two side branches and two detached ovals. At a 1440px desktop width, keep the group about 650px wide and 650px tall. Layer charcoal silhouette fill and rectangular photographic fragments, blur the mask edge by about 5px and add a faint white halo. Preserve internal white negative space and asymmetric balance.

### Floating film collage

**Use:** Signature work-reveal chapter on black.

**Observed:** Unequal portrait and landscape clips hover at different heights: a head at the left edge, a tall shoe detail, a central warm portrait, a rocky object layered above it and a darker group scene on the right. Sharp rectangular clips contrast with the isolated natural object.

**Transfer:** Use product details, a person using it and an environmental wide shot with the same unequal scale and overlap. Original stills can stand in for moving clips.

### Technical contour field

**Use:** Signature technical layer behind white editorial chapters.

**Observed:** Fine gray nested irregular loops resemble topographic contours. Long black dashed construction lines and large arcs cross the page; tiny outlined squares and corner dots create a drawing-board vocabulary.

**Transfer:** Keep the construction-drawing character while deriving the central contour from a shape related to the new product.

**Build:** Use a full-width SVG on white. Draw 15–20 nested wavy closed paths in black at roughly 0.25 opacity with 1px strokes and 8px dash gaps. Add several vertical and horizontal black construction lines with 18px dashes and 18px gaps, one oversized curved arc, sparse 20px outline squares and 3px corner handles. Keep this layer behind text, not over it.

### Physical closing artifact

**Use:** Signature large object above the final action.

**Observed:** A rough tan-gray rock slab with an impressed figure floats against pure black, oblique and softly lit from above. It occupies about half the viewport width, leaving room for small side captions.

**Transfer:** Commission an original artifact, tool or material with a meaningful embossed or carved mark. Minimum version: a high-resolution cutout of a tactile object, subtly rotated, with realistic directional light; do not replace it with a flat icon.

**Build:** For a 3D version, bevel an irregular flattened slab, displace its surface with layered stone noise, emboss an original simplified emblem into the front face and light from upper-left with a broad neutral area light. Render with transparent background and place centrally over black without a surrounding frame.

### Process documentary

**Use:** Portrait filmstrip within the white chapter.

**Observed:** Candid handheld-looking scenes show cameras, monitors, crews and people in natural settings. Bright daylight, greenery and red earth remain unflattened; frames crop tightly without rounded corners.

**Transfer:** Photograph actual making, testing and human work in portrait orientation.

### Cinematic still series

**Only for:** case studies

**Use:** Full-width pairs and trios after the film.

**Observed:** One story uses cold cyan snow, blue haze and grainy winter close-ups; the other uses deep red-brown earth, warm golden skin, sweat and backlit silhouettes. Both mix extreme detail, human portrait and environmental wide view, with low-key lighting and tactile grain.

**Transfer:** Choose a coherent project-specific grade rather than mixing the two palettes. Alternate intimate details with wider context; keep footage colors out of the interface.

### Icons

**Observed:** Controls are spare white silhouettes: a 14×22px play mark and 27×23px sound symbol; fullscreen uses a 51×50px mixed line/fill treatment. Icons belong to media controls rather than feature lists.

**Transfer:** Use simple white media glyphs, leaving marketing headings and conversion links icon-free.

## Section recipes

How recurring sections are built.

### First screen: Emblem stage opening

**Observed:** The first 900px is a white stage, not a conventional headline-and-button hero. The Fixed navigation floats across the top; the Organic media emblem occupies roughly the central half-width and most of the middle two-thirds of the screen. White canvas is behind the dark soft silhouette, photographic rectangles sit within it, and the rough material object overlaps the upper portion. A Scroll cue sits lower-right. There is no hero headline, supporting paragraph or conversion button above the fold; the large display statement belongs below the work reveal.

**Transfer:** Start a new marketing page with an original media emblem of comparable scale. Use the SVG-mask fallback with original product photographs when 3D or film is unavailable. Case studies instead open with a full-bleed darkened film still, small client/category metadata and a very large bold uppercase title near the bottom center.

**Avoid:** Do not turn this first screen into a two-column SaaS pitch or put a generic gradient orb behind a stack of buttons.

**Text style:** `display` — Futura 700 · 62px/0.9 · uppercase

### Floating work reveal

**Observed:** Black stage surrounds the Floating film collage across a long scrolling chapter, with fragments separated by negative space and overlapping in the center.

**Transfer:** Reveal evidence of the product's world before giving the detailed verbal promise.

### Manifesto and process

**Observed:** A small eyebrow precedes a heavy justified multi-line statement spanning about ten columns. The Technical drawing field continues behind it and the Process filmstrip, whose chapter label sits 24px above the images.

**Transfer:** State what the product enables in one substantive sentence, then support it with candid visual evidence.

**Text style:** `display` — Futura 700 · 62px/0.9 · uppercase

### Inset proof board chapter

**Observed:** A left-aligned large proof heading sits in the centered eight-column region. Below, Proof boards meet at a shared baseline over the Technical drawing field; the right list is taller than the left.

**Transfer:** Pair capabilities with credible adoption, outcomes or use cases. Keep entries concise and visually dense rather than converting them into logo cards.

**Text style:** `display` — Futura 700 · 62px/0.9 · uppercase

### Artifact closing invitation

**Observed:** A 900px Black stage centers the Physical closing artifact above the invitation at about two-thirds of the stage height. Monumental text action completes the two-line thought. Opposed condensed side notes sit around mid-height; Dotted footer rule and tiny credits occupy the bottom.

**Transfer:** Close with a physical symbol of the product's value and a direct collaborative action, retaining the object/text scale contrast.

**Text style:** `closing` — Futura 700 · 54.4px/1 · uppercase

### Case narrative and film

**Only for:** case studies

**Observed:** After the full-screen film opening, the black body uses 123.9px chapter gaps. A 20px uppercase lead and 16px/1.2 narrative sit in the middle eight columns, followed by a 921×614px Film player. One narrative is split into two columns; the other is a single short block.

**Transfer:** Explain the challenge and decisive creative or technical move, then let the film prove it.

**Text style:** `case-heading` — Futura 700 · 20px/1 · uppercase

### Case proof and continuation

**Only for:** case studies

**Observed:** Alternating Gallery rows of pairs and trios lead to a single Testimonial line. The ending reverses to a 755px white stage: a centered two-line next-story heading, underlined story name and a 685px-wide preview below. Both case endings use this construction rather than the artifact contact footer.

**Transfer:** Use the white reversal to open a related story, not to introduce a many-link footer.

## Page flow

**Storyline:** visual identity → immersive work → concise promise → human process → proof → monumental invitation; case studies expand the work into narrative and image evidence.

### Image-led marketing landing page

1. **Visual identity** — White emblem stage with sparse fixed navigation.
2. **Work demonstration** — Black floating collage of clips and a tactile object.
3. **Promise** — Heavy justified manifesto over technical contours.
4. **Human proof** — Candid portrait filmstrip.
5. **Credibility** — Inset display claim and paired inventory boards.
6. **Closing call** — Black artifact stage with enormous underlined text action and minimal credits.

**Transfer:** Adapt the narrative length and section order to the product while retaining the media emblem, collage, drawing marks and artifact call as recognizable devices.

### Cold-toned film case study

1. **Hook** — Full-bleed film still with large bottom-centered title.
2. **Context** — Short uppercase lead and a compact two-column narrative.
3. **Demonstration** — Inset film player.
4. **Visual proof** — Pairs, a trio and a pair of grainy cool-toned stills.
5. **Social proof** — Brief reaction with peripheral attribution.
6. **Continuation** — White next-story invitation with underlined name and large preview.

**Transfer:** Let a consistent cool project grade unify the images without changing the black and white interface.

### Warm-toned film case study

1. **Hook** — Full-bleed warm earthy film still and large bottom-centered title.
2. **Context** — Short lead and single compact narrative.
3. **Demonstration** — Inset film player.
4. **Visual proof** — Trio, pair, trio and pair alternate macro detail, portrait and place.
5. **Social proof** — Short reaction line before the white reversal.
6. **Continuation** — Centered next-story title and preview on white.

**Transfer:** Expand or contract the gallery according to available proof; maintain one coherent warm grade and the same editorial grid.

## Writing

Confident, practical and collaborative. The language sounds like people who make things in the field, not a platform promising universal transformation.

**Do not copy:** Do not reuse Podium's name, emblem, fossil artwork, client lists, project names, dates, production claims or attributed testimonials. Use new verified facts and original brand assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and your for the reader's ambition; case narratives speak concretely about the work and people.
- **Rhythm:** Large statements are one sentence spread across several dense lines. Small chapter titles are brief; case paragraphs mix compact factual setup with short emphatic conclusions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Manifesto | We help a specific audience achieve something through named methods. | One substantive sentence | “We help sports brands tell stories through fieldwork, narrative, and creative research, with deep production expertise.” |
| Chapter lead | A short physical or conceptual phrase, or a concrete setup followed by a reversal. | 4–16 words | “Red earth, New ground”<br>“Auclair turned 80. This wasn’t a regular seasonal push. It was about heritage.” |
| Closing invitation | Collaborative invitation followed by a direct action. | 3–5 words per line | “Let's build your vision”<br>“Work with us” |
| Peripheral note | Two opposed fragments that create forward momentum. | 3–5 words | “Not the finish line.”<br>“It's step one.” |
| Social proof | Short, informal client reaction rather than a polished marketing paragraph. | 3–5 words | “You guys are nuts...”<br>“Honestly, exceeded expectations.” |

**Words and phrasing to use:** fieldwork; stories; research; build; vision; behind the scenes; concrete material and process nouns

**Avoid:** revolutionary platform; unlock limitless potential; seamless ecosystem; game-changing solution; excessive superlatives

**Rules:**

- Name real methods instead of stacking abstract benefits.
- Let images carry atmosphere; use text for intention, process and proof.
- Write normal sentences even when their visual treatment is uppercase.
- Keep calls to action collaborative and direct.

## Do's and Don'ts

### Do

- Keep major statements at 700 weight with 0.9 line height.
- Align recurring content to the twelve-column grid with 23.4px gutters.
- Retain a white first screen and black cinematic stages as distinct moods.
- Use 3:2 media for case-study pairs and trios.
- Keep the closing action at the same 54.4px size as its invitation.
- Use 12px condensed notes at the edges rather than adding more body copy.
- Preserve square media edges and flat, unshadowed boards.

### Don't

- Do not add saturated interface accent fills; let photography carry chromatic color.
- Do not turn case galleries into captioned cards with borders and 12px radii.
- Do not use a monospaced font for the narrow peripheral labels.
- Do not letter-space the large capitals into a luxury fashion treatment; their tracking is normal.
- Do not center every editorial heading; the inset proof statement remains left aligned.
- Do not substitute a logo cloud for the dense paired proof inventories.
- Do not apply drop shadows to the flat boards or media frames.

## Motion and responsive

### Motion

**Observed:**

- The brand link declares an opacity transition of 0.5s cubic-bezier(.4, 0, .2, 1).
- Case opening media declares a linear scroll-linked animation across the first viewport.
- The visual system includes flipping artwork, noise and reveal animation definitions.

**Transfer:**

- Treat the emblem, collage and artifact as coordinated scene changes rather than independent card hover effects.
- Keep film controls visually subordinate to the footage.

**Unknown:**

- Exact artwork animation choreography, reveal timing and interaction endpoint styles are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 767px, 768px, 1024px, 1280px, 1512px and 1536px.
- Navigation is hidden below the medium breakpoint; the process strip changes from 26.4vw slide bases to 77.6vw.
- Desktop side captions are hidden on smaller widths.

**Transfer:**

- Preserve the emblem as the primary first-screen object on narrow screens rather than introducing a new text-heavy hero.
- Use the wider mobile carousel slides to show one process image and part of the next.
- Stack case gallery items and keep the short narrative readable without shrinking the desktop type proportionally.

**Unknown:**

- The narrow-screen menu mechanism and complete mobile compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
