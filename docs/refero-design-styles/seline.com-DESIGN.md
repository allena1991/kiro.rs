# Seline — paper, sky and doodles

## Overview

A friendly software style that pairs matter-of-fact product explanations with a lightly handmade personality. Warm off-white, stone-gray text and small sky-blue accents surround crisp interface demonstrations, hand-drawn characters and tactile paper details. Regular-weight geometric sans headings and compact grotesk body text keep the experience practical rather than precious; spacious chapters contain surprisingly dense, useful demonstrations.

### Essentials

- A plain promise gets a blue highlighter, not a giant slogan: regular roobert at 52px/58px with -1.1px tracking, left aligned across two lines, with one short phrase on a 10% sky-blue wash.
- The opening sells with the actual tool: a 1024px-wide interface image begins below compact copy and paired actions, occupies the lower first screen, and continues below the fold; a small hand-drawn figure leans over its edge.
- Buttons look gently pressed out of the page: 40px-high, 8px-radius blue primary actions use a white top sheen, inset lower edge and small shadow; a stone-tinted secondary action sits beside them with a 16px gap.
- Color is a marking system on a mostly paper-and-white page: #fafaf9 canvas, #ffffff cards, #78716c body, #0c0a09 headings; #3ba6f1 is concentrated in actions, links, small icons and translucent text highlights, not full-width bands.
- Technical proof and handmade humanity must coexist: white 10px-radius cards with 24px padding and 16px gutters hold clipped interface fragments, while ink-line illustrations, pale pencil loops and paper-like elements soften the system. Without custom artwork, use original simple outlined figures and a few sketched objects rather than stock 3D.
- Proof reads like a passage someone marked for you: unboxed 16px/27px quotations highlight only a useful clause with 30% blue, then end in a 40px circular portrait and compact attribution.
- The closing invitation is a small illustrated object, not a giant color field: a white 1024px-wide card pairs a 32px/40px dark line and pale stone continuation with paired actions; a figure and thin rising lines occupy its right side. Follow it with an open, multi-column directory footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky blue | `#3ba6f1` | `--color-blue` | action, link, accent | Primary actions, text links, chapter icons and comparison-column edges. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Blue button edge | `#3398e1` | `--color-blue-edge` | border | Fine darker edge on primary buttons. |
| Highlighted headline ink | `#236796` | `--color-blue-ink` | text | Dark blue lettering inside the opening highlighter phrase. |
| Quote highlighter | `#c1e1f7` | `--color-blue-mark` | surface | Visible sky blue at 30% over paper behind selected proof clauses. |
| Headline wash | `#e7f2f8` | `--color-blue-wash` | surface | Visible sky blue at 10% over paper; brief highlighted phrases. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Near-black ink | `#0c0a09` | `--color-ink` | text | Headings and emphasized phrases. |
| Warm gray text | `#78716c` | `--color-body` | text | Default body copy and secondary action labels. |
| Secondary stone | `#78726d` | `--color-secondary` | text | Opening support and explanatory section text. |
| Muted stone | `#a8a29e` | `--color-muted` | text | Attribution metadata, social links and footer baseline. |
| Pale continuation | `#d6d3d1` | `--color-pale-ink` | text, border | De-emphasized closing headline continuation and neutral edge source color. |
| Card hairline | `#e8e7e5` | `--color-edge` | border | Visible fine edge on paper canvas; built from stone #d6d3d1 at 50% opacity. |
| Secondary action wash | `#edeceb` | `--color-secondary-fill` | surface | Visible 10% warm-gray action fill; source hue #78726d. |
| Soft stone | `#f5f5f4` | `--color-soft-surface` | surface | Interface backing, small utility labels and recessed controls. |
| Button lettering | `#f8fafc` | `--color-on-blue` | text | Near-white text over sky-blue actions. |
| Warm paper | `#fafaf9` | `--color-canvas` | background | Default page canvas. |
| White | `#ffffff` | `--color-card` | surface | Raised cards, interface framing and paper objects. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| comparison tables | Comparison wash | `#f2f7f9` | `--color-comparison-wash` | surface | Visible sky blue at 4% over paper, only inside the emphasized comparison column. |
| company story pages | Editorial stone | `#44403c` | `--color-prose-ink` | text | Slightly darker long-form company prose. |
| company story pages | Portrait panel stone | `#e7e5e4` | `--color-team-panel` | surface | Flat panel backing the portrait directory. |

