# User Interviews — serif meets doodle

## Overview

A personable, editorial style for software that connects people and simplifies complex work. Light canvases, warm off-white chapters and sea-green controls are enlivened by loose black line drawings, tiny portrait cutouts and pastel interface stages. Rounded serif headlines and friendly geometric sans-serif copy keep spacious marketing sections approachable, while small monospace labels add a practical, operational counterpoint. Deep painted-blue endings give the otherwise light experience a memorable finish.

### Essentials

- Editorial headlines inside a hand-drawn world: regular-weight serif at 64px/74px for the main promise and 50px/60px for section leads, with normal tracking; reserve bold italic serif for a short emphatic word.
- An illustrated opening surrounds rather than competes with the message: a centered 500px text column sits inside a 1300px stage with a 1284px-wide line-art composition, a 24px/32px support line and one centered action.
- Friendly pills against nearly square panels: main actions are 52px tall with 48px corners and 14px 22px 16px padding, while ordinary cards use just 5px corners.
- Color arrives in chapters, not everywhere: white is the default canvas; warm #f8f4f2 and pale mint or blue backings hold product content, green is concentrated in actions and highlights, and a deep painted navy field anchors the ending.
- People and software share the same visual plane: stage cropped white interface fragments on pale backings, overlap small circular portraits and add black looping paths, sparse stars and mint marks. When interface imagery is unavailable, use a simplified real workflow diagram with the same portrait-and-line treatment.
- The ending is a designed scene, not a utility afterthought: pair a white 50px/60px serif conversion line with a 440px × 375px comet-like line drawing, then continue the same navy painted field through grouped links and a separate 50px dark legal strip.
- Proof feels annotated by hand: compact monospace facts, underlined phrases, irregular loops and a single strong green testimonial tile interrupt otherwise pale proof cards; keep these devices crisp rather than glossy.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Teal action | `#1c5d5f` | `--color-teal-action` | action, background, link | Default main action on a light marketing canvas. |
| Bright emerald hover | `#177863` | `--color-green-hover` | action | Hover for emerald actions. |
| Sea teal | `#2a7779` | `--color-teal` | background, border, action | Default primary hover, announcement outline and occasional full-width proof bands. |
| Emerald | `#156152` | `--color-green` | action, text, link, background, border | Closing actions, compact product-page actions and operational eyebrows. |
| Painted navy | `#01152d` | `--color-navy` | background | Deep blue painted panels and the tonal family of the closing scene. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Drawn panel edge | `#158d71` | `--color-outline-green` | border | Thin outline around product demonstration and special pricing panels. |
| Footer mint | `#65b8a2` | `--color-footer-mint` | text, border | Small headings and legal links against navy. |
| Mint accent | `#bfddd5` | `--color-mint` | surface, accent | Flat offset shadows, phrase highlights and circular plus-icon backings. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep legal navy | `#021020` | `--color-legal-navy` | background | Bottom legal strip. |
| Black ink | `#000000` | `--color-ink` | text, border | Headlines, body text and hand-drawn outlines. |
| Stone divider | `#e6e2e0` | `--color-stone` | background, border | Muted separators and comparison-table category bars. |
| FAQ mint wash | `#edf5f3` | `--color-faq-wash` | surface | Low-contrast FAQ rows. |
| Warm paper | `#f8f4f2` | `--color-warm-paper` | background, surface | Alternating capability chapters, directory fields and pricing backings. |
| Cool paper | `#f4f9f9` | `--color-announcement-wash` | surface | Announcement capsule backing; also the visible result of a 20% pale teal wash over white. |
| White canvas | `#ffffff` | `--color-canvas` | background, surface, text | Default page, white cards and reversed copy on dark chapters. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Outline action ink | `#0d4a3e` | `--color-pricing-action-ink` | text | Text inside outlined pricing actions. |
| tabbed product demonstrations | Tab edge | `#3ea388` | `--color-tab-green` | border | Product-stage tabs. |
| integration directories | Data yellow | `#fff1ab` | `--color-tag-yellow` | surface | Data-category pills. |
| secondary-audience conversion sections | Berry chapter | `#662344` | `--color-berry` | background | A contrasting audience-conversion band, backed by darker painted swirls. |
| integration directories | Calendar blue | `#bdd1fb` | `--color-tag-blue` | surface | Calendar-category pills. |
| integration directories | Video mint | `#d4f6e5` | `--color-tag-mint` | surface | Video-category pills. |
| integration directories | Testing pink | `#f0cfe0` | `--color-tag-pink` | surface | Testing-category pills. |
| integration directories | Survey lilac | `#dcd7f1` | `--color-tag-lilac` | surface | Survey-category pills. |
| tabbed product demonstrations | Soft black | `#222222` | `--color-soft-ink` | text | Small operational tab text. |
| pricing selectors and integration directories | Warm hairline | `#cecbc9` | `--color-edge` | border | Light selector edges and dashed empty-directory invitation borders. |
| tabbed product demonstrations | Active mint wash | `#ecf6f3` | `--color-active-tab-wash` | surface | Selected product-stage tab backing. |
| company and culture content | Pale teal wash | `#f2f8f8` | `--color-benefit-wash` | surface | Visible 25% #cae1e2 over white on benefit cards. |

## Typography

