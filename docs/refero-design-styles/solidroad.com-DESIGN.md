# Solidroad — alpine editorial optimism

## Overview

A human, outdoors-inflected technology style that pairs delicate mixed-serif headlines with small, practical sans-serif copy. Mostly white and warm cream, it reserves electric yellow-green for actions and a winding route through cinematic landscapes. Oversized interface scenes, defocused natural backdrops and translucent details give enterprise software a tangible, approachable presence without making the page dense.

### Essentials

- Editorial headlines stay surprisingly restrained beside enormous media: ABC Arizona Mix at 40px/1, weight 300, -0.02em tracking; the opening headline occupies a 400px column while the product scene spills beyond the right edge.
- The opening is a layered expedition, not a flat dashboard: a 900px-tall landscape, a glass-framed interface roughly 971px wide, foreground terrain and a luminous yellow-green route; use original landscape layers and a representative workflow when full product media is unavailable.
- Electric color behaves like a trail marker: #dbf400 appears in compact 40px-high, 80px-radius actions and the route, not broad content fills. Most reading sections are white, with warm cream reserved for the ending and pastel media stages scoped to product explanations.
- Interfaces float inside the landscape: 8px-radius media windows, strongly defocused scenery, white controls and translucent shells with 0.5px edges and 5–20px backdrop blur separate sharp product detail from soft surroundings.
- Proof reads like an editorial testimony rather than a dashboard: 32px/1.1 light mixed-serif quotes and numbers, 12px/1.3 explanatory labels, thin vertical dividers and a 2px progress rail with a green active segment.
- Every page resolves into a cream terrain print: a two-line 40px closing thought opposite a lime pill, then a fine rule, compact navigation columns and a low-contrast halftone mountain sweeping behind the footer. Recreate the dotted contour artwork rather than substituting an empty footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric route lime | `#dbf400` | `--color-lime` | action, accent | Primary conversion pills and the signature scenic route. |
| Dusk blue | `#273849` | `--color-sky-dark` | background | Upper scenic hero fallback, beneath photography. |
| Warm cream | `#fbf7eb` | `--color-cream` | background, text | Closing band and light type over dark scenic media. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal text | `#2d2c29` | `--color-text` | text, action | Main section headings, body text and button labels. |
| Warm headline ink | `#322f25` | `--color-ink` | text | Mixed-serif display, quotes, footer links and active feature text. |
| Dusk charcoal | `#3c3b3d` | `--color-sky-mid` | background | Middle scenic hero fallback. |
| Dusk stone | `#6d6965` | `--color-sky-low` | background | Lower scenic hero fallback. |
| Muted stone | `#6f6e6b` | `--color-muted` | text | Support paragraphs, author roles and small metadata. |
| Outline control gray | `#808080` | `--color-strong-edge` | border | Visible black at 50% over white for outlined actions. |
| Receding heading | `#878683` | `--color-receding` | text, link | The first clause of paired headings and link hover. |
| Inactive control edge | `#c3c2bf` | `--color-disabled-edge` | border, text | Receding circular carousel controls. |
| Progress rail gray | `#cccccc` | `--color-rail` | border, surface | Visible black at 20% over white; progress tracks and standard hairline edges. |
| Light rule | `#e1e0dd` | `--color-rule` | border | Subtle dividers and pale tracks. |
| Secondary action sand | `#ebe5d5` | `--color-sand` | action, surface | Small secondary trial action in navigation. |
| Subtle separator gray | `#e6e6e6` | `--color-subtle-edge` | border | Visible black at 10% over white for question rows. |
| Pale stone | `#f5f4f1` | `--color-stone` | surface, background | Media backing and the soft warm reading-band variant used for product proof and questions. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text, border | Primary page canvas, sharp interface interiors and reverse navigation. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof progress green | `#09a619` | `--color-progress` | accent | Active segment of testimonial progress; distinct from conversion lime. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product capability triptychs | Apricot stage | `#ffcda9` | `--color-peach-stage` | surface | Third media panel in the pastel capability trio. |
| product capability triptychs | Powder blue stage | `#e4efff` | `--color-blue-stage` | surface | First media panel in the pastel capability trio. |
| product capability triptychs | Blush stage | `#fff6fa` | `--color-pink-stage` | surface | Second media panel in the pastel capability trio. |

