# Obscura — pixel skies, human conviction

## Overview

A friendly retro-computing world makes serious technical promises feel approachable. Pale blue skies, white floating panels, charcoal pixel lettering and hot orange highlights give it the optimism of an early platform game, while a clean geometric sans keeps the explanations practical. Product interfaces, simplified diagrams and candid photography share a spacious, low-density canvas. It suits tools whose engineering deserves explanation without an enterprise-sales tone.

### Essentials

- Pixel headlines carry a two-tone argument: Jersey 10 at 96px/0.7, weight 500 and -0.025em tracking opens the page; charcoal setup gives way to an orange payoff. Section headings use 60px/0.8 with the same tracking.
- The opening is a sky rather than a dashboard wall: a centered 768px maximum text stage floats beneath a white 72px navigation bar, with a 32px announcement capsule, sparse stepped clouds and a real product window entering at the bottom of the first 900px.
- Actions are small tactile rectangles, not arcade lettering: orange buttons use Manrope, 48px height, 8px corners and 32px horizontal padding for the hero; compact actions use 36px height and 6px corners, with fine inset light and layered downward shadows.
- Color lives in punctuation and the illustrated world: #dceefe dominates the long body, #ffffff carries panels, and #ff5e24 marks payoff phrases, links, icons and actions rather than whole content bands. A brown #6c3200 ending with green pixel turf is the deliberate full-width exception.
- An original pixel-world motif must recur: stepped white clouds behind content, a small product-related sprite interacting with a panel, and a pixel-ground ending. Use crisp SVG rectangles on an integer grid; when no character fits the product, invent a simple pixel tool or object instead.
- Proof floats in rounded white containers: 16px card corners, 12px accordion corners, 16px grid gaps and soft three-layer shadows contrast with the hard-edged art. Technical explanation can expand to a 1280px white panel with a 1px orange outline and 32px corners.
- Human conviction breaks the diagram rhythm: conversational 16px/24px prose can sit beside an unfiltered 584×438px photograph with 24px corners, a 24px hard offset shadow and a small centered caption. Pair technical certainty with an identifiable human voice rather than stock-business gloss.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Pixel earth | `#6c3200` | `--color-earth` | background | Dark warm footer ground beneath a pixelated turf edge. |
| Sky blue | `#dceefe` | `--color-canvas` | background | Default continuous marketing canvas behind text, clouds and floating panels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5e24` | `--color-orange` | accent, action, link, border, text | Headline payoff, primary buttons, selected boundaries, inline links and explanatory icons. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Sky hairline | `#cddeed` | `--color-edge` | border | Visible charcoal-at-8% edge over the blue canvas; use rgba(35,38,41,0.08) so it adapts over white. |
| Cloud glass | `#e3f1fe` | `--color-glass` | surface | White at 20% over the sky, used for comparison enclosures. |
| Charcoal | `#232629` | `--color-ink` | text | Default headline and strong body text. |
| Soft graphite | `#5c6066` | `--color-secondary` | text, link | Supporting paragraphs, navigation and secondary actions. |
| Cool gray | `#989ea4` | `--color-muted` | text | Eyebrows, low-priority labels and quiet metadata. |
| Chalk | `#f6f8f7` | `--color-soft-white` | background, text | Thin status band and reversed footer copy. |
| Milky sky | `#f8fcff` | `--color-announcement` | surface | White at 80% over sky for the translucent announcement capsule. |
| Panel white | `#ffffff` | `--color-white` | surface, text | Navigation and raised panels; reversed button text; bright cloud edges. |

### Semantic

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Disconnected red | `#f4352f` | `--color-status-red` | accent | Small connection-state dot; reserve for actual product status. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| platform availability grids | Peach availability wash | `#ffefe9` | `--color-availability` | surface | Orange at 10% over white for compact availability badges. |

## Typography

