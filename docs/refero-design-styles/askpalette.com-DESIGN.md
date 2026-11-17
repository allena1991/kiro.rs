# Palette — charcoal with a sunset

## Overview

A dark, gallery-minded style that pairs compact, tightly set grotesk typography with exuberant creative work. Charcoal and soft white keep the interface restrained while photography, identity graphics and dimensional logo tiles supply the color. It suits curated services, creative tools and products whose outcomes can be shown rather than diagrammed at length; spacious openings give way to small, dense explanations and a warm-to-blue closing band.

### Essentials

- A small floating control bar above a delayed promise: a centered 640px × 58px glass capsule sits 24px from the top, while the main content begins after 250px of dark breathing room.
- Headlines feel like compact statements, not posters: Geist 500, 64px/0.95 with -0.02em tracking for the opening, then 42px/1 with -0.02em tracking for section leads; centered copy wraps into deliberate short lines.
- Actions are tiny high-contrast lozenges: 42px height, 8px 16px padding, 18px text and fully rounded ends; white on dark, reversed to black on the bright closing band.
- Color belongs to the work and the final invitation: most page chrome is #141414, with an orange proof badge only 26px high and a full-width 388px orange–gold–blue band as the signature release.
- Proof becomes an object: use an edge-clipped ribbon of vivid work and a perspective ring of rounded identity tiles around a central statement; when finished work is unavailable, use original product-output studies and abstract feature symbols in those same frames.
- Explanations stay deliberately small beside the spectacle: 260px × 296px process cards with 160px monochrome illustration stages, and a 500px-wide stack of 46px FAQ rows with circular plus controls.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sunset orange | `#fc6435` | `--color-orange` | accent, background | First gradient stop and solid count capsule. |
| Warm gold | `#ffb638` | `--color-gold` | background | Middle stop of the signature closing gradient. |
| Sky blue | `#80bdff` | `--color-blue` | background | Bottom stop of the signature closing gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof orange | `#fc6338` | `--color-orange-text` | text | Proof badge label. |
| Ember wash | `#2b1c17` | `--color-orange-wash` | surface | Visible orange at 10% over charcoal behind the proof badge. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, surface | Headings, primary actions and high-contrast graphic marks. |
| Black | `#000000` | `--color-black` | text, action | Text on white actions and gradient bands; closing action fill. |
| Deeper charcoal | `#0f0f0f` | `--color-footer` | background | Footer band. |
| Charcoal canvas | `#141414` | `--color-canvas` | background | Default page background. |
| Low charcoal lift | `#202020` | `--color-card` | surface | FAQ fill and visible white at 5% over the canvas for process cards. |
| Illustration wash | `#2b2b2b` | `--color-stage` | surface | Visible #f6f6f6 at 10% over the canvas; used as a layered process illustration stage, appearing brighter over a raised card. |
| Glass gray | `#2c2c2c` | `--color-glass` | surface | Visible white at 10% over the canvas for the floating navigation; changes with the imagery beneath. |
| Control gray | `#3a3a3a` | `--color-control` | surface | Circular FAQ plus controls. |
| Muted gray | `#6b6b6b` | `--color-muted` | text | Process descriptions, brand proof labels and footer description. |
| Soft white | `#a1a1a1` | `--color-secondary` | text, link | Visible white at 60% over charcoal for support copy and navigation. |

## Typography

- **Geist** — Marketing headings, body text, actions and wordmark-style text. Contemporary grotesk, mostly medium weight, with tightly fitted letters and open, clear forms. OpenType features: "blwf", "cv03", "cv04", "cv09", "cv11". Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 64px | 0.95 | -0.02em | Default landing-page promise. |
| heading | Geist | 500 | 42px | 1 | -0.02em | Centered section leads, compact secondary-page openings and closing call. |
| wordmark | Geist | 600 | 22px | 1.07 | -0.03em, features normal | Compact brand name in navigation and footer. |
| action | Geist | 500 | 18px | 26px | -0.02em | Both action pill variants. |
| card-title | Geist | 500 | 18px | 24px | -0.03em | Short centered process card titles. |
| body | Geist | 500 | 16px | 22px | -0.02em | Opening support, FAQ questions and editorial paragraphs. |
| compact-body | Geist | 500 | 16px | 22px | -0.03em | Navigation, process descriptions, proof labels and closing support. |
| small | Geist | 500 | 14px | 20px | -0.02em | Footer descriptions, link columns and column headings. |
| proof | Geist | 600 | 14px | 22px | -0.02em | Proof count and adjacent label. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company or editorial pages | editorial-eyebrow | Geist | 400 | 14px | 20px | -0.03em | Small sentence-case label above an editorial opening. |
| company or editorial pages | byline | Geist | 500 | 14px | 16px | -0.02em | Centered author name and muted role. |

