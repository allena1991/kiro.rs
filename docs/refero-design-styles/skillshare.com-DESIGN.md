# Skillshare — creative momentum in loops

## Overview

An upbeat geometric sans style that pairs practical product explanations with the energy of a creative studio. White and pale gray chapters alternate with substantial black stages, while mint actions, cyan highlights and rainbow linework keep the mood optimistic. Candid portraits, colorful work samples and straightforward interface images make it suitable for community, productivity and subscription products. The overall composition is spacious, with deliberately dense browsing grids.

### Essentials

- Bold, friendly promises rather than oversized manifesto type: geometric sans headlines at 50px/1.1 and 700 weight, section titles at 46px/1.2, all with normal tracking.
- A promise on the left, a loose rainbow gesture on the right: the opening uses a 1200px container, a 600px text column and a mint action beneath the copy; the colorful stroke exits the white canvas rather than sitting in a card.
- High contrast carries the page, not an all-over color wash: long black proof and discovery bands interrupt white and pale gray sections; mint #55da9b is concentrated in actions and cyan #24c2f2 in selection and short emphasized passages.
- Actions are small rectangles, not pills: 4px corners, 16px/24px bold text and 12px 24px padding for the main 48px-tall button; pills belong to category filters with 100px corners and 1px outlines.
- Real work and real people are the visual substance: 272px-wide image-led cards form four-column grids with 16px gaps, while portraits preserve natural interiors, expressions and saturated creative surroundings.
- The looping color stroke and cyan line-face testimonial badges are signature punctuation: include a crisp open gradient ribbon and 64px circular proof badges, using a simple SVG curve and original abstract line drawings when equivalent artwork is unavailable.
- The ending has a deliberate dark landing: a 1200px black conversion panel with 12px corners can carry the rainbow gesture, and the compact dark footer closes with five columns, a 1px mint rule and centered small social marks.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action mint | `#55da9b` | `--color-mint` | action, background, border, accent | Primary buttons, footer dividing rule and the green portion of the signature line. |
| Deep blue ink | `#002333` | `--color-ink` | text | Primary headings and body copy on light surfaces. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Selection cyan | `#24c2f2` | `--color-cyan` | accent, surface, border, text | Selected category filter, testimonial badges, emphasized quote passages and primary-button hover. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Product chapter ink | `#0b1926` | `--color-technical-ink` | text | Capability statements beside dashboard images. |
| Stage black | `#000000` | `--color-black` | background, text, border | Discovery and testimonial stages, high-contrast text and accordion rules. |
| Blue charcoal | `#0b1215` | `--color-footer` | background, text | Footer and dark secondary header action. |
| Metadata gray | `#394649` | `--color-muted` | text, border | Card metadata and restrained outlined controls. |
| Separator gray | `#dcdee1` | `--color-rule` | border | Testimonial attribution rules and search field edges. |
| Gallery gray | `#f4f4f4` | `--color-muted-surface` | background | Backing for the portrait gallery. |
| Almost white | `#fafafa` | `--color-soft` | background, text | Product capability chapters and slightly softened reversed headings. |
| White | `#ffffff` | `--color-white` | background, surface, text, border | Opening canvas, cards, reversed text and filter outlines. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| promotional offers and account acquisition | Promotional violet | `#5620c1` | `--color-purple` | background, text | Inset promotional banner and an email sign-up link. |
| consumer acquisition pages | Proof tile charcoal | `#232424` | `--color-stat` | surface | Compact metric tiles on black. |

## Typography

