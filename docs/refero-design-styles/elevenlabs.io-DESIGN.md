# ElevenLabs — living instruments on cream

## Overview

A light, research-minded identity where restrained grotesk typography and warm off-white architecture surround surprisingly sensuous color. Grainy luminous spheres, soft-focus color fields, fine geometric diagrams and carefully staged interfaces make technical products feel alive. The density alternates between spacious editorial introductions and compact, useful demonstrations; it suits creative tools, developer platforms and enterprise products.

### Essentials

- The headline speaks softly while the object performs: light-weight Waldenburg at 48px/52px with -0.02em tracking, a left-hand two-line promise and a right-hand 16px/24px explanation above a broad interactive stage.
- Color lives inside instruments, not across the page: keep the surrounding canvas #fdfcfc and stages #f5f3f1; concentrate saturated orange, violet, cyan and green in rounded media and luminous objects rather than navigation or paragraph text.
- A living object is the signature: stage a grain-textured, softly shaded sphere at 256px with smaller flanking objects, a white circular play control and subdued captions. For an intangible product, use a layered gradient sphere as its demonstrable material counterpart.
- Actions are small polished capsules: black and white 44px-high pills, 20px side padding, 16px regular text and an 8px gap; white buttons have a 0.5px edge and only 1px–4px shadow offsets.
- The page behaves like a fine technical drawing: 1px black-at-5% container rails, 12px column gaps, small joint dots and 160px chapter lead-ins surround 36px/42px light headings.
- Demonstrations are nested, not pasted: 16px-radius cream stages hold white interface fragments with fine edges and shallow shadows, often clipped at a stage edge; captions remain small at 15px/22px.
- The ending is an understated invitation, not a billboard: a 190px ruled band pairs 32px/36px light text with two pills, followed by a spacious directory with 13px muted headings and 14px medium-weight links.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Luminous blue | `#3d75d8` | `--color-material-blue` | accent | A blue anchor for luminous material and gradient artwork, paired with cyan highlights; keep it inside media rather than using it for navigation or ordinary actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, action | Headlines, text, primary buttons and fine diagram strokes. |
| Warm dark gray | `#44403b` | `--color-dark-gray` | action, text | Primary-button hover and secondary dark text. |
| Warm gray text | `#777169` | `--color-muted` | text | Support copy, eyebrows, inactive labels and footer category labels. |
| Receding gray | `#a59f97` | `--color-inactive` | text | Unselected demonstration captions and tertiary information. |
| Capsule edge | `#d7d2cc` | `--color-tab-edge` | border | The 0.5px inset edge around segmented controls. |
| Warm edge | `#ebe8e4` | `--color-warm-edge` | border, surface | Internal separators and restrained neutral media backing. |
| Canvas hairline | `#f0efef` | `--color-hairline` | border | Visible result of black at 5% over the warm-white canvas; used for rails and section divisions. |
| Warm cream | `#f5f3f1` | `--color-cream` | surface, background | Media stages, feature cards and announcement band. |
| Warm white canvas | `#fdfcfc` | `--color-canvas` | background | Default page ground and secondary-button hover. |
| Raised white | `#ffffff` | `--color-white` | surface, text | Nested interfaces, secondary buttons and reversed media captions. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Focus blue | `#2b7fff` | `--color-focus` | border | Keyboard focus outline, not a marketing accent. |

## Typography

