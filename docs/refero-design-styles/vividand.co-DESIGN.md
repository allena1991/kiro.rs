# Vivid+Co — prismatic manifesto

## Overview

A cinematic dark style that pairs matter-of-fact grotesk typography with refractive glass sculpture and faint spectral light. Warm white statements dominate a near-black field, with cool halos and flashes of rainbow color confined to the imagery. The feeling is conceptual and self-assured rather than technical or dashboard-like, suited to ambitious products and expert services with a strong point of view. Density alternates between monumental text and restrained lists, portraits and small proof marks.

### Essentials

- Statements behave like oversized spoken lines: regular-weight Neue Montreal at 105.3px/1.01 for chapter headlines and 135.9px/1 with -0.02em tracking for the opening.
- The opening is deliberately off-center: a two-line headline begins about one quarter across the viewport, a glass object crosses behind it, and 33.5px/1.2 support text starts around the horizontal midpoint below.
- Actions remain typographic, not chunky pills: the closing action is an inline warm-white link with a 1px underline; navigation uses a small unfilled rectangular contact outline.
- Color belongs to refraction, not interface chrome: #101010 and #fffdf9 dominate the entire page; rainbow slivers live on glass edges and broad blue-violet halos fade almost to black.
- A luminous modular sculpture and a soft peripheral halo are signature devices: stage a tilted glass assembly behind text, with a clear dark center. Without bespoke 3D, use beveled SVG tiles with narrow spectral edges rather than substitute stock photography.
- Hierarchy is also indentation: use an eight-column field with 38.4px gutters, principal copy inset about 185px and support paragraphs shifted one or more columns right.
- The ending is another manifesto, not a boxed conversion banner: 105.3px lines joined by plus signs sit beside a 331px support column, followed by compact contact and legal rows over the continuing atmospheric field.

## Colors

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Slate blue rule | `#495764` | `--color-cool-rule` | border, accent | Visible result of slate #6f879c at 60% opacity over the canvas; use rgba(111,135,156,0.6) for proof and accordion separators. This is an edge color, not a large panel fill. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm white | `#fffdf9` | `--color-text` | text, border, link, action | All primary text, monochrome marks, small icons and action underlines. |
| Near-black canvas | `#101010` | `--color-canvas` | background, surface | Continuous page field behind typography and atmospheric artwork. |
| Dim warm rule | `#403f3f` | `--color-rule` | border | Visible warm-white separator at 20% opacity over the canvas; use rgba(255,253,249,0.2) for service-card rules. |

## Typography

- **Neue Montreal** — All marketing text, from monumental statements to small captions. Neutral contemporary grotesk with open counters and a light-feeling regular cut; the hierarchy comes from scale and line placement rather than weight changes. If unavailable, use **DM Sans**. Use 400 for text and display; tune line breaks to preserve the broad, unforced silhouette. Font stack: "Neue Montreal", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Scales with viewport | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| display | Neue Montreal | 400 | 135.9px | 1 | -0.02em | fixed | Two-line opening statement; short introductory phrase above a changing identity or promise. |
| statement | Neue Montreal | 400 | 105.3px | 1.01 | normal | fixed | Main chapter statements and monumental closing line; usually two to five intentionally wrapped lines. |
| heading | Neue Montreal | 400 | 55.9px | 1.125 | normal | fixed | Secondary chapter headings that introduce a long supporting list. |
| lead | Neue Montreal | 400 | 33.5px | 1.2 | -0.01em | fixed | Opening description, offset support paragraphs, names and large inline actions. |
| section-label | Neue Montreal | 400 | 32px | 1.01 | normal, uppercase | fixed | Large utilitarian section labels, proof-row titles and accordion names. |
| contact | Neue Montreal | 400 | 21px | 1.24 | 0.01em | fixed | Footer email contact, slightly more prominent than the legal row. |
| body | Neue Montreal | 400 | 20px | 1.2 | -0.01em | fixed | Service descriptions and compact editorial support. |
| service-label | Neue Montreal | 400 | 16.8px | 1.5 | 0.02em, uppercase | size clamp(1.5rem, 0.3929rem + 0.8929vw, 2rem) | Uppercase service headings paired with small symbols. |
| caption | Neue Montreal | 400 | 15px | 1.2 | 0.01em | fixed | Small role qualifiers beside names and the restrained footer. |

