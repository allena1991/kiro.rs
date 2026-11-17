# SuperHi — playground meets practical

## Overview

A buoyant, light creative-tech style that pairs matter-of-fact grotesk typography with exuberant primary-colored geometry. Ice-blue space, rounded white panels, electric blue actions and poster-like color blocks make serious information feel approachable. Flat geometric illustration, grainy abstract collages and real work demonstrations carry the personality; the text remains direct and surprisingly dense inside the playful frames.

### Essentials

- The promise sits inside a geometric playground, not beside a dashboard: center a 92px/1 regular grotesk headline with -0.03em tracking in an 800px opening, with oversized shapes cut off by the outer edges and a small circular character above it.
- Big lettering stays unembellished while labels become tiny tickets: 72px/1 section headings, 52px/1.1 panel headings and 12px/1 uppercase monospace metadata, all at weight 400.
- Actions are slim capsules rather than chunky app controls: 40px high, 48px radius, 24px text and 3.6px 14.4px padding; electric blue is primary, ink is the opening companion, and white belongs on colored panels.
- Color behaves like sheets of construction paper: pale #f0f6ff remains visible in 24px side gutters and 48px section gaps, while substantial 24px-radius panels turn green, yellow, pink, cyan or orange. Keep the opening's central reading area light and let color occupy its perimeter.
- Proof feels handled by people: include a slightly rotated paper-card composition, using 16px or 24px corners and tiny blue-tinted shadows. Real work fills wide media frames; if there is no work imagery, use original geometric compositions rather than generic stock photography.
- The ending is a second playground: a 675px pale-blue field of bright circular tokens sits behind a translucent white navigation panel with 24px corners and 4px backdrop blur. Preserve this illustrated closing device and invent a simple character or symbol system appropriate to the new product.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#2727e6` | `--color-blue` | action, accent, background, link | Primary actions, ticker, small character discs, accent panels and footer marks. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Grass green | `#16ab59` | `--color-green` | surface, background, accent | Large proof panels and selected feature cards. |
| Sun yellow | `#ffda00` | `--color-yellow` | surface, accent | Social-proof garden backing and quote cards. |
| Pool cyan | `#91d8ec` | `--color-cyan` | surface, accent | Split feature panels and quote cards. |
| Poster orange | `#ff7715` | `--color-orange` | surface, accent | Tall editorial posters and experiential demonstration backing. |
| Soft orange | `#ff8e3d` | `--color-warm-orange` | surface | Split invitation panels and quote-card variants; softer than the poster orange. |
| Blush paper | `#ffcfd6` | `--color-pink` | surface | The backing sheet behind the tilted promotional posters. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White paper | `#ffffff` | `--color-white` | surface, text, action | Information cards, reverse text and white actions. Glass uses white at 0.9 alpha. |
| Ice-blue canvas | `#f0f6ff` | `--color-canvas` | background, surface | The default page ground, pale logo capsules and email fields. |
| Deeper ice blue | `#e1edff` | `--color-footer` | background, surface | Closing illustration field, pale poster stock and secondary informational panels. |
| Near-black ink | `#111118` | `--color-ink` | text, border, action | Default text, metadata outlines and the dark companion action. |

## Typography

