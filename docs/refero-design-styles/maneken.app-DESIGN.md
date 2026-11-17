# Maneken — blue stages, tangible outcomes

## Overview

A spacious, image-led style for creative tools and products whose results deserve to be seen. Black grotesk headlines sit on white and pale gray, interrupted by saturated blue demonstrations and charcoal feature stages. Real-world photography, compact interface controls and a playful sculptural object give the otherwise restrained layout a tactile, studio-made feel.

### Essentials

- Headlines feel like plainspoken posters rather than advertising flourishes: TWKEverett at 110px/1, weight 500, normal tracking for the main promise; 77px/1 for section titles.
- The opening sells ease before complexity: a centered two-line headline about 590px wide, a 28px/1.2 gray support line, one blue action, then a 1200px-wide media stage entering the first 900px.
- Actions are small, solid blue rounded rectangles, not pills: 55px high, 10px radius, 40px horizontal padding, 15px medium Inter and a small right arrow; navigation uses a 48px-high version.
- Color has a theatrical job: white and #f4f4f4 frame most content, #0050b7 fills a substantial demonstration chapter as well as actions, and #10151c backs a second capability chapter and the sculptural sign-off. Photography carries the remaining color.
- Outcomes look tangible: large rounded photographs of designs in streets, shops, hands and interiors are staged in asymmetrical clusters, four-column masonry and edge-clipped creator strips. For an intangible product, show authentic outputs in plausible working environments instead of substituting generic icon cards.
- A blue object punctuates the experience: a glossy extruded emblem stands against charcoal beside a short relationship-building message. Reinterpret it as a new product's own abstract object; the minimum version is a shaded extruded SVG, not a stock illustration.
- The interface stays above the spectacle: a fixed white navigation tray is 60px high with a 14px radius and 30px outer inset, remaining legible over blue, photography and charcoal. Major chapter panels have 15px corners and a 20px white gutter.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Action and demonstration blue | `#0050b7` | `--color-blue` | action, background, accent | Conversion buttons and the full-color workflow chapter. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Black ink | `#000000` | `--color-ink` | text | Headlines, feature text and footer labels on light surfaces. |
| Charcoal stage | `#10151c` | `--color-night` | background, text | Dark capability and sculpture stages; attribution text on white. |
| Secondary gray | `#666666` | `--color-secondary` | text | Visible result of black at 60% opacity on white, as in expanded answers and subdued descriptive text. |
| Resting link gray | `#808080` | `--color-link-muted` | link, text | Visible result of black at 50% opacity over white for navigation and footer links; becomes black on interaction. |
| Intro gray | `#86868b` | `--color-muted` | text | Opening descriptive line. |
| Footer rule | `#eaeaea` | `--color-footer-rule` | border | Single faint horizontal separator above legal links. |
| Pale gray panel | `#f4f4f4` | `--color-panel` | surface, background | Large rounded gallery, demonstration, proof and FAQ chapters. |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Page canvas, navigation and FAQ cards; reversed headings and button text. Pricing glass is rgba(255,255,255,0.9), visually white on the canvas. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| pricing pages | Gradient light blue | `#0872db` | `--color-electric` | accent, surface | Small radial highlight in the premium plan header, selected billing segment and premium price. |
| pricing pages | Gradient royal blue | `#0c27b9` | `--color-royal` | accent, surface | Deep blue base of premium header and price gradients. |
| pricing pages | Control charcoal | `#3e3e3e` | `--color-control-text` | text | Secondary action text and detailed terms links. |
| pricing pages | Panel edge | `#ebebeb` | `--color-edge` | border, surface | Pricing panel borders, header separators, segmented controls and neutral badges. |
| interactive product demonstrations | Upload edge | `#e6e6e6` | `--color-drop-edge` | border | Dashed upload tile edge. |

## Typography

