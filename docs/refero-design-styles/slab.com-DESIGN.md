# Slab — plum and paper

## Overview

An approachable editorial style for collaborative software and thoughtful business tools. Light, spacious pages pair a bookish slab serif with a humanist sans, punctuated by a rich plum opening and coral actions. Simplified interface illustrations float over pastel organic shapes and fine looping lines; customer photography adds an everyday, human counterpoint.

### Essentials

- Bookish promises rather than oversized tech slogans: Sentinel 53px/60.6px, weight 400, -1px tracking in the dark opening; 42px/52px regular serif headings carry the light body.
- A split plum stage makes the product tangible: a 560px text column faces an 872×650px interface scene that bleeds beyond the right edge; the first 900px includes navigation, signup choices and a customer-logo strip.
- Actions are small rounded rectangles, not pills: coral #ff4143, 6px corners, 18px/24px semibold type and 16px 24px padding; compact navigation actions shrink to 40px high.
- Color is concentrated at the opening and behind media: #42022e fills the first screen, while most of the remaining page is white with slate text. Cyan, yellow, coral and mint appear as small accents or translucent organic backing, not competing full-width bands.
- Product proof feels like paper cutouts: roughly 550px-wide white interface panels sit over flat pastel blobs and thin off-center loops. Include this layered organic device even without finished product media, using a legible simplified workflow panel.
- A reassuring orbital callout gives conversion its own visual world: a 489px near-white band contains a centered serif prompt and coral action, surrounded by clipped concentric hairlines and small labeled nodes. Carry this device into new landing pages with relevant tool or workflow labels.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Coral action | `#ff4143` | `--color-coral` | action, accent | Primary signup buttons and small line illustrations. |
| Deep plum | `#42022e` | `--color-plum` | background, text, border | Default opening stage; dark enterprise column and trust links are scoped applications. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Golden yellow | `#fcb415` | `--color-yellow` | accent, action | Illustration loops and categorized plan or trust actions. |
| Clear cyan | `#50c5dc` | `--color-cyan` | accent, action, link | Arrow accents, illustration outlines and categorized actions. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep slate | `#2f4050` | `--color-heading` | text, action | Light-page titles, emphasized labels and entry-plan action. |
| Slate ink | `#455360` | `--color-ink` | text | Default paragraphs and feature headings. |
| Muted gray | `#939598` | `--color-muted` | text | Captions, footer labels and closing reassurance. |
| Paper edge | `#e6e6e6` | `--color-rule` | border | Visible result of black at 0.1 opacity on white; fine panel outlines and footer separator. |
| Almost white | `#fcfcfd` | `--color-closing` | background | Orbital conversion band. |
| White paper | `#ffffff` | `--color-canvas` | background, surface, text | Main page, interface panels and reversed text on plum. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| audience pages | Mint | `#45c693` | `--color-mint` | text, accent | Audience category labels and related organic illustrations. |
| pricing pages | Active mulberry | `#7e0048` | `--color-toggle-active` | surface | Selected billing segment. |
| categorized actions and dark-stage artwork | Berry | `#741448` | `--color-berry` | action, accent | Enterprise and verification actions; richer organic shape on plum. |
| pricing pages | Table charcoal | `#333333` | `--color-table-ink` | text | Dense comparison cell values. |
| pricing pages | Price slate | `#6d7985` | `--color-price-muted` | text | Currency prefixes and entry price; rgba(47,64,80,0.7) on white. |
| light-page introductions | Soft slate | `#7d8790` | `--color-lead-muted` | text | Centered introductory copy; visible result of rgba(69,83,96,0.7) on white. |
| pricing pages | Comparison gray | `#d1d3d4` | `--color-comparison-rule` | border, accent | Dashed feature underlines and unavailable-feature dashes. |
| pricing pages | Control gray | `#ebecec` | `--color-control-track` | surface | Billing toggle track. |
| trust and customer-story pages | Cool gray wash | `#f8f9f9` | `--color-wash` | background | Long-form reading and story-library backing. |
| provider signup | Provider blue | `#4285f4` | `--color-provider-blue` | action, border | Third-party identity-provider signup only. |

## Typography