- **GT Walsheim Pro** — All marketing headings, paragraphs, controls and metadata. A broad, approachable geometric sans with circular counters and a strongly rounded bold cut. If unavailable, use **DM Sans**. Use 400–700 weights; retain normal tracking and tune wrapping to the broad headline measure. Font stack: "GT Walsheim Pro", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | GT Walsheim Pro | 700 | 50px | 1.1 | normal | Default opening promise, usually broken into three strong lines. |
| heading-lg | GT Walsheim Pro | 700 | 46px | 1.2 | normal | Main section titles and large unboxed proof numbers. |
| heading | GT Walsheim Pro | 700 | 36px | 44px | normal | Portrait gallery heading and centered question-section heading. |
| capability | GT Walsheim Pro | 700 | 36px | 1.2 | normal | Short capability statements and conversion-panel offer lines. |
| body-lg | GT Walsheim Pro | 400 | 22px | 1.5 | normal | Expanded benefit explanations and introductory paragraphs. |
| quote | GT Walsheim Pro | 400 | 18px | 24px | normal | Default dark-stage testimonial text and attribution details. |
| quote-emphasis | GT Walsheim Pro | 700 | 18px | 24px | normal | Cyan-highlighted statements within testimonials. |
| footer-heading | GT Walsheim Pro | 700 | 18px | 1.55 | normal | Footer column headings. |
| body | GT Walsheim Pro | 400 | 16px | 1.5 | normal | Opening support paragraph. |
| control | GT Walsheim Pro | 700 | 16px | 1.5 | normal | Primary actions, navigation and category filters. |
| card-title | GT Walsheim Pro | 600 | 15px | 1.33 | normal | Multi-line image-card titles. |
| footer-link | GT Walsheim Pro | 400 | 14px | 1.14 | normal | Footer links and final utility line. |
| metadata | GT Walsheim Pro | 400 | 13px | 1 | normal | Counts and duration labels beneath image thumbnails. |
| card-credit | GT Walsheim Pro | 400 | 13px | 24px | normal | Creator credit at the bottom of an image card. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| consumer acquisition pages | consumer-display | GT Walsheim Pro | 700 | 46px | 1.26 | normal | Consumer promise and catalog section headings. |
| consumer portrait galleries | portrait-name | GT Walsheim Pro | 700 | 38.4px | 0.9 | normal | Large centered names over portraits. |
| consumer acquisition pages | compact-proof | GT Walsheim Pro | 700 | 36px | 1 | normal | Large values within charcoal metric tiles. |
| consumer acquisition pages | question | GT Walsheim Pro | 700 | 22px | 1.3 | normal | Question rows and emphasized consumer quotes. |
| consumer acquisition pages | answer | GT Walsheim Pro | 400 | 16px | 22px | normal | Expanded answer paragraphs. |

**Notes:**

- Keep the headline voice bold and rounded; do not substitute a condensed or monospaced display face.
- Tracking remains normal through the scale. The small portrait kicker is the exception at 0.1em.
- Default section headlines use 1.2 line height. Consumer discovery headings use 1.26; portrait names deliberately compress to 0.9.
- Use the single sans family for metadata too; a separately named Regular cut is not a separate typographic voice.

## Layout

**Density:** Airy chapters around compact evidence: broad section padding contrasts with closely packed filter rows and image-card grids.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Filter gaps and image-card content padding. |
| 16px | Grid gaps, attribution icon-to-text separation and tight content stacks. |
| 24px | Headline-to-support gap and main button horizontal padding. |
| 32px | Inset promotional panel horizontal padding. |
| 36px | Opening text-group to action-group spacing. |
| 40px | Footer column gaps. |
| 48px | Footer grid to final utility block spacing. |
| 56px | Closing panel title-to-offer separation. |
| 64px | Wide section side padding and gallery heading-to-grid separation. |
| 80px | Default major-section vertical padding and capability-row separation. |
| 96px | Expanded consumer testimonial section padding. |
| 120px | Consumer metric-band vertical padding. |

### Containers and grids

- **main container**: max width 1200px · side padding 64px. Centered default marketing chapters; at 1440px the inner content begins 120px from either edge.
- **opening text**: max width 600px. Half-width text column, with a 582px headline measure and decorative linework in the other half.
- **catalog grid**: max width 1136px · 4 columns · gap 16px. Four 272px image cards per row on a black stage.
- **portrait grid**: max width 1136px · 4 columns · gap 16px. Default four-column expert gallery, with credits beneath images.
- **footer grid**: max width 1090px · 5 columns · gap 40px. Five compact link groups above a full-width mint divider.
- **question stack** (only for consumer acquisition pages): max width 821px. Centered accordion narrower than the main container.

