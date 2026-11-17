# Spring/Summer — billboard meets scrapbook

## Overview

A digital-agency sensibility that pairs billboard-sized condensed grotesk lettering with small, almost administrative monospace labels. Warm grey, hot red and inky black alternate around richly staged interface imagery and candid photographs. The feeling is assertive but sociable: spacious editorial compositions, tiny functional controls and a spectacular closing line rather than conventional sales-page furniture.

### Essentials

- Billboard typography behaves like an object: uppercase Grotesk at 386.2px/0.75 for the main impact statement and 170.4px/0.76 for chapter and closing lines, both weight 400 with normal tracking.
- An introduction precedes the visual shout: a left-aligned 43.2px/1.1 sans paragraph sits above an enormous two-line statement, with a 462px-wide portrait image overlapping its right side. Preserve this type-and-image collision even when the image is a simple original product photograph.
- The page has a working edge and a note-taking edge: the main desktop field is 1136px wide, starts 54px from the left and leaves a 250px right rail for 210px-wide translucent information widgets.
- Controls are miniature instruments, not pills: a 27px square icon with 4px corners sits 14px from a 12px monospace action; category tags use 3px corners and 10px monospace text.
- Colour arrives in scenes, not scattered decoration: the default opening is red on warm grey, the proof/editorial field is predominantly warm grey with dark type, and the close is cream on charcoal. Full red or fluorescent green fields belong to particular editorial or case-study variants.
- Proof is staged at two opposite scales: near-full-screen photographic scenes carry inset interfaces, while a disciplined six-column identity grid uses 179px-wide tiles and 12px gaps. If no interface exists, stage a genuine product artefact at the same scale.
- The ending is a second billboard: a compact right-half contact invitation and icon links lead into a 170.4px uppercase closing question, with a fading right edge, a fine bracket rule and 12px utility links beneath it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal red | `#fe3939` | `--color-signal` | text, accent, link, background | Opening typography, fine link underlines and red theme accents. Large red fills are reserved for the process-story opening. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm black | `#100b0a` | `--color-ink` | text, action | Main text and icon colour on the light field and bright case-study panels. |
| Closing charcoal | `#171616` | `--color-closing` | background | Shared closing field; also the dark editorial opening variant. |
| Light-field hairline | `#b3b3aa` | `--color-rule` | border | Subtle neutral edge on the light theme; red-theme edges instead use signal red at 20% alpha. |
| Identity tile grey | `#d2d2c8` | `--color-tile` | surface | Slightly darker, flat backing for monochrome identity tiles on the light canvas. |
| Warm grey canvas | `#dedcd3` | `--color-canvas` | background | Default light editorial field and opening backdrop. |
| Warm cream | `#f3f1e6` | `--color-cream` | text, surface, action | Closing typography and square icon backplates on charcoal. |
| Media white | `#ffffff` | `--color-white` | text, border, background | Project-image captions and tag text, white presentation fields in case studies, and 20% alpha edges over dark imagery. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| colour-led case studies | Fluorescent green | `#2eff74` | `--color-case-green` | background, accent | Immersive case-study title and presentation fields, paired with warm black. |
| service landing pages | Service warm dark | `#161414` | `--color-service-dark` | background | Red-on-dark service narrative field. |

## Typography

