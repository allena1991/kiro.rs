# Tokens Studio — tooling as toybox

## Overview

A light, punchy software style that makes technical infrastructure feel tangible and playful. Heavy uppercase grotesk headlines sit above calm explanatory copy, surrounded by candy-colored interface objects and chunky illustrated tools. Pale gray space dominates, with lavender and yellow editorial panels, cyan actions, pastel proof cards and a deep teal ending. The density alternates between spacious product theater and compact practical information.

### Essentials

- Compressed verbal posters, not delicate typography: uppercase display headlines use 80px/0.9, visual weight 800 and -0.03em tracking; section headlines step to 64px or 48px at 1 line height.
- A centered promise floats above a toybox of useful objects: an approximately 798px headline width, 728px support width and paired 370×88px actions occupy the upper center; tilted interface fragments enter from the lower edges.
- Actions are chunky rectangles rather than pills: cyan #38e8f5, dark teal text, 12px corners and a 48px dark icon tile in the main 88px-high button; navigation uses a smaller 40px-high, 10px-corner version.
- Color arrives in bounded bursts: keep most of the reading canvas #f7f8f8, then introduce 1280px-wide yellow or lavender panels with 20px corners and color-matched dark text. Reserve the full-width deep teal field for the monumental closing call.
- Technical imagery is made physical: thin dark outlines, solid-colored rounded backing plates, slight rotation, visible extruded edges and restrained offset shadows; include a playful tool-object scene even when the fallback is a simplified SVG control panel.
- Proof has two registers: soft pastel quote cards use 28px/1 text with generous 32px 24px padding, while short dark stat bars use 32px colored numbers. Preserve this contrast rather than making every proof card identical.
- The ending is a second hero, not a narrow legal strip: a white 80px/0.9 uppercase invitation sits on #032d30 above a cyan action, then five link columns, a brand/social row and a subdued legal baseline.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep teal | `#032d30` | `--color-teal` | background, text | Closing field and text on cyan actions. |
| Electric cyan | `#38e8f5` | `--color-cyan` | action, accent | Main and navigation actions; tangible control-object artwork. |
| Purple black | `#08022f` | `--color-navy` | text, background | Ink and secondary actions in lavender chapters. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lavender panel | `#a499ff` | `--color-lavender` | surface, accent | Wide editorial panels and object faces. |
| Toolbox yellow | `#ffca38` | `--color-yellow` | surface, accent, text | Editorial panels and warm stat accents. |
| Yellow black | `#2f2302` | `--color-olive` | text, surface | Yellow-panel text and dark yellow-stat bars. |
| Rose proof wash | `#fef0f4` | `--color-pink-wash` | surface | Soft testimonial backing. |
| Rose proof ink | `#5c1027` | `--color-pink-ink` | text | Quote and customer mark on rose wash. |
| Violet proof wash | `#f1f0fe` | `--color-violet-wash` | surface | Lavender testimonial backing. |
| Violet proof ink | `#261f5c` | `--color-violet-ink` | text | Quote and customer mark on violet wash. |
| Peach proof wash | `#fef3f0` | `--color-peach-wash` | surface | Warm testimonial backing. |
| Peach proof ink | `#671c05` | `--color-peach-ink` | text | Quote and customer mark on peach wash. |
| Lime proof wash | `#f6fef0` | `--color-green-wash` | surface | Green testimonial and expanded capability backing. |
| Lime proof ink | `#306705` | `--color-green-ink` | text | Quote and customer mark on lime wash. |
| Lime black | `#162f02` | `--color-forest` | text, surface | Dark green stat bars and capability text. |
| Lime accent | `#90eb4b` | `--color-lime` | text, accent | Bright text on dark green stat bars; green object family. |
| Orange black | `#2f0d02` | `--color-rust-dark` | surface | Dark orange stat backing. |
| Orange stat accent | `#ff764c` | `--color-orange` | text, accent | Warm stat figures and labels. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Navigation, cards, interface frames and reversed text. |
| Cool light canvas | `#f7f8f8` | `--color-canvas` | background | Main reading field. |
| Track gray | `#eceeee` | `--color-track` | surface | Slim inactive progress rails. |
| Control gray | `#ebedee` | `--color-soft-gray` | surface, border | Secondary hero action, pale physical frames and offset card shadows. |
| Muted teal-field text | `#9ab5b6` | `--color-muted-on-teal` | text | Visible result of white at 60% over deep teal, used for footer categories and legal text. |
| Headline ink | `#0c0f0f` | `--color-ink` | text, background | Primary headings and dark action surfaces. |
| Secondary near black | `#0c0e0f` | `--color-secondary` | text, background | Card titles and secondary editorial copy. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Entry plan gray | `#e6e9e8` | `--color-plan-gray` | surface | Entry-tier header. |
| pricing pages | Team plan pink | `#ff709c` | `--color-plan-pink` | surface, accent | Middle-tier header and matching checklist marks. |

