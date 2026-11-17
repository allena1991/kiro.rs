# Zapier — pastoral systems editorial

## Overview

A warm, capable software style that pairs friendly, tightly fitted grotesk headlines with literary serif explanations and testimonials. Cream and putty canvases, near-brown black, and concentrated orange accents surround interfaces staged against blurred landscapes and soft daylight. The spacious marketing composition gives way to compact ruled diagrams and practical comparison tables, making complex products feel usable rather than futuristic.

### Essentials

- Headlines sound conversational but fit like display lettering: Degular Display 56px/1 at weight 500 for the opening, 48px/1 for section leads, with normal tracking; explanatory feature titles switch to Serrif 28px/1.25 at weight 300.
- The opening is an invitation above a landscape-backed demonstration: centered 768px headline, 640px support line, paired 40px actions, then a 1024×576px media stage separated by 40px.
- Orange is punctuation, not the canvas: #ff4f00 marks primary actions, selected phrases, short rectangular eyebrow marks and proof numerals; cream #fffefb, #f8f4f0 and putty #eceae3 occupy most of the page, interrupted by dark proof and closing bands.
- Buttons have two personalities, not one universal pill: content actions use 4px corners and 40px or 48px heights; only the compact navigation conversion uses an 18px radius and 36px height.
- Product logic sits in atmospheric daylight: crisp cream interface panels float over blurred green, olive, blue and peach scenery, sometimes with a faint square grid. Every landing page includes this contrast; without product artwork, stage a simple connected process diagram on the same soft backing.
- Proof reads like an editorial spread: 40px/1.08 light serif quotations beside a large square or portrait atmospheric image, 1px rules, and orange 48px numerals. Preserve this serif-and-rule device with a verified outcome or concise editorial statement when customer material is unavailable.
- A dark closing invitation resolves the story: #201515 band, centered 48px display line with a short orange phrase, a 16px/1.5 support sentence and compact actions; the light, utilitarian footer returns immediately beneath it.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff4f00` | `--color-orange` | accent, action, text, border | Conversion fills, isolated display phrases, proof figures and small graphic marks. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Warm paper | `#fffefb` | `--color-canvas` | background, surface, text | Default canvas, pale panels and inverse text. |
| Cream wash | `#f8f4f0` | `--color-wash` | background, surface, text | Feature chapters, FAQ groups and pale text on olive-charcoal sections. |
| Putty | `#eceae3` | `--color-putty` | background, border | Proof and assurance bands, faint separators and unfilled slider tracks. |
| Fine warm rule | `#dfdcd2` | `--color-fine-rule` | border, accent | Feature separators and dots on technical backings. |
| Taupe outline | `#c5c0b1` | `--color-outline` | border, surface | Proof-card edges, plan borders, input outlines and muted social circles. |
| Stone gray | `#939084` | `--color-faint-text` | text, border | Small feature eyebrows and secondary diagram rules. |
| Warm gray | `#605d52` | `--color-muted` | text, border | Supporting labels, captions and secondary copy. |
| Olive charcoal | `#36342e` | `--color-charcoal` | text, background, border | Secondary dark text, outlined diagrams and dark platform sections. |
| Brown black | `#201515` | `--color-ink` | text, background, border, action | Primary text, strong rules, dark buttons and closing bands. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| enterprise and audience-specific pages | Deep moss | `#32372c` | `--color-moss` | background | Olive-green alternative to the brown-black testimonial band and the lead-generation band. |
| interactive spectrum explanations | Progress blush | `#f0d0db` | `--color-slider-blush` | accent | First pale transition of the orange-to-violet progress rail. |
| interactive spectrum explanations | Progress pink | `#dea4c8` | `--color-slider-pink` | accent | Second transition of the progress rail. |
| interactive spectrum explanations | Progress violet | `#6558e6` | `--color-slider-violet` | accent | Far end of the progress rail, not a general link color. |

## Typography

