# mmmmenu — monochrome stage, colorful outcomes

## Overview

A bright, practical product style with tightly set grotesk headlines and a restrained black-and-white interface. Color lives inside richly branded product examples, while grainy silver backdrops make small interface demonstrations feel tangible. The spacious composition suits approachable creation tools and self-service software, balancing expressive output galleries with plainspoken explanations.

### Essentials

- Compact promises above expansive output: centered Inter headlines at 48px/1, weight 600 and -0.05em tracking sit in a 620px text column before a full-width moving gallery.
- A monochrome shell lends the product its color: white canvas, black headings and #666666 supporting text surround forest, rose, navy and sand media stages; color occupies the lower visual half of the opening rather than the navigation or prose.
- Actions feel like small black lozenges: primary buttons are 48px high with 28px horizontal padding and fully rounded ends; the header uses a 40px compact version.
- Show finished work as tall artifacts, not generic dashboard tiles: 288px-wide examples sit in 480×600px rounded stages with 56px top inset, clipped at the bottom and separated by 8px. Every new page needs an expressive output showcase; use designed sample documents or result previews when no finished media exists.
- Software gets a tactile silver stage: white floating interface panels sit over blurred black-to-white folds with fine overlay grain, inside 14px corners. Include this monochrome material device around at least one explanation or demonstration.
- Small pills introduce large breathing spaces: sentence-case 14px/20px labels use 2px 6px padding, followed by 36px/1.1 section headings; 56px and 72px gaps separate intros from proof.
- The ending becomes a useful directory, not a sales billboard: open question-and-answer text in a 704px reading column leads to a white footer with a small left identity, three columns of subdued 14px links, a hairline and tiny copyright.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Navy stage | `#0d255b` | `--color-navy` | background | Deep blue backing in the output showcase. |
| Rose stage | `#c8859d` | `--color-rose` | background | Muted pink backing in the output showcase. |
| Sand stage | `#d1bfaf` | `--color-sand` | background | Warm beige backing in the output showcase. |
| Forest stage | `#0a1b11` | `--color-forest` | background | Deep green backing for finished-output imagery; not a prose background. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Soft black action | `#171717` | `--color-action` | action, text | Primary button fill and secondary button text. |
| Black ink | `#000000` | `--color-ink` | text, accent | Headings, feature titles and outline icons. |
| Navigation gray | `#4d4d4d` | `--color-nav-text` | text, link | Black at 70% over white for the navigation link. |
| Supporting gray | `#666666` | `--color-muted` | text, link | Black at 60% over white; supporting copy and subdued directory links. |
| Directory rule | `#e4e4e7` | `--color-footer-rule` | border | Subtle cool-gray footer separator. |
| Content hairline | `#e6e6e6` | `--color-rule` | border | Black at 10% over white for answer separators and panel rings. |
| Label wash | `#f2f2f2` | `--color-badge` | surface, border | Black at 5% over white for label pills and faint comparison rules. |
| Preview backing | `#f3f3f3` | `--color-card` | surface | Visible neutral-900 at 5% over white behind gallery previews and secondary actions. |
| Button white | `#fafafa` | `--color-on-action` | text | Primary action text. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface | Page canvas, navigation and floating interface panels. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| comparison-led product pages | Positive comparison edge | `#b3dbb1` | `--color-comparison-rule` | border | Horizontal dividers within the highlighted product column. |
| comparison-led product pages | Positive comparison wash | `#e9ffe8` | `--color-comparison` | surface | Continuous highlighted product column. |

## Typography

