# Depot — prismatic signal flow

## Overview

An airy technical style that makes infrastructure feel fast, tangible, and interconnected. Cool pale-gray canvases, black grotesk headlines, compact monospaced markings, and cyan-to-violet light create a bright rather than dark developer aesthetic. Abstract flowing tracks, translucent blocks, and fine-lined geometric diagrams carry the visual story, with restrained interface demonstrations and candid photography reserved for supporting roles.

### Essentials

- Headlines feel compressed vertically, not heavy: Neue Montreal at 92px/0.9, weight 500, -0.03em tracking for the opening; 72px/0.9 for major chapters and 52px/1.05, weight 400, -0.02em for explanatory sections.
- The opening is an asymmetric meeting of streams and language: an 800px-tall stage with diagonal cyan–violet tracks occupying the upper-left and a right-aligned 840px text block anchored in the lower-right, inside 48px gutters.
- Actions are tiny technical instruments beneath monumental text: 32px-high, 6px-radius rectangles with 12px uppercase mono labels; pair a blue-to-purple fill with a canvas-filled gradient-outline action, separated by 24px.
- Color travels rather than coats: #eaecf0 remains the continuous majority canvas; saturated #00aaff and #a033ff belong to tracks, small markers, button edges, selected details, and atmospheric light, not alternating solid section fills.
- Every landing page carries a flowing signal graphic: fine parallel paths mixed with broad translucent ribbons and a few luminous blocks, fading into the canvas. Without product media, use an original SVG network of smooth offset paths rather than a generic dashboard mockup.
- The ending blooms into light, then returns to an expansive utility landscape: a 465px centered conversion band with overlapping 120px-blurred cyan and violet lights, followed by a 960px-minimum footer with four mono link columns, a substantial lower-left identity, and diagonal track artwork at lower-right.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal cyan | `#00aaff` | `--color-blue` | accent, action, border | Bright end of flowing graphics, focus outlines, gradient details, and atmospheric light. |
| Signal violet | `#a033ff` | `--color-purple` | accent, action | Violet end of tracks, glows, gradient frames, and small emphasis. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Diagram lavender | `#dcdaee` | `--color-lavender` | surface | Pale lavender top of illustration panels, fading to canvas. |
| Atmospheric periwinkle | `#bccaf0` | `--color-wash-blue` | background | Broad pale radial washes behind proof and product-flow scenes. |
| Atmospheric lilac | `#d8dcf2` | `--color-wash-lilac` | background | Intermediate pale color in broad radial washes. |
| Action violet | `#a338ff` | `--color-button-violet` | action | Right-hand saturated endpoint of the primary button gradient. |
| Action blue | `#007dbc` | `--color-button-blue` | action | Darker blue endpoint that keeps white action labels legible. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action white | `#ffffff` | `--color-white` | text | Text on saturated gradient actions. |
| Cool canvas | `#eaecf0` | `--color-canvas` | background, surface | Continuous marketing canvas and card interiors; also used at 75% alpha for the translucent header over the same pale environment. |
| Control gray | `#dbe0e2` | `--color-control` | surface | Utility-control backing, table header bands, and theme switch tray. |
| Quiet hairline | `#d4d6d9` | `--color-rule` | border, surface | Default card outlines, table separators, and footer top edge. |
| Structural edge | `#c6ced1` | `--color-edge` | border, surface | More legible panel boundaries, progress tracks, and carousel controls. |
| Technical gray | `#636365` | `--color-muted` | text, border | Supporting copy, inactive labels, outline controls, and fine diagram lines. |
| Near black | `#080808` | `--color-ink` | text, background | Headlines, active labels, identity marks, and small solid plan tags. |

## Typography