- **TWKEverett** — Headlines, large descriptive lines, FAQ questions and answers, pricing titles and figures. Direct contemporary grotesk with broad, open forms, a high x-height and an approachable rather than mechanical rhythm. If unavailable, use **DM Sans**. Use weights 400–600 and retain normal tracking; tune line breaks to preserve the broad silhouettes. Font stack: "TWKEverett", "DM Sans", Inter, sans-serif.
- **Inter** — Navigation, actions, interface-like descriptions, attribution labels, footer and comparison lists. Neutral, highly legible sans with compact medium-weight controls. Font stack: "Inter", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | TWKEverett | 500 | 110px | 1 | normal | Two-line opening promise and the largest chapter statements. |
| heading | TWKEverett | 500 | 77px | 1 | normal | Centered chapter titles and the left-aligned sculptural sign-off; also the pricing opening. |
| workflow-heading | TWKEverett | 500 | 60px | 1.2 | normal | Large left-aligned step titles inside the blue demonstration chapter. |
| feature-heading | TWKEverett | 500 | 55px | 1.2 | normal | Capability titles beside square media in the charcoal chapter. |
| lead | TWKEverett | 400 | 28px | 1.2 | normal | Opening support, centered chapter descriptions and capability explanations. |
| demonstration-copy | Inter | 500 | 28px | 1.2 | normal | Blue workflow descriptions and compact centered outcome statements. |
| signoff-copy | Inter | 400 | 28px | 1.2 | normal | Short paragraph beside the blue sculpture. |
| question | TWKEverett | 500 | 22px | 1.2 | normal | FAQ summary labels. |
| footer-link | Inter | 500 | 18px | 1 | normal | Footer navigation lists. |
| footer-heading | Inter | 800 | 18px | 1 | normal | Footer column labels. |
| legal-link | Inter | 500 | 18px | 1.4 | normal | Footer credit and legal link row. |
| answer | TWKEverett | 400 | 16px | 1.45 | normal | Expanded FAQ paragraphs, with understated inline underlined links. |
| action | Inter | 500 | 15px | 1 | normal | Primary conversion buttons and account actions. |
| nav | Inter | 500 | 15px | 1.25 | normal | Centered navigation links. |
| attribution | Inter | 500 | 14px | 1 | normal | Creator labels over imagery. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | plan-title-price | TWKEverett | 600 | 48px | 1 | normal | Plan names and current prices. |
| pricing pages | comparison-heading | TWKEverett | 600 | 30px | 1 | normal | License comparison titles. |
| pricing pages | comparison-copy | Inter | 400 | 16px | 1.2 | normal | Plan benefits and permission lists. |
| pricing pages | secondary-action | Inter | 500 | 14px | 1.2 | normal | Outlined free-plan action. |
| pricing pages | badge | Inter | 500 | 12px | 1 | normal, uppercase | Small license category badges. |

**Notes:**

- Normal tracking is part of the character even at 110px; do not apply the fashionable tightly kerned display treatment.
- Headlines are medium, not heavy. Reserve 600 for comparison titles and pricing figures, and 800 for small footer column labels.
- The 28px descriptive layer is unusually prominent relative to the 15px controls. Preserve that contrast rather than inflating the buttons.
- Muted text on dark and blue stages uses white at 60% opacity; foreground headings stay fully white.

## Layout

**Density:** Airy at chapter scale, with compact controls and lists inside the large media-led stages.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Icon-to-label gaps and comparison list rows. |
| 12px | Footer link gaps and compact title groups. |
| 16px | FAQ row gaps and demonstration preset gaps. |
| 20px | Outer chapter gutter and feature title-to-description gap. |
| 24px | Pricing card gaps and comparison group spacing. |
| 30px | Main title, descriptive line and action spacing. |
| 32px | FAQ horizontal padding and plan body vertical padding. |
| 36px | License card padding. |
| 45px | Workflow heading-to-description spacing. |
| 55px | Gap between media and text in capability rows. |
| 80px | Desktop section side padding and large heading-to-media separation. |
| 140px | Default major chapter top and bottom padding. |
| 150px | Opening top padding and separation between dark capability rows. |

### Containers and grids

