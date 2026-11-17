# Titan — lived-in institutional theatre

## Overview

An institutional identity made personable through cinematic workplace scenes, delicate line art and unhurried editorial typography. Warm ivory and near-black dominate, with natural greens and brick tones carried by photography rather than interface decoration. Regular grotesk text and compact pill actions keep even expansive compositions approachable; white editorial variants introduce engraved illustrations and small monospace labels. It suits high-trust services and complex products that need both human presence and substantive explanation.

### Essentials

- A monumental identity sits above an unusually modest promise: a 596×135px wordmark graphic anchors the upper left of an 810px photographic opening, while the actual headline is 24px/1.25, weight 400.
- The page alternates paper with immersive theatre: #fdfefa is the default canvas, #12100e carries dark chapters, and chromatic intensity belongs primarily to photographs and muted atmospheric media, not colored marketing cards.
- Actions feel like small smooth objects: 52px-high pills use 16px/1.25 regular sans text and 16px 24px padding; light actions sit over dark scenes and dark actions sit on paper.
- People and abstract machinery share the stage: candid window-lit photography is paired with fine wire-like curves inside 16px-rounded frames. Include both a human scene and a restrained line sculpture; a still photograph and SVG curves are the minimum equivalent.
- Information gets the scale usually reserved for slogans: 48px/1.375 regular headings and numerals sit on a 1192px content field, with 32px gaps between four unboxed proof columns.
- A framed atmospheric call is a signature device: an 800×456px dark translucent panel, 16px corners and 128px backdrop blur presents a centered 48px heading and one light pill. Preserve this concentrated visual pause wherever the narrative needs its strongest invitation.

## Colors

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Charcoal action | `#1d1b19` | `--color-button` | action | Dark pill fill on paper. |
| Warm ink | `#12100e` | `--color-ink` | text, background | Default text and dark theatrical chapters. |
| Warm supporting ink | `#595755` | `--color-support` | text, border | Featured-panel support and footer divider. |
| Muted gray | `#878784` | `--color-muted` | text | Supporting labels, captions and secondary editorial text. |
| Paper edge | `#e2e2de` | `--color-edge` | border, text | Featured-panel edge and softened reverse support copy. |
| Soft white action text | `#f6f7f3` | `--color-button-text` | text | Text inside dark default pills. |
| Ivory paper | `#fdfefa` | `--color-canvas` | background, surface, text, action | Default canvas, light panels and reverse text; also used at 20% alpha for glass over media. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| white editorial, company, recruiting and strategy pages | Distant amber | `#ff9900` | `--color-orange` | accent, action, link | Declared hover fill and a very faint radial glow entering the footer from below the left edge; not a general section fill. |
| white editorial, company, recruiting and strategy pages | Editorial black | `#111111` | `--color-editorial-ink` | text, background, action | Text, solid actions and dark footer. |
| white editorial, company, recruiting and strategy pages | Warm gray emphasis | `#615e5b` | `--color-editorial-muted` | text | Secondary clauses in editorial headings. |
| white editorial, company, recruiting and strategy pages | Stone edge | `#d8d3cc` | `--color-stone-edge` | border | Outline pills and index badges; 10% alpha outlines the dark footer. |
| strategy fact sheets | Facts divider | `#dfddda` | `--color-fact-rule` | border | Rules inside the stone facts panel. |
| white editorial, company, recruiting and strategy pages | Editorial hairline | `#e9eaeb` | `--color-rule` | border | Fine structural rules and outlined square cards. |
| white editorial, company and strategy pages | Warm stone | `#f3efeb` | `--color-stone` | surface | Manifesto and key-facts panels. |
| white editorial, company, recruiting and strategy pages | Editorial white | `#ffffff` | `--color-white` | background, text | White editorial canvas and reversed text; navigation uses this hue at 68% alpha. |

## Typography

