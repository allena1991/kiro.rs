# Artboard Studio — pastel stages, electric details

## Overview

A light, image-led style for creative tools and products whose results deserve to be shown. Dense, rounded sans-serif headlines and practical system-sans copy sit on a faint green-to-stone canvas, while large pastel stages hold realistic photography, rendered objects and interface demonstrations. Electric lime is a small but memorable punctuation mark; the overall feeling is capable, approachable and visually abundant rather than luxurious or technical.

### Essentials

- Headlines feel compressed and substantial, not monumental: Vend Sans at 60.8px/1.2 with -2px tracking, weight 600 with a 700 opening phrase; feature headings use 43.2px/1.2, 700, -1px.
- The opening is a centered promise above a browsable image collection: 768px headline width, 600px support width, a 24px text gap, then 200×50px rectangular tabs and a three-column preview grid entering the first screen.
- Color belongs to stages, not paragraphs: the continuous canvas shifts from #f9ffeb to #f4f3f2, while 814px square blue, green or lavender media panels occupy roughly three fifths of feature rows. Lime #aaff00 stays concentrated in small identity details and selected conversion accents.
- Controls are compact soft rectangles rather than pills: 8px radii, dark #0d1400 primary buttons at 42px high, and white outlined category controls at 50px high.
- Image abundance is organized into contact sheets and collages: four square previews within a white 12px-radius card, or a 2×2 group with 16px gaps on a broad pastel stage. Every new page needs an equivalent visual proof collection; use four distinct real outcomes or concrete workflow views when physical imagery is unavailable.
- The ending stays useful rather than theatrical: a white FAQ panel with two columns, a centered 32px help prompt and compact contact action, followed by a spacious four-column directory with 48px gutters and a small copyright/chat baseline.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Electric lime | `#aaff00` | `--color-lime` | accent, action | Small identity tile; on catalog pages also the main conversion button and free-item badges. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Lime rim | `#dfff9f` | `--color-lime-edge` | border | Subtle light border around the lime identity tile. |
| Soft green | `#caf3aa` | `--color-stage-green` | surface | Large stages around square imagery and four-up demonstrations. |
| Powder blue | `#cbedff` | `--color-stage-blue` | surface | Large demonstration stages. |
| Lavender | `#e2c9f5` | `--color-stage-lavender` | surface | Collaged outcomes and transformation artwork. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Olive black | `#0d1400` | `--color-ink` | text, action, border | Default text, selected category backgrounds and primary actions. |
| Secondary black | `#222222` | `--color-secondary-ink` | text, surface | Small proof labels and declared dark hover backgrounds. |
| Charcoal stage | `#444444` | `--color-stage-charcoal` | surface | Dark backing behind a tall, floating tool demonstration. |
| Soft olive edge | `#e7e8e6` | `--color-edge` | border | Visible hairline from 10% olive-black over white; exact construction uses rgba(13,20,0,0.1). |
| Faint media edge | `#f2f2f2` | `--color-media-edge` | border | Visible 5% black edge on white image tiles. |
| Warm stone | `#f4f3f2` | `--color-canvas` | background | Broad central canvas and catalog background. |
| Pale citron | `#f9ffeb` | `--color-canvas-tint` | background | Very light green at the beginning and end of the continuous canvas gradient. |
| White | `#ffffff` | `--color-white` | surface, text, background | Cards, FAQ panels, footer and reversed action text. |

### Page-type variants

| Only for | Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- | --- |
| integration landing pages | Peach | `#ffe4c3` | `--color-stage-peach` | surface | Fresh-content contact sheets. |
| social proof bands | Sage gray | `#838976` | `--color-muted` | text | Trust statement and monochrome customer marks. |

## Typography