- **p22-mackinac-pro** — Display promises, section headings and compact bold card titles; bold italic is a companion cut declared separately as P 22 Mackinac italic. Rounded, warm, low-drama editorial serif with distinctive personable curves. If unavailable, use **Lora**. Use 400 and 700 with italic; preserve generous line heights and the centered headline measure. Font stack: "p22-mackinac-pro", "Lora", Georgia, serif.
- **sofia-pro** — Body copy, navigation, controls and large numeric proof. Friendly geometric sans with open counters and soft forms, mainly regular rather than heavy. If unavailable, use **Nunito Sans**. Use 400, 500, 600 and 700; keep body copy at its compact measured size. Font stack: "sofia-pro", "Nunito Sans", Arial, sans-serif.
- **IBM Plex Mono** — Operational eyebrows, step labels, facts and footer group labels. Practical fixed-width lettering, often uppercase, providing contrast to the rounded serif. Font stack: "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | p22-mackinac-pro | 400 | 64px | 74px | normal | Default main marketing promise, centered in the illustrated opening or left aligned in a split product opening. |
| heading | p22-mackinac-pro | 400 | 50px | 1.2 | normal | Primary section leads and the closing conversion line. |
| emphasis | p22-mackinac-pro | 700 italic | 50px | 1.2 | normal | A short stressed word within a closing headline, using the bold italic companion cut. |
| hero-support | sofia-pro | 400 | 24px | 32px | normal | Centered opening support, usually two lines within the headline measure. |
| card-heading | p22-mackinac-pro | 700 | 20px | 1.3 | normal | Compact feature titles, plan names and directory item titles. |
| process-label | IBM Plex Mono | 500 | 20px | 1.3 | normal, uppercase | Prominent process introduction beneath a section title. |
| body | sofia-pro | 400 | 16px | 1.5 | normal | Default explanatory copy, navigation and feature bullets. |
| body-bold | sofia-pro | 700 | 16px | 1.5 | normal | FAQ questions, inline emphasis and substantial text links. |
| button | sofia-pro | 400 | 16px | 22px | normal | Default primary actions and the secondary closing text action. |
| eyebrow | IBM Plex Mono | 500 | 14px | 22px | normal, uppercase | Operational section labels above the serif lead. |
| footer-heading | IBM Plex Mono | 500 | 13px | 22px | 0.0385em, uppercase | Mint-colored labels over grouped footer links. |
| footer-link | sofia-pro | 400 | 13px | 19px | normal | White footer navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | p22-mackinac-pro | 400 | 56px | 68px | normal | Pricing opening promise, left aligned beside product art. |
| pricing pages | price | sofia-pro | 600 | 48px | 50px | normal | Dominant plan price with smaller currency and unit labels. |
| company overview pages | stat | sofia-pro | 600 | 48px | 52px | normal | Large white numerals across the teal proof strip. |
| secondary conversion and add-on sections | band-heading | p22-mackinac-pro | 400 | 44px | 58px | normal | White headline in the berry secondary-audience band and premium add-on panel. |
| company and culture content | editorial-heading | p22-mackinac-pro | 400 | 42px | 50px | normal | Story, team and culture headings. |
| company and culture content | quote | p22-mackinac-pro | 400 | 28px | 40px | normal | Long human testimonial set as an editorial quotation. |
| product-detail and pricing pages | compact-action | sofia-pro | 500 | 14px | 20px | normal | Smaller action recipe for product and pricing pages. |
| tabbed product demonstrations | product-tab | IBM Plex Mono | 500 | 11px | 20px | 0.091em, uppercase | Short workflow tabs beside small icons. |
| integration directories | category | sofia-pro | 600 | 10px | 18px | 0.05em, uppercase | Tiny pastel category pills beneath directory item titles. |

**Notes:**

- Maintain normal tracking on the large serif: the shape and loose line rhythm, not tight letterspacing or heavy weight, provide character.
- Use sans-serif for explanations and numbers, serif for ideas, monospace for procedural markings. Do not let the small labels become the dominant voice.
- Bold italic emphasis is a companion serif cut, not a slanted sans-serif. Keep it inside the same baseline and size as the surrounding headline.
- The default display is 64px/74px; the company opening uses a slightly more relaxed 64px/76px and deep teal text, while the pricing opening uses its scoped 56px/68px recipe.

## Layout

**Density:** Airy sections with compact information inside cards; large pauses separate distinct narrative ideas.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small icon-to-copy and title-to-label spacing. |
| 16px | Heading-to-body spacing, bullet stacks and directory card content rhythm. |
| 24px | Opening text stacks, paired actions and standard horizontal container inset. |
| 30px | Space between collapsed FAQ rows. |
| 32px | Demonstration panel column gap and company-card grid spacing. |
| 34px | Standard feature and directory card inner padding. |
| 40px | Footer scene-to-navigation spacing and vertical directory row gaps. |
| 48px | Feature-card grid gaps and split-section breathing room. |
| 56px | Special panel vertical padding and small illustrative pauses. |
| 72px | Dark inset chapter padding. |
| 88px | Default major section vertical padding and inter-block rhythm. |
| 112px | Roomier editorial chapter padding and footer identity-to-link grouping gap. |

### Containers and grids

