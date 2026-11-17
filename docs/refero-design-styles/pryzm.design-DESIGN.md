# Pryzm — luminous specimens in darkness

## Overview

A black gallery for tactile digital experiments, with vivid glass, grain and blurred organic imagery suspended in ample negative space. Rounded geometric headings and small neutral interface text give the work a friendly, tool-like clarity rather than a luxury or sci-fi tone. It suits creative software and visually expressive products: spacious at the chapter level, compact inside controls and cards.

### Essentials

- The opening is a specimen field, not a centered billboard: rounded images float at mixed sizes across a black 900px stage, with a two-line 48px Poppins headline anchored low left and a separate 280px support-and-action column low right.
- Headlines feel geometric and approachable: Poppins 600 with -0.02em tracking, 48px/1.05 in the opening, 36px/40px for major chapters and 30px/36px for gallery and integration headings.
- Controls stay deliberately miniature: main actions are 32px high, 8px radius, 10px horizontal padding and Inter 12px/19.5px at 500; header actions shrink to 24px high rather than becoming oversized pills.
- Color belongs to the specimens, not the furniture: the canvas is #000000, card backing #141414, text #fafafa or 60% white, and chromatic imagery occupies isolated islands surrounded by black. Keep navigation, headings and conversion controls achromatic.
- Tactile output must carry the visual identity: combine grain, soft-focus organic imagery and refracted vertical light in 14px rounded image windows; use an original textured abstract study when the product has no natural visual output.
- The lower page returns to atmosphere: include a darkened organic image field and a broad image-backed footer, balanced by a plain black closing call with a centered 48px/1 headline. This contrast is a signature device, not a demand for a particular section order.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action silver | `#e5e5e5` | `--color-primary` | action, surface | Primary button fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black canvas | `#000000` | `--color-canvas` | background, surface | Page canvas, pricing cards, email fields and dark image overlays. |
| Quiet action fill | `#0b0b0b` | `--color-quiet-action` | action, surface | Secondary outlined button: 4.5% white over black. |
| Charcoal backing | `#141414` | `--color-card` | surface | Gallery cards, demonstration frames and glass badges. |
| Button ink | `#171717` | `--color-button-ink` | text | Dark text on silver primary actions. |
| Subtle edge | `#1c1c1c` | `--color-hairline` | border | Visible 11% white hairline on black; preserve the alpha recipe over images and charcoal. |
| Raised charcoal | `#262626` | `--color-secondary` | surface, action | Solid secondary actions and the visible result of 15% white header button fills over black. |
| Muted gray | `#999999` | `--color-muted` | text | Supporting text and captions; white at 0.6 alpha over black produces this visible tone. |
| Navigation gray | `#b3b3b3` | `--color-nav-text` | text, link | Header links; white at 0.7 alpha over black. |
| Soft white | `#fafafa` | `--color-foreground` | text | Headings, card names and principal interface copy. |
| Pure white | `#ffffff` | `--color-white` | text, accent | Header button text and the source hue for translucent white edges and fills. |

## Typography

- **Poppins** — Marketing headlines. Rounded geometric sans with a broad, friendly lowercase, set semibold. Font stack: "Poppins", sans-serif.
- **Inter** — Body copy, controls, navigation, card names and price numerals. Compact neutral grotesk; regular paragraphs contrast with medium controls and semibold labels. Font stack: "Inter", system-ui, sans-serif.
- **Geist Mono** (only for technical demonstrations and specimen labels) — Code examples and small two-line labels beneath opening specimens. Small monospaced technical annotations, subordinate to artwork. Font stack: "Geist Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 600 | 48px | 1.05 | -0.02em | Two-line opening promise. |
| closing-display | Poppins | 600 | 48px | 1 | -0.02em | Centered closing invitation, balanced across two lines. |
| heading | Poppins | 600 | 36px | 40px | -0.02em | Major capability, pricing, questions and subscription headings. |
| heading-compact | Poppins | 600 | 30px | 1.2 | -0.02em | Gallery and integration chapter headings. |
| price | Inter | 600 | 30px | 1.2 | -0.025em | Price numerals beside smaller baseline-aligned billing text. |
| lead | Inter | 400 | 20px | 1.4 | normal | Muted section support paragraphs. |
| question | Inter | 500 | 16px | 1.5 | normal | Always-visible FAQ questions. |
| body | Inter | 400 | 14px | 20px | normal | Opening support, lists and footer links. |
| nav | Inter | 500 | 14px | 20px | -0.025em | Header navigation. |
| card-title | Inter | 600 | 14px | 20px | -0.025em | Gallery specimen names. |
| answer | Inter | 400 | 14px | 1.625 | normal | Longer explanatory FAQ answers. |
| eyebrow | Inter | 500 | 12px | 16px | 0.025em, uppercase | Muted chapter labels. |
| action | Inter | 500 | 12px | 1.625 | normal | Buttons and compact conversion links. |
| caption | Inter | 400 | 12px | 16px | normal | Image captions, card descriptions, reassurance and footer credits. |
| badge | Inter | 500 | 12px | 16px | normal | Small release announcement above the opening headline. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| technical demonstrations | code | Geist Mono | 400 | 12px | 1.625 | normal | Short code sample over a live visual demonstration. |

