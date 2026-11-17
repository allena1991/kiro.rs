# Basecamp — paper, proof, plain talk

## Overview

A friendly, matter-of-fact light style that feels like useful software explained by the people who make it. Heavy grotesk headlines and conversational prose sit on icy blue paper, with white sheets, practical blue links, and small yellow and green accents. Real interface views and unpolished human video carry the persuasion; the page is spacious between chapters but comfortably dense within them. It suits products that can demonstrate their usefulness rather than rely on abstract spectacle.

### Essentials

- A useful directory comes before the sales pitch: the opening pairs an approximately 659px-wide working interface on the left with a stack of 19.1px linked explanations on the right, then a 42.1px/1.1 weight-800 promise below that stack.
- Headlines have the heft of a plainspoken declaration, not billboard scale: Graphik 800, -0.02625em tracking, 42.1px primary section headings and 38.3px secondary headings; the opening support is a substantial 30.6px/1.3 regular.
- White paper floats on an almost-white blue field: #f5f9ff fills most of the long body inside 30.6px white outer gutters; square white panels and diffuse multi-layer shadows make the content feel tangible. Include a slightly askew stacked-paper statement as a signature editorial device.
- Actions are useful rectangles, not candy-shaped pills: blue gradient fills, white weight-500 text, 0px corner radius, approximately 50px main actions and 37px navigation actions. Blue is concentrated in actions and links rather than whole-page decoration.
- Proof is specific and visibly human: large natural-light video stills, compact three-column italic reviews with yellow marked phrases and five stars, and short statistics in 42.1px-radius white capsules. Use a real workflow illustration or a readable constructed example when interface media is unavailable.
- The ending is a cheerful sign-off followed by a link patchwork: a centered 38.3px/1.15 heavy greeting, newsletter form, and tightly wrapped pale-blue rectangular links at 17.2px with 7.8px gaps, then a small centered maker credit and utility row. Preserve this device rather than replacing it with a conventional multi-column footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action blue | `#117af3` | `--color-action` | action | Base fill below the darker blue action gradient. |
| Deep action blue | `#0067de` | `--color-action-deep` | action | Darker gradient stop and declared hover fill. |
| Practical link blue | `#146dc7` | `--color-link` | link, text, action | Text links and footer chips; also the muted end of the action gradient. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Marked yellow | `#ffeeba` | `--color-highlight` | surface, accent | Inline review highlighting; #ffdc74 at 50% over white. |
| Blue chip wash | `#e7f2fe` | `--color-chip` | surface | Visible pale-blue footer link backing; action blue at 10% over white. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue-black ink | `#29353c` | `--color-ink` | text | All primary headings, body copy, icons and focus outlines. |
| Soft gray edge | `#ececec` | `--color-rule` | border | Fine separators between disclosure rows and pricing panes; black at 7.5% over white. |
| Icy blue canvas | `#f5f9ff` | `--color-canvas` | background, surface | Default inset marketing canvas and secondary navigation action. |
| White paper | `#ffffff` | `--color-paper` | background, surface, text | Outer canvas, raised sheets, video labels and text on filled blue actions. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Status green | `#1db847` | `--color-status` | accent | Small live-status dot, not a general background. |
| New stamp green | `#008a10` | `--color-stamp` | background, accent | Tiny tilted novelty stamps on selected footer links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| activity visualizations | Night map backing | `#0b151b` | `--color-map` | background | Contained dark visual field for geographic activity proof, not a dark page theme. |
| capability catalogs and release announcements | Lavender chapter canvas | `#fcf7ff` | `--color-lavender` | background | Alternate inset canvas for illustrated capability and release stories. |

## Typography