- **Vend Sans** — Headlines, feature titles, questions and proof labels. Dense, friendly sans serif with rounded forms and strong, compact bold cuts. If unavailable, use **Inter Tight**. Use 500–700 weights and preserve the tight headline tracking. Font stack: "Vend Sans", "Inter Tight", sans-serif.
- **system-ui** — Paragraphs, navigation, footer links and buttons. Unembellished operating-system sans serif; regular text contrasts with the heavier display face. Font stack: "system-ui", -apple-system, "Segoe UI", Roboto, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| display | Vend Sans | 600 | 60.8px | 1.2 | -0.0329em | Centered primary promise. |
| display-emphasis | Vend Sans | 700 | 60.8px | 1.2 | -0.0329em | Opening product noun within the primary promise; also full integration headlines. |
| section-heading | Vend Sans | 700 | 48px | 1.2 | normal | FAQ and instructional panel headings. |
| feature-heading | Vend Sans | 700 | 43.2px | 1.2 | -0.0231em | Short feature headings in narrow copy columns. |
| help-heading | Vend Sans | 700 | 32px | 1.3 | normal | Centered help prompt before the final contact action. |
| question | Vend Sans | 500 | 24px | 1.2 | normal | Marketing FAQ accordion questions. |
| card-title | Vend Sans | 600 | 19.2px | 1.2 | normal | Single-line category captions below image collections. |
| body | system-ui | 400 | 16px | 1.5 | normal | Paragraphs, lists and category tab labels. |
| action | system-ui | 400 | 16px | 1.5 | 0.031em | Dark primary button labels. |
| link | system-ui | 400 | 16px | 1 | normal | Navigation and directory links. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| catalog pages | catalog-display | Vend Sans | 700 | 56px | 1.2 | normal | Left-aligned headline above the searchable collection. |
| social proof bands | trust | Vend Sans | 600 | 24px | 1.5 | normal | Centered muted statement above customer marks. |
| catalog and integration pages | instruction-title | Vend Sans | 600 | 19.2px | 1.3 | normal | Step titles and compact FAQ questions. |
| integration landing pages | proof-label | Vend Sans | 400 | 11.2px | 1.5 | 0.045em, uppercase | Icon-led miniature proof strip and new-content markers. |

**Notes:**

- Keep heading and paragraph families distinct; do not set the whole page in the display face.
- Only the largest headlines tighten to -2px. Feature titles use -1px; ordinary section headings, questions and card captions retain normal tracking.
- Feature titles can wrap to three or four lines within 460px. Body text stays 16px rather than growing to match the oversized media.

## Layout

**Density:** Airy at section scale, compact within image collections and controls.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Button icon gaps and tight tile gutters. |
| 12px | Directory link gaps and category caption inset. |
| 16px | Four-up and nine-up media gutters. |
| 24px | Headline-to-copy gaps, category grid gutters and navigation gaps. |
| 48px | Feature column gap, feature vertical padding and footer gutters. |
| 64px | FAQ column gap. |
| 80px | Large help-prompt separation and collection opening space. |
| 96px | Space above the opening text block after navigation. |
| 100px | Inset around square media on the green stage. |
| 112px | White instructional and FAQ panel vertical padding. |

### Containers and grids

- **wide-content**: max width 1346px · side padding 12px. Centered collection and feature-row container; at desktop its inner content spans about 1322px.
- **hero-copy**: max width 768px. Centered headline block; supporting paragraph narrows to 600px.
- **feature-copy**: max width 460px · gap 24px. Vertically centered copy column alongside an 814px square media stage; separate columns by 48px.
- **category-grid**: 3 columns · gap 24px. White category cards, each holding a 2×2 preview sheet.
- **faq-grid**: 2 columns · gap 64px. Two equal question columns inside white panels.
- **directory**: 4 columns · gap 48px · side padding 48px. Full-width directory; four 300px columns at desktop.
- **catalog-shell** (only for catalog pages): 3 columns · gap 16px · side padding 30px. A 350px white persistent left sidebar with the searchable grid and all subsequent content offset to its right.

## Corner radius

| Element | Radius |
| --- | --- |
| controls-and-images | 8px |
| cards-and-stages | 12px |

## Surfaces and depth

### Surfaces

#### Continuous canvas · level 0

**Use:** Default marketing page background.

**CSS:** `background: linear-gradient(#f9ffeb, #f4f3f2 20%, #f4f3f2 70%, #f9ffeb)`

**Observed:** A barely colored field that connects the whole page, rather than a separate gradient for every section.

**Transfer:** Let white cards and pastel artwork provide the stronger surface changes.

#### White collection card · level 1

**Use:** Category preview groups and catalog items.

**CSS:** `background: #ffffff; border: 1px solid rgba(13,20,0,0.1); border-radius: 12px; box-shadow: none`

**Observed:** Thin outlined shell, with smaller rounded image tiles nested inside.

**Transfer:** Group concrete examples, not abstract feature blurbs.

#### Pastel stage · level 0

**Use:** Dominant image block in feature rows.

**CSS:** `background: #cbedff; border-radius: 12px; overflow: hidden`

