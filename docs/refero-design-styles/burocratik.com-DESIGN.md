# Burocratik — swagger in the margins

## Overview

A stark editorial framework gives way to exuberant, cinematic demonstrations of craft. Black and white grotesk typography, unusually tight headlines and lopsided columns make the surrounding page feel almost undesigned, while saturated imagery supplies the spectacle. It suits visually ambitious products and creative services with enough substance for a long, image-led story; small, dense annotations coexist with enormous gestures and open white space.

### Essentials

- Spectacle precedes explanation: a full-width moving product scene occupies roughly 917px of height before the white editorial introduction; a fixed 575px × 46px navigation capsule floats above it.
- Headlines behave like indented paragraphs, not banners: regular grotesk at 75.3px/1.05 with -0.07em tracking; the first line begins about one quarter of the page in, while following lines return to the left margin.
- The interface stays monochrome while the work supplies the color: white canvas and black type across the editorial sections, with saturated color confined to rectangular photography, films and rendered product scenes rather than colored navigation or section fills.
- Actions are typography, not sales furniture: contact links use 17.6px/1.2 regular type without a filled button; the navigation's white current-page chip is only 28px tall with 12px corners inside a 20px-radius dark bar.
- Proof becomes typographic sculpture: include a giant 284.2px/0.8 numeral treatment with -0.05em tracking, grounded by a small descriptive label and a thin horizontal rule. Use a meaningful product quantity, not an ornamental invented statistic.
- Numbered editorial rows preserve a conspicuous empty left field: 57.6px numbers sit around the two-thirds division, with 17.6px explanations in the last sixth and full-width hairlines. Carry this device into product principles, benefits or technical distinctions.
- Media has a contact-sheet rhythm: mix full-width, 694px half-width and 339px quarter-width rectangles across 16.8px gutters; captions sit 6px below, outside the image. When film or 3D is unavailable, use sharply art-directed stills and enlarged interface details at the same scale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, border | Primary text, strong rules and backing for cinematic media. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal capsule | `#262626` | `--color-nav-dark` | surface | Visible dark navigation on white, made with an 85% black overlay over a translucent white backing. Over media the backing remains translucent. |
| Receding annotation | `#999999` | `--color-muted` | text | Secondary labels and descriptive lists; the visible result of black text at 0.4 opacity on white. |
| Pale rule | `#cccccc` | `--color-rule` | border | Quiet separators, including beneath testimonials; black at 0.2 opacity on white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Editorial page, current-page chip and reversed text. |

## Typography

