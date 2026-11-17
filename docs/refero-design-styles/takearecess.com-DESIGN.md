# Recess — pastel daydream playground

## Overview

A playful, spacious consumer-product style that makes everyday relief feel like a small escape. Dark forest openings give way to periwinkle skies, peach and pink washes, cobalt punctuation and deep navy endings. Wide geometric grotesk lettering, brightly lit product photography, floating cutouts and soft sculptural clouds create an airy, gently surreal world rather than a conventional wellness brochure.

### Essentials

- Conversational headlines have a broad, rounded presence rather than a delicate wellness look: Sharp Grotesk Web at 60px, weight 500, line height 1.25 and normal tracking; mostly lowercase sentence openings.
- The opening feels like a product invitation at night: a forest-green 900px stage, a left-hand three-line headline and a 626px square, flash-lit photograph on the right, with one cream rectangular action beneath the copy.
- Color is the environment, not a sprinkle of accents: after the dark opening, full-width periwinkle and pastel-gradient stages occupy most of the narrative; navy anchors text and the footer, while cobalt is reserved for a short statement or an entire proof band.
- Actions feel like movable paper blocks: primary buttons have square corners, 2px borders, 24px 36px padding, 16px bold uppercase labels and a hard lower-left backing, not a soft shadow. Rounded 57px-high controls are secondary.
- Products inhabit a sky rather than a card deck: bright isolated objects float, tilt and then settle into generous rows beneath centered 60px headings. Soft cloud sculptures must recur around the narrative; use shaded SVG cloud clusters when custom three-dimensional assets are unavailable.
- Endings offer a little escape before the utility: a spacious 900px newsletter scene pairs an underlined email field with a surreal doorway sculpture, followed by a deep-navy footer with a broad wave edge, three link columns and a wider newsletter column. Reinterpret the doorway as an inviting geometric portal when no custom artwork exists.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Peach | `#ffc8a0` | `--color-peach` | background, surface | Warm gradient stop; solid selection stage in purchase flows. |
| Periwinkle sky | `#a2b0ff` | `--color-sky` | background | Main sky-like canvas for floating objects and centered product chapters. |
| Gradient lilac | `#a8b2ff` | `--color-gradient-lilac` | background | Cool end of the peach-pink-lilac environment. |
| Apricot | `#fedab3` | `--color-apricot` | background, surface | Warm newsletter stage and product-selection field. |
| Blush pink | `#ffb8b8` | `--color-pink` | background | Soft gradient stop and illustrated benefit band. |
| Pale lavender | `#c2caff` | `--color-lavender-panel` | surface, action | Button faces and light testimonial panels over periwinkle. |
| Banner navy | `#1d2a58` | `--color-announcement` | background | Narrow promotional strip at the top. |
| Cloud-burst navy | `#25385b` | `--color-ink` | text, border | Default lettering, outlines and hard offset backing on pastel fields. |
| Midnight navy | `#0a0a3a` | `--color-footer` | background | Full-width closing utility region. |
| Night forest | `#00140c` | `--color-forest` | background | Dark opening stage; do not extend this dark theme across the pastel narrative. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric blue | `#163bf3` | `--color-cobalt` | text, background, accent | Short emphatic statements, a saturated press band and focus outlines. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Cream button | `#fffcef` | `--color-cream` | action | Primary action on the forest stage. |
| Muted footer text | `#a6a6b7` | `--color-muted` | text | Secondary utility and colophon copy against midnight navy. |
| White | `#ffffff` | `--color-inverse` | text, border | Type and thin image edges on the forest opening, cobalt proof band and navy footer. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| catalog category bands | Sunset coral | `#ff8672` | `--color-coral` | background | Top stop of warm-to-cool category gradients. |
| catalog category bands | Sunset peach | `#ffc27a` | `--color-sunset-peach` | background | Middle stop of category gradients. |
| catalog category bands | Sunset lilac | `#a7a4df` | `--color-sunset-lilac` | background | Lower stop of category gradients. |
| subscription or configuration landing pages | Browser chrome gray | `#dedede` | `--color-window-edge` | border, surface | Faux browser frame. |
| educational product explainers | Light lavender rule | `#e9ecff` | `--color-section-rule` | border | 2px separator between educational chapters. |

## Typography

