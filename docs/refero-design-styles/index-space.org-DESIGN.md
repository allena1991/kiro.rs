# Index Space — the social noticeboard

## Overview

An unpolished-in-the-best-way editorial style that feels like a useful community noticeboard rather than a sales funnel. A light canvas, black grotesk text, fine outlines and tiny utilitarian controls make room for warm, lived-in documentary photography. Pale yellow and mint punctuate the white default, with sky blue and light gray defining more immersive page variants. It suits participatory products, creative services and membership offerings, pairing sparse page composition with information-rich cards and lists.

### Essentials

- The photograph makes the opening argument: a square-cornered 1180×598px scene leads, followed by a modest 24px/1.3 regular headline in a 580px column, not an oversized slogan.
- Controls look like printed labels: 16px/1.3 text with 0.01em tracking, 1px black outlines and 2px 5px padding produce roughly 27px-high buttons; dashed outlines distinguish invitation-like actions.
- The page behaves like a spaced-out noticeboard: 160px between chapters, 20px gutters, 460px outlined square cards and a centered 940px main reading grid.
- Color is a paper stock, not decoration: white is the default canvas; one pale-yellow 1180px-wide notice and mint-backed editorial thumbnails punctuate a mostly neutral page. Continuous sky blue and gray belong to dedicated variants.
- Human proof stays materially plain: daylight interiors, people actually using things and occasional direct-flash gatherings fill unrounded rectangles; use a real working context or photographed tools when there is no physical venue.
- A pinned invitation and a browsing shelf are signature devices: center a 16px uppercase label and small action in a yellow panel with two 12px black side dots, and expose neighboring items in a horizontal rail with 20px gaps. Adapt their content and placement to the new story.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lemon paper | `#ffffa5` | `--color-notice` | surface, accent | A concentrated invitation notice rather than a recurring section background. |
| Mint backing | `#9ee6c4` | `--color-editorial` | surface | Backing for editorial resource images, mostly covered by artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-canvas` | background, surface | Default page canvas, navigation label backing and photo-overlay pagination. |
| Secondary gray | `#666666` | `--color-muted` | text, border | Secondary copy and list dividers use black at 60% opacity, appearing gray on white; let the same alpha adapt to tinted canvases. |
| Black ink | `#000000` | `--color-ink` | text, border, accent | All primary text, outlines, rules and tiny graphic markers. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| offering directories and detailed membership pages | Sky paper | `#98ccee` | `--color-blue` | background, surface | Continuous canvas, including controls and footer. |
| organization and culture pages | Gray paper | `#e5e4e4` | `--color-gray` | background, surface | Continuous editorial canvas, including navigation and footer. |
| availability and membership information | Live green | `#00ff00` | `--color-available` | accent | Tiny availability dots paired with capacity text, never a promotional fill. |

## Typography

- **kmrWaldenburg** — All headings, paragraphs, captions, labels and controls. Matter-of-fact grotesk with open, readable lowercase forms and little weight contrast. If unavailable, use **Inter**. Use regular 400 throughout; retain positive 0.01em tracking and the restrained size range. Font stack: "kmrWaldenburg", "Inter", Helvetica, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| heading | kmrWaldenburg | 400 | 32px | 1.3 | 0.01em | Card titles, short section statements and detail-page titles; larger than the main opening statement without becoming a display face. |
| lead | kmrWaldenburg | 400 | 24px | 1.3 | 0.01em | Default opening statement, editorial introductions and centered full-width expansion actions. |
| body-large | kmrWaldenburg | 400 | 20px | 1.3 | 0.01em | Testimonial paragraphs, listing titles and detail-page explanatory copy. |
| body | kmrWaldenburg | 400 | 16px | 1.3 | 0.01em | Standard paragraphs, actions, metadata, prices and footer links. |
| notice-label | kmrWaldenburg | 400 | 16px | 1.3 | 0.01em, uppercase | Centered label on the yellow invitation notice. |

**Notes:**

