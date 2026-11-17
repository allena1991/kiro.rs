# Aaply — clay toys meet workbench

## Overview

A friendly, light software-marketing style where chunky geometric sans headlines meet toy-like collaboration graphics. Pale gray and white provide an uncluttered stage for acid yellow, coral red and electric blue. Rounded modular cards, tactile 3D objects and conversational asides make technical workflows feel sociable rather than corporate; editorial variants use loose black-line illustration instead.

### Essentials

- Headlines behave like illustrated sentences: Poppins 700 at 57px/60px with -1px tracking, interrupted by small avatar clusters, a chat tile, a cursor or a highlighted squiggle.
- The opening is a text-led stage, not a split-screen pitch: a roughly 792px headline sits inside a wider 1128px composition, followed by paired 286×60px pills and the upper portion of a broad product window.
- Actions are soft capsules, never rectangles: main actions use acid yellow with black text and 30px corners; the equally sized secondary action is black with white text.
- Color arrives as bounded punctuation: most of the reading area stays #f2f2f2 or white, while individual 36px-radius cards turn coral or acid yellow and a scalloped blue tile adds a playful interruption.
- Capabilities are numbered exhibits: a 60px outlined circle, a 27px/36px medium-weight title, large tactile imagery and a bottom hairline separating a bold one-word label from an 18px explanation.
- Every new landing page carries tactile punctuation and a shaped graphic tile: use softly beveled objects with bright flat color, and a panel built from repeated capsule lobes; simplified shaded SVG objects are the fallback.
- The closing call changes the atmosphere completely: a full-width black field pairs avatar-chat artwork on the left with a white 52px headline and yellow action on the right, then resolves into a hairline and compact footer.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Acid yellow | `#e6e51e` | `--color-acid` | surface, action, accent, link | Primary conversion pills, highlighted proof panels, selected plans and small graphic accents. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral red | `#f34646` | `--color-coral` | surface, accent | A contrasting capability-card fill and tactile artwork accents. |
| Electric blue | `#466cf3` | `--color-blue` | surface, action, accent | Shaped demonstration tile and tactile graphics; also the paid-plan action on pricing pages. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text, background, border, action | Default typography, outlines, secondary actions and the closing field. |
| Fine gray edge | `#cccccc` | `--color-edge` | border | Login outlines and portrait-card edges. |
| Window gray | `#e6e6e6` | `--color-chrome` | surface, border | Broad browser-window backing and its substantial pale edge. |
| Pale gray canvas | `#f2f2f2` | `--color-canvas` | background | Continuous light page field around all modules. |
| White | `#ffffff` | `--color-white` | surface, text, border | Feature cards, navigation, speech notes and text on dark or colored fields. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Selected billing yellow | `#e7e51e` | `--color-selected-billing` | surface | Selected half of the billing control; retain the main acid yellow elsewhere. |
| pricing pages | Control charcoal | `#1a1a1a` | `--color-control-edge` | border | Billing-selector outline. |

## Typography

