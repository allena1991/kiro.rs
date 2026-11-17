# Biograph — hospitality meets deep science

## Overview

A premium, human-centered style that makes complex expertise feel like a private hospitality experience. Predominantly white and pale gray editorial spaces alternate with charcoal chapters and cinematic, warmly lit photography. Regular-weight geometric grotesk headlines, practical sans-serif text and a rare elegant serif quotation balance scientific depth with personal reassurance; the page breathes even when the content becomes detailed.

### Essentials

- The first impression is an illuminated world, not a dashboard: a full-bleed 900px photographic opening, a 68px regular headline low on the left, and a small light action beneath it.
- Headlines feel spoken rather than shouted: Aeonik at 68px/0.95 with -0.02em tracking for major promises and 52px/1 with -0.01em for section leads; 10px uppercase labels with 3px tracking introduce the chapters.
- Light editorial expanses do most of the explaining: white and #f9f9f9 dominate, interrupted by full-width near-black chapters. Saturated color belongs to media, scientific objects and tiny links, not broad flat UI fills.
- Actions are deliberately modest rectangles: 41px tall, 8px corners and 10px 20px padding, reversing from charcoal on light to translucent white on dark.
- Photography makes expertise tangible: warm wood, glass, stone, natural light and unposed human interactions fill large rounded frames; use three 433px-wide portrait panels with 10px gutters for a process story. Without bespoke media, photograph the real setting and hands using the product rather than substituting generic interface tiles.
- Proof becomes an editorial object: use 92px regular numerals above bottom-aligned explanations in nearly square panels, and an isolated 56px Instrument Serif quotation with a tiny portrait attribution.
- Every landing page carries a cinematic closing promise: centered 68px white type and one small light button over immersive human or outdoor footage, followed by a spacious white directory footer. A carefully art-directed still is the fallback for unavailable film.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Information blue | `#0095ff` | `--color-link` | link | Small supporting links, especially the FAQ escape link; not a brand-wide fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, text, border | Default editorial canvas, text on dark chapters and white edges on pale panels. |
| Almost white | `#f9f9f9` | `--color-pale` | surface, background | Cards, alternating editorial bands and pale plan panels. |
| Pale divider | `#f0f0f0` | `--color-rule` | border | Low-contrast separators on white, made with black at 6% opacity. |
| Pearl action | `#e6e6e6` | `--color-light-action` | action | Visible light button over black; white at 90% opacity. |
| Soft white text | `#b3b3b3` | `--color-reverse-support` | text | Hero support text; white at 70% over the darkest image regions. |
| Silver text | `#a8aeb9` | `--color-reverse-muted` | text | Visible secondary text on dark chapters; rgba(208,214,224,0.8) over near black. |
| Cool gray text | `#686873` | `--color-muted` | text | Paragraphs, secondary labels and directory links on light backgrounds. |
| Blue slate | `#28373f` | `--color-slate` | background | Lighter corner of the diagonal dark scientific chapter. |
| Charcoal ink | `#27272c` | `--color-ink` | text, surface | Main headings and strong text on light surfaces; also solid explanatory panels. |
| Action charcoal | `#161719` | `--color-action` | action, surface | Filled buttons on white. |
| Deep charcoal | `#111214` | `--color-chapter` | background, surface | Dark experience chapters and contrasting premium plan cards. |
| Near black | `#09090a` | `--color-night` | background | Backing for cinematic closing sections. |
| Gradient black | `#020202` | `--color-gradient-black` | background | Dark corner of the scientific chapter. |
| Cinema black | `#000000` | `--color-black` | background | Photographic opening backing and image scrims. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| process detail pages | Results charcoal | `#18181a` | `--color-results` | background | Dark middle chapter of a step-by-step explanation. |
| business audience pages | Warm mineral | `#e8e7df` | `--color-warm-proof` | surface | Warm proof panel beside a large human photograph. |
| plan detail pages | Premium black | `#111111` | `--color-premium` | surface | Continuous dark panel family for the extended plan detail. |
| plan presentations | Ice cyan | `#95faf9` | `--color-cyan-soft` | accent | Blurred light behind the entry-tier physical card. |
| plan presentations | Electric cyan | `#3dd2ff` | `--color-cyan` | accent | Second end of the entry-tier glow. |
| plan presentations | Lilac light | `#c75eff` | `--color-violet` | accent | Lighter end of the premium card glow. |
| plan presentations | Deep indigo | `#130fff` | `--color-indigo` | accent | Blue-violet end of the premium card glow. |