- **Jersey 10** — Hero, section headings, closing promise and human-note heading. Hard-edged, densely constructed pixel display lettering with broad angular forms; never the body font. Font stack: "Jersey 10", monospace.
- **Manrope Variable** — Explanations, navigation, buttons, card labels, captions and price numerals. Clean geometric sans with friendly round counters and a broad weight range. Font stack: "Manrope Variable", system-ui, -apple-system, "Segoe UI", "Helvetica Neue", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Jersey 10 | 500 | 96px | 0.7 | -0.025em | Centered opening promise, split into charcoal setup and orange payoff. |
| closing-display | Jersey 10 | 500 | 72px | 0.85 | -0.025em | Closing call; also the headline size for a split pricing opening. |
| heading | Jersey 10 | 500 | 60px | 0.8 | -0.025em | Section headline and orange inline or second-line payoff. |
| heading-prelude | Jersey 10 | 500 | 48px | 1 | -0.03125em | Short introductory line above a larger assertion. |
| note-heading | Jersey 10 | 400 | 36px | 1.111 | normal | Conversational title inside a personal letter card. |
| support | Manrope Variable | 500 | 16px | 1.5 | normal | Hero and section support lines in soft graphite. |
| body | Manrope Variable | 400 | 16px | 1.5 | normal | Longer, personal prose. |
| label | Manrope Variable | 700 | 16px | 1.5 | normal | Muted section eyebrows, card claims and accordion questions; sentence case. |
| button | Manrope Variable | 600 | 16px | 1.5 | normal | Hero and closing primary action text. |
| compact | Manrope Variable | 500 | 14px | 1.43 | normal | Card descriptions, small explanatory paragraphs and footer quotation. |
| navigation | Manrope Variable | 600 | 14px | 1.43 | normal | Navigation controls, compact actions and footer links. |
| caption | Manrope Variable | 400 | 14px | 1.43 | normal | Centered documentary photograph caption. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Manrope Variable | 700 | 36px | 1.111 | normal | One clear price, with a smaller muted billing interval. |
| platform availability grids | availability | Manrope Variable | 600 | 11px | 1.43 | normal | Short status inside a peach pill. |

**Notes:**

- Keep the pixel display and geometric sans sharply separated by role. Do not make the button or explanatory prose pixelated.
- Display tracking is -0.025em at 60px, 72px and 96px; the 48px prelude keeps the section heading's -1.5px spacing.
- The tight line boxes make two-line headings into solid graphic blocks. Keep normal mixed-case spelling rather than adding uppercase tracking.
- Use selective bold spans in support copy and orange spans in headings; inline links, not entire paragraphs, receive underlines.

## Layout

**Density:** Airy between chapters, compact inside proof cards and controls. The repeating sky remains visible around every group.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing and tight card stacks. |
| 16px | Default card-grid gap, accordion row gap and horizontal card inset. |
| 24px | Card vertical padding and comparison-panel inset. |
| 32px | Two-column proof gap and hero-button horizontal padding. |
| 40px | Hero support-to-action spacing. |
| 48px | Section heading-to-content spacing, announcement-to-headline gap and photo-to-caption spacing. |
| 64px | Desktop section side padding and assertion-to-card-grid gap. |
| 96px | Default major-section top and bottom padding; split pricing column gap. |
| 112px | Footer top padding allows the ground artwork to resolve before text begins. |
| 144px | Opening text stage's separation from the navigation. |

### Containers and grids

- **wide content**: max width 1280px · side padding 64px. Centered main container; at 1440px the content edges land 80px from the viewport.
- **navigation inner**: max width 1216px · side padding 64px. Slightly inset navigation content, with brand and links left and account/conversion controls right.
- **opening stage**: max width 768px · side padding 16px. Centered headline and action cluster; no adjacent hero illustration competing for its width.
- **section lead**: max width 896px. Broad centered statements; support paragraphs narrow to 576px or 672px.
- **comparison grid**: max width 1024px · 2 columns · gap 32px. Equal tall translucent comparison panels.
- **benefit grid**: max width 1280px · 3 columns · gap 16px. Three short equal-width white cards.
- **questions column**: max width 672px · gap 16px. Centered accordion stack beneath a centered section lead.
- **human split**: max width 1280px · 2 columns · gap 32px. Personal letter on the left, documentary photo on the right, vertically centered.
- **pricing split** (only for pricing pages): max width 1152px · 2 columns · gap 96px. Left-aligned promise beside a single purchase card.
- **availability grid** (only for platform availability grids): max width 896px · 3 columns · gap 16px. Two compact rows of equal platform tiles.

## Corner radius