- **chapter frame**: max width 1600px · side padding 20px. Broad centered page structure with 20px white gutters around rounded chapters; chapters are 1400px wide at a 1440px viewport.
- **media stage**: max width 1200px · side padding 80px. Large centered hero video and outcome demonstrations. The opening video is 1200×675px.
- **copy block**: max width 840px. Centered chapter descriptions; narrower feature paragraphs use 336px and FAQ answers use 480px.
- **capability row**: max width 1200px · 2 columns · gap 55px · side padding 50px. Vertically centered text and 523×523px media. Alternate media side across rows.
- **workflow grid**: max width 1100px · 2 columns · gap 80px. 510px text column and approximately 510px portrait-media column within the blue chapter.
- **gallery grid**: 4 columns · gap 10px. Four 303px-wide columns of varying-height imagery inside the pale chapter.
- **questions**: max width 900px · gap 16px. Single centered stack of white details rows.
- **footer grid**: max width 1600px · 4 columns · gap 80px · side padding 80px. A double-width brand column beside three 200px link columns; legal row follows the same alignment.
- **plans** (only for pricing pages): 3 columns · gap 24px · side padding 80px. Top-aligned 350px cards with intrinsic height rather than artificially equal-height footers.
- **license comparison** (only for pricing pages): max width 800px · 2 columns · gap 24px. Two 388px cards below a centered heading and explanation.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | chapter panels | 15px |
|  | navigation tray | 14px |
|  | buttons and gallery media | 10px |
|  | FAQ rows | 16px |
|  | creator badges | 5px |
| pricing pages | comparison panels | 12px |
| pricing pages | billing control | 6px |
| interactive product demonstrations | upload tile | 12px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | floating photograph | `0px 90px 40px 0px rgba(0,0,0,0.01), 0px 50px 30px 0px rgba(0,0,0,0.05), 0px 20px 20px 0px rgba(0,0,0,0.09), 0px 6px 10px 0px rgba(0,0,0,0.1)` | Loose photographs arranged around an outcome statement. |
| pricing pages | comparison panel | `0px 4px 12px 0px rgba(10,10,10,0.024), 0px 8px 28px 0px rgba(10,10,10,0.04), 0px 12px 40px 0px rgba(10,10,10,0.05)` | Soft, multi-layer lift on white pricing and license panels. |

### Surfaces

#### Canvas · level 0

**Use:** Continuous white canvas and gutters between chapters.

**CSS:** `background: #ffffff; color: #000000`

#### Pale chapter · level 0

**Use:** Gallery, interactive example, proof and FAQ chapters.

**CSS:** `background: #f4f4f4; border-radius: 15px; padding: 140px 80px`

**Observed:** Broad inset slabs with white gaps around them; imagery and type carry the hierarchy, not card outlines.

**Transfer:** Group a substantial narrative unit into one pale slab instead of making each sentence a separate card.

#### Blue workflow stage · level 0

**Use:** Immersive step-by-step demonstration chapter.

**CSS:** `background: #0050b7; color: #ffffff; border-radius: 15px; padding: 100px 80px`

**Observed:** A full blue chapter behind white step headings and a large portrait result. Descriptions are white at 60% opacity.

**Transfer:** Keep the blue stage for the clearest demonstration of the product in use.

#### Charcoal chapter · level 0

**Use:** Deep capability exposition and sculptural sign-off.

**CSS:** `background: #10151c; color: #ffffff; border-radius: 15px; padding: 140px 80px`

**Observed:** A single uninterrupted dark stage can hold a centered chapter statement and several alternating feature rows. The sign-off is a separate, shorter dark panel.

**Transfer:** Use charcoal as a change of pace, with real media occupying roughly half each row.

#### Comparison glass · level 1

**Only for:** pricing pages

**Use:** Plan and license panels.

**CSS:** `background: rgba(255,255,255,0.9); border: 1px solid #ebebeb; border-radius: 12px; backdrop-filter: blur(80px); box-shadow: 0px 4px 12px 0px rgba(10,10,10,0.024), 0px 8px 28px 0px rgba(10,10,10,0.04), 0px 12px 40px 0px rgba(10,10,10,0.05)`

**Observed:** Reads as softly elevated white rather than visibly transparent glass.

**Transfer:** Reserve this compact raised construction for choices and comparisons.

#### Premium blue highlight · level 1

**Only for:** pricing pages

**Use:** Recommended plan header; smaller versions highlight selected billing options and the premium price.

**CSS:** `background: radial-gradient(120px 120px at 70% 90%, #0872db 0px, #0c27b9); color: #ffffff; border-bottom: 1px solid #ebebeb`

**Observed:** Bright blue bloom low on a royal-blue field, confined to the card header; the body stays white.

**Transfer:** Highlight one premium option, not the entire comparison area.

## Components

### Navigation tray

**Use:** Persistent orientation and account entry.

**CSS:** `display: grid; grid-template-columns: 1fr auto 1fr; align-items: center; gap: 24px; background: #ffffff; border-radius: 14px; height: 60px; padding: 6px 6px 6px 24px; max-width: 1600px`

**Text style:** `nav` — Inter 500 · 15px/1.25

**Observed:** Fixed wrapper with 30px top and side inset. Brand at left, centered links, login and compact blue signup at right. The compact button is 48px high with 20px horizontal padding; the tray stays white across every background.

