# New Genre — horizons and hothouse craft

## Overview

An editorial, optimistic design language that pairs elegant narrow serif statements with a practical contemporary grotesk. White galleries sit between long atmospheric passages of midnight blue, cream and burnt orange, with richly lit botanical objects providing a tactile counterpoint to digital work. It suits ambitious creative or technology products with strong visual proof and a spacious, unhurried story.

### Essentials

- A sentence is the hero object: a left-aligned 72px serif at weight 400, 1.05 line height and -0.02em tracking, constrained to 1024px rather than stretched across the canvas.
- The opening feels like travelling through a horizon: a 2160px gradient field supports a sticky 900px stage, with the promise in the upper middle and one 48px pill near the bottom left.
- Actions are small against the scenery: 16px/1, weight 570, -0.01em tracking inside 16px 24px padding and fully rounded ends; translucent white on dark scenery, faint cool gray on white.
- Color belongs to environments, not interface chrome: full-width blue-to-cream and orange-to-brown passages bookend a predominantly white content gallery; cards remain nearly white, with 16px corners and no shadows.
- Proof is staged like a design exhibition: 16px gutters, rounded edge-to-edge media, 4:5 portrait tiles or a one-third text/two-thirds landscape split, with small labels outside the artwork.
- An organic transformation anchors the story: isolated, realistically lit specimens progress from compact to open forms in pale cards and return as a monumental 900px closing sculpture. Use a photographed natural or physical object when bespoke animation is unavailable.
- The closing invitation is another reading scene, not a banner: 64px/1.05 serif copy, a 1024px measure, 128px vertical inset and one low-positioned pill on an 1800px atmospheric field, followed by contact information and a full-screen object finale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Opening brown | `#280e01` | `--color-horizon-dark` | background | Narrow dark-brown beginning of the opening horizon. |
| Night blue | `#182644` | `--color-horizon-navy` | background | Deep blue region of atmospheric gradients. |
| Slate blue | `#5a769f` | `--color-horizon-mid` | background | Middle blue of the opening atmosphere. |
| Horizon blue | `#87a1c4` | `--color-horizon-blue` | background | Light blue transition in opening and closing atmospheres. |
| Pale blue | `#c1d3e6` | `--color-horizon-pale` | background | Light end of the opening sky. |
| Sunlit cream | `#fef9e1` | `--color-horizon-cream` | background | Warm light band before the opening dissolves into the gallery. |
| Deep earth | `#1e1310` | `--color-closing-dark` | background | Dark end of the closing invitation and upper footer. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Apricot light | `#ed9454` | `--color-closing-orange` | background, accent | Warm horizon of the default closing invitation and radial newsletter treatment; not a button color. |
| Solar yellow | `#ffe600` | `--color-newsletter-yellow` | accent | Small hot center beyond the lower-right edge of the newsletter panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text | Main gallery canvas and contrast text on dark scenery. |
| Cool translucent wash | `#f9f9fa` | `--color-soft-surface` | surface, action | Visible cool-gray wash on white for cards, tags and fields; source uses a cool gray at 6% opacity. |
| Warm paper | `#f7f3f0` | `--color-warm-paper` | background | Transition from the opening to white content. |
| Soft white lettering | `#f1f1f2` | `--color-contrast-soft` | text | Contrast lettering during atmospheric closing passages; closely related off-white variants serve the same role. |
| Fine cool rule | `#eaebed` | `--color-rule` | border | Visible hairlines on white, made with a cool dark gray at 12% opacity. |
| Cool media backing | `#e5e7eb` | `--color-media-backing` | surface | Backing beneath loaded media, not an empty visual treatment. |
| Muted ink | `#9e9fa3` | `--color-muted` | text | Visible result of primary ink at 40% opacity on white; secondary descriptions and supporting statements. |
| Blue-black ink | `#0c1018` | `--color-ink` | text | Primary text and monochrome marks. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| project, index and culture pages | Warm stone | `#ede8e3` | `--color-closing-stone` | background | Upper region of blue closing gradients. |
| playful education case studies | Mint introduction | `#dffffe` | `--color-case-mint` | background | Project-specific introductory wash, fading into white. |

## Typography

