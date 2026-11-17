# Rox — human-scale machinery

## Overview

Warm ivory software marketing with a cinematic human face and an unusually restrained technical interior. Flared, serif-inflected display lettering sits beside matter-of-fact grotesk and system sans text, with stone grays doing almost all the work. Large interview photography, pale interface demonstrations and fine architectural rules give complex enterprise products a tangible, credible presence without making the page dense.

### Essentials

- Human testimony is the opening monument: an edge-to-edge interview image fills an 837px stage, with a centered 56px two-line promise low over the image rather than beside it.
- Headlines have a second, softer voice: regular 420-weight Season Mix at 30px/1.2 and -0.02em tracking pairs #1c1917 assertions with #87827d continuations; the opening expands this to 56px.
- Actions look like shallow rectangular hardware, not capsules: 41px-high conversion buttons use 12px 24px 13px padding, hairline lower edges and tiny inset or downward shadows; navigation actions shrink to 30px.
- Color lives inside the imagery, not across the page: #f7f6f4 canvas, white panels and warm gray text dominate; natural photographic color supplies the broad chromatic areas, with blue confined to tiny new-item labels and the fine-line closing graphic.
- Product demonstrations are pale objects on pale stages: a 1040px-wide white panel pairs a 428px capability selector with a larger interface scene, faint edges and a 0px 4px 8px shadow at 4% black.
- The close has an engineered signature: a 568px ruled invitation field, fine vertical bars and a faint blue pulse lead into a #f0eeea footer with a 1100px-wide, bottom-clipped wordmark at 12% opacity. Recreate the device with the new identity, even without bespoke artwork.
- Human proof receives a dark gallery rather than ordinary quote boxes: an 822px black-to-brown band holds three large interview portraits, compact identity captions and square 45px navigation controls.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pulse blue | `#0099ff` | `--color-pulse` | accent | Tiny gradient tips in the closing line field, not broad fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Panel white | `#ffffff` | `--color-white` | surface, action | Product panels, raised cards and light conversion actions. |
| Stage black | `#000000` | `--color-black` | background | Top of dark photographic proof bands. |
| Near-black | `#0c0a09` | `--color-strong` | text, action | Action text and product-hero headlines. |
| Warm heading ink | `#1c1917` | `--color-ink` | text, background | Default headings and brown-black end of the testimonial gradient. |
| Label charcoal | `#403f3e` | `--color-label` | text, action | Footer column labels, question text and darker pricing actions. |
| Body stone | `#57534d` | `--color-body` | text | Supporting paragraphs; editorial descriptions additionally use 60% parent opacity. |
| Soft heading gray | `#87827d` | `--color-heading-muted` | text | Second lines of promises, muted diagrams and logos. |
| Secondary stone | `#a6a09b` | `--color-subtle` | text | Low-priority links and feature support lines. |
| Hairline stone | `#dbdad3` | `--color-edge` | border, accent | Half-pixel rules, button edges and fine-line closing art. |
| Ghost wordmark | `#eae8e3` | `--color-ghost-mark` | accent | Visible footer wordmark color: #c2bdb2 at 12% opacity over limestone. |
| Footer limestone | `#f0eeea` | `--color-footer` | background | Warm footer ground. |
| Chalk band | `#f5f5f4` | `--color-band` | background, surface | Subtle broad bands behind grouped information. |
| Warm ivory canvas | `#f7f6f4` | `--color-canvas` | background | Default page ground. |
| Soft white | `#fafafa` | `--color-near-white` | surface, text | Small cards and questions; inverse headings. Over photography and dark bands, inverse secondary text uses this hue at 80% or 60% alpha. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Price ink | `#111111` | `--color-price-ink` | text | Price numerals. |
| pricing pages | Plan paper | `#faf9f7` | `--color-plan` | surface | Plan cards. |

## Typography