**Transfer:** Keep the three-part balance even when the new product has fewer navigation items.

### Primary button

**Use:** Main conversion action and paid-plan subscription.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; height: 55px; padding: 0px 40px; background: #0050b7; color: #ffffff; border-radius: 10px; transition: transform .4s cubic-bezier(.175,.885,.32,1.275)`

**Text style:** `action` — Inter 500 · 15px/1

**Observed:** Content-sized rectangle with a 15px right arrow after the label in marketing sections; paid-plan actions span the available panel width and omit the arrow.

**States:** Declared: hover transform scale(1.05); focus-visible transform scale(1.05); active transform scale(0.95).

### Navigation link

**Use:** Low-noise links in the central tray.

**CSS:** `color: #000000; opacity: 0.5; transition: opacity .2s cubic-bezier(.445,.05,.55,.95)`

**Text style:** `nav` — Inter 500 · 15px/1.25

**Observed:** Unboxed links arranged horizontally with 40px gaps.

**States:** Declared: hover opacity 1; focus-visible opacity 1.

### FAQ row

**Use:** Objection handling without a dense text wall.

**CSS:** `background: #ffffff; border-radius: 16px; padding: 0px 32px; outline: 4px solid #ffffff; outline-offset: -4px; max-width: 900px`

**Text style:** `question` — TWKEverett 500 · 22px/1.2

**Observed:** Native details and summary structure; closed summary is 80px high with text at left and a 24px chevron at right. Rows are separated by 16px. Expanded content uses the answer recipe, black at 60% opacity, a 480px text measure and 28px bottom padding.

### Creator badge

**Use:** Compact human attribution anchored to an output image.

**CSS:** `display: flex; align-items: center; gap: 6px; background: #ffffff; border-radius: 5px; height: 36px; padding: 3px 10px 3px 3px; position: absolute`

**Text style:** `attribution` — Inter 500 · 14px/1

**Observed:** Small 30×30px avatar precedes the name; label sits near the lower-left corner of the photo. Text is charcoal at 60% opacity.

**Transfer:** Credit a real maker, customer or source; keep the label visually subordinate to the work.

### Footer column link

**Use:** Navigation within the spacious footer.

**CSS:** `display: flex; align-items: center; gap: 4px; color: #000000; opacity: 0.5; transition: opacity .2s cubic-bezier(.445,.05,.55,.95)`

**Text style:** `footer-link` — Inter 500 · 18px/1

**Observed:** Simple vertical lists with 12px gaps. Column headings use the footer-heading recipe and an additional 18px bottom margin.

**States:** Declared: hover opacity 1; focus-visible opacity 1.

### Legal text link

**Use:** Understated footer policies and creator credit.

**CSS:** `color: #000000; opacity: 0.5; padding-bottom: 1px; background-image: linear-gradient(#000000, #000000); background-size: 0px 1px; background-position: 0px 100%; background-repeat: no-repeat; transition: opacity .2s cubic-bezier(.445,.05,.55,.95), background-size .4s cubic-bezier(.215,.61,.355,1)`

**Text style:** `legal-link` — Inter 500 · 18px/1.4

**Observed:** Lives below a 1px pale rule in the footer's shared column grid; credit prefix remains black.

**States:** Declared: hover opacity 1; focus-visible opacity 1.

### Plan card

**Only for:** pricing pages

**Use:** Compare offers without overwhelming the reader.

**CSS:** `display: grid; max-width: 350px; background: rgba(255,255,255,0.9); border: 1px solid #ebebeb; border-radius: 12px; overflow: clip; backdrop-filter: blur(80px); box-shadow: 0px 4px 12px 0px rgba(10,10,10,0.024), 0px 8px 28px 0px rgba(10,10,10,0.04), 0px 12px 40px 0px rgba(10,10,10,0.05)`

**Text style:** `plan-title-price` — TWKEverett 600 · 48px/1

**Observed:** Header holds a small billing switch at upper right, then plan name and savings on a shared baseline. Header is 150px high with a 1px bottom rule. Body has 32px vertical and 24px horizontal padding: check list, centered price, short billing note, action. Free action is outlined, 44px high with 12px corners and secondary-action text; paid actions use Primary button. Premium header uses Premium blue highlight. The 150×30px billing switch has a 6px outer radius, 2px inset, uppercase 10px labels and a blue selected segment.

