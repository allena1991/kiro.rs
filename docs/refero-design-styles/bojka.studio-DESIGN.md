# Bōjka Studio — electric editorial buoyancy

## Overview

An exuberantly spare, light editorial style with an acid-green entrance, black extended grotesk lettering and vermilion statements on white. Large, naturally lit photographs alternate with conversational columns of text, making the experience feel like an independent design journal rather than a conventional sales funnel. It suits creative products and services that can express confidence through scale, real-world imagery and a warm invitation rather than dense interface decoration.

### Essentials

- The identity is the opening spectacle: a regular-weight 157px extended grotesk masthead stretches almost edge to edge across an acid-green field; on the desktop stage it reads at about 221px.
- An off-centre introduction leaves the right half empty: 22px regular text sits in the left half below a deep green pause, followed by a nearly full-width rectangular photograph that continues below the fold.
- Navigation lives at the bottom, not in a header: a persistent white strip carries four plain 22px text links and a language link pushed to the far right; the current destination becomes vermilion.
- Color has strict territories: #0af500 is the opening field, #ff4600 is reserved for expressive headings, numbers and inline links, and the long reading canvas is #ffffff with #000000 text.
- Photographs are architectural blocks, not decorated cards: a 994px by 559px main frame, square corners, no border or shadow, with atmospheric real-world imagery as a required counterweight to text. Use a simple photographed product or relevant environment when no campaign imagery exists.
- The invitation is a monumental editorial ending: two 44px vermilion sentences wrap in the left column opposite a stack of black contact pills, each 60px high with 68px radii and white 22px labels.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric green | `#0af500` | `--color-opening` | background | Full-width opening field behind the identity and introduction; not a repeated card fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#ff4600` | `--color-expression` | text, link, accent | Closing invitation, chapter titles, step numbers, inline cross-links and current navigation item. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black | `#000000` | `--color-ink` | text, surface, action | Body text, masthead, navigation and solid contact pills. |
| White | `#ffffff` | `--color-canvas` | background, text | Main reading canvas, persistent navigation band and reversed contact labels. |

## Typography

- **custom_15364** — All editorial text, identity, navigation and buttons. Wide, low-contrast geometric grotesk with round bowls and a notably extended horizontal presence; regular weight carries every role. If unavailable, use **Questrial**. Use 400; tune horizontal width to retain the broad, open lettering, especially in the masthead. Font stack: "custom_15364", "Questrial", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | custom_15364 | 400 | 157px | 1px | -1.2px | Single-line identity masthead; isolate it in a 157px-high line box on the design stage. |
| heading | custom_15364 | 400 | 44px | 1px | 0.009em | Vermilion closing sentences and editorial section titles; compose inside 44px paragraph rows. |
| body | custom_15364 | 400 | 22px | 1px | normal | Inline text for paragraphs, navigation, captions and links; paragraph rows use 24px leading. |
| button | custom_15364 | 400 | 22px | 60px | normal | Centered white contact and social labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| capability lists on company pages | list | custom_15364 | 400 | 22px | 24px | normal | Dash-led services with compact paragraph rows. |

**Notes:**

- The type recipes specify the inline text layer. Do not apply the 1px inline line-height as the containing paragraph's row spacing: use 24px body rows, 44px heading rows and a 157px masthead box.
- The desktop composition uses a 1024px design stage enlarged to 1440px. Scale geometry and type together by 1.40625: body reads at 30.9px, headings at 61.9px, the identity at 220.8px and contact pills at 84.4px high. Alternatively implement these visible sizes directly without a transformed stage.
- Keep all roles at weight 400. Scale, width and color provide hierarchy; small text remains wide and conspicuous rather than becoming fine print.
- No viewport type formula is prescribed. Preserve the masthead's edge-to-edge silhouette by fitting the new name to its available width.

## Layout

**Density:** Airy at section scale but tightly led within paragraphs; the page alternates large photographic blocks and unboxed text islands.

### Spacing

| Value | Use |
| --- | --- |
| 15px | Design-stage side inset, inter-pill gap and recurring small separation; appears as 21.1px in the desktop composition. |
| 24px | Body paragraph row spacing on the design stage. |
| 44px | Heading row spacing and separation between the two closing statements on the design stage. |

