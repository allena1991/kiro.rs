# Subframe — tools as sculptures

## Overview

A light, almost monochrome product style that makes software feel like a beautifully finished physical instrument. Tight grotesk headlines, pale gray sculpted cards and silver-edged interface scenes balance expansive space with detailed product demonstrations. It suits creative and technical tools with tangible workflows, using restrained color inside the work rather than across the marketing canvas.

### Essentials

- Software becomes a floating object: three gently tilted interface panels sit above the opening promise, with silver rims and pale interiors; larger straight-on demonstrations repeat the material language.
- Headlines are compact blocks, not airy banners: 96px/0.92 at weight 500 with -0.035em tracking in the opening, and 88px/1 for capability chapters.
- The opening is centered and fully composed within 900px: a product triptych above a two-line headline, a 576px support measure, paired 64px actions and a small compatibility line.
- Controls and proof have softened-square silhouettes: actions use 9999px squircle corners, large quote and pricing cards use 96px corners, and FAQ rows use 48px corners.
- Color lives inside the work: the marketing canvas stays #f9f9f9 with black-alpha text and #efefef card fields; small blue selection marks and colorful object imagery are confined to demonstrations.
- The ending becomes a pale word sculpture: a brand wordmark spans the available 1344px width below two fine ruled footer rows, with a 160px breathing interval. Use the new product's own name as vector artwork or heavy tightly fitted text.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Primary ink | `#0a0a0a` | `--color-ink` | text, action | Visible result of black at 0.96 over the canvas; headlines, labels and main actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Footer rule | `#161616` | `--color-rule` | border | Visible black at 0.91 over the canvas; thin footer dividers. |
| Body gray | `#707070` | `--color-body` | text | Visible result of black at 0.55 over the canvas; support copy and explanatory paragraphs. |
| Secondary gray | `#9f9f9f` | `--color-secondary` | text | Visible result of black at 0.36 over the canvas; chapter labels and closing descriptor. |
| Action gray | `#eaeaea` | `--color-action` | surface, action | Visible black at 0.06 over the canvas; primary action fill. |
| Soft gray field | `#efefef` | `--color-card` | surface | Visible black at 0.04 over the canvas; proof cards, pricing cards and FAQ containers; also the tone of the monumental footer wordmark. |
| Off-white canvas | `#f9f9f9` | `--color-canvas` | background | Continuous marketing background, also the visible color of the translucent navigation. |
| White | `#ffffff` | `--color-white` | surface, text | Product panel interiors and inverted button text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Selection blue | `#0096ff` | `--color-selection` | border, accent | Thin selection boxes, handles and active-layer markers. |
| product demonstrations | Warm demonstration ground | `#d9d8d3` | `--color-ui-ground` | surface | Warm gray backing inside the example interfaces, not a marketing band. |
| product demonstrations | Demonstration canvas | `#f0f0f0` | `--color-ui-canvas` | surface | Large neutral working canvas inside demonstrations. |
| product demonstrations | Demonstration panel | `#f8f8f8` | `--color-ui-panel` | surface | Inset layers and inspector panels. |

## Typography

