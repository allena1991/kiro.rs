# Altius Labs — ember-lit machinery

## Overview

A technical, assured marketing style with the warmth of red-hot machinery rather than the chill of conventional enterprise software. Near-black brown stages alternate with pale peach and lavender-white, while coral light and fine drafting marks make abstract systems feel tangible. Tightly tracked grotesk headlines, utilitarian mono labels and sparse schematic art suit complex infrastructure and high-stakes products without making the page feel dense.

### Essentials

- A promise above a luminous waveform: center a 60px/1.08 medium headline, 20px/28px support and compact paired actions above a full-bleed, roughly 389px-high field of vertical coral light bars. Carry this light sculpture into every new landing page, even when there is no product media.
- Warm darkness carries most of the experience: roughly two thirds of the landing page is #190501, interrupted by substantial #feeae6 and #f7f6ff chapters. Use #fa5838 for light, fine edges, numbering and links rather than ordinary full-width fills.
- Headlines feel compressed but not heavy: Matter 500 at 60px with -2.5px tracking for the promise, 48px/54px with -1.6px for chapter headings; the bold 24px card title is a deliberate exception.
- Actions resemble illuminated instrument switches: square corners, 38px height, 8px 16px padding and 1px warm borders. Pair a dark inset-glowing button with a pale peach filled button in the opening.
- Proof is staged like an engineering plate: technical line art on pale fields, compact uppercase mono annotations, 1px rules and 8px corner registration marks. Include this drafting language on new pages; a simple SVG system drawing is the minimum equivalent.
- Capabilities are numbered modules, not soft tiles: three equal columns inside 1130px with 20px gaps, #340a01 panels, coral borders, 20px padding and 20px mono numbers beside small icons.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Ember coral | `#fa5838` | `--color-ember` | accent, border, action, link | Light sculpture, numeric labels, links and capability edges. A full-bleed fill belongs only to the organizational statement variant. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep rust | `#951c04` | `--color-rust` | text, border | Body text on pale sections and dark action borders. |
| Light salmon | `#fcac9c` | `--color-salmon` | text, border, accent | Supporting text on dark stages, pale card edges, registration corners and outlined companion actions. |
| Inset red | `#631303` | `--color-glow` | accent, text | Warm inset action glow; also biography text in the people variant. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Oxide panel | `#340a01` | `--color-panel` | surface, border | Capability panel fill, dark social-button edges and footer rule. |
| Brown black | `#190501` | `--color-dark` | background, text | Dominant dark stages and footer; primary text on pale chapters. |
| Peach paper | `#feeae6` | `--color-peach` | background, surface, text | Problem chapter, filled companion action and warm light text inside capability panels. |
| Lavender white | `#f7f6ff` | `--color-paper` | background, text | Light technical-proof canvas and high-contrast headings on dark stages. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| organizational storytelling and people sections | Copper | `#c2410c` | `--color-copper` | text, accent | People names, role labels and mission eyebrow. |
| organizational statement bands | Statement ink | `#1a0a06` | `--color-statement-ink` | text | Very dark headline and copy over the saturated statement band. |

## Typography

- **Matter** — All prose, headings, navigation and button labels. Compact contemporary grotesk with rounded bowls and a large readable lowercase; medium-weight display text feels direct rather than industrially heavy. If unavailable, use **Inter**. Use weights 400–700 and retain the tight display tracking. Font stack: "Matter", "Inter", Impact, sans-serif.
- **Fabrikatmono** — Uppercase eyebrows, numbering, footer links and technical markings. Condensed utilitarian monospace, giving the fine graphic labels an equipment-panel quality. If unavailable, use **Barlow Condensed**. Use weights 400–500; this prioritizes narrow industrial construction over fixed pitch. Font stack: "Fabrikatmono", "Barlow Condensed", Impact, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Matter | 500 | 60px | 1.08 | -0.0417em | Centered landing promise; also the monumental statement headline. |
| heading | Matter | 500 | 48px | 1.125 | -0.0333em | Chapter headings, capability introduction and closing invitation. |
| card-title | Matter | 700 | 24px | 1.16 | normal | Short capability titles; the notably bold part of the hierarchy. |
| body-lead | Matter | 400 | 20px | 1.4 | -0.04em | Hero support and section explanations; salmon on dark, rust on pale. |
| module-number | Fabrikatmono | 500 | 20px | 1.5 | -0.04em | Two-digit capability indices. |
| body | Matter | 400 | 16px | 1.5 | normal | Capability details and navigation. |
| eyebrow | Fabrikatmono | 500 | 16px | 1.5 | normal, uppercase | Trust caption and section labels. |
| action | Matter | 500 | 16px | 1.25 | -0.01em | All rectangular conversion buttons. |
| footer-link | Fabrikatmono | 400 | 16px | 1.75 | -0.05em, uppercase | Compact footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| company and people pages | company-display | Matter | 600 | 52px | 1.08 | -0.0385em | Two-line centered organizational introduction. |
| people sections | person-name | Matter | 500 | 36px | 1.22 | -0.0333em | Names within biography cards. |
| people sections | person-role | Fabrikatmono | 500 | 20px | 1.5 | -0.04em, uppercase | Role label at the top of a biography card. |

