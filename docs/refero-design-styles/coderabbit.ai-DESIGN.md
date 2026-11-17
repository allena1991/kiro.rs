# CodeRabbit — instruments against chaos

## Overview

A dark, developer-minded style that makes complex software feel inspectable rather than magical. Near-black and mauve-gray surfaces carry white grotesk typography, mint technical labels and tiny orange signals. Dense interface demonstrations sit inside warm, solid frames, balanced by spacious introductions and restrained data drawings. It suits technical platforms with substantial workflows, measurable outcomes and detailed buying decisions.

### Essentials

- The promise reads like a correction to conventional wisdom: a left-aligned 64px/68px medium grotesk headline with -0.03em tracking, beside a smaller 20px/28px explanation and action rather than centered beneath it.
- The opening is an instrument rack, not a floating app window: 120px desktop side margins, a 64px split-intro gap and a wide, numbered four-part demonstration with one expanded panel and narrow neighboring previews.
- White is the conversion color: primary actions are 36px high, 4px-radius white rectangles with 14px side padding and a small right arrow; secondary controls are dark with 6px corners and faint outlines.
- Color behaves like a signal on dark equipment: almost the entire canvas is near-black or mauve-gray; mint #19d59e marks 12px uppercase mono labels and proof links, while orange #ff570a marks identity, selected rules and footer headings.
- Product evidence is framed as a physical specimen: dark interfaces occupy roughly five sevenths of a feature row, inset in muted brown #504343 or warm beige #d7ccc1 surrounds with 6px top corners; a narrow benefits rail remains outside the frame.
- Fine technical art and segmented edges are signature devices: include a delicate line-based system drawing and a 4px segmented multicolor edge under a major stage or conversion band. A simple node-and-path SVG is the minimum equivalent when no interactive model exists.
- The ending has a second scale of identity: a nearly full-content-width outlined wordmark fading into darkness, around 1200px × 172px, beneath compact orange-headed link columns and above a bordered newsletter rail.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Orange signal | `#ff570a` | `--color-orange` | text, accent | Identity accents, footer category labels and selected vertical markers; not the primary action fill. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Mint signal | `#19d59e` | `--color-mint` | text, link, accent | Uppercase chapter labels and outcome links. |
| Warm edge signal | `#ffa057` | `--color-peach` | accent | Small warm portions of the multicolor baseline. |
| Bright edge signal | `#46e1a5` | `--color-green-edge` | accent | Tiny lit portions of the multicolor baseline. |
| Blue edge signal | `#4d60c7` | `--color-blue` | accent | Tiny segments in the multicolor baseline. |
| Announcement green | `#062619` | `--color-deep-green` | background | Narrow announcement strip and small segments of the decorative edge. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, action, background | Headlines and primary buttons. |
| Black plum canvas | `#121014` | `--color-canvas` | background, text | Default page background and text on white actions. |
| Mauve charcoal | `#1a181d` | `--color-panel` | surface, background | Outcome cards, secondary controls, testimonials and closing bands. |
| Raised charcoal | `#232127` | `--color-raised` | surface, border | Inputs and subtle separator lines. |
| Frame edge | `#2a2830` | `--color-frame-border` | border | Outer group frames. |
| Control edge | `#322f37` | `--color-control-border` | border | Control and panel outlines; also used with 0.4 or 0.6 alpha for faint rules. |
| Warm brown frame | `#504343` | `--color-brown` | surface | Solid backing around dark product demonstrations. |
| Secondary text | `#b5b2b9` | `--color-muted` | text | Support paragraphs, descriptions and navigation. |
| Warm beige frame | `#d7ccc1` | `--color-beige` | surface | Alternating solid backing around dark product demonstrations. |
| Soft white | `#efedf0` | `--color-soft-white` | text, action | Secondary action text and primary-action hover fill. |

## Typography