- **Sharp Grotesk Web** — Headlines, body, actions, captions and navigation. Wide, friendly geometric grotesk with substantial lowercase forms and an open, unhurried rhythm. If unavailable, use **Montserrat**. Use weights 400, 500 and 700; retain normal tracking and generous headline widths. Font stack: "Sharp Grotesk Web", "Montserrat", system-ui, -apple-system, "Segoe UI", sans-serif.
- **Antidote Display Web** (only for catalog and purchase slogan ribbons) — Repeating slogan ribbons, not main headings. Compact, personable display lettering that gives small slogans a branded cadence. If unavailable, use **DM Sans**. Font stack: "Antidote Display Web", "DM Sans", sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Sharp Grotesk Web | 500 | 60px | 1.25 | normal | Opening headline and principal section headings, usually lowercase-led. |
| body-large | Sharp Grotesk Web | 400 | 24px | 1.625 | normal | Mission statements and more expansive narrative copy. |
| chapter-support | Sharp Grotesk Web | 400 | 24px | 1.375 | normal | Centered support beneath floating-product chapter headings. |
| email-label | Sharp Grotesk Web | 500 | 24px | 1.2 | normal, lowercase | Main newsletter scene's inline field label. |
| body | Sharp Grotesk Web | 400 | 20px | 1.625 | normal | Opening support line and explanatory product summaries. |
| quote | Sharp Grotesk Web | 500 | 20px | 1.625 | normal | Centered customer testimony. |
| footer-heading | Sharp Grotesk Web | 500 | 18px | 1.625 | normal | Footer column headings. |
| footer-body | Sharp Grotesk Web | 400 | 18px | 1.625 | normal | Footer newsletter invitation. |
| button | Sharp Grotesk Web | 700 | 16px | 1.125 | normal, uppercase | Rectangular conversion actions. |
| navigation | Sharp Grotesk Web | 400 | 16px | 1 | normal | Small header links and testimonial attribution. |
| small-link | Sharp Grotesk Web | 400 | 14px | 1.625 | normal | Compact footer navigation. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| educational product explainers | explanation-heading | Sharp Grotesk Web | 500 | 36px | 1 | normal | Mid-sized heading in a half-width explanation panel. |
| purchase configuration | choice | Sharp Grotesk Web | 400 | 20px | 1.125 | normal, lowercase | Frequency text inside broad rounded choices. |
| catalog and purchase slogan ribbons | ribbon | Antidote Display Web | 400 | 16px | 1 | normal | Continuously repeated short slogans separated by tiny cloud marks. |
| educational product explainers | ingredient-caption | Sharp Grotesk Web | 400 | 14px | 1.25 | normal | Short benefit below a named illustrative object. |

**Notes:**

- Keep tracking normal even at 60px. The personality comes from wide letterforms, lowercase language and relatively loose 1.25 headline leading, not condensed or tightly tracked display type.
- Use 60px for both the opening and major section titles; hierarchy is driven by composition, color and surrounding space rather than escalating font sizes.
- Short actions are bold and uppercase; conversational support, navigation and field labels remain lowercase-led.

## Layout

**Density:** Airy in storytelling, compact in shopping grids: large uninterrupted color fields surround relatively short copy, while merchandise cells share edges.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Heading-to-support gap in centered chapters. |
| 16px | Header vertical padding and compact internal group spacing. |
| 24px | Inline main newsletter form gap and secondary content spacing. |
| 28px | Support-to-primary-action gap. |
| 32px | Catalog cell padding, object-to-label spacing and repeated content stacks. |
| 40px | Testimonial panel padding. |
| 48px | Large content group gaps and roomy section stacks. |
| 64px | Footer top zone before its content. |
| 80px | Opening column gap and footer row gap. |
| 84.4px | Vertical padding of broad benefit, choice and proof bands. |
| 144px | Deep product-stage breathing room. |
| 160px | Extended lower breathing room of the final catalog category. |

### Containers and grids

- **content-container**: max width 1267px · side padding 86.4px. Centered desktop narrative and footer content at a 1440px viewport.
- **opening-split**: 2 columns · gap 80px. Two equal 626px columns; text begins at the normal left gutter while the right media extends closer to the edge.
- **centered-copy**: max width 934px. Centered section title and compact two-line chapter support.
- **footer-grid**: 5 columns · gap 36px. Three single-track link columns and a two-track newsletter area, with 80px between rows.
- **reading-column** (only for purchase explanations): max width 768px. Centered questions and longer answers.
- **catalog-grid** (only for catalog and purchase selection): 4 columns · gap 0px. Edge-to-edge shared-border merchandise cells, each approximately 362px by 320px at desktop.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | Primary actions and panels | 0px |
|  | Secondary controls | 36.5px |
|  | Hero photograph | 40px |
| purchase configuration | Frequency choices | 45px |

