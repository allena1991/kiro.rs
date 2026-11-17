# Aninix — playful output gallery

## Overview

A bright, generous software-marketing style that lets colorful creative output do the persuading. Heavy, tightly set system sans headlines sit above rounded media galleries, with white raised buttons and a mostly white and cool-gray canvas. The tone is practical but enthusiastic, softened by bookish serif customer quotations and a sky-blue community panel. It suits creative tools and products whose results can be shown rather than merely described.

### Essentials

- The promise is a broad black sentence, not a decorative slogan: centered system sans at 86px, weight 800, 1.04 line height and -2px tracking, spanning most of a 1120px content width.
- The first screen is a miniature exhibition: a centered headline, 36px supporting line and small raised action precede two unequal media panels, 625px and 471px wide with a 24px gap; their lower edges continue below the 900px fold.
- Actions look like small white keys: 46px high, 10px corners, 10px 24px 13px padding, bold 18px geometric text and two soft gray shadows; they are not solid accent pills.
- Color belongs primarily to the work on display: white surrounds a gallery of saturated or dark creative scenes, while the marketing chrome stays neutral; indigo #374fd5 is concentrated in tiny attribution chips and identity marks. Pricing alone expands green and indigo into plan-sized fills.
- Proof has a distinct softer register: a 1120px-wide blue-to-white panel with 24px outer corners, a white 64px headline, and staggered white 16px-corner cards holding 20px serif quotes and 16px italic attributions. Carry this proof device into new landing pages; use genuine customer statements or attributed expert observations when output media is scarce.
- The invitation returns at monumental scale without becoming a dark closing band: centered 64px/72px bold text, a 36px/54px community-minded support line, a white raised action and 120px breathing room. A spare light footer remains separate.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Indigo identity | `#374fd5` | `--color-indigo` | accent, surface | Small identity and attribution surfaces, text selection; a full panel fill only for a paid team plan. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky proof wash | `#8ecdf8` | `--color-proof-blue` | background | Visible top of the community panel: #1d9bf0 at 0.5 opacity over white, fading to white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Main page canvas, raised actions and quote cards; reversed text on colored proof and plan surfaces. |
| Icon black | `#000000` | `--color-black` | text, accent | Small utility glyphs and italic quote attributions. |
| Blue black | `#0b1118` | `--color-action-ink` | text | Geometric bold action labels and identity lettering. |
| Headline black | `#171717` | `--color-ink` | text | Large promises, section headings and closing invitations. |
| Charcoal | `#333333` | `--color-body` | text | Supporting lines, testimonial prose and commercial detail. |
| Slate text | `#5c6574` | `--color-secondary` | text | Explanatory paragraphs and small user-count support. |
| Link hover gray | `#62656a` | `--color-hover` | link | Hover color for navigation and footer links. |
| Navigation gray | `#89909a` | `--color-muted` | text, link | Inactive navigation, footer links and social symbols. |
| Pale gray | `#ced3d9` | `--color-faint` | text, accent | Low-emphasis footer copyright and small quotation-source symbols. |
| Gallery backing | `#f0f0f0` | `--color-media-base` | surface | Underlying neutral gallery media surface; artwork covers it. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Paid-plan green | `#1bc47d` | `--color-green` | surface | The individual paid-plan panel, not a general landing-page background. |
| pricing pages | Hairline gray | `#e6eaed` | `--color-edge` | border | Subtle commercial-panel outlines and separators. |
| capability catalogs and pricing pages | Cool card | `#f5f6f8` | `--color-feature-base` | surface | Large capability cards and the entry-level plan panel. |

## Typography