| Element | Radius |
| --- | --- |
| primary hero action | 8px |
| compact actions | 6px |
| accordion and small tiles | 12px |
| cards and product window | 16px |
| comparison and photograph | 24px |
| explanation stage | 32px |
| announcement and status pills | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| floating panel | `0px 49px 30px 0px rgba(0,0,0,0.01), 0px 22px 22px 0px rgba(0,0,0,0.03), 0px 5px 12px 0px rgba(0,0,0,0.03)` | White cards, navigation and accordion rows. |
| product window | `0px 25px 50px -12px rgba(0,0,0,0.25)` | Large application window below the opening. |
| photo offset | `24px 24px 0px 0px rgba(0,0,0,0.07)` | Hard-edged offset backing behind the candid photograph. |

### Surfaces

#### Sky canvas · level 0

**Use:** Continuous light background for the ordinary marketing page.

**CSS:** `background: #dceefe; color: #232629`

**Observed:** Cloud art floats behind sections without alternating solid-color chapter bands.

**Transfer:** Keep generous exposed blue between content groups.

#### Floating white card · level 1

**Use:** Benefits, personal letter, purchase card and question rows.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 49px 30px 0px rgba(0,0,0,0.01), 0px 22px 22px 0px rgba(0,0,0,0.03), 0px 5px 12px 0px rgba(0,0,0,0.03)`

**Observed:** Bright opaque planes with low-contrast soft elevation, not heavy dark borders.

**Transfer:** Let the shape and shadow separate content from the sky.

#### Comparison glass · level 1

**Use:** Two alternatives in an explanatory comparison.

**CSS:** `background: rgba(255,255,255,0.2); border: 1px solid rgba(35,38,41,0.08); border-radius: 24px; backdrop-filter: blur(12px); padding: 24px`

**Observed:** White detail cards sit within the translucent enclosure; the preferred side uses an orange outline.

**Transfer:** Compare a familiar problem and a concrete improved mechanism, rather than generic feature checklists.

#### Explanation stage · level 1

**Use:** Wide process diagram with a centered section lead.

**CSS:** `background: #ffffff; border: 1px solid #ff5e24; border-radius: 32px; padding: 128px 16px 16px; box-shadow: 0px 49px 30px 0px rgba(0,0,0,0.01), 0px 22px 22px 0px rgba(0,0,0,0.03), 0px 5px 12px 0px rgba(0,0,0,0.03)`

**Observed:** A large bright interruption in the sky, with the diagram stretching horizontally and descriptions aligned beneath its nodes.

**Transfer:** Give one important explanation the room of a full stage.

#### Pixel earth footer · level 0

**Use:** Distinctive ending on all page types.

**CSS:** `background-color: #6c3200; color: #f6f8f7; padding-top: 112px; background-repeat: repeat-x; background-size: 320px auto`

**Observed:** A crisp green turf edge and irregular pixel earth texture make the sky meet the ground. Link columns sit below the illustrated boundary.

**Transfer:** Create a new tiled ground SVG and preserve the sky-to-earth transition.

## Components

### Navigation bar

**Use:** Persistent desktop orientation and compact conversion action.

**CSS:** `background: #ffffff; position: sticky; top: 0px; height: 72px; padding: 0px 64px; z-index: 50; display: flex; justify-content: center; box-shadow: 0px 49px 30px 0px rgba(0,0,0,0.01), 0px 22px 22px 0px rgba(0,0,0,0.03), 0px 5px 12px 0px rgba(0,0,0,0.03)`

**Text style:** `navigation` — Manrope Variable 600 · 14px/1.43

**Observed:** Blocky wordmark at left, two chevron menus and text links beside it; account access and a compact orange action align right. A thin status band precedes it and scrolls away.

**Transfer:** Keep the white navigation distinct from the illustrated body.

### Primary button

**Use:** Hero and closing conversion.

**CSS:** `background: #ff5e24; color: #ffffff; height: 48px; padding: 0px 32px; border-radius: 8px; display: inline-flex; align-items: center; justify-content: center; gap: 8px; box-shadow: inset 0px 1px 0px rgba(255,255,255,0.17), inset 0px -1px 0px rgba(255,255,255,0.03), 0px 0px 0px 1px #ff5e24, 0px 15px 6px rgba(4,15,32,0.02), 0px 8px 5px rgba(4,15,32,0.06), 0px 4px 4px rgba(4,15,32,0.1), 0px 1px 2px rgba(4,15,32,0.12)`