### Containers and grids

- **Design stage**: max width 1024px · side padding 15px. Proportional desktop canvas, enlarged to the available 1440px width rather than centered as a narrow column; these are design-stage dimensions.
- **Editorial pair**: 2 columns · gap 16px. Two approximately 489px columns; the right column begins at 520px on the design stage. Text remains ragged-right.
- **Main photographic span**: max width 994px. Wide media spanning both columns; a 559px-high landscape is the central recurring format.
- **Offset gallery** (only for work-index and image-rich company pages): 6 columns · gap 16px. A compositional six-track guide, not a uniform tile grid. Alternate 321px portraits, 489px half-width images, 658px landscapes and 826px wide images, leaving intentional unfilled columns.

## Corner radius

| Element | Radius |
| --- | --- |
| Contact pills | 68px |
| Photographs | 0px |

## Surfaces and depth

### Surfaces

#### Reading canvas · level 0

**Use:** Default surface for all long-form reading and the closing invitation.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat white without rules, panel outlines or elevation.

**Transfer:** Separate content through open space and alignment, not nested cards.

#### Electric opening field · level 0

**Use:** The opening identity stage.

**CSS:** `background: #0af500; color: #000000`

**Observed:** A pure flat fill extends to both browser edges behind the huge masthead, intro and beginning of media.

**Transfer:** Keep this one strong chromatic entrance, then let white dominate the rest of the page.

#### Photographic frame · level 1

**Use:** Media and slideshow clipping surface.

**CSS:** `background: #000000; overflow: hidden; border-radius: 0px`

**Observed:** The photograph covers the frame; black is a concealed backing rather than a visible decorative border.

**Transfer:** Use real imagery edge to edge inside the frame.

## Components

### Identity masthead

**Use:** Opening identity as the page's largest graphic.

**CSS:** `font-family: custom_15364, Arial, sans-serif; font-size: 157px; font-weight: 400; letter-spacing: -1.2px; color: #000000`

**Text style:** `display` — custom_15364 400 · 157px/1px · tracking -1.2px

**Observed:** Two words sit on one immense line close to the upper and lateral edges, without an accompanying symbol or eyebrow.

**Transfer:** Fit a short product name or two-word promise into the same extended silhouette.

### Bottom navigation

**Use:** Persistent page navigation and language selection.

**CSS:** `background: #ffffff; color: #000000; font-size: 22px; font-weight: 400`

**Text style:** `body` — custom_15364 400 · 22px/1px

**Observed:** A white full-width strip stays at the viewport bottom over the scrolling content. Four destinations occupy the left and middle; language is isolated at the right edge. The active destination is vermilion, without a box or underline.

**Transfer:** Keep links text-only and reserve space for this strip throughout the page.

### Contact pill

**Use:** Email and social destinations in the closing invitation.

**CSS:** `background: #000000; color: #ffffff; height: 60px; border-radius: 68px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — custom_15364 400 · 22px/60px

**Observed:** The email pill is wider than the two social pills. All align on their left edge, with content-sized widths rather than stretching across the column; no icons accompany the labels.

**Transfer:** Use a direct contact destination and two relevant public channels; retain the visibly generous horizontal breathing room.

### Editorial copy pair

**Use:** Short introduction and explanatory text.

**CSS:** `font-size: 22px; font-weight: 400; color: #000000`

**Text style:** `body` — custom_15364 400 · 22px/1px

**Observed:** Independent ragged-right paragraphs occupy two columns without divider lines. A short greeting introduces the pair; some second-column text extends farther down.

**Transfer:** Pair a point of view with a concrete account of the product's value rather than two duplicate feature summaries.

### Closing statement pair

**Use:** Warm final invitation, distinct from navigation.

**CSS:** `color: #ff4600; font-size: 44px; font-weight: 400; letter-spacing: 0.4px`

**Text style:** `heading` — custom_15364 400 · 44px/1px · tracking 0.009em

**Observed:** Two complete sentences form separate multiline paragraphs at the left, opposite the Contact pill stack. The second sentence begins after a conspicuous pause.

**Transfer:** Write one outcome-led invitation followed by a human welcome.

### Back to top link

**Use:** Small utility at the foot of the closing composition.

**CSS:** `color: #000000; font-size: 22px; font-weight: 400; text-decoration: none`

