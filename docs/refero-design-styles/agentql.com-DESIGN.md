# AgentQL — luminous developer theatre

## Overview

A near-black technical style with silvery sans-serif headings and small pools of blue, cyan and violet light. Product interfaces float like physical objects, backed by glossy icon sculptures and fine dot textures rather than photography. It suits developer tools and sophisticated software: spacious between chapters, compact and practical within each demonstration.

### Essentials

- Silver lettering instead of flat white display type: Figtree 64px/1, weight 500, -0.02em tracking, with a white-to-#999999 vertical text gradient; ordinary section headings step down to 48px/1.
- An asymmetric theatre of explanation and output: a 435px text column faces layered interface panels, with a 376px-wide foreground stack and a smaller browser behind it inside a 1152px container.
- Conversion controls look like softly lit hardware keys: primary actions are 48px high, 8px radius, 26px horizontal padding and a 95%-to-85% white gradient; secondary controls retain a dark translucent face.
- Color behaves as emitted light, not page paint: near-black remains the majority of the canvas, while blue and cyan halos, violet edges and occasional coral corners stay around media and panels.
- Capabilities are illustrated objects rather than plain icon lists: 470×418px cards with 12px corners give most of their area to glossy badges and diagrams, leaving a 24px-padded text shelf below. Recreate simple beveled symbol tiles when custom artwork is unavailable.
- Fine dot fields and a luminous horizon bind the page together: masked dots appear at card edges and a blue-violet pool rises behind the closing actions, above a full-width dark footer. Preserve both devices with CSS gradients when no artwork is available.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm label | `#c09f94` | `--color-warm-label` | text | Warm eyebrow, using rgba(238,196,182,0.8) over the canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Button ink | `#191a1f` | `--color-button-ink` | text | Dark lettering on light actions; lower gradient stop uses 80% alpha. |
| Near-black canvas | `#0a0b0c` | `--color-canvas` | background | Main page background. |
| Footer black | `#0b0c0e` | `--color-footer` | background | Footer base behind subdued atmospheric gradients. |
| Blue-black band | `#0e111b` | `--color-band` | surface | Wide illustrated callout. |
| Feature panel | `#101219` | `--color-feature` | surface | Capability card base. |
| Plan panel | `#121317` | `--color-plan` | surface | Pricing card base beneath localized lighting. |
| Control edge | `#3e3e3e` | `--color-control-edge` | border | Thin outline around secondary actions. |
| Muted underline | `#5b5d64` | `--color-link-edge` | border | Visible underline from rgba(171,174,187,0.5) over the canvas. |
| Inactive gray | `#777a88` | `--color-inactive` | text, border | Inactive capability controls. |
| Social gray | `#9194a1` | `--color-icon` | accent | Footer social symbols. |
| Display shade | `#999999` | `--color-silver` | text | Lower stop of silver heading gradients. |
| Muted body | `#abaebb` | `--color-muted` | text, link | Card paragraphs and inline links. |
| Pale supporting text | `#c7c9d1` | `--color-support` | text | Lead paragraphs and testimonial copy. |
| Control foreground | `#eeeff1` | `--color-foreground` | text, link | Navigation and dark-button labels. |
| Display highlight | `#ffffff` | `--color-white` | text, accent | Heading gradient tops, selected labels and icon highlights. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| product demonstrations | Demonstration edge | `#172540` | `--color-demo-edge` | border | Hairline around floating product panels. |
| product demonstrations | Demonstration navy | `#0d172b` | `--color-demo` | surface | Floating product panels. |

## Typography