## Corner radius

| Element | Radius |
| --- | --- |
| controls | 4px |
| portrait and promotional cards | 8px |
| conversion panel | 12px |
| category filters | 100px |
| attribution badges | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| catalog card | `rgba(0, 0, 0, 0.1) 0px 2px 4px 0px` | Low lift on white image cards. |
| portrait card | `rgba(180, 184, 184, 0.5) 0px 2px 4px 0px` | Soft narrow shadow beneath portrait imagery. |

### Surfaces

#### White canvas · level 0

**Use:** Opening, introductory proof and lighter breathing spaces.

**CSS:** `background: #ffffff; color: #002333`

**Observed:** Full-width, flat and untextured; decoration is separate from the background.

**Transfer:** Let content and linework supply the color rather than tinting the whole canvas.

#### Black stage · level 0

**Use:** Catalog browsing and testimonial chapters.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** A sustained black band, not isolated black cards on white.

**Transfer:** Group visually rich proof or browsing content on one continuous dark field.

#### Capability canvas · level 0

**Use:** Alternating interface demonstrations.

**CSS:** `background: #fafafa; color: #0b1926`

**Observed:** Near-white backing with no visible enclosing card around each capability row.

**Transfer:** Use an unobtrusive backdrop so the interface images remain readable.

#### Gallery canvas · level 0

**Use:** Default expert portrait gallery.

**CSS:** `background: #f4f4f4; color: #002333`

**Observed:** A pale gray band distinguishes the people chapter from the neighboring white sections.

**Transfer:** Use for people or practitioner proof, not every repeated grid.

#### Rainbow conversion panel · level 1

**Use:** Closing conversion chapter.

**CSS:** `background: #000000; color: #ffffff; border-radius: 12px; overflow: hidden; padding: 102px 0px`

**Observed:** Inset within white margins; cropped rainbow loops enter from opposite corners.

**Transfer:** Keep the ribbon away from the central offers and actions.

#### Promotional banner · level 1

**Only for:** promotional offers and account acquisition

**Use:** A compact secondary offer.

**CSS:** `background: #5620c1; color: #fafafa; border-radius: 8px; padding: 0px 32px; overflow: hidden`

**Observed:** Violet panel with low-contrast angular rays, a tilted central artifact, bold copy at left and explanation plus mint action at right.

**Transfer:** Use a real offer artifact or simple original ticket shape, keeping the three-part balance.

## Components

### Navigation

**Use:** Persistent orientation and conversion.

**CSS:** `position: fixed; top: 0px; width: 100%; height: 80px; background: #000000; color: #ffffff; display: flex; align-items: center; justify-content: space-between`

**Text style:** `control` — GT Walsheim Pro 700 · 16px/1.5

**Observed:** A compact wordmark sits left; a few links, a dark secondary action and a mint plan action cluster at right. The consumer variant is white, with browse control, a 500px search field and account actions.

**Transfer:** Use the black navigation as the default. Reserve search-heavy navigation for large content libraries.

### Primary button

**Use:** The main conversion action on both white and black.

**CSS:** `background: #55da9b; color: #000000; border-radius: 4px; padding: 12px 24px; height: 48px; display: flex; align-items: center; justify-content: center`

**Text style:** `control` — GT Walsheim Pro 700 · 16px/1.5

**Observed:** Plain bold label without an arrow; the compact navigation version uses 6px 16px padding and 36px height.

**States:** Declared: hover background-color #24c2f2; focus-visible styling is unknown.

### Category filter

**Use:** Dense browsing choices above an image grid.

**CSS:** `border: 1px solid #ffffff; border-radius: 100px; padding: 4px 16px; color: #ffffff; height: 34px`