## Typography

- **ABC Arizona Mix** — Headlines, testimony, numbers and editorial navigation. Light mixed serif with soft, open forms and a literary rather than corporate character. OpenType features: "ss01". If unavailable, use **Lora**. Use regular weight with tight tracking; preserve the narrow headline measure. Font stack: "ABC Arizona Mix", "Lora", Georgia, serif.
- **FT Regola Neue** — Body copy, feature labels, actions and metadata. Neutral contemporary grotesk; compact, regular and unobtrusive. If unavailable, use **Inter**. Use 400; preserve the small body scale. Font stack: "FT Regola Neue", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | ABC Arizona Mix | 300 | 56px | 1 | -0.02em | Large flowing benefit statement between detailed chapters. |
| heading | ABC Arizona Mix | 300 | 40px | 1 | -0.02em | Default opening and section headline; also the two-line closing thought. |
| quote-stat | ABC Arizona Mix | 300 | 32px | 1.1 | -0.02em | Testimonial quotation and adjacent numerical outcomes. |
| feature-label | FT Regola Neue | 400 | 18px | 1.2 | normal | Feature selectors and short capability titles. |
| footer-link | ABC Arizona Mix | 400 | 16px | 1.2 | normal | Footer navigation links. |
| body | FT Regola Neue | 400 | 14px | 1.4 | normal | Default support paragraph, small section label and capability caption. |
| action | FT Regola Neue | 400 | 14px | 1.1 | normal | Main and outlined section actions. |
| nav | ABC Arizona Mix | 400 | 14px | 1.2 | normal | Top-level editorial navigation. |
| caption | FT Regola Neue | 400 | 12px | 1.3 | normal | Author roles and stat explanations. |
| nav-action | FT Regola Neue | 400 | 12px | 1.1 | normal | Compact actions inside navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product FAQ sections | question | ABC Arizona Mix | 300 | 18px | 1.2 | -0.02em, features "blwf", "cv03", "cv04", "cv09", "cv11", "ss01" | Expanded question headings. |
| product explanations and FAQ sections | answer | FT Regola Neue | 400 | 16px | 1.4 | normal | Readable explanatory answers and introductory product prose. |

**Notes:**

- The default hero is the same 40px scale as ordinary section headings; its prominence comes from placement and contrast, not oversized lettering.
- The mixed-serif display recipes tighten to -0.02em; body, actions and navigation retain normal tracking.
- Use sentence case throughout. Small section labels are not uppercase technical eyebrows.
- Keep muted and dark clauses within one heading recipe rather than introducing a second type scale.

## Layout

**Density:** Airy at the section scale, compact at the text scale; large scenic windows and long pauses surround small labels and short paragraphs.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small label-to-heading gap and paired icon-control gap. |
| 10px | Question-to-answer gap and tight story-card gutters. |
| 12px | Button horizontal inset and capability trio gutters. |
| 16px | Heading groups, media-to-caption gap and footer link rhythm. |
| 24px | Outer page gutter and question-row vertical inset. |
| 32px | Hero copy stack and heading-to-support gap on editorial openings. |
| 40px | Feature content stacks and story-card inner inset. |
| 64px | Heading-to-major-media separation. |
| 80px | Standard desktop section vertical inset and additional inset for editorial content. |
| 104px | Total desktop side inset of editorial feature and testimony content. |
| 120px | Proof section breathing room and closing-band top inset. |
| 160px | Large statement top breathing room. |

### Containers and grids