**Notes:**

- Poppins is reserved for marketing headings; Inter handles small text even where geometric styling might suggest otherwise.
- Keep display tracking at -0.02em; Inter navigation, card titles and prices tighten slightly further to -0.025em.
- The opening support is unusually small at 14px, while chapter support expands to 20px. Preserve this split rather than applying one paragraph scale everywhere.

## Layout

**Density:** Airy chapters with dense, small controls: substantial black intervals separate compact informational groups.

### Spacing

| Value | Use |
| --- | --- |
| 6px | Email form and header control gaps. |
| 8px | FAQ question-to-answer spacing and list item gaps. |
| 12px | Eyebrow-to-heading and heading-to-support spacing; gallery text padding and paired action gaps. |
| 20px | Gallery grid gutters and card content groups. |
| 24px | Container side padding and pricing card padding. |
| 28px | Subscription form offset below supporting copy. |
| 40px | Heading-to-gallery spacing and FAQ column gap. |
| 64px | Desktop footer grouping and opening bottom clearance. |
| 112px | Standard desktop section vertical padding. |
| 128px | Closing call vertical padding and footer top padding. |

### Containers and grids

- **content-container**: max width 1152px · side padding 24px. Centered outer box; at 1440px it yields 1104px of usable content and 168px to the first content edge.
- **heading-measure**: max width 576px. Left-aligned chapter introductions; balance against an action at the far right.
- **opening-copy**: max width 672px · gap 48px. Wide headline block opposite a 280px support column, bottom-aligned.
- **gallery-grid**: 4 columns · gap 20px. Equal specimens in a four-column desktop gallery, each 261px wide.
- **pricing-grid**: max width 768px · 2 columns · gap 24px. Centered equal-height plan cards rather than a full-width comparison table.
- **questions-grid**: 2 columns · gap 40px. 320px title column and a 744px answer column within the content container.

## Corner radius

| Element | Radius |
| --- | --- |
| actions and inputs | 8px |
| inner images and pricing cards | 14px |
| outer gallery and media frames | 18px |
| badges and segmented control | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| image edge | `inset 0 0 0 1px rgba(255,255,255,0.1)` | A faint inner edge on rounded gallery artwork. |
| recommended plan | `0 0 0 1px rgba(250,250,250,0.15)` | A restrained additional outline for the paid plan; not a colored glow. |

### Surfaces

#### Black canvas · level 0

**Use:** Continuous marketing background.

**CSS:** `background: #000000; color: #fafafa`

#### Charcoal frame · level 1

**Use:** Gallery cards and large demonstration panels.

**CSS:** `background: #141414; border: 1px solid rgba(255,255,255,0.11); border-radius: 18px; overflow: hidden`

**Observed:** Edges do the separating; there is no broad elevated shadow.

**Transfer:** Keep framing subordinate to the work inside.

#### Media frame · level 1

**Use:** Large output demonstrations and atmospheric subscription panel.

**CSS:** `border: 1px solid rgba(255,255,255,0.11); border-radius: 18px; overflow: hidden; aspect-ratio: 4 / 3`

**Observed:** The image fills the frame. Subscription artwork is darkened toward the bottom using black at 0.85, 0.65 and 0.4 alpha; output demonstrations can remain bright.