## Typography

- **Almarena Neue** — Body, actions, navigation, quotations and figures. Friendly contemporary grotesk with broad, direct shapes; medium quotations remain conversational rather than editorial-serif. If unavailable, use **DM Sans**. Use 400, 500, 600 and 800; preserve the compact line heights. Font stack: "Almarena Neue", "DM Sans", Arial, sans-serif.
- **Almarena Neue Display** — Poster headlines and prominent section labels. Heavy grotesk with distinctive angled cuts and tightly packed capitals. If unavailable, use **DM Sans**. Use 800 for opening headlines, 700 for section titles and 600 for mixed-case leads; retain -0.03em tracking. Font stack: "Almarena Neue Display", "DM Sans", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Almarena Neue Display | 800 | 80px | 0.9 | -0.03em, uppercase | Centered opening promise. |
| closing-display | Almarena Neue | 800 | 80px | 0.9 | -0.01em, uppercase | Monumental white closing invitation. |
| heading-lg | Almarena Neue Display | 700 | 64px | 1 | -0.03em, uppercase | Demo introductions and wide colored editorial panels. |
| heading | Almarena Neue Display | 700 | 48px | 1 | -0.03em, uppercase | Section titles, proof introductions, contact invitations and capability chapters. |
| card-title | Almarena Neue | 600 | 32px | 38px | normal | Resource and audience-card titles in mixed case. |
| stat | Almarena Neue Display | 600 | 32px | 1.4 | -0.01em | Compact colored numbers on dark bars. |
| stat-tight | Almarena Neue Display | 600 | 32px | 38px | -0.03em | Short metric heading paired with a smaller description. |
| quote | Almarena Neue | 500 | 28px | 1 | normal | Testimonials without oversized quotation marks. |
| proof-label | Almarena Neue Display | 600 | 24px | 38px | -0.03em, uppercase | Centered customer-logo introduction. |
| action | Almarena Neue | 600 | 20px | 1.2 | -0.01em | Hero and closing actions and editorial text links. |
| body | Almarena Neue | 400 | 18px | 1.4 | -0.01em | Support lines and explanatory paragraphs. |
| navigation | Almarena Neue | 600 | 14px | 2 | normal, uppercase | Primary navigation categories. |
| small-action | Almarena Neue | 600 | 14px | 1.4 | -0.01em | Navigation conversion label and footer links. |
| footer-label | Almarena Neue | 600 | 14px | 1.4 | -0.01em, uppercase | Subdued link-column categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| use-case and culture lists | list-lead | Almarena Neue Display | 600 | 48px | 56px | -0.02em | Open mixed-case statement lists beside a smaller uppercase section heading. |
| pricing pages | price | Almarena Neue | 600 | 44px | 1 | -0.02em | Plan price before currency-period details. |
| pricing questions | question | Almarena Neue | 600 | 24px | 1 | normal | Accordion question title. |

**Notes:**

- Keep the heavy display cuts heavy even though their separate font files use a regular CSS weight. The opening is visually ExtraBold, section titles Bold, mixed-case display leads SemiBold.
- The 80px opening and 64px/48px section titles share -0.03em tracking, while body and actions stay at -0.01em. The closing uses the less tightly tracked sans recipe rather than the opening display recipe.
- Body remains mixed case and comparatively small. Never uppercase the long explanatory paragraphs. No viewport-relative type formula is specified; these are the desktop recipes.

## Layout

**Density:** Airy at section scale, compact inside controls and proof cards; large open intervals let the physical tool objects carry the color.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Small control groups and stacked local labels. |
| 16px | Pricing-grid gutters. |
| 20px | Proof-column gutters and resource-card inner padding. |
| 24px | Action-pair gap and horizontal quote padding. |
| 32px | Opening title-to-copy and copy-to-action intervals; vertical quote padding. |
| 40px | Colored-panel inner padding and general layout separations. |
| 48px | Quote-to-logo separation and logo-introduction gap. |
| 60px | Recurring outer gaps between landing-page blocks. |
| 80px | Capability-selector spacing and desktop content margins at 1440px. |
| 100px | Major chapter breathing room and closing-field top/bottom padding. |
| 200px | Top-of-page lead-in before the opening headline; spacious educational-media section padding. |

