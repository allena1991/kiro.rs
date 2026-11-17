# Hungry Tiger — spice-soaked poster theatre

## Overview

A warm, high-impact product style with burnt-orange grounds, golden lettering and concentrated flashes of hot pink. Heavy geometric sans headlines behave like posters, while tiny uppercase annotations leave the product to do most of the talking. Glossy floating product renders, tactile printed textures and rich editorial photography give this spacious but visually loud style its physical appetite. It suits expressive consumer products and highly visual launches better than text-heavy service explanations.

### Essentials

- Headlines behave like oversized packaging: Salmond 700 in uppercase, 213.1px/0.8 with -0.02em tracking for the opening promise, and 129.6px/0.9 with -0.016em for major chapters.
- The opening is a product theatre, not a two-column pitch: a nearly full-width headline above a centered 72px product descriptor, a glossy isolated object rising from the lower half, and a tiny 225px-wide support block with a 48px pill at bottom left.
- Color fills the page rather than accenting white space: burnt orange #823513 dominates the long product story, gold #faae33 carries type and substantial inverted bands, and deep brown #281006 closes the page. Hot pink stays concentrated in product-image backings and small stickers.
- Soft controls contrast with hard poster typography: golden 48px-high pills, 52px circular icon holders and restrained 6px card corners; no raised-card shadows.
- A tactile graphic layer is essential: low-contrast botanical silhouettes and grain sit behind product theatre, while 4px dotted rules repeat at 10px intervals. For non-botanical products, use silhouette motifs drawn from their materials or use context.
- The product becomes a sculpture: isolated, sharply lit objects overlap giant type and change angle across generous stages. When no physical object exists, use an isolated dimensional emblem or composed service artifact, not a generic interface rectangle.
- The ending is monumental rather than administrative: a 900px split gold-and-pink signup stage leads to a deep-brown 668px footer with a 195.1px uppercase name, tiny link columns and a low dotted baseline. Preserve the giant closing name and split conversion stage wherever the narrative places them.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Poster gold | `#faae33` | `--color-gold` | text, surface, action, border | Default lettering on orange and dark brown; pill actions, cards and full inverted editorial bands. |
| Printed-rule gold | `#f7ac32` | `--color-dot` | border, accent | Repeated dotted rules; keep their slightly different gold rather than substituting a neutral divider. |
| Burnt orange | `#823513` | `--color-canvas` | background, surface | Dominant marketing canvas and dark metadata pills on gold cards. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sticker pink | `#d1255c` | `--color-pink` | accent, surface | Small tilted benefit stickers; a related hotter magenta family appears in photographic product backdrops. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Gold-panel edge | `#b97c27` | `--color-rule` | border | Visible cocoa edge on gold: rgba(64,32,17,0.35) over #faae33, used for inputs and benefit-column dividers. |
| Dimmed orange | `#702e10` | `--color-shade` | surface | Visible result of a 14% black scrim on burnt orange; use the alpha scrim over conversion photography rather than an opaque patch. |
| Cocoa ink | `#402011` | `--color-ink` | text, surface, action | Text on gold, submit buttons, circular pictogram backings and dark image holders. |
| Blackened brown | `#281006` | `--color-deep` | background, surface | Dark split-story panels and the closing footer; replaces neutral black. |

## Typography

