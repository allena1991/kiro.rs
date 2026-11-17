# Lightship — open-country engineering

## Overview

An expansive, image-led style that brings engineered products into a warm, lived-in world. White and chalky cream canvases, black regular-weight grotesk type, muted teal and rare vermilion accents feel outdoorsy without becoming rustic. Cinematic landscape photography, restrained technical renders and oversized word sculptures alternate with small, practical information, giving premium hardware and ambitious consumer products room to breathe.

### Essentials

- A cinematic promise is split across the horizon: a nearly full-screen image inside an 8px perimeter and 12px rounded mask, with two white 72px, weight-400 phrases pushed to opposite sides at mid-height.
- Words become scenery behind the product: include a monumental black word sculpture spanning almost the full width behind a centered 592×644px image stack; use live oversized type when custom lettering is unavailable.
- The hierarchy feels stretched open but tightly typeset: regular grotesk headings use 1 line height and -0.05em tracking at 48–76px; practical copy drops to 16px/1.25 and bold 14px labels.
- Controls stay small against enormous media: 40px-high pills with 20px corners, 24px horizontal padding and 14px labels; circular 40px plus and arrow controls accompany image rails.
- Color is a punctuation system, not a theme wash: white dominates, #f2efea supports substantial utility bands, #29525e is a thin 40px announcement strip, and #fa5c40 is reserved for focused conversion or editorial emphasis.
- Real light does the emotional work: subdued olive, straw, rock and sunset photography fills large rounded frames; technical imagery sits on pale warm-gray stages. For products without location photography, pair a truthful product render with tactile real-use detail photography.
- A survey-like plus field gives warmth a technical register: faint repeated crosshairs sit behind cream newsletter and system panels; combine this with 100–200px chapter spacing rather than a dense dashboard grid.

## Colors

### Brand

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Deep blue teal | `#29525e` | `--color-teal` | background | Announcement strip, carrying white compact copy. |

### Accent

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| Vermilion | `#fa5c40` | `--color-conversion` | action, accent | Focus outlines throughout; filled emphasis is limited to customization actions and bold editorial tiles. |

### Neutral

| Name | Value | Token | Roles | Use |
| --- | --- | --- | --- | --- |
| White | `#ffffff` | `--color-canvas` | background, surface, text | Dominant page canvas, white cards and reversed image-overlay text. White also forms translucent navigation glass. |
| Cool porcelain | `#f7f7f7` | `--color-control` | surface, action | Secondary controls and technical illustration stages. |
| Warm ivory | `#faf6ef` | `--color-media-backing` | surface | Warm backing under photographic media and portrait stages; imagery remains the visible foreground. |
| Chalk stone | `#f2efea` | `--color-band` | background, surface | Warm utility bands and patterned editorial panels. |
| Hairline gray | `#d9d9d9` | `--color-rule` | border | Input outlines, footer link rules and list separators. |
| Neutral gray | `#a1a1a1` | `--color-muted` | text | Supporting paragraphs, eyebrows and article dates. |
| Subdued ink | `#999999` | `--color-subdued` | text | Visible result of black at 40% over white; used for footer descriptive copy. |
| Black ink | `#000000` | `--color-ink` | text, background, action | Primary type, solid conversion pills and dark technical accents. |

## Typography

- **F37Bolton** — All text, from monumental headings to form labels. A clean, open grotesk with regular-weight display forms, compact spacing and approachable rounded counters. If unavailable, use **Inter**. Use 400 and 700; preserve tight display tracking and check line breaks. Font stack: "F37Bolton", "Inter", Arial, sans-serif.

| Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- |
| manifesto | F37Bolton | 400 | 76px | 1 | -0.05em | Large left-aligned editorial paragraph with a 1000px measure. |
| display | F37Bolton | 400 | 72px | 1 | -0.05em | Split image hero headlines and centered major chapter headings. |
| heading | F37Bolton | 400 | 48px | 1 | -0.05em | Image-stack closing message and medium centered declarations. |
| heading-sm | F37Bolton | 400 | 34px | 1.2 | -0.05em | Editorial split sections and newsletter headings. |
| card-heading | F37Bolton | 400 | 24px | 1.25 | -0.03em | Feature overlays, journal titles, supporting feature statements and job titles. |
| lead | F37Bolton | 400 | 22px | 1.25 | normal | Centered introduction paragraphs, footer primary links and accordion questions or answers. |
| body | F37Bolton | 400 | 16px | 1.25 | normal | Editorial body text, supporting navigation and feature details. |
| eyebrow | F37Bolton | 700 | 14px | 1.25 | normal | Sentence-case section labels and card micro-headings. |
| caption | F37Bolton | 400 | 14px | 1.25 | normal | Button labels, dates and location metadata. |