- **Inter** — All marketing headings, supporting copy, actions and navigation. Clean contemporary grotesk with a high x-height; tightly tracked at display sizes, open and neutral at reading sizes. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Inter | 600 | 48px | 1 | -0.05em | Centered opening promise, typically wrapping to two lines. |
| heading | Inter | 600 | 36px | 1.1 | -0.05em | Section titles, usually centered within a narrow text column. |
| lead | Inter | 400 | 18px | 1.5 | -0.025em | Opening support and section introductions. |
| item-title | Inter | 500 | 16px | 1.5 | normal | Feature titles, questions, preview captions and full-size buttons. |
| body | Inter | 400 | 16px | 1.625 | normal | Feature and process descriptions. |
| answer | Inter | 400 | 16px | 1.8 | normal | Expanded explanatory answers. |
| label | Inter | 500 | 14px | 20px | normal | Eyebrow pills, step labels and compact header actions. |
| small-link | Inter | 400 | 14px | 20px | normal | Navigation and directory links. |

**Notes:**

- Use the same family throughout the marketing shell; expressive lettering belongs within showcased output, not in marketing headings.
- Headings retain -0.05em tracking at both levels. Supporting lead copy relaxes to -0.025em; ordinary reading copy and labels use normal tracking.
- The display is only one step above section headings; expressive media, not enormous type, provides the main spectacle.

## Layout

**Density:** Airy at section level, compact within explanatory clusters; the page alternates large proof objects and small, plain text groups.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Feature title-to-description gap. |
| 8px | Icon-to-title gap and opening gallery stage separation. |
| 16px | Label-to-heading gap and preview-to-caption spacing. |
| 20px | Heading-to-support and support-to-action gaps; process grid gutters. |
| 24px | Question vertical padding and answer bottom padding. |
| 32px | Container side padding and inset around the main demonstration. |
| 56px | Opening action-to-gallery gap; heading-to-feature grid gap; footer internal separation. |
| 64px | Opening section top padding beneath navigation. |
| 72px | Intro-to-process and intro-to-main-demo gaps. |
| 80px | Standard section and footer vertical padding. |
| 100px | Question section vertical padding and process section bottom padding. |

### Containers and grids

- **container**: max width 1280px · side padding 32px. Centered outer container; at 1440px the usable content is 1216px wide with 112px visible side margins.
- **opening text**: max width 620px. Centered headline block; supporting text is limited to 540px.
- **section introduction**: max width 560px. Centered eyebrow and heading; supporting copy generally stays within 540px.
- **process grid**: 3 columns · gap 20px. Equal 392px-wide chapters, with labels and explanatory text over individual media stages.
- **feature grid**: 3 columns · gap 56px. Three 368px text columns with 48px or 56px row spacing; no enclosing cards.
- **reading column**: max width 768px · side padding 32px. Question section with 704px usable text width.
- **directory grid**: 3 columns · gap 32px. Three link columns to the right of a small identity; 16px row spacing.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media and panels | 14px |
|  | opening stages | 16px |
|  | buttons and labels | 9999px (pill) |
| device-led product openings | floating code panel | 24px |
| device-led product openings | device screen top | 46px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating interface | `0 0 0 1px rgba(0,0,0,0.1), 0 4px 24px -6px rgba(0,0,0,0.25)` | Small white interface panels on silver material stages. |
| main demonstration | `0 0 0 1px rgba(0,0,0,0.1), 0 10px 16px -10px rgba(0,0,0,0.25)` | Large inset editor demonstration. |
| floating utility | `0 0 0 1px rgba(0,0,0,0.1), 0 24px 64px rgba(0,0,0,0.15)` | Small raised code or sharing artifact. |

### Surfaces

#### Canvas · level 0

**Use:** All main page sections and navigation.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** White continues uninterrupted between narrative chapters and through the footer.

**Transfer:** Separate chapters through space and media rather than alternating colored full-width bands.

#### Silver material stage · level 1

**Use:** Process illustrations and the principal product demonstration.

**CSS:** `border-radius: 14px; overflow: hidden; position: relative`

**Observed:** Soft diagonal black, silver and white folds carry fine grain. Interface panels stay crisp above this material; the large demo uses 32px inset.

**Transfer:** Recreate with the Silver fold artwork recipe and place a real, readable interface or simplified working-state illustration above it.

#### Floating white panel · level 2