- **Geist** — All marketing headings, prose, navigation and controls. Contemporary grotesk with compact forms; regular and medium weights dominate. Font stack: "Geist", "Geist Fallback", ui-sans-serif, system-ui, sans-serif.
- **hack** — Chapter labels, technical markers and comparison quantities. Utilitarian monospace that looks like an annotation on a technical instrument. Font stack: "hack", "hack Fallback", ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| quotation-mark | Geist | 500 | 96px | 0.55 | normal | Oversized opening quotation mark at 10% white; decorative rather than a headline. |
| display | Geist | 500 | 64px | 68px | -0.03em | Two-line opening promise. Also used as a single-line title on proof-led pages. |
| closing | Geist | 400 | 48px | 54px | -0.02em | Large conversational conversion line inside the closing band. |
| heading | Geist | 500 | 32px | 1.25 | -0.02em | Default capability and outcome headings. |
| stat | Geist | 400 | 32px | 1.25 | -0.02em | Outcome figures without oversized dashboard styling. |
| lead | Geist | 400 | 20px | 1.4 | normal | Section introductions and testimonial prose. |
| tight-lead | Geist | 400 | 20px | 1.4 | -0.05em | Opening support copy and compact question labels. |
| body | Geist | 400 | 16px | 1.5 | normal | Card descriptions and footer links. |
| compact-body | Geist | 400 | 16px | 1.35 | normal | Short benefits and dense descriptive text. |
| feature-label | Geist | 600 | 16px | 1.5 | 0px | Small benefits headings. |
| primary-action | Geist | 500 | 16px | 1.35 | normal | Primary button labels. |
| secondary-action | Geist | 600 | 16px | 1.35 | normal | Secondary button labels and short proof links. |
| navigation | Geist | 500 | 16px | 1 | normal | Top-level short navigation links. |
| footer-label | Geist | 600 | 16px | 1.5 | -0.02em | Orange footer column and signup headings. |
| eyebrow | hack | 400 | 12px | 1.5 | normal, uppercase | Mint category or numbered chapter label, 16px above the heading. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and dedicated proof pages | heading-expanded | Geist | 500 | 48px | 54px | -0.02em | Buying-page title, FAQ title and enlarged proof heading. |
| pricing pages | plan-title | Geist | 600 | 24px | 32px | 0px | Plan names in sticky card headers. |
| pricing pages | table-quantity | hack | 400 | 16px | 1.35 | normal | Centered comparison quantities and availability labels. |

**Notes:**

- The default marketing section heading is 32px, not 48px. Larger secondary-page headings are a deliberate page-type variant.
- Keep regular prose neutral in tracking; reserve the unusually tight -0.05em setting for the opening support line and FAQ questions.
- Display size alone does not determine emphasis: opening promises use medium weight, closing invitations use regular weight, and outcome numbers remain regular.

## Layout

**Density:** Airy introductions and section boundaries surround dense, compact demonstrations and comparison content.

### Spacing

| Value | Use |
| --- | --- |
| 4px | Inner gutters and inset around shared outcome or plan frames. |
| 8px | Small text groups and form control gaps. |
| 12px | Integration bento gutters. |
| 16px | Eyebrow-to-heading distance and testimonial grid gutters. |
| 24px | Heading-to-support spacing and table description insets. |
| 32px | Outcome and testimonial padding; spacing between benefits. |
| 36px | Gap between product stage and benefit rail. |
| 40px | Heading group to demonstration and outcome frame. |
| 64px | Split opening introduction gap. |
| 80px | Typical capability section vertical padding and major block separation. |
| 96px | FAQ band padding and proof-page opening offset. |
| 120px | Desktop page side padding and opening top padding. |

### Containers and grids

- **outer-container**: max width 1920px · side padding 120px. Centered outer shell; at a 1440px desktop width this leaves 1200px of usable content.
- **opening-split**: 2 columns · gap 64px. Left promise uses a 1.75fr track; right support uses 0.8fr with a 320px minimum.
- **feature-stage**: 2 columns · gap 36px. 5:2 split between media and benefits, with a minimum 240px benefits rail.
- **outcome-grid**: 4 columns · gap 4px. Equal cards in one fine outlined outer frame; about 295px wide each at desktop.
- **support-copy**: max width 768px. Limit section introductory paragraphs to a readable measure.
- **quote-grid** (only for dedicated proof pages): 2 columns · gap 16px. Equal testimonial columns; final testimonial may span the entire width.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | primary-buttons | 4px |
|  | group-frames-and-secondary-buttons | 6px |
|  | outcome-and-plan-cards | 3px |
| integration showcases | integration-bento | 10px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| product-window | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Dark interface windows lifted slightly from their solid warm backing. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #121014; color: #ffffff`