## Typography

- **Aeonik** — Display headlines, section leads, plan titles and large numerals. Circular, clean geometric grotesk with open, light-looking regular forms. If unavailable, use **Manrope**. 400 and 500; retain the tight headline tracking and compare line breaks. Font stack: "Aeonik", "Manrope", Arial, sans-serif.
- **Apercu Pro** — Body, labels, actions, navigation and captions. Practical grotesk with subtly humanist details; regular text and medium labels. If unavailable, use **DM Sans**. 400 and 500; keep small text restrained rather than bold. Font stack: "Apercu Pro", "DM Sans", Arial, sans-serif.
- **Instrument Serif** — Isolated editorial testimonial. Narrow, high-contrast serif, upright and delicate rather than italic. Font stack: "Instrument Serif", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| stat | Aeonik | 400 | 92px | 0.95 | -0.02em | Large open-panel quantified proof. |
| display | Aeonik | 400 | 68px | 0.95 | -0.02em | Opening promise and centered closing promise. |
| quote | Instrument Serif | 400 | 56px | 1.1 | normal | Large standalone testimonial, visually distinct from sans-serif proof cards. |
| heading | Aeonik | 400 | 52px | 1 | -0.01em, features "blwf", "cv03", "cv04", "cv09", "cv11" | Main section headings, usually centered and no more than two lines. |
| statement | Aeonik | 400 | 32px | 1.2 | normal | Editorial statement paragraphs and compact proof numbers. |
| card-title | Aeonik | 400 | 24px | 1.2 | normal | Plan names and internal card headings. |
| hero-support | Apercu Pro | 400 | 18px | 1.5 | normal | Opening and closing supporting sentences. |
| body | Apercu Pro | 400 | 16px | 1.5 | normal | Core paragraphs and FAQ questions. |
| item-label | Apercu Pro | 500 | 16px | 1.5 | normal | Numbered process captions and feature group labels. |
| small | Apercu Pro | 400 | 14px | 1.5 | normal | Navigation, button text, short feature descriptions, social proof and plan lists. |
| caption | Apercu Pro | 400 | 12px | 1.5 | normal, features "blwf", "cv03", "cv04", "cv09", "cv11" | Small footer positioning line and secondary annotations. |
| eyebrow | Apercu Pro | 500 | 10px | 1 | 3px, uppercase, features "blwf", "cv03", "cv04", "cv09", "cv11" | Widely spaced chapter identifiers above headings. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| business audience pages | business-stat | Aeonik | 400 | 72px | 0.95 | -0.02em | Bottom-anchored numbers in tall illustrated proof cards. |

**Notes:**

- Keep the visual weight of all headline roles at 400; hierarchy comes from scale and placement rather than boldness.
- Tighten tracking only on the 52px and larger sans-serif roles. Body text remains normally spaced; labels deliberately open out to 3px.
- Use the serif only for the isolated testimonial moment, not for every card or heading.

## Layout

**Density:** Airy across chapters, compact within lists: extensive editorial pauses surround tightly packed, useful detail.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Repeated card gutters and compact item spacing. |
| 15px | Eyebrow-to-heading gap and media-to-caption spacing. |
| 20px | Heading-to-support and support-to-action gaps. |
| 30px | Plan card padding and grouped content separation. |
| 40px | Editorial panel padding. |
| 50px | Section introduction to its content grid. |
| 60px | Desktop page side inset. |
| 80px | Footer top padding and larger action-to-content pause. |
| 150px | Default chapter top and bottom breathing room. |
| 200px | Extra spacious testimonial chapter padding. |

### Containers and grids

- **page container**: max width 1600px · side padding 60px. Centered outer content system; at 1440px it leaves a 1320px working width.
- **editorial heading**: max width 800px. Centered headline; supporting paragraphs are slightly narrower.
- **triptych**: 3 columns · gap 10px. Equal media/process cards, compact capability tiles and testimonial columns; each is 433px wide at desktop.
- **plan pair**: max width 1030px · 2 columns · gap 10px. Two equal 510px plan cards centered inside the wider page.
- **faq column**: max width 800px. Single narrow column centered under the FAQ introduction.
- **detail split** (only for plan detail pages): 2 columns · gap 10px · side padding 60px. Plan details keep a roughly 539px purchase panel at left and a wider 771px sequence at right.
- **gallery pair** (only for place and experience pages): 2 columns · gap 10px · side padding 60px. Equal tall images alternate with full 1320px-wide images.