- **Figtree** — Display and section headings. Rounded, open geometric sans with compact negative tracking. Font stack: "Figtree", ui-sans-serif, system-ui, sans-serif.
- **Inter** — Body, controls, card headings and prices. Practical neutral sans with a restrained technical tone. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.
- **IBM Plex Mono** (only for product demonstrations) — Code and compact format labels. Small, clearly differentiated monospaced glyphs. Font stack: "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Figtree | 500 | 64px | 1 | -0.02em | Hero promise and major comparison heading. |
| band-heading | Figtree | 600 | 64px | 1 | -0.02em | Headline inside the wide illustrated band. |
| heading | Figtree | 500 | 48px | 1 | -0.02em | Centered section introductions. |
| closing-heading | Figtree | 600 | 48px | 1 | -0.02em | Short centered closing invitation. |
| proof-heading | Figtree | 500 | 44px | 1.125 | -0.02em | Broad, balanced social-proof statement. |
| explanation-heading | Figtree | 500 | 36px | 1.125 | -0.02em | Longer left-aligned capability statement. |
| card-heading | Inter | 500 | 20px | 1.125 | -0.02em | Capability and plan names. |
| lead | Inter | 300 | 18px | 1.375 | -0.02em | Hero and section supporting text. |
| body | Inter | 400 | 16px | 1.5 | normal | Capability descriptions and inline resource links. |
| action | Inter | 600 | 16px | 1.5 | -0.02em | Main action labels. |
| footer-heading | Inter | 500 | 15px | 1 | -0.02em | Footer column titles. |
| navigation | Inter | 400 | 14px | 1.5 | -0.02em | Header links. |
| eyebrow | Inter | 500 | 14px | 1 | 0.02em, uppercase | Warm label above the illustrated band. |
| small-body | Inter | 300 | 14px | 1.375 | -0.02em | Testimonials and dense comparison details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing sections | price | Inter | 500 | 40px | 1.125 | -0.04em | Pricing figures and the custom-tier equivalent. |

**Notes:**

- Display headings are medium rather than heavy. Their white-to-gray gradient darkens the lower lines without changing font weight.
- Keep -0.02em tracking across most marketing type; body card paragraphs remain normally tracked. Pricing figures tighten to -0.04em.
- Use the 64px hero recipe in a short two-line block. Reserve the 36px recipe for a longer multi-line explanation, not for all section titles.

## Layout

**Density:** Airy between chapters and compact within product scenes; broad black pauses separate tightly layered media.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card heading-to-paragraph separation. |
| 12px | Eyebrow-to-headline separation. |
| 18px | Gap between paired main actions. |
| 20px | Bento grid gutters. |
| 24px | Card interior padding and capability-control separation. |
| 28px | Plan and testimonial gutters; header link spacing. |
| 32px | Container side padding and hero action top margin. |
| 36px | Closing action top margin and four-column benefit gutters. |
| 40px | Heading-to-bento separation and footer vertical padding. |
| 64px | Illustrated band side padding and demonstration column gap. |
| 160px | Typical major chapter separation. |
| 192px | Black breathing room around the illustrated band. |
| 230px | Closing section space beneath actions for the luminous horizon. |

### Containers and grids

- **main**: max width 1152px · side padding 32px. Centered hero and broad marketing container; hero text occupies 435px and the demonstration is right weighted.
- **bento**: max width 1024px · 2 columns · gap 20px · side padding 32px. 960px content grid with half-width cards and a full-width explanatory card.
- **comparison**: max width 1088px · 3 columns · gap 28px. Equal-width 344px plan cards and similarly sized testimonial cards.
- **wide-demonstration**: max width 1312px · gap 64px · side padding 32px. 448px left text and controls opposite a larger overlapping product illustration.
- **chrome**: max width 1408px · side padding 32px. Navigation and footer reach wider than the main storytelling columns.
- **heading-measure**: max width 780px. Balanced centered two-line section titles.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | panels | 12px |
|  | main-buttons | 8px |
|  | tabs-and-badges | 9999px (pill) |
|  | testimonials | 8px |
| comparison sections and header actions | compact-actions | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating-demo | `0px 20px 35px 0px rgba(0,0,0,0.34), 0px 4px 13px 0px rgba(0,0,0,0.25)` | Layered product panels. |
| card-depth | `0px 4px 30px 0px rgba(0,0,0,0.5)` | Pricing cards and the illustrated band. |
| button-depth | `0px 3px 16px 0px rgba(0,0,0,0.2)` | Main paired actions. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #0a0b0c; color: #ffffff`

