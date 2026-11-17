# Corgi — storybook meets infrastructure

## Overview

An almost-white, ruled editorial system makes technical services feel approachable through surreal cutout objects and storybook landscapes. Tight grotesk headlines mix with a single expressive italic phrase, while orange actions sit like physical keys above soft grey bases. Sparse text chapters alternate with compact modular cards, dark explanatory stages, and warmly theatrical imagery.

### Essentials

- A practical headline gets one romantic interruption: 60px/1 hero sans at weight 500 with -0.032em tracking, interrupted by orange italic serif at the same size and weight 400.
- The opening is an airy illustrated scene, not a dashboard: a 900px stage with centered copy, a 752px headline limit, pale cloudy backing, diagonally opposed cutouts, and a monochrome logo rail at its foot. Use a textured object metaphor when no mascot exists.
- Actions have physical undersides: 16px rounded faces sit on matching rounded bases with 4px of exposed depth; orange is the main action, white the companion, charcoal the alternative.
- Most of the page remains #f6f6f6 with #e1e1e1 hairlines; orange #ff5c00 concentrates in actions, short emphasis and chips. Full-width charcoal #313131 chapters punctuate this light majority rather than turning the whole page dark.
- Objects behave like editorial clippings: monochrome stippled hands, literal objects, portraits and orange botanical cutouts sit on white card stages; 24px rounded containers and 24px gutters keep the playfulness organized.
- The ending is a designed destination: a charcoal call with a row of five small character or object variations, white 48px text and paired actions, followed by a press rail, ruled footer columns and a full-width painted landscape above a black legal band. Recreate the landscape as a simple layered pastoral illustration if bespoke painting is unavailable.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Signal orange | `#ff5c00` | `--color-orange` | action, accent, link, text | Primary actions, announcement strip, italic hero emphasis and interactive chips. |
| Orange key base | `#cc4a00` | `--color-orange-base` | surface | Exposed underside of orange buttons. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Chip peach | `#ffdecc` | `--color-peach` | surface | Small selectable chips and selected product navigation. |
| Badge pink | `#f66398` | `--color-badge-pink` | accent | Start of small availability-badge gradients. |
| Badge coral | `#fb846c` | `--color-badge-coral` | accent | Middle of small availability-badge gradients. |
| Badge apricot | `#fe9850` | `--color-badge-apricot` | accent | End of small availability-badge gradients. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Card white | `#ffffff` | `--color-white` | surface, text | Cards, white buttons and reversed text; navigation uses 85% white over the canvas. |
| Chalk canvas | `#f6f6f6` | `--color-canvas` | background, surface | Dominant marketing canvas and FAQ raised face. |
| Fine rule | `#e1e1e1` | `--color-rule` | border, surface | Light edges, section dividers and white-button undersides. |
| Press caption grey | `#7b7b7b` | `--color-caption` | text | Tiny attribution beneath press logos. |
| Dark stage rule | `#585858` | `--color-dark-rule` | border | Hairline structure on charcoal bands. |
| Supporting grey | `#4e4e4e` | `--color-support` | text | Hero support line and explanatory prose. |
| Body grey | `#4a4a4a` | `--color-body` | text | Default prose, card descriptions and questions. |
| Charcoal stage | `#313131` | `--color-charcoal` | background, surface | Comparison chapter and shared closing band. |
| Headline ink | `#191919` | `--color-ink` | text, action | Headlines and dark action faces. |
| Legal black | `#000000` | `--color-black` | background | Terminal legal band only. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| technical product chapters | Secondary headline grey | `#b1b1b1` | `--color-muted-heading` | text | Second line of explanatory chapter headings. |

## Typography

