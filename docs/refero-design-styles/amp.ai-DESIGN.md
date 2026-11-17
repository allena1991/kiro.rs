# amp.ai — adaptive domestic cinema

## Overview

A polished, approachable premium-product style that makes intelligent technology feel at home. Mostly white and pale gray, with charcoal endings and sharp orange punctuation, it pairs tightly set geometric sans-serif type with warm domestic films, oversized hardware details and candid customer photography. Spacious editorial chapters alternate with immersive demonstrations and horizontal media shelves; the tone is encouraging rather than technical.

### Essentials

- Promises read as a compact sculpture of rounded type: 95px/0.9 regular hero lettering with -0.03em tracking, then 55px/1 section headings at the same tracking.
- The opening is a lived-in product film, not a floating interface: full-width 851px media beneath a 49px announcement, a left-aligned white headline, orange action and a three-part assurance rail all fit in the first 900px.
- Orange acts as verbal punctuation and conversion signal: #ff6105 fills 230×70px pill actions and highlights short phrases within charcoal headings; the surrounding page remains overwhelmingly neutral.
- Proof feels cinematic before it feels tabular: warm, softly lit full-width scenes carry narrow 360px white copy columns, while product-detail shelves use 1123×720px media with small frosted captions. Include this immersive proof device; use a staged workflow film or carefully art-directed still if hardware footage is unavailable.
- Discovery uses oversized objects and undersized controls: a 1400×760px pale stage crops a product detail dramatically, with 56px frosted plus-sign pills along its left side. A software equivalent uses a sharply enlarged workflow detail on the same stage.
- Horizontal stories have a tactile progress handle: media rails reveal the next item beyond the right edge and use a centered 235×56px rounded scrubber with an 8px track rather than a row of dots.
- The ending becomes a substantial charcoal room: #202120, a 48px/1 medium subscription headline, outlined 50px email field and white Send pill, separated from a narrow utility column by a 1px dark rule.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff6105` | `--color-accent` | text, accent, action | Short highlighted promises, primary actions and comparison inclusion marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep charcoal | `#202120` | `--color-deep` | background, text | Footer and selected section headings. |
| Primary charcoal | `#292b2a` | `--color-ink` | text, action | Default headings, body copy and selected filters. |
| Charcoal edge | `#3c3e3d` | `--color-dark-rule` | border | Footer column divider and outlined plus icons. |
| Input edge | `#7a7b7b` | `--color-input-edge` | border, accent | Email field outline and scrubber thumb. |
| Footer gray | `#a2a3a2` | `--color-muted` | text | Secondary text and utility links on charcoal. |
| Scrubber track | `#dcdce0` | `--color-track` | surface | Inset progress track. |
| Light edge | `#e9eae9` | `--color-rule` | border | Comparison grid and light panel outlines. |
| Scrubber shell | `#ececf0` | `--color-scrubber` | surface | Progress control body, used at 0.9 opacity. |
| Frosted chip | `#eeeef2` | `--color-chip` | surface | Visible pale chip tone; source tint is rgba(232,232,237,0.72) on white. |
| Soft green gray | `#f3f4f3` | `--color-onboarding-panel` | surface, border | Numbered walkthrough panel and FAQ hairlines. |
| Cool pale gray | `#f5f5f7` | `--color-panel` | surface, text | Default editorial panel, oversized product stage and inactive FAQ categories. |
| Closing mist | `#f7f7f9` | `--color-band` | background, surface | Closing conversion band and inactive catalog filters. |
| White | `#ffffff` | `--color-canvas` | background, text, action | Main canvas, text over films and footer submit action. |

## Typography