- **marketing-container**: max width 1300px · side padding 24px. Centered desktop stage, with 1252px available inside its side insets. Supports paired media/text columns and broad section leads.
- **opening-copy**: max width 500px. Centered text island inside surrounding illustration; headline and support share this narrow measure.
- **navigation-container**: max width 1248px · side padding 24px. Horizontal brand, category navigation and account-action row inside the full-width header.
- **reading-column**: max width 700px. Centered FAQs and dense explanatory content.
- **feature-grid**: 2 columns · gap 48px. Equal white capability cards on warm paper.
- **directory-grid** (only for integration directories): 3 columns · gap 16px. Three equal desktop columns with 40px row gaps and cards up to 400px wide.
- **pricing-grid** (only for pricing pages): 3 columns · gap 48px. Three 350px-wide plan columns centered on a warm-paper field.
- **comparison-grid** (only for pricing pages): 4 columns · gap 2px. One feature column plus three plan columns, approximately 294px each.
- **company-container** (only for company and culture content): max width 1400px · side padding 24px. Broader story and benefit layouts than the default marketing stage.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-actions | 48px |
|  | compact-actions-and-announcements | 88px |
|  | cards | 5px |
|  | dark-inset-panels | 10px |
|  | portrait-circles | 50% |
| tabbed product demonstrations | demonstration-panels-and-tabs | 8px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | announcement | `2px 2px 2px 0px rgba(14, 71, 73, 0.15)` | A small, lightly softened lift under the announcement capsule. |
| tabbed product demonstrations | demonstration-offset | `6px 6px 0px 0px #bfddd5` | Flat mint offset behind outlined product demonstration panels. |
| pricing pages | pricing-offset | `4px 4px 0px 0px #bfddd5` | Thin, crisp offset for the special subscription offer. |

### Surfaces

#### White canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Untextured and spacious; illustration can bleed into the surrounding white without an enclosing card.

**Transfer:** Let the drawing and typography define the scene rather than surrounding every block with a border.

#### Warm chapter · level 0

**Use:** Alternating capability, pricing and directory fields.

**CSS:** `background: #f8f4f2`

**Observed:** A broad full-width off-white field behind contrasting white cards.

**Transfer:** Use it to group a family of capabilities rather than tinting unrelated individual paragraphs.

#### White information card · level 1

**Use:** Feature and directory content.

**CSS:** `background: #ffffff; border-radius: 5px; padding: 34px; box-shadow: none`

**Observed:** Very small rounding, with no conspicuous elevation; text starts below a small icon.

**Transfer:** Keep the material flat and rely on a warm backing and layout gaps for separation.

#### Painted navy field · level 0

**Use:** Closing scene continuing uninterrupted behind footer navigation.

**CSS:** `background-color: #01152d; color: #ffffff; padding: 88px 0px`

**Observed:** Dark blue horizontal brush layers are softened under a 50% navy overlay. The surface is continuous rather than divided into a separate CTA card and footer.

**Transfer:** Recreate layered low-contrast painted strokes beneath dark blue; preserve enough tonal depth to feel tactile without impairing text.

#### Legal strip · level 0

**Use:** Final utility bar below the closing field.

**CSS:** `background: #021020; color: #65b8a2; min-height: 50px`

**Observed:** Compact copyright, legal links and a thin outlined cookie-settings control share a horizontal baseline.

**Transfer:** Keep this subordinate to the designed closing scene.

#### Outlined demonstration · level 1

**Only for:** tabbed product demonstrations

**Use:** Large content stage beneath workflow tabs.

**CSS:** `background: #ffffff; border: 2px solid #158d71; border-radius: 8px; box-shadow: 6px 6px 0px 0px #bfddd5; padding: 40px 32px`

**Observed:** Approximately 1000px wide, with explanatory copy at left and a product fragment at right.

**Transfer:** Use a real or simplified workflow within the frame; keep its offset shadow hard-edged.

#### Dark inset chapter · level 1

**Only for:** technical capability spotlights

**Use:** A focused technical or platform promise within a warm chapter.

**CSS:** `background-color: #01152d; color: #ffffff; border-radius: 10px; padding: 72px`

**Observed:** Painted horizontal blue texture under a 65% navy overlay, with two columns and a white compact action; the product variant uses a similarly painted dark green.

**Transfer:** Use a contained dark field to explain one connected capability rather than switching the entire page to a dark theme.

#### Berry conversion band · level 0

**Only for:** secondary-audience conversion sections

**Use:** A distinct secondary conversion route.

**CSS:** `background-color: #662344; color: #ffffff; padding: 0px 16px`

**Observed:** Darker flowing paint texture, white headline and an oversized black-and-white figure extending above and below the band.

**Transfer:** Give a genuinely different audience or use case its own chromatic chapter.

#### Benefit wash · level 1

**Only for:** company and culture content

**Use:** Small illustrated benefit cards.

**CSS:** `background: rgba(202, 225, 226, 0.25); border-radius: 5px; padding: 34px`

**Observed:** A very pale teal wash over white, arranged in an intentionally incomplete last row.

**Transfer:** Use for short human-oriented commitments or benefits.

## Components

### Fixed navigation

**Use:** Persistent site orientation and account actions.

**CSS:** `background: #ffffff; border-bottom: 1px solid #000000; height: 90px; padding: 0px 24px; position: fixed; top: 0px; width: 100%; z-index: 10`

**Text style:** `body` — sofia-pro 400 · 16px/1.5

**Observed:** A compact identity sits left, category links and small chevrons occupy the middle, and a filled primary action plus plain sign-in sit right. The content is centered in the navigation container.