## Corner radius

| Element | Radius |
| --- | --- |
| buttons | 8px |
| cards | 16px |
| media | 16px |
| small thumbnails | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| place pages | location information | `20px 14px 28px 2px rgba(204,211,214,0.52)` | Single white location-information card lifted above a pale background. |
| process detail imagery | glass highlight | `inset 1px 1px 1px 0px rgba(255,255,255,0.09)` | Subtle edge light on floating translucent information strips. |

### Surfaces

#### Editorial canvas · level 0

**Use:** Main page and explanatory sections.

**CSS:** `background: #ffffff; color: #27272c`

**Observed:** Broad unboxed areas alternate with pale bands.

**Transfer:** Leave ample unpainted space around the content.

#### Pale card · level 1

**Use:** Capabilities, social proof and entry plan.

**CSS:** `background: #f9f9f9; border-radius: 16px; box-shadow: none`

**Observed:** Defined by tonal contrast rather than elevation. Larger pale presentation panels can have a white 1px edge.

**Transfer:** Use this for practical grouped information.

#### Dark chapter · level 0

**Use:** Immersive experience and premium comparisons.

**CSS:** `background: #111214; color: #ffffff`

**Observed:** Whole chapters invert, including their support text and actions.

**Transfer:** Use a full dark chapter rather than scattering black cards everywhere.

#### Scientific atmosphere · level 0

**Use:** Object-led capability chapter.

**CSS:** `background: linear-gradient(315deg, #28373f 0%, #020202 100%); color: #ffffff`

**Observed:** A low-key blue-gray diagonal wash backs barely raised translucent cards.

**Transfer:** Keep the gradient dark and close to neutral.

#### Cinema scrim · level 1

**Use:** Legibility over opening photography.

**CSS:** `background: linear-gradient(90deg, #000000 0%, rgba(0,0,0,0) 100%)`

**Observed:** Left-side darkness joins top and bottom black fades while the illuminated image remains visible.

**Transfer:** Match the scrim to the text placement rather than darkening all subjects equally.

#### Floating glass · level 2

**Only for:** process detail imagery

**Use:** Tiny explanatory overlays on photographs.

**CSS:** `background: rgba(255,255,255,0.08); border-radius: 16px; backdrop-filter: blur(10px); box-shadow: inset 1px 1px 1px 0px rgba(255,255,255,0.09)`

**Observed:** Compact strips float within the image, not across the editorial canvas.

**Transfer:** Summarize a single meaningful signal; keep interface internals subordinate.

#### Mineral proof · level 1

**Only for:** business audience pages

**Use:** Measured outcomes beside a human photograph.

**CSS:** `background: #e8e7df; border-radius: 16px; padding: 40px`

**Observed:** Warm neutral panel with a heading high and divided outcome rows low.

**Transfer:** Use warmth as a tonal change, not a saturated campaign color.

#### Premium detail · level 1

**Only for:** plan detail pages

**Use:** Long-form premium tier information.

**CSS:** `background: #111111; border: 1px solid rgba(255,255,255,0.03); border-radius: 16px`

**Observed:** A series of closely spaced panels reads as a continuous dark world.

**Transfer:** Keep the purchase summary visually connected to the scrolling detail.

## Components

### Fixed navigation

**Use:** Persistent orientation with one compact conversion action.

**CSS:** `position: fixed; top: 0px; height: 64px; width: 100%; z-index: 10; backdrop-filter: blur(10px); padding: 13px 60px`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** Spaced wordmark left, category links centered, login and compact join action right. White text and a white button over dark media reverse to dark links and a dark button on light sections. Navigation actions use 8px 14px padding; the compact filled action is 35px tall.

### Light button

**Use:** Conversion over dark imagery or a dark plan.

**CSS:** `background: rgba(255,255,255,0.9); color: #27272c; border-radius: 8px; padding: 10px 20px; height: 41px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** Text-only, intrinsic width in editorial sections; stretches across the plan interior. No oversized arrow treatment.

### Dark button

**Use:** Conversion within light editorial sections.

**CSS:** `background: #161719; color: #ffffff; border-radius: 8px; padding: 10px 20px; height: 41px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** The same geometry as the Light button, simply reversed.