- **PublicaSans** — All marketing headings, paragraphs, labels and controls. Rounded geometric sans with broad circular counters, single-storey forms and a friendly, low-contrast finish. If unavailable, use **Outfit**. Use weights 300–500; retain the tight display tracking and check line wrapping. Font stack: "PublicaSans", "Outfit", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | PublicaSans | 400 | 95px | 0.9 | -0.03em | fixed | Opening promise, white over full-bleed film. |
| heading-lg | PublicaSans | 400 | 55px | 1 | -0.03em | fixed | Default major section title, including highlighted continuation. |
| cinematic-heading | PublicaSans | 300 | 55px | 1 | -0.03em | fixed | White headings in immersive full-width benefit scenes. |
| stage-heading | PublicaSans | 400 | 50px | 1.1 | -0.025em | size clamp(28px, 3.5vw, 52px) | Oversized product-detail stage title. |
| walkthrough-heading | PublicaSans | 400 | 50px | 1 | -0.03em | fixed | Three-clause headline inside the numbered walkthrough. |
| footer-heading | PublicaSans | 500 | 48px | 1 | -0.03em | fixed | Subscription headline at the ending. |
| heading | PublicaSans | 400 | 45px | 1 | -0.03em | size clamp(32px, 5vw, 45px) | Centered shelf titles, FAQ and closing conversion title. |
| step | PublicaSans | 300 | 34px | 1 | -0.03em | fixed | Large numbered walkthrough selector. |
| card-heading | PublicaSans | 300 | 25px | 1.2 | normal | fixed | Frosted caption title. |
| body-lead | PublicaSans | 300 | 24px | 1.2 | -0.02em | fixed | Section support paragraphs and FAQ question labels. |
| stage-body | PublicaSans | 400 | 24px | 1.2 | normal | size clamp(18px, 2vw, 24px) | Support beside the stage heading. |
| category | PublicaSans | 300 | 24px | 0.917 | -0.02em | fixed | FAQ category pills. |
| action | PublicaSans | 500 | 20px | 1.05 | -0.02em | fixed | Primary and secondary conversion actions. |
| body | PublicaSans | 300 | 18px | 1.2 | normal | fixed | Frosted caption descriptions and shelf support text. |
| attribution | PublicaSans | 300 | 18px | 1.3 | -0.02em | fixed | Name, date and place below customer quotations. |
| footer-body | PublicaSans | 300 | 18px | 1.2 | -0.02em | fixed | Subscription support text. |
| submit | PublicaSans | 500 | 18px | 1.222 | normal | fixed | Newsletter submit action. |
| chip | PublicaSans | 400 | 16px | 1.235 | -0.022em | fixed | Plus-sign product feature chips. |
| media-caption | PublicaSans | 300 | 16px | 1.2 | normal | fixed | Portrait and demonstration media labels; also catalog filter labels. |
| quote | PublicaSans | 300 | 16px | 1.3 | -0.02em | fixed | Customer quotations beneath portrait media. |
| table | PublicaSans | 400 | 16px | 1.2 | normal | fixed | Comparison labels and status marks. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular-weight large type does most of the work; medium is reserved for actions, bold caption leads and the newsletter title.
- Most headings retain -0.03em tracking at different sizes. Body leads loosen to -0.02em, while short media labels remain normally spaced.
- Orange continuations are the same size, family and weight as the surrounding heading; they are not separate badges or decorative gradient text.

## Layout

**Density:** Airy editorial spacing around very large media, with compact controls and information rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Gap before an orange continuation in the split feature title. |
| 12px | Split-panel gutter and vertical feature-chip gaps. |
| 16px | Small control gaps and action vertical padding. |
| 20px | Media rail gaps and frosted caption inset. |
| 24px | Headline-to-support gap and paired CTA gutter. |
| 25px | Shelf image-to-caption gap and FAQ question vertical padding. |
| 36px | Walkthrough selector gaps and space above a scrubber. |
| 50px | Split-section outer padding, headline-to-action gap and closing content gap. |
| 64px | Walkthrough panel inset. |
| 80px | Major section lead vertical padding. |
| 100px | Tall feature panel vertical inset. |
| 110px | Closing band vertical padding. |
| 120px | Desktop editorial side margins. |

### Containers and grids

- **Editorial container**: max width 1440px · side padding 120px. At desktop, two 600px visual halves share a 1200px content span; titles occupy the left and short support copy the right.
- **Split stage**: 2 columns · gap 12px · side padding 50px. Two nearly equal 665px panels, with a pale text panel left and matching full-height film right.
- **Wide object stage**: max width 1728px · 2 columns · gap 72px · side padding 20px. Wide heading pair above a 1400px product stage; the stage itself reserves roughly 36% for controls and the remainder for a cropped object.
- **Media rail**: gap 20px · side padding 120px. Left-anchored horizontal shelves exceed the right viewport edge. Use 1123px feature slides, 530px collage slides, 430px expert portraits or 300px catalog clips according to content role.
- **FAQ split**: 2 columns · gap 50px · side padding 120px. Equal 575px columns: category controls left and question list right.