## Typography

- **roobert** — Headings, pricing numerals and accordion questions. Rounded geometric sans with friendly proportions; regular headings feel substantial without heavy weights. If unavailable, use **DM Sans**. Use 400 for headings and 500 for questions; retain tight headline tracking. Font stack: "roobert", "DM Sans", sans-serif.
- **Inter** — Body copy, navigation, actions, captions and attributions. Compact, highly legible grotesk that makes dense explanations and interface-adjacent text feel usable. Font stack: "Inter", ui-sans-serif, system-ui, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | roobert | 400 | 52px | 58px | -0.0212em | Default product landing-page opening headline; highlighted words retain the same recipe. |
| heading | roobert | 400 | 32px | 1.25 | -0.025em | Major section headings and closing invitation. |
| card-heading | roobert | 400 | 20px | 1.2 | -0.005em | Feature card titles. |
| lead | Inter | 500 | 18px | 1.5 | 0.003em | Opening supporting copy. |
| body-lg | Inter | 400 | 16px | 27px | 0.003em | Section introductions and unboxed testimonial quotations. |
| question | roobert | 500 | 16px | 27px | normal | Accordion questions. |
| letter | Inter | 400 | 15px | 23px | 0.003em | Personal letter inset. |
| body | Inter | 400 | 14px | 23px | 0.004em | Default paragraphs, navigation and footer links. |
| action | Inter | 500 | 14px | 20px | 0.004em | Primary and secondary action labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing and company story pages | utility-title | roobert | 400 | 36px | 42px | -0.0222em | Centered secondary-page opening title. |
| pricing pages | plan-title | roobert | 400 | 30px | 32px | -0.005em | Plan and service card headings. |
| pricing pages | pricing-section | roobert | 400 | 24px | 32px | -0.006em | Compact question-section title. |
| company story pages | editorial | Inter | 400 | 15px | 1.6 | 0.003em | Long-form story paragraphs. |

**Notes:**

- Display headings tighten progressively: -1.1px at 52px and -0.8px at 32px. Do not make all headings semibold merely because their geometry looks strong.
- Body copy usually remains 14px/23px; use 16px/27px for human testimony and section introductions rather than enlarging every paragraph.
- The main headline's blue phrase is an inline highlight within a natural sentence, not a separate badge or eyebrow.

## Layout

**Density:** Airy chapter spacing around compact, information-rich cards; most of the breathing room belongs between sections rather than between lines.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Card heading to supporting text and footer link rows. |
| 12px | Small icon-title stacks and comparison-cell padding. |
| 16px | Primary grid gutters, paired action gap and section heading to support. |
| 24px | Card padding and opening headline/support/action separation. |
| 32px | Footer top padding and repeated proof-row spacing. |
| 40px | Desktop section side padding and testimonial column gap. |
| 48px | Story prose separation and letter top inset. |
| 64px | Secondary-page opening top padding. |
| 80px | Letter side inset on desktop. |
| 96px | Default major section vertical padding and footer baseline separation. |

### Containers and grids

- **marketing-container**: max width 1024px · side padding 40px. Centered shared alignment for navigation, product stage, chapters, closing card and footer; desktop margins are broad.
- **opening-copy**: max width 780px. Headline aligns to the container's left; supporting copy narrows to 680px and the action pair to 400px.
- **feature-grid**: 2 columns · gap 16px. Balanced large demonstration cards; mix with a three-column row where one card spans two columns.
- **small-feature-grid**: 3 columns · gap 16px. Short text-only supporting feature cards beneath larger demonstrations.
- **proof-grid**: 2 columns · gap 40px. Unboxed testimonials sit side by side; vertical row gap is 32px.
- **question-column**: max width 700px. Left-aligned accordion within the wider shared container, preserving space to the right.
- **letter-sheet**: max width 760px · side padding 80px. Centered paper insert with a 600px text measure.
- **footer-links**: 4 columns · gap 24px. Four directory columns alongside a separate wider brand column; the brand occupies two of an eight-column parent grid.
- **story-prose** (only for company story pages): max width 656px. Narrow centered editorial column under a 700px portrait directory.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | cards | 10px |
|  | buttons-and-main-media | 8px |
|  | text-highlights | 4px |
|  | portraits | 50% |
| comparison tables | comparison-column-caps | 40px |
| company story pages | portrait-panel | 6px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card | `0px 4px 16px 0px rgba(0, 0, 0, 0.05)` | White feature and closing cards. |
| main-product-stage | `0px 4px 80px 0px rgba(0, 0, 0, 0.15)` | Large opening interface image. |
| letter | `-6px 17px 26px -5px rgba(50, 50, 93, 0.15), -6px 8px 16px -8px rgba(0, 0, 0, 0.3)` | Asymmetric lifted-paper shadow on the personal note. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default full-page ground.