**Use:** Small controls, result artifacts and process demonstrations.

**CSS:** `background: #ffffff; border-radius: 14px; box-shadow: 0 0 0 1px rgba(0,0,0,0.1), 0 4px 24px -6px rgba(0,0,0,0.25)`

**Observed:** Panels are centered against silver material, with minimal chrome and a few meaningful controls.

**Transfer:** Use a concise interface fragment rather than shrinking an entire application into each step.

#### Gallery well · level 1

**Use:** Backing around tall output previews.

**CSS:** `background: rgba(23,23,23,0.05); border-radius: 14px; overflow: hidden; padding: 20px 20px 0`

**Observed:** The preview is bottom-aligned and clipped while its caption sits outside the well.

**Transfer:** Preserve the neutral frame so colorful finished work remains the focus.

#### Comparison highlight · level 1

**Only for:** comparison-led product pages

**Use:** One continuous favored column in a comparison table.

**CSS:** `background: #e9ffe8; border-bottom: 1px solid #b3dbb1`

**Observed:** The column has rounded outer top and bottom corners, not separate rounded cells.

**Transfer:** Highlight a single meaningful choice without turning the full table into a promotional card.

## Components

### Sticky navigation

**Use:** Persistent compact orientation and conversion.

**CSS:** `position: sticky; top: 0px; z-index: 100; background: #ffffff; padding: 28px 0`

**Text style:** `small-link` — Inter 400 · 14px/20px

**Observed:** A three-part row places one understated link left, a compact stacked identity centered, and a dark action right. Content height is 40px, total header height 96px. The compact action uses the label recipe, 16px side padding and 40px height.

**Transfer:** Keep the centered identity visually independent of unequal side content.

### Primary button

**Use:** Main conversion after an opening or proof block.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #171717; color: #fafafa; height: 48px; padding: 0 28px; border-radius: 9999px; gap: 8px`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** A short text-only lozenge, centered beneath support copy; width follows the label.

**States:** Declared: hover background uses the soft-black fill at 90% opacity; focus-visible border-color is lab(66.128% -.0000298023 .0000119209), with no added visible shadow.

### Secondary button

**Use:** Browse a larger collection after a preview gallery.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0 28px; border-radius: 9999px; background: rgba(23,23,23,0.05); color: #171717`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** Placed centrally beneath the horizontal collection rather than beside the primary action.

**States:** Declared: hover background uses soft black at 10% opacity; focus-visible border-color is lab(66.128% -.0000298023 .0000119209).

### Eyebrow pill

**Use:** Small topic and process-step signposts.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: rgba(0,0,0,0.05); border: 1px solid transparent; border-radius: 9999px; padding: 2px 6px; gap: 4px`

**Text style:** `label` — Inter 500 · 14px/20px

**Observed:** Sentence case; centered above section titles but left-aligned at the start of each process chapter.

### Output stage

**Use:** Large moving gallery of finished work.

**CSS:** `display: flex; justify-content: center; width: 480px; height: 600px; padding: 56px 96px 0; border-radius: 16px; overflow: hidden; background: #0a1b11; flex-shrink: 0`

**Observed:** Tall 288px previews begin at a shared top inset and extend beyond the stage's lower edge. Alternate backing colors include rose, navy and sand.

**Transfer:** Use several genuinely distinct output designs with the same framing; preserve their individual typography inside the artifact.

### Feature item

**Use:** Short capability explanations in an unboxed grid.

**CSS:** `display: flex; flex-direction: column; gap: 6px`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** A small outline icon precedes the medium-weight title with an 8px gap; one or two lines of body copy sit below in supporting gray. No colored container or raised tile.

### Preview card

**Use:** Horizontally scrolling library of concrete examples.

**CSS:** `background: rgba(23,23,23,0.05); border-radius: 14px; padding: 20px 20px 0; height: 470px; overflow: hidden`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** A 296px well sits within a 320px item that has 12px outer padding. The 256px-wide preview is clipped to 450px visible height with a faint ring; its caption is outside, 16px below the well.