- **Degular Display** — Opening and major section headlines. Soft, closely fitted display grotesk with a large x-height and personable rounded forms. If unavailable, use **DM Sans**. Use weight 500; balance line breaks to maintain the compact silhouette. Font stack: "Degular Display", "DM Sans", Inter, system-ui, sans-serif.
- **Inter** — Body copy, actions, navigation, labels and data. Plain, highly legible sans-serif that stays unobtrusive next to the display and serif voices. Font stack: "Inter", system-ui, sans-serif.
- **Serrif** — Feature titles, explanations and customer quotations. Light, high-contrast editorial serif with delicate joins and tightly spaced large settings. If unavailable, use **Newsreader**. Use weights 200–300 and preserve negative tracking. Font stack: "Serrif", "Newsreader", Georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Degular Display | 500 | 56px | 1 | normal | Default centered opening headline. |
| heading | Degular Display | 500 | 48px | 1 | normal | Major section and closing headings, including orange inline emphasis. |
| proof-number | Inter | 500 | 48px | 1.04 | normal | Orange outcomes beneath the light proof quotation. |
| editorial-heading | Serrif | 300 | 40px | 1.1 | -0.03em | Concept explanations above interactive diagrams. |
| quote-dark | Serrif | 200 | 40px | 1.08 | -0.04em | Editorial quotation on dark bands. |
| quote-light | Serrif | 300 | 40px | 1.08 | -0.04em | Quotation within a bordered proof spread. |
| feature-heading | Serrif | 300 | 28px | 1.25 | -0.015em | Narrow-column feature chapter titles. |
| card-heading | Inter | 600 | 20px | 1.25 | -0.025em | Plan names, resource titles and FAQ questions. |
| body | Inter | 400 | 16px | 1.5 | normal | General paragraphs and supporting section text. |
| body-small | Inter | 400 | 14px | 1.5 | normal | Opening support line, feature descriptions and captions. |
| footer-heading | Inter | 500 | 14px | 24px | normal | Footer group headings and utility navigation. |
| footer-link | Inter | 400 | 14px | 24px | normal | Footer directory and secondary links. |
| eyebrow | Inter | 400 | 12px | 1.5 | 0.04em, uppercase | Centered section labels and trust-strip titles. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | pricing-display | Degular Display | 500 | 80px | 1 | normal | Left-aligned commercial opening. |
| pricing pages | platform-display | Degular Display | 500 | 80px | 0.9 | normal | Oversized platform diagram introduction on charcoal. |
| audience-specific pages | audience-display | Degular Display | 500 | 64px | 1 | normal | Wide centered audience-specific opening headline. |
| pricing pages | price | Inter | 500 | 36px | 1.5 | -0.019em | Price or short sales-contact phrase within plan columns. |

**Notes:**

- Keep display headlines at normal tracking rather than imposing a generic negative-tracking rule. Their fitted quality comes from the family and balanced line breaks.
- Serif feature titles are smaller than the sans section leads; large serif quotations carry the emotional weight. Do not substitute bold sans for every heading role.
- Tracking tightens on the large serif settings to -0.04em, while uppercase labels open to 0.04em or 0.05em. Use Inter numerals, not the display family, for proof.
- The default opening is 56px, not the pricing variant's 80px. No viewport-relative type scale is prescribed.
- Feature eyebrows use Inter 12px, weight 400, normal line height, 0.05em tracking and uppercase. Audience trust statements use Serrif 48px, weight 200, normal line height and -0.04em tracking; their statistical figures use Inter 80px, weight 400, normal line height and -0.025em tracking.

## Layout

**Density:** Airy sections with compact controls and ruled information groups; large media stages carry detail rather than dense surrounding prose.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Small label-to-detail and figure-to-caption gaps. |
| 12px | Stacked feature-button separation and small text grouping. |
| 16px | Heading-to-support gap, paired actions and small card gutters. |
| 20px | Outer section side padding and form row gaps. |
| 24px | Opening headline-to-support gap, common card padding and grid gutters. |
| 32px | Opening support-to-action gap and label-to-feature-title spacing. |
| 40px | Opening actions-to-media gap; quotation-to-attribution spacing. |
| 48px | Section header-to-grid gap and testimonial columns. |
| 64px | Inner top and bottom spacing inside the ruled dark quotation spread. |
| 80px | Feature text/media column gap. |
| 96px | Default major band vertical padding. |
| 120px | Expanded feature and concept chapter vertical padding. |

### Containers and grids

- **Main container**: max width 1280px · side padding 20px. Centered chapter container; at 1440px it leaves 80px margins.
- **Opening text**: max width 768px · side padding 20px. Centered two-line opening headline; support is constrained separately to 640px.
- **Opening media**: max width 1024px. Centered 16:9 demonstration beneath opening actions.
- **Feature split**: max width 1280px · 2 columns · gap 80px. Asymmetric 1fr 2.25fr split: about 369px text beside 831px media.
- **Three-column cards**: max width 1280px · 3 columns · gap 24px. About 411px per resource or capability card.
- **FAQ container**: max width 1024px · side padding 20px. Narrower question groups centered under the section heading.
- **Footer container**: max width 1200px · side padding 20px. Utility rows and optional directory columns inset beyond the main content.
- **Plan comparison** (only for pricing pages): max width 1280px · 4 columns · gap 0px. Four adjoining columns with shared hairlines, rather than separated floating cards.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Content actions and fields | 4px |
|  | Navigation conversion | 18px |
| interactive spectrum explanations | Concept selector cards | 12px |
| FAQ sections | FAQ groups | 16px |
| enterprise lead generation | Lead form panel | 6px |
| audience-specific integration showcases | App logo tiles | 10px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| audience-specific integration showcases | Logo tile lift | `0px 5px 10px 0px rgba(0, 0, 0, 0.1)` | Small square app tiles only; page cards otherwise rely on rules. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page background.