- Size, whitespace and position carry hierarchy; regular weight is the rule rather than bold headlines.
- All core text keeps 0.01em positive tracking and 1.3 line height. Do not tighten large headings or turn metadata into widely tracked microtype.
- Resource captions are an exceptionally small 13px treatment, used beneath images rather than as a general body size.

## Layout

**Density:** Airy between sections and compact inside information blocks; large chapter gaps coexist with tiny label-sized actions.

### Spacing

**Spacing system:**

- **rhythm** 10px, vertical — Base vertical rhythm for gaps and padding.
- **gutter** 20px, horizontal — Main grid spacing and card inset.

| Value | Use |
| --- | --- |
| 2px | Button vertical padding and tightly joined filter controls. |
| 5px | Button horizontal padding, small inline gaps and resource-caption separation. |
| 10px | Title-to-copy gaps and small grouped labels. |
| 20px | Grid gutters, standard card padding and photo-to-hero-copy spacing. |
| 30px | Membership-card padding and footer vertical padding. |
| 40px | Generous panel padding, image-to-editorial-copy gaps and spacing before expansion actions. |
| 60px | Separation between membership summary and feature rows. |
| 80px | Long-form statement separation after a detail photograph. |
| 125px | Document start below the fixed navigation. |
| 160px | Major section separation and breathing room before the footer. |

### Containers and grids

- **page-grid**: 12 columns · gap 20px · side padding 10px. Full-width underlying grid; centered subsets create several nested widths rather than one uniform container.
- **main-content**: max width 940px · gap 20px. Centered eight-column region at a 1440px viewport for lists, photo sections and paired cards.
- **wide-stage**: max width 1180px · gap 20px. Ten-column opening photograph, yellow notice and closing related cards.
- **reading-column**: max width 700px. Inset editorial statements; opening copy instead uses 580px aligned with the photograph's left edge.
- **paired-cards**: 2 columns · gap 20px. Two 460px columns in the main region; full-width companion card can sit beneath them.
- **resource-shelf**: max width 700px · 3 columns · gap 20px. Three 220px square editorial images with captions; 30px between rows.
- **compact-gallery** (only for offering directories): max width 940px · 4 columns · gap 20px. Four square images with centered two-line captions.

## Corner radius

| Element | Radius |
| --- | --- |
| rectangular-content | 0px |
| pagination-dots | 5px |
| circular-controls | 50% |

## Surfaces and depth

### Surfaces

#### Paper canvas · level 0

**Use:** Default page and footer background.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Flat, untextured and without raised cards or shadows.

**Transfer:** Let whitespace, rules and photography provide depth.

#### Outlined paper · level 1

**Use:** Cards and full-width actions.

**CSS:** `background: transparent; border: 1px solid #000000; border-radius: 0px; box-shadow: none`

**Observed:** The surrounding canvas shows through the card; it is a boundary rather than an elevated tile.

**Transfer:** Keep every content panel visually on the same sheet.

#### Lemon notice · level 1

**Use:** The pinned invitation panel.

**CSS:** `background: #ffffa5; border: 1px solid #000000; padding: 40px; text-align: center`

**Observed:** Two black side markers make it feel pinned; copy occupies only the central portion.

**Transfer:** Use for an open invitation or participation prompt, not a repeated feature-card fill.

#### Sky canvas · level 0

**Only for:** offering directories and detailed membership pages

**Use:** An immersive alternate page stock.

**CSS:** `background: #98ccee; color: #000000`

**Observed:** Persists behind photos, testimonials, cards and the ending.

**Transfer:** Choose it for a whole page rather than alternating blue and white bands.

#### Gray canvas · level 0

**Only for:** organization and culture pages

**Use:** Editorial alternate page stock.

**CSS:** `background: #e5e4e4; color: #000000`

**Observed:** Persists through introductory imagery, principle labels, listings and footer.

**Transfer:** Use one continuous neutral field for a long institutional story.

## Components

### Fixed navigation

**Use:** Persistent, small-scale wayfinding.

**CSS:** `position: fixed; top: 0px; height: 65px; z-index: 50; background: transparent`

**Text style:** `body` — kmrWaldenburg 400 · 16px/1.3 · tracking 0.01em

