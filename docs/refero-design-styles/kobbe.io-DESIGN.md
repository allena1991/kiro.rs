# Kobbe — storybook software shores

## Overview

A warm, matter-of-fact software aesthetic with the charm of an illustrated field guide. Off-white and stone surfaces, charcoal grotesk typography and tiny practical labels give detailed interfaces room to breathe. Hand-drawn people, animals and coastal landscapes soften the technical material with muted watercolor color; the overall density is low outside the product demonstrations.

### Essentials

- An offset editorial voice, not a centered billboard: a 224px side note sits beside an 800px main column in a 12-column container, with 32px gutters and 96px section padding.
- Headlines are medium-weight conversation, not poster type: Switzer 48px/1.25 at weight 500 for the opening, 36px/1.25 for chapters, both tracked at -0.025em.
- A small dark invitation anchors the pale page: 40px charcoal buttons with 10px corners, 14px/20px medium text and a small down-right arrow; a stone secondary action sits 8px away.
- Color lives in the pictures, not the chrome: the entire marketing canvas uses off-white, stone, gray and charcoal; muted green, brick red and watery blue are confined to illustrations and interface content.
- The software gets a storybook companion: wide pale product stages carry 1024px interface panels and small hand-drawn characters perched on their upper edge. Without finished software, use a truthful representative workflow panel plus an original ink-and-wash vignette.
- A living illustrated horizon frames the experience: include a low, full-bleed narrative frieze and a substantial illustrated closing landscape. Use original task-related figures or objects along a shared baseline when no equivalent scene exists.
- The ending stays light and inhabited: a two-tone 36px closing statement leads to small navigation columns and a 1440×480px landscape, with 12px credits tucked into its lower-right open space.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#2b2b2b` | `--color-ink` | text, action | Headlines, emphasis, arrows and primary action fills. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm gray | `#75736e` | `--color-muted` | text, link | Support copy, descriptive side notes and footer links. |
| Stone hairline | `#e4e2dd` | `--color-rule` | border | Feature lists, pricing rows and accordion separators. |
| Pale stone | `#f5f3f0` | `--color-stone` | surface | Cards, interface stages and secondary action fills. |
| Warm off-white | `#faf9f8` | `--color-canvas` | background, text | Default page canvas and light text on dark actions. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| billing controls | Soft charcoal track | `#c6c6c5` | `--color-switch-track` | surface | Visible result of 25% charcoal on the light canvas; implement with alpha charcoal. |

## Typography

- **Switzer** — Default marketing text, headlines and actions. Unassuming contemporary grotesk with open counters and a gently compact medium weight. If unavailable, use **Inter**. Use weights 400–600 and retain tight headline tracking. Font stack: "Switzer", "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.
- **Inter** (only for downloadable resource pages) — All text in the downloadable-resource variant. Neutral sans with direct, slightly technical proportions. Font stack: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Switzer | 500 | 48px | 1.25 | -0.025em | fixed | Opening promise; usually two lines in the wide main column. |
| heading | Switzer | 500 | 36px | 1.25 | -0.025em | fixed | Chapter headings and both lines of the closing invitation. |
| stat | Switzer | 500 | 30px | 1.2 | -0.025em | fixed | Small proof numbers paired with lowercase unit labels. |
| body | Switzer | 400 | 16px | 26px | normal | fixed | Main supporting paragraphs, restricted to 448px width. |
| item-title | Switzer | 500 | 16px | 1.5 | normal | fixed | Card titles and accordion questions. |
| text-link | Switzer | 500 | 16px | 1.25 | normal | fixed | Editorial links with down-right arrows. |
| side-note | Switzer | 400 | 14px | 1.5 | normal | fixed | Muted contextual phrase in the left rail. |
| side-note-lead | Switzer | 500 | 14px | 1.5 | normal | fixed | Dark opening words within a side note, continuing inline into gray copy. |
| item-copy | Switzer | 400 | 14px | 20px | normal | fixed | Compact card and feature descriptions. |
| action | Switzer | 500 | 14px | 20px | normal | fixed | Default buttons and navigation. |
| feature-bullet | Switzer | 500 | 14px | 20px | -0.025em | fixed | Dense included-feature lists. |
| caption | Switzer | 500 | 12px | 16px | normal | fixed | Footer links, credits and compact overflow counts. |
| footer-heading | Switzer | 600 | 12px | 16px | normal | fixed | Footer column labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| downloadable resource pages | resource-display | Inter | 500 | 36px | 1.25 | -0.025em | size clamp(24px, 2.5vw, 36px) | Inline dark promise and muted explanation in a single heading block. |
| downloadable resource pages | resource-heading | Inter | 500 | 21.6px | 1.25 | -0.025em | size clamp(20px, 2vw, 21.6px) | Small editorial introductions to galleries and instructions. |
| downloadable resource galleries | resource-caption | Inter | 500 | 16px | 1.5 | normal | fixed | Inline dark image title followed by gray descriptive prose. |
| downloadable resource pages | resource-body | Inter | 400 | 16px | 1.5 | normal | fixed | Specifications and numbered instructions. |
| downloadable resource pages | resource-action | Inter | 500 | 14px | 20px | normal | fixed | Resource actions and appearance selector. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Headline tracking remains -0.025em across display, headings and proof numbers; normal tracking is the default for prose and controls.
- Use weight and color, rather than uppercase or ornament, to distinguish the opening phrase of a side note.
- The closing reassurance is as large as its dark promise, but gray. Do not demote it to small print.