- **heroHeading** — Opening headline sans portion. Compact proportional grotesk with rounded bowls; medium rather than heavy. If unavailable, use **Geist**. Use weight 500 and preserve tight tracking. Font stack: "heroHeading", "Geist", Arial, sans-serif.
- **heroSerif** — One expressive phrase within the opening headline. High-contrast italic serif, fluid and literary against the practical sans. If unavailable, use **Libre Baskerville**. Use italic 400; tune wrapping before changing the measured size. Font stack: "heroSerif", "Libre Baskerville", Georgia, serif.
- **f37Bolton** — Section headings, package names, large quotations and press captions. Clean proportional sans-like letterforms despite the monospace fallback stack; do not substitute a visibly fixed-width coding face. If unavailable, use **Inter**. Use 400–500 with tight tracking. Font stack: "f37Bolton", "Inter", Arial, sans-serif.
- **Geist** — Body copy, navigation, actions and bold card titles. Contemporary grotesk with compact small-text proportions. Font stack: "Geist", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | heroHeading | 500 | 60px | 1 | -0.032em | Default marketing hero sans headline. |
| display-italic | heroSerif | 400 italic | 60px | 1 | -0.032em | Orange benefit phrase inline with the hero headline. |
| heading | f37Bolton | 500 | 48px | 1 | -0.032em | Main section heads, large centered quotation and closing statement. |
| package-title | f37Bolton | 400 | 32px | 1 | -0.032em | Names in package-card raised caps. |
| card-title | Geist | 700 | 20px | 1 | -0.032em | Catalogue titles and compact feature headings. |
| lead | Geist | 400 | 20px | 1.2 | -0.015em | Hero support and section introductions. |
| button-large | Geist | 500 | 20px | 1.2 | -0.015em | Closing and larger conversion actions. |
| body | Geist | 400 | 16px | 1.2 | -0.015em | Ordinary prose and text links. |
| button | Geist | 500 | 16px | 1.2 | -0.015em | Default compact action face. |
| question | Geist | 700 | 16px | 1.2 | -0.015em | Accordion questions. |
| small | Geist | 400 | 14px | 1.2 | -0.015em | Card descriptions and navigation. |
| chip | Geist | 500 | 12px | 1 | normal | Small selectable module labels. |
| badge | Geist | 400 | 12px | 1.2 | -0.015em | White text on availability gradients. |
| press-caption | f37Bolton | 400 | 11px | 1.5 | -0.01em | Source and date line beneath press logos. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| specialist and editorial openings | product-display | f37Bolton | 500 | 60px | 1 | -0.032em | Plain two-line hero on specialist, editorial and company pages. |
| technical product chapters | chapter-heading | f37Bolton | 400 | 48px | 1 | -0.032em | Explanatory heading with a pale second line. |
| illustrated vertical product openings | split-display | f37Bolton | 500 | 48px | 1.08 | -0.045em | Left-aligned headline beside a large halftone architectural scene. |
| customer stories | story-quote | f37Bolton | 400 | 40px | 1 | -0.025em | Long white testimonial in charcoal inset panel. |
| technical and trust chapters | chapter-title | f37Bolton | 400 | 28px | 1 | -0.032em | Titles in open three-column explanatory rows. |

**Notes:**

- Keep the main display scale compact in leading, not oversized in weight. Large headings generally tighten to -0.032em; body and actions use -0.015em.
- The italic phrase is a change of voice inside the same headline, not a detached script badge.
- Use the sans appearance of the section display face; its fallback category does not make the design a monospace interface.

## Layout

**Density:** Airy between chapters, compact within cards; large ruled fields contrast with close-set typography.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Compact button vertical padding and press-logo caption gaps. |
| 12px | Card title-to-copy spacing, action pairs and card action trays. |
| 16px | Accordion internal gaps and compact button horizontal padding. |
| 20px | Catalogue text and package inner padding. |
| 24px | Primary grid gutters, support-line separation and panel padding. |
| 32px | Press-band vertical padding and legal-band padding. |
| 36px | Vertical separation in closing composition. |
| 48px | Heading-to-proof gaps and closing statement-to-actions. |
| 64px | Desktop side gutters and normal section padding. |
| 80px | Catalogue and FAQ vertical section padding. |
| 96px | Long chapter rhythm and generous separations. |

### Containers and grids

- **main-container**: max width 1600px · side padding 64px. Wide centered structure; at 1440px the inner field is 1312px. Fine vertical rails align sections across the page.
- **catalogue**: max width 1200px · 3 columns · gap 24px. Centered three-column illustrated card grid.
- **packages**: 4 columns · gap 24px. Four equal cards, 310px wide in the desktop inner field.
- **faq**: max width 800px · side padding 24px. Narrow centered question stack; 752px usable row width.
- **explanatory-row** (only for technical and trust chapters): max width 1128px · 3 columns · gap 0px. Open columns separated by right-hand hairlines, not floating cards.
- **story-article** (only for customer stories): max width 740px. Main reading column paired with a small right-hand facts sidebar inside wider rules.

## Corner radius

