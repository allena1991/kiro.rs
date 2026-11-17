# Airbnb — human stories, miniature worlds

## Overview

An inviting, light product-marketing style where rounded geometric sans typography and small, tactile objects make a substantial platform feel personal. White and pale gray dominate, with charcoal text, berry-pink actions, natural photography and carefully staged phone demonstrations. The marketing experience is spacious and conversational; a denser discovery variant trades the big promises for browsable photographic shelves.

### Essentials

- Friendly headlines form compact two-line blocks, not sprawling billboards: 60px/64px, weight 600, -0.04em tracking for the opening; 54px/58px, weight 600, -0.03em for section leads.
- The opening feels like two objects sharing a white stage: a centered 476px text block on the left and a 756px media stage on the right, beneath an 80px fixed navigation bar. Keep the conversion action in the upper-right rather than adding a hero button stack.
- Conversion is a small berry-colored capsule: a 48px-high gradient button with 14px 28px padding and fully rounded ends; color belongs to actions and imagery, while almost all page canvas remains white or #f7f7f7.
- Make capabilities tangible with miniature objects: softly lit dimensional symbols isolated on white, paired with short labels or small body copy. Every new marketing page needs this tactile device; use simple modeled objects or photographed cutouts when elaborate illustration is unavailable.
- Demonstrations are exhibits rather than dashboards: upright black phones, pale neutral backing, 400px × 422px media stages in an 848px two-column grid with a 48px gap and centered captions.
- Human proof is composed, not boxed into a corporate logo wall: overlapping circular portraits with a 194px central face and 132px–146px neighbors, followed by stacked 36px/44px proof statements and small explanatory lines.
- The closing changes pace rather than shouting again: a #f7f7f7 question-and-answer band, 120px top breathing room, 632px-wide ruled accordions and a restrained legal/localization footer. The main conversion remains available in the fixed header.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm berry | `#e61e4d` | `--color-berry-start` | action | Left stop of the primary action gradient. |
| Deep pink | `#d70466` | `--color-berry-end` | action | Right stop of the primary action gradient. |
| Rose berry | `#e31c5f` | `--color-berry-mid` | action | Middle stop of the primary action gradient. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal | `#222222` | `--color-ink` | text, action | Headlines, labels and secondary dark actions. |
| Secondary gray | `#6a6a6a` | `--color-muted` | text | Supporting sentences, feature explanations and proof captions. |
| Divider gray | `#dddddd` | `--color-rule` | border | Accordion separators and outlined inputs. |
| Soft gray | `#f7f7f7` | `--color-soft` | background, surface | Closing question band, subtle media backing and profile cards. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Primary page stage, caption strips and inverse action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| full directory footers | Footer hairline | `#ebebeb` | `--color-footer-rule` | border | Fine separation above legal and localization utilities. |
| discovery interfaces and assisted-conversion pages | Control gray | `#f2f2f2` | `--color-control` | surface | Circular utility controls and subdued secondary controls. |
| assisted-conversion pages | Warm support tint | `#f4f2ec` | `--color-cream` | surface | Compact specialist-support invitation. |

## Typography