- **wide page**: max width 1648px · side padding 24px. Outer wrapper for broad product media, story grids and question lists.
- **editorial inset**: max width 1648px · side padding 104px. Inset feature stories and testimony; 1232px content width at a 1440px viewport.
- **navigation shell**: max width 1600px · gap 48px · side padding 24px. Logo at left, editorial links toward the right and a tightly grouped action cluster at far right.
- **heading measure**: max width 600px. Two-line section headline, usually left aligned.
- **hero title measure**: max width 400px. Narrow three-line opening title beside the large scenic interface.
- **quote measure**: max width 880px. Wide but readable testimony above compact author and stat row.
- **feature split**: 2 columns · gap 16px. 730px-wide landscape media beside a 486px selector column within the inset wrapper.
- **pastel trio** (only for product capability triptychs): 3 columns · gap 12px. Equal product capability stages with captions beneath.
- **story grid** (only for customer-story collections): 3 columns · gap 10px. Tall landscape-backed customer story cards.
- **logo wall** (only for customer proof directories): 4 columns · gap 0px. Ruled grid of centered dark customer marks, with broad merged cells in the final row.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 80px |
|  | media windows | 8px |
|  | glass interface shells | 20px |
|  | circular controls | 40px |
| product demonstration artwork | floating review shell | 66px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating detail | `0px 4px 15.5px 0px rgba(0,0,0,0.1)` | A translucent detail floating over blurred scenic media; not a general card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Primary reading surface.

**CSS:** `background: #ffffff`

**Transfer:** Let white space do most of the grouping.

#### Cream ending · level 0

**Use:** Shared closing call and footer.

**CSS:** `background: #fbf7eb; overflow: clip`

**Observed:** A low-contrast terrain print sits behind both closing call and footer columns.

**Transfer:** Use a warm material ending after white reading sections.

#### Scenic dusk · level 0

**Use:** Default landing opening behind scenic photography.

**CSS:** `background: linear-gradient(#273849 0%, #3c3b3d 60%, #6d6965 100%); overflow: clip`

**Observed:** Photography supplies the terrain; the gradient is a fallback rather than the main picture.

**Transfer:** Retain dusk contrast beneath original landscape art.

#### Media window · level 1

**Use:** Rounded scenic demonstration window.

**CSS:** `background: #f5f4f1; border-radius: 8px; overflow: hidden`

**Observed:** The surface is covered by defocused photography and sharply drawn product details.

**Transfer:** Do not leave its backing exposed as an empty panel.

#### Floating glass · level 2

**Use:** Small detail shell over a photographic demonstration.

**CSS:** `background: linear-gradient(rgba(251,247,235,0.25), rgba(235,229,213,0.25)); border: 0.5px solid #ffffff; border-radius: 66px; padding: 4px; backdrop-filter: blur(20px); box-shadow: 0px 4px 15.5px 0px rgba(0,0,0,0.1)`

**Observed:** A separate white inner pill keeps the important label sharp; the glass is a thin outer cushion.

**Transfer:** Use selectively for a status or meaningful piece of workflow UI.

#### Soft reading band · level 0

**Only for:** product proof and FAQ sections

**Use:** Warm neutral alternative to white for sustained reading.

**CSS:** `background: #f5f4f1`

**Observed:** Light stone is perceptible behind testimony and questions.

**Transfer:** Use as a gentle tonal chapter change.

#### Pastel stage · level 1

**Only for:** product capability triptychs

**Use:** Large isolated stage for one capability illustration.

**CSS:** `background: #e4efff; border-radius: 8px; aspect-ratio: 5 / 6; display: flex; align-items: center; justify-content: center`

**Observed:** Equal siblings use blush and apricot; each object is substantially smaller than its stage.

**Transfer:** Keep color behind the visual rather than behind all caption text.

## Components

### Primary button

**Use:** Main conversion action within sections.

**CSS:** `background: #dbf400; color: #2d2c29; border-radius: 80px; padding: 0px 12px; height: 40px; display: inline-flex; align-items: center; justify-content: center; gap: 4px; border: 0.5px solid rgba(0,0,0,0.2)`

**Text style:** `action` — FT Regola Neue 400 · 14px/1.1

**Observed:** Text precedes a small right arrow on most section actions; the opening action is text-only. Width follows the label.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #02f with outline-offset 2px.

**Transfer:** Use one concise conversion verb phrase.

### Outlined button

**Use:** Read a story or explore a supporting detail.

**CSS:** `color: #2d2c29; border: 0.5px solid rgba(0,0,0,0.5); border-radius: 80px; padding: 0px 12px; height: 40px; display: inline-flex; align-items: center; gap: 4px; backdrop-filter: blur(5px)`

**Text style:** `action` — FT Regola Neue 400 · 14px/1.1

