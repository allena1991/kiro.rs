# DashDigital — uppercase cinematic index

## Overview

An editorial showcase where tightly stacked grotesk headlines and tiny catalogue captions frame richly lit photography and digital work. The default is pale grey and charcoal, with almost all colour living inside the imagery; muted olive and near-black provide distinct long-form variants. It suits visually confident products, creative tools and premium services that can show their value through substantial media rather than dense interface chrome.

### Essentials

- Headlines behave like compact typographic posters: regular-weight Founders Grotesk capitals at 100.8px, 0.8 line height and -0.03em tracking, left aligned in tightly stacked lines.
- The opening makes its claim, then immediately shows the work: a 56px navigation bar, 86.4px of headline top breathing room, a tiny two-line descriptor, and a two-column image field beginning within the first 900px.
- Actions are miniature capsules, not oversized conversion banners: 22px high, 4px 12px padding, 999px corners and 12px uppercase labels on charcoal; a warm stone layer supports the masked alternate label.
- Colour belongs to the work rather than the chrome: the ordinary page is #f0f0f0 with #2a2a2a text, and natural greens, amber light and saturated subjects stay inside edge-to-edge rectangular media.
- Images read like entries in an art-directed catalogue: 677px × 490px desktop fields, 28.8px gutters, 12px uppercase discipline captions and 21.6px titles, divided by 1px rules. Every new landing page needs this media-led proof device; use a convincingly lit product still or composed interface scene when photography is unavailable.
- The ending is another destination, not a dense sitemap: a #fafafa full-screen closing field pairs a 70px next-destination title with a much smaller 21.6px contact invitation, a tiny pill and widely separated contact columns. Preserve this destination-plus-invitation device.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm stone | `#ccc4b9` | `--color-stone` | surface, text, action | Alternate button layer; text and pale actions on dark editorial pages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Closing white | `#fafafa` | `--color-closing` | background | Full-screen closing field, subtly lighter than the body. |
| Pale grey canvas | `#f0f0f0` | `--color-canvas` | background, text | Default marketing canvas and light text on dark capsules. |
| Soft grey rule | `#d6d6d6` | `--color-soft-rule` | border | Subdued proof-row and recognition separators. |
| Footer rule | `#cccccc` | `--color-meta-rule` | border | Hairline above the bottom metadata strip. |
| Metadata grey | `#757575` | `--color-muted` | text | Small contact category labels in the closing field. |
| Charcoal ink | `#2a2a2a` | `--color-ink` | text, action, border | Default letters, thin structural lines and dark action capsules. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and methodology storytelling | Grey olive | `#bcbcb4` | `--color-olive` | background | Muted background for the introductory culture and methodology chapters. |
| case studies and catalogue controls | Editorial black | `#0f0f0f` | `--color-dark` | background, surface | Long-form case-study canvas and selected catalogue-view indicator. |
| case studies | Dark media stage | `#161616` | `--color-stage` | surface | Raised tonal backdrop for demonstrations against the editorial black canvas. |
| capability pages | Chapter divider | `#949494` | `--color-chapter-rule` | border | Separators between large capability chapters. |
| catalogue pages | Control outline | `#cecece` | `--color-control-edge` | border | Fine outline surrounding the segmented view control. |

## Typography