- **Salmond** — Display headlines, compact supporting copy, editorial cards and product annotations. Broad, heavy geometric sans with blunt poster-like capitals; medium cuts keep tiny annotations warm rather than technical. If unavailable, use **Outfit**. Use 500 and 700; retain the broad headline setting and tight tracking. Font stack: "Salmond", "Outfit", Arial, sans-serif.
- **Graphikx** — Navigation, footer links and utility information. Narrow, economical sans lettering that visually contrasts with the wide display capitals. If unavailable, use **Barlow Condensed**. Use 500; fit short labels without expanding pill widths. Font stack: "Graphikx", "Barlow Condensed", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Salmond | 700 | 213.1px | 0.8 | -0.02em, uppercase | Single-line opening promise spanning nearly the entire width. |
| closing-name | Salmond | 700 | 195.1px | 1 | -0.01em, uppercase | Nearly edge-to-edge brand name in the footer. |
| textured-display | Salmond | 700 | 144px | 0.9 | -0.02em, uppercase | Centered two-line statement with botanical pattern inside its golden letterforms. |
| chapter | Salmond | 700 | 129.6px | 0.9 | -0.016em, uppercase | Major product-story chapters, image-backed calls and editorial collection titles. |
| inverted-heading | Salmond | 700 | 100.8px | 0.88 | -0.016em, uppercase | Dark-on-gold editorial headings and centered benefit arguments. |
| product-name | Salmond | 700 | 72px | 0.9 | -0.02em, uppercase | Centered product descriptor below the opening promise. |
| split-heading | Salmond | 700 | 64.8px | 0.9 | -0.005em, uppercase | Compact stacked heading in dark split panels. |
| newsletter-heading | Salmond | 700 | 41.8px | 0.95 | -0.01em, uppercase | Multi-line offer statement at the top of the gold signup panel. |
| card-heading | Salmond | 700 | 28.8px | 1 | -0.01em, uppercase | Dense two-line editorial card titles. |
| nav-label | Graphikx | 500 | 13px | 1.3 | 0.01em, uppercase | Narrow uppercase navigation labels. |
| footer-label | Graphikx | 500 | 13px | 1 | 0.01em, uppercase | Footer menus, contact details and baseline information. |
| card-body | Salmond | 500 | 12.2px | 1.4 | 0.01em | Sentence-case editorial card descriptions. |
| annotation | Salmond | 500 | 11.5px | 1.3 | 0.02em, uppercase | Short supporting statements in the product theatre and icon explanations. |
| button-label | Salmond | 700 | 11.5px | 1 | -0.02em, uppercase | Main product conversion pill. |
| metadata | Salmond | 500 | 10.8px | 1 | 0.01em, uppercase | Paired category and duration pills on editorial cards. |

**Notes:**

- The gulf between monumental headings and tiny annotations is intentional: do not insert a conventional medium-sized paragraph tier into product stages.
- Keep uppercase headline line breaks short and blocky. Main chapter headings typically stack into two or three tightly packed lines.
- Headline tracking is negative; small support and navigation labels open to 0.01–0.02em. Sentence case is reserved mainly for card descriptions.
- Fit new closing names to the available width while preserving the monumental scale relationship; long names can occupy two lines instead of becoming a small logo.

## Layout

**Density:** Airy product theatre with compact annotations and closely packed editorial cards; long open stages separate the dense moments.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Between adjacent navigation pills, metadata pills and paired form fields. |
| 10px | Card title-to-description gap. |
| 12px | Icon-to-copy spacing and photo-to-metadata separation. |
| 14px | Editorial card inset around photography. |
| 16px | Three-column card-grid gaps. |
| 28px | Default outer side gutters, metadata-to-card-title gap and benefit-panel internal separation. |
| 32px | Card bottom padding and primary button horizontal padding. |
| 42px | Signup panel top padding and dark-panel headline inset. |
| 192px | Generous editorial chapter top and bottom space. |

### Containers and grids

- **edge-to-edge stage**: side padding 28px. Full viewport-width canvas with 1384px usable width at 1440px; no fixed centered max-width wrapper.
- **editorial grid**: 3 columns · gap 16px · side padding 28px. Equal-width 451px cards at desktop; one featured row or a multi-row collection.
- **split product story**: 2 columns · gap 0px. Dark information panel occupies about 55% of the width, with a bright edge-to-edge product photograph filling the remainder.
- **signup split**: 2 columns · gap 0px. Equal 720px-wide gold form and magenta photographic panels at desktop, each 900px tall.
- **benefit columns**: 3 columns · gap 0px · side padding 28px. Equal columns separated by hairlines; icons and short explanations above low-set image panels.

## Corner radius

| Element | Radius |
| --- | --- |
| pills | 9999px (pill) |
| editorial cards | 6px |
| icon holders | 50% |

## Surfaces and depth

### Surfaces

#### Burnt-orange canvas · level 0

**Use:** Default marketing page ground.

**CSS:** `background-color: #823513; color: #faae33`

**Observed:** The long opening product narrative shares one continuous warm ground.

**Transfer:** Use the orange as the page itself rather than a contained hero card.

#### Printed texture · level 1

**Use:** Tactile layer across the product theatre.