**CSS:** `background: #fafaf9; color: #78716c`

#### White card · level 1

**Use:** Demonstrations, small capability cards and final conversion panel.

**CSS:** `background: #ffffff; border: 1px solid rgba(214, 211, 209, 0.5); border-radius: 10px; padding: 24px; box-shadow: 0px 4px 16px 0px rgba(0, 0, 0, 0.05)`

**Observed:** Cards remain close to the canvas in brightness. Rich demonstration content sits below a small icon, title and explanatory copy.

**Transfer:** Let shadows reveal the edges gently; keep the visual hierarchy in content rather than surface contrast.

#### Product stage · level 1

**Use:** Hero interface presentation.

**CSS:** `background: #f5f5f4; border: 1px solid rgba(214, 211, 209, 0.3); border-radius: 8px; box-shadow: 0px 4px 80px 0px rgba(0, 0, 0, 0.15)`

**Observed:** A broad, straight-on desktop interface floats just above the page rather than inside a decorative browser mockup.

**Transfer:** Use a credible product view with enough detail to reward inspection.

#### Letter paper · level 1

**Use:** Personal founder or maker note.

**CSS:** `background: linear-gradient(#ffffff 0%, rgba(245, 245, 245, 0.5) 70%, rgba(238, 238, 238, 0.2) 100%); box-shadow: -6px 17px 26px -5px rgba(50, 50, 93, 0.15), -6px 8px 16px -8px rgba(0, 0, 0, 0.3)`

**Observed:** Square-edged paper with subtle tonal shifts between horizontal portions; a white sign-off area completes the sheet.

**Transfer:** Use the tactile sheet for a genuinely personal explanation, not another feature list.

#### Emphasized comparison column · level 0

**Only for:** comparison tables

**Use:** Single preferred option within a neutral comparison.

**CSS:** `background: rgba(59, 166, 241, 0.04); border-left: 2px solid #3ba6f1; border-right: 2px solid #3ba6f1; box-shadow: 0px 1px 0px 0px rgba(59, 166, 241, 0.1) inset`

**Observed:** The tint and side borders form one continuous vertical capsule with 40px curved top and bottom caps.

**Transfer:** Emphasize one option without coloring the whole table.

#### Portrait directory backing · level 0

**Only for:** company story pages

**Use:** Compact team directory.

**CSS:** `background: #e7e5e4; border-radius: 6px; padding: 8px`

**Observed:** Flat gray backing unifies painted portraits in two columns rather than separate raised cards.

**Transfer:** Use the panel to keep a human directory modest and editorial.

## Components

### Sticky navigation

**Use:** Persistent low-profile global wayfinding.

**CSS:** `position: sticky; top: 0px; z-index: 50; display: flex; align-items: center; justify-content: space-between; padding: 8px 16px; gap: 16px`

**Text style:** `body` — Inter 400 · 14px/23px · tracking 0.004em

**Observed:** A 52px strip holds a small identity mark at the left of the shared container and compact text links at right. A tiny overlapping portrait cluster accompanies the company link; a vertical rule separates resources from account actions. The header primary button is 36px high with 12px side padding.

**Transfer:** Keep the identity small; preserve the human portrait detail where a real team can stand behind the product.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 24px; border-radius: 8px; background-color: #3ba6f1; background-image: linear-gradient(rgba(255, 255, 255, 0.1), rgba(0, 0, 0, 0)); border: 1px solid #3398e1; color: #f8fafc; box-shadow: inset 0px 1px 0px rgba(255, 255, 255, 0.3), inset 0px -2px 1px rgba(10, 85, 138, 0.14), 0px 1px 2px rgba(0, 0, 0, 0.12)`