- **whitney** — Body, navigation, actions, small labels and supporting copy. Friendly humanist sans with narrow, open letterforms; conversational rather than geometric. If unavailable, use **Source Sans 3**. Use 400, 500 and 600; preserve the generous line spacing. Font stack: "whitney", "Source Sans 3", system-ui, helvetica, sans-serif.
- **sentinel** — Promises, section headings, editorial card titles and prices. Sturdy, bracketed slab serif; literary but not delicate or high-contrast. If unavailable, use **Bitter**. Use light to semibold cuts; tune line breaks to the text column. Font stack: "sentinel", "Bitter", georgia, serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | sentinel | 400 | 53px | 1.14286 | -0.0189em | Default white landing-page promise on plum. |
| heading | sentinel | 400 | 42px | 1.2381 | normal | Feature benefit, closing prompt, featured customer and FAQ heading. |
| lead | whitney | 400 | 24px | 1.5 | normal | Opening support and audience chapter introductions. |
| feature-label | whitney | 600 | 24px | 1.5 | normal | Icon-adjacent capability names and trust overview titles. |
| body | whitney | 400 | 20px | 1.6 | normal | Default prose and navigation links. |
| strong | whitney | 600 | 20px | 1.6 | normal | Login, read-story actions, question labels and compact subheadings. |
| button | whitney | 600 | 18px | 1.33333 | normal | Default conversion and category action. |
| caption | whitney | 500 | 16px | 1.75 | normal | Small signup reassurance and utility captions. |
| eyebrow | whitney | 600 | 12px | 1.66667 | 0.167em, uppercase | Footer column headings and story categories. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| pricing pages | price | sentinel | 600 | 75px | 64px | -0.02em | Colored plan amount. |
| pricing, trust, audience and story-library pages | light-page-title | sentinel | 300 | 72px | 1 | -0.0208em | Centered title above a light introduction. |
| audience pages | chapter-title | sentinel | 400 | 56px | 1.14286 | -0.0179em | Named audience chapter. |
| pricing pages | custom-price | sentinel | 600 | 37px | 64px | -0.027em | Word replacing the numeric enterprise amount. |
| audience pages | chapter-statement | whitney | 400 | 32px | 1.5 | normal | Broad concluding audience statement. |
| customer-story libraries | story-title | sentinel | 400 | 28px | 1.28571 | normal | Multi-line editorial headline inside a story card. |
| pricing pages | currency | sentinel | 600 | 28px | 1 | normal | Small raised prefix to price. |
| light-page introductions | light-page-lead | whitney | 400 | 24px | 1.66667 | normal | Muted centered description, generally within 580px. |
| featured customer stories | featured-eyebrow | whitney | 500 | 18px | 1.66667 | 0.111em, uppercase | Featured story overline. |
| pricing and trust pages | small-prose | whitney | 500 | 18px | 1.66667 | normal | FAQ answers and trust overview details. |
| audience pages | category-label | whitney | 600 | 18px | 1.66667 | normal | Colored audience navigation card label. |
| pricing pages | comparison-value | whitney | 500 | 16px | 50px | normal | Centered values in 52px comparison rows. |
| compact navigation | compact-button | whitney | 600 | 16px | 1.5 | normal | Compact signup in the light or scrolled navigation. |
| pricing pages | billing-label | whitney | 600 | 16px | 1.75 | normal | Billing-period segments. |

**Notes:**

- Serif is reserved for benefits and editorial hierarchy; sans carries practical explanation and controls.
- Tracking tightens only on larger serif titles and prices. Body and most section headings keep normal tracking.
- The default opening headline is smaller than the 72px light-page title; do not average these distinct treatments.
- No fluid type formula is specified; keep these desktop recipes together when adapting widths.

## Layout

**Density:** Airy: long editorial rows, roomy prose leading and substantial separation between illustrated ideas; dense comparisons are a scoped exception.

### Spacing

**Spacing system:**

- **grid** 8px — Dominant layout rhythm; preserve documented exceptions such as 100px feature gaps and 110px footer padding.

| Value | Use |
| --- | --- |
| 8px | Email-to-button gap. |
| 16px | Navigation item padding and audience-card grid gaps. |
| 24px | Label-to-benefit spacing and story-grid gaps. |
| 32px | Heading-to-description separation and footer heading-to-list spacing. |
| 40px | Container side padding, footer column gaps and expanded navigation vertical padding. |
| 48px | FAQ item separation. |
| 56px | Featured story inner padding. |
| 64px | Trust reading-area top and bottom padding. |
| 80px | Audience chapter padding and transition to first feature row. |
| 100px | Feature columns and separation between feature rows. |
| 110px | Footer top and bottom padding. |