### Page-type variants

| Only for | Recipe | Font | Weight | Size | Line height | Tracking | Use |
| --- | --- | --- | --- | --- | --- | --- | --- |
| product conversion finales | closing-display | F37Bolton | 400 | 218px | 1 | -0.05em | Monumental white closing invitation across an immersive scenic image. |
| recruitment listings | listing-heading | F37Bolton | 400 | 64px | 1 | -0.05em | Section title with a matching-size result count aligned at the far right. |
| system diagrams and customization cards | tile-body | F37Bolton | 400 | 20px | 1.25 | normal | Larger explanatory copy inside small white feature tiles. |

**Notes:**

- Display hierarchy comes from size and placement, not bold weight. Keep heading tracking at -0.05em, card headings at -0.03em and small copy at normal.
- Sentence case predominates, including the bold small labels; avoid turning the hierarchy into all-capital equipment labels.
- Use a 576px measure for centered gray introductions, roughly 392px for newsletter headings and 300px for feature-overlay titles.
- Type sizes inherit a viewport-scaled root. Keep the stated desktop recipes together rather than changing tracking independently.

## Layout

**Density:** Airy at the chapter level, compact inside controls: large white intervals separate immersive scenes while rails use narrow gutters.

### Spacing

| Value | Use |
| --- | --- |
| 8px | Outer media inset, grid gutters and form row gaps. |
| 12px | Compact tile interiors and ruled navigation row padding. |
| 16px | Button icon gaps, card label-to-copy spacing and date separation. |
| 20px | Eyebrow-to-heading gap and compact content stacks. |
| 24px | Feature overlay padding and heading-to-support gaps. |
| 28px | Journal image-to-title gap. |
| 40px | Editorial text-to-action separation and introduction content gaps. |
| 100px | Section title-to-carousel interval. |
| 124px | Desktop container side margins and image-stack intervals. |
| 150px | Standard chapter margins, newsletter vertical padding and footer group spacing. |
| 200px | Major introduction and storytelling intervals. |

### Containers and grids

- **editorial-container**: max width 1440px · side padding 124px. Desktop inner content spans 1192px; used for split editorials, footer, newsletters and technical details.
- **immersive-container**: max width 1440px · side padding 8px. Near-full-bleed media with a thin white perimeter.
- **feature-rail**: 2 columns · gap 8px. 592px-wide feature cards in an overflowing rail; show two complete cards and part of the next rather than shrinking three to fit.
- **journal-rail**: 3 columns · gap 8px. 392px-wide image-and-text cards, with the next card visible beyond the editorial container.
- **accordion-measure**: max width 792px. Centered disclosure rows under a spacious chapter heading.
- **introduction-measure**: max width 576px. Centered lead paragraph isolated by broad white margins.

## Corner radius

| Only for | Element | Radius |
| --- | --- | --- |
|  | media-panels | 12px |
|  | compact-media | 8px |
|  | stacked-images | 10px |
|  | buttons | 20px |
|  | inputs | 100px |
| recruitment listings | listing-filters | 8px |

## Surfaces and depth

### Surfaces

#### White canvas · level 0

**Use:** Main uninterrupted page ground.

**CSS:** `background: #ffffff; color: #000000`

**Observed:** Broad empty intervals contrast with large media; no raised-card shadow system.

**Transfer:** Let imagery and typography define sections without boxing every text block.

#### Survey panel · level 0

**Use:** Newsletter, customization and systems bands.

**CSS:** `background: #f2efea; clip-path: inset(0px 8px round 12px)`

**Observed:** A barely visible plus-sign field covers the warm panel. The pattern continues behind both content columns.

**Transfer:** Use the Crosshair field graphic as a background layer; keep it much lower contrast than body text.

#### Media stage · level 1

**Use:** Warm-backed imagery and technical media.

**CSS:** `background: #faf6ef; border-radius: 12px; overflow: hidden`