## Surfaces and depth

### Surfaces

#### Forest opening · level 0

**Use:** First-screen product introduction.

**CSS:** `background: #00140c; color: #ffffff`

**Observed:** A full-width dark stage makes the colorful photograph and cream action feel especially bright.

**Transfer:** Reserve this darkness for the opening; let the rest of the page open into pastel color.

#### Periwinkle sky · level 0

**Use:** Default narrative environment after the opening.

**CSS:** `background: #a2b0ff; color: #25385b`

**Observed:** Clouds and isolated products share the same uninterrupted field, with no card rectangles behind the product rows.

**Transfer:** Use a single sky field across related chapters; change the atmosphere rather than boxing each capability.

#### Pastel wash · level 0

**Use:** Broad product-family stage.

**CSS:** `background: linear-gradient(#ffc8a0, #ffb8b8, #a8b2ff); color: #25385b`

**Observed:** Peach, blush and lilac merge in low-contrast, luminous fields. The large product ensemble is the high-detail foreground.

**Transfer:** Use broad diffuse color changes; exact stops are less important than the soft, enveloping glow.

#### Quote paper · level 1

**Use:** Customer testimony over the sky.

**CSS:** `background: #c2caff; padding: 40px; color: #25385b; border-radius: 0px`

**Observed:** Flat lavender rectangles sit over a solid navy duplicate shifted down and right. Oversized quotation marks interrupt the upper edge.

**Transfer:** Create depth with a second flat rectangle, not blur or elevation.

#### Warm closing stage · level 0

**Use:** Large newsletter invitation.

**CSS:** `background: #fedab3; color: #25385b`

**Observed:** A warm field holds a left-aligned form and right-hand surreal sculpture, with clouds between them.

**Transfer:** Keep the scene sparse enough to read as a destination rather than a form card.

#### Midnight footer · level 0

**Use:** Shared ending.

**CSS:** `background: #0a0a3a; color: #ffffff; padding-top: 64px`

**Observed:** The upper edge is a broad shallow wave. Content is organized in link columns, a newsletter form, brand and social row, an animation control and lower utility material.

**Transfer:** Retain the wavy edge and long, spacious ending even when the utility content is shorter.

#### Sunset category · level 0

**Only for:** catalogs

**Use:** Merchandise category bands.

**CSS:** `background: linear-gradient(#ff8672, #ffc27a, #a7a4df); color: #25385b`

**Observed:** Warm coral flows through peach into cool lilac behind a ribbon, split heading pair and bordered product row.

**Transfer:** Assign each category its own gentle environmental color variation rather than a different card color.

#### Illustrated benefit band · level 0

**Only for:** subscription landing pages

**Use:** Subscriber advantage summaries.

**CSS:** `background: #ffb8b8; color: #25385b; padding: 84.4px 0px`

**Observed:** Four large lavender tubular symbols stand above compact uppercase labels and a short sentence.

**Transfer:** Keep icons unusually large relative to the brief supporting text.

## Components

### Primary button

**Use:** Main action on a marketing stage.

**CSS:** `background: #fffcef; color: #25385b; border: 2px solid #25385b; border-radius: 0px; padding: 24px 36px; min-height: 70px; transform: translate3d(4px, -4px, 1px)`

**Text style:** `button` — Sharp Grotesk Web 700 · 16px/1.125 · uppercase

**Observed:** The button face is displaced from a solid ink backing toward the upper right, leaving a hard lower-left ledge. Pastel scenes use lavender faces; dark scenes may use white text and outlines.

**States:** Declared: hover transform translate3d(calc(.25em*1.5),calc(.25em*-1.5),1px); focus-visible outline 3px solid #163bf3 with 4px offset. Opacity and outline transition for 0.3s; transform for 0.15s.

**Transfer:** Keep the offset backing separate from the face so the hover movement reveals more of it.

### Header navigation link

**Use:** Sparse sticky header navigation.

**CSS:** `padding: 12px; color: #ffffff; background: transparent`

**Text style:** `navigation` — Sharp Grotesk Web 400 · 16px/1

**Observed:** A small handwritten-style identity sits at left, a shop label with tiny cloud sits beside it, and subscription, login and cart controls align at right. The foreground changes to navy over pastel sections.

**States:** Declared: hover state unspecified; focus-visible outline 3px solid #163bf3 with 4px offset.

**Transfer:** Use a compact identity mark and few short labels, not a full-width button-filled navigation bar.