- **Season Mix-TRIAL** — Promises, section headings, card headings and footer column labels. A light, tightly fitted hybrid with flared serif-like terminals and an editorial rhythm; body copy remains plainly sans. If unavailable, use **Lora**. Use regular weight and tight tracking; preserve compact line lengths rather than adding boldness. Font stack: "Season Mix-TRIAL", "Lora", Georgia, serif.
- **Geist** — Navigation, buttons, larger support lines and person names. Clean contemporary grotesk, mainly regular with medium action labels. Font stack: "Geist", Arial, sans-serif.
- **system-ui** — Explanatory prose, small labels and footer links. Unembellished system sans with a generous 1.4 line height. Font stack: "system-ui", -apple-system, "Segoe UI", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Season Mix-TRIAL | 420 | 56px | 1.2 | -0.02em | Two-line opening promise; light and centered, with a softer continuation. |
| heading | Season Mix-TRIAL | 420 | 30px | 1.2 | -0.02em | Section leads, dark-gallery lead and closing invitation. |
| card-heading | Season Mix-TRIAL | 420 | 24px | 1.2 | -0.02em | Capability names and understated statistic values. |
| editorial-heading | Season Mix-TRIAL | 420 | 22px | 1.2 | -0.02em | Report and news card titles. |
| small-heading | Season Mix-TRIAL | 420 | 20px | 1.2 | -0.02em | Question rows, process step labels and video titles. |
| support | Geist | 400 | 18px | 1.4 | normal | Active capability support lines and person names. |
| quote | Season Mix-TRIAL | 420 | 18px | 1.3 | normal | Short testimonial above the opening promise. |
| body | system-ui | 400 | 16px | 1.4 | normal | Explanatory paragraphs and closing support copy. |
| button | Geist | 500 | 16px | 1 | normal | Conversion labels. |
| footer-label | Season Mix-TRIAL | 580 | 15px | 1.4 | normal | Footer column headings. |
| small-body | system-ui | 400 | 14px | 1.4 | normal | Card descriptions and footer links. |
| navigation | Geist | 500 | 14px | 1 | normal | Top navigation and compact header actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and company pages | split-opening | Season Mix-TRIAL | 420 | 42px | 1.2 | -0.02em | Left-aligned two-line opening paired with a short right-hand explanation. |
| pricing pages | price | Season Mix-TRIAL | 420 | 42px | 1 | -0.03em | Monthly price numerals. |
| product overview and capability pages | hero-support | Geist | 400 | 22px | 1.4 | normal | Centered supporting sentence below a product promise. |
| pricing pages | plan-label | Geist | 500 | 14px | 1.2 | 0.03em, uppercase | Plan names beside a small gray dot. |

**Notes:**

- Keep display weight light even when the claim is assertive; hierarchy comes from size, line breaks and ink contrast rather than bolding.
- Display tracking stays at -0.02em across most sizes. Price numerals tighten to -0.03em; prose and action labels use normal tracking.
- A second heading line is an intentional gray continuation, not a gradient applied across the lettering. On dark stages use soft-white alpha instead.
- The oversized footer identity is artwork, not a new body typography tier.

## Layout

**Density:** Airy sections enclosing compact information: wide outer fields surround closely packed selectors, lists and small controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap in the closing invitation. |
| 10px | Active capability content and tight card gutters. |
| 12px | Paired actions, portrait gutters and compact component gaps. |
| 20px | Capability card padding and three-column gutters. |
| 24px | Question-row padding and person-card image-to-copy separation. |
| 30px | Editorial card gutters and media-to-copy spacing. |
| 38px | Secondary internal vertical rhythm. |
| 44px | Section heading-to-content separation. |
| 80px | Standard section inset and top/bottom padding. |
| 100px | Editorial section top padding and expanded chapter breaks. |
| 120px | Dark-gallery top padding and split-opening top inset. |
| 158px | Expanded top breathing room before the feature selector. |

### Containers and grids

- **chapter-container**: max width 1200px · side padding 80px. Centered outer chapter wrapper; gives a 1040px interior at desktop.
- **wide-media**: max width 1200px · side padding 0px. Large product film below the centered product opening.
- **invitation-grid**: max width 1100px. Fine-rule closing field and oversized footer identity align to this secondary width.
- **three-card-grid**: max width 1040px · 3 columns · gap 20px. Capability and statistic cards; editorial stories use 30px gutters.
- **capability-pair** (only for capability detail pages): max width 1040px · 2 columns · gap 20px. Four explanatory cards in two balanced rows.
- **portrait-grid** (only for company pages): max width 1040px · 4 columns · gap 12px. Four tightly packed portrait cards.
- **customer-matrix** (only for product overview pages): max width 1040px · 5 columns · gap 8px. Small customer tiles with logo above a concise result.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion-actions | 0px |
| interface-media | 8px |
| large-product-frame | 10px |
| editorial-stage-bottom | 20px |
| footer-link-hit-area | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| product-stage | `0px 4px 8px 0px rgba(0,0,0,0.04)` | White feature selector stage. |
| paper-card | `0px 2px 6px 0px rgba(0,0,0,0.07)` | Portrait and small editorial cards. |
| invitation-edge | `0px 14px 12px -5px rgba(41,40,36,0.06)` | The slight lower lip separating invitation from footer. |