**Text style:** `body` — custom_15364 400 · 22px/1px

**Observed:** A plain left-aligned text action sits near the lower edge, well below the invitation; a compact rights block occupies the right column above the persistent navigation.

**Transfer:** Keep the utility separate from the contact stack and use the same readable text size.

### Image caption link

**Only for:** work galleries

**Use:** Plain linked project title immediately below each photograph.

**CSS:** `color: #000000; font-size: 22px; font-weight: 400; text-decoration: none`

**Text style:** `body` — custom_15364 400 · 22px/1px

**Observed:** Caption sits outside the image on white, aligned to the image's left edge. Long names wrap naturally; there are no category tags or card containers.

**Transfer:** Use product examples, customer stories or demonstrations as the caption subject.

### Numbered chapter

**Only for:** process and instructional pages

**Use:** Explain stages with oversized enumeration.

**CSS:** `color: #ff4600; font-size: 157px; font-weight: 400; letter-spacing: -1.2px`

**Text style:** `display` — custom_15364 400 · 157px/1px · tracking -1.2px

**Observed:** A giant orange number sits beside a smaller orange title, with the title aligned toward the numeral's baseline. Black explanatory prose spans the column beneath; two chapters can share a row, with photographs interrupting subsequent rows.

**Transfer:** Use these numerals for a real sequence, not as arbitrary decorative statistics.

## Imagery and graphics

### Real-world product photographs

**Use:** Opening slideshow and proof imagery throughout a landing page.

**Observed:** A tablet or laptop is photographed at a slight angle in a pale, naturally lit setting. Other scenes show printed objects, signage, interiors and people holding products. Images retain their own color and texture, with no page-color tint or text overlay; wide frames dominate the text in area.

**Transfer:** Photograph the new product in use or place a readable interface in a credible device photograph. A single well-composed, softly lit scene is the minimum version; do not replace it with a floating UI tile.

### Atmospheric photographic interludes

**Use:** Required visual breathing space between argument and invitation.

**Observed:** Cool turquoise water, birds over a waterfront and urban surroundings create expansive horizons and tactile detail. The imagery is rectangular and often almost full-width; its softness contrasts with hard flat green and crisp type.

**Transfer:** Use an environment connected to the new product's world: a material, place, landscape or everyday action with natural light and spatial depth. Maintain a photographic interlude even when no campaign assets exist.

### Offset documentary collage

**Only for:** process, company and work-index pages

**Use:** Varied pacing within longer editorial pages.

**Observed:** Tall waterfall and river photographs interrupt two-column numbered chapters; company imagery includes bridge structure, waterfront scenes and a sunset. Gallery pairs mix narrow portraits with broader landscapes, sometimes staggered vertically or centered over four tracks.

**Transfer:** Mix portrait detail with wide environmental context, respecting each image's subject rather than forcing identical aspect ratios.

## Section recipes

How recurring sections are built.

### First screen: Electric identity opening

**Observed:** Back to front: Electric opening field, Identity masthead across nearly the entire width at the top, a compact three-line introduction in the left half after a deep open interval, then a Main photographic span; Bottom navigation overlays the lower edge on white. At 1440px wide the masthead reads at 220.8px, the intro at 30.9px and the photograph begins about 563px down with 21.1px side margins. Within the first 900px, the complete identity and intro, the upper part of the photographic scene and the fixed navigation are visible. The remainder of the photograph and editorial explanation continue below. There is no separate hero button cluster; navigation and contact provide actions.

**Transfer:** Use the new product's short name as the giant graphic, with one concise value statement below it. Without polished campaign media, use a softly lit photograph of the product, its material or its working environment in the same broad frame. Work indexes use a narrower first photograph, while instructional and company pages retain the large identity and change the introductory paragraph and subject of the image.

**Avoid:** Do not center a conventional headline above two CTA buttons, add a top navigation bar, or crowd the green pause with badges and feature tiles.

**Text style:** `display` — custom_15364 400 · 157px/1px · tracking -1.2px

### Editorial introduction

**Observed:** Editorial copy pair on Reading canvas follows a wide photograph. A brief greeting leads the two-column explanation; a second wide atmospheric photograph closes the passage.