- **Montreal** — Introductions, body copy, navigation and large process numerals. Regular neo-grotesk, open and direct, with gently positive tracking in text sizes. If unavailable, use **Inter**. Use regular 400; preserve the positive tracking rather than adopting tight display settings. Font stack: "Montreal", "Inter", Arial, sans-serif.
- **Grotesk** — Monumental uppercase headlines and closing statements. Heavy-looking condensed grotesk with solid counters and very tight vertical stacking; its declared regular cut is visually forceful. If unavailable, use **Anton**. Use 400 and tune width before changing size; retain compressed line height. Font stack: "Grotesk", "Anton", Impact, sans-serif.
- **Supply** — Section labels, clock, category tags and compact action text. Small utilitarian monospace that makes labels feel like annotations rather than marketing eyebrows. If unavailable, use **IBM Plex Mono**. Use 400 at the small measured sizes. Font stack: "Supply", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| impact | Grotesk | 400 | 386.2px | 0.75 | normal, uppercase | Two-line opening impact statement; treat the wording as a large compositional shape. |
| billboard | Grotesk | 400 | 170.4px | 0.76 | normal, uppercase | Chapter statements, case-study titles and the shared closing question. |
| statement | Montreal | 400 | 43.2px | 1.1 | 0.02em | Opening introduction, substantial editorial statements, service title and long testimonial. |
| body | Montreal | 400 | 18px | 1.4 | 0.02em | Editorial paragraphs and capability lists. |
| utility | Montreal | 400 | 12px | 1.3 | 0.023em | Navigation, widget descriptions and footer utility links. |
| label | Supply | 400 | 12px | 1.3 | 0.01em | Section headings, subheadings and attribution labels; often at 0.75 opacity. |
| action | Supply | 400 | 12px | 1.3 | 0.023em | Icon-link text and live time display. |
| micro | Supply | 400 | 10px | 1.26 | 0.01em | Image tags, compact image captions and widget destinations. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| process explanations | process-number | Montreal | 400 | 140px | 1.1 | normal | Freestanding step numbers above small labels and short explanations. |

**Notes:**

- Keep the extreme contrast between colossal display type and 10–12px annotation type. Do not fill the hierarchy with multiple medium-weight heading tiers.
- The display face has a heavy appearance at its declared 400 weight; do not apply synthetic bold. Its line boxes intentionally overlap the apparent capital height.
- Positive tracking belongs to the sans and mono text. Display tracking stays normal.
- The root size follows max(20px, 8px + 0.83333vw); rem-based text and spacing therefore grow above the desktop minimum. The listed recipes describe the desktop composition.

## Layout

**Density:** Airy editorial fields with tightly packed labels and controls; the large empty areas are balanced by enormous type and immersive media.

### Spacing

**Spacing system:**

- **layout unit** 20px — Declared outer grid margin and grid gap; main column gutters use this unit.
- **half unit** 10px — Compact group gaps and the base of the common 30px, 50px, 60px, 100px and 150px rhythms.

| Value | Use |
| --- | --- |
| 10px | Tag and widget-stack gaps. |
| 12px | Identity grid gutters and project overlay insets. |
| 14px | Widget padding and icon-to-label gap. |
| 20px | Main grid gutters and rail side margins. |
| 30px | Column content gaps and space below carousel controls. |
| 50px | Contact link group spacing and large internal content gaps. |
| 54px | Desktop left inset. |
| 60px | Paragraph-to-media separation and short chapter breathing room. |
| 100px | Opening top padding and regular section lead-in. |
| 150px | Major editorial chapter separation. |
| 200px | Extended case-study presentation breathing room. |

### Containers and grids

- **Main field and rail**: max width 1440px · gap 20px · side padding 54px. At desktop, reserve 250px on the right rather than centering the content. The main field is 1136px wide; the right rail contains 210px widgets with 20px side margins.
- **Split editorial**: max width 1136px · 2 columns · gap 20px. Two 558px columns. Small metadata occupies the left; substantive paragraphs often occupy only the right half.
- **Identity proof**: max width 1136px · 6 columns · gap 12px. Three rows of shallow monochrome identity tiles; add a rail action alongside rather than inside the grid.
- **Process stagger** (only for process explanations): max width 1136px · 3 columns · gap 20px. 365px columns. Two steps occupy the right two columns of one row, then the left two columns of the next, creating a descending diagonal.

## Corner radius

| Element | Radius |
| --- | --- |
| Media and widgets | 4px |
| Category tags | 3px |
| Clock outline | 50% |

## Surfaces and depth

### Surfaces

#### Editorial canvas · level 0

**Use:** Default marketing-page field.