**Transfer:** Use a modest identity and a few meaningful categories, keeping account actions visually separate.

### Primary button

**Use:** Default principal conversion action.

**CSS:** `background: #1c5d5f; color: #ffffff; border-radius: 48px; padding: 14px 22px 16px; height: 52px; text-align: center; transition: 0.2s`

**Text style:** `button` — sofia-pro 400 · 16px/22px

**Observed:** A short text-only pill, centered under the opening support. The closing variant fills with emerald instead of teal.

**States:** Declared: hover background-color #2a7779 and color #ffffff; focus-visible unknown; active outline 0px.

**Transfer:** Keep the label direct and the width content-driven.

### Announcement capsule

**Use:** A compact timely message centered above the opening promise.

**CSS:** `background: #f4f9f9; border: 1.5px solid #2a7779; border-radius: 88px; padding: 5px 16px 7px; box-shadow: 2px 2px 2px 0px rgba(14, 71, 73, 0.15); max-width: 1000px`

**Observed:** A single compact line combines a tiny symbol, announcement copy and an underlined destination. It floats in the white opening rather than filling the screen width.

**Transfer:** Use only when there is a real timely update; do not replicate its persistent overlay behavior.

### Feature card

**Use:** A short capability explained through an icon, title and bullets.

**CSS:** `background: #ffffff; border-radius: 5px; padding: 34px`

**Text style:** `card-heading` — p22-mackinac-pro 700 · 20px/1.3

**Observed:** A mint-and-black line icon precedes a bold serif title; body-sized bullet rows follow with small mint markers. Usually a two-column grid on warm paper.

**Transfer:** Use three concise evidence-bearing bullet points rather than a large decorative illustration inside every card.

### FAQ row

**Use:** Compact objection handling.

**CSS:** `background: #edf5f3; border-radius: 5px; padding: 16px 24px; display: flex; align-items: center; min-height: 62px; max-width: 700px`

**Text style:** `body-bold` — sofia-pro 700 · 16px/1.5

**Observed:** A 30px mint circle with a fine plus sign sits left, followed by a bold question. Rows are separated by 30px; answers use normal body copy below the question surface.

**Transfer:** Keep question widths controlled and disclose answers in place.

### Footer link group

**Use:** Navigation beneath the closing conversion scene.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; color: #ffffff`

**Text style:** `footer-link` — sofia-pro 400 · 13px/19px

**Observed:** Mint uppercase monospace heading above white links with 8px top and bottom padding. Four link groups sit beside a small reversed identity; the last also holds comparison links.

**Transfer:** Group destinations by visitor intent; preserve generous column separation and compact link typography.

### Compact action

**Only for:** product-detail and pricing pages

**Use:** Smaller action within split heroes and supporting panels.

**CSS:** `background: #156152; color: #ffffff; border-radius: 88px; padding: 12px 22px 14px; height: 46px; transition: 0.2s`

**Text style:** `compact-action` — sofia-pro 500 · 14px/20px

**Observed:** Paired with a simple underlined text action; dark panels can use a white filled version.

**States:** Declared: hover background-color #177863 and color white; focus-visible unknown; active outline 0px.

### Outlined plan action

**Only for:** pricing pages

**Use:** Consistent plan conversion across pricing columns.

**CSS:** `background: transparent; color: #0d4a3e; border: 2px solid #156152; border-radius: 88px; padding: 12px 22px 14px; height: 50px; transition: 0.2s`

**Text style:** `compact-action` — sofia-pro 500 · 14px/20px

**Observed:** Centered below price and session selectors. Plans share the outlined construction rather than using an exaggerated featured-plan card.

**States:** Declared: hover background-color #156152 and color white; focus-visible unknown; active outline 0px.

### Workflow tab

**Only for:** tabbed product demonstrations

**Use:** Selecting a step in a multi-stage workflow.

**CSS:** `border: 1.5px solid #3ea388; border-radius: 8px; padding: 9px 30px; display: flex; align-items: center; gap: 8px; color: #222222`

**Text style:** `product-tab` — IBM Plex Mono 500 · 11px/20px · tracking 0.091em · uppercase

**Observed:** An 18px pictogram sits before a short uppercase monospace label. Selected tabs add a pale mint fill and a 3px mint ring; the row sits above Outlined demonstration.

**States:** Declared: hover color #000000; focus-visible unknown; active outline 0px.

**Transfer:** Use for a small set of real workflow stages, not as navigation for every section.

### Directory card

**Only for:** integration directories

**Use:** A consistent description of each connected tool.

**CSS:** `background: #ffffff; border-radius: 5px; padding: 34px; display: flex; flex-direction: column; align-items: flex-start; gap: 16px; max-width: 400px`

**Text style:** `body` — sofia-pro 400 · 16px/1.5

**Observed:** Order is 38px logo, bold serif name, pastel category pills, compact description and bold underlined destination. An ending invitation card substitutes a dashed outline.

**Transfer:** Keep category meaning stable across the filter row and all cards.

### Category pill

**Only for:** integration directories

**Use:** Tool categories and matching directory filters.

**CSS:** `background: #f0cfe0; border-radius: 100px; padding: 2px 8px 4px`

**Text style:** `category` — sofia-pro 600 · 10px/18px · tracking 0.05em · uppercase

**Observed:** Tiny uppercase dark text on pink, lilac, mint, blue or yellow according to category. Several pills form a close row beneath the tool name.

