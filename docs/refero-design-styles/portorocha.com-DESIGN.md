# PORTO ROCHA — a living editorial deck

## Overview

An image-led editorial workspace with a persistent index beside a stream of visual work. White and pale gray framing, small regular grotesk type and restrained controls let photography, printed matter and vivid project graphics supply the drama. It suits visually rich products, creative tools and portfolios with substantial proof to browse; the interface is dense but the main images are expansive.

### Essentials

- The page behaves like an index beside an exhibition: at 1440px, a 395px sticky left rail sits beside a 1045px content region, with 8px outer padding and gutters.
- The opening sells through an object, not a giant slogan: a 1029×687px rounded media stage fills the right side, while the first 23px/27px regular-weight headlines appear in cards immediately below it.
- Small type carries unusually much responsibility: 14px/1.25 regular text handles navigation, section headings and captions; 23px/27px display grotesk with 0.5px tracking is the main editorial emphasis.
- Navigation is a tangible deck: 387×98px pale cards have 16px padding, 10px corners and 65px square thumbnails; lower cards visibly recede into a smaller, faded stack. Include this deck and a centered two-line location clock as signature interface devices.
- The shell stays monochrome while the work is allowed to shout: white canvas, 4% black card fills and 50% black supporting text; saturated color belongs inside thumbnails and large media rather than navigation or page-wide brand bands.
- Actions stay at the scale of browsing: the default is a 40px-high pale pill with 16px horizontal padding and 40px radius, not a hero-sized conversion button.
- Proof accumulates in tight seams: 8px gaps separate media and three uneven card columns; cards use 16px insets and 8px text gaps. Include both an expansive visual stage and smaller, captioned proof even when the equivalent media must be newly made.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White canvas | `#ffffff` | `--color-canvas` | background, text | Page canvas, toggle knob and inverse action text. |
| Pale card | `#f5f5f5` | `--color-card` | surface | Navigation cards use this solid fill; main cards use black at 4% over white for the same visible tone. |
| Deck mist | `#efefef` | `--color-deck-mist` | surface | Outer edge of the navigation deck radial wash. |
| Control gray | `#ebebeb` | `--color-control` | surface, action | Toggle track and pale-action hover; black at 8% over white. |
| Deck stone | `#d9d6d5` | `--color-deck-stone` | surface | Warm center of the subtle radial wash on the receding navigation deck. |
| Secondary gray | `#808080` | `--color-secondary` | text, link | Dates, descriptions, section labels and quiet links; black at 50% over the white canvas. |
| Black ink | `#000000` | `--color-ink` | text, action | Headlines, names and primary labels; also the inverse purchase action. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| directory panels | Faint separator | `#f5f5f5` | `--color-rule` | border | Black at 4% for directory separators; the actual visible edge is slightly darker when laid over a pale card. |
| event listings | Agenda separator | `#b3b3b3` | `--color-agenda-rule` | border | Black at 30% for the stronger top rule on compact event listings. |
| embedded location maps | Location blue | `#007aff` | `--color-location-accent` | accent | A tiny 19px circular location marker inside map media; not a shell-wide action color. |

## Typography

- **sf-pro-text** — Small editorial text, controls, navigation and section labels. Neutral system grotesk with open small-size forms; predominantly regular weight. If unavailable, use **Inter**. Use 400 for nearly everything; preserve the compact line height. Font stack: "sf-pro-text", "Inter", Arial, sans-serif.
- **sf-pro-display** — Editorial card titles, the location clock and larger introductory prose. Smooth display optical grotesk; regular weight with slightly open tracking rather than tight headline compression. If unavailable, use **Inter**. Use 400 and retain the positive tracking. Font stack: "sf-pro-display", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| editorial-heading | sf-pro-display | 400 | 23px | 27px | 0.0196em | News-card headlines and the centered two-line date/location clock; also larger introductory prose on information pages. |
| body | sf-pro-text | 400 | 14px | 1.25 | normal | Body copy, dates, section labels, navigation, captions and pill actions; use color and position rather than a separate large section-heading scale. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| case studies | credits | sf-pro-text | 400 | 14px | 1.4 | normal | Dense role/name credits and collaborator lists at the end of a visual story. |