**CSS:** `background-color: #fffefb; color: #201515`

#### Cream chapter · level 0

**Use:** Feature chapters and comparison sections.

**CSS:** `background-color: #f8f4f0`

**Observed:** Full-width flat warm wash, without depth effects.

**Transfer:** Use a tonal change to collect related explanations.

#### Putty proof band · level 0

**Use:** Outcome spreads and assurance content.

**CSS:** `background-color: #eceae3`

#### Brown-black band · level 0

**Use:** Editorial quotation and closing invitation.

**CSS:** `background-color: #201515; color: #fffefb`

#### Ruled panel · level 1

**Use:** Light editorial proof and comparison content.

**CSS:** `border: 1px solid #c5c0b1; border-radius: 0px; box-shadow: none`

**Observed:** The surrounding band shows through; divisions organize the content without a raised-card effect.

**Transfer:** Use shared edges to make related evidence read as a single spread.

#### Technical dot field · level 1

**Use:** Backing for a controls diagram.

**CSS:** `background-color: #f8f4f0; background-image: radial-gradient(#dfdcd2 1px, rgba(0, 0, 0, 0) 0px); background-size: 8px 8px; border: 1px solid #201515`

**Observed:** Very low-contrast dots sit inside a sharply outlined rectangular panel.

**Transfer:** Put meaningful labels and connections over the field; it is not empty decoration.

#### Charcoal platform band · level 0

**Only for:** commercial platform and audience capability sections

**Use:** Denser technical explanations.

**CSS:** `background-color: #36342e; color: #fffefb`

**Observed:** Ruled diagrams on commercial pages; pale translucent feature tiles on audience pages. The latter use rgba(255,254,251,0.1), visually a warmer, lighter charcoal.

**Transfer:** Keep the dark olive cast rather than using blue-black.

#### Moss invitation · level 0

**Only for:** enterprise and audience-specific pages

**Use:** Lead-generation and customer-story alternative.

**CSS:** `background-color: #32372c; color: #fffefb`

## Components

### Navigation

**Use:** Persistent compact site navigation.

**CSS:** `height: 56px; position: sticky; top: 0px; z-index: 1000; display: flex; justify-content: space-between; align-items: center; padding: 0px 40px; background-color: #fffefb; border-bottom: 1px solid #eceae3; font-family: Inter, system-ui, sans-serif; font-size: 14px; font-weight: 400; line-height: normal`

**Observed:** Logo and category triggers sit left; utility links and conversion sit right. Small downward chevrons accompany expandable labels; navigation triggers use 6px 10px padding.

### Primary button

**Use:** Opening conversion and most important next step.

**CSS:** `display: flex; align-items: center; justify-content: center; background-color: #ff4f00; color: #fffefb; border: 1px solid #ff4f00; border-radius: 4px; padding: 8px 16px; height: 40px; gap: 4px; font-family: Inter, system-ui, sans-serif; font-size: 16px; font-weight: 600; line-height: normal`

**Observed:** Default compact content action. Larger proof and closing actions use 48px height, 12px 24px padding and the action-large recipe.

**Transfer:** Use one dominant orange action per action group.

### Secondary button

**Use:** Alternative starting route or supporting conversion.

**CSS:** `display: flex; justify-content: center; align-items: center; background-color: transparent; color: #201515; border: 1px solid #201515; border-radius: 4px; height: 40px; padding: 8px 16px; font-family: Inter, system-ui, sans-serif; font-size: 16px; font-weight: 600; line-height: normal`

**Observed:** Pairs with a filled action; feature-column versions span the text-column width. The dark-band alternative uses a paper-colored border and text at 48px height.

### Dark button

**Use:** Feature exploration and comparison actions.

**CSS:** `background-color: #201515; color: #fffefb; border: 1px solid #201515; border-radius: 4px; height: 48px; padding: 12px 24px; display: flex; justify-content: center; align-items: center; gap: 6px; font-family: Inter, system-ui, sans-serif; font-size: 18px; font-weight: 600; line-height: normal`

**Observed:** Solid brown black rather than charcoal. Narrow feature columns use a 40px variant with the action recipe; plan cards use full-width buttons.

### Navigation signup

**Use:** Small conversion at the end of the header.

**CSS:** `background-color: #ff4f00; color: #fffefb; border: 1px solid #ff4f00; border-radius: 18px; height: 36px; padding: 6px 12px; font-family: Inter, system-ui, sans-serif; font-size: 14px; font-weight: 600; line-height: normal`