- **Waldenburg** — Hero, section and closing headings. Light neo-grotesk with open, approachable lowercase and compact display proportions. If unavailable, use **Inter**. Use weight 300 and preserve the measured sizes and tracking. Font stack: "Waldenburg", "Inter", Arial, sans-serif.
- **Inter** — Paragraphs, labels, navigation and actions. Neutral, highly readable grotesk with a restrained regular-to-medium hierarchy. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Waldenburg | 300 | 48px | 52px | -0.02em | Primary promise, generally wrapping into two lines. |
| heading | Waldenburg | 300 | 36px | 42px | normal | Chapter headings; usually one or two short lines. |
| closing | Waldenburg | 300 | 32px | 36px | normal | Ruled closing invitation. |
| article-title | Inter | 400 | 20px | 1.35 | normal | Editorial card titles below square media. |
| question | Inter | 400 | 17px | 25px | 0.01em | Accordion questions. |
| body | Inter | 400 | 16px | 1.5 | 0.01em | Hero support, explanatory paragraphs and feature headings. |
| button | Inter | 400 | 16px | 1.5 | normal | Default conversion actions and segmented-control labels. |
| eyebrow | Inter | 500 | 15px | 22px | 0.01em | Muted sentence-case chapter labels. |
| support | Inter | 400 | 15px | 22px | 0.01em | Card support copy and compact feature descriptions. |
| navigation | Inter | 400 | 14px | 20px | normal | Top-level navigation. |
| directory-link | Inter | 500 | 14px | 1.5 | 0.01em | Directory links in the footer. |
| announcement | Inter | 400 | 14px | 18px | 0.01em | Announcement copy and compact resource links. |
| directory-label | Inter | 500 | 13px | 18px | normal | Muted directory category titles. |
| caption | Inter | 400 | 13px | 18px | normal | Demonstration captions and small controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and enterprise capability selectors | plan-title | Inter | 400 | 24px | 32px | -0.01em | Plan names and intermediate capability headings. |

**Notes:**

- Light display text contrasts with regular body text; do not make the display hierarchy bold.
- Only the 48px headline tightens to -0.02em. The 36px default chapter heading retains normal tracking.
- Sentence case is the default for labels as well as headlines. Small body recipes often use +0.01em, while button and navigation text use normal tracking.
- The 18px root text is not the default visible paragraph recipe; most marketing explanations use body or support.

## Layout

**Density:** Airy chapter spacing with compact controls and tightly assembled demonstration grids.

### Spacing

**Spacing system:**

- **gutter** 8px — Declared base gutter for small control gaps; not a claim that every value is an 8px multiple.
- **inset** 16px — Declared base inset, particularly for nested white panels.

| Value | Use |
| --- | --- |
| 8px | Paired action gap and small inline groups. |
| 12px | Main grid gutters and card-to-card gaps. |
| 16px | Nested interface inset and compact copy separation. |
| 20px | Button side padding and card caption side inset. |
| 24px | Editorial title margin and larger control groups. |
| 28px | Eyebrow-to-heading separation. |
| 32px | Heading-to-action or support separation; inner editorial-section side padding. |
| 40px | Chapter title block bottom space and footer group row gap. |
| 48px | Logo row separation and tab-to-media space. |
| 72px | Closing-band vertical padding. |
| 96px | Product and enterprise hero top padding. |
| 120px | Default opening top space and major section or footer padding. |
| 160px | Spacious chapter heading lead-in. |

### Containers and grids

- **main rails**: max width 1180px · side padding 12px. Centered desktop architecture with faint vertical rails; approximately 130px outer margins at a 1440px viewport.
- **editorial grid**: 12 columns · gap 12px · side padding 32px. Heading and support occupy opposite halves; section headings can span eight columns while the support column stays shorter.
- **three card grid**: 3 columns · gap 12px. Three 376px-wide media cards across a 1152px inner field.
- **feature pair**: 2 columns · gap 12px. Two approximately 570px-wide main demonstrations with smaller capability tiles beneath.
- **question column**: max width 724px. Right-hand accordion paired with a heading in the left third.
- **pricing columns** (only for pricing pages): 4 columns · gap 0px. Four equal 294px plan columns with 16px inner padding and faint vertical separators.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions and segmented controls | 9999px (pill) |
|  | media and feature cards | 16px |
|  | directory focus corners | 4px |
| interactive demonstrations | small interface controls | 12px |
| enterprise product demonstrations | enterprise product panels | 20px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| shallow raised edge | `0px 0px 0px 0.5px rgba(0,0,0,0.125), 0px 1px 1px rgba(0,0,0,0.04), 0px 2px 4px rgba(0,0,0,0.04)` | White secondary actions and nested product panels. |
| stage inset | `inset 0px 0px 0px 0.5px rgba(0,0,0,0.075)` | A nearly invisible edge around large cream stages. |

