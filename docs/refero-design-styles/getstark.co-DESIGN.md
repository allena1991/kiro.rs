# Stark — marker-bright software optimism

## Overview

A warm, light software-marketing style with the energy of a helpful workshop rather than a sterile enterprise dashboard. Heavy rounded grotesk headlines, violet and navy, butter-yellow marker strokes and mint panels make technical products feel approachable. Large interface collages mingle with hand-drawn diagrams, grainy color clouds and small human details; the overall density is spacious, with concentrated pockets of practical information.

### Essentials

- Headlines feel like bold statements marked by hand: ArminGrotesk at 900, 110px/1.1 with -0.02em tracking in the opening, and 56px/1.1 with -0.01em tracking for chapters; a skew-ended yellow highlight picks out one meaningful phrase.
- The default opening is a violet product theater, not a split white sales pitch: a centered 1000px-wide headline, 650px support line and yellow 44px action sit above a browser interface rising through the fold.
- Cream owns most of the scrolling canvas: #f6f6eb backs the long middle, #10284b carries text and the full-width ending, and #381fd1 concentrates in the opening, actions and small labels. A 1024px mint benefit panel and pale-lilac closing panel punctuate rather than replace the cream.
- Controls are small, rectangular tools against oversized words: 6px corners, 2px borders, 44px main actions with 6px 24px padding, and 32px uppercase navigation controls.
- Product images dissolve into the page instead of sitting in uniform cards: 1200px-wide layered browser scenes fade at the lower edge; outlined doodles, violet halftone shapes and occasional circular portraits make them human. Without finished product media, use a legible representative interface framed by the same drawn accents.
- The page combines a marker phrase, an illustrated benefit device and a substantial navy directory ending: 40px-radius color panels group benefits, while the footer pairs cream links with a yellow 16px uppercase mono maker line.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep navy | `#10284b` | `--color-ink` | text, background, border | Default text, illustration outlines and footer field. |
| Electric violet | `#381fd1` | `--color-primary` | background, action, link, accent, border | Opening field, filled actions, headings in compact feature groups and technical labels. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Butter yellow | `#fedb63` | `--color-marker` | accent, action, text | Headline marker strips, opening action and footer maker line. |
| Soft mint | `#99d6cc` | `--color-mint` | surface | Large benefits panel and selected drawn details. |
| Selected lavender | `#e5e0ff` | `--color-selected` | surface | Active audience row within the lilac panel. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-white` | text, surface | Opening text, interface windows, inverse navigation and the highlighted pricing plan. |
| Lilac paper | `#faf5ff` | `--color-lilac-panel` | surface | Broad audience-switching closing panel. |
| Warm cream | `#f6f6eb` | `--color-canvas` | background, text | Long-form page canvas and light footer links. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience landing pages | Trial lavender wash | `#f3f2fc` | `--color-trial-wash` | surface | Compact outlined closing trial banner. |
| pricing pages | Dark cream | `#edede0` | `--color-comparison-row` | surface | Alternating comparison rows. |
| pricing pages | Bracket gray | `#acacaf` | `--color-bracket` | border | Fine grouping brackets above pricing cards. |
| pricing pages | Selector edge | `#e6e6e6` | `--color-selector-edge` | border | Visible black at 10% over the white segmented selector. |

## Typography

