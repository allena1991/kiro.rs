# Auxia — cobalt connected systems

## Overview

An expansive enterprise style that makes complex software feel like a connected, working system. Warm cream and charcoal alternate with electric blue chapters, tightly set grotesk headlines and small technical monospace labels. Floating interface illustrations, routed lines and dot fields give the otherwise spare layouts a sense of operation and momentum.

### Essentials

- Headlines feel compressed vertically rather than heavy: PP Neue Montreal at 104px/0.95, weight 500 and -0.03em tracking for the main promise; 64px and 48px retain the same proportions.
- The opening leaves room for the system to breathe: a cream canvas, a fine routed line above a low-left two-line headline, a 648px text column and 40px gaps between headline, support and actions.
- Actions are compact rounded rectangles, not capsules: 12px radius, 16px/1.3 medium text, 14px 24px padding for section actions and 8px 20px for the navigation conversion.
- Color works in chapters: cream carries the explanatory majority, charcoal carries tension and trust, and saturated #0b4fff fills selected system panels and the entire closing territory rather than tinting every card.
- Software is staged as a physical object: 608px-wide interface plates, 24px corners, deep diffuse downward shadows and cream or charcoal backing; use a small custom diagram when full interface artwork is unavailable.
- A routed thread and dot field make the page one system: thin blue paths turn through rounded elbows between alternating modules; regular low-contrast dots back key blue and dark scenes.
- The ending is monumental, not merely utilitarian: a blue closing field leads into an oversized cream wordmark spanning the 1232px container, followed by small mono labels and three sparse link columns. Use the new product's own wordmark or a typeset name at the same visual scale.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| System cobalt | `#0b4fff` | `--color-blue` | background, accent, action, text | Primary chromatic identity: conversion actions, routed paths, proof numerals, major panels and the closing field. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Proof black | `#161616` | `--color-proof-dark` | background | Near-black field behind the monumental numerical proof. |
| Charcoal ink | `#232323` | `--color-ink` | text, background, surface | Default text and dark narrative bands; also the secondary action fill. |
| Warm rule | `#e2e1d3` | `--color-rule` | border | Light card edges and subtle routed or separating rules. |
| Warm canvas | `#f0efe3` | `--color-canvas` | background, text | Default light page canvas and warm reverse text on dark or blue. |
| Ivory plate | `#fefdf5` | `--color-card` | surface, background | Raised explanatory panels and light application-card sections. |
| Action white | `#ffffff` | `--color-white` | surface, text | White conversion action on blue; small bright details. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product illustrations and institutional openings | Interface black | `#191919` | `--color-deep-dark` | surface, background | Deep interface scenes and the institutional opening variant. |
| company and recruiting pages | Warm stone | `#e6e5d8` | `--color-team-band` | background | Recruiting band distinguished from the main cream. |

## Typography

- **PP Neue Montreal** — All headlines, prose, navigation and conversion actions. Compact neo-grotesk with open counters and a firm medium weight; large text is closely packed without becoming bold. If unavailable, use **Inter**. Use weight 500 and retain tight display tracking; tune line breaks to the compact original. Font stack: "PP Neue Montreal", "Inter", Arial, sans-serif.
- **IBM Plex Mono** — Section markers, capability labels, diagram annotations and footer categories. Technical monospaced lettering, medium weight, usually uppercase. Font stack: "IBM Plex Mono", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| proof-number | PP Neue Montreal | 500 | 120px | 0.95 | -0.03em | A single monumental quantified result, centered on a dark field. |
| display | PP Neue Montreal | 500 | 104px | 0.95 | -0.03em | Main promise and oversized transformational statements. |
| heading-lg | PP Neue Montreal | 500 | 64px | 0.95 | -0.03em | Major section introductions and closing call. |
| heading | PP Neue Montreal | 500 | 48px | 0.95 | -0.03em | Capability chapter headings, trust pillars and cross-product titles. |
| layer-title | PP Neue Montreal | 500 | 24px | 1.2 | normal | Layer names inside a platform explanation. |
| body-lead | PP Neue Montreal | 500 | 20px | 1.3 | normal | Opening support, substantial paragraphs and footer destination links. |
| body | PP Neue Montreal | 500 | 16px | 1.3 | normal | Body descriptions, navigation and actions. |
| eyebrow | IBM Plex Mono | 500 | 14px | 1.3 | 0.014em, uppercase | Technical section markers and capability column labels. |
| footer-label | IBM Plex Mono | 500 | 12px | 1.4 | normal, uppercase | Small footer category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product application grids | card-title | PP Neue Montreal | 500 | 24px | 1.1 | normal | Short application-card headings. |
| product capability chapters | feature-point | PP Neue Montreal | 500 | 20px | 1.2 | normal | Named capability points above smaller explanatory copy. |