- **Founders Grotesk** — All marketing text, from display statements to tiny navigation and captions. A lean, matter-of-fact grotesk with compact capitals and light paragraph texture; hierarchy comes from scale rather than bold weight. If unavailable, use **Inter Tight**. Use 300 for paragraphs and 400 for capitals; tune line breaks to retain the compact headline width. Font stack: "Founders Grotesk", "Inter Tight", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Founders Grotesk | 400 | 100.8px | 0.8 | -0.03em, uppercase | fixed | Primary promise and page-title statements, usually two or three tightly stacked lines. |
| heading-lg | Founders Grotesk | 400 | 70px | 0.8 | -0.03em, uppercase | size 4.86vw | Major section headings and next-destination links. |
| heading | Founders Grotesk | 400 | 40.3px | 1 | -0.03em, uppercase | size 2.8vw | Secondary section titles and compact proof numerals. |
| lead | Founders Grotesk | 400 | 21.6px | 0.9 | -0.03em, uppercase | size 1.5vw | Short section propositions, media titles, recognition categories and closing invitation. |
| brand-link | Founders Grotesk | 400 | 17.3px | 1 | -0.03em | size 1.2vw | Text-based brand link in the navigation. |
| body | Founders Grotesk | 300 | 16px | 1.2 | normal | size 1.11111vw | Explanatory paragraphs, benefit narratives and capability inventories. |
| label | Founders Grotesk | 400 | 14px | 1 | -0.02em, uppercase | fixed | Navigation, opening descriptors, proof-row names and short contact details. |
| caption | Founders Grotesk | 400 | 12px | 1 | -0.02em, uppercase | fixed | Disciplines, category labels, social links and metadata. |
| button | Founders Grotesk | 400 | 12px | 14px | normal, uppercase | fixed | Both layers of miniature capsule actions. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | editorial-statement | Founders Grotesk | 400 | 54.7px | 0.85 | -0.03em, uppercase | size 3.8vw | Wide narrative statements between substantial demonstrations. |
| methodology chapters | method-list | Founders Grotesk | 400 | 36px | 1.2 | normal, uppercase | size 2.5vw | Oversized scrolling capability inventories. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep large capitals at weight 400 and -0.03em tracking; do not substitute a heavy display weight. The 0.8 line height deliberately makes multiline headlines feel tightly packed.
- Paragraphs switch to weight 300, normal tracking and sentence case. Small uppercase captions use -0.02em rather than the headline tracking.
- Align the visible left edge of capitals with the grid; negative left margins equal to the tracking compensate for the first letter. Use normal tracking on capsule labels.
- The display statement is substantially larger than the major section heading; the contact invitation remains a small lead rather than becoming another hero.

## Layout

**Density:** Airy at section scale and compact within typographic clusters; long pauses separate densely labelled media.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 12px | Text stacks and list-group spacing. | fixed |
| 14.4px | Half-gutters and close internal spacing. | 1vw |
| 17.3px | Media-to-caption gap. | 1.2vw |
| 28.8px | Page inset, primary gutters and heading-to-support gap. | 2vw |
| 43.2px | Space after media captions and before the next entry. | 3vw |
| 57.6px | Secondary section breaks and opening bottom space. | 4vw |
| 86.4px | Opening headline top space and editorial section pauses. | 6vw |
| 115.2px | Major section breaks. | 8vw |

### Containers and grids

- **page container**: max width 1440px · side padding 28.8px. Broad desktop canvas with a 1382px inner field; use fluid side insets rather than a narrow centred reading column.
- **editorial grid**: 8 columns · gap 28.8px. Main alignment scaffold: statement on the left half, prose beginning in the right half; paragraphs commonly span about 500px.
- **showcase grid**: 2 columns · gap 28.8px. Equal-width media columns, each with a 677px image field at desktop. A centre hairline makes the two columns read as a catalogue.
- **proof grid**: 4 columns · gap 28.8px. Four open 324px-wide proof entries, without boxed card fills.
- **recognition stats** (only for capability pages): 3 columns · gap 205.2px. Three widely separated 324px-wide proof counters.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 999px |
|  | media and editorial panels | 0px |
| catalogue pages | view control | 144px |

## Surfaces and depth

### Surfaces

#### Pale canvas · level 0

**Use:** Default marketing field.

**CSS:** `background: #f0f0f0; color: #2a2a2a`

**Observed:** Text and media share one continuous field; sections do not become stacks of elevated cards.

**Transfer:** Let whitespace and hairlines organise the page.

#### Closing field · level 0

**Use:** Shared destination and contact ending.

**CSS:** `background: #fafafa; color: #2a2a2a`

**Observed:** A subtly brighter full-screen field with a fine bottom metadata rule.