### Quote panel

**Use:** Customer proof in a horizontal gallery.

**CSS:** `padding: 40px; width: 432px; background: #c2caff; color: #25385b; text-align: center`

**Text style:** `quote` — Sharp Grotesk Web 500 · 20px/1.625

**Observed:** Panels vary in height with the quote. A navy duplicate is offset down and right, quotation marks sit across the top edge, and a smaller attribution follows below the quotation.

**Transfer:** Allow neighboring panels to differ in height; keep the text short enough to remain airy.

### Inline email field

**Use:** Large newsletter stage.

**CSS:** `border: 0px; border-bottom: 2px solid #25385b; background: transparent; padding: 6px 12px; height: 43px; color: #25385b`

**Text style:** `email-label` — Sharp Grotesk Web 500 · 24px/1.2 · lowercase

**Observed:** A visible label and asterisk share a continuous underline with the input; a plain-text sign-up action sits alongside it. The combined label and input span about 384px.

**Transfer:** Keep the field visually integrated into the stage rather than placing it in a filled box.

### Footer link group

**Use:** Compact utility navigation.

**CSS:** `color: #ffffff; padding: 1.8px 0px`

**Text style:** `small-link` — Sharp Grotesk Web 400 · 14px/1.625

**Observed:** Six short links stack under an 18px medium heading; columns sit on the navy field without separators.

**States:** Declared: hover color lightens; focus-visible outline 3px solid #163bf3 with 4px offset.

**Transfer:** Group by shopping, information and contact function, retaining short lowercase labels.

### Footer newsletter

**Use:** Wide right-hand footer column.

**CSS:** `max-width: 576px; color: #ffffff`

**Text style:** `footer-body` — Sharp Grotesk Web 400 · 18px/1.625

**Observed:** An 18px medium heading precedes an 18px regular invitation. Beneath it, a white 2px underline field and simple sign-up text sit on one baseline with an 18px gap.

**Transfer:** Use a single friendly sentence to explain the exchange; no nested card or oversized action.

### Product tile

**Only for:** catalogs and purchase configuration

**Use:** Shared-border product selection.

**CSS:** `border: 2px solid #25385b; padding: 32px; display: flex; flex-direction: column; align-items: center; justify-content: end; gap: 32px; margin: -1px`

**Text style:** `navigation` — Sharp Grotesk Web 400 · 16px/1

**Observed:** Four touching cells form a desktop row. Each contains a contained cutout image, then a centered label. Catalog images occupy about 294px by 200px. Purchase variants add a bottom control rail split into quantity controls and add-to-cart.

**Transfer:** Keep the surrounding category gradient visible through the cells and align labels along the bottom.

### Expansion control

**Only for:** catalogs

**Use:** Reveal more variants beneath a product row.

**CSS:** `border: 2px solid #25385b; border-radius: 36.5px; padding: 16px; background: transparent; color: #25385b; height: 57px`

**Text style:** `navigation` — Sharp Grotesk Web 400 · 16px/1

**Observed:** A centered rounded outline control sits 32px below the product grid, quieter than the square conversion buttons.

**States:** Declared: hover state unspecified; focus-visible outline 3px solid #163bf3 with 4px offset.

### Frequency choice

**Only for:** purchase configuration

**Use:** Single-select delivery interval.

**CSS:** `background: #ffc8a0; color: #25385b; border: 2px solid #25385b; border-radius: 45px; padding: 27.1px 45px; transform: translate3d(5px, -5px, 1px)`

**Text style:** `choice` — Sharp Grotesk Web 400 · 20px/1.125 · lowercase

**Observed:** Three choices sit in a centered row, each beneath a short delivery label. Their hard backing echoes the main button construction; the selected face becomes a lighter peach.

**Transfer:** Use for a small set of meaningful choices, not every filter.

### Slogan ribbon

**Only for:** catalog and purchase sections

**Use:** Divider between shopping categories.

**CSS:** `border-top: 2px solid #25385b; border-bottom: 2px solid #25385b; padding: 8px 0px; overflow: hidden; display: grid; gap: 12px`

**Text style:** `ribbon` — Antidote Display Web 400 · 16px/1

**Observed:** Short phrases repeat horizontally with tiny cloud silhouettes between them; text is clipped at both viewport edges.

**Transfer:** Write two or three short complementary phrases rather than repeating a paragraph.

## Imagery and graphics

### Flash-lit product encounter

**Use:** Main opening image.