**Observed:** The conspicuous pill exception to rectangular content buttons.

### Proof card

**Use:** Customer quotation with quantified outcomes.

**CSS:** `border: 1px solid #c5c0b1; border-radius: 0px; display: flex; flex-direction: column; box-shadow: none`

**Text style:** `quote-light` — Serrif 300 · 40px/1.08 · tracking -0.04em

**Observed:** Logo, quotation mark, large serif quote and attribution form the upper portion; a ruled bottom area holds two orange outcomes and their captions. A separate image of matching width sits beside the card, with 24px between them.

**Transfer:** Keep the quotation dominant and use only a few verified outcomes.

### Assurance matrix

**Use:** Compact collection of trust or reliability properties.

**CSS:** `background-color: #f8f4f0; border: 1px solid #201515; display: grid; grid-template-columns: repeat(5, 1fr); border-radius: 0px; overflow: hidden`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Five contiguous columns separated with 1px dark rules. Each has a small icon high in the cell and title plus muted caption near the bottom. A connected technical-controls panel can continue below it.

**Transfer:** Translate to a small set of product assurances; keep the table-like shared edges.

### Utility footer

**Use:** Final site utilities after the last content band.

**CSS:** `background-color: #fffefb; border-top: 1px solid #eceae3; padding: 40px 20px; color: #36342e`

**Text style:** `footer-link` — Inter 400 · 14px/24px

**Observed:** A 1200px inner container carries muted circular social icons left and a compact link row right, then a small logo left and legal links right. The expanded directory variant adds an alphabet index and five unboxed link columns above these rows; the compact footer is 169px tall.

**Transfer:** Use the compact ending by default for focused pages; reserve the expanded directory for a broad catalog.

### FAQ item

**Only for:** FAQ sections

**Use:** Practical objection handling.

**CSS:** `border-bottom: 1px solid #eceae3`

**Text style:** `card-heading` — Inter 600 · 20px/1.25 · tracking -0.025em

**Observed:** Native details/summary construction. Summary uses 24px padding and a plus aligned to the right; the closed row is 74px tall. Items sit in a cream group with 16px outside corners; answers use body text. A category title sits outside each group.

**Transfer:** Group related questions rather than putting every item in its own rounded card.

### Plan card

**Only for:** pricing pages

**Use:** Side-by-side commercial comparison.

**CSS:** `background-color: #fffefb; border: 1px solid #c5c0b1; padding: 28px; border-radius: 0px; display: grid`

**Text style:** `card-heading` — Inter 600 · 20px/1.25 · tracking -0.025em

**Observed:** Name, price, brief description, full-width Dark button, then checked feature list. Four columns adjoin with collapsed-looking borders; align action rows despite differing copy lengths. Price uses the price recipe.

**Transfer:** Keep tiers comparable and neutral rather than floating one giant highlighted plan.

### Form field

**Only for:** enterprise lead generation

**Use:** Text inputs, selects and longer qualification responses.

**CSS:** `background-color: #fffefb; border: 1px solid #c5c0b1; border-radius: 4px; padding: 8px 12px`

**Text style:** `body` — Inter 400 · 16px/1.5

**Observed:** Single-line fields are 48px tall; textarea is 138px tall. Labels sit 8px above. A 592px paper panel with 6px corners and 32px 24px 24px padding collects the fields; paired short fields use 20px gaps, and the submit button spans the panel.

**Transfer:** Pair the light form with a dark moss explanation column; do not turn the whole page into an application form.

## Imagery and graphics

### Atmospheric product stage

**Use:** Signature opening demonstration and recurring feature media.

**Observed:** Crisp pale interface fragments sit over defocused landscapes: dark green corners, olive and straw middle tones, cool blue bands and peach daylight. The opening uses a 1024×576px rectangle; feature demonstrations occupy an 831×587px stage beside much narrower copy. Some stages add a faint grid, floating assistant cards, thin connector lines or a centered notification. Media is rectangular and only subtly rounded, never a glossy device mockup.

**Transfer:** Stage a meaningful portion of the new product at readable scale. If no interface exists, use a small set of cream task panels connected into one clear process; retain the atmospheric backing and ample separation.

**Build:** Use an overflow-hidden rectangular stage. Layer broad blurred diagonal ellipses in dark olive, sage, straw, dusty blue and peach, with a pale translucent veil. Make each field at least half the stage width and blur it by 60px–100px so no hard gradient boundary remains. Overlay a very faint paper-grain texture; optionally add 1px paper lines at 24px intervals at low alpha. Place a sharp paper UI panel above, offset from center, with one smaller overlapping annotation. These are construction guidelines; match the daylight softness rather than exact gradient stops.