**Observed:** 814px square default stage. Green uses a 100px inset, blue uses 20px; lavender carries a loose collage. Charcoal is the dark tool-demo variant.

**Transfer:** Keep the background flat and put dimensionality into the objects or interface artwork.

#### White information panel · level 0

**Use:** FAQ, instructions and closing support content.

**CSS:** `background: #ffffff; border-radius: 12px`

**Observed:** Broad panel with 112px vertical breathing room; the footer is also white but has square outer corners.

**Transfer:** Switch from visual selling to readable support without introducing a dark closing theme.

## Components

### Navigation

**Use:** Lightweight entry navigation.

**CSS:** `display: flex; justify-content: space-between; align-items: center; padding: 20px; max-width: 1140px; margin: 0 auto`

**Text style:** `link` — system-ui 400 · 16px/1

**Observed:** Small identity at left and spaced text links at right; blends into the canvas without a divider or shadow. Integration pages replace the link group with a dark install action.

### Identity tile

**Use:** Small bright visual anchor beside a compact wordmark.

**CSS:** `background: #aaff00; border: 1px solid #dfff9f; border-radius: 8px; width: 40px; height: 40px; padding: 4px; display: flex; align-items: center; justify-content: center`

**Observed:** A dark simple symbol inside a lime square; adjacent name uses a bold first part and regular second part.

**Transfer:** Use the new product's own simple symbol and name in this small-format construction.

### Primary button

**Use:** Install, contact and continuation actions.

**CSS:** `display: flex; align-items: center; justify-content: center; gap: 8px; padding: 8px 19.2px; height: 42px; background: #0d1400; color: #ffffff; border: 1px solid #0d1400; border-radius: 8px`

**Text style:** `action` — system-ui 400 · 16px/1.5 · tracking 0.031em

**Observed:** Content-sized with an optional leading icon; repeated at the help close rather than expanded into a giant banner action.

**States:** Declared: hover background #222222 and text #0d1400; focus-visible unspecified; active text #ffffff and outline 0px.

**Transfer:** Preserve the compact geometry; ensure readable text contrast when implementing the hover treatment.

### Category tab

**Use:** Horizontal filtering above visual collections.

**CSS:** `background: #ffffff; color: #0d1400; border: 1px solid rgba(13,20,0,0.1); border-radius: 8px; padding: 12px 24px; height: 50px; width: 200px`

**Text style:** `body` — system-ui 400 · 16px/1.5

**Observed:** Equal-width tabs, six across at desktop with 24px gaps. The selected tab reverses to olive-black with white text.

**States:** Declared: hover text #0d1400; focus-visible outline rgb(77,101,255) solid 2px with 2px offset; active text #ffffff and outline 0px.

### Category card

**Use:** Show a compact family of outcomes.

**CSS:** `display: flex; flex-direction: column; align-items: flex-start; background: #ffffff; border: 1px solid rgba(13,20,0,0.1); border-radius: 12px; padding-bottom: 12px`

**Text style:** `card-title` — Vend Sans 600 · 19.2px/1.2

**Observed:** Four square images in a close 2×2 sheet above a left-aligned caption inset 12px. Desktop shell is about 425×460px; image cells have 8px corners and faint outlines.

**Transfer:** Give each preview a meaningfully different view or result; preserve the contact-sheet logic.

### FAQ question

**Use:** Compact objection handling in two columns.

**CSS:** `display: flex; align-items: center; justify-content: space-between; gap: 24px; padding: 20px 0`

**Text style:** `question` — Vend Sans 500 · 24px/1.2

**Observed:** Question at left, small down-chevron at right; no heavy row container. Marketing and integration questions are collapsed by default. Catalog FAQs expose answers as static text.

### Directory link

**Use:** Footer navigation organized under category headings.

**CSS:** `display: flex; align-items: center; justify-content: center; padding: 4px 0; height: 42px; border-radius: 8px`

**Text style:** `link` — system-ui 400 · 16px/1

**Observed:** Individual links are content-sized and aligned to the left edge of their column; column groups use 12px gaps and bold system-sans headings.

**States:** Declared: hover text #aaa and background #222; focus-visible unspecified; active text #fff and outline 0px.

### Proof micro-label

**Only for:** integration landing pages

**Use:** Small proof strip above the opening headline.

**CSS:** `display: flex; align-items: center; gap: 4px; padding: 4px 8px 4px 0; border-radius: 8px`

**Text style:** `proof-label` — Vend Sans 400 · 11.2px/1.5 · tracking 0.045em · uppercase

