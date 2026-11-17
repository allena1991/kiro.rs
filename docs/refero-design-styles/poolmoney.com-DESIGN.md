# Pool — painted worlds, practical tools

## Overview

Warm paper and deep petrol frame a friendly, matter-of-fact product story. Light grotesk headlines and tiny spaced monospace controls balance everyday photography with painterly turquoise-and-green product stages. The feeling is communal but carefully engineered, with sparse text, large demonstrations and a surprisingly monumental dark ending. It suits approachable tools that need both human warmth and operational trust.

### Essentials

- A light, conversational headline sits above a much wider product world: 62px Söhne at weight 300, line height 1 and -0.03em tracking; text aligns to the inner column while the 1280px demonstration extends beyond it.
- Controls read like small machine markings rather than sales badges: 12px medium monospace capitals, 0.1em tracking, 48px-high deep-petrol pill actions with 24px side padding.
- Color lives inside scenes, not across the entire interface: warm #f9f6f1 dominates the light content, #001f22 anchors an inset trust panel and the full-width ending, and vivid turquoise, leafy green and a single lemon connector belong to illustrations.
- A painterly setting makes the product tangible: stage a crisp interface in an 8px white frame with 40px outer and 32px inner radii, backed by textured foliage and luminous sky; use layered SVG landscape shapes if bespoke artwork is unavailable.
- Everyday evidence travels sideways: 264×236px white photo cards with 24px corners, 16px intervals and softly fading edges form a continuous strip; show real applications or outcomes rather than generic logos.
- The ending is a whisper at monumental scale: a full-width petrol footer closes with a single-line 182.3px, weight-500 statement, -0.03em tracking and white at 3% opacity, deliberately overflowing both edges and clipping its lower edge.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action petrol | `#003439` | `--color-primary` | action, surface | Primary action pills and small security icon disc. |
| Deep petrol | `#001f22` | `--color-petrol` | background, surface | Full-width footer and inset trust band; the dark counterweight to the paper canvas. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Submerged lettering | `#082629` | `--color-ghost` | text | Monumental footer statement; white at 3% over petrol. |
| Sage hairline | `#3a5457` | `--color-dark-rule` | border | Footer divider; sage at 30% over petrol. |
| Muted sage on petrol | `#60787a` | `--color-footer-muted` | text, link | Footer links and fine print; sage #c0d0d1 at 50% over petrol. |
| Near-black green | `#071313` | `--color-ink` | text, link | Primary headings, paragraphs and light-surface controls. |
| Warm graphite | `#666463` | `--color-muted-ink` | text | Secondary copy on warm paper; rgba(65,63,63,0.8) produces this visible tone. |
| Silver on petrol | `#808f91` | `--color-dark-caption` | text | Small supporting monospace note in the dark trust panel; white at 50% over petrol. |
| Clear sage | `#c0d0d1` | `--color-sage` | link | Footer link hover color. |
| Sand rule | `#eae2d7` | `--color-rule` | border | Fine horizontal separators in question and opportunity rows. |
| Soft sand tray | `#f0ede8` | `--color-subtle-sand` | surface | The low-contrast tray beneath the main demonstration; rgba(65,63,63,0.05) over warm paper. |
| Warm paper | `#f9f6f1` | `--color-canvas` | background, surface | Default light page canvas and secondary action fill. |
| Clean white | `#ffffff` | `--color-white` | surface, text, border | Photo cards, product-stage frame and reversed text. |

## Typography