**Observed:** Usually covered by photography; technical renders also use cool porcelain. Borders and drop shadows are absent.

**Transfer:** Match the frame tone to the image edges, not to a generic elevated UI card.

#### Navigation glass · level 2

**Use:** Floating navigation above scenes.

**CSS:** `background: rgba(255,255,255,0.468414); backdrop-filter: blur(51.5px); border-radius: 12px`

**Observed:** A shallow translucent white bar overlays photography; interior-page glass uses 60% white and 66px blur. Text reverses from white over the opening scene to black over light content.

**Transfer:** Use translucent white rather than a dark frosted dashboard panel.

#### Proof glass · level 1

**Only for:** impact and quantified editorial stories

**Use:** A pair of statistic tiles over dark scenic photography.

**CSS:** `background: rgba(0,0,0,0.2); backdrop-filter: blur(18px); border-radius: 8px; padding: 12px; color: #ffffff`

**Observed:** Two 278×199px tiles use 72px numerals high in each tile and tiny unit captions near the bottom.

**Transfer:** Use a meaningful comparison with units; keep the background scene visible.

## Components

### Announcement strip

**Use:** A compact sitewide news or availability notice.

**CSS:** `background: #29525e; color: #ffffff; height: 40px; display: grid; grid-template-columns: 1fr auto 1fr; padding: 0px 12px; align-items: center`

**Text style:** `caption` — F37Bolton 400 · 14px/1.25

**Observed:** A faint descriptor sits left; centered short news copy is followed by a small white pill; a fine close glyph sits at the right.

### Floating navigation

**Use:** Persistent orientation without interrupting media.

**CSS:** `height: 50px; display: grid; grid-template-columns: 1fr 200px 1fr; padding: 0px 16px; border-radius: 12px`

**Text style:** `caption` — F37Bolton 400 · 14px/1.25

**Observed:** Uses Navigation glass behind a centered compact identity, menu icon and product links to the left, experience and conversion links to the right. It begins almost full width and becomes a narrower centered bar over the story.

**Transfer:** Preserve the three-part balance with a compact original identity rather than a huge logo.

### Primary button

**Use:** Newsletter submission and straightforward conversion.

**CSS:** `background: #000000; color: #ffffff; height: 40px; border-radius: 20px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center; gap: 16px`

**Text style:** `caption` — F37Bolton 400 · 14px/1.25

**Observed:** A small right arrow can follow the label. Secondary actions use porcelain with black text. Customization uses vermilion; its persistent build-bar variant has 8px corners rather than pill corners.

**States:** Declared: hover values are unspecified; focus-visible outline-color #fa5c40, outline-offset 5px, outline-style auto, outline-width 10px. Color and background-color transition .15s.

### Media button

**Use:** An action directly on photography.

**CSS:** `background: rgba(0,0,0,0.4); color: #ffffff; backdrop-filter: blur(22px); height: 40px; border-radius: 20px; padding: 0px 24px; display: inline-flex; align-items: center; justify-content: center`

**Text style:** `caption` — F37Bolton 400 · 14px/1.25

**Observed:** Centered beneath a short white statement, or reduced to a plus-icon circle on the lower right of a feature image.

### Rail controls

**Use:** Move through editorial and capability carousels.

**CSS:** `width: 40px; height: 40px; background: #f7f7f7; border-radius: 20px; display: flex; align-items: center; justify-content: center`

**Observed:** A pair of arrow circles sits below the left edge of the rail with 8px between them; a sparse dot pager follows after a 40px interval. Icons are 16px.

### Feature image card

**Use:** Capability chapters presented as visual invitations.

**CSS:** `width: 592px; height: 370px; position: relative; padding: 24px; border-radius: 12px; overflow: hidden; color: #ffffff`

**Text style:** `card-heading` — F37Bolton 400 · 24px/1.25 · tracking -0.03em

**Observed:** Full-image background with restrained darkening, a bold micro-label at upper left, lower-left title with a 300px measure and a Media button plus-circle at lower right.

**Transfer:** Alternate isolated engineered detail and real-use scenes within the same rail.

### Journal card

**Use:** Editorial proof and ongoing activity.

**CSS:** `width: 392px; display: flex; flex-direction: column; gap: 28px`

**Text style:** `card-heading` — F37Bolton 400 · 24px/1.25 · tracking -0.03em