- **__haasGrotDisp_332926** — Headlines, panel headings, questions and navigation. Neutral neo-grotesk display lettering, regular weight, with strongly tightened large headlines. If unavailable, use **Inter**. Use weight 400 and preserve tight tracking and compact line breaks. Font stack: "__haasGrotDisp_332926", "Inter", Arial, sans-serif.
- **__haasGrotText_7ea857** — Paragraphs, supporting lines, buttons and card titles. Practical text grotesk with compact spacing and an unshowy regular texture. If unavailable, use **Inter**. Use weight 400; do not introduce semibold UI styling. Font stack: "__haasGrotText_7ea857", "Inter", Arial, sans-serif.
- **__martianMono_eeab0a** — Ticker copy, chapter tickets, category labels and author captions. Wide, mechanically spaced monospace used as a small graphic counterpoint to the grotesk. If unavailable, use **Martian Mono**. Font stack: "__martianMono_eeab0a", "Martian Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | __haasGrotDisp_332926 | 400 | 92px | 1 | -0.03em | Opening promise, usually broken into two or three compact lines. |
| heading-lg | __haasGrotDisp_332926 | 400 | 72px | 1 | -0.03em | Major section introductions and detailed chapter titles. |
| poster-heading | __haasGrotDisp_332926 | 400 | 62.7px | 1.1 | -0.0077em | Tall tilted promotional cards, retaining multiple lines rather than shrinking to normal card-title size. |
| heading | __haasGrotDisp_332926 | 400 | 52px | 1.1 | -0.0092em | Headings within split panels and information modules. |
| section-label | __haasGrotDisp_332926 | 400 | 42px | 1.1 | -0.0038em | Panel-edge headings, proof headlines and inline proof numbers. |
| question | __haasGrotDisp_332926 | 400 | 35px | 1.15 | -0.0046em | Accordion questions and prominent short quotations. |
| lead | __haasGrotText_7ea857 | 400 | 24px | 1.25 | -0.0067em | Opening support line and medium-size card titles. |
| action | __haasGrotText_7ea857 | 400 | 24px | 1.35 | -0.02em | Capsule action labels. |
| navigation | __haasGrotDisp_332926 | 400 | 24px | 1 | -0.02em | The short labels inside the floating navigation bar. |
| poster-body | __haasGrotText_7ea857 | 400 | 22.4px | 1.25 | -0.007em | Supporting prose on tall tilted promotional cards. |
| body-large | __haasGrotText_7ea857 | 400 | 20px | 1.25 | -0.008em | Main explanatory paragraphs and accordion answers. |
| body | __haasGrotText_7ea857 | 400 | 16px | 1.4 | -0.01em | Secondary descriptions and compact quotations. |
| footer-link | __haasGrotText_7ea857 | 400 | 16px | 1.35 | -0.01em | Footer navigation links. |
| mono-caption | __martianMono_eeab0a | 400 | 12px | 1.35 | normal, uppercase | Promotional ticker and quote attributions. |
| ticket | __martianMono_eeab0a | 400 | 12px | 1 | -0.013em, uppercase | Outlined chapter and content-category labels. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalogs and detailed product outlines | catalog-caption | __haasGrotText_7ea857 | 400 | 14px | 1.4 | -0.0114em | Compact item summaries and side-rail outline entries. |

**Notes:**

- Use regular weight throughout. Scale, line breaks, colored paper and alignment do the work that bold type often does elsewhere.
- The two biggest sizes share -0.03em tracking. Smaller headings use fixed -0.5px or -0.2px spacing rather than carrying that tight ratio down indiscriminately.
- Keep numbers within the sentence on proof headings; do not turn an inline audience count into an unrelated giant KPI. Monospace belongs to metadata, not general body text.

## Layout

**Density:** Airy between modules, information-rich within them; broad colored sheets surround compact paragraphs and surprisingly slim controls.

### Spacing

**Spacing system:**

- **grid** 8px — Main layout rhythm: 16px, 24px, 32px, 40px, 48px, 64px and 80px. Small ticket and button padding uses its own compact values.

| Value | Use |
| --- | --- |
| 8px | Heading-to-support spacing and gaps between accordion rows. |
| 16px | Action-row gaps, carousel card gaps and small quote-card padding. |
| 24px | Page side gutters, paper-card padding and split-panel stack gaps. |
| 32px | Split-panel content padding and gallery heading-to-media separation. |
| 40px | Hero text-group-to-actions spacing and detailed outline group spacing. |
| 48px | Default space between independent page modules. |
| 72px | Top inset of FAQ content. |
| 80px | Opening safe area beneath navigation. |
| 120px | Space before the illustrated ending. |

### Containers and grids

- **page-container**: max width 1536px · side padding 24px. Centered broad canvas; at a 1440px viewport the inset panels are 1392px wide.
- **hero-copy**: max width 684px. Centered headline column, with support text constrained to 640.3px.
- **split-panel**: 2 columns · gap 0px. Equal illustration and content halves; a 1392px-wide panel is 392px tall, with 32px padding in the content half.
- **work-preview**: 4 columns · gap 16px. A single row of wide 16:9 work previews beneath a centered introduction.
- **readable-prose**: max width 800px. Long descriptions and expanded answers remain left aligned within much wider panels.
- **catalog-grid** (only for browsable catalogs): 3 columns · gap 24px. Three 330px-wide cards to the right of a filter rail; the underlying page uses a 12-column grid.
- **detail-columns** (only for long product detail pages): 2 columns · gap 24px. A 920px main stack of white information and chapter panels beside a 448px supporting rail.

## Corner radius

| Element | Radius |
| --- | --- |
| panels | 24px |
| posters-and-quotes | 16px |
| media-and-catalog-cards | 8px |
| actions | 48px |
| email-field | 9999px (pill) |

## Surfaces and depth

### Shadows

| Name | Value | Use |
| --- | --- | --- |
| small-paper | `rgba(18, 18, 151, 0.067) 0px 3.2px 4px 0px` | Quote cards and media; just a faint cool contact shadow. |
| raised-paper | `rgba(18, 18, 151, 0.133) 0px 3.2px 4px 0px` | Floating navigation, footer glass and raised social cards. |