- **Poppins** — Headlines, feature-card titles, numbers and editorial statements. Geometric sans with round counters, broad lowercase and a substantial bold cut. Font stack: "Poppins", Arial, sans-serif.
- **Inter** — Body explanations, navigation, calls to action and footer details. Direct, compact sans supporting the rounder display face. Font stack: "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Poppins | 700 | 57px | 60px | -0.0175em | Main promise, page titles and major conversion statements. |
| display-inline | Poppins | 700 | 57px | 1 | -0.0175em | Individually placed headline fragments around inline artwork; maintain the overall display baseline rhythm. |
| closing-heading | Poppins | 700 | 52px | 81px | -0.0192em | White headline in the black closing scene. |
| card-heading | Poppins | 500 | 27px | 36px | normal | Numbered capabilities and the prominent feature list. |
| number | Poppins | 700 | 27px | 42px | -0.074em | Numerals centered within outlined chapter circles. |
| body | Inter | 400 | 18px | 26px | -0.028em | Short explanations inside modular cards. |
| action | Inter | 400 | 18px | 1.55 | normal | Main buttons and navigation links. |
| caption-label | Inter | 700 | 18px | 28px | normal | One-word bottom-row prompts such as Why?, Focus and Friends. |
| closing-body | Inter | 400 | 18px | 28px | normal | Single supporting sentence beneath the closing headline. |
| login | Inter | 300 | 18px | 1.55 | normal | Lightweight login control in navigation. |
| footer-link | Inter | 400 | 15px | 21px | normal | Compact footer navigation. |
| footer-note | Inter | 400 | 15px | 23px | normal | Human signoff and contact details. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | Poppins | 500 | 157px | 243px | normal | Monumental plan amounts with separate small currency and monthly suffix. |
| workflow walkthroughs | chapter-heading | Poppins | 700 | 47px | 52px | normal | Large numbered instruction headings beside speech notes. |
| team and culture pages | culture-heading | Poppins | 700 | 47px | 49px | -0.0213em | Secondary team introduction and inline contact invitation. |
| story and team pages | editorial-statement | Poppins | 500 | 35px | 46px | normal | Story paragraphs presented as statements, and portrait names. |
| pricing pages | plan-title | Poppins | 700 | 35px | 47px | normal | Plan names above prices and comparison columns. |
| pricing pages | plan-body | Poppins | 500 | 23px | 31px | normal | Plan descriptions, bullets and comparison rows. |
| workflow walkthroughs | speech-note | Poppins | 400 | 18px | 26px | -0.028em | Friendly narrator notes in white speech cards. |
| team pages | portrait-caption | Inter | 700 | 18px | 25px | normal | Informal personality descriptions below portraits. |

**Notes:**

- Use geometric Poppins for expressive content and Inter for practical details; do not collapse them into one face.
- Bold is reserved for display promises, instructions and small bottom labels. Most card titles remain medium-weight rather than bold.
- Headlines use tight fixed -1px tracking; body explanations use -0.5px, while controls and footer text remain normally spaced.
- Inline graphics replace pauses in a sentence rather than forming a separate decorative row. No recurring uppercase eyebrow system is used.

## Layout

**Density:** Airy outside modules, comparatively compact within them; long visual pauses separate broad product demonstrations.

### Spacing

| Value | Use |
| --- | --- |
| 10px | Tight action-content and small flex gaps. |
| 15px | Short trailing space after media and compact section variants. |
| 30px | Story-statement bottom spacing. |
| 45px | Heading-to-demonstration section padding. |
| 60px | Control height and compact major section spacing. |
| 75px | Page-introduction and comparison-section bottom padding. |
| 120px | Story-statement top padding and editorial closing clearance. |
| 180px | Long pause beneath full-width walkthrough demonstrations. |

### Containers and grids

- **module stage**: max width 1128px · side padding 156px. At 1440px desktop width, centered full-width feature modules and product scenes sit inside this stage. Treat this as the desktop composition width rather than a universal fixed side margin.
- **navigation stage**: max width 1200px · side padding 120px. Wider inset white navigation shell, with brand left, links in the middle and account actions right.
- **feature mosaic**: 2 columns · gap 24px. Two 552px columns combine full-width modules, unequal-height cards and stacked smaller tiles.
- **editorial text** (only for story and culture pages): max width 851px · side padding 180px. Left-aligned page titles and closing editorial statements; story paragraphs narrow further to roughly 565–639px.
- **portrait grid** (only for team pages): 3 columns · gap 30px. Three portrait cards per desktop row, each 359px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | action capsules | 30px |
|  | feature cards | 36px |
|  | navigation shell | 40px |
|  | product window edge | 45px |
|  | wide action | 50px |
|  | number circles | 50% |
| workflow walkthroughs | speech notes | 16px |
| pricing pages | comparison columns | 40px |
| pricing pages | billing shell | 64px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| miniature product screens | `rgba(0, 0, 0, 0.2) 0px 10px 10px -5px` | Small floating screen objects within product scenes, not marketing-card containers. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous light content field.

**CSS:** `background: #f2f2f2`

#### White module · level 1

**Use:** Default feature-card material.