### Information link

**Use:** Secondary help destination.

**CSS:** `color: #0095ff; text-decoration-line: underline; text-decoration-thickness: 1px; text-underline-offset: 5px`

**Text style:** `body` — Apercu Pro 400 · 16px/1.5

**Observed:** Embedded in a gray support sentence rather than placed in a separate action row.

**States:** Declared: hover retains #0095ff with a 1px underline offset by 5px; focus-visible not specified.

### Process card

**Use:** Explain a sequence through lived experience.

**CSS:** `display: flex; flex-direction: column; gap: 15px`

**Text style:** `item-label` — Apercu Pro 500 · 16px/1.5

**Observed:** Tall rounded photograph above a medium-weight numbered label and regular body description; cards sit without an enclosing painted shell. The media occupies roughly 433px by 533px.

**Transfer:** Show preparation, meaningful interaction and outcome rather than three abstract icons.

### Capability tile

**Use:** Dense but approachable feature inventory.

**CSS:** `background: #f9f9f9; border-radius: 16px; padding: 8px; height: 71px; display: flex; gap: 10px; align-items: center`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** 55px square thumbnail left; medium 14px title above a regular 14px explanation. Three columns share tight gutters; a white fade softens the lower inventory into a centered reveal action.

**Transfer:** Use recognizable miniatures or material studies instead of repeated generic line icons.

### Plan card

**Use:** Compare two levels of service.

**CSS:** `background: #f9f9f9; border-radius: 16px; padding: 30px; display: flex; flex-direction: column; gap: 30px; width: 510px`

**Text style:** `card-title` — Aeonik 400 · 24px/1.2

**Observed:** Small card artwork, centered name and support line, full-width Dark button, then left-aligned feature list. The premium sibling reverses to Dark chapter and Light button. Price and deposit rows appear only in the purchase comparison.

**Transfer:** Keep the two tiers equally legible; differentiate by depth and surface, not a giant recommended badge.

### Stat panel

**Use:** Turn quantitative proof into a spacious visual moment.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 20px 30px 30px; height: 439px`

**Text style:** `stat` — Aeonik 400 · 92px/0.95 · tracking -0.02em

**Observed:** Oversized number at top left, 32px percent sign aligned high, body explanation pinned low. Three adjoining panels share the width; their edges remain exceptionally faint.

**Transfer:** Use verified metrics with short explanations, preserving the empty space between number and meaning.

### Testimonial card

**Use:** Compact social proof in unequal-height columns.

**CSS:** `background: #f9f9f9; border-radius: 16px; display: flex; flex-direction: column; gap: 20px`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** Tiny square portrait, name and professional attribution at the top; platform mark at the far right; gray quote beneath. Content-driven heights form a three-column masonry-like wall; inner text has 15px side insets.

**Transfer:** Retain attribution specificity rather than turning these into anonymous review stars.

### FAQ row

**Use:** Objection handling without a heavy accordion shell.

**CSS:** `max-width: 800px; padding: 25px 0px; display: flex; align-items: center; justify-content: space-between; border-top: 1px solid rgba(0,0,0,0.06)`

**Text style:** `body` — Apercu Pro 400 · 16px/1.5

**Observed:** Left question and small plus at the right, in a 28px control. Closed rows are roughly 78px tall; no colored container.

**Transfer:** Use concise questions that remove practical friction.

### Directory footer

**Use:** A clear and unusually airy end after the cinematic close.

**CSS:** `background: #ffffff; padding: 80px 60px 40px; display: flex; flex-direction: column; gap: 80px`

**Text style:** `small` — Apercu Pro 400 · 14px/1.5

**Observed:** Small brand symbol left above a low-positioned two-line positioning statement and tiny icon links; four directory columns occupy the right. A faint divider precedes copyright left and small legal links right. Overall height is 621px at desktop.

**Transfer:** Keep the compact identity and dense useful directory, rather than replacing it with a second giant promotional headline.

## Imagery and graphics

### Illuminated real world

**Use:** Opening atmosphere and immersive experience chapters.