### Surfaces

#### Canvas · level 0

**Use:** Main page ground.

**CSS:** `background: #f7f6f4`

#### White demonstration stage · level 1

**Use:** Large capability selector and interface demonstrations.

**CSS:** `background: #ffffff; box-shadow: 0px 4px 8px 0px rgba(0,0,0,0.04)`

**Observed:** A broad rectangular object, not a stack of heavily rounded floating widgets.

**Transfer:** Frame one coherent product demonstration and leave its surrounding page warm.

#### Research paper · level 1

**Use:** Editorial-to-product bridge.

**CSS:** `background: linear-gradient(#f7f6f4 23.1563%, #ffffff 100%); border-width: 0px 0.5px 0.5px; border-style: solid; border-color: #dbdad3; border-radius: 0px 0px 20px 20px`

**Observed:** The warm page fades imperceptibly into a white bottom; fine rules subdivide the upper content.

**Transfer:** Use for a technical or editorial proof chapter with a large product artifact below.

#### Dark proof gallery · level 0

**Use:** Photographic testimonial chapter.

**CSS:** `background: linear-gradient(#000000 0%, #1c1917 92.5226%); padding: 120px 0px 90px`

**Observed:** Black above, warmer brown-black below; broad interview images carry the color.

**Transfer:** Separate lived customer experience from the pale explanatory body.

#### Chalk information band · level 0

**Use:** Grouped questions or institutional proof.

**CSS:** `background: #f5f5f4`

#### Footer limestone · level 0

**Use:** Footer with link columns and ghost identity.

**CSS:** `background: #f0eeea; padding: 80px 80px 180px; overflow: hidden`

#### Fine-line invitation · level 0

**Use:** Closing conversion field.

**CSS:** `background: #f7f6f4; box-shadow: 0px 14px 12px -5px rgba(41,40,36,0.06)`

**Observed:** A lightly ruled architectural field with registration dots and a low-amplitude bar landscape at its base.

**Transfer:** Use the line field as a designed closing object rather than a plain colored CTA banner.

## Components

### Navigation

**Use:** Persistent orientation over image and light sections.

**CSS:** `height: 64px; padding: 16px 80px; display: flex; align-items: center; backdrop-filter: blur(5px)`

**Text style:** `navigation` — Geist 500 · 14px/1

**Observed:** Small identity at left, six compact destinations with occasional down chevrons, then two right-aligned actions. A 40px announcement strip sits above at the opening. Over imagery links are soft white; scrolled light sections use charcoal. Compact actions are 30px high with 8px 13px padding.

**Transfer:** Keep the navigation lightweight enough to share the photographic stage.

### Light conversion button

**Use:** Default self-serve action and closing primary action.

**CSS:** `background: #ffffff; color: #0c0a09; height: 41px; padding: 12px 24px 13px; border-radius: 0px; border-width: 0px 0.5px 0.5px; border-style: solid; border-color: #dbdad3; box-shadow: 0px 1px 2px 0px rgba(0,0,0,0.14)`

**Text style:** `button` — Geist 500 · 16px/1

**Observed:** Paired with the recessed action; closing buttons are equal 235px widths with a 12px gap. The photo opening uses a wider pair to span the promise beneath it.

### Recessed conversion button

**Use:** Companion sales or assisted action.

**CSS:** `background: rgba(0,0,0,0.02); color: #57534d; height: 41px; padding: 12px 24px 13px; border-radius: 0px; border-width: 0px 0.5px 0.5px; border-style: solid; border-color: #dbdad3; box-shadow: inset 0px 1px 0px 0px rgba(0,0,0,0.04)`

**Text style:** `button` — Geist 500 · 16px/1

**Observed:** Appears to sit slightly into the surface. Over the dark photo stage the companion is transparent with light lettering. Product-only openings instead emphasize the sales action with a near-black filled button.