- **neueMontreal** — Default marketing headlines, paragraphs and actions. Regular neo-grotesk, open and understated rather than aggressively tightened. If unavailable, use **Inter**. Use weight 400 and normal tracking; retain the generous leading. Font stack: "neueMontreal", "Inter", Arial, sans-serif.
- **Geist** (only for white editorial, company, recruiting and strategy pages) — Editorial variant headings, paragraphs and navigation. Compact contemporary grotesk with medium headings and tight tracking. Font stack: "Geist", -apple-system, system-ui, "Segoe UI", sans-serif.
- **Geist Mono** (only for white editorial, company, recruiting and strategy pages) — Uppercase editorial actions, role captions and indexes. Small technical monospace, sharply contrasting with the broad whitespace. Font stack: "Geist Mono", "SF Mono", Monaco, "Courier New", monospace.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| section-lead | neueMontreal | 400 | 48px | 1.375 | normal | Main editorial statements, proof numerals, centered section introductions and closing invitation. |
| stage-heading | neueMontreal | 400 | 48px | 1.25 | normal | Short centered statement on the dark media stage and the stacked featured-product title. |
| opening-promise | neueMontreal | 400 | 24px | 1.25 | normal | Small two-line promise over the cinematic opening; support uses the same recipe in softer reverse ink. |
| body-lead | neueMontreal | 400 | 20px | 1.375 | normal | Featured descriptions and footer positioning line. |
| action-label | neueMontreal | 400 | 16px | 1.25 | normal | Default pill actions, proof labels and footer navigation. |
| body | neueMontreal | 400 | 16px | 1.5 | normal | Short editorial support paragraphs. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| white editorial recruiting and strategy pages | editorial-display | Geist | 500 | 60px | 1.1 | -0.03em, features "ss02", "ss03" | Text-led recruiting and strategy openings. |
| white editorial, company, recruiting and strategy pages | editorial-heading | Geist | 500 | 40px | 1.1 | -0.03em, features "ss02", "ss03" | Section leads and the company introduction. |
| white editorial, company, recruiting and strategy pages | editorial-card-heading | Geist | 500 | 32px | 1.1 | -0.03em, features "ss02", "ss03" | Headlines in square split cards and person names. |
| white editorial recruiting and strategy pages | editorial-row | Geist | 400 | 20px | 1.3 | normal | Question, process and opportunity row labels. |
| white editorial, company, recruiting and strategy pages | editorial-body-lead | Geist | 400 | 18px | 1.3 | normal | Opening support and principle descriptions. |
| white editorial, company, recruiting and strategy pages | editorial-body | Geist | 400 | 16px | 1.3 | normal | Square-card paragraphs and fact values. |
| white editorial, company, recruiting and strategy pages | editorial-navigation | Geist | 500 | 14px | 1 | 0.02em | Compact floating-header links. |
| white editorial, company, recruiting and strategy pages | editorial-small | Geist | 400 | 14px | 1 | 0.02em | Quote strips and dark-footer links. |
| white editorial, company, recruiting and strategy pages | mono-action | Geist Mono | 500 | 13px | 1 | normal, uppercase | Editorial pill actions. |
| strategy fact sheets | fact-index | Geist Mono | 400 | 11px | 1 | 0.03em | Numbered badges inside factual tables. |

**Notes:**

- Keep the default sans at weight 400 with normal tracking, even for 48px headings. Its spacious leading is part of the conversational tone.
- The editorial variant is a separate system: medium-weight headings consistently tighten to -0.03em and use 1.1 leading; secondary clauses change color rather than weight.
- The oversized serif identity in the opening is artwork, not the headline font. Preserve a comparable identity-scale graphic without turning body copy into a serif system.

## Layout

**Density:** Airy, with compact controls and generous pauses around a few large visual objects.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label spacing in actions. |
| 16px | Small component gaps. |
| 24px | Action-pair gaps, standard horizontal pill padding and narrow-screen side padding. |
| 32px | Proof-column gaps and centered heading-to-action spacing. |
| 40px | Editorial split-grid gaps and dark-footer panel padding. |
| 48px | Opening support-to-action spacing and bottom inset. |
| 56px | Editorial square-card inner padding. |
| 72px | Main statement-to-proof spacing. |
| 80px | Editorial page gutters and substantial inter-block pauses. |
| 112px | Dark resource-chapter vertical padding. |
| 120px | Closing-panel vertical padding. |
| 124px | Default desktop content gutters. |
| 168px | Default broad statement section vertical padding. |

### Containers and grids