**Notes:**

- The default weight is 500, including body copy; contrast comes from size and color rather than heavy bold headings.
- Display and section headings use -0.02em tracking, while navigation and process copy tighten to -0.03em. Keep these distinct even at the same 16px size.
- White section headings generally occupy a 470px-wide measure; opening support narrows to 400px. Editorial prose is left aligned at 500px.

## Layout

**Density:** Airy overall, with large dark intervals around very compact actions, cards and footer text.

### Spacing

| Value | Use |
| --- | --- |
| 5px | FAQ row separation and title-to-description gap inside process cards. |
| 8px | Navigation inset and action vertical padding. |
| 10px | Footer content gaps and masonry gutters. |
| 16px | Heading-to-support gap in the closing call and horizontal action padding. |
| 20px | Opening stack gaps, navigation link gaps, process card gutters and prose paragraph gaps. |
| 24px | Navigation top offset, closing support-to-action gap and editorial opening stack. |
| 50px | Top padding for explanatory sections and footer. |
| 60px | Section heading-to-card or heading-to-FAQ stack gap. |
| 100px | Closing band vertical padding. |
| 120px | Bottom breathing room after FAQ, editorial prose and masonry. |
| 250px | Landing-page opening top padding. |

### Containers and grids

- **Main container**: max width 1280px · side padding 20px. Centered explanatory content; inner usable width is 1240px.
- **Heading measure**: max width 470px. Centered multi-line section headlines.
- **Support measure**: max width 400px. Centered opening and closing support text.
- **Process row**: max width 820px · 3 columns · gap 20px. Three equal 260px cards centered well inside the main container.
- **Reading column**: max width 500px. FAQ stack and left-aligned editorial prose.
- **Footer container**: max width 1240px · gap 24px · side padding 20px. A broad brand column on the left and three approximately 195px link columns on the right.
- **Masonry wall** (only for work collection pages): 5 columns · gap 10px · side padding 10px. Near-edge-to-edge image columns with independently varied image heights.

## Corner radius

| Element | Radius |
| --- | --- |
| Action pills | 9999px (pill) |
| Floating navigation | 34px |
| Process cards | 7px |
| FAQ rows | 8px |
| Proof badge | 99px |
| FAQ plus control | 100px |

## Surfaces and depth

### Surfaces

#### Charcoal canvas · level 0

**Use:** All ordinary marketing content.

**CSS:** `background: #141414`

**Observed:** A continuous flat dark field with no texture or section divider lines.

**Transfer:** Let spacing and media, rather than alternating panels, separate chapters.

#### Low-lift card · level 1

**Use:** Process cards and compact grouped explanations.

**CSS:** `background: rgba(255, 255, 255, 0.05); border-radius: 7px; box-shadow: none`

**Observed:** The illustration occupies the top portion and receives an additional translucent neutral wash.

**Transfer:** Use subdued tonal separation rather than outlines or floating shadows.

#### Floating glass · level 2

**Use:** Navigation above text and media.

**CSS:** `background: rgba(255, 255, 255, 0.1); backdrop-filter: blur(25px); border-radius: 34px`

**Observed:** The gray capsule becomes softly colored when vivid imagery passes behind it.

**Transfer:** Keep the blur limited to navigation rather than turning all cards into glass.

#### Sunset band · level 0

**Use:** Signature full-width conversion surface.

**CSS:** `background-image: linear-gradient(#fc6435 0%, #ffb638 63.0001%, #80bdff 100%); padding: 100px 0`

**Observed:** Smooth vertical orange-to-gold-to-blue color fills the entire 388px band; black text sits directly on it.

**Transfer:** Retain this warm top and cool bottom with no texture, vignette or inset panel.

#### Footer floor · level 0

**Use:** Site ending.

**CSS:** `background: #0f0f0f; padding: 50px 20px 40px`