**Transfer:** Fill with meaningful product output rather than decorative empty panels.

#### Opening fade · level 2

**Use:** Protect low-set opening copy without erasing the specimen field.

**CSS:** `background: linear-gradient(to top, #000000 2%, rgba(0,0,0,0.6) 60%, rgba(0,0,0,0) 100%); backdrop-filter: blur(40px)`

**Observed:** A masked blur and black fade occupy the lower 359px; the upper gallery stays crisp.

**Transfer:** Mask the blur so it grows toward the copy rather than frosting the whole scene.

#### Glass code panel · level 2

**Only for:** technical demonstrations

**Use:** Short code specimen over artwork.

**CSS:** `background: rgba(0,0,0,0.55); border: 1px solid rgba(255,255,255,0.15); border-radius: 14px; backdrop-filter: blur(12px); padding: 16px`

**Observed:** Anchored near the lower-left of the image with a maximum width of 448px.

## Components

### Fixed navigation

**Use:** Persistent orientation without a separate opaque bar.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; z-index: 50`

**Text style:** `nav` — Inter 500 · 14px/20px · tracking -0.025em

**Observed:** A small serif wordmark sits left, three subdued links follow, and two miniature actions sit at the right. A 128px-deep masked blur field steps through 2px, 4px, 8px and 16px beneath a black-to-transparent fade.

**Transfer:** Use the new product's own compact mark; keep the links visually secondary.

### Primary button

**Use:** The main action in opening, pricing, forms and closing call.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 4px; height: 32px; padding: 0px 10px; border: 1px solid transparent; border-radius: 8px; background: #e5e5e5; color: #171717`

**Text style:** `action` — Inter 500 · 12px/1.625

**Observed:** A right arrow follows launch and subscription actions; plan buttons span their card width.

**States:** Declared: hover background becomes 80% of its silver fill mixed with transparent; focus-visible border becomes lab(66.128% -.0000298023 .0000119209); active translate remains 0 0.

### Secondary button

**Use:** Alternative route beside a primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 4px; height: 32px; padding: 0px 10px; border: 1px solid rgba(255,255,255,0.11); border-radius: 8px; background: rgba(255,255,255,0.045); color: #fafafa`

**Text style:** `action` — Inter 500 · 12px/1.625

**Observed:** Used for secondary destinations; chapter actions instead use a solid raised-charcoal fill with an arrow.

**States:** Declared: hover background becomes 7.5% white and text remains soft white; focus-visible border becomes lab(66.128% -.0000298023 .0000119209); active translate remains 0 0.

### Header action

**Use:** Compact launch and account actions.

**CSS:** `height: 24px; padding: 0px 8px; background: rgba(255,255,255,0.15); color: #ffffff; border: 1px solid rgba(255,255,255,0.2); border-radius: 8px`

**Text style:** `action` — Inter 500 · 12px/1.625

**Observed:** Two text-only controls, separated by 6px.

**States:** Declared: hover background becomes 25% white; focus-visible border becomes lab(66.128% -.0000298023 .0000119209); active translate remains 0 0.

### Navigation link

**Use:** Short header destinations.

**CSS:** `display: flex; align-items: center; gap: 6px; padding: 6px 10px; border-radius: 8px; color: rgba(255,255,255,0.7)`

**Text style:** `nav` — Inter 500 · 14px/20px · tracking -0.025em

**Observed:** Links remain unfilled; a small outline badge can sit beside an experimental feature label.

**States:** Declared: hover color #fff.

### Announcement badge

**Use:** One concise product update above the opening headline.

**CSS:** `display: inline-flex; align-items: center; gap: 6px; padding: 4px 12px; border: 1px solid rgba(255,255,255,0.11); border-radius: 9999px; background: rgba(20,20,20,0.6); backdrop-filter: blur(8px); color: rgba(255,255,255,0.6)`

**Text style:** `badge` — Inter 500 · 12px/16px

**Observed:** Small sparkle icon precedes the update; subdued enough not to compete with the headline.

### Specimen card

**Use:** Browsable examples or outcome gallery.

**CSS:** `display: flex; flex-direction: column; position: relative; overflow: hidden; background: #141414; border: 1px solid rgba(255,255,255,0.11); border-radius: 18px`

**Text style:** `card-title` — Inter 600 · 14px/20px · tracking -0.025em