**Transfer:** Assign semantic category colors, not random decorative variations.

### Plan card

**Only for:** pricing pages

**Use:** Present one purchase model.

**CSS:** `background: #ffffff; border-radius: 5px; padding: 24px 16px; max-width: 350px; display: flex; flex-direction: column; align-items: center`

**Text style:** `card-heading` — p22-mackinac-pro 700 · 20px/1.3

**Observed:** Small monospace product label, bold serif plan name, short audience description, large sans price, compact billing note, selectors, outlined action and feature list. Small green savings ribbons sit near the top edge.

**Transfer:** Align equivalent content and controls across plans; use genuine pricing differences rather than oversized decorative badges.

## Imagery and graphics

### Human line-art surround

**Use:** Signature opening graphic and smaller connective accents throughout the page.

**Observed:** Black hand-drawn people appear in loose browser windows around the central message. Sweeping tapered paths curl between windows, tiny real portrait circles, folders, arrows, stars and small mint or dusty pink marks. Most of the graphic remains white; color fills only a few details.

**Transfer:** Illustrate the people and artifacts relevant to the new product around an open central text island. The minimum version is two simple character busts in browser frames, a few circular real portraits and one flowing connector path.

**Build:** Use a 1300px-wide SVG stage with an open center about 500px wide. Place irregular outlined browser rectangles at upper left, lower left and lower right; use near-black paths around 2–4px thick with rounded ends and uneven curves. Draw broad looping cubic paths around the margins and below the action, interspersed with sparse 4–6-ray stars in mint and muted pink. Clip a few supplied portraits into 40–70px circles with dark outlines. Keep people monochrome with one mint accent and never run a high-contrast line behind text.

### Pastel product stages

**Use:** Core product demonstration and product-family comparison.

**Observed:** White interface fragments sit on large very pale mint and blue rectangles. Small portrait discs overlap the interface edge; illustrated sparkle bursts and occasional doodles soften the software. Interface content occupies more of each panel than the label beneath it, but remains one legible focused task.

**Transfer:** Use authentic UI selectively: show one useful operation rather than an entire dashboard. If no UI exists, draw a credible task card with fields, choices and a result; back it with a pale solid stage and overlap one relevant human or object detail.

**Build:** Make two equal pale rectangular stages inside the main container. Center a white task card in each with restrained edging and a very soft local shadow. Overlap up to three circular portraits along one edge. Add one black outlined starburst or curved path outside the card; place a compact identity and descriptor beneath. Keep the backing low contrast and avoid colored dashboard chrome.

### Painted chapter textures

**Use:** Tactile dark endings, technical spotlights and contrasting conversion bands.

**Observed:** Wide horizontal brush strokes in related dark blue tones create depth under the ending. The technical panel has more visibly layered navy strokes; the secondary band uses berry paint, and a special pricing offer uses pale warm paper texture with a mint brush underline.

**Transfer:** Create restrained painterly tonal layers rather than a glossy mesh gradient. The minimum acceptable version is a dark solid field with a few broad, subtly irregular translucent strokes.

**Build:** Layer 8–12 SVG horizontal brush polygons with ragged short edges at different heights, using white at 2–6% alpha and black at 5–12% alpha over navy. Add fine turbulence clipped inside the strokes for pigment variation. Cover the closing version with rgba(1,25,54,0.5); use rgba(1,21,45,0.65) over the technical panel. Keep the contrast low behind text; use equivalent berry-on-berry layers for the secondary band.

### Closing comet

**Use:** Signature line-art counterweight to the closing conversion message.

**Observed:** A small circular people symbol sits inside a tilted loop, trailing multiple white tapered curves and jagged speed strokes down-left. Sparse mint and pink stars and dots punctuate the scene. The composition occupies a 440px × 375px area to the right of the copy.

**Transfer:** Use the new product's own simple meaningful symbol inside the loop, not a large logo pasted into a stock rocket. The minimum is a rounded motif enclosed by two open elliptical arcs and a few hand-drawn speed lines.

**Build:** Within a 440px × 375px SVG, draw two open elongated ellipses tilted about 40 degrees upward to the right using white 2–3px strokes. Extend their lower-left ends into tapered zigzag trails. Put a small product-relevant emblem near the upper-right center; scatter six small asterisks and dots in mint, white and muted pink outside the trails.

### Annotated proof collage

**Use:** Testimonials and compact quantified credibility.

**Observed:** A two-column field of pale teal quote tiles is interrupted by one deep teal highlighted quote. Bold phrases sit within otherwise regular sans copy; small circular author portraits and tiny review marks sit below. A pale irregular loop wanders behind the tiles, with a pin and trophy doodle at the highlighted card.

**Transfer:** Use real attributable proof and one visually dominant quote. Without ratings or badges, use a small portrait, role and plain attribution while preserving the tile contrast and hand-drawn annotation.

**Build:** Place a pale warm-gray SVG loop behind a two-column grid. Keep three cards very pale teal and one dark teal with white type; add a small outlined pin at its upper-left edge and a simple trophy outline at lower right. Use compact circular portraits beneath text. The loop must remain low contrast and never act as a heavy card border.

### Portrait story collages

**Only for:** company and culture content

**Use:** People-first editorial opening, testimonials and team profiles.