## Layout

**Density:** Airy around the narrative, compact within useful lists and interface panels.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Headline-to-support and adjacent action gaps. |
| 16px | Feature-row vertical padding and compact grid gaps. |
| 24px | Text-group-to-action spacing and stacked internal groups. |
| 32px | Container side padding, card padding and horizontal grid gutters. |
| 48px | Heading-to-full-width-content gap and vertical separation of card content. |
| 64px | Top inset of product panels inside their pale stages. |
| 96px | Default section top and bottom padding. |
| 144px | Generous separation between closing call and footer navigation. |
| 288px | Opening top padding for resource introductions. |

### Containers and grids

- **Editorial container**: max width 1280px · 12 columns · gap 32px · side padding 32px. Centered desktop shell: 1216px usable width at 1440px. Side note spans four columns; headline and paragraph span eight.
- **Side-note measure**: max width 224px. Keep contextual notes narrow and detached from the primary argument.
- **Paragraph measure**: max width 448px. Supporting paragraphs remain narrower than their 800px headline column.
- **Product panel**: max width 1024px. Centered within the full-width pale product stage.
- **Proof cards**: 4 columns · gap 32px. Four equally sized 280px cards with substantial internal breathing room.
- **Feature index**: 3 columns · gap 32px. Bordered text rows, 384px wide, not a wall of raised cards.
- **Resource gallery** (only for downloadable resource galleries): 2 columns · gap 32px. 592px-wide 16:9 image frames; rows are separated by 56px.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Cards and default buttons | 10px |
|  | Compact navigation controls | 8px |
| billing controls | Billing switch | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Lifted interface | `0 0 0 1px rgb(255,255,255), 0 0 0 2px oklab(0.35 0.00426693 0.0447972 / 0.08), 0 2px 1px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 2px 1px -0.5px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 4px 3px -1.5px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 7px 6px -3px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 13px 12px -6px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 25px 24px -12px oklab(0.35 0.00426693 0.0447972 / 0.02), 0 0 48px 4px oklab(0.35 0.00426693 0.0447972 / 0.06), 0 -8px 24px -8px oklab(0.35 0.00426693 0.0447972 / 0.05)` | Softly lifts product panels without making the surrounding cards appear elevated. |

### Surfaces

#### Paper canvas · level 0

**Use:** Continuous light ground throughout the page.

**CSS:** `background: #faf9f8; color: #2b2b2b`

#### Stone grouping · level 1

**Use:** Proof and pricing cards.