- **Söhne** — All prose, headlines and photo-card captions. A clean contemporary grotesk with a particularly light, open display cut and compact everyday text. If unavailable, use **Inter**. Use 300 for display and 400 for prose; preserve negative display tracking. Font stack: "Söhne", "Inter", system-ui, sans-serif.
- **Söhne Mono** — Action labels, navigation, footer links and technical captions. Compact utilitarian monospace; widely tracked in controls and tightly tracked in explanatory notes. If unavailable, use **IBM Plex Mono**. Use 500 for controls and 400 for notes. Font stack: "Söhne Mono", "IBM Plex Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| closing-monument | Söhne | 500 | 182.3px | 1 | -0.03em | Oversized, nearly submerged single-line statement at the bottom of the footer. |
| display | Söhne | 300 | 62px | 1 | -0.03em | Opening headline and centered conversion statement. |
| heading | Söhne | 400 | 32px | 1.2 | -0.02em | Feature chapters, question-section heading and editorial section headings. |
| body | Söhne | 400 | 18px | 1.4 | normal | Introductory support, feature explanations, question summaries and answers. |
| card-caption | Söhne | 400 | 14px | 18px | normal | Names and compact quantities beneath application photographs. |
| control | Söhne Mono | 500 | 12px | 1.2 | 0.1em, uppercase | Buttons, navigation, demonstration tabs and footer links. |
| technical-note | Söhne Mono | 400 | 12px | 1.4 | -0.02em | Supporting assurance note within the dark panel. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| editorial company and recruiting content | editorial-emphasis | Söhne | 500 | 18px | 1.4 | normal | Lead phrases within bulleted prose; not an additional heading level. |

**Notes:**

- The hierarchy changes weight as well as scale: display is 300, ordinary headings and prose are 400, and small control labels are 500.
- Large text tightens to -0.03em; headings use -0.02em. Body copy stays untracked while uppercase controls spread to 0.1em.
- Keep the closing line single-line and width-led: fit a short original statement slightly wider than its viewport, rather than wrapping it into a conventional headline.

## Layout

**Density:** Airy at section scale, compact inside controls and miniature application cards.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Spacing between demonstration tabs, conversion actions and photo-card image/caption. |
| 12px | Caption side inset and expanded-answer top margin. |
| 16px | Photo-card strip intervals and heading-to-copy spacing in the dark panel. |
| 20px | Question-row vertical padding and footer-list row gaps. |
| 24px | Headline-to-support gap, default card-grid gap and button side padding. |
| 32px | Navigation link gaps, header vertical padding and stage-to-heading-pair separation. |
| 40px | Opening support-to-action gap and editorial chapter separation. |
| 48px | Feature introduction-to-illustration gap. |
| 64px | Opening headline section top padding below navigation. |
| 80px | Opening demonstration top breathing room and footer divider margins. |
| 96px | Default feature and question-section vertical padding. |
| 104px | Desktop inner-container side padding and dark-panel inner vertical padding. |
| 120px | Headline/support column separation and major conversion-section vertical padding. |

### Containers and grids

- **outer-stage**: max width 1280px · side padding 0px. Wide centered media stage; at a 1440px viewport its edges sit 80px from the sides.
- **inner-content**: max width 1280px · side padding 104px. Desktop text and navigation shell, producing 1072px of usable width aligned inside the wider stage.
- **heading-pair**: 2 columns · gap 120px. Equal 476px desktop columns within the inner shell: heading left and explanation right.
- **feature-board**: 2 columns · gap 24px. Equal 524px desktop halves: one large product object opposite a two-by-two linked application grid.
- **editorial-column** (only for editorial company and recruiting content): max width 768px · side padding 24px. Centered reading column with 720px usable prose width.
- **opportunity-list** (only for recruiting and directory pages): max width 768px. Centered list wider than the editorial text, with title and right-aligned metadata.

## Corner radius

| Element | Radius |
| --- | --- |
| action-pills | 9999px (pill) |
| stage-frame | 40px |
| stage-interior-and-trust-band | 32px |
| photo-cards | 24px |
| feature-tiles | 16px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| feature-inset | `inset 0px 0px 0px 1px rgba(0,0,0,0.1)` | Subtle edge definition for the large illustrated object tile; avoid raised-card elevation. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f9f6f1; color: #071313`

#### Demonstration tray · level 1

**Use:** Groups the main stage with a narrow supporting caption below.

**CSS:** `background: rgba(65,63,63,0.05); border-radius: 40px; overflow: hidden`

**Observed:** The faint tray remains visible beneath the white-framed art rather than acting as a shadow.

**Transfer:** Keep any necessary qualification attached to its demonstration rather than floating elsewhere.

#### White stage frame · level 2

**Use:** Large product demonstration.

**CSS:** `background: #ffffff; padding: 8px; border-radius: 40px; overflow: hidden`