### Atmospheric customer plate

**Use:** Image half of the editorial proof spread.

**Observed:** A square green motion-blurred landscape carries a centered white customer wordmark; a portrait-format sky-and-cloud plate carries another. These are saturated enough to contrast with the putty background but remain soft and photographic, without hard illustrative edges.

**Transfer:** Use licensed landscape or context photography with a restrained identifying mark; without customer art, pair the editorial statement with a softly blurred scene relevant to the product.

**Build:** Fill a square or portrait frame with a landscape or sky image. Use directional blur for green scenes, or retain soft cloud edges for blue scenes. Keep the identifying text sharp, white and centered above the image.

### Workflow-and-people collage

**Only for:** audience-specific pages

**Use:** Large use-case chapters and the audience opening.

**Observed:** Wide pale lavender or putty fields combine cropped office photography with a large flat workflow editor and overlapping conversational cards. Photography is warm, naturally lit and candid: people on calls, at laptops or collaborating. Product panels cover most of the field; photos anchor opposite corners rather than becoming full-width stock-photo banners.

**Transfer:** Show the new user's work context alongside a simplified product sequence. Keep one main UI plane and at most two supporting fragments, with photographed edges still visible.

### Technical connection diagram

**Only for:** enterprise architecture explanations

**Use:** Bounded system and integration explanation.

**Observed:** A cream 1280px ruled frame contains small outlined app labels on left and right, joined by thin orthogonal lines and braces to a central square. A subtle orange halftone strip is the only textured accent. Comparison artwork uses a faint dotted backing and outlined pill labels, with disordered tilted steps on one side and three orderly stacked steps on the other.

**Transfer:** Represent relationships with plain labeled rectangles and hairline connectors; adapt the number of endpoints to the product rather than copying the ecosystem.

**Build:** Draw SVG connectors at 1px in olive charcoal; place paper rectangles with 4px corners above the lines. Use a larger square central node and a short orange-to-transparent dot strip near its base. For a before/after variant, divide the frame in two, add 1.3px putty dots on cream, and contrast rotated overlapping process pills with an evenly spaced vertical stack.

### Editorial growth illustration

**Only for:** audience-specific proof sections

**Use:** Companion to a large serif trust statement and awards.

**Observed:** Three rising, offset graph planes use dark plum hairline grids, orange spray-like blocks and starbursts, and a thin hand-drawn rising arrow. The illustration occupies a roughly square area to the right of the statement; below it sit three large black statistics.

**Transfer:** Translate the product's progress into a small layered data illustration, not a generic 3D bar chart.

**Build:** Use SVG to draw three offset upright quadrilateral grid panels increasing in height. Add narrow dark plum side faces, flat orange blocks, a few irregular orange starbursts, and stippled masks around the block edges. Draw a single fine rising arrow diagonally through the panels. Preserve large areas of paper between marks.

### Resource thumbnails

**Only for:** resource collections

**Use:** Upper image strip on three-column editorial cards.

**Observed:** Wide landscape thumbnails use the same blurred green and blue photography as the product stages, with centered white multi-line article titles. The card repeats its title in dark text below the image on paper.

**Transfer:** Use short editorial titles over subdued atmosphere; keep the title legible without adding heavy black scrims.

### Icons

**Observed:** Mostly simple monochrome SVG symbols at 16px in navigation, 20px in actions, and 24px in feature cells. Chevrons, plus signs, arrows and small assurance symbols use ink or muted gray; orange highlights capabilities. App marks retain their native colors only within integration illustrations and small logo groups.

**Transfer:** Choose compact, visually light glyphs with consistent silhouettes; keep plus controls and arrows small. Do not enlarge every feature icon into an illustration.

## Section recipes

How recurring sections are built.

### First screen: Landscape demonstration opening

**Observed:** Below the 56px Navigation, a paper field begins with 96px top padding. Center an uppercase 12px eyebrow, then a two-line display headline in a 768px text block, a single 14px supporting line within 640px after 24px, and paired Primary button and Secondary button after 32px. The action row is compact, not full width. After 40px, center the 1024×576px Atmospheric product stage. Layers run paper canvas, soft landscape, sharp pale notification or interface, then any small playback control. Within the first 900px, all text and actions and the upper majority of the media are visible; its bottom and the trust-logo strip continue below the fold.

**Transfer:** Use a product promise with similarly balanced two-line shape and a meaningful demonstration on the atmospheric stage. Without media assets, make the cream connected-panel fallback described in Atmospheric product stage. Enterprise openings retain the centered 56px headline but substitute assurance icons and a trust strip for the large demo. Audience openings use audience-display and a 1280px collage below; commercial openings use pricing-display left and a compact explanatory paragraph right, with controls appearing early.