**Observed:** A fine perimeter and faint warm translucent layer make it quieter than the primary action; a small right arrow follows the text.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #02f with outline-offset 2px.

### Navigation

**Use:** Persistent top-level orientation.

**CSS:** `position: fixed; top: 0px; left: 0px; right: 0px; height: 67px; z-index: 10; padding: 16px 24px; display: flex; align-items: center; border-bottom: 1px solid rgba(255,255,255,0.2); backdrop-filter: blur(8px); background: rgba(0,0,0,0.02)`

**Text style:** `nav` — ABC Arizona Mix 400 · 14px/1.2

**Observed:** Small wordmark left; three editorial links align toward the right before sign-in, a sand trial pill and a lime demo pill. Reverse text overlays the scenic opening; white surface with dark type serves reading sections. Link hit areas are 35px high with 8px 12px inset.

**Transfer:** Keep the navigation shallow and visually subordinate to the scene.

### Compact navigation action

**Use:** Conversion action inside the fixed header.

**CSS:** `background: #dbf400; color: #2d2c29; height: 34px; padding: 0px 12px; border-radius: 80px; display: inline-flex; align-items: center`

**Text style:** `nav-action` — FT Regola Neue 400 · 12px/1.1

**Observed:** The primary header action has an arrow; the neighboring trial action uses sand, and sign-in uses a fine outline.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #02f with outline-offset 2px.

### Feature selector

**Use:** Text-led tabs beside a changing scenic product demonstration.

**CSS:** `color: #322f25; max-width: 600px; text-align: left; width: 100%`

**Text style:** `feature-label` — FT Regola Neue 400 · 18px/1.2

**Observed:** The active item opens a short paragraph and primary action beneath its title. A fine vertical rule marks the selected chapter; inactive labels are muted and widely separated.

**States:** Declared: hover inactive labels change to #322f25; focus-visible outline 2px solid #02f with outline-offset 2px.

**Transfer:** Show one capability in detail while keeping the other titles visible.

### Carousel arrow

**Use:** Move through stories or testimony.

**CSS:** `width: 30px; height: 30px; padding: 2px; border: 0.5px solid #c3c2bf; border-radius: 40px; backdrop-filter: blur(5px); display: inline-flex; align-items: center; justify-content: center; color: #c3c2bf`

**Observed:** A 20px arrow sits inside a small circular control. Previous is receding; the forward control uses a stronger dark outline.

**States:** Declared: hover unspecified; focus-visible outline 2px solid #02f with outline-offset 2px.

**Transfer:** Pair controls at the far right, not large overlay buttons on the media.

### Proof rail

**Use:** Progress across testimonial slides.

**CSS:** `height: 2px; width: 100%; background: rgba(0,0,0,0.2); border-radius: 1px; position: relative`

**Observed:** A green active segment covers one quarter of the rail for four stories. A compact fraction sits below at left; circular controls sit below at right.

**Transfer:** Divide the rail by the actual story count and preserve its nearly hairline visual weight.

### Footer link

**Use:** Compact navigation columns inside the shared ending.

**CSS:** `color: #322f25; border-radius: 2px; text-decoration: none; display: inline-block`

**Text style:** `footer-link` — ABC Arizona Mix 400 · 16px/1.2

**Observed:** Four columns have muted sans-serif labels, with 32px before the links and 16px between them. Legal links form a separate small baseline row.

**States:** Declared: hover color #878683; focus-visible outline 2px solid #02f with outline-offset 2px.

### Story card

**Only for:** customer-story collections

**Use:** Landscape-backed link into a customer outcome.

**CSS:** `height: 510px; padding: 40px; border-radius: 8px; background: #f5f4f1; display: flex; flex-direction: column; justify-content: space-between; overflow: hidden`

**Text style:** `body` — FT Regola Neue 400 · 14px/1.4

**Observed:** Defocused blue-green landscape fills the card; a small frosted name chip sits at top left, a white customer mark is centered, and a pale outcome caption anchors the bottom.

**Transfer:** Use genuine proof and a single outcome per card rather than a feature checklist.

### Question row

**Only for:** product FAQ sections

**Use:** Expanded objection-handling question and answer.

**CSS:** `padding: 24px 0px; border-bottom: 1px solid rgba(0,0,0,0.1); display: flex; flex-direction: column; gap: 10px`