### Capability selector

**Use:** A single large product chapter containing several related capabilities.

**CSS:** `background: #ffffff; width: 1040px; min-height: 512px; display: flex; overflow: hidden; box-shadow: 0px 4px 8px 0px rgba(0,0,0,0.04)`

**Text style:** `card-heading` — Season Mix-TRIAL 420 · 24px/1.2 · tracking -0.02em

**Observed:** A 428px left stack centers capability names; the active row expands to include support and a chevron link. Inactive rows are muted. Right side holds a pale demonstration. A narrow update strip sits above and a muted security strip below.

**Transfer:** Use one active capability and a concrete stateful demonstration, not equal-sized feature boxes.

### Editorial row

**Use:** Dated technical updates inside Research paper.

**CSS:** `padding: 22px 36px 22px 40px; border-width: 0.5px 0.5px 0px 0px; border-style: solid; border-color: #dbdad3; display: flex; flex-direction: column; gap: 6px`

**Text style:** `body` — system-ui 400 · 16px/1.4

**Observed:** Title first, then muted date and a tiny uppercase new marker. Rows occupy the wider part of a split upper panel; an output notification can float in the adjacent product space.

**Transfer:** Use real release notes or technical publishing to connect expertise to the product artifact.

### Statistic card

**Use:** Compact quantified outcomes.

**CSS:** `background: #fafafa; padding: 20px; display: flex; flex-direction: column; gap: 17px; border: 0.5px solid rgba(28,25,23,0.08); box-shadow: 0px 2px 8px 2px rgba(0,0,0,0.04)`

**Text style:** `card-heading` — Season Mix-TRIAL 420 · 24px/1.2 · tracking -0.02em

**Observed:** Three 333px-wide cards; values stay at 24px rather than ballooning into giant counters. One short 14px description sits below.

**Transfer:** Keep evidence small and specific; use only substantiated results.

### Capability card

**Use:** Related product destinations.

**CSS:** `background: #ffffff; width: 333px; min-height: 470px; display: flex; flex-direction: column; box-shadow: 0px 2px 6px 0px rgba(28,25,23,0.08)`

**Text style:** `card-heading` — Season Mix-TRIAL 420 · 24px/1.2 · tracking -0.02em

**Observed:** Upper 246px media field holds a smaller interface vignette; title and two or three lines of support are left-aligned below, with a chevron link anchored near the bottom.

**Transfer:** Give every card a distinct product-state image, not just a different icon.

### Footer link

**Use:** Dense low-emphasis navigation columns.

**CSS:** `color: #a6a09b; padding: 4px 0px 5px; border-radius: 6px; min-height: 29px; display: flex; align-items: center`

**Text style:** `small-body` — system-ui 400 · 14px/1.4

**Observed:** Stacked under darker footer-label headings; columns are roughly 123px wide with 40px separation. Brand, social icons and small copyright occupy a separate left column.

### Question row

**Only for:** pricing pages

**Use:** Objection handling in a vertical accordion.

**CSS:** `background: #fafafa; padding: 24px; min-height: 72px; width: 1040px`

**Text style:** `small-heading` — Season Mix-TRIAL 420 · 20px/1.2 · tracking -0.02em

**Observed:** Question left, small plus right. Rows are separated by 4px of band color, with no oversized rounded enclosure.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side purchase options.

**CSS:** `background: #faf9f7; width: 340px; min-height: 365px; padding: 16px 16px 24px; display: flex; flex-direction: column; justify-content: space-between; box-shadow: 0px 5px 6px 0px rgba(0,0,0,0.03)`

**Text style:** `small-body` — system-ui 400 · 14px/1.4

**Observed:** Fine rectangular outlines, dot plus uppercase plan name, short audience description, price or contact message, optional white usage selector, then a full-width 41px action. Included-feature bullets continue below the raised card. First plan action is charcoal; later actions are medium gray.

### Portrait card

**Only for:** company pages

**Use:** Named people with credentials.

**CSS:** `background: #ffffff; width: 251px; min-height: 395px; padding: 20px; display: flex; flex-direction: column; gap: 24px; border: 1px solid rgba(28,25,23,0.08); box-shadow: 0px 2px 6px 0px rgba(0,0,0,0.07)`