**CSS:** `background: #dedcd3; color: #100b0a`

**Observed:** A warm, slightly grey paper-like colour without visible fibre or texture.

**Transfer:** Let typography and photography supply the contrast rather than adding gradients to the canvas.

#### Closing field · level 0

**Use:** Shared ending and final editorial transition.

**CSS:** `background: #171616; color: #f3f1e6`

**Observed:** Flat charcoal continues behind the contact invitation, billboard line and bottom utilities.

**Transfer:** Carry the final content into this field so the footer feels like a designed chapter, not a separate widget.

#### Rail glass · level 1

**Use:** Small information widgets over the current page colour or image.

**CSS:** `background: transparent; border: 1px solid rgba(254,57,57,0.2); border-radius: 4px; backdrop-filter: blur(10px); padding: 14px`

**Observed:** Transparent rather than frosted white; the theme changes its text and edge colour. No shadow.

**Transfer:** Use for one short supporting note or destination, keeping the backdrop visible.

#### Identity backing · level 0

**Use:** Uniform logo proof tiles.

**CSS:** `background: #d2d2c8; border-radius: 4px`

**Observed:** A shallow contrast change from the canvas; centred monochrome marks appear embedded in a flat grid.

**Transfer:** Normalize the backing and visual scale of partner or integration marks.

#### Bright case field · level 0

**Only for:** colour-led case studies

**Use:** Title and large media-presentation chapters.

**CSS:** `background: #2eff74; color: #100b0a`

**Observed:** An uninterrupted fluorescent field alternates with black and white presentation chapters.

**Transfer:** Use one project-specific saturated colour as a scene, not as a second global brand accent.

#### Dark service field · level 0

**Only for:** service landing pages

**Use:** Long capability and technical-partner narrative.

**CSS:** `background: #161414; color: #fe3939`

**Observed:** Red text, red identity marks and low-contrast red-tinted presentation tiles sit on a nearly black field.

**Transfer:** Keep this a whole-page narrative theme rather than interspersing many unrelated coloured cards.

## Components

### Fixed navigation

**Use:** Persistent orientation without competing with the media.

**CSS:** `position: fixed; height: 52px; z-index: 20; width: 100%`

**Text style:** `utility` — Montreal 400 · 12px/1.3 · tracking 0.023em

**Observed:** Brand mark at left, three short navigation links immediately after it, clock and location in the right rail. A masked 8px backdrop-blur layer extends to 70px and fades below the header; a thin bracket edge aligns with the main field.

**Transfer:** Keep the link count compact and use product-specific navigation nouns.

### Square icon action

**Use:** Main contact and contextual destination actions.

**CSS:** `display: flex; align-items: center; gap: 14px; max-width: 320px`

**Text style:** `action` — Supply 400 · 12px/1.3 · tracking 0.023em

**Observed:** A small filled square containing a simple line or silhouette symbol precedes the plain text destination. The square is 27px with 3px inner padding and 4px corners; its colour inverts with the theme. Actions are paired horizontally with 50px between groups.

**States:** Declared: hover values are not specified; focus-visible uses a 2px solid #1e90ff outline, 5px offset and 1px corner radius.

**Transfer:** Use a message, phone or outbound-arrow symbol appropriate to the action; the text stays outside the square.

### Underline link

**Use:** Inline destinations and compact widget links.

**CSS:** `background-image: linear-gradient(#fe3939, #fe3939); background-size: 0% 0.8px; background-position: 0px 100%; background-repeat: no-repeat; transition: background-size 0.5s`

**Text style:** `micro` — Supply 400 · 10px/1.26 · tracking 0.01em

**Observed:** The underline is a background-image treatment, not a persistent thick rule. Body links inherit the 18px paragraph recipe; contact links use the action recipe.

**States:** Declared: hover end size is not specified; focus-visible uses a 2px solid #1e90ff outline with 5px offset.

### Rail note

**Use:** Contextual proof, contact detail or secondary conversion beside a section.