**Observed:** A wide group photograph is clipped into a slanted ribbon with softly rounded ends. Other story blocks use circular natural-light photos, dotted mint fields, soft organic beige or teal shapes and dashed wandering connectors. Leadership portraits are uniform 175px circles with dark outlines and centered names and roles.

**Transfer:** Use unpolished but well-lit real people rather than uniform studio stock. Retain circular framing and a small amount of tactile illustration; reserve the wide group ribbon for a genuine collective image.

**Build:** Clip the group image to a wide parallelogram with softened corners. For story portraits, use a circular mask over an off-center pale organic blob and a mint dot grid of 3–4px dots spaced about 12px apart. Join separate circular photos with a faint dashed curved SVG path.

### Icons

**Observed:** Marketing pictograms are playful black line drawings with mint fills or accents, often deliberately irregular rather than a uniform app-icon library. Feature icons sit around 38–44px; workflow controls use 18px icons, while checks, information dots and comparison marks remain tiny at about 10–14px.

**Transfer:** Choose simple recognizable objects with black outlines and restrained mint accents. Use tiny utility icons for dense facts and larger illustrated icons only at card or section starts.

## Section recipes

How recurring sections are built.

### First screen: Illustrated text-island opening

**Observed:** A 90px fixed white navigation bar with a black bottom rule tops a white 807px hero. Beneath the header, a centered announcement capsule sits above the promise. The headline uses display in a 500px-wide centered island, breaking across three balanced lines; the 24px/32px support follows after 24px and the Primary button after 30px. A 1284px × 725px Human line-art surround spans almost the full 1300px stage behind and around the copy: people in browser frames occupy the side margins and lower corners, loops sweep underneath, and portrait circles sit beside the right-hand drawing. Back-to-front layers are white canvas, pale accent paths, black illustration and portraits, then the clear central text/action stack. Within the first 900px, the whole promise, support, action and the principal illustrated scene are visible; the following proof section begins below the fold.

**Transfer:** For a different product, preserve the open central text island and make a people-and-artifact surround relevant to its promise. Use the minimum SVG recipe when bespoke art is unavailable. Product-detail pages instead use a left-aligned 64px headline and right-hand illustration around 500px wide; pricing uses pricing-display beside a product fragment, directories use a split illustration hero, and company storytelling opens with a centered title above a wide group-photo ribbon.

**Avoid:** Do not replace the surrounding scene with a giant centered dashboard, put the headline on a saturated gradient, or allow decorative paths to cross the text island.

**Text style:** `display` — p22-mackinac-pro 400 · 64px/74px

### Capability heading pair

**Observed:** A short emerald monospace eyebrow precedes a centered heading by 16px. A brief body-sized support line follows by 16px, with controls or media below after roughly 32–48px. The chapter has 88px vertical padding on White canvas or Warm chapter.

**Transfer:** Name the capability in the headline, explain the result in one sentence, then demonstrate it rather than adding a second paragraph of general claims.

**Text style:** `heading` — p22-mackinac-pro 400 · 50px/1.2

### Paired product stages

**Observed:** A centered serif lead and short support line introduce two adjacent pale product stages. Each stage holds a focused white interface fragment, portrait or sparkle overlaps, a compact descriptor and its own conversion action. A narrow annotated facts strip sits beneath the pair.

**Transfer:** Use paired stages for two genuinely complementary routes or modes. Reduce the UI to one useful operation per route and summarize measurable differences beneath.

### Process with ruled rows

**Observed:** A left-hand 50px serif title, uppercase 20px monospace label and small line drawing face a broad right-hand stack of process rows. Thin black horizontal rules separate steps; each step has an icon, ordinal, short benefit and smaller supporting detail.

**Transfer:** Use for a real short sequence. Keep each step actionable and let the rules, not cards or timeline dots, establish order.

### Annotated testimonial field

**Observed:** A left-aligned serif heading shares the top with compact external proof emblems. Annotated proof collage fills the width below: two columns, pale tiles, a single dark teal lead tile, selective bold phrases and portraits. A low-contrast looping line sits behind the grid.

**Transfer:** Present a few specific outcomes with attribution, using one strong proof tile to create hierarchy instead of making all quotes equally loud.

### Comet close and continuous footer

**Observed:** Painted navy field is about 1054px tall with 88px vertical padding. The upper row pairs a white 50px/60px serif headline in a 500px measure at left and Closing comet at right. A bold italic final word supplies the punch. Primary button in emerald and an underlined secondary action sit 24px below. After 40px, a small reversed identity sits beside four Footer link groups with mint monospace labels and white 13px/19px links. The same paint continues behind both regions. Legal strip finishes below as a distinct 50px bar.

**Transfer:** End with a conversational, immediate promise and one emphatic word; redraw the comet around an original symbol. Carry the dark painted material through the navigation and make the final legal bar visibly quieter.

**Text style:** `heading` — p22-mackinac-pro 400 · 50px/1.2

### Tabbed demonstration chapter

**Only for:** product-detail pages

**Observed:** Capability heading pair above Workflow tab, then Outlined demonstration. Copy and product imagery split the stage; a testimonial beneath uses selected phrases highlighted with mint bands. A second audience-oriented chapter uses the same panel grammar with factual lists opposite a deeper UI fragment.

**Transfer:** Explain one meaningful stage at a time and keep tab labels short. Maintain a stable demonstration frame as the content changes.

### Secondary conversion band

**Only for:** secondary-audience conversion sections

