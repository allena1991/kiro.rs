# Gemini — horizons and hard numbers

## Overview

An expansive, image-led technology style that sets crisp grotesk typography and compact controls against dreamlike skies, real-world scenes and isolated product interfaces. White explanatory space gives way to cinematic color and a substantial black ending, with denser, glowing dark presentations for institutional products. It suits ambitious platforms that need both an accessible consumer promise and a credible technical story.

### Essentials

- A vast world surrounds a small, usable product: the default opening combines a full-bleed atmospheric scene, a 72px/1.04 medium headline and a white 400px-wide working panel. Include an atmospheric world somewhere on every new landing page; a textured sky and a simplified product panel are the fallback when bespoke illustration is unavailable.
- Headlines feel conversational rather than poster-bold: Geist 500, -1.6px tracking at both 72px and 42px, with compact line heights of 1.04 and 1.08. Institutional pages instead use a centered 48px/1 bold promise.
- Controls are deliberately smaller than the scenery: primary actions are 40px-high black pills, with 14px/20px semibold labels and 16px horizontal padding; a 60px translucent navigation bar stays above the scene.
- Color belongs to worlds, not every interface surface: ordinary explanatory sections remain white with near-black text, while imagery carries teal, peach and saturated photographic color. Institutional cyan is limited to actions and highlighted phrases; the orange 580px band belongs to the consumer launch variant.
- Proof is unboxed and widely spaced: a short two-line lead precedes four large numeric facts on white, using a 64px separation between lead and metrics. Carry this bare-number proof device into the new product rather than turning every fact into a card.
- The page resolves into a black directory, not a giant slogan: use a 1200px-wide footer with a newsletter pill, four narrow link columns, subdued 14px text and a ruled utility strip. Image-led cross-sell tiles or editorial cards can make the transition into that ending.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-black` | background, action, text | Footer, late-page dark bands and primary conversion pills. |
| Near-black ink | `#010304` | `--color-ink` | text, background, action | Primary text on white and the dark app-download action; also the institutional opening canvas. |
| Newsletter charcoal | `#1a1a1a` | `--color-newsletter-fill` | surface | Visible white-at-10% fill over the black newsletter area. |
| Charcoal rule | `#343536` | `--color-dark-rule` | border, surface | FAQ separators and dark button hover treatment. |
| Body gray | `#4d4f4f` | `--color-body-muted` | text | Supporting paragraphs and light-theme answers. |
| Heading gray | `#676868` | `--color-heading-muted` | text, surface | Section labels on the default light canvas; institutional category headings and selected product tabs. |
| Directory gray | `#999a9b` | `--color-muted` | text | Footer links and small supporting details on black. |
| Light rule | `#e6e6e6` | `--color-light-rule` | border | Faint panel edges on white; also the visible result of black at 10% over white. |
| Soft gray | `#f7f7f7` | `--color-soft-canvas` | background, surface | Alternate explanatory bands and backgrounds for white cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text, action | Default explanatory canvas and white panels; inverse text and buttons on dark scenes. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| consumer launch pages | Launch orange | `#ff4809` | `--color-orange` | background, accent | A full-width consumer launch band; surrounding explanation remains neutral. |
| institutional product pages | Electric cyan | `#26ddf9` | `--color-cyan` | text, action, accent, border | Institutional CTA fill, emphasized product captions and answer-word headings; not the default consumer action color. |
| security-focused institutional pages | Deep gold | `#dead30` | `--color-gold` | text | Bottom stop of security-themed gradient text. |
| execution-focused institutional pages | Deep green | `#0db751` | `--color-green` | text | Bottom stop of execution-themed gradient text. |
| execution-focused institutional pages | Fresh green | `#48ef6d` | `--color-green-light` | text | Top stop of execution-themed gradient text. |
| security-focused institutional pages | Pale gold | `#fae9bc` | `--color-gold-light` | text | Top stop of security-themed gradient text. |
| institutional product pages | Medium gray | `#808181` | `--color-secondary` | text | Institutional explanatory copy and compact card paragraphs. |

## Typography

