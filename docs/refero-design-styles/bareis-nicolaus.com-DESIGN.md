# Bareis + Nicolaus — split-screen visual index

## Overview

An uncompromising black-and-white framework behaves like a live visual index rather than a conventional sales page. Regular grotesk navigation and bookish serif explanations sit beside vivid, tightly framed photography and graphic work. It suits image-led products, creative tools and collections with strong visual proof; the interface is dense, direct and almost entirely monochrome while the media supplies the exuberance.

### Essentials

- Navigation is half the experience: at 1440px, a 719px black navigation pane faces a 719px media pane across a 2px white division; the right pane scrolls independently.
- Headings behave like oversized menu labels, not advertising slogans: Lausanne regular at 72px/1 with normal tracking, paired with 24px/1 interface labels and 24px/1.2 Victor Serif explanations.
- Every category reads as a capsule: 50px-high controls with 2px outlines, 120px corner radii and 12px 13.2px 9.6px padding; the selected category flips to white with black lettering.
- Color belongs to the exhibits, not the furniture: black, white and secondary gray form the interface; vivid media occupies roughly half of the desktop opening and can change palette completely from one item to the next.
- Proof is a continuous filmstrip: square-cornered, approximately 719×405px images meet at 2px white rules with title pills floating 20px inside the upper-left edge. Use original product close-ups or composed feature artwork when no photographic collection exists.
- A narrow live-information ribbon is part of the identity: a 39px white ticker spans both panes at the bottom, using black 24px sans text and vertical-bar separators; contact remains accessible in the left pane even at the end of a long gallery.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface white | `#ffffff` | `--color-white` | text, background, border, action | Default lettering and 2px rules; selected capsules, ticker and editorial canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Interface black | `#000000` | `--color-black` | background, text, border, action | Default dark canvas, inverted text on white, and rules in the editorial variant. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| bilingual editorial content and case-study descriptions | Secondary gray | `#a9a9a9` | `--color-secondary` | text | Secondary translations on white and subdued narrative text on black. |

## Typography

- **Lausanne** — Oversized navigation, section titles, capsules and ticker. Regular, open, unembellished grotesk with a prominent x-height and even strokes. If unavailable, use **Inter**. Use 400; preserve normal tracking rather than tightening the display. Font stack: "Lausanne", "Inter", Arial, sans-serif.
- **Victor Serif** — Explanatory paragraphs, studio introductions and continuous proof lists. Bookish, high-contrast serif that adds a literary counterpoint to the utilitarian navigation. If unavailable, use **Bodoni Moda**. Use 400 and check line wrapping in the wide text column. Font stack: "Victor Serif", "Bodoni Moda", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Lausanne | 400 | 72px | 1 | normal | Main navigation words and large editorial section titles. |
| label | Lausanne | 400 | 24px | 1 | normal | Capsules, image title headings, short links and ticker text. |
| prose | Victor Serif | 400 | 24px | 1.2 | normal | Descriptions and long, slash-separated editorial lists. |

**Notes:**

- The hierarchy uses a strong 3:1 size relationship between display and interface text, not a ladder of intermediate headings.
- Keep both families regular. Serif descriptions are upright even where they are semantically emphasized.
- Large title rows use optical negative margins of about 4.3px above and 13px below the display line, keeping the visible lettering snug inside padded bands.

## Layout

**Density:** Dense navigation and uninterrupted media; comfortable serif paragraphs are contained within the same compact ruled framework.

### Spacing

| Value | Use |
| --- | --- |
| 20px | Pane insets, heading-band padding and media title inset. |
| 6.7px | Horizontal space between wrapping capsules. |
| 13.3px | Vertical space between capsule rows. |
| 28.8px | Paragraph separation, equal to one prose line. |
| 40px | Roomier editorial separation without breaking the compact panel language. |

### Containers and grids

- **split shell**: 2 columns · gap 0px · side padding 0px. Full viewport width with no centered maximum. At 1440px, allocate 719px to the left pane and 721px including its 2px divider to the right pane. Reserve the bottom 39px for the ticker; the upper panes occupy 861px in a 900px viewport.
- **media column**: 1 column · gap 0px · side padding 0px. Full-width images within the right pane, typically 719px wide and about 405px tall before separators.
- **editorial column** (only for information and service pages): 1 column · gap 0px · side padding 20px. White right pane with 679px text width inside a 719px column; photos and title-band rules extend to the pane edges.
- **square journal grid** (only for visual journals and archives): 2 columns · gap 0px · side padding 0px. Two approximately 360px-wide square-image cells within the right pane, separated by white rules rather than gutters.