## Corner radius

| Element | Radius |
| --- | --- |
| Conversion actions | 54px |
| Editorial panels | 16px |
| Object stage | 28px |
| Media portraits | 10px |
| Catalog clips | 8px |
| Frosted captions | 12px |
| Feature chips | 28px |
| Newsletter field and submit | 50px |
| Scrubber | 68px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Chip inset edge | `rgba(0, 0, 0, 0.11) 0px 0px 0.5px 0px inset` | Very subtle glass-chip definition, not a floating card shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #292b2a`

**Observed:** Large uninterrupted white areas frame media and title pairs.

**Transfer:** Let imagery, not colored section containers, supply most visual richness.

#### Pale editorial panel · level 1

**Use:** Left half of paired feature and walkthrough compositions.

**CSS:** `background: #f5f5f7; border-radius: 16px`

**Observed:** No outline or drop shadow. The numbered walkthrough uses the slightly greener #f3f4f3 variant.

**Transfer:** Use the default panel for broad benefit copy and the alternate tone for step-based content.

#### Object stage · level 1

**Use:** Oversized product-detail presentation.

**CSS:** `background: #f5f5f7; border-radius: 28px; overflow: hidden`

**Observed:** A light continuous field backs a tightly cropped metallic object; the controls are layered over its open left side.

**Transfer:** Use the same pale field behind a dramatically enlarged product or workflow detail.

#### Frosted caption · level 2

**Use:** Small explanatory overlay on warm product media.

**CSS:** `background-image: linear-gradient(0deg, rgba(255, 255, 255, 0.05), rgba(255, 255, 255, 0.05)), linear-gradient(0deg, rgba(0, 0, 0, 0.1), rgba(0, 0, 0, 0.1)); border: 1px solid rgba(255, 255, 255, 0.2); border-radius: 12px; backdrop-filter: blur(90px); padding: 20px`

**Observed:** A 335×300px translucent panel picks up the warm brown media beneath it; title and description sit at opposite vertical ends.

**Transfer:** Preserve the media-derived tint and strong blur instead of painting a fixed brown card.

#### Closing mist band · level 0

**Use:** Centered paired conversion actions.

**CSS:** `background: #f7f7f9; padding: 110px 120px`

**Observed:** A restrained light band with a narrow centered title and two actions.

**Transfer:** Use to create a calm conversion pause after proof.

#### Charcoal ending · level 0

**Use:** Newsletter and utility footer.

**CSS:** `background: #202120; color: #ffffff`

**Observed:** Dark divider lines organize a broad signup area, narrow links column and bottom legal strip.

**Transfer:** Keep this substantial, spacious ending rather than reducing it to a slim logo bar.

#### Dark community interlude · level 0

**Only for:** community and shared-use stories

**Use:** Horizontal collage shelf emphasizing people and participation.

**CSS:** `background: rgba(0, 0, 0, 1); color: #ffffff`

**Observed:** Black surrounds bright photo collages, white caption leads and orange heading punctuation.

**Transfer:** Use this contrast variant only when the content has a genuine people-centered story.

## Components

### Navigation

**Use:** Persistent global orientation and compact purchase action.

**CSS:** `position: fixed; height: 64px; width: 100%; background: rgba(255, 255, 255, 0.97); z-index: 100; display: flex; align-items: center`

**Observed:** Logo left, four small links centered, account circle and compact 110×40px orange action right. Over the opening film it becomes visually transparent with light lettering; it also switches to light lettering over the black interlude.

**Transfer:** Keep navigation modest compared with the hero; use short destination names.

### Primary button

**Use:** Main conversion action.