**Text style:** `control` — GT Walsheim Pro 700 · 16px/1.5

**Observed:** Centered wrapping rows with 8px gaps. One selected item uses cyan fill and cyan border with dark text; the remaining items stay transparent.

### Image content card

**Use:** Browseable examples, resources or product outcomes.

**CSS:** `background: #ffffff; border-radius: 4px 8px 8px 8px; box-shadow: rgba(0, 0, 0, 0.1) 0px 2px 4px 0px; max-width: 272px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-title` — GT Walsheim Pro 600 · 15px/1.33

**Observed:** A 272px by 153px thumbnail leads. The white body has 8px padding, a small count-and-duration row, a bold title and a quiet creator credit. Total height is about 283px. Thumbnail badges sit over a dark translucent top gradient.

**Transfer:** Keep actual work or useful demonstrations in the thumbnail, with real metadata rather than decorative filler.

### Portrait card

**Use:** Expert or practitioner proof.

**CSS:** `border-radius: 8px; box-shadow: rgba(180, 184, 184, 0.5) 0px 2px 4px 0px; overflow: hidden; width: 272px; height: 340px`

**Observed:** Default portraits use full-color environmental photography with names and short credentials beneath, outside the image. The consumer variant uses 268px by 380px rectangular portraits, a bottom black fade, a centered underlined kicker and tightly stacked white names.

**Transfer:** Use credible practitioners in real environments; keep credits factual and short.

### Testimonial attribution

**Use:** Distinctive proof marker above each quote.

**CSS:** `display: flex; align-items: center; gap: 16px; border-bottom: 1px solid #dcdee1; padding-bottom: 20px; margin-bottom: 20px`

**Text style:** `quote` — GT Walsheim Pro 400 · 18px/24px

**Observed:** A 64px cyan circle containing an irregular black line-face sits beside a bold name and regular role. The quote below contains selected bold cyan clauses on black. Consumer quotes are centered on white and use black emphasis instead.

**Transfer:** Use original abstract continuous-line faces rather than a uniform headshot grid.

### Closing offer columns

**Use:** Two self-serve and assisted-conversion paths inside the Rainbow conversion panel.

**CSS:** `display: grid; grid-template-columns: repeat(2, 1fr); color: #ffffff; text-align: center; gap: 0px`

**Text style:** `capability` — GT Walsheim Pro 700 · 36px/1.2

**Observed:** Centered outline illustrations sit over bold offer lines and mint buttons. The left column ends with a 1px white divider at half opacity. A shared 46px heading sits above both columns.

**Transfer:** Split by purchasing need or customer scale only when there are two genuine routes.

### Footer

**Use:** The final navigation and utility landing.

**CSS:** `background: #0b1215; color: #ffffff; padding: 30px 0px`

**Text style:** `footer-link` — GT Walsheim Pro 400 · 14px/1.14

**Observed:** Five columns with 18px bold headings, 14px links and 12px link separation; marketplace badges occupy the final group. After 48px, a mint top rule introduces centered utility text and a second row of small white social marks. Consumer variant uses pure black.

**Transfer:** Retain the mint hairline and centered final rows even with fewer link groups.

### Metric tile

**Only for:** consumer acquisition pages

**Use:** Compact quantified proof on a black band.

**CSS:** `background: #232424; border-radius: 8px; padding: 24px; height: 110px; display: flex; flex-direction: column; align-items: center; justify-content: center`

**Text style:** `compact-proof` — GT Walsheim Pro 700 · 36px/1

**Observed:** A bold value over an uppercase 16px category label; four tiles form a row with 48px gaps.

**Transfer:** Use comparable substantiated numbers; for a smaller set, preserve the compact tile rather than inflating the figures.

### Question row

**Only for:** consumer acquisition pages

**Use:** Objection handling.

**CSS:** `border-top: 1px solid #000000; padding: 16px 0px; display: flex; justify-content: space-between; align-items: center`