| Element | Radius |
| --- | --- |
| action-face | 16px |
| cards-and-panels | 24px |
| availability-badge | 12px |
| module-chip | 4px |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| card-haze | `0px 0px 24px 0px rgba(25,25,25,0.05)` | Low lift around outer package cards. |
| raised-cap | `0px 0px 24px 0px rgba(25,25,25,0.35)` | Strong soft lift for package caps and FAQ face; shadows spread with no vertical offset. |

### Surfaces

#### Ruled canvas · level 0

**Use:** Default page field.

**CSS:** `background: #f6f6f6; border-bottom: 1px solid #e1e1e1`

**Observed:** Thin section and container rules remain visible through otherwise empty space.

**Transfer:** Let aligned hairlines carry structure rather than adding a background to every block.

#### White card · level 1

**Use:** Catalogue cards and outer package shells.

**CSS:** `background: #ffffff; border: 1px solid #e1e1e1; border-radius: 24px; overflow: hidden`

**Observed:** Image, text and action tray are distinct stacked compartments.

**Transfer:** Keep the container white and compartment rules faint.

#### Raised face · level 2

**Use:** Nested package header and FAQ question stack.

**CSS:** `background: #f6f6f6; border-radius: 24px; box-shadow: 0px 0px 24px 0px rgba(25,25,25,0.35)`

**Observed:** A softly elevated rounded face sits above a larger enclosing white body; package caps use white rather than canvas.

**Transfer:** Use the conspicuous soft shadow only where one panel visibly sits over another.

#### Charcoal band · level 0

**Use:** Comparison chapter and closing call.

**CSS:** `background: #313131; border-top: 1px solid #585858; border-bottom: 1px solid #585858; padding: 64px; color: #ffffff`

**Observed:** The same vertical grid rails continue in a lighter dark-stage grey.

**Transfer:** Use as a decisive tonal punctuation, with light typography and white or orange controls.

#### Navigation glass · level 3

**Use:** Fixed navigation beneath announcement strip.

**CSS:** `background: rgba(255,255,255,0.85); backdrop-filter: blur(6px); border-bottom: 1px solid #e1e1e1`

**Transfer:** Keep the translucency subtle and readable over illustrated media.

#### Legal foundation · level 0

**Use:** Very bottom of the page.

**CSS:** `background: #000000; padding: 32px`

**Observed:** Dense pale disclosure paragraphs appear directly below the painted panorama.

**Transfer:** Reserve the hard black contrast for necessary terminal disclosures.

## Components

### Navigation

**Use:** Persistent route and conversion access.

**CSS:** `background: rgba(255,255,255,0.85); backdrop-filter: blur(6px); border-bottom: 1px solid #e1e1e1; padding: 8px 64px; height: 56px`

**Text style:** `small` — Geist 400 · 14px/1.2 · tracking -0.015em

**Observed:** Brand mark left, compact category menus with small down chevrons across the middle, login and two physical action keys right. A 36px orange announcement strip sits above, creating a 92px header.

**Transfer:** Keep route labels short enough that the actions remain separate.

### Primary button

**Use:** Default hero and card conversion.

**CSS:** `background: #ff5c00; color: #ffffff; border: 1px solid transparent; border-radius: 16px; padding: 8px 16px; display: flex; align-items: center; justify-content: center`

**Text style:** `button` — Geist 500 · 16px/1.2 · tracking -0.015em

**Observed:** Face is 37px tall and nests in an orange-base wrapper with 4px bottom padding. Large closing variant uses 12px 24px padding, button-large text and a 50px face.

**States:** Declared: hover background-color #ff7d33; focus-visible unspecified; active background-color #ff9d66.

**Transfer:** Implement the underside as a real wrapper, not a diffuse drop shadow.

### Secondary button

**Use:** Consultative companion and catalogue navigation.

**CSS:** `background: #ffffff; color: #191919; border: 1px solid #e1e1e1; border-radius: 16px; padding: 12px 24px`

**Text style:** `button-large` — Geist 500 · 20px/1.2 · tracking -0.015em

**Observed:** White face on a rule-grey base with 4px exposed depth. Compact catalogue version uses button text and 8px 16px padding; dark alternative has an ink face and lighter grey underside.

**States:** Declared: hover background-color lab(98.2596% -.247031 -.706708); focus-visible unspecified; active background-color #ededed.

### Module chip

**Use:** Selectable included capabilities inside package cards.

**CSS:** `background: #ffdecc; color: #ff5c00; border-radius: 4px; padding: 4px 8px; display: inline-flex`

**Text style:** `chip` — Geist 500 · 12px/1

**Observed:** Small rectangular labels wrap into centered rows rather than a continuous sentence.

