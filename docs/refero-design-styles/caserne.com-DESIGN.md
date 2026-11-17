# Caserne — airborne portfolio editorial

## Overview

A light, image-led identity with the economy of an exhibition checklist and a soft, drifting atmosphere behind it. Regular grotesk type, black and gray text, tiny glass controls and expansive photographic compositions give creative products a confident but approachable presence. Color belongs mostly to the work itself; the surrounding interface stays pale and sparse.

### Essentials

- The headline behaves like a paragraph, not a billboard: regular grotesk at 30px/1 with -0.015em tracking, occupying the right two thirds while the left third stays open.
- An editorial preface gives way to a cinematic object: a 96px utility band, a compact statement, 180px of breathing room and a full-width 16:9 moving-image stage.
- Controls resemble tiny glass lozenges: 27px high, 6px 12px padding, 9999px radius, 15px regular text and a 20px backdrop blur rather than solid conversion-button fills.
- A pale atmosphere floats behind sharp content: #f6f6f6 canvas, heavily blurred muted color and a white veil; orange #ff5205 is restricted to text-link hover while rich color lives inside media.
- Images form an uneven exhibition hang: a 24-column framework with 10px gutters, 6px image corners, alternating 1063px and 467px media widths at desktop, and 80px between editorial rows. Use composed product photographs or crafted demonstration stills when campaign imagery is unavailable.
- Captions whisper beneath dominant images: 15px/1.05, weight 400, -0.03em tracking, 8px below media, with black names and gray descriptions separated by 20px.
- The closing invitation stays human-scale: a 1px rule, a short greeting in the left third, a 30px two-line invitation and gray text action in the right two thirds, followed by 180px of open space before the utility footer.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5205` | `--color-accent` | link, accent | Hover color for the large inline text links; not a page fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, link | Primary text and monochrome brand symbol. |
| Soft gray text | `#949494` | `--color-muted` | text, link | Secondary text and inline links; black at 40% opacity over the pale canvas produces this visible gray. |
| Fine gray rule | `#c5c5c5` | `--color-rule` | border | Section separators; black at 20% opacity over the canvas. |
| Pale canvas | `#f6f6f6` | `--color-canvas` | background | Underlying page canvas, visible through the atmospheric layer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| capability directories | Translucent white | `#fbfbfb` | `--color-card` | surface | White at 50% opacity over the canvas, allowing the atmosphere underneath to remain visible. |

## Typography

- **Plain** — All headings, prose, captions and controls. Unembellished contemporary grotesk with compact spacing and a deliberately regular weight. If unavailable, use **Inter**. Use 400 throughout; preserve the tight spacing and modest headline scale. Font stack: "Plain", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| statement | Plain | 400 | 30px | 1 | -0.015em | Opening paragraph, large inline links and closing invitation. |
| section-label | Plain | 400 | 20px | 1 | -0.0225em | Section labels, text-only proof lists and capability titles. |
| body-caption | Plain | 400 | 15px | 1.05 | -0.03em | Prose, image names and descriptors, utility page labels and directory details. |
| control | Plain | 400 | 15px | 1 | -0.03em | Navigation, glass actions and footer controls. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| browsable catalogs | filter | Plain | 400 | 15px | 1 | normal | Category filter buttons. |

**Notes:**

- Use size, color and position for hierarchy, not bold cuts. A project title can be a semantic heading while retaining the body-caption recipe.
- The largest interface type is only twice the caption size. Large lettering within campaign photography is artwork, not a second headline font.
- Tracking is -0.5px across the main size range; the em equivalents therefore differ by recipe.

## Layout

**Density:** Airy at section scale and compact inside text blocks; expansive empty fields surround tightly led captions and paragraphs.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Vertical padding in glass controls; a separate declared compact gap token. |
| 8px | Media-to-caption separation. |
| 10px | Outer page margins, gallery gutters and footer action gaps. |
| 12px | Horizontal control padding and ruled-section top padding. |
| 16px | Header top inset and directory-card padding. |
| 20px | Caption name-to-description gap and compact flex spacing. |
| 22px | Links inside the navigation capsule. |
| 30px | Portrait-row separation. |
| 80px | Editorial gallery row gap. |
| 120px | Declared major rhythm token. |
| 180px | Major chapter separation and space before the footer. |

### Containers and grids