- **Graphik** — All marketing headings, paragraphs, links, actions and captions. A compact, clear grotesk with very heavy friendly headings and understated regular prose. OpenType features: "liga", "ss05". If unavailable, use **Inter**. Use weights 400–800 and retain the tight display tracking. Font stack: "Graphik", "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| opening-headline | Graphik | 800 | 42.1px | 1.1 | -0.02625em | Left-aligned main promise in the split opening. |
| section-heading | Graphik | 800 | 42.1px | 1.15 | -0.02625em | Centered major proof and editorial section headings. |
| heading | Graphik | 800 | 38.3px | 1.15 | -0.02625em | Cheerful closing greeting and smaller section headlines. |
| opening-support | Graphik | 400 | 30.6px | 1.3 | -0.02625em | Two-line statement beneath the opening promise. |
| lead | Graphik | 400 | 23px | 1.3 | -0.01375em | Centered supporting paragraph beneath major section headings. |
| body | Graphik | 400 | 19.1px | 1.5 | -0.01375em | Letters, editorial paragraphs and explanatory link lists. |
| button | Graphik | 500 | 19.1px | 1 | -0.01375em, features "c2sc", "smcp", "ss05" | Main conversion and video labels; small-cap features are enabled without forced uppercase. |
| stat | Graphik | 600 | 19.1px | 1 | -0.01375em | Numbers within proof capsules; adjoining descriptions use weight 400 at the same size. |
| chip-link | Graphik | 500 | 17.2px | 1 | -0.01375em | Dense wraparound footer navigation. |
| nav-action | Graphik | 500 | 15.3px | 1 | -0.01375em, features "c2sc", "smcp", "ss05" | Compact account actions in the top navigation. |
| review | Graphik | 400 italic | 15.3px | 1.3 | -0.01375em | Short centered customer quotations; marked excerpts rise to weight 500. |
| review-credit | Graphik | 600 | 13.4px | 1.5 | -0.01375em | Compact upright attribution beneath italic reviews. |
| stamp-label | Graphik | 600 | 13.4px | 1 | normal, uppercase | Tiny tilted New labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| interior pricing, capability and release pages | interior-title | Graphik | 800 | 49.8px | 1.15 | -0.02625em | Centered title above a focused conversion tool or long illustrated catalog. |
| pricing pages | plan-heading | Graphik | 600 | 25.1px | 1.5 | -0.01375em | Inline plan name and price rather than oversized pricing numerals. |
| capability catalogs and release announcements | feature-copy | Graphik | 400 | 19.1px | 1.3 | -0.01375em | Centered explanatory text beneath a large interface image. |
| pricing and objection handling | question | Graphik | 600 | 19.1px | 1.3 | -0.01375em | Disclosure question text. |

**Notes:**

- Display tracking is almost twice as tight as prose: -0.02625em versus -0.01375em. Weight 800 provides the emphatic hierarchy; do not substitute enormous type for that heft.
- The default opening is smaller and left-aligned; focused interior pages have the larger centered title. Preserve these as different roles.
- Italic reviews contrast with upright semibold credits. Bold and underlined phrases inside prose provide useful reading landmarks.
- Use the listed desktop sizes as the baseline; keep paragraphs materially smaller than the opening support.

## Layout

**Density:** Airy between paper chapters and comfortable within prose; the footer intentionally becomes a dense patchwork.

### Spacing

| Value | Use |
| --- | --- |
| 7.8px | Footer chip row and column gaps. |
| 18.4px | Tight review content separation. |
| 30.6px | Outer page gutters and recurring column-stack gaps. |
| 38.3px | Review column gaps. |
| 46px | Heading-to-media layout gap and medium section separation. |
| 61.3px | Standard paper-card interior padding. |
| 76.6px | Letter side padding. |
| 91.9px | Major section margins and inset section side padding. |
| 122.6px | White-space separation above and below the common footer. |

### Containers and grids

