# Analogue — optical theatre, editorial soul

## Overview

A cinematic product showcase with the sensibility of a fashion editorial and the clarity of an industrial object study. White space, near-black scenes and cool blue-grey light alternate around tightly set grotesk headlines and slender, narrow serif storytelling. Large polished product renders share the stage with grainy, intimate lifestyle photography; text density is low in the scenes and unusually generous in the editorial interludes.

### Essentials

- The object gets the opening headline's space: a 1400px × 820px rounded blue light stage within a white first screen, a modest 34px product title above a centered 736px × 409px object, not a giant text-led hero.
- Two typographic personalities do different jobs: Graphik at 150px/1.2 with -10px tracking names chapters, while narrow Garamond at 40px/0.9 with -0.9px tracking tells the story in flowing paragraphs.
- Blue acts like an optical signal, not a page theme: #002fff marks actions and one selected proof tile; broad chromatic fields are soft blue-to-grey light, with white and near-black carrying most of the page.
- Controls are little rounded rectangles, never pills: 10px clipped action corners, 15px inner fills, 20px media cards and 30px large light stages; the main purchase control is 296px × 50px.
- A cinematic reveal is a signature device: a large blurred photographic or object scene carries a crisp 150px white chapter title, then resolves into detailed proof. Use a staged still-image pair when there is no animation or 3D asset.
- Editorial emphasis lives inside sentences: 40px narrow serif prose in #696969 with meaningful phrases in #171717, set across roughly 1088px with 100px vertical breathing room.
- The story ends in a human tableau rather than a link directory: a full-width, 900px-tall cool-grey photographic stage with a centered white 64px narrow-serif maker line. For products without a team portrait, use a commissioned user or maker tableau with the same scale and lighting.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Optical blue | `#004fce` | `--color-optical-blue` | background | Saturated inner halo of the opening light field, fading into mist. |
| Optical deep blue | `#00368c` | `--color-optical-deep` | background | Deep center of the opening radial light field. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric action blue | `#002fff` | `--color-blue` | action, accent, surface | Primary conversion fills and selected milestone tile; compact, concentrated areas. |
| Diffused blue | `#b6c4e0` | `--color-soft-blue` | background | Soft center of the process demonstration stage. |
| Glass blue grey | `#bdc6d9` | `--color-blue-grey` | background | Cool radial backing for large product explanations. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep black | `#000000` | `--color-black` | background, text | Darkest stop of the close-up stage and small feature labels. |
| Cinema black | `#070707` | `--color-cinema` | background, text | Dark immersive chapters and high-contrast functional copy. |
| Editorial ink | `#171717` | `--color-ink` | text, background | Primary headings and emphasized prose; newsletter band backing. |
| Smoke glass | `#313131` | `--color-field` | surface | Visible newsletter input fill: white at 11% over editorial ink. |
| Stage horizon | `#545454` | `--color-stage-grey` | background | Lower horizon of the dark product close-up gradient. |
| Editorial grey | `#696969` | `--color-muted` | text | Narrative prose, supporting lines and technical captions. |
| Portrait grey | `#c9cbd1` | `--color-portrait-grey` | background | Cool seamless background of the closing human tableau. |
| Stage mist | `#ededed` | `--color-mist` | surface, text, background | Light media backing, purchase gallery and inactive specification lines. |
| White canvas | `#ffffff` | `--color-canvas` | background, text, surface | Main reading canvas, reversed scene text and light form submit controls. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| progress and roadmap sections | Past milestone wash | `#f6f6f6` | `--color-faded-tile` | surface | Visible result of mist at 50% opacity over white; past milestone tiles. |

## Typography