### Containers and grids

- **page-container**: max width 1280px · side padding 40px. Centered outer container yielding 1200px of content and 120px viewport margins at 1440px.
- **feature-row**: 2 columns · gap 100px. Equal 550px media and content tracks; prose itself is limited to 496px. Alternate media side.
- **signup**: max width 460px · gap 8px. Provider signup spans the width; email and coral action share the next row.
- **footer-grid**: 5 columns · gap 40px. Five 208px link columns across the shared content width.
- **intro-copy** (only for light-page introductions): max width 580px. Centered explanatory text on light page types.
- **story-grid** (only for customer-story libraries): 3 columns · gap 24px. 384px-wide equal-height editorial cards within 1200px.
- **audience-grid** (only for audience pages): 4 columns · gap 16px. Four 288px category navigation cards.
- **trust-reading** (only for trust pages): max width 496px · gap 40px. Reading column alongside a 390px sticky contents panel.
- **comparison** (only for pricing pages): 5 columns · gap 16px. A feature-name column and four plan columns; cells approximately 221px wide.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | buttons-inputs-panels | 6px |
| pricing pages | billing-toggle | 18px |
| provider signup | provider-button | 2px |

## Surfaces and depth

### Shadows

| Only for | Name | Value | Use |
| --- | --- | --- | --- |
|  | paper-edge | `rgba(0, 0, 0, 0.1) 0px 0px 0px 1px` | Input wrapper edge. |
| audience and trust pages | inset-edge | `rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset` | Audience navigation cards and trust contents panel. |
| customer-story libraries | story-card | `rgba(24, 59, 59, 0.06) 0px 7px 26px 1px` | Diffuse cool lift under white editorial cards. |

### Surfaces

#### Paper canvas · level 0

**Use:** Default content background.

**CSS:** `background: #ffffff; color: #455360`

**Observed:** Most of the body remains unboxed and white.

**Transfer:** Let type and illustrations organize the page before adding cards.

#### Plum stage · level 0

**Use:** Primary marketing opening.

**CSS:** `background: #42022e; color: #ffffff`

**Observed:** Navigation, hero and logo strip form one continuous dark field.

**Transfer:** Concentrate the dark treatment at the opening rather than turning the entire page dark.

#### Orbital band · level 0

**Use:** Reassuring conversion scene.

**CSS:** `background: #fcfcfd; border-top: 1px solid rgba(0, 0, 0, 0.1); overflow: hidden`

**Observed:** Fine orbital artwork is clipped by the 489px band.

**Transfer:** Keep the center uncluttered and place labels out along the rings.

#### Reading wash · level 0

**Only for:** trust and customer-story pages

**Use:** Long reading or repeated-story area.

**CSS:** `background: #f8f9f9`

**Observed:** A neutral backing supports white cards or an unboxed reading column.

**Transfer:** Use one continuous gray field, not alternating gray stripes.

#### Outlined paper · level 1

**Only for:** trust and audience pages

**Use:** Contents and category navigation panels.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset`

#### Editorial card · level 1

**Only for:** customer-story libraries

**Use:** Story-library entries.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: rgba(24, 59, 59, 0.06) 0px 7px 26px 1px; overflow: hidden`

#### Enterprise column · level 1

**Only for:** pricing pages

**Use:** Sales-led plan contrast.

**CSS:** `background: #42022e; color: #ffffff; border-left: 1px solid #42022e; border-right: 1px solid #42022e`

**Observed:** Dark fill runs continuously through the comparison rows; berry action sits within it.

**Transfer:** Give the whole column continuity, not just its header.

## Components

### Navigation

**Use:** Shared desktop navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding-top: 40px; padding-bottom: 40px`

**Text style:** `body` — whitney 400 · 20px/1.6

**Observed:** Small handwritten-style logo at left, four plain links beside it, login with cyan arrow at far right. Default opening is reversed on plum; light and scrolled variants use slate links and an inline compact email signup. Scrolled navigation is visibly slimmer than the expanded opening.

**Transfer:** Use the new product's own modest wordmark, not a giant display logo.

### Primary button

**Use:** Default conversion action.

**CSS:** `background: #ff4143; color: #ffffff; border-radius: 6px; padding: 16px 24px; height: 56px`