**States:** Declared: hover transform rotate(8deg) and background-color #ffc9a3; focus-visible outline #ff5c00 solid 2px with 3px offset; active unspecified.

**Transfer:** Use short module names; pair the chip field with a short explanatory instruction.

### Availability badge

**Use:** Tiny status label over a card image compartment.

**CSS:** `background: linear-gradient(90deg, #f66398 0%, #fb846c 60.894%, #fe9850 100%); border-radius: 12px; padding: 6px 12px; color: #ffffff`

**Text style:** `badge` — Geist 400 · 12px/1.2 · tracking -0.015em

**Observed:** Pinned toward the upper-left of the white image stage; a single-line gradient label, not a large promotional panel.

### Catalogue card

**Use:** Browseable capability or product collection.

**CSS:** `background: #ffffff; border: 1px solid #e1e1e1; border-radius: 24px; overflow: hidden; display: flex; flex-direction: column`

**Text style:** `card-title` — Geist 700 · 20px/1 · tracking -0.032em

**Observed:** A 120px image stage carries one clipped object and Availability badge; a 20px-padded text area holds bold title and small description with 12px gap; a ruled 12px-padded bottom tray holds a full-width Secondary button. Typical desktop card is 384px by 311px.

**Transfer:** Choose a physical metaphor per capability, not a repeated generic icon.

### Package card

**Use:** Compare maturity stages or bundles without conventional price tables.

**CSS:** `background: #ffffff; border: 1px solid #e1e1e1; border-radius: 24px; box-shadow: 0px 0px 24px 0px rgba(25,25,25,0.05); display: flex; flex-direction: column; overflow: clip`

**Text style:** `package-title` — f37Bolton 400 · 32px/1 · tracking -0.032em

**Observed:** A 160px raised white cap contains a bottom-aligned name, small support line and partially clipped object at upper right. Beneath it sit centered Module chips, then a separate action tray. The custom bundle receives a dark action instead of orange.

**Transfer:** Compare by audience or growth stage; do not invent currency prices when the offer is modular.

### FAQ panel

**Use:** Concentrated objection handling.

**CSS:** `background: #f6f6f6; border-radius: 24px; padding: 24px; box-shadow: 0px 0px 24px 0px rgba(25,25,25,0.35); display: flex; flex-direction: column; gap: 16px`

**Text style:** `question` — Geist 700 · 16px/1.2 · tracking -0.015em

**Observed:** Questions align left with 16px chevrons right and 1px rules between. The raised question face sits over an enclosing white panel whose bottom lip holds a centered contact sentence.

**Transfer:** Use real question buttons and keep longer answers subordinate to the compact closed rows.

### Accent text link

**Use:** Inline contact and contextual story links.

**CSS:** `color: #ff5c00`

**Text style:** `body` — Geist 400 · 16px/1.2 · tracking -0.015em

**Observed:** Short orange phrase inside otherwise grey prose.

**States:** Declared: hover text-decoration-line underline; focus-visible unspecified; active unspecified.

## Imagery and graphics

### Cloud theatre

**Use:** Signature marketing opening.

**Observed:** Pale blue-grey clouds cover the stage and dissolve into the lower canvas. A richly modeled flying character sits upper-right while an engraved black-and-white hand rises lower-left; neither is framed. The headline remains the visual center.

**Transfer:** Use two diagonally opposed object cutouts with contrasting treatments: one softly colored dimensional object and one monochrome engraved gesture. Minimum version is a single well-lit object plus a stippled hand-like or tool-like metaphor.

**Build:** Back a full-stage pale sky image with a translucent blue wash rgba(79,179,255,0.05), then overlay a bottom fade to #f6f6f6 beginning around 72% and becoming opaque by 95%. Place a roughly 364px square transparent object above/right of the copy and a roughly 318px by 241px monochrome cutout below/left. Preserve clear space around the copy.

### Editorial object clippings

**Use:** Signature card images and explanatory accents.

**Observed:** Objects are isolated on white: peeled banana, hammer and lock, blackletter numerals, suited animals, floating coins and paper. Most are monochrome halftone; orange seed and botanical silhouettes distinguish growth packages.

**Transfer:** Choose tangible metaphors for abstract benefits. Desaturate photographs, isolate silhouettes, apply print-like stipple, and keep one orange family for progression.