- **system-ui** — Promises, headings, supporting text, navigation and body copy. Heavy contemporary system sans for the broad headlines; regular and medium cuts keep explanatory content direct. Font stack: "system-ui", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif.
- **Euclid Circular A** — Compact bold conversion labels and identity lettering. Rounded geometric sans, noticeably more constructed than the system text. If unavailable, use **DM Sans**. Use 700 for the bold cut and retain the tight action-label tracking. Font stack: "Euclid Circular A", "DM Sans", sans-serif.
- **P22 Mackinac Pro** — Customer quotations and their italic attributions. Warm, broad, gently irregular book serif; medium roman prose with medium italic signatures. If unavailable, use **Lora**. Use 500 roman and italic; preserve the generous quote line height. Font stack: "P22 Mackinac Pro", "Lora", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | system-ui | 800 | 86px | 1.04 | -0.0233em | Centered first-screen promise; single broad line or carefully balanced two-line sentence. |
| closing | system-ui | 700 | 64px | 1.125 | normal | Monumental closing invitation and community-proof headline. |
| heading | system-ui | 500 | 36px | 1.14 | -0.0278em | Opening support line, gallery section lead and capability-card headings. |
| support | system-ui | 500 | 36px | 1.5 | -0.0133em | Generous centered supporting statements below secondary-page promises and closing calls. |
| quote | P22 Mackinac Pro | 500 | 20px | 1.4 | normal | Customer quotations on white cards. |
| action | Euclid Circular A | 700 | 18px | 1.3 | -0.01em | Main raised-button labels. |
| small-support | system-ui | 400 | 18px | 1.438 | normal | Footer links and small count beneath the hero action. |
| navigation | system-ui | 400 | 16px | 1.44 | normal | Header navigation, utility labels and gallery credits. |
| attribution | P22 Mackinac Pro | 500 italic | 16px | 1.5 | normal | Centered quotation authors. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | system-ui | 400 | 40px | 1.12 | -0.02em | Plan price numerals; intentionally lighter than marketing headlines. |
| team-oriented conversion sections | team-action | system-ui | 700 | 36px | 1.5 | -0.0133em | Oversized account-creation button label. |
| capability catalogs | body | system-ui | 400 | 20px | 1.4 | normal | Slate explanatory copy below card headings. |
| pricing pages | commercial-body | system-ui | 400 | 18px | 1.44 | normal | Plan names, billing details, feature lists, table entries and FAQ questions. |

**Notes:**

- The largest promise is the heaviest and most tightly tracked. The 36px headings remain medium rather than bold; the 64px closing lines use normal tracking.
- There is no recurring uppercase eyebrow system. Section hierarchy is carried by scale, spacing and alignment rather than small technical labels.
- Keep the serif confined to human testimony. Medium and Bold font files are represented by their visual weights, not by treating every declared cut as regular.

## Layout

**Density:** Airy at page level, image-dense inside galleries; large quiet intervals separate strong output scenes while control groups remain compact.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Hero action to user-count support. |
| 10px | Action icon-to-label gap and small footer stacks. |
| 12px | Capability heading to paragraph; quote content stack. |
| 16px | Staggered proof-card gutters and commercial panel padding. |
| 20px | Closing headline, support and action stack. |
| 24px | Gallery gutters, capability-card inset and image-to-heading gap. |
| 40px | Opening text-stack gaps, gallery-row gaps and capability grid gutters. |
| 48px | Footer content-to-copyright separation. |
| 60px | Main content top inset within the outer marketing wrapper. |
| 80px | Outer desktop page gutters and commercial section intervals. |
| 120px | Major landing-page section separation and bottom breathing room at closing sections. |

### Containers and grids