**CSS:** `background: #ff6105; color: #ffffff; border-radius: 54px; width: 230px; height: 70px; padding: 16px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — PublicaSans 500 · 20px/1.05 · tracking -0.02em

**Observed:** A solid pill with centered text and no icon. The navigation uses a compact version.

**States:** Declared: hover background-color #f25c05; focus-visible unknown.

### Secondary button

**Use:** Low-commitment alternative beside the main action.

**CSS:** `background: transparent; color: #292b2a; border: 0.5px solid #292b2a; border-radius: 54px; width: 230px; height: 70px; padding: 16px 24px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — PublicaSans 500 · 20px/1.05 · tracking -0.02em

**Observed:** Equal visual dimensions to the primary button, outlined rather than filled.

**States:** Declared: hover opacity 0.9; focus-visible unknown.

### Feature chip

**Use:** Selectable product details over the oversized object stage.

**CSS:** `height: 56px; padding: 0px 32px 0px 16px; display: flex; align-items: center; gap: 14px; border-radius: 28px; background: rgba(232, 232, 237, 0.72); backdrop-filter: blur(20px); box-shadow: rgba(0, 0, 0, 0.11) 0px 0px 0.5px 0px inset; color: #292b2a`

**Text style:** `chip` — PublicaSans 400 · 16px/1.235 · tracking -0.022em

**Observed:** Content-sized pills form a vertical list. A thin 24px outlined circle containing a small plus precedes each label.

**Transfer:** Name one tangible attribute per chip.

### Numbered selector

**Use:** Choose a step in the paired walkthrough film.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; color: #292b2a`

**Text style:** `step` — PublicaSans 300 · 34px/1 · tracking -0.03em

**Observed:** Label left, two-digit number right; active text is charcoal and inactive text is muted gray. Three rows sit low in the panel beneath a fine separator. The unnumbered feature variant uses 45px light text with 25px row gaps.

**States:** Declared: hover color #292b2a; focus-visible border-radius 4px, outline none, box-shadow 0 0 0 2px #fff,0 0 0 4px #ff6105.

**Transfer:** Keep labels brief enough to read as large text, not menu paragraphs.

### Rail scrubber

**Use:** Tactile progress and slide selection beneath horizontal media.

**CSS:** `background: #ececf0; border-radius: 68px; width: 235px; height: 56px; padding: 0px 23px; opacity: 0.9; display: flex; align-items: center; justify-content: center`

**Observed:** An inset 189×8px rounded track contains a short dark thumb. The complete control is centered below the media, with substantial white or black breathing room.

**Transfer:** Use the shared shell across different rail sizes; update the thumb position to reflect real progress.

### Portrait media card

**Use:** Expert or practitioner proof.

**CSS:** `border-radius: 10px; overflow: hidden; position: relative; width: 430px; height: 575px; border: 1px solid transparent`

**Text style:** `media-caption` — PublicaSans 300 · 16px/1.2

**Observed:** Tall black-and-white portrait, darkened for contrast, with small white name and role at bottom left. A bottom gradient deepens from transparent to rgba(0,0,0,0.65). Cards sit in a horizontal shelf with 20px gaps.

**Transfer:** Keep roles and names factual; choose portraits with strong presence rather than avatar headshots.

### FAQ category pill

**Use:** Switch question categories.

**CSS:** `background: #292b2a; color: #ffffff; border-radius: 32px; padding: 16px 24px; height: 54px; display: flex; align-items: center`

**Text style:** `category` — PublicaSans 300 · 24px/0.917 · tracking -0.02em

**Observed:** Selected category is dark. Inactive categories use the pale editorial tone and charcoal text. Buttons wrap into short rows in the left FAQ column.

**States:** Declared: hover on inactive categories opacity 0.8; focus-visible unknown.

### FAQ question

**Use:** Expandable objection-handling row.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 16px; padding: 25px 0px; color: #292b2a`

**Text style:** `body-lead` — PublicaSans 300 · 24px/1.2 · tracking -0.02em

**Observed:** A roughly 80px row sits between pale hairlines. The question is left aligned with a thin plus at the far right; no enclosing card fill.

**Transfer:** Keep category controls separate from the question list.

### Newsletter input

**Use:** Subscription field in the dark ending.

**CSS:** `background: transparent; border: 1px solid #7a7b7b; border-radius: 50px; height: 50px; padding: 13px 26px 16px; color: #ffffff`