### Surfaces

#### Canvas · level 0

**Use:** Default marketing background.

**CSS:** `background: #f0f6ff`

**Observed:** The light ground connects colorful modules without becoming white-on-white.

**Transfer:** Keep the pale ground visible around every large colored sheet.

#### Opening wash · level 0

**Use:** Centered marketing opening.

**CSS:** `background: linear-gradient(#ffffff, #f0f6ff)`

**Observed:** An almost imperceptible white-to-ice-blue change under crisp flat perimeter shapes.

**Transfer:** Keep this wash subtle; the geometry provides saturation.

#### White panel · level 1

**Use:** Information modules, logos and accordion rows.

**CSS:** `background: #ffffff; border-radius: 24px; overflow: clip`

**Observed:** Usually unoutlined, with enough internal space to keep compact text readable.

**Transfer:** Separate information with paper color and spacing, not gray borders around every block.

#### Colored sheet · level 1

**Use:** Feature, invitation and proof panels.

**CSS:** `background: #16ab59; border-radius: 24px; overflow: clip`

**Observed:** Green, yellow, cyan, pink and orange variants fill entire modules. Some split panels add a black gradient ending at 0.067 alpha for barely visible depth.

**Transfer:** Assign a different paper color to a meaningful narrative block rather than to every paragraph.

#### Glass navigation · level 2

**Use:** Floating header and illustrated footer navigation.

**CSS:** `background: rgba(255, 255, 255, 0.9); border-radius: 24px; backdrop-filter: blur(4px); box-shadow: rgba(18, 18, 151, 0.133) 0px 3.2px 4px 0px`

**Observed:** The illustration remains faintly visible through the panel. This is restrained milky glass, not glossy glassmorphism.

**Transfer:** Place the glass above saturated geometry, keeping text opaque and dark.

#### Closing field · level 0

**Use:** The illustrated end of the page.

**CSS:** `background: #e1edff; height: 675px; overflow: hidden; position: relative`

**Observed:** Bright circular tokens rise above and continue behind the low glass panel.

**Transfer:** Keep this as a real visual scene rather than a plain footer strip.

## Components

### Floating navigation

**Use:** Persistent primary navigation.

**CSS:** `background: rgba(255, 255, 255, 0.9); border-radius: 24px; backdrop-filter: blur(4px); box-shadow: rgba(18, 18, 151, 0.133) 0px 3.2px 4px 0px; height: 48px; display: grid; grid-template-columns: auto 1fr auto`

**Text style:** `navigation` — __haasGrotDisp_332926 400 · 24px/1 · tracking -0.02em

**Observed:** An inset horizontal capsule carries a small blue circular identity at left, two short navigation labels, then search and account or purchase links at right. It floats above the page artwork and remains visible during scrolling.

**Transfer:** Keep the label count sparse; use the space between groups as the main organizing device.

### Primary button

**Use:** Main conversion and directional actions.

**CSS:** `background: #2727e6; color: #ffffff; border-radius: 48px; padding: 3.6px 14.4px; height: 40px; display: flex; align-items: center; gap: 7.2px`

**Text style:** `action` — __haasGrotText_7ea857 400 · 24px/1.35 · tracking -0.02em

**Observed:** Most directional actions end in a long thin right arrow. White-on-color is the secondary variant on saturated sheets; smaller utility capsules retain the same construction.

**States:** Declared: hover background-color #121297 and color #fff; focus-visible not specified in the available declarations.

**Transfer:** Let labels determine width rather than forcing identical wide buttons.

### Dark companion button

**Use:** The alternate, low-commitment action beside the opening primary action.

**CSS:** `background: #111118; color: #ffffff; border-radius: 48px; padding: 3.6px 14.4px; height: 40px`

**Text style:** `action` — __haasGrotText_7ea857 400 · 24px/1.35 · tracking -0.02em

**Observed:** Sits alongside the blue capsule, separated by 16px; the dark companion does not need an arrow.

**States:** Declared: hover background-color #58585d and color #fff; focus-visible not specified in the available declarations.

### Tilted poster

**Use:** Large editorial promotion cards inside a contrasting backing sheet.

