# Deta — skyborne software garden

## Overview

An airy, light software style that makes digital tools feel personal, tactile and a little enchanted. Sky blue and white frame elegant serif headlines, restrained grotesk explanations and colorful product scenes. Floating paper objects, soft clouds and painterly planting soften otherwise practical interface demonstrations; density rises only in the proof and small-feature collections.

### Essentials

- Literary promises float above functional software: Gambarino 60px/1 at weight 500 for the opening, then 36px/40px at weight 400 for chapter headings; Switzer carries the explanations.
- The opening feels airborne rather than boxed: a full-width blue-to-white sky, centered 672px-wide interactive product object, four tilted peripheral artifacts and a narrow 768px navigation. Keep the headline, support, object and primary action visible within 900px.
- Actions feel like pressable blue objects: 56px height, 16px corners, 12px 48px 16px padding and a 4.4px inset lower edge; compact inset-card actions use 36px height and 10px corners.
- Color arrives as scenery, not as a dark theme: retain white for the majority of the long page, reserve saturated blue for the opening, large demonstration stages and actions, and pale blue, mint and pink for proof cards.
- Product proof is staged at landscape scale: 1088px-wide rounded blue panels, layered white application windows and an overlapping row of tactile feature selectors with condensed 19.4px labels.
- A cultivated natural world bookends the technology: clouds and floating artifacts above, a full-width painted foliage fringe below a sparse closing call. Recreate both the airborne collage and organic closing fringe even when the product has no equivalent artwork, using simple original paper cards and layered SVG planting.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Upper sky | `#4a9eff` | `--color-sky-top` | background | Top stop of the opening sky gradient. |
| Stage blue | `#43a3e2` | `--color-stage-blue` | background, surface | Central blue of rounded radial demonstration stages. |
| Middle sky | `#7bb8ff` | `--color-sky-mid` | background | Middle stop of the opening sky gradient. |
| Lower sky | `#a8d5ff` | `--color-sky-light` | background | Lower stop of the opening sky before its white fade. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Selected blue top | `#0396df` | `--color-selected-top` | action, surface | Top of selected feature-selector gradient. |
| Selected blue bottom | `#0282e8` | `--color-selected-bottom` | action, surface | Bottom of selected feature-selector gradient. |
| Icy blue edge | `#cfe9fd` | `--color-cta-edge` | border | Conversion-art panel outline; rgba(17,144,246,0.2) over white. |
| Dotted blue edge | `#d8e6fd` | `--color-note-edge` | border | Personal-note link border; rgba(59,130,246,0.2) over white. |
| Blue proof edge | `#dbeafe` | `--color-blue-edge` | border | Two-pixel edge of blue proof cards. |
| Mint proof edge | `#dcfce7` | `--color-mint-edge` | border | Edge paired with mint proof wash. |
| Pink proof edge | `#fce7f3` | `--color-pink-edge` | border | Edge paired with pink proof wash. |
| Pink proof wash | `#fdf2f8` | `--color-pink-wash` | surface | Occasional highlighted press quotation. |
| Blue proof wash | `#eff6ff` | `--color-blue-wash` | surface | Default testimonial card background. |
| Mint proof wash | `#f0fdf4` | `--color-mint-wash` | surface | Occasional highlighted press quotation. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text | Serif headings and primary dark text. |
| Zinc ink | `#27272a` | `--color-card-ink` | text | Testimonial prose and compact feature titles. |
| Zinc caption | `#52525b` | `--color-caption` | text | Small feature descriptions. |
| Slate body | `#4b5563` | `--color-body` | text | Supporting paragraphs and media captions. |
| Soft black | `#808080` | `--color-muted` | text | Secondary quotations and personal notes; black at 50% over white. |
| Cool hairline | `#e5e7eb` | `--color-rule` | border | Collection dividers, media edges and circular controls. |
| Warm paper edge | `#f3f2f2` | `--color-paper-edge` | border | Visible white-card border made with rgba(231,229,228,0.5). |
| Media gray | `#f3f4f6` | `--color-media-gray` | surface | Neutral surround for demonstration slides. |
| Lavender frost | `#fbfbff` | `--color-frost` | surface | Outer shell of the opening product demonstration. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main page, paper cards and reversed text on blue. |

## Typography