**Text style:** `button` — whitney 600 · 18px/1.33333

**Observed:** No trailing icon. Compact navigation uses 8px 16px padding, 40px height and compact-button type. Categorized trust and pricing actions use yellow, cyan or berry; the entry pricing action uses deep slate.

**States:** Declared: hover background #ff5052; focus-visible unknown; active background #ff4143.

**Transfer:** Keep coral as the general conversion default; reserve category colors for a coherent comparison or category set.

### Email field

**Use:** Inline signup in the opening.

**CSS:** `background: #ffffff; border-radius: 6px; padding: 0px 12px; height: 56px; width: 316px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px`

**Observed:** Field followed by Primary button with 8px gap; reassurance beneath. Compact navigation reduces the field to 183×40px. Field text recipe is not specified.

**Transfer:** Use one work-email field rather than a multi-field contact form.

### Arrow link

**Use:** Editorial read-through and login.

**CSS:** `color: #455360; display: inline-flex; align-items: center`

**Text style:** `strong` — whitney 600 · 20px/1.6

**Observed:** Semibold text followed by a small cyan right arrow. The arrow is an accent, not a circular button.

**Transfer:** Use a short verb-object label for secondary destinations.

### Footer

**Use:** Shared final navigation and legal ending.

**CSS:** `background: #ffffff; border-top: 1px solid rgba(0, 0, 0, 0.1); padding: 110px 0px`

**Text style:** `body` — whitney 400 · 20px/1.6

**Observed:** Five columns with eyebrow headings, 32px separation before link lists, 40px column gaps and roughly 48px link rhythm. Bottom row has a small coral wordmark at left and muted legal links at right. Informational pages finish here without an added conversion band.

**Transfer:** Adapt column topics to the new product while preserving the roomy directory-like ending.

### Story card

**Only for:** customer-story libraries

**Use:** Clickable customer proof entry.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: rgba(24, 59, 59, 0.06) 0px 7px 26px 1px; display: flex; flex-direction: column; overflow: hidden`

**Text style:** `story-title` — sentinel 400 · 28px/1.28571

**Observed:** Full-width cover image, small company logo, serif title, tracked uppercase industry label, then Arrow link anchored toward the bottom. Typical card is 384×510px; content uses 32px vertical and 40px horizontal padding; first-row covers are 384×200px.

**Transfer:** Preserve equal card heights despite different title lengths.

### Featured story

**Only for:** featured customer stories

**Use:** Lead proof module beneath a centered introduction.

**CSS:** `background: #ffffff; padding: 56px; border-top: 1px solid rgba(0, 0, 0, 0.1); border-right: 1px solid rgba(0, 0, 0, 0.1); border-bottom: 1px solid rgba(0, 0, 0, 0.1); border-radius: 0px 6px 6px 0px`

**Text style:** `heading` — sentinel 400 · 42px/1.2381

**Observed:** Text panel is one half of a 966×460px split card: photograph left, eyebrow, title, paragraph and Arrow link right. Pale yellow organic artwork and a plum contour extend behind the photograph.

**Transfer:** Use a real workplace or product-in-context photo, not an abstract testimonial quotation.

### Contents panel

**Only for:** trust pages

**Use:** Sticky table of contents for substantial prose.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset; overflow: hidden`

**Text style:** `small-prose` — whitney 500 · 18px/1.66667

**Observed:** A 390px-wide panel is grouped into three colored parent headings with indented gray subsection links. The active subsection is dark with a small bullet. A tracked uppercase overline labels the whole panel.

**Transfer:** Use real anchor links tied to the adjacent reading column.

### Audience card

**Only for:** audience pages

**Use:** Illustrated chapter jump.

**CSS:** `background: #ffffff; border-radius: 6px; box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 1px inset; overflow: hidden`

**Text style:** `category-label` — whitney 600 · 18px/1.66667

**Observed:** Centered colored title above a bottom-aligned laptop-user illustration on a pastel mound. Four equal cards act as an index into the chapters.

**Transfer:** Reuse each category's color in its chapter illustration.

### Billing switch