**Transfer:** Retain the tonal change even when the main page uses a darker theme.

#### Olive field · level 0

**Only for:** company and methodology storytelling

**Use:** Long-form introduction and process chapters.

**CSS:** `background: #bcbcb4; color: #2a2a2a`

**Observed:** Muted olive-grey supports black text, a central vertical rule and broad text inventories; people-focused sections can return to pale grey.

**Transfer:** Use as a scoped chapter atmosphere, not as the ordinary product landing-page background.

#### Dark editorial canvas · level 0

**Only for:** case studies

**Use:** Immersive project narrative.

**CSS:** `background: #0f0f0f; color: #ccc4b9`

**Observed:** Warm stone text softens the contrast; full-width photography interrupts the dark field.

**Transfer:** Keep the surrounding chrome neutral even when the demonstrated product is colourful.

#### Demonstration stage · level 1

**Only for:** case studies

**Use:** Inset desktop and mobile product demonstrations.

**CSS:** `background: #161616; padding: 180px 0; border-radius: 0px; box-shadow: none`

**Observed:** A 1030px × 579px desktop demonstration sits centred in a broad tonal field; other sequences use two 677px panels or a horizontally overflowing editorial strip.

**Transfer:** Render a genuine product task or composed static interface, framed by ample dark backing rather than decorative browser chrome.

## Components

### Navigation

**Use:** Persistent orientation and section access.

**CSS:** `position: fixed; height: 56px; padding: 0px 28.8px; background: #f0f0f0; color: #2a2a2a; z-index: 5`

**Text style:** `label` — Founders Grotesk 400 · 14px/1 · tracking -0.02em · uppercase

**Observed:** Small text brand at left; six short links spread across the right half at the top. During scrolling the bar compacts to brand plus current section and a right-aligned Menu +. Background follows the active page theme.

**Transfer:** Keep the brand typographic and the link group narrow; preserve the open space between them.

### Capsule action

**Use:** Contact, deeper exploration and project links.

**CSS:** `background: #2a2a2a; color: #f0f0f0; border-radius: 999px; height: 22px; padding: 4px 12px; display: inline-flex; position: relative`

**Text style:** `button` — Founders Grotesk 400 · 12px/14px · uppercase

**Observed:** A dark front mask carries the short resting label. A warm-stone rear mask carries a longer contextual label with extra left padding; both occupy a single link, not two separate buttons. The dark editorial variant reverses the front to warm stone.

**States:** Declared: hover outline 0px; active outline 0px. Focus-visible styling is unknown.

**Transfer:** Keep the front label concise and use the alternate text to explain the destination.

### Text link

**Use:** Navigation and compact contact links.

**CSS:** `position: relative; padding-bottom: 2px; color: #2a2a2a`

**Text style:** `label` — Founders Grotesk 400 · 14px/1 · tracking -0.02em · uppercase

**Observed:** Plain uppercase text without a box; thin underline treatment belongs to the text edge rather than a broad coloured block.

**Transfer:** Use caption typography for the smaller social-link variant.

### Showcase entry

**Use:** Large visual evidence in paired columns.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; padding: 0px 14.4px; position: relative`

**Text style:** `lead` — Founders Grotesk 400 · 21.6px/0.9 · tracking -0.03em · uppercase

**Observed:** Sharp rectangular image first, then a discipline caption and a short title. The caption stack begins 17.3px after the image and leaves 43.2px below it. Fine horizontal rules separate successive rows; a centre rule runs through the grid.

**Transfer:** Pair a real product result with compact category text instead of descriptive card paragraphs.

### Proof accordion row

**Use:** Dense expandable proof or customer index.

**CSS:** `position: relative; height: 54px; color: #2a2a2a`

**Text style:** `label` — Founders Grotesk 400 · 14px/1 · tracking -0.02em · uppercase

**Observed:** Full-width row aligns name at left, small discipline text beginning in the right half and More + at the far right. The expanded label becomes Less —; rows are separated by pale hairlines.