**Observed:** A 14px-radius 4:3 image sits inset by 8px. Below it, a 12px-padded stack contains a one-line name, two-line muted description and tiny outlined tags. A duplicate image enlarged to 1.25 scale at 10% opacity tints the backing, then fades into charcoal. Small access badges sit over image corners.

**Transfer:** Use output variations with descriptive names; allow the image to tint the card instead of inventing a separate brand-colored surface.

### Plan card

**Use:** Simple free-versus-paid comparison.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 24px; background: #000000; border: 1px solid rgba(255,255,255,0.11); border-radius: 14px`

**Text style:** `body` — Inter 400 · 14px/20px

**Observed:** Plan name, price, billing suffix, short summary, checkmarked list and bottom-pinned full-width button. The paid option adds a subtle outline and small popularity badge, not a colored fill.

**Transfer:** Compare genuinely different permissions or outcomes; keep both cards equal height.

### Question row

**Use:** Open, readable objection handling.

**CSS:** `display: flex; flex-direction: column; gap: 8px; padding: 20px 0px; border-bottom: 1px solid rgba(255,255,255,0.11)`

**Text style:** `question` — Inter 500 · 16px/1.5

**Observed:** Question and answer are both visible; the first row has no top padding. Answers use the answer recipe rather than the question recipe.

**Transfer:** Use direct questions and complete, plain-language answers; do not hide the information by default.

### Inline subscription form

**Use:** Low-friction email conversion in atmospheric artwork.

**CSS:** `display: flex; align-items: center; gap: 6px; max-width: 448px; padding: 6px; background: #000000; border: 1px solid rgba(255,255,255,0.11); border-radius: 14px`

**Text style:** `body` — Inter 400 · 14px/20px

**Observed:** A flexible transparent email input shares one black enclosure with a silver Primary button. A 12px reassurance line sits below; footer variant separates its 32px-high input and button.

### Atmospheric footer

**Use:** Site-wide destination links and secondary subscription.

**CSS:** `position: sticky; bottom: 0px; z-index: 0; overflow: hidden; background: #000000`

**Text style:** `body` — Inter 400 · 14px/20px

**Observed:** The black main page reveals a full-width image-backed footer beneath it. A left brand block contains a short description and email form; three link columns sit right. Credits and a tiny operational note anchor opposite lower corners. The container uses 128px top and 112px bottom padding.

**Transfer:** Carry the same organic image language into this ending so the page does not stop at a generic black link list.

## Imagery and graphics

### Floating specimen field

**Use:** Signature opening artwork.

**Observed:** An irregular constellation of portrait, square and landscape studies floats directly on black, with large gaps and several pieces cut off by viewport edges. Visible subjects include moss-green blurred figures, violet halftone, pale iridescent grain, cobalt floral diffusion and hot orange-red fluted glass. Two-line monospaced annotations sit beneath pieces. Individual pictures are roughly 175–235px wide, with larger portrait heights; artwork dominates the upper two thirds.

**Transfer:** Show original product outputs or abstract studies in the same staggered, non-grid arrangement. If output is not visual, create a consistent family of textured studies that express the product's transformations; keep the minimum version to several polished studies repeated at varied scales, not random stock tiles.

**Build:** Place 14px-rounded image wrappers on an oversized absolute scene clipped by the viewport. Alternate widths around 176px, 216px and 235px and portrait/square/landscape ratios. Keep the center unevenly spaced and spill selected pieces beyond both side edges. Add small mono labels beneath them; overlay Opening fade only across the lower copy zone.

### Refracted light and grain

**Use:** Signature specimen material across opening and gallery.

**Observed:** Bright magenta, violet and orange light is softened behind vertical flutes; other studies use fine grain, halftone or blurred organic imagery. Saturation stays inside the image frames while their surrounding backing is nearly black.

**Transfer:** Produce a small coherent family of luminous material studies. A layered SVG/CSS still with convincing texture is the minimum acceptable substitute for a shader.

**Build:** On a black 4:3 artboard, layer a broad saturated radial glow and a narrower contrasting glow. Blur the light layer by roughly 20–40px, then overlay repeated narrow vertical SVG strips with alternating light and dark translucent edges to suggest refraction. Add a low-opacity monochrome turbulence texture on top and clip to a 14px rounded frame. Tune glow falloff and grain by eye; exact color stops are not essential.