**Transfer:** Keep the collection edge overflowing the content container and show a partial next item.

### Gallery arrow

**Use:** Previous and next controls over preview imagery.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; width: 64px; height: 64px; border-radius: 9999px; background: rgba(255,255,255,0.1); backdrop-filter: blur(20px) brightness(1.5); box-shadow: 0 0 0 1px rgba(0,0,0,0.1), 0 0 40px rgba(0,0,0,0.25); color: #000000`

**Observed:** 32px black line arrows sit over the gallery at its vertical midpoint, within a 1024px-wide control rail.

**States:** Declared: hover background becomes white at 40% opacity; focus-visible border-color is lab(66.128% -.0000298023 .0000119209) and retains a 1px dark ring plus the diffuse shadow.

### Question row

**Use:** Open objection-handling content near the ending.

**CSS:** `display: flex; flex-direction: column; border-bottom: 1px solid rgba(0,0,0,0.1)`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** Always-visible definition-list structure: question uses 24px top and bottom padding; answer uses the answer recipe, supporting gray and 24px bottom padding. The final row has no closing divider.

**Transfer:** Write answers directly beneath questions; do not assume accordion behavior.

### Directory link

**Use:** Dense, subdued footer navigation.

**CSS:** `font-size: 14px; line-height: 20px; color: #000000; opacity: 0.6`

**Text style:** `small-link` — Inter 400 · 14px/20px

**Observed:** Links form three columns with plain category headings, not individual boxed navigation items.

**States:** Declared: hover opacity 1.

### Comparison cell

**Only for:** comparison-led product pages

**Use:** Concise binary evaluation of capabilities.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #e9ffe8; padding: 32px 24px; border-bottom: 1px solid #b3dbb1`

**Text style:** `item-title` — Inter 500 · 16px/1.5

**Observed:** Two centered result columns follow a double-width row-label column in a 768px table. Checks and crosses are black 20px outlines; only the favored column is tinted.

**Transfer:** Use honest feature comparisons with row-specific positive and negative results.

## Imagery and graphics

### Finished output gallery

**Use:** Signature opening spectacle and later library preview.

**Observed:** Long, individually designed menu artifacts combine expressive lettering, strong backgrounds and small food pictures. They stand upright inside solid rounded color stages, clipped rather than miniaturized to fit. The gallery occupies the broad lower portion of the opening while copy stays narrow above.

**Transfer:** Show the new product's finished outputs at a similarly tall, readable scale. If no assets exist, design several convincing sample result sheets with differing visual identities, real-looking content and compact imagery; keep the surrounding site monochrome.

### Silver fold artwork

**Use:** Signature backing behind process panels and the main demonstration.

**Observed:** An abstract fabric-like monochrome field moves from dense charcoal at the left to milky white at the right, with diagonal soft creases and fine photographic grain. A repeating grain layer uses 120px sizing and overlay blending; the white UI floats sharply above it.

**Transfer:** Maintain the silver, tactile material even with a simplified interface. Match the soft folds and grain; exact gradient stops are not essential.

**Build:** Within a 14px clipped stage, layer a black-to-white diagonal linear gradient with two broad curved SVG bands, one black at 35% alpha and one white at 70% alpha; rotate their long axes about -30 degrees and blur them by 32px. Add an SVG feTurbulence noise tile at 120px repeat size with mix-blend-mode: overlay. Keep the left edge dark and the right edge pale. Place the crisp white interface above both layers with at least 32px inset for a full-width demonstration.

### Live editor demonstration

**Use:** Large functional proof after an explanatory heading.

**Observed:** A wide white editor shows a narrow settings sidebar and a much larger preview area. Its 1152×713px frame is inset 32px inside the 1216×777px silver stage, with a subtle outline and low shadow.

**Transfer:** Use an actual recording or polished still of the new workflow. Minimum version: a meaningful settings panel beside a populated output preview, not ornamental UI noise.