**Observed:** An inner 32px-radius image combines a painted landscape, tabs and an oversized crisp interface.

**Transfer:** Use the same nested-radius construction around an original product or workflow scene.

#### Petrol band · level 1

**Use:** Inset assurance or trust chapter.

**CSS:** `background: #001f22; color: #ffffff; border-radius: 32px; overflow: hidden`

**Observed:** At desktop the band is 1328px wide and 598px tall, set in paper margins rather than running edge to edge.

**Transfer:** Use a single focused reassurance message paired with a low-contrast diagram.

#### Feature tile · level 1

**Use:** Small connected application or outcome tiles.

**CSS:** `background: #f9f6f1; border: 1px solid rgba(65,63,63,0.15); border-radius: 16px; padding: 32px 16px`

**Observed:** Centered photo, compact name and quantity; a tiny recessed node occupies one upper corner.

**Transfer:** Show concrete destinations or outputs linked to the primary object.

#### Footer ocean · level 0

**Use:** Full-width ending.

**CSS:** `background: #001f22; overflow-x: clip`

**Observed:** This is a full section with substantial empty space, subdued navigation, a fine rule and the closing monument.

**Transfer:** Preserve the expansive dark ending even on text-led pages.

## Components

### Primary button

**Use:** Main conversion in navigation, opening and centered conversion call.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; height: 48px; padding: 0px 24px; border-radius: 9999px; background: #003439; color: #ffffff`

**Text style:** `control` — Söhne Mono 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** Text-only pill; width follows the label. The same action recurs without a trailing arrow.

**States:** Declared: hover opacity 0.9; focus-visible not specified.

### Navigation link

**Use:** Small secondary navigation beside the primary action.

**CSS:** `color: #071313; text-decoration: none`

**Text style:** `control` — Söhne Mono 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** A small wordmark sits left; a short group of text links and the Primary button sits right with 32px gaps. The header is 112px tall.

**States:** Declared: hover opacity 0.7; focus-visible not specified.

### Secondary button

**Use:** Low-emphasis alternative beside a conversion action.

**CSS:** `display: inline-flex; align-items: center; padding: 12px 24px; border-radius: 9999px; background: #f9f6f1; color: #071313`

**Text style:** `control` — Söhne Mono 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** A paper-colored pill without an outline; it is smaller than the primary action and vertically centered alongside it.

**States:** Declared: hover opacity 0.9; focus-visible not specified.

### Demonstration tab

**Use:** Switch between short functional product views.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 160px; height: 44px; padding: 0px 24px; border: 1px solid transparent; border-radius: 9999px; color: #ffffff; background-image: linear-gradient(rgba(0,0,0,0.3),rgba(0,0,0,0.3)),linear-gradient(rgba(0,0,0,0.15),rgba(0,0,0,0) 50%); backdrop-filter: blur(14px)`

**Text style:** `control` — Söhne Mono 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** A horizontal group floats inside the painted scene above the interface. The selected pill uses white at 90% with dark text and a matching white edge; inactive pills remain translucent.

**States:** Declared: hover dark overlay increases from 0.3 to 0.4; focus-visible solid 2px white outline with 2px offset.

### Photo application card

**Use:** Human-scale proof in the moving application strip.

**CSS:** `width: 264px; height: 236px; flex-shrink: 0; background: #ffffff; border-radius: 24px; padding: 4px 4px 12px 4px; margin-right: 16px`

**Text style:** `card-caption` — Söhne 400 · 14px/18px

**Observed:** A 256×176px cover photograph sits above two compact text lines. Overlapping 24px circular avatars align to the right of the caption; images have 20px top and 8px bottom corners.

**Transfer:** Use actual settings or outcomes for the new product, with small people or participant indicators where relevant.

### Question row

**Use:** Objection handling without heavy accordion boxes.

**CSS:** `padding: 20px 0px; border-bottom: 1px solid #eae2d7`

**Text style:** `body` — Söhne 400 · 18px/1.4

**Observed:** A native disclosure row places its question left and a small plus right. Expanded copy uses muted ink and a 12px top gap. The last row drops its bottom border.

### Footer link

**Use:** Secondary and policy navigation in the dark ending.

