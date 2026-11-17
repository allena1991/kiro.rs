# Dropmark — geometric play at work

## Overview

A bright, practical style that pairs friendly grotesk typography with exuberant flat geometric illustration. White space and charcoal text keep the product easy to understand, while cyan actions, warm gray proof panels and deep indigo accents add a playful studio character. It suits creative tools and collaborative products, with sparse opening compositions and more compact capability and comparison sections.

### Essentials

- A plainspoken promise gets the stage before the artwork: centered 60px/1.2 medium grotesk headings in a 720px measure, followed by 20px/1.5 support in a 500px measure.
- The first screen is half explanation, half unfolding picture: a 110px header, headline beginning around 170px, paired actions around 454px, and a full-width geometric scene entering the lower third of the 900px viewport.
- Actions are little rectangles, not capsules: 3px corners, 8px 20px 10px padding, 20px regular text; cyan primary, white inset-outline secondary, charcoal header action.
- Color lives in contained visual events: white dominates the text-led opening; saturated cyan, violet, mint and coral inhabit flat illustration, while warm #f7f7f1 bands and #1e2554 proof blocks carry the lower-page contrast.
- A geometric picture language is essential: sharply cut parallelograms, circles, stairs and media-like symbols form a playful upright construction. Use an original SVG tile sculpture with simple symbols when bespoke character illustration is unavailable.
- Proof has a graphic personality: pair a warm gray logo panel with a navy panel split between geometric art and centered facts; 40px headings, cyan 24px tabular numbers and white 14px captions replace oversized dashboard metrics.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof navy | `#1e2554` | `--color-navy` | background, surface | Dark proof tile and product-demonstration band. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action cyan | `#00affa` | `--color-cyan` | action, link, accent | Primary buttons, short story links and proof numerals. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal ink | `#404040` | `--color-ink` | text, action | Default headings, body, navigation and dark header action. |
| Muted gray | `#7f7f7f` | `--color-muted` | text | Story descriptions and integration body text. |
| Inset outline | `#dcdcd2` | `--color-inset` | border | Secondary button's 2px inset edge. |
| Logo-panel stone | `#dcdcd4` | `--color-stone` | surface | Large customer-logo proof panel. |
| Story-card edge | `#e7e7e7` | `--color-edge` | border | Visible hairline from rgba(17,17,17,0.1) over white. |
| Warm ivory | `#f7f7f1` | `--color-warm` | background, surface | Proof band, secondary-action hover and comparison entry tier. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Main canvas, story cards and reversed text; carousel controls use this at 75% opacity. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Plan turquoise | `#00cccc` | `--color-turquoise` | surface | Individual paid-tier header. |
| pricing pages | Plan purple | `#7b49ed` | `--color-purple` | surface | Collaborative paid-tier header. |
| app-download and pricing pages | Deep violet | `#2c2a6c` | `--color-violet` | surface, action | Video action and enterprise comparison header. |
| app-download pages | Device black | `#111111` | `--color-device` | surface | Physical device bezels. |
| pricing pages | Answer gray | `#40484d` | `--color-answer` | text | Long FAQ answers and support links. |

## Typography