- **inset-canvas**: side padding 30.6px. White exterior gutters frame a pale continuous canvas; its desktop width is 1379px.
- **split-opening**: 2 columns · gap 0px. Equal-width image and explanation halves. The right half has 46px left and 30.6px right padding; the browser view fills nearly the left half.
- **wide-paper**: max width 1195px · side padding 91.9px. Centered media and proof sheets inside the inset canvas; width is the desktop target, not an absolute fixed-width requirement.
- **reading-column**: max width 735px. Centered explanatory paragraphs and list content inside wider paper sheets.
- **review-grid**: 3 columns · gap 38.3px. Compact equal review columns, approximately 317px per review in the default proof sheet.
- **service-pair**: 2 columns · gap 30.6px. Two 582px-wide white cards with video above left-aligned heading and prose.
- **catalog-paper** (only for capability catalogs and release announcements): max width 1011px · side padding 30.6px. Full-width interface image over centered caption, with 61.3px bottom padding.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions-and-paper | 0px |
|  | browser-frame | 9.6px |
|  | stat-capsules | 42.1px |
| event listings | calendar-tile | 7.7px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-paper | `0px 0px 0px 1px rgba(0,0,0,0.02), 0px 6.1px 61.3px -36.8px rgba(0,0,0,0.1), 0px 12.3px 85.8px -42.9px rgba(0,0,0,0.2), 0px 12.3px 36.8px -49px rgba(0,0,0,0.3), 0px 24.5px 49px -67.4px rgba(0,0,0,0.4), 0px 36.8px 61.3px -79.7px rgba(0,0,0,0.5)` | Wide white proof sheets and translucent catalog panels; light outlines with diffuse shadows below, not a visible gray drop-shadow rim. |

### Surfaces

#### Outer paper · level 0

**Use:** Exterior page and shared closing region.

**CSS:** `background: #ffffff; color: #29353c`

#### Blue canvas · level 0

**Use:** Default long-form marketing body.

**CSS:** `background: #f5f9ff; margin-left: 30.6px; margin-right: 30.6px; padding-bottom: 91.9px`

**Observed:** A single continuous pale field connects the floating sections.

**Transfer:** Use it as the default, retaining white outer gutters.

#### Floating sheet · level 1

**Use:** Major proof, editorial and demonstration cards.

**CSS:** `background: #ffffff; border-radius: 0px; box-shadow: 0px 0px 0px 1px rgba(0,0,0,0.02), 0px 6.1px 61.3px -36.8px rgba(0,0,0,0.1), 0px 12.3px 85.8px -42.9px rgba(0,0,0,0.2), 0px 12.3px 36.8px -49px rgba(0,0,0,0.3), 0px 24.5px 49px -67.4px rgba(0,0,0,0.4), 0px 36.8px 61.3px -79.7px rgba(0,0,0,0.5)`

**Observed:** Square-edged white sheets occupy most of the available width, not small rounded bento tiles.

**Transfer:** Group a complete argument or media demonstration on one sheet.

#### Marked phrase

**Use:** Emphasized clauses in customer quotations.

**CSS:** `background: rgba(255,220,116,0.5)`

**Observed:** Highlight follows individual text lines; it is not a full quotation card fill.

**Transfer:** Mark only the outcome-bearing phrase.

#### Lavender canvas · level 0

**Only for:** capability catalogs and release announcements

**Use:** Alternate long illustrated story background.

**CSS:** `background: #fcf7ff`

#### Translucent caption sheet · level 1

**Only for:** capability catalogs and release announcements

**Use:** Image-led feature cards.

**CSS:** `background: rgba(255,255,255,0.4); padding: 0px 30.6px 61.3px; border-radius: 0px`

**Observed:** The Floating sheet shadow is retained; a large interface image meets a very pale caption panel below without a decorative frame.

**Transfer:** Keep the actual working example prominent and the explanation below it.

## Components

### Slim navigation

**Use:** Orient the reader without a full navigation menu.

**CSS:** `display: flex; position: relative; height: 92px; padding: 0px 30.6px; background: #ffffff`

**Observed:** A small centered pictorial product mark is flanked by sign-in on the far left and sign-up on the far right. Interior pages retain the centered mark alone.

**Transfer:** Use a compact original product symbol, keeping the central space unburdened.

### Primary button

**Use:** Newsletter submission and main conversion action.

**CSS:** `background-color: #117af3; background-image: linear-gradient(135deg, #0067de, #146dc7); color: #ffffff; border-radius: 0px; padding: 19.1px 21.1px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Graphik 500 · 19.1px/1 · tracking -0.01375em

**Observed:** A solid rectangular action. Visible height is about 50–52px; the label uses optical negative margins within the padded wrapper. A small original product mark can precede the sticky trial label.

**States:** Declared: hover background-color #0067de and white text; focus-visible outline max(2px, 0.1em) solid #29353c with matching offset.

### Account action

**Use:** Compact sign-up control in the slim navigation.

**CSS:** `background-color: #117af3; background-image: linear-gradient(135deg, #0067de, #146dc7); color: #ffffff; border-radius: 0px; padding: 13.8px 15.3px`