- **Gambarino** — Promises, chapter headings and personal editorial accents. High-contrast, graceful serif with narrow proportions and sharply modeled terminals. If unavailable, use **Instrument Serif**. Use regular weight; check headline width before adjusting size. Font stack: "Gambarino", "Instrument Serif", Georgia, serif.
- **Switzer** — Navigation, explanations, captions, testimonials and actions. Clean contemporary grotesk, regular for explanation and medium for action or proof. If unavailable, use **Inter**. Use weights 400–500 with normal tracking. Font stack: "Switzer", "Inter", Arial, sans-serif.
- **Tanker** — Physical feature-selector titles. Narrow emphatic display capitals that resemble equipment labels. If unavailable, use **Barlow Condensed**. Use weight 700 to match the dense display construction. Font stack: "Tanker", "Barlow Condensed", Impact, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Gambarino | 500 | 60px | 1 | normal | Single-line opening promise in white. |
| art-call | Gambarino | 400 | 48px | 1.2 | -0.0101em | Headline within conversion artwork. |
| panel-heading | Gambarino | 400 | 40px | 1.2 | normal | Left-aligned title within a blue demonstration stage. |
| heading | Gambarino | 400 | 36px | 40px | normal | Default centered section headline and final call. |
| faq-title | Gambarino | 400 | 36px | 1.5 | normal | Centered title in the FAQ destination panel. |
| lead | Switzer | 400 | 20px | 28px | normal | Centered opening explanation and editorial proof quotation. |
| action | Switzer | 500 | 20px | 28px | normal | Main blue action labels. |
| personal-title | Gambarino | 400 | 20px | 28px | normal | Editorial note link title. |
| selector-title | Tanker | 400 | 19.4px | 1.3 | 0.05em | Condensed uppercase-looking labels on feature selectors. |
| body-lg | Switzer | 400 | 18px | 28px | normal | Chapter support lines. |
| panel-body | Switzer | 400 | 18px | 1.6 | normal | Longer white explanation inside the blue stage. |
| selector-body | Switzer | 500 | 16.2px | 1.4 | normal | Two-line explanation on feature selectors. |
| body | Switzer | 400 | 16px | 1.5 | normal | Navigation, media captions and personal-note body. |
| proof | Switzer | 500 | 16px | 1.5 | normal | Testimonial prose. |
| small-title | Switzer | 500 | 14px | 20px | normal | Small feature titles and compact blue action. |
| caption | Switzer | 400 | 14px | 20px | normal | Small feature descriptions. |

**Notes:**

- Serif headings are sentence case with punctuation, not heavy sans display type. Most tracking remains normal; selector labels alone use 0.05em.
- Use the 36px heading as the ordinary chapter default. The 40px and 48px recipes belong inside colored media and conversion panels, not every chapter.

## Layout

**Density:** Airy chapters with compact, readable islands of proof and feature detail.

### Spacing

**Spacing system:**

- **horizontal step** 8px, horizontal — Underlying horizontal spacing rhythm; 12px is a local compact exception.

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 4px | Small title-to-description gap. | fixed |
| 12px | Small card media-to-text gap and carousel control gap. | fixed |
| 16px | Small card padding and stacked proof-card spacing. | fixed |
| 24px | Heading-to-support spacing, proof padding and feature-grid gutters. | fixed |
| 32px | Desktop side padding and closing headline-to-action spacing. | fixed |
| 48px | Space above and below the opening object; grid block padding. | fixed |
| 64px | Proof introduction and conversion block outer padding. | fixed |
| 96px | Generous conversion-panel padding and footer block rhythm. | fixed |
| 128px | White-space introduction to major capability chapters. | fixed |
| 25.2px | Feature-selector grid gap. | clamp(14.4px, 1.8vw, 25.2px) |

### Containers and grids

- **wide demonstration**: max width 1152px · side padding 32px. Centered outer wrapper yielding 1088px-wide visual stages.
- **editorial heading**: max width 768px · side padding 32px. Narrow centered chapter text and opening navigation.
- **opening object**: max width 672px. Centered interactive demonstration under the promise.
- **proof collection**: max width 896px · side padding 32px. Narrower collection below large media.
- **small feature grid**: 3 columns · gap 24px. Three equal columns, two rows in the feature collection.
- **conversion art**: max width 1024px · side padding 32px. 960px-wide inset art panel with left text and right tactile object collage.
- **feature selectors**: 3 columns · gap 25.2px. Overlapping row extends beyond the landscape demonstration's edges.