- **DropmarkRealHead** — Display, section titles and numerals. Friendly, sturdy grotesk with open counters and a compact, rounded feel. If unavailable, use **Lato**. Use 400, 500 and 700; preserve normal tracking and the measured line lengths. Font stack: "DropmarkRealHead", "Lato", sans-serif.
- **DropmarkRealText** — Body, navigation, buttons, labels and compact proof heading. Readable humanist grotesk with open forms and an informal workmanlike tone. If unavailable, use **Lato**. Use 400, 600 and 700; do not tighten body tracking. Font stack: "DropmarkRealText", "Lato", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | DropmarkRealHead | 500 | 60px | 1.2 | normal | Centered opening promise. |
| heading | DropmarkRealHead | 500 | 40px | 1.2 | normal | Proof title and substantial section headings. |
| proof-heading | DropmarkRealText | 600 | 40px | 1.5 | normal | Centered two-line heading above customer logos. |
| stat | DropmarkRealHead | 500 | 24px | 1.2 | normal, features "lnum", "tnum" | Cyan centered proof numbers, including a spelled-out value. |
| body | DropmarkRealText | 400 | 20px | 1.5 | normal | Main prose, navigation and rectangular actions. |
| story-title | DropmarkRealText | 600 | 17px | 1.5 | normal | Short story-card titles. |
| small | DropmarkRealText | 400 | 16px | 1.5 | normal | Footer, quotations and compact capability descriptions. |
| story-body | DropmarkRealText | 400 | 15px | 1.5 | normal | Muted story-card descriptions. |
| story-link | DropmarkRealText | 600 | 15px | 1.5 | normal | Cyan story-card actions. |
| stat-caption | DropmarkRealText | 400 | 14px | 1.2 | normal | White labels directly below proof numbers. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | DropmarkRealHead | 400 | 54px | 1.5 | normal | Price numerals alongside a smaller currency mark and billing explanation. |
| feature-explanation and pricing pages | chapter-heading | DropmarkRealHead | 500 | 38px | 1.2 | normal | Left-aligned chapter or comparison introduction. |
| pricing pages | faq-heading | DropmarkRealHead | 700 | 38px | 1.2 | normal, uppercase | FAQ section title. |
| feature-explanation pages | band-heading | DropmarkRealHead | 500 | 32px | 1.2 | normal | Centered title on the dark product band. |
| app-download pages | integration-heading | DropmarkRealHead | 500 | 25px | 1.5 | normal | Unboxed integration-grid headings. |
| pricing pages | plan-label | DropmarkRealText | 600 | 20px | 1.5 | normal | Plan titles and customer-strip introduction. |
| pricing pages | faq-question | DropmarkRealText | 700 | 18px | 1.2 | normal | Questions above always-visible answers. |
| feature-explanation pages | band-body | DropmarkRealText | 400 | 17px | 1.5 | normal | Compact centered supporting prose on navy. |
| pricing pages | plan-action | DropmarkRealText | 600 | 16px | 1.5 | normal | Text action with a right arrow inside comparison header. |
| pricing pages | plan-detail | DropmarkRealText | 400 | 14px | 1.5 | normal | Billing qualifications and feature bullets. |

**Notes:**

- Keep normal tracking throughout. Character comes from the friendly letterforms and line breaks rather than compressed spacing.
- Display and standard headings use 1.2 line height; prose uses 1.5. The customer-logo heading deliberately uses the text family at 40px/1.5.
- Sentence case is the rule; the uppercase FAQ title is a scoped exception.

## Layout

**Density:** Airy at the opening and between major scenes; compact within story cards, feature summaries and the footer.

### Spacing

**Spacing system:**

- **rhythm** 10px, vertical — Major vertical intervals follow multiples of 10px; type-related margins and compact internal padding remain independent.

| Value | Use |
| --- | --- |
| 10px | Proof-row gaps and FAQ question-to-answer separation. |
| 20px | Comparison-header content inset and button side padding. |
| 30px | Header/footer vertical padding and proof content inset. |
| 40px | Story-card horizontal separation and wide proof-band side clearance. |
| 60px | Opening offset after navigation, action-row margin and warm-band vertical padding. |
| 80px | FAQ padding and spacing around the dark demonstration band. |
| 90px | Device-scene separation beneath app actions. |

### Containers and grids