### Product demonstration

**Use:** Credibility immediately after the opening and in capability chapters.

**Observed:** A large dark studio recording sits in an 18px-radius browser-like frame with small top-left window dots; a later process diagram uses charcoal nodes, dashed curved connectors and a faint dot-grid backing. The diagram stays grayscale so that the surrounding image gallery carries the color.

**Transfer:** Use a real workflow demonstration or a simplified, truthful diagram showing inputs resolving into one output. Do not rebuild every internal interface detail.

**Build:** For a process illustration, draw a very faint evenly spaced dot grid on black; position three small rounded input nodes toward the left and one larger preview node to the right. Connect their circular ports using thin dashed curved SVG paths in muted gray. Keep labels and controls small and monochrome.

### Live output study

**Use:** Full-width technical or integration proof.

**Observed:** A large 4:3 silver-gray grain field contains soft, blurred black organic ellipses. It is framed at 1104px wide with a small glass code panel near its lower-left and a centered caption beneath. This is rendered visual output, not a neutral content panel.

**Transfer:** Show a striking live or still output at large scale, then pair it with a short implementation detail and an honest compact caption.

### Organic atmospheric field

**Use:** Signature lower-page conversion field and footer backing.

**Observed:** Deep green foliage and an indistinct human silhouette are heavily defocused into moss, olive and nearly black patches. The subscription image occupies a tall 4:3 rounded frame; the footer uses a wide, even darker version. Text remains white or muted gray, never green.

**Transfer:** Choose an original organic image with soft depth and shadow. For a non-photographic substitute, compose irregular blurred dark green and olive forms with one darker central silhouette-like mass.

**Build:** Fill the frame with defocused organic photography. For the footer, enlarge the image beyond the edges, apply blur(10px) and opacity 0.5, then cover it with rgba(0,0,0,0.45). For the subscription frame, apply a bottom-heavy black overlay, approximately 0.85 alpha at bottom, 0.65 midway and 0.4 at top. Keep meaningful detail soft rather than legible.

### Icons

**Observed:** Small Lucide-like outline symbols with 2px strokes and rounded caps. Arrows are 16px in buttons; checkmarks and the announcement sparkle are 14px. Icons inherit dark primary-button text or muted white.

**Transfer:** Use a single rounded-stroke outline set. Limit icon use to action direction, compact status and list checks rather than giving each section a decorative emblem.

## Section recipes

How recurring sections are built.

### First screen: Specimen field opening

**Observed:** A black 900px-tall first screen is layered with an oversized, edge-clipped Floating specimen field, then the masked Opening fade over its lower 359px, then low-set copy and the Fixed navigation. The gallery occupies most of the upper two thirds. A small Announcement badge introduces a two-line 48px/1.05 Poppins promise in a 672px-wide block at the lower left. A separate 280px-wide column at the lower right contains a 14px support line and Primary button plus Secondary button. The two columns align at their bottom edge with 64px clearance. The first 900px includes the image field, headline, support and both actions; the large studio demonstration begins below the fold.

**Transfer:** Keep the image-led first impression and bottom-anchored split copy for a new landing page. Create an original specimen family when no equivalent product media exists. Focused secondary pages can open with the same compact heading-and-support grammar, while retaining a strong framed visual instead of inventing a second brand language.

**Avoid:** Do not move the headline into a huge centered text block above a single dashboard, or tile the specimens into a regular background grid.

**Text style:** `display` — Poppins 600 · 48px/1.05 · tracking -0.02em

### Demonstration window

**Observed:** An 1104px-wide Charcoal frame holds a 16:9 studio video and small browser dots. A tiny centered text link follows below. Standard lower clearance is 112px.

**Transfer:** Prove the promise with one intelligible workflow rather than another promotional paragraph.

### Chapter heading with side action

**Observed:** A muted uppercase eyebrow precedes a left-aligned Poppins heading by 12px, followed by a 20px muted support paragraph after 12px. The text measure is 576px; a compact solid-charcoal action aligns with the text block's lower edge at the far right. Artwork or gallery begins about 40px below.

**Transfer:** Use one capability or outcome per chapter. Select heading for major explanation and heading-compact for gallery or integration chapters.