## Corner radius

| Element | Radius |
| --- | --- |
| capsules | 120px |
| media panels | 0px |

## Surfaces and depth

### Surfaces

#### Black index canvas · level 0

**Use:** Default shell and media backing.

**CSS:** `background: #000000; color: #ffffff; box-shadow: none`

**Observed:** Flat, hard-edged and continuous. Structural white rules are more important than elevation.

**Transfer:** Keep the framework neutral so neighboring images can use unrelated palettes.

#### Ruled media stack · level 0

**Use:** Sequential visual proof.

**CSS:** `background: #000000; border-bottom: 2px solid #ffffff; border-radius: 0px`

**Observed:** Images are flush to the pane edges with no surrounding card or shadow.

**Transfer:** Make the image itself the panel, not a thumbnail inside another box.

#### White editorial canvas · level 0

**Only for:** information and service pages

**Use:** Long-form right pane.

**CSS:** `background: #ffffff; color: #000000; box-shadow: none`

**Observed:** The left index stays black; only the reading pane inverts.

**Transfer:** Use this scoped inversion for substantial explanations, specifications or institutional proof.

## Components

### Outline capsule

**Use:** Utility navigation, category filters and compact actions.

**CSS:** `background: #000000; color: #ffffff; border: 2px solid #ffffff; border-radius: 120px; padding: 12px 13.2px 9.6px; height: 50px; box-sizing: border-box`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** Text determines width. Capsules wrap into an index rather than stretching into equal-width buttons.

**States:** Declared: hover text-decoration none; focus-visible not specified; active text-decoration none.

**Transfer:** Use short categories and destinations in the same visual grammar.

### Selected capsule

**Use:** Current filter or persistent selected item.

**CSS:** `background: #ffffff; color: #000000; border: 2px solid #ffffff; border-radius: 120px; padding: 12px 13.2px 9.6px; height: 50px; box-sizing: border-box`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** A solid inversion distinguishes the current item from the outline controls. Case-study titles also use this filled treatment.

**Transfer:** Reserve the inversion for state and emphasis, not a rainbow of categories.

### Accordion navigation band

**Use:** Large left-pane destinations and expandable context.

**CSS:** `padding: 20px; border-bottom: 2px solid #ffffff; display: flex; justify-content: space-between; align-items: center`

**Text style:** `display` — Lausanne 400 · 72px/1

**Observed:** The active band grows to contain filters or explanatory prose. Collapsed headings remain visible below it; the contact band sits at the bottom of the navigation area.

**Transfer:** Use a few broad destination nouns; expand the current context instead of introducing a second navigation system.

### Circular toggle

**Use:** Expand, collapse or close the contextual navigation area.

**CSS:** `width: 52px; height: 52px; background: #000000; border: 2px solid #ffffff; border-radius: 120px; display: flex; justify-content: center; align-items: center; box-sizing: border-box`

**Observed:** A fine white plus, minus or diagonal cross sits in the ring at the right of the oversized navigation word.

**Transfer:** Construct the marks with two straight SVG or CSS strokes; keep the surrounding control visually identical.

### Media panel

**Use:** Clickable visual proof and case-study gallery frames.

**CSS:** `position: relative; border-bottom: 2px solid #ffffff; border-radius: 0px; overflow: hidden`

**Observed:** Landscape imagery fills the right pane. Consecutive items share edges; no text block sits beneath each image.

**Transfer:** Use a consistent landscape frame for each proof item, varying between tightly cropped detail and a complete object.

### Floating title capsule

**Use:** Identify media without consuming a separate caption band.

**CSS:** `position: absolute; top: 20px; left: 20px; border: 2px solid #ffffff; border-radius: 120px; padding: 12px 13.2px 9.6px; color: #ffffff`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** Transparent outline titles float over the collection imagery; on a detail view a filled Selected capsule remains at the top of the scrolling pane.

**Transfer:** Keep titles concise and let them overlap the image instead of adding explanatory card chrome.

### Bottom ticker

**Use:** Continuous identity, contact and contextual information across the whole shell.

