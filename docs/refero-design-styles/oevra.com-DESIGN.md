# Oevra — diffuse light, staggered verse

## Overview

An airy, experiential style that combines softly grained green light with pale grey editorial space. Light grotesk headlines drift across deliberately staggered lines, while small monospaced labels lend a research-notebook quality. Atmospheric human photography, abstract color studies and floating product views make it suited to thoughtful tools, learning products and wellbeing experiences rather than dense transactional pages.

### Essentials

- Headlines behave like staggered verse: light Suisse at 75px/1.1 or 90px/1, normal tracking, lowercase phrases with lines shifted left and right rather than a single centered rectangle.
- The opening is an atmosphere, not a product dashboard: a 900px-tall green field carries three white 75px lines across most of the width, two thin horizontal interruptions, and a small explanation and text action along the bottom.
- Controls have two distinct silhouettes: uppercase 12px/15px mono actions use 22.5px-radius capsules with 11.3px 22.5px padding, while the navigation signup is a true 90px × 50px ellipse with 50% radius.
- Color lives in light rather than UI chrome: pale #efefef editorial fields alternate with full-viewport olive atmospheres; sage-to-olive text gradients and the #778643 conversion accent stay restrained. Do not turn the whole page into solid green panels.
- Media floats inside enormous breathing space: small unframed human photographs, overlapping portrait-format product views, and a rounded abstract thumbnail embedded within a headline. Supply a procedural abstract color study when original art is unavailable.
- Proof reads like a personal note pinned to light: 345px-wide translucent cards, 15px corners, 30px padding, a small hollow circle, and 15px/18px and 12px/15px mono quotations in an overflowing horizontal strip.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lichen | `#acb58c` | `--color-lichen` | text, accent | Last gradient stop and small chapter labels. |
| Sage gradient middle | `#93a288` | `--color-sage-middle` | accent, text | Middle stop of the default text gradient. |
| Sage gradient start | `#869c85` | `--color-sage` | accent, text | First stop of the default text gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action olive | `#778643` | `--color-olive` | action, text | Recommended conversion capsule and compact price labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, action, border | Pale-field headlines, text actions and outline controls. |
| Soft black | `#4e4e4e` | `--color-body` | text | Explanations and plan descriptions on pale fields. |
| Medium grey | `#636363` | `--color-primary-grey` | text, border | Feature disclosure borders and secondary heading tone before atmospheric compositing. |
| Content grey | `#939393` | `--color-content-grey` | text, border | Secondary content and proof-card source tone; atmospheric proof uses the white-light variant. |
| Navigation grey | `#969696` | `--color-nav-grey` | text, border | Navigation links and signup ellipse on the default pale treatment. |
| Pale grey canvas | `#efefef` | `--color-canvas` | background | Base for the pale editorial fields. |
| Translucent white wash | `#f1f1f1` | `--color-proof-wash` | surface | 10% white over the pale base; over green light it remains translucent green rather than an opaque neutral. |
| Luminous white card | `#fdfdfd` | `--color-card-white` | surface | Visible near-white of 90% white over the pale canvas; use rgba(255,255,255,0.9). |
| White light | `#ffffff` | `--color-white` | text, border, surface | Headlines, rules and proof text over green atmospheres; inverse capsules. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and mission storytelling | Leaf olive | `#7c8b4a` | `--color-leaf` | text, accent | Editorial opening accent and light end of the darker gradient. |
| company and mission storytelling | Muted moss | `#566c43` | `--color-moss-middle` | text, accent | Middle of the darker editorial gradient. |
| company and mission storytelling | Deep moss | `#40633f` | `--color-moss` | text, accent | Dark end of the editorial text gradient. |
| company and mission storytelling | Editorial near-black | `#0a0a0a` | `--color-editorial-ink` | text, border | Editorial body, FAQ rules and headings on pale fields. |
| company and mission storytelling | Editorial grey | `#555555` | `--color-editorial-grey` | text | Secondary biography and community text. |

## Typography