### Surfaces

#### Canvas · level 0

**Use:** The continuous page ground.

**CSS:** `background: #fdfcfc; color: #000000`

**Observed:** Light throughout, including the footer.

**Transfer:** Let section spacing and fine rails organize the page instead of alternating large colored bands.

#### Cream stage · level 1

**Use:** Interactive scenes and feature media.

**CSS:** `background: #f5f3f1; border-radius: 16px; box-shadow: inset 0px 0px 0px 0.5px rgba(0,0,0,0.075)`

**Observed:** Broad, low-contrast rounded fields frame saturated objects or raised white fragments.

**Transfer:** Use as the stable ground beneath richer product material.

#### Raised interface · level 2

**Use:** Product examples nested inside stages.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.125), 0px 1px 1px rgba(0,0,0,0.04), 0px 2px 4px rgba(0,0,0,0.04); padding: 16px`

**Observed:** The object is visibly lifted only a little; overflow may be clipped by its outer stage.

**Transfer:** Show one legible task or result, not a dense full application.

#### Ruled architecture · level 0

**Use:** Container edges and chapter divisions.

**CSS:** `border-left: 1px solid rgba(0,0,0,0.05); border-right: 1px solid rgba(0,0,0,0.05)`

**Observed:** Horizontal rules meet vertical rails at small dot-like joints.

**Transfer:** Continue the same geometry through multiple sections without boxing every paragraph.

## Components

### Primary button

**Use:** The principal conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 20px; gap: 8px; background: #000000; color: #ffffff; border-radius: 9999px`

**Text style:** `button` — Inter 400 · 16px/1.5

**Observed:** Usually paired with a white alternative. Header versions are 36px high with 14px side padding; compact product actions can be 40px high.

**States:** Declared: hover background #44403b; focus-visible 1.5px solid #2b7fff outline with 2px offset; active transform returns to scale 1.

### Secondary button

**Use:** Sales, documentation and supporting actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 44px; padding: 0px 20px; gap: 8px; background: #ffffff; color: #000000; border-radius: 9999px; box-shadow: 0px 0px 0px 0.5px rgba(0,0,0,0.125), 0px 1px 1px rgba(0,0,0,0.04), 0px 2px 4px rgba(0,0,0,0.04)`

**Text style:** `button` — Inter 400 · 16px/1.5

**Observed:** A short label, sometimes followed by a small chevron; never a heavy outlined rectangle.

**States:** Declared: hover background #fdfcfc; focus-visible 1.5px solid #2b7fff outline with 2px offset.

### Navigation link

**Use:** Compact global navigation.

**CSS:** `padding: 8px 12px; border-radius: 18px; color: #000000`

**Text style:** `navigation` — Inter 400 · 14px/20px

**Observed:** A 64px header aligns a left wordmark, central links and right login/signup capsules. Product pages add a 56px contextual row; the compact product navigation remains visible during scrolling.

### Announcement band

**Use:** One concise release message above navigation.

**CSS:** `display: flex; justify-content: center; align-items: center; height: 48px; padding: 8px 16px; background: #f5f3f1`

**Text style:** `announcement` — Inter 400 · 14px/18px · tracking 0.01em

**Observed:** A small release mark, a short sentence and a white 32px-high discovery capsule form a centered horizontal unit.

### Segmented control

**Use:** Switching between product families or demonstrations.

**CSS:** `display: grid; height: 44px; border-radius: 9999px; box-shadow: inset 0px 0px 0px 0.5px #d7d2cc`

**Text style:** `button` — Inter 400 · 16px/1.5