**Observed:** Architectural night scenes make warm vertical timber fins and glass glow against deep black. People are naturally positioned within the environment; the building occupies the center while dark foreground protects low-left copy. Interior images emphasize warm wood, mineral surfaces, plants, reflected water and careful pools of light.

**Transfer:** Stage the real product or service environment with the same warm interior/cool-dark exterior contrast. If architecture is irrelevant, use a real workbench, studio or workspace with a single illuminated focal area; preserve the environmental scale rather than making a floating software window.

### Human process photography

**Use:** Process triptychs, outcome stories and detail panels.

**Observed:** Close observational views of consultations, hands holding tablets and people in motion. Natural beige and amber light dominates, punctuated by intense violet-blue technical lighting. Portrait frames fill most of each card, with captions outside; larger business proof pairs use asymmetrical image/text widths.

**Transfer:** Photograph real use, expert attention and the resulting activity. Keep backgrounds tactile, lighting directional, expressions unposed and saturation concentrated within the image.

### Scientific specimens

**Use:** Signature object-led chapter and capability miniatures.

**Observed:** Saturated red granular and violet folded spheres float in the centers of large dark translucent panels, about 180px across within a 533px by 650px card. Tiny rounded-square scientific or photographic miniatures also repeat through the feature inventory, with larger rotated miniatures around its heading.

**Transfer:** Create material studies derived from the new product's mechanism: a textured sphere, layered membrane or magnified physical detail. Include this object language somewhere on the page even without custom 3D artwork.

**Build:** For a minimum version, clip a detailed material photograph to a 180px circle, overlay radial shading with a bright upper-right highlight and dark lower-left edge, and place it without a cast shadow in the center of a panel filled with rgba(255,255,255,0.02). Use red or violet only inside the specimen. For the inventory halo, reuse thumbnail images in rounded 110px squares rotated in alternating directions around the outer heading margins, fading the farthest ones to white.

### Outdoor cinematic close

**Use:** Signature large promise near the end of a landing page.

**Observed:** Full-width footage shows open-air movement, underwater swimming, rocky landscapes and sunlit human closeness. The frame is richly photographic, not a flat dark panel; white centered copy remains the visual anchor as the scene changes.

**Transfer:** Show the life enabled by the product, not another technical diagram. A full-bleed still of genuine human activity with a subtle dark scrim maintains the intended effect.

### Radiant physical card

**Only for:** plan presentations

**Use:** Entry and premium tier introductions and purchase summaries.

**Observed:** A hand raises a thin card with dense radiating fine lines and a central emblem. The pale card glows cyan against almost white; its dark sibling glows purple-blue against black. Full-size hand imagery fills the right half of an 800px-tall presentation, while smaller cards float above plan names.

**Transfer:** Use the new product's own access object, package or simple abstract token. Keep the fine engraved-ray effect and physically plausible light; a clean vector card with rays is the minimum acceptable substitute.

**Build:** Draw a rounded rectangular SVG card, then fan many hairline paths from an off-center focal point to its perimeter; clip paths to the card and add the product's simple central symbol. Behind the entry card put a 393px circle with conic-gradient(#95faf9 0deg,#3dd2ff 360deg) and blur(100px). Behind the premium equivalent use a 365px circle with conic-gradient(#c75eff 0deg,#130fff 360deg) and the same blur. Rotate the card slightly in perspective and mask it behind photographed fingers when available.

### Architectural gallery

**Only for:** place and experience pages

**Use:** Let the place itself carry the story.

**Observed:** Large 1320px by 773px landscape photographs alternate with pairs of tall 655px-wide images separated by 10px. Wood fins, windows, greenery and intimate furnishing details are shown with restrained warm grading and rounded edges.

**Transfer:** Alternate wide establishing views with tactile details; prioritize actual material quality rather than a decorative collage.

### Icons

**Observed:** Small monochrome glyphs and filled SVG marks dominate; common utility sizes are 20px and 24px, with 10px checks and plus/minus strokes for compact controls. Tiny blue checks appear in plan lists. Photographic thumbnails do much of the explanatory work normally assigned to icons.