**CSS:** `background: #ffffff; border-radius: 36px`

**Observed:** Flat, clean white panels are defined by contrast with the gray canvas, not drop shadows.

**Transfer:** Let large imagery and compact copy share the same untextured panel.

#### Coral module · level 1

**Use:** One strongly contrasting capability module.

**CSS:** `background: #f34646; color: #ffffff; border-radius: 36px`

**Observed:** White title, numeral outline and divider sit on a saturated solid fill.

**Transfer:** Use for a single expressive benefit rather than coloring every card.

#### Acid module · level 1

**Use:** A high-impact feature-summary or proof panel.

**CSS:** `background: #e6e51e; color: #000000; border-radius: 36px`

**Observed:** A broad low panel carries a numbered marker, large list and oversized black action.

**Transfer:** Concentrate the strongest product breadth or proof here.

#### Product window · level 1

**Use:** Large demonstration backing.

**CSS:** `background: #e6e6e6; border: 4px solid #e6e6e6; border-radius: 45px`

**Observed:** Pale browser chrome, round corners, tiny colored window dots and a near-white working area frame detailed product content.

**Transfer:** Show a real task or a representative product diagram, not an empty window.

#### Black closing field · level 0

**Use:** Closing invitation and footer.

**CSS:** `background: #000000; color: #ffffff`

**Observed:** Full bleed, square section edges, generous negative space and a thin white separator.

**Transfer:** Create a dramatic final contrast to the light modular content.

#### Scalloped blue tile · level 1

**Use:** A playful demonstration invitation within the feature mosaic.

**CSS:** `background: #466cf3; color: #ffffff`

**Observed:** The 552×340px tile has six rounded lobes along both top and bottom, while the middle remains a solid rectangle.

**Transfer:** Use the capsule-lobe construction for a short interactive invitation; construction is specified under imagery.

## Components

### Navigation

**Use:** Persistent site-level wayfinding.

**CSS:** `position: fixed; top: 0px; height: 81px; width: 1200px; background: #ffffff; border-radius: 40px; z-index: 2000`

**Text style:** `action` — Inter 400 · 18px/1.55

**Observed:** An inset white shell touches the top viewport edge; its upper portion extends offscreen so the lower corners are the visible rounding. Brand at left, four short links centrally, outlined login and compact black signup at right.

**Transfer:** Use your own compact mark and three or four short destination labels.

### Primary button

**Use:** Default conversion action.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 286px; height: 60px; background: #e6e51e; color: #000000; border-radius: 30px`

**Text style:** `action` — Inter 400 · 18px/1.55

**Observed:** Centered text with a simple right arrow where useful; the same yellow action recurs on light and black fields.

**Transfer:** Keep the width generous relative to the short label.

### Secondary button

**Use:** Low-friction trial or demo beside the main action.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 286px; height: 60px; background: #000000; color: #ffffff; border-radius: 30px`

**Text style:** `action` — Inter 400 · 18px/1.55

**Observed:** Equal visual size to the primary hero action rather than a tiny text link.

### Login button

**Use:** Secondary account action in navigation.

**CSS:** `height: 44px; width: 90px; border: 1px solid #cccccc; border-radius: 30px; color: #000000`

**Text style:** `login` — Inter 300 · 18px/1.55

**Observed:** A quiet outlined capsule adjacent to the black signup action.

**States:** Declared: hover color #494949 with solid #cccccc border; focus-visible not specified.

### Number marker

**Use:** Index a capability or a workflow chapter.

**CSS:** `width: 60px; height: 60px; border: 1px solid #000000; border-radius: 50%; display: flex; align-items: center; justify-content: center`

**Text style:** `number` — Poppins 700 · 27px/42px · tracking -0.074em

**Observed:** Placed in a narrow leading rail, separate from the headline. White outline and numeral are used on coral.

### Capability card

**Use:** Explain a benefit as a numbered visual exhibit.

**CSS:** `background: #ffffff; border-radius: 36px; width: 552px`

**Text style:** `card-heading` — Poppins 500 · 27px/36px

