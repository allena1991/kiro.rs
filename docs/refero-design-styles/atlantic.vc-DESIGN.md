# Atlantic — signals from the unknown

## Overview

An expansive, almost nocturnal identity with electric blue signals cutting through black space. Regular grotesk typography, tiny monospaced markings and particulate terrain give ambitious technology a scientific but human atmosphere. Natural portraits and documentary photographs interrupt the abstraction, while sparse layouts and short, conviction-led statements keep the experience closer to a manifesto than a dashboard.

### Essentials

- A single sentence floats inside a field of blue particles: the default opening is a 900px-tall black stage with a centered 96px/1 Monument headline, weight 400, -0.03em tracking, and one blue phrase.
- Headlines behave like separated coordinates: 96px words span the content width beneath distributed 14px uppercase mono labels with 2.2px tracking; 64px statements reconnect the words into longer thoughts.
- Color is a signal, not a coat of paint: black and #0d0d0f occupy nearly all structural surfaces, #d8eaff carries text, #1f58f2 marks selected words and graphic lines, and #ff4105 is confined to small actions and icons.
- Actions are compact rectangular instruments: 35px height, 4px corners, 16px horizontal padding, uppercase 14px mono text and an 8px gap before a tiny arrow; default in-content actions use a translucent pale-blue fill, while the header action is orange.
- Framing feels plotted rather than boxed: 1px rules, 8px blue square registration nodes and open black interiors organize logos and prose. Photography uses 16px corners and broad black gutters instead of enclosing whole stories in cards.
- Atmosphere has two scales: a grainy blue terrain fills the opening and returns inside a square media window; a 960×540px blue light with 80px blur underlights a 24px-rounded dark chapter panel. Use generated particle contours when there is no suitable product film.
- The ending is a destination, not a link directory: a full-height contact stage centers a 96px closing word and small action amid blue rays fading toward the center, with social and address details on opposite sides and legal links along the bottom.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal blue | `#1f58f2` | `--color-blue` | text, accent | Selected headline phrases, particles, rays and registration squares. |
| Ice blue | `#d8eaff` | `--color-text` | text | Headlines, labels, navigation and high-priority copy. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action orange | `#ff4105` | `--color-orange` | action, accent, link | Header action fill, active navigation, arrows, plus signs and quotation marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Absolute black | `#000000` | `--color-canvas` | background | Primary page canvas and open media backing. |
| Night panel | `#0d0d0f` | `--color-panel` | surface | Inset long-form chapter panel. |
| Smoked ice | `#111314` | `--color-button` | surface, action | Visible ice blue at 8% on black; translucent content-button backing. |
| Low-light rule | `#16171a` | `--color-soft-rule` | border | Visible ice blue at 10% on black, for thin chapter separators. |
| Dark edge | `#232529` | `--color-edge` | border | Footer, expandable directory and proof-panel boundaries. |
| Ice rule | `#2b2f33` | `--color-rule` | border, surface | Visible ice blue at 20% on black, used for accordion rules and underlying media backing. |
| Logo lattice edge | `#565657` | `--color-logo-rule` | border | The brighter grid lines around the logo lattice. |
| Dim ice | `#6c7580` | `--color-muted` | text | Supporting paragraphs; the visible result of ice blue at 50% on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| cinematic campaign pages | Campaign red | `#e70026` | `--color-red` | accent, action | Campaign action fill, pixel fields, comparative data and isolated contrasting words. |
| cinematic campaign pages | Film white | `#ffffff` | `--color-white` | text | Headlines and quotations over the cinematic campaign treatment. |

## Typography