### Containers and grids

- **content**: max width 1280px · side padding 20px. Centered main content; at 1440px the full-width panels have 80px outer margins.
- **opening-copy**: max width 798px. Centered title block; support text narrows further to 728px.
- **three-column**: max width 1280px · 3 columns · gap 20px. Proof composition, resources and audience cards; use staggered heights instead of forcing equal horizontal baselines.
- **footer**: max width 960px · side padding 20px. Narrower closing composition inside the full-width teal field; five category columns share the width.
- **pricing-grid** (only for pricing pages): max width 1280px · 3 columns · gap 16px. Equal 416px plan cards with aligned colored headers.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | main-actions | 12px |
|  | compact-actions-and-rows | 10px |
|  | cards | 16px |
|  | editorial-panels | 20px |
|  | demo-frame | 40px |
| product capability illustrations | feature-art-plate | 44px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | navigation-ledge | `0px 3px 0px 0px rgba(12, 15, 15, 0.2)` | Small solid-looking ledge under the floating white navigation. |
| pricing pages | plan-card | `0px 2px 20px 0px rgba(0, 0, 0, 0.08)` | Soft lifting shadow under white plans. |
| audience cards | audience-card | `6px 6px 0px 0px #ebedee` | Hard pale offset that reinforces an illustrated-paper construction. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing canvas.

**CSS:** `background: #f7f8f8`

#### White card · level 1

**Use:** Resource cards and grouped information.

**CSS:** `background: #ffffff; border-radius: 16px; overflow: hidden`

**Observed:** Resource and audience cards have a thin dark perimeter in the visible design; plain utility cards are flatter.

**Transfer:** Keep a crisp edge where picture and white text area need separation; avoid a generic shadow on every card.

#### Yellow editorial panel · level 1

**Use:** Large confidence or story chapter.

**CSS:** `background: #ffca38; color: #2f2302; border-radius: 20px; padding: 40px 100px 40px 40px; overflow: hidden`

**Observed:** A wide text-heavy left half is counterweighted by a tangible illustration on the right.

**Transfer:** Give this field one focused claim, not a dense feature grid.

#### Lavender editorial panel · level 1

**Use:** Open-system or product-value chapter.

**CSS:** `background: #a499ff; color: #08022f; border-radius: 20px; padding: 40px 100px 40px 40px; overflow: hidden`

**Observed:** The full-width story panel is distinct from the larger 40px-corner manifesto field used on company and detailed product pages.

**Transfer:** Preserve the saturated flat backing rather than replacing it with a gradient.

#### Pastel proof · level 1

**Use:** Testimonials in a compact masonry wall.

**CSS:** `background: #fef0f4; color: #5c1027; border-radius: 16px; padding: 32px 24px`

**Observed:** Other pairings are violet wash/violet ink, peach wash/peach ink and lime wash/lime ink; peach and violet versions use 10px corners.

**Transfer:** Pair a very light tint with a dark version of the same hue; do not use one global black for every quote.

#### Closing field · level 0

**Use:** Closing invitation and full footer.

**CSS:** `background: #032d30; color: #ffffff; padding: 100px 20px`

**Observed:** A continuous 1119px-tall desktop field joins conversion and navigation, with no separate light footer.

**Transfer:** Keep the invitation and footer visually continuous even when the link inventory changes.

## Components

### Navigation

**Use:** Persistent brand and site-level access.

**CSS:** `position: fixed; z-index: 10; height: 78px; background: #ffffff; border-radius: 10px; box-shadow: 0px 3px 0px 0px rgba(12, 15, 15, 0.2)`

**Text style:** `navigation` — Almarena Neue 600 · 14px/2 · uppercase

**Observed:** Logo left, three category links with small chevrons and pricing in the center, login and Compact action right. The opening bar reads nearly full width; on scroll it becomes a centered 1024px island with a 20px top inset.

**Transfer:** Retain the full-to-floating behavior and separation of plain login from the cyan conversion action.

### Primary action

**Use:** Opening and closing conversion.

**CSS:** `width: 370px; height: 88px; background: #38e8f5; color: #032d30; border-radius: 12px; position: relative; overflow: hidden`