**Observed:** Marker and title sit at the top; a large object or diagram occupies the middle; a labeled explanation sits beneath a fine rule. Wide variant spans both mosaic columns and places the object to the right.

**Transfer:** Allow heights to follow the content instead of equalizing every tile.

### Labeled explanation

**Use:** Compact reason or context at a card’s bottom edge.

**CSS:** `border-top: 1px solid #000000; display: grid; grid-template-columns: 120px 1fr; column-gap: 24px`

**Text style:** `body` — Inter 400 · 18px/26px · tracking -0.028em

**Observed:** A bold short prompt sits left of a regular paragraph. The rule spans both columns. On color fields the text and rule invert to white.

**Transfer:** Use caption-label for the prompt and body for the explanation; this is a miniature editorial row, not an eyebrow.

### Wide action

**Use:** Strong onward link beneath a feature list or at a walkthrough’s end.

**CSS:** `width: 520px; height: 96px; background: #000000; color: #ffffff; border-radius: 50px; display: flex; align-items: center; justify-content: center`

**Text style:** `action` — Inter 400 · 18px/1.55

**Observed:** Despite the oversized hit area the label stays at ordinary action size; it occupies almost a whole card column.

### Footer links

**Use:** Navigation and contact beneath the closing scene.

**CSS:** `color: #ffffff; font-size: 15px; line-height: 21px`

**Text style:** `footer-link` — Inter 400 · 15px/21px

**Observed:** Three small link groups near the left-center balance a row of white social marks at the right. A small remote-work signoff and yellow contact link sit below.

**States:** Declared: hover color #c4c4c4; focus-visible not specified.

### Speech note

**Only for:** workflow walkthroughs

**Use:** A friendly narrator beside an instruction.

**CSS:** `background: #ffffff; border-radius: 16px; width: 304px`

**Text style:** `speech-note` — Poppins 400 · 18px/26px · tracking -0.028em

**Observed:** An 80px circular 3D avatar stands just left of the note. The white note is compact and visually separate from the large product demonstration below.

### Portrait card

**Only for:** team pages

**Use:** Introduce people through personality rather than job-title hierarchy.

**CSS:** `width: 359px; border: 1px solid #cccccc; border-radius: 36px`

**Text style:** `editorial-statement` — Poppins 500 · 35px/46px

**Observed:** Name at top, 320px square illustrated portrait in the middle, thin divider and a bold compact personality caption beneath. No white fill is needed against the gray canvas.

### Billing selector

**Only for:** pricing pages

**Use:** Switch between billing periods.

**CSS:** `width: 316px; height: 66px; border: 1px solid #1a1a1a; border-radius: 64px`

**Text style:** `action` — Inter 400 · 18px/1.55

**Observed:** Two centered options in one outline; the selected half is a 152×60px yellow capsule. A small red discount badge sits outside the control to the right; it is not part of the selection track.

## Imagery and graphics

### Tactile inline punctuation

**Use:** In the opening headline and selected short statements.

**Observed:** Small glossy clay-like avatar heads overlap in colored discs; a red rounded square contains a yellow chat symbol, and a bright cursor has a thick pale beveled edge. A black wavy arrow is backed by a broad acid-yellow highlight. Objects are roughly cap-height and sit inside the reading line.

**Transfer:** Create product-relevant punctuation using a small shaded object, a colored disc cluster and a hand-drawn arrow. Minimum acceptable version is rounded SVG geometry with an offset light edge and subtle inner highlight, not flat stock emoji.

**Build:** For the wave, draw a smooth SVG path with three alternating peaks and rounded caps; duplicate it beneath at a much wider stroke in acid yellow, then add a narrow black stroke and arrowhead. For the cursor use a rounded triangular path, a pale outer extrusion and a saturated inner face. Keep the geometry at text-line scale.

### Toy product objects

**Use:** Large feature-card illustrations and collaboration scenes.

**Observed:** Softly rounded off-white phone sculptures, chunky controls, small red hearts, bright avatar discs and glossy red, blue and yellow cursor/name pairs. Objects have gentle bevels, soft studio light and short contact shadows; they fill roughly half a wide card without a photographic environment.