- **Monument** — Display statements, body paragraphs, names and story headlines. Regular neo-grotesk with clean construction and tightly joined large words. If unavailable, use **Inter**. Use weight 400 and retain the negative tracking; balance line breaks rather than increasing weight. Font stack: "Monument", "Inter", Arial, sans-serif.
- **Mono** — Navigation, eyebrows, metadata, compact actions and technical captions. Utilitarian monospaced capitals with conspicuous letter spacing in labels. If unavailable, use **IBM Plex Mono**. Use weight 400; preserve the separate navigation, label and button tracking recipes. Font stack: "Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Monument | 400 | 96px | 1 | -0.03em | fixed | Opening statement, distributed section headlines and closing contact word. |
| statement | Monument | 400 | 64px | 1.06 | -0.03em | fixed | Multi-line declarations, testimonial introductions and large numerical proof. |
| body | Monument | 400 | 24px | 1.24 | -0.03em | fixed | Support lines, story titles, testimonial text and directory names. Supporting copy uses dim ice; primary statements use ice blue. |
| eyebrow | Mono | 400 | 14px | 1 | 0.16em, uppercase | fixed | Distributed section labels, categories and dates. |
| button | Mono | 400 | 14px | 0.8 | 0.06em, uppercase | fixed | Compact rectangular actions. |
| navigation | Mono | 400 | 12px | 1.5 | normal, uppercase | fixed | Header navigation links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| cinematic campaign pages | campaign-display | Monument | 400 | 108px | 1.06 | -0.015em, uppercase | size 7.5vw | Split two-line title across cinematic media. |
| cinematic campaign pages | campaign-quote | Monument | 400 | 40px | 1.24 | -0.03em | fixed | Extended expert quotations beside a small square portrait. |
| FAQ sections | question | Monument | 400 | 28px | 1.24 | -0.01em | fixed | Expandable FAQ question text. |
| cinematic campaign pages | campaign-subtitle | Mono | 400 | 27px | 1 | 0.083em, uppercase | size 1.875vw | Centered campaign descriptor below the film title. |
| long-form explanation and data sections | detail | Monument | 400 | 16px | 1.46 | -0.01em | fixed | Compact descriptive text in expertise rows and source captions. |
| editorial pagination and attribution | micro | Mono | 400 | 10px | 1 | 0.16em, uppercase | fixed | Numbered carousel tabs and small external-site captions. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- All principal typography stays at weight 400, including blue emphasis. Emphasis changes color, not weight.
- The 96px display and 64px statement share -0.03em tracking. The smaller 28px and 16px explanatory roles loosen to -0.01em.
- Distributed headline words are separated by layout, not by inserting spaces into the text. Preserve readable semantic sentences.
- Use ice-blue text rather than pure white in the default look; reserve white for the film-led campaign variant.

## Layout

**Density:** Airy at the page scale, with 200px chapter gaps and compact 35px actions; paragraphs and captions remain closely grouped.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Button icon gap and registration-square dimension. |
| 12px | Tight stacked metadata and name details. |
| 16px | Action side padding, paired-action gap and number-to-caption gap. |
| 24px | FAQ vertical padding and featured-story text spacing. |
| 32px | Eyebrow-to-heading, media-to-caption and navigation gaps. |
| 50px | Desktop page gutters and separation of adjacent explanation rows. |
| 80px | Distributed heading-to-support gap. |
| 100px | Section heading-to-media and major internal chapter gaps. |
| 110px | Horizontal inset inside the dark chapter panel. |
| 150px | Dark-panel vertical padding and editorial-section vertical padding. |
| 200px | Principal page chapter separation. |
| 250px | Vertical breathing room around campaign manifesto statements. |

### Containers and grids

- **content frame**: max width 1345px · side padding 50px. Centered marketing content; at 1440px the visible content is 1340px wide, with the maximum limiting wider windows.
- **hero sentence**: max width 880px. Compact centered sentence in the full-height particle stage.
- **support column**: max width 655px. Balanced center-aligned support paragraphs beneath distributed headings.
- **story grid**: max width 1345px · 3 columns · gap 32px. Three equal grid tracks with 345px-wide stories aligned left, center and right; the resulting visual gaps are about 152px, larger than the declared grid gap.
- **logo proof split**: 2 columns · gap 0px. Equal-width outer halves; the left half contains a three-column by two-row logo lattice and the right half a single centered action.
- **chapter interior**: max width 1120px · gap 100px. Interior of the dark chapter panel, with square art on the left and a narrower stack of labelled paragraphs on the right.
- **people directory** (only for people and organization pages): max width 538px. Right-side expandable names balanced against small category labels in the left half.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | actions | 4px |
|  | media and proof cards | 16px |
|  | chapter panel | 24px |
| editorial pagination | numbered tabs | 8px |

## Surfaces and depth

### Surfaces

#### Black canvas · level 0

**Use:** Default foundation for the entire page.

**CSS:** `background: #000000; color: #d8eaff`

**Observed:** Content is usually laid directly on the canvas, leaving broad untouched black intervals.

**Transfer:** Use open space to separate chapters rather than alternating many filled bands.