- **Airbnb Cereal VF** — All marketing headings, paragraphs, captions and controls. Rounded geometric sans with a high x-height, open counters and approachable, substantial lowercase forms. If unavailable, use **DM Sans**. Use weights 400–700; preserve compact display widths and negative headline tracking. Font stack: "Airbnb Cereal VF", "DM Sans", Circular, -apple-system, system-ui, Roboto, "Helvetica Neue", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Airbnb Cereal VF | 600 | 60px | 64px | -0.04em | Opening promise in a compact centered text block. |
| heading | Airbnb Cereal VF | 600 | 54px | 58px | -0.03em | Centered chapter headings, usually two lines. |
| proof | Airbnb Cereal VF | 600 | 36px | 44px | -0.04em | Stacked audience and commercial proof statements. |
| hero-support | Airbnb Cereal VF | 400 | 24px | 1.5 | normal | Opening support line beneath the display. |
| section-support | Airbnb Cereal VF | 400 | 22px | 32px | normal | Chapter support lines and question accordion labels. |
| feature-title | Airbnb Cereal VF | 500 | 18px | 24px | normal | Centered labels beneath demonstrations. |
| feature-body | Airbnb Cereal VF | 400 | 16px | 22px | normal | Short feature explanations. |
| body | Airbnb Cereal VF | 400 | 16px | 1.5 | normal | Question answers and longer explanatory paragraphs. |
| action | Airbnb Cereal VF | 500 | 16px | 1.25 | normal | Primary and secondary action labels. |
| proof-caption | Airbnb Cereal VF | 400 | 16px | 1.25 | normal | Short qualifiers immediately below proof figures. |
| caption | Airbnb Cereal VF | 400 | 14px | 18px | normal | Photographic story captions and footer links. |
| utility | Airbnb Cereal VF | 500 | 14px | 18px | normal | Localization labels and footer column headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| calculator-led conversion pages | earnings-display | Airbnb Cereal VF | 700 | 60px | 64px | -0.03em | Calculated outcome and matching bold chapter headings. |
| assisted-conversion pages | benefit-title | Airbnb Cereal VF | 700 | 28px | 32px | -0.01em | Three-part benefit statements. |
| expert-network sections | profile-name | Airbnb Cereal VF | 700 | 26px | 30px | -0.007em | Names in raised profile cards. |
| discovery and catalog pages | directory-heading | Airbnb Cereal VF | 500 | 22px | 26px | -0.02em | Tabbed inspiration directory heading. |
| discovery and catalog pages | shelf-heading | Airbnb Cereal VF | 600 | 20px | 1.2 | -0.009em | Left-aligned headings for image shelves. |
| assisted-conversion pages | benefit-body | Airbnb Cereal VF | 400 | 18px | 28px | normal | Longer explanations below benefit labels. |

**Notes:**

- Use one sans family throughout. The friendly character comes from rounded letterforms and tightly fitted headlines, not a second decorative font.
- Tracking tightens to -0.04em in opening promises and proof; section leads use -0.03em. Paragraphs and small labels retain normal tracking.
- Prefer sentence case and deliberate two-line headlines. Center the copy within its own column, not necessarily across the whole viewport.
- The calculator-led variant increases the display weight to 700; do not average this into the default 600-weight marketing style.

## Layout

**Density:** Airy marketing chapters with compact text groups; discovery shelves are intentionally denser.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small title-to-detail and utility gaps. |
| 12px | Discovery shelf gutters and tighter caption relationships. |
| 16px | Space below large chapter headings and story caption padding. |
| 24px | Media-to-caption spacing, story card gutters and accordion spacing. |
| 32px | Profile-card gaps and benefit icon-to-title separation. |
| 48px | Two-column media gutters and directory footer padding. |
| 56px | Chapter-to-media breathing room and feature row spacing. |
| 80px | Marketing side gutters and navigation height. |
| 120px | Major chapter separation and question-band top padding. |

### Containers and grids

- **marketing-container**: max width 1440px · side padding 80px. Centered outer marketing stage; content is narrower inside it.
- **chapter-copy**: max width 600px. Centered heading block, with supporting lines commonly limited to 580px.
- **feature-grid**: max width 848px · 2 columns · gap 48px. Two 400px media exhibits per row; captions centered below, with 56px between rows.
- **question-column**: max width 632px. Narrow left-aligned answers within a centered closing band.
- **story-grid**: 3 columns · gap 24px. Three 300px photographic story cards centered on the white stage.
- **discovery-container** (only for discovery and catalog pages): max width 1920px · side padding 48px. Broad horizontal photographic shelves; allow sideways browsing rather than shrinking imagery to fit an arbitrary column count.
- **footer-columns** (only for full directory footers): 3 columns · gap 16px · side padding 48px. Three evenly distributed columns with a legal utility row below.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-action | 800px |
|  | story-card | 12px |
|  | utility-control | 50% |
| expert-network sections | profile-card | 30px |
| assisted-conversion pages | support-panel | 24px |
| discovery and catalog pages | category-tile | 20px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | story-card | `0px 0px 0px 1px rgba(0,0,0,0.04), 0px 6px 16px 0px rgba(0,0,0,0.12)` | A faint edge and low, soft lift beneath photographic story cards. |
| expert-network sections | profile-card | `1.1px 1.1px 1.1px 0px rgb(255,255,255), 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 6.7px 9.9px 0px rgba(0,0,0,0.12)` | Soft molded lift on pale profile cards. |

### Surfaces

#### White stage · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #ffffff`

**Observed:** Most chapters share one uninterrupted white ground; content is grouped through spacing rather than colored rectangles.

**Transfer:** Keep the canvas continuous across benefit, proof and demonstration chapters.