**Observed:** Equal-width segments; active selection is a shallow white capsule, inactive labels are muted. Some media-stage tabs use a 12px rounded rectangle rather than a pill.

### Feature stage

**Use:** A capability demonstrated with an object or small working interface.

**CSS:** `position: relative; overflow: hidden; background: #f5f3f1; border-radius: 16px`

**Text style:** `support` — Inter 400 · 15px/22px · tracking 0.01em

**Observed:** One dominant visual above a bottom-aligned short heading and support line, with 20px caption side insets. Main pair cards are about 570px square; small supporting tiles carry a line icon near their upper edge.

**Transfer:** Keep the visual about one task, then state its benefit in one or two sentences.

### Editorial card

**Use:** Updates and case studies in a three-column grid.

**CSS:** `position: relative; overflow: hidden; background: #f5f3f1; border-radius: 16px; aspect-ratio: 1 / 1`

**Text style:** `article-title` — Inter 400 · 20px/1.35

**Observed:** The CSS describes the square media wrapper. Its title sits outside, 24px below, with 20px horizontal inset; category and date follow in small muted text.

### Question row

**Use:** Objection handling on product, enterprise and pricing pages.

**CSS:** `text-align: left; border-radius: 4px; color: #000000`

**Text style:** `question` — Inter 400 · 17px/25px · tracking 0.01em

**Observed:** A full-width trigger in a 724px column, approximately 55px tall for a single line. Text has 20px vertical padding with optical trimming; a small chevron is right-aligned. Dotted separators are separate layers, not thick borders.

**States:** Declared: hover state unspecified; focus-visible 1.5px solid #2b7fff outline with 2px offset.

### Directory link

**Use:** Footer navigation.

**CSS:** `display: block; padding: 9px 6px; margin-left: -6px; margin-right: -6px; border-radius: 4px; color: #000000`

**Text style:** `directory-link` — Inter 500 · 14px/1.5 · tracking 0.01em

**Observed:** Links read as a tight 28px vertical cadence due to optical text trimming. Muted Directory-label text heads each group; the brand/language column sits left of three link columns and a second row of groups.

**States:** Declared: hover color #777169; focus-visible 1.5px solid #2b7fff outline with 0px offset.

### Closing invitation

**Use:** The final conversion band above the footer.

**CSS:** `border-top: 1px solid rgba(0,0,0,0.05); border-bottom: 1px solid rgba(0,0,0,0.05)`

**Text style:** `closing` — Waldenburg 300 · 32px/36px

**Observed:** A 190px-high band contains 72px vertical padding, a left proposition and right-aligned Secondary button plus Primary button. The footer begins after this band with 120px top and bottom space.

## Imagery and graphics

### Living gradient instruments

**Use:** Signature hero object and recurring demonstration motifs.

**Observed:** Spheres look like luminous, finely grained materials rather than flat gradient logos. Warm orange/red/yellow, purple/pink/cyan and green/blue variants sit against cream. The central 256px sphere is larger than flanking 202px and 145px spheres, with faded partial neighbors at the stage edges.

**Transfer:** Every new landing page needs a tactile luminous object. Relate it to a product state or output; if no suitable media exists, the minimum equivalent is a convincing shaded gradient sphere with fine grain and a small white action control.

**Build:** Clip a 256px square to a circle. Layer broad radial color clouds: a pale warm highlight near the upper-left, a vivid center pool, and a dark complementary crescent toward the lower-right. Blur the internal clouds by about 24px while keeping the silhouette crisp. Add a subtle monochrome SVG turbulence layer at roughly 0.1 opacity using soft-light, plus a narrow soft rim highlight. Use scaled copies at 202px and 145px and cream-to-transparent edge masks; avoid a visible drop shadow under the sphere.

### Atmospheric media fields

**Use:** Backing for selected feature demonstrations and editorial artwork.

**Observed:** Soft-focus orange/brown or blue/green light fields have fine grain and darkened lower edges for white captions. UI fragments sit in front, sometimes extending beyond the field's top or side; color remains inside the rounded frame.