## Corner radius

| Element | Radius |
| --- | --- |
| primary action | 16px |
| compact action | 10px |
| small cards | 12px |
| blue stages | 24px |
| conversion art | 32px |
| FAQ panel | 44px |
| personal note | 8px |
| circular controls | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small paper lift | `0px 1px 2px 0px rgba(0,0,0,0.05)` | Proof and feature cards. |
| personal note lift | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | Dotted personal note. |

### Surfaces

#### White canvas · level 0

**Use:** Long-page base.

**CSS:** `background: #ffffff`

#### Opening sky · level 0

**Use:** Full-width opening atmosphere.

**CSS:** `background: linear-gradient(#4a9eff 0%, #7bb8ff 50%, #a8d5ff 100%)`

**Observed:** Cloud texture overlays the gradient; a white fade rises from the lower edge to dissolve into the page.

**Transfer:** Keep the top saturated and clear behind white type, fading into white before the first ordinary chapter.

#### Blue demonstration stage · level 1

**Use:** Large product demonstrations, either centered media or a text/media split.

**CSS:** `background: radial-gradient(116.05% 111.85% at 44.33% 115.39%, color(display-p3 0.2048 0.5316 0.8202), #43a3e2 57.27%, color(display-p3 0.2 0.6039 0.9608)); border-radius: 24px; padding: 20px 0px; overflow: hidden`

**Observed:** Subtle white radial sheen overlays the blue. White windows remain crisp and occupy most of the panel.

**Transfer:** Use the same stage to make new interface demonstrations feel luminous rather than technical.

#### Paper card · level 1

**Use:** Small feature collections.

**CSS:** `background: #ffffff; border: 1px solid rgba(231,229,228,0.5); border-radius: 12px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

#### Collection title strip · level 2

**Use:** Centered title above dense collections.

**CSS:** `background: rgba(255,255,255,0.8); backdrop-filter: blur(4px); padding: 16px 32px`

**Observed:** A hairline divider beneath the title introduces the grid without a large tinted section background.

#### Conversion artwork panel · level 1

**Use:** Inset invitation with object collage.

**CSS:** `background: #ffffff; border: 1.5px solid rgba(17,144,246,0.2); border-radius: 32px; overflow: hidden`

**Observed:** Landscape proportions, 960px by 480px, with a blue atmospheric artwork backing and white headline treatment.

**Transfer:** Keep text readable over a restrained atmospheric left region; concentrate dimensional objects on the right.

## Components

### Narrow navigation

**Use:** Unobtrusive opening wayfinding.

**CSS:** `display: flex; justify-content: space-between; align-items: center; max-width: 768px; padding: 32px; color: #ffffff`

**Text style:** `body` — Switzer 400 · 16px/1.5

**Observed:** Small emblem and serif brand label at left; two short links at right, one with a translucent rounded count badge and external arrow. No separate navigation background.

### Primary button

**Use:** Main conversion at opening and close.

**CSS:** `display: flex; align-items: center; background: linear-gradient(color(display-p3 0.1285 0.5802 0.9715), color(display-p3 0.0285 0.4802 0.8715)); color: #ffffff; height: 56px; padding: 12px 48px 16px; border-radius: 16px; box-shadow: color(display-p3 0.0265 0.4186 0.7582) 0px -4.3px 0px 0px inset`

**Text style:** `action` — Switzer 500 · 20px/28px

**Observed:** Centered standalone action with a visible darker lower lip, not a pill.

**States:** Declared: hover translateY(-1px) with a brighter blue gradient, 6px inset lower edge and 0px 4px 8px rgba(0,0,0,0.1) shadow; focus-visible unknown; active translateY(2px) with a darker gradient and 2px inset edge.

### Compact button

**Use:** Action inside the conversion-art panel.

**CSS:** `display: flex; align-items: center; justify-content: center; min-width: 160px; height: 36px; padding: 6px 16px; border-radius: 10px; color: #ffffff; background: linear-gradient(color(display-p3 0.1285 0.5802 0.9715) 0%, color(display-p3 0.0285 0.4802 0.8715) 100%); box-shadow: rgb(0, 109, 200) 0px -4px 0px 0px inset, rgba(0,0,0,0.1) 0px 2px 4px 0px`