**Observed:** Thin dark icon followed by uppercase text; four compact claims share a single centered strip, including one abbreviated audience count rather than a large stat card.

**Transfer:** Use truthful short capabilities and one verified quantity if available.

## Imagery and graphics

### Outcome contact sheets

**Use:** Opening proof collection and feature-stage grids.

**Observed:** Realistic devices, printed matter, apparel and packaging mix studio-lit isolated objects with hands and people. Individual images are square, often front-facing or three-quarter, with neutral white or gray backgrounds alternating with vivid colored scenes. Four previews form a category card; larger stages use four or nine cells.

**Transfer:** Use the new product's actual outputs or well-crafted sample deliverables. Minimum version: four clean, distinct outcome images with consistent square framing and a mixture of neutral and colorful backings.

**Build:** Create a 2×2 CSS grid with 8px gaps inside a white 12px-radius shell; use square image cells with 8px radii and 1px rgba(13,20,0,0.1) outlines. For a large green stage use 100px padding and a 2×2 grid with 16px gaps.

### Floating workflow collage

**Use:** Large feature-stage demonstrations.

**Observed:** A browser or plugin panel is surrounded by rounded outcome cards: a tall central image, angled devices above, smaller paper and package results overlapping below. White tile backings separate vivid lime artwork from a flat blue or lavender field. The media takes substantially more width than its accompanying copy.

**Transfer:** Show a real interface view with three to five resulting artifacts; for a nonvisual product, show concrete report, message or automation outputs rather than decorative empty windows.

**Build:** Use an 814px square, 12px-radius pastel parent. Place a tall interface panel across the left-center, then overlap three rounded white-backed outcome images across the middle and right, keeping an outer margin of about 24px. Use the product's own content, restrained rotations and no global drop-shadow treatment.

### Transformation stage

**Use:** Visual explanation of a generative or transformative capability.

**Observed:** Lavender square backing with a smaller clean input portrait at left, a much larger contextual output at upper right, and a low white prompt/settings strip beneath. The output has darker cinematic blue lighting while the input remains studio-clean.

**Transfer:** Translate this to before-and-after states, data-to-report, or draft-to-finished work; the contrast must demonstrate a real transformation.

**Build:** On a lavender 814px square, place a small white-backed input tile occupying about one quarter of the width at left, a rounded output image occupying about two thirds at upper right, and a wide white command strip near the bottom. Maintain separation between the three layers without adding connecting arrows.

### Workflow video

**Only for:** integration and instructional sections

**Use:** Opening tool demonstration and instructional panels.

**Observed:** Interface footage shows a selected design, tool window and realistic rendered result together. The opening demo sits in an approximately 900px-wide lightly outlined rounded frame; instructional video is a wide landscape player in a white panel.

**Transfer:** Use a short legible task demonstration with the same input-to-result clarity; a single composed still showing those states is the minimum acceptable alternative.

### Icons

**Observed:** Small dark outline utility icons, generally 20–32px. Chevrons and contact bubbles use rounded strokes near 2px; category symbols can use 32px mixed-fill shapes with finer strokes. Customer logos are uniformly sage gray.

**Transfer:** Choose simple outline icons for utility and questions. Let real output imagery, rather than a field of oversized feature icons, explain the product.

## Section recipes

How recurring sections are built.

### First screen: Promise over collection

**Observed:** Continuous canvas behind a centered, 106px-high Navigation area. The headline begins after 96px of breathing room, spans no more than 768px and wraps to two lines at 60.8px/1.2; the first noun is heavier than the remaining promise. A centered 600px-wide body paragraph follows after 24px. There is no dominant hero CTA: navigation provides entry actions and the collection itself is the next interaction. Below the text, a broad row of Category tabs sits above a three-column Category card grid. Within the first 900px, the navigation, full headline and support paragraph, tabs and upper portions of the first three image cards are visible; the rest of the collection continues below. Layers run canvas → white outlined cards → photographic previews; no floating decoration obscures the promise.

**Transfer:** Lead with a compact outcome promise and immediately expose a visually rich collection of results. If the product has no physical output, use actual workflow views or finished documents within the contact sheets. Integration pages instead use the bold display recipe for the full headline, add Proof micro-labels above it and a large framed Workflow video below. Catalog pages use a left-aligned catalog headline with actions above search and results beside the persistent sidebar.

**Avoid:** Do not replace the opening with a giant device centered over a dark gradient, or insert a large paired CTA group between the default headline and the collection.