**Text style:** `nav-action` — Graphik 500 · 15.3px/1 · tracking -0.01375em

**Observed:** A small rectangular control opposite a pale-blue sign-in variant. Optical label margins keep the visible height near 37px.

**States:** Declared: hover background-color #0067de; focus-visible ink outline with max(2px, 0.1em) offset; active transform none.

### Directory chip

**Use:** The dense shared footer navigation.

**CSS:** `background: rgba(17,122,243,0.1); color: #146dc7; padding: 10.3px 12.1px 8.6px; border-radius: 0px`

**Text style:** `chip-link` — Graphik 500 · 17.2px/1 · tracking -0.01375em

**Observed:** Content-width rectangles wrap into centered rows rather than categorized columns. A few have a New stamp overlapping the upper-left corner.

**States:** Declared: hover blue background #146dc7 with #f5f9ff text; focus-visible ink outline max(2px, 0.1em) with matching offset.

### New stamp

**Use:** Tiny emphasis on newly relevant directory links.

**CSS:** `background: #008a10; color: #ffffff; padding: 2px 4px; transform: rotate(-7deg)`

**Text style:** `stamp-label` — Graphik 600 · 13.4px/1 · uppercase

**Observed:** Small rectangular stamp sits just above and left of a link, not in the text flow.

### Video label

**Use:** Invite a real demonstration from a still image.

**CSS:** `background: #ffffff; color: #29353c; padding: 19.1px 21.1px 19.1px 46px; position: relative; display: flex; align-items: center; border-radius: 0px`

**Text style:** `button` — Graphik 500 · 19.1px/1 · tracking -0.01375em

**Observed:** Centered over a wide 16:9 poster, with a solid triangular play glyph before the label. Human-service cards instead use a round central play control and a small blue lower-edge name caption.

### Letter sheet

**Use:** A personal statement that explains the problem and earns trust.

**CSS:** `background: #ffffff; padding: 71.8px 76.6px; transform: rotate(-0.8deg); position: relative`

**Text style:** `body` — Graphik 400 · 19.1px/1.5 · tracking -0.01375em

**Observed:** A narrow page of prose on a subtly uneven stack of white sheets, ending with a handwritten signature, small round portrait, name, role and direct contact link.

**Transfer:** Use a credible short signed note; keep the paper stack even when the signature is rendered as a simple typographic name.

### Stat capsule

**Use:** Compact quantified proof below a larger proof visual.

**CSS:** `background: #ffffff; border-radius: 42.1px; padding: 0px 19.1px; height: 42px; color: #29353c`

**Text style:** `stat` — Graphik 600 · 19.1px/1 · tracking -0.01375em

**Observed:** A semibold number precedes a regular description of equal size. Multiple capsules wrap into centered rows with modest gaps and soft shallow shadows.

### FAQ disclosure

**Only for:** pricing and objection handling

**Use:** Answer concrete purchase concerns without a giant text wall.

**CSS:** `display: flex; position: relative; padding: 23px 0px 23px 24.5px; border-bottom: 1px solid rgba(0,0,0,0.075); color: #29353c`

**Text style:** `question` — Graphik 600 · 19.1px/1.3 · tracking -0.01375em

**Observed:** An opening chevron precedes a semibold question in a native disclosure row. Rows sit in a single Floating sheet; paragraphs are revealed beneath the question, not in separate cards.

**States:** Declared: focus-visible ink outline max(2px, 0.1em) with matching offset.

### Plan chooser

**Only for:** pricing pages

**Use:** Compare packages while showing only one detailed offer.

**CSS:** `display: grid; grid-template-columns: auto 1fr; border-radius: 0px`

**Text style:** `plan-heading` — Graphik 600 · 25.1px/1.5 · tracking -0.01375em

**Observed:** A roughly 871px-wide panel has a 308px pale left selector and a 563px white detail pane divided by a faint vertical rule. Five compact radio choices show plan names and limits; the selected row has a pale-blue rectangular highlight and green check. The detail pane puts name and price on one line, then a short summary, Primary button and an inclusion list with green checks and muted exclusions.