**Transfer:** Let benefit count determine card height, with all plan tops aligned. Use the blue header for one differentiated tier.

### License card

**Only for:** pricing pages

**Use:** Explain permission or entitlement differences in parallel.

**CSS:** `display: flex; flex-direction: column; gap: 24px; padding: 36px; background: rgba(255,255,255,0.9); border: 1px solid #ebebeb; border-radius: 12px; backdrop-filter: blur(80px); box-shadow: 0px 4px 12px 0px rgba(10,10,10,0.024), 0px 8px 28px 0px rgba(10,10,10,0.04), 0px 12px 40px 0px rgba(10,10,10,0.05)`

**Text style:** `comparison-heading` — TWKEverett 600 · 30px/1

**Observed:** Small category badges precede a title, with 12px between them. Neutral badge is gray; paid badges are blue. Below, comparison-copy rows pair 16px check or cross marks with 8px gaps. Both columns repeat the same criteria for easy scanning.

### Upload tile

**Only for:** interactive product demonstrations

**Use:** A compact add-your-own entry among visual presets.

**CSS:** `display: flex; align-items: center; justify-content: center; width: 100px; height: 100px; background: #ffffff; border: 2px dashed #e6e6e6; border-radius: 12px`

**Observed:** A single upload icon is centered inside the dashed tile; it follows image preset thumbnails underneath a large demonstration canvas.

**Transfer:** Use a real input-backed upload action rather than an ornamental empty square.

## Imagery and graphics

### Tangible output photography

**Use:** Primary hero media, outcome clusters, catalog-like galleries and capability demonstrations.

**Observed:** Designs are applied to billboards, shop signs, bags, apparel, cups, laptops and phones in natural environments. Street brick, stone, greenery, warm furniture and human hands retain texture and daylight. Bright graphics occupy a portion of each scene rather than coloring the entire photograph. Large images have modest rounded corners; free-floating cluster images have layered soft shadows.

**Transfer:** Photograph or composite authentic outputs of the new product into believable contexts. Preserve natural light and environmental detail. If the product is purely digital, show an output on a real screen or printed artifact rather than a full-page dashboard.

### Black media theater

**Use:** Opening product-reel stage.

**Observed:** A wide dark rounded video frame presents overlapping photographic cards, later expanding into a tight matrix of varied output scenes. The stage is 1200×675px and dominates the opening's lower half and the following scroll.

**Transfer:** Create a restrained output reel or a static composition of three overlapping examples on dark backing when no video exists. The visible content must be a result, not a stock abstract animation.

**Build:** Use a 16:9 rounded dark frame with overflow hidden. Layer three photo rectangles around its center with 10px corners, offset upward and sideways to reveal edges; use the floating photograph shadow lightly. For a later reel scene, arrange output thumbnails in a tight multi-row grid on the same dark backing. Use the Charcoal chapter color for a reproducible backing.

### Masonry and creator strip

**Use:** Breadth of outcomes and human proof.

**Observed:** One gallery uses four narrow columns with 10px gaps and variable-height photos. The creator strip instead uses 400×500px slots with 10px internal padding around 380×480px images, continuing beyond the viewport edges. Creator badge overlays are pinned near the photo bottoms.

**Transfer:** Keep repeated image treatments coherent, but vary subjects and aspect ratios in masonry. Use the edge-clipped strip for credited work rather than turning it into testimonial quote cards.

### Blue extruded emblem

**Use:** A memorable visual sign-off and tactile brand punctuation.

**Observed:** A cobalt-blue, thick extruded figure with wavy edges and a spherical head floats on the right of a charcoal panel. Smooth plastic-like surfaces have brighter top-left highlights, deeper blue sides and no separate ground plane. It is a substantial object but leaves ample air around the left-hand invitation.

**Transfer:** Make a new proprietary symbol, letter or abstract shape with similar physical depth and blue material. A clean shaded SVG with visible side faces is the minimum acceptable equivalent.

**Build:** Draw a simple original SVG silhouette with one curving edge and one geometric edge. Duplicate its path diagonally down-right by about 30px to form the rear face; join corresponding edges with side polygons. Fill the front with a blue gradient from the light-blue accent toward action blue, side faces with royal blue and charcoal-blue alpha shading. Add a narrow translucent white highlight along the upper-left edge and a soft inset highlight, not an outer neon glow. Center the sculpture within roughly half the panel and leave the other half for text; a sphere or rounded primitive can add the playful physical cue.