**Observed:** A centered 940px region carries an outlined brand label and a 25px circular ellipsis menu at left, with two outlined actions at right. Labels sit 20px from the top. Context pages add a small current-section label between the groups; there is no broad filled navbar.

**Transfer:** Use a short text brand label and a minimal menu, retaining the contrast between tiny controls and large media.

### Outline button

**Use:** Primary and secondary actions share one modest treatment.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; padding: 2px 5px; border: 1px solid #000000; border-radius: 0px; background: transparent; color: #000000`

**Text style:** `body` — kmrWaldenburg 400 · 16px/1.3 · tracking 0.01em

**Observed:** Content-sized, approximately 27px high. Adjacent actions sometimes share an edge; separated hero actions use a 5px gap. No oversized filled primary variant.

**States:** Declared: hover background-color #0000000f and no underline; focus-visible outline-style none with zero box-shadow.

**Transfer:** Keep text labels short and communicate importance by placement rather than button mass.

### Dashed button

**Use:** Invitation-like or contextual actions.

**CSS:** `display: inline-flex; padding: 2px 5px; border: 1px dashed #000000; border-radius: 0px; color: #000000; background: transparent`

**Text style:** `body` — kmrWaldenburg 400 · 16px/1.3 · tracking 0.01em

**Observed:** Matches the solid outline action's size and baseline, changing only the boundary language.

**States:** Declared: hover background-color #0000000f and no underline; focus-visible outline-style none with zero box-shadow.

### Information card

**Use:** Compare offerings and link to deeper content.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; padding: 20px; border: 1px solid #000000; min-height: 460px; border-radius: 0px`

**Text style:** `heading` — kmrWaldenburg 400 · 32px/1.3 · tracking 0.01em

**Observed:** Title, practical metadata and body copy cluster at the top; short actions anchor the bottom. A wide companion card can span both columns. Closing related cards are 580px wide, use 40px padding and a shorter 242px overall form.

**Transfer:** Keep the empty interior space intentional, with action alignment independent of paragraph length.

### Testimonial card

**Use:** A horizontal human-proof shelf.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 20px; border: 1px dashed #000000; width: 460px; min-height: 460px; border-radius: 0px`

**Text style:** `body-large` — kmrWaldenburg 400 · 20px/1.3 · tracking 0.01em

**Observed:** Long first-person prose at top, small muted attribution at bottom. Neighboring cards remain partly visible beyond the centered content region; the shelf label sits below at left and PREV/NEXT controls at right.

**Transfer:** Use concrete, conversational accounts rather than short praise slogans.

### Editorial list row

**Use:** Dated updates, learning resources or public activity.

**CSS:** `position: relative; border-bottom: 1px solid rgba(0, 0, 0, 0.6)`

**Text style:** `body-large` — kmrWaldenburg 400 · 20px/1.3 · tracking 0.01em

**Observed:** A 940px row uses 20px vertical insets, a flexible title-and-metadata column, 20px horizontal gap and a 135px square image at right. Typical total height is 176px. Title and date sit above host and location metadata. Category links and a small bordered GRID/LIST switch share the ruled top bar.

**States:** Declared: hover underlines the row title and text links.

**Transfer:** Retain the title/date/credit hierarchy even when listing other kinds of activity.

### Expansion panel

**Use:** Continue browsing after a compact list.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 100%; padding: 40px; border: 1px solid #000000`

**Text style:** `lead` — kmrWaldenburg 400 · 24px/1.3 · tracking 0.01em

**Observed:** A full-width outlined action follows the list after 40px, measuring 113px tall at desktop.

**States:** Declared: hover underlines the label.

### Pinned invitation

**Use:** A distinctive open invitation within a mostly neutral page.

**CSS:** `position: relative; background: #ffffa5; border: 1px solid #000000; padding: 40px; text-align: center`

**Text style:** `notice-label` — kmrWaldenburg 400 · 16px/1.3 · tracking 0.01em · uppercase