**Transfer:** Use for integrations, customer outcomes or detailed capabilities when a visual tile would be repetitive.

### Recognition row

**Use:** Grouped third-party or independently verifiable proof.

**CSS:** `display: grid; grid-template-columns: repeat(2, 1fr); gap: 32.4px; padding-bottom: 37.4px; border-bottom: 1px solid #d6d6d6`

**Text style:** `lead` — Founders Grotesk 400 · 21.6px/0.9 · tracking -0.03em · uppercase

**Observed:** Category occupies the first column; multiple small uppercase achievements stack in the second. The group occupies the right half of the page beside an introductory paragraph.

**Transfer:** Translate to certifications, benchmarks or verified outcomes without inventing prestige.

### Destination link

**Use:** Primary onward path in the closing field.

**CSS:** `position: relative; padding-bottom: 5.8px; color: #2a2a2a`

**Text style:** `heading-lg` — Founders Grotesk 400 · 70px/0.8 · tracking -0.03em · uppercase

**Observed:** A tiny Next page label precedes the large title. Where appropriate a small count sits beside the title's top edge. It remains left aligned with extensive space around it.

**Transfer:** Point to the most useful next step rather than reproducing a full sitemap.

### Footer metadata strip

**Use:** Bottom-edge copyright, socials and return control.

**CSS:** `display: grid; grid-template-columns: repeat(8, 1fr); gap: 28.8px; border-top: 1px solid #cccccc; align-items: center`

**Text style:** `caption` — Founders Grotesk 400 · 12px/1 · tracking -0.02em · uppercase

**Observed:** Copyright sits at the left; three social links occupy separate right-hand grid positions; the return link is pinned to the far right. The strip is 58px high.

**Transfer:** Keep utility text small and spatially dispersed.

### Proof counter

**Only for:** capability pages

**Use:** Compact quantified evidence.

**CSS:** `border-bottom: 1px solid #2a2a2a; padding-bottom: 14.4px`

**Text style:** `heading` — Founders Grotesk 400 · 40.3px/1 · tracking -0.03em · uppercase

**Observed:** A monochrome credential mark sits above the rule; below it a regular-weight numeral is left aligned with a tiny uppercase source label at the right. Three counters use wide gaps and no filled cards.

**Transfer:** Use validated counts or performance measures with clear attribution.

### Portrait entry

**Only for:** team and culture pages

**Use:** Human introduction within a four-column grid.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; border-top: 1px solid #2a2a2a; padding-bottom: 43.2px; margin-right: 28.8px`

**Text style:** `lead` — Founders Grotesk 400 · 21.6px/0.9 · tracking -0.03em · uppercase

**Observed:** A tiny personal-interest line and job role sit above a narrow 202px × 288px portrait. Name is uppercase below the picture; the image does not fill the entire 324px column.

**Transfer:** Use consistent lighting and crop while leaving the same deliberate unused width.

### View switch

**Only for:** catalogue pages

**Use:** Grid/list choice beside a collection heading.

**CSS:** `display: flex; position: relative; align-items: center; padding: 4px; border: 1px solid #cecece; border-radius: 144px; height: 40px`

**Text style:** `label` — Founders Grotesk 400 · 14px/1 · tracking -0.02em · uppercase

**Observed:** A dark 65px × 30px sliding capsule marks the selected choice. A filter link sits to its left, while the collection title and small count anchor the opposite edge.

**Transfer:** Use only when there are genuinely distinct catalogue views.

## Imagery and graphics

### Cinematic product catalogue

**Use:** Primary media-led proof device, including the opening pair.

**Observed:** Natural landscape and people photography alternate with carefully staged laptops, posters and digital interfaces. Screens sit on textured stone or wood, among architectural glass and metal, or in warm hospitality interiors. Directional daylight, deep shadows, earthy greens and warm amber make the work tactile. Rectangular 677px × 490px fields dominate their small captions; there are no rounded media cards.