Sizes are for a 1440px-wide desktop window. Recipes with a viewport formula grow and shrink with the window; use the formula (for example in `clamp()`), not the fixed pixel value.

**Notes:**

- Keep the display and statement recipes regular, even when the claim is emphatic. Large chapters use normal tracking; only the opening tightens to -0.02em.
- Support text is unusually substantial at 33.5px, then drops to 20px for descriptions. Preserve that separation rather than flattening everything into a standard body size.
- Wrap statements as editorial phrases. Keep support blocks narrow enough for three to five short lines; do not center them beneath the headline.

## Layout

**Density:** Airy and theatrical: tall pauses separate compact information groups, while oversized text itself stays closely led.

### Spacing

| Value | Use | Scales with viewport |
| --- | --- | --- |
| 38.4px | Default row and column gutter in the eight-column field. | clamp(1.6rem, 0.8105rem + 2.1053vw, 4.6rem) |
| 56px | Service-card space below body copy before the separator. | fixed |
| 64px | Section-level inner breathing room. | fixed |
| 72px | Header side inset at desktop. | 5vw |
| 79px | Typical gap between a monumental statement and its right-shifted supporting paragraph. | fixed |
| 180px | Intermediate separation between major narrative regions. | fixed |
| 450px | Long theatrical pause for the evolving atmospheric scene; reserve for major chapter changes rather than every content block. | fixed |

### Containers and grids

- **eight-column field**: 8 columns · gap 38.4px. Full-width underlying desktop grid. Content often occupies the central six columns; staggered left edges make typography and media feel choreographed.
- **main content**: max width 1070px · side padding 0px. Central reading region at 1440px, with approximately 185px left and right insets. Let the artwork extend outside this region.
- **service grid**: max width 1070px · 3 columns · gap 38.4px. Three equal 331px text modules within the main content region.
- **offset support**: max width 516px. Support paragraphs begin around the page midpoint. In the opening, the description expands to 603px; in the closing it narrows to 331px.
- **indented list**: max width 886px. Secondary list starts one grid column to the right of the principal heading; horizontal rules stretch far beyond the short labels.

## Corner radius

| Element | Radius |
| --- | --- |
| portrait frame | 15px |

## Surfaces and depth

### Surfaces

#### Dark field · level 0

**Use:** Unbroken background for the entire narrative.

**CSS:** `background: #101010; color: #fffdf9`

**Observed:** No alternating solid-color bands or raised-panel system. Atmospheric light changes the field while its base stays dark.

**Transfer:** Use a continuous canvas across section boundaries so artwork can persist through the story.

#### Rule-only module · level 1

**Use:** Services, proof rows and secondary lists.

**CSS:** `background: transparent; border-bottom: 1px solid rgba(111,135,156,0.6)`

**Observed:** Content is grouped with horizontal lines, not enclosing borders or shadows. Service modules use the warmer rgba(255,253,249,0.2) variant.

**Transfer:** Preserve long, low-contrast separators and open sides even when adapting the content to features or results.

## Components

### Fixed navigation

**Use:** Persistent orientation and a compact contact route.

**CSS:** `position: fixed; top: 0px; height: 121px; padding-left: 72px; padding-right: 72px; z-index: 20; color: #fffdf9`

**Observed:** Small wordmark at left and a widely spaced uppercase link cluster at right; the final contact action has a thin unfilled rectangular outline. All elements sit directly on the atmospheric background.

**Transfer:** Keep navigation visually subordinate to the opening statement; use a short label set and a single outlined endpoint.

### Inline contact action

**Use:** Conversational conversion within the closing support paragraph.

**CSS:** `color: #fffdf9; background: transparent; border-bottom: 1px solid #fffdf9`

**Text style:** `lead` — Neue Montreal 400 · 33.5px/1.2 · tracking -0.01em