**Build:** Mask a high-contrast object photograph onto transparency; overlay an SVG halftone pattern of black dots with varying radius according to image luminance, or use a preprocessed stippled asset. Keep it within the 120px card image stage, clipping overscale parts at edges. For growth cards use one orange botanical silhouette in the upper-right of the raised cap.

### Connection funnel

**Use:** Dark comparison chapter's positive alternative.

**Observed:** A colored hourglass-like channel pinches around a glowing central brand disc; small client or module tokens travel visually from either side. Navy corners frame pink, cool lavender and warm peach light.

**Transfer:** Turn a fragmented workflow into a central connecting object. A flat vector channel with layered light and generic module tokens is the minimum acceptable equivalent.

**Build:** In a 24px rounded panel, draw two navy SVG masks with broad inward curves, one above and one below, leaving a narrow center channel. Fill the channel with a left-to-right pink, lavender and peach gradient. Center a white circular product symbol and two larger translucent white rings; scatter 36px–80px rounded tokens toward the edges. Add a soft colored blur behind the center disc.

### Portrait rail

**Use:** Customer proof section.

**Observed:** Oversized monochrome halftone portraits fill rounded cards, fading to white near their base. Name, role and small colored company icon sit over the fade; the written endorsement occupies the lower compartment. Cards extend beyond the viewport edges.

**Transfer:** Use candid founder or practitioner photographs, not uniform corporate headshots. Keep a horizontal clipping rail with 24px spacing.

**Build:** Apply monochrome stipple to portraits, cover-fit into an approximately 380px by 318px image area, and overlay a white gradient strongest at the lower-left. Use 24px corners and a thin edge around the portrait compartment.

### Pastoral panorama

**Use:** Signature footer artwork above disclosures.

**Observed:** A full-width painterly landscape of green rolling hills, small warm-stone houses, cypress trees, paths and golden clouds. Its pale upper sky melts into the canvas; the bottom is densely painted green. It occupies a 1440px by 534px image field.

**Transfer:** End with a similarly welcoming imagined place rather than a product UI. Keep the horizontal depth, warm cloud light and soft brushwork; the setting can reflect the new product's notion of refuge.

**Build:** Construct an SVG panorama with three overlapping hill layers, a winding cream path, small terracotta-roof buildings and irregular tree silhouettes. Add clustered translucent cream cloud shapes at the top and a paper-grain filter across the scene. Fade the sky into the canvas while keeping the lower edge solid and uninterrupted.

### Halftone architecture

**Only for:** illustrated vertical product openings

**Use:** Split hero's large right-hand scene.

**Observed:** A close view of an apartment building rendered in coarse colored stipple, with a warm orange mural. The architecture is cropped by the right and bottom viewport edges and dissolves into the light field at left.

**Transfer:** Use a relevant real-world environment with localized warm color, not a glossy stock-photo rectangle.

**Build:** Halftone a building or operational environment image, mask its left edge with a gradual dissolve, and let it occupy about the right half of the 900px stage. Keep the text half untextured.

### Technical object stage

**Only for:** technical product chapters

**Use:** Scenario demonstration paired with explanatory rows.

**Observed:** A charcoal 648px by 640px rounded field contains a faint dot grid, subtle radial light and a small silver-edged dimensional object near center. Beside it, one scenario row is highlighted in pale grey with a thin progress bar.

**Transfer:** Use a single glass or chrome symbol for the active scenario; a carefully shaded SVG object is sufficient.

**Build:** Use a #313131 rounded field with a low-opacity white dot pattern and radial-gradient(circle, rgba(255,255,255,0.08), transparent 42%). Draw a layered cylinder or another simple product metaphor with thin silver highlights and transparent dark faces, keeping it small relative to the panel.

### Culture collage

**Only for:** company and culture pages

**Use:** Human chapter before the closing call.

**Observed:** Large overlapping photos of celebrations, work, travel and speaking are rotated in opposing directions, with 4px light borders. Strong halftone texture unifies mixed color photography; panels run beyond the page edges.

**Transfer:** Use authentic team moments at mixed scales rather than an evenly spaced staff grid.

**Build:** Layer seven rectangular images at varied widths with small opposing rotations and 4px canvas borders. Apply a shared print-dot treatment and crop the entire collage at the viewport edges; retain recognizable faces and natural colors.

### Icons

**Observed:** Material Symbols Sharp glyphs supply 16px chevrons and arrows, 20px information markers and occasional 24px thematic icons. Small SVG navigation glyphs use approximately 2px round strokes at 14px. They sit after action labels or at the far edge of accordion rows.