- **PP Neue Montreal 3** — All marketing headings, paragraphs, labels and actions. Compact neo-grotesk with a high x-height; medium display cuts appear substantial without becoming bold. If unavailable, use **Inter**. Use 400 and 500; preserve the tight tracking and balanced line breaks. Font stack: "PP Neue Montreal 3", "PP Neue Montreal", Inter, -apple-system, system-ui, "Helvetica Neue", Arial, sans-serif.
- **OT Neue Montreal Semi Squeezed** (only for pricing numerals) — Oversized prices only. Narrow, light-looking grotesk numerals that contrast with the wider medium headings. If unavailable, use **Roboto Condensed**. Use 400 with -0.035em tracking. Font stack: "OT Neue Montreal Semi Squeezed", "Roboto Condensed", "PP Neue Montreal 3", Inter, "Helvetica Neue Condensed", sans-serif.
- **Inter** (only for product demonstrations) — Interface content within product scenes. Small, readable interface sans distinct from the marketing scale. Font stack: "Inter", system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| process-number | PP Neue Montreal 3 | 500 | 184px | 1 | -0.035em | Oversized ordinal alongside process text. |
| hero | PP Neue Montreal 3 | 500 | 96px | 0.92 | -0.035em | Centered two-line opening promise. |
| display | PP Neue Montreal 3 | 500 | 96px | 1 | -0.035em | Large narrative transition and closing call. |
| chapter | PP Neue Montreal 3 | 500 | 88px | 1 | -0.035em | Left-aligned capability chapter headline. |
| heading | PP Neue Montreal 3 | 500 | 64px | 1 | -0.035em | Proof, pricing, FAQ and integration section headings. |
| quote | PP Neue Montreal 3 | 500 | 48px | 52px | -0.03em | Large quotation blocks inside soft gray cards. |
| closing-descriptor | PP Neue Montreal 3 | 500 | 40px | 1.1 | -0.025em | Centered short descriptor beneath the closing display. |
| eyebrow | PP Neue Montreal 3 | 500 | 28px | 32px | -0.02em | Sentence-case chapter label; also short process step titles. |
| body-lead | PP Neue Montreal 3 | 400 | 28px | 36px | -0.002em | Explanatory captions beneath large demonstrations. |
| body-lead-emphasis | PP Neue Montreal 3 | 500 | 28px | 36px | -0.002em | Black inline benefit phrase at the start of a gray demonstration caption. |
| body | PP Neue Montreal 3 | 400 | 24px | 32px | -0.0025em | Opening support, pricing features and FAQ answers. |
| body-emphasis | PP Neue Montreal 3 | 500 | 24px | 32px | -0.0025em | FAQ question text. |
| nav | PP Neue Montreal 3 | 500 | 24px | 1 | -0.01em | Underlined header links. |
| body-small | PP Neue Montreal 3 | 400 | 20px | 1.4 | -0.003em | Compact feature-grid descriptions and explanatory notes. |
| action | PP Neue Montreal 3 | 500 | 20px | 1.2 | -0.01em | Primary and secondary conversion labels. |
| footer | PP Neue Montreal 3 | 400 | 18px | 24px | -0.003em | Footer navigation and small supporting labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing sections | price | OT Neue Montreal Semi Squeezed | 400 | 96px | 1 | -0.035em | Plan amount, with the billing unit aligned at its baseline. |

**Notes:**

- Keep medium weight 500 throughout the headline hierarchy; use scale and line breaks rather than bold weight to create emphasis.
- Display tracking is -0.035em; quote tracking relaxes to -0.03em and body copy stays at -0.1px.
- Chapter labels are 28px sentence case in secondary gray, not small uppercase technical tags.
- Pair an ink medium phrase with regular gray copy on the same baseline in demonstration captions.

## Layout

**Density:** Airy marketing rhythm surrounding dense product scenes; large pauses separate tightly composed text and media groups.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Narrow separation between FAQ rows. |
| 8px | Footer link stacks and compact internal pairs. |
| 12px | Gap between opening conversion actions. |
| 16px | Eyebrow-to-headline gap and adjacent card gutters. |
| 24px | Small support groups and compatibility-line separation. |
| 32px | Desktop section side padding and media-to-caption gap. |
| 48px | Headline group to actions, quote-card padding and process-grid gaps. |
| 64px | Pricing-card padding and major media-group gaps. |
| 96px | Large heading-to-content pauses and footer row separation. |
| 160px | Major section vertical padding and footer artwork breathing space. |

### Containers and grids