**Text style:** `button` — Manrope Variable 600 · 16px/1.5

**Observed:** A right arrow follows the label. Fine top light and soft-light shading give the orange face a tactile finish. The navigation and utility version is shorter, uses the navigation recipe, 36px height, 6px corners and 8px 16px padding.

**States:** Declared: hover scale 1 1; focus-visible outline-style none with an orange 1px ring and shadow; active opacity 0.85 and scale 1 1.

### Announcement capsule

**Use:** Short timely update above the main promise.

**CSS:** `background: rgba(255,255,255,0.8); color: #ff5e24; height: 32px; padding: 0px 12px 0px 0px; border-radius: 9999px; display: inline-flex; align-items: center; gap: 8px; backdrop-filter: blur(8px); box-shadow: 0px 0px 0px 1px rgba(35,38,41,0.08), 0px 88px 53px rgba(1,18,35,0.01), 0px 39px 39px rgba(1,18,35,0.02), 0px 10px 21px rgba(1,18,35,0.03)`

**Text style:** `navigation` — Manrope Variable 600 · 14px/1.43

**Observed:** A small orange capsule reading New is attached flush left; update text and a right arrow finish the row.

### Benefit card

**Use:** Compact proof of a specific promise.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 24px 0px; display: flex; flex-direction: column; gap: 16px; box-shadow: 0px 49px 30px rgba(0,0,0,0.01), 0px 22px 22px rgba(0,0,0,0.03), 0px 5px 12px rgba(0,0,0,0.03)`

**Text style:** `compact` — Manrope Variable 500 · 14px/1.43

**Observed:** A 16px inner side inset holds a centered 48px orange icon, a bold question-and-answer claim, and a short explanation with selective strong spans. Three cards share a row and equal height.

**Transfer:** Make each card answer a different practical concern.

### Question row

**Use:** Expandable objection handling.

**CSS:** `background: #ffffff; border-radius: 12px; max-width: 672px; min-height: 56px; box-shadow: 0px 49px 30px rgba(0,0,0,0.01), 0px 22px 22px rgba(0,0,0,0.03), 0px 5px 12px rgba(0,0,0,0.03)`

**Text style:** `label` — Manrope Variable 700 · 16px/1.5

**Observed:** Native details/summary structure. The summary has 16px padding and a three-part grid: gray question icon, left-aligned question, plus icon. The stack has 16px gaps, with Show All and Hide All controls above.

**States:** Declared: hover text-decoration-line underline.

### Personal letter

**Use:** A human voice inside a technical marketing story.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 32px 20px; box-shadow: 0px 49px 30px rgba(0,0,0,0.01), 0px 22px 22px rgba(0,0,0,0.03), 0px 5px 12px rgba(0,0,0,0.03)`

**Text style:** `body` — Manrope Variable 400 · 16px/1.5

**Observed:** Small pixel title, several short left-aligned paragraphs, direct contact link, named sign-off and a brief italic aside. The adjacent photograph gives the text a real-world counterpart.

**Transfer:** Use a real builder's note with specific experience and a welcoming invitation.

### Footer directory

**Use:** Useful navigation and a values-led ending.

**CSS:** `color: #f6f8f7; max-width: 1280px; display: grid; grid-template-columns: repeat(2, minmax(0px, 1fr)); gap: 96px; padding: 32px`

**Text style:** `navigation` — Manrope Variable 600 · 14px/1.43

**Observed:** The left half holds a reversed wordmark beside a contact link, with a short quotation and right-aligned attribution below. The right half splits into three compact link columns. Small copyright and trademark lines form a separate bottom row.

**Transfer:** Keep a small values statement or attributed thought alongside genuinely useful links.

### Purchase card

**Only for:** pricing pages

**Use:** Single clear offer in a split opening.

**CSS:** `background: #ffffff; border-radius: 16px; padding-top: 24px; display: flex; flex-direction: column; gap: 16px; box-shadow: 0px 49px 30px rgba(0,0,0,0.01), 0px 22px 22px rgba(0,0,0,0.03), 0px 5px 12px rgba(0,0,0,0.03)`

**Text style:** `compact` — Manrope Variable 500 · 14px/1.43