**Observed:** Berry conversion band carries a 44px/58px white serif question at right, a short support line with an underlined proof number and an outlined pill beneath. A 387px × 482px illustrated person overflows the 386px band at left.

**Transfer:** Use this distinct visual route to address a secondary audience or alternative participation model; substitute an equally simple celebratory human illustration.

**Text style:** `band-heading` — p22-mackinac-pro 400 · 44px/58px

### Commercial comparison

**Only for:** pricing pages

**Observed:** A split pricing hero leads into product tabs and three Plan cards on Warm chapter. A thin outlined, flat-shadowed subscription panel follows, with two columns, warm painted paper and a mint brush underline. A four-column comparison matrix uses warm-paper cells, narrow white gutters and stone category bars. A dark painted add-on panel and a 700px-wide FAQ column deepen the explanation before the shared ending.

**Transfer:** Let the initial plan summary aid choice, then provide detailed comparison for readers who need it. Keep numeric prices and billing notes aligned; use texture and annotation sparingly rather than turning pricing into a dashboard.

### Filterable ecosystem

**Only for:** integration directories

**Observed:** A split illustrated opening is followed by a warm-paper directory with a left-aligned 50px heading, a 20px support line, category filters and a three-column Directory card grid. A dashed invitation card closes the grid. Dark inset chapter introduces a technical extension; three pale service cards sit on white before the shared ending.

**Transfer:** Make the directory useful for scanning: recognizable tool symbols, stable category colors, brief descriptions and a clear destination per item.

### Human editorial chapters

**Only for:** company and culture content

**Observed:** Wide group-photo ribbon, alternating image-and-story blocks, a five-number teal band with gently irregular edges, large serif testimonial quotations, and a warm-paper portrait grid. Story portraits use organic backings and dotted fields. A dark team spotlight and a three-column Benefit wash grid precede the shared ending.

**Transfer:** Tell an origin, show people and working principles through real examples, then offer a focused next action. Adapt the graphic devices to the subject rather than requiring a team directory.

## Page flow

**Storyline:** Human promise → useful product explanation → specific proof and capability depth → objections or next-step resources → illustrated conversion scene and grouped navigation.

### Broad marketing landing page that connects a promise to complementary product routes

1. **Promise** — Centered text island inside a lively hand-drawn human surround.
2. **Social proof** — Compact editorial lead and a wide logo strip on a subtly textured backing.
3. **Product explanation** — Two pale product stages with focused interface fragments and an annotated facts strip.
4. **Process** — Split introduction and thin-ruled step rows.
5. **Alternative conversion** — Contrasting berry band with overflowing line-art figure.
6. **Outcome proof** — Annotated testimonial field with one dark lead tile.
7. **Closing call and navigation** — Navy painted comet scene, grouped footer links and separate dark legal strip.

**Transfer:** Use the same shifts in narrative scale while choosing product routes and proof relevant to the new offering.

### Deep product-detail page that explains a workflow and builds confidence

1. **Promise** — Left promise and checklist beside illustrated matching workflow, with compact facts below.
2. **Social proof** — Dark green logo band.
3. **Demonstration** — Workflow tabs, outlined flat-shadow stage and highlighted quotation.
4. **Capability depth** — Audience-oriented stage followed by a two-by-two feature grid.
5. **Conversion checkpoint** — Inset painted green callout overlapping the chapter boundary.
6. **Objection handling** — Narrow mint FAQ rows.
7. **Resources** — Three illustrated editorial resource cards on warm paper.
8. **Closing call and navigation** — Shared painted navy comet scene, footer groups and legal strip.

**Transfer:** Balance interaction, explanation and proof; use the overlapping conversion card as a checkpoint rather than replacing the final scene.

### Pricing page that supports both quick selection and detailed evaluation

1. **Promise** — Compact split hero with eyebrow and product illustration.
2. **Purchase choices** — Product tabs, three plan cards, session controls and small savings ribbons.
3. **Value explanation** — Warm painted subscription panel with flat mint offset and brush underline.
4. **Detailed comparison** — Four-column matrix separated by stone category bars.
5. **Expansion options** — Dark painted add-on panel with white type and illustration.
6. **Objection handling** — Tabbed FAQ categories and mint question rows.
7. **Closing call and navigation** — Shared painted navy comet scene, footer groups and legal strip.

**Transfer:** Keep commercial detail easy to compare and retain the expressive serif, paint and line-art language around the dense matrix.

### Ecosystem page for discovering compatible tools and technical extension points

1. **Promise** — Split headline and human workflow illustration with a pale vertical-rule callout.
2. **Discovery** — Warm chapter with category pills and a three-column directory.
3. **Contribution invitation** — Dashed-outline card offers a way to request or add a connection.
4. **Technical depth** — Painted navy inset panel with two explanatory columns.
5. **Supporting capability** — Three pale service cards on white.
6. **Closing call and navigation** — Shared painted navy comet scene, footer groups and legal strip.

**Transfer:** Treat scanning and filtering as the main task, then place technical depth in a visually distinct inset chapter.

### Company story that communicates human character and working principles