**CSS:** `width: 210px; padding: 14px; display: grid; gap: 10px; border: 1px solid rgba(254,57,57,0.2); border-radius: 4px; backdrop-filter: blur(10px)`

**Text style:** `utility` — Montreal 400 · 12px/1.3 · tracking 0.023em

**Observed:** A brief title or note sits above an icon-and-destination row. Height follows content, commonly 58px or 83px. It belongs in the reserved rail, not in a row of feature cards.

**Transfer:** Write one concrete fact or destination per note.

### Identity grid

**Use:** Compact social or integration proof.

**CSS:** `display: grid; grid-template-columns: repeat(6, 1fr); gap: 12px`

**Observed:** Eighteen shallow tiles fill three rows. Each cell is about 179px wide; its identity artwork is approximately 112px high within a 118px row box. Marks are centred and monochrome on Identity backing.

**Transfer:** Use genuine partner identities or a consistent text-only identity treatment; retain the uniform tile structure.

### Project teaser

**Use:** Large visual proof in carousels and related-project sections.

**CSS:** `position: relative; padding: 12px; display: flex; border-radius: 4px; overflow: hidden`

**Text style:** `micro` — Supply 400 · 10px/1.26 · tracking 0.01em

**Observed:** Portrait photographic backing, approximately 558px wide and 692px tall, with an interface inset across its centre. Small name and descriptor sit at the top left, categories at top right or along the bottom. The horizontal carousel exposes clipped neighbouring cards; previous and next arrows sit beside its small section label.

**Transfer:** Pair an authentic use-context photograph with one legible view of the new product. Do not add a white text-card footer.

### Category tag

**Use:** Project categories and technology labels over images or on case title fields.

**CSS:** `border: 1px solid rgba(255,255,255,0.2); border-radius: 3px; color: #ffffff; position: relative`

**Text style:** `micro` — Supply 400 · 10px/1.26 · tracking 0.01em

**Observed:** Compact rectangular outline; an inner text wrapper uses 8px vertical and 13px horizontal padding, yielding a 31px outer height. Tags wrap with 10px gaps. The bright-field variant uses dark text and a dark 20% alpha edge.

**States:** Declared: hover end colour is not specified; focus-visible uses a 2px solid #1e90ff outline with 5px offset. Border-colour transition is 0.2s.

### Bracket rule

**Use:** Frame the main field below navigation and above the final page edge.

**CSS:** `height: 24px; border: 1px solid rgba(254,57,57,0.2); border-radius: 4px; mask-image: linear-gradient(rgb(0,0,0) 50%, rgba(0,0,0,0) 0px)`

**Observed:** Only one half of a rounded rectangular outline is visible, producing a long hairline with short downturned ends. The bottom version reverses the mask and uses a 30% edge.

**Transfer:** Align the bracket to the main editorial field, leaving the note rail outside it.

### Numbered process step

**Only for:** process explanations

**Use:** Explain a short sequence without boxing it into cards.

**CSS:** `display: flex; flex-direction: column; gap: 30px`

**Text style:** `process-number` — Montreal 400 · 140px/1.1

**Observed:** A freestanding large sans numeral is followed by a 12px monospace stage title and an 18px explanation. The title-to-body space is about 18px; no border, fill or connecting line.

**Transfer:** Use a small number of purposeful steps and the Process stagger layout.

## Imagery and graphics

### Overlapping proof photograph

**Use:** The signature opening collision of typography and real-world evidence.

**Observed:** A tall black-and-white photograph of physical objects sits in front of enormous red text, covering part of the rightmost letters. The framing is direct and unpolished, with 4px media corners; the image is about one third of the viewport wide.

**Transfer:** Photograph a real object, customer setting or product artefact in an ordinary environment, then use a tight monochrome portrait framing. A single well-lit original photograph is the minimum equivalent; do not replace it with an icon.

### Interface in a world

**Use:** Project teasers and immersive full-width demonstrations.