**Observed:** A 36px bold sans price and muted billing suffix lead. A quiet label and hairline introduce six checkmarked benefit lines. A full-width orange purchase action closes the card; the inner column is inset 24px. The action uses 40px height and 6px corners, not the hero's larger treatment.

**Transfer:** Explain one simple offer without inventing competing plan tiers.

### Platform tile

**Only for:** platform availability grids

**Use:** Show supported environments on a purchase-oriented page.

**CSS:** `background: #ffffff; border: 1px solid rgba(255,94,36,0.2); border-radius: 12px; padding: 16px; height: 118px; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 8px; box-shadow: 0px 4px 6px rgba(4,15,32,0.04)`

**Text style:** `navigation` — Manrope Variable 600 · 14px/1.43

**Observed:** Orange 32px platform symbol above a small platform name, then a peach availability pill. Three columns form two rows; an outlined waitlist action sits below.

**Transfer:** Use recognizable environment symbols and honest status labels.

## Imagery and graphics

### Stepped sky clouds

**Use:** Recurring signature background across the full marketing body.

**Observed:** White pixel clouds with very pale blue undersides occupy a small share of the blue field. Different-sized clusters sit beside headings or at viewport edges, behind rather than in front of text. Their stepped edges are crisp; there are no blurred atmospheric gradients.

**Transfer:** Recreate the sky motif even for a product with no visual media; sparse clouds establish the world without needing photography.

**Build:** Draw SVG paths on an 8px integer grid in a 225×160px viewBox. Build a flat-bottomed silhouette from 8px and 16px horizontal/vertical steps, rising to one asymmetric central peak; layer a white top, a white-at-65% lower face and a charcoal-at-4% base offset down 8px. Place several 160–225px-wide clouds at unequal heights behind content, partially clipping a few at the viewport edges. Use shape-rendering crispEdges, no blur.

### Pixel product companion

**Use:** Recurring original sprite at the product window, explanation nodes and closing ground.

**Observed:** A small orange smiling computer-like character sits on the application window, appears as a diagram node and returns larger above the footer. Black pixel outlines, pale face, orange body and simple block highlights contrast with smooth white panels.

**Transfer:** Invent an original pixel object associated with the new product, keeping the friendly engineering tone. The minimum version is a recognizable tool-shaped sprite, not a generic emoji.

**Build:** Create a 24×32 cell SVG sprite with rectangular fills and a 1-cell charcoal outline. Use orange for its main casing, white for a display or face, and white at 40% for hard-edged highlights. Add two small charcoal eyes or functional details. Scale to roughly 72–96px wide near panels and 88px wide at the ground without interpolation; anchor its bottom to the panel or turf.

### Pixel ground boundary

**Use:** Signature full-width ending shared by marketing and purchase-oriented pages.

**Observed:** Bright green turf has an irregular dark green pixel fringe; branching brown dirt pixels descend into the solid warm brown footer. A horizontally repeated strip turns the long sky into a platform-game landscape.

**Transfer:** Carry the ground transition into the ending, whether or not the page has a separate closing action. Keep it a narrow illustrated edge rather than a full game scene.

**Build:** Make a seamless 320px-wide SVG tile on a 4px or 8px grid. Use a bright grass top about 16px deep, three darker irregular stepped green fringe layers reaching about 32px, then branching lighter-brown rectangles tapering into #6c3200 over the next 64px. Repeat horizontally at native scale above the footer text; keep every edge orthogonal and unblurred.

### Application window

**Use:** Large product proof immediately after the opening promise.

**Observed:** One real desktop application view, 1152px wide with 16px corners, fine low-opacity charcoal edge and strong soft shadow. It rests directly in the sky without an extra colored pedestal; its top edge enters the opening fold, with the companion perched on it.

**Transfer:** Show one credible workflow in a real application frame. If there is no UI, use a specific process diagram at the same scale rather than an empty window.

### Technical pixel diagrams

**Use:** Explain how a capability actually works.

**Observed:** Simplified pixel objects such as a companion, globe and server connect through thin orange and pale gray paths. One diagram lives directly on the blue canvas; another fills the white Explanation stage, with two short text columns aligned below the main nodes.

**Transfer:** Use two or three original symbolic objects and one legible path to explain cause and effect, not a decorative network of dozens of nodes.

**Build:** Place two or three crisp SVG objects at 56–82px scale along a horizontal 4px neutral track. Overlay selected segments in orange and an orange 16px circular marker. Align concise text beneath the corresponding nodes; use a simple curved merge path only where the story requires convergence.