- **suisse** — All display headings and explanatory prose; light cut for headings, regular for body. Neutral neo-grotesk with fine headline strokes, open counters and understated punctuation. If unavailable, use **Inter**. Use 300 for the light display cut and 400 for prose; retain normal tracking. Font stack: "suisse", "Inter", Arial, sans-serif.
- **space** — Navigation, numbered chapter tabs, actions, price labels and testimonial text. Monospaced, mechanical lettering that contrasts with the soft organic atmosphere. If unavailable, use **Space Mono**. Use regular 400; preserve the compact uppercase labels. Font stack: "space", "Space Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display-xl | suisse | 400 | 90px | 1 | normal | size calc(12 * min(10 * 100vw/1920,25.6px)) | Light-cut capability statement with an image between phrases. |
| display | suisse | 400 | 75px | 1.1 | normal | size calc(10 * min(10 * 100vw/1920,25.6px)) | Light-cut opening and introduction headlines. |
| heading | suisse | 400 | 45px | 1 | normal | size calc(6 * min(10 * 100vw/1920,25.6px)) | Light-cut proof and conversion headings. |
| heading-small | suisse | 400 | 33.8px | 1 | normal | size calc(4.5 * min(10 * 100vw/1920,25.6px)) | Light-cut plan titles and compact closing headings. |
| body | suisse | 400 | 15px | 1.2 | normal | size calc(2 * min(10 * 100vw/1920,25.6px)) | Regular-cut introductory paragraphs and supporting statements. |
| mono-lead | space | 400 | 15px | 1.2 | normal | size calc(2 * min(10 * 100vw/1920,25.6px)) | Short quotation leads and price amounts; prices uppercase, quotations sentence case. |
| body-small | suisse | 400 | 13.5px | 1.3 | normal | size calc(1.8 * min(10 * 100vw/1920,25.6px)) | Regular-cut feature descriptions, disclosure answers and plan conditions. |
| label | space | 400 | 13.5px | 1.3 | normal, uppercase | size calc(1.8 * min(10 * 100vw/1920,25.6px)) | Navigation, numbered chapter selectors and conversion eyebrows. |
| action | space | 400 | 12px | 1.25 | normal, uppercase | size calc(1.6 * min(10 * 100vw/1920,25.6px)) | CTA labels and compact disclosure summaries. |
| mono-caption | space | 400 | 12px | 1.25 | normal | size calc(1.6 * min(10 * 100vw/1920,25.6px)) | Longer quotation text, short benefit notes and supporting annotations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| company and mission storytelling | editorial-heading | suisse | 400 | 52.5px | 1.1 | normal | size calc(7 * min(10 * 100vw/1920,25.6px)) | Light-cut biography titles and short mission statements. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- The declared light and regular cuts both use weight 400; implement the light face as a separate cut, not as bold regular text. With the substitute, use its actual light weight.
- Keep tracking normal throughout. Hierarchy comes from the contrast between fine oversized sans and small monospace, not from exaggerated letter spacing.
- Large headlines use manually composed phrase lines and occasional negative interline margins of 15px. Keep new phrases legible rather than shrinking every headline to the same width.
- The viewport-relative root is min(10 * 100vw/1920,25.6px); the scale formulas preserve its rem relationships. Narrow layouts need a deliberate readable override, not indefinite shrinking.

## Layout

**Density:** Airy: compact prose and controls sit inside very large areas of atmospheric negative space.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 7.5px | Tight title-to-price spacing. | fixed |
| 12px | Main twelve-column gutter. | fixed |
| 15px | Inline action gap, disclosure side padding and paired-card gutter. | fixed |
| 18.8px | Proof-card horizontal gap. | fixed |
| 22.5px | Paragraph-to-control spacing within plan cards. | fixed |
| 30px | Card padding and compact vertical groups. | fixed |
| 60px | Desktop page side padding. | calc(8 * min(10 * 100vw/1920,25.6px)) |
| 75px | Introduction heading-to-copy separation. | fixed |
| 82.5px | Proof heading-to-strip and conversion intro-to-card spacing. | fixed |
| 120px | Capability headline-to-support separation. | fixed |
| 180px | Major capability and conversion section top space. | calc(24 * min(10 * 100vw/1920,25.6px)) |
| 225px | Introductory editorial field top space. | calc(30 * min(10 * 100vw/1920,25.6px)) |

### Containers and grids

- **Page grid**: max width 1440px · 12 columns · gap 12px · side padding 60px. Full-width desktop grid; use offset spans rather than equal-width centered stacks for editorial composition.
- **Reading column**: max width 360px. Narrow introduction copy placed to the right of the headline centerline.
- **Conversion island**: max width 876px · 2 columns · gap 15px. Centered eight-column area for the paired plans and split heading/support row.
- **Editorial disclosure column** (only for company and mission storytelling): max width 654px. Centered six-column FAQ area.