- **reading-container**: max width 1024px · side padding 32px. Centered container with left-aligned chapter headings, captions and process blocks.
- **wide-container**: max width 1280px · side padding 32px. Demonstration stages, proof cards, pricing pairs and FAQ rows.
- **hero-copy**: max width 768px. Centered headline block; support copy narrows to 576px.
- **chapter-measure**: max width 672px. Restricts chapter headings to compact two-line blocks.
- **feature-grid**: max width 1024px · 3 columns · gap 16px. Small illustrated benefits; 24px row gap and 16px item padding.
- **process-grid**: max width 1024px · 2 columns · gap 48px. Ordinal-led steps in a two-by-two composition.
- **footer-grid**: 3 columns · gap 16px · side padding 48px. Broad three-column navigation and metadata bands, with nested pairs in the last column.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 9999px (pill) |
|  | proof-and-pricing | 96px |
|  | faq | 48px |
|  | demo-stage | 24px |
| product demonstrations | ui-panels | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| product demonstrations | demo-float | `0px 4px 32px -4px rgba(0,0,0,0.08), 0px 2px 8px -2px rgba(0,0,0,0.08), 0px 0px 0px 1px rgba(0,0,0,0.04) inset` | Separated browser and canvas windows, not ordinary marketing cards. |

### Surfaces

#### Page canvas · level 0

**Use:** Continuous light background.

**CSS:** `background: #f9f9f9; color: rgba(0,0,0,0.96)`

**Observed:** No alternating dark bands; tonal distinctions come from objects and cards.

**Transfer:** Retain one uninterrupted neutral ground across the whole narrative.

#### Sculpted gray card · level 1

**Use:** Quotes and pricing content.

**CSS:** `background: rgba(0,0,0,0.04); border-radius: 96px; corner-shape: squircle; box-shadow: none`

**Observed:** Broad softened-square corners rather than circular arcs; no outline or elevated shadow.

**Transfer:** Use generous text padding and contrasting card proportions instead of badges or ornamental borders.

#### Translucent header · level 2

**Use:** Persistent navigation.

**CSS:** `background: rgba(249,249,249,0.8); backdrop-filter: blur(12px)`

**Observed:** A subtle veil preserves the pale canvas while passing over media.

**Transfer:** Keep it borderless and nearly invisible until content passes behind it.

#### Demonstration stage · level 1

**Only for:** product demonstrations

**Use:** Wide feature demonstrations.

**CSS:** `background: rgba(0,0,0,0.04); border-radius: 24px; overflow: hidden; padding: 8px`

**Observed:** A pale frame holds detailed interface content in a roughly 16:9 field.

**Transfer:** Frame the actual workflow tightly enough for its interaction to be understood.

## Components

### Navigation

**Use:** Persistent brand and two utility actions.

**CSS:** `position: sticky; top: 0px; z-index: 50; display: flex; align-items: center; justify-content: space-between; padding: 32px 48px; background: rgba(249,249,249,0.8); backdrop-filter: blur(12px)`

**Text style:** `nav` — PP Neue Montreal 3 500 · 24px/1 · tracking -0.01em

**Observed:** Compact black wordmark at left; two underlined links separated by 32px at right. Overall desktop height is 88px.

**Transfer:** Use the new brand's compact mark, with only the essential entry and conversion links.

### Primary button

**Use:** Main conversion throughout the narrative.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 64px; padding: 0px 32px; background: rgba(0,0,0,0.06); color: rgba(0,0,0,0.96); border-radius: 9999px; corner-shape: squircle`

**Text style:** `action` — PP Neue Montreal 3 500 · 20px/1.2 · tracking -0.01em

**Observed:** Content-width in opening and closing; fills the pricing-card content width. A smaller interlude variant is 56px high with 24px horizontal padding.

**States:** Declared: hover background-color #000000e8 and color #fff; focus-visible solid 2px outline with 2px offset in #000000e8; active scale 0.97.

### Secondary button

**Use:** Parallel lower-commitment conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 64px; padding: 0px 32px; background: transparent; color: rgba(0,0,0,0.96); border-radius: 9999px; corner-shape: squircle`

**Text style:** `action` — PP Neue Montreal 3 500 · 20px/1.2 · tracking -0.01em

**Observed:** Text followed by a small right arrow; visually lighter than the filled action and placed beside it.

**States:** Declared: hover background-color #0000000a; focus-visible solid 2px outline with 2px offset in #000000e8; active scale 0.97.