**Transfer:** Use minimal single-color utility symbols; choose small photographic or material thumbnails for substantive categories rather than a uniform colorful icon set.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** A 900px full-width environmental photograph sits on Cinema black. A fixed 64px navigation overlays its top; the glowing architectural subject occupies the upper and middle center, with dark floor and edges left for copy. Cinema scrim protects the low-left text. The 68px Display headline spans about two fifths of the width on one line, with a roughly 618px-wide support sentence below and a Light button beneath. Three compact proof captions align at the lower right with hairline vertical dividers. In the first 900px the navigation, entire subject, headline, two-line support, action and proof strip are visible; the explanatory section begins below the fold.

**Transfer:** Create an environmental portrait of the new product's world with a strong illuminated focal point and dark negative space for the promise. If film or bespoke photography is unavailable, use a carefully lit real still, never an empty black field. Process and business pages retain the full-screen photo with low-left text; plan and place pages use a light, centered 68px title and dark action above large tangible artwork or a wide establishing photograph.

**Avoid:** Do not center a giant abstract headline above a small floating screenshot, and do not let supporting text compete with the illuminated subject.

**Text style:** `display` — Aeonik 400 · 68px/0.95 · tracking -0.02em

### Editorial chapter introduction

**Observed:** Eyebrow above Heading with 15px separation, support text 20px below, optional small action 20px after that. The heading fits an 800px measure; the content grid starts after a 50px pause. Default section padding is 150px vertically and 60px horizontally on Editorial canvas.

**Transfer:** Name the chapter in a tiny label and state one meaningful benefit in the heading; use the same hierarchy reversed inside Dark chapter.

**Text style:** `heading` — Aeonik 400 · 52px/1 · tracking -0.01em

### Photographic process triptych

**Observed:** Editorial chapter introduction above three Process cards separated by 10px. A white chapter can alternate with a #18181a middle chapter; portraits and compact translucent annotations carry the details.

**Transfer:** Break a complicated service into tangible moments, keeping captions short and images large.

### Isolated quotation

**Observed:** A single centered 56px serif quotation takes a broad white field. A tiny portrait and restrained name/role sit below, followed by miniature pagination dots with one elongated dark active mark.

**Transfer:** Use one emotionally specific, attributable statement to interrupt technical detail; retain the upright serif contrast.

**Text style:** `quote` — Instrument Serif 400 · 56px/1.1

### Open quantified proof

**Observed:** Three Stat panels make a nearly square row, with giant numbers at the top and explanations at the bottom. A Dark button sits centered 80px below; a small publication-mark strip can follow after generous white space.

**Transfer:** Make numbers feel like editorial headlines rather than dashboard KPI widgets.

### Specimen carousel

**Observed:** Scientific atmosphere supports a centered introduction and large translucent cards. Two cards and the edge of a third are visible; each contains a centered Scientific specimen, a tiny information mark and a bottom label/description. A small circular arrow overlaps the visible edge.

**Transfer:** Use a horizontally overflowing set of major mechanisms, not a tightly compressed four-card grid.

### Capability inventory

**Observed:** A centered two-line Heading is surrounded by rotated rounded miniatures, then a three-column 10px-gap grid of Capability tiles. The bottom rows fade into white above a reveal action.

**Transfer:** Show breadth in compact meaningful rows while using the floating thumbnail halo to prevent the list from feeling administrative.

### Experience immersion

**Observed:** Full-width warm arrival imagery transitions into Dark chapter; a centered Heading and support introduce two tall interior photographs with low caption overlays.

**Transfer:** Give the product's real-world environment a distinct immersive moment, retaining the architectural or material emphasis.

### Contrasting comparison

**Observed:** An Editorial chapter introduction precedes two Plan cards. Pale and charcoal surfaces carry equivalent centered headers and opposite button fills; detailed check lists stay left aligned.

**Transfer:** Use matched structure so customers can compare substance, not decorations.

### Proof wall and questions

**Observed:** Three unequal-height columns of Testimonial cards follow a centered Heading. A separate white chapter narrows into an 800px FAQ column beneath a heading, gray support sentence and Information link.

**Transfer:** Move from attributable reassurance to practical answers without adding a heavy colored support panel.

### Cinematic closing and directory

**Observed:** An 810px full-bleed Outdoor cinematic close carries a centered Display headline, 18px support sentence and Light button. The business variant is 900px tall with audience-specific copy. Directory footer immediately returns to white, keeping the small identity on the left, four link columns on the right and legal links in a low strip.

**Transfer:** Close on the human outcome, not another feature list. Preserve the cinematic promise and the understated directory as separate visual beats.