- **Graphik** — Product names, chapter titles, functional headings, descriptions and controls. Compact neutral grotesk with a medium cut; aggressively tightened at display sizes. If unavailable, use **Inter**. Use 500; retain tight tracking and compare line breaks. Font stack: "Graphik", "Inter", Arial, sans-serif.
- **ITC Garamond Std Light Narrow** — Narrative prose, specification lists, photographic statements and captions. Very narrow, light editorial serif with tall proportions and delicate contrast. If unavailable, use **Bodoni Moda**. Use 400 and a condensed width treatment; match narrow line lengths before matching detail. Font stack: "ITC Garamond Std Light Narrow", "Bodoni Moda", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| chapter-display | Graphik | 500 | 150px | 1.2 | -0.0667em | Single-name immersive chapters and monumental section headings. |
| serif-display | ITC Garamond Std Light Narrow | 300 | 64px | 0.9 | -0.0234em | Photographic statements, specification list and maker sign-off. |
| heading | Graphik | 500 | 40px | 1 | -0.045em | Section invitations, purchase heading and paired benefit headings. |
| editorial | ITC Garamond Std Light Narrow | 300 | 40px | 0.9 | -0.0225em | Long narrative interludes and feature descriptions; emphasis changes color, not weight. |
| opening-title | Graphik | 500 | 34px | 1 | -0.053em | Modest product identifier centered above the opening object. |
| signup-heading | ITC Garamond Std Light Narrow | 300 | 30px | 0.9 | -0.0167em | Compact invitation within the newsletter band. |
| body | Graphik | 500 | 22px | 1.2 | -0.0455em | Supporting feature text and purchase metadata. |
| caption | ITC Garamond Std Light Narrow | 300 | 15px | 0.9 | normal | Small technical notes, media captions and payment reassurance. |
| label | Graphik | 500 | 14px | 1.2 | -0.021em | Feature eyebrows, milestone descriptions and primary action labels. |

**Notes:**

- The opening product title is smaller than later chapter titles; preserve that reversal of ordinary landing-page hierarchy.
- Grotesk headings are tightly packed and visually medium. Serif text is slender, never bold; its 0.9 line height makes prose read as an editorial block rather than ordinary body copy.
- Keep the two-line benefit heading at the same 40px size: first line ink, second line grey. Color is the subordinate hierarchy.
- Desktop sizes are the defaults. Scale long display words down only enough to keep them within the composition; do not widen the serif to fill space.

## Layout

**Density:** Airy scene-level pacing with compact text relationships: entire viewport stages alternate with closely led editorial blocks.

### Spacing

**Spacing system:**

- **step** 10px — Dominant spacing rhythm for gutters, stage insets, card gaps and section breathing room.

| Value | Use |
| --- | --- |
| 5px | Tight stacking of purchase actions. |
| 10px | Repeated card gaps and short heading-to-copy gaps. |
| 20px | Opening side inset, feature-copy gaps and milestone padding. |
| 30px | Large media panel inner inset. |
| 40px | Default desktop reading and media gutter. |
| 50px | Process-stage padding and narrative-to-card separation. |
| 100px | Vertical padding of editorial and proof sections. |
| 150px | Bottom breathing room of a large product benefit panel. |

### Containers and grids

- **reading-and-media**: side padding 40px. Fluid desktop composition, 1360px usable width at 1440px; not a fixed maximum-width site.
- **opening-stage**: side padding 20px. 1400px-wide opening light field at desktop; 60px reserved above and 20px below within a 900px first screen.
- **editorial-measure**: max width 1088px. Left-aligned narrative blocks stop before the right gutter, leaving an open margin.
- **paired-proof**: 2 columns · gap 20px. Two large media tiles, sometimes equal and sometimes a roughly two-thirds product detail beside a one-third lifestyle crop.
- **purchase-split**: 2 columns · gap 0px. Two 720px-wide halves at desktop: a tall product-angle gallery left and a centered sticky offer right.

## Corner radius