**Text style:** `question` — GT Walsheim Pro 700 · 22px/1.3

**Observed:** An 821px-wide centered stack with a bold question and small expansion control; expanded text is 16px/22px and has 15px bottom padding.

## Imagery and graphics

### Rainbow gesture

**Use:** Signature decoration in the opening and closing conversion stage.

**Observed:** A clean thick open line sweeps in a large loose loop, shifting from mint through cyan and violet to magenta and warm orange. It is crisp, not glowing, and extends past the canvas edge. The opening puts it on the right, balancing rather than framing the headline; the closing uses partial arcs at opposite corners.

**Transfer:** Always retain a large open gesture, even for a product without rich media. A single original looping SVG line is a sufficient equivalent.

**Build:** Draw an unfilled cubic Bézier path in an SVG viewBox around 700 by 450. Use a rounded stroke around 18px wide, no shadow or blur, and a user-space linear gradient progressing mint, cyan, violet, magenta and orange. Make a broad shallow bowl, reverse into a high loop, then sweep out beyond the right edge. Clip the SVG at its container; in the black closing panel reuse smaller partial curves at bottom-left and top-right. Exact gradient stops are not essential.

### Environmental portraits

**Use:** People-led proof gallery.

**Observed:** Waist-up or seated people appear in studios, offices or outdoor working settings. Natural light, visible surroundings and saturated artwork add texture without an artificial duotone. Images occupy most of each card.

**Transfer:** Show users or practitioners doing work in believable environments, with diverse compositions and comparable face scale.

### Work thumbnails

**Use:** Browsing cards and consumer category strip.

**Observed:** Richly colored creative outputs, close-ups of tools and hands, portraits and interface compositions coexist. Browsing thumbnails are wide; the consumer strip uses edge-to-edge 320px by 400px images with white category labels near the top and no gutters.

**Transfer:** Mix real outcomes with process imagery; for an abstract product, render a genuine use-case artifact instead of stock mood photos.

### Interface chapters

**Use:** Capability explanations on the almost-white canvas.

**Observed:** Crisp rectangular dashboard images show tables, a violet area graph and bar metrics. They alternate left and right beside large bold statements and are not enclosed in elaborate device mockups.

**Transfer:** Use authentic interface images or a minimal faithful workflow diagram; keep the surrounding marketing surface nearly white.

### Cyan line faces

**Use:** Signature testimonial badge.

**Observed:** Black continuous-line facial gestures sit inside flat cyan circles, with each face slightly different. These playful badges replace personal photography in the testimonial groups.

**Transfer:** Create original single-line abstract faces for every quote, preserving the uniform colored disc.

**Build:** Use a 64px circular cyan background with overflow hidden. Draw one black SVG path with no fill and a thin rounded stroke: a loose vertical curve, an oval eye loop and a second curved mouth or chin. Vary the path rather than repeating one generic user icon.

### Floating work cascade

**Only for:** consumer community feature chapters

**Use:** A large visual counterpart to stacked benefit statements.

**Observed:** White social-post frames containing colorful handmade work tilt in perspective and recede toward the upper-right against pure black. A large foreground card leads a diminishing fan of overlapping cards, occupying about half the content width.

**Transfer:** Use authentic project outputs or customer artifacts in simple white frames; a minimum of three differently scaled, rotated cards creates the same depth.

**Build:** Arrange white rectangular cards in an approximately 600px by 820px scene. Anchor the largest toward the lower-left, rotate it slightly clockwise and position progressively smaller cards diagonally upward and right. Use perspective and modest Y-axis rotation, retaining white frame edges and clear colorful centers.

### Icons

**Observed:** Functional chevrons and social marks are small solid silhouettes, commonly 24px. Benefit illustrations are larger black outline doodles on white; closing-offer illustrations reverse to white. The consumer community chapter uses bright single-color outline icons above centered statements.

**Transfer:** Keep navigation icons subordinate to the bold labels. Use simple, friendly outline illustrations for conceptual benefits, not a large multicolor icon library.