#### Charcoal panel · level 1

**Use:** Grouped proof, secondary actions and conversion bands.

**CSS:** `background: #1a181d; border: 1px solid #232127; border-radius: 6px`

**Observed:** A small tonal lift, not a glossy or frosted material.

**Transfer:** Use this as the restrained alternative to a bare canvas.

#### Inset group frame · level 1

**Use:** Shared frame enclosing tightly packed outcome or plan cards.

**CSS:** `border: 1px solid #2a2830; border-radius: 6px; padding: 4px`

**Observed:** The narrow outer inset and internal gutters make separate cards read as one instrument.

**Transfer:** Keep the common frame even when card content changes.

#### Warm media backing · level 1

**Use:** Frame for product demonstrations.

**CSS:** `background: #504343; border-radius: 6px 6px 0px 0px; overflow: hidden`

**Observed:** Alternates brown and beige backings; dark UI is inset on the top and sides, with the lower edge trimmed by a segmented color line.

**Transfer:** Use solid muted framing, never an atmospheric gradient behind the interface.

#### Integration panel · level 2

**Only for:** integration showcases

**Use:** Asymmetric bento examples.

**CSS:** `background: #1a181d; border: 1px solid #322f37; border-radius: 10px; padding: 20px; box-shadow: inset 0px 1px 0px rgba(239,237,240,0.05), 0px 20px 64px rgba(18,16,20,0.4)`

**Observed:** One wide demonstration is paired with three stacked small text cards.

**Transfer:** Reserve the more rounded treatment for an ancillary integration story.

## Components

### Navigation link

**Use:** Compact desktop navigation.

**CSS:** `display: flex; align-items: center; height: 36px; padding: 0px 8px; color: #b5b2b9; border-radius: 6px`

**Text style:** `navigation` — Geist 500 · 16px/1

**Observed:** A left identity mark, centered links with small disclosure chevrons where needed, then a secondary login and white conversion action; the header itself is 70px high.

**States:** Declared: hover white text over 5% white; focus-visible outline none and dark text; active white text.

**Transfer:** Keep the same quiet hierarchy and compact action scale.

### Primary button

**Use:** Primary conversion and short forward actions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 6px; height: 36px; padding: 0px 14px; background: #ffffff; color: #121014; border: 1px solid #ffffff; border-radius: 4px`

**Text style:** `primary-action` — Geist 500 · 16px/1.35

**Observed:** Label followed by a 16px right arrow; widths fit the label except full-width actions at the bottom of plan cards.

**States:** Declared: hover background and border soft white; focus-visible outline none with zero shadow; active scale 0.98.

**Transfer:** Preserve the short height even alongside large headlines.

### Secondary button

**Use:** Login, sample views and additional questions.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; gap: 6px; height: 36px; padding: 0px 14px; background: #1a181d; color: #efedf0; border: 1px solid #322f37; border-radius: 6px`

**Text style:** `secondary-action` — Geist 600 · 16px/1.35

**Observed:** May end with a northeast arrow rather than the primary action's straight arrow. Subscription version is 44px high.

**States:** Declared: hover darker 6% black fill and a lighter neutral border; focus-visible outline none with zero shadow; active repeats the hover treatment.

### Outcome card

**Use:** Quantified social proof.

**CSS:** `display: flex; flex-direction: column; padding: 32px; background: #1a181d; border-radius: 3px`

**Text style:** `stat` — Geist 400 · 32px/1.25 · tracking -0.02em

**Observed:** Monochrome client logo above a regular-weight figure, metric label, short contextual paragraph and mint case-study link pinned toward the bottom. Four equal cards sit in Inset group frame and are about 360px tall.

**Transfer:** Use a real metric and its denominator or time context, with the same restrained numeral scale.