## Corner radius

| Element | Radius |
| --- | --- |
| Cards and inset media | 15px |
| Capsule actions | 22.5px |
| Navigation signup | 50% |

## Surfaces and depth

### Surfaces

#### Pale canvas · level 0

**Use:** Editorial sections and conversion area.

**CSS:** `background: #efefef`

**Observed:** The neutral base is suffused with diffuse green light and fine grain rather than presented as a flat sheet.

**Transfer:** Keep the underlying canvas neutral so the light can move between sections without hard boundaries.

#### Atmospheric field · level 0

**Use:** Immersive opening and proof region.

**CSS:** `background: #778643; position: relative; overflow: hidden`

**Observed:** A full-bleed olive field carries broad feathered lighter and darker green clouds with a soft granular texture. It is a backdrop, not a bounded card.

**Transfer:** Use the Diffuse light field construction; shift back to the pale canvas for detailed reading.

#### Text light gradient

**Use:** Large display phrases on pale backgrounds.

**CSS:** `background-image: linear-gradient(285.8deg, #869c85 7.1%, #93a288 43.13%, #acb58c 91.71%); background-clip: text; color: rgba(0,0,0,0); background-size: 100% 200%`

**Observed:** The gradient remains tonal and plant-like. The deeper editorial variant uses moss, muted moss and leaf olive with the same angle and stops.

**Transfer:** Do not introduce rainbow colors into headline gradients.

#### Proof glass · level 1

**Use:** Personal proof over the green atmosphere.

**CSS:** `background: rgba(255,255,255,0.1); border: 1px solid #ffffff; border-radius: 15px; padding: 30px; box-shadow: none`

**Observed:** A translucent tint and fine luminous edge, without a thick glass rim or obvious frosted blur.

**Transfer:** Retain visibility of the light field through each card.

#### Conversion card · level 1

**Use:** Plan choices over the pale field.

**CSS:** `background: rgba(255,255,255,0.9); border-radius: 15px; padding: 30px; box-shadow: none`

**Observed:** Near-opaque white panels are the page's strongest conventional containers.

**Transfer:** Reserve this density of white fill for concrete decisions rather than every feature.

## Components

### Navigation

**Use:** Persistent brand and account access outside the immersive opening.

**CSS:** `position: fixed; display: flex; justify-content: space-between; align-items: center; padding: 30px 60px; height: 110px; z-index: 10`

**Text style:** `label` — space 400 · 13.5px/1.3 · uppercase

**Observed:** A compact mark and wordmark at left; two plain links and an outlined signup ellipse at right. Links use a 37.5px gap. The immersive first screen leaves the headline unobstructed; the editorial opening displays the navigation.

**Transfer:** Use the new brand's own compact lockup; keep navigation minimal.

### Signup ellipse

**Use:** Account creation in navigation.

**CSS:** `border: 1px solid #969696; color: #969696; border-radius: 50%; padding: 15px; width: 90px; height: 50px`

**Text style:** `label` — space 400 · 13.5px/1.3 · uppercase

**Observed:** A stretched oval rather than a rounded rectangle. Editorial navigation uses black text and border.

**States:** Declared: focus-visible outline 1px solid #fff; outline-offset 1px.

### Arrow text action

**Use:** Default low-chrome action below explanatory copy.

**CSS:** `display: inline-flex; align-items: center; column-gap: 15px; color: #000000`

**Text style:** `action` — space 400 · 12px/1.25 · uppercase

**Observed:** Uppercase mono label followed by a short broken-line arrow, with no enclosing background.

**States:** Declared: focus-visible outline 1px solid #fff; outline-offset 1px.

### Olive capsule

**Use:** Highlighted conversion action.

**CSS:** `display: inline-flex; align-items: center; background: #778643; color: #ffffff; border-radius: 22.5px; padding: 11.3px 22.5px`

**Text style:** `action` — space 400 · 12px/1.25 · uppercase

**Observed:** Compact text-only capsule; the paired alternative is the Outline capsule.

**States:** Declared: focus-visible outline 1px solid #fff; outline-offset 1px.

### Outline capsule

**Use:** Alternative conversion action.

**CSS:** `display: inline-flex; align-items: center; border: 1px solid #000000; color: #000000; border-radius: 22.5px; padding: 11.3px 22.5px`