**Observed:** A 392×245px photograph with 8px corners is followed by an unboxed title and a muted caption-size date separated by 16px. No colored card body or outline.

**States:** Declared: hover text-decoration-line underline on title links; focus-visible outline-color #fa5c40, outline-offset 5px, outline-style auto, outline-width 10px.

### Newsletter input

**Use:** Low-friction newsletter signup in the cream panel and footer.

**CSS:** `height: 50px; background: #ffffff; border: 1px solid #d9d9d9; border-radius: 100px; display: flex; position: relative`

**Text style:** `caption` — F37Bolton 400 · 14px/1.25

**Observed:** A location field and email field are stacked with 8px between them in a 392px-wide form. The email row encloses a Primary button with a 4px inset. In the footer, the fields become an adjacent pair.

### Footer link row

**Use:** Primary destinations in the spacious closing navigation.

**CSS:** `border-bottom: 1px solid #d9d9d9; padding: 12px 0px`

**Text style:** `lead` — F37Bolton 400 · 22px/1.25

**Observed:** Four primary destinations form a 592px-wide ruled column opposite a compact brand promise and gray description. Smaller secondary links and social icons sit in a separate lower group.

### Accordion row

**Use:** Objection handling and structured values.

**CSS:** `display: flex; justify-content: space-between; align-items: center; gap: 20px; padding: 12px 0px`

**Text style:** `lead` — F37Bolton 400 · 22px/1.25

**Observed:** Centered in a 792px measure with fine horizontal separators and a 16px plus at the right. Answers expand below in the same 22px text style; the values variant adds a left number and centers its short title.

**States:** Declared: hover values are unspecified; focus-visible outline-color #fa5c40, outline-offset 2px, outline-style auto, outline-width 10px.

### Job row

**Only for:** recruitment listings

**Use:** Practical opportunities list following an editorial culture introduction.

**CSS:** `display: flex; justify-content: space-between; align-items: flex-start; gap: 8px; padding: 32px 0px; border-bottom: 1px solid #d9d9d9`

**Text style:** `card-heading` — F37Bolton 400 · 24px/1.25 · tracking -0.03em

**Observed:** Location at left, department above the larger title in the wide middle, work type next and a compact Apply button at right. Rows are about 133px tall. Above them, 40px filter chips with 8px corners wrap at 8px gaps; active filters are black.

### Upgrade tile

**Only for:** system diagrams and customization cards

**Use:** Small modular explanations with a distinct visual anchor.

**CSS:** `background: #ffffff; width: 292px; padding: 4px; border-radius: 12px; display: flex; flex-direction: column; justify-content: space-between`

**Text style:** `tile-body` — F37Bolton 400 · 20px/1.25

**Observed:** Bold 14px heading and muted 20px explanation are inset another 12px; a 284×175px image occupies the bottom. Customization versions add a plus-circle over that image.

## Imagery and graphics

### Cinematic environment

**Use:** Opening, full-width chapter interludes and emotional conversion moments.

**Observed:** Product shown small to medium within immense meadows, pine valleys, desert formations and sunset skies. Natural greens and ochres are subdued, shadows deep, glass reflective. Frames have softly rounded corners and often a gentle dark layer to hold white type.

**Transfer:** Show a new product in a believable world with warm directional light and ample environmental context. For intangible products, photograph the human setting and show a truthful interface on a real device; avoid generic abstract stock.

### Word sculpture and image stack

**Use:** A signature product-introduction device within the main story.

**Observed:** A full-width black product-identification line sits behind centrally stacked vertical photographs. The lettering is much larger than ordinary headings; foreground cards are 592×644px and overlap into a compact pile as the story progresses. Small side captions balance the stack.

**Transfer:** Use a short original naming statement as large lettering and layer different use, detail and human scenes in front. Include the device even without custom artwork by using live type.

**Build:** Set a single-line regular grotesk statement at about 248px/1 with -0.05em tracking across a 1424px desktop stage. Fit the phrase to nearly touch the edges; use SVG textLength or responsive live type at roughly 17.2vw. Place a 592×644px rounded photo frame centrally above it; additional frames sit behind with small upward offsets. Keep the ground white, without glows or drop shadows.

### Crosshair field

**Use:** Signature quiet texture on Survey panel.

**Observed:** Very faint gray plus marks repeat evenly over cream, like plotting marks rather than a visible grid. Marks remain visible in the empty space around forms and photography.