### Newsletter input

**Use:** Footer email subscription.

**CSS:** `height: 44px; padding: 6px 12px; background: #232127; border: 1px solid #322f37; border-radius: 6px; color: #efedf0`

**Observed:** An email field about 345px wide sits beside the Subscribe variant of Secondary button, with an 8px gap. A category heading and small consent copy flank the form in a bordered rail.

**Transfer:** Use a visible accessible label and keep the form subordinate to the closing identity.

### Capability benefit

**Use:** Narrow explanatory rail beside a product stage.

**CSS:** `max-width: 352px; margin-bottom: 32px`

**Text style:** `feature-label` — Geist 600 · 16px/1.5 · tracking 0px

**Observed:** A short white semibold heading followed by muted compact body copy; selected supporting terms are underlined. This is plain text, not another card.

**Transfer:** Use three to five independently useful benefits without competing with the demonstration.

### Closing band

**Use:** Final conversion invitation.

**CSS:** `background: #1a181d; border: 1px solid #232127; border-radius: 6px; overflow: hidden`

**Text style:** `closing` — Geist 400 · 48px/54px · tracking -0.02em

**Observed:** A broad regular-weight line sits at the left, Primary button at the right, with roughly 58px total inner insets and a 4px segmented baseline. Overall band is about 175px high.

**Transfer:** Use one friction-reducing invitation, not an extra paragraph or checklist.

### Footer category

**Use:** Grouped site links.

**CSS:** `display: flex; flex-direction: column; gap: 8px; color: #ff570a`

**Text style:** `footer-label` — Geist 600 · 16px/1.5 · tracking -0.02em

**Observed:** Five columns across the content shell; links below use muted body text in 32px rows. Above the columns sit the identity mark, language control and small social glyphs.

**Transfer:** Scale the number of categories to the content while retaining orange headings and the monumental outlined identity below.

### Testimonial card

**Only for:** dedicated proof pages

**Use:** Long-form customer validation.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #1a181d; border: 1px solid #232127; border-radius: 6px; padding: 32px`

**Text style:** `lead` — Geist 400 · 20px/1.4

**Observed:** A low-contrast quotation mark introduces the prose; a small circular portrait, semibold name and regular role are aligned at the bottom. Typical two-column cards are 592px × 385px.

**Transfer:** Keep attributed prose readable and identities compact rather than adding oversized portraits.

### Plan card

**Only for:** pricing pages

**Use:** Equal-weight buying options.

**CSS:** `display: flex; flex-direction: column; padding: 32px; gap: 32px; background: #1a181d; border-radius: 3px`

**Text style:** `plan-title` — Geist 600 · 24px/32px · tracking 0px

**Observed:** A 64px-high sticky name bar, short description, 32px price, grouped feature lists with tiny green checks, and bottom-aligned white action. Four equal columns share Inset group frame; no oversized bright recommended card.

**Transfer:** Allow list lengths to vary while keeping titles and final actions aligned.

### FAQ row

**Only for:** pricing and buying-decision pages

**Use:** Objection handling.

**CSS:** `border-top: 1px solid rgba(50,47,55,0.4); padding: 24px 0px; display: flex; justify-content: space-between; gap: 20px`

**Text style:** `tight-lead` — Geist 400 · 20px/1.4 · tracking -0.05em

**Observed:** A tightly tracked question and tiny plus control occupy a 768px-wide list. Rows are about 77px high; the final row also has a bottom rule.

**Transfer:** Keep questions plain, direct and full-sentence; expanded answers should remain within the list measure.

## Imagery and graphics

### Framed interface specimens

**Use:** Primary visual evidence throughout capability sections.

**Observed:** Detailed dark application views show actual workflows: comments, queue cards, sidebars, code diffs and security charts. The warm backing is much less saturated than the tiny mint, red and yellow UI signals; the media dominates its row, with benefits outside to the right.

**Transfer:** Show a legible, representative workflow for the new product inside the same solid warm frame. If complete product media is unavailable, construct one convincing functional view with a sidebar, a clear work object and a few meaningful annotations, rather than abstract floating rectangles.