**Avoid:** Do not use a full-bleed orange hero, a dark futuristic dashboard opening, an oversized 80px headline by default, or a tiny decorative image beside left-aligned copy.

**Text style:** `display` — Degular Display 500 · 56px/1

### Heading pair

**Observed:** Center a 48px heading with a short orange phrase inline, 16px above body support constrained to 768px. A 12px uppercase eyebrow can sit above. The next grid or media begins after 48px.

**Transfer:** Emphasize the decisive part of the promise rather than coloring the entire heading.

**Text style:** `heading` — Degular Display 500 · 48px/1

### Asymmetric capability chapter

**Observed:** On Cream chapter, use Feature split with the serif feature-heading, muted feature-eyebrow, 14px description, and a small feature disclosure list. Rows use 1px fine warm rules, 12px vertical padding, semibold 14px labels and a plus to the right. Stack Dark button and Secondary button below. Atmospheric product stage fills the wider side. Repeat chapters with 120px outer vertical rhythm rather than boxing the text in cards.

**Transfer:** Use the narrow column for the explanation and three concise capabilities; let the main demonstration provide detail.

**Text style:** `feature-heading` — Serrif 300 · 28px/1.25 · tracking -0.015em

### Ruled editorial quotation

**Observed:** Brown-black band contains a 1280px inner spread with paper-colored rules above and below and 64px inner vertical padding. Columns are 1.25fr and 1fr with 48px gap; the left holds a quote-dark statement and attribution after 40px, the right a 548px square image. A moss version belongs to audience stories.

**Transfer:** Give one credible voice room to explain a real transformation; use a context image or atmospheric customer plate.

**Text style:** `quote-dark` — Serrif 200 · 40px/1.08 · tracking -0.04em

### Interactive spectrum explanation

**Observed:** A 720px left-aligned introduction uses editorial-heading and body text. A thin 8px progress rail spans most of the 1280px container with circular previous/next controls; the rail runs orange through blush and pink to violet. Four 308×167px selector cards sit below with 16px gaps, 24px padding and 12px corners. The selected card is putty with a dark border; inactive cards are cream. Below, a warm peach diagram sits opposite a serif explanation.

**Transfer:** Use this construction to explain a genuine progression of modes or maturity, with a selected state changing the diagram; do not invent a spectrum merely to fill space.

**Text style:** `editorial-heading` — Serrif 300 · 40px/1.1 · tracking -0.03em

### Outcome proof spread

**Observed:** Putty proof band begins with Heading pair, then a Proof card and portrait atmospheric customer plate in equal columns. The quote panel's lower ruled compartment contains two proof-number figures with short captions. Small previous/next arrows and a centered orange action follow the spread.

**Transfer:** Keep the editorial-plus-quantified-proof device even when the content is a founder explanation rather than a customer carousel.

**Text style:** `quote-light` — Serrif 300 · 40px/1.08 · tracking -0.04em

### Assurance and controls

**Observed:** Heading pair introduces Assurance matrix. Five icon-led cells share edges; a connected dotted technical panel beneath explains concrete controls using outlined labels and connectors. A centered Dark button ends the chapter.

**Transfer:** Translate trust into a small number of inspectable properties and a meaningful system diagram, rather than an unsubstantiated badge wall.

### Capability and resource grids

**Observed:** Three-column cards use 24px gaps in a 1280px container. Light resource cards have 1px putty borders, imagery above and 20px card-heading titles below. Actionable examples use small app marks, title, description and a right-arrow text link. Audience capability grids invert this treatment on Charcoal platform band with pale translucent tiles and orange icons.

**Transfer:** Choose the light variant for examples and reading; scope the dark variant to a dense technical chapter, not every feature.

**Text style:** `card-heading` — Inter 600 · 20px/1.25 · tracking -0.025em

### Dark closing invitation

**Observed:** Brown-black band uses 96px vertical padding, centered heading and a short inline orange phrase. Support follows after 12px and the actions after 36px. The default is a 48px orange primary with a paper-outlined alternative. Enterprise uses compact 40px orange and paper-filled actions; audience conversion can use one 48px action. Utility footer returns to paper immediately underneath.

**Transfer:** Compress the promise into a final outcome and one clear next step; preserve the dark-to-light ending contrast.

**Text style:** `heading` — Degular Display 500 · 48px/1

### Enterprise invitation and support

**Only for:** enterprise pages

**Observed:** Moss invitation uses two equal columns separated by 96px: a light serif invitation on the left and a paper lead-form panel on the right. Later, a putty service section pairs a large sans heading and a two-by-two grid of top-ruled support summaries with a warm square workplace photo.

