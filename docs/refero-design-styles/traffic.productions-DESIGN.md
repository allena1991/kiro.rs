# Traffic Productions — serpentine rules, acid interruptions

## Overview

An editorial, industrial grotesk identity with the blunt confidence of a production ledger and an unexpectedly playful streak. Pale grey and near-black dominate, punctuated by acid yellow, cool grey panels and richly photographed work. Dense, tightly set statements sit above expanses of open space; continuous angular rules make the whole page feel like one connected object. It suits creative tools, specialist services and products whose output deserves a visual portfolio.

### Essentials

- The opening is a manifesto rather than a slogan: regular-weight Suisse at 84px, 0.93 line height and -0.03em tracking fills nearly the whole width in six tightly stacked lines, leaving a deep empty field underneath.
- Rules behave like a continuous folded ribbon: 4px near-black strokes run across 1400px panels within 20px side gutters, turning alternately at the left and right edges rather than enclosing every block as an independent card.
- Hierarchy switches register, not typeface: sentence-case 54px statements contrast with 108px uppercase service links and a monumental two-line closing invitation, all at weight 400.
- Actions are words, not capsules: 18px uppercase underlined links and bent-arrow links carry navigation and conversion. The deliberate exception is a 162px black circular play control with 30px text and a pale smile arc.
- Color arrives in concentrated interruptions: the default page stays pale grey for its manifesto, explanations and portfolio; one 675px yellow interaction field and narrow yellow footer labels supply the chromatic punch.
- Proof is staged as a ruled catalogue: letter indexes and small underlined names sit beside hard-edged monochrome image strips; full-color photography takes over in detailed stories. With no photographic output, stage a real product artifact or interface in the same square-edged format.
- The ending is a graphic destination: 108px uppercase invitation words sit on opposite edges of successive 130px rows, above two half-width serpentine line sculptures with yellow name strips and compact arrow-led links. Carry this device into every new page, using the new identity's own short labels.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#fff824` | `--color-signal` | background, accent, surface | The interaction field and thin footer name strips; capability chapters also use it as a complete panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Production black | `#151515` | `--color-ink` | text, background, border, action | Primary type, continuous rules, index dots and the play control; inverse editorial panels use the same near-black. |
| Pale grey | `#f3f3f3` | `--color-canvas` | background, text | Default page canvas and inverse type on black. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| company and portfolio overview pages | Cool blue grey | `#a5adb6` | `--color-slate` | background, surface | Editorial philosophy and recruitment panels. |
| case studies | Case study grey | `#c5cbd1` | `--color-case-grey` | background, surface | Project title, project summary and discipline explanation panels. |
| capability explorer sections | Catalogue white | `#ffffff` | `--color-white` | background, surface | Right-hand catalogue half paired with a black image stage. |

## Typography

- **Suisse** — All visible navigation, headings, paragraph text, labels and numerals. Compact neo-grotesk with a high x-height, blunt terminals and closely packed regular-weight text. If unavailable, use **Inter**. Use 400 for the main system; preserve tight tracking and manually tune line breaks. Font stack: "Suisse", "Inter", ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| monument | Suisse | 400 | 108px | 0.89 | -0.04em, uppercase | Oversized service rows, closing invitation and concise interior-page titles. |
| manifesto | Suisse | 400 | 84px | 0.93 | -0.03em | Default first-screen manifesto in sentence case; a multi-line paragraph with headline scale. |
| statement | Suisse | 400 | 54px | 0.96 | -0.03em | Main editorial statement to the right of an indexed section label. |
| lead | Suisse | 400 | 30px | 1 | -0.02em | Play control and longer editorial leads. |
| label | Suisse | 400 | 18px | 1 | -0.02em, uppercase | Navigation, section labels, footer links and default text actions. |
| body | Suisse | 400 | 18px | 1.17 | -0.03em | Supporting paragraphs, compact descriptions and capability lists. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| full-panel capability or creative-service statements | poster | Suisse | 400 | 84px | 0.93 | -0.03em, uppercase | Full-width uppercase declaration across a yellow or black panel. |
| case-study explanation panels | case-heading | Suisse | 400 | 54px | 0.96 | -0.03em, uppercase | Uppercase editorial heading over a discipline list. |
| portfolio indexes | project-title | Suisse | 400 | 36px | 1 | -0.02em, uppercase | Project names in detailed catalogue rows. |