- **Commercial Gräphik Web** — All editorial text, navigation, captions, headlines and numerals. Matter-of-fact contemporary grotesk, regular throughout; tight spacing supplies force instead of bold weight. If unavailable, use **Inter**. Use 400; retain tight tracking and tune line breaks to the same column spans. Font stack: "Commercial Gräphik Web", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| proof-number | Commercial Gräphik Web | 400 | 284.2px | 0.8 | -0.05em | fixed | Monumental quantitative proof, with restrained surrounding annotation. |
| display | Commercial Gräphik Web | 400 | 75.3px | 1.05 | -0.07em | size clamp(40px, 26.9px + 3.36vw, 84px) | Editorial introduction and major chapter statements; first-line indent is a composition rule, not extra letter spacing. |
| statement | Commercial Gräphik Web | 400 | 57.6px | 1.1 | -0.07em | size clamp(32px, 22.5px + 2.44vw, 64px) | Section-length assertions, numbered rows and descriptive introductions. |
| heading | Commercial Gräphik Web | 400 | 37.7px | 1.1 | -0.05em | size clamp(28px, 24.4px + 0.92vw, 40px) | Compact section headings and large testimonial prose. |
| closing-line | Commercial Gräphik Web | 400 | 28.8px | 1.1 | -0.05em | size clamp(24px, 22.2px + 0.46vw, 30px) | Two-line closing invitation and prominent archive titles. |
| label-medium | Commercial Gräphik Web | 400 | 23.3px | 1.1 | -0.05em | size clamp(20px, 18.8px + 0.31vw, 24px) | Project names, editorial lists and larger text actions. |
| body | Commercial Gräphik Web | 400 | 17.6px | 1.2 | -0.04em | size clamp(16px, 15.4px + 0.15vw, 18px) | Body prose, small section labels, navigation and captions. Labels remain sentence case, not an uppercase eyebrow system. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| anniversary campaigns | milestone-display | Commercial Gräphik Web | 400 | 270.3px | 0.8 | -0.05em | fixed | Stacked number and time-unit sculpture beside a timeline invitation; the short intervening word uses line height 1. |
| location showcases | place-display | Commercial Gräphik Web | 400 | 146.1px | 0.9 | -0.07em | size clamp(90px, 69.2px + 5.34vw, 160px) | Oversized place name above architectural photography. |
| collection and archive openings | archive-display | Commercial Gräphik Web | 400 | 123.3px | 1.1 | -0.03em | size clamp(56px, 31px + 6.41vw, 140px) | Centered, short manifesto-like heading over a field of tiny names. |
| case studies | case-metadata | Commercial Gräphik Web | 400 | 15.4px | 1.3 | -0.04em | fixed | Compact year, industry, location, deliverable and recognition columns. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Regular weight is the default at every scale. Large prose keeps the same sober grotesk as small annotations rather than introducing a display family.
- Tracking tightens to -0.07em for the main statement tiers, then relaxes to -0.05em for section headings and -0.04em for body text. Keep these recipes intact; bold text is not the source of hierarchy.
- The body recipe also serves actual section headings such as capability labels; hierarchy often comes from position and column span rather than font size.
- Use paragraph-like line lengths and first-line indentation for large statements. A 75.3px headline can run across several full lines instead of being reduced to a centered slogan.

## Layout

**Density:** Airy at the page level, compact within lists and captions: broad empty column fields surround tightly set text and closely captioned images.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 6px | Media-to-caption separation. | fixed |
| 16.8px | Primary column gutter and many grid gaps. | fixed |
| 17.7px | Outer desktop content inset. | fixed |
| 28.1px | Vertical margin on each side of numbered row content. | clamp(12px, 6px + 1.53vw, 32px) |
| 32px | Gallery row gap and separation between image groups. | fixed |
| 64px | Breathing space after major proof and gallery blocks. | fixed |
| 96px | Separation around large testimonial and location sections. | fixed |
| 131.3px | Pause before the closing contact area. | clamp(96px, 82.9px + 3.36vw, 140px) |
| 144px | Bottom breathing room in the contact footer. | fixed |

### Containers and grids

- **editorial-container**: max width 1405px · side padding 17.7px. Nearly edge-to-edge editorial content at a 1440px viewport; full-bleed media ignores this inset.
- **editorial-grid**: 24 columns · gap 16.8px. Underlying alignment system. Headline first lines and footer content start near the first quarter; annotations often occupy the far-right four columns.
- **media-grid**: 4 columns · gap 16.8px. Four 339px tiles, two 694px tiles or one 1405px tile. Mix square and landscape media without forcing equal-height cards.
- **case-study-split** (only for case studies): 24 columns · gap 16.8px. An 812px media column aligns to either edge while a narrow text column sits opposite, separated by deliberately unused columns.

## Corner radius

| Element | Radius |
| --- | --- |
| navigation capsule | 20px |
| current page chip | 12px |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Continuous background behind all ordinary page content.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** No raised card system; image edges, type alignment and thin rules structure the page.

**Transfer:** Keep the framework neutral even when the product's art direction is colorful.

#### Cinema backing · level 0

**Use:** Behind full-bleed films and immersive opening media.

**CSS:** `background: #000000`

**Observed:** The image itself supplies color and depth; the surrounding interface does not imitate its palette.

**Transfer:** Use a fully resolved still as the fallback to motion.