- **main-container**: max width 1200px. Centered desktop navigation, text-and-image chapters and footer. At 1440px the side clearance is 120px.
- **opening-copy**: max width 720px. Centered headline measure; support prose narrows to 500px.
- **reading-column** (only for pricing pages): max width 500px. Centered but left-aligned pricing introduction and FAQ reading measure.
- **split-chapter** (only for feature-explanation pages): max width 1200px · 2 columns. A 480px text column opposite approximately 600px of illustration; reverse the sides for another chapter.
- **plan-grid** (only for pricing pages): max width 1200px · 4 columns · gap 48px. Equal 264px comparison columns with colored headers above open bullet lists.
- **integration-grid** (only for app-download pages): max width 1200px · 3 columns · gap 60px. Six unboxed descriptions in two rows; individual articles are 348px wide.
- **capability-grid** (only for feature-explanation pages): max width 1200px · 4 columns · gap 48px. Four 252px icon-led summaries beneath each feature chapter.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-plan-headers | 3px |
|  | carousel-controls | 50% |
| app-download pages | desktop-device | 30px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| secondary-action-inset | `rgb(220, 220, 210) 0px 0px 0px 2px inset` | A quiet inset outline rather than an elevated shadow. |

### Surfaces

#### White canvas · level 0

**Use:** Default page ground and footer.

**CSS:** `background-color: #ffffff; color: #404040`

**Observed:** Most text sits directly on the canvas, without enclosing cards.

**Transfer:** Keep prose-led regions flat and visually open.

#### Warm band · level 0

**Use:** A lower-page proof ground; also extended reading sections.

**CSS:** `background-color: #f7f7f1; padding: 60px 0px`

**Observed:** The proof panels sit together on this warm ground. FAQ uses 80px vertical padding.

**Transfer:** Use a subtle temperature shift to group supporting evidence.

#### Stone proof panel · level 1

**Use:** Customer or partner recognition.

**CSS:** `background-color: #dcdcd4; overflow: hidden`

**Observed:** Square-edged and flat, with a centered text heading and a horizontally clipped monochrome logo strip.

**Transfer:** Keep marks monochrome so the artwork retains the expressive color.

#### Navy proof panel · level 1

**Use:** Graphic proof and product emphasis.

**CSS:** `background-color: #1e2554; color: #ffffff; overflow: hidden`

**Observed:** Hard rectangular silhouette; geometric art occupies one side and centered type the other.

**Transfer:** Use navy for a concentrated proof event, not as the default page theme.

#### Story surface · level 1

**Use:** Horizontal editorial cards.

**CSS:** `background-color: #ffffff; border: 1px solid rgba(17,17,17,0.1); box-shadow: none`

**Observed:** Thin edge, square corners and no floating-card effect.

**Transfer:** Let a colorful image area supply the visual interest.

#### Device shell · level 1

**Only for:** app-download pages

**Use:** Desktop product demonstrations.

**CSS:** `background-color: #111111; border-radius: 30px; padding: 24px`

**Observed:** A 540px by 356px monitor shell has a pale metal stand; a landscape tablet uses an elliptical corner treatment and overlaps a narrow phone.

**Transfer:** Place real working product visuals inside restrained black hardware silhouettes.

## Components

### Navigation

**Use:** Global orientation at the top of every page.

**CSS:** `display: flex; justify-content: flex-end`

**Text style:** `body` — DropmarkRealText 400 · 20px/1.5

**Observed:** A small colorful symbol and bold wordmark sit left; plain text destinations, a login link and Header action sit right. The 1200px header has 30px vertical padding and is 110px tall.

**Transfer:** Use a compact identity and a small set of direct destinations; preserve the open center.

### Primary button

**Use:** Main conversion or download action.

**CSS:** `background-color: #00affa; color: #ffffff; border-radius: 3px; padding: 8px 20px 10px`

**Text style:** `body` — DropmarkRealText 400 · 20px/1.5

**Observed:** The action is a short, flat rectangle. It appears beside Secondary button in the opening, with about 36px visible separation; rendered height is 47px.

**States:** Declared: hover filter brightness(120%); focus-visible unknown.

**Transfer:** Keep label length close to a short spoken invitation.

### Secondary button

**Use:** Explore before committing.