**Text style:** `action` — space 400 · 12px/1.25 · uppercase

**Observed:** The outline gives the non-highlighted choice equivalent shape without a competing fill.

**States:** Declared: focus-visible outline 1px solid #fff; outline-offset 1px.

### Proof note

**Use:** Reader quotations in a horizontally overflowing strip.

**CSS:** `width: 345px; padding: 30px; border: 1px solid #ffffff; border-radius: 15px; background: rgba(255,255,255,0.1); color: #ffffff`

**Text style:** `mono-caption` — space 400 · 12px/1.25

**Observed:** A hollow circular marker precedes the mono-lead quote; a short dash separator leads into the longer account, then a dash-prefixed uppercase name. Cards have content-driven heights and align at the top.

**Transfer:** Use real accounts with a short memorable lead; preserve the uneven note-like lengths.

### Plan card

**Use:** A concrete purchase or subscription choice.

**CSS:** `padding: 30px; background: rgba(255,255,255,0.9); border-radius: 15px; color: #4e4e4e`

**Text style:** `heading-small` — suisse 400 · 33.8px/1

**Observed:** Title, small olive mono price, regular small-print conditions, then one capsule action. Both choices use the same white surface; emphasis belongs to the button, not a badge or colored panel.

### Feature disclosure

**Use:** Compact details within a capability chapter.

**CSS:** `border: 1px solid #636363; padding: 0px 15px; color: #636363`

**Text style:** `action` — space 400 · 12px/1.25 · uppercase

**Observed:** Stacked square-corner rows share adjoining rules. A small plus at the far edge indicates expansion; a narrow vertical 'includes' bracket sits along the side of the stack. Expanded copy uses mono-caption.

**Transfer:** Group a few supporting details under an active chapter rather than presenting a dashboard of feature cards.

### Footer bar

**Use:** Low-key ending shared across page types.

**CSS:** `display: flex; flex-wrap: wrap; align-items: center; justify-content: space-between; padding: 30px 60px; color: #4e4e4e`

**Observed:** A single shallow 78px bar: copyright and linked company at left, three small social marks near the center, credits/contact/legal at right. Footer text is regular Suisse 12px/15px, with underlined company attribution; link groups have 37.5px gaps.

**Transfer:** End with a thin utilitarian signature, not a second giant navigation sitemap.

### Editorial capsule

**Only for:** company and mission storytelling

**Use:** Solid action after a mission or community passage.

**CSS:** `background: #000000; color: #ffffff; border-radius: 22.5px; padding: 11.3px 22.5px; display: inline-flex; align-items: center; column-gap: 15px`

**Text style:** `action` — space 400 · 12px/1.25 · uppercase

**Observed:** Black on the pale field; the inverse mission-band variant is white with black text and a broken-line arrow.

**States:** Declared: focus-visible outline 1px solid #fff; outline-offset 1px.

### FAQ row

**Only for:** company and mission storytelling

**Use:** Objection handling on a narrow centered column.

**CSS:** `border: 1px solid #ffffff; padding: 15px; color: #ffffff`

**Text style:** `label` — space 400 · 13.5px/1.3 · uppercase

**Observed:** Square-edged transparent accordion rows, plus symbol aligned right, no elevated cards. Atmospheric treatment is white; the pale-field variant uses near-black rules and text. Answers use body-small.

## Imagery and graphics

### Diffuse light field

**Use:** Signature atmosphere across the opening, editorial pauses and proof; it must recur on a new page.

**Observed:** Olive, pale lime and forest-green clouds fill the entire viewport, with very soft transitions and fine noise. Pale sections retain wandering green halos rather than becoming plain white; proof sections deepen to green with white text.

**Transfer:** Recreate the feeling of light seen through translucent foliage. Exact stops are not essential; keep broad indistinct shapes and readable foreground contrast.

**Build:** On the pale canvas, layer three absolutely positioned ellipses of roughly 600px–1000px width: lichen rgba(172,181,140,0.6) at upper left, pale white rgba(255,255,255,0.65) near center-right, and sage rgba(134,156,133,0.5) near lower center. Blur the layers by 100px–180px, allow generous overflow and overlay low-opacity monochrome SVG fractal noise. For the saturated version, use the olive base, deepen one 700px ellipse with rgba(64,99,63,0.7), and add elongated white-light blooms at 0.2–0.35 alpha. Do not draw distinct radial rings.