**CSS:** `color: rgba(192,208,209,0.5); text-decoration: none`

**Text style:** `control` — Söhne Mono 500 · 12px/1.2 · tracking 0.1em · uppercase

**Observed:** Two narrow columns sit opposite a reversed wordmark; each has 20px row gaps, and the columns have 114px separation on desktop.

**States:** Declared: hover color #c0d0d1; focus-visible not specified.

### Opportunity row

**Only for:** recruiting and directory pages

**Use:** Available roles or entries with compact location metadata.

**CSS:** `display: flex; align-items: center; justify-content: space-between; min-height: 80px; column-gap: 12px; border-bottom: 1px solid #eae2d7; transition-property: padding, background-color; transition-duration: 0.5s; transition-timing-function: cubic-bezier(0, 0, .2, 1)`

**Text style:** `body` — Söhne 400 · 18px/1.4

**Observed:** Rows are 89px tall at desktop. The title is left; uppercase monospace location and a thin right arrow are grouped on the right. The whole row is the link.

**States:** Declared: hover background-color #f4eee5; focus-visible not specified.

## Imagery and graphics

### Painted product world

**Use:** The dominant opening demonstration and related feature backdrops.

**Observed:** A sunlit, visibly brush-textured landscape puts dense leafy greens at the left edge, turquoise sky or water across the center and pale cream clouds at the right. A crisp, white product interface fills most of the foreground, extending below the stage's clipped lower edge. Tabs remain legible over the landscape.

**Transfer:** Place the new product's real interface or one meaningful workflow in front of a similarly light, tactile landscape. A simplified original interface with one clear interaction is the minimum acceptable foreground.

**Build:** Create a wide SVG landscape with irregular overlapping leaf clusters concentrated along the left third, a turquoise field behind, and cream cloud polygons drifting right. Apply feTurbulence through a subtle displacement and low-opacity grain layer to avoid a smooth mesh appearance. Inside a 32px clipped panel, overlay a transparent-to-black gradient reaching 20% darkness near the lower half, then position the crisp interface with roughly 96px side insets and room above for the tab strip.

### Everyday photographic proof

**Use:** Photo application cards and small linked outcome tiles.

**Observed:** Candid classrooms, friends, sports, coastlines, books and domestic rituals; natural light and varied color, never a uniform corporate portrait system. Wide cover images dominate strip cards, while small square images are centered in linked tiles.

**Transfer:** Use believable environments in which the new tool matters. Preserve ordinary, lived-in texture and a mixture of places and people rather than matching every image to one brand hue.

### Linked object board

**Use:** An explanatory feature illustration relating one product object to several destinations.

**Observed:** A dark petrol physical card floats flat and frontal over a heavily blurred turquoise, olive and cream background. A luminous lemon curve leaves its caption and arcs into a neighboring two-by-two grid. Recessed circular nodes give the board a lightly physical quality.

**Transfer:** Replace the card with an original output, device, document or central workflow object. Keep one large object, several small destinations and one unmistakable connection.

**Build:** Split a 1072px board into two 524px halves with a 24px gap. Blur enlarged landscape shapes behind the primary object inside a 16px-radius tile. Draw one SVG cubic Bézier curve in luminous pale lemon, about 4px wide, with rounded ends; let it cross the gutter and terminate at a recessed corner node. Use a faint duplicate stroke for a soft halo rather than a broad neon glow.

### Protected flow diagram

**Use:** Right half of the dark assurance band.

**Observed:** Muted translucent transaction pills with small photographic avatars drift around a vertical hairline. A 32px lock disc sits on the line; readable amounts become scrambled characters across it. Contrast remains below the white explanatory text.

**Transfer:** Represent a meaningful assurance mechanism for the new product: visible input on one side and protected, validated or simplified output on the other.

**Build:** Place several short rounded pills with white at low opacity on petrol. Add tiny circular portraits or original input thumbnails, two-line text, and reduced opacity toward the outer edges. Draw a 310px vertical divider as adjacent dark and white-at-12% hairlines, centered behind a 32px petrol disc with a 16px white lock outline. Replace text progressively with monospace symbols on the far side.

### Editorial identity panel

**Only for:** company and recruiting pages