| Element | Radius |
| --- | --- |
| action-clip | 10px |
| action-fill-and-field | 15px |
| media-card | 20px |
| light-stage | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| input-edge | `rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset` | Subtle inner white edge of the smoke-glass email field. |
| photo-type | `rgba(0, 0, 0, 0.2) 0px 0px 14px, rgba(0, 0, 0, 0.35) 0px 1px 2px` | White closing serif line over the portrait, rather than a panel behind the words. |

### Surfaces

#### White canvas · level 0

**Use:** Editorial reading stretches and product purchase area.

**CSS:** `background: #ffffff; color: #171717`

#### Opening optical field · level 0

**Use:** Soft saturated light behind the main product.

**CSS:** `background: radial-gradient(50% 75%, #00368c 0%, #004fce 10.6771%, #ededed 100%); border-radius: 30px; overflow: hidden`

**Observed:** A broad blue center diffuses into pale edges; there are no hard light rings or visible noise.

**Transfer:** Keep the glow behind the object, not behind a mass of copy.

#### Dark close-up stage · level 0

**Use:** Large oblique product study.

**CSS:** `background: linear-gradient(#000000 0%, #070707 39.1769%, #545454 96.4193%); border-radius: 20px; overflow: hidden`

**Observed:** Near-black upper field with a lighter bottom horizon supports a dark product without a drop-shadow card.

#### Glass-blue stage · level 0

**Use:** Product rendering with centered benefit copy beneath.

**CSS:** `background: radial-gradient(106% 100% at 30.2% 8.7%, #bdc6d9 42.4567%, #ededed 100%); border-radius: 20px; overflow: hidden`

#### Process light field · level 0

**Use:** Side-by-side mechanism explanation and cropped product.

**CSS:** `background: radial-gradient(50% 50%, #b6c4e0 38%, #ededed 100%); border-radius: 30px; padding: 50px; overflow: hidden`

#### Cinema canvas · level 0

**Use:** Immersive technical and photographic chapters.

**CSS:** `background: #070707; color: #ffffff; overflow: hidden`

#### Purchase gallery · level 0

**Use:** Tall stack of isolated product angles.

**CSS:** `background: #ededed; border-radius: 30px; overflow: hidden`

## Components

### Minimal masthead

**Use:** Brand orientation before the product stage.

**CSS:** `height: 55px; position: absolute; width: 100%; z-index: 1`

**Observed:** Centered black wordmark on white; small language chooser at the far right with globe and chevron. There is no sprawling navigation menu.

**Transfer:** Use the new brand's own wordmark; keep secondary utilities visually tiny.

### Primary button

**Use:** Main purchase or conversion action.

**CSS:** `background: #002fff; color: #ffffff; width: 296px; height: 50px; border-radius: 10px; overflow: hidden`

**Text style:** `label` — Graphik 500 · 14px/1.2 · tracking -0.021em

**Observed:** Centered text, no arrow. A 15px rounded fill sits inside a 10px clipped link wrapper. In the offer stack it precedes a pale secondary action.

### Email field

**Use:** Collect updates inside a compact inline form.

**CSS:** `background: rgba(255, 255, 255, 0.11); width: 395px; height: 47px; padding: 15px 115px 15px 15px; border-radius: 15px; box-shadow: rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset; box-sizing: border-box`

**Observed:** Right padding reserves room for an inset submit control; the field is smoke glass against the dark band, not a separate white box.

### Inset submit

**Use:** Small newsletter submission control.

**CSS:** `background: #ffffff; width: 100px; height: 37px; border-radius: 10px`

**Observed:** Anchored inside the field at the right with a small inset on every side. A blue-filled version belongs on a light-backed opt-in form.

### Newsletter band

**Use:** A compact interruption between editorial and immersive content.

**CSS:** `background: #171717; height: 100px; display: flex; justify-content: center; align-items: center; gap: 20px; padding: 0px 10px 0px 40px`

**Text style:** `signup-heading` — ITC Garamond Std Light Narrow 300 · 30px/0.9 · tracking -0.0167em