**CSS:** `background-color: #ffffff; color: #00affa; border-radius: 3px; padding: 8px 20px 10px; box-shadow: rgb(220, 220, 210) 0px 0px 0px 2px inset`

**Text style:** `body` — DropmarkRealText 400 · 20px/1.5

**Observed:** Same silhouette and baseline as Primary button; the edge reads as a pale inset frame.

**States:** Declared: hover filter none, background-color #f7f7f1 and box-shadow none; focus-visible unknown.

### Header action

**Use:** Persistent signup in the navigation.

**CSS:** `background-color: #404040; color: #ffffff; border-radius: 3px; padding: 8px 20px 10px`

**Text style:** `body` — DropmarkRealText 400 · 20px/1.5

**Observed:** The dark action terminates the right-aligned navigation and is visually quieter than the cyan hero action.

**States:** Declared: hover opacity 0.6; focus-visible unknown.

### Story card

**Use:** Compact editorial or use-case carousel items.

**CSS:** `background-color: #ffffff; border: 1px solid rgba(17,17,17,0.1); height: 155px; margin-right: 40px`

**Text style:** `story-title` — DropmarkRealText 600 · 17px/1.5

**Observed:** Cards are 320px or 420px wide. A cropped flat illustration or colorful image fills the left portion, with title, muted description and cyan Story link on the right; the rail clips cards at both viewport edges.

**Transfer:** Use concrete use cases or customer stories with similarly short descriptions.

### Story link

**Use:** Short action inside a story card.

**CSS:** `color: #00affa`

**Text style:** `story-link` — DropmarkRealText 600 · 15px/1.5

**Observed:** The action sits beneath the description and is visually stronger than the muted prose.

**States:** Declared: hover filter brightness(120%); focus-visible unknown.

### Carousel control

**Use:** Move through the horizontal story rail.

**CSS:** `background-color: rgba(255,255,255,0.75); border-radius: 50%; width: 44px; height: 44px`

**Observed:** Circular controls overlay the rail near the viewport edges. A 26px charcoal filled chevron is centered inside.

**States:** Declared: hover background #ffffff; focus-visible unknown; active opacity 0.6.

### Customer proof tile

**Use:** Recognition by recognizable users or partners.

**CSS:** `background-color: #dcdcd4; overflow: hidden`

**Text style:** `proof-heading` — DropmarkRealText 600 · 40px/1.5

**Observed:** A 641px by 419px panel places a two-line centered heading above an 80px-tall monochrome logo strip. Marks extend beyond the edges.

**Transfer:** Substitute genuine partners, publications or compatible platforms.

### Graphic stat tile

**Use:** A compact, memorable proof device.

**CSS:** `background-color: #1e2554; color: #ffffff; display: grid; grid-template-columns: repeat(2, 1fr); overflow: hidden`

**Text style:** `stat` — DropmarkRealHead 500 · 24px/1.2

**Observed:** A 641px by 419px tile divides evenly into geometric art and a centered content column. Heading uses heading; four values stack with stat-caption beneath each and 10px row gaps. A word such as zero can replace a numeral.

**Transfer:** Use a few verified outcomes with one clear label each; retain the artwork half even with fewer facts.

### Footer link

**Use:** Compact destination columns and maker attribution.

**CSS:** `color: #404040`

**Text style:** `small` — DropmarkRealText 400 · 16px/1.5

**Observed:** The white footer is 204px tall with 30px vertical padding. Attribution and copyright occupy the far left; four narrow link columns group account, product, support/legal and social destinations on the right. Links have no card containers or large section labels.

**States:** Declared: hover opacity 0.6; focus-visible unknown.

### Plan header

**Only for:** pricing pages

**Use:** Top portion of a comparison column.

**CSS:** `background-color: #f7f7f1; border-radius: 3px; position: relative`

**Text style:** `plan-label` — DropmarkRealText 600 · 20px/1.5