**Observed:** The action completes a sentence and shares the surrounding paragraph's baseline; it is not separated into a button row.

**Transfer:** Use a brief lowercase verb phrase tied to the next real step.

### Service module

**Use:** Explain three related capabilities without heavy card chrome.

**CSS:** `position: relative; padding-bottom: 56px; border-bottom: 1px solid rgba(255,253,249,0.2)`

**Text style:** `body` — Neue Montreal 400 · 20px/1.2 · tracking -0.01em

**Observed:** A small geometric symbol and uppercase Service-label form the header, followed by a compact description. Three modules share one horizontal baseline and equal widths.

**Transfer:** Use the same construction for product pillars, methods or outcomes; keep descriptions similar in length.

### Proof row

**Use:** List selected work or analogous evidence.

**CSS:** `position: relative; border-bottom: 1px solid rgba(111,135,156,0.6); transition: border-color 0.2s cubic-bezier(0.52, 0.01, 0, 1)`

**Text style:** `section-label` — Neue Montreal 400 · 32px/1.01 · uppercase

**Observed:** Short uppercase identifiers sit at the left of very broad, tall rows. The row spans 1070px while the identifier occupies only a narrow portion; heights vary around 179–211px.

**Transfer:** Use concise evidence labels, not dense card descriptions. Supply actual supporting details through the appropriate linked or expanded destination.

### Portrait tile

**Use:** Human proof in an editorial people or customer chapter.

**CSS:** `position: relative; width: 343px; height: 406px; border-radius: 15px; overflow: hidden`

**Observed:** A light-backed color portrait sits above a large name and a tiny plus-prefixed role on the same caption line; a long fine rule anchors the tile below. The horizontal strip continues beyond the viewport, with neighboring tiles vertically staggered.

**Transfer:** Use real people with uncluttered pale backgrounds. For non-person content, retain a single clearly framed subject rather than filling the strip with UI thumbnails.

### Accordion row

**Use:** Secondary authority list or concise supporting detail.

**CSS:** `border-bottom: 1px solid rgba(111,135,156,0.6)`

**Text style:** `section-label` — Neue Montreal 400 · 32px/1.01 · uppercase

**Observed:** Each header is a full-width button in an indented 886px list; rows are approximately 161px high. Names are uppercase and vertically centered within an otherwise open dark field.

**Transfer:** Use for an appropriate authority, partner or detail list. Preserve the generous height and long rules instead of adding a boxed FAQ treatment.

### Contact footer

**Use:** Close with practical contact information without breaking the mood.

**CSS:** `display: flex; align-items: center; color: #fffdf9`

**Text style:** `contact` — Neue Montreal 400 · 21px/1.24 · tracking 0.01em

**Observed:** A single email line sits beside a small social mark. A separate small caption row contains copyright and two understated underlined legal links. The footer stays aligned with the main 185px inset and shares the closing artwork rather than introducing a new background.

**Transfer:** Retain the two-level hierarchy and considerable breathing space; adapt contact routes to the new product.

## Imagery and graphics

### Refractive modular sculpture

**Use:** Signature visual in the opening and at later narrative transitions, including the closing.

**Observed:** Dark transparent cubes assemble into tilted, stepped structures. Bright warm-white bevels, electric-blue edges and tiny rainbow bands make the glass legible. The opening assembly is roughly 300px wide and 400px tall, centered behind the text toward the right; later a lone cube or a wider cluster changes the silhouette. Objects float without a visible platform or rectangular image frame.

**Transfer:** Create a simple modular object that expresses the new product's organizing idea. A minimum acceptable version is a small family of tilted, beveled translucent tiles, with layered faces and spectral edges; the luminous geometry must remain even when there is no product photography.

**Build:** Use SVG polygons to draw three faces per cube, around 110px per face in the opening. Arrange four to six cubes in a stepped cluster about 300px by 400px and rotate the group around 20deg. Keep face fills near the canvas color with low opacity; stroke exposed top edges warm white at 1–3px. Duplicate selected edge paths behind with 6–12px blur and translucent blue. Add narrow red-to-yellow-to-cyan-to-blue linear-gradient strips along only one or two bevels per cube. Layer the group behind live text, not inside a card.