- **outer-wrapper**: max width 1280px · side padding 80px. Centered desktop shell. At 1440px the shell begins 80px from each viewport edge; its inner 80px inset yields a 1120px gallery and text field.
- **gallery**: max width 1120px · 2 columns · gap 24px. Unequal image columns with equal row heights; widths respond to the media proportions rather than a rigid equal-card grid.
- **proof-grid**: max width 1040px · 3 columns · gap 16px. Three independent vertical stacks of 336px-wide cards, not a row-aligned matrix.
- **footer**: max width 1280px · side padding 80px. Wider than the main gallery; two resource columns on the left and a compact social cluster on the right.
- **capability-grid** (only for capability catalogs): max width 1160px · 2 columns · gap 40px. Equal 560px-wide cards. This wider content variant uses 60px inner side padding within the outer shell.
- **plan-grid** (only for pricing pages): max width 1120px · 3 columns · gap 24px. Equal plan columns with a colored summary above a white checklist.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 10px |
|  | gallery-and-quotes | 16px |
|  | proof-panel | 24px |
|  | credits | 8px |
| capability catalogs | capability-cards | 40px |
| pricing pages | plan-summary | 11px |
| pricing pages | plan-shell | 22px |
| pricing pages | table-panel | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | raised-action | `0px 2px 7px 0px rgba(104, 116, 123, 0.15), 0px 5px 15px 0px rgba(104, 116, 123, 0.3)` | White primary actions; the main depth cue in otherwise flat marketing chrome. |
| team-oriented conversion sections | team-action | `0px 2px 7px 0px rgba(104, 116, 123, 0.15), 0px 5px 17px 0px rgba(104, 116, 123, 0.2)` | Softer wide shadow under the oversized action. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light page ground.

**CSS:** `background: #ffffff; color: #333333`

**Observed:** White negative space remains visible around every media group and closing call.

**Transfer:** Keep the page frame neutral while allowing demonstrations to supply local color.

#### Gallery backing · level 1

**Use:** Rounded clipping stage behind finished output.

**CSS:** `background: #f0f0f0; border-radius: 16px; overflow: hidden`

**Observed:** Artwork and video cover the backing, often carrying their own light pastel or almost-black scene.

**Transfer:** Fill the panel with a finished product result rather than an empty neutral rectangle.

#### Blue proof panel · level 1

**Use:** Distinctive community-proof field.

**CSS:** `background: linear-gradient(180deg, rgba(29, 155, 240, 0.5) 0%, rgba(29, 155, 240, 0) 100%), #ffffff; border-radius: 24px; padding: 40px; overflow: hidden`

**Observed:** Blue is strongest behind the white heading and fades away beneath the staggered quotation stacks.

**Transfer:** Preserve this gentle blue-to-white descent instead of making the entire section a saturated banner.

#### Capability card · level 1

**Only for:** capability catalogs

**Use:** Large softly rounded feature explanation.

**CSS:** `background: #f5f6f8; border-radius: 40px; padding: 24px 24px 36px; box-shadow: none`

**Observed:** A square product illustration is inset at the top, followed by left-aligned text.

**Transfer:** Let each card teach a single capability using an enlarged, legible product detail.

#### Commercial outline · level 1

**Only for:** pricing pages

**Use:** Comparison-table enclosure.

**CSS:** `background: #ffffff; border: 1px solid #e6eaed; border-radius: 12px; padding: 16px`

**Observed:** Lightweight outlines group dense information without shadows.

**Transfer:** Use faint outlines for comparison and purchasing detail; keep large creative showcases borderless.

## Components

### Navigation bar

**Use:** Persistent site orientation.

**CSS:** `position: sticky; top: 0px; z-index: 10; background: #ffffff; height: 78px`

**Text style:** `navigation` — system-ui 400 · 16px/1.44

**Observed:** Compact identity at left, four muted links centered, two small utility actions at right. The desktop header has a faint bottom division and stays visually white over media.

**Transfer:** Use a small recognizable symbol plus name; keep utilities less prominent than the centered hero action.

### Navigation link

**Use:** Plain navigation and text-only resource actions.

**CSS:** `color: #89909a; text-decoration: none`

**Text style:** `navigation` — system-ui 400 · 16px/1.44

**Observed:** Current secondary-page item becomes blue-black; footer links use the 18px small-support recipe.

**States:** Declared: hover color #62656a with no underline; focus-visible not specified.

**Transfer:** Communicate active position with darker text, not a filled tab.