**Text style:** `action` — Almarena Neue 600 · 20px/1.2 · tracking -0.01em

**Observed:** Left-aligned label follows a dark 48px icon tile with a white product glyph. Tile sits 20px inside the action; label and tile have a 12px gap.

**Transfer:** Use the new product's simple symbol or an abstract four-point tool glyph; preserve the oversized tactile proportions.

### Secondary action

**Use:** Alternate path alongside the main action.

**CSS:** `width: 370px; height: 88px; background: #ebedee; color: #032d30; border-radius: 12px`

**Text style:** `action` — Almarena Neue 600 · 20px/1.2 · tracking -0.01em

**Observed:** Plain text without the dark icon tile. Paired with Primary action at a 24px gap.

### Compact action

**Use:** Navigation conversion.

**CSS:** `height: 40px; background: #38e8f5; color: #032d30; border-radius: 10px; padding: 10px 16px`

**Text style:** `small-action` — Almarena Neue 600 · 14px/1.4 · tracking -0.01em

**Observed:** Text-only, about 113px wide; visually subordinate to the hero action.

### Story panel

**Use:** Illustrated narrative chapter.

**CSS:** `background: #ffca38; color: #2f2302; border-radius: 20px; padding: 40px 100px 40px 40px; max-width: 1280px`

**Text style:** `heading-lg` — Almarena Neue Display 700 · 64px/1 · tracking -0.03em · uppercase

**Observed:** Title, compact paragraph and dark rectangular action sit left; a large illustrated object occupies the right third. Lavender variant changes both backing and ink to the matching purple family.

**Transfer:** Use a purposeful tool or interface illustration rather than a generic decorative blob.

### Quote card

**Use:** Customer story in the proof wall.

**CSS:** `background: #fef0f4; color: #5c1027; border-radius: 16px; padding: 32px 24px; display: flex; flex-direction: column; gap: 48px`

**Text style:** `quote` — Almarena Neue 500 · 28px/1

**Observed:** Quote first, customer logo below in matching dark hue; variable heights make a masonry rhythm. No star rating or oversized quote glyph.

### Stat bar

**Use:** Concise quantified proof between testimonial cards.

**CSS:** `background: #2f2302; color: #ffca38; border-radius: 10px; height: 106px`

**Text style:** `stat` — Almarena Neue Display 600 · 32px/1.4 · tracking -0.01em

**Observed:** Short figure and optional smaller descriptor aligned left. Orange-on-rust variant is also 106px high; lime-on-forest variant is 80px high. Numerals stay modest rather than becoming giant display art.

### Resource card

**Use:** Editorial resource preview.

**CSS:** `background: #ffffff; color: #0c0e0f; border-radius: 16px; overflow: hidden`

**Text style:** `card-title` — Almarena Neue 600 · 32px/38px

**Observed:** A 413×260px thumbnail leads into a 20px-padded body with title, optional one-line explanation and Action link. A thin dark outline surrounds the card; staggered cards flank a central heading.

### Action link

**Use:** Resource-card navigation without another filled button.

**CSS:** `color: #032d30; background: transparent`

**Text style:** `action` — Almarena Neue 600 · 20px/1.2 · tracking -0.01em

**Observed:** Plain, strong text set at the bottom of the card; no pill, arrow capsule or underline in its resting presentation.

### Footer link

**Use:** Repeated links under subdued category labels.

**CSS:** `color: #ffffff; padding: 12px 0px; background: transparent`

**Text style:** `small-action` — Almarena Neue 600 · 14px/1.4 · tracking -0.01em

**Observed:** Five categories spread across the closing container, with uneven link counts. A lower row pairs brand mark with social icons, then a faint rule and copyright/legal baseline.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side buying options.

**CSS:** `background: #ffffff; border-radius: 16px; box-shadow: 0px 2px 20px 0px rgba(0, 0, 0, 0.08); overflow: hidden`

**Text style:** `price` — Almarena Neue 600 · 44px/1 · tracking -0.02em

**Observed:** Three equal cards: gray, pink and lavender 115px header strips; centered plan name and audience line; price, full-width dark action, outlined category tag, scalloped check list and small ideal-for explanation below. Billing switch is centered above; yearly savings is a yellow badge.

**Transfer:** Keep shared action color across tiers; distinguish tiers through the header and checklist accents.

### Question row

**Only for:** pricing questions

**Use:** Objection handling in an accordion column.