**Text style:** `action` — Inter 500 · 14px/20px · tracking 0.004em

**Observed:** The standard landing action shares a 400px two-button row with its secondary partner. A small translucent keyboard-hint tile follows the label on desktop. Pricing uses a full-width 36px-high version with 6px corners.

**States:** Declared: hover background-color hsl(205deg 87% 59% / .9); focus-visible outline-offset 2px and transparent 2px outline, preserving the inset shadows; active transform returns to scale 1.

### Secondary button

**Use:** Low-risk demonstration action beside the primary action.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 40px; padding: 0px 24px; border-radius: 8px; background: rgba(120, 114, 109, 0.1); color: #78716c`

**Text style:** `action` — Inter 500 · 14px/20px · tracking 0.004em

**Observed:** Same width as the paired primary action; a small pointer-style icon trails the label.

**States:** Declared: hover background-color hsl(25deg 5% 45% / .15), color hsl(222.2deg 47.4% 11.2%); focus-visible outline-offset 2px and transparent 2px outline.

### Feature card

**Use:** A capability explained through a small piece of working product.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; background: #ffffff; border: 1px solid rgba(214, 211, 209, 0.5); border-radius: 10px; padding: 24px; box-shadow: 0px 4px 16px 0px rgba(0, 0, 0, 0.05)`

**Text style:** `card-heading` — roobert 400 · 20px/1.2 · tracking -0.005em

**Observed:** Small blue icon precedes the title; a pale setup tag sits at upper right. Compact body text and sometimes an outward-arrow link introduce the demo. Larger diagrams are aligned low and clipped by the card; shorter supporting cards are text-only.

**Transfer:** Pick one specific capability and one intelligible interface fragment, not a full mini landing page inside each card.

### Inline link

**Use:** Documentation and supporting explanations inside prose.

**CSS:** `color: #3ba6f1; text-decoration: none`

**Text style:** `body` — Inter 400 · 14px/23px · tracking 0.004em

**Observed:** Links remain inline in the same font and size as surrounding text; standalone feature links use medium-weight action lettering and a small diagonal arrow.

**States:** Declared: hover opacity 0.8; text-decoration underline; color remains sky blue.

### Highlighted quote

**Use:** Emphasize the useful clause of unboxed social proof.

**CSS:** `background: rgba(59, 166, 241, 0.3); border-radius: 4px; padding: 0px 2px; color: #0c0a09`

**Text style:** `body-lg` — Inter 400 · 16px/27px · tracking 0.003em

**Observed:** Highlight follows the inline text wrapping instead of becoming a solid quote card. The rest of the quotation stays warm gray; gold stars precede many quotes and portrait attribution follows.

**Transfer:** Mark a short meaningful phrase rather than the whole testimonial.

### Question row

**Use:** Compact objection handling.

**CSS:** `display: flex; align-items: center; text-align: left; padding: 16px 0px; max-width: 700px; color: #0c0a09`

**Text style:** `question` — roobert 500 · 16px/27px

**Observed:** Unboxed 59px rows lead with a blue downward chevron, not a trailing plus. Answers use body text with inline blue links. The chevron rotates when the row opens.

### Footer directory

**Use:** Full site ending on every page type.

**CSS:** `display: grid; grid-template-columns: repeat(4, minmax(0px, 1fr)); gap: 24px`

**Text style:** `body` — Inter 400 · 14px/23px · tracking 0.004em

**Observed:** Four compact link columns sit beside a wider identity and short positioning line. Column headings are darker and medium weight; links stack with 8px gaps. A small green status dot is the only functional color exception. The address and copyright sit on a separate baseline after 96px of breathing room.

**Transfer:** Use real, useful navigation groupings without forcing every column to have equal link counts.

### Personal letter

**Use:** A human explanation of why the product exists.

**CSS:** `max-width: 760px; box-shadow: -6px 17px 26px -5px rgba(50, 50, 93, 0.15), -6px 8px 16px -8px rgba(0, 0, 0, 0.3)`

**Text style:** `letter` — Inter 400 · 15px/23px · tracking 0.003em