#### Navigation glass · level 2

**Use:** Floating persistent navigation.

**CSS:** `background-color: rgba(255, 255, 255, 0.4); background-image: linear-gradient(0deg, rgba(0, 0, 0, 0.85) 0px, rgba(0, 0, 0, 0.85) 100%); border-radius: 20px; backdrop-filter: blur(18px)`

**Observed:** A compact dark island above both bright and dark imagery, not a full-width translucent header.

**Transfer:** Keep glass limited to this navigational layer.

## Components

### Floating navigation

**Use:** Persistent orientation, contextual aside and menu access.

**CSS:** `position: fixed; width: 575px; height: 46px; bottom: 30px; border-radius: 20px; padding: 0px 16px; display: flex; align-items: center; justify-content: space-between; gap: 14px; z-index: 9; color: #ffffff`

**Text style:** `body` — Commercial Gräphik Web 400 · 17.6px/1.2 · tracking -0.04em

**Observed:** Centered horizontally with Navigation glass behind it; a small symbol and changing conversational aside sit left, Current page chip and a thin plus control sit right.

**Transfer:** Use a compact original identity symbol and short contextual sentence. Preserve the capsule across the page rather than adding a conventional top navigation.

### Current page chip

**Use:** Orient the reader inside Floating navigation.

**CSS:** `background: #ffffff; color: #000000; height: 28px; border-radius: 12px; padding: 4px 10px 0px`

**Text style:** `body` — Commercial Gräphik Web 400 · 17.6px/1.2 · tracking -0.04em

**Observed:** A small white rounded rectangle, not a prominent conversion button. Its text has a clipped duplicate layer for transitions.

### Plain text action

**Use:** Contact, social and supporting navigation actions.

**CSS:** `color: #000000; background: transparent; transition: opacity 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94)`

**Text style:** `body` — Commercial Gräphik Web 400 · 17.6px/1.2 · tracking -0.04em

**Observed:** No enclosing shape or arrow badge; actions sit directly in the text grid. Larger utility actions use label-medium.

**States:** Declared: hover opacity 0.4 and outline 0px; active opacity 0.3 and outline 0px. Focus-visible treatment is unknown.

**Transfer:** Use direct conversational verbs, not a cluster of filled conversion buttons.

### Media caption

**Use:** Label imagery without overlaying its artwork.

**CSS:** `display: flex; justify-content: space-between; align-items: baseline; column-gap: 16.8px; margin-top: 6px`

**Text style:** `label-medium` — Commercial Gräphik Web 400 · 23.3px/1.1 · tracking -0.05em

**Observed:** Name left; short deliverable right in body type; a more subdued category can occupy the far edge of wider cards. The name can swap to a short descriptive line.

**Transfer:** Use product name, demonstration purpose and category as separate caption roles.

### Numbered editorial row

**Use:** Explain principles, benefits or distinctions.

**CSS:** `display: flex; flex-wrap: wrap; padding: 0px 9.3px; margin-top: 28.1px; margin-bottom: 28.1px`

**Text style:** `statement` — Commercial Gräphik Web 400 · 57.6px/1.1 · tracking -0.07em

**Observed:** Full-width fine rules bracket each row. The number begins around two thirds across; short body prose sits in the last sixth. Most of the left remains empty. Row heights vary with the copy rather than being equal cards.

**Transfer:** Use one real idea per row, not icon-and-title feature boxes.

### Testimonial slide

**Use:** Large-format customer proof.

**CSS:** `margin-top: 24px; margin-bottom: 24px; padding-right: 83.9px`

**Text style:** `heading` — Commercial Gräphik Web 400 · 37.7px/1.1 · tracking -0.05em

**Observed:** Customer mark above the quotation, attribution below, a pale baseline and small Previous/Next pagination. The active 812px-wide slide begins near the first quarter; the next slide peeks beyond the right edge.

**Transfer:** Let a substantive quotation occupy several lines; keep logos monochrome and the slide unboxed.