- **saans** — Section headings, descriptions, captions, controls and labels. Contemporary, closely fitted grotesk with a practical medium texture. If unavailable, use **Inter**. Use weights 450 and 570 with the stated negative tracking. Font stack: "saans", "Inter", Arial, sans-serif.
- **serrif** — Opening promises, closing invitations and editorial quotations. Narrow, high-contrast editorial serif with delicate joins and a compact lowercase rhythm. If unavailable, use **Instrument Serif**. Use regular 400; preserve the narrow measure and close line spacing. Font stack: "serrif", "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| hero | serrif | 400 | 72px | 1.05 | -0.02em | fixed | Default atmospheric opening promise and its second statement. |
| statement | serrif | 400 | 64px | 1.05 | -0.02em | fixed | Closing invitations and secondary introductory statements. |
| section-heading | saans | 450 | 32px | 1.1 | -0.01em | fixed | Section leads, project-row titles and large directional links. |
| quotation | serrif | 400 | 32px | 1.1 | -0.02em | fixed | Editorial testimonial quotation. |
| card-heading | saans | 450 | 24px | 1.15 | -0.01em | fixed | Process headings, media captions, newsletter headings and contact cities. |
| description | saans | 450 | 20px | 1.15 | -0.01em | fixed | Short supporting paragraphs, editorial card titles and service labels. |
| action | saans | 570 | 16px | 1 | -0.01em | size clamp(1rem, 1.26786rem - 0.297619vw, 1.125rem) | Navigation and pill action lettering. |
| attribution | saans | 450 | 16px | 1.4 | -0.01em | fixed | Name and role beneath a testimonial. |
| small-label | saans | 570 | 14px | 1.1 | -0.01em | size clamp(0.875rem, 1.00893rem - 0.14881vw, 0.9375rem) | Category tags and footer social links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| capability directories | chapter-heading | saans | 450 | 40px | 1.1 | -0.01em | fixed | Capability chapter titles. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Serif text is not bold or italic: its contrast comes from scale and narrow construction. Sans headings use 450 and controls use 570.
- Main statements read as continuous sentences, not uppercase slogans. At 72px and 64px the serif tracking remains -0.02em; sans roles use -0.01em.
- Supporting copy often uses the same scale as its lead but a lighter tone. Keep this relationship within introductory and closing passages rather than introducing a small body paragraph.

## Layout

**Density:** Airy, with tightly set sentences inside long, open reading stages and generous separation between media groups.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Logo-tile gaps and form-control gaps. |
| 16px | Media-grid gutters and media-to-caption spacing. |
| 24px | Horizontal pill padding. |
| 32px | Card padding and contact-group spacing. |
| 48px | Testimonial padding and newsletter content-to-form separation. |
| 64px | Desktop side insets, project-row separation and compact section gaps. |
| 96px | Major content-group separation and contact-section vertical padding. |
| 128px | Large section padding and atmospheric stage insets. |

### Containers and grids

- **page-container**: max width 1440px · side padding 64px. Centered desktop frame with 1312px usable content at a 1440px viewport.
- **statement-measure**: max width 1024px. Left-aligned serif statements and section leads, leaving the right side open.
- **media-grid**: 3 columns · gap 16px. Three equal 427px media columns; project rows allocate one column to text and two to a landscape image.
- **logo-grid**: 6 columns · gap 8px. 212px by 128px monochrome logo tiles.
- **case-pair** (only for case studies): 2 columns · gap 16px. Equal portrait media panels alternate with full-width landscape panels.
- **chapter-description** (only for capability directories): max width 640px. Compact capability lead before full-width ruled rows.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| cards-and-media | 16px |
| tags-and-fields | 8px |

## Surfaces and depth

### Surfaces

#### Gallery canvas · level 0

**Use:** Default content region.

**CSS:** `background: #ffffff; color: #0c1018`

**Observed:** Flat white without raised panels or drop shadows.

**Transfer:** Let the imagery supply texture and saturation.

#### Faint card · level 1

**Use:** Process, proof and quotation grouping.

**CSS:** `background: rgba(156,163,175,0.06); border-radius: 16px; box-shadow: none`

**Observed:** An almost-white cool wash separates the card from the canvas without a border.

**Transfer:** Use the same low visual weight for new grouped content.

#### Opening horizon · level 0

**Use:** Default marketing introduction.