**Notes:**

- Tighten tracking as sans headings grow; reserve normal tracking for the bold card titles and small body copy. Do not turn the prose into monospace.
- Most headings use medium weight, with compact balanced line breaks. Body leads can span several lines but remain visually subordinate through warm lower-contrast color.
- Keep diagram annotations subordinate to the marketing type hierarchy; they are part of the illustration rather than a second page-wide type system.

## Layout

**Density:** Airy sections around comfortable, fairly compact information modules; broad empty fields separate technical statements.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-button padding and corner-mark extent. |
| 16px | Paired action gap and social-icon group gap. |
| 20px | Headline/support separation, module gaps and panel padding. |
| 32px | Navigation link spacing and gap before the opening artwork. |
| 40px | Outer desktop gutters and section-heading-to-action separation. |
| 48px | Trust-panel interior spacing. |
| 64px | Footer vertical padding. |
| 100px | Standard chapter top and bottom breathing room. |
| 180px | Organizational-page introduction and closing-stage breathing room; not the default product chapter padding. |

### Containers and grids

- **outer-frame**: max width 1440px · side padding 40px. Full-width stage with inset header, trust plate and footer.
- **chapter-container**: max width 1130px. Centered core content; splits into two 555px columns separated by 20px.
- **split-chapter**: max width 1130px · 2 columns · gap 20px. Schematic at left and explanation at right, vertically centered.
- **module-grid**: max width 1130px · 3 columns · gap 20px. Equal-width capability cards; reused for biography cards in the people variant.
- **hero-copy**: max width 670px. Centered support text and actions; the short main heading may extend beyond this width.
- **technical-proof**: max width 900px. Left-aligned chapter heading and support over a centered wide technical diagram.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | rectangular-controls-and-panels | 0px |
| people sections | portraits | 50% |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| action-glow | `inset 0px 0px 20px 0px #631303` | Primary dark action, never a floating-card elevation. |
| dark-companion-inset | `inset 0px 0px 20px 0px #190501` | Outlined companion action within dark capability chapters. |

### Surfaces

#### Dark stage · level 0

**Use:** Opening, trust, capabilities, closing invitation and footer.

**CSS:** `background: #190501; color: #f7f6ff`

**Observed:** Full-width brown-black fields make luminous artwork and fine red rules visible.

**Transfer:** Let broad dark space surround the content rather than boxing every chapter.

#### Peach chapter · level 0

**Use:** Explanatory contrast to the dark stages.

**CSS:** `background: #feeae6; color: #190501`

**Observed:** Flat warm paper behind a technical drawing and prose; no generic background gradient.

**Transfer:** Use for problem framing or a concise explanation.

#### Pale proof canvas · level 0

**Use:** Technical proof and diagrams.

**CSS:** `background: #f7f6ff; color: #190501`

**Observed:** A faint lavender cast distinguishes it from the warm peach chapter.

**Transfer:** Keep diagram artwork unboxed on the canvas.

#### Capability panel · level 1

**Use:** Numbered capability modules.

**CSS:** `background: #340a01; border: 1px solid #fa5838; border-radius: 0px; backdrop-filter: blur(4px)`

**Observed:** Fine corner registration accents lighten the rectangular perimeter; the panel is opaque-looking, not frosted white glass.