**Transfer:** Repeat a fine original registration mark, maintaining its low contrast and open spacing.

**Build:** Create a transparent 100×100px SVG pattern tile with a centered plus formed by two 14px lines at 0.5px stroke. Use black at about 10% alpha; lay it over #f2efea and beneath content. Keep marks fixed-size rather than scaling with each panel.

### Technical product study

**Use:** Capability rails, technical opening scenes and feature explanations.

**Observed:** Photoreal hardware cutaways, floating material layers and semi-transparent overhead assemblies sit on pale gray or ivory grounds. Parts remain tangible rather than diagrammatically flat; perspective and realistic soft contact shading make complex systems legible.

**Transfer:** Use an honest exploded view, material stack or close-up with a neutral background. A clean product photograph with a restrained annotation is the minimum equivalent when high-quality 3D is unavailable.

### Linked system diagram

**Only for:** technical explanation chapters

**Use:** Show how a sequence of capabilities forms one system.

**Observed:** Staggered white Upgrade tiles flank a thin central connector across a cream Crosshair field. Large circular symbols punctuate a path that changes from green solid to black dotted. A pale warm sunlike wash occupies the top; black nodes become green at an active step.

**Transfer:** Use three or more genuinely linked stages rather than unrelated benefit cards.

**Build:** Draw an SVG connector with vertical runs and gently rounded diagonal bends between 80px circle nodes. Use 1–2px lines; change later runs to a dotted stroke. Place 292px white tiles alternately left and right. Add a broad low-opacity warm-yellow radial wash behind the top node, keeping it lighter than the tiles.

### People and making

**Only for:** company, recruitment and editorial proof sections

**Use:** Humanize engineering and make the organization tangible.

**Observed:** Candid workshop scenes, team gatherings and outdoor moments appear in asymmetrical rounded collages. Leadership portraits are grayscale, waist-up or chest-up against warm ivory, arranged in 292×365px frames; names and roles sit below rather than on top.

**Transfer:** Mix working details with an expansive group scene; reserve the consistent neutral portrait grid for actual team information.

### Icons

**Observed:** Small monochrome filled SVGs, usually 16px inside arrows and plus controls, 20px for social actions. Fine plus, close and menu marks contrast with simple solid symbols. The central identity uses a compact paired sparkle motif.

**Transfer:** Use spare monochrome plus, arrow and menu glyphs at the same optical scale. Choose an original compact identity mark; keep decorative symbols subordinate to media.

## Section recipes

How recurring sections are built.

### First screen: Horizon promise opening

**Observed:** The first 900px is dominated by a scenic moving image inside an 8px white perimeter with a 12px rounded mask. A 40px teal Announcement strip sits at the top and Floating navigation overlays the upper scene. The main product lies in the lower half against a broad landscape, with two short white 72px headline phrases arranged on a shared mid-height baseline: first to the left, second anchored to the right edge. Back-to-front layers are landscape, product in its real setting, restrained contrast darkening, split heading, navigation and banner. A fine bottom rule and tiny scroll cue finish the scene. No long supporting paragraph or oversized central CTA appears above the fold; the short banner action is visible. Collage and introductory copy arrive below.

**Transfer:** Create the same scale contrast between a real environment and a confident two-part promise. If no film exists, use one excellent still showing product and context, not a blank abstract stage. Technical pages can use a translucent cutaway on pale gray in the same split-heading composition. Recruitment opens with centered 72px black type, a small eyebrow and a secondary pill on white; institutional storytelling uses a centered 48px statement well below navigation.

**Avoid:** Do not replace the split horizon headline with a left text column and right boxed thumbnail, or pile badges, bullet lists and multiple large buttons into the first screen.

**Text style:** `display` — F37Bolton 400 · 72px/1 · tracking -0.05em

### Centered chapter heading

**Observed:** A muted bold 14px eyebrow precedes a regular 72px centered title. Some chapters use 48px instead. A 40px interval separates any 22px gray support copy or small secondary action, and 100px separates the title group from a rail.

**Transfer:** Use a concise human benefit as the chapter title, not a catalog of features.

**Text style:** `display` — F37Bolton 400 · 72px/1 · tracking -0.05em

### Editorial split