#### Question band · level 0

**Use:** The closing objection-handling region.

**CSS:** `background: #f7f7f7`

**Observed:** A full-width pale gray band holds a large centered heading and narrower ruled answers, continuing into the compact footer.

**Transfer:** Use the tonal shift to signal practical questions after the visual story.

#### Frosted navigation · level 2

**Use:** Fixed conversion navigation.

**CSS:** `background: rgba(255,255,255,0.9); backdrop-filter: blur(10px); border-bottom: 1px solid #ffffff`

**Observed:** The translucent white layer stays visually light above scrolling media.

**Transfer:** Retain legibility without turning the header into a dark toolbar.

#### Warm support panel · level 1

**Only for:** assisted-conversion pages

**Use:** A small invitation to speak with a specialist.

**CSS:** `background: #f4f2ec; border-radius: 24px; overflow: clip`

**Observed:** An 848px × 148px horizontal panel combines a small illustration, brief explanation and dark capsule action.

**Transfer:** Use for human assistance next to a more involved decision, not as a repeated feature-card background.

## Components

### Primary button

**Use:** Persistent main conversion action.

**CSS:** `background: linear-gradient(to right, #e61e4d 0%, #e31c5f 50%, #d70466 100%); color: #ffffff; border-radius: 800px; padding: 14px 28px; height: 48px; border: none`

**Text style:** `action` — Airbnb Cereal VF 500 · 16px/1.25

**Observed:** A single short label; the default location is the upper-right navigation. There is no competing secondary button beside it.

**States:** Declared: hover retains the gradient and removes text decoration; focus-visible uses 0 0 0 2px rgba(255,255,255,0.8), 0 0 0 4px #222222; active uses scale(0.96).

**Transfer:** Keep the label brief and task-oriented.

### Conversion navigation

**Use:** Maintain access to the main action through a long marketing story.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 80px; z-index: 100; background: rgba(255,255,255,0.9); backdrop-filter: blur(10px); border-bottom: 1px solid #ffffff`

**Observed:** A small brand symbol sits left and the Primary button right within 80px side gutters; the center is deliberately unoccupied.

**Transfer:** Use a compact identity mark and one conversion action, not a full product-menu hierarchy.

### Photo story card

**Use:** Introduce real practitioners or customer outcomes.

**CSS:** `width: 300px; border-radius: 12px; overflow: hidden; display: grid; grid-template-columns: 1fr; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.04), 0px 6px 16px 0px rgba(0,0,0,0.12)`

**Text style:** `caption` — Airbnb Cereal VF 400 · 14px/18px

**Observed:** A 300px × 356px documentary photograph sits above a white caption strip with 16px vertical padding. The caption is centered within a 200px text width, typically two lines.

**Transfer:** Tell a tiny concrete story about a person doing something rather than using a generic testimonial quote.

### Feature exhibit

**Use:** Explain one capability with a large visual and small caption.

**CSS:** `width: 400px; text-align: center`

**Text style:** `feature-title` — Airbnb Cereal VF 500 · 18px/24px

**Observed:** A 400px × 422px phone demonstration is followed after 24px by a title and a muted explanation, generally two lines and about 311px wide. The tile itself has no raised card boundary.

**Transfer:** Show one useful task at a time; place the detail below, not over the demonstration.

### Question accordion

**Use:** Resolve practical objections in the closing band.

**CSS:** `max-width: 632px; border-bottom: 1px solid #dddddd; margin-bottom: 24px`

**Text style:** `section-support` — Airbnb Cereal VF 400 · 22px/32px

**Observed:** A full-width label and a 16px chevron form a space-between trigger with 24px bottom padding. An expanded first group reveals 16px/24px answers, small subquestions and underlined links; subsequent groups remain compact.

**Transfer:** Group related questions under plain-language topics rather than making every sentence a separate oversized card.

### Footer link

**Use:** Understated policy and support navigation.

**CSS:** `color: #222222; border-radius: 4px; position: relative`

**Text style:** `caption` — Airbnb Cereal VF 400 · 14px/18px

**Observed:** Small inline legal links in the compact footer; the expanded directory variant stacks the same restrained text beneath utility-weight headings.

**States:** Declared: hover underlines at 1px thickness with inherited color; focus-visible reverses to white on #3F3F3F with a 2px shadow ring.

### Expert profile card

**Only for:** expert-network sections