**Transfer:** Use a blurred original photograph or layered color field that evokes the product's material; pair it with one sharply rendered result.

**Build:** Fill a 16px-radius clipped panel with overlapping, oversized blurred radial ellipses in complementary warm or cool colors. Add fine turbulence at low opacity, then a transparent-to-black bottom gradient reaching about 0.35 opacity. Keep the caption above this darkening layer and the white interface above both.

### Fine scientific geometry

**Use:** Principle cards, benefits and abstract technical explanations.

**Observed:** Hair-thin black ellipses, nested circles, dotted axes and wireframe cubes occupy roughly 202px squares with ample cream around them. Diagrams use almost no filled area and sit above bottom captions.

**Transfer:** Include fine geometric reasoning alongside luminous material. Map a new benefit to growth curves, branching paths, nested contours or modular construction rather than a stock pictogram.

**Build:** Use a 202px SVG viewBox with 0.5px–1px black strokes, no fill, and occasional 1px dash patterns. Draw six offset circles sharing one tangent, a subdivided isometric cube, or two ellipses linked to a common axis. Extend dotted construction axes beyond the primary shape.

### Human use-case films

**Only for:** human-service product pages

**Use:** Opening demonstrations and customer proof.

**Observed:** Warm natural-light footage of people in everyday environments appears in a wide 794px-by-600px expanded tile beside narrow collapsed tiles. Short white overlay labels sit near the top; translucent chat fragments and compact controls provide context. A later proof film uses a 1152px-by-648px frame.

**Transfer:** Use real people engaged in the task, cropped closely enough to show expressions; maintain warm cinematic light rather than abstract corporate stock scenes.

### Output cover carousel

**Only for:** creative-output product pages

**Use:** Media-first opening before the product promise.

**Observed:** A 1200px-by-500px scene presents a large square central cover, angled side covers receding in perspective, arrows, a white play circle and a compact filter control below. The light page ground stays visible around the artwork.

**Transfer:** Use representative finished outputs, not generic app windows. Keep perspective shallow and make the selected output clearly dominant.

**Build:** Arrange square output cards in a perspective container: center card faces front, adjacent cards rotate on the Y axis toward the center and recede in scale. Clip artwork to rounded corners; overlay a thin playback line near the lower edge and a white circular control at its start.

### Recommended-plan color field

**Only for:** pricing pages

**Use:** A single recommended tier and the calculator result.

**Observed:** A noisy blue pool fades into deep red with a warm orange lower edge. White text sits at the top, while a full-width white action anchors the bottom of a 524px square. Ordinary plans keep cream cards.

**Transfer:** Reserve the rich field for the recommended decision, not every plan.

**Build:** Layer an oversized soft blue radial pool at the upper-left over a red ground, add an orange radial glow at the bottom-right, and apply low-opacity monochrome turbulence. Clip to 16px corners. Keep sufficient dark red or blue beneath white text; exact color stops are not essential.

### Integration plane

**Only for:** enterprise integration sections

**Use:** A quiet systems-connectivity scene.

**Observed:** A pale isometric grid with widely spaced monochrome partner marks fades radially into the page. It is a diagrammatic backdrop, not a field of floating full-color badges.

**Transfer:** Arrange relevant integrations on a fine shared plane and make connections feel native rather than decorative.

**Build:** Create horizontal and vertical 1px lines using black at 7%, transform the plane into an isometric diamond, and place low-contrast gray marks on selected intersections. Apply a radial opacity mask fading to the canvas at the perimeter.

### Icons

**Observed:** Small outline SVGs, most often 16px, 18px or 20px, with 1.5px strokes; rounded caps dominate arrows and controls, while some technical marks use butt caps. Black or warm gray is the norm; play symbols are solid inside white circles.

**Transfer:** Use a consistent thin outline set at these sizes. Keep large conceptual diagrams separate from interface icons.

## Section recipes

How recurring sections are built.