**Transfer:** Use sharp simple directional symbols for controls; reserve richly textured cutouts for content imagery rather than replacing them with a uniform icon set.

## Section recipes

How recurring sections are built.

### First screen: Cloud stage opening

**Observed:** The first 900px is a full illustrated stage beneath a fixed 92px two-tier Navigation. Back-to-front layers are cloudy sky, faint cool wash, lower fade into canvas, diagonally opposed character and engraved cutouts, centered headline/support/action, then a monochrome customer-logo rail at the foot. The 60px headline occupies about the middle half of the width, limited to 752px, and wraps into two close-set lines with an inline orange serif phrase. The 20px support occupies two short lines about 432px wide, separated by 24px; a compact Primary button follows another 24px gap. The major colored object sits above and to the right, the monochrome one below and left. Headline, support, action, both objects and logo rail are all visible within the first 900px; the dark introductory panel begins below.

**Transfer:** Make the new promise the center of an illustrated world using Cloud theatre and product-relevant clippings, even without a character. Specialist pages can open more plainly with a centered 60px headline, small object above, support and one orange action. Editorial stories use a broad left-aligned title and paired logos; illustrated vertical offerings use a 48px left headline beside Halftone architecture; company pages use a short text-and-halftone banner.

**Avoid:** Do not put the text in a floating white card, turn the cutouts into equal-sized feature tiles, or let the scene cover the central reading area.

**Text style:** `display` — heroHeading 500 · 60px/1 · tracking -0.032em

### Compact thesis and expansive quote

**Observed:** A wide inset charcoal rounded panel delivers a compact 32px platform thesis with one orange word, faint oversized circle outlines and a tilted document clipping. Below, a centered 48px quotation spans several tight lines, followed by a small portrait/name card and a white physical case-study action.

**Transfer:** Pair a short explanation of what the product actually is with an unusually prominent customer statement. Keep attribution visibly smaller than the words.

### Package comparison

**Observed:** A left-aligned heading and 20px support introduce a four-column Package card row on Ruled canvas. Heading-to-support gap is 24px; cards use 24px gutters. The tiny chips carry modular detail while the card caps carry the memorable object metaphors.

**Transfer:** Present audience progression or configurable bundles rather than defaulting to a generic pricing table.

### Before and after on charcoal

**Observed:** Charcoal band holds a centered white heading and two equal white rounded cards with 24px gap. Their upper graphic areas contrast fragmented paper and error labels with Connection funnel; bold 20px titles and compact 16px prose sit below.

**Transfer:** Contrast the old process with a unified new mechanism using concrete visual objects, not a feature-check matrix.

### Two ways to act

**Observed:** A single 48px heading contrasts an orange self-service phrase with a black consultative phrase. Two spacious split rows pair layered application imagery with short bold lead, explanation, audience qualifier and a physical action; the second row introduces a playful phone character.

**Transfer:** Make the two paths genuinely different in effort or audience. Show a small amount of actual workflow without letting internal UI typography dominate.

### Proof rail

**Observed:** A 48px heading includes one italic serif noun and a support line. A dark customer-story button aligns beside the heading block. Portrait rail below overflows the side edges; cards retain individual quotations beneath the photographic compartments.

**Transfer:** Use human proof with real roles and candid imagery rather than reducing customers to logos alone.

### Catalogue chapter

**Observed:** Left-aligned 48px headline and 20px lead sit over a centered 1200px three-column Catalogue card grid. A character or object can peek in from outside the grid; a centered orange conversion follows the collection.

**Transfer:** Use a coherent family of object metaphors and consistent compartment heights so varied descriptions remain scan-friendly.

### FAQ and contact lip

**Observed:** Centered 48px heading sits above the 800px FAQ panel. Fine dividers organize bold compact questions. The enclosing white panel extends below the raised question stack to show a centered contact sentence with Accent text link; the surrounding section uses 80px vertical padding.

**Transfer:** Concentrate practical objections into a clearly bounded reading width.

### Shared illustrated ending

**Observed:** A 601px Charcoal band has 64px padding, a centered row of five approximately 107px-wide character variations, a white 48px statement, then Secondary button and Primary button with 12px gap and larger action text. Below is a 121px press-logo rail with tiny source/date captions, then five ruled footer columns comprising brand mark plus four link groups. A centered policy/social link row leads into Pastoral panorama, then Legal foundation.

**Transfer:** Retain the memorable miniature-object row and painted destination in the ending of new pages; replace the character variations with five product-relevant tokens if necessary. Footer taxonomy and disclosures must suit the new business, not imitate the same link names.