**Text style:** `question` — ABC Arizona Mix 300 · 18px/1.2 · tracking -0.02em

**Observed:** All answers are visible. The answer uses the answer recipe with a 640px measure, even though the dividing line spans the page.

**Transfer:** Keep the list editorial, not a grid of heavy accordion cards.

## Imagery and graphics

### Scenic interface expedition

**Use:** Signature opening artwork for marketing landings.

**Observed:** A dusk mountain panorama fills the viewport. A huge sharp white interface rises from the right half in a translucent shell, clipped at the right edge. A nearer rocky ridge occludes its bottom; a lime path flows across that ridge and toward the right. Light customer marks sit along the bottom edge.

**Transfer:** Stage a representative workflow in an original landscape with foreground occlusion and a route. If finished interface art is unavailable, draw a credible white two-pane workflow with a few real labels; retain the scenic depth and route rather than replacing it with generic device mockups.

**Build:** Layer a full-cover original dusk landscape, a left darkening scrim, a right-aligned translucent 20px-radius shell with white workflow panels, and a cutout foreground ridge above it. Draw an SVG cubic path in #dbf400 along the ridge, thin near its distant origin and thickening toward the right exit. Keep the path clear of the text column.

### Defocused nature stage

**Use:** Recurring media treatment behind detailed product objects.

**Observed:** Mountain, sky and greenery dissolve into broad blue, olive and warm stone fields. The image remains luminous but strongly blurred; small white interfaces, profile chips and glass status elements float sharply in the center. Inset demonstrations occupy about three fifths of their text-and-media split.

**Transfer:** Use original landscape photography with strong depth blur; the minimum is an enlarged, blurred landscape with a single meaningful sharp workflow object.

**Build:** Place a cover landscape image in an 8px-radius clipped panel. Enlarge it beyond the edge and apply approximately 24–40px blur as a construction guide; add a light translucent wash if necessary. Center the sharp object on a separate layer, using the Floating glass surface only at its perimeter.

### Halftone terrain print

**Use:** Signature art behind every closing band and footer.

**Observed:** A pale dotted mountain silhouette rises from the lower left, peaks beneath the closing headline and dissolves toward the right. It is monochrome, low contrast and substantially wider than the logo, with no bounding card.

**Transfer:** Create a new halftone terrain shape and keep footer text legible over it; this printed texture is the required counterpart to the photographic opening.

**Build:** Use an SVG pattern of small #322f25 circles on a roughly 8px pitch. Mask the field to an irregular low mountain silhouette, densest on the left slope and fading to zero on the right. Apply roughly 0.12 opacity at the darkest area. Place it full width starting 170px below the top of the cream ending; do not draw contour outlines.

### Pastel capability objects

**Only for:** product capability triptychs

**Use:** Equal illustrations explaining three complementary capabilities.

**Observed:** Blue, near-white blush and apricot stages each hold a centered miniature interface. Objects range from a small white profile card to stacked communication chips and a larger translucent evaluation panel; the backgrounds dominate over the objects. Titles and descriptions sit below on white.

**Transfer:** Reduce each capability to one legible object; do not reproduce an entire application in each panel.

### Frosted trust symbols

**Only for:** trust and assurance pages

**Use:** Compliance and privacy storytelling within scenic panels.

**Observed:** White certification seals overlap as translucent discs over a heavily defocused blue-and-orange scene. Another state uses a white padlock inside three concentric hairline rings; the object is centered and modest against the wide image.

**Transfer:** Replace seals with verified credentials or a meaningful assurance symbol. Keep the backdrop softer and larger than the symbol.

**Build:** Over blurred photography, center three concentric SVG circles with 0.5px white strokes at low opacity and a simple white lock. For verified seals, overlap two translucent discs; retain crisp white marks inside and avoid thick dark outlines.

### Human documentary chapter

**Only for:** company or origin storytelling

**Use:** Full-bleed humanizing interlude.

**Observed:** Candid people walking outside occupy the right and center of an architectural scene. Natural muted clothing, deep green surroundings and a black lower fade support a small cream headline at left, aligned beside a slender vertical marker.

