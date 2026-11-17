# Lattice — pastel-powered human ambition

## Overview

A bright, people-centered software style that gives serious business tools a friendly, optimistic presence. Deep green grotesk typography sits on white and warm ivory, with mint, lilac and sherbet-colored product stages. Rounded interface vignettes, candid people photography and compact proof cards balance spacious section composition with information-rich content.

### Essentials

- Headlines feel closely knitted rather than heavy: Matter 500, 72.2px/0.9 with -0.024em tracking for the opening and 46.9px/0.9 for section titles.
- The opening pairs a plainspoken promise with a luminous product theater: a 541px text column opposite a 628×433px rounded stage, followed by a low-contrast eight-logo strip.
- Conversion controls are soft rectangles, not capsules: 13px corners, 13px 26px padding, forest-green primary and mint secondary; the opening primary has a thin iridescent under-edge.
- Color lives around useful objects: most of the page remains white or ivory, pastel media and capability cards carry local color, and isolated inset bands carry saturated violet or luminous mint. Preserve at least one large luminous stage and a pastel card grouping.
- Interface imagery is edited into approachable miniatures: white rounded windows float over pastel washes, with 7.2px outer card insets and 14.4px media corners; use a few legible workflow fragments when a full interface is unavailable.
- Proof feels human and specific: pair portraits and short quotes with a separated metric, then give the closing invitation its own 866px white panel inside a 43.3px-radius luminous band.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Green-black ink | `#001f1f` | `--color-ink` | text | Default headings and primary copy; also the source hue for translucent edges and gray washes. |
| Forest green | `#046645` | `--color-action` | action, text | Primary button fill, secondary button text and highlighted organizational metrics. |
| Action mint | `#cdface` | `--color-mint` | action, surface, text | Secondary buttons, section pills and primary button text. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Leaf label ink | `#366625` | `--color-pill-ink` | text | Text inside green section pills. |
| Announcement lavender | `#d9adff` | `--color-lavender` | background, accent | Slim announcement strip; full canvas only in the editorial campaign variant. |
| Aubergine | `#3d1866` | `--color-purple-ink` | text, border, surface | Announcement text; campaign typography, rules and gated-report backdrop. |
| Electric violet | `#624ee5` | `--color-violet` | background, accent | Isolated ecosystem band and product-update accents; not the default page canvas. |
| Washed turquoise | `#caf5ef` | `--color-turquoise-card` | surface | Visible capability-card wash: #b1f0e7 with a 32% white overlay. |
| Washed lime | `#f4f8de` | `--color-lime-card` | surface | Visible capability-card wash: #eff5ce with a 32% white overlay. |
| Washed pink | `#feedff` | `--color-pink-card` | surface | Visible capability-card wash: #fde5ff with a 32% white overlay. |
| Washed yellow | `#fff7d6` | `--color-yellow-card` | surface | Visible capability-card wash: #fff3c2 with a 32% white overlay. |
| Pill lilac | `#ecdcfa` | `--color-lilac` | surface | AI section pills and alternate campaign actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Opening canvas, cards, interface frames and reversed text. |
| Warm white | `#faf9f7` | `--color-warm-canvas` | background | Middle stops of the long page gradient, returning to white at the ends. |
| Ivory band | `#f7f6f2` | `--color-ivory` | background, surface | Large inset chapter backings. |
| Light gray wash | `#f5f6f6` | `--color-wash` | surface | Visible result of green-black at 4% over white; closed question rows. |
| Green-gray hairline | `#ebeded` | `--color-edge` | border | Visible result of green-black at 8% over white; card outlines and dividing rules. |
| Muted green-gray | `#6a7878` | `--color-muted` | text | Footer labels, supporting metadata and inactive question text. |
| Secondary green-gray | `#455252` | `--color-body` | text, link | Card descriptions, navigation and footer links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| editorial campaigns | Report statistic purple | `#652ea3` | `--color-report-stat` | text | Editorial statistic figures. |
| editorial campaigns | Report statistic tint | `#f8f0ff` | `--color-report-tint` | surface | Editorial statistic cells. |
| searchable story catalogs | Control border | `#c4cccc` | `--color-filter-edge` | border | Checkbox outlines in browsing filters. |

## Typography