**Observed:** A broad outlined field sits inline with a small white submit pill, separated by 7px. It occupies most of the form width.

**Transfer:** Retain the understated outline instead of using a white rectangular field.

### Newsletter submit

**Use:** Complete the subscription form.

**CSS:** `background: #ffffff; color: #292b2a; border-radius: 50px; padding: 14px 26px; height: 50px; width: 96px`

**Text style:** `submit` — PublicaSans 500 · 18px/1.222

**Observed:** The submit control is white, not orange; it is visibly secondary to the page's sales actions.

### Comparison frame

**Use:** Dense evidence after cinematic and expert proof.

**CSS:** `background: #ffffff; border: 1px solid #e9eae9; border-radius: 10px; overflow: hidden`

**Text style:** `table` — PublicaSans 400 · 16px/1.2

**Observed:** Centered title occupies a spacious upper zone. The grid below has a wide descriptive column and six narrow comparison columns; 1px rules, 15px row padding, pale highlighted product column and tiny orange inclusion marks keep it restrained.

**Transfer:** Use a smaller honest comparison when fewer alternatives exist; retain the generous heading area and subtle column emphasis.

## Imagery and graphics

### Domestic product cinema

**Use:** Opening and immersive benefit chapters.

**Observed:** Full-width warm domestic footage mixes hands using a phone, people moving naturally and close details of a restrained metallic device. Beige walls, wood surfaces, soft daylight and muted clothing dominate; large objects continue behind the text. A dark translucent veil supports white copy without making the footage monochrome.

**Transfer:** Film a new product being used in a believable interior with warm neutral materials and soft side light. For software, show hands and screens in a lived-in setting; the minimum version is a high-quality still with the same generous composition.

### Oversized object detail

**Use:** Signature product stage and feature-detail shelf.

**Observed:** A brushed-metal control and softened rectangular hardware body are enlarged until they run beyond the right and bottom edges of a pale stage. Warm detail slides use side-lit peach-beige surfaces and a phone; the scene occupies far more space than the captions.

**Transfer:** Use a close render or photograph with real material texture, soft reflections and a physically coherent shadow. Without a physical object, enlarge one crisp workflow detail and give it the same restrained pale backing.

**Build:** Create a 1400×760px clipped panel with a 28px radius and #f5f5f7 backing. Reserve the left third for feature chips. Position an object image across the right two thirds, scaling until a meaningful detail leaves the right and bottom edges. Use one broad soft side light and a subtle contact shadow in the artwork; do not replace the object with decorative gradient blobs.

### Expert portraits

**Use:** Authority proof shelf.

**Observed:** Three tall grayscale images use close human framing, deep shadows and bottom-left names. The look is more editorial and sober than the warm product footage.

**Transfer:** Use real experts or practitioners in natural settings, keeping this grayscale treatment distinct from everyday customer proof.

### Customer proof

**Use:** Testimonial shelf.

**Observed:** 277×369px informal color photos show people beside the product in actual homes. Beneath them are small gold stars, light 16px quotations and 18px name/date/place lines. Images and copy sit directly on white without boxed cards.

**Transfer:** Preserve the candid lighting and imperfect personal settings; use genuine proof with equivalent image-to-copy proportions.

### Human collage shelf

**Only for:** community and shared-use stories

**Use:** Black interlude with 530×500px collage slides.

**Observed:** One slide tessellates warm participant portraits with rounded photo corners and a fade to white at the bottom. Another puts a shared activity scene inside a thick pale frame, with circular participant cutouts and very short overlay labels. Captions sit below rather than inside the image.

**Transfer:** Build equivalent collages around actual use, collaboration or outcomes, preserving the bright pale framing against black.

**Build:** Within a 530×500px frame, arrange a dominant portrait plus smaller rounded rectangles separated by narrow pale gutters; clip the composition at 6px outer corners. Add a bottom linear white alpha fade to the collage variant. For a shared-use variant, inset one large rounded photo and overlap two circular face cutouts near its lower corners.

### Icons

**Observed:** Feature chips use thin circular plus signs: 24px outlined circles with a 10px plus and 1.7px stroke. FAQ rows use simple plus marks; social controls are compact monochrome brand glyphs. Icons remain subordinate to text.