**Text style:** `display` — Vend Sans 600 · 60.8px/1.2 · tracking -0.0329em

### Alternating demonstration chapter

**Observed:** An approximately 910px-tall row contains an 814px Pastel stage and a 460px copy block, with 48px between columns and 48px vertical padding. Image and text alternate sides across chapters. Feature-heading leads a paragraph after 24px; a Primary button appears only where there is a direct installation action.

**Transfer:** Give one concrete capability its own visually dominant proof stage. Vary the internal media arrangement rather than inventing new section shells.

**Text style:** `feature-heading` — Vend Sans 700 · 43.2px/1.2 · tracking -0.0231em

### Muted trust band

**Observed:** Centered 768px-wide trust statement in sage gray at 24px/1.5 above a compact horizontal row of monochrome customer logos. The band is quiet and airy, not an array of white testimonial cards.

**Transfer:** Use permissioned customer marks and a restrained statement of audience or use. Keep proof subordinate to the visual demonstration.

**Text style:** `trust` — Vend Sans 600 · 24px/1.5

### Instructional panel

**Observed:** White information panel with a 48px heading and 112px vertical padding. The integration variant includes a wide tutorial player followed by three text steps; the catalog variant is text-led with compact 19.2px step titles and 16px explanatory paragraphs.

**Transfer:** Explain the shortest complete path from starting input to exported or useful result. Keep steps practical and avoid selling copy here.

**Text style:** `section-heading` — Vend Sans 700 · 48px/1.2

### FAQ and human help close

**Observed:** White information panel with a left-aligned 48px heading, about 80px of separation before two question columns, and a 64px column gap. FAQ question rows show chevrons and hidden answers on marketing pages. A centered help block follows with a 32px heading, one short support line and a small Primary button. Catalog pages display answers in two columns and end with the help message without the contact button or a directory.

**Transfer:** Handle practical eligibility, setup, output and commercial questions. Close with a human route to help rather than a new exaggerated sales claim.

**Text style:** `section-heading` — Vend Sans 700 · 48px/1.2

### Directory ending

**Observed:** White full-width footer padded 48px. Compact identity above four 300px columns separated by 48px; directory groups use small bold labels and regular Directory links. The column area is deliberately tall. Copyright sits at bottom left and a small chat icon/link at bottom right.

**Transfer:** Use the breadth appropriate to the new product, grouping resources and policies clearly; maintain the low-key baseline rather than adding giant wordmark art.

## Page flow

**Storyline:** Outcome promise → visible results → capability demonstrations → practical setup and objections → human help and useful navigation.

### Broad marketing landing page

1. **Promise** — Centered two-line headline and explanatory paragraph on the pale canvas.
2. **Product proof** — Category tabs and six four-image preview cards.
3. **Capability chapters** — Alternating large media stages and narrow descriptive text, with one installation action.
4. **Objection handling** — Two-column collapsed FAQ.
5. **Human help** — Centered support prompt and compact contact action.
6. **Resource navigation** — Four-column directory ending with copyright and chat.

**Transfer:** Replace the categories and chapters with the new product's outcomes; keep visual evidence close to its promise and finish with useful support.

### Searchable catalog with conversion support

1. **Orientation** — Persistent left category sidebar, left-aligned promise and lime primary action beside a white secondary action.
2. **Product discovery** — Search followed by a long three-column grid of square images and small single-line captions, then Load more.
3. **Capability explanation** — Compact selector of four capabilities beside one large demonstration image.
4. **Setup guidance** — White panel with three practical steps.
5. **Objection handling** — Static answers in two columns and a centered help close; the sidebar remains visible through the ending.

**Transfer:** Use this denser variant for large browsable inventories, not as the default marketing shell.

### Focused integration landing page

1. **Conversion entry** — Minimal identity-and-install navigation, micro-proof strip and centered bold promise.
2. **Product demonstration** — Large lightly framed task video beneath the support line.
3. **Social proof** — Muted trust statement and customer marks.
4. **Capability chapters** — Alternating pastel stages: nine-up collection, freshness marker, detailed result, outcome collage and human teamwork image.
5. **Setup guidance** — Wide tutorial player and three steps in a white panel.
6. **Objection handling** — Collapsed two-column FAQ and contact close.
7. **Resource navigation** — Full directory footer with small copyright/chat baseline.

**Transfer:** Concentrate the promise around fitting an existing workflow; use verified proof labels and a task demonstration rather than broad catalog navigation.