**Observed:** Darker than the main canvas, flat and unbordered.

**Transfer:** Close with a compact utility area instead of another display-sized statement.

## Components

### Floating navigation

**Use:** Persistent global wayfinding.

**CSS:** `width: 640px; height: 58px; padding: 8px 8px 8px 24px; border-radius: 34px; background: rgba(255, 255, 255, 0.1); backdrop-filter: blur(25px); box-sizing: border-box`

**Text style:** `compact-body` — Geist 500 · 16px/22px · tracking -0.03em

**Observed:** Fixed at the top center with a 24px offset. A small square color mark and white name anchor the left; three muted links and Primary button sit on the right. Link gaps are 20px.

**Transfer:** Use a short brand name and three high-value destinations.

### Primary button

**Use:** Default action on the dark canvas and inside navigation.

**CSS:** `background: #ffffff; color: #000000; border-radius: 9999px; padding: 8px 16px; height: 42px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — Geist 500 · 18px/26px · tracking -0.02em

**Observed:** Text-only pill, about 136px wide for the example action. The same treatment repeats in the opening and compact collection header.

### Closing button

**Use:** Conversion on the Sunset band.

**CSS:** `background: #000000; color: #ffffff; border-radius: 9999px; padding: 8px 16px; height: 42px; display: inline-flex; align-items: center; justify-content: center; box-sizing: border-box`

**Text style:** `action` — Geist 500 · 18px/26px · tracking -0.02em

**Observed:** A direct inverse of Primary button, about 139px wide for this label.

### Text link

**Use:** Navigation links and footer destinations.

**CSS:** `color: rgba(255, 255, 255, 0.6); text-decoration: none`

**Text style:** `compact-body` — Geist 500 · 16px/22px · tracking -0.03em

**Observed:** No icon or underline. Footer links use the small recipe instead.

**States:** Declared: hover color #ffffff and no text-decoration; focus-visible styling is unspecified.

### Proof badge

**Use:** Compact quantified reassurance above the opening promise.

**CSS:** `background: rgba(252, 100, 53, 0.1); color: #fc6338; padding: 2px 14px 2px 4px; border-radius: 99px; height: 26px; gap: 7px; display: inline-flex; align-items: center; box-sizing: border-box`

**Text style:** `proof` — Geist 600 · 14px/22px · tracking -0.02em

**Observed:** An orange inner count capsule leads, with a tiny white status dot and white numeral. The adjacent orange descriptor stays on the tinted outer capsule.

**Transfer:** Use a substantiated short metric; keep the badge subordinate to the headline.

### Process card

**Use:** Explain a short workflow through miniature interface metaphors.

**CSS:** `width: 260px; height: 296px; background: rgba(255, 255, 255, 0.05); border-radius: 7px; overflow: hidden`

**Text style:** `card-title` — Geist 500 · 18px/24px · tracking -0.03em

**Observed:** A 160px-tall illustration stage above a 136px text region. The text region has 25px top, 12px side and 16px bottom padding; a short white title precedes centered muted compact-body copy with a 5px gap.

**Transfer:** Pair each step with a simple grayscale mechanism, not a decorative full-color illustration.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `width: 500px; height: 46px; padding: 10px 14px 12px 18px; background: #202020; border-radius: 8px; box-sizing: border-box`

**Text style:** `body` — Geist 500 · 16px/22px · tracking -0.02em

**Observed:** White question left, circular plus control right. Eight rows are separated by 5px. The 28px control is #3a3a3a with a white plus made from 12px × 2px bars.

**Transfer:** Keep questions short; allow content-driven row height when a question must wrap.

### Footer columns

**Use:** Site-wide ending beneath the conversion band.

**CSS:** `max-width: 1240px; display: flex; gap: 24px; align-items: flex-start`

**Text style:** `small` — Geist 500 · 14px/20px · tracking -0.02em

**Observed:** Brand name, a muted two-line description and copyright form the broad left column; three compact destination groups sit right. Headings are white; links are soft white. No newsletter form or extra closing button.

### Editorial byline

**Only for:** company or editorial pages