### Device and floating artifact

**Only for:** device-led product openings

**Use:** Focused single-product opening instead of the moving output gallery.

**Observed:** A realistic upright black phone dominates the center below the CTA, with a cream-and-red designed screen, a white code card peeking from behind and a light-gray hand-drawn looping arrow. The phone overlaps a broad dark-to-red image strip lower down. The code card uses 24px corners and a diffuse shadow.

**Transfer:** Replace the phone content with a coherent product result and the code card with a relevant shareable artifact. Keep the upright foreground object, small floating secondary object and broad lower backing rather than adding many scattered badges.

**Build:** Center a 340px-wide device silhouette over a 1216px-wide media strip, use a rounded black outer shell and inset populated screen. Offset a 220px white artifact card upward behind it; add a single thin gray SVG loop arrow pointing toward that card. Keep the annotations monochrome.

### Product in context photograph

**Only for:** explanatory product pages

**Use:** Right half of a problem-to-benefit split section.

**Observed:** A 572×600px rounded photograph shows a phone on a saturated red restaurant tabletop with dishes and utensils. Directional light produces crisp shadows; the device is legible and the environment is vivid rather than softly washed out.

**Transfer:** Stage the new product in its real use context with a strong single-color environment and directional light. Preserve the roughly square framing, half-section scale and 14px corners; select a color native to that context.

### Icons

**Observed:** Black outline SVGs with 2px round-ended strokes. Feature icons are usually 18px; comparison checks and crosses are 20px; gallery arrows are 32px. Icons sit inline beside titles rather than in colored medallions.

**Transfer:** Choose a consistent Lucide-like outline set; use ordinary functional symbols and match size to role.

## Section recipes

How recurring sections are built.

### First screen: Output-led opening

**Observed:** A 96px white Sticky navigation precedes a centered text stack with 64px top padding. The display headline spans a 620px maximum column and wraps to two tightly set lines; lead copy sits 20px below in a 540px column, followed by a Primary button after another 20px. The output gallery begins 56px below the button, around the middle of the first 900px. White canvas sits behind a full-bleed rail of solid-color Output stages, then tall finished artifacts sit inside those stages. Within the first viewport the complete headline, support and CTA are visible, plus the upper, substantial portion of several artifacts and partial edge stages; the stage bottoms fall below the fold.

**Transfer:** Keep the restrained text promise above a visually rich output rail. Without existing media, create convincing populated sample outputs with several contrasting identities. A focused product page can replace the rail with the Device and floating artifact scene beneath the same centered type and single CTA; it uses 80px opening top padding.

**Avoid:** Do not substitute a left-text/right-dashboard split, enormous full-width slogan, twin CTA row or a collage of tiny floating interface windows.

**Text style:** `display` — Inter 600 · 48px/1 · tracking -0.05em

### Section heading pair

**Observed:** Eyebrow pill, 16px gap, centered heading within 560px, then 20px to lead copy within 540px. Standard chapters use 80px vertical padding. Proof follows after 56px or 72px depending on its scale.

**Transfer:** Give each chapter a short category signpost and a single concrete promise; retain the small label versus tightly set title contrast.

**Text style:** `heading` — Inter 600 · 36px/1.1 · tracking -0.05em

### Three-step explanation

**Observed:** Section heading pair leads by 72px into a three-column process grid. Each chapter contains an Eyebrow pill step number, a 32px gap, Feature item copy, then a centered Floating white panel on a 392×326px Silver material stage. A Primary button follows the grid by 72px.

**Transfer:** Show three genuinely meaningful actions or transformations; keep illustrations related in scale and material even when their inner controls differ.

### Demonstration and capability grid

**Observed:** A Section heading pair leads to the large Live editor demonstration after 72px. Six Feature items follow the media after 56px, in three columns with generous horizontal gaps and no cards.

**Transfer:** Show the product doing something before explaining its capabilities. Use the full-width demo as the chapter anchor and short grid copy as supporting detail.