**Notes:**

- Keep weight 400 dominant; impact comes from scale, close line spacing and the graphic rules, not heavy bold typography.
- Use -0.03em for manifesto and statement text, tightening to -0.04em at 108px. Small labels remain compact at -0.02em.
- Sentence case makes extended introductory claims readable; uppercase belongs to compact navigational words, poster panels and monumental closing lines.
- The nominal heading hierarchy is deliberately inverted: a small indexed section heading introduces a much larger statement. Preserve both roles semantically.

## Layout

**Density:** Airy at the section level and compact within text and rules; long blank lower fields balance very tightly stacked headings.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 4px | Structural rule thickness and separation between monumental row edges. | fixed |
| 8px | Index-dot to label spacing. | 0.556vw |
| 12px | Section-label and catalogue title inset. | fixed |
| 20px | Side gutters and main column gaps. | fixed |
| 31px | Narrow ruled divider and fixed navigation bar height. | fixed |
| 44px | Editorial panel top padding. | 3.056vw |
| 47px | Statement-to-support and support-to-action separation. | 3.264vw |
| 273px | Deep empty lower field in editorial sections. | 18.958vw |

### Containers and grids

- **page wrapper**: side padding 20px. At 1440px viewport width, the ruled content spans 1400px. Keep the canvas visible outside both edges rather than bleeding every panel to the browser boundary.
- **editorial grid**: 12 columns · gap 20px. Section labels occupy the left rail; main text starts at the fourth column, about one quarter of the page across. Statements span eight columns, while a nine-column content wrapper holds support and actions.
- **support pair**: 2 columns · gap 20px. Two supporting paragraphs, each about 393px wide, below the editorial statement; align the left paragraph and the action with the large statement.
- **closing halves**: 2 columns · gap 20px. Each half is 690px wide at desktop; line sculpture and identity labels on the left, navigational and location links on the right.
- **proof grid** (only for client proof sections): 4 columns · gap 20px. Four columns of logo media, each 335px wide in approximately 190px-high cells on black.

## Corner radius

| Element | Radius |
| --- | --- |
| Rectangular panels | 0px |
| Play control and index dots | 9999px (pill) |

## Surfaces and depth

### Surfaces

#### Pale canvas · level 0

**Use:** Default page ground.

**CSS:** `background: #f3f3f3; color: #151515`

**Observed:** Flat and untextured; no elevation or atmospheric gradient.

**Transfer:** Let type, ruled structure and real media provide the texture.

#### Signal field · level 0

**Use:** High-energy interaction or compact capability declaration.

**CSS:** `background: #fff824; color: #151515; border-radius: 0px`

**Observed:** A single broad yellow rectangle stays inside the page gutters. Thin yellow name strips repeat the color at the ending.

**Transfer:** Concentrate the accent in a deliberate destination rather than scattering bright cards throughout the page.

#### Inverse editorial · level 0

**Only for:** company history, creative-service and proof chapters

**Use:** Dense editorial statements or logo proof.

**CSS:** `background: #151515; color: #f3f3f3`

**Observed:** Flat black with pale type, retaining the same column offsets and large open lower field.

**Transfer:** Use for a focused secondary narrative, not as a replacement for the pale default opening.

#### Slate editorial · level 0

**Only for:** company and portfolio overview pages

**Use:** Philosophy and recruitment material.

**CSS:** `background: #a5adb6; color: #151515`

**Observed:** Muted cool grey fills one ruled panel; text remains black.

**Transfer:** Keep this as an editorial variant, not a general card color.

#### Case study field · level 0

**Only for:** case studies

**Use:** Title and explanatory interludes.

**CSS:** `background: #c5cbd1; color: #151515`

**Observed:** Lighter than the slate editorial variant and paired with full-color project images.

**Transfer:** Use a consistent muted ground to connect a project's title and later explanations.

#### Split catalogue stage · level 0

**Only for:** capability explorer sections

**Use:** Pinned image-and-list presentation.

**CSS:** `background: #ffffff; color: #151515`

**Observed:** Black left half holds centered square color media; white right half holds the list and a full-width yellow highlight band.

**Transfer:** Separate image and taxonomy through opposing flat grounds, not floating cards.

## Components

### Fixed ruled navigation

**Use:** Persistent top-level wayfinding.