- **Geist** — All marketing headings, body text, navigation and actions. Contemporary grotesk with open, legible small text and tightly fitted medium-weight display letters. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Geist | 500 | 72px | 1.04 | -0.0222em | Default image-led opening promise, set in white across two or three lines. |
| heading | Geist | 500 | 42px | 1.08 | -0.038em | Primary light-page section headings and image-band promises. |
| heading-small | Geist | 500 | 32px | 1.16 | -0.05em | Short proof leads and image-tile titles. |
| section-label | Geist | 500 | 22px | 1.25 | -0.01em | Product-family label above a heading, or a short instructional subheading. |
| body | Geist | 400 | 16px | 1.4 | -0.01em | Default supporting explanation beside product imagery. |
| small | Geist | 500 | 14px | 1.4 | normal | Status labels, footer links and newsletter labels. |
| button | Geist | 600 | 14px | 20px | 0.025em | Compact primary and navigation actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| institutional FAQ and resource sections | faq-display | Geist | 600 | 80px | 0.95 | -0.04em | Oversized paired question-and-answer heading, the second phrase in cyan. |
| institutional product pages | institutional-heading | Geist | 700 | 60px | 1 | -0.044em | Centered gray category and related-product headings. |
| institutional product pages | institutional-product-heading | Geist | 600 | 60px | 1 | -0.044em | Related-product title and cyan editorial section heading. |
| institutional product pages | institutional-display | Geist | 700 | 48px | 1 | -0.055em | Centered two-line opening promise. |
| consumer launch openings | launch-support | Geist | 500 | 34px | 1.16 | -0.01em | Large translucent support line below a short product name. |
| institutional product pages | institutional-caption | Geist | 600 | 32px | 36px | -0.03em | Centered explanatory statements with color-gradient emphasis near a glowing product presentation. |
| institutional audience cards | audience-title | Geist | 600 | 32px | 36px | normal | Centered titles underneath isolated object illustrations. |
| institutional product pages | faq-question-dark | Geist | 500 | 24px | 32px | normal | Question rows on black. |
| consumer launch pages | launch-feature-heading | Geist | 400 | 24px | 28px | -0.021em | Restrained feature-row headings beside substantial product imagery. |
| institutional editorial grids | editorial-title | Geist | 600 | 22px | 26px | -0.0455em | Multiline article titles on white cards. |
| institutional product pages | feature-body | Geist | 500 | 20px | 28px | normal | White feature title flowing directly into gray explanation. |
| institutional product pages | faq-answer-dark | Geist | 400 | 16px | 1.15 | normal | Expanded answer paragraphs on black. |
| consumer launch pages | faq-question-light | Geist | 500 | 16px | 1.4 | -0.01em | Compact light-theme accordion labels. |
| institutional audience cards | audience-body | Geist | 500 | 14px | 20px | -0.01em | Dense centered paragraphs in audience cards. |
| consumer launch pages | launch-body | Geist | 400 | 14px | 20px | normal | Short feature descriptions and underlined text actions. |
| consumer launch pages | faq-answer-light | Geist | 400 | 14px | 1.4 | normal | Compact light-theme accordion answers. |

**Notes:**

- Display tracking stays at -1.6px across the default 32px, 42px and 72px sizes, so smaller display headings feel particularly tight. Do not replace this with one shared em tracking value.
- Use sentence case for promises, labels and actions. Institutional category titles can use title case; no mono or decorative display family is needed.
- The small default label is 14px, while section labels can be 22px. Preserve this distinction rather than treating every line above a heading as a tiny uppercase eyebrow.

## Layout

**Density:** Airy at the section scale, compact within controls and demonstrations; small text clusters sit inside very large visual fields.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Inline icon gaps and title-to-tile-support spacing. |
| 12px | Heading stacks, product-panel groups and feature copy stacks. |
| 16px | Button side padding and institutional card gutters. |
| 24px | Information-card padding and separation before actions. |
| 32px | Three-tile cross-sell gutters and institutional section side padding. |
| 40px | Footer group spacing and carousel top inset. |
| 64px | Proof lead-to-metrics gap, paired explanation-to-media gap and footer lead-column separation. |
| 84px | Desktop opening content top and bottom inset beneath navigation. |
| 100px | Dark cross-sell band top and bottom breathing room. |
| 128px | Major instructional heading top space and light FAQ vertical margins. |

### Containers and grids