- **ArminGrotesk** — All marketing headings, paragraphs, controls and navigation. Friendly wide grotesk with rounded bowls and a dense, emphatic black cut. If unavailable, use **DM Sans**. Use 400–900; preserve broad headline measure and negative tracking. Font stack: "ArminGrotesk", "DM Sans", Arial, sans-serif.
- **RobotoMono** — Section eyebrows, feature captions and the footer maker line. Bold technical monospace, uppercase with open letterspacing. If unavailable, use **Roboto Mono**. Font stack: "RobotoMono", "Roboto Mono", ui-monospace, monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | ArminGrotesk | 900 | 110px | 1.1 | -0.02em | Centered white headline in the default opening. |
| heading | ArminGrotesk | 900 | 56px | 1.1 | -0.01em | Main chapter headings and large benefit-panel promise. |
| heading-compact | ArminGrotesk | 900 | 48px | 1.1 | -0.01em | Platform overview heading; also pricing title and price figures. |
| feature-title | ArminGrotesk | 900 | 24px | 1.1 | normal | Illustrated feature columns, benefit titles and audience rows. |
| lead | ArminGrotesk | 400 | 20px | 1.5 | normal | Opening support and centered chapter explanations. |
| body | ArminGrotesk | 400 | 16px | 1.7 | normal | Narrow feature columns and benefit descriptions. |
| eyebrow | RobotoMono | 700 | 16px | 1.4 | 0.08em, uppercase | Section identifiers; recolor yellow for footer maker text. |
| button | ArminGrotesk | 600 | 16px | 1.5 | 0.02em | Main and secondary action labels. |
| footer-link | ArminGrotesk | 600 | 16px | 1.7 | normal | Cream links in the directory footer. |
| navigation | ArminGrotesk | 900 | 14px | 20px | 0.08em, uppercase | Header links and compact demo action. |
| footer-label | ArminGrotesk | 900 | 14px | 1.5 | 0.08em, uppercase | White directory column labels. |
| feature-caption | RobotoMono | 700 | 12.8px | 1.4 | 0.08em, uppercase | Short utility statement above each illustrated feature title. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| audience landing pages | audience-display | ArminGrotesk | 900 | 86px | 1.2 | -0.02em | Left-aligned opening headline beside an oversized interface. |
| pricing pages | table-heading | ArminGrotesk | 900 | 32px | 1.1 | normal | Comparison category headings. |
| pricing pages | plan-name | ArminGrotesk | 800 | 22px | 1.5 | normal | Plan names at the top of purchase cards. |
| pricing pages | table-text | ArminGrotesk | 600 | 16px | 1.5 | normal | Comparison cells and selected audience segment. |

**Notes:**

- Black-weight headings are the expressive voice; paragraph text remains regular rather than competing with it.
- Tight tracking is reserved for the two largest headline scales; small navigation and mono labels open out to 0.08em.
- Keep marker words in the same type recipe as their surrounding headline. The highlight changes the backing, not the font size.
- Default chapter headings are centered, usually two lines; compact column text is left-aligned.

## Layout

**Density:** Airy image-led chapters, with dense but readable feature columns and comparison rows.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Footer label-to-link spacing and small control interiors. |
| 12px | Feature title margins and pricing column gutters. |
| 16px | Headline-to-support spacing, outer section gutters and stacked action gaps. |
| 24px | Action horizontal padding and selected audience row padding. |
| 32px | Support-to-action gap and eyebrow-to-heading spacing. |
| 48px | Four-column overview and footer grid gaps. |
| 56px | Lilac panel interior and desktop trial-banner side padding. |
| 64px | Mint panel interior and shorter section separation. |
| 80px | Benefit column gutter and footer top/bottom rhythm. |
| 96px | Space before the navy footer. |
| 144px | Main image-led chapter separation. |

### Containers and grids

- **media-stage**: max width 1200px · side padding 16px. Centered large image stage; interfaces can overlap the opening and fade into the text section.
- **text-overview**: max width 960px · side padding 16px. Header navigation and illustrated platform overview.
- **reading-measure**: max width 780px. Typical centered chapter support, narrower than the image above.
- **color-panel**: max width 1024px · side padding 16px. Contained mint and lilac sections, keeping cream visible on both sides.
- **feature-grid**: max width 960px · 4 columns · gap 48px. Equal unboxed illustration columns; each approximately 204px wide.
- **benefit-grid**: 2 columns · gap 80px. Two columns of illustrated outcomes inside the mint panel.
- **footer-directory**: max width 1160px · 4 columns · gap 48px · side padding 24px. Two tiers of directory groups, followed by a full-width social and maker row.
- **pricing-grid** (only for pricing pages): max width 1316px · 4 columns · gap 12px · side padding 24px. Four top-aligned plan cards with content-driven unequal heights.
- **comparison** (only for pricing pages): max width 1098px · side padding 16px. Outlined table; a broad feature column takes about 40% of the inner width, with four centered value columns.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | controls | 6px |
|  | color-panels | 40px |
|  | selected-audience | 20px |
| audience landing pages | trial-banner | 12px |
| pricing pages | plan-cards | 8px |
| pricing pages | comparison-frame | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| pricing pages | selected-segment | `0px 4px 6px -1px rgba(0,0,0,0.1), 0px 2px 4px -2px rgba(0,0,0,0.1)` | A small lift on the active audience selector; not a general card shadow. |

### Surfaces