**CSS:** `position: fixed; margin-top: 20px; height: 31px; z-index: 1000; overflow: hidden`

**Text style:** `label` — Suisse 400 · 18px/1 · tracking -0.02em · uppercase

**Observed:** A compact identity link sits left; a single horizontal run of small uppercase links aligns right. A ruled strip backs the content and remains pale over later sections.

**Transfer:** Use a short text identity and a few tightly spaced destinations; keep it visually thin rather than creating a tall masthead.

### Underlined text action

**Use:** Default editorial conversion link.

**CSS:** `display: inline-flex; position: relative; overflow: hidden; color: #151515`

**Text style:** `label` — Suisse 400 · 18px/1 · tracking -0.02em · uppercase

**Observed:** Text sits directly on the current ground with an underline and no padded button box. Inverse panels use pale text.

**States:** Declared: hover outline transparent solid 2px with outline-offset 2px; focus-visible behavior is not specified.

**Transfer:** Name the destination with a short verb phrase.

### Indexed section label

**Use:** Small anchor for a much larger editorial block.

**CSS:** `display: flex; align-items: center; color: #151515`

**Text style:** `label` — Suisse 400 · 18px/1 · tracking -0.02em · uppercase

**Observed:** A 14px circular index precedes the heading by 8px; the group is inset 12px from the panel edge. Inverse sections reverse the dot and type.

**Transfer:** Use sequential numbers where helpful, keeping the index visually subordinate.

### Ribbon divider

**Use:** Connect sections with the site's angular line language.

**CSS:** `height: 31px; border-top: 4px solid #151515; border-bottom: 4px solid #151515; border-left: 4px solid #151515`

**Observed:** Narrow empty rule lanes connect to the panel below; the open side alternates as the ribbon travels down the page.

**Transfer:** Join divider and panel edges continuously. Avoid doubling shared strokes.

### Project strip

**Use:** Selected proof on a marketing page.

**CSS:** `position: relative; overflow: hidden; color: #151515`

**Text style:** `label` — Suisse 400 · 18px/1 · tracking -0.02em · uppercase

**Observed:** A letter index anchors the left edge, a small underlined project name occupies the next rail, and a monochrome image strip begins farther right. Media is 287px tall, with varying widths rather than identical thumbnails. Narrow Ribbon dividers separate rows.

**Transfer:** Present outputs as a catalogue of artifacts, adapting image width to the artifact while retaining row alignment.

### Monumental service row

**Use:** High-impact links to principal capabilities.

**CSS:** `display: flex; align-items: center; padding: 15px 8px; color: #151515`

**Text style:** `monument` — Suisse 400 · 108px/0.89 · tracking -0.04em · uppercase

**Observed:** Oversized uppercase words run through alternating left- and right-turning ruled rows. Small square photographic thumbnails, about 78px, precede the words.

**Transfer:** Use one or two broad capability names rather than fitting a sentence into the row.

### Smile play control

**Use:** Primary interaction within the yellow field.

**CSS:** `display: flex; flex-direction: column; justify-content: center; align-items: center; width: 162px; height: 162px; background: #151515; color: #f3f3f3; border-radius: 9999px`

**Text style:** `lead` — Suisse 400 · 30px/1 · tracking -0.02em

**Observed:** Centered multi-line text occupies the upper part of the circle; a pale upward-curving smile arc fills the bottom. The whole control sits near the center of the yellow rectangle.

**States:** Declared: hover outline transparent solid 2px with outline-offset 2px; focus-visible behavior is not specified.

**Transfer:** Retain the smile-and-circle device for a reel, walkthrough or interactive demonstration, with a truthful action label.

### Closing invitation row

**Use:** The large final conversion gesture.

**CSS:** `border-top: 4px solid #151515; border-left: 4px solid #151515; padding-right: 4px`

**Text style:** `monument` — Suisse 400 · 108px/0.89 · tracking -0.04em · uppercase

**Observed:** Two successive lines form one invitation: the first anchors left, the second anchors right. The second row turns the border at the right edge and closes below. Neither line is a filled button.

**Transfer:** Choose a short invitation that can split naturally into two strongly opposed words or phrases.

### Bent arrow link

**Use:** Footer navigation and location destinations.

**CSS:** `display: flex; align-items: center; color: #151515`

**Text style:** `label` — Suisse 400 · 18px/1 · tracking -0.02em · uppercase