**Transfer:** Use simple outline utility symbols, circles and pluses rather than a colorful illustrated icon family.

## Section recipes

How recurring sections are built.

### First screen: Domestic film opening

**Observed:** The first 900px contains a 49px dark announcement strip and an 851px full-bleed film. Back to front: softly lit domestic footage, a black veil at 0.2 opacity, white navigation, a left-aligned display headline and orange Primary button, then the bottom assurance rail. The headline spans roughly the left two thirds and reads as three tightly stacked lines at 95px/0.9. It sits near the vertical middle rather than flush to the top; the action follows after 50px. No separate support paragraph competes with it. A fine translucent rule divides the bottom 89px assurance strip into three broadly spaced statements. The phone and product control remain recognizable around and behind the lettering. The following pale paired section begins below the first screen.

**Transfer:** Compose new copy into a compact multiline promise and stage the product in real use behind it. If no film exists, use a strong warm photographic still with one meaningful object or screen, not a generic abstract hero. Other marketing page types can open with a shorter promise on the same media stage and use an action appropriate to their goal.

**Avoid:** Do not replace this with a centered SaaS headline above a small floating dashboard, add a paragraph that pushes the assurance rail below the fold, or use a saturated orange hero background.

**Text style:** `display` — PublicaSans 400 · 95px/0.9 · tracking -0.03em

### Paired adaptive feature

**Observed:** Split stage pairs Pale editorial panel with equally tall edge-to-edge warm demonstration film. The left title uses heading-lg with an orange second phrase; body-lead follows after 24px. A short list of large light-weight selectors sits below. The panel has 100px vertical and 70px horizontal inset.

**Transfer:** Connect a few customer benefits to distinct demonstrable scenes, letting the active label control the adjacent media.

**Text style:** `heading-lg` — PublicaSans 400 · 55px/1 · tracking -0.03em

### Editorial heading pair

**Observed:** On White canvas, a 55px compact title occupies the left half and 24px support copy the right. 80px vertical and 120px side padding give the pair a calm cadence. One short title clause can be orange, with no eyebrow required.

**Transfer:** Lead with the outcome and explain the mechanism in one short paragraph rather than duplicating the headline.

**Text style:** `heading-lg` — PublicaSans 400 · 55px/1 · tracking -0.03em

### Cinematic benefit chapter

**Observed:** A full-width 1440×810px scene is darkened with a 0.25 black overlay. A right-aligned placement holds a left-aligned 360px copy column: cinematic-heading, then body-lead in near-white after 15px. Small translucent interface demonstrations can sit on the open left side.

**Transfer:** Use one scene per customer situation; retain the asymmetrical image-first composition rather than fitting every benefit into identical small cards.

**Text style:** `cinematic-heading` — PublicaSans 300 · 55px/1 · tracking -0.03em

### Feature-detail rail

**Observed:** Editorial heading pair leads into very wide warm product-detail media with 32px gaps and a visible next-slide sliver. Frosted caption panels sit near the lower left. A Rail scrubber is centered beneath the media.

**Transfer:** Show close evidence of how the product behaves, not decorative illustrations of feature nouns.

### Monumental object stage

**Observed:** Stage-heading and stage-body share a wide two-column header. Object stage follows after 48px; the enlarged object fills the right side while Feature chips stack on the left with 12px gaps.

**Transfer:** Present one physical or digital detail with enough scale to communicate finish, then anchor each chip to a meaningful explanation.

**Text style:** `stage-heading` — PublicaSans 400 · 50px/1.1 · tracking -0.025em

### Numbered walkthrough

**Observed:** Split stage uses a 64px-inset soft green-gray left panel and a close phone interaction film on the right. A three-clause 50px heading highlights its middle promise in orange. A fine rule separates it from three Numbered selectors with 36px row gaps.

**Transfer:** Turn setup or first success into a few clear steps with real corresponding media; keep the number at the opposite end of each row.

**Text style:** `walkthrough-heading` — PublicaSans 400 · 50px/1 · tracking -0.03em

### Browsable catalog shelf