**Transfer:** Use a selectable plan list, not five equal tall pricing cards. Keep the price subordinate to the offer.

## Imagery and graphics

### Readable working interface

**Use:** Opening product proof and deeper capability demonstrations.

**Observed:** A real, information-rich browser view rather than an abstract dashboard collage. The opening view is about 659px wide with restrained browser chrome, white content, fine gray edges and a 9.6px frame radius. Deeper views are approximately 1011px wide, often vertically tall, on pale cream or icy-blue interface backings; the explanatory caption sits below.

**Transfer:** Show one coherent workflow with credible sample data. Without finished product media, construct a legible list, calendar or document example with real labels and a few original avatars; keep the broad white layout and restrained color rather than filling it with decorative widgets.

### Stacked paper statement

**Use:** A signature tangible editorial moment in the marketing story.

**Observed:** A white letter sits slightly askew on two pale white sheets with fine diffuse shadows, black conversational prose, blue links and a handwritten sign-off.

**Transfer:** Make a sincere product explanation feel like correspondence rather than another feature grid.

**Build:** Use an approximately 820px reading sheet with 76.6px side padding, transform rotate(-0.8deg), and two absolute white pseudo-element sheets behind it. Offset their top edges by about 10px and rotate them in subtly different directions. Apply very faint black edge rings and downward diffuse shadows; avoid paper textures and torn edges.

### Five-star marked reviews

**Use:** A signature compact social-proof treatment, in a proof sheet or between release chapters.

**Observed:** Five small yellow stars above each centered italic quotation; selected words have translucent yellow highlighting and slightly stronger weight. Small upright semibold attributions finish each review. Three columns sit on white or pale lavender without individual card outlines.

**Transfer:** Use verifiable concise quotations and emphasize a concrete changed outcome. If no customer quotation is available, use clearly labeled testing feedback rather than invented testimonials.

**Build:** Draw five identical five-point SVG stars in a horizontal row approximately 17px tall. Use a warm yellow fill, center the row, leave roughly 15px before the italic text, and wrap only one or two key clauses in mark elements using rgba(255,220,116,0.5). Finish with the review-credit recipe.

### Human video posters

**Use:** Large proof and demonstration sheets plus paired service cards.

**Observed:** Ordinary people in a real office, street or rooftop setting; natural light, everyday clothing and visible surroundings. The wide proof poster reaches edge-to-edge across the white sheet below its heading; a white Video label sits at center. Paired interviews have blue caption strips pinned near the lower edge.

**Transfer:** Film a person using or explaining the new product in a credible environment. A well-lit still with a short recorded walkthrough is sufficient; preserve the unpolished human scale.

### Fine zigzag divider

**Use:** Signature breathing-space ornament between major arguments.

**Observed:** A very pale short horizontal zigzag line with a tiny outlined product mark at its center, surrounded by a 183.8px-high breathing interval.

**Transfer:** Keep the hand-friendly small ornament and ample empty space, using an original simple symbol.

**Build:** Create two SVG paths with repeating 4px rises and falls, using ink at about 13% alpha and a 1px stroke. Separate them around a small central outlined original mark. Center the approximately 390px-wide ornament in a 183.8px-high separator.

### Activity proof map

**Only for:** activity visualizations

**Use:** A single contained dramatic proof graphic.

**Observed:** A dark blue-black rectangular field holds a world silhouette made of subdued dots, with concentrated electric-blue activity clusters and small white location callouts. The white heading and support block remain above it; statistics follow in capsules.

**Transfer:** Use a truthful geographic or process-activity graphic. When geography is irrelevant, retain the small luminous dots on a contained dark field but map them to a labeled process rather than inventing global usage.

**Build:** Place an SVG point grid inside a 1195px by 571px viewBox on #0b151b. Clip low-opacity ink-gray dots to a relevant outline; overlay blue dots in varying sizes and a few slightly blurred blue clusters. Add only factual white callout labels.

### Icons

**Observed:** Small solid ink icons around 20px accompany utility actions and maker credits; a few interface controls use thin round-capped strokes. Play triangles and green inclusion checks are functional rather than an all-purpose feature-icon system.