### Primary button

**Use:** The principal conversion action.

**CSS:** `display: flex; gap: 10px; background: #ffffff; color: #0b1118; border-radius: 10px; padding: 10px 24px 13px; height: 46px; box-sizing: border-box; box-shadow: 0px 2px 7px 0px rgba(104, 116, 123, 0.15), 0px 5px 15px 0px rgba(104, 116, 123, 0.3)`

**Text style:** `action` — Euclid Circular A 700 · 18px/1.3 · tracking -0.01em

**Observed:** Optional small platform symbol precedes the bold label; the short hero version has a count underneath. Text-only purchasing actions keep the same white-key treatment.

**Transfer:** Name the actual first action and include a platform symbol only when the integration matters.

### Gallery tile

**Use:** Display a complete creative result.

**CSS:** `background: #f0f0f0; border-radius: 16px; overflow: hidden; position: relative`

**Observed:** Edge-to-edge video or art; unequal widths in paired rows share a common height. A compact credit sits at the lower-left corner.

**Transfer:** Show distinct results and vary aspect ratio, palette and scene scale while preserving clean edges.

### Creator credit

**Use:** Small source attribution attached to gallery artwork.

**CSS:** `background: #374fd5; color: #ffffff; border-radius: 8px; padding: 4px 8px`

**Text style:** `navigation` — system-ui 400 · 16px/1.44

**Observed:** Inset from the lower-left media edge. First-party work uses indigo; contributed work uses a white chip with charcoal text.

**Transfer:** Attribute real creators without turning the credit into a headline or category tag.

### Quotation card

**Use:** Human proof inside the blue panel.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 28px 24px 24px; display: flex; flex-direction: column; gap: 12px`

**Text style:** `quote` — P22 Mackinac Pro 500 · 20px/1.4

**Observed:** Small pale source symbol above a left-aligned serif quotation, with centered italic attribution below. Card height follows the quotation length; no visible raised-card shadow.

**Transfer:** Use real medium-length testimony and uneven vertical stacks.

### Resource footer

**Use:** A restrained utility ending shared by page types.

**CSS:** `padding: 24px 0px; display: flex; align-items: flex-start; gap: 10px`

**Text style:** `small-support` — system-ui 400 · 18px/1.438

**Observed:** A wide top hairline, two left-hand link columns and three right-hand social glyphs. A small green service-status indicator sits under the resource links; pale 14px copyright sits much lower. Overall desktop depth is 266px.

**Transfer:** Keep service status conditional on a real service; retain the sparse resource and legal hierarchy.

### Capability card

**Only for:** capability catalogs

**Use:** Explain one product capability.

**CSS:** `background: #f5f6f8; border-radius: 40px; padding: 24px 24px 36px; display: flex; flex-direction: column; gap: 24px; width: 560px; box-sizing: border-box`

**Text style:** `heading` — system-ui 500 · 36px/1.14 · tracking -0.0278em

**Observed:** A 512px square UI scene leads; beneath it the heading and slate 20px paragraph are separated by 12px. Paired cards share a row height even when their text lengths differ.

**Transfer:** Show one useful interface operation at a time and keep the caption outside the image.

### Plan summary

**Only for:** pricing pages

**Use:** Present plan identity, price, billing qualification and action.

**CSS:** `background: #f5f6f8; border-radius: 11px; padding: 36px 8px 32px; height: 340px; display: flex; flex-direction: column; align-items: center; justify-content: space-between`

**Text style:** `commercial-body` — system-ui 400 · 18px/1.44

**Observed:** Neutral entry tier, green individual paid tier and indigo team tier. Paid-tier text is white, with billing qualifications at 0.8 white opacity. White primary actions sit at the bottom. Each summary is inset 16px into a faintly outlined 22px-corner shell with a checklist beneath.

**Transfer:** Keep the trio equal in geometry; color denotes plan identity rather than making one card taller.

### Comparison panel