**CSS:** `background: #ffffff; border-radius: 10px; padding: 20px 24px 0px 24px`

**Text style:** `question` — Almarena Neue 600 · 24px/1

**Observed:** One-line rows are about 65px high, longer questions wrap. A black plus occupies the right edge; the text row has 20px bottom padding. A narrower heading/support/action column sits to the left.

## Imagery and graphics

### Physical interface toybox

**Use:** Signature opening product scene and selected feature illustrations.

**Observed:** Pink graph plates, lime font controls, purple accessibility tiles, cyan switches and a dark code panel orbit a large pale-framed interface. They are slightly rotated, with visible colored side faces and pale offset shadows. The scene enters from the lower and side edges, leaving the headline and actions clear; the main interface continues below the fold.

**Transfer:** Turn two or three real capabilities into small physical control objects. Minimum version: one useful white interface panel plus three SVG control plates, not a stock laptop mockup.

**Build:** Create rounded SVG plates with 12–24px corners, a thin darker-hue outline and a duplicate face offset 6–12px to suggest extrusion. Rotate each plate by roughly 5–12 degrees; add a pale gray shadow offset about 12px down-right. Use lavender, cyan and yellow faces, with one pink or lime object. Put simple graph paths, toggle shapes or two-by-two labeled controls on their front faces. Arrange around a central white rounded panel; clip outer objects at the viewport edges. These construction dimensions are transfer guidance.

### Illustrated story companions

**Use:** Wide colored story panels.

**Observed:** A hand-drawn mechanical character on yellow and a purple character beside a tilted dark interface on lavender. Bold dark contours, limited monochromatic shading and solid flattened grounding shapes keep them cartoon-like rather than photorealistic.

**Transfer:** Use a new tool-character or an abstract articulated mechanism, occupying roughly the right third. Minimum acceptable version is a thick-line SVG tool with two solid shade planes.

**Build:** Draw a tool body with rounded rectangle joints, short articulated connectors and a few bold interior lines. Use the panel hue for highlights, its paired ink for outlines and a low-opacity ink ellipse beneath. Place a skewed rounded interface card in front if needed; keep facial or mechanical detail sparse.

### Resource and education media

**Use:** Human proof and learning content.

**Observed:** A mix of actual product closeups, colorful talk graphics and candid speaker/team photography. Resource media is edge-to-edge above white text cards; educational videos form an overlapping stack with a larger front frame and smaller receding frames.

**Transfer:** Use real people and actual teaching material. Maintain rounded clipping and show one readable front frame rather than a wall of tiny videos.

### Capability closeups

**Only for:** detailed product chapters

**Use:** One concrete visual per capability.

**Observed:** About 400px-square rounded bright backing plates contain tightly cropped white interface fragments, including sidebars, graphs and export windows. Large 44px corners and deliberately off-center crops make the interface look like a tangible object. Purple, cyan, lime, yellow and pink plates alternate.

**Transfer:** Show only the portion proving the nearby claim, backed by one flat accent. Keep copy alongside, not baked into a giant application image.

### Culture word sculpture

**Only for:** company storytelling

**Use:** Emotional typographic interlude.

**Observed:** An enormous cyan extruded word sits between smaller black uppercase lines. Individual letters vary in tilt and baseline; darker cyan side faces and pale gray shadows create chunky paper-toy volume.

**Transfer:** Choose one short emotional word relevant to the new company. It should act as the section's artwork, not as an additional body-copy font.

**Build:** Convert a heavy uppercase word to SVG paths; separate the letters, rotate them independently and stagger baselines. Duplicate paths diagonally behind each face to create side depth, with a darker cyan layer and a farther pale-gray shadow. Keep surrounding lines flat black and much smaller. Fit the sculpture across roughly two thirds of the content width.

### People and origin imagery

**Only for:** company storytelling

**Use:** Team and parent-company context.

**Observed:** Cutout team portraits sit in cyan, yellow and lime cards above dark matching nameplates; arrow buttons and short progress marks signal a carousel. A separate near-black rounded panel pairs white copy with a tall faceted crystal enclosing a warm mountain landscape that extends beyond the panel's height.

**Transfer:** Use authentic portraits with the same bright-card/dark-nameplate construction. For an origin story, use a location or meaningful object treated as one dramatic cutout against the dark field; keep the crystalline landscape treatment confined to this narrative type.

### Icons