**Observed:** Invitation sits left of the Email field, both centered as a single horizontal composition.

### Product benefit panel

**Use:** Large visual demonstration followed by a concise explanation.

**CSS:** `border-radius: 20px; padding: 30px 30px 150px; display: flex; flex-direction: column; gap: 29px; overflow: hidden`

**Text style:** `heading` — Graphik 500 · 40px/1 · tracking -0.045em

**Observed:** Uses Glass-blue stage. The isolated object fills the upper region; a centered two-line heading pair and narrow body paragraph sit below it, not on the product.

### Milestone tile

**Only for:** progress and roadmap sections

**Use:** Show the status of a staged release or process.

**CSS:** `background: rgba(237, 237, 237, 0.5); border-radius: 20px; height: 255px; width: 180px; padding: 20px; box-sizing: border-box`

**Text style:** `label` — Graphik 500 · 14px/1.2 · tracking -0.021em

**Observed:** Horizontal track with 10px gaps; dates in editorial serif sit above 100px vertical stems. Some tiles are 250px wide for longer content. Past steps fade; one current step becomes electric blue with white type.

**Transfer:** Use actual milestones; the blue selection remains singular.

## Imagery and graphics

### Studio object sculpture

**Use:** Opening hero, close-up stage, mechanism chapters and purchase gallery.

**Observed:** Glossy black hardware with controlled silver edge highlights and pale blue glass reflections. Front-on opening view is centered and fully legible; later views become monumental oblique crops or separated optical parts, on black horizons or cool seamless fields. Objects occupy far more area than their labels.

**Transfer:** Render or photograph a real product with soft studio reflections and a clean cutout. For software or services, make a single carefully lit dimensional artifact or a high-quality interface plane rather than scattering small floating windows. A sharp isolated still with two alternate angles is the minimum.

### Optical light fields

**Use:** Signature luminous backings for isolated objects and mechanisms.

**Observed:** A concentrated deep blue behind the opening product fades to almost white at every edge; secondary panels use much softer desaturated blue-grey.

**Transfer:** Keep both a saturated opening halo and a cooler explanatory field in the visual language; do not turn every card into a bright gradient.

**Build:** Use the Opening optical field and Process light field CSS as full-panel radial gradients. Clip at 30px radius. Center the product in front with transparent edges; avoid an extra box or opaque floor. Light is a continuous radial interpolation, not multiple concentric circles.

### Intimate lifestyle proof

**Use:** Emotional setup and evidence of the product's result.

**Observed:** Full-bleed youthful portraits, close-ups of skin and candid movement, warm flash, teal dusk and deep red light. Some photographs are grainy and tactile, others sharply flashed. Large crops run beneath crisp typography; paired proof tiles round their corners. Color comes from the photography rather than decorative UI.

**Transfer:** Choose human moments or tangible outcomes relevant to the new product. Preserve candid framing, rich shadows and skin/material texture rather than generic corporate stock imagery.

### Editorial strip

**Use:** A signature narrow image sequence through a dark emotional scene.

**Observed:** A vertical strip of photographic frames and dark edge markings runs through the center; short white copy occupies the right third or overlays the full image.

**Transfer:** Keep a vertical contact-sheet device even without photographic film: stack outcome frames, process photographs or interface states in a narrow central ribbon.

**Build:** Create an SVG or HTML ribbon roughly one sixth of the desktop width, with vertically stacked rectangular image masks, narrow black margins and tiny muted edge labels. For a physical-media product add repeated rounded rectangular perforations along both edges; for other products use simple contact-sheet dividers. Darken the overall scene so white side copy remains distinct.

### Cinematic focus reveal

**Use:** Chapter changes into new capabilities.

**Observed:** Blurred full-screen photographs or objects carry a crisp white grotesk chapter name; later states show detailed imagery and smaller serif explanations.