**CSS:** `background: #e1edff; border-radius: 16px; padding: 24px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `poster-heading` — __haasGrotDisp_332926 400 · 62.7px/1.1 · tracking -0.0077em

**Observed:** A three-card composition uses pale blue, green and orange stock with rotations of -2deg, 3deg and -1.5deg. Heading and paragraph occupy the top, while a white arrow action is anchored at the bottom. The poster body uses poster-body; a small circular free badge can sit at the upper edge.

**Transfer:** Use this construction for distinct entry paths or outcomes, not a generic equal-height icon-feature grid.

### Question accordion

**Use:** Plainspoken objection handling.

**CSS:** `background: #ffffff; border-radius: 24px`

**Text style:** `question` — __haasGrotDisp_332926 400 · 35px/1.15 · tracking -0.0046em

**Observed:** Closed summaries are 72px high, with 16px 24px text-group padding and a 32px plus at the right. Rows are separated by 8px. The open answer uses body-large, a readable left-aligned column and 24px bottom padding; the plus becomes a cross.

**Transfer:** Start with one useful answer expanded and keep subsequent questions concise.

### Metadata ticket

**Use:** Categories, levels, chapters and small classifications.

**CSS:** `background: #ffffff; color: #111118; border: 1px solid #111118; border-radius: 24px; padding: 3px 6px; display: inline-flex`

**Text style:** `ticket` — __martianMono_eeab0a 400 · 12px/1 · tracking -0.013em · uppercase

**Observed:** Tiny outlined capsules coexist with squared labels and pointed-end level tickets. A single hairline and uppercase mono text make the label read like a printed classification rather than a heavy badge.

**Transfer:** Use one or two meaningful classifications per card; adapt the outline to the surrounding text color.

### Email capsule

**Use:** Newsletter invitations.

**CSS:** `background: #f0f6ff; border-radius: 9999px; padding: 12px 68px 12px 16px; height: 42px; width: 427px`

**Observed:** A blue arrow-only submit capsule is inset at the right edge of the pale email field. The form appears within a split color panel or a short blue illustrated band.

**Transfer:** Keep the submit integrated into the field rather than placing a second full-size button below it.

### Quote card

**Use:** Human proof in a playful overlapping composition.

**CSS:** `background: #91d8ec; border-radius: 16px; padding: 16px; box-shadow: rgba(18, 18, 151, 0.067) 0px 3.2px 4px 0px`

**Text style:** `body-large` — __haasGrotText_7ea857 400 · 20px/1.25 · tracking -0.008em

**Observed:** Portrait and uppercase mono attribution sit at the foot. Cards around 320px wide overlap and rotate slightly on a green sheet; blue variants reverse the text, while warm cards keep dark text. Quote sizes vary with length rather than enforcing uniform card typography.

**Transfer:** Make a small pile with at least one fully readable foreground quote and shorter glimpses behind it.

### Footer navigation panel

**Use:** Navigation and small-print information over the closing illustration.

**CSS:** `background: rgba(255, 255, 255, 0.9); border-radius: 24px; padding: 24px; display: grid; grid-template-columns: repeat(12, 1fr); gap: 24px; backdrop-filter: blur(4px); box-shadow: rgba(18, 18, 151, 0.133) 0px 3.2px 4px 0px`

**Text style:** `footer-link` — __haasGrotText_7ea857 400 · 16px/1.35 · tracking -0.01em

**Observed:** A brand mark occupies the broad left half; three navigation groups occupy the right half. Small copyright text sits low left, blue social marks low right. Group headings use body-large, links have 8px vertical gaps and 16px heading-to-list separation.

**Transfer:** Retain the asymmetric left/right balance and illustrated background, even when link counts change.

### Catalog card

**Only for:** catalogs and related-item recommendations

**Use:** Dense browsable product collections.

**CSS:** `background: #ffffff; border-radius: 8px; overflow: hidden`

**Text style:** `lead` — __haasGrotText_7ea857 400 · 24px/1.25 · tracking -0.0067em

**Observed:** A 320px by 480px carousel card or 330px by 495px grid card begins with a 16:9 image, followed by a 24px-padded text block, a compact catalog-caption summary and a bottom row of metadata tickets. Grid gaps are 24px; carousel gaps are 16px.

**Transfer:** Show enough real detail for comparison and keep labels aligned near the bottom.

## Imagery and graphics

### Perimeter geometry

**Use:** Signature opening artwork.

**Observed:** Huge, flat circles, a polygon, a triangle and a starburst are clipped by the viewport. Yellow, cyan, green, pink and red surround a clear central reading space. A small blue disc with a simple white face punctuates the headline stack.

**Transfer:** Create an original geometric alphabet tied to the product's personality. The minimum version is five clean oversized shapes plus a small original character or symbol above the promise.