**Observed:** Small navigation chevrons are dark and minimal. Main actions carry a white filled glyph in a dark 48px rounded tile. Pricing uses 22px outlined scalloped check marks with 1.5px strokes in tier colors; FAQ rows use plain black plus signs. Social marks are solid white on teal.

**Transfer:** Prefer plain functional symbols. Reserve the larger filled badge for primary conversion; do not distribute decorative icon circles throughout every paragraph.

## Section recipes

How recurring sections are built.

### First screen: Centered promise over physical tools

**Observed:** A white navigation strip sits above the pale Canvas. The title begins 200px down the desktop page and spans about 798px in the center: two tightly stacked 80px uppercase lines on a 1440px-wide screen. A 728px-wide mixed-case support paragraph follows after 32px, then Primary action and Secondary action sit side by side after another 32px. Behind and below the text, Physical interface toybox objects enter from the edges: a small purple tile at the right, pink graph at lower left, lime control and dark code card at lower right. Within the first 900px, the full headline, paragraph and both actions are visible, along with those objects and only the upper lip of the central interface. The main interface and demonstration continue below the fold.

**Transfer:** Use this centered promise/action composition as the default landing opening. Construct an equivalent toybox from the new product's own inputs and outputs, or use the simplified SVG recipe. A detailed product opening may use one primary action and lead directly to a framed demo on lavender; a pricing opening replaces the artwork with a billing selector and plan headers, while a company opening leads to a broad candid work photograph.

**Avoid:** Do not turn the opening into a left-copy/right-dashboard SaaS split, put the whole scene inside a hero card, or move the main interface above the promise.

**Text style:** `display` — Almarena Neue Display 800 · 80px/0.9 · tracking -0.03em · uppercase

### Demonstration theater

**Observed:** A centered stacked 64px uppercase introduction leads to an oversized rounded demonstration frame. The pale outer frame and white inner frame sit against the cool canvas, allowing the media to dominate the width.

**Transfer:** Show a working product preview with a poster and useful controls; let the frame be wider than the support text.

### Capability selector and closeup

**Observed:** A compact centered 48px heading introduces a split composition: three 40px uppercase capability labels on the left and large product artwork on the right. The selected capability expands into a pale green rounded explanation with 40px padding, an 18px paragraph and a slim progress rail. Detailed product chapters instead give each capability a 48px title, 30px/42px explanatory copy and a bright square closeup, separated by nearly viewport-sized intervals.

**Transfer:** Use a compact selector for an overview and the spacious illustration/copy format for a deep product page. Keep the selected state legible and the illustration tied to one claim.

### Colored story chapter

**Observed:** Story panel combines heading-lg, a short paragraph and a dark 88px-high action with Illustrated story companions. Yellow and lavender variants form successive wide panels, using sticky overlap rather than small tiles.

**Transfer:** Use a wide chapter for a strategic belief or differentiator; vary its place in the story rather than reproducing a fixed sequence.

### Logo field and proof masonry

**Observed:** A 24px uppercase label sits 48px above a five-column, two-row customer-mark field; marks occupy about 160×50px with 80px horizontal and 32px row gaps. The larger proof wall pairs a narrow left heading with two 412–416px masonry columns of Quote card and Stat bar, with 20px gutters.

**Transfer:** Use verified customer marks and genuine quotations; preserve the alternation of pale quotes and dark numerical summaries, adapting the number of cards to available proof.

### Staggered editorial cards

**Observed:** Three Resource cards form an uneven landscape: a left card high, center card low and right card between, leaving a centered 48px stacked headline in the upper middle. Cards use real pictures, mixed-case titles and Action links rather than repeating conversion buttons.

**Transfer:** Let content lengths vary; use the open area between cards as part of the composition, not a rigid equal-height grid.

### Monumental closing and footer

**Observed:** Closing field starts with 100px breathing room, a centered closing-display headline about 778px wide, white support 24px below it and Primary action after 32px. The 960px container then opens into five link categories with small muted uppercase labels and white links. Beneath is a brand/social row, faint horizontal divider and split copyright/legal baseline; legal text is white at 60%. All four page types share this ending.

**Transfer:** Make one concise outcome-based final invitation, followed by useful routes through the site. Keep the entire ending on deep teal and preserve its generous height.

### Practical purchase and questions

**Only for:** pricing pages

**Observed:** A centered display promise and 18px explanation introduce the billing control, then Plan cards. A two-column enterprise note uses a white contact card with a cutout staff portrait. Logos precede a split question section: 48px uppercase heading and contact copy left, Question rows right.