**Transfer:** Use simple solid symbols for actions and small round check badges for inclusion. Keep illustrated or multicolored icons inside the working-product media rather than scattering them above every marketing paragraph.

## Section recipes

How recurring sections are built.

### First screen: Working product and directory opening

**Observed:** The first 92px is white Slim navigation with a small centered product mark and opposing Account actions. Beneath it the Blue canvas is inset by 30.6px. Two equal halves contain a roughly 659px-wide browser demonstration on the left and an explanatory directory on the right. The directory begins high in the field, pairing bold blue underlined links with regular 19.1px explanations on separate rows; a small tour thumbnail and two-line label follow. Below that list, the weight-800 42.1px opening promise is left aligned and wraps into three lines, followed by two lines of 30.6px regular support. The product view, link stack, tour, headline, support and small example-project link beneath the media are visible inside the first 900px; the letter begins just below the fold. Layers are pale canvas, shadowed white browser, small surrounding example thumbnails and text.

**Transfer:** Keep the useful asymmetry: one convincing working example opposite a compact guide to the product, with the main promise below the guide. Construct a readable workflow example when finished media is unavailable. Focused pricing pages open instead with a centered interior-title and selector panel; capability and release pages use the same centered title over a large leading interface view or video.

**Avoid:** Do not turn this into a centered giant slogan with a decorative dashboard beneath it, or put the directory in a conventional top navigation bar.

**Text style:** `opening-headline` — Graphik 800 · 42.1px/1.1 · tracking -0.02625em

### Personal paper argument

**Observed:** Letter sheet is centered in the pale field, separated by 91.9px of space. Prose remains left aligned at 19.1px/1.5 and contains occasional strong blue links; the signature block closes the note.

**Transfer:** Use the stacked-paper device for a candid note about the reader's problem and the product's approach, without forcing it to be a founder biography.

### Heading and wide demonstration

**Observed:** Floating sheet begins with a centered section-heading, a narrower lead paragraph about 15px below it, and approximately 39px of visible space before full-width 16:9 media. The sheet is approximately 1195px wide and its header has about 69px top padding.

**Transfer:** Give each sheet one question or claim, followed immediately by a human demonstration or specific result.

### Marked review grid

**Observed:** Three-column Five-star marked reviews fill a Floating sheet beneath a centered heavy heading. Compact italic review and semibold credit are separated from the next row by about 30.6px.

**Transfer:** Gather several short, specific outcomes rather than one oversized quotation. The same treatment can interrupt a long release narrative without an enclosing sheet.

### Paired human reassurance

**Observed:** A centered section-heading and lead sit directly on Blue canvas, followed by two white service cards. Each has a 582px by 327px video poster above left-aligned prose, a bold subheading and occasional underlined link.

**Transfer:** Use two complementary reasons to trust the product, supported by real people and practical detail rather than abstract badges.

### Cheerful newsletter and patchwork close

**Observed:** The pale body ends before a generously spaced white region. A 38.3px heavy greeting includes a changing positive adjective, followed by a centered lead with a bold invitation and regular explanatory clause. A 613px-wide email-and-Primary-button form sits below. Directory chips wrap in centered rows with 7.8px gaps, some carrying New stamps. Small inline maker marks and a utility row with a green status dot complete the page; a compact blue trial action stays near the lower-right viewport edge on long marketing stories.

**Transfer:** Preserve the personable greeting, newsletter and rectangular link patchwork on new pages. Adapt the maker credit to the actual organization; keep utilities secondary instead of using a giant closing slogan.

### Image then explanation chapter

**Only for:** capability catalogs and release announcements

**Observed:** A 1011px-wide working interface image leads each Translucent caption sheet on Lavender canvas. Below the image, a centered 38.3px weight-800 heading and 19.1px/1.3 explanation occupy a pale caption block with 61.3px bottom padding. Chapters are separated by 91.9px; images retain their natural variable height.

**Transfer:** Use one capability per chapter and make the picture explain the claim before the paragraph elaborates it. A release story can intersperse compact review strips; a capability catalog can run uninterrupted chapters.

### Live-class listing