**Build:** Use an absolutely positioned SVG behind the hero with a central clear zone spanning about half the page width. Place 260px–400px circles at lower left and upper right, a 300px polygon at upper left, and a 250px starburst at lower right; clip the outer artwork at the hero edges. Use flat blue, yellow, cyan, green and pink fills with no shadows. Draw a 72px blue character disc using a few white strokes, or replace the face with an original product-related mark.

### Geometric split-panel patterns

**Use:** Illustrated halves of feature and invitation panels.

**Observed:** Flush edge-to-edge arrangements of circles, quarter circles, rectangles and triangles resemble bright toy blocks. The pattern is large enough to read as a single composition, not tiny decoration. Some panels show real work framed by colored strips instead.

**Transfer:** Use graphic arrangements for abstract benefits and actual work for concrete outcomes.

**Build:** Within one half of a 1392px by 392px rounded panel, create a four-column SVG grid. Fill cells with alternating blue, pink, cyan, yellow and green; insert circles tangent to cell edges, quarter-circle arcs and paired triangles. Use no stroke, maintain hard edges and let adjacent shapes share boundaries. For a work example, back a single wide image with thick bands of these same colors.

### Work demonstrations

**Use:** Outcome galleries and product previews.

**Observed:** Real websites and interactive projects appear as wide images or videos without heavy device mockups. The compact gallery uses four 16:9 frames. The portfolio variant gives one demonstration a 1104px by 621px frame with 8px corners and a narrow metadata column beside it.

**Transfer:** Show the new product's actual outputs at their natural proportions; do not restyle the content inside the demonstration to imitate the marketing typography.

### Closing token playground

**Use:** Required illustrated ending.

**Observed:** A loose pile of roughly 160px-diameter bright circles fills the lower part of an ice-blue field. Some carry white line-drawn faces at different rotations. Tokens remain crisp above the navigation glass and become softly obscured behind it.

**Transfer:** Use an original symbol family on colored discs to make the product's ending memorable without relying on photography.

**Build:** Create an overflow-hidden 675px-high field. Scatter 160px–170px circles across the lower 500px in blue, green, yellow and pink, with a few partially outside the frame. Vary vertical position, overlap and rotation. Add sparse white line symbols to selected tokens. Layer Footer navigation panel above the lower portion, leaving several tokens fully visible above its top edge.

### Grainy geometric collage

**Only for:** product cover artwork and catalog thumbnails

**Use:** Identity images for individual offers.

**Observed:** Dense tilted ribbons, curved tubes, circles, notched sheets, dotted patterns and fine white grids combine electric blue, green, pink and yellow. Soft sprayed grain on the forms adds depth; it is not a glossy photorealistic render. Covers fill their media boxes and become a full-bleed backing on detail openings.

**Transfer:** Create a distinct but related composition per offer. A minimum version combines a grid plane, three angled geometric objects and restrained noise shading.

**Build:** Draw a blue or green SVG ground with a 48px square grid at low white alpha. Layer diagonal rectangular ribbons, semicircular bands, a perforated paper polygon and small confetti shapes. Add a clipped monochrome noise layer over the objects at low opacity, plus a faint dark offset edge to imply depth. Keep the graphic dense at the edges and leave a region of simpler texture where a white title card will overlap.

### Soft procedural color field

**Only for:** experiential demonstration sections

**Use:** A large playful closing demonstration before the footer.

**Observed:** A 1392px-wide, 780px-tall rounded field carries soft, irregular orange and yellow-green flowing bands with subtle grain. A tiny upper-left caption and small lower-left white capsule leave almost the entire surface to the effect.

**Transfer:** Demonstrate a real product behavior if available; otherwise create an original abstract color interaction with the same broad soft scale.

**Build:** Use an SVG filter with low-frequency turbulence and displacement on several broad orange, yellow and green curves, then apply soft blur and a very low-opacity grain layer. Cover the panel without obvious repeated tiles. Keep white text confined to a small upper-left block and place a compact white action near the lower-left edge; match the flowing softness rather than particular color stops.

### Icons

**Observed:** Long, fine right arrows in actions are 30px by 17px with 1px round strokes. Accordion plus/cross marks are 32px with 2px round strokes. Search is an unfilled magnifier; social marks are small solid blue shapes. Tiny category labels use custom outline shapes rather than pictographic icons.

**Transfer:** Keep functional icons sparse and unfilled, in the surrounding text color. Use cheerful original circular symbols as illustration accents, not a large library of multicolor feature icons.

## Section recipes

How recurring sections are built.

### First screen: Geometric promise opening