**Transfer:** Prepare a blurred and a sharp version of one scene. Use a static sharp proof section if a moving sequence is not feasible, but retain the blurred title-stage contrast.

**Build:** Place the image as an oversized cover layer inside an overflow-hidden stage and apply CSS blur to the image only. Put the 150px chapter title in a separate crisp layer above it. Match the broad loss of detail without softening the letters.

### Human closing tableau

**Use:** Final maker signature after practical details.

**Observed:** A wide studio group portrait on cool grey, full bodies at mixed standing and sitting heights, cropped people continuing beyond the side edges. Clothes add natural blue and pink accents; directional light gives clear floor shadows. White narrow serif copy is centered over the group.

**Transfer:** Commission an equivalent user, maker or customer tableau. If a group is unavailable, photograph one maker and meaningful tools with the same wide seamless grey staging, not an avatar grid.

### Icons

**Observed:** Icons are sparse: an 18px filled globe and a 9px chevron with 1.5px rounded stroke accompany the language utility. Media captions often begin with a small electric-blue dot.

**Transfer:** Keep icons functional and subordinate; use the blue dot for technical notes rather than inventing a full decorative icon set.

## Section recipes

How recurring sections are built.

### First screen: Optical object opening

**Observed:** The first 900px contains the Minimal masthead on white and a 1400px × 820px Opening optical field inset 20px horizontally, beginning below a 60px top reservation. A centered white 34px product name and tiny one-line benefit occupy the upper region. The 736px × 409px front-facing product sits in the lower half, with broad air between title and object; its actual dark silhouette is about half the screen width. Layers are white canvas, rounded blue radial light, isolated object and crisp text, then a small translucent scroll prompt near the bottom. This is an invitation to explore rather than a purchase form; the press strip and narrative imagery begin below the fold.

**Transfer:** Use one confidently staged product silhouette with a short name and one-line promise. Without a render, commission a cutout photograph or one dimensional representation of the result. A secondary informational page can use a concise heading above a similarly lit relevant artifact rather than repeating a long spectacle.

**Avoid:** Do not enlarge the opening title to 150px, add a left-copy/right-dashboard SaaS layout, or crowd the first screen with feature bullets and multiple conversion buttons.

**Text style:** `opening-title` — Graphik 500 · 34px/1 · tracking -0.053em

### Immersive chapter reveal

**Observed:** A viewport-filling Cinematic focus reveal supports a 150px white chapter name. As the scene develops, the object or lifestyle image becomes proof, with short 64px serif statements or a 40px heading. A compact bottom-center dock pairs a subdued current-chapter control with a blue purchase control across the journey.

**Transfer:** Use the device for a small number of meaningful capabilities; keep the title layer crisp and the bottom action distinct from story text.

**Text style:** `chapter-display` — Graphik 500 · 150px/1.2 · tracking -0.0667em

### Editorial interlude

**Observed:** White canvas with 100px vertical padding, 40px side gutters and a roughly 1088px-wide block of 40px narrow-serif prose. Grey sentences contain ink-colored phrases without changing size or weight.

**Transfer:** Explain material choices, benefits or product philosophy in continuous prose. Highlight only phrases that carry the argument.

**Text style:** `editorial` — ITC Garamond Std Light Narrow 300 · 40px/0.9 · tracking -0.0225em

### Product study and proof pair

**Observed:** Product benefit panel on Glass-blue stage centers an isolated object above a 40px heading pair and a 559px-wide 22px supporting paragraph. Below, 20px-separated rounded proof cards combine extreme human detail with hardware close-up. Another variant uses a roughly two-thirds product card and one-third lifestyle crop, with text tucked into the upper corner.

**Transfer:** Connect an engineered detail to a visible human result. Use the same functional proof in both images rather than unrelated decoration.

**Text style:** `heading` — Graphik 500 · 40px/1 · tracking -0.045em

### Mechanism explanation