**Transfer:** Use the border and fill for modules whose content should read as an engineered system.

#### People panel · level 1

**Only for:** people sections

**Use:** Biographies within a pale section.

**CSS:** `background: #feeae6; border: 1px solid #fcac9c; border-radius: 0px; backdrop-filter: blur(8px)`

**Observed:** The same sharp registration corners are reused in a pale material.

**Transfer:** Keep the warmth and fine edges when adapting to experts or contributors.

#### Coral statement band · level 0

**Only for:** organizational storytelling

**Use:** A single expansive statement of standards or direction.

**CSS:** `background: #fa5838; color: #1a0a06`

**Observed:** A broad saturated red-orange interruption with a large left-aligned headline and a narrow support paragraph, followed by extensive empty space.

**Transfer:** Reserve this high-color variant for a strong organizational belief, not ordinary feature grids.

## Components

### Fixed navigation

**Use:** Persistent top-level site navigation.

**CSS:** `position: fixed; height: 68px; background: #190501; padding: 14px 40px; z-index: 101`

**Text style:** `body` — Matter 400 · 16px/1.5

**Observed:** Coral identity at left, a compact right-aligned link group and two square social actions. A resource label has a small downward chevron; ordinary links remain peach rather than coral.

**Transfer:** Keep only a few navigation destinations and preserve the asymmetric empty middle.

### Primary button

**Use:** Main conversational conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; height: 38px; padding: 8px 16px; border: 1px solid #951c04; border-radius: 0px; background: transparent; color: #fa5838; box-shadow: inset 0px 0px 20px 0px #631303; transition: all 0.2s ease`

**Text style:** `action` — Matter 500 · 16px/1.25 · tracking -0.01em

**Observed:** A short text-only rectangular control, placed beside the pale companion action or alone in the closing invitation.

**States:** Declared: hover border-color #fa5838 and outline 0px; focus-visible outline 0px; active outline 0px.

**Transfer:** Name a concrete next step rather than a generic motivational slogan.

### Companion button

**Use:** Specific low-friction conversion alongside the main action.

**CSS:** `height: 38px; padding: 8px 16px; border: 1px solid #951c04; border-radius: 0px; background: #feeae6; color: #951c04; transition: all 0.2s ease`

**Text style:** `action` — Matter 500 · 16px/1.25 · tracking -0.01em

**Observed:** Pale filled by default in the opening. In the dark capability chapter it becomes transparent with salmon text and border and a brown-black inset shadow.

**States:** Declared: hover border-color #fa5838 and color #fa5838; focus-visible outline 0px; active outline 0px. Dark chapter variant hover border-color and color #f7f6ff.

**Transfer:** Keep the commitment explicit, using a real duration only when it is true.

### Social square

**Use:** Small external destinations in navigation and footer.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 36px; height: 36px; padding: 8px; border: 1px solid #340a01; border-radius: 0px; color: #fa5838; transition: all 0.2s ease`

**Observed:** An 18px icon sits in a restrained square frame; groups use 16px gaps.

**States:** Declared: hover border-color #951c04, box-shadow inset 0 0 20px 0 #951c04 and color #fa5838; focus-visible outline 0px; active outline 0px.

### Numbered capability card

**Use:** A compact, benefit-led technical argument.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 20px; background: #340a01; border: 1px solid #fa5838; border-radius: 0px; backdrop-filter: blur(4px)`

**Text style:** `body` — Matter 400 · 16px/1.5

**Observed:** Top row pairs a two-digit Module-number with a small line-like technical icon on the right. Card-title and body follow. Four 8px corner marks sit over the border; cards align to a shared row height even when copy lengths differ.

**Transfer:** Write one benefit per module, with a short mechanism beneath it.

### Trust plate

**Use:** A restrained partner or customer proof interval.

**CSS:** `display: flex; flex-direction: column; align-items: center; padding: 48px; backdrop-filter: blur(2px)`

**Text style:** `eyebrow` — Fabrikatmono 500 · 16px/1.5 · uppercase

**Observed:** Centered coral mono caption over two broad rows of monochrome pale logos on the dark stage. Corner registration marks define the wide plate without a heavy enclosing card.