- **Neue Montreal** — Headlines, introductory paragraphs, feature titles, and quotes. Compact neo-grotesk with open counters and understated personality; regular explanatory headings contrast with medium display lines. If unavailable, use **Inter**. Use 400 and 500; retain tight display tracking and check line wraps. Font stack: "Neue Montreal", "Inter", ui-sans-serif, system-ui, sans-serif.
- **Neue Montreal Text** — Body copy, navigation, and supporting feature descriptions. Text-oriented companion grotesk with a compact, even texture. If unavailable, use **Inter**. Use 400 with the small negative tracking of the text recipes. Font stack: "Neue Montreal Text", "Inter", ui-sans-serif, system-ui, sans-serif.
- **ABC Favorit Mono** — Eyebrows, buttons, sequence numbers, technical captions, and footer navigation. Plain monospaced lettering that gives small labels the feeling of system markings. If unavailable, use **IBM Plex Mono**. Use 400; avoid increasing the already compact uppercase tracking. Font stack: "ABC Favorit Mono", "IBM Plex Mono", ui-monospace, SFMono-Regular, Menlo, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Neue Montreal | 500 | 92px | 0.9 | -0.03em | Opening promise and monumental proof-directory heading. |
| chapter | Neue Montreal | 500 | 72px | 0.9 | -0.03em | Major product-family and advantages chapter headings. |
| heading | Neue Montreal | 400 | 52px | 1.05 | -0.02em | Default explanatory section heading; also large plan prices. |
| closing-heading | Neue Montreal | 500 | 40px | 1.1 | -0.01em | Centered conversion heading and compact major section leads. |
| subheading | Neue Montreal | 500 | 32px | 1.2 | -0.01em | Proof-band lead and substantial feature subheads. |
| feature-title | Neue Montreal | 500 | 24px | 1.3 | 0.005em | Feature selectors, comparison panel titles, and testimonial quotes. |
| footer-heading | ABC Favorit Mono | 400 | 20px | 1 | -0.01em, uppercase | Footer column headings. |
| lead | Neue Montreal | 400 | 19px | 1.35 | normal | Introductory support text and explanatory section paragraphs. |
| body | Neue Montreal Text | 400 | 16px | 1.4 | -0.005em | Feature descriptions and compact prose. |
| mono-body | ABC Favorit Mono | 400 | 16px | 1.05 | -0.01em, uppercase | Footer links and timeline date markings. |
| nav-label | Neue Montreal Text | 400 | 16px | 1 | -0.005em | Compact dropdown navigation labels. |
| label | ABC Favorit Mono | 400 | 12px | 1.1 | normal, uppercase | Eyebrows, action labels, and small technical annotations. |

**Notes:**

- Large headlines tighten to -0.03em and use a 0.9 line height, while explanatory headings relax to -0.02em and 1.05. Do not replace this hierarchy with bold weights.
- Feature titles use slightly positive tracking rather than the negative tracking of large headings.
- Keep labels visibly much smaller than the content they identify. Capital-height alignment makes actions feel compact even with substantial internal padding.

## Layout

**Density:** Airy at the section scale, compact within controls and data rows; long intervals let the graphics and large type breathe.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Tight inline icon or utility spacing. |
| 12px | Eyebrow marker gap, navigation action gap, and button horizontal inset. |
| 16px | Feature title-to-description gap. |
| 24px | Standard card padding, heading group gap, action pair gap, and three-column grid gutter. |
| 32px | Opening text-stack gap and selector left inset. |
| 40px | Spacing between feature-selector items and portrait grid rows. |
| 48px | Desktop side gutters, proof-directory gutter, and closing heading-to-action interval. |
| 64px | Section heading-to-content and two-part feature layout gaps. |
| 80px | Compact opening-to-content spacing on secondary page types. |
| 96px | Large chapter heading-to-content gap or section bottom padding. |
| 112px | Footer top padding and deep comparison-panel bottom inset. |
| 224px | Default desktop separation between major narrative sections. |

### Containers and grids

- **marketing-container**: max width 1624px · side padding 48px. Centered full-width marketing wrapper; at a 1440px viewport its content is 1344px wide.
- **opening-copy**: max width 840px. Right-aligned opening headline block; its support paragraph narrows to 700px.
- **explanatory-heading**: max width 800px. Left-aligned section headline allowed to wrap into two short lines.
- **triple-grid**: 3 columns · gap 24px. Equal-width plans, quote cards, and capability summaries; each column is 432px at desktop.
- **feature-split**: 2 columns · gap 64px. Selector list and larger illustration panel, using a 0.85:1 width relationship.
- **story-directory** (only for customer proof directories): 2 columns · gap 48px. Wide unboxed story entries separated by horizontal rules.
- **portrait-wall** (only for company and team pages): 6 columns · gap 24px. 204px square portraits with 40px row gaps and text directly underneath.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-and-panels | 6px |
|  | theme-switch-tray | 8px |
| technical product demonstrations | technical-media | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| luminous-frame | `0px 0px 12px 6px rgba(116,140,255,0.22)` | A soft chromatic halo behind an emphasized technical demonstration or recommended plan. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light page ground.