**Observed:** Process light field fills a 1360px-wide inset stage. A small label and two short editorial paragraphs occupy the left third; the right half contains a large cropped mechanism and accessory, allowed to extend out of frame.

**Transfer:** Separate a new product into a clear process or moving part. Keep explanatory text away from the detailed artwork.

**Text style:** `editorial` — ITC Garamond Std Light Narrow 300 · 40px/0.9 · tracking -0.0225em

### Purchase pause

**Observed:** Purchase-split layout places a tall light-grey gallery of multiple product angles on the left. The right offer remains centered in a viewport-height region: 40px title, delivery line, price, Primary button, pale secondary action and tiny serif payment reassurance. The offer is not boxed into a generic pricing card.

**Transfer:** Use real availability, price and purchase terms. For a service, substitute a single focused conversion offer and a relevant deliverable gallery.

**Text style:** `heading` — Graphik 500 · 40px/1 · tracking -0.045em

### Oversized technical index

**Observed:** A 150px ink heading introduces a long specification list. A small sticky left label occupies roughly one third of the width; 64px narrow-serif lines run in the remaining area. Most lines are mist-colored and the current reading region is ink.

**Transfer:** Use for a dense, genuinely useful technical index. Preserve selected-line emphasis while ensuring all essential information is available in a readable static view.

**Text style:** `serif-display` — ITC Garamond Std Light Narrow 300 · 64px/0.9 · tracking -0.0234em

### Horizontal progress proof

**Observed:** A monumental 150px title sits high on white with a wide gap before the Milestone tile track. Serif dates stand above thin vertical markers. The track extends beyond the viewport and the active card alone is blue.

**Transfer:** Use only when progress or chronology adds confidence; substitute real delivery stages or process steps, not invented dates.

**Text style:** `chapter-display` — Graphik 500 · 150px/1.2 · tracking -0.0667em

### Human maker sign-off

**Observed:** A full-width 900px Human closing tableau ends the page with no conventional footer columns. A centered white 64px serif maker line overlays the people with a subtle text shadow.

**Transfer:** Close with a human statement of authorship or purpose and a portrait appropriate to the new product; keep the image uninterrupted by link grids.

**Text style:** `serif-display` — ITC Garamond Std Light Narrow 300 · 64px/0.9 · tracking -0.0234em

## Page flow

**Storyline:** object introduction → emotional motivation → capability spectacle → editorial explanation → visible proof → focused offer → technical reassurance → human signature

### A flagship product launch that makes a manufactured object feel both desirable and understandable

1. **Product introduction** — A modest product title floats above a monumental isolated object in blue light.
2. **Emotional motivation** — Press marks give way to photographic storytelling, a vertical contact sheet and short reflective copy.
3. **Capability overview** — Overlapping visual highlight cards preview the product's strongest reasons to care.
4. **Capability chapters** — Blurred chapter reveals alternate with close-ups, mechanism artwork, large serif statements and editorial interludes.
5. **Conversion** — A product-angle gallery faces a compact sticky offer stack.
6. **Technical reassurance** — Oversized specification typography and a horizontally moving milestone track answer practical questions.
7. **Human signature** — A studio group portrait and centered maker line end the experience.

**Transfer:** Borrow the alternation of spectacle and explanation rather than the full length or section count. A shorter launch can combine capabilities into one rich chapter while retaining the object opening, editorial serif, cinematic reveal and human sign-off.

## Writing

Reflective, tactile and aspirational, with occasional direct technical confidence. The language connects machinery to ordinary moments rather than presenting engineering as an end in itself.