**Only for:** pricing pages

**Use:** Detailed entitlement comparison.

**CSS:** `background: #ffffff; border: 1px solid #e6eaed; border-radius: 12px; padding: 16px; display: flex; flex-direction: column; gap: 16px`

**Text style:** `commercial-body` — system-ui 400 · 18px/1.44

**Observed:** Broad feature-label column and two centered entitlement columns. Fine horizontal rules separate rows; checks indicate inclusion. Separate groups distinguish available work from upcoming work with small status badges.

**Transfer:** Use factual entitlements and clearly label future availability instead of mixing it with released functionality.

### FAQ row

**Only for:** pricing pages

**Use:** Resolve purchasing objections.

**CSS:** `padding: 16px 0px; display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `commercial-body` — system-ui 400 · 18px/1.44

**Observed:** Full-width question with a small plus aligned far right, a hairline beneath and 10px between rows. Closed rows are about 59px high; the heading is 36px and left-aligned.

**Transfer:** Use short genuine questions; make the whole question row the disclosure control.

### Oversized team button

**Only for:** team-oriented conversion sections

**Use:** Large final account-creation action.

**CSS:** `background: #ffffff; color: #0b1118; border-radius: 10px; padding: 10px 24px 13px; height: 77px; box-sizing: border-box; box-shadow: 0px 2px 7px 0px rgba(104, 116, 123, 0.15), 0px 5px 17px 0px rgba(104, 116, 123, 0.2)`

**Text style:** `team-action` — system-ui 700 · 36px/1.5 · tracking -0.0133em

**Observed:** A text-only white key below a two-line 64px invitation. It enlarges the action label rather than changing the component into an accent block.

**Transfer:** Reserve this emphasis for a collective signup action, not every CTA on the page.

## Imagery and graphics

### Finished-output gallery

**Use:** Primary visual proof, beginning within the first screen and continuing through unequal paired and full-width stages.

**Observed:** The opening contrasts a softly lit, glossy multicolor app-symbol sculpture on a pale lavender field with a dark circular interface visualization. Later panels include cinematic interface compositions, a narrow mobile example, a bold yellow graphic animation and a floating white analytics module on mist-gray. Media dominates the page; copy between scenes is minimal.

**Transfer:** Show the new product's best outputs in contrasting light and dark environments. If rendered video is unavailable, use finished still compositions: one tactile abstract product-result object and one designed application scene, followed by varied real outcomes. Do not repeat the same screen in every panel.

**Build:** For the minimum tactile scene, center a rounded square plaque about half the panel width on a pale near-white field. Assemble a product-relevant symbol from overlapping circles and rounded capsules; use warm and cool gradient faces, soft inner highlights and blurred colored contact shadows. Pair it with a near-black designed result scene rather than extending the pastel treatment across all media.

### Blue community field

**Use:** Signature backdrop to the serif proof cards.

**Observed:** A smooth sky-blue top fades vertically to white under three staggered stacks; white cards are bright and flat, and the large white title is centered above them.

**Transfer:** Rebuild the field behind genuine testimony or attributed specialist observations. Keep the softened editorial texture even when there are fewer quotes.

**Build:** Use a white 1120px-wide container with 24px corners and hidden overflow. Add an absolute full-size layer using linear-gradient(180deg, rgba(29,155,240,0.5) 0%, rgba(29,155,240,0) 100%). Above it, place a centered white 64px headline and three independent 336px card columns with 16px gaps and 40px panel padding. Let the gradient disappear into the page near the bottom; do not add a hard lower edge.

### Square capability scenes

**Only for:** capability catalogs

**Use:** Illustrate the single operation explained by each card.

**Observed:** Large square scenes enlarge selected product UI: export controls, team members, a timeline and property inspector, or linked design panels. White UI rectangles sit on cool pale-gray backing, with restrained cyan and indigo active details. Some cards instead use an isolated animated mark on white; these are demonstrations, not decorative badges.