**Transfer:** Model a few simple objects relevant to the product, with off-white bodies and one or two highly saturated details. A carefully shaded SVG or layered CSS object with rounded contours is sufficient if 3D production is unavailable.

**Build:** Layer rounded off-white rectangles with shallow gray offsets, small dark control slots and saturated capsule controls. Use white translucent inset highlights along upper edges, soft dark lower-edge shading and short blurred contact shadows. Float two or three colored pointers and rounded name chips around the main form; avoid perspective-heavy scenes.

### Capsule-lobe artwork

**Use:** The shaped blue invitation tile and playful abstract media accents.

**Observed:** Repeated vertical capsule forms merge into one field; six equal lobes make the top and bottom of the blue panel scalloped. Elsewhere mustard-yellow rounded ribbon forms sit beside red and white cards.

**Transfer:** Preserve at least one shaped panel as a recognizable counterpoint to normal rounded rectangles, using a product invitation or proof highlight.

**Build:** For a 552×340px blue tile, place six adjacent 92px-wide full-height capsules with 46px ends behind a rectangle spanning the central 248px of height. Merge the fill, then overlay title, a fine white rule, support copy and a white action. Scale the geometry as one SVG mask or background layer.

### Product demonstrations

**Use:** Broad overview after the opening and large panels in detailed walkthroughs.

**Observed:** Near-white product boards show miniature screens, connecting paths, light colored group regions and collaborator avatars, inside pale gray rounded browser chrome. Detailed walkthrough images span about 1131px and are roughly 634px tall; the demonstrations dominate each chapter.

**Transfer:** Use authentic interface imagery centered on a single task. If no interface exists, build a legible board of representative product objects linked by thin paths; keep internal UI details secondary to the composition.

### Conversation closing artwork

**Use:** Left half of the dark closing scene.

**Observed:** Staggered dark-gray chat bubbles alternate sides with circular colorful 3D avatars. The bubbles and heads form a tall loose column rather than a conventional testimonial card; varied brightness gives depth against black.

**Transfer:** Use short fictional conversational fragments only as illustrative UI, not as attributed customer proof. Simplified circular faces and SVG bubbles preserve the effect without elaborate artwork.

**Build:** Arrange an approximately 500px-wide column of pill-like speech shapes with one lower corner squared off. Alternate 84px avatar discs left and right. Fill bubbles with low-opacity white over black and use soft white text; vary opacity between rows while retaining a clear reading hierarchy. Keep the invitation beside, not inside, the bubble column.

### Hand-drawn editorial scenes

**Only for:** story and culture pages

**Use:** Narrative interludes and illustrated team portraits.

**Observed:** Loose black pen lines, pencil grain, elongated people, mischievous dark creatures and scribbled knots are punctuated by sharp acid-yellow shapes and occasional pale-blue device screens. Story scenes span about 1161px without a rectangular backdrop; team versions fit square portrait spaces.

**Transfer:** Commission or draw small visual metaphors for the product’s friction and relief. Keep backgrounds open and nearly all marks monochrome; use a few yellow sparks rather than colored scenery.

**Build:** Use irregular black SVG strokes, restrained crosshatching or a subtle grain mask, scribble loops and isolated angular yellow patches. Compose two or three character/object vignettes across the width with no enclosing frame.

### Cropped plan characters

**Only for:** pricing pages

**Use:** Add personality to otherwise numeric subscription cards.

**Observed:** Enormous smooth 3D heads with saturated orange or purple hair enter from the right and bottom edges of white and acid-yellow plan cards; their faces are deliberately clipped by the panel.

**Transfer:** Use one friendly object or character per plan, clipped behind rather than over the price and benefit text. Preserve the dramatic scale contrast with the small plan heading.

### Icons

**Observed:** Navigation uses a thin 15×10px right arrow. Footer social silhouettes are white, predominantly 32px with optical-size variations. Decorative cursor and chat graphics are tactile illustrations rather than a consistent outline icon set.

**Transfer:** Use simple recognizable monochrome social marks and thin directional arrows for utility; reserve volume and saturated color for expressive inline objects.