**Notes:**

- The display system keeps weight 500 throughout; scale, -0.03em tracking and 0.95 line height create the hierarchy rather than boldness.
- Mono labels are much smaller than headings and can be cobalt on cream or cream on blue. Reserve sentence case for the grotesk.
- Within a statement, an introductory clause can be muted to 50% opacity while the conclusion remains fully bright; do not turn entire headings into gradients.
- The giant footer name is vector artwork fitted to the container, not another body-font size.

## Layout

**Density:** Airy at the page level, compact within demonstrations: long narrative breaths surround tightly grouped controls and diagram details.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small action icon gaps and compact navigation spacing. |
| 12px | Eyebrow-to-capability-heading gap. |
| 16px | Action groups, card grids and footer columns. |
| 24px | Paragraph groups and application-card padding. |
| 32px | Closing headline-to-action gap. |
| 40px | Global side padding, major-panel horizontal inset and opening text-stack gap. |
| 48px | Explanatory panel vertical padding and internal composition separation. |
| 64px | Grid section heading-to-card separation and footer bottom padding. |
| 112px | Company-band vertical padding. |
| 128px | Major section padding and footer wordmark-to-links separation. |
| 180px | Dark narrative and closing-call vertical padding. |

### Containers and grids

- **Main container**: max width 1232px · side padding 40px. Centered explanatory content; at 1440px the content edges sit 104px inward. Full-bleed colored bands surround this inset content.
- **Navigation container**: max width 1440px · side padding 40px. A wider shell than the main content: brand left and compact menu plus conversion right.
- **Opening text**: max width 648px. Low-left promise column with two-line headline and narrower support.
- **Capability grid**: max width 1232px · 12 columns · gap 16px. Alternating text and media chapters. Media spans about half the grid at 608px; the text column is about 504px, with an open gutter between.
- **Platform explanation**: 2 columns · gap 80px. A larger left diagram and narrower right layer list, proportioned 1.35fr to 1fr.
- **Application grid** (only for product application sections): 3 columns · gap 16px. Three equal cards per row; a four-column variant fits shorter application descriptions.
- **Assurance tiles** (only for product assurance sections): 4 columns · gap 4px. A nearly continuous row of four raised blue tiles under a centered heading.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Actions | 12px |
|  | Panels and media plates | 24px |
|  | Navigation links | 8px |
| product diagrams | Diagram tags | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| Floating plate | `rgba(0, 0, 0, 0) 0px 634px 177px 0px, rgba(0, 0, 0, 0.01) 0px 406px 162px 0px, rgba(0, 0, 0, 0.05) 0px 228px 137px 0px, rgba(0, 0, 0, 0.09) 0px 101px 101px 0px, rgba(0, 0, 0, 0.1) 0px 25px 56px 0px` | Interface plates and blue assurance tiles; the long soft shadow makes them hover above the warm canvas. |

### Surfaces

#### Warm canvas · level 0

**Use:** Default light page field.

**CSS:** `background: #f0efe3; color: #232323`

#### Dark chapter · level 0

**Use:** Problem framing and enterprise reassurance.

**CSS:** `background: #232323; color: #f0efe3`

**Observed:** Full-width rectangular bands, not rounded giant containers.

**Transfer:** Use dark chapters to change narrative emphasis without changing type families.

#### Cobalt field · level 0

**Use:** Selected system stories and the closing territory.

**CSS:** `background: #0b4fff; color: #f0efe3`

**Observed:** Saturated flat blue supports cream text; it is not a pastel wash.

**Transfer:** Keep the field flat and let dots or routed lines supply detail.

#### Ivory explanation panel · level 1

**Use:** Contained overview of a system and its layers.

**CSS:** `background: #fefdf5; border: 2px solid #e2e1d3; border-radius: 24px; padding: 48px 40px`

**Observed:** A large panel aligned to the main container, with the heading pair above the diagram and layer list.

**Transfer:** Explain an unfamiliar product architecture in one composed scene.

#### Proof field · level 0