**CSS:** `background-color: #823513; position: relative`

**Observed:** A grain layer uses overlay blending; the large botanical texture beneath it uses multiply blending at 0.5 opacity. Fine radial speckle adds another very faint layer.

**Transfer:** Use the Botanical print construction, retaining legibility and matte depth.

#### Golden editorial band · level 0

**Use:** Inverted storytelling and benefits.

**CSS:** `background-color: #faae33; color: #402011`

**Observed:** Full-width gold with a fine grain layer at 0.1 opacity and difference blending, not a clean white editorial section.

**Transfer:** Give process, craft or supporting proof an immersive change of ground.

#### Dark panel · level 0

**Use:** Split product explanations and footer.

**CSS:** `background-color: #281006; color: #faae33`

**Observed:** Flat blackened brown carries small gold text without shadow or glossy UI effects.

**Transfer:** Use as a heavy tonal counterweight to bright media.

#### Editorial card · level 1

**Use:** Photo-first content previews.

**CSS:** `background-color: #faae33; border-radius: 6px; overflow: hidden`

**Observed:** Gold remains visible as a narrow photo frame and a larger title-and-description area.

**Transfer:** Use for content that demonstrates the product in use.

#### Photographic scrim · level 1

**Use:** Text over full-bleed product photography.

**CSS:** `background-color: rgba(0, 0, 0, 0.14)`

**Observed:** A restrained dark veil lets gold display type sit on rich close-up photography.

**Transfer:** Preserve the photograph's saturation instead of dimming it to near black.

## Components

### Navigation pill

**Use:** Short primary destinations in the fixed header.

**CSS:** `background-color: #faae33; color: #402011; border-radius: 9999px; height: 48px; padding: 0px 17.5px; display: flex; align-items: center`

**Text style:** `nav-label` — Graphikx 500 · 13px/1.3 · tracking 0.01em · uppercase

**Observed:** A tight cluster sits left, a compact illustrated logo stays centered, and contact plus purchase controls sit right. A dotted rule runs beneath the 82px header.

**Transfer:** Keep labels short enough for the narrow lettering and small individual capsules.

### Primary button

**Use:** Product conversion on orange or image stages.

**CSS:** `background-color: #faae33; color: #402011; border-radius: 9999px; height: 48px; padding: 20px 32px 16px 32px; box-sizing: border-box; overflow: hidden`

**Text style:** `button-label` — Salmond 700 · 11.5px/1 · tracking -0.02em · uppercase

**Observed:** The opening uses a small standalone pill beneath its bottom-left support line. The header purchase variant is 50px high, uses narrow utility lettering and includes a basket pictogram.

### Editorial preview

**Use:** Photo-led usage stories and collection entries.

**CSS:** `background-color: #faae33; color: #402011; border-radius: 6px; padding: 14px 14px 32px 14px; overflow: hidden`

**Text style:** `card-heading` — Salmond 700 · 28.8px/1 · tracking -0.01em · uppercase

**Observed:** A 423×346px photograph leads a 451×572px card. Paired Metadata pills follow, then the title after 28px and a short Card-body description after 10px.

**Transfer:** Replace recipe content with relevant use cases, guides or examples while keeping image dominance.

### Metadata pill

**Use:** Category and a compact practical fact below card imagery.

**CSS:** `background-color: #823513; color: #faae33; border-radius: 9999px; padding: 12px 12px 8px 12px`

**Text style:** `metadata` — Salmond 500 · 10.8px/1 · tracking 0.01em · uppercase

**Observed:** Two small pills sit on one line, separated by 4px; their edges are fully rounded.

### Icon medallion

**Use:** Ingredient or feature explanation rows.

**CSS:** `width: 52px; height: 52px; border: 1px solid #faae33; border-radius: 50%; padding: 10px; box-sizing: border-box`

**Observed:** A simple 30px pictogram occupies the center. Gold outlines sit on dark panels; inverted benefit rows use solid cocoa circles and warm pictograms.

**Transfer:** Use a small literal object symbol for each claim, not a general-purpose software icon set.

### Benefit column

**Use:** Evidence for a product material or construction choice.

**CSS:** `border-right: 1px solid rgba(64, 32, 17, 0.35); padding: 0px 28px 28px 0px`