### First screen: Promise over living stage

**Observed:** A 48px cream Announcement band sits above a 64px light navigation row. The content begins with 120px breathing room: a two-line, 48px light headline occupies the left half, while a short 16px explanation sits in the right half. Two 44px pills sit 32px below the headline. A roughly 1180px-wide Cream stage begins beneath the text with a three-part tab strip, then a centered 256px luminous sphere and smaller neighbors, white play control and muted category captions. Layers run canvas, cream stage, textured objects, controls, then captions. Within the first 900px the promise, explanation, paired actions, tabs, main sphere and the beginning of captions are visible; the stage's lower conversion and social-proof grid continue below.

**Transfer:** Preserve the split promise/support layout and a tangible interactive stage even when the new product has no media: construct Living gradient instruments and connect them to meaningful output states. Enterprise openings can center the same display recipe above one black action and a paired product demo. Creative-output openings can put Output cover carousel before the headline; pricing opens directly with a heading, family selector and plan grid.

**Avoid:** Do not turn this into a centered oversized slogan on a full-bleed gradient, or replace the main object with an unframed application screenshot.

**Text style:** `display` — Waldenburg 300 · 48px/52px · tracking -0.02em

### Chapter heading pair

**Observed:** Faint rails and small joint marks precede 160px of chapter lead-in. A muted Eyebrow, when present, sits 28px above a 36px heading. Heading and action are left, support copy is right; the action is 32px below the heading and the block ends with 40px space. Centered variants keep copy near 576px wide.

**Transfer:** Introduce a new capability with a compact benefit headline and a separate concrete explanation rather than duplicating the headline in the paragraph.

**Text style:** `heading` — Waldenburg 300 · 36px/42px

### Demonstration bento

**Observed:** Feature stage pairs use 12px gutters and 16px corners. Two large scenes lead into three or four smaller feature tiles; mixed-width variants use a broad interface beside a narrow material object. Captions remain near the bottom; UI panels may be intentionally clipped by the outer frame.

**Transfer:** Use a dominant task and result above smaller capabilities. Alternate an atmospheric field with a cream interface scene to keep color concentrated.

### Proof with editorial weight

**Observed:** A low-contrast six-column logo grid uses 148px-by-26px marks and 48px row spacing. Richer proof uses a staggered composition of 320px and 488px square cards with white captions on darkened lower edges, or one large customer film followed by three quote columns.

**Transfer:** Use earned proof, with logos subdued and case-study content allowed richer imagery. Do not treat every proof item as an identical badge.

### Research instrument

**Observed:** A 1152px-by-496px Cream stage has 96px vertical and 64px horizontal padding. A horizontal rail of fine tick marks supports a tall selected marker, a short centered title above and summary/date below, with 40px white circular arrow controls at the sides.

**Transfer:** Use this unusually sparse instrument treatment for a release history, maturity scale or changing product state. Keep the selected state more important than the number of entries.

**Text style:** `body` — Inter 400 · 16px/1.5 · tracking 0.01em

### Principle triptych

**Observed:** Three 376px-wide cream cards have 12px gaps, roughly 202px geometric diagrams near the center, and compact bottom captions. Large untouched areas make fine strokes feel intentional.

**Transfer:** Explain three distinct trust or operating principles with Fine scientific geometry. The subjects should belong to the new product, not to a fixed company-values template.

### Commercial decision

**Observed:** Pricing begins with a 48px headline, product-family Segmented control and a billing capsule. Four equal columns contain 262px-by-200px plan tops, black full-width pills, dotted feature rows and bottom-aligned allowances. A later two-column calculator pairs simple numbered inputs and a usage slider with Recommended-plan color field. Comparison tables use narrow columns and faint dotted row rules.

**Transfer:** Separate immediate plan choice from detailed comparison; preserve a single rich recommendation and keep the rest neutral.

### Enterprise reassurance