**Observed:** Centered square-edged sheet uses the Letter paper surface, 80px side insets and a bold salutation, short paragraphs, a personal sign-off, contact links and a small postscript.

**Transfer:** Replace the feature pitch with a sincere maker's note; keep the sheet restrained and readable.

## Imagery and graphics

### Interface demonstrations

**Use:** Main proof in the opening and capability cards.

**Observed:** The opening is a straight-on desktop dashboard, 1024px wide with white panels, small gray labels and vivid blue charts. Subsequent cards show enlarged fragments: layered profile panels, source rows, a short bar funnel, a filter menu and activity dots. Fragments are cropped at card edges and often slightly tilted, with faint shadows rather than heavy device frames.

**Transfer:** Show the new product's most useful workflow in a believable light interface. Without finished UI, create a restrained, legible diagram of a real input-to-output interaction; keep synthetic details secondary to the capability.

### Ink character vignettes

**Use:** Human accent at the main product stage, major action interlude and closing invitation.

**Observed:** An expressive glasses-wearing figure uses black ink hair and clothing, pale skin and stone-beige fabric with scratchy pencil shading. It leans over panels, carries ochre cardboard boxes or balances among thin rising colored curves. Scenes sit directly on the paper ground with no rectangular image background.

**Transfer:** Commission an original character or hands-and-tools scene with the same small scale, black silhouette, muted clothing and dry drawn texture. Minimum version: a simple original outline figure interacting with two or three product-relevant objects; retain the human presence and slight imperfection.

**Build:** Draw SVG paths with varied 1px–2px dark strokes, irregular silhouette edges, flat near-black clothing, muted beige secondary shapes and sparse diagonal hatch shading. Keep the opening figure around 130px wide, the interlude ensemble around 620px wide, and the closing art around 370px wide. Place transparent art over panel edges. Add three thin, loose upward paths in blue, lavender and ochre behind the closing figure, never through the text.

### Pale pencil atmosphere

**Use:** Sparse peripheral decoration around openings and illustrated action interludes.

**Observed:** Very faint warm-gray, textured looping strokes run off the outer edges. The action interlude adds scattered short blue and graphite speed lines angled toward the central scene; the center stays clean.

**Transfer:** Retain the almost-erased paper marks as a subtle handmade counterpoint to the precise cards.

**Build:** Use oversized open SVG cubic paths near the outer left and right edges, with 6px–10px warm-gray strokes at roughly 8% opacity. Add a mild fractal-noise displacement or broken short strokes to suggest dry pencil. For the illustrated interlude, distribute a few 1px blue and gray lines, 40px–100px long, around the perimeter; leave the central copy zone untouched.

### Loose paper stickers

**Use:** Compact ecosystem or compatibility proof.

**Observed:** Seven white rectangular partner-logo slips form an overlapping two-row pile, each rotated a few degrees, with fine edges, rounded corners and diffuse card shadows. The group is far smaller than the section's centered heading.

**Transfer:** Use actual compatibility marks when applicable; otherwise use short category names or tiny original tool symbols on the same scattered slips.

**Build:** Arrange white 100px–140px-wide slips in two offset flex rows with about 12px overlap, 8px corners, a faint neutral edge and 0px 4px 16px rgba(0,0,0,0.05) shadow. Alternate rotations around -12deg to 12deg without obscuring labels.

### Painted portraits and candid photos

**Only for:** company story pages

**Use:** A compact team introduction followed by a personal editorial story.

**Observed:** Four painterly head-and-shoulder portraits sit in 80px square light backings within a flat gray two-column directory. Below the prose, two overlapping rounded photos contrast warm amber desk work with a cool mountain-window view; their slight opposing rotations suggest casual prints.

**Transfer:** Use original team portraits with a consistent painted treatment and real, unpolished work or travel photos. Preserve the small editorial footprint rather than making a full-bleed lifestyle campaign.

### Icons

**Observed:** Small capability symbols are blue and usually 16px–20px; some are solid glyphs, others 2px round-stroked outlines. Supporting utility icons are gray at 12px–16px. Accordion chevrons use a 24px by 16px blue SVG box and sit before the label.

**Transfer:** Choose a compact, friendly icon family with round terminals and simple recognizable silhouettes. Mix solid feature symbols with light utility arrows deliberately, not with oversized multicolor pictograms.