**CSS:** `height: 39px; background: #ffffff; color: #000000; position: sticky; overflow: hidden; z-index: 100; white-space: nowrap`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** A single repeated line runs through both columns at the lower edge. Vertical bars separate identity, discipline, email and local weather; the ribbon persists during gallery scrolling.

**Transfer:** Use a short repeating set of real product facts, availability and a contact destination.

### Editorial capsule heading

**Only for:** information and service pages

**Use:** Small topic labels above long descriptions and proof lists.

**CSS:** `color: #000000; border: 2px solid #000000; border-radius: 120px; padding: 12px 13.2px 9.6px; height: 50px; box-sizing: border-box`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** Left-aligned outlined pills sit within the text inset on white, while major headings span ruled full-width bands.

**Transfer:** Use capsules for specific topics and display bands for chapter-level divisions.

### Journal tile

**Only for:** visual journals and archives

**Use:** Dated visual observations in a dense two-column feed.

**CSS:** `border-right: 1px solid #ffffff; border-bottom: 2px solid #ffffff; position: relative`

**Text style:** `label` — Lausanne 400 · 24px/1

**Observed:** Square photographs meet edge-to-edge. A date, time and author line overlays the upper edge, without a capsule or a separate description below.

**Transfer:** Use first-hand process pictures and brief factual metadata rather than marketing card summaries.

## Imagery and graphics

### Edge-to-edge visual proof

**Use:** Primary media throughout the default right-hand filmstrip.

**Observed:** Large photographic or rendered details dominate the right half: pale hardware against soft red and yellow forms, closely cropped sports photography, printed posters against real walls and books photographed obliquely. Color is intense where the work warrants it, but the interface never picks up that hue.

**Transfer:** Show a new product's distinctive materials, output or use at this scale. If photography is unavailable, make a carefully composed original feature image or a full-bleed product demonstration rather than substituting a generic stock photograph.

### Physical-object study

**Only for:** case-study galleries

**Use:** Reveal craft through multiple views of one product or output.

**Observed:** Printed discs, sleeves and cover artwork alternate between black-backed isolated compositions and sunlit photographs on turquoise textured fabric. Hard diagonal shadows, reflections, bright cyan and yellow print and warm sunset imagery make the object tactile. Some isolated objects occupy only the central portion of a landscape black field.

**Transfer:** Alternate a clean front view, a pair or arrangement, a material close-up and an in-use photograph. Preserve actual shadows, texture and reflections rather than placing everything in a synthetic rounded mockup.

### Observational journal photography

**Only for:** visual journals and archives

**Use:** A long visual research feed.

**Observed:** Square informal photographs of printed matter, lettering, packaging, street details, plants, food, fabric and everyday objects. Lighting and color vary naturally; close framing and the grid supply coherence rather than a shared filter.

**Transfer:** Collect first-hand material and process observations relevant to the new product, mixing finished output with unexpected details.

### Environmental portrait

**Only for:** information pages

**Use:** Human introduction at the start of a white reading pane.

**Observed:** A full-column landscape portrait shows two people standing against a muted green-gray concrete wall. Mustard and orange clothing add warmth; natural side light and slight foreground softness keep it candid rather than corporate.

**Transfer:** Photograph the people behind the product in a real working environment, waist-up or wider, without cutout silhouettes or headshot cards.

### Icons

**Observed:** The prominent controls use a thin white circle and simple plus, minus or cross marks. There is no decorative feature-icon grid.

**Transfer:** Limit interface symbols to these direct geometric control marks; use text for categories.

## Section recipes

How recurring sections are built.

### First screen: Split index opening

**Observed:** A flat black shell divides the first screen almost equally. The left begins with a large two-line identity at the upper-left and two compact utility capsules aligned to its upper-right. A white rule separates that masthead from the 72px Accordion navigation band. The expanded band contains wrapping 24px Outline capsules, with one Selected capsule; lower destination bands and contact remain visible. The right starts immediately with edge-to-edge media, not a separate hero heading. At 900px height, two landscape Media panels and the start of a third appear above the persistent 39px Bottom ticker. A Floating title capsule labels each exhibit. The layers are black canvas, photographic panels, rules and overlaid capsules, then the ticker; there is no introductory slogan or support paragraph above the gallery.