**Observed:** Uppercase label above a centered 16px support paragraph, then an Outline button separated by 20px. Two 12px black circles flank the copy at the vertical midpoint. At desktop the panel is 1180px wide and 222px high, with a roughly 650px copy block.

**Transfer:** Keep its open, participatory tone even when the action concerns another product.

### Resource tile

**Use:** A compact editorial browsing grid.

**CSS:** `width: 220px; height: 220px; background: #9ee6c4; border: 1px solid #000000; overflow: hidden`

**Observed:** Square artwork above small 13px captions, arranged three across. A 220px outlined circle replaces the last image as the browse-all action, with centered 20px text.

**Transfer:** Use covers, useful artifacts or illustrations that genuinely belong to the new content; retain the circular terminal tile.

### Compact footer

**Use:** The quiet final navigation on every page type.

**CSS:** `border-top: 1px solid #000000; padding: 30px 10px; background: transparent`

**Text style:** `body` — kmrWaldenburg 400 · 16px/1.3 · tracking 0.01em

**Observed:** A full-viewport top rule, then a centered compact wrap of navigation links, a second line of legal/contact/social links and a muted copyright line 10px below. Total desktop height is 143px. It inherits the page's paper color.

**Transfer:** End with a useful index, not a giant slogan or a dark conversion block.

### Membership card

**Only for:** pricing and capacity-based offerings

**Use:** Explain plans without a dominant recommended tier.

**CSS:** `display: flex; flex-direction: column; gap: 60px; padding: 30px; border: 1px solid #000000; border-radius: 0px`

**Text style:** `heading` — kmrWaldenburg 400 · 32px/1.3 · tracking 0.01em

**Observed:** Two-column grid: 32px plan name, muted 16px price and description, a green availability dot with a remaining-capacity sentence, then feature rows divided by 1px black top rules. All tiers share the same canvas; an odd final tier remains in the left column.

**Transfer:** Use honest availability only where meaningful; avoid manufactured urgency.

### Principle labels

**Only for:** organization and culture pages

**Use:** A compact row of named commitments.

**CSS:** `display: inline-flex; padding: 10px; border: 1px dashed #000000; border-radius: 0px`

**Text style:** `lead` — kmrWaldenburg 400 · 24px/1.3 · tracking 0.01em

**Observed:** Centered wrapping row of labels with 10px gaps, like perforated paper slips rather than pills.

**Transfer:** Name short, concrete operating principles instead of generic benefits.

## Imagery and graphics

### Lived-in documentary scene

**Use:** Dominant opening media and later full-width narrative images.

**Observed:** People talking, working and gathering in pale timber interiors with white beams, plants and daylight. Color is natural, warm and restrained rather than heavily graded. The main opening image occupies 1180×598px; most subsequent wide images occupy 940×598px. Rectangular edges are crisp with no caption overlay or decorative frame. Occasional evening gathering photos use candid direct flash and deep shadows.

**Transfer:** Photograph the new product in actual use with contextual surroundings and imperfect human gestures. If there is no venue, show tools, artifacts or a user working at a real table; retain soft daylight, substantial environmental space and a broad rectangular composition.

### Portrait and square proof grid

**Use:** Compare locations, contexts or related examples.

**Observed:** Two 460×575px portrait views sit side by side with centered 16px captions and actions beneath. Related contexts become square images, either four 220px tiles across or a two-column grid of 460px images. Subjects include façades, records, mountain views through windows and a red-lit interior; each keeps its own natural color.

**Transfer:** Use different authentic contexts instead of repeated mockups on identical studio backdrops.

### Overflow photo rail

**Use:** Extend the story beyond a single framed image.

**Observed:** A centered 940×623px image is flanked by partially visible neighbors, separated by 20px. Black pagination sits beneath on colored paper; inset photo galleries use white 10px markers over the lower-right corner, with the selected marker square and the rest round.

**Transfer:** Use a small set of genuine complementary views. Carry the browsing-shelf device through photography or the Testimonial card shelf, keeping the visible edge previews.

### Typographic cost diagram

**Only for:** transparent operational or financial explanations

**Use:** A rare data-art proof panel.