**Observed:** A centered heading-lg combines an orange quantity with a charcoal description. Small centered group labels precede rows of 55px pale filter pills; selected filters are charcoal with white text. Tall 300×547px warm demonstration clips follow with 20px gaps and small white bottom captions; a Rail scrubber sits below.

**Transfer:** Use to prove breadth with an actual browsable set of use cases, templates or examples. Quantity must reflect the new offering.

### Layered proof

**Observed:** An Editorial heading pair introduces Portrait media cards. Comparison frame supplies structured differentiation in a separate light block. A centered 45px title then introduces unboxed candid customer images, star ratings, quotations and attribution in a horizontal shelf.

**Transfer:** Keep authority, objective comparison and lived experience visually distinct; use only the kinds of proof available to the new product.

### Conversion pause and questions

**Observed:** Closing mist band centers a 45px title in a 560px content column, with Secondary button and Primary button 50px below it. A white FAQ block uses 90px vertical padding: title above, FAQ category pills left and FAQ questions right, with 53px between title and controls.

**Transfer:** Offer a direct action and an exploratory action, then address practical purchase friction without making the FAQ the visual climax.

**Text style:** `heading` — PublicaSans 400 · 45px/1 · tracking -0.03em

### Charcoal subscription ending

**Observed:** Charcoal ending is 608px tall. A broad signup region begins 87px from the top and 120px from the left; the 48px medium headline is followed by muted support text after 40px and an inline Newsletter input plus Newsletter submit after 25px. Small consent copy sits below. A 1px vertical rule separates a narrower utility link column, with social icons low in that column. A full-width bottom rule introduces the 72px legal strip. There is no giant closing wordmark.

**Transfer:** Write a short subscription invitation tied to the new product's use, retaining the wide signup/narrow utility balance and spare dark space.

**Text style:** `footer-heading` — PublicaSans 500 · 48px/1 · tracking -0.03em

## Page flow

**Storyline:** lived-in promise → adaptive demonstration → cinematic benefits → close-up capability proof → getting started and breadth → authority and customer evidence → conversion pause → objections → subscription ending

### A premium product landing page that makes an intelligent system feel tangible and easy to adopt

1. **Promise** — Immersive film, compact oversized white headline, orange action and assurance rail.
2. **Product demonstration** — Pale split panel connects large feature selectors to warm demonstration footage.
3. **Benefit chapters** — Editorial heading pair gives way to full-width human-use scenes with narrow white copy.
4. **Capability proof** — Wide close-up slides, frosted captions and monumental object stage reveal behavior and finish.
5. **Participation and first success** — A dark collage shelf presents shared use; numbered split walkthrough clarifies the first steps.
6. **Breadth** — Orange quantity, compact filter rows and tall demonstration clips.
7. **Evidence** — Grayscale expert portraits, fine-lined comparison grid and candid customer testimonial shelf.
8. **Conversion and objections** — Pale two-action band followed by split category tabs and expandable questions.
9. **Ongoing relationship** — Substantial charcoal newsletter footer with utilities, social icons and legal strip.

**Transfer:** Adapt the sequence to the product's buying journey rather than reproducing its length. Preserve cinematic proof, an oversized detail stage, tactile media progress and the dark subscription ending even when the subject matter changes.

## Writing

Confident and warmly directive. Intelligent behavior is described through everyday relief, progress and ease rather than technical architecture.

**Do not copy:** Do not reuse amp names, logos, product imagery, proprietary interface assets, athlete identities, customer quotes, numerical claims, guarantees, financing terms or unsupported superlatives. Replace all with truthful material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your goals. The product is an active helper; we appears sparingly in reassuring promises.
- **Rhythm:** Short sentence-case headlines often split into two or three punctuated clauses. Support paragraphs explain one mechanism in a few plain sentences; action labels are brief verbs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A superlative category promise followed by a personal adaptive benefit. | 8–14 words | “The smartest all-in-one gym that adapts to you” |
| Section heading | Two complementary clauses: an intentional design quality followed by its human payoff. | 4–10 words | “Thoughtfully designed. Powerfully adaptive.”<br>“Trusted by experts. Proven by athletes.” |
| Reassurance | A short invitation followed by the product taking responsibility. | 6–12 words | “Just show up. We’ll handle the rest.” |
| Supporting line | Describe concrete adaptation and its relevance to the reader's life. | 15–35 words | “amp adapts to every training challenge, so life doesn’t stand in the way of your goals.” |
| Action | Direct verb plus minimal object. | 1–4 words | “Buy now”<br>“Book a demo”<br>“Send” |
| Closing invitation | A familiar phrase from the product's world repurposed as a subscription hook. | 3–6 words | “Never miss a rep” |