- **marketing field**: max width 1440px · side padding 124px. Desktop content spans 1192px inside the broad page field; media chapters can run full bleed.
- **proof columns**: 4 columns · gap 32px. Equal unboxed proof groups, each approximately 274px wide.
- **editorial field** (only for white editorial, company, recruiting and strategy pages): max width 1440px · side padding 80px. A 1280px-wide white editorial content field.
- **editorial split** (only for white editorial, company, recruiting and strategy pages): 2 columns · gap 40px. Equal 620px square text and image cards; alternate their sides between narrative chapters.
- **editorial reading rail** (only for white editorial recruiting and strategy pages): max width 954px. Inset videos, opportunities, process and question lists occupy about three quarters of the editorial field.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | pills | 9999px (pill) |
|  | media and featured panels | 16px |
| white editorial, company, recruiting and strategy pages | editorial square cards | 32px |
| white editorial, company, recruiting and strategy pages | editorial navigation and buttons | 160px |
| white editorial, company, recruiting and strategy pages | footer enclosure | 20px |
| strategy fact sheets | index badges | 6px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
| white editorial, company, recruiting and strategy pages | glass header edge | `rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset` | An almost invisible edge, not a floating-card drop shadow. |
| company product-transparency sections | handheld product frame | `rgba(0, 0, 0, 0.05) 0px 4px 74px 0px` | Soft halo around the narrow mobile product demonstration. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default page field.

**CSS:** `background: #fdfefa; color: #12100e`

#### Dark stage · level 0

**Use:** Immersive media and resource chapters.

**CSS:** `background: #12100e; color: #fdfefa`

**Observed:** Broad dark chapters interrupt the paper rather than surrounding every component.

#### Cinematic scrim · level 1

**Use:** Preserve legibility over full-bleed human scenes.

**CSS:** `background-image: linear-gradient(60.48deg, rgba(0, 0, 0, 0.6) 6.11%, rgba(0, 0, 0, 0) 95.35%), linear-gradient(245.27deg, rgba(0, 0, 0, 0.4) -0.27%, rgba(0, 0, 0, 0) 25.69%)`

#### Ivory feature panel · level 2

**Use:** Feature content floating over atmospheric media.

**CSS:** `background: #fdfefa; border: 1px solid #e2e2de; border-radius: 16px; overflow: hidden`

#### Smoked invitation · level 2

**Use:** Centered closing invitation over a subdued atmospheric scene.

**CSS:** `background: rgba(18, 16, 14, 0.75); border-radius: 16px; backdrop-filter: blur(128px)`

#### Editorial paper · level 0

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Text-led editorial field.

**CSS:** `background: #ffffff; color: #111111`

#### Stone panel · level 1

**Only for:** white editorial company and strategy pages

**Use:** Manifesto copy and factual summary panels.

**CSS:** `background: #f3efeb; border-radius: 32px`

#### Distant amber footer · level 0

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Long-form editorial ending.

**CSS:** `background-color: #111111; background-image: radial-gradient(168.01% 150.5% at -21.04% 235.84%, #ff9900 0%, rgba(255, 153, 0, 0) 100%); color: #ffffff`

**Observed:** Most of the footer remains nearly black. Warmth only barely enters at the lower left.

## Components

### Identity navigation

**Use:** Default fixed marketing navigation.

**CSS:** `position: fixed; padding: 24px; gap: 24px; z-index: 50`

**Observed:** Opening state places a monumental light wordmark at left and a two-stroke menu at right without a header bar. On paper chapters it becomes a small circular identity mark with login, primary action and menu aligned right.

**Transfer:** Use an original identity graphic at monumental scale, then its compact mark for the reading state.

### Primary button

**Use:** Primary action on paper.

**CSS:** `display: inline-flex; align-items: center; justify-content: center; background: #1d1b19; color: #f6f7f3; border-radius: 9999px; padding: 16px 24px; height: 52px; gap: 8px`

**Text style:** `action-label` — neueMontreal 400 · 16px/1.25

**Observed:** Sentence-case label without a mandatory arrow; its width follows the text.

**States:** Declared: hover background-color #403e3c; focus-visible border-color #d0d0cc with zero-valued shadow layers.

### Reverse button

**Use:** Primary action over dark media or inside a dark invitation.

**CSS:** `display: inline-flex; justify-content: center; align-items: center; background: #fdfefa; color: #12100e; border-radius: 9999px; padding: 16px 24px; height: 52px`

**Text style:** `action-label` — neueMontreal 400 · 16px/1.25

**Observed:** The light solid action is paired with a less prominent translucent action in the opening.