### Icons

**Observed:** Sparse functional symbols rather than a feature-icon system: 15px white arrows in marketing actions, 24px black FAQ chevrons, 16px black checks and crosses in comparisons, and 40px white social symbols inside 60px targets. Upload uses a centered 24px icon. Functional marks are uncomplicated filled SVG shapes with thin-looking silhouettes.

**Transfer:** Use consistent simple SVG marks in current text color. Keep comparisons monochrome, and use recognizable social symbols only where they are actual links.

## Section recipes

How recurring sections are built.

### First screen: Centered promise and media theater

**Observed:** White canvas behind a fixed Navigation tray. The headline begins after 150px of section top padding, occupies about 590px across the center, and breaks into two closely stacked lines at 110px/1 with no decorative fill. A gray 28px support line follows after 30px, then one Primary button after another 30px. A broad 1200×675px Black media theater begins about 102px below the action. Within the first 900px, navigation, the full promise, support and action are visible, plus the upper portion of the dark media stage and its central stack of output images. Most of the reel and all subsequent chapters lie below the fold. Layers remain simple: white canvas, centered type, blue action, then dark rounded media with photographs inside it.

**Transfer:** Use a short outcome promise broken into two balanced lines, one factual product-category line and one conversion action. Without a reel, make the static three-output theater described in imagery. Comparison-focused pages use a 77px centered title, a short 28px support block and plan cards directly underneath instead of the media theater.

**Avoid:** Do not replace the opening with a left-copy/right-dashboard split, a tinted gradient backdrop or a hero filled with multiple competing actions.

**Text style:** `display` — TWKEverett 500 · 110px/1

### Asymmetric outcome cluster

**Observed:** Pale chapter with three large floating photographs surrounding a compact centered 28px statement. A taller photograph anchors the left; two smaller photos overlap vertically at right. Broad empty space and soft downward shadows separate the objects from the backing.

**Transfer:** Show one result across different contexts or formats, keeping the compact explanatory statement between rather than above every image.

**Text style:** `demonstration-copy` — Inter 500 · 28px/1.2

### Immersive workflow chapter

**Observed:** Blue workflow stage with a two-column Workflow grid. Left-aligned 60px titles and narrow 336px descriptions sit beside a portrait result around 510px wide. Three workflow steps occupy consecutive tall reading beats; the demonstration retains a small dark translucent control strip near its bottom.

**Transfer:** Break the core task into a few concrete steps and show the result changing alongside the explanation. Preserve the full blue stage even if using static step illustrations rather than an interactive editor.

**Text style:** `workflow-heading` — TWKEverett 500 · 60px/1.2

### Heading pair and hands-on result

**Observed:** A centered display title and 28px supporting line separated by 30px lead into a large 1000×667px example on a Pale chapter. Small square presets and Upload tile sit beneath the media; the controls do not dominate the section.

**Transfer:** Give the visitor one immediately understandable result or transformation with a small set of meaningful inputs.

**Text style:** `display` — TWKEverett 500 · 110px/1

### Breadth gallery

**Observed:** A 77px centered title, 28px description and Primary button sit above a four-column masonry gallery on a Pale chapter. Imagery becomes the majority of the chapter's area, with consistent narrow gaps and no explanatory text attached to every photo.

**Transfer:** Use this for a library, integration range, output variety or real-world applications; retain the dense visual field below the airy heading.

**Text style:** `heading` — TWKEverett 500 · 77px/1

### Dark capability exposition

**Observed:** Charcoal chapter begins with a centered 110px statement, a support line and Primary button. Below, vertically centered capability rows alternate text and square 523px media, separated by 150px. Each row uses a 55px heading, 20px title-to-body spacing and a 55px gap between the two halves.

**Transfer:** Group deeper capabilities in one dark chapter and show a concrete result for each, rather than creating a grid of icon-based feature cards.

**Text style:** `feature-heading` — TWKEverett 500 · 55px/1.2

### Credited outcome strip

**Observed:** Centered 77px title, support line and action on a Pale chapter, followed by an edge-clipped continuous row of large portrait images with Creator badge overlays. The row reaches beyond the content container instead of fitting exactly within it.

**Transfer:** Let authentic examples supply social proof; attribute the work directly on the image.

**Text style:** `heading` — TWKEverett 500 · 77px/1

### FAQ slab