## Section recipes

How recurring sections are built.

### First screen: Illustrated sentence opening

**Observed:** A light gray canvas sits beneath the fixed white Navigation shell. The 57px bold headline begins well below it, around 169px from the top, and spans about two thirds of the module stage in four compact lines. Avatar discs interrupt the first line, a chat tile the second, a cursor the next, and a highlighted wave closes the last line. The whole text-and-object sentence is left-aligned within the stage, inset farther than the product window below. Primary button and Secondary button sit side by side 68px below the headline. A broad Product window begins at roughly 622px and occupies the lower part of the first 900px; only its upper working area is visible above the fold. There is no separate hero support paragraph. Back-to-front layers are Canvas, sentence typography, inline tactile objects, actions, then the following product scene.

**Transfer:** Write a similarly compact promise and break it deliberately around two or three product-relevant symbols plus a highlighted wave. Without interface media, show a representative task board in the Product window. Workflow pages instead open with a left-aligned display title followed by the first numbered instruction; pricing centers a short title over billing controls and two plans; culture pages use a simple left-aligned title or editorial statement.

**Avoid:** Do not turn this into a centered headline above a detached row of emoji, a half-width illustration split, or a hero with several dense support paragraphs. Do not put all of the large product window above the actions.

**Text style:** `display` — Poppins 700 · 57px/60px · tracking -0.0175em

### Numbered feature mosaic

**Observed:** White module panels form a two-column Feature mosaic. A full-width opening card combines Number marker, card-heading, a large Toy product object to the right and a Labeled explanation below. Subsequent modules alternate coral and white, vary in height and combine the Scalloped blue tile with a tall collaboration card.

**Transfer:** Use a small family of related benefits with mixed visual weights; the number of cards follows the product story, not a fixed template.

**Text style:** `card-heading` — Poppins 500 · 27px/36px

### Bright breadth panel

**Observed:** An Acid module spans 1128px. Number marker occupies the upper-left rail, while a prominent bulleted capability list occupies the right half. A Labeled explanation anchors the lower left and a Wide action anchors the lower right.

**Transfer:** Collect breadth, outcomes or included capabilities in one saturated proof moment. Keep the list readable and the bottom row balanced.

**Text style:** `card-heading` — Poppins 500 · 27px/36px

### Conversation closing and footer

**Observed:** Black closing field spans the viewport and is 1088px tall in the desktop composition. Conversation closing artwork fills the left side; the right-hand headline sits 277px into the section with a single support sentence 8px below its line box and a Primary button below. A 1080px thin white rule separates the roomy invitation stage from the compact footer, with Footer links, a small mark, social silhouettes, contact signoff and rights note.

**Transfer:** Carry the dark conversational closing into new pages, adapting the invitation to the actual offer. Use the artwork as a sociable counterweight, not as unverified customer quotations.

**Text style:** `closing-heading` — Poppins 700 · 52px/81px · tracking -0.0192em

### Narrated workflow chapter

**Only for:** workflow walkthroughs

**Observed:** A Number marker at left precedes a 47px bold multi-line instruction. An avatar and Speech note balance it on the right. After 45px of section padding, a wide Product demonstration follows; most chapters leave 180px beneath their media before the next instruction.

**Transfer:** Build repeatable task chapters around actual user decisions. End the walkthrough with a celebratory result scene and a Wide action, then use the shared dark closing.

**Text style:** `chapter-heading` — Poppins 700 · 47px/52px

### Plans and open comparison

**Only for:** pricing pages

**Observed:** Centered display title and Billing selector introduce paired white and yellow plan cards. Plan names are 35px bold; price numerals reach 157px while currency and monthly suffix remain separate smaller elements. Large clipped character heads occupy the right sides. The free plan uses a yellow action and the paid plan a blue action. A second centered heading and 23px support lead into an open label column beside tall white and yellow comparison columns with 40px corners, aligned plus signs and final action pills.

**Transfer:** Make price the dominant datum, keep features aligned without spreadsheet cell boxes, and distinguish the upgraded plan by a broad colored column rather than a tiny badge.