**Transfer:** Photograph the new product in a credible environment with raking light and visible material texture. For software, composite a real interface into one convincing device scene; the minimum is a carefully lit, high-resolution flat composition with a genuine product view, never a generic floating dashboard.

**Build:** For a reproducible device scene, place a perspective-transformed interface on a photographed or rendered dark laptop; use a matte stone or wooden plane, a single side key light and a diagonal cast shadow. Crop the environment to a 677:490 field and preserve readable screen contrast; keep all scenic colour inside the image.

### Candid horizontal strip

**Use:** A human-scale counterpoint to product proof.

**Observed:** Office life in window light: working, laughing, reading and collaborating. Landscape and narrow portrait frames share a 346px height, with 28.8px gaps and a strip that extends beyond the viewport. Plants, wood desks, dark clothes and glass architecture give a natural, unsaturated tone.

**Transfer:** Use customers or makers in real activity rather than a stock-photo handshake. Keep varied widths and a common height to create the same editorial rhythm.

### Film inset

**Use:** A substantial visual pause between text and proof chapters.

**Observed:** A centred cinematic film frame with close-up human imagery, deep blacks and small title/date markings. The visible composition is wider than the narrow underlying media slot and stays sharply rectangular.

**Transfer:** Use one strong motion scene or a sequence of product-detail stills. Keep it as media rather than turning the full page into a video background.

### Dark portrait series

**Only for:** team and culture pages

**Use:** Consistent human profiles.

**Observed:** Waist-up portraits against a near-black green-grey background, mostly dark clothing, restrained frontal light and occasional foliage. Narrow images leave room within the broader ruled columns.

**Transfer:** Use one lighting setup and repeat the framing; let expressions carry individuality, not coloured background circles.

### Demonstration montage

**Only for:** case studies

**Use:** Detailed proof of product behaviour and design decisions.

**Observed:** Large interface views, paired mobile screens, design-system sheets and typography panels sit on dark tonal stages. Full-bleed product photography punctuates them: warm studio backdrops and glossy draped fabric contrast with the flat UI. The demonstrated work has its own typography and colour, contained inside the media.

**Transfer:** Show an equivalent sequence of product use, structural detail and finished result. The product's own visual identity can vary freely inside the neutral editorial framing.

### Icons

**Observed:** Interface symbolism is primarily typographic: + for opening, an em dash for closing, small counts and understated index markings. Monochrome recognition marks function as logos rather than feature icons.

**Transfer:** Prefer text, + and — over a library of decorative line icons. Keep any necessary symbols small and matched to the adjacent label colour.

## Section recipes

How recurring sections are built.

### First screen: Statement and catalogue opening

**Observed:** A pale canvas supports a 56px top navigation with the small brand left and links across the right half. After 86.4px of top breathing room, a left-aligned 100.8px uppercase promise forms three tightly stacked lines, reaching roughly three quarters of the page width. A 14px two-line descriptor tucks beneath it, leaving the right side open. The first two sharp rectangular showcase images begin about 483px into the page, with 28.8px outer insets and a matching central gutter. Within the first 900px the entire headline, descriptor and upper majority of both images are visible; their captions fall below the fold. There is no hero capsule: navigation and clickable media provide the opening actions. Layers are simply pale field, typographic navigation and statement, then richly coloured media.

**Transfer:** Write a compact product promise with comparable visual width and two or three intentional line breaks. Stage two complementary product results beneath it; if no photography exists, use a real interface scene plus a detail or use-context image. Capability pages add a right-half support paragraph and a wide photograph below the headline. Culture storytelling uses the olive field; a case study uses a short title, indices, year and wide lead image on dark; a catalogue opens compactly with title, count, filter and view switch.

**Avoid:** Do not centre a short headline above a floating mockup, add a large conversion-button row, or push all visual proof below the first screen.

**Text style:** `display` — Founders Grotesk 400 · 100.8px/0.8 · tracking -0.03em · uppercase

### Split proposition