### Segmented signal baseline

**Use:** Signature lower edge on product stages and conversion bands.

**Observed:** A 4px stripe spans the frame: mostly long, subdued neutral stretches, interrupted by short green, blue, orange and peach segments, ending in a pale warm stretch.

**Transfer:** Carry this device onto a major visual and the closing invitation; it is a structural signature, not a progress bar.

**Build:** Use a 4px-high flex row clipped to the panel. Give most width to muted brown, beige and dark neutral spans. Insert short 7–30px mint, blue, orange and peach spans between longer 150–270px stretches. Keep hard boundaries, not a rainbow gradient.

### Converging system lines

**Use:** A technical interlude expressing complexity and coordination.

**Observed:** Many dim, thin colored paths enter from small outlined objects on the left, bend toward a single vertical junction, then run horizontally beneath a compact headline on the right. The drawing occupies a broad 1200px × 512px stage without a filled card.

**Transfer:** Map the new product's inputs into a common output; use a minimum set of fine paths and tiny outlined objects if a richer simulation is unavailable.

**Build:** Create an SVG viewBox of 1200 by 512. Arrange small 12–20px wireframe rectangles in a loose left cluster. Draw 1px cubic paths from varied heights into a junction around one third across, then continue as near-horizontal lines to the right. Use mint, orange and peach at low opacity, with dark fade masks at both ends; put the text above the outgoing paths.

### Inspectable node drawing

**Use:** Deep capability explanation inside a bordered interactive stage.

**Observed:** A roughly 300px left rail of text choices is divided from a large circular network by a faint rule. Hundreds of dark, hollow nodes and short links form a ball; a few larger white nodes and mint monospace annotations identify an active path. A thin orange vertical line marks the active rail item.

**Transfer:** Use a network, dependency map or process graph relevant to the new product, preserving the low-contrast field and tiny highlighted subset.

**Build:** Within a 1200px × 610px outlined panel, allocate one quarter to a label rail. In the remaining region, distribute hollow 3–6px-radius SVG circles inside a circular boundary; connect nearby nodes with 1px gray lines at 20–35% opacity. Highlight five to eight nodes with larger white rings and connected white paths, plus one mint annotation. Use a 2px orange rule beside the selected label.

### Outlined identity sculpture

**Use:** Required large-scale identity moment in the footer.

**Observed:** A heavy grotesk wordmark stretches across the 1200px content width in a shallow 172px image. Only its fine orange-brown outline is visible, fading vertically to the canvas; there is no solid letter fill.

**Transfer:** Set the new product's own name as a single oversized outlined word, fitting its width to the shell. For short names, increase letter width or use a wider cut rather than adding decorative symbols.

**Build:** Use an SVG text element fitted to a 1200 by 172 viewBox with a heavy Geist face, fill none and 1px orange stroke at restrained opacity. Apply a vertical mask from visible at the top to transparent at the bottom. Keep the letter bottoms clipped or faded and the background continuous with Canvas.

### Proof identities

**Only for:** proof-led pages and social-proof sections

**Use:** Customer logos and testimonial attribution.

**Observed:** Logos are monochrome soft white, either in a fine ruled rack or freely spaced across broad rows. Portraits are small circular color thumbnails, never the dominant image.

**Transfer:** Normalize optical logo size without making every logo equally wide; keep real portraits small and attribution-specific.

### Technical grid wash

**Only for:** pricing pages

**Use:** Low-contrast texture behind the buying-page introduction.

**Observed:** A fine square grid sits behind the heading and support text and fades outward into the dark canvas.

**Transfer:** Keep this diagram-paper effect local to a utilitarian buying introduction.

**Build:** Layer two perpendicular 1px repeating linear gradients on a 20px square grid, using the control-edge neutral at 24% opacity. Mask the layer with a broad radial fade so the grid disappears at the sides and lower edge.

### Icons

**Observed:** Marketing controls use small filled SVG arrows and chevrons, generally 16px. Feature checks are about 12px and mint; social glyphs are about 17px. Small line icons inside demonstrations use rounded caps and thin strokes.