**CSS:** `background: #f5f3f0; border-radius: 10px; box-shadow: none`

**Observed:** A barely darker neutral than the page. Flat and borderless; no saturated feature bands.

**Transfer:** Group substantial information without competing with illustrations.

#### Product stage · level 1

**Use:** Wide backing behind interface demonstrations.

**CSS:** `background: #f5f3f0; border-radius: 10px; padding: 64px 16px 0px; overflow: hidden; position: relative`

**Observed:** The panel is centered inside, with its lower edge clipped and progressively softened by blur layers from 0.5px to 16px.

**Transfer:** Keep the important top and middle of a real workflow crisp, allowing its bottom to disappear into the page.

#### Progressive header veil · level 2

**Use:** Behind sticky navigation.

**CSS:** `position: absolute; height: 90px; inset: 0px 0px auto; pointer-events: none`

**Observed:** A transparent-to-soft blur treatment, not an opaque full-width navbar. Layered masks increase blur from 0.5px through 1px, 2px, 4px, 8px and 16px near the upper edge.

**Transfer:** Keep the small navigation controls legible while letting underlying content remain perceptible.

## Components

### Sticky navigation

**Use:** Persistent compact navigation above the editorial layout.

**CSS:** `position: sticky; top: 0px; height: 60px; padding: 10px 0px; z-index: 50`

**Text style:** `action` — Switzer 500 · 14px/20px

**Observed:** Small mark-and-menu group at left; pricing, demo, sign-in and a compact trial action at right. The groups align with the editorial container. Compact controls have 8px corners; the small dark action is 32px tall.

**States:** Declared: hover navigation opacity 0.7.

### Primary button

**Use:** Main conversion action in openings and closings.

**CSS:** `background: #2b2b2b; color: #faf9f8; border-radius: 10px; padding: 10px 16px; height: 40px; display: inline-flex; align-items: center; gap: 8px`

**Text style:** `action` — Switzer 500 · 14px/20px

**Observed:** Text followed by a down-right arrow. The pricing variant is full width, 48px tall with 12px 20px padding and item-title text.