#### Feature shell · level 1

**Use:** Capability bento cards.

**CSS:** `background: #101219; border-radius: 12px; overflow: hidden; position: relative`

**Observed:** A faint directional colored rim and artwork sit above the base; edges are lit selectively rather than uniformly.

**Transfer:** Use a masked 1px gradient border overlay; keep the lower text shelf dark.

#### Illustrated band · level 1

**Use:** Wide callout with text left and artwork right.

**CSS:** `background: #0e111b; border-radius: 12px; padding: 104px 64px 118px; box-shadow: 0px 4px 30px 0px rgba(0,0,0,0.5); overflow: hidden`

**Observed:** A coral corner bloom and violet-to-blue tile field are vignetted into the dark base.

**Transfer:** Keep colored light localized at the outside corners and behind the illustrated object.

#### Silver lettering

**Use:** Large marketing headings.

**CSS:** `background-image: linear-gradient(#ffffff 40%, #999999); background-clip: text; color: rgba(0,0,0,0); padding-bottom: 4px`

**Observed:** Hero and pricing title keep white through 70%; broad section headings begin fading at 40%.

**Transfer:** Apply to type only, never as a light rectangular background.

#### Footer atmosphere · level 0

**Use:** Full-width ending below the final call.

**CSS:** `background-color: #0b0c0e; background-image: linear-gradient(to right, rgba(35,38,52,0.5) -70%, rgba(35,38,52,0)); padding: 40px 0`

**Observed:** A thin multitone top rule separates it from the blue horizon. Large muted navy ellipses remain behind the columns.

**Transfer:** Keep footer lighting softer than the closing horizon.

## Components

### Sticky navigation

**Use:** Persistent brand and resource access.

**CSS:** `position: sticky; top: 0px; z-index: 50; height: 57px; background-color: rgba(6,7,9,0.525); border-bottom: 1px solid rgba(28,29,34,0.545)`

**Text style:** `navigation` — Inter 400 · 14px/1.5 · tracking -0.02em

**Observed:** Logo left, six compact resource links across the middle, community links and a compact pale action on the right; the inner width is broader than body content.

**States:** Declared: hover navigation links change to #abaebb.

### Primary button

**Use:** Main conversion or practical next step.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 26px; border-radius: 8px; background: linear-gradient(rgba(255,255,255,0.95), rgba(255,255,255,0.85)); color: #191a1f; box-shadow: 0px 3px 16px 0px rgba(0,0,0,0.2)`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.02em

**Observed:** Dark lettering is subtly graded. Comparison variants are 40px high with 16px side padding; the header variant is 30px high. Main paired actions have an 18px gap.

### Secondary button

**Use:** Documentation or alternate exploration beside a primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 26px; border-radius: 8px; background: linear-gradient(rgba(255,255,255,0.01), rgba(255,255,255,0.04)); border: 1px solid #3e3e3e; color: #eeeff1; box-shadow: 0px 3px 16px 0px rgba(0,0,0,0.2)`

**Text style:** `action` — Inter 600 · 16px/1.5 · tracking -0.02em

**Observed:** A dark face with a quiet illuminated outline, never a competing bright fill.

### Capability card

**Use:** Illustrated capability with a small practical explanation.

**CSS:** `display: flex; align-items: flex-end; height: 418px; background: #101219; border-radius: 12px; overflow: hidden; position: relative`

**Text style:** `card-heading` — Inter 500 · 20px/1.125 · tracking -0.02em

**Observed:** Artwork fills the upper area. Text sits above the art in a 24px-padded shelf with body copy 8px below its heading. A wide variant spans both columns and places explanatory text above a comparison scene.

**Transfer:** Give each card one distinct product affordance, not an identical generic icon.