**Observed:** A 264px by 217px colored box contains a tier title, price and billing note, then a plan-action with a right arrow near the bottom. The default free tier uses charcoal text; paid variants use turquoise, purple and deep violet with white text. Bullet lists sit below the box, on white, rather than inside it.

**Transfer:** Compare tiers through compact lists, not badges or oversized recommendation borders.

## Imagery and graphics

### Geometric tile sculpture

**Use:** Essential signature art for the opening and supporting visual accents.

**Observed:** A sprawling flat-vector construction of upright parallelogram tiles, circles, stair steps and simplified media symbols. Small diverse figures interact with the construction. Saturated mint, cyan, coral, pink, violet and indigo sit against white and pale warm angular ground planes; there is no photorealistic lighting or glossy material. The opening scene spans the viewport and continues below the fold.

**Transfer:** Create a new construction around the product's own actions. Minimum version: an original interlocking SVG tile sculpture with three simple symbols and a few circles or stair shapes; keep the scale and multicolor energy even without figures.

**Build:** Use an SVG viewBox around 1440 by 900. Lay out adjoining rectangles as upright parallelograms with a shared sloping top and bottom edge; stagger their vertical positions. Fill neighboring tiles with navy, cyan, violet, mint and coral. Add circles, semicircles, a stair path and white symbolic line shapes clipped to the tile faces. Put broad pale ivory and stone polygons behind the lower half as ground planes. Keep all fills flat, edges sharp and shadows absent.

### Graphic proof artwork

**Use:** The artwork half of Graphic stat tile and thin decorative strips on product bands.

**Observed:** A tightly cropped modular pattern combines a navy upper field, warm coral and pink arcs, cyan stair steps, purple circles and white discs. It fills half the proof tile from edge to edge; the same vocabulary becomes a narrow column at the right edge of a navy band.

**Transfer:** Reuse the geometric vocabulary as a complementary composition, not a reduced logo or a stock illustration.

**Build:** Create two adjacent SVG columns about 160px wide in a 320 by 419 viewBox. Stack flat rectangular fills; overlay one stepped polygon, two partial circles, a broad arc and one white disc. Clip at the outside bounds. Use navy and cyan from the palette with mint, coral and pink art fills; no gradients, bevels or blurred shadows.

### Interface demonstration

**Only for:** feature-explanation pages

**Use:** Visual proof inside a navy demonstration band.

**Observed:** A large desktop browser window shows a light masonry collection of fashion and lifestyle imagery, with a muted lavender browser bar and tiny window dots. The approximately 600px-wide window sits left, starts 40px below the band edge and is clipped at the bottom; centered white text and a cyan button occupy the right.

**Transfer:** Show a credible interface populated with attractive, varied content. Keep internal UI legible enough to imply usefulness without turning marketing typography into a dense UI specimen.

### Hardware scenes

**Only for:** app-download pages

**Use:** Platform-specific product presentation.

**Observed:** A narrow phone overlaps the lower-left foreground of a much larger landscape tablet; both have black bezels on white. A later monitor is paired with a centered text-and-action column. The visible phone contains light collection-list UI and colorful thumbnails.

**Transfer:** Populate hardware with genuine product views; retain the asymmetrical phone/tablet overlap and the separate monitor-and-copy composition.

### Testimonial accent

**Only for:** feature-explanation pages

**Use:** Separate chapter explanation from a supporting quotation.

**Observed:** A short pale gray wavy rule sits above a compact 16px quotation, followed by a bold person name and regular role line. The quote stays in the text column rather than in a colored card.

**Transfer:** Use a short attributed customer observation; keep the wave as a modest editorial detail.

**Build:** Draw a single thin stone-colored sinusoidal SVG path roughly 84px wide and 6px tall, with several shallow rounded waves; place it above the quotation with open vertical spacing.

### Icons