### Contact footer

**Use:** Close a general marketing page with a human invitation and practical contact detail.

**CSS:** `display: grid; grid-template-columns: repeat(24, minmax(0px, 1fr)); gap: 16.8px; padding: 0px 17.7px 144px; background: #ffffff; margin-top: 131.3px`

**Text style:** `body` — Commercial Gräphik Web 400 · 17.6px/1.2 · tracking -0.04em

**Observed:** Closing-line sits around the first quarter, with contacts and a vertical social list beneath. Two narrow location columns sit at the far right, with coordinates and an understated email-signup prompt. Muted labels sit over black links. There is no giant final button or contrasting footer band.

**Transfer:** Use the same asymmetry with the product's contact routes and relevant practical details; keep the final line witty and short.

### Archive row

**Only for:** collection and archive pages

**Use:** Dense, chronological index below visual selections.

**CSS:** `position: relative; padding: 12px 0px; transition: opacity 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94)`

**Text style:** `label-medium` — Commercial Gräphik Web 400 · 23.3px/1.1 · tracking -0.05em

**Observed:** Year sits in a separate left column; each approximately 56px row stretches across the remaining 1049px with title, category and location on aligned baselines, divided by hairlines. Row titles use closing-line while metadata uses label-medium.

**States:** Declared: hover opacity 0.4 and outline 0px; active opacity 0.3 and outline 0px. Focus-visible treatment is unknown.

**Transfer:** Adapt the fields to releases, projects or products, retaining the unboxed index structure.

## Imagery and graphics

### Cinematic product close-up

**Use:** The opening's dominant visual and larger demonstration interludes.

**Observed:** An aggressively enlarged device/interface detail fills the viewport, with edges cut by the frame. Teal light, dark glass, a sculptural circular form and a slim device edge make the opening feel like a moving showreel, not a static app screenshot. Other scenes range from electric blue presentation spaces to softly lit material worlds.

**Transfer:** Create a close-up of the new product in use or a geometric interpretation of its core mechanism. The minimum is a high-resolution still with controlled directional light and decisive framing; it must fill the stage rather than float as a tiny mockup.

**Build:** Place a product render or interface plane edge-to-edge with object-fit: cover. Enlarge it until one edge exits the frame; give the remaining edge a dark bevel and a directional highlight. If no product asset exists, build a simple original geometric mechanism in SVG using two or three solid planes, a light-to-dark gradient clipped to each plane, and a dark backing. Keep color inside the rendered scene, with the capsule navigation on top.

### Mixed-scale demonstration contact sheet

**Use:** Recurring proof imagery throughout marketing and collection pages.

**Observed:** Rectangular videos, screen compositions, outdoor advertising and brand objects mix at full, half and quarter widths. A landscape image can sit beside a square image, leaving intentional white space underneath the shorter tile. Bright red, violet, orange and yellow belong to the work, while captions stay black and gray.

**Transfer:** Combine close interface details, a real-world use scene and a product still. Do not recolor all media to one universal accent or wrap it in padded cards.

### Monumental type sculpture

**Use:** A required oversized proof gesture within the editorial story.

**Observed:** Large black numerals rise to roughly 284px, with a compact label and a rule. A milestone variation stacks a giant age and time unit beside a dense list and an underlined timeline invitation, punctuated by a small expressive graphic.

**Transfer:** Use a verified quantity for the proof numeral. The campaign variation can use a short product-related word or milestone in place of a historic age.

**Build:** Use live regular grotesk type with -0.05em tracking and 0.8 line height, clipped within a roughly 300px-tall band for numerals. Place the small label above or beside it; extend a 1px rule across the available width. For the milestone variant, stack two giant text lines in one half and a compact chronological list in the other. Use an original simple outlined expressive glyph if needed.

### Identity and product artifact studies

**Only for:** case studies

**Use:** Long image-led chapters explaining the product and its system.