#### Dark chapter panel · level 1

**Use:** A substantial explanation chapter inside the black page.

**CSS:** `background: #0d0d0f; border-radius: 24px; padding: 150px 110px`

**Observed:** Inset by the page gutters; holds distributed headings, a thin rule, abstract art and labelled text. A low blue underlight extends below the panel.

**Transfer:** Keep it as one large narrative enclosure rather than a collection of small feature cards.

#### Smoked action backing · level 1

**Use:** Default in-content action surface.

**CSS:** `background: rgba(216,234,255,0.08); border-radius: 4px; backdrop-filter: blur(8px)`

**Observed:** A shallow translucent rectangle, not a conspicuously frosted glass slab.

**Transfer:** Keep the backing dark enough that the mono label and orange arrow remain the strongest details.

#### Underlight · level 0

**Use:** Atmosphere beneath the dark chapter panel.

**CSS:** `background: linear-gradient(rgba(31,88,242,0.2), rgba(31,88,242,0.2)); width: 960px; height: 540px; filter: blur(80px); border-radius: 40.8px`

**Observed:** Centered behind the lower edge so only a subdued blue pool escapes onto black.

**Transfer:** Keep the light behind the panel, not over text or across the entire canvas.

#### Open ruled frame · level 1

**Use:** Logo-proof lattice and registration-style content boundaries.

**CSS:** `background: #000000; border: 1px solid #565657`

**Observed:** Square corners and open interiors; blue square nodes mark selected intersections. Explanatory variants use the darker edge color.

**Transfer:** Use line geometry to suggest a plotted framework rather than raised card depth.

#### Proof tile · level 1

**Only for:** extended numerical proof chapters

**Use:** Individual statistic within a larger ray-field scene.

**CSS:** `background: #000000; border: 1px solid #232529; border-radius: 16px`

**Observed:** The opaque black tile interrupts the lines behind it. Black-to-transparent fades sit inside each edge.

**Transfer:** Keep the statistic legible and the surrounding graphic subordinate.

## Components

### Fixed navigation

**Use:** Persistent page navigation above every visual theme.

**CSS:** `position: fixed; top: 32px; display: flex; align-items: center; gap: 32px; color: #d8eaff`

**Text style:** `navigation` — Mono 400 · 12px/1.5 · uppercase

**Observed:** A compact pale wordmark anchors the left, followed by horizontal links. The selected link is orange; the filled action is pushed to the far right. The mark can condense into a square emblem after the opening.

**Transfer:** Use the new identity's wordmark and compact emblem while retaining the low-height navigation silhouette.

### Signal button

**Use:** High-priority header action.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 35px; padding: 0px 16px; border-radius: 4px; background: #ff4105; color: #d8eaff`

**Text style:** `button` — Mono 400 · 14px/0.8 · tracking 0.06em · uppercase

**Observed:** The label precedes a tiny right arrow. Campaign treatment changes the fill to red and can use status text rather than an invitation.

**States:** Declared: focus-visible outline-style none and transparent box-shadow; the backing uses an active scale of 0.95.

**Transfer:** Reserve the filled action for one priority rather than coloring every link.

### Smoked button

**Use:** Default in-content navigation or secondary conversion.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 35px; padding: 0px 16px; border-radius: 4px; background: rgba(216,234,255,0.08); backdrop-filter: blur(8px); color: #d8eaff`

**Text style:** `button` — Mono 400 · 14px/0.8 · tracking 0.06em · uppercase

**Observed:** A pale label ends with an orange arrow. The outlined sibling replaces the fill with a 1px ice-blue-at-20% border; paired actions sit side by side.

**States:** Declared: focus-visible outline-style none and transparent box-shadow; the backing uses an active scale of 0.95.

### Story card

**Use:** Editorial proof, announcements and updates.

**CSS:** `display: flex; flex-direction: column; gap: 32px; max-width: 345px; color: #d8eaff`

**Text style:** `body` — Monument 400 · 24px/1.24 · tracking -0.03em

**Observed:** Portrait-oriented media comes first in a 345×450px window with 16px corners. Below it, a blue square and uppercase category sit opposite a date; a title begins with a blue entity name followed by an ice-blue dash and description. The whole story has no filled enclosing card.

**Transfer:** Use a concrete development or outcome as the title, not a generic feature name.