**Observed:** A tight square photograph shows hands bringing two colorful cans together, liquid splashing above them and a dark curtain behind. Direct light produces bright packaging, tactile skin and deep background shadows. A thin light edge and generously rounded corners frame the image.

**Transfer:** Show the new product being used in a close, social or tactile moment. Use direct light, saturated product color and dark environmental depth; the minimum equivalent is one beautifully lit object with a human hand and a dark backing.

### Floating sky collection

**Use:** Signature narrative device across product chapters.

**Observed:** Precisely isolated cans, boxes and tubs float at slight angles around centered copy before appearing as orderly front-facing rows. Colorful packaging supplies detail while the pastel field remains open. Soft cream-lilac cloud puffs recur at different depths and occasionally overlap the objects.

**Transfer:** Stage isolated product objects with consistent frontal light and modest rotations. For nonphysical offerings, create tangible symbolic objects or simple dimensional interface slabs rather than pasting a full dashboard into every chapter.

**Build:** Build cloud puffs as SVG clusters of 4–6 overlapping circles or irregular ellipses, spanning roughly 40–150px. Shade each with radial gradients from white through pale lavender to peach; use subtle soft internal shading rather than an outer drop shadow. Scatter 5–8 at unequal sizes around the content perimeter and between rows, keeping the main text readable. Place crisp transparent object renders above this cloud layer.

### Atmospheric color field

**Use:** Soft backdrop behind hero ensembles and narrative chapters.

**Observed:** Large peach, pink and lilac areas blend without hard bands, with luminous cooler edges and warmer centers. The color field fills the entire viewport width rather than appearing inside a contained panel.

**Transfer:** Make an enveloping color atmosphere for the new product; let strongly colored foreground objects provide contrast.

**Build:** Layer broad peach and pink radial gradients with transparent edges over a periwinkle base. Give the ellipses widths of about 800–1200px on desktop, blur the color layer by about 80px and oversize it beyond the stage boundary. Keep text and products on separate crisp layers. A simple peach-to-blush-to-lilac linear gradient is the minimum version.

### Portal invitation

**Use:** Signature large newsletter closing scene.

**Observed:** Blue and violet steps float below a coral-edged arched doorway filled with bright sky and white clouds. The sculpture occupies the right third of the warm stage while the left side carries the headline and email form.

**Transfer:** Create a small impossible architectural invitation appropriate to the new product: a doorway, window or lifted platform. The minimum is a crisp dimensional arch and stacked steps with a sky-colored interior.

**Build:** Use SVG rectangles and skewed parallelograms for 6–7 steps, alternating cobalt tops with violet side faces. Place an arched opening above, made from a rectangle capped by a semicircle with a thick pink rim. Fill it with blue sky and soft white cloud forms. Keep the full sculpture near 272px by 445px, isolated without a ground plane.

### Colorful tabletop still life

**Only for:** educational product explainers

**Use:** Product-family illustration beside educational copy.

**Observed:** Bright cans and packages stand among fruit, flowers, vegetables, glassware and playful colored props. Scenes are cropped to a half-width 720px by 360px rectangle with no inset border; red checks, shiny surfaces and saturated orange or pink provide a tactile counterweight to the flat text panel.

**Transfer:** Photograph the product among physical materials that explain its use or character, with a carefully coordinated but abundant palette. Preserve the tight two-to-one framing.

### Ingredient and benefit specimens

**Only for:** educational and subscription benefit sections

**Use:** Illustrated explanatory rows.

**Observed:** Large isolated leaves, delicate stems, flowers, faceted lavender crystals and a golden lightning bolt sit above small centered labels. Subscription benefit symbols instead look like inflated lavender tubing, including a bell and sliders.

**Transfer:** Use one isolated object per benefit, mixing literal materials with a few sculptural symbols. Avoid a uniform generic line-icon library.

**Build:** For a minimal version, draw simple botanical silhouettes with internal vein strokes, a low-poly crystal built from lavender polygons and an extruded lightning shape in SVG. For tubular symbols, use thick rounded paths with layered pale-lavender highlights and darker inner-edge strokes; render them in a roughly 312px square.

### Rotating product wreath

**Only for:** subscription landing pages

**Use:** Playful closing affirmation after questions.

**Observed:** A large ring of pastel product cans, each at a different axial angle, surrounds an empty center. The 883px-square artwork sits over periwinkle before a centered cobalt closing line.

**Transfer:** Arrange repeated product objects or simple representative forms into a loose circular sculpture instead of another rectangular banner.