- **Matter** — All marketing headings, body copy, labels and controls. Friendly contemporary grotesk with circular bowls and open, unforced lowercase; medium rather than bold display weight. If unavailable, use **Inter**. Use 400 and 500; retain tight display tracking and check line breaks. Font stack: "Matter", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Matter | 500 | 72.2px | 0.9 | -0.024em | Default opening promise and monumental company headings. |
| heading | Matter | 500 | 46.9px | 0.9 | -0.024em | Section titles and closing invitation. |
| lead | Matter | 400 | 21.7px | 1.3 | normal | Opening support, chapter introductions and closing support. |
| card-heading | Matter | 500 | 21.7px | 1.1 | -0.024em | Capability and resource card titles. |
| card-body | Matter | 400 | 16.2px | 1.3 | normal | Compact card descriptions. |
| button | Matter | 500 | 16.2px | 1.2 | normal | Main paired conversion actions. |
| pill | Matter | 500 | 14.4px | 1 | normal | Sentence-case section links with circular arrows. |
| navigation | Matter | 500 | 14.4px | 1.3 | normal | Navigation and announcement text. |
| footer-link | Matter | 500 | 12.6px | 1.3 | normal | Dense footer navigation lists. |
| eyebrow | Matter | 500 | 10.8px | 1.3 | 0.08em, uppercase | Small resource tags and footer group labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial campaigns | editorial-heading | Matter | 400 | 72.2px | 0.9 | -0.024em | Wide editorial chapter headlines. |
| focused product landing pages | product-display | Matter | 500 | 57.8px | 1 | -0.024em | More compact opening for a single product capability. |
| editorial campaigns | editorial-stat | Matter | 400 | 57.8px | 1 | -0.04em | Large percentages in divided editorial callouts. |
| company scale and organizational proof | highlight-stat | Matter | 500 | 46.9px | 1.3 | -0.024em | Green figures on mint highlighter tabs. |
| customer-story catalogs | photo-stat | Matter | 500 | 28.9px | 1 | normal | White metrics at the lower edge of story photography. |
| resource and story grids | article-heading | Matter | 500 | 18px | 1.1 | -0.024em | Longer article and customer-story titles. |
| product FAQs | question | Matter | 500 | 18px | 1.3 | normal | Accordion question labels. |
| product FAQs | answer | Matter | 400 | 18px | 1.4 | normal | Expanded accordion answers. |
| editorial campaigns and dated product updates | editorial-label | Matter | 500 | 12.6px | 1.3 | 0.08em, uppercase | Newsbar actions and editorial labels. |

**Notes:**

- The default display and section headings share -0.024em tracking and tight 0.9 line height. Do not substitute a bold weight to obtain their visual impact.
- Paragraphs reset tracking to normal and open to 1.3 line height. More sustained answers use 1.4; longer editorial prose uses 1.5.
- Sentence-case navigation pills and tiny uppercase tags are separate roles, not interchangeable labels.

## Layout

**Density:** Airy at section level, compact inside cards; broad chapter breathing room surrounds short tightly arranged descriptions.

### Spacing

**Spacing system:**

- **rhythm** 7.2px — Primary spacing step; 14.4px, 21.7px and 28.9px are two, three and four steps.

| Value | Use |
| --- | --- |
| 7.2px | Outer inset on white media cards and small content gaps. |
| 14.4px (2 × 7.2px) | Card-grid gutters, media-to-content spacing and standard inner text inset. |
| 21.7px (3 × 7.2px) | Capability grid gutters and support-to-action separation. |
| 28.9px (4 × 7.2px) | Container side padding, capability-card content padding and major text gaps. |
| 43.3px (6 × 7.2px) | Split heading gaps, media-stage padding and heading-to-media separation. |
| 57.8px (8 × 7.2px) | Closing white panel padding. |
| 72.2px | Standard section vertical padding; ten rhythm steps. |
| 101.1px | Feature chapter top padding; fourteen rhythm steps. |
| 115.5px | Large band padding; sixteen rhythm steps. |

### Containers and grids

- **main container**: max width 1299px · side padding 28.9px. Centered desktop wrapper; at a 1440px viewport the actual content spans roughly 1242px with 99px visual side margins.
- **opening split**: 2 columns · gap 72.2px. 541px maximum text column and a wider 628px media stage; text aligns left rather than to the stage center.
- **heading pair**: 2 columns · gap 43.3px. Broad left heading paired with a narrower right paragraph aligned to the bottom of the heading block.
- **four cards**: 4 columns · gap 14.4px. Equal 300px cards for supporting capabilities, resources and location choices.
- **capability mosaic**: 3 columns · gap 21.7px. One card spans two columns in the top row; remaining cards use single columns.
- **centered prose**: max width 758px. Centered company openings and large chapter introductions.
- **inset band**: max width 1660px · side padding 14.4px. Nearly full-window panels with a narrow outer white gutter.
- **story catalog** (only for searchable story catalogs): 2 columns · gap 14.4px. Two 457px story cards beside a 271px sticky filter rail, separated from it by 43.3px.

## Corner radius