### Logo lattice tile

**Use:** Compact visual proof inside the Open ruled frame.

**CSS:** `position: relative; height: 260px; border-right: 1px solid #565657; border-bottom: 1px solid #565657`

**Observed:** Each 223px-wide cell centers a restrained pale logo on black. Six cells share one half of the larger split frame. Small blue nodes appear on outer corners.

**Transfer:** Use partner, integration or customer marks; keep their visual sizes comparable and their treatment monochrome.

### Contact stage

**Use:** The closing conversion and utility footer.

**CSS:** `position: relative; background: #000000; border-top: 1px solid #232529; overflow: clip; height: 900px; color: #d8eaff`

**Text style:** `display` — Monument 400 · 96px/1 · tracking -0.03em

**Observed:** Ray-field artwork fills the stage behind a centered eyebrow, closing word and Smoked button. Small social links sit left and a dim address sits right, while the legal line hugs the lower edge.

**Transfer:** Keep a single invitation as the focal point; adapt side details to the new business without converting the stage into a sitemap.

### FAQ row

**Only for:** FAQ sections

**Use:** Objection handling without a card stack.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 24px 0px; border-top: 1px solid rgba(216,234,255,0.2); color: #d8eaff`

**Text style:** `question` — Monument 400 · 28px/1.24 · tracking -0.01em

**Observed:** One question spans most of the row with a tiny orange plus at the far edge. Closed rows are about 84px tall and the list ends with a matching bottom rule. Open answers use the body recipe.

**Transfer:** Keep questions plainly phrased and the entire row interactive.

### People row

**Only for:** people and organization pages

**Use:** Expandable person directory grouped by role.

**CSS:** `display: flex; align-items: center; justify-content: space-between; padding: 16px; border-bottom: 1px solid #232529; color: #d8eaff`

**Text style:** `body` — Monument 400 · 24px/1.24 · tracking -0.03em

**Observed:** A name sits left and a 10px orange plus right. Rows are 538px wide and about 63px tall; the group category sits remotely in the left column instead of above each name.

### Statistic tile

**Only for:** extended numerical proof chapters

**Use:** One large fact within a spatial proof sequence.

**CSS:** `display: flex; flex-direction: column; align-items: center; justify-content: center; width: 335px; height: 335px; gap: 16px; background: #000000; border: 1px solid #232529; border-radius: 16px; text-align: center`

**Text style:** `statement` — Monument 400 · 64px/1.06 · tracking -0.03em

**Observed:** A single large number sits above a short uppercase mono caption. Tiles alternate between left and right positions around a persistent central graphic rather than making a conventional dense dashboard.

**Transfer:** Use genuinely comparable, verified facts with compact explanatory captions.

### Numbered tabs

**Only for:** editorial pagination

**Use:** Featured-story carousel selection.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 30px; height: 30px; border-radius: 8px; background: rgba(216,234,255,0.08); color: #d8eaff`

**Text style:** `micro` — Mono 400 · 10px/1 · tracking 0.16em · uppercase

**Observed:** Three tabs sit together with 4px gaps; the selected numeral is orange.