**Observed:** A 13px by 14px solid bent arrow precedes each label. Links stack with a 3.6px row gap and sit alongside, not inside, the left-hand line sculpture.

**States:** Declared: hover outline transparent solid 2px with outline-offset 2px; focus-visible behavior is not specified.

### Capability highlight

**Only for:** capability explorer sections

**Use:** Mark the active discipline in the scroll-driven catalogue.

**CSS:** `position: absolute; height: 21px; background: #fff824; transition: opacity 0.25s cubic-bezier(0.33, 0, 0, 1)`

**Text style:** `body` — Suisse 400 · 18px/1.17 · tracking -0.03em

**Observed:** The yellow band spans the full white half, behind a letter-indexed line item; the matching square media changes in the black half.

**Transfer:** Keep one active row at a time, tied to a meaningful visual example.

## Imagery and graphics

### Monochrome output strips

**Use:** Portfolio proof on the pale marketing canvas.

**Observed:** Black-and-white human portraits, product smears, packaging and campaign photography are clipped into hard rectangular bands. Images are deliberately offset to the right of letter indexes and small titles; they are not decorative backgrounds.

**Transfer:** Desaturate a few compelling real outputs; choose close-up detail and clean silhouettes that survive the shallow band framing.

### Serpentine identity sculpture

**Use:** Signature graphic structure of the closing section.

**Observed:** A stack of 26px-high narrow horizontal lanes switches its closed edge each row. Two short identity labels occupy acid-yellow strips; the ribbon expands across the full width near the legal line.

**Transfer:** Recreate with the new product's short name fragments or functional labels. It remains a graphic line sculpture, not a list of empty cards.

**Build:** Use SVG paths with fill='none', stroke #151515 and stroke-width 4. Draw horizontal runs across one 690px half, stepping down 26px and alternating the joining vertical edge. Put #fff824 rectangles behind the two labelled lanes. Continue the final path across the 1400px content width; keep all corners square.

### Smile arc

**Use:** Friendly interruption within the strict graphic system.

**Observed:** A pale open arc sits below the play text inside the black circle, making an abstract smiling face without eyes.

**Transfer:** Preserve this spare geometry rather than adding a mascot illustration.

**Build:** Inside a 162px circle, position a 115px-wide SVG at the lower third. Draw a shallow U-shaped path with #f3f3f3 stroke about 4px, no fill, spanning roughly 110px by 44px. Leave a clear gap between the arc and the stacked action text.

### Immersive case-study photography

**Only for:** case studies

**Use:** Long-form demonstration of an output across contexts.

**Observed:** Full-color portraits and street campaign scenes alternate with close-up crops, paired images and product mockup grids. Wide images span about 1396px, often 798px high; 20px pale gutters separate pairs. Warm skin tones, daylight, kraft paper and black packaging keep the imagery tactile.

**Transfer:** Show the new product in use, then inspect its physical or digital artifacts. Alternate full-width context with detail pairs instead of repeating the same mockup angle.

### Black-backed exhibit

**Only for:** capability explorers and case-study media grids

**Use:** Isolate examples with museum-like framing.

**Observed:** Square color examples sit centered with generous black margins. Paired exhibit tiles show retail experiences or people; a six-cell mockup matrix alternates light and black backings around kraft bags, cards and stationery.

**Transfer:** Use a square product rendering, interface or photograph on a flat black stage; retain substantial margin and omit ornamental shadows outside the image.

### Layered creative object

**Only for:** creative-service promotional chapters

**Use:** Dim sculptural visual behind pale editorial text.

**Observed:** An oblique stack of dark translucent rectangular plates, with reflective yellow-green edges and faint repeated lettering, floats on black behind the copy. The object is smaller than the poster heading and does not replace it.

**Transfer:** Use a product-related stack or artifact with restrained reflections. A minimum version is several offset translucent rectangles, kept dark enough for uninterrupted pale type.

**Build:** Stack 8–10 SVG quadrilateral outlines into a roughly 300px by 360px object, shifting each layer downward about 24px. Use rgba(243,243,243,0.25) for thin edges and rgba(255,248,36,0.12) for sparse internal marks over #151515. Tilt the top plane and keep the object behind the support text; avoid a luminous page-wide glow.

### Icons

**Observed:** Small solid bent arrows measure 13px by 14px; case navigation also uses 18px versions. Interior title bands have a bold paired downward-chevron motif about 82px by 88px, and the opening places it at the lower right.