| Element | Radius |
| --- | --- |
| conversion buttons | 13px |
| cards | 21.7px |
| media and questions | 14.4px |
| large bands | 43.3px |
| closing inner panel | 28.9px |
| section pills | 28.9px |
| arrow discs | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card lift | `0px 12px 12px -6px rgba(0,31,31,0.04), 0px 6px 6px -3px rgba(0,31,31,0.04), 0px 3px 3px -1.5px rgba(0,31,31,0.04), 0px 1px 1px -0.5px rgba(0,31,31,0.08), 0px 0px 0px 1px rgba(0,31,31,0.04)` | Subtle stacked contact shadows and an almost invisible perimeter on standard white cards. |

### Surfaces

#### Long ivory canvas · level 0

**Use:** Default marketing-page foundation.

**CSS:** `background: linear-gradient(#ffffff, #faf9f7 33%, #faf9f7 66%, #ffffff)`

**Observed:** The long middle quietly warms while the opening and footer remain white.

**Transfer:** Keep the change gradual across the document, not as a striped section background.

#### White media card · level 1

**Use:** Reusable supporting content.

**CSS:** `background: #ffffff; border-radius: 21.7px; padding: 7.2px; box-shadow: 0px 12px 12px -6px rgba(0,31,31,0.04), 0px 6px 6px -3px rgba(0,31,31,0.04), 0px 3px 3px -1.5px rgba(0,31,31,0.04), 0px 1px 1px -0.5px rgba(0,31,31,0.08), 0px 0px 0px 1px rgba(0,31,31,0.04)`

**Observed:** Media occupies the upper area, with a smaller independent radius; text is nested farther inward.

**Transfer:** Use equal shell geometry even when image subjects differ.

#### Ivory chapter band · level 0

**Use:** Oversized demonstration or trust chapters.

**CSS:** `background: #f7f6f2; border-radius: 43.3px; padding: 101.1px 0px 115.5px`

**Observed:** Inset from the viewport and sometimes covered by soft pastel illumination.

**Transfer:** Keep neutral backing under the light rather than switching the entire page theme.

#### Turquoise capability wash · level 1

**Use:** Largest capability card.

**CSS:** `background: #caf5ef; border-radius: 21.7px; overflow: hidden`

**Observed:** Companion cards use washed lime, pink, yellow and mint; a faint tinted rim fades down the image area.

**Transfer:** Assign a different pale wash to each capability, not a different component system.

#### Violet ecosystem band · level 0

**Use:** A concentrated, high-energy chapter.

**CSS:** `background: #624ee5; border-radius: 43.3px; padding: 72.2px 0px 101.1px; color: #ffffff`

**Observed:** White centered headline above a horizontal procession of app symbols, with moving violet light in the background.

**Transfer:** Use for connected tools, partners or a similarly broad ecosystem.

#### Luminous closing stage · level 0

**Use:** Signature conversion framing.

**CSS:** `background: radial-gradient(ellipse at 95% 90%, rgba(205,250,206,1), rgba(205,250,206,0) 65%), radial-gradient(ellipse at 10% 100%, rgba(217,173,255,0.4), rgba(217,173,255,0) 65%), #f7f6f2; border-radius: 43.3px; padding: 115.5px 0px`

**Observed:** A broad mint-cyan light field surrounds a white centered panel; the bottom edge carries brighter lime and cyan light.

**Transfer:** Match the soft glow and luminous lower rim; exact light stops are not essential.

#### Editorial paper · level 0

**Only for:** editorial campaigns

**Use:** Publication-like research storytelling.

**CSS:** `background: #d9adff; color: #3d1866`

**Observed:** Fine grain over lavender, torn or folded white paper chapters, thin purple rules and green paper stickers.

**Transfer:** Create a tactile publication variant rather than applying grain to ordinary product cards.

#### Update glass · level 1

**Only for:** product changelogs

**Use:** Short dated release notes.

**CSS:** `background: linear-gradient(to top, #ffffff, rgba(255,255,255,0.64)); border-radius: 21.7px; padding: 7.2px`

**Observed:** Three translucent white cards sit over a violet-to-pink band with a faint square grid and separate dates below.

**Transfer:** Reserve the grid and glass combination for a time-based update chapter.

## Components

### Navigation

**Use:** Persistent global orientation.

**CSS:** `background: #ffffff; border-bottom: 1px solid rgba(0,31,31,0.08); height: 65px; position: sticky; z-index: 1000`

**Text style:** `navigation` — Matter 500 · 14.4px/1.3

**Observed:** Logo left; compact central links; account link and smaller forest-green conversion control right. Dropdown chevrons are tiny and subdued.

**States:** Declared: hover links use warm-white backing and ink text; focus-visible uses a 3px outline in green-black at 4%.

### Primary button

**Use:** Main conversion.