**Text style:** `support` — Geist 400 · 18px/1.4

**Observed:** Square 211px photo above name and compact credential text. Consistent card height allows descriptions of different lengths; four columns with 12px gutters.

## Imagery and graphics

### Cinematic interview stage

**Use:** Opening and human-proof chapters.

**Observed:** Real seated customers in bright windowed offices, framed waist-up with softly defocused plants and architectural glazing. A dark veil makes muted green, burgundy and warm skin tones recede behind soft-white type. The opening fills the width; gallery portraits become three large nearly square frames.

**Transfer:** Commission an authentic user interview or use a single well-lit environmental portrait. Without video, a still portrait with the same negative space and dark overlay is the minimum equivalent.

**Build:** Use an object-fit: cover image layer across the stage, then a black alpha overlay around 0.35 and a stronger bottom gradient. Place text above both; keep the face clear of the lower two-line promise. Match the darkness by eye rather than forcing identical overlay stops.

### Pale product artifact

**Use:** Large demonstrations and capability-card media.

**Observed:** Actual interface windows are white and warm gray with subtle shadows, small colored details and softened peripheral edges. Large windows occupy most of a chapter; card vignettes are only 250px by 154px within a larger pale field. Some card fields use a faint stippled dot mesh fading toward the edges.

**Transfer:** Show a believable screen state with one readable task or output. For unavailable product media, construct a restrained wireframe of the essential workflow rather than using an empty white rectangle.

**Build:** For a vignette, center an 8px-radius interface window above a faint radial dot pattern: 1px rgba(28,25,23,0.10) dots on a 4px repeat, masked by a radial fade. Use layered low-alpha black shadows, white surfaces and warm-gray backing; preserve abundant margin.

### Closing line landscape

**Use:** Signature at the base of the closing invitation.

**Observed:** An 1100px-wide field of thin vertical gray bars rests on a common baseline, rising and falling in a subtle wave. A small blue concentration appears within the field. Fine horizontal and vertical rules and 3px registration dots frame the invitation.

**Transfer:** Retain this engineered field on new pages and let the wave respond to the new product metaphor without becoming a chart with invented data.

**Build:** Create 1px vertical bars separated by 4px gaps in a 161px-high overflow-hidden field. Vary heights in a smooth low-amplitude envelope. Base bars use #dbdad3; a small moving group overlays a transparent-to-#0099ff vertical gradient with staggered opacity. Add 0.5px perimeter and inset column rules plus 3px dots at selected junctions.

### Ghost identity

**Use:** Oversized clipped identity at the footer bottom.

**Observed:** A broad serif wordmark spans 1100px and extends below the footer edge. Its visible fill is only slightly darker than the limestone background.

**Transfer:** Recreate the new product's wordmark at monumental scale. If no custom identity exists, use a typographic word sculpture with the same low contrast and deliberate clipping.

**Build:** Render an SVG text or outlined wordmark in an 1100px-wide, roughly 399px-high box; fill rgba(194,189,178,0.12), center it horizontally and let the lower portion overflow a clipped footer. Keep all functional footer copy above it.

### Editorial proof artwork

**Use:** Report and announcement cards.

**Observed:** Three landscape cover images in dark olive, gold-brown and blue-gray sit above light editorial text. Strong cover typography is part of the image, not page-wide accent color.

**Transfer:** Use real publications or designed proof artifacts in muted dark palettes; keep the surrounding layout neutral.

### Technical diagrams

**Only for:** product overview pages

**Use:** Explain a system or lifecycle without photographic distraction.

**Observed:** A fine circular orbit connects pale 105px nodes around a small metallic central symbol. Architecture diagrams instead stack white horizontal strata, gray interior modules and tiny read/write connectors.

**Transfer:** Use the new product's genuine relationships. Minimum equivalent is an SVG orbit with labeled circular nodes or a few clearly connected white strata.

**Build:** Draw a 1px low-contrast circular path and distribute 105px soft-white nodes around it; use 16px system labels. For a layered diagram, use full-width white bands with inset chalk modules and tiny vertical arrows, no saturated background.

### People and workplace photography

**Only for:** company pages

**Use:** Culture opening, dark team chapter and advisor directory.