**Transfer:** Give a different product a similarly prominent typographic identity, a broad current-context heading and a concise capsule index. Lead the right side with its strongest close-up or visual result and immediately reveal the next result below. Without photography, compose original product-output artwork at the same scale. A detail page replaces filters with serif context and a gallery; an information page opens the right pane with a display title and environmental photograph on white; a journal starts directly with square images.

**Avoid:** Do not turn the opening into a centered headline, supporting sentence and button above a full-width hero; the simultaneous index and exhibits are the first impression.

**Text style:** `display` — Lausanne 400 · 72px/1

### Continuous proof strip

**Observed:** Media panel follows Media panel with only the 2px rule between them. Floating title capsules sit inside the imagery. The surrounding left index and Bottom ticker stay available throughout scrolling.

**Transfer:** Use an adaptable number of visual results, demonstrations or product scenes; let the media establish the case before adding extensive claims.

**Text style:** `label` — Lausanne 400 · 24px/1

### Persistent closing interface

**Observed:** The collection and detail galleries conclude with final media rather than a new full-width sales section. The editorial variant ends with its publication list. The Contact band and Bottom ticker remain present, so a route onward is already available at the ending.

**Transfer:** End the content pane with a strong final proof image or compact credibility block while preserving the same contact route. Treat the ticker as a signature device, not a substitute for a usable destination.

### Case-study context and variations

**Only for:** case studies

**Observed:** The active left band contains 24px serif narrative, a compact collaborator capsule and filled category pills. A fixed filled title capsule identifies the right pane as its landscape image sequence scrolls from object studies to graphic detail and back to photographs.

**Transfer:** Pair a concise explanation of purpose and production with multiple complementary views. Keep credits in the contextual pane rather than overlaying paragraphs onto images.

**Text style:** `prose` — Victor Serif 400 · 24px/1.2

### White editorial chapters

**Only for:** information and service pages

**Observed:** White editorial canvas begins with a 72px title band and full-width portrait. Subsequent display headings divide chapters with black 2px rules. Editorial capsule headings introduce 24px/1.2 serif paragraphs; primary-language text is black and the following translation is secondary gray. Later proof appears as dense slash-separated name lists rather than a logo wall.

**Transfer:** Use this variant for capabilities, methods and credible references. Keep parallel-language passages paired and separate the longer proof lists with topic capsules.

**Text style:** `prose` — Victor Serif 400 · 24px/1.2

### Square visual journal

**Only for:** visual journals and archives

**Observed:** The right pane is a zero-gutter two-column grid of square Journal tiles with timestamp overlays. The left navigation is mostly collapsed, leaving a broad black field below the destinations.

**Transfer:** Use a chronological visual feed for process or inspiration, not as the default landing-page layout.

**Text style:** `label` — Lausanne 400 · 24px/1

## Page flow

**Storyline:** Identity and contextual index alongside immediate visual proof → deeper variations or explanatory chapters → final proof with persistent contact.

### Image-led marketing collection

1. **Orientation** — Large two-line identity, utility capsules and an expanded category index in the black left pane.
2. **Visual proof** — A long landscape filmstrip with pill titles in the scrolling right pane.
3. **Closing contact** — Final images end the filmstrip; the contact band and repeating information ribbon remain in place.

**Transfer:** Present a product through varied outcomes while keeping its categories and contact route continuously legible.

### Detailed demonstration of one project or product outcome

1. **Context** — Serif description, credit link and category capsules replace the left filter list.
2. **Product demonstration** — A filled persistent title accompanies a sequence of object arrangements, artwork and photographed details.
3. **Closing proof** — The sequence finishes with a physical-product photograph, retaining the shell and contact ribbon.

**Transfer:** Explain the intent once, then let complementary views deepen understanding without repeating marketing copy.

### Chronological process and visual-discovery archive

1. **Orientation** — Collapsed left index and selected utility destination.
2. **Process proof** — Long two-column square-image feed with date, time and author overlays.
3. **Continuation** — The repeated tile grid runs to its final item; the global contact and ticker remain outside the feed.

**Transfer:** Use a visual journal when the product benefits from an ongoing record of materials, experiments or field observations.

### Institutional explanation and credibility