**Transfer:** Use solid angular directional forms, not a large library of rounded outline pictograms. Build the paired chevron from two downward V shapes with thick square-ended strokes.

## Section recipes

How recurring sections are built.

### First screen: Manifesto opening

**Observed:** The first 900px contains a fixed 31px navigation strip inset 20px from the top and sides, then a 759px-tall pale panel. Its sentence-case manifesto begins just below the navigation and spans almost the whole content width at 84px, weight 400, 0.93 line height and -0.03em tracking. It occupies roughly the upper 480px of the panel in six dense lines; a large empty lower field ends in a double downward chevron at the right. Back-to-front layers are pale ground, angular 4px framing rules, text and chevrons, then the persistent navigation. There is no hero photography, separate support line or filled CTA. A narrow ruled lane and the beginning of the next indexed section become visible near the fold; its full explanation is below it.

**Transfer:** Open with a concrete description of what the new product does, for whom and toward what outcome. Let the statement itself be the main object; no substitute hero artwork is necessary. Interior overview pages instead use a compact 108px uppercase title band with the double chevron, followed immediately by an editorial panel. Case stories pair that title band with wide full-color media.

**Avoid:** Do not turn this into a centered short slogan with a pill CTA, dashboard mockup and decorative gradient; the long flush-left statement and its unoccupied lower field are the composition.

**Text style:** `manifesto` — Suisse 400 · 84px/0.93 · tracking -0.03em

### Indexed editorial argument

**Observed:** Indexed section label sits in the left rail; statement begins about one quarter of the width across. Use statement type, a pair of body paragraphs after 47px, and an Underlined text action another 47px later. Panel padding is 44px above and 273px below; Ribbon dividers connect the edges. Pale is the default; inverse, yellow and slate are chapter variants.

**Transfer:** Use this for positioning, differentiation or an explanation of the product's operating model. Keep the smaller support more specific than the large statement.

**Text style:** `statement` — Suisse 400 · 54px/0.96 · tracking -0.03em

### Proof catalogue

**Observed:** Project strip components form the selected-output list, with letter indexes, underlined names and right-offset monochrome imagery. The portfolio-index variant uses 36px uppercase project names at left, a compact capability list and action in the middle, and 571px by 341px imagery on the right, with approximately 371px row pitch.

**Transfer:** Use this to show customers' outcomes, examples or product use cases. Preserve the ledger-like relationship between identifier, description and image.

### Capability gateway

**Observed:** An Indexed section label precedes two Monumental service rows with embedded tiny square portraits. A Ribbon divider leads into the 675px Signal field with a centered Smile play control.

**Transfer:** Use the giant row labels to name the product's principal modes, then give the visitor a playful demonstration destination. The row device and smile interaction can appear elsewhere in a new narrative.

### Monumental closing

**Observed:** Closing invitation rows oppose left- and right-aligned 108px words. Below, the Serpentine identity sculpture occupies the left half while Bent arrow links group navigation above locations in the right half. The lower edge expands to a full-width ruled lane and a compact legal row. The shared ending is approximately 830px tall; the long case story leaves extra lead-in space before it.

**Transfer:** Always end with the opposed-word invitation and ruled identity sculpture. Use the new product's conversion destination, name fragments, relevant links and appropriate legal details.

**Text style:** `monument` — Suisse 400 · 108px/0.89 · tracking -0.04em · uppercase

### Pinned capability explorer

**Only for:** capability-heavy product pages

**Observed:** A 900px viewport-height chapter holds a near-equal split: black image stage left, white taxonomy right. A square 459px image is centered in the left half; 54px category titles and letter-indexed 18px lines occupy the right. Capability highlight tracks the active line while the example changes. A small underlined destination anchors the bottom.

**Transfer:** Make a finite set of capabilities concrete through corresponding examples. Keep the list legible throughout, even if the experience is implemented without pinning.

### Poster chapter

**Only for:** capability and creative-service promotional chapters

**Observed:** Poster type spans the full panel at the top. Below it, a small Indexed section label aligns with a 30px lead starting at the quarter-width rail. Yellow panels use black type; the creative-service variant uses pale type on black with the Layered creative object behind.

**Transfer:** Use for a single strong operational promise or adjacent offer, not every section heading.