**Observed:** A 32px blue mono ticker runs across the top. Below it, Floating navigation is inset by 24px and floats over an 800px Opening wash. Oversized perimeter geometry lives behind the content and is clipped by the edges. The centered content column is about 684px wide: a 72px blue character disc above a two-line 92px headline, a 24px two-line support statement, then Primary button and Dark companion button separated by 16px. Text-group gaps are 16px and the action group is separated by 40px. All of the promise, support line, actions and main geometric artwork are visible within the first 900px; only the beginning of the next white proof panel reaches the bottom of that screen.

**Transfer:** Use a concise outcome promise with equally decisive line breaks; invent perimeter geometry and an original circular mark when no product media exists. A catalog can use this same centered frame with a short benefits row instead of actions. A detail page uses a full-bleed illustrated cover with a left-aligned white title card; a portfolio index uses a compact blue introduction with white display type; an organizational story can use a yellow field with a centered promise.

**Avoid:** Do not substitute a conventional left-copy/right-device hero, a full-screen dark gradient, or a cluster of small outlined feature cards for the oversized geometric frame.

**Text style:** `display` — __haasGrotDisp_332926 400 · 92px/1 · tracking -0.03em

### Heading and work strip

**Observed:** A centered heading-lg and body-large support line are separated by 8px. After 32px, Work demonstrations form a four-column row with 16px gaps, followed by a centered Primary button. The section stays on Canvas rather than inside another colored box.

**Transfer:** Use this for visible outcomes, customer artifacts or product examples; give the imagery more width than the introductory copy.

**Text style:** `heading-lg` — __haasGrotDisp_332926 400 · 72px/1 · tracking -0.03em

### Poster promotion sheet

**Observed:** A blush Colored sheet holds an upper-left section-label with a small blue action at upper right. Three Tilted poster cards dominate the remaining panel height, using pale blue, green and orange stock and bottom-anchored white actions.

**Transfer:** Use a few clearly different entry points, each with one outcome-led heading and a short practical explanation.

**Text style:** `poster-heading` — __haasGrotDisp_332926 400 · 62.7px/1.1 · tracking -0.0077em

### Split capability stack

**Observed:** A centered heading-lg and a row of small dot-marked capsules introduce stacked equal-half panels. Each Colored sheet pairs Geometric split-panel patterns or a work preview on the left with a small circular symbol, heading, explanation and white capsule on the right. Panels are 392px tall with 32px content padding and 24px stack gaps.

**Transfer:** Translate benefits into distinct illustrated chapters. Keep one graphic and one text block per sheet rather than subdividing it into miniature cards.

**Text style:** `heading` — __haasGrotDisp_332926 400 · 52px/1.1 · tracking -0.0092em

### Human proof gardens

**Observed:** One version uses a yellow backing and a horizontal run of white 320px social cards with slight rotations, small portraits and expressive quote sizes. The other uses a green backing, an inline section-label count headline and an overlapping central pile of Quote card elements in cyan, yellow, pink, blue and orange. Tiny mono attributions ground the exuberance.

**Transfer:** Use authentic endorsements with a deliberate foreground/background hierarchy; the amount of proof can vary while retaining a handled-paper composition.

**Text style:** `section-label` — __haasGrotDisp_332926 400 · 42px/1.1 · tracking -0.0038em

### Practical question stack

**Observed:** A left-aligned heading-lg sits 36px above Question accordion. The group begins 72px inside its section and spans the broad page container. White rows sit directly on Canvas; only the active answer expands.

**Transfer:** Move from the visual promise into practical specifics using the questions a reader would actually ask.

**Text style:** `heading-lg` — __haasGrotDisp_332926 400 · 72px/1 · tracking -0.03em

### Illustrated newsletter band

**Observed:** A 210px-high blue rounded band with peripheral geometry centers a short white question-size heading above Email capsule. A taller variant places the same form inside a cyan split capability panel.

**Transfer:** Keep subscription copy brief and let the field remain the main action.

**Text style:** `question` — __haasGrotDisp_332926 400 · 35px/1.15 · tracking -0.0046em

### Illustrated glass ending

**Observed:** After 120px of separation, Closing field carries Closing token playground. Footer navigation panel sits across its lower area in 24px side gutters, with a broad left brand zone, three right navigation groups, copyright low left and social marks low right. The same visual ending appears after brief marketing modules and long detail content.

**Transfer:** Finish with a distinct original graphic scene; adapt navigation labels and symbols while preserving the pale field, token scale, glass layer and asymmetric information layout.

**Text style:** `footer-link` — __haasGrotText_7ea857 400 · 16px/1.35 · tracking -0.01em

### Detail cover and chapter stack

**Only for:** long-form product detail pages