#### Cream canvas · level 0

**Use:** Default reading field.

**CSS:** `background: #f6f6eb; color: #10284b`

#### Violet opening · level 0

**Use:** Default product-theater opening.

**CSS:** `background-color: #381fd1; color: #ffffff; overflow: hidden`

**Observed:** Violet remains saturated through the text area; the lower field blooms with warm magenta and blue haze behind chart stems and interface fragments.

**Transfer:** Keep the headline area high-contrast and put atmospheric complexity below and to the sides, using the Opening atmosphere recipe.

#### Mint benefits · level 1

**Use:** A contained business-outcome chapter.

**CSS:** `background: #99d6cc; border-radius: 40px; padding: 64px; box-shadow: none`

**Observed:** A wide rounded field with centered title and unboxed illustrated outcomes beneath.

**Transfer:** Group consequential benefits without turning each one into a separate tile.

#### Lilac audience panel · level 1

**Use:** A closing product-and-audience chapter.

**CSS:** `background: #faf5ff; border-radius: 40px; padding: 56px`

**Observed:** A large interface extends beyond the left edge; the right side holds the heading and audience rows.

**Transfer:** Use the broad panel as a stage, not a clipping container for its illustration.

#### Navy directory · level 0

**Use:** Full-width ending.

**CSS:** `background: #10284b; color: #f6f6eb; padding: 0px 24px`

**Observed:** Flat color, without a gradient or card enclosure; light links and a yellow maker line provide the contrast.

#### Comparison stripe · level 1

**Only for:** pricing pages

**Use:** Alternate table rows.

**CSS:** `background: #edede0`

**Observed:** Color bands replace cell borders; long grouped rows retain the same striping logic.

## Components

### Primary button

**Use:** Main action on cream or pastel surfaces.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #381fd1; color: #ffffff; border: 2px solid transparent; border-radius: 6px; min-height: 44px; padding: 6px 24px`

**Text style:** `button` — ArminGrotesk 600 · 16px/1.5 · tracking 0.02em

**Observed:** A centered text-only action follows chapter copy. An outlined secondary variant uses a violet border and violet text on the surrounding field; the recommended plan uses the filled version.

**States:** Declared: hover background-color #5740e2 and color #ffffff; focus-visible 2px solid #0057b8 outline with 4px offset; active scale 0.99 and background-color #2c19a4.

### Opening button

**Use:** Single main conversion in the violet opening.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #fedb63; color: #10284b; border: 2px solid transparent; border-radius: 6px; min-height: 44px; padding: 6px 24px`

**Text style:** `button` — ArminGrotesk 600 · 16px/1.5 · tracking 0.02em

**Observed:** The warm action is the opening's strongest compact accent, set below the support paragraph.

**States:** Declared: hover opacity 0.9; focus-visible 2px solid #f6f6eb outline with 4px offset; active scale 0.99 and opacity 0.9.

### Navigation control

**Use:** Compact top-level site navigation.

**CSS:** `display: flex; align-items: center; height: 32px; padding: 0px 8px; color: #ffffff; border: 2px solid transparent; border-radius: 6px`

**Text style:** `navigation` — ArminGrotesk 900 · 14px/20px · tracking 0.08em · uppercase

**Observed:** A 64px-high header centers a 960px row with a small symbol on the left, links and dropdown chevrons, then login and a white demo action. Light-page variant uses violet text and a filled violet demo action.

**States:** Declared: hover border-color #ffffff; focus-visible border-color #ffffff and 2px solid #f6f6eb outline with 4px offset.

### Marker phrase

**Use:** A key benefit phrase within a headline.

**CSS:** `color: #10284b; padding: 0px 16.8px; margin: 0px -16.8px; background-image: linear-gradient(to right bottom, rgba(0,0,0,0) 50%, #fedb63 50%), linear-gradient(#fedb63, #fedb63), linear-gradient(to left top, rgba(0,0,0,0) 50%, #fedb63 50%); background-size: 16px 56px, calc(100% - 48px) 56px, 16px 56px; background-position: 16px 50%, 32px 50%, 100% 50%; background-repeat: no-repeat`

**Text style:** `heading` — ArminGrotesk 900 · 56px/1.1 · tracking -0.01em

**Observed:** The strip has slanted ends and sits behind the full letter height, not below it as an underline. A compact overview variant uses white letters on violet; the comparison title uses mint.