### Inline resource link

**Use:** Links embedded in capability prose.

**CSS:** `color: #abaebb; border-bottom: 1px solid rgba(171,174,187,0.5); padding-bottom: 1px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** The underline is a fine bottom border, integrated into the paragraph rather than a separate action row.

**States:** Declared: hover border-color #ffffff and color #ffffff.

### Testimonial card

**Use:** Compact peer proof.

**CSS:** `display: flex; flex-direction: column; border-radius: 8px; padding: 24px; overflow: hidden; background-image: radial-gradient(79.43% 95.88% at 38.94% -53.46%, rgba(98,95,255,0.38) 0px, rgba(0,0,0,0)), radial-gradient(27.99% 22.08% at 72.13% 103.46%, rgba(255,125,218,0.33) 0px, rgba(0,0,0,0))`

**Text style:** `small-body` — Inter 300 · 14px/1.375 · tracking -0.02em

**Observed:** Three cards across, approximately 342×245px. Quote above, portrait and author attribution pinned below; localized cyan or violet light and a fine gradient edge. Circular 32px previous/next controls flank the carousel.

**Transfer:** Keep quotes technical and specific, with restrained attribution.

### Footer columns

**Use:** Resource navigation at the page ending.

**CSS:** `display: flex; justify-content: space-between; column-gap: 96px`

**Text style:** `footer-heading` — Inter 500 · 15px/1 · tracking -0.02em

**Observed:** Brand occupies the left; four compact link columns occupy the right. Muted resource links sit beneath white titles. A lower row places copyright left and 20px monochrome social icons right, separated by 20px gaps.

**Transfer:** Use the new product's actual information architecture; keep the airy lower row.

### Plan card

**Only for:** pricing sections

**Use:** Comparable tiers with a strong value and practical limits.

**CSS:** `background-color: #121317; border-radius: 12px; padding: 24px; box-shadow: 0px 4px 30px 0px rgba(0,0,0,0.5)`

**Text style:** `card-heading` — Inter 500 · 20px/1.125 · tracking -0.02em

**Observed:** Plan name, price, short audience description, full-width pale action, then fine check-marked feature rows. Neutral, teal and purple lighting distinguish tiers; the middle tier has a small glassy popularity badge, not an oversized card.

### Floating product panel

**Only for:** product demonstrations

**Use:** Foreground input/output panels in product scenes.

**CSS:** `background: #0d172b; border: 1px solid #172540; border-radius: 12px; overflow: hidden; box-shadow: 0px 20px 35px 0px rgba(0,0,0,0.34), 0px 4px 13px 0px rgba(0,0,0,0.25)`

**Observed:** A narrow title strip, compact monospaced content and small copy control make each layer believable; do not enlarge internal code into marketing typography.

**Transfer:** Show a legible representative transformation rather than recreating an entire application.

## Imagery and graphics

### Layered product theatre

**Use:** Hero and large explanatory demonstration.

**Observed:** A dark browser mockup sits behind two navy input/output panels. Fine connector lines, tiny glints, blue selections and a cyan-blue halo suggest a transformation. Media is taller and more visually intricate than the short left text column.

**Transfer:** Stage a real input and result from the new product. A minimum version is one simplified browser or document silhouette behind two genuine UI cards, with a single connecting path.

**Build:** Use a relative stage with a rear rounded browser and two 12px-radius navy foreground panels. Put 1px translucent dotted SVG connectors behind them, add small white/cyan endpoint circles, and layer 300–600px blurred blue ellipses behind the entire scene. Use blur(40px) and blur(64px), feathering to transparent before the text column.

### Glossy symbol sculptures

**Use:** Capability cards and the wide illustrated callout.

**Observed:** Raised rounded-square app badges and circular disks carry white symbols. Indigo, cyan, purple and occasional orange highlights roll across bevels; soft shadows, translucent concentric disks and faint background code provide depth. The callout repeats these tiles into a darkening grid.