**CSS:** `background: linear-gradient(180deg, #280e01 0%, #182644 12%, #5a769f 32%, #87a1c4 52%, #c1d3e6 68%, #fef9e1 84%, #f7f3f0 100%)`

**Observed:** A tall, smooth environmental gradient moves from night to daylight; text sits above it, not inside a card.

**Transfer:** Preserve the brown-to-blue-to-cream progression and large vertical span.

#### Warm closing atmosphere · level 0

**Use:** Default invitation and sculptural footer environment.

**CSS:** `background: linear-gradient(180deg, #ffffff 0%, #ed9454 45%, #1e1310 100%)`

**Observed:** The invitation descends through apricot and terracotta into deep earth. The footer continues from deep earth through red-brown to warm orange.

**Transfer:** Match the broad warm glow; exact intermediate stops are not essential. Reverse the dark-to-warm direction beneath the closing object.

#### Solar newsletter panel · level 1

**Use:** Compact signup invitation.

**CSS:** `background: radial-gradient(75% 300% at 109.6% 147.1%, #ffe600 0%, #ed9454 29.5837%, rgba(156,163,175,0.06) 100%); border-radius: 16px; overflow: hidden`

**Observed:** The warm light enters from outside the lower-right corner, leaving the text side pale.

**Transfer:** Keep the bright center away from copy and controls.

#### Blue closing atmosphere · level 0

**Only for:** project, index and culture pages

**Use:** A cooler variant of the invitation scene.

**CSS:** `background: linear-gradient(180deg, #ffffff 0%, #ede8e3 17.9459%, #87a1c4 45.2668%, #182644 88.0191%, #1e1310 100%)`

**Observed:** Warm stone gives way to blue and finally dark earth, joining the same footer.

**Transfer:** Use for evidence-heavy or people-focused page types without changing the core typography.

## Components

### Navigation link

**Use:** Compact top navigation.

**CSS:** `display: inline-flex; align-items: center; padding: 6px 10px; border-radius: 8px; color: #ffffff`

**Text style:** `action` — saans 570 · 16px/1 · tracking -0.01em

**Observed:** A small wordmark sits left and a single row of links is aligned right. Light scenes use dark lettering; the top header is fixed and can leave the viewport while reading.

**States:** Declared: hover behavior is unspecified; focus-visible outline is 2px solid lab(23.3423% -1.03992 -9.07016/.24), offset 2px.

### Scene pill

**Use:** One main action within an atmospheric stage.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 16px 24px; border-radius: 9999px; background: rgba(255,255,255,0.16); color: #ffffff`

**Text style:** `action` — saans 570 · 16px/1 · tracking -0.01em

**Observed:** Understated and left-aligned, separated from the statement by open space. A small right arrow can sit after the label. On light surfaces the pill uses the Faint card wash and ink text.

**States:** Declared: hover background becomes white at 32% opacity on dark scenes; focus-visible uses a 2px outline with 2px offset. The light pill turns dark with white text on hover and focus-visible.

### Section direction link

**Use:** Secondary navigation at the right edge of a section heading.

**CSS:** `display: inline-flex; align-items: center; padding: 6px 10px; border-radius: 16px`

**Text style:** `section-heading` — saans 450 · 32px/1.1 · tracking -0.01em

**Observed:** Text and a 32px arrow share the heading baseline. The label group is subdued to 40% opacity rather than boxed into a button.

### Project row

**Use:** Featured visual proof within a landing page.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 16px`

**Text style:** `section-heading` — saans 450 · 32px/1.1 · tracking -0.01em

**Observed:** A full-width hairline precedes the row by 64px. Left column holds title and short description near its top and category tags near its bottom; a rounded 16:9 visual spans the other two columns.

**Transfer:** Replace project titles with use cases or product outcomes while retaining the asymmetry.

### Media card

**Use:** Editorial, related-work and portfolio galleries.

**CSS:** `display: flex; flex-direction: column; overflow: hidden; border-radius: 16px`

**Text style:** `card-heading` — saans 450 · 24px/1.15 · tracking -0.01em

**Observed:** A 4:5 edge-to-edge visual appears above an unboxed caption with a 16px gap. Editorial titles use description type; project names use card-heading type. The card shell stays visually flat.

### Transformation card

**Use:** A horizontally browsable progression of stages.

**CSS:** `display: flex; flex-direction: column; overflow: hidden; border-radius: 16px; background: rgba(156,163,175,0.06)`

**Text style:** `card-heading` — saans 450 · 24px/1.15 · tracking -0.01em

**Observed:** Text is inset 32px with a 4px heading-to-description gap; a square specimen image is anchored at the bottom. Three full cards fit at desktop and the next continues beyond the edge.

**Transfer:** Show one physical motif at successive stages rather than unrelated feature icons.

### Category tag

**Use:** Small taxonomy beneath proof content.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding: 6px 10px; border-radius: 8px; background: rgba(156,163,175,0.06); color: #0c1018`