**Transfer:** Use one restrained icon family, aligning 16px directional glyphs at the end of actions. Do not turn small technical indicators into large illustrated feature icons.

## Section recipes

How recurring sections are built.

### First screen: Split promise and instrument rack

**Observed:** A 41px dark-green announcement strip precedes a 70px navigation bar. After a substantial dark breathing space, a 1200px shell holds the two-column introduction with 120px top padding. The mint mono eyebrow precedes a two-line white 64px/68px medium promise spanning about two thirds of the shell; the right third holds tight 20px/28px support and Primary button. Below a broad pause, a four-part numbered interface rack spans the content width; one panel expands while narrow neighboring previews remain visible. Layers are Canvas, a subtly lighter full-width backing band, fine panel outlines, dark interface content, then tiny colored UI signals. Within the first 900px the entire promise, support and action are visible, along with the upper portion of the substantial interface rack; its lower content and trust rack fall below the fold.

**Transfer:** Replace the promise with a concise reversal of a category assumption. Stage a representative workflow as an expanded panel alongside narrow previews of related capabilities; a static but meaningful interface view is an acceptable minimum. Proof-led pages instead open with a single-line display title and logo field. Buying pages use a 48px title, short support and Technical grid wash before practical controls.

**Avoid:** Do not center the promise over a tiny floating dashboard, fill the background with a neon glow, or turn the four-part rack into four equally prominent marketing cards.

**Text style:** `display` — Geist 500 · 64px/68px · tracking -0.03em

### Capability chapter

**Observed:** Use eyebrow, heading and lead recipes in a left-aligned group with 16px then 24px gaps. Begin the feature-stage layout 40px below. Warm media backing carries the dominant interface, while Capability benefit items form a narrow right column. Sections use 80px vertical padding.

**Transfer:** Repeat the layout for genuinely different product benefits; alternate brown and beige backing without changing the dark canvas.

**Text style:** `heading` — Geist 500 · 32px/1.25 · tracking -0.02em

### Trust rack and compact proof

**Observed:** A fine outlined logo rack uses two rows of eight equal cells at desktop. Under it, restrained 32px statistics and a larger attributed quote share a divided proof panel.

**Transfer:** Combine recognized identities with one specific, attributed endorsement or quantitative trust measure; use the same engineered divisions instead of a decorative logo cloud.

### Context explorer

**Observed:** A left-aligned heading group introduces Inspectable node drawing in a 1200px outlined stage. The quarter-width text rail uses an orange selected marker, and the technical drawing remains the main object.

**Transfer:** Explain a deep differentiator with one inspectable model rather than adding another row of generic benefits.

### Outcome frame

**Observed:** A mint eyebrow and heading introduce four Outcome cards inside Inset group frame, 40px below. The default heading is 32px; dedicated proof pages enlarge it to 48px and place a small action at the right.

**Transfer:** Use independently meaningful results that have comparable explanatory depth rather than unrelated oversized numbers.

**Text style:** `heading` — Geist 500 · 32px/1.25 · tracking -0.02em

### Conversion and monumental footer

**Observed:** Closing band sits within the shell with 80px surrounding vertical space. The footer begins after another 80px pause and uses 72px top and 48px bottom padding. Footer category columns precede Outlined identity sculpture, then the newsletter rail and a final row of legal links and copyright. The buying-page variant omits the separate conversion band and retains the same complete footer.

**Transfer:** End the narrative with a single direct invitation when appropriate, then retain the large outlined identity and compact signup rail as the recognizable ending.

**Text style:** `closing` — Geist 400 · 48px/54px · tracking -0.02em

### Integration bento

**Only for:** integration showcases

**Observed:** A heading introduces a pairing of compact application identity tiles and a short explanation. Below, Integration panel forms a roughly 60:40 bento: a large UI demonstration left and three stacked short cards right, separated by 12px gutters.

**Transfer:** Use this variant for a secondary workflow or ecosystem story; preserve the asymmetry and keep the content concrete.

### Quote wall

**Only for:** dedicated proof pages