**Transfer:** Use real permissioned marks; if unavailable, place compact factual proof items in the same captioned plate.

### Footer navigation

**Use:** Quiet closing navigation rather than another sales banner.

**CSS:** `display: flex; flex-direction: column; row-gap: 4px; color: #fa5838`

**Text style:** `footer-link` — Fabrikatmono 400 · 16px/1.75 · tracking -0.05em · uppercase

**Observed:** Two compact link columns sit at the far right, separated by 80px; identity and four social squares sit left. A lower full-width brown rule separates subdued copyright from small uppercase legal links.

**States:** Declared: hover color #f7f6ff and outline 0px; focus-visible outline 0px; active outline 0px.

**Transfer:** Preserve the broad empty middle and visually subordinate legal material.

### Biography card

**Only for:** people sections

**Use:** Establish credibility through named expertise.

**CSS:** `display: flex; flex-direction: column; gap: 20px; padding: 20px; background: #feeae6; border: 1px solid #fcac9c; border-radius: 0px; backdrop-filter: blur(8px)`

**Text style:** `body-lead` — Matter 400 · 20px/1.4 · tracking -0.04em

**Observed:** Uppercase Person-role and social icons form the top row; a 64px circular portrait, Person-name and a brief career paragraph follow. Copper labels and names, deep rust prose and tiny corner ticks sit on peach.

**Transfer:** Describe present responsibility before previous experience; let rows grow to fit factual biographies.

## Imagery and graphics

### Luminous bar field

**Use:** Signature landing-page opening artwork below the promise and actions.

**Observed:** A horizontally overflowing band of adjacent vertical rectangular beams forms two peaks and a center trough. Coral-red light transitions through narrow hot peach-white centers into dark transparent ends. The graphic occupies the lower roughly 389px of the opening and is clipped by the viewport edges, with no enclosing frame.

**Transfer:** Keep a luminous abstract signal even without product assets; vary the rhythm of peaks to suggest the new product's energy without illustrating its interface.

**Build:** Create an SVG viewBox approximately 1962 by 389, centered in an overflow-hidden wrapper. Tile roughly 94px-wide rectangles with staggered heights into repeating rising and falling groups. Fill each with a vertical gradient using transparent #fa5838 at the ends, opaque #fa5838 around the middle and a thin #feeae6 hot zone. Offset each gradient center vertically with the bar height to form a traveling wave. Keep hard vertical seams and softened light only along the beam length; exact gradient stops are not essential.

### Drafting plate

**Use:** Explain a problem or system in a pale split chapter.

**Observed:** A red wireframe sphere is enclosed by a square targeting frame on lavender-white paper, with diagonal guide lines, tiny mono callouts, vertical margin labels and salmon annotation tabs. The artwork occupies about one column while prose occupies the other.

**Transfer:** Substitute a wireframe object, simplified process or topology for the new product. Retain fine geometry, small labels, restrained coral and a pale paper backing.

**Build:** Use a 555px-wide SVG art area. Center an outlined square panel with a smaller inset square; add 1px rust diagonal guides, coral latitude-like ellipses or a grid around one central object, and small mono captions at the corners. Add narrow salmon label strips outside two edges. Keep the actual concept readable without requiring decorative microcopy.

### Dark technical atmosphere

**Use:** Secondary artwork behind capabilities and beside a closing invitation.

**Observed:** A very faint oversized outlined emblem sits to the right, with sparse red particles over brown-black. It is lower-contrast than all text and not a polished solid 3D object.

**Transfer:** Use the new identity's own abstract geometry or a generic structural motif; it must remain background-scale rather than compete with the promise.

**Build:** Draw two or three nested angular paths in a roughly 444px by 336px SVG, using 1px #951c04 strokes at low opacity over #190501. Place at the right edge behind content. Add sparse 1px to 3px dots in #fa5838 at low alpha across the larger stage; do not add a bright neon halo.

### Exploded system diagram

**Use:** Technical proof before the footer.

**Observed:** Three dark burgundy isometric slabs float in a vertical exploded stack on lavender-white. Thin red edges, small icons and compact mono labels make them feel like machined parts. Dotted elbow leaders connect to black technical bullet annotations at right. The complete graphic is about 812px wide.