**Use:** Make trusted assistance feel human and locally relevant.

**CSS:** `width: 280px; height: 352px; padding: 30px; background: #f7f7f7; border-radius: 30px; display: flex; flex-direction: column; align-items: center; gap: 18px; box-shadow: 1.1px 1.1px 1.1px 0px #ffffff, 0px 0px 0px 1px rgba(0,0,0,0.08), 0px 6.7px 9.9px 0px rgba(0,0,0,0.12)`

**Text style:** `profile-name` — Airbnb Cereal VF 700 · 26px/30px · tracking -0.007em

**Observed:** A 140px circular headshot, bold name, short location and a white inset metric strip create a softly molded personal profile. Four cards sit in a horizontal row with 32px gaps.

**Transfer:** Use real people and relevant credentials; keep fine-print details subordinate to the face and name.

### Category object tile

**Only for:** discovery and catalog pages

**Use:** Browse high-level categories through tangible visual symbols.

**CSS:** `width: 183px; height: 183px; padding: 24px; background: #f7f7f7; border-radius: 20px`

**Observed:** A 135px dimensional object illustration is centered within the square; its label sits outside below with an 8px gap. Seven tiles appear in one broad shelf.

**Transfer:** Reuse the miniature-object visual language in an efficient browsing surface.

## Imagery and graphics

### Rounded hero vignette

**Use:** Primary marketing opening media.

**Observed:** A warm orange balloon floats in a pale blue and cream sky inside a softly rounded square, surrounded by a much larger white media stage. The visible vignette is around 310px across within a 756px square animation area, balancing the text without filling the right column edge to edge. Other task-led openings use an upright oversized black phone instead.

**Transfer:** Use a single emotionally legible view of the product's outcome, naturally lit and simply framed. A rounded photograph or a polished object rendering is the minimum equivalent; keep the surrounding whitespace.

**Build:** Place a rounded-square image near the center of a 756px white stage; use object-fit: cover and a radius around 40px as design guidance. Back the bottom of the stage with a broad radial shadow using rgba(34,34,34,0.3) fading to transparent, at 0.15 overall opacity. Keep the effect nearly invisible rather than a colored glow.

### Tactile miniatures

**Use:** Signature capability symbols and category illustrations.

**Observed:** Small, three-quarter-view objects model real materials: brushed metal, glazed food, soft towels, polished camera bodies, painted architecture and tiny green landscapes. Light falls softly from above-left, with short contact shadows, vivid but localized colors and no heavy enclosing badge.

**Transfer:** Represent abstract capabilities with familiar physical metaphors. Use a few well-lit modeled primitives or a clean photographed cutout as a minimum, retaining volume, material differences and a grounded contact shadow.

**Build:** Compose each symbol in an 88px–112px square transparent SVG or rendered image. Layer a flattened ellipse at the base using rgba(34,34,34,0.12), blur it 4px, then place a three-quarter-view object with lighter upper-left planes and darker right faces. Use small colored inserts rather than a uniformly saturated silhouette; display directly on white.

### Documentary people

**Use:** Story cards and question-resource photography.

**Observed:** People are shown in action and in context: outside with animals, working on a craft or moving through a city. Portrait-oriented crops retain environmental information, natural light and warm human expressions; colors are photographic rather than filtered into the action palette.

**Transfer:** Photograph real users in the setting where the new product matters, showing activity rather than formal posed business portraits.

### Portrait cluster

**Use:** Humanize quantified proof.

**Observed:** Five circular headshots overlap into a shallow horizontal arc; the central face is largest at 194px, flanked by 132px–146px circles. Backgrounds remain photographic, not colored avatar chips.

**Transfer:** Use genuine audience or customer portraits with a broad range of faces and similarly close framing.

**Build:** Create five circular image masks with object-fit: cover, center-align them vertically, and overlap adjacent masks slightly. Place the 194px central circle above the 146px inner and 132px outer circles in stacking order. Keep the total cluster about 630px wide on white.

### Phone exhibits

**Use:** Single-feature demonstrations and paired capability grids.

**Observed:** Black rounded phone hardware frames crisp white interfaces. Tall devices rise from pale gray square media panels and are cleanly clipped at the panel bottom. A central solo phone is displayed in a 600px × 520px stage; paired stages are 400px × 422px. Controls are small frosted dark circles near the media corner.

**Transfer:** Put one credible workflow into a realistic device silhouette; simplified interface content with real product imagery is enough, but preserve the physical frame, legible hierarchy and restrained backing.