**Build:** Position about 10 isolated objects around a circular SVG group, rotate each tangentially and vary its tilt slightly. Keep a central opening of roughly one third the total diameter and softly lit pastel surfaces.

### Icons

**Observed:** Tiny filled clouds punctuate the shop label and ribbons at about 12px. Cart and account-sized controls are around 16px; white social marks are around 24px. One small outlined navigation mark uses a 2px rounded stroke.

**Transfer:** Use a tiny soft-shaped divider mark consistently, paired with simple lightweight utility symbols. Large benefit illustrations belong to the imagery system, not the utility icon set.

## Section recipes

How recurring sections are built.

### First screen: Nighttime product invitation

**Observed:** A 32px navy announcement ribbon precedes a sparse sticky header. Beneath it, a forest stage fills approximately 900px. Two equal columns are separated by 80px: the left holds a 60px medium headline over three lines, a 20px support sentence and the Primary button; the right holds a 626px square Flash-lit product encounter with a fine white edge and rounded corners. The text is vertically centered against the photograph rather than pinned to the top. Back-to-front layers are forest field, header and content, photograph, then the cream offset action. Within the first 900px the header, whole headline, support, action and complete main object are visible; the pastel collection stage begins below.

**Transfer:** For a new product, retain the dark intimate invitation and one dominant tactile product image. Use a close photograph or one well-lit object with a human gesture if there is no campaign image. Educational pages open instead with a centered 60px title and 20px introduction over sky; catalogs use a left title with a right product ensemble; subscription pages use a centered faux browser window.

**Avoid:** Do not replace this opening with a pastel centered slogan, a wall of small product tiles or a giant edge-to-edge photograph that leaves no separate copy column.

**Text style:** `display` — Sharp Grotesk Web 500 · 60px/1.25

### Collection on a cloud field

**Observed:** A centered 60px title and 20px summary sit above an approximately 1024px by 564px product ensemble. The Pastel wash spans the full background; a Primary button anchors the lower center.

**Transfer:** Show the breadth of the offering with a small overlapping family of objects, keeping their labels legible and their scale much larger than surrounding copy.

**Text style:** `display` — Sharp Grotesk Web 500 · 60px/1.25

### Floating product chapter

**Observed:** Centered display heading plus chapter-support with an 8px gap, constrained to roughly 934px. Floating sky collection objects occupy the surrounding and lower stage, then resolve into an aligned row of 4–6 products with small labels. A quiet rounded shop control sits at the lower right.

**Transfer:** Use one chapter per meaningful family or benefit and give each enough visual space to form its own scene. The floating-to-row contrast matters more than reproducing a long section sequence.

**Text style:** `display` — Sharp Grotesk Web 500 · 60px/1.25

### Cobalt press interlude

**Observed:** A full cobalt field switches all heading, publication marks and brief quotations to white. A horizontal row of roughly 256px-wide editorial quotes sits below the centered 60px title, followed by a contrasting rectangular press action.

**Transfer:** Use a small number of credible editorial endorsements or external validations, preserving the abrupt blue immersion and compact white typography.

### Customer quote gallery

**Observed:** A centered 60px heading introduces Quote panels in a horizontal row, with the outer panels partially clipped by the viewport. The middle panel can be taller; the pale faces and navy offset backings create visible physical depth. A Primary button follows below.

**Transfer:** Use authentic short testimony, balancing a few differently sized panels rather than forcing identical heights.

### Portal newsletter destination

**Observed:** Warm closing stage spans about 900px. A left-aligned two-line 60px invitation sits above the Inline email field; Portal invitation occupies the right third and small clouds cross the open middle. The Midnight footer follows after breathing room.

**Transfer:** Give the final conversion an atmospheric object and a simple exchange, not a dense checklist or sales pitch.

### Wave into utility

**Observed:** A broad shallow wave introduces the Midnight footer. Three link columns and Footer newsletter fill the first row, followed by the identity mark, social controls and a square animation pause control. Lower rows carry a thin outlined notice, credits and subdued utility material. The full ending is roughly 1028px tall at desktop.

**Transfer:** Preserve the undulating boundary, two scales of type and generous lower space; include only utility content relevant to the new product.

### Faux window invitation

**Only for:** subscription or configuration landing pages

**Observed:** A centered 1257px by 450px pastel gradient content area sits inside a gray faux browser frame with a small top bar and three dots. A 60px heading, 24px support, small reassurance and Primary button fill its center; fruit and product cutouts overlap the edges.