**Transfer:** Translate the new product's capabilities into simple white geometric glyphs on luminous tiles. The minimum version is layered SVG rounded squares with a thin lit rim and an inset gradient highlight.

**Build:** Construct rounded-square SVG tiles with a dark indigo base, a violet lower-left radial bloom, a cyan or coral corner bloom, and a 1px pale translucent stroke. Offset a dark blurred duplicate behind each tile. Center one white symbol; add two larger translucent circles behind circular versions. Mask repeated background tiles with a black-to-transparent edge fade.

### Dot-field lighting

**Use:** Card corners, plan tops and the closing horizon.

**Observed:** Minute evenly spaced dots catch the colored light, then disappear into black. They add a technical material rather than a conspicuous grid.

**Transfer:** Retain this texture around the new product's main illustration and closing scene, with low contrast so body text stays crisp.

**Build:** Overlay a radial-gradient circle pattern of rgba(255,255,255,0.16) dots at 1px radius on a 4px square repeat. Mask with a broad radial gradient near a lit edge. Put blue/cyan/violet radial blooms beneath it and a dark vignette above; do not place the pattern over text.

### Luminous closing horizon

**Use:** The final invitation above the footer.

**Observed:** A wide blue-violet glow rises from the bottom of a black field below centered text and paired actions. Fine dots gather near the horizon; there is no standalone boxed illustration.

**Transfer:** Keep a luminous horizon as a signature ending even if the product has no visual interface.

**Build:** Place a wide elliptical radial gradient centered at the bottom, rgba(43,51,115,0.65) fading to transparent, with a smaller low-alpha cyan ellipse offset sideways. Blur by 40–64px. Add the masked dot field in the lower half and clip at the footer's 1px top edge. Leave 230px beneath the actions.

### Icons

**Observed:** Small monochrome utility symbols: 16px in actions, 24px beside comparison features, 32px for benefit markers and 20px social marks. White and muted gray dominate; glossy colorful badge illustrations are a separate larger art category.

**Transfer:** Choose simple solid or fine 1px-outline utility symbols; keep them subordinate to labels. Reserve dimensional colorful icons for illustrated scenes.

## Section recipes

How recurring sections are built.

### First screen: Product theatre opening

**Observed:** A 57px sticky navigation tops a near-black first screen. The hero has 60px top padding and a centered 1152px container with 32px side padding. A 435px left copy column sits near the vertical middle: two small award marks, a short two-line 64px silver-gradient headline, a light 18px support sentence and paired Primary button and Secondary button with 18px gap and 32px top separation. The right half is occupied by Layered product theatre: two 376px-wide navy panels form a 560px-tall foreground stack over a smaller browser, with small category pills above and a blue examples pill near the base. Black canvas, diffused cyan-blue light, connectors, rear browser, front panels and controls form the back-to-front order. Within 900px the complete promise, support, actions and main scene are visible; the illustrated callout begins below the fold.

**Transfer:** Use a short outcome promise opposite a concrete before/after transformation. Without custom media, build the simplified layered-panel scene rather than replacing it with a generic stock photo. Other landing-page purposes can substitute their own proof marks and result object while retaining this split composition.

**Avoid:** Do not center everything above a flat full-width application screenshot; it loses the asymmetric depth and compact promise.

**Text style:** `display` — Figtree 500 · 64px/1 · tracking -0.02em

### Illustrated callout

**Observed:** Illustrated band spans 1152×460px, separated from adjacent chapters by 192px. A warm uppercase eyebrow leads a 64px semibold silver headline, support and Primary button. A glossy symbol-tile grid occupies the right, vignetted into the text background.

**Transfer:** Use for compatibility, ecosystem or another broad enabling promise. Give the right-side tile field a real relationship to that promise.

**Text style:** `band-heading` — Figtree 600 · 64px/1 · tracking -0.02em

### Centered introduction and bento