**Text style:** `display` — Aeonik 400 · 68px/0.95 · tracking -0.02em

### Sticky plan explanation

**Only for:** plan detail pages

**Observed:** A large tier introduction pairs left text with right hand-held Radiant physical card. Below, a persistent purchase summary occupies the left column while the right stacks an overview, recommended audience, inclusion rows, thumbnail timeline and attributed testimonials. The second tier becomes an extended dark world; final purchase comparison returns to white.

**Transfer:** Keep a purchase anchor visible through a long explanation. Use dated milestones and small thumbnails for a service journey rather than a generic feature table.

### Business proof pair

**Only for:** business audience pages

**Observed:** Large human photographs alternate left and right beside 570px-wide text panels with 40px padding and 16px corners. One is charcoal, another Mineral proof; compact quantified rows sit near the base. A later full-bleed lifestyle image holds a left heading/action and three numbered right-hand explanations.

**Transfer:** Connect organizational outcomes to actual people; retain the alternating image/panel balance.

### Place editorial gallery

**Only for:** place and experience pages

**Observed:** A centered light opening uses a two-line 68px title, with the secondary line gray, then a small Dark button and an 80px pause before the wide photograph. A white raised information card accompanies a 32px statement and two small text columns. Architectural gallery follows; later 570px-wide portraits pair with short body copy, then a dark cross-location feature.

**Transfer:** Let factual access information be compact while material photography does the selling.

## Page flow

**Storyline:** Outcome promise → tangible experience → depth and proof → suitable offer → reassurance → human-outcome closing → useful directory.

### Broad premium service or product introduction

1. **Promise** — Immersive night environment with low-left promise, action and compact proof.
2. **Demonstration** — Photographic triptych followed by a serif human testimonial.
3. **Quantified proof** — Large open stat row and publication marks.
4. **Capability depth** — Dark specimen chapter, light capability inventory and immersive environment story.
5. **Offer and reassurance** — Contrasting plans, institutional logo wall, social testimonials and narrow FAQ.
6. **Closing call** — Centered promise over outdoor film, then white directory.

**Transfer:** Alternate editorial clarity with sensory depth; adapt the number of capability chapters to the new product.

### Explain a complex customer experience

1. **Promise** — Human arrival photograph and concise low-left introduction.
2. **Process explanation** — Three major chapters with portrait triptychs; the middle chapter inverts to charcoal.
3. **Reassurance** — Attributed social proof followed by practical FAQ.
4. **Closing call** — Shared cinematic outcome promise and white directory.

**Transfer:** Show what the customer does, learns and receives over time rather than only naming features.

### Connect a premium offer to organizational needs

1. **Audience promise** — Full-screen human collaboration image and partnership action.
2. **Problem proof** — Tall illustrated cards with 72px bottom-anchored statistics.
3. **Outcome demonstration** — Alternating large photographs and charcoal/mineral proof panels.
4. **Offer and implementation** — Two-tier comparison and full-bleed partnership chapter with three numbered explanations.
5. **Objection handling** — Audience-specific FAQ.
6. **Closing call** — 900px human film, tailored partnership action, white directory.

**Transfer:** Translate capabilities into organizational relevance while preserving a human visual focus.

### Make a physical destination desirable and accessible

1. **Orientation** — Centered two-tone location title, action and large exterior.
2. **Practical reassurance** — Compact address card beside an attributed editorial statement.
3. **Experience demonstration** — Wide and paired architectural views, then image/text details.
4. **Related offer** — Dark split feature for another destination.
5. **Closing call** — Shared cinematic promise followed by white directory; no FAQ wall in this variant.

**Transfer:** Use real materials and useful access details to establish confidence in a place.

### Explain tier differences and support a considered purchase

1. **Offer orientation** — Centered title and two physical-card tier previews.
2. **Capability chapters** — Pale entry-tier world with a hand-held card intro, sticky purchase summary and stacked details.
3. **Expanded offer** — Dark premium world repeats the overview, inclusion rows, timeline and proof.
4. **Purchase decision** — Return to white for matched plan cards with prices, deposit rows and a small advisory callout.
5. **Objection handling** — Narrow FAQ.
6. **Closing call** — Shared cinematic outcome promise and white directory.

**Transfer:** Repeat the same information architecture per tier so deeper detail does not obscure comparison.