**Transfer:** Highlight a single clause whose meaning deserves emphasis; scale the strip with the heading recipe.

### Illustrated feature column

**Use:** Platform capability overview.

**CSS:** `max-width: 205px; color: #10284b`

**Text style:** `body` — ArminGrotesk 400 · 16px/1.7

**Observed:** Order is a 205px by 156px hand-drawn vignette, Feature-caption, violet Feature-title, then a narrow paragraph. Columns have no border, shadow or painted card backing.

**Transfer:** Give each capability one concrete visual metaphor and one practical paragraph.

### Audience row

**Use:** Clickable audience choices within the lilac panel.

**CSS:** `background: #e5e0ff; border-radius: 20px; padding: 24px`

**Text style:** `feature-title` — ArminGrotesk 900 · 24px/1.1

**Observed:** The selected row has a lavender backing; other rows retain the panel field. Each row stacks a violet title over a short navy description. Only one row is emphasized at once.

**Transfer:** Pair different roles or use cases with the adjacent product scene rather than unrelated icons.

### Footer link group

**Use:** Deep directory navigation in the navy ending.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; color: #f6f6eb; gap: 8px`

**Text style:** `footer-link` — ArminGrotesk 600 · 16px/1.7

**Observed:** A Footer-label precedes a vertical link list. Four columns span the first tier and the remaining groups form a second tier; long labels wrap naturally. Links are visually plain at rest.

**States:** Declared: focus-visible 2px solid #f6f6eb outline with 4px offset.

### Trial banner

**Only for:** audience landing pages

**Use:** Compact final conversion invitation.

**CSS:** `display: flex; align-items: center; gap: 16px; background: #f3f2fc; border: 2px solid #381fd1; border-radius: 12px; padding: 16px 56px; max-width: 1024px`

**Text style:** `lead` — ArminGrotesk 400 · 20px/1.5

**Observed:** A violet seal-like symbol leads an inline bold invitation and regular support sentence; a Primary button sits at the right. The banner has 144px above and 160px below.

**Transfer:** Preserve the small, helpful invitation rather than inflating it into another hero.

### Plan card

**Only for:** pricing pages

**Use:** Purchase options and feature inclusions.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; border: 2px solid #10284b; border-radius: 8px; padding: 24px 24px 8px 32px; width: 320px`

**Text style:** `plan-name` — ArminGrotesk 800 · 22px/1.5

**Observed:** Stack plan name, short audience description, price prefix, large price, billing qualifier, full-width action and checked feature list. White fill, violet outline and filled action distinguish one recommended plan; the others remain cream with outlined actions. Fine gray brackets group plans above the cards.

**Transfer:** Let feature quantity determine height; do not stretch all cards to match the longest list.

### Audience selector

**Only for:** pricing pages

**Use:** Switching team and individual pricing.

**CSS:** `display: flex; align-items: center; height: 40px; background: #ffffff; border: 1px solid rgba(0,0,0,0.1); border-radius: 6px`

**Text style:** `table-text` — ArminGrotesk 600 · 16px/1.5

**Observed:** Two equal 200px segments. The selected segment receives a violet 2px outline, violet text, check icon and small shadow; the inactive segment stays unoutlined.

### Comparison table

**Only for:** pricing pages

**Use:** Detailed plan differentiation.

**CSS:** `border: 2px solid #381fd1; border-radius: 12px; padding: 16px; max-width: 1098px`

**Text style:** `table-text` — ArminGrotesk 600 · 16px/1.5

**Observed:** A plan-name/action header precedes category headings, short violet descriptions and 61px rows. Comparison stripe alternates with cream. Violet filled checks mean inclusion, navy open circles indicate a distinct availability state, and navy dashes show absence; small chevrons introduce expandable feature rows.

**Transfer:** Keep the feature column left-aligned and values centered; state icon meanings in accessible text.

## Imagery and graphics

### Opening atmosphere

**Use:** Behind and beneath the default opening promise.

**Observed:** A violet-to-magenta haze, fine grain and a low perspective grid back translucent status chips, circular avatars and a field of thin violet chart stems with white round tips. A white browser window rises from the lower center, partly outside the first screen.

**Transfer:** Make the graphic about the new product's visible output. At minimum, use a clean browser interface and an abstract stem chart or workflow field; keep the headline foreground uncluttered.