**Use:** Wide visual bridge from opening promise to long-form prose.

**Observed:** A 976×512px rounded landscape panel uses the same turquoise, cream and leafy palette, but heavily blurred. A white identity mark sits at the upper left, with a simple page-purpose label toward the bottom.

**Transfer:** Use an original wordmark and a plain page-purpose label over the same blurred landscape vocabulary rather than adding a new illustration style.

**Build:** Blur a landscape layer within a rounded rectangle, then add the identity and label as sharp white SVG or live text above it. Keep foreground lettering out of the blur filter.

### Icons

**Observed:** Small 16×16px outline icons use 2px round-capped strokes in ink or white. Plus signs mark disclosures, arrows mark linked opportunities, and a lock occupies a small circular disc.

**Transfer:** Choose simple outline symbols with the same stroke and scale; reserve avatars and photography for human context rather than replacing them with pictograms.

## Section recipes

How recurring sections are built.

### First screen: Promise above a painted stage

**Observed:** Paper canvas supports a 112px header with a compact left wordmark and right-aligned Navigation links plus Primary button. Below it, the inner text column starts after 64px of top space: a light 62px headline spans about two thirds of the usable content width, followed after 24px by a two-line 18px support paragraph no wider than 576px, then a Primary button after 40px. An 80px breath separates the action from the 1280px-wide White stage frame. From back to front the stage contains painted landscape, a subtle dark overlay, Demonstration tabs, and a crisp white interface. Within the first 900px the complete headline, support and action are visible along with the tabs and upper portion of the product object; its lower portion and the explanatory heading pair continue below the fold.

**Transfer:** Use the product's clearest practical promise, one short support thought and one action. Without a finished interface, build a polished original workflow panel against the Painted product world; retain the scale and the below-fold continuation. Editorial company or recruiting openings omit the support paragraph, allow the same display recipe to wrap to two lines, and replace the interface stage with the Editorial identity panel.

**Avoid:** Do not turn this into a centered headline with floating mini-cards, a full-bleed dark hero or a small illustration squeezed beside the copy.

**Text style:** `display` — Söhne 300 · 62px/1 · tracking -0.03em

### Heading and explanation pair

**Observed:** The inner-content shell divides into two equal columns separated by 120px. A 32px heading sits left and 18px explanation right, aligned at their top edges; an illustration or strip follows below with 48px or more breathing room.

**Transfer:** Pair one compact capability name with a plain explanation of what changes for the reader. Let the following media carry the detailed proof.

**Text style:** `heading` — Söhne 400 · 32px/1.2 · tracking -0.02em

### Photographic application strip

**Observed:** Photo application cards move horizontally through the wide outer-stage shell. Cards stay compact and fixed-width, with soft 160px-wide paper-to-transparent masks at both ends. A fine dotted divider separates this chapter from the next.

**Transfer:** Use a varied set of real applications or outcomes, then let the horizontal motion suggest breadth without writing a long list.

### Connected feature board

**Observed:** A Heading and explanation pair introduces the Feature-board layout. The Linked object board fills the left half, and four Feature tiles occupy the right half in a two-by-two arrangement with 24px gaps. One curved connector crosses the composition.

**Transfer:** Explain a one-to-many relationship spatially. Keep the large object recognizable and the satellite tiles simple enough to read at a glance.

### Inset assurance chapter

**Observed:** The Petrol band is inset 56px from the viewport sides with 120px outer vertical padding. Inside, a 454px text column pairs a white 32px heading and 18px paragraph with the Protected flow diagram on the right. A small Technical-note sits low in the text column, with substantial space above it.

**Transfer:** Use a concrete reassurance mechanism, not a generic list of security badges. Keep the supporting diagram deliberately subdued.

**Text style:** `heading` — Söhne 400 · 32px/1.2 · tracking -0.02em

### Centered conversion pause

**Observed:** A centered 768px shell has 120px vertical padding. A 62px light statement wraps into a short, balanced shape; support follows after 24px and a centered pair of Primary button and Secondary button after another 24px.

**Transfer:** Restate the emotional or practical contrast in fewer words than the opening; keep this block uncluttered by illustration.