**Use:** Monumental numerical evidence.

**CSS:** `background: #161616; color: #f0efe3`

**Observed:** Dim horizontal event rows remain behind a central cobalt number.

**Transfer:** Keep the underlying data texture subordinate to one true result.

#### Dotted cobalt · level 1

**Only for:** product stages and assurance tiles

**Use:** Technical texture on saturated scenes.

**CSS:** `background-color: #0b4fff; background-image: radial-gradient(circle, rgba(255, 255, 255, 0.2) 2px, rgba(0, 0, 0, 0) 2px)`

**Observed:** Regular dots sit beneath content and fade toward scene edges.

**Transfer:** Use the dot-field imagery recipe for repeat size and fading.

#### Recruiting stone · level 0

**Only for:** company and recruiting pages

**Use:** Warm contrast band for an invitation to join.

**CSS:** `background: #e6e5d8; color: #232323`

## Components

### Navigation

**Use:** Shared masthead below a narrow announcement strip.

**CSS:** `display: flex; align-items: center; background: #f0efe3; padding: 0px 40px; height: 72px`

**Text style:** `body` — PP Neue Montreal 500 · 16px/1.3

**Observed:** Brand at left, destination links and a product dropdown at right, then Primary button and a language link separated by a vertical rule. The company variant reverses the navigation against dark backing.

**Transfer:** Keep destinations sparse and preserve the wider shell relative to body content.

### Navigation link

**Use:** Masthead destinations.

**CSS:** `color: #232323; padding: 8px 16px; border-radius: 8px; opacity: 0.7`

**Text style:** `body` — PP Neue Montreal 500 · 16px/1.3

**Observed:** Plain text links without filled tabs; dropdown adds a small downward chevron.

**States:** Declared: hover opacity 1 and outline 0px; focus-visible unknown; active outline 0px.

### Primary button

**Use:** Conversion in navigation and light sections.

**CSS:** `background: #0b4fff; color: #f0efe3; border-radius: 12px; padding: 8px 20px; display: flex; align-items: center; gap: 8px`

**Text style:** `body` — PP Neue Montreal 500 · 16px/1.3

**Observed:** Compact navigation default; section actions are roomier. No trailing arrow on the standard demo action.

**States:** Declared: hover background-color #232323 and border-radius 8px; focus-visible unknown; active outline 0px.

### Reverse button

**Use:** Primary conversion on blue closing fields.

**CSS:** `background: #ffffff; color: #232323; border-radius: 12px; padding: 14px 24px; display: flex; align-items: center; gap: 8px`

**Text style:** `body` — PP Neue Montreal 500 · 16px/1.3

**Observed:** Sits first in an action pair. Product cross-links use a cream-filled variant with a 2px cream border.

**States:** Declared: hover background-color #232323 and border-radius 8px; focus-visible unknown; active outline 0px.

### Secondary button

**Use:** Companion explanatory action beside Reverse button.

**CSS:** `background: #232323; color: rgba(255, 255, 255, 0.7); border-radius: 12px; padding: 14px 24px`

**Text style:** `body` — PP Neue Montreal 500 · 16px/1.3

**Observed:** Dark filled action paired horizontally with the white conversion action at a 16px gap.

**States:** Declared: hover background-color #232323 and border-radius 8px; focus-visible unknown; active outline 0px.

### System overview panel

**Use:** Explain a product's constituent layers.

**CSS:** `background: #fefdf5; border: 2px solid #e2e1d3; border-radius: 24px; padding: 48px 40px; display: flex; flex-direction: column; gap: 48px`

**Text style:** `layer-title` — PP Neue Montreal 500 · 24px/1.2

**Observed:** Heading and supporting paragraph form the top row; below, an exploded stack illustration faces an eyebrow and a list of layer names with square bullets and short prose.

**Transfer:** Replace the stack with the new product's actual architecture; retain the hierarchy of overview, object and named layers.

### Footer column

**Use:** Small navigation groups beneath the giant wordmark.

**CSS:** `display: flex; flex-direction: column; gap: 16px; color: #f0efe3`

**Text style:** `body-lead` — PP Neue Montreal 500 · 20px/1.3

**Observed:** Three columns occupy the right half of the container; each begins with Footer-label text. Copyright and legal links occupy the left half. The wordmark is separated from this grid by 128px.

**Transfer:** Keep each category short so the wordmark remains the footer's main event.

### Application card