### Open explanatory triptych

**Only for:** technical and trust chapters

**Observed:** A 1128px open grid places a 48px regular heading above three 376px-wide columns, with 24px inset text and vertical rules. An optional pale-grey continuation line extends the headline; column titles are 28px and descriptions 16px. The composition is vertically centered in a 900px field.

**Transfer:** Use for three risks, outcomes or foundations that need explanation rather than imagery.

### Editorial story

**Only for:** customer stories

**Observed:** A long 60px title and paired customer/product logos lead to a charcoal 40px quote panel with thin oversized circular outlines. A wide 16:9 video follows; a 740px article column and compact facts sidebar carry challenge, solution and numbered results. A centered local conversion and back link precede the shared ending.

**Transfer:** Let the customer's sequence of friction, change and outcome determine the headings; keep results specific and attributed.

### Alternating detail and selector

**Only for:** multi-product vertical pages

**Observed:** After a five-card overview, large paired rows alternate a product card with a 26px descriptive heading and short explanatory copy. A later exploration panel pairs a compact numbered selector at left with one large object, title, description and action at right; the selected row has peach fill and orange text.

**Transfer:** Use for a family of offerings with meaningful differences; the selector is a second browsing mode, not a replacement for the explanatory rows.

## Page flow

**Storyline:** Promise → concrete explanation → proof → modular choices and capability chapters → practical objections → illustrated conversion → press and navigational foundation.

### Broad product landing page

1. **promise** — Cloud stage opening with a compact benefit promise and logo rail.
2. **explanation and proof** — Dark thesis panel followed by a large customer quotation.
3. **choices and differentiation** — Package comparison, dark before/after stage and two ways to act.
4. **capability and social proof** — Portrait rail and illustrated catalogue.
5. **objection handling and closing** — FAQ, shared illustrated ending, press, footer, panorama and black legal base.

**Transfer:** Use the contrast between imaginative scene-setting and literal modular offers; adapt the number and order of middle chapters.

### Customer outcome story

1. **hook** — Wide editorial title, paired logos and prominent dark quotation.
2. **demonstration** — Large video before long-form reading.
3. **results** — Challenge and solution article, numbered outcomes and concise reasons, with facts sidebar.
4. **local conversion** — Customer-specific action invitation and return link.
5. **shared ending** — Charcoal illustrated call, press rail, ruled footer, landscape and legal base.

**Transfer:** Use a real person's decision journey with attributed evidence and a distinct article reading width.

### Vertical offering family

1. **promise** — Split left headline and full-height halftone environmental scene.
2. **overview** — Five illustrated offering cards.
3. **capability chapters** — Alternating card-and-description rows.
4. **selection** — Numbered selector beside a large product object and action.
5. **trust and objection handling** — Three charcoal benefit cards then focused FAQ.
6. **shared ending** — Illustrated dark call through the press, columns, landscape and legal foundation.

**Transfer:** Make the setting relevant to the audience and explain eligibility or product distinctions directly.

### Technical specialist landing page

1. **promise** — Centered plain headline with small object and single action.
2. **problem education** — Open three-column row with muted continuation heading.
3. **demonstration** — Charcoal dimensional object stage paired with scenario rows and a short customer proof line.
4. **modular solution** — Package cards and illustrated catalogue.
5. **application and objections** — Scenario triptych, small industry object rail and FAQ.
6. **shared ending** — Dark illustrated call, press rail, ruled footer, pastoral painting and legal base.

**Transfer:** Keep technical specificity in explanatory copy while imagery stays simple and material.

### Company and trust narrative

1. **mission** — Compact headline banner with right-hand halftone photo, followed by a signed prose letter and recruiting action.
2. **broader ambition** — Inset charcoal statement panel with circular linework and a small financial-symbol ticker.
3. **trust** — Three open columns of foundation claims.
4. **human proof** — Large overlapping halftone culture collage.
5. **shared ending** — Miniature character row and dark call, then press rail, footer columns, landscape and disclosures.

**Transfer:** Separate institutional claims from the human photo story; scope ticker-like financial details to genuinely relevant offerings.

## Writing

Founder-to-founder confidence with a playful visual wink, but practical rather than jokey prose. Technical terms are explained through speed, clarity and operational consequences.