### Inline abstract study

**Use:** A small visual interruption inside a major headline.

**Observed:** A rounded landscape thumbnail containing fluid purple, peach and deep blue reflections sits between phrases; an editorial variant is a small portrait color study.

**Transfer:** Include one compact abstract study even when there is no original product art. It should feel like a tactile swatch rather than an app icon.

**Build:** Clip an SVG or CSS artwork to a roughly 110px × 75px box with 15px corners. Layer narrow curved bands in deep blue and mauve over a peach field; blur the bands slightly and add restrained grain. Use high chromatic intensity only within this small artwork.

### Floating human photography

**Use:** Experiential interludes and the editorial closing collage.

**Observed:** Unframed rectangular pictures of people making, dancing, writing and working in tactile surroundings. They range from small isolated central images to edge-clipped portraits around an empty center. Natural color, imperfect movement and human activity matter more than studio polish.

**Transfer:** Show people using the new product's underlying practice, not generic posed teams. Keep images relatively small against the light field and vary their vertical position. The minimum is two or three original activity photographs with generous negative space.

### Overlapping product views

**Use:** Capability chapters below the display statement.

**Observed:** Portrait-format device and interface images overlap as a loose fan; a larger foreground screen sits before smaller pale device images. Backing is neutral and softly lit, with the page glow continuing around it.

**Transfer:** Stage real product views on a few portrait planes, emphasize one in front and keep secondary views subdued. Do not fabricate empty UI panels as decoration.

### Research-film backdrop

**Only for:** company and mission storytelling

**Use:** Long-form experiential proof panels.

**Observed:** Full-bleed movement photography with teal sky and motion-blurred figures in light clothing; small numbered notes and fine-bordered annotations are overlaid in white.

**Transfer:** Use a full-bleed image or short film that evokes the product's human outcome, with sufficient tonal separation for the restrained copy.

### Portrait and workspace pairing

**Only for:** company and mission storytelling

**Use:** Founder or maker biography.

**Observed:** A 323px × 408px portrait and a smaller 218px × 272px workspace photograph accompany offset text columns.

**Transfer:** Pair a human portrait with evidence of their working environment, preserving the unequal scale rather than making a team-avatar grid.

### Icons

**Observed:** CTA arrows are spare black or white marks around 26px × 10px with 2px butt-ended strokes; a broken shaft gives them a typed-diagram quality. Small social marks are filled 18px icons. Hollow circles and small plus signs act as editorial punctuation.

**Transfer:** Use a narrow set of simple line marks for actions and disclosures. Keep feature illustrations out of the icon system; let the photography and abstract art carry expression.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric verse opening

**Observed:** A full-viewport 900px scene with an uninterrupted Diffuse light field behind white light-cut display text. Three lowercase benefit phrases span roughly four fifths of the page across the middle: the first is centered, the second starts farther left and leaves a short thin rule at right, and the third shifts right with a balancing rule at left. The main object is the atmosphere itself, not a device. Within the first 900px the complete headline, a small three-line product explanation low on the right half, a small trial text action at the far lower right, and a vertical scroll cue at lower left are visible. The editorial explanation and product imagery begin below the fold. The opening navigation does not compete with the verse.

**Transfer:** Write three distinct benefit phrases for the new product and compose them as staggered verse with two fine rules. Make a procedural Diffuse light field when no film or art exists. For company-story openings, use the pale field, visible Navigation, green display text, a right-offset reading column and a few floating images instead.

**Avoid:** Do not replace this with a centered SaaS heading, two large buttons and a laptop mockup, or place the explanation directly below the headline in the middle.

**Text style:** `display` — suisse 400 · 75px/1.1

### Staggered editorial promise

**Observed:** A pale field with 225px top space and 60px side padding; a four-line gradient display heading occupies a central offset area. An uppercase availability annotation sits to its left, while a 360px-wide paragraph and Arrow text action sit farther right below it.

**Transfer:** Use this for the concrete explanation after an emotional opening. Keep label, headline and prose on separate alignments rather than centering all three.

**Text style:** `display` — suisse 400 · 75px/1.1

### Capability chapter

**Observed:** A 90px light-cut headline forms three staggered lines with an Inline abstract study inside the second line. A small chapter label sits beside it; support copy follows with 120px separation. Below, numbered mono selectors occupy a three-column/two-row group at left, Feature disclosure rows sit beneath, and Overlapping product views fill the right.