**Observed:** A wide candid office photo shows people working at shared desks. Team portraits are consistently lit against near-black green backgrounds with names over the bottom. Advisor photos retain varied real-world backgrounds but use uniform square framing on white cards.

**Transfer:** Use genuine workplace photography and consistent portrait framing; distinguish the curated team stage from the utilitarian directory.

### Icons

**Observed:** Small monochrome utility marks and chevrons, mostly 14–20px. Gallery navigation uses white chevrons inside 45px black squares. Small process and capability icons sit beside labels rather than floating above giant headings.

**Transfer:** Choose simple filled or fine outline glyphs with consistent optical weight; reserve large identity symbols for diagrams, not every feature.

## Section recipes

How recurring sections are built.

### First screen: Interview opening

**Observed:** An edge-to-edge 837px interview stage sits behind a fixed 104px header consisting of a 40px announcement and 64px navigation. Back to front: environmental portrait, dark translucent veil with darker lower edge, a short 18px quotation, a centered two-line 56px promise, then a horizontal light/recessed action pair. Text occupies roughly the middle third of the width and the lower third of the stage; the person's face remains the primary object in the upper and middle image. The second promise line is lower-contrast soft white. Within the first 900px, the announcement, navigation, face, quotation, full promise and actions are visible, followed by the beginning of the pale logo strip. Research and detailed product explanation remain below the fold.

**Transfer:** Replace the interview with a genuine user or maker portrait and a short substantiated statement. A still environmental photograph is enough if video is unavailable. Product-only pages can instead open with the same 56px promise centered on ivory, a hero-support line, paired actions and the top of a wide demonstration below; pricing and institutional pages use the smaller split-opening recipe with explanation on the right.

**Avoid:** Do not turn the default opening into a left-copy/right-dashboard SaaS template, or put the promise over the person's face.

**Text style:** `display` — Season Mix-TRIAL 420 · 56px/1.2 · tracking -0.02em

### Two-tone chapter heading

**Observed:** A 30px heading with a dark first assertion and gray second line sits left in the 1040px content area. A short chevron destination or compact paragraph aligns to the opposite edge. Content typically follows after 44px.

**Transfer:** Split a promise into an action and consequence; keep the gray continuation grammatically connected.

**Text style:** `heading` — Season Mix-TRIAL 420 · 30px/1.2 · tracking -0.02em

### Editorial expertise bridge

**Observed:** Research paper contains a two-tone heading and right-aligned link, a ruled stack of Editorial rows beside a small result notification, then a large interface window below. The main panel is 1120px wide and the interface is about 1040px wide.

**Transfer:** Use a technical publishing or release chapter to support the product's credibility; end the chapter in a concrete working artifact.

### Interactive capability chapter

**Observed:** Two-tone chapter heading leads to Capability selector, with update strip above and inset security strip below. A 158px top inset gives the composite object room to breathe.

**Transfer:** Choose a small set of related capabilities and demonstrate the currently selected one with a realistic input-to-output state.

### Editorial proof triptych

**Observed:** Three 327px-wide editorial columns with 30px gutters; landscape cover, 22px title, 16px description and small chevron link. Chapter padding is 100px above and 140px below.

**Transfer:** Combine independent proof with readable titles and restrained summaries; let the cover images provide visual variation.

### Human proof gallery

**Observed:** Dark proof gallery uses a left-aligned two-tone 30px lead and right-side square arrows. Three large interview frames span nearly the full viewport with narrow gaps, while logos and compact result captions sit beneath the portraits.

**Transfer:** Use authentic customer or practitioner stories; preserve the image-led scale even when only still photographs are available.

### Ruled closing invitation and footer

**Observed:** Fine-line invitation is 568px tall, with the centered 30px invitation about 210px from its top. An 8px support gap and roughly 27px action gap keep the central group compact. Closing line landscape sits at the bottom. Footer limestone follows with a separate brand column and six navigation columns, then a broad low-emphasis disclosure area and the Ghost identity clipped at the bottom. All page types use this ending; the institutional version goes directly from its people directory to the invitation rather than repeating the dark testimonial gallery.

**Transfer:** Retain the engineered invitation, small paired actions and monumental ghost identity. Adapt the number of footer columns to real destinations without inflating their typography.

**Text style:** `heading` — Season Mix-TRIAL 420 · 30px/1.2 · tracking -0.02em

### Compact process and outcomes