**Observed:** A centered two-line 77px title precedes the Questions stack by 80px. White FAQ rows contrast softly with the pale backing. Questions are short and remain comfortably inset; answers open beneath rather than alongside.

**Transfer:** Choose objections that affect action and keep long answers inside the expandable rows.

**Text style:** `heading` — TWKEverett 500 · 77px/1

### Sculptural relationship sign-off

**Observed:** A separate 835px-high Charcoal chapter uses a two-column 1100px grid with 40px gap. Left: 77px invitation, a narrow 336px supporting paragraph after 30px, then three white social symbols. Right: a large Blue extruded emblem with room around its silhouette. The text is vertically centered against the object rather than pinned to the section top.

**Transfer:** Include the sculptural brand punctuation somewhere in the new experience. This closing version can invite following, updates, community or another ongoing relationship instead of repeating the primary sales message.

**Text style:** `heading` — TWKEverett 500 · 77px/1

### Airy utility footer

**Observed:** White footer after the final chapter, with 140px top padding inside its grid. A compact black wordmark occupies the double-width left column; three link columns sit to its right. Below a generous gap, a 1px Footer rule introduces the credit and policy row with 28px vertical padding. Both long-form and pricing experiences end with this same footer.

**Transfer:** Keep the ending useful and calm after the media-heavy content. Adapt the three groups to product, community and contact destinations without adding another promotional banner.

**Text style:** `footer-link` — Inter 500 · 18px/1

### Comparison opening and entitlement chapter

**Only for:** pricing pages

**Observed:** Centered 77px page title and 28px support at a 160px top inset. Three Plan cards follow with 24px gaps; card tops align and their lengths vary with benefits. A separate entitlement chapter repeats the heading pair, then two License cards on an 800px grid with a modest underlined terms link below.

**Transfer:** Use the same heading hierarchy for another decision-oriented page; separate the purchase choice from the detailed permission explanation.

**Text style:** `heading` — TWKEverett 500 · 77px/1

## Page flow

**Storyline:** Simple promise → tangible outcomes → task demonstration → breadth and capability proof → reassurance → continuing relationship → utility links.

### Introduce a creative product through the quality and ease of its outputs

1. **Promise** — Centered two-line statement, single action and a broad output reel.
2. **Outcome proof** — Asymmetrically staged photographs show the same work across formats.
3. **Task demonstration** — Immersive blue workflow chapter pairs large step text with changing portrait media.
4. **Hands-on proof** — Oversized example and small input presets make the task feel approachable.
5. **Breadth** — Centered invitation above a four-column output gallery.
6. **Capability chapters** — One charcoal stage moves from a monumental statement into alternating square-media rows.
7. **Social proof** — Edge-clipped work strip with small maker attributions.
8. **Objection handling** — Pale FAQ slab with white expandable rows.
9. **Continuing relationship** — Short invitation and social links face a blue sculptural emblem.
10. **Utility ending** — White, spacious brand-and-columns footer with a separate legal row.

**Transfer:** Borrow the narrative functions, not the number of chapters. Retain strong output photography, a full blue demonstration stage, a dark capability stage and the tactile blue emblem as the distinguishing visual devices.

### Help readers choose an offer and understand the terms

1. **Choice framing** — Centered title and short upgrade-oriented support line.
2. **Pricing** — Three raised white panels with benefit lists, billing controls, prices and actions; one header receives the blue gradient.
3. **Objection handling** — Parallel permission lists in two compact license cards, followed by a detailed terms link.
4. **Utility ending** — The same white footer, with no sculptural social chapter inserted.

**Transfer:** For a transactional page, prioritize compact comparison panels and factual criteria while retaining the shared typography, action blue and spacious footer.

## Writing

Friendly, direct and lightly playful, with the confidence of a creative tool that can demonstrate its usefulness. Claims emphasize ease, concrete tasks and visible outcomes rather than abstract transformation.

**Do not copy:** Do not reuse the Maneken name, logo, blue figure silhouette, artist work, creator identities, catalog counts, subscription prices, license promises or product-specific claims. Source quotations below illustrate voice only.