## Section recipes

How recurring sections are built.

### First screen: Highlighted promise and product stage

**Observed:** A 52px sticky navigation sits above a paper canvas with faint outer pencil loops. The 1024px centered content column begins with 96px top padding; the two-line, left-aligned headline spans roughly three quarters of it. A short dark-blue phrase on a 10% blue wash is integrated into the first line. An 18px support block sits 24px below, then a 400px-wide Primary button and Secondary button pair after another 24px. Muted customer logos and a tiny review cue bridge to the main Product stage. The 1024px-wide interface begins around 532px down the page; a hand-drawn figure leans across its upper-right edge. Within the first 900px, the complete promise, support, actions, proof strip and upper interface are visible; the lower interface and four demo tabs fall below.

**Transfer:** Use the strongest plain-language promise, highlight its distinguishing phrase, and make an equally broad, readable product view the main object. If there is no finished UI, stage one concrete workflow diagram and an original ink vignette. Utility and company pages instead use a centered 36px title, 16px gap to compact support and 64px top padding, followed promptly by their functional or editorial content.

**Avoid:** Do not center the default landing headline, turn the demonstration into a small side thumbnail, or inflate the headline into a full-screen typographic poster.

**Text style:** `display` — roobert 400 · 52px/58px · tracking -0.0212em

### Heading and muted continuation

**Observed:** A 32px section heading shares a line with a pale continuation, followed by 16px/27px support in two unequal columns. The continuation is lighter, not smaller; a single concluding clause may use a blue highlight.

**Transfer:** Pair a short assertion with a conversational continuation, then move directly into useful explanation.

**Text style:** `heading` — roobert 400 · 32px/1.25 · tracking -0.025em

### Capability mosaic

**Observed:** Feature card groups use a 16px gutter: two large cards, or a two-column-spanning card beside stacked smaller ones, and three compact supporting cards. Blue icon, title, setup tag, paragraph and selective text link sit above low-aligned interface fragments. Unboxed testimonials interrupt the grid rather than forming a separate wall.

**Transfer:** Vary card size by explanatory need, retaining crisp alignment and compact text. Mix proof into the chapter where it answers the claim.

**Text style:** `card-heading` — roobert 400 · 20px/1.2 · tracking -0.005em

### Illustrated action interlude

**Observed:** A centered ink character and cardboard-object ensemble occupies a wide, open upper stage. A 32px heading sits below, followed by a centered 16px support line, paired actions and small reassurance text. Pale pencil strokes and sparse speed lines frame the outer margins.

**Transfer:** Use a small human scene to make a simple action feel tangible. Match the product's onboarding task with relevant physical props rather than reusing the same objects.

**Text style:** `heading` — roobert 400 · 32px/1.25 · tracking -0.025em

### Compatibility and maker note

**Observed:** A centered heading and support precede Loose paper stickers and a small highlighted testimonial. A separate Personal letter sits below with ample open canvas, 15px/23px text, personal salutation and contact routes.

**Transfer:** Use this pair to move from practical reassurance to the maker's motivation. The tactile sheet can appear wherever a human explanation strengthens trust.

### Open question list

**Observed:** A left-aligned heading introduces a 700px column of Question row components. There are no boxed accordion cards or strong rules; white space and the leading blue chevron separate rows. Landing sections use the 32px heading; pricing uses 24px.

**Transfer:** Keep the question list narrow and direct. Explain limits, setup and terms in ordinary language before asking for another commitment.

**Text style:** `question` — roobert 500 · 16px/27px

### Illustrated closing card and directory

**Observed:** A White card spans the shared container with 24px padding and a 600px text region. Its 32px heading breaks into dark promise and pale continuation. Body copy and the paired action row sit below. A 370px-wide Ink character vignette and rising line drawing occupy the right third and slightly cross the top edge. After the invitation, the Footer directory stays on the paper canvas with a wider brand column, four navigation columns and a low address/copyright baseline. Company and pricing pages go straight from their own content to this same footer, without another conversion card.

**Transfer:** Close a marketing story with a compact, illustrated invitation rather than a monumental banner. Use the shared open directory on every page type.

**Text style:** `heading` — roobert 400 · 32px/1.25 · tracking -0.025em

### Honest comparison capsule