### Catalog photography

**Only for:** discovery and catalog pages

**Use:** Dense horizontally browsable product shelves.

**Observed:** Near-square photos carry most of the color: interiors, landscapes, architecture and people. Rounded image corners, small overlay favorite controls and tiny detail lines make the shelf useful without heavy card chrome.

**Transfer:** Use consistent image aspect ratios and small metadata below. Preserve vivid real-world variation rather than tinting every photo to match the brand accent.

### Icons

**Observed:** Navigation and utility icons are compact monochrome SVGs, commonly 16px, with simple chevrons, arrows and familiar controls. Media controls sit in 32px circles. Dimensional category illustrations are a separate visual language, not enlarged utility glyphs.

**Transfer:** Use simple dark functional icons at 16px with generous clear space; use tactile miniature art rather than line icons when explaining a category or capability.

## Section recipes

How recurring sections are built.

### First screen: Two-object opening

**Observed:** An 80px Conversion navigation sits above an 820px white hero. Within 80px side gutters, a compact centered copy column occupies roughly the left two-fifths and a 756px square media stage the right. The headline uses display, fits a 476px width and forms two strong lines; 16px below it, hero-support is limited to 420px. Both are centered in their own column around the middle-lower part of the viewport. Behind them are the White stage and a very faint bottom radial shadow; the rounded photographic vignette floats above this ground. Within the first 900px the navigation action, complete promise, support line and main vignette are visible; the next centered chapter starts below the fold. The only main action is the upper-right Primary button.

**Transfer:** Give another product one concrete outcome image or tactile object on the right, not a collection of abstract decorations. Maintain the asymmetry of a centered copy block beside a larger visual stage. Task-led variants can substitute an oversized device; calculator-led pages pair the larger bold outcome with a map or other interactive result. Discovery pages instead open with search and immediate photographic shelves.

**Avoid:** Do not turn this into a centered text-over-full-bleed-photo hero, add two competing hero buttons, or stretch the small vignette to fill the entire media stage.

**Text style:** `display` — Airbnb Cereal VF 600 · 60px/64px · tracking -0.04em

### Centered chapter pair

**Observed:** Heading uses a centered 600px maximum block with 16px below, followed by muted section-support, commonly within 580px. Major chapters have 120px separation, and 56px is a recurring lead-in to visual content.

**Transfer:** State a reader benefit in one or two lines and add one sentence explaining how it works.

**Text style:** `heading` — Airbnb Cereal VF 600 · 54px/58px · tracking -0.03em

### Human story triptych

**Observed:** A Centered chapter pair introduces three Photo story cards with 24px gutters. Portrait images dominate; the small centered caption strips describe specific people and actions.

**Transfer:** Show the range of outcomes through a few distinct human examples rather than repeating equivalent product thumbnails.

### Miniature capability field

**Observed:** A centered heading introduces five tactile miniature symbols in a two-column grid; symbols sit to the left of concise 18px titles and 16px explanations. The service-category variant centers nine labeled miniatures in two balanced rows, five then four, without card boxes.

**Transfer:** Choose the arrangement based on whether the symbols need explanatory sentences or just category labels. Preserve the miniature-object device even when the new product is abstract.

### Portraits and stacked proof

**Observed:** A Centered chapter pair leads to the Portrait cluster. Below it, proof uses 36px/44px statements with 8px to muted 16px/20px qualifiers. Proof statements stack vertically with a fine divider and small qualification text below, not in a row of giant colored numerals.

**Transfer:** Use one or two verifiable outcome statements and clear context; if no audience numbers exist, use concrete proof of capability with the same human cluster and centered hierarchy.

**Text style:** `proof` — Airbnb Cereal VF 600 · 36px/44px · tracking -0.04em

### Solo demonstration

**Observed:** A two-line heading and muted support line introduce one central phone in a 600px × 520px stage. The upright device is clipped into the lower boundary, while a small media control sits near the lower-right edge. A 120px break follows.

**Transfer:** Explain one compelling result through a focused workflow rather than a full product tour.

### Paired capability exhibits

**Observed:** A Centered chapter pair leads to the feature-grid. Feature exhibits place large media first, then title and short explanation. Two rows explain distinct management tasks; the second row is not given a redundant chapter heading.

**Transfer:** Group two or four related capabilities into one coherent chapter, keeping caption lengths similarly compact.