**Only for:** product application sections

**Use:** Specific jobs or contexts, grouped in a regular grid.

**CSS:** `border: 1px solid #e2e1d3; border-radius: 24px; padding: 24px; display: flex; flex-direction: column; align-items: flex-start`

**Text style:** `card-title` — PP Neue Montreal 500 · 24px/1.1

**Observed:** A 48px monochrome icon sits high in the card, with generous open space before a title and short 16px description. Cards use the surrounding ivory field rather than a colored fill.

**Transfer:** Use one concrete task per card, not a vague benefit slogan.

### Assurance tile

**Only for:** product assurance sections

**Use:** Reassure readers about controls and reliability.

**CSS:** `background: #0b4fff; color: #f0efe3; border-radius: 24px; padding: 40px 24px; display: flex; flex-direction: column; justify-content: space-between; align-items: center`

**Text style:** `layer-title` — PP Neue Montreal 500 · 24px/1.2

**Observed:** Four equal blue tiles, each with an outline symbol above a centered short label, a fine dot field and Floating plate shadow.

**Transfer:** Choose four distinct assurances supported by the new product; retain the simple symbol-plus-label composition.

## Imagery and graphics

### Routed thread

**Use:** Signature connective graphic across capability chapters and in the opening.

**Observed:** Thin orthogonal paths turn with generously rounded elbows. A warm faint route is overlaid by cobalt progress segments; the route passes between alternating media and text, with occasional tiny mono annotations or bolt nodes.

**Transfer:** Include a connected route on every new page, linking meaningful steps rather than drawing a decorative tangle. A static SVG is an adequate minimum.

**Build:** Draw SVG paths with no fill and 2px strokes. Use #e2e1d3 for the base route and #0b4fff for selected segments. Join horizontal and vertical runs using quadratic curves with about 40px bend radii; place the route behind cards and interrupt it with canvas-backed labels. In the opening, run one faint route across the upper field and place a few outlined capsule nodes on it.

### Dot field

**Use:** Signature texture behind technical scenes and the closing call.

**Observed:** Regular small dots form an ordered field, visible on blue and dark backing, sometimes denser behind a central object and fading around the edges.

**Transfer:** Keep dots low contrast so they read as a system substrate, never as confetti.

**Build:** Repeat a radial-gradient circle of 2px radius in rgba(255,255,255,0.2) on blue. Use a roughly 40px square repeat for the spacious closing scene and a tighter repeat for small illustrations. Fade with a separate radial mask or transparent overlay. On charcoal, use rgba(68,68,68,0.5) dots. Match the soft fade; exact mask stops are not essential.

### Floating interface plates

**Use:** Primary visual proof in capability chapters.

**Observed:** Cream or nearly black rectangular interfaces float above the cream page on broad gray-brown shadows. Plates are around 608px wide with 24px corners, showing simplified workflows, sliders, permissions, data cards or charts, rather than full browser chrome.

**Transfer:** Make a focused, legible diagram of one real product interaction. Keep cream, charcoal and blue dominant; reserve other colors for actual interface status or integration marks.

### Exploded system stack

**Use:** Architecture explanation inside System overview panel.

**Observed:** Three thin rounded-square plates are viewed isometrically, separated vertically: ivory base, cobalt middle and charcoal top. Small integration tiles sit on the top plate; dots and soft contact shadows make the structure tangible.

**Transfer:** Use the same material vocabulary for the new system's layers. A clean SVG isometric stack with simple neutral feature tiles is the minimum acceptable version.

**Build:** Draw three equal rounded parallelograms in an SVG, with corners softened, separated by about one fifth of a plate's width vertically. Fill bottom #f0efe3, middle #0b4fff and top #232323; add shallow lighter side faces, faint regular dots and broad blurred black shadows at low alpha beneath each plate. Label along the same isometric axis.

### Monumental footer name

**Use:** Signature large-scale ending on every page.

**Observed:** A cream lowercase wordmark fills a 1232px-wide by 417px-high vector box on blue. It is flat, sharply edged and much larger than any navigation or section text.

**Transfer:** Fit the new brand's own name as vector or live type across almost the entire content width; preserve the dramatic scale even for a longer name.

**Build:** Create an SVG with the new wordmark converted to paths, use #f0efe3 fill on #0b4fff, set width to 100% of Main container and preserve its natural aspect ratio. If no wordmark exists, typeset a compact grotesk name and fit its width to the container without distorting letters.