**Text style:** `heading` — Poppins 600 · 36px/40px · tracking -0.02em

### Process stage

**Observed:** Chapter heading with side action introduces a tall grayscale diagram with three small source/effect nodes feeding one larger preview. The dotted process stage can extend wider than the text container.

**Transfer:** Demonstrate a relationship or transformation with meaningful inputs and output instead of ornamental feature cards.

### Outcome gallery

**Observed:** Chapter heading with side action precedes a four-column gallery-grid of Specimen cards. Eight examples form two rows, with color confined to the artwork and its faintly tinted backing.

**Transfer:** Show enough distinct examples to communicate range; card count follows actual content rather than a fixed requirement.

### Integration proof

**Observed:** A heading-compact introduction precedes a full-width Media frame containing Live output study. Glass code panel sits over the lower-left image area and a small centered caption follows after 12px.

**Transfer:** Pair a tangible output with one concrete fact about using it elsewhere, not a wall of code.

**Text style:** `heading-compact` — Poppins 600 · 30px/1.2 · tracking -0.02em

### Compact pricing comparison

**Observed:** Centered heading and support sit above a pill-shaped billing toggle. Two Plan cards sit in a 768px-wide grid with a 24px gap. The active toggle segment is soft white with dark text; inactive text stays muted. The paid plan uses only an extra pale outline for emphasis.

**Transfer:** Make the upgrade boundary explicit without turning pricing into a brightly colored interruption.

**Text style:** `heading` — Poppins 600 · 36px/40px · tracking -0.02em

### Open questions

**Observed:** A 320px-wide heading column sits left of a 744px-wide stack of Question rows with a 40px gap. Questions and full answers remain visible, separated by subtle hairlines.

**Transfer:** Place the title next to the content, not over the entire width; use enough text to resolve genuine concerns.

**Text style:** `heading` — Poppins 600 · 36px/40px · tracking -0.02em

### Atmospheric subscription

**Observed:** A large 4:3 Media frame contains Organic atmospheric field, a centered 36px heading, muted support, Inline subscription form and one short reassurance. Dark image detail continues far below the text, making the field feel immersive rather than like a short form strip.

**Transfer:** Use this as a calm secondary conversion moment with a real reason to subscribe; retain atmospheric depth.

**Text style:** `heading` — Poppins 600 · 36px/40px · tracking -0.02em

### Closing invitation and reveal

**Observed:** On plain Black canvas, a centered two-line 48px/1 Poppins heading is constrained to 672px, with support after 16px, paired actions after 32px and small reassurance after 16px. Vertical padding is 128px. Beneath it, Atmospheric footer introduces a full-width green-black image, brand block, three link columns and low corner credits.

**Transfer:** End with a simple reader outcome and immediate action, then change material to reveal the footer. Preserve this black-to-organic contrast even when the content and link groups change.

**Text style:** `closing-display` — Poppins 600 · 48px/1 · tracking -0.02em

## Page flow

**Storyline:** Visual promise → workflow proof → capability and outcome chapters → commitment choice → objections → secondary relationship → final invitation and atmospheric wayfinding.

### A creative-tool landing page that makes visual range tangible before explaining mechanics and purchase boundaries

1. **Promise** — Floating specimen field with low-set split headline and compact actions.
2. **Product demonstration** — Large studio recording inside a dark browser frame.
3. **Capability chapters** — A grayscale process diagram, colorful outcome gallery and large live output with code detail.
4. **Pricing** — Centered introduction, billing toggle and two restrained plan cards.
5. **Objection handling** — Left title and always-open question-and-answer stack.
6. **Relationship** — Email subscription over a dark organic image.
7. **Closing call** — Plain black centered invitation followed by an image-backed footer with subscription and link columns.

**Transfer:** Adapt the order and number of proof chapters to the new product. Keep the alternation between luminous output, restrained explanation and concrete conversion, including the specimen and atmospheric-ending devices.

## Writing

Practical, warm and maker-facing, with confidence grounded in a visible action or a specific output. A little creative informality keeps technical details from sounding institutional.

**Do not copy:** Do not reuse the Pryzm name, artwork, specimen names, creator identity, prices, performance numbers, export entitlements or product-specific claims. Source examples illustrate tone only.