**Words and phrasing to use:** adapts to you; designed for; guided; show up; progress; your goals; every day; personalized; ready

**Avoid:** revolutionary ecosystem; synergize; disruptive paradigm; crush the competition; AI-powered everything

**Rules:**

- Put the benefit in the headline and the behavior that earns it in the supporting paragraph.
- Use parallel clauses to make orange text feel like the payoff, not an unrelated promotional badge.
- Translate intelligence into specific actions: adjusts, guides, counts, recommends or learns.
- Keep emotional language grounded in real routines and practical friction.
- Use factual labels for proof and plain spoken questions for objections.

## Do's and Don'ts

### Do

- Set hero type to 95px/0.9 with -0.03em tracking and regular weight at desktop.
- Keep ordinary section headlines at 55px/1 and use orange only for short payoff clauses.
- Give split media panels a 12px gutter and 16px corners.
- Let warm media occupy full-width 810px chapters or oversized rail slides, not just small illustrations.
- Use 230×70px conversion pills, with a half-pixel outline for the secondary action.
- Repeat the centered 235×56px scrubber wherever horizontal stories need navigation.
- Retain 1px pale comparison rules and a lightly emphasized product column.
- Close with a substantial charcoal subscription zone and white 50px-high submit pill.

### Don't

- Do not make all large headings weight 700; the main scale relies on weights 300–400.
- Do not turn the accent into broad orange section fills; it belongs to phrases, status marks and conversion pills.
- Do not apply soft drop shadows to every pale card; the panels are flat and the chip edge is an inset effect.
- Do not make catalog filters the same size as the 70px conversion controls; they are compact 55px pills.
- Do not use grayscale for everyday customer imagery; reserve that authority treatment for expert portraits.
- Do not replace the media scrubber with a dense row of pagination dots.
- Do not apply 28px corners to every surface; media, panels and large stages use different radii.
- Do not use an orange newsletter submit action on the charcoal footer; its white pill is deliberately restrained.

## Motion and responsive

### Motion

**Observed:**

- Primary action declares background-color 0.2s; secondary action declares opacity 0.2s.
- Large selectors declare color 0.2s and a two-ring orange-and-white focus-visible treatment.
- Feature chips declare opacity 400ms ease-in-out with 350ms delay; their frosted backing declares background-color 250ms linear.
- Navigation declares all 0.6s cubic-bezier(.4,0,.2,1). Benefit chapters use sticky scene panels.
- Image cards declare opacity and transform 1.2s cubic-bezier(0.28, 0.11, 0.32, 1), with filter 1.4s using the same curve.

**Transfer:**

- Use scene-sized sticky chapters for immersive storytelling and retain the tactile horizontal progress control for shelves.
- Keep text selectors synchronized with meaningful media changes rather than adding unrelated decorative motion.

**Unknown:**

- Autoplay cadence, full scroll choreography and video playback behavior are not established.

### Responsive

**Observed:**

- Styles declare breakpoints at 430px, 600px, 700px, 768px, 1000px, 1023px, 1024px and 1068px.
- The object-stage title uses clamp(28px, 3.5vw, 52px); its support uses clamp(18px, 2vw, 24px). The centered shelf title declares clamp(32px, 5vw, 45px).
- Footer declarations provide a column layout with 20px horizontal and 50px vertical padding before the wide-screen grid applies.

**Transfer:**

- On narrow layouts, stack paired text and media while preserving the pale-panel/film distinction; reduce broad editorial margins before shrinking type excessively.
- Keep shelves horizontally browsable with a visible next-card edge and usable progress control. Reframe the oversized object so it remains recognizable beside or beneath its controls.
- Keep the headline, one action and a recognizable media subject as the opening priorities.

**Unknown:**

- Exact mobile hero composition, navigation collapse and comparison-table replacement are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