**CSS:** `background: #046645; color: #cdface; border-radius: 13px; padding: 13px 26px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Matter 500 · 16.2px/1.2

**Observed:** Paired with a mint secondary. The opening version has an iridescent rim beneath its lower edge; the navigation version is smaller, with 11.6px corners.

**States:** Declared: hover translates the opening button down 0.08em; active translates it down 0.24em; focus-visible uses a 2px solid green-black outline at 8%. Other main-action instances use perspective(1200px) with translateZ(16px) on hover and -16px on active.

**Transfer:** Keep one strong action and one lower-commitment route.

### Secondary button

**Use:** Tour or exploratory alternative.

**CSS:** `background: #cdface; color: #046645; border-radius: 13px; padding: 13px 26px`

**Text style:** `button` — Matter 500 · 16.2px/1.2

**Observed:** Same size and text treatment as the main action, without the iridescent edge.

**States:** Declared: hover uses perspective(1200px) translateZ(16px) perspective(1200px); focus-visible uses a 2px solid green-black outline at 8%; active reverses depth to -16px.

### Section pill

**Use:** Linking section label.

**CSS:** `display: flex; align-items: center; gap: 8.7px; background: #cdface; color: #366625; border-radius: 28.9px; padding: 8.7px 8.7px 8.7px 17.3px`

**Text style:** `pill` — Matter 500 · 14.4px/1

**Observed:** Sentence-case text followed by a darker mint circular arrow. Lilac is the AI variant; neutral gray is used for tertiary links.

**States:** Declared: hover moves the arrow through its clipped disc; focus-visible uses a 2px solid green-black outline at 8%; active scales the pill to 0.97.

### Media card

**Use:** Supporting capabilities and resources.

**CSS:** `display: flex; flex-direction: column; gap: 7.2px; background: #ffffff; border-radius: 21.7px; padding: 7.2px; overflow: hidden`

**Text style:** `card-heading` — Matter 500 · 21.7px/1.1 · tracking -0.024em

**Observed:** Pastel illustration or UI vignette first; title and circular arrow share a line; a short description follows. Text gets another 14.4px horizontal inset. Add the card-lift shadow. Article variants use article-heading and wide photography.

**States:** Declared: hover uses perspective(1200px) translateZ(8px) with a deeper shadow; focus-visible uses a 2px green-black outline at 8%.

### Capability tile

**Use:** A high-level product map.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #caf5ef; border-radius: 21.7px; overflow: hidden`

**Text style:** `card-heading` — Matter 500 · 21.7px/1.1 · tracking -0.024em

**Observed:** Small line icon and title at top left, arrow at top right; concise benefit below; enlarged UI fragment anchors the bottom. The lead tile spans two columns.

**Transfer:** Make each card about one useful outcome and use the pastel companion fills.

### Footer link

**Use:** Dense grouped navigation.

**CSS:** `display: block; padding: 3.6px 0px; color: #455252`

**Text style:** `footer-link` — Matter 500 · 12.6px/1.3

**Observed:** Four widely spaced columns, each containing several labeled groups; 28.9px separates groups. Tiny novelty tags sit inline. A hairline separates the legal row and four gray social squares.

**States:** Declared: hover changes to ink and translates 0.2em; focus-visible changes to ink with a 2px green-black outline at 8%.

### Closing invitation panel

**Use:** Conversion with reassurance.

**CSS:** `background: #ffffff; border-radius: 28.9px; padding: 57.8px; max-width: 866.3px; display: flex; flex-direction: column; align-items: center`

**Text style:** `heading` — Matter 500 · 46.9px/0.9 · tracking -0.024em

**Observed:** Inside Luminous closing stage: ratings and award marks first, then a centered two-line invitation, one support sentence and paired Primary button / Secondary button.

**Transfer:** Replace award marks with verified trust evidence of a similar footprint; preserve the inset white panel.

### FAQ row

**Only for:** product FAQs

**Use:** Resolve practical product objections.

**CSS:** `background: rgba(0,31,31,0.04); border-radius: 14.4px; position: relative`

**Text style:** `question` — Matter 500 · 18px/1.3

**Observed:** A details/summary construction. Summary padding is 21.7px top/bottom, 28.9px left and 57.8px right; plus sits at the right. Open rows become white with card-lift shadow, a minus and answer text.

**States:** Declared: hover turns the question to ink; focus-visible uses a 4px green-black outline at 8%.

### Catalog search

**Only for:** searchable story catalogs

**Use:** Find relevant stories in a long grid.

**CSS:** `background: #ffffff; border: 1px solid rgba(0,31,31,0.08); border-radius: 14.4px; padding: 14.4px; height: 51px`

**Observed:** Search icon right; a sticky stack of filter groups below uses 44px summaries, checkbox lists, dashed dividers and a subdued result count.

**Transfer:** Reuse the soft input shell and narrow rail only where the collection needs actual filtering.

### Editorial newsbar

**Only for:** editorial campaigns

**Use:** Publication framing and repeated report action.