**Observed:** Fintech work uses translucent repeated blue-violet planes, luminous edges, dark devices and physical stationery. Material-led work uses mossy sculptural forms, foliage shadows on warm off-white, lime and deep green print artifacts, factory close-ups and seasonal landscapes. These treatments belong to the showcased identity, not the editorial canvas.

**Transfer:** Derive a coherent material world from the new product's mechanism and actual materials. Alternate full-bleed introductions with an 812px visual column and a small opposite commentary column.

### Human and architectural photography

**Only for:** culture and location pages

**Use:** Team introductions and visits to real spaces.

**Observed:** Black-and-white portraits use dark studio backdrops, informal poses, white names near the top and small roles at the bottom. Architecture is bright and natural, often with a person blurred by movement, framed full bleed and then as paired or offset smaller photographs.

**Transfer:** Use candid but deliberately lit portraits and real work environments rather than generic smiling-team stock imagery.

### Icons

**Observed:** Small monochrome symbols are sparse: a 24px white identity glyph in navigation, a thin plus for menu access, plain directional arrows and occasional expressive inline emoji-like marks in large prose.

**Transfer:** Use an original monochrome identity glyph and simple plus/arrow geometry. Reserve expressive pictograms for a single punctuation beat rather than adding a feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Cinematic opening

**Observed:** Back to front: black Cinema backing, a full-width 1440px × 917px moving product close-up, then Floating navigation centered near the bottom with 30px clearance. The media fills the first 900px: the product/device edge is enlarged beyond the frame and its rendered content becomes the main object. No separate headline, support paragraph or conversion button is visible in that first screen. The white introduction begins below the fold with 35.3px top space: display type spans most of the width, first line indented to the quarter division and subsequent lines returning left. Its support is the assertion itself rather than a small centered subtitle.

**Transfer:** Open with a visually complete product film or art-directed still, even if the new product is software or a service. Make an original mechanism or interface detail the object when no physical product exists. Keep the large textual promise immediately after the visual. Case studies instead open on white with a 57.6px indented statement, narrow right metadata and Back/Open Website utilities; collection pages use a centered archive-display over tiny names; culture pages overlay display prose on a full-bleed monochrome group portrait.

**Avoid:** Do not turn the default first screen into a centered headline, two pill buttons and a small floating dashboard. Do not overlay a fabricated marketing headline on top of the opening film.

**Text style:** `display` — Commercial Gräphik Web 400 · 75.3px/1.05 · tracking -0.07em

### Indented editorial statement

**Observed:** Small body-sized section label occupies the left start of the first line; statement text begins near the quarter division and wraps back across the container. The text spans about 990px in capability introductions; later chapter statements can span nearly the entire content width.

**Transfer:** Use a substantial one- or two-sentence assertion with an intentional first-line indent, followed by the relevant demonstration rather than a decorative card row.

**Text style:** `statement` — Commercial Gräphik Web 400 · 57.6px/1.1 · tracking -0.07em

### Proof and right-weighted explanation

**Observed:** Monumental type sculpture establishes a quantity. A heading in the left sixth is paired with a narrow body column starting around two thirds across; small monochrome award-like proof objects sit under the prose. Numbered editorial row continues the right-weighted alignment with full-width rules.

**Transfer:** Pair the giant proof device with concise substantiation, then explain distinct advantages through numbered rows. Reuse the empty space as part of the composition, not as space to fill with extra marketing copy.

**Text style:** `proof-number` — Commercial Gräphik Web 400 · 284.2px/0.8 · tracking -0.05em

### Variable media gallery

**Observed:** Mixed-scale demonstration contact sheet uses the media-grid, 32px row separation and Media caption below each image. Rows alternate two halves, a full-width hero, two quarters plus a half, and four quarters. Square photographs are allowed to create uneven lower edges.

**Transfer:** Select widths by the strength of each asset and its narrative role rather than enforcing a uniform gallery. Keep the labels outside the art.