**Observed:** Testimonial card repeats in two equal columns with 16px gutters; a concluding quote spans the width. Low-contrast quotation marks sit above prose and portrait attributions sit near the bottom.

**Transfer:** Let quote length vary naturally while aligning identities within each row.

**Text style:** `lead` — Geist 400 · 20px/1.4

### Buying comparison

**Only for:** pricing pages

**Observed:** A compact annual/monthly control precedes four equal Plan cards inside Inset group frame. Horizontal on-demand product panels follow, then a detailed table with a wide description column and four approximately 169px availability columns. Alternating dark fills, 1px rules and small centered checks keep the matrix readable; category headers get local low-intensity colored dot textures.

**Transfer:** Separate commitment options, occasional purchases and detailed entitlements. Preserve equal plan weight and dense table typography instead of adding a dominant bright recommendation card.

### Questions band

**Only for:** pricing and buying-decision pages

**Observed:** A full-width Charcoal panel band uses 96px vertical padding. A 48px heading wraps in a narrow left column, while FAQ row fills the 768px right column. A secondary action sits beneath the questions.

**Transfer:** Use the question list as the closing decision aid; the buying page moves from this band directly to the footer.

**Text style:** `heading-expanded` — Geist 500 · 48px/54px · tracking -0.02em

## Page flow

**Storyline:** category correction → visible workflow → trust → capability evidence → measurable outcomes → decision or conversion → monumental identity and utility

### Introduce a technical platform and make its breadth credible

1. **promise** — Split opening promise and support, with an expanded multi-capability instrument rack.
2. **social proof** — Logo rack, compact statistics and attributed endorsement.
3. **problem framing** — Converging system-line illustration with a short contrast headline.
4. **capability chapters** — Numbered mint labels, framed interfaces, narrow benefits rails and a deeper node explorer.
5. **ecosystem extension** — Asymmetric integration bento.
6. **quantified proof** — Four tightly grouped outcome cards.
7. **closing call** — Broad conversion band, segmented baseline and full outlined-identity footer.

**Transfer:** Choose the chapters relevant to the new product while retaining the contrast between inspectable complexity and terse explanatory copy.

### Establish confidence through identities, results and customer voices

1. **promise** — Plain large title followed by a broad monochrome logo field.
2. **quantified proof** — Enlarged outcome heading, four result cards and small case-study action.
3. **social proof** — Two-column testimonial wall with a full-width final quote.
4. **closing call** — Low-friction invitation band and complete monumental footer.

**Transfer:** Use a simpler opening than the platform presentation; let third-party specificity supply the depth.

### Help buyers compare commitments and resolve practical objections

1. **orientation** — 48px title and short paragraph over a faint grid wash.
2. **pricing** — Billing selector and four equal, long-form plan cards.
3. **additional offers** — Horizontal product panels with descriptions, checks and white actions.
4. **detailed comparison** — Dense ruled matrix grouped into colored technical category headers.
5. **objection handling** — Split FAQ band.
6. **utility ending** — Full footer with outlined identity, newsletter rail and legal row, without an extra closing conversion band.

**Transfer:** Favor equal comparison and aligned buying actions over a promotional hero; preserve the full brand ending after the functional content.

## Writing

Confident and technically fluent, with a dry sense of urgency about complexity. Benefit claims are short and assertive; supporting paragraphs explain the mechanism rather than adding emotional superlatives.

**Do not copy:** Do not reuse CodeRabbit's name, rabbit identity, customer logos, quotations, security promotion, pricing, customer counts or performance claims. Use the new product's own verified identities and evidence. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak to teams through you and your; use we for capabilities and the product name for specific tools. Prefer direct verbs to impersonal platform language.
- **Rhythm:** Headlines are usually short sentence-case statements with a period. Contrast pairs and compact corrections supply rhythm; support is one or two concise sentences, and actions are short verb phrases.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Reject an assumed goal, then replace it with the more consequential one. | Two short sentences | “The future isn't writing code. It's reviewing it.” |
| Capability heading | Name the outcome or problem plainly, with one technical noun. | 3–7 words | “Prioritize your PR flood.”<br>“Code explainability for massive diffs.” |
| Support | Describe a specific workflow limitation, then the mechanism that changes it. | 1–2 sentences | “Git platforms make massive diffs confusing. Change Stack helps you understand a thousand-line diff in minutes.” |
| Outcome heading | Pair an upward benefit with a reduced burden. | Two parallel clauses | “Raise the quality bar. Lower the review burden.” |
| Primary action | A direct verb and a low-friction next step; the arrow does the extra persuasion. | 2–5 words | “Try it for free”<br>“Get in Touch” |
| Question | Ask the buyer's practical question without marketing language. | One sentence | “Can I switch between Essentials and Team?” |