**CSS:** `background: #ecdcfa; border: 1px solid #3d1866; padding: 14.4px 68.6px 14.4px 21.7px; color: #3d1866`

**Text style:** `editorial-label` — Matter 500 · 12.6px/1.3 · tracking 0.08em · uppercase

**Observed:** A square-ended action segment sits at the right of a full-width outlined horizontal rule, with a dark square lock cell. A small slogan anchors the left.

**Transfer:** Use at both the publication opening and closing.

### Highlighter statistic

**Only for:** company scale and organizational proof

**Use:** Turn a small set of organization facts into a visual proof stack.

**CSS:** `background: #cdface; color: #046645; border-radius: 10.8px; padding: 0px 14.1px`

**Text style:** `highlight-stat` — Matter 500 · 46.9px/1.3 · tracking -0.024em

**Observed:** Each number is a snug mint tab near the upper left of a wider white card, with an explanatory label below; three cards stack beside a text column.

**Transfer:** Use independently verifiable quantities with short noun labels, not decorative random numbers.

## Imagery and graphics

### Luminous product theater

**Use:** Signature opening media and large product demonstrations.

**Observed:** A roughly 628×433px pastel stage encloses a 541×311px white-rimmed film or interface window. Mint, cyan, pale yellow and lilac light mix behind it; the hero film has white radial streaks and a small dark subtitle plaque.

**Transfer:** Show an original workflow clip or three layered interface fragments with one clear central result. The minimum equivalent is a crisp white product window on a luminous pastel field.

**Build:** Use a 43.3px-radius clipped outer stage. Layer broad radial gradients in mint at lower left, cyan at upper right and lilac near center; blur the color layers about 60px. Center a white window with 21.7px corners, a 7.2px white rim and subtle contact shadow. For a film poster, add 8–12 tapered white SVG streaks radiating away from a central symbol; keep them behind the central content.

### Workflow miniatures

**Use:** Capability tiles and supporting cards.

**Observed:** Floating white snippets show a feedback response, a small chart, a meeting agenda or a suggestion. Media regions are typically 285×228px in compact cards, with pastel light that fades toward the text area.

**Transfer:** Design a handful of convincing, readable product states rather than shrinking a full dashboard beyond recognition.

**Build:** Place two or three white rounded rectangles with thin gray-green edges on a vertical pastel-to-white gradient. Use one emphasized control, a short text line, a tiny avatar or a simple chart. Keep the lower text region white and visually separate.

### Human proof cards

**Use:** Testimonials and story links.

**Observed:** Large pale mint and cyan cards carry a slightly rotated, white-bordered portrait with a small overlapping company badge. Below the identity line, a quote occupies the left and a large metric the right, separated by a faint vertical rule. Neighboring cards peek in from both edges.

**Transfer:** Use authentic people and attributed quotes. When portraits are unavailable, use a verified identity badge in the same small footprint, not a generic stock face.

### Resource illustrations

**Use:** Compact education and support cards.

**Observed:** Simple outlined book, cap, conversation and ticket symbols float centrally over turquoise, pink, lime and lilac gradients fading toward white.

**Transfer:** Draw one simple category symbol per card, avoiding a full illustrated scene.

**Build:** Use a 285×143px backing with 14.4px corners and a vertical pastel-to-white gradient. Center a 48px outline SVG using rounded strokes and a darker relative of the backing hue.

### Luminous edge and grid

**Use:** Signature color energy in inset bands.

**Observed:** The closing band has a soft mint-cyan field with brighter color along its base. Update bands use violet and pink with a faint square grid, while the ecosystem chapter uses richer violet light.

**Transfer:** Preserve one emphatic luminous band in a new marketing page; its location can follow the story rather than a fixed section sequence.

**Build:** Layer two or three large blurred radial gradients behind content, contained by 43.3px corners. Add a narrow brighter cyan/lime radial layer along the lower boundary. For an update-only variant, overlay 1px white lines at low alpha in a 48px repeating grid and mask the grid outward with a radial gradient.

### People photography

**Only for:** company and customer-story pages

**Use:** Company narrative, customer cards and culture bands.

**Observed:** Natural workplace scenes and team groups retain their real color; profile photos have warm direct expressions and alternating pale pastel backdrops. Company leaders are framed as large square portraits; the story opening uses six narrow 195×273px portraits with bottom name overlays. A culture strip runs edge to edge with softened ends.

**Transfer:** Use real collaborators and varied, believable work settings. Keep portraits consistently framed while allowing clothing and skin tones to supply contrast.

### Editorial paper graphics

**Only for:** editorial campaigns

**Use:** Research publication identity and chapter punctuation.