### Practical closing

**Observed:** The Question band begins with 120px top spacing and a centered large question heading. After 56px, a 632px Question accordion column switches to left-aligned practical text. The first group is expanded; remaining groups show a title, chevron and 1px rule. The gray region continues to a compact 78px legal/localization footer with 24px vertical padding. There is no monumental final conversion banner.

**Transfer:** End the visual pitch with credible answers and unobtrusive utility navigation while the fixed conversion action stays accessible.

**Text style:** `heading` — Airbnb Cereal VF 600 · 54px/58px · tracking -0.03em

### Assisted decision chapter

**Only for:** calculator-led and assisted-conversion pages

**Observed:** The opening pairs a bold 60px outcome and simple adjustable inputs with a 631px × 599px map. Later, three 88px benefit symbols lead into large bold chapter headings, Expert profile cards and reassurance rows. The question region adds photographic resource cards and a small assistance prompt before a full three-column directory footer.

**Transfer:** Use for products where a personalized estimate, expert support and risk reduction are more useful than an entirely linear demonstration.

### Discovery shelves and directory ending

**Only for:** discovery and catalog pages

**Observed:** A search-led header introduces broad shelves with 20px headings, 12px image gutters and compact detail lines. Tactile Category object tiles and smaller destination images broaden discovery. The ending becomes a pale gray tabbed inspiration directory with a 22px heading, six columns of paired text links, then three footer columns and a ruled legal/localization row.

**Transfer:** For a catalog, prioritize browseable imagery and practical filters; reserve the larger marketing display scale for dedicated conversion narratives.

## Page flow

**Storyline:** Personal promise → tangible range → human and quantified proof → focused product demonstrations → practical objections → restrained utilities.

### Recruit contributors through an emotional promise and concrete examples

1. **Promise** — Two-object opening pairs a short personal benefit with a rounded outcome vignette.
2. **Range and social proof** — A photographic triptych and miniature capability field establish real people and varied possibilities.
3. **Quantified proof** — Overlapping faces and vertically stacked proof statements make scale feel personal.
4. **Product demonstration** — One solo device demonstration, paired discovery exhibits and a four-part tools grid explain the system.
5. **Objection handling and ending** — A pale gray question band with the first answer group open ends in a compact legal and localization footer; conversion remains in the fixed header.

**Transfer:** Use this as the default long-form marketing narrative, adapting chapter order to the product's strongest proof.

### Recruit businesses by making a new channel feel familiar and manageable

1. **Promise** — A compact promise shares the opening with an oversized phone.
2. **Range** — A balanced field of nine miniature category objects makes the offer immediately understandable.
3. **Social and quantified proof** — The shared portrait arc and stacked proof treatment establish audience reach.
4. **Product demonstration** — A solo listing exhibit becomes paired discovery demos and a tools grid.
5. **Objection handling and ending** — The same gray ruled question column and compact utility footer close the narrative.

**Transfer:** Use the device-led opening when the product experience itself is the best introduction.

### Convert a considered decision with a personal estimate and reassurance

1. **Personalized promise** — A large calculated outcome and adjustable input share the opening with a map.
2. **Ease and reassurance** — Three small symbol-led benefits and a compact specialist-support invitation reduce uncertainty.
3. **Human assistance** — Large centered copy introduces raised expert profiles and a dark secondary action.
4. **Risk reduction and capability proof** — Protection rows, additional safeguards and paired phone exhibits answer operational concerns.
5. **Objection handling** — Photo-led question resources and accordions lead to an assistance prompt.
6. **Ending** — Qualification text precedes a full three-column footer with a legal/localization baseline.

**Transfer:** Replace the personalized earning result with a relevant cost, time or outcome calculator; use assistance only where the decision warrants it.

### Enable immediate discovery and comparison across a broad catalog

1. **Orientation** — Category navigation and a rounded segmented search open directly onto photo shelves.
2. **Discovery** — Repeated locality or intent-led shelves combine small headings, photography and compact details.
3. **Broaden possibilities** — Miniature category tiles and compact destination imagery offer alternative paths.
4. **Directory and ending** — A pale gray tabbed link directory transitions to three support columns and a ruled legal utility row.

**Transfer:** Use this denser variant for browse-first experiences, not as the default for a new single-product landing page.

## Writing

Warm, practical and directly beneficial. Confidence comes from concrete tasks and reassuring plain language rather than technical jargon or inflated spectacle.