**Transfer:** Use a real working interaction rather than posed cutout portraits. Keep it photographic and cinematic, with restrained captioning.

### Icons

**Observed:** Small filled SVG arrows and chevrons dominate marketing controls: 12–16px inside actions and 20px in carousel controls. Dark warm ink on light surfaces, white over scenery; category markers use a small pale circular backing.

**Transfer:** Choose simple filled directional icons and minimal symbolic marks. Let product artwork carry detail; do not introduce a large multicolor icon family across the marketing layout.

## Section recipes

How recurring sections are built.

### First screen: Scenic expedition opening

**Observed:** A full 900px scenic opening sits beneath the fixed 67px Navigation. Back to front: Scenic dusk, mountain panorama and left darkening scrim, translucent workflow shell, foreground ridge with lime route, text and bottom customer marks. The text begins around 200px from the top inside the 104px editorial inset: a 400px-wide three-line heading, 340px-wide support line and Primary button separated by 32px. The main workflow begins near the center, is roughly 971px wide by 700px high, and extends off the right edge. Within the first 900px the headline, support, action, large workflow, route and logo strip are visible; the next white section falls below the fold.

**Transfer:** Use the Scenic interface expedition recipe with original workflow and landscape layers. Product-detail openings instead use white canvas, a small category marker, a 40px headline and short paragraph above a wide scenic workflow window, with the action aligned to the far right. Story collections open with an editorial introduction and three tall Story cards; assurance pages use the compact heading above a sticky image-and-copy chapter.

**Avoid:** Do not center a giant sans-serif headline over a small floating dashboard, or flatten the scene into an ordinary image below the text.

**Text style:** `heading` — ABC Arizona Mix 300 · 40px/1 · tracking -0.02em

### Muted-to-ink heading pair

**Observed:** A small body-size section label precedes a 600px-wide heading by 16px. The introductory clause is receding gray while the conclusion is charcoal at the same size. A 64px pause separates the heading from substantial media.

**Transfer:** Split a proposition at a natural semantic boundary so the darker clause carries the result.

**Text style:** `heading` — ABC Arizona Mix 300 · 40px/1 · tracking -0.02em

### Scenic feature selector split

**Observed:** Within the editorial inset, a 730px by 440px Media window sits beside Feature selector content across a 16px gutter. The active title, short paragraph and Primary button form one expanded chapter; other titles remain collapsed beneath. Standard vertical section inset is 80px.

**Transfer:** Use three concise chapter labels and a genuinely different central object for each state, rather than adding a long feature checklist.

**Text style:** `feature-label` — FT Regola Neue 400 · 18px/1.2

### Editorial quantified testimony

**Observed:** An inset 2px Proof rail and small controls lead into a customer mark and an 880px-wide quotation. Light 32px type also sets two outcome numbers, while 12px captions explain them. A small portrait and name align beside the outcomes; fine vertical dividers separate the groups. Outlined button sits beneath. The full chapter has 120px top and bottom inset.

**Transfer:** Use an attributable quote and a small number of verified outcomes; give the quotation more visual space than the metrics.

**Text style:** `quote-stat` — ABC Arizona Mix 300 · 32px/1.1 · tracking -0.02em

### Large benefit sentence

**Observed:** A flowing 56px light mixed-serif statement spans the 1232px inset content width, with 160px above and a very long pause below. It reads as continuous prose rather than a set of cards.

**Transfer:** Write one connected sentence summarizing the transformation and use it as an editorial breath between detailed chapters.

**Text style:** `statement` — ABC Arizona Mix 300 · 56px/1 · tracking -0.02em

### Cream terrain closing

**Observed:** A 765px Cream ending begins with 120px top inset. The 40px two-line closing thought sits left while a Primary button aligns far right. A rule 320px into the band separates the invitation from a larger logo at left and four Footer link columns at right. Halftone terrain print sweeps behind both zones; small legal links and copyright finish on a low baseline.

**Transfer:** Write an original short two-part partnership thought. Preserve the cream field, dotted terrain, asymmetric CTA row and functional footer rather than ending in a boxed promotion.

**Text style:** `heading` — ABC Arizona Mix 300 · 40px/1 · tracking -0.02em

### Pastel capability trio