### Underlined utility link

**Use:** Header utility navigation.

**CSS:** `color: rgba(0,0,0,0.96); text-decoration: underline; text-underline-offset: 4px; text-decoration-thickness: 1px`

**Text style:** `nav` — PP Neue Montreal 3 500 · 24px/1 · tracking -0.01em

**Observed:** Plain text rather than a boxed navigation control.

**States:** Declared: hover opacity 0.6; focus-visible solid 2px outline with 4px offset in #000000e8.

### Inline benefit caption

**Use:** Interpret a demonstration directly beneath its media.

**CSS:** `max-width: 875px; padding-left: 16px; color: rgba(0,0,0,0.55)`

**Text style:** `body-lead` — PP Neue Montreal 3 400 · 28px/36px · tracking -0.002em

**Observed:** Starts with an ink medium phrase using body-lead-emphasis, immediately followed by regular gray explanation. Full caption remains one paragraph.

**Transfer:** State the benefit first, then describe the concrete interaction without adding a separate title.

### Quote card

**Use:** Large-format social proof.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 24px; padding: 48px; background: rgba(0,0,0,0.04); border-radius: 96px; corner-shape: squircle`

**Text style:** `quote` — PP Neue Montreal 3 500 · 48px/52px · tracking -0.03em

**Observed:** Oversized quotation text is the entire visual payload; narrow tall cards mix with wider short cards in an asymmetric mosaic.

**Transfer:** Let quote length determine card proportion rather than forcing equal-height testimonial tiles.

### Pricing card

**Use:** Compare a small number of plans.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; gap: 48px; padding: 64px; background: rgba(0,0,0,0.04); border-radius: 96px; corner-shape: squircle`

**Text style:** `body` — PP Neue Montreal 3 400 · 24px/32px · tracking -0.0025em

**Observed:** Two equal cards separated by 16px; plan name, squeezed price with billing suffix, feature list, then full-width Primary button. Both plans receive the same restrained surface.

**Transfer:** Maintain equal visual status unless the new offer has a real reason to highlight one tier.

### FAQ row

**Use:** Compact objection handling with expandable answers.

**CSS:** `background: rgba(0,0,0,0.04); border-radius: 48px; corner-shape: squircle; overflow: hidden`

**Text style:** `body-emphasis` — PP Neue Montreal 3 500 · 24px/32px · tracking -0.0025em

**Observed:** Native details/summary construction; question inset 32px vertically and 48px horizontally, chevron at far right. Closed rows are 96px high, separated by 4px. Answers use body text.

**Transfer:** Keep questions short enough to scan as one line on desktop; allow height to grow for wrapping.

### Footer band

**Use:** Navigation and metadata at the end.

**CSS:** `display: grid; grid-template-columns: repeat(3, minmax(0px, 1fr)); gap: 16px; border-top: 1px solid rgba(0,0,0,0.91); padding-top: 16px`

**Text style:** `footer` — PP Neue Montreal 3 400 · 18px/24px · tracking -0.003em

**Observed:** Two ruled bands separated by 96px. The first groups brand, product links, resources and social links; the second groups a short identity line, legal links, location and copyright. Pale wordmark artwork anchors the space beneath.

## Imagery and graphics

### Floating silver interface triptych

**Use:** Signature opening object and large capability demonstrations.

**Observed:** Three rounded interface windows float on the off-white ground; the center sits higher while the sides tilt in opposing directions. Their thin silver-gray rims carry sharp white highlights and darker inner edges. Interiors remain pale, with small photographs and blue selection accents; there is no large ambient colored glow.

**Transfer:** Show three complementary states of the new product. If finished interface media is unavailable, build simplified but meaningful panels containing the product's inputs, working state and result; retain the metallic edging and dimensional staging.