### Testimonials with a visible next thought

**Observed:** A compact heading and narrow introductory paragraph precede Testimonial slide. A large gap of about 200px separates introduction from quotation content. The slide track starts at the quarter-page alignment and extends beyond the right edge; a customer mark, multiline quotation, attribution and pale rule read in sequence.

**Transfer:** Use the same open, clipped horizontal composition for customer outcomes or independent reviews, with small pagination below.

**Text style:** `heading` — Commercial Gräphik Web 400 · 37.7px/1.1 · tracking -0.05em

### Understated closing invitation

**Observed:** Contact footer stays on Editorial canvas after a 131.3px pause. The two-line 28.8px invitation sits at the quarter alignment; contacts begin well below it, alongside narrow right-hand practical columns. The total block is about 633px tall with 144px bottom space. A playful signup prompt appears in the right column without a large boxed form.

**Transfer:** Close with a human sentence and real contact paths. Keep conversion quiet in scale but unambiguous in wording.

**Text style:** `closing-line` — Commercial Gräphik Web 400 · 28.8px/1.1 · tracking -0.05em

### Case-study chapters and closing endorsement

**Only for:** case studies

**Observed:** The opening pairs an indented statement with case-metadata, then a 1405px-wide lead image. A ruled summary places a 37.7px challenge statement left and small prose columns right. Large display chapter lines introduce full-bleed media, followed by alternating 812px demonstration columns and narrow commentary. The page ends with a 501px endorsement block, not the general contact footer: small attribution left, 812px indented heading-size quotation right, top hairline and 115.2px bottom space.

**Transfer:** Show the product's problem, design rationale, mechanism and lived use as distinct image-led chapters. Finish with an attributable outcome in the same restrained split layout.

**Text style:** `heading` — Commercial Gräphik Web 400 · 37.7px/1.1 · tracking -0.05em

### Stacked capability sheets

**Only for:** extended capability and culture pages

**Observed:** White sticky sheets each occupy 900px at desktop. A giant numeral anchors the left, a small category sits at the quarter line, and a 57.6px assertion, small demonstration image and three narrow descriptive lists occupy the right half. The sheets overlap while scrolling.

**Transfer:** Use for deep product capability chapters when there is enough content to justify a whole screen per topic, not for ordinary short feature lists.

**Text style:** `statement` — Commercial Gräphik Web 400 · 57.6px/1.1 · tracking -0.07em

### Place and people showcase

**Only for:** culture and location pages

**Observed:** An oversized 146.1px place name begins at the quarter division above a full-width architectural image. Small address details and contact links sit opposite a vertical sequence of half-width images. Portraits earlier in the story form a horizontal monochrome strip with names on the image.

**Transfer:** Use this editorial treatment for real spaces or people; retain natural light and irregularly occupied columns.

**Text style:** `place-display` — Commercial Gräphik Web 400 · 146.1px/0.9 · tracking -0.07em

## Page flow

**Storyline:** visual intrigue → plainspoken positioning → material proof → deeper explanation → independent endorsement → human invitation; adapt the order to the story rather than treating it as a checklist.

### An expressive general marketing landing page

1. **Visual intrigue** — Viewport-filling product film with persistent capsule navigation.
2. **Positioning** — Large indented editorial assertion, then a milestone type sculpture and dense supporting list.
3. **Demonstrated proof** — Mixed-scale gallery, huge proof count, narrow substantiation and numbered editorial rows.
4. **Capabilities** — Further vivid demonstrations followed by a large statement and compact descriptive lists.
5. **Independent endorsement** — Open testimonial carousel with the next quotation partly visible.
6. **Closing invitation** — White contact footer with a two-line quip, contact stack, locations and understated signup.

**Transfer:** Use the default cinematic opening and alternate visual abundance with typographic restraint. Let the product determine which proof and capability blocks matter.

### A technical product transformation case study