**Build:** Use #381fd1 as the base. Layer broad blurred radial pools of rgba(254,219,99,0.18), rgba(153,214,204,0.12) and rgba(255,255,255,0.12) in the bottom half, plus a magenta-tinted translucent glow. Add a low-opacity SVG grain overlay and fine perspective lines converging toward the center. Build the stem field with repeated 8px-wide rounded bars of varied height and 14px white circular tips; keep it below the action. Add 2–3 translucent rounded chips at the sides, then a centered browser panel in front. Match the soft glow; exact stops are not essential.

### Floating interface scenes

**Use:** Large chapter illustrations and the opening product reveal.

**Observed:** Real interface windows dominate a 1200px stage, often layered with a smaller floating inspector. Soft shadows give windows lift; their lower edges dissolve into cream. Some scenes add circular portraits, a violet speech pill, tiny hand-drawn rays or a fan of rotated tool panels.

**Transfer:** Show a readable representative workflow rather than a wall of tiny dashboards. If no finished interface exists, create a focused example with one main document and one tool panel. Retain the cream fade and limited colored accents.

**Build:** Layer a wide browser window behind one smaller inspector; fan secondary windows by roughly 4–8 degrees when showing breadth. Apply a bottom mask transitioning to transparent over the final quarter of the scene. Put subtle violet and mint blurred ellipses and a sparse halftone blob behind the windows; add three short navy or violet SVG rays near a focal corner.

### Drawn capability vignettes

**Use:** Feature overview and benefit panel.

**Observed:** Small paper-like diagrams use uneven navy outlines, lilac panes, mint notes and yellow badges. Browser frames, rockets, documents and shields have a friendly marker-drawn character rather than photorealistic volume.

**Transfer:** Choose a simple metaphor for each new benefit. A minimum equivalent is an original SVG with an irregular outline, two pastel fills and one violet accent; avoid polished stock 3D.

**Build:** Draw layered rectangles, tabs, notes or a single symbolic object with 2px navy strokes and rounded joins. Offset a second irregular contour slightly for hand-drawn character. Fill major pieces with #e5e0ff, #99d6cc and #ffffff, reserving #fedb63 for a small badge and #381fd1 for one emphatic detail. Add sparse dots and short rays rather than a uniform texture.

### Orbit and bubble diagrams

**Use:** Integration breadth and trust chapters.

**Observed:** A central violet symbol is surrounded by differently sized white logo discs in the integration scene. The trust scene uses a lilac shield with orbiting mint dots, irregular navy ellipses and white violet-outlined label stickers. Both are wide, airy diagrams on cream.

**Transfer:** For another product, put its organizing concept at the center and its related capabilities on satellites. Keep labels few and make their relationship clear.

**Build:** Use three nested SVG ellipses tilted about -15 degrees with 2px #10284b outlines. Scatter #99d6cc circles on the paths, place a simple center emblem and add white rounded labels with violet inner outlines. For an integration version, replace ellipses with loosely arranged circular discs, keeping the largest disc in the center.

### Closing spill-out composition

**Use:** Around the lilac audience panel.

**Observed:** An oversized browser scene exits the left edge while a solid violet organic ribbon and a grainy violet contour extend outside the panel. The text remains cleanly aligned inside its right half.

**Transfer:** Use the product's own interface and a simple original flowing backdrop to make the final product scene feel larger than its container.

**Build:** Place the interface in an overflow-visible wrapper above a 1024px panel. Behind it, draw a thick violet SVG S-curve entering from the upper left and a broad irregular blob on the lower right. Fill the blob with a tiny violet dot pattern fading at its edges; keep both behind the panel text.

### Monochrome proof strip

**Use:** A short trust interlude within the light canvas.

**Observed:** Customer marks are reduced to navy, aligned by visual weight rather than identical dimensions, and extend horizontally beyond the viewport with soft edge fades.

**Transfer:** Use authorized proof marks or short textual proof units in the same single-color treatment; preserve the horizontal, low-height rhythm.

### Icons

**Observed:** Marketing controls use small solid 12px chevrons; comparison tables use 24px violet filled checks and navy 2px round-stroke circles and chevrons. Benefit illustrations are larger hand-drawn symbols, not the same icon system.

**Transfer:** Use consistent simple SVG controls for interaction, and reserve irregular illustrative marks for storytelling. Do not turn every feature illustration into a tiny UI glyph.