**Transfer:** Recompose meaningful fragments of the new interface at large scale; remove unrelated chrome and retain enough labels to explain the task. Use a simple vector output demonstration where a UI view is less informative.

### Icons

**Observed:** Mostly compact filled SVG utility and social symbols. Platform symbols sit immediately before action text; 32px muted social glyphs form the footer cluster. Pricing uses small checks, plus signs and occasional outlined utilities; a 24px outlined utility uses a 2px round stroke.

**Transfer:** Choose simple filled utility silhouettes for global chrome and clear checks and plus signs for dense commercial information. Keep multicolor symbols limited to relevant platform identity or product artwork.

## Section recipes

How recurring sections are built.

### First screen: Exhibition opening

**Observed:** A white sticky 78px Navigation bar caps a centered 1120px field. The heavy 86px display promise begins around 148px down the page and spans almost the full field, with a single medium 36px support line below after 40px. Another 40px leads to the compact Primary button, then an 18px count with an 8px gap. About 40px after that small support, two Gallery tiles begin side by side, 625px and 471px wide with a 24px gutter and a shared 469px height. Back to front: white canvas, neutral clipped media stages, vivid light and dark output scenes, then small Creator credits near their lower-left edges. Within the first 900px, the entire heading, support, action and count are visible along with most of both main media objects; the tile bottoms and credits continue below the fold.

**Transfer:** Write one broad product promise and stage two different impressive results beneath it. Without video, create a tactile result-object still and a realistic designed output scene. Capability and team-oriented pages keep the same centered heavy promise and broad 36px support but begin paired Capability cards instead of a hero action; a pricing opening uses a short title, tighter 24px title-to-support spacing and equal Plan summaries below.

**Avoid:** Do not replace this composition with a split text-and-dashboard hero, an eyebrow-led startup template, or a full-viewport gradient scene that hides the output gallery.

**Text style:** `display` — system-ui 800 · 86px/1.04 · tracking -0.0233em

### Gallery challenge and reveal

**Observed:** A single centered 36px heading introduces an output sequence. Gallery tiles mix a very wide landscape scene with a narrow portrait, another portrait with a square, and a full-width 1120px by 630px scene. Rows use 40px separation and 24px internal gutters; Creator credits remain low in each tile.

**Transfer:** Lead with a concise question or challenge, then prove it with varied finished outcomes. Let media proportions determine the row composition.

### Monumental invitation

**Observed:** Centered closing text uses the 64px recipe on white, followed by a 36px support line and Primary button with 20px stack gaps. The section is separated from preceding content by 120px. Team-oriented conversion replaces the support line and compact action with an Oversized team button beneath a two-line invitation.

**Transfer:** Return to the visitor's desired outcome in a warm imperative, then give one clear next action. Retain the uncolored canvas and oversized text contrast.

**Text style:** `closing` — system-ui 700 · 64px/1.125

### Soft editorial proof

**Observed:** Blue proof panel contains a centered white 64px heading above three staggered quote columns. Quotation cards contrast bookish roman prose and italic authors with the otherwise system-sans page. The lower blue field fades away before the footer.

**Transfer:** Use this distinctive device for credible human proof; vary quote length naturally instead of equalizing card heights.

**Text style:** `quote` — P22 Mackinac Pro 500 · 20px/1.4

### Light utility ending

**Observed:** Resource footer sits in the wider 1280px field, divided from the main content by a faint top line. Link columns and social symbols share the first row, service status sits below the resources, and copyright is lower and much paler. This treatment ends every page type.

**Transfer:** Keep this ending light even when the preceding media is dark or saturated. Use only a few resource links and a compact social cluster.

### Capability pairs

**Only for:** capability catalogs

**Observed:** Two Capability cards share a 1160px row with 40px gutters and 40px between rows. Each uses an inset square scene, 36px heading and 20px slate explanation; descriptive text stays left aligned.