**Text style:** `annotation` — Salmond 500 · 11.5px/1.3 · tracking 0.02em · uppercase

**Observed:** Icon medallion and short label lead each column; compact explanation is followed by substantial open space and a bottom-aligned product-use photo. The last column has no right divider.

### Dotted rule

**Use:** Header boundary, headline boundary and footer baseline.

**CSS:** `height: 4px; background-image: repeating-radial-gradient(circle, #f7ac32 0px, #f7ac32 2px, rgba(0, 0, 0, 0) 2px, rgba(0, 0, 0, 0) 10px); background-size: 10px 4px`

**Observed:** Small round marks read as printed perforation; they traverse the full width without a boxed frame.

**Transfer:** Repeat at key structural boundaries rather than under every text block.

### Signup field

**Use:** Name and email collection in the split conversion stage.

**CSS:** `background-color: rgba(0, 0, 0, 0); color: #402011; height: 54px; border: 1px solid rgba(64, 32, 17, 0.35); border-radius: 9999px; padding: 16px 16px 12px 20px; box-sizing: border-box`

**Observed:** Two equal fields sit side by side near the panel bottom with a 4px gap; small uppercase prompts replace external labels visually.

**Transfer:** Retain accessible labels even if visually hidden.

### Signup submit

**Use:** Single full-width action below the paired fields.

**CSS:** `background-color: #402011; color: #faae33; height: 54px; border-radius: 9999px; padding: 16px 42px 12px 42px; margin-top: 8px; box-sizing: border-box`

**Observed:** One dark capsule spans both fields, followed by a tiny consent line with an underlined privacy link.

### Footer menu

**Use:** Compact wayfinding beneath the monumental closing name.

**CSS:** `display: flex; flex-direction: column; gap: 2px; color: #faae33`

**Text style:** `footer-label` — Graphikx 500 · 13px/1 · tracking 0.01em · uppercase

**Observed:** Three tight menu columns occupy the left portion; contact information sits farther right and a circular social control anchors the far edge. A large unoccupied brown field separates these from the bottom dotted rule.

## Imagery and graphics

### Floating product sculpture

**Use:** Opening and immersive benefit chapters.

**Observed:** Glossy glass jars with black lids and warm orange contents are isolated against matte orange. They rotate through diagonal and underside views, overlap type, then open and pour a thick ribbon. The object occupies roughly the central third to half of the stage; the first upright view extends below the fold.

**Transfer:** Render or photograph the new object with crisp specular edges, rich material color and no surrounding room. If no physical object exists, assemble a dimensional emblem from the service's actual artifacts and light it as one sculptural object.

**Build:** Isolate an original product photograph with an alpha mask; scale it to roughly 320–500px wide on a 1440px stage. Prepare alternate angled views, layer them above text where overlap is intentional, and retain hard material highlights rather than adding a generic drop shadow.

### Botanical print

**Use:** Signature backdrop for the warm product theatre and pattern inside a chapter headline.

**Observed:** Oversized leaf-and-stem silhouettes and grain drift diagonally through rust-on-rust fields. Their contrast stays low behind the object; inside golden headline letters the same motifs become more legible.

**Transfer:** Replace leaves with original silhouettes of the product's ingredients, materials or working tools. Preserve the overprinted tactile quality.

**Build:** Draw an SVG tile around 700px wide with branching curved stems and tapered leaf shapes in cocoa. Repeat at different rotations and scales across the orange ground, use multiply blending at 0.5 opacity, and overlay fine monochrome SVG turbulence grain. Add a faint 1px radial black speckle layer at 0.04 alpha with 0.2 layer opacity. For patterned letters use an SVG text clip over a gold rectangle plus low-opacity cocoa silhouettes.

### Magenta product portrait

**Use:** Right side of split explanations and the signup stage; full-bleed conversion photography.

**Observed:** Hot-pink tonal foliage fills the backing. A hand presents or opens the jar in explanation panels; the signup image shows a single large diagonal floating jar. The conversion band uses several enormous jars entering from the frame edges.

**Transfer:** Pair an isolated original product with a strongly saturated pink backing and tonal motifs. Include hands when they can demonstrate scale or an action naturally.