- **marketing stage**: max width 1220px · side padding 104px. Centered content region; at 1440px the visible content aligns around 110px from either edge. The 104px inset belongs to the outer content-box wrapper, not a second inset inside a 1220px border-box.
- **footer container**: max width 1200px · side padding 80px. Wide newsletter-and-directory layout with a ruled utility row beneath.
- **instruction pair**: gap 64px. A roughly 330px text column beside a 565–576px-wide interface illustration, centered within the marketing stage.
- **cross-sell grid**: 3 columns · gap 32px. Three equal image-led squares, each 385px wide at desktop, on black.
- **institutional grid** (only for institutional product pages): max width 1126px · 3 columns · gap 16px · side padding 32px. Three roughly 364px audience or article cards.
- **faq column** (only for product detail pages): max width 784px · side padding 32px. Centered dark FAQ and download-resource content; the light consumer variant uses 800px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action pills | 9999px (pill) |
|  | product panels | 16px |
|  | information cards | 20px |
|  | cross-sell tiles | 12px |
| institutional product pages | institutional cards | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| information-card lift | `0px 8px 32px 0px rgba(0,0,0,0.08)` | White information cards on the horizontal rail. |
| hero-panel lift | `0px 16px 64px 0px rgba(0,0,0,0.08)` | The large white product panel over atmospheric artwork. |

### Surfaces

#### White canvas · level 0

**Use:** Default explanatory space.

**CSS:** `background: #ffffff; color: #010304`

**Observed:** Long, open sections let phones and interface illustrations stand on their own without a surrounding card.

**Transfer:** Use empty space to isolate one clear operation or benefit.

#### Soft canvas · level 0

**Use:** A neutral chapter break behind white cards or a closing product photograph.

**CSS:** `background: #f7f7f7`

#### Black ending · level 0

**Use:** Late-page cross-sell and shared footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** The black field continues between adjacent ending sections rather than rounding each band.

**Transfer:** Let the closing content form one continuous dark destination.

#### White product panel · level 1

**Use:** Tangible working proof over a cinematic world.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,0,0,0.1); border-radius: 16px; box-shadow: 0px 16px 64px 0px rgba(0,0,0,0.08)`

#### Dark product stage · level 0

**Only for:** institutional product pages

**Use:** Glowing screen demonstrations and technical proof.

**CSS:** `background: #010304; color: #ffffff`

**Observed:** A black field surrounds centered desktop interfaces; violet and cyan halos remain close to their edges.

**Transfer:** Keep the screen legible and the light local, not a page-wide neon gradient.

#### Security gradient text

**Only for:** security-focused institutional pages

**Use:** Emphasized technical statement.

**CSS:** `background-image: linear-gradient(#fae9bc 2.08%, #dead30 100%); background-clip: text; -webkit-text-fill-color: transparent`

#### Execution gradient text

**Only for:** execution-focused institutional pages

**Use:** Emphasized audience or capability statement.

**CSS:** `background-image: linear-gradient(#48ef6d 2.08%, #0db751 100%); background-clip: text; -webkit-text-fill-color: transparent`

#### Launch band

**Only for:** consumer launch pages

**Use:** A concentrated full-width color interruption.

**CSS:** `background: #ff4809; color: #ffffff`

**Observed:** The 580px band stages a desktop display between a left title and a short right explanation with a white pill.

**Transfer:** Use one self-contained launch chapter rather than coloring every feature row.

## Components

### Navigation bar

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; top: 0px; height: 60px; width: 100%; background: rgba(255,255,255,0.6); backdrop-filter: blur(12px); display: flex; align-items: center; justify-content: space-between; z-index: 100`

**Text style:** `small` — Geist 500 · 14px/1.4

**Observed:** Identity on the left, compact product links across the middle, sign-in and Primary button on the right. Default text is near-black; institutional and launch variants use white text over near-black at 60% opacity.

**Transfer:** Keep the center links short and the conversion cluster separate from the identity.

### Primary button

**Use:** Default conversion action on a light canvas.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 8px; height: 40px; padding: 0px 16px; background: #000000; color: #ffffff; border-radius: 9999px`

**Text style:** `button` — Geist 600 · 14px/20px · tracking 0.025em

**Observed:** Text-only compact pill; on dark navigation it reverses to white with black lettering.