**Observed:** Capability summaries use 42px image icons: bright circular discs with simple white symbols such as grid dots, a tag, a plus, a lock or a play triangle. Carousel arrows are filled charcoal chevrons at 26px. Icons sit above the small capability prose, not beside oversized headlines.

**Transfer:** Choose simple solid symbols with one idea each; use colorful discs for capability grids and restrained charcoal for navigation controls.

## Section recipes

How recurring sections are built.

### First screen: Illustrated promise opening

**Observed:** White canvas carries Navigation in a 1200px container, 110px tall. After a 60px interval, the centered display headline spans a 720px measure and breaks into two lines at 60px/1.2. A 500px support paragraph follows after 27px; the action row sits roughly 53px below the prose, pairing Primary button with Secondary button. The lower third of the first 900px reveals the top of the full-width Geometric tile sculpture, beginning around 600px visually, with pale ground planes behind saturated upright tiles. Text and actions remain fully readable above the artwork; the scene continues well below the fold before the story rail.

**Transfer:** Use an equally direct benefit promise and a product-specific tile sculpture when custom art is unavailable. App-download openings retain the centered display and paired actions but substitute overlapping hardware. Pricing opens with a smaller left-aligned title and paragraph centered in a narrow reading column. Feature-explanation openings use a two-column chapter with illustration and a quotation.

**Avoid:** Do not replace this with a generic split hero, an abstract blurred gradient, or a small illustration stranded beside the headline.

**Text style:** `display` — DropmarkRealHead 500 · 60px/1.2

### Story rail

**Observed:** Story card items form a full-width horizontal strip around 155px tall on Warm band. Images and text alternate within the cards, outer items clip beyond the viewport, and Carousel control buttons float at both edges.

**Transfer:** Use the rail for concrete examples of what people can do with the product, keeping each item readable as a compact teaser.

### Paired graphic proof

**Observed:** Two 641px by 419px square-edged panels sit on Warm band with 40px outer clearance and approximately 78px between them at desktop. Customer proof tile centers a generous two-line heading over a clipped logo strip. Graphic stat tile combines art and a centered stack of four facts. The band has 60px lower padding and transitions directly to the white footer.

**Transfer:** Use the juxtaposition of recognition and quantified evidence wherever the narrative needs reassurance. Keep the graphic split and compact number treatment even when the exact proof categories differ.

### Compact utility ending

**Observed:** All page types finish with the same white footer: 1200px container, 30px top and bottom padding, attribution and copyright at left, four narrow link groups at right, all in small. No giant closing slogan or newsletter panel intervenes.

**Transfer:** Keep the ending useful and understated; group links by purpose and let the final substantive section carry the persuasion.

**Text style:** `small` — DropmarkRealText 400 · 16px/1.5

### Illustrated chapter with quotation

**Only for:** feature-explanation pages

**Observed:** A 1200px two-column layout pairs 480px of left-aligned chapter-heading and body with a 600px illustration; the next chapter reverses the arrangement. A Testimonial accent and attributed quote follow the prose. Below each chapter, four icon-led summaries use 252px columns with 48px gaps and small body text with a bold lead-in.

**Transfer:** Explain one broad benefit per chapter and let the supporting summaries name specific capabilities.

**Text style:** `chapter-heading` — DropmarkRealHead 500 · 38px/1.2

### Navy product interlude

**Only for:** feature-explanation pages

**Observed:** Navy proof panel expands into a full-width 461px band with 80px surrounding vertical separation. A 600px product view occupies the left half; centered band-heading, band-body and Primary button occupy a 440px text measure on the right. A narrow multicolor geometric strip meets the far right edge.

**Transfer:** Use a dark interlude to convert an illustrated promise into tangible product proof, maintaining a light interface against navy.

**Text style:** `band-heading` — DropmarkRealHead 500 · 32px/1.2

### Open comparison and reassurance

**Only for:** pricing pages