**Transfer:** Break the new system into two to four genuinely meaningful layers. A clean SVG axonometric drawing with editable labels is sufficient; photorealistic rendering is unnecessary.

**Build:** Draw stacked skewed quadrilateral tops with shallow extruded side faces in #340a01 and #190501; edge them in #951c04 and separate the slabs with visible air. Add small coral icons, muted annotation labels, and salmon dotted leader lines terminating in round rust nodes. Place text outside the stack on the pale canvas.

### People linework and portraits

**Only for:** company and people pages

**Use:** Humanize an organizational opening and expert grid.

**Observed:** The organizational opening uses overlapping circular heads and curved shoulder outlines above rising coral hairlines, not large lifestyle photos. The actual people appear as 64px circular upper-body portraits on light neutral backgrounds inside biography panels.

**Transfer:** Use an SVG community diagram above the fold and small consistent portraits within cards. Keep portrait lighting even and backgrounds simple.

**Build:** For the opening illustration, arrange five overlapping head circles with slightly varied heights in a 1000px-wide SVG, then draw broad intersecting shoulder arcs beneath them. Use fine salmon-to-transparent strokes over brown-black, with slender coral vertical lines rising from the bottom at varied heights.

### Icons

**Observed:** Technical glyphs are simple small SVGs in coral, roughly 24px within capability cards. Social glyphs are mostly solid 18px marks inside 36px squares; people-card social glyphs are copper and about 24px. Resource navigation has a small peach chevron.

**Transfer:** Choose a consistent sparse technical icon family. Keep benefit icons subordinate to the mono indices; reserve recognizable filled marks for actual social destinations.

## Section recipes

How recurring sections are built.

### First screen: Signal-field opening

**Observed:** Dark stage fills the opening, with Fixed navigation across the top. A centered single-line Display promise spans about half the viewport width, beginning after 164px of top space; its 670px-wide support block follows with 20px separation and three balanced lines. Primary button and Companion button sit centered 36px after the support, separated by 16px. The Luminous bar field begins 32px below the actions, fills the lower 389px and spills past both horizontal edges. Back to front: brown-black canvas, luminous field in the lower region, high-contrast heading and salmon support above it, actions and navigation. Within the first 900px the complete headline, support, both actions and the entire light field are visible; the trust caption and logo rows fall below.

**Transfer:** Lead with a short two-part product promise and preserve the large abstract signal field even without product media. For company storytelling, use Company-display over two lines, an eyebrow and People linework instead of conversion buttons; keep the centered dark-stage hierarchy.

**Avoid:** Do not replace the lower light field with a dashboard mockup, place the main headline over the hottest bars or turn the first screen into a left-copy/right-image template.

**Text style:** `display` — Matter 500 · 60px/1.08 · tracking -0.0417em

### Captioned trust interval

**Observed:** Trust plate sits in a generous continuation of the dark stage, with a centered mono eyebrow and pale logo rows. The plate is inset 40px from the outer frame and uses 48px internal padding and registration corners.

**Transfer:** Use as a visual pause with credible external proof; choose its position based on the new narrative.

**Text style:** `eyebrow` — Fabrikatmono 500 · 16px/1.5 · uppercase

### Problem and schematic

**Observed:** Peach chapter with 100px vertical breathing room and Split-chapter layout. Drafting plate is at left, Heading and Body-lead at right, separated within the text stack by 20px.

**Transfer:** Explain one expensive limitation in words, and make the adjacent graphic express that same constraint.

**Text style:** `heading` — Matter 500 · 48px/1.125 · tracking -0.0333em

### Numbered capability stage

**Observed:** Dark stage with an upper-left 555px-wide heading, an outlined companion action 40px below and Dark technical atmosphere on the right. A Module-grid of Numbered capability cards follows with 32px separation; each card is about 363px wide and the row is 356px tall. Use 100px section padding.

**Transfer:** Present a small set of differentiated benefits with mechanisms, not an exhaustive catalogue.

**Text style:** `heading` — Matter 500 · 48px/1.125 · tracking -0.0333em

### Pale technical proof

**Observed:** Pale proof canvas uses a 900px-wide content column, a left-aligned Heading and Body-lead with 20px separation, then the wide Exploded system diagram after about 60px. Ample lower breathing room leads straight to the dark footer rather than another large callout.