**Words and phrasing to use:** context; understand; prioritize; review; risk; continuous; ship; chaos; before; across

**Avoid:** revolutionary; unleash your potential; delightful magic; supercharge everything; limitless possibilities

**Rules:**

- Anchor every broad promise to a mechanism in the adjacent paragraph or demonstration.
- Use contrast to sharpen meaning, not to create a slogan in every section.
- Keep technical terms where they reduce ambiguity; explain consequential outcomes in ordinary language.
- For proof, state what was measured and over what period or denominator.
- Write button labels as the immediate next action, not a metaphor.

## Do's and Don'ts

### Do

- Keep the desktop shell at 120px side padding with 1200px usable width at 1440px.
- Use 32px/40px medium type for ordinary capability headings and 48px regular type for the closing invitation.
- Set chapter labels in 12px/18px uppercase hack and mint, 16px before the heading.
- Make primary actions white, 36px high and 4px rounded, with a 16px arrow.
- Place the interface in the wide track of a 5:2 feature row, 36px away from the benefits.
- Inset four outcome cards in a 4px-gutter shared frame; keep their figures at 32px regular weight.
- Carry the segmented 4px edge onto a major product stage and conversion band.
- Keep the outlined footer identity broad and low-contrast, above the newsletter rail.

### Don't

- Do not use orange-filled marketing CTAs; orange is a marker and identity signal.
- Do not replace the warm brown and beige media frames with saturated gradient blobs.
- Do not give each proof card 24px gaps; the shared frame depends on a tight 4px gutter.
- Do not inflate outcome figures to the 64px display size; the logo and explanatory context share the emphasis.
- Do not render the giant footer name as solid white; the thin fading outline is the characteristic treatment.
- Do not use monospace for large headings or body paragraphs; reserve it for labels and technical quantities.
- Do not elevate every section into a rounded tile; most capability chapters sit directly on the dark canvas.
- Do not apply the 10px bento radius to the default 3px outcome or plan cards.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare 0.15s background, border, color and transform transitions with cubic-bezier(.19,1,.22,1), and an active scale of 0.98.
- Secondary actions declare 0.2s color transitions with cubic-bezier(.4,0,.2,1).
- The opening rack declares a 6s linear progress animation and exposes a pause control.
- Some entrances declare 0.5s ease-out fade-up; the technical security drawings include 7s cycles.

**Transfer:**

- Preserve the visible expanded-panel hierarchy during rotation and provide the same pause affordance.
- Use the declared compact button transitions rather than conspicuous bouncing or glow effects.

**Unknown:**

- Exact behavior of the changing headline, scroll-linked explorers and all motion sequences is not established.

### Responsive

**Observed:**

- Styles include major width thresholds at 640px, 768px, 1024px and 1280px, with additional component-specific thresholds.
- The proof grid declares two columns from a small-screen threshold and four at the widest tier; testimonials declare two columns from the medium tier.
- The detailed comparison table declares a 768px minimum width and is hidden below its medium layout variant.

**Transfer:**

- On narrow layouts, stack the split introduction and place its support immediately below the promise, retaining left alignment.
- Reduce the outcome grid to two then one columns while preserving the fine common frame.
- Preserve the product stage as a readable visual viewport rather than shrinking all interface text to marketing-body size; place benefits below.
- Fit the outlined identity to the content width and stack the newsletter rail while preserving its border.

**Unknown:**

- Exact mobile media-stage interaction, menu presentation, replacement comparison UI and responsive type sizes are unknown.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