**Do not copy:** Do not reuse Airbnb names, symbols, product names, branded illustrations, customer identities, numeric claims, fees, guarantees or quotations as your own. Source examples illustrate voice only; all claims and proof must belong to the new product.

- **Addressing the reader:** Speak directly to you and your work, space or customers. Use we sparingly to explain what the platform does for the reader.
- **Rhythm:** Short sentence-case promises, often split into two balanced clauses. Follow with one simple explanatory sentence; use compact verb-led labels for features and plain questions for help.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Turn a personal ambition into a concrete benefit with everyday words. | 6–9 words | “Get paid to do what you love”<br>“Give your business a new home” |
| Chapter headline | Pair an appealing result with a practical payoff. | 5–10 words | “Show up beautifully. Get booked instantly.”<br>“World-class tools for your local business” |
| Supporting line | Explain what the product enables in one direct sentence. | 10–18 words | “Create a standout listing and fill your calendar with instant booking.” |
| Feature label | Start with a familiar action verb. | 2–5 words | “Manage reservations”<br>“Get paid quickly” |
| Primary action | Short, low-friction next step. | 2–3 words | “Get started” |
| Question heading | Acknowledge uncertainty without making it feel like a problem. | 3–5 words | “Your questions, answered” |

**Words and phrasing to use:** your; get started; help; create; show up; reach; manage; easily; local

**Avoid:** revolutionary; disruptive; synergy; unlock limitless potential; best-in-class solutions; frictionless ecosystem

**Rules:**

- Give each chapter one reader benefit, then explain the mechanism.
- Prefer a useful verb over a noun-heavy feature name.
- Place factual context next to numerical proof; keep qualifications readable and separate from the headline.
- Use questions to help someone decide, not to manufacture urgency.
- Keep CTA wording consistent throughout a marketing narrative.

## Do's and Don'ts

### Do

- Keep the default headline at 60px/64px and weight 600 with -0.04em tracking.
- Use 54px/58px centered chapter headings with a 16px separation from support copy.
- Preserve the 848px paired-exhibit width and 48px gutter at desktop.
- Keep major chapter breaks around 120px while small captions remain tightly grouped.
- Give miniature objects realistic material differences and a soft contact shadow.
- Make primary actions 48px high with 14px 28px padding and rounded capsule ends.
- Use #6a6a6a for supporting copy and #222222 for the heading above it.
- Shift to #f7f7f7 for practical closing questions and keep answers in a 632px column.

### Don't

- Do not replace the rounded geometric sans with a sharp condensed display face.
- Do not use the 700-weight calculator display as the default for every marketing heading.
- Do not put every feature inside a shadowed card; paired exhibits rely on whitespace and pale media backing.
- Do not enlarge miniature capability objects into flat full-section illustrations; their small tactile scale is part of the character.
- Do not make proof numerals enormous or accent-colored; the default proof is 36px/44px charcoal.
- Do not use berry gradients as full-page backgrounds or headline fills.
- Do not turn photographic captions into 24px testimonials; the story strips use 14px/18px.
- Do not add a dark, high-pressure final sales band after the question region; the closing stays pale and practical.

## Motion and responsive

### Motion

**Observed:**

- Primary action declares box-shadow 0.2s cubic-bezier(0.2,0,0,1) and transform 0.1s cubic-bezier(0.2,0,0,1); its active state scales to 0.96.
- Small text links declare text-decoration-thickness, box-shadow and background-color transitions of 0.3s cubic-bezier(0.2,0,0,1).
- Hero and phone stages contain video animation with small play/pause controls.

**Transfer:**

- Keep pressed feedback localized to the small capsule or utility control.
- Use animated demonstrations to explain one workflow while keeping chapter text stable and readable.

**Unknown:**

- Exact hero animation choreography and scroll-trigger timing are not established.
- No reduced-motion rendering is established.

### Responsive

**Observed:**

- Width breakpoints include 744px, 950px, 1128px, 1440px and 1920px; the described compositions are desktop.

**Transfer:**

- On narrow screens, stack the promise above its object stage and keep the visual focused on one subject.
- Collapse paired exhibits into readable single-column stages; preserve the miniature-object scale rather than stretching symbols.
- Let discovery shelves remain horizontally browseable instead of squeezing many tiny images into a fixed row.

**Unknown:**

- Mobile typography, gutters, header transformations and exact stacking breakpoints are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