- **page-grid**: 24 columns · gap 10px · side padding 10px. Fluid full-width grid without a fixed maximum. At 1440px the inner area is 1420px. Major text starts after the first eight columns, leaving one third open.
- **editorial-gallery**: 24 columns · gap 10px. Span images across different column counts: centered 18-column landscapes around 1063px, offset 16-column features around 943px and smaller 8-column items around 467px. Preserve substantial unoccupied grid regions.
- **catalog-grid** (only for browsable catalogs): 3 columns · gap 10px · side padding 10px. Equal-width 467px columns at desktop, with varied media aspect ratios and 120px between gallery rows.
- **directory-grid** (only for capability directories): 2 columns · gap 10px. Two columns inside the right-hand 943px content region; each card has two internal text columns.
- **portrait-grid** (only for organization profiles): 4 columns · gap 10px. Four portraits across the right two thirds, with 30px row gaps.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | glass-controls | 9999px (pill) |
|  | media | 6px |
| capability directories | directory-cards | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| glass-inner-edge | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -1px 1px 0px inset` | Subtle top and bottom edges of glass controls; accompany with a soft drop-shadow filter rather than card elevation. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light ground.

**CSS:** `background: #f6f6f6`

#### Atmospheric veil · level 0

**Use:** Continuous soft-focus backing behind text and media.

**CSS:** `background: rgba(255,255,255,0.8); backdrop-filter: blur(60px)`

**Observed:** Broad pale green, cream, blue-gray and warm gray clouds remain indistinct beneath a white veil. Sharp content floats in front; this is not a gradient-filled section boundary.

**Transfer:** Use the Atmospheric color field recipe behind a fixed veil; keep enough white for small black text to remain crisp.

#### Glass capsule · level 1

**Use:** Navigation and short utility actions.

**CSS:** `border-radius: 9999px; backdrop-filter: blur(20px) saturate(1.8) brightness(1.1); box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -1px 1px 0px inset; filter: drop-shadow(rgba(0, 0, 0, 0.15) 0px 4px 16px)`

**Observed:** Nearly transparent lozenges with faint optical edges. An overlay radial highlight subtly shades the top.

**Transfer:** Retain the underlying atmosphere instead of replacing it with a flat white button.

#### Directory card · level 1

**Only for:** capability directories

**Use:** Grouped capability descriptions.

**CSS:** `background: rgba(255, 255, 255, 0.5); border-radius: 6px; padding: 16px`

**Observed:** Pale panels have no raised shadow; their soft fill is enough to separate adjacent groups.

**Transfer:** Group concise titles and short lists, not long feature essays.

## Components

### Floating navigation

**Use:** Persistent site navigation.

**CSS:** `display: flex; gap: 22px; padding: 6px 12px; height: 27px; box-sizing: border-box; border-radius: 9999px; backdrop-filter: blur(20px) saturate(1.8) brightness(1.1)`

**Text style:** `control` — Plain 400 · 15px/1 · tracking -0.03em

**Observed:** A compact shared Glass capsule at the upper right contains four plain links. A separate language capsule sits beside it; a 27px black emblem anchors the far left. The fixed header has 16px top and 10px side padding.

### Glass action

**Use:** Contact, social and utility actions.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 6px 12px; height: 27px; box-sizing: border-box; color: #000000; border-radius: 9999px; backdrop-filter: blur(20px) saturate(1.8) brightness(1.1); box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px inset, rgba(0, 0, 0, 0.05) 0px -1px 1px 0px inset; filter: drop-shadow(rgba(0, 0, 0, 0.15) 0px 4px 16px)`

**Text style:** `control` — Plain 400 · 15px/1 · tracking -0.03em

**Observed:** Content-width actions use the Glass capsule surface. Language and theme utilities are gray rather than black; no prominent filled primary-button variant is used.

### Inline statement link

**Use:** Clickable key nouns inside statements and the closing text action.

**CSS:** `color: rgba(0, 0, 0, 0.4); transition: color 0.2s; text-decoration: none`

**Text style:** `statement` — Plain 400 · 30px/1 · tracking -0.015em

**Observed:** Link words share the surrounding paragraph's size and baseline. The lower-contrast words create a second reading layer without underlines.

**States:** Declared: hover color #ff5205; focus-visible not specified.

### Media card

**Use:** Large image or video proof with an understated caption.

**CSS:** `border-radius: 6px; overflow: hidden; position: relative; max-width: 100%`

**Observed:** The figure alone is rounded. The caption sits outside it; the entire image-and-caption group is linked. Media retains its own aspect ratio rather than conforming to one uniform card height.