**Observed:** Inside the 1192px editorial width, a roughly 392px text block balances a 692×432px rounded image. The text uses an eyebrow, a 34px heading and 16px support separated by 24px; some scenes reverse the image and text. A small action follows after 40px when needed.

**Transfer:** Use each split to explain one mechanism and its practical consequence.

**Text style:** `heading-sm` — F37Bolton 400 · 34px/1.2 · tracking -0.05em

### Monumental image stack

**Observed:** Word sculpture and image stack sits on white with the lettering behind the central media. Images progress at 124px vertical intervals and become sticky overlapping cards. The final darker human scene carries a centered 48px white statement and Media button.

**Transfer:** Make a compact visual argument through context, detail and use rather than repeating similar product angles.

**Text style:** `heading` — F37Bolton 400 · 48px/1 · tracking -0.05em

### Overflow capability rail

**Observed:** Feature image cards run horizontally at an 8px gutter. Their 592×370px size yields two full cards plus a partial next card. Rail controls sit below, aligned to the 124px editorial inset. A large centered heading is separated from the images by 100px.

**Transfer:** Keep card width and visible overflow; let readers discover more without flattening the layout into tiny equal tiles.

**Text style:** `card-heading` — F37Bolton 400 · 24px/1.25 · tracking -0.03em

### Large editorial statement

**Observed:** A 76px black paragraph sits almost flush to the 8px outer inset with a 1000px measure, leaving the right side open. It reads like a continuous manifesto rather than a normal body paragraph.

**Transfer:** Use one substantial but readable statement to bridge visual demonstrations and the wider brand purpose.

**Text style:** `manifesto` — F37Bolton 400 · 76px/1 · tracking -0.05em

### Cream invitation panel

**Observed:** Survey panel has 150px vertical padding and 124px side insets. A left 392px heading and Newsletter input form balance a 692×432px scenic image on the right. Heading begins with an eyebrow; form aligns near the image bottom rather than immediately under the heading.

**Transfer:** Use the panel as a warm low-pressure invitation, with a useful reason to subscribe or request information.

**Text style:** `heading-sm` — F37Bolton 400 · 34px/1.2 · tracking -0.05em

### Quiet information ending

**Observed:** The shared ending is white, not dark. After a 150px break, a short promise and muted 22px description sit left, with Footer link rows in a right-hand 592px column. Another widely spaced group pairs a newsletter form with two compact link columns and social icons. Small disclosures and a final hairline legal row close the page. The main footer spans about 953px with substantial internal white space.

**Transfer:** Keep navigation and a useful signup form as the ending even when a dramatic conversion scene precedes it; preserve the contrast between modest small links and expansive whitespace.

**Text style:** `lead` — F37Bolton 400 · 22px/1.25

### Impact bento

**Only for:** company and impact storytelling

**Observed:** A 392px vermilion quotation tile above a smaller human photograph sits beside a 792×645px night scene. Repeated white text moves across that image as a restrained horizontal rail. Below, a wide dark scenic image carries a 34px statement, a small explanatory paragraph and paired Proof glass statistics.

**Transfer:** Combine a first-person belief, a real place and a substantiated metric comparison. Use the bright quote tile as a single emphasis, not a repeated color-card system.

**Text style:** `heading-sm` — F37Bolton 400 · 34px/1.2 · tracking -0.05em

### Product conversion finale

**Only for:** product detail landing pages

**Observed:** A narrow scenic aperture expands to a nearly full-viewport rounded image. A white 218px invitation spans its upper third; the product remains below the line in the environment. Along the bottom, a dark glass action panel pairs a smaller expert-help area with a wider vermilion build action. Each uses a bold small label, larger bottom-aligned explanation and arrow circle. A compact identity flourish separates this scene from the white footer.

**Transfer:** Offer human help and direct action as two differently weighted paths; retain the scenic backdrop and enormous invitation rather than a conventional centered CTA band.

**Text style:** `closing-display` — F37Bolton 400 · 218px/1 · tracking -0.05em

## Page flow

**Storyline:** Immersive promise → contextual introduction → visual capability stories → deeper mechanism or human proof → useful invitation → spacious information ending.

### Brand-led marketing landing page