**Text style:** `poster` — Suisse 400 · 84px/0.93 · tracking -0.03em · uppercase

### Institutional proof and locations

**Only for:** company and trust pages

**Observed:** Company detail uses two compact paragraphs on the quarter-width rail, a small year/location pair well below, and letter-indexed address rows at the bottom of a 646px pale panel. Client proof instead uses a short 18px introductory claim and a four-column logo field on black; the number is inline, not an oversized stat.

**Transfer:** Give concrete facts quiet typographic treatment. Use the ruled address-row construction for equivalent structured facts, and logos only where they genuinely support the product.

### Case-study media essay

**Only for:** case studies

**Observed:** A muted title band and wide hero lead into a summary panel with discipline labels left and 30px narrative right. Full-width and paired photographic sections alternate with one muted explanation panel, then a related-project section: 54px invitation left, two color portrait-format thumbnails right with previous/next captions and bent-arrow names. The common closing follows.

**Transfer:** Organize the visual evidence from context to artifact to experience, with concise explanatory pauses rather than a paragraph under every image.

## Page flow

**Storyline:** plainspoken promise → explanatory argument → visible outputs or capabilities → focused interaction or trust proof → monumental invitation

### Introduce the offer and demonstrate its range

1. **Promise** — Large sentence-case manifesto fills the opening panel.
2. **Positioning** — Indexed editorial argument with two supporting paragraphs.
3. **Product proof** — Selected monochrome output strips.
4. **Capability gateway** — Monumental service rows and a yellow play field.
5. **Closing call** — Opposed invitation words, serpentine identity and compact links.

**Transfer:** Let a product description carry the hero; prove it with a small number of actual outputs and give the demonstration a strong graphic destination.

### Explain a project through extensive visual evidence

1. **Identification** — Uppercase title on muted grey followed by wide color photography.
2. **Context** — Discipline labels and a substantial 30px project summary.
3. **Demonstration** — Long sequence of wide photos, paired details and artifact matrices.
4. **Explanation** — Muted editorial panel summarizing the work across disciplines.
5. **Continuation** — Two related-project thumbnails and directional captions.
6. **Closing call** — Shared monumental invitation and ruled footer.

**Transfer:** Use for an implementation story or product launch, scaling the media essay to the amount of genuine proof available.

### Establish an organization's character and credibility

1. **Identification** — Compact uppercase title band.
2. **History** — Inverse editorial argument and small supporting paragraphs.
3. **Capability promise** — Yellow full-width poster statement and lead.
4. **Concrete facts** — Team description, year/location pair and ruled address rows.
5. **Participation** — Slate editorial recruitment invitation.
6. **Closing call** — Shared monumental invitation and ruled footer.

**Transfer:** Replace history and recruitment with facts and participation modes relevant to the new organization.

### Provide a browsable index of output

1. **Identification** — Compact uppercase title band.
2. **Framing** — Slate philosophy panel explains the value of the examples.
3. **Navigation** — Thin category filter strip with circular markers.
4. **Product proof** — Repeated ruled project rows with title, capability list, action and monochrome image.
5. **Closing call** — Shared monumental invitation and ruled footer.

**Transfer:** Use for use cases, examples or a template library without turning the catalogue into a generic card grid.

### Make a broad capability offering tangible

1. **Identification** — Compact uppercase title band.
2. **Positioning** — Yellow editorial panel with statement, two paragraphs and text action.
3. **Capability demonstration** — Pinned split explorer pairs a highlighted list item with square color media.
4. **Adjacent offer** — Inverse poster chapter with a dark layered object.
5. **Social proof** — Short inline tenure claim and a four-column client logo field.
6. **Closing call** — Shared monumental invitation and ruled footer.

**Transfer:** Map the product's modes to visual examples, then support breadth with credible proof rather than adding more feature cards.

## Writing

Direct, business-minded and execution-focused, with an independent creative confidence. Warmth comes through collaboration and practical service language rather than jokes or lifestyle slogans.

**Do not copy:** Do not reuse the organization's name, client names, project imagery, proprietary artwork, founding year, locations, awards, tenure claims or exact promotional statements as facts about another product. Examples below illustrate structure and tone only.