## Section recipes

How recurring sections are built.

### First screen: Promise and looping gesture

**Observed:** A fixed 80px black Navigation caps a white opening. A centered 1200px composition places a 600px text stack on the left and a large Rainbow gesture cropped at the top and right. The 50px bold deep-blue headline fills about half the content width in three lines; 16px/24px support follows with a 24px text-stack gap and a mint Primary button sits below. The hero is about 505px tall. Within the first 900px, the complete promise, support, action, ribbon and a logo proof row are visible, along with the start of an inset promotional banner. The catalog stage sits farther below. Layers are flat white, decorative line, then readable text and action; no enclosing hero card.

**Transfer:** For a new product, write a concrete capability promise and balance it with an original SVG ribbon rather than requiring a hero photograph. Keep any actual product image for a later demonstration. Consumer acquisition can open with a shorter 46px/1.26 promise at left, a compact sign-up stack at right and a full-width image strip beneath.

**Avoid:** Do not center the whole hero, stretch the title across the entire viewport or replace the crisp ribbon with a blurred rainbow background.

**Text style:** `display` — GT Walsheim Pro 700 · 50px/1.1

### Heading and proof pair

**Observed:** On white, a 46px title occupies the left half and 22px/33px explanatory paragraphs occupy the right. A lower row distributes five bold statistics evenly, each with a regular 20px label. Section padding is 80px vertically.

**Transfer:** Use the upper pair to explain the promise and the lower row to quantify its breadth with real comparable facts.

**Text style:** `heading-lg` — GT Walsheim Pro 700 · 46px/1.2

### Dark discovery stage

**Observed:** A centered 46px heading sits above wrapping Category filters and a four-column Image content card grid. The content grid is 1136px wide with 16px gaps and two rows; the black stage has 60px top and about 80px bottom padding.

**Transfer:** Translate the library into examples, templates, use cases or resources while retaining the density contrast between the spacious heading and compact cards.

**Text style:** `consumer-display` — GT Walsheim Pro 700 · 46px/1.26

### Asymmetric testimonial stage

**Observed:** A black band sets a large heading over a quote in the left column and two quotes in the right. Testimonial attribution components lead each block. Oversized dark-gray quotation marks punctuate the outer edges; bold cyan clauses pick out outcomes. Consumer proof instead uses a centered heading and a two-by-two white layout with centered black quotes.

**Transfer:** Vary quote lengths and emphasize only the outcome clause; retain cyan faces and the distinction between attribution and testimony.

**Text style:** `quote` — GT Walsheim Pro 400 · 18px/24px

### Alternating capability chapters

**Observed:** On Capability canvas, a centered 46px title introduces three alternating image-and-statement rows. Images range roughly 454–603px wide, while statements use 36px/1.2 bold type within a 488px measure. Rows have 80px separation.

**Transfer:** Pair each statement with a different real task or result, alternating sides without adding surrounding feature cards.

**Text style:** `capability` — GT Walsheim Pro 700 · 36px/1.2

### Outline benefit row

**Observed:** A white band with an 80px vertical inset places a centered 46px heading over a horizontal set of black line illustrations, 22px bold short labels and 14px/21px centered explanations.

**Transfer:** Use a small set of distinct benefits with recognizable conceptual drawings and very short support, allowing the row to wrap for narrower layouts.

**Text style:** `heading-lg` — GT Walsheim Pro 700 · 46px/1.2

### People gallery

**Observed:** Gallery canvas holds a 36px heading at left and a concise explanatory paragraph at right, followed after about 64px by the four-column Portrait card grid. Two rows provide a substantial people-led chapter. Default names and credentials sit beneath photos; consumer portrait galleries place white name labels over a bottom fade on a white section.

**Transfer:** Use practitioners, users or partners whose identity supports the product's credibility. Keep the imagery dominant.

**Text style:** `heading` — GT Walsheim Pro 700 · 36px/44px