1. **Promise and context** — White indented statement, compact factual metadata, lead 3D image and ruled challenge summary.
2. **Product demonstration** — Immersive full-width film followed by a small commentary column opposite large interface and device scenes.
3. **System rationale** — Large chapter statement, physical applications and coherent geometric visual studies.
4. **Mechanism** — Another indented chapter statement introduces product-level 3D and interface demonstrations.
5. **Independent endorsement** — Ruled split closing quotation and attribution without the general contact footer.

**Transfer:** Use explanatory chapters to connect complex technical function to a visual mechanism, keeping the editorial shell monochrome.

### A material-led product and identity case study

1. **Promise and context** — Independently readable statement with metadata, lead film and a ruled problem-and-approach summary.
2. **Product demonstration** — Large film and extended interface demonstrations with anchored commentary.
3. **System rationale** — Chapter statement introduces identity, printed artifacts, materials and applications.
4. **Process proof** — Large chapter line and full-width collage lead into factory and fabrication photography.
5. **Lived outcome** — Seasonal film and behind-the-scenes imagery show the product inhabiting real places.
6. **Independent endorsement** — Final ruled customer quotation and attribution.

**Transfer:** Translate this longer rhythm to physical products with real process imagery and use contexts; do not replace everything with interface mockups.

### A curated collection with a complete searchable-feeling archive

1. **Attitude** — Short centered declaration over a dense field of tiny names, with date endpoints above.
2. **Selected proof** — Variable media gallery interspersed with a large explanatory statement and identity montage.
3. **Breadth** — Giant count, prominent text selector, small introductory prose and view controls.
4. **Index** — Year-grouped ruled rows align name, category and place.
5. **Closing invitation** — Quiet contact footer with a different playful closing line.

**Transfer:** Combine a curated visual selection with a compact exhaustive index; reserve this denser opening variant for collections.

### A human, process and place-oriented company page

1. **Human positioning** — Display prose over monochrome group photography with a fine line-art overlay.
2. **People and trust** — Statement, portrait strip, selected customer marks and giant proof count.
3. **Principles** — Small heading, far-right prose and numbered editorial rows.
4. **Capabilities** — Overlapping full-screen numbered capability sheets.
5. **Independent endorsement** — Large open testimonial carousel.
6. **Place** — Oversized place names, architectural photography and small contact annotations.
7. **Closing invitation** — The shared white contact footer with another short quip.

**Transfer:** Use only genuine people, places and processes; keep portraits and capability sheets scoped to this deeper organizational story.

## Writing

Confident craft talk with a mischievous aside. Serious explanations are specific and grounded, while navigation and closing lines sound like a human muttering something funny just offstage.

**Do not copy:** Do not reuse the studio's name or identity artwork, customer names, rankings, award totals, anniversary numbers, coordinates, quotations or product claims. All examples illustrate tone only; replace them with truthful content and original assets.

- **Addressing the reader:** Use we for the makers, you for direct invitations and third-person factual language for case-study subjects. The reader is treated as a collaborator, not a lead in a funnel.
- **Rhythm:** Long, paragraph-like display statements alternate with tiny practical labels. Explanatory prose can be substantial; closing lines and contextual asides are short, conversational and occasionally fragmentary.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Positioning statement | Plain description of what the organization does, with a confident adjective and a small expressive interruption. | One substantial sentence across several lines. | “We're a fearless 🤟 digital studio with two decades of craft, ranked Europe’s #1 digital studio by the 💫 European Design Agencies league (2021–2025).” |
| Chapter line | A short substantive assertion that ties design decisions to a real outcome. | One or two sentences. | “Floema at its core. Raw materials, great design, honest process, built to last.” |
| Principle | A memorable everyday analogy followed by a direct statement. | One compact thought. | “Design is not tequila. It can’t make everyone happy.” |
| Primary action | Direct human invitation rather than conversion jargon. | Two to three words. | “Let's talk!”<br>“Open Website” |
| Closing invitation | Two short conversational beats, sometimes ending with a down arrow. | Two brief lines. | “Say no more It's a match ↓”<br>“Keep calm and... That's it. That's the message.”<br>“Butter. Knife. You’re next? ↓” |