### Human company photography

**Only for:** company and recruiting pages

**Use:** Mission story and recruiting invitation.

**Observed:** A candid team group photograph sits in a rounded rectangle alongside blue mission copy. A wider team-photo strip anchors the warm-stone recruiting band. Photography stays naturally lit and relatively subdued.

**Transfer:** Use real workplace or team photography, not glossy stock portraits. Preserve warm indoor light, group scale and simple rounded framing.

### Icons

**Observed:** Utility marks are small filled SVGs around 16px or 24px; application cards use 48px dark symbols. Blue reassurance tiles use larger cream outline symbols. Blue squares introduce capability points; check marks distinguish included items.

**Transfer:** Choose simple functional symbols with a consistent visual weight. Keep colored integration logos confined to diagrams; do not turn every feature into a multicolor icon.

## Section recipes

How recurring sections are built.

### First screen: Low-left system opening

**Observed:** The first 900px contains a 40px blue announcement strip, 72px cream Navigation and a cream stage. Back to front: warm canvas, faint routed thread across the upper field, then a low-left 648px text stack. The 104px display headline breaks into two compact lines and takes roughly half the content width; its support sits 40px below. The top of the stage is exceptionally open while the promise anchors the lower-left. The settled first view shows the route, headline and support, not a dominant central object; the action pair sits just below the first fold, with the brand strip following lower down.

**Transfer:** Use a short transformative promise with the same two-line mass, a specific support sentence and the Routed thread as the minimum graphic. When product media is available, use focused workflow fragments rather than a stock hero image. Dedicated product openings use a top-left promise with right-hand support and action, plus a lower product scene; institutional openings use a dark field and a row of blue proof numbers.

**Avoid:** Do not move the default promise into a centered SaaS template, fill the upper field with generic gradient blobs, or force a huge browser mockup into the first screen.

**Text style:** `display` — PP Neue Montreal 500 · 104px/0.95 · tracking -0.03em

### Tension and resolution chapter

**Observed:** Dark chapter pairs a 64px left statement with a narrower 20px paragraph column at right. Below, a thin outlined dark system panel contrasts with a solid blue resolution panel; both have 24px corners and generous 40px insets.

**Transfer:** Show a concrete before-and-after mechanism with nodes or pathways, using darkness for friction and blue for the resolved system.

### Platform anatomy

**Observed:** System overview panel places a 64px headline opposite supporting prose, then an Exploded system stack opposite a mono label and named layer list. Dark and cobalt offering panels can continue beneath it at a 16px gap.

**Transfer:** Use this when a product has multiple interacting layers; put the architecture into one coherent object rather than unrelated feature tiles.

### Alternating connected chapters

**Observed:** Capability grid alternates a roughly 504px text block and 608px Floating interface plates. Text begins with a cobalt Eyebrow, a 12px gap to a 48px heading, then named points and compact descriptions. The Routed thread bends from one illustration to the next through generous open space.

**Transfer:** Explain a process or set of capabilities in focused chapters; alternate sides while keeping the connective route continuous.

**Text style:** `heading` — PP Neue Montreal 500 · 48px/0.95 · tracking -0.03em

### Monumental quantified proof

**Observed:** A 900px-tall Proof field holds many dim horizontal input-to-output rows. A cobalt 120px number dominates the center above a smaller cream explanation, with a 16px gap. Rows form atmosphere rather than a second reading column.

**Transfer:** Use one auditable scale or outcome figure. For a product without a valid numeric claim, use a short, truthful outcome statement at comparable visual prominence instead.

### Customer proof rail

**Observed:** A 64px left-aligned introduction precedes an edge-clipped horizontal rail of large proof cards. Each card combines a logo, a compact company description and a dominant metric near the lower edge. Light, dark and blue variants belong to their surrounding chapter.

**Transfer:** Use permissioned customer marks and real proof; preserve the oversized metric and clipped-rail composition rather than turning the rail into a dense testimonial grid.

### Enterprise trust pillars

**Observed:** Dark chapter uses a split heading pair above three spare columns. Each pillar has a thin cobalt left rule, a cream symbol, a 48px title and small muted explanatory copy. The chapter uses 128px vertical padding and a 128px gap between introduction and pillars.

**Transfer:** Use a few substantiated technical assurances; keep this treatment typographic rather than turning it into badge clutter.

### Cobalt closing and wordmark