1. **Identity promise** — Centered serif title above a slanted group-photo ribbon and short mission paragraph.
2. **Origin story** — Founder portrait collage beside editorial copy and supporting logos.
3. **Quantified proof** — Teal full-width strip with five large sans numbers and small captions.
4. **Human proof** — Alternating portrait-and-quote blocks with organic and dotted backings.
5. **People** — Warm-paper circular portrait grid with compact names and roles.
6. **Working principles** — Dark illustrated spotlight, editorial culture story and pale benefit cards.
7. **Closing call and navigation** — Shared painted navy comet scene, footer groups and legal strip.

**Transfer:** Translate the photo treatment, quotation hierarchy and benefit material into a real human story without requiring the same organizational sections.

## Writing

Warm, capable and unusually human for operational software. Benefits are concrete and fast-moving; confidence is softened by conversational asides, small jokes and plain explanations rather than grandiose category language.

**Do not copy:** Do not reuse the brand names, logos, character artwork, customer identities, attributed quotations, proprietary product names, participant counts, earnings, conversion claims, pricing or performance statistics. Supply original assets and substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader directly as you and your team. Use we for human commitments and product beliefs, and name the product only where it clarifies an action or capability.
- **Rhythm:** Most headlines are a compact phrase or a direct question; support usually starts with one plain sentence. Short imperative actions contrast with longer explanatory bullets. Conversational fragments and parenthetical asides are welcome in human stories, while commercial detail stays literal.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | State the useful connection or outcome in ordinary language, with an optional speed cue. | 4–8 words | “We connect researchers and participants”<br>“Recruit qualified research participants, fast” |
| Supporting line | Expand the benefit with an action and a concrete way to participate. | 12–20 words | “Get fast access to quality participants or earn money by participating in studies” |
| Capability heading | Active verb plus a specific capability or audience. | 4–9 words | “Target just about any niche”<br>“Connect to all your favorite apps” |
| Primary action | Simple verb phrase; emphasize low-friction entry or a clear human conversation. | 2–4 words | “Sign up free”<br>“Schedule your demo” |
| Closing line | Immediate invitation followed by a short conversational reinforcement and one emphasized word. | 8–12 words | “Talk to users today. Seriously, we're fast.” |
| Human story | Specific, candid description with a gentle self-aware aside. | One or two short paragraphs | “We care, we work hard, we’re customer obsessed (but not in a weird way), curious, maybe a little quirky?” |

**Words and phrasing to use:** fast; quality; your team; connect; build; flexible; simple; just about; Seriously.; built-in

**Avoid:** revolutionary paradigm; unlock limitless potential; synergistic; best-in-class everything; robotic enterprise jargon; forced whimsy in pricing terms

**Rules:**

- Lead with a useful action or result before naming mechanisms.
- Place concrete facts beside claims, and use bold within a sentence only for the phrase that carries the proof.
- Keep procedural labels short enough to read as markings, not miniature headlines.
- Use questions to resolve genuine buyer concerns.
- Save the loosest language and parenthetical jokes for human stories; keep billing, permissions and technical constraints unambiguous.

## Do's and Don'ts

### Do

- Keep the main serif promise at weight 400 with normal tracking and 74px line height at 64px.
- Use a 500px centered copy island and protect it from the surrounding illustration.
- Separate major ideas with 88px vertical padding while keeping card copy on a 16px internal rhythm.
- Make default actions 52px tall and text-driven, with 48px rounded ends.
- Stage software on pale mint or blue backings with small portrait and doodle overlaps.
- Use 5px corners for ordinary cards and reserve outlined, hard-shadowed panels for demonstrations.
- Carry painted navy continuously from the closing conversion scene through grouped footer navigation.
- Keep procedural labels in uppercase IBM Plex Mono and let the serif remain the dominant voice.

### Don't

- Do not tighten the serif into a compressed technology headline or replace its regular weight with a heavy grotesk.
- Do not spread saturated berry, mint and navy equally across the page; most content sits on white or warm paper.
- Do not round every information panel into a 24px-radius floating tile; the default is 5px.
- Do not add blurred floating shadows to all marketing cards; the characteristic demonstration shadow is a flat 6px mint offset.
- Do not turn tiny category labels into large colorful badges; directory pills use 10px type and 24px total height.
- Do not set ordinary explanations in monospace; reserve it for procedural labels and compact facts.
- Do not use neon glows, glass panels or glossy three-dimensional mascots in place of brush texture and black line art.
- Do not enlarge footer links to body headline scale; the grouped navigation uses 13px/19px text.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s transitions, including teal and emerald hover color changes. A smaller set of elements declares 0.3s transitions.
- Some section content uses opacity during scroll entrance, but the readable design resolves to full opacity.

**Transfer:**

- Use the declared short action transition to make teal-to-sea-teal or emerald-to-brighter-emerald changes feel responsive.
- Keep completed line drawings and readable text present in the settled state; do not treat faded intermediate content as a material treatment.

**Unknown:**

- Exact scroll entrance timing and easing per section, looping behavior and focus-visible styling are not established.

### Responsive

**Observed:**

- Width breakpoints are declared at 376px, 400px, 479px, 767px, 768px, 991px and 1200px.

**Transfer:**

- As a design adaptation, collapse paired product stages and split chapters to one column while retaining the serif-first hierarchy.
- On narrow screens, redraw or simplify the line-art surround so the central promise stays clear; move the comet below the closing copy rather than shrinking its strokes into noise.
- Keep pricing matrices horizontally usable and category pills wrap-capable rather than reducing all text to fit.

**Unknown:**

- Exact mobile typography, navigation transformation, section spacing and artwork visibility rules are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