**Transfer:** Separate high-intent qualification from general product explanation. Use the support grid to explain concrete implementation help, not a feature list.

### Commercial comparison

**Only for:** pricing pages

**Observed:** Cream chapter carries a split 80px opening, then a bordered product-category selector with a dark selected tab and two outlined alternatives. A wide quantity slider, billing selection and currency control precede four adjoining Plan cards. Paid-plan inclusions sit in a single ruled four-column panel. An atmospheric-backed announcement and a white explainer lead into a charcoal, hairline-organized platform diagram headed at 80px/0.9.

**Transfer:** Explain the billing model before elaborating the platform; keep selection controls visually distinct from purchase buttons.

**Text style:** `pricing-display` — Degular Display 500 · 80px/1

### Monumental statistical proof

**Only for:** audience-specific proof sections

**Observed:** Cream band pairs a 48px light serif trust statement and awards with Editorial growth illustration. Three 80px black statistics run below in equal columns with 56px gaps; each has a top 1px ink rule and a short body caption.

**Transfer:** Use independently verifiable statistics with varied short units, not decorative large numbers.

**Text style:** `heading` — Degular Display 500 · 48px/1

### Grouped objections

**Only for:** FAQ sections

**Observed:** A centered 48px title precedes categorized FAQ item groups within 1024px. Category titles sit above the 16px-radius cream groups; individual rows remain flat and separated by hairlines. Pricing ends with these groups and then the compact Utility footer, without a closing conversion band.

**Transfer:** Let decision-stage pages end on answered practical questions rather than forcing an extra sales pitch.

**Text style:** `heading` — Degular Display 500 · 48px/1

## Page flow

**Storyline:** Invitation → tangible demonstration → capability explanation → editorial and quantified proof → assurance or decision support → concise next step → light utilities.

### Broad product or platform landing page

1. **Promise and demonstration** — Centered opening with atmospheric product media followed by a muted trust-logo strip.
2. **Capability explanation** — A section lead introduces asymmetric serif-titled chapters with wide demonstrations.
3. **Editorial proof** — Dark ruled quotation spread punctuates the pale chapter rhythm.
4. **Concept differentiation** — Interactive spectrum links an explanation, selectable cards and diagram.
5. **Quantified proof and assurance** — Putty outcome spread and outlined assurance matrix turn the promise into inspectable substance.
6. **Closing call and utilities** — Short brown-black invitation with orange phrase and paired actions; expanded light directory footer.

**Transfer:** Use the stage, editorial proof and dark closing devices as the visual anchors; rearrange capability chapters around the new product's strongest argument.

### Commercial selection and billing explanation

1. **Commercial promise** — Split oversized heading and short explanation on cream.
2. **Selection** — Product tabs, quantity rail, billing controls and adjoining plan columns.
3. **Value and billing clarification** — Shared inclusions, atmospheric announcement and split model explainer.
4. **Platform context** — Charcoal ruled diagram followed by three plain-language commitment columns.
5. **Objection handling and utilities** — Categorized FAQ groups lead directly to compact light utilities, with no final conversion band.

**Transfer:** Prioritize comparability and pricing mechanics over a decorative hero or repeated conversion sections.

### Enterprise confidence and qualified inquiry

1. **Promise and trust** — Centered opening, single compact action, assurance icons and muted customer strip.
2. **Problem reframing** — Two-column dotted process comparison makes friction visible.
3. **Qualified invitation** — Moss band pairs serif business-case copy with a light form.
4. **Capability and assurance** — Asymmetric chapters, security media panels and a large ruled connection diagram.
5. **Evidence and partnership** — Editorial customer spread followed by a putty service grid and warm workplace photo.
6. **Activation and closing** — Example cards precede a dark invitation with orange phrase, two compact actions and the light compact footer.

**Transfer:** Bring assurance into the opening, reserve a dedicated lead-generation band, and explain ongoing support as concretely as product capabilities.

### Audience-specific outcomes and practical use cases

1. **Audience promise** — Centered 64px heading, direct action and large photo/interface collage.
2. **System explanation** — Trust strip and full-width relationship diagram contextualize the product.
3. **Social proof** — Two-column cream-backed testimonial collection.
4. **Capability chapters** — Centered headings above large workflow-and-people collages with concise explanatory copy.
5. **Deepening and quantified proof** — Dark quotation, tabbed use cases, app tile showcase and monumental statistical proof.
6. **Decision support** — Dark capability grid, light resource cards and grouped questions.
7. **Closing call and utilities** — Dark single-action invitation followed by compact paper utilities.

**Transfer:** Retain the more photographic, audience-centered variant; show the work being improved without reproducing every chapter.

## Writing

Approachable operational confidence: ambitious outcomes are grounded in everyday work, explicit controls and practical next steps. Editorial warmth softens technical language without hiding complexity.