**Transfer:** Conclude a product narrative by showing how the system is assembled or why the promise is credible.

**Text style:** `heading` — Matter 500 · 48px/1.125 · tracking -0.0333em

### Sparse dark ending

**Observed:** Footer navigation sits in an Outer-frame with 64px top and bottom padding. Identity and social actions occupy the left, two slim mono link columns the right. A 1px panel-colored divider precedes the subdued legal row. The product narrative ends after technical proof; the organizational narrative adds a closing invitation before this same footer.

**Transfer:** Use the same restrained ending across page types; it should not feel like a new unrelated campaign.

### Editorial statement pair

**Only for:** organizational storytelling

**Observed:** A peach text-only chapter uses an uppercase eyebrow, a 48px heading and supporting prose with 20px and 24px separations. A Coral statement band uses a 60px headline in a 1130px container, then a much narrower paragraph and expansive lower space.

**Transfer:** Contrast a practical mission with a bolder statement of standards; adapt the text lengths rather than reproducing the original subject.

**Text style:** `display` — Matter 500 · 60px/1.08 · tracking -0.0417em

### Expert wall

**Only for:** people sections

**Observed:** Centered eyebrow, Heading and support on Pale proof canvas introduce the Module-grid of Biography cards. The grid remains left-aligned on its final incomplete row rather than centering the last card.

**Transfer:** Use named people only when expertise materially supports the proposition; prioritize responsibility and relevant experience.

**Text style:** `heading` — Matter 500 · 48px/1.125 · tracking -0.0333em

### Closing invitation

**Only for:** company and people pages

**Observed:** A dark closing stage places a 48px two-line invitation and coral support at left with a single Primary button. Dark technical atmosphere sits at the far right. Broad top breathing room and an uninterrupted dark background connect it to the footer.

**Transfer:** End organizational storytelling with a direct invitation to work together, not a generic newsletter form.

**Text style:** `heading` — Matter 500 · 48px/1.125 · tracking -0.0333em

## Page flow

**Storyline:** promise → credibility → reason to change → differentiated mechanism → technical or human proof → fitting invitation and restrained navigation

### Product or infrastructure landing page

1. **Promise** — Centered dark opening with a concise ownership-oriented promise, paired actions and the luminous signal field.
2. **External credibility** — Captioned trust plate with pale monochrome marks.
3. **Problem framing** — Peach split chapter pairs a drafting illustration with a concise explanation of the cost of the status quo.
4. **Differentiation** — Dark numbered capability modules beneath a large heading and specific action.
5. **Technical proof** — Pale chapter explains architecture through an exploded system drawing.
6. **Navigation ending** — Sparse dark footer, with no additional standalone sales section.

**Transfer:** Use this as the default marketing rhythm, changing the placement and number of arguments as needed while retaining light sculpture, drafted proof and warm dark modules.

### Organizational credibility and people page

1. **Purpose** — Centered organizational headline over thin people linework on a dark stage.
2. **Practical commitment** — Peach editorial chapter states the team's purpose plainly.
3. **Standards** — Saturated coral field gives one belief monumental typographic scale.
4. **Human proof** — Centered introduction and sharp peach biography cards on pale lavender-white.
5. **Closing invitation** — Large direct invitation and one glowing action on a dark stage with faint outline art.
6. **Navigation ending** — Shared sparse footer with small mono link groups and subdued legal row.

**Transfer:** For company-oriented pages, let beliefs and specific expertise replace capability claims; keep the brighter statement band scoped to this narrative.

## Writing

Confident, technically literate and commercially grounded. It describes control, performance and operational responsibility in plain language, then backs those benefits with specific mechanisms or experience.

**Do not copy:** Do not reuse the Altius name, identity graphics, partner marks, team identities, biographies, performance numbers, employment credentials or proprietary claims. Source examples illustrate tone only; replace all facts with substantiated facts for the new product.