**Observed:** A full-width blue dot-field closing scene is about 562px high. A left-aligned 64px two-line call spans at most 698px, with Reverse button and Secondary button 32px below. The blue continues into Monumental footer name, then Footer column groups. The institutional ending instead goes from the recruiting band directly to the giant-name footer; a technical product ending can insert a bordered cross-product link before the footer.

**Transfer:** Close with one actionable outcome and a dramatic name treatment. Preserve the giant footer even when the final conversion is a recruiting or cross-product action.

**Text style:** `heading-lg` — PP Neue Montreal 500 · 64px/0.95 · tracking -0.03em

### Assurance and applications

**Only for:** product detail pages

**Observed:** A centered 64px heading and brief support introduce Assurance tiles. A following ivory section uses a left-aligned eyebrow and 64px heading above Application cards in three or four columns, with 64px between introduction and grid.

**Transfer:** Separate confidence-building controls from concrete jobs the product performs; let each grid carry one kind of information.

### Culture route and invitation

**Only for:** company and recruiting pages

**Observed:** A dark opening with blue numbers gives way to a blue mission story and rounded team photograph. Values are spaced along a serpentine Routed thread rather than boxed into a grid. A Warm stone recruiting band pairs a 64px invitation with prose and an action, then a broad photo strip.

**Transfer:** Adapt the route to principles or milestones and use an authentic group image; this is a people-story variant, not the default product section sequence.

## Page flow

**Storyline:** Transformative promise → explain the mechanism → demonstrate connected capabilities → establish scale and trust → invite the next action → monumental brand ending.

### Broad platform landing page

1. **Promise** — Low-left statement on cream with a faint system route.
2. **Problem framing** — Dark narrative and contrasting tangled-versus-ordered diagrams.
3. **Product explanation** — Layered architecture object followed by dark and cobalt offering panels.
4. **Product demonstration** — Long connected workflow with alternating interface scenes and compact stage labels.
5. **Quantified proof** — Monumental number over dim data rows, followed by customer proof cards.
6. **Objection handling** — Dark enterprise-trust pillars.
7. **Closing call** — Blue dot field, paired actions and giant cream wordmark footer.

**Transfer:** Adapt the amount of demonstration to the complexity of the new product; retain the contrast between spare promise, tangible system and large-scale proof.

### Institutional story and recruiting page

1. **Positioning** — Dark large headline and a row of blue scale figures.
2. **Mission** — Blue story chapter with longer prose and team photography.
3. **Principles** — Individual principles placed along a routed path on cream.
4. **Recruiting invitation** — Warm-stone heading pair, action and wide team image.
5. **Brand ending** — Direct transition into the shared giant-name blue footer.

**Transfer:** Use human proof and principles rather than copying the product-demo storyline.

### Technical product explanation

1. **Promise** — Blue dotted stage with left headline, right support and action, and a lower data-to-output diagram.
2. **Social proof** — A sparse horizontal customer-logo strip.
3. **Capability chapters** — Alternating cream-backed diagrams and text connected by the routed line.
4. **Assurance** — Centered introduction and blue control tiles.
5. **Applications** — Ivory application grid.
6. **Customer proof** — Blue customer metric rail.
7. **Next product** — Dark cross-product band with outlined inset panel and cream action.
8. **Brand ending** — Blue monumental-name footer.

**Transfer:** Make the process legible through a succession of simple input, control, output and feedback scenes.

### Workflow product explanation

1. **Promise** — Dark dotted stage with left headline, right support and action, and a centered compact assistant interface above moving task labels.
2. **Social proof** — Customer-logo strip.
3. **Capability chapters** — Alternating integration, workflow, collaboration and control illustrations linked by one route.
4. **Assurance** — Four blue tiles under a centered heading.
5. **Applications** — Three-column, two-row task grid.
6. **Customer proof** — Dark customer metric rail.
7. **Next product** — Blue cross-product inset link panel.
8. **Closing call** — Blue dotted action scene and shared monumental-name footer.

**Transfer:** Use real workflow steps and control boundaries to give automation a tangible, trustworthy form.

## Writing

Confident, operational and direct. Ambitious promises are followed by concrete descriptions of what runs, what connects and what the reader controls.

**Do not copy:** Do not reuse Auxia's brand names, logos, customer marks, proprietary diagrams, customer descriptions, numerical claims, certification claims or team-origin claims. Source examples illustrate syntax and tone, not claims licensed for another product.