### Framed closing offer

**Observed:** White 80px section padding surrounds the 1200px Rainbow conversion panel. A centered heading leads Closing offer columns, with a shared large promise, two illustrated offers, a fine central divider and mint actions. The colored curves enter only at the corners.

**Transfer:** Make a clear final decision stage for the new product. When there is only one conversion route, retain the dark ribbon-backed panel with one centered offer rather than inventing a second plan.

**Text style:** `heading-lg` — GT Walsheim Pro 700 · 46px/1.2

### Dark utility ending

**Observed:** The Footer follows the conversion stage on the default marketing treatment. The consumer ending is longer: a question stack, a black press-logo band, a social and recurring-billing notice band, a white three-column topic directory, then the black Footer. Both endings use the mint divider and centered utility/social rows.

**Transfer:** End with useful navigation rather than a giant decorative wordmark. Keep any directory specific to content-heavy products, and any subscription notice specific to the business model.

**Text style:** `footer-link` — GT Walsheim Pro 400 · 14px/1.14

## Page flow

**Storyline:** Concrete promise → breadth and proof → useful examples → human validation → practical capabilities → credible people → conversion and utility landing.

### Default product or business marketing landing page

1. **Promise** — Left-aligned bold promise and support with one mint action, balanced by a cropped rainbow line.
2. **Social proof** — A spacious customer-logo row followed by a compact violet secondary-offer banner.
3. **Quantified proof** — A split introductory explanation followed by a row of large values and short labels.
4. **Product examples** — Black catalog stage with pills and a dense image-led grid.
5. **Human validation** — Asymmetric reversed quotes with cyan faces and outcome highlights.
6. **Capabilities** — Alternating interface-image rows followed by an outline-illustration benefit row.
7. **Expert credibility** — Pale-gray gallery of environmental portraits and factual credentials.
8. **Closing conversion** — Inset black ribbon-decorated offer panel, then a compact blue-charcoal footer.

**Transfer:** Use this as a flexible business-product narrative; select proof and demonstrations that make the promise credible without requiring a library or team-management product.

### Consumer subscription and content discovery acquisition

1. **Promise and immediate conversion** — White hero pairs a two-line promise with provider sign-up options; an edge-to-edge creative category strip follows.
2. **Breadth and quantified proof** — Black benefit list and compact charcoal metric tiles.
3. **Discovery** — Outlined filter pills introduce white image cards on black.
4. **Community demonstration** — Centered benefit statements oppose a perspective cascade of colorful work.
5. **Human credibility** — White environmental portrait wall followed by centered testimonial groups.
6. **Adjacent offer** — A black split text-and-photo business callout.
7. **Objection handling** — Narrow centered question rows on white.
8. **Utility ending** — Black press and social bands, subscription notice, white topic directory and black five-column footer.

**Transfer:** Use the immediate sign-up opening for transactional acquisition; retain the richly visual discovery and practical final utility instead of forcing the business pricing close.

## Writing

Encouraging, direct and generously optimistic. Confidence comes from concrete skills, people and useful outcomes rather than technical mystique or hard-sell urgency.

**Do not copy:** Do not reuse Skillshare names, logos, customer marks, creator identities, proprietary artwork, testimonials, membership prices or numerical claims. Source quotations below illustrate sentence construction only; replace them with truthful product-specific copy. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Use the product name in explanatory statements and let customer quotes speak in the first person.
- **Rhythm:** Benefit headlines tend to be short title-case phrases; the opening may be a longer sentence broken into three lines. Support is usually one or two straightforward sentences. Short imperatives repeat to create momentum.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad but concrete capability promise addressed to a defined audience, connecting present usefulness with future growth. | 8–13 words | “All the Skills Your Creative Team Needs for Today and Tomorrow”<br>“Creative Classes Taught by the Best Creative Pros” |
| Benefit heading | An encouraging verb phrase with a tangible outcome. | 3–6 words | “Support Your Team's Growth”<br>“Explore Inspiring Online Courses” |
| Supporting line | Explain the benefit through things people can do; use a short list of active verbs. | 10–24 words | “Discover trending topics, get quick answers, and find your people.”<br>“Keep your team up on the latest trends and energized with thousands of classes updated weekly.” |
| Capability statement | A direct task followed by a practical reassurance. | 8–14 words | “Easily manage your seats. Add or remove members any time.” |
| Primary action | Plain verb and object; no invented cleverness. | 2–3 words | “Get Started”<br>“Contact Sales”<br>“Learn More” |