**Do not copy:** Do not reuse Corgi names, logos, mascot artwork, customer identities, quotations, publication endorsements, regulatory details or numerical business claims. Replace them with the new product's verified assets and facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; speak as we when explaining the service and use the product name for compact positioning statements.
- **Rhythm:** Short benefit-led headlines, direct action verbs and one or two support sentences. Longer educational and case-study text uses clear labeled sections; staccato clauses add emphasis near conversion.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Category promise followed by a differentiating benefit phrase. | About 7–12 words | “Business Insurance at the Speed of Compute.” |
| Supporting line | Remove two frustrations, then state the practical next step and audience fit. | Two short sentences, about 15–25 words | “No confusion, no waiting. Get a quote in minutes. Modular coverage, built for founders by founders.” |
| Section heading | Describe fit or progression rather than naming a generic feature collection. | About 5–10 words | “Coverage Designed Around Your Startup’s Journey” |
| Primary action | Verb plus concrete outcome, optionally with a speed qualifier. | 2–5 words | “Get a quote instantly”<br>“Talk to an advisor” |
| Objection question | Use the buyer's real operational concern in plain speech. | One question | “Can I upgrade my coverage as the company scales?” |
| Closing statement | Restate audience fit then stack brief action-oriented clauses. | One promise and three short clauses | “Move fast. Break things. Stay covered, under one roof.” |

**Words and phrasing to use:** built for; modular; from your first…to your next…; get; review; protect; clearer; grow; ship; in minutes

**Avoid:** revolutionary synergy; unlock limitless potential; enterprise-grade everything; whimsical jokes inside technical disclosures; unqualified superlatives without proof

**Rules:**

- Tie each benefit to a specific friction, workflow or audience stage.
- Use concrete option names in cards and explain boundaries in direct prose.
- Keep action labels literal; let images carry most of the eccentricity.
- Use quotations as human speech with visible attribution, not as rewritten marketing slogans.

## Do's and Don'ts

### Do

- Keep large sans headings close-set at 48px/1 and -0.032em tracking.
- Reserve a same-size italic serif phrase for the main promise or a deliberate human emphasis.
- Align light #e1e1e1 rules to the 64px desktop gutters across chapters.
- Use 24px rounded cards with separately ruled image, description and action compartments.
- Build action depth with 4px exposed rounded bases.
- Use a 120px white image stage for catalogue object clippings.
- Include an illustrated closing destination as well as the conventional footer links.
- Keep technical explanatory rows open and ruled rather than automatically boxing them.

### Don't

- Do not make the display face look like a code editor simply because its fallback stack is monospace.
- Do not replace 16px rounded physical action keys with full pills.
- Do not spread the orange into every large background; its strongest broad fill is the slim announcement strip.
- Do not apply the 0.35-alpha panel shadow to every catalogue card; ordinary card edges are much lighter.
- Do not turn the halftone imagery into polished generic 3D icons across all sections.
- Do not put tiny press captions at the same scale as ordinary 16px body copy.
- Do not use the culture collage or financial ticker as a default product-page requirement.
- Do not stop at footer columns; the painted panorama and black disclosure base complete the visual ending.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions are declared at 0.15s cubic-bezier(.4,0,.2,1); physical wrappers declare padding and margin transitions at 75ms cubic-bezier(0.4,0,0.2,1).
- Module chips declare background and transform transitions at 0.3s ease-out and rotate 8deg on hover.
- A marquee-left animation is declared at 24s linear infinite; pill-ring-pulse is declared at 2s ease-in-out infinite.
- The fixed header declares a 0.3s transform transition.

**Transfer:**

- Use the short physical press timing for the key-like actions and the slower playful tilt for module chips.
- Use horizontal movement for logo and press rails while keeping text sections stable.

**Unknown:**

- Exact scroll-trigger timing, visibility logic and dimensional-scene playback are not specified.

### Responsive

**Observed:**

- Declared breakpoints include 640px, 768px, 1024px and 1280px.
- Package grid classes specify one column by default, two at medium widths and four at extra-large widths; catalogue grid classes specify one, then two, then three.
- Desktop navigation padding is 64px, with 16px and 24px narrower-layout declarations.

**Transfer:**

- Retain the editorial object treatment while stacking cards; reposition decorative cutouts away from the headline rather than squeezing the central copy.
- Stack closing actions on narrow widths and preserve their visible undersides.
- Let the footer panorama remain full-width while its landscape is horizontally clipped.

**Unknown:**

- Only the desktop composition is visually confirmed; exact narrow-screen headline wrapping, menu behavior and illustrated-scene rearrangement remain unspecified.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