**Text style:** `small-title` — Switzer 500 · 14px/20px

**Observed:** Same physical blue construction as Primary button but visually subordinate to the artwork title.

### Feature selector

**Use:** Switchable capability explanation attached to a large demonstration.

**CSS:** `display: flex; position: relative; background: #ffffff; border-radius: 16.2px; padding: 4px 0px 12px; text-align: left`

**Text style:** `selector-title` — Tanker 400 · 19.4px/1.3 · tracking 0.05em

**Observed:** Condensed title over a selector-body explanation; inner content has 21.6px vertical and 27px horizontal padding with a 9px gap. An outer overlay creates a lower inset lip and faint outline. Selected variant is blue with white text; siblings are white with blue-gray text gradients.

**States:** Declared: hover translateY(-1px); focus-visible unknown; active translateY(2px).

**Transfer:** Use two or three concise capability switches, not a grid of marketing icons.

### Testimonial card

**Use:** Dense social proof collection.

**CSS:** `background: #eff6ff; border: 2px solid #dbeafe; border-radius: 12px; padding: 24px; color: #27272a; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05); margin-bottom: 16px`

**Text style:** `proof` — Switzer 500 · 16px/1.5

**Observed:** Text-first variable-height cards in three masonry-like columns. A small minority of press quotes use mint or pink with matching borders; no oversized quotation marks.

### Small feature card

**Use:** Secondary capabilities after larger demonstrations.

**CSS:** `display: flex; flex-direction: column; gap: 12px; background: #ffffff; border: 1px solid rgba(231,229,228,0.5); border-radius: 12px; padding: 16px; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.05)`

**Text style:** `small-title` — Switzer 500 · 14px/20px

**Observed:** Landscape product detail image above a short title and caption. Title and caption use a tighter 4px gap; cards are about 261px wide.

### Carousel arrow

**Use:** Browse landscape demonstrations.

**CSS:** `display: flex; justify-content: center; align-items: center; width: 48px; height: 48px; background: rgba(255,255,255,0.9); border: 1px solid #e5e7eb; border-radius: 9999px; backdrop-filter: blur(4px); box-shadow: 0px 10px 15px -3px rgba(0,0,0,0.1), 0px 4px 6px -4px rgba(0,0,0,0.1)`

**Observed:** Paired circular chevrons aligned to the right below the media, separated by 12px.

**States:** Declared: hover background-color white; focus-visible unknown.

### Personal note link

**Use:** Human editorial aside near help and conversion.

**CSS:** `display: block; background: #ffffff; border: 2px dotted rgba(59,130,246,0.2); border-radius: 8px; padding: 16px; box-shadow: 0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)`

**Text style:** `personal-title` — Gambarino 400 · 20px/28px

**Observed:** Wide linked paper note with serif title and muted sans explanation, left aligned rather than centered.

### FAQ destination panel

**Use:** Prominent link to help rather than an inline accordion.

**CSS:** `display: flex; align-items: center; background: radial-gradient(153.97% 153.55% at 44.33% 115.39%, color(display-p3 0.2048 0.5316 0.8202), #43a3e2 57.27%, color(display-p3 0.2 0.6039 0.9608)); border-radius: 44px; padding: 40px 48px; backdrop-filter: blur(2px); overflow: hidden`

**Text style:** `faq-title` — Gambarino 400 · 36px/1.5

**Observed:** Large 896px-wide landscape destination with a centered white serif title over illustration.

## Imagery and graphics

### Airborne paper collage

**Use:** Signature opening composition.

**Observed:** Four tilted artifacts orbit the central interface without obscuring it: a turquoise bound notebook, a tall paper note, a compact illustrated web card and a landscape photo of hands over water. Soft contact shadows give each a tangible edge. Objects are roughly 160–259px wide against a bright sky and clouds.

**Transfer:** Use original artifacts related to the new product: a sample result, a physical metaphor, an image card and a document. Minimum version is four clean paper cards with distinct aspect ratios, gentle rotation and soft shadows around a genuine interface.

**Build:** Place four absolutely positioned card wrappers around the outside of a centered 672px stage, two on either side. Alternate roughly -8deg and 7deg rotations; use white paper, 4px corners and 0px 8px 16px rgba(0,0,0,0.12) shadows. Keep the central text column clear; use a blue book-like block with a narrow darker spine for the dimensional object.