**Transfer:** Turn an enrollment promise into a playful contained world. Use new contextual cutouts around the frame, keeping the central copy unoccluded.

### Alternating explanation and specimens

**Only for:** educational product explainers

**Observed:** Each approximately 692px chapter starts with a half-width 720px by 360px tabletop photograph beside a centered text panel using explanation-heading, body and a smaller rectangular action. The image and text sides alternate. Beneath them, 3–4 large ingredient specimens appear with names and ingredient-caption benefits; a pale 2px rule closes the chapter.

**Transfer:** Pair concrete material proof with a concise explanation, then break the benefit down into a small illustrated specimen row.

### Ribbon and merchandise matrix

**Only for:** catalogs

**Observed:** Slogan ribbon caps a category. A 60px category title occupies the left half and 24px support occupies the right; Product tiles span four touching columns underneath. Expansion control sits centered 32px below the grid. A final category leaves 160px of lower breathing room before the wave footer.

**Transfer:** Use a few well-differentiated categories with shared-border rows, rather than a single unstructured product wall.

### Choices then reassurance

**Only for:** purchase configuration

**Observed:** Large centered section titles introduce an illustrated four-benefit band, then a warm selection band with three Frequency choices. A four-column bordered merchandise grid follows. Questions use a centered reading column with uppercase question labels and 24px answers. A Rotating product wreath and cobalt affirmation lead into the wave footer.

**Transfer:** Move from a reassuring promise to simple decisions and then objection handling. The circular closing sculpture provides emotional release after dense selection.

## Page flow

**Storyline:** Invitation → breadth of possibilities → focused product or benefit chapters → credible reassurance → a playful final exchange → wave-edged utility ending.

### Immersive marketing introduction

1. **Product invitation** — Dark split opening with tactile square photography and one offset action.
2. **Breadth** — Large product ensemble over a pastel atmospheric field.
3. **Motivation** — Brief centered explanation of the everyday problem.
4. **Product exploration** — Floating-object chapters resolve into labeled rows.
5. **External and customer proof** — Cobalt editorial band followed by lavender quote panels.
6. **Closing exchange** — Warm newsletter scene with a portal sculpture.
7. **Utility ending** — Long midnight footer with wave boundary, link columns and a second small newsletter form.

**Transfer:** Adapt the chapter count to the offering while preserving the transition from intimate dark opening to expansive pastel exploration.

### Reassure and configure a recurring purchase

1. **Enrollment promise** — Gradient faux browser window surrounded by overlapping objects.
2. **Benefits** — Four large tubular illustrations over blush.
3. **Configuration** — Warm interval choices, followed by a bordered merchandise matrix and repeating slogan ribbons.
4. **Objection handling** — Centered questions and generous full answers.
5. **Emotional close** — Large circular product sculpture and cobalt affirmation.
6. **Utility ending** — Wave-edged midnight footer with navigation, email and lower notices.

**Transfer:** Keep the configuration steps explicit and the final scene emotionally light after the dense shopping region.

### Explain what makes the offering work

1. **Framing promise** — Centered sky-backed headline and a short empathetic introduction.
2. **Mechanism and materials** — Alternating half-image, half-copy chapters with illustrated specimen rows.
3. **Further discovery** — Centered heading above four simple resource links.
4. **Utility ending** — Broad wave into the same spacious navy footer.

**Transfer:** Explain each family through a concrete image and a few named contributors instead of a technical specification wall.

### Browse product families efficiently

1. **Orientation** — Left headline and support beside a right-hand product ensemble.
2. **Category exploration** — Repeating slogan ribbon, split category heading, four shared-border product tiles and rounded expansion control.
3. **Final browsing invitation** — Last warm-to-cool category leaves extra breathing room after its action.
4. **Utility ending** — Wave-edged midnight footer; no extra sales banner is needed.

**Transfer:** Let environmental gradients differentiate families while keeping tile construction consistent.

## Writing

Warm, lightly mischievous and reassuring, with a direct sense of everyday life rather than clinical authority. Benefits are described as small changes in how a person feels or moves through the day.