## Section recipes

How recurring sections are built.

### First screen: Violet product theater

**Observed:** The first 900px contains a 64px navigation strip, a centered three-line white Display headline spanning roughly two thirds of the page, a 650px-wide Lead paragraph, a yellow Opening button, and the top of a large white browser scene entering at the bottom. The heading starts after a generous upper pause and occupies about 360px of height. Layers run from Violet opening and Opening atmosphere to side status fragments, stem chart, browser window, then crisp headline and action. Most of the browser interface and its multi-device continuation fall below the fold.

**Transfer:** Use one large outcome promise, not a list of capabilities. Recreate the lower-stage data or workflow art with the new product's own representative interface. Audience pages instead open on cream with an 86px left-aligned headline, eyebrow, explanation and vertically stacked filled/outlined actions beside oversized media; pricing opens compactly with a 48px title, selector and plan cards visible in the first screen.

**Avoid:** Do not replace the theatrical centered opening with a generic equal-width text-and-small-card split, or put the entire interface above the fold by shrinking the headline.

**Text style:** `display` — ArminGrotesk 900 · 110px/1.1 · tracking -0.02em

### Image-first benefit chapter

**Observed:** A 1200px Floating interface scene leads into a centered two-line Heading with Marker phrase, a Lead paragraph within about 780px and a Primary button 32px later. Chapters are separated by 144px rather than boxed into alternating full-width bands.

**Transfer:** Give each chapter one visible workflow and one benefit; use a drawn diagram instead of an interface when the idea is conceptual.

**Text style:** `heading` — ArminGrotesk 900 · 56px/1.1 · tracking -0.01em

### Illustrated platform overview

**Observed:** A centered Eyebrow sits 32px above a two-line Heading-compact with an inverse violet marker phrase. Four Illustrated feature columns sit beneath it in a 960px grid with 48px gaps. A centered Primary button can follow the columns.

**Transfer:** Use parallel capability descriptions, each with its own small metaphor, caption and practical paragraph.

**Text style:** `heading-compact` — ArminGrotesk 900 · 48px/1.1 · tracking -0.01em

### Mint outcome panel

**Observed:** Mint benefits contains a centered Eyebrow and large two-line Heading, followed by two rows of two illustrated outcomes. Each has a hand-drawn symbol, violet Feature-title and Body copy. The 64px padding and 80px column gap make it read as one shared field.

**Transfer:** Translate capabilities into business or user outcomes; place any numerical proof inside the explanatory sentence rather than building an unrelated giant-stat wall.

**Text style:** `heading` — ArminGrotesk 900 · 56px/1.1 · tracking -0.01em

### Audience product finale

**Observed:** Lilac audience panel has an oversized left-side interface spill-out and right-side eyebrow, two-line Heading with yellow Marker phrase, and four Audience rows. The first row is lavender while the others are plain. Organic violet backing art extends outside the panel.

**Transfer:** End a general landing narrative by showing how different people participate in the same workflow; keep the adjacent media relevant to the selected role.

**Text style:** `heading` — ArminGrotesk 900 · 56px/1.1 · tracking -0.01em

### Directory ending

**Observed:** Navy directory spans the full width. A 1160px interior begins 80px down, with four columns and 48px gaps across two tiers. After another 80px pause, small circular social marks sit left and a yellow uppercase mono maker/copyright line sits right; the ending leaves about 80px below.

**Transfer:** Retain the substantial information-rich ending and warm maker voice. Organize destinations around the new product rather than substituting a giant closing slogan.

**Text style:** `footer-label` — ArminGrotesk 900 · 14px/1.5 · tracking 0.08em · uppercase

### Feature fan and inventory

**Only for:** audience landing pages

**Observed:** A broad fan of overlapping product panels fades into cream above a centered Heading and yellow marker phrase. A two-column inventory of small violet icons and short feature labels continues beneath.

**Transfer:** After focused workflow chapters, show breadth without adding another grid of heavy cards.

**Text style:** `heading` — ArminGrotesk 900 · 56px/1.1 · tracking -0.01em

### Compact trial close

**Only for:** audience landing pages

**Observed:** Trial banner sits alone on cream with 144px above and 160px below; its seal, inline invitation and action form a horizontal row before the navy footer.

**Transfer:** Use a friendly, low-pressure trial invitation after the full product explanation.