### Cloud atmosphere

**Use:** Opening and large demonstration scenery.

**Observed:** Soft painted cumulus clouds drift into the lower opening and upper corners of the blue capability stage. The sky lightens toward the white page; texture is gentle rather than noisy.

**Transfer:** Preserve a bright open-air mood even for abstract products.

**Build:** Back with Opening sky. Add original SVG cloud silhouettes made of overlapping irregular lobes, white at 0.75–0.95 opacity, with a faint blue-gray lower edge. Place large clouds off the lower right and lower left; overlay linear-gradient(to top, white 20%, rgba(255,255,255,0)) across the stage to blend into the page.

### Interface landscapes

**Use:** Primary capability demonstrations.

**Observed:** Large white application windows float against blue or appear as neutral carousel slides. A desktop file window overlaps a larger notebook window; media is substantially larger than surrounding text. A later split panel gives about two thirds of its width to a live demonstration and one quarter to white serif copy.

**Transfer:** Show actual workflows with readable content and a limited number of windows. Keep browser chrome and artifact detail inside media rather than turning their type and colors into marketing tokens.

### Garden world

**Use:** Signature illustrated product film and closing fringe.

**Observed:** Painterly grasses, leafy plants and flowers frame a floating notebook in the film; the ending uses dark green layered grasses and yellow sunflowers along the entire lower edge. The center remains white and clear behind the final promise, button and small personal signoff.

**Transfer:** Retain a lush, handmade natural border with original vegetation. Minimum version is an SVG fringe with varied leaf shapes, long grass blades and sparse yellow flower heads, not a photographic stock banner.

**Build:** Construct an SVG across the full width, pinned to the bottom of the closing section. Layer a dark green low base, medium-green broad leaf clusters and thinner lighter blades, with irregular peaks about 200–280px above the bottom on desktop. Add sparse sunflower-like radial petals around muted dark centers. Use three overlapping depth bands and subtle texture or dither; keep all planting below the signoff.

### Tactile conversion objects

**Use:** Inset invitation artwork.

**Observed:** A dimensional blue notebook and scattered small paper/photo artifacts share a rounded landscape panel with a white serif invitation. The objects sit to the right of the copy rather than replacing it.

**Transfer:** Use an original physical metaphor for the product, with paper and a blue cover or enclosure; maintain the left reading area.

**Build:** Create a slightly rotated book-like rectangle with asymmetric spine corners, a narrow darker spine, a thin top highlight and layered soft blue shadows. Surround it with two small white image cards at opposing rotations. Back the scene with a restrained blue atmosphere that supports white text.

### Icons

**Observed:** Small navigation arrows are white 16px outline SVGs with 2px rounded strokes. Carousel chevrons are 24px with 2px rounded strokes in dark slate. The colorful emblem is separate from the utility icon vocabulary.

**Transfer:** Use simple outline chevrons and external arrows, keeping decorative illustration out of utility controls.

## Section recipes

How recurring sections are built.

### First screen: Airborne product opening

**Observed:** A full-width Opening sky sits behind Narrow navigation, a small status sentence with an outlined pill, a centered one-line display headline and a two-line lead. The headline is 60px and spans roughly two fifths of the desktop width. A 672px by 206px pale product input sits below with a luminous white inner face; four Airborne paper collage objects frame it at the outer edges. The Primary button is centered 48px below the object. Within the first 900px all these layers are visible, with lower objects nearing the edge and the cloud fade blending to white; the press quotation begins below the fold.

**Transfer:** For a new product, put one usable or convincing central interaction under a short promise and orbit original outputs or artifacts around it. Preserve sky, collage, serif promise and tactile action. A secondary page can open with a smaller heading and focused artifact while retaining the same material vocabulary.

**Avoid:** Do not turn the opening into a conventional left-copy/right-dashboard split or put the headline inside a white card. Do not let the collage compete with the interaction.

**Text style:** `display` — Gambarino 500 · 60px/1

### Centered chapter introduction

**Observed:** White canvas with 128px above a centered heading in a 768px text region. A body-lg support line follows after 24px, occasionally followed by a second short line. A landscape visual begins beneath the introduction rather than beside the title.

**Transfer:** Introduce a capability through a reader benefit and one short clarification; let the next visual supply the mechanics.