**Observed:** A website view floats at roughly three quarters of a portrait card's width over evocative photography: desert and mirrored slabs, soft green meadow, a historical portrait, or a product close-up. Full-width versions use a centred landscape interface over clouds, fabric or documentary imagery. The backing remains visually substantial rather than becoming a blur behind a tiny screen.

**Transfer:** Choose a use-context scene with its own light and material character; inset one clean front-facing product view. Without a digital interface, substitute a photograph of a meaningful product detail, framed with the same scale contrast.

**Build:** Create a relative, overflow-hidden panel with 4px corners. Fill it with an object-fit: cover photograph. Place a flat interface rectangle centrally at 75% of panel width, without a browser-toolbar illustration; keep top annotations above it. For an atmospheric alternative, use an original sky or softly focused natural-light photograph, not a multicolour mesh gradient.

### Taped editorial photographs

**Only for:** people and process stories

**Use:** Interrupt large headlines and offset editorial chapters with tactile personal imagery.

**Observed:** Candid office, travel and shared-meal photographs alternate between full-width landscapes and narrow portraits. Smaller portraits tilt slightly and have irregular translucent tape strips across the top. Two unequal images can share a row, with the larger one bleeding to the right edge.

**Transfer:** Use actual people and working contexts with daylight and ordinary colour. Avoid corporate stock handshakes and overly coordinated studio portraits.

**Build:** Place a portrait image at 365px width, rotate it a few degrees, and overlay a 35px-high translucent grey-white SVG polygon across its top edge. Use uneven polygon corners, rgba(255,255,255,0.25) fill and two faint diagonal crease lines. Keep the tape separate from the photograph, with no thick surrounding frame.

### Reflective numeral object

**Only for:** editorial benefit or culture stories

**Use:** A playful physical punctuation mark for a numerical claim.

**Observed:** An oversized silver foil numeral balloon overlaps a chapter heading and sits beside a right-half text block. Black reflections, bright crinkled highlights and a softly shaded underside make it feel materially real.

**Transfer:** Use a single reflective object related to a truthful number or benefit. If photorealistic rendering is unavailable, photograph a real foil object against a neutral wall; do not substitute a flat emoji.

**Build:** Use a transparent cutout photograph or a 3D extruded numeral with rounded inflated edges, metallic silver material, strong dark environment reflections and wrinkled seam details. Size the object around 462px wide and 588px high, overlapping the preceding heading rather than centring it over the paragraph.

### Case-study presentation collage

**Only for:** detailed case studies

**Use:** Demonstrate a system across artefacts and devices.

**Observed:** Large staggered desktop views, approximately 558px wide, combine with 269px-wide phone views. Fluorescent green, black and white fields alternate around museum objects, rich photography and flat interface boards. Phones overlap boards instead of sitting in equal device slots.

**Transfer:** Present a few representative product states at sharply different scales; keep colours inside the product distinct from the marketing palette. Use a clean original device frame or a flat mobile view if a realistic frame is unavailable.

### Icons

**Observed:** Small, simple arrows, eye, message, phone and clock symbols. Icon artwork is generally 18–24px; action icons sit in 27px rounded-square backplates. The header clock uses a 13px circular outline.

**Transfer:** Choose recognisable utilitarian symbols with little detail. Use theme-inverted icon squares for actions and bare arrows for carousel navigation, not a decorative feature-icon library.

## Section recipes

How recurring sections are built.

### First screen: Introduction and billboard opening

**Observed:** The first screen is a warm-grey field with a fine Fixed navigation layer in front. A 43.2px statement spans most of the 1136px main field above the main event. Below it, the impact headline stacks two very short uppercase lines, occupying much of the left and middle field; the 386.2px type is almost architectural. A 462px-wide monochrome portrait sits in front of the right side of the lettering and aligns near the main field's right edge, not the viewport edge. Within the first 900px, navigation, the full introductory statement, both giant headline lines and most of the portrait are visible. Explanatory proof copy and carousel controls follow below the fold; there is no oversized hero CTA button.