**Observed:** Centered heading/support pairs introduce product panels, security selectors and Integration plane. A three-step service line uses a 12px pale horizontal track, black joint dots and short descriptions underneath before the questions.

**Transfer:** Use a visible onboarding or implementation path to turn enterprise reassurance into a concrete process.

### Questions and closing directory

**Observed:** A 36px heading sits in the left third with Question row triggers in the right two-thirds. The next conversion is Closing invitation, then a light footer with a left brand/language column and six directory groups arranged in three columns across two rows. All five page types end with this same restrained band and directory treatment.

**Transfer:** Make the final proposition concise and relevant to the page's purpose; organize footer groups by how users seek information, not by repeating every preceding section.

## Page flow

**Storyline:** Promise → tangible demonstration → earned proof → capability chapters → deeper technical or commercial detail → objections → restrained invitation and directory.

### Broad platform landing page

1. **Promise** — Split headline and support above a living-object stage.
2. **Social proof** — Subdued logo grid followed by paired platform overview.
3. **Capability chapters** — Eyebrow-led introductions, demonstration bentos and compact customer strips.
4. **Technical depth** — API rows with supporting code panels.
5. **Credibility** — Editorial case-study mosaic, research instrument, principle triptych and update cards.
6. **Closing call** — Ruled invitation and full directory.

**Transfer:** Give breadth a series of tangible demonstrations rather than one exhaustive feature list.

### Plan selection and cost explanation

1. **Pricing** — Direct display heading, family selector, four-column plan grid and separate business tier row.
2. **Cost clarification** — Usage calculator with vivid recommendation card.
3. **Alternative route** — Program offer with wireframe step illustration.
4. **Comparison** — Tabbed feature matrix with narrow plan columns.
5. **Objection handling** — Long question column.
6. **Closing call** — Ruled invitation and directory.

**Transfer:** Prioritize the initial decision, then progressively expose calculation and comparison detail.

### Creative-output product landing page

1. **Product demonstration** — Perspective output-cover carousel before the promise.
2. **Capability chapters** — Access-point cards, selectable output styles, editing bento and playable examples.
3. **Workflow depth** — Several product-route chapters each followed by demonstrations and testimonials.
4. **Technical depth** — API example and compact category directory.
5. **Pricing and objections** — Comparison matrix and question rows.
6. **Closing call** — Ruled invitation and directory.

**Transfer:** Lead with the quality of finished work, then reveal how different audiences produce it.

### Enterprise evaluation and sales conversion

1. **Promise** — Centered headline, concise explanation and one sales pill above a paired demonstration.
2. **Social proof** — Logos and staggered customer-story mosaic.
3. **Capability chapters** — Two large product panels and security-selector illustration.
4. **Operational reassurance** — Integration plane and a three-step implementation line.
5. **Objection handling** — Security, residency and deployment questions.
6. **Closing call** — Ruled invitation and directory.

**Transfer:** Pair emotional polish with visibly concrete implementation, support and security details.

### Human-service product landing page

1. **Promise** — Split promise and explanation with paired actions.
2. **Demonstration** — Wide human-use film with narrow adjacent use-case tiles.
3. **Social and quantified proof** — Muted logo grid, three benefit diagrams and a results headline above a large customer film.
4. **Capability chapters** — Mixed-width workflow and analytics bento, resource rows, integrations and living-object use-case stage.
5. **Adoption routes** — Three vertical paths with actions and compact feature lists.
6. **Objection handling** — Editorial stories then question rows.
7. **Closing call** — Ruled invitation and directory.

**Transfer:** Start with a recognizable human situation, then show the operational controls behind it.

## Writing

Confident and practical, with warmth carried by natural-language benefits rather than jokes. Technical specificity supports the promise; short, direct actions keep the page usable.