**Observed:** The opening is a monumental, narrow, irregular serif title graphic in dark purple, stacked within a 902×457px area on grainy lavender. Small italic words and a year interrupt the large lettering. Mint paper stickers, curled corners, handwritten underlines, fold lines and torn white edges continue the print metaphor. The ending restates the title in a single wide strip.

**Transfer:** Create an original publication title lockup using a condensed expressive serif, keeping supporting text in Matter. Carry the same title treatment into the final action rather than ending with a standard marketing footer.

**Build:** Create the title as SVG text converted to outlines or an original typographic illustration. Use a condensed serif such as Instrument Serif as a starting point, vary individual word scale, and add fine SVG turbulence at very low opacity. Add four 58px corner registration brackets, a 1px purple newsbar, mint skewed paper rectangles with an offset outline, and a white chapter edge made from a shallow irregular polygon.

### Icons

**Observed:** Utility and capability symbols use 1.5px rounded strokes in 18–24px boxes. Direction arrows sit inside 23–28px circular pastel or gray discs. Close marks use a 14px box and 2px square-ended strokes.

**Transfer:** Choose restrained rounded line icons and tinted arrow discs; keep filled brand marks confined to partner, trust and identity content.

## Section recipes

How recurring sections are built.

### First screen: Split luminous opening

**Observed:** The first screen starts with a 33px lavender announcement strip and a 65px white Navigation. A centered main container begins 72.2px below it. The left column holds a three-line display promise within 541px, followed by 28.9px of space, a three-line lead paragraph and paired actions separated from support by 21.7px. The right half is the Luminous product theater, 628×433px, whose top aligns with the composition rather than the first letter. White canvas is behind both; pastel illumination sits behind a smaller white-rimmed film window. An eight-logo gray strip runs across the bottom. Within the first 900px, the full promise, support, actions, main object, logos and the next section's label are visible; the capability grid falls below.

**Transfer:** Use a succinct two- or three-line promise and an original product scene. Without film, stage one convincing product result and two supporting fragments on the luminous field. Focused product pages use product-display and a breadcrumb with a denser UI scene. Company pages center display text over a video still; story collections center display text over a narrow portrait row; editorial campaigns replace the split with a full-width publication lockup.

**Avoid:** Do not replace the media stage with an unframed dashboard, a full-bleed stock photograph or an abstract glow with no useful object. Do not center the default opening copy.

**Text style:** `display` — Matter 500 · 72.2px/0.9 · tracking -0.024em

### Split section introduction

**Observed:** Section pill above a heading on the left; lead copy and an underlined text link occupy the right, aligned to the heading's lower edge. The heading pair has a 43.3px gap and 36.1px before the following card group.

**Transfer:** State the benefit on the left and explain the mechanism on the right.

**Text style:** `heading` — Matter 500 · 46.9px/0.9 · tracking -0.024em

### Pastel capability mosaic

**Observed:** Capability tile grouping uses a three-column grid with 21.7px gutters: the main tile spans two columns, with single-column companions. Titles and benefits remain at the top while product fragments fill the lower portion.

**Transfer:** Give the most important capability more surface area, retaining the common pastel and corner system.

### Centered demonstration chapter

**Observed:** Ivory chapter band holds a centered Section pill, a two-line heading within 758px, lead support and a large isolated interface illustration about 650px wide. Soft lilac and cyan illumination spreads around the demonstration.

**Transfer:** Use one focused product behavior and enough vertical room for the object to read as a feature, not another small card.

### Human metric carousel

**Observed:** A left-aligned section title introduces a horizontal strip of Human proof cards. Two substantial cards are readable while the neighbors extend beyond the viewport. Pagination uses 14px neutral dots with an active mint capsule around 43px wide.

**Transfer:** Pair each customer voice with one concrete outcome and link to the underlying story; keep quote and metric visually distinct.

### Connected ecosystem

**Observed:** Violet ecosystem band centers a pill, white heading and support over a single horizontal row of app symbols.

**Transfer:** Use recognizable integration or partner marks in a restrained repeated procession, not a dense directory.

### Proof-framed closing and footer

**Observed:** Luminous closing stage contains Closing invitation panel, with verified rating marks above the heading and paired actions below. After 72.2px of separation, the footer uses a top hairline, 72.2px top padding, four compact navigation columns, and a second rule above legal copy and social squares. Product and story pages share this ending.

**Transfer:** End ordinary marketing pages with the luminous proof-and-action device. For company recruiting, the location-card invitation takes its place; editorial campaigns end with the wide publication title, repeated Editorial newsbar action and a minimal white legal/social strip.

### Product chapter rail

**Only for:** focused product landing pages

**Observed:** An ivory-to-white inset chapter places a persistent heading, explanation and five-item capability rail on the left. A vertical stack of 663px-wide white cards sits on the right; each includes a 632px-wide UI scene, short title, description and occasional pill action. Thin vertical rail marks connect the labels.