**Transfer:** Separate an evocative capability claim from specific tools. Keep chapter selectors small and editorial rather than using colorful navigation pills.

**Text style:** `display-xl` — suisse 400 · 90px/1

### Affirmation strip

**Observed:** Atmospheric field, centered 45px heading with a small parenthesized index at its upper right, then Proof notes separated by 18.8px. The row overflows beyond the right edge and aligns cards at the top.

**Transfer:** Use candid customer language or first-hand observations, not a uniform star-rating grid.

**Text style:** `heading` — suisse 400 · 45px/1

### Paired conversion island

**Observed:** A centered 876px area on the pale light field. An uppercase eyebrow and two-line 45px heading occupy the left half; support and Arrow text action occupy the right. After 82.5px, two equal Plan cards sit side by side with a 15px gap. The Footer bar follows without a giant closing graphic.

**Transfer:** Adapt to two commitment levels or two clear ways to begin. Preserve the modest mono price treatment and decisive capsule hierarchy.

**Text style:** `heading` — suisse 400 · 45px/1

### Editorial objection and mission passage

**Only for:** company and mission storytelling

**Observed:** A centered 654px FAQ column on green light uses a 45px title and transparent FAQ rows. Below it, a 52.5px staggered white statement has a faint geometric rosette between words, followed by a short rule, a narrow supporting paragraph and an inverse Editorial capsule.

**Transfer:** Answer practical doubts, then move to a brief human belief. For the rosette, draw four faint overlapping outline circles in a small square rather than using a large emblem.

**Text style:** `editorial-heading` — suisse 400 · 52.5px/1.1

### Photographic community close

**Only for:** company and mission storytelling

**Observed:** A 900px pale field with green bloom. A 432px-wide central-left text block uses a 33.8px two-line invitation, a small support paragraph and a black Editorial capsule. Five portrait activity photographs float around the perimeter, with some clipped by the edges. Small mono reassurance lines sit near the upper right. The shared Footer bar ends the page.

**Transfer:** Let people and the product's practice surround a clear invitation; swap the source subjects for genuine customer activities. Preserve the open center and sparse footer.

**Text style:** `heading-small` — suisse 400 · 33.8px/1

## Page flow

**Storyline:** Emotional promise → concrete explanation → experiential demonstration → specific capabilities or rationale → human proof → a clear way to begin → shallow utility footer.

### Immersive product marketing and conversion

1. **Promise** — Full-viewport staggered white benefit verse over organic green light.
2. **Product explanation** — Pale-field gradient headline, offset narrow prose and a small arrow action.
3. **Experiential demonstration** — Extended scroll-led media scenes with small human activity imagery and atmospheric space.
4. **Capability chapters** — Large inline-art heading, numbered selectors, compact disclosures and overlapping product views.
5. **Social proof** — White-on-green personal notes in an overflowing horizontal strip.
6. **Conversion** — Split invitation and support above two white plan choices.
7. **Utility ending** — Copyright, compact social marks and legal links in one shallow row.

**Transfer:** Use the contrast between emotional atmosphere and specific small copy. The media journey can be shorter for a simpler product; retain the staggered type, recurring light field, inline study and personal proof device.

### Explain the people, rationale and human value behind a product

1. **Origin** — Pale-field green verse, right-offset prose and scattered small photographs.
2. **Rationale** — Full-bleed movement imagery with numbered research-oriented statements and fine annotations.
3. **Human credibility** — Offset biography with portrait and smaller workspace image.
4. **Invitation** — Green headline and compact solid action.
5. **Objection handling** — Narrow transparent accordion stack.
6. **Belief** — White mission verse over green atmosphere with a short supporting statement.
7. **Community invitation** — Pale photographic collage around a compact central-left invitation and reassurance notes.
8. **Utility ending** — The same shallow footer used for product marketing.

**Transfer:** Use this variant for company, philosophy or research-led storytelling. Substitute relevant rationale and real maker context without turning the page into a conventional staff grid.

## Writing

Reflective, encouraging and lightly research-minded. It joins an emotional promise to a practical explanation without sounding like a loud productivity pitch.