**Transfer:** Use a concise human introduction, then contrast what the product believes with what it helps people do.

**Text style:** `body` — custom_15364 400 · 22px/1px

### Open closing invitation

**Observed:** Closing statement pair fills the left half of Reading canvas while Contact pill stack starts level with its top in the right half. The composition is nearly viewport-height and deliberately sparse below the copy. Back to top link and a rights block sit near the bottom, with Bottom navigation still visible. Every page ends with this same construction; some have the trailing edge of the previous photograph above it.

**Transfer:** Keep the two-column invitation and stacked direct-contact actions as a signature device. Use product-appropriate next steps without turning the ending into a many-column sitemap.

**Text style:** `heading` — custom_15364 400 · 44px/1px · tracking 0.009em

### Asymmetric visual index

**Only for:** work-index pages

**Observed:** Offset gallery combines large single landscapes, portrait/landscape pairs and centered wide images. Image caption link follows every image; ample white is part of the rhythm. The first image overlaps the green opening area before the gallery continues on white.

**Transfer:** Present examples at varied scales while giving each an immediately adjacent plain-text title. Let the strength of each image decide its size.

### Numbered explanation

**Only for:** process and instructional pages

**Observed:** After a landscape image and a short left-column introduction, Numbered chapter blocks form two-column rows. The six-stage example is punctuated by narrow nature photographs. A more personal prose-and-photo passage leads to a proof section with an orange heading, short acknowledgment at left and a wide run of names at right.

**Transfer:** Explain the number of stages the new content truly needs, then follow the method with credible textual proof rather than inventing numerical stats.

**Text style:** `heading` — custom_15364 400 · 44px/1px · tracking 0.009em

### Company perspective spread

**Only for:** company and culture pages

**Observed:** A wide documentary image leads into paired paragraphs. A compact dash-led capability list and smaller images deepen the story. Later, two unequal-width orange heading-and-body blocks explain an identity detail; a large offset sunset image bridges into the final invitation.

**Transfer:** Use this treatment for people, craft and product philosophy, grounding abstract ideas in a tangible detail.

**Text style:** `heading` — custom_15364 400 · 44px/1px · tracking 0.009em

## Page flow

**Storyline:** Identity and promise → tangible visual proof → editorial explanation or an expanded body of work → atmospheric pause → personal invitation.

### Compact marketing landing page

1. **Identity and promise** — Electric identity opening with a brief left-aligned statement and a broad product photograph.
2. **Point of view** — Greeting and two unboxed columns explain a distinctive approach.
3. **Atmospheric pause** — A broad environmental photograph provides an emotional counterweight.
4. **Closing call** — Open closing invitation with orange sentences and black contact pills.

**Transfer:** Use the default composition for a focused product or service introduction; select proof that can carry a large photograph.

### Visual proof index

1. **Introduction** — The identity stage introduces the collection with a longer paragraph.
2. **Demonstration** — An asymmetric sequence of product-in-context images, each followed by a plain caption.
3. **Closing call** — The shared invitation, utilities and persistent navigation finish the gallery.

**Transfer:** Use for case studies, a collection or product applications without reducing every entry to the same tile.

### Method and reassurance

1. **Promise** — Identity opening and a broad close-up of moving water.
2. **Orientation** — Left-column prose explains how the method helps the reader.
3. **Capability chapters** — Oversized orange enumeration and titles, compact black paragraphs and interspersed photographs.
4. **Objection handling** — A personal text-and-photo passage invites unusual challenges.
5. **Social proof** — Orange heading with acknowledgment and a dense text list of clients.
6. **Closing call** — Shared orange invitation and contact stack.

**Transfer:** Use for onboarding, implementation or a complex service; make the sequence understandable without making it a rigid flowchart.

### Human context and philosophy

1. **Origin** — Identity opening with a personal story and urban environmental photograph.
2. **Capability and people** — Paired explanatory columns, dash-led service list and documentary imagery.
3. **Distinctive detail** — Unequal heading-and-copy blocks turn a small identity decision into a story.
4. **Atmospheric pause** — An offset wide sunset scene.
5. **Closing call** — Shared invitation and bottom utilities.

**Transfer:** Use for team, product principles or company pages; explain a genuine detail rather than adding generic values cards.

## Writing