**Transfer:** Pair photographs, demonstration clips or designed stills with concise names and one short outcome phrase.

### Caption pair

**Use:** Labeling media without competing with it.

**CSS:** `display: flex; gap: 20px; margin-top: 8px`

**Text style:** `body-caption` — Plain 400 · 15px/1.05 · tracking -0.03em

**Observed:** A black name precedes a gray descriptor on the same baseline. Text is directly on the page, not on a caption panel.

### Ruled invitation

**Use:** Human closing call on every page type.

**CSS:** `display: grid; grid-template-columns: repeat(24, 1fr); gap: 10px; border-top: 1px solid rgba(0, 0, 0, 0.2); padding-top: 12px; margin-top: 180px`

**Text style:** `statement` — Plain 400 · 30px/1 · tracking -0.015em

**Observed:** A short greeting occupies eight columns; the remaining sixteen hold a one-line invitation with an Inline statement link directly below. It is a compact 73px block, not an oversized banner.

### Utility footer

**Use:** Final navigation and attribution.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 0px 10px 10px; margin-top: 180px`

**Text style:** `control` — Plain 400 · 15px/1 · tracking -0.03em

**Observed:** Small copyright sits at far left. Contact, community, social and theme Glass actions align at far right with 10px gaps. The same ending serves editorial, directory and catalog layouts.

### Capability card

**Only for:** capability directories

**Use:** A scannable service or feature family.

**CSS:** `display: grid; grid-template-columns: 1fr 1fr; padding: 16px; background: rgba(255, 255, 255, 0.5); border-radius: 6px; height: 190px; box-sizing: border-box`

**Text style:** `section-label` — Plain 400 · 20px/1 · tracking -0.0225em

**Observed:** Black title on the left, a tight gray body-caption list on the right. Two cards sit across the main content region.

### Filter capsule

**Only for:** browsable catalogs

**Use:** Industry or capability filtering.

**CSS:** `height: 27px; padding: 6px 12px; box-sizing: border-box; border-radius: 9999px; color: rgba(0, 0, 0, 0.4); backdrop-filter: blur(20px) saturate(1.8) brightness(1.1)`

**Text style:** `filter` — Plain 400 · 15px/1

**Observed:** Filters sit beside a small catalog-mode control in the utility band, aligned with the right-two-thirds text region.

**States:** Declared: hover not specified; focus-visible outline 1px solid #000 with outline-offset 2px.

## Imagery and graphics

### Cinematic proof

**Use:** The opening's dominant visual and occasional gallery motion.

**Observed:** Full-bleed 16:9 footage follows the opening statement. Aerial off-road action and dust are overlaid with thin white typographic framing within the film itself. The media is much larger than the interface typography.

**Transfer:** Show the product in use with a strong physical or visual gesture. Without film, use a composed full-width photographic still or an animated demonstration with a convincing focal point; retain the 16:9 stage.

### Editorial project photography

**Use:** The main visual storytelling system.

**Observed:** A mix of street-level applications, identity materials on tactile fabric, glossy packaging, apparel details, staged product still lifes and event photography. Crops alternate portrait, square and landscape. Colors can be saturated inside the image while the surrounding canvas stays pale.

**Transfer:** Photograph the new product's materials, real-world use and finished outputs. Mix close tactile details with wider contextual views; use one large centered scene between smaller offset groupings.

### Atmospheric color field

**Use:** A signature backing throughout the interface, visible most clearly in open spaces.

**Observed:** Out-of-focus color masses appear greenish near the opening, then cool gray, beige and pale blue through later sections. They have no hard edges or recognizable picture content.

**Transfer:** Keep this soft chromatic depth even if no photographic work is available. Match the low-contrast haze rather than introducing decorative neon gradients.

**Build:** Place oversized overlapping image fragments or soft elliptical fields behind the page: pale olive at upper left, blue-gray near lower center, warm beige off one side. For a CSS equivalent use radial gradients with rgba(100,134,54,0.18), rgba(59,126,191,0.12) and rgba(177,156,123,0.18), each fading to transparent across roughly 600px; blur 60px and add the Atmospheric veil above. Keep all text and media on a sharp foreground layer.

### People photography

**Only for:** organization profiles

**Use:** A broad group scene followed by an individual directory.

**Observed:** A natural-light group portrait fills almost the entire content width. Individual waist-up portraits have neutral studio or office backgrounds, relaxed clothing and consistent 3:4 framing; the grid occupies the right two thirds.

**Transfer:** Use real people with varied poses and restrained environmental detail; preserve consistent framing rather than identical expressions.

### Icons

**Observed:** A small black 27px emblem anchors the header. Media affordances use compact white filled SVGs around 16px; the video control uses a white 19px symbol inside a small translucent square.

**Transfer:** Keep icons sparse and functional, using filled monochrome silhouettes at these sizes. Use the new identity's own compact symbol for the corner anchor.

## Section recipes

How recurring sections are built.

### First screen: Offset statement and cinema

**Observed:** A continuous Atmospheric veil backs the first screen. Floating navigation sits above it, with a small emblem left and a capsule at upper right; a tiny product label aligns to the main content start. After a 96px utility band, a 30px regular statement occupies the right two thirds in about four tightly led lines, with selected nouns expressed as gray Inline statement links. The left third remains open. A 180px pause separates the statement from a full-width 1440px by 810px film stage beginning around 396px down the page. Within the first 900px the complete statement, navigation and upper 504px of the main visual are visible; the film's lower part and gallery fall below. No separate support paragraph or filled CTA row interrupts the composition.

**Transfer:** Write a concise positioning paragraph and let a single strong product-use scene carry the visual weight. Use a crafted still when motion is unavailable. Organization profiles use a longer paragraph followed by a wide people photograph; catalogs replace the statement with compact filters and begin the gallery immediately below the utility band.

**Avoid:** Do not substitute a centered oversized slogan, split-screen dashboard hero or pile of CTA buttons for the small offset statement and broad image stage.

**Text style:** `statement` — Plain 400 · 30px/1 · tracking -0.015em

### Uneven exhibition hang

**Observed:** Media cards use the editorial-gallery grid. Large centered landscapes alternate with asymmetrical groups of two or three smaller items; unused columns create conspicuous negative space. Caption pairs sit directly below each image. Rows are separated by 80px, with 180px before the gallery chapter.

**Transfer:** Vary image spans and aspect ratios to establish a visual rhythm, rather than treating every proof item as equally important.

### Text-only proof index

**Observed:** A thin rule and 12px top padding introduce a gray section-label in the left third; two columns of black 20px names occupy the right two thirds. A gray inline continuation link closes the list.

**Transfer:** Use concise partner, integration, publication or customer names as a typographic proof field, without requiring logos.

### Invitation and utility ending

**Observed:** The Ruled invitation returns to the opening's third/two-thirds alignment and statement typography. After 180px of empty atmosphere, the Utility footer provides the final slim row. This remains the ending across all page types.

**Transfer:** Close with a short human greeting, one direct invitation and one text action; preserve the low-key footer instead of creating a second sales section.

### Labeled directory chapter

**Only for:** information-rich organization or capability pages

**Observed:** A gray section-label anchors the left third; the right region holds ruled key-value rows, a compact year-indexed recognition list, Capability cards or a portrait grid. Chapters are separated by 180px.

**Transfer:** Keep the section label stationary in the visual hierarchy while changing the right-hand content structure to suit facts, capabilities or people.

### Catalog exhibition

**Only for:** browsable catalogs

**Observed:** A compact filter utility strip opens directly onto three equal columns of Media cards. Tops align by row while differing image heights leave air below shorter items; captions remain outside the media.

**Transfer:** Use a row-based gallery with varied aspect ratios, not a tightly packed masonry wall.

## Page flow

**Storyline:** Positioning or browsing context → image-led proof or structured detail → credibility → human invitation → minimal utilities.

### Image-led marketing landing page

1. **Positioning** — Small offset statement with gray linked nouns.
2. **Demonstration** — Full-width cinematic scene.
3. **Proof** — Asymmetric exhibition of contextual and tactile imagery with tiny captions.
4. **Credibility** — Text-only names arranged under a ruled label.
5. **Closing call** — Compact invitation followed by an airy utility footer.

**Transfer:** Let selected uses and outcomes demonstrate the new product; vary the number and ordering of proof blocks while preserving the image/text scale contrast.

### Organization or capability information page

1. **Context** — Longer offset introduction.
2. **Human proof** — Wide natural-light group photograph.
3. **Practical information** — Ruled key-value directory.
4. **Credibility** — Year-indexed recognition list.
5. **Capabilities** — Two-column pale-card directory.
6. **People** — Four-column portrait grid within the right region.
7. **Closing call** — Shared invitation and utility footer.

**Transfer:** Use structured detail chapters for the new product's process, support or organization; keep their headings modest and gray.

### Browsable work or product catalog

1. **Orientation** — Small mode and filter capsules.
2. **Exploration** — Three-column image gallery with varying aspect ratios and caption pairs.
3. **Closing call** — Shared ruled invitation and utility footer.

**Transfer:** Use products, applications or case studies as the catalog items; preserve the editorial breathing room between rows.

## Writing

Confident, culturally aware and conversational. Broad positioning is balanced by concrete names, tangible outputs and brief outcome phrases; the final invitation is warm rather than promotional.

**Do not copy:** Do not reuse Caserne's identity, project artwork, customer names, proprietary claims, founding details, awards or experience numbers as claims for a new product. Source examples illustrate phrasing only.

- **Addressing the reader:** Introductions describe the organization, then move to 'our' and 'we'. Closing copy directly invites the reader into a conversation.
- **Rhythm:** Compact multi-clause opening paragraph; short noun labels and three-to-eight-word caption phrases; a two-line closing exchange. Sentence case dominates and punctuation stays restrained.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning | State category, differentiator and consequence in a connected paragraph. | About four compact display lines for a landing introduction. | “Our tightly knit team brings exceptional craft to every challenge, creating work that stands apart and drives culture forward.” |
| Media descriptor | A short change or benefit phrase rather than an explanatory paragraph. | 3–8 words. | “From Projection to Amplification”<br>“A New Standard for Healthy Living” |
| Section label | Plain functional noun, without a promotional setup. | 1–2 words. | “Selected Clients”<br>“Services” |
| Closing invitation | Short greeting, direct challenge, conversational action. | One short sentence and a two-word action. | “Bring us a challenge.”<br>“Let’s talk.” |

**Words and phrasing to use:** craft; clarity; character; thinking; ideas; challenge; category-defining

**Avoid:** revolutionary platform; unlock limitless possibilities; best-in-class; act now; all-in-one solution

**Rules:**

- Let image captions communicate a transformation in a phrase, not a case-study abstract.
- Keep section names functional and concrete.
- Use experience or recognition claims only when they can be substantiated for the new product.
- Keep the closing action conversational rather than transactional.

## Do's and Don'ts

### Do

- Set the main statement at 30px/1 and weight 400.
- Align statement and detail regions after the first eight columns of a 24-column grid.
- Keep page margins and grid gutters at 10px.
- Round media by 6px while leaving captions outside the figure.
- Use 27px-high glass controls with 6px 12px padding.
- Separate major chapters and the footer with 180px of air.
- Keep gray descriptors at 15px/1.05 beside black image names.
- Carry the pale blurred atmosphere through empty areas, not just the opening.

### Don't

- Do not turn 30px statements into bold 72px display headlines.
- Do not convert the 27px glass controls into oversized solid orange CTA buttons.
- Do not make every gallery image the same height or width.
- Do not add drop shadows to project photographs; optical shadows belong to glass controls.
- Do not use the orange hover accent as a full-width marketing background.
- Do not replace the text-only proof list with a boxed logo carousel.
- Do not use uppercase tracked eyebrows as the main section-label treatment.
- Do not compress the 180px ending pause into a dense multi-column sitemap.

## Motion and responsive

### Motion

**Observed:**

- Large inline links declare color 0.2s and orange hover.
- Glass surfaces declare filter, transform and background transitions of .2s cubic-bezier(0.19,1,0.22,1), plus backdrop-filter .6s with .8s delay for actions and 1s for navigation.
- Media-related elements declare opacity 0.2s; a 0.5s opacity transition also occurs.

**Transfer:**

- Keep linked nouns responsive through the subtle color transition, not a new button treatment.
- Use the declared glass transition recipe when implementing the capsule's optical effects.

**Unknown:**

- Actual animation triggers and motion paths of the background field.
- Video playback controls and full moving-image sequence.

### Responsive

**Observed:**

- CSS declares width breakpoints at 991px, 1023px, 1024px, 1280px, 1600px and 1728px.
- The desktop grid is fluid and has no fixed max-width container.

**Transfer:**

- For narrow layouts, preserve the contrast between compact type and dominant media; reduce the open left column before shrinking body text.
- Adapt the editorial hang into fewer columns while retaining varied aspect ratios and external captions. These are implementation recommendations.

**Unknown:**

- Exact mobile navigation, column collapse rules, spacing changes and type sizes.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