**CSS:** `background: #eaecf0; color: #080808`

#### Quiet panel · level 1

**Use:** Comparisons and structured grouped content.

**CSS:** `background: #eaecf0; border: 1px solid #d4d6d9; border-radius: 6px; box-shadow: none`

**Observed:** Panels are defined by edges rather than a different fill. Their internal content remains spacious.

**Transfer:** Use outlines to group ideas without turning the page into a stack of elevated cards.

#### Diagram backing · level 1

**Use:** Fine-line abstract product illustrations.

**CSS:** `background: linear-gradient(#dcdaee 0%, #eaecf0 70%); border: 1px solid #c6ced1; border-radius: 6px; overflow: hidden`

**Observed:** A pale lavender ceiling dissolves toward the lower canvas; the illustration floats near the center.

**Transfer:** Keep the object smaller than its frame with ample surrounding air.

#### Proof wash · level 0

**Use:** Broad, nearly borderless trust or flow bands.

**CSS:** `background: radial-gradient(110% 110% at 10% 0%, #bccaf0 0%, #d8dcf2 30%, #eaecf0 90%)`

**Transfer:** Use as a gentle environmental change rather than a colored card.

#### Luminous frame · level 1

**Only for:** emphasized demonstrations and recommended plans

**Use:** Highlight one important framed object.

**CSS:** `background: conic-gradient(from 188.238deg, #00aaff 0%, #a033ff 50%, #00aaff 100%); border-radius: 4px; padding: 1px`

**Observed:** A canvas-colored inner panel masks the gradient center. The technical demo has a blurred duplicate behind it at 0.72 opacity and 15px blur; the recommended plan uses a tighter 3px blur and 6px corners.

**Transfer:** Keep the luminous edge thin; the interior remains pale and readable.

## Components

### Sticky navigation

**Use:** Persistent slim top navigation.

**CSS:** `position: sticky; top: 0px; height: 60px; background: rgba(234,236,240,0.75); backdrop-filter: blur(16px); z-index: 20`

**Text style:** `body` — Neue Montreal Text 400 · 16px/1.4 · tracking -0.005em

**Observed:** Identity at left, plain text navigation alongside it, and paired compact actions at far right. A 48px announcement strip sits below on entry, with a tiny icon and dismiss control; a faint cyan–violet hairline defines the boundary.

### Primary button