**Build:** Use three clipped rounded rectangles about 210–250px wide in the opening, with 16–24px corners. Nest a 2px highlight edge, a 2px gray rim and a 1px dark inner stroke; use layered white and black-alpha inset shadows to suggest polished metal. Rotate the side panels in opposite directions by roughly 6–9deg, leave the middle nearly upright, and stagger their vertical positions. Keep their combined span near 720px and height near 280px at desktop. Scale the same construction into a nearly full-width straight-on window for chapter media.

### Monumental pale wordmark

**Use:** Signature ending beneath the utility footer.

**Observed:** A very heavy tightly fitted wordmark fills the 1344px inner width and is 234px high, barely darker than the page. It is flat artwork, not a heading in the text scale.

**Transfer:** Render the new brand name as an oversized pale vector or width-fitted heavy grotesk wordmark. For a long name, use a compact letterform rather than shrinking it into ordinary footer text.

**Build:** Place an SVG wordmark in a full-width wrapper with 160px top padding and 48px side clearance at desktop. Set the fill to the soft gray field, fit the viewBox tightly to the letterforms and preserve its aspect ratio. For text-only implementation, use a heavy grotesk, negative tracking and width fitting; keep the low contrast and full-width silhouette.

### Workflow detail scenes

**Only for:** product demonstrations

**Use:** Capability explanations and compact feature groups.

**Observed:** Large pale interface canvases show layers, browsers, inspectors and chat alongside the resulting design. Warm gray content grounds host small product-object photographs, including a red radio and a silver camera; blue outlines identify active elements. Smaller scene fragments are enlarged and clipped into rounded rectangular thumbnails.

**Transfer:** Use real work relevant to the new product, not generic dashboard decoration. Show a clear before/after or selected object, with enough contextual controls to explain the action; reserve saturated color for the work itself.

### Icons

**Observed:** Marketing icons are sparse: a 20px right arrow accompanies the secondary action and 24px chevrons sit at the far edge of FAQ rows. Outline SVGs use 2px rounded strokes in primary ink. Dense smaller controls belong inside interface scenes.

**Transfer:** Use simple rounded-stroke directional symbols; keep decorative iconography out of headlines and quote cards.

## Section recipes

How recurring sections are built.

### First screen: Floating-tool opening

**Observed:** The Translucent header sits over Page canvas. A centered triptych occupies the upper third of the first screen, below the navigation; it is followed by a two-line hero headline constrained to 768px. The hero uses 96px type with 0.92 line height, occupying roughly half the viewport width. A two-line support paragraph follows after 16px, constrained to 576px. After 48px, Primary button and Secondary button sit in one row with a 12px gap; a small compatibility line with tiny partner marks follows after 24px. All of the object, headline, support, actions and compatibility line are visible within the first 900px. The next narrative interlude falls below the first screen.

**Transfer:** Make the upper object communicate the product's essential working modes, then give one compact result-oriented promise. Other landing-page types can reduce the number of panels but should retain a sculptural product object above the centered promise and the same restrained paired actions.

**Avoid:** Do not replace the floating object with a full-bleed background image, put copy beside it in a conventional split hero, or push the conversion row below the first screen.

**Text style:** `hero` — PP Neue Montreal 3 500 · 96px/0.92 · tracking -0.035em

### Three-word interlude

**Observed:** Three single-word lines use the chapter scale in very pale black-alpha text, centered over a narrow 28px support paragraph with a 40px gap and a smaller Primary button below.

**Transfer:** Condense the new product's conceptual model into a short vertical stack; use it as a pause between the promise and deeper explanation.

### Capability chapter

**Observed:** A left-aligned eyebrow and chapter headline sit in the reading-container with 16px between them and a 672px headline measure. A wide, silver-edged demonstration follows after 64px. An explanatory paragraph and further workflow scenes continue in the narrower 1024px container, with Inline benefit captions beneath media.

**Transfer:** Give each major capability one clear headline and one demonstrable interaction. Reuse the chapter structure without requiring the same number of chapters.

**Text style:** `chapter` — PP Neue Montreal 3 500 · 88px/1 · tracking -0.035em

### Compact capability grid

**Observed:** Three columns within 1024px, with 16px horizontal and 24px vertical gaps. Small 96px illustrations sit above 20px explanatory text, often with a short black lead phrase. Four-column workflow fragments form a denser variant.