- **Addressing the reader:** Mostly first-person plural describing what the organization does for clients; restrained direct invitation in action labels. The reader is treated as a capable professional.
- **Rhythm:** Long declarative introductory sentences contrast with short uppercase labels and two- to four-word actions. Support is compact, often two parallel paragraphs; commas and compound phrases carry momentum without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening statement | Identify the offer, operating breadth, relationship and practical outcome in connected sentences. | About 40–55 words | “We are a service-oriented production house, working across physical and digital completely in-tune with our clients. We produce things from beginning to end, that help solve business issues.” |
| Editorial statement | State a differentiated way of working, then name the audience or outcome. | About 15–30 words | “A non-agency offer for Brands, Agencies, Marketers, Creatives and Procurement focusing on delivering performance at scale.” |
| Support | Balance a clear stance with a collaborative qualification. | One sentence per compact paragraph | “Independent in thinking, but seamlessly integrated in our clients' ecosystem to deliver sustainable growth.”<br>“Radically service-oriented and without ego, but always with a clear vision.” |
| Section label | Plain noun phrase locating the topic, without clever metaphor. | Two or three words | “Who are we”<br>“Our capabilities” |
| Action | Name the next destination or experience directly. | Two to four words | “more about us”<br>“Click and play”<br>“See our work” |
| Closing invitation | An everyday invitation broken into two emphatic fragments. | Three words | “Get in touch” |

**Words and phrasing to use:** service-oriented; in-tune; across; from beginning to end; partners; production; consistency; touchpoints; efficiency

**Avoid:** revolutionary magic; game-changing; 10x everything; disrupt the universe; excessively cute microcopy

**Rules:**

- Make the big type explain the actual offer; do not waste it on a vague motivational slogan.
- Ground abstract benefits in processes, outputs or working relationships in the supporting copy.
- Use parallel syntax for paired support paragraphs.
- Keep taxonomy labels literal and short enough to fit a compact line.
- Place playful language in the interaction invitation, not in every headline.

## Do's and Don'ts

### Do

- Keep the page gutters and primary column gaps at 20px.
- Use 4px square-corner rules as connected paths with alternating turns.
- Set the main manifesto at 84px and 0.93 line height, not as a short centered slogan.
- Keep all major display roles at weight 400 and preserve their negative tracking.
- Start editorial support about one quarter of the way across the page.
- Concentrate yellow in a broad interaction field and narrow identity strips.
- Give the circular play action its full 162px diameter and smile arc.
- Retain both opposed 108px closing lines and the half-width serpentine identity treatment.

### Don't

- Do not replace the 4px structural rule with faint 1px card outlines.
- Do not round image tiles or editorial panels; only dots and the play control are circular.
- Do not put a drop shadow beneath navigation, cards or panels; the system is flat.
- Do not make every action a filled pill; ordinary actions are compact uppercase text.
- Do not distribute yellow evenly through every section; pale grey remains the landing-page default.
- Do not apply monochrome to all detailed storytelling media; case imagery is full color.
- Do not promote the inline tenure number into a giant dashboard-style stat.
- Do not add an outline-icon feature grid; directional arrows, indexes and real artifacts carry this identity.

## Motion and responsive

### Motion

**Observed:**

- Text is structured into masked word and line groups. Declared transform transitions include 0.6s cubic-bezier(0.19, 1, 0.22, 1) with stagger delays from 0.2s to 0.7s.
- Media filter transitions include 0.6s cubic-bezier(0.23, 1, 0.32, 1).
- The capability explorer holds a split scene while scrolling changes the highlighted row and square example; its highlight declares opacity 0.25s cubic-bezier(0.33, 0, 0, 1).

**Transfer:**

- Use masked line reveals to support the tightly stacked manifesto rather than adding character-by-character typing.
- For a capability explorer, synchronize one active list row with one visual example while keeping the taxonomy stationary.

**Unknown:**

- Exact entrance triggers, image-hover filter endpoints, play-overlay behavior and reduced-motion implementation are not established.

### Responsive

**Observed:**

- CSS width breakpoints occur at 768px, 1024px and 1440px boundaries.

**Transfer:**

- On narrow screens, preserve the connected rule path and opposed closing-word alignment; reduce type enough to prevent overflow rather than clipping the invitation.
- Stack support paragraphs and move the section label above the statement when the quarter-width rail becomes too narrow.
- For the capability explorer, keep the active label and associated media adjacent in reading order even if the two halves must stack.

**Unknown:**

- Only the desktop composition is established; exact mobile font sizes, menu behavior and narrow-screen pinning are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