**Only for:** product capability triptychs

**Observed:** Three equal 5:6 Pastel stage panels sit across the wide wrapper with 12px gutters. Centered sharp objects remain smaller than their backgrounds. Each panel is followed by a 16px gap, an 18px sans-serif title and a short muted 14px description.

**Transfer:** Choose complementary concepts and vary the objects while preserving equal stages and caption baselines.

**Text style:** `feature-label` — FT Regola Neue 400 · 18px/1.2

### Sticky assurance chapters

**Only for:** trust and assurance pages

**Observed:** A category marker, 40px headline and 14px support remain above successive image-and-copy states. The chapter is sticky beneath the header. A fine inset rule precedes a 806px by 450px scenic media window on the left; the right column contains narrow prose and an Outlined button, with substantial open space around it.

**Transfer:** Group assurance claims into a small set of credible themes, using Frosted trust symbols and readable supporting explanations.

**Text style:** `heading` — ABC Arizona Mix 300 · 40px/1 · tracking -0.02em

### Expanded question list

**Only for:** product FAQ sections

**Observed:** A 40px heading introduces full-width Question rows; short 18px questions and 16px answers stay left aligned. Answers cap at 640px; the rows remain open with thin full-width separators.

**Transfer:** Answer practical adoption objections directly, in one short paragraph per question.

**Text style:** `question` — ABC Arizona Mix 300 · 18px/1.2 · tracking -0.02em

## Page flow

**Storyline:** Promise → tangible product scene → capability explanation → attributable proof → broader reassurance → warm closing invitation.

### Brand-level marketing landing

1. **promise** — Scenic expedition opening combines the desired outcome with an oversized workflow.
2. **capability explanation** — A muted-to-ink heading introduces the scenic feature selector.
3. **social proof** — Editorial testimony pairs a quote with compact quantified outcomes.
4. **transformation** — A large benefit sentence turns details into an overall promise.
5. **reassurance** — Full-bleed scenic and human chapters broaden confidence beyond the interface.
6. **closing call** — Cream terrain closing unifies invitation and navigation.

**Transfer:** Balance demonstrable functionality with a scenic sense of progress; treat this as a narrative vocabulary rather than a fixed section sequence.

### Customer proof directory

1. **promise** — Editorial title and short introduction frame relevance to the reader.
2. **social proof** — Three tall Story cards introduce distinct outcomes.
3. **quantified proof** — Editorial testimony expands one story.
4. **breadth of adoption** — A ruled four-column logo wall establishes range.
5. **closing call** — The common cream invitation and terrain footer finish the page.

**Transfer:** Use authentic outcome stories and a structured logo collection, while preserving the light editorial introduction.

### Flagship product detail

1. **promise** — Category marker and compact heading above a broad scenic workflow window.
2. **product demonstration** — Introductory prose and customer marks ground the demo in real usage.
3. **capability chapters** — Pastel capability trio, followed by the deeper scenic selector split.
4. **quantified proof** — Shared testimonial chapter adds external validation.
5. **objection handling** — Expanded question rows address practical adoption concerns.
6. **closing call** — Shared cream terrain ending.

**Transfer:** Move from an immediately recognizable workflow to isolated capabilities, then answer practical buying questions.

### Trust and assurance detail

1. **reassurance promise** — Compact editorial heading states reliability and operational care.
2. **objection handling** — Sticky chapters pair scenic trust symbols with short explanations and outlined exploration actions.
3. **closing call** — Shared cream terrain ending softens the technical subject.

**Transfer:** Use factual assurance themes and restrained visual symbols rather than a dense compliance dashboard.

## Writing

Confident, plainspoken and encouraging. It speaks about improved work and readiness, using concrete mechanisms to support optimistic outcomes rather than sounding like an abstract AI manifesto.

**Do not copy:** Do not reuse Solidroad's name, wordmark, landscape assets, customer logos, quotations, proprietary feature names or numerical performance claims. Source wording here illustrates voice, not copy to transplant.