- **Addressing the reader:** Speak directly to the reader with you and your, and use concise imperatives. Use we sparingly for product updates; name the product when clarifying billing or implementation.
- **Rhythm:** Short outcome-led headings, usually four to nine words, followed by one useful sentence. Technical explanations and FAQ answers can be longer, but remain plain and specific.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Distinctive outcome plus low effort or short time to value. | 6–10 words | “Backgrounds nobody else has, in seconds” |
| Chapter headline | Action or concrete contrast, not a category label. | 4–8 words | “Wire it up as a graph”<br>“Ship it as code, not a video” |
| Supporting line | Explain the mechanism with tangible verbs and materials. | 12–25 words for a short introduction | “Feed a gradient and effects into a base and watch it resolve live.” |
| Primary action | Verb plus destination or result. | 2–5 words | “Open studio”<br>“Try it in the studio” |
| Subscription | Specific reason to hear from the product, then a plain opt-out reassurance. | One sentence each | “Hear when we ship a new effect or add a look worth stealing.”<br>“Occasional product emails. Unsubscribe in one click, anytime.” |
| Closing headline | Your next outcome is close at hand. | 7–10 words | “Your next background is a minute away.” |

**Words and phrasing to use:** make; open; ship; live; remix; look; in seconds; your next

**Avoid:** revolutionary; unleash your potential; world-class; seamless ecosystem; game-changing; enterprise transformation

**Rules:**

- Lead with what the reader can make or accomplish, then explain how.
- Use specific implementation and ownership details where they resolve a real doubt.
- Reassurance should be small, direct and adjacent to the relevant action.
- Let visual examples demonstrate range; avoid unsupported superlatives.

## Do's and Don'ts

### Do

- Keep the first-screen headline at 48px rather than inflating it to dominate the artwork.
- Use 112px chapter padding against compact 32px controls.
- Keep major text on a 1152px outer container with 24px inner side padding.
- Use 18px outer frames and 14px inner artwork windows to create nested softness.
- Retain 20px gallery gaps and small 12px descriptions beneath specimen names.
- Keep pricing emphasis to a fine pale outline and silver action.
- Repeat an organic image treatment in a lower-page conversion field and footer.
- Maintain the 14px opening-support versus 20px chapter-support contrast.

### Don't

- Do not add a saturated brand-color button; primary controls are #e5e5e5 with dark text.
- Do not turn main actions into 48px-tall fully rounded pills; use 32px height and 8px corners.
- Do not make every section a charcoal box; the main background remains continuous black.
- Do not substitute bold Inter for the Poppins 600 headline character.
- Do not turn the large grainy output study into a generic gray background behind text.
- Do not use strong drop shadows to separate dark panels; hairlines carry their edges.
- Do not center every chapter introduction; most pair a left text measure with a right action.
- Do not sharpen the organic background into literal, busy stock photography; its soft detail is part of the material language.

## Motion and responsive

### Motion

**Observed:**

- Declared action transitions use .15s cubic-bezier(.4, 0, .2, 1), either all properties or the color-related property set.
- Gallery card transforms declare 0.3s cubic-bezier(.4, 0, .2, 1).
- The footer is sticky at bottom with z-index 0 beneath the main content's z-index 10, creating a reveal structure.

**Transfer:**

- Keep interaction changes small and tonal so that the artwork remains the visual event.
- Preserve the layered footer reveal rather than animating the whole footer as a floating card.

**Unknown:**

- Exact playback and timing of animated artwork, entrance sequences and process-edge animation are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 640px, 768px, 1024px, 1280px and 1536px.
- Class rules specify a two-column gallery below the four-column desktop layout, a stacked pricing layout below its two-column variant and hidden desktop navigation below 768px.
- Container side padding changes from 16px to 24px; opening copy changes from stacked to side-by-side at the large layout.

**Transfer:**

- On narrow screens, keep the specimen field clipped at its edges but reduce overlapping visual competition behind the stacked copy.
- Stack the FAQ title above answers and footer brand block above link groups while preserving the black-to-organic ending.
- Use the declared smaller 32px opening headline and 80px chapter padding as the narrow-layout starting point.

**Unknown:**

- Only desktop layouts are visually established; exact mobile specimen positions and footer reveal behavior require layout testing.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