**Observed:** A heading-lg title spans the top of the editorial grid; 28.8px below, a short lead sits at left while a roughly 500px paragraph begins in the right half. Capsule action follows that paragraph after 28.8px. Major surrounding pauses use 115.2px and 57.6px breaks.

**Transfer:** Use the left side for the promise and the right side for the explanation and next step.

**Text style:** `heading-lg` — Founders Grotesk 400 · 70px/0.8 · tracking -0.03em · uppercase

### Open proof gallery

**Observed:** Four open columns combine monochrome customer marks, light paragraphs and Capsule actions. A secondary heading introduces the Proof accordion row index beneath. No card backgrounds or shadows separate the columns.

**Transfer:** Translate to four outcomes, use cases or customer examples; let the index hold the longer tail of proof.

### Recognition split

**Observed:** A large two-line heading and compact paragraph occupy the left half; Recognition rows occupy the right half with categories and tiny uppercase achievement lists separated by hairlines.

**Transfer:** Use this asymmetric treatment for credible proof that needs several compact entries, not an icon-card grid.

### Compact news pair

**Observed:** A 40.3px heading and small View all capsule share a line. Two editorial entries sit below, each splitting a 324px-wide image and text column within a 677px-wide block; metadata and uppercase lead titles provide the reading hierarchy.

**Transfer:** Use for substantive product updates or editorial content, retaining the image-plus-text construction rather than converting it to rounded blog cards.

### Destination and invitation ending

**Observed:** Closing field fills a 900px desktop viewport. Navigation returns across the top. An isolated Next page caption and Destination link occupy the upper-left portion; after a broad 115.2px pause the contact invitation and Capsule action remain on the left. Two compact contact columns begin in the right half, including muted category captions and uppercase details. The Footer metadata strip anchors the bottom. The same construction follows light, olive and dark content; only the onward destination changes.

**Transfer:** Always provide a large onward destination and a smaller human invitation. Substitute relevant sales, support or community details while retaining the unusual contrast between spacious field and tiny contact text.

**Text style:** `heading-lg` — Founders Grotesk 400 · 70px/0.8 · tracking -0.03em · uppercase

### Capability chapter

**Only for:** capability pages

**Observed:** A heading at 40.3px, paragraph and Capsule action occupy the left half. A Showcase entry fills the right half. Chapters stay aligned to the same two-column grid and close with a 1px medium-grey rule.

**Transfer:** Give each product capability a distinct demonstration while keeping the text short.

**Text style:** `heading` — Founders Grotesk 400 · 40.3px/1 · tracking -0.03em · uppercase

### Capability inventory

**Only for:** capability and detailed case-study pages

**Observed:** A large title, short uppercase lead and contact action occupy the left half; grouped lists occupy two columns in the right half. Group titles use lead typography, list entries use body typography and 12px gaps keep the lists readable without boxes.

**Transfer:** Group technical depth by user outcome or function instead of presenting a wall of equal cards.

### Pinned methodology list

**Only for:** methodology chapters

**Observed:** A muted olive chapter splits at a central vertical rule. The left half holds a large changing chapter title, small numeric progress pair, paragraph and Capsule action. The right half carries 36px uppercase lists; successive lines shift horizontally to make a shallow diagonal staircase, with thin rules between groups.

**Transfer:** Use for a meaningful staged process. Keep the staircase restrained and preserve the relationship between a stable summary and scrolling detail.

**Text style:** `method-list` — Founders Grotesk 400 · 36px/1.2 · uppercase

### Case-study media chapters

**Only for:** case studies

**Observed:** A dark editorial canvas alternates wide 54.7px uppercase narrative statements, split challenge/solution text and Demonstration stages. Two-column panels and full-bleed photography vary the scale. Near the end, a capability inventory gives scope, then four portrait-oriented related-project cards precede the Closing field.

**Transfer:** Alternate why, how and what-it-looks-like; use real demonstrations rather than repeating the same screenshot at different sizes.