**Transfer:** Write one plain-language product introduction and a separate two-to-four-word impact phrase. Layer one real photograph over the phrase; use a physical artefact or original product-detail photograph when no campaign film exists. People/process stories can begin directly with the impact phrase and a taped portrait. Service pages instead begin with a 43.2px title, a right-half 18px explanation and the start of an immersive demonstration. Case studies use the billboard recipe on a saturated field with categories and a split summary.

**Avoid:** Do not centre a conventional headline, supporting paragraph and pill-button stack above a tidy screenshot. Do not reduce the impact statement to a normal section heading or move the image into a non-overlapping adjacent card.

**Text style:** `impact` — Grotesk 400 · 386.2px/0.75 · uppercase

### Annotated editorial statement

**Observed:** A small label introduces a 43.2px statement across the main field, or a 12px label and 18px paragraph occupy just one 558px half. Chapters use 100px or 150px top separation; image-led continuations may begin after only 60px.

**Transfer:** Alternate broad declarative statements with narrower explanations; let blank space in the opposite half create pace.

**Text style:** `statement` — Montreal 400 · 43.2px/1.1 · tracking 0.02em

### Visual proof carousel

**Observed:** A 12px monospace section heading and bare previous/next arrows sit above Project teaser cards, separated by 30px. Tall images dominate the section; partially visible neighbours communicate horizontal continuation.

**Transfer:** Group several specific proof examples into a visual gallery rather than a list of identical feature cards.

### Identity proof field

**Observed:** A small section heading precedes Identity grid. A Rail note provides the next destination. A supporting 18px paragraph can sit in the right half below the grid, with 60px separation.

**Transfer:** Use identities to establish breadth, then add a short interpretation of what that breadth means for the new audience.

### Offset image and chapter

**Observed:** A billboard chapter line leads into a portrait on the left and 18px text on the right. The portrait can overlap the headline by 50–100px and sit inward from the left field edge. People/process variants use Taped editorial photographs; full-width photos create a contrasting pause.

**Transfer:** Let one photograph interrupt the typographic rhythm and carry the human or material story without an enclosing card.

**Text style:** `billboard` — Grotesk 400 · 170.4px/0.76 · uppercase

### Staggered process explanation

**Observed:** A billboard chapter title and short explanatory paragraph introduce Numbered process step components. Steps descend from the right two columns to the left two columns over two rows, with 60px row lead-ins.

**Transfer:** Use this for methodology, onboarding or a product workflow; keep explanations short enough for the 365px columns.

### Immersive case narrative

**Observed:** Bright case field, black and white presentation fields support Case-study presentation collage at near-screen scale. Right-half label-and-paragraph commentary alternates with media; a large 43.2px testimonial spans the main field with a small attribution above. Near the end, compact metadata and question-and-answer copy form a two-column information section, followed by related Project teaser cards.

**Transfer:** Keep the narrative specific: premise, decisions, demonstrations and outcome. Use compact explanatory information only after the visual argument has been made.

### Monumental contact close

**Observed:** Closing field contains a 542px-tall footer. In its upper portion, a right-half contact label and 18px invitation lead to two Square icon action links; an address Rail note sits at the far right. A billboard closing question stretches across nearly the full main field, with 50px above and 80px below its lettering. Its right edge fades into the background. Below are 12px copyright and social/legal utilities, a reversed Bracket rule, and a clock/status note in the rail.

**Transfer:** End with a short human invitation relevant to the product, then a huge closing question or phrase. Preserve the large-to-small scale jump and the right-edge fade rather than substituting a boxed newsletter banner.

**Text style:** `billboard` — Grotesk 400 · 170.4px/0.76 · uppercase

## Page flow

**Storyline:** Plain-language premise → oversized emotional hook → immersive proof → narrower explanatory chapters → credibility and human detail → monumental invitation.

### Broad marketing introduction that balances personality with proof