**Notes:**

- Regular weight is the default even for headings. The hierarchy is largely a change from gray 14px labels to black 23px titles.
- Keep small text at normal tracking; the larger display recipe opens slightly to 0.5px instead of becoming tightly tracked.
- Artwork may contain huge condensed, serif or monospaced lettering. Treat that as the product's visual content, not an additional interface type family.

## Layout

**Density:** Compact interface and content seams around expansive imagery; the rail has a deliberate open identity area above the deck.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Outer canvas inset, card-to-card gutters and most label/title/copy gaps. |
| 12px | Navigation thumbnail-to-text gap, paragraph separation and directory-row vertical padding. |
| 16px | Default card inset and section-label separation in credits. |
| 24px | Caption spacing beneath location and portrait imagery; lower padding on agenda rows. |
| 40px | Separation between larger content groups inside the information-page left column. |
| 48px | Separation between stacked credit groups. |

### Containers and grids

- **desktop split**: 2 columns · gap 8px · side padding 8px. At 1440px the sticky navigation occupies 395px including its left inset; the right content region is 1045px with 8px side padding, leaving 1029px for content. Use the full window rather than a centered maximum-width page.
- **proof masonry**: 3 columns · gap 8px. Three 338px columns at desktop, with independently flowing card heights rather than equal-height rows.
- **information split** (only for case studies and information pages): 2 columns · gap 8px. A roughly two-thirds narrative panel beside a one-third credits or contact stack; both top-aligned, with the narrow column allowed to continue below the narrative.
- **paired media** (only for case studies): 2 columns · gap 8px. Equal side-by-side media within the right content region, interleaved with full-width stages.

## Corner radius

| Element | Radius |
| --- | --- |
| content panels | 8px |
| navigation cards | 10px |
| pill actions | 40px |
| toggle track | 38px |
| round controls | 50% |

## Surfaces and depth

### Surfaces

#### Canvas · level 0

**Use:** Overall page and exposed space around content.

**CSS:** `background: #ffffff; color: #000000`

#### Pale panel · level 1