**Only for:** pricing pages

**Use:** Compare billing periods.

**CSS:** `background: #ebecec; border-radius: 18px; display: inline-flex; align-items: center; position: relative; height: 36px; width: 182px`

**Text style:** `billing-label` — whitney 600 · 16px/1.75

**Observed:** Selected mulberry capsule moves behind white semibold text; unselected text is dark. Each label has 4px 16px padding.

**Transfer:** Keep this pill treatment exclusive to a binary segmented control, not general buttons.

### Comparison cell

**Only for:** pricing pages

**Use:** Plan-by-feature matrix.

**CSS:** `background: #ffffff; border-left: 1px solid rgba(0, 0, 0, 0.1); border-right: 1px solid rgba(0, 0, 0, 0.1); padding: 1px; height: 52px; text-align: center; color: #333333`

**Text style:** `comparison-value` — whitney 500 · 16px/50px

**Observed:** Quiet vertical edges join each plan into a continuous column. Feature-name column is on the gray backing. Colored outlined check circles and gray dashes replace values when appropriate; dark plan reverses text. Actions repeat below the final feature group.

**Transfer:** Group features with small uppercase labels and horizontal hairlines rather than making every row a separate card.

## Imagery and graphics

### Organic interface cutouts

**Use:** Hero and alternating capability explanations.

**Observed:** White browser or document panels with very light rules, gray text bars, a few colored highlights and tiny avatars. Hero scene is 872×650px and exits the viewport at right; body illustrations are about 550px wide. Behind them are asymmetric pastel shapes and a single fine colored loop; cyan, yellow, pink and mint rotate by capability.

**Transfer:** Rebuild the new product's key workflow with a credible title, navigation and a few meaningful controls. Minimum acceptable media is a simplified white workflow panel with readable labels and restrained highlight marks, not a blank card.

**Build:** Use an SVG viewBox of 0 0 550 480. Draw one closed asymmetric cubic-Bezier blob across about 470×400px, filled with cyan, yellow, coral or mint at 0.16–0.22 opacity over white. Add a separate offset open looping path with 1–2px stroke in the related saturated hue and no fill. Place the white interface panel in front, inset about 30px, with a 1px black-at-0.06 outline. On plum, use a berry blob and yellow loop; keep edges crisp, with no blur or 3D extrusion.

### Orbital reassurance artwork

**Use:** Signature landing-page conversion scene.

**Observed:** Three delicate, very large incomplete concentric rings curve around a clear centered title and action. Small outlined nodes interrupt the rings next to tool labels. Artwork occupies roughly 1095×489px and is clipped at top and bottom.

**Transfer:** Replace tool labels with the new product's connected workflows or migration sources. If those do not exist, use short customer-task labels around the rings; retain the orbital structure.

**Build:** Create a 1095×489px SVG with three concentric circles centered near the top middle, with radii about 200px, 360px and 545px. Use 1px gray strokes at low opacity, then overlay short cyan, mint and coral arc segments at similarly faint opacity. Put 4–8px hollow nodes on a few arcs and short labels outside them. Clip the SVG to the band; leave the central headline and button unobstructed.

### Customer logo strip

**Use:** Proof at the base of the dark opening.

**Observed:** A single low horizontal line of pale or white customer marks, varied intrinsic widths and consistent optical height. Plum fades conceal the strip's edges.

**Transfer:** Use permissioned customer marks in one pale tone; if unavailable, use brief factual proof labels in the same restrained strip.

### Audience characters

**Only for:** audience pages

**Use:** Chapter index and large chapter illustrations.

**Observed:** Flat friendly people using laptops, drawn in plum outlines with white skin, solid colorful shirts and stylized hair. Each sits over a pale irregular blob keyed to the category; no realistic lighting, texture or volume.

**Transfer:** Draw simple half-length figures or task-related line objects with one solid accent fill; keep the generous pastel backing rather than substituting generic 3D avatars.

**Build:** Use an SVG around 560×473px: one irregular pastel blob, then a plum-outlined laptop and half-length figure with 2px strokes, white face and one saturated shirt color. Use rounded cubic curves for hair and body; avoid gradients and cast shadows.

### Customer photography

**Only for:** customer-story libraries and featured customer stories

**Use:** Human proof and editorial covers.