**Do not copy:** Do not reuse Recess names, taglines, packaging art, product formulas, discounts, efficacy claims, publication logos, customer quotations or regulatory statements. Create new substantiated claims and original imagery for the new product. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Use we to explain intentions and you to recognize ordinary frustrations. Speak as a helpful peer; let the product name carry identity without repeating it in every sentence.
- **Rhythm:** Short lowercase-led headlines, one- or two-sentence support and compact action labels. Ampersands and parenthetical reassurance make longer explanations feel conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening headline | A simple invitation to meet something concrete rather than an abstract superlative. | 5–9 words | “meet Zero Proof Apple + Espresso ‘Tinis” |
| Chapter title | Short product-family name or everyday benefit, set without a formal introductory eyebrow. | 2–5 words | “calm for every occasion”<br>“why it's great” |
| Supporting line | Describe what the product does in familiar, human terms; a contrast can make the benefit memorable. | 8–24 words | “the iconic martini experience without the hangover” |
| Reassurance | A small parenthesis removes a specific worry immediately next to the action or choice. | 6–14 words | “(pause, skip or cancel at anytime)” |
| Action | A direct verb and a concrete destination, without hype. | 2–4 words | “shop all products”<br>“get started”<br>“show more flavors” |
| Newsletter invitation | A personable promise about the quality of the exchange, with a low-key aside. | 15–25 words | “if you give us your email we promise to only write things worth reading (& the occasional deal)” |

**Words and phrasing to use:** meet; a moment; help you; everyday; we made; unwind; discover more; don't worry; &

**Avoid:** revolutionary; biohack; maximum performance; clinically guaranteed; unlock your potential; act now!!!

**Rules:**

- Name the recognizable everyday tension before explaining the mechanism.
- Keep headline language informal even when the subject is scientific.
- Use uppercase mainly for short button labels and categorical question labels, not whole paragraphs.
- Give choices concrete labels and follow with reassurance, not artificial urgency.
- Use a small humorous aside sparingly; clarity still leads.

## Do's and Don'ts

### Do

- Keep principal headings at 60px/1.25, weight 500, with normal tracking.
- Use full-width periwinkle and pastel environments after the forest opening.
- Give the opening image approximately equal visual weight to the text column.
- Construct main actions with 2px outlines and a hard displaced backing.
- Use 32px internal padding and shared edges for catalog cells.
- Keep small footer headings at 18px and links at 14px/1.625.
- Repeat soft sculptural clouds at varied sizes throughout the narrative.
- Reserve a spacious final scene for the newsletter exchange and a wavy navy footer.

### Don't

- Do not apply capsule corners to the 70px-high primary actions; the rounded 57px controls serve a quieter role.
- Do not use thin elegant serifs or condensed display lettering for the main 60px headings.
- Do not make the narrative a white-page grid of rounded feature cards.
- Do not use blurred elevation shadows where the design calls for flat navy backing shapes.
- Do not shrink isolated product ensembles into thumbnails surrounded by long paragraphs.
- Do not spread cobalt across every button, caption and border; it works as focused punctuation or one immersive proof band.
- Do not make all product cutouts rotate at identical angles; the floating stages need an easy, irregular rhythm.
- Do not compress the footer into a narrow copyright strip or remove its broad wave boundary.

## Motion and responsive

### Motion

**Observed:**

- Primary button faces declare opacity 0.3s, outline 0.3s and transform 0.15s transitions, with a diagonal upper-right hover displacement.
- Category ribbons use linear infinite scrolling with row-specific duration and delay.
- The broad wave declares a 13s linear infinite animation; the product wreath declares a 20s linear infinite rotation.
- Color-scheme properties declare 0.6s transitions. Sticky product chapters visually alternate floating-object and aligned-row arrangements.
- A visible footer control allows site animations to be paused.

**Transfer:**

- Use motion to make objects feel suspended and to reveal an orderly collection, not to animate every text line.
- Keep the hard-backed button movement and provide an explicit pause control when the page uses continuous sky, ribbon or sculpture movement.

**Unknown:**

- Exact scroll interpolation and per-ribbon durations are not established.
- Which floating objects animate independently and their paths are not established.

### Responsive

**Observed:**

- Declared width breakpoints include 360px, 480px, 568px, 601px, 640px, 768px, 1024px, 1200px, 1460px, 1600px and 2000px.
- The opening uses centered text before a desktop left-aligned split; educational image-and-copy wrappers allow wrapping. Catalog grids declare auto-fit columns with a 320px minimum.

**Transfer:**

- On narrow widths, stack the opening copy and photograph, retaining the dark stage, cream action and rounded photo boundary.
- Reduce the number of simultaneous floating objects rather than scaling labels into illegibility.
- Let illustrated specimen rows scroll horizontally, preserving the substantial individual object scale.
- Stack footer groups while keeping the newsletter field and wave edge recognizable.

**Unknown:**

- Exact small-screen font sizes, navigation collapse behavior and final mobile compositions are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