**Text style:** `display` — Söhne 300 · 62px/1 · tracking -0.03em

### Question split

**Observed:** Within the inner-content shell, a 32px heading occupies the left column and a vertical stack of Question rows occupies the right. The section uses 96px vertical padding and the same 120px column separation as feature introductions.

**Transfer:** Answer adoption objections in the right column; let the left heading remain a simple invitation rather than repeating each question.

### Submerged monumental ending

**Observed:** Footer ocean starts with 140px top padding. A reversed identity mark occupies the left half of the inner-content shell; Footer links form two narrow columns on the right. A 1px sage-at-30% rule follows with 80px margins. Fine-print paragraphs occupy at most 768px beneath it. After another broad empty interval, the Closing-monument runs wider than the viewport, remains single-line, and is clipped at the bottom. The total ending is about 1010px tall at desktop.

**Transfer:** Finish every page with this dark, spacious field and a short original communal or aspirational statement. Adapt the links and necessary disclosures, but retain the nearly invisible oversized lettering.

**Text style:** `closing-monument` — Söhne 500 · 182.3px/1 · tracking -0.03em

### Editorial narrative and opportunities

**Only for:** company and recruiting pages

**Observed:** A narrow editorial-column carries 32px headings, 18px prose, 16px paragraph gaps and roughly 40px chapter breaks. Lists indent 24px and begin selected phrases at weight 500. Underlined resource links stay in the text flow. A wider 768px Opportunity list closes the light content, with a 24px gap below its heading and 80px section padding.

**Transfer:** Use the longer prose format for mission, operating principles or a considered argument, then close with relevant next-step entries rather than copying a product feature grid.

**Text style:** `body` — Söhne 400 · 18px/1.4

## Page flow

**Storyline:** practical promise → visual explanation → concrete applications or deeper narrative → reassurance or next steps → expansive dark brand ending

### Product marketing and conversion

1. **Promise** — Light left-aligned headline, short support and repeated primary action.
2. **Product demonstration** — Large painted interface stage with functional tabs and a heading/explanation pair below.
3. **Application proof** — Moving photographic cards show varied real-world settings.
4. **Capability explanation** — A connected object board translates a one-to-many relationship into a physical diagram.
5. **Reassurance** — Inset petrol panel pairs a concise message with a protected-flow visualization.
6. **Conversion** — Centered large statement and a compact pair of actions.
7. **Objection handling** — Split heading and disclosure rows.
8. **Brand close** — Full-width dark footer with subdued navigation and clipped monumental lettering.

**Transfer:** Use this as a narrative vocabulary, not a fixed section count: demonstrate the product before asking the reader to absorb details, and use photographic applications and a dark ending to balance technical explanation.

### Company narrative and recruiting

1. **Mission promise** — The same light display type introduces an ambitious building statement and direct action.
2. **Identity bridge** — A blurred landscape identity panel connects the opening to prose.
3. **Context and credibility** — Narrow editorial paragraphs explain the problem, team and working principles.
4. **Practical detail** — Bullets use medium-weight lead phrases for benefits and operating information.
5. **Further reading** — Simple underlined resource links stay within the editorial column.
6. **Next steps** — A wider list of opportunities pairs titles with monospace metadata and arrows.
7. **Brand close** — The same dark footer and oversized submerged statement finish the page.

**Transfer:** Keep the shared opening and ending vocabulary while using a genuinely readable editorial middle for content that needs explanation.

## Writing

Practical, warm and direct. Confidence comes from naming what the tool does and explaining its mechanics, not from grand technological superlatives; occasional conversational wit keeps longer prose human.