**Text style:** `heading` — Gambarino 400 · 36px/40px

### Immersive demonstration

**Observed:** A 1088px-wide landscape media stage dominates the chapter, sometimes with illustrated scenery, sometimes Blue demonstration stage with a centered product view. The split variant has a narrow left panel-heading and panel-body, a 48px inter-column gap and a 732px-wide demonstration on the right.

**Transfer:** Alternate centered scenes with occasional left-copy/right-media blue panels to keep long capability stories varied.

### Overlapping capability selectors

**Observed:** A blue-framed landscape with overlapping white windows sits behind three Feature selectors. Their row is wider than the media and crosses its bottom edge; one selected blue card anchors two white siblings.

**Transfer:** Connect a small set of important capabilities to one changing product scene. Retain the overlapping physical construction rather than using detached tabs.

### Landscape carousel

**Observed:** Two approximately 648px-wide media cards appear side by side in a horizontally clipped track. Caption text sits 12px below each visual; Carousel arrows are right aligned 24px beneath the captions.

**Transfer:** Use adjacent workflow examples that reward comparison, with the next card visibly extending toward the edge.

### Proof and small capability collections

**Observed:** A Collection title strip and thin top divider introduce an 896px-wide region. Testimonials use three variable-height columns of Testimonial cards; small capabilities use three equal columns of Small feature cards with 24px gutters and 48px block padding.

**Transfer:** Use variable-height cards for voices, aligned cards for feature summaries. Keep most proof cards pale blue and only a few mint or pink.

### Help and personal aside

**Observed:** The large FAQ destination panel centers its white title over blue illustration. A separate Personal note link follows below, returning to white paper and a left-aligned editorial voice.

**Transfer:** Offer help as a memorable destination, then a concise human note. Keep detailed help content on the destination rather than implying an accordion.

### Inset invitation

**Observed:** Conversion artwork panel is 960px by 480px inside a 1024px wrapper. Copy occupies the left with art-call title, short support and Compact button; tactile notebook and paper objects balance the right. Desktop interior spacing is 96px vertically and 80px horizontally.

**Transfer:** Use a short invitation and a physical product metaphor, preserving clear separation of reading area and object composition.

**Text style:** `art-call` — Gambarino 400 · 48px/1.2 · tracking -0.0101em

### Garden closing call

**Observed:** A full-width 736px-tall white ending carries a centered 36px serif benefit pair about 144px below its top, followed by Primary button after 32px. A small serif maker-location signoff and one social link sit well below. Garden world forms the lower fringe, leaving the middle almost empty; there is no dense multi-column footer.

**Transfer:** End with a compact benefit contrast, one action and a truthful personal signoff, framed by original planting. Let the full-width organic fringe provide the final visual memory.

**Text style:** `heading` — Gambarino 400 · 36px/40px

## Page flow

**Storyline:** aspirational promise → tangible interaction → editorial reassurance → visual capability chapters → user proof and compact detail → help and human context → invitation → organic closing call

### Long-form product landing page that connects emotional promise to concrete workflows

1. **Promise and interaction** — Skyborne serif promise, centered interaction, orbiting artifacts and tactile primary action.
2. **Editorial reassurance** — A narrow centered publication quotation with logo and pagination dots on white.
3. **Capability chapters** — Spacious centered headings alternate with landscape films, blue interface stages, a carousel and overlapping feature selectors.
4. **Social proof** — Pale-blue masonry quotation cards with a few mint and pink highlights.
5. **Capability detail** — Small image-first feature cards in a regular three-column grid.
6. **Objection handling and human context** — Illustrated help destination and dotted personal note link.
7. **Invitation** — Inset rounded artwork with short serif invitation and compact blue action.
8. **Closing call** — A benefit pair, blue action and maker signoff above a painted garden fringe.

**Transfer:** Adapt the number and order of chapters to the new product. Retain the contrast between skyborne promise, large concrete demonstrations, compact proof islands and a nature-framed close.

## Writing

Warmly ambitious, curious and personal rather than corporate. Broad promises are balanced by plain descriptions of what the tool does, with an occasional conversational aside.

**Do not copy:** Do not reuse Deta or Surf names, artwork, quotations, publication endorsements, repository counts, location, open-source status, privacy assertions or product claims. Source examples illustrate cadence, not facts to inherit.