1. **Premise and hook** — A large sans introduction leads into an enormous two-line phrase and overlapping monochrome photograph.
2. **Visual proof** — A short contextual paragraph gives way to a tall project carousel, then a six-column identity field.
3. **Depth and personality** — An immersive demonstration precedes a billboard statement and staggered personal photographs with compact explanatory copy.
4. **Closing call** — A charcoal contact chapter ends in a huge question, tiny utilities and a bracket edge.

**Transfer:** Use a clear introductory promise, specific visual demonstrations and one human or material detail before the closing invitation.

### Detailed case study explaining a product or platform transformation

1. **Project premise** — A fluorescent title field pairs a large title with category tags and a split summary above an immersive demonstration.
2. **Context and decisions** — Metadata and right-half narrative alternate with staggered object, desktop and mobile imagery.
3. **External validation** — A small attribution introduces a substantial sans testimonial on a white field.
4. **Outcome and depth** — Further demonstration scenes lead to compact questions and answers about implementation and results.
5. **Continuation and closing call** — Related visual projects precede the shared charcoal closing invitation.

**Transfer:** Make colour project-specific, show decisions through artefacts and keep the shared close stable.

### Service landing page establishing capability and delivery credibility

1. **Promise** — A modest large-sans title sits left, explanation right, then an immersive product scene begins.
2. **Capability** — A broad statement introduces a long simple list of services.
3. **Proof** — Identity grid and portrait project carousel show range.
4. **Delivery detail** — Partner marks and compact technical descriptions alternate in a four-column grid.
5. **Credibility and closing call** — A substantial statement and a plain recognition list lead to one full-width visual case and the common contact close.

**Transfer:** Replace the service list and technical partners with concrete product capabilities and ecosystem proof, keeping the red-on-dark scoped theme.

### Human story that makes a team or community tangible

1. **Personality** — Huge red uppercase wording on black is interrupted by a taped monochrome photo strip.
2. **Values through scenes** — Short commentary alternates with daylight office, travel and meal photographs on warm grey.
3. **Specific differentiators** — Billboard benefit headings, offset portraits and a reflective numeral object give individual facts visual weight.
4. **Collective proof and closing call** — A large group photograph leads directly into the shared charcoal close.

**Transfer:** Describe the new organisation's actual behaviour through real scenes and truthful details rather than a generic values grid.

### Explain an approach while retaining the personality of an editorial landing page

1. **Scope and promise** — Black impact lettering on a full-red field meets a small taped working photograph.
2. **Working context** — A short explanation and full-width collaboration photograph lead to a broad sans statement.
3. **Method** — Huge chapter lettering introduces a four-step stagger of large regular sans numerals and tiny mono stage labels.
4. **Craft and confidence** — Unequal photographic pairs and an offset portrait support a detail-focused chapter, then a broad client-oriented statement.
5. **Closing call** — The shared charcoal contact chapter ends the story.

**Transfer:** Use a short authentic process and material examples of care; avoid turning the staggered method into a software-dashboard diagram.

## Writing

Confident about craft, relaxed about itself and warmly collaborative. Broad statements of intent are balanced by concrete work, ordinary human details and occasional cheeky asides.

**Do not copy:** Do not reuse the agency name, client names or identities, project artwork, awards, project counts, team demographics, working-week claims, address, contact information or testimonial. Replace every factual claim with the new product's own substantiated material. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we for the makers and you for the prospective collaborator; invitations sound person-to-person rather than like funnel commands.
- **Rhythm:** Impact phrases are usually two to five words. The larger sans statements can be full sentences; 18px paragraphs are conversational and moderately long. Tiny labels are terse, descriptive and usually sentence case; exuberant capitals are reserved for display and occasional playful asides.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Impact phrase | Short, direct phrase that can be stacked into a visual object. | 2–5 words | “WE WON”<br>“From A to Z” |
| Chapter heading | A memorable noun phrase or crisp benefit, not a keyword-heavy sentence. | 2–4 words | “Lasting First Impressions”<br>“Attention to Detail” |
| Annotation | Plain description of what the following content is. | 3–8 words | “Some of our work”<br>“Small but agile” |
| Invitation | A direct human request followed by a collaborative possibility. | 1–2 short sentences | “Tell us about your project. Let’s collaborate and make great stuff.” |
| Action | Short verb-led destination in ordinary language. | 2–5 words | “Write us”<br>“See open positions”<br>“Drop us a DM” |