**Transfer:** Use close-up tool fragments or simple meaningful object illustrations for secondary benefits, not brightly colored feature-icon tiles.

### Ordinal process

**Observed:** A display headline introduces a two-column grid of four steps. Each step pairs a 184px numeral in a 128px-wide field with a 28px title and a short gray list; columns and rows are separated by 48px.

**Transfer:** Make a complex workflow feel navigable with a few concrete verbs and oversized ordinals. Preserve the numeral-to-text contrast rather than shrinking it into ordinary numbered bullets.

**Text style:** `process-number` — PP Neue Montreal 3 500 · 184px/1 · tracking -0.035em

### Quotation mosaic

**Observed:** A 64px heading sits above an asymmetric field of Quote cards within 1280px. A narrow tall card is paired with wider stacked cards, then the proportions reverse. Gutters stay 16px while the quotations use 48px type.

**Transfer:** Arrange authentic statements by their length and rhetorical strength; keep the mosaic tonal and text-led.

### Equal-plan comparison

**Observed:** A 64px heading introduces two Pricing cards within 1280px. Large squeezed amounts sit beside 28px billing units; features use 24px body text with 16px gaps. A centered 20px explanatory note and a text link follow below.

**Transfer:** Keep the plan comparison simple and let the actual offer provide hierarchy rather than an unrelated accent color.

### Rounded objection list

**Observed:** A 64px heading leads a 1280px stack of FAQ rows. Questions are visible in the resting state; answers expand within the same pale field.

**Transfer:** Use direct user questions about fit, compatibility and practical constraints rather than repeating feature slogans.

### Closing call and wordmark footer

**Observed:** A centered 96px display promise returns within a 576px measure, followed by a 40px gray descriptor after 24px and paired actions after 48px. The footer then opens with 144px top padding and 48px side clearance, two Footer bands and the Monumental pale wordmark beneath a 160px pause.

**Transfer:** Restate the central outcome in new words, repeat the same conversion paths, and end with the new brand's pale full-width name. Keep the monumental artwork as an actual final visual event, not a small logo beside legal text.

**Text style:** `display` — PP Neue Montreal 3 500 · 96px/1 · tracking -0.035em

## Page flow

**Storyline:** compact promise → conceptual model → workflow demonstrations → practical process → human proof → offer and objections → repeated action → monumental brand ending

### A product marketing landing page that connects an abstract promise to visible working behavior

1. **Promise** — Floating interface triptych above a centered benefit headline, support line and paired conversion actions.
2. **Conceptual model** — A pale three-word stack compresses the product into a memorable set of modes.
3. **Capability chapters** — Oversized left-aligned headings introduce large product scenes, then narrower captioned interactions and small supporting grids.
4. **Ecosystem reassurance** — Centered supporting copy and softly rounded integration cards show compatibility.
5. **Process** — A broad display statement followed by oversized numbered steps makes the workflow legible.
6. **Social proof** — Large quotations form an asymmetric low-contrast card mosaic.
7. **Offer** — Two equally styled plans communicate price and practical inclusions.
8. **Objection handling** — A compact stack of pale expandable questions resolves fit and implementation concerns.
9. **Closing call** — Centered promise, short descriptor and the same paired actions return.
10. **Brand ending** — Ruled utility bands give way to a very large, very pale wordmark.

**Transfer:** Adapt the number and ordering of demonstrations to the new product. Keep the contrast between sculptural product scenes, compact explanatory captions, large text-led proof and the monumental ending.

## Writing

Plainspoken and assured, with the enthusiasm of someone who actually uses the tool. Claims are grounded in visible actions and workflow benefits rather than abstract transformation.