### Candid builder photograph

**Use:** Human trust chapter paired with a personal note.

**Observed:** A warm, ordinary indoor team photograph in a workshop, without duotone or dramatic grading. The 4:3 image has 24px corners and a hard 24px down-right translucent shadow; a tiny pixel companion perches near its top edge. A centered gray caption sits 48px below.

**Transfer:** Use a real working moment related to making the product. Keep the mundane surroundings, warm light and documentary framing; avoid polished corporate portraiture.

### Icons

**Observed:** Mostly filled SVG symbols. Utility arrows, chevrons and external-link marks are 16px; gray question symbols are 19px; benefit symbols are 48px orange and platform symbols 32px orange. Pixel-art objects belong to illustrations rather than the utility icon set.

**Transfer:** Use a consistent filled utility set for controls and larger orange silhouettes for benefits. Do not pixelate every small navigation icon.

## Section recipes

How recurring sections are built.

### First screen: Sky promise opening

**Observed:** Back to front: continuous Sky canvas, sparse Stepped sky clouds, centered announcement and text, primary action, secondary text actions, then the broad Application window with a Pixel product companion on its edge. A 32px status band and 72px Navigation bar fill the top. The opening text stage has a 768px maximum width and begins 144px below navigation. The 32px Announcement capsule is separated from the headline by 48px. The headline fills about half the desktop width in two tightly packed lines: charcoal setup above a longer orange payoff, using display. A centered 16px/24px support sentence sits below with key words bold and one emphatic italic. The Primary button follows a 40px gap; two small icon-led secondary actions sit on a separate row. Within the first 900px, all copy and actions are visible, plus a sprite and the top of the 1152px application window entering near the lower edge; most of the interface extends below the fold.

**Transfer:** Preserve the centered sky composition as the default landing-page opening. Use a new benefit statement and original pixel object; replace unavailable UI with a concrete explanatory diagram whose top enters the fold. Purchase-oriented pages instead use a 72px two-tone headline and short support on the left of a single Purchase card, while retaining clouds and blue sky.

**Avoid:** Do not replace this with a split hero, huge right-side 3D object, full-screen app screenshot or a headline floating over photography.

**Text style:** `display` — Jersey 10 500 · 96px/0.7 · tracking -0.025em

### Two-tone section lead

**Observed:** Centered label in muted gray uses label, followed after 16px by a compact heading block using heading. Orange is an inline conclusion or second line, not a gradient. Support uses support and a 576–672px measure, with orange underlined detail links. The broader heading measure reaches 896px; content typically begins after 48px.

**Transfer:** Write a short setup and decisive payoff, then give one explanatory paragraph and a route to more detail.

**Text style:** `heading` — Jersey 10 500 · 60px/0.8 · tracking -0.025em

### Comparison as visible mechanism

**Observed:** Two-tone section lead above a 1024px two-column grid with 32px gap. Comparison glass surrounds tall equal panels; a 1px orange border distinguishes the improved mechanism. Small object icons and short captions lead into stacked white detail cards, with nested muted containers and thin connecting lines.

**Transfer:** Make the difference observable through what each system exposes, changes or removes. Keep the simplified interface only as detailed as the argument needs.

### Short assertion and three proofs

**Observed:** A 48px pixel prelude introduces a 60px charcoal-and-orange assertion. A 64px gap separates it from three Benefit cards in a 1280px row with 16px gaps. Each card combines one orange symbol, a compact question-answer claim and centered explanatory text.

**Transfer:** Compress three practical objections into specific answers without turning the entire page into a feature tile wall.

**Text style:** `heading` — Jersey 10 500 · 60px/0.8 · tracking -0.025em

### Process explanation stage

**Observed:** Explanation stage fills a 1280px container. A centered Two-tone section lead sits above Technical pixel diagrams. The horizontal track connects three large objects, while two explanatory columns beneath use bold small headings and compact paragraphs with selective bold phrases.

**Transfer:** Use the wide white stage for the mechanism that makes the promise credible; retain the illustrated paths and quiet text instead of substituting a dense system architecture chart.

### Questions with global controls