**Transfer:** Map each label to a real product behavior and corresponding detailed scene; adapt the number of chapters to the product.

### Product updates and questions

**Only for:** focused product landing pages

**Observed:** A luminous grid-backed update band holds three translucent release cards with dates beneath. Later, a one-third-width FAQ heading faces a two-thirds-width stack of FAQ rows with 14.4px gaps; the first answer is open.

**Transfer:** Use release evidence to make the product feel maintained, then handle genuine buying questions rather than repeating feature slogans.

### Story discovery

**Only for:** searchable story catalogs

**Observed:** A centered display opening with a six-portrait row precedes gray logos. The browsing chapter combines Catalog search and a sticky 271px filter rail with two-column Media cards. Photographs are 442×232px; white photo-stat text sits over a bottom dark-green gradient, above category chips and an article-heading title. A neutral Load more pill follows the collection.

**Transfer:** Lead with the people behind the outcomes, then enable practical discovery by customer type or problem.

### Company credibility

**Only for:** company pages

**Observed:** Centered mission opening with a single green-gradient word and a 744×418px video still. A split text-and-Highlighter statistic chapter precedes three-column square portrait cards, compact leadership rows and an ivory four-column award grid. Centered investor prose and grayscale logos give way to a candid photo strip. The ending is a centered recruiting invitation over four illustrated location cards, then the ordinary footer.

**Transfer:** Move from belief to scale, people, external validation and participation. Use truthful company-specific material rather than generic corporate abstractions.

### Publication chapters and gate

**Only for:** editorial campaigns

**Observed:** Grainy lavender surrounds a large serif title graphic and Editorial newsbar. Editorial-heading titles introduce white paper chapters with two columns of prose and charts, green highlighted drop caps, handwritten emphasis and dotted purple dividers. Three pale statistic cells use editorial-stat figures. A deep-purple gridded chapter centers a 541px white form sheet. Later come testimonial cards, methodology and a white product-context chapter with rectangular mint and lilac actions.

**Transfer:** Let the report's central finding drive the display words, diagrams and excerpts. The gate should feel like a sheet within a publication, not a rounded product card.

## Page flow

**Storyline:** Promise → tangible product behavior → human or quantitative proof → deeper capability and ecosystem context → useful next steps → reassured invitation.

### Broad platform marketing

1. **promise** — Split luminous opening and muted customer logos.
2. **capability overview** — Pastel capability mosaic and a centered demonstration chapter.
3. **daily use** — Four compact workflow cards.
4. **social proof** — Human metric carousel.
5. **ecosystem and education** — Violet connected-tools band and four resource cards.
6. **closing call** — Proof-framed luminous invitation and grouped footer.

**Transfer:** Start broad and make the product concrete before expanding into trust and supporting resources.

### Focused product landing

1. **promise** — Compact split opening with breadcrumb and layered UI.
2. **product demonstration** — Persistent chapter rail beside five detailed scenes.
3. **platform context** — Four related capability cards.
4. **social proof** — Human metric carousel.
5. **freshness and education** — Dated glass update cards and article grid.
6. **objection handling** — FAQ heading beside accordion rows.
7. **closing call** — Shared luminous invitation and four-column footer.

**Transfer:** Spend more space explaining behavior and answering questions than on a broad platform page.

### Browse customer outcomes

1. **human introduction** — Centered headline, portrait lineup and gray logos.
2. **searchable proof** — Sticky filters beside a long two-column photographic story grid with overlaid metrics.
3. **collection continuation** — Subdued Load more pill.
4. **closing call** — Shared proof-framed invitation and ordinary footer.

**Transfer:** Make a long evidence library useful through filters, consistent cards and real outcome summaries.

### Research-led campaign and report conversion

1. **publication identity** — Oversized serif artwork on lavender and outlined action newsbar.
2. **central tension** — Short editorial introduction and three findings.
3. **evidence** — White paper chapter with prose, charts, quotes and divided statistics.
4. **conversion gate** — Centered white form sheet on deep-purple grid.
5. **validation and context** — Testimonials, methodology and product-context chapter.
6. **closing call** — Wide publication title, repeated newsbar and minimal legal/social ending.

**Transfer:** Create a self-contained editorial world and repeat the publication identity at the end rather than using the standard marketing sitemap.

### Company story and participation

1. **mission** — Centered display with one green-gradient word above workplace film.
2. **scale proof** — Three highlighter metric cards beside an explanation.
3. **people** — Large leadership portraits and smaller identity cards.
4. **external validation** — Award grid, investor prose and muted logo strip.
5. **culture** — Edge-to-edge candid photo strip.
6. **participation** — Recruiting invitation and four location cards before the ordinary footer.

**Transfer:** Let real people and independent validation carry the company story; close on a way to participate.

## Writing