**Build:** Fill a full-height panel with sticker pink, layer large silhouette motifs in cocoa using low alpha so the backing remains pink, then place a sharply masked product or hand-and-product photo over it. For the conversion band duplicate original object views at different angles and let them extend beyond all edges; avoid a neat row of objects.

### Editorial craft photography

**Use:** Gold storytelling band and benefit-column images.

**Observed:** Warm, richly colored documentary photographs show preparation, utensils, steam, meals and textured surfaces. Individual photographs are loosely staggered and slightly tilted, not a uniform wall; tiny numbered circles and uppercase captions sit above them.

**Transfer:** Show the making, material and real-life use of the new product with similarly physical textures and directional light.

### Usage-card photography

**Use:** Editorial previews and content collections.

**Observed:** Close, appetizing food photographs fill landscape 423×346px frames inside thin gold insets; colors remain natural and rich. The view may be overhead or close oblique, with little dead background.

**Transfer:** Use close views of the product's actual outcomes, tightly framed and as visually specific as the source's finished dishes.

### Icons

**Observed:** Small literal pictograms of ingredients, containers, basket, social platform and editorial motifs; gold and brown dominate. Explanation symbols sit inside 52px circles with 10px padding; fixed lower-right utility circles repeat the product and basket symbols.

**Transfer:** Use compact filled or softly illustrated object symbols and simple social marks. Keep each pictogram subordinate to the circle, avoiding thin technical line-icon libraries.

## Section recipes

How recurring sections are built.

### First screen: Poster and product opening

**Observed:** A full-width 900px stage begins with the fixed Navigation pill header and Dotted rule. Back to front: Burnt-orange canvas, Botanical print and grain, centered small category label, near-edge-to-edge Display headline, another dotted separator, then the centered Product-name descriptor. The headline occupies the upper-middle width rather than one side. A glossy upright object rises centrally from just below the descriptor and continues beyond the lower edge. Within the first 900px the entire promise and descriptor, upper product body, bottom-left 225px support block and Primary button are visible; the lower product and subsequent angled views fall below. Two small circular utility actions sit at bottom right.

**Transfer:** Use a two- or three-word promise that can form one broad poster line, a short product descriptor and a large isolated original object. Without a physical product, stage a dimensional emblem with the same tactile light. Editorial collection pages instead open below the shared header with a left-aligned Chapter title and a small circular editorial symbol, followed by the card grid.

**Avoid:** Do not turn this into a centered text-only hero with an inline button row or shrink the object into a boxed thumbnail.

**Text style:** `display` — Salmond 700 · 213.1px/0.8 · tracking -0.02em · uppercase

### Sculptural chapter

**Observed:** A continuous textured orange field carries successive angled object views. Chapter type can anchor to the upper left or stack low on the left; one centered Textured-display statement carries tonal foliage inside its letters. Tiny support blocks occupy a distant edge rather than competing beside the object.

**Transfer:** Use each stage to reveal a new material, capability or perspective, keeping a single object as the visual thread.

**Text style:** `chapter` — Salmond 700 · 129.6px/0.9 · tracking -0.016em · uppercase

### Dark and pink explanation

**Observed:** Dark panel pairs with a full-height Magenta product portrait. A Split-heading sits at the top left above a dotted divider and tiny support line. Farther down, three icon-and-copy rows step diagonally inward; a second split moment uses a terse negative-pair statement and a hand opening the product.

**Transfer:** Explain what the product contains or how it works through a few concrete pictograms and a close interaction photograph.

**Text style:** `split-heading` — Salmond 700 · 64.8px/0.9 · tracking -0.005em · uppercase

### Gold editorial trail

**Observed:** Golden editorial band opens with a large left-aligned Inverted-heading and tiny support block. Three original photographs are distributed through an unusually spacious staggered trail, each paired with a small cocoa numeral circle and uppercase caption. Slight rotations keep the composition physical.

**Transfer:** Tell a making, process or outcome story using three or another small number of distinct visual proof points; do not require the same subject matter.

**Text style:** `inverted-heading` — Salmond 700 · 100.8px/0.88 · tracking -0.016em · uppercase

### Stickered benefit argument

**Observed:** Centered Inverted-heading on gold has small pink pill stickers crossing its edges and gaps. Short supporting copy stays directly underneath. Below a generous separation, three Benefit columns carry Icon medallions, explanations and low-set photography. The section begins with 192px of top space and 28px side gutters.