**Observed:** A 720px illustrated cover holds a 920px-wide white title panel low on the left with tickets, display heading, lead description, portrait attribution and a blue price action. Below it, the 920px main column uses white panels for introduction, outcomes, requirements and audience, then repeated chapters. Each chapter starts with a 920px by 368px image, followed by a ticket, 72px heading, 16px description, three 256px by 144px thumbnail rows and an arrow capsule. The 448px side rail groups purchase, expert biography, expandable outline and support. After the final chapter the illustrated ending follows directly.

**Transfer:** Use this for products with extensive content or technical depth; preserve readable modules and a supporting rail rather than compressing every chapter into a carousel.

**Text style:** `display` — __haasGrotDisp_332926 400 · 92px/1 · tracking -0.03em

### Portfolio color stage

**Only for:** case-study and outcome indexes

**Observed:** A compact electric-blue introduction uses left-aligned white display type and a small description. Full-width 900px-tall stages then pair a large 1104px by 621px demonstration with a narrow right column of outlined labels, 35px names and 24px links. Each stage borrows a color from its project. Related-item recommendations and a logo strip lead into the illustrated ending.

**Transfer:** Let the work determine each stage's backing and contrast, while keeping the metadata system constant.

**Text style:** `display` — __haasGrotDisp_332926 400 · 92px/1 · tracking -0.03em

## Page flow

**Storyline:** Outcome promise → visible examples → practical entry paths → human proof → answers and low-pressure invitation → illustrated navigation ending.

### Broad marketing landing page

1. **Promise** — Centered display copy inside a clipped geometric frame with two slim actions.
2. **Credibility** — White logo strip and four-image outcome gallery.
3. **Entry paths** — Tilted poster sheet followed by illustrated split invitations.
4. **Social proof** — Social-card garden, practical question stack and overlapping quote pile.
5. **Experiential close** — Large procedural demonstration with a tiny invitation, then token playground and glass footer.

**Transfer:** Choose the proof and entry paths relevant to the new product; retain the geometric opening, human paper treatment and illustrated ending without requiring the same sequence.

### Long-form product detail and purchase page

1. **Offer** — Illustrated cover behind an overlapping white title and purchase panel.
2. **Qualification** — Readable description, outcomes, requirements and audience panels alongside purchase and support information.
3. **Product depth** — Repeated visual chapters with miniature preview lists and individual actions.
4. **Ending** — The final chapter gives way directly to the shared token playground and glass navigation.

**Transfer:** Use when a buyer needs substantive detail; the rail handles practical assistance while the main column demonstrates depth.

### Outcome showcase index

1. **Proof promise** — Compact blue introduction with white display headline and metadata tickets.
2. **Demonstration** — One nearly viewport-height colored stage per piece of work, with a large video and a narrow attribution column.
3. **Next step** — Logo strip and related-offer carousel on a pale backing.
4. **Ending** — Shared illustrated closing field with translucent navigation.

**Transfer:** Use a gallery-led narrative when the outputs themselves make the strongest argument.

### Browsable offer catalog

1. **Orientation** — Centered geometric promise with a short benefit row.
2. **Curation** — Green panel with a popular-items carousel.
3. **Comparison** — Filter rail beside a three-column white-card grid with compact metadata.
4. **Objection handling** — Broad FAQ stack followed by an illustrated email band.
5. **Ending** — Shared circular playground beneath a glass navigation panel.

**Transfer:** Separate editorial curation from exhaustive browsing; keep the dense catalog treatment scoped to discovery tasks.

### Organizational story and trust page

1. **Belief** — Centered display statement on a yellow field with a small circular character.
2. **Method** — Tabbed introduction and colored split-panel chapters.
3. **Trust** — Green overlapping quote pile, logo strip and press-style card carousel.
4. **Invitation and answers** — Illustrated email band and organization-specific questions.
5. **Ending** — Shared token playground and glass navigation.

**Transfer:** Use original values and mechanisms to explain the organization, and back them with concrete outcomes and human voices.

## Writing

Friendly, candid and practical, with the confidence of people who enjoy making things. Playfulness appears in invitations and questions; explanations quickly become concrete about what the reader can do.