1. **Promise** — Split horizon headline over a scenic film, followed by a loose collage of real-life scenes.
2. **Positioning** — Centered gray introduction with a narrow measure.
3. **Product demonstration** — Monumental word sculpture behind overlapping image cards, ending with an image-overlay invitation.
4. **Capability chapters** — Overflow feature rail and large photographic interlude.
5. **Belief and proof** — Large editorial statement, small text beside photography and a journal rail.
6. **Continuing relationship** — Cream patterned newsletter panel followed by the white navigation footer.

**Transfer:** Use an emotional entry and alternate broad scenes with tightly focused explanations; the narrative can be shortened without losing the word sculpture, scenic imagery or patterned invitation.

### Technical explanation page

1. **Engineering promise** — Split white heading over a translucent overhead product study.
2. **Mechanism introduction** — Large editorial paragraph introduces the system logic.
3. **Capability chapters** — Centered headings, alternating editorials, testing film and detail-image rails.
4. **System proof** — Linked system diagram on cream, then a ruled feature list and app-in-use media.
5. **Product invitation** — Word sculpture and image stack reconnect engineering to lived experience.
6. **Objection handling** — Centered FAQ accordion, then cream newsletter and the shared white footer.

**Transfer:** Explain real mechanisms through detail media and a linked process; return to the human benefit before answering questions.

### Product detail and conversion page

1. **Promise** — Scenic split-headline opening with a compact persistent conversion bar.
2. **Differentiation** — Gray introduction and image rail.
3. **Product demonstration** — Large interactive product stage with view tabs, mode selection and restrained color swatches.
4. **Capability and flexibility** — Technical rail, editorial split, then cream customization tiles.
5. **Decision support** — Large overhead product image with a specifications invitation.
6. **Closing call** — Expanding scenic aperture, monumental white invitation, paired help and build actions, identity flourish and shared white footer.

**Transfer:** Use immersive exploration and specification support before the dramatic conversion moment; keep configuration controls scoped to products that need them.

### Institutional belief and people page

1. **Belief** — Centered regular-weight statements revealed in a large white field.
2. **Human proof** — Asymmetric image collage and grayscale portrait grid.
3. **Purpose and quantified proof** — Bright quotation tile, night-scene text rail and large image with paired statistics.
4. **Values and culture** — Numbered accordion and an editorial working-culture split.
5. **Further exploration** — Paired image links and journal rail, followed by newsletter and shared footer.

**Transfer:** Trade the immersive opening for typographic conviction; substantiate belief with people, behavior and meaningful metrics.

### Recruitment and opportunities page

1. **Invitation** — Centered 72px recruitment statement with a small secondary action.
2. **Culture proof** — Loose working-life collage followed by team photograph and short introduction.
3. **Practical discovery** — 64px listing title and count, compact wrapping filters and ruled multi-column job rows.
4. **Wider purpose** — Editorial image-and-text split and journal rail.
5. **Continuing relationship** — Cream newsletter followed by the same white footer.

**Transfer:** Separate emotional culture storytelling from the efficient, unboxed opportunities list.

## Writing

Optimistic and assured, balancing the romance of freedom with tangible engineering. Technical terms are explained through ordinary comforts and useful outcomes rather than jargon alone.

**Do not copy:** Do not reuse the brand name, product names, wordmark or paired-sparkle artwork, named technologies, leadership names, quotations, proprietary claims, production facts, prices, efficiency figures, emissions comparisons or test numbers. Source examples illustrate cadence only.

- **Addressing the reader:** Use you and your for experiences and choices; use we for beliefs and making. Refer to the product by name when explaining a concrete system.
- **Rhythm:** Short two-part headlines frequently pair parallel clauses, while supporting paragraphs flow in complete conversational sentences. Buttons use direct verbs; punctuation is calm, with periods and occasional em dashes rather than exclamations.

| Role | Pattern | Typical length | Examples of the pattern |
| --- | --- | --- | --- |
| Hero headline | Two complementary clauses connect aspiration with credibility or forward movement. | 6–10 words | “Born for Adventure. Built in America.”<br>“Engineered for What’s Ahead” |
| Capability heading | Pair a practical benefit with a short emotional payoff. | 5–10 words | “Twice the Efficiency. All the Freedom.”<br>“Built to Withstand. Designed to Transform.” |
| Supporting explanation | Name a mechanism, then describe its everyday effect with concrete nouns. | One or two sentences | “Track water and power at a glance, so nothing interrupts your trip.”<br>“A twin bed that lowers by night and disappears by day.” |
| Primary action | Direct, low-friction verb; reserve personal language for configuration. | 1–4 words | “Register”<br>“Customize now”<br>“Open Positions” |
| Belief statement | Plain first-person conviction, without inflated corporate abstractions. | 3–12 words | “We are optimists.” |