**Words and phrasing to use:** craft; creating; collaborate; together; experience; purpose; detail; great stuff

**Avoid:** revolutionary all-in-one solution; unlock unparalleled synergy; crush your competition; limited-time urgency; frictionless everything

**Rules:**

- Let a short emotional phrase and a longer factual statement do different jobs.
- Use concrete descriptions of the product or work before abstract praise.
- Allow one warm or playful aside in an otherwise useful explanation.
- Keep metadata and navigation literal; the visual typography already supplies enough personality.

## Do's and Don'ts

### Do

- Keep display weight at 400 and preserve the compressed 0.75–0.76 line heights.
- Use the 54px left inset and 250px rail reservation to create an intentionally off-centre desktop composition.
- Pair the giant impact phrase with one overlapping portrait-scale photograph.
- Keep paragraph text at 18px/1.4 and most annotations at 12px/1.3.
- Use 4px corners on media and widgets, and 3px corners on category tags.
- Give major editorial chapters 100px or 150px breathing room while keeping controls compact.
- Keep partner proof monochrome and regular within the six-column, 12px-gap grid.
- Retain the giant closing line, small contact actions and bracket edge as a designed final impression.

### Don't

- Do not replace the condensed display face with a wide geometric sans at the same nominal size.
- Do not apply negative tracking to the 18px body text; its 0.02em spacing is part of the texture.
- Do not turn the 27px icon-square action into a filled pill or a 48px-high standard CTA.
- Do not centre the main content inside equal side gutters; that erases the working rail.
- Do not add drop shadows to widgets, identity tiles or project cards.
- Do not spread fluorescent green across ordinary landing-page controls; it belongs to the case-study theme.
- Do not turn every 12px section label into an uppercase, widely tracked marketing eyebrow.
- Do not use a dense three-up feature-card wall in place of the alternating editorial and immersive image fields.

## Motion and responsive

### Motion

**Observed:**

- Theme text and background declare .4s ease-out transitions.
- Link underlines declare background-size 0.5s; tag edges declare border-color 0.2s.
- Media wrappers declare opacity .4s ease-out, and icon backplates declare background-color .4s ease-out.
- A sweep animation declares calc(1000*4ms) infinite alternate ease-in-out; the closing title has a horizontal translation and right-edge mask.
- Some offset media has translated and rotated positioning, creating layered parallax relationships.

**Transfer:**

- Preserve the slow horizontal life of the monumental closing line and its fading edge.
- Let image reveals and theme changes stay subordinate to the oversized typography rather than animating every label.

**Unknown:**

- Scroll-trigger timing, exact parallax mapping and hover end values are not specified.

### Responsive

**Observed:**

- Width breakpoints are declared at 350px, 576px, 899px, 900px, 1199px, 1200px and 1399px.
- The root-size rule is max(20px, 8px + 0.83333vw); rem-based dimensions scale with it.

**Transfer:**

- On narrow layouts, move rail notes into the relevant chapter rather than preserving a 250px empty rail.
- Keep the impact phrase dramatically larger than body copy, but rewrap its words and reposition the overlapping photograph so both remain readable.
- Reduce identity-grid column count while retaining equal tile backing and compact gutters; preserve horizontal continuation for visual proof galleries.
- Stack editorial columns and preserve a small amount of overlap rather than shrinking the desktop composition as a single image.

**Unknown:**

- Exact mobile type sizes, column counts, navigation replacement and overlap offsets are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