**Observed:** The 500px reading-column introduction begins 80px below the header. Four Plan header columns follow, separated by 48px, with plain feature lists underneath. A customer-logo strip separates comparison from an ivory FAQ band. FAQ answers remain expanded in a 500px column; questions have 25px top spacing and 10px before answers. The last answer offers support links, followed by the standard footer.

**Transfer:** Preserve transparent billing notes and open answers; change the number of columns to suit the product rather than manufacturing tiers.

**Text style:** `chapter-heading` — DropmarkRealHead 500 · 38px/1.2

### App platform and integration close

**Only for:** app-download pages

**Observed:** Centered display, body and paired actions lead into overlapping Hardware scenes. A later monitor-and-copy split uses a 40px heading and a cyan download action. The close is a 40px heading over six unboxed integration articles in a three-column grid, with 25px headings, gray body prose and underlined inline links; the standard footer follows without a large final CTA.

**Transfer:** Lead with the main platform, then secondary access methods; let concise compatibility information close the case.

**Text style:** `display` — DropmarkRealHead 500 · 60px/1.2

## Page flow

**Storyline:** Direct promise → expressive visual explanation → concrete ways to use it → confidence-building proof → compact utility ending; specialize the middle for comparison, capabilities or downloads.

### General product landing page

1. **Promise** — Centered two-line display, concise support and two actions.
2. **Visual explanation** — A large geometric scene unfolds beyond the first screen.
3. **Use cases** — A clipped horizontal story rail supplies concrete examples.
4. **Social and quantified proof** — Paired monochrome-logo and illustrated-stat panels on warm ivory.
5. **Utility ending** — Small white multi-column footer.

**Transfer:** Use bold original illustration to make an abstract product feel approachable, then ground it in actual use and credible proof.

### Plan selection and objection handling

1. **Orientation** — Narrow introduction identifies that there is a suitable option for different needs.
2. **Comparison** — Four colored price headers above open feature lists.
3. **Social proof** — A monochrome customer-logo strip.
4. **Objection handling** — Expanded FAQ on warm ivory, ending in direct support links.
5. **Utility ending** — The shared white footer.

**Transfer:** Use color to distinguish options, and prose to explain decisions and billing without hiding details in interactions.

### Platform download and access options

1. **Platform promise** — Centered display, useful support, download and video actions.
2. **Product demonstration** — Overlapping mobile hardware followed by a desktop scene and download action.
3. **Compatibility** — Six unboxed articles describe additional entry points with inline links.
4. **Utility ending** — The shared white footer.

**Transfer:** Present the main platform first, secondary platform next, and alternate access paths as a concise editorial grid.

### Capability explanation

1. **Benefit chapter** — Text, quotation and colorful illustration in two columns.
2. **Capability detail** — Four small colorful icon-led summaries.
3. **Product demonstration and action** — Navy band with a large browser view, centered pitch and cyan button.
4. **Second benefit chapter** — Reversed illustration and quotation layout followed by another capability row.
5. **Utility ending** — The shared white footer follows the last capability row directly.

**Transfer:** Alternate expressive scenes with precise small summaries, using the dark product interlude as a visual reset.

## Writing

Friendly, practical and confident without sounding technical or grandiose. Benefits are framed as everyday work getting easier, with small flashes of playful language.

**Do not copy:** Do not reuse the Dropmark name, logo, artwork, customer marks, named people, quotations, prices, tenure or usage counts. Supply original product content and verified claims. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team; use we sparingly for intentions and support. Name the product when a sentence needs clarity.
- **Rhythm:** Short sentence-case headlines, followed by one or two explanatory sentences. Lists and compact labels handle specifics; conversational contractions keep long answers approachable.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a useful category, then qualify it with a human need. | 6–12 words | “Visual organization for people with things to do” |
| Support | Explain who it serves and what they can do with a simple verb sequence. | 18–30 words | “[Brand] is the smart way for teams and individuals to collect, organize, and discuss anything on the web.” |
| Action | A direct verb and a low-friction next step. | 2–6 words | “Show me more”<br>“Try free for 14 days” |
| Story title | A small everyday frustration or inviting possibility. | 3–5 words | “Escape email ping-pong”<br>“Start an adventure” |
| Chapter headline | A concrete benefit expressed as a familiar phrase. | 7–13 words | “See the big picture by bringing all your materials together”<br>“All the people you need, in one place” |
| FAQ question | Ask the practical question a buyer would actually say aloud. | 4–12 words | “Can I change my plan?” |