**Only for:** capability detail pages

**Observed:** A 30px section title leads to numbered horizontal steps with 20px labels, then a 1040px by 585px demonstration. A separate result row uses three Statistic cards with 24px numbers and small factual descriptions.

**Transfer:** Use short verbs for the steps and show the actual changing product state; keep numerical proof visually restrained.

### Plans and objections

**Only for:** pricing pages

**Observed:** Split-opening sits above three Plan cards with 10px gutters. Expanded comparisons follow as broad rows. A Chalk information band then carries a 30px FAQ lead, a short muted introduction and stacked Question rows.

**Transfer:** Distinguish audience and usage before listing feature detail; explain metering and commitment in direct questions.

### Institutional people chapter

**Only for:** company pages

**Observed:** Split-opening and wide candid office photo lead to a pale investor-card row. A black team chapter holds a two-tone 30px heading, small category tabs, four environmental portraits and a repeated recruitment action. A light four-column Portrait card directory follows.

**Transfer:** Preserve the difference between curated team portraits and credential directory cards; use the dark stage only for the curated human story.

## Page flow

**Storyline:** Human or product promise → tangible working proof → capability explanation → external or quantified credibility → invitation → deep utility footer.

### Brand-led marketing landing page

1. **promise** — Full-bleed interview stage with quotation, two-tone promise and paired actions.
2. **social proof** — Pale matrix of customer marks and a compact investor acknowledgement.
3. **expertise** — Ruled editorial publishing chapter resolving into a large product artifact.
4. **capability chapters** — Interactive selector and attached trust strip.
5. **external proof** — Three editorial report cards.
6. **human proof** — Dark portrait gallery.
7. **closing call** — Ruled invitation and limestone identity footer.

**Transfer:** Let authentic customer context establish the emotional stakes before showing the product's machinery.

### Purchase decision and usage explanation

1. **promise** — Compact split headline and right-side reassurance.
2. **pricing** — Three aligned plan cards, usage selectors and feature bullets outside the raised cards.
3. **comparison** — Expandable comparison and price-list rows.
4. **objection handling** — Long stack of restrained question rows.
5. **social proof** — Dark human portrait gallery.
6. **closing call** — Shared invitation and full utility footer.

**Transfer:** Focus the page on the basis of payment, audience differences and common concerns, not another long feature tour.

### Single-capability explanation

1. **promise** — Centered product name, support line, paired actions and a large workflow stage.
2. **capability chapters** — Two-by-two cards translating capabilities into practical tasks.
3. **product demonstration** — Numbered process tabs with a large changing interface view.
4. **quantified proof** — Three compact statistic cards.
5. **demonstration** — Wide presenter film.
6. **related destinations** — Three product-vignette cards.
7. **social proof** — Shared dark portrait gallery.
8. **closing call** — Shared ruled invitation and footer.

**Transfer:** Make the path from task description to useful output more prominent than the taxonomy of features.

### Whole-product overview

1. **promise** — Centered two-tone display, short support and paired actions above a wide product film.
2. **capability chapters** — Shared selector and security strip.
3. **system explanation** — Circular lifecycle diagram followed by stacked technical architecture.
4. **customer proof** — Five-column matrix of logo-and-result tiles.
5. **education** — Three-column, two-row presenter-video library.
6. **social proof** — Dark human gallery.
7. **closing call** — Shared ruled invitation and footer.

**Transfer:** Alternate abstract system explanation with recognizable interface and customer evidence.

### Institutional credibility and recruitment

1. **mission** — Split two-tone promise with short statement and recruiting link.
2. **human context** — Wide candid workplace photograph.
3. **institutional proof** — Three pale investor panels.
4. **team credibility** — Black curated portrait stage with category tabs and recruiting actions.
5. **expert credibility** — Extended four-column white portrait directory.
6. **closing call** — Shared invitation and identity footer without the testimonial gallery.

**Transfer:** Use people, workplace and relevant credentials in place of feature explanations while retaining the same pale/dark/pale material contrast.

## Writing

Confident and outcome-led, with an operator's vocabulary rather than speculative futurism. Technical specificity and human testimony lend authority; supporting copy is plain and economical.