**Transfer:** Explain who each option suits and what changes between tiers; keep operational details visually smaller than prices and questions.

### Open statement list

**Only for:** use-case and culture lists

**Observed:** A 1280px-wide, 523px-high rounded chapter sets an uppercase heading on the left and four open mixed-case 48px/56px statements on the right, with about 30px between them. Company version is white; product version uses the cool canvas.

**Transfer:** Use short outcome or principle statements without enclosing each one in another card.

### Audience cards and product montage

**Only for:** detailed product pages

**Observed:** Three staggered audience cards use white bodies, dark outlines, pale 6px offset shadows and saturated illustrated top halves. The middle card sits lower beneath a central 64px heading. Later, a wide two-row montage of rounded product images bleeds past both viewport edges, mixing UI closeups with bright physical control objects.

**Transfer:** Differentiate audiences through outcomes and one graphic motif each. Use the montage to reconnect broad claims to actual product surfaces, not as a random screenshot gallery.

### Contact invitation

**Only for:** company and detailed product pages

**Observed:** A 600px-tall light section pairs a centered 48px uppercase contact heading and 18px support line on the left with a simple stacked form on the right. Rounded gray name/email fields and a taller message field lead to a compact cyan send action.

**Transfer:** Keep form styling subdued and the invitation short; place operational validation beneath the relevant field.

## Page flow

**Storyline:** Promise → tangible demonstration → capability explanation → values or differentiation → proof → learning or purchase support → monumental closing invitation.

### Broad product marketing overview

1. **Promise** — Centered uppercase outcome with two large actions and physical tool objects.
2. **Product demonstration** — Oversized interface scene and a framed demo introduced by a stacked headline.
3. **Capability explanation** — Selected capability text and changing tool artwork.
4. **Differentiation** — Wide yellow and lavender illustrated story panels.
5. **Social and quantified proof** — Customer logos followed by pastel quotes and dark stat bars.
6. **Learning** — Staggered editorial cards and stacked education videos.
7. **Closing call** — Deep teal invitation, cyan action and integrated footer.

**Transfer:** Lead with an outcome, make the product tangible, then support it with genuine proof and useful education.

### Detailed platform evaluation

1. **Promise** — Centered display headline, short automation-oriented support and one large action.
2. **Product demonstration** — Wide framed video overlaps a rounded lavender rationale panel.
3. **Capability chapters** — A centered chapter title leads to repeated bright interface closeups beside substantial copy.
4. **Ecosystem proof** — A text column sits beside pastel integration tiles.
5. **Comparison** — Centered heading pair and a spacious two-offering comparison table.
6. **Audience fit** — Open use-case list and staggered audience cards.
7. **Product breadth** — Customer marks and an edge-bleeding product montage.
8. **Contact and closing call** — Simple contact form, then the shared teal invitation and footer.

**Transfer:** Use the detailed variant for products requiring architectural explanation or comparison; keep technical copy in readable chapters.

### Purchase decision and objection handling

1. **Promise** — Centered display headline with a compact explanation of the offer.
2. **Pricing** — Billing switch and three plan cards with distinct colored headers.
3. **Enterprise support** — Tailored-service copy beside a staff contact card.
4. **Trust** — Customer-logo field.
5. **Objection handling** — Split FAQ introduction and white question rows.
6. **Closing call** — Shared teal invitation and full footer.

**Transfer:** Trade visual theater for comparative clarity while retaining the same type, bright headers and closing field.

### Company affinity and credibility

1. **Belief** — Centered display statement followed by a broad photograph of creative work.
2. **Emotional identity** — Extruded cyan word sculpture and open manifesto copy with small sticker-like keywords.
3. **Mission** — A yellow raised statement card and large lavender manifesto panel with physical tool objects.
4. **Principles and people** — Open statement list and bright portrait carousel.
5. **Origin** — Near-black story panel with a dramatic faceted landscape object.
6. **Contact and closing call** — Light contact section followed by the common teal invitation and footer.

**Transfer:** Use the company variant to show authentic craft, people and beliefs, keeping its word sculpture and origin art out of ordinary feature pages.

## Writing

Direct, technically literate and optimistic, with playful flashes rather than constant jokes. Claims describe real workflow consequences; the confidence comes from concrete mechanisms and short declarative lines.