**Only for:** comparison tables

**Observed:** Centered heading and support precede a wide comparison table. Feature labels align left while option cells center small status symbols and short captions. One column is a continuous blue-edged, barely tinted capsule; the other columns remain almost unpainted. Horizontal rules are faint and rows are around 63px tall.

**Transfer:** Compare real tradeoffs, including where another option fits better; reserve the strong outline for one option.

### Utility pricing composition

**Only for:** pricing pages

**Observed:** A centered utility title and compact support introduce two White cards: a larger foreground plan card and narrower service card offset down at the right. An ink figure leans over the main card. The main card combines billing toggle, usage quantity and price, recessed slider, compact two-column inclusions and full-width blue action. The service card ends in a white outlined action. A muted trust strip separates this from the question list.

**Transfer:** Use an asymmetrical pair only when the second offer is genuinely subordinate; keep the commercial controls and inclusions compact.

**Text style:** `plan-title` — roobert 400 · 30px/32px · tracking -0.005em

### Company editorial opening

**Only for:** company story pages

**Observed:** Centered 36px title and 14px introductory copy lead to the flat Portrait directory backing. A 656px prose measure starts 48px below. Painted portraits, a highlighted claim and overlapping candid photographs carry the human content; the story ends directly in the shared footer.

**Transfer:** Explain the people and product motivation with restrained editorial text and small real-life images, not a grid of abstract values.

**Text style:** `utility-title` — roobert 400 · 36px/42px · tracking -0.0222em

## Page flow

**Storyline:** Plain promise → tangible demonstration → contextual proof → deeper capabilities or terms → human reassurance → questions → appropriate invitation and open directory.

### Product marketing landing page

1. **Promise** — Highlighted two-line headline, concise support, paired actions and broad interface stage.
2. **Social proof** — Muted customer marks and highlighted, unboxed quotations.
3. **Capability chapters** — Alternating large interface cards and compact feature cards, with proof interspersed.
4. **Activation** — Centered illustrated scene explains a low-effort first step and repeats the actions.
5. **Evaluation** — Honest comparison table with one blue capsule column.
6. **Reassurance** — Compatibility sticker pile and personal paper letter.
7. **Objection handling** — Narrow unboxed accordion.
8. **Closing call** — Illustrated white invitation card followed by a full open directory and low legal baseline.

**Transfer:** Choose the capability chapters and proof needed for the new product; keep tangible demonstrations and handmade human accents throughout rather than duplicating a fixed section order.

### Company story

1. **Positioning** — Centered modest title, concise introduction and a highlighted statement.
2. **People** — Small painted portrait directory on a flat stone panel.
3. **Motivation** — Narrow editorial prose with overlapping candid photographs.
4. **Wayfinding** — Shared directory footer, then address and copyright; no separate final action card.

**Transfer:** Use the compact editorial variant for an authentic story; let portraits and prose do the work without adding marketing-card density.

### Pricing and buying confidence

1. **Commercial promise** — Centered title and trial reassurance.
2. **Offer** — Foreground main plan with controls and a smaller adjacent service card.
3. **Trust** — Small uppercase reassurance and muted customer marks.
4. **Objection handling** — Compact heading and unboxed questions about billing, limits and suitability.
5. **Wayfinding** — Shared directory footer and bottom legal baseline, without a repeated closing invitation.

**Transfer:** Prioritize usable offer controls and clear terms; retain the handmade edge detail without turning the page into a promotional mural.

## Writing

Conversational, practical and candid, with a developer-maker's warmth. Confidence comes from clear mechanics and useful tradeoffs, with occasional dry humor rather than corporate bravado.

**Do not copy:** Do not reuse the Seline name, logo, character artwork, customer identities, testimonials, pricing, company history or numerical claims. Examples illustrate cadence only; all product facts and proof must be specific and verified for the new product.