### Peripheral spectral halo

**Use:** Continuous atmospheric backdrop, strongest around major human-proof and closing regions.

**Observed:** A huge, softly defocused ring leaves the center almost black. Its cool blue, cyan and violet edges are uneven, cloudy and faintly grainy; the ring is partially clipped by viewport edges. This is optical spill rather than a crisp neon circle. Some chapters nearly lose the halo, allowing text to dominate.

**Transfer:** Carry a soft luminous perimeter through the page and change its strength between chapters. Keep the reading center dark; match the soft glow rather than relying on exact gradient stops.

**Build:** Place two or three oversized elliptical SVG strokes behind content, each around 1200px wide and 1000px high at desktop. Use 30–80px strokes with translucent blue, cyan and violet segments, blurred 40–100px. Mask the center with a dark radial falloff and let the outer edges clip. Add very faint monochrome turbulence over the light to break up perfect digital gradients. Keep the field subtle enough that warm-white text stays the brightest layer.

### Light-backed portraits

**Use:** Editorial people and testimonial content.

**Observed:** Natural color head-and-shoulder photography against pale studio-like backgrounds, framed in tall 343px by 406px rounded rectangles. Clothing is understated and expressions thoughtful; a trace of colored light harmonizes the photos with the surrounding halo.

**Transfer:** Commission or select similarly restrained portraits with real expressions, pale backgrounds and tight vertical framing. Keep photographic color local to the image instead of recoloring the whole page.

### Monochrome proof marks

**Use:** Compact client and publication proof bands.

**Observed:** Small warm-white logos are grouped on the dark field beside uppercase section labels. Repeated media cells are around 140px by 80px, leaving substantial room around each mark.

**Transfer:** Normalize authentic partner marks by optical size and use monochrome treatments where allowed; retain the small scale so proof remains secondary to the statements.

### Icons

**Observed:** Small solid warm-white SVG marks, generally 20px or 24px; smaller 11px geometric symbols sit with service labels. Plus signs recur in the editorial language and role captions.

**Transfer:** Choose spare solid geometric symbols and a single-color social mark. Avoid multicolor app-icon tiles and detailed line illustrations.

## Section recipes

How recurring sections are built.

### First screen: Refractive statement opening

**Observed:** Dark field and Peripheral spectral halo sit furthest back, then the Refractive modular sculpture, then live warm-white type and Fixed navigation. A two-line 135.9px statement begins about one quarter across the viewport, below a large upper breathing area, and occupies much of the central width. The first short phrase sits above a changing identity word; the glass assembly tilts behind the right side of both lines. A three-line Lead paragraph begins around the midpoint, roughly 59px below the display area, with a width near 603px. Within the first 900px the navigation, whole headline, glass assembly and support paragraph are visible. There is no separate hero CTA group: the outlined contact route is in navigation. Further narrative statements begin below the first screen.

**Transfer:** Use a short introductory phrase and a strong product identity or promise with a comparable two-line silhouette. Rebuild the modular sculpture from simple glass tiles if no bespoke art exists. For detail-oriented page types, keep the offset opening and optical backdrop but use a specific subject statement instead of a changing identity.

**Avoid:** Do not turn this into a centered headline above a dashboard image, a left-text/right-card SaaS split, or a row of filled conversion buttons.

**Text style:** `display` — Neue Montreal 400 · 135.9px/1 · tracking -0.02em

### Offset manifesto pair

**Observed:** Statement typography spans two to five lines across the central 1070px region. A Lead paragraph sits below, separated by around 79px and shifted toward the right, typically within 516px. The artwork can drift behind or between these text blocks while the text remains foreground.

**Transfer:** State one strong viewpoint about the reader's problem, then resolve it with a short supporting explanation. Preserve the asymmetric relationship rather than a specific topic or number of lines.

**Text style:** `statement` — Neue Montreal 400 · 105.3px/1.01

### Three open capabilities