**Observed:** Centered Two-tone section lead, short reassuring support and small Show All / Hide All controls precede a 672px column of Question rows. Thirteen closed rows use 16px vertical gaps. Clouds remain visible around the stack.

**Transfer:** Include a focused set of actual decision-blocking questions; the number should follow the product rather than fill a quota.

**Text style:** `heading` — Jersey 10 500 · 60px/0.8 · tracking -0.025em

### Builder note and documentary image

**Observed:** Human split places the Personal letter in a 624px column and the Candid builder photograph in the matching right column. Columns have a 32px gap and are vertically centered. Smaller pixel display type makes this chapter more intimate than the product assertions.

**Transfer:** Use a real person's conviction and working context as a change of register after technical explanation.

**Text style:** `note-heading` — Jersey 10 400 · 36px/1.111

### Closing promise meets the ground

**Observed:** A centered closing-display repeats the charcoal setup/orange payoff treatment, with a brief support line and side-by-side primary and text actions after 48px. The companion occupies the open blue space below, standing on the Pixel ground boundary. Footer directory follows on Pixel earth footer. Purchase-oriented pages move directly from questions to the same ground and directory, without a second conversion block.

**Transfer:** Keep the original sprite and ground as the closing visual signature. Choose whether a separate conversion promise serves the page; the illustrated ending remains in either case.

**Text style:** `closing-display` — Jersey 10 500 · 72px/0.85 · tracking -0.025em

### Single-offer purchase opening

**Only for:** pricing pages

**Observed:** A 1152px split with 96px horizontal gap aligns a left 72px charcoal/orange promise and support with a right Purchase card. The card's large price and six checkmarked lines create the main white mass. A centered availability heading and six Platform tiles follow on the same blue sky.

**Transfer:** Make the offer itself the main object rather than leading with an application window; use only truthful platform and billing details.

**Text style:** `closing-display` — Jersey 10 500 · 72px/0.85 · tracking -0.025em

## Page flow

**Storyline:** Promise → visible mechanism → practical proof → deeper explanation → objection handling → human conviction or direct conversion → illustrated ground and useful directory.

### Introduce a technical product and earn trust through explanation

1. **Promise** — Centered two-tone pixel headline, announcement, actions and sky-world introduction.
2. **Product demonstration** — Wide application window with a small character perched on its edge.
3. **Differentiation** — Two tall comparison panels make the mechanism visible.
4. **Practical proof** — Short assertion with three concise white proof cards.
5. **Capability chapters** — A diagram on the sky followed by a wide orange-outlined explanation stage.
6. **Objection handling** — Centered question stack with global expand and collapse controls.
7. **Human conviction** — A personal letter beside a candid working photograph.
8. **Closing call** — Two-tone promise, primary and secondary actions, and an original sprite above pixel turf.
9. **Directory** — Brown illustrated footer with values statement, contact and three link columns.

**Transfer:** Adapt the explanatory arc to the product's real mechanism; keep the pixel world, white proof surfaces and human voice without treating the chapter count as fixed.

### Make an uncomplicated purchase decision and remove remaining doubts

1. **Offer** — Left promise and right single-price card with checkmarked inclusions.
2. **Compatibility proof** — Six small platform tiles and a waitlist action.
3. **Reassurance** — The same assertion and three proof cards used in broader marketing.
4. **Objection handling** — The full centered question stack.
5. **Directory** — Direct transition into the pixel-ground footer, with no extra closing purchase pitch.

**Transfer:** Lead with a clear offer, then answer compatibility and practical concerns; preserve the shared sky and ground vocabulary.

## Writing

Technically confident, plainspoken and warmly irreverent. Strong promises are explained through mechanisms, then softened by conversational invitations and a builder's personality.