**Words and phrasing to use:** built; engineered; explore; effortless; freedom; comfort; your way; designed to; at a glance

**Avoid:** disruptive ecosystem; next-gen synergy; unparalleled excellence; hustle; game-changing magic; excessive exclamation marks

**Rules:**

- Link technical nouns to a lived benefit in the same paragraph.
- Write headings as confident statements rather than strings of adjectives.
- Keep calls to action smaller and plainer than the aspirational headline.
- Use numbers only when substantiated and give the relevant unit or context.

## Do's and Don'ts

### Do

- Keep default hero and chapter display type at 72px, weight 400, line height 1 and -0.05em tracking.
- Maintain the 8px outer image perimeter and 12px rounded mask.
- Give image-led chapters about 150px of breathing room instead of boxing them in panels.
- Keep feature rails at 592×370px with 8px gutters and journal media at 392×245px.
- Use 14px sentence-case labels; make eyebrows bold and action labels regular.
- Repeat the faint crosshair pattern on the warm #f2efea invitation panel.
- Use black 40px pills for ordinary conversion and translucent dark pills over photography.
- Preserve the light footer with 22px primary link rows and 1px #d9d9d9 rules.

### Don't

- Do not apply bold weights to the 48–76px display hierarchy; its character comes from tight regular grotesk forms.
- Do not turn vermilion into the default page background or repeat it across every card.
- Do not add floating-card drop shadows; media frames and thin rules provide separation.
- Do not replace the 8px rail gutter with roomy 24–32px tile gutters.
- Do not restyle rounded 40px action pills as sharp rectangular enterprise buttons.
- Do not set body paragraphs at the same -0.05em tracking as display headings.
- Do not tint all technical imagery blue or add neon gradients; stages stay pale and photographic.
- Do not use a dark mega-footer to finish a primarily white story.

## Motion and responsive

### Motion

**Observed:**

- Buttons declare color .15s and background-color .15s transitions; navigation glass declares background-color .3s and backdrop-filter .3s.
- Scroll-reveal elements declare transform and opacity over 1.8s with cubic-bezier(0,1,.4,1).
- Repeated text rails declare rail 15s linear infinite.
- Image stacks use sticky positioning and clipped rounded cards; the product finale uses a sticky expanding aperture.
- Focus-visible outlines use #fa5c40, 10px auto outlines; offsets are 5px on ordinary actions, -4px within navigation and 2px on accordions.

**Transfer:**

- Keep long scroll scenes focused on one visual transformation, such as an image stack or aperture expansion, rather than animating every card independently.
- Use the declared slow linear rail for a repeated short belief line only in a matching editorial image scene.

**Unknown:**

- Exact scroll interpolation, video playback logic and animation triggers are not established.
- Hover color endpoints are not established for most buttons.

### Responsive

**Observed:**

- The root size follows clamp(1rem, 0.6604rem + 0.3774vw, 1.25rem), so rem-based recipes vary with viewport width.
- Declared width breakpoints include 340, 500, 616, 700, 1000, 1200, 1400, 1440, 1600, 1800, 2000 and 2400px.

**Transfer:**

- On narrow layouts, retain the thin outer media margin and original regular-weight type relationships; scale the word sculpture as a width-fitted graphic.
- Let carousel cards remain a readable horizontal rail with a next-card cue rather than collapsing into an unrelated icon grid.
- Stack editorial and newsletter columns, placing the image and form in a clear reading sequence; preserve the distinct cream patterned band.

**Unknown:**

- Mobile compositions, exact breakpoint-specific typography and menu expansion behavior are not established.

## How to use this guide

1. Start from the Essentials and the first-screen recipe; where the guide offers variants, use the default named for a new marketing page.
2. Plan the page before building: map your content onto the section recipes and page flow, then check the plan against the Do's and Don'ts.
3. Build with the tokens and component specs; recreate signature graphics with their build recipes instead of generic decoration, and use the named font substitutes if a font is unavailable.
4. Render the page at desktop and mobile widths, compare it with the Essentials and the Don'ts, and fix the differences before you finish.