- **Addressing the reader:** The reader is addressed as you and your, especially around ownership and outcomes. We appears when accepting responsibility or describing collaboration; institutional details use direct factual statements.
- **Rhythm:** Short declarative headlines, often two compact sentences or a contrast. Supporting paragraphs explain the mechanism in two to four sentences; actions are brief and literal. Periods and contractions keep the voice decisive without shouting.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Two parallel outcome statements addressed to the reader. | 4–8 words | “Your Chain. Your Economics.” |
| Problem heading | Name the current approach and its concrete cost with an active verb. | 4–8 words | “Shared infrastructure leaks value.” |
| Capability title | Use an imperative or compressed benefit, with decisive punctuation. | 3–6 words | “Own the Economics.”<br>“Live in Weeks, Not Years.” |
| Supporting explanation | State what the system does and contrast purpose-built design with retrofitting. | 25–55 words | “Designed from the ground up for high-volume trading and settlement, with the throughput, security, and privacy financial workloads demand. Not retrofitted from a general-purpose chain.” |
| Action | Name an actual next step and clarify commitment when useful. | 3–5 words | “Request a Demo”<br>“Talk to Our Team” |
| Closing invitation | Pair the reader's ambition with a promise of collaboration. | 9–15 words | “Build the chain you own. We'll run it with you.” |

**Words and phrasing to use:** own; built for; purpose-built; from the ground up; production-ready; alongside your team; not retrofitted; by default

**Avoid:** revolutionary; magic; game-changing; limitless possibilities; effortless transformation; unsubstantiated superlatives

**Rules:**

- Lead with an economic or operational outcome before describing architecture.
- Use contrast to sharpen an argument, not to create vague hostility toward competitors.
- Explain technical terms through their consequence for the reader.
- Keep biographies factual: present responsibility, then relevant history.
- Use quantified claims only where they can be substantiated.

## Do's and Don'ts

### Do

- Keep the opening headline at 60px/1.08, weight 500 and -2.5px tracking at desktop.
- Use brown-black #190501 rather than neutral black for broad dark stages.
- Give main content chapters 100px vertical breathing room and use the 1130px centered container.
- Keep rectangular buttons compact at 38px with 1px borders and 8px 16px padding.
- Give capability panels 20px padding and gutters, with 8px registration corner accents.
- Pair pale technical artwork with rust 20px/28px explanation rather than a wall of tiny labels.
- Preserve a luminous signal field and fine drafted graphics when adapting to products without visual interfaces.
- Use the same sparse footer across product and organizational narratives.

### Don't

- Do not replace the warm palette with blue-violet neon or neutral charcoal; preserve the red-brown relationships.
- Do not round capability cards or conversion buttons into pills; only portraits are circular.
- Do not use 700-weight type for all headings; bold belongs chiefly to the 24px module titles.
- Do not make all prose monospace; it is a labeling and indexing voice, not the primary reading face.
- Do not turn backdrop blur into translucent white glass over the dark stages; the panels read as deep oxide surfaces.
- Do not spread saturated coral fills through an ordinary landing page; the full-field treatment is an organizational-story variant.
- Do not use large lifestyle photography in place of the small 64px people portraits and diagrammatic linework.
- Do not inflate the closing footer into giant centered link tiles; retain slim right-aligned columns.

## Motion and responsive

### Motion

**Observed:**

- Actions declare all 0.2s ease transitions. Buttons change border or text color; social squares gain an inset red glow.
- Horizontal and vertical loop keyframes and rotation-related keyframes are declared, but their visible application and duration are not established.

**Transfer:**

- Carry the short 0.2s ease color and edge transitions into the rectangular controls; keep the light field recognizable even as a static composition.

**Unknown:**

- Light-field playback timing, scroll-trigger choreography and loop speeds are unknown.
- No positive focus treatment is established beyond declared outline removal; provide a visible accessible keyboard treatment in implementation.

### Responsive

**Observed:**

- Stylesheets declare width breakpoints at 479px, 640px, 767px, 768px, 991px and 992px.

**Transfer:**

- On narrow screens, retain the centered promise over the edge-clipped signal field; keep the signal graphic wide rather than shrinking every bar into a thumbnail.
- Adapt split chapters and three-column modules into a readable single column while preserving 20px internal gaps and sharp borders. Keep diagram annotations legible by simplifying the drawing rather than scaling tiny text indefinitely.

**Unknown:**

- Mobile typography, exact gutter changes, menu construction and breakpoint-specific layout behavior are not established. Responsive transfer rules are recommendations, not measured variants.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