**Observed:** A thin black rectangular frame contains a large outlined pie diagram on the same sky-blue canvas. Instead of colored fills, each segment is packed with repeated category words that rotate slightly with the sector; a small title sits in the top-left corner. Dashed category controls sit underneath.

**Transfer:** Use only when there is real categorical data; keep the graphic typographic and monochrome rather than importing a colorful analytics chart.

**Build:** Use a 940×703px SVG stage with a 1px black frame. Place a large pie circle centrally with 1px radial separators. Clip repeated rows of 16px black category labels into each sector, with a slight rotation per sector. Leave the canvas color visible through all sectors, and place a small two-line title near the upper-left inset.

### Icons

**Observed:** Iconography is almost absent: a 25px circular ellipsis menu, simple 10px pagination dots/squares and 12px notice pins. Availability uses a 10px bright-green dot beside text.

**Transfer:** Use geometric punctuation and explicit text labels rather than a feature-icon library; distinguish active gallery position by square versus circle.

## Section recipes

How recurring sections are built.

### First screen: Documentary opening

**Observed:** On white Paper canvas, Fixed navigation floats above a wide, centered photograph starting 125px down the document. The 1180×598px image is about four-fifths of the viewport width and roughly two-thirds of its height; it leads the composition, with small white pagination at its lower-right. Beneath it, after 20px, a two-line 24px lead statement occupies a 580px left-aligned column anchored to the image edge. Another 20px leads to two tiny outline/dashed actions. The first 900px includes the navigation, complete image, headline and actions, with whitespace below; the next chapter starts below the fold. Layers are flat paper, photograph, pagination, then text and controls—not superimposed hero copy.

**Transfer:** For a new landing page, lead with a real scene that proves the product's environment or use, then plainly state what it is. Without existing media, create a daylight photograph of the relevant tools or a person using the product. Offering directories open with a narrower 940px photograph and a 24px inset explanation. Detail pages place a 32px title and practical actions beside 20px copy below the image; institutional pages put a small centered welcome line before the image.

**Avoid:** Do not replace this with a centered giant headline, gradient background or floating interface mockup. Do not move the headline into the photograph or enlarge the actions to compete with it.

**Text style:** `lead` — kmrWaldenburg 400 · 24px/1.3 · tracking 0.01em

### Outline comparison

**Observed:** Information cards fill a paired 940px grid with 20px gutters. A 32px heading and 16px practical copy sit high in each card, while Outline buttons align low. A broad companion card can span the pair.

**Transfer:** Compare two routes, formats or service options; let different copy lengths share the same action baseline.

**Text style:** `heading` — kmrWaldenburg 400 · 32px/1.3 · tracking 0.01em

### Editorial browsing chapter

**Observed:** Resource tiles form a narrower three-column island; a circular terminal tile breaks the rectangular repetition. Editorial list rows use a wider 940px region, a ruled filter bar and Expansion panel beneath.

**Transfer:** Use one format for browseable artifacts and the other for dated or credited material; keep the circular browse-all device with the resource grid.

### Pinned participation notice

**Observed:** Pinned invitation interrupts the white canvas with a single wide Lemon notice, centered copy and side pins. The chapter is short compared with the surrounding photography and whitespace.

**Transfer:** Adapt it to a submission, request, contribution or trial invitation; retain the paper-like geometry and restrained type.

### Centered text invitation

**Observed:** A regular 32px statement spans most of the 940px region, centered over a small Outline button with 20px separation. Other media chapters use a centered 24px title, a 40px gap to a photograph, then 24px explanatory copy in an inset column.

**Transfer:** Use a concise benefit statement as a pause between denser proof chapters rather than introducing a different visual language.

**Text style:** `heading` — kmrWaldenburg 400 · 32px/1.3 · tracking 0.01em

### Community proof shelf

**Observed:** Testimonial cards occupy a full-width horizontal rail with 20px gaps and visible offscreen neighbors. Small captioning and paired PREV/NEXT Outline buttons sit below the rail aligned to the main content region.

**Transfer:** Use substantive first-person testimony that can sustain the square format; attribute it plainly.