### Horizontal collection

**Observed:** Section heading pair leads to a viewport-bleeding row of Preview cards, with the next item partially visible. Gallery arrows overlay the row, and a Secondary button follows below. Each caption sits outside its neutral well.

**Transfer:** Use a curated family of examples or use cases, retaining the colorful-artifact versus neutral-frame contrast.

### Open questions and directory ending

**Observed:** A 100px-padded question chapter uses the reading column, a centered title and 56px gap to Question rows. The white footer follows with 80px vertical padding, a small left identity and a three-column directory to the right; link groups are separated by 40px. A full-content hairline and copyright complete the page, without a separate closing sales banner.

**Transfer:** Answer practical adoption questions in full, then provide useful onward paths. Let link volume follow the new product's real information architecture rather than manufacturing dozens of destinations.

### Problem and context split

**Only for:** explanatory product pages

**Observed:** Two approximately equal columns share 1216px of usable width: a left-aligned heading and lead paragraph, followed by four short checkmarked benefits with 20px spacing, face a 572×600px Product in context photograph.

**Transfer:** Explain a specific old friction and its practical replacement, backed by one credible in-use scene.

### Comparison proof

**Only for:** comparison-led product pages

**Observed:** Section heading pair precedes a 768px table. Row labels occupy half its width; two 192px result columns occupy the rest. One continuous Comparison highlight runs through the favored column, with 89px rows and 14px outer corners. A Primary button closes the chapter.

**Transfer:** Compare a small set of meaningful user outcomes rather than filling every cell with marketing prose.

## Page flow

**Storyline:** plain promise → tangible product outputs → practical explanation and proof → capability or comparison chapters → example collection → open objections → useful directory

### Broad creation-tool marketing landing page

1. **Promise** — Centered headline and one action over a full-width moving finished-output rail.
2. **Process explanation** — Three numbered chapters with matching silver-backed interface illustrations and a follow-up action.
3. **Product demonstration** — Large editor view followed by an unboxed capability grid.
4. **Breadth of application** — Colorful example library in a horizontally overflowing carousel.
5. **Objection handling** — Open text answers in a narrow column.
6. **Onward navigation** — White multi-column directory and a restrained legal ending.

**Transfer:** Use this as the default product-marketing structure; adapt the order to the argument while preserving expressive outputs, tactile demonstration and the useful ending.

### Focused product education and adoption page

1. **Promise** — Centered headline and action over a single oversized device with floating sharing artifact.
2. **Problem reframing** — Left-aligned explanation and checkmarked benefits beside vivid in-context photography.
3. **Comparison proof** — Binary table with a continuous pale-green product column and closing action.
4. **Capability chapters** — Repeated centered heading pairs introduce concise unboxed grids.
5. **Breadth of application** — Shared example carousel.
6. **Objection handling** — Open questions tailored to adoption and compatibility.
7. **Onward navigation** — The same white directory footer and hairline ending.

**Transfer:** Use the device-led variant when a single interaction explains the product better than a range of outputs; comparisons and contextual photography belong to this educational argument.

## Writing

Direct, useful and gently reassuring. Benefits are expressed as everyday actions and avoided hassles, not as sweeping brand rhetoric.

**Do not copy:** Do not reuse the brand name, wordmark, example business identities, template artwork, proprietary product claims or source-specific promises as facts about another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your, often through imperative verbs. Refer to the product by its plain category rather than a personified we.
- **Rhythm:** Headlines are short sentence-case statements; support uses one or two plain sentences. Feature titles are brief noun phrases or action-benefit phrases, with one concrete sentence below.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Name the tool category and its intended audience without metaphor. | 5–8 words | “Online Menu Maker for Restaurants”<br>“Digital restaurant menu for modern restaurants” |
| Section headline | One practical outcome, often addressed to the reader. | 5–9 words | “How to create your online menu”<br>“Update your menu in seconds” |
| Supporting line | A small sequence of verbs followed by a tangible delivery or maintenance benefit. | 15–35 words | “Add your items, customize the look, and instantly share your menu with a link or QR code.” |
| Feature description | Explain the action and its everyday consequence in one sentence. | 10–20 words | “Adjust prices whenever costs change, without reprinting a single menu.” |
| Primary action | Imperative verb plus concrete object. | 2–5 words | “Create menu”<br>“Generate QR code menu” |
| Question heading | A straightforward adoption concern, answered directly beneath it. | 5–12 words | “Do I need design skills?”<br>“Can I customize the design of my restaurant menu?” |