**Text style:** `small-label` — saans 570 · 14px/1.1 · tracking -0.01em

**Observed:** Compact sentence-case tags wrap with 4px gaps; they are secondary to the title and visual.

### Newsletter field

**Use:** Email input inside the Solar newsletter panel.

**CSS:** `padding: 16px; border-radius: 8px; background: rgba(156,163,175,0.06); color: #0c1018`

**Text style:** `action` — saans 570 · 16px/1 · tracking -0.01em

**Observed:** A flexible field and signup pill share a row with an 8px gap in a 512px form. Heading and support sit above, separated from the form by 48px.

### Testimonial panel

**Use:** Human proof after a visual story or partner grid.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; gap: 24px; padding: 48px; border-radius: 16px; background: rgba(156,163,175,0.06); overflow: hidden`

**Text style:** `quotation` — serrif 400 · 32px/1.1 · tracking -0.02em

**Observed:** The quotation occupies roughly 55% of the panel width; the rest remains open. Attribution sits well below the quote in attribution type with a lighter role line.

### Footer social link

**Use:** Small utility navigation above the closing object.

**CSS:** `display: inline-flex; align-items: center; padding: 6px 10px; border-radius: 8px; color: #ffffff`

**Text style:** `small-label` — saans 570 · 14px/1.1 · tracking -0.01em

**Observed:** A small symbol sits at the left, social and participation links at the right. Copyright and privacy occupy opposite lower corners of the final stage.

## Imagery and graphics

### Organic transformation sculpture

**Use:** Signature process progression and monumental closing visual.

**Observed:** Botanical specimens are isolated on pale cards, with dark slender stems, translucent crinkled gold petals and directional light. In the finale, a single hibiscus fills most of a 900px-square stage against red-brown atmosphere, its stem continuing below the frame.

**Transfer:** Use a natural or crafted physical object that can move from compact to expanded form. A carefully cut-out, warmly lit photograph is the minimum version; the finale must still feel sculptural, not like a small decorative icon.

**Build:** For a static implementation, cut out one detailed specimen with alpha transparency, contain it in a 900px square centered at the bottom of the viewport, and allow the stem or base to extend below the edge. Place it over a deep-earth-to-orange vertical gradient. For a simple original SVG alternative, layer five irregular overlapping gold petals around a slim curved stem; use translucent cream highlights, dark olive folds and a fine grain mask. Preserve asymmetry and directional light rather than a flat flower symbol.

### Horizon fields

**Use:** Opening and closing environmental graphics.

**Observed:** Smooth vertical bands of dark brown, navy, slate, pale blue and cream create a horizon without hard edges, texture or a literal landscape.

**Transfer:** Use the Opening horizon and closing surfaces as the artwork when the product has no hero media; no stock device mockup is needed above the fold.

**Build:** Fill a 2160px-tall relative block with Opening horizon. Overlay a sticky viewport-height text stage. For the invitation use an 1800px block and a warm or blue closing surface, keeping text and action on a separate foreground layer.

### Exhibition proof media

**Use:** Main proof rows, galleries and case-study sequences.

**Observed:** Artwork is intentionally varied: pixel-art night forests, lush aerial greenery, tactile interiors, brand posters and interface compositions. Saturation stays inside the rounded media frame while surrounding text remains monochrome.

**Transfer:** Use authentic product outcomes, environmental photographs and interface compositions as a curated set; retain a strong singular subject and avoid uniform stock-photo cards.

### Playful case-study media

**Only for:** playful education case studies

**Use:** Alternating landscape and paired portrait demonstration panels.

**Observed:** Mint and ice-blue illustrations, bright sticker sheets and softly modeled mascots alternate with warm domestic photographs of real children using devices. Interface demonstrations are nested inside intentional colored scenes rather than pasted raw into body copy.