Optimistic, practical and people-first, with business confidence grounded in everyday work. Headlines make clear promises; supporting copy explains how the tools help without sounding clinical.

**Do not copy:** Do not reuse the Lattice name, logo, proprietary artwork, customer identities, testimonials, report identity, rankings, customer counts, review scores or numerical outcomes. Replace all examples and claims with independently supported content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address teams and readers as you or your; the product is a practical partner. Company storytelling shifts to we and our without losing specificity.
- **Rhythm:** Usually 4–10 words in a headline, often with two balanced clauses. Support is one substantial sentence; cards use short titles and a single compact explanation. Editorial chapters permit longer, more opinionated paragraphs.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Join human ambition to a simple product promise. | 4–9 words | “People + AI: Succeeding Together”<br>“The AI agent built for HR teams” |
| Section headline | Use parallel verbs or a concrete outcome rather than a technical category. | 5–11 words | “Integrate everything. Align everyone.”<br>“Build high performance through everyday habits” |
| Support | Explain the daily behavior and resulting benefit in plain terms. | 15–40 words | “Turn daily moments like 1:1s, Updates, and Feedback into clarity and alignment that boost performance.” |
| Action | Verb plus a tangible next step; distinguish sales contact from exploration. | 3–5 words | “Request a demo”<br>“Take a product tour”<br>“Read the story” |
| Story title | Name the organization, transformation and result. | 10–18 words | “How PandaDoc Rebuilt Engagement by Empowering Managers with [Brand]” |
| Editorial thesis | State a tension between expectation and reality. | 7–12 words | “HR’s mandate is expanding faster than its support.” |

**Words and phrasing to use:** together; grow; lead; clarity; alignment; everyday; trusted; potential; meaningful; built for; in the flow of work

**Avoid:** revolutionary disruption; supercharge everything; autonomous magic; frictionless synergy; guaranteed transformation

**Rules:**

- Tie abstract benefits to familiar actions, not just capability names.
- Use paired clauses sparingly to create memorable section headlines.
- Present a metric with its unit, context and attribution, not as a floating sales claim.
- Keep actions explicit: request, take, learn, read, explore.
- Use warm invitations in company copy and sharper evidence-led claims in editorial writing.

## Do's and Don'ts

### Do

- Keep display weight at 500 and preserve the 0.9 headline line height.
- Retain the 72.2px section rhythm and smaller 7.2px card insets.
- Give media its own 14.4px corners inside 21.7px card shells.
- Use forest-green and mint as the default paired conversion colors.
- Make at least one inset band glow, contained by 43.3px corners.
- Keep section pills sentence-case and resource labels at 10.8px uppercase with 0.08em tracking.
- Pair human testimony with one contextualized quantitative result.
- Use four compact footer columns with muted labels and fine horizontal rules.

### Don't

- Do not turn the default marketing page into a dark aubergine theme; that belongs to the editorial gate.
- Do not make all buttons fully pill-shaped; the main actions have 13px corners.
- Do not fill every section with violet; concentrate it in an isolated band.
- Do not use heavy black drop shadows or thick dark outlines on white cards.
- Do not set body paragraphs with the negative tracking used in headings.
- Do not make all capability tiles the same size; preserve a visibly larger lead tile when using the mosaic.
- Do not replace soft product miniatures with dense tiny dashboard screenshots in every card.
- Do not spread serif display lettering or paper grain into ordinary product navigation and capability cards.

## Motion and responsive

### Motion

**Observed:**

- Button and pill transitions declare 0.3s cubic-bezier(0.165,0.84,0.44,1); card depth transitions declare all 300ms cubic-bezier(0.215,0.61,0.355,1).
- Arrows translate through clipped circular wrappers; hover can raise product cards in perspective.
- Ticker declarations use 30s linear infinite; icon and image marquees use 90s linear. A green-gradient word declares a 12s linear infinite cycle.

**Transfer:**

- Use the declared depth and arrow behaviors for tactile controls, while keeping text stationary inside its container.
- Use slow linear movement for logo or photo processions, not rapid scene switching.

**Unknown:**

- Exact sequencing of hero film, moving atmospheric fields and scroll-triggered chapter selection is not specified.

### Responsive

**Observed:**

- Declared width breakpoints include 478px, 479px, 767px, 768px, 991px, 992px, 1200px and 1920px; desktop measurements describe the 1440px composition.

**Transfer:**

- On narrow screens, preserve promise then actions then luminous object; reduce the split to a stack without losing the white frame.
- Allow supporting card rows and human-proof strips to scroll horizontally where a multi-column grid would make the product fragments unreadable.
- Move the catalog filter rail above its results and keep each statistic attached to its photograph.

**Unknown:**

- Exact mobile typography, container padding, navigation transformation and breakpoint-specific column counts are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