**Text style:** `lead` — ArminGrotesk 400 · 20px/1.5

### Pricing choices and deep comparison

**Only for:** pricing pages

**Observed:** A centered 48px title with yellow marker leads to Audience selector, support copy and four Plan cards. Beneath them, a mint-marked 48px comparison heading introduces Comparison table. Category sections create generous breaks within the dense data; a Monochrome proof strip follows the table before the footer.

**Transfer:** Keep initial decisions skimmable and reserve exhaustive differences for the outlined table. Highlight one recommended option with white fill and violet.

**Text style:** `heading-compact` — ArminGrotesk 900 · 48px/1.1 · tracking -0.01em

## Page flow

**Storyline:** Outcome promise → visible workflow → capability breadth and practical proof → business reassurance → audience fit or final invitation → useful directory ending.

### Broad product marketing landing page

1. **promise** — Violet product theater pairs an ambitious automation outcome with a lower-fold browser reveal.
2. **product demonstration** — Multi-device product scene and a marked speed benefit establish everyday usefulness.
3. **social proof** — A low monochrome logo strip establishes adoption.
4. **capability breadth** — Four illustrated overview columns introduce the platform's main jobs.
5. **capability chapters** — Large interface, integration and trust diagrams alternate with marked headings and actions.
6. **business reassurance** — The mint panel collects four practical outcomes.
7. **audience fit** — The lilac product finale connects roles to a shared workflow.
8. **directory ending** — A deep navy footer closes with social links and a yellow maker line.

**Transfer:** Use image-led chapters to move from promise to practical confidence; adapt their number and sequence to the new product.

### Technical audience landing page

1. **audience promise** — Cream split opening pairs a task-specific 86px headline and two stacked actions with a large code-oriented interface.
2. **workflow demonstration** — Focused chapters show direct tooling, handoff and reporting.
3. **capability breadth** — A fan of panels leads into a compact feature inventory.
4. **business reassurance** — Mint benefits connect tool use to organizational outcomes.
5. **platform context** — Illustrated overview places the specific workflow in a wider suite.
6. **closing call** — A compact outlined trial invitation precedes the shared navy ending.

**Transfer:** Make the opening and first demonstrations specific to the reader's tools, while keeping the same lighter overview and ending.

### Creative audience landing page

1. **audience promise** — Cream split opening features a short outcome headline and a foreground tool panel over a design canvas.
2. **workflow demonstration** — Large interface chapters show assisted problem-solving, handoff and reporting.
3. **capability breadth** — A feature fan and inventory convey range without a dense card wall.
4. **business reassurance** — Mint outcomes reinforce the broader value.
5. **platform context** — Four illustrated columns widen the story beyond the individual task.
6. **closing call** — The small trial banner and deep navy directory complete the page.

**Transfer:** Use imagery that shows the creative reader's familiar canvas; keep proof concrete and the actions straightforward.

### Purchase and plan evaluation page

1. **decision framing** — Compact centered title, two-part audience selector and short upgrade explanation.
2. **pricing** — Four outlined cards align at the top, with one white and violet recommendation.
3. **objection handling** — A long outlined comparison table groups features by category, mixing striped rows, checks and expandable details.
4. **social proof** — A monochrome trust strip appears after the detailed comparison.
5. **directory ending** — The same navy directory and yellow maker line finish the page without another large sales pitch.

**Transfer:** Prioritize purchase clarity over decorative media, retaining marker headings, warm cream, violet controls and the shared ending.

## Writing

Confident, practical and upbeat, with a little workshop humor. Technical detail supports the benefit rather than making the voice institutional.

**Do not copy:** Do not reuse Stark names, logos, customer marks, interface artwork, proprietary feature names, customer counts, performance statistics, certification claims or copyrighted copy as claims for another product. Source quotations below illustrate voice only.