**Transfer:** Explain a consequential product design choice; let the stickers call out concise benefits while the columns substantiate them.

**Text style:** `inverted-heading` — Salmond 700 · 100.8px/0.88 · tracking -0.016em · uppercase

### Photographic conversion band

**Observed:** Several oversized objects fill a saturated magenta photograph; a Photographic scrim backs gold Chapter type and a small Primary button aligned left. Object edges extend outside the band rather than fitting within a container.

**Transfer:** Make a high-impact action moment from an original product collage; use the product's strongest material details rather than an unrelated lifestyle image.

**Text style:** `chapter` — Salmond 700 · 129.6px/0.9 · tracking -0.016em · uppercase

### Editorial card collection

**Observed:** On orange, a large centered Chapter heading and small pill action introduce one row of Editorial previews with 16px gaps and 28px side gutters. The collection-page variant starts with a left-aligned title and extends the same three-column grid to two rows, keeping 192px bottom space before the signup stage.

**Transfer:** Use a featured row for a landing page and an extended grid for a library or catalog; choose relevant usage stories rather than inventing a new tile system.

**Text style:** `chapter` — Salmond 700 · 129.6px/0.9 · tracking -0.016em · uppercase

### Split signup stage

**Observed:** A 900px equal split combines a gold form panel and Magenta product portrait. Newsletter-heading occupies about four lines within a 531px text width at the upper left, with 42px top and 28px side insets. A dark serrated discount seal floats in the open middle space. Paired Signup fields and Signup submit sit near the bottom, with consent text underneath.

**Transfer:** Offer a relevant ongoing benefit, waitlist or useful resource. Preserve the dramatic distance between the top statement and low form, and retain a small symbolic seal even without a discount.

**Text style:** `newsletter-heading` — Salmond 700 · 41.8px/0.95 · tracking -0.01em · uppercase

### Monumental closing name

**Observed:** Dark panel extends 668px high. Closing-name type begins 24px below its top and spans nearly the full width within 28px gutters. Footer menus, contact details and a circular social action sit below it; a large brown field leads to the Dotted rule and tiny baseline text near the bottom.

**Transfer:** Set the new product's name as real display text with the same oversized presence; keep practical links in small concentrated clusters rather than filling the footer with cards.

**Text style:** `closing-name` — Salmond 700 · 195.1px/1 · tracking -0.01em · uppercase

## Page flow

**Storyline:** Oversized promise → immersive product revelation → concrete explanations and visual proof → useful applications → split conversion stage → monumental brand sign-off.

### Immersive product landing page that turns one object into a sustained visual story

1. **Promise** — Full-width poster headline, product descriptor and glossy central object over tactile orange.
2. **Product demonstration** — Successive angled views, patterned type and opening or pouring action reveal the object.
3. **Capability explanation** — Dark-and-pink split panels connect literal pictograms with close interaction photography.
4. **Process proof** — Gold editorial trail shows material, making and use in captioned photographs.
5. **Objection handling** — Stickered central argument and three divided benefit columns explain a construction choice.
6. **Conversion** — Full-bleed object collage supports a giant action headline and small pill.
7. **Applications** — Featured usage cards turn the promise into practical possibilities.
8. **Ongoing relationship** — Split signup stage pairs an offer and bottom-aligned form with a vivid object portrait.
9. **Brand sign-off** — Monumental name, compact menus and low dotted baseline.

**Transfer:** Adapt the number and order of product chapters to the new story, but retain sculptural product theatre, tactile print and a monumental ending.

### Editorial collection page for finding practical ways to use the product

1. **Orientation** — Large two-line title at left beneath the shared capsule navigation.
2. **Applications** — Three-column, two-row photo-first card grid with category and duration pills.
3. **Ongoing relationship** — The same full-height split signup stage used by the product narrative.
4. **Brand sign-off** — The same deep-brown oversized-name footer and tiny wayfinding clusters.

**Transfer:** Use this compact opening for a resource library, guide collection or use-case catalog; preserve the shared conversion and closing devices.

## Writing

Confident, warm and sensorial. The language makes a product feel tangible and adventurous, balancing punchy promises with concrete descriptions of materials, actions and outcomes.