**Text style:** `body-large` — kmrWaldenburg 400 · 20px/1.3 · tracking 0.01em

### Related-content ending

**Observed:** The default ending follows a final documentary media-and-action chapter with two short, wide Information cards, then 160px of breathing room and Compact footer. Directory endings use a four-image gallery; detailed offerings add an outlined related-offering card after a two-column gallery. Editorial endings finish with the Overflow photo rail and the same footer.

**Transfer:** Choose related routes or concrete examples as the last substantive content. Keep the final navigation compact and on the same canvas.

### Transparent terms chapter

**Only for:** pricing and capacity-based offerings

**Observed:** A 32px invitation and short 20px explanation introduce the Membership card grid. A later financial explanation uses 32px heading, 20px paragraphs and the Typographic cost diagram separated from the prose by 160px. Simple YES/NO columns use 20px headings and 16px ruled rows to clarify fit.

**Transfer:** Explain eligibility, terms and economics candidly, preserving the contrast between simple prose and an unusually expressive but monochrome data panel.

## Page flow

**Storyline:** Show a real context → explain the offer → expose ways in → provide human and practical proof → invite participation → point to related routes → compact index.

### Introduce a multi-part product or community offering

1. **promise through demonstration** — Broad documentary image, modest definition and two small entry actions.
2. **offer architecture** — Outlined comparison cards and a spanning companion route.
3. **active proof** — Editorial resource grid with circular browse-all tile, followed by dated thumbnail rows.
4. **participation** — Yellow pinned invitation and a centered benefit-and-action pause.
5. **human proof** — Dashed testimonial shelf.
6. **secondary conversion** — Documentary photo chapter with plain explanatory copy and a small action.
7. **related routes and closure** — Paired short outline cards, breathing room and compact ruled footer.

**Transfer:** Use the same balance of lived context, useful information and modest invitations; select the chapters relevant to the new product.

### Help readers choose among concrete offering variants

1. **context** — Daylight image and inset descriptive paragraphs on continuous sky-blue paper.
2. **human proof** — Dashed testimonial rail.
3. **comparison** — Two portrait photographs with factual captions, availability and paired actions.
4. **breadth** — Short network explanation and four square related examples.
5. **closure** — Compact footer on the same blue canvas.

**Transfer:** Use this variant for directories, multi-location services or parallel product formats.

### Make one detailed offering understandable and actionable

1. **demonstration and practical promise** — Wide photograph above title, address-like metadata, action cluster and explanatory column.
2. **philosophy and fit** — Another photograph, editorial paragraphs and ruled affirmative/negative lists.
3. **immersive proof** — Overflow photo rail.
4. **conversion and terms** — Short invitation followed by equal-weight plan cards with capacity markers.
5. **objection handling** — Open explanation of costs and a text-filled pie diagram.
6. **ongoing value** — Dated editorial list and expansion action.
7. **breadth and closure** — Centered benefit statement, square related-example grid, a related-offering outline card and compact footer.

**Transfer:** Translate the practical metadata, fit criteria, plans and financial proof to the new offering rather than treating the page as a generic feature list.

### Explain an organization's character through practice

1. **welcome** — Small centered heading, documentary gallery and origin explanation on gray paper.
2. **operating principles** — A centered row of perforated-looking labels and explanatory prose.
3. **tangible proof** — Paired portrait examples with factual captions and actions.
4. **activity proof** — Dated editorial list.
5. **broader purpose** — Three plain explanatory paragraphs and one action.
6. **human closing image** — Overflow documentary rail before the compact footer.

**Transfer:** Let real behavior and contexts substantiate the values; preserve the continuous gray-paper treatment.

## Writing

Warm, direct and specific, with the candor of people running a useful place together. It can be opinionated about how things should work, but prefers concrete invitations and practical detail to polished sales language.