**Observed:** Natural-color office scenes, teams, architecture, products and customer-provided graphic covers coexist. Photos are rectangular, edge-to-edge within cards, with no universal duotone filter. Featured photography is large and nearly square; grid covers are shallow landscape crops.

**Transfer:** Use real subject-specific images and allow their authentic colors; unify through framing, title structure and the white card rather than forcing a monochrome treatment.

### Icons

**Observed:** Small capability symbols are colored outline drawings around 38–46px. Trust overview icons are around 62–72px with pale organic backing. Pricing checks use 38px SVG boxes, 2px strokes and circular outlines; text-link arrows are cyan.

**Transfer:** Choose thin, open line symbols matched to the adjacent category color. Do not place them inside heavy filled square badges.

## Section recipes

How recurring sections are built.

### First screen: Split plum opening

**Observed:** A continuous Plum stage begins behind the 131px expanded Navigation. Left-aligned display sits in a roughly 560px text column near the content margin, wrapping into two lines. A 24px support paragraph follows with breathing room, then a 460px signup group: provider action, a ruled 'or' divider, Email field and Primary button, then small reassurance. To the right, a large white interface scene sits over berry organic art and a yellow contour loop; the scene is about 872×650px and extends beyond the right viewport edge. Within the first 900px, navigation, promise, support, signup, main interface and a low pale logo strip are visible. The first alternating capability row begins below the fold.

**Transfer:** Use a short outcome promise and one convincing product workflow. Without mature interface media, build Organic interface cutouts using the new product's actual task and keep the oversized right-hand bleed. Pricing, trust, audience and proof-library pages instead open on white with a centered light-page-title, a muted lead 32px below, and relevant comparison, category or proof content.

**Avoid:** Do not center the default hero, shrink its interface into a small contained card, or replace the dark field with a generic gradient.

**Text style:** `display` — sentinel 400 · 53px/1.14286 · tracking -0.0189em

### Alternating capability row

**Observed:** Feature-row layout alternates a 550px illustration and a 496px prose block, vertically centered across a 100px gap. A colored outline icon sits beside feature-label text; heading follows 24px below and body follows 32px below that. Rows are separated by about 100px on white.

**Transfer:** Tell one concrete benefit per row; reuse Organic interface cutouts instead of introducing a new visual language for every feature.

**Text style:** `heading` — sentinel 400 · 42px/1.2381

### Centered light introduction

**Observed:** On white, a 72px light-page-title begins 40px beneath Navigation; light-page-lead follows 32px below within a 580px centered measure. Below it, distinct page-specific modules take over rather than repeating the dark marketing stage.

**Transfer:** Use for task-focused secondary pages with a short descriptive title and one reassuring explanatory line.

**Text style:** `light-page-title` — sentinel 300 · 72px/1 · tracking -0.0208em

### Audience chapters

**Observed:** Audience card index leads to spacious chapters padded 80px vertically. Alternate full-width two-column introductions plus three prose columns with narrower illustration-side layouts plus two prose columns. Chapter-title is 56px; supporting lead is 24px, with strong subheads and 20px body. Final broad audience chapter uses a 32px statement before the shared Footer.

**Transfer:** Organize by reader job or context, keeping the colored illustration linkage and varied chapter proportions.

**Text style:** `chapter-title` — sentinel 400 · 56px/1.14286 · tracking -0.0179em

### Trust overview and reading

**Observed:** Three centered icon-led columns introduce topic groups with feature-label titles, small-prose descriptions and colored actions. Reading wash then holds Contents panel on the left and 496px prose on the right. Serif 42px group headings, colored icons, bold 20px subsection labels and generously separated paragraphs give the long document hierarchy. Verification badges appear within the relevant text; the final disclosure paragraph leads directly to Footer.

**Transfer:** Use this for policies or technical reassurance; support every badge and assurance with actual product facts.

**Text style:** `heading` — sentinel 400 · 42px/1.2381

### Plan comparison

**Observed:** A label column and four plan columns follow the centered introduction. Headers have small organic caps, 75px colored serif prices and small currency prefixes. The sales-led column stays plum from header through all comparison rows; other columns stay white over a gray table backing. Billing switch sits in the label area. Grouped feature rows end with repeated plan actions.

**Transfer:** Keep category colors consistent among price, check marks and action. Use the dark column to distinguish a genuinely different purchasing path.