**Words and phrasing to use:** craft; clarity; made for; built to last; people; a dry aside; a concrete process verb

**Avoid:** revolutionary synergy; unlock limitless potential; seamless repeated without detail; generic best-in-class slogans; formal enterprise boilerplate

**Rules:**

- Make the main statement intelligible before adding a joke.
- Use humor in the margins, contextual navigation and final invitation; do not turn every technical paragraph into a punchline.
- Explain a design choice through its material, mechanism or purpose rather than merely calling it beautiful.
- Let factual proof carry authority, then undercut self-seriousness with one brief human aside.
- Sentence-case labels and contractions are natural; avoid an all-capitals marketing taxonomy.

## Do's and Don'ts

### Do

- Keep display type at weight 400 and -0.07em tracking rather than making it bold.
- Start major editorial first lines near the quarter-page alignment and let later lines return left.
- Use the 24-column grid and 16.8px gutters to align distant elements.
- Keep image captions outside media with a 6px separation.
- Include both the giant 284.2px proof numeral and right-weighted numbered rows as recognizable typographic devices.
- Keep the fixed navigation compact at 575px × 46px on desktop with its small 28px current-page chip.
- Allow a 694px landscape image beside a 694px square image to leave an uneven white field.
- End ordinary marketing pages in a white, 633px-scale contact area with 144px of bottom space.

### Don't

- Do not use a 700-weight geometric headline to simulate impact; the regular cut and tight spacing do the work.
- Do not turn 17.6px sentence-case section labels into widely tracked uppercase mono eyebrows.
- Do not apply the showcased product's violet, lime or teal to every section background or link.
- Do not give gallery tiles 20px corners, shadows and interior padding; those rounded forms belong chiefly to the floating navigation.
- Do not replace the 16.8px gutters with broad 48px card-grid gaps.
- Do not put the text-action system inside tall filled conversion pills.
- Do not fill the deliberately empty left two thirds of numbered rows with extra illustrations or badges.
- Do not append a generic dark sitemap footer after a case-study endorsement; that page type resolves with the quotation.

## Motion and responsive

### Motion

**Observed:**

- Text actions declare opacity 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94), reaching 0.4 on hover and 0.3 when active.
- Clipped duplicate text layers support label swaps; transform transitions include 0.35s cubic-bezier(0.645, 0.045, 0.355, 1) with 0.05s delay.
- The navigation stays fixed while editorial content scrolls; extended capability sheets use sticky positioning.
- Films, canvas-driven dividers and a paginated testimonial track supply motion without a broad animated button system.

**Transfer:**

- Preserve the quiet opacity feedback on text actions and a steady fixed capsule over moving media.
- Confine expressive motion to the cinematic scenes, label swaps and ruled narrative devices; provide complete still artwork for the same compositions.

**Unknown:**

- Exact video sequencing, canvas deformation, scroll trigger thresholds and complete menu-open choreography are unspecified.
- Focus-visible styling is not established.

### Responsive

**Observed:**

- Declared width breakpoints include 410px, 743px, 1023px, 1290px, 1440px, 1700px and 2000px; the collection layout also declares 300px.
- Display, statement, heading and body type use the clamp formulas attached to their recipes.
- Grid classes include full-width small-screen headline and metadata variants, and numbered rows with paired half-width number/text cells.

**Transfer:**

- On narrow layouts, preserve the media-first opening with a deliberate alternate image framing, not a shrunken desktop scene.
- Remove large empty grid offsets as columns collapse; let numbered explanations become a number/text pair while retaining the rules.
- Keep the floating capsule within the available width and shorten its aside before reducing the current-page label.

**Unknown:**

- Only desktop layouts are established; exact narrow-screen capsule dimensions, stacking order and mobile motion behavior remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