**Text style:** `price` — Poppins 500 · 157px/243px

### Illustrated editorial story

**Only for:** story pages

**Observed:** A long 57px bold opening statement leads into wide open-backed line illustrations. Later 35px medium statements sit in a narrower left column, with 120px top and 30px bottom padding before broad imagery. A final bold statement and yellow action conclude the light narrative before the shared dark closing.

**Transfer:** Alternate concise ideas with visual metaphors rather than turning the story into a small-text article.

**Text style:** `editorial-statement` — Poppins 500 · 35px/46px

### Personality wall and inline invitation

**Only for:** team pages

**Observed:** A display title and 47px secondary statement precede a three-column Portrait card grid. After the wall, a bold multiline invitation uses a conspicuously underlined contact phrase and inserts a yellow capsule action directly into the next sentence.

**Transfer:** Show personality through custom portraits and short human descriptions. Let the contact invitation behave like expressive typography rather than a separate form.

**Text style:** `culture-heading` — Poppins 700 · 47px/49px · tracking -0.0213em

## Page flow

**Storyline:** Promise → visible product or people → explanatory chapters → breadth or resolution → invitation → conversational dark closing.

### Product landing page that makes a complex tool approachable

1. **Promise** — Illustrated sentence and paired signup/demo pills.
2. **Product demonstration** — Large pale browser board with connected screens.
3. **Capability chapters** — Numbered mixed-height feature mosaic with tactile objects and bottom explanations.
4. **Breadth** — Bright yellow list panel and wide onward action.
5. **Closing call** — Dark avatar conversation, invitation and compact footer.

**Transfer:** Move from a tangible promise to a tangible task, then group benefits into a lively but coherent mosaic.

### Humanize a team and invite contact

1. **Introduction** — Simple page title followed by a bold informal team statement.
2. **People** — Illustrated three-column personality wall.
3. **Invitation** — Large inline contact sentence with embedded action.
4. **Closing call** — Shared dark conversation and footer.

**Transfer:** Replace corporate biography density with distinctive portraits and one memorable personal line per person.

### Teach a workflow through visible progress

1. **Promise** — Compact display title with highlighted wave.
2. **Capability chapters** — Repeated numbered instructions, avatar notes and broad product demonstrations.
3. **Resolution** — Celebratory completion image and wide demo link.
4. **Closing call** — Shared dark conversation and footer.

**Transfer:** Give every chapter a clear action and visible result; let the product image do most of the explaining.

### Help readers compare a simple subscription choice

1. **Pricing** — Centered title, billing toggle and two expressive plan cards.
2. **Comparison** — Centered heading and open feature-label column against two rounded plan columns.
3. **Closing call** — Shared dark conversation and footer.

**Transfer:** Use the oversized numeral and strong plan fill to clarify the choice, then answer inclusion questions in aligned rows.

### Explain the motivation behind a product

1. **Motivation** — Long bold wish-and-friction opening statement.
2. **Narrative chapters** — Medium-weight statement paragraphs alternate with wide hand-drawn metaphor scenes.
3. **Resolution** — Bold product-resolution statement and yellow trial action.
4. **Closing call** — Shared dark conversation and footer.

**Transfer:** Tell an origin through a few illustrated ideas and resolve with a practical invitation, not a chronology of milestones.

## Writing

Warm, slightly mischievous and openly collaborative. The voice explains real workflow friction in everyday language, with confident benefits and informal asides rather than enterprise grandiosity.

**Do not copy:** Do not reuse the Aaply name, logo, character artwork, exact product counts, prices, capability claims, team identities, origin claims or attributed quotations. Source copy examples illustrate tone only; write new claims grounded in the new product.