**Do not copy:** Do not reuse the Oevra name, logo, proprietary process, founder identity, customer quotations, trial terms, prices, scientific claims or source-specific research assertions. Use independently substantiated facts and original language for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to 'you' for benefits and invitations; use 'we' for beliefs and origins. Introduce the product in plain third-person language when explaining what it does.
- **Rhythm:** Lowercase display phrases read as a flowing sentence broken into short lines. Prose is compact but complete, often using an em dash to connect an idea with a concrete explanation. Actions are brief uppercase mono labels, not mini-headlines.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening benefit verse | Three direct, human outcomes in parallel verb phrases. | 4–6 words per phrase | “realize your creative potential”<br>“overcome any blocks”<br>“find inspiration within” |
| Capability headline | A gentle conceptual metaphor joined to a practical grounding phrase. | 7–12 words | “the creative process down to a science” |
| Support | Acknowledge the reader's starting point, then explain tools and intended benefits in one coherent paragraph. | 25–50 words | “Whether or not you consider yourself creative, oevra is designed to train your brain to think more creatively — with structured daily practices, guided exercises, focus tools, courses, and everything you need to break through creative blocks.” |
| Action | Plain verb plus destination or next step. | 2–4 words | “Get the app”<br>“Activate now”<br>“Discover the app” |
| Belief statement | Short everyday proposition that broadens the product into a human practice. | 4–9 words | “life is a creative process” |

**Words and phrasing to use:** practice; support; within; flow; holistic; designed to; inspired by; process; community

**Avoid:** crush it; 10x everything; dominate; game-changing; unlimited potential guaranteed; hustle

**Rules:**

- Lead with a felt benefit, then explain the mechanism in smaller type.
- Use research language only when a specific claim is supportable.
- Make the invitation feel like beginning a practice, not winning a competition.
- Keep actions unembellished; let the environment carry the emotion.

## Do's and Don'ts

### Do

- Use the 75px/1.1 light display recipe for the opening verse.
- Keep desktop editorial side padding at 60px and the main grid gutter at 12px.
- Give plan and proof cards 30px padding and 15px corners.
- Use 12px/15px uppercase mono for compact actions.
- Keep prices at 15px/18px mono rather than promoting them to display size.
- Let at least one proof card extend beyond the viewport in the horizontal strip.
- Keep the footer shallow, with 30px vertical padding rather than a large closing sitemap.
- Alternate pale and saturated light fields without hard-edged colored bands.

### Don't

- Do not apply bold weight or compressed tracking to the fine grotesk headlines.
- Do not replace the signup ellipse with the 22.5px-radius conversion capsule; they serve distinct roles.
- Do not add drop shadows to the white plan cards or translucent proof notes.
- Do not enlarge the inline abstract study until it becomes a competing hero illustration.
- Do not fill every capability with white rounded cards; use small numbered selectors and square disclosures.
- Do not make price amounts the largest elements in their cards.
- Do not use saturated green for every button, label and border; the page relies on restrained olive actions.
- Do not replace the human activity photographs with identical studio headshots.

## Motion and responsive

### Motion

**Observed:**

- Declared action/surface transitions include color 0.2s ease-out, opacity 0.3s ease-out, and opacity 0.2s ease-out with transform 0.8s cubic-bezier(0.43, 0.195, 0.02, 1).
- The light and halo layers are fixed viewport-sized canvases; the halo uses plus-lighter compositing. Long media sections support an immersive scroll-led experience.
- A noise keyframe is declared; action focus-visible rules specify a 1px white outline with 1px offset.

**Transfer:**

- Keep any scene movement behind the sparse editorial foreground. Use gradual changes in the light field to link pale and green sections rather than discrete slide transitions.
- Use the declared transform curve only for deliberate reveal movement; keep small controls on the short color/opacity transitions.

**Unknown:**

- Exact scroll choreography, light-field generation, noise timing and all hover appearance changes are not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 768px, 1023px, 1024px, 1280px, 1366px, 1536px and 1920px.
- Narrow-layout classes switch the footer to a left-aligned column, turn capability details into a column and remove desktop-only line breaks.

**Transfer:**

- On narrow screens recompose the verse into shorter phrase lines and reduce the ornamental rule lengths; preserve a full-screen atmospheric first impression.
- Stack the paired conversion choices and move floating photos away from the central reading area. Keep small mono text readable rather than scaling it down indefinitely.

**Unknown:**

- Exact mobile font sizes, page padding, navigation behavior and image arrangements are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