**Do not copy:** Do not reuse the Subframe name or wordmark, partner marks, product-specific claims, plan prices, customer quotations, compatibility promises or example project artwork. Replace them with truthful content and assets for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your work. Name the product when defining its category; use we sparingly when explaining what the tool provides.
- **Rhythm:** Short sentence-case headlines commonly run four to seven words and end with a period. Supporting copy uses one or two concrete sentences; brief imperative phrases lead explanatory captions.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Combine two familiar actions into one compact outcome. | 6–8 words | “Design & build in one tool.” |
| Capability headline | A short action or category statement with a specific object. | 4–7 words | “Preview & edit your live app.”<br>“Infinite canvas built for code.” |
| Benefit caption | A terse benefit phrase followed immediately by a practical explanation. | 2–6 word lead; 15–30 word explanation | “Capture to canvas.”<br>“Select an element in the browser, then copy & paste to the canvas as editable designs.” |
| Primary action | Name the exact next action or destination. | 3–4 words | “Download for macOS”<br>“Open in web” |
| Process step | Single active verb with a period, followed by short task fragments. | 1 word title; 2–4 words per task | “Explore.”<br>“Design from scratch.” |
| Question | Ask the practical question a prospective user would ask. | 4–12 words | “Does my code leave my machine?” |

**Words and phrasing to use:** build; explore; iterate; connect; ship; your; directly; live; one tool; full control

**Avoid:** revolutionary; supercharge; unlock limitless potential; game-changing; seamless synergy

**Rules:**

- Describe the interaction that produces the benefit, not just the benefit alone.
- Use ampersands in compact headlines when pairing two actions.
- Keep section labels descriptive and sentence case.
- Use short fragments for process lists; reserve full sentences for explanations.
- Make button labels specific enough to reveal the platform or destination.

## Do's and Don'ts

### Do

- Keep the opening headline at 96px, weight 500, with -0.035em tracking and 0.92 line height.
- Keep chapter headings within 672px so the block remains compact.
- Use 160px vertical section padding to separate major narrative changes.
- Use 16px gutters between broad gray cards instead of heavy borders.
- Keep quote and pricing surfaces shadowless with 96px squircle corners.
- Use 28px captions with a black medium lead phrase and gray regular continuation.
- Preserve the 184px process numerals when introducing a practical workflow.
- Finish with pale full-width brand artwork below the ruled footer.

### Don't

- Do not turn the default marketing canvas into alternating black and colored bands.
- Do not use saturated brand-color fills for conversion buttons; the resting action fill is black at 0.06.
- Do not apply 96px card rounding as ordinary circular arcs when squircle shaping is available.
- Do not use tiny uppercase monospaced chapter labels; the label role is 28px sentence-case sans.
- Do not put glossy shadows on quote or plan cards; dimensional lighting belongs to product objects.
- Do not replace the asymmetric quotation mosaic with avatar-led equal-size review tiles.
- Do not let screenshot typography determine the marketing scale; the surrounding captions are 24–28px.
- Do not render the final wordmark in high-contrast ink; it should read as a pale silhouette.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions animate background-color, color and transform over 0.15s with cubic-bezier(.165,.84,.44,1).
- Declared utility-link opacity transitions use 0.15s with cubic-bezier(.4,0,.2,1).
- The opening uses a sticky viewport-height product stage; the objects are staged as floating, tilted panels.

**Transfer:**

- Preserve the short button color inversion and 0.97 press-scale response.
- If animating the opening object, keep the interface content legible and the promise stable while the product stage changes.

**Unknown:**

- The exact scroll choreography, keyframe timing and behavior between settled scenes are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 767px, 768px, 769px, 1024px, 1280px and 1536px.
- Mobile classes reduce section side padding from 32px to 16px, stack the conversion row and pricing cards, and reduce process numerals to 112px.
- The opening includes a height-sensitive type variant below 820px viewport height.

**Transfer:**

- For narrow screens, preserve the centered product-object-over-promise relationship; simplify panel overlap rather than making the interface details unreadably small.
- Stack plan cards and process steps; retain the pale footer wordmark fitted to the new width.
- Reduce the 160px chapter padding to the declared mobile 64px rhythm where applicable.

**Unknown:**

- Rendered mobile compositions and exact headline sizes at each breakpoint are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