**Words and phrasing to use:** your team; all in one place; collect, organize, and discuss; make it easy; right from; on the go; a breeze

**Avoid:** revolutionary ecosystem; unlock limitless potential; synergize; enterprise-grade transformation; disrupt the future

**Rules:**

- Lead with the outcome; put format and integration specifics in supporting copy.
- Use familiar verbs and concrete objects instead of abstract benefit stacks.
- State billing qualifications next to prices, not only in footnotes.
- Let proof labels be short nouns; do not make every number into a slogan.
- Keep FAQ answers direct and complete, ending with a useful next step when necessary.

## Do's and Don'ts

### Do

- Keep the opening headline at 60px/1.2 and within a 720px measure at desktop.
- Keep the main support line at 20px/1.5 and around 500px wide.
- Use 3px corners and 8px 20px 10px padding on conversion buttons.
- Anchor the visual identity in hard-edged flat geometric illustration, with an original SVG fallback.
- Use #f7f7f1 to connect proof content and #1e2554 for concentrated contrast.
- Set proof values at 24px/1.2 with tabular lining numerals and 14px/1.2 labels.
- Preserve square, shadow-free story and proof panels.
- End with a 30px-padded, 16px/1.5 utility footer rather than another campaign.

### Don't

- Do not turn the 3px action corners into pill buttons or round every panel.
- Do not apply negative tracking across the headings; this style uses normal tracking.
- Do not enlarge proof numbers into dominant 80px dashboard counters.
- Do not use cyan as an all-page background; keep it in actions, facts and illustration.
- Do not give story cards floating drop shadows or glass backdrops; their edge is a 1px alpha hairline.
- Do not wrap pricing feature lists in the colored header fill; lists belong below on white.
- Do not box integration descriptions into a generic card grid; they are open columns.
- Do not use the bold uppercase FAQ treatment for ordinary section headlines.

## Motion and responsive

### Motion

**Observed:**

- Text links and the charcoal navigation action declare opacity 0.1s transitions, with hover opacity 0.6.
- Cyan actions and story links declare filter 0.225s transitions to brightness(120%).
- Secondary action declares background-color 0.225s and box-shadow 0.225s transitions; hover removes the inset shadow and changes the fill to warm ivory.
- Customer logos declare a 60s linear infinite scrolling animation.
- Carousel controls declare white hover fill and active opacity 0.6.

**Transfer:**

- Keep the logo strip a slow, continuous monochrome drift rather than a fast promotional ticker.
- Use the brief opacity and brightness feedback to retain the flat, lightweight action treatment.

**Unknown:**

- Illustration animation timing and settled-to-moving behavior are not established.
- No focus-visible appearance is established; provide an accessible focus treatment without treating it as a brand-specific effect.

### Responsive

**Observed:**

- The desktop composition uses centered 1200px containers. Styles declare many breakpoints, including 479px, 719px, 959px and 1199px.

**Transfer:**

- On narrower layouts, retain the centered promise and readable support before stacking actions as needed.
- Stack graphic proof panels while keeping the art-and-fact split within the navy panel where space permits.
- Reduce comparison and capability column counts before shrinking text; keep the story rail horizontally navigable.
- Scale the SVG scene as a coherent construction instead of scattering its symbols into unrelated mobile cards.

**Unknown:**

- Exact mobile font sizes, navigation changes and column-collapse thresholds are not established. These narrow-layout rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