**Transfer:** Group related benefits in pairs. Let the illustration explain a concrete operation and the paragraph explain its value.

**Text style:** `heading` — system-ui 500 · 36px/1.14 · tracking -0.0278em

### Commercial decision field

**Only for:** pricing pages

**Observed:** Three equal plan columns precede left-aligned 36px comparison and FAQ headings, with 80px between major commercial sections. Plan summaries supply the page's largest marketing color blocks; Comparison panels restore white surfaces and fine outlines. FAQ rows close the content before a generous white interval and Resource footer; no extra closing CTA is inserted.

**Transfer:** Offer a quick commercial choice first, then detailed differentiation and billing objections. Keep future availability visually separate from current entitlements.

## Page flow

**Storyline:** Broad promise → visible outcome or capability proof → confidence-building detail → invitation or objection handling → light utility ending.

### Output-led product landing page

1. **promise** — Centered heavy promise, broad support, raised action and a small adoption count.
2. **product demonstration** — Unequal creative-output pairs begin above the fold, followed by a brief challenge heading and more varied gallery scenes.
3. **closing call** — Large conversational invitation, community-minded support and repeated action.
4. **social proof** — Blue fading panel with staggered serif testimonial cards.
5. **utility ending** — Sparse resource links, status and social cluster.

**Transfer:** Lead with impressive outcomes rather than enumerating features; use human testimony to validate the invitation.

### Commercial choice and objection handling

1. **promise** — Short centered title with a broad free-to-paid value line.
2. **pricing** — Three equal plan shells with neutral, green and indigo summaries and checklists.
3. **comparison** — Fine outlined tables group current, in-development and future entitlements.
4. **objection handling** — Seven restrained closed FAQ rows with plus controls.
5. **utility ending** — White breathing room leads directly to the shared resource footer.

**Transfer:** Use color to distinguish plans, then make the detail reading calm and neutral; end with answers instead of forcing a separate promotional close.

### Explain collective value and encourage group adoption

1. **promise** — Long two-line centered promise and a broad second-person team-oriented support line.
2. **capability chapters** — Paired illustrated cards connect management, collaboration, economics and delivery to specific UI scenes.
3. **closing call** — Two-line 64px invitation and unusually large white account-creation key.
4. **utility ending** — Shared light footer.

**Transfer:** Replace gallery spectacle with concrete shared-work scenarios while retaining scale, neutrality and friendly confidence.

### Explain a product's practical capabilities

1. **promise** — Two-line 86px promise and one 36px supporting sentence.
2. **capability chapters** — Repeated equal card pairs; square UI scenes precede clear headings and explanatory paragraphs.
3. **closing call** — Large imperative headline, community support and compact raised action.
4. **utility ending** — Shared light footer.

**Transfer:** Organize capabilities into coherent pairs and explain each operation in its own image-led card.

## Writing

Direct and enthusiastic, with plain explanations and occasional conversational delight. The product speaks like a useful tool made by fellow practitioners rather than an enterprise procurement platform.

**Do not copy:** Do not reuse Aninix or Figma identity artwork, creator media, customer names or quotations, adoption counts, pricing, plan entitlements or claims. Source examples illustrate voice only; all new claims and testimonials must belong to the new product.