**Text style:** `price` — sentinel 600 · 75px/64px · tracking -0.02em

### Editorial proof library

**Observed:** Featured story follows a centered introduction, with pale organic backing and a split photo/text composition. Reading wash then introduces a centered 42px library heading and a short support line before a three-column Story card grid with 24px gutters. The final partial row is left-aligned; the section ends with gray breathing room and Footer, not a fabricated closing CTA.

**Transfer:** Lead with one strong case study, then let a consistent editorial grid carry breadth of proof.

**Text style:** `story-title` — sentinel 400 · 28px/1.28571

### Open FAQ

**Observed:** Two broad columns: a sticky 42px heading and short contact links left, six always-visible question-and-answer groups right. Questions use strong type; answers use small-prose, separated by 48px. Cyan underlined contact links provide a modest escape hatch. Footer follows the final answer.

**Transfer:** Use clear prose answers, not accordion chrome; let the left heading remain a stable landmark.

**Text style:** `heading` — sentinel 400 · 42px/1.2381

### Orbital closing call

**Observed:** Orbital band combines centered 42px serif prompt, muted 24px reassurance and Primary button. Orbital reassurance artwork surrounds this compact stack without obscuring it; Footer follows immediately.

**Transfer:** Use a low-anxiety final prompt tied to switching, onboarding or the next step. Preserve the orbit as a distinctive conversion device even when its labels change.

**Text style:** `heading` — sentinel 400 · 42px/1.2381

## Page flow

**Storyline:** Promise → tangible product or category orientation → benefits and substantiation → practical reassurance → appropriate ending and shared directory.

### Product landing narrative

1. **Promise and product demonstration** — Split plum opening with signup, oversized interface and pale logo strip.
2. **Capability chapters** — Alternating white-space-rich illustration and benefit rows.
3. **Closing call** — Orbital reassurance with a centered coral action.
4. **Directory** — Five-column Footer and small legal row.

**Transfer:** Choose benefits that tell a coherent product story; preserve the organic illustration and orbital conversion devices without requiring a fixed number of rows.

### Technical trust and reassurance

1. **Orientation** — Centered light title and short reassurance.
2. **Category overview** — Three illustrated topic summaries and colored actions.
3. **Substantiation** — Gray reading band, sticky contents and detailed prose with verification marks.
4. **Directory** — Final disclosure/contact text transitions directly to Footer.

**Transfer:** Use a compact overview to make long technical material approachable before exposing details.

### Plan selection and purchase objections

1. **Promise** — Centered title and low-risk support line.
2. **Pricing** — Billing switch and tall four-plan comparison with a feature-label column.
3. **Decision support** — Repeated plan actions at table bottom.
4. **Objection handling** — Open FAQ with sticky heading and contact links.
5. **Directory** — Footer after the final answer.

**Transfer:** Let one continuous comparison do the heavy lifting; avoid inserting unrelated marketing blocks into the matrix.

### Help different audiences recognize their fit

1. **Orientation** — Centered title and four illustrated audience jump cards.
2. **Capability chapters** — Alternating figure-led chapters with two or three supporting prose columns.
3. **Broad applicability** — Final general-audience chapter with larger sans statement.
4. **Directory** — Whitespace leads to Footer without a separate signup band.

**Transfer:** Make each chapter speak to a distinct job while keeping one visual family.

### Establish breadth and credibility of adoption

1. **Social proof promise** — Centered headline with factual adoption support.
2. **Featured proof** — Large split photographic story over organic artwork.
3. **Proof library** — Gray-backed three-column editorial card grid.
4. **Directory** — Partial final row and gray breathing room lead directly to Footer.

**Transfer:** Use authentic customer stories and a consistent editorial container, not a wall of identical quotes.

## Writing

Warm, practical and quietly confident. Benefits are explained in everyday team language, with enough concrete detail to make the promise credible and occasional conversational turns to lower anxiety.

**Do not copy:** Do not reuse Slab's name, wordmark, customer logos, proprietary illustrations, customer story titles, adoption counts, prices, compliance claims or promises. Source examples illustrate the voice only; substitute verified facts and original copy for the new product.