**Do not copy:** Do not reuse the Hungry Tiger name, tiger artwork, packaging, recipe names, proprietary product claims, origin claims, discount amount, contact details or exact promotional lines as the new brand's content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to the reader with you and your; use our for the product's composition and making. Actions are direct imperatives rather than conversational questions.
- **Rhythm:** Two- to six-word display statements, often split into short stacked phrases. Supporting copy is one or two compact sentences; card copy is brief and sentence case, while product-stage text reads as uppercase annotations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A short sensory payoff, not a complete explanation. | 2–4 words | “bold flavor” |
| Chapter heading | Active metaphor or change of perspective attached to an outcome. | 3–6 words | “A New Angle of Flavor”<br>“Unwrap the Adventure” |
| Support | Pair a concrete product trait with the feeling or action it enables. | 12–25 words | “Bold flavors from the kitchens of India. Crafted for those who crave more.” |
| Claim pair | Two short negatives establish standards before a positive payoff. | 2–3 words per clause | “No Fillers. No Shortcuts.” |
| Action | Literal verb and brief destination or next step. | 1–3 words | “buy now”<br>“all recipes” |
| Card description | Lead with an appealing result, then explain the practical method or ease. | 12–20 words | “Bold, oven-charred chicken in just 20 minutes. Marinated in rich [Brand] flavor.” |

**Words and phrasing to use:** bold; real; crafted; unlock; inside; rich; warmth; ready; concrete material and action words

**Avoid:** enterprise jargon; vague innovation claims; clinical technical language; long abstract mission statements; forced internet slang

**Rules:**

- Use sensory specificity that is true of the new product, rather than borrowing food adjectives indiscriminately.
- Put the payoff in the headline and the mechanism in the tiny support text.
- Keep claim language short enough to work as a sticker or printed annotation.
- Use practical metadata on cards to complement expressive titles.

## Do's and Don'ts

### Do

- Keep the opening promise at 213.1px/0.8 at the desktop reference width, with broad uppercase letterforms.
- Use 28px outer gutters and 16px gaps for the equal-width editorial grid.
- Keep card corners at 6px so photography feels framed rather than floating in bubbles.
- Pair 48px golden conversion pills with small 11.5px bold labels.
- Repeat 4px-high gold dotted rules at 10px intervals at major boundaries.
- Reserve the largest gold backgrounds for intentional editorial or conversion inversions.
- Preserve the split signup composition and the 195.1px closing name as major brand gestures.
- Keep product photography rich and reflective against matte, grainy backings.

### Don't

- Do not replace the burnt-orange canvas with off-white or a generic black technology theme.
- Do not introduce a blue or green action color; gold handles conversion across the dark grounds.
- Do not give editorial cards 24px corners or soft elevation shadows.
- Do not set product-stage support copy at conventional 18–20px body size; its small annotation scale is part of the contrast.
- Do not stretch the hot-pink accent uniformly over the whole page; concentrate it in photographic backings and stickers.
- Do not replace the dotted separator with a thin gray solid rule.
- Do not put all process photographs on one evenly aligned baseline; preserve their staggered editorial placement.
- Do not fill the footer's brown breathing room with extra promotional tiles.

## Motion and responsive

### Motion

**Observed:**

- A small decorative seal uses a declared 15s linear infinite spin.
- Product theatre shows changing orientation, opened packaging and a flowing material reveal through the scroll narrative.
- The fixed header appears in the opening and some later positions; the warm patterned product background remains visually continuous.

**Transfer:**

- Tie changes of object angle to product chapters rather than making every text block move independently.
- Use the slow linear spin for a small serrated seal, not for the main headline.

**Unknown:**

- Exact scroll-scrubbing implementation, reveal timings and easing are unknown.
- No button hover, focus-visible or active-state styling is established.

### Responsive

**Observed:**

- The established layout is a 1440×900px desktop viewport with full-width stages, three-column cards and split panels.

**Transfer:**

- On narrower screens, preserve the hierarchy of huge promise, isolated object and tiny support; fit headline line breaks before reducing all type uniformly.
- Stack split panels and card columns when needed, keeping gold framing, dark-and-pink contrast and the oversized closing name.

**Unknown:**

- Mobile breakpoints, exact fluid type formulas, alternate navigation and narrow-screen object choreography are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