**States:** Declared: hover background-color color-mix(in oklab,#d8eaff20%,transparent); focus-visible outline-style none and transparent box-shadow.

## Imagery and graphics

### Particulate terrain

**Use:** Full-bleed opening atmosphere and a square reprise in the explanation chapter.

**Observed:** Dense cobalt pinpoints trace irregular folded ridges, almost like a topographic scan or turbulent cloth. Vast black cavities remain between ribbons. The hero field covers the viewport behind the sentence and fades to black at the lower edge; the interior version is a 488px square with rounded corners.

**Transfer:** Generate a bespoke field that evokes the new product's complexity. The minimum version is an irregular blue point-cloud terrain on black, not a generic smooth gradient or an empty media window.

**Build:** Render an SVG or canvas field of sub-2px blue points. Start with multiple broad, winding contour ribbons, perturb each contour with layered noise, and scatter points densely along the ribbons while leaving deep empty valleys. Use signal blue with varied alpha, a black backing, and a transparent-to-black vertical mask over the bottom 250px. Reuse a tighter square window of the same field inside the chapter.

### Ray field

**Use:** Signature contact-stage artwork and the expanded numerical-proof scene.

**Observed:** Long straight blue spokes extend from a hidden central convergence toward offscreen endpoints. Their inner ends dissolve into black, leaving a calm readable void around the content. The lines are crisp rather than luminous tubes.

**Transfer:** Retain the radial, outward-directed energy behind the closing invitation. For a proof scene, center an original compact geometric emblem rather than using a literal product image.

**Build:** Use a full-width SVG with 8–10 radial paths from near the center to well beyond the edges, mixing shallow lateral directions with steeper downward and upper-diagonal directions. Give paths a 4–6px blue stroke at desktop and mask them with a black central ellipse fading into white outward. Keep the text and opaque statistic tiles above the SVG; do not add a glowing halo to each line.

### Natural people photography

**Use:** Human testimony and editorial proof.

**Observed:** Square founder portraits in a horizontally clipped carousel, with the selected center portrait brighter and side portraits dimmed. Editorial stories mix natural color portraits, workshop scenes, event photographs and technology imagery inside portrait windows. Faces remain recognizable; no universal duotone is imposed.

**Transfer:** Photograph actual users or builders in believable working environments. Use natural skin tones and documentary lighting to contrast the synthetic blue graphics.

### Wide documentary carousel

**Only for:** people and culture pages

**Use:** A visual closing chapter before the contact stage.

**Observed:** Large 1100×620px documentary photographs show architecture, gatherings and working environments. A neighboring slide peeks in beyond the right edge; small square pagination indicators sit beneath with a 50px gap.

**Transfer:** Show the physical context of the new team or community, retaining wide frames and edge-peeking motion rather than small headshot tiles.

### Chromatic campaign film

**Only for:** cinematic campaign pages

**Use:** A film-led opening and featured editorial banner.

**Observed:** A silhouetted person in profile wearing protective eyewear is surrounded by drifting blue, violet and pink-red smoke. The film fills the opening behind white uppercase type, then fades into black. A wide featured-story window uses the same saturated photographic atmosphere.

**Transfer:** Create a new cinematic scene tied to the offering, with a dark human or object silhouette against colored vapor or light; retain readable white type and a dark lower fade.

### Pixel fields and data

**Only for:** cinematic campaign pages

**Use:** Comparative data and a centered campaign offer.

**Observed:** Blue and red rectangular cells form jagged rising plotted regions and separate maze-like patches. The offer has a blue patch above and a red patch below, both fading into black; data endpoints are labelled in matching color.

**Transfer:** Use discrete rectangular marks to express a real comparison or abstract structure. Keep explanatory text and sources outside the pixel mass.

**Build:** Construct an SVG on an 18px cell grid, joining adjacent colored cells into stepped islands. Use blue and red layers with deliberate black holes and no rounded corners. For an offer, place two roughly 335px-wide patches above and below the text and mask their distant edges into black. For data, map occupied cells to actual values and add thin neutral horizontal guides.

### Icons

**Observed:** Tiny orange directional arrows and plus signs, typically 7–11px, accompany actions, expandable rows and external links. A 36×36px orange outlined scroll control sits near the hero bottom. Blue 8×8px squares act as registration marks; larger sparse blue starbursts echo the ray motif.

**Transfer:** Choose crisp simple arrows and plus signs with no decorative badge. Use the blue square as a structural marker, not a conventional round bullet.

## Section recipes

How recurring sections are built.

### First screen: Particle-stage opening

**Observed:** The first 900px are a full-height black stage: particle terrain fills the back, a black lower fade controls contrast, and Fixed navigation floats above it near the top. A short centered sentence in the display recipe spans about two fifths of the screen width, sitting at the visual midpoint. Most words are ice blue and the final identity word is signal blue without extra weight. The terrain is the main object; there is no separate device mockup, support paragraph or central CTA. The Signal button sits in the header and the outlined 36px scroll control near the bottom. The next narrative chapter falls below the fold after a 200px interval.

**Transfer:** Write a brief identity or promise statement and generate a distinctive particle field if no product film exists. People and explanation pages use a two-line centered statement with a small eyebrow on the same stage. Editorial listings instead open with a distributed heading and wide featured image; film-led campaigns use the scoped uppercase title treatment.

**Avoid:** Do not turn the opening into a conventional left-copy/right-mockup composition, add a dense support paragraph, or place a stack of conversion buttons over the center.

**Text style:** `display` — Monument 400 · 96px/1 · tracking -0.03em

### Distributed heading

**Observed:** Small mono words are spread across the content frame as a complete phrase. After 32px, the headline is split into two or three far-separated 96px words, with the key word blue. A centered dim support paragraph up to 655px wide follows after 80px.

**Transfer:** Choose short headline words that remain meaningful when read across the width; use the distributed labels as a secondary phrase, not random decorative text.

**Text style:** `display` — Monument 400 · 96px/1 · tracking -0.03em

### Lattice proof

**Observed:** Below a Distributed heading, the Open ruled frame splits into equal halves. Logo lattice tiles fill the left half in three columns and two rows; the right half centers a Smoked button amid mostly black space. Registration nodes punctuate the outer frame.

**Transfer:** Adapt to credible partner or integration proof; retain the contrast between repeated small marks and one uncluttered invitation.

### Human testimony carousel

**Observed:** A 64px statement with selected blue phrases and a sparse blue starburst leads into an overflow-clipped row of square portraits. The central 425px portrait is fully lit while neighboring roughly 404px portraits are dimmed. An orange quote mark, body-sized testimonial, name and small site attribution sit beneath the active image; square slide markers finish the section.

**Transfer:** Use first-person testimony with a clear human face and keep peripheral content partially visible to establish the horizontal sequence.

**Text style:** `statement` — Monument 400 · 64px/1.06 · tracking -0.03em

### Underlit explanation chapter

**Observed:** The Dark chapter panel contains a Distributed heading, centered support copy and a thin rule with blue end nodes. Below, Particulate terrain sits on the left while three generously separated labelled paragraphs sit on the right; labels begin with blue squares and fine rules. A Smoked button follows the last paragraph. Underlight escapes beneath the panel.

**Transfer:** Organize the offering's rationale, method and audience into short labelled passages; retain the large singular panel and recurring abstract field rather than illustrating every paragraph separately.

### Editorial grid

**Observed:** A Distributed heading leads to Story cards arranged in three widely spaced columns. The leading image is 345×450px; image, metadata and title stay visually distinct. A centered Smoked button and outlined sibling can follow after 100px. Editorial listings add a featured 1340×754px image, Numbered tabs, category-filter row and multiple rows of stories.

**Transfer:** Use this for outcomes, releases or case studies. Keep image crops consistent even when source subjects vary.

### Ray-field closing invitation

**Observed:** Contact stage ends every page with a full-height black composition. The center stack contains a blue-square eyebrow, a monumental single word and a Smoked button; social information stays near the left edge and address information near the right. Sparse blue rays escape from the calm central void to the viewport edges. Copyright and compact utility links align along the bottom.

**Transfer:** Make the last screen a direct, human invitation. Preserve the radial artwork and central word even if side utilities are minimal.

**Text style:** `display` — Monument 400 · 96px/1 · tracking -0.03em

### Expertise row

**Only for:** long-form explanation pages

**Observed:** A small upper-left category label interrupts the top edge of a 1340px-wide ruled frame. Each roughly 325px-tall row divides evenly: a centered 345px text column on the left and a horizontal strip of pale partner logos on the right. The strip fades and blurs toward its edges. Blue squares mark corners and the center division; rows have 50px separation.

**Transfer:** Pair a compact capability explanation with credible examples or integrations, retaining the half-text half-proof composition.

### Spatial numerical proof

**Only for:** extended numerical proof chapters

**Observed:** A full-width Ray field supports a central compact emblem and small two-part caption. Statistic tiles alternate at generous vertical intervals to its left and right; individual numbers use the 64px statement recipe and captions use the eyebrow recipe. The section has dark top and bottom rules.

**Transfer:** Use this immersive format for a few important facts rather than a dense KPI grid. Create an original center emblem and let each fact have its own reading moment.

### Objection chapter

**Only for:** FAQ sections

**Observed:** A centered display-sized heading and dim body support line introduce full-width FAQ rows. The introduction is padded by 150px vertically at the section level. A short title remains one line while a longer conversational title wraps into a narrow centered stack.

**Transfer:** Use honest questions that remove uncertainty after the main story; add a compact supporting action only when it resolves a remaining practical need.

### People directory and invitation

**Only for:** people and organization pages

**Observed:** A two-line 64px blue-emphasis statement precedes a Distributed heading and grouped People rows, with remote category labels on the left. A centered statement and Smoked button lead into the Wide documentary carousel before the contact stage.

**Transfer:** Present people as readable names grouped by function rather than defaulting to a wall of headshot cards.

### Film manifesto and offer

**Only for:** cinematic campaign pages

**Observed:** The film opening splits a 108px uppercase title across two rows with blue and red rectangular interruptions and a centered 27px mono descriptor. Later, a narrow 680px manifesto uses 64px type with blue and red words, followed by comparative pixel data, 40px portrait quotations and a centered offer framed by Pixel fields and data.

**Transfer:** Use for a focused launch or initiative with one offer, preserving the tension between cinematic color and austere black editorial chapters.

## Page flow

**Storyline:** Identity → evidence of possibility → human conviction → explanation of method → current proof → direct invitation; longer narratives add quantified proof and objections.

### Broad brand or product introduction

1. **Identity** — Particle-stage opening establishes one short identity sentence.
2. **Social proof** — Distributed heading introduces a split logo lattice.
3. **Human proof** — Portrait carousel connects the promise to real voices.
4. **Method** — Underlit explanation chapter organizes the rationale and audience.
5. **Current proof** — Editorial grid demonstrates momentum.
6. **Closing call** — Ray-field closing invitation completes the page.

**Transfer:** Balance abstract ambition with credible people and concrete developments; adapt the blocks to the offering rather than preserving a fixed section count.

### Editorial discovery and updates

1. **Editorial promise** — Distributed heading and wide featured image with numbered tabs.
2. **Discovery** — Category filters and small external-resource links precede the grid.
3. **Evidence** — Three-column story grid continues across several rows.
4. **Continuation** — Centered compact load-more action.
5. **Closing call** — Ray-field closing invitation.

**Transfer:** Let images and titles carry the archive, with very little interface chrome.

### Focused initiative or campaign conversion

1. **Promise** — Cinematic film with split uppercase title and compact status action.
2. **Rationale** — Narrow large-type manifesto frames a problem and opportunity.
3. **Quantified proof** — Blue and red pixel data makes the comparison tangible.
4. **Human conviction** — Two extended portrait quotations lend authority.
5. **Offer** — Centered value proposition between fading pixel patches.
6. **Objection handling** — FAQ list and practical supporting action.
7. **Closing call** — Ray-field closing invitation.

**Transfer:** Use a distinct campaign color and film treatment without changing the regular-weight typography, black chapters or common ending.

### People, organization and recruitment

1. **Promise** — Particle stage with a centered people-oriented statement.
2. **Belief** — Large centered statement connects people to the mission.
3. **Human proof** — Distributed heading and categorized expandable name directory.
4. **Invitation** — Large statement and compact recruitment action.
5. **Context** — Wide documentary carousel reveals the lived environment.
6. **Closing call** — Ray-field closing invitation.

**Transfer:** Use the directory for discoverability and the photography for atmosphere, rather than asking portraits to perform both jobs.

### Detailed explanation of a method or offering

1. **Positioning** — Particle stage states a compact positioning line.
2. **Method** — Underlit panel combines a distributed title, manifesto and supporting paragraphs.
3. **Capabilities** — Centered statement introduces repeated half-text half-logo expertise rows.
4. **Quantified proof** — Immersive ray-field chapter alternates statistic tiles around a central emblem.
5. **Evidence invitation** — Large centered statement directs readers toward examples.
6. **Objection handling** — Extended FAQ list addresses practical questions.
7. **Closing call** — Ray-field closing invitation.

**Transfer:** Use a longer reading arc when the offering needs explanation; maintain discrete chapters and contrast between technical detail and monumental statements.

## Writing

Confident, curious and conviction-led, with a taste for the unexplored rather than the merely fashionable. Grand ambitions are grounded in direct commitments, specific developments and human testimony.

**Do not copy:** Do not reuse Atlantic's name, wordmark, emblem, portfolio identities, program names, proprietary claims, investment figures, dates, contact details or attributed quotations. Source examples illustrate cadence only.

- **Addressing the reader:** The organization speaks as we. It addresses builders and potential partners directly with you when offering reassurance or inviting action; editorial titles name the subject plainly.
- **Rhythm:** Short identity statements and two-to-five-word section headings alternate with longer, flowing declarative sentences. Supporting paragraphs are usually a few sentences; rhetorical contrasts and occasional questions provide energy without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A compact declaration of identity or position, with the defining phrase emphasized by color. | 3–9 words | “We are [Brand]”<br>“First-round investor on the edge” |
| Section headline | Short directional phrase with a deliberate tension or refusal. | 2–5 words | “Into the Unknown”<br>“No ‘Too Early’” |
| Supporting line | Concrete commitment followed by a more expansive horizon. | 20–45 words | “We write the first cheque for people building technologies on the edge of the impossible.” |
| Action | Plain verb or destination, no sales pressure. | 2–5 words | “Our approach”<br>“Explore roles”<br>“See More” |
| Question | Reader's practical uncertainty stated conversationally. | 4–12 words | “When is the right time to reach out for an investment?” |

**Words and phrasing to use:** build; back; edge; unknown; conviction; from the start; what comes next; breakthrough

**Avoid:** revolutionary solution; unlock your potential; game-changing platform; seamless ecosystem; act now; guaranteed success

**Rules:**

- State what the organization actually does before expanding into future-facing language.
- Use contrast to make a belief memorable: familiar versus unknown, early versus inevitable.
- Let blue emphasize the meaningful clause; write sentences that still read naturally without color.
- Keep metadata factual and concise; reserve manifesto language for display statements.
- Use authentic first-person quotations and precise achievements to counterbalance abstract ambition.

## Do's and Don'ts

### Do

- Keep 96px display statements regular-weight with -0.03em tracking.
- Make the 14px mono eyebrow a separate visual layer with 2.2px tracking.
- Preserve 50px desktop outer gutters and 200px chapter breathing room.
- Repeat blue 8px square nodes at selected rules and frame intersections.
- Use 35px rectangular actions with 4px corners and tiny trailing arrows.
- Give editorial images 16px corners without adding a filled enclosing card.
- Include both a particulate atmosphere and the radial closing artwork, with an underlit dark chapter as a secondary atmospheric device.
- Keep natural portraits in color so the people contrast with the synthetic blue fields.

### Don't

- Do not make blue emphasis bold; weight 400 is integral to the voice.
- Do not replace near-black panels with light gray cards or white page bands.
- Do not spread the orange action color across large section backgrounds.
- Do not use pill buttons or 48px-tall default controls in place of the compact rectangles.
- Do not tighten the editorial columns into a dense equal-gap card wall; cards are 345px wide within widely spaced tracks.
- Do not substitute glowing neon tubes for the crisp fading blue spokes.
- Do not use soft circular bullets where blue registration squares belong.
- Do not promote the campaign red, white uppercase type or colored smoke into the default marketing theme.

## Motion and responsive

### Motion

**Observed:**

- Declared marquee animation runs for 30s, linearly and infinitely on repeated moving strips.
- Action backings declare transform transitions of .15s cubic-bezier(.4,0,.2,1); active backings scale to 0.95.
- Color transitions include .15s and 0.3s cubic-bezier(.4,0,.2,1); numbered tabs use 0.2s with the same curve.
- Blur-fade, page-entry and page-exit keyframes are named; text and logo strips use layered fading treatments.

**Transfer:**

- Keep the particle field and ray artwork visually meaningful when static; motion should enrich these devices rather than substitute for them.
- Use the 30s linear marquee for repeated proof marks and maintain edge fades.
- For accessible implementation, add a visible keyboard focus treatment rather than relying on the visually empty declared outline state.

**Unknown:**

- Exact particle animation, scroll choreography, ray rotations and text-reveal durations are not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px, 1280px and 1536px.
- Opening heading classes pair a 54px base with the 96px desktop recipe; statement headings pair 40px with 64px.
- Support text pairs 16px with 24px. Dark chapter panels pair 33px horizontal and 100px vertical padding with the desktop 110px and 150px.
- Full navigation links and header action are desktop-only at the 1024px breakpoint; story grids declare one column before the three-column desktop treatment.

**Transfer:**

- On narrower screens, keep the particle field edge-to-edge, wrap the centered sentence and retain the bottom scroll cue.
- Stack chapter artwork above explanatory paragraphs; use the declared compact padding rather than shrinking the artwork into a thumbnail.
- Retain side-peeking slides for photographic carousels, and stack distributed heading words when width would make the sentence unreadable.

**Unknown:**

- Mobile menu construction, exact narrow-screen gutters and fully rendered mobile compositions are unspecified; stacking guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