**Do not copy:** Do not reuse ElevenLabs names, logos, proprietary artwork, customer identities, testimonials, release dates, plan prices, performance numbers, language counts, certifications or superiority claims. Replace them with substantiated content and original assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use direct imperatives and occasional 'your' for the reader; use 'we' for commitments and explanations. Product descriptions often begin with an active verb rather than a company name.
- **Rhythm:** Headlines are generally compact clauses, sometimes a sequence of three verbs. Supporting copy uses one or two matter-of-fact sentences; action labels are usually two or three words. Avoid exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | An accessible outcome, not a technical inventory. | 4–11 words | “Bringing technology to life”<br>“Conversational agents that feel human” |
| Chapter heading | Active verbs assemble a complete workflow into a concise promise. | 6–12 words | “Create, edit, and localize in one AI platform”<br>“Generate music programmatically” |
| Supporting line | Name concrete capabilities and the operation they enable. | One or two short sentences | “Configure, deploy and monitor conversational agents.”<br>“Build your first agent in minutes - no engineering required.” |
| Primary action | Verb plus immediate next step; sales and self-serve paths coexist. | 2–4 words | “Build for free”<br>“Explore docs”<br>“Talk to sales” |
| Question | Ask the buyer's practical question in their own terms. | One short question | “Is there an API?”<br>“What channels can I deploy agents on?” |

**Words and phrasing to use:** create; configure; deploy; monitor; control; connect; built for; across; in one platform; at scale

**Avoid:** revolutionary magic; game-changing; unleash limitless possibilities; disrupt everything; !!!

**Rules:**

- State an outcome first, then explain the mechanism.
- When using a performance or scale claim, make it verifiable and put it near relevant proof.
- Use short capability labels, then a sentence that explains what the reader can do.
- Keep pricing caveats and rights limitations plain and close to the decision.
- Let testimonials sound like real speech; keep surrounding copy factual.

## Do's and Don'ts

### Do

- Keep default hero type at 48px/52px and weight 300.
- Use the 36px/42px recipe for chapter headings rather than escalating every chapter to hero scale.
- Preserve 12px gutters between cream media frames.
- Make the luminous object tactile through internal shading and fine grain.
- Keep 44px primary and secondary pills paired with an 8px gap.
- Give white nested panels a 0.5px edge and shallow 1px–4px shadows.
- Use 160px chapter lead-ins to separate major ideas.
- End with the 190px ruled invitation and a light directory.

### Don't

- Do not use black page sections as the default backdrop; the canvas remains warm white.
- Do not turn muted #777169 support text into a saturated link color.
- Do not add heavy card outlines where a 0.5px inset edge is sufficient.
- Do not use bold display headings in place of weight 300.
- Do not replace thin geometric diagrams with filled cartoon illustrations.
- Do not give every plan a colorful recommendation field.
- Do not make small footer links oversized; preserve the 14px medium-weight directory rhythm.
- Do not apply interface-scale typography to marketing paragraphs; use 16px body or 15px support.

## Motion and responsive

### Motion

**Observed:**

- Actions declare background-color, color, box-shadow and border-color transitions of 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Many text links declare color transitions with the same duration and curve.
- Some carousel labels declare opacity transitions of 0.3s; object and media stages include selectable states, playback controls and arrows.

**Transfer:**

- Keep button feedback shallow and primarily tonal; use the declared 0.15s transition for capsule surfaces.
- Make the selected demonstration visibly dominant through scale, contrast and caption state, not by animating all page text.

**Unknown:**

- Exact sphere shader motion, carousel movement timing and scroll choreography are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1024px, 1280px and 1536px; some layouts also use 400px, 848px.
- The opening markup changes from a desktop split to a stacked layout and places actions after the support on narrower widths.
- Some media rows use horizontal overflow and scroll snapping.

**Transfer:**

- On narrow screens, preserve the living central object and show partial side objects instead of shrinking all objects equally.
- Stack promise and support while keeping paired pills close to their explanation.
- Allow comparative grids and output carousels to scroll; do not squeeze all plans into unreadable columns.
- Collapse the directory into fewer columns while retaining category groupings.

**Unknown:**

- Exact mobile spacing, type sizes and rendered navigation behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