**Transfer:** Use the new product's own palette and demonstration artifacts, mixing real use with isolated brand elements; keep the host page's white frame and 16px gutters.

### People and places

**Only for:** culture and team pages

**Use:** Opening horizontal image strip and portrait gallery.

**Observed:** Warm neutral wall backdrops, softly lit chest-up portraits and natural clothing create a consistent grid. A looser strip mixes interiors, architecture and candid working photographs.

**Transfer:** Photograph people in consistent soft daylight against warm stone; place name and role outside each image rather than overlaying a biography.

### Icons

**Observed:** Simple directional arrows use a 2px round-ended stroke, 16px within pills, 32px in section links and 26px beside the contact invitation. Grid/list controls use 22px outline icons. Color follows the text.

**Transfer:** Favor arrows and functional view controls; do not create a feature-icon library to replace the large visual proof.

## Section recipes

How recurring sections are built.

### First screen: Horizon sentence opening

**Observed:** The first 900px is an atmospheric reading stage. From back to front: full-width night-to-blue gradient, fixed small wordmark and right-aligned navigation, then a white serif promise at 72px within a 1024px measure, beginning around the upper third and spanning roughly three lines. It occupies about two-thirds of the width and leaves the right side open. One Scene pill sits near the lower-left, with 128px of lower breathing room. The background itself is the main object; no product picture or separate supporting paragraph competes above the fold. Scrolling through the 2160px field replaces the promise with a dark capability sentence as the horizon lightens. Partner proof starts below this opening journey.

**Transfer:** Lead with one specific product promise in two or three flowing serif lines, and let the horizon carry the first impression even without product artwork. Use the second statement to explain the mechanism. Capability and index introductions instead use a short 64px statement over a pale blue-to-white wash; culture introductions use a warm-stone wash. Case-study introductions pair a 64px project name and same-size supporting line with tags and a compact description below.

**Avoid:** Do not center the promise, add a dashboard beside it, introduce an oversized bold sans headline, or turn the quiet action into a bright filled conversion button.

**Text style:** `hero` — serrif 400 · 72px/1.05 · tracking -0.02em

### Heading and direction

**Observed:** A section-heading lead is left-aligned within a 1024px measure. Section direction link aligns at the far right, followed by 64px or 96px of space before the content group.

**Transfer:** Use conversational sentence headings rather than small uppercase eyebrow stacks.

**Text style:** `section-heading` — saans 450 · 32px/1.1 · tracking -0.01em

### Partner constellation

**Observed:** A sentence lead precedes a six-column grid of 212px by 128px pale tiles, with 8px gutters and centered black marks. A deeper proof section can place a Testimonial panel immediately below.

**Transfer:** Keep logos monochrome and equal in visual weight; use real integrations, partners or credentials relevant to the new product.

### Asymmetric featured proof

**Observed:** Project row repeats between full-width 1px rules with 64px breathing room. A narrow text column balances a two-column landscape visual; category tags sit low in the text column.

**Transfer:** Use this for outcomes, product scenarios or selected demonstrations, keeping descriptions to one short paragraph.

### Transformation rail

**Observed:** A section-heading lead introduces Transformation cards, each roughly 427px wide and 591px tall. The text occupies the top; isolated organic imagery rises from the lower square. The rail continues beyond the content frame.

**Transfer:** Use a sequence of stages or changes meaningful to the product, joined by one evolving visual metaphor.

### Editorial gallery and solar signup

**Observed:** Three-column Media cards use 427px by 533px visuals with 16px caption separation and larger row breathing room. A 1312px-wide Solar newsletter panel follows, with 32px inner padding, a compact left text block and the Newsletter field plus a pill beneath.

**Transfer:** Pair helpful updates or resources with a single signup promise instead of inserting a dense promotional sidebar.

### Atmospheric invitation and object ending

**Observed:** An 1800px gradient supports a sticky 900px invitation: 64px statement type, 1024px measure, 128px vertical inset, a darker lead sentence and a lighter continuation before the scene turns dark. A low Scene pill is followed by contact information with 96px vertical padding, two compact city/time/contact columns and a 32px arrow invitation. The final 2250px scene holds a viewport-height object stage: small symbol and social links above, monumental organic sculpture in the center, copyright and privacy below. This full ending appears across all page types.