**Do not copy:** Do not reuse the Obscura name, wordmark, character artwork, employee identity, contact details, prices, device counts, network claims, privacy guarantees or manifesto quotation. Replace them with the new product's own substantiated facts and original assets. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your needs. Use we for the builders, the product name for concrete behavior, and first-person singular only in a genuinely personal note.
- **Rhythm:** Short headline propositions, often completed by a contrasting final phrase; support uses one or two plain sentences. Compact question-and-answer labels punctuate longer technical explanations. The personal note is allowed to be longer and more playful.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A meaningful promise followed by a stronger qualification; highlight the qualification. | 5–9 words | “Privacy that’s more than a promise” |
| Section assertion | State a limitation or mechanism in everyday words, with the decisive ending emphasized. | 6–16 words | “We can’t leak what we don’t have.” |
| Eyebrow | Short functional signpost in ordinary title case, not advertising jargon. | 1–4 words | “How it Works”<br>“More than Privacy” |
| Support | Connect concrete behavior to a reader outcome using short declarative sentences. | 15–30 words | “No logs by design. Stealth protocol for performance. Browse, stream, and game without worrying about your VPN.” |
| Primary action | Direct verb-led action without hype. | 2–4 words | “Get Started” |
| Reassurance | Brief question, then a firm short answer. | 2–6 words | “Logs? Not possible.” |
| Personal note | Acknowledge the reader, reveal a real person and invite direct contact. | Short paragraphs with a named sign-off | “Thanks for reaching the bottom — not everyone makes it.”<br>“I’m Carl, head-janitor of [Brand] 👋” |

**Words and phrasing to use:** by design; here to help; built; simple; your; we can’t; how it works; concrete technical nouns followed by plain explanation

**Avoid:** revolutionary; military-grade; unparalleled; enterprise transformation; unlock limitless potential; unsupported absolutes

**Rules:**

- Make the reason for a strong claim easy to find in the following sentence or diagram.
- Use contractions naturally; let a short italic or bold phrase carry emphasis rather than adding exclamation marks.
- Inline detail links can be conversational and brief, while the surrounding sentence remains intelligible.
- Give the personal voice specific experience and a direct invitation, not a generic corporate mission statement.

## Do's and Don'ts

### Do

- Keep the body canvas #dceefe across chapters so the page reads as one illustrated sky.
- Set the opening at 96px/0.7 Jersey 10 and ordinary section headings at 60px/0.8.
- Use orange on the headline's payoff and charcoal on its setup.
- Retain the primary button's 48px height, 8px corners and inset top light.
- Use 96px vertical section padding around compact 16px-gapped content groups.
- Let clouds and an original small pixel object recur at panel edges and in the closing landscape.
- Use 16px white cards with subtle multi-layer elevation rather than thick outlines.
- Keep the footer's brown ground and crisp tiled turf distinct from the blue page.
- Pair intimate 16px/24px prose with a candid 4:3 working photograph when adding human proof.

### Don't

- Do not turn the primary action into a 9999px pill; pills belong to announcements and tiny badges.
- Do not set body text or navigation in the pixel display face.
- Do not flood ordinary sections with orange; it is a text, icon, edge and action accent.
- Do not add blurry neon glows or smooth 3D clouds to the hard-edged sky artwork.
- Do not round every panel to 32px; that radius belongs to the wide explanation stage.
- Do not use the product window's strong 25px/50px shadow on every small benefit card.
- Do not make the personal photograph monochrome or replace its offset backing with a glowing frame.
- Do not turn the availability grid into giant feature cards; keep the tiles compact at 118px high.
- Do not use an ordinary black footer that erases the sky-to-pixel-ground ending.

## Motion and responsive

### Motion

**Observed:**

- Actions commonly declare 0.3s transitions with cubic-bezier(.4, 0, .2, 1); hero action and announcement use cubic-bezier(0, 0, .2, 1). Navigation uses 0.25s with cubic-bezier(0, 0, .2, 1).
- Primary actions declare hover scale 1 1 and active opacity 0.85; question controls declare hover underlining.

**Transfer:**

- Keep tactile shading stable on hover rather than adding bouncing game-button movement.
- Pixel objects retain their identity as static SVG when animation is not available.

**Unknown:**

- Timing and behavior of canvas scenes and sprite animation are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 600px, 640px, 768px, 800px, 1024px, 1280px and 1536px.
- Sections switch between 20px and 64px side insets. Desktop navigation is hidden below medium.
- Opening display reduces to 60px below large; section headings reduce to 48px below medium.
- Pricing split becomes a column below medium. Platform grids start at two columns and become three at small.
- Question rows lose corners and shadows and gain bottom borders below medium.

**Transfer:**

- Retain crisp clouds and the ground tile on small screens; move decorative objects clear of text.
- Stack explanation nodes with their descriptions when a horizontal diagram no longer fits.

**Unknown:**

- Mobile navigation replacement, small-screen opening spacing and canvas resizing behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