- **Addressing the reader:** Speak directly to you and your workflow. Use we and us for the makers, and the product name for functional capabilities.
- **Rhythm:** Short concrete titles lead into one or two useful sentences. Longer personal paragraphs are reserved for the letter and company story; contractions and occasional fragments keep them human.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the category or familiar alternative, then mark the practical differentiator within the sentence. | 6–12 words | “The simple & actionable Google Analytics alternative” |
| Capability title | Specific feature or action in plain noun-and-verb language. | 2–6 words | “Filter every report”<br>“Monitor traffic from AI tools” |
| Activation heading | A small action immediately followed by a useful result and time horizon. | 8–13 words | “Paste one script. See your first visitor in minutes.” |
| Primary action | Direct verb with a transparent commitment level. | 3–7 words | “Start free trial”<br>“Start your free 7-day trial” |
| Tradeoff heading | Admit that the choice depends on fit. | 6–10 words | “Where [Brand] loses, and where it wins.” |
| Company title | Three short, concrete descriptors with no inflated mission statement. | 3–5 words | “Independent, small, simple” |
| Trial reassurance | State timing and payment requirements in two blunt sentences. | 8–15 words | “Sign up for free 7-day trial. No credit card required.” |

**Words and phrasing to use:** simple; your; one; in minutes; no setup required; see; built; fast; plain; we

**Avoid:** revolutionary; unlock limitless potential; synergy; world-class ecosystem; game-changing; seamless digital transformation

**Rules:**

- Tie each feature to something the reader can see or do; describe the mechanism before adding adjectives.
- Use negation to remove real friction, not to make broad unverifiable superiority claims.
- Keep technical words when they help a buyer understand setup or capability, and explain the practical result beside them.
- Allow a modest joke or personal greeting in the human sections; keep pricing and answer copy literal.
- Use testimonials as ordinary speech, highlighting the useful clause rather than rewriting it into a slogan.

## Do's and Don'ts

### Do

- Keep the default display at 52px/58px, weight 400, with -1.1px tracking.
- Align the default opening copy with the left edge of the 1024px product stage.
- Use 24px card padding and 16px gutters to keep interface-rich sections organized.
- Keep the primary and secondary landing actions at equal 192px widths within a 400px pair.
- Use blue at 10% for the opening phrase and 30% for marked testimonial clauses.
- Include original ink-line humanity and nearly erased peripheral pencil marks alongside precise product proof.
- Give the personal letter a 760px maximum width and a 600px desktop text measure.
- Carry the same open four-column link directory through every page type.

### Don't

- Do not replace the near-white canvas with a dark theme or saturated blue section background.
- Do not use capsule-shaped primary actions; the default action radius is 8px.
- Do not apply the 80px-blur hero shadow to ordinary cards; their shadow is only 16px blur at 5% black.
- Do not use heavy 700-weight headings to imitate the rounded display face's visual presence.
- Do not enlarge every paragraph to 18px; that size is reserved for opening support.
- Do not box testimonials in dark or brightly colored tiles; the highlighted inline clause is the visual accent.
- Do not turn the single continuous comparison capsule into separate blue cards for every row.
- Do not spread the painted team directory or candid photo collage into ordinary product chapters; they belong to the company-story variant.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 0.15s cubic-bezier(0.4, 0, 0.2, 1).
- Accordion question rows declare all-property transitions at 0.15s cubic-bezier(0.4, 0, 0.2, 1); their chevrons rotate for the open state.
- Status and live indicators declare 1s ease-out pulsation and 2s cubic-bezier(0.4, 0, 0.6, 1) pulse animations.

**Transfer:**

- Keep interaction feedback subtle and local to the small controls; live data indicators can supply the sense of activity without moving entire chapters.

**Unknown:**

- The precise playback behavior of decorative figures and on-scroll entry sequences is not specified.

### Responsive

**Observed:**

- Declared width breakpoints are 640px, 768px, 1024px and 1400px.
- The desktop navigation is hidden below 768px.
- The opening action group declares a single column below 640px and two columns above it; mobile gap is 8px and desktop gap is 16px.
- Feature grids declare one column below 768px, with multi-column layouts above it. The portrait directory declares one column below 640px and two above it.
- Letter side padding changes from 24px to 80px at 640px. Footer link groups declare two columns below 640px and four above it.

**Transfer:**

- Preserve the headline-plus-highlight relationship when wrapping, stack actions before shrinking labels, and let the product demonstration remain the dominant image.
- Keep peripheral pencil art outside narrow text columns and move overlapping human vignettes away from interactive controls.

**Unknown:**

- Mobile navigation construction and actual narrow-screen rendering are unspecified; do not infer a particular menu animation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