**Do not copy:** Do not reuse Tokens Studio, HYMA, product names, proprietary character artwork, customer marks, quotations, user counts, prices or performance claims. Source examples demonstrate cadence only; replace them with substantiated content for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use you and your for outcomes and fit, we for convictions and practical support. Name the product when explaining its role; avoid impersonal enterprise jargon.
- **Rhythm:** Headlines are short stacked declarations, often 3–8 words, with paired clauses or three clipped imperatives. Paragraphs explain mechanisms in one to three sentences. Em dashes connect cause and outcome; occasional fragments add emphasis.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the job, then state its transformed condition. | 4–8 words | “Design systems, fully automated”<br>“One platform. Endless possibilities.” |
| Supporting line | A sequence of practical verbs links automation to a useful outcome. | 12–35 words | “Automate the boring. Scale your brand. Bridge design and development—from Figma to code.” |
| Primary action | Short verb plus product destination or low-friction entry. | 2–4 words | “Explore Studio Platform”<br>“Start for free” |
| Capability explanation | Name the mechanism, then explain why it saves effort. | 20–45 words | “Tokens flow directly into your CI/CD pipeline: Web, iOS, Android, and more. No more manual copy/paste.” |
| Proof introduction | Confident but human, sometimes contrasting shallow proof with real experience. | 6–12 words | “Logos are nice. But stories are better.” |
| Culture statement | An abstract principle made concrete through two short opposing clauses. | 5–10 words | “To automate the boring. To scale the creative.” |
| Closing invitation | An outcome-based imperative with a final acceleration. | 4–7 words | “Build better systems—faster” |

**Words and phrasing to use:** build; bridge; open; shared; structure; flow; scale; source of truth; No more…; without…

**Avoid:** revolutionary magic; unparalleled synergy; future-proof everything; effortless transformation; cute mascot narration

**Rules:**

- Connect every abstract benefit to a concrete action or mechanism.
- Use terse, rhythmic heading clauses above more explanatory mixed-case copy.
- Support openness or interoperability claims with actual tools, formats or workflows.
- Use warmth in support and contact language; retain confidence in the product story.

## Do's and Don'ts

### Do

- Keep the opening at 80px/0.9 with -0.03em tracking and an unmistakably heavy visual weight.
- Keep support copy near 728px wide and separate headline, support and actions by 32px.
- Use the 370×88px cyan action for the main conversion and the 40px-high text-only version in navigation.
- Pair pastel quote surfaces with their own hue-matched dark ink.
- Use 20px gutters for masonry proof and 16px gutters for pricing cards.
- Let 1280px colored panels and a 960px closing container form different scales of enclosure.
- Give product artwork a visible plate, edge or offset shadow so it reads as a useful physical object.
- Keep the final CTA and all footer navigation on one continuous deep teal field.

### Don't

- Do not replace the cool #f7f8f8 canvas with warm beige or a site-wide dark theme.
- Do not make the 12px-corner primary actions fully pill-shaped.
- Do not turn the bright yellow and lavender story fields into translucent gradients or glass cards.
- Do not give every card the pricing-only 20px-blur shadow; most surfaces stay flat or use a hard offset.
- Do not enlarge proof numerals to the 80px headline size; their 32px scale keeps the masonry compact.
- Do not use serif or monospace as general marketing text just because interface specimens contain them.
- Do not force staggered resource cards into a uniform equal-height three-up row.
- Do not end with only a small legal strip or interrupt the teal closing field with a white footer.

## Motion and responsive

### Motion

**Observed:**

- Navigation is fixed and visibly changes from a broad top strip to a smaller floating island while scrolling.
- Wide illustrated story panels use a sticky overlapping composition; selected capability content and media stacks change emphasis through the page.
- No matched action transitions or reusable animation timing declarations are established.

**Transfer:**

- Keep the shrinking navigation and layered story-panel feel; if animation is unavailable, render the panels sequentially and retain the physical-object layering.

**Unknown:**

- Precise scroll thresholds, durations and easing for these scenes.
- Hover, focus-visible and active styling for the main actions.

### Responsive

**Observed:**

- Desktop composition is defined at 1440×900px.
- Styles declare layout boundaries around 810px, 1024px, 1200px, 1280px and 1440px.

**Transfer:**

- On narrow layouts, preserve the centered poster hierarchy and stack the large action pair before compressing their labels.
- Recompose the toybox around the lower edges, keeping decorative plates away from copy. Stack proof and pricing columns in reading order; keep full-width colored chapters and the continuous teal ending.

**Unknown:**

- Exact mobile type sizes, navigation menu design, stacking rules and spacing are not specified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