**Use:** Main self-serve conversion.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 12px; border-radius: 6px; background: radial-gradient(112% 300% at 125% 50%, #a338ff 0%, #007dbc 88%); color: #ffffff`

**Text style:** `label` — ABC Favorit Mono 400 · 12px/1.1 · uppercase

**Observed:** Short uppercase mono label, sometimes followed by a small right arrow. The main marketing variant is compact; comparison-table actions reduce to 24px height.

**States:** Declared: hover adds 0 0 0 1px rgba(255,255,255,0.08), 0 0 14px rgba(160,51,255,0.28), 0 0 24px rgba(0,170,255,0.22); focus-visible uses a 2px solid #00aaff outline with 2px offset.

### Secondary button

**Use:** Docs, contact, or a secondary proof action beside the primary.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 32px; padding: 11px 12px; border: 1px solid transparent; border-radius: 6px; background: linear-gradient(#eaecf0, #eaecf0) padding-box, linear-gradient(90deg, #00aaff, #a033ff) border-box; color: #080808`

**Text style:** `label` — ABC Favorit Mono 400 · 12px/1.1 · uppercase

**Observed:** Canvas-filled center with a very fine chromatic outline. Some labels carry a leading docs or code icon. Compact table variants reduce the height to 26px.

**States:** Declared: hover adds 0 0 14px rgba(160,51,255,0.24), 0 0 24px rgba(0,170,255,0.18); focus-visible uses a 2px solid #00aaff outline with 2px offset.

### Comparison panel

**Use:** Explain an old approach beside a new model.

**CSS:** `background: #eaecf0; border: 1px solid #d4d6d9; border-radius: 6px; padding: 24px 24px 112px; display: flex; flex-direction: column; gap: 40px`

**Text style:** `feature-title` — Neue Montreal 500 · 24px/1.3 · tracking 0.005em

**Observed:** Small identity icon and title lead a vertical list. The new-model panel is much wider and splits its list from a pale framed flow illustration; violet checkmarks replace the old model's gray circles.

**Transfer:** Compare mechanisms rather than inventing a long feature checklist.

### Feature selector

**Use:** Show several capabilities against one changing diagram.

**CSS:** `display: flex; flex-direction: column; gap: 16px; text-align: left`

**Text style:** `feature-title` — Neue Montreal 500 · 24px/1.3 · tracking 0.005em

**Observed:** Each item has a tiny two-digit mono number, a title, and a short body paragraph. Items are spaced by 40px; an inset 32px from a thin vertical rail creates alignment. The active segment is cyan–violet and the active text is black; inactive entries recede.

**Transfer:** Pair a compact set of distinct benefits with a shared Diagram backing.

### Footer link column

**Use:** Utility navigation in the large closing landscape.

**CSS:** `display: flex; flex-direction: column; gap: 12px; color: #636365`

**Text style:** `mono-body` — ABC Favorit Mono 400 · 16px/1.05 · tracking -0.01em · uppercase

**Observed:** Four columns use black Footer-heading labels and gray uppercase links. A bracketed online count is the rare gradient-text accent among the links.

### Theme switch

**Use:** Footer utility control.

**CSS:** `display: inline-flex; align-items: center; gap: 4px; padding: 4px; height: 52px; background: #dbe0e2; border-radius: 8px`

**Text style:** `label` — ABC Favorit Mono 400 · 12px/1.1 · uppercase

**Observed:** Three icon-and-text options share a tray. The selected option has a cyan–violet fill, white text, and soft colored glow; a separate language selector sits below.

### Plan card

**Only for:** pricing pages

**Use:** Present comparable paid tiers.

**CSS:** `display: grid; border: 1px solid #c6ced1; border-radius: 6px; overflow: hidden`

**Text style:** `heading` — Neue Montreal 400 · 52px/1.05 · tracking -0.02em

**Observed:** Small black rectangular tier tag, large price with a small billing suffix, uppercase mono description, divider, included allowances, and bottom-aligned action. Equal-height columns align their internal bands. The recommended middle plan gets the Luminous frame, gradient price, and small gradient popularity badge.

**Transfer:** Make only one plan chromatically prominent; keep all interiors on the page canvas.

### FAQ row

**Only for:** pricing and objection-handling sections

**Use:** Compact accordion questions.

**CSS:** `border-top: 1px solid #d4d6d9; min-height: 49px; width: 800px`

**Text style:** `lead` — Neue Montreal 400 · 19px/1.35

**Observed:** Plain question at left, small downward chevron at right; no card fill. The final row also has a bottom border. Rows form the wide right side of a heading-and-questions split.

### Case study entry

**Only for:** customer proof directories

**Use:** Make stories scan as a linked editorial directory.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; justify-content: space-between; gap: 24px; padding: 48px 24px 24px; border-bottom: 1px solid rgba(99,99,101,0.2)`

**Text style:** `lead` — Neue Montreal 400 · 19px/1.35

**Observed:** A monochrome customer logo sits above a one- or two-line outcome summary. A tiny uppercase mono case-study link with an arrow anchors the bottom; the entry is not enclosed on all four sides.

## Imagery and graphics

### Prismatic signal streams

**Use:** Signature opening artwork, product-flow chapters, and lower-right footer continuation.

**Observed:** Smooth parallel paths travel diagonally from lower-left to upper-right in the opening and footer. Fine cyan and purple lines coexist with broad translucent ribbons and elongated glassy blocks; edges dissolve into the pale background. Horizontal chapter versions split and recombine into smooth tracks rather than terminating in boxed nodes.

**Transfer:** Create an original network expressing the new product's transformation. The minimum version is layered SVG paths with smooth bends, color variation, and fading edges; it must still communicate directional flow.

**Build:** Draw 12–20 offset SVG paths with long straight runs connected by broad cubic bends. Mix 1px strokes at cyan and violet alpha 0.15–0.5 with 16–36px ribbon strokes at alpha 0.08–0.25. For the diagonal composition rotate the network about -35deg and let it overflow the stage; fade the perimeter with a canvas-colored mask. Add two or three elongated translucent isometric prisms using three polygon faces, bright cyan or violet end faces, low-alpha side faces, and a soft duplicate blurred by 8–16px. Fade behind the text with a canvas gradient.

### Geometric capability diagrams

**Use:** Illustration side of capability selectors and comparison panels.

**Observed:** Fine gray isometric cube grids and flowing line diagrams sit on Diagram backing. Most facets remain canvas-colored; a few isolated faces are vivid cyan or violet, with a diffused lavender halo and faint dashed construction guides.

**Transfer:** Abstract the product into connected modules, grids, or channels rather than using unrelated stock 3D objects.

**Build:** Construct an isometric object with SVG polygon faces and 1px gray divisions. Color only two or three cells cyan or violet. Place a low-opacity purple ellipse behind it with 40–70px blur and draw faint dashed diagonal construction lines under the object; leave generous empty area inside the frame.

### Conversion light bloom

**Use:** Signature centered conversion environment near the ending.

**Observed:** Blue light rises from below the left of center and violet from below the right, overlapping into a luminous pool behind a black mark, two-line heading, and compact actions. The top remains pale enough to read and the bottom is cut cleanly by the footer.

**Transfer:** Keep this luminous device even when the product has no visual interface. Use a simple original identity symbol above the invitation.

**Build:** Within a 465px isolated section, position two 400px by 600px rounded light layers below center, offset left and right by 56px. Use cyan at 0.5 opacity and violet at 0.7, each with 120px blur and 20% corners, translating down by 45%. Add broad 662px by 141px ellipses with 140px blur at 0.2 and 0.3 opacity for the distant wash. Keep content above all lights.

### Signal dash field

**Only for:** secondary page openings and social-proof sections

**Use:** Ambient texture behind centered opening text, logos, or quotes.

**Observed:** Short horizontal cyan, violet, and gray dashes gather into airy irregular vertical waves. The field is low contrast and fades away toward the bottom and center, keeping black type dominant.

**Transfer:** Use this as the quieter alternative to the prismatic stream opening for pricing, company, or customer pages.

**Build:** Use an SVG pattern of 1px horizontal dashes, 4–30px long, distributed on loose 8–16px vertical intervals. Vary opacity around 0.06–0.22 and reveal clusters through broad wave-shaped masks. Layer a canvas gradient over the center and bottom rather than creating a regular dot grid.

### Technical demonstration

**Only for:** technical product pages

**Use:** Concrete proof of workflow and performance.

**Observed:** A pale terminal panel occupies slightly more than half a split section, with a thin luminous edge and soft cyan–violet halo. Small mono command output sits near its top and right-aligned timings make performance legible; the adjacent heading and support are right aligned. A later compact code panel pairs with thin gradient benchmark bars.

**Transfer:** Use a real workflow excerpt or an equally sparse product demonstration. Keep the interface pale, not a dark developer-terminal cliché; do not expand its internal UI into the whole marketing style.

### Candid portrait wall

**Only for:** company and team pages

**Use:** Humanize a company introduction.

**Observed:** Square 204px portraits use mixed natural backgrounds, lighting, and occasional monochrome treatment. Six columns place names, tiny uppercase roles, and small social icons directly below without enclosing cards.

**Transfer:** Use authentic individual portraits with consistent square framing but do not force uniform studio styling.

### Icons

**Observed:** Mostly filled SVG glyphs at 12px, 16px, or 20px, colored muted gray or near black. Tiny docs, arrows, chevrons, code marks, and checks sit inline; a few technical capability icons are larger outline-like geometric forms.

**Transfer:** Choose simple compact silhouettes and keep their optical weight below the text. Use cyan–violet only for selected technical markers rather than making every icon colorful.

## Section recipes

How recurring sections are built.

### First screen: Signal stream opening

**Observed:** A 60px Sticky navigation precedes an 800px stage with a slim announcement strip near the top. Back-to-front layers are Canvas, oversized diagonal Prismatic signal streams entering from the left and upper edge, pale edge fades, then a right-aligned text group anchored toward the bottom-right. The 92px display headline spans roughly three fifths of the content width in two compressed lines; the 19px lead below it narrows to 700px, followed by a short standalone reinforcement and a right-aligned Primary button plus Secondary button. Content has 48px side gutters and 64px breathing room at the stage bottom. Within the first 900px the navigation, announcement, major artwork, entire headline, support, and actions are visible; the proof band begins below the fold.

**Transfer:** For a new product, create an original stream network to express connected work and keep the two-line promise in the lower-right rather than relying on a specific interface. Pricing, customer, and company openings use a centered display heading over the quieter Signal dash field, with a small category label and short centered support; their stage is 652px, or 496px for the denser pricing introduction.

**Avoid:** Do not substitute a centered SaaS headline above a laptop mockup, make the whole background a saturated gradient, or let detailed tracks compete with the headline counters.

**Text style:** `display` — Neue Montreal 500 · 92px/0.9 · tracking -0.03em

### Marked section lead

**Observed:** A tiny gradient square precedes a 12px uppercase label by 12px. A left-aligned 52px heading follows about 24px below, constrained to 800px; short gray Lead text continues below. Content starts after a 64px gap.

**Transfer:** Use one concise label and one consequential claim to introduce a chapter, not an ornamental label on every paragraph.

**Text style:** `heading` — Neue Montreal 400 · 52px/1.05 · tracking -0.02em

### Asymmetric model comparison

**Observed:** A Marked section lead introduces a 24px-gutter pair of Comparison panels in approximately 0.7:1.6 proportions. The smaller old-model list is muted; the wider positive model holds both a checkmarked list and a Geometric capability diagram. A soft violet–cyan atmospheric layer sits behind the wider panel.

**Transfer:** Show a meaningful difference between mechanisms or work patterns. Keep the stronger approach visually wider and more connected.

### Flow rail chapter

**Observed:** A 72px chapter title and short Lead introduce broad horizontal Prismatic signal streams. Below, compact product summaries form a rail with 19px titles, 16px descriptions, tiny mono links, and inactive items faded. A dashed baseline, gradient active segment, and square marker define navigation; 40px outlined arrows sit at left while a larger concluding statement sits at right.

**Transfer:** Use for a family of related capabilities or stages in a larger system, with the stream graphic explaining continuity rather than literal wiring.

**Text style:** `chapter` — Neue Montreal 500 · 72px/0.9 · tracking -0.03em

### Capability split

**Observed:** A centered chapter heading sits 96px above a Feature selector and Diagram backing in a 64px-gutter split. The numbered list occupies the smaller side; the diagram is around 692px by 460px at desktop. A narrower secondary variant uses 32px subheads and a terminal or command panel.

**Transfer:** Present distinct reasons to choose the product with one visual system that changes with selection; preserve a readable static state.

### Practical controls grid

**Observed:** A 40px section lead sits above a three-part composition: a left explanatory stack with a 32px subheading, Lead text, and secondary action, beside a two-column grid of compact capabilities. Each capability uses a short title, Body description, and bottom hairline rather than a surrounding card.

**Transfer:** Use for assurance, operational detail, or requirements without making the section feel like another feature-card wall.

### Human proof modules

**Observed:** A logo-and-proof band uses Proof wash and a 32px lead next to a horizontal logo rail. A larger proof moment places an abstract striped signal mark at left and a right-aligned 52px outcome statement with actions at right. Social quotes use small identity photos and thin outlined tall cards over a Signal dash field; one active card receives a luminous edge.

**Transfer:** Combine recognizable identity, an authentic outcome, and a short route to deeper proof. Give the statement equal visual stature to a product claim.

### Light bloom and utility landscape

**Observed:** Conversion light bloom holds a centered black 64px symbol, 40px two-line heading, and paired actions about 48px below it. The footer begins with a top hairline, then 112px top padding and four Footer link columns. Its 960px minimum height leaves a long calm interval before a 331px by 72px lower-left identity, Theme switch, language control, and small legal row. Prismatic signal streams fill the lower-right with pale gradients fading behind utility content.

**Transfer:** Retain both the luminous invitation and the expansive utility landscape. Use the new identity at a similarly substantial but not full-width scale; adapt link groups to the product's actual ecosystem.

**Text style:** `closing-heading` — Neue Montreal 500 · 40px/1.1 · tracking -0.01em

### Pricing and objections

**Only for:** pricing pages

**Observed:** A short centered display opening leads into three Plan cards with 24px gutters. A plain shared-benefits strip and usage table follow; the latter uses a Control gray header, mono numerical allowances, and hairline rows. A detailed feature comparison keeps tier headings and actions visible above long groups of approximately 65px rows. The ending objections section puts a 52px heading at left and an 800px FAQ row stack at right across a 64px gap.

**Transfer:** Separate quick choice, usage explanation, detailed comparison, and objections. Dense information stays flat and ruled rather than individually boxed.

### Proof directory

**Only for:** customer proof directories

**Observed:** Three 432px-wide quote columns combine low-contrast dash fields, black customer logos, 24px quotes, a speaker name, and uppercase mono role. A separate centered 92px directory headline and short Lead sit above a two-column grid of Case study entries.

**Transfer:** Make the opening proof emotional and the directory scannable by outcome; do not needlessly repeat the same claim in every card.

### Company editorial sequence

**Only for:** company and team pages

**Observed:** A 52px heading introduces the Candid portrait wall. A later centered 52px belief statement spans a broad text measure, followed by a horizontal dashed timeline with gradient square milestones and alternating mono dates above and below. Investor or partner logos sit in six compartments separated by vertical rules; supporter names form a flat ruled row, followed by a centered contact heading with three tiny mono links.

**Transfer:** Use this vocabulary for people, principles, milestones, and credible affiliations when those support the page's purpose.

## Page flow

**Storyline:** Promise → proof of relevance → explanation of the new model → capability and workflow evidence → trust and objections → luminous invitation → expansive utility landscape.

### Broad platform or marketing landing page

1. **Promise** — Asymmetric signal-stream opening with monumental right-aligned type.
2. **Social proof** — Low-contrast trust wash and logo rail.
3. **Problem and model** — Marked chapter lead and asymmetric old-versus-new comparison.
4. **Capability chapters** — Horizontal flow rail, practical controls grid, and numbered visual selector.
5. **Outcome proof** — Large editorial customer statement and social quote rail.
6. **Closing call** — Light bloom followed by the large utility footer.

**Transfer:** Adapt the chapter selection to the new product; keep the alternation of abstract system explanation and human proof.

### Focused technical product landing page

1. **Promise** — Centered category heading over a faint signal field, with start and documentation routes.
2. **Product demonstration** — Luminous pale terminal against a right-aligned benefit statement.
3. **Capability chapters** — Numbered selectors beside technical panels.
4. **Workflow explanation** — Alternating numbered steps along a fine dotted vertical spine.
5. **Practical proof** — Three flat capability summaries, compact SDK example, and thin gradient benchmark bars.
6. **Closing call** — Shared light bloom and utility landscape.

**Transfer:** Replace the terminal, steps, and benchmark content with genuine workflow evidence for the new product.

### Plan selection and detailed commercial evaluation

1. **Promise** — Short centered opening.
2. **Pricing** — Three aligned tiers with one luminous recommendation, followed by common benefits.
3. **Usage explanation** — Flat ruled allowance table and calculator callout.
4. **Detailed comparison** — Long feature table with persistent tier summaries and compact actions.
5. **Objection handling** — Split heading and plain accordion stack.
6. **Closing call** — Shared light bloom and utility footer.

**Transfer:** Support both rapid choice and careful evaluation without forcing visitors to read every row.

### Customer validation and story discovery

1. **Promise** — Centered heading over a dash field.
2. **Human proof** — Three logo-led quote columns with speaker details.
3. **Outcome proof** — Monumental directory heading and two-column ruled story entries.
4. **Closing call** — Shared luminous invitation and spacious footer.

**Transfer:** Lead with authentic voices, then let readers scan deeper stories by their outcomes.

### Company credibility and human introduction

1. **Introduction** — Centered concise heading and candid support line.
2. **People** — Six-column square portrait wall.
3. **Principle** — Broad centered belief statement.
4. **Credibility** — Dashed milestone timeline, partner logos, and named supporters.
5. **Contact** — Centered heading and compact direct contact links.
6. **Closing call** — Shared light bloom and utility footer.

**Transfer:** Use authentic people and milestones; preserve the flat editorial presentation rather than inventing lifestyle marketing panels.

## Writing

Direct, technically literate, and confident about concrete operational outcomes. Warmth comes from plain language and real engineers' experiences rather than cheerleading; company copy can be candid and occasionally irreverent.

**Do not copy:** Do not reuse Depot names, logos, proprietary artwork, customer identities or quotes, performance multipliers, prices, funding details, adoption counts, or claims. Source examples illustrate phrasing only; all new factual claims need their own basis.

- **Addressing the reader:** Address the reader as you or your when describing work and integration. Refer to the product by name for clear capability claims; use we sparingly for beliefs and company narrative.
- **Rhythm:** Short declarative headlines alternate with compact explanatory sentences. Most supporting groups contain one or two sentences; action labels are terse verbs, and technical lists use parallel phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name a broad category and the scale or outcome it is built to serve. | 5–9 words | “Software delivery built for machine scale” |
| Explanatory heading | Make a diagnosis in a plain, consequential sentence. | 8–15 words | “The bottleneck has shifted from writing code to everything after.” |
| Capability headline | Reduce a complex system to a compact contrast or progression. | 4–8 words | “One stack. From code to deploy.” |
| Support | Explain the practical fit and effort required rather than repeating a slogan. | 12–25 words | “Same command, same flags, use with your existing CI provider and dev workflows.” |
| Primary action | Verb plus immediate next step, with a specific low-friction qualifier when true. | 2–5 words | “START BUILDING FOR FREE”<br>“Read the docs” |
| Company introduction | Human commitment expressed with unusually candid language. | 10–18 words | “Meet the team that gives a shit about making software delivery exponentially faster.” |

**Words and phrasing to use:** built for; drop-in; reliable; same command; persistent; at scale; in minutes; through code; your existing tools

**Avoid:** revolutionary magic; unleash your potential; game-changing ecosystem; delightful journeys; limitless possibilities

**Rules:**

- Explain how an improvement happens, not only that it is faster.
- Use technical nouns when they help a reader evaluate integration or behavior.
- Put verified numerical outcomes beside the mechanism or proof that supports them.
- Keep sentence case for major headings; uppercase belongs to mono labels and controls.
- Use occasional bluntness only in human company language, not as a substitute for product clarity.

## Do's and Don'ts

### Do

- Keep the continuous cool canvas at #eaecf0 behind nearly all sections.
- Pair 92px/0.9 display type with 19px/1.35 support rather than enlarging every text role.
- Use 48px desktop gutters and 224px major section separation to preserve the open rhythm.
- Keep primary and secondary actions compact at 32px high with 6px corners.
- Let 1px #d4d6d9 rules define most grouped content without elevation.
- Make the active selector visually specific with black text and a thin cyan–violet rail segment.
- Carry the signal-stream device into a chapter or the footer as well as the opening.
- Finish with the 465px light bloom and a footer generous enough to hold both utilities and artwork.

### Don't

- Do not reinterpret the style as a near-black developer site; the dominant page surface is pale.
- Do not use pill-shaped primary buttons or oversized 48–56px conversion controls.
- Do not turn every feature into a rounded white card with a gray drop shadow.
- Do not set explanatory 52px headings in a heavy 700 weight.
- Do not put all body copy in mono; it is reserved for markings, controls, and technical fragments.
- Do not paint whole content bands in saturated cyan or violet; keep saturation concentrated in signals and light.
- Do not replace smooth offset tracks with rigid connector-box flowcharts.
- Do not give portraits circular masks or force the mixed natural photography into a uniform campaign treatment.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare 0.18s transitions for shadow, filter, transform, and background using cubic-bezier(0,0,0.2,1).
- Navigation color transitions use 0.2s cubic-bezier(0.4,0,0.2,1).
- Luminous demo and recommended-plan borders declare border-rotate 5s linear infinite.
- Carousel controls declare active scale 0.97 and visible focus outlines; some selectors declare 0.3s color or opacity transitions.

**Transfer:**

- Keep interaction feedback concentrated in chromatic edges and soft glow rather than large button movement.
- Use slow rotating chromatic frames only for the singled-out demonstration or recommended plan.

**Unknown:**

- Exact timing and implementation of the large signal artwork and dash-field movement are not established.

### Responsive

**Observed:**

- The container uses 16px base, 32px intermediate, and 48px desktop side padding in its class declarations.
- Team grids declare two columns at base, three at an intermediate size, and six at desktop; footer links declare two columns before the four-column desktop layout.
- Technical demonstration splits declare a single-column base layout; desktop navigation is hidden outside its desktop mode.

**Transfer:**

- On narrow layouts, preserve the stream artwork as an edge-faded background while letting the promise occupy the readable width.
- Stack split chapters and keep their active diagram paired with its explanation; reduce headline size to preserve the compressed line-height relationship.
- Keep the light bloom centered and simplify footer artwork to the unoccupied edge rather than letting it overlap controls.

**Unknown:**

- Exact breakpoint widths, smaller type sizes, and mobile navigation construction are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