**Do not copy:** Do not reuse the SuperHi name, logo, mascot artwork, proprietary illustrations, customer logos, course titles, testimonials, learner totals, discounts or claims. Replace them with original assets and substantiated facts for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Talk directly to you and your; use we and our for the people behind the product. Contractions make practical explanations conversational.
- **Rhythm:** Short outcome-led headlines contrast with complete, useful paragraphs. Actions are brief verb phrases; questions sound spoken. Plus signs connect related concepts, and occasional exclamations signal genuine enthusiasm rather than constant hype.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | A direct, personal invitation toward a useful future. | 5–10 words | “Curate your own creative career”<br>“Your creative learning journey starts here” |
| Section heading | Use everyday language to introduce the reader's decision or question. | 2–7 words | “Don’t know where to start?”<br>“The big questions” |
| Supporting line | Explain the tangible next step or reassure the reader about what is required. | One sentence or a compact paragraph | “Discover some of the fantastic work our students create”<br>“A computer (Windows, Mac or Linux) with the latest version of Chrome installed and a broadband internet connection. Just that!” |
| Action | Use a low-pressure verb or conversational acceptance, with a clear destination. | 2–5 words | “See our catalog”<br>“Count me in”<br>“Let’s start” |
| Experiential caption | Ask a playful, slightly challenging question, then connect it to a practical outcome. | A short question plus one sentence | “Love or hate this effect?” |

**Words and phrasing to use:** make; create; your own; from scratch; practical; get to know; real-life; friendly; start; show-don’t-tell

**Avoid:** revolutionary ecosystem; unlock unparalleled potential; enterprise-grade synergy; effortless mastery; guaranteed transformation

**Rules:**

- Lead with what the reader can make or accomplish, then explain the mechanism.
- Use reassuring specifics instead of vague ease claims: equipment, starting point, support and access details.
- Keep metadata factual and compressed; save warmth for headlines, invitations and body copy.
- Let actual proof carry credibility rather than adding a self-congratulatory adjective to every claim.

## Do's and Don'ts

### Do

- Keep the largest headline at 92px/1, weight 400 and -0.03em tracking at the desktop composition.
- Use 24px gutters and 48px between independent modules so the ice-blue canvas stays visible.
- Combine large 24px-radius sheets with smaller 16px paper cards; preserve the difference in scale.
- Keep the primary capsule only 40px tall even though its label is 24px.
- Give split panels equal-width halves and 32px content padding.
- Pair saturated proof surfaces with authentic portraits and 12px uppercase mono attributions.
- Show work in wide natural-aspect frames with 8px corners rather than decorative hardware mockups.
- End with bright circular tokens behind 0.9-alpha white glass and a 4px backdrop blur.

### Don't

- Do not use semibold or bold headlines to create emphasis; the hierarchy is regular-weight and scale-led.
- Do not turn all white information panels into heavily bordered cards; reserve the 1px ink outline for tiny metadata.
- Do not apply a deep gray page background to imitate the occasional dark project demonstration.
- Do not replace the 30px thin action arrow with a filled chevron in a separate square.
- Do not use 16px UI text for the main conversion capsules; the characteristic label size is 24px.
- Do not make every card rotate; the catalog and detailed information modules remain orderly.
- Do not spread testimonials into a sterile uniform three-column grid when using the paper-pile proof treatment.
- Do not add thick drop shadows or glass highlights; the strongest paper shadow is only 3.2px down with 4px blur.

## Motion and responsive

### Motion

**Observed:**

- Action color transitions use 0.2s cubic-bezier(0.37,0,0.63,1). Arrow transforms use 0.4s cubic-bezier(0.34,1.56,0.64,1).
- Header entries declare 0.4s animation with 0.4s delay and the same spring-like cubic-bezier(0.34,1.56,0.64,1).
- Split capability panels use sticky positioning; horizontal poster and card collections allow horizontal scrolling. Quote cards are arranged as draggable-looking layered pieces.
- A repeated promotional ticker, character animation and procedural demonstration provide small pockets of play.

**Transfer:**

- Use the declared spring-like transform treatment for thin arrows and navigation entries, while keeping color transitions short and controlled.
- Concentrate playful motion in geometric artwork and card compositions rather than making every paragraph animate.

**Unknown:**

- Exact ticker speed, procedural field timing, character animation sequencing and drag behavior are not established.
- Complete focus-visible and active-state designs are not established.

### Responsive

**Observed:**

- Styles declare width breakpoints at 640px, 896px, 1152px and 1440px.
- The catalog results grid uses repeat(auto-fill, minmax(288px, 1fr)); broad containers have a 1536px maximum width.

**Transfer:**

- On narrow screens, preserve the clear central promise and let perimeter shapes clip farther outside the opening rather than shrinking them into decorative icons.
- Stack illustration and copy halves, and move detail-page supporting information into the reading flow. Retain the distinction between broad colored sheets and compact paper cards.
- Keep horizontally browsable collections recognizably card-based rather than reducing their copy to unreadable type.

**Unknown:**

- Exact mobile font sizes, navigation collapse, footer stacking and mobile artwork behavior are not established; the narrow-screen guidance is a design recommendation.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