**Transfer:** Keep the long invitation and sculptural finale as signature devices, but adapt their placement and frequency to the new page's story. Replace office data with the product's real contact or availability information; a static cut-out object can deliver the same final impression.

**Text style:** `statement` — serrif 400 · 64px/1.05 · tracking -0.02em

### Capability directory

**Only for:** capability directories

**Observed:** Each chapter opens with chapter-heading and a 24px support statement in a 640px measure. After 64px, full-width 88px rows carry 20px labels between hairlines; chapter groups are separated by 96px.

**Transfer:** Apply to capabilities, integrations or a product's technical coverage without forcing everything into cards.

**Text style:** `chapter-heading` — saans 450 · 40px/1.1 · tracking -0.01em

### Principle and portrait chapters

**Only for:** culture and team pages

**Observed:** A 32px lead introduces full-width ruled 128px rows with 24px title/support pairs. Another lead introduces a three-column portrait grid, with 427px by 508px photographs and 24px names and lighter roles beneath.

**Transfer:** Use for a product's people, approach or operating commitments only when they support that page's purpose.

### Immersive case-study gallery

**Only for:** case studies

**Observed:** Full-width 16:9 panels alternate with two-column 4:5 panels. Every media container has 16px corners; 16px gaps join the sequence. A Testimonial panel and three related Media cards provide a return from immersion to navigation.

**Transfer:** Alternate whole-product scenes with close details and real-world use, rather than annotating every image with a new heading.

## Page flow

**Storyline:** Atmospheric promise → curated proof → explanatory depth → human or editorial reassurance → immersive invitation → contact and sculptural sign-off.

### Broad marketing landing page

1. **Promise** — Two statements share a changing horizon.
2. **Social proof** — Monochrome marks in a pale tile grid.
3. **Product proof** — Asymmetric featured rows emphasize strong visual outcomes.
4. **Mechanism** — An evolving organic motif accompanies a rail of process cards.
5. **Editorial reassurance** — A media gallery and warm signup panel show an active point of view.
6. **Closing call** — Warm serif invitation, contact columns and oversized object finale.

**Transfer:** Use the contrast between immersive scenery and white proof galleries; adapt the amount and order of proof to the product.

### Deep visual case study

1. **Context** — Project name, same-size serif summary, taxonomy and concise introduction.
2. **Demonstration** — Alternating wide and paired media panels mix identity details, interfaces and real use.
3. **Human proof** — A spacious serif quotation panel.
4. **Discovery** — Three related visual cards.
5. **Closing call** — Cool atmospheric invitation and shared contact/object ending.

**Transfer:** Let visual evidence do the explaining, with text concentrated at the introduction and testimonial.

### Capability directory

1. **Promise** — Pale-blue serif introduction.
2. **Capability chapters** — Four title/support chapters with full-width ruled service rows.
3. **Social proof** — Monochrome logo grid and editorial testimonial.
4. **Closing call** — Blue atmospheric invitation followed by shared contact/object ending.

**Transfer:** Organize broad functionality into readable chapters, not a dense icon-card matrix.

### Visual proof index

1. **Orientation** — Short serif heading and lighter supporting line over pale atmosphere.
2. **Selection** — Large text filters and compact grid/list controls.
3. **Proof collection** — Three-column portrait media gallery and load-more link.
4. **Closing call** — Blue invitation, contact details and object finale.

**Transfer:** Keep filters quiet and let cover imagery dominate the browsing experience.

### People and approach page

1. **Identity** — Warm serif manifesto above a horizontal strip of places and working scenes.
2. **Principles** — Ruled rows pair compact titles with lighter statements.
3. **Human proof** — Consistent softly lit portrait grid.
4. **Closing call** — A recruitment-oriented blue invitation, then the shared contact and sculptural finale.

**Transfer:** Use a warmer introductory tone and real people while preserving the same grid, typography and ending.

## Writing

Confident and imaginative, but grounded in craft. Expansive metaphors open the conversation; practical descriptions explain what is actually made or enabled.