1. **Introduction** — Black contextual introduction faces a white display-title band and environmental portrait.
2. **Capability chapters** — Ruled display headings, topic capsules and paired serif language passages.
3. **Social proof** — Dense slash-separated reference and recognition lists replace conventional logos or testimonial cards.
4. **Closing credibility** — Publication and interview references form the final content while contact stays available in the shell.

**Transfer:** Use the light reading-pane variant for substantial narrative and proof; adapt the chapter topics to the new offering.

## Writing

Direct, culturally literate and matter-of-fact. Visual work carries the confidence; prose explains intent, collaboration and execution rather than shouting benefits.

**Do not copy:** Do not reuse the studio identity, project titles, collaborators, client and award lists, contact details, locations, claims or original artwork. Source examples illustrate syntax and tone only.

- **Addressing the reader:** Navigation is impersonal. Explanations use first-person plural or the organization name; they rarely address the reader directly.
- **Rhythm:** One- or two-word chapter headings, compact category nouns and longer explanatory prose. Lists can become continuous text separated by slashes; title case is common without all-capital UI shouting.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Main destination | A plain noun at monumental size. | 1 word | “Work”<br>“Contact” |
| Category or action | Name a medium, topic or destination rather than promising an outcome. | 1–3 words | “Selected”<br>“Research”<br>“Art Direction” |
| Chapter heading | A factual label that groups related content. | 1–3 words | “Creative Services”<br>“+ Network” |
| Explanation | State what is planned or made, then describe the media and working relationship. | 2–4 sentences | “We plan and develop strategic communication concepts and modern graphic solutions for various fields of visual communication.” |
| Credit | Direct attribution with no testimonial framing. | Short attribution | “Photos by” |

**Words and phrasing to use:** selected; work; research; identity; concept; develop; collaboration; visual; print; digital

**Avoid:** revolutionary; game-changing; unlock your potential; best-in-class; limited-time offer

**Rules:**

- Let the media title identify the result instead of turning every panel into a benefit headline.
- Use concrete process and material nouns in explanations.
- Keep bilingual text paired by topic, with the translation visually secondary.
- Format long reference lists as editorial text, not invented endorsement quotations.

## Do's and Don'ts

### Do

- Keep the desktop shell split into two nearly equal panes with a 2px divider.
- Set navigation titles at 72px/1, weight 400 and normal tracking.
- Use 24px interface labels even when this produces a dense capsule index.
- Maintain the asymmetric 12px top and 9.6px bottom capsule padding.
- Keep main insets and overlay offsets at 20px.
- Preserve square image corners and zero-gutter media sequencing.
- Include the 39px bottom information ribbon across both panes.
- Use the white reading-pane variant for long explanations while retaining the black index.

### Don't

- Do not tint the shell to match each image; keep its black-and-white identity stable.
- Do not apply the 120px capsule radius to photographs or whole content panels.
- Do not add drop shadows or glass effects to structural bands.
- Do not replace the regular 72px navigation with bold condensed display typography.
- Do not shrink the interface into a conventional 14px toolbar.
- Do not turn the slash-separated proof lists into a generic wall of monochrome logos.
- Do not add colored category fills; selected state is a black-and-white inversion.
- Do not place explanatory paragraphs underneath every gallery tile; explanations belong in contextual or editorial areas.

## Motion and responsive

### Motion

**Observed:**

- Declared panel transitions include flex 0.4s cubic-bezier(0.16, 1, 0.3, 1) and opacity 0.4s cubic-bezier(0.76, 0, 0.24, 1).
- The bottom information line repeats horizontally while the right media pane scrolls independently.
- Action hover and active declarations remove text decoration.

**Transfer:**

- Use the flex transition for the expanding contextual navigation; keep the media pane separate from that expansion.
- Maintain the continuous ticker as part of the persistent shell without assigning it an unverified speed.

**Unknown:**

- Ticker speed and direction are not established.
- Focus-visible treatment and complete interaction choreography are not established.

### Responsive

**Observed:**

- CSS width breakpoints occur at 599px, 600px, 999px, 1000px, 1399px, 1400px, 1599px and 1600px.

**Transfer:**

- On narrow screens, prioritize preserving the index-to-media relationship through a collapsible context area rather than squeezing two illegible columns; this is adaptation guidance.
- Keep title capsules tied to their images and retain a usable contact route when the large desktop bands cannot all fit.

**Unknown:**

- Exact narrow-screen arrangements, typography changes and pane behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