**Text style:** `editorial-statement` — Founders Grotesk 400 · 54.7px/0.85 · tracking -0.03em · uppercase

## Page flow

**Storyline:** Statement → immediate visual proof → explanation → deeper evidence or capability chapters → human or independent credibility → onward destination and contact invitation.

### A visual marketing landing page that establishes taste before explaining the offer

1. **Promise** — Large three-line uppercase statement and tiny descriptor.
2. **Immediate proof** — Two-by-two cinematic showcase grid.
3. **Explanation** — Split proposition and substantial film inset.
4. **Social proof** — Four open proof columns followed by an expandable index.
5. **Human credibility** — Candid image strip, recognition split and compact editorial updates.
6. **Closing call** — Destination and invitation ending.

**Transfer:** Lead with tangible product results, then explain the approach and reinforce trust before offering the next destination.

### A capability page that connects broad claims to concrete examples

1. **Promise** — Two-line uppercase statement, right-half support paragraphs and wide contextual photograph.
2. **Capability chapters** — Repeated text-left, media-right chapters with dividing rules.
3. **Technical depth** — Grouped inventory in the right half beside a compact proposition.
4. **Quantified proof** — Three monochrome proof counters.
5. **Closing call** — Shared bright destination and contact field.

**Transfer:** Organise by what a customer can achieve; associate every capability with visible proof.

### A culture and methodology story with human credibility

1. **Positioning** — Olive opening with large statement, right-half prose and wide film.
2. **Method explanation** — Stable left summary and stepped scrolling lists on the right.
3. **Human proof** — Four-column ruled portrait entries.
4. **Working context** — Split collaboration statement, compact locations and candid photo strip.
5. **Closing call** — Bright shared destination and contact field.

**Transfer:** Use the olive variant for process depth, then return to lighter people-focused content and a spacious ending.

### A detailed outcome narrative and product demonstration

1. **Identification** — Dark title, small project indices, year and wide photographic lead.
2. **Context and stakes** — Large uppercase overview followed by recognitions and challenge/solution columns.
3. **Demonstrated solution** — Tonal demonstration stages, detailed split chapters and wide product photography.
4. **Implementation depth** — Design-system details, responsive views and interaction examples.
5. **Scope and continuation** — Grouped capability inventory and four related visual entries.
6. **Closing call** — Return to the bright shared destination and contact field.

**Transfer:** Let the demonstrated product keep its own visual identity; the surrounding narrative retains restrained grotesk type and neutral surfaces.

### A browsable visual catalogue with minimal editorial interruption

1. **Orientation** — Compact large title, small count, filter and segmented view switch.
2. **Product proof** — Long two-column grid of image, tiny discipline caption and uppercase title, with central and horizontal rules.
3. **Closing call** — Shared bright destination and contact field.

**Transfer:** Use for an extensive collection; keep metadata brief and let varied media subjects provide richness.

## Writing

Confident, collaborative and design-literate, but grounded in what the work does for people. Large declarative headlines give way to modest, explanatory prose and a friendly invitation.

**Do not copy:** Do not reuse DashDigital's name, client names, team names, project artwork, contact details, award counts, recognitions, proprietary claims or exact campaign statements. Examples illustrate voice only; replace all facts with substantiated content for the new product.

- **Addressing the reader:** Use we for the maker and you or your for the customer. Describe collaboration as a shared effort, not a vendor speaking down to a buyer.
- **Rhythm:** Compact noun-led or verb-led headlines, often 5–12 words; short one-sentence uppercase propositions; longer sentence-case explanations in small, light paragraphs. Use em dashes for conversational pivots and reserve plus/minus symbols for controls.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | State the practice and its motivating approach, or a clear transformation. | 6–12 words | “A digital design studio driven by research & strategy”<br>“Transforming ideas into digital experiences” |
| Supporting proposition | Connect the offer to a human or customer outcome in one sentence. | 8–16 words | “An international digital design studio reimagining how people connect with brands.” |
| Explanatory paragraph | Explain the approach through concrete actions, linking craft to customer value. | 40–80 words | “We're a small team of curious humans who create work we're proud of for people and brands we believe in.” |
| Primary action | Short destination or conversational invitation; alternate text can add context. | 2–5 words | “Get in touch”<br>“View case study” |
| Closing invitation | Warm direct invitation followed by a shared-action phrase. | 10–16 words | “We would love to hear from you. Let's work — together.” |