- **Addressing the reader:** Address the reader as you or your; use we for help and reassurance. Name the product when explaining a specific capability, not in every headline.
- **Rhythm:** Headlines are generally short phrases of roughly three to eight words. Support lines are one plain sentence or fragment; feature descriptions are brief and practical. A playful headline is usually followed by a literal explanation.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | Name the core task and reduce its perceived difficulty. | 3–6 words | “Mockups made easy” |
| Product-category support | One factual description of what the tool is. | 5–10 words | “The browser powered mockup editor” |
| Section headline | A conversational phrase or playful idiom, anchored by literal supporting text. | 4–8 words | “Drop it like it's hot”<br>“We got you covered” |
| Feature explanation | Begin with an action, name the object and explain the practical result. | One short sentence | “Create the perfect layout and apply photo effects.” |
| Primary action | Short verb phrase focused on beginning or seeing the product. | 2–4 words | “Start for Free”<br>“Browse our catalog” |
| Decision headline | Plain invitation to make the next choice. | 3–5 words | “Choose your plan” |
| Relationship invitation | A minimal invitation with a practical reason to stay connected. | 2–3 word title plus one sentence | “Follow us”<br>“Stay up to date for the new releases and content updates” |

**Words and phrasing to use:** easy; create; insert; edit; export; bring your ideas to life; we got you covered; get started; free; your workflow

**Avoid:** revolutionary ecosystem; unprecedented synergy; enterprise-grade transformation; disrupt the future; overwritten luxury language

**Rules:**

- Tie each capability to an action the reader can picture.
- Use one playful expression at a time; keep its explanation literal.
- Keep offer details and permission language factual, distinct and easy to compare.
- Prefer short descriptive action labels over urgent or manipulative conversion copy.

## Do's and Don'ts

### Do

- Keep the opening display at 110px/1, weight 500, with normal tracking and a deliberately balanced two-line silhouette.
- Preserve the 30px rhythm between major headings, descriptive lines and centered actions.
- Frame major slabs with 20px white gutters and 15px corners.
- Give product outputs room at 1000–1200px wide or roughly half a capability row, not only thumbnail scale.
- Use 55px-high, 10px-radius blue actions for marketing conversions and the compact 48px variant in navigation.
- Keep the fixed 60px navigation tray white even above blue and charcoal chapters.
- Carry maker attribution in 36px-high white badges over the work itself.
- On comparison pages, use 24px column gaps, subtle 1px edges and a blue highlight confined to the premium header.

### Don't

- Do not tighten the large headlines with negative tracking; the measured recipes remain normal throughout.
- Do not turn the blue conversion rectangles into pills or oversized full-width marketing bars.
- Do not make every chapter white: the full blue workflow stage and charcoal material contrast are central to the visual language.
- Do not spread blue gradients across ordinary headings; clipped blue prices and gradient headers belong to offer comparisons.
- Do not apply comparison-card borders and glass blur to every marketing section; the main chapters are broad flat slabs.
- Do not replace natural output photography with rows of colorful feature icons.
- Do not replace the blue sculptural punctuation with an emoji, a neon glow or an unrelated stock mascot.
- Do not compress the footer into a single dark bar; keep its white field, 140px top padding and separate pale legal rule.

## Motion and responsive

### Motion

**Observed:**

- Primary actions declare transform transitions of .4s cubic-bezier(.175,.885,.32,1.275), with scale(1.05) on hover and focus-visible and scale(0.95) while active.
- Navigation and footer links declare .2s opacity cubic-bezier(.445,.05,.55,.95), moving from 0.5 to 1 on hover and focus-visible.
- Legal links additionally declare .4s background-size cubic-bezier(.215,.61,.355,1).
- Photographic showcase items declare a .6s entrance animation using cubic-bezier(.445,.05,.55,.95). Output reels, changing workflow media and the sculptural object use video; the work strip is horizontally translated.

**Transfer:**

- Use the spring-like button scale as the main interaction signature, while text-link changes remain restrained.
- Keep demonstrations result-led: change the displayed output with the workflow step rather than animating decorative copy independently.

**Unknown:**

- Video playback schedules, carousel speed, scroll choreography and the exact entrance keyframes are not established.

### Responsive

**Observed:**

- Source styles declare width breakpoints at 767px, 768px, 1200px and 1280px.

**Transfer:**

- On narrow screens, preserve the centered promise above its media theater, reducing headline size while retaining a deliberate two-line break where possible.
- Stack capability and comparison columns when necessary; keep each explanation adjacent to its result and retain the dark or blue chapter backing.
- Retain the creator strip's edge-clipped continuity rather than shrinking all images into tiny cards.

**Unknown:**

- Mobile navigation construction, exact type sizes, insets and reordering at each breakpoint are not established. These stacking rules are design recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