- **Addressing the reader:** Speak directly to you and your team; use the product name for capabilities and we for human commitments.
- **Rhythm:** Short emphatic headlines and paired clauses sit over fuller explanatory paragraphs. Sentence fragments and occasional playful turns lighten concrete technical language.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | A broad outcome expressed as an easy new state, or a clipped three-beat audience promise. | 3–8 words | “Digital accessibility compliance on autopilot”<br>“Ready. Set. Accessible Code.”<br>“Accessible, by design” |
| Chapter headline | Lead with a practical capability, then complete it with the user's benefit. | 6–13 words | “Integrated into the tools you already use”<br>“Real-time reports and insights to keep your projects on track” |
| Supporting paragraph | Name familiar working contexts, explain what changes and remove a specific source of friction. | 35–70 words | “Meet your team where they work, from Figma and Sketch to GitHub and their browser of choice. An accessibility workflow built right into the tools they love. No need for them to switch or relearn.” |
| Eyebrow | A short orientation label, not a second headline. | 2–6 words | “Explore the [Brand] platform”<br>“Streamlining workflows, consolidating tools” |
| Primary action | An imperative that names the next step and lowers commitment. | 3–5 words | “Get started for free”<br>“Start a free team trial” |
| Playful transition | A familiar turn of phrase anchors an otherwise concrete explanation. | 6–10 words | “Come for the features, stay for the magic”<br>“Specs never seemed so spectacular.” |

**Words and phrasing to use:** your team; workflow; find and fix; real-time; built right into; from … to …; in one place; get started

**Avoid:** revolutionary paradigm; synergy; disrupt everything; unqualified best-in-the-world promises; abstract transformation without a task

**Rules:**

- Give each headline one outcome that a reader can picture.
- Attach technical terms to recognizable tasks and explain their payoff.
- Use verified numbers in context rather than decorative numerical spectacle.
- Keep playful language to transitions and small human moments; preserve precision in billing and feature descriptions.

## Do's and Don'ts

### Do

- Keep chapter headlines at 56px/1.1 and weight 900; preserve their dense, rounded presence.
- Use the 1200px image stage against a narrower centered reading measure.
- Carry navy text through cream and mint sections rather than switching body copy to black.
- Use a yellow skew-ended marker behind a meaningful headline phrase.
- Keep main actions 44px tall with 6px corners and 2px borders.
- Use 40px corners for the large mint and lilac fields, not for every control.
- Pair small mono labels with 0.08em tracking and ordinary sentence-case paragraphs.
- Finish with a navy directory, cream links and the yellow mono maker line.

### Don't

- Do not replace the warm #f6f6eb middle with stark white throughout.
- Do not turn violet into a thin accent used only on tiny links; it must anchor the opening and controls.
- Do not use light-weight or condensed display type in place of the 900-weight grotesk.
- Do not render chapter marker strips as rounded highlighter pills or thin underlines.
- Do not add shadows to every marketing card; the flat color panels need no elevation.
- Do not equalize pricing-card heights by adding empty feature rows.
- Do not put all body copy in monospace; it belongs to labels and maker text.
- Do not use bright multicolor customer logos in the navy proof strip.
- Do not replace the irregular drawn diagrams with glossy stock 3D objects.

## Motion and responsive

### Motion

**Observed:**

- Declared: main buttons transition background-color and transform over 0.2s ease; active scale is 0.99.
- Declared: marker text wipe runs for .75s with cubic-bezier(.35,0,.5,1) and forwards fill.
- Declared: opening background expands over 5s ease-in-out, infinitely alternating in reverse.
- Declared: horizontal scrolling animation uses 240s linear infinite; the audience section has a .4s fade with .2s delay.

**Transfer:**

- Use marker reveals to reinforce a selected phrase, leaving the final resting composition readable.
- Keep the proof strip's drift slow and subordinate to the page; preserve legibility of each mark.
- Let the opening atmosphere breathe without moving the foreground promise or action.

**Unknown:**

- Exact scroll triggers, reduced-motion behavior and the full timing of interface changes are not established.

### Responsive

**Observed:**

- Desktop typography and composition use a 1440px-wide viewport.
- Declared heading rules reduce 56px chapter headings to 48px for a mobile variant, and 86px audience headings to 56px/1.1 with -0.01em tracking.
- Declared overview grid changes from one column to two to four; footer grid changes from two to three to four.
- Declared opening action links become full-width at 404px and below. Audience opening has a single-column navigation-width variant; trial banner changes from a column to a row.

**Transfer:**

- On narrow layouts, preserve the order promise → actions → product scene, letting oversized media bleed horizontally only within a controlled wrapper.
- Keep the headline marker attached to its phrase when lines wrap; shorten the highlighted phrase before shrinking the whole headline.
- Stack colored-panel content and reduce padding while keeping the large-radius field recognizable.

**Unknown:**

- Exact rendered mobile spacing, navigation behavior and comparison-table reflow are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