- **Addressing the reader:** Use you and your for the user's work and controls. Name the product when describing its mechanism; use we mainly for company principles and mission.
- **Rhythm:** Short declarative headlines, often built around a contrast or transformation, followed by one explanatory sentence. Feature descriptions are denser and specific; actions stay short. Sentence case dominates outside technical mono labels.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the reader's transformed state or the product's central role in a short declarative phrase. | 3–9 words | “The marketer, multiplied”<br>“The full campaign workflow, run by agents” |
| Capability headline | Start with a concrete verb or contrast the new way with the old way. | 5–14 words | “Your data in, model-ready features out”<br>“The intelligence compounds, not the work” |
| Supporting line | Explain the mechanism and useful outcome, including boundaries when they matter. | One sentence or a compact paragraph | “[Brand]’s agents work across your stack and create a unique journey for every customer, while continuously learning and optimizing the next interaction. Marketing stops resetting and performance compounds over time.” |
| Feature point | A compact operational claim followed by how it works. | 3–7 words for the lead | “Connect your data”<br>“Nothing ships without approval” |
| Primary action | A clear verb and a concrete next step. | 2–4 words | “Request a demo”<br>“Discover more” |
| Closing call | Turn an activity into an outcome, not a vague aspiration. | 7–10 words | “Turn every customer interaction into impact.” |

**Words and phrasing to use:** run; connect; build; learn; control; guardrails; workflow; in real time; on your stack; with you approving

**Avoid:** magic; revolutionary; limitless; effortless everything; best-in-class without proof; playful internet slang

**Rules:**

- Make each abstract promise tangible in the very next sentence.
- Use contrasts such as fragmented versus unified or static versus learning, but explain the actual difference.
- Mention control, approval or privacy where automation could raise a practical concern.
- Tie a numerical proof to a clear unit and a verifiable definition.
- Use technical nouns only when they make a mechanism clearer.

## Do's and Don'ts

### Do

- Keep major headlines at weight 500 and 0.95 line height, with -0.03em tracking.
- Use the 1232px content width inside full-bleed cream, charcoal and blue chapters.
- Keep rounded controls at 12px and large panels at 24px.
- Join capability illustrations with a 2px routed line rather than repeating isolated decorative flourishes.
- Stage focused product plates at roughly half the content width and give them broad downward shadows.
- Reserve 14px uppercase mono for technical section labels and 12px mono for footer categories.
- Carry the cobalt field through a monumental cream name and sparse footer navigation.
- Use 16px card-grid gaps, with the distinctive 4px gap reserved for blue assurance tiles.

### Don't

- Do not replace the warm #f0efe3 canvas with a sterile pure-white page.
- Do not use bold 700 display headings; the large medium-weight grotesk supplies the force.
- Do not turn the main conversion actions into 9999px pills; capsules belong to diagram tags.
- Do not apply Floating plate shadows to every text card; the outlined application cards stay comparatively flat.
- Do not color ordinary paragraphs cobalt; blue text is concentrated in markers and numerical proof.
- Do not put every section inside a rounded container; narrative color bands extend edge to edge.
- Do not use colorful stock 3D blobs in place of diagrams of actual operations.
- Do not shrink the final name into a conventional small footer logo.

## Motion and responsive

### Motion

**Observed:**

- Actions declare 0.2s transitions; some background-color transitions are 0.3s.
- The workflow-product task marquee declares a 50s linear infinite animation and a circular orbit declares 20s linear infinite.
- Headlines use word-level reveal wrappers; routed paths show selected bright segments against muted base paths.

**Transfer:**

- Keep movement tied to routed progression and working-system scenes; the task-label marquee belongs to the workflow-product opening.
- Provide a static connected-path composition when motion is reduced.

**Unknown:**

- Exact scroll-trigger timing, reveal easing and all intermediate animation states are unspecified.

### Responsive

**Observed:**

- Styles include width breakpoints at 479px, 767px, 768px, 991px and 992px; some variants also use 478px.

**Transfer:**

- On narrow layouts, stack the promise, support and scene while keeping headline prominence and the connected-route motif.
- Convert alternating chapters to a single reading column and redraw the route vertically; fit the giant footer name to the available width rather than retaining a fixed desktop size.

**Unknown:**

- Mobile font sizes, navigation behavior, spacing values and exact chapter rearrangements are unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