**Use:** Main editorial cards and grouped information.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 8px; box-shadow: none`

**Observed:** Panels are distinguished by fill and narrow white seams, not by outlines or elevation.

**Transfer:** Use the same material for prose, facts and resources so the imagery sets the visual hierarchy.

#### Navigation deck wash · level 1

**Use:** Subtle material variation on a card within the index deck.

**CSS:** `background: radial-gradient(76.17% 129.78% at 23.83% 65.4%, #d9d6d5 0px, #efefef 100%); border-radius: 10px`

**Observed:** The wash is low contrast and warm-neutral. Receding cards become smaller and more transparent; this is not a shadow.

**Transfer:** Use it to give the deck a little depth without making the rest of the page glossy.

#### Scrollable directory · level 1

**Only for:** directory panels

**Use:** Long team or resource lists inside a bounded panel.

**CSS:** `background: rgba(0, 0, 0, 0.04); border-radius: 8px; overflow: hidden`

**Observed:** The team panel is 498px tall, with a 16px-inset scrolling interior and a pale fade masking the lower rows.

**Transfer:** Use a local scrolling list when a long directory should not overwhelm adjacent content.

## Components

### Browse pill

**Use:** Default navigation action at the top left.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; border-radius: 40px; background: rgba(0, 0, 0, 0.04); color: #000000; transition: background-color 0.5s`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** A compact text-only pill sits apart from the card deck, opposite the mode toggle.

**States:** Declared: hover background-color rgba(0,0,0,.08); focus-visible not specified.

### Navigation card

**Use:** Persistent index links and short product positioning.

**CSS:** `display: flex; gap: 12px; padding: 16px; background: #f5f5f5; border-radius: 10px; overflow: hidden`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** A square thumbnail sits left of a black name and a gray one- or two-line description. The leading information card has no thumbnail. Cards form a receding deck at the bottom of the rail.

**Transfer:** Use product areas, applications or customer examples as the deck entries; provide a simple original thumbnail for each.

### Editorial proof card

**Use:** News, launches and attributable proof in the main three-column stream.

**CSS:** `padding: 16px; margin-bottom: 8px; background: rgba(0, 0, 0, 0.04); border-radius: 8px; transition: background-color 0.5s`

**Text style:** `editorial-heading` — sf-pro-display 400 · 23px/27px · tracking 0.0196em

**Observed:** Date comes first in gray body type, then a black title, gray paragraphs and an inset image. Content length and image aspect ratio determine height; the whole card is linked.

**States:** Declared: hover background-color rgba(0,0,0,.08); focus-visible not specified.

**Transfer:** Make each card an actual story or proof point, not an icon with an interchangeable feature slogan.

### Media stage

**Use:** Opening visual and continuous case-study image chapters.

**CSS:** `position: relative; overflow: hidden; background: rgba(0, 0, 0, 0.04); border-radius: 8px`

**Observed:** The default wide stage is about 3:2. Image content reaches its rounded edges; any black matte or photographic backing belongs to the image composition rather than a universal dark section.

**Transfer:** Stage one excellent object photograph, product scene or graphic composition instead of filling the panel with several small elements.

### Mode toggle

**Use:** Small mode control beside the browse action.

**CSS:** `width: 62px; height: 38px; padding: 3px; border-radius: 38px; background: rgba(0, 0, 0, 0.08); transition: background-color 0.5s, transform 0.5s`

**Observed:** A white 32px circular knob sits inside the track. The control is visually unlabelled.

**Transfer:** Keep the compact proportions; provide an accessible name rather than adding visible text that changes the top-row balance.

### Quiet text link

**Use:** Contacts, collaborators and downloadable resources.

**CSS:** `color: rgba(0, 0, 0, 0.5); text-decoration: underline; transition: color 0.5s`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** Links remain part of the small-text hierarchy; downloads append a tiny downward arrow rather than an enclosing button.

**States:** Declared: hover color #000; focus-visible not specified.

### Credits panel

**Only for:** case studies

**Use:** Attribution and production detail at the end of a visual story.

**CSS:** `padding: 16px; background: rgba(0, 0, 0, 0.04); border-radius: 8px`

**Text style:** `credits` — sf-pro-text 400 · 14px/1.4

**Observed:** A gray body-size heading starts a tall narrow panel. Black role/name text is grouped by discipline, with gray subgroup labels and understated links. A separate resource panel follows it.

**Transfer:** Treat collaborators and technical resources as useful closing content instead of adding a generic full-width sales footer.

### Directory row

**Only for:** directory panels

**Use:** Compact people or resource records.

**CSS:** `display: grid; grid-template-columns: 2.5fr 4fr 2.87fr; column-gap: 8px; padding: 12px 0px; border-bottom: 1px solid rgba(0, 0, 0, 0.04)`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** The primary name is black; role and location are gray. Rows are about 43px high and run inside the locally scrolling panel.

### Purchase pill

**Only for:** small merchandise modules

**Use:** A single transactional action within a small product card.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 40px; padding: 0px 16px; border-radius: 40px; background: #000000; color: #ffffff; transition: background-color 0.5s`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** A cutout object dominates the card, with its name and price at lower left and the inverse action at lower right.

**States:** Declared: hover background-color rgba(0,0,0,.5); focus-visible not specified.

### Utility tile

**Only for:** information-page endings

**Use:** A final policy or supporting resource link in the narrow column.

**CSS:** `padding: 16px; background: rgba(0, 0, 0, 0.04); border-radius: 8px; color: #000000`

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

**Observed:** A full-column shallow tile sits beneath the merchandise module rather than becoming a separate global footer.

## Imagery and graphics

### Object-led opening

**Use:** Primary visual statement for a landing page.

**Observed:** An open printed volume is photographed against a nearly black field. The object is broad and centered, with visible folds, page thickness and a cast shadow; monochrome figurative imagery occupies its spread. The large stage outweighs all surrounding text.

**Transfer:** Photograph the product, its output or a carefully made physical proxy with visible material and controlled light. For software without physical output, use one legible interface or a printed workflow in an equally composed scene; do not substitute a decorative stock background.

**Build:** Use a 3:2 image composition with a single broad object occupying roughly three quarters of the width, dark neutral backing and one directional light. For a minimal digital alternative, place one original product-output plane on a dark field with a restrained cast shadow rendered inside the artwork, then clip the composition to the Media stage.

### Editorial proof imagery

**Use:** Images within the main card stream.

**Observed:** A mix of portrait photography, publication covers, event graphics, architectural photographs and identity applications. Full color and monochrome coexist. Each image is inset in its card and has softly rounded corners; aspect ratios vary, preserving the uneven editorial cadence.

**Transfer:** Mix real people, useful product artifacts and graphic results. Let each asset retain its own palette, but keep the surrounding interface neutral.

### Receding navigation deck

**Use:** Signature visual treatment at the base of the persistent rail.

**Observed:** Several pale index cards tuck behind the last fully visible card, narrowing and fading toward the bottom. Small slivers of thumbnails reinforce the sense of a real stack.

**Transfer:** Always retain this tangible index device, using original product-area thumbnails when there is no project portfolio.

**Build:** Build a vertical stack with 8px gaps and 10px corners. Near the rail bottom, layer additional copies behind the front card, centered horizontally and translated upward; progressively reduce scale and opacity. Use the Navigation deck wash, not a drop shadow. One lower layer can be about 80% scale and 22% opacity; mask the bottom gently into the white canvas.

### Case-study visual essay

**Only for:** case studies

**Use:** Long-form demonstration of an individual body of work.

**Observed:** Large full-width stages alternate with paired images. Physical installations and people using them are intercut with close details, digital compositions and device mockups. One editorial project uses cream newsprint on black mattes, hard sunlight on concrete and saturated red-black cover art; another moves between bright exhibition photography and varied digital report scenes.

**Transfer:** Choose a material and palette specific to the product story, then alternate context, detail, output and use. Keep campaign artwork inside the image stages rather than spreading its type and colors into the global shell.

### Information-page photography

**Only for:** company and information pages

**Use:** Human introduction, locations and leadership.

**Observed:** A wide outdoor group photograph in vivid green daylight opens the page. Square interior images show airy workspaces; portraits use simple backdrops. The photos remain documentary and direct, not washed-out or heavily duotoned.

**Transfer:** Use a genuine team or community image as the broad opening and square location or maker images below.

### Icons

**Observed:** Very sparse utilitarian symbols: small gray downward arrows on download links, a 9×11px download SVG, outline location pins around 14×19px, and simple black play triangles inside 38px circles. Location clocks use black circular outlines with thin hands.

**Transfer:** Use simple single-color SVG geometry aligned with small text. Do not introduce a feature-icon system or multicolor interface pictograms.

## Section recipes

How recurring sections are built.

### First screen: Index and object opening

**Observed:** A white full-window shell splits into a persistent left index occupying a little over one quarter of the width and an expansive right visual stage. The rail starts with Browse pill and Mode toggle, followed by a centered wordmark, then a centered two-line date/location clock in editorial-heading type; the Navigation card deck starts lower down. The right side begins immediately with a 1029×687px Media stage, 8px from the window edges, showing a broad monochrome book object on dark backing. There is no overlaid marketing headline or hero CTA. Within the first 900px, the complete opening image and the first dated proof-card headlines and gray support text are visible. Most card imagery falls below the fold. Layers are white canvas, pale framing panels and photographic artwork; navigation stays visually separate from the artwork.

**Transfer:** Use this image-first split as the default landing-page opening: place the promise in a short rail information card and let an original product or output scene provide the visual hook. Use the same centered live clock and receding deck to keep the shell recognizable. Detail pages open with their strongest project artifact; company pages use a wide human photograph. For a product with no suitable photography, construct one polished product-output scene rather than inventing an oversized headline.

**Avoid:** Do not turn it into a centered headline-and-two-buttons SaaS hero, overlay copy across the object, or stretch the left rail into a conventional top navigation bar.

**Text style:** `editorial-heading` — sf-pro-display 400 · 23px/27px · tracking 0.0196em

### Dated proof stream

**Observed:** Editorial proof cards flow down three columns with 8px seams. Gray dates, black editorial-heading titles, gray body copy and inset media form an immediately readable order. Card heights remain independent.

**Transfer:** Present launches, customer outcomes, use cases or field notes as browsable editorial stories. The stream can be short; the recognizable device is its density and uneven card rhythm, not archive length.

**Text style:** `editorial-heading` — sf-pro-display 400 · 23px/27px · tracking 0.0196em

### Visual essay chapters

**Only for:** case studies

**Observed:** Media stages fill the right region with 8px vertical gaps. Full-width 3:2 images alternate with paired media; headings are often part of the artwork rather than separate HTML title blocks.

**Transfer:** Sequence big-picture context, close details and evidence of use, without adding repeated marketing titles between every image.

### Narrative and attribution ending

**Only for:** case studies

**Observed:** The final artwork is followed by an information split. A wide Pale panel carries a gray body-size section label and black prose; a narrow Credits panel continues farther down and ends with a separate download resource panel. The wide column is left open once its text ends. There is no monumental closing CTA or full-width footer band.

**Transfer:** End a detailed product story with its rationale, contributors and a useful resource. Preserve the asymmetric column lengths rather than padding the narrative to match the credits.

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

### Information mosaic and directory ending

**Only for:** company and information pages

**Observed:** A wide human photograph gives way to a two-thirds left column and a one-third sticky utility stack. The left groups larger introductory prose, compact tabbed lists, paired location images, offerings and portraits. The final left block is Scrollable directory; the right holds contacts, openings, locally scrolling event listings, a small merchandise card and Utility tile. The page ends on those useful modules, with 8px seams rather than a new footer design.

**Transfer:** Adapt to product specifications, resources, team or support information. Preserve the distinction between the larger reading column and small utility modules; only use merchandise when there is a genuine item.

**Text style:** `body` — sf-pro-text 400 · 14px/1.25

## Page flow

**Storyline:** Visual hook → browsable proof or visual demonstration → context and attribution → useful resources; persistent navigation remains available throughout.

### Image-led landing page and living proof index

1. **Visual hook** — A single expansive product-output image beside the permanent rail.
2. **Accumulating proof** — A dated, three-column stream mixes news, people, outcomes and artifacts.
3. **Continued browsing** — The archive remains the main content rather than switching into a separate sales-ending treatment.

**Transfer:** Use a curated stream of credible proof for a new product; place contact and navigation in the persistent shell rather than relying on a large closing banner.

### Multiform research or product-experience case study

1. **Identity** — A full-width title image establishes the project's own visual identity.
2. **Demonstration** — Digital scenes alternate with physical use, installations and close-up artifacts.
3. **Context** — A late wide prose panel explains the problem, method and questions.
4. **Attribution and resource** — A tall narrow credits list ends in a small download tile.

**Transfer:** Use the essay structure for a product with several modes or use contexts; its campaign art stays inside the media.

### Focused material or editorial case study

1. **Artifact hook** — A publication photographed in hard directional light introduces the work.
2. **Close examination** — Whole spreads on dark mattes alternate with tight paper and typography details.
3. **Context and credits** — The visual sequence yields to small-type rationale, contributors and resource links.

**Transfer:** Apply to a single product, launch or crafted output; show enough close detail to make the quality tangible.

### Company information and practical directory

1. **Human introduction** — A broad group photograph precedes a larger introductory paragraph.
2. **Capability and trust** — Compact lists, workspace photos, offerings and biographies provide substance.
3. **Useful ending** — A bounded directory sits beside contacts, opportunities, events and a final utility tile.

**Transfer:** Use this mosaic for a company or resource page; let practical information close the story rather than adding another pitch.

## Writing

Editorial and matter-of-fact, with confidence carried by specific work and attribution. Institutional descriptions can be thoughtful and expansive; short navigation copy remains plain and useful.

**Do not copy:** Do not reuse the studio name, wordmark, project artwork, client names, awards, rankings, research counts, biographies, quotations or claims as facts about another product. Source examples illustrate syntax only.

- **Addressing the reader:** First-person plural for the organization and its process; third person for news, people and collaborators. Direct questions invite reflection more often than direct commands to buy.
- **Rhythm:** News titles are often full descriptive phrases, while labels and actions are very short. Supporting copy uses compact paragraphs with occasional longer contextual sentences. Excitement appears in individual news items, not in every label.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Editorial title | Name the work or person and a specific development, not an abstract superlative. | Usually 7–16 words | “MASP identity wins two Golds and two Silvers at LAD Awards” |
| Section label | Plain noun phrase naming the contents of the panel. | 1–3 words | “Project Information”<br>“Current Openings” |
| Supporting description | Explain who the organization is, where it operates and what kind of work it does. | One short paragraph, followed by a second paragraph for approach | “[Brand] is a global strategy and design agency with offices in New York and London.” |
| Action | Literal verb plus the destination or resource. | 1–4 words | “Show all projects”<br>“Download Project Images”<br>“Order” |
| Reflective question | Ask a concise question about the broader problem or possible future. | 4–9 words | “Where does design go from here?” |

**Words and phrasing to use:** work; systems; context; research; community; collaboration; identity; questions; project information; credits

**Avoid:** revolutionary solution; unlock limitless potential; game-changing platform; best-in-class; act now; frictionless everything

**Rules:**

- Make proof attributable: state what happened, who was involved and why it matters.
- Use labels as orientation, not miniature advertising slogans.
- Explain process and context when a visual story needs them, but let the artwork lead.
- Keep action labels literal and brief; a useful download is a valid closing action.

## Do's and Don'ts

### Do

- Keep the desktop rail near 395px and the media field near 1029px at a 1440px window.
- Use 8px seams so cards read as a continuous editorial system.
- Set editorial titles at 23px/27px, weight 400 and 0.5px tracking.
- Use 14px/1.25 text for labels as well as paragraphs; change color to distinguish their role.
- Keep 16px panel insets and 10px navigation-card corners distinct from 8px content corners.
- Use the compact 40px pale browse pill as the default action.
- Mix color-rich artifacts and monochrome imagery within the neutral shell.
- Make the two-line clock and receding card deck visible parts of the index.

### Don't

- Do not make all proof cards equal height; that destroys the independent-column rhythm.
- Do not use heavy bold headings to manufacture hierarchy in the small-text shell.
- Do not apply drop shadows to pale content cards; separation comes from fill and white seams.
- Do not inflate panel corners to 24px or make every panel a pill.
- Do not spread a project's saturated palette across the global canvas or navigation.
- Do not turn every text link into a filled button; contacts and resources remain underlined gray text.
- Do not make the centered identity area a giant typographic logo sculpture; its openness is intentional.
- Do not fill the shorter narrative column with invented modules merely to match the length of a credits list.

## Motion and responsive

### Motion

**Observed:**

- Pale card and browse-action background changes use background-color 0.5s.
- Quiet links use color 0.5s; toggle parts declare background-color 0.5s and transform 0.5s.
- The deck includes transformed, scaled and faded cards. Some surfaces declare opacity transitions of 0.3s.
- Case-study pages include a circular play control beside the mode switch; the rail clock updates its time.

**Transfer:**

- Use the declared half-second color transitions for the understated controls.
- Preserve the tactile receding-deck effect without turning every editorial card into a floating animated object.

**Unknown:**

- The exact deck scroll interpolation, playback behavior, easing per component and reduced-motion implementation are not established.

### Responsive

**Observed:**

- The root font-size declares 0.520833vw and rem-based dimensions scale with it.
- Styles include width boundaries at 656/657px, 768px, 896/897px, 912/913px, 1024/1025px and 1280px; a 769px boundary also appears on the information page.

**Transfer:**

- For narrow layouts, prioritize the visual stage and keep the index accessible as a compact deck or dedicated browsing view; reduce the masonry to fewer columns rather than shrinking its prose indefinitely.
- Retain 8px seams, the clock/index identity and the distinction between expansive media and small captioned proof.

**Unknown:**

- Exact narrow-screen column counts, rail behavior and type overrides are not established; the suggested collapse is implementation guidance.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