**Observed:** A centered 780px headline and supporting paragraph lead the 960px bento grid by 40px. Capability cards use 20px gutters, two half-width cards and a spanning demonstration card. Art dominates upper portions while headings and explanatory links sit on dark lower shelves.

**Transfer:** Adapt card count and spans to the story, preserving the shift between compact illustrated features and a wider concrete explanation.

**Text style:** `heading` — Figtree 500 · 48px/1 · tracking -0.02em

### Benefit strip

**Observed:** A centered 48px headline introduces four compact unboxed benefit columns, 36px apart. Each has a 32px icon, a short white title and a muted paragraph with 8px title-to-body separation.

**Transfer:** Use for concise assurances after detailed product explanation; contrast unboxed text with the richer bento panels.

### Selectable explanation

**Observed:** The wide-demonstration layout pairs a 448px text column with an 800×604px layered product scene. A 36px heading sits above four vertically separated statements. Each statement is marked by a 2px left rule and 16px inset; selected copy and rule are white, inactive ones #777a88.

**Transfer:** Explain several transformations or use cases while showing a single coherent product scene. Keep selected state unmistakable without filled tab boxes.

**Text style:** `explanation-heading` — Figtree 500 · 36px/1.125 · tracking -0.02em

### Comparison and proof

**Observed:** A centered 64px plan heading leads to an 832×268px trial panel with invitation left and feature list right. Below a smaller centered subheading, three Plan cards form a 1088px row with 28px gaps. A later proof chapter uses a broad 44px title and three Testimonial cards with the same gutter rhythm.

**Transfer:** Separate low-friction entry from tier comparison. Match proof-card density to concise, attributable statements rather than inflated statistics.

**Text style:** `display` — Figtree 500 · 64px/1 · tracking -0.02em

### Horizon close and resource footer

**Observed:** A centered 48px semibold closing title, a light support sentence and paired actions sit above Luminous closing horizon. Actions are 36px below the copy and the light occupies the 230px space beneath. Footer atmosphere begins at a fine full-width rule; the 351px-tall footer uses 40px vertical padding, brand left, four Footer columns right, then the low copyright/social row.

**Transfer:** End with a practical invitation to explore or build, followed by real resource paths. Preserve the glowing horizon and sober footer contrast, not a giant sales banner.

**Text style:** `closing-heading` — Figtree 600 · 48px/1 · tracking -0.02em

## Page flow

**Storyline:** Outcome promise → tangible product transformation → enabling ecosystem → capability depth → practical assurances → guided explanation → commercial entry → peer proof → practical closing invitation and resources.

### Developer-product marketing landing page

1. **Promise** — Short outcome headline opposite layered input/output panels.
2. **Compatibility proof** — Wide illuminated tile field with a concise enabling claim.
3. **Capability chapters** — Centered introduction, illustrated bento and unboxed assurance strip.
4. **Product explanation** — Left-rule capability controls beside another transformation scene.
5. **Commercial entry** — Trial callout followed by three comparably sized plan cards.
6. **Social proof** — Compact atmospheric quote cards with attributed practitioners.
7. **Closing call** — Resource-oriented action pair over a dotted blue horizon, then a wide multi-column footer.

**Transfer:** Reorder or combine narrative beats to fit the product; keep tangible demonstrations, luminous technical materials and a practical resource-oriented ending.

## Writing

Direct, technically literate and approachable. Confident benefits are immediately grounded in tools, behaviors or constraints, with occasional conversational phrases instead of enterprise grandiosity.