**Observed:** Service modules align as three 331px columns with 38.4px gutters. Uppercase headers with small geometric symbols lead 20px descriptions; warm translucent bottom rules replace card boundaries. Long surrounding pauses let this relatively compact group act as a change of pace.

**Transfer:** Group three similarly weighted ideas under concrete labels, using comparable copy lengths and no enclosing backgrounds.

**Text style:** `body` — Neue Montreal 400 · 20px/1.2 · tracking -0.01em

### Evidence ledger and marks

**Observed:** Proof rows stack across the main content width with narrow uppercase identifiers at left and long cool separators. Smaller monochrome proof marks sit in adjacent bands with Section-label headings rather than in decorative badges.

**Transfer:** Combine a small set of concrete project entries with authentic outside validation. Adapt the proof format to the new offering without fabricating metrics.

**Text style:** `section-label` — Neue Montreal 400 · 32px/1.01 · uppercase

### People strip and supporting list

**Observed:** A two-line Statement heading sits left, with a short Body introduction indented beneath. Portrait tiles enter from the right, stagger vertically and continue past the edge. The Peripheral spectral halo becomes more visible here. A smaller Heading then introduces an indented Accordion row list.

**Transfer:** Use this composition when people, customers or collaborators are the relevant proof; otherwise borrow the horizontal framed-subject strip for comparable real-world evidence. A secondary list can give depth without competing with the main headline.

**Text style:** `statement` — Neue Montreal 400 · 105.3px/1.01

### Monumental closing and contact

**Observed:** A Section-label introduction leads a four-line Statement block occupying about 701px on the left. Plus signs join short concepts. A 331px Lead paragraph sits at right and ends with Inline contact action. Refractive modular sculpture overlaps behind the lower statement, with the halo continuing around the perimeter. Contact footer follows on the same dark field, with email and social mark above a tiny legal row; approximately 140px of breathing room remains at the bottom.

**Transfer:** Finish with an equally concise statement of the product's promise or desired outcome, linked by plus signs where appropriate, beside a direct invitation. Keep the atmospheric device and compact practical footer, not the original recruiting topic.

**Text style:** `statement` — Neue Montreal 400 · 105.3px/1.01

## Page flow

**Storyline:** identity → point of view → capabilities → concrete proof → human credibility → monumental invitation → practical contact

### A cinematic marketing landing page that establishes a strong perspective before supplying compact proof

1. **Identity** — A two-line offset display, short description and refractive sculpture establish character before detailed explanation.
2. **Point of view** — Large editorial statements alternate with smaller right-shifted supporting arguments and evolving glass geometry.
3. **Capabilities** — Three open, rule-bottom modules briefly clarify how the promise is delivered.
4. **Concrete proof** — A large outcome statement leads to tall evidence rows and small monochrome validation marks.
5. **Human credibility** — Staggered portrait strip and an indented secondary authority list give the argument a human face.
6. **Closing invitation** — Plus-linked monumental text and an inline contact invitation share the field with a final glass assembly.
7. **Practical contact** — Email, a social mark and minimal legal links finish without a separate footer panel.

**Transfer:** Treat this as a narrative rhythm, not a prescribed section count. Keep the shift from big declarations to compact proof, and repeat the optical sculpture and peripheral light wherever they best reinforce the new story.

## Writing

Confident, articulate and direct, with a strategic rather than sales-promotional tone. Strong claims are expressed as plain statements, followed by short explanations of the underlying approach.

**Do not copy:** Do not reuse the brand name, personnel names, client or publication assets, proprietary artwork, service claims or original statements as claims for the new product. Examples illustrate cadence only.