**Do not copy:** Do not reuse Zapier names, logos, proprietary feature names, customer marks, quotations, pricing, awards, adoption figures or outcome claims. Replace them with the new product's own substantiated content. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Speak directly to you and your team. Name the product when clarifying what it does; use we sparingly for commitments and assistance.
- **Rhythm:** Headlines often use short active clauses or parallel fragments. Support paragraphs explain the mechanism in one to three sentences; longer practical answers are welcome in FAQs. Em dashes and conversational contractions add warmth without exclamation marks.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | Welcome the reader into a new way of working, or name an audience outcome plainly. | 7–10 words | “Welcome to automation in the agentic era”<br>“Close more deals faster with automation” |
| Section headline | Use parallel active clauses or a concise, tangible benefit. | 4–10 words | “Build anywhere. Run on [Brand]. Govern in one place.”<br>“Don't let your best ideas die in a backlog” |
| Support line | Describe where work starts, what the product does next, and the practical benefit. | 15–30 words | “Start building in your favorite AI tool, then run and govern trusted workflows on [Brand].” |
| Primary action | Verb plus route or destination; avoid vague aspirational language. | 2–5 words | “Start free with email”<br>“Talk to an expert now” |
| Capability title | Concrete control or operating property, not a grand promise. | 2–6 words | “Workflows that run while you sleep”<br>“Define exactly what runs” |
| FAQ | Ask the question in the reader's own practical language; answer directly before adding detail. | 5–14 words per question | “Do I need to know how to code?” |
| Closing line | Compress the transformation into a short memorable contrast. | 5–14 words | “Go from AI to ROI” |

**Words and phrasing to use:** build; run; connect; govern; your team; in one place; trusted; works; every step; real outcomes

**Avoid:** revolutionary synergy; magic; limitless possibilities; next-level disruption; frictionless everything; unqualified superlatives

**Rules:**

- Lead with the user's job, then explain the mechanism that improves it.
- Technical terms earn their place through a concrete action or example nearby.
- Use contrast to clarify choices: build freely while retaining control; move faster without losing reliability.
- Keep action labels literal and match their destination.
- Put measurement and attribution next to proof claims; do not turn a plausible benefit into an unsupported statistic.

## Do's and Don'ts

### Do

- Use 56px/1 display type for the default opening and 48px/1 for major section leads.
- Balance 369px text columns against 831px demonstrations with an 80px gutter.
- Preserve the 28px light-serif feature-title voice beside 14px supporting copy.
- Use 96px vertical padding for major bands and 120px for expanded explanatory chapters.
- Keep page panels flat and let 1px warm rules establish their structure.
- Stage at least one sharp pale product diagram over blurred natural color.
- Keep 4px corners on content buttons and reserve the 18px pill for the header.
- Use orange selectively on actions, a decisive phrase and a few proof numbers.

### Don't

- Do not make all headings bold Inter; the display-grotesk and light-serif contrast is essential.
- Do not turn the putty and cream neutral ramp into pure white against cool blue-gray.
- Do not use the 80px pricing display as the default headline across all page types.
- Do not add broad floating shadows to proof cards, plan columns or the assurance table.
- Do not spread violet or pink from the spectrum rail into unrelated navigation and buttons.
- Do not separate adjoining comparison cells with oversized gutters or 24px rounded corners.
- Do not recolor every utility link orange; most are ink or warm gray.
- Do not treat product-stage interface colors as the marketing palette or enlarge the small app marks into decorative logos.

## Motion and responsive

### Motion

**Observed:**

- Product demonstrations have play/pause controls; the concept spectrum has previous/next controls and selectable stops, and customer proof has slide arrows.
- No action transitions or animation timings are established for these elements.

**Transfer:**

- Keep playback controls compact and attached to the media stage. Spectrum changes should retain the relationship between selected card, rail and diagram.

**Unknown:**

- Demonstration choreography, carousel timing, transition durations and easing.

### Responsive

**Observed:**

- Desktop composition uses centered max-width containers, wrapping action groups and asymmetric text/media grids.
- Width breakpoints include 400px, 425px, 426px, 476px, 530px, 550px, 600px, 768px and 896px; commercial pages also include 1024px and 1280px.

**Transfer:**

- On narrow screens, retain the opening text → actions → atmospheric stage relationship. Stack the narrow feature explanation above its wide demonstration rather than shrinking both into unreadable columns.
- Let paired actions wrap; turn adjoining comparison and assurance content into readable stacked groups while preserving shared rules. These are adaptation recommendations, not prescribed mobile measurements.

**Unknown:**

- Exact mobile type sizes, header behavior, grid-collapse thresholds and mobile media framing.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