- **Addressing the reader:** Speak directly to 'you' and 'your team'; use 'we' when taking responsibility for assistance. Product references are straightforward rather than personified.
- **Rhythm:** Short outcome-led headings contrast with explanatory paragraphs of two or three sentences. Functional action labels are brief and title-cased; occasional question headings and contractions keep the page conversational.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Opening promise | An active invitation to a better working habit, not a category label. | 6–10 words | “Build a culture of knowledge-sharing today.” |
| Benefit heading | Name the practical improvement; conversational negatives can clarify a differentiator. | 5–11 words | “Create content that looks good by default.”<br>“Not yet another place to search.” |
| Supporting line | Explain what becomes easy and who benefits. | One or two short sentences | “Easily create, organize, and discover knowledge for your entire organization, from non-technical to tech-savvy.” |
| Action | Direct next step without hype. | 2–3 words | “Get Started”<br>“Learn More”<br>“Read story” |
| Reassurance | Acknowledge a concern, then make the next step feel manageable. | One short prompt and response | “Switching?”<br>“We’ll take care of that for you”<br>“Use [Brand] free forever. No credit card required.” |
| Story headline | How a specific organization achieves a specific operational result. | 8–13 words | “How Karat Stays Secure and Compliant with [Brand]” |

**Words and phrasing to use:** your team; looks good by default; easy; discover; share; learn; pure and simple; we’ll take care of that

**Avoid:** revolutionary; 10x everything; AI-powered magic; disrupt the future; enterprise-grade synergy

**Rules:**

- Lead with a human work outcome, then explain the mechanism in prose.
- Use concrete examples of tasks to substantiate broad benefits.
- Use contractions and a restrained conversational aside without making every headline a joke.
- Keep category names short enough to work beside a small icon.
- Make pricing and trust reassurance factual; avoid absolute assurances unsupported by the new product.

## Do's and Don'ts

### Do

- Keep default serif headings regular: 42px/52px, not semibold sans.
- Preserve the 53px plum-stage promise as a distinct role from the 72px light-page title.
- Use 6px corners on actions, fields and cards.
- Limit capability prose to about 496px and pair it with roughly 550px media.
- Use 100px feature gaps and 80px chapter padding to maintain the airy rhythm.
- Keep cyan arrows small beside 20px semibold text links.
- Use 24px gutters for three-column editorial cards and 16px for four audience cards.
- Give the Footer 110px vertical padding and a single faint top rule.

### Don't

- Do not make all actions pill-shaped; 18px capsules belong to the billing switch.
- Do not fill the long body with alternating saturated brand-color bands; its default is white.
- Do not replace flat organic media backing with blurred neon glows or glass panels.
- Do not impose a uniform heavy shadow on every interface illustration; outlines and pale backing do most of the work.
- Do not turn 20px/32px prose into tiny dense marketing copy.
- Do not use tracked uppercase for benefit headlines; reserve it for small labels.
- Do not break the dark comparison plan into disconnected floating tiles.
- Do not append the orbital signup band to every secondary page; their content-specific endings flow directly into the shared Footer.

## Motion and responsive

### Motion

**Observed:**

- Declared: story-card opacity transitions use 0.25s linear; outlined panels and inputs use box-shadow 0.2s; feature underlines use border-bottom-color 0.2s.
- Declared: billing selection moves left and width over 0.2s ease-out; provider action uses background-color 0.2s.
- The navigation changes to a slim white signup strip in scrolled views.

**Transfer:**

- Keep feedback on the paper edges and small controls; the organic illustration language does not require animated blobs.
- Treat the orbital composition as a complete static design; movement is not necessary to communicate its structure.

**Unknown:**

- Continuous orbit movement, scroll choreography and their timings are not established.
- Focus-visible appearances are not established.

### Responsive

**Observed:**

- Width breakpoints include 480px, 700px, 768px, 960px, 1024px and 1280px; exact mobile compositions are unspecified.

**Transfer:**

- For narrow layouts, stack the plum text and organic interface scene while keeping a substantial product object rather than reducing it to an icon.
- Reduce multi-column card and footer grids as space requires; keep serif/sans roles and category-color linkage.
- For long-form trust content, place chapter navigation before the reading column; for comparisons, retain clear plan-to-feature association rather than shrinking text below its utility size.

**Unknown:**

- Mobile typography, menu behavior, comparison overflow behavior and exact breakpoint-to-layout mappings are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