**Use:** A human signature beneath an editorial opening.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 10px; padding-top: 10px`

**Text style:** `byline` — Geist 500 · 14px/16px · tracking -0.02em

**Observed:** A small circular pink-orange gradient avatar above a white name and muted role; the avatar is 40px in diameter.

**Transfer:** Use a restrained circular author image or abstract avatar rather than a large team portrait.

## Imagery and graphics

### Outcome ribbon

**Use:** Primary visual proof in the first screen.

**Observed:** A full-width clipped row of tall creative-work images begins around 600px down the opening. Roughly five complete 260px-wide tiles plus clipped neighbors show interfaces, packaging in a person's hand, identity posters and a landscape with an overlaid mark. Saturation remains native to each project. Small maker/verification chips sit near the lower edge.

**Transfer:** Use original finished outcomes, product-in-context photos or carefully art-directed output studies; preserve the portrait framing and edge clipping rather than substituting generic abstract wallpaper.

**Build:** Make a horizontal flex strip with 260px portrait image frames and about 20px gutters, overflow hidden at the viewport edges. Fill each frame with object-fit: cover. Place a compact translucent gray maker chip and a circular symbol near the lower edge.

### Perspective identity ring

**Use:** Signature sculptural proof around a central value statement.

**Observed:** Rounded square identity tiles form a tilted, hollow elliptical ring on charcoal. White abstract marks on black alternate with saturated blue, green, orange and gradient faces. Front tiles are broad and back or side tiles foreshorten sharply; the central heading is 470px wide with a 350px support measure.

**Transfer:** Include this dimensional family-of-outputs device on a new landing page. Replace identity marks with original output symbols or feature glyphs; a static perspective composition is an acceptable minimum.

**Build:** Arrange approximately 12 rounded square planes around a horizontal ellipse in a 3D CSS container with perspective. Use roughly 160px square back faces and wider projected front faces, an overall width around 850px, and a dark center opening for the heading. Rotate each face toward its tangent, scale nearer faces up, and use flat-color or original gradient artwork with white symbols. Do not add a pedestal, metallic extrusion or glow.

### Monochrome process miniatures

**Use:** Top stages of Process card.

**Observed:** Neutral gray stages contain a three-node progress line, three verification cards and a short sent/booked confirmation pill. They are intentionally diagrammatic, not detailed application screenshots.

**Transfer:** Reduce each process to one recognizable interface event in white and layered gray.

**Build:** Use a 260px × 160px stage with rgba(246,246,246,0.1) over the card. Center either three 32px circular steps joined by thin bars, three vertical gray cards with a white verification emblem, or a compact pale status pill. Keep these graphics free of accent colors.

### Masonry work wall

**Only for:** work collection pages

**Use:** Dense browsing proof after a compact centered header.

**Observed:** Five 276px columns at desktop, 10px gutters and 10px outer margins. Images keep varied portrait, square and landscape proportions; bright identity compositions, physical print, photography and interface mockups alternate without descriptive card bodies. Column endings are uneven.

**Transfer:** Use varied real outcomes at their natural ratios; retain a dense editorial wall rather than regularizing everything into identical cards.

### Icons

**Observed:** Sparse utility marks: white plus bars inside 28px gray circles, small rounded checkmarks, verification seals and small circular maker marks. Most visual complexity belongs to the work, not to an icon system.

**Transfer:** Use simple white/black checks and plus signs at utility scale. Avoid colorful feature-icon badges alongside every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Centered promise with outcome ribbon

**Observed:** Back to front: continuous Charcoal canvas, centered text stack, full-width Outcome ribbon, then Floating navigation fixed above all. The opening has 250px top padding. Proof badge precedes a two-line 64px display headline in a 725px measure, about half the viewport width; support narrows to 400px and the Primary button follows, with 20px stack gaps. Within the first 900px the entire promise, support and action are visible, plus the upper 300px of a vivid portrait ribbon beginning around 600px. The ribbon continues below the fold; brand proof is later. Text remains white, not gradient-filled.

**Transfer:** Lead with one audience-specific outcome and a concise verified metric. Create five original outcome studies when finished media is scarce. Collection pages use the 42px heading and a small maker chip with 204px top padding before a dense work wall; editorial pages use a sentence-case eyebrow, 42px heading, wider support and Editorial byline instead of a conversion-first ribbon.

**Avoid:** Do not replace the centered promise with a left/right SaaS split or place a giant browser dashboard behind the text.

**Text style:** `display` — Geist 500 · 64px/0.95 · tracking -0.02em

### Restrained brand proof

**Observed:** A centered muted compact-body label introduces a compact row of four approximately 120px-wide brand marks inside the Main container. The section has 150px top and 64px bottom padding.

**Transfer:** Use a small number of credible proof marks or concise textual credentials, leaving room around the group.

### Workflow triptych

**Observed:** A centered 42px heading in Heading measure, followed after 60px by the Process row of three Process cards. Section padding is 50px top and 25px bottom.

**Transfer:** Explain entry, selection and result in brief steps; match the monochrome mechanism to the new product's actual workflow.

**Text style:** `heading` — Geist 500 · 42px/1 · tracking -0.02em

### Dimensional proof statement

**Observed:** Perspective identity ring surrounds a centered heading and short support on the uninterrupted dark field. The overall chapter is 975px tall, giving the sculpture more space than its text.

**Transfer:** Use this as a memorable proof or capability chapter, preserving the hollow center and dimensional arrangement rather than copying specific logos.

**Text style:** `heading` — Geist 500 · 42px/1 · tracking -0.02em

### Narrow question stack

**Observed:** A centered Heading measure title sits 60px above the 500px-wide FAQ row stack. The section finishes with 120px bottom padding.

**Transfer:** Address practical hesitation with plain questions, leaving the artwork chapter visually separate.

**Text style:** `heading` — Geist 500 · 42px/1 · tracking -0.02em

### Sunset invitation and utility ending

**Observed:** Sunset band is full width and 388px tall, with 100px top and bottom padding. A black two-line heading occupies a 480px measure, support follows after 16px and Closing button after 24px. Footer floor follows immediately, containing Footer columns and a compact brand signature.

**Transfer:** Use the bright band as the decisive invitation, then reduce visual intensity for useful destinations. Keep this signature color release even on a shorter page.

**Text style:** `heading` — Geist 500 · 42px/1 · tracking -0.02em

### Single-column editorial explanation

**Only for:** company or editorial pages

**Observed:** After a centered editorial opening, a 500px-wide left-aligned column carries 16px/22px prose in soft white with 20px paragraph gaps. Short white inline subheads use the same size and weight instead of introducing another large type scale. Section padding is 50px 20px 120px.

**Transfer:** Use for mission, approach or methodology pages; explain the product in connected prose without adding decorative cards.

**Text style:** `body` — Geist 500 · 16px/22px · tracking -0.02em

### Compact collection opening and image wall

**Only for:** work collection pages

**Observed:** A small maker chip, centered 42px two-line heading, one support line and Primary button lead into Masonry work wall. The header is 492px tall; the wall follows flush across nearly the full viewport and ends with 120px bottom padding before the shared conversion band.

**Transfer:** Keep collection browsing image-first, with the centered header acting as a concise introduction rather than a second large landing hero.

**Text style:** `heading` — Geist 500 · 42px/1 · tracking -0.02em

## Page flow

**Storyline:** Clear promise → visible outcomes → concise mechanism or explanation → reassurance → bright invitation → compact utility ending.

### Convert a first-time visitor with visual confidence and a short explanation

1. **Promise** — Centered headline, small quantified badge, concise support and one action above a vivid output ribbon.
2. **Social proof** — A restrained line of brand marks.
3. **Product explanation** — Three small monochrome process cards.
4. **Capability proof** — Perspective identity ring around a centered value statement.
5. **Objection handling** — Narrow eight-row question stack.
6. **Closing call** — Sunset invitation and compact multi-column footer.

**Transfer:** Use visual outcomes to earn attention, then explain just enough to make one action feel low-risk.

### Let visitors judge quality through a dense visual collection

1. **Orientation** — Compact centered headline and single action under a maker chip.
2. **Product proof** — Five-column mixed-ratio masonry work wall.
3. **Closing call** — Shared gradient invitation followed by utility footer.

**Transfer:** Lead quickly into the work; avoid repeating a full explanatory landing-page narrative.

### Explain intent and suitability in a more personal, editorial format

1. **Purpose** — Small eyebrow, centered heading and support, then a compact author signature.
2. **Explanation** — Narrow prose column with same-size white subheads and muted paragraphs.
3. **Closing call** — Shared gradient invitation and utility footer.

**Transfer:** Keep the global visual language but trade the art-heavy opening for an accountable voice and readable prose.

## Writing

Direct, conversational and lightly opinionated. The language respects the reader's taste while making a complicated choice feel easy, specific and human.

**Do not copy:** Do not reuse Palette's name, logo, studio identities, founder name, project artwork, match counts, customer claims or exact promises. Source quotations below illustrate voice only.

- **Addressing the reader:** Address the reader as you and your; the service speaks as we when explaining what happens next.
- **Rhythm:** Headlines are usually short statements or questions, often breaking into two lines. Support is one sentence; process descriptions are two short sentences. Editorial pages expand into connected paragraphs without changing the conversational tone.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the desired result and the reader's context. | 6–10 words | “Find the best studio for your business” |
| Section lead | Contrast the frustrating activity with the useful outcome. | 4–8 words | “Stop browsing, get matched” |
| Support | State the reader's small input and the service's resulting work. | 10–20 words | “Answer a few questions and we’ll instantly match you with the perfect creative for your project.” |
| Process description | Acknowledge a concern, then make the next step concrete. | Two short sentences | “Describe what feels off. Three minutes and we know exactly who can solve it.” |
| Action | Verb-led outcome or low-commitment entry. | 2–3 words | “Get Matched”<br>“Start for Free” |
| Closing call | A readiness question followed by reassurance that the service will carry the load. | 5–8 words plus one support sentence | “Ready to find your match?”<br>“Tell us about your project and we’ll handle the rest.” |
| FAQ question | Use the reader's plain-language hesitation. | 5–10 words | “What if I don't know what I need?” |

**Words and phrasing to use:** right fit; get started; your project; focused; specific; verified; ready; handle the rest

**Avoid:** revolutionary ecosystem; synergize; world-class solutions; unlock limitless potential; excessive technical jargon

**Rules:**

- Prefer the practical result over an abstract category claim.
- Use a small concrete action to make the promise believable.
- Allow occasional blunt contrasts such as less searching versus better fit.
- Make trust claims specific and supportable; keep adjectives out of action labels.

## Do's and Don'ts

### Do

- Keep the default opening at 64px/0.95 and section leads at 42px/1, both weight 500.
- Keep primary support to a 400px measure so it reads as a compact two-line block.
- Use 20px gutters for the three-card process row and 10px gutters for the denser image wall.
- Retain 25px backdrop blur on the fixed navigation so passing artwork subtly colors it.
- Give the signature closing band 100px vertical padding and black text.
- Keep process illustrations grayscale so the work images own the saturated color.
- Use 5px separation between FAQ rows and retain their 28px plus controls.
- End with small 14px utility text rather than another oversized hero.

### Don't

- Do not increase all body copy to 18px; 16px/22px is the compact reading voice.
- Do not use bold 700 headings; the hierarchy relies on medium weight and short line breaks.
- Do not add hairline borders around every dark card; tonal fills provide separation.
- Do not turn ordinary actions orange; white and black pills maintain the contrast system.
- Do not flatten every corner to one radius: 7px cards, 8px question rows and 34px navigation serve distinct roles.
- Do not use neon glows, grain or mesh blobs behind the dark sections; their field is flat.
- Do not desaturate the portfolio media to match the interface; native project colors create the contrast.
- Do not enlarge the footer into a multi-screen destination; its painted band is only about 222px tall at desktop.

## Motion and responsive

### Motion

**Observed:**

- Navigation remains fixed through scrolling.
- Text-link hover changes soft white to white without an underline.
- No action or surface transition durations are specified.

**Transfer:**

- Keep the perspective ring and outcome ribbon visually complete in a still state; their spatial arrangement carries the identity even without motion.

**Unknown:**

- Timing, easing and autoplay behavior of the image ribbon, identity ring, count and miniature process states are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 810px and 1200px.

**Transfer:**

- On narrow screens, preserve centered short-line headings and the edge-clipped output ribbon; reduce the number of simultaneously visible tiles rather than shrinking them into thumbnails.
- As an adaptation, stack the process cards and reduce masonry columns while preserving 10px image gutters and natural image ratios.
- Keep the floating navigation compact within side gutters and retain the conversion pill as its strongest element.

**Unknown:**

- Exact small-screen type sizes, navigation collapse behavior, column counts and section padding are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