**Words and phrasing to use:** create; customize; share; update; your; instantly; anytime; match your brand; without

**Avoid:** revolutionary; game-changing; unlock potential; seamless ecosystem; the future of everything; exclusive luxury

**Rules:**

- Use a concrete category term in the opening, then vary action verbs in later chapters.
- Translate features into changed everyday tasks rather than stacking abstract adjectives.
- Answer yes-or-no questions with a clear yes or no before adding detail.
- Keep labels in sentence case; reserve expressive all-caps lettering for the work being showcased.
- Use speed claims only when the new product can substantiate them.

## Do's and Don'ts

### Do

- Keep the opening headline at 48px, weight 600 and -0.05em tracking on desktop.
- Keep supporting lead paragraphs within 540px so the centered stack stays compact.
- Maintain white between chapters, using 80px vertical section padding rather than colored section bands.
- Frame large finished outputs in 16px stages and process illustrations in 14px frames.
- Use 18px outline icons with 2px strokes beside feature titles.
- Keep the full-size primary action 48px high and the compact header action 40px high.
- Give open answer text the 1.8 line-height recipe and a 704px usable reading column.
- Keep preview captions outside the 470px-tall neutral wells.

### Don't

- Do not make the main marketing type a mixture of decorative output fonts; use Inter throughout the shell.
- Do not carry the forest, rose or navy stage fills into navigation, body paragraphs or ordinary feature tiles.
- Do not turn the unboxed 368px-wide feature columns into elevated cards.
- Do not use sharp rectangular CTAs or heavily rounded square buttons in place of the pill actions.
- Do not give every interface panel the large 64px diffuse utility shadow; preserve the quieter demonstration shadow.
- Do not replace the gallery's glass arrows with opaque colored medallions.
- Do not give each comparison cell separate rounded corners; the tint must read as one continuous column.
- Do not append a dark promotional footer or giant closing slogan after the open questions.

## Motion and responsive

### Motion

**Observed:**

- The output marquee declares a 52s linear infinite animation.
- Buttons declare all-property transitions lasting .15s with cubic-bezier(.4,0,.2,1).
- Some preview elements declare transform, translate, scale and rotate transitions lasting 0.3s with cubic-bezier(.4,0,.2,1).
- Label pills declare color and box-shadow transitions lasting .15s with cubic-bezier(.4,0,.2,1).

**Transfer:**

- Use the continuous marquee for a varied output rail rather than a jump-cut slideshow.
- Keep interaction motion concentrated on gallery browsing and small action feedback.

**Unknown:**

- Playback behavior of the editor recording, scroll-trigger details and exact marquee travel distance are not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Below 1024px, opening titles declare 36px sizing, section titles 30px, lead copy 16px, and process grids become one column.
- Below 768px, opening gallery stages declare 300×375px dimensions with 60px side insets and 36px top inset.
- Below 768px, the header's left navigation is hidden and its grid becomes one centered column; footer link grids declare two columns.

**Transfer:**

- Preserve the tall-output rail on small screens using the reduced stage size instead of compressing all artifacts into one screen.
- Stack explanatory process panels while retaining their shared silver material and clear step hierarchy.
- For the focused device variant, scale the foreground scene as a unit so the secondary artifact continues to peek from behind.

**Unknown:**

- Actual narrow-screen rendering, overflow edge behavior and all small-screen header-action details are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