## Writing

Assured, clinically literate and hospitable. Strong benefit statements are balanced by concrete descriptions of the experience and carefully qualified explanations.

**Do not copy:** Do not reuse the Biograph name, trademarks, emblem, proprietary artwork, member identities, testimonial quotations, clinical claims, pricing or numerical outcomes. Examples illustrate tone and structure only; supply substantiated content for the new product.

- **Addressing the reader:** Speak directly to you and your goals; use we for the expert team and the product name sparingly. Describe the service as a continuing relationship rather than a transaction.
- **Rhythm:** Short sentence-case headlines, often 4–10 words, followed by one or two measured explanatory sentences. Occasional fragments such as 'Private suites. No waiting rooms.' add clarity without hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A direct action linked to a desirable long-term outcome. | 4–9 words | “Act now, live longer” |
| Section heading | State a practical benefit or make a complex process intelligible. | 4–12 words | “The most comprehensive health assessment”<br>“Your results are analyzed and explained” |
| Supporting line | Explain what is delivered and why it matters to the reader. | 15–35 words | “A proactive approach to long-term health, designed around you.” |
| Primary action | Plain verb and clear destination; audience-specific actions can be longer. | 2–6 words | “Learn more”<br>“Talk to our partnerships team” |
| Reassurance | Name a likely practical concern in the reader's words. | 7–18 words | “If my results show something concerning, what happens next?” |

**Words and phrasing to use:** personalized; expert-led; comprehensive; clear insights; designed around you; over time; a seamless experience; proactive

**Avoid:** miracle; life hack; disruptive; crush your goals; guaranteed results; exclusive luxury; revolutionary breakthrough

**Rules:**

- Pair an ambitious promise with a specific explanation of the mechanism.
- Use concrete experience details to convey premium quality instead of repeatedly calling it premium.
- Qualify interventions and eligibility where relevant; avoid implying every customer receives the same result.
- Keep labels short and functional; reserve emotional language for the opening, testimonial and closing.

## Do's and Don'ts

### Do

- Use 68px/0.95 regular display type for the main promise and 52px/1 for chapter headings.
- Keep the 10px uppercase eyebrow visibly delicate with 3px tracking.
- Maintain 60px desktop side insets and 10px gutters in repeated grids.
- Give primary chapters 150px top and bottom breathing room.
- Reverse the same 41px button between light and dark settings rather than inventing a second shape.
- Pair giant 92px metrics with small bottom-anchored explanations.
- Give imagery enough scale to reveal wood, skin, glass and other material textures.
- End with human-outcome media and then the 621px airy white directory.

### Don't

- Do not turn all headings into bold type; the regular circular forms are essential.
- Do not make the default page a continuous dark technology theme; white editorial chapters carry most explanation.
- Do not use cyan or violet as broad button and navigation fills; those hues belong primarily to scoped physical-card artwork.
- Do not round primary actions into pills; keep their 8px corner treatment.
- Do not give every pale card a drop shadow; use tonal separation and faint edges.
- Do not replace substantive miniature imagery with a field of large colorful line icons.
- Do not compress the 439px stat panel into a small horizontal KPI badge.
- Do not spread glass effects over whole sections; keep them inside photographic detail overlays.

## Motion and responsive

### Motion

**Observed:**

- Video media appears in specimen and closing sections; testimonial pagination and carousel controls indicate changing content.
- The information link declares a blue 1px underline with a 5px offset on hover; no action transition timing is established.

**Transfer:**

- Keep the centered closing promise stationary and readable while the human footage changes behind it.
- Provide a strong still composition for cinematic and specimen media when motion is unavailable.

**Unknown:**

- Playback speed, loop timing, carousel timing, scroll-trigger behavior and easing are not established.

### Responsive

**Observed:**

- Width breakpoints are declared around 390px, 810px, 1200px and 1400px; the business variant also declares 1800px.

**Transfer:**

- On narrow layouts, preserve the illuminated subject and low-copy contrast before reducing cinematic image height.
- Stack portrait process cards and comparison tiers; keep captions attached to their images and retain the light/dark tier distinction.
- Release the persistent purchase summary into normal reading order before its detail panels when two columns cannot remain legible.

**Unknown:**

- Exact mobile type sizes, navigation collapse behavior and column-switch rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