**States:** Declared: hover background-color color-mix(in oklab,#000 70%,transparent); focus-visible outline-style none and a zero box-shadow.

**Transfer:** Let width follow a short action label rather than expanding to a promotional banner.

### Download button

**Use:** Opening action placed over atmospheric imagery.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 1px 24px; background: #010304; color: #ffffff; border-radius: 9999px`

**Text style:** `small` — Geist 500 · 14px/1.4

**Observed:** A wider pill using a medium 14px label rather than the tracked semibold navigation label.

**States:** Declared: hover background-color #343536; focus-visible outline-style none and a zero box-shadow; active background-color color-mix(in oklab,#000 90%,transparent).

### Working product panel

**Use:** Opening proof that the promise leads to a real interaction.

**CSS:** `display: flex; flex-direction: column; gap: 12px; max-width: 400px; padding: 12px; background: #ffffff; color: #010304; border: 1px solid rgba(0,0,0,0.1); border-radius: 16px; box-shadow: 0px 16px 64px 0px rgba(0,0,0,0.08); overflow: hidden`

**Observed:** Centered short task title, compact category navigation, concise context, a selection, a result summary and a full-width dark action. It occupies the right third of the opening, distinct from the wider headline.

**Transfer:** Show one credible end-to-end operation for the new product; simplify secondary controls without reducing the panel to an empty browser frame.

### Information rail card

**Use:** A horizontal stream of live-looking product proof below the opening.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 12px; width: 357px; padding: 24px; background: #ffffff; border-radius: 20px; box-shadow: 0px 8px 32px 0px rgba(0,0,0,0.08)`

**Text style:** `small` — Geist 500 · 14px/1.4

**Observed:** Short status and context at the top, a compact claim and outcome detail beneath. Cards are spaced by their padded wrappers and cut by the viewport edges; small round arrows sit below.

**Transfer:** Use fresh examples or useful summaries from the product, not repeated testimonial boxes.

### Newsletter field

**Use:** Low-key subscription inside the black footer.

**CSS:** `display: flex; align-items: center; height: 52px; width: 379px; padding: 6px; background: rgba(255,255,255,0.1); border-radius: 9999px`

**Text style:** `small` — Geist 500 · 14px/1.4

**Observed:** Label above, borderless input on the left, white rounded arrow-submit control inset at the right; small legal copy sits beneath.

**Transfer:** Keep the entire field visually subordinate to the page story, with one clear input.

### Footer directory

**Use:** Shared ending and broad site navigation.

**CSS:** `display: flex; justify-content: space-between; gap: 16px; color: #999a9b`

**Text style:** `small` — Geist 500 · 14px/1.4

**Observed:** Four narrow columns sit beside a wider newsletter column separated by 64px. Column headings are white, links gray; long labels wrap. A full-width fine rule separates locale, social icons and policy links below.

**Transfer:** Use the new site's real information architecture and preserve the contrast between wide subscription area and dense directory.

### Cross-sell tile

**Use:** Bridge from the main story into the black ending.

**CSS:** `position: relative; display: flex; flex-direction: column; justify-content: flex-end; width: 385px; height: 385px; padding: 24px; border-radius: 12px; overflow: hidden; color: #ffffff`

**Text style:** `heading-small` — Geist 500 · 32px/1.16 · tracking -0.05em

**Observed:** Full image backing, short benefit line above product name, and a 44px translucent circular arrow at lower right. Three equal tiles sit on the Black ending surface.

**Transfer:** Use distinct product or capability imagery; if bespoke media is unavailable, stage a meaningful product object with directional lighting rather than an empty colored square.

### Audience card

**Only for:** institutional product pages

**Use:** Explain who a complex product serves.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: space-between; width: 364px; padding: 48px 34px; background: #ffffff; border-radius: 16px; text-align: center`

**Text style:** `audience-title` — Geist 600 · 32px/36px

**Observed:** Small photoreal object floats above the title with ample headroom; the compact gray paragraph uses Audience-body. No border or prominent shadow.

**Transfer:** Choose one concrete object per audience and write a specific use case, not a generic persona name.

### Dark FAQ row

**Only for:** institutional product pages

**Use:** Technical or purchasing objection handling.

**CSS:** `max-width: 784px; min-height: 93px; border-bottom: 1px solid #343536; color: #ffffff`

**Text style:** `faq-question-dark` — Geist 500 · 24px/32px

**Observed:** Question at left with a white circled plus at right; collapsed rows are spacious. Expanded answer copy uses Faq-answer-dark with a 24px inset below the question.

**Transfer:** Use actual operational questions and keep the answer in the same ruled row.

### Editorial card

**Only for:** institutional editorial grids

**Use:** Offer deeper reading before the directory ending.

**CSS:** `display: flex; flex-direction: column; align-items: center; width: 364px; padding: 12px 12px 35px; background: #ffffff; color: #000000; border-radius: 16px`

**Text style:** `editorial-title` — Geist 600 · 22px/26px · tracking -0.0455em

**Observed:** A 340px-wide image sits at the top, followed by a tightly set multiline headline. Gray category and date sit near the base, leaving a large open middle. Three cards form a row.

**Transfer:** Use genuine editorial content with varied thumbnail art, while keeping the card skeleton consistent.

## Imagery and graphics

### Atmospheric world

**Use:** Signature first impression and a later full-width invitation.

**Observed:** Grainy painterly clouds in peach, dusty pink and cream cross a muted teal sky around a pale moon. A later scene widens into rose-colored canyon walls with a person at a desktop at the lower center. The world fills the band; white headings remain crisp and the product panel stays photographically sharp.

**Transfer:** Create an expansive world around the new product's promise: a believable horizon, warm side light and cool atmospheric distance. The minimum version is a textured sky with layered cloud silhouettes and a clear interface panel, not a generic smooth mesh gradient.

**Build:** Use an edge-to-edge SVG scene with a cool teal base, several irregular cloud paths in peach and dusty coral, and a pale circular moon partly hidden behind them. Layer distant cloud shapes at reduced opacity, add fine feTurbulence grain through a low-opacity overlay, and keep broad low-detail regions behind the headline. A closing illustration adds angular warm rock silhouettes at the lower edges and a small dark product-use silhouette near the bottom. Match the soft grain and warm/cool balance; exact pigment values are not essential.

### Isolated product demonstrations

**Use:** Large white-space product proof and short instructional chapters.

**Observed:** Upright dark phone shells stand alone on white; instructional images show simplified white cards against muted pale-green or gray backings. Text is a narrow column next to a much larger visual. Device hardware remains realistic and screens remain sharply legible.

**Transfer:** Show a single meaningful task per visual. Use a faithful interface inside a device, or a simplified panel with the same contrast and breathing room.

### Cinematic category scene

**Only for:** consumer category storytelling

**Use:** An immersive interactive chapter.

**Observed:** Full-bleed sports action and concert-stage photography change the mood dramatically: close-cropped bodies and grass, or saturated red beams against a black auditorium. Paired white statements sit at the sides of a small central translucent task card; category pills float below.

**Transfer:** Choose subject matter relevant to the product's uses. Preserve full-bleed scale, darkened text-safe zones and restrained glass controls; the new subject need not be sports or performance.

### Local screen halo

**Only for:** institutional product demonstrations

**Use:** Give a desktop interface physical presence on black.

**Observed:** A centered screen roughly 720–740px wide is surrounded by soft violet light above and cyan light below. A darkened reflection or lower screen transition merges it back into black. Captions sit close beneath and combine white with cyan.

**Transfer:** Use a high-fidelity screen and localized light; the minimum is a rounded screenshot frame with a subtle cyan-violet halo and a soft black fade below.

**Build:** Place two blurred elliptical gradients behind the screen: a wide violet rgba(90,60,180,0.25) glow near its top and a smaller cyan rgba(38,221,249,0.25) glow below its center. Blur by about 50px as design guidance. Keep the glow within roughly one screen-width; use a black-to-transparent overlay to fade the lower reflection. Do not place a hard luminous border around the whole section.

### Object miniatures

**Only for:** institutional audience cards

**Use:** Make abstract audiences concrete.

**Observed:** A classical building, leather briefcase, office chair and modern towers are small, realistic isolated objects on white, with soft contact shadows or reflections. They sit above large centered headings rather than filling the card.

**Transfer:** Select familiar, materially believable objects for the new audience types. Preserve small scale and neutral lighting instead of substituting flat colorful icon badges.

### Launch product collage

**Only for:** consumer launch pages

**Use:** Bolder product-name opening and colored launch chapter.

**Observed:** An oversized upright phone is clipped by the lower edge of a green hero with a red-and-green rectangular market mosaic underneath. Feature rows mix warm lifestyle phone photography, orange-backed device images and black transaction screens. A later orange band centers a desktop monitor. The final light band uses a close-up hand holding a red-screen phone, greatly enlarged on the left.

**Transfer:** Give a launch one strong product object and a compact geometric field; keep text outside the busiest region. For the ending, a close hand or tool photograph should dwarf the short conversion copy.

**Build:** Construct the lower hero field as a flat SVG treemap of differently sized rectangles in green, mint, coral and red, without gutters. Add faint tiny directional triangles or product-relevant marks inside a few cells. Back the upper text area with a green vertical tonal shift, then overlay a realistic phone on the right that crosses both zones. Keep these colors inside the launch illustration rather than extending them to body text.

### Icons

**Observed:** Utility and social icons are monochrome. Common controls use 16px or 20px marks; tile arrows use 24px glyphs inside 44px circles; dark FAQ expanders are white circled plus signs. Institutional feature illustrations can use thin gold or green linework.

**Transfer:** Use simple familiar silhouettes or clean thin outlines at the same scale. Keep decorative objects separate from functional icons.

## Section recipes

How recurring sections are built.

### First screen: Atmospheric split opening

**Observed:** A 60px fixed Navigation bar overlays a full-width cloud world. The opening occupies 803px of the first 900px: a left headline block about three-fifths of the content width is balanced by the 400px-wide, 575px-tall Working product panel on the right. The content stage has 84px of top and bottom breathing room below the navigation, with the left headline group beginning lower than the panel. Back-to-front layers are the atmospheric world, sharp white headline and small status line, black Download button, then the raised white panel. The 72px medium headline spans three lines; a tiny live-status dot and 14px label replace a paragraph-length support line. All actions and the full panel are visible before 803px; the top of the horizontal proof rail appears by 900px, while the main white explanatory heading is below the fold.

**Transfer:** Lead with a short benefit that can hold two or three strong lines, a textured aspirational world, and one real product operation. If no full interaction is available, build a simplified but credible task-and-result panel. Institutional pages open differently: centered 48px bold copy on near-black, cyan 56px action, gradient support statement and a glowing desktop interface starting above the fold. Consumer launches can use the same 72px display size with a large phone and geometric color backing.

**Avoid:** Do not shrink the world into a small thumbnail, center everything into a generic SaaS stack, or make the white panel wider than the promise. Do not add a long body paragraph to the default first screen.

**Text style:** `display` — Geist 500 · 72px/1.04 · tracking -0.0222em

### Open heading pair

**Observed:** On White canvas, a centered 22px Section-label sits 12px above a 42px Heading, or the headline comes first with a 24px gap to its support line. A compact Primary button sits below. The instructional heading begins with 128px of top space.

**Transfer:** Use this for a clear change of subject or a simple promise before a demonstration; keep the line lengths short.

**Text style:** `heading` — Geist 500 · 42px/1.08 · tracking -0.038em

### Bare metric proof

**Observed:** A short two-line 32px proof lead is left aligned above four evenly distributed unboxed statistics. A 64px gap separates lead and numeric row; the section has 64px top and 128px bottom padding. Numerals are visually much larger than the lead, with concise labels immediately beneath.

**Transfer:** Use a small set of verifiable facts, keeping numerals visually around 56px at desktop and labels secondary. A static numeric row can carry the same identity as animated counters.

**Text style:** `heading-small` — Geist 500 · 32px/1.16 · tracking -0.05em

### Instruction beside product

**Observed:** White canvas holds a roughly 330px text column beside a 565–576px interface illustration with a 64px gap. A 22px title, 16px supporting paragraph and compact action form a tight vertical group. Product steps change within a spacious scrolling chapter.

**Transfer:** Break a workflow into understandable moments; maintain a fixed visual scale between steps rather than mixing unrelated card layouts.

**Text style:** `section-label` — Geist 500 · 22px/1.25 · tracking -0.01em

### Institutional capability chapter

**Observed:** Dark product stage carries a centered Local screen halo and a 32px semibold caption mixing white and cyan. A subsequent row of three unboxed feature explanations uses small line illustrations, white 20px titles and gray copy. The story then changes to Soft canvas with 60px gray category headings and Audience cards.

**Transfer:** For a high-trust technical product, pair one legible demonstration with operational explanations, then translate capability into audience relevance. Keep the gold and green gradient statements specific to the relevant theme.

**Text style:** `institutional-caption` — Geist 600 · 32px/36px · tracking -0.03em

### Related product comparison

**Observed:** A centered institutional category heading and pill tabs precede a split row: 60px product title and short paragraph at left, realistic laptop at right. A three-column feature summary sits below, all on Soft canvas.

**Transfer:** Use tabs to compare genuinely adjacent offerings without duplicating the main product story.

**Text style:** `institutional-product-heading` — Geist 600 · 60px/1 · tracking -0.044em

### Two FAQ moods

**Observed:** Institutional objection handling uses Black ending, an 80px white-and-cyan paired heading and Dark FAQ rows in a 784px column. The consumer launch variant uses White canvas, a 42px heading and an 800px column of 57px compact rows with 16px questions and chevrons. Answers expand within their rules rather than floating as cards.

**Transfer:** Match the FAQ mood to the page type; preserve the typography and density of each variant rather than blending them.

### Editorial and download ending

**Observed:** Institutional pages continue on black after FAQs. One version adds a ruled download resource with an outlined pill. A cyan 60px section heading and white support line introduce three Editorial cards before the shared directory.

**Transfer:** Offer a useful deeper-reading or downloadable artifact when the purchase requires research; retain the bright white card contrast against black.

### Image invitation into directory

**Observed:** The default late-page invitation is a 600px full-width atmospheric scene with centered white Section-label, 42px Heading and black pill above the product-use subject. A three-column Cross-sell tile band follows on black with 100px vertical breathing room, flowing into Footer directory. The launch variant instead uses an 840px light closing band: a monumental hand-and-phone photograph on the left and 42px conversion heading, paragraph and black sign-up pill on the right, then a narrow black disclosure band and the directory.

**Transfer:** Give the closing action its own memorable visual world or enlarged physical product, then resolve into the continuous black directory. Choose the variant appropriate to the product; the exact preceding section order can change.

## Page flow

**Storyline:** Promise and working proof → product demonstration → confidence and relevance → deeper capabilities or workflow → objection handling or adjacent offers → visual invitation and substantial directory.

### Broad consumer platform introduction

1. **Promise** — Atmospheric split opening with an actionable product panel.
2. **Live proof** — Edge-clipped horizontal information rail.
3. **Product demonstration** — Centered promise followed by isolated phone presentations.
4. **Quantified proof** — Bare four-metric row with a brief trust lead.
5. **Use-case immersion** — Full-bleed category photography with glass controls.
6. **Workflow education** — Heading pair followed by paired explanation and interface steps.
7. **Closing invitation** — Painterly infrastructure scene and image-led cross-sell tiles.
8. **Directory** — Black newsletter, four link columns and ruled utilities.

**Transfer:** For a broad platform, alternate immersive worlds with neutral demonstrations so variety does not become visual noise.

### Security-oriented institutional product explanation

1. **Promise** — Centered dark opening with cyan action and gold technical statement.
2. **Product demonstration** — Glowing desktop screens and cyan captions.
3. **Operational proof** — Three unboxed governance and control explanations.
4. **Audience relevance** — Light gray chapter with three object-led audience cards.
5. **Adjacent capability** — Tabbed laptop presentation and feature summaries.
6. **Objection handling** — Dark FAQ with oversized paired heading.
7. **Deeper research** — Download resource followed by bright editorial cards on black.
8. **Directory** — Shared black newsletter and navigation ending.

**Transfer:** Make security concrete through operations and verifiable controls, then provide research depth rather than relying on grand trust language.

### Execution-oriented institutional product explanation

1. **Promise** — Centered white promise, cyan action, contact link and green gradient statement.
2. **Product demonstration** — Glowing desktop interface and cyan capability caption.
3. **Operational proof** — Three icon-led feature explanations.
4. **Audience relevance** — Light chapter of small object-led audience cards.
5. **Adjacent capability** — Tabbed related-product laptop and three feature summaries.
6. **Objection handling** — Black ruled FAQ under a white-and-cyan heading.
7. **Deeper research** — Three white editorial cards on black.
8. **Directory** — Shared newsletter and navigation ending.

**Transfer:** Use the institutional structure for products where permissions, integration and operational detail matter; tailor the proof and questions to the buyer.

### Focused consumer product launch

1. **Promise** — Short product-name display on green, oversized phone and geometric mosaic.
2. **Capability chapters** — Three restrained text-and-image rows on white.
3. **Platform context** — Orange band with central monitor and short flanking copy.
4. **Objection handling** — Compact white FAQ with eleven ruled questions.
5. **Closing call** — Large hand-and-phone photograph and concise sign-up copy.
6. **Disclosure and directory** — Small risk text on black, then the shared footer.

**Transfer:** Keep launch copy economical and let highly specific product images explain the offer; the bright opening and band remain scoped to launches.

## Writing

Confident and plainspoken, with aspirational consumer promises grounded by concrete product actions. Institutional copy becomes more operational and compliance-aware without adopting a different personality.

**Do not copy:** Do not reuse Gemini names, logos, proprietary artwork, product claims, supported-asset counts, dates, performance statistics, yields, regulatory assertions or customer and partner names. Source phrases are tonal examples only; replace claims with verified facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader through imperative verbs and occasional you/your. Name the product when explaining a mechanism; use we sparingly.
- **Rhythm:** Consumer headlines are typically short promises or two clipped sentences; supporting lines explain one benefit. Institutional headlines can be longer, with dense but concrete supporting paragraphs. Actions are brief and literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A benefit stated plainly, sometimes followed by a second sentence that explains immediacy or personalization. | 4–9 words for consumer promises; up to 14 for institutional promises. | “Smarter predictions. Personalized in real time.”<br>“Execute trades in seconds with advanced features for institutions.” |
| Section promise | An active verb and a broad benefit, with no ornamental tagline. | 4–7 words. | “Access the power of markets”<br>“Trade everything you believe in” |
| Supporting line | One sentence that locates the product's practical value. | 8–25 words for consumer explanations. | “One platform for predicting, investing, and earning.”<br>“Wall Street without the walls. Trade [Brand] Stocks without commission.” |
| Primary action | Verb plus the next step; explicit rather than clever. | 2–4 words. | “Download the app”<br>“Start your application” |
| Technical explanation | Name a capability, then state the concrete operation it enables. | One or two specific sentences. | “Give auditors view-only access into balances, transactions, and activity.” |

**Words and phrasing to use:** access; start; trade; your; tools; one platform; designed for; supported; secure; advanced

**Avoid:** revolutionary; game-changing; unleash; magical; guaranteed returns; excessive exclamation marks

**Rules:**

- Pair a broad promise with a visible operation or a specific explanation nearby.
- Keep action labels consistent with what happens next: download, sign up, explore or apply are distinct commitments.
- Use actual user questions for FAQs, including limits, access and fees where relevant.
- Use evidence-backed numbers for proof and carefully qualified language for trust or performance.

## Do's and Don'ts

### Do

- Keep ordinary section headings at 42px/1.08, weight 500 and -1.6px tracking.
- Balance the 72px opening promise with a tangible 400px product panel over a full-bleed world.
- Use 40px pill actions so the scenery, not the button, carries the visual scale.
- Keep information cards at 20px radius and raised product panels at 16px radius.
- Use 64px between proof lead and metrics, and between instructional copy and media.
- Carry the black field continuously through closing offers and the directory.
- Use the 784px dark FAQ column and 800px light FAQ column as separate page-type variants.
- Retain the contrast between small realistic object illustrations and substantial 32px card titles on institutional pages.

### Don't

- Do not apply 700 weight to the default 72px consumer promise; reserve the heavier treatment for institutional openings.
- Do not spread institutional cyan across ordinary consumer buttons or every heading.
- Do not turn the metric row into four bordered dashboard cards.
- Do not place broad drop shadows on every white surface; the strongest 16px/64px shadow belongs to the opening product panel.
- Do not replace the footer's subdued gray directory with uniformly white bold links.
- Do not give ordinary cards the exaggerated pill curvature of 40px actions.
- Do not extend launch orange through the neutral instructional and FAQ sections.
- Do not make institutional screen halos brighter than the interfaces they support.

## Motion and responsive

### Motion

**Observed:**

- Compact actions declare color and background transitions of .15s cubic-bezier(.4,0,.2,1).
- Information links declare transform transitions of 0.2s; other surfaces include opacity transitions of 0.2s and transforms of 0.3s.
- Product demonstrations change through scrolling chapters, and the proof numbers use rolling digit structures. The information stream extends horizontally beyond the viewport.

**Transfer:**

- Keep button color changes short and subordinate to the cinematic scenes.
- Use a stable product stage for workflow changes, with a readable static step and numeric fallback when animation is unavailable.

**Unknown:**

- Exact timelines, autoplay behavior, scroll-trigger thresholds and counter durations are not specified.

### Responsive

**Observed:**

- The default hero uses a side-by-side layout at 1000px and above; its classes provide centered text and action alignment below that threshold.
- Marketing wrapper side padding changes through 16px, 48px, 72px and 104px rules, with explicit 1000px and 1140px layout thresholds.

**Transfer:**

- At narrow widths, stack the product panel below the promise while preserving the atmospheric background as one continuous world.
- Reduce side padding before compressing interface content; keep pills compact and let the horizontal information rail remain edge-clipped.
- Treat three-column audience and cross-sell layouts as stacked or swipeable groups when they cannot retain readable text.

**Unknown:**

- Exact mobile font sizes, navigation-menu behavior, device scaling and final stacked section heights are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