- **Addressing the reader:** Address the reader as you and your team; refer to the product by name when introducing a mechanism, and use we sparingly for partnership or operational responsibility.
- **Rhythm:** Headlines are usually 6–10 words, sentence case and often split over two or three lines. Support is one short sentence; detailed explanations may use two or three plain sentences. Feature labels are direct verb phrases and often end in a period.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Connect an immediate human outcome to a practical enabling action. | 6–10 words | “Better customer outcomes start with better training”<br>“Practice that feels like the real thing.” |
| Support line | Name the mechanism, then explain what becomes easier for the team. | 14–28 words | “Realistic AI-powered simulations that make every agent, and every interaction, better.” |
| Feature label | Start with a concrete verb and name the thing the reader can shape. | 3–9 words | “Create custom scorecards.”<br>“Build immersive customer simulations” |
| Primary action | A short invitation to a specific next step. | 2–4 words | “Get a demo” |
| Closing thought | Two complementary clauses express expertise and reader agency through one grounded metaphor. | 8–14 words | “We know the terrain. You know the destination.” |
| Assurance | State responsibility plainly, then substantiate it with practices. | One short heading plus 1–2 sentences | “Security and reliability are at our core” |

**Words and phrasing to use:** practice; prepared; ready; realistic; confidence; your team; standard; workflow; quality; build; before

**Avoid:** revolutionary; game-changing; 10x everything; magic; synergy; AI-first disruption; unparalleled

**Rules:**

- Lead with a change in the reader's working life, not a technology category.
- Keep body copy practical: who acts, what they do and what happens next.
- Support proof with attribution and clearly labeled outcomes.
- Use one coherent physical metaphor sparingly; do not turn every label into an outdoor pun.

## Do's and Don'ts

### Do

- Keep the default heading at 40px/1 with weight 300 and -0.02em tracking.
- Preserve the contrast between narrow 400px title copy and oversized right-hand media.
- Use compact 40px section pills and 34px navigation pills.
- Keep ordinary support copy at 14px/1.4 even beside large imagery.
- Give inset feature stories 80px vertical breathing room.
- Pair 32px proof numbers with 12px explanatory labels rather than prominent badges.
- Recreate low-contrast halftone terrain within the cream ending.
- Keep product details sharp against heavily softened scenery.

### Don't

- Do not turn the electric lime into a broad page background or paragraph color.
- Do not use bold geometric sans-serif headings as a substitute for the light mixed serif.
- Do not enlarge all body copy to 18px; that removes the compact editorial contrast.
- Do not use 24px rounding on ordinary media; reserve the measured 8px media edge.
- Do not spread glass blur over every reading card; it belongs around scenic product details and controls.
- Do not turn the quiet proof row into bright metric tiles.
- Do not introduce a dark boxed footer; keep the shared cream material ending.
- Do not treat pastel stages as general-purpose tinted text cards outside capability illustrations.

## Motion and responsive

### Motion

**Observed:**

- Primary actions and carousel controls declare 0.6s color-related transitions with cubic-bezier(.6, 0, .05, 1). Footer links declare .4s with cubic-bezier(.44, 0, .56, 1).
- Navigation backing declares background and backdrop-filter transitions at 0.45s with cubic-bezier(.6, 0, .05, 1).
- The active proof segment declares a width transition of 0.6s with cubic-bezier(.6, 0, .05, 1).
- A route-stroke drawing animation declares 3s with cubic-bezier(0.02, 0.47, 0.5, 1), delayed 50ms; scenic parallax and text reveal are also declared.

**Transfer:**

- Animate the route as a drawn journey, not a flashing decorative stripe.
- Use the declared proof-rail transition when changing stories and keep label transitions subordinate to the media.

**Unknown:**

- Exact reveal durations, scroll choreography and automatic carousel cadence are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 810px, 1200px, 1280px and 1440px.
- Feature splits and capability trios have column-to-row variants; desktop navigation links are hidden below their desktop mode.
- The assurance scene is sticky in tablet-and-wider mode; its media pane has a hidden narrow-screen variant.

**Transfer:**

- On narrow layouts, stack the scenic object after the title while retaining foreground layering and the lime route.
- Let capability stages stack with their captions and keep the footer columns compact in a two-column arrangement.
- Reduce the editorial inset toward the 24px outer gutter rather than squeezing the 104px desktop inset.

**Unknown:**

- Exact mobile type sizes, menu behavior and scenic art positioning are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