- **Addressing the reader:** Speak directly to you and your team. Use we for the makers and our for a shared invitation; the product is a helpful tool rather than an impersonal platform.
- **Rhythm:** Benefit headings are often long enough for two to four short lines. Explanations are one or two plain sentences; lists stay terse. Friendly questions, contractions, parentheses and occasional exclamation marks break up instructional passages.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Promise | Name the audience and practical creation outcome in one sentence. | About 12–18 words | “Tool that helps teams design mobile apps and create a human-centered product experience” |
| Benefit heading | Lead with a concrete verb and describe the work made easier. | About 6–14 words | “Ready-made templates for rapid iterating”<br>“Get the full helicopter view” |
| Supporting explanation | Recognize a familiar problem, then explain the relief without jargon. | One or two sentences | “We all know the problem of endless design edits. We made it possible to manage low poly wireframes. It's faster and more convenient.” |
| Narrator aside | A friendly colleague reacts to the reader’s next step. | One short conversational remark | “Let’s get it started!”<br>“Wow! We planned the whole app so quickly even without UI design.” |
| Action | Short verb-led invitation with low commitment. | Two to four words | “Try demo project”<br>“Join beta!” |
| Closing invitation | Offer belonging and early access, with a short benefit underneath. | A short headline plus one sentence | “Join the early birds”<br>“Be the first to try — and get something special!” |

**Words and phrasing to use:** try; create; collaborate; your team; let’s; Why?; in one place; get the whole picture

**Avoid:** enterprise-grade transformation; revolutionary ecosystem; unlock synergies; best-in-class; impersonal feature inventories

**Rules:**

- Describe the next useful action before discussing technical implementation.
- Make bottom-row captions sound like small editorial prompts: Why?, Focus, Friends.
- Let personality appear in a brief aside, not in every sentence.
- Use concrete tasks and outcomes rather than unsupported superlatives.
- Keep instructions human enough to sound spoken by a helpful teammate.

## Do's and Don'ts

### Do

- Keep the main promise at 57px Poppins 700 with -1px tracking and inline graphic interruptions.
- Use paired 286×60px yellow and black action capsules in a product-led opening.
- Combine 552px feature columns into full-width 1128px moments.
- Set numbered feature titles at 27px/36px, weight 500, rather than using display weight everywhere.
- Preserve the 60px outlined number rail and the bottom label-plus-explanation device.
- Include a capsule-lobe graphic panel and tactile punctuation in each new landing-page composition.
- Keep most content on gray and white, concentrating saturated color in selected bounded panels.
- Resolve the page with the black conversation scene and compact 15px footer links.

### Don't

- Do not give all marketing cards the product-screen shadow; the white modules are flat.
- Do not replace the capsule geometry with sharp or 8px-rounded buttons.
- Do not use acid yellow as the continuous light-page background; it belongs to actions and selected large panels.
- Do not make all feature titles 700 weight; their 500 weight provides a characteristic softer middle tier.
- Do not turn comparison rows into a dense bordered spreadsheet; the plan columns are broad continuous fills.
- Do not mix the hand-drawn culture illustrations into every ordinary product card; the default artwork is tactile and toy-like.
- Do not enlarge action labels in proportion to the 520×96px wide action; retain the 18px recipe.
- Do not replace the black closing with a pale generic newsletter form or a footer-only strip.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare background-color, color and border-color transitions of 0.2s ease-in-out; some also include box-shadow at the same timing.
- Footer links declare 0.3s ease-in-out transitions and a gray hover color.
- The compact black navigation signup declares a yellow background and border with black text on hover.
- No matched running animation establishes a reliable loop duration.

**Transfer:**

- Keep button feedback restrained so the vivid shape and color remain the main affordance.
- Treat the inline art, pointers and staggered conversation as composed scenes; motion must not disrupt the headline’s reading order.

**Unknown:**

- Exact entrance sequencing, scroll choreography and chat-bubble fade timings are not established.

### Responsive

**Observed:**

- Styles declare width boundaries at 479/480px, 639/640px, 959/960px and 1199/1200px.

**Transfer:**

- On narrow layouts, preserve the illustrated sentence as readable text flow rather than shrinking the entire desktop artboard.
- Stack the feature columns and keep the number marker adjacent to its title; move oversized objects below text if necessary.
- Stack the conversation artwork and closing invitation while retaining the black field and yellow action.

**Unknown:**

- Mobile font sizes, navigation transformation and actual breakpoint-specific placement are not established; the transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