**Words and phrasing to use:** connect; collaboration; research; strategy; crafted; experience; together; intuitive; meaningful

**Avoid:** crush the competition; 10x everything; game-changing magic; disrupt or die; unsubstantiated best-in-class claims

**Rules:**

- Pair expressive headline claims with practical explanations of what changes for the customer.
- Use compact category names for navigation and lists; keep paragraphs sentence case despite the uppercase heading system.
- Write proof in attributable terms, with real counts and clear sources.
- Keep conversion language conversational rather than urgent or promotional.

## Do's and Don'ts

### Do

- Use 100.8px regular capitals with 0.8 line height for the opening promise.
- Keep the pale marketing field continuous and organise it with 1px rules.
- Maintain 28.8px desktop page insets and media gutters, scaling them with the viewport.
- Preserve the contrast between 12px captions and 677px-wide media.
- Use 22px miniature action capsules with 12px labels.
- Set explanatory prose at weight 300 with 1.2 line height.
- Carry the bright 900px destination-and-contact ending across theme variants.
- Stage software inside tactile light and materials, or use a convincingly composed flat demonstration.

### Don't

- Do not make all section headings the 100.8px hero size; the main section role is 70px.
- Do not introduce a bright brand-colour button system; actions are charcoal and warm stone.
- Do not add rounded corners or drop shadows to the showcase grid.
- Do not make small body paragraphs uppercase; that treatment belongs to headings, labels and captions.
- Do not fill unused portrait-column width by stretching the narrow 202px portrait.
- Do not use the olive background as the default for an ordinary product landing page.
- Do not make the contact invitation as large as the next-destination title.
- Do not apply the demonstrated product's condensed lettering or vivid interface colours to the surrounding marketing typography.

## Motion and responsive

### Motion

**Observed:**

- Text and media wrappers declare transform 1.5s cubic-bezier(0.075, 0.82, 0.165, 1).
- The navigation declares transform 1s cubic-bezier(0.215, 0.61, 0.355, 1).
- Media declares opacity 1s cubic-bezier(0.075, 0, 0.165, 0) alongside the 1.5s transform transition.
- Clipped masks declare clip-path 0.75s cubic-bezier(0.645, 0.045, 0.355, 1).
- The selected view indicator declares transform and width 0.2s cubic-bezier(0.645, 0.045, 0.355, 1).

**Transfer:**

- Reveal uppercase lines through clipped wrappers rather than fading an entire headline uniformly.
- Retain the layered capsule construction for contextual alternate labels.
- Use broad media and restrained typographic movement rather than ornamental bouncing or pulsing.

**Unknown:**

- Exact scroll trigger thresholds, delay values and runtime choreography are not established.
- Focus-visible treatment and all open-menu behaviour are not established.

### Responsive

**Observed:**

- Desktop typography and spacing use viewport-relative formulas, including 4.86vw section headings, 1.11111vw paragraphs and 2vw gutters.
- Declared width breakpoints include 480px, 481px, 767px, 768px, 769px, 1281px, 1441px and 1921px; some layouts add 915px, 992px and 1280px.

**Transfer:**

- On narrow screens, preserve the priority of statement then media: rewrap the promise and stack paired proof fields when two readable columns no longer fit.
- Retain small catalogue captions and sharp media corners; prevent desktop viewport formulas from making essential text unreadable.
- Collapse split proposition and contact columns into reading order while preserving the destination-plus-invitation hierarchy.

**Unknown:**

- Exact mobile type sizes, grid changes, menu presentation and breakpoint-specific rules are not established; narrow-screen transfers are design guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