**Do not copy:** Do not reuse Rox's identity, customer or investor names, proprietary product labels, quoted endorsements, analyst recognitions, financial amounts, performance metrics, compliance claims or office details. Replace all such assets and claims with verified material for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use your for the reader's work and outcomes. Product-led sentences name the product or describe what the agent does; institutional passages use we.
- **Rhythm:** Headlines are short clauses often divided into two complementary lines. Support is usually one sentence; task examples can be longer and quoted. Actions are two or three direct words without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active outcome or concise category statement, followed by a softer scope or consequence. | 4–10 words | “The Revenue Agent for the Global 2000”<br>“Automate your revenue and consolidate SaaS tools” |
| Section lead | A specific capability or point of view in a dark clause, then its practical effect in gray. | 5–10 words | “Applied AI research, shipped into revenue growth.”<br>“Warehouse-native, pre-built agent. Ready to deploy on every account.” |
| Supporting line | Name the concrete task range, or say what becomes repeatable. | 8–22 words | “Turn your sales process into repeatable action.”<br>“Automate your sales cycle. Choose from pre-built agents or build your own.” |
| Primary action | Direct verb plus immediate destination or action. | 2–3 words | “Contact Sales”<br>“Start now”<br>“See open roles” |
| Process label | Short imperative in ordinary language. | 3–7 words | “Describe the task in plain English”<br>“Preview and test the workflow” |
| Question | A real buying or usage concern phrased without marketing polish. | 6–16 words | “What is an agent action?”<br>“Will my unused agent actions roll over to the next month?” |

**Words and phrasing to use:** repeatable action; plain English; build your own; ready to deploy; working every account; research; workflow; privacy; production

**Avoid:** revolutionary magic; limitless possibilities; supercharge everything; friendly mascot chatter; vague transformation without a task

**Rules:**

- Tie a claim to an identifiable task, process or verified result.
- Use technical nouns where they carry useful distinctions, then explain their practical consequence.
- Write the gray continuation as part of the thought, not as a disconnected subtitle.
- Keep links functional: Learn more, Explore and short destination names fit better than clever calls to adventure.

## Do's and Don'ts

### Do

- Keep the ordinary chapter heading at 30px/1.2 with -0.02em tracking.
- Use 1040px interiors inside 1200px chapter wrappers.
- Preserve the 12px gap between equal closing actions.
- Set statistic values at 24px alongside concise factual descriptions.
- Use 0.5px stone rules to subdivide the pale editorial and closing fields.
- Give interface vignettes actual content and wide pale margins.
- Include the line landscape and faint oversized identity in the closing design.
- Maintain a clear distinction between warm canvas, white panels and limestone footer.

### Don't

- Do not make all type Geist; the flared display face is central to the character.
- Do not substitute pill-shaped conversion buttons for square 41px rectangles.
- Do not enlarge the 24px outcome values into oversized dashboard counters.
- Do not use blue as a full-width marketing section fill; it belongs to the tiny pulse and small details.
- Do not turn the low-contrast identity into a dark footer headline.
- Do not cover white product panels with heavy black drop shadows or thick outlines.
- Do not round every card to 20px; that radius belongs to the bottom of the large editorial stage.
- Do not style ordinary chapters as black panels; darkness is concentrated in human proof and the scoped team stage.

## Motion and responsive

### Motion

**Observed:**

- The navigation changes from translucent over imagery to a pale bar over the body, with the announcement strip absent in later scroll views.
- Gallery previous/next controls, process steps, capability selection and video play affordances are present; no component-specific transition durations are established.

**Transfer:**

- Use the line landscape as a restrained signal rather than a bright looping light show.
- Keep changing demonstration states inside their stable pale frame so the chapter does not jump in height.

**Unknown:**

- Exact gallery, hero-film, line-field and selector timings and easing are unspecified.

### Responsive

**Observed:**

- Desktop composition uses 1440px width. Declared layout breakpoints cluster at 810px and 1200px; pricing and institutional layouts also include 600px.

**Transfer:**

- On narrower screens preserve the face and low-positioned promise as separate readable layers; use the portrait crop rather than shrinking the desktop image indiscriminately.
- Stack the capability selector before its demonstration, collapse card columns, and retain the thin-rule invitation and clipped identity at the available width.
- Let paired actions stack only when their labels and padding no longer fit; keep the rectangular silhouette.

**Unknown:**

- Exact mobile font sizes, navigation transformation, portrait framing and grid arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