**Only for:** event or guided-demo invitations

**Observed:** A Floating sheet pairs a centered heading and explanatory lead with a narrow two-column list of six scheduled sessions. Each item has a 51px calendar tile with a red month cap, large date and adjoining title and time; tiles have a 7.7px radius.

**Transfer:** Offer a small set of genuinely scheduled opportunities; use the calendar tile for dates rather than turning it into a generic icon card.

### Focused pricing and questions

**Only for:** pricing pages

**Observed:** An interior-title and short social-proof line precede Plan chooser. Below are a small demo/contact line, customer proof, separate heading-plus-paper inclusion lists, plain risk-reversal paragraphs and a single Floating sheet of FAQ disclosures.

**Transfer:** Move from deciding a package to understanding inclusions, then remove purchase anxieties with specific answers. Preserve one active offer rather than repeating all details across columns.

## Page flow

**Storyline:** Useful promise and immediate product proof → candid explanation → human and quantified proof → practical reassurance or capability detail → low-pressure invitation and dense helpful close.

### Broad product introduction and trust building

1. **Promise and product demonstration** — Split working-interface opening with linked product guide and substantial plainspoken headline.
2. **Problem recognition** — A signed personal letter on stacked white paper.
3. **Social and practical proof** — Customer video, compact marked reviews, and a real clicked-through demonstration in separate white sheets.
4. **Quantified proof** — Contained dark activity visualization followed by white stat capsules.
5. **Reassurance** — Paired human-service videos and practical explanations.
6. **Invitation and closing** — A live-class invitation precedes the cheerful newsletter and link-patchwork close.

**Transfer:** Let the strongest available evidence determine the balance of demos, reviews and practical reassurance; retain the tangible paper and helpful ending.

### Help a reader choose and feel safe purchasing

1. **Conversion** — Centered title and live proof line above a single selectable pricing panel.
2. **Proof** — Compact endorsement and customer-video invitation.
3. **Value explanation** — Inclusion list and operational trust list on separate white sheets.
4. **Risk reversal** — Plain paragraphs address flexibility, affordability and administrative burden.
5. **Objection handling** — One paper panel of chevron-led disclosure questions.
6. **Closing** — The common greeting, newsletter, chip navigation and maker-credit footer.

**Transfer:** Use the selector to simplify comparison, then address actual commercial terms with straightforward language.

### Explain a substantial release without losing credibility

1. **Announcement** — Centered heavy title, short summary and a large walkthrough video on a lavender field.
2. **Social proof** — Three compact starred reviews introduce the first chapters.
3. **Capability chapters** — Large working examples lead captioned paper panels, with further review strips between groups.
4. **Summary** — A small ornament and broad concluding heading lead two left-aligned paragraphs about the wider improvements.
5. **Closing** — White newsletter and link-patchwork ending, with the compact trial action still present.

**Transfer:** Show visible changes in enough detail to make the release useful; use a concise final synthesis rather than another long feature grid.

### Provide a deep visual catalog of capabilities

1. **Scope and promise** — Centered heavy title and concise explanatory introduction on lavender.
2. **Capability chapters** — A long series of large working-interface images with centered heavy headings and compact descriptions underneath.
3. **Final demonstration** — The final activity example receives the same complete caption treatment as earlier chapters.
4. **Closing** — The lavender field ends and the shared white greeting, newsletter and chip footer follow directly.

**Transfer:** Keep chapters visually consistent and allow image height to follow the actual workflow. No extra sales-summary section is needed before the shared close.

## Writing

Confident, personable and unusually literal about usefulness. It sounds like a capable human explaining what they made, with warmth and occasional opinion, not a sales department inventing a category.