**States:** Declared: hover background-color color-mix(in oklab, #2b2b2b 85%, transparent).

### Secondary button

**Use:** Companion exploratory action.

**CSS:** `background: #f5f3f0; color: #2b2b2b; border-radius: 10px; padding: 10px 16px; height: 40px; display: inline-flex; gap: 8px; align-items: center`

**Text style:** `action` — Switzer 500 · 14px/20px

**Observed:** Same down-right arrow and silhouette as the primary button, but visually recedes into the page.

**States:** Declared: hover background-color color-mix(in oklab, #e4e2dd 60%, transparent).

### Editorial arrow link

**Use:** Explain a mechanism or open a guide beneath supporting copy.

**CSS:** `display: inline-flex; align-items: center; gap: 2px; margin-top: 32px; color: #2b2b2b`

**Text style:** `text-link` — Switzer 500 · 16px/1.25

**Observed:** A tightly attached down-right arrow follows the phrase. A clipped rolling text wrapper supports the link's animated treatment.

### Proof card

**Use:** Compact quantified compatibility or capability proof.

**CSS:** `background: #f5f3f0; border-radius: 10px; padding: 32px; display: flex; flex-direction: column; justify-content: space-between; gap: 48px`

**Text style:** `item-title` — Switzer 500 · 16px/1.5

**Observed:** Title and item-copy description sit above a stat with small unit label, a row of 28px partner icons and an overflow count, then an Editorial arrow link. Cards align their lower content.

**Transfer:** Use genuine counts or a similarly concise proof fact, with recognisable supporting marks rather than decorative badges.

### Feature row

**Use:** A scan-friendly index of capabilities.

**CSS:** `border-top: 1px solid #e4e2dd; padding: 16px 0px`

**Text style:** `item-title` — Switzer 500 · 16px/1.5

**Observed:** Dark title above a muted item-copy sentence; a small down-right arrow is aligned to the right of the combined text block. No filled backing.

### Pricing panel

**Use:** Present an uncomplicated volume-based offer.

**CSS:** `background: #f5f3f0; border-radius: 10px; padding: 32px; display: flex; flex-direction: column; position: relative`

**Text style:** `action` — Switzer 500 · 14px/20px

**Observed:** A narrow price panel pairs with a double-width inclusions panel. Billing controls lead into ruled rows with quantities left and prices right; a full-width Primary button and short terms sit below. A small illustrated bird perches above the narrow panel.

**Transfer:** Retain the side-by-side rates and shared-inclusions structure when the offer supports it, rather than manufacturing multiple feature tiers.

### FAQ row

**Use:** Plain-language objections in the main eight-column text area.

**CSS:** `border-bottom: 1px solid #e4e2dd; min-height: 65px`

**Text style:** `item-title` — Switzer 500 · 16px/1.5

**Observed:** Question button spans the row with 20px vertical padding, a small muted plus at the far right, and no card fill. The list also has a top hairline.

### Footer columns

**Use:** Compact practical navigation before the closing landscape.

**CSS:** `display: grid; grid-template-columns: repeat(12, minmax(0px, 1fr)); gap: 32px`

**Text style:** `caption` — Switzer 500 · 12px/16px

**Observed:** One two-column brand-mark area and five two-column navigation groups. Each has a footer-heading label and gray caption links. Credits move into the lower-right open water of the landscape.

**States:** Declared: hover links color #2b2b2b.

### Gallery tile

**Only for:** downloadable resource galleries

**Use:** Illustration previews with explanatory captions.

**CSS:** `aspect-ratio: 16 / 9; border-radius: 10px; overflow: hidden; position: relative`

**Text style:** `resource-caption` — Inter 500 · 16px/1.5

**Observed:** A faint double edge and soft shadow frame the image; the caption sits 20px below, with a dark inline name followed by muted descriptive sentences.

### Appearance selector

**Only for:** downloadable resource galleries

**Use:** Compare two coordinated illustration appearances.

**CSS:** `background: #faf9f8; border-radius: 8px; padding: 6px 12px; height: 32px; color: #2b2b2b`

**Text style:** `resource-action` — Inter 500 · 14px/20px

**Observed:** Selected control floats within a stone rounded group padded by 4px. The unselected alternative is gray and unfilled; selection has the faint panel shadow.

**States:** Declared: hover color #2b2b2b.

## Imagery and graphics

### Narrative horizon frieze

**Use:** A full-bleed illustrated baseline in the opening experience.

**Observed:** Fine gray ink outlines and pale watercolor fills depict a sequence of people performing small tasks along a stone quay, with water underfoot. Figures are roughly 100px tall on desktop; a tiny flying bird interrupts the large empty field above. Dusty red, ochre, gray and sage remain low saturation.

**Transfer:** Commission or draw original figures enacting the product's underlying activities, not literal floating interface cards. The minimum version is a simple hand-drawn procession of tools, people or objects on a shared textured ground.

**Build:** Use a wide SVG scene with transparent upper space. Arrange 12–18 outlined groups along one baseline in the lower fifth; draw irregular thin paths, add pale translucent wash shapes, then a low band of uneven stones and sparse horizontal water strokes. Keep the background the same off-white as the page and avoid an enclosing rectangle.

### Perched storybook companions

**Use:** Small playful markers above product panels and pricing.

**Observed:** A small robot, running animal, seal and bird perch just above interface or card edges. They share the fine outlined, softly shaded hand-drawn treatment of the larger scenes and stay much smaller than the information they accompany.

**Transfer:** Create original tiny figures or tools that give each chapter a single visual joke or metaphor.

**Build:** Use transparent SVG or raster cutouts around 48–80px wide, anchored by their feet or base to the top edge. Draw with charcoal-gray fine outlines and desaturated washes; let only the silhouette extend beyond the stage.

### Lifted software panels

**Use:** Capability demonstrations.

**Observed:** Light desktop interfaces nearly fill their pale stages, centered at 1024px wide. Fine edges and diffuse shadows separate them from the stone backing. Tables, charts and maps remain understated; their lower region softens and is clipped by the stage.

**Transfer:** Show one real workflow per chapter with an equally calm interface. For a product without a UI, use an evidence-rich process sheet or annotated artifact in the same lifted panel; keep decorative companions outside it.

### Illustrated closing landscape

**Use:** Signature full-width page ending.

**Observed:** A 3:1 landscape rises densely at the left with trees, rocks and painted cottages, then descends into open blue water to the right. Fine ink lines, irregular foliage, red roofs, sage greens, cream rocks and soft horizontal reflections make it feel like a watercolor storybook rather than a vector mascot scene. There is no hard background boundary.

**Transfer:** Make an original landscape or inhabited environment connected to the new product's character. Preserve a dense left silhouette, open right ground and room for credits. A simpler ink-and-wash cluster with trees, objects and horizontal reflections is the minimum acceptable alternative.

**Build:** Compose a transparent 1440×480px illustration: tallest foliage at far left, clustered small structures and irregular rocks across the left half, low islands or objects toward the right. Layer fine hand-drawn paths over translucent sage, dusty brick and pale blue washes; use broken horizontal strokes for water. Fade the perimeter into the paper instead of filling a rectangular sky.

### Day and night illustration pairs

**Only for:** downloadable resource galleries

**Use:** Art-led preview grids.

**Observed:** 16:9 compositions with much open sky and detail near the bottom. Captions describe the setting and small changes after dark; light and dark appearances retain the exact composition.

**Transfer:** Keep geometry fixed between appearances and change environmental lighting and tiny illuminated details rather than swapping to unrelated art.

### Icons

**Observed:** Action arrows are 16px or 18px outlined SVGs, generally 1.8px stroke with round caps. FAQ plus marks use 16px, 1.5px gray strokes. Partner marks are 28px tiles with 8px corners.

**Transfer:** Use restrained rounded-stroke directional icons in charcoal or gray, matching the text role; reserve full-color marks for genuine partner identities.

## Section recipes

How recurring sections are built.

### First screen: Offset promise and illustrated horizon

**Observed:** A 60px compact Sticky navigation sits over Paper canvas. After 96px of top breathing room, a narrow Side-note measure occupies the left third; an 800px main column occupies the right two-thirds. The 48px display headline wraps to two lines, followed 8px later by a 448px-wide gray paragraph and, after 24px, Primary button and Secondary button. A broad empty field separates the text from a full-width Narrative horizon frieze along the bottom. Back to front: continuous paper, ground-and-water artwork, tiny task figures, then type and actions above. Within the first 900px, navigation, note, complete promise, paragraph, both actions and the entire low illustrated horizon are visible; product interface demonstrations begin below the fold.

**Transfer:** Lead with a concrete product promise and an independent contextual note. Create a new low narrative scene from original task-related drawings rather than requiring an existing product image. Resource pages use a distinct editorial opening: 288px top padding, a left-aligned inline dark-and-gray resource-display block, and actions 32px below.

**Avoid:** Do not center the headline over a giant dashboard, fill the empty middle with badges, or enlarge the small figures into a dominant mascot.

**Text style:** `display` — Switzer 500 · 48px/1.25 · tracking -0.025em

### Mechanism chapter

**Observed:** Side note and heading use the opening's four/eight-column alignment at 96px top padding. An 8px support gap and Editorial arrow link establish the argument. After 48px, a Product stage spans all columns with a Lifted software panel inset 64px from its top and a Perched storybook companion above the panel edge.

**Transfer:** Give each chapter a distinct practical benefit, one supporting mechanism and one clear visual demonstration.

**Text style:** `heading` — Switzer 500 · 36px/1.25 · tracking -0.025em

### Quantified proof collection

**Observed:** A shared editorial heading precedes four Proof cards across the container. Dark 30px proof numbers are baseline-paired with small gray unit labels; icon rows and guide links give the counts context.

**Transfer:** Use this device for compatibility, performance or breadth without turning the numbers into enormous isolated typography.

**Text style:** `stat` — Switzer 500 · 30px/1.2 · tracking -0.025em

### Open capability index

**Observed:** An editorial heading and supporting explanation lead into three columns of Feature rows, with 32px gutters and 1px top rules.

**Transfer:** Use short capability titles and one-sentence outcomes for information best scanned rather than demonstrated.

### Rates beside inclusions

**Observed:** Two Stone grouping panels share a row: a 384px price panel and an 800px inclusions panel with 32px between. Inclusions form three columns of tightly tracked feature-bullet text; the narrow panel includes restrained rates, a billing switch and the enlarged Primary button.

**Transfer:** Separate the price decision from what is universally included. Use the compact list treatment for honest details rather than colorful tier badges.

### Plain questions

**Observed:** A short left note accompanies a 36px heading in the right column. A ruled FAQ list starts beneath it, 800px wide, with 65px closed rows and small plus signs.

**Transfer:** Address practical questions about setup, costs and constraints with direct question labels.

### Closing invitation and inhabited footer

**Observed:** After 96px of space, a dark 36px promise and same-size muted reassurance occupy the left, with a Primary button aligned at right. Footer columns follow after a generous 144px separation. A full-bleed Illustrated closing landscape sits below the navigation; small credits occupy its lower-right area. Both page types share this ending.

**Transfer:** Close with one meaningful outcome and one practical reassurance, then let useful links and original illustration make the final impression rather than switching to a dark conversion band.

**Text style:** `heading` — Switzer 500 · 36px/1.25 · tracking -0.025em

### Resource gallery and practical handoff

**Only for:** downloadable resource pages

**Observed:** A resource-heading introduction and Appearance selector sit above two columns of Gallery tiles. A subsequent two-column block pairs resource specifications with numbered installation steps, using 64px between columns and 96px section padding.

**Transfer:** Show the resource, explain what is included, then give brief use instructions before the shared closing invitation.

## Page flow

**Storyline:** Plain promise → concrete demonstrations → breadth and practical details → objections → reassuring invitation → illustrated landing.

### A product marketing page that explains mechanisms before asking for commitment

1. **Promise** — Offset editorial headline, two actions and a full-width narrative frieze.
2. **Product demonstration** — Repeated benefit chapters with pale interface stages and tiny illustrated companions.
3. **Quantified proof** — Four small proof cards pair counts with genuine supporting marks.
4. **Capability breadth** — A three-column ruled index keeps secondary features concise.
5. **Pricing** — Narrow rates panel beside a wider shared-inclusions panel.
6. **Objection handling** — Plain accordion questions in the main text column.
7. **Closing call** — Two-tone outcome and reassurance, compact navigation, then full-width watercolor landscape.

**Transfer:** Adapt the number and order of chapters to the product, preserving the contrast between practical information and humane drawn scenes.

### A resource landing page that helps visitors inspect, acquire and use a visual download

1. **Promise** — Delayed editorial introduction with dark opening clause and muted continuation.
2. **Product preview** — Two-column illustrated gallery with appearance comparison and inline captions.
3. **Practical details** — Specifications alongside numbered setup steps.
4. **Closing call** — The shared two-tone invitation and illustrated footer reconnect the resource to the product.

**Transfer:** Use the scoped Inter recipes and gallery composition for templates, downloads or other inspectable resources; retain the common pale canvas and closing landscape.

## Writing

Plain-spoken, practical and lightly playful. It makes specific claims about mechanisms, costs and limits rather than speaking in superlatives; the illustrations carry most of the whimsy.

**Do not copy:** Do not reuse the brand name, logo, original illustrations, regional identity, proprietary product claims, prices, counts or trial terms. Source examples demonstrate phrasing only and must be replaced by truthful new-product content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; refer to the product by name when clarifying what it does. Use short direct questions for objections.
- **Rhythm:** Headlines are compact statements, usually 5–12 words. Support uses one or two plain sentences, with occasional clipped clauses. Context labels blend directly into a muted continuation rather than becoming all-caps eyebrows.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category or benefit, then contrast it with the frustration removed. | 8–12 words | “Privacy-first web analytics that counts people, not bots” |
| Chapter heading | Explain a concrete outcome in ordinary words. | 5–9 words | “See what every page earns”<br>“Nothing for visitors to consent to” |
| Support | Explain what happens, then clarify an exception or boundary. | 15–35 words | “Headless browsers, datacenter traffic, and referrer spam never reach your stats or your quota. VPN users still count.” |
| Action | A verb plus concrete next step or commitment. | 2–6 words | “Start free for 15 days”<br>“How bot filtering works” |
| Objection | Ask the question as a prospective user would. | 6–10 words | “Will [Brand] slow my site down?” |
| Art caption | A short scene title followed by physical detail and a small observational flourish. | 25–45 words | “Pines on a granite shore, one red cottage, and a sailboat passing a skerry. After dark the cottage window and the masthead light are the only things awake.” |

**Words and phrasing to use:** plainly; every; your; works with; no; what; see; bring; counts

**Avoid:** revolutionary; game-changing; unlock limitless potential; enterprise-grade magic; best-in-class; exclamation-heavy hype

**Rules:**

- State what a product does before naming its technology.
- Pair strong claims with specific mechanisms or honest boundaries.
- Use reassurance to remove a concrete uncertainty, not to repeat the headline.
- Keep functional labels literal; put gentle personality into illustrative captions.

## Do's and Don'ts

### Do

- Align repeated section notes and headings to the same four/eight-column split.
- Use the 448px paragraph measure even under an 800px-wide heading.
- Keep major type at weight 500, with -0.025em tracking on headings.
- Use 32px internal card padding and 32px desktop gutters.
- Place small illustrated companions at panel edges, not inside functional controls.
- Keep proof numbers at 30px and pair them with explanatory units.
- Give the closing reassurance the same 36px scale as the closing promise.
- Use 1px warm-gray rules for feature and FAQ lists.

### Don't

- Do not turn 10px rounded rectangles into pill CTAs.
- Do not use pure black text or pure white as the default page background.
- Do not introduce saturated marketing bands behind headings or pricing.
- Do not apply the lifted interface shadow to every proof card.
- Do not replace 14px sentence-case context notes with widely tracked uppercase eyebrows.
- Do not turn 12px footer navigation into oversized promotional typography.
- Do not scatter colorful generic line icons through the ruled feature index.
- Do not use photographic device mockups or glossy 3D characters in place of ink-and-wash illustration.

## Motion and responsive

### Motion

**Observed:**

- Color and background transitions use 0.15s cubic-bezier(.4, 0, .2, 1); some links declare 0.3s cubic-bezier(0.22, 1, 0.36, 1).
- Navigation action expansion declares max-width, padding and margin over 0.35s cubic-bezier(0.22, 1, 0.36, 1), with opacity over 0.15s.
- The footer boat has a 4s ease-in-out infinite alternate bob. Small scene figures also declare 2.8s glide, 5s hop and 3.6s wobble loops.

**Transfer:**

- Keep ambient movement confined to tiny narrative details so reading remains stationary.
- Use the declared short color transitions for the compact action controls.

**Unknown:**

- Exact movement paths, scroll choreography and whether every declared animation runs in every context.

### Responsive

**Observed:**

- The desktop shell is 1280px with 32px side padding. Classes specify a single-column base, two-column intermediate proof grids and four-column desktop proof grids; exact breakpoint widths are not established.
- Resource display sizes use bounded viewport-relative sizing. Desktop navigation has a separate large-screen treatment.

**Transfer:**

- On narrow screens, place each side note above its corresponding headline and stack actions only when necessary.
- Keep the narrative horizon as a coherent horizontal scene; simplify the number of figures rather than shrinking them into unreadable dots.
- Stack pricing panels and reduce feature and footer columns while preserving their practical reading order.

**Unknown:**

- Exact mobile breakpoint values, mobile navigation construction and narrow-screen illustration art direction.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