**Do not copy:** Do not reuse the brand name, organization names, addresses, network names, plan prices, capacity numbers, founding story, financial totals, artwork, quoted testimonials or claims as facts for another product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the people behind the product, you for an invitation or practical instruction, and a straightforward product-name definition at the opening.
- **Rhythm:** Short utility labels alternate with complete, moderately long explanatory sentences. Section statements often run one or two lines; editorial prose is allowed to explain rather than being reduced to slogans.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Define the product's category, functions and context in one ordinary sentence. | About 12–20 words | “Index NYC is a shared studio, event space, and community center in downtown NYC.” |
| Section invitation | State a concrete opportunity, sometimes as a full sentence rather than a clipped headline. | About 6–18 words | “Explore a new passion and hone your skills with asynchronous courses at Index.” |
| Practical action | Plain verb plus object, title case, no urgency language. | 1–4 words | “Request a Tour”<br>“Submit A Proposal”<br>“Book With Us” |
| Principle label | Name an actual practice or constraint. | 2–3 words | “Financial transparency”<br>“Peer-led programming” |
| Support prose | Explain who can participate and the concrete forms participation takes. | One or two complete sentences | “Anyone can come to us with an idea for a public event, workshop, or multi-session class.” |

**Words and phrasing to use:** gather; shared; join; host; access; members; peer-led; transparent; reach out; Learn More

**Avoid:** revolutionary; unlock your potential; game-changing; seamless ecosystem; exclusive luxury; act now

**Rules:**

- Define what the product is before arguing why it matters.
- Pair broad statements with concrete use cases, access terms or examples.
- Keep actions clear and literal; a small outline label should be enough to understand the next step.
- Let testimony retain personal details and conversational syntax.
- When discussing trade-offs, explain them plainly rather than disguising constraints as benefits.

## Do's and Don'ts

### Do

- Keep core text regular at 16px, 20px, 24px and 32px with 1.3 line height.
- Use 20px gutters to tie photographs, cards and lists together.
- Give major chapters 160px of separation rather than adding decorative dividers everywhere.
- Keep ordinary controls at 2px 5px padding with a 1px outline.
- Retain the two black 12px pins on the yellow invitation panel.
- Show neighboring items at the edges of a 20px-gap horizontal shelf.
- Use 135px square thumbnails for desktop editorial rows.
- Carry an alternate paper color continuously through its footer.

### Don't

- Do not use bold 64px sales headlines; the ordinary heading range ends at 32px.
- Do not round rectangular cards or photographs into soft app-style tiles.
- Do not introduce drop shadows to distinguish outlined cards.
- Do not make every action a pill; circles are reserved for menu, pagination and the resource browse-all tile.
- Do not use bright green as a section fill or button color; it belongs to 10px availability markers.
- Do not turn plan comparison into a dark recommended card against pale secondary plans.
- Do not add a dense feature-icon grid to a system that uses mostly text and geometric punctuation.
- Do not replace the compact ruled footer with a giant wordmark or oversized final CTA.

## Motion and responsive

### Motion

**Observed:**

- Availability markers declare status-pulse 1.65s step-end infinite.
- Horizontal photo and testimonial shelves use scroll-snap behavior and pagination or PREV/NEXT controls.
- No action or surface transition declarations were matched; hover changes are subtle black overlays or underlines.

**Transfer:**

- Preserve the discrete pulse for factual live capacity markers and the browseable rail interaction; keep ordinary hover changes visually immediate.

**Unknown:**

- Gallery autoplay, slide timing and the exact pulse keyframe appearance are not established.

### Responsive

**Observed:**

- The layout declares breakpoints including 400px, 640px, 768px, 1024px, 1150px and 1440px.
- Two-column content grids have one-column base classes and switch at the medium breakpoint; desktop navigation arrangements are gated at 1150px.
- Hero media has separate mobile and desktop aspect treatments.

**Transfer:**

- On narrow screens, stack comparison cards and portrait examples while preserving outlines and the hierarchy of image before explanation.
- Retain edge previews and horizontal scrolling for the browsing shelves instead of squeezing square cards into tiny columns.
- Keep the small outlined labels and circular menu as the navigation language; reflow action groups rather than scaling their type down.

**Unknown:**

- Exact mobile geometry, media aspect ratios and spacing changes are not established; the desktop dimensions are not mobile requirements.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