**Do not copy:** Do not reuse Basecamp or affiliated product names, logos, signatures, customer identities, quotations, performance numbers, prices, years in business or subscriber counts. Replace these assets and claims with truthful material belonging to the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you; use we for the people building and supporting the product. Questions acknowledge ordinary frustrations rather than qualifying enterprise buyers.
- **Rhythm:** Headlines range from short emphatic fragments to full conversational questions. Support is usually one to three sentences; body paragraphs can be longer when they explain a real decision. Contractions, em dashes, occasional exclamation marks and short fragments are welcome.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Concrete verbs describe what the product helps the reader accomplish. | 10–16 words | “Manage projects, coordinate teams, and master your company with [Brand].” |
| Demonstration heading | A friendly question invites the reader to see for themselves. | 5–10 words | “How about a quick demonstration?” |
| Supporting line | Disarm sales expectations, then say exactly what is shown. | 15–30 words | “No slides, no sales pitch. Just a real project, clicked through in real time. A wonderful way to get comfortable with [Brand].” |
| Action | Plain verb and clear next step, often naming the commitment. | 2–7 words | “Start a 30-day free trial”<br>“See all upcoming classes” |
| Risk reversal | Name the feared constraint and explain the actual policy. | 6–12 words for the heading | “Risk-free, cancel anytime, no long-term lock-in” |
| Closing greeting | A small human wish rather than a final hard sell. | 4–6 words | “Have a terrific day!” |

**Words and phrasing to use:** straightforward; easy-to-use; real; just; here for you; no sales pitch; simple; show you; things; you’re in control

**Avoid:** synergize; unlock unprecedented potential; enterprise-grade transformation; revolutionary ecosystem; seamless solutions

**Rules:**

- Pair each benefit with the visible action or concrete situation that makes it believable.
- Use specific policy language for risk reversal; do not conceal terms behind reassurance.
- Let headings ask the reader's ordinary questions, including objections.
- Explain capabilities in human language before introducing acronyms.
- Use proof numbers only when they can be substantiated, and keep them part of sentences rather than monumental isolated numerals.

## Do's and Don'ts

### Do

- Keep the default body field #f5f9ff with 30.6px white outer gutters.
- Set major headings in weight 800 with -0.02625em tracking, not a light geometric display cut.
- Preserve the opening's nearly equal image and explanation halves.
- Keep primary actions rectangular at 0px radius, with blue fills and white weight-500 labels.
- Use 91.9px major intervals to separate whole paper arguments.
- Include the slightly askew paper statement and pale zigzag ornament as tangible signature devices.
- Render proof capsules with inline 19.1px numbers and equal-size descriptions.
- Keep the ending link patchwork compact at 17.2px type and 7.8px gaps.

### Don't

- Do not spread the dark visualization backing into an overall dark marketing theme.
- Do not use pill shapes for conversion buttons; the rounded capsule belongs to compact statistics.
- Do not round every white sheet into a 24px bento card.
- Do not flood full sections with saturated action blue; the pale canvas and white sheets dominate.
- Do not magnify prices into display-sized isolated numerals; plan titles and prices share a 25.1px line.
- Do not make every review a bordered card or replace compact italic quotations with huge quotation marks.
- Do not add a separate icon tile above every feature; the working interface is the primary explanation.
- Do not turn blue link chips into widely spaced footer columns; their dense centered wrapping is characteristic.

## Motion and responsive

### Motion

**Observed:**

- Declared action color and background transitions use 0.15s ease; link text-decoration-color changes also use 0.15s ease.
- Blue actions declare a pointer-centered radial white glow at 10% alpha, spanning an 8em circle.
- The theme control declares an active scale of 0.9; navigation account buttons explicitly keep transform none on hover and active.
- The closing greeting's positive adjective changes while the fixed words remain in place.

**Transfer:**

- Keep pointer effects local to blue actions rather than adding ambient glow behind the page.
- Preserve the stable paper reading surface; use the small changing greeting as the playful motion accent.

**Unknown:**

- The greeting's timing, sequence and easing are not specified.
- Continuous activity visualization behavior and scroll-trigger mechanics are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 360px, 375px, 399px, 400px, 432px, 480px, 568px, 576px, 768px, 1023px and 1024px.
- Review layout declares auto-fit columns with a 287.2px minimum.

**Transfer:**

- On narrower layouts, prioritize the working example and keep the linked guide readable rather than squeezing both opening halves.
- Allow review columns and footer chips to wrap naturally; retain their compact typography and rectangular treatment.
- Reduce paper side padding before compressing readable prose; keep interface images at a legible scale with intentional framing.

**Unknown:**

- Exact narrow-screen ordering, gutters and type scaling are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