**Words and phrasing to use:** explore; inspiring; your way; growth; get started; learn; create; tools; share; today and tomorrow

**Avoid:** revolutionary disruption; dominate; 10x everything; exclusive elite; hustle harder; unprecedented synergy

**Rules:**

- Name the audience and outcome before explaining the mechanism.
- Use repeated short verbs to create a friendly cadence, not repeated exclamation marks.
- Use factual roles and credentials beneath people imagery.
- Highlight a specific result inside a quote rather than coloring the entire testimonial.
- Use numbers only when they make scale or usefulness easier to understand.

## Do's and Don'ts

### Do

- Keep the default opening headline at 50px, weight 700 and 1.1 line height.
- Set major chapters within a centered 1200px width and retain substantial 80px vertical padding.
- Use the mint 48px action as the stable conversion marker on both light and dark.
- Place 272px image cards in four-column grids with 16px gaps.
- Preserve the crisp gradient ribbon as a line, with ample empty space around it.
- Make cyan testimonial faces 64px circles and separate attributions from quotes with a 1px gray rule.
- Close on a compact dark footer with 14px links and a 1px mint divider.
- Keep natural portrait environments visible and use short factual credits.

### Don't

- Do not make primary buttons fully rounded; 100px radii are for filters, not conversion actions.
- Do not apply negative tracking throughout the type scale; the main text uses normal tracking.
- Do not replace the sustained black stages with a uniform pale-gray page.
- Do not turn every cyan emphasis into a full cyan panel; cyan mostly marks selection, faces and short text clauses.
- Do not add glass, noisy textures or broad drop shadows to the flat white and black surfaces.
- Do not use isolated purple portrait backings as a substitute for complete environmental photography.
- Do not enlarge metadata into body-sized captions; counts remain 13px.
- Do not end every page with pricing: consumer acquisition uses practical questions, directory links and utilities.

## Motion and responsive

### Motion

**Observed:**

- Primary business actions declare a 0.5s cubic-bezier(0.37, 0.01, 0, 0.98) transition and cyan hover fill.
- Category filters declare a 0.1s cubic-bezier(0.37, 0.01, 0, 0.98) transition.
- The consumer header sign-up action declares 200ms ease-in-out and changes mint to #50cf93 on hover.
- A category-strip animation is declared with an 80000ms linear infinite duration; a pause control is visible.

**Transfer:**

- Keep action changes restrained and color-led; do not animate the headline or blur the signature line.
- If using a moving edge-to-edge media strip, retain an explicit pause control.

**Unknown:**

- Actual animation trajectories and trigger behavior beyond the stated declarations.
- Focus-visible treatments and reduced-motion behavior.

### Responsive

**Observed:**

- Width breakpoints are declared at 599px, 640px, 810px, 899px and 991px for the business treatment.
- The consumer treatment additionally declares several breakpoints including 375px, 540px, 600px, 744px, 900px, 1200px and 1536px.

**Transfer:**

- On narrow layouts, prioritize the promise and mint action, move decorative loops away from text, and reduce four-column grids without compressing card contents.
- Allow category filters to wrap; keep the long media strip horizontally continuous rather than shrinking images to thumbnails.
- Stack closing offers and capability pairs while preserving the dark closing frame and image/text relationships.

**Unknown:**

- Rendered mobile column counts, header collapse, type sizes and exact breakpoint-specific spacing.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