**Do not copy:** Do not reuse the studio name, wordmark, flower artwork, client identities, proprietary project imagery, office information, quotations, superlatives or factual claims. The source examples demonstrate voice only; all product facts and proof must be original and true. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the reader. Invitations sound like collaboration rather than sales pressure.
- **Rhythm:** Short action labels contrast with flowing multi-line serif sentences. Section leads are conversational sentences; descriptions usually explain one outcome in a single sentence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Identify the maker and its forward-looking role in one flowing statement. | A sentence of roughly 12–20 words | “[Brand] is a global design & technology studio accelerating tomorrow’s ideas.” |
| Section lead | A practical category followed by a poetic or human qualifier. | About 6–12 words | “Our work, from petal to planet.”<br>“Our process, crafted through decades of experience.” |
| Supporting description | Begin with an active verb, then say what the work enables. | One concise sentence | “We engineer scalable digital products and experiences ready for real-world impact.” |
| Closing invitation | A question followed by an optimistic collaborative possibility. | Short question plus one or two sentences | “Ready to make the leap?”<br>“Let’s turn curiosity into collaboration.” |
| Action | Plain destination or shared next step. | 2–3 words | “Our work”<br>“Contact us”<br>“Sign me up” |

**Words and phrasing to use:** shape; craft; curiosity; ideas; systems; growth; next; together; vision

**Avoid:** crush the competition; 10x everything; game-changing solution; buy now!; unmatched excellence

**Rules:**

- Pair each metaphor with a concrete mechanism or outcome nearby.
- Use natural and astronomical language sparingly as a unifying idea, not as decoration in every sentence.
- Keep control labels direct even when the surrounding statement is poetic.
- Do not invent numerical proof merely to add a stats section; visual and human proof carry this voice.

## Do's and Don'ts

### Do

- Use 72px regular serif statements for the default opening and 64px for closing scenes.
- Keep core text in a 1024px measure within the 1440px frame.
- Set desktop gallery gutters to 16px and media corners to 16px.
- Retain 128px atmospheric insets and the strong separation between statement and action.
- Use 32px card padding and 48px testimonial padding.
- Keep neutral controls small: 16px type, 48px height and 24px horizontal pill padding.
- Preserve a large physical-object sign-off even when it is static.
- Use 1px low-contrast rules to organize long lists and featured rows.

### Don't

- Do not replace the serif/sans pairing with one geometric sans family throughout.
- Do not bold the 72px hero to manufacture emphasis; regular weight is central to the effect.
- Do not paint every card with the horizon colors; the gallery is white and almost-white.
- Do not give the flat cards elevation shadows or thick outlines.
- Do not use 16px compact body text as the default for visible marketing descriptions; the prominent description role is 20px.
- Do not place captions inside tinted bars beneath media; they belong on the white page.
- Do not enlarge the 14px taxonomy into prominent colored badges.
- Do not end with only a compact link grid; the large object stage carries the final emotional impression.

## Motion and responsive

### Motion

**Observed:**

- Opening and closing passages use sticky viewport stages within taller gradient fields; the opening carries two text layers and light/dark action variants.
- Actions declare color transitions at 0.3s cubic-bezier(.4, 0, .2, 1); scene action opacity can transition over 0.5s with the same curve.
- Transformation cards declare background-color, opacity and scale transitions over 0.3s cubic-bezier(0, 0, .2, 1).
- The final object is presented as video within a sticky viewport-height stage.

**Transfer:**

- Keep the horizon and statement as coordinated layers; switch contrast as the environment lightens or darkens.
- Retain the slow visual journey through a physical object's transformation; a static object and uninterrupted gradient are the minimum composition.

**Unknown:**

- Exact scroll progress mappings, text reveal timing and object-video playback synchronization are unspecified.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 640px, 768px, 1024px, 1280px, 1440px and 1536px.
- Media grids declare one column, then two at medium width and three at large width. Transformation rails declare full-width cards, then half-width and third-width cards.
- The newsletter controls declare a vertical stack before switching to a row; contact columns also stack at narrow widths.

**Transfer:**

- Keep the reading-stage hierarchy on narrow screens: promise first, open breathing room, then the small action.
- Stack the text and visual portions of featured proof rather than reducing a three-column composition to unreadable sizes.
- Let transformation cards remain a browsable rail instead of fitting all stages into one narrow screen.

**Unknown:**

- Narrow-screen type sizes, exact side insets, header menu construction and mobile scroll-scene behavior were not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