Confident, friendly and thoughtful. The voice links creative conviction to practical collaboration, thanking people and inviting conversation rather than using hard-sell urgency.

**Do not copy:** Do not reuse the Bōjka name or wordmark, its buoy metaphor as an owned brand story, contact details, project and client names, founding history, claims or rights dates. Source quotations illustrate tone only.

- **Addressing the reader:** First-person plural for the maker and direct, courteous second person for the reader. Czech copy uses a warm professional register rather than impersonal corporate language.
- **Rhythm:** Short plain navigation labels; full-sentence opening statements; compact paragraphs with several connected thoughts. Orange headings can be complete sentences and wrap naturally over two or three lines. The ending uses two deliberate sentences separated by a pause.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A clear outcome followed by how the maker achieves it. | Two sentences, about 15–25 words. | “Perfektní viditelnost v jakékoliv situaci. Vytváříme kreativní řešení a dáváme je do strategických souvislostí.” |
| Chapter title | Name a concrete action or stage in everyday words. | One to six words. | “Hledání shody”<br>“Budování týmu a návrh koncepce” |
| Closing invitation | Invite a shared outcome, then express anticipation of working together. | Two short sentences in separate paragraphs. | “Najděte s námi správný směr pro svoji značku.”<br>“Těšíme se na začátek nové spolupráce.” |
| Utility action | Use the literal destination or action, not promotional language. | One word or a direct address. | “Kontakt”<br>“Nahoru” |

**Words and phrasing to use:** together; context; clear direction; thoughtful work; let us know; thank you; from first idea to final result

**Avoid:** revolutionary platform; growth hacks; 10× everything; act now; industry-leading solutions; excessive English jargon

**Rules:**

- Explain the practical value of a creative decision instead of presenting creativity as an end in itself.
- Let a small detail support a larger point of view.
- Use acknowledgment and an invitation to create warmth; avoid artificial urgency.
- Keep destination labels literal even when the surrounding prose is expressive.

## Do's and Don'ts

### Do

- Keep all text at weight 400 and let the 157px, 44px and 22px stage sizes establish hierarchy.
- Scale the entire desktop stage consistently so media, type and contact pills retain their proportions.
- Keep the opening introduction to roughly half the width and leave the opposite side open.
- Use #ff4600 on white for the invitation and meaningful chapter headings.
- Give the main image its 994px by 559px design-stage silhouette with square corners.
- Maintain content-sized black contact pills with a 60px stage height and 15px vertical gaps.
- Preserve the white bottom navigation band while the content scrolls.
- Use environmental photography to punctuate a page even when product proof is primarily textual.

### Don't

- Do not make the extended masthead bold; its scale already supplies the emphasis.
- Do not spread green across every section or use it as the default button color.
- Do not add grey card backgrounds, hairline card borders or drop shadows to explanatory prose.
- Do not shrink captions and navigation into tiny secondary UI; they share the 22px body scale.
- Do not make social pills equal-width full-column slabs; preserve their different content-led widths.
- Do not impose uniform square thumbnails on the visual index.
- Do not use orange for long body paragraphs; keep extended reading black on white.
- Do not decorate links with icon badges or introduce a generic feature-icon grid.

## Motion and responsive

### Motion

**Observed:**

- Page layers declare a 545ms cubic-bezier(0.4, 0.24, 0.4, 1) transition.
- The opening slideshow image declares opacity 1s ease-in-out.

**Transfer:**

- Use the declared opacity crossfade for a multi-image opening stage; retain the composition and frame during image changes.
- Keep navigation separate from scrolling imagery so destinations remain available.

**Unknown:**

- Slideshow cadence and action hover/focus treatments are unspecified.
- The exact behaviour of gallery animations is unspecified.

### Responsive

**Observed:**

- The desktop presentation is a proportionally enlarged 1024px design stage in a 1440px-wide window.

**Transfer:**

- On narrow screens, reflow the editorial pairs into one column rather than shrinking the entire 1024px stage until text becomes illegible.
- Fit the giant identity to the screen width while preserving its unusually broad silhouette.
- Keep the bottom navigation readable and reserve content space for its height; place contact actions below the invitation when two columns no longer fit.

**Unknown:**

- Mobile breakpoints, exact small-screen type sizes and navigation changes are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