**Do not copy:** Do not reuse AgentQL or TinyFish identity, logos, partner artwork, awards, pricing figures, customer counts, product claims or customer quotations. Replace them with substantiated details for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; name the product when explaining what it does. Action labels use direct imperatives.
- **Rhythm:** Short conversational headlines alternate with one-sentence explanations. Feature titles are usually two or three words; longer explanatory statements can span several lines. Use em dashes for clarifications and exact technical nouns where they help.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A short imperative promising a changed state. | 4–7 words | “Make the web AI-ready” |
| Supporting line | Name the product, its action and the scope of its usefulness. | 10–20 words | “[Brand] connects LLMs and AI agents to the entire web” |
| Section headline | Conversational benefit rather than a category label. | 3–12 words | “Plays well with others” |
| Capability description | Explain a concrete behavior and remove a practical concern. | One sentence | “Public or private, any site, any URL, even behind authentication.” |
| Primary action | A useful next step, sometimes naming the destination. | 2–6 words | “Get started”<br>“See samples on GitHub” |
| Closing support | Give the reader agency rather than applying pressure. | One or two brief sentences | “Holds no opinions on what’s and how’s. Build whatever makes sense to you.” |

**Words and phrasing to use:** build; connect; workflow; tools; describe; structured; works; reusable; get started

**Avoid:** revolutionary; unprecedented; synergy; unlock limitless potential; game-changing platform

**Rules:**

- Lead with the job the reader can accomplish, then explain the mechanism.
- Name technical formats and interfaces only when they clarify the benefit.
- Use concrete limitations and inclusions in comparisons, not vague tier adjectives.
- Favor practical exploration links over urgent sales language.

## Do's and Don'ts

### Do

- Keep the default canvas #0a0b0c and supporting paragraphs #c7c9d1 or #abaebb.
- Use Figtree 64px/1 at weight 500 for the opening promise, with -0.02em tracking.
- Keep ordinary capability descriptions Inter 16px/24px with normal tracking.
- Stage navy panels at different depths using 12px corners and long soft black shadows.
- Keep primary and secondary main actions equally 48px tall with 8px corners.
- Use 20px bento gutters and 28px comparison gutters rather than one universal gap.
- Carry the masked dot texture into both illustrated panels and the closing horizon.
- Let major chapters breathe with 160px separations while card copy remains 24px padded.

### Don't

- Do not turn primary conversion buttons into saturated blue pills; their main treatment is pale and rectangular.
- Do not use 700–900 weight display text; the rounded 500–600 weights carry the hierarchy.
- Do not apply negative tracking to all body copy; 16px card paragraphs use normal tracking.
- Do not flood the whole page with a bright blue gradient; luminosity is concentrated behind objects.
- Do not make every card a colorful solid tile; dark text shelves and selective lit edges are essential.
- Do not use a uniform bright 1px white outline on every card; rims should fade and change with the light.
- Do not scale code labels to body-heading size; the product scene is a compact technical artifact.
- Do not replace the ending with a flat boxed CTA; the horizon needs unboxed space before the resource footer.

## Motion and responsive

### Motion

**Observed:**

- Resource link colors transition over 0.2s using cubic-bezier(0.4,0,0.2,1). Main paired actions declare 0.3s color-family transitions with the same easing.
- Header height, border-color and background-color declare a 0.2s transition.
- Inline resource links become white with a white underline on hover; navigation links instead dim to #abaebb.

**Transfer:**

- Preserve the different hover behavior of navigation and embedded resource links.
- Keep the product theatre readable in a settled state; movement should not be required to understand the input/output relationship.

**Unknown:**

- Product-scene animation timing, scroll choreography and carousel autoplay behavior are not established.

### Responsive

**Observed:**

- Declared width thresholds include 320px, 359px, 413px, 480px, 639px, 640px, 767px, 799px, 991px, 992px, 1023px, 1279px and 1439px.
- Responsive classes reduce hero heading size, center supporting text at narrow widths, collapse the bento to one column, hide the middle navigation links and reduce card padding.

**Transfer:**

- On narrow screens, stack the promise and demonstration while keeping the small overlapping input/output composition intact.
- Reduce illustration scale and collapse multi-column comparison content rather than compressing technical labels into unreadability.
- Keep horizon lighting behind the ending rather than letting it cover resource links.

**Unknown:**

- Exact breakpoint-to-class mapping and rendered mobile arrangements are not established. No fluid type formulas are established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