- **Addressing the reader:** Address the visitor as you or your; use we and our for the makers. Actions use straightforward imperatives, and explanations name the operation before its benefit.
- **Rhythm:** Brief action labels and compact feature headings alternate with expansive promise sentences. Most support is one sentence; capability explanations may run to two or three. Questions, sentence fragments and occasional exclamation marks supply warmth.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero promise | Name the desired work and where it becomes possible, or state a broad human benefit. | 4–15 words | “Motion Design within Figma”<br>“Alone you can do so little; together you can do so much.” |
| Supporting line | Explain the benefit in direct everyday language, centered below the promise. | 8–24 words | “Animate your designs wherever you create them”<br>“A suite of handy tools to create UI animations.” |
| Proof bridge | A conversational question makes the visible work feel pleasantly surprising. | 8–15 words | “Hard to believe these animations were actually made in Figma?” |
| Capability heading | Name the operation or use a familiar benefit phrase rather than a grand abstraction. | 2–6 words | “Flawless delivery”<br>“All popular formats” |
| Primary action | Verb plus immediate object; short and literal. | 2–4 words | “Install plugin”<br>“Create your team”<br>“Get started” |
| Closing invitation | Return to the desired result or invite the visitor into a practitioner community. | 6–12 words | “Add animations to your designs now!”<br>“Join the community of animation evangelists” |
| Commercial question | Use the visitor's practical billing concern as a complete question. | 6–14 words | “Do you have monthly and yearly billing options?” |

**Words and phrasing to use:** create; your designs; handy tools; one click; share; simple; support; join; get started

**Avoid:** synergize; paradigm shift; enterprise-grade transformation; unprecedented disruption; cryptic technical slogans

**Rules:**

- Let the artwork establish quality; use the supporting sentence to clarify usefulness.
- Name actual operations and supported outputs instead of stacking abstract superlatives.
- Use community language in invitations and matter-of-fact language in commercial detail.
- Keep creator attributions short and visually subordinate; retain natural human phrasing in authentic quotes.

## Do's and Don'ts

### Do

- Set the main promise at 86px, weight 800, with -2px tracking and a 1.04 line height at desktop.
- Keep the core gallery 1120px wide and use 24px gutters between unequal media panels.
- Use 46px white conversion keys with 10px corners and the two-layer gray shadow.
- Put saturated color inside finished-output scenes and small indigo credits; preserve the surrounding white canvas.
- Retain the blue-to-white proof field and the 20px serif quotation contrast.
- Separate major landing-page blocks with 120px and use 40px intervals within gallery or capability sequences.
- Keep capability explanations at 20px/1.4 in slate below medium 36px headings.
- Use light outlined commercial detail and the wider 1280px utility footer.

### Don't

- Do not make the default CTA an indigo pill; the primary conversion action is a white 10px-corner key.
- Do not apply 40px card corners to the creative gallery; those panels use 16px.
- Do not turn the main promise into thin or widely letterspaced display type; its weight is 800.
- Do not extend paid-plan green and indigo across ordinary marketing sections.
- Do not use serif for navigation or feature explanations; it is the human-proof contrast.
- Do not force the proof cards into equal-height rows; their uneven stacks are part of the editorial character.
- Do not add diffuse glows or heavy shadows to every card; most page surfaces are flat.
- Do not turn the ending into a dark mega-footer or add a giant wordmark; utility links remain pale and compact.

## Motion and responsive

### Motion

**Observed:**

- The main output gallery uses video demonstrations; still scenes present completed states rather than explanatory motion controls.
- Navigation and footer links declare hover color #62656a with no underline. No action or surface transitions are specified.

**Transfer:**

- Keep movement within the output stages so the white navigation and text frame remain stable.
- Provide a polished still composition for each moving result so the gallery remains convincing without playback.

**Unknown:**

- Playback timing, sequencing, scroll-entry animation and easing are not established.
- Expanded FAQ behavior and focus-visible styling are not established.

### Responsive

**Observed:**

- Width breakpoints are declared near 809px, 810px, 959px, 960px and 1199px; team-oriented layouts additionally declare 1279px and 1280px.

**Transfer:**

- Recommended adaptation: stack unequal gallery scenes vertically while retaining their individual aspect ratios and attribution placement.
- Recommended adaptation: collapse capability pairs and quote stacks into one column; reduce the promise scale while keeping its heavy weight and balanced line breaks.
- Recommended adaptation: preserve the comparison table's label-to-entitlement relationship with horizontal overflow rather than shrinking its 18px text into illegibility.

**Unknown:**

- Exact mobile typography, gutters, navigation transformation and sticky behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