- **Addressing the reader:** The company speaks as “we” and “our”; readers are usually addressed indirectly through their ambitions and challenges, with a direct invitation near the end.
- **Rhythm:** Short identity language gives way to longer, deliberately line-broken declarative headlines. Support is one or two compact sentences; parallel clauses, repetition and plus signs provide rhythm without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening identity | A very short collective introduction followed by an identity word or phrase. | 2–5 words | “We are” |
| Editorial headline | A confident assertion built from repeated or parallel phrases, made legible through line breaks. | 8–20 words | “Our unconventional process generates unconventional outcomes”<br>“Strategy without clarity, PR without purpose, and creative without identity simply don’t work” |
| Supporting line | Explain the operating approach or resolve the headline in one clear sentence. | 12–30 words | “We take an integrated approach because there is no silver bullet to building a brand.” |
| Section label | Plain descriptive noun phrase without decorative punctuation. | 1–4 words | “Our clients”<br>“Meet our people” |
| Primary action | A lowercase conversational verb phrase that completes the sentence. | 2–3 words | “contact us” |

**Words and phrasing to use:** clarity; purpose; together; approach; outcomes; creativity; experience; solve; we / our

**Avoid:** revolutionary!!!; 10x everything; unlock limitless potential; game-changing ecosystem; click here

**Rules:**

- Give each monumental headline one coherent thought; use parallel clauses only when they sharpen the argument.
- Follow an abstract statement with a concrete explanation rather than another slogan.
- Let a direct sentence carry the confidence; avoid hype punctuation and stacked superlatives.
- Use plus signs as readable joins between short concepts, not as decoration on every label.

## Do's and Don'ts

### Do

- Keep the principal display at weight 400 and its opening tracking at -0.02em.
- Use #fffdf9 rather than stark blue-white for text and hairlines.
- Retain the eight-column logic and 38.4px desktop gutters when shifting support copy to the right.
- Stage glass geometry behind live text with enough dark face area to preserve legibility.
- Use 1px bottom rules for evidence and service modules, leaving their sides open.
- Keep the closing invitation at Lead size with an inline underline rather than a separate large button.
- Give portraits their distinct 15px corners and 343px by 406px vertical framing.
- Preserve the compact email-plus-social footer below the monumental closing.

### Don't

- Do not promote the slate rule color into a large blue panel; it is an edge treatment.
- Do not use 700-weight type for the oversized statements; the characteristic force comes from scale.
- Do not make every section a rounded card: the only substantial rounding belongs to framed media.
- Do not put rainbow gradients on body text or action fills; spectrum belongs to optical artwork.
- Do not enlarge monochrome partner marks into hero-sized badges; their cells are around 140px wide.
- Do not replace the peripheral halo with a sharp, high-contrast neon ring; the center must stay dark.
- Do not collapse the 33.5px Lead and 20px Body into one generic 16px paragraph style.
- Do not add drop shadows to raise content panels from the canvas; separation comes from space and hairlines.

## Motion and responsive

### Motion

**Observed:**

- Text lines are wrapped in overflow-hidden masks with declared transform transitions of 0.5s cubic-bezier(0.52, 0.01, 0, 1), including staggered delays.
- Proof-row border transitions declare 0.2s cubic-bezier(0.52, 0.01, 0, 1). Other elements declare opacity 0.25s linear.
- The fixed full-viewport canvas declares opacity 1s cubic-bezier(0.215, 0.61, 0.355, 1). The opening identity wording differs between rendered and static text, consistent with a changing identity treatment.

**Transfer:**

- Reveal oversized phrases by line through masks rather than scaling the whole headline.
- Use the evolving glass assembly and peripheral light to connect narrative chapters; keep practical links subordinate to that scene.

**Unknown:**

- Exact WebGL choreography, scroll timing, pointer response, complete identity-word cycle and action hover/focus appearances are unknown.

### Responsive

**Observed:**

- Declared width breakpoints include 640px, 767px, 768px, 1024px, 1239px, 1240px and 1800px.
- Header side padding uses 5vw; grid gaps and service labels use clamped fluid values.

**Transfer:**

- On narrow screens, preserve the hierarchy of monumental statement, offset support and optical artwork, but reduce indentation so phrases remain readable.
- Stack service modules and keep their bottom rules. Let the horizontal framed-subject strip remain edge-clipped only if its remaining content is accessible.
- Recompose glass and halo around the text rather than shrinking the complete desktop scene into a miniature.

**Unknown:**

- Exact mobile headline sizes, navigation collapse and touch behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