**Do not copy:** Do not reuse Analogue, aF-1, Renaisson, product claims, third-party endorsements, specifications, release dates, prices or the site's photography, logo and proprietary product artwork. Source examples describe cadence only. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for practical benefits; we or our for design decisions. Product names appear in descriptive passages, while chapter titles are simple feature nouns.
- **Rhythm:** Short feature headings alternate with flowing editorial paragraphs. Benefits often precede the technical reason; the voice uses full sentences, contractions and occasional em dashes, not an all-caps slogan system.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A compact plain-language instruction that makes the object feel easy. | 3–5 words | “Just Point and Shoot” |
| Emotional statement | Invite a slower, more attentive experience rather than claiming market dominance. | 5–14 words | “Discover the joy of capturing life, one frame at a time.” |
| Feature benefit | A direct action or outcome, with tactile language. | 3–6 words | “Brighten every moment”<br>“Take a closer look” |
| Supporting explanation | Explain an automatic mechanism as a relief from effort. | One or two flowing sentences | “Once the roll is full, it winds back seamlessly—ready for your next adventure.” |
| Primary action | Use a literal verb and clear commitment. | 2–3 words | “Pre-order now”<br>“Stay tuned” |

**Words and phrasing to use:** crafted; draws in light; moments; effortlessly; clear; from start to finish; detail; ease of use

**Avoid:** disruptive; 10x; growth hack; enterprise-grade everything; revolutionize your workflow; shouted urgency

**Rules:**

- Pair an emotional outcome with one concrete mechanism or supported measurement.
- Keep chapter labels literal; reserve lyrical language for serif statements and narrative prose.
- Use sentence case and conventional capitalization rather than tracked uppercase eyebrows.
- Keep payment, timing and availability language factual and compact.

## Do's and Don'ts

### Do

- Keep 40px desktop side gutters around editorial and proof sections.
- Use the 34px opening title to let the object, not text, dominate the first impression.
- Set major chapter nouns at 150px with -10px tracking.
- Use 40px/0.9 serif prose with selected ink phrases within grey sentences.
- Keep the conversion action at 296px × 50px in the focused offer.
- Let large renders crop beyond later scene edges while preserving a complete opening silhouette.
- Use 100px breathing room around substantial editorial interludes.
- Retain one full-width photographic human sign-off with a 64px serif line.

### Don't

- Do not replace the narrow light serif with a broad bold luxury serif; its density and delicacy are central.
- Do not make every heading 150px: the working heading scale is 40px and the opening identifier is 34px.
- Do not turn rounded rectangular actions into 9999px pills.
- Do not apply heavy floating drop shadows to product panels; their depth comes from light and the object itself.
- Do not use blue for long paragraphs or whole ordinary reading sections; reserve electric blue for compact signals.
- Do not turn proof into a uniform three-column icon-card grid; the visual evidence is large and asymmetrically cropped.
- Do not use a multi-column link directory as the dominant last impression.
- Do not repeat the same pale blue panel behind all media; alternate white, near-black and cool optical fields.

## Motion and responsive

### Motion

**Observed:**

- The journey uses scroll-linked visual reveals, changing object views, blurred-to-sharp chapters, a horizontal milestone track and a persistent bottom-center chapter/purchase dock.
- A purchase offer and technical index label use sticky positioning. No action transitions or durations were declared for the reviewed controls.

**Transfer:**

- Tie scene changes to progress through the chapter, keeping each resting composition complete and legible.
- Use still-image pairs as the fallback for cinematic focus reveals; retain the object scale and alternating light/dark scenes.

**Unknown:**

- Exact scene timing, blur progression, easing assignments and hover/focus treatments are unknown.

### Responsive

**Observed:**

- Stylesheet width boundaries include 810px, 1100px, 1500px and 1919px; only the 1440px desktop composition is established.

**Transfer:**

- On narrow screens, retain the centered object-first hero and its cool light field; reduce display size to preserve whole words.
- Stack paired proof and purchase halves, placing the product image before its explanation or offer. Keep the milestone track horizontally scrollable rather than shrinking its dates and tiles.
- Keep the closing portrait full bleed and choose a purposeful crop; do not reduce it to a tiny thumbnail.

**Unknown:**

- Exact mobile type sizes, spacing, navigation behavior and scene substitutions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