## Writing

Direct, encouraging and outcome-oriented. The product sounds easy to use because it describes concrete actions and removes specific workflow friction, not because it adopts grandiose technology language.

**Do not copy:** Do not reuse Artboard Studio names, logos, product artwork, customer marks, audience counts, library sizes, pricing, claims or testimonials as the new product's assets or facts. The examples below show the pattern only; write new copy for the new product.

- **Addressing the reader:** Address the reader as you and your; use we for the team maintaining the product. Feature copy often starts with an imperative.
- **Rhythm:** Headlines are short practical promises or plain feature names. Supporting paragraphs run several concise sentences, often using a clipped opening and a three-part action sequence.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Name the output and the improvement it enables. | 6–12 words | “Mockups to present your designs like a pro” |
| Feature heading | Use a familiar task or a specific workflow benefit. | 2–9 words | “Online mockup editor”<br>“Create mockups and animations inside Figma” |
| Supporting copy | Start with friction removed, then explain the concrete mechanism and result. | 35–65 words | “Skip the software. Our online editor lets you apply your designs to any mockup directly in the browser, adjust backgrounds, and export high-res images in seconds. Everything you need for a client-ready presentation, without opening a single app.” |
| Primary action | Verb plus destination or task; no clever euphemism. | 1–4 words | “Install Figma plugin”<br>“Create mockups online” |
| Help close | Ask a short friendly question, then name the available support route. | 3–6 words for heading | “Still have questions?” |

**Words and phrasing to use:** right inside; no switching; ready-to-use; high-quality; your workflow; in seconds; just place; export

**Avoid:** revolutionary ecosystem; paradigm shift; unleash limitless potential; enterprise-grade synergy

**Rules:**

- Tie every benefit to an action, artifact or context the reader recognizes.
- Use short friction-removal openings such as 'Skip the software' before a fuller explanation.
- Keep FAQ answers plain, practical and specific about limits, setup and outputs.
- Use quantities only when verified; an unproven number is not a substitute for a visible demonstration.

## Do's and Don'ts

### Do

- Keep the default headline at 60.8px with -2px tracking and emphasize only the opening noun or phrase.
- Use 43.2px feature headings beside 16px body copy rather than enlarging every text role.
- Keep feature media about 814px square and copy no wider than 460px at desktop.
- Use 8px radii for actions and inner media; 12px for enclosing cards and stages.
- Make color blocks flat and pastel; let full-color outcomes provide the visual energy.
- Use 24px for text and collection gaps and 48px for feature-column and footer separation.
- Keep information panels white with 112px vertical padding.
- End marketing pages with human support and an organized directory rather than a dramatic second hero.

### Don't

- Do not make the default canvas pure white throughout; retain the faint citron-to-stone field behind the content.
- Do not apply lime to full-width section backgrounds or body paragraphs; reserve it for small identity and action accents.
- Do not turn the 42px primary action into a 64px pill.
- Do not use visible card shadows as the default depth cue; the site relies on hairlines and image staging.
- Do not convert the unequal 814px/460px feature composition into equally sized text and image columns.
- Do not wrap every paragraph in its own rounded container; white shells belong to collections and information panels.
- Do not make directory links tiny legal text; their default is 16px with 42px interaction height.
- Do not carry the 350px catalog sidebar into an ordinary marketing landing page.

## Motion and responsive

### Motion

**Observed:**

- Category cards declare width 0.2s and box-shadow 0.3s transitions with cubic-bezier(0.455,0.03,0.515,0.955).
- Catalog cards declare box-shadow 0.3s transitions. Demonstration media includes video.

**Transfer:**

- Keep animation concentrated in task demonstrations and restrained card interactions; preserve the stable grid and alternating stage composition.

**Unknown:**

- Scroll animation timing, video sequencing and actual interactive hover appearance are not established.

### Responsive

**Observed:**

- CSS declares width breakpoints at 479px, 767px, 768px and 991px.

**Transfer:**

- On narrower layouts, stack each stage with its associated copy and scale the square stage proportionally; retain the image-to-copy emphasis.
- Allow category controls and contact sheets to reorganize without shrinking their labels below readable sizes. Treat the catalog sidebar as a separate navigation problem rather than squeezing the desktop offset into mobile.

**Unknown:**

- Actual mobile typography, stacking order, sidebar behavior and navigation interactions are not established; these transfer rules are recommendations.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