**States:** Declared: hover background-color color-mix(in oklab, #fdfefa 90%, transparent); focus-visible border-color #d0d0cc with zero-valued shadow layers.

### Glass secondary button

**Use:** Secondary access action over photographic media.

**CSS:** `background: rgba(253, 254, 250, 0.2); color: #fdfefa; backdrop-filter: blur(12px); border-radius: 9999px; padding: 16px 24px; height: 52px`

**Text style:** `action-label` — neueMontreal 400 · 16px/1.25

**Observed:** A translucent companion to Reverse button rather than an outlined rectangle.

**States:** Declared: hover background-color color-mix(in oklab, #fdfefa 30%, transparent); focus-visible border-color #d0d0cc with zero-valued shadow layers.

### Proof group

**Use:** Large numbers or institutional credentials under a broad introductory statement.

**CSS:** `display: flex; flex-direction: column; gap: 0px`

**Text style:** `section-lead` — neueMontreal 400 · 48px/1.375

**Observed:** Large regular numeral above a small muted action-label caption; four equal groups share one row without card fills or vertical dividers.

**Transfer:** Use independently verifiable metrics and keep their explanatory labels short.

### Featured panel

**Use:** Focused product announcement within an atmospheric stage.

**CSS:** `background: #fdfefa; border: 1px solid #e2e2de; border-radius: 16px; max-width: 776px; padding: 96px 50px 50px; overflow: hidden`

**Text style:** `stage-heading` — neueMontreal 400 · 48px/1.25

**Observed:** A small pill tag sits near the top right; a muted parent line and dark product name stack left. Body-lead copy and Primary button sit below; thin wire art fills the lower right and clips at the panel edge.

**Transfer:** Reserve half the panel for a single abstract diagram instead of packing in feature bullets.

### Closing invitation

**Use:** Concentrated action at a major narrative pause.

**CSS:** `display: flex; flex-direction: column; align-items: center; gap: 32px; background: rgba(18, 16, 14, 0.75); border-radius: 16px; backdrop-filter: blur(128px); width: 800px; padding: 120px 24px`

**Text style:** `section-lead` — neueMontreal 400 · 48px/1.375

**Observed:** A two-line centered invitation and Reverse button sit inside a dark rectangle, itself staged inside a broader atmospheric frame.

### Editorial glass navigation

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Compact fixed editorial header.

**CSS:** `display: flex; align-items: center; background: rgba(255, 255, 255, 0.68); border-radius: 160px; height: 40px; gap: 40px; padding: 0px 15.5px; backdrop-filter: blur(13.5px); box-shadow: rgba(0, 0, 0, 0.05) 0px 0px 0px 1px inset`

**Text style:** `editorial-navigation` — Geist 500 · 14px/1 · tracking 0.02em

**Observed:** Compact identity at left, grouped page links beside it, access links at far right; sits inside an 88px header. Current page has a pale filled capsule.

**States:** Declared: hover link opacity 0.7; focus-visible outline #111111 solid 2px with 2px offset.

### Editorial mono button

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Compact editorial conversion or reading action.

**CSS:** `display: flex; align-items: center; justify-content: center; background: #111111; color: #ffffff; border-radius: 160px; height: 44px; padding: 0px 24px; gap: 8px`

**Text style:** `mono-action` — Geist Mono 500 · 13px/1 · uppercase

**Observed:** Uppercase monospace label; reading links can end with an 8px arrow. Secondary variant is transparent with a 1px stone-edge border and dark text.

**States:** Declared: hover background-color #ff9900 and color #111111; outlined variant also changes border-color to #ff9900; focus-visible outline #111111 solid 2px with 2px offset.

### Editorial split card

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** One idea explained alongside a same-sized picture.

**CSS:** `display: flex; flex-direction: column; justify-content: space-between; align-items: flex-start; gap: 16px; padding: 56px; border: 1px solid #e9eaeb; border-radius: 32px`

**Text style:** `editorial-card-heading` — Geist 500 · 32px/1.1 · tracking -0.03em

**Observed:** A 620px square pins its heading high and its editorial-body paragraph low; the adjacent square is a full image, sharing the same rounded silhouette. Heading continuations can turn warm gray.

### Editorial disclosure row

**Only for:** white editorial recruiting and strategy pages

**Use:** Questions, process steps and linked opportunities.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 16px; padding: 28px 0px; border-top: 1px solid #e9eaeb`

**Text style:** `editorial-row` — Geist 400 · 20px/1.3

**Observed:** A 954px list has plain text at left and a 32px circular chevron control at the far right. Question and process lists use roughly 89px rows; opportunity lists are slightly tighter.

**Transfer:** Preserve the thin ruled list; expose actual answers or destination links rather than making rows decorative.

### Editorial footer enclosure

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Navigation and brand close within Distant amber footer.

**CSS:** `display: flex; gap: 78px; padding: 40px; border: 1px solid rgba(216, 211, 204, 0.1); border-radius: 20px; margin-bottom: 40px`

**Text style:** `editorial-small` — Geist 400 · 14px/1 · tracking 0.02em

**Observed:** A 1280×492px outlined enclosure contains a return control and identity column, several narrow navigation lists, an advisor action and social marks. Dense subdued legal prose follows outside the enclosure.

## Imagery and graphics

### Cinematic human scene

**Use:** Opening image and human proof throughout the page.

**Observed:** Candid people in conversation, seen through black window mullions in a leafy, brick-and-timber interior. Natural side light, softened highlights, dark foreground depth and restrained green-brown color make the full-bleed scene feel inhabited rather than staged. The opening uses almost the entire first screen.

**Transfer:** Photograph the real context in which the new service is used, with people concentrating or conversing. A carefully lit still is sufficient when moving footage is unavailable; keep the wide environmental framing and negative space for the identity and promise.

### Wire sculpture

**Use:** Abstract counterpart to human photography, especially inside a feature panel or media collage.

**Observed:** Very thin dark elliptical loops form an open cylinder; other small panels show delicate plotted curves and flowing mesh-like lines on pale backing. The object is nearly colorless, light and partly clipped rather than shiny or solid.

**Transfer:** Translate a product mechanism into a simple repeated-curve sculpture. The minimum version is a coherent set of fine SVG paths, not a stock 3D icon.

**Build:** Use an SVG viewBox of 464×547. Stack 10–14 unfilled ellipses with radii around 185px and 60px, moving centers downward by 22px; alternate small rotation angles. Use rgba(18,16,14,0.25) strokes at 1px with a few 0.5px secondary paths. Clip the lower portion against the 16px-rounded ivory feature panel.

### Atmospheric backing

**Use:** Full-stage backing for featured content and the concentrated closing invitation.

**Observed:** Soft gray-green light and broad shadow pools sit behind pale or dark nested rectangular frames. The closing version is darker and more neutral; the feature version is lighter and greener. The atmosphere fills the viewport while the readable content stays concentrated in the middle.

**Transfer:** Match the soft glow; exact stops are not essential. Use blurred local photography if available, or broad translucent neutral shapes with a subdued green cast.

**Build:** Place a cover image of softly lit foliage or a window interior on the Dark stage, blur it by 80px and scale it beyond the edges. Add a full-stage rgba(18,16,14,0.5) veil for the closing variant. Center one oversized rectangular frame behind Featured panel or Closing invitation; keep edge contrast low and avoid a bright point-source glow.

### Product demonstration

**Use:** Substantive interface proof between editorial chapters.

**Observed:** A large pale desktop interface is staged on a subdued light field, with a centered caption underneath. The company variant floats a narrow mobile interface between two headings, using a 28px frame radius and a very soft halo.

**Transfer:** Show one authentic workflow at legible scale, retaining the neutral product-ui treatment. Do not make internal dashboard typography part of the marketing type scale.

### Engraved object illustrations

**Only for:** white editorial, company, recruiting and strategy pages

**Use:** Editorial opening objects, split-card images and an illustrated closing call.

**Observed:** Black-and-white architectural engravings, classical sculpture, an animal statue and a charging bull. Stipple, hatching and imperfect ink edges create old print texture. Hero objects float isolated on white at about 412px square; split-card architecture can be dramatically enlarged and clipped.

**Transfer:** Select a domain-relevant object and render it as a high-contrast monochrome engraving. Keep white around the isolated hero object; use an enlarged detail for a full square image.

**Build:** Draw a recognizable SVG silhouette using black outlines, then fill shadow regions with clipped parallel strokes 2–4px apart and scattered tiny dots. Vary stroke density across lit and shadowed planes. Use no colored fill or gray rectangular backing; prioritize a strong silhouette if intricate engraving is impractical.

### People and editorial portraits

**Only for:** company and recruiting pages

**Use:** Culture chapters and team carousels.

**Observed:** Candid conversations and portraits in warm window light, interspersed with leafy interior details and occasional black-and-white group scenes. Square culture images fill 620px cards; portrait strips use 374×439px images with rounded corners, names above and small uppercase monospace role captions.

**Transfer:** Use documentary portraits and actual working spaces. Keep contextual framing and natural tonal variation rather than uniform corporate cutouts.

### Icons

**Observed:** Default menu is two short rounded strokes inside a 32px SVG, with 2.6px stroke and a 64px action target. Editorial iconography uses 32px circles and fine rounded line drawings around 1.5px; small action arrows are 8px, while social marks are compact solid silhouettes.

**Transfer:** Use sparse, monochrome icons. Keep menu geometry simple, use circular chevrons at the end of editorial lists, and avoid colorful filled feature-icon tiles.

## Section recipes

How recurring sections are built.

### First screen: Cinematic identity opening

**Observed:** An 810px-high, full-width human scene with 16px lower corners occupies nine tenths of the first 900px. Back to front: cover footage, Cinematic scrim, monumental ivory identity artwork at the upper left, a discreet menu at the upper right, then a lower-left promise and support block aligned with the 124px content gutter. The identity graphic is 596×135px; the actual promise uses opening-promise in a compact two-line measure, with softer support taking roughly three lines below. Reverse button and Glass secondary button sit 48px below support with a 24px gap and 48px bottom breathing room. The first 900px includes the entire opening plus a 90px horizontal trust strip; the large editorial statement and metric groups begin below the fold.

**Transfer:** Use an original large identity graphic and a natural environmental photograph or still film frame to establish presence before detail. Keep the promise modest, not billboard-sized. White editorial pages instead open beneath Editorial glass navigation with a left-aligned 60px text title, isolated engraved object on the right and a thin quote strip below; a company introduction uses a 40px statement and larger architecture illustration.

**Avoid:** Do not replace this composition with a centered oversized sans headline, dashboard mockup and bright gradient background. Do not float the promise in a white card over the photograph.

**Text style:** `opening-promise` — neueMontreal 400 · 24px/1.25

### Broad statement and open proof

**Observed:** Paper canvas carries a left-aligned section-lead statement across most of the 1192px field. After 72px, four Proof groups sit in a row with 32px gaps, followed by a subdued qualification and a Primary button. Main section padding is 168px vertically.

**Transfer:** State one clear positioning idea, then substantiate it with a small set of defensible numbers or credentials.

### Centered media theatre

**Observed:** A dark central panel approximately 580px square overlaps a collage of human scenes and delicate abstract graphics. A centered stage-heading and Reverse button occupy the panel, which expands into a larger dark stage through the chapter.

**Transfer:** Use a compact central statement surrounded by context and mechanism imagery, rather than a conventional tiled feature grid.

### Human endorsement

**Observed:** A centered section-lead and Primary button introduce a spacious two-column proof scene: quotation and attribution on the left, a rounded warm portrait on the right. A restrained segmented progress indicator and small arrows sit low in the composition.

**Transfer:** Pair a specific customer outcome with a real human presence; keep attribution subordinate and separate substantiation beneath the scene.

### Featured atmospheric pause

**Observed:** Featured panel sits in an ivory outer frame over Atmospheric backing. The object is significantly smaller than the full 900px stage, so the background reads as an environment rather than a card fill.

**Transfer:** Introduce one special capability through its name, one clear outcome and an abstract mechanism graphic.

### Dark resource gallery

**Observed:** Dark stage presents a horizontal strip of differently proportioned visual media above a lower row: a 48px title left and a 448px support-and-action column right. The chapter has 112px vertical breathing room and 52px between gallery and text.

**Transfer:** Use editorial imagery or product insight previews with varied widths, not a uniform three-card blog grid.

### Concentrated invitation and paper ending

**Observed:** Closing invitation fills the center of a dark atmospheric framed scene. After it, Paper canvas returns for a large footer: a short positioning line and two actions on the left, three narrow navigation columns on the right, then copyright and terms across a fine divider and dense low-emphasis legal copy beneath.

**Transfer:** Let the visual invitation deliver the emotional close, and let the footer handle navigation and necessary detail without another promotional headline.

### Editorial heading pair and ruled explanation

**Observed:** A 40px editorial-heading combines black primary text and warm-gray continuation at identical weight. Fine rules organize the section. Support can sit in a right-hand rail as stacked icon-and-copy rows, rather than directly under the heading.

**Transfer:** Split a single thought into primary and explanatory clauses; keep the color shift semantic and the text readable as one sentence.

### Editorial alternating squares

**Observed:** Editorial split card alternates with full-image squares in a two-column 40px-gap grid. Headline stays high, explanatory paragraph low; photography and engraved architecture share the image role.

**Transfer:** Give each pair one explanatory job. Alternate image position for cadence while retaining the square construction.

### Stone fact sheet

**Observed:** A 1280px Stone panel places a 40px title left and a 536px ruled fact list right. Rows use 18px vertical padding and fact-rule separators; each begins with a 37×22px outlined, 6px-rounded index badge, followed by a label and right-aligned value.

**Transfer:** Use for comparison-ready specifications, costs or constraints, with accurate labels and short values.

**Text style:** `fact-index` — Geist Mono 400 · 11px/1 · tracking 0.03em

### Editorial illustrated close

**Observed:** A 1280×400px outlined rounded enclosure splits a short 40px invitation and Editorial mono button on the left from a 400px engraved object on the right, with a faint central divider. The company variant uses this before the Distant amber footer; recruiting goes from final video to footer, while strategy pages place advisory and disclosure actions before the footer.

**Transfer:** Use the illustrated close for an editorial company narrative, but let recruiting end on opportunities and product detail end on resolved questions and next actions.

## Page flow

**Storyline:** Atmosphere or identity → positioning → substantive proof → capability or culture chapters → questions or opportunities → focused invitation → navigational and legal close.

### Broad marketing landing page

1. **Promise** — Cinematic identity opening and compact trust strip.
2. **Quantified proof** — Broad statement with open proof columns.
3. **Capability demonstration** — Expanding dark media stage and large neutral interface proof.
4. **Human proof** — Quotation paired with a warm portrait.
5. **Special capability** — Featured panel over an atmospheric field.
6. **Education and objection handling** — Dark resource gallery followed by a centered question-section introduction.
7. **Closing call** — Concentrated invitation followed by the paper navigation and legal ending.

**Transfer:** Use the atmospheric landing system as the default, varying the number and order of proof chapters to suit the new offering.

### Company and trust narrative

1. **Identity** — Two-tone introduction beside oversized engraved architecture.
2. **Mission** — Paired statement and stone manifesto card beside human photography.
3. **Trust demonstration** — Engraved hands banner, paired claims around a narrow mobile interface, then explanatory prose.
4. **Principles** — Engraved sculpture at left and numbered ruled statements at right.
5. **Human proof** — Horizontal portrait carousel with names and monospace role captions.
6. **Recruiting bridge** — Square copy card beside a group photograph.
7. **Closing call** — Illustrated outlined invitation, then dark enclosed navigation and subdued legal text.

**Transfer:** Use the white editorial variant to connect beliefs, product transparency and people rather than repeating the cinematic landing opening.

### Recruiting narrative and opportunity index

1. **Identity** — Large two-tone text title opposite an engraved statue, ending in a quote strip.
2. **Culture proof** — Wide conversation video introduced by a 40px heading.
3. **Principles** — Compact mono label, broad statement and right-hand icon-and-copy rows.
4. **Culture chapters** — Alternating square candid photographs and text cards.
5. **Opportunities** — Department groups with ruled linked role rows and circular chevrons.
6. **Decision support** — A final wide explanatory video, followed directly by the dark footer enclosure and legal close.

**Transfer:** Let real environments and explicit expectations substantiate the invitation; retain a usable opportunity index as the central action.

### Detailed product or strategy explanation

1. **Promise** — Text-led title, advisor action and isolated engraved architecture above a quote strip.
2. **Benefits** — Broad heading with a right-hand list of short icon-supported outcomes.
3. **Capability chapters** — Alternating square text, engraving and people imagery.
4. **Demonstration** — Inset wide video.
5. **Factual proof** — Stone fact sheet with numbered rows.
6. **Process** — Short ruled steps and a secondary action.
7. **Objection handling** — Question list, explanatory disclosures and final advisory and risk actions.
8. **Ending** — Dark footer enclosure with navigation, identity and social links followed by legal text.

**Transfer:** Use the white editorial variant when detail and constraints matter more than immersive brand introduction; never let imagery replace the specifications or answers.

## Writing

Assured, service-minded and plainspoken. Institutional credibility comes through specific explanations and qualifications, while human invitations soften the formality.

**Do not copy:** Do not reuse Titan's name, identity artwork, product names, employee or client identities, company logos, financial claims, statistics, quotations or regulatory assertions. Source examples illustrate structure only; all new claims and proof must belong to the new product.

- **Addressing the reader:** Speak as we or our team and address the reader as you or your. Product explanations can use the product name as subject, then quickly return to practical reader outcomes.
- **Rhythm:** Short declarative headlines, compact action labels and explanatory paragraphs. Longer mechanism descriptions are broken by very short sentences; the voice prefers a period to an exclamation mark.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the service and the audience directly. | 7–10 words | “The wealth manager for tech professionals.” |
| Section statement | State an encompassing outcome in a short complete phrase. | 4–8 words | “Your wealth, fully managed.” |
| Mechanism explanation | Explain what happens, then state practical constraints in short sentences. | One short paragraph | “Low risk. Fully liquid.”<br>“It scans rates daily.” |
| Human invitation | Warm, direct service language rather than a pressured sales imperative. | One or two sentences | “Our team is based in NYC, and available from anywhere. We'd be thrilled to help you navigate your wealth.” |
| Action | Simple verb plus destination or conversation. | 2–5 words | “Get started”<br>“Speak with an advisor”<br>“READ MANIFESTO” |
| Question | Ask the reader's practical question without cleverness. | 5–12 words | “What does Smart Treasury cost?” |

**Words and phrasing to use:** fully managed; our team; designed to; how it works; help you; clear practical outcomes; specific mechanisms

**Avoid:** disruptive magic; guaranteed results; 10x everything; crush it; world-changing superlatives; exclamation-heavy calls to action

**Rules:**

- Distinguish goals from guarantees and keep necessary qualifications next to substantive claims.
- Lead each chapter with one outcome; use support copy to explain the mechanism rather than restating the heading.
- Use sentence case in the default system. Uppercase belongs to the editorial mono action treatment, not to every headline.
- Make proof captions factual and restrained; keep emotional language for human invitations.

## Do's and Don'ts

### Do

- Keep default 48px headings at weight 400 and normal tracking.
- Align paper content to 124px desktop gutters and reserve full bleed for immersive scenes.
- Use 52px pills with 16px 24px padding in the default landing system.
- Give abstract line art hairline strokes and ample pale backing.
- Preserve the 800px centered dark invitation as a clear visual pause.
- Use four open proof columns with 32px gaps when comparable metrics are available.
- Keep editorial square cards at 32px radius with 56px inner padding.
- Restrict the amber accent to editorial hover states and a distant footer glow.

### Don't

- Do not apply the editorial 60px medium heading recipe to the modest 24px cinematic promise.
- Do not turn default navigation into a permanent frosted capsule; that treatment belongs to the editorial variant.
- Do not replace the default ivory canvas with pure white throughout.
- Do not put every metric in its own shaded or bordered card.
- Do not use glossy metallic 3D objects where delicate wire paths should carry the mechanism metaphor.
- Do not substitute vivid gradient-filled text for the black-and-warm-gray editorial heading pair.
- Do not add heavy drop shadows to ordinary cards; the editorial header has only a 1px inset edge.
- Do not end every page with the illustrated editorial call; recruiting and detailed product narratives have their own action-led endings.

## Motion and responsive

### Motion

**Observed:**

- Default action color, background, border, shadow and opacity transitions are declared at 0.3s with cubic-bezier(0, 0, .2, 1).
- The default landing system uses sticky 900px media stages inside longer scroll chapters, with clipping and translated panels.
- The identity treatment declares height and margin-top transitions at 0.3s ease.
- Editorial navigation declares 0.3s background transitions with cubic-bezier(0.83, 0, 0.17, 1) and opacity at 0.3s ease.

**Transfer:**

- Use the media-stage reveal to concentrate attention on one object or invitation, not to animate every paragraph independently.
- Keep the compact reading-state identity stable while changing chapter surfaces beneath it.

**Unknown:**

- Exact scroll interpolation, video loop lengths, autoplay behavior and all animation choreography are not specified.

### Responsive

**Observed:**

- Default landing styles declare width breakpoints at 640px, 768px, 1024px, 1280px, 1536px and 1600px.
- Editorial variants declare breakpoints spanning 375px to 1300px, including 767px/768px and 991px/992px.
- Default class rules distinguish narrow 24px gutters from desktop 124px gutters and single-column proof from four-column proof.

**Transfer:**

- On narrow layouts, retain the photographic opening, compact promise and original identity while reducing the identity graphic to fit its available width.
- Stack proof groups and editorial square pairs, maintaining text-image pairing and the headline-high/body-low relationship where space permits.
- Allow the dark invitation to become full width within 24px gutters, rather than preserving an overflowing 800px fixed width.

**Unknown:**

- Mobile compositions, exact small-screen type sizes and mobile menu expansion were not visually established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