- **Addressing the reader:** Use you and your for the reader's work. Use we sparingly for human intentions; product descriptions can name the product plainly.
- **Rhythm:** Short sentence-case promises, often with a period. Support usually takes one or two economical sentences; longer prose belongs in demonstrations or proof, not the opening.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A brief aspirational verb phrase addressing the reader. | 3–6 words | “Elevate your thinking.” |
| Chapter headline | A benefit framed as an action, or a compact paired quality. | 3–9 words | “Explore your interests from another level.”<br>“Private and open.” |
| Supporting line | Explain the improvement with concrete activities and readable contrast. | One or two short sentences | “Less scrolling, typing, and copying than your browser.”<br>“Get the summary and the deep dive.” |
| Primary action | Direct verb; name the product only when needed for clarity. | 1–3 words | “Download”<br>“Try Surf” |
| Closing line | Two clipped statements contrasting reduced effort with improved outcome. | 4–8 words | “Search less. Think better.” |
| Conversational aside | Brief human interruption before a dense collection. | 3–5 words | “Wait — There's More” |

**Words and phrasing to use:** your; explore; personal; curiosity; make sense; keep writing; less / better contrasts

**Avoid:** enterprise-grade transformation; unlock unprecedented synergy; revolutionary platform; aggressive urgency; stacked AI superlatives

**Rules:**

- Lead with what the reader can think, make or understand, then explain the mechanism.
- Name concrete media or activities in support copy rather than piling up abstract benefits.
- Keep navigation and action labels literal; reserve lyrical language for the serif headings.
- Allow conversational warmth in asides without making every heading a joke.

## Do's and Don'ts

### Do

- Use white as the long-page base and 128px breathing room before major chapter headings.
- Keep opening prose in a 672px region and chapter headings within 768px.
- Pair 36px regular serif chapter headings with 18px/28px sans support.
- Make blue actions tactile with the inset lower edge and 16px corners.
- Show workflows at roughly 1088px landscape scale before reducing them to small detail cards.
- Keep feature-card text compact at 14px/20px and testimonial text at 16px/24px.
- Preserve the airborne artifact collage and a planted full-width close as distinct signature devices.
- Keep pale proof collections narrower than the large demonstration stages.

### Don't

- Do not replace the serif promises with bold all-caps grotesk display type.
- Do not make all buttons pills; 16px and 10px rounded rectangles carry the main actions.
- Do not spread mint and pink across every chapter; they belong to occasional proof highlights.
- Do not turn every product image into an isolated white card on a gray dashboard-like page.
- Do not give all text condensed display lettering; it belongs to the tactile selectors.
- Do not flatten the selector row into ordinary inline text tabs; its overlap and lower lip matter.
- Do not increase card shadows into dark floating boxes; small cards use only a 1px/2px lift.
- Do not substitute a dense dark footer for the white garden-framed signoff.

## Motion and responsive

### Motion

**Observed:**

- Opening elements declare heroFadeUp at 0.8s cubic-bezier(0.16,1,0.3,1), once with forwards fill.
- A status ring declares a 2s cubic-bezier(0.4,0,0.6,1) infinite pulse.
- Main and compact buttons declare 0.2s transitions; selectors declare transform 0.2s cubic-bezier(0.4,0,0.2,1).

**Transfer:**

- Keep button lift and press movement small: -1px on hover and 2px on active. Preserve the physical lower edge as the state changes.
- Use the opening rise/fade for the sky scene's text and central object rather than adding unrelated looping ornament.

**Unknown:**

- Scroll choreography, media playback timing and focus-visible styling are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 480px, 640px, 768px, 1024px, 1280px and 1536px.
- Opening classes specify a 36px heading below the desktop 60px treatment and 16px side padding before 32px.
- Feature selectors declare two columns before three at the medium breakpoint; the conversion-art content switches from column to row at that breakpoint.
- Feature-selector gutters use clamp(14.4px, 1.8vw, 25.2px).

**Transfer:**

- On narrow layouts keep the centered promise and central product object dominant; move orbiting paper outward or reduce its scale rather than squeezing the reading column.
- Stack colored-stage copy above media and keep planting below the closing signoff. These are adaptation recommendations, not a different visual theme.

**Unknown:**

- No mobile rendering was reviewed; exact collage positions, media behavior and navigation wrapping at narrow widths remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