**Do not copy:** Do not reuse Pool names, logo, artwork, slogan, customer identities, monetary figures, financial protections, partner claims, benefits or quoted press headlines. Replace every factual and regulatory claim with verified information for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the team and the product name for concrete operations. Actions can use first-person ownership when it makes the outcome feel personal.
- **Rhythm:** Short sentence-case headlines, often three to eight words. Support is one or two plain sentences; feature copy strings together a few simple actions. Longer editorial passages admit qualifications and occasional dry humor.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Frame the product as the appropriate tool for a familiar job rather than listing features. | About five to nine words. | “The right account for the job.” |
| Supporting line | Name the starting action, then a short list of things the reader can make their own. | One or two short sentences. | “Create a [Brand]. Add agents, cards, members and payments to make it yours.” |
| Feature headline | Use a direct verb or concrete capability noun phrase. | Two to eight words. | “Collect money”<br>“One debit card for all your Pools” |
| Primary action | Verb plus owned outcome, or a direct invitation to a relevant destination. | Two to four words. | “Create My [Brand]”<br>“View open roles” |
| Conversion statement | Contrast the familiar solitary approach with a better shared outcome. | A short balanced pair of clauses. | “Bank alone, [Brand] together.” |
| Editorial detail | Acknowledge a real-world constraint before naming practical specifics. | One conversational sentence followed by detail. | “As a seed-stage company, our biggest perk is potential. But you can’t pay rent with potential, so we also offer these benefits:” |

**Words and phrasing to use:** create; add; make it yours; together; simple; sharing; clear concrete verbs; specific operational nouns

**Avoid:** revolutionary; game-changing; unleash; frictionless everything; vague promises of transformation; forced financial puns

**Rules:**

- Pair each benefit with a recognizable operation or outcome.
- Prefer plain, human explanations to technical prestige language.
- Use sentence case in prose and headings; reserve capitals for visual control labels.
- Make qualifications readable and specific without allowing them to become the leading sales message.

## Do's and Don'ts

### Do

- Keep the main display at 62px/1 and weight 300, with -0.03em tracking.
- Align text to the 1072px inner content area while letting the main stage extend to 1280px.
- Keep buttons at 48px high with 24px side padding and fully rounded ends.
- Use 32px/1.2 regular headings opposite 18px/1.4 explanations.
- Give the main stage its 8px white frame and nested 40px/32px corners.
- Use a 16px interval between the 264px-wide photographic cards.
- Keep the footer statement nearly submerged at white 3% opacity, not normal heading contrast.
- Separate ordinary feature chapters with 96px vertical padding and retain the 120px conversion pause.

### Don't

- Do not substitute a bold 700-weight hero for the light 300-weight display.
- Do not uppercase body copy to match the monospace controls; uppercase is a small-label treatment.
- Do not spread bright turquoise or lemon across navigation and ordinary text; their home is the illustrated scene.
- Do not add heavy floating shadows to every card; use fine edges and nested surfaces.
- Do not turn the photographic strip into oversized testimonial quotation cards; its evidence is compact and image-led.
- Do not give each question a separate filled, rounded container; use sand hairlines and 20px vertical padding.
- Do not make footer navigation bright white by default; use the muted sage treatment.
- Do not carry the narrow editorial prose layout into the main product demonstration; it needs the wider stage.

## Motion and responsive

### Motion

**Observed:**

- The photographic strip declares a 60s linear infinite marquee animation.
- Demonstration panel-in and copy-in animations are named; their timing is not specified here.
- Opportunity rows declare padding and background-color transitions over 0.5s with cubic-bezier(0, 0, .2, 1).
- Primary and secondary actions declare 0.9 hover opacity; navigation links declare 0.7.

**Transfer:**

- Keep the application strip a slow continuous drift rather than a rapid carousel.
- Use discrete functional views in the main demonstration; the media and explanatory copy should describe the same selected function.

**Unknown:**

- Exact demonstration entrance durations and keyframe geometry.
- Whether or how the strip pauses for interaction.

### Responsive

**Observed:**

- Desktop composition uses wide media outside narrower text columns.
- Layout declarations include smaller-screen 24px side padding, single-column text layouts, horizontally overflowing tabs and a 398/223 stage aspect ratio; desktop stage ratio is 1349/736.

**Transfer:**

- On narrow screens stack heading before explanation, preserving their typographic distinction.
- Let the tab group scroll horizontally instead of shrinking 12px labels.
- Keep the painted backdrop and white interface together as one coherent scaled scene.
- Fit the closing single line to viewport width while retaining clipped edges; do not turn it into a paragraph.

**Unknown:**

- Exact breakpoint thresholds and full mobile navigation behavior.
- Mobile type scaling and opportunity-row metadata wrapping.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
